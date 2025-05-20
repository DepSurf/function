# Function: <code>wm831x_device_init</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int wm831x_device_init(struct wm831x *wm831x, long unsigned int id, int irq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/mfd/wm831x-core.c (ffffffff815827a0)
Location: drivers/mfd/wm831x-core.c:1619
Inline: False
Direct callers:
  - drivers/mfd/wm831x-i2c.c:wm831x_i2c_probe
  - drivers/mfd/wm831x-spi.c:wm831x_spi_probe
```
**Symbols:**

```
ffffffff815827a0-ffffffff81582ece: wm831x_device_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int wm831x_device_init(struct wm831x *wm831x, long unsigned int id, int irq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/mfd/wm831x-core.c (ffffffff815d8890)
Location: drivers/mfd/wm831x-core.c:1619
Inline: False
Direct callers:
  - drivers/mfd/wm831x-i2c.c:wm831x_i2c_probe
  - drivers/mfd/wm831x-spi.c:wm831x_spi_probe
```
**Symbols:**

```
ffffffff815d8890-ffffffff815d8fe1: wm831x_device_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int wm831x_device_init(struct wm831x *wm831x, long unsigned int id, int irq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/mfd/wm831x-core.c (ffffffff81605580)
Location: drivers/mfd/wm831x-core.c:1619
Inline: False
Direct callers:
  - drivers/mfd/wm831x-i2c.c:wm831x_i2c_probe
  - drivers/mfd/wm831x-spi.c:wm831x_spi_probe
```
**Symbols:**

```
ffffffff81605580-ffffffff81605cd1: wm831x_device_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int wm831x_device_init(struct wm831x *wm831x, int irq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/mfd/wm831x-core.c (ffffffff81619420)
Location: drivers/mfd/wm831x-core.c:1633
Inline: False
Direct callers:
  - drivers/mfd/wm831x-i2c.c:wm831x_i2c_probe
  - drivers/mfd/wm831x-spi.c:wm831x_spi_probe
```
**Symbols:**

```
ffffffff81619420-ffffffff81619ab0: wm831x_device_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int wm831x_device_init(struct wm831x *wm831x, int irq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/mfd/wm831x-core.c (ffffffff81681ad0)
Location: drivers/mfd/wm831x-core.c:1633
Inline: False
Direct callers:
  - drivers/mfd/wm831x-i2c.c:wm831x_i2c_probe
  - drivers/mfd/wm831x-spi.c:wm831x_spi_probe
```
**Symbols:**

```
ffffffff81681ad0-ffffffff81682178: wm831x_device_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int wm831x_device_init(struct wm831x *wm831x, int irq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/mfd/wm831x-core.c (ffffffff816bdb30)
Location: drivers/mfd/wm831x-core.c:1633
Inline: False
Direct callers:
  - drivers/mfd/wm831x-i2c.c:wm831x_i2c_probe
  - drivers/mfd/wm831x-spi.c:wm831x_spi_probe
```
**Symbols:**

```
ffffffff816bdb30-ffffffff816be1d1: wm831x_device_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int wm831x_device_init(struct wm831x *wm831x, int irq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/mfd/wm831x-core.c (ffffffff816dee70)
Location: drivers/mfd/wm831x-core.c:1633
Inline: False
Direct callers:
  - drivers/mfd/wm831x-i2c.c:wm831x_i2c_probe
  - drivers/mfd/wm831x-spi.c:wm831x_spi_probe
```
**Symbols:**

```
ffffffff816dee70-ffffffff816df598: wm831x_device_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
int wm831x_device_init(struct wm831x *wm831x, int irq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/mfd/wm831x-core.c (0)
Location: drivers/mfd/wm831x-core.c:1629
Inline: False
Direct callers:
  - drivers/mfd/wm831x-i2c.c:wm831x_i2c_probe
  - drivers/mfd/wm831x-spi.c:wm831x_spi_probe
```
**Symbols:**

```
ffffffff817187e7-ffffffff81718db9: wm831x_device_init.cold (STB_LOCAL)
ffffffff817185f0-ffffffff817186e1: wm831x_device_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
int wm831x_device_init(struct wm831x *wm831x, int irq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/mfd/wm831x-core.c (0)
Location: drivers/mfd/wm831x-core.c:1629
Inline: False
Direct callers:
  - drivers/mfd/wm831x-i2c.c:wm831x_i2c_probe
  - drivers/mfd/wm831x-spi.c:wm831x_spi_probe
```
**Symbols:**

```
ffffffff8173cad1-ffffffff8173d0a2: wm831x_device_init.cold (STB_LOCAL)
ffffffff8173c900-ffffffff8173c9f1: wm831x_device_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
int wm831x_device_init(struct wm831x *wm831x, int irq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/mfd/wm831x-core.c (0)
Location: drivers/mfd/wm831x-core.c:1629
Inline: False
Direct callers:
  - drivers/mfd/wm831x-i2c.c:wm831x_i2c_probe
  - drivers/mfd/wm831x-spi.c:wm831x_spi_probe
```
**Symbols:**

```
ffffffff817fa470-ffffffff817faa22: wm831x_device_init.cold (STB_LOCAL)
ffffffff817fa2a0-ffffffff817fa391: wm831x_device_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
int wm831x_device_init(struct wm831x *wm831x, int irq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/mfd/wm831x-core.c (0)
Location: drivers/mfd/wm831x-core.c:1633
Inline: False
Direct callers:
  - drivers/mfd/wm831x-i2c.c:wm831x_i2c_probe
  - drivers/mfd/wm831x-spi.c:wm831x_spi_probe
```
**Symbols:**

```
ffffffff81c11b14-ffffffff81c120c6: wm831x_device_init.cold (STB_LOCAL)
ffffffff8180cc20-ffffffff8180cd11: wm831x_device_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
int wm831x_device_init(struct wm831x *wm831x, int irq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/mfd/wm831x-core.c (0)
Location: drivers/mfd/wm831x-core.c:1633
Inline: False
Direct callers:
  - drivers/mfd/wm831x-i2c.c:wm831x_i2c_probe
  - drivers/mfd/wm831x-spi.c:wm831x_spi_probe
```
**Symbols:**

```
ffffffff81c03c8b-ffffffff81c0423b: wm831x_device_init.cold (STB_LOCAL)
ffffffff817f13f0-ffffffff817f14e1: wm831x_device_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int wm831x_device_init(struct wm831x *wm831x, int irq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/mfd/wm831x-core.c (0)
Location: drivers/mfd/wm831x-core.c:1457
Inline: False
Direct callers:
  - drivers/mfd/wm831x-i2c.c:wm831x_i2c_probe
  - drivers/mfd/wm831x-spi.c:wm831x_spi_probe
```
**Symbols:**

```
ffffffff81d06b63-ffffffff81d071b1: wm831x_device_init.cold (STB_LOCAL)
ffffffff81879a90-ffffffff81879b90: wm831x_device_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int wm831x_device_init(struct wm831x *wm831x, int irq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/mfd/wm831x-core.c (0)
Location: drivers/mfd/wm831x-core.c:1457
Inline: False
Direct callers:
  - drivers/mfd/wm831x-i2c.c:wm831x_i2c_probe
  - drivers/mfd/wm831x-spi.c:wm831x_spi_probe
```
**Symbols:**

```
ffffffff81ecf4a8-ffffffff81ecfac5: wm831x_device_init.cold (STB_LOCAL)
ffffffff819c21c0-ffffffff819c22d4: wm831x_device_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
int wm831x_device_init(struct wm831x *wm831x, int irq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/mfd/wm831x-core.c (0)
Location: drivers/mfd/wm831x-core.c:1457
Inline: False
Direct callers:
  - drivers/mfd/wm831x-i2c.c:wm831x_i2c_probe
  - drivers/mfd/wm831x-spi.c:wm831x_spi_probe
```
**Symbols:**

```
ffffffff82099d39-ffffffff82099d77: wm831x_device_init.cold (STB_LOCAL)
ffffffff81b37cb0-ffffffff81b3845b: wm831x_device_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
int wm831x_device_init(struct wm831x *wm831x, int irq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/mfd/wm831x-core.c (0)
Location: drivers/mfd/wm831x-core.c:1457
Inline: False
Direct callers:
  - drivers/mfd/wm831x-i2c.c:wm831x_i2c_probe
  - drivers/mfd/wm831x-spi.c:wm831x_spi_probe
```
**Symbols:**

```
ffffffff8211ae4e-ffffffff8211ae8c: wm831x_device_init.cold (STB_LOCAL)
ffffffff81b8b120-ffffffff81b8b8c6: wm831x_device_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
int wm831x_device_init(struct wm831x *wm831x, int irq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/mfd/wm831x-core.c (0)
Location: drivers/mfd/wm831x-core.c:1456
Inline: False
Direct callers:
  - drivers/mfd/wm831x-i2c.c:wm831x_i2c_probe
  - drivers/mfd/wm831x-spi.c:wm831x_spi_probe
```
**Symbols:**

```
ffffffff821f8cd5-ffffffff821f8d13: wm831x_device_init.cold (STB_LOCAL)
ffffffff81bdf020-ffffffff81bdf7c6: wm831x_device_init (STB_GLOBAL)
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
int wm831x_device_init(struct wm831x *wm831x, int irq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/mfd/wm831x-core.c (ffff800010937b08)
Location: drivers/mfd/wm831x-core.c:1629
Inline: False
Direct callers:
  - drivers/mfd/wm831x-i2c.c:wm831x_i2c_probe
  - drivers/mfd/wm831x-spi.c:wm831x_spi_probe
```
**Symbols:**

```
ffff800010937b08-ffff80001093820c: wm831x_device_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int wm831x_device_init(struct wm831x *wm831x, int irq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/mfd/wm831x-core.c (c0a1ff74)
Location: drivers/mfd/wm831x-core.c:1629
Inline: False
Direct callers:
  - drivers/mfd/wm831x-i2c.c:wm831x_i2c_probe
  - drivers/mfd/wm831x-spi.c:wm831x_spi_probe
```
**Symbols:**

```
c0a1ff74-c0a206c8: wm831x_device_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int wm831x_device_init(struct wm831x *wm831x, int irq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/mfd/wm831x-core.c (c0000000009de3a0)
Location: drivers/mfd/wm831x-core.c:1629
Inline: False
Direct callers:
  - drivers/mfd/wm831x-i2c.c:wm831x_i2c_probe
  - drivers/mfd/wm831x-spi.c:wm831x_spi_probe
```
**Symbols:**

```
c0000000009de3a0-c0000000009dec6c: wm831x_device_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int wm831x_device_init(struct wm831x *wm831x, int irq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/mfd/wm831x-core.c (ffffffe0005aca2c)
Location: drivers/mfd/wm831x-core.c:1629
Inline: False
Direct callers:
  - drivers/mfd/wm831x-i2c.c:wm831x_i2c_probe
  - drivers/mfd/wm831x-spi.c:wm831x_spi_probe
```
**Symbols:**

```
ffffffe0005aca2c-ffffffe0005acfec: wm831x_device_init (STB_GLOBAL)
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
int wm831x_device_init(struct wm831x *wm831x, int irq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/mfd/wm831x-core.c (0)
Location: drivers/mfd/wm831x-core.c:1629
Inline: False
Direct callers:
  - drivers/mfd/wm831x-spi.c:wm831x_spi_probe
```
**Symbols:**

```
ffffffff817005b1-ffffffff81700b82: wm831x_device_init.cold (STB_LOCAL)
ffffffff817003e0-ffffffff817004d1: wm831x_device_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Transformation ⚠️</summary>

```c
int wm831x_device_init(struct wm831x *wm831x, int irq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/mfd/wm831x-core.c (0)
Location: drivers/mfd/wm831x-core.c:1629
Inline: False
Direct callers:
  - drivers/mfd/wm831x-spi.c:wm831x_spi_probe
```
**Symbols:**

```
ffffffff816d43c1-ffffffff816d4992: wm831x_device_init.cold (STB_LOCAL)
ffffffff816d41f0-ffffffff816d42e1: wm831x_device_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Transformation ⚠️</summary>

```c
int wm831x_device_init(struct wm831x *wm831x, int irq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/mfd/wm831x-core.c (0)
Location: drivers/mfd/wm831x-core.c:1629
Inline: False
Direct callers:
  - drivers/mfd/wm831x-i2c.c:wm831x_i2c_probe
  - drivers/mfd/wm831x-spi.c:wm831x_spi_probe
```
**Symbols:**

```
ffffffff8172ff91-ffffffff81730562: wm831x_device_init.cold (STB_LOCAL)
ffffffff8172fdc0-ffffffff8172feb1: wm831x_device_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
int wm831x_device_init(struct wm831x *wm831x, int irq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/mfd/wm831x-core.c (0)
Location: drivers/mfd/wm831x-core.c:1629
Inline: False
Direct callers:
  - drivers/mfd/wm831x-i2c.c:wm831x_i2c_probe
  - drivers/mfd/wm831x-spi.c:wm831x_spi_probe
```
**Symbols:**

```
ffffffff8174b3d1-ffffffff8174b9a2: wm831x_device_init.cold (STB_LOCAL)
ffffffff8174b200-ffffffff8174b2f1: wm831x_device_init (STB_GLOBAL)
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
<details>
<summary>Changed between <code>4.10</code> and <code>4.13</code> ⚠️</summary>
<ul>
<li>
<b>Param removed. </b>
<code>long unsigned int id</code>
</li>
<li>
<b>Param reordered. </b>
<code>wm831x, id, irq</code> ➡️ <code>wm831x, irq</code>
</li>
</ul>
</details>
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
