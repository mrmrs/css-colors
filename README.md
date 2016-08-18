# CSS COLOR VARIABLES

  Mobile-first classes for css-colors.
  Set the desired css-colors on any element for any breakpoint.
  Base class names are namespaced across three breakpoints:

*  -ns = not-small (covers everything larger than mobile)
*  -m  = medium
*  -l  = large

## Install
Grab the css partial from github and include it in your project or alternatively
you can install it via npm:
```
npm install --save-dev css-colors
```
View on [npm](https://www.npmjs.org/package/css-color-variables)

```

/*
   COLOR VARIABLES
*/


:root {
  --near-black: #111;
  --dark-gray:#333;
  --mid-gray:#666;
  --gray: #888;
  --silver: #999;
  --light-silver: #aaa;
  --light-gray: #ccc;
  --near-white: #eee;
  --white: #fff;

  --pink: #ffc0cb;
  --lightpink: #ffb6c1;
  --hotpink: #ff69b4;
  --deeppink: #ff1493;
  --palevioletred: #db7093;
  --mediumvioletred: #c71585;
  --lightsalmon: #ffa07a;
  --salmon: #fa8072;
  --darksalmon: #e9967a;
  --lightcoral: #f08080;
  --indianred: #cd5c5c;
  --crimson: #dc143c;
  --firebrick: #b22222;
  --darkred: #8b0000;
  --red: #ff0000;
  --orangered: #ff4500;
  --tomato: #ff6347;
  --coral: #ff7f50;
  --darkorange: #ff8c00;
  --orange: #ffa500;
  --gold: #ffd700;
  --yellow: #ffff00;
  --lightyellow: #ffffe0;
  --lemonchiffon: #fffacd;
  --lightgoldenrodyellow: #fafad2;
  --papayawhip: #ffefd5;
  --moccasin: #ffe4b5;
  --peachpuff: #ffdab9;
  --palegoldenrod: #eee8aa;
  --khaki: #f0e68c;
  --darkkhaki: #bdb76b;
  --cornsilk: #fff8dc;
  --blanchedalmond: #ffebcd;
  --bisque: #ffe4c4;
  --navajowhite: #ffdead;
  --wheat: #f5deb3;
  --burlywood: #deb887;
  --tan: #d2b48c;
  --rosybrown: #bc8f8f;
  --sandybrown: #f4a460;
  --goldenrod: #daa520;
  --darkgoldenrod: #b8860b;
  --peru: #cd853f;
  --chocolate: #d2691e;
  --saddlebrown: #8b4513;
  --sienna: #a0522d;
  --brown: #a52a2a;
  --maroon: #800000;
  --darkolivegreen: #556b2f;
  --olive: #808000;
  --olivedrab: #6b8e23;
  --yellowgreen: #9acd32;
  --limegreen: #32cd32;
  --lime: #00ff00;
  --lawngreen: #7cfc00;
  --chartreuse: #7fff00;
  --greenyellow: #adff2f;
  --springgreen: #00ff7f;
  --mediumspringgreen: #00fa9a;
  --lightgreen: #90ee90;
  --palegreen: #98fb98;
  --darkseagreen: #8fbc8f;
  --mediumseagreen: #3cb371;
  --seagreen: #2e8b57;
  --forestgreen: #228b22;
  --green: #008000;
  --darkgreen: #006400;
  --mediumaquamarine: #66cdaa;
  --aqua: #00ffff;
  --cyan: #00ffff;
  --lightcyan: #e0ffff;
  --paleturquoise: #afeeee;
  --aquamarine: #7fffd4;
  --turquoise: #40e0d0;
  --mediumturquoise: #48d1cc;
  --darkturquoise: #00ced1;
  --lightseagreen: #20b2aa;
  --cadetblue: #5f9ea0;
  --darkcyan: #008b8b;
  --teal: #008080;
  --lightsteelblue: #b0c4de;
  --powderblue: #b0e0e6;
  --lightblue: #add8e6;
  --skyblue: #87ceeb;
  --lightskyblue: #87cefa;
  --deepskyblue: #00bfff;
  --dodgerblue: #1e90ff;
  --cornflowerblue: #6495ed;
  --steelblue: #4682b4;
  --royalblue: #4169e1;
  --blue: #0000ff;
  --mediumblue: #0000cd;
  --darkblue: #00008b;
  --navy: #000080;
  --midnightblue: #191970;
  --lavender: #e6e6fa;
  --thistle: #d8bfd8;
  --plum: #dda0dd;
  --violet: #ee82ee;
  --orchid: #da70d6;
  --fuchsia: #ff00ff;
  --magenta: #ff00ff;
  --mediumorchid: #ba55d3;
  --mediumpurple: #9370db;
  --blueviolet: #8a2be2;
  --darkviolet: #9400d3;
  --darkorchid: #9932cc;
  --darkmagenta: #8b008b;
  --purple: #800080;
  --indigo: #4b0082;
  --darkslateblue: #483d8b;
  --slateblue: #6a5acd;
  --mediumslateblue: #7b68ee;
  --white: #ffffff;
  --snow: #fffafa;
  --honeydew: #f0fff0;
  --mintcream: #f5fffa;
  --azure: #f0ffff;
  --aliceblue: #f0f8ff;
  --ghostwhite: #f8f8ff;
  --whitesmoke: #f5f5f5;
  --seashell: #fff5ee;
  --beige: #f5f5dc;
  --oldlace: #fdf5e6;
  --floralwhite: #fffaf0;
  --ivory: #fffff0;
  --antiquewhite: #faebd7;
  --linen: #faf0e6;
  --lavenderblush: #fff0f5;
  --mistyrose: #ffe4e1;
  --gainsboro: #dcdcdc;
  --lightgray: #d3d3d3;
  --silver: #c0c0c0;
  --darkgray: #a9a9a9;
  --gray: #808080;
  --dimgray: #696969;
  --lightslategray: #778899;
  --slategray: #708090;
  --darkslategray: #2f4f4f;
  --black: #000000;
}

```

## Author

[http://mrmrs.io](http://mrmrs.io)

## License

ISC
