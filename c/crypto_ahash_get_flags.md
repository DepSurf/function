# Function: <code>crypto_ahash_get_flags</code>

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
<details>
<summary>In <code>4.15</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In security/integrity/ima/ima_crypto.c (0)
Location: include/crypto/hash.h:351
Inline: True
```
```
In crypto/ahash.c (0)
Location: include/crypto/hash.h:351
Inline: True
```
```
In crypto/gcm.c (0)
Location: include/crypto/hash.h:351
Inline: True
```
```
In net/ipv4/tcp_ipv4.c (0)
Location: include/crypto/hash.h:351
Inline: True
```
```
In net/ipv6/tcp_ipv6.c (0)
Location: include/crypto/hash.h:351
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
Location: include/crypto/hash.h:350
Inline: True
Inline callers:
  - security/integrity/ima/ima_crypto.c:ima_calc_buffer_hash
  - security/integrity/ima/ima_crypto.c:ima_calc_file_hash
```
```
In crypto/ahash.c (ffffffff8145ed89)
Location: include/crypto/hash.h:350
Inline: True
Inline callers:
  - crypto/ahash.c:crypto_ahash_digest
```
```
In crypto/gcm.c (ffffffff8146b9f2)
Location: include/crypto/hash.h:350
Inline: True
Inline callers:
  - crypto/gcm.c:gcm_hash
  - crypto/gcm.c:crypto_gcm_setkey
```
```
In net/ipv4/tcp_ipv4.c (ffffffff8190eb4a)
Location: include/crypto/hash.h:350
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_md5_hash_skb
  - net/ipv4/tcp_ipv4.c:tcp_v4_md5_hash_hdr
```
```
In net/ipv6/tcp_ipv6.c (ffffffff8199263e)
Location: include/crypto/hash.h:350
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
Location: include/crypto/hash.h:354
Inline: True
Inline callers:
  - security/integrity/ima/ima_crypto.c:ima_calc_buffer_hash
  - security/integrity/ima/ima_crypto.c:ima_calc_file_hash
```
```
In crypto/ahash.c (ffffffff8147c968)
Location: include/crypto/hash.h:354
Inline: True
Inline callers:
  - crypto/ahash.c:crypto_ahash_digest
```
```
In crypto/gcm.c (ffffffff81488f52)
Location: include/crypto/hash.h:354
Inline: True
Inline callers:
  - crypto/gcm.c:gcm_hash
  - crypto/gcm.c:crypto_gcm_setkey
```
```
In net/ipv4/tcp_ipv4.c (ffffffff8193cf7a)
Location: include/crypto/hash.h:354
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_md5_hash_skb
  - net/ipv4/tcp_ipv4.c:tcp_v4_md5_hash_hdr
```
```
In net/ipv6/tcp_ipv6.c (ffffffff819c8d7e)
Location: include/crypto/hash.h:354
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
Location: include/crypto/hash.h:353
Inline: True
Inline callers:
  - security/integrity/ima/ima_crypto.c:ima_calc_buffer_hash
  - security/integrity/ima/ima_crypto.c:ima_calc_file_hash_atfm
```
```
In crypto/ahash.c (ffffffff814ab107)
Location: include/crypto/hash.h:353
Inline: True
Inline callers:
  - crypto/ahash.c:crypto_ahash_digest
```
```
In crypto/gcm.c (ffffffff814b6bfd)
Location: include/crypto/hash.h:353
Inline: True
Inline callers:
  - crypto/gcm.c:gcm_hash
  - crypto/gcm.c:crypto_gcm_setkey
```
```
In net/ipv4/tcp_ipv4.c (ffffffff819a13ca)
Location: include/crypto/hash.h:353
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_md5_hash_skb
  - net/ipv4/tcp_ipv4.c:tcp_v4_md5_hash_hdr
```
```
In net/ipv6/tcp_ipv6.c (ffffffff81a3772f)
Location: include/crypto/hash.h:353
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
Location: include/crypto/hash.h:353
Inline: True
Inline callers:
  - fs/verity/hash_algs.c:fsverity_hash_page
  - fs/verity/hash_algs.c:fsverity_prepare_hash_state
```
```
In security/integrity/ima/ima_crypto.c (ffffffff814b7f3e)
Location: include/crypto/hash.h:353
Inline: True
Inline callers:
  - security/integrity/ima/ima_crypto.c:ima_calc_buffer_hash
  - security/integrity/ima/ima_crypto.c:ima_calc_file_hash_atfm
```
```
In crypto/ahash.c (ffffffff814c5dc7)
Location: include/crypto/hash.h:353
Inline: True
Inline callers:
  - crypto/ahash.c:crypto_ahash_digest
```
```
In crypto/gcm.c (ffffffff814cfe1d)
Location: include/crypto/hash.h:353
Inline: True
Inline callers:
  - crypto/gcm.c:gcm_hash
  - crypto/gcm.c:crypto_gcm_setkey
```
```
In net/ipv4/tcp_ipv4.c (ffffffff819d807a)
Location: include/crypto/hash.h:353
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_md5_hash_skb
  - net/ipv4/tcp_ipv4.c:tcp_v4_md5_hash_hdr
```
```
In net/ipv6/tcp_ipv6.c (ffffffff81a6e259)
Location: include/crypto/hash.h:353
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
Location: include/crypto/hash.h:366
Inline: True
Inline callers:
  - fs/verity/hash_algs.c:fsverity_hash_page
  - fs/verity/hash_algs.c:fsverity_prepare_hash_state
```
```
In security/integrity/ima/ima_crypto.c (ffffffff81516f6d)
Location: include/crypto/hash.h:366
Inline: True
Inline callers:
  - security/integrity/ima/ima_crypto.c:calc_buffer_ahash_atfm
  - security/integrity/ima/ima_crypto.c:ima_calc_file_hash_atfm
```
```
In crypto/ahash.c (ffffffff81524777)
Location: include/crypto/hash.h:366
Inline: True
Inline callers:
  - crypto/ahash.c:crypto_ahash_digest
```
```
In crypto/gcm.c (ffffffff8152effd)
Location: include/crypto/hash.h:366
Inline: True
Inline callers:
  - crypto/gcm.c:gcm_hash
```
```
In net/ipv4/tcp_ipv4.c (ffffffff81ac406a)
Location: include/crypto/hash.h:366
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_md5_hash_skb
```
```
In net/ipv6/tcp_ipv6.c (ffffffff81b67482)
Location: include/crypto/hash.h:366
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
Location: include/crypto/hash.h:374
Inline: True
Inline callers:
  - fs/verity/hash_algs.c:fsverity_hash_page
  - fs/verity/hash_algs.c:fsverity_prepare_hash_state
```
```
In security/integrity/ima/ima_crypto.c (ffffffff8153412d)
Location: include/crypto/hash.h:374
Inline: True
Inline callers:
  - security/integrity/ima/ima_crypto.c:calc_buffer_ahash_atfm
  - security/integrity/ima/ima_crypto.c:ima_calc_file_hash_atfm
```
```
In crypto/ahash.c (ffffffff81541647)
Location: include/crypto/hash.h:374
Inline: True
Inline callers:
  - crypto/ahash.c:crypto_ahash_digest
```
```
In crypto/gcm.c (ffffffff8154bf7d)
Location: include/crypto/hash.h:374
Inline: True
Inline callers:
  - crypto/gcm.c:gcm_hash
```
```
In net/ipv4/tcp_ipv4.c (ffffffff81acfafa)
Location: include/crypto/hash.h:374
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_md5_hash_skb
```
```
In net/ipv6/tcp_ipv6.c (ffffffff81b75c82)
Location: include/crypto/hash.h:374
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
Location: include/crypto/hash.h:376
Inline: True
Inline callers:
  - fs/verity/hash_algs.c:fsverity_hash_page
  - fs/verity/hash_algs.c:fsverity_prepare_hash_state
```
```
In security/integrity/ima/ima_crypto.c (ffffffff8153d11a)
Location: include/crypto/hash.h:376
Inline: True
Inline callers:
  - security/integrity/ima/ima_crypto.c:ima_calc_buffer_hash
  - security/integrity/ima/ima_crypto.c:ima_calc_file_hash_atfm
```
```
In crypto/ahash.c (ffffffff81549c77)
Location: include/crypto/hash.h:376
Inline: True
Inline callers:
  - crypto/ahash.c:crypto_ahash_digest
```
```
In crypto/gcm.c (ffffffff8155456d)
Location: include/crypto/hash.h:376
Inline: True
Inline callers:
  - crypto/gcm.c:gcm_hash
```
```
In net/ipv4/tcp_ipv4.c (ffffffff81abac4a)
Location: include/crypto/hash.h:376
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_md5_hash_skb
```
```
In net/ipv6/tcp_ipv6.c (ffffffff81b650aa)
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
<summary>In <code>5.15</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/verity/hash_algs.c (ffffffff813ff62a)
Location: include/crypto/hash.h:376
Inline: True
Inline callers:
  - fs/verity/hash_algs.c:fsverity_hash_page
  - fs/verity/hash_algs.c:fsverity_prepare_hash_state
```
```
In security/integrity/ima/ima_crypto.c (ffffffff8159bf9a)
Location: include/crypto/hash.h:376
Inline: True
Inline callers:
  - security/integrity/ima/ima_crypto.c:ima_calc_buffer_hash
  - security/integrity/ima/ima_crypto.c:ima_calc_file_hash_atfm
```
```
In crypto/ahash.c (ffffffff815aa457)
Location: include/crypto/hash.h:376
Inline: True
Inline callers:
  - crypto/ahash.c:crypto_ahash_digest
```
```
In crypto/gcm.c (ffffffff815b559d)
Location: include/crypto/hash.h:376
Inline: True
Inline callers:
  - crypto/gcm.c:gcm_hash
```
```
In net/ipv4/tcp_ipv4.c (ffffffff81b77f9a)
Location: include/crypto/hash.h:376
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_md5_hash_skb
```
```
In net/ipv6/tcp_ipv6.c (ffffffff81c2d2ea)
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
<summary>In <code>5.19</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/verity/hash_algs.c (ffffffff81473231)
Location: include/crypto/hash.h:376
Inline: True
Inline callers:
  - fs/verity/hash_algs.c:fsverity_hash_page
  - fs/verity/hash_algs.c:fsverity_prepare_hash_state
```
```
In security/integrity/ima/ima_crypto.c (ffffffff81640f74)
Location: include/crypto/hash.h:376
Inline: True
Inline callers:
  - security/integrity/ima/ima_crypto.c:ima_calc_buffer_hash
  - security/integrity/ima/ima_crypto.c:ima_calc_file_hash_atfm
```
```
In crypto/ahash.c (ffffffff816518d7)
Location: include/crypto/hash.h:376
Inline: True
Inline callers:
  - crypto/ahash.c:crypto_ahash_digest
```
```
In crypto/gcm.c (ffffffff8165e70c)
Location: include/crypto/hash.h:376
Inline: True
Inline callers:
  - crypto/gcm.c:gcm_hash
```
```
In net/ipv4/tcp_ipv4.c (ffffffff81d07bbb)
Location: include/crypto/hash.h:376
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_md5_hash_skb
```
```
In net/ipv6/tcp_ipv6.c (ffffffff81dca707)
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
<summary>In <code>6.2</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/verity/hash_algs.c (ffffffff81505083)
Location: include/crypto/hash.h:376
Inline: True
Inline callers:
  - fs/verity/hash_algs.c:fsverity_hash_page
  - fs/verity/hash_algs.c:fsverity_prepare_hash_state
```
```
In security/integrity/ima/ima_crypto.c (ffffffff816f8ee4)
Location: include/crypto/hash.h:376
Inline: True
Inline callers:
  - security/integrity/ima/ima_crypto.c:ima_calc_buffer_hash
  - security/integrity/ima/ima_crypto.c:ima_calc_file_hash_atfm
```
```
In crypto/ahash.c (ffffffff8170b507)
Location: include/crypto/hash.h:376
Inline: True
Inline callers:
  - crypto/ahash.c:crypto_ahash_digest
```
```
In crypto/gcm.c (ffffffff8171843c)
Location: include/crypto/hash.h:376
Inline: True
Inline callers:
  - crypto/gcm.c:gcm_hash
```
```
In net/ipv4/tcp_ipv4.c (ffffffff81ecd51b)
Location: include/crypto/hash.h:376
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_md5_hash_skb
```
```
In net/ipv6/tcp_ipv6.c (ffffffff81f9b741)
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
<summary>In <code>6.5</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In security/integrity/ima/ima_crypto.c (ffffffff817330e8)
Location: include/crypto/hash.h:407
Inline: True
Inline callers:
  - security/integrity/ima/ima_crypto.c:ima_calc_buffer_hash
  - security/integrity/ima/ima_crypto.c:ima_calc_file_hash_atfm
```
```
In crypto/ahash.c (ffffffff8174515a)
Location: include/crypto/hash.h:407
Inline: True
Inline callers:
  - crypto/ahash.c:crypto_ahash_digest
  - crypto/ahash.c:ahash_save_req
```
```
In crypto/gcm.c (ffffffff81753dac)
Location: include/crypto/hash.h:407
Inline: True
Inline callers:
  - crypto/gcm.c:gcm_hash
```
```
In net/ipv4/tcp_ipv4.c (ffffffff81f2c1db)
Location: include/crypto/hash.h:407
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_md5_hash_skb
```
```
In net/ipv6/tcp_ipv6.c (ffffffff81ffaea2)
Location: include/crypto/hash.h:407
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
In crypto/ahash.c (ffffffff81786ee4)
Location: include/crypto/hash.h:388
Inline: True
Inline callers:
  - crypto/ahash.c:crypto_ahash_import
  - crypto/ahash.c:crypto_ahash_digest
  - crypto/ahash.c:crypto_ahash_init
```
```
In net/ipv4/tcp_sigpool.c (ffffffff8204cf08)
Location: include/crypto/hash.h:388
Inline: True
Inline callers:
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
In fs/verity/hash_algs.c (ffff800010412058)
Location: include/crypto/hash.h:353
Inline: True
Inline callers:
  - fs/verity/hash_algs.c:fsverity_hash_page
  - fs/verity/hash_algs.c:fsverity_prepare_hash_state
```
```
In security/integrity/ima/ima_crypto.c (ffff8000105b02f8)
Location: include/crypto/hash.h:353
Inline: True
Inline callers:
  - security/integrity/ima/ima_crypto.c:ima_calc_buffer_hash
  - security/integrity/ima/ima_crypto.c:ima_calc_file_hash_atfm
```
```
In crypto/ahash.c (ffff8000105c0c18)
Location: include/crypto/hash.h:353
Inline: True
Inline callers:
  - crypto/ahash.c:crypto_ahash_digest
```
```
In crypto/gcm.c (ffff8000105ccc7c)
Location: include/crypto/hash.h:353
Inline: True
Inline callers:
  - crypto/gcm.c:gcm_hash
  - crypto/gcm.c:crypto_gcm_setkey
```
```
In net/ipv4/tcp_ipv4.c (ffff800010c8ad70)
Location: include/crypto/hash.h:353
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_md5_hash_skb
  - net/ipv4/tcp_ipv4.c:tcp_v4_md5_hash_hdr
```
```
In net/ipv6/tcp_ipv6.c (ffff800010d37c10)
Location: include/crypto/hash.h:353
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
Location: include/crypto/hash.h:353
Inline: True
Inline callers:
  - fs/verity/hash_algs.c:fsverity_hash_page
  - fs/verity/hash_algs.c:fsverity_prepare_hash_state
```
```
In security/integrity/ima/ima_crypto.c (c075fa28)
Location: include/crypto/hash.h:353
Inline: True
Inline callers:
  - security/integrity/ima/ima_crypto.c:ima_calc_buffer_hash
  - security/integrity/ima/ima_crypto.c:ima_calc_file_hash_atfm
```
```
In crypto/ahash.c (c076e6ac)
Location: include/crypto/hash.h:353
Inline: True
Inline callers:
  - crypto/ahash.c:crypto_ahash_digest
```
```
In crypto/gcm.c (c077a1ac)
Location: include/crypto/hash.h:353
Inline: True
Inline callers:
  - crypto/gcm.c:gcm_hash
  - crypto/gcm.c:crypto_gcm_setkey
```
```
In net/ipv4/tcp_ipv4.c (c0d99648)
Location: include/crypto/hash.h:353
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_md5_hash_skb
  - net/ipv4/tcp_ipv4.c:tcp_v4_md5_hash_hdr
```
```
In net/ipv6/tcp_ipv6.c (c0e38828)
Location: include/crypto/hash.h:353
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_response
  - net/ipv6/tcp_ipv6.c:tcp_v6_md5_hash_skb
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
Location: include/crypto/hash.h:353
Inline: True
Inline callers:
  - fs/verity/hash_algs.c:fsverity_hash_page
  - fs/verity/hash_algs.c:fsverity_prepare_hash_state
```
```
In security/integrity/ima/ima_crypto.c (c00000000072fdc0)
Location: include/crypto/hash.h:353
Inline: True
Inline callers:
  - security/integrity/ima/ima_crypto.c:ima_calc_buffer_hash
  - security/integrity/ima/ima_crypto.c:ima_calc_file_hash_atfm
```
```
In crypto/ahash.c (c000000000749008)
Location: include/crypto/hash.h:353
Inline: True
Inline callers:
  - crypto/ahash.c:crypto_ahash_digest
```
```
In crypto/gcm.c (c000000000757454)
Location: include/crypto/hash.h:353
Inline: True
Inline callers:
  - crypto/gcm.c:gcm_hash
  - crypto/gcm.c:crypto_gcm_setkey
```
```
In net/ipv4/tcp_ipv4.c (c000000000d99830)
Location: include/crypto/hash.h:353
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_md5_hash_skb
  - net/ipv4/tcp_ipv4.c:tcp_v4_md5_hash_hdr
```
```
In net/ipv6/tcp_ipv6.c (c000000000e69134)
Location: include/crypto/hash.h:353
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
Location: include/crypto/hash.h:353
Inline: True
Inline callers:
  - fs/verity/hash_algs.c:fsverity_hash_page
  - fs/verity/hash_algs.c:fsverity_prepare_hash_state
```
```
In security/integrity/ima/ima_crypto.c (ffffffe0003f7f9c)
Location: include/crypto/hash.h:353
Inline: True
Inline callers:
  - security/integrity/ima/ima_crypto.c:ima_calc_buffer_hash
  - security/integrity/ima/ima_crypto.c:ima_calc_file_hash_atfm
```
```
In crypto/ahash.c (ffffffe000405ab0)
Location: include/crypto/hash.h:353
Inline: True
Inline callers:
  - crypto/ahash.c:crypto_ahash_digest
```
```
In crypto/gcm.c (ffffffe000410b24)
Location: include/crypto/hash.h:353
Inline: True
Inline callers:
  - crypto/gcm.c:gcm_hash
  - crypto/gcm.c:crypto_gcm_setkey
```
```
In net/ipv4/tcp_ipv4.c (ffffffe0007ec28e)
Location: include/crypto/hash.h:353
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_md5_hash_skb
  - net/ipv4/tcp_ipv4.c:tcp_v4_md5_hash_hdr
```
```
In net/ipv6/tcp_ipv6.c (ffffffe000874048)
Location: include/crypto/hash.h:353
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
Location: include/crypto/hash.h:353
Inline: True
Inline callers:
  - fs/verity/hash_algs.c:fsverity_hash_page
  - fs/verity/hash_algs.c:fsverity_prepare_hash_state
```
```
In security/integrity/ima/ima_crypto.c (ffffffff814b051e)
Location: include/crypto/hash.h:353
Inline: True
Inline callers:
  - security/integrity/ima/ima_crypto.c:ima_calc_buffer_hash
  - security/integrity/ima/ima_crypto.c:ima_calc_file_hash_atfm
```
```
In crypto/ahash.c (ffffffff814be3a7)
Location: include/crypto/hash.h:353
Inline: True
Inline callers:
  - crypto/ahash.c:crypto_ahash_digest
```
```
In crypto/gcm.c (ffffffff814c83fd)
Location: include/crypto/hash.h:353
Inline: True
Inline callers:
  - crypto/gcm.c:gcm_hash
  - crypto/gcm.c:crypto_gcm_setkey
```
```
In net/ipv4/tcp_ipv4.c (ffffffff81977eea)
Location: include/crypto/hash.h:353
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_md5_hash_skb
  - net/ipv4/tcp_ipv4.c:tcp_v4_md5_hash_hdr
```
```
In net/ipv6/tcp_ipv6.c (ffffffff81a0d8e9)
Location: include/crypto/hash.h:353
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
Location: include/crypto/hash.h:353
Inline: True
Inline callers:
  - fs/verity/hash_algs.c:fsverity_hash_page
  - fs/verity/hash_algs.c:fsverity_prepare_hash_state
```
```
In security/integrity/ima/ima_crypto.c (ffffffff814a0f3e)
Location: include/crypto/hash.h:353
Inline: True
Inline callers:
  - security/integrity/ima/ima_crypto.c:ima_calc_buffer_hash
  - security/integrity/ima/ima_crypto.c:ima_calc_file_hash_atfm
```
```
In crypto/ahash.c (ffffffff814aedc7)
Location: include/crypto/hash.h:353
Inline: True
Inline callers:
  - crypto/ahash.c:crypto_ahash_digest
```
```
In crypto/gcm.c (ffffffff814b8e1d)
Location: include/crypto/hash.h:353
Inline: True
Inline callers:
  - crypto/gcm.c:gcm_hash
  - crypto/gcm.c:crypto_gcm_setkey
```
```
In net/ipv4/tcp_ipv4.c (ffffffff819319aa)
Location: include/crypto/hash.h:353
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_md5_hash_skb
  - net/ipv4/tcp_ipv4.c:tcp_v4_md5_hash_hdr
```
```
In net/ipv6/tcp_ipv6.c (ffffffff819ca6a9)
Location: include/crypto/hash.h:353
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
Location: include/crypto/hash.h:353
Inline: True
Inline callers:
  - fs/verity/hash_algs.c:fsverity_hash_page
  - fs/verity/hash_algs.c:fsverity_prepare_hash_state
```
```
In security/integrity/ima/ima_crypto.c (ffffffff814ac5ae)
Location: include/crypto/hash.h:353
Inline: True
Inline callers:
  - security/integrity/ima/ima_crypto.c:ima_calc_buffer_hash
  - security/integrity/ima/ima_crypto.c:ima_calc_file_hash_atfm
```
```
In crypto/ahash.c (ffffffff814ba437)
Location: include/crypto/hash.h:353
Inline: True
Inline callers:
  - crypto/ahash.c:crypto_ahash_digest
```
```
In crypto/gcm.c (ffffffff814c448d)
Location: include/crypto/hash.h:353
Inline: True
Inline callers:
  - crypto/gcm.c:gcm_hash
  - crypto/gcm.c:crypto_gcm_setkey
```
```
In net/ipv4/tcp_ipv4.c (ffffffff819e26ba)
Location: include/crypto/hash.h:353
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_md5_hash_skb
  - net/ipv4/tcp_ipv4.c:tcp_v4_md5_hash_hdr
```
```
In net/ipv6/tcp_ipv6.c (ffffffff81a78369)
Location: include/crypto/hash.h:353
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
Location: include/crypto/hash.h:353
Inline: True
Inline callers:
  - fs/verity/hash_algs.c:fsverity_hash_page
  - fs/verity/hash_algs.c:fsverity_prepare_hash_state
```
```
In security/integrity/ima/ima_crypto.c (ffffffff814c4ffe)
Location: include/crypto/hash.h:353
Inline: True
Inline callers:
  - security/integrity/ima/ima_crypto.c:ima_calc_buffer_hash
  - security/integrity/ima/ima_crypto.c:ima_calc_file_hash_atfm
```
```
In crypto/ahash.c (ffffffff814d2ee7)
Location: include/crypto/hash.h:353
Inline: True
Inline callers:
  - crypto/ahash.c:crypto_ahash_digest
```
```
In crypto/gcm.c (ffffffff814dcf5d)
Location: include/crypto/hash.h:353
Inline: True
Inline callers:
  - crypto/gcm.c:gcm_hash
  - crypto/gcm.c:crypto_gcm_setkey
```
```
In net/ipv4/tcp_ipv4.c (ffffffff819ec40a)
Location: include/crypto/hash.h:353
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_md5_hash_skb
  - net/ipv4/tcp_ipv4.c:tcp_v4_md5_hash_hdr
```
```
In net/ipv6/tcp_ipv6.c (ffffffff81a84ad9)
Location: include/crypto/hash.h:353
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_response
  - net/ipv6/tcp_ipv6.c:tcp_v6_md5_hash_skb
```
</details>
</li>
</ul>

## Differences
