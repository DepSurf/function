# Function: <code>gpio_v2_line_config_debounce_period</code>

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
In drivers/gpio/gpiolib-cdev.c (ffffffff8163ac0a)
Location: drivers/gpio/gpiolib-cdev.c:755
Inline: True
Inline callers:
  - drivers/gpio/gpiolib-cdev.c:linereq_set_config_unlocked
  - drivers/gpio/gpiolib-cdev.c:edge_detector_setup
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
In drivers/gpio/gpiolib-cdev.c (ffffffff8161ef30)
Location: drivers/gpio/gpiolib-cdev.c:755
Inline: True
Inline callers:
  - drivers/gpio/gpiolib-cdev.c:linereq_set_config_unlocked
  - drivers/gpio/gpiolib-cdev.c:edge_detector_setup
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
u32 gpio_v2_line_config_debounce_period(struct gpio_v2_line_config *lc, unsigned int line_idx);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/gpio/gpiolib-cdev.c (0)
Location: drivers/gpio/gpiolib-cdev.c:755
Inline: False
Direct callers:
  - drivers/gpio/gpiolib-cdev.c:linereq_set_config_unlocked
  - drivers/gpio/gpiolib-cdev.c:edge_detector_setup
```
**Symbols:**

```
ffffffff8168cbe0-ffffffff8168cc4d: gpio_v2_line_config_debounce_period (STB_LOCAL)
ffffffff81ce23a4-ffffffff81ce23c2: gpio_v2_line_config_debounce_period.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
u32 gpio_v2_line_config_debounce_period(struct gpio_v2_line_config *lc, unsigned int line_idx);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/gpio/gpiolib-cdev.c (0)
Location: drivers/gpio/gpiolib-cdev.c:919
Inline: False
Direct callers:
  - drivers/gpio/gpiolib-cdev.c:linereq_set_config_unlocked
  - drivers/gpio/gpiolib-cdev.c:edge_detector_setup
```
**Symbols:**

```
ffffffff817aa5d0-ffffffff817aa64e: gpio_v2_line_config_debounce_period (STB_LOCAL)
ffffffff81ea8da5-ffffffff81ea8dc3: gpio_v2_line_config_debounce_period.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
u32 gpio_v2_line_config_debounce_period(struct gpio_v2_line_config *lc, unsigned int line_idx);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/gpio/gpiolib-cdev.c (0)
Location: drivers/gpio/gpiolib-cdev.c:990
Inline: False
Direct callers:
  - drivers/gpio/gpiolib-cdev.c:linereq_set_config_unlocked
  - drivers/gpio/gpiolib-cdev.c:edge_detector_setup
```
**Symbols:**

```
ffffffff818c3150-ffffffff818c31ce: gpio_v2_line_config_debounce_period (STB_LOCAL)
ffffffff8208e6b8-ffffffff8208e6d6: gpio_v2_line_config_debounce_period.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
u32 gpio_v2_line_config_debounce_period(struct gpio_v2_line_config *lc, unsigned int line_idx);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/gpio/gpiolib-cdev.c (0)
Location: drivers/gpio/gpiolib-cdev.c:989
Inline: False
Direct callers:
  - drivers/gpio/gpiolib-cdev.c:linereq_set_config_unlocked
  - drivers/gpio/gpiolib-cdev.c:edge_detector_setup
```
**Symbols:**

```
ffffffff81906040-ffffffff81906148: gpio_v2_line_config_debounce_period (STB_LOCAL)
ffffffff8210e9bb-ffffffff8210e9e1: gpio_v2_line_config_debounce_period.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
u32 gpio_v2_line_config_debounce_period(struct gpio_v2_line_config *lc, unsigned int line_idx);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/gpio/gpiolib-cdev.c (0)
Location: drivers/gpio/gpiolib-cdev.c:1078
Inline: False
Direct callers:
  - drivers/gpio/gpiolib-cdev.c:linereq_set_config
  - drivers/gpio/gpiolib-cdev.c:edge_detector_setup
```
**Symbols:**

```
ffffffff8194db50-ffffffff8194dc58: gpio_v2_line_config_debounce_period (STB_LOCAL)
ffffffff821ec60d-ffffffff821ec633: gpio_v2_line_config_debounce_period.cold (STB_LOCAL)
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
