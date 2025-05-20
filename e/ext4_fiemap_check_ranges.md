# Function: <code>ext4_fiemap_check_ranges</code>

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
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int ext4_fiemap_check_ranges(struct inode *inode, u64 start, u64 *len);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/extents.c (ffffffff813dd850)
Location: fs/ext4/extents.c:4861
Inline: False
Direct callers:
  - fs/ext4/extents.c:ext4_get_es_cache
  - fs/ext4/extents.c:ext4_fiemap
```
**Symbols:**

```
ffffffff813dd850-ffffffff813dd8c0: ext4_fiemap_check_ranges (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int ext4_fiemap_check_ranges(struct inode *inode, u64 start, u64 *len);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/extents.c (ffffffff813ef140)
Location: fs/ext4/extents.c:4870
Inline: False
Direct callers:
  - fs/ext4/extents.c:ext4_get_es_cache
  - fs/ext4/extents.c:ext4_fiemap
```
**Symbols:**

```
ffffffff813ef140-ffffffff813ef1b0: ext4_fiemap_check_ranges (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int ext4_fiemap_check_ranges(struct inode *inode, u64 start, u64 *len);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/extents.c (ffffffff813f5600)
Location: fs/ext4/extents.c:4876
Inline: False
Direct callers:
  - fs/ext4/extents.c:ext4_get_es_cache
  - fs/ext4/extents.c:ext4_fiemap
```
**Symbols:**

```
ffffffff813f5600-ffffffff813f5670: ext4_fiemap_check_ranges (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int ext4_fiemap_check_ranges(struct inode *inode, u64 start, u64 *len);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/extents.c (ffffffff81447d40)
Location: fs/ext4/extents.c:4914
Inline: False
Direct callers:
  - fs/ext4/extents.c:ext4_get_es_cache
  - fs/ext4/extents.c:ext4_fiemap
```
**Symbols:**

```
ffffffff81447d40-ffffffff81447db0: ext4_fiemap_check_ranges (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/ext4/extents.c (ffffffff814cc5b0)
Location: fs/ext4/extents.c:4917
Inline: True
Inline callers:
  - fs/ext4/extents.c:ext4_get_es_cache
  - fs/ext4/extents.c:ext4_fiemap
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/ext4/extents.c (ffffffff81564cc0)
Location: fs/ext4/extents.c:4921
Inline: True
Inline callers:
  - fs/ext4/extents.c:ext4_get_es_cache
  - fs/ext4/extents.c:ext4_fiemap
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/ext4/extents.c (ffffffff8159c960)
Location: fs/ext4/extents.c:4920
Inline: True
Inline callers:
  - fs/ext4/extents.c:ext4_get_es_cache
  - fs/ext4/extents.c:ext4_fiemap
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/ext4/extents.c (ffffffff815d5610)
Location: fs/ext4/extents.c:4955
Inline: True
Inline callers:
  - fs/ext4/extents.c:ext4_get_es_cache
  - fs/ext4/extents.c:ext4_fiemap
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
No changes between <code>5.8</code> and <code>5.11</code> ✅
</li>
<li>
No changes between <code>5.11</code> and <code>5.13</code> ✅
</li>
<li>
No changes between <code>5.13</code> and <code>5.15</code> ✅
</li>
</ul>
