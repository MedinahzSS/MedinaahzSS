

## Introdução

MedinahzSS é um scanner para dispositivos Android que tem o objetivo de
reunir logs e arquivos suspeitos em questão de segundos de utilização.

**Por que usar o MedinahzSS?**

O projeto tem como principal função facilitar o trabalho dos analistas
em suas telagens, que contem várias funções, como:

-   **🔵 Automação:** O scanner faz todo o trabalho pesado por você,
    poupando seu tempo.
-   **⚫️ Logs suspeitas:** Reune log's de todos possíves bypass para
    você automaticamente.
-   **🟣 Facilidade:** O scanner roda utilizando `Termux`, e com alguns
    simples comandos você já vai estar rodando ele sem problemas.

## Como utilizar?

#### `<img width="2%" src="https://simpleicons.org/icons/diagramsdotnet.svg">`{=html}  Faça o download do Termux:

  -------------------------------------------------------------------------------------------------
  Aplicativo                                                     Descrição
  -------------------------------------------------------------- ----------------------------------
  [Termux](https://f-droid.org/repo/com.termux_1022.apk)         Terminal utilizado para rodar o
                                                                 scanner

  [Tutorial](https://www.youtube.com/watch?v=RF7O1MHThsE&t=8s)   Tutorial ensinando a como utilizar
  -------------------------------------------------------------------------------------------------

#### `<img width="2%" src="https://simpleicons.org/icons/gnometerminal.svg">`{=html}  Rode utilizando o Termux:

#### `<img width="2%" src="https://simpleicons.org/icons/termius.svg">`{=html}  Após abrir o Termux, dividindo a tela com o pareamento wifi aberto, rode os comandos abaixo:

``` sh
❯ adb pair localhost:porta codigopareamento
```

#### `<img width="2%" src="https://simpleicons.org/icons/termius.svg">`{=html}  Após parear, a porta irá atualizar, então suba nas opções e confira a nova porta.

``` sh
❯ adb connect localhost:portaatualizada
```

#### `<img width="2%" src="https://simpleicons.org/icons/termius.svg">`{=html}  Após parear e conectar corretamente, só rodar o código que irá baixar e executar o scanner.

``` sh
❯ pkg install git php android-tools -y && git clone https://github.com/MedinahzSS/MedinaahzSS
```

`<img src="https://i.imgur.com/NnWf7Fm.png" alt="line break" width="100%" height="3px">`{=html}

## Detecções

  ------------------------------------------------------------------------------------------
  Detecções                                 Descrição
  ----------------------------------------- ------------------------------------------------
  `Verificação da instalação do FreeFire`   Verificar se o jogo está instalado

  `Reinicialização do dispositivo`          Verifica se o dispositivo foi reiniciado a menos
                                            de 60 minutos

  `Versão Android`                          Verifica a versão do Android

  `Root`                                    Verifica se o dispositivo possui Root

  `Data e Hora`                             Verifica bypass de Data e Hora

  `Passagem de Replay`                      Verifica se o usuário passou Replay

  `MTP`                                     Verifica se o MTP está ativado

  `Shaders`                                 Verifica se o usuário deu bypass usando
                                            wallhack/holograma

  `OBB`                                     Verifica se o usuário deu algum tipo de bypass
                                            na OBB
  ------------------------------------------------------------------------------------------

`<sub>`{=html}

`</sub>`{=html}

`<img src="https://i.imgur.com/NnWf7Fm.png" alt="line break" width="100%" height="3px">`{=html}

## Contribuições

Contribuições são bem vindas! Por favor me chame no privado do discord
`keller22cao`.

-   **🐛 [Reporte um Problema](https://discord.gg/allianceoficial)**:
    Encontrou um bug? Me avise!
-   **💬 [Faça uma sugestão](https://discord.gg/allianceoficial)**: Tem
    ideias ou sugestões? Eu adoraria lhe ouvir. `<br>`{=html}

## Agradecimentos

Um grande agradecimento aos membros abaixo por seu trabalho incrível e
contribuições sobre bypass:

::: {style="text-align:; font-weight: bold; margin-bottom: 10px;"}
ㅤKellerㅤㅤSheikㅤ ㅤRibeiroㅤㅤㅤPxㅤㅤㅤㅤHgㅤㅤApela
:::

```{=html}
<table>
```
```{=html}
<tr>
```
```{=html}
<td style="text-align: center; margin-right: 20px;">
```
`<a href="https://www.instagram.com/kellerffx">`{=html}
`<img src="https://i.imgur.com/25Qrvbh.png" alt="kellerSS" style="width: 50px; height: 50px;">`{=html}
`</a>`{=html}
```{=html}
</td>
```
```{=html}
<td style="text-align: center; margin-right: 20px;">
```
`<a href="https://discord.gg/allianceoficial">`{=html}
`<img src="https://i.imgur.com/DkHpc3a.jpeg" alt="sheik" style="width: 50px; height: 50px; object-fit: cover;">`{=html}
`</a>`{=html}
```{=html}
</td>
```
```{=html}
<td style="text-align: center; margin-right: 20px;">
```
`<a href="https://www.instagram.com/Ribeirowxz">`{=html}
`<img src="https://i.imgur.com/xqmiMSG.png" alt="ribeiro" style="width: 50px; height: 50px;">`{=html}
`</a>`{=html}
```{=html}
</td>
```
```{=html}
<td style="text-align: center;">
```
`<a href="https://discord.gg/allianceoficial">`{=html}
`<img src="https://i.imgur.com/8BUhE5T.jpeg" alt="PX" style="width: 50px; height: 50px;">`{=html}
`</a>`{=html}
```{=html}
</td>
```
    </td>
    <td style="text-align: center; margin-right: 20px;">
      <a href="https://www.instagram.com/_hugomoises">
        <img src="https://i.imgur.com/8QVfHn2.png" alt="ribeiro" style="width: 50px; height: 50px;">
      </a>
    </td>
    <td style="text-align: center;">
      <a href="https://discord.gg/allianceoficial">
        <img src="https://i.imgur.com/Fyk08YR.jpeg" alt="PX" style="width: 50px; height: 50px;">
      </a>
    </td>

```{=html}
</tr>
```
```{=html}
</table>
```
## 🎗 Licença

Copyright MedinahzSS © 2025-2030.`<br />`{=html}

::: {align="left"}
:::

`<img src="https://i.imgur.com/NnWf7Fm.png" alt="line break" width="100%" height="3px">`{=html}
