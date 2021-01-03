# TailwindCSS-Study Resume

## Backgrounds, colors and shades

Class prefix
- bg ⇒ background

- Colors

Default: green, red, purple, yellow, oragen...
B&W: black and white does not apply shadings

- Shades

100, 200, 300, ... , 900

Usage

```
<div class="bg-purple-200 "/>
<div class="bg-black" />
```

## Rem property

- Sizes

Class prefix

- h ⇒ height
- w ⇒ width

- screen, full
- 0, 1, 2, 3, 4, 5
- 6, 8, 10, 12
- 16, 20, 24
- 32, 40, 48, 56, 64
- 1/2, 1/{3, 4, 5, 6, 12}, 2/4, 3/5...

Usage

```
<div class="w-full h-screen">
  <div class="w-1/2 h-4" />
</div>
```

### Spacing

Class prefix

- p ⇒ padding
- m ⇒ margin

Direction

- x ⇒ horizontal
- y ⇒ vertical

Expecific

- t ⇒ top
- b ⇒ bottom
- r ⇒ right
- l ⇒ left

Usage

```
<div class="px-2 py-4 ml-16"/>
```

### Typhography

Class prefix

- font-{family} ⇒ sans, serif, mono 
- font-{weight} ⇒ 100, 200, 300, ..., 900

#### Typhography size

Class prefix

- text-{size}

Sizes

- xs ⇒ .75rem = 12px
- sm ⇒ .875rem = 14px
- base ⇒ 1rem = 16px
- lg ⇒ 1.125rem = 18px
- xl ⇒ 1.25rem = 20px
- 2xl ⇒ 1.5rem = 24px
- 3xl ⇒ 1.875rem = 30px
- 4xl ⇒ 2.25rem = 36px
- 5xl ⇒ 3rem = 48px
- 6xl ⇒ 4rem = 64px

#### Typhography align

Class prefix

- text-{align} ⇒ left, center, right, justify

#### Typhography color

Its same bg-color-shade

Class prefix

- text-{color}-{shade}

#### Typhography letter-spacing, line-height and decorations

[1] Letter-spacing

Class prefix

- tracking-{spacing}

Spacing

- tighter ⇒ -0.05em
- tight ⇒ -0.025em
- normal ⇒ 0
- wide ⇒ 0.025em
- wider ⇒ 0.05em
- widest ⇒ 0.1em

[2] Line-height

Class prefix

- leading-{spacing}

Spacing

- none ⇒ 1
- tight ⇒ 1.25
- snug ⇒ 1.375
- normal ⇒ 1.5
- relaxed ⇒ 1.625
- loose ⇒ 2

[3] Decorations

- underline
- no-underline
- line-through

- uppercase
- lowercase
- capitalize
- normal-case

- uppercase
- lowercase
- capitalize
- normal-case


### Border

Class prefix

- border-{size}
- border-{size}-{side}
- border-{color}-{shade} ⇒ its same bg-{color}-{shade}
- border-{style}
- border-{radius}
- rounded-{side}-{radius}

Sizes

- 0 ⇒ 0px
- [default] ⇒ 1px
- 2 ⇒ 2px
- 4 ⇒ 4px
- 8 ⇒ 8px

Sides

- t ⇒ top
- b ⇒ bottom
- l ⇒ left
- r ⇒ right

Styles

- solid
- dashed
- dotted
- double
- none

Radius

- sm ⇒ .125rem = 2px
- [default] ⇒ .25rem = 4px
- lg ⇒ .5rem = 8px
- xl ⇒ .75rem = 12px
- 2xl ⇒ 1rem = 16px
- 3xl ⇒ 1.5rem = 24px
- full ⇒ __ = 9999px
- none ⇒ 0 = 0px

Rounded

- t ⇒ top-left & top-right
- r ⇒ top-right & bottom-right
- b ⇒ bottom-left & bottom-right
- l ⇒ top-left & bottom-left
- tl ⇒ top-left
- tr ⇒ top-right
- br ⇒ bottom-right
- bl ⇒ bottom-left


### Layouts

Class prefix

- container - 

sets max-width using current breakpoint

- sm ⇒ max-width: 640px
- md ⇒ max-width: 768px
- lg ⇒ max-width: 1024px
- xl ⇒ max-width: 1280px


### Displays

Class prefix
- {display} ⇒ block, inline, inline-block, flex, inline-flex, table, table-row, table-cell, hidden

### Positions

Class prefix
- {position} ⇒ static, fixed, absolute, relative, sticky

#### Z-Index

Class prefix
- z-{order} ⇒ 0, 10, 20, 30, 40 50, auto

### Flex-box

Class prefix
- {flex}

### Horizontal direction

Class prefix
- justify-{alignment} ⇒ start, center, end, between, around

- items-{alignment} ⇒ stretch, start, center, end, baseline

### Change direction

Class prefix
- flex-{direction} ⇒ row, row-reverse, column, column-reverse

### Wrapping

Class prefix
- flex-{wrap} ⇒ no-wrap, wrap, wrap-reverse

### Responsive

Screen breaking-points

Class prefix
- {screen}:{...classes}

- [default] *0px*
- sm: *640px*
- md: *768px*
- lg: *1024px*
- xl: *1280px*

Usage

```
<div class="h-40 w-full md:w-1/2"/>
```

### Effects

#### Shadow

Class prefix
- shadow-{size}

Sizes

- md
- lg
- xl
- 2xl
- inner
- outline
- none

#### Opacity

Class prefix
- opacity-{percent}

Percents

- 100
- 75
- 50
- 25
- 0

### Interactivity

Class prefix
- hover-{...classes}
- focus-{...classes}
- active-{...classes}
- checked-{...classes}

Combination with breaking points

- md:hover:bg-black
- lg:hover:text-white


### Cursor

Class prefix
- cursor-{style}

Styles

- default
- pointer
- wait
- text
- move
- not-allowed

### Text selected

Class prefix
- select-{style}

Styles

- none
- text
- all
- auto

### Accessibility

Class prefix
- sr-only
- not-sr-only

### Visibility

Class prefix
- visibile
- invisible


### Transitions and Animations

Class prefix
- transition-{property}
- duration-{time in ms}
- delay-{time in ms}
- ease-{timing}
- animate-{name}

Propertys

- none
- all
- colors
- opacity
- shadow
- transform

Times

- 75
- 100
- 150
- 200
- 300
- 500
- 700
- 1000

Timing

- linear
- in
- out
- in-out

Animation names

- none
- spin
- ping
- pulse
- bounce

