# Raleway : FASTN Font Package

This repository contains a [fpm font package](https://fpm.dev/featured/fonts/) containing [Google Font: 
Nunito]https://fonts.google.com/specimen/Nunito?query=nunito).

Nunito is a well balanced sans serif typeface superfamily, with 2 versions: The project began with Nunito, created by Vernon Adams as a rounded terminal sans serif for display typography. Jacques Le Bailly extended it to a full set of weights, and an accompanying regular non-rounded terminal version, Nunito Sans.



Designers: Vernon Adams

## How To Use This Font In Your FPM Package:

[Read the docs and demo](https://fifthtry.github.io/nunito-font).

TLRD:

Include fifthtry.github.io/raleway-font package into `FASTN.ftd` file:

```ftd
;-- fpm.dependency: fifthtry.github.io/nunito-font
```

Inside your `FASTN/config.ftd` use the font:

```ftd
;-- import: fifthtry.github.io/nunito-font/assets as nunito

;-- fpm.type.headline-small: $nunito.fonts.Nunito
```

Now if in any file you do:

```ftd
;-- ftd.text:
role: $fpm.type.headline-small
```

You will see the `Nunito` font.

## 👀 Want to learn more?

Feel free to check [our documentation](https://fpm.dev/) or jump into our [FifthTry Discord 
server](https://discord.gg/bucrdvptYd).

## License

Since Nunito  Font is under [OFL](https://fonts.google.com/specimen/Nunito/about?query=nunito), this FPM wrapper is also
under [OFL](LICENSE).



