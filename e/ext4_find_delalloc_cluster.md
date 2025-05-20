# Function: <code>ext4_find_delalloc_cluster</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int ext4_find_delalloc_cluster(struct inode *inode, ext4_lblk_t lblk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/extents.c (ffffffff812c8770)
Location: fs/ext4/extents.c:3850
Inline: False
Direct callers:
  - fs/ext4/inode.c:ext4_da_get_block_prep
```
**Symbols:**

```
ffffffff812c8770-ffffffff812c8798: ext4_find_delalloc_cluster (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int ext4_find_delalloc_cluster(struct inode *inode, ext4_lblk_t lblk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/extents.c (ffffffff812f7240)
Location: fs/ext4/extents.c:3864
Inline: False
Direct callers:
  - fs/ext4/inode.c:ext4_da_get_block_prep
```
**Symbols:**

```
ffffffff812f7240-ffffffff812f7268: ext4_find_delalloc_cluster (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int ext4_find_delalloc_cluster(struct inode *inode, ext4_lblk_t lblk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/extents.c (ffffffff8130d250)
Location: fs/ext4/extents.c:3856
Inline: False
Direct callers:
  - fs/ext4/inode.c:ext4_da_get_block_prep
```
**Symbols:**

```
ffffffff8130d250-ffffffff8130d278: ext4_find_delalloc_cluster (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int ext4_find_delalloc_cluster(struct inode *inode, ext4_lblk_t lblk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/extents.c (ffffffff812ec5c0)
Location: fs/ext4/extents.c:3851
Inline: False
Direct callers:
  - fs/ext4/inode.c:ext4_da_get_block_prep
```
**Symbols:**

```
ffffffff812ec5c0-ffffffff812ec5e8: ext4_find_delalloc_cluster (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int ext4_find_delalloc_cluster(struct inode *inode, ext4_lblk_t lblk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/extents.c (ffffffff81311080)
Location: fs/ext4/extents.c:3851
Inline: False
Direct callers:
  - fs/ext4/inode.c:ext4_da_get_block_prep
```
**Symbols:**

```
ffffffff81311080-ffffffff813110a8: ext4_find_delalloc_cluster (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int ext4_find_delalloc_cluster(struct inode *inode, ext4_lblk_t lblk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/extents.c (ffffffff8133ef20)
Location: fs/ext4/extents.c:3845
Inline: False
Direct callers:
  - fs/ext4/inode.c:ext4_da_get_block_prep
```
**Symbols:**

```
ffffffff8133ef20-ffffffff8133ef48: ext4_find_delalloc_cluster (STB_GLOBAL)
```
</details>
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
No changes between <code>4.4</code> and <code>4.8</code> ✅
</li>
<li>
No changes between <code>4.8</code> and <code>4.10</code> ✅
</li>
<li>
No changes between <code>4.10</code> and <code>4.13</code> ✅
</li>
<li>
No changes between <code>4.13</code> and <code>4.15</code> ✅
</li>
<li>
No changes between <code>4.15</code> and <code>4.18</code> ✅
</li>
</ul>
