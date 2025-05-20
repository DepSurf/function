# Function: <code>bgpio_multiple_get_masks</code>

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
void bgpio_multiple_get_masks(struct gpio_chip *gc, long unsigned int *mask, long unsigned int *bits, long unsigned int *set_mask, long unsigned int *clear_mask);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpio-mmio.c (ffffffff817b23b0)
Location: drivers/gpio/gpio-mmio.c:263
Inline: False
Direct callers:
  - drivers/gpio/gpio-mmio.c:bgpio_set_multiple_with_clear
  - drivers/gpio/gpio-mmio.c:bgpio_set_multiple_single_reg
```
**Symbols:**

```
ffffffff817b23b0-ffffffff817b247a: bgpio_multiple_get_masks (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void bgpio_multiple_get_masks(struct gpio_chip *gc, long unsigned int *mask, long unsigned int *bits, long unsigned int *set_mask, long unsigned int *clear_mask);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpio-mmio.c (ffffffff818cc480)
Location: drivers/gpio/gpio-mmio.c:263
Inline: False
Direct callers:
  - drivers/gpio/gpio-mmio.c:bgpio_set_multiple_with_clear
  - drivers/gpio/gpio-mmio.c:bgpio_set_multiple_single_reg
```
**Symbols:**

```
ffffffff818cc480-ffffffff818cc51c: bgpio_multiple_get_masks (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void bgpio_multiple_get_masks(struct gpio_chip *gc, long unsigned int *mask, long unsigned int *bits, long unsigned int *set_mask, long unsigned int *clear_mask);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpio-mmio.c (ffffffff8190f4f0)
Location: drivers/gpio/gpio-mmio.c:263
Inline: False
Direct callers:
  - drivers/gpio/gpio-mmio.c:bgpio_set_multiple_with_clear
  - drivers/gpio/gpio-mmio.c:bgpio_set_multiple_single_reg
```
**Symbols:**

```
ffffffff8190f4f0-ffffffff8190f58c: bgpio_multiple_get_masks (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void bgpio_multiple_get_masks(struct gpio_chip *gc, long unsigned int *mask, long unsigned int *bits, long unsigned int *set_mask, long unsigned int *clear_mask);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpio-mmio.c (ffffffff819572f0)
Location: drivers/gpio/gpio-mmio.c:262
Inline: False
Direct callers:
  - drivers/gpio/gpio-mmio.c:bgpio_set_multiple_with_clear
  - drivers/gpio/gpio-mmio.c:bgpio_set_multiple_single_reg
```
**Symbols:**

```
ffffffff819572f0-ffffffff8195738c: bgpio_multiple_get_masks (STB_LOCAL)
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
void bgpio_multiple_get_masks(struct gpio_chip *gc, long unsigned int *mask, long unsigned int *bits, long unsigned int *set_mask, long unsigned int *clear_mask);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpio-mmio.c (ffff8000106cc5f0)
Location: drivers/gpio/gpio-mmio.c:265
Inline: False
Direct callers:
  - drivers/gpio/gpio-mmio.c:bgpio_set_multiple_with_clear
  - drivers/gpio/gpio-mmio.c:bgpio_set_multiple_single_reg
```
**Symbols:**

```
ffff8000106cc5f0-ffff8000106cc710: bgpio_multiple_get_masks (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void bgpio_multiple_get_masks(struct gpio_chip *gc, long unsigned int *mask, long unsigned int *bits, long unsigned int *set_mask, long unsigned int *clear_mask);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpio-mmio.c (c08675d4)
Location: drivers/gpio/gpio-mmio.c:265
Inline: False
Direct callers:
  - drivers/gpio/gpio-mmio.c:bgpio_set_multiple_with_clear
  - drivers/gpio/gpio-mmio.c:bgpio_set_multiple_single_reg
```
**Symbols:**

```
c08675d4-c08676c4: bgpio_multiple_get_masks (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void bgpio_multiple_get_masks(struct gpio_chip *gc, long unsigned int *mask, long unsigned int *bits, long unsigned int *set_mask, long unsigned int *clear_mask);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpio-mmio.c (c0000000008482a0)
Location: drivers/gpio/gpio-mmio.c:265
Inline: False
Direct callers:
  - drivers/gpio/gpio-mmio.c:bgpio_set_multiple_with_clear
  - drivers/gpio/gpio-mmio.c:bgpio_set_multiple_single_reg
```
**Symbols:**

```
c0000000008482a0-c0000000008483b8: bgpio_multiple_get_masks (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void bgpio_multiple_get_masks(struct gpio_chip *gc, long unsigned int *mask, long unsigned int *bits, long unsigned int *set_mask, long unsigned int *clear_mask);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpio-mmio.c (ffffffe0004ad760)
Location: drivers/gpio/gpio-mmio.c:265
Inline: False
Direct callers:
  - drivers/gpio/gpio-mmio.c:bgpio_set_multiple_with_clear
  - drivers/gpio/gpio-mmio.c:bgpio_set_multiple_single_reg
```
**Symbols:**

```
ffffffe0004ad760-ffffffe0004ad850: bgpio_multiple_get_masks (STB_LOCAL)
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
void bgpio_multiple_get_masks(struct gpio_chip *gc, long unsigned int *mask, long unsigned int *bits, long unsigned int *set_mask, long unsigned int *clear_mask);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpio-mmio.c (ffffffff8156a0d0)
Location: drivers/gpio/gpio-mmio.c:265
Inline: False
Direct callers:
  - drivers/gpio/gpio-mmio.c:bgpio_set_multiple_with_clear
  - drivers/gpio/gpio-mmio.c:bgpio_set_multiple_single_reg
```
**Symbols:**

```
ffffffff8156a0d0-ffffffff8156a17e: bgpio_multiple_get_masks (STB_LOCAL)
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
<b>Arch</b>
<ul>
</ul>
<b>Flavor</b>
<ul>
</ul>
