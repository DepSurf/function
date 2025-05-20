# Function: <code>gpiod_direction_output_raw_commit</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4</code>: Absent ⚠️
</li>
<li>
In <code>4.8</code>: Absent ⚠️
</li>
<li>
In <code>4.10</code>: Absent ⚠️
</li>
<li>
In <code>4.13</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int gpiod_direction_output_raw_commit(struct gpio_desc *desc, int value);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib.c (ffffffff814d96e0)
Location: drivers/gpio/gpiolib.c:2418
Inline: False
```
**Symbols:**

```
ffffffff814d96e0-ffffffff814d9851: gpiod_direction_output_raw_commit (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Transformation ⚠️</summary>

```c
int gpiod_direction_output_raw_commit(struct gpio_desc *desc, int value);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/gpio/gpiolib.c (0)
Location: drivers/gpio/gpiolib.c:2532
Inline: False
Direct callers:
  - drivers/gpio/gpiolib.c:gpiod_direction_output
  - drivers/gpio/gpiolib.c:gpiod_direction_output
  - drivers/gpio/gpiolib.c:gpiod_direction_output_raw
```
**Symbols:**

```
ffffffff81508c80-ffffffff81508dbb: gpiod_direction_output_raw_commit (STB_LOCAL)
ffffffff8150be79-ffffffff8150beaf: gpiod_direction_output_raw_commit.cold.49 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Transformation ⚠️</summary>

```c
int gpiod_direction_output_raw_commit(struct gpio_desc *desc, int value);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/gpio/gpiolib.c (0)
Location: drivers/gpio/gpiolib.c:2589
Inline: False
Direct callers:
  - drivers/gpio/gpiolib.c:gpiod_direction_output
  - drivers/gpio/gpiolib.c:gpiod_direction_output
  - drivers/gpio/gpiolib.c:gpiod_direction_output_raw
```
**Symbols:**

```
ffffffff8151d950-ffffffff8151db00: gpiod_direction_output_raw_commit (STB_LOCAL)
ffffffff81520d4f-ffffffff81520dce: gpiod_direction_output_raw_commit.cold.47 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
int gpiod_direction_output_raw_commit(struct gpio_desc *desc, int value);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/gpio/gpiolib.c (0)
Location: drivers/gpio/gpiolib.c:2677
Inline: False
Direct callers:
  - drivers/gpio/gpiolib.c:gpiod_direction_output
  - drivers/gpio/gpiolib.c:gpiod_direction_output
  - drivers/gpio/gpiolib.c:gpiod_direction_output_raw
```
**Symbols:**

```
ffffffff8154ba60-ffffffff8154bc0a: gpiod_direction_output_raw_commit (STB_LOCAL)
ffffffff8154f0a1-ffffffff8154f11e: gpiod_direction_output_raw_commit.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
int gpiod_direction_output_raw_commit(struct gpio_desc *desc, int value);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/gpio/gpiolib.c (0)
Location: drivers/gpio/gpiolib.c:3009
Inline: False
Direct callers:
  - drivers/gpio/gpiolib.c:gpiod_direction_output
  - drivers/gpio/gpiolib.c:gpiod_direction_output
  - drivers/gpio/gpiolib.c:gpiod_direction_output_raw
```
**Symbols:**

```
ffffffff8156cc40-ffffffff8156cdea: gpiod_direction_output_raw_commit (STB_LOCAL)
ffffffff815705fd-ffffffff8157067a: gpiod_direction_output_raw_commit.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
int gpiod_direction_output_raw_commit(struct gpio_desc *desc, int value);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/gpio/gpiolib.c (0)
Location: drivers/gpio/gpiolib.c:3412
Inline: False
Direct callers:
  - drivers/gpio/gpiolib.c:gpiod_direction_output
  - drivers/gpio/gpiolib.c:gpiod_direction_output_raw
```
**Symbols:**

```
ffffffff8160fbe0-ffffffff8160fd8e: gpiod_direction_output_raw_commit (STB_LOCAL)
ffffffff816145be-ffffffff8161463e: gpiod_direction_output_raw_commit.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
int gpiod_direction_output_raw_commit(struct gpio_desc *desc, int value);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/gpio/gpiolib.c (0)
Location: drivers/gpio/gpiolib.c:2255
Inline: False
Direct callers:
  - drivers/gpio/gpiolib.c:gpiod_direction_output
  - drivers/gpio/gpiolib.c:gpiod_direction_output_raw
```
**Symbols:**

```
ffffffff81635ba0-ffffffff81635d3f: gpiod_direction_output_raw_commit (STB_LOCAL)
ffffffff81bf5d6e-ffffffff81bf5df1: gpiod_direction_output_raw_commit.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
int gpiod_direction_output_raw_commit(struct gpio_desc *desc, int value);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/gpio/gpiolib.c (0)
Location: drivers/gpio/gpiolib.c:2232
Inline: False
Direct callers:
  - drivers/gpio/gpiolib.c:gpiod_direction_output
  - drivers/gpio/gpiolib.c:gpiod_direction_output_raw
```
**Symbols:**

```
ffffffff81619ff0-ffffffff8161a1a3: gpiod_direction_output_raw_commit (STB_LOCAL)
ffffffff81be7d04-ffffffff81be7d87: gpiod_direction_output_raw_commit.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int gpiod_direction_output_raw_commit(struct gpio_desc *desc, int value);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/gpio/gpiolib.c (0)
Location: drivers/gpio/gpiolib.c:2261
Inline: False
Direct callers:
  - drivers/gpio/gpiolib.c:gpiod_direction_output
  - drivers/gpio/gpiolib.c:gpiod_direction_output_raw
```
**Symbols:**

```
ffffffff816893f0-ffffffff816895a0: gpiod_direction_output_raw_commit (STB_LOCAL)
ffffffff81ce188e-ffffffff81ce1911: gpiod_direction_output_raw_commit.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int gpiod_direction_output_raw_commit(struct gpio_desc *desc, int value);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/gpio/gpiolib.c (0)
Location: drivers/gpio/gpiolib.c:2322
Inline: False
Direct callers:
  - drivers/gpio/gpiolib.c:gpiod_direction_output
  - drivers/gpio/gpiolib.c:gpiod_direction_output_raw
```
**Symbols:**

```
ffffffff817a6040-ffffffff817a622c: gpiod_direction_output_raw_commit (STB_LOCAL)
ffffffff81ea810b-ffffffff81ea8186: gpiod_direction_output_raw_commit.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int gpiod_direction_output_raw_commit(struct gpio_desc *desc, int value);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib.c (ffffffff818be080)
Location: drivers/gpio/gpiolib.c:2392
Inline: False
Direct callers:
  - drivers/gpio/gpiolib.c:gpiod_direction_output
  - drivers/gpio/gpiolib.c:gpiod_direction_output_raw
```
**Symbols:**

```
ffffffff818be080-ffffffff818be2c8: gpiod_direction_output_raw_commit (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int gpiod_direction_output_raw_commit(struct gpio_desc *desc, int value);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib.c (ffffffff81901130)
Location: drivers/gpio/gpiolib.c:2433
Inline: False
Direct callers:
  - drivers/gpio/gpiolib.c:gpiod_direction_output
  - drivers/gpio/gpiolib.c:gpiod_direction_output_raw
```
**Symbols:**

```
ffffffff81901130-ffffffff81901378: gpiod_direction_output_raw_commit (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int gpiod_direction_output_raw_commit(struct gpio_desc *desc, int value);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib.c (ffffffff81948a60)
Location: drivers/gpio/gpiolib.c:2627
Inline: False
Direct callers:
  - drivers/gpio/gpiolib.c:gpiod_direction_output
  - drivers/gpio/gpiolib.c:gpiod_direction_output_raw
```
**Symbols:**

```
ffffffff81948a60-ffffffff81948c7e: gpiod_direction_output_raw_commit (STB_LOCAL)
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
int gpiod_direction_output_raw_commit(struct gpio_desc *desc, int value);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib.c (ffff8000106c0a20)
Location: drivers/gpio/gpiolib.c:3009
Inline: False
Direct callers:
  - drivers/gpio/gpiolib.c:gpiod_direction_output
  - drivers/gpio/gpiolib.c:gpiod_direction_output
  - drivers/gpio/gpiolib.c:gpiod_direction_output_raw
```
**Symbols:**

```
ffff8000106c0a20-ffff8000106c0cb4: gpiod_direction_output_raw_commit (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int gpiod_direction_output_raw_commit(struct gpio_desc *desc, int value);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib.c (c0860874)
Location: drivers/gpio/gpiolib.c:3009
Inline: False
Direct callers:
  - drivers/gpio/gpiolib.c:gpiod_direction_output
  - drivers/gpio/gpiolib.c:gpiod_direction_output
  - drivers/gpio/gpiolib.c:gpiod_direction_output_raw
```
**Symbols:**

```
c0860874-c0860adc: gpiod_direction_output_raw_commit (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int gpiod_direction_output_raw_commit(struct gpio_desc *desc, int value);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib.c (c00000000083e220)
Location: drivers/gpio/gpiolib.c:3009
Inline: False
Direct callers:
  - drivers/gpio/gpiolib.c:gpiod_direction_output
  - drivers/gpio/gpiolib.c:gpiod_direction_output
  - drivers/gpio/gpiolib.c:gpiod_direction_output_raw
```
**Symbols:**

```
c00000000083e220-c00000000083e534: gpiod_direction_output_raw_commit (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int gpiod_direction_output_raw_commit(struct gpio_desc *desc, int value);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib.c (ffffffe0004a7478)
Location: drivers/gpio/gpiolib.c:3009
Inline: False
Direct callers:
  - drivers/gpio/gpiolib.c:gpiod_direction_output
  - drivers/gpio/gpiolib.c:gpiod_direction_output
  - drivers/gpio/gpiolib.c:gpiod_direction_output_raw
```
**Symbols:**

```
ffffffe0004a7478-ffffffe0004a7650: gpiod_direction_output_raw_commit (STB_LOCAL)
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
int gpiod_direction_output_raw_commit(struct gpio_desc *desc, int value);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/gpio/gpiolib.c (0)
Location: drivers/gpio/gpiolib.c:3009
Inline: False
Direct callers:
  - drivers/gpio/gpiolib.c:gpiod_direction_output
  - drivers/gpio/gpiolib.c:gpiod_direction_output
  - drivers/gpio/gpiolib.c:gpiod_direction_output_raw
```
**Symbols:**

```
ffffffff81562400-ffffffff815625aa: gpiod_direction_output_raw_commit (STB_LOCAL)
ffffffff81565dbd-ffffffff81565e3a: gpiod_direction_output_raw_commit.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Transformation ⚠️</summary>

```c
int gpiod_direction_output_raw_commit(struct gpio_desc *desc, int value);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/gpio/gpiolib.c (0)
Location: drivers/gpio/gpiolib.c:3009
Inline: False
Direct callers:
  - drivers/gpio/gpiolib.c:gpiod_direction_output
  - drivers/gpio/gpiolib.c:gpiod_direction_output
  - drivers/gpio/gpiolib.c:gpiod_direction_output_raw
```
**Symbols:**

```
ffffffff81553250-ffffffff815533fa: gpiod_direction_output_raw_commit (STB_LOCAL)
ffffffff81556c0d-ffffffff81556c8a: gpiod_direction_output_raw_commit.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Transformation ⚠️</summary>

```c
int gpiod_direction_output_raw_commit(struct gpio_desc *desc, int value);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/gpio/gpiolib.c (0)
Location: drivers/gpio/gpiolib.c:3009
Inline: False
Direct callers:
  - drivers/gpio/gpiolib.c:gpiod_direction_output
  - drivers/gpio/gpiolib.c:gpiod_direction_output
  - drivers/gpio/gpiolib.c:gpiod_direction_output_raw
```
**Symbols:**

```
ffffffff81560f70-ffffffff8156111a: gpiod_direction_output_raw_commit (STB_LOCAL)
ffffffff8156492d-ffffffff815649aa: gpiod_direction_output_raw_commit.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
int gpiod_direction_output_raw_commit(struct gpio_desc *desc, int value);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/gpio/gpiolib.c (0)
Location: drivers/gpio/gpiolib.c:3009
Inline: False
Direct callers:
  - drivers/gpio/gpiolib.c:gpiod_direction_output
  - drivers/gpio/gpiolib.c:gpiod_direction_output
  - drivers/gpio/gpiolib.c:gpiod_direction_output_raw
```
**Symbols:**

```
ffffffff8157ae30-ffffffff8157b00a: gpiod_direction_output_raw_commit (STB_LOCAL)
ffffffff8157e84d-ffffffff8157e8ca: gpiod_direction_output_raw_commit.cold (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
