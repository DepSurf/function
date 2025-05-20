# Function: <code>filemap_check_errors</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int filemap_check_errors(struct address_space *mapping);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/filemap.c (ffffffff8118c4a0)
Location: mm/filemap.c:254
Inline: False
Direct callers:
  - mm/filemap.c:filemap_fdatawait_range
```
**Symbols:**

```
ffffffff8118c4a0-ffffffff8118c4e3: filemap_check_errors (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int filemap_check_errors(struct address_space *mapping);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/filemap.c (ffffffff8119f2f0)
Location: mm/filemap.c:332
Inline: False
Direct callers:
  - mm/filemap.c:filemap_fdatawait_range
  - fs/fuse/file.c:fuse_fsync_common
  - fs/fuse/file.c:fuse_flush
```
**Symbols:**

```
ffffffff8119f2f0-ffffffff8119f331: filemap_check_errors (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int filemap_check_errors(struct address_space *mapping);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/filemap.c (ffffffff811aeda0)
Location: mm/filemap.c:297
Inline: False
Direct callers:
  - mm/filemap.c:filemap_fdatawait_range
  - fs/fuse/file.c:fuse_fsync_common
  - fs/fuse/file.c:fuse_flush
```
**Symbols:**

```
ffffffff811aeda0-ffffffff811aeddb: filemap_check_errors (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int filemap_check_errors(struct address_space *mapping);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/filemap.c (ffffffff811b58d0)
Location: mm/filemap.c:291
Inline: False
Direct callers:
  - mm/filemap.c:filemap_fdatawait
  - mm/page-writeback.c:write_one_page
  - fs/fuse/file.c:fuse_fsync_common
  - fs/fuse/file.c:fuse_flush
```
**Symbols:**

```
ffffffff811b58d0-ffffffff811b590b: filemap_check_errors (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int filemap_check_errors(struct address_space *mapping);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/filemap.c (ffffffff811c99c0)
Location: mm/filemap.c:391
Inline: False
Direct callers:
  - mm/page-writeback.c:write_one_page
  - fs/fuse/file.c:fuse_flush
```
**Symbols:**

```
ffffffff811c99c0-ffffffff811c99fb: filemap_check_errors (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int filemap_check_errors(struct address_space *mapping);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/filemap.c (ffffffff811eab20)
Location: mm/filemap.c:391
Inline: False
Direct callers:
  - mm/page-writeback.c:write_one_page
  - fs/fuse/file.c:fuse_flush
```
**Symbols:**

```
ffffffff811eab20-ffffffff811eab5d: filemap_check_errors (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int filemap_check_errors(struct address_space *mapping);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/filemap.c (ffffffff811fb690)
Location: mm/filemap.c:357
Inline: False
Direct callers:
  - mm/page-writeback.c:write_one_page
  - fs/fuse/file.c:fuse_flush
```
**Symbols:**

```
ffffffff811fb690-ffffffff811fb6cd: filemap_check_errors (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int filemap_check_errors(struct address_space *mapping);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/filemap.c (ffffffff81212d20)
Location: mm/filemap.c:359
Inline: False
Direct callers:
  - mm/page-writeback.c:write_one_page
  - fs/fuse/file.c:fuse_flush
```
**Symbols:**

```
ffffffff81212d20-ffffffff81212d5d: filemap_check_errors (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int filemap_check_errors(struct address_space *mapping);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/filemap.c (ffffffff81220570)
Location: mm/filemap.c:364
Inline: False
Direct callers:
  - mm/page-writeback.c:write_one_page
  - fs/fuse/file.c:fuse_flush
```
**Symbols:**

```
ffffffff81220570-ffffffff812205ad: filemap_check_errors (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
int filemap_check_errors(struct address_space *mapping);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/filemap.c (ffffffff8124d990)
Location: mm/filemap.c:364
Inline: True
Direct callers:
  - mm/page-writeback.c:write_one_page
  - fs/fuse/file.c:fuse_flush
```
**Symbols:**

```
ffffffff8124d990-ffffffff8124d9cd: filemap_check_errors (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
int filemap_check_errors(struct address_space *mapping);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/filemap.c (ffffffff81257ee0)
Location: mm/filemap.c:365
Inline: True
Direct callers:
  - mm/page-writeback.c:write_one_page
  - fs/fuse/file.c:fuse_flush
```
**Symbols:**

```
ffffffff81257ee0-ffffffff81257f1d: filemap_check_errors (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
int filemap_check_errors(struct address_space *mapping);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/filemap.c (ffffffff8125c4c0)
Location: mm/filemap.c:356
Inline: True
Direct callers:
  - mm/page-writeback.c:write_one_page
  - fs/fuse/file.c:fuse_flush
```
**Symbols:**

```
ffffffff8125c4c0-ffffffff8125c4fd: filemap_check_errors (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
int filemap_check_errors(struct address_space *mapping);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/filemap.c (ffffffff81298370)
Location: mm/filemap.c:356
Inline: True
Direct callers:
  - mm/page-writeback.c:write_one_page
  - fs/fuse/file.c:fuse_flush
```
**Symbols:**

```
ffffffff81298370-ffffffff812983b9: filemap_check_errors (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
int filemap_check_errors(struct address_space *mapping);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/filemap.c (ffffffff812ee8d0)
Location: mm/filemap.c:344
Inline: True
Direct callers:
  - mm/page-writeback.c:folio_write_one
  - fs/fuse/file.c:fuse_flush
```
**Symbols:**

```
ffffffff812ee8d0-ffffffff812ee921: filemap_check_errors (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int filemap_check_errors(struct address_space *mapping);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/filemap.c (ffffffff81358f00)
Location: mm/filemap.c:344
Inline: False
Direct callers:
  - mm/filemap.c:filemap_fdatawait_range
  - mm/page-writeback.c:folio_write_one
  - fs/fuse/file.c:fuse_flush
```
**Symbols:**

```
ffffffff81358f00-ffffffff81358f51: filemap_check_errors (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int filemap_check_errors(struct address_space *mapping);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/filemap.c (ffffffff8138a860)
Location: mm/filemap.c:349
Inline: False
Direct callers:
  - mm/filemap.c:filemap_fdatawait_range
  - fs/fuse/file.c:fuse_flush
```
**Symbols:**

```
ffffffff8138a860-ffffffff8138a8a5: filemap_check_errors (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int filemap_check_errors(struct address_space *mapping);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/filemap.c (ffffffff813b4380)
Location: mm/filemap.c:344
Inline: False
Direct callers:
  - mm/filemap.c:filemap_fdatawait_range
  - fs/fuse/file.c:fuse_flush
```
**Symbols:**

```
ffffffff813b4380-ffffffff813b43c5: filemap_check_errors (STB_GLOBAL)
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
int filemap_check_errors(struct address_space *mapping);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/filemap.c (ffff8000102afb68)
Location: mm/filemap.c:364
Inline: False
Direct callers:
  - mm/page-writeback.c:write_one_page
  - fs/fuse/file.c:fuse_flush
```
**Symbols:**

```
ffff8000102afb68-ffff8000102afc48: filemap_check_errors (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int filemap_check_errors(struct address_space *mapping);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/filemap.c (c04dac14)
Location: mm/filemap.c:364
Inline: False
Direct callers:
  - mm/page-writeback.c:write_one_page
  - fs/fuse/file.c:fuse_flush
```
**Symbols:**

```
c04dac14-c04dac90: filemap_check_errors (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int filemap_check_errors(struct address_space *mapping);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/filemap.c (c000000000361630)
Location: mm/filemap.c:364
Inline: False
Direct callers:
  - mm/page-writeback.c:write_one_page
  - fs/fuse/file.c:fuse_flush
```
**Symbols:**

```
c000000000361630-c0000000003616c4: filemap_check_errors (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
int filemap_check_errors(struct address_space *mapping);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/filemap.c (ffffffe0001d45c6)
Location: mm/filemap.c:364
Inline: True
Inline callers:
  - mm/filemap.c:filemap_fdatawait_range
Direct callers:
  - mm/page-writeback.c:write_one_page
  - mm/page-writeback.c:write_one_page
  - fs/fuse/file.c:fuse_flush
```
**Symbols:**

```
ffffffe0001d3cdc-ffffffe0001d3d30: filemap_check_errors (STB_GLOBAL)
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
int filemap_check_errors(struct address_space *mapping);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/filemap.c (ffffffff81218bc0)
Location: mm/filemap.c:364
Inline: False
Direct callers:
  - mm/page-writeback.c:write_one_page
  - fs/fuse/file.c:fuse_flush
```
**Symbols:**

```
ffffffff81218bc0-ffffffff81218bfd: filemap_check_errors (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int filemap_check_errors(struct address_space *mapping);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/filemap.c (ffffffff8120bdd0)
Location: mm/filemap.c:364
Inline: False
Direct callers:
  - mm/page-writeback.c:write_one_page
  - fs/fuse/file.c:fuse_flush
```
**Symbols:**

```
ffffffff8120bdd0-ffffffff8120be0d: filemap_check_errors (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int filemap_check_errors(struct address_space *mapping);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/filemap.c (ffffffff81216960)
Location: mm/filemap.c:364
Inline: False
Direct callers:
  - mm/page-writeback.c:write_one_page
  - fs/fuse/file.c:fuse_flush
```
**Symbols:**

```
ffffffff81216960-ffffffff8121699d: filemap_check_errors (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int filemap_check_errors(struct address_space *mapping);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/filemap.c (ffffffff812259e0)
Location: mm/filemap.c:364
Inline: False
Direct callers:
  - mm/page-writeback.c:write_one_page
  - fs/fuse/file.c:fuse_flush
```
**Symbols:**

```
ffffffff812259e0-ffffffff81225a1d: filemap_check_errors (STB_GLOBAL)
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
