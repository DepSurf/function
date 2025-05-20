# Function: <code>ext4_ext_search_left</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/ext4/extents.c (ffffffff812c890e)
Location: fs/ext4/extents.c:1419
Inline: True
Inline callers:
  - fs/ext4/extents.c:ext4_ext_map_blocks
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/ext4/extents.c (ffffffff812f75d0)
Location: fs/ext4/extents.c:1425
Inline: True
Inline callers:
  - fs/ext4/extents.c:ext4_ext_map_blocks
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/ext4/extents.c (ffffffff8130d5e2)
Location: fs/ext4/extents.c:1425
Inline: True
Inline callers:
  - fs/ext4/extents.c:ext4_ext_map_blocks
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/ext4/extents.c (ffffffff812ec968)
Location: fs/ext4/extents.c:1425
Inline: True
Inline callers:
  - fs/ext4/extents.c:ext4_ext_map_blocks
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/ext4/extents.c (ffffffff8131142d)
Location: fs/ext4/extents.c:1425
Inline: True
Inline callers:
  - fs/ext4/extents.c:ext4_ext_map_blocks
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/ext4/extents.c (ffffffff8133f09b)
Location: fs/ext4/extents.c:1419
Inline: True
Inline callers:
  - fs/ext4/extents.c:ext4_ext_map_blocks
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/ext4/extents.c (ffffffff813565fb)
Location: fs/ext4/extents.c:1419
Inline: True
Inline callers:
  - fs/ext4/extents.c:ext4_ext_map_blocks
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/ext4/extents.c (ffffffff8137ffac)
Location: fs/ext4/extents.c:1436
Inline: True
Inline callers:
  - fs/ext4/extents.c:ext4_ext_map_blocks
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/ext4/extents.c (ffffffff813986ac)
Location: fs/ext4/extents.c:1436
Inline: True
Inline callers:
  - fs/ext4/extents.c:ext4_ext_map_blocks
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int ext4_ext_search_left(struct inode *inode, struct ext4_ext_path *path, ext4_lblk_t *logical, ext4_fsblk_t *phys);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/extents.c (ffffffff813dcd50)
Location: fs/ext4/extents.c:1417
Inline: False
Direct callers:
  - fs/ext4/extents.c:ext4_ext_map_blocks
```
**Symbols:**

```
ffffffff813dcd50-ffffffff813dcef9: ext4_ext_search_left (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int ext4_ext_search_left(struct inode *inode, struct ext4_ext_path *path, ext4_lblk_t *logical, ext4_fsblk_t *phys);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/extents.c (ffffffff813ee690)
Location: fs/ext4/extents.c:1415
Inline: False
Direct callers:
  - fs/ext4/extents.c:ext4_ext_map_blocks
```
**Symbols:**

```
ffffffff813ee690-ffffffff813ee839: ext4_ext_search_left (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int ext4_ext_search_left(struct inode *inode, struct ext4_ext_path *path, ext4_lblk_t *logical, ext4_fsblk_t *phys);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/extents.c (ffffffff813f4c60)
Location: fs/ext4/extents.c:1418
Inline: False
Direct callers:
  - fs/ext4/extents.c:ext4_ext_map_blocks
```
**Symbols:**

```
ffffffff813f4c60-ffffffff813f4e09: ext4_ext_search_left (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int ext4_ext_search_left(struct inode *inode, struct ext4_ext_path *path, ext4_lblk_t *logical, ext4_fsblk_t *phys);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/extents.c (ffffffff81446eb0)
Location: fs/ext4/extents.c:1460
Inline: False
Direct callers:
  - fs/ext4/extents.c:ext4_ext_map_blocks
```
**Symbols:**

```
ffffffff81446eb0-ffffffff81447059: ext4_ext_search_left (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int ext4_ext_search_left(struct inode *inode, struct ext4_ext_path *path, ext4_lblk_t *logical, ext4_fsblk_t *phys);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/extents.c (ffffffff814c31c0)
Location: fs/ext4/extents.c:1462
Inline: False
Direct callers:
  - fs/ext4/extents.c:ext4_ext_map_blocks
```
**Symbols:**

```
ffffffff814c31c0-ffffffff814c335f: ext4_ext_search_left (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int ext4_ext_search_left(struct inode *inode, struct ext4_ext_path *path, ext4_lblk_t *logical, ext4_fsblk_t *phys);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/extents.c (ffffffff8155b5d0)
Location: fs/ext4/extents.c:1470
Inline: False
Direct callers:
  - fs/ext4/extents.c:ext4_ext_map_blocks
```
**Symbols:**

```
ffffffff8155b5d0-ffffffff8155b76f: ext4_ext_search_left (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int ext4_ext_search_left(struct inode *inode, struct ext4_ext_path *path, ext4_lblk_t *logical, ext4_fsblk_t *phys);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/extents.c (ffffffff815933f0)
Location: fs/ext4/extents.c:1470
Inline: False
Direct callers:
  - fs/ext4/extents.c:ext4_ext_map_blocks
```
**Symbols:**

```
ffffffff815933f0-ffffffff8159358f: ext4_ext_search_left (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int ext4_ext_search_left(struct inode *inode, struct ext4_ext_path *path, ext4_lblk_t *logical, ext4_fsblk_t *phys);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/extents.c (ffffffff815cc0e0)
Location: fs/ext4/extents.c:1470
Inline: False
Direct callers:
  - fs/ext4/extents.c:ext4_ext_map_blocks
```
**Symbols:**

```
ffffffff815cc0e0-ffffffff815cc27f: ext4_ext_search_left (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/ext4/extents.c (ffff80001046b244)
Location: fs/ext4/extents.c:1436
Inline: True
Inline callers:
  - fs/ext4/extents.c:ext4_ext_map_blocks
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/ext4/extents.c (c062c1ec)
Location: fs/ext4/extents.c:1436
Inline: True
Inline callers:
  - fs/ext4/extents.c:ext4_ext_map_blocks
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/ext4/extents.c (c00000000058a5c8)
Location: fs/ext4/extents.c:1436
Inline: True
Inline callers:
  - fs/ext4/extents.c:ext4_ext_map_blocks
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/ext4/extents.c (ffffffe0002f8950)
Location: fs/ext4/extents.c:1436
Inline: True
Inline callers:
  - fs/ext4/extents.c:ext4_ext_map_blocks
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/ext4/extents.c (ffffffff81390c8c)
Location: fs/ext4/extents.c:1436
Inline: True
Inline callers:
  - fs/ext4/extents.c:ext4_ext_map_blocks
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/ext4/extents.c (ffffffff8138171c)
Location: fs/ext4/extents.c:1436
Inline: True
Inline callers:
  - fs/ext4/extents.c:ext4_ext_map_blocks
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/ext4/extents.c (ffffffff8138e5ec)
Location: fs/ext4/extents.c:1436
Inline: True
Inline callers:
  - fs/ext4/extents.c:ext4_ext_map_blocks
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/ext4/extents.c (ffffffff813a23ac)
Location: fs/ext4/extents.c:1436
Inline: True
Inline callers:
  - fs/ext4/extents.c:ext4_ext_map_blocks
```
</details>
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
