# Nyttige tips & tricks

Disclaimer: Det er ikke nødvendigvis et mål å bli megaeffektiv på kodeskrivingsfronten, for det er som oftest ikke der utfordringene ligger. Som regel bruker man mye mer tid på å tenke på løsninger enn den faktiske implementasjonen, så se på disse tipsene som noen måter man kan ha det mer moro mens man faktisk implementerer tankene man har brukt tid på å løse 🤓

## Editorshortcuts

Vi kommer til å ta utgangspunkt i Visual Studio Code, men shortcutsene og tankene er så klart overførbare til enhver ordentlig editor (les. IntelliJ, Vim osv).

Alle disse kan endres ved å åpne shortcuts-menyen – by default kan denne åpnes med <kbd>Cmd</kbd> <kbd>K</kbd> → <kbd>Cmd</kbd> <kbd>S</kbd>, eller ved å kjøre kommandoen _Preferences: Open Keyboard Shortcuts_ – du åpner kommandomenyen med <kbd>Cmd</kbd> <kbd>Shift</kbd> <kbd>P</kbd>.

<table>

<tr>
<td>

### Go to file

Lister opp alle filene i prosjektet og lar deg søke i disse. Åpner filen du velger.

<table>
    <thead>
        <tr>
            <th></th>
            <th>Keybinding</th>
        </tr>
    </thead>
    <tbody>
        <tr>
            <td>Default</td>
            <td><kbd>Cmd</kbd> <kbd>P</kbd></td>
        </tr>
    </tbody>
</table>
</td>
<td>

![Go to file](/images/go_to_file.gif)

</td>
</tr>

<tr>
<td>

### Commands

Lister opp alle mulige kommandoer i VS Code, og lar deg søke i disse. Kjører den kommandoen du velger. Her kan du gjøre mer eller mindre alt VS Code lar deg gjøre. Denne er veldig nyttig for ting du ikke bruker så ofte at du orker å sette opp en keybind, og for å sjekke hva som i det hele tatt er mulig.

Kommandoer jeg ofte bruker er _File: Save without formatting_ og _Preferences: Color Theme_ (for å endre fargetema f.eks. når jeg deler skjerm). Noen andre kule og nyttige kommandoer er _Sort lines Ascending/Descending_ og _Transform to Uppercase/Lowercase/Kebab Case/Title Case_.

<table>
    <thead>
        <tr>
            <th></th>
            <th>Keybinding</th>
        </tr>
    </thead>
    <tbody>
        <tr>
            <td>Default</td>
            <td><kbd>Cmd</kbd> <kbd>Shift</kbd> <kbd>P</kbd></td>
        </tr>
    </tbody>
</table>
</td>
<td>

![Commands](/images/commands.gif)

</td>
</tr>

<tr>
<td>

### Hover

Viser informasjon om det som er under cursoren.

I VS Code finnes det både `Show Hover` og `Show Definition Preview Hover`. Jeg foretrekker å bruke `Show Definition Preview Hover`, siden den gir litt mer info.

<table>
    <thead>
        <tr>
            <th></th>
            <th>Keybinding</th>
        </tr>
    </thead>
    <tbody>
        <tr>
            <td>Default</td>
            <td><kbd>Cmd</kbd> <kbd>K</kbd> → <kbd>Cmd</kbd> <kbd>I</kbd></td>
        </tr>
        <tr>
            <td>Foreslått</td>
            <td><kbd>Ctrl</kbd> <kbd>K</kbd></td>
        </tr>
    </tbody>
</table>
</td>
<td>

![Show Definition Preview Hover](/images/hover_definition.gif)

</td>
</tr>

<tr>
<td>

### Quick fix

Vis forslagene editoren har om det som er under cursoren. Editoren har ofte gode forslag til ting du kan gjøre, enten det er for å rette opp i feil, eller bare potensielle forbedringer. Dette kan f.eks. være å importere noe du har glemt å importere, eller å fjerne ubrukt kode.

<table>
    <thead>
        <tr>
            <th></th>
            <th>Keybinding</th>
        </tr>
    </thead>
    <tbody>
        <tr>
            <td>Default</td>
            <td><kbd>Cmd</kbd> <kbd>.</kbd></td>
        </tr>
    </tbody>
</table>
</td>
<td>

![Trigger suggest](/images/quick_fix.gif)

</td>
</tr>

<tr>
<td>

### Rename Symbol

Endrer navet på symbolet der det er definert og alle steder det er brukt.

<table>
    <thead>
        <tr>
            <th></th>
            <th>Keybinding</th>
        </tr>
    </thead>
    <tbody>
        <tr>
            <td>Default</td>
            <td><kbd>F2</kbd></td>
        </tr>
        <tr>
            <td>Foreslått</td>
            <td><kbd>Cmd</kbd> <kbd>Shift</kbd> <kbd>2</kbd></td>
        </tr>
    </tbody>
</table>
</td>
<td>

![Rename](/images/rename.gif)

</td>
</tr>

<tr>
<td>

### Go to symbol

Lister opp alle symbolene i filen og går til det symbolet du velger.

<table>
    <thead>
        <tr>
            <th></th>
            <th>Keybinding</th>
        </tr>
    </thead>
    <tbody>
        <tr>
            <td>Default</td>
            <td><kbd>Cmd</kbd> <kbd>Shift</kbd> <kbd>O</kbd></td>
        </tr>
    </tbody>
</table>
</td>
<td>

![Go to symbol](/images/go_to_symbol.gif)

</td>
</tr>

<tr>
<td>

### Go to definition

Går til definisjonen av det som er under cursoren. Denne er nyttig å bruke for å gå til f.eks. der en variabel eller type er definert.

<table>
    <thead>
        <tr>
            <th></th>
            <th>Keybinding</th>
        </tr>
    </thead>
    <tbody>
        <tr>
            <td>Default</td>
            <td><kbd>F12</kbd></td>
        </tr>
        <tr>
            <td>Foreslått</td>
            <td><kbd>Cmd</kbd> <kbd>Shift</kbd> <kbd>D</kbd></td>
        </tr>
    </tbody>
</table>
</td>
<td>

![Go to definition](/images/go_to_definition.gif)

</td>
</tr>

<tr>
<td>

### Go to references

Lister opp alle steder det som er under cursoren er brukt. Denne er nyttig for å finne alle stedene en variabel eller type er brukt, og om den i det hele tatt er brukt.

<table>
    <thead>
        <tr>
            <th></th>
            <th>Keybinding</th>
        </tr>
    </thead>
    <tbody>
        <tr>
            <td>Default</td>
            <td><kbd>Shift</kbd> <kbd>F12</kbd></td>
        </tr>
        <tr>
            <td>Foreslått</td>
            <td><kbd>Cmd</kbd> <kbd>Shift</kbd> <kbd>R</kbd></td>
        </tr>
    </tbody>
</table>
</td>
<td>

![Go to references](/images/go_to_references.gif)

</td>
</tr>

<tr>
<td>

### Go Back/Forward

Går til neste/forrige sted du var i editoren, lignende frem/tilbake i nettleseren. Denne er nyttig å bruke etter du f.eks. har gått til definisjonen av en variabel eller type, og ønsker å gå tilbake til der du var.

Demovideoen viser at man går til definisjonen av en type, og så bruker _Go Back_ for å komme seg tilbake til der man var, og så bruker _Go Forward_ for å komme tilbake til definisjonen igjen.

#### Go Back

<table>
    <thead>
        <tr>
            <th></th>
            <th>Keybinding</th>
        </tr>
    </thead>
    <tbody>
        <tr>
            <td>Default</td>
            <td><kbd>Ctrl</kbd> <kbd>-</kbd></td>
        </tr>
        <tr>
            <td>Foreslått</td>
            <td><kbd>Ctrl</kbd> <kbd>O</kbd></td>
        </tr>
    </tbody>
</table>

#### Go Forward

<table>
    <thead>
        <tr>
            <th></th>
            <th>Keybinding</th>
        </tr>
    </thead>
    <tbody>
        <tr>
            <td>Default</td>
            <td><kbd>Ctrl</kbd> <kbd>Shift</kbd> <kbd>-</kbd></td>
        </tr>
        <tr>
            <td>Foreslått</td>
            <td><kbd>Ctrl</kbd> <kbd>I</kbd></td>
        </tr>
    </tbody>
</table>
</td>
<td>

![Go back/forward](/images/go_back.gif)

</td>
</tr>

<tr>
<td>

### Go to Next/Previous Problem

Hopper til neste/forrige sted editoren har oppdaget en feil/advarsel. Herfra kan man så klart også prøve seg på en _Quick Fix_, eller bare fikse feilen manuelt.

Man kan også velge mellom _Go to Next/Previous Problem_ og _Go to Next/Previous Problem in Files_ – hvor den første kun går mellom advarslene i filen du er i, mens den andre går mellom alle advarslene i prosjektet.

#### Go to Next Problem

<table>
    <thead>
        <tr>
            <th></th>
            <th>Keybinding</th>
        </tr>
    </thead>
    <tbody>
        <tr>
            <td>Default</td>
            <td><kbd>Shift</kbd> <kbd>F9</kbd></td>
        </tr>
        <tr>
            <td>Foreslått</td>
            <td><kbd>Cmd</kbd> <kbd>Shift</kbd> <kbd>9</kbd></td>
        </tr>
    </tbody>
</table>

#### Go to Previous Problem

<table>
    <thead>
        <tr>
            <th></th>
            <th>Keybinding</th>
        </tr>
    </thead>
    <tbody>
        <tr>
            <td>Default</td>
            <td><kbd>Shift</kbd> <kbd>F8</kbd></td>
        </tr>
        <tr>
            <td>Foreslått</td>
            <td><kbd>Cmd</kbd> <kbd>Shift</kbd> <kbd>8</kbd></td>
        </tr>
    </tbody>
</table>
</td>
<td>

![Go to problem](/images/go_to_problem.gif)

</td>
</tr>

<tr>
<td>

### Go to Next/Previous Change

Hopper til neste/forrige sted det har blitt gjort en kodeendring – krever at prosjektet bruker git til versjonshåndtering.

#### Go to Next Change

<table>
    <thead>
        <tr>
            <th></th>
            <th>Keybinding</th>
        </tr>
    </thead>
    <tbody>
        <tr>
            <td>Default</td>
            <td><kbd>Option</kbd> <kbd>F5</kbd></td>
        </tr>
        <tr>
            <td>Foreslått</td>
            <td><kbd>Cmd</kbd> <kbd>Shift</kbd> <kbd>0</kbd></td>
        </tr>
    </tbody>
</table>

#### Go to Previous Change

<table>
    <thead>
        <tr>
            <th></th>
            <th>Keybinding</th>
        </tr>
    </thead>
    <tbody>
        <tr>
            <td>Default</td>
            <td><kbd>Option</kbd> <kbd>Shift</kbd> <kbd>F5</kbd></td>
        </tr>
        <tr>
            <td>Foreslått</td>
            <td><kbd>Cmd</kbd> <kbd>Shift</kbd> <kbd>7</kbd></td>
        </tr>
    </tbody>
</table>
</td>
<td>

![Go to change](/images/go_to_change.gif)

</td>
</tr>

<tr>
<td>

### Add Cursor Above/Below

Legger til en ny cursor. Denne er nyttig når du f.eks. skal gjøre samme endring på flere linjer som er ganske like.

#### Add Cursor Above

<table>
    <thead>
        <tr>
            <th></th>
            <th>Keybinding</th>
        </tr>
    </thead>
    <tbody>
        <tr>
            <td>Default</td>
            <td><kbd>Option</kbd> <kbd>Cmd</kbd> <kbd>↑</kbd></td>
        </tr>
    </tbody>
</table>

#### Add Cursor Below

<table>
    <thead>
        <tr>
            <th></th>
            <th>Keybinding</th>
        </tr>
    </thead>
    <tbody>
        <tr>
            <td>Default</td>
            <td><kbd>Option</kbd> <kbd>Cmd</kbd> <kbd>↓</kbd></td>
        </tr>
    </tbody>
</table>

</td>
<td>

![Add cursor](/images/add_cursor.gif)

</td>
</tr>

<tr>
<td>

### Add Selection to Next Find Match

Markerer ordet du er på om det ikke er markert – dersom hele ordet og spawner en ny cursor på neste sted som matcher teksten markert. Dette kan brukes for å spawne nye cursors på gjentagende ord.

Brukes for eksempel om du vil gjøre om på et ord som brukes flere steder.

<table>
    <thead>
        <tr>
            <th></th>
            <th>Keybinding</th>
        </tr>
    </thead>
    <tbody>
        <tr>
            <td>Default</td>
            <td><kbd>Cmd</kbd> <kbd>D</kbd></td>
        </tr>
    </tbody>
</table>

</td>
<td>

![Go to change](/images/add_selection_to_next_find_match.gif)

</td>
</tr>

</tbody>
</table>

<!-- ### Åpne terminal

Bør bindes til

```
    {
        "key": "cmd+j",
        "command": "workbench.action.terminal.focus",
        "when": "!terminalFocus"
    },
``` -->

<!-- ### Go to next/previous hunk

Hopper til neste/forrige sted det har blitt gjort en kodeendring – krever at prosjektet bruker git til versjonshåndtering. -->

<!-- ### Stage hunk

En hunk er en sammenhengende endring i en fil. Legger til hunkensom er under cursoren til endringene som skal med i neste commit. Du stager med andre ord hunken. Denne er nyttig når du har gjort flere endringer i en fil, men kun ønsker å commite noen av disse endringene. -->

<!-- ### Preview hunk

En hunk er en sammenhengende endring i en fil. Viser endringene som er gjort i hunken under cursoren. -->

## Oppsett av Mac'en

<table>

<tr>
<td>

### Endre Caps Lock til noe nyttig

Hvor ofte bruker du egentlig <kbd>Caps Lock</kbd>? Selve knappen ligger jo perfekt plassert for venstre lillefinger, så det er synd at den ikke blir mer brukt. Heldigvis kan man enkelt endre hva den knappen gjør 🤯

Personlig synes jeg det er nice å binde den til enten <kbd>Esc</kbd> eller <kbd>Ctrl</kbd> (eller en kombo av disse – men mer om det senere), men du får nesten bare teste ut hva du foretrekker – det viktigste er at binder den til noe du får bruk for, enten det er <kbd>Caps Lock</kbd>, <kbd>Esc</kbd>, <kbd>Ctrl</kbd> eller noe annet 🤷‍♂️

Om du skulle ønske du kunne gjøre mer – som f.eks. å binde et klikk på <kbd>Caps Lock</kbd> til å resultere i <kbd>Esc</kbd>, men hvis du holder <kbd>Caps Lock</kbd> nede, så resulterer det i at <kbd>Ctrl</kbd> blir holdt nede, så bør du sjekke ut [_Karabiner Elements_](https://karabiner-elements.pqrs.org/docs/), som tillater all mulig slags herjing.

Jeg har blant annet satt opp at et klikk på <kbd>Space</kbd> sender <kbd>Space</kbd>, men hvis jeg holder den nede, så er det det samme som å holde <kbd>Fn</kbd> nede. Og så har jeg satt opp at dersom jeg trykker på <kbd>Fn</kbd> <kbd>H</kbd>/<kbd>J</kbd>/<kbd>K</kbd>/<kbd>L</kbd>, så sender det <kbd>←</kbd>/<kbd>↓</kbd>/<kbd>↑</kbd>/<kbd>→</kbd> – jeg får med andre ord Vim-pilnavigasjon når jeg holder nede <kbd>Space</kbd> 🤓

</td>
<td>

![Endre Caps Lock](/images/caps_lock.gif)

</td>
</tr>

<tr>
<td>

### Skru av Spaces-omrokkering

Spaces, altså de virtuelle desktop'ene på macOS, er meganice for å unngå alt for mye rot når man veksler mellom programmer. Problemet er bare at macOS by default omrokkerer på hvor hvilket Space ligger basert på hva du nylig har brukt

Det vil si at dersom du har et Space med Google Chrome, et med VS Code og et med Figma, og du har eksplisitt sortert disse i den rekkfølgen, fra venstre. Om du sitter i VS Code og smeller inn en <kbd>Option</kbd> <kbd>Tab</kbd> for å komme deg til Figma, så vil ikke nødvendigvis et venstreswipe føre deg tilbake til Figma.

Heldigvis kan denne omrokkeringen skrus av, slik at du alltid har kontroll på hvor hvilke Spaces ligger i forhold til hverandre 💆‍♂️

</td>
<td>

![Spaces](/images/spaces.gif)

</td>
</tr>

<tr>
<td>

### Start skjermspareren ved et sveip

Synes du også skjermsparerne til Mac er helt vanvittig vakre, men synes det er alt for tungvint å få startet den? Da kan Hot Corners være noe for deg!

Du kan få Mac'en til å starte skjermsparer (og låse maskinen i samme slengen) ved å flytte musepekeren til et av hjørnene – ganske nyttig om du vil forlate maskinen trygt og med stil når du skal ta deg en kaffe/et game foos ⚽️

</td>
<td>

![Hot corners](/images/hot_corners.gif)

</td>
</tr>

<tr>
<td>

### Fjern Dock'en

På Mac kan du alltid klikke <kbd>Cmd</kbd> <kbd>Space</kbd> for å få opp Spotlight Search, hvor du f.eks. kan skrive inn navn på programmet du ønsker å åpne. Dette kombinert med navigasjon på tvers av programmer med <kbd>Cmd</kbd> <kbd>Tab</kbd>, gjør at du mer eller mindre egentlig ikke trenger denne Dock'en på bunnen av skjermen – som bruker dyrebare pixler på å vise noen ikoner. Heldigvis kan man skjule den når man har programmer som overlapper 😋

</td>
<td>

![Dock](/images/dock.gif)

</td>
</tr>

<tr>
<td>

### Vinduflytting med Rectangle

Mac er helt ubrukelig når det kommer til Window Management. Heldigvis finnes det folk som tar ansvaret i sine egne hender. [_Rectangle_](https://rectangleapp.com/) er et program som enkelt lar deg endre størrelsen og flytte rundt på vinduene dine.

</td>
<td>

![Rectangle](/images/rectangle.gif)

</td>
</tr>

</table>

## Andre nyttige ting

### Aliaser

Om du henger mye i termisen (obvi terminalen), så er aliaser og funksjoner fort noe du bør ta en titt på!

Du kan enkelt legge til et alias ved å utvide `~/.zshrc`-filen din med f.eks.:

```bash
# aliaser
alias s='npm start'
alias ni='npm install'
alias nr='npm run'

alias g=git
alias ga='git add'
alias gc='git commit -v'
alias gl='git pull'
alias gp='git push'
alias gm='git merge'
alias gco='git checkout'
alias gcb='git checkout -b'
alias gcl='git clone --recurse-submodules'

# funksjoner
function c() {
    # åpner ~/.zshrc med vim og sourcer den etterpå
    vim ~/.zshrc && source ~/.zshrc
}
```

_[Oh My Zsh](https://ohmyz.sh/)_ mange meganice aliaser, spesielt for Git, så sjekk gjerne det ut. Noen av mine favoritter derfra er følgende (disse bruker variabler/funksjoner som blir definert av plugins):

```bash
alias gcm='git checkout $(git_main_branch)'
alias gpsup='git push --set-upstream origin $(current_branch)'
```

### Bruk av Vim / Neovim

Nå som du har blitt en råtass på navigasjon i VS Code, oppdager du kanskje at du savner noe bedre navigasjon rundt i selve teksten. Da kan jeg virkelig anbefale deg å sjekke ut Vim/Neovim, som er laget for akkurat dette.

Det er rimelig beinhardt å hoppe rett inn i Vim, for hele konseptet med at du har forskjellige modes (insert mode/normal mode osv.), er ganske annerledes fra vanlige editorer, som VS Code.

Ja, du har kanskje gjort noen endringer med Vim, og da åpnet du en fil, trykket <kbd>I</kbd> for å komme inn i insert mode, skrevet det du skulle, trykket <kbd>Esc</kbd> for å komme tilbake til normal mode, trykket <kbd>:</kbd> for å skrive inn kommandoen `wq` for å lagre og deretter lukke filen.

Det som fikk ting til å klikke litt for meg, er at alt med Vim handler om å lære seg grunnleggende navigasjon og så å bygge opp egne shortcuts. F.eks., så har jeg bundet <kbd>Ctrl</kbd> <kbd>S</kbd> til å fyre av kommandoen `:w`, altså at filen lagres. Det er kanskje uvant og rart at det ikke var sånn innebygd, men det gir deg også muligheten til å sette opp de keybindsa du selv ønsker og trenger.

Det første jeg anbefaler for å se om Vim kan være noe for deg, er å installere en Vim-plugin til favoritteditoren din, og så lære deg grunnleggende navigasjon ved enten dokumentasjonslesing, YouTube-titting eller hva enn som får geita di til å flyte 🐐

Jeg tror ikke dette er helt riktig sted å gå løs på en rask intro til Vim, men det ligger vel potensielt i kortene at det bør lages en eller annen gang.

![yehaw](/images/vscode_vim.jpeg)

– Si gjerne fra om du oppdager noe feil eller har noen tips/ønsker til noe mer innhold i denne lille lista! 🤠

<!-- <tr>
<td>

### Stage/Unstage Selected Ranges

En hunk er en sammenhengende endring i en fil. Legger til hunken som er under cursoren til endringene som skal med i neste commit. Du stager med andre ord hunken. Denne er nyttig når du har gjort flere endringer i en fil, men kun ønsker å commite noen av disse endringene.

Dessverre støtter tilsynelatende ikke VS Code direkte staging av hunken som er under cursoren, så vi må først markere de endringene vi vil legge til, og deretter bruke _Stage Selected Ranges_. Vi kan også fjerne en range ved å bruke _Unstage Selected Ranges_.

#### Stage Selected Ranges

<table>
    <thead>
        <tr>
            <th></th>
            <th>Keybinding</th>
        </tr>
    </thead>
    <tbody>
        <tr>
            <td>Default</td>
            <td><kbd>Cmd</kbd> <kbd>K</kbd> → <kbd>Option</kbd> <kbd>Cmd</kbd> <kbd>S</kbd></td>
        </tr>
        <tr>
            <td>Foreslått</td>
            <td><kbd>Cmd</kbd> <kbd>Shift</kbd> <kbd>A</kbd></td>
        </tr>
    </tbody>
</table>

#### Unstage Selected Ranges

<table>
    <thead>
        <tr>
            <th></th>
            <th>Keybinding</th>
        </tr>
    </thead>
    <tbody>
        <tr>
            <td>Default</td>
            <td><kbd>Cmd</kbd> <kbd>K</kbd> → <kbd>Cmd</kbd> <kbd>N</kbd></td>
        </tr>
        <tr>
            <td>Foreslått</td>
            <td><kbd>Cmd</kbd> <kbd>Shift</kbd> <kbd>U</kbd></td>
        </tr>
    </tbody>
</table>
</td>
<td>

![Stage/Unstage selected ranges](/images/stage.gif)

</td>
</tr> -->
