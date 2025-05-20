# Function: <code>dax_dedupe_file_range_compare</code>

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
int dax_dedupe_file_range_compare(struct inode *src, loff_t srcoff, struct inode *dst, loff_t dstoff, loff_t len, bool *same, const struct iomap_ops *ops);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/dax.c (ffffffff814fb5f0)
Location: fs/dax.c:2005
Inline: False
Direct callers:
  - fs/remap_range.c:__generic_remap_file_range_prep
```
**Symbols:**

```
ffffffff814fb5f0-ffffffff814fb853: dax_dedupe_file_range_compare (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int dax_dedupe_file_range_compare(struct inode *src, loff_t srcoff, struct inode *dst, loff_t dstoff, loff_t len, bool *same, const struct iomap_ops *ops);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/dax.c (ffffffff81532a40)
Location: fs/dax.c:2047
Inline: False
Direct callers:
  - fs/remap_range.c:__generic_remap_file_range_prep
```
**Symbols:**

```
ffffffff81532a40-ffffffff81532b7a: dax_dedupe_file_range_compare (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int dax_dedupe_file_range_compare(struct inode *src, loff_t srcoff, struct inode *dst, loff_t dstoff, loff_t len, bool *same, const struct iomap_ops *ops);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/dax.c (ffffffff81567930)
Location: fs/dax.c:2030
Inline: False
Direct callers:
  - fs/remap_range.c:__generic_remap_file_range_prep
```
**Symbols:**

```
ffffffff81567930-ffffffff81567a6a: dax_dedupe_file_range_compare (STB_GLOBAL)
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
