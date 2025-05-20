# Function: <code>gpiod_set_value_nocheck</code>

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
void gpiod_set_value_nocheck(struct gpio_desc *desc, int value);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib.c (ffffffff814d9dd0)
Location: drivers/gpio/gpiolib.c:2917
Inline: False
```
**Symbols:**

```
ffffffff814d9dd0-ffffffff814d9e1b: gpiod_set_value_nocheck (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void gpiod_set_value_nocheck(struct gpio_desc *desc, int value);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib.c (ffffffff81508b90)
Location: drivers/gpio/gpiolib.c:3109
Inline: False
Direct callers:
  - drivers/gpio/gpiolib.c:gpiod_set_value_cansleep
  - drivers/gpio/gpiolib.c:gpiod_set_value
```
**Symbols:**

```
ffffffff81508b90-ffffffff81508be3: gpiod_set_value_nocheck (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void gpiod_set_value_nocheck(struct gpio_desc *desc, int value);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib.c (ffffffff8151d4a0)
Location: drivers/gpio/gpiolib.c:3274
Inline: False
Direct callers:
  - drivers/gpio/gpiolib.c:gpiod_set_value_cansleep
  - drivers/gpio/gpiolib.c:gpiod_set_value
```
**Symbols:**

```
ffffffff8151d4a0-ffffffff8151d4f3: gpiod_set_value_nocheck (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void gpiod_set_value_nocheck(struct gpio_desc *desc, int value);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib.c (ffffffff8154b540)
Location: drivers/gpio/gpiolib.c:3362
Inline: False
Direct callers:
  - drivers/gpio/gpiolib.c:gpiod_set_value_cansleep
  - drivers/gpio/gpiolib.c:gpiod_set_value
```
**Symbols:**

```
ffffffff8154b540-ffffffff8154b593: gpiod_set_value_nocheck (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void gpiod_set_value_nocheck(struct gpio_desc *desc, int value);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib.c (ffffffff8156c770)
Location: drivers/gpio/gpiolib.c:3716
Inline: False
Direct callers:
  - drivers/gpio/gpiolib.c:gpiod_set_value_cansleep
  - drivers/gpio/gpiolib.c:gpiod_set_value
```
**Symbols:**

```
ffffffff8156c770-ffffffff8156c7c3: gpiod_set_value_nocheck (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void gpiod_set_value_nocheck(struct gpio_desc *desc, int value);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib.c (ffffffff816103a0)
Location: drivers/gpio/gpiolib.c:4122
Inline: False
Direct callers:
  - drivers/gpio/gpiolib.c:gpiod_set_value_cansleep
  - drivers/gpio/gpiolib.c:gpiod_set_value
```
**Symbols:**

```
ffffffff816103a0-ffffffff816103f3: gpiod_set_value_nocheck (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void gpiod_set_value_nocheck(struct gpio_desc *desc, int value);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib.c (ffffffff81636470)
Location: drivers/gpio/gpiolib.c:2946
Inline: False
Direct callers:
  - drivers/gpio/gpiolib.c:gpiod_set_value_cansleep
  - drivers/gpio/gpiolib.c:gpiod_set_value
```
**Symbols:**

```
ffffffff81636470-ffffffff816364c3: gpiod_set_value_nocheck (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void gpiod_set_value_nocheck(struct gpio_desc *desc, int value);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib.c (ffffffff81619c70)
Location: drivers/gpio/gpiolib.c:2923
Inline: False
Direct callers:
  - drivers/gpio/gpiolib.c:gpiod_set_value_cansleep
  - drivers/gpio/gpiolib.c:gpiod_set_value
```
**Symbols:**

```
ffffffff81619c70-ffffffff81619cc3: gpiod_set_value_nocheck (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void gpiod_set_value_nocheck(struct gpio_desc *desc, int value);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib.c (ffffffff816892d0)
Location: drivers/gpio/gpiolib.c:2972
Inline: False
Direct callers:
  - drivers/gpio/gpiolib.c:gpiod_set_value_cansleep
  - drivers/gpio/gpiolib.c:gpiod_set_value
```
**Symbols:**

```
ffffffff816892d0-ffffffff81689323: gpiod_set_value_nocheck (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void gpiod_set_value_nocheck(struct gpio_desc *desc, int value);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib.c (ffffffff817a5ee0)
Location: drivers/gpio/gpiolib.c:3093
Inline: False
Direct callers:
  - drivers/gpio/gpiolib.c:gpiod_set_value_cansleep
  - drivers/gpio/gpiolib.c:gpiod_set_value
```
**Symbols:**

```
ffffffff817a5ee0-ffffffff817a5f51: gpiod_set_value_nocheck (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void gpiod_set_value_nocheck(struct gpio_desc *desc, int value);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib.c (ffffffff818bddf0)
Location: drivers/gpio/gpiolib.c:3163
Inline: False
Direct callers:
  - drivers/gpio/gpiolib.c:gpiod_set_value_cansleep
  - drivers/gpio/gpiolib.c:gpiod_set_value
```
**Symbols:**

```
ffffffff818bddf0-ffffffff818bde61: gpiod_set_value_nocheck (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void gpiod_set_value_nocheck(struct gpio_desc *desc, int value);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib.c (ffffffff81900fb0)
Location: drivers/gpio/gpiolib.c:3204
Inline: False
Direct callers:
  - drivers/gpio/gpiolib.c:gpiod_set_value_cansleep
  - drivers/gpio/gpiolib.c:gpiod_set_value
```
**Symbols:**

```
ffffffff81900fb0-ffffffff81901021: gpiod_set_value_nocheck (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void gpiod_set_value_nocheck(struct gpio_desc *desc, int value);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib.c (ffffffff819488f0)
Location: drivers/gpio/gpiolib.c:3397
Inline: False
Direct callers:
  - drivers/gpio/gpiolib.c:gpiod_set_value_cansleep
  - drivers/gpio/gpiolib.c:gpiod_set_value
```
**Symbols:**

```
ffffffff819488f0-ffffffff81948961: gpiod_set_value_nocheck (STB_LOCAL)
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
void gpiod_set_value_nocheck(struct gpio_desc *desc, int value);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib.c (ffff8000106c2368)
Location: drivers/gpio/gpiolib.c:3716
Inline: False
Direct callers:
  - drivers/gpio/gpiolib.c:gpiod_set_value_cansleep
  - drivers/gpio/gpiolib.c:gpiod_set_value
```
**Symbols:**

```
ffff8000106c2368-ffff8000106c23fc: gpiod_set_value_nocheck (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void gpiod_set_value_nocheck(struct gpio_desc *desc, int value);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib.c (c08602c4)
Location: drivers/gpio/gpiolib.c:3716
Inline: False
Direct callers:
  - drivers/gpio/gpiolib.c:gpiod_set_value_cansleep
  - drivers/gpio/gpiolib.c:gpiod_set_value
```
**Symbols:**

```
c08602c4-c0860324: gpiod_set_value_nocheck (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void gpiod_set_value_nocheck(struct gpio_desc *desc, int value);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib.c (c00000000083da80)
Location: drivers/gpio/gpiolib.c:3716
Inline: False
Direct callers:
  - drivers/gpio/gpiolib.c:gpiod_set_value_cansleep
  - drivers/gpio/gpiolib.c:gpiod_set_value
```
**Symbols:**

```
c00000000083da80-c00000000083dae4: gpiod_set_value_nocheck (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void gpiod_set_value_nocheck(struct gpio_desc *desc, int value);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib.c (ffffffe0004a7008)
Location: drivers/gpio/gpiolib.c:3716
Inline: False
Direct callers:
  - drivers/gpio/gpiolib.c:gpiod_set_value_cansleep
  - drivers/gpio/gpiolib.c:gpiod_set_value
```
**Symbols:**

```
ffffffe0004a7008-ffffffe0004a7082: gpiod_set_value_nocheck (STB_LOCAL)
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
void gpiod_set_value_nocheck(struct gpio_desc *desc, int value);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib.c (ffffffff81561f30)
Location: drivers/gpio/gpiolib.c:3716
Inline: False
Direct callers:
  - drivers/gpio/gpiolib.c:gpiod_set_value_cansleep
  - drivers/gpio/gpiolib.c:gpiod_set_value
```
**Symbols:**

```
ffffffff81561f30-ffffffff81561f83: gpiod_set_value_nocheck (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void gpiod_set_value_nocheck(struct gpio_desc *desc, int value);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib.c (ffffffff81552d80)
Location: drivers/gpio/gpiolib.c:3716
Inline: False
Direct callers:
  - drivers/gpio/gpiolib.c:gpiod_set_value_cansleep
  - drivers/gpio/gpiolib.c:gpiod_set_value
```
**Symbols:**

```
ffffffff81552d80-ffffffff81552dd3: gpiod_set_value_nocheck (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void gpiod_set_value_nocheck(struct gpio_desc *desc, int value);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib.c (ffffffff81560aa0)
Location: drivers/gpio/gpiolib.c:3716
Inline: False
Direct callers:
  - drivers/gpio/gpiolib.c:gpiod_set_value_cansleep
  - drivers/gpio/gpiolib.c:gpiod_set_value
```
**Symbols:**

```
ffffffff81560aa0-ffffffff81560af3: gpiod_set_value_nocheck (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void gpiod_set_value_nocheck(struct gpio_desc *desc, int value);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib.c (ffffffff8157a940)
Location: drivers/gpio/gpiolib.c:3716
Inline: False
Direct callers:
  - drivers/gpio/gpiolib.c:gpiod_set_value_cansleep
  - drivers/gpio/gpiolib.c:gpiod_set_value
```
**Symbols:**

```
ffffffff8157a940-ffffffff8157a993: gpiod_set_value_nocheck (STB_LOCAL)
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
