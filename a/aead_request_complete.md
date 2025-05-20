# Function: <code>aead_request_complete</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>4.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In crypto/seqiv.c (ffffffff813deb0b)
Location: include/crypto/internal/aead.h:73
Inline: True
Inline callers:
  - crypto/seqiv.c:seqiv_aead_encrypt_complete
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In crypto/seqiv.c (ffffffff813f70ab)
Location: include/crypto/internal/aead.h:73
Inline: True
Inline callers:
  - crypto/seqiv.c:seqiv_aead_encrypt_complete
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In crypto/seqiv.c (ffffffff81403250)
Location: include/crypto/internal/aead.h:73
Inline: True
Inline callers:
  - crypto/seqiv.c:seqiv_aead_encrypt_complete
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In crypto/seqiv.c (ffffffff8142b930)
Location: include/crypto/internal/aead.h:73
Inline: True
Inline callers:
  - crypto/seqiv.c:seqiv_aead_encrypt_complete
```
```
In crypto/gcm.c (ffffffff8143937c)
Location: include/crypto/internal/aead.h:73
Inline: True
Inline callers:
  - crypto/gcm.c:gcm_decrypt_done
  - crypto/gcm.c:gcm_encrypt_done
  - crypto/gcm.c:gcm_hash_init_done
  - crypto/gcm.c:gcm_hash_assoc_done
  - crypto/gcm.c:gcm_hash_assoc_remain_done
  - crypto/gcm.c:gcm_hash_crypt_done
  - crypto/gcm.c:gcm_hash_crypt_remain_done
  - crypto/gcm.c:gcm_hash_len_done
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In crypto/seqiv.c (ffffffff8145e64b)
Location: include/crypto/internal/aead.h:73
Inline: True
Inline callers:
  - crypto/seqiv.c:seqiv_aead_encrypt_complete
```
```
In crypto/gcm.c (ffffffff8146bd12)
Location: include/crypto/internal/aead.h:73
Inline: True
Inline callers:
  - crypto/gcm.c:gcm_decrypt_done
  - crypto/gcm.c:gcm_encrypt_done
  - crypto/gcm.c:gcm_hash_init_done
  - crypto/gcm.c:gcm_hash_assoc_done
  - crypto/gcm.c:gcm_hash_assoc_remain_done
  - crypto/gcm.c:gcm_hash_crypt_done
  - crypto/gcm.c:gcm_hash_crypt_remain_done
  - crypto/gcm.c:gcm_hash_len_done
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In crypto/seqiv.c (ffffffff8147bf3b)
Location: include/crypto/internal/aead.h:73
Inline: True
Inline callers:
  - crypto/seqiv.c:seqiv_aead_encrypt_complete
```
```
In crypto/gcm.c (ffffffff814892c2)
Location: include/crypto/internal/aead.h:73
Inline: True
Inline callers:
  - crypto/gcm.c:gcm_decrypt_done
  - crypto/gcm.c:gcm_encrypt_done
  - crypto/gcm.c:gcm_hash_init_done
  - crypto/gcm.c:gcm_hash_assoc_done
  - crypto/gcm.c:gcm_hash_assoc_remain_done
  - crypto/gcm.c:gcm_hash_crypt_done
  - crypto/gcm.c:gcm_hash_crypt_remain_done
  - crypto/gcm.c:gcm_hash_len_done
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In crypto/seqiv.c (ffffffff814aa2dc)
Location: include/crypto/internal/aead.h:68
Inline: True
Inline callers:
  - crypto/seqiv.c:seqiv_aead_encrypt_complete
```
```
In crypto/gcm.c (ffffffff814b6f03)
Location: include/crypto/internal/aead.h:68
Inline: True
Inline callers:
  - crypto/gcm.c:gcm_decrypt_done
  - crypto/gcm.c:gcm_encrypt_done
  - crypto/gcm.c:gcm_hash_init_done
  - crypto/gcm.c:gcm_hash_assoc_done
  - crypto/gcm.c:gcm_hash_assoc_remain_done
  - crypto/gcm.c:gcm_hash_crypt_done
  - crypto/gcm.c:gcm_hash_crypt_remain_done
  - crypto/gcm.c:gcm_hash_len_done
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In crypto/seqiv.c (ffffffff814c4f9c)
Location: include/crypto/internal/aead.h:68
Inline: True
Inline callers:
  - crypto/seqiv.c:seqiv_aead_encrypt_complete
```
```
In crypto/gcm.c (ffffffff814d0123)
Location: include/crypto/internal/aead.h:68
Inline: True
Inline callers:
  - crypto/gcm.c:gcm_decrypt_done
  - crypto/gcm.c:gcm_encrypt_done
  - crypto/gcm.c:gcm_hash_init_done
  - crypto/gcm.c:gcm_hash_assoc_done
  - crypto/gcm.c:gcm_hash_assoc_remain_done
  - crypto/gcm.c:gcm_hash_crypt_done
  - crypto/gcm.c:gcm_hash_crypt_remain_done
  - crypto/gcm.c:gcm_hash_len_done
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In crypto/seqiv.c (ffffffff81523eac)
Location: include/crypto/internal/aead.h:68
Inline: True
Inline callers:
  - crypto/seqiv.c:seqiv_aead_encrypt_complete
```
```
In crypto/gcm.c (ffffffff8152f253)
Location: include/crypto/internal/aead.h:68
Inline: True
Inline callers:
  - crypto/gcm.c:gcm_decrypt_done
  - crypto/gcm.c:gcm_encrypt_done
  - crypto/gcm.c:gcm_hash_init_done
  - crypto/gcm.c:gcm_hash_assoc_done
  - crypto/gcm.c:gcm_hash_assoc_remain_done
  - crypto/gcm.c:gcm_hash_crypt_done
  - crypto/gcm.c:gcm_hash_crypt_remain_done
  - crypto/gcm.c:gcm_hash_len_done
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In crypto/seqiv.c (ffffffff81540dbc)
Location: include/crypto/internal/aead.h:68
Inline: True
Inline callers:
  - crypto/seqiv.c:seqiv_aead_encrypt_complete
```
```
In crypto/gcm.c (ffffffff8154c1d3)
Location: include/crypto/internal/aead.h:68
Inline: True
Inline callers:
  - crypto/gcm.c:gcm_decrypt_done
  - crypto/gcm.c:gcm_encrypt_done
  - crypto/gcm.c:gcm_hash_init_done
  - crypto/gcm.c:gcm_hash_assoc_done
  - crypto/gcm.c:gcm_hash_assoc_remain_done
  - crypto/gcm.c:gcm_hash_crypt_done
  - crypto/gcm.c:gcm_hash_crypt_remain_done
  - crypto/gcm.c:gcm_hash_len_done
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In crypto/seqiv.c (ffffffff8154941c)
Location: include/crypto/internal/aead.h:68
Inline: True
Inline callers:
  - crypto/seqiv.c:seqiv_aead_encrypt_complete
```
```
In crypto/gcm.c (ffffffff815547c3)
Location: include/crypto/internal/aead.h:68
Inline: True
Inline callers:
  - crypto/gcm.c:gcm_decrypt_done
  - crypto/gcm.c:gcm_encrypt_done
  - crypto/gcm.c:gcm_hash_init_done
  - crypto/gcm.c:gcm_hash_assoc_done
  - crypto/gcm.c:gcm_hash_assoc_remain_done
  - crypto/gcm.c:gcm_hash_crypt_done
  - crypto/gcm.c:gcm_hash_crypt_remain_done
  - crypto/gcm.c:gcm_hash_len_done
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In crypto/seqiv.c (ffffffff815a9bfc)
Location: include/crypto/internal/aead.h:68
Inline: True
Inline callers:
  - crypto/seqiv.c:seqiv_aead_encrypt_complete
```
```
In crypto/gcm.c (ffffffff815b57f3)
Location: include/crypto/internal/aead.h:68
Inline: True
Inline callers:
  - crypto/gcm.c:gcm_decrypt_done
  - crypto/gcm.c:gcm_encrypt_done
  - crypto/gcm.c:gcm_hash_init_done
  - crypto/gcm.c:gcm_hash_assoc_done
  - crypto/gcm.c:gcm_hash_assoc_remain_done
  - crypto/gcm.c:gcm_hash_crypt_done
  - crypto/gcm.c:gcm_hash_crypt_remain_done
  - crypto/gcm.c:gcm_hash_len_done
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In crypto/seqiv.c (ffffffff816510ea)
Location: include/crypto/internal/aead.h:68
Inline: True
Inline callers:
  - crypto/seqiv.c:seqiv_aead_encrypt_complete
```
```
In crypto/gcm.c (ffffffff8165e9b2)
Location: include/crypto/internal/aead.h:68
Inline: True
Inline callers:
  - crypto/gcm.c:gcm_decrypt_done
  - crypto/gcm.c:gcm_encrypt_done
  - crypto/gcm.c:gcm_hash_init_done
  - crypto/gcm.c:gcm_hash_assoc_done
  - crypto/gcm.c:gcm_hash_assoc_remain_done
  - crypto/gcm.c:gcm_hash_crypt_done
  - crypto/gcm.c:gcm_hash_crypt_remain_done
  - crypto/gcm.c:gcm_hash_len_done
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In crypto/seqiv.c (ffffffff8170a95a)
Location: include/crypto/internal/aead.h:83
Inline: True
Inline callers:
  - crypto/seqiv.c:seqiv_aead_encrypt_complete
```
```
In crypto/gcm.c (ffffffff81718752)
Location: include/crypto/internal/aead.h:83
Inline: True
Inline callers:
  - crypto/gcm.c:gcm_decrypt_done
  - crypto/gcm.c:gcm_encrypt_done
  - crypto/gcm.c:gcm_hash_init_done
  - crypto/gcm.c:gcm_hash_assoc_done
  - crypto/gcm.c:gcm_hash_assoc_remain_done
  - crypto/gcm.c:gcm_hash_crypt_done
  - crypto/gcm.c:gcm_hash_crypt_remain_done
  - crypto/gcm.c:gcm_hash_len_done
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In crypto/seqiv.c (ffffffff817441a7)
Location: include/crypto/internal/aead.h:83
Inline: True
Inline callers:
  - crypto/seqiv.c:seqiv_aead_encrypt_complete
```
```
In crypto/gcm.c (ffffffff817540c1)
Location: include/crypto/internal/aead.h:83
Inline: True
Inline callers:
  - crypto/gcm.c:gcm_decrypt_done
  - crypto/gcm.c:gcm_encrypt_done
  - crypto/gcm.c:gcm_hash_init_done
  - crypto/gcm.c:gcm_hash_assoc_done
  - crypto/gcm.c:gcm_hash_assoc_remain_done
  - crypto/gcm.c:gcm_hash_crypt_done
  - crypto/gcm.c:gcm_hash_crypt_remain_done
  - crypto/gcm.c:gcm_hash_len_done
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In crypto/seqiv.c (ffffffff81786767)
Location: include/crypto/internal/aead.h:83
Inline: True
Inline callers:
  - crypto/seqiv.c:seqiv_aead_encrypt_complete
```
```
In crypto/gcm.c (ffffffff81795a31)
Location: include/crypto/internal/aead.h:83
Inline: True
Inline callers:
  - crypto/gcm.c:gcm_decrypt_done
  - crypto/gcm.c:gcm_encrypt_done
  - crypto/gcm.c:gcm_hash_init_done
  - crypto/gcm.c:gcm_hash_assoc_done
  - crypto/gcm.c:gcm_hash_assoc_remain_done
  - crypto/gcm.c:gcm_hash_crypt_done
  - crypto/gcm.c:gcm_hash_crypt_remain_done
  - crypto/gcm.c:gcm_hash_len_done
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In crypto/seqiv.c (ffff8000105bfb5c)
Location: include/crypto/internal/aead.h:68
Inline: True
Inline callers:
  - crypto/seqiv.c:seqiv_aead_encrypt_complete
```
```
In crypto/gcm.c (ffff8000105cc5e4)
Location: include/crypto/internal/aead.h:68
Inline: True
Inline callers:
  - crypto/gcm.c:gcm_decrypt_done
  - crypto/gcm.c:gcm_encrypt_done
  - crypto/gcm.c:gcm_hash_init_done
  - crypto/gcm.c:gcm_hash_assoc_done
  - crypto/gcm.c:gcm_hash_assoc_remain_done
  - crypto/gcm.c:gcm_hash_crypt_done
  - crypto/gcm.c:gcm_hash_crypt_remain_done
  - crypto/gcm.c:gcm_hash_len_done
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In crypto/seqiv.c (c076d7a4)
Location: include/crypto/internal/aead.h:68
Inline: True
Inline callers:
  - crypto/seqiv.c:seqiv_aead_encrypt_complete
```
```
In crypto/gcm.c (c077a4f8)
Location: include/crypto/internal/aead.h:68
Inline: True
Inline callers:
  - crypto/gcm.c:gcm_decrypt_done
  - crypto/gcm.c:gcm_encrypt_done
  - crypto/gcm.c:gcm_hash_init_done
  - crypto/gcm.c:gcm_hash_assoc_done
  - crypto/gcm.c:gcm_hash_assoc_remain_done
  - crypto/gcm.c:gcm_hash_crypt_done
  - crypto/gcm.c:gcm_hash_crypt_remain_done
  - crypto/gcm.c:gcm_hash_len_done
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In crypto/seqiv.c (c000000000747984)
Location: include/crypto/internal/aead.h:68
Inline: True
Inline callers:
  - crypto/seqiv.c:seqiv_aead_encrypt_complete
```
```
In crypto/gcm.c (c0000000007579d0)
Location: include/crypto/internal/aead.h:68
Inline: True
Inline callers:
  - crypto/gcm.c:gcm_decrypt_done
  - crypto/gcm.c:gcm_encrypt_done
  - crypto/gcm.c:gcm_hash_init_done
  - crypto/gcm.c:gcm_hash_assoc_done
  - crypto/gcm.c:gcm_hash_assoc_remain_done
  - crypto/gcm.c:gcm_hash_crypt_done
  - crypto/gcm.c:gcm_hash_crypt_remain_done
  - crypto/gcm.c:gcm_hash_len_done
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In crypto/seqiv.c (ffffffe000404d9a)
Location: include/crypto/internal/aead.h:68
Inline: True
Inline callers:
  - crypto/seqiv.c:seqiv_aead_encrypt_complete
```
```
In crypto/gcm.c (ffffffe000410318)
Location: include/crypto/internal/aead.h:68
Inline: True
Inline callers:
  - crypto/gcm.c:gcm_decrypt_done
  - crypto/gcm.c:gcm_encrypt_done
  - crypto/gcm.c:gcm_hash_init_done
  - crypto/gcm.c:gcm_hash_assoc_done
  - crypto/gcm.c:gcm_hash_assoc_remain_done
  - crypto/gcm.c:gcm_hash_crypt_done
  - crypto/gcm.c:gcm_hash_crypt_remain_done
  - crypto/gcm.c:gcm_hash_len_done
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In crypto/seqiv.c (ffffffff814bd57c)
Location: include/crypto/internal/aead.h:68
Inline: True
Inline callers:
  - crypto/seqiv.c:seqiv_aead_encrypt_complete
```
```
In crypto/gcm.c (ffffffff814c8703)
Location: include/crypto/internal/aead.h:68
Inline: True
Inline callers:
  - crypto/gcm.c:gcm_decrypt_done
  - crypto/gcm.c:gcm_encrypt_done
  - crypto/gcm.c:gcm_hash_init_done
  - crypto/gcm.c:gcm_hash_assoc_done
  - crypto/gcm.c:gcm_hash_assoc_remain_done
  - crypto/gcm.c:gcm_hash_crypt_done
  - crypto/gcm.c:gcm_hash_crypt_remain_done
  - crypto/gcm.c:gcm_hash_len_done
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In crypto/seqiv.c (ffffffff814adf9c)
Location: include/crypto/internal/aead.h:68
Inline: True
Inline callers:
  - crypto/seqiv.c:seqiv_aead_encrypt_complete
```
```
In crypto/gcm.c (ffffffff814b9123)
Location: include/crypto/internal/aead.h:68
Inline: True
Inline callers:
  - crypto/gcm.c:gcm_decrypt_done
  - crypto/gcm.c:gcm_encrypt_done
  - crypto/gcm.c:gcm_hash_init_done
  - crypto/gcm.c:gcm_hash_assoc_done
  - crypto/gcm.c:gcm_hash_assoc_remain_done
  - crypto/gcm.c:gcm_hash_crypt_done
  - crypto/gcm.c:gcm_hash_crypt_remain_done
  - crypto/gcm.c:gcm_hash_len_done
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In crypto/seqiv.c (ffffffff814b960c)
Location: include/crypto/internal/aead.h:68
Inline: True
Inline callers:
  - crypto/seqiv.c:seqiv_aead_encrypt_complete
```
```
In crypto/gcm.c (ffffffff814c4793)
Location: include/crypto/internal/aead.h:68
Inline: True
Inline callers:
  - crypto/gcm.c:gcm_decrypt_done
  - crypto/gcm.c:gcm_encrypt_done
  - crypto/gcm.c:gcm_hash_init_done
  - crypto/gcm.c:gcm_hash_assoc_done
  - crypto/gcm.c:gcm_hash_assoc_remain_done
  - crypto/gcm.c:gcm_hash_crypt_done
  - crypto/gcm.c:gcm_hash_crypt_remain_done
  - crypto/gcm.c:gcm_hash_len_done
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In crypto/seqiv.c (ffffffff814d20ac)
Location: include/crypto/internal/aead.h:68
Inline: True
Inline callers:
  - crypto/seqiv.c:seqiv_aead_encrypt_complete
```
```
In crypto/gcm.c (ffffffff814dd263)
Location: include/crypto/internal/aead.h:68
Inline: True
Inline callers:
  - crypto/gcm.c:gcm_decrypt_done
  - crypto/gcm.c:gcm_encrypt_done
  - crypto/gcm.c:gcm_hash_init_done
  - crypto/gcm.c:gcm_hash_assoc_done
  - crypto/gcm.c:gcm_hash_assoc_remain_done
  - crypto/gcm.c:gcm_hash_crypt_done
  - crypto/gcm.c:gcm_hash_crypt_remain_done
  - crypto/gcm.c:gcm_hash_len_done
```
</details>
</li>
</ul>

## Differences
