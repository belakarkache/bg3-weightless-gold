# Weightless Gold

*[English](#english) · [Português](#português)*

Gold weighs nothing. That's the whole mod.

![Version](https://img.shields.io/badge/version-1.0.0-blue) ![BG3](https://img.shields.io/badge/BG3-Patch%208-green)

---

## English

### What it does

Sets the weight of gold to zero. In the base game each coin weighs `0.001`, so
a big purse quietly eats into your carry capacity — 10.000 gold is 10 kg. With
this mod it's 0.

One stat entry, no scripts, no new items.

### Requirements

- Baldur's Gate 3, Patch 8

### Installing

1. Download `WeightlessGold.pak` from the [Releases](../../releases) page.
2. Put it in your Mods folder:
   `%LOCALAPPDATA%\Larian Studios\Baldur's Gate 3\Mods`
   (paste that into the Windows Explorer address bar) or install using the BG3 Mod Manager
3. Open **BG3 Mod Manager**, enable **Weightless Gold**, and click
   *Export Load Order to Game*.
4. Launch the game. Gold no longer counts toward your weight.

### Good to know

- Safe to add or remove at any time — nothing is written into your save.
- It overrides the shared `_Gold` stat, so any mod that also touches gold weight
  will conflict. Whichever loads last wins.
- Only gold. Coin pouches, gems and trade goods keep their normal weight.
- Not tested in co-op.

### Repository contents

This repository holds the mod's source files — `meta.lsx` and the stats entry —
exactly as they are packed into the `.pak`. The build tooling is not published.

To repack it yourself you need LSLib/Divine:

```
divine -g bg3 -a create-package -s mod/WeightlessGold -d WeightlessGold.pak
```

---

## Português

### O que faz

Zera o peso do ouro. No jogo base cada moeda pesa `0.001`, então uma bolsa
gorda come sua capacidade de carga sem você perceber — 10.000 de ouro são 10 kg.
Com o mod, são 0.

Uma entrada de stat, nenhum script, nenhum item novo.

### Requisitos

- Baldur's Gate 3, Patch 8

### Instalação

1. Baixe o `WeightlessGold.pak` na página de [Releases](../../releases).
2. Coloque o arquivo na sua pasta de Mods:
   `%LOCALAPPDATA%\Larian Studios\Baldur's Gate 3\Mods`
   (cole isso na barra de endereço do Explorador de Arquivos) ou instale normalmente pelo BG3 Mod Manager
3. Abra o **BG3 Mod Manager**, ative o **Weightless Gold** e clique em
   *Export Load Order to Game*.
4. Inicie o jogo. O ouro não conta mais no peso.

### Bom saber

- Pode instalar e remover a qualquer momento — nada fica gravado no save.
- O mod sobrescreve o stat compartilhado `_Gold`, então conflita com qualquer
  outro mod que mexa no peso do ouro. Vale o que carregar por último.
- Só o ouro. Bolsas de moedas, gemas e mercadorias mantêm o peso normal.
- Não testado em co-op.

### Conteúdo do repositório

Este repositório guarda os arquivos-fonte do mod — o `meta.lsx` e a entrada de
stat — exatamente como vão dentro do `.pak`. As ferramentas de build não são
publicadas.

Para reempacotar por conta própria você precisa do LSLib/Divine:

```
divine -g bg3 -a create-package -s mod/WeightlessGold -d WeightlessGold.pak
```

---

Autora: **[icka.dev](https://www.icka.dev/)**
