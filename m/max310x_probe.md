# Function: <code>max310x_probe</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/tty/serial/max310x.c (ffffffff8150df4d)
Location: drivers/tty/serial/max310x.c:1081
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/tty/serial/max310x.c (ffffffff815603a7)
Location: drivers/tty/serial/max310x.c:1095
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/tty/serial/max310x.c (ffffffff8158cb0f)
Location: drivers/tty/serial/max310x.c:1095
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/tty/serial/max310x.c (ffffffff815a0bdf)
Location: drivers/tty/serial/max310x.c:1095
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/tty/serial/max310x.c (ffffffff8160630f)
Location: drivers/tty/serial/max310x.c:1091
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int max310x_probe(struct device *dev, struct max310x_devtype *devtype, struct regmap *regmap, int irq);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/serial/max310x.c (ffffffff8163eef0)
Location: drivers/tty/serial/max310x.c:1185
Inline: False
```
**Symbols:**

```
ffffffff8163eef0-ffffffff8163f7b5: max310x_probe (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int max310x_probe(struct device *dev, struct max310x_devtype *devtype, struct regmap *regmap, int irq);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/serial/max310x.c (ffffffff8165d0f0)
Location: drivers/tty/serial/max310x.c:1188
Inline: False
```
**Symbols:**

```
ffffffff8165d0f0-ffffffff8165d9d2: max310x_probe (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
int max310x_probe(struct device *dev, struct max310x_devtype *devtype, struct regmap *regmap, int irq);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/tty/serial/max310x.c (0)
Location: drivers/tty/serial/max310x.c:1227
Inline: False
```
**Symbols:**

```
ffffffff81693030-ffffffff816937d4: max310x_probe (STB_LOCAL)
ffffffff816939e1-ffffffff81693a42: max310x_probe.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
int max310x_probe(struct device *dev, struct max310x_devtype *devtype, struct regmap *regmap, int irq);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/tty/serial/max310x.c (0)
Location: drivers/tty/serial/max310x.c:1253
Inline: False
```
**Symbols:**

```
ffffffff816b5bd0-ffffffff816b6374: max310x_probe (STB_LOCAL)
ffffffff816b6581-ffffffff816b65e2: max310x_probe.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
int max310x_probe(struct device *dev, struct max310x_devtype *devtype, struct regmap *regmap, int irq);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/tty/serial/max310x.c (0)
Location: drivers/tty/serial/max310x.c:1253
Inline: False
```
**Symbols:**

```
ffffffff817691f0-ffffffff8176977b: max310x_probe (STB_LOCAL)
ffffffff81769f2c-ffffffff81769f78: max310x_probe.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
int max310x_probe(struct device *dev, const struct max310x_devtype *devtype, struct regmap *regmap, int irq);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/tty/serial/max310x.c (0)
Location: drivers/tty/serial/max310x.c:1253
Inline: False
```
**Symbols:**

```
ffffffff81784020-ffffffff8178459b: max310x_probe (STB_LOCAL)
ffffffff81c081ac-ffffffff81c081f8: max310x_probe.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
int max310x_probe(struct device *dev, const struct max310x_devtype *devtype, struct regmap *regmap, int irq);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/tty/serial/max310x.c (0)
Location: drivers/tty/serial/max310x.c:1253
Inline: False
```
**Symbols:**

```
ffffffff81767910-ffffffff81767ec2: max310x_probe (STB_LOCAL)
ffffffff81bf9d70-ffffffff81bf9dbc: max310x_probe.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int max310x_probe(struct device *dev, const struct max310x_devtype *devtype, struct regmap *regmap, int irq);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/tty/serial/max310x.c (0)
Location: drivers/tty/serial/max310x.c:1253
Inline: False
```
**Symbols:**

```
ffffffff817ec310-ffffffff817ec8dc: max310x_probe (STB_LOCAL)
ffffffff81cfa444-ffffffff81cfa48f: max310x_probe.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int max310x_probe(struct device *dev, const struct max310x_devtype *devtype, struct regmap *regmap, int irq);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/tty/serial/max310x.c (0)
Location: drivers/tty/serial/max310x.c:1252
Inline: False
```
**Symbols:**

```
ffffffff8192ae90-ffffffff8192b6cf: max310x_probe (STB_LOCAL)
ffffffff81ec2600-ffffffff81ec2663: max310x_probe.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int max310x_probe(struct device *dev, const struct max310x_devtype *devtype, const struct max310x_if_cfg *if_cfg, struct regmap **regmaps, int irq);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/serial/max310x.c (ffffffff81a895d0)
Location: drivers/tty/serial/max310x.c:1263
Inline: False
Direct callers:
  - drivers/tty/serial/max310x.c:max310x_i2c_probe
  - drivers/tty/serial/max310x.c:max310x_spi_probe
```
**Symbols:**

```
ffffffff81a895d0-ffffffff81a89eaf: max310x_probe (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int max310x_probe(struct device *dev, const struct max310x_devtype *devtype, const struct max310x_if_cfg *if_cfg, struct regmap **regmaps, int irq);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/serial/max310x.c (ffffffff81ad4d90)
Location: drivers/tty/serial/max310x.c:1267
Inline: False
Direct callers:
  - drivers/tty/serial/max310x.c:max310x_i2c_probe
  - drivers/tty/serial/max310x.c:max310x_spi_probe
```
**Symbols:**

```
ffffffff81ad4d90-ffffffff81ad5674: max310x_probe (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int max310x_probe(struct device *dev, const struct max310x_devtype *devtype, const struct max310x_if_cfg *if_cfg, struct regmap **regmaps, int irq);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/serial/max310x.c (ffffffff81b28250)
Location: drivers/tty/serial/max310x.c:1284
Inline: False
Direct callers:
  - drivers/tty/serial/max310x.c:max310x_i2c_probe
  - drivers/tty/serial/max310x.c:max310x_spi_probe
```
**Symbols:**

```
ffffffff81b28250-ffffffff81b2893a: max310x_probe (STB_LOCAL)
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
int max310x_probe(struct device *dev, struct max310x_devtype *devtype, struct regmap *regmap, int irq);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/serial/max310x.c (ffff8000108994e8)
Location: drivers/tty/serial/max310x.c:1253
Inline: False
```
**Symbols:**

```
ffff8000108994e8-ffff800010899d30: max310x_probe (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int max310x_probe(struct device *dev, struct max310x_devtype *devtype, struct regmap *regmap, int irq);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/serial/max310x.c (c0993824)
Location: drivers/tty/serial/max310x.c:1253
Inline: False
```
**Symbols:**

```
c0993824-c0994070: max310x_probe (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/tty/serial/max310x.c (c00000000093c01c)
Location: drivers/tty/serial/max310x.c:1253
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int max310x_probe(struct device *dev, struct max310x_devtype *devtype, struct regmap *regmap, int irq);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/serial/max310x.c (ffffffe00055af18)
Location: drivers/tty/serial/max310x.c:1253
Inline: False
```
**Symbols:**

```
ffffffe00055af18-ffffffe00055b590: max310x_probe (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Transformation ⚠️</summary>

```c
int max310x_probe(struct device *dev, struct max310x_devtype *devtype, struct regmap *regmap, int irq);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/tty/serial/max310x.c (0)
Location: drivers/tty/serial/max310x.c:1253
Inline: False
```
**Symbols:**

```
ffffffff8167b630-ffffffff8167bdd4: max310x_probe (STB_LOCAL)
ffffffff8167bfe1-ffffffff8167c042: max310x_probe.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Transformation ⚠️</summary>

```c
int max310x_probe(struct device *dev, struct max310x_devtype *devtype, struct regmap *regmap, int irq);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/tty/serial/max310x.c (0)
Location: drivers/tty/serial/max310x.c:1253
Inline: False
```
**Symbols:**

```
ffffffff8165a720-ffffffff8165aec4: max310x_probe (STB_LOCAL)
ffffffff8165b0d1-ffffffff8165b132: max310x_probe.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Transformation ⚠️</summary>

```c
int max310x_probe(struct device *dev, struct max310x_devtype *devtype, struct regmap *regmap, int irq);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/tty/serial/max310x.c (0)
Location: drivers/tty/serial/max310x.c:1253
Inline: False
```
**Symbols:**

```
ffffffff816a9a10-ffffffff816aa1b4: max310x_probe (STB_LOCAL)
ffffffff816aa3c1-ffffffff816aa422: max310x_probe.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
int max310x_probe(struct device *dev, struct max310x_devtype *devtype, struct regmap *regmap, int irq);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/tty/serial/max310x.c (0)
Location: drivers/tty/serial/max310x.c:1253
Inline: False
```
**Symbols:**

```
ffffffff816c3e70-ffffffff816c4614: max310x_probe (STB_LOCAL)
ffffffff816c4821-ffffffff816c4882: max310x_probe.cold (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
<details>
<summary>Changed between <code>5.8</code> and <code>5.11</code> ⚠️</summary>
<ul>
<li>
<b>Param type changed. </b>
<code>struct max310x_devtype *devtype</code> ➡️ <code>const struct max310x_devtype *devtype</code>
</li>
</ul>
</details>
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
<details>
<summary>Changed between <code>5.19</code> and <code>6.2</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>const struct max310x_if_cfg *if_cfg</code>
</li>
<li>
<b>Param added. </b>
<code>struct regmap **regmaps</code>
</li>
<li>
<b>Param removed. </b>
<code>struct regmap *regmap</code>
</li>
<li>
<b>Param reordered. </b>
<code>dev, devtype, regmap, irq</code> ➡️ <code>dev, devtype, if_cfg, regmaps, irq</code>
</li>
</ul>
</details>
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
