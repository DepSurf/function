# Function: <code>gpiod_find</code>

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
In drivers/gpio/gpiolib.c (ffffffff81426e26)
Location: drivers/gpio/gpiolib.c:1919
Inline: True
Inline callers:
  - drivers/gpio/gpiolib.c:gpiod_get_index
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
In drivers/gpio/gpiolib.c (ffffffff81471cb1)
Location: drivers/gpio/gpiolib.c:2935
Inline: True
Inline callers:
  - drivers/gpio/gpiolib.c:gpiod_get_index
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
In drivers/gpio/gpiolib.c (ffffffff81493e9e)
Location: drivers/gpio/gpiolib.c:3056
Inline: True
Inline callers:
  - drivers/gpio/gpiolib.c:gpiod_get_index
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
In drivers/gpio/gpiolib.c (ffffffff8149dd14)
Location: drivers/gpio/gpiolib.c:3065
Inline: True
Inline callers:
  - drivers/gpio/gpiolib.c:gpiod_get_index
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
In drivers/gpio/gpiolib.c (ffffffff814dc8e2)
Location: drivers/gpio/gpiolib.c:3398
Inline: True
Inline callers:
  - drivers/gpio/gpiolib.c:gpiod_get_index
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib.c (ffffffff8150ac87)
Location: drivers/gpio/gpiolib.c:3616
Inline: True
Inline callers:
  - drivers/gpio/gpiolib.c:gpiod_get_index
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib.c (ffffffff8151f7f6)
Location: drivers/gpio/gpiolib.c:3869
Inline: True
Inline callers:
  - drivers/gpio/gpiolib.c:gpiod_get_index
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib.c (ffffffff8154d997)
Location: drivers/gpio/gpiolib.c:3958
Inline: True
Inline callers:
  - drivers/gpio/gpiolib.c:gpiod_get_index
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib.c (ffffffff8156eb97)
Location: drivers/gpio/gpiolib.c:4312
Inline: True
Inline callers:
  - drivers/gpio/gpiolib.c:gpiod_get_index
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
struct gpio_desc *gpiod_find(struct device *dev, const char *con_id, unsigned int idx, long unsigned int *flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/gpio/gpiolib.c (0)
Location: drivers/gpio/gpiolib.c:4725
Inline: False
Direct callers:
  - drivers/gpio/gpiolib.c:gpiod_get_index
```
**Symbols:**

```
ffffffff8160ec90-ffffffff8160ee28: gpiod_find (STB_LOCAL)
ffffffff81614415-ffffffff81614460: gpiod_find.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
struct gpio_desc *gpiod_find(struct device *dev, const char *con_id, unsigned int idx, long unsigned int *flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/gpio/gpiolib.c (0)
Location: drivers/gpio/gpiolib.c:3549
Inline: False
Direct callers:
  - drivers/gpio/gpiolib.c:gpiod_get_index
```
**Symbols:**

```
ffffffff816360e0-ffffffff81636272: gpiod_find (STB_LOCAL)
ffffffff81bf5e05-ffffffff81bf5e4d: gpiod_find.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib.c (ffffffff8161b953)
Location: drivers/gpio/gpiolib.c:3530
Inline: True
Inline callers:
  - drivers/gpio/gpiolib.c:gpiod_get_index
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib.c (ffffffff8168ae63)
Location: drivers/gpio/gpiolib.c:3589
Inline: True
Inline callers:
  - drivers/gpio/gpiolib.c:gpiod_get_index
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib.c (ffffffff817a81a4)
Location: drivers/gpio/gpiolib.c:3717
Inline: True
Inline callers:
  - drivers/gpio/gpiolib.c:gpiod_get_index
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib.c (ffffffff818c09d4)
Location: drivers/gpio/gpiolib.c:3787
Inline: True
Inline callers:
  - drivers/gpio/gpiolib.c:gpiod_find_and_request
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib.c (ffffffff81903a14)
Location: drivers/gpio/gpiolib.c:3828
Inline: True
Inline callers:
  - drivers/gpio/gpiolib.c:gpiod_find_and_request
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
struct gpio_desc *gpiod_find(struct device *dev, const char *con_id, unsigned int idx, long unsigned int *flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib.c (ffffffff81949090)
Location: drivers/gpio/gpiolib.c:4022
Inline: False
Direct callers:
  - drivers/gpio/gpiolib.c:gpiod_find_and_request
```
**Symbols:**

```
ffffffff81949090-ffffffff819492ec: gpiod_find (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib.c (ffff8000106c4988)
Location: drivers/gpio/gpiolib.c:4312
Inline: True
Inline callers:
  - drivers/gpio/gpiolib.c:gpiod_get_index
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib.c (c0862cc4)
Location: drivers/gpio/gpiolib.c:4312
Inline: True
Inline callers:
  - drivers/gpio/gpiolib.c:gpiod_get_index
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
In drivers/gpio/gpiolib.c (c0000000008412e4)
Location: drivers/gpio/gpiolib.c:4312
Inline: True
Inline callers:
  - drivers/gpio/gpiolib.c:gpiod_get_index
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib.c (ffffffe0004a9150)
Location: drivers/gpio/gpiolib.c:4312
Inline: True
Inline callers:
  - drivers/gpio/gpiolib.c:gpiod_get_index
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib.c (ffffffff81564357)
Location: drivers/gpio/gpiolib.c:4312
Inline: True
Inline callers:
  - drivers/gpio/gpiolib.c:gpiod_get_index
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib.c (ffffffff815551a7)
Location: drivers/gpio/gpiolib.c:4312
Inline: True
Inline callers:
  - drivers/gpio/gpiolib.c:gpiod_get_index
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib.c (ffffffff81562ec7)
Location: drivers/gpio/gpiolib.c:4312
Inline: True
Inline callers:
  - drivers/gpio/gpiolib.c:gpiod_get_index
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib.c (ffffffff8157cde7)
Location: drivers/gpio/gpiolib.c:4312
Inline: True
Inline callers:
  - drivers/gpio/gpiolib.c:gpiod_get_index
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>5.8</code> and <code>5.11</code> ✅
</li>
</ul>
