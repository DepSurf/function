# Function: <code>squashfs_get_datablock</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
struct squashfs_cache_entry *squashfs_get_datablock(struct super_block *sb, u64 start_block, int length);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/squashfs/cache.c (ffffffff81321b30)
Location: fs/squashfs/cache.c:404
Inline: False
Direct callers:
  - fs/squashfs/file_direct.c:squashfs_readpage_block
```
**Symbols:**

```
ffffffff81321b30-ffffffff81321b53: squashfs_get_datablock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
struct squashfs_cache_entry *squashfs_get_datablock(struct super_block *sb, u64 start_block, int length);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/squashfs/cache.c (ffffffff813379c0)
Location: fs/squashfs/cache.c:404
Inline: False
Direct callers:
  - fs/squashfs/file_direct.c:squashfs_readpage_block
```
**Symbols:**

```
ffffffff813379c0-ffffffff813379e3: squashfs_get_datablock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
struct squashfs_cache_entry *squashfs_get_datablock(struct super_block *sb, u64 start_block, int length);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/squashfs/cache.c (ffffffff8134c6d0)
Location: fs/squashfs/cache.c:404
Inline: False
Direct callers:
  - fs/squashfs/file_direct.c:squashfs_readpage_block
```
**Symbols:**

```
ffffffff8134c6d0-ffffffff8134c6f3: squashfs_get_datablock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
struct squashfs_cache_entry *squashfs_get_datablock(struct super_block *sb, u64 start_block, int length);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/squashfs/cache.c (ffffffff81370d50)
Location: fs/squashfs/cache.c:404
Inline: False
Direct callers:
  - fs/squashfs/file_direct.c:squashfs_readpage_block
```
**Symbols:**

```
ffffffff81370d50-ffffffff81370d73: squashfs_get_datablock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
struct squashfs_cache_entry *squashfs_get_datablock(struct super_block *sb, u64 start_block, int length);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/squashfs/cache.c (ffffffff8139f590)
Location: fs/squashfs/cache.c:407
Inline: False
Direct callers:
  - fs/squashfs/file_direct.c:squashfs_readpage_block
```
**Symbols:**

```
ffffffff8139f590-ffffffff8139f5b3: squashfs_get_datablock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
struct squashfs_cache_entry *squashfs_get_datablock(struct super_block *sb, u64 start_block, int length);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/squashfs/cache.c (ffffffff813b8320)
Location: fs/squashfs/cache.c:407
Inline: False
Direct callers:
  - fs/squashfs/file_direct.c:squashfs_readpage_block
```
**Symbols:**

```
ffffffff813b8320-ffffffff813b8343: squashfs_get_datablock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
struct squashfs_cache_entry *squashfs_get_datablock(struct super_block *sb, u64 start_block, int length);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/squashfs/cache.c (ffffffff813e2b00)
Location: fs/squashfs/cache.c:394
Inline: False
Direct callers:
  - fs/squashfs/file_direct.c:squashfs_readpage_block
```
**Symbols:**

```
ffffffff813e2b00-ffffffff813e2b23: squashfs_get_datablock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
struct squashfs_cache_entry *squashfs_get_datablock(struct super_block *sb, u64 start_block, int length);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/squashfs/cache.c (ffffffff813fcb30)
Location: fs/squashfs/cache.c:394
Inline: False
Direct callers:
  - fs/squashfs/file_direct.c:squashfs_readpage_block
```
**Symbols:**

```
ffffffff813fcb30-ffffffff813fcb53: squashfs_get_datablock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
struct squashfs_cache_entry *squashfs_get_datablock(struct super_block *sb, u64 start_block, int length);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/squashfs/cache.c (ffffffff8144a4a0)
Location: fs/squashfs/cache.c:394
Inline: False
Direct callers:
  - fs/squashfs/file_direct.c:squashfs_read_cache
```
**Symbols:**

```
ffffffff8144a4a0-ffffffff8144a4c3: squashfs_get_datablock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
struct squashfs_cache_entry *squashfs_get_datablock(struct super_block *sb, u64 start_block, int length);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/squashfs/cache.c (ffffffff81466b90)
Location: fs/squashfs/cache.c:394
Inline: False
Direct callers:
  - fs/squashfs/file_direct.c:squashfs_read_cache
```
**Symbols:**

```
ffffffff81466b90-ffffffff81466bb3: squashfs_get_datablock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
struct squashfs_cache_entry *squashfs_get_datablock(struct super_block *sb, u64 start_block, int length);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/squashfs/cache.c (ffffffff8146c2a0)
Location: fs/squashfs/cache.c:394
Inline: False
Direct callers:
  - fs/squashfs/file_direct.c:squashfs_readpage_block
```
**Symbols:**

```
ffffffff8146c2a0-ffffffff8146c2c3: squashfs_get_datablock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
struct squashfs_cache_entry *squashfs_get_datablock(struct super_block *sb, u64 start_block, int length);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/squashfs/cache.c (ffffffff814c2b00)
Location: fs/squashfs/cache.c:394
Inline: False
Direct callers:
  - fs/squashfs/file_direct.c:squashfs_readpage_block
```
**Symbols:**

```
ffffffff814c2b00-ffffffff814c2b23: squashfs_get_datablock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
struct squashfs_cache_entry *squashfs_get_datablock(struct super_block *sb, u64 start_block, int length);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/squashfs/cache.c (ffffffff8154d620)
Location: fs/squashfs/cache.c:394
Inline: False
Direct callers:
  - fs/squashfs/file_direct.c:squashfs_readpage_block
```
**Symbols:**

```
ffffffff8154d620-ffffffff8154d64f: squashfs_get_datablock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
struct squashfs_cache_entry *squashfs_get_datablock(struct super_block *sb, u64 start_block, int length);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/squashfs/cache.c (ffffffff815ed5d0)
Location: fs/squashfs/cache.c:394
Inline: False
```
**Symbols:**

```
ffffffff815ed5d0-ffffffff815ed5ff: squashfs_get_datablock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
struct squashfs_cache_entry *squashfs_get_datablock(struct super_block *sb, u64 start_block, int length);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/squashfs/cache.c (ffffffff81625590)
Location: fs/squashfs/cache.c:394
Inline: False
```
**Symbols:**

```
ffffffff81625590-ffffffff816255bf: squashfs_get_datablock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
struct squashfs_cache_entry *squashfs_get_datablock(struct super_block *sb, u64 start_block, int length);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/squashfs/cache.c (ffffffff8165e6a0)
Location: fs/squashfs/cache.c:394
Inline: False
```
**Symbols:**

```
ffffffff8165e6a0-ffffffff8165e6cf: squashfs_get_datablock (STB_GLOBAL)
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
struct squashfs_cache_entry *squashfs_get_datablock(struct super_block *sb, u64 start_block, int length);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/squashfs/cache.c (ffff8000104daa80)
Location: fs/squashfs/cache.c:394
Inline: False
Direct callers:
  - fs/squashfs/file_direct.c:squashfs_readpage_block
```
**Symbols:**

```
ffff8000104daa80-ffff8000104daacc: squashfs_get_datablock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
struct squashfs_cache_entry *squashfs_get_datablock(struct super_block *sb, u64 start_block, int length);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/squashfs/cache.c (c069c10c)
Location: fs/squashfs/cache.c:394
Inline: False
Direct callers:
  - fs/squashfs/file_direct.c:squashfs_readpage_block
```
**Symbols:**

```
c069c10c-c069c140: squashfs_get_datablock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
struct squashfs_cache_entry *squashfs_get_datablock(struct super_block *sb, u64 start_block, int length);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/squashfs/cache.c (c0000000006157c0)
Location: fs/squashfs/cache.c:394
Inline: False
Direct callers:
  - fs/squashfs/file_direct.c:squashfs_readpage_block
```
**Symbols:**

```
c0000000006157c0-c0000000006157e4: squashfs_get_datablock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
struct squashfs_cache_entry *squashfs_get_datablock(struct super_block *sb, u64 start_block, int length);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/squashfs/cache.c (ffffffe00034f99a)
Location: fs/squashfs/cache.c:394
Inline: False
Direct callers:
  - fs/squashfs/file_direct.c:squashfs_readpage_block
```
**Symbols:**

```
ffffffe00034f99a-ffffffe00034f9da: squashfs_get_datablock (STB_GLOBAL)
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
struct squashfs_cache_entry *squashfs_get_datablock(struct super_block *sb, u64 start_block, int length);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/squashfs/cache.c (ffffffff813f5110)
Location: fs/squashfs/cache.c:394
Inline: False
Direct callers:
  - fs/squashfs/file_direct.c:squashfs_readpage_block
```
**Symbols:**

```
ffffffff813f5110-ffffffff813f5133: squashfs_get_datablock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
struct squashfs_cache_entry *squashfs_get_datablock(struct super_block *sb, u64 start_block, int length);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/squashfs/cache.c (ffffffff813e5b90)
Location: fs/squashfs/cache.c:394
Inline: False
Direct callers:
  - fs/squashfs/file_direct.c:squashfs_readpage_block
```
**Symbols:**

```
ffffffff813e5b90-ffffffff813e5bb3: squashfs_get_datablock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
struct squashfs_cache_entry *squashfs_get_datablock(struct super_block *sb, u64 start_block, int length);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/squashfs/cache.c (ffffffff813f2490)
Location: fs/squashfs/cache.c:394
Inline: False
Direct callers:
  - fs/squashfs/file_direct.c:squashfs_readpage_block
```
**Symbols:**

```
ffffffff813f2490-ffffffff813f24b3: squashfs_get_datablock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
struct squashfs_cache_entry *squashfs_get_datablock(struct super_block *sb, u64 start_block, int length);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/squashfs/cache.c (ffffffff81408080)
Location: fs/squashfs/cache.c:394
Inline: False
Direct callers:
  - fs/squashfs/file_direct.c:squashfs_readpage_block
```
**Symbols:**

```
ffffffff81408080-ffffffff814080a3: squashfs_get_datablock (STB_GLOBAL)
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
