# Function: <code>edge_detector_setup</code>

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
<summary>In <code>5.11</code>: ✅</summary>

```c
int edge_detector_setup(struct line *line, struct gpio_v2_line_config *lc, unsigned int line_idx, u64 eflags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib-cdev.c (ffffffff81639d60)
Location: drivers/gpio/gpiolib-cdev.c:784
Inline: False
Direct callers:
  - drivers/gpio/gpiolib-cdev.c:linereq_create
  - drivers/gpio/gpiolib-cdev.c:linereq_set_config_unlocked
```
**Symbols:**

```
ffffffff81639d60-ffffffff81639fb1: edge_detector_setup (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int edge_detector_setup(struct line *line, struct gpio_v2_line_config *lc, unsigned int line_idx, u64 eflags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib-cdev.c (ffffffff8161d9b0)
Location: drivers/gpio/gpiolib-cdev.c:784
Inline: False
Direct callers:
  - drivers/gpio/gpiolib-cdev.c:linereq_create
  - drivers/gpio/gpiolib-cdev.c:linereq_set_config_unlocked
```
**Symbols:**

```
ffffffff8161d9b0-ffffffff8161dc09: edge_detector_setup (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int edge_detector_setup(struct line *line, struct gpio_v2_line_config *lc, unsigned int line_idx, u64 eflags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib-cdev.c (ffffffff8168d020)
Location: drivers/gpio/gpiolib-cdev.c:784
Inline: False
Direct callers:
  - drivers/gpio/gpiolib-cdev.c:linereq_create
  - drivers/gpio/gpiolib-cdev.c:linereq_set_config_unlocked
```
**Symbols:**

```
ffffffff8168d020-ffffffff8168d227: edge_detector_setup (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int edge_detector_setup(struct line *line, struct gpio_v2_line_config *lc, unsigned int line_idx, u64 eflags, bool hte_req);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib-cdev.c (ffffffff817ac1e0)
Location: drivers/gpio/gpiolib-cdev.c:951
Inline: False
Direct callers:
  - drivers/gpio/gpiolib-cdev.c:linereq_create
  - drivers/gpio/gpiolib-cdev.c:linereq_set_config_unlocked
```
**Symbols:**

```
ffffffff817ac1e0-ffffffff817ac435: edge_detector_setup (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int edge_detector_setup(struct line *line, struct gpio_v2_line_config *lc, unsigned int line_idx, u64 edflags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib-cdev.c (ffffffff818c5190)
Location: drivers/gpio/gpiolib-cdev.c:1024
Inline: False
Direct callers:
  - drivers/gpio/gpiolib-cdev.c:linereq_create
  - drivers/gpio/gpiolib-cdev.c:linereq_set_config_unlocked
```
**Symbols:**

```
ffffffff818c5190-ffffffff818c5401: edge_detector_setup (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int edge_detector_setup(struct line *line, struct gpio_v2_line_config *lc, unsigned int line_idx, u64 edflags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib-cdev.c (ffffffff81908260)
Location: drivers/gpio/gpiolib-cdev.c:1023
Inline: False
Direct callers:
  - drivers/gpio/gpiolib-cdev.c:linereq_create
  - drivers/gpio/gpiolib-cdev.c:linereq_set_config_unlocked
```
**Symbols:**

```
ffffffff81908260-ffffffff819084bf: edge_detector_setup (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int edge_detector_setup(struct line *line, struct gpio_v2_line_config *lc, unsigned int line_idx, u64 edflags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib-cdev.c (ffffffff8194fa70)
Location: drivers/gpio/gpiolib-cdev.c:1111
Inline: False
Direct callers:
  - drivers/gpio/gpiolib-cdev.c:linereq_create
  - drivers/gpio/gpiolib-cdev.c:linereq_set_config
```
**Symbols:**

```
ffffffff8194fa70-ffffffff8194fcd7: edge_detector_setup (STB_LOCAL)
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
No changes between <code>5.11</code> and <code>5.13</code> ✅
</li>
<li>
No changes between <code>5.13</code> and <code>5.15</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>5.15</code> and <code>5.19</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>bool hte_req</code>
</li>
</ul>
</details>
</li>
<li>
<details>
<summary>Changed between <code>5.19</code> and <code>6.2</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>u64 edflags</code>
</li>
<li>
<b>Param removed. </b>
<code>u64 eflags</code>
</li>
<li>
<b>Param removed. </b>
<code>bool hte_req</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>6.2</code> and <code>6.5</code> ✅
</li>
<li>
No changes between <code>6.5</code> and <code>6.8</code> ✅
</li>
</ul>
