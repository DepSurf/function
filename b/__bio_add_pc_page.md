# Function: <code>__bio_add_pc_page</code>

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
int __bio_add_pc_page(struct request_queue *q, struct bio *bio, struct page *page, unsigned int len, unsigned int offset, bool put_same_page);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/bio.c (ffffffff814c4e00)
Location: block/bio.c:686
Inline: False
Direct callers:
  - block/bio.c:bio_copy_kern
  - block/bio.c:bio_map_kern
  - block/bio.c:bio_map_user_iov
  - block/bio.c:bio_copy_user_iov
```
**Symbols:**

```
ffffffff814c4e00-ffffffff814c507e: __bio_add_pc_page (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
int __bio_add_pc_page(struct request_queue *q, struct bio *bio, struct page *page, unsigned int len, unsigned int offset, bool *same_page);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/bio.c (ffffffff814dddd0)
Location: block/bio.c:733
Inline: True
Direct callers:
  - block/bio.c:bio_copy_kern
  - block/bio.c:bio_map_kern
  - block/bio.c:bio_map_user_iov
  - block/bio.c:bio_copy_user_iov
```
**Symbols:**

```
ffffffff814dddd0-ffffffff814ddf52: __bio_add_pc_page (STB_LOCAL)
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
int __bio_add_pc_page(struct request_queue *q, struct bio *bio, struct page *page, unsigned int len, unsigned int offset, bool *same_page);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/bio.c (ffff8000105da3c8)
Location: block/bio.c:733
Inline: True
Direct callers:
  - block/bio.c:bio_copy_kern
  - block/bio.c:bio_map_kern
  - block/bio.c:bio_map_kern
  - block/bio.c:bio_map_user_iov
  - block/bio.c:bio_copy_user_iov
```
**Symbols:**

```
ffff8000105da3c8-ffff8000105da58c: __bio_add_pc_page (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In block/bio.c (c07880bc)
Location: block/bio.c:733
Inline: True
Direct callers:
  - block/bio.c:bio_copy_kern
  - block/bio.c:bio_map_kern
  - block/bio.c:bio_map_user_iov
  - block/bio.c:bio_copy_user_iov
```
**Symbols:**

```
c07880bc-c0788288: __bio_add_pc_page.constprop.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
int __bio_add_pc_page(struct request_queue *q, struct bio *bio, struct page *page, unsigned int len, unsigned int offset, bool *same_page);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/bio.c (c00000000076b200)
Location: block/bio.c:733
Inline: True
Direct callers:
  - block/bio.c:bio_copy_kern
  - block/bio.c:bio_map_kern
  - block/bio.c:bio_map_kern
  - block/bio.c:bio_map_user_iov
  - block/bio.c:bio_copy_user_iov
```
**Symbols:**

```
c00000000076b200-c00000000076b424: __bio_add_pc_page (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
int __bio_add_pc_page(struct request_queue *q, struct bio *bio, struct page *page, unsigned int len, unsigned int offset, bool *same_page);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/bio.c (ffffffe00041e168)
Location: block/bio.c:733
Inline: True
Direct callers:
  - block/bio.c:bio_copy_kern
  - block/bio.c:bio_map_kern
  - block/bio.c:bio_map_user_iov
  - block/bio.c:bio_copy_user_iov
```
**Symbols:**

```
ffffffe00041e168-ffffffe00041e2ba: __bio_add_pc_page (STB_LOCAL)
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
int __bio_add_pc_page(struct request_queue *q, struct bio *bio, struct page *page, unsigned int len, unsigned int offset, bool *same_page);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/bio.c (ffffffff814d63b0)
Location: block/bio.c:733
Inline: True
Direct callers:
  - block/bio.c:bio_copy_kern
  - block/bio.c:bio_map_kern
  - block/bio.c:bio_map_user_iov
  - block/bio.c:bio_copy_user_iov
```
**Symbols:**

```
ffffffff814d63b0-ffffffff814d6532: __bio_add_pc_page (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
int __bio_add_pc_page(struct request_queue *q, struct bio *bio, struct page *page, unsigned int len, unsigned int offset, bool *same_page);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/bio.c (ffffffff814c6d10)
Location: block/bio.c:733
Inline: True
Direct callers:
  - block/bio.c:bio_copy_kern
  - block/bio.c:bio_map_kern
  - block/bio.c:bio_map_user_iov
  - block/bio.c:bio_copy_user_iov
```
**Symbols:**

```
ffffffff814c6d10-ffffffff814c6e92: __bio_add_pc_page (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
int __bio_add_pc_page(struct request_queue *q, struct bio *bio, struct page *page, unsigned int len, unsigned int offset, bool *same_page);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/bio.c (ffffffff814d2440)
Location: block/bio.c:733
Inline: True
Direct callers:
  - block/bio.c:bio_copy_kern
  - block/bio.c:bio_map_kern
  - block/bio.c:bio_map_user_iov
  - block/bio.c:bio_copy_user_iov
```
**Symbols:**

```
ffffffff814d2440-ffffffff814d25c2: __bio_add_pc_page (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
int __bio_add_pc_page(struct request_queue *q, struct bio *bio, struct page *page, unsigned int len, unsigned int offset, bool *same_page);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/bio.c (ffffffff814eaf60)
Location: block/bio.c:733
Inline: True
Direct callers:
  - block/bio.c:bio_copy_kern
  - block/bio.c:bio_map_kern
  - block/bio.c:bio_map_user_iov
  - block/bio.c:bio_copy_user_iov
```
**Symbols:**

```
ffffffff814eaf60-ffffffff814eb0e2: __bio_add_pc_page (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
<details>
<summary>Changed between <code>5.3</code> and <code>5.4</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>bool *same_page</code>
</li>
<li>
<b>Param removed. </b>
<code>bool put_same_page</code>
</li>
</ul>
</details>
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
