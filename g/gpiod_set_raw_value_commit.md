# Function: <code>gpiod_set_raw_value_commit</code>

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
void gpiod_set_raw_value_commit(struct gpio_desc *desc, bool value);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib.c (ffffffff814d9d20)
Location: drivers/gpio/gpiolib.c:2806
Inline: False
Direct callers:
  - drivers/gpio/gpiolib.c:gpiod_set_value_nocheck
```
**Symbols:**

```
ffffffff814d9d20-ffffffff814d9dcd: gpiod_set_raw_value_commit (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void gpiod_set_raw_value_commit(struct gpio_desc *desc, bool value);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib.c (ffffffff81508850)
Location: drivers/gpio/gpiolib.c:2982
Inline: False
Direct callers:
  - drivers/gpio/gpiolib.c:gpiod_set_raw_value_cansleep
  - drivers/gpio/gpiolib.c:gpiod_set_value_nocheck
  - drivers/gpio/gpiolib.c:gpiod_set_raw_value
```
**Symbols:**

```
ffffffff81508850-ffffffff81508900: gpiod_set_raw_value_commit (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void gpiod_set_raw_value_commit(struct gpio_desc *desc, bool value);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib.c (ffffffff8151d360)
Location: drivers/gpio/gpiolib.c:3109
Inline: False
Direct callers:
  - drivers/gpio/gpiolib.c:gpiod_set_raw_value_cansleep
  - drivers/gpio/gpiolib.c:gpiod_set_value_nocheck
  - drivers/gpio/gpiolib.c:gpiod_set_raw_value
```
**Symbols:**

```
ffffffff8151d360-ffffffff8151d410: gpiod_set_raw_value_commit (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void gpiod_set_raw_value_commit(struct gpio_desc *desc, bool value);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib.c (ffffffff8154b440)
Location: drivers/gpio/gpiolib.c:3197
Inline: False
Direct callers:
  - drivers/gpio/gpiolib.c:gpiod_set_raw_value_cansleep
  - drivers/gpio/gpiolib.c:gpiod_set_value_nocheck
  - drivers/gpio/gpiolib.c:gpiod_set_raw_value
```
**Symbols:**

```
ffffffff8154b440-ffffffff8154b4f2: gpiod_set_raw_value_commit (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void gpiod_set_raw_value_commit(struct gpio_desc *desc, bool value);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib.c (ffffffff8156c620)
Location: drivers/gpio/gpiolib.c:3551
Inline: False
Direct callers:
  - drivers/gpio/gpiolib.c:gpiod_set_raw_value_cansleep
  - drivers/gpio/gpiolib.c:gpiod_set_value_nocheck
  - drivers/gpio/gpiolib.c:gpiod_set_raw_value
```
**Symbols:**

```
ffffffff8156c620-ffffffff8156c6d2: gpiod_set_raw_value_commit (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void gpiod_set_raw_value_commit(struct gpio_desc *desc, bool value);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib.c (ffffffff8160e8c0)
Location: drivers/gpio/gpiolib.c:3959
Inline: False
Direct callers:
  - drivers/gpio/gpiolib.c:gpiod_set_raw_value_cansleep
  - drivers/gpio/gpiolib.c:gpiod_set_value_nocheck
  - drivers/gpio/gpiolib.c:gpiod_set_raw_value
```
**Symbols:**

```
ffffffff8160e8c0-ffffffff8160e96e: gpiod_set_raw_value_commit (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void gpiod_set_raw_value_commit(struct gpio_desc *desc, bool value);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib.c (ffffffff81635830)
Location: drivers/gpio/gpiolib.c:2784
Inline: False
Direct callers:
  - drivers/gpio/gpiolib.c:gpiod_set_raw_value_cansleep
  - drivers/gpio/gpiolib.c:gpiod_set_value_nocheck
  - drivers/gpio/gpiolib.c:gpiod_set_raw_value
```
**Symbols:**

```
ffffffff81635830-ffffffff816358dc: gpiod_set_raw_value_commit (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void gpiod_set_raw_value_commit(struct gpio_desc *desc, bool value);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib.c (ffffffff81619b90)
Location: drivers/gpio/gpiolib.c:2761
Inline: False
Direct callers:
  - drivers/gpio/gpiolib.c:gpiod_set_raw_value_cansleep
  - drivers/gpio/gpiolib.c:gpiod_set_value_nocheck
  - drivers/gpio/gpiolib.c:gpiod_set_raw_value
```
**Symbols:**

```
ffffffff81619b90-ffffffff81619c61: gpiod_set_raw_value_commit (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void gpiod_set_raw_value_commit(struct gpio_desc *desc, bool value);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib.c (ffffffff81689200)
Location: drivers/gpio/gpiolib.c:2801
Inline: False
Direct callers:
  - drivers/gpio/gpiolib.c:gpiod_set_raw_value_cansleep
  - drivers/gpio/gpiolib.c:gpiod_set_value_nocheck
  - drivers/gpio/gpiolib.c:gpiod_set_raw_value
```
**Symbols:**

```
ffffffff81689200-ffffffff816892ce: gpiod_set_raw_value_commit (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void gpiod_set_raw_value_commit(struct gpio_desc *desc, bool value);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib.c (ffffffff817a5de0)
Location: drivers/gpio/gpiolib.c:2922
Inline: False
Direct callers:
  - drivers/gpio/gpiolib.c:gpiod_set_value_nocheck
  - drivers/gpio/gpiolib.c:gpiod_set_raw_value
```
**Symbols:**

```
ffffffff817a5de0-ffffffff817a5ed5: gpiod_set_raw_value_commit (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void gpiod_set_raw_value_commit(struct gpio_desc *desc, bool value);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib.c (ffffffff818bdce0)
Location: drivers/gpio/gpiolib.c:2992
Inline: False
Direct callers:
  - drivers/gpio/gpiolib.c:gpiod_set_value_nocheck
  - drivers/gpio/gpiolib.c:gpiod_set_raw_value
```
**Symbols:**

```
ffffffff818bdce0-ffffffff818bddd5: gpiod_set_raw_value_commit (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void gpiod_set_raw_value_commit(struct gpio_desc *desc, bool value);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib.c (ffffffff81900ea0)
Location: drivers/gpio/gpiolib.c:3033
Inline: False
Direct callers:
  - drivers/gpio/gpiolib.c:gpiod_set_value_nocheck
  - drivers/gpio/gpiolib.c:gpiod_set_raw_value
```
**Symbols:**

```
ffffffff81900ea0-ffffffff81900f95: gpiod_set_raw_value_commit (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void gpiod_set_raw_value_commit(struct gpio_desc *desc, bool value);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib.c (ffffffff81948810)
Location: drivers/gpio/gpiolib.c:3226
Inline: False
Direct callers:
  - drivers/gpio/gpiolib.c:gpiod_set_value_nocheck
  - drivers/gpio/gpiolib.c:gpiod_set_raw_value
```
**Symbols:**

```
ffffffff81948810-ffffffff819488da: gpiod_set_raw_value_commit (STB_LOCAL)
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
void gpiod_set_raw_value_commit(struct gpio_desc *desc, bool value);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib.c (ffff8000106bf9d0)
Location: drivers/gpio/gpiolib.c:3551
Inline: False
Direct callers:
  - drivers/gpio/gpiolib.c:gpiod_set_raw_value_cansleep
  - drivers/gpio/gpiolib.c:gpiod_set_value_nocheck
  - drivers/gpio/gpiolib.c:gpiod_set_raw_value
```
**Symbols:**

```
ffff8000106bf9d0-ffff8000106bfad0: gpiod_set_raw_value_commit (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void gpiod_set_raw_value_commit(struct gpio_desc *desc, bool value);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib.c (c0860128)
Location: drivers/gpio/gpiolib.c:3551
Inline: False
Direct callers:
  - drivers/gpio/gpiolib.c:gpiod_set_raw_value_cansleep
  - drivers/gpio/gpiolib.c:gpiod_set_value_nocheck
  - drivers/gpio/gpiolib.c:gpiod_set_raw_value
```
**Symbols:**

```
c0860128-c086020c: gpiod_set_raw_value_commit (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void gpiod_set_raw_value_commit(struct gpio_desc *desc, bool value);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib.c (c00000000083d7f0)
Location: drivers/gpio/gpiolib.c:3551
Inline: False
Direct callers:
  - drivers/gpio/gpiolib.c:gpiod_set_raw_value_cansleep
  - drivers/gpio/gpiolib.c:gpiod_set_value_nocheck
  - drivers/gpio/gpiolib.c:gpiod_set_raw_value
```
**Symbols:**

```
c00000000083d7f0-c00000000083d94c: gpiod_set_raw_value_commit (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void gpiod_set_raw_value_commit(struct gpio_desc *desc, bool value);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib.c (ffffffe0004a6ea2)
Location: drivers/gpio/gpiolib.c:3551
Inline: False
Direct callers:
  - drivers/gpio/gpiolib.c:gpiod_set_raw_value_cansleep
  - drivers/gpio/gpiolib.c:gpiod_set_value_nocheck
  - drivers/gpio/gpiolib.c:gpiod_set_raw_value
```
**Symbols:**

```
ffffffe0004a6ea2-ffffffe0004a6f64: gpiod_set_raw_value_commit (STB_LOCAL)
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
void gpiod_set_raw_value_commit(struct gpio_desc *desc, bool value);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib.c (ffffffff81561de0)
Location: drivers/gpio/gpiolib.c:3551
Inline: False
Direct callers:
  - drivers/gpio/gpiolib.c:gpiod_set_raw_value_cansleep
  - drivers/gpio/gpiolib.c:gpiod_set_value_nocheck
  - drivers/gpio/gpiolib.c:gpiod_set_raw_value
```
**Symbols:**

```
ffffffff81561de0-ffffffff81561e92: gpiod_set_raw_value_commit (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void gpiod_set_raw_value_commit(struct gpio_desc *desc, bool value);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib.c (ffffffff81552c30)
Location: drivers/gpio/gpiolib.c:3551
Inline: False
Direct callers:
  - drivers/gpio/gpiolib.c:gpiod_set_raw_value_cansleep
  - drivers/gpio/gpiolib.c:gpiod_set_value_nocheck
  - drivers/gpio/gpiolib.c:gpiod_set_raw_value
```
**Symbols:**

```
ffffffff81552c30-ffffffff81552ce2: gpiod_set_raw_value_commit (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void gpiod_set_raw_value_commit(struct gpio_desc *desc, bool value);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib.c (ffffffff81560950)
Location: drivers/gpio/gpiolib.c:3551
Inline: False
Direct callers:
  - drivers/gpio/gpiolib.c:gpiod_set_raw_value_cansleep
  - drivers/gpio/gpiolib.c:gpiod_set_value_nocheck
  - drivers/gpio/gpiolib.c:gpiod_set_raw_value
```
**Symbols:**

```
ffffffff81560950-ffffffff81560a02: gpiod_set_raw_value_commit (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void gpiod_set_raw_value_commit(struct gpio_desc *desc, bool value);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib.c (ffffffff8157a7e0)
Location: drivers/gpio/gpiolib.c:3551
Inline: False
Direct callers:
  - drivers/gpio/gpiolib.c:gpiod_set_raw_value_cansleep
  - drivers/gpio/gpiolib.c:gpiod_set_value_nocheck
  - drivers/gpio/gpiolib.c:gpiod_set_raw_value
```
**Symbols:**

```
ffffffff8157a7e0-ffffffff8157a8ac: gpiod_set_raw_value_commit (STB_LOCAL)
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
