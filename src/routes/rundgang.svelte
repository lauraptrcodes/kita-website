<script>
    import Textblock from "./textblock.svelte";
</script>

<div class="py-10">
    <div class="w-full text-center my-10 grid justify-items-center">
        <div class="mx-auto relative bg-[#04BF9D] w-[500px] h-[80px]">
            <h1 class="font-(family-name:--font-oi) text-white align-center mt-5 text-5xl"> Rundgang </h1>
        </div>
    </div>

    <div class="p-8 w-full grid justify-center divide-[#cccccc] space-y-4">

        <div class="grid grid-flow-col space-x-8 justify-center pb-16">
            <img src="/images/bewegung1.jpg" alt="Bewegungsraum" class="h-128"/>
            <img src="/images/bewegung2.jpg" alt="Bewegungsraum" class="h-128"/>
        </div>

        <div class="space-y-16">
        <Textblock category="Bewegungs- und Funktions- räume" orientation="left">
                <p class="font-bold">Raumwahrnehmung und Atmosphäre:</p>
                <ul class="list-disc">
                    <li>
                        Raum wirkt offen, lichtdurchflutet und aufgeräumt
                    </li>
                    <li>
                        große Fenster geben Sicht nach draußen, lassen Tageslicht herein –> wirkt beruhigend und einladend
                    </li>
                    <li>
                        vielfältige Ausstattung, vielseitig nutzbar –> Bsp.: Matten, Trommeln, Reifen, Spielhöhle
                    </li>
                    <li>
                        viel Potenzial zur Selbstgestaltung durch Kinder
                    </li>
                </ul>
        </Textblock>
        <Textblock category="Bildungs- perspektive" orientation="right">
                <p class="font-bold">Bewegungslernen</p>
                <ul class="list-disc">
                    <li>
                        Raum erlaubt freie Bewegung, Grobmotorik, Koordination –> wichtig für kognitive und emotionale Entwicklung
                    </li>
                </ul>
                <br>
                <p class="font-bold">Kreatives Spiel und Rollenspiel</p>
                <ul class="list-disc">
                    <li>
                        vorhandene Requisiten (Zelt, Instrumente) fördern fantasievolles Spiel
                    </li>
                </ul>
                <br>
                <p class="font-bold">soziales Lernen</p>
                <ul class="list-disc">
                    <li>
                        gemeinsames Spielen erfordert Aushandlungsprozesse –> Kooperationsfähigkeit, Konfliktbewältigung
                    </li>
                </ul>
                <br>
                <p class="font-bold">Exploration und Selbstwirksamkeit</p>
                <ul class="list-disc">
                    <li>
                        Kinder können Entscheidungen treffen
                    </li>
                    <li>
                        Wo spiele ich? Womit? –> zentraler Aspekt für kindliches Lernen
                    </li>
                </ul>
        </Textblock>
        <div class="w-full text-center p-4 grid justify-items-center mb-32">
            <h1 class="text-[#F27457] text-6xl font-bold">Reflexion </h1>
            <p class="max-w-lg mt-8">
                Die Ausstattung im Raum ermöglicht durch Flexibilität und Offenheit vielfältige Lernformen: Bewegung, Ausdruck,
                Gruppenerfahrung, Selbststeuerung –> wesentliche Bestandteile frühkindlicher Bildungsprozesse
            </p>
        </div>
        <div class="grid grid-flow-col space-x-8 justify-center mt-16 mb-16">
            <img src="/images/toilettenraum1.jpg" alt="Bewegungsraum" class="h-64"/>
            <img src="/images/toilettenraum2.jpg" alt="Bewegungsraum" class="h-64"/>
            <img src="/images/toilettenraum3.jpg" alt="Bewegungsraum" class="h-64"/>
        </div>
        <Textblock category="Toiletten- raum" orientation="left">
            <p class="font-bold">Raumwahrnehmung und Atmosphäre</p>
            <ul class="list-disc">
                <li>
                    Raum wirkt klar strukturiert, hell und funktional –> durch große Lichtpaneele und saubere Fliesen
                </li>
                <li>
                    bunte Fliesenbordüre (rot, blau, gelb, grün) und personalisierte Bilder am Waschbecken schaffen spielerische
                    Farbakzente –> kindgerechte Wirkung            
                </li> 
            </ul>
        </Textblock>
        <Textblock category="Bildungs- perspektive" orientation="right">
                <p class="font-bold">Selbstständigkeit fördern</p>
                <ul class="list-disc">
                    <li>
                        runde Waschinsel, optimal auf Kinderhöhe
                    </li>
                    <li>
                        können gleichzeitig und selbstständig Hände waschen
                    </li>
                </ul>
                <br>
                <p class="font-bold">Soziales Lernen</p>
                <ul class="list-disc">
                    <li>
                        gemeinsames Waschen schafft informelle Interaktionen
                    </li>
                    <li>
                        kann auch Konfliktpotenzial darstellen (Platz, Wasserspiel)
                    </li>
                </ul>
                <br>
                <p class="font-bold">Körperbewusstsein</p>
                <ul class="list-disc">
                    <li>
                        Raum trägt zur Entwicklung von Hygiene-Routinen bei –> frühe Selbstfürsorge als Bildungselement
                    </li>
                </ul>
                <br>
                <p class="font-bold">Sichtbarkeit und Kontrolle</p>
                <ul class="list-disc">
                    <li>
                        offene Gestaltung mit Spiegeln –> erlaubt pädagogischem Personal visuelle Übersicht
                    </li>
                    <li>
                        könnte auch kindliche Privatsphäre einschränken
                    </li>
                </ul>
        </Textblock>
        <div class="w-full text-center grid justify-items-center">
            <h1 class="text-[#F27457] text-6xl font-bold">Reflexion </h1>
            <p class="max-w-lg mt-8">
                Die Gestaltung des Toilettenraums unterstützt Bildungsprozesse wie Selbstregulation, Routinenlernen und soziale
                Rücksichtnahme, jedoch in einem Spannungsfeld zwischen Kindgerechtigkeit und institutioneller Kontrolle.
            </p>
        </div>
        <div class="grid grid-flow-col space-x-8 justify-center mt-16 mb-16">
            <img src="/images/gruppenraum1.jpg" alt="Bewegungsraum" class="h-72"/>
            <img src="/images/gruppenraum2.jpg" alt="Bewegungsraum" class="h-72"/>
            <img src="/images/gruppenraum3.jpg" alt="Bewegungsraum" class="h-72"/>
        </div>
        <Textblock category="Gruppen- raum" orientation="left">
            <p class="font-bold">Raumwahrnehmung und Atmosphäre</p>
            <ul class="list-disc">
                <li>
                    Raum wirkt hell und freundlich durch die großen Fensterfronten, welche für viel Tageslicht sorgen
                </li>
                <li>
                    Strukturiert und übersichtlich -> Möblierung und Aufteilung der Flächen wirken klar gegliedert           
                </li> 
                <li>
                    Kindgerecht -> Möbel in Kinderhöhe, weiche Teppichflächen, leuchtende Farben und
                    ansprechende Dekorationen an den Wänden -> vermitteln warme und sichere
                    Umgebung           
                </li> 
                <li>
                    Die verwendeten Farben haben eine ausgleichende Wirkung, die sicher und beruhigend wirken           
                </li> 
                <li>
                    Wandgestaltungen mit geometrischen Formen, thematisch eingerichtete Spielbereiche und Dekorationen fördern die Neugier          
                </li> 
                <li>
                    Ordnung und Funktionalität -> klare Bereiche für bestimmte Aktivitäten helfen Kindern sich zu orientieren           
                </li> 
            </ul>
        </Textblock>
        <Textblock category="Bildungs- perspektive" orientation="right">
            <ul class="list-disc">
                <li>
                    Freies Spiel und Selbstwirksamkeit -> die verschiedenen Funktionsbereiche ermöglichen es den Kindern, 
                    sich je nach Interesse selbstständig Aktivitäten zu
                    suchen
                </li>
                <li>
                    Soziales Lernen -> Gruppentische, offene Regale und Spielflächen regen zur
                    Interaktion und Kooperation an
                </li>
                <li>
                    Symbolisches Spiel -> Küchenecke mit Puppenwagen zielt auf Rollenspiel ab
                </li>
                <li>
                    Kognitive und motorische Anregung -> geometrische Wanddekorationen und
                    greifbare Materialien sprechen verschiedene Entwicklungsbereiche an
                </li>
            </ul>
    </Textblock>
    <div class="w-full text-center grid justify-items-center">
        <h1 class="text-[#F27457] text-6xl font-bold">Reflexion </h1>
        <p class="max-w-lg mt-8">
            Die Raumgestaltung wirkt direkt auf das Lernverhalten der Kinder. Durch klare
            Strukturen, helle und freundliche Farben sowie funktional eingerichtete Spiel- und
            Rückzugsbereiche werden unterschiedliche Bildungsprozesse angeregt. Der Raum
            bietet Orientierung, fördert Selbstständigkeit und lädt zum explorativen Lernen ein.
            Die kindgerechte Anordnung von Materialien ermöglicht eigenständiges Handeln.
        </p>
    </div>
    <div class="grid grid-flow-col space-x-8 justify-center mt-16 mb-16">
        <img src="/images/u3gruppenraum1.jpg" alt="Bewegungsraum" class="h-72"/>
        <img src="/images/u3gruppenraum2.jpg" alt="Bewegungsraum" class="h-72"/>
    </div>
    <Textblock category="Ü3 Gruppen- raum" orientation="left">
        <p class="font-bold">Raumwahrnehmung und Atmosphäre</p>
        <ul class="list-disc">
            <li>
                Der Raum ist lichtdurchflutet durch große Fenster
            </li>
            <li>
                Die klare Strukturierung durch die Möbelanordnung schafft Übersichtlichkeit und Orientierung           
            </li> 
            <li>
                Unterschiedliche Funktionsbereiche sind klar erkennbar          
            </li> 
            <li>
                Warme Holzmaterialien und ein natürlicher Bodenbelag erzeugen eine wohnliche und beruhigende Wirkung          
            </li> 
            <li>
                Bunte Akzente bringen Lebendigkeit in den Raum, jedoch ohne überreizend zu wirken          
            </li> 
            <li>
                Die Verbindung nach außen stärkt das Gefühl von Weite und Naturverbundenheit           
            </li>
            <li>
                Der Raum wirkt insgesamt einladend, sicher und anregend           
            </li>  
        </ul>
    </Textblock>
    <Textblock category="Bildungs- perspektive" orientation="right">
        <ul class="list-disc">
            <li>
                Selbstständiges Arbeiten -> zugängliche Materialien und flexible Möbel
            </li>
            <li>
                Vielfältige Zonen regen unterschiedliche Lernformen an -> kooperativ, kreativ, ruhig
            </li>
            <li>
                Blick in das Außengelände kann für naturbezogene Bildungsangebote genutzt werden
            </li>
            <li>
                Raum begünstigt sowohl freies Spiel als auch gezielte Förderung
            </li>
        </ul>
    </Textblock>
    <div class="w-full text-center grid justify-items-center">
        <h1 class="text-[#F27457] text-6xl font-bold">Reflexion </h1>
        <p class="max-w-lg mt-8">
            Die Raumgestaltung beeinflusst Bildungsprozesse wesentlich. Durch Struktur,
            Materialität und offene Gestaltung werden Selbstständigkeit, Orientierung und
            kreative Lernprozesse gefördert. Der Raum wirkt aktiv als Lernumgebung und
            unterstützt die kindliche Entwicklung auf mehreren Ebenen.
        </p>
    </div>
    <div class="grid grid-flow-col space-x-8 justify-center mt-16 mb-16">
        <img src="/images/aussenbereich1.jpg" alt="Bewegungsraum" class="h-72"/>
        <img src="/images/aussenbereich2.jpg" alt="Bewegungsraum" class="h-72"/>
        <img src="/images/aussenbereich3.jpg" alt="Bewegungsraum" class="h-72"/>
    </div>
    <Textblock category="Außen- bereich" orientation="left">
        <p class="font-bold">Raumwahrnehmung und Atmosphäre</p>
        <ul class="list-disc">
            <li>
                <p class="font-bold">Naturnah & abwechslungsreich</p>
                Der Außenbereich wirkt durch die umgebenden Bäume sehr grün und
                naturnah.
                Die Mischung aus Wiesenflächen, Sandspielbereich, Holzspielgeräten und
                Sitzmöglichkeiten schafft verschiedene Zonen.
                Die große Schaukel, Holzstämme und Spielhäuschen regen unterschiedliche
                Arten von Spiel an.
            </li>
            <li>
                <p class="font-bold">Offen & einladend</p>
                Es gibt keine hohen Zäune, die den Blick einschränken – der Hof öffnet sich
                optisch in die Baumlandschaft.
                Die gelben Sitzgruppen und Holzbänke schaffen ein freundliches, fröhliches
                Bild.            
            </li> 
            <li>
                <p class="font-bold">Struktur & Orientierung</p>
                Die Anordnung ist übersichtlich: Sitzbereiche (Picknicktische, Bänke) sind klar
                von den Spielbereichen getrennt.
                Der Boden wechselt von gepflastert zu Rasen und Sand, was Orientierung
                erleichtert.          
            </li> 
            <li>
                <p class="font-bold">Beruhigend & anregend zugleich</p>
                Die Naturmaterialien (Holz, Baumstämme) und die Bäume erzeugen eine
                beruhigende Wirkung, während bunte Elemente wie die leuchtend gelbe
                Sitzgruppe fröhliche Akzente setzen.
                Die Kinder können zwischen Schatten- und Sonnenplätzen wählen.          
            </li> 
            <li>
                <p class="font-bold">Sinne werden angesprochen</p>
                Die unterschiedlichen Oberflächen (Sand, Holz, Gras) laden zum Tasten ein,
                die Naturgeräusche der Bäume wirken entspannend.
                Es entstehen vielfältige Sinneseindrücke.          
            </li> 
            <li>
                <p class="font-bold">Wechselspiel Mensch/Natur</p>
                Die Umgebung ist nicht nur gebaut, sondern integriert Natur bewusst: liegende
                Baumstämme regen Fantasie an (Balancieren, Klettern, Sitzen).        
            </li> 
        </ul>
    </Textblock>
    <Textblock category="Bildungs- perspektive" orientation="right">
        <ul class="list-disc">
            <li>
                <p class="font-bold">Freies Spiel & Selbstwirksamkeit</p>
                Kinder können selbst entscheiden, ob sie klettern, schaukeln, buddeln oder
                einfach sitzen möchten.
                Die offene Gestaltung unterstützt exploratives Handeln.
            </li>
            <li>
                <p class="font-bold">Soziales Lernen</p>
                Sitzbänke und Picknicktische fördern Begegnung, Kommunikation und
                gemeinsames Tun (z.B. Brotzeit im Freien).
            </li>
            <li>
                <p class="font-bold">Naturbezug & Bewegung</p>
                Der direkte Kontakt zu Pflanzen, Holz und Erde stärkt Naturverbundenheit.
                Vielfältige Bewegungsanreize (balancieren, schaukeln, rennen) fördern
                motorische Entwicklung.            
            </li>
            <li>
                <p class="font-bold">Ästhetische Bildung</p>
                Die Gestaltung lädt ein, Jahreszeiten zu beobachten (Blätter im Wind,
                Schattenmuster oder Tiergeräusche)
            </li>
        </ul>
    </Textblock>
    <div class="w-full text-center grid justify-items-center">
        <h1 class="text-[#F27457] text-6xl font-bold">Reflexion </h1>
        <p class="max-w-lg mt-8">
            Der Außenbereich wirkt als ganzheitlicher Bildungsraum: Er bietet Rückzugsorte,
            Platz für Bewegung, Naturerfahrungen und soziale Begegnungen. Die klare, aber
            offene Struktur unterstützt Kinder in ihrer Selbstständigkeit und ermutigt zu
            eigenständigem, forschendem Lernen.<br>
            Die Kombination aus Natur und gestalteten Elementen zeigt, wie gebauter Raum und
            gewachsene Umwelt ineinandergreifen. Um das Potenzial noch stärker zu nutzen,
            wäre es denkbar, die Bepflanzung und naturnahe Elemente weiter auszubauen oder
            kindgerechte Beete einzuführen, um ökologische Bildung zu fördern.
        </p>
    </div>

    <div class="grid grid-flow-col space-x-8 justify-center mt-16 mb-16">
        <img src="/images/schlafraum1.jpg" alt="Bewegungsraum" class="h-72"/>
        <img src="/images/schlafraum2.jpg" alt="Bewegungsraum" class="h-72"/>
        <img src="/images/schlafraum3.jpg" alt="Bewegungsraum" class="h-72"/>

    </div>
    <Textblock category="U3 Schlaf- raum" orientation="left">
        <p class="font-bold">Raumwahrnehmung und Atmosphäre</p>
        <ul class="list-disc">
            <li>
                Die Betten bestehen aus abwischbarem, weichem Material -> einfache Reinigung, keine Stoßgefahr
            </li>
            <li>
                Angebot verschiedener Schlafmöglichkeiten -> Bett, Körbchen, Bodenbett -> Orientierung an der Individualität und der Bedürfnisse der Kinder           
            </li> 
            <li>
                Die Kinder schlafen in Schlafsäcken und nicht mit Decken -> Verhinderung von Strangulierungs- oder Erstickungsgefahr          
            </li> 
            <li>
                Der Raum kann abgedunkelt werden, wobei er nicht vollständig verdunkelt wird -> Wahrung der Aufsichtspflicht, Sicherheit und Geborgenheit der Kinder durch möglichen Blickkontakt zur Bezugsperson          
            </li> 
            <li>
                Ruhiges Ambiente durch Lichtspiel und gedeckte Farben          
            </li> 
        </ul>
    </Textblock>
    <Textblock category="Bildungs- perspektive" orientation="right">
        <ul class="list-disc">
            <li>
                Ruhiges Ambiente durch Lichtspiel und gedeckte Farben <br>
                -> Förderung der Selbstständigkeit und ebenso der Sicherheit im Brandfall <br>
                -> Schutz der pädagogischen Fachkräfte, da nicht jedes Kind in eine Krippe gehoben
                werden muss
            </li>
            <li>
                Ruhemöglichkeit um altersgerecht den Wechsel zwischen Anspannung und Entspannung zu ermöglichen
            </li>
            <li>
                Geborgenheit, Ruhe und Entspannung erfahren als Kind -> Prävention, Gesunderhaltung
            </li>
            <li>
                Kennenlernen von Ritualen: z.B. Vorlesen von Büchern -> Sprachbildung
            </li>
        </ul>
    </Textblock>
    <div class="w-full text-center grid justify-items-center">
        <h1 class="text-[#F27457] text-6xl font-bold">Reflexion </h1>
        <p class="max-w-lg mt-8">
            Selbst der Schlafraum, in dem scheinbar keine „aktive“ Bildung stattindet, hat erhebliche
            Ausmaße in seiner Gestaltung auf den Bildungsprozess des gesamten Tages. Die Erfüllung
            von Grundbedürfnissen kann nur in einem Raum und mit dessen Ausstattung gewährleistet
            sein, der sich genau nach dessen Funktionsweise ausrichtet.
        </p>
    </div>

    <div class="grid grid-flow-col space-x-8 justify-center mt-16 mb-16">
        <img src="/images/krippenbereich1.jpg" alt="Bewegungsraum" class="h-72"/>
        <img src="/images/krippenbereich2.jpg" alt="Bewegungsraum" class="h-72"/>
    </div>
    <Textblock category="Krippen- bereich" orientation="left">
        <p class="font-bold">Raumwahrnehmung und Atmosphäre</p>
        <ul class="list-disc">
            <li>
                Betreuung von Kindern ab 12 Monaten bis zum dri8en Geburtstag            
            </li>
            <li>
                Der Raum wirkt recht „leer“ <br>
                -> offene Gestaltung je nach Bedarf der Kinder/der Gruppe <br>
                -> hoher Bewegungsdrang von Kindern unter drei Jahren <br>
                -> keine Reizüberforderung         
            </li> 
            <li>
                Mobiliar auf Kinderhöhe <br>
                -> Tische und Stühle tatsächlich auf höhe der Kleinkinder, so dass selbstständiges
                Sitzen geübt werden kann (keine Hochstühle) <br>
                -> zum Schutz der pädagogischen FachkräRe: Erzieherstühle, die höhenverstellbar
                sind <br>
                -> ebenso Fenster auf Kinderhöhe <br>
                -> Poraolioordner (Entwicklungstagebuche) ebenfalls frei zugänglich
            </li> 
            <li>
                Höhlen und Versteckmöglichkeiten <br>
                -> Rückzugsorte <br>
                -> Ruhezonen
            </li> 
            <li>
                Teppiche <br>
                -> viel Spiel auf dem Boden <br>
                -> Krabbelkinder
            </li> 
            <li>
                Überwiegend sensorisches Spielmaterial <br>
                -> U-3-Kinder in oraler und taktiler Phase
            </li> 
        </ul>
    </Textblock>
    <Textblock category="Bildungs- perspektive" orientation="right">
        <ul class="list-disc">
            <li>
                OrienFerung an den Bedürfnissen von U-3-Kindern
            </li>
            <li>
                -> freies Spiel durch wenig stark vorgebendes Material
            </li>
            <li>
                -> Wechsel von An- und Entspannung           
            </li>
            <li>
                -> Autonomie und Selbstwirksamkeit
            </li>
            <li>
                -> Erkundung mit dem ganzen Körper
            </li>
        </ul>
    </Textblock>
    <div class="w-full text-center grid justify-items-center">
        <h1 class="text-[#F27457] text-6xl font-bold">Reflexion </h1>
        <p class="max-w-lg mt-8">
            Der U-3-Bereich ist exakt auf diese Altersstufe zugeschni8en. Durch entsprechendes
            Mobiliar und Spielmaterial aus „Kinderperspektive“/auf Kinderhöhe wird ein
            Bildungsraum für Kleinkinder geschaffen, in dem sie sich als selbstständige Menschen
            erleben und frei entfalten können. Der Raum hält die Balance zwischen den
            Anforderungen an einen gesunden Arbeitsplatz und den Voraussetzungen eines
            Raumes für jüngere Kinder.
        </p>
    </div>

    </div>
    </div>

</div>