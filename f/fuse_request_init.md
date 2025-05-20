# Function: <code>fuse_request_init</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void fuse_request_init(struct fuse_req *req, struct page **pages, struct fuse_page_desc *page_descs, unsigned int npages);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fuse/dev.c (ffffffff8130d740)
Location: fs/fuse/dev.c:38
Inline: False
Direct callers:
  - fs/fuse/dev.c:__fuse_request_alloc
```
**Symbols:**

```
ffffffff8130d740-ffffffff8130d806: fuse_request_init (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void fuse_request_init(struct fuse_req *req, struct page **pages, struct fuse_page_desc *page_descs, unsigned int npages);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fuse/dev.c (ffffffff81341a50)
Location: fs/fuse/dev.c:38
Inline: False
Direct callers:
  - fs/fuse/dev.c:__fuse_request_alloc
```
**Symbols:**

```
ffffffff81341a50-ffffffff81341b16: fuse_request_init (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void fuse_request_init(struct fuse_req *req, struct page **pages, struct fuse_page_desc *page_descs, unsigned int npages);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fuse/dev.c (ffffffff813578a0)
Location: fs/fuse/dev.c:38
Inline: False
Direct callers:
  - fs/fuse/dev.c:__fuse_request_alloc
```
**Symbols:**

```
ffffffff813578a0-ffffffff81357966: fuse_request_init (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void fuse_request_init(struct fuse_req *req, struct page **pages, struct fuse_page_desc *page_descs, unsigned int npages);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fuse/dev.c (ffffffff8136c400)
Location: fs/fuse/dev.c:39
Inline: False
Direct callers:
  - fs/fuse/dev.c:__fuse_request_alloc
```
**Symbols:**

```
ffffffff8136c400-ffffffff8136c4c6: fuse_request_init (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void fuse_request_init(struct fuse_req *req, struct page **pages, struct fuse_page_desc *page_descs, unsigned int npages);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fuse/dev.c (ffffffff81390fe0)
Location: fs/fuse/dev.c:39
Inline: False
Direct callers:
  - fs/fuse/dev.c:__fuse_request_alloc
```
**Symbols:**

```
ffffffff81390fe0-ffffffff813910a6: fuse_request_init (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void fuse_request_init(struct fuse_req *req, struct page **pages, struct fuse_page_desc *page_descs, unsigned int npages);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fuse/dev.c (ffffffff813c0050)
Location: fs/fuse/dev.c:39
Inline: False
Direct callers:
  - fs/fuse/dev.c:__fuse_request_alloc
```
**Symbols:**

```
ffffffff813c0050-ffffffff813c0118: fuse_request_init (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/fuse/dev.c (ffffffff813d9676)
Location: fs/fuse/dev.c:43
Inline: True
Inline callers:
  - fs/fuse/dev.c:__fuse_request_alloc
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/fuse/dev.c (ffffffff8140520e)
Location: fs/fuse/dev.c:43
Inline: True
Inline callers:
  - fs/fuse/dev.c:__fuse_request_alloc
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/fuse/dev.c (ffffffff8141f337)
Location: fs/fuse/dev.c:43
Inline: True
Inline callers:
  - fs/fuse/dev.c:fuse_request_alloc
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/fuse/dev.c (ffffffff8146e815)
Location: fs/fuse/dev.c:43
Inline: True
Inline callers:
  - fs/fuse/dev.c:fuse_simple_background
  - fs/fuse/dev.c:fuse_simple_request
  - fs/fuse/dev.c:fuse_get_req
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/fuse/dev.c (ffffffff81488f95)
Location: fs/fuse/dev.c:43
Inline: True
Inline callers:
  - fs/fuse/dev.c:fuse_simple_background
  - fs/fuse/dev.c:fuse_simple_request
  - fs/fuse/dev.c:fuse_get_req
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/fuse/dev.c (ffffffff8148e89a)
Location: fs/fuse/dev.c:43
Inline: True
Inline callers:
  - fs/fuse/dev.c:fuse_simple_background
  - fs/fuse/dev.c:fuse_simple_request
  - fs/fuse/dev.c:fuse_get_req
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/fuse/dev.c (ffffffff814e630a)
Location: fs/fuse/dev.c:43
Inline: True
Inline callers:
  - fs/fuse/dev.c:fuse_simple_background
  - fs/fuse/dev.c:fuse_simple_request
  - fs/fuse/dev.c:fuse_get_req
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/fuse/dev.c (ffffffff81574e98)
Location: fs/fuse/dev.c:43
Inline: True
Inline callers:
  - fs/fuse/dev.c:fuse_simple_background
  - fs/fuse/dev.c:fuse_simple_request
  - fs/fuse/dev.c:fuse_get_req
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/fuse/dev.c (ffffffff81619539)
Location: fs/fuse/dev.c:43
Inline: True
Inline callers:
  - fs/fuse/dev.c:fuse_request_alloc
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/fuse/dev.c (ffffffff81651689)
Location: fs/fuse/dev.c:43
Inline: True
Inline callers:
  - fs/fuse/dev.c:fuse_request_alloc
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/fuse/dev.c (ffffffff8168ac99)
Location: fs/fuse/dev.c:43
Inline: True
Inline callers:
  - fs/fuse/dev.c:fuse_request_alloc
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/fuse/dev.c (ffff8000105015bc)
Location: fs/fuse/dev.c:43
Inline: True
Inline callers:
  - fs/fuse/dev.c:fuse_request_alloc
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/fuse/dev.c (c06be3b4)
Location: fs/fuse/dev.c:43
Inline: True
Inline callers:
  - fs/fuse/dev.c:fuse_request_alloc
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/fuse/dev.c (c000000000645ca0)
Location: fs/fuse/dev.c:43
Inline: True
Inline callers:
  - fs/fuse/dev.c:fuse_request_alloc
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/fuse/dev.c (ffffffe00036ec50)
Location: fs/fuse/dev.c:43
Inline: True
Inline callers:
  - fs/fuse/dev.c:fuse_request_alloc
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/fuse/dev.c (ffffffff81417917)
Location: fs/fuse/dev.c:43
Inline: True
Inline callers:
  - fs/fuse/dev.c:fuse_request_alloc
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/fuse/dev.c (ffffffff81408397)
Location: fs/fuse/dev.c:43
Inline: True
Inline callers:
  - fs/fuse/dev.c:fuse_request_alloc
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/fuse/dev.c (ffffffff81413ab7)
Location: fs/fuse/dev.c:43
Inline: True
Inline callers:
  - fs/fuse/dev.c:fuse_request_alloc
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/fuse/dev.c (ffffffff8142a937)
Location: fs/fuse/dev.c:43
Inline: True
Inline callers:
  - fs/fuse/dev.c:fuse_request_alloc
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
</ul>
