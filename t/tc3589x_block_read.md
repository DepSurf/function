# Function: <code>tc3589x_block_read</code>

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
In <code>5.19</code>: Absent ⚠️
</li>
<li>
In <code>6.2</code>: Absent ⚠️
</li>
<li>
In <code>6.5</code>: Absent ⚠️
</li>
<li>
In <code>6.8</code>: Absent ⚠️
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: ✅</summary>

```c
int tc3589x_block_read(struct tc3589x *tc3589x, u8 reg, u8 length, u8 *values);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/mfd/tc3589x.c (ffff800010930918)
Location: drivers/mfd/tc3589x.c:81
Inline: False
Direct callers:
  - drivers/gpio/gpio-tc3589x.c:tc3589x_gpio_irq
```
**Symbols:**

```
ffff800010930918-ffff80001093098c: tc3589x_block_read (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int tc3589x_block_read(struct tc3589x *tc3589x, u8 reg, u8 length, u8 *values);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/mfd/tc3589x.c (c0a11ca8)
Location: drivers/mfd/tc3589x.c:81
Inline: False
Direct callers:
  - drivers/gpio/gpio-tc3589x.c:tc3589x_gpio_irq
```
**Symbols:**

```
c0a11ca8-c0a11cf8: tc3589x_block_read (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int tc3589x_block_read(struct tc3589x *tc3589x, u8 reg, u8 length, u8 *values);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/mfd/tc3589x.c (c0000000009d0960)
Location: drivers/mfd/tc3589x.c:81
Inline: False
Direct callers:
  - drivers/gpio/gpio-tc3589x.c:tc3589x_gpio_irq
```
**Symbols:**

```
c0000000009d0960-c0000000009d09e8: tc3589x_block_read (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int tc3589x_block_read(struct tc3589x *tc3589x, u8 reg, u8 length, u8 *values);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/mfd/tc3589x.c (ffffffe0005a6e60)
Location: drivers/mfd/tc3589x.c:81
Inline: False
Direct callers:
  - drivers/gpio/gpio-tc3589x.c:tc3589x_gpio_irq
```
**Symbols:**

```
ffffffe0005a6e60-ffffffe0005a6ec6: tc3589x_block_read (STB_GLOBAL)
```
</details>
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
<b>Arch</b>
<ul>
</ul>
