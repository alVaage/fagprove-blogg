# Testrapport

### Plan for testing
- Utføre en grundig gjennomgang av alle hovedfunksjonene, dokumenter hver funksjon, skrive inn test resultatene, inkludere relevante bilder og beskrive hvordan feilen skal utbedres

<table>
    <tr>
      <th>Funksjoner</th>
      <th>Beskrivelse</th>
      <th>Resultat</th>
      <th>Bilder</th>
      <th>Eventuelle utbedringer</th>
      <th>Status</th>
    </tr>
    <tr>
      <td>Opprettelse av nye innlegg</td>
      <td>Skal kunne lage nye innlegg med tittel, forskjellig type innhold og kategorier</td>
      <td>Fungerer. Farging av tekst og emojier fungerer ikke, dette skyldes stylingen som overskriver</td>
      <td> 
        <table>
          <th><img src="https://github.com/ArvidWedtstein/Fagproove/assets/71834553/acb438a5-a793-4f75-88a7-118c1f6c3aaf" width="60" /></th>
          <th><img src="https://github.com/ArvidWedtstein/Fagproove/assets/71834553/6625344b-fbda-4b62-a1a3-906f02d796a3" width="60" /></th>
        </table>
      </td>
      <td>Se på hvordan man kan påvirke bare tekst som ikke har en farge-styling. Sørg for at kun de ønskede SVG-ene blir påvirket av transformen</td>
      <td>🟢Fungerer med mindre avvik (ikke fikset)</td>
    </tr>
    <tr>
      <td>Redigering av innlegg</td>
      <td>Skal kunne redigere innhold, tittel og endre kategorier</td>
      <td>Alt fungerer som det skal. Editoren kan strekke seg over lagre- og avbryt-knappene.</td>
      <td> 
        <table>
          <th><img src="https://github.com/ArvidWedtstein/Fagproove/assets/71834553/acb438a5-a793-4f75-88a7-118c1f6c3aaf" width="60" /></th>
          <th><img src="https://github.com/ArvidWedtstein/Fagproove/assets/71834553/6625344b-fbda-4b62-a1a3-906f02d796a3" width="60" /></th>
        </table>
      </td>
      <td>Legg til en funksjon som sikrer at lagre-knappene er synlige</td>
      <td>🟢Fungerer med mindre avvik (ikke fikset)</td>        
    </tr>
    <tr>
      <td>Sletting av innlegg</td>
      <td>Skal kunne slette blog poster</td>
      <td>Fungerer</td>
      <td> 
        <table>
          <th><img src="https://github.com/ArvidWedtstein/Fagproove/assets/71834553/acb438a5-a793-4f75-88a7-118c1f6c3aaf" width="60" /></th>
          <th><img src="https://github.com/ArvidWedtstein/Fagproove/assets/71834553/6625344b-fbda-4b62-a1a3-906f02d796a3" width="60" /></th>
        </table>
      </td>
      <td></td>
      <td>🟢Fungerer</td>        
    </tr>
    <tr>
      <td>Reaksjoner på innlegg</td>
      <td>Skal kunne reagere på poster med standard reaksjoner og velge fra en liste </td>
      <td>Alt fungerer som det skal, men visningen av reaksjonene er ikke veldig smooth. Dette skyldes hvordan de blir generert.</td>
      <td> 
        <table>
          <th><img src="https://github.com/ArvidWedtstein/Fagproove/assets/71834553/acb438a5-a793-4f75-88a7-118c1f6c3aaf" width="60" /></th>
          <th><img src="https://github.com/ArvidWedtstein/Fagproove/assets/71834553/6625344b-fbda-4b62-a1a3-906f02d796a3" width="60" /></th>
        </table>
      </td>
      <td>Forbedre visningen av reaksjonene(ikke kritisk)</td>
      <td>🟢Fungerer</td>        
    </tr>
    <tr>
      <td>Reaksjoner på innlegg</td>
      <td>Skal kunne reagere på poster med standard reaksjoner og velge fra en liste </td>
      <td>Alt fungerer som det skal, men visningen av reaksjonene er ikke veldig smooth. Dette skyldes hvordan de blir generert.</td>
      <td> 
        <table>
          <th><img src="https://github.com/ArvidWedtstein/Fagproove/assets/71834553/acb438a5-a793-4f75-88a7-118c1f6c3aaf" width="60" /></th>
          <th><img src="https://github.com/ArvidWedtstein/Fagproove/assets/71834553/6625344b-fbda-4b62-a1a3-906f02d796a3" width="60" /></th>
        </table>
      </td>
      <td>Forbedre visningen av reaksjonene(ikke kritisk)</td>
      <td>🟢Fungerer</td>        
    </tr>
    <tr>
      <td>Legge til og fjerne topics på innlegg</td>
      <td>Skal kunne legge til og fjerne topics på innlegg </td>
      <td>Alt fungerer som det skal</td>
      <td> </td>
      <td></td>
      <td>🟢Fungerer</td>        
    </tr>
      <td>Sortere på topics og endre farge</td>
      <td>Skal kunne sorte poster på topic og endre tema farge på topicen </td>
      <td>Alt fungerer som det skal</td>
      <td> </td>
      <td></td>
      <td>🟢Fungerer</td>        
    </tr>        
    </tr>
      <td>Lage nye og slette topics</td>
      <td>Skal kunne lage nye topics og og de uten poster skal kunne settes</td>
      <td>Fungerer som det skal</td>
      <td></td>
      <td></td>
      <td>🟢Fungerer</td>        
    </tr>
</table>
