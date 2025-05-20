# Function: <code>fsverity_alloc_hash_request</code>

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
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
struct ahash_request *fsverity_alloc_hash_request(struct fsverity_hash_alg *alg, gfp_t gfp_flags);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/verity/hash_algs.c (ffffffff81396ea4)
Location: fs/verity/hash_algs.c:123
Inline: True
Inline callers:
  - fs/verity/hash_algs.c:fsverity_hash_buffer
  - fs/verity/hash_algs.c:fsverity_prepare_hash_state
Direct callers:
  - fs/verity/enable.c:build_merkle_tree
  - fs/verity/verify.c:fsverity_verify_bio
  - fs/verity/verify.c:fsverity_verify_page
```
**Symbols:**

```
ffffffff813969f0-ffffffff81396a1c: fsverity_alloc_hash_request (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
struct ahash_request *fsverity_alloc_hash_request(struct fsverity_hash_alg *alg, gfp_t gfp_flags);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/verity/hash_algs.c (ffffffff813a8ad4)
Location: fs/verity/hash_algs.c:123
Inline: True
Inline callers:
  - fs/verity/hash_algs.c:fsverity_hash_buffer
  - fs/verity/hash_algs.c:fsverity_prepare_hash_state
Direct callers:
  - fs/verity/enable.c:build_merkle_tree
  - fs/verity/verify.c:fsverity_verify_bio
  - fs/verity/verify.c:fsverity_verify_page
```
**Symbols:**

```
ffffffff813a8620-ffffffff813a864c: fsverity_alloc_hash_request (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
struct ahash_request *fsverity_alloc_hash_request(struct fsverity_hash_alg *alg, gfp_t gfp_flags);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/verity/hash_algs.c (ffffffff813afb44)
Location: fs/verity/hash_algs.c:123
Inline: True
Inline callers:
  - fs/verity/hash_algs.c:fsverity_hash_buffer
  - fs/verity/hash_algs.c:fsverity_prepare_hash_state
Direct callers:
  - fs/verity/enable.c:build_merkle_tree
  - fs/verity/verify.c:fsverity_verify_bio
  - fs/verity/verify.c:fsverity_verify_page
```
**Symbols:**

```
ffffffff813af670-ffffffff813af69c: fsverity_alloc_hash_request (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
struct ahash_request *fsverity_alloc_hash_request(struct fsverity_hash_alg *alg, gfp_t gfp_flags);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/verity/hash_algs.c (ffffffff813ff734)
Location: fs/verity/hash_algs.c:123
Inline: True
Inline callers:
  - fs/verity/hash_algs.c:fsverity_hash_buffer
  - fs/verity/hash_algs.c:fsverity_prepare_hash_state
Direct callers:
  - fs/verity/enable.c:build_merkle_tree
  - fs/verity/verify.c:fsverity_verify_bio
  - fs/verity/verify.c:fsverity_verify_page
```
**Symbols:**

```
ffffffff813ff260-ffffffff813ff28c: fsverity_alloc_hash_request (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
struct ahash_request *fsverity_alloc_hash_request(struct fsverity_hash_alg *alg, gfp_t gfp_flags);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/verity/hash_algs.c (ffffffff8147338b)
Location: fs/verity/hash_algs.c:123
Inline: True
Inline callers:
  - fs/verity/hash_algs.c:fsverity_hash_buffer
  - fs/verity/hash_algs.c:fsverity_prepare_hash_state
Direct callers:
  - fs/verity/enable.c:build_merkle_tree
  - fs/verity/verify.c:fsverity_verify_bio
  - fs/verity/verify.c:fsverity_verify_page
```
**Symbols:**

```
ffffffff81472dd0-ffffffff81472e06: fsverity_alloc_hash_request (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
struct ahash_request *fsverity_alloc_hash_request(struct fsverity_hash_alg *alg, gfp_t gfp_flags);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/verity/hash_algs.c (ffffffff8150521b)
Location: fs/verity/hash_algs.c:125
Inline: True
Inline callers:
  - fs/verity/hash_algs.c:fsverity_hash_buffer
  - fs/verity/hash_algs.c:fsverity_prepare_hash_state
Direct callers:
  - fs/verity/enable.c:build_merkle_tree
  - fs/verity/verify.c:fsverity_verify_bio
  - fs/verity/verify.c:fsverity_verify_page
```
**Symbols:**

```
ffffffff81504bf0-ffffffff81504c26: fsverity_alloc_hash_request (STB_GLOBAL)
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
</ul>
