# Function: <code>dax_zero_range</code>

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
int dax_zero_range(struct inode *inode, loff_t pos, loff_t len, bool *did_zero, const struct iomap_ops *ops);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/dax.c (ffffffff81467aa0)
Location: fs/dax.c:1098
Inline: False
Direct callers:
  - fs/dax.c:dax_truncate_page
  - fs/ext4/inode.c:ext4_block_zero_page_range
```
**Symbols:**

```
ffffffff81467aa0-ffffffff81467d8d: dax_zero_range (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int dax_zero_range(struct inode *inode, loff_t pos, loff_t len, bool *did_zero, const struct iomap_ops *ops);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/dax.c (ffffffff814f8a30)
Location: fs/dax.c:1370
Inline: False
Direct callers:
  - fs/dax.c:dax_truncate_page
  - fs/ext4/inode.c:ext4_block_zero_page_range
```
**Symbols:**

```
ffffffff814f8a30-ffffffff814f8ddf: dax_zero_range (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int dax_zero_range(struct inode *inode, loff_t pos, loff_t len, bool *did_zero, const struct iomap_ops *ops);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/dax.c (ffffffff8152fee0)
Location: fs/dax.c:1403
Inline: False
Direct callers:
  - fs/dax.c:dax_truncate_page
  - fs/ext4/inode.c:ext4_block_zero_page_range
```
**Symbols:**

```
ffffffff8152fee0-ffffffff81530133: dax_zero_range (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int dax_zero_range(struct inode *inode, loff_t pos, loff_t len, bool *did_zero, const struct iomap_ops *ops);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/dax.c (ffffffff81564dc0)
Location: fs/dax.c:1389
Inline: False
Direct callers:
  - fs/dax.c:dax_truncate_page
  - fs/ext4/inode.c:ext4_block_zero_page_range
```
**Symbols:**

```
ffffffff81564dc0-ffffffff81565013: dax_zero_range (STB_GLOBAL)
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
No changes between <code>5.19</code> and <code>6.2</code> ✅
</li>
<li>
No changes between <code>6.2</code> and <code>6.5</code> ✅
</li>
<li>
No changes between <code>6.5</code> and <code>6.8</code> ✅
</li>
</ul>
