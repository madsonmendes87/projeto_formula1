<h1>Formula 1</h1>

  <table>
        <tr>
            <td>
                <img src="./assets/F1.gif" alt="F1" width="200">
            </td>
            <td>
                <b>Objetivo:</b>
                <p> Nosso desafio será criar uma lógica de um jogo de vídeo game para simular corridas de Formula 1, levando em consideração as regras e mecânicas abaixo.</p>
            </td>
        </tr>
    </table>

<h2>Pilotos</h2>
      <table style="border-collapse: collapse; width: 800px; margin: 0 auto;">
        <tr>
            <td style="border: 1px solid black; text-align: center;">
                <p>Piastri</p>
                <img src="./assets/piastri.gif" alt="Oscar Piastri" width="60" height="60">
            </td>
            <td style="border: 1px solid black; text-align: center;">
                <p>Velocidade: 4</p>
                <p>Manobrabilidade: 3</p>
            </td>
             <td style="border: 1px solid black; text-align: center;">
                <p>Norris</p>
                <img src="./assets/lando-norris.gif" alt="Lando Norris" width="60" height="60">
            </td>
            <td style="border: 1px solid black; text-align: center;">
                <p>Velocidade: 3</p>
                <p>Manobrabilidade: 4</p>
            </td>
              <td style="border: 1px solid black; text-align: center;">
                <p>Leclerc</p>
                <img src="./assets/leclerc.gif" alt="Charles Leclerc" width="60" height="60">
            </td>
            <td style="border: 1px solid black; text-align: center;">
                <p>Velocidade: 2</p>
                <p>Manobrabilidade: 4</p>
            </td>
        </tr>
        <tr>
            <td style="border: 1px solid black; text-align: center;">
                <p>Hamilton</p>
                <img src="./assets/hamilton.gif" alt="Lewis Hamilton" width="60" height="60">
            </td>
            <td style="border: 1px solid black; text-align: center;">
                <p>Velocidade: 5</p>
                <p>Manobrabilidade: 2</p>
            </td>
            <td style="border: 1px solid black; text-align: center;">
                <p>Bortoletto</p>
                <img src="./assets/bortoletto.gif" alt="Mario Kart" width="60" height="60">
            </td>
            <td style="border: 1px solid black; text-align: center;">
                <p>Velocidade: 3</p>
                <p>Manobrabilidade: 4</p>
            </td>
            <td style="border: 1px solid black; text-align: center;">
                <p>Kimi Antolelli</p>
                <img src="./assets/antonelli.gif" alt="Mario Kart" width="60" height="60">
            </td>
            <td style="border: 1px solid black; text-align: center;">
                <p>Velocidade: 2</p>
                <p>Manobrabilidade: 2</p>
            </td>
        </tr>
    </table>

<p></p>

<h3>🕹️ Regras & mecânicas:</h3>

<b>Pilotos:</b>

<input type="checkbox" id="pilotos-item" />
<label for="pilotos-item">O Computador deve receber dois pilotos para disputar a corrida</label>

<b>Pistas:</b>

<ul>
  <li><input type="checkbox" id="pistas-1-item" /> <label for="pistas-1-item">Os pilotos irão correr em uma pista aleatória de 10 voltas</label></li>
  <li><input type="checkbox" id="pistas-2-item" /> <label for="pistas-2-item">A cada volta, será sorteado um bloco da pista que pode ser uma reta ou curva</label>
    <ul>
      <li><input type="checkbox" id="pistas-2-1-item" /> <label for="pistas-2-1-item">Caso o bloco da pista seja uma RETA, o piloto deve jogar um dado de 6 lados e somar o atributo VELOCIDADE, quem vencer ganha um ponto</label></li>
      <li><input type="checkbox" id="pistas-2-2-item" /> <label for="pistas-2-2-item">Caso o bloco da pista seja uma CURVA, o piloto deve jogar um dado de 6 lados e somar o atributo MANOBRABILIDADE, quem vencer ganha um ponto</label></li>
      <li><input type="checkbox" id="pistas-2-3-item" /> <label for="pistas-2-3-item">Nenhum piloto pode ter pontuação negativa (valores abaixo de 0)</label></li>
    </ul>
  </li>
</ul>

<b>Condição de vitória:</b>

<input type="checkbox" id="vitoria-item" />
<label for="vitoria-item">Vence a corrida quem acumulou mais pontos</label>
