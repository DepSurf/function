# Function: <code>gpio_desc_to_lineinfo</code>

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
In <code>4.18</code>: Absent ⚠️
</li>
<li>
In <code>5.0</code>: Absent ⚠️
</li>
<li>
In <code>5.3</code>: Absent ⚠️
</li>
<li>
In <code>5.4</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void gpio_desc_to_lineinfo(struct gpio_desc *desc, struct gpioline_info *info);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib.c (ffffffff8160d740)
Location: drivers/gpio/gpiolib.c:1195
Inline: False
Direct callers:
  - drivers/gpio/gpiolib.c:gpio_ioctl
  - drivers/gpio/gpiolib.c:gpio_ioctl
```
**Symbols:**

```
ffffffff8160d740-ffffffff8160d8a6: gpio_desc_to_lineinfo (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
void gpio_desc_to_lineinfo(struct gpio_desc *desc, struct gpio_v2_line_info *info);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/gpio/gpiolib-cdev.c (0)
Location: drivers/gpio/gpiolib-cdev.c:1890
Inline: False
Direct callers:
  - drivers/gpio/gpiolib-cdev.c:lineinfo_get
  - drivers/gpio/gpiolib-cdev.c:lineinfo_get
```
**Symbols:**

```
ffffffff81639ae0-ffffffff81639d5b: gpio_desc_to_lineinfo (STB_LOCAL)
ffffffff81bf6803-ffffffff81bf681b: gpio_desc_to_lineinfo.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
void gpio_desc_to_lineinfo(struct gpio_desc *desc, struct gpio_v2_line_info *info);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/gpio/gpiolib-cdev.c (0)
Location: drivers/gpio/gpiolib-cdev.c:1891
Inline: False
Direct callers:
  - drivers/gpio/gpiolib-cdev.c:lineinfo_get
  - drivers/gpio/gpiolib-cdev.c:lineinfo_get
```
**Symbols:**

```
ffffffff8161d730-ffffffff8161d9ab: gpio_desc_to_lineinfo (STB_LOCAL)
ffffffff81be872b-ffffffff81be8743: gpio_desc_to_lineinfo.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
void gpio_desc_to_lineinfo(struct gpio_desc *desc, struct gpio_v2_line_info *info);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/gpio/gpiolib-cdev.c (0)
Location: drivers/gpio/gpiolib-cdev.c:1891
Inline: False
Direct callers:
  - drivers/gpio/gpiolib-cdev.c:lineinfo_get
  - drivers/gpio/gpiolib-cdev.c:lineinfo_get
```
**Symbols:**

```
ffffffff8168cda0-ffffffff8168d01b: gpio_desc_to_lineinfo (STB_LOCAL)
ffffffff81ce241c-ffffffff81ce2434: gpio_desc_to_lineinfo.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
void gpio_desc_to_lineinfo(struct gpio_desc *desc, struct gpio_v2_line_info *info);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/gpio/gpiolib-cdev.c (0)
Location: drivers/gpio/gpiolib-cdev.c:2082
Inline: False
Direct callers:
  - drivers/gpio/gpiolib-cdev.c:lineinfo_changed_notify
  - drivers/gpio/gpiolib-cdev.c:lineinfo_get
  - drivers/gpio/gpiolib-cdev.c:lineinfo_get
  - drivers/gpio/gpiolib-cdev.c:lineinfo_get_v1
  - drivers/gpio/gpiolib-cdev.c:lineinfo_get_v1
```
**Symbols:**

```
ffffffff817aa810-ffffffff817aaa97: gpio_desc_to_lineinfo (STB_LOCAL)
ffffffff81ea8e1d-ffffffff81ea8e35: gpio_desc_to_lineinfo.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void gpio_desc_to_lineinfo(struct gpio_desc *desc, struct gpio_v2_line_info *info);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib-cdev.c (ffffffff818c33e0)
Location: drivers/gpio/gpiolib-cdev.c:2236
Inline: False
Direct callers:
  - drivers/gpio/gpiolib-cdev.c:lineinfo_changed_notify
  - drivers/gpio/gpiolib-cdev.c:lineinfo_get
  - drivers/gpio/gpiolib-cdev.c:lineinfo_get
  - drivers/gpio/gpiolib-cdev.c:lineinfo_get_v1
  - drivers/gpio/gpiolib-cdev.c:lineinfo_get_v1
```
**Symbols:**

```
ffffffff818c33e0-ffffffff818c3691: gpio_desc_to_lineinfo (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void gpio_desc_to_lineinfo(struct gpio_desc *desc, struct gpio_v2_line_info *info);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib-cdev.c (ffffffff819064d0)
Location: drivers/gpio/gpiolib-cdev.c:2233
Inline: False
Direct callers:
  - drivers/gpio/gpiolib-cdev.c:lineinfo_changed_notify
  - drivers/gpio/gpiolib-cdev.c:lineinfo_get
  - drivers/gpio/gpiolib-cdev.c:lineinfo_get
  - drivers/gpio/gpiolib-cdev.c:lineinfo_get_v1
  - drivers/gpio/gpiolib-cdev.c:lineinfo_get_v1
```
**Symbols:**

```
ffffffff819064d0-ffffffff8190676d: gpio_desc_to_lineinfo (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void gpio_desc_to_lineinfo(struct gpio_desc *desc, struct gpio_v2_line_info *info);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib-cdev.c (ffffffff81950860)
Location: drivers/gpio/gpiolib-cdev.c:2300
Inline: False
Direct callers:
  - drivers/gpio/gpiolib-cdev.c:lineinfo_changed_notify
  - drivers/gpio/gpiolib-cdev.c:lineinfo_get
  - drivers/gpio/gpiolib-cdev.c:lineinfo_get
  - drivers/gpio/gpiolib-cdev.c:lineinfo_get_v1
  - drivers/gpio/gpiolib-cdev.c:lineinfo_get_v1
```
**Symbols:**

```
ffffffff81950860-ffffffff81950b0e: gpio_desc_to_lineinfo (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
In <code>arm64</code>: Absent ⚠️
</li>
<li>
In <code>armhf</code>: Absent ⚠️
</li>
<li>
In <code>ppc64el</code>: Absent ⚠️
</li>
<li>
In <code>riscv64</code>: Absent ⚠️
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
In <code>aws</code>: Absent ⚠️
</li>
<li>
In <code>azure</code>: Absent ⚠️
</li>
<li>
In <code>gcp</code>: Absent ⚠️
</li>
<li>
In <code>lowlatency</code>: Absent ⚠️
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
<details>
<summary>Changed between <code>5.8</code> and <code>5.11</code> ⚠️</summary>
<ul>
<li>
<b>Param type changed. </b>
<code>struct gpioline_info *info</code> ➡️ <code>struct gpio_v2_line_info *info</code>
</li>
</ul>
</details>
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
