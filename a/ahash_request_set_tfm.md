# Function: <code>ahash_request_set_tfm</code>

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
In security/integrity/ima/ima_crypto.c (ffffffff81397dd9)
Location: include/crypto/hash.h:511
Inline: True
Inline callers:
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
In security/integrity/ima/ima_crypto.c (ffffffff813d494b)
Location: include/crypto/hash.h:534
Inline: True
Inline callers:
  - security/integrity/ima/ima_crypto.c:ima_calc_buffer_hash
  - security/integrity/ima/ima_crypto.c:ima_calc_file_hash
```
```
In net/ipv4/tcp.c (ffffffff817d4847)
Location: include/crypto/hash.h:534
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_alloc_md5sig_pool
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
In security/integrity/ima/ima_crypto.c (ffffffff813ec39b)
Location: include/crypto/hash.h:534
Inline: True
Inline callers:
  - security/integrity/ima/ima_crypto.c:ima_calc_buffer_hash
  - security/integrity/ima/ima_crypto.c:ima_calc_file_hash
```
```
In arch/x86/power/hibernate_64.c (ffffffff8178d600)
Location: include/crypto/hash.h:534
Inline: True
Inline callers:
  - arch/x86/power/hibernate_64.c:get_e820_md5
```
```
In net/ipv4/tcp.c (ffffffff81804589)
Location: include/crypto/hash.h:534
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_alloc_md5sig_pool
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
In security/integrity/ima/ima_crypto.c (ffffffff813f8754)
Location: include/crypto/hash.h:540
Inline: True
Inline callers:
  - security/integrity/ima/ima_crypto.c:ima_calc_buffer_hash
  - security/integrity/ima/ima_crypto.c:ima_calc_file_hash
```
```
In arch/x86/power/hibernate_64.c (ffffffff817ab790)
Location: include/crypto/hash.h:540
Inline: True
Inline callers:
  - arch/x86/power/hibernate_64.c:get_e820_md5
```
```
In net/ipv4/tcp.c (ffffffff81824817)
Location: include/crypto/hash.h:540
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_alloc_md5sig_pool
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
In security/integrity/ima/ima_crypto.c (ffffffff81420ad8)
Location: include/crypto/hash.h:548
Inline: True
Inline callers:
  - security/integrity/ima/ima_crypto.c:ima_calc_buffer_hash
  - security/integrity/ima/ima_crypto.c:ima_calc_file_hash
```
```
In crypto/gcm.c (ffffffff81438aa1)
Location: include/crypto/hash.h:548
Inline: True
Inline callers:
  - crypto/gcm.c:gcm_hash
```
```
In arch/x86/power/hibernate_64.c (ffffffff81822d00)
Location: include/crypto/hash.h:548
Inline: True
Inline callers:
  - arch/x86/power/hibernate_64.c:get_e820_md5
```
```
In net/ipv4/tcp.c (ffffffff818a35a8)
Location: include/crypto/hash.h:548
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_alloc_md5sig_pool
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
In security/integrity/ima/ima_crypto.c (ffffffff81452f5f)
Location: include/crypto/hash.h:547
Inline: True
Inline callers:
  - security/integrity/ima/ima_crypto.c:ima_calc_buffer_hash
  - security/integrity/ima/ima_crypto.c:ima_calc_file_hash
```
```
In crypto/gcm.c (ffffffff8146b9cf)
Location: include/crypto/hash.h:547
Inline: True
Inline callers:
  - crypto/gcm.c:gcm_hash
```
```
In arch/x86/power/hibernate_64.c (ffffffff8186d029)
Location: include/crypto/hash.h:547
Inline: True
Inline callers:
  - arch/x86/power/hibernate_64.c:get_e820_md5
```
```
In net/ipv4/tcp.c (ffffffff818f7ae5)
Location: include/crypto/hash.h:547
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
In security/integrity/ima/ima_crypto.c (ffffffff814700bd)
Location: include/crypto/hash.h:559
Inline: True
Inline callers:
  - security/integrity/ima/ima_crypto.c:ima_calc_buffer_hash
  - security/integrity/ima/ima_crypto.c:ima_calc_file_hash
```
```
In crypto/gcm.c (ffffffff81488f2f)
Location: include/crypto/hash.h:559
Inline: True
Inline callers:
  - crypto/gcm.c:gcm_hash
```
```
In net/ipv4/tcp.c (ffffffff81926155)
Location: include/crypto/hash.h:559
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
In security/integrity/ima/ima_crypto.c (ffffffff8149dab5)
Location: include/crypto/hash.h:558
Inline: True
Inline callers:
  - security/integrity/ima/ima_crypto.c:ima_calc_buffer_hash
  - security/integrity/ima/ima_crypto.c:ima_calc_file_hash_atfm
```
```
In crypto/gcm.c (ffffffff814b6bda)
Location: include/crypto/hash.h:558
Inline: True
Inline callers:
  - crypto/gcm.c:gcm_hash
```
```
In net/ipv4/tcp.c (ffffffff81987289)
Location: include/crypto/hash.h:558
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
In fs/verity/enable.c (ffffffff8134f610)
Location: include/crypto/hash.h:558
Inline: True
Inline callers:
  - fs/verity/enable.c:build_merkle_tree
```
```
In fs/verity/hash_algs.c (ffffffff81350500)
Location: include/crypto/hash.h:558
Inline: True
Inline callers:
  - fs/verity/hash_algs.c:fsverity_hash_buffer
  - fs/verity/hash_algs.c:fsverity_prepare_hash_state
```
```
In fs/verity/verify.c (ffffffff81351966)
Location: include/crypto/hash.h:558
Inline: True
Inline callers:
  - fs/verity/verify.c:fsverity_verify_page
```
```
In security/integrity/ima/ima_crypto.c (ffffffff814b7ef5)
Location: include/crypto/hash.h:558
Inline: True
Inline callers:
  - security/integrity/ima/ima_crypto.c:ima_calc_buffer_hash
  - security/integrity/ima/ima_crypto.c:ima_calc_file_hash_atfm
```
```
In crypto/gcm.c (ffffffff814cfdfa)
Location: include/crypto/hash.h:558
Inline: True
Inline callers:
  - crypto/gcm.c:gcm_hash
```
```
In net/ipv4/tcp.c (ffffffff819bda29)
Location: include/crypto/hash.h:558
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
In fs/verity/hash_algs.c (ffffffff81396eb9)
Location: include/crypto/hash.h:571
Inline: True
Inline callers:
  - fs/verity/hash_algs.c:fsverity_hash_buffer
  - fs/verity/hash_algs.c:fsverity_prepare_hash_state
```
```
In security/integrity/ima/ima_crypto.c (ffffffff81516f2b)
Location: include/crypto/hash.h:571
Inline: True
Inline callers:
  - security/integrity/ima/ima_crypto.c:calc_buffer_ahash_atfm
  - security/integrity/ima/ima_crypto.c:ima_calc_file_hash_atfm
```
```
In crypto/gcm.c (ffffffff8152efda)
Location: include/crypto/hash.h:571
Inline: True
Inline callers:
  - crypto/gcm.c:gcm_hash
```
```
In net/ipv4/tcp.c (ffffffff81aa85cc)
Location: include/crypto/hash.h:571
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
In fs/verity/hash_algs.c (ffffffff813a8ae9)
Location: include/crypto/hash.h:579
Inline: True
Inline callers:
  - fs/verity/hash_algs.c:fsverity_hash_buffer
  - fs/verity/hash_algs.c:fsverity_prepare_hash_state
```
```
In security/integrity/ima/ima_crypto.c (ffffffff815340eb)
Location: include/crypto/hash.h:579
Inline: True
Inline callers:
  - security/integrity/ima/ima_crypto.c:calc_buffer_ahash_atfm
  - security/integrity/ima/ima_crypto.c:ima_calc_file_hash_atfm
```
```
In crypto/gcm.c (ffffffff8154bf5a)
Location: include/crypto/hash.h:579
Inline: True
Inline callers:
  - crypto/gcm.c:gcm_hash
```
```
In net/ipv4/tcp.c (ffffffff81ab2b3c)
Location: include/crypto/hash.h:579
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
In fs/verity/hash_algs.c (ffffffff813afb5c)
Location: include/crypto/hash.h:581
Inline: True
Inline callers:
  - fs/verity/hash_algs.c:fsverity_hash_buffer
  - fs/verity/hash_algs.c:fsverity_prepare_hash_state
```
```
In security/integrity/ima/ima_crypto.c (ffffffff8153d0d1)
Location: include/crypto/hash.h:581
Inline: True
Inline callers:
  - security/integrity/ima/ima_crypto.c:ima_calc_buffer_hash
  - security/integrity/ima/ima_crypto.c:ima_calc_file_hash_atfm
```
```
In crypto/gcm.c (ffffffff8155454a)
Location: include/crypto/hash.h:581
Inline: True
Inline callers:
  - crypto/gcm.c:gcm_hash
```
```
In net/ipv4/tcp.c (ffffffff81a9dd8c)
Location: include/crypto/hash.h:581
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
In fs/verity/hash_algs.c (ffffffff813ff74c)
Location: include/crypto/hash.h:581
Inline: True
Inline callers:
  - fs/verity/hash_algs.c:fsverity_hash_buffer
  - fs/verity/hash_algs.c:fsverity_prepare_hash_state
```
```
In security/integrity/ima/ima_crypto.c (ffffffff8159bf51)
Location: include/crypto/hash.h:581
Inline: True
Inline callers:
  - security/integrity/ima/ima_crypto.c:ima_calc_buffer_hash
  - security/integrity/ima/ima_crypto.c:ima_calc_file_hash_atfm
```
```
In crypto/gcm.c (ffffffff815b557a)
Location: include/crypto/hash.h:581
Inline: True
Inline callers:
  - crypto/gcm.c:gcm_hash
```
```
In net/ipv4/tcp.c (ffffffff81b597ee)
Location: include/crypto/hash.h:581
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
In fs/verity/hash_algs.c (ffffffff8147339e)
Location: include/crypto/hash.h:581
Inline: True
Inline callers:
  - fs/verity/hash_algs.c:fsverity_hash_buffer
  - fs/verity/hash_algs.c:fsverity_prepare_hash_state
```
```
In security/integrity/ima/ima_crypto.c (ffffffff81640f2d)
Location: include/crypto/hash.h:581
Inline: True
Inline callers:
  - security/integrity/ima/ima_crypto.c:ima_calc_buffer_hash
  - security/integrity/ima/ima_crypto.c:ima_calc_file_hash_atfm
```
```
In crypto/gcm.c (ffffffff8165e6e9)
Location: include/crypto/hash.h:581
Inline: True
Inline callers:
  - crypto/gcm.c:gcm_hash
```
```
In net/ipv4/tcp.c (ffffffff81ce8258)
Location: include/crypto/hash.h:581
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
In fs/verity/hash_algs.c (ffffffff8150522e)
Location: include/crypto/hash.h:581
Inline: True
Inline callers:
  - fs/verity/hash_algs.c:fsverity_hash_buffer
  - fs/verity/hash_algs.c:fsverity_prepare_hash_state
```
```
In security/integrity/ima/ima_crypto.c (ffffffff816f8e9d)
Location: include/crypto/hash.h:581
Inline: True
Inline callers:
  - security/integrity/ima/ima_crypto.c:ima_calc_buffer_hash
  - security/integrity/ima/ima_crypto.c:ima_calc_file_hash_atfm
```
```
In crypto/gcm.c (ffffffff81718419)
Location: include/crypto/hash.h:581
Inline: True
Inline callers:
  - crypto/gcm.c:gcm_hash
```
```
In net/ipv4/tcp.c (ffffffff81eabbb2)
Location: include/crypto/hash.h:581
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
In security/integrity/ima/ima_crypto.c (ffffffff81733096)
Location: include/crypto/hash.h:631
Inline: True
Inline callers:
  - security/integrity/ima/ima_crypto.c:ima_calc_buffer_hash
  - security/integrity/ima/ima_crypto.c:ima_calc_file_hash_atfm
```
```
In crypto/ahash.c (ffffffff81744e90)
Location: include/crypto/hash.h:631
Inline: True
Inline callers:
  - crypto/ahash.c:ahash_save_req
```
```
In crypto/gcm.c (ffffffff81753d89)
Location: include/crypto/hash.h:631
Inline: True
Inline callers:
  - crypto/gcm.c:gcm_hash
```
```
In net/ipv4/tcp.c (ffffffff81f0a372)
Location: include/crypto/hash.h:631
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
In security/integrity/ima/ima_crypto.c (ffffffff81773aa6)
Location: include/crypto/hash.h:563
Inline: True
Inline callers:
  - security/integrity/ima/ima_crypto.c:ima_calc_buffer_hash
  - security/integrity/ima/ima_crypto.c:ima_calc_file_hash_atfm
```
```
In crypto/ahash.c (ffffffff817872b6)
Location: include/crypto/hash.h:563
Inline: True
```
```
In crypto/gcm.c (ffffffff81796ad8)
Location: include/crypto/hash.h:563
Inline: True
Inline callers:
  - crypto/gcm.c:gcm_hash
```
```
In net/ipv4/tcp_sigpool.c (ffffffff8204c9be)
Location: include/crypto/hash.h:563
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
In fs/verity/enable.c (ffff800010411008)
Location: include/crypto/hash.h:558
Inline: True
Inline callers:
  - fs/verity/enable.c:build_merkle_tree
```
```
In fs/verity/hash_algs.c (ffff8000104121b8)
Location: include/crypto/hash.h:558
Inline: True
Inline callers:
  - fs/verity/hash_algs.c:fsverity_hash_buffer
  - fs/verity/hash_algs.c:fsverity_prepare_hash_state
```
```
In fs/verity/verify.c (ffff8000104138d0)
Location: include/crypto/hash.h:558
Inline: True
Inline callers:
  - fs/verity/verify.c:fsverity_verify_bio
  - fs/verity/verify.c:fsverity_verify_page
```
```
In security/integrity/ima/ima_crypto.c (ffff8000105b02c0)
Location: include/crypto/hash.h:558
Inline: True
Inline callers:
  - security/integrity/ima/ima_crypto.c:ima_calc_buffer_hash
  - security/integrity/ima/ima_crypto.c:ima_calc_file_hash_atfm
```
```
In crypto/gcm.c (ffff8000105ccc70)
Location: include/crypto/hash.h:558
Inline: True
Inline callers:
  - crypto/gcm.c:gcm_hash
```
```
In net/ipv4/tcp.c (ffff800010c6f5e8)
Location: include/crypto/hash.h:558
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
In fs/verity/enable.c (c05dd5dc)
Location: include/crypto/hash.h:558
Inline: True
Inline callers:
  - fs/verity/enable.c:build_merkle_tree
```
```
In fs/verity/hash_algs.c (c05de834)
Location: include/crypto/hash.h:558
Inline: True
Inline callers:
  - fs/verity/hash_algs.c:fsverity_hash_buffer
  - fs/verity/hash_algs.c:fsverity_prepare_hash_state
```
```
In fs/verity/verify.c (c05dfb7c)
Location: include/crypto/hash.h:558
Inline: True
Inline callers:
  - fs/verity/verify.c:fsverity_verify_bio
  - fs/verity/verify.c:fsverity_verify_page
```
```
In security/integrity/ima/ima_crypto.c (c075f9e0)
Location: include/crypto/hash.h:558
Inline: True
Inline callers:
  - security/integrity/ima/ima_crypto.c:ima_calc_buffer_hash
  - security/integrity/ima/ima_crypto.c:ima_calc_file_hash_atfm
```
```
In crypto/gcm.c (c077a19c)
Location: include/crypto/hash.h:558
Inline: True
Inline callers:
  - crypto/gcm.c:gcm_hash
```
```
In net/ipv4/tcp.c (c0d7e7ec)
Location: include/crypto/hash.h:558
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
In fs/verity/enable.c (c00000000051eaf0)
Location: include/crypto/hash.h:558
Inline: True
Inline callers:
  - fs/verity/enable.c:build_merkle_tree
```
```
In fs/verity/hash_algs.c (c00000000051ff18)
Location: include/crypto/hash.h:558
Inline: True
Inline callers:
  - fs/verity/hash_algs.c:fsverity_hash_buffer
  - fs/verity/hash_algs.c:fsverity_prepare_hash_state
```
```
In fs/verity/verify.c (c000000000521b44)
Location: include/crypto/hash.h:558
Inline: True
Inline callers:
  - fs/verity/verify.c:fsverity_verify_page
```
```
In security/integrity/ima/ima_crypto.c (c00000000072fd70)
Location: include/crypto/hash.h:558
Inline: True
Inline callers:
  - security/integrity/ima/ima_crypto.c:ima_calc_buffer_hash
  - security/integrity/ima/ima_crypto.c:ima_calc_file_hash_atfm
```
```
In crypto/gcm.c (c000000000757454)
Location: include/crypto/hash.h:558
Inline: True
Inline callers:
  - crypto/gcm.c:gcm_hash
```
```
In net/ipv4/tcp.c (c000000000d76390)
Location: include/crypto/hash.h:558
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
In fs/verity/enable.c (ffffffe0002b9496)
Location: include/crypto/hash.h:558
Inline: True
Inline callers:
  - fs/verity/enable.c:build_merkle_tree
```
```
In fs/verity/hash_algs.c (ffffffe0002ba224)
Location: include/crypto/hash.h:558
Inline: True
Inline callers:
  - fs/verity/hash_algs.c:fsverity_hash_buffer
  - fs/verity/hash_algs.c:fsverity_prepare_hash_state
```
```
In fs/verity/verify.c (ffffffe0002bb2c6)
Location: include/crypto/hash.h:558
Inline: True
Inline callers:
  - fs/verity/verify.c:fsverity_verify_bio
  - fs/verity/verify.c:fsverity_verify_page
```
```
In security/integrity/ima/ima_crypto.c (ffffffe0003f7f5a)
Location: include/crypto/hash.h:558
Inline: True
Inline callers:
  - security/integrity/ima/ima_crypto.c:ima_calc_buffer_hash
  - security/integrity/ima/ima_crypto.c:ima_calc_file_hash_atfm
```
```
In crypto/gcm.c (ffffffe000410afa)
Location: include/crypto/hash.h:558
Inline: True
Inline callers:
  - crypto/gcm.c:gcm_hash
```
```
In net/ipv4/tcp.c (ffffffe0007d4956)
Location: include/crypto/hash.h:558
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
In fs/verity/enable.c (ffffffff81347bf0)
Location: include/crypto/hash.h:558
Inline: True
Inline callers:
  - fs/verity/enable.c:build_merkle_tree
```
```
In fs/verity/hash_algs.c (ffffffff81348ae0)
Location: include/crypto/hash.h:558
Inline: True
Inline callers:
  - fs/verity/hash_algs.c:fsverity_hash_buffer
  - fs/verity/hash_algs.c:fsverity_prepare_hash_state
```
```
In fs/verity/verify.c (ffffffff81349f46)
Location: include/crypto/hash.h:558
Inline: True
Inline callers:
  - fs/verity/verify.c:fsverity_verify_page
```
```
In security/integrity/ima/ima_crypto.c (ffffffff814b04d5)
Location: include/crypto/hash.h:558
Inline: True
Inline callers:
  - security/integrity/ima/ima_crypto.c:ima_calc_buffer_hash
  - security/integrity/ima/ima_crypto.c:ima_calc_file_hash_atfm
```
```
In crypto/gcm.c (ffffffff814c83da)
Location: include/crypto/hash.h:558
Inline: True
Inline callers:
  - crypto/gcm.c:gcm_hash
```
```
In net/ipv4/tcp.c (ffffffff8195d899)
Location: include/crypto/hash.h:558
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
In fs/verity/enable.c (ffffffff813388d0)
Location: include/crypto/hash.h:558
Inline: True
Inline callers:
  - fs/verity/enable.c:build_merkle_tree
```
```
In fs/verity/hash_algs.c (ffffffff813397c0)
Location: include/crypto/hash.h:558
Inline: True
Inline callers:
  - fs/verity/hash_algs.c:fsverity_hash_buffer
  - fs/verity/hash_algs.c:fsverity_prepare_hash_state
```
```
In fs/verity/verify.c (ffffffff8133ac26)
Location: include/crypto/hash.h:558
Inline: True
Inline callers:
  - fs/verity/verify.c:fsverity_verify_page
```
```
In security/integrity/ima/ima_crypto.c (ffffffff814a0ef5)
Location: include/crypto/hash.h:558
Inline: True
Inline callers:
  - security/integrity/ima/ima_crypto.c:ima_calc_buffer_hash
  - security/integrity/ima/ima_crypto.c:ima_calc_file_hash_atfm
```
```
In crypto/gcm.c (ffffffff814b8dfa)
Location: include/crypto/hash.h:558
Inline: True
Inline callers:
  - crypto/gcm.c:gcm_hash
```
```
In net/ipv4/tcp.c (ffffffff81917389)
Location: include/crypto/hash.h:558
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
In fs/verity/enable.c (ffffffff813456c0)
Location: include/crypto/hash.h:558
Inline: True
Inline callers:
  - fs/verity/enable.c:build_merkle_tree
```
```
In fs/verity/hash_algs.c (ffffffff813465b0)
Location: include/crypto/hash.h:558
Inline: True
Inline callers:
  - fs/verity/hash_algs.c:fsverity_hash_buffer
  - fs/verity/hash_algs.c:fsverity_prepare_hash_state
```
```
In fs/verity/verify.c (ffffffff81347a16)
Location: include/crypto/hash.h:558
Inline: True
Inline callers:
  - fs/verity/verify.c:fsverity_verify_page
```
```
In security/integrity/ima/ima_crypto.c (ffffffff814ac565)
Location: include/crypto/hash.h:558
Inline: True
Inline callers:
  - security/integrity/ima/ima_crypto.c:ima_calc_buffer_hash
  - security/integrity/ima/ima_crypto.c:ima_calc_file_hash_atfm
```
```
In crypto/gcm.c (ffffffff814c446a)
Location: include/crypto/hash.h:558
Inline: True
Inline callers:
  - crypto/gcm.c:gcm_hash
```
```
In net/ipv4/tcp.c (ffffffff819c8069)
Location: include/crypto/hash.h:558
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
In fs/verity/enable.c (ffffffff813589a0)
Location: include/crypto/hash.h:558
Inline: True
Inline callers:
  - fs/verity/enable.c:build_merkle_tree
```
```
In fs/verity/hash_algs.c (ffffffff81359890)
Location: include/crypto/hash.h:558
Inline: True
Inline callers:
  - fs/verity/hash_algs.c:fsverity_hash_buffer
  - fs/verity/hash_algs.c:fsverity_prepare_hash_state
```
```
In fs/verity/verify.c (ffffffff8135ad16)
Location: include/crypto/hash.h:558
Inline: True
Inline callers:
  - fs/verity/verify.c:fsverity_verify_page
```
```
In security/integrity/ima/ima_crypto.c (ffffffff814c4fb5)
Location: include/crypto/hash.h:558
Inline: True
Inline callers:
  - security/integrity/ima/ima_crypto.c:ima_calc_buffer_hash
  - security/integrity/ima/ima_crypto.c:ima_calc_file_hash_atfm
```
```
In crypto/gcm.c (ffffffff814dcf3a)
Location: include/crypto/hash.h:558
Inline: True
Inline callers:
  - crypto/gcm.c:gcm_hash
```
```
In net/ipv4/tcp.c (ffffffff819d1bb9)
Location: include/crypto/hash.h:558
Inline: True
Inline callers:
  - net/ipv4/tcp.c:__tcp_alloc_md5sig_pool
```
</details>
</li>
</ul>

## Differences
