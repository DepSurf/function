# Function: <code>bgpio_read64</code>

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
long unsigned int bgpio_read64(void *reg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpio-mmio.c (ffffffff817b1990)
Location: drivers/gpio/gpio-mmio.c:99
Inline: False
```
**Symbols:**

```
ffffffff817b1990-ffffffff817b19a4: bgpio_read64 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
long unsigned int bgpio_read64(void *reg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpio-mmio.c (ffffffff818cb800)
Location: drivers/gpio/gpio-mmio.c:99
Inline: False
```
**Symbols:**

```
ffffffff818cb800-ffffffff818cb814: bgpio_read64 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
long unsigned int bgpio_read64(void *reg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpio-mmio.c (ffffffff8190e870)
Location: drivers/gpio/gpio-mmio.c:99
Inline: False
```
**Symbols:**

```
ffffffff8190e870-ffffffff8190e884: bgpio_read64 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
long unsigned int bgpio_read64(void *reg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpio-mmio.c (ffffffff819565e0)
Location: drivers/gpio/gpio-mmio.c:98
Inline: False
```
**Symbols:**

```
ffffffff819565e0-ffffffff819565f4: bgpio_read64 (STB_LOCAL)
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
long unsigned int bgpio_read64(void *reg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpio-mmio.c (ffff8000106cc290)
Location: drivers/gpio/gpio-mmio.c:99
Inline: False
```
**Symbols:**

```
ffff8000106cc290-ffff8000106cc2c4: bgpio_read64 (STB_LOCAL)
```
</details>
</li>
<li>
In <code>armhf</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
long unsigned int bgpio_read64(void *reg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpio-mmio.c (c000000000848e80)
Location: drivers/gpio/gpio-mmio.c:99
Inline: False
```
**Symbols:**

```
c000000000848e80-c000000000848f04: bgpio_read64 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
long unsigned int bgpio_read64(void *reg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpio-mmio.c (ffffffe0004ad36a)
Location: drivers/gpio/gpio-mmio.c:99
Inline: False
```
**Symbols:**

```
ffffffe0004ad36a-ffffffe0004ad390: bgpio_read64 (STB_LOCAL)
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
long unsigned int bgpio_read64(void *reg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpio-mmio.c (ffffffff81569a70)
Location: drivers/gpio/gpio-mmio.c:99
Inline: False
```
**Symbols:**

```
ffffffff81569a70-ffffffff81569a7e: bgpio_read64 (STB_LOCAL)
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
