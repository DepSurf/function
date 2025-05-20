# Function: <code>crypto_ahash_digestsize</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In security/integrity/ima/ima_crypto.c (ffffffff81397da2)
Location: include/crypto/hash.h:304
Inline: True
Inline callers:
  - security/integrity/ima/ima_crypto.c:ima_calc_file_hash_atfm
```
```
In crypto/ahash.c (ffffffff813a2c12)
Location: include/crypto/hash.h:304
Inline: True
Inline callers:
  - crypto/ahash.c:ahash_def_finup_finish2
  - crypto/ahash.c:ahash_save_req
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In security/integrity/ima/ima_crypto.c (ffffffff813d4918)
Location: include/crypto/hash.h:327
Inline: True
Inline callers:
  - security/integrity/ima/ima_crypto.c:ima_calc_buffer_hash
  - security/integrity/ima/ima_crypto.c:ima_calc_file_hash
```
```
In crypto/ahash.c (ffffffff813dedc2)
Location: include/crypto/hash.h:327
Inline: True
Inline callers:
  - crypto/ahash.c:ahash_def_finup_finish2
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In security/integrity/ima/ima_crypto.c (ffffffff813ec368)
Location: include/crypto/hash.h:327
Inline: True
Inline callers:
  - security/integrity/ima/ima_crypto.c:ima_calc_buffer_hash
  - security/integrity/ima/ima_crypto.c:ima_calc_file_hash
```
```
In crypto/ahash.c (ffffffff813f7352)
Location: include/crypto/hash.h:327
Inline: True
Inline callers:
  - crypto/ahash.c:ahash_def_finup_finish2
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In security/integrity/ima/ima_crypto.c (ffffffff813f8724)
Location: include/crypto/hash.h:327
Inline: True
Inline callers:
  - security/integrity/ima/ima_crypto.c:ima_calc_buffer_hash
  - security/integrity/ima/ima_crypto.c:ima_calc_file_hash
```
```
In crypto/ahash.c (ffffffff8140382c)
Location: include/crypto/hash.h:327
Inline: True
Inline callers:
  - crypto/ahash.c:ahash_restore_req
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
In security/integrity/ima/ima_crypto.c (ffffffff81420aa5)
Location: include/crypto/hash.h:331
Inline: True
Inline callers:
  - security/integrity/ima/ima_crypto.c:ima_calc_buffer_hash
  - security/integrity/ima/ima_crypto.c:ima_calc_file_hash
```
```
In crypto/ahash.c (ffffffff8142bf8c)
Location: include/crypto/hash.h:331
Inline: True
Inline callers:
  - crypto/ahash.c:ahash_restore_req
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
In security/integrity/ima/ima_crypto.c (ffffffff81452f33)
Location: include/crypto/hash.h:330
Inline: True
Inline callers:
  - security/integrity/ima/ima_crypto.c:ima_calc_buffer_hash
  - security/integrity/ima/ima_crypto.c:ima_calc_file_hash
```
```
In crypto/ahash.c (ffffffff8145ec7c)
Location: include/crypto/hash.h:330
Inline: True
Inline callers:
  - crypto/ahash.c:ahash_restore_req
  - crypto/ahash.c:ahash_save_req
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
In security/integrity/ima/ima_crypto.c (ffffffff81470092)
Location: include/crypto/hash.h:334
Inline: True
Inline callers:
  - security/integrity/ima/ima_crypto.c:ima_calc_buffer_hash
  - security/integrity/ima/ima_crypto.c:ima_calc_file_hash
```
```
In crypto/ahash.c (ffffffff8147c5ec)
Location: include/crypto/hash.h:334
Inline: True
Inline callers:
  - crypto/ahash.c:ahash_restore_req
  - crypto/ahash.c:ahash_save_req
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
In security/integrity/ima/ima_crypto.c (ffffffff8149da85)
Location: include/crypto/hash.h:333
Inline: True
Inline callers:
  - security/integrity/ima/ima_crypto.c:ima_calc_buffer_hash
  - security/integrity/ima/ima_crypto.c:ima_calc_file_hash_atfm
```
```
In crypto/ahash.c (ffffffff814aa75c)
Location: include/crypto/hash.h:333
Inline: True
Inline callers:
  - crypto/ahash.c:ahash_restore_req
  - crypto/ahash.c:ahash_save_req
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
In fs/verity/hash_algs.c (ffffffff8135009b)
Location: include/crypto/hash.h:333
Inline: True
Inline callers:
  - fs/verity/hash_algs.c:fsverity_get_hash_alg
```
```
In security/integrity/ima/ima_crypto.c (ffffffff814b7ec5)
Location: include/crypto/hash.h:333
Inline: True
Inline callers:
  - security/integrity/ima/ima_crypto.c:ima_calc_buffer_hash
  - security/integrity/ima/ima_crypto.c:ima_calc_file_hash_atfm
```
```
In crypto/ahash.c (ffffffff814c541c)
Location: include/crypto/hash.h:333
Inline: True
Inline callers:
  - crypto/ahash.c:ahash_restore_req
  - crypto/ahash.c:ahash_save_req
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
In fs/verity/hash_algs.c (ffffffff81396977)
Location: include/crypto/hash.h:346
Inline: True
Inline callers:
  - fs/verity/hash_algs.c:fsverity_get_hash_alg
```
```
In security/integrity/ima/ima_crypto.c (ffffffff81516ef8)
Location: include/crypto/hash.h:346
Inline: True
Inline callers:
  - security/integrity/ima/ima_crypto.c:calc_buffer_ahash_atfm
  - security/integrity/ima/ima_crypto.c:ima_calc_file_hash_atfm
```
```
In crypto/ahash.c (ffffffff8152450c)
Location: include/crypto/hash.h:346
Inline: True
Inline callers:
  - crypto/ahash.c:ahash_restore_req
  - crypto/ahash.c:ahash_save_req
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
In fs/verity/hash_algs.c (ffffffff813a85a7)
Location: include/crypto/hash.h:354
Inline: True
Inline callers:
  - fs/verity/hash_algs.c:fsverity_get_hash_alg
```
```
In security/integrity/ima/ima_crypto.c (ffffffff815340b8)
Location: include/crypto/hash.h:354
Inline: True
Inline callers:
  - security/integrity/ima/ima_crypto.c:calc_buffer_ahash_atfm
  - security/integrity/ima/ima_crypto.c:ima_calc_file_hash_atfm
```
```
In crypto/ahash.c (ffffffff815413d7)
Location: include/crypto/hash.h:354
Inline: True
Inline callers:
  - crypto/ahash.c:ahash_restore_req
  - crypto/ahash.c:ahash_save_req
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
In fs/verity/hash_algs.c (ffffffff813af5f7)
Location: include/crypto/hash.h:356
Inline: True
Inline callers:
  - fs/verity/hash_algs.c:fsverity_get_hash_alg
```
```
In security/integrity/ima/ima_crypto.c (ffffffff8153d0a4)
Location: include/crypto/hash.h:356
Inline: True
Inline callers:
  - security/integrity/ima/ima_crypto.c:ima_calc_buffer_hash
  - security/integrity/ima/ima_crypto.c:ima_calc_file_hash_atfm
```
```
In crypto/ahash.c (ffffffff81549a07)
Location: include/crypto/hash.h:356
Inline: True
Inline callers:
  - crypto/ahash.c:ahash_restore_req
  - crypto/ahash.c:ahash_save_req
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
In fs/verity/hash_algs.c (ffffffff813ff1c1)
Location: include/crypto/hash.h:356
Inline: True
Inline callers:
  - fs/verity/hash_algs.c:fsverity_get_hash_alg
```
```
In security/integrity/ima/ima_crypto.c (ffffffff8159bf24)
Location: include/crypto/hash.h:356
Inline: True
Inline callers:
  - security/integrity/ima/ima_crypto.c:ima_calc_buffer_hash
  - security/integrity/ima/ima_crypto.c:ima_calc_file_hash_atfm
```
```
In crypto/ahash.c (ffffffff815aa1e7)
Location: include/crypto/hash.h:356
Inline: True
Inline callers:
  - crypto/ahash.c:ahash_restore_req
  - crypto/ahash.c:ahash_save_req
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
In fs/verity/hash_algs.c (ffffffff81472d2f)
Location: include/crypto/hash.h:356
Inline: True
Inline callers:
  - fs/verity/hash_algs.c:fsverity_get_hash_alg
```
```
In security/integrity/ima/ima_crypto.c (ffffffff81640eed)
Location: include/crypto/hash.h:356
Inline: True
Inline callers:
  - security/integrity/ima/ima_crypto.c:ima_calc_buffer_hash
  - security/integrity/ima/ima_crypto.c:ima_calc_file_hash_atfm
```
```
In crypto/ahash.c (ffffffff81651627)
Location: include/crypto/hash.h:356
Inline: True
Inline callers:
  - crypto/ahash.c:ahash_restore_req
  - crypto/ahash.c:ahash_save_req
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
In fs/verity/hash_algs.c (ffffffff81504abe)
Location: include/crypto/hash.h:356
Inline: True
Inline callers:
  - fs/verity/hash_algs.c:fsverity_get_hash_alg
```
```
In security/integrity/ima/ima_crypto.c (ffffffff816f8e5d)
Location: include/crypto/hash.h:356
Inline: True
Inline callers:
  - security/integrity/ima/ima_crypto.c:ima_calc_buffer_hash
  - security/integrity/ima/ima_crypto.c:ima_calc_file_hash_atfm
```
```
In crypto/ahash.c (ffffffff8170b2f7)
Location: include/crypto/hash.h:356
Inline: True
Inline callers:
  - crypto/ahash.c:ahash_restore_req
  - crypto/ahash.c:ahash_save_req
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
In security/integrity/ima/ima_crypto.c (ffffffff81733058)
Location: include/crypto/hash.h:387
Inline: True
Inline callers:
  - security/integrity/ima/ima_crypto.c:ima_calc_buffer_hash
  - security/integrity/ima/ima_crypto.c:ima_calc_file_hash_atfm
```
```
In crypto/ahash.c (ffffffff81744987)
Location: include/crypto/hash.h:387
Inline: True
Inline callers:
  - crypto/ahash.c:ahash_restore_req
  - crypto/ahash.c:ahash_save_req
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
In security/integrity/ima/ima_crypto.c (ffffffff81773a6c)
Location: include/crypto/hash.h:368
Inline: True
Inline callers:
  - security/integrity/ima/ima_crypto.c:ima_calc_buffer_hash
  - security/integrity/ima/ima_crypto.c:ima_calc_file_hash_atfm
```
```
In crypto/ahash.c (ffffffff81786f37)
Location: include/crypto/hash.h:368
Inline: True
Inline callers:
  - crypto/ahash.c:ahash_restore_req
```
```
In net/ipv4/tcp_ao.c (ffffffff82056b02)
Location: include/crypto/hash.h:368
Inline: True
Inline callers:
  - net/ipv4/tcp_ao.c:tcp_ao_add_cmd
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
In fs/verity/hash_algs.c (ffff800010411c00)
Location: include/crypto/hash.h:333
Inline: True
Inline callers:
  - fs/verity/hash_algs.c:fsverity_get_hash_alg
```
```
In security/integrity/ima/ima_crypto.c (ffff8000105b0294)
Location: include/crypto/hash.h:333
Inline: True
Inline callers:
  - security/integrity/ima/ima_crypto.c:ima_calc_buffer_hash
  - security/integrity/ima/ima_crypto.c:ima_calc_file_hash_atfm
```
```
In crypto/ahash.c (ffff8000105c0064)
Location: include/crypto/hash.h:333
Inline: True
Inline callers:
  - crypto/ahash.c:ahash_restore_req
  - crypto/ahash.c:ahash_save_req
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
In fs/verity/hash_algs.c (c05de258)
Location: include/crypto/hash.h:333
Inline: True
Inline callers:
  - fs/verity/hash_algs.c:fsverity_get_hash_alg
```
```
In security/integrity/ima/ima_crypto.c (c075f9bc)
Location: include/crypto/hash.h:333
Inline: True
Inline callers:
  - security/integrity/ima/ima_crypto.c:ima_calc_buffer_hash
  - security/integrity/ima/ima_crypto.c:ima_calc_file_hash_atfm
```
```
In crypto/ahash.c (c076dc28)
Location: include/crypto/hash.h:333
Inline: True
Inline callers:
  - crypto/ahash.c:ahash_restore_req
  - crypto/ahash.c:ahash_save_req
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
In fs/verity/hash_algs.c (c00000000051f79c)
Location: include/crypto/hash.h:333
Inline: True
Inline callers:
  - fs/verity/hash_algs.c:fsverity_get_hash_alg
```
```
In security/integrity/ima/ima_crypto.c (c00000000072fd48)
Location: include/crypto/hash.h:333
Inline: True
Inline callers:
  - security/integrity/ima/ima_crypto.c:ima_calc_buffer_hash
  - security/integrity/ima/ima_crypto.c:ima_calc_file_hash_atfm
```
```
In crypto/ahash.c (c000000000748018)
Location: include/crypto/hash.h:333
Inline: True
Inline callers:
  - crypto/ahash.c:ahash_restore_req
  - crypto/ahash.c:ahash_save_req
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
In fs/verity/hash_algs.c (ffffffe0002b9d96)
Location: include/crypto/hash.h:333
Inline: True
Inline callers:
  - fs/verity/hash_algs.c:fsverity_get_hash_alg
```
```
In security/integrity/ima/ima_crypto.c (ffffffe0003f7f34)
Location: include/crypto/hash.h:333
Inline: True
Inline callers:
  - security/integrity/ima/ima_crypto.c:ima_calc_buffer_hash
  - security/integrity/ima/ima_crypto.c:ima_calc_file_hash_atfm
```
```
In crypto/ahash.c (ffffffe0004050a0)
Location: include/crypto/hash.h:333
Inline: True
Inline callers:
  - crypto/ahash.c:ahash_restore_req
  - crypto/ahash.c:ahash_save_req
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
In fs/verity/hash_algs.c (ffffffff8134867b)
Location: include/crypto/hash.h:333
Inline: True
Inline callers:
  - fs/verity/hash_algs.c:fsverity_get_hash_alg
```
```
In security/integrity/ima/ima_crypto.c (ffffffff814b04a5)
Location: include/crypto/hash.h:333
Inline: True
Inline callers:
  - security/integrity/ima/ima_crypto.c:ima_calc_buffer_hash
  - security/integrity/ima/ima_crypto.c:ima_calc_file_hash_atfm
```
```
In crypto/ahash.c (ffffffff814bd9fc)
Location: include/crypto/hash.h:333
Inline: True
Inline callers:
  - crypto/ahash.c:ahash_restore_req
  - crypto/ahash.c:ahash_save_req
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
In fs/verity/hash_algs.c (ffffffff8133935b)
Location: include/crypto/hash.h:333
Inline: True
Inline callers:
  - fs/verity/hash_algs.c:fsverity_get_hash_alg
```
```
In security/integrity/ima/ima_crypto.c (ffffffff814a0ec5)
Location: include/crypto/hash.h:333
Inline: True
Inline callers:
  - security/integrity/ima/ima_crypto.c:ima_calc_buffer_hash
  - security/integrity/ima/ima_crypto.c:ima_calc_file_hash_atfm
```
```
In crypto/ahash.c (ffffffff814ae41c)
Location: include/crypto/hash.h:333
Inline: True
Inline callers:
  - crypto/ahash.c:ahash_restore_req
  - crypto/ahash.c:ahash_save_req
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
In fs/verity/hash_algs.c (ffffffff8134614b)
Location: include/crypto/hash.h:333
Inline: True
Inline callers:
  - fs/verity/hash_algs.c:fsverity_get_hash_alg
```
```
In security/integrity/ima/ima_crypto.c (ffffffff814ac535)
Location: include/crypto/hash.h:333
Inline: True
Inline callers:
  - security/integrity/ima/ima_crypto.c:ima_calc_buffer_hash
  - security/integrity/ima/ima_crypto.c:ima_calc_file_hash_atfm
```
```
In crypto/ahash.c (ffffffff814b9a8c)
Location: include/crypto/hash.h:333
Inline: True
Inline callers:
  - crypto/ahash.c:ahash_restore_req
  - crypto/ahash.c:ahash_save_req
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
In fs/verity/hash_algs.c (ffffffff8135942b)
Location: include/crypto/hash.h:333
Inline: True
Inline callers:
  - fs/verity/hash_algs.c:fsverity_get_hash_alg
```
```
In security/integrity/ima/ima_crypto.c (ffffffff814c4f85)
Location: include/crypto/hash.h:333
Inline: True
Inline callers:
  - security/integrity/ima/ima_crypto.c:ima_calc_buffer_hash
  - security/integrity/ima/ima_crypto.c:ima_calc_file_hash_atfm
```
```
In crypto/ahash.c (ffffffff814d253c)
Location: include/crypto/hash.h:333
Inline: True
Inline callers:
  - crypto/ahash.c:ahash_restore_req
  - crypto/ahash.c:ahash_save_req
```
</details>
</li>
</ul>

## Differences
