# Function: <code>crypto_free_ahash</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In security/integrity/ima/ima_crypto.c (ffffffff81398301)
Location: include/crypto/hash.h:257
Inline: True
Inline callers:
  - security/integrity/ima/ima_crypto.c:ima_calc_file_hash
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In security/integrity/ima/ima_crypto.c (ffffffff813d49c6)
Location: include/crypto/hash.h:258
Inline: True
Inline callers:
  - security/integrity/ima/ima_crypto.c:ima_calc_buffer_hash
  - security/integrity/ima/ima_crypto.c:ima_calc_file_hash
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
In security/integrity/ima/ima_crypto.c (ffffffff813ec416)
Location: include/crypto/hash.h:258
Inline: True
Inline callers:
  - security/integrity/ima/ima_crypto.c:ima_calc_buffer_hash
  - security/integrity/ima/ima_crypto.c:ima_calc_file_hash
```
```
In arch/x86/power/hibernate_64.c (ffffffff8178d6c3)
Location: include/crypto/hash.h:258
Inline: True
Inline callers:
  - arch/x86/power/hibernate_64.c:get_e820_md5
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
In security/integrity/ima/ima_crypto.c (ffffffff813f87cd)
Location: include/crypto/hash.h:258
Inline: True
Inline callers:
  - security/integrity/ima/ima_crypto.c:ima_calc_buffer_hash
  - security/integrity/ima/ima_crypto.c:ima_calc_file_hash
```
```
In arch/x86/power/hibernate_64.c (ffffffff817ab853)
Location: include/crypto/hash.h:258
Inline: True
Inline callers:
  - arch/x86/power/hibernate_64.c:get_e820_md5
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
In security/integrity/ima/ima_crypto.c (ffffffff81420bf6)
Location: include/crypto/hash.h:262
Inline: True
Inline callers:
  - security/integrity/ima/ima_crypto.c:ima_calc_buffer_hash
  - security/integrity/ima/ima_crypto.c:ima_calc_file_hash
```
```
In crypto/gcm.c (ffffffff81438c71)
Location: include/crypto/hash.h:262
Inline: True
Inline callers:
  - crypto/gcm.c:crypto_gcm_exit_tfm
  - crypto/gcm.c:crypto_gcm_init_tfm
```
```
In arch/x86/power/hibernate_64.c (ffffffff81822dc3)
Location: include/crypto/hash.h:262
Inline: True
Inline callers:
  - arch/x86/power/hibernate_64.c:get_e820_md5
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
In security/integrity/ima/ima_crypto.c (ffffffff81453078)
Location: include/crypto/hash.h:261
Inline: True
Inline callers:
  - security/integrity/ima/ima_crypto.c:ima_calc_buffer_hash
  - security/integrity/ima/ima_crypto.c:ima_calc_file_hash
```
```
In crypto/gcm.c (ffffffff8146af71)
Location: include/crypto/hash.h:261
Inline: True
Inline callers:
  - crypto/gcm.c:crypto_gcm_exit_tfm
  - crypto/gcm.c:crypto_gcm_init_tfm
```
```
In arch/x86/power/hibernate_64.c (ffffffff8186d0a9)
Location: include/crypto/hash.h:261
Inline: True
Inline callers:
  - arch/x86/power/hibernate_64.c:get_e820_md5
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
In security/integrity/ima/ima_crypto.c (ffffffff81470228)
Location: include/crypto/hash.h:265
Inline: True
Inline callers:
  - security/integrity/ima/ima_crypto.c:ima_calc_buffer_hash
  - security/integrity/ima/ima_crypto.c:ima_calc_file_hash
```
```
In crypto/gcm.c (ffffffff81488871)
Location: include/crypto/hash.h:265
Inline: True
Inline callers:
  - crypto/gcm.c:crypto_gcm_exit_tfm
  - crypto/gcm.c:crypto_gcm_init_tfm
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
In security/integrity/ima/ima_crypto.c (ffffffff8149dbf7)
Location: include/crypto/hash.h:264
Inline: True
Inline callers:
  - security/integrity/ima/ima_crypto.c:ima_calc_buffer_hash
  - security/integrity/ima/ima_crypto.c:ima_calc_file_hash
```
```
In crypto/gcm.c (ffffffff814b65b1)
Location: include/crypto/hash.h:264
Inline: True
Inline callers:
  - crypto/gcm.c:crypto_gcm_exit_tfm
  - crypto/gcm.c:crypto_gcm_init_tfm
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
In fs/verity/hash_algs.c (ffffffff813500b5)
Location: include/crypto/hash.h:264
Inline: True
Inline callers:
  - fs/verity/hash_algs.c:fsverity_get_hash_alg
  - fs/verity/hash_algs.c:fsverity_get_hash_alg
```
```
In security/integrity/ima/ima_crypto.c (ffffffff814b8037)
Location: include/crypto/hash.h:264
Inline: True
Inline callers:
  - security/integrity/ima/ima_crypto.c:ima_calc_buffer_hash
  - security/integrity/ima/ima_crypto.c:ima_calc_file_hash
```
```
In crypto/gcm.c (ffffffff814cf7d1)
Location: include/crypto/hash.h:264
Inline: True
Inline callers:
  - crypto/gcm.c:crypto_gcm_exit_tfm
  - crypto/gcm.c:crypto_gcm_init_tfm
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
In fs/verity/hash_algs.c (ffffffff813969bf)
Location: include/crypto/hash.h:277
Inline: True
Inline callers:
  - fs/verity/hash_algs.c:fsverity_get_hash_alg
```
```
In security/integrity/ima/ima_crypto.c (ffffffff81517be0)
Location: include/crypto/hash.h:277
Inline: True
Inline callers:
  - security/integrity/ima/ima_crypto.c:ima_calc_buffer_hash
  - security/integrity/ima/ima_crypto.c:ima_calc_file_hash
```
```
In crypto/gcm.c (ffffffff8152e9d1)
Location: include/crypto/hash.h:277
Inline: True
Inline callers:
  - crypto/gcm.c:crypto_gcm_exit_tfm
  - crypto/gcm.c:crypto_gcm_init_tfm
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
In fs/verity/hash_algs.c (ffffffff813a85ef)
Location: include/crypto/hash.h:285
Inline: True
Inline callers:
  - fs/verity/hash_algs.c:fsverity_get_hash_alg
```
```
In security/integrity/ima/ima_crypto.c (ffffffff81534ce7)
Location: include/crypto/hash.h:285
Inline: True
Inline callers:
  - security/integrity/ima/ima_crypto.c:ima_calc_buffer_hash
  - security/integrity/ima/ima_crypto.c:ima_calc_file_hash
```
```
In crypto/gcm.c (ffffffff8154b951)
Location: include/crypto/hash.h:285
Inline: True
Inline callers:
  - crypto/gcm.c:crypto_gcm_exit_tfm
  - crypto/gcm.c:crypto_gcm_init_tfm
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
In fs/verity/hash_algs.c (ffffffff813af63f)
Location: include/crypto/hash.h:287
Inline: True
Inline callers:
  - fs/verity/hash_algs.c:fsverity_get_hash_alg
```
```
In security/integrity/ima/ima_crypto.c (ffffffff8153d21d)
Location: include/crypto/hash.h:287
Inline: True
Inline callers:
  - security/integrity/ima/ima_crypto.c:ima_calc_buffer_hash
  - security/integrity/ima/ima_crypto.c:ima_calc_file_hash
```
```
In crypto/gcm.c (ffffffff81553f51)
Location: include/crypto/hash.h:287
Inline: True
Inline callers:
  - crypto/gcm.c:crypto_gcm_exit_tfm
  - crypto/gcm.c:crypto_gcm_init_tfm
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
In fs/verity/hash_algs.c (ffffffff813ff20a)
Location: include/crypto/hash.h:287
Inline: True
Inline callers:
  - fs/verity/hash_algs.c:fsverity_get_hash_alg
```
```
In security/integrity/ima/ima_crypto.c (ffffffff8159c09d)
Location: include/crypto/hash.h:287
Inline: True
Inline callers:
  - security/integrity/ima/ima_crypto.c:ima_calc_buffer_hash
  - security/integrity/ima/ima_crypto.c:ima_calc_file_hash
```
```
In crypto/gcm.c (ffffffff815b4f81)
Location: include/crypto/hash.h:287
Inline: True
Inline callers:
  - crypto/gcm.c:crypto_gcm_exit_tfm
  - crypto/gcm.c:crypto_gcm_init_tfm
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
In fs/verity/hash_algs.c (ffffffff81472d78)
Location: include/crypto/hash.h:287
Inline: True
Inline callers:
  - fs/verity/hash_algs.c:fsverity_get_hash_alg
```
```
In security/integrity/ima/ima_crypto.c (ffffffff81641084)
Location: include/crypto/hash.h:287
Inline: True
Inline callers:
  - security/integrity/ima/ima_crypto.c:ima_calc_buffer_hash
  - security/integrity/ima/ima_crypto.c:ima_calc_file_hash
```
```
In crypto/gcm.c (ffffffff8165dff1)
Location: include/crypto/hash.h:287
Inline: True
Inline callers:
  - crypto/gcm.c:crypto_gcm_exit_tfm
  - crypto/gcm.c:crypto_gcm_init_tfm
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
In fs/verity/hash_algs.c (ffffffff81504b0c)
Location: include/crypto/hash.h:287
Inline: True
Inline callers:
  - fs/verity/hash_algs.c:fsverity_get_hash_alg
```
```
In security/integrity/ima/ima_crypto.c (ffffffff816f8ff4)
Location: include/crypto/hash.h:287
Inline: True
Inline callers:
  - security/integrity/ima/ima_crypto.c:ima_calc_buffer_hash
  - security/integrity/ima/ima_crypto.c:ima_calc_file_hash
```
```
In crypto/gcm.c (ffffffff81717931)
Location: include/crypto/hash.h:287
Inline: True
Inline callers:
  - crypto/gcm.c:crypto_gcm_exit_tfm
  - crypto/gcm.c:crypto_gcm_init_tfm
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
In security/integrity/ima/ima_crypto.c (ffffffff817331b2)
Location: include/crypto/hash.h:318
Inline: True
Inline callers:
  - security/integrity/ima/ima_crypto.c:ima_calc_buffer_hash
  - security/integrity/ima/ima_crypto.c:ima_calc_file_hash
```
```
In crypto/ahash.c (ffffffff81744d89)
Location: include/crypto/hash.h:318
Inline: True
Inline callers:
  - crypto/ahash.c:crypto_clone_ahash
```
```
In crypto/shash.c (ffffffff81746c02)
Location: include/crypto/hash.h:318
Inline: True
Inline callers:
  - crypto/shash.c:crypto_clone_shash_ops_async
```
```
In crypto/gcm.c (ffffffff81753311)
Location: include/crypto/hash.h:318
Inline: True
Inline callers:
  - crypto/gcm.c:crypto_gcm_exit_tfm
  - crypto/gcm.c:crypto_gcm_init_tfm
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
In security/integrity/ima/ima_crypto.c (ffffffff81773bba)
Location: include/crypto/hash.h:305
Inline: True
Inline callers:
  - security/integrity/ima/ima_crypto.c:ima_calc_buffer_hash
  - security/integrity/ima/ima_crypto.c:ima_calc_file_hash
```
```
In crypto/ahash.c (ffffffff817875dd)
Location: include/crypto/hash.h:305
Inline: True
Inline callers:
  - crypto/ahash.c:crypto_clone_ahash
```
```
In crypto/gcm.c (ffffffff817951e1)
Location: include/crypto/hash.h:305
Inline: True
Inline callers:
  - crypto/gcm.c:crypto_gcm_exit_tfm
  - crypto/gcm.c:crypto_gcm_init_tfm
```
```
In net/ipv4/tcp_sigpool.c (ffffffff8204c5d1)
Location: include/crypto/hash.h:305
Inline: True
Inline callers:
  - net/ipv4/tcp_sigpool.c:tcp_sigpool_end
  - net/ipv4/tcp_sigpool.c:tcp_sigpool_start
  - net/ipv4/tcp_sigpool.c:cpool_cleanup_work_cb
  - net/ipv4/tcp_sigpool.c:tcp_sigpool_alloc_ahash
  - net/ipv4/tcp_sigpool.c:tcp_sigpool_alloc_ahash
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
In fs/verity/hash_algs.c (ffff800010411c68)
Location: include/crypto/hash.h:264
Inline: True
Inline callers:
  - fs/verity/hash_algs.c:fsverity_get_hash_alg
  - fs/verity/hash_algs.c:fsverity_get_hash_alg
```
```
In security/integrity/ima/ima_crypto.c (ffff8000105b03d0)
Location: include/crypto/hash.h:264
Inline: True
Inline callers:
  - security/integrity/ima/ima_crypto.c:ima_calc_buffer_hash
  - security/integrity/ima/ima_crypto.c:ima_calc_file_hash
```
```
In crypto/gcm.c (ffff8000105cb8c4)
Location: include/crypto/hash.h:264
Inline: True
Inline callers:
  - crypto/gcm.c:crypto_gcm_exit_tfm
  - crypto/gcm.c:crypto_gcm_init_tfm
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
In fs/verity/hash_algs.c (c05de2bc)
Location: include/crypto/hash.h:264
Inline: True
Inline callers:
  - fs/verity/hash_algs.c:fsverity_get_hash_alg
  - fs/verity/hash_algs.c:fsverity_get_hash_alg
```
```
In security/integrity/ima/ima_crypto.c (c075fb34)
Location: include/crypto/hash.h:264
Inline: True
Inline callers:
  - security/integrity/ima/ima_crypto.c:ima_calc_buffer_hash
  - security/integrity/ima/ima_crypto.c:ima_calc_file_hash
```
```
In crypto/gcm.c (c0779300)
Location: include/crypto/hash.h:264
Inline: True
Inline callers:
  - crypto/gcm.c:crypto_gcm_exit_tfm
  - crypto/gcm.c:crypto_gcm_init_tfm
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
In fs/verity/hash_algs.c (c00000000051f7e0)
Location: include/crypto/hash.h:264
Inline: True
Inline callers:
  - fs/verity/hash_algs.c:fsverity_get_hash_alg
  - fs/verity/hash_algs.c:fsverity_get_hash_alg
```
```
In security/integrity/ima/ima_crypto.c (c00000000072fee0)
Location: include/crypto/hash.h:264
Inline: True
Inline callers:
  - security/integrity/ima/ima_crypto.c:ima_calc_buffer_hash
  - security/integrity/ima/ima_crypto.c:ima_calc_file_hash
```
```
In crypto/gcm.c (c0000000007569d8)
Location: include/crypto/hash.h:264
Inline: True
Inline callers:
  - crypto/gcm.c:crypto_gcm_exit_tfm
  - crypto/gcm.c:crypto_gcm_init_tfm
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
In fs/verity/hash_algs.c (ffffffe0002b9ddc)
Location: include/crypto/hash.h:264
Inline: True
Inline callers:
  - fs/verity/hash_algs.c:fsverity_get_hash_alg
  - fs/verity/hash_algs.c:fsverity_get_hash_alg
```
```
In security/integrity/ima/ima_crypto.c (ffffffe0003f805e)
Location: include/crypto/hash.h:264
Inline: True
Inline callers:
  - security/integrity/ima/ima_crypto.c:ima_calc_buffer_hash
  - security/integrity/ima/ima_crypto.c:ima_calc_file_hash
```
```
In crypto/gcm.c (ffffffe00040fc10)
Location: include/crypto/hash.h:264
Inline: True
Inline callers:
  - crypto/gcm.c:crypto_gcm_exit_tfm
  - crypto/gcm.c:crypto_gcm_init_tfm
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
In fs/verity/hash_algs.c (ffffffff81348695)
Location: include/crypto/hash.h:264
Inline: True
Inline callers:
  - fs/verity/hash_algs.c:fsverity_get_hash_alg
  - fs/verity/hash_algs.c:fsverity_get_hash_alg
```
```
In security/integrity/ima/ima_crypto.c (ffffffff814b0617)
Location: include/crypto/hash.h:264
Inline: True
Inline callers:
  - security/integrity/ima/ima_crypto.c:ima_calc_buffer_hash
  - security/integrity/ima/ima_crypto.c:ima_calc_file_hash
```
```
In crypto/gcm.c (ffffffff814c7db1)
Location: include/crypto/hash.h:264
Inline: True
Inline callers:
  - crypto/gcm.c:crypto_gcm_exit_tfm
  - crypto/gcm.c:crypto_gcm_init_tfm
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
In fs/verity/hash_algs.c (ffffffff81339375)
Location: include/crypto/hash.h:264
Inline: True
Inline callers:
  - fs/verity/hash_algs.c:fsverity_get_hash_alg
  - fs/verity/hash_algs.c:fsverity_get_hash_alg
```
```
In security/integrity/ima/ima_crypto.c (ffffffff814a1037)
Location: include/crypto/hash.h:264
Inline: True
Inline callers:
  - security/integrity/ima/ima_crypto.c:ima_calc_buffer_hash
  - security/integrity/ima/ima_crypto.c:ima_calc_file_hash
```
```
In crypto/gcm.c (ffffffff814b87d1)
Location: include/crypto/hash.h:264
Inline: True
Inline callers:
  - crypto/gcm.c:crypto_gcm_exit_tfm
  - crypto/gcm.c:crypto_gcm_init_tfm
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
In fs/verity/hash_algs.c (ffffffff81346165)
Location: include/crypto/hash.h:264
Inline: True
Inline callers:
  - fs/verity/hash_algs.c:fsverity_get_hash_alg
  - fs/verity/hash_algs.c:fsverity_get_hash_alg
```
```
In security/integrity/ima/ima_crypto.c (ffffffff814ac6a7)
Location: include/crypto/hash.h:264
Inline: True
Inline callers:
  - security/integrity/ima/ima_crypto.c:ima_calc_buffer_hash
  - security/integrity/ima/ima_crypto.c:ima_calc_file_hash
```
```
In crypto/gcm.c (ffffffff814c3e41)
Location: include/crypto/hash.h:264
Inline: True
Inline callers:
  - crypto/gcm.c:crypto_gcm_exit_tfm
  - crypto/gcm.c:crypto_gcm_init_tfm
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
In fs/verity/hash_algs.c (ffffffff81359445)
Location: include/crypto/hash.h:264
Inline: True
Inline callers:
  - fs/verity/hash_algs.c:fsverity_get_hash_alg
  - fs/verity/hash_algs.c:fsverity_get_hash_alg
```
```
In security/integrity/ima/ima_crypto.c (ffffffff814c50f7)
Location: include/crypto/hash.h:264
Inline: True
Inline callers:
  - security/integrity/ima/ima_crypto.c:ima_calc_buffer_hash
  - security/integrity/ima/ima_crypto.c:ima_calc_file_hash
```
```
In crypto/gcm.c (ffffffff814dc911)
Location: include/crypto/hash.h:264
Inline: True
Inline callers:
  - crypto/gcm.c:crypto_gcm_exit_tfm
  - crypto/gcm.c:crypto_gcm_init_tfm
```
</details>
</li>
</ul>

## Differences
