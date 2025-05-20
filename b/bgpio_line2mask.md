# Function: <code>bgpio_line2mask</code>

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
<summary>In <code>5.19</code>: Selective Inline, Transformation ⚠️</summary>

```c
long unsigned int bgpio_line2mask(struct gpio_chip *gc, unsigned int line);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/gpio/gpio-mmio.c (ffffffff817b2b55)
Location: drivers/gpio/gpio-mmio.c:125
Inline: True
Inline callers:
  - drivers/gpio/gpio-mmio.c:bgpio_set_with_clear
  - drivers/gpio/gpio-mmio.c:bgpio_set_with_clear
  - drivers/gpio/gpio-mmio.c:bgpio_get
  - drivers/gpio/gpio-mmio.c:bgpio_get
  - drivers/gpio/gpio-mmio.c:bgpio_get_set
  - drivers/gpio/gpio-mmio.c:bgpio_get_set
Direct callers:
  - drivers/gpio/gpio-mmio.c:bgpio_get_dir
  - drivers/gpio/gpio-mmio.c:bgpio_get_dir
  - drivers/gpio/gpio-mmio.c:bgpio_dir_in
  - drivers/gpio/gpio-mmio.c:bgpio_multiple_get_masks
  - drivers/gpio/gpio-mmio.c:bgpio_multiple_get_masks
  - drivers/gpio/gpio-mmio.c:bgpio_set_set
  - drivers/gpio/gpio-mmio.c:bgpio_set
  - drivers/gpio/gpio-mmio.c:bgpio_get_multiple_be
  - drivers/gpio/gpio-mmio.c:bgpio_get_multiple_be
```
**Symbols:**

```
ffffffff817b1f90-ffffffff817b1ff6: bgpio_line2mask (STB_LOCAL)
ffffffff81ea926e-ffffffff81ea92c5: bgpio_line2mask.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline, Transformation ⚠️</summary>

```c
long unsigned int bgpio_line2mask(struct gpio_chip *gc, unsigned int line);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/gpio/gpio-mmio.c (ffffffff818ccaf5)
Location: drivers/gpio/gpio-mmio.c:125
Inline: True
Inline callers:
  - drivers/gpio/gpio-mmio.c:bgpio_set_with_clear
  - drivers/gpio/gpio-mmio.c:bgpio_set_with_clear
  - drivers/gpio/gpio-mmio.c:bgpio_get
  - drivers/gpio/gpio-mmio.c:bgpio_get
  - drivers/gpio/gpio-mmio.c:bgpio_get_set
  - drivers/gpio/gpio-mmio.c:bgpio_get_set
Direct callers:
  - drivers/gpio/gpio-mmio.c:bgpio_get_dir
  - drivers/gpio/gpio-mmio.c:bgpio_get_dir
  - drivers/gpio/gpio-mmio.c:bgpio_dir_in
  - drivers/gpio/gpio-mmio.c:bgpio_multiple_get_masks
  - drivers/gpio/gpio-mmio.c:bgpio_multiple_get_masks
  - drivers/gpio/gpio-mmio.c:bgpio_set_set
  - drivers/gpio/gpio-mmio.c:bgpio_set
  - drivers/gpio/gpio-mmio.c:bgpio_get_multiple_be
  - drivers/gpio/gpio-mmio.c:bgpio_get_multiple_be
```
**Symbols:**

```
ffffffff818cbed0-ffffffff818cbf36: bgpio_line2mask (STB_LOCAL)
ffffffff8208e976-ffffffff8208e9cd: bgpio_line2mask.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline, Transformation ⚠️</summary>

```c
long unsigned int bgpio_line2mask(struct gpio_chip *gc, unsigned int line);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/gpio/gpio-mmio.c (ffffffff8190fb65)
Location: drivers/gpio/gpio-mmio.c:125
Inline: True
Inline callers:
  - drivers/gpio/gpio-mmio.c:bgpio_set_with_clear
  - drivers/gpio/gpio-mmio.c:bgpio_set_with_clear
  - drivers/gpio/gpio-mmio.c:bgpio_get
  - drivers/gpio/gpio-mmio.c:bgpio_get
  - drivers/gpio/gpio-mmio.c:bgpio_get_set
  - drivers/gpio/gpio-mmio.c:bgpio_get_set
Direct callers:
  - drivers/gpio/gpio-mmio.c:bgpio_get_dir
  - drivers/gpio/gpio-mmio.c:bgpio_get_dir
  - drivers/gpio/gpio-mmio.c:bgpio_dir_in
  - drivers/gpio/gpio-mmio.c:bgpio_multiple_get_masks
  - drivers/gpio/gpio-mmio.c:bgpio_multiple_get_masks
  - drivers/gpio/gpio-mmio.c:bgpio_set_set
  - drivers/gpio/gpio-mmio.c:bgpio_set
  - drivers/gpio/gpio-mmio.c:bgpio_get_multiple_be
  - drivers/gpio/gpio-mmio.c:bgpio_get_multiple_be
```
**Symbols:**

```
ffffffff8190ef40-ffffffff8190efa6: bgpio_line2mask (STB_LOCAL)
ffffffff8210ec68-ffffffff8210ecbf: bgpio_line2mask.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline, Transformation ⚠️</summary>

```c
long unsigned int bgpio_line2mask(struct gpio_chip *gc, unsigned int line);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/gpio/gpio-mmio.c (ffffffff81957a35)
Location: drivers/gpio/gpio-mmio.c:124
Inline: True
Inline callers:
  - drivers/gpio/gpio-mmio.c:bgpio_set_with_clear
  - drivers/gpio/gpio-mmio.c:bgpio_set_with_clear
  - drivers/gpio/gpio-mmio.c:bgpio_get
  - drivers/gpio/gpio-mmio.c:bgpio_get
  - drivers/gpio/gpio-mmio.c:bgpio_get_set
  - drivers/gpio/gpio-mmio.c:bgpio_get_set
Direct callers:
  - drivers/gpio/gpio-mmio.c:bgpio_get_dir
  - drivers/gpio/gpio-mmio.c:bgpio_get_dir
  - drivers/gpio/gpio-mmio.c:bgpio_dir_in
  - drivers/gpio/gpio-mmio.c:bgpio_multiple_get_masks
  - drivers/gpio/gpio-mmio.c:bgpio_multiple_get_masks
  - drivers/gpio/gpio-mmio.c:bgpio_set_set
  - drivers/gpio/gpio-mmio.c:bgpio_set
  - drivers/gpio/gpio-mmio.c:bgpio_get_multiple_be
  - drivers/gpio/gpio-mmio.c:bgpio_get_multiple_be
```
**Symbols:**

```
ffffffff81956d40-ffffffff81956da6: bgpio_line2mask (STB_LOCAL)
ffffffff821ec8f4-ffffffff821ec94b: bgpio_line2mask.cold (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpio-mmio.c (ffff8000106cd294)
Location: drivers/gpio/gpio-mmio.c:125
Inline: True
Inline callers:
  - drivers/gpio/gpio-mmio.c:bgpio_dir_out
  - drivers/gpio/gpio-mmio.c:bgpio_dir_in
  - drivers/gpio/gpio-mmio.c:bgpio_multiple_get_masks
  - drivers/gpio/gpio-mmio.c:bgpio_multiple_get_masks
  - drivers/gpio/gpio-mmio.c:bgpio_set_set
  - drivers/gpio/gpio-mmio.c:bgpio_set_with_clear
  - drivers/gpio/gpio-mmio.c:bgpio_set
  - drivers/gpio/gpio-mmio.c:bgpio_get_multiple_be
  - drivers/gpio/gpio-mmio.c:bgpio_get_multiple_be
  - drivers/gpio/gpio-mmio.c:bgpio_get
  - drivers/gpio/gpio-mmio.c:bgpio_get_set
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpio-mmio.c (c0867998)
Location: drivers/gpio/gpio-mmio.c:125
Inline: True
Inline callers:
  - drivers/gpio/gpio-mmio.c:bgpio_dir_out
  - drivers/gpio/gpio-mmio.c:bgpio_dir_in
  - drivers/gpio/gpio-mmio.c:bgpio_multiple_get_masks
  - drivers/gpio/gpio-mmio.c:bgpio_multiple_get_masks
  - drivers/gpio/gpio-mmio.c:bgpio_set_set
  - drivers/gpio/gpio-mmio.c:bgpio_set_with_clear
  - drivers/gpio/gpio-mmio.c:bgpio_set
  - drivers/gpio/gpio-mmio.c:bgpio_get_multiple_be
  - drivers/gpio/gpio-mmio.c:bgpio_get_multiple_be
  - drivers/gpio/gpio-mmio.c:bgpio_get
  - drivers/gpio/gpio-mmio.c:bgpio_get_set
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpio-mmio.c (c000000000848764)
Location: drivers/gpio/gpio-mmio.c:125
Inline: True
Inline callers:
  - drivers/gpio/gpio-mmio.c:bgpio_dir_out
  - drivers/gpio/gpio-mmio.c:bgpio_dir_in
  - drivers/gpio/gpio-mmio.c:bgpio_multiple_get_masks
  - drivers/gpio/gpio-mmio.c:bgpio_multiple_get_masks
  - drivers/gpio/gpio-mmio.c:bgpio_set_set
  - drivers/gpio/gpio-mmio.c:bgpio_set_with_clear
  - drivers/gpio/gpio-mmio.c:bgpio_set
  - drivers/gpio/gpio-mmio.c:bgpio_get_multiple_be
  - drivers/gpio/gpio-mmio.c:bgpio_get_multiple_be
  - drivers/gpio/gpio-mmio.c:bgpio_get
  - drivers/gpio/gpio-mmio.c:bgpio_get_set
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpio-mmio.c (ffffffe0004adad8)
Location: drivers/gpio/gpio-mmio.c:125
Inline: True
Inline callers:
  - drivers/gpio/gpio-mmio.c:bgpio_dir_out
  - drivers/gpio/gpio-mmio.c:bgpio_dir_in
  - drivers/gpio/gpio-mmio.c:bgpio_multiple_get_masks
  - drivers/gpio/gpio-mmio.c:bgpio_multiple_get_masks
  - drivers/gpio/gpio-mmio.c:bgpio_set_set
  - drivers/gpio/gpio-mmio.c:bgpio_set_with_clear
  - drivers/gpio/gpio-mmio.c:bgpio_set
  - drivers/gpio/gpio-mmio.c:bgpio_get_multiple_be
  - drivers/gpio/gpio-mmio.c:bgpio_get_multiple_be
  - drivers/gpio/gpio-mmio.c:bgpio_get
  - drivers/gpio/gpio-mmio.c:bgpio_get_set
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpio-mmio.c (ffffffff81569ef4)
Location: drivers/gpio/gpio-mmio.c:125
Inline: True
Inline callers:
  - drivers/gpio/gpio-mmio.c:bgpio_dir_out
  - drivers/gpio/gpio-mmio.c:bgpio_dir_in
  - drivers/gpio/gpio-mmio.c:bgpio_multiple_get_masks
  - drivers/gpio/gpio-mmio.c:bgpio_multiple_get_masks
  - drivers/gpio/gpio-mmio.c:bgpio_set_set
  - drivers/gpio/gpio-mmio.c:bgpio_set_with_clear
  - drivers/gpio/gpio-mmio.c:bgpio_set
  - drivers/gpio/gpio-mmio.c:bgpio_get_multiple_be
  - drivers/gpio/gpio-mmio.c:bgpio_get_multiple_be
  - drivers/gpio/gpio-mmio.c:bgpio_get
  - drivers/gpio/gpio-mmio.c:bgpio_get_set
```
</details>
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
