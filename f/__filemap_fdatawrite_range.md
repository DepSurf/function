# Function: <code>__filemap_fdatawrite_range</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int __filemap_fdatawrite_range(struct address_space *mapping, loff_t start, loff_t end, int sync_mode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/filemap.c (ffffffff8118e850)
Location: mm/filemap.c:282
Inline: False
Direct callers:
  - mm/filemap.c:filemap_flush
  - mm/filemap.c:filemap_fdatawrite_range
  - fs/sync.c:SyS_sync_file_range2
```
**Symbols:**

```
ffffffff8118e850-ffffffff8118e949: __filemap_fdatawrite_range (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int __filemap_fdatawrite_range(struct address_space *mapping, loff_t start, loff_t end, int sync_mode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/filemap.c (ffffffff811a23e0)
Location: mm/filemap.c:361
Inline: False
Direct callers:
  - mm/filemap.c:filemap_flush
  - mm/filemap.c:filemap_fdatawrite_range
  - mm/fadvise.c:SyS_fadvise64
  - fs/sync.c:SyS_sync_file_range2
```
**Symbols:**

```
ffffffff811a23e0-ffffffff811a24df: __filemap_fdatawrite_range (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int __filemap_fdatawrite_range(struct address_space *mapping, loff_t start, loff_t end, int sync_mode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/filemap.c (ffffffff811b2220)
Location: mm/filemap.c:326
Inline: False
Direct callers:
  - mm/filemap.c:filemap_flush
  - mm/filemap.c:filemap_fdatawrite_range
  - mm/fadvise.c:SyS_fadvise64
  - fs/sync.c:SyS_sync_file_range2
```
**Symbols:**

```
ffffffff811b2220-ffffffff811b231f: __filemap_fdatawrite_range (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int __filemap_fdatawrite_range(struct address_space *mapping, loff_t start, loff_t end, int sync_mode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/filemap.c (ffffffff811b8ea0)
Location: mm/filemap.c:330
Inline: False
Direct callers:
  - mm/filemap.c:file_write_and_wait_range
  - mm/filemap.c:filemap_flush
  - mm/filemap.c:filemap_fdatawrite_range
  - mm/fadvise.c:SyS_fadvise64
  - fs/sync.c:SyS_sync_file_range2
```
**Symbols:**

```
ffffffff811b8ea0-ffffffff811b8f91: __filemap_fdatawrite_range (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int __filemap_fdatawrite_range(struct address_space *mapping, loff_t start, loff_t end, int sync_mode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/filemap.c (ffffffff811cd7a0)
Location: mm/filemap.c:430
Inline: False
Direct callers:
  - mm/filemap.c:file_write_and_wait_range
  - mm/filemap.c:filemap_flush
  - mm/filemap.c:filemap_fdatawrite_range
  - mm/fadvise.c:SyS_fadvise64
  - fs/sync.c:SyS_sync_file_range2
```
**Symbols:**

```
ffffffff811cd7a0-ffffffff811cd891: __filemap_fdatawrite_range (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int __filemap_fdatawrite_range(struct address_space *mapping, loff_t start, loff_t end, int sync_mode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/filemap.c (ffffffff811ef2d0)
Location: mm/filemap.c:430
Inline: False
Direct callers:
  - mm/filemap.c:file_write_and_wait_range
  - mm/filemap.c:filemap_flush
  - mm/filemap.c:filemap_fdatawrite_range
  - mm/fadvise.c:ksys_fadvise64_64
  - fs/sync.c:ksys_sync_file_range
```
**Symbols:**

```
ffffffff811ef2d0-ffffffff811ef3c2: __filemap_fdatawrite_range (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int __filemap_fdatawrite_range(struct address_space *mapping, loff_t start, loff_t end, int sync_mode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/filemap.c (ffffffff81200ad0)
Location: mm/filemap.c:396
Inline: False
Direct callers:
  - mm/filemap.c:file_write_and_wait_range
  - mm/filemap.c:filemap_flush
  - mm/filemap.c:filemap_fdatawrite_range
  - mm/fadvise.c:vfs_fadvise
  - fs/sync.c:ksys_sync_file_range
```
**Symbols:**

```
ffffffff81200ad0-ffffffff81200bc2: __filemap_fdatawrite_range (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int __filemap_fdatawrite_range(struct address_space *mapping, loff_t start, loff_t end, int sync_mode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/filemap.c (ffffffff812186f0)
Location: mm/filemap.c:400
Inline: False
Direct callers:
  - mm/filemap.c:file_write_and_wait_range
  - mm/filemap.c:filemap_flush
  - mm/filemap.c:filemap_fdatawrite_range
  - mm/fadvise.c:vfs_fadvise
  - fs/sync.c:sync_file_range
```
**Symbols:**

```
ffffffff812186f0-ffffffff812187ed: __filemap_fdatawrite_range (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int __filemap_fdatawrite_range(struct address_space *mapping, loff_t start, loff_t end, int sync_mode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/filemap.c (ffffffff81225f60)
Location: mm/filemap.c:405
Inline: False
Direct callers:
  - mm/filemap.c:file_write_and_wait_range
  - mm/filemap.c:filemap_flush
  - mm/filemap.c:filemap_fdatawrite_range
  - mm/fadvise.c:generic_fadvise
  - fs/sync.c:sync_file_range
```
**Symbols:**

```
ffffffff81225f60-ffffffff8122606e: __filemap_fdatawrite_range (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int __filemap_fdatawrite_range(struct address_space *mapping, loff_t start, loff_t end, int sync_mode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/filemap.c (ffffffff812510a0)
Location: mm/filemap.c:405
Inline: False
Direct callers:
  - mm/filemap.c:file_write_and_wait_range
  - mm/filemap.c:filemap_flush
  - mm/filemap.c:filemap_fdatawrite_range
  - mm/filemap.c:filemap_fdatawrite
  - mm/fadvise.c:generic_fadvise
  - fs/sync.c:sync_file_range
```
**Symbols:**

```
ffffffff812510a0-ffffffff812511a5: __filemap_fdatawrite_range (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int __filemap_fdatawrite_range(struct address_space *mapping, loff_t start, loff_t end, int sync_mode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/filemap.c (ffffffff8125c730)
Location: mm/filemap.c:406
Inline: False
Direct callers:
  - mm/filemap.c:file_write_and_wait_range
  - mm/filemap.c:filemap_flush
  - mm/filemap.c:filemap_fdatawrite_range
  - mm/filemap.c:filemap_fdatawrite
  - mm/fadvise.c:generic_fadvise
  - fs/sync.c:sync_file_range
```
**Symbols:**

```
ffffffff8125c730-ffffffff8125c835: __filemap_fdatawrite_range (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int __filemap_fdatawrite_range(struct address_space *mapping, loff_t start, loff_t end, int sync_mode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/filemap.c (ffffffff81261510)
Location: mm/filemap.c:397
Inline: False
Direct callers:
  - mm/filemap.c:file_write_and_wait_range
  - mm/filemap.c:filemap_flush
  - mm/filemap.c:filemap_fdatawrite_range
  - mm/filemap.c:filemap_fdatawrite
  - mm/fadvise.c:generic_fadvise
  - fs/sync.c:sync_file_range
```
**Symbols:**

```
ffffffff81261510-ffffffff81261615: __filemap_fdatawrite_range (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
int __filemap_fdatawrite_range(struct address_space *mapping, loff_t start, loff_t end, int sync_mode);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/filemap.c (ffffffff8129b0a5)
Location: mm/filemap.c:423
Inline: True
Inline callers:
  - mm/filemap.c:file_write_and_wait_range
  - mm/filemap.c:filemap_flush
  - mm/filemap.c:filemap_fdatawrite_range
  - mm/filemap.c:filemap_fdatawrite
Direct callers:
  - mm/fadvise.c:generic_fadvise
  - fs/sync.c:sync_file_range
```
**Symbols:**

```
ffffffff8129e170-ffffffff8129e1da: __filemap_fdatawrite_range (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int __filemap_fdatawrite_range(struct address_space *mapping, loff_t start, loff_t end, int sync_mode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/filemap.c (ffffffff812f5590)
Location: mm/filemap.c:411
Inline: False
Direct callers:
  - mm/filemap.c:file_write_and_wait_range
  - mm/filemap.c:filemap_flush
  - mm/filemap.c:filemap_fdatawrite_range
  - mm/filemap.c:filemap_fdatawrite
  - mm/fadvise.c:generic_fadvise
  - fs/sync.c:sync_file_range
```
**Symbols:**

```
ffffffff812f5590-ffffffff812f5610: __filemap_fdatawrite_range (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int __filemap_fdatawrite_range(struct address_space *mapping, loff_t start, loff_t end, int sync_mode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/filemap.c (ffffffff8135f3e0)
Location: mm/filemap.c:411
Inline: False
Direct callers:
  - mm/filemap.c:file_write_and_wait_range
  - mm/filemap.c:filemap_flush
  - mm/filemap.c:filemap_fdatawrite_range
  - mm/filemap.c:filemap_fdatawrite
  - mm/fadvise.c:generic_fadvise
  - fs/sync.c:sync_file_range
```
**Symbols:**

```
ffffffff8135f3e0-ffffffff8135f460: __filemap_fdatawrite_range (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int __filemap_fdatawrite_range(struct address_space *mapping, loff_t start, loff_t end, int sync_mode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/filemap.c (ffffffff81390540)
Location: mm/filemap.c:416
Inline: False
Direct callers:
  - mm/filemap.c:file_write_and_wait_range
  - mm/filemap.c:filemap_flush
  - mm/filemap.c:filemap_fdatawrite_range
  - mm/filemap.c:filemap_fdatawrite
  - mm/fadvise.c:generic_fadvise
  - fs/sync.c:sync_file_range
```
**Symbols:**

```
ffffffff81390540-ffffffff813905c0: __filemap_fdatawrite_range (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int __filemap_fdatawrite_range(struct address_space *mapping, loff_t start, loff_t end, int sync_mode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/filemap.c (ffffffff813b9f80)
Location: mm/filemap.c:411
Inline: False
Direct callers:
  - mm/filemap.c:file_write_and_wait_range
  - mm/filemap.c:filemap_flush
  - mm/filemap.c:filemap_fdatawrite_range
  - mm/filemap.c:filemap_fdatawrite
  - mm/fadvise.c:generic_fadvise
  - fs/sync.c:sync_file_range
```
**Symbols:**

```
ffffffff813b9f80-ffffffff813ba000: __filemap_fdatawrite_range (STB_GLOBAL)
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
int __filemap_fdatawrite_range(struct address_space *mapping, loff_t start, loff_t end, int sync_mode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/filemap.c (ffff8000102b3138)
Location: mm/filemap.c:405
Inline: False
Direct callers:
  - mm/filemap.c:file_write_and_wait_range
  - mm/filemap.c:filemap_flush
  - mm/filemap.c:filemap_fdatawrite_range
  - mm/fadvise.c:generic_fadvise
  - fs/sync.c:sync_file_range
```
**Symbols:**

```
ffff8000102b3138-ffff8000102b32b0: __filemap_fdatawrite_range (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int __filemap_fdatawrite_range(struct address_space *mapping, loff_t start, loff_t end, int sync_mode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/filemap.c (c04e0388)
Location: mm/filemap.c:405
Inline: False
Direct callers:
  - mm/filemap.c:file_write_and_wait_range
  - mm/filemap.c:filemap_flush
  - mm/filemap.c:filemap_fdatawrite_range
  - mm/fadvise.c:generic_fadvise
  - fs/sync.c:sync_file_range
```
**Symbols:**

```
c04e0388-c04e04c0: __filemap_fdatawrite_range (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int __filemap_fdatawrite_range(struct address_space *mapping, loff_t start, loff_t end, int sync_mode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/filemap.c (c000000000369c90)
Location: mm/filemap.c:405
Inline: False
Direct callers:
  - mm/filemap.c:file_write_and_wait_range
  - mm/filemap.c:filemap_flush
  - mm/filemap.c:filemap_fdatawrite_range
  - mm/fadvise.c:generic_fadvise
  - fs/sync.c:sync_file_range
```
**Symbols:**

```
c000000000369c90-c000000000369e0c: __filemap_fdatawrite_range (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int __filemap_fdatawrite_range(struct address_space *mapping, loff_t start, loff_t end, int sync_mode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/filemap.c (ffffffe0001d88ce)
Location: mm/filemap.c:405
Inline: False
Direct callers:
  - mm/filemap.c:file_write_and_wait_range
  - mm/filemap.c:filemap_flush
  - mm/filemap.c:filemap_fdatawrite_range
  - mm/fadvise.c:generic_fadvise
  - fs/sync.c:sync_file_range
```
**Symbols:**

```
ffffffe0001d88ce-ffffffe0001d89cc: __filemap_fdatawrite_range (STB_GLOBAL)
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
int __filemap_fdatawrite_range(struct address_space *mapping, loff_t start, loff_t end, int sync_mode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/filemap.c (ffffffff8121e5b0)
Location: mm/filemap.c:405
Inline: False
Direct callers:
  - mm/filemap.c:file_write_and_wait_range
  - mm/filemap.c:filemap_flush
  - mm/filemap.c:filemap_fdatawrite_range
  - mm/fadvise.c:generic_fadvise
  - fs/sync.c:sync_file_range
```
**Symbols:**

```
ffffffff8121e5b0-ffffffff8121e6be: __filemap_fdatawrite_range (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int __filemap_fdatawrite_range(struct address_space *mapping, loff_t start, loff_t end, int sync_mode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/filemap.c (ffffffff81211770)
Location: mm/filemap.c:405
Inline: False
Direct callers:
  - mm/filemap.c:file_write_and_wait_range
  - mm/filemap.c:filemap_flush
  - mm/filemap.c:filemap_fdatawrite_range
  - mm/fadvise.c:generic_fadvise
  - fs/sync.c:sync_file_range
```
**Symbols:**

```
ffffffff81211770-ffffffff8121187e: __filemap_fdatawrite_range (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int __filemap_fdatawrite_range(struct address_space *mapping, loff_t start, loff_t end, int sync_mode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/filemap.c (ffffffff8121c350)
Location: mm/filemap.c:405
Inline: False
Direct callers:
  - mm/filemap.c:file_write_and_wait_range
  - mm/filemap.c:filemap_flush
  - mm/filemap.c:filemap_fdatawrite_range
  - mm/fadvise.c:generic_fadvise
  - fs/sync.c:sync_file_range
```
**Symbols:**

```
ffffffff8121c350-ffffffff8121c45e: __filemap_fdatawrite_range (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int __filemap_fdatawrite_range(struct address_space *mapping, loff_t start, loff_t end, int sync_mode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/filemap.c (ffffffff8122b3e0)
Location: mm/filemap.c:405
Inline: False
Direct callers:
  - mm/filemap.c:file_write_and_wait_range
  - mm/filemap.c:filemap_flush
  - mm/filemap.c:filemap_fdatawrite_range
  - mm/fadvise.c:generic_fadvise
  - fs/sync.c:sync_file_range
```
**Symbols:**

```
ffffffff8122b3e0-ffffffff8122b4ee: __filemap_fdatawrite_range (STB_GLOBAL)
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
