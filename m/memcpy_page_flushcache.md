# Function: <code>memcpy_page_flushcache</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4</code>: Absent ⚠️
</li>
<li>
In <code>4.8</code>: Absent ⚠️
</li>
<li>
In <code>4.10</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void memcpy_page_flushcache(char *to, struct page *page, size_t offset, size_t len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/lib/usercopy_64.c (ffffffff818fd890)
Location: arch/x86/lib/usercopy_64.c:201
Inline: False
Direct callers:
  - lib/iov_iter.c:_copy_from_iter_flushcache
```
**Symbols:**

```
ffffffff818fd890-ffffffff818fd8d5: memcpy_page_flushcache (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void memcpy_page_flushcache(char *to, struct page *page, size_t offset, size_t len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/lib/usercopy_64.c (ffffffff81985380)
Location: arch/x86/lib/usercopy_64.c:201
Inline: False
Direct callers:
  - lib/iov_iter.c:_copy_from_iter_flushcache
```
**Symbols:**

```
ffffffff81985380-ffffffff819853c5: memcpy_page_flushcache (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void memcpy_page_flushcache(char *to, struct page *page, size_t offset, size_t len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/lib/usercopy_64.c (ffffffff819e18d0)
Location: arch/x86/lib/usercopy_64.c:221
Inline: False
Direct callers:
  - lib/iov_iter.c:_copy_from_iter_flushcache
```
**Symbols:**

```
ffffffff819e18d0-ffffffff819e1915: memcpy_page_flushcache (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void memcpy_page_flushcache(char *to, struct page *page, size_t offset, size_t len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/lib/usercopy_64.c (ffffffff81a1c890)
Location: arch/x86/lib/usercopy_64.c:221
Inline: False
Direct callers:
  - lib/iov_iter.c:_copy_from_iter_flushcache
```
**Symbols:**

```
ffffffff81a1c890-ffffffff81a1c8d5: memcpy_page_flushcache (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void memcpy_page_flushcache(char *to, struct page *page, size_t offset, size_t len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/lib/usercopy_64.c (ffffffff81a8c4c0)
Location: arch/x86/lib/usercopy_64.c:202
Inline: False
Direct callers:
  - lib/iov_iter.c:_copy_from_iter_flushcache
```
**Symbols:**

```
ffffffff81a8c4c0-ffffffff81a8c508: memcpy_page_flushcache (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void memcpy_page_flushcache(char *to, struct page *page, size_t offset, size_t len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/lib/usercopy_64.c (ffffffff81ac3780)
Location: arch/x86/lib/usercopy_64.c:202
Inline: False
Direct callers:
  - lib/iov_iter.c:_copy_from_iter_flushcache
```
**Symbols:**

```
ffffffff81ac3780-ffffffff81ac37c8: memcpy_page_flushcache (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void memcpy_page_flushcache(char *to, struct page *page, size_t offset, size_t len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/lib/usercopy_64.c (ffffffff815ffc80)
Location: arch/x86/lib/usercopy_64.c:203
Inline: False
Direct callers:
  - lib/iov_iter.c:_copy_from_iter_flushcache
```
**Symbols:**

```
ffffffff815ffc80-ffffffff815ffccb: memcpy_page_flushcache (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void memcpy_page_flushcache(char *to, struct page *page, size_t offset, size_t len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/lib/usercopy_64.c (ffffffff81624b70)
Location: arch/x86/lib/usercopy_64.c:182
Inline: False
Direct callers:
  - lib/iov_iter.c:_copy_from_iter_flushcache
```
**Symbols:**

```
ffffffff81624b70-ffffffff81624bbb: memcpy_page_flushcache (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void memcpy_page_flushcache(char *to, struct page *page, size_t offset, size_t len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/lib/usercopy_64.c (ffffffff81608520)
Location: arch/x86/lib/usercopy_64.c:182
Inline: False
Direct callers:
  - lib/iov_iter.c:_copy_from_iter_flushcache
  - lib/iov_iter.c:_copy_from_iter_flushcache
```
**Symbols:**

```
ffffffff81608520-ffffffff8160856b: memcpy_page_flushcache (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void memcpy_page_flushcache(char *to, struct page *page, size_t offset, size_t len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/lib/usercopy_64.c (ffffffff81677160)
Location: arch/x86/lib/usercopy_64.c:182
Inline: False
```
**Symbols:**

```
ffffffff81677160-ffffffff816771ab: memcpy_page_flushcache (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void memcpy_page_flushcache(char *to, struct page *page, size_t offset, size_t len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/lib/usercopy_64.c (ffffffff81792190)
Location: arch/x86/lib/usercopy_64.c:180
Inline: False
```
**Symbols:**

```
ffffffff81792190-ffffffff81792212: memcpy_page_flushcache (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void memcpy_page_flushcache(char *to, struct page *page, size_t offset, size_t len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/lib/usercopy_64.c (ffffffff8204ff60)
Location: arch/x86/lib/usercopy_64.c:140
Inline: False
```
**Symbols:**

```
ffffffff8204ff60-ffffffff8204ffe2: memcpy_page_flushcache (STB_GLOBAL)
```
</details>
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
void memcpy_page_flushcache(char *to, struct page *page, size_t offset, size_t len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/arm64/lib/uaccess_flushcache.c (ffff800010d83588)
Location: arch/arm64/lib/uaccess_flushcache.c:22
Inline: False
Direct callers:
  - lib/iov_iter.c:_copy_from_iter_flushcache
```
**Symbols:**

```
ffff800010d83588-ffff800010d835e8: memcpy_page_flushcache (STB_GLOBAL)
```
</details>
</li>
<li>
In <code>armhf</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void memcpy_page_flushcache(char *to, struct page *page, size_t offset, size_t len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/powerpc/lib/pmem.c (c0000000000a7f00)
Location: arch/powerpc/lib/pmem.c:54
Inline: False
Direct callers:
  - lib/iov_iter.c:_copy_from_iter_flushcache
```
**Symbols:**

```
c0000000000a7f00-c0000000000a7f3c: memcpy_page_flushcache (STB_GLOBAL)
```
</details>
</li>
<li>
In <code>riscv64</code>: Absent ⚠️
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: ✅</summary>

```c
void memcpy_page_flushcache(char *to, struct page *page, size_t offset, size_t len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/lib/usercopy_64.c (ffffffff81a625d0)
Location: arch/x86/lib/usercopy_64.c:202
Inline: False
Direct callers:
  - lib/iov_iter.c:_copy_from_iter_flushcache
```
**Symbols:**

```
ffffffff81a625d0-ffffffff81a62618: memcpy_page_flushcache (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void memcpy_page_flushcache(char *to, struct page *page, size_t offset, size_t len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/lib/usercopy_64.c (ffffffff81a1f640)
Location: arch/x86/lib/usercopy_64.c:202
Inline: False
Direct callers:
  - lib/iov_iter.c:_copy_from_iter_flushcache
```
**Symbols:**

```
ffffffff81a1f640-ffffffff81a1f688: memcpy_page_flushcache (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void memcpy_page_flushcache(char *to, struct page *page, size_t offset, size_t len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/lib/usercopy_64.c (ffffffff81ace9c0)
Location: arch/x86/lib/usercopy_64.c:202
Inline: False
Direct callers:
  - lib/iov_iter.c:_copy_from_iter_flushcache
```
**Symbols:**

```
ffffffff81ace9c0-ffffffff81acea08: memcpy_page_flushcache (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void memcpy_page_flushcache(char *to, struct page *page, size_t offset, size_t len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/lib/usercopy_64.c (ffffffff81adaed0)
Location: arch/x86/lib/usercopy_64.c:202
Inline: False
Direct callers:
  - lib/iov_iter.c:_copy_from_iter_flushcache
```
**Symbols:**

```
ffffffff81adaed0-ffffffff81adaf30: memcpy_page_flushcache (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
</ul>
<b>Arch</b>
<ul>
<li>
No changes between <code>amd64</code> and <code>arm64</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>ppc64el</code> ✅
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
