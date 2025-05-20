# Function: <code>bitmap_print_bitmask_to_buf</code>

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
int bitmap_print_bitmask_to_buf(char *buf, const long unsigned int *maskp, int nmaskbits, loff_t off, size_t count);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/bitmap.c (ffffffff81611cb0)
Location: lib/bitmap.c:591
Inline: False
Direct callers:
  - drivers/base/topology.c:die_cpus_read
  - drivers/base/node.c:cpumap_read
```
**Symbols:**

```
ffffffff81611cb0-ffffffff81611cd1: bitmap_print_bitmask_to_buf (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int bitmap_print_bitmask_to_buf(char *buf, const long unsigned int *maskp, int nmaskbits, loff_t off, size_t count);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/bitmap.c (ffffffff816ddf50)
Location: lib/bitmap.c:602
Inline: False
Direct callers:
  - drivers/base/topology.c:die_cpus_read
  - drivers/base/topology.c:cluster_cpus_read
  - drivers/base/node.c:cpumap_read
```
**Symbols:**

```
ffffffff816ddf50-ffffffff816ddf7d: bitmap_print_bitmask_to_buf (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int bitmap_print_bitmask_to_buf(char *buf, const long unsigned int *maskp, int nmaskbits, loff_t off, size_t count);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/bitmap.c (ffffffff817cdf10)
Location: lib/bitmap.c:613
Inline: False
Direct callers:
  - drivers/base/topology.c:die_cpus_read
  - drivers/base/topology.c:cluster_cpus_read
  - drivers/base/node.c:cpumap_read
```
**Symbols:**

```
ffffffff817cdf10-ffffffff817cdf3d: bitmap_print_bitmask_to_buf (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int bitmap_print_bitmask_to_buf(char *buf, const long unsigned int *maskp, int nmaskbits, loff_t off, size_t count);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/bitmap.c (ffffffff8180c3c0)
Location: lib/bitmap.c:613
Inline: False
Direct callers:
  - drivers/base/topology.c:die_cpus_read
  - drivers/base/topology.c:cluster_cpus_read
  - drivers/base/node.c:cpumap_read
```
**Symbols:**

```
ffffffff8180c3c0-ffffffff8180c3ed: bitmap_print_bitmask_to_buf (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int bitmap_print_bitmask_to_buf(char *buf, const long unsigned int *maskp, int nmaskbits, loff_t off, size_t count);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/bitmap-str.c (ffffffff81861560)
Location: lib/bitmap-str.c:180
Inline: False
Direct callers:
  - drivers/base/topology.c:die_cpus_read
  - drivers/base/topology.c:cluster_cpus_read
  - drivers/base/node.c:cpumap_read
```
**Symbols:**

```
ffffffff81861560-ffffffff8186158d: bitmap_print_bitmask_to_buf (STB_GLOBAL)
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
