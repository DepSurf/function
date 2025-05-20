# Function: <code>ext4_es_insert_extent</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int ext4_es_insert_extent(struct inode *inode, ext4_lblk_t lblk, ext4_lblk_t len, ext4_fsblk_t pblk, unsigned int status);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/extents_status.c (ffffffff812dbce0)
Location: fs/ext4/extents_status.c:690
Inline: False
Direct callers:
  - fs/ext4/inode.c:ext4_da_get_block_prep
  - fs/ext4/inode.c:ext4_da_get_block_prep
  - fs/ext4/inode.c:ext4_map_blocks
  - fs/ext4/inode.c:ext4_map_blocks
  - fs/ext4/extents.c:ext4_zeroout_es
  - fs/ext4/extents.c:ext4_ext_put_gap_in_cache
```
**Symbols:**

```
ffffffff812dbce0-ffffffff812dbe97: ext4_es_insert_extent (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int ext4_es_insert_extent(struct inode *inode, ext4_lblk_t lblk, ext4_lblk_t len, ext4_fsblk_t pblk, unsigned int status);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/extents_status.c (ffffffff8130b620)
Location: fs/ext4/extents_status.c:690
Inline: False
Direct callers:
  - fs/ext4/inode.c:ext4_da_get_block_prep
  - fs/ext4/inode.c:ext4_da_get_block_prep
  - fs/ext4/inode.c:ext4_map_blocks
  - fs/ext4/inode.c:ext4_map_blocks
  - fs/ext4/extents.c:ext4_zeroout_es
  - fs/ext4/extents.c:ext4_ext_put_gap_in_cache
```
**Symbols:**

```
ffffffff8130b620-ffffffff8130b7c9: ext4_es_insert_extent (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int ext4_es_insert_extent(struct inode *inode, ext4_lblk_t lblk, ext4_lblk_t len, ext4_fsblk_t pblk, unsigned int status);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/extents_status.c (ffffffff81321620)
Location: fs/ext4/extents_status.c:690
Inline: False
Direct callers:
  - fs/ext4/inode.c:ext4_da_get_block_prep
  - fs/ext4/inode.c:ext4_da_get_block_prep
  - fs/ext4/inode.c:ext4_map_blocks
  - fs/ext4/inode.c:ext4_map_blocks
  - fs/ext4/extents.c:ext4_zeroout_es
  - fs/ext4/extents.c:ext4_ext_put_gap_in_cache
```
**Symbols:**

```
ffffffff81321620-ffffffff813217c9: ext4_es_insert_extent (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int ext4_es_insert_extent(struct inode *inode, ext4_lblk_t lblk, ext4_lblk_t len, ext4_fsblk_t pblk, unsigned int status);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/extents_status.c (ffffffff812f05a0)
Location: fs/ext4/extents_status.c:690
Inline: False
Direct callers:
  - fs/ext4/extents.c:ext4_zeroout_es
  - fs/ext4/extents.c:ext4_ext_put_gap_in_cache
  - fs/ext4/inode.c:ext4_da_get_block_prep
  - fs/ext4/inode.c:ext4_da_get_block_prep
  - fs/ext4/inode.c:ext4_map_blocks
  - fs/ext4/inode.c:ext4_map_blocks
```
**Symbols:**

```
ffffffff812f05a0-ffffffff812f073a: ext4_es_insert_extent (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int ext4_es_insert_extent(struct inode *inode, ext4_lblk_t lblk, ext4_lblk_t len, ext4_fsblk_t pblk, unsigned int status);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/extents_status.c (ffffffff813150c0)
Location: fs/ext4/extents_status.c:691
Inline: False
Direct callers:
  - fs/ext4/extents.c:ext4_zeroout_es
  - fs/ext4/extents.c:ext4_ext_put_gap_in_cache
  - fs/ext4/inode.c:ext4_da_get_block_prep
  - fs/ext4/inode.c:ext4_da_get_block_prep
  - fs/ext4/inode.c:ext4_map_blocks
  - fs/ext4/inode.c:ext4_map_blocks
```
**Symbols:**

```
ffffffff813150c0-ffffffff8131525d: ext4_es_insert_extent (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int ext4_es_insert_extent(struct inode *inode, ext4_lblk_t lblk, ext4_lblk_t len, ext4_fsblk_t pblk, unsigned int status);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/extents_status.c (ffffffff81342ed0)
Location: fs/ext4/extents_status.c:690
Inline: False
Direct callers:
  - fs/ext4/extents.c:ext4_zeroout_es
  - fs/ext4/extents.c:ext4_ext_put_gap_in_cache
  - fs/ext4/inode.c:ext4_da_get_block_prep
  - fs/ext4/inode.c:ext4_da_get_block_prep
  - fs/ext4/inode.c:ext4_map_blocks
  - fs/ext4/inode.c:ext4_map_blocks
```
**Symbols:**

```
ffffffff81342ed0-ffffffff8134306d: ext4_es_insert_extent (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int ext4_es_insert_extent(struct inode *inode, ext4_lblk_t lblk, ext4_lblk_t len, ext4_fsblk_t pblk, unsigned int status);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/extents_status.c (ffffffff8135a9c0)
Location: fs/ext4/extents_status.c:806
Inline: False
Direct callers:
  - fs/ext4/extents.c:ext4_zeroout_es
  - fs/ext4/extents.c:ext4_ext_put_gap_in_cache
  - fs/ext4/inode.c:ext4_da_get_block_prep
  - fs/ext4/inode.c:ext4_map_blocks
  - fs/ext4/inode.c:ext4_map_blocks
```
**Symbols:**

```
ffffffff8135a9c0-ffffffff8135ac85: ext4_es_insert_extent (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int ext4_es_insert_extent(struct inode *inode, ext4_lblk_t lblk, ext4_lblk_t len, ext4_fsblk_t pblk, unsigned int status);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/extents_status.c (ffffffff81383a00)
Location: fs/ext4/extents_status.c:806
Inline: False
Direct callers:
  - fs/ext4/extents.c:ext4_zeroout_es
  - fs/ext4/extents.c:ext4_ext_put_gap_in_cache
  - fs/ext4/inode.c:ext4_map_blocks
  - fs/ext4/inode.c:ext4_map_blocks
```
**Symbols:**

```
ffffffff81383a00-ffffffff81383cbb: ext4_es_insert_extent (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int ext4_es_insert_extent(struct inode *inode, ext4_lblk_t lblk, ext4_lblk_t len, ext4_fsblk_t pblk, unsigned int status);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/extents_status.c (ffffffff8139c4a0)
Location: fs/ext4/extents_status.c:806
Inline: False
Direct callers:
  - fs/ext4/extents.c:ext4_zeroout_es
  - fs/ext4/extents.c:ext4_ext_put_gap_in_cache
  - fs/ext4/inode.c:ext4_map_blocks
  - fs/ext4/inode.c:ext4_map_blocks
```
**Symbols:**

```
ffffffff8139c4a0-ffffffff8139c755: ext4_es_insert_extent (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int ext4_es_insert_extent(struct inode *inode, ext4_lblk_t lblk, ext4_lblk_t len, ext4_fsblk_t pblk, unsigned int status);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/extents_status.c (ffffffff813e7ca0)
Location: fs/ext4/extents_status.c:806
Inline: False
Direct callers:
  - fs/ext4/extents.c:ext4_ext_convert_to_initialized
  - fs/ext4/extents.c:ext4_ext_convert_to_initialized
  - fs/ext4/extents.c:ext4_split_extent_at
  - fs/ext4/extents.c:ext4_ext_put_gap_in_cache
  - fs/ext4/inode.c:ext4_map_blocks
  - fs/ext4/inode.c:ext4_map_blocks
```
**Symbols:**

```
ffffffff813e7ca0-ffffffff813e7e89: ext4_es_insert_extent (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int ext4_es_insert_extent(struct inode *inode, ext4_lblk_t lblk, ext4_lblk_t len, ext4_fsblk_t pblk, unsigned int status);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/extents_status.c (ffffffff813f9f60)
Location: fs/ext4/extents_status.c:815
Inline: False
Direct callers:
  - fs/ext4/extents.c:ext4_ext_map_blocks
  - fs/ext4/extents.c:ext4_ext_convert_to_initialized
  - fs/ext4/extents.c:ext4_ext_convert_to_initialized
  - fs/ext4/extents.c:ext4_split_extent_at
  - fs/ext4/inode.c:ext4_map_blocks
  - fs/ext4/inode.c:ext4_map_blocks
```
**Symbols:**

```
ffffffff813f9f60-ffffffff813fa144: ext4_es_insert_extent (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int ext4_es_insert_extent(struct inode *inode, ext4_lblk_t lblk, ext4_lblk_t len, ext4_fsblk_t pblk, unsigned int status);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/extents_status.c (ffffffff81400320)
Location: fs/ext4/extents_status.c:815
Inline: False
Direct callers:
  - fs/ext4/extents.c:ext4_ext_map_blocks
  - fs/ext4/extents.c:ext4_ext_convert_to_initialized
  - fs/ext4/extents.c:ext4_ext_convert_to_initialized
  - fs/ext4/extents.c:ext4_split_extent_at
  - fs/ext4/inode.c:ext4_map_blocks
  - fs/ext4/inode.c:ext4_map_blocks
```
**Symbols:**

```
ffffffff81400320-ffffffff81400508: ext4_es_insert_extent (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int ext4_es_insert_extent(struct inode *inode, ext4_lblk_t lblk, ext4_lblk_t len, ext4_fsblk_t pblk, unsigned int status);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/extents_status.c (ffffffff81452940)
Location: fs/ext4/extents_status.c:815
Inline: False
Direct callers:
  - fs/ext4/extents.c:ext4_ext_map_blocks
  - fs/ext4/extents.c:ext4_ext_convert_to_initialized
  - fs/ext4/extents.c:ext4_ext_convert_to_initialized
  - fs/ext4/extents.c:ext4_split_extent_at
  - fs/ext4/inode.c:ext4_map_blocks
  - fs/ext4/inode.c:ext4_map_blocks
```
**Symbols:**

```
ffffffff81452940-ffffffff81452b28: ext4_es_insert_extent (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int ext4_es_insert_extent(struct inode *inode, ext4_lblk_t lblk, ext4_lblk_t len, ext4_fsblk_t pblk, unsigned int status);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/extents_status.c (ffffffff814cfd20)
Location: fs/ext4/extents_status.c:815
Inline: False
Direct callers:
  - fs/ext4/extents.c:ext4_ext_map_blocks
  - fs/ext4/extents.c:ext4_ext_convert_to_initialized
  - fs/ext4/extents.c:ext4_ext_convert_to_initialized
  - fs/ext4/extents.c:ext4_split_extent_at
  - fs/ext4/inode.c:ext4_map_blocks
  - fs/ext4/inode.c:ext4_map_blocks
```
**Symbols:**

```
ffffffff814cfd20-ffffffff814cff62: ext4_es_insert_extent (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int ext4_es_insert_extent(struct inode *inode, ext4_lblk_t lblk, ext4_lblk_t len, ext4_fsblk_t pblk, unsigned int status);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/extents_status.c (ffffffff81568650)
Location: fs/ext4/extents_status.c:812
Inline: False
Direct callers:
  - fs/ext4/extents.c:ext4_ext_map_blocks
  - fs/ext4/extents.c:ext4_ext_convert_to_initialized
  - fs/ext4/extents.c:ext4_ext_convert_to_initialized
  - fs/ext4/extents.c:ext4_split_extent_at
  - fs/ext4/inode.c:ext4_map_blocks
  - fs/ext4/inode.c:ext4_map_blocks
```
**Symbols:**

```
ffffffff81568650-ffffffff81568892: ext4_es_insert_extent (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void ext4_es_insert_extent(struct inode *inode, ext4_lblk_t lblk, ext4_lblk_t len, ext4_fsblk_t pblk, unsigned int status);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/extents_status.c (ffffffff815a01a0)
Location: fs/ext4/extents_status.c:833
Inline: False
Direct callers:
  - fs/ext4/extents.c:ext4_ext_map_blocks
  - fs/ext4/extents.c:ext4_ext_convert_to_initialized
  - fs/ext4/extents.c:ext4_ext_convert_to_initialized
  - fs/ext4/extents.c:ext4_split_extent_at
  - fs/ext4/inode.c:ext4_map_blocks
  - fs/ext4/inode.c:ext4_map_blocks
```
**Symbols:**

```
ffffffff815a01a0-ffffffff815a04e3: ext4_es_insert_extent (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void ext4_es_insert_extent(struct inode *inode, ext4_lblk_t lblk, ext4_lblk_t len, ext4_fsblk_t pblk, unsigned int status);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/extents_status.c (ffffffff815d8e50)
Location: fs/ext4/extents_status.c:847
Inline: False
Direct callers:
  - fs/ext4/extents.c:ext4_ext_determine_insert_hole
  - fs/ext4/extents.c:ext4_ext_convert_to_initialized
  - fs/ext4/extents.c:ext4_ext_convert_to_initialized
  - fs/ext4/extents.c:ext4_split_extent_at
  - fs/ext4/inode.c:ext4_punch_hole
  - fs/ext4/inode.c:ext4_map_blocks
  - fs/ext4/inode.c:ext4_map_blocks
```
**Symbols:**

```
ffffffff815d8e50-ffffffff815d91f7: ext4_es_insert_extent (STB_GLOBAL)
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
int ext4_es_insert_extent(struct inode *inode, ext4_lblk_t lblk, ext4_lblk_t len, ext4_fsblk_t pblk, unsigned int status);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/extents_status.c (ffff80001046f2a8)
Location: fs/ext4/extents_status.c:806
Inline: False
Direct callers:
  - fs/ext4/extents.c:ext4_zeroout_es
  - fs/ext4/extents.c:ext4_ext_put_gap_in_cache
  - fs/ext4/inode.c:ext4_map_blocks
  - fs/ext4/inode.c:ext4_map_blocks
```
**Symbols:**

```
ffff80001046f2a8-ffff80001046f610: ext4_es_insert_extent (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int ext4_es_insert_extent(struct inode *inode, ext4_lblk_t lblk, ext4_lblk_t len, ext4_fsblk_t pblk, unsigned int status);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/extents_status.c (c063087c)
Location: fs/ext4/extents_status.c:806
Inline: False
Direct callers:
  - fs/ext4/extents.c:ext4_ext_map_blocks
  - fs/ext4/extents.c:ext4_zeroout_es
  - fs/ext4/inode.c:ext4_map_blocks
  - fs/ext4/inode.c:ext4_map_blocks
```
**Symbols:**

```
c063087c-c0630ba4: ext4_es_insert_extent (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int ext4_es_insert_extent(struct inode *inode, ext4_lblk_t lblk, ext4_lblk_t len, ext4_fsblk_t pblk, unsigned int status);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/extents_status.c (c00000000058f690)
Location: fs/ext4/extents_status.c:806
Inline: False
Direct callers:
  - fs/ext4/extents.c:ext4_zeroout_es
  - fs/ext4/extents.c:ext4_ext_put_gap_in_cache
  - fs/ext4/inode.c:ext4_map_blocks
  - fs/ext4/inode.c:ext4_map_blocks
```
**Symbols:**

```
c00000000058f690-c00000000058fa68: ext4_es_insert_extent (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int ext4_es_insert_extent(struct inode *inode, ext4_lblk_t lblk, ext4_lblk_t len, ext4_fsblk_t pblk, unsigned int status);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/extents_status.c (ffffffe0002fbf20)
Location: fs/ext4/extents_status.c:806
Inline: False
Direct callers:
  - fs/ext4/extents.c:ext4_zeroout_es
  - fs/ext4/extents.c:ext4_ext_put_gap_in_cache
  - fs/ext4/inode.c:ext4_map_blocks
  - fs/ext4/inode.c:ext4_map_blocks
```
**Symbols:**

```
ffffffe0002fbf20-ffffffe0002fc1a6: ext4_es_insert_extent (STB_GLOBAL)
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
int ext4_es_insert_extent(struct inode *inode, ext4_lblk_t lblk, ext4_lblk_t len, ext4_fsblk_t pblk, unsigned int status);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/extents_status.c (ffffffff81394a80)
Location: fs/ext4/extents_status.c:806
Inline: False
Direct callers:
  - fs/ext4/extents.c:ext4_zeroout_es
  - fs/ext4/extents.c:ext4_ext_put_gap_in_cache
  - fs/ext4/inode.c:ext4_map_blocks
  - fs/ext4/inode.c:ext4_map_blocks
```
**Symbols:**

```
ffffffff81394a80-ffffffff81394d35: ext4_es_insert_extent (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int ext4_es_insert_extent(struct inode *inode, ext4_lblk_t lblk, ext4_lblk_t len, ext4_fsblk_t pblk, unsigned int status);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/extents_status.c (ffffffff81385510)
Location: fs/ext4/extents_status.c:806
Inline: False
Direct callers:
  - fs/ext4/extents.c:ext4_zeroout_es
  - fs/ext4/extents.c:ext4_ext_put_gap_in_cache
  - fs/ext4/inode.c:ext4_map_blocks
  - fs/ext4/inode.c:ext4_map_blocks
```
**Symbols:**

```
ffffffff81385510-ffffffff813857c5: ext4_es_insert_extent (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int ext4_es_insert_extent(struct inode *inode, ext4_lblk_t lblk, ext4_lblk_t len, ext4_fsblk_t pblk, unsigned int status);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/extents_status.c (ffffffff813923e0)
Location: fs/ext4/extents_status.c:806
Inline: False
Direct callers:
  - fs/ext4/extents.c:ext4_zeroout_es
  - fs/ext4/extents.c:ext4_ext_put_gap_in_cache
  - fs/ext4/inode.c:ext4_map_blocks
  - fs/ext4/inode.c:ext4_map_blocks
```
**Symbols:**

```
ffffffff813923e0-ffffffff81392695: ext4_es_insert_extent (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int ext4_es_insert_extent(struct inode *inode, ext4_lblk_t lblk, ext4_lblk_t len, ext4_fsblk_t pblk, unsigned int status);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/extents_status.c (ffffffff813a6300)
Location: fs/ext4/extents_status.c:806
Inline: False
Direct callers:
  - fs/ext4/extents.c:ext4_zeroout_es
  - fs/ext4/extents.c:ext4_ext_put_gap_in_cache
  - fs/ext4/inode.c:ext4_map_blocks
  - fs/ext4/inode.c:ext4_map_blocks
```
**Symbols:**

```
ffffffff813a6300-ffffffff813a65db: ext4_es_insert_extent (STB_GLOBAL)
```
</details>
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
<details>
<summary>Changed between <code>6.2</code> and <code>6.5</code> ⚠️</summary>
<ul>
<li>
<b>Return type changed. </b>
<code>int</code> ➡️ <code>void</code>
</li>
</ul>
</details>
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
