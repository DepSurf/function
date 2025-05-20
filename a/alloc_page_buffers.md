# Function: <code>alloc_page_buffers</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
struct buffer_head *alloc_page_buffers(struct page *page, long unsigned int size, int retry);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/buffer.c (ffffffff812437b0)
Location: fs/buffer.c:872
Inline: False
Direct callers:
  - fs/buffer.c:create_empty_buffers
  - fs/buffer.c:nobh_write_begin
  - drivers/md/bitmap.c:read_page
```
**Symbols:**

```
ffffffff812437b0-ffffffff81243883: alloc_page_buffers (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
struct buffer_head *alloc_page_buffers(struct page *page, long unsigned int size, int retry);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/buffer.c (ffffffff8126b8a0)
Location: fs/buffer.c:865
Inline: False
Direct callers:
  - fs/buffer.c:nobh_write_begin
  - fs/buffer.c:create_empty_buffers
  - drivers/md/bitmap.c:read_page
```
**Symbols:**

```
ffffffff8126b8a0-ffffffff8126b977: alloc_page_buffers (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
struct buffer_head *alloc_page_buffers(struct page *page, long unsigned int size, int retry);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/buffer.c (ffffffff8127e9e0)
Location: fs/buffer.c:866
Inline: False
Direct callers:
  - fs/buffer.c:nobh_write_begin
  - fs/buffer.c:create_empty_buffers
  - fs/buffer.c:__getblk_gfp
  - drivers/md/bitmap.c:read_page
```
**Symbols:**

```
ffffffff8127e9e0-ffffffff8127eab3: alloc_page_buffers (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
struct buffer_head *alloc_page_buffers(struct page *page, long unsigned int size, int retry);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/buffer.c (ffffffff8128c360)
Location: fs/buffer.c:863
Inline: False
Direct callers:
  - fs/buffer.c:nobh_write_begin
  - fs/buffer.c:create_empty_buffers
  - fs/buffer.c:__getblk_gfp
  - drivers/md/bitmap.c:read_page
```
**Symbols:**

```
ffffffff8128c360-ffffffff8128c435: alloc_page_buffers (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
struct buffer_head *alloc_page_buffers(struct page *page, long unsigned int size, bool retry);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/buffer.c (ffffffff812aee40)
Location: fs/buffer.c:842
Inline: False
Direct callers:
  - fs/buffer.c:nobh_write_begin
  - fs/buffer.c:create_empty_buffers
  - fs/buffer.c:__getblk_gfp
  - drivers/md/md-bitmap.c:read_page
```
**Symbols:**

```
ffffffff812aee40-ffffffff812aeef4: alloc_page_buffers (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
struct buffer_head *alloc_page_buffers(struct page *page, long unsigned int size, bool retry);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/buffer.c (ffffffff812d6970)
Location: fs/buffer.c:812
Inline: False
Direct callers:
  - fs/buffer.c:nobh_write_begin
  - fs/buffer.c:create_empty_buffers
  - fs/buffer.c:__getblk_gfp
  - drivers/md/md-bitmap.c:read_page
```
**Symbols:**

```
ffffffff812d6970-ffffffff812d6a15: alloc_page_buffers (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
struct buffer_head *alloc_page_buffers(struct page *page, long unsigned int size, bool retry);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/buffer.c (ffffffff812ebdf0)
Location: fs/buffer.c:813
Inline: False
Direct callers:
  - fs/buffer.c:nobh_write_begin
  - fs/buffer.c:create_empty_buffers
  - fs/buffer.c:__getblk_gfp
  - drivers/md/md-bitmap.c:read_page
```
**Symbols:**

```
ffffffff812ebdf0-ffffffff812ebf21: alloc_page_buffers (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
struct buffer_head *alloc_page_buffers(struct page *page, long unsigned int size, bool retry);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/buffer.c (ffffffff8130d510)
Location: fs/buffer.c:814
Inline: False
Direct callers:
  - fs/buffer.c:nobh_write_begin
  - fs/buffer.c:create_empty_buffers
  - fs/buffer.c:__getblk_gfp
  - drivers/md/md-bitmap.c:read_page
```
**Symbols:**

```
ffffffff8130d510-ffffffff8130d669: alloc_page_buffers (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
struct buffer_head *alloc_page_buffers(struct page *page, long unsigned int size, bool retry);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/buffer.c (ffffffff813204e0)
Location: fs/buffer.c:814
Inline: False
Direct callers:
  - fs/buffer.c:nobh_write_begin
  - fs/buffer.c:create_empty_buffers
  - fs/buffer.c:__getblk_gfp
  - drivers/md/md-bitmap.c:read_page
```
**Symbols:**

```
ffffffff813204e0-ffffffff81320639: alloc_page_buffers (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
struct buffer_head *alloc_page_buffers(struct page *page, long unsigned int size, bool retry);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/buffer.c (ffffffff81359940)
Location: fs/buffer.c:840
Inline: False
Direct callers:
  - fs/buffer.c:nobh_write_begin
  - fs/buffer.c:create_empty_buffers
  - fs/buffer.c:grow_dev_page
```
**Symbols:**

```
ffffffff81359940-ffffffff81359a89: alloc_page_buffers (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
struct buffer_head *alloc_page_buffers(struct page *page, long unsigned int size, bool retry);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/buffer.c (ffffffff81367a20)
Location: fs/buffer.c:839
Inline: False
Direct callers:
  - fs/buffer.c:nobh_write_begin
  - fs/buffer.c:create_empty_buffers
  - fs/buffer.c:grow_dev_page
```
**Symbols:**

```
ffffffff81367a20-ffffffff81367bbd: alloc_page_buffers (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
struct buffer_head *alloc_page_buffers(struct page *page, long unsigned int size, bool retry);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/buffer.c (ffffffff8136e620)
Location: fs/buffer.c:839
Inline: False
Direct callers:
  - fs/buffer.c:nobh_write_begin
  - fs/buffer.c:create_empty_buffers
  - fs/buffer.c:grow_dev_page
```
**Symbols:**

```
ffffffff8136e620-ffffffff8136e772: alloc_page_buffers (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
struct buffer_head *alloc_page_buffers(struct page *page, long unsigned int size, bool retry);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/buffer.c (ffffffff813bd8b0)
Location: fs/buffer.c:814
Inline: False
Direct callers:
  - fs/buffer.c:nobh_write_begin
  - fs/buffer.c:create_empty_buffers
  - fs/buffer.c:grow_dev_page
```
**Symbols:**

```
ffffffff813bd8b0-ffffffff813bda43: alloc_page_buffers (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
struct buffer_head *alloc_page_buffers(struct page *page, long unsigned int size, bool retry);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/buffer.c (ffffffff814444a0)
Location: fs/buffer.c:811
Inline: False
Direct callers:
  - fs/buffer.c:nobh_write_begin
  - fs/buffer.c:create_empty_buffers
  - fs/buffer.c:grow_dev_page
```
**Symbols:**

```
ffffffff814444a0-ffffffff8144465c: alloc_page_buffers (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
struct buffer_head *alloc_page_buffers(struct page *page, long unsigned int size, bool retry);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/buffer.c (ffffffff814d3710)
Location: fs/buffer.c:811
Inline: False
Direct callers:
  - fs/buffer.c:create_empty_buffers
  - fs/buffer.c:grow_dev_page
```
**Symbols:**

```
ffffffff814d3710-ffffffff814d38cc: alloc_page_buffers (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
struct buffer_head *alloc_page_buffers(struct page *page, long unsigned int size, bool retry);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/buffer.c (ffffffff8150a350)
Location: fs/buffer.c:972
Inline: False
```
**Symbols:**

```
ffffffff8150a350-ffffffff8150a3c3: alloc_page_buffers (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
struct buffer_head *alloc_page_buffers(struct page *page, long unsigned int size, bool retry);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/buffer.c (ffffffff8153f260)
Location: fs/buffer.c:956
Inline: False
```
**Symbols:**

```
ffffffff8153f260-ffffffff8153f2de: alloc_page_buffers (STB_GLOBAL)
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
struct buffer_head *alloc_page_buffers(struct page *page, long unsigned int size, bool retry);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/buffer.c (ffff8000103d9150)
Location: fs/buffer.c:814
Inline: False
Direct callers:
  - fs/buffer.c:nobh_write_begin
  - fs/buffer.c:create_empty_buffers
  - fs/buffer.c:__getblk_gfp
  - drivers/md/md-bitmap.c:read_page
```
**Symbols:**

```
ffff8000103d9150-ffff8000103d9300: alloc_page_buffers (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
struct buffer_head *alloc_page_buffers(struct page *page, long unsigned int size, bool retry);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/buffer.c (c05b1ebc)
Location: fs/buffer.c:814
Inline: False
Direct callers:
  - fs/buffer.c:nobh_write_begin
  - fs/buffer.c:create_empty_buffers
  - fs/buffer.c:__getblk_slow
  - drivers/md/md-bitmap.c:read_page
```
**Symbols:**

```
c05b1ebc-c05b2098: alloc_page_buffers (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
struct buffer_head *alloc_page_buffers(struct page *page, long unsigned int size, bool retry);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/buffer.c (c0000000004dd140)
Location: fs/buffer.c:814
Inline: False
Direct callers:
  - fs/buffer.c:nobh_write_begin
  - fs/buffer.c:create_empty_buffers
  - fs/buffer.c:__getblk_gfp
  - drivers/md/md-bitmap.c:read_page
```
**Symbols:**

```
c0000000004dd140-c0000000004dd36c: alloc_page_buffers (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
struct buffer_head *alloc_page_buffers(struct page *page, long unsigned int size, bool retry);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/buffer.c (ffffffe000291cca)
Location: fs/buffer.c:814
Inline: False
Direct callers:
  - fs/buffer.c:nobh_write_begin
  - fs/buffer.c:create_empty_buffers
  - fs/buffer.c:__getblk_gfp
  - drivers/md/md-bitmap.c:read_page
```
**Symbols:**

```
ffffffe000291cca-ffffffe000291e3e: alloc_page_buffers (STB_GLOBAL)
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
struct buffer_head *alloc_page_buffers(struct page *page, long unsigned int size, bool retry);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/buffer.c (ffffffff81318ac0)
Location: fs/buffer.c:814
Inline: False
Direct callers:
  - fs/buffer.c:nobh_write_begin
  - fs/buffer.c:create_empty_buffers
  - fs/buffer.c:__getblk_gfp
  - drivers/md/md-bitmap.c:read_page
```
**Symbols:**

```
ffffffff81318ac0-ffffffff81318c19: alloc_page_buffers (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
struct buffer_head *alloc_page_buffers(struct page *page, long unsigned int size, bool retry);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/buffer.c (ffffffff813096b0)
Location: fs/buffer.c:814
Inline: False
Direct callers:
  - fs/buffer.c:nobh_write_begin
  - fs/buffer.c:create_empty_buffers
  - fs/buffer.c:__getblk_gfp
  - drivers/md/md-bitmap.c:read_page
```
**Symbols:**

```
ffffffff813096b0-ffffffff81309809: alloc_page_buffers (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
struct buffer_head *alloc_page_buffers(struct page *page, long unsigned int size, bool retry);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/buffer.c (ffffffff81316590)
Location: fs/buffer.c:814
Inline: False
Direct callers:
  - fs/buffer.c:nobh_write_begin
  - fs/buffer.c:create_empty_buffers
  - fs/buffer.c:__getblk_gfp
  - drivers/md/md-bitmap.c:read_page
```
**Symbols:**

```
ffffffff81316590-ffffffff813166e9: alloc_page_buffers (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
struct buffer_head *alloc_page_buffers(struct page *page, long unsigned int size, bool retry);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/buffer.c (ffffffff81328380)
Location: fs/buffer.c:814
Inline: False
Direct callers:
  - fs/buffer.c:nobh_write_begin
  - fs/buffer.c:create_empty_buffers
  - fs/buffer.c:__getblk_gfp
  - drivers/md/md-bitmap.c:read_page
```
**Symbols:**

```
ffffffff81328380-ffffffff813284e1: alloc_page_buffers (STB_GLOBAL)
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
<details>
<summary>Changed between <code>4.13</code> and <code>4.15</code> ⚠️</summary>
<ul>
<li>
<b>Param type changed. </b>
<code>int retry</code> ➡️ <code>bool retry</code>
</li>
</ul>
</details>
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
