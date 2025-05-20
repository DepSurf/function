# Function: <code>regmap_irq_get_virq</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int regmap_irq_get_virq(struct regmap_irq_chip_data *data, int irq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/regmap/regmap-irq.c (ffffffff8156bc70)
Location: drivers/base/regmap/regmap-irq.c:598
Inline: False
Direct callers:
  - drivers/mfd/twl6040.c:twl6040_probe
  - drivers/mfd/twl6040.c:twl6040_probe
  - drivers/mfd/twl6040.c:twl6040_probe
  - drivers/mfd/da9052-irq.c:da9052_enable_irq
  - drivers/mfd/da9052-irq.c:da9052_disable_irq
  - drivers/mfd/da9052-irq.c:da9052_disable_irq_nosync
  - drivers/mfd/da9052-irq.c:da9052_request_irq
  - drivers/mfd/da9052-irq.c:da9052_free_irq
```
**Symbols:**

```
ffffffff8156bc70-ffffffff8156bca3: regmap_irq_get_virq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int regmap_irq_get_virq(struct regmap_irq_chip_data *data, int irq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/regmap/regmap-irq.c (ffffffff815c09f0)
Location: drivers/base/regmap/regmap-irq.c:810
Inline: False
Direct callers:
  - drivers/mfd/twl6040.c:twl6040_probe
  - drivers/mfd/twl6040.c:twl6040_probe
  - drivers/mfd/twl6040.c:twl6040_probe
  - drivers/mfd/da9052-irq.c:da9052_free_irq
  - drivers/mfd/da9052-irq.c:da9052_request_irq
  - drivers/mfd/da9052-irq.c:da9052_disable_irq_nosync
  - drivers/mfd/da9052-irq.c:da9052_disable_irq
  - drivers/mfd/da9052-irq.c:da9052_enable_irq
```
**Symbols:**

```
ffffffff815c09f0-ffffffff815c0a2c: regmap_irq_get_virq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int regmap_irq_get_virq(struct regmap_irq_chip_data *data, int irq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/regmap/regmap-irq.c (ffffffff815efe30)
Location: drivers/base/regmap/regmap-irq.c:810
Inline: False
Direct callers:
  - drivers/mfd/twl6040.c:twl6040_probe
  - drivers/mfd/twl6040.c:twl6040_probe
  - drivers/mfd/twl6040.c:twl6040_probe
  - drivers/mfd/da9052-irq.c:da9052_free_irq
  - drivers/mfd/da9052-irq.c:da9052_request_irq
  - drivers/mfd/da9052-irq.c:da9052_disable_irq_nosync
  - drivers/mfd/da9052-irq.c:da9052_disable_irq
  - drivers/mfd/da9052-irq.c:da9052_enable_irq
```
**Symbols:**

```
ffffffff815efe30-ffffffff815efe6c: regmap_irq_get_virq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int regmap_irq_get_virq(struct regmap_irq_chip_data *data, int irq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/regmap/regmap-irq.c (ffffffff81603c40)
Location: drivers/base/regmap/regmap-irq.c:824
Inline: False
Direct callers:
  - drivers/mfd/twl6040.c:twl6040_probe
  - drivers/mfd/twl6040.c:twl6040_probe
  - drivers/mfd/twl6040.c:twl6040_probe
  - drivers/mfd/da9052-irq.c:da9052_free_irq
  - drivers/mfd/da9052-irq.c:da9052_request_irq
  - drivers/mfd/da9052-irq.c:da9052_disable_irq_nosync
  - drivers/mfd/da9052-irq.c:da9052_disable_irq
  - drivers/mfd/da9052-irq.c:da9052_enable_irq
```
**Symbols:**

```
ffffffff81603c40-ffffffff81603c7c: regmap_irq_get_virq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int regmap_irq_get_virq(struct regmap_irq_chip_data *data, int irq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/regmap/regmap-irq.c (ffffffff8166c020)
Location: drivers/base/regmap/regmap-irq.c:824
Inline: False
Direct callers:
  - drivers/mfd/twl6040.c:twl6040_probe
  - drivers/mfd/twl6040.c:twl6040_probe
  - drivers/mfd/twl6040.c:twl6040_probe
  - drivers/mfd/da9052-irq.c:da9052_free_irq
  - drivers/mfd/da9052-irq.c:da9052_request_irq
  - drivers/mfd/da9052-irq.c:da9052_disable_irq_nosync
  - drivers/mfd/da9052-irq.c:da9052_disable_irq
  - drivers/mfd/da9052-irq.c:da9052_enable_irq
```
**Symbols:**

```
ffffffff8166c020-ffffffff8166c05c: regmap_irq_get_virq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int regmap_irq_get_virq(struct regmap_irq_chip_data *data, int irq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/regmap/regmap-irq.c (ffffffff816a7a80)
Location: drivers/base/regmap/regmap-irq.c:824
Inline: False
Direct callers:
  - drivers/gpio/gpio-palmas.c:palmas_gpio_to_irq
  - drivers/mfd/twl6040.c:twl6040_probe
  - drivers/mfd/twl6040.c:twl6040_probe
  - drivers/mfd/twl6040.c:twl6040_probe
  - drivers/mfd/da9052-irq.c:da9052_free_irq
  - drivers/mfd/da9052-irq.c:da9052_request_irq
  - drivers/mfd/da9052-irq.c:da9052_disable_irq_nosync
  - drivers/mfd/da9052-irq.c:da9052_disable_irq
  - drivers/mfd/da9052-irq.c:da9052_enable_irq
```
**Symbols:**

```
ffffffff816a7a80-ffffffff816a7abc: regmap_irq_get_virq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int regmap_irq_get_virq(struct regmap_irq_chip_data *data, int irq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/regmap/regmap-irq.c (ffffffff816c8620)
Location: drivers/base/regmap/regmap-irq.c:886
Inline: False
Direct callers:
  - drivers/gpio/gpio-palmas.c:palmas_gpio_to_irq
  - drivers/mfd/twl6040.c:twl6040_probe
  - drivers/mfd/twl6040.c:twl6040_probe
  - drivers/mfd/twl6040.c:twl6040_probe
  - drivers/mfd/da9052-irq.c:da9052_free_irq
  - drivers/mfd/da9052-irq.c:da9052_request_irq
  - drivers/mfd/da9052-irq.c:da9052_disable_irq_nosync
  - drivers/mfd/da9052-irq.c:da9052_disable_irq
  - drivers/mfd/da9052-irq.c:da9052_enable_irq
```
**Symbols:**

```
ffffffff816c8620-ffffffff816c865c: regmap_irq_get_virq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int regmap_irq_get_virq(struct regmap_irq_chip_data *data, int irq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/regmap/regmap-irq.c (ffffffff81703a80)
Location: drivers/base/regmap/regmap-irq.c:970
Inline: False
Direct callers:
  - drivers/gpio/gpio-palmas.c:palmas_gpio_to_irq
  - drivers/mfd/twl6040.c:twl6040_probe
  - drivers/mfd/twl6040.c:twl6040_probe
  - drivers/mfd/twl6040.c:twl6040_probe
  - drivers/mfd/da9052-irq.c:da9052_free_irq
  - drivers/mfd/da9052-irq.c:da9052_request_irq
  - drivers/mfd/da9052-irq.c:da9052_disable_irq_nosync
  - drivers/mfd/da9052-irq.c:da9052_disable_irq
  - drivers/mfd/da9052-irq.c:da9052_enable_irq
```
**Symbols:**

```
ffffffff81703a80-ffffffff81703abc: regmap_irq_get_virq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int regmap_irq_get_virq(struct regmap_irq_chip_data *data, int irq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/regmap/regmap-irq.c (ffffffff81727dc0)
Location: drivers/base/regmap/regmap-irq.c:965
Inline: False
Direct callers:
  - drivers/gpio/gpio-palmas.c:palmas_gpio_to_irq
  - drivers/mfd/twl6040.c:twl6040_probe
  - drivers/mfd/twl6040.c:twl6040_probe
  - drivers/mfd/twl6040.c:twl6040_probe
  - drivers/mfd/da9052-irq.c:da9052_free_irq
  - drivers/mfd/da9052-irq.c:da9052_request_irq
  - drivers/mfd/da9052-irq.c:da9052_disable_irq_nosync
  - drivers/mfd/da9052-irq.c:da9052_disable_irq
  - drivers/mfd/da9052-irq.c:da9052_enable_irq
```
**Symbols:**

```
ffffffff81727dc0-ffffffff81727dfc: regmap_irq_get_virq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int regmap_irq_get_virq(struct regmap_irq_chip_data *data, int irq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/regmap/regmap-irq.c (ffffffff817e4430)
Location: drivers/base/regmap/regmap-irq.c:1017
Inline: False
Direct callers:
  - drivers/gpio/gpio-palmas.c:palmas_gpio_to_irq
  - drivers/mfd/arizona-irq.c:arizona_irq_exit
  - drivers/mfd/arizona-irq.c:arizona_irq_exit
  - drivers/mfd/arizona-irq.c:arizona_irq_exit
  - drivers/mfd/arizona-irq.c:arizona_irq_exit
  - drivers/mfd/arizona-irq.c:arizona_set_irq_wake
  - drivers/mfd/arizona-irq.c:arizona_set_irq_wake
  - drivers/mfd/arizona-irq.c:arizona_request_irq
  - drivers/mfd/arizona-irq.c:arizona_request_irq
  - drivers/mfd/twl6040.c:twl6040_probe
  - drivers/mfd/twl6040.c:twl6040_probe
  - drivers/mfd/twl6040.c:twl6040_probe
  - drivers/mfd/da9052-irq.c:da9052_irq_exit
  - drivers/mfd/da9052-irq.c:da9052_irq_init
  - drivers/mfd/da9052-irq.c:da9052_disable_irq_nosync
  - drivers/mfd/da9052-irq.c:da9052_disable_irq
  - drivers/mfd/da9052-irq.c:da9052_enable_irq
```
**Symbols:**

```
ffffffff817e4430-ffffffff817e446c: regmap_irq_get_virq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int regmap_irq_get_virq(struct regmap_irq_chip_data *data, int irq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/regmap/regmap-irq.c (ffffffff817f9290)
Location: drivers/base/regmap/regmap-irq.c:1052
Inline: False
Direct callers:
  - drivers/gpio/gpio-palmas.c:palmas_gpio_to_irq
  - drivers/mfd/arizona-irq.c:arizona_irq_exit
  - drivers/mfd/arizona-irq.c:arizona_irq_exit
  - drivers/mfd/arizona-irq.c:arizona_irq_exit
  - drivers/mfd/arizona-irq.c:arizona_irq_exit
  - drivers/mfd/arizona-irq.c:arizona_set_irq_wake
  - drivers/mfd/arizona-irq.c:arizona_set_irq_wake
  - drivers/mfd/arizona-irq.c:arizona_request_irq
  - drivers/mfd/arizona-irq.c:arizona_request_irq
  - drivers/mfd/twl6040.c:twl6040_probe
  - drivers/mfd/twl6040.c:twl6040_probe
  - drivers/mfd/twl6040.c:twl6040_probe
  - drivers/mfd/da9052-irq.c:da9052_irq_exit
  - drivers/mfd/da9052-irq.c:da9052_irq_init
  - drivers/mfd/da9052-irq.c:da9052_disable_irq_nosync
  - drivers/mfd/da9052-irq.c:da9052_disable_irq
  - drivers/mfd/da9052-irq.c:da9052_enable_irq
```
**Symbols:**

```
ffffffff817f9290-ffffffff817f92ce: regmap_irq_get_virq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int regmap_irq_get_virq(struct regmap_irq_chip_data *data, int irq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/regmap/regmap-irq.c (ffffffff817dd500)
Location: drivers/base/regmap/regmap-irq.c:1120
Inline: False
Direct callers:
  - drivers/gpio/gpio-palmas.c:palmas_gpio_to_irq
  - drivers/mfd/arizona-irq.c:arizona_irq_exit
  - drivers/mfd/arizona-irq.c:arizona_irq_exit
  - drivers/mfd/arizona-irq.c:arizona_irq_exit
  - drivers/mfd/arizona-irq.c:arizona_irq_exit
  - drivers/mfd/arizona-irq.c:arizona_set_irq_wake
  - drivers/mfd/arizona-irq.c:arizona_set_irq_wake
  - drivers/mfd/arizona-irq.c:arizona_request_irq
  - drivers/mfd/arizona-irq.c:arizona_request_irq
  - drivers/mfd/twl6040.c:twl6040_probe
  - drivers/mfd/twl6040.c:twl6040_probe
  - drivers/mfd/twl6040.c:twl6040_probe
  - drivers/mfd/da9052-irq.c:da9052_irq_exit
  - drivers/mfd/da9052-irq.c:da9052_irq_init
  - drivers/mfd/da9052-irq.c:da9052_disable_irq_nosync
  - drivers/mfd/da9052-irq.c:da9052_disable_irq
  - drivers/mfd/da9052-irq.c:da9052_enable_irq
```
**Symbols:**

```
ffffffff817dd500-ffffffff817dd53e: regmap_irq_get_virq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int regmap_irq_get_virq(struct regmap_irq_chip_data *data, int irq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/regmap/regmap-irq.c (ffffffff81868fb0)
Location: drivers/base/regmap/regmap-irq.c:1119
Inline: False
Direct callers:
  - drivers/gpio/gpio-palmas.c:palmas_gpio_to_irq
  - drivers/mfd/twl6040.c:twl6040_probe
  - drivers/mfd/twl6040.c:twl6040_probe
  - drivers/mfd/twl6040.c:twl6040_probe
  - drivers/mfd/da9052-irq.c:da9052_irq_exit
  - drivers/mfd/da9052-irq.c:da9052_irq_init
  - drivers/mfd/da9052-irq.c:da9052_disable_irq_nosync
  - drivers/mfd/da9052-irq.c:da9052_disable_irq
  - drivers/mfd/da9052-irq.c:da9052_enable_irq
```
**Symbols:**

```
ffffffff81868fb0-ffffffff81868fee: regmap_irq_get_virq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int regmap_irq_get_virq(struct regmap_irq_chip_data *data, int irq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/regmap/regmap-irq.c (ffffffff819b1bf0)
Location: drivers/base/regmap/regmap-irq.c:1121
Inline: False
Direct callers:
  - drivers/gpio/gpio-palmas.c:palmas_gpio_to_irq
  - drivers/mfd/twl6040.c:twl6040_probe
  - drivers/mfd/twl6040.c:twl6040_probe
  - drivers/mfd/twl6040.c:twl6040_probe
  - drivers/mfd/da9052-irq.c:da9052_irq_exit
  - drivers/mfd/da9052-irq.c:da9052_irq_init
  - drivers/mfd/da9052-irq.c:da9052_disable_irq_nosync
  - drivers/mfd/da9052-irq.c:da9052_disable_irq
  - drivers/mfd/da9052-irq.c:da9052_enable_irq
```
**Symbols:**

```
ffffffff819b1bf0-ffffffff819b1c4c: regmap_irq_get_virq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int regmap_irq_get_virq(struct regmap_irq_chip_data *data, int irq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/regmap/regmap-irq.c (ffffffff81b26b60)
Location: drivers/base/regmap/regmap-irq.c:1304
Inline: False
Direct callers:
  - drivers/gpio/gpio-palmas.c:palmas_gpio_to_irq
  - drivers/mfd/twl6040.c:twl6040_probe
  - drivers/mfd/twl6040.c:twl6040_probe
  - drivers/mfd/twl6040.c:twl6040_probe
  - drivers/mfd/da9052-irq.c:da9052_irq_exit
  - drivers/mfd/da9052-irq.c:da9052_irq_init
  - drivers/mfd/da9052-irq.c:da9052_disable_irq_nosync
  - drivers/mfd/da9052-irq.c:da9052_disable_irq
  - drivers/mfd/da9052-irq.c:da9052_enable_irq
```
**Symbols:**

```
ffffffff81b26b60-ffffffff81b26bbc: regmap_irq_get_virq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int regmap_irq_get_virq(struct regmap_irq_chip_data *data, int irq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/regmap/regmap-irq.c (ffffffff81b769d0)
Location: drivers/base/regmap/regmap-irq.c:1116
Inline: False
Direct callers:
  - drivers/gpio/gpio-palmas.c:palmas_gpio_to_irq
  - drivers/mfd/twl6040.c:twl6040_probe
  - drivers/mfd/twl6040.c:twl6040_probe
  - drivers/mfd/twl6040.c:twl6040_probe
  - drivers/mfd/da9052-irq.c:da9052_irq_exit
  - drivers/mfd/da9052-irq.c:da9052_irq_init
  - drivers/mfd/da9052-irq.c:da9052_disable_irq_nosync
  - drivers/mfd/da9052-irq.c:da9052_disable_irq
  - drivers/mfd/da9052-irq.c:da9052_enable_irq
```
**Symbols:**

```
ffffffff81b769d0-ffffffff81b76a2c: regmap_irq_get_virq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int regmap_irq_get_virq(struct regmap_irq_chip_data *data, int irq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/regmap/regmap-irq.c (ffffffff81bca7a0)
Location: drivers/base/regmap/regmap-irq.c:1116
Inline: False
Direct callers:
  - drivers/gpio/gpio-palmas.c:palmas_gpio_to_irq
  - drivers/mfd/twl6040.c:twl6040_probe
  - drivers/mfd/twl6040.c:twl6040_probe
  - drivers/mfd/twl6040.c:twl6040_probe
  - drivers/mfd/da9052-irq.c:da9052_irq_exit
  - drivers/mfd/da9052-irq.c:da9052_irq_init
  - drivers/mfd/da9052-irq.c:da9052_disable_irq_nosync
  - drivers/mfd/da9052-irq.c:da9052_disable_irq
  - drivers/mfd/da9052-irq.c:da9052_enable_irq
```
**Symbols:**

```
ffffffff81bca7a0-ffffffff81bca7fc: regmap_irq_get_virq (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: ✅</summary>

```c
int regmap_irq_get_virq(struct regmap_irq_chip_data *data, int irq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/regmap/regmap-irq.c (ffff80001091d578)
Location: drivers/base/regmap/regmap-irq.c:965
Inline: False
Direct callers:
  - drivers/pinctrl/pinctrl-as3722.c:as3722_gpio_to_irq
  - drivers/gpio/gpio-palmas.c:palmas_gpio_to_irq
  - drivers/mfd/twl6040.c:twl6040_probe
  - drivers/mfd/twl6040.c:twl6040_probe
  - drivers/mfd/twl6040.c:twl6040_probe
  - drivers/mfd/twl6040.c:twl6040_probe
  - drivers/mfd/da9052-irq.c:da9052_free_irq
  - drivers/mfd/da9052-irq.c:da9052_request_irq
  - drivers/mfd/da9052-irq.c:da9052_disable_irq_nosync
  - drivers/mfd/da9052-irq.c:da9052_disable_irq
  - drivers/mfd/da9052-irq.c:da9052_enable_irq
```
**Symbols:**

```
ffff80001091d578-ffff80001091d5cc: regmap_irq_get_virq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int regmap_irq_get_virq(struct regmap_irq_chip_data *data, int irq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/regmap/regmap-irq.c (c0a02a40)
Location: drivers/base/regmap/regmap-irq.c:965
Inline: False
Direct callers:
  - drivers/pinctrl/pinctrl-as3722.c:as3722_gpio_to_irq
  - drivers/gpio/gpio-palmas.c:palmas_gpio_to_irq
  - drivers/mfd/arizona-irq.c:arizona_map_irq
  - drivers/mfd/arizona-irq.c:arizona_map_irq
  - drivers/mfd/twl6040.c:twl6040_probe
  - drivers/mfd/twl6040.c:twl6040_probe
  - drivers/mfd/twl6040.c:twl6040_probe
  - drivers/mfd/twl6040.c:twl6040_probe
  - drivers/mfd/da9052-irq.c:da9052_free_irq
  - drivers/mfd/da9052-irq.c:da9052_request_irq
  - drivers/mfd/da9052-irq.c:da9052_disable_irq_nosync
  - drivers/mfd/da9052-irq.c:da9052_disable_irq
  - drivers/mfd/da9052-irq.c:da9052_enable_irq
```
**Symbols:**

```
c0a02a40-c0a02a84: regmap_irq_get_virq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int regmap_irq_get_virq(struct regmap_irq_chip_data *data, int irq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/regmap/regmap-irq.c (c0000000009c2130)
Location: drivers/base/regmap/regmap-irq.c:965
Inline: False
Direct callers:
  - drivers/pinctrl/pinctrl-as3722.c:as3722_gpio_to_irq
  - drivers/gpio/gpio-palmas.c:palmas_gpio_to_irq
  - drivers/mfd/arizona-irq.c:arizona_map_irq
  - drivers/mfd/arizona-irq.c:arizona_map_irq
  - drivers/mfd/twl6040.c:twl6040_probe
  - drivers/mfd/twl6040.c:twl6040_probe
  - drivers/mfd/twl6040.c:twl6040_probe
  - drivers/mfd/twl6040.c:twl6040_probe
  - drivers/mfd/da9052-irq.c:da9052_free_irq
  - drivers/mfd/da9052-irq.c:da9052_request_irq
  - drivers/mfd/da9052-irq.c:da9052_disable_irq_nosync
  - drivers/mfd/da9052-irq.c:da9052_disable_irq
  - drivers/mfd/da9052-irq.c:da9052_enable_irq
```
**Symbols:**

```
c0000000009c2130-c0000000009c2198: regmap_irq_get_virq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int regmap_irq_get_virq(struct regmap_irq_chip_data *data, int irq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/regmap/regmap-irq.c (ffffffe00059cd60)
Location: drivers/base/regmap/regmap-irq.c:965
Inline: False
Direct callers:
  - drivers/pinctrl/pinctrl-as3722.c:as3722_gpio_to_irq
  - drivers/gpio/gpio-palmas.c:palmas_gpio_to_irq
  - drivers/mfd/arizona-irq.c:arizona_map_irq
  - drivers/mfd/arizona-irq.c:arizona_map_irq
  - drivers/mfd/twl6040.c:twl6040_probe
  - drivers/mfd/twl6040.c:twl6040_probe
  - drivers/mfd/twl6040.c:twl6040_probe
  - drivers/mfd/twl6040.c:twl6040_probe
  - drivers/mfd/da9052-irq.c:da9052_free_irq
  - drivers/mfd/da9052-irq.c:da9052_request_irq
  - drivers/mfd/da9052-irq.c:da9052_disable_irq_nosync
  - drivers/mfd/da9052-irq.c:da9052_disable_irq
  - drivers/mfd/da9052-irq.c:da9052_enable_irq
```
**Symbols:**

```
ffffffe00059cd60-ffffffe00059cdae: regmap_irq_get_virq (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: ✅</summary>

```c
int regmap_irq_get_virq(struct regmap_irq_chip_data *data, int irq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/regmap/regmap-irq.c (ffffffff816edba0)
Location: drivers/base/regmap/regmap-irq.c:965
Inline: False
Direct callers:
  - drivers/mfd/da9052-irq.c:da9052_free_irq
  - drivers/mfd/da9052-irq.c:da9052_request_irq
  - drivers/mfd/da9052-irq.c:da9052_disable_irq_nosync
  - drivers/mfd/da9052-irq.c:da9052_disable_irq
  - drivers/mfd/da9052-irq.c:da9052_enable_irq
```
**Symbols:**

```
ffffffff816edba0-ffffffff816edbdc: regmap_irq_get_virq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int regmap_irq_get_virq(struct regmap_irq_chip_data *data, int irq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/regmap/regmap-irq.c (ffffffff816c81e0)
Location: drivers/base/regmap/regmap-irq.c:965
Inline: False
Direct callers:
  - drivers/mfd/da9052-irq.c:da9052_free_irq
  - drivers/mfd/da9052-irq.c:da9052_request_irq
  - drivers/mfd/da9052-irq.c:da9052_disable_irq_nosync
  - drivers/mfd/da9052-irq.c:da9052_disable_irq
  - drivers/mfd/da9052-irq.c:da9052_enable_irq
```
**Symbols:**

```
ffffffff816c81e0-ffffffff816c821c: regmap_irq_get_virq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int regmap_irq_get_virq(struct regmap_irq_chip_data *data, int irq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/regmap/regmap-irq.c (ffffffff8171b280)
Location: drivers/base/regmap/regmap-irq.c:965
Inline: False
Direct callers:
  - drivers/gpio/gpio-palmas.c:palmas_gpio_to_irq
  - drivers/mfd/twl6040.c:twl6040_probe
  - drivers/mfd/twl6040.c:twl6040_probe
  - drivers/mfd/twl6040.c:twl6040_probe
  - drivers/mfd/da9052-irq.c:da9052_free_irq
  - drivers/mfd/da9052-irq.c:da9052_request_irq
  - drivers/mfd/da9052-irq.c:da9052_disable_irq_nosync
  - drivers/mfd/da9052-irq.c:da9052_disable_irq
  - drivers/mfd/da9052-irq.c:da9052_enable_irq
```
**Symbols:**

```
ffffffff8171b280-ffffffff8171b2bc: regmap_irq_get_virq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int regmap_irq_get_virq(struct regmap_irq_chip_data *data, int irq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/regmap/regmap-irq.c (ffffffff817365e0)
Location: drivers/base/regmap/regmap-irq.c:965
Inline: False
Direct callers:
  - drivers/gpio/gpio-palmas.c:palmas_gpio_to_irq
  - drivers/mfd/twl6040.c:twl6040_probe
  - drivers/mfd/twl6040.c:twl6040_probe
  - drivers/mfd/twl6040.c:twl6040_probe
  - drivers/mfd/da9052-irq.c:da9052_free_irq
  - drivers/mfd/da9052-irq.c:da9052_request_irq
  - drivers/mfd/da9052-irq.c:da9052_disable_irq_nosync
  - drivers/mfd/da9052-irq.c:da9052_disable_irq
  - drivers/mfd/da9052-irq.c:da9052_enable_irq
```
**Symbols:**

```
ffffffff817365e0-ffffffff8173661c: regmap_irq_get_virq (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>4.4</code> and <code>4.8</code> ✅
</li>
<li>
No changes between <code>4.8</code> and <code>4.10</code> ✅
</li>
<li>
No changes between <code>4.10</code> and <code>4.13</code> ✅
</li>
<li>
No changes between <code>4.13</code> and <code>4.15</code> ✅
</li>
<li>
No changes between <code>4.15</code> and <code>4.18</code> ✅
</li>
<li>
No changes between <code>4.18</code> and <code>5.0</code> ✅
</li>
<li>
No changes between <code>5.0</code> and <code>5.3</code> ✅
</li>
<li>
No changes between <code>5.3</code> and <code>5.4</code> ✅
</li>
<li>
No changes between <code>5.4</code> and <code>5.8</code> ✅
</li>
<li>
No changes between <code>5.8</code> and <code>5.11</code> ✅
</li>
<li>
No changes between <code>5.11</code> and <code>5.13</code> ✅
</li>
<li>
No changes between <code>5.13</code> and <code>5.15</code> ✅
</li>
<li>
No changes between <code>5.15</code> and <code>5.19</code> ✅
</li>
<li>
No changes between <code>5.19</code> and <code>6.2</code> ✅
</li>
<li>
No changes between <code>6.2</code> and <code>6.5</code> ✅
</li>
<li>
No changes between <code>6.5</code> and <code>6.8</code> ✅
</li>
</ul>
<b>Arch</b>
<ul>
<li>
No changes between <code>amd64</code> and <code>arm64</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>armhf</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>ppc64el</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>riscv64</code> ✅
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
No changes between <code>generic</code> and <code>aws</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>azure</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>gcp</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>lowlatency</code> ✅
</li>
</ul>
