# Function: <code>squashfs_copy_data</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline, Transformation ⚠️</summary>

```c
int squashfs_copy_data(void *buffer, struct squashfs_cache_entry *entry, int offset, int length);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/squashfs/cache.c (ffffffff81321a03)
Location: fs/squashfs/cache.c:306
Inline: True
Inline callers:
  - fs/squashfs/cache.c:squashfs_read_metadata
Direct callers:
  - fs/squashfs/cache.c:squashfs_read_metadata
  - fs/squashfs/file.c:squashfs_copy_cache
  - fs/squashfs/symlink.c:squashfs_symlink_readpage
  - fs/squashfs/file_direct.c:squashfs_readpage_block
```
**Symbols:**

```
ffffffff813211b0-ffffffff8132129e: squashfs_copy_data.part.0 (STB_LOCAL)
ffffffff81321990-ffffffff813219b7: squashfs_copy_data (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline, Transformation ⚠️</summary>

```c
int squashfs_copy_data(void *buffer, struct squashfs_cache_entry *entry, int offset, int length);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/squashfs/cache.c (ffffffff81337893)
Location: fs/squashfs/cache.c:306
Inline: True
Inline callers:
  - fs/squashfs/cache.c:squashfs_read_metadata
Direct callers:
  - fs/squashfs/cache.c:squashfs_read_metadata
  - fs/squashfs/file.c:squashfs_copy_cache
  - fs/squashfs/symlink.c:squashfs_symlink_readpage
  - fs/squashfs/file_direct.c:squashfs_readpage_block
```
**Symbols:**

```
ffffffff81337060-ffffffff8133714e: squashfs_copy_data.part.0 (STB_LOCAL)
ffffffff81337820-ffffffff81337847: squashfs_copy_data (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline, Transformation ⚠️</summary>

```c
int squashfs_copy_data(void *buffer, struct squashfs_cache_entry *entry, int offset, int length);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/squashfs/cache.c (ffffffff8134c5d1)
Location: fs/squashfs/cache.c:306
Inline: True
Inline callers:
  - fs/squashfs/cache.c:squashfs_read_metadata
Direct callers:
  - fs/squashfs/cache.c:squashfs_read_metadata
  - fs/squashfs/file.c:squashfs_copy_cache
  - fs/squashfs/symlink.c:squashfs_symlink_readpage
  - fs/squashfs/file_direct.c:squashfs_readpage_block
```
**Symbols:**

```
ffffffff8134be20-ffffffff8134bf0e: squashfs_copy_data.part.1 (STB_LOCAL)
ffffffff8134c560-ffffffff8134c588: squashfs_copy_data (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline, Transformation ⚠️</summary>

```c
int squashfs_copy_data(void *buffer, struct squashfs_cache_entry *entry, int offset, int length);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/squashfs/cache.c (ffffffff81370c51)
Location: fs/squashfs/cache.c:306
Inline: True
Inline callers:
  - fs/squashfs/cache.c:squashfs_read_metadata
Direct callers:
  - fs/squashfs/cache.c:squashfs_read_metadata
  - fs/squashfs/file.c:squashfs_copy_cache
  - fs/squashfs/symlink.c:squashfs_symlink_readpage
  - fs/squashfs/file_direct.c:squashfs_readpage_block
```
**Symbols:**

```
ffffffff813704a0-ffffffff8137058e: squashfs_copy_data.part.1 (STB_LOCAL)
ffffffff81370be0-ffffffff81370c08: squashfs_copy_data (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline, Transformation ⚠️</summary>

```c
int squashfs_copy_data(void *buffer, struct squashfs_cache_entry *entry, int offset, int length);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/squashfs/cache.c (ffffffff8139f4df)
Location: fs/squashfs/cache.c:306
Inline: True
Inline callers:
  - fs/squashfs/cache.c:squashfs_read_metadata
Direct callers:
  - fs/squashfs/cache.c:squashfs_read_metadata
  - fs/squashfs/file.c:squashfs_fill_page
  - fs/squashfs/symlink.c:squashfs_symlink_readpage
```
**Symbols:**

```
ffffffff8139ec60-ffffffff8139ee1f: squashfs_copy_data.part.1 (STB_LOCAL)
ffffffff8139f3f0-ffffffff8139f417: squashfs_copy_data (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline, Transformation ⚠️</summary>

```c
int squashfs_copy_data(void *buffer, struct squashfs_cache_entry *entry, int offset, int length);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/squashfs/cache.c (ffffffff813b826f)
Location: fs/squashfs/cache.c:306
Inline: True
Inline callers:
  - fs/squashfs/cache.c:squashfs_read_metadata
Direct callers:
  - fs/squashfs/cache.c:squashfs_read_metadata
  - fs/squashfs/file.c:squashfs_fill_page
  - fs/squashfs/symlink.c:squashfs_symlink_readpage
```
**Symbols:**

```
ffffffff813b79f0-ffffffff813b7baf: squashfs_copy_data.part.1 (STB_LOCAL)
ffffffff813b8180-ffffffff813b81a7: squashfs_copy_data (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline, Transformation ⚠️</summary>

```c
int squashfs_copy_data(void *buffer, struct squashfs_cache_entry *entry, int offset, int length);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/squashfs/cache.c (ffffffff813e2a40)
Location: fs/squashfs/cache.c:293
Inline: True
Inline callers:
  - fs/squashfs/cache.c:squashfs_read_metadata
Direct callers:
  - fs/squashfs/cache.c:squashfs_read_metadata
  - fs/squashfs/file.c:squashfs_fill_page
  - fs/squashfs/symlink.c:squashfs_symlink_readpage
```
**Symbols:**

```
ffffffff813e21c0-ffffffff813e2379: squashfs_copy_data.part.0 (STB_LOCAL)
ffffffff813e2950-ffffffff813e2977: squashfs_copy_data (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline, Transformation ⚠️</summary>

```c
int squashfs_copy_data(void *buffer, struct squashfs_cache_entry *entry, int offset, int length);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/squashfs/cache.c (ffffffff813fca70)
Location: fs/squashfs/cache.c:293
Inline: True
Inline callers:
  - fs/squashfs/cache.c:squashfs_read_metadata
Direct callers:
  - fs/squashfs/cache.c:squashfs_read_metadata
  - fs/squashfs/file.c:squashfs_fill_page
  - fs/squashfs/symlink.c:squashfs_symlink_readpage
```
**Symbols:**

```
ffffffff813fc1f0-ffffffff813fc3a9: squashfs_copy_data.part.0 (STB_LOCAL)
ffffffff813fc980-ffffffff813fc9a7: squashfs_copy_data (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline, Transformation ⚠️</summary>

```c
int squashfs_copy_data(void *buffer, struct squashfs_cache_entry *entry, int offset, int length);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/squashfs/cache.c (ffffffff8144a3e0)
Location: fs/squashfs/cache.c:293
Inline: True
Inline callers:
  - fs/squashfs/cache.c:squashfs_read_metadata
Direct callers:
  - fs/squashfs/cache.c:squashfs_read_metadata
  - fs/squashfs/file.c:squashfs_fill_page
  - fs/squashfs/symlink.c:squashfs_symlink_readpage
```
**Symbols:**

```
ffffffff81449b50-ffffffff81449d0a: squashfs_copy_data.part.0 (STB_LOCAL)
ffffffff8144a2f0-ffffffff8144a317: squashfs_copy_data (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline, Transformation ⚠️</summary>

```c
int squashfs_copy_data(void *buffer, struct squashfs_cache_entry *entry, int offset, int length);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/squashfs/cache.c (ffffffff81466ad0)
Location: fs/squashfs/cache.c:293
Inline: True
Inline callers:
  - fs/squashfs/cache.c:squashfs_read_metadata
Direct callers:
  - fs/squashfs/cache.c:squashfs_read_metadata
  - fs/squashfs/file.c:squashfs_fill_page
  - fs/squashfs/symlink.c:squashfs_symlink_readpage
```
**Symbols:**

```
ffffffff81466270-ffffffff8146642a: squashfs_copy_data.part.0 (STB_LOCAL)
ffffffff814669e0-ffffffff81466a07: squashfs_copy_data (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
int squashfs_copy_data(void *buffer, struct squashfs_cache_entry *entry, int offset, int length);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/squashfs/cache.c (ffffffff8146bfb0)
Location: fs/squashfs/cache.c:293
Inline: True
Direct callers:
  - fs/squashfs/cache.c:squashfs_read_metadata
  - fs/squashfs/file.c:squashfs_fill_page
  - fs/squashfs/symlink.c:squashfs_symlink_readpage
```
**Symbols:**

```
ffffffff8146bfb0-ffffffff8146c119: squashfs_copy_data (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
int squashfs_copy_data(void *buffer, struct squashfs_cache_entry *entry, int offset, int length);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/squashfs/cache.c (ffffffff814c2810)
Location: fs/squashfs/cache.c:293
Inline: True
Direct callers:
  - fs/squashfs/cache.c:squashfs_read_metadata
  - fs/squashfs/file.c:squashfs_fill_page
  - fs/squashfs/symlink.c:squashfs_symlink_readpage
```
**Symbols:**

```
ffffffff814c2810-ffffffff814c2979: squashfs_copy_data (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int squashfs_copy_data(void *buffer, struct squashfs_cache_entry *entry, int offset, int length);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/squashfs/cache.c (ffffffff8154d320)
Location: fs/squashfs/cache.c:293
Inline: False
Direct callers:
  - fs/squashfs/cache.c:squashfs_read_metadata
  - fs/squashfs/file.c:squashfs_fill_page
  - fs/squashfs/symlink.c:squashfs_symlink_read_folio
```
**Symbols:**

```
ffffffff8154d320-ffffffff8154d47d: squashfs_copy_data (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int squashfs_copy_data(void *buffer, struct squashfs_cache_entry *entry, int offset, int length);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/squashfs/cache.c (ffffffff815ed2a0)
Location: fs/squashfs/cache.c:293
Inline: False
Direct callers:
  - fs/squashfs/cache.c:squashfs_read_metadata
  - fs/squashfs/file.c:squashfs_fill_page
  - fs/squashfs/symlink.c:squashfs_symlink_read_folio
```
**Symbols:**

```
ffffffff815ed2a0-ffffffff815ed3fd: squashfs_copy_data (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int squashfs_copy_data(void *buffer, struct squashfs_cache_entry *entry, int offset, int length);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/squashfs/cache.c (ffffffff816251d0)
Location: fs/squashfs/cache.c:293
Inline: False
Direct callers:
  - fs/squashfs/cache.c:squashfs_read_metadata
  - fs/squashfs/file.c:squashfs_fill_page
  - fs/squashfs/symlink.c:squashfs_symlink_read_folio
```
**Symbols:**

```
ffffffff816251d0-ffffffff816253b2: squashfs_copy_data (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int squashfs_copy_data(void *buffer, struct squashfs_cache_entry *entry, int offset, int length);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/squashfs/cache.c (ffffffff8165e2e0)
Location: fs/squashfs/cache.c:293
Inline: False
Direct callers:
  - fs/squashfs/cache.c:squashfs_read_metadata
  - fs/squashfs/file.c:squashfs_fill_page
  - fs/squashfs/symlink.c:squashfs_symlink_read_folio
```
**Symbols:**

```
ffffffff8165e2e0-ffffffff8165e4c2: squashfs_copy_data (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Selective Inline, Transformation ⚠️</summary>

```c
int squashfs_copy_data(void *buffer, struct squashfs_cache_entry *entry, int offset, int length);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/squashfs/cache.c (ffff8000104da94c)
Location: fs/squashfs/cache.c:293
Inline: True
Inline callers:
  - fs/squashfs/cache.c:squashfs_read_metadata
Direct callers:
  - fs/squashfs/cache.c:squashfs_read_metadata
  - fs/squashfs/file.c:squashfs_fill_page
  - fs/squashfs/symlink.c:squashfs_symlink_readpage
```
**Symbols:**

```
ffff8000104d9f88-ffff8000104da0b0: squashfs_copy_data.part.0 (STB_LOCAL)
ffff8000104da830-ffff8000104da8a8: squashfs_copy_data (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline, Transformation ⚠️</summary>

```c
int squashfs_copy_data(void *buffer, struct squashfs_cache_entry *entry, int offset, int length);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/squashfs/cache.c (c069c030)
Location: fs/squashfs/cache.c:293
Inline: True
Inline callers:
  - fs/squashfs/cache.c:squashfs_read_metadata
Direct callers:
  - fs/squashfs/cache.c:squashfs_read_metadata
  - fs/squashfs/file.c:squashfs_fill_page
  - fs/squashfs/symlink.c:squashfs_symlink_readpage
```
**Symbols:**

```
c069b798-c069b87c: squashfs_copy_data.part.0 (STB_LOCAL)
c069bf24-c069bf78: squashfs_copy_data (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline, Transformation ⚠️</summary>

```c
int squashfs_copy_data(void *buffer, struct squashfs_cache_entry *entry, int offset, int length);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/squashfs/cache.c (c00000000061563c)
Location: fs/squashfs/cache.c:293
Inline: True
Inline callers:
  - fs/squashfs/cache.c:squashfs_read_metadata
Direct callers:
  - fs/squashfs/cache.c:squashfs_read_metadata
  - fs/squashfs/file.c:squashfs_fill_page
  - fs/squashfs/symlink.c:squashfs_symlink_readpage
```
**Symbols:**

```
c000000000614960-c000000000614b10: squashfs_copy_data.part.0 (STB_LOCAL)
c000000000615500-c00000000061555c: squashfs_copy_data (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline, Transformation ⚠️</summary>

```c
int squashfs_copy_data(void *buffer, struct squashfs_cache_entry *entry, int offset, int length);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/squashfs/cache.c (ffffffe00034f886)
Location: fs/squashfs/cache.c:293
Inline: True
Inline callers:
  - fs/squashfs/cache.c:squashfs_read_metadata
Direct callers:
  - fs/squashfs/cache.c:squashfs_read_metadata
  - fs/squashfs/file.c:squashfs_fill_page
  - fs/squashfs/symlink.c:squashfs_symlink_readpage
```
**Symbols:**

```
ffffffe00034ef9a-ffffffe00034f092: squashfs_copy_data.part.0 (STB_LOCAL)
ffffffe00034f7ca-ffffffe00034f838: squashfs_copy_data (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Selective Inline, Transformation ⚠️</summary>

```c
int squashfs_copy_data(void *buffer, struct squashfs_cache_entry *entry, int offset, int length);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/squashfs/cache.c (ffffffff813f5050)
Location: fs/squashfs/cache.c:293
Inline: True
Inline callers:
  - fs/squashfs/cache.c:squashfs_read_metadata
Direct callers:
  - fs/squashfs/cache.c:squashfs_read_metadata
  - fs/squashfs/file.c:squashfs_fill_page
  - fs/squashfs/symlink.c:squashfs_symlink_readpage
```
**Symbols:**

```
ffffffff813f47d0-ffffffff813f4989: squashfs_copy_data.part.0 (STB_LOCAL)
ffffffff813f4f60-ffffffff813f4f87: squashfs_copy_data (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline, Transformation ⚠️</summary>

```c
int squashfs_copy_data(void *buffer, struct squashfs_cache_entry *entry, int offset, int length);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/squashfs/cache.c (ffffffff813e5ad0)
Location: fs/squashfs/cache.c:293
Inline: True
Inline callers:
  - fs/squashfs/cache.c:squashfs_read_metadata
Direct callers:
  - fs/squashfs/cache.c:squashfs_read_metadata
  - fs/squashfs/file.c:squashfs_fill_page
  - fs/squashfs/symlink.c:squashfs_symlink_readpage
```
**Symbols:**

```
ffffffff813e5250-ffffffff813e5409: squashfs_copy_data.part.0 (STB_LOCAL)
ffffffff813e59e0-ffffffff813e5a07: squashfs_copy_data (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline, Transformation ⚠️</summary>

```c
int squashfs_copy_data(void *buffer, struct squashfs_cache_entry *entry, int offset, int length);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/squashfs/cache.c (ffffffff813f23d0)
Location: fs/squashfs/cache.c:293
Inline: True
Inline callers:
  - fs/squashfs/cache.c:squashfs_read_metadata
Direct callers:
  - fs/squashfs/cache.c:squashfs_read_metadata
  - fs/squashfs/file.c:squashfs_fill_page
  - fs/squashfs/symlink.c:squashfs_symlink_readpage
```
**Symbols:**

```
ffffffff813f1b50-ffffffff813f1d09: squashfs_copy_data.part.0 (STB_LOCAL)
ffffffff813f22e0-ffffffff813f2307: squashfs_copy_data (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline, Transformation ⚠️</summary>

```c
int squashfs_copy_data(void *buffer, struct squashfs_cache_entry *entry, int offset, int length);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/squashfs/cache.c (ffffffff81407fc0)
Location: fs/squashfs/cache.c:293
Inline: True
Inline callers:
  - fs/squashfs/cache.c:squashfs_read_metadata
Direct callers:
  - fs/squashfs/cache.c:squashfs_read_metadata
  - fs/squashfs/file.c:squashfs_fill_page
  - fs/squashfs/symlink.c:squashfs_symlink_readpage
```
**Symbols:**

```
ffffffff81407750-ffffffff81407909: squashfs_copy_data.part.0 (STB_LOCAL)
ffffffff81407ed0-ffffffff81407ef7: squashfs_copy_data (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
