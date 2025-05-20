# Function: <code>gpiochip_machine_hog</code>

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
In <code>4.15</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/gpio/gpiolib.c (0)
Location: drivers/gpio/gpiolib.c:1182
Inline: True
Direct callers:
  - drivers/gpio/gpiolib.c:gpiod_add_hogs
  - drivers/gpio/gpiolib.c:gpiochip_add_data_with_key
```
**Symbols:**

```
ffffffff8150b1d0-ffffffff8150b24d: gpiochip_machine_hog.isra.42 (STB_LOCAL)
ffffffff8150bfc3-ffffffff8150bfee: gpiochip_machine_hog.isra.42.cold.53 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/gpio/gpiolib.c (0)
Location: drivers/gpio/gpiolib.c:1205
Inline: True
Direct callers:
  - drivers/gpio/gpiolib.c:gpiod_add_hogs
  - drivers/gpio/gpiolib.c:gpiochip_add_data_with_key
```
**Symbols:**

```
ffffffff81520020-ffffffff8152009d: gpiochip_machine_hog.isra.40 (STB_LOCAL)
ffffffff81520ef3-ffffffff81520f1e: gpiochip_machine_hog.isra.40.cold.51 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/gpio/gpiolib.c (0)
Location: drivers/gpio/gpiolib.c:1215
Inline: True
Direct callers:
  - drivers/gpio/gpiolib.c:gpiod_add_hogs
  - drivers/gpio/gpiolib.c:gpiochip_add_data_with_key
```
**Symbols:**

```
ffffffff8154e160-ffffffff8154e1de: gpiochip_machine_hog.isra.0 (STB_LOCAL)
ffffffff8154f338-ffffffff8154f363: gpiochip_machine_hog.isra.0.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/gpio/gpiolib.c (0)
Location: drivers/gpio/gpiolib.c:1219
Inline: True
Direct callers:
  - drivers/gpio/gpiolib.c:gpiod_add_hogs
  - drivers/gpio/gpiolib.c:gpiochip_add_data_with_key
```
**Symbols:**

```
ffffffff8156f360-ffffffff8156f3de: gpiochip_machine_hog.isra.0 (STB_LOCAL)
ffffffff81570840-ffffffff8157086b: gpiochip_machine_hog.isra.0.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
void gpiochip_machine_hog(struct gpio_chip *gc, struct gpiod_hog *hog);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/gpio/gpiolib.c (0)
Location: drivers/gpio/gpiolib.c:1595
Inline: False
Direct callers:
  - drivers/gpio/gpiolib.c:gpiod_add_hogs
  - drivers/gpio/gpiolib.c:gpiochip_add_data_with_key
```
**Symbols:**

```
ffffffff816139a0-ffffffff81613a3b: gpiochip_machine_hog (STB_LOCAL)
ffffffff81614def-ffffffff81614e44: gpiochip_machine_hog.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
void gpiochip_machine_hog(struct gpio_chip *gc, struct gpiod_hog *hog);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/gpio/gpiolib.c (0)
Location: drivers/gpio/gpiolib.c:524
Inline: False
Direct callers:
  - drivers/gpio/gpiolib.c:gpiod_add_hogs
  - drivers/gpio/gpiolib.c:gpiochip_add_data_with_key
```
**Symbols:**

```
ffffffff81638890-ffffffff8163892f: gpiochip_machine_hog (STB_LOCAL)
ffffffff81bf6687-ffffffff81bf66e2: gpiochip_machine_hog.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
void gpiochip_machine_hog(struct gpio_chip *gc, struct gpiod_hog *hog);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/gpio/gpiolib.c (0)
Location: drivers/gpio/gpiolib.c:522
Inline: False
Direct callers:
  - drivers/gpio/gpiolib.c:gpiod_add_hogs
  - drivers/gpio/gpiolib.c:gpiochip_add_data_with_key
```
**Symbols:**

```
ffffffff8161c3b0-ffffffff8161c44f: gpiochip_machine_hog (STB_LOCAL)
ffffffff81be8574-ffffffff81be85cf: gpiochip_machine_hog.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
void gpiochip_machine_hog(struct gpio_chip *gc, struct gpiod_hog *hog);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/gpio/gpiolib.c (0)
Location: drivers/gpio/gpiolib.c:544
Inline: False
Direct callers:
  - drivers/gpio/gpiolib.c:gpiod_add_hogs
  - drivers/gpio/gpiolib.c:gpiochip_add_data_with_key
```
**Symbols:**

```
ffffffff8168b8d0-ffffffff8168b96f: gpiochip_machine_hog (STB_LOCAL)
ffffffff81ce2221-ffffffff81ce227c: gpiochip_machine_hog.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
void gpiochip_machine_hog(struct gpio_chip *gc, struct gpiod_hog *hog);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/gpio/gpiolib.c (0)
Location: drivers/gpio/gpiolib.c:545
Inline: False
Direct callers:
  - drivers/gpio/gpiolib.c:gpiod_add_hogs
  - drivers/gpio/gpiolib.c:gpiochip_add_data_with_key
```
**Symbols:**

```
ffffffff817a8ca0-ffffffff817a8d6b: gpiochip_machine_hog (STB_LOCAL)
ffffffff81ea8c3d-ffffffff81ea8c98: gpiochip_machine_hog.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void gpiochip_machine_hog(struct gpio_chip *gc, struct gpiod_hog *hog);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib.c (ffffffff818c1530)
Location: drivers/gpio/gpiolib.c:602
Inline: False
Direct callers:
  - drivers/gpio/gpiolib.c:gpiod_add_hogs
  - drivers/gpio/gpiolib.c:gpiochip_add_data_with_key
```
**Symbols:**

```
ffffffff818c1530-ffffffff818c1661: gpiochip_machine_hog (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void gpiochip_machine_hog(struct gpio_chip *gc, struct gpiod_hog *hog);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib.c (ffffffff819044b0)
Location: drivers/gpio/gpiolib.c:637
Inline: False
Direct callers:
  - drivers/gpio/gpiolib.c:gpiod_add_hogs
  - drivers/gpio/gpiolib.c:gpiochip_add_data_with_key
```
**Symbols:**

```
ffffffff819044b0-ffffffff819045e1: gpiochip_machine_hog (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void gpiochip_machine_hog(struct gpio_chip *gc, struct gpiod_hog *hog);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib.c (ffffffff8194bee0)
Location: drivers/gpio/gpiolib.c:711
Inline: False
Direct callers:
  - drivers/gpio/gpiolib.c:gpiod_add_hogs
  - drivers/gpio/gpiolib.c:gpiochip_add_data_with_key
```
**Symbols:**

```
ffffffff8194bee0-ffffffff8194c01f: gpiochip_machine_hog (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/gpio/gpiolib.c (ffff8000106c54e0)
Location: drivers/gpio/gpiolib.c:1219
Inline: True
Direct callers:
  - drivers/gpio/gpiolib.c:gpiod_add_hogs
  - drivers/gpio/gpiolib.c:gpiochip_add_data_with_key
```
**Symbols:**

```
ffff8000106c54e0-ffff8000106c55a0: gpiochip_machine_hog.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void gpiochip_machine_hog(struct gpio_chip *chip, struct gpiod_hog *hog);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib.c (c08635ec)
Location: drivers/gpio/gpiolib.c:1219
Inline: False
Direct callers:
  - drivers/gpio/gpiolib.c:gpiod_add_hogs
  - drivers/gpio/gpiolib.c:gpiochip_add_data_with_key
```
**Symbols:**

```
c08635ec-c086369c: gpiochip_machine_hog (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void gpiochip_machine_hog(struct gpio_chip *chip, struct gpiod_hog *hog);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib.c (c000000000842090)
Location: drivers/gpio/gpiolib.c:1219
Inline: False
Direct callers:
  - drivers/gpio/gpiolib.c:gpiod_add_hogs
  - drivers/gpio/gpiolib.c:gpiochip_add_data_with_key
```
**Symbols:**

```
c000000000842090-c0000000008421ac: gpiochip_machine_hog (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void gpiochip_machine_hog(struct gpio_chip *chip, struct gpiod_hog *hog);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib.c (ffffffe0004a9960)
Location: drivers/gpio/gpiolib.c:1219
Inline: False
Direct callers:
  - drivers/gpio/gpiolib.c:gpiod_add_hogs
  - drivers/gpio/gpiolib.c:gpiochip_add_data_with_key
```
**Symbols:**

```
ffffffe0004a9960-ffffffe0004a9a02: gpiochip_machine_hog (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/gpio/gpiolib.c (0)
Location: drivers/gpio/gpiolib.c:1219
Inline: True
Direct callers:
  - drivers/gpio/gpiolib.c:gpiod_add_hogs
  - drivers/gpio/gpiolib.c:gpiochip_add_data_with_key
```
**Symbols:**

```
ffffffff81564b20-ffffffff81564b9e: gpiochip_machine_hog.isra.0 (STB_LOCAL)
ffffffff81566000-ffffffff8156602b: gpiochip_machine_hog.isra.0.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/gpio/gpiolib.c (0)
Location: drivers/gpio/gpiolib.c:1219
Inline: True
Direct callers:
  - drivers/gpio/gpiolib.c:gpiod_add_hogs
  - drivers/gpio/gpiolib.c:gpiochip_add_data_with_key
```
**Symbols:**

```
ffffffff81555970-ffffffff815559ee: gpiochip_machine_hog.isra.0 (STB_LOCAL)
ffffffff81556e50-ffffffff81556e7b: gpiochip_machine_hog.isra.0.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/gpio/gpiolib.c (0)
Location: drivers/gpio/gpiolib.c:1219
Inline: True
Direct callers:
  - drivers/gpio/gpiolib.c:gpiod_add_hogs
  - drivers/gpio/gpiolib.c:gpiochip_add_data_with_key
```
**Symbols:**

```
ffffffff81563690-ffffffff8156370e: gpiochip_machine_hog.isra.0 (STB_LOCAL)
ffffffff81564b70-ffffffff81564b9b: gpiochip_machine_hog.isra.0.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/gpio/gpiolib.c (0)
Location: drivers/gpio/gpiolib.c:1219
Inline: True
Direct callers:
  - drivers/gpio/gpiolib.c:gpiod_add_hogs
  - drivers/gpio/gpiolib.c:gpiochip_add_data_with_key
```
**Symbols:**

```
ffffffff8157d5b0-ffffffff8157d62e: gpiochip_machine_hog.isra.0 (STB_LOCAL)
ffffffff8157ea90-ffffffff8157eabb: gpiochip_machine_hog.isra.0.cold (STB_LOCAL)
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
</ul>
