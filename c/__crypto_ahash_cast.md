# Function: <code>__crypto_ahash_cast</code>

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
Location: include/crypto/hash.h:226
Inline: True
```
```
In crypto/ahash.c (0)
Location: include/crypto/hash.h:226
Inline: True
```
```
In crypto/shash.c (0)
Location: include/crypto/hash.h:226
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
Location: include/crypto/hash.h:227
Inline: True
```
```
In crypto/ahash.c (0)
Location: include/crypto/hash.h:227
Inline: True
```
```
In crypto/shash.c (0)
Location: include/crypto/hash.h:227
Inline: True
```
```
In net/ipv4/tcp.c (0)
Location: include/crypto/hash.h:227
Inline: True
```
```
In net/ipv4/tcp_ipv4.c (0)
Location: include/crypto/hash.h:227
Inline: True
```
```
In net/ipv6/tcp_ipv6.c (0)
Location: include/crypto/hash.h:227
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
Location: include/crypto/hash.h:227
Inline: True
```
```
In crypto/ahash.c (0)
Location: include/crypto/hash.h:227
Inline: True
```
```
In crypto/shash.c (0)
Location: include/crypto/hash.h:227
Inline: True
```
```
In arch/x86/power/hibernate_64.c (0)
Location: include/crypto/hash.h:227
Inline: True
```
```
In net/ipv4/tcp.c (0)
Location: include/crypto/hash.h:227
Inline: True
```
```
In net/ipv4/tcp_ipv4.c (0)
Location: include/crypto/hash.h:227
Inline: True
```
```
In net/ipv6/tcp_ipv6.c (0)
Location: include/crypto/hash.h:227
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
Location: include/crypto/hash.h:227
Inline: True
```
```
In crypto/ahash.c (0)
Location: include/crypto/hash.h:227
Inline: True
```
```
In crypto/shash.c (0)
Location: include/crypto/hash.h:227
Inline: True
```
```
In arch/x86/power/hibernate_64.c (0)
Location: include/crypto/hash.h:227
Inline: True
```
```
In net/ipv4/tcp.c (0)
Location: include/crypto/hash.h:227
Inline: True
```
```
In net/ipv4/tcp_ipv4.c (0)
Location: include/crypto/hash.h:227
Inline: True
```
```
In net/ipv6/tcp_ipv6.c (0)
Location: include/crypto/hash.h:227
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
In security/integrity/ima/ima_crypto.c (0)
Location: include/crypto/hash.h:231
Inline: True
```
```
In crypto/ahash.c (0)
Location: include/crypto/hash.h:231
Inline: True
```
```
In crypto/shash.c (0)
Location: include/crypto/hash.h:231
Inline: True
```
```
In crypto/gcm.c (0)
Location: include/crypto/hash.h:231
Inline: True
```
```
In arch/x86/power/hibernate_64.c (0)
Location: include/crypto/hash.h:231
Inline: True
```
```
In net/ipv4/tcp.c (0)
Location: include/crypto/hash.h:231
Inline: True
```
```
In net/ipv4/tcp_ipv4.c (0)
Location: include/crypto/hash.h:231
Inline: True
```
```
In net/ipv6/tcp_ipv6.c (0)
Location: include/crypto/hash.h:231
Inline: True
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
Location: include/crypto/hash.h:230
Inline: True
Inline callers:
  - security/integrity/ima/ima_crypto.c:ima_calc_buffer_hash
  - security/integrity/ima/ima_crypto.c:ima_calc_buffer_hash
  - security/integrity/ima/ima_crypto.c:ima_calc_file_hash
  - security/integrity/ima/ima_crypto.c:ima_calc_file_hash
```
```
In crypto/ahash.c (ffffffff8145f0d5)
Location: include/crypto/hash.h:230
Inline: True
Inline callers:
  - crypto/ahash.c:crypto_ahash_init_tfm
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
In crypto/shash.c (ffffffff81460077)
Location: include/crypto/hash.h:230
Inline: True
Inline callers:
  - crypto/shash.c:crypto_init_shash_ops_async
  - crypto/shash.c:shash_async_import
  - crypto/shash.c:shash_async_digest
  - crypto/shash.c:shash_async_finup
  - crypto/shash.c:shash_async_init
```
```
In crypto/gcm.c (ffffffff8146b9f2)
Location: include/crypto/hash.h:230
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
Location: include/crypto/hash.h:230
Inline: True
Inline callers:
  - arch/x86/power/hibernate_64.c:get_e820_md5
```
```
In net/ipv4/tcp.c (ffffffff818f6556)
Location: include/crypto/hash.h:230
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_md5_hash_key
  - net/ipv4/tcp.c:tcp_md5_hash_skb_data
  - net/ipv4/tcp.c:tcp_md5_hash_skb_data
```
```
In net/ipv4/tcp_ipv4.c (ffffffff8190eb4a)
Location: include/crypto/hash.h:230
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_md5_hash_skb
  - net/ipv4/tcp_ipv4.c:tcp_v4_md5_hash_hdr
```
```
In net/ipv6/tcp_ipv6.c (ffffffff8199263e)
Location: include/crypto/hash.h:230
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
Location: include/crypto/hash.h:234
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
In crypto/ahash.c (ffffffff8147cab5)
Location: include/crypto/hash.h:234
Inline: True
Inline callers:
  - crypto/ahash.c:crypto_ahash_init_tfm
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
In crypto/shash.c (ffffffff8147dad7)
Location: include/crypto/hash.h:234
Inline: True
Inline callers:
  - crypto/shash.c:crypto_init_shash_ops_async
  - crypto/shash.c:shash_async_import
  - crypto/shash.c:shash_async_digest
  - crypto/shash.c:shash_async_finup
  - crypto/shash.c:shash_async_init
```
```
In crypto/gcm.c (ffffffff81488f52)
Location: include/crypto/hash.h:234
Inline: True
Inline callers:
  - crypto/gcm.c:gcm_hash
  - crypto/gcm.c:gcm_hash_update
  - crypto/gcm.c:gcm_hash_update
```
```
In lib/iov_iter.c (ffffffff814dd3da)
Location: include/crypto/hash.h:234
Inline: True
Inline callers:
  - lib/iov_iter.c:hash_and_copy_to_iter
  - lib/iov_iter.c:hash_and_copy_to_iter
```
```
In net/ipv4/tcp.c (ffffffff81926a16)
Location: include/crypto/hash.h:234
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
In net/ipv4/tcp_ipv4.c (ffffffff8193cf7a)
Location: include/crypto/hash.h:234
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_md5_hash_skb
  - net/ipv4/tcp_ipv4.c:tcp_v4_md5_hash_hdr
```
```
In net/ipv6/tcp_ipv6.c (ffffffff819c8d7e)
Location: include/crypto/hash.h:234
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
Location: include/crypto/hash.h:233
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
In crypto/ahash.c (ffffffff814aaa65)
Location: include/crypto/hash.h:233
Inline: True
Inline callers:
  - crypto/ahash.c:crypto_ahash_init_tfm
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
In crypto/shash.c (ffffffff814abd72)
Location: include/crypto/hash.h:233
Inline: True
Inline callers:
  - crypto/shash.c:crypto_init_shash_ops_async
  - crypto/shash.c:shash_async_import
  - crypto/shash.c:shash_async_digest
  - crypto/shash.c:shash_async_finup
  - crypto/shash.c:shash_async_init
```
```
In crypto/gcm.c (ffffffff814b6bfd)
Location: include/crypto/hash.h:233
Inline: True
Inline callers:
  - crypto/gcm.c:gcm_hash
  - crypto/gcm.c:gcm_hash_update
  - crypto/gcm.c:gcm_hash_update
```
```
In lib/iov_iter.c (ffffffff81509b0f)
Location: include/crypto/hash.h:233
Inline: True
Inline callers:
  - lib/iov_iter.c:hash_and_copy_to_iter
  - lib/iov_iter.c:hash_and_copy_to_iter
```
```
In net/ipv4/tcp.c (ffffffff819878a8)
Location: include/crypto/hash.h:233
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
In net/ipv4/tcp_ipv4.c (ffffffff819a13ca)
Location: include/crypto/hash.h:233
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_md5_hash_skb
  - net/ipv4/tcp_ipv4.c:tcp_v4_md5_hash_hdr
```
```
In net/ipv6/tcp_ipv6.c (ffffffff81a3772f)
Location: include/crypto/hash.h:233
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
In fs/verity/hash_algs.c (ffffffff813503fa)
Location: include/crypto/hash.h:233
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
Location: include/crypto/hash.h:233
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
In crypto/ahash.c (ffffffff814c5725)
Location: include/crypto/hash.h:233
Inline: True
Inline callers:
  - crypto/ahash.c:crypto_ahash_init_tfm
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
In crypto/shash.c (ffffffff814c6a52)
Location: include/crypto/hash.h:233
Inline: True
Inline callers:
  - crypto/shash.c:crypto_init_shash_ops_async
  - crypto/shash.c:shash_async_import
  - crypto/shash.c:shash_async_digest
  - crypto/shash.c:shash_async_finup
  - crypto/shash.c:shash_async_init
```
```
In crypto/gcm.c (ffffffff814cfe1d)
Location: include/crypto/hash.h:233
Inline: True
Inline callers:
  - crypto/gcm.c:gcm_hash
  - crypto/gcm.c:gcm_hash_update
  - crypto/gcm.c:gcm_hash_update
```
```
In lib/iov_iter.c (ffffffff81526f51)
Location: include/crypto/hash.h:233
Inline: True
Inline callers:
  - lib/iov_iter.c:hash_and_copy_to_iter
  - lib/iov_iter.c:hash_and_copy_to_iter
```
```
In net/ipv4/tcp.c (ffffffff819be078)
Location: include/crypto/hash.h:233
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
In net/ipv4/tcp_ipv4.c (ffffffff819d807a)
Location: include/crypto/hash.h:233
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_md5_hash_skb
  - net/ipv4/tcp_ipv4.c:tcp_v4_md5_hash_hdr
```
```
In net/ipv6/tcp_ipv6.c (ffffffff81a6e259)
Location: include/crypto/hash.h:233
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
In fs/verity/hash_algs.c (ffffffff81396d9a)
Location: include/crypto/hash.h:246
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
Location: include/crypto/hash.h:246
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
In crypto/ahash.c (ffffffff81524ae5)
Location: include/crypto/hash.h:246
Inline: True
Inline callers:
  - crypto/ahash.c:crypto_ahash_init_tfm
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
In crypto/shash.c (ffffffff81525d02)
Location: include/crypto/hash.h:246
Inline: True
Inline callers:
  - crypto/shash.c:crypto_init_shash_ops_async
  - crypto/shash.c:shash_async_import
  - crypto/shash.c:shash_async_digest
  - crypto/shash.c:shash_async_finup
  - crypto/shash.c:shash_async_init
```
```
In crypto/gcm.c (ffffffff8152effd)
Location: include/crypto/hash.h:246
Inline: True
Inline callers:
  - crypto/gcm.c:gcm_hash
  - crypto/gcm.c:gcm_hash_update
  - crypto/gcm.c:gcm_hash_update
```
```
In lib/iov_iter.c (ffffffff8158bae1)
Location: include/crypto/hash.h:246
Inline: True
Inline callers:
  - lib/iov_iter.c:hash_and_copy_to_iter
  - lib/iov_iter.c:hash_and_copy_to_iter
```
```
In net/ipv4/tcp.c (ffffffff81aa9403)
Location: include/crypto/hash.h:246
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
In net/ipv4/tcp_ipv4.c (ffffffff81ac406a)
Location: include/crypto/hash.h:246
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_md5_hash_skb
  - net/ipv4/tcp_ipv4.c:tcp_v4_md5_hash_headers
  - net/ipv4/tcp_ipv4.c:tcp_v4_md5_hash_headers
```
```
In net/ipv6/tcp_ipv6.c (ffffffff81b67482)
Location: include/crypto/hash.h:246
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
In fs/verity/hash_algs.c (ffffffff813a89ca)
Location: include/crypto/hash.h:254
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
Location: include/crypto/hash.h:254
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
In crypto/ahash.c (ffffffff815419b5)
Location: include/crypto/hash.h:254
Inline: True
Inline callers:
  - crypto/ahash.c:crypto_ahash_init_tfm
  - crypto/ahash.c:crypto_ahash_exit_tfm
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
In crypto/shash.c (ffffffff81542c35)
Location: include/crypto/hash.h:254
Inline: True
Inline callers:
  - crypto/shash.c:crypto_init_shash_ops_async
  - crypto/shash.c:shash_async_import
  - crypto/shash.c:shash_async_digest
  - crypto/shash.c:shash_async_finup
  - crypto/shash.c:shash_async_init
```
```
In crypto/gcm.c (ffffffff8154bf7d)
Location: include/crypto/hash.h:254
Inline: True
Inline callers:
  - crypto/gcm.c:gcm_hash
  - crypto/gcm.c:gcm_hash_update
  - crypto/gcm.c:gcm_hash_update
```
```
In lib/iov_iter.c (ffffffff815a6ab1)
Location: include/crypto/hash.h:254
Inline: True
Inline callers:
  - lib/iov_iter.c:hash_and_copy_to_iter
  - lib/iov_iter.c:hash_and_copy_to_iter
```
```
In net/ipv4/tcp.c (ffffffff81ab3723)
Location: include/crypto/hash.h:254
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
In net/ipv4/tcp_ipv4.c (ffffffff81acfafa)
Location: include/crypto/hash.h:254
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_md5_hash_skb
  - net/ipv4/tcp_ipv4.c:tcp_v4_md5_hash_headers
  - net/ipv4/tcp_ipv4.c:tcp_v4_md5_hash_headers
```
```
In net/ipv6/tcp_ipv6.c (ffffffff81b75c82)
Location: include/crypto/hash.h:254
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
In fs/verity/hash_algs.c (ffffffff813afa3a)
Location: include/crypto/hash.h:254
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
Location: include/crypto/hash.h:254
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
In crypto/ahash.c (ffffffff8154a015)
Location: include/crypto/hash.h:254
Inline: True
Inline callers:
  - crypto/ahash.c:crypto_ahash_init_tfm
  - crypto/ahash.c:crypto_ahash_exit_tfm
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
In crypto/shash.c (ffffffff8154b2d5)
Location: include/crypto/hash.h:254
Inline: True
Inline callers:
  - crypto/shash.c:crypto_init_shash_ops_async
  - crypto/shash.c:shash_async_import
  - crypto/shash.c:shash_async_digest
  - crypto/shash.c:shash_async_finup
  - crypto/shash.c:shash_async_init
```
```
In crypto/gcm.c (ffffffff8155456d)
Location: include/crypto/hash.h:254
Inline: True
Inline callers:
  - crypto/gcm.c:gcm_hash
  - crypto/gcm.c:gcm_hash_update
  - crypto/gcm.c:gcm_hash_update
```
```
In lib/iov_iter.c (ffffffff815b1871)
Location: include/crypto/hash.h:254
Inline: True
Inline callers:
  - lib/iov_iter.c:hash_and_copy_to_iter
  - lib/iov_iter.c:hash_and_copy_to_iter
```
```
In net/ipv4/tcp.c (ffffffff81a9e893)
Location: include/crypto/hash.h:254
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
In net/ipv4/tcp_ipv4.c (ffffffff81abac4a)
Location: include/crypto/hash.h:254
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_md5_hash_skb
  - net/ipv4/tcp_ipv4.c:tcp_v4_md5_hash_headers
  - net/ipv4/tcp_ipv4.c:tcp_v4_md5_hash_headers
```
```
In net/ipv6/tcp_ipv6.c (ffffffff81b650aa)
Location: include/crypto/hash.h:254
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
In fs/verity/hash_algs.c (ffffffff813ff62a)
Location: include/crypto/hash.h:254
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
Location: include/crypto/hash.h:254
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
In crypto/ahash.c (ffffffff815aa7f5)
Location: include/crypto/hash.h:254
Inline: True
Inline callers:
  - crypto/ahash.c:crypto_ahash_init_tfm
  - crypto/ahash.c:crypto_ahash_exit_tfm
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
In crypto/shash.c (ffffffff815abab5)
Location: include/crypto/hash.h:254
Inline: True
Inline callers:
  - crypto/shash.c:crypto_init_shash_ops_async
  - crypto/shash.c:shash_async_import
  - crypto/shash.c:shash_async_digest
  - crypto/shash.c:shash_async_finup
  - crypto/shash.c:shash_async_init
```
```
In crypto/gcm.c (ffffffff815b559d)
Location: include/crypto/hash.h:254
Inline: True
Inline callers:
  - crypto/gcm.c:gcm_hash
  - crypto/gcm.c:gcm_hash_update
  - crypto/gcm.c:gcm_hash_update
```
```
In lib/iov_iter.c (ffffffff81619321)
Location: include/crypto/hash.h:254
Inline: True
Inline callers:
  - lib/iov_iter.c:hash_and_copy_to_iter
  - lib/iov_iter.c:hash_and_copy_to_iter
```
```
In net/ipv4/tcp.c (ffffffff81b5a353)
Location: include/crypto/hash.h:254
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
In net/ipv4/tcp_ipv4.c (ffffffff81b77f9a)
Location: include/crypto/hash.h:254
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_md5_hash_skb
  - net/ipv4/tcp_ipv4.c:tcp_v4_md5_hash_headers
  - net/ipv4/tcp_ipv4.c:tcp_v4_md5_hash_headers
```
```
In net/ipv6/tcp_ipv6.c (ffffffff81c2d2ea)
Location: include/crypto/hash.h:254
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
In fs/verity/hash_algs.c (0)
Location: include/crypto/hash.h:254
Inline: True
```
```
In security/integrity/ima/ima_crypto.c (0)
Location: include/crypto/hash.h:254
Inline: True
```
```
In crypto/ahash.c (ffffffff81651e65)
Location: include/crypto/hash.h:254
Inline: True
Inline callers:
  - crypto/ahash.c:crypto_ahash_init_tfm
  - crypto/ahash.c:crypto_ahash_exit_tfm
```
```
In crypto/shash.c (0)
Location: include/crypto/hash.h:254
Inline: True
```
```
In crypto/gcm.c (0)
Location: include/crypto/hash.h:254
Inline: True
```
```
In lib/iov_iter.c (0)
Location: include/crypto/hash.h:254
Inline: True
```
```
In net/ipv4/tcp.c (0)
Location: include/crypto/hash.h:254
Inline: True
```
```
In net/ipv4/tcp_ipv4.c (0)
Location: include/crypto/hash.h:254
Inline: True
```
```
In net/ipv6/tcp_ipv6.c (0)
Location: include/crypto/hash.h:254
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
Location: include/crypto/hash.h:254
Inline: True
```
```
In security/integrity/ima/ima_crypto.c (0)
Location: include/crypto/hash.h:254
Inline: True
```
```
In crypto/ahash.c (ffffffff8170b8b5)
Location: include/crypto/hash.h:254
Inline: True
Inline callers:
  - crypto/ahash.c:crypto_ahash_init_tfm
  - crypto/ahash.c:crypto_ahash_exit_tfm
```
```
In crypto/shash.c (0)
Location: include/crypto/hash.h:254
Inline: True
```
```
In crypto/gcm.c (0)
Location: include/crypto/hash.h:254
Inline: True
```
```
In lib/iov_iter.c (0)
Location: include/crypto/hash.h:254
Inline: True
```
```
In net/ipv4/tcp.c (0)
Location: include/crypto/hash.h:254
Inline: True
```
```
In net/ipv4/tcp_ipv4.c (0)
Location: include/crypto/hash.h:254
Inline: True
```
```
In net/ipv6/tcp_ipv6.c (0)
Location: include/crypto/hash.h:254
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
Location: include/crypto/hash.h:283
Inline: True
```
```
In crypto/ahash.c (ffffffff81745345)
Location: include/crypto/hash.h:283
Inline: True
Inline callers:
  - crypto/ahash.c:crypto_ahash_init_tfm
  - crypto/ahash.c:crypto_ahash_exit_tfm
```
```
In crypto/shash.c (0)
Location: include/crypto/hash.h:283
Inline: True
```
```
In crypto/gcm.c (0)
Location: include/crypto/hash.h:283
Inline: True
```
```
In lib/iov_iter.c (0)
Location: include/crypto/hash.h:283
Inline: True
```
```
In net/ipv4/tcp.c (0)
Location: include/crypto/hash.h:283
Inline: True
```
```
In net/ipv4/tcp_ipv4.c (0)
Location: include/crypto/hash.h:283
Inline: True
```
```
In net/ipv6/tcp_ipv6.c (0)
Location: include/crypto/hash.h:283
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
In crypto/ahash.c (ffffffff81787615)
Location: include/crypto/hash.h:270
Inline: True
Inline callers:
  - crypto/ahash.c:crypto_ahash_init_tfm
  - crypto/ahash.c:crypto_ahash_exit_tfm
```
```
In net/ipv4/tcp_sigpool.c (ffffffff8204c5c3)
Location: include/crypto/hash.h:270
Inline: True
Inline callers:
  - net/ipv4/tcp_sigpool.c:tcp_sigpool_end
```
```
In net/ipv4/tcp_ao.c (ffffffff82053fe1)
Location: include/crypto/hash.h:270
Inline: True
Inline callers:
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
In fs/verity/hash_algs.c (ffff800010412058)
Location: include/crypto/hash.h:233
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
Location: include/crypto/hash.h:233
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
In crypto/ahash.c (ffff8000105c0408)
Location: include/crypto/hash.h:233
Inline: True
Inline callers:
  - crypto/ahash.c:crypto_ahash_init_tfm
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
In crypto/shash.c (ffff8000105c1f18)
Location: include/crypto/hash.h:233
Inline: True
Inline callers:
  - crypto/shash.c:crypto_init_shash_ops_async
  - crypto/shash.c:shash_async_import
  - crypto/shash.c:shash_async_digest
  - crypto/shash.c:shash_async_finup
  - crypto/shash.c:shash_async_init
```
```
In crypto/gcm.c (ffff8000105ccc7c)
Location: include/crypto/hash.h:233
Inline: True
Inline callers:
  - crypto/gcm.c:gcm_hash
  - crypto/gcm.c:gcm_hash_update
  - crypto/gcm.c:gcm_hash_update
```
```
In lib/iov_iter.c (ffff8000106316b8)
Location: include/crypto/hash.h:233
Inline: True
Inline callers:
  - lib/iov_iter.c:hash_and_copy_to_iter
  - lib/iov_iter.c:hash_and_copy_to_iter
```
```
In net/ipv4/tcp.c (ffff800010c6fc80)
Location: include/crypto/hash.h:233
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
In net/ipv4/tcp_ipv4.c (ffff800010c8ad70)
Location: include/crypto/hash.h:233
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_md5_hash_skb
  - net/ipv4/tcp_ipv4.c:tcp_v4_md5_hash_hdr
```
```
In net/ipv6/tcp_ipv6.c (ffff800010d37c10)
Location: include/crypto/hash.h:233
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
In fs/verity/hash_algs.c (c05de6b8)
Location: include/crypto/hash.h:233
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
Location: include/crypto/hash.h:233
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
In crypto/ahash.c (c076df7c)
Location: include/crypto/hash.h:233
Inline: True
Inline callers:
  - crypto/ahash.c:crypto_ahash_init_tfm
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
In crypto/shash.c (c076f48c)
Location: include/crypto/hash.h:233
Inline: True
Inline callers:
  - crypto/shash.c:crypto_init_shash_ops_async
  - crypto/shash.c:shash_async_import
  - crypto/shash.c:shash_async_digest
  - crypto/shash.c:shash_async_finup
  - crypto/shash.c:shash_async_init
```
```
In crypto/gcm.c (c077a1ac)
Location: include/crypto/hash.h:233
Inline: True
Inline callers:
  - crypto/gcm.c:gcm_hash
  - crypto/gcm.c:gcm_hash_update
  - crypto/gcm.c:gcm_hash_update
```
```
In lib/iov_iter.c (c07d7a10)
Location: include/crypto/hash.h:233
Inline: True
Inline callers:
  - lib/iov_iter.c:hash_and_copy_to_iter
  - lib/iov_iter.c:hash_and_copy_to_iter
```
```
In net/ipv4/tcp.c (c0d7ede0)
Location: include/crypto/hash.h:233
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
In net/ipv4/tcp_ipv4.c (c0d99648)
Location: include/crypto/hash.h:233
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_md5_hash_skb
  - net/ipv4/tcp_ipv4.c:tcp_v4_md5_hash_hdr
  - net/ipv4/tcp_ipv4.c:tcp_v4_md5_hash_headers
  - net/ipv4/tcp_ipv4.c:tcp_v4_md5_hash_headers
```
```
In net/ipv6/tcp_ipv6.c (c0e38828)
Location: include/crypto/hash.h:233
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
In fs/verity/hash_algs.c (c00000000051fd48)
Location: include/crypto/hash.h:233
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
Location: include/crypto/hash.h:233
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
In crypto/ahash.c (c0000000007484c0)
Location: include/crypto/hash.h:233
Inline: True
Inline callers:
  - crypto/ahash.c:crypto_ahash_init_tfm
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
In crypto/shash.c (c00000000074a558)
Location: include/crypto/hash.h:233
Inline: True
Inline callers:
  - crypto/shash.c:crypto_init_shash_ops_async
  - crypto/shash.c:shash_async_import
  - crypto/shash.c:shash_async_digest
  - crypto/shash.c:shash_async_finup
  - crypto/shash.c:shash_async_init
```
```
In crypto/gcm.c (c000000000757454)
Location: include/crypto/hash.h:233
Inline: True
Inline callers:
  - crypto/gcm.c:gcm_hash
  - crypto/gcm.c:gcm_hash_update
  - crypto/gcm.c:gcm_hash_update
```
```
In lib/iov_iter.c (c0000000007d5718)
Location: include/crypto/hash.h:233
Inline: True
Inline callers:
  - lib/iov_iter.c:hash_and_copy_to_iter
  - lib/iov_iter.c:hash_and_copy_to_iter
```
```
In net/ipv4/tcp.c (c000000000d76c34)
Location: include/crypto/hash.h:233
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
In net/ipv4/tcp_ipv4.c (c000000000d99830)
Location: include/crypto/hash.h:233
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_md5_hash_skb
  - net/ipv4/tcp_ipv4.c:tcp_v4_md5_hash_hdr
```
```
In net/ipv6/tcp_ipv6.c (c000000000e69134)
Location: include/crypto/hash.h:233
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
In fs/verity/hash_algs.c (ffffffe0002ba10a)
Location: include/crypto/hash.h:233
Inline: True
Inline callers:
  - fs/verity/hash_algs.c:fsverity_hash_page
  - fs/verity/hash_algs.c:fsverity_prepare_hash_state
  - fs/verity/hash_algs.c:fsverity_prepare_hash_state
  - fs/verity/hash_algs.c:fsverity_prepare_hash_state
  - fs/verity/hash_algs.c:fsverity_prepare_hash_state
```
```
In security/integrity/ima/ima_crypto.c (ffffffe0003f7f9c)
Location: include/crypto/hash.h:233
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
In crypto/ahash.c (ffffffe00040537a)
Location: include/crypto/hash.h:233
Inline: True
Inline callers:
  - crypto/ahash.c:crypto_ahash_init_tfm
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
In crypto/shash.c (ffffffe000406a58)
Location: include/crypto/hash.h:233
Inline: True
Inline callers:
  - crypto/shash.c:crypto_init_shash_ops_async
  - crypto/shash.c:shash_async_import
  - crypto/shash.c:shash_async_digest
  - crypto/shash.c:shash_async_finup
  - crypto/shash.c:shash_async_init
```
```
In crypto/gcm.c (ffffffe000410b24)
Location: include/crypto/hash.h:233
Inline: True
Inline callers:
  - crypto/gcm.c:gcm_hash
  - crypto/gcm.c:gcm_hash_update
  - crypto/gcm.c:gcm_hash_update
```
```
In lib/iov_iter.c (ffffffe000460006)
Location: include/crypto/hash.h:233
Inline: True
Inline callers:
  - lib/iov_iter.c:hash_and_copy_to_iter
  - lib/iov_iter.c:hash_and_copy_to_iter
```
```
In net/ipv4/tcp.c (ffffffe0007d4f3e)
Location: include/crypto/hash.h:233
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
In net/ipv4/tcp_ipv4.c (ffffffe0007ec28e)
Location: include/crypto/hash.h:233
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_md5_hash_skb
  - net/ipv4/tcp_ipv4.c:tcp_v4_md5_hash_hdr
```
```
In net/ipv6/tcp_ipv6.c (ffffffe000874048)
Location: include/crypto/hash.h:233
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
In fs/verity/hash_algs.c (ffffffff813489da)
Location: include/crypto/hash.h:233
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
Location: include/crypto/hash.h:233
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
In crypto/ahash.c (ffffffff814bdd05)
Location: include/crypto/hash.h:233
Inline: True
Inline callers:
  - crypto/ahash.c:crypto_ahash_init_tfm
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
In crypto/shash.c (ffffffff814bf032)
Location: include/crypto/hash.h:233
Inline: True
Inline callers:
  - crypto/shash.c:crypto_init_shash_ops_async
  - crypto/shash.c:shash_async_import
  - crypto/shash.c:shash_async_digest
  - crypto/shash.c:shash_async_finup
  - crypto/shash.c:shash_async_init
```
```
In crypto/gcm.c (ffffffff814c83fd)
Location: include/crypto/hash.h:233
Inline: True
Inline callers:
  - crypto/gcm.c:gcm_hash
  - crypto/gcm.c:gcm_hash_update
  - crypto/gcm.c:gcm_hash_update
```
```
In lib/iov_iter.c (ffffffff8151f531)
Location: include/crypto/hash.h:233
Inline: True
Inline callers:
  - lib/iov_iter.c:hash_and_copy_to_iter
  - lib/iov_iter.c:hash_and_copy_to_iter
```
```
In net/ipv4/tcp.c (ffffffff8195dee8)
Location: include/crypto/hash.h:233
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
In net/ipv4/tcp_ipv4.c (ffffffff81977eea)
Location: include/crypto/hash.h:233
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_md5_hash_skb
  - net/ipv4/tcp_ipv4.c:tcp_v4_md5_hash_hdr
```
```
In net/ipv6/tcp_ipv6.c (ffffffff81a0d8e9)
Location: include/crypto/hash.h:233
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
In fs/verity/hash_algs.c (ffffffff813396ba)
Location: include/crypto/hash.h:233
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
Location: include/crypto/hash.h:233
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
In crypto/ahash.c (ffffffff814ae725)
Location: include/crypto/hash.h:233
Inline: True
Inline callers:
  - crypto/ahash.c:crypto_ahash_init_tfm
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
In crypto/shash.c (ffffffff814afa52)
Location: include/crypto/hash.h:233
Inline: True
Inline callers:
  - crypto/shash.c:crypto_init_shash_ops_async
  - crypto/shash.c:shash_async_import
  - crypto/shash.c:shash_async_digest
  - crypto/shash.c:shash_async_finup
  - crypto/shash.c:shash_async_init
```
```
In crypto/gcm.c (ffffffff814b8e1d)
Location: include/crypto/hash.h:233
Inline: True
Inline callers:
  - crypto/gcm.c:gcm_hash
  - crypto/gcm.c:gcm_hash_update
  - crypto/gcm.c:gcm_hash_update
```
```
In lib/iov_iter.c (ffffffff8150f821)
Location: include/crypto/hash.h:233
Inline: True
Inline callers:
  - lib/iov_iter.c:hash_and_copy_to_iter
  - lib/iov_iter.c:hash_and_copy_to_iter
```
```
In net/ipv4/tcp.c (ffffffff819179d8)
Location: include/crypto/hash.h:233
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
In net/ipv4/tcp_ipv4.c (ffffffff819319aa)
Location: include/crypto/hash.h:233
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_md5_hash_skb
  - net/ipv4/tcp_ipv4.c:tcp_v4_md5_hash_hdr
```
```
In net/ipv6/tcp_ipv6.c (ffffffff819ca6a9)
Location: include/crypto/hash.h:233
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
In fs/verity/hash_algs.c (ffffffff813464aa)
Location: include/crypto/hash.h:233
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
Location: include/crypto/hash.h:233
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
In crypto/ahash.c (ffffffff814b9d95)
Location: include/crypto/hash.h:233
Inline: True
Inline callers:
  - crypto/ahash.c:crypto_ahash_init_tfm
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
In crypto/shash.c (ffffffff814bb0c2)
Location: include/crypto/hash.h:233
Inline: True
Inline callers:
  - crypto/shash.c:crypto_init_shash_ops_async
  - crypto/shash.c:shash_async_import
  - crypto/shash.c:shash_async_digest
  - crypto/shash.c:shash_async_finup
  - crypto/shash.c:shash_async_init
```
```
In crypto/gcm.c (ffffffff814c448d)
Location: include/crypto/hash.h:233
Inline: True
Inline callers:
  - crypto/gcm.c:gcm_hash
  - crypto/gcm.c:gcm_hash_update
  - crypto/gcm.c:gcm_hash_update
```
```
In lib/iov_iter.c (ffffffff8151b5c1)
Location: include/crypto/hash.h:233
Inline: True
Inline callers:
  - lib/iov_iter.c:hash_and_copy_to_iter
  - lib/iov_iter.c:hash_and_copy_to_iter
```
```
In net/ipv4/tcp.c (ffffffff819c86b8)
Location: include/crypto/hash.h:233
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
In net/ipv4/tcp_ipv4.c (ffffffff819e26ba)
Location: include/crypto/hash.h:233
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_md5_hash_skb
  - net/ipv4/tcp_ipv4.c:tcp_v4_md5_hash_hdr
```
```
In net/ipv6/tcp_ipv6.c (ffffffff81a78369)
Location: include/crypto/hash.h:233
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
In fs/verity/hash_algs.c (ffffffff8135978a)
Location: include/crypto/hash.h:233
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
Location: include/crypto/hash.h:233
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
In crypto/ahash.c (ffffffff814d2845)
Location: include/crypto/hash.h:233
Inline: True
Inline callers:
  - crypto/ahash.c:crypto_ahash_init_tfm
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
In crypto/shash.c (ffffffff814d3b92)
Location: include/crypto/hash.h:233
Inline: True
Inline callers:
  - crypto/shash.c:crypto_init_shash_ops_async
  - crypto/shash.c:shash_async_import
  - crypto/shash.c:shash_async_digest
  - crypto/shash.c:shash_async_finup
  - crypto/shash.c:shash_async_init
```
```
In crypto/gcm.c (ffffffff814dcf5d)
Location: include/crypto/hash.h:233
Inline: True
Inline callers:
  - crypto/gcm.c:gcm_hash
  - crypto/gcm.c:gcm_hash_update
  - crypto/gcm.c:gcm_hash_update
```
```
In lib/iov_iter.c (ffffffff81534e01)
Location: include/crypto/hash.h:233
Inline: True
Inline callers:
  - lib/iov_iter.c:hash_and_copy_to_iter
  - lib/iov_iter.c:hash_and_copy_to_iter
```
```
In net/ipv4/tcp.c (ffffffff819d2208)
Location: include/crypto/hash.h:233
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
In net/ipv4/tcp_ipv4.c (ffffffff819ec40a)
Location: include/crypto/hash.h:233
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_md5_hash_skb
  - net/ipv4/tcp_ipv4.c:tcp_v4_md5_hash_hdr
```
```
In net/ipv6/tcp_ipv6.c (ffffffff81a84ad9)
Location: include/crypto/hash.h:233
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_response
  - net/ipv6/tcp_ipv6.c:tcp_v6_md5_hash_skb
```
</details>
</li>
</ul>

## Differences
