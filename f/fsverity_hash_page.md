# Function: <code>fsverity_hash_page</code>

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
int fsverity_hash_page(const struct merkle_tree_params *params, const struct inode *inode, struct ahash_request *req, struct page *page, u8 *out);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/verity/hash_algs.c (0)
Location: fs/verity/hash_algs.c:184
Inline: False
Direct callers:
  - fs/verity/enable.c:build_merkle_tree
  - fs/verity/verify.c:verify_page
  - fs/verity/verify.c:verify_page
```
**Symbols:**

```
ffffffff81350670-ffffffff813506bb: fsverity_hash_page.cold (STB_LOCAL)
ffffffff81350320-ffffffff8135047f: fsverity_hash_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
int fsverity_hash_page(const struct merkle_tree_params *params, const struct inode *inode, struct ahash_request *req, struct page *page, u8 *out);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/verity/hash_algs.c (0)
Location: fs/verity/hash_algs.c:233
Inline: False
Direct callers:
  - fs/verity/enable.c:build_merkle_tree_level
  - fs/verity/verify.c:verify_page
  - fs/verity/verify.c:verify_page
```
**Symbols:**

```
ffffffff8139707b-ffffffff8139709e: fsverity_hash_page.cold (STB_LOCAL)
ffffffff81396cc0-ffffffff81396e3b: fsverity_hash_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
int fsverity_hash_page(const struct merkle_tree_params *params, const struct inode *inode, struct ahash_request *req, struct page *page, u8 *out);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/verity/hash_algs.c (0)
Location: fs/verity/hash_algs.c:233
Inline: False
Direct callers:
  - fs/verity/enable.c:build_merkle_tree_level
  - fs/verity/verify.c:verify_page
  - fs/verity/verify.c:verify_page
```
**Symbols:**

```
ffffffff81beb4a4-ffffffff81beb4c7: fsverity_hash_page.cold (STB_LOCAL)
ffffffff813a88f0-ffffffff813a8a6b: fsverity_hash_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
int fsverity_hash_page(const struct merkle_tree_params *params, const struct inode *inode, struct ahash_request *req, struct page *page, u8 *out);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/verity/hash_algs.c (0)
Location: fs/verity/hash_algs.c:233
Inline: False
Direct callers:
  - fs/verity/enable.c:build_merkle_tree_level
  - fs/verity/verify.c:verify_page
  - fs/verity/verify.c:verify_page
```
**Symbols:**

```
ffffffff81bdd4f8-ffffffff81bdd51b: fsverity_hash_page.cold (STB_LOCAL)
ffffffff813af960-ffffffff813afadb: fsverity_hash_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int fsverity_hash_page(const struct merkle_tree_params *params, const struct inode *inode, struct ahash_request *req, struct page *page, u8 *out);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/verity/hash_algs.c (0)
Location: fs/verity/hash_algs.c:233
Inline: False
Direct callers:
  - fs/verity/enable.c:build_merkle_tree_level
  - fs/verity/verify.c:verify_page
  - fs/verity/verify.c:verify_page
```
**Symbols:**

```
ffffffff81cc6dfe-ffffffff81cc6e21: fsverity_hash_page.cold (STB_LOCAL)
ffffffff813ff550-ffffffff813ff6cb: fsverity_hash_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int fsverity_hash_page(const struct merkle_tree_params *params, const struct inode *inode, struct ahash_request *req, struct page *page, u8 *out);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/verity/hash_algs.c (0)
Location: fs/verity/hash_algs.c:233
Inline: False
Direct callers:
  - fs/verity/enable.c:build_merkle_tree_level
  - fs/verity/verify.c:verify_page
  - fs/verity/verify.c:verify_page
```
**Symbols:**

```
ffffffff81e7933a-ffffffff81e7935d: fsverity_hash_page.cold (STB_LOCAL)
ffffffff81473130-ffffffff814732e5: fsverity_hash_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int fsverity_hash_page(const struct merkle_tree_params *params, const struct inode *inode, struct ahash_request *req, struct page *page, u8 *out);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/verity/hash_algs.c (ffffffff81504f80)
Location: fs/verity/hash_algs.c:235
Inline: False
Direct callers:
  - fs/verity/enable.c:build_merkle_tree_level
  - fs/verity/verify.c:verify_page
  - fs/verity/verify.c:verify_page
```
**Symbols:**

```
ffffffff81504f80-ffffffff81505170: fsverity_hash_page (STB_GLOBAL)
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
int fsverity_hash_page(const struct merkle_tree_params *params, const struct inode *inode, struct ahash_request *req, struct page *page, u8 *out);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/verity/hash_algs.c (ffff800010411f88)
Location: fs/verity/hash_algs.c:184
Inline: False
Direct callers:
  - fs/verity/enable.c:build_merkle_tree
  - fs/verity/verify.c:verify_page
  - fs/verity/verify.c:verify_page
```
**Symbols:**

```
ffff800010411f88-ffff800010412140: fsverity_hash_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int fsverity_hash_page(const struct merkle_tree_params *params, const struct inode *inode, struct ahash_request *req, struct page *page, u8 *out);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/verity/hash_algs.c (c05de5e0)
Location: fs/verity/hash_algs.c:184
Inline: False
Direct callers:
  - fs/verity/enable.c:build_merkle_tree
  - fs/verity/verify.c:verify_page
  - fs/verity/verify.c:verify_page
```
**Symbols:**

```
c05de5e0-c05de7b4: fsverity_hash_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int fsverity_hash_page(const struct merkle_tree_params *params, const struct inode *inode, struct ahash_request *req, struct page *page, u8 *out);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/verity/hash_algs.c (c00000000051fc30)
Location: fs/verity/hash_algs.c:184
Inline: False
Direct callers:
  - fs/verity/enable.c:build_merkle_tree
  - fs/verity/verify.c:verify_page
  - fs/verity/verify.c:verify_page
```
**Symbols:**

```
c00000000051fc30-c00000000051fe7c: fsverity_hash_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int fsverity_hash_page(const struct merkle_tree_params *params, const struct inode *inode, struct ahash_request *req, struct page *page, u8 *out);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/verity/hash_algs.c (ffffffe0002ba05e)
Location: fs/verity/hash_algs.c:184
Inline: False
Direct callers:
  - fs/verity/enable.c:build_merkle_tree
  - fs/verity/verify.c:verify_page
  - fs/verity/verify.c:verify_page
```
**Symbols:**

```
ffffffe0002ba05e-ffffffe0002ba1bc: fsverity_hash_page (STB_GLOBAL)
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
int fsverity_hash_page(const struct merkle_tree_params *params, const struct inode *inode, struct ahash_request *req, struct page *page, u8 *out);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/verity/hash_algs.c (0)
Location: fs/verity/hash_algs.c:184
Inline: False
Direct callers:
  - fs/verity/enable.c:build_merkle_tree
  - fs/verity/verify.c:verify_page
  - fs/verity/verify.c:verify_page
```
**Symbols:**

```
ffffffff81348c50-ffffffff81348c9b: fsverity_hash_page.cold (STB_LOCAL)
ffffffff81348900-ffffffff81348a5f: fsverity_hash_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Transformation ⚠️</summary>

```c
int fsverity_hash_page(const struct merkle_tree_params *params, const struct inode *inode, struct ahash_request *req, struct page *page, u8 *out);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/verity/hash_algs.c (0)
Location: fs/verity/hash_algs.c:184
Inline: False
Direct callers:
  - fs/verity/enable.c:build_merkle_tree
  - fs/verity/verify.c:verify_page
  - fs/verity/verify.c:verify_page
```
**Symbols:**

```
ffffffff81339930-ffffffff8133997b: fsverity_hash_page.cold (STB_LOCAL)
ffffffff813395e0-ffffffff8133973f: fsverity_hash_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Transformation ⚠️</summary>

```c
int fsverity_hash_page(const struct merkle_tree_params *params, const struct inode *inode, struct ahash_request *req, struct page *page, u8 *out);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/verity/hash_algs.c (0)
Location: fs/verity/hash_algs.c:184
Inline: False
Direct callers:
  - fs/verity/enable.c:build_merkle_tree
  - fs/verity/verify.c:verify_page
  - fs/verity/verify.c:verify_page
```
**Symbols:**

```
ffffffff81346720-ffffffff8134676b: fsverity_hash_page.cold (STB_LOCAL)
ffffffff813463d0-ffffffff8134652f: fsverity_hash_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
int fsverity_hash_page(const struct merkle_tree_params *params, const struct inode *inode, struct ahash_request *req, struct page *page, u8 *out);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/verity/hash_algs.c (0)
Location: fs/verity/hash_algs.c:184
Inline: False
Direct callers:
  - fs/verity/enable.c:build_merkle_tree
  - fs/verity/verify.c:verify_page
  - fs/verity/verify.c:verify_page
```
**Symbols:**

```
ffffffff81359a00-ffffffff81359a4b: fsverity_hash_page.cold (STB_LOCAL)
ffffffff813596b0-ffffffff8135980f: fsverity_hash_page (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
