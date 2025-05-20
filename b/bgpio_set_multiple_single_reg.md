# Function: <code>bgpio_set_multiple_single_reg</code>

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
void bgpio_set_multiple_single_reg(struct gpio_chip *gc, long unsigned int *mask, long unsigned int *bits, void *reg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpio-mmio.c (ffffffff817b2480)
Location: drivers/gpio/gpio-mmio.c:281
Inline: False
Direct callers:
  - drivers/gpio/gpio-mmio.c:bgpio_set_multiple_set
  - drivers/gpio/gpio-mmio.c:bgpio_set_multiple
```
**Symbols:**

```
ffffffff817b2480-ffffffff817b2555: bgpio_set_multiple_single_reg (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void bgpio_set_multiple_single_reg(struct gpio_chip *gc, long unsigned int *mask, long unsigned int *bits, void *reg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpio-mmio.c (ffffffff818cc530)
Location: drivers/gpio/gpio-mmio.c:281
Inline: False
Direct callers:
  - drivers/gpio/gpio-mmio.c:bgpio_set_multiple_set
  - drivers/gpio/gpio-mmio.c:bgpio_set_multiple
```
**Symbols:**

```
ffffffff818cc530-ffffffff818cc605: bgpio_set_multiple_single_reg (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void bgpio_set_multiple_single_reg(struct gpio_chip *gc, long unsigned int *mask, long unsigned int *bits, void *reg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpio-mmio.c (ffffffff8190f5a0)
Location: drivers/gpio/gpio-mmio.c:281
Inline: False
Direct callers:
  - drivers/gpio/gpio-mmio.c:bgpio_set_multiple_set
  - drivers/gpio/gpio-mmio.c:bgpio_set_multiple
```
**Symbols:**

```
ffffffff8190f5a0-ffffffff8190f675: bgpio_set_multiple_single_reg (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void bgpio_set_multiple_single_reg(struct gpio_chip *gc, long unsigned int *mask, long unsigned int *bits, void *reg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpio-mmio.c (ffffffff819573a0)
Location: drivers/gpio/gpio-mmio.c:280
Inline: False
Direct callers:
  - drivers/gpio/gpio-mmio.c:bgpio_set_multiple_set
  - drivers/gpio/gpio-mmio.c:bgpio_set_multiple
```
**Symbols:**

```
ffffffff819573a0-ffffffff81957475: bgpio_set_multiple_single_reg (STB_LOCAL)
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
void bgpio_set_multiple_single_reg(struct gpio_chip *gc, long unsigned int *mask, long unsigned int *bits, void *reg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpio-mmio.c (ffff8000106cd3c0)
Location: drivers/gpio/gpio-mmio.c:287
Inline: False
Direct callers:
  - drivers/gpio/gpio-mmio.c:bgpio_set_multiple_set
  - drivers/gpio/gpio-mmio.c:bgpio_set_multiple
```
**Symbols:**

```
ffff8000106cd3c0-ffff8000106cd4d4: bgpio_set_multiple_single_reg (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void bgpio_set_multiple_single_reg(struct gpio_chip *gc, long unsigned int *mask, long unsigned int *bits, void *reg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpio-mmio.c (c08676c4)
Location: drivers/gpio/gpio-mmio.c:287
Inline: False
Direct callers:
  - drivers/gpio/gpio-mmio.c:bgpio_set_multiple_set
  - drivers/gpio/gpio-mmio.c:bgpio_set_multiple
```
**Symbols:**

```
c08676c4-c0867780: bgpio_set_multiple_single_reg (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void bgpio_set_multiple_single_reg(struct gpio_chip *gc, long unsigned int *mask, long unsigned int *bits, void *reg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpio-mmio.c (c0000000008483c0)
Location: drivers/gpio/gpio-mmio.c:287
Inline: False
Direct callers:
  - drivers/gpio/gpio-mmio.c:bgpio_set_multiple_set
  - drivers/gpio/gpio-mmio.c:bgpio_set_multiple
```
**Symbols:**

```
c0000000008483c0-c0000000008484b0: bgpio_set_multiple_single_reg (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void bgpio_set_multiple_single_reg(struct gpio_chip *gc, long unsigned int *mask, long unsigned int *bits, void *reg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpio-mmio.c (ffffffe0004ad850)
Location: drivers/gpio/gpio-mmio.c:287
Inline: False
Direct callers:
  - drivers/gpio/gpio-mmio.c:bgpio_set_multiple_set
  - drivers/gpio/gpio-mmio.c:bgpio_set_multiple
```
**Symbols:**

```
ffffffe0004ad850-ffffffe0004ad8d6: bgpio_set_multiple_single_reg (STB_LOCAL)
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
void bgpio_set_multiple_single_reg(struct gpio_chip *gc, long unsigned int *mask, long unsigned int *bits, void *reg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpio-mmio.c (ffffffff8156a180)
Location: drivers/gpio/gpio-mmio.c:287
Inline: False
Direct callers:
  - drivers/gpio/gpio-mmio.c:bgpio_set_multiple_set
  - drivers/gpio/gpio-mmio.c:bgpio_set_multiple
```
**Symbols:**

```
ffffffff8156a180-ffffffff8156a234: bgpio_set_multiple_single_reg (STB_LOCAL)
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
