# Function: <code>bitmap_print_to_buf</code>

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
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int bitmap_print_to_buf(bool list, char *buf, const long unsigned int *maskp, int nmaskbits, loff_t off, size_t count);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/bitmap.c (ffffffff81611c20)
Location: lib/bitmap.c:496
Inline: False
Direct callers:
  - lib/bitmap.c:bitmap_print_list_to_buf
  - lib/bitmap.c:bitmap_print_bitmask_to_buf
```
**Symbols:**

```
ffffffff81611c20-ffffffff81611ca7: bitmap_print_to_buf (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int bitmap_print_to_buf(bool list, char *buf, const long unsigned int *maskp, int nmaskbits, loff_t off, size_t count);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/bitmap.c (ffffffff816ddeb0)
Location: lib/bitmap.c:501
Inline: False
Direct callers:
  - lib/bitmap.c:bitmap_print_list_to_buf
  - lib/bitmap.c:bitmap_print_bitmask_to_buf
```
**Symbols:**

```
ffffffff816ddeb0-ffffffff816ddf46: bitmap_print_to_buf (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int bitmap_print_to_buf(bool list, char *buf, const long unsigned int *maskp, int nmaskbits, loff_t off, size_t count);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/bitmap.c (ffffffff817cde60)
Location: lib/bitmap.c:512
Inline: False
Direct callers:
  - lib/bitmap.c:bitmap_print_list_to_buf
  - lib/bitmap.c:bitmap_print_bitmask_to_buf
```
**Symbols:**

```
ffffffff817cde60-ffffffff817cdef6: bitmap_print_to_buf (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int bitmap_print_to_buf(bool list, char *buf, const long unsigned int *maskp, int nmaskbits, loff_t off, size_t count);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/bitmap.c (ffffffff8180c310)
Location: lib/bitmap.c:512
Inline: False
Direct callers:
  - lib/bitmap.c:bitmap_print_list_to_buf
  - lib/bitmap.c:bitmap_print_bitmask_to_buf
```
**Symbols:**

```
ffffffff8180c310-ffffffff8180c3a6: bitmap_print_to_buf (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int bitmap_print_to_buf(bool list, char *buf, const long unsigned int *maskp, int nmaskbits, loff_t off, size_t count);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/bitmap-str.c (ffffffff818614b0)
Location: lib/bitmap-str.c:79
Inline: False
Direct callers:
  - lib/bitmap-str.c:bitmap_print_list_to_buf
  - lib/bitmap-str.c:bitmap_print_bitmask_to_buf
```
**Symbols:**

```
ffffffff818614b0-ffffffff81861546: bitmap_print_to_buf (STB_LOCAL)
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
