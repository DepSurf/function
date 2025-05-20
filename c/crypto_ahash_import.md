# Function: <code>crypto_ahash_import</code>

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
<summary>In <code>5.4</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/verity/hash_algs.c (ffffffff813503f5)
Location: include/crypto/hash.h:484
Inline: True
Inline callers:
  - fs/verity/hash_algs.c:fsverity_hash_page
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
In fs/verity/hash_algs.c (ffffffff81396d95)
Location: include/crypto/hash.h:497
Inline: True
Inline callers:
  - fs/verity/hash_algs.c:fsverity_hash_page
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
In fs/verity/hash_algs.c (ffffffff813a89c5)
Location: include/crypto/hash.h:505
Inline: True
Inline callers:
  - fs/verity/hash_algs.c:fsverity_hash_page
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
In fs/verity/hash_algs.c (ffffffff813afa35)
Location: include/crypto/hash.h:507
Inline: True
Inline callers:
  - fs/verity/hash_algs.c:fsverity_hash_page
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
In fs/verity/hash_algs.c (ffffffff813ff625)
Location: include/crypto/hash.h:507
Inline: True
Inline callers:
  - fs/verity/hash_algs.c:fsverity_hash_page
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
In fs/verity/hash_algs.c (ffffffff8147322d)
Location: include/crypto/hash.h:507
Inline: True
Inline callers:
  - fs/verity/hash_algs.c:fsverity_hash_page
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
In fs/verity/hash_algs.c (ffffffff8150507f)
Location: include/crypto/hash.h:507
Inline: True
Inline callers:
  - fs/verity/hash_algs.c:fsverity_hash_page
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
In crypto/ahash.c (ffffffff81744ef9)
Location: include/crypto/hash.h:538
Inline: True
Inline callers:
  - crypto/ahash.c:ahash_save_req
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
int crypto_ahash_import(struct ahash_request *req, const void *in);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In crypto/ahash.c (0)
Location: crypto/ahash.c:494
Inline: False
```
**Symbols:**

```
ffffffff821d2564-ffffffff821d2579: crypto_ahash_import.cold (STB_LOCAL)
ffffffff81786e90-ffffffff81786f07: crypto_ahash_import (STB_GLOBAL)
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
In fs/verity/hash_algs.c (ffff800010412054)
Location: include/crypto/hash.h:484
Inline: True
Inline callers:
  - fs/verity/hash_algs.c:fsverity_hash_page
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
In fs/verity/hash_algs.c (c05de6b4)
Location: include/crypto/hash.h:484
Inline: True
Inline callers:
  - fs/verity/hash_algs.c:fsverity_hash_page
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
In fs/verity/hash_algs.c (c00000000051fd44)
Location: include/crypto/hash.h:484
Inline: True
Inline callers:
  - fs/verity/hash_algs.c:fsverity_hash_page
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
In fs/verity/hash_algs.c (ffffffe0002ba108)
Location: include/crypto/hash.h:484
Inline: True
Inline callers:
  - fs/verity/hash_algs.c:fsverity_hash_page
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
In fs/verity/hash_algs.c (ffffffff813489d5)
Location: include/crypto/hash.h:484
Inline: True
Inline callers:
  - fs/verity/hash_algs.c:fsverity_hash_page
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
In fs/verity/hash_algs.c (ffffffff813396b5)
Location: include/crypto/hash.h:484
Inline: True
Inline callers:
  - fs/verity/hash_algs.c:fsverity_hash_page
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
In fs/verity/hash_algs.c (ffffffff813464a5)
Location: include/crypto/hash.h:484
Inline: True
Inline callers:
  - fs/verity/hash_algs.c:fsverity_hash_page
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
In fs/verity/hash_algs.c (ffffffff81359785)
Location: include/crypto/hash.h:484
Inline: True
Inline callers:
  - fs/verity/hash_algs.c:fsverity_hash_page
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
</ul>
