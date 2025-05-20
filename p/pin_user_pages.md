# Function: <code>pin_user_pages</code>

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
In <code>5.3</code>: Absent ⚠️
</li>
<li>
In <code>5.4</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
long int pin_user_pages(long unsigned int start, long unsigned int nr_pages, unsigned int gup_flags, struct page **pages, struct vm_area_struct **vmas);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/gup.c (ffffffff8128a4f0)
Location: mm/gup.c:3027
Inline: False
Direct callers:
  - fs/io_uring.c:io_sqe_buffer_register
  - net/xdp/xdp_umem.c:xdp_umem_pin_pages
```
**Symbols:**

```
ffffffff8128a4f0-ffffffff8128a539: pin_user_pages (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
long int pin_user_pages(long unsigned int start, long unsigned int nr_pages, unsigned int gup_flags, struct page **pages, struct vm_area_struct **vmas);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/gup.c (ffffffff812940d0)
Location: mm/gup.c:2814
Inline: False
Direct callers:
  - fs/io_uring.c:io_sqe_buffer_register
  - net/xdp/xdp_umem.c:xdp_umem_pin_pages
```
**Symbols:**

```
ffffffff812940d0-ffffffff81294123: pin_user_pages (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
long int pin_user_pages(long unsigned int start, long unsigned int nr_pages, unsigned int gup_flags, struct page **pages, struct vm_area_struct **vmas);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/gup.c (ffffffff81299b60)
Location: mm/gup.c:2880
Inline: False
Direct callers:
  - fs/io_uring.c:io_sqe_buffer_register
  - net/xdp/xdp_umem.c:xdp_umem_pin_pages
```
**Symbols:**

```
ffffffff81299b60-ffffffff81299ba1: pin_user_pages (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
long int pin_user_pages(long unsigned int start, long unsigned int nr_pages, unsigned int gup_flags, struct page **pages, struct vm_area_struct **vmas);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/gup.c (ffffffff812da4f0)
Location: mm/gup.c:2975
Inline: False
Direct callers:
  - fs/io_uring.c:io_sqe_buffer_register
  - net/xdp/xdp_umem.c:xdp_umem_reg
```
**Symbols:**

```
ffffffff812da4f0-ffffffff812da531: pin_user_pages (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
long int pin_user_pages(long unsigned int start, long unsigned int nr_pages, unsigned int gup_flags, struct page **pages, struct vm_area_struct **vmas);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/gup.c (ffffffff81339f40)
Location: mm/gup.c:3132
Inline: False
Direct callers:
  - io_uring/io_uring.c:io_pin_pages
  - net/xdp/xdp_umem.c:xdp_umem_pin_pages
```
**Symbols:**

```
ffffffff81339f40-ffffffff81339fc6: pin_user_pages (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
long int pin_user_pages(long unsigned int start, long unsigned int nr_pages, unsigned int gup_flags, struct page **pages, struct vm_area_struct **vmas);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/gup.c (ffffffff813b1de0)
Location: mm/gup.c:3158
Inline: False
Direct callers:
  - io_uring/rsrc.c:io_pin_pages
  - net/xdp/xdp_umem.c:xdp_umem_reg
```
**Symbols:**

```
ffffffff813b1de0-ffffffff813b1e68: pin_user_pages (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
long int pin_user_pages(long unsigned int start, long unsigned int nr_pages, unsigned int gup_flags, struct page **pages);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/gup.c (ffffffff813e6a80)
Location: mm/gup.c:3364
Inline: False
Direct callers:
  - io_uring/rsrc.c:io_pin_pages
  - net/xdp/xdp_umem.c:xdp_umem_reg
```
**Symbols:**

```
ffffffff813e6a80-ffffffff813e6b35: pin_user_pages (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
long int pin_user_pages(long unsigned int start, long unsigned int nr_pages, unsigned int gup_flags, struct page **pages);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/gup.c (ffffffff81411710)
Location: mm/gup.c:3382
Inline: False
Direct callers:
  - io_uring/rsrc.c:io_pin_pages
  - net/xdp/xdp_umem.c:xdp_umem_reg
```
**Symbols:**

```
ffffffff81411710-ffffffff814117c5: pin_user_pages (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
In <code>arm64</code>: Absent ⚠️
</li>
<li>
In <code>armhf</code>: Absent ⚠️
</li>
<li>
In <code>ppc64el</code>: Absent ⚠️
</li>
<li>
In <code>riscv64</code>: Absent ⚠️
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
In <code>aws</code>: Absent ⚠️
</li>
<li>
In <code>azure</code>: Absent ⚠️
</li>
<li>
In <code>gcp</code>: Absent ⚠️
</li>
<li>
In <code>lowlatency</code>: Absent ⚠️
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
<details>
<summary>Changed between <code>6.2</code> and <code>6.5</code> ⚠️</summary>
<ul>
<li>
<b>Param removed. </b>
<code>struct vm_area_struct **vmas</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>6.5</code> and <code>6.8</code> ✅
</li>
</ul>
