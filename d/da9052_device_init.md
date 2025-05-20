# Function: <code>da9052_device_init</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int da9052_device_init(struct da9052 *da9052, u8 chip_id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/mfd/da9052-core.c (ffffffff8158d310)
Location: drivers/mfd/da9052-core.c:544
Inline: False
Direct callers:
  - drivers/mfd/da9052-spi.c:da9052_spi_probe
  - drivers/mfd/da9052-i2c.c:da9052_i2c_probe
```
**Symbols:**

```
ffffffff8158d310-ffffffff8158d412: da9052_device_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int da9052_device_init(struct da9052 *da9052, u8 chip_id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/mfd/da9052-core.c (ffffffff815e2520)
Location: drivers/mfd/da9052-core.c:544
Inline: False
Direct callers:
  - drivers/mfd/da9052-spi.c:da9052_spi_probe
  - drivers/mfd/da9052-i2c.c:da9052_i2c_probe
```
**Symbols:**

```
ffffffff815e2520-ffffffff815e2621: da9052_device_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int da9052_device_init(struct da9052 *da9052, u8 chip_id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/mfd/da9052-core.c (ffffffff8160f1c0)
Location: drivers/mfd/da9052-core.c:591
Inline: False
Direct callers:
  - drivers/mfd/da9052-spi.c:da9052_spi_probe
  - drivers/mfd/da9052-i2c.c:da9052_i2c_probe
```
**Symbols:**

```
ffffffff8160f1c0-ffffffff8160f4dc: da9052_device_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int da9052_device_init(struct da9052 *da9052, u8 chip_id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/mfd/da9052-core.c (ffffffff816232c0)
Location: drivers/mfd/da9052-core.c:591
Inline: False
Direct callers:
  - drivers/mfd/da9052-spi.c:da9052_spi_probe
  - drivers/mfd/da9052-i2c.c:da9052_i2c_probe
```
**Symbols:**

```
ffffffff816232c0-ffffffff8162359e: da9052_device_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int da9052_device_init(struct da9052 *da9052, u8 chip_id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/mfd/da9052-core.c (ffffffff8168bb30)
Location: drivers/mfd/da9052-core.c:595
Inline: False
Direct callers:
  - drivers/mfd/da9052-spi.c:da9052_spi_probe
  - drivers/mfd/da9052-i2c.c:da9052_i2c_probe
```
**Symbols:**

```
ffffffff8168bb30-ffffffff8168be75: da9052_device_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int da9052_device_init(struct da9052 *da9052, u8 chip_id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/mfd/da9052-core.c (ffffffff816c7bf0)
Location: drivers/mfd/da9052-core.c:595
Inline: False
Direct callers:
  - drivers/mfd/da9052-spi.c:da9052_spi_probe
  - drivers/mfd/da9052-i2c.c:da9052_i2c_probe
```
**Symbols:**

```
ffffffff816c7bf0-ffffffff816c7f40: da9052_device_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int da9052_device_init(struct da9052 *da9052, u8 chip_id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/mfd/da9052-core.c (ffffffff816e90b0)
Location: drivers/mfd/da9052-core.c:595
Inline: False
Direct callers:
  - drivers/mfd/da9052-spi.c:da9052_spi_probe
  - drivers/mfd/da9052-i2c.c:da9052_i2c_probe
```
**Symbols:**

```
ffffffff816e90b0-ffffffff816e9400: da9052_device_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
int da9052_device_init(struct da9052 *da9052, u8 chip_id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/mfd/da9052-core.c (0)
Location: drivers/mfd/da9052-core.c:591
Inline: False
Direct callers:
  - drivers/mfd/da9052-spi.c:da9052_spi_probe
  - drivers/mfd/da9052-i2c.c:da9052_i2c_probe
```
**Symbols:**

```
ffffffff81722b2a-ffffffff81722b9b: da9052_device_init.cold (STB_LOCAL)
ffffffff817229a0-ffffffff81722abf: da9052_device_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
int da9052_device_init(struct da9052 *da9052, u8 chip_id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/mfd/da9052-core.c (0)
Location: drivers/mfd/da9052-core.c:591
Inline: False
Direct callers:
  - drivers/mfd/da9052-spi.c:da9052_spi_probe
  - drivers/mfd/da9052-i2c.c:da9052_i2c_probe
```
**Symbols:**

```
ffffffff81746dca-ffffffff81746e3b: da9052_device_init.cold (STB_LOCAL)
ffffffff81746c40-ffffffff81746d5f: da9052_device_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
int da9052_device_init(struct da9052 *da9052, u8 chip_id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/mfd/da9052-core.c (0)
Location: drivers/mfd/da9052-core.c:591
Inline: False
Direct callers:
  - drivers/mfd/da9052-spi.c:da9052_spi_probe
  - drivers/mfd/da9052-i2c.c:da9052_i2c_probe
```
**Symbols:**

```
ffffffff81804acc-ffffffff81804b3d: da9052_device_init.cold (STB_LOCAL)
ffffffff81804940-ffffffff81804a5f: da9052_device_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
int da9052_device_init(struct da9052 *da9052, u8 chip_id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/mfd/da9052-core.c (0)
Location: drivers/mfd/da9052-core.c:591
Inline: False
Direct callers:
  - drivers/mfd/da9052-spi.c:da9052_spi_probe
  - drivers/mfd/da9052-i2c.c:da9052_i2c_probe
```
**Symbols:**

```
ffffffff81c13a66-ffffffff81c13ad7: da9052_device_init.cold (STB_LOCAL)
ffffffff81815370-ffffffff8181548f: da9052_device_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
int da9052_device_init(struct da9052 *da9052, u8 chip_id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/mfd/da9052-core.c (0)
Location: drivers/mfd/da9052-core.c:591
Inline: False
Direct callers:
  - drivers/mfd/da9052-spi.c:da9052_spi_probe
  - drivers/mfd/da9052-i2c.c:da9052_i2c_probe
```
**Symbols:**

```
ffffffff81c05bde-ffffffff81c05c4d: da9052_device_init.cold (STB_LOCAL)
ffffffff817f9a50-ffffffff817f9b6f: da9052_device_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int da9052_device_init(struct da9052 *da9052, u8 chip_id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/mfd/da9052-core.c (0)
Location: drivers/mfd/da9052-core.c:591
Inline: False
Direct callers:
  - drivers/mfd/da9052-spi.c:da9052_spi_probe
  - drivers/mfd/da9052-i2c.c:da9052_i2c_probe
```
**Symbols:**

```
ffffffff81d090a0-ffffffff81d0910f: da9052_device_init.cold (STB_LOCAL)
ffffffff81882f00-ffffffff8188301f: da9052_device_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int da9052_device_init(struct da9052 *da9052, u8 chip_id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/mfd/da9052-core.c (0)
Location: drivers/mfd/da9052-core.c:591
Inline: False
Direct callers:
  - drivers/mfd/da9052-spi.c:da9052_spi_probe
  - drivers/mfd/da9052-i2c.c:da9052_i2c_probe
```
**Symbols:**

```
ffffffff81ed14e2-ffffffff81ed154c: da9052_device_init.cold (STB_LOCAL)
ffffffff819cb8d0-ffffffff819cba0c: da9052_device_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int da9052_device_init(struct da9052 *da9052, u8 chip_id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/mfd/da9052-core.c (ffffffff81b43450)
Location: drivers/mfd/da9052-core.c:591
Inline: False
Direct callers:
  - drivers/mfd/da9052-spi.c:da9052_spi_probe
  - drivers/mfd/da9052-i2c.c:da9052_i2c_probe
```
**Symbols:**

```
ffffffff81b43450-ffffffff81b43605: da9052_device_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int da9052_device_init(struct da9052 *da9052, u8 chip_id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/mfd/da9052-core.c (ffffffff81b967c0)
Location: drivers/mfd/da9052-core.c:591
Inline: False
Direct callers:
  - drivers/mfd/da9052-spi.c:da9052_spi_probe
  - drivers/mfd/da9052-i2c.c:da9052_i2c_probe
```
**Symbols:**

```
ffffffff81b967c0-ffffffff81b96975: da9052_device_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int da9052_device_init(struct da9052 *da9052, u8 chip_id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/mfd/da9052-core.c (ffffffff81bea790)
Location: drivers/mfd/da9052-core.c:591
Inline: False
Direct callers:
  - drivers/mfd/da9052-spi.c:da9052_spi_probe
  - drivers/mfd/da9052-i2c.c:da9052_i2c_probe
```
**Symbols:**

```
ffffffff81bea790-ffffffff81bea945: da9052_device_init (STB_GLOBAL)
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
int da9052_device_init(struct da9052 *da9052, u8 chip_id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/mfd/da9052-core.c (ffff800010943698)
Location: drivers/mfd/da9052-core.c:591
Inline: False
Direct callers:
  - drivers/mfd/da9052-spi.c:da9052_spi_probe
  - drivers/mfd/da9052-i2c.c:da9052_i2c_probe
```
**Symbols:**

```
ffff800010943698-ffff800010943818: da9052_device_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int da9052_device_init(struct da9052 *da9052, u8 chip_id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/mfd/da9052-core.c (c0a2c614)
Location: drivers/mfd/da9052-core.c:591
Inline: False
Direct callers:
  - drivers/mfd/da9052-spi.c:da9052_spi_probe
  - drivers/mfd/da9052-i2c.c:da9052_i2c_probe
```
**Symbols:**

```
c0a2c614-c0a2c9d0: da9052_device_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int da9052_device_init(struct da9052 *da9052, u8 chip_id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/mfd/da9052-core.c (c0000000009eca00)
Location: drivers/mfd/da9052-core.c:591
Inline: False
Direct callers:
  - drivers/mfd/da9052-spi.c:da9052_spi_probe
  - drivers/mfd/da9052-i2c.c:da9052_i2c_probe
```
**Symbols:**

```
c0000000009eca00-c0000000009ecea8: da9052_device_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int da9052_device_init(struct da9052 *da9052, u8 chip_id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/mfd/da9052-core.c (ffffffe0005b61bc)
Location: drivers/mfd/da9052-core.c:591
Inline: False
Direct callers:
  - drivers/mfd/da9052-spi.c:da9052_spi_probe
  - drivers/mfd/da9052-i2c.c:da9052_i2c_probe
```
**Symbols:**

```
ffffffe0005b61bc-ffffffe0005b64e8: da9052_device_init (STB_GLOBAL)
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
int da9052_device_init(struct da9052 *da9052, u8 chip_id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/mfd/da9052-core.c (0)
Location: drivers/mfd/da9052-core.c:591
Inline: False
Direct callers:
  - drivers/mfd/da9052-spi.c:da9052_spi_probe
```
**Symbols:**

```
ffffffff81703e3a-ffffffff81703eab: da9052_device_init.cold (STB_LOCAL)
ffffffff81703cb0-ffffffff81703dcf: da9052_device_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Transformation ⚠️</summary>

```c
int da9052_device_init(struct da9052 *da9052, u8 chip_id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/mfd/da9052-core.c (0)
Location: drivers/mfd/da9052-core.c:591
Inline: False
Direct callers:
  - drivers/mfd/da9052-spi.c:da9052_spi_probe
```
**Symbols:**

```
ffffffff816d7c3a-ffffffff816d7cab: da9052_device_init.cold (STB_LOCAL)
ffffffff816d7ab0-ffffffff816d7bcf: da9052_device_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Transformation ⚠️</summary>

```c
int da9052_device_init(struct da9052 *da9052, u8 chip_id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/mfd/da9052-core.c (0)
Location: drivers/mfd/da9052-core.c:591
Inline: False
Direct callers:
  - drivers/mfd/da9052-spi.c:da9052_spi_probe
  - drivers/mfd/da9052-i2c.c:da9052_i2c_probe
```
**Symbols:**

```
ffffffff8173a28a-ffffffff8173a2fb: da9052_device_init.cold (STB_LOCAL)
ffffffff8173a100-ffffffff8173a21f: da9052_device_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
int da9052_device_init(struct da9052 *da9052, u8 chip_id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/mfd/da9052-core.c (0)
Location: drivers/mfd/da9052-core.c:591
Inline: False
Direct callers:
  - drivers/mfd/da9052-spi.c:da9052_spi_probe
  - drivers/mfd/da9052-i2c.c:da9052_i2c_probe
```
**Symbols:**

```
ffffffff817556ca-ffffffff8175573b: da9052_device_init.cold (STB_LOCAL)
ffffffff81755540-ffffffff8175565f: da9052_device_init (STB_GLOBAL)
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
