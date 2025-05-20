# Function: <code>dax_iomap_copy_around</code>

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
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int dax_iomap_copy_around(loff_t pos, uint64_t length, size_t align_size, const struct iomap *srcmap, void *daddr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/dax.c (ffffffff814f7bd0)
Location: fs/dax.c:1106
Inline: False
Direct callers:
  - fs/dax.c:dax_fault_iter
  - fs/dax.c:dax_iomap_iter
  - fs/dax.c:dax_zero_range
```
**Symbols:**

```
ffffffff814f7bd0-ffffffff814f7de2: dax_iomap_copy_around (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int dax_iomap_copy_around(loff_t pos, uint64_t length, size_t align_size, const struct iomap *srcmap, void *daddr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/dax.c (ffffffff8152ea20)
Location: fs/dax.c:1133
Inline: False
Direct callers:
  - fs/dax.c:dax_fault_iter
  - fs/dax.c:dax_iomap_iter
  - fs/dax.c:dax_memzero
```
**Symbols:**

```
ffffffff8152ea20-ffffffff8152ec43: dax_iomap_copy_around (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int dax_iomap_copy_around(loff_t pos, uint64_t length, size_t align_size, const struct iomap *srcmap, void *daddr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/dax.c (ffffffff81563900)
Location: fs/dax.c:1119
Inline: False
Direct callers:
  - fs/dax.c:dax_fault_iter
  - fs/dax.c:dax_iomap_iter
  - fs/dax.c:dax_memzero
```
**Symbols:**

```
ffffffff81563900-ffffffff81563b23: dax_iomap_copy_around (STB_LOCAL)
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
No changes between <code>6.2</code> and <code>6.5</code> ✅
</li>
<li>
No changes between <code>6.5</code> and <code>6.8</code> ✅
</li>
</ul>
