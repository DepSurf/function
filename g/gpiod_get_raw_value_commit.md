# Function: <code>gpiod_get_raw_value_commit</code>

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
int gpiod_get_raw_value_commit(const struct gpio_desc *desc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib.c (ffffffff814da040)
Location: drivers/gpio/gpiolib.c:2580
Inline: False
```
**Symbols:**

```
ffffffff814da040-ffffffff814da10a: gpiod_get_raw_value_commit (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int gpiod_get_raw_value_commit(const struct gpio_desc *desc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib.c (ffffffff81508ef0)
Location: drivers/gpio/gpiolib.c:2738
Inline: False
Direct callers:
  - drivers/gpio/gpiolib.c:gpiod_get_raw_value_cansleep
  - drivers/gpio/gpiolib.c:gpiod_get_value
  - drivers/gpio/gpiolib.c:gpiod_get_raw_value
```
**Symbols:**

```
ffffffff81508ef0-ffffffff81508fb9: gpiod_get_raw_value_commit (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int gpiod_get_raw_value_commit(const struct gpio_desc *desc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib.c (ffffffff8151d590)
Location: drivers/gpio/gpiolib.c:2818
Inline: False
Direct callers:
  - drivers/gpio/gpiolib.c:gpiod_get_raw_value_cansleep
  - drivers/gpio/gpiolib.c:gpiod_get_value
  - drivers/gpio/gpiolib.c:gpiod_get_raw_value
```
**Symbols:**

```
ffffffff8151d590-ffffffff8151d659: gpiod_get_raw_value_commit (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int gpiod_get_raw_value_commit(const struct gpio_desc *desc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib.c (ffffffff8154b680)
Location: drivers/gpio/gpiolib.c:2906
Inline: False
Direct callers:
  - drivers/gpio/gpiolib.c:gpiod_get_raw_value_cansleep
  - drivers/gpio/gpiolib.c:gpiod_get_value
  - drivers/gpio/gpiolib.c:gpiod_get_raw_value
```
**Symbols:**

```
ffffffff8154b680-ffffffff8154b75a: gpiod_get_raw_value_commit (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int gpiod_get_raw_value_commit(const struct gpio_desc *desc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib.c (ffffffff8156c860)
Location: drivers/gpio/gpiolib.c:3264
Inline: False
Direct callers:
  - drivers/gpio/gpiolib.c:gpiod_get_raw_value_cansleep
  - drivers/gpio/gpiolib.c:gpiod_get_value
  - drivers/gpio/gpiolib.c:gpiod_get_raw_value
```
**Symbols:**

```
ffffffff8156c860-ffffffff8156c93a: gpiod_get_raw_value_commit (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int gpiod_get_raw_value_commit(const struct gpio_desc *desc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib.c (ffffffff8160e970)
Location: drivers/gpio/gpiolib.c:3672
Inline: False
Direct callers:
  - drivers/gpio/gpiolib.c:gpiod_get_raw_value_cansleep
  - drivers/gpio/gpiolib.c:gpiod_get_value
  - drivers/gpio/gpiolib.c:gpiod_get_raw_value
  - drivers/gpio/gpiolib.c:lineevent_irq_thread
  - drivers/gpio/gpiolib.c:lineevent_ioctl
```
**Symbols:**

```
ffffffff8160e970-ffffffff8160ea38: gpiod_get_raw_value_commit (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int gpiod_get_raw_value_commit(const struct gpio_desc *desc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib.c (ffffffff81635ad0)
Location: drivers/gpio/gpiolib.c:2498
Inline: False
Direct callers:
  - drivers/gpio/gpiolib.c:gpiod_get_raw_value_cansleep
  - drivers/gpio/gpiolib.c:gpiod_get_value
  - drivers/gpio/gpiolib.c:gpiod_get_raw_value
```
**Symbols:**

```
ffffffff81635ad0-ffffffff81635b92: gpiod_get_raw_value_commit (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int gpiod_get_raw_value_commit(const struct gpio_desc *desc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib.c (ffffffff81619f20)
Location: drivers/gpio/gpiolib.c:2475
Inline: False
Direct callers:
  - drivers/gpio/gpiolib.c:gpiod_get_raw_value_cansleep
  - drivers/gpio/gpiolib.c:gpiod_get_value
  - drivers/gpio/gpiolib.c:gpiod_get_raw_value
```
**Symbols:**

```
ffffffff81619f20-ffffffff81619fe2: gpiod_get_raw_value_commit (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int gpiod_get_raw_value_commit(const struct gpio_desc *desc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib.c (ffffffff81689330)
Location: drivers/gpio/gpiolib.c:2504
Inline: False
Direct callers:
  - drivers/gpio/gpiolib.c:gpiod_get_raw_value_cansleep
  - drivers/gpio/gpiolib.c:gpiod_get_value
  - drivers/gpio/gpiolib.c:gpiod_get_raw_value
```
**Symbols:**

```
ffffffff81689330-ffffffff816893ef: gpiod_get_raw_value_commit (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int gpiod_get_raw_value_commit(const struct gpio_desc *desc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib.c (ffffffff817a5f60)
Location: drivers/gpio/gpiolib.c:2627
Inline: False
Direct callers:
  - drivers/gpio/gpiolib.c:gpiod_get_raw_value_cansleep
  - drivers/gpio/gpiolib.c:gpiod_get_value
  - drivers/gpio/gpiolib.c:gpiod_get_raw_value
```
**Symbols:**

```
ffffffff817a5f60-ffffffff817a603e: gpiod_get_raw_value_commit (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int gpiod_get_raw_value_commit(const struct gpio_desc *desc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib.c (ffffffff818bde80)
Location: drivers/gpio/gpiolib.c:2697
Inline: False
Direct callers:
  - drivers/gpio/gpiolib.c:gpiod_get_raw_value_cansleep
  - drivers/gpio/gpiolib.c:gpiod_get_value
  - drivers/gpio/gpiolib.c:gpiod_get_raw_value
```
**Symbols:**

```
ffffffff818bde80-ffffffff818bdf5e: gpiod_get_raw_value_commit (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int gpiod_get_raw_value_commit(const struct gpio_desc *desc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib.c (ffffffff81901040)
Location: drivers/gpio/gpiolib.c:2738
Inline: False
Direct callers:
  - drivers/gpio/gpiolib.c:gpiod_get_raw_value_cansleep
  - drivers/gpio/gpiolib.c:gpiod_get_value
  - drivers/gpio/gpiolib.c:gpiod_get_raw_value
```
**Symbols:**

```
ffffffff81901040-ffffffff8190111e: gpiod_get_raw_value_commit (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int gpiod_get_raw_value_commit(const struct gpio_desc *desc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib.c (ffffffff81948980)
Location: drivers/gpio/gpiolib.c:2931
Inline: False
Direct callers:
  - drivers/gpio/gpiolib.c:gpiod_get_raw_value_cansleep
  - drivers/gpio/gpiolib.c:gpiod_get_value
  - drivers/gpio/gpiolib.c:gpiod_get_raw_value
```
**Symbols:**

```
ffffffff81948980-ffffffff81948a46: gpiod_get_raw_value_commit (STB_LOCAL)
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
int gpiod_get_raw_value_commit(const struct gpio_desc *desc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib.c (ffff8000106bfb98)
Location: drivers/gpio/gpiolib.c:3264
Inline: False
Direct callers:
  - drivers/gpio/gpiolib.c:gpiod_get_raw_value_cansleep
  - drivers/gpio/gpiolib.c:gpiod_get_value
  - drivers/gpio/gpiolib.c:gpiod_get_raw_value
```
**Symbols:**

```
ffff8000106bfb98-ffff8000106bfc98: gpiod_get_raw_value_commit (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int gpiod_get_raw_value_commit(const struct gpio_desc *desc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib.c (c08603d4)
Location: drivers/gpio/gpiolib.c:3264
Inline: False
Direct callers:
  - drivers/gpio/gpiolib.c:gpiod_get_raw_value_cansleep
  - drivers/gpio/gpiolib.c:gpiod_get_value
  - drivers/gpio/gpiolib.c:gpiod_get_raw_value
```
**Symbols:**

```
c08603d4-c08604cc: gpiod_get_raw_value_commit (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int gpiod_get_raw_value_commit(const struct gpio_desc *desc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib.c (c00000000083dc00)
Location: drivers/gpio/gpiolib.c:3264
Inline: False
Direct callers:
  - drivers/gpio/gpiolib.c:gpiod_get_raw_value_cansleep
  - drivers/gpio/gpiolib.c:gpiod_get_value
  - drivers/gpio/gpiolib.c:gpiod_get_raw_value
```
**Symbols:**

```
c00000000083dc00-c00000000083dd68: gpiod_get_raw_value_commit (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int gpiod_get_raw_value_commit(const struct gpio_desc *desc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib.c (ffffffe0004a7122)
Location: drivers/gpio/gpiolib.c:3264
Inline: False
Direct callers:
  - drivers/gpio/gpiolib.c:gpiod_get_raw_value_cansleep
  - drivers/gpio/gpiolib.c:gpiod_get_value
  - drivers/gpio/gpiolib.c:gpiod_get_raw_value
```
**Symbols:**

```
ffffffe0004a7122-ffffffe0004a71de: gpiod_get_raw_value_commit (STB_LOCAL)
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
int gpiod_get_raw_value_commit(const struct gpio_desc *desc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib.c (ffffffff81562020)
Location: drivers/gpio/gpiolib.c:3264
Inline: False
Direct callers:
  - drivers/gpio/gpiolib.c:gpiod_get_raw_value_cansleep
  - drivers/gpio/gpiolib.c:gpiod_get_value
  - drivers/gpio/gpiolib.c:gpiod_get_raw_value
```
**Symbols:**

```
ffffffff81562020-ffffffff815620fa: gpiod_get_raw_value_commit (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int gpiod_get_raw_value_commit(const struct gpio_desc *desc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib.c (ffffffff81552e70)
Location: drivers/gpio/gpiolib.c:3264
Inline: False
Direct callers:
  - drivers/gpio/gpiolib.c:gpiod_get_raw_value_cansleep
  - drivers/gpio/gpiolib.c:gpiod_get_value
  - drivers/gpio/gpiolib.c:gpiod_get_raw_value
```
**Symbols:**

```
ffffffff81552e70-ffffffff81552f4a: gpiod_get_raw_value_commit (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int gpiod_get_raw_value_commit(const struct gpio_desc *desc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib.c (ffffffff81560b90)
Location: drivers/gpio/gpiolib.c:3264
Inline: False
Direct callers:
  - drivers/gpio/gpiolib.c:gpiod_get_raw_value_cansleep
  - drivers/gpio/gpiolib.c:gpiod_get_value
  - drivers/gpio/gpiolib.c:gpiod_get_raw_value
```
**Symbols:**

```
ffffffff81560b90-ffffffff81560c6a: gpiod_get_raw_value_commit (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int gpiod_get_raw_value_commit(const struct gpio_desc *desc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib.c (ffffffff8157aa30)
Location: drivers/gpio/gpiolib.c:3264
Inline: False
Direct callers:
  - drivers/gpio/gpiolib.c:gpiod_get_raw_value_cansleep
  - drivers/gpio/gpiolib.c:gpiod_get_value
  - drivers/gpio/gpiolib.c:gpiod_get_raw_value
```
**Symbols:**

```
ffffffff8157aa30-ffffffff8157ab21: gpiod_get_raw_value_commit (STB_LOCAL)
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
