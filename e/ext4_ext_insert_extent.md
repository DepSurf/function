# Function: <code>ext4_ext_insert_extent</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int ext4_ext_insert_extent(handle_t *handle, struct inode *inode, struct ext4_ext_path **ppath, struct ext4_extent *newext, int gb_flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/extents.c (ffffffff812c4ce0)
Location: fs/ext4/extents.c:1925
Inline: False
Direct callers:
  - fs/ext4/extents.c:ext4_split_extent_at
  - fs/ext4/extents.c:ext4_ext_map_blocks
  - fs/ext4/extents.c:ext4_ext_map_blocks
  - fs/ext4/migrate.c:finish_range
```
**Symbols:**

```
ffffffff812c4ce0-ffffffff812c5ff7: ext4_ext_insert_extent (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int ext4_ext_insert_extent(handle_t *handle, struct inode *inode, struct ext4_ext_path **ppath, struct ext4_extent *newext, int gb_flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/extents.c (ffffffff812f4520)
Location: fs/ext4/extents.c:1937
Inline: False
Direct callers:
  - fs/ext4/extents.c:ext4_ext_map_blocks
  - fs/ext4/extents.c:ext4_split_extent_at
  - fs/ext4/migrate.c:finish_range
```
**Symbols:**

```
ffffffff812f4520-ffffffff812f5835: ext4_ext_insert_extent (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int ext4_ext_insert_extent(handle_t *handle, struct inode *inode, struct ext4_ext_path **ppath, struct ext4_extent *newext, int gb_flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/extents.c (ffffffff8130a4d0)
Location: fs/ext4/extents.c:1937
Inline: False
Direct callers:
  - fs/ext4/extents.c:ext4_ext_map_blocks
  - fs/ext4/extents.c:ext4_split_extent_at
  - fs/ext4/migrate.c:finish_range
```
**Symbols:**

```
ffffffff8130a4d0-ffffffff8130b7e5: ext4_ext_insert_extent (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int ext4_ext_insert_extent(handle_t *handle, struct inode *inode, struct ext4_ext_path **ppath, struct ext4_extent *newext, int gb_flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/extents.c (ffffffff812e8bb0)
Location: fs/ext4/extents.c:1937
Inline: False
Direct callers:
  - fs/ext4/extents.c:ext4_ext_map_blocks
  - fs/ext4/extents.c:ext4_split_extent_at
  - fs/ext4/migrate.c:finish_range
```
**Symbols:**

```
ffffffff812e8bb0-ffffffff812e9ed3: ext4_ext_insert_extent (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int ext4_ext_insert_extent(handle_t *handle, struct inode *inode, struct ext4_ext_path **ppath, struct ext4_extent *newext, int gb_flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/extents.c (ffffffff8130d650)
Location: fs/ext4/extents.c:1937
Inline: False
Direct callers:
  - fs/ext4/extents.c:ext4_ext_map_blocks
  - fs/ext4/extents.c:ext4_split_extent_at
  - fs/ext4/migrate.c:finish_range
```
**Symbols:**

```
ffffffff8130d650-ffffffff8130e973: ext4_ext_insert_extent (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int ext4_ext_insert_extent(handle_t *handle, struct inode *inode, struct ext4_ext_path **ppath, struct ext4_extent *newext, int gb_flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/extents.c (ffffffff8133c860)
Location: fs/ext4/extents.c:1931
Inline: False
Direct callers:
  - fs/ext4/extents.c:ext4_ext_map_blocks
  - fs/ext4/extents.c:ext4_split_extent_at
  - fs/ext4/migrate.c:finish_range
```
**Symbols:**

```
ffffffff8133c860-ffffffff8133d14c: ext4_ext_insert_extent (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int ext4_ext_insert_extent(handle_t *handle, struct inode *inode, struct ext4_ext_path **ppath, struct ext4_extent *newext, int gb_flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/extents.c (ffffffff81353f10)
Location: fs/ext4/extents.c:1931
Inline: False
Direct callers:
  - fs/ext4/extents.c:ext4_ext_map_blocks
  - fs/ext4/extents.c:ext4_split_extent_at
  - fs/ext4/migrate.c:finish_range
```
**Symbols:**

```
ffffffff81353f10-ffffffff813547fc: ext4_ext_insert_extent (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int ext4_ext_insert_extent(handle_t *handle, struct inode *inode, struct ext4_ext_path **ppath, struct ext4_extent *newext, int gb_flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/extents.c (ffffffff8137da60)
Location: fs/ext4/extents.c:1948
Inline: False
Direct callers:
  - fs/ext4/extents.c:ext4_ext_map_blocks
  - fs/ext4/extents.c:ext4_split_extent_at
  - fs/ext4/migrate.c:finish_range
```
**Symbols:**

```
ffffffff8137da60-ffffffff8137e016: ext4_ext_insert_extent (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int ext4_ext_insert_extent(handle_t *handle, struct inode *inode, struct ext4_ext_path **ppath, struct ext4_extent *newext, int gb_flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/extents.c (ffffffff81396180)
Location: fs/ext4/extents.c:1948
Inline: False
Direct callers:
  - fs/ext4/extents.c:ext4_ext_map_blocks
  - fs/ext4/extents.c:ext4_split_extent_at
  - fs/ext4/migrate.c:finish_range
```
**Symbols:**

```
ffffffff81396180-ffffffff81396736: ext4_ext_insert_extent (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int ext4_ext_insert_extent(handle_t *handle, struct inode *inode, struct ext4_ext_path **ppath, struct ext4_extent *newext, int gb_flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/extents.c (ffffffff813e1740)
Location: fs/ext4/extents.c:1918
Inline: False
Direct callers:
  - fs/ext4/extents.c:ext4_ext_map_blocks
  - fs/ext4/extents.c:ext4_split_extent_at
  - fs/ext4/migrate.c:finish_range
```
**Symbols:**

```
ffffffff813e1740-ffffffff813e1d71: ext4_ext_insert_extent (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int ext4_ext_insert_extent(handle_t *handle, struct inode *inode, struct ext4_ext_path **ppath, struct ext4_extent *newext, int gb_flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/extents.c (ffffffff813f2fa0)
Location: fs/ext4/extents.c:1917
Inline: False
Direct callers:
  - fs/ext4/extents.c:ext4_ext_map_blocks
  - fs/ext4/extents.c:ext4_split_extent_at
  - fs/ext4/migrate.c:finish_range
  - fs/ext4/fast_commit.c:ext4_fc_replay_add_range
```
**Symbols:**

```
ffffffff813f2fa0-ffffffff813f35d1: ext4_ext_insert_extent (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int ext4_ext_insert_extent(handle_t *handle, struct inode *inode, struct ext4_ext_path **ppath, struct ext4_extent *newext, int gb_flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/extents.c (ffffffff813f9280)
Location: fs/ext4/extents.c:1920
Inline: False
Direct callers:
  - fs/ext4/extents.c:ext4_ext_map_blocks
  - fs/ext4/extents.c:ext4_split_extent_at
  - fs/ext4/migrate.c:finish_range
```
**Symbols:**

```
ffffffff813f9280-ffffffff813f99c7: ext4_ext_insert_extent (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int ext4_ext_insert_extent(handle_t *handle, struct inode *inode, struct ext4_ext_path **ppath, struct ext4_extent *newext, int gb_flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/extents.c (ffffffff8144b760)
Location: fs/ext4/extents.c:1958
Inline: False
Direct callers:
  - fs/ext4/extents.c:ext4_ext_map_blocks
  - fs/ext4/extents.c:ext4_split_extent_at
  - fs/ext4/migrate.c:finish_range
```
**Symbols:**

```
ffffffff8144b760-ffffffff8144be52: ext4_ext_insert_extent (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int ext4_ext_insert_extent(handle_t *handle, struct inode *inode, struct ext4_ext_path **ppath, struct ext4_extent *newext, int gb_flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/extents.c (ffffffff814c8000)
Location: fs/ext4/extents.c:1959
Inline: False
Direct callers:
  - fs/ext4/extents.c:ext4_ext_map_blocks
  - fs/ext4/extents.c:ext4_split_extent_at
  - fs/ext4/migrate.c:finish_range
```
**Symbols:**

```
ffffffff814c8000-ffffffff814c874a: ext4_ext_insert_extent (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int ext4_ext_insert_extent(handle_t *handle, struct inode *inode, struct ext4_ext_path **ppath, struct ext4_extent *newext, int gb_flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/extents.c (ffffffff81560630)
Location: fs/ext4/extents.c:1967
Inline: False
Direct callers:
  - fs/ext4/extents.c:ext4_ext_map_blocks
  - fs/ext4/extents.c:ext4_split_extent_at
  - fs/ext4/migrate.c:finish_range
```
**Symbols:**

```
ffffffff81560630-ffffffff81560d7a: ext4_ext_insert_extent (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int ext4_ext_insert_extent(handle_t *handle, struct inode *inode, struct ext4_ext_path **ppath, struct ext4_extent *newext, int gb_flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/extents.c (ffffffff815983f0)
Location: fs/ext4/extents.c:1967
Inline: False
Direct callers:
  - fs/ext4/extents.c:ext4_ext_map_blocks
  - fs/ext4/extents.c:ext4_split_extent_at
  - fs/ext4/migrate.c:finish_range
```
**Symbols:**

```
ffffffff815983f0-ffffffff81598b49: ext4_ext_insert_extent (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int ext4_ext_insert_extent(handle_t *handle, struct inode *inode, struct ext4_ext_path **ppath, struct ext4_extent *newext, int gb_flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/extents.c (ffffffff815d1230)
Location: fs/ext4/extents.c:1967
Inline: False
Direct callers:
  - fs/ext4/extents.c:ext4_ext_map_blocks
  - fs/ext4/extents.c:ext4_split_extent_at
  - fs/ext4/migrate.c:finish_range
```
**Symbols:**

```
ffffffff815d1230-ffffffff815d1989: ext4_ext_insert_extent (STB_GLOBAL)
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
int ext4_ext_insert_extent(handle_t *handle, struct inode *inode, struct ext4_ext_path **ppath, struct ext4_extent *newext, int gb_flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/extents.c (ffff800010468ff8)
Location: fs/ext4/extents.c:1948
Inline: False
Direct callers:
  - fs/ext4/extents.c:ext4_ext_map_blocks
  - fs/ext4/extents.c:ext4_split_extent_at
  - fs/ext4/migrate.c:finish_range
```
**Symbols:**

```
ffff800010468ff8-ffff800010469558: ext4_ext_insert_extent (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int ext4_ext_insert_extent(handle_t *handle, struct inode *inode, struct ext4_ext_path **ppath, struct ext4_extent *newext, int gb_flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/extents.c (c0629d84)
Location: fs/ext4/extents.c:1948
Inline: False
Direct callers:
  - fs/ext4/extents.c:ext4_ext_map_blocks
  - fs/ext4/extents.c:ext4_split_extent_at
  - fs/ext4/migrate.c:finish_range
```
**Symbols:**

```
c0629d84-c062a2ac: ext4_ext_insert_extent (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int ext4_ext_insert_extent(handle_t *handle, struct inode *inode, struct ext4_ext_path **ppath, struct ext4_extent *newext, int gb_flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/extents.c (c000000000587720)
Location: fs/ext4/extents.c:1948
Inline: False
Direct callers:
  - fs/ext4/extents.c:ext4_ext_map_blocks
  - fs/ext4/extents.c:ext4_split_extent_at
  - fs/ext4/migrate.c:finish_range
```
**Symbols:**

```
c000000000587720-c0000000005881d4: ext4_ext_insert_extent (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int ext4_ext_insert_extent(handle_t *handle, struct inode *inode, struct ext4_ext_path **ppath, struct ext4_extent *newext, int gb_flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/extents.c (ffffffe0002f6a18)
Location: fs/ext4/extents.c:1948
Inline: False
Direct callers:
  - fs/ext4/extents.c:ext4_ext_map_blocks
  - fs/ext4/extents.c:ext4_split_extent_at
  - fs/ext4/migrate.c:finish_range
```
**Symbols:**

```
ffffffe0002f6a18-ffffffe0002f6ea2: ext4_ext_insert_extent (STB_GLOBAL)
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
int ext4_ext_insert_extent(handle_t *handle, struct inode *inode, struct ext4_ext_path **ppath, struct ext4_extent *newext, int gb_flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/extents.c (ffffffff8138e760)
Location: fs/ext4/extents.c:1948
Inline: False
Direct callers:
  - fs/ext4/extents.c:ext4_ext_map_blocks
  - fs/ext4/extents.c:ext4_split_extent_at
  - fs/ext4/migrate.c:finish_range
```
**Symbols:**

```
ffffffff8138e760-ffffffff8138ed16: ext4_ext_insert_extent (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int ext4_ext_insert_extent(handle_t *handle, struct inode *inode, struct ext4_ext_path **ppath, struct ext4_extent *newext, int gb_flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/extents.c (ffffffff8137f1f0)
Location: fs/ext4/extents.c:1948
Inline: False
Direct callers:
  - fs/ext4/extents.c:ext4_ext_map_blocks
  - fs/ext4/extents.c:ext4_split_extent_at
  - fs/ext4/migrate.c:finish_range
```
**Symbols:**

```
ffffffff8137f1f0-ffffffff8137f7a6: ext4_ext_insert_extent (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int ext4_ext_insert_extent(handle_t *handle, struct inode *inode, struct ext4_ext_path **ppath, struct ext4_extent *newext, int gb_flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/extents.c (ffffffff8138c0c0)
Location: fs/ext4/extents.c:1948
Inline: False
Direct callers:
  - fs/ext4/extents.c:ext4_ext_map_blocks
  - fs/ext4/extents.c:ext4_split_extent_at
  - fs/ext4/migrate.c:finish_range
```
**Symbols:**

```
ffffffff8138c0c0-ffffffff8138c676: ext4_ext_insert_extent (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int ext4_ext_insert_extent(handle_t *handle, struct inode *inode, struct ext4_ext_path **ppath, struct ext4_extent *newext, int gb_flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/extents.c (ffffffff8139fe10)
Location: fs/ext4/extents.c:1948
Inline: False
Direct callers:
  - fs/ext4/extents.c:ext4_ext_map_blocks
  - fs/ext4/extents.c:ext4_split_extent_at
  - fs/ext4/migrate.c:finish_range
```
**Symbols:**

```
ffffffff8139fe10-ffffffff813a03c6: ext4_ext_insert_extent (STB_GLOBAL)
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
