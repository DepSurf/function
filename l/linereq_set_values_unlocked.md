# Function: <code>linereq_set_values_unlocked</code>

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
long int linereq_set_values_unlocked(struct linereq *lr, struct gpio_v2_line_values *lv);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib-cdev.c (ffffffff8163a240)
Location: drivers/gpio/gpiolib-cdev.c:1058
Inline: False
Direct callers:
  - drivers/gpio/gpiolib-cdev.c:linereq_ioctl_compat
```
**Symbols:**

```
ffffffff8163a240-ffffffff8163a3b3: linereq_set_values_unlocked (STB_LOCAL)
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
In drivers/gpio/gpiolib-cdev.c (ffffffff8161dedc)
Location: drivers/gpio/gpiolib-cdev.c:1058
Inline: True
Inline callers:
  - drivers/gpio/gpiolib-cdev.c:linereq_set_values
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
long int linereq_set_values_unlocked(struct linereq *lr, struct gpio_v2_line_values *lv);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/gpio/gpiolib-cdev.c (0)
Location: drivers/gpio/gpiolib-cdev.c:1058
Inline: False
Direct callers:
  - drivers/gpio/gpiolib-cdev.c:linereq_ioctl_compat
```
**Symbols:**

```
ffffffff8168d5b0-ffffffff8168d756: linereq_set_values_unlocked (STB_LOCAL)
ffffffff81ce2434-ffffffff81ce2491: linereq_set_values_unlocked.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
long int linereq_set_values_unlocked(struct linereq *lr, struct gpio_v2_line_values *lv);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/gpio/gpiolib-cdev.c (0)
Location: drivers/gpio/gpiolib-cdev.c:1240
Inline: False
Direct callers:
  - drivers/gpio/gpiolib-cdev.c:linereq_ioctl_compat
```
**Symbols:**

```
ffffffff817acf80-ffffffff817ad143: linereq_set_values_unlocked (STB_LOCAL)
ffffffff81ea8e35-ffffffff81ea8e9a: linereq_set_values_unlocked.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
long int linereq_set_values_unlocked(struct linereq *lr, struct gpio_v2_line_values *lv);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/gpio/gpiolib-cdev.c (0)
Location: drivers/gpio/gpiolib-cdev.c:1314
Inline: False
Direct callers:
  - drivers/gpio/gpiolib-cdev.c:linereq_ioctl_unlocked
```
**Symbols:**

```
ffffffff818c6290-ffffffff818c6453: linereq_set_values_unlocked (STB_LOCAL)
ffffffff8208e730-ffffffff8208e795: linereq_set_values_unlocked.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
long int linereq_set_values_unlocked(struct linereq *lr, struct gpio_v2_line_values *lv);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/gpio/gpiolib-cdev.c (0)
Location: drivers/gpio/gpiolib-cdev.c:1313
Inline: False
Direct callers:
  - drivers/gpio/gpiolib-cdev.c:linereq_ioctl_unlocked
```
**Symbols:**

```
ffffffff81909350-ffffffff819094f3: linereq_set_values_unlocked (STB_LOCAL)
ffffffff8210ea4b-ffffffff8210ea8b: linereq_set_values_unlocked.cold (STB_LOCAL)
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
</ul>
