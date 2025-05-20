# Function: <code>__crypto_hash_alg_common</code>

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
In security/integrity/ima/ima_crypto.c (0)
Location: include/crypto/hash.h:282
Inline: True
```
```
In crypto/ahash.c (ffffffff813a30e9)
Location: include/crypto/hash.h:282
Inline: True
Inline callers:
  - crypto/ahash.c:ahash_attr_alg
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
In security/integrity/ima/ima_crypto.c (0)
Location: include/crypto/hash.h:305
Inline: True
```
```
In crypto/ahash.c (ffffffff813df2e9)
Location: include/crypto/hash.h:305
Inline: True
Inline callers:
  - crypto/ahash.c:ahash_attr_alg
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
In security/integrity/ima/ima_crypto.c (0)
Location: include/crypto/hash.h:305
Inline: True
```
```
In crypto/ahash.c (ffffffff813f7879)
Location: include/crypto/hash.h:305
Inline: True
Inline callers:
  - crypto/ahash.c:ahash_attr_alg
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
In security/integrity/ima/ima_crypto.c (0)
Location: include/crypto/hash.h:305
Inline: True
```
```
In crypto/ahash.c (ffffffff81403ec9)
Location: include/crypto/hash.h:305
Inline: True
Inline callers:
  - crypto/ahash.c:ahash_attr_alg
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
In security/integrity/ima/ima_crypto.c (0)
Location: include/crypto/hash.h:309
Inline: True
```
```
In crypto/ahash.c (ffffffff8142c749)
Location: include/crypto/hash.h:309
Inline: True
Inline callers:
  - crypto/ahash.c:ahash_attr_alg
```
```
In crypto/gcm.c (ffffffff8143989f)
Location: include/crypto/hash.h:309
Inline: True
Inline callers:
  - crypto/gcm.c:crypto_gcm_create_common
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
Location: include/crypto/hash.h:308
Inline: True
Inline callers:
  - security/integrity/ima/ima_crypto.c:ima_calc_buffer_hash
  - security/integrity/ima/ima_crypto.c:ima_calc_file_hash
```
```
In crypto/ahash.c (ffffffff8145e8e3)
Location: include/crypto/hash.h:308
Inline: True
Inline callers:
  - crypto/ahash.c:crypto_hash_alg_has_setkey
  - crypto/ahash.c:ahash_attr_alg
  - crypto/ahash.c:crypto_ahash_show
  - crypto/ahash.c:crypto_ahash_report
  - crypto/ahash.c:crypto_ahash_init_tfm
  - crypto/ahash.c:ahash_restore_req
  - crypto/ahash.c:ahash_save_req
```
```
In crypto/gcm.c (ffffffff8146c561)
Location: include/crypto/hash.h:308
Inline: True
Inline callers:
  - crypto/gcm.c:crypto_gcm_create_common
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
Location: include/crypto/hash.h:312
Inline: True
Inline callers:
  - security/integrity/ima/ima_crypto.c:ima_calc_buffer_hash
  - security/integrity/ima/ima_crypto.c:ima_calc_file_hash
```
```
In crypto/ahash.c (ffffffff8147c253)
Location: include/crypto/hash.h:312
Inline: True
Inline callers:
  - crypto/ahash.c:crypto_hash_alg_has_setkey
  - crypto/ahash.c:ahash_attr_alg
  - crypto/ahash.c:crypto_ahash_show
  - crypto/ahash.c:crypto_ahash_report
  - crypto/ahash.c:crypto_ahash_init_tfm
  - crypto/ahash.c:crypto_ahash_init_tfm
  - crypto/ahash.c:ahash_restore_req
  - crypto/ahash.c:ahash_save_req
  - crypto/ahash.c:crypto_ahash_setkey
```
```
In crypto/gcm.c (ffffffff81489cd1)
Location: include/crypto/hash.h:312
Inline: True
Inline callers:
  - crypto/gcm.c:crypto_gcm_create_common
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
Location: include/crypto/hash.h:311
Inline: True
Inline callers:
  - security/integrity/ima/ima_crypto.c:ima_calc_buffer_hash
  - security/integrity/ima/ima_crypto.c:ima_calc_file_hash_atfm
```
```
In crypto/ahash.c (ffffffff814aa543)
Location: include/crypto/hash.h:311
Inline: True
Inline callers:
  - crypto/ahash.c:crypto_hash_alg_has_setkey
  - crypto/ahash.c:ahash_attr_alg
  - crypto/ahash.c:crypto_ahash_show
  - crypto/ahash.c:crypto_ahash_report
  - crypto/ahash.c:crypto_ahash_init_tfm
  - crypto/ahash.c:crypto_ahash_init_tfm
  - crypto/ahash.c:ahash_restore_req
  - crypto/ahash.c:ahash_save_req
  - crypto/ahash.c:crypto_ahash_setkey
```
```
In crypto/gcm.c (ffffffff814b759e)
Location: include/crypto/hash.h:311
Inline: True
Inline callers:
  - crypto/gcm.c:crypto_gcm_create_common
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
In fs/verity/hash_algs.c (ffffffff8135012d)
Location: include/crypto/hash.h:311
Inline: True
Inline callers:
  - fs/verity/hash_algs.c:fsverity_prepare_hash_state
  - fs/verity/hash_algs.c:fsverity_get_hash_alg
```
```
In security/integrity/ima/ima_crypto.c (ffffffff814b7ec5)
Location: include/crypto/hash.h:311
Inline: True
Inline callers:
  - security/integrity/ima/ima_crypto.c:ima_calc_buffer_hash
  - security/integrity/ima/ima_crypto.c:ima_calc_file_hash_atfm
```
```
In crypto/ahash.c (ffffffff814c5203)
Location: include/crypto/hash.h:311
Inline: True
Inline callers:
  - crypto/ahash.c:crypto_hash_alg_has_setkey
  - crypto/ahash.c:ahash_attr_alg
  - crypto/ahash.c:crypto_ahash_show
  - crypto/ahash.c:crypto_ahash_report
  - crypto/ahash.c:crypto_ahash_init_tfm
  - crypto/ahash.c:crypto_ahash_init_tfm
  - crypto/ahash.c:ahash_restore_req
  - crypto/ahash.c:ahash_save_req
  - crypto/ahash.c:crypto_ahash_setkey
```
```
In crypto/gcm.c (ffffffff814d07be)
Location: include/crypto/hash.h:311
Inline: True
Inline callers:
  - crypto/gcm.c:crypto_gcm_create_common
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
In fs/verity/hash_algs.c (ffffffff81396aa0)
Location: include/crypto/hash.h:324
Inline: True
Inline callers:
  - fs/verity/hash_algs.c:fsverity_prepare_hash_state
  - fs/verity/hash_algs.c:fsverity_get_hash_alg
```
```
In security/integrity/ima/ima_crypto.c (ffffffff8151718d)
Location: include/crypto/hash.h:324
Inline: True
Inline callers:
  - security/integrity/ima/ima_crypto.c:ima_calc_file_hash_atfm
```
```
In crypto/ahash.c (ffffffff81524133)
Location: include/crypto/hash.h:324
Inline: True
Inline callers:
  - crypto/ahash.c:crypto_hash_alg_has_setkey
  - crypto/ahash.c:crypto_ahash_show
  - crypto/ahash.c:crypto_ahash_report
  - crypto/ahash.c:crypto_ahash_init_tfm
  - crypto/ahash.c:crypto_ahash_init_tfm
  - crypto/ahash.c:ahash_restore_req
  - crypto/ahash.c:ahash_save_req
  - crypto/ahash.c:crypto_ahash_setkey
```
```
In crypto/gcm.c (ffffffff8152fbda)
Location: include/crypto/hash.h:324
Inline: True
Inline callers:
  - crypto/gcm.c:crypto_gcm_create_common
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
In fs/verity/hash_algs.c (ffffffff813a86d0)
Location: include/crypto/hash.h:332
Inline: True
Inline callers:
  - fs/verity/hash_algs.c:fsverity_prepare_hash_state
  - fs/verity/hash_algs.c:fsverity_get_hash_alg
```
```
In security/integrity/ima/ima_crypto.c (ffffffff8153434d)
Location: include/crypto/hash.h:332
Inline: True
Inline callers:
  - security/integrity/ima/ima_crypto.c:ima_calc_file_hash_atfm
```
```
In crypto/ahash.c (ffffffff81541133)
Location: include/crypto/hash.h:332
Inline: True
Inline callers:
  - crypto/ahash.c:crypto_hash_alg_has_setkey
  - crypto/ahash.c:crypto_ahash_show
  - crypto/ahash.c:crypto_ahash_report
  - crypto/ahash.c:crypto_ahash_init_tfm
  - crypto/ahash.c:crypto_ahash_init_tfm
  - crypto/ahash.c:crypto_ahash_exit_tfm
  - crypto/ahash.c:ahash_restore_req
  - crypto/ahash.c:ahash_save_req
  - crypto/ahash.c:crypto_ahash_setkey
```
```
In crypto/gcm.c (ffffffff8154ce75)
Location: include/crypto/hash.h:332
Inline: True
Inline callers:
  - crypto/gcm.c:crypto_gcm_create_common
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
In fs/verity/hash_algs.c (ffffffff813af740)
Location: include/crypto/hash.h:334
Inline: True
Inline callers:
  - fs/verity/hash_algs.c:fsverity_prepare_hash_state
  - fs/verity/hash_algs.c:fsverity_get_hash_alg
```
```
In security/integrity/ima/ima_crypto.c (ffffffff8153d0a4)
Location: include/crypto/hash.h:334
Inline: True
Inline callers:
  - security/integrity/ima/ima_crypto.c:ima_calc_buffer_hash
  - security/integrity/ima/ima_crypto.c:ima_calc_file_hash_atfm
```
```
In crypto/ahash.c (ffffffff81549f62)
Location: include/crypto/hash.h:334
Inline: True
Inline callers:
  - crypto/ahash.c:crypto_hash_alg_has_setkey
  - crypto/ahash.c:crypto_ahash_show
  - crypto/ahash.c:crypto_ahash_report
  - crypto/ahash.c:crypto_ahash_init_tfm
  - crypto/ahash.c:crypto_ahash_init_tfm
  - crypto/ahash.c:crypto_ahash_exit_tfm
  - crypto/ahash.c:ahash_restore_req
  - crypto/ahash.c:ahash_save_req
  - crypto/ahash.c:crypto_ahash_setkey
```
```
In crypto/gcm.c (ffffffff81554e0a)
Location: include/crypto/hash.h:334
Inline: True
Inline callers:
  - crypto/gcm.c:crypto_gcm_create_common
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
In fs/verity/hash_algs.c (ffffffff813ff330)
Location: include/crypto/hash.h:334
Inline: True
Inline callers:
  - fs/verity/hash_algs.c:fsverity_prepare_hash_state
  - fs/verity/hash_algs.c:fsverity_get_hash_alg
```
```
In security/integrity/ima/ima_crypto.c (ffffffff8159bf24)
Location: include/crypto/hash.h:334
Inline: True
Inline callers:
  - security/integrity/ima/ima_crypto.c:ima_calc_buffer_hash
  - security/integrity/ima/ima_crypto.c:ima_calc_file_hash_atfm
```
```
In crypto/ahash.c (ffffffff815aa742)
Location: include/crypto/hash.h:334
Inline: True
Inline callers:
  - crypto/ahash.c:crypto_hash_alg_has_setkey
  - crypto/ahash.c:crypto_ahash_show
  - crypto/ahash.c:crypto_ahash_report
  - crypto/ahash.c:crypto_ahash_init_tfm
  - crypto/ahash.c:crypto_ahash_init_tfm
  - crypto/ahash.c:crypto_ahash_exit_tfm
  - crypto/ahash.c:ahash_restore_req
  - crypto/ahash.c:ahash_save_req
  - crypto/ahash.c:crypto_ahash_setkey
```
```
In crypto/gcm.c (ffffffff815b5e3a)
Location: include/crypto/hash.h:334
Inline: True
Inline callers:
  - crypto/gcm.c:crypto_gcm_create_common
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
In fs/verity/hash_algs.c (0)
Location: include/crypto/hash.h:334
Inline: True
```
```
In security/integrity/ima/ima_crypto.c (0)
Location: include/crypto/hash.h:334
Inline: True
```
```
In crypto/ahash.c (0)
Location: include/crypto/hash.h:334
Inline: True
```
```
In crypto/gcm.c (0)
Location: include/crypto/hash.h:334
Inline: True
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
In fs/verity/hash_algs.c (0)
Location: include/crypto/hash.h:334
Inline: True
```
```
In security/integrity/ima/ima_crypto.c (0)
Location: include/crypto/hash.h:334
Inline: True
```
```
In crypto/ahash.c (0)
Location: include/crypto/hash.h:334
Inline: True
```
```
In crypto/gcm.c (0)
Location: include/crypto/hash.h:334
Inline: True
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
In security/integrity/ima/ima_crypto.c (0)
Location: include/crypto/hash.h:365
Inline: True
```
```
In crypto/ahash.c (0)
Location: include/crypto/hash.h:365
Inline: True
```
```
In crypto/shash.c (0)
Location: include/crypto/hash.h:365
Inline: True
```
```
In crypto/gcm.c (0)
Location: include/crypto/hash.h:365
Inline: True
```
```
In lib/iov_iter.c (0)
Location: include/crypto/hash.h:365
Inline: True
```
```
In net/ipv4/tcp.c (0)
Location: include/crypto/hash.h:365
Inline: True
```
```
In net/ipv4/tcp_ipv4.c (0)
Location: include/crypto/hash.h:365
Inline: True
```
```
In net/ipv6/tcp_ipv6.c (0)
Location: include/crypto/hash.h:365
Inline: True
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
In security/integrity/ima/ima_crypto.c (0)
Location: include/crypto/hash.h:346
Inline: True
```
```
In crypto/ahash.c (0)
Location: include/crypto/hash.h:346
Inline: True
```
```
In crypto/shash.c (0)
Location: include/crypto/hash.h:346
Inline: True
```
```
In crypto/gcm.c (0)
Location: include/crypto/hash.h:346
Inline: True
```
```
In net/ipv4/tcp_ao.c (0)
Location: include/crypto/hash.h:346
Inline: True
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
In fs/verity/hash_algs.c (ffff800010411d98)
Location: include/crypto/hash.h:311
Inline: True
Inline callers:
  - fs/verity/hash_algs.c:fsverity_prepare_hash_state
  - fs/verity/hash_algs.c:fsverity_get_hash_alg
```
```
In security/integrity/ima/ima_crypto.c (ffff8000105b0294)
Location: include/crypto/hash.h:311
Inline: True
Inline callers:
  - security/integrity/ima/ima_crypto.c:ima_calc_buffer_hash
  - security/integrity/ima/ima_crypto.c:ima_calc_file_hash_atfm
```
```
In crypto/ahash.c (ffff8000105bfdbc)
Location: include/crypto/hash.h:311
Inline: True
Inline callers:
  - crypto/ahash.c:crypto_hash_alg_has_setkey
  - crypto/ahash.c:ahash_attr_alg
  - crypto/ahash.c:crypto_ahash_show
  - crypto/ahash.c:crypto_ahash_init_tfm
  - crypto/ahash.c:crypto_ahash_init_tfm
  - crypto/ahash.c:ahash_restore_req
  - crypto/ahash.c:ahash_save_req
  - crypto/ahash.c:crypto_ahash_setkey
```
```
In crypto/gcm.c (ffff8000105cc020)
Location: include/crypto/hash.h:311
Inline: True
Inline callers:
  - crypto/gcm.c:crypto_gcm_create_common
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
In fs/verity/hash_algs.c (c05de3f4)
Location: include/crypto/hash.h:311
Inline: True
Inline callers:
  - fs/verity/hash_algs.c:fsverity_prepare_hash_state
  - fs/verity/hash_algs.c:fsverity_get_hash_alg
```
```
In security/integrity/ima/ima_crypto.c (c075f9bc)
Location: include/crypto/hash.h:311
Inline: True
Inline callers:
  - security/integrity/ima/ima_crypto.c:ima_calc_buffer_hash
  - security/integrity/ima/ima_crypto.c:ima_calc_file_hash_atfm
```
```
In crypto/ahash.c (c076d9e8)
Location: include/crypto/hash.h:311
Inline: True
Inline callers:
  - crypto/ahash.c:crypto_hash_alg_has_setkey
  - crypto/ahash.c:ahash_attr_alg
  - crypto/ahash.c:crypto_ahash_show
  - crypto/ahash.c:crypto_ahash_report
  - crypto/ahash.c:crypto_ahash_init_tfm
  - crypto/ahash.c:crypto_ahash_init_tfm
  - crypto/ahash.c:ahash_restore_req
  - crypto/ahash.c:ahash_save_req
  - crypto/ahash.c:crypto_ahash_setkey
```
```
In crypto/gcm.c (c077997c)
Location: include/crypto/hash.h:311
Inline: True
Inline callers:
  - crypto/gcm.c:crypto_gcm_create_common
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
In fs/verity/hash_algs.c (c00000000051f998)
Location: include/crypto/hash.h:311
Inline: True
Inline callers:
  - fs/verity/hash_algs.c:fsverity_prepare_hash_state
  - fs/verity/hash_algs.c:fsverity_get_hash_alg
```
```
In security/integrity/ima/ima_crypto.c (c00000000072fd48)
Location: include/crypto/hash.h:311
Inline: True
Inline callers:
  - security/integrity/ima/ima_crypto.c:ima_calc_buffer_hash
  - security/integrity/ima/ima_crypto.c:ima_calc_file_hash_atfm
```
```
In crypto/ahash.c (c000000000747c50)
Location: include/crypto/hash.h:311
Inline: True
Inline callers:
  - crypto/ahash.c:crypto_hash_alg_has_setkey
  - crypto/ahash.c:ahash_attr_alg
  - crypto/ahash.c:crypto_ahash_show
  - crypto/ahash.c:crypto_ahash_report
  - crypto/ahash.c:crypto_ahash_init_tfm
  - crypto/ahash.c:crypto_ahash_init_tfm
  - crypto/ahash.c:ahash_restore_req
  - crypto/ahash.c:ahash_save_req
  - crypto/ahash.c:crypto_ahash_setkey
```
```
In crypto/gcm.c (c000000000758a98)
Location: include/crypto/hash.h:311
Inline: True
Inline callers:
  - crypto/gcm.c:crypto_gcm_create_common
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
In fs/verity/hash_algs.c (ffffffe0002b9ec4)
Location: include/crypto/hash.h:311
Inline: True
Inline callers:
  - fs/verity/hash_algs.c:fsverity_prepare_hash_state
  - fs/verity/hash_algs.c:fsverity_get_hash_alg
```
```
In security/integrity/ima/ima_crypto.c (ffffffe0003f7f34)
Location: include/crypto/hash.h:311
Inline: True
Inline callers:
  - security/integrity/ima/ima_crypto.c:ima_calc_buffer_hash
  - security/integrity/ima/ima_crypto.c:ima_calc_file_hash_atfm
```
```
In crypto/ahash.c (ffffffe000404e10)
Location: include/crypto/hash.h:311
Inline: True
Inline callers:
  - crypto/ahash.c:crypto_hash_alg_has_setkey
  - crypto/ahash.c:ahash_attr_alg
  - crypto/ahash.c:crypto_ahash_show
  - crypto/ahash.c:crypto_ahash_report
  - crypto/ahash.c:crypto_ahash_init_tfm
  - crypto/ahash.c:crypto_ahash_init_tfm
  - crypto/ahash.c:ahash_restore_req
  - crypto/ahash.c:ahash_save_req
  - crypto/ahash.c:crypto_ahash_setkey
```
```
In crypto/gcm.c (ffffffe0004112e6)
Location: include/crypto/hash.h:311
Inline: True
Inline callers:
  - crypto/gcm.c:crypto_gcm_create_common
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
In fs/verity/hash_algs.c (ffffffff8134870d)
Location: include/crypto/hash.h:311
Inline: True
Inline callers:
  - fs/verity/hash_algs.c:fsverity_prepare_hash_state
  - fs/verity/hash_algs.c:fsverity_get_hash_alg
```
```
In security/integrity/ima/ima_crypto.c (ffffffff814b04a5)
Location: include/crypto/hash.h:311
Inline: True
Inline callers:
  - security/integrity/ima/ima_crypto.c:ima_calc_buffer_hash
  - security/integrity/ima/ima_crypto.c:ima_calc_file_hash_atfm
```
```
In crypto/ahash.c (ffffffff814bd7e3)
Location: include/crypto/hash.h:311
Inline: True
Inline callers:
  - crypto/ahash.c:crypto_hash_alg_has_setkey
  - crypto/ahash.c:ahash_attr_alg
  - crypto/ahash.c:crypto_ahash_show
  - crypto/ahash.c:crypto_ahash_report
  - crypto/ahash.c:crypto_ahash_init_tfm
  - crypto/ahash.c:crypto_ahash_init_tfm
  - crypto/ahash.c:ahash_restore_req
  - crypto/ahash.c:ahash_save_req
  - crypto/ahash.c:crypto_ahash_setkey
```
```
In crypto/gcm.c (ffffffff814c8d9e)
Location: include/crypto/hash.h:311
Inline: True
Inline callers:
  - crypto/gcm.c:crypto_gcm_create_common
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
In fs/verity/hash_algs.c (ffffffff813393ed)
Location: include/crypto/hash.h:311
Inline: True
Inline callers:
  - fs/verity/hash_algs.c:fsverity_prepare_hash_state
  - fs/verity/hash_algs.c:fsverity_get_hash_alg
```
```
In security/integrity/ima/ima_crypto.c (ffffffff814a0ec5)
Location: include/crypto/hash.h:311
Inline: True
Inline callers:
  - security/integrity/ima/ima_crypto.c:ima_calc_buffer_hash
  - security/integrity/ima/ima_crypto.c:ima_calc_file_hash_atfm
```
```
In crypto/ahash.c (ffffffff814ae203)
Location: include/crypto/hash.h:311
Inline: True
Inline callers:
  - crypto/ahash.c:crypto_hash_alg_has_setkey
  - crypto/ahash.c:ahash_attr_alg
  - crypto/ahash.c:crypto_ahash_show
  - crypto/ahash.c:crypto_ahash_report
  - crypto/ahash.c:crypto_ahash_init_tfm
  - crypto/ahash.c:crypto_ahash_init_tfm
  - crypto/ahash.c:ahash_restore_req
  - crypto/ahash.c:ahash_save_req
  - crypto/ahash.c:crypto_ahash_setkey
```
```
In crypto/gcm.c (ffffffff814b97be)
Location: include/crypto/hash.h:311
Inline: True
Inline callers:
  - crypto/gcm.c:crypto_gcm_create_common
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
In fs/verity/hash_algs.c (ffffffff813461dd)
Location: include/crypto/hash.h:311
Inline: True
Inline callers:
  - fs/verity/hash_algs.c:fsverity_prepare_hash_state
  - fs/verity/hash_algs.c:fsverity_get_hash_alg
```
```
In security/integrity/ima/ima_crypto.c (ffffffff814ac535)
Location: include/crypto/hash.h:311
Inline: True
Inline callers:
  - security/integrity/ima/ima_crypto.c:ima_calc_buffer_hash
  - security/integrity/ima/ima_crypto.c:ima_calc_file_hash_atfm
```
```
In crypto/ahash.c (ffffffff814b9873)
Location: include/crypto/hash.h:311
Inline: True
Inline callers:
  - crypto/ahash.c:crypto_hash_alg_has_setkey
  - crypto/ahash.c:ahash_attr_alg
  - crypto/ahash.c:crypto_ahash_show
  - crypto/ahash.c:crypto_ahash_report
  - crypto/ahash.c:crypto_ahash_init_tfm
  - crypto/ahash.c:crypto_ahash_init_tfm
  - crypto/ahash.c:ahash_restore_req
  - crypto/ahash.c:ahash_save_req
  - crypto/ahash.c:crypto_ahash_setkey
```
```
In crypto/gcm.c (ffffffff814c4e2e)
Location: include/crypto/hash.h:311
Inline: True
Inline callers:
  - crypto/gcm.c:crypto_gcm_create_common
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
In fs/verity/hash_algs.c (ffffffff813594bd)
Location: include/crypto/hash.h:311
Inline: True
Inline callers:
  - fs/verity/hash_algs.c:fsverity_prepare_hash_state
  - fs/verity/hash_algs.c:fsverity_get_hash_alg
```
```
In security/integrity/ima/ima_crypto.c (ffffffff814c4f85)
Location: include/crypto/hash.h:311
Inline: True
Inline callers:
  - security/integrity/ima/ima_crypto.c:ima_calc_buffer_hash
  - security/integrity/ima/ima_crypto.c:ima_calc_file_hash_atfm
```
```
In crypto/ahash.c (ffffffff814d2413)
Location: include/crypto/hash.h:311
Inline: True
Inline callers:
  - crypto/ahash.c:crypto_hash_alg_has_setkey
  - crypto/ahash.c:ahash_attr_alg
  - crypto/ahash.c:crypto_ahash_show
  - crypto/ahash.c:crypto_ahash_report
  - crypto/ahash.c:crypto_ahash_init_tfm
  - crypto/ahash.c:crypto_ahash_init_tfm
  - crypto/ahash.c:ahash_restore_req
  - crypto/ahash.c:ahash_save_req
  - crypto/ahash.c:crypto_ahash_setkey
```
```
In crypto/gcm.c (ffffffff814dd8fe)
Location: include/crypto/hash.h:311
Inline: True
Inline callers:
  - crypto/gcm.c:crypto_gcm_create_common
```
</details>
</li>
</ul>

## Differences
