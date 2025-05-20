# Function: <code>filemap_fdatawait_range</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int filemap_fdatawait_range(struct address_space *mapping, loff_t start_byte, loff_t end_byte);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/filemap.c (ffffffff8118cb60)
Location: mm/filemap.c:385
Inline: False
Direct callers:
  - fs/sync.c:SyS_sync_file_range2
  - fs/sync.c:SyS_sync_file_range2
  - fs/fat/file.c:fat_setattr
```
**Symbols:**

```
ffffffff8118cb60-ffffffff8118cb8a: filemap_fdatawait_range (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int filemap_fdatawait_range(struct address_space *mapping, loff_t start_byte, loff_t end_byte);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/filemap.c (ffffffff8119fb50)
Location: mm/filemap.c:464
Inline: False
Direct callers:
  - fs/sync.c:SyS_sync_file_range2
  - fs/sync.c:SyS_sync_file_range2
  - fs/fat/file.c:fat_cont_expand
```
**Symbols:**

```
ffffffff8119fb50-ffffffff8119fb7a: filemap_fdatawait_range (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int filemap_fdatawait_range(struct address_space *mapping, loff_t start_byte, loff_t end_byte);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/filemap.c (ffffffff811afdb0)
Location: mm/filemap.c:429
Inline: False
Direct callers:
  - fs/sync.c:SyS_sync_file_range2
  - fs/sync.c:SyS_sync_file_range2
  - fs/fat/file.c:fat_cont_expand
```
**Symbols:**

```
ffffffff811afdb0-ffffffff811afdda: filemap_fdatawait_range (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
int filemap_fdatawait_range(struct address_space *mapping, loff_t start_byte, loff_t end_byte);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/filemap.c (ffffffff811b6e59)
Location: mm/filemap.c:461
Inline: True
Inline callers:
  - mm/filemap.c:filemap_fdatawait
Direct callers:
  - fs/sync.c:SyS_sync_file_range2
  - fs/sync.c:SyS_sync_file_range2
  - fs/fat/file.c:fat_cont_expand
```
**Symbols:**

```
ffffffff811b6e20-ffffffff811b6e3d: filemap_fdatawait_range (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
int filemap_fdatawait_range(struct address_space *mapping, loff_t start_byte, loff_t end_byte);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/filemap.c (ffffffff811cafa0)
Location: mm/filemap.c:556
Inline: True
Direct callers:
  - fs/fs-writeback.c:__writeback_single_inode
  - fs/fat/file.c:fat_cont_expand
```
**Symbols:**

```
ffffffff811cafa0-ffffffff811cafbd: filemap_fdatawait_range (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
int filemap_fdatawait_range(struct address_space *mapping, loff_t start_byte, loff_t end_byte);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/filemap.c (ffffffff811ec200)
Location: mm/filemap.c:556
Inline: True
Direct callers:
  - fs/fs-writeback.c:__writeback_single_inode
  - fs/fat/file.c:fat_cont_expand
```
**Symbols:**

```
ffffffff811ec200-ffffffff811ec21d: filemap_fdatawait_range (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
int filemap_fdatawait_range(struct address_space *mapping, loff_t start_byte, loff_t end_byte);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/filemap.c (ffffffff811fe560)
Location: mm/filemap.c:533
Inline: True
Direct callers:
  - fs/fs-writeback.c:__writeback_single_inode
  - fs/fat/file.c:fat_cont_expand
```
**Symbols:**

```
ffffffff811fe560-ffffffff811fe57d: filemap_fdatawait_range (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
int filemap_fdatawait_range(struct address_space *mapping, loff_t start_byte, loff_t end_byte);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/filemap.c (ffffffff81213620)
Location: mm/filemap.c:544
Inline: True
Direct callers:
  - fs/fs-writeback.c:__writeback_single_inode
  - fs/fat/file.c:fat_cont_expand
```
**Symbols:**

```
ffffffff81213620-ffffffff8121363f: filemap_fdatawait_range (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
int filemap_fdatawait_range(struct address_space *mapping, loff_t start_byte, loff_t end_byte);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/filemap.c (ffffffff81220df0)
Location: mm/filemap.c:550
Inline: True
Direct callers:
  - fs/fs-writeback.c:__writeback_single_inode
  - fs/fat/file.c:fat_cont_expand
```
**Symbols:**

```
ffffffff81220df0-ffffffff81220e0f: filemap_fdatawait_range (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
int filemap_fdatawait_range(struct address_space *mapping, loff_t start_byte, loff_t end_byte);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/filemap.c (ffffffff8124f4d0)
Location: mm/filemap.c:550
Inline: True
Direct callers:
  - fs/fs-writeback.c:__writeback_single_inode
  - fs/fat/file.c:fat_cont_expand
```
**Symbols:**

```
ffffffff8124f4d0-ffffffff8124f51a: filemap_fdatawait_range (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
int filemap_fdatawait_range(struct address_space *mapping, loff_t start_byte, loff_t end_byte);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/filemap.c (ffffffff81259af0)
Location: mm/filemap.c:551
Inline: True
Direct callers:
  - fs/fs-writeback.c:__writeback_single_inode
  - fs/fat/file.c:fat_cont_expand
```
**Symbols:**

```
ffffffff81259af0-ffffffff81259b3a: filemap_fdatawait_range (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
int filemap_fdatawait_range(struct address_space *mapping, loff_t start_byte, loff_t end_byte);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/filemap.c (ffffffff8125dd60)
Location: mm/filemap.c:542
Inline: True
Direct callers:
  - fs/fs-writeback.c:__writeback_single_inode
  - fs/fat/file.c:fat_cont_expand
```
**Symbols:**

```
ffffffff8125dd60-ffffffff8125ddaa: filemap_fdatawait_range (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
int filemap_fdatawait_range(struct address_space *mapping, loff_t start_byte, loff_t end_byte);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/filemap.c (ffffffff81299a0a)
Location: mm/filemap.c:560
Inline: True
Direct callers:
  - fs/fs-writeback.c:__writeback_single_inode
  - fs/fat/file.c:fat_cont_expand
```
**Symbols:**

```
ffffffff8129a470-ffffffff8129a4c6: filemap_fdatawait_range (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
int filemap_fdatawait_range(struct address_space *mapping, loff_t start_byte, loff_t end_byte);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/filemap.c (ffffffff812f0260)
Location: mm/filemap.c:548
Inline: True
Direct callers:
  - fs/fs-writeback.c:__writeback_single_inode
  - fs/fat/file.c:fat_cont_expand
```
**Symbols:**

```
ffffffff812f0260-ffffffff812f02c0: filemap_fdatawait_range (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int filemap_fdatawait_range(struct address_space *mapping, loff_t start_byte, loff_t end_byte);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/filemap.c (ffffffff8135af50)
Location: mm/filemap.c:545
Inline: False
Direct callers:
  - fs/fs-writeback.c:__writeback_single_inode
  - fs/fat/file.c:fat_cont_expand
```
**Symbols:**

```
ffffffff8135af50-ffffffff8135af7a: filemap_fdatawait_range (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int filemap_fdatawait_range(struct address_space *mapping, loff_t start_byte, loff_t end_byte);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/filemap.c (ffffffff8138dc50)
Location: mm/filemap.c:552
Inline: False
Direct callers:
  - fs/fs-writeback.c:__writeback_single_inode
  - fs/fat/file.c:fat_cont_expand
```
**Symbols:**

```
ffffffff8138dc50-ffffffff8138dc7a: filemap_fdatawait_range (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int filemap_fdatawait_range(struct address_space *mapping, loff_t start_byte, loff_t end_byte);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/filemap.c (ffffffff813b7390)
Location: mm/filemap.c:547
Inline: False
Direct callers:
  - fs/fs-writeback.c:__writeback_single_inode
  - fs/fat/file.c:fat_cont_expand
```
**Symbols:**

```
ffffffff813b7390-ffffffff813b73ba: filemap_fdatawait_range (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Selective Inline ⚠️</summary>

```c
int filemap_fdatawait_range(struct address_space *mapping, loff_t start_byte, loff_t end_byte);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/filemap.c (ffff8000102afc48)
Location: mm/filemap.c:550
Inline: True
Direct callers:
  - fs/fs-writeback.c:__writeback_single_inode
  - fs/fat/file.c:fat_cont_expand
```
**Symbols:**

```
ffff8000102afc48-ffff8000102afc94: filemap_fdatawait_range (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
int filemap_fdatawait_range(struct address_space *mapping, loff_t start_byte, loff_t end_byte);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/filemap.c (c04dada0)
Location: mm/filemap.c:550
Inline: True
Direct callers:
  - fs/fs-writeback.c:__writeback_single_inode
  - fs/fat/file.c:fat_cont_expand
```
**Symbols:**

```
c04dada0-c04dadd8: filemap_fdatawait_range (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
int filemap_fdatawait_range(struct address_space *mapping, loff_t start_byte, loff_t end_byte);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/filemap.c (c000000000362700)
Location: mm/filemap.c:550
Inline: True
Direct callers:
  - fs/fs-writeback.c:__writeback_single_inode
  - fs/fat/file.c:fat_cont_expand
```
**Symbols:**

```
c000000000362700-c000000000362740: filemap_fdatawait_range (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int filemap_fdatawait_range(struct address_space *mapping, loff_t start_byte, loff_t end_byte);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/filemap.c (ffffffe0001d459a)
Location: mm/filemap.c:550
Inline: False
Direct callers:
  - fs/fs-writeback.c:__writeback_single_inode
  - fs/fat/file.c:fat_cont_expand
```
**Symbols:**

```
ffffffe0001d459a-ffffffe0001d4608: filemap_fdatawait_range (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Selective Inline ⚠️</summary>

```c
int filemap_fdatawait_range(struct address_space *mapping, loff_t start_byte, loff_t end_byte);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/filemap.c (ffffffff81219440)
Location: mm/filemap.c:550
Inline: True
Direct callers:
  - fs/fs-writeback.c:__writeback_single_inode
  - fs/fat/file.c:fat_cont_expand
```
**Symbols:**

```
ffffffff81219440-ffffffff8121945f: filemap_fdatawait_range (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
int filemap_fdatawait_range(struct address_space *mapping, loff_t start_byte, loff_t end_byte);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/filemap.c (ffffffff8120c650)
Location: mm/filemap.c:550
Inline: True
Direct callers:
  - fs/fs-writeback.c:__writeback_single_inode
  - fs/fat/file.c:fat_cont_expand
```
**Symbols:**

```
ffffffff8120c650-ffffffff8120c66f: filemap_fdatawait_range (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
int filemap_fdatawait_range(struct address_space *mapping, loff_t start_byte, loff_t end_byte);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/filemap.c (ffffffff812171e0)
Location: mm/filemap.c:550
Inline: True
Direct callers:
  - fs/fs-writeback.c:__writeback_single_inode
  - fs/fat/file.c:fat_cont_expand
```
**Symbols:**

```
ffffffff812171e0-ffffffff812171ff: filemap_fdatawait_range (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
int filemap_fdatawait_range(struct address_space *mapping, loff_t start_byte, loff_t end_byte);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/filemap.c (ffffffff81226270)
Location: mm/filemap.c:550
Inline: True
Direct callers:
  - fs/fs-writeback.c:__writeback_single_inode
  - fs/fat/file.c:fat_cont_expand
```
**Symbols:**

```
ffffffff81226270-ffffffff8122628f: filemap_fdatawait_range (STB_GLOBAL)
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
