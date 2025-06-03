# Yann's Keyboard Layout Guide

## Overview

This is a custom layout for the Corne split keyboard, designed for programming and multilingual typing with special support for French accents.

## Layout Diagrams

### Base Layer (Layer 0)

```
,-------------------------------------------.                    ,-----------------------------------------.
| Tab   |  Q   |  W   | E/é/è |  R   |  T   |                    |  Y   | U/ù  |  I   |  O   |  P   | Bksp  |
|-------+------+------+-------+------+------+                    +------+------+------+------+------+-------|
| Ctrl  | A/à  |  S   |  D    |  F   |  G   |                    |  H   |  J   |  K   |  L   | :/;  | Enter |
|-------+------+------+-------+------+------+                    +------+------+------+------+------+-------|
|Sh/Esc |Shift |  Z   |  X    |  C   |  V   |                    |  B   |  N   |  M   | ,/←  |  .   | Right |
`-------+------+------+-------+------+------'                    `------+------+------+------+------+-------'
                    | Alt   | GUI  | L1/Spc |                    |L2/Spc| GUI  | Alt  |
                    `-----------------------'                    `--------------------'
```

- E : Tap = E, double tap = é, triple tap = è
- A : Tap = A, double tap = à
- U : Tap = U, double tap = ù
- : : Tap = :, shift = ;
- = : Tap = =, double tap = => (flèche)
- Shift/Esc : Tap = Shift, double tap = Escape
- , : Tap = ,, Cmd/GUI = ← (flèche gauche)

- Special tap dance keys (see below)
  † Comma becomes Left Arrow when GUI (Command) is held

### Lower Layer (Layer 1)

```
,-----------------------------------------.                     ,-----------------------------------------.
| Tab   |  &   |  N2  |  '   |  "   |      |                    |  7   |  8   |  9   |      |      | Bksp  |
|-------+------+------+------+------+------|                    |------+------+------+------+------+-------|
| Esc   |      |      |      |      |      |                    |  4   |  5   |  6   |      |  Up  |       |
|-------+------+------+------+------+------|                    |------+------+------+------+------+-------|
|Shift  |      |      |      |      |      |                    |  1   |  2   |  3   | Left | Down | Right |
`-----------------+------+------+------+---'                    `------+------+------+------+------+-------'
                    |      |      |      |                      |  0   |  0   |      |
                    `---------------------'                     `---------------------'
```

- N2 : touche personnalisée (voir keymap)
- Les touches non renseignées sont transparentes ou non assignées sur cette couche.

### Raise Layer (Layer 2)

```
,-------------------------------------------.                    ,-----------------------------------------.
| Tab   |  ?   |  ^   |  !   |  #   |  ~   |                    |  *   |  _   |  (   |  )   |  %   | Bksp  |
|-------+------+------+------+------+------|                    |------+------+------+------+------+-------|
| Ctrl  |  @   |  $   |      |      |      |                    |  -   |  +   |  [   |  ]   |  /   |  `    |
|-------+------+------+------+------+------|                    |------+------+------+------+------+-------|
|Shift  |BTClr |      | BT1  | BT2  | BT3  |                    |  \   | =/=> |  {   |  }   |  |   |  &    |
`-------+------+------+------+------+------'                    `------+------+------+------+------+-------'
                    |      |      |      |                      |      |      |      |
                    `--------------------'                      `-------------------'
```

- =/=> : Tap =, double tap => (flèche)
- BT Clr/BT1/BT2/BT3 : Contrôles Bluetooth
- Les touches non renseignées sont transparentes ou non assignées sur cette couche.

```

Double tap = for => arrow

# Fonctionnalités spéciales

Touches multifonctions (Tap Dance, Morph, etc.)

- E : Tap = E, double tap = é, triple tap = è
- A : Tap = A, double tap = à
- U : Tap = U, double tap = ù
- : : Tap = :, shift = ;
- = : Tap = =, double tap = => (flèche)
- Shift/Esc : Tap = Shift, double tap = Escape
- , : Tap = ,, Cmd/GUI = ← (flèche gauche)

Accès aux couches

- Espace gauche : Maintenir pour accéder à la couche Lower (Layer 1) : chiffres et navigation
- Espace droit : Maintenir pour accéder à la couche Raise (Layer 2) : symboles et Bluetooth

Contrôles Bluetooth (Layer 2)

- BT Clr : Efface les connexions Bluetooth
- BT1/BT2/BT3 : Sélectionne le profil Bluetooth 1, 2 ou 3

Utilisation

- Saisie classique : Utiliser la couche de base
- Chiffres/navigation : Maintenir espace gauche (Layer 1)
- Symboles/spéciaux : Maintenir espace droit (Layer 2)
- Accents français : Double/triple tap sur E, A ou U
- Bluetooth : Utiliser Layer 2 pour gérer le Bluetooth

Ce layout est conçu pour garder les touches fréquentes accessibles tout en offrant un accès rapide aux caractères spéciaux et fonctions via des couches intuitives.
This layout is designed to keep frequently used keys accessible while providing easy access to special characters and functions through intuitive layers.
```
