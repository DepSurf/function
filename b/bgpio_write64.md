# Function: <code>bgpio_write64</code>

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
void bgpio_write64(void *reg, long unsigned int data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpio-mmio.c (ffffffff817b1970)
Location: drivers/gpio/gpio-mmio.c:94
Inline: False
```
**Symbols:**

```
ffffffff817b1970-ffffffff817b1986: bgpio_write64 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void bgpio_write64(void *reg, long unsigned int data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpio-mmio.c (ffffffff818cb7d0)
Location: drivers/gpio/gpio-mmio.c:94
Inline: False
```
**Symbols:**

```
ffffffff818cb7d0-ffffffff818cb7e6: bgpio_write64 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void bgpio_write64(void *reg, long unsigned int data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpio-mmio.c (ffffffff8190e840)
Location: drivers/gpio/gpio-mmio.c:94
Inline: False
```
**Symbols:**

```
ffffffff8190e840-ffffffff8190e856: bgpio_write64 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void bgpio_write64(void *reg, long unsigned int data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpio-mmio.c (ffffffff819565b0)
Location: drivers/gpio/gpio-mmio.c:93
Inline: False
```
**Symbols:**

```
ffffffff819565b0-ffffffff819565c6: bgpio_write64 (STB_LOCAL)
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
void bgpio_write64(void *reg, long unsigned int data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpio-mmio.c (ffff8000106cc260)
Location: drivers/gpio/gpio-mmio.c:94
Inline: False
```
**Symbols:**

```
ffff8000106cc260-ffff8000106cc290: bgpio_write64 (STB_LOCAL)
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
void bgpio_write64(void *reg, long unsigned int data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpio-mmio.c (c000000000847d10)
Location: drivers/gpio/gpio-mmio.c:94
Inline: False
```
**Symbols:**

```
c000000000847d10-c000000000847d2c: bgpio_write64 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void bgpio_write64(void *reg, long unsigned int data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpio-mmio.c (ffffffe0004ad316)
Location: drivers/gpio/gpio-mmio.c:94
Inline: False
```
**Symbols:**

```
ffffffe0004ad316-ffffffe0004ad36a: bgpio_write64 (STB_LOCAL)
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
void bgpio_write64(void *reg, long unsigned int data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpio-mmio.c (ffffffff81569a60)
Location: drivers/gpio/gpio-mmio.c:94
Inline: False
```
**Symbols:**

```
ffffffff81569a60-ffffffff81569a6e: bgpio_write64 (STB_LOCAL)
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
