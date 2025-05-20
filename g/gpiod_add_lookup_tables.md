# Function: <code>gpiod_add_lookup_tables</code>

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
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void gpiod_add_lookup_tables(struct gpiod_lookup_table **tables, size_t n);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib.c (ffffffff814dc690)
Location: drivers/gpio/gpiolib.c:3304
Inline: False
```
**Symbols:**

```
ffffffff814dc690-ffffffff814dc6f6: gpiod_add_lookup_tables (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void gpiod_add_lookup_tables(struct gpiod_lookup_table **tables, size_t n);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib.c (ffffffff8150aa90)
Location: drivers/gpio/gpiolib.c:3495
Inline: False
```
**Symbols:**

```
ffffffff8150aa90-ffffffff8150aaf6: gpiod_add_lookup_tables (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void gpiod_add_lookup_tables(struct gpiod_lookup_table **tables, size_t n);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib.c (ffffffff8151f530)
Location: drivers/gpio/gpiolib.c:3745
Inline: False
```
**Symbols:**

```
ffffffff8151f530-ffffffff8151f596: gpiod_add_lookup_tables (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void gpiod_add_lookup_tables(struct gpiod_lookup_table **tables, size_t n);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib.c (ffffffff8154d6c0)
Location: drivers/gpio/gpiolib.c:3834
Inline: False
```
**Symbols:**

```
ffffffff8154d6c0-ffffffff8154d723: gpiod_add_lookup_tables (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void gpiod_add_lookup_tables(struct gpiod_lookup_table **tables, size_t n);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib.c (ffffffff8156e8c0)
Location: drivers/gpio/gpiolib.c:4188
Inline: False
```
**Symbols:**

```
ffffffff8156e8c0-ffffffff8156e923: gpiod_add_lookup_tables (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void gpiod_add_lookup_tables(struct gpiod_lookup_table **tables, size_t n);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib.c (ffffffff81612db0)
Location: drivers/gpio/gpiolib.c:4601
Inline: False
```
**Symbols:**

```
ffffffff81612db0-ffffffff81612e13: gpiod_add_lookup_tables (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void gpiod_add_lookup_tables(struct gpiod_lookup_table **tables, size_t n);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib.c (ffffffff81637c70)
Location: drivers/gpio/gpiolib.c:3425
Inline: False
```
**Symbols:**

```
ffffffff81637c70-ffffffff81637cd3: gpiod_add_lookup_tables (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void gpiod_add_lookup_tables(struct gpiod_lookup_table **tables, size_t n);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib.c (ffffffff8161b620)
Location: drivers/gpio/gpiolib.c:3402
Inline: False
```
**Symbols:**

```
ffffffff8161b620-ffffffff8161b683: gpiod_add_lookup_tables (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void gpiod_add_lookup_tables(struct gpiod_lookup_table **tables, size_t n);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib.c (ffffffff8168ab30)
Location: drivers/gpio/gpiolib.c:3461
Inline: False
```
**Symbols:**

```
ffffffff8168ab30-ffffffff8168ab93: gpiod_add_lookup_tables (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
void gpiod_add_lookup_tables(struct gpiod_lookup_table **tables, size_t n);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib.c (ffffffff817a51f5)
Location: drivers/gpio/gpiolib.c:3582
Inline: True
Inline callers:
  - drivers/gpio/gpiolib.c:gpiod_add_lookup_table
```
**Symbols:**

```
ffffffff817a7e50-ffffffff817a7ec1: gpiod_add_lookup_tables (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
void gpiod_add_lookup_tables(struct gpiod_lookup_table **tables, size_t n);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib.c (ffffffff818bd455)
Location: drivers/gpio/gpiolib.c:3652
Inline: True
Inline callers:
  - drivers/gpio/gpiolib.c:gpiod_add_lookup_table
```
**Symbols:**

```
ffffffff818c04b0-ffffffff818c0521: gpiod_add_lookup_tables (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
void gpiod_add_lookup_tables(struct gpiod_lookup_table **tables, size_t n);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib.c (ffffffff81900335)
Location: drivers/gpio/gpiolib.c:3693
Inline: True
Inline callers:
  - drivers/gpio/gpiolib.c:gpiod_add_lookup_table
```
**Symbols:**

```
ffffffff81903480-ffffffff819034f1: gpiod_add_lookup_tables (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
void gpiod_add_lookup_tables(struct gpiod_lookup_table **tables, size_t n);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib.c (ffffffff81947b65)
Location: drivers/gpio/gpiolib.c:3886
Inline: True
Inline callers:
  - drivers/gpio/gpiolib.c:gpiod_add_lookup_table
```
**Symbols:**

```
ffffffff8194b020-ffffffff8194b091: gpiod_add_lookup_tables (STB_GLOBAL)
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
void gpiod_add_lookup_tables(struct gpiod_lookup_table **tables, size_t n);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib.c (ffff8000106c4568)
Location: drivers/gpio/gpiolib.c:4188
Inline: False
```
**Symbols:**

```
ffff8000106c4568-ffff8000106c45e4: gpiod_add_lookup_tables (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void gpiod_add_lookup_tables(struct gpiod_lookup_table **tables, size_t n);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib.c (c086289c)
Location: drivers/gpio/gpiolib.c:4188
Inline: False
```
**Symbols:**

```
c086289c-c086290c: gpiod_add_lookup_tables (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void gpiod_add_lookup_tables(struct gpiod_lookup_table **tables, size_t n);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib.c (c000000000840ca0)
Location: drivers/gpio/gpiolib.c:4188
Inline: False
```
**Symbols:**

```
c000000000840ca0-c000000000840d6c: gpiod_add_lookup_tables (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void gpiod_add_lookup_tables(struct gpiod_lookup_table **tables, size_t n);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib.c (ffffffe0004a8d9a)
Location: drivers/gpio/gpiolib.c:4188
Inline: False
```
**Symbols:**

```
ffffffe0004a8d9a-ffffffe0004a8e12: gpiod_add_lookup_tables (STB_GLOBAL)
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
void gpiod_add_lookup_tables(struct gpiod_lookup_table **tables, size_t n);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib.c (ffffffff81564080)
Location: drivers/gpio/gpiolib.c:4188
Inline: False
```
**Symbols:**

```
ffffffff81564080-ffffffff815640e3: gpiod_add_lookup_tables (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void gpiod_add_lookup_tables(struct gpiod_lookup_table **tables, size_t n);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib.c (ffffffff81554ed0)
Location: drivers/gpio/gpiolib.c:4188
Inline: False
```
**Symbols:**

```
ffffffff81554ed0-ffffffff81554f33: gpiod_add_lookup_tables (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void gpiod_add_lookup_tables(struct gpiod_lookup_table **tables, size_t n);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib.c (ffffffff81562bf0)
Location: drivers/gpio/gpiolib.c:4188
Inline: False
```
**Symbols:**

```
ffffffff81562bf0-ffffffff81562c53: gpiod_add_lookup_tables (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void gpiod_add_lookup_tables(struct gpiod_lookup_table **tables, size_t n);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib.c (ffffffff8157cb10)
Location: drivers/gpio/gpiolib.c:4188
Inline: False
```
**Symbols:**

```
ffffffff8157cb10-ffffffff8157cb73: gpiod_add_lookup_tables (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>4.15</code> and <code>4.18</code> ✅
</li>
<li>
No changes between <code>4.18</code> and <code>5.0</code> ✅
</li>
<li>
No changes between <code>5.0</code> and <code>5.3</code> ✅
</li>
<li>
No changes between <code>5.3</code> and <code>5.4</code> ✅
</li>
<li>
No changes between <code>5.4</code> and <code>5.8</code> ✅
</li>
<li>
No changes between <code>5.8</code> and <code>5.11</code> ✅
</li>
<li>
No changes between <code>5.11</code> and <code>5.13</code> ✅
</li>
<li>
No changes between <code>5.13</code> and <code>5.15</code> ✅
</li>
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
<b>Arch</b>
<ul>
<li>
No changes between <code>amd64</code> and <code>arm64</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>armhf</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>ppc64el</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>riscv64</code> ✅
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
No changes between <code>generic</code> and <code>aws</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>azure</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>gcp</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>lowlatency</code> ✅
</li>
</ul>
