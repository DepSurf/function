# Function: <code>gpio_v2_line_config_output_value</code>

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
In <code>5.8</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>5.11</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib-cdev.c (ffffffff8163b344)
Location: drivers/gpio/gpiolib-cdev.c:875
Inline: True
Inline callers:
  - drivers/gpio/gpiolib-cdev.c:linereq_create
  - drivers/gpio/gpiolib-cdev.c:linereq_set_config_unlocked
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
In drivers/gpio/gpiolib-cdev.c (ffffffff8161e9a5)
Location: drivers/gpio/gpiolib-cdev.c:875
Inline: True
Inline callers:
  - drivers/gpio/gpiolib-cdev.c:linereq_create
  - drivers/gpio/gpiolib-cdev.c:linereq_set_config_unlocked
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int gpio_v2_line_config_output_value(struct gpio_v2_line_config *lc, unsigned int line_idx);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/gpio/gpiolib-cdev.c (0)
Location: drivers/gpio/gpiolib-cdev.c:875
Inline: False
Direct callers:
  - drivers/gpio/gpiolib-cdev.c:linereq_create
  - drivers/gpio/gpiolib-cdev.c:linereq_set_config_unlocked
```
**Symbols:**

```
ffffffff8168cd30-ffffffff8168cd99: gpio_v2_line_config_output_value (STB_LOCAL)
ffffffff81ce23fe-ffffffff81ce241c: gpio_v2_line_config_output_value.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int gpio_v2_line_config_output_value(struct gpio_v2_line_config *lc, unsigned int line_idx);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/gpio/gpiolib-cdev.c (0)
Location: drivers/gpio/gpiolib-cdev.c:1051
Inline: False
Direct callers:
  - drivers/gpio/gpiolib-cdev.c:linereq_create
  - drivers/gpio/gpiolib-cdev.c:linereq_set_config_unlocked
```
**Symbols:**

```
ffffffff817aa750-ffffffff817aa7d1: gpio_v2_line_config_output_value (STB_LOCAL)
ffffffff81ea8dff-ffffffff81ea8e1d: gpio_v2_line_config_output_value.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
int gpio_v2_line_config_output_value(struct gpio_v2_line_config *lc, unsigned int line_idx);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/gpio/gpiolib-cdev.c (0)
Location: drivers/gpio/gpiolib-cdev.c:1119
Inline: False
Direct callers:
  - drivers/gpio/gpiolib-cdev.c:linereq_create
  - drivers/gpio/gpiolib-cdev.c:linereq_set_config_unlocked
```
**Symbols:**

```
ffffffff818c3300-ffffffff818c3381: gpio_v2_line_config_output_value (STB_LOCAL)
ffffffff8208e712-ffffffff8208e730: gpio_v2_line_config_output_value.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
int gpio_v2_line_config_output_value(struct gpio_v2_line_config *lc, unsigned int line_idx);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/gpio/gpiolib-cdev.c (0)
Location: drivers/gpio/gpiolib-cdev.c:1118
Inline: False
Direct callers:
  - drivers/gpio/gpiolib-cdev.c:linereq_create
  - drivers/gpio/gpiolib-cdev.c:linereq_set_config_unlocked
```
**Symbols:**

```
ffffffff81906360-ffffffff81906475: gpio_v2_line_config_output_value (STB_LOCAL)
ffffffff8210ea25-ffffffff8210ea4b: gpio_v2_line_config_output_value.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
int gpio_v2_line_config_output_value(struct gpio_v2_line_config *lc, unsigned int line_idx);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/gpio/gpiolib-cdev.c (0)
Location: drivers/gpio/gpiolib-cdev.c:1206
Inline: False
Direct callers:
  - drivers/gpio/gpiolib-cdev.c:linereq_create
  - drivers/gpio/gpiolib-cdev.c:linereq_set_config
```
**Symbols:**

```
ffffffff8194de70-ffffffff8194df85: gpio_v2_line_config_output_value (STB_LOCAL)
ffffffff821ec677-ffffffff821ec69d: gpio_v2_line_config_output_value.cold (STB_LOCAL)
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
