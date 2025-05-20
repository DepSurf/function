# Function: <code>crypto_hash_alg_common</code>

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
Location: include/crypto/hash.h:288
Inline: True
```
```
In crypto/ahash.c (ffffffff813a2c12)
Location: include/crypto/hash.h:288
Inline: True
Inline callers:
  - crypto/ahash.c:ahash_def_finup_finish2
  - crypto/ahash.c:crypto_ahash_init_tfm
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
Location: include/crypto/hash.h:311
Inline: True
```
```
In crypto/ahash.c (ffffffff813df0a5)
Location: include/crypto/hash.h:311
Inline: True
Inline callers:
  - crypto/ahash.c:crypto_ahash_init_tfm
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
In security/integrity/ima/ima_crypto.c (0)
Location: include/crypto/hash.h:311
Inline: True
```
```
In crypto/ahash.c (ffffffff813f7635)
Location: include/crypto/hash.h:311
Inline: True
Inline callers:
  - crypto/ahash.c:crypto_ahash_init_tfm
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
In security/integrity/ima/ima_crypto.c (0)
Location: include/crypto/hash.h:311
Inline: True
```
```
In crypto/ahash.c (ffffffff81403c85)
Location: include/crypto/hash.h:311
Inline: True
Inline callers:
  - crypto/ahash.c:crypto_ahash_init_tfm
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
In security/integrity/ima/ima_crypto.c (0)
Location: include/crypto/hash.h:315
Inline: True
```
```
In crypto/ahash.c (ffffffff8142c405)
Location: include/crypto/hash.h:315
Inline: True
Inline callers:
  - crypto/ahash.c:crypto_ahash_init_tfm
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
Location: include/crypto/hash.h:314
Inline: True
Inline callers:
  - security/integrity/ima/ima_crypto.c:ima_calc_buffer_hash
  - security/integrity/ima/ima_crypto.c:ima_calc_file_hash
```
```
In crypto/ahash.c (ffffffff8145f0d5)
Location: include/crypto/hash.h:314
Inline: True
Inline callers:
  - crypto/ahash.c:crypto_ahash_init_tfm
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
Location: include/crypto/hash.h:318
Inline: True
Inline callers:
  - security/integrity/ima/ima_crypto.c:ima_calc_buffer_hash
  - security/integrity/ima/ima_crypto.c:ima_calc_file_hash
```
```
In crypto/ahash.c (ffffffff8147cab5)
Location: include/crypto/hash.h:318
Inline: True
Inline callers:
  - crypto/ahash.c:crypto_ahash_init_tfm
  - crypto/ahash.c:crypto_ahash_init_tfm
  - crypto/ahash.c:ahash_restore_req
  - crypto/ahash.c:ahash_save_req
  - crypto/ahash.c:crypto_ahash_setkey
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
Location: include/crypto/hash.h:317
Inline: True
Inline callers:
  - security/integrity/ima/ima_crypto.c:ima_calc_buffer_hash
  - security/integrity/ima/ima_crypto.c:ima_calc_file_hash_atfm
```
```
In crypto/ahash.c (ffffffff814aaa65)
Location: include/crypto/hash.h:317
Inline: True
Inline callers:
  - crypto/ahash.c:crypto_ahash_init_tfm
  - crypto/ahash.c:crypto_ahash_init_tfm
  - crypto/ahash.c:ahash_restore_req
  - crypto/ahash.c:ahash_save_req
  - crypto/ahash.c:crypto_ahash_setkey
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
Location: include/crypto/hash.h:317
Inline: True
Inline callers:
  - fs/verity/hash_algs.c:fsverity_prepare_hash_state
  - fs/verity/hash_algs.c:fsverity_get_hash_alg
```
```
In security/integrity/ima/ima_crypto.c (ffffffff814b7ec5)
Location: include/crypto/hash.h:317
Inline: True
Inline callers:
  - security/integrity/ima/ima_crypto.c:ima_calc_buffer_hash
  - security/integrity/ima/ima_crypto.c:ima_calc_file_hash_atfm
```
```
In crypto/ahash.c (ffffffff814c5725)
Location: include/crypto/hash.h:317
Inline: True
Inline callers:
  - crypto/ahash.c:crypto_ahash_init_tfm
  - crypto/ahash.c:crypto_ahash_init_tfm
  - crypto/ahash.c:ahash_restore_req
  - crypto/ahash.c:ahash_save_req
  - crypto/ahash.c:crypto_ahash_setkey
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
Location: include/crypto/hash.h:330
Inline: True
Inline callers:
  - fs/verity/hash_algs.c:fsverity_prepare_hash_state
  - fs/verity/hash_algs.c:fsverity_get_hash_alg
```
```
In security/integrity/ima/ima_crypto.c (ffffffff8151718d)
Location: include/crypto/hash.h:330
Inline: True
Inline callers:
  - security/integrity/ima/ima_crypto.c:ima_calc_file_hash_atfm
```
```
In crypto/ahash.c (ffffffff81524ae5)
Location: include/crypto/hash.h:330
Inline: True
Inline callers:
  - crypto/ahash.c:crypto_ahash_init_tfm
  - crypto/ahash.c:crypto_ahash_init_tfm
  - crypto/ahash.c:ahash_restore_req
  - crypto/ahash.c:ahash_save_req
  - crypto/ahash.c:crypto_ahash_setkey
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
Location: include/crypto/hash.h:338
Inline: True
Inline callers:
  - fs/verity/hash_algs.c:fsverity_prepare_hash_state
  - fs/verity/hash_algs.c:fsverity_get_hash_alg
```
```
In security/integrity/ima/ima_crypto.c (ffffffff8153434d)
Location: include/crypto/hash.h:338
Inline: True
Inline callers:
  - security/integrity/ima/ima_crypto.c:ima_calc_file_hash_atfm
```
```
In crypto/ahash.c (ffffffff815419b5)
Location: include/crypto/hash.h:338
Inline: True
Inline callers:
  - crypto/ahash.c:crypto_ahash_init_tfm
  - crypto/ahash.c:crypto_ahash_init_tfm
  - crypto/ahash.c:crypto_ahash_exit_tfm
  - crypto/ahash.c:ahash_restore_req
  - crypto/ahash.c:ahash_save_req
  - crypto/ahash.c:crypto_ahash_setkey
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
Location: include/crypto/hash.h:340
Inline: True
Inline callers:
  - fs/verity/hash_algs.c:fsverity_prepare_hash_state
  - fs/verity/hash_algs.c:fsverity_get_hash_alg
```
```
In security/integrity/ima/ima_crypto.c (ffffffff8153d0a4)
Location: include/crypto/hash.h:340
Inline: True
Inline callers:
  - security/integrity/ima/ima_crypto.c:ima_calc_buffer_hash
  - security/integrity/ima/ima_crypto.c:ima_calc_file_hash_atfm
```
```
In crypto/ahash.c (ffffffff8154a015)
Location: include/crypto/hash.h:340
Inline: True
Inline callers:
  - crypto/ahash.c:crypto_ahash_init_tfm
  - crypto/ahash.c:crypto_ahash_init_tfm
  - crypto/ahash.c:crypto_ahash_exit_tfm
  - crypto/ahash.c:ahash_restore_req
  - crypto/ahash.c:ahash_save_req
  - crypto/ahash.c:crypto_ahash_setkey
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
Location: include/crypto/hash.h:340
Inline: True
Inline callers:
  - fs/verity/hash_algs.c:fsverity_prepare_hash_state
  - fs/verity/hash_algs.c:fsverity_get_hash_alg
```
```
In security/integrity/ima/ima_crypto.c (ffffffff8159bf24)
Location: include/crypto/hash.h:340
Inline: True
Inline callers:
  - security/integrity/ima/ima_crypto.c:ima_calc_buffer_hash
  - security/integrity/ima/ima_crypto.c:ima_calc_file_hash_atfm
```
```
In crypto/ahash.c (ffffffff815aa7f5)
Location: include/crypto/hash.h:340
Inline: True
Inline callers:
  - crypto/ahash.c:crypto_ahash_init_tfm
  - crypto/ahash.c:crypto_ahash_init_tfm
  - crypto/ahash.c:crypto_ahash_exit_tfm
  - crypto/ahash.c:ahash_restore_req
  - crypto/ahash.c:ahash_save_req
  - crypto/ahash.c:crypto_ahash_setkey
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
In fs/verity/hash_algs.c (ffffffff81472efc)
Location: include/crypto/hash.h:340
Inline: True
Inline callers:
  - fs/verity/hash_algs.c:fsverity_prepare_hash_state
  - fs/verity/hash_algs.c:fsverity_get_hash_alg
```
```
In security/integrity/ima/ima_crypto.c (ffffffff81640eed)
Location: include/crypto/hash.h:340
Inline: True
Inline callers:
  - security/integrity/ima/ima_crypto.c:ima_calc_buffer_hash
  - security/integrity/ima/ima_crypto.c:ima_calc_file_hash_atfm
```
```
In crypto/ahash.c (ffffffff81651e65)
Location: include/crypto/hash.h:340
Inline: True
Inline callers:
  - crypto/ahash.c:crypto_ahash_init_tfm
  - crypto/ahash.c:crypto_ahash_exit_tfm
  - crypto/ahash.c:ahash_restore_req
  - crypto/ahash.c:crypto_ahash_setkey
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
In fs/verity/hash_algs.c (ffffffff81504d3c)
Location: include/crypto/hash.h:340
Inline: True
Inline callers:
  - fs/verity/hash_algs.c:fsverity_prepare_hash_state
  - fs/verity/hash_algs.c:fsverity_get_hash_alg
```
```
In security/integrity/ima/ima_crypto.c (ffffffff816f8e5d)
Location: include/crypto/hash.h:340
Inline: True
Inline callers:
  - security/integrity/ima/ima_crypto.c:ima_calc_buffer_hash
  - security/integrity/ima/ima_crypto.c:ima_calc_file_hash_atfm
```
```
In crypto/ahash.c (ffffffff8170b8b5)
Location: include/crypto/hash.h:340
Inline: True
Inline callers:
  - crypto/ahash.c:crypto_ahash_init_tfm
  - crypto/ahash.c:crypto_ahash_exit_tfm
  - crypto/ahash.c:ahash_restore_req
  - crypto/ahash.c:crypto_ahash_setkey
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
Location: include/crypto/hash.h:371
Inline: True
Inline callers:
  - security/integrity/ima/ima_crypto.c:ima_calc_buffer_hash
  - security/integrity/ima/ima_crypto.c:ima_calc_buffer_hash
  - security/integrity/ima/ima_crypto.c:ima_calc_file_hash_atfm
  - security/integrity/ima/ima_crypto.c:ima_calc_file_hash_atfm
```
```
In crypto/ahash.c (ffffffff81744c75)
Location: include/crypto/hash.h:371
Inline: True
Inline callers:
  - crypto/ahash.c:crypto_clone_ahash
  - crypto/ahash.c:crypto_ahash_init_tfm
  - crypto/ahash.c:crypto_ahash_exit_tfm
  - crypto/ahash.c:crypto_ahash_digest
  - crypto/ahash.c:crypto_ahash_finup
  - crypto/ahash.c:crypto_ahash_final
  - crypto/ahash.c:crypto_ahash_op
  - crypto/ahash.c:ahash_restore_req
  - crypto/ahash.c:crypto_ahash_setkey
```
```
In crypto/gcm.c (ffffffff8175309f)
Location: include/crypto/hash.h:371
Inline: True
Inline callers:
  - crypto/gcm.c:gcm_hash_update
```
```
In lib/iov_iter.c (ffffffff81811c27)
Location: include/crypto/hash.h:371
Inline: True
Inline callers:
  - lib/iov_iter.c:hash_and_copy_to_iter
```
```
In net/ipv4/tcp.c (ffffffff81f0ae76)
Location: include/crypto/hash.h:371
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_md5_hash_key
  - net/ipv4/tcp.c:tcp_md5_hash_skb_data
  - net/ipv4/tcp.c:tcp_md5_hash_skb_data
```
```
In net/ipv4/tcp_ipv4.c (ffffffff81f2c119)
Location: include/crypto/hash.h:371
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_md5_hash_headers
```
```
In net/ipv6/tcp_ipv6.c (ffffffff81ffadd5)
Location: include/crypto/hash.h:371
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
In security/integrity/ima/ima_crypto.c (ffffffff81773a6c)
Location: include/crypto/hash.h:352
Inline: True
Inline callers:
  - security/integrity/ima/ima_crypto.c:ima_calc_buffer_hash
  - security/integrity/ima/ima_crypto.c:ima_calc_file_hash_atfm
```
```
In crypto/ahash.c (ffffffff817874a5)
Location: include/crypto/hash.h:352
Inline: True
Inline callers:
  - crypto/ahash.c:crypto_clone_ahash
  - crypto/ahash.c:crypto_clone_ahash
  - crypto/ahash.c:crypto_ahash_init_tfm
  - crypto/ahash.c:crypto_ahash_exit_tfm
  - crypto/ahash.c:crypto_ahash_import
  - crypto/ahash.c:crypto_ahash_export
  - crypto/ahash.c:ahash_def_finup
  - crypto/ahash.c:ahash_def_finup_finish1
  - crypto/ahash.c:crypto_ahash_digest
  - crypto/ahash.c:crypto_ahash_finup
  - crypto/ahash.c:crypto_ahash_final
  - crypto/ahash.c:crypto_ahash_update
  - crypto/ahash.c:ahash_restore_req
  - crypto/ahash.c:crypto_ahash_init
  - crypto/ahash.c:crypto_ahash_setkey
```
```
In net/ipv4/tcp_ao.c (ffffffff82056b02)
Location: include/crypto/hash.h:352
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
In fs/verity/hash_algs.c (ffff800010411d98)
Location: include/crypto/hash.h:317
Inline: True
Inline callers:
  - fs/verity/hash_algs.c:fsverity_prepare_hash_state
  - fs/verity/hash_algs.c:fsverity_get_hash_alg
```
```
In security/integrity/ima/ima_crypto.c (ffff8000105b0294)
Location: include/crypto/hash.h:317
Inline: True
Inline callers:
  - security/integrity/ima/ima_crypto.c:ima_calc_buffer_hash
  - security/integrity/ima/ima_crypto.c:ima_calc_file_hash_atfm
```
```
In crypto/ahash.c (ffff8000105c0408)
Location: include/crypto/hash.h:317
Inline: True
Inline callers:
  - crypto/ahash.c:crypto_ahash_init_tfm
  - crypto/ahash.c:crypto_ahash_init_tfm
  - crypto/ahash.c:ahash_restore_req
  - crypto/ahash.c:ahash_save_req
  - crypto/ahash.c:crypto_ahash_setkey
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
Location: include/crypto/hash.h:317
Inline: True
Inline callers:
  - fs/verity/hash_algs.c:fsverity_prepare_hash_state
  - fs/verity/hash_algs.c:fsverity_get_hash_alg
```
```
In security/integrity/ima/ima_crypto.c (c075f9bc)
Location: include/crypto/hash.h:317
Inline: True
Inline callers:
  - security/integrity/ima/ima_crypto.c:ima_calc_buffer_hash
  - security/integrity/ima/ima_crypto.c:ima_calc_file_hash_atfm
```
```
In crypto/ahash.c (c076df7c)
Location: include/crypto/hash.h:317
Inline: True
Inline callers:
  - crypto/ahash.c:crypto_ahash_init_tfm
  - crypto/ahash.c:crypto_ahash_init_tfm
  - crypto/ahash.c:ahash_restore_req
  - crypto/ahash.c:ahash_save_req
  - crypto/ahash.c:crypto_ahash_setkey
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
Location: include/crypto/hash.h:317
Inline: True
Inline callers:
  - fs/verity/hash_algs.c:fsverity_prepare_hash_state
  - fs/verity/hash_algs.c:fsverity_get_hash_alg
```
```
In security/integrity/ima/ima_crypto.c (c00000000072fd48)
Location: include/crypto/hash.h:317
Inline: True
Inline callers:
  - security/integrity/ima/ima_crypto.c:ima_calc_buffer_hash
  - security/integrity/ima/ima_crypto.c:ima_calc_file_hash_atfm
```
```
In crypto/ahash.c (c0000000007484c0)
Location: include/crypto/hash.h:317
Inline: True
Inline callers:
  - crypto/ahash.c:crypto_ahash_init_tfm
  - crypto/ahash.c:crypto_ahash_init_tfm
  - crypto/ahash.c:ahash_restore_req
  - crypto/ahash.c:ahash_save_req
  - crypto/ahash.c:crypto_ahash_setkey
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
Location: include/crypto/hash.h:317
Inline: True
Inline callers:
  - fs/verity/hash_algs.c:fsverity_prepare_hash_state
  - fs/verity/hash_algs.c:fsverity_get_hash_alg
```
```
In security/integrity/ima/ima_crypto.c (ffffffe0003f7f34)
Location: include/crypto/hash.h:317
Inline: True
Inline callers:
  - security/integrity/ima/ima_crypto.c:ima_calc_buffer_hash
  - security/integrity/ima/ima_crypto.c:ima_calc_file_hash_atfm
```
```
In crypto/ahash.c (ffffffe00040537a)
Location: include/crypto/hash.h:317
Inline: True
Inline callers:
  - crypto/ahash.c:crypto_ahash_init_tfm
  - crypto/ahash.c:crypto_ahash_init_tfm
  - crypto/ahash.c:ahash_restore_req
  - crypto/ahash.c:ahash_save_req
  - crypto/ahash.c:crypto_ahash_setkey
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
Location: include/crypto/hash.h:317
Inline: True
Inline callers:
  - fs/verity/hash_algs.c:fsverity_prepare_hash_state
  - fs/verity/hash_algs.c:fsverity_get_hash_alg
```
```
In security/integrity/ima/ima_crypto.c (ffffffff814b04a5)
Location: include/crypto/hash.h:317
Inline: True
Inline callers:
  - security/integrity/ima/ima_crypto.c:ima_calc_buffer_hash
  - security/integrity/ima/ima_crypto.c:ima_calc_file_hash_atfm
```
```
In crypto/ahash.c (ffffffff814bdd05)
Location: include/crypto/hash.h:317
Inline: True
Inline callers:
  - crypto/ahash.c:crypto_ahash_init_tfm
  - crypto/ahash.c:crypto_ahash_init_tfm
  - crypto/ahash.c:ahash_restore_req
  - crypto/ahash.c:ahash_save_req
  - crypto/ahash.c:crypto_ahash_setkey
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
Location: include/crypto/hash.h:317
Inline: True
Inline callers:
  - fs/verity/hash_algs.c:fsverity_prepare_hash_state
  - fs/verity/hash_algs.c:fsverity_get_hash_alg
```
```
In security/integrity/ima/ima_crypto.c (ffffffff814a0ec5)
Location: include/crypto/hash.h:317
Inline: True
Inline callers:
  - security/integrity/ima/ima_crypto.c:ima_calc_buffer_hash
  - security/integrity/ima/ima_crypto.c:ima_calc_file_hash_atfm
```
```
In crypto/ahash.c (ffffffff814ae725)
Location: include/crypto/hash.h:317
Inline: True
Inline callers:
  - crypto/ahash.c:crypto_ahash_init_tfm
  - crypto/ahash.c:crypto_ahash_init_tfm
  - crypto/ahash.c:ahash_restore_req
  - crypto/ahash.c:ahash_save_req
  - crypto/ahash.c:crypto_ahash_setkey
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
Location: include/crypto/hash.h:317
Inline: True
Inline callers:
  - fs/verity/hash_algs.c:fsverity_prepare_hash_state
  - fs/verity/hash_algs.c:fsverity_get_hash_alg
```
```
In security/integrity/ima/ima_crypto.c (ffffffff814ac535)
Location: include/crypto/hash.h:317
Inline: True
Inline callers:
  - security/integrity/ima/ima_crypto.c:ima_calc_buffer_hash
  - security/integrity/ima/ima_crypto.c:ima_calc_file_hash_atfm
```
```
In crypto/ahash.c (ffffffff814b9d95)
Location: include/crypto/hash.h:317
Inline: True
Inline callers:
  - crypto/ahash.c:crypto_ahash_init_tfm
  - crypto/ahash.c:crypto_ahash_init_tfm
  - crypto/ahash.c:ahash_restore_req
  - crypto/ahash.c:ahash_save_req
  - crypto/ahash.c:crypto_ahash_setkey
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
Location: include/crypto/hash.h:317
Inline: True
Inline callers:
  - fs/verity/hash_algs.c:fsverity_prepare_hash_state
  - fs/verity/hash_algs.c:fsverity_get_hash_alg
```
```
In security/integrity/ima/ima_crypto.c (ffffffff814c4f85)
Location: include/crypto/hash.h:317
Inline: True
Inline callers:
  - security/integrity/ima/ima_crypto.c:ima_calc_buffer_hash
  - security/integrity/ima/ima_crypto.c:ima_calc_file_hash_atfm
```
```
In crypto/ahash.c (ffffffff814d2845)
Location: include/crypto/hash.h:317
Inline: True
Inline callers:
  - crypto/ahash.c:crypto_ahash_init_tfm
  - crypto/ahash.c:crypto_ahash_init_tfm
  - crypto/ahash.c:ahash_restore_req
  - crypto/ahash.c:ahash_save_req
  - crypto/ahash.c:crypto_ahash_setkey
```
</details>
</li>
</ul>

## Differences
