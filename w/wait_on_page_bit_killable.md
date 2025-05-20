# Function: <code>wait_on_page_bit_killable</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int wait_on_page_bit_killable(struct page *page, int bit_nr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/filemap.c (ffffffff8118f5d0)
Location: mm/filemap.c:756
Inline: False
```
**Symbols:**

```
ffffffff8118f5d0-ffffffff8118f6b3: wait_on_page_bit_killable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int wait_on_page_bit_killable(struct page *page, int bit_nr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/filemap.c (ffffffff811a2ba0)
Location: mm/filemap.c:796
Inline: False
Direct callers:
  - mm/filemap.c:generic_file_read_iter
```
**Symbols:**

```
ffffffff811a2ba0-ffffffff811a2c81: wait_on_page_bit_killable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
int wait_on_page_bit_killable(struct page *page, int bit_nr);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/filemap.c (ffffffff811b2a49)
Location: mm/filemap.c:890
Inline: True
Inline callers:
  - mm/filemap.c:generic_file_read_iter
```
**Symbols:**

```
ffffffff811b32d0-ffffffff811b3439: wait_on_page_bit_killable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
int wait_on_page_bit_killable(struct page *page, int bit_nr);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/filemap.c (ffffffff811b9825)
Location: mm/filemap.c:1016
Inline: True
Inline callers:
  - mm/filemap.c:generic_file_read_iter
```
**Symbols:**

```
ffffffff811ba110-ffffffff811ba270: wait_on_page_bit_killable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
int wait_on_page_bit_killable(struct page *page, int bit_nr);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/filemap.c (ffffffff811ceb7c)
Location: mm/filemap.c:1137
Inline: True
Inline callers:
  - mm/filemap.c:generic_file_read_iter
```
**Symbols:**

```
ffffffff811cb560-ffffffff811cb6bd: wait_on_page_bit_killable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
int wait_on_page_bit_killable(struct page *page, int bit_nr);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/filemap.c (ffffffff811ee486)
Location: mm/filemap.c:1137
Inline: True
Inline callers:
  - mm/filemap.c:generic_file_buffered_read
```
**Symbols:**

```
ffffffff811ecb50-ffffffff811eccb1: wait_on_page_bit_killable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
int wait_on_page_bit_killable(struct page *page, int bit_nr);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/filemap.c (ffffffff811ffbed)
Location: mm/filemap.c:1171
Inline: True
Inline callers:
  - mm/filemap.c:generic_file_buffered_read
```
**Symbols:**

```
ffffffff811fd9c0-ffffffff811fdbf8: wait_on_page_bit_killable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
int wait_on_page_bit_killable(struct page *page, int bit_nr);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/filemap.c (ffffffff81216ca2)
Location: mm/filemap.c:1219
Inline: True
Inline callers:
  - mm/filemap.c:generic_file_buffered_read
  - mm/filemap.c:__lock_page_or_retry
```
**Symbols:**

```
ffffffff81214a30-ffffffff81214c63: wait_on_page_bit_killable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
int wait_on_page_bit_killable(struct page *page, int bit_nr);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/filemap.c (ffffffff812245b2)
Location: mm/filemap.c:1228
Inline: True
Inline callers:
  - mm/filemap.c:generic_file_buffered_read
  - mm/filemap.c:__lock_page_or_retry
```
**Symbols:**

```
ffffffff81222260-ffffffff81222493: wait_on_page_bit_killable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
int wait_on_page_bit_killable(struct page *page, int bit_nr);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/filemap.c (ffffffff8125223e)
Location: mm/filemap.c:1203
Inline: True
Inline callers:
  - mm/filemap.c:generic_file_buffered_read
  - mm/filemap.c:__lock_page_or_retry
```
**Symbols:**

```
ffffffff8124faf0-ffffffff8124fb31: wait_on_page_bit_killable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
int wait_on_page_bit_killable(struct page *page, int bit_nr);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/filemap.c (ffffffff8125ba0b)
Location: mm/filemap.c:1342
Inline: True
Inline callers:
  - mm/filemap.c:generic_file_buffered_read_pagenotuptodate
  - mm/filemap.c:__lock_page_or_retry
```
**Symbols:**

```
ffffffff8125aaa0-ffffffff8125aae1: wait_on_page_bit_killable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
int wait_on_page_bit_killable(struct page *page, int bit_nr);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/filemap.c (ffffffff81262976)
Location: mm/filemap.c:1366
Inline: True
Inline callers:
  - mm/filemap.c:__lock_page_or_retry
  - mm/filemap.c:wait_on_page_private_2_killable
Direct callers:
  - mm/page-writeback.c:wait_on_page_writeback_killable
```
**Symbols:**

```
ffffffff8125f320-ffffffff8125f361: wait_on_page_bit_killable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
int wait_on_page_bit_killable(struct page *page, int bit_nr);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/filemap.c (ffffffff8129efc6)
Location: mm/filemap.c:1421
Inline: True
Inline callers:
  - mm/filemap.c:__lock_page_or_retry
  - mm/filemap.c:wait_on_page_private_2_killable
Direct callers:
  - mm/page-writeback.c:wait_on_page_writeback_killable
```
**Symbols:**

```
ffffffff8129baa0-ffffffff8129bae1: wait_on_page_bit_killable (STB_GLOBAL)
```
</details>
</li>
<li>
In <code>5.19</code>: Absent ⚠️
</li>
<li>
In <code>6.2</code>: Absent ⚠️
</li>
<li>
In <code>6.5</code>: Absent ⚠️
</li>
<li>
In <code>6.8</code>: Absent ⚠️
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Selective Inline ⚠️</summary>

```c
int wait_on_page_bit_killable(struct page *page, int bit_nr);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/filemap.c (ffff8000102b1bdc)
Location: mm/filemap.c:1228
Inline: True
Inline callers:
  - mm/filemap.c:generic_file_buffered_read
  - mm/filemap.c:__lock_page_or_retry
```
**Symbols:**

```
ffff8000102af8f0-ffff8000102af954: wait_on_page_bit_killable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
int wait_on_page_bit_killable(struct page *page, int bit_nr);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/filemap.c (c04de888)
Location: mm/filemap.c:1228
Inline: True
Inline callers:
  - mm/filemap.c:generic_file_buffered_read
  - mm/filemap.c:__lock_page_or_retry
```
**Symbols:**

```
c04dbd5c-c04dc00c: wait_on_page_bit_killable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
int wait_on_page_bit_killable(struct page *page, int bit_nr);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/filemap.c (c0000000003679d8)
Location: mm/filemap.c:1228
Inline: True
Inline callers:
  - mm/filemap.c:generic_file_buffered_read
  - mm/filemap.c:__lock_page_or_retry
```
**Symbols:**

```
c000000000363e00-c000000000364160: wait_on_page_bit_killable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
int wait_on_page_bit_killable(struct page *page, int bit_nr);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/filemap.c (ffffffe0001d7458)
Location: mm/filemap.c:1228
Inline: True
Inline callers:
  - mm/filemap.c:generic_file_buffered_read
  - mm/filemap.c:__lock_page_or_retry
```
**Symbols:**

```
ffffffe0001d5bea-ffffffe0001d5e1c: wait_on_page_bit_killable (STB_GLOBAL)
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
int wait_on_page_bit_killable(struct page *page, int bit_nr);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/filemap.c (ffffffff8121cc02)
Location: mm/filemap.c:1228
Inline: True
Inline callers:
  - mm/filemap.c:generic_file_buffered_read
  - mm/filemap.c:__lock_page_or_retry
```
**Symbols:**

```
ffffffff8121a8b0-ffffffff8121aae3: wait_on_page_bit_killable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
int wait_on_page_bit_killable(struct page *page, int bit_nr);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/filemap.c (ffffffff8120fde2)
Location: mm/filemap.c:1228
Inline: True
Inline callers:
  - mm/filemap.c:generic_file_buffered_read
  - mm/filemap.c:__lock_page_or_retry
```
**Symbols:**

```
ffffffff8120dac0-ffffffff8120dced: wait_on_page_bit_killable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
int wait_on_page_bit_killable(struct page *page, int bit_nr);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/filemap.c (ffffffff8121a9a2)
Location: mm/filemap.c:1228
Inline: True
Inline callers:
  - mm/filemap.c:generic_file_buffered_read
  - mm/filemap.c:__lock_page_or_retry
```
**Symbols:**

```
ffffffff81218650-ffffffff81218883: wait_on_page_bit_killable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
int wait_on_page_bit_killable(struct page *page, int bit_nr);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/filemap.c (ffffffff81229a6d)
Location: mm/filemap.c:1228
Inline: True
Inline callers:
  - mm/filemap.c:generic_file_buffered_read
  - mm/filemap.c:__lock_page_or_retry
```
**Symbols:**

```
ffffffff812276f0-ffffffff81227958: wait_on_page_bit_killable (STB_GLOBAL)
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
