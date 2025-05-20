# Function: <code>ext4_ext_handle_unwritten_extents</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int ext4_ext_handle_unwritten_extents(handle_t *handle, struct inode *inode, struct ext4_map_blocks *map, struct ext4_ext_path **ppath, int flags, unsigned int allocated, ext4_fsblk_t newblock);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/extents.c (ffffffff812c7a20)
Location: fs/ext4/extents.c:4010
Inline: False
Direct callers:
  - fs/ext4/extents.c:ext4_ext_map_blocks
```
**Symbols:**

```
ffffffff812c7a20-ffffffff812c876d: ext4_ext_handle_unwritten_extents (STB_LOCAL)
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
In fs/ext4/extents.c (ffffffff812f780b)
Location: fs/ext4/extents.c:4024
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
In fs/ext4/extents.c (ffffffff8130d821)
Location: fs/ext4/extents.c:4016
Inline: True
Inline callers:
  - fs/ext4/extents.c:ext4_ext_map_blocks
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int ext4_ext_handle_unwritten_extents(handle_t *handle, struct inode *inode, struct ext4_map_blocks *map, struct ext4_ext_path **ppath, int flags, unsigned int allocated, ext4_fsblk_t newblock);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/extents.c (ffffffff812eb9e0)
Location: fs/ext4/extents.c:4011
Inline: False
Direct callers:
  - fs/ext4/extents.c:ext4_ext_map_blocks
```
**Symbols:**

```
ffffffff812eb9e0-ffffffff812ec5bc: ext4_ext_handle_unwritten_extents (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int ext4_ext_handle_unwritten_extents(handle_t *handle, struct inode *inode, struct ext4_map_blocks *map, struct ext4_ext_path **ppath, int flags, unsigned int allocated, ext4_fsblk_t newblock);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/extents.c (ffffffff813104a0)
Location: fs/ext4/extents.c:4011
Inline: False
Direct callers:
  - fs/ext4/extents.c:ext4_ext_map_blocks
```
**Symbols:**

```
ffffffff813104a0-ffffffff81311080: ext4_ext_handle_unwritten_extents (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int ext4_ext_handle_unwritten_extents(handle_t *handle, struct inode *inode, struct ext4_map_blocks *map, struct ext4_ext_path **ppath, int flags, unsigned int allocated, ext4_fsblk_t newblock);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/extents.c (ffffffff8133e340)
Location: fs/ext4/extents.c:4005
Inline: False
Direct callers:
  - fs/ext4/extents.c:ext4_ext_map_blocks
```
**Symbols:**

```
ffffffff8133e340-ffffffff8133ef16: ext4_ext_handle_unwritten_extents (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int ext4_ext_handle_unwritten_extents(handle_t *handle, struct inode *inode, struct ext4_map_blocks *map, struct ext4_ext_path **ppath, int flags, unsigned int allocated, ext4_fsblk_t newblock);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/extents.c (ffffffff81354ea0)
Location: fs/ext4/extents.c:3959
Inline: False
Direct callers:
  - fs/ext4/extents.c:ext4_ext_map_blocks
```
**Symbols:**

```
ffffffff81354ea0-ffffffff81355a72: ext4_ext_handle_unwritten_extents (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int ext4_ext_handle_unwritten_extents(handle_t *handle, struct inode *inode, struct ext4_map_blocks *map, struct ext4_ext_path **ppath, int flags, unsigned int allocated, ext4_fsblk_t newblock);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/extents.c (ffffffff8137f000)
Location: fs/ext4/extents.c:3979
Inline: False
Direct callers:
  - fs/ext4/extents.c:ext4_ext_map_blocks
```
**Symbols:**

```
ffffffff8137f000-ffffffff8137f44b: ext4_ext_handle_unwritten_extents (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int ext4_ext_handle_unwritten_extents(handle_t *handle, struct inode *inode, struct ext4_map_blocks *map, struct ext4_ext_path **ppath, int flags, unsigned int allocated, ext4_fsblk_t newblock);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/extents.c (ffffffff81397720)
Location: fs/ext4/extents.c:4025
Inline: False
Direct callers:
  - fs/ext4/extents.c:ext4_ext_map_blocks
```
**Symbols:**

```
ffffffff81397720-ffffffff81397b6b: ext4_ext_handle_unwritten_extents (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int ext4_ext_handle_unwritten_extents(handle_t *handle, struct inode *inode, struct ext4_map_blocks *map, struct ext4_ext_path **ppath, int flags, unsigned int allocated, ext4_fsblk_t newblock);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/extents.c (ffffffff813e30c0)
Location: fs/ext4/extents.c:3803
Inline: False
Direct callers:
  - fs/ext4/extents.c:ext4_ext_map_blocks
```
**Symbols:**

```
ffffffff813e30c0-ffffffff813e3347: ext4_ext_handle_unwritten_extents (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int ext4_ext_handle_unwritten_extents(handle_t *handle, struct inode *inode, struct ext4_map_blocks *map, struct ext4_ext_path **ppath, int flags, unsigned int allocated, ext4_fsblk_t newblock);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/extents.c (ffffffff813f4910)
Location: fs/ext4/extents.c:3802
Inline: False
Direct callers:
  - fs/ext4/extents.c:ext4_ext_map_blocks
```
**Symbols:**

```
ffffffff813f4910-ffffffff813f4b58: ext4_ext_handle_unwritten_extents (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int ext4_ext_handle_unwritten_extents(handle_t *handle, struct inode *inode, struct ext4_map_blocks *map, struct ext4_ext_path **ppath, int flags, unsigned int allocated, ext4_fsblk_t newblock);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/extents.c (ffffffff813fab40)
Location: fs/ext4/extents.c:3808
Inline: False
Direct callers:
  - fs/ext4/extents.c:ext4_ext_map_blocks
```
**Symbols:**

```
ffffffff813fab40-ffffffff813fae91: ext4_ext_handle_unwritten_extents (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int ext4_ext_handle_unwritten_extents(handle_t *handle, struct inode *inode, struct ext4_map_blocks *map, struct ext4_ext_path **ppath, int flags, unsigned int allocated, ext4_fsblk_t newblock);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/extents.c (ffffffff8144cf30)
Location: fs/ext4/extents.c:3847
Inline: False
Direct callers:
  - fs/ext4/extents.c:ext4_ext_map_blocks
```
**Symbols:**

```
ffffffff8144cf30-ffffffff8144d25b: ext4_ext_handle_unwritten_extents (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int ext4_ext_handle_unwritten_extents(handle_t *handle, struct inode *inode, struct ext4_map_blocks *map, struct ext4_ext_path **ppath, int flags, unsigned int allocated, ext4_fsblk_t newblock);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/extents.c (ffffffff814c9960)
Location: fs/ext4/extents.c:3845
Inline: False
Direct callers:
  - fs/ext4/extents.c:ext4_ext_map_blocks
```
**Symbols:**

```
ffffffff814c9960-ffffffff814c9cde: ext4_ext_handle_unwritten_extents (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int ext4_ext_handle_unwritten_extents(handle_t *handle, struct inode *inode, struct ext4_map_blocks *map, struct ext4_ext_path **ppath, int flags, unsigned int allocated, ext4_fsblk_t newblock);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/extents.c (ffffffff81561fe0)
Location: fs/ext4/extents.c:3850
Inline: False
Direct callers:
  - fs/ext4/extents.c:ext4_ext_map_blocks
```
**Symbols:**

```
ffffffff81561fe0-ffffffff8156235e: ext4_ext_handle_unwritten_extents (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int ext4_ext_handle_unwritten_extents(handle_t *handle, struct inode *inode, struct ext4_map_blocks *map, struct ext4_ext_path **ppath, int flags, unsigned int allocated, ext4_fsblk_t newblock);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/extents.c (ffffffff81599d50)
Location: fs/ext4/extents.c:3849
Inline: False
Direct callers:
  - fs/ext4/extents.c:ext4_ext_map_blocks
```
**Symbols:**

```
ffffffff81599d50-ffffffff8159a0ce: ext4_ext_handle_unwritten_extents (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int ext4_ext_handle_unwritten_extents(handle_t *handle, struct inode *inode, struct ext4_map_blocks *map, struct ext4_ext_path **ppath, int flags, unsigned int allocated, ext4_fsblk_t newblock);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/extents.c (ffffffff815d2ba0)
Location: fs/ext4/extents.c:3825
Inline: False
Direct callers:
  - fs/ext4/extents.c:ext4_ext_map_blocks
```
**Symbols:**

```
ffffffff815d2ba0-ffffffff815d2f1e: ext4_ext_handle_unwritten_extents (STB_LOCAL)
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
int ext4_ext_handle_unwritten_extents(handle_t *handle, struct inode *inode, struct ext4_map_blocks *map, struct ext4_ext_path **ppath, int flags, unsigned int allocated, ext4_fsblk_t newblock);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/extents.c (ffff80001046a320)
Location: fs/ext4/extents.c:4025
Inline: False
Direct callers:
  - fs/ext4/extents.c:ext4_ext_map_blocks
```
**Symbols:**

```
ffff80001046a320-ffff80001046a718: ext4_ext_handle_unwritten_extents (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int ext4_ext_handle_unwritten_extents(handle_t *handle, struct inode *inode, struct ext4_map_blocks *map, struct ext4_ext_path **ppath, int flags, unsigned int allocated, ext4_fsblk_t newblock);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/extents.c (c062b164)
Location: fs/ext4/extents.c:4025
Inline: False
Direct callers:
  - fs/ext4/extents.c:ext4_ext_map_blocks
```
**Symbols:**

```
c062b164-c062b5b8: ext4_ext_handle_unwritten_extents (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int ext4_ext_handle_unwritten_extents(handle_t *handle, struct inode *inode, struct ext4_map_blocks *map, struct ext4_ext_path **ppath, int flags, unsigned int allocated, ext4_fsblk_t newblock);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/extents.c (c000000000589290)
Location: fs/ext4/extents.c:4025
Inline: False
Direct callers:
  - fs/ext4/extents.c:ext4_ext_map_blocks
```
**Symbols:**

```
c000000000589290-c000000000589850: ext4_ext_handle_unwritten_extents (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int ext4_ext_handle_unwritten_extents(handle_t *handle, struct inode *inode, struct ext4_map_blocks *map, struct ext4_ext_path **ppath, int flags, unsigned int allocated, ext4_fsblk_t newblock);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/extents.c (ffffffe0002f7c0a)
Location: fs/ext4/extents.c:4025
Inline: False
Direct callers:
  - fs/ext4/extents.c:ext4_ext_map_blocks
```
**Symbols:**

```
ffffffe0002f7c0a-ffffffe0002f7fba: ext4_ext_handle_unwritten_extents (STB_LOCAL)
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
int ext4_ext_handle_unwritten_extents(handle_t *handle, struct inode *inode, struct ext4_map_blocks *map, struct ext4_ext_path **ppath, int flags, unsigned int allocated, ext4_fsblk_t newblock);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/extents.c (ffffffff8138fd00)
Location: fs/ext4/extents.c:4025
Inline: False
Direct callers:
  - fs/ext4/extents.c:ext4_ext_map_blocks
```
**Symbols:**

```
ffffffff8138fd00-ffffffff8139014b: ext4_ext_handle_unwritten_extents (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int ext4_ext_handle_unwritten_extents(handle_t *handle, struct inode *inode, struct ext4_map_blocks *map, struct ext4_ext_path **ppath, int flags, unsigned int allocated, ext4_fsblk_t newblock);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/extents.c (ffffffff81380790)
Location: fs/ext4/extents.c:4025
Inline: False
Direct callers:
  - fs/ext4/extents.c:ext4_ext_map_blocks
```
**Symbols:**

```
ffffffff81380790-ffffffff81380bdb: ext4_ext_handle_unwritten_extents (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int ext4_ext_handle_unwritten_extents(handle_t *handle, struct inode *inode, struct ext4_map_blocks *map, struct ext4_ext_path **ppath, int flags, unsigned int allocated, ext4_fsblk_t newblock);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/extents.c (ffffffff8138d660)
Location: fs/ext4/extents.c:4025
Inline: False
Direct callers:
  - fs/ext4/extents.c:ext4_ext_map_blocks
```
**Symbols:**

```
ffffffff8138d660-ffffffff8138daab: ext4_ext_handle_unwritten_extents (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int ext4_ext_handle_unwritten_extents(handle_t *handle, struct inode *inode, struct ext4_map_blocks *map, struct ext4_ext_path **ppath, int flags, unsigned int allocated, ext4_fsblk_t newblock);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/extents.c (ffffffff813a13f0)
Location: fs/ext4/extents.c:4025
Inline: False
Direct callers:
  - fs/ext4/extents.c:ext4_ext_map_blocks
```
**Symbols:**

```
ffffffff813a13f0-ffffffff813a184f: ext4_ext_handle_unwritten_extents (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
