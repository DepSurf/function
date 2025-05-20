# Function: <code>gpio_v2_line_info_to_v1</code>

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
In <code>5.11</code>: Absent ⚠️
</li>
<li>
In <code>5.13</code>: Absent ⚠️
</li>
<li>
In <code>5.15</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void gpio_v2_line_info_to_v1(struct gpio_v2_line_info *info_v2, struct gpioline_info *info_v1);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib-cdev.c (ffffffff817ab7e0)
Location: drivers/gpio/gpiolib-cdev.c:2038
Inline: False
Direct callers:
  - drivers/gpio/gpiolib-cdev.c:lineinfo_watch_read
  - drivers/gpio/gpiolib-cdev.c:lineinfo_get_v1
  - drivers/gpio/gpiolib-cdev.c:lineinfo_get_v1
```
**Symbols:**

```
ffffffff817ab7e0-ffffffff817ab894: gpio_v2_line_info_to_v1 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void gpio_v2_line_info_to_v1(struct gpio_v2_line_info *info_v2, struct gpioline_info *info_v1);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib-cdev.c (ffffffff818c5830)
Location: drivers/gpio/gpiolib-cdev.c:2192
Inline: False
Direct callers:
  - drivers/gpio/gpiolib-cdev.c:lineinfo_watch_read_unlocked
  - drivers/gpio/gpiolib-cdev.c:lineinfo_get_v1
  - drivers/gpio/gpiolib-cdev.c:lineinfo_get_v1
```
**Symbols:**

```
ffffffff818c5830-ffffffff818c58e4: gpio_v2_line_info_to_v1 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void gpio_v2_line_info_to_v1(struct gpio_v2_line_info *info_v2, struct gpioline_info *info_v1);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib-cdev.c (ffffffff819088e0)
Location: drivers/gpio/gpiolib-cdev.c:2189
Inline: False
Direct callers:
  - drivers/gpio/gpiolib-cdev.c:lineinfo_watch_read_unlocked
  - drivers/gpio/gpiolib-cdev.c:lineinfo_get_v1
  - drivers/gpio/gpiolib-cdev.c:lineinfo_get_v1
```
**Symbols:**

```
ffffffff819088e0-ffffffff81908994: gpio_v2_line_info_to_v1 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void gpio_v2_line_info_to_v1(struct gpio_v2_line_info *info_v2, struct gpioline_info *info_v1);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib-cdev.c (ffffffff8194ffd0)
Location: drivers/gpio/gpiolib-cdev.c:2256
Inline: False
Direct callers:
  - drivers/gpio/gpiolib-cdev.c:lineinfo_watch_read
  - drivers/gpio/gpiolib-cdev.c:lineinfo_get_v1
  - drivers/gpio/gpiolib-cdev.c:lineinfo_get_v1
```
**Symbols:**

```
ffffffff8194ffd0-ffffffff81950084: gpio_v2_line_info_to_v1 (STB_LOCAL)
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
No changes between <code>5.19</code> and <code>6.2</code> ✅
</li>
<li>
No changes between <code>6.2</code> and <code>6.5</code> ✅
</li>
<li>
No changes between <code>6.5</code> and <code>6.8</code> ✅
</li>
</ul>
