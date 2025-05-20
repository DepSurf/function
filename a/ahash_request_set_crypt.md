# Function: <code>ahash_request_set_crypt</code>

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
In security/integrity/ima/ima_crypto.c (ffffffff81397ea0)
Location: include/crypto/hash.h:607
Inline: True
Inline callers:
  - security/integrity/ima/ima_crypto.c:ima_calc_file_hash_atfm
  - security/integrity/ima/ima_crypto.c:ima_calc_file_hash_atfm
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
In security/integrity/ima/ima_crypto.c (ffffffff813d4a07)
Location: include/crypto/hash.h:635
Inline: True
Inline callers:
  - security/integrity/ima/ima_crypto.c:ima_calc_buffer_hash
  - security/integrity/ima/ima_crypto.c:ima_calc_buffer_hash
  - security/integrity/ima/ima_crypto.c:ima_calc_file_hash
  - security/integrity/ima/ima_crypto.c:ima_calc_file_hash
```
```
In net/ipv4/tcp.c (ffffffff817d2fa3)
Location: include/crypto/hash.h:635
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_md5_hash_key
  - net/ipv4/tcp.c:tcp_md5_hash_skb_data
  - net/ipv4/tcp.c:tcp_md5_hash_skb_data
  - net/ipv4/tcp.c:tcp_md5_hash_header
```
```
In net/ipv4/tcp_ipv4.c (ffffffff817e807e)
Location: include/crypto/hash.h:635
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_md5_hash_skb
  - net/ipv4/tcp_ipv4.c:tcp_v4_md5_hash_hdr
  - net/ipv4/tcp_ipv4.c:tcp_v4_md5_hash_headers
```
```
In net/ipv6/tcp_ipv6.c (ffffffff8185dc54)
Location: include/crypto/hash.h:635
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_response
  - net/ipv6/tcp_ipv6.c:tcp_v6_md5_hash_skb
  - net/ipv6/tcp_ipv6.c:tcp_v6_md5_hash_headers
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
In security/integrity/ima/ima_crypto.c (ffffffff813ec457)
Location: include/crypto/hash.h:635
Inline: True
Inline callers:
  - security/integrity/ima/ima_crypto.c:ima_calc_buffer_hash
  - security/integrity/ima/ima_crypto.c:ima_calc_buffer_hash
  - security/integrity/ima/ima_crypto.c:ima_calc_file_hash
  - security/integrity/ima/ima_crypto.c:ima_calc_file_hash
```
```
In arch/x86/power/hibernate_64.c (ffffffff8178d64e)
Location: include/crypto/hash.h:635
Inline: True
Inline callers:
  - arch/x86/power/hibernate_64.c:get_e820_md5
```
```
In net/ipv4/tcp.c (ffffffff81802b33)
Location: include/crypto/hash.h:635
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_md5_hash_key
  - net/ipv4/tcp.c:tcp_md5_hash_skb_data
  - net/ipv4/tcp.c:tcp_md5_hash_skb_data
```
```
In net/ipv4/tcp_ipv4.c (ffffffff8181878e)
Location: include/crypto/hash.h:635
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_md5_hash_skb
  - net/ipv4/tcp_ipv4.c:tcp_v4_md5_hash_hdr
  - net/ipv4/tcp_ipv4.c:tcp_v4_md5_hash_headers
```
```
In net/ipv6/tcp_ipv6.c (ffffffff8188fcfc)
Location: include/crypto/hash.h:635
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_response
  - net/ipv6/tcp_ipv6.c:tcp_v6_md5_hash_skb
  - net/ipv6/tcp_ipv6.c:tcp_v6_md5_hash_headers
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
In security/integrity/ima/ima_crypto.c (ffffffff813f883a)
Location: include/crypto/hash.h:641
Inline: True
Inline callers:
  - security/integrity/ima/ima_crypto.c:ima_calc_buffer_hash
  - security/integrity/ima/ima_crypto.c:ima_calc_buffer_hash
  - security/integrity/ima/ima_crypto.c:ima_calc_file_hash
  - security/integrity/ima/ima_crypto.c:ima_calc_file_hash
```
```
In arch/x86/power/hibernate_64.c (ffffffff817ab7de)
Location: include/crypto/hash.h:641
Inline: True
Inline callers:
  - arch/x86/power/hibernate_64.c:get_e820_md5
```
```
In net/ipv4/tcp.c (ffffffff81822913)
Location: include/crypto/hash.h:641
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_md5_hash_key
  - net/ipv4/tcp.c:tcp_md5_hash_skb_data
  - net/ipv4/tcp.c:tcp_md5_hash_skb_data
```
```
In net/ipv4/tcp_ipv4.c (ffffffff81838dde)
Location: include/crypto/hash.h:641
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_md5_hash_skb
  - net/ipv4/tcp_ipv4.c:tcp_v4_md5_hash_hdr
  - net/ipv4/tcp_ipv4.c:tcp_v4_md5_hash_headers
```
```
In net/ipv6/tcp_ipv6.c (ffffffff818b638d)
Location: include/crypto/hash.h:641
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_response
  - net/ipv6/tcp_ipv6.c:tcp_v6_md5_hash_skb
  - net/ipv6/tcp_ipv6.c:tcp_v6_md5_hash_headers
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
In security/integrity/ima/ima_crypto.c (ffffffff81420b66)
Location: include/crypto/hash.h:649
Inline: True
Inline callers:
  - security/integrity/ima/ima_crypto.c:ima_calc_buffer_hash
  - security/integrity/ima/ima_crypto.c:ima_calc_buffer_hash
  - security/integrity/ima/ima_crypto.c:ima_calc_file_hash
  - security/integrity/ima/ima_crypto.c:ima_calc_file_hash
```
```
In crypto/gcm.c (ffffffff81438a13)
Location: include/crypto/hash.h:649
Inline: True
Inline callers:
  - crypto/gcm.c:gcm_hash_init_continue
  - crypto/gcm.c:gcm_hash_assoc_continue
  - crypto/gcm.c:gcm_hash_assoc_remain_continue
  - crypto/gcm.c:gcm_hash_crypt_continue
  - crypto/gcm.c:gcm_hash_crypt_remain_continue
```
```
In arch/x86/power/hibernate_64.c (ffffffff81822d4e)
Location: include/crypto/hash.h:649
Inline: True
Inline callers:
  - arch/x86/power/hibernate_64.c:get_e820_md5
```
```
In net/ipv4/tcp.c (ffffffff818a1a23)
Location: include/crypto/hash.h:649
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_md5_hash_key
  - net/ipv4/tcp.c:tcp_md5_hash_skb_data
  - net/ipv4/tcp.c:tcp_md5_hash_skb_data
```
```
In net/ipv4/tcp_ipv4.c (ffffffff818b8651)
Location: include/crypto/hash.h:649
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_md5_hash_skb
  - net/ipv4/tcp_ipv4.c:tcp_v4_md5_hash_hdr
  - net/ipv4/tcp_ipv4.c:tcp_v4_md5_hash_headers
```
```
In net/ipv6/tcp_ipv6.c (ffffffff8193914e)
Location: include/crypto/hash.h:649
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_response
  - net/ipv6/tcp_ipv6.c:tcp_v6_md5_hash_skb
  - net/ipv6/tcp_ipv6.c:tcp_v6_md5_hash_headers
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
In security/integrity/ima/ima_crypto.c (ffffffff81452feb)
Location: include/crypto/hash.h:648
Inline: True
Inline callers:
  - security/integrity/ima/ima_crypto.c:ima_calc_buffer_hash
  - security/integrity/ima/ima_crypto.c:ima_calc_buffer_hash
  - security/integrity/ima/ima_crypto.c:ima_calc_file_hash
  - security/integrity/ima/ima_crypto.c:ima_calc_file_hash
```
```
In crypto/gcm.c (ffffffff8146b963)
Location: include/crypto/hash.h:648
Inline: True
Inline callers:
  - crypto/gcm.c:gcm_hash_init_continue
  - crypto/gcm.c:gcm_hash_assoc_continue
  - crypto/gcm.c:gcm_hash_assoc_remain_continue
  - crypto/gcm.c:gcm_hash_crypt_continue
```
```
In arch/x86/power/hibernate_64.c (ffffffff8186d073)
Location: include/crypto/hash.h:648
Inline: True
Inline callers:
  - arch/x86/power/hibernate_64.c:get_e820_md5
```
```
In net/ipv4/tcp.c (ffffffff818f653f)
Location: include/crypto/hash.h:648
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_md5_hash_key
  - net/ipv4/tcp.c:tcp_md5_hash_skb_data
  - net/ipv4/tcp.c:tcp_md5_hash_skb_data
```
```
In net/ipv4/tcp_ipv4.c (ffffffff8190ebed)
Location: include/crypto/hash.h:648
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_md5_hash_skb
  - net/ipv4/tcp_ipv4.c:tcp_v4_md5_hash_hdr
```
```
In net/ipv6/tcp_ipv6.c (ffffffff819929ed)
Location: include/crypto/hash.h:648
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
In security/integrity/ima/ima_crypto.c (ffffffff8147015e)
Location: include/crypto/hash.h:660
Inline: True
Inline callers:
  - security/integrity/ima/ima_crypto.c:ima_calc_buffer_hash
  - security/integrity/ima/ima_crypto.c:ima_calc_buffer_hash
  - security/integrity/ima/ima_crypto.c:ima_calc_file_hash
  - security/integrity/ima/ima_crypto.c:ima_calc_file_hash
```
```
In crypto/gcm.c (ffffffff81488810)
Location: include/crypto/hash.h:660
Inline: True
Inline callers:
  - crypto/gcm.c:gcm_hash_update
```
```
In lib/iov_iter.c (ffffffff814dd3c6)
Location: include/crypto/hash.h:660
Inline: True
Inline callers:
  - lib/iov_iter.c:hash_and_copy_to_iter
```
```
In net/ipv4/tcp.c (ffffffff81926a03)
Location: include/crypto/hash.h:660
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_md5_hash_key
  - net/ipv4/tcp.c:tcp_md5_hash_skb_data
  - net/ipv4/tcp.c:tcp_md5_hash_skb_data
```
```
In net/ipv4/tcp_ipv4.c (ffffffff8193d01a)
Location: include/crypto/hash.h:660
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_md5_hash_skb
  - net/ipv4/tcp_ipv4.c:tcp_v4_md5_hash_hdr
```
```
In net/ipv6/tcp_ipv6.c (ffffffff819c911b)
Location: include/crypto/hash.h:660
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
In security/integrity/ima/ima_crypto.c (ffffffff8149db41)
Location: include/crypto/hash.h:659
Inline: True
Inline callers:
  - security/integrity/ima/ima_crypto.c:ima_calc_buffer_hash
  - security/integrity/ima/ima_crypto.c:ima_calc_buffer_hash
  - security/integrity/ima/ima_crypto.c:ima_calc_file_hash_atfm
  - security/integrity/ima/ima_crypto.c:ima_calc_file_hash_atfm
```
```
In crypto/gcm.c (ffffffff814b6832)
Location: include/crypto/hash.h:659
Inline: True
Inline callers:
  - crypto/gcm.c:gcm_hash_update
```
```
In lib/iov_iter.c (ffffffff81509af7)
Location: include/crypto/hash.h:659
Inline: True
Inline callers:
  - lib/iov_iter.c:hash_and_copy_to_iter
```
```
In net/ipv4/tcp.c (ffffffff81987895)
Location: include/crypto/hash.h:659
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_md5_hash_key
  - net/ipv4/tcp.c:tcp_md5_hash_skb_data
  - net/ipv4/tcp.c:tcp_md5_hash_skb_data
```
```
In net/ipv4/tcp_ipv4.c (ffffffff819a146a)
Location: include/crypto/hash.h:659
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_md5_hash_skb
  - net/ipv4/tcp_ipv4.c:tcp_v4_md5_hash_hdr
```
```
In net/ipv6/tcp_ipv6.c (ffffffff81a37ba1)
Location: include/crypto/hash.h:659
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
In fs/verity/hash_algs.c (ffffffff81350533)
Location: include/crypto/hash.h:659
Inline: True
Inline callers:
  - fs/verity/hash_algs.c:fsverity_hash_buffer
  - fs/verity/hash_algs.c:fsverity_hash_page
  - fs/verity/hash_algs.c:fsverity_prepare_hash_state
```
```
In security/integrity/ima/ima_crypto.c (ffffffff814b7f81)
Location: include/crypto/hash.h:659
Inline: True
Inline callers:
  - security/integrity/ima/ima_crypto.c:ima_calc_buffer_hash
  - security/integrity/ima/ima_crypto.c:ima_calc_buffer_hash
  - security/integrity/ima/ima_crypto.c:ima_calc_file_hash_atfm
  - security/integrity/ima/ima_crypto.c:ima_calc_file_hash_atfm
```
```
In crypto/gcm.c (ffffffff814cfa52)
Location: include/crypto/hash.h:659
Inline: True
Inline callers:
  - crypto/gcm.c:gcm_hash_update
```
```
In lib/iov_iter.c (ffffffff81526f39)
Location: include/crypto/hash.h:659
Inline: True
Inline callers:
  - lib/iov_iter.c:hash_and_copy_to_iter
```
```
In net/ipv4/tcp.c (ffffffff819be065)
Location: include/crypto/hash.h:659
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_md5_hash_key
  - net/ipv4/tcp.c:tcp_md5_hash_skb_data
  - net/ipv4/tcp.c:tcp_md5_hash_skb_data
```
```
In net/ipv4/tcp_ipv4.c (ffffffff819d811a)
Location: include/crypto/hash.h:659
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_md5_hash_skb
  - net/ipv4/tcp_ipv4.c:tcp_v4_md5_hash_hdr
```
```
In net/ipv6/tcp_ipv6.c (ffffffff81a6e6d9)
Location: include/crypto/hash.h:659
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
In fs/verity/hash_algs.c (ffffffff81396efa)
Location: include/crypto/hash.h:672
Inline: True
Inline callers:
  - fs/verity/hash_algs.c:fsverity_hash_buffer
  - fs/verity/hash_algs.c:fsverity_hash_page
  - fs/verity/hash_algs.c:fsverity_prepare_hash_state
```
```
In security/integrity/ima/ima_crypto.c (ffffffff81516fb1)
Location: include/crypto/hash.h:672
Inline: True
Inline callers:
  - security/integrity/ima/ima_crypto.c:calc_buffer_ahash_atfm
  - security/integrity/ima/ima_crypto.c:calc_buffer_ahash_atfm
  - security/integrity/ima/ima_crypto.c:ima_calc_file_hash_atfm
  - security/integrity/ima/ima_crypto.c:ima_calc_file_hash_atfm
```
```
In crypto/gcm.c (ffffffff8152ed0e)
Location: include/crypto/hash.h:672
Inline: True
Inline callers:
  - crypto/gcm.c:gcm_hash_len
  - crypto/gcm.c:gcm_hash_update
```
```
In lib/iov_iter.c (ffffffff8158bac9)
Location: include/crypto/hash.h:672
Inline: True
Inline callers:
  - lib/iov_iter.c:hash_and_copy_to_iter
```
```
In net/ipv4/tcp.c (ffffffff81aa93f0)
Location: include/crypto/hash.h:672
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_md5_hash_key
  - net/ipv4/tcp.c:tcp_md5_hash_skb_data
  - net/ipv4/tcp.c:tcp_md5_hash_skb_data
```
```
In net/ipv4/tcp_ipv4.c (ffffffff81ac4105)
Location: include/crypto/hash.h:672
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_md5_hash_skb
  - net/ipv4/tcp_ipv4.c:tcp_v4_md5_hash_headers
```
```
In net/ipv6/tcp_ipv6.c (ffffffff81b67533)
Location: include/crypto/hash.h:672
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
In fs/verity/hash_algs.c (ffffffff813a8b2a)
Location: include/crypto/hash.h:680
Inline: True
Inline callers:
  - fs/verity/hash_algs.c:fsverity_hash_buffer
  - fs/verity/hash_algs.c:fsverity_hash_page
  - fs/verity/hash_algs.c:fsverity_prepare_hash_state
```
```
In security/integrity/ima/ima_crypto.c (ffffffff81534171)
Location: include/crypto/hash.h:680
Inline: True
Inline callers:
  - security/integrity/ima/ima_crypto.c:calc_buffer_ahash_atfm
  - security/integrity/ima/ima_crypto.c:calc_buffer_ahash_atfm
  - security/integrity/ima/ima_crypto.c:ima_calc_file_hash_atfm
  - security/integrity/ima/ima_crypto.c:ima_calc_file_hash_atfm
```
```
In crypto/gcm.c (ffffffff8154bc8e)
Location: include/crypto/hash.h:680
Inline: True
Inline callers:
  - crypto/gcm.c:gcm_hash_len
  - crypto/gcm.c:gcm_hash_update
```
```
In lib/iov_iter.c (ffffffff815a6a99)
Location: include/crypto/hash.h:680
Inline: True
Inline callers:
  - lib/iov_iter.c:hash_and_copy_to_iter
```
```
In net/ipv4/tcp.c (ffffffff81ab3710)
Location: include/crypto/hash.h:680
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_md5_hash_key
  - net/ipv4/tcp.c:tcp_md5_hash_skb_data
  - net/ipv4/tcp.c:tcp_md5_hash_skb_data
```
```
In net/ipv4/tcp_ipv4.c (ffffffff81acfb95)
Location: include/crypto/hash.h:680
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_md5_hash_skb
  - net/ipv4/tcp_ipv4.c:tcp_v4_md5_hash_headers
```
```
In net/ipv6/tcp_ipv6.c (ffffffff81b75d33)
Location: include/crypto/hash.h:680
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
In fs/verity/hash_algs.c (ffffffff813afb9a)
Location: include/crypto/hash.h:682
Inline: True
Inline callers:
  - fs/verity/hash_algs.c:fsverity_hash_buffer
  - fs/verity/hash_algs.c:fsverity_hash_page
  - fs/verity/hash_algs.c:fsverity_prepare_hash_state
```
```
In security/integrity/ima/ima_crypto.c (ffffffff8153d164)
Location: include/crypto/hash.h:682
Inline: True
Inline callers:
  - security/integrity/ima/ima_crypto.c:ima_calc_buffer_hash
  - security/integrity/ima/ima_crypto.c:ima_calc_buffer_hash
  - security/integrity/ima/ima_crypto.c:ima_calc_file_hash_atfm
  - security/integrity/ima/ima_crypto.c:ima_calc_file_hash_atfm
```
```
In crypto/gcm.c (ffffffff8155428f)
Location: include/crypto/hash.h:682
Inline: True
Inline callers:
  - crypto/gcm.c:gcm_hash_crypt_remain_continue
  - crypto/gcm.c:gcm_hash_update
```
```
In lib/iov_iter.c (ffffffff815b1859)
Location: include/crypto/hash.h:682
Inline: True
Inline callers:
  - lib/iov_iter.c:hash_and_copy_to_iter
```
```
In net/ipv4/tcp.c (ffffffff81a9e880)
Location: include/crypto/hash.h:682
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_md5_hash_key
  - net/ipv4/tcp.c:tcp_md5_hash_skb_data
  - net/ipv4/tcp.c:tcp_md5_hash_skb_data
```
```
In net/ipv4/tcp_ipv4.c (ffffffff81abace5)
Location: include/crypto/hash.h:682
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_md5_hash_skb
  - net/ipv4/tcp_ipv4.c:tcp_v4_md5_hash_headers
```
```
In net/ipv6/tcp_ipv6.c (ffffffff81b65512)
Location: include/crypto/hash.h:682
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
In fs/verity/hash_algs.c (ffffffff813ff78a)
Location: include/crypto/hash.h:682
Inline: True
Inline callers:
  - fs/verity/hash_algs.c:fsverity_hash_buffer
  - fs/verity/hash_algs.c:fsverity_hash_page
  - fs/verity/hash_algs.c:fsverity_prepare_hash_state
```
```
In security/integrity/ima/ima_crypto.c (ffffffff8159bfe4)
Location: include/crypto/hash.h:682
Inline: True
Inline callers:
  - security/integrity/ima/ima_crypto.c:ima_calc_buffer_hash
  - security/integrity/ima/ima_crypto.c:ima_calc_buffer_hash
  - security/integrity/ima/ima_crypto.c:ima_calc_file_hash_atfm
  - security/integrity/ima/ima_crypto.c:ima_calc_file_hash_atfm
```
```
In crypto/gcm.c (ffffffff815b52bf)
Location: include/crypto/hash.h:682
Inline: True
Inline callers:
  - crypto/gcm.c:gcm_hash_crypt_remain_continue
  - crypto/gcm.c:gcm_hash_update
```
```
In lib/iov_iter.c (ffffffff81619309)
Location: include/crypto/hash.h:682
Inline: True
Inline callers:
  - lib/iov_iter.c:hash_and_copy_to_iter
```
```
In net/ipv4/tcp.c (ffffffff81b5a340)
Location: include/crypto/hash.h:682
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_md5_hash_key
  - net/ipv4/tcp.c:tcp_md5_hash_skb_data
  - net/ipv4/tcp.c:tcp_md5_hash_skb_data
```
```
In net/ipv4/tcp_ipv4.c (ffffffff81b78035)
Location: include/crypto/hash.h:682
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_md5_hash_skb
  - net/ipv4/tcp_ipv4.c:tcp_v4_md5_hash_headers
```
```
In net/ipv6/tcp_ipv6.c (ffffffff81c2d788)
Location: include/crypto/hash.h:682
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
In fs/verity/hash_algs.c (ffffffff814733dc)
Location: include/crypto/hash.h:682
Inline: True
Inline callers:
  - fs/verity/hash_algs.c:fsverity_hash_buffer
  - fs/verity/hash_algs.c:fsverity_hash_page
  - fs/verity/hash_algs.c:fsverity_prepare_hash_state
```
```
In security/integrity/ima/ima_crypto.c (ffffffff81640fbe)
Location: include/crypto/hash.h:682
Inline: True
Inline callers:
  - security/integrity/ima/ima_crypto.c:ima_calc_buffer_hash
  - security/integrity/ima/ima_crypto.c:ima_calc_buffer_hash
  - security/integrity/ima/ima_crypto.c:ima_calc_file_hash_atfm
  - security/integrity/ima/ima_crypto.c:ima_calc_file_hash_atfm
```
```
In crypto/gcm.c (ffffffff8165e392)
Location: include/crypto/hash.h:682
Inline: True
Inline callers:
  - crypto/gcm.c:gcm_hash_crypt_remain_continue
  - crypto/gcm.c:gcm_hash_update
```
```
In lib/iov_iter.c (ffffffff816e5ff9)
Location: include/crypto/hash.h:682
Inline: True
Inline callers:
  - lib/iov_iter.c:hash_and_copy_to_iter
```
```
In net/ipv4/tcp.c (ffffffff81ce8e3f)
Location: include/crypto/hash.h:682
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_md5_hash_key
  - net/ipv4/tcp.c:tcp_md5_hash_skb_data
  - net/ipv4/tcp.c:tcp_md5_hash_skb_data
```
```
In net/ipv4/tcp_ipv4.c (ffffffff81d07c6d)
Location: include/crypto/hash.h:682
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_md5_hash_skb
  - net/ipv4/tcp_ipv4.c:tcp_v4_md5_hash_headers
```
```
In net/ipv6/tcp_ipv6.c (ffffffff81dcab5d)
Location: include/crypto/hash.h:682
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
In fs/verity/hash_algs.c (ffffffff8150526c)
Location: include/crypto/hash.h:682
Inline: True
Inline callers:
  - fs/verity/hash_algs.c:fsverity_hash_buffer
  - fs/verity/hash_algs.c:fsverity_hash_page
  - fs/verity/hash_algs.c:fsverity_prepare_hash_state
```
```
In security/integrity/ima/ima_crypto.c (ffffffff816f8f2e)
Location: include/crypto/hash.h:682
Inline: True
Inline callers:
  - security/integrity/ima/ima_crypto.c:ima_calc_buffer_hash
  - security/integrity/ima/ima_crypto.c:ima_calc_buffer_hash
  - security/integrity/ima/ima_crypto.c:ima_calc_file_hash_atfm
  - security/integrity/ima/ima_crypto.c:ima_calc_file_hash_atfm
```
```
In crypto/gcm.c (ffffffff81718052)
Location: include/crypto/hash.h:682
Inline: True
Inline callers:
  - crypto/gcm.c:gcm_hash_crypt_remain_continue
  - crypto/gcm.c:gcm_hash_update
```
```
In lib/iov_iter.c (ffffffff817d4219)
Location: include/crypto/hash.h:682
Inline: True
Inline callers:
  - lib/iov_iter.c:hash_and_copy_to_iter
```
```
In net/ipv4/tcp.c (ffffffff81eac3af)
Location: include/crypto/hash.h:682
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_md5_hash_key
  - net/ipv4/tcp.c:tcp_md5_hash_skb_data
  - net/ipv4/tcp.c:tcp_md5_hash_skb_data
```
```
In net/ipv4/tcp_ipv4.c (ffffffff81ecd5cd)
Location: include/crypto/hash.h:682
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_md5_hash_skb
  - net/ipv4/tcp_ipv4.c:tcp_v4_md5_hash_headers
```
```
In net/ipv6/tcp_ipv6.c (ffffffff81f9bbca)
Location: include/crypto/hash.h:682
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
In security/integrity/ima/ima_crypto.c (ffffffff8173312a)
Location: include/crypto/hash.h:732
Inline: True
Inline callers:
  - security/integrity/ima/ima_crypto.c:ima_calc_buffer_hash
  - security/integrity/ima/ima_crypto.c:ima_calc_buffer_hash
  - security/integrity/ima/ima_crypto.c:ima_calc_file_hash_atfm
  - security/integrity/ima/ima_crypto.c:ima_calc_file_hash_atfm
```
```
In crypto/ahash.c (ffffffff81744ec4)
Location: include/crypto/hash.h:732
Inline: True
Inline callers:
  - crypto/ahash.c:ahash_save_req
```
```
In crypto/gcm.c (ffffffff81753967)
Location: include/crypto/hash.h:732
Inline: True
Inline callers:
  - crypto/gcm.c:gcm_hash_len
  - crypto/gcm.c:gcm_hash_update
```
```
In lib/iov_iter.c (ffffffff81811c0f)
Location: include/crypto/hash.h:732
Inline: True
Inline callers:
  - lib/iov_iter.c:hash_and_copy_to_iter
```
```
In net/ipv4/tcp.c (ffffffff81f0ae5f)
Location: include/crypto/hash.h:732
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_md5_hash_key
  - net/ipv4/tcp.c:tcp_md5_hash_skb_data
  - net/ipv4/tcp.c:tcp_md5_hash_skb_data
```
```
In net/ipv4/tcp_ipv4.c (ffffffff81f2c28e)
Location: include/crypto/hash.h:732
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_md5_hash_skb
  - net/ipv4/tcp_ipv4.c:tcp_v4_md5_hash_headers
```
```
In net/ipv6/tcp_ipv6.c (ffffffff81ffaf67)
Location: include/crypto/hash.h:732
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
In security/integrity/ima/ima_crypto.c (ffffffff81773b2b)
Location: include/crypto/hash.h:664
Inline: True
Inline callers:
  - security/integrity/ima/ima_crypto.c:ima_calc_buffer_hash
  - security/integrity/ima/ima_crypto.c:ima_calc_buffer_hash
  - security/integrity/ima/ima_crypto.c:ima_calc_file_hash_atfm
  - security/integrity/ima/ima_crypto.c:ima_calc_file_hash_atfm
```
```
In crypto/ahash.c (ffffffff817872d1)
Location: include/crypto/hash.h:664
Inline: True
```
```
In crypto/gcm.c (ffffffff81796a65)
Location: include/crypto/hash.h:664
Inline: True
Inline callers:
  - crypto/gcm.c:gcm_hash_init_continue
  - crypto/gcm.c:gcm_hash_assoc_continue
  - crypto/gcm.c:gcm_hash_assoc_remain_continue
  - crypto/gcm.c:gcm_hash_crypt_continue
  - crypto/gcm.c:gcm_hash_len
```
```
In net/core/datagram.c (ffffffff81eddcfa)
Location: include/crypto/hash.h:664
Inline: True
Inline callers:
  - net/core/datagram.c:hash_and_copy_to_iter
```
```
In net/ipv4/tcp.c (ffffffff81fcdfc0)
Location: include/crypto/hash.h:664
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_md5_hash_key
```
```
In net/ipv4/tcp_ipv4.c (ffffffff81ff105a)
Location: include/crypto/hash.h:664
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_md5_hash_skb
  - net/ipv4/tcp_ipv4.c:tcp_v4_md5_hash_headers
```
```
In net/ipv4/tcp_sigpool.c (ffffffff8204c81e)
Location: include/crypto/hash.h:664
Inline: True
Inline callers:
  - net/ipv4/tcp_sigpool.c:tcp_sigpool_hash_skb_data
  - net/ipv4/tcp_sigpool.c:tcp_sigpool_hash_skb_data
```
```
In net/ipv4/tcp_ao.c (ffffffff820540aa)
Location: include/crypto/hash.h:664
Inline: True
Inline callers:
  - net/ipv4/tcp_ao.c:tcp_ao_parse_crypto
  - net/ipv4/tcp_ao.c:tcp_ao_hash_skb
  - net/ipv4/tcp_ao.c:tcp_ao_hash_skb
  - net/ipv4/tcp_ao.c:tcp_ao_hash_skb
  - net/ipv4/tcp_ao.c:tcp_ao_hash_hdr
  - net/ipv4/tcp_ao.c:tcp_ao_hash_hdr
  - net/ipv4/tcp_ao.c:tcp_ao_hash_hdr
  - net/ipv4/tcp_ao.c:tcp_ao_calc_traffic_key
```
```
In net/ipv6/tcp_ipv6.c (ffffffff820ca8d2)
Location: include/crypto/hash.h:664
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_response
  - net/ipv6/tcp_ipv6.c:tcp_v6_md5_hash_skb
```
```
In net/ipv6/tcp_ao.c (ffffffff820f4bd4)
Location: include/crypto/hash.h:664
Inline: True
Inline callers:
  - net/ipv6/tcp_ao.c:tcp_v6_ao_hash_pseudoheader
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
In fs/verity/hash_algs.c (ffff8000104121f0)
Location: include/crypto/hash.h:659
Inline: True
Inline callers:
  - fs/verity/hash_algs.c:fsverity_hash_buffer
  - fs/verity/hash_algs.c:fsverity_hash_page
  - fs/verity/hash_algs.c:fsverity_prepare_hash_state
```
```
In security/integrity/ima/ima_crypto.c (ffff8000105b033c)
Location: include/crypto/hash.h:659
Inline: True
Inline callers:
  - security/integrity/ima/ima_crypto.c:ima_calc_buffer_hash
  - security/integrity/ima/ima_crypto.c:ima_calc_buffer_hash
  - security/integrity/ima/ima_crypto.c:ima_calc_file_hash_atfm
  - security/integrity/ima/ima_crypto.c:ima_calc_file_hash_atfm
```
```
In crypto/gcm.c (ffff8000105cc424)
Location: include/crypto/hash.h:659
Inline: True
Inline callers:
  - crypto/gcm.c:gcm_hash_update
```
```
In lib/iov_iter.c (ffff8000106316ac)
Location: include/crypto/hash.h:659
Inline: True
Inline callers:
  - lib/iov_iter.c:hash_and_copy_to_iter
```
```
In net/ipv4/tcp.c (ffff800010c6fc74)
Location: include/crypto/hash.h:659
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_md5_hash_key
  - net/ipv4/tcp.c:tcp_md5_hash_skb_data
  - net/ipv4/tcp.c:tcp_md5_hash_skb_data
```
```
In net/ipv4/tcp_ipv4.c (ffff800010c8ae10)
Location: include/crypto/hash.h:659
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_md5_hash_skb
  - net/ipv4/tcp_ipv4.c:tcp_v4_md5_hash_hdr
```
```
In net/ipv6/tcp_ipv6.c (ffff800010d37f58)
Location: include/crypto/hash.h:659
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
In fs/verity/hash_algs.c (c05de87c)
Location: include/crypto/hash.h:659
Inline: True
Inline callers:
  - fs/verity/hash_algs.c:fsverity_hash_buffer
  - fs/verity/hash_algs.c:fsverity_hash_page
  - fs/verity/hash_algs.c:fsverity_prepare_hash_state
```
```
In security/integrity/ima/ima_crypto.c (c075fa70)
Location: include/crypto/hash.h:659
Inline: True
Inline callers:
  - security/integrity/ima/ima_crypto.c:ima_calc_buffer_hash
  - security/integrity/ima/ima_crypto.c:ima_calc_buffer_hash
  - security/integrity/ima/ima_crypto.c:ima_calc_file_hash_atfm
  - security/integrity/ima/ima_crypto.c:ima_calc_file_hash_atfm
```
```
In crypto/gcm.c (c0779d5c)
Location: include/crypto/hash.h:659
Inline: True
Inline callers:
  - crypto/gcm.c:gcm_hash_update
```
```
In lib/iov_iter.c (c07d79fc)
Location: include/crypto/hash.h:659
Inline: True
Inline callers:
  - lib/iov_iter.c:hash_and_copy_to_iter
```
```
In net/ipv4/tcp.c (c0d7edc8)
Location: include/crypto/hash.h:659
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_md5_hash_key
  - net/ipv4/tcp.c:tcp_md5_hash_skb_data
  - net/ipv4/tcp.c:tcp_md5_hash_skb_data
```
```
In net/ipv4/tcp_ipv4.c (c0d996f8)
Location: include/crypto/hash.h:659
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_md5_hash_skb
  - net/ipv4/tcp_ipv4.c:tcp_v4_md5_hash_hdr
  - net/ipv4/tcp_ipv4.c:tcp_v4_md5_hash_headers
```
```
In net/ipv6/tcp_ipv6.c (c0e38c34)
Location: include/crypto/hash.h:659
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_response
  - net/ipv6/tcp_ipv6.c:tcp_v6_md5_hash_skb
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
In fs/verity/hash_algs.c (c00000000051ff68)
Location: include/crypto/hash.h:659
Inline: True
Inline callers:
  - fs/verity/hash_algs.c:fsverity_hash_buffer
  - fs/verity/hash_algs.c:fsverity_hash_page
  - fs/verity/hash_algs.c:fsverity_prepare_hash_state
```
```
In security/integrity/ima/ima_crypto.c (c00000000072fe20)
Location: include/crypto/hash.h:659
Inline: True
Inline callers:
  - security/integrity/ima/ima_crypto.c:ima_calc_buffer_hash
  - security/integrity/ima/ima_crypto.c:ima_calc_buffer_hash
  - security/integrity/ima/ima_crypto.c:ima_calc_file_hash_atfm
  - security/integrity/ima/ima_crypto.c:ima_calc_file_hash_atfm
```
```
In crypto/gcm.c (c000000000756e4c)
Location: include/crypto/hash.h:659
Inline: True
Inline callers:
  - crypto/gcm.c:gcm_hash_update
```
```
In lib/iov_iter.c (c0000000007d5704)
Location: include/crypto/hash.h:659
Inline: True
Inline callers:
  - lib/iov_iter.c:hash_and_copy_to_iter
```
```
In net/ipv4/tcp.c (c000000000d76c1c)
Location: include/crypto/hash.h:659
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_md5_hash_key
  - net/ipv4/tcp.c:tcp_md5_hash_skb_data
  - net/ipv4/tcp.c:tcp_md5_hash_skb_data
```
```
In net/ipv4/tcp_ipv4.c (c000000000d99920)
Location: include/crypto/hash.h:659
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_md5_hash_skb
  - net/ipv4/tcp_ipv4.c:tcp_v4_md5_hash_hdr
```
```
In net/ipv6/tcp_ipv6.c (c000000000e695e8)
Location: include/crypto/hash.h:659
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
In fs/verity/hash_algs.c (ffffffe0002ba256)
Location: include/crypto/hash.h:659
Inline: True
Inline callers:
  - fs/verity/hash_algs.c:fsverity_hash_buffer
  - fs/verity/hash_algs.c:fsverity_hash_page
  - fs/verity/hash_algs.c:fsverity_prepare_hash_state
```
```
In security/integrity/ima/ima_crypto.c (ffffffe0003f7fd4)
Location: include/crypto/hash.h:659
Inline: True
Inline callers:
  - security/integrity/ima/ima_crypto.c:ima_calc_buffer_hash
  - security/integrity/ima/ima_crypto.c:ima_calc_buffer_hash
  - security/integrity/ima/ima_crypto.c:ima_calc_file_hash_atfm
  - security/integrity/ima/ima_crypto.c:ima_calc_file_hash_atfm
```
```
In crypto/gcm.c (ffffffe00041053c)
Location: include/crypto/hash.h:659
Inline: True
Inline callers:
  - crypto/gcm.c:gcm_hash_update
```
```
In lib/iov_iter.c (ffffffe00045fff8)
Location: include/crypto/hash.h:659
Inline: True
Inline callers:
  - lib/iov_iter.c:hash_and_copy_to_iter
```
```
In net/ipv4/tcp.c (ffffffe0007d4f2c)
Location: include/crypto/hash.h:659
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_md5_hash_key
  - net/ipv4/tcp.c:tcp_md5_hash_skb_data
  - net/ipv4/tcp.c:tcp_md5_hash_skb_data
```
```
In net/ipv4/tcp_ipv4.c (ffffffe0007ec320)
Location: include/crypto/hash.h:659
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_md5_hash_skb
  - net/ipv4/tcp_ipv4.c:tcp_v4_md5_hash_hdr
```
```
In net/ipv6/tcp_ipv6.c (ffffffe00087433c)
Location: include/crypto/hash.h:659
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
In fs/verity/hash_algs.c (ffffffff81348b13)
Location: include/crypto/hash.h:659
Inline: True
Inline callers:
  - fs/verity/hash_algs.c:fsverity_hash_buffer
  - fs/verity/hash_algs.c:fsverity_hash_page
  - fs/verity/hash_algs.c:fsverity_prepare_hash_state
```
```
In security/integrity/ima/ima_crypto.c (ffffffff814b0561)
Location: include/crypto/hash.h:659
Inline: True
Inline callers:
  - security/integrity/ima/ima_crypto.c:ima_calc_buffer_hash
  - security/integrity/ima/ima_crypto.c:ima_calc_buffer_hash
  - security/integrity/ima/ima_crypto.c:ima_calc_file_hash_atfm
  - security/integrity/ima/ima_crypto.c:ima_calc_file_hash_atfm
```
```
In crypto/gcm.c (ffffffff814c8032)
Location: include/crypto/hash.h:659
Inline: True
Inline callers:
  - crypto/gcm.c:gcm_hash_update
```
```
In lib/iov_iter.c (ffffffff8151f519)
Location: include/crypto/hash.h:659
Inline: True
Inline callers:
  - lib/iov_iter.c:hash_and_copy_to_iter
```
```
In net/ipv4/tcp.c (ffffffff8195ded5)
Location: include/crypto/hash.h:659
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_md5_hash_key
  - net/ipv4/tcp.c:tcp_md5_hash_skb_data
  - net/ipv4/tcp.c:tcp_md5_hash_skb_data
```
```
In net/ipv4/tcp_ipv4.c (ffffffff81977f8a)
Location: include/crypto/hash.h:659
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_md5_hash_skb
  - net/ipv4/tcp_ipv4.c:tcp_v4_md5_hash_hdr
```
```
In net/ipv6/tcp_ipv6.c (ffffffff81a0dd69)
Location: include/crypto/hash.h:659
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
In fs/verity/hash_algs.c (ffffffff813397f3)
Location: include/crypto/hash.h:659
Inline: True
Inline callers:
  - fs/verity/hash_algs.c:fsverity_hash_buffer
  - fs/verity/hash_algs.c:fsverity_hash_page
  - fs/verity/hash_algs.c:fsverity_prepare_hash_state
```
```
In security/integrity/ima/ima_crypto.c (ffffffff814a0f81)
Location: include/crypto/hash.h:659
Inline: True
Inline callers:
  - security/integrity/ima/ima_crypto.c:ima_calc_buffer_hash
  - security/integrity/ima/ima_crypto.c:ima_calc_buffer_hash
  - security/integrity/ima/ima_crypto.c:ima_calc_file_hash_atfm
  - security/integrity/ima/ima_crypto.c:ima_calc_file_hash_atfm
```
```
In crypto/gcm.c (ffffffff814b8a52)
Location: include/crypto/hash.h:659
Inline: True
Inline callers:
  - crypto/gcm.c:gcm_hash_update
```
```
In lib/iov_iter.c (ffffffff8150f809)
Location: include/crypto/hash.h:659
Inline: True
Inline callers:
  - lib/iov_iter.c:hash_and_copy_to_iter
```
```
In net/ipv4/tcp.c (ffffffff819179c5)
Location: include/crypto/hash.h:659
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_md5_hash_key
  - net/ipv4/tcp.c:tcp_md5_hash_skb_data
  - net/ipv4/tcp.c:tcp_md5_hash_skb_data
```
```
In net/ipv4/tcp_ipv4.c (ffffffff81931a4a)
Location: include/crypto/hash.h:659
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_md5_hash_skb
  - net/ipv4/tcp_ipv4.c:tcp_v4_md5_hash_hdr
```
```
In net/ipv6/tcp_ipv6.c (ffffffff819cab29)
Location: include/crypto/hash.h:659
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
In fs/verity/hash_algs.c (ffffffff813465e3)
Location: include/crypto/hash.h:659
Inline: True
Inline callers:
  - fs/verity/hash_algs.c:fsverity_hash_buffer
  - fs/verity/hash_algs.c:fsverity_hash_page
  - fs/verity/hash_algs.c:fsverity_prepare_hash_state
```
```
In security/integrity/ima/ima_crypto.c (ffffffff814ac5f1)
Location: include/crypto/hash.h:659
Inline: True
Inline callers:
  - security/integrity/ima/ima_crypto.c:ima_calc_buffer_hash
  - security/integrity/ima/ima_crypto.c:ima_calc_buffer_hash
  - security/integrity/ima/ima_crypto.c:ima_calc_file_hash_atfm
  - security/integrity/ima/ima_crypto.c:ima_calc_file_hash_atfm
```
```
In crypto/gcm.c (ffffffff814c40c2)
Location: include/crypto/hash.h:659
Inline: True
Inline callers:
  - crypto/gcm.c:gcm_hash_update
```
```
In lib/iov_iter.c (ffffffff8151b5a9)
Location: include/crypto/hash.h:659
Inline: True
Inline callers:
  - lib/iov_iter.c:hash_and_copy_to_iter
```
```
In net/ipv4/tcp.c (ffffffff819c86a5)
Location: include/crypto/hash.h:659
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_md5_hash_key
  - net/ipv4/tcp.c:tcp_md5_hash_skb_data
  - net/ipv4/tcp.c:tcp_md5_hash_skb_data
```
```
In net/ipv4/tcp_ipv4.c (ffffffff819e275a)
Location: include/crypto/hash.h:659
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_md5_hash_skb
  - net/ipv4/tcp_ipv4.c:tcp_v4_md5_hash_hdr
```
```
In net/ipv6/tcp_ipv6.c (ffffffff81a787e9)
Location: include/crypto/hash.h:659
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
In fs/verity/hash_algs.c (ffffffff813598c3)
Location: include/crypto/hash.h:659
Inline: True
Inline callers:
  - fs/verity/hash_algs.c:fsverity_hash_buffer
  - fs/verity/hash_algs.c:fsverity_hash_page
  - fs/verity/hash_algs.c:fsverity_prepare_hash_state
```
```
In security/integrity/ima/ima_crypto.c (ffffffff814c5041)
Location: include/crypto/hash.h:659
Inline: True
Inline callers:
  - security/integrity/ima/ima_crypto.c:ima_calc_buffer_hash
  - security/integrity/ima/ima_crypto.c:ima_calc_buffer_hash
  - security/integrity/ima/ima_crypto.c:ima_calc_file_hash_atfm
  - security/integrity/ima/ima_crypto.c:ima_calc_file_hash_atfm
```
```
In crypto/gcm.c (ffffffff814dcb92)
Location: include/crypto/hash.h:659
Inline: True
Inline callers:
  - crypto/gcm.c:gcm_hash_update
```
```
In lib/iov_iter.c (ffffffff81534de9)
Location: include/crypto/hash.h:659
Inline: True
Inline callers:
  - lib/iov_iter.c:hash_and_copy_to_iter
```
```
In net/ipv4/tcp.c (ffffffff819d21f5)
Location: include/crypto/hash.h:659
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_md5_hash_key
  - net/ipv4/tcp.c:tcp_md5_hash_skb_data
  - net/ipv4/tcp.c:tcp_md5_hash_skb_data
```
```
In net/ipv4/tcp_ipv4.c (ffffffff819ec4aa)
Location: include/crypto/hash.h:659
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_md5_hash_skb
  - net/ipv4/tcp_ipv4.c:tcp_v4_md5_hash_hdr
```
```
In net/ipv6/tcp_ipv6.c (ffffffff81a84f79)
Location: include/crypto/hash.h:659
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_response
  - net/ipv6/tcp_ipv6.c:tcp_v6_md5_hash_skb
```
</details>
</li>
</ul>

## Differences
