<template>
    <main>
        <h2>Le mie spese</h2> <!--prima sezione di main-->
            <table> <!--inizio tabella-->
                <thead>
                    <tr>
                        <th>Numero</th>
                        <th>Descrizione</th>
                        <th>Costo</th>
                    </tr> <!--Fine prima riga della colonna-->
                </thead>
                <tbody>
                    <tr>
                        <td> 1 </td>
                        <td> Biglietto aereo </td>
                        <td> &euro;120 </td>
                    </tr>
                    <tr>
                        <td> 1 </td>
                        <td> Biglietto aereo </td>
                        <td> &euro;120 </td>
                    </tr>
                    <tr>
                        <td> 1 </td>
                        <td> Biglietto aereo </td>
                        <td> &euro;120 </td>
                    </tr>
                </tbody> <!--fine corpo della tabella-->
                <tfoot>
                    <tr>
                        <td colspan="2">Totale</td>
                        <td>&euro;360</td>
                    </tr>
                </tfoot>
            </table> <!--fine tabella-->
        </section>
        <hr>

        <h3>Cose da fare</h3> <!--seconda sezione di main-->
        <ul>
            <li>Visitare la Tower of London &cross;</li>
            <li>Visitare Greenwich &#10003;</li>
            <li>Ascoltare un artista di strada a Covent Garden &#10003;</li>
            <li>Mangiare il tipico Fish&Chips inglese &cross;</li>
        </ul>
        <hr>

        <h3>Info utili</h3>
        <ol>
            <li><span>Numeri utili di emergenza</span>
                <ul>
                    <li> <strong>999</strong> - Emergenze</li>
                    <li> <strong>101</strong> - Numero Polizia</li>
                    <li> <strong>111</strong> - Numero assistenza medica</li>
                </ul>
            </li>
            <li><span>Hotel</span>
                <ul>
                    <li> <strong>Nome hotel</strong>: Buckingham Palace</li>
                    <li> <strong>Indirizzo hotel</strong>: Wesrminster, London SW1A1AA, Regno Unito</li>
                </ul>
            </li>
            <li><span>Aereo</span>
                <ul>
                    <li><strong>Volo di andata</strong> :Y1234X, ore 9.30 da Milano Malpensa</li>
                    <li><strong>Volo di ritorno</strong> :Y1236X, ore 18.30 da London Heathrow</li>
                </ul>
            </li>
        </ol>
        <hr> <!--fine main-->
    </main>
</template>

<script>
    export default {
        name: 'MainComponent'
    }
</script>

<style lang="scss" scoped>

</style>