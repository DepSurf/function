# Function: <code>crypto_ahash_reqtfm</code>

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
Location: include/crypto/hash.h:339
Inline: True
```
```
In crypto/ahash.c (ffffffff813a2d96)
Location: include/crypto/hash.h:339
Inline: True
Inline callers:
  - crypto/ahash.c:ahash_def_finup
```
```
In crypto/shash.c (0)
Location: include/crypto/hash.h:339
Inline: True
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
Location: include/crypto/hash.h:362
Inline: True
```
```
In crypto/ahash.c (ffffffff813def46)
Location: include/crypto/hash.h:362
Inline: True
Inline callers:
  - crypto/ahash.c:ahash_def_finup
```
```
In crypto/shash.c (0)
Location: include/crypto/hash.h:362
Inline: True
```
```
In net/ipv4/tcp.c (0)
Location: include/crypto/hash.h:362
Inline: True
```
```
In net/ipv4/tcp_ipv4.c (0)
Location: include/crypto/hash.h:362
Inline: True
```
```
In net/ipv6/tcp_ipv6.c (0)
Location: include/crypto/hash.h:362
Inline: True
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
Location: include/crypto/hash.h:362
Inline: True
```
```
In crypto/ahash.c (ffffffff813f74d6)
Location: include/crypto/hash.h:362
Inline: True
Inline callers:
  - crypto/ahash.c:ahash_def_finup
```
```
In crypto/shash.c (0)
Location: include/crypto/hash.h:362
Inline: True
```
```
In arch/x86/power/hibernate_64.c (0)
Location: include/crypto/hash.h:362
Inline: True
```
```
In net/ipv4/tcp.c (0)
Location: include/crypto/hash.h:362
Inline: True
```
```
In net/ipv4/tcp_ipv4.c (0)
Location: include/crypto/hash.h:362
Inline: True
```
```
In net/ipv6/tcp_ipv6.c (0)
Location: include/crypto/hash.h:362
Inline: True
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
Location: include/crypto/hash.h:372
Inline: True
```
```
In crypto/ahash.c (ffffffff81403a56)
Location: include/crypto/hash.h:372
Inline: True
Inline callers:
  - crypto/ahash.c:ahash_def_finup
```
```
In crypto/shash.c (0)
Location: include/crypto/hash.h:372
Inline: True
```
```
In arch/x86/power/hibernate_64.c (0)
Location: include/crypto/hash.h:372
Inline: True
```
```
In net/ipv4/tcp.c (0)
Location: include/crypto/hash.h:372
Inline: True
```
```
In net/ipv4/tcp_ipv4.c (0)
Location: include/crypto/hash.h:372
Inline: True
```
```
In net/ipv6/tcp_ipv6.c (0)
Location: include/crypto/hash.h:372
Inline: True
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
In security/integrity/ima/ima_crypto.c (ffffffff81420b05)
Location: include/crypto/hash.h:376
Inline: True
Inline callers:
  - security/integrity/ima/ima_crypto.c:ima_calc_buffer_hash
  - security/integrity/ima/ima_crypto.c:ima_calc_file_hash
```
```
In crypto/ahash.c (ffffffff8142c1b6)
Location: include/crypto/hash.h:376
Inline: True
Inline callers:
  - crypto/ahash.c:ahash_def_finup
  - crypto/ahash.c:crypto_ahash_digest
```
```
In crypto/shash.c (0)
Location: include/crypto/hash.h:376
Inline: True
```
```
In crypto/gcm.c (0)
Location: include/crypto/hash.h:376
Inline: True
```
```
In arch/x86/power/hibernate_64.c (0)
Location: include/crypto/hash.h:376
Inline: True
```
```
In net/ipv4/tcp.c (0)
Location: include/crypto/hash.h:376
Inline: True
```
```
In net/ipv4/tcp_ipv4.c (ffffffff818b8592)
Location: include/crypto/hash.h:376
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_md5_hash_skb
  - net/ipv4/tcp_ipv4.c:tcp_v4_md5_hash_hdr
```
```
In net/ipv6/tcp_ipv6.c (ffffffff81938dcb)
Location: include/crypto/hash.h:376
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_response
  - net/ipv6/tcp_ipv6.c:tcp_v6_md5_hash_skb
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
In security/integrity/ima/ima_crypto.c (ffffffff81452fa9)
Location: include/crypto/hash.h:375
Inline: True
Inline callers:
  - security/integrity/ima/ima_crypto.c:ima_calc_buffer_hash
  - security/integrity/ima/ima_crypto.c:ima_calc_buffer_hash
  - security/integrity/ima/ima_crypto.c:ima_calc_file_hash
  - security/integrity/ima/ima_crypto.c:ima_calc_file_hash
```
```
In crypto/ahash.c (ffffffff8145ee85)
Location: include/crypto/hash.h:375
Inline: True
Inline callers:
  - crypto/ahash.c:ahash_def_finup
  - crypto/ahash.c:ahash_def_finup_finish1
  - crypto/ahash.c:crypto_ahash_digest
  - crypto/ahash.c:crypto_ahash_finup
  - crypto/ahash.c:crypto_ahash_final
  - crypto/ahash.c:crypto_ahash_op
  - crypto/ahash.c:ahash_restore_req
  - crypto/ahash.c:ahash_save_req
```
```
In crypto/shash.c (ffffffff8145f4f5)
Location: include/crypto/hash.h:375
Inline: True
Inline callers:
  - crypto/shash.c:shash_async_import
  - crypto/shash.c:shash_async_digest
  - crypto/shash.c:shash_async_finup
  - crypto/shash.c:shash_async_init
```
```
In crypto/gcm.c (ffffffff8146b9f2)
Location: include/crypto/hash.h:375
Inline: True
Inline callers:
  - crypto/gcm.c:gcm_hash
  - crypto/gcm.c:gcm_hash_init_continue
  - crypto/gcm.c:gcm_hash_assoc_continue
  - crypto/gcm.c:gcm_hash_assoc_remain_continue
  - crypto/gcm.c:gcm_hash_crypt_continue
```
```
In arch/x86/power/hibernate_64.c (ffffffff8186d091)
Location: include/crypto/hash.h:375
Inline: True
Inline callers:
  - arch/x86/power/hibernate_64.c:get_e820_md5
```
```
In net/ipv4/tcp.c (ffffffff818f6556)
Location: include/crypto/hash.h:375
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_md5_hash_key
  - net/ipv4/tcp.c:tcp_md5_hash_skb_data
  - net/ipv4/tcp.c:tcp_md5_hash_skb_data
```
```
In net/ipv4/tcp_ipv4.c (ffffffff8190eb46)
Location: include/crypto/hash.h:375
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_md5_hash_skb
  - net/ipv4/tcp_ipv4.c:tcp_v4_md5_hash_hdr
```
```
In net/ipv6/tcp_ipv6.c (ffffffff81992637)
Location: include/crypto/hash.h:375
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_response
  - net/ipv6/tcp_ipv6.c:tcp_v6_md5_hash_skb
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
In security/integrity/ima/ima_crypto.c (ffffffff81470111)
Location: include/crypto/hash.h:379
Inline: True
Inline callers:
  - security/integrity/ima/ima_crypto.c:ima_calc_buffer_hash
  - security/integrity/ima/ima_crypto.c:ima_calc_buffer_hash
  - security/integrity/ima/ima_crypto.c:ima_calc_buffer_hash
  - security/integrity/ima/ima_crypto.c:ima_calc_file_hash
  - security/integrity/ima/ima_crypto.c:ima_calc_file_hash
  - security/integrity/ima/ima_crypto.c:ima_calc_file_hash
```
```
In crypto/ahash.c (ffffffff8147c785)
Location: include/crypto/hash.h:379
Inline: True
Inline callers:
  - crypto/ahash.c:ahash_def_finup
  - crypto/ahash.c:ahash_def_finup_finish1
  - crypto/ahash.c:crypto_ahash_digest
  - crypto/ahash.c:crypto_ahash_finup
  - crypto/ahash.c:crypto_ahash_finup
  - crypto/ahash.c:crypto_ahash_final
  - crypto/ahash.c:crypto_ahash_final
  - crypto/ahash.c:crypto_ahash_op
  - crypto/ahash.c:ahash_restore_req
  - crypto/ahash.c:ahash_save_req
```
```
In crypto/shash.c (ffffffff8147cf25)
Location: include/crypto/hash.h:379
Inline: True
Inline callers:
  - crypto/shash.c:shash_async_import
  - crypto/shash.c:shash_async_digest
  - crypto/shash.c:shash_async_finup
  - crypto/shash.c:shash_async_init
```
```
In crypto/gcm.c (ffffffff81488f52)
Location: include/crypto/hash.h:379
Inline: True
Inline callers:
  - crypto/gcm.c:gcm_hash
  - crypto/gcm.c:gcm_hash_update
  - crypto/gcm.c:gcm_hash_update
```
```
In lib/iov_iter.c (ffffffff814dd3da)
Location: include/crypto/hash.h:379
Inline: True
Inline callers:
  - lib/iov_iter.c:hash_and_copy_to_iter
  - lib/iov_iter.c:hash_and_copy_to_iter
```
```
In net/ipv4/tcp.c (ffffffff81926a16)
Location: include/crypto/hash.h:379
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_md5_hash_key
  - net/ipv4/tcp.c:tcp_md5_hash_key
  - net/ipv4/tcp.c:tcp_md5_hash_skb_data
  - net/ipv4/tcp.c:tcp_md5_hash_skb_data
  - net/ipv4/tcp.c:tcp_md5_hash_skb_data
  - net/ipv4/tcp.c:tcp_md5_hash_skb_data
```
```
In net/ipv4/tcp_ipv4.c (ffffffff8193cf76)
Location: include/crypto/hash.h:379
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_md5_hash_skb
  - net/ipv4/tcp_ipv4.c:tcp_v4_md5_hash_hdr
```
```
In net/ipv6/tcp_ipv6.c (ffffffff819c8d77)
Location: include/crypto/hash.h:379
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_response
  - net/ipv6/tcp_ipv6.c:tcp_v6_md5_hash_skb
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
In security/integrity/ima/ima_crypto.c (ffffffff8149dafe)
Location: include/crypto/hash.h:378
Inline: True
Inline callers:
  - security/integrity/ima/ima_crypto.c:ima_calc_buffer_hash
  - security/integrity/ima/ima_crypto.c:ima_calc_buffer_hash
  - security/integrity/ima/ima_crypto.c:ima_calc_buffer_hash
  - security/integrity/ima/ima_crypto.c:ima_calc_file_hash_atfm
  - security/integrity/ima/ima_crypto.c:ima_calc_file_hash_atfm
  - security/integrity/ima/ima_crypto.c:ima_calc_file_hash_atfm
```
```
In crypto/ahash.c (ffffffff814ab145)
Location: include/crypto/hash.h:378
Inline: True
Inline callers:
  - crypto/ahash.c:ahash_def_finup
  - crypto/ahash.c:ahash_def_finup_finish1
  - crypto/ahash.c:crypto_ahash_digest
  - crypto/ahash.c:crypto_ahash_finup
  - crypto/ahash.c:crypto_ahash_finup
  - crypto/ahash.c:crypto_ahash_final
  - crypto/ahash.c:crypto_ahash_final
  - crypto/ahash.c:crypto_ahash_op
  - crypto/ahash.c:ahash_restore_req
  - crypto/ahash.c:ahash_save_req
```
```
In crypto/shash.c (ffffffff814ab215)
Location: include/crypto/hash.h:378
Inline: True
Inline callers:
  - crypto/shash.c:shash_async_import
  - crypto/shash.c:shash_async_digest
  - crypto/shash.c:shash_async_finup
  - crypto/shash.c:shash_async_init
```
```
In crypto/gcm.c (ffffffff814b6bfd)
Location: include/crypto/hash.h:378
Inline: True
Inline callers:
  - crypto/gcm.c:gcm_hash
  - crypto/gcm.c:gcm_hash_update
  - crypto/gcm.c:gcm_hash_update
```
```
In lib/iov_iter.c (ffffffff81509b0f)
Location: include/crypto/hash.h:378
Inline: True
Inline callers:
  - lib/iov_iter.c:hash_and_copy_to_iter
  - lib/iov_iter.c:hash_and_copy_to_iter
```
```
In net/ipv4/tcp.c (ffffffff819878a8)
Location: include/crypto/hash.h:378
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_md5_hash_key
  - net/ipv4/tcp.c:tcp_md5_hash_key
  - net/ipv4/tcp.c:tcp_md5_hash_skb_data
  - net/ipv4/tcp.c:tcp_md5_hash_skb_data
  - net/ipv4/tcp.c:tcp_md5_hash_skb_data
  - net/ipv4/tcp.c:tcp_md5_hash_skb_data
```
```
In net/ipv4/tcp_ipv4.c (ffffffff819a13c6)
Location: include/crypto/hash.h:378
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_md5_hash_skb
  - net/ipv4/tcp_ipv4.c:tcp_v4_md5_hash_hdr
```
```
In net/ipv6/tcp_ipv6.c (ffffffff81a3772b)
Location: include/crypto/hash.h:378
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_response
  - net/ipv6/tcp_ipv6.c:tcp_v6_md5_hash_skb
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
In fs/verity/hash_algs.c (ffffffff813503f5)
Location: include/crypto/hash.h:378
Inline: True
Inline callers:
  - fs/verity/hash_algs.c:fsverity_hash_page
  - fs/verity/hash_algs.c:fsverity_prepare_hash_state
  - fs/verity/hash_algs.c:fsverity_prepare_hash_state
  - fs/verity/hash_algs.c:fsverity_prepare_hash_state
  - fs/verity/hash_algs.c:fsverity_prepare_hash_state
```
```
In security/integrity/ima/ima_crypto.c (ffffffff814b7f3e)
Location: include/crypto/hash.h:378
Inline: True
Inline callers:
  - security/integrity/ima/ima_crypto.c:ima_calc_buffer_hash
  - security/integrity/ima/ima_crypto.c:ima_calc_buffer_hash
  - security/integrity/ima/ima_crypto.c:ima_calc_buffer_hash
  - security/integrity/ima/ima_crypto.c:ima_calc_file_hash_atfm
  - security/integrity/ima/ima_crypto.c:ima_calc_file_hash_atfm
  - security/integrity/ima/ima_crypto.c:ima_calc_file_hash_atfm
```
```
In crypto/ahash.c (ffffffff814c5e05)
Location: include/crypto/hash.h:378
Inline: True
Inline callers:
  - crypto/ahash.c:ahash_def_finup
  - crypto/ahash.c:ahash_def_finup_finish1
  - crypto/ahash.c:crypto_ahash_digest
  - crypto/ahash.c:crypto_ahash_finup
  - crypto/ahash.c:crypto_ahash_finup
  - crypto/ahash.c:crypto_ahash_final
  - crypto/ahash.c:crypto_ahash_final
  - crypto/ahash.c:crypto_ahash_op
  - crypto/ahash.c:ahash_restore_req
  - crypto/ahash.c:ahash_save_req
```
```
In crypto/shash.c (ffffffff814c5ed5)
Location: include/crypto/hash.h:378
Inline: True
Inline callers:
  - crypto/shash.c:shash_async_import
  - crypto/shash.c:shash_async_digest
  - crypto/shash.c:shash_async_finup
  - crypto/shash.c:shash_async_init
```
```
In crypto/gcm.c (ffffffff814cfe1d)
Location: include/crypto/hash.h:378
Inline: True
Inline callers:
  - crypto/gcm.c:gcm_hash
  - crypto/gcm.c:gcm_hash_update
  - crypto/gcm.c:gcm_hash_update
```
```
In lib/iov_iter.c (ffffffff81526f51)
Location: include/crypto/hash.h:378
Inline: True
Inline callers:
  - lib/iov_iter.c:hash_and_copy_to_iter
  - lib/iov_iter.c:hash_and_copy_to_iter
```
```
In net/ipv4/tcp.c (ffffffff819be078)
Location: include/crypto/hash.h:378
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_md5_hash_key
  - net/ipv4/tcp.c:tcp_md5_hash_key
  - net/ipv4/tcp.c:tcp_md5_hash_skb_data
  - net/ipv4/tcp.c:tcp_md5_hash_skb_data
  - net/ipv4/tcp.c:tcp_md5_hash_skb_data
  - net/ipv4/tcp.c:tcp_md5_hash_skb_data
```
```
In net/ipv4/tcp_ipv4.c (ffffffff819d8076)
Location: include/crypto/hash.h:378
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_md5_hash_skb
  - net/ipv4/tcp_ipv4.c:tcp_v4_md5_hash_hdr
```
```
In net/ipv6/tcp_ipv6.c (ffffffff81a6e255)
Location: include/crypto/hash.h:378
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_response
  - net/ipv6/tcp_ipv6.c:tcp_v6_md5_hash_skb
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
In fs/verity/hash_algs.c (ffffffff81396d95)
Location: include/crypto/hash.h:391
Inline: True
Inline callers:
  - fs/verity/hash_algs.c:fsverity_hash_page
  - fs/verity/hash_algs.c:fsverity_prepare_hash_state
  - fs/verity/hash_algs.c:fsverity_prepare_hash_state
  - fs/verity/hash_algs.c:fsverity_prepare_hash_state
  - fs/verity/hash_algs.c:fsverity_prepare_hash_state
```
```
In security/integrity/ima/ima_crypto.c (ffffffff81516f6d)
Location: include/crypto/hash.h:391
Inline: True
Inline callers:
  - security/integrity/ima/ima_crypto.c:calc_buffer_ahash_atfm
  - security/integrity/ima/ima_crypto.c:calc_buffer_ahash_atfm
  - security/integrity/ima/ima_crypto.c:calc_buffer_ahash_atfm
  - security/integrity/ima/ima_crypto.c:ima_calc_file_hash_atfm
  - security/integrity/ima/ima_crypto.c:ima_calc_file_hash_atfm
  - security/integrity/ima/ima_crypto.c:ima_calc_file_hash_atfm
```
```
In crypto/ahash.c (ffffffff815245d5)
Location: include/crypto/hash.h:391
Inline: True
Inline callers:
  - crypto/ahash.c:ahash_def_finup
  - crypto/ahash.c:ahash_def_finup
  - crypto/ahash.c:ahash_def_finup_done1
  - crypto/ahash.c:crypto_ahash_digest
  - crypto/ahash.c:crypto_ahash_finup
  - crypto/ahash.c:crypto_ahash_finup
  - crypto/ahash.c:crypto_ahash_final
  - crypto/ahash.c:crypto_ahash_final
  - crypto/ahash.c:crypto_ahash_op
  - crypto/ahash.c:ahash_restore_req
  - crypto/ahash.c:ahash_save_req
```
```
In crypto/shash.c (ffffffff81524dd5)
Location: include/crypto/hash.h:391
Inline: True
Inline callers:
  - crypto/shash.c:shash_async_import
  - crypto/shash.c:shash_async_digest
  - crypto/shash.c:shash_async_finup
  - crypto/shash.c:shash_async_init
```
```
In crypto/gcm.c (ffffffff8152effd)
Location: include/crypto/hash.h:391
Inline: True
Inline callers:
  - crypto/gcm.c:gcm_hash
  - crypto/gcm.c:gcm_hash_update
  - crypto/gcm.c:gcm_hash_update
```
```
In lib/iov_iter.c (ffffffff8158bae1)
Location: include/crypto/hash.h:391
Inline: True
Inline callers:
  - lib/iov_iter.c:hash_and_copy_to_iter
  - lib/iov_iter.c:hash_and_copy_to_iter
```
```
In net/ipv4/tcp.c (ffffffff81aa9403)
Location: include/crypto/hash.h:391
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_md5_hash_key
  - net/ipv4/tcp.c:tcp_md5_hash_key
  - net/ipv4/tcp.c:tcp_md5_hash_skb_data
  - net/ipv4/tcp.c:tcp_md5_hash_skb_data
  - net/ipv4/tcp.c:tcp_md5_hash_skb_data
  - net/ipv4/tcp.c:tcp_md5_hash_skb_data
```
```
In net/ipv4/tcp_ipv4.c (ffffffff81ac4066)
Location: include/crypto/hash.h:391
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_md5_hash_skb
  - net/ipv4/tcp_ipv4.c:tcp_v4_md5_hash_headers
  - net/ipv4/tcp_ipv4.c:tcp_v4_md5_hash_headers
```
```
In net/ipv6/tcp_ipv6.c (ffffffff81b6747e)
Location: include/crypto/hash.h:391
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_md5_hash_skb
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
In fs/verity/hash_algs.c (ffffffff813a89c5)
Location: include/crypto/hash.h:399
Inline: True
Inline callers:
  - fs/verity/hash_algs.c:fsverity_hash_page
  - fs/verity/hash_algs.c:fsverity_prepare_hash_state
  - fs/verity/hash_algs.c:fsverity_prepare_hash_state
  - fs/verity/hash_algs.c:fsverity_prepare_hash_state
  - fs/verity/hash_algs.c:fsverity_prepare_hash_state
```
```
In security/integrity/ima/ima_crypto.c (ffffffff8153412d)
Location: include/crypto/hash.h:399
Inline: True
Inline callers:
  - security/integrity/ima/ima_crypto.c:calc_buffer_ahash_atfm
  - security/integrity/ima/ima_crypto.c:calc_buffer_ahash_atfm
  - security/integrity/ima/ima_crypto.c:calc_buffer_ahash_atfm
  - security/integrity/ima/ima_crypto.c:ima_calc_file_hash_atfm
  - security/integrity/ima/ima_crypto.c:ima_calc_file_hash_atfm
  - security/integrity/ima/ima_crypto.c:ima_calc_file_hash_atfm
```
```
In crypto/ahash.c (ffffffff815414a5)
Location: include/crypto/hash.h:399
Inline: True
Inline callers:
  - crypto/ahash.c:ahash_def_finup
  - crypto/ahash.c:ahash_def_finup
  - crypto/ahash.c:ahash_def_finup_done1
  - crypto/ahash.c:crypto_ahash_digest
  - crypto/ahash.c:crypto_ahash_finup
  - crypto/ahash.c:crypto_ahash_finup
  - crypto/ahash.c:crypto_ahash_final
  - crypto/ahash.c:crypto_ahash_final
  - crypto/ahash.c:crypto_ahash_op
  - crypto/ahash.c:ahash_restore_req
  - crypto/ahash.c:ahash_save_req
```
```
In crypto/shash.c (ffffffff81541ce5)
Location: include/crypto/hash.h:399
Inline: True
Inline callers:
  - crypto/shash.c:shash_async_import
  - crypto/shash.c:shash_async_digest
  - crypto/shash.c:shash_async_finup
  - crypto/shash.c:shash_async_init
```
```
In crypto/gcm.c (ffffffff8154bf7d)
Location: include/crypto/hash.h:399
Inline: True
Inline callers:
  - crypto/gcm.c:gcm_hash
  - crypto/gcm.c:gcm_hash_update
  - crypto/gcm.c:gcm_hash_update
```
```
In lib/iov_iter.c (ffffffff815a6ab1)
Location: include/crypto/hash.h:399
Inline: True
Inline callers:
  - lib/iov_iter.c:hash_and_copy_to_iter
  - lib/iov_iter.c:hash_and_copy_to_iter
```
```
In net/ipv4/tcp.c (ffffffff81ab3723)
Location: include/crypto/hash.h:399
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_md5_hash_key
  - net/ipv4/tcp.c:tcp_md5_hash_key
  - net/ipv4/tcp.c:tcp_md5_hash_skb_data
  - net/ipv4/tcp.c:tcp_md5_hash_skb_data
  - net/ipv4/tcp.c:tcp_md5_hash_skb_data
  - net/ipv4/tcp.c:tcp_md5_hash_skb_data
```
```
In net/ipv4/tcp_ipv4.c (ffffffff81acfaf6)
Location: include/crypto/hash.h:399
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_md5_hash_skb
  - net/ipv4/tcp_ipv4.c:tcp_v4_md5_hash_headers
  - net/ipv4/tcp_ipv4.c:tcp_v4_md5_hash_headers
```
```
In net/ipv6/tcp_ipv6.c (ffffffff81b75c7e)
Location: include/crypto/hash.h:399
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_md5_hash_skb
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
In fs/verity/hash_algs.c (ffffffff813afa35)
Location: include/crypto/hash.h:401
Inline: True
Inline callers:
  - fs/verity/hash_algs.c:fsverity_hash_page
  - fs/verity/hash_algs.c:fsverity_prepare_hash_state
  - fs/verity/hash_algs.c:fsverity_prepare_hash_state
  - fs/verity/hash_algs.c:fsverity_prepare_hash_state
  - fs/verity/hash_algs.c:fsverity_prepare_hash_state
```
```
In security/integrity/ima/ima_crypto.c (ffffffff8153d11a)
Location: include/crypto/hash.h:401
Inline: True
Inline callers:
  - security/integrity/ima/ima_crypto.c:ima_calc_buffer_hash
  - security/integrity/ima/ima_crypto.c:ima_calc_buffer_hash
  - security/integrity/ima/ima_crypto.c:ima_calc_buffer_hash
  - security/integrity/ima/ima_crypto.c:ima_calc_file_hash_atfm
  - security/integrity/ima/ima_crypto.c:ima_calc_file_hash_atfm
  - security/integrity/ima/ima_crypto.c:ima_calc_file_hash_atfm
```
```
In crypto/ahash.c (ffffffff81549ad5)
Location: include/crypto/hash.h:401
Inline: True
Inline callers:
  - crypto/ahash.c:ahash_def_finup
  - crypto/ahash.c:ahash_def_finup
  - crypto/ahash.c:ahash_def_finup_done1
  - crypto/ahash.c:crypto_ahash_digest
  - crypto/ahash.c:crypto_ahash_finup
  - crypto/ahash.c:crypto_ahash_finup
  - crypto/ahash.c:crypto_ahash_final
  - crypto/ahash.c:crypto_ahash_final
  - crypto/ahash.c:crypto_ahash_op
  - crypto/ahash.c:ahash_restore_req
  - crypto/ahash.c:ahash_save_req
```
```
In crypto/shash.c (ffffffff8154a385)
Location: include/crypto/hash.h:401
Inline: True
Inline callers:
  - crypto/shash.c:shash_async_import
  - crypto/shash.c:shash_async_digest
  - crypto/shash.c:shash_async_finup
  - crypto/shash.c:shash_async_init
```
```
In crypto/gcm.c (ffffffff8155456d)
Location: include/crypto/hash.h:401
Inline: True
Inline callers:
  - crypto/gcm.c:gcm_hash
  - crypto/gcm.c:gcm_hash_update
  - crypto/gcm.c:gcm_hash_update
```
```
In lib/iov_iter.c (ffffffff815b1871)
Location: include/crypto/hash.h:401
Inline: True
Inline callers:
  - lib/iov_iter.c:hash_and_copy_to_iter
  - lib/iov_iter.c:hash_and_copy_to_iter
```
```
In net/ipv4/tcp.c (ffffffff81a9e893)
Location: include/crypto/hash.h:401
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_md5_hash_key
  - net/ipv4/tcp.c:tcp_md5_hash_key
  - net/ipv4/tcp.c:tcp_md5_hash_skb_data
  - net/ipv4/tcp.c:tcp_md5_hash_skb_data
  - net/ipv4/tcp.c:tcp_md5_hash_skb_data
  - net/ipv4/tcp.c:tcp_md5_hash_skb_data
```
```
In net/ipv4/tcp_ipv4.c (ffffffff81abac46)
Location: include/crypto/hash.h:401
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_md5_hash_skb
  - net/ipv4/tcp_ipv4.c:tcp_v4_md5_hash_headers
  - net/ipv4/tcp_ipv4.c:tcp_v4_md5_hash_headers
```
```
In net/ipv6/tcp_ipv6.c (ffffffff81b650a6)
Location: include/crypto/hash.h:401
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_response
  - net/ipv6/tcp_ipv6.c:tcp_v6_md5_hash_skb
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
In fs/verity/hash_algs.c (ffffffff813ff625)
Location: include/crypto/hash.h:401
Inline: True
Inline callers:
  - fs/verity/hash_algs.c:fsverity_hash_page
  - fs/verity/hash_algs.c:fsverity_prepare_hash_state
  - fs/verity/hash_algs.c:fsverity_prepare_hash_state
  - fs/verity/hash_algs.c:fsverity_prepare_hash_state
  - fs/verity/hash_algs.c:fsverity_prepare_hash_state
```
```
In security/integrity/ima/ima_crypto.c (ffffffff8159bf9a)
Location: include/crypto/hash.h:401
Inline: True
Inline callers:
  - security/integrity/ima/ima_crypto.c:ima_calc_buffer_hash
  - security/integrity/ima/ima_crypto.c:ima_calc_buffer_hash
  - security/integrity/ima/ima_crypto.c:ima_calc_buffer_hash
  - security/integrity/ima/ima_crypto.c:ima_calc_file_hash_atfm
  - security/integrity/ima/ima_crypto.c:ima_calc_file_hash_atfm
  - security/integrity/ima/ima_crypto.c:ima_calc_file_hash_atfm
```
```
In crypto/ahash.c (ffffffff815aa2b5)
Location: include/crypto/hash.h:401
Inline: True
Inline callers:
  - crypto/ahash.c:ahash_def_finup
  - crypto/ahash.c:ahash_def_finup
  - crypto/ahash.c:ahash_def_finup_done1
  - crypto/ahash.c:crypto_ahash_digest
  - crypto/ahash.c:crypto_ahash_finup
  - crypto/ahash.c:crypto_ahash_finup
  - crypto/ahash.c:crypto_ahash_final
  - crypto/ahash.c:crypto_ahash_final
  - crypto/ahash.c:crypto_ahash_op
  - crypto/ahash.c:ahash_restore_req
  - crypto/ahash.c:ahash_save_req
```
```
In crypto/shash.c (ffffffff815aab65)
Location: include/crypto/hash.h:401
Inline: True
Inline callers:
  - crypto/shash.c:shash_async_import
  - crypto/shash.c:shash_async_digest
  - crypto/shash.c:shash_async_finup
  - crypto/shash.c:shash_async_init
```
```
In crypto/gcm.c (ffffffff815b559d)
Location: include/crypto/hash.h:401
Inline: True
Inline callers:
  - crypto/gcm.c:gcm_hash
  - crypto/gcm.c:gcm_hash_update
  - crypto/gcm.c:gcm_hash_update
```
```
In lib/iov_iter.c (ffffffff81619321)
Location: include/crypto/hash.h:401
Inline: True
Inline callers:
  - lib/iov_iter.c:hash_and_copy_to_iter
  - lib/iov_iter.c:hash_and_copy_to_iter
```
```
In net/ipv4/tcp.c (ffffffff81b5a353)
Location: include/crypto/hash.h:401
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_md5_hash_key
  - net/ipv4/tcp.c:tcp_md5_hash_key
  - net/ipv4/tcp.c:tcp_md5_hash_skb_data
  - net/ipv4/tcp.c:tcp_md5_hash_skb_data
  - net/ipv4/tcp.c:tcp_md5_hash_skb_data
  - net/ipv4/tcp.c:tcp_md5_hash_skb_data
```
```
In net/ipv4/tcp_ipv4.c (ffffffff81b77f96)
Location: include/crypto/hash.h:401
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_md5_hash_skb
  - net/ipv4/tcp_ipv4.c:tcp_v4_md5_hash_headers
  - net/ipv4/tcp_ipv4.c:tcp_v4_md5_hash_headers
```
```
In net/ipv6/tcp_ipv6.c (ffffffff81c2d2e6)
Location: include/crypto/hash.h:401
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_response
  - net/ipv6/tcp_ipv6.c:tcp_v6_md5_hash_skb
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
In fs/verity/hash_algs.c (ffffffff814733fd)
Location: include/crypto/hash.h:401
Inline: True
Inline callers:
  - fs/verity/hash_algs.c:fsverity_hash_buffer
  - fs/verity/hash_algs.c:fsverity_hash_page
  - fs/verity/hash_algs.c:fsverity_prepare_hash_state
  - fs/verity/hash_algs.c:fsverity_prepare_hash_state
  - fs/verity/hash_algs.c:fsverity_prepare_hash_state
  - fs/verity/hash_algs.c:fsverity_prepare_hash_state
  - fs/verity/hash_algs.c:fsverity_prepare_hash_state
```
```
In security/integrity/ima/ima_crypto.c (ffffffff81640f74)
Location: include/crypto/hash.h:401
Inline: True
Inline callers:
  - security/integrity/ima/ima_crypto.c:ima_calc_buffer_hash
  - security/integrity/ima/ima_crypto.c:ima_calc_buffer_hash
  - security/integrity/ima/ima_crypto.c:ima_calc_buffer_hash
  - security/integrity/ima/ima_crypto.c:ima_calc_file_hash_atfm
  - security/integrity/ima/ima_crypto.c:ima_calc_file_hash_atfm
  - security/integrity/ima/ima_crypto.c:ima_calc_file_hash_atfm
```
```
In crypto/ahash.c (ffffffff81651715)
Location: include/crypto/hash.h:401
Inline: True
Inline callers:
  - crypto/ahash.c:ahash_def_finup
  - crypto/ahash.c:ahash_def_finup
  - crypto/ahash.c:ahash_def_finup_done1
  - crypto/ahash.c:crypto_ahash_digest
  - crypto/ahash.c:crypto_ahash_finup
  - crypto/ahash.c:crypto_ahash_finup
  - crypto/ahash.c:crypto_ahash_final
  - crypto/ahash.c:crypto_ahash_final
  - crypto/ahash.c:crypto_ahash_op
  - crypto/ahash.c:ahash_restore_req
  - crypto/ahash.c:ahash_save_req
```
```
In crypto/shash.c (ffffffff81652215)
Location: include/crypto/hash.h:401
Inline: True
Inline callers:
  - crypto/shash.c:shash_async_import
  - crypto/shash.c:shash_async_digest
  - crypto/shash.c:shash_async_finup
  - crypto/shash.c:shash_async_init
```
```
In crypto/gcm.c (ffffffff8165e294)
Location: include/crypto/hash.h:401
Inline: True
Inline callers:
  - crypto/gcm.c:gcm_hash_update
  - crypto/gcm.c:gcm_hash_update
```
```
In lib/iov_iter.c (ffffffff816e600d)
Location: include/crypto/hash.h:401
Inline: True
Inline callers:
  - lib/iov_iter.c:hash_and_copy_to_iter
  - lib/iov_iter.c:hash_and_copy_to_iter
```
```
In net/ipv4/tcp.c (ffffffff81ce8e52)
Location: include/crypto/hash.h:401
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_md5_hash_key
  - net/ipv4/tcp.c:tcp_md5_hash_key
  - net/ipv4/tcp.c:tcp_md5_hash_skb_data
  - net/ipv4/tcp.c:tcp_md5_hash_skb_data
  - net/ipv4/tcp.c:tcp_md5_hash_skb_data
  - net/ipv4/tcp.c:tcp_md5_hash_skb_data
```
```
In net/ipv4/tcp_ipv4.c (ffffffff81d07bb7)
Location: include/crypto/hash.h:401
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_md5_hash_skb
  - net/ipv4/tcp_ipv4.c:tcp_v4_md5_hash_headers
  - net/ipv4/tcp_ipv4.c:tcp_v4_md5_hash_headers
```
```
In net/ipv6/tcp_ipv6.c (ffffffff81dca6fc)
Location: include/crypto/hash.h:401
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_response
  - net/ipv6/tcp_ipv6.c:tcp_v6_md5_hash_skb
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
In fs/verity/hash_algs.c (ffffffff8150528d)
Location: include/crypto/hash.h:401
Inline: True
Inline callers:
  - fs/verity/hash_algs.c:fsverity_hash_buffer
  - fs/verity/hash_algs.c:fsverity_hash_page
  - fs/verity/hash_algs.c:fsverity_prepare_hash_state
  - fs/verity/hash_algs.c:fsverity_prepare_hash_state
  - fs/verity/hash_algs.c:fsverity_prepare_hash_state
  - fs/verity/hash_algs.c:fsverity_prepare_hash_state
  - fs/verity/hash_algs.c:fsverity_prepare_hash_state
```
```
In security/integrity/ima/ima_crypto.c (ffffffff816f8ee4)
Location: include/crypto/hash.h:401
Inline: True
Inline callers:
  - security/integrity/ima/ima_crypto.c:ima_calc_buffer_hash
  - security/integrity/ima/ima_crypto.c:ima_calc_buffer_hash
  - security/integrity/ima/ima_crypto.c:ima_calc_buffer_hash
  - security/integrity/ima/ima_crypto.c:ima_calc_file_hash_atfm
  - security/integrity/ima/ima_crypto.c:ima_calc_file_hash_atfm
  - security/integrity/ima/ima_crypto.c:ima_calc_file_hash_atfm
```
```
In crypto/ahash.c (ffffffff8170b565)
Location: include/crypto/hash.h:401
Inline: True
Inline callers:
  - crypto/ahash.c:ahash_def_finup
  - crypto/ahash.c:ahash_def_finup
  - crypto/ahash.c:ahash_def_finup_done1
  - crypto/ahash.c:crypto_ahash_digest
  - crypto/ahash.c:crypto_ahash_finup
  - crypto/ahash.c:crypto_ahash_finup
  - crypto/ahash.c:crypto_ahash_final
  - crypto/ahash.c:crypto_ahash_final
  - crypto/ahash.c:crypto_ahash_op
  - crypto/ahash.c:ahash_restore_req
  - crypto/ahash.c:ahash_save_req
```
```
In crypto/shash.c (ffffffff8170bca5)
Location: include/crypto/hash.h:401
Inline: True
Inline callers:
  - crypto/shash.c:shash_async_import
  - crypto/shash.c:shash_async_digest
  - crypto/shash.c:shash_async_finup
  - crypto/shash.c:shash_async_init
```
```
In crypto/gcm.c (ffffffff81717c34)
Location: include/crypto/hash.h:401
Inline: True
Inline callers:
  - crypto/gcm.c:gcm_hash_update
  - crypto/gcm.c:gcm_hash_update
```
```
In lib/iov_iter.c (ffffffff817d422d)
Location: include/crypto/hash.h:401
Inline: True
Inline callers:
  - lib/iov_iter.c:hash_and_copy_to_iter
  - lib/iov_iter.c:hash_and_copy_to_iter
```
```
In net/ipv4/tcp.c (ffffffff81eac3c2)
Location: include/crypto/hash.h:401
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_md5_hash_key
  - net/ipv4/tcp.c:tcp_md5_hash_key
  - net/ipv4/tcp.c:tcp_md5_hash_skb_data
  - net/ipv4/tcp.c:tcp_md5_hash_skb_data
  - net/ipv4/tcp.c:tcp_md5_hash_skb_data
  - net/ipv4/tcp.c:tcp_md5_hash_skb_data
```
```
In net/ipv4/tcp_ipv4.c (ffffffff81ecd517)
Location: include/crypto/hash.h:401
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_md5_hash_skb
  - net/ipv4/tcp_ipv4.c:tcp_v4_md5_hash_headers
  - net/ipv4/tcp_ipv4.c:tcp_v4_md5_hash_headers
```
```
In net/ipv6/tcp_ipv6.c (ffffffff81f9b736)
Location: include/crypto/hash.h:401
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_response
  - net/ipv6/tcp_ipv6.c:tcp_v6_md5_hash_skb
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
In security/integrity/ima/ima_crypto.c (ffffffff817330e8)
Location: include/crypto/hash.h:432
Inline: True
Inline callers:
  - security/integrity/ima/ima_crypto.c:ima_calc_buffer_hash
  - security/integrity/ima/ima_crypto.c:ima_calc_buffer_hash
  - security/integrity/ima/ima_crypto.c:ima_calc_file_hash_atfm
  - security/integrity/ima/ima_crypto.c:ima_calc_file_hash_atfm
```
```
In crypto/ahash.c (ffffffff81744f65)
Location: include/crypto/hash.h:432
Inline: True
Inline callers:
  - crypto/ahash.c:ahash_def_finup
  - crypto/ahash.c:ahash_def_finup
  - crypto/ahash.c:ahash_def_finup_done1
  - crypto/ahash.c:crypto_ahash_digest
  - crypto/ahash.c:crypto_ahash_finup
  - crypto/ahash.c:crypto_ahash_final
  - crypto/ahash.c:crypto_ahash_op
  - crypto/ahash.c:ahash_restore_req
  - crypto/ahash.c:ahash_save_req
  - crypto/ahash.c:ahash_save_req
  - crypto/ahash.c:ahash_save_req
```
```
In crypto/shash.c (ffffffff817457b5)
Location: include/crypto/hash.h:432
Inline: True
Inline callers:
  - crypto/shash.c:shash_async_import
  - crypto/shash.c:shash_async_digest
  - crypto/shash.c:shash_async_finup
  - crypto/shash.c:shash_async_init
```
```
In crypto/gcm.c (ffffffff8175309f)
Location: include/crypto/hash.h:432
Inline: True
Inline callers:
  - crypto/gcm.c:gcm_hash_update
```
```
In lib/iov_iter.c (ffffffff81811c27)
Location: include/crypto/hash.h:432
Inline: True
Inline callers:
  - lib/iov_iter.c:hash_and_copy_to_iter
```
```
In net/ipv4/tcp.c (ffffffff81f0ae72)
Location: include/crypto/hash.h:432
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_md5_hash_key
  - net/ipv4/tcp.c:tcp_md5_hash_skb_data
  - net/ipv4/tcp.c:tcp_md5_hash_skb_data
```
```
In net/ipv4/tcp_ipv4.c (ffffffff81f2c1d7)
Location: include/crypto/hash.h:432
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_md5_hash_skb
  - net/ipv4/tcp_ipv4.c:tcp_v4_md5_hash_headers
```
```
In net/ipv6/tcp_ipv6.c (ffffffff81ffae9e)
Location: include/crypto/hash.h:432
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_md5_hash_skb
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
In crypto/ahash.c (ffffffff81786e95)
Location: include/crypto/hash.h:413
Inline: True
Inline callers:
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
```
```
In net/ipv4/tcp_sigpool.c (ffffffff8204c5a5)
Location: include/crypto/hash.h:413
Inline: True
Inline callers:
  - net/ipv4/tcp_sigpool.c:tcp_sigpool_end
```
```
In net/ipv4/tcp_ao.c (ffffffff82056b02)
Location: include/crypto/hash.h:413
Inline: True
Inline callers:
  - net/ipv4/tcp_ao.c:tcp_ao_add_cmd
  - net/ipv4/tcp_ao.c:tcp_ao_parse_crypto
  - net/ipv4/tcp_ao.c:tcp_ao_hash_skb
  - net/ipv4/tcp_ao.c:tcp_ao_hash_hdr
  - net/ipv4/tcp_ao.c:tcp_ao_calc_traffic_key
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
In fs/verity/hash_algs.c (ffff800010412054)
Location: include/crypto/hash.h:378
Inline: True
Inline callers:
  - fs/verity/hash_algs.c:fsverity_hash_page
  - fs/verity/hash_algs.c:fsverity_prepare_hash_state
  - fs/verity/hash_algs.c:fsverity_prepare_hash_state
  - fs/verity/hash_algs.c:fsverity_prepare_hash_state
  - fs/verity/hash_algs.c:fsverity_prepare_hash_state
```
```
In security/integrity/ima/ima_crypto.c (ffff8000105b02f8)
Location: include/crypto/hash.h:378
Inline: True
Inline callers:
  - security/integrity/ima/ima_crypto.c:ima_calc_buffer_hash
  - security/integrity/ima/ima_crypto.c:ima_calc_buffer_hash
  - security/integrity/ima/ima_crypto.c:ima_calc_buffer_hash
  - security/integrity/ima/ima_crypto.c:ima_calc_file_hash_atfm
  - security/integrity/ima/ima_crypto.c:ima_calc_file_hash_atfm
  - security/integrity/ima/ima_crypto.c:ima_calc_file_hash_atfm
```
```
In crypto/ahash.c (ffff8000105c0c78)
Location: include/crypto/hash.h:378
Inline: True
Inline callers:
  - crypto/ahash.c:ahash_def_finup
  - crypto/ahash.c:ahash_def_finup_finish1
  - crypto/ahash.c:crypto_ahash_digest
  - crypto/ahash.c:crypto_ahash_finup
  - crypto/ahash.c:crypto_ahash_finup
  - crypto/ahash.c:crypto_ahash_final
  - crypto/ahash.c:crypto_ahash_final
  - crypto/ahash.c:crypto_ahash_op
  - crypto/ahash.c:ahash_restore_req
  - crypto/ahash.c:ahash_save_req
```
```
In crypto/shash.c (ffff8000105c0eb4)
Location: include/crypto/hash.h:378
Inline: True
Inline callers:
  - crypto/shash.c:shash_async_import
  - crypto/shash.c:shash_async_digest
  - crypto/shash.c:shash_async_finup
  - crypto/shash.c:shash_async_init
```
```
In crypto/gcm.c (ffff8000105ccc7c)
Location: include/crypto/hash.h:378
Inline: True
Inline callers:
  - crypto/gcm.c:gcm_hash
  - crypto/gcm.c:gcm_hash_update
  - crypto/gcm.c:gcm_hash_update
```
```
In lib/iov_iter.c (ffff8000106316b8)
Location: include/crypto/hash.h:378
Inline: True
Inline callers:
  - lib/iov_iter.c:hash_and_copy_to_iter
  - lib/iov_iter.c:hash_and_copy_to_iter
```
```
In net/ipv4/tcp.c (ffff800010c6fc80)
Location: include/crypto/hash.h:378
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_md5_hash_key
  - net/ipv4/tcp.c:tcp_md5_hash_key
  - net/ipv4/tcp.c:tcp_md5_hash_skb_data
  - net/ipv4/tcp.c:tcp_md5_hash_skb_data
  - net/ipv4/tcp.c:tcp_md5_hash_skb_data
  - net/ipv4/tcp.c:tcp_md5_hash_skb_data
```
```
In net/ipv4/tcp_ipv4.c (ffff800010c8ad6c)
Location: include/crypto/hash.h:378
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_md5_hash_skb
  - net/ipv4/tcp_ipv4.c:tcp_v4_md5_hash_hdr
```
```
In net/ipv6/tcp_ipv6.c (ffff800010d37c10)
Location: include/crypto/hash.h:378
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_response
  - net/ipv6/tcp_ipv6.c:tcp_v6_md5_hash_skb
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
In fs/verity/hash_algs.c (c05de6b4)
Location: include/crypto/hash.h:378
Inline: True
Inline callers:
  - fs/verity/hash_algs.c:fsverity_hash_page
  - fs/verity/hash_algs.c:fsverity_prepare_hash_state
  - fs/verity/hash_algs.c:fsverity_prepare_hash_state
  - fs/verity/hash_algs.c:fsverity_prepare_hash_state
  - fs/verity/hash_algs.c:fsverity_prepare_hash_state
```
```
In security/integrity/ima/ima_crypto.c (c075fa28)
Location: include/crypto/hash.h:378
Inline: True
Inline callers:
  - security/integrity/ima/ima_crypto.c:ima_calc_buffer_hash
  - security/integrity/ima/ima_crypto.c:ima_calc_buffer_hash
  - security/integrity/ima/ima_crypto.c:ima_calc_buffer_hash
  - security/integrity/ima/ima_crypto.c:ima_calc_file_hash_atfm
  - security/integrity/ima/ima_crypto.c:ima_calc_file_hash_atfm
  - security/integrity/ima/ima_crypto.c:ima_calc_file_hash_atfm
```
```
In crypto/ahash.c (c076e6fc)
Location: include/crypto/hash.h:378
Inline: True
Inline callers:
  - crypto/ahash.c:ahash_def_finup
  - crypto/ahash.c:ahash_def_finup_finish1
  - crypto/ahash.c:crypto_ahash_digest
  - crypto/ahash.c:crypto_ahash_finup
  - crypto/ahash.c:crypto_ahash_finup
  - crypto/ahash.c:crypto_ahash_final
  - crypto/ahash.c:crypto_ahash_final
  - crypto/ahash.c:crypto_ahash_op
  - crypto/ahash.c:ahash_restore_req
  - crypto/ahash.c:ahash_save_req
```
```
In crypto/shash.c (c076e7ec)
Location: include/crypto/hash.h:378
Inline: True
Inline callers:
  - crypto/shash.c:shash_async_import
  - crypto/shash.c:shash_async_digest
  - crypto/shash.c:shash_async_finup
  - crypto/shash.c:shash_async_init
```
```
In crypto/gcm.c (c077a1ac)
Location: include/crypto/hash.h:378
Inline: True
Inline callers:
  - crypto/gcm.c:gcm_hash
  - crypto/gcm.c:gcm_hash_update
  - crypto/gcm.c:gcm_hash_update
```
```
In lib/iov_iter.c (c07d7a10)
Location: include/crypto/hash.h:378
Inline: True
Inline callers:
  - lib/iov_iter.c:hash_and_copy_to_iter
  - lib/iov_iter.c:hash_and_copy_to_iter
```
```
In net/ipv4/tcp.c (c0d7ede0)
Location: include/crypto/hash.h:378
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_md5_hash_key
  - net/ipv4/tcp.c:tcp_md5_hash_key
  - net/ipv4/tcp.c:tcp_md5_hash_skb_data
  - net/ipv4/tcp.c:tcp_md5_hash_skb_data
  - net/ipv4/tcp.c:tcp_md5_hash_skb_data
  - net/ipv4/tcp.c:tcp_md5_hash_skb_data
```
```
In net/ipv4/tcp_ipv4.c (c0d99644)
Location: include/crypto/hash.h:378
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_md5_hash_skb
  - net/ipv4/tcp_ipv4.c:tcp_v4_md5_hash_hdr
  - net/ipv4/tcp_ipv4.c:tcp_v4_md5_hash_headers
  - net/ipv4/tcp_ipv4.c:tcp_v4_md5_hash_headers
```
```
In net/ipv6/tcp_ipv6.c (c0e38824)
Location: include/crypto/hash.h:378
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_response
  - net/ipv6/tcp_ipv6.c:tcp_v6_md5_hash_skb
  - net/ipv6/tcp_ipv6.c:tcp_v6_md5_hash_headers
  - net/ipv6/tcp_ipv6.c:tcp_v6_md5_hash_headers
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
In fs/verity/hash_algs.c (c00000000051fd44)
Location: include/crypto/hash.h:378
Inline: True
Inline callers:
  - fs/verity/hash_algs.c:fsverity_hash_page
  - fs/verity/hash_algs.c:fsverity_prepare_hash_state
  - fs/verity/hash_algs.c:fsverity_prepare_hash_state
  - fs/verity/hash_algs.c:fsverity_prepare_hash_state
  - fs/verity/hash_algs.c:fsverity_prepare_hash_state
```
```
In security/integrity/ima/ima_crypto.c (c00000000072fdc0)
Location: include/crypto/hash.h:378
Inline: True
Inline callers:
  - security/integrity/ima/ima_crypto.c:ima_calc_buffer_hash
  - security/integrity/ima/ima_crypto.c:ima_calc_buffer_hash
  - security/integrity/ima/ima_crypto.c:ima_calc_buffer_hash
  - security/integrity/ima/ima_crypto.c:ima_calc_file_hash_atfm
  - security/integrity/ima/ima_crypto.c:ima_calc_file_hash_atfm
  - security/integrity/ima/ima_crypto.c:ima_calc_file_hash_atfm
```
```
In crypto/ahash.c (c000000000749094)
Location: include/crypto/hash.h:378
Inline: True
Inline callers:
  - crypto/ahash.c:ahash_def_finup
  - crypto/ahash.c:ahash_def_finup_finish1
  - crypto/ahash.c:crypto_ahash_digest
  - crypto/ahash.c:crypto_ahash_finup
  - crypto/ahash.c:crypto_ahash_finup
  - crypto/ahash.c:crypto_ahash_final
  - crypto/ahash.c:crypto_ahash_final
  - crypto/ahash.c:crypto_ahash_op
  - crypto/ahash.c:ahash_restore_req
  - crypto/ahash.c:ahash_save_req
```
```
In crypto/shash.c (c000000000749200)
Location: include/crypto/hash.h:378
Inline: True
Inline callers:
  - crypto/shash.c:shash_async_import
  - crypto/shash.c:shash_async_digest
  - crypto/shash.c:shash_async_finup
  - crypto/shash.c:shash_async_init
```
```
In crypto/gcm.c (c000000000757454)
Location: include/crypto/hash.h:378
Inline: True
Inline callers:
  - crypto/gcm.c:gcm_hash
  - crypto/gcm.c:gcm_hash_update
  - crypto/gcm.c:gcm_hash_update
```
```
In lib/iov_iter.c (c0000000007d5718)
Location: include/crypto/hash.h:378
Inline: True
Inline callers:
  - lib/iov_iter.c:hash_and_copy_to_iter
  - lib/iov_iter.c:hash_and_copy_to_iter
```
```
In net/ipv4/tcp.c (c000000000d76c34)
Location: include/crypto/hash.h:378
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_md5_hash_key
  - net/ipv4/tcp.c:tcp_md5_hash_key
  - net/ipv4/tcp.c:tcp_md5_hash_skb_data
  - net/ipv4/tcp.c:tcp_md5_hash_skb_data
  - net/ipv4/tcp.c:tcp_md5_hash_skb_data
  - net/ipv4/tcp.c:tcp_md5_hash_skb_data
```
```
In net/ipv4/tcp_ipv4.c (c000000000d9982c)
Location: include/crypto/hash.h:378
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_md5_hash_skb
  - net/ipv4/tcp_ipv4.c:tcp_v4_md5_hash_hdr
```
```
In net/ipv6/tcp_ipv6.c (c000000000e69130)
Location: include/crypto/hash.h:378
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_response
  - net/ipv6/tcp_ipv6.c:tcp_v6_md5_hash_skb
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
In fs/verity/hash_algs.c (ffffffe0002ba108)
Location: include/crypto/hash.h:378
Inline: True
Inline callers:
  - fs/verity/hash_algs.c:fsverity_hash_page
  - fs/verity/hash_algs.c:fsverity_prepare_hash_state
  - fs/verity/hash_algs.c:fsverity_prepare_hash_state
  - fs/verity/hash_algs.c:fsverity_prepare_hash_state
  - fs/verity/hash_algs.c:fsverity_prepare_hash_state
```
```
In security/integrity/ima/ima_crypto.c (ffffffe0003f7f8a)
Location: include/crypto/hash.h:378
Inline: True
Inline callers:
  - security/integrity/ima/ima_crypto.c:ima_calc_buffer_hash
  - security/integrity/ima/ima_crypto.c:ima_calc_buffer_hash
  - security/integrity/ima/ima_crypto.c:ima_calc_buffer_hash
  - security/integrity/ima/ima_crypto.c:ima_calc_file_hash_atfm
  - security/integrity/ima/ima_crypto.c:ima_calc_file_hash_atfm
  - security/integrity/ima/ima_crypto.c:ima_calc_file_hash_atfm
```
```
In crypto/ahash.c (ffffffe000405b06)
Location: include/crypto/hash.h:378
Inline: True
Inline callers:
  - crypto/ahash.c:ahash_def_finup
  - crypto/ahash.c:ahash_def_finup_finish1
  - crypto/ahash.c:crypto_ahash_digest
  - crypto/ahash.c:crypto_ahash_finup
  - crypto/ahash.c:crypto_ahash_finup
  - crypto/ahash.c:crypto_ahash_final
  - crypto/ahash.c:crypto_ahash_final
  - crypto/ahash.c:crypto_ahash_op
  - crypto/ahash.c:ahash_restore_req
  - crypto/ahash.c:ahash_save_req
```
```
In crypto/shash.c (ffffffe000405cca)
Location: include/crypto/hash.h:378
Inline: True
Inline callers:
  - crypto/shash.c:shash_async_import
  - crypto/shash.c:shash_async_digest
  - crypto/shash.c:shash_async_finup
  - crypto/shash.c:shash_async_init
```
```
In crypto/gcm.c (ffffffe000410b24)
Location: include/crypto/hash.h:378
Inline: True
Inline callers:
  - crypto/gcm.c:gcm_hash
  - crypto/gcm.c:gcm_hash_update
  - crypto/gcm.c:gcm_hash_update
```
```
In lib/iov_iter.c (ffffffe000460006)
Location: include/crypto/hash.h:378
Inline: True
Inline callers:
  - lib/iov_iter.c:hash_and_copy_to_iter
  - lib/iov_iter.c:hash_and_copy_to_iter
```
```
In net/ipv4/tcp.c (ffffffe0007d4f3e)
Location: include/crypto/hash.h:378
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_md5_hash_key
  - net/ipv4/tcp.c:tcp_md5_hash_key
  - net/ipv4/tcp.c:tcp_md5_hash_skb_data
  - net/ipv4/tcp.c:tcp_md5_hash_skb_data
  - net/ipv4/tcp.c:tcp_md5_hash_skb_data
  - net/ipv4/tcp.c:tcp_md5_hash_skb_data
```
```
In net/ipv4/tcp_ipv4.c (ffffffe0007ec28a)
Location: include/crypto/hash.h:378
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_md5_hash_skb
  - net/ipv4/tcp_ipv4.c:tcp_v4_md5_hash_hdr
```
```
In net/ipv6/tcp_ipv6.c (ffffffe000874044)
Location: include/crypto/hash.h:378
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_response
  - net/ipv6/tcp_ipv6.c:tcp_v6_md5_hash_skb
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
In fs/verity/hash_algs.c (ffffffff813489d5)
Location: include/crypto/hash.h:378
Inline: True
Inline callers:
  - fs/verity/hash_algs.c:fsverity_hash_page
  - fs/verity/hash_algs.c:fsverity_prepare_hash_state
  - fs/verity/hash_algs.c:fsverity_prepare_hash_state
  - fs/verity/hash_algs.c:fsverity_prepare_hash_state
  - fs/verity/hash_algs.c:fsverity_prepare_hash_state
```
```
In security/integrity/ima/ima_crypto.c (ffffffff814b051e)
Location: include/crypto/hash.h:378
Inline: True
Inline callers:
  - security/integrity/ima/ima_crypto.c:ima_calc_buffer_hash
  - security/integrity/ima/ima_crypto.c:ima_calc_buffer_hash
  - security/integrity/ima/ima_crypto.c:ima_calc_buffer_hash
  - security/integrity/ima/ima_crypto.c:ima_calc_file_hash_atfm
  - security/integrity/ima/ima_crypto.c:ima_calc_file_hash_atfm
  - security/integrity/ima/ima_crypto.c:ima_calc_file_hash_atfm
```
```
In crypto/ahash.c (ffffffff814be3e5)
Location: include/crypto/hash.h:378
Inline: True
Inline callers:
  - crypto/ahash.c:ahash_def_finup
  - crypto/ahash.c:ahash_def_finup_finish1
  - crypto/ahash.c:crypto_ahash_digest
  - crypto/ahash.c:crypto_ahash_finup
  - crypto/ahash.c:crypto_ahash_finup
  - crypto/ahash.c:crypto_ahash_final
  - crypto/ahash.c:crypto_ahash_final
  - crypto/ahash.c:crypto_ahash_op
  - crypto/ahash.c:ahash_restore_req
  - crypto/ahash.c:ahash_save_req
```
```
In crypto/shash.c (ffffffff814be4b5)
Location: include/crypto/hash.h:378
Inline: True
Inline callers:
  - crypto/shash.c:shash_async_import
  - crypto/shash.c:shash_async_digest
  - crypto/shash.c:shash_async_finup
  - crypto/shash.c:shash_async_init
```
```
In crypto/gcm.c (ffffffff814c83fd)
Location: include/crypto/hash.h:378
Inline: True
Inline callers:
  - crypto/gcm.c:gcm_hash
  - crypto/gcm.c:gcm_hash_update
  - crypto/gcm.c:gcm_hash_update
```
```
In lib/iov_iter.c (ffffffff8151f531)
Location: include/crypto/hash.h:378
Inline: True
Inline callers:
  - lib/iov_iter.c:hash_and_copy_to_iter
  - lib/iov_iter.c:hash_and_copy_to_iter
```
```
In net/ipv4/tcp.c (ffffffff8195dee8)
Location: include/crypto/hash.h:378
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_md5_hash_key
  - net/ipv4/tcp.c:tcp_md5_hash_key
  - net/ipv4/tcp.c:tcp_md5_hash_skb_data
  - net/ipv4/tcp.c:tcp_md5_hash_skb_data
  - net/ipv4/tcp.c:tcp_md5_hash_skb_data
  - net/ipv4/tcp.c:tcp_md5_hash_skb_data
```
```
In net/ipv4/tcp_ipv4.c (ffffffff81977ee6)
Location: include/crypto/hash.h:378
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_md5_hash_skb
  - net/ipv4/tcp_ipv4.c:tcp_v4_md5_hash_hdr
```
```
In net/ipv6/tcp_ipv6.c (ffffffff81a0d8e5)
Location: include/crypto/hash.h:378
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_response
  - net/ipv6/tcp_ipv6.c:tcp_v6_md5_hash_skb
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
In fs/verity/hash_algs.c (ffffffff813396b5)
Location: include/crypto/hash.h:378
Inline: True
Inline callers:
  - fs/verity/hash_algs.c:fsverity_hash_page
  - fs/verity/hash_algs.c:fsverity_prepare_hash_state
  - fs/verity/hash_algs.c:fsverity_prepare_hash_state
  - fs/verity/hash_algs.c:fsverity_prepare_hash_state
  - fs/verity/hash_algs.c:fsverity_prepare_hash_state
```
```
In security/integrity/ima/ima_crypto.c (ffffffff814a0f3e)
Location: include/crypto/hash.h:378
Inline: True
Inline callers:
  - security/integrity/ima/ima_crypto.c:ima_calc_buffer_hash
  - security/integrity/ima/ima_crypto.c:ima_calc_buffer_hash
  - security/integrity/ima/ima_crypto.c:ima_calc_buffer_hash
  - security/integrity/ima/ima_crypto.c:ima_calc_file_hash_atfm
  - security/integrity/ima/ima_crypto.c:ima_calc_file_hash_atfm
  - security/integrity/ima/ima_crypto.c:ima_calc_file_hash_atfm
```
```
In crypto/ahash.c (ffffffff814aee05)
Location: include/crypto/hash.h:378
Inline: True
Inline callers:
  - crypto/ahash.c:ahash_def_finup
  - crypto/ahash.c:ahash_def_finup_finish1
  - crypto/ahash.c:crypto_ahash_digest
  - crypto/ahash.c:crypto_ahash_finup
  - crypto/ahash.c:crypto_ahash_finup
  - crypto/ahash.c:crypto_ahash_final
  - crypto/ahash.c:crypto_ahash_final
  - crypto/ahash.c:crypto_ahash_op
  - crypto/ahash.c:ahash_restore_req
  - crypto/ahash.c:ahash_save_req
```
```
In crypto/shash.c (ffffffff814aeed5)
Location: include/crypto/hash.h:378
Inline: True
Inline callers:
  - crypto/shash.c:shash_async_import
  - crypto/shash.c:shash_async_digest
  - crypto/shash.c:shash_async_finup
  - crypto/shash.c:shash_async_init
```
```
In crypto/gcm.c (ffffffff814b8e1d)
Location: include/crypto/hash.h:378
Inline: True
Inline callers:
  - crypto/gcm.c:gcm_hash
  - crypto/gcm.c:gcm_hash_update
  - crypto/gcm.c:gcm_hash_update
```
```
In lib/iov_iter.c (ffffffff8150f821)
Location: include/crypto/hash.h:378
Inline: True
Inline callers:
  - lib/iov_iter.c:hash_and_copy_to_iter
  - lib/iov_iter.c:hash_and_copy_to_iter
```
```
In net/ipv4/tcp.c (ffffffff819179d8)
Location: include/crypto/hash.h:378
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_md5_hash_key
  - net/ipv4/tcp.c:tcp_md5_hash_key
  - net/ipv4/tcp.c:tcp_md5_hash_skb_data
  - net/ipv4/tcp.c:tcp_md5_hash_skb_data
  - net/ipv4/tcp.c:tcp_md5_hash_skb_data
  - net/ipv4/tcp.c:tcp_md5_hash_skb_data
```
```
In net/ipv4/tcp_ipv4.c (ffffffff819319a6)
Location: include/crypto/hash.h:378
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_md5_hash_skb
  - net/ipv4/tcp_ipv4.c:tcp_v4_md5_hash_hdr
```
```
In net/ipv6/tcp_ipv6.c (ffffffff819ca6a5)
Location: include/crypto/hash.h:378
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_response
  - net/ipv6/tcp_ipv6.c:tcp_v6_md5_hash_skb
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
In fs/verity/hash_algs.c (ffffffff813464a5)
Location: include/crypto/hash.h:378
Inline: True
Inline callers:
  - fs/verity/hash_algs.c:fsverity_hash_page
  - fs/verity/hash_algs.c:fsverity_prepare_hash_state
  - fs/verity/hash_algs.c:fsverity_prepare_hash_state
  - fs/verity/hash_algs.c:fsverity_prepare_hash_state
  - fs/verity/hash_algs.c:fsverity_prepare_hash_state
```
```
In security/integrity/ima/ima_crypto.c (ffffffff814ac5ae)
Location: include/crypto/hash.h:378
Inline: True
Inline callers:
  - security/integrity/ima/ima_crypto.c:ima_calc_buffer_hash
  - security/integrity/ima/ima_crypto.c:ima_calc_buffer_hash
  - security/integrity/ima/ima_crypto.c:ima_calc_buffer_hash
  - security/integrity/ima/ima_crypto.c:ima_calc_file_hash_atfm
  - security/integrity/ima/ima_crypto.c:ima_calc_file_hash_atfm
  - security/integrity/ima/ima_crypto.c:ima_calc_file_hash_atfm
```
```
In crypto/ahash.c (ffffffff814ba475)
Location: include/crypto/hash.h:378
Inline: True
Inline callers:
  - crypto/ahash.c:ahash_def_finup
  - crypto/ahash.c:ahash_def_finup_finish1
  - crypto/ahash.c:crypto_ahash_digest
  - crypto/ahash.c:crypto_ahash_finup
  - crypto/ahash.c:crypto_ahash_finup
  - crypto/ahash.c:crypto_ahash_final
  - crypto/ahash.c:crypto_ahash_final
  - crypto/ahash.c:crypto_ahash_op
  - crypto/ahash.c:ahash_restore_req
  - crypto/ahash.c:ahash_save_req
```
```
In crypto/shash.c (ffffffff814ba545)
Location: include/crypto/hash.h:378
Inline: True
Inline callers:
  - crypto/shash.c:shash_async_import
  - crypto/shash.c:shash_async_digest
  - crypto/shash.c:shash_async_finup
  - crypto/shash.c:shash_async_init
```
```
In crypto/gcm.c (ffffffff814c448d)
Location: include/crypto/hash.h:378
Inline: True
Inline callers:
  - crypto/gcm.c:gcm_hash
  - crypto/gcm.c:gcm_hash_update
  - crypto/gcm.c:gcm_hash_update
```
```
In lib/iov_iter.c (ffffffff8151b5c1)
Location: include/crypto/hash.h:378
Inline: True
Inline callers:
  - lib/iov_iter.c:hash_and_copy_to_iter
  - lib/iov_iter.c:hash_and_copy_to_iter
```
```
In net/ipv4/tcp.c (ffffffff819c86b8)
Location: include/crypto/hash.h:378
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_md5_hash_key
  - net/ipv4/tcp.c:tcp_md5_hash_key
  - net/ipv4/tcp.c:tcp_md5_hash_skb_data
  - net/ipv4/tcp.c:tcp_md5_hash_skb_data
  - net/ipv4/tcp.c:tcp_md5_hash_skb_data
  - net/ipv4/tcp.c:tcp_md5_hash_skb_data
```
```
In net/ipv4/tcp_ipv4.c (ffffffff819e26b6)
Location: include/crypto/hash.h:378
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_md5_hash_skb
  - net/ipv4/tcp_ipv4.c:tcp_v4_md5_hash_hdr
```
```
In net/ipv6/tcp_ipv6.c (ffffffff81a78365)
Location: include/crypto/hash.h:378
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_response
  - net/ipv6/tcp_ipv6.c:tcp_v6_md5_hash_skb
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
In fs/verity/hash_algs.c (ffffffff81359785)
Location: include/crypto/hash.h:378
Inline: True
Inline callers:
  - fs/verity/hash_algs.c:fsverity_hash_page
  - fs/verity/hash_algs.c:fsverity_prepare_hash_state
  - fs/verity/hash_algs.c:fsverity_prepare_hash_state
  - fs/verity/hash_algs.c:fsverity_prepare_hash_state
  - fs/verity/hash_algs.c:fsverity_prepare_hash_state
```
```
In security/integrity/ima/ima_crypto.c (ffffffff814c4ffe)
Location: include/crypto/hash.h:378
Inline: True
Inline callers:
  - security/integrity/ima/ima_crypto.c:ima_calc_buffer_hash
  - security/integrity/ima/ima_crypto.c:ima_calc_buffer_hash
  - security/integrity/ima/ima_crypto.c:ima_calc_buffer_hash
  - security/integrity/ima/ima_crypto.c:ima_calc_file_hash_atfm
  - security/integrity/ima/ima_crypto.c:ima_calc_file_hash_atfm
  - security/integrity/ima/ima_crypto.c:ima_calc_file_hash_atfm
```
```
In crypto/ahash.c (ffffffff814d2f25)
Location: include/crypto/hash.h:378
Inline: True
Inline callers:
  - crypto/ahash.c:ahash_def_finup
  - crypto/ahash.c:ahash_def_finup_finish1
  - crypto/ahash.c:crypto_ahash_digest
  - crypto/ahash.c:crypto_ahash_finup
  - crypto/ahash.c:crypto_ahash_finup
  - crypto/ahash.c:crypto_ahash_final
  - crypto/ahash.c:crypto_ahash_final
  - crypto/ahash.c:crypto_ahash_op
  - crypto/ahash.c:ahash_restore_req
  - crypto/ahash.c:ahash_save_req
```
```
In crypto/shash.c (ffffffff814d2ff5)
Location: include/crypto/hash.h:378
Inline: True
Inline callers:
  - crypto/shash.c:shash_async_import
  - crypto/shash.c:shash_async_digest
  - crypto/shash.c:shash_async_finup
  - crypto/shash.c:shash_async_init
```
```
In crypto/gcm.c (ffffffff814dcf5d)
Location: include/crypto/hash.h:378
Inline: True
Inline callers:
  - crypto/gcm.c:gcm_hash
  - crypto/gcm.c:gcm_hash_update
  - crypto/gcm.c:gcm_hash_update
```
```
In lib/iov_iter.c (ffffffff81534e01)
Location: include/crypto/hash.h:378
Inline: True
Inline callers:
  - lib/iov_iter.c:hash_and_copy_to_iter
  - lib/iov_iter.c:hash_and_copy_to_iter
```
```
In net/ipv4/tcp.c (ffffffff819d2208)
Location: include/crypto/hash.h:378
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_md5_hash_key
  - net/ipv4/tcp.c:tcp_md5_hash_key
  - net/ipv4/tcp.c:tcp_md5_hash_skb_data
  - net/ipv4/tcp.c:tcp_md5_hash_skb_data
  - net/ipv4/tcp.c:tcp_md5_hash_skb_data
  - net/ipv4/tcp.c:tcp_md5_hash_skb_data
```
```
In net/ipv4/tcp_ipv4.c (ffffffff819ec406)
Location: include/crypto/hash.h:378
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_md5_hash_skb
  - net/ipv4/tcp_ipv4.c:tcp_v4_md5_hash_hdr
```
```
In net/ipv6/tcp_ipv6.c (ffffffff81a84ad5)
Location: include/crypto/hash.h:378
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_response
  - net/ipv6/tcp_ipv6.c:tcp_v6_md5_hash_skb
```
</details>
</li>
</ul>

## Differences
