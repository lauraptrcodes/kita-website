<script>
    import Textblock from "./textblock.svelte";
</script>

<div class="py-10">
    <div class="w-full text-center my-10 grid justify-items-center">
        <div class="mx-auto relative bg-[#04BF9D] w-[300px] h-[80px]">
            <h1 class="text-white align-center mt-2 text-5xl font-bold"> Rundgang </h1>
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
    </div>
    </div>

</div>