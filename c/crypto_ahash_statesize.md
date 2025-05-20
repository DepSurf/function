# Function: <code>crypto_ahash_statesize</code>

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
In fs/verity/hash_algs.c (ffffffff8135012d)
Location: include/crypto/hash.h:348
Inline: True
Inline callers:
  - fs/verity/hash_algs.c:fsverity_prepare_hash_state
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
In fs/verity/hash_algs.c (ffffffff81396aa0)
Location: include/crypto/hash.h:361
Inline: True
Inline callers:
  - fs/verity/hash_algs.c:fsverity_prepare_hash_state
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
In fs/verity/hash_algs.c (ffffffff813a86d0)
Location: include/crypto/hash.h:369
Inline: True
Inline callers:
  - fs/verity/hash_algs.c:fsverity_prepare_hash_state
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
In fs/verity/hash_algs.c (ffffffff813af740)
Location: include/crypto/hash.h:371
Inline: True
Inline callers:
  - fs/verity/hash_algs.c:fsverity_prepare_hash_state
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
In fs/verity/hash_algs.c (ffffffff813ff330)
Location: include/crypto/hash.h:371
Inline: True
Inline callers:
  - fs/verity/hash_algs.c:fsverity_prepare_hash_state
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
In fs/verity/hash_algs.c (ffffffff81472efc)
Location: include/crypto/hash.h:371
Inline: True
Inline callers:
  - fs/verity/hash_algs.c:fsverity_prepare_hash_state
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
In fs/verity/hash_algs.c (ffffffff81504d3c)
Location: include/crypto/hash.h:371
Inline: True
Inline callers:
  - fs/verity/hash_algs.c:fsverity_prepare_hash_state
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
In crypto/ahash.c (ffffffff81744ed1)
Location: include/crypto/hash.h:402
Inline: True
Inline callers:
  - crypto/ahash.c:ahash_save_req
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
In crypto/ahash.c (ffffffff817872e4)
Location: include/crypto/hash.h:383
Inline: True
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
In fs/verity/hash_algs.c (ffff800010411d98)
Location: include/crypto/hash.h:348
Inline: True
Inline callers:
  - fs/verity/hash_algs.c:fsverity_prepare_hash_state
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
In fs/verity/hash_algs.c (c05de3f4)
Location: include/crypto/hash.h:348
Inline: True
Inline callers:
  - fs/verity/hash_algs.c:fsverity_prepare_hash_state
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
In fs/verity/hash_algs.c (c00000000051f998)
Location: include/crypto/hash.h:348
Inline: True
Inline callers:
  - fs/verity/hash_algs.c:fsverity_prepare_hash_state
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
In fs/verity/hash_algs.c (ffffffe0002b9ec4)
Location: include/crypto/hash.h:348
Inline: True
Inline callers:
  - fs/verity/hash_algs.c:fsverity_prepare_hash_state
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
In fs/verity/hash_algs.c (ffffffff8134870d)
Location: include/crypto/hash.h:348
Inline: True
Inline callers:
  - fs/verity/hash_algs.c:fsverity_prepare_hash_state
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
In fs/verity/hash_algs.c (ffffffff813393ed)
Location: include/crypto/hash.h:348
Inline: True
Inline callers:
  - fs/verity/hash_algs.c:fsverity_prepare_hash_state
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
In fs/verity/hash_algs.c (ffffffff813461dd)
Location: include/crypto/hash.h:348
Inline: True
Inline callers:
  - fs/verity/hash_algs.c:fsverity_prepare_hash_state
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
In fs/verity/hash_algs.c (ffffffff813594bd)
Location: include/crypto/hash.h:348
Inline: True
Inline callers:
  - fs/verity/hash_algs.c:fsverity_prepare_hash_state
```
</details>
</li>
</ul>

## Differences
