# Function: <code>verify_page</code>

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
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
bool verify_page(struct inode *inode, const struct fsverity_info *vi, struct ahash_request *req, struct page *data_page);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/verity/verify.c (0)
Location: fs/verity/verify.c:86
Inline: False
Direct callers:
  - fs/verity/verify.c:fsverity_verify_bio
  - fs/verity/verify.c:fsverity_verify_page
```
**Symbols:**

```
ffffffff81351160-ffffffff81351731: verify_page (STB_LOCAL)
ffffffff81351995-ffffffff81351a7c: verify_page.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
bool verify_page(struct inode *inode, const struct fsverity_info *vi, struct ahash_request *req, struct page *data_page, long unsigned int level0_ra_pages);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/verity/verify.c (0)
Location: fs/verity/verify.c:86
Inline: False
Direct callers:
  - fs/verity/verify.c:fsverity_verify_bio
  - fs/verity/verify.c:fsverity_verify_page
```
**Symbols:**

```
ffffffff81397ba0-ffffffff8139818d: verify_page (STB_LOCAL)
ffffffff813983e5-ffffffff813984cc: verify_page.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
bool verify_page(struct inode *inode, const struct fsverity_info *vi, struct ahash_request *req, struct page *data_page, long unsigned int level0_ra_pages);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/verity/verify.c (0)
Location: fs/verity/verify.c:86
Inline: False
Direct callers:
  - fs/verity/verify.c:fsverity_verify_bio
  - fs/verity/verify.c:fsverity_verify_page
```
**Symbols:**

```
ffffffff813a9420-ffffffff813a9a07: verify_page (STB_LOCAL)
ffffffff81beb794-ffffffff81beb87b: verify_page.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
bool verify_page(struct inode *inode, const struct fsverity_info *vi, struct ahash_request *req, struct page *data_page, long unsigned int level0_ra_pages);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/verity/verify.c (0)
Location: fs/verity/verify.c:86
Inline: False
Direct callers:
  - fs/verity/verify.c:fsverity_verify_bio
  - fs/verity/verify.c:fsverity_verify_page
```
**Symbols:**

```
ffffffff813b0960-ffffffff813b0f4b: verify_page (STB_LOCAL)
ffffffff81bdd818-ffffffff81bdd8ff: verify_page.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
bool verify_page(struct inode *inode, const struct fsverity_info *vi, struct ahash_request *req, struct page *data_page, long unsigned int level0_ra_pages);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/verity/verify.c (0)
Location: fs/verity/verify.c:86
Inline: False
Direct callers:
  - fs/verity/verify.c:fsverity_verify_bio
  - fs/verity/verify.c:fsverity_verify_page
```
**Symbols:**

```
ffffffff81400540-ffffffff81400c23: verify_page (STB_LOCAL)
ffffffff81cc7168-ffffffff81cc72d3: verify_page.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
bool verify_page(struct inode *inode, const struct fsverity_info *vi, struct ahash_request *req, struct page *data_page, long unsigned int level0_ra_pages);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/verity/verify.c (0)
Location: fs/verity/verify.c:86
Inline: False
Direct callers:
  - fs/verity/verify.c:fsverity_verify_bio
  - fs/verity/verify.c:fsverity_verify_page
```
**Symbols:**

```
ffffffff81474480-ffffffff81474c9f: verify_page (STB_LOCAL)
ffffffff81e796e0-ffffffff81e7983a: verify_page.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
bool verify_page(struct inode *inode, const struct fsverity_info *vi, struct ahash_request *req, struct page *data_page, long unsigned int level0_ra_pages);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/verity/verify.c (0)
Location: fs/verity/verify.c:76
Inline: False
Direct callers:
  - fs/verity/verify.c:fsverity_verify_bio
  - fs/verity/verify.c:fsverity_verify_page
```
**Symbols:**

```
ffffffff815066b0-ffffffff81507057: verify_page (STB_LOCAL)
ffffffff8206aa69-ffffffff8206aaff: verify_page.cold (STB_LOCAL)
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
bool verify_page(struct inode *inode, const struct fsverity_info *vi, struct ahash_request *req, struct page *data_page);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/verity/verify.c (ffff8000104131c0)
Location: fs/verity/verify.c:86
Inline: False
Direct callers:
  - fs/verity/verify.c:fsverity_verify_bio
  - fs/verity/verify.c:fsverity_verify_page
```
**Symbols:**

```
ffff8000104131c0-ffff8000104137c8: verify_page (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
bool verify_page(struct inode *inode, const struct fsverity_info *vi, struct ahash_request *req, struct page *data_page);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/verity/verify.c (c05df498)
Location: fs/verity/verify.c:86
Inline: False
Direct callers:
  - fs/verity/verify.c:fsverity_verify_bio
  - fs/verity/verify.c:fsverity_verify_page
```
**Symbols:**

```
c05df498-c05dfb20: verify_page (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
bool verify_page(struct inode *inode, const struct fsverity_info *vi, struct ahash_request *req, struct page *data_page);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/verity/verify.c (c000000000520fa0)
Location: fs/verity/verify.c:86
Inline: False
Direct callers:
  - fs/verity/verify.c:fsverity_verify_bio
  - fs/verity/verify.c:fsverity_verify_page
```
**Symbols:**

```
c000000000520fa0-c000000000521820: verify_page (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
bool verify_page(struct inode *inode, const struct fsverity_info *vi, struct ahash_request *req, struct page *data_page);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/verity/verify.c (ffffffe0002bad68)
Location: fs/verity/verify.c:86
Inline: False
Direct callers:
  - fs/verity/verify.c:fsverity_verify_bio
  - fs/verity/verify.c:fsverity_verify_page
```
**Symbols:**

```
ffffffe0002bad68-ffffffe0002bb264: verify_page (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Transformation ⚠️</summary>

```c
bool verify_page(struct inode *inode, const struct fsverity_info *vi, struct ahash_request *req, struct page *data_page);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/verity/verify.c (0)
Location: fs/verity/verify.c:86
Inline: False
Direct callers:
  - fs/verity/verify.c:fsverity_verify_bio
  - fs/verity/verify.c:fsverity_verify_page
```
**Symbols:**

```
ffffffff81349740-ffffffff81349d11: verify_page (STB_LOCAL)
ffffffff81349f75-ffffffff8134a05c: verify_page.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Transformation ⚠️</summary>

```c
bool verify_page(struct inode *inode, const struct fsverity_info *vi, struct ahash_request *req, struct page *data_page);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/verity/verify.c (0)
Location: fs/verity/verify.c:86
Inline: False
Direct callers:
  - fs/verity/verify.c:fsverity_verify_bio
  - fs/verity/verify.c:fsverity_verify_page
```
**Symbols:**

```
ffffffff8133a420-ffffffff8133a9f1: verify_page (STB_LOCAL)
ffffffff8133ac55-ffffffff8133ad3c: verify_page.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Transformation ⚠️</summary>

```c
bool verify_page(struct inode *inode, const struct fsverity_info *vi, struct ahash_request *req, struct page *data_page);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/verity/verify.c (0)
Location: fs/verity/verify.c:86
Inline: False
Direct callers:
  - fs/verity/verify.c:fsverity_verify_bio
  - fs/verity/verify.c:fsverity_verify_page
```
**Symbols:**

```
ffffffff81347210-ffffffff813477e1: verify_page (STB_LOCAL)
ffffffff81347a45-ffffffff81347b2c: verify_page.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
bool verify_page(struct inode *inode, const struct fsverity_info *vi, struct ahash_request *req, struct page *data_page);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/verity/verify.c (0)
Location: fs/verity/verify.c:86
Inline: False
Direct callers:
  - fs/verity/verify.c:fsverity_verify_bio
  - fs/verity/verify.c:fsverity_verify_page
```
**Symbols:**

```
ffffffff8135a510-ffffffff8135aae1: verify_page (STB_LOCAL)
ffffffff8135ad45-ffffffff8135ae2c: verify_page.cold (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
<details>
<summary>Changed between <code>5.4</code> and <code>5.8</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>long unsigned int level0_ra_pages</code>
</li>
</ul>
</details>
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
