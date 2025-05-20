# Function: <code>gpio_set_open_source_value_commit</code>

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
void gpio_set_open_source_value_commit(struct gpio_desc *desc, bool value);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib.c (ffffffff814d9bd0)
Location: drivers/gpio/gpiolib.c:2784
Inline: False
Direct callers:
  - drivers/gpio/gpiolib.c:gpiod_set_value_nocheck
  - drivers/gpio/gpiolib.c:gpiod_set_array_value_complex
```
**Symbols:**

```
ffffffff814d9bd0-ffffffff814d9d1a: gpio_set_open_source_value_commit (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Transformation ⚠️</summary>

```c
void gpio_set_open_source_value_commit(struct gpio_desc *desc, bool value);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/gpio/gpiolib.c (0)
Location: drivers/gpio/gpiolib.c:2960
Inline: False
Direct callers:
  - drivers/gpio/gpiolib.c:gpiod_set_value_nocheck
  - drivers/gpio/gpiolib.c:gpiod_set_array_value_complex
```
**Symbols:**

```
ffffffff81508a90-ffffffff81508b8d: gpio_set_open_source_value_commit (STB_LOCAL)
ffffffff8150be33-ffffffff8150be79: gpio_set_open_source_value_commit.cold.48 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Transformation ⚠️</summary>

```c
void gpio_set_open_source_value_commit(struct gpio_desc *desc, bool value);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/gpio/gpiolib.c (0)
Location: drivers/gpio/gpiolib.c:3087
Inline: False
Direct callers:
  - drivers/gpio/gpiolib.c:gpiod_set_value_nocheck
  - drivers/gpio/gpiolib.c:gpiod_set_array_value_complex
```
**Symbols:**

```
ffffffff8151d260-ffffffff8151d35d: gpio_set_open_source_value_commit (STB_LOCAL)
ffffffff81520d09-ffffffff81520d4f: gpio_set_open_source_value_commit.cold.46 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
void gpio_set_open_source_value_commit(struct gpio_desc *desc, bool value);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/gpio/gpiolib.c (0)
Location: drivers/gpio/gpiolib.c:3175
Inline: False
Direct callers:
  - drivers/gpio/gpiolib.c:gpiod_set_value_nocheck
  - drivers/gpio/gpiolib.c:gpiod_set_array_value_complex
```
**Symbols:**

```
ffffffff8154b350-ffffffff8154b43b: gpio_set_open_source_value_commit (STB_LOCAL)
ffffffff8154f011-ffffffff8154f055: gpio_set_open_source_value_commit.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
void gpio_set_open_source_value_commit(struct gpio_desc *desc, bool value);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/gpio/gpiolib.c (0)
Location: drivers/gpio/gpiolib.c:3531
Inline: False
Direct callers:
  - drivers/gpio/gpiolib.c:gpiod_set_value_nocheck
  - drivers/gpio/gpiolib.c:gpiod_set_array_value_complex
```
**Symbols:**

```
ffffffff8156c530-ffffffff8156c612: gpio_set_open_source_value_commit (STB_LOCAL)
ffffffff815705b9-ffffffff815705fd: gpio_set_open_source_value_commit.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
void gpio_set_open_source_value_commit(struct gpio_desc *desc, bool value);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/gpio/gpiolib.c (0)
Location: drivers/gpio/gpiolib.c:3939
Inline: False
Direct callers:
  - drivers/gpio/gpiolib.c:gpiod_set_value_nocheck
  - drivers/gpio/gpiolib.c:gpiod_set_array_value_complex
```
**Symbols:**

```
ffffffff816102b0-ffffffff8161039a: gpio_set_open_source_value_commit (STB_LOCAL)
ffffffff81614682-ffffffff816146c6: gpio_set_open_source_value_commit.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
void gpio_set_open_source_value_commit(struct gpio_desc *desc, bool value);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/gpio/gpiolib.c (0)
Location: drivers/gpio/gpiolib.c:2764
Inline: False
Direct callers:
  - drivers/gpio/gpiolib.c:gpiod_set_value_nocheck
  - drivers/gpio/gpiolib.c:gpiod_set_array_value_complex
```
**Symbols:**

```
ffffffff81636390-ffffffff81636468: gpio_set_open_source_value_commit (STB_LOCAL)
ffffffff81bf5e97-ffffffff81bf5ee1: gpio_set_open_source_value_commit.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
void gpio_set_open_source_value_commit(struct gpio_desc *desc, bool value);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/gpio/gpiolib.c (0)
Location: drivers/gpio/gpiolib.c:2741
Inline: False
Direct callers:
  - drivers/gpio/gpiolib.c:gpiod_set_value_nocheck
  - drivers/gpio/gpiolib.c:gpiod_set_array_value_complex
```
**Symbols:**

```
ffffffff81619ac0-ffffffff81619b90: gpio_set_open_source_value_commit (STB_LOCAL)
ffffffff81be7cba-ffffffff81be7d04: gpio_set_open_source_value_commit.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
void gpio_set_open_source_value_commit(struct gpio_desc *desc, bool value);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/gpio/gpiolib.c (0)
Location: drivers/gpio/gpiolib.c:2781
Inline: False
Direct callers:
  - drivers/gpio/gpiolib.c:gpiod_set_value_nocheck
  - drivers/gpio/gpiolib.c:gpiod_set_array_value_complex
```
**Symbols:**

```
ffffffff81688ee0-ffffffff81688faa: gpio_set_open_source_value_commit (STB_LOCAL)
ffffffff81ce1844-ffffffff81ce188e: gpio_set_open_source_value_commit.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
void gpio_set_open_source_value_commit(struct gpio_desc *desc, bool value);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/gpio/gpiolib.c (0)
Location: drivers/gpio/gpiolib.c:2902
Inline: False
Direct callers:
  - drivers/gpio/gpiolib.c:gpiod_set_value_nocheck
  - drivers/gpio/gpiolib.c:gpiod_set_array_value_complex
```
**Symbols:**

```
ffffffff817a5ce0-ffffffff817a5dde: gpio_set_open_source_value_commit (STB_LOCAL)
ffffffff81ea80c1-ffffffff81ea810b: gpio_set_open_source_value_commit.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void gpio_set_open_source_value_commit(struct gpio_desc *desc, bool value);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib.c (ffffffff818bdb10)
Location: drivers/gpio/gpiolib.c:2972
Inline: False
Direct callers:
  - drivers/gpio/gpiolib.c:gpiod_set_value_nocheck
  - drivers/gpio/gpiolib.c:gpiod_set_array_value_complex
```
**Symbols:**

```
ffffffff818bdb10-ffffffff818bdc5b: gpio_set_open_source_value_commit (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void gpio_set_open_source_value_commit(struct gpio_desc *desc, bool value);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib.c (ffffffff81900d40)
Location: drivers/gpio/gpiolib.c:3013
Inline: False
Direct callers:
  - drivers/gpio/gpiolib.c:gpiod_set_value_nocheck
  - drivers/gpio/gpiolib.c:gpiod_set_array_value_complex
```
**Symbols:**

```
ffffffff81900d40-ffffffff81900e8b: gpio_set_open_source_value_commit (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void gpio_set_open_source_value_commit(struct gpio_desc *desc, bool value);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib.c (ffffffff81948550)
Location: drivers/gpio/gpiolib.c:3206
Inline: False
Direct callers:
  - drivers/gpio/gpiolib.c:gpiod_set_value_nocheck
  - drivers/gpio/gpiolib.c:gpiod_set_array_value_complex
```
**Symbols:**

```
ffffffff81948550-ffffffff81948684: gpio_set_open_source_value_commit (STB_LOCAL)
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
void gpio_set_open_source_value_commit(struct gpio_desc *desc, bool value);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib.c (ffff8000106c21f0)
Location: drivers/gpio/gpiolib.c:3531
Inline: False
Direct callers:
  - drivers/gpio/gpiolib.c:gpiod_set_value_nocheck
  - drivers/gpio/gpiolib.c:gpiod_set_array_value_complex
```
**Symbols:**

```
ffff8000106c21f0-ffff8000106c2364: gpio_set_open_source_value_commit (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void gpio_set_open_source_value_commit(struct gpio_desc *desc, bool value);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib.c (c085ffcc)
Location: drivers/gpio/gpiolib.c:3531
Inline: False
Direct callers:
  - drivers/gpio/gpiolib.c:gpiod_set_value_nocheck
  - drivers/gpio/gpiolib.c:gpiod_set_array_value_complex
```
**Symbols:**

```
c085ffcc-c0860128: gpio_set_open_source_value_commit (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void gpio_set_open_source_value_commit(struct gpio_desc *desc, bool value);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib.c (c00000000083d630)
Location: drivers/gpio/gpiolib.c:3531
Inline: False
Direct callers:
  - drivers/gpio/gpiolib.c:gpiod_set_value_nocheck
  - drivers/gpio/gpiolib.c:gpiod_set_array_value_complex
```
**Symbols:**

```
c00000000083d630-c00000000083d7ec: gpio_set_open_source_value_commit (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void gpio_set_open_source_value_commit(struct gpio_desc *desc, bool value);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib.c (ffffffe0004a6d7e)
Location: drivers/gpio/gpiolib.c:3531
Inline: False
Direct callers:
  - drivers/gpio/gpiolib.c:gpiod_set_value_nocheck
  - drivers/gpio/gpiolib.c:gpiod_set_array_value_complex
```
**Symbols:**

```
ffffffe0004a6d7e-ffffffe0004a6ea2: gpio_set_open_source_value_commit (STB_LOCAL)
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
void gpio_set_open_source_value_commit(struct gpio_desc *desc, bool value);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/gpio/gpiolib.c (0)
Location: drivers/gpio/gpiolib.c:3531
Inline: False
Direct callers:
  - drivers/gpio/gpiolib.c:gpiod_set_value_nocheck
  - drivers/gpio/gpiolib.c:gpiod_set_array_value_complex
```
**Symbols:**

```
ffffffff81561cf0-ffffffff81561dd2: gpio_set_open_source_value_commit (STB_LOCAL)
ffffffff81565d79-ffffffff81565dbd: gpio_set_open_source_value_commit.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Transformation ⚠️</summary>

```c
void gpio_set_open_source_value_commit(struct gpio_desc *desc, bool value);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/gpio/gpiolib.c (0)
Location: drivers/gpio/gpiolib.c:3531
Inline: False
Direct callers:
  - drivers/gpio/gpiolib.c:gpiod_set_value_nocheck
  - drivers/gpio/gpiolib.c:gpiod_set_array_value_complex
```
**Symbols:**

```
ffffffff81552b40-ffffffff81552c22: gpio_set_open_source_value_commit (STB_LOCAL)
ffffffff81556bc9-ffffffff81556c0d: gpio_set_open_source_value_commit.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Transformation ⚠️</summary>

```c
void gpio_set_open_source_value_commit(struct gpio_desc *desc, bool value);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/gpio/gpiolib.c (0)
Location: drivers/gpio/gpiolib.c:3531
Inline: False
Direct callers:
  - drivers/gpio/gpiolib.c:gpiod_set_value_nocheck
  - drivers/gpio/gpiolib.c:gpiod_set_array_value_complex
```
**Symbols:**

```
ffffffff81560860-ffffffff81560942: gpio_set_open_source_value_commit (STB_LOCAL)
ffffffff815648e9-ffffffff8156492d: gpio_set_open_source_value_commit.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
void gpio_set_open_source_value_commit(struct gpio_desc *desc, bool value);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/gpio/gpiolib.c (0)
Location: drivers/gpio/gpiolib.c:3531
Inline: False
Direct callers:
  - drivers/gpio/gpiolib.c:gpiod_set_value_nocheck
  - drivers/gpio/gpiolib.c:gpiod_set_array_value_complex
```
**Symbols:**

```
ffffffff8157a6e0-ffffffff8157a7db: gpio_set_open_source_value_commit (STB_LOCAL)
ffffffff8157e809-ffffffff8157e84d: gpio_set_open_source_value_commit.cold (STB_LOCAL)
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
