# Function: <code>sync_mapping_buffers</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int sync_mapping_buffers(struct address_space *mapping);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/buffer.c (ffffffff81246500)
Location: fs/buffer.c:574
Inline: False
Direct callers:
  - fs/libfs.c:__generic_file_fsync
  - fs/ext4/fsync.c:ext4_sync_file
  - fs/fat/file.c:fat_file_fsync
  - fs/fat/file.c:fat_setattr
```
**Symbols:**

```
ffffffff81246500-ffffffff81246818: sync_mapping_buffers (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int sync_mapping_buffers(struct address_space *mapping);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/buffer.c (ffffffff8126f440)
Location: fs/buffer.c:568
Inline: False
Direct callers:
  - fs/libfs.c:__generic_file_fsync
  - fs/ext4/fsync.c:ext4_sync_file
  - fs/fat/file.c:fat_cont_expand
  - fs/fat/file.c:fat_file_fsync
```
**Symbols:**

```
ffffffff8126f440-ffffffff8126f776: sync_mapping_buffers (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int sync_mapping_buffers(struct address_space *mapping);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/buffer.c (ffffffff81282640)
Location: fs/buffer.c:569
Inline: False
Direct callers:
  - fs/libfs.c:__generic_file_fsync
  - fs/ext4/fsync.c:ext4_sync_file
  - fs/fat/file.c:fat_cont_expand
  - fs/fat/file.c:fat_file_fsync
```
**Symbols:**

```
ffffffff81282640-ffffffff81282976: sync_mapping_buffers (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int sync_mapping_buffers(struct address_space *mapping);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/buffer.c (ffffffff8128fcf0)
Location: fs/buffer.c:566
Inline: False
Direct callers:
  - fs/libfs.c:__generic_file_fsync
  - fs/ext4/fsync.c:ext4_sync_file
  - fs/fat/file.c:fat_cont_expand
  - fs/fat/file.c:fat_file_fsync
```
**Symbols:**

```
ffffffff8128fcf0-ffffffff81290077: sync_mapping_buffers (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int sync_mapping_buffers(struct address_space *mapping);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/buffer.c (ffffffff812b2a20)
Location: fs/buffer.c:545
Inline: False
Direct callers:
  - fs/libfs.c:__generic_file_fsync
  - fs/ext4/fsync.c:ext4_sync_file
  - fs/fat/file.c:fat_cont_expand
  - fs/fat/file.c:fat_file_fsync
```
**Symbols:**

```
ffffffff812b2a20-ffffffff812b2d81: sync_mapping_buffers (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int sync_mapping_buffers(struct address_space *mapping);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/buffer.c (ffffffff812da940)
Location: fs/buffer.c:514
Inline: False
Direct callers:
  - fs/libfs.c:__generic_file_fsync
  - fs/ext4/fsync.c:ext4_sync_file
  - fs/fat/file.c:fat_cont_expand
  - fs/fat/file.c:fat_file_fsync
```
**Symbols:**

```
ffffffff812da940-ffffffff812dac74: sync_mapping_buffers (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int sync_mapping_buffers(struct address_space *mapping);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/buffer.c (ffffffff812efe20)
Location: fs/buffer.c:515
Inline: False
Direct callers:
  - fs/libfs.c:__generic_file_fsync
  - fs/ext4/fsync.c:ext4_sync_file
  - fs/fat/file.c:fat_cont_expand
  - fs/fat/file.c:fat_file_fsync
```
**Symbols:**

```
ffffffff812efe20-ffffffff812f0157: sync_mapping_buffers (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int sync_mapping_buffers(struct address_space *mapping);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/buffer.c (ffffffff813116b0)
Location: fs/buffer.c:516
Inline: False
Direct callers:
  - fs/libfs.c:__generic_file_fsync
  - fs/ext4/fsync.c:ext4_sync_file
  - fs/fat/file.c:fat_cont_expand
  - fs/fat/file.c:fat_file_fsync
```
**Symbols:**

```
ffffffff813116b0-ffffffff81311a15: sync_mapping_buffers (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int sync_mapping_buffers(struct address_space *mapping);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/buffer.c (ffffffff81324690)
Location: fs/buffer.c:516
Inline: False
Direct callers:
  - fs/libfs.c:__generic_file_fsync
  - fs/ext4/fsync.c:ext4_sync_file
  - fs/fat/file.c:fat_cont_expand
  - fs/fat/file.c:fat_file_fsync
```
**Symbols:**

```
ffffffff81324690-ffffffff81324a3e: sync_mapping_buffers (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int sync_mapping_buffers(struct address_space *mapping);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/buffer.c (ffffffff8135b360)
Location: fs/buffer.c:542
Inline: False
Direct callers:
  - fs/libfs.c:__generic_file_fsync
  - fs/ext4/fsync.c:ext4_sync_file
  - fs/ext4/fsync.c:ext4_sync_parent
  - fs/fat/file.c:fat_cont_expand
  - fs/fat/file.c:fat_file_fsync
```
**Symbols:**

```
ffffffff8135b360-ffffffff8135b3a0: sync_mapping_buffers (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int sync_mapping_buffers(struct address_space *mapping);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/buffer.c (ffffffff81369480)
Location: fs/buffer.c:541
Inline: False
Direct callers:
  - fs/libfs.c:__generic_file_fsync
  - fs/ext4/fsync.c:ext4_sync_file
  - fs/ext4/fsync.c:ext4_sync_parent
  - fs/fat/file.c:fat_cont_expand
  - fs/fat/file.c:fat_file_fsync
```
**Symbols:**

```
ffffffff81369480-ffffffff813694c0: sync_mapping_buffers (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int sync_mapping_buffers(struct address_space *mapping);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/buffer.c (ffffffff81371860)
Location: fs/buffer.c:541
Inline: False
Direct callers:
  - fs/libfs.c:__generic_file_fsync
  - fs/ext4/fsync.c:ext4_sync_file
  - fs/ext4/fsync.c:ext4_sync_file
  - fs/fat/file.c:fat_cont_expand
  - fs/fat/file.c:fat_file_fsync
```
**Symbols:**

```
ffffffff81371860-ffffffff81371899: sync_mapping_buffers (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int sync_mapping_buffers(struct address_space *mapping);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/buffer.c (ffffffff813c0300)
Location: fs/buffer.c:541
Inline: False
Direct callers:
  - fs/libfs.c:__generic_file_fsync
  - fs/ext4/fsync.c:ext4_sync_file
  - fs/ext4/fsync.c:ext4_sync_file
  - fs/fat/file.c:fat_cont_expand
  - fs/fat/file.c:fat_file_fsync
```
**Symbols:**

```
ffffffff813c0300-ffffffff813c033c: sync_mapping_buffers (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int sync_mapping_buffers(struct address_space *mapping);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/buffer.c (ffffffff81444fb0)
Location: fs/buffer.c:541
Inline: False
Direct callers:
  - fs/libfs.c:__generic_file_fsync
  - fs/ext4/fsync.c:ext4_sync_file
  - fs/ext4/fsync.c:ext4_sync_file
  - fs/fat/file.c:fat_cont_expand
  - fs/fat/file.c:fat_file_fsync
```
**Symbols:**

```
ffffffff81444fb0-ffffffff81445010: sync_mapping_buffers (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int sync_mapping_buffers(struct address_space *mapping);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/buffer.c (ffffffff814d3e10)
Location: fs/buffer.c:541
Inline: False
Direct callers:
  - fs/libfs.c:__generic_file_fsync
  - fs/ext4/fsync.c:ext4_sync_file
  - fs/ext4/fsync.c:ext4_sync_file
  - fs/fat/file.c:fat_cont_expand
  - fs/fat/file.c:fat_file_fsync
```
**Symbols:**

```
ffffffff814d3e10-ffffffff814d3e70: sync_mapping_buffers (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
int sync_mapping_buffers(struct address_space *mapping);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/buffer.c (ffffffff8150bed2)
Location: fs/buffer.c:582
Inline: True
Inline callers:
  - fs/buffer.c:generic_buffers_fsync_noflush
Direct callers:
  - fs/libfs.c:__generic_file_fsync
  - fs/ext4/fsync.c:ext4_sync_file
  - fs/fat/file.c:fat_cont_expand
  - fs/fat/file.c:fat_file_fsync
```
**Symbols:**

```
ffffffff8150be20-ffffffff8150be80: sync_mapping_buffers (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
int sync_mapping_buffers(struct address_space *mapping);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/buffer.c (ffffffff81540ad2)
Location: fs/buffer.c:570
Inline: True
Inline callers:
  - fs/buffer.c:generic_buffers_fsync_noflush
Direct callers:
  - fs/libfs.c:__generic_file_fsync
  - fs/ext4/fsync.c:ext4_sync_file
  - fs/fat/file.c:fat_cont_expand
  - fs/fat/file.c:fat_file_fsync
```
**Symbols:**

```
ffffffff81540a20-ffffffff81540a80: sync_mapping_buffers (STB_GLOBAL)
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
int sync_mapping_buffers(struct address_space *mapping);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/buffer.c (ffff8000103ddab8)
Location: fs/buffer.c:516
Inline: False
Direct callers:
  - fs/libfs.c:__generic_file_fsync
  - fs/ext4/fsync.c:ext4_sync_file
  - fs/fat/file.c:fat_cont_expand
  - fs/fat/file.c:fat_file_fsync
```
**Symbols:**

```
ffff8000103ddab8-ffff8000103ddfa0: sync_mapping_buffers (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int sync_mapping_buffers(struct address_space *mapping);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/buffer.c (c05b72f8)
Location: fs/buffer.c:516
Inline: False
Direct callers:
  - fs/libfs.c:__generic_file_fsync
  - fs/ext4/fsync.c:ext4_sync_file
  - fs/fat/file.c:fat_cont_expand
  - fs/fat/file.c:fat_file_fsync
```
**Symbols:**

```
c05b72f8-c05b733c: sync_mapping_buffers (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int sync_mapping_buffers(struct address_space *mapping);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/buffer.c (c0000000004e35e0)
Location: fs/buffer.c:516
Inline: False
Direct callers:
  - fs/libfs.c:__generic_file_fsync
  - fs/ext4/fsync.c:ext4_sync_file
  - fs/fat/file.c:fat_cont_expand
  - fs/fat/file.c:fat_file_fsync
```
**Symbols:**

```
c0000000004e35e0-c0000000004e3c18: sync_mapping_buffers (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int sync_mapping_buffers(struct address_space *mapping);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/buffer.c (ffffffe0002959e8)
Location: fs/buffer.c:516
Inline: False
Direct callers:
  - fs/libfs.c:__generic_file_fsync
  - fs/ext4/fsync.c:ext4_sync_file
  - fs/fat/file.c:fat_cont_expand
  - fs/fat/file.c:fat_file_fsync
```
**Symbols:**

```
ffffffe0002959e8-ffffffe000295e18: sync_mapping_buffers (STB_GLOBAL)
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
int sync_mapping_buffers(struct address_space *mapping);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/buffer.c (ffffffff8131cc70)
Location: fs/buffer.c:516
Inline: False
Direct callers:
  - fs/libfs.c:__generic_file_fsync
  - fs/ext4/fsync.c:ext4_sync_file
  - fs/fat/file.c:fat_cont_expand
  - fs/fat/file.c:fat_file_fsync
```
**Symbols:**

```
ffffffff8131cc70-ffffffff8131d01e: sync_mapping_buffers (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int sync_mapping_buffers(struct address_space *mapping);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/buffer.c (ffffffff8130d810)
Location: fs/buffer.c:516
Inline: False
Direct callers:
  - fs/libfs.c:__generic_file_fsync
  - fs/ext4/fsync.c:ext4_sync_file
  - fs/fat/file.c:fat_cont_expand
  - fs/fat/file.c:fat_file_fsync
```
**Symbols:**

```
ffffffff8130d810-ffffffff8130dbbe: sync_mapping_buffers (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int sync_mapping_buffers(struct address_space *mapping);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/buffer.c (ffffffff8131a740)
Location: fs/buffer.c:516
Inline: False
Direct callers:
  - fs/libfs.c:__generic_file_fsync
  - fs/ext4/fsync.c:ext4_sync_file
  - fs/fat/file.c:fat_cont_expand
  - fs/fat/file.c:fat_file_fsync
```
**Symbols:**

```
ffffffff8131a740-ffffffff8131aaee: sync_mapping_buffers (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int sync_mapping_buffers(struct address_space *mapping);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/buffer.c (ffffffff8132c440)
Location: fs/buffer.c:516
Inline: False
Direct callers:
  - fs/libfs.c:__generic_file_fsync
  - fs/ext4/fsync.c:ext4_sync_file
  - fs/fat/file.c:fat_cont_expand
  - fs/fat/file.c:fat_file_fsync
```
**Symbols:**

```
ffffffff8132c440-ffffffff8132c7a4: sync_mapping_buffers (STB_GLOBAL)
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
