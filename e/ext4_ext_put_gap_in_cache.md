# Function: <code>ext4_ext_put_gap_in_cache</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void ext4_ext_put_gap_in_cache(struct inode *inode, struct ext4_ext_path *path, ext4_lblk_t block);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/extents.c (ffffffff812c41d0)
Location: fs/ext4/extents.c:2301
Inline: False
Direct callers:
  - fs/ext4/extents.c:ext4_ext_map_blocks
```
**Symbols:**

```
ffffffff812c41d0-ffffffff812c42e0: ext4_ext_put_gap_in_cache (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void ext4_ext_put_gap_in_cache(struct inode *inode, ext4_lblk_t hole_start, ext4_lblk_t hole_len);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/extents.c (ffffffff812f2120)
Location: fs/ext4/extents.c:2355
Inline: False
Direct callers:
  - fs/ext4/extents.c:ext4_ext_map_blocks
```
**Symbols:**

```
ffffffff812f2120-ffffffff812f21a8: ext4_ext_put_gap_in_cache (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void ext4_ext_put_gap_in_cache(struct inode *inode, ext4_lblk_t hole_start, ext4_lblk_t hole_len);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/extents.c (ffffffff813080f0)
Location: fs/ext4/extents.c:2355
Inline: False
Direct callers:
  - fs/ext4/extents.c:ext4_ext_map_blocks
```
**Symbols:**

```
ffffffff813080f0-ffffffff81308178: ext4_ext_put_gap_in_cache (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void ext4_ext_put_gap_in_cache(struct inode *inode, ext4_lblk_t hole_start, ext4_lblk_t hole_len);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/extents.c (ffffffff812e6890)
Location: fs/ext4/extents.c:2355
Inline: False
Direct callers:
  - fs/ext4/extents.c:ext4_ext_map_blocks
```
**Symbols:**

```
ffffffff812e6890-ffffffff812e6918: ext4_ext_put_gap_in_cache (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void ext4_ext_put_gap_in_cache(struct inode *inode, ext4_lblk_t hole_start, ext4_lblk_t hole_len);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/extents.c (ffffffff8130b2a0)
Location: fs/ext4/extents.c:2355
Inline: False
Direct callers:
  - fs/ext4/extents.c:ext4_ext_map_blocks
```
**Symbols:**

```
ffffffff8130b2a0-ffffffff8130b328: ext4_ext_put_gap_in_cache (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void ext4_ext_put_gap_in_cache(struct inode *inode, ext4_lblk_t hole_start, ext4_lblk_t hole_len);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/extents.c (ffffffff81339250)
Location: fs/ext4/extents.c:2349
Inline: False
Direct callers:
  - fs/ext4/extents.c:ext4_ext_map_blocks
```
**Symbols:**

```
ffffffff81339250-ffffffff813392d6: ext4_ext_put_gap_in_cache (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void ext4_ext_put_gap_in_cache(struct inode *inode, ext4_lblk_t hole_start, ext4_lblk_t hole_len);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/extents.c (ffffffff813505c0)
Location: fs/ext4/extents.c:2349
Inline: False
Direct callers:
  - fs/ext4/extents.c:ext4_ext_map_blocks
```
**Symbols:**

```
ffffffff813505c0-ffffffff8135064f: ext4_ext_put_gap_in_cache (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void ext4_ext_put_gap_in_cache(struct inode *inode, ext4_lblk_t hole_start, ext4_lblk_t hole_len);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/extents.c (ffffffff81379280)
Location: fs/ext4/extents.c:2366
Inline: False
Direct callers:
  - fs/ext4/extents.c:ext4_ext_map_blocks
```
**Symbols:**

```
ffffffff81379280-ffffffff81379315: ext4_ext_put_gap_in_cache (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void ext4_ext_put_gap_in_cache(struct inode *inode, ext4_lblk_t hole_start, ext4_lblk_t hole_len);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/extents.c (ffffffff81391630)
Location: fs/ext4/extents.c:2412
Inline: False
Direct callers:
  - fs/ext4/extents.c:ext4_ext_map_blocks
```
**Symbols:**

```
ffffffff81391630-ffffffff813916c5: ext4_ext_put_gap_in_cache (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void ext4_ext_put_gap_in_cache(struct inode *inode, ext4_lblk_t hole_start, ext4_lblk_t hole_len);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/extents.c (ffffffff813dd110)
Location: fs/ext4/extents.c:2233
Inline: False
Direct callers:
  - fs/ext4/extents.c:ext4_ext_map_blocks
```
**Symbols:**

```
ffffffff813dd110-ffffffff813dd1a5: ext4_ext_put_gap_in_cache (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/ext4/extents.c (ffffffff813f6343)
Location: fs/ext4/extents.c:2232
Inline: True
Inline callers:
  - fs/ext4/extents.c:ext4_ext_map_blocks
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/ext4/extents.c (ffffffff813fc850)
Location: fs/ext4/extents.c:2235
Inline: True
Inline callers:
  - fs/ext4/extents.c:ext4_ext_map_blocks
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/ext4/extents.c (ffffffff8144ebed)
Location: fs/ext4/extents.c:2273
Inline: True
Inline callers:
  - fs/ext4/extents.c:ext4_ext_map_blocks
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
In fs/ext4/extents.c (ffffffff814cb8cd)
Location: fs/ext4/extents.c:2272
Inline: True
Inline callers:
  - fs/ext4/extents.c:ext4_ext_map_blocks
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
In fs/ext4/extents.c (ffffffff81563faf)
Location: fs/ext4/extents.c:2279
Inline: True
Inline callers:
  - fs/ext4/extents.c:ext4_ext_map_blocks
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
In fs/ext4/extents.c (ffffffff8159bc99)
Location: fs/ext4/extents.c:2279
Inline: True
Inline callers:
  - fs/ext4/extents.c:ext4_ext_map_blocks
```
</details>
</li>
<li>
In <code>6.8</code>: Absent ⚠️
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: ✅</summary>

```c
void ext4_ext_put_gap_in_cache(struct inode *inode, ext4_lblk_t hole_start, ext4_lblk_t hole_len);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/extents.c (ffff8000104641f8)
Location: fs/ext4/extents.c:2412
Inline: False
Direct callers:
  - fs/ext4/extents.c:ext4_ext_map_blocks
```
**Symbols:**

```
ffff8000104641f8-ffff8000104642ac: ext4_ext_put_gap_in_cache (STB_LOCAL)
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
In fs/ext4/extents.c (c062c7fc)
Location: fs/ext4/extents.c:2412
Inline: True
Inline callers:
  - fs/ext4/extents.c:ext4_ext_map_blocks
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void ext4_ext_put_gap_in_cache(struct inode *inode, ext4_lblk_t hole_start, ext4_lblk_t hole_len);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/extents.c (c0000000005823a0)
Location: fs/ext4/extents.c:2412
Inline: False
Direct callers:
  - fs/ext4/extents.c:ext4_ext_map_blocks
```
**Symbols:**

```
c0000000005823a0-c000000000582484: ext4_ext_put_gap_in_cache (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void ext4_ext_put_gap_in_cache(struct inode *inode, ext4_lblk_t hole_start, ext4_lblk_t hole_len);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/extents.c (ffffffe0002f3138)
Location: fs/ext4/extents.c:2412
Inline: False
Direct callers:
  - fs/ext4/extents.c:ext4_ext_map_blocks
```
**Symbols:**

```
ffffffe0002f3138-ffffffe0002f31b2: ext4_ext_put_gap_in_cache (STB_LOCAL)
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
void ext4_ext_put_gap_in_cache(struct inode *inode, ext4_lblk_t hole_start, ext4_lblk_t hole_len);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/extents.c (ffffffff81389c10)
Location: fs/ext4/extents.c:2412
Inline: False
Direct callers:
  - fs/ext4/extents.c:ext4_ext_map_blocks
```
**Symbols:**

```
ffffffff81389c10-ffffffff81389ca5: ext4_ext_put_gap_in_cache (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void ext4_ext_put_gap_in_cache(struct inode *inode, ext4_lblk_t hole_start, ext4_lblk_t hole_len);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/extents.c (ffffffff8137a6a0)
Location: fs/ext4/extents.c:2412
Inline: False
Direct callers:
  - fs/ext4/extents.c:ext4_ext_map_blocks
```
**Symbols:**

```
ffffffff8137a6a0-ffffffff8137a735: ext4_ext_put_gap_in_cache (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void ext4_ext_put_gap_in_cache(struct inode *inode, ext4_lblk_t hole_start, ext4_lblk_t hole_len);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/extents.c (ffffffff81387570)
Location: fs/ext4/extents.c:2412
Inline: False
Direct callers:
  - fs/ext4/extents.c:ext4_ext_map_blocks
```
**Symbols:**

```
ffffffff81387570-ffffffff81387605: ext4_ext_put_gap_in_cache (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void ext4_ext_put_gap_in_cache(struct inode *inode, ext4_lblk_t hole_start, ext4_lblk_t hole_len);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/extents.c (ffffffff8139b250)
Location: fs/ext4/extents.c:2412
Inline: False
Direct callers:
  - fs/ext4/extents.c:ext4_ext_map_blocks
```
**Symbols:**

```
ffffffff8139b250-ffffffff8139b2e5: ext4_ext_put_gap_in_cache (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
<details>
<summary>Changed between <code>4.4</code> and <code>4.8</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>ext4_lblk_t hole_start</code>
</li>
<li>
<b>Param added. </b>
<code>ext4_lblk_t hole_len</code>
</li>
<li>
<b>Param removed. </b>
<code>struct ext4_ext_path *path</code>
</li>
<li>
<b>Param removed. </b>
<code>ext4_lblk_t block</code>
</li>
</ul>
</details>
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
</ul>
<b>Arch</b>
<ul>
<li>
No changes between <code>amd64</code> and <code>arm64</code> ✅
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
