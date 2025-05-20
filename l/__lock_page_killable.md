# Function: <code>__lock_page_killable</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int __lock_page_killable(struct page *page);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/filemap.c (ffffffff8118cdf0)
Location: mm/filemap.c:883
Inline: False
Direct callers:
  - mm/filemap.c:generic_file_read_iter
  - mm/filemap.c:generic_file_read_iter
```
**Symbols:**

```
ffffffff8118cdf0-ffffffff8118cec1: __lock_page_killable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int __lock_page_killable(struct page *page);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/filemap.c (ffffffff8119fd90)
Location: mm/filemap.c:925
Inline: False
Direct callers:
  - mm/filemap.c:generic_file_read_iter
  - mm/filemap.c:generic_file_read_iter
```
**Symbols:**

```
ffffffff8119fd90-ffffffff8119fe71: __lock_page_killable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int __lock_page_killable(struct page *__page);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/filemap.c (ffffffff811afe10)
Location: mm/filemap.c:1029
Inline: False
Direct callers:
  - mm/filemap.c:generic_file_read_iter
  - mm/filemap.c:generic_file_read_iter
```
**Symbols:**

```
ffffffff811afe10-ffffffff811aff87: __lock_page_killable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int __lock_page_killable(struct page *__page);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/filemap.c (ffffffff811b70e0)
Location: mm/filemap.c:1155
Inline: False
Direct callers:
  - mm/filemap.c:generic_file_read_iter
  - mm/filemap.c:generic_file_read_iter
```
**Symbols:**

```
ffffffff811b70e0-ffffffff811b7247: __lock_page_killable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int __lock_page_killable(struct page *__page);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/filemap.c (ffffffff811cb1f0)
Location: mm/filemap.c:1277
Inline: False
Direct callers:
  - mm/filemap.c:generic_file_read_iter
  - mm/filemap.c:generic_file_read_iter
```
**Symbols:**

```
ffffffff811cb1f0-ffffffff811cb356: __lock_page_killable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int __lock_page_killable(struct page *__page);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/filemap.c (ffffffff811ec320)
Location: mm/filemap.c:1277
Inline: False
Direct callers:
  - mm/filemap.c:generic_file_buffered_read
  - mm/filemap.c:generic_file_buffered_read
```
**Symbols:**

```
ffffffff811ec320-ffffffff811ec495: __lock_page_killable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int __lock_page_killable(struct page *__page);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/filemap.c (ffffffff811fd4a0)
Location: mm/filemap.c:1331
Inline: False
Direct callers:
  - mm/filemap.c:generic_file_buffered_read
  - mm/filemap.c:generic_file_buffered_read
```
**Symbols:**

```
ffffffff811fd4a0-ffffffff811fd6dc: __lock_page_killable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int __lock_page_killable(struct page *__page);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/filemap.c (ffffffff812144d0)
Location: mm/filemap.c:1379
Inline: False
Direct callers:
  - mm/filemap.c:filemap_fault
  - mm/filemap.c:generic_file_buffered_read
  - mm/filemap.c:generic_file_buffered_read
  - mm/filemap.c:__lock_page_or_retry
```
**Symbols:**

```
ffffffff812144d0-ffffffff8121473e: __lock_page_killable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int __lock_page_killable(struct page *__page);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/filemap.c (ffffffff81221d00)
Location: mm/filemap.c:1388
Inline: False
Direct callers:
  - mm/filemap.c:filemap_fault
  - mm/filemap.c:generic_file_buffered_read
  - mm/filemap.c:generic_file_buffered_read
  - mm/filemap.c:__lock_page_or_retry
```
**Symbols:**

```
ffffffff81221d00-ffffffff81221f6e: __lock_page_killable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
int __lock_page_killable(struct page *__page);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/filemap.c (ffffffff8125341a)
Location: mm/filemap.c:1363
Inline: True
Inline callers:
  - mm/filemap.c:filemap_fault
  - mm/filemap.c:generic_file_buffered_read
  - mm/filemap.c:generic_file_buffered_read
  - mm/filemap.c:__lock_page_or_retry
```
**Symbols:**

```
ffffffff8124fb90-ffffffff8124fbdf: __lock_page_killable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
int __lock_page_killable(struct page *__page);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/filemap.c (ffffffff8125e01b)
Location: mm/filemap.c:1548
Inline: True
Inline callers:
  - mm/filemap.c:filemap_fault
  - mm/filemap.c:__lock_page_or_retry
```
**Symbols:**

```
ffffffff8125ab40-ffffffff8125ab8f: __lock_page_killable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
int __lock_page_killable(struct page *__page);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/filemap.c (ffffffff81260cf0)
Location: mm/filemap.c:1598
Inline: True
Inline callers:
  - mm/filemap.c:filemap_fault
  - mm/filemap.c:__lock_page_or_retry
```
**Symbols:**

```
ffffffff8125f3c0-ffffffff8125f40f: __lock_page_killable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
int __lock_page_killable(struct page *__page);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/filemap.c (ffffffff8129d4af)
Location: mm/filemap.c:1653
Inline: True
Inline callers:
  - mm/filemap.c:filemap_fault
  - mm/filemap.c:__lock_page_or_retry
```
**Symbols:**

```
ffffffff8129bb40-ffffffff8129bb8e: __lock_page_killable (STB_GLOBAL)
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
<summary>In <code>arm64</code>: ✅</summary>

```c
int __lock_page_killable(struct page *__page);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/filemap.c (ffff8000102afaf0)
Location: mm/filemap.c:1388
Inline: False
Direct callers:
  - mm/filemap.c:filemap_fault
  - mm/filemap.c:generic_file_buffered_read
  - mm/filemap.c:generic_file_buffered_read
  - mm/filemap.c:__lock_page_or_retry
```
**Symbols:**

```
ffff8000102afaf0-ffff8000102afb68: __lock_page_killable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int __lock_page_killable(struct page *__page);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/filemap.c (c04dc3cc)
Location: mm/filemap.c:1388
Inline: False
Direct callers:
  - mm/filemap.c:filemap_fault
  - mm/filemap.c:generic_file_buffered_read
  - mm/filemap.c:generic_file_buffered_read
  - mm/filemap.c:__lock_page_or_retry
```
**Symbols:**

```
c04dc3cc-c04dc660: __lock_page_killable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int __lock_page_killable(struct page *__page);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/filemap.c (c000000000364480)
Location: mm/filemap.c:1388
Inline: False
Direct callers:
  - mm/filemap.c:filemap_fault
  - mm/filemap.c:generic_file_buffered_read
  - mm/filemap.c:generic_file_buffered_read
  - mm/filemap.c:__lock_page_or_retry
```
**Symbols:**

```
c000000000364480-c000000000364830: __lock_page_killable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int __lock_page_killable(struct page *__page);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/filemap.c (ffffffe0001d571a)
Location: mm/filemap.c:1388
Inline: False
Direct callers:
  - mm/filemap.c:filemap_fault
  - mm/filemap.c:generic_file_buffered_read
  - mm/filemap.c:generic_file_buffered_read
  - mm/filemap.c:__lock_page_or_retry
```
**Symbols:**

```
ffffffe0001d571a-ffffffe0001d5928: __lock_page_killable (STB_GLOBAL)
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
int __lock_page_killable(struct page *__page);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/filemap.c (ffffffff8121a350)
Location: mm/filemap.c:1388
Inline: False
Direct callers:
  - mm/filemap.c:filemap_fault
  - mm/filemap.c:generic_file_buffered_read
  - mm/filemap.c:generic_file_buffered_read
  - mm/filemap.c:__lock_page_or_retry
```
**Symbols:**

```
ffffffff8121a350-ffffffff8121a5be: __lock_page_killable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int __lock_page_killable(struct page *__page);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/filemap.c (ffffffff8120d560)
Location: mm/filemap.c:1388
Inline: False
Direct callers:
  - mm/filemap.c:filemap_fault
  - mm/filemap.c:generic_file_buffered_read
  - mm/filemap.c:generic_file_buffered_read
  - mm/filemap.c:__lock_page_or_retry
```
**Symbols:**

```
ffffffff8120d560-ffffffff8120d7c8: __lock_page_killable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int __lock_page_killable(struct page *__page);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/filemap.c (ffffffff812180f0)
Location: mm/filemap.c:1388
Inline: False
Direct callers:
  - mm/filemap.c:filemap_fault
  - mm/filemap.c:generic_file_buffered_read
  - mm/filemap.c:generic_file_buffered_read
  - mm/filemap.c:__lock_page_or_retry
```
**Symbols:**

```
ffffffff812180f0-ffffffff8121835e: __lock_page_killable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int __lock_page_killable(struct page *__page);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/filemap.c (ffffffff812271c0)
Location: mm/filemap.c:1388
Inline: False
Direct callers:
  - mm/filemap.c:filemap_fault
  - mm/filemap.c:generic_file_buffered_read
  - mm/filemap.c:generic_file_buffered_read
  - mm/filemap.c:__lock_page_or_retry
```
**Symbols:**

```
ffffffff812271c0-ffffffff812273f2: __lock_page_killable (STB_GLOBAL)
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
<details>
<summary>Changed between <code>4.8</code> and <code>4.10</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>struct page *__page</code>
</li>
<li>
<b>Param removed. </b>
<code>struct page *page</code>
</li>
</ul>
</details>
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
