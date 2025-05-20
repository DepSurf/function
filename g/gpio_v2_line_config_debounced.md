# Function: <code>gpio_v2_line_config_debounced</code>

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
In drivers/gpio/gpiolib-cdev.c (ffffffff81639da4)
Location: drivers/gpio/gpiolib-cdev.c:741
Inline: True
Inline callers:
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
In drivers/gpio/gpiolib-cdev.c (ffffffff8161d9f4)
Location: drivers/gpio/gpiolib-cdev.c:741
Inline: True
Inline callers:
  - drivers/gpio/gpiolib-cdev.c:edge_detector_setup
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
bool gpio_v2_line_config_debounced(struct gpio_v2_line_config *lc, unsigned int line_idx);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/gpio/gpiolib-cdev.c (0)
Location: drivers/gpio/gpiolib-cdev.c:741
Inline: False
Direct callers:
  - drivers/gpio/gpiolib-cdev.c:edge_detector_setup
  - drivers/gpio/gpiolib-cdev.c:edge_detector_setup
```
**Symbols:**

```
ffffffff8168cc50-ffffffff8168ccb7: gpio_v2_line_config_debounced (STB_LOCAL)
ffffffff81ce23c2-ffffffff81ce23e0: gpio_v2_line_config_debounced.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
bool gpio_v2_line_config_debounced(struct gpio_v2_line_config *lc, unsigned int line_idx);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/gpio/gpiolib-cdev.c (0)
Location: drivers/gpio/gpiolib-cdev.c:905
Inline: False
Direct callers:
  - drivers/gpio/gpiolib-cdev.c:gpio_v2_line_config_validate
  - drivers/gpio/gpiolib-cdev.c:edge_detector_setup
  - drivers/gpio/gpiolib-cdev.c:edge_detector_setup
```
**Symbols:**

```
ffffffff817aa650-ffffffff817aa6ce: gpio_v2_line_config_debounced (STB_LOCAL)
ffffffff81ea8dc3-ffffffff81ea8de1: gpio_v2_line_config_debounced.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
bool gpio_v2_line_config_debounced(struct gpio_v2_line_config *lc, unsigned int line_idx);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/gpio/gpiolib-cdev.c (0)
Location: drivers/gpio/gpiolib-cdev.c:976
Inline: False
Direct callers:
  - drivers/gpio/gpiolib-cdev.c:gpio_v2_line_config_validate
  - drivers/gpio/gpiolib-cdev.c:edge_detector_setup
  - drivers/gpio/gpiolib-cdev.c:edge_detector_setup
  - drivers/gpio/gpiolib-cdev.c:edge_detector_setup
```
**Symbols:**

```
ffffffff818c31e0-ffffffff818c325e: gpio_v2_line_config_debounced (STB_LOCAL)
ffffffff8208e6d6-ffffffff8208e6f4: gpio_v2_line_config_debounced.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
bool gpio_v2_line_config_debounced(struct gpio_v2_line_config *lc, unsigned int line_idx);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/gpio/gpiolib-cdev.c (0)
Location: drivers/gpio/gpiolib-cdev.c:975
Inline: False
Direct callers:
  - drivers/gpio/gpiolib-cdev.c:gpio_v2_line_config_validate
  - drivers/gpio/gpiolib-cdev.c:edge_detector_setup
  - drivers/gpio/gpiolib-cdev.c:edge_detector_setup
  - drivers/gpio/gpiolib-cdev.c:edge_detector_setup
```
**Symbols:**

```
ffffffff81906160-ffffffff81906229: gpio_v2_line_config_debounced (STB_LOCAL)
ffffffff8210e9e1-ffffffff8210e9ff: gpio_v2_line_config_debounced.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
bool gpio_v2_line_config_debounced(struct gpio_v2_line_config *lc, unsigned int line_idx);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/gpio/gpiolib-cdev.c (0)
Location: drivers/gpio/gpiolib-cdev.c:1064
Inline: False
Direct callers:
  - drivers/gpio/gpiolib-cdev.c:gpio_v2_line_config_validate
  - drivers/gpio/gpiolib-cdev.c:edge_detector_setup
  - drivers/gpio/gpiolib-cdev.c:edge_detector_setup
  - drivers/gpio/gpiolib-cdev.c:edge_detector_setup
```
**Symbols:**

```
ffffffff8194dc70-ffffffff8194dd39: gpio_v2_line_config_debounced (STB_LOCAL)
ffffffff821ec633-ffffffff821ec651: gpio_v2_line_config_debounced.cold (STB_LOCAL)
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
