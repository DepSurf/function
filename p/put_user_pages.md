# Function: <code>put_user_pages</code>

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
In <code>4.13</code>: Absent ⚠️
</li>
<li>
In <code>4.15</code>: Absent ⚠️
</li>
<li>
In <code>4.18</code>: Absent ⚠️
</li>
<li>
In <code>5.0</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void put_user_pages(struct page **pages, long unsigned int npages);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/gup.c (ffffffff8124a8b0)
Location: mm/gup.c:123
Inline: False
```
**Symbols:**

```
ffffffff8124a8b0-ffffffff8124a92b: put_user_pages (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
void put_user_pages(struct page **pages, long unsigned int npages);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/gup.c (ffffffff81258d80)
Location: mm/gup.c:108
Inline: True
Direct callers:
  - fs/io_uring.c:io_sqe_buffer_register
```
**Symbols:**

```
ffffffff81258d80-ffffffff81258dfb: put_user_pages (STB_GLOBAL)
```
</details>
</li>
<li>
In <code>5.8</code>: Absent ⚠️
</li>
<li>
In <code>5.11</code>: Absent ⚠️
</li>
<li>
In <code>5.13</code>: Absent ⚠️
</li>
<li>
In <code>5.15</code>: Absent ⚠️
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
void put_user_pages(struct page **pages, long unsigned int npages);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/gup.c (ffff8000102f0d40)
Location: mm/gup.c:108
Inline: True
Direct callers:
  - fs/io_uring.c:io_sqe_buffer_register
```
**Symbols:**

```
ffff8000102f0d40-ffff8000102f0dd4: put_user_pages (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
void put_user_pages(struct page **pages, long unsigned int npages);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/gup.c (c051451c)
Location: mm/gup.c:108
Inline: True
Direct callers:
  - fs/io_uring.c:io_sqe_buffer_register
```
**Symbols:**

```
c051451c-c0514598: put_user_pages (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
void put_user_pages(struct page **pages, long unsigned int npages);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/gup.c (c0000000003b58f0)
Location: mm/gup.c:108
Inline: True
Direct callers:
  - fs/io_uring.c:io_sqe_buffer_register
```
**Symbols:**

```
c0000000003b58f0-c0000000003b59dc: put_user_pages (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
void put_user_pages(struct page **pages, long unsigned int npages);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/gup.c (ffffffe00020443c)
Location: mm/gup.c:108
Inline: True
Direct callers:
  - fs/io_uring.c:io_sqe_buffer_register
```
**Symbols:**

```
ffffffe00020443c-ffffffe0002044a8: put_user_pages (STB_GLOBAL)
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
void put_user_pages(struct page **pages, long unsigned int npages);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/gup.c (ffffffff812513d0)
Location: mm/gup.c:108
Inline: True
Direct callers:
  - fs/io_uring.c:io_sqe_buffer_register
```
**Symbols:**

```
ffffffff812513d0-ffffffff8125144b: put_user_pages (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
void put_user_pages(struct page **pages, long unsigned int npages);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/gup.c (ffffffff812442c0)
Location: mm/gup.c:108
Inline: True
Direct callers:
  - fs/io_uring.c:io_sqe_buffer_register
```
**Symbols:**

```
ffffffff812442c0-ffffffff8124433b: put_user_pages (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
void put_user_pages(struct page **pages, long unsigned int npages);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/gup.c (ffffffff8124f170)
Location: mm/gup.c:108
Inline: True
Direct callers:
  - fs/io_uring.c:io_sqe_buffer_register
```
**Symbols:**

```
ffffffff8124f170-ffffffff8124f1eb: put_user_pages (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
void put_user_pages(struct page **pages, long unsigned int npages);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/gup.c (ffffffff8125eae0)
Location: mm/gup.c:108
Inline: True
Direct callers:
  - fs/io_uring.c:io_sqe_buffer_register
```
**Symbols:**

```
ffffffff8125eae0-ffffffff8125eb5b: put_user_pages (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>5.3</code> and <code>5.4</code> ✅
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
