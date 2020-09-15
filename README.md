# node-red-contrib-ina-sensor

(in English)

a node-red node for the [ina226](https://www.tij.co.jp/jp/lit/ds/symlink/ina226.pdf) and [ina260](https://www.tij.co.jp/lit/ds/symlink/ina260.pdf) sensor module.

the node uses [ina226 npm module](https://www.npmjs.com/package/ina226).

```bash
npm install node-red-contrib-ina-sensor
```

Outputs voltage, current(ampere) and power in JSON format.

I2C address(default: 0x40) and shunt resistor(ina226 excludes, ina260 includes 2m-Ohm) are configurable.


(in Japanese)

ina226, ina260モジュール向けNode-REDノードです。

このノードはina226ノードモジュールを使用しています。

```bash
npm install node-red-contrib-ina-sensor
```

電圧値(V)、電流値(A)、電力値(W)の情報をJSONフォーマットで出力します。

I2Cアドレス(デフォルトは0x40)とシャント抵抗値(ina226は外出し、ina260は2mΩを内包)を設定できます。

![example flow](https://github.com/kitazaki/node-red-contrib-ina-sensor/raw/master/flow_example.png)

