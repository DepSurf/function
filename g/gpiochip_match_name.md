# Function: <code>gpiochip_match_name</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int gpiochip_match_name(struct gpio_chip *chip, void *data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib.c (ffffffff81424710)
Location: drivers/gpio/gpiolib.c:466
Inline: False
```
**Symbols:**

```
ffffffff81424710-ffffffff8142472b: gpiochip_match_name (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int gpiochip_match_name(struct gpio_chip *chip, void *data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib.c (ffffffff8146e000)
Location: drivers/gpio/gpiolib.c:1386
Inline: False
```
**Symbols:**

```
ffffffff8146e000-ffffffff8146e01b: gpiochip_match_name (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int gpiochip_match_name(struct gpio_chip *chip, void *data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib.c (ffffffff8148fed0)
Location: drivers/gpio/gpiolib.c:1463
Inline: False
```
**Symbols:**

```
ffffffff8148fed0-ffffffff8148feeb: gpiochip_match_name (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int gpiochip_match_name(struct gpio_chip *chip, void *data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib.c (ffffffff81499680)
Location: drivers/gpio/gpiolib.c:1454
Inline: False
```
**Symbols:**

```
ffffffff81499680-ffffffff8149969b: gpiochip_match_name (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int gpiochip_match_name(struct gpio_chip *chip, void *data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib.c (ffffffff814d7980)
Location: drivers/gpio/gpiolib.c:1485
Inline: False
```
**Symbols:**

```
ffffffff814d7980-ffffffff814d799b: gpiochip_match_name (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int gpiochip_match_name(struct gpio_chip *chip, void *data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib.c (ffffffff81506d30)
Location: drivers/gpio/gpiolib.c:1593
Inline: False
```
**Symbols:**

```
ffffffff81506d30-ffffffff81506d4b: gpiochip_match_name (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int gpiochip_match_name(struct gpio_chip *chip, void *data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib.c (ffffffff8151b2d0)
Location: drivers/gpio/gpiolib.c:1593
Inline: False
```
**Symbols:**

```
ffffffff8151b2d0-ffffffff8151b2eb: gpiochip_match_name (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int gpiochip_match_name(struct gpio_chip *chip, void *data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib.c (ffffffff81549480)
Location: drivers/gpio/gpiolib.c:1612
Inline: False
```
**Symbols:**

```
ffffffff81549480-ffffffff8154949b: gpiochip_match_name (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int gpiochip_match_name(struct gpio_chip *chip, void *data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib.c (ffffffff8156a750)
Location: drivers/gpio/gpiolib.c:1621
Inline: False
```
**Symbols:**

```
ffffffff8156a750-ffffffff8156a76b: gpiochip_match_name (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib.c (ffffffff8160ed3c)
Location: drivers/gpio/gpiolib.c:1950
Inline: True
Inline callers:
  - drivers/gpio/gpiolib.c:gpiod_find
  - drivers/gpio/gpiolib.c:gpiod_add_hogs
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib.c (ffffffff8163618c)
Location: drivers/gpio/gpiolib.c:897
Inline: True
Inline callers:
  - drivers/gpio/gpiolib.c:gpiod_find
  - drivers/gpio/gpiolib.c:gpiod_add_hogs
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
In drivers/gpio/gpiolib.c (ffffffff8161b9e4)
Location: drivers/gpio/gpiolib.c:886
Inline: True
Inline callers:
  - drivers/gpio/gpiolib.c:gpiod_get_index
  - drivers/gpio/gpiolib.c:gpiod_add_hogs
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
In drivers/gpio/gpiolib.c (ffffffff8168aef4)
Location: drivers/gpio/gpiolib.c:908
Inline: True
Inline callers:
  - drivers/gpio/gpiolib.c:gpiod_get_index
  - drivers/gpio/gpiolib.c:gpiod_add_hogs
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
In drivers/gpio/gpiolib.c (ffffffff817a8237)
Location: drivers/gpio/gpiolib.c:938
Inline: True
Inline callers:
  - drivers/gpio/gpiolib.c:gpiod_get_index
  - drivers/gpio/gpiolib.c:gpiod_add_hogs
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
In drivers/gpio/gpiolib.c (ffffffff818c0a67)
Location: drivers/gpio/gpiolib.c:1011
Inline: True
Inline callers:
  - drivers/gpio/gpiolib.c:gpiod_find_and_request
  - drivers/gpio/gpiolib.c:gpiod_add_hogs
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
In drivers/gpio/gpiolib.c (ffffffff81903aaf)
Location: drivers/gpio/gpiolib.c:1042
Inline: True
Inline callers:
  - drivers/gpio/gpiolib.c:gpiod_find_and_request
  - drivers/gpio/gpiolib.c:gpiod_add_hogs
```
</details>
</li>
<li>
In <code>6.8</code>: Absent ⚠️
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: ✅</summary>

```c
int gpiochip_match_name(struct gpio_chip *chip, void *data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib.c (ffff8000106bde98)
Location: drivers/gpio/gpiolib.c:1621
Inline: False
```
**Symbols:**

```
ffff8000106bde98-ffff8000106bded4: gpiochip_match_name (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int gpiochip_match_name(struct gpio_chip *chip, void *data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib.c (c085db60)
Location: drivers/gpio/gpiolib.c:1621
Inline: False
```
**Symbols:**

```
c085db60-c085db88: gpiochip_match_name (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int gpiochip_match_name(struct gpio_chip *chip, void *data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib.c (c00000000083a570)
Location: drivers/gpio/gpiolib.c:1621
Inline: False
```
**Symbols:**

```
c00000000083a570-c00000000083a708: gpiochip_match_name (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int gpiochip_match_name(struct gpio_chip *chip, void *data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib.c (ffffffe0004a4d4c)
Location: drivers/gpio/gpiolib.c:1621
Inline: False
```
**Symbols:**

```
ffffffe0004a4d4c-ffffffe0004a4d82: gpiochip_match_name (STB_LOCAL)
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
int gpiochip_match_name(struct gpio_chip *chip, void *data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib.c (ffffffff8155ff10)
Location: drivers/gpio/gpiolib.c:1621
Inline: False
```
**Symbols:**

```
ffffffff8155ff10-ffffffff8155ff2b: gpiochip_match_name (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int gpiochip_match_name(struct gpio_chip *chip, void *data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib.c (ffffffff81550d60)
Location: drivers/gpio/gpiolib.c:1621
Inline: False
```
**Symbols:**

```
ffffffff81550d60-ffffffff81550d7b: gpiochip_match_name (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int gpiochip_match_name(struct gpio_chip *chip, void *data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib.c (ffffffff8155ea80)
Location: drivers/gpio/gpiolib.c:1621
Inline: False
```
**Symbols:**

```
ffffffff8155ea80-ffffffff8155ea9b: gpiochip_match_name (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int gpiochip_match_name(struct gpio_chip *chip, void *data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib.c (ffffffff81578910)
Location: drivers/gpio/gpiolib.c:1621
Inline: False
```
**Symbols:**

```
ffffffff81578910-ffffffff8157892b: gpiochip_match_name (STB_LOCAL)
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
