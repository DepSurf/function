# Function: <code>ext4_ext_search_right</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int ext4_ext_search_right(struct inode *inode, struct ext4_ext_path *path, ext4_lblk_t *logical, ext4_fsblk_t *phys, struct ext4_extent **ret_ex);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/extents.c (ffffffff812c2e10)
Location: fs/ext4/extents.c:1484
Inline: False
Direct callers:
  - fs/ext4/extents.c:ext4_ext_remove_space
  - fs/ext4/extents.c:ext4_ext_map_blocks
```
**Symbols:**

```
ffffffff812c2e10-ffffffff812c30f8: ext4_ext_search_right (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int ext4_ext_search_right(struct inode *inode, struct ext4_ext_path *path, ext4_lblk_t *logical, ext4_fsblk_t *phys, struct ext4_extent **ret_ex);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/extents.c (ffffffff812f2810)
Location: fs/ext4/extents.c:1490
Inline: False
Direct callers:
  - fs/ext4/extents.c:ext4_ext_map_blocks
  - fs/ext4/extents.c:ext4_ext_remove_space
```
**Symbols:**

```
ffffffff812f2810-ffffffff812f2adc: ext4_ext_search_right (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int ext4_ext_search_right(struct inode *inode, struct ext4_ext_path *path, ext4_lblk_t *logical, ext4_fsblk_t *phys, struct ext4_extent **ret_ex);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/extents.c (ffffffff813087e0)
Location: fs/ext4/extents.c:1490
Inline: False
Direct callers:
  - fs/ext4/extents.c:ext4_ext_map_blocks
  - fs/ext4/extents.c:ext4_ext_remove_space
```
**Symbols:**

```
ffffffff813087e0-ffffffff81308aac: ext4_ext_search_right (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int ext4_ext_search_right(struct inode *inode, struct ext4_ext_path *path, ext4_lblk_t *logical, ext4_fsblk_t *phys, struct ext4_extent **ret_ex);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/extents.c (ffffffff812e6f70)
Location: fs/ext4/extents.c:1490
Inline: False
Direct callers:
  - fs/ext4/extents.c:ext4_ext_map_blocks
  - fs/ext4/extents.c:ext4_ext_remove_space
```
**Symbols:**

```
ffffffff812e6f70-ffffffff812e725c: ext4_ext_search_right (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int ext4_ext_search_right(struct inode *inode, struct ext4_ext_path *path, ext4_lblk_t *logical, ext4_fsblk_t *phys, struct ext4_extent **ret_ex);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/extents.c (ffffffff8130b970)
Location: fs/ext4/extents.c:1490
Inline: False
Direct callers:
  - fs/ext4/extents.c:ext4_ext_map_blocks
  - fs/ext4/extents.c:ext4_ext_remove_space
```
**Symbols:**

```
ffffffff8130b970-ffffffff8130bc5c: ext4_ext_search_right (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int ext4_ext_search_right(struct inode *inode, struct ext4_ext_path *path, ext4_lblk_t *logical, ext4_fsblk_t *phys, struct ext4_extent **ret_ex);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/extents.c (ffffffff81339af0)
Location: fs/ext4/extents.c:1484
Inline: False
Direct callers:
  - fs/ext4/extents.c:ext4_ext_map_blocks
  - fs/ext4/extents.c:ext4_ext_remove_space
```
**Symbols:**

```
ffffffff81339af0-ffffffff81339de0: ext4_ext_search_right (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int ext4_ext_search_right(struct inode *inode, struct ext4_ext_path *path, ext4_lblk_t *logical, ext4_fsblk_t *phys, struct ext4_extent **ret_ex);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/extents.c (ffffffff81350c90)
Location: fs/ext4/extents.c:1484
Inline: False
Direct callers:
  - fs/ext4/extents.c:ext4_ext_map_blocks
  - fs/ext4/extents.c:ext4_ext_remove_space
```
**Symbols:**

```
ffffffff81350c90-ffffffff81350f80: ext4_ext_search_right (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int ext4_ext_search_right(struct inode *inode, struct ext4_ext_path *path, ext4_lblk_t *logical, ext4_fsblk_t *phys, struct ext4_extent **ret_ex);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/extents.c (ffffffff81379990)
Location: fs/ext4/extents.c:1501
Inline: False
Direct callers:
  - fs/ext4/extents.c:ext4_ext_map_blocks
  - fs/ext4/extents.c:ext4_ext_remove_space
```
**Symbols:**

```
ffffffff81379990-ffffffff81379c71: ext4_ext_search_right (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int ext4_ext_search_right(struct inode *inode, struct ext4_ext_path *path, ext4_lblk_t *logical, ext4_fsblk_t *phys, struct ext4_extent **ret_ex);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/extents.c (ffffffff81391eb0)
Location: fs/ext4/extents.c:1501
Inline: False
Direct callers:
  - fs/ext4/extents.c:ext4_ext_map_blocks
  - fs/ext4/extents.c:ext4_ext_remove_space
```
**Symbols:**

```
ffffffff81391eb0-ffffffff81392191: ext4_ext_search_right (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int ext4_ext_search_right(struct inode *inode, struct ext4_ext_path *path, ext4_lblk_t *logical, ext4_fsblk_t *phys, struct ext4_extent **ret_ex);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/extents.c (ffffffff813de630)
Location: fs/ext4/extents.c:1482
Inline: False
Direct callers:
  - fs/ext4/extents.c:ext4_ext_map_blocks
  - fs/ext4/extents.c:ext4_ext_remove_space
```
**Symbols:**

```
ffffffff813de630-ffffffff813de8f3: ext4_ext_search_right (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int ext4_ext_search_right(struct inode *inode, struct ext4_ext_path *path, ext4_lblk_t *logical, ext4_fsblk_t *phys, struct ext4_extent *ret_ex);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/extents.c (ffffffff813efec0)
Location: fs/ext4/extents.c:1480
Inline: False
Direct callers:
  - fs/ext4/extents.c:ext4_ext_map_blocks
  - fs/ext4/extents.c:ext4_ext_remove_space
```
**Symbols:**

```
ffffffff813efec0-ffffffff813f01ab: ext4_ext_search_right (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int ext4_ext_search_right(struct inode *inode, struct ext4_ext_path *path, ext4_lblk_t *logical, ext4_fsblk_t *phys, struct ext4_extent *ret_ex);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/extents.c (ffffffff813f6150)
Location: fs/ext4/extents.c:1483
Inline: False
Direct callers:
  - fs/ext4/extents.c:ext4_ext_map_blocks
  - fs/ext4/extents.c:ext4_ext_remove_space
```
**Symbols:**

```
ffffffff813f6150-ffffffff813f6437: ext4_ext_search_right (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int ext4_ext_search_right(struct inode *inode, struct ext4_ext_path *path, ext4_lblk_t *logical, ext4_fsblk_t *phys, struct ext4_extent *ret_ex);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/extents.c (ffffffff814489f0)
Location: fs/ext4/extents.c:1525
Inline: False
Direct callers:
  - fs/ext4/extents.c:ext4_ext_map_blocks
  - fs/ext4/extents.c:ext4_ext_remove_space
```
**Symbols:**

```
ffffffff814489f0-ffffffff81448cc2: ext4_ext_search_right (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int ext4_ext_search_right(struct inode *inode, struct ext4_ext_path *path, ext4_lblk_t *logical, ext4_fsblk_t *phys, struct ext4_extent *ret_ex);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/extents.c (ffffffff814c57f0)
Location: fs/ext4/extents.c:1526
Inline: False
Direct callers:
  - fs/ext4/extents.c:ext4_ext_map_blocks
  - fs/ext4/extents.c:ext4_ext_remove_space
```
**Symbols:**

```
ffffffff814c57f0-ffffffff814c5b33: ext4_ext_search_right (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int ext4_ext_search_right(struct inode *inode, struct ext4_ext_path *path, ext4_lblk_t *logical, ext4_fsblk_t *phys, struct ext4_extent *ret_ex);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/extents.c (ffffffff8155dd70)
Location: fs/ext4/extents.c:1534
Inline: False
Direct callers:
  - fs/ext4/extents.c:ext4_ext_map_blocks
  - fs/ext4/extents.c:ext4_ext_remove_space
```
**Symbols:**

```
ffffffff8155dd70-ffffffff8155e0b3: ext4_ext_search_right (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int ext4_ext_search_right(struct inode *inode, struct ext4_ext_path *path, ext4_lblk_t *logical, ext4_fsblk_t *phys, struct ext4_extent *ret_ex);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/extents.c (ffffffff81595b90)
Location: fs/ext4/extents.c:1534
Inline: False
Direct callers:
  - fs/ext4/extents.c:ext4_ext_map_blocks
  - fs/ext4/extents.c:ext4_ext_remove_space
```
**Symbols:**

```
ffffffff81595b90-ffffffff81595ecf: ext4_ext_search_right (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int ext4_ext_search_right(struct inode *inode, struct ext4_ext_path *path, ext4_lblk_t *logical, ext4_fsblk_t *phys, struct ext4_extent *ret_ex);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/extents.c (ffffffff815ce840)
Location: fs/ext4/extents.c:1534
Inline: False
Direct callers:
  - fs/ext4/extents.c:ext4_ext_map_blocks
  - fs/ext4/extents.c:ext4_ext_remove_space
```
**Symbols:**

```
ffffffff815ce840-ffffffff815ceb7f: ext4_ext_search_right (STB_LOCAL)
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
int ext4_ext_search_right(struct inode *inode, struct ext4_ext_path *path, ext4_lblk_t *logical, ext4_fsblk_t *phys, struct ext4_extent **ret_ex);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/extents.c (ffff8000104656f0)
Location: fs/ext4/extents.c:1501
Inline: False
Direct callers:
  - fs/ext4/extents.c:ext4_ext_map_blocks
  - fs/ext4/extents.c:ext4_ext_remove_space
```
**Symbols:**

```
ffff8000104656f0-ffff800010465a7c: ext4_ext_search_right (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int ext4_ext_search_right(struct inode *inode, struct ext4_ext_path *path, ext4_lblk_t *logical, ext4_fsblk_t *phys, struct ext4_extent **ret_ex);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/extents.c (c0624db8)
Location: fs/ext4/extents.c:1501
Inline: False
Direct callers:
  - fs/ext4/extents.c:ext4_ext_map_blocks
  - fs/ext4/extents.c:ext4_ext_remove_space
```
**Symbols:**

```
c0624db8-c0625104: ext4_ext_search_right (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int ext4_ext_search_right(struct inode *inode, struct ext4_ext_path *path, ext4_lblk_t *logical, ext4_fsblk_t *phys, struct ext4_extent **ret_ex);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/extents.c (c000000000581c70)
Location: fs/ext4/extents.c:1501
Inline: False
Direct callers:
  - fs/ext4/extents.c:ext4_ext_map_blocks
  - fs/ext4/extents.c:ext4_ext_remove_space
```
**Symbols:**

```
c000000000581c70-c0000000005820dc: ext4_ext_search_right (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int ext4_ext_search_right(struct inode *inode, struct ext4_ext_path *path, ext4_lblk_t *logical, ext4_fsblk_t *phys, struct ext4_extent **ret_ex);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/extents.c (ffffffe0002f2c48)
Location: fs/ext4/extents.c:1501
Inline: False
Direct callers:
  - fs/ext4/extents.c:ext4_ext_map_blocks
  - fs/ext4/extents.c:ext4_ext_remove_space
```
**Symbols:**

```
ffffffe0002f2c48-ffffffe0002f2ef6: ext4_ext_search_right (STB_LOCAL)
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
int ext4_ext_search_right(struct inode *inode, struct ext4_ext_path *path, ext4_lblk_t *logical, ext4_fsblk_t *phys, struct ext4_extent **ret_ex);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/extents.c (ffffffff8138a490)
Location: fs/ext4/extents.c:1501
Inline: False
Direct callers:
  - fs/ext4/extents.c:ext4_ext_map_blocks
  - fs/ext4/extents.c:ext4_ext_remove_space
```
**Symbols:**

```
ffffffff8138a490-ffffffff8138a771: ext4_ext_search_right (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int ext4_ext_search_right(struct inode *inode, struct ext4_ext_path *path, ext4_lblk_t *logical, ext4_fsblk_t *phys, struct ext4_extent **ret_ex);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/extents.c (ffffffff8137af20)
Location: fs/ext4/extents.c:1501
Inline: False
Direct callers:
  - fs/ext4/extents.c:ext4_ext_map_blocks
  - fs/ext4/extents.c:ext4_ext_remove_space
```
**Symbols:**

```
ffffffff8137af20-ffffffff8137b201: ext4_ext_search_right (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int ext4_ext_search_right(struct inode *inode, struct ext4_ext_path *path, ext4_lblk_t *logical, ext4_fsblk_t *phys, struct ext4_extent **ret_ex);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/extents.c (ffffffff81387df0)
Location: fs/ext4/extents.c:1501
Inline: False
Direct callers:
  - fs/ext4/extents.c:ext4_ext_map_blocks
  - fs/ext4/extents.c:ext4_ext_remove_space
```
**Symbols:**

```
ffffffff81387df0-ffffffff813880d1: ext4_ext_search_right (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int ext4_ext_search_right(struct inode *inode, struct ext4_ext_path *path, ext4_lblk_t *logical, ext4_fsblk_t *phys, struct ext4_extent **ret_ex);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/extents.c (ffffffff8139baf0)
Location: fs/ext4/extents.c:1501
Inline: False
Direct callers:
  - fs/ext4/extents.c:ext4_ext_map_blocks
  - fs/ext4/extents.c:ext4_ext_remove_space
```
**Symbols:**

```
ffffffff8139baf0-ffffffff8139bdd1: ext4_ext_search_right (STB_LOCAL)
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
<details>
<summary>Changed between <code>5.8</code> and <code>5.11</code> ⚠️</summary>
<ul>
<li>
<b>Param type changed. </b>
<code>struct ext4_extent **ret_ex</code> ➡️ <code>struct ext4_extent *ret_ex</code>
</li>
</ul>
</details>
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
