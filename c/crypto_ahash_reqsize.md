# Function: <code>crypto_ahash_reqsize</code>

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
In security/integrity/ima/ima_crypto.c (0)
Location: include/crypto/hash.h:355
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
Location: include/crypto/hash.h:378
Inline: True
```
```
In net/ipv4/tcp.c (0)
Location: include/crypto/hash.h:378
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
Location: include/crypto/hash.h:378
Inline: True
```
```
In arch/x86/power/hibernate_64.c (ffffffff8178d6a8)
Location: include/crypto/hash.h:378
Inline: True
Inline callers:
  - arch/x86/power/hibernate_64.c:get_e820_md5
```
```
In net/ipv4/tcp.c (0)
Location: include/crypto/hash.h:378
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
Location: include/crypto/hash.h:384
Inline: True
```
```
In arch/x86/power/hibernate_64.c (ffffffff817ab838)
Location: include/crypto/hash.h:384
Inline: True
Inline callers:
  - arch/x86/power/hibernate_64.c:get_e820_md5
```
```
In net/ipv4/tcp.c (0)
Location: include/crypto/hash.h:384
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
Location: include/crypto/hash.h:388
Inline: True
```
```
In crypto/gcm.c (0)
Location: include/crypto/hash.h:388
Inline: True
```
```
In arch/x86/power/hibernate_64.c (ffffffff81822da8)
Location: include/crypto/hash.h:388
Inline: True
Inline callers:
  - arch/x86/power/hibernate_64.c:get_e820_md5
```
```
In net/ipv4/tcp.c (0)
Location: include/crypto/hash.h:388
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
In security/integrity/ima/ima_crypto.c (ffffffff81452f46)
Location: include/crypto/hash.h:387
Inline: True
Inline callers:
  - security/integrity/ima/ima_crypto.c:ima_calc_buffer_hash
  - security/integrity/ima/ima_crypto.c:ima_calc_file_hash
```
```
In crypto/gcm.c (ffffffff8146b007)
Location: include/crypto/hash.h:387
Inline: True
Inline callers:
  - crypto/gcm.c:crypto_gcm_init_tfm
```
```
In arch/x86/power/hibernate_64.c (ffffffff8186cfdb)
Location: include/crypto/hash.h:387
Inline: True
Inline callers:
  - arch/x86/power/hibernate_64.c:get_e820_md5
  - arch/x86/power/hibernate_64.c:get_e820_md5
```
```
In net/ipv4/tcp.c (ffffffff818f7aca)
Location: include/crypto/hash.h:387
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_alloc_md5sig_pool
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
In security/integrity/ima/ima_crypto.c (ffffffff814700a4)
Location: include/crypto/hash.h:391
Inline: True
Inline callers:
  - security/integrity/ima/ima_crypto.c:ima_calc_buffer_hash
  - security/integrity/ima/ima_crypto.c:ima_calc_file_hash
```
```
In crypto/gcm.c (ffffffff81488907)
Location: include/crypto/hash.h:391
Inline: True
Inline callers:
  - crypto/gcm.c:crypto_gcm_init_tfm
```
```
In net/ipv4/tcp.c (ffffffff8192613e)
Location: include/crypto/hash.h:391
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_alloc_md5sig_pool
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
In security/integrity/ima/ima_crypto.c (ffffffff8149da9d)
Location: include/crypto/hash.h:390
Inline: True
Inline callers:
  - security/integrity/ima/ima_crypto.c:ima_calc_buffer_hash
  - security/integrity/ima/ima_crypto.c:ima_calc_file_hash_atfm
```
```
In crypto/gcm.c (ffffffff814b66ec)
Location: include/crypto/hash.h:390
Inline: True
Inline callers:
  - crypto/gcm.c:crypto_gcm_init_tfm
```
```
In net/ipv4/tcp.c (ffffffff8198726f)
Location: include/crypto/hash.h:390
Inline: True
Inline callers:
  - net/ipv4/tcp.c:__tcp_alloc_md5sig_pool
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
In fs/verity/enable.c (ffffffff8134f5f7)
Location: include/crypto/hash.h:390
Inline: True
Inline callers:
  - fs/verity/enable.c:build_merkle_tree
```
```
In fs/verity/hash_algs.c (ffffffff813504de)
Location: include/crypto/hash.h:390
Inline: True
Inline callers:
  - fs/verity/hash_algs.c:fsverity_hash_buffer
  - fs/verity/hash_algs.c:fsverity_prepare_hash_state
```
```
In fs/verity/verify.c (ffffffff8135193e)
Location: include/crypto/hash.h:390
Inline: True
Inline callers:
  - fs/verity/verify.c:fsverity_verify_page
```
```
In security/integrity/ima/ima_crypto.c (ffffffff814b7edd)
Location: include/crypto/hash.h:390
Inline: True
Inline callers:
  - security/integrity/ima/ima_crypto.c:ima_calc_buffer_hash
  - security/integrity/ima/ima_crypto.c:ima_calc_file_hash_atfm
```
```
In crypto/gcm.c (ffffffff814cf90c)
Location: include/crypto/hash.h:390
Inline: True
Inline callers:
  - crypto/gcm.c:crypto_gcm_init_tfm
```
```
In net/ipv4/tcp.c (ffffffff819bda0f)
Location: include/crypto/hash.h:390
Inline: True
Inline callers:
  - net/ipv4/tcp.c:__tcp_alloc_md5sig_pool
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
In fs/verity/hash_algs.c (ffffffff8139698d)
Location: include/crypto/hash.h:403
Inline: True
Inline callers:
  - fs/verity/hash_algs.c:fsverity_get_hash_alg
```
```
In security/integrity/ima/ima_crypto.c (ffffffff81516f0f)
Location: include/crypto/hash.h:403
Inline: True
Inline callers:
  - security/integrity/ima/ima_crypto.c:calc_buffer_ahash_atfm
  - security/integrity/ima/ima_crypto.c:ima_calc_file_hash_atfm
```
```
In crypto/gcm.c (ffffffff8152eb0c)
Location: include/crypto/hash.h:403
Inline: True
Inline callers:
  - crypto/gcm.c:crypto_gcm_init_tfm
```
```
In net/ipv4/tcp.c (ffffffff81aa85b2)
Location: include/crypto/hash.h:403
Inline: True
Inline callers:
  - net/ipv4/tcp.c:__tcp_alloc_md5sig_pool
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
In fs/verity/hash_algs.c (ffffffff813a85bd)
Location: include/crypto/hash.h:411
Inline: True
Inline callers:
  - fs/verity/hash_algs.c:fsverity_get_hash_alg
```
```
In security/integrity/ima/ima_crypto.c (ffffffff815340cf)
Location: include/crypto/hash.h:411
Inline: True
Inline callers:
  - security/integrity/ima/ima_crypto.c:calc_buffer_ahash_atfm
  - security/integrity/ima/ima_crypto.c:ima_calc_file_hash_atfm
```
```
In crypto/gcm.c (ffffffff8154ba8c)
Location: include/crypto/hash.h:411
Inline: True
Inline callers:
  - crypto/gcm.c:crypto_gcm_init_tfm
```
```
In net/ipv4/tcp.c (ffffffff81ab2b22)
Location: include/crypto/hash.h:411
Inline: True
Inline callers:
  - net/ipv4/tcp.c:__tcp_alloc_md5sig_pool
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
In fs/verity/hash_algs.c (ffffffff813af60d)
Location: include/crypto/hash.h:413
Inline: True
Inline callers:
  - fs/verity/hash_algs.c:fsverity_get_hash_alg
```
```
In security/integrity/ima/ima_crypto.c (ffffffff8153d0b9)
Location: include/crypto/hash.h:413
Inline: True
Inline callers:
  - security/integrity/ima/ima_crypto.c:ima_calc_buffer_hash
  - security/integrity/ima/ima_crypto.c:ima_calc_file_hash_atfm
```
```
In crypto/gcm.c (ffffffff8155408c)
Location: include/crypto/hash.h:413
Inline: True
Inline callers:
  - crypto/gcm.c:crypto_gcm_init_tfm
```
```
In net/ipv4/tcp.c (ffffffff81a9dd72)
Location: include/crypto/hash.h:413
Inline: True
Inline callers:
  - net/ipv4/tcp.c:__tcp_alloc_md5sig_pool
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
In fs/verity/hash_algs.c (ffffffff813ff1d7)
Location: include/crypto/hash.h:413
Inline: True
Inline callers:
  - fs/verity/hash_algs.c:fsverity_get_hash_alg
```
```
In security/integrity/ima/ima_crypto.c (ffffffff8159bf39)
Location: include/crypto/hash.h:413
Inline: True
Inline callers:
  - security/integrity/ima/ima_crypto.c:ima_calc_buffer_hash
  - security/integrity/ima/ima_crypto.c:ima_calc_file_hash_atfm
```
```
In crypto/gcm.c (ffffffff815b50bc)
Location: include/crypto/hash.h:413
Inline: True
Inline callers:
  - crypto/gcm.c:crypto_gcm_init_tfm
```
```
In net/ipv4/tcp.c (ffffffff81b597d7)
Location: include/crypto/hash.h:413
Inline: True
Inline callers:
  - net/ipv4/tcp.c:__tcp_alloc_md5sig_pool
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
Location: include/crypto/hash.h:413
Inline: True
Inline callers:
  - fs/verity/hash_algs.c:fsverity_hash_buffer
  - fs/verity/hash_algs.c:fsverity_prepare_hash_state
  - fs/verity/hash_algs.c:fsverity_get_hash_alg
```
```
In security/integrity/ima/ima_crypto.c (ffffffff81640f13)
Location: include/crypto/hash.h:413
Inline: True
Inline callers:
  - security/integrity/ima/ima_crypto.c:ima_calc_buffer_hash
  - security/integrity/ima/ima_crypto.c:ima_calc_file_hash_atfm
```
```
In crypto/gcm.c (ffffffff8165e15c)
Location: include/crypto/hash.h:413
Inline: True
Inline callers:
  - crypto/gcm.c:crypto_gcm_init_tfm
```
```
In net/ipv4/tcp.c (ffffffff81ce823d)
Location: include/crypto/hash.h:413
Inline: True
Inline callers:
  - net/ipv4/tcp.c:__tcp_alloc_md5sig_pool
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
Location: include/crypto/hash.h:413
Inline: True
Inline callers:
  - fs/verity/hash_algs.c:fsverity_hash_buffer
  - fs/verity/hash_algs.c:fsverity_prepare_hash_state
  - fs/verity/hash_algs.c:fsverity_get_hash_alg
```
```
In security/integrity/ima/ima_crypto.c (ffffffff816f8e83)
Location: include/crypto/hash.h:413
Inline: True
Inline callers:
  - security/integrity/ima/ima_crypto.c:ima_calc_buffer_hash
  - security/integrity/ima/ima_crypto.c:ima_calc_file_hash_atfm
```
```
In crypto/gcm.c (ffffffff81717acc)
Location: include/crypto/hash.h:413
Inline: True
Inline callers:
  - crypto/gcm.c:crypto_gcm_init_tfm
```
```
In net/ipv4/tcp.c (ffffffff81eabb97)
Location: include/crypto/hash.h:413
Inline: True
Inline callers:
  - net/ipv4/tcp.c:__tcp_alloc_md5sig_pool
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
In security/integrity/ima/ima_crypto.c (ffffffff8173307e)
Location: include/crypto/hash.h:444
Inline: True
Inline callers:
  - security/integrity/ima/ima_crypto.c:ima_calc_buffer_hash
  - security/integrity/ima/ima_crypto.c:ima_calc_file_hash_atfm
```
```
In crypto/ahash.c (ffffffff81744e56)
Location: include/crypto/hash.h:444
Inline: True
Inline callers:
  - crypto/ahash.c:ahash_save_req
```
```
In crypto/gcm.c (ffffffff817534ac)
Location: include/crypto/hash.h:444
Inline: True
Inline callers:
  - crypto/gcm.c:crypto_gcm_init_tfm
```
```
In net/ipv4/tcp.c (ffffffff81f0a357)
Location: include/crypto/hash.h:444
Inline: True
Inline callers:
  - net/ipv4/tcp.c:__tcp_alloc_md5sig_pool
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
In security/integrity/ima/ima_crypto.c (ffffffff81773a8e)
Location: include/crypto/hash.h:425
Inline: True
Inline callers:
  - security/integrity/ima/ima_crypto.c:ima_calc_buffer_hash
  - security/integrity/ima/ima_crypto.c:ima_calc_file_hash_atfm
```
```
In crypto/ahash.c (ffffffff8178725d)
Location: include/crypto/hash.h:425
Inline: True
```
```
In crypto/gcm.c (ffffffff8179537c)
Location: include/crypto/hash.h:425
Inline: True
Inline callers:
  - crypto/gcm.c:crypto_gcm_init_tfm
```
```
In net/ipv4/tcp_sigpool.c (ffffffff8204c9a4)
Location: include/crypto/hash.h:425
Inline: True
Inline callers:
  - net/ipv4/tcp_sigpool.c:tcp_sigpool_start
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
In fs/verity/enable.c (ffff800010410ff4)
Location: include/crypto/hash.h:390
Inline: True
Inline callers:
  - fs/verity/enable.c:build_merkle_tree
```
```
In fs/verity/hash_algs.c (ffff8000104121a4)
Location: include/crypto/hash.h:390
Inline: True
Inline callers:
  - fs/verity/hash_algs.c:fsverity_hash_buffer
  - fs/verity/hash_algs.c:fsverity_prepare_hash_state
```
```
In fs/verity/verify.c (ffff8000104138bc)
Location: include/crypto/hash.h:390
Inline: True
Inline callers:
  - fs/verity/verify.c:fsverity_verify_bio
  - fs/verity/verify.c:fsverity_verify_page
```
```
In security/integrity/ima/ima_crypto.c (ffff8000105b02ac)
Location: include/crypto/hash.h:390
Inline: True
Inline callers:
  - security/integrity/ima/ima_crypto.c:ima_calc_buffer_hash
  - security/integrity/ima/ima_crypto.c:ima_calc_file_hash_atfm
```
```
In crypto/gcm.c (ffff8000105cba34)
Location: include/crypto/hash.h:390
Inline: True
Inline callers:
  - crypto/gcm.c:crypto_gcm_init_tfm
```
```
In net/ipv4/tcp.c (ffff800010c6f5d4)
Location: include/crypto/hash.h:390
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_alloc_md5sig_pool
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
In fs/verity/enable.c (c05dd5c0)
Location: include/crypto/hash.h:390
Inline: True
Inline callers:
  - fs/verity/enable.c:build_merkle_tree
```
```
In fs/verity/hash_algs.c (c05de81c)
Location: include/crypto/hash.h:390
Inline: True
Inline callers:
  - fs/verity/hash_algs.c:fsverity_hash_buffer
  - fs/verity/hash_algs.c:fsverity_prepare_hash_state
```
```
In fs/verity/verify.c (c05dfb68)
Location: include/crypto/hash.h:390
Inline: True
Inline callers:
  - fs/verity/verify.c:fsverity_verify_bio
  - fs/verity/verify.c:fsverity_verify_page
```
```
In security/integrity/ima/ima_crypto.c (c075f9cc)
Location: include/crypto/hash.h:390
Inline: True
Inline callers:
  - security/integrity/ima/ima_crypto.c:ima_calc_buffer_hash
  - security/integrity/ima/ima_crypto.c:ima_calc_file_hash_atfm
```
```
In crypto/gcm.c (c0779460)
Location: include/crypto/hash.h:390
Inline: True
Inline callers:
  - crypto/gcm.c:crypto_gcm_init_tfm
```
```
In net/ipv4/tcp.c (c0d7e7d4)
Location: include/crypto/hash.h:390
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_alloc_md5sig_pool
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
In fs/verity/enable.c (c00000000051ead8)
Location: include/crypto/hash.h:390
Inline: True
Inline callers:
  - fs/verity/enable.c:build_merkle_tree
```
```
In fs/verity/hash_algs.c (c00000000051ff00)
Location: include/crypto/hash.h:390
Inline: True
Inline callers:
  - fs/verity/hash_algs.c:fsverity_hash_buffer
  - fs/verity/hash_algs.c:fsverity_prepare_hash_state
```
```
In fs/verity/verify.c (c000000000521b2c)
Location: include/crypto/hash.h:390
Inline: True
Inline callers:
  - fs/verity/verify.c:fsverity_verify_page
```
```
In security/integrity/ima/ima_crypto.c (c00000000072fd58)
Location: include/crypto/hash.h:390
Inline: True
Inline callers:
  - security/integrity/ima/ima_crypto.c:ima_calc_buffer_hash
  - security/integrity/ima/ima_crypto.c:ima_calc_file_hash_atfm
```
```
In crypto/gcm.c (c000000000756c30)
Location: include/crypto/hash.h:390
Inline: True
Inline callers:
  - crypto/gcm.c:crypto_gcm_init_tfm
```
```
In net/ipv4/tcp.c (c000000000d7637c)
Location: include/crypto/hash.h:390
Inline: True
Inline callers:
  - net/ipv4/tcp.c:__tcp_alloc_md5sig_pool
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
In fs/verity/enable.c (ffffffe0002b947e)
Location: include/crypto/hash.h:390
Inline: True
Inline callers:
  - fs/verity/enable.c:build_merkle_tree
```
```
In fs/verity/hash_algs.c (ffffffe0002ba214)
Location: include/crypto/hash.h:390
Inline: True
Inline callers:
  - fs/verity/hash_algs.c:fsverity_hash_buffer
  - fs/verity/hash_algs.c:fsverity_prepare_hash_state
```
```
In fs/verity/verify.c (ffffffe0002bb2b2)
Location: include/crypto/hash.h:390
Inline: True
Inline callers:
  - fs/verity/verify.c:fsverity_verify_bio
  - fs/verity/verify.c:fsverity_verify_page
```
```
In security/integrity/ima/ima_crypto.c (ffffffe0003f7f44)
Location: include/crypto/hash.h:390
Inline: True
Inline callers:
  - security/integrity/ima/ima_crypto.c:ima_calc_buffer_hash
  - security/integrity/ima/ima_crypto.c:ima_calc_file_hash_atfm
```
```
In crypto/gcm.c (ffffffe00040fd72)
Location: include/crypto/hash.h:390
Inline: True
Inline callers:
  - crypto/gcm.c:crypto_gcm_init_tfm
```
```
In net/ipv4/tcp.c (ffffffe0007d4994)
Location: include/crypto/hash.h:390
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_alloc_md5sig_pool
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
In fs/verity/enable.c (ffffffff81347bd7)
Location: include/crypto/hash.h:390
Inline: True
Inline callers:
  - fs/verity/enable.c:build_merkle_tree
```
```
In fs/verity/hash_algs.c (ffffffff81348abe)
Location: include/crypto/hash.h:390
Inline: True
Inline callers:
  - fs/verity/hash_algs.c:fsverity_hash_buffer
  - fs/verity/hash_algs.c:fsverity_prepare_hash_state
```
```
In fs/verity/verify.c (ffffffff81349f1e)
Location: include/crypto/hash.h:390
Inline: True
Inline callers:
  - fs/verity/verify.c:fsverity_verify_page
```
```
In security/integrity/ima/ima_crypto.c (ffffffff814b04bd)
Location: include/crypto/hash.h:390
Inline: True
Inline callers:
  - security/integrity/ima/ima_crypto.c:ima_calc_buffer_hash
  - security/integrity/ima/ima_crypto.c:ima_calc_file_hash_atfm
```
```
In crypto/gcm.c (ffffffff814c7eec)
Location: include/crypto/hash.h:390
Inline: True
Inline callers:
  - crypto/gcm.c:crypto_gcm_init_tfm
```
```
In net/ipv4/tcp.c (ffffffff8195d87f)
Location: include/crypto/hash.h:390
Inline: True
Inline callers:
  - net/ipv4/tcp.c:__tcp_alloc_md5sig_pool
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
In fs/verity/enable.c (ffffffff813388b7)
Location: include/crypto/hash.h:390
Inline: True
Inline callers:
  - fs/verity/enable.c:build_merkle_tree
```
```
In fs/verity/hash_algs.c (ffffffff8133979e)
Location: include/crypto/hash.h:390
Inline: True
Inline callers:
  - fs/verity/hash_algs.c:fsverity_hash_buffer
  - fs/verity/hash_algs.c:fsverity_prepare_hash_state
```
```
In fs/verity/verify.c (ffffffff8133abfe)
Location: include/crypto/hash.h:390
Inline: True
Inline callers:
  - fs/verity/verify.c:fsverity_verify_page
```
```
In security/integrity/ima/ima_crypto.c (ffffffff814a0edd)
Location: include/crypto/hash.h:390
Inline: True
Inline callers:
  - security/integrity/ima/ima_crypto.c:ima_calc_buffer_hash
  - security/integrity/ima/ima_crypto.c:ima_calc_file_hash_atfm
```
```
In crypto/gcm.c (ffffffff814b890c)
Location: include/crypto/hash.h:390
Inline: True
Inline callers:
  - crypto/gcm.c:crypto_gcm_init_tfm
```
```
In net/ipv4/tcp.c (ffffffff8191736f)
Location: include/crypto/hash.h:390
Inline: True
Inline callers:
  - net/ipv4/tcp.c:__tcp_alloc_md5sig_pool
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
In fs/verity/enable.c (ffffffff813456a7)
Location: include/crypto/hash.h:390
Inline: True
Inline callers:
  - fs/verity/enable.c:build_merkle_tree
```
```
In fs/verity/hash_algs.c (ffffffff8134658e)
Location: include/crypto/hash.h:390
Inline: True
Inline callers:
  - fs/verity/hash_algs.c:fsverity_hash_buffer
  - fs/verity/hash_algs.c:fsverity_prepare_hash_state
```
```
In fs/verity/verify.c (ffffffff813479ee)
Location: include/crypto/hash.h:390
Inline: True
Inline callers:
  - fs/verity/verify.c:fsverity_verify_page
```
```
In security/integrity/ima/ima_crypto.c (ffffffff814ac54d)
Location: include/crypto/hash.h:390
Inline: True
Inline callers:
  - security/integrity/ima/ima_crypto.c:ima_calc_buffer_hash
  - security/integrity/ima/ima_crypto.c:ima_calc_file_hash_atfm
```
```
In crypto/gcm.c (ffffffff814c3f7c)
Location: include/crypto/hash.h:390
Inline: True
Inline callers:
  - crypto/gcm.c:crypto_gcm_init_tfm
```
```
In net/ipv4/tcp.c (ffffffff819c804f)
Location: include/crypto/hash.h:390
Inline: True
Inline callers:
  - net/ipv4/tcp.c:__tcp_alloc_md5sig_pool
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
In fs/verity/enable.c (ffffffff81358987)
Location: include/crypto/hash.h:390
Inline: True
Inline callers:
  - fs/verity/enable.c:build_merkle_tree
```
```
In fs/verity/hash_algs.c (ffffffff8135986e)
Location: include/crypto/hash.h:390
Inline: True
Inline callers:
  - fs/verity/hash_algs.c:fsverity_hash_buffer
  - fs/verity/hash_algs.c:fsverity_prepare_hash_state
```
```
In fs/verity/verify.c (ffffffff8135acee)
Location: include/crypto/hash.h:390
Inline: True
Inline callers:
  - fs/verity/verify.c:fsverity_verify_page
```
```
In security/integrity/ima/ima_crypto.c (ffffffff814c4f9d)
Location: include/crypto/hash.h:390
Inline: True
Inline callers:
  - security/integrity/ima/ima_crypto.c:ima_calc_buffer_hash
  - security/integrity/ima/ima_crypto.c:ima_calc_file_hash_atfm
```
```
In crypto/gcm.c (ffffffff814dca4c)
Location: include/crypto/hash.h:390
Inline: True
Inline callers:
  - crypto/gcm.c:crypto_gcm_init_tfm
```
```
In net/ipv4/tcp.c (ffffffff819d1b9f)
Location: include/crypto/hash.h:390
Inline: True
Inline callers:
  - net/ipv4/tcp.c:__tcp_alloc_md5sig_pool
```
</details>
</li>
</ul>

## Differences
