# Function: <code>ahash_request_set_callback</code>

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
In security/integrity/ima/ima_crypto.c (ffffffff81397e0c)
Location: include/crypto/hash.h:584
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
In security/integrity/ima/ima_crypto.c (ffffffff813d4980)
Location: include/crypto/hash.h:612
Inline: True
Inline callers:
  - security/integrity/ima/ima_crypto.c:ima_calc_buffer_hash
  - security/integrity/ima/ima_crypto.c:ima_calc_file_hash
```
```
In net/ipv4/tcp.c (ffffffff817d484f)
Location: include/crypto/hash.h:612
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
In security/integrity/ima/ima_crypto.c (ffffffff813ec3d0)
Location: include/crypto/hash.h:612
Inline: True
Inline callers:
  - security/integrity/ima/ima_crypto.c:ima_calc_buffer_hash
  - security/integrity/ima/ima_crypto.c:ima_calc_file_hash
```
```
In arch/x86/power/hibernate_64.c (ffffffff8178d658)
Location: include/crypto/hash.h:612
Inline: True
Inline callers:
  - arch/x86/power/hibernate_64.c:get_e820_md5
```
```
In net/ipv4/tcp.c (ffffffff81804591)
Location: include/crypto/hash.h:612
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
In security/integrity/ima/ima_crypto.c (ffffffff813f877f)
Location: include/crypto/hash.h:618
Inline: True
Inline callers:
  - security/integrity/ima/ima_crypto.c:ima_calc_buffer_hash
  - security/integrity/ima/ima_crypto.c:ima_calc_file_hash
```
```
In crypto/ahash.c (ffffffff81403862)
Location: include/crypto/hash.h:618
Inline: True
Inline callers:
  - crypto/ahash.c:ahash_restore_req
```
```
In arch/x86/power/hibernate_64.c (ffffffff817ab7e8)
Location: include/crypto/hash.h:618
Inline: True
Inline callers:
  - arch/x86/power/hibernate_64.c:get_e820_md5
```
```
In net/ipv4/tcp.c (ffffffff8182481f)
Location: include/crypto/hash.h:618
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
In security/integrity/ima/ima_crypto.c (ffffffff81420b09)
Location: include/crypto/hash.h:626
Inline: True
Inline callers:
  - security/integrity/ima/ima_crypto.c:ima_calc_buffer_hash
  - security/integrity/ima/ima_crypto.c:ima_calc_file_hash
```
```
In crypto/ahash.c (ffffffff8142bfc2)
Location: include/crypto/hash.h:626
Inline: True
Inline callers:
  - crypto/ahash.c:ahash_restore_req
```
```
In crypto/gcm.c (ffffffff81438a89)
Location: include/crypto/hash.h:626
Inline: True
Inline callers:
  - crypto/gcm.c:gcm_hash
  - crypto/gcm.c:gcm_hash_init_continue
  - crypto/gcm.c:gcm_hash_assoc_continue
  - crypto/gcm.c:gcm_hash_assoc_remain_continue
  - crypto/gcm.c:gcm_hash_crypt_continue
  - crypto/gcm.c:gcm_hash_crypt_remain_continue
```
```
In arch/x86/power/hibernate_64.c (ffffffff81822d58)
Location: include/crypto/hash.h:626
Inline: True
Inline callers:
  - arch/x86/power/hibernate_64.c:get_e820_md5
```
```
In net/ipv4/tcp.c (ffffffff818a3622)
Location: include/crypto/hash.h:626
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
In security/integrity/ima/ima_crypto.c (ffffffff81452f8d)
Location: include/crypto/hash.h:625
Inline: True
Inline callers:
  - security/integrity/ima/ima_crypto.c:ima_calc_buffer_hash
  - security/integrity/ima/ima_crypto.c:ima_calc_file_hash
```
```
In crypto/ahash.c (ffffffff8145ecaa)
Location: include/crypto/hash.h:625
Inline: True
Inline callers:
  - crypto/ahash.c:ahash_restore_req
```
```
In crypto/gcm.c (ffffffff8146b9ec)
Location: include/crypto/hash.h:625
Inline: True
Inline callers:
  - crypto/gcm.c:gcm_hash
  - crypto/gcm.c:gcm_hash_init_continue
  - crypto/gcm.c:gcm_hash_assoc_continue
  - crypto/gcm.c:gcm_hash_assoc_remain_continue
  - crypto/gcm.c:gcm_hash_crypt_continue
```
```
In arch/x86/power/hibernate_64.c (ffffffff8186d033)
Location: include/crypto/hash.h:625
Inline: True
Inline callers:
  - arch/x86/power/hibernate_64.c:get_e820_md5
```
```
In net/ipv4/tcp.c (ffffffff818f7b05)
Location: include/crypto/hash.h:625
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
In security/integrity/ima/ima_crypto.c (ffffffff814700f2)
Location: include/crypto/hash.h:637
Inline: True
Inline callers:
  - security/integrity/ima/ima_crypto.c:ima_calc_buffer_hash
  - security/integrity/ima/ima_crypto.c:ima_calc_file_hash
```
```
In crypto/ahash.c (ffffffff8147c61a)
Location: include/crypto/hash.h:637
Inline: True
Inline callers:
  - crypto/ahash.c:ahash_restore_req
```
```
In crypto/gcm.c (ffffffff81488f4c)
Location: include/crypto/hash.h:637
Inline: True
Inline callers:
  - crypto/gcm.c:gcm_hash
  - crypto/gcm.c:gcm_hash_update
```
```
In net/ipv4/tcp.c (ffffffff81926175)
Location: include/crypto/hash.h:637
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
In security/integrity/ima/ima_crypto.c (ffffffff8149dae2)
Location: include/crypto/hash.h:636
Inline: True
Inline callers:
  - security/integrity/ima/ima_crypto.c:ima_calc_buffer_hash
  - security/integrity/ima/ima_crypto.c:ima_calc_file_hash_atfm
```
```
In crypto/ahash.c (ffffffff814aa78a)
Location: include/crypto/hash.h:636
Inline: True
Inline callers:
  - crypto/ahash.c:ahash_restore_req
```
```
In crypto/gcm.c (ffffffff814b6bf7)
Location: include/crypto/hash.h:636
Inline: True
Inline callers:
  - crypto/gcm.c:gcm_hash
  - crypto/gcm.c:gcm_hash_update
```
```
In net/ipv4/tcp.c (ffffffff819872ac)
Location: include/crypto/hash.h:636
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
In fs/verity/hash_algs.c (ffffffff81350510)
Location: include/crypto/hash.h:636
Inline: True
Inline callers:
  - fs/verity/hash_algs.c:fsverity_hash_buffer
  - fs/verity/hash_algs.c:fsverity_hash_page
  - fs/verity/hash_algs.c:fsverity_prepare_hash_state
```
```
In security/integrity/ima/ima_crypto.c (ffffffff814b7f22)
Location: include/crypto/hash.h:636
Inline: True
Inline callers:
  - security/integrity/ima/ima_crypto.c:ima_calc_buffer_hash
  - security/integrity/ima/ima_crypto.c:ima_calc_file_hash_atfm
```
```
In crypto/ahash.c (ffffffff814c544a)
Location: include/crypto/hash.h:636
Inline: True
Inline callers:
  - crypto/ahash.c:ahash_restore_req
```
```
In crypto/gcm.c (ffffffff814cfe17)
Location: include/crypto/hash.h:636
Inline: True
Inline callers:
  - crypto/gcm.c:gcm_hash
  - crypto/gcm.c:gcm_hash_update
```
```
In net/ipv4/tcp.c (ffffffff819bda4c)
Location: include/crypto/hash.h:636
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
In fs/verity/hash_algs.c (ffffffff81396ed7)
Location: include/crypto/hash.h:649
Inline: True
Inline callers:
  - fs/verity/hash_algs.c:fsverity_hash_buffer
  - fs/verity/hash_algs.c:fsverity_hash_page
  - fs/verity/hash_algs.c:fsverity_prepare_hash_state
```
```
In security/integrity/ima/ima_crypto.c (ffffffff81516f51)
Location: include/crypto/hash.h:649
Inline: True
Inline callers:
  - security/integrity/ima/ima_crypto.c:calc_buffer_ahash_atfm
  - security/integrity/ima/ima_crypto.c:ima_calc_file_hash_atfm
```
```
In crypto/ahash.c (ffffffff8152453a)
Location: include/crypto/hash.h:649
Inline: True
Inline callers:
  - crypto/ahash.c:ahash_restore_req
```
```
In crypto/gcm.c (ffffffff8152eff7)
Location: include/crypto/hash.h:649
Inline: True
Inline callers:
  - crypto/gcm.c:gcm_hash
  - crypto/gcm.c:gcm_hash_len
  - crypto/gcm.c:gcm_hash_update
```
```
In net/ipv4/tcp.c (ffffffff81aa85ef)
Location: include/crypto/hash.h:649
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
In fs/verity/hash_algs.c (ffffffff813a8b07)
Location: include/crypto/hash.h:657
Inline: True
Inline callers:
  - fs/verity/hash_algs.c:fsverity_hash_buffer
  - fs/verity/hash_algs.c:fsverity_hash_page
  - fs/verity/hash_algs.c:fsverity_prepare_hash_state
```
```
In security/integrity/ima/ima_crypto.c (ffffffff81534111)
Location: include/crypto/hash.h:657
Inline: True
Inline callers:
  - security/integrity/ima/ima_crypto.c:calc_buffer_ahash_atfm
  - security/integrity/ima/ima_crypto.c:ima_calc_file_hash_atfm
```
```
In crypto/ahash.c (ffffffff8154140a)
Location: include/crypto/hash.h:657
Inline: True
Inline callers:
  - crypto/ahash.c:ahash_restore_req
```
```
In crypto/gcm.c (ffffffff8154bf77)
Location: include/crypto/hash.h:657
Inline: True
Inline callers:
  - crypto/gcm.c:gcm_hash
  - crypto/gcm.c:gcm_hash_len
  - crypto/gcm.c:gcm_hash_update
```
```
In net/ipv4/tcp.c (ffffffff81ab2b5f)
Location: include/crypto/hash.h:657
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
In fs/verity/hash_algs.c (ffffffff813afb77)
Location: include/crypto/hash.h:659
Inline: True
Inline callers:
  - fs/verity/hash_algs.c:fsverity_hash_buffer
  - fs/verity/hash_algs.c:fsverity_hash_page
  - fs/verity/hash_algs.c:fsverity_prepare_hash_state
```
```
In security/integrity/ima/ima_crypto.c (ffffffff8153d0fe)
Location: include/crypto/hash.h:659
Inline: True
Inline callers:
  - security/integrity/ima/ima_crypto.c:ima_calc_buffer_hash
  - security/integrity/ima/ima_crypto.c:ima_calc_file_hash_atfm
```
```
In crypto/ahash.c (ffffffff81549a3a)
Location: include/crypto/hash.h:659
Inline: True
Inline callers:
  - crypto/ahash.c:ahash_restore_req
```
```
In crypto/gcm.c (ffffffff81554567)
Location: include/crypto/hash.h:659
Inline: True
Inline callers:
  - crypto/gcm.c:gcm_hash
  - crypto/gcm.c:gcm_hash_crypt_remain_continue
  - crypto/gcm.c:gcm_hash_update
```
```
In net/ipv4/tcp.c (ffffffff81a9ddaf)
Location: include/crypto/hash.h:659
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
In fs/verity/hash_algs.c (ffffffff813ff767)
Location: include/crypto/hash.h:659
Inline: True
Inline callers:
  - fs/verity/hash_algs.c:fsverity_hash_buffer
  - fs/verity/hash_algs.c:fsverity_hash_page
  - fs/verity/hash_algs.c:fsverity_prepare_hash_state
```
```
In security/integrity/ima/ima_crypto.c (ffffffff8159bf7e)
Location: include/crypto/hash.h:659
Inline: True
Inline callers:
  - security/integrity/ima/ima_crypto.c:ima_calc_buffer_hash
  - security/integrity/ima/ima_crypto.c:ima_calc_file_hash_atfm
```
```
In crypto/ahash.c (ffffffff815aa21a)
Location: include/crypto/hash.h:659
Inline: True
Inline callers:
  - crypto/ahash.c:ahash_restore_req
```
```
In crypto/gcm.c (ffffffff815b5597)
Location: include/crypto/hash.h:659
Inline: True
Inline callers:
  - crypto/gcm.c:gcm_hash
  - crypto/gcm.c:gcm_hash_crypt_remain_continue
  - crypto/gcm.c:gcm_hash_update
```
```
In net/ipv4/tcp.c (ffffffff81b597fe)
Location: include/crypto/hash.h:659
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
In fs/verity/hash_algs.c (ffffffff814733b6)
Location: include/crypto/hash.h:659
Inline: True
Inline callers:
  - fs/verity/hash_algs.c:fsverity_hash_buffer
  - fs/verity/hash_algs.c:fsverity_hash_page
  - fs/verity/hash_algs.c:fsverity_prepare_hash_state
```
```
In security/integrity/ima/ima_crypto.c (ffffffff81640f58)
Location: include/crypto/hash.h:659
Inline: True
Inline callers:
  - security/integrity/ima/ima_crypto.c:ima_calc_buffer_hash
  - security/integrity/ima/ima_crypto.c:ima_calc_file_hash_atfm
```
```
In crypto/ahash.c (ffffffff8165165a)
Location: include/crypto/hash.h:659
Inline: True
Inline callers:
  - crypto/ahash.c:ahash_restore_req
```
```
In crypto/gcm.c (ffffffff8165e706)
Location: include/crypto/hash.h:659
Inline: True
Inline callers:
  - crypto/gcm.c:gcm_hash
  - crypto/gcm.c:gcm_hash_crypt_remain_continue
  - crypto/gcm.c:gcm_hash_update
```
```
In net/ipv4/tcp.c (ffffffff81ce8268)
Location: include/crypto/hash.h:659
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
In fs/verity/hash_algs.c (ffffffff81505246)
Location: include/crypto/hash.h:659
Inline: True
Inline callers:
  - fs/verity/hash_algs.c:fsverity_hash_buffer
  - fs/verity/hash_algs.c:fsverity_hash_page
  - fs/verity/hash_algs.c:fsverity_prepare_hash_state
```
```
In security/integrity/ima/ima_crypto.c (ffffffff816f8ec8)
Location: include/crypto/hash.h:659
Inline: True
Inline callers:
  - security/integrity/ima/ima_crypto.c:ima_calc_buffer_hash
  - security/integrity/ima/ima_crypto.c:ima_calc_file_hash_atfm
```
```
In crypto/ahash.c (ffffffff8170b32a)
Location: include/crypto/hash.h:659
Inline: True
Inline callers:
  - crypto/ahash.c:ahash_restore_req
```
```
In crypto/gcm.c (ffffffff81718436)
Location: include/crypto/hash.h:659
Inline: True
Inline callers:
  - crypto/gcm.c:gcm_hash
  - crypto/gcm.c:gcm_hash_crypt_remain_continue
  - crypto/gcm.c:gcm_hash_update
```
```
In net/ipv4/tcp.c (ffffffff81eabbc2)
Location: include/crypto/hash.h:659
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
In security/integrity/ima/ima_crypto.c (ffffffff817330c8)
Location: include/crypto/hash.h:709
Inline: True
Inline callers:
  - security/integrity/ima/ima_crypto.c:ima_calc_buffer_hash
  - security/integrity/ima/ima_crypto.c:ima_calc_file_hash_atfm
```
```
In crypto/ahash.c (ffffffff81744e9d)
Location: include/crypto/hash.h:709
Inline: True
Inline callers:
  - crypto/ahash.c:ahash_save_req
```
```
In crypto/gcm.c (ffffffff81753da6)
Location: include/crypto/hash.h:709
Inline: True
Inline callers:
  - crypto/gcm.c:gcm_hash
  - crypto/gcm.c:gcm_hash_len
  - crypto/gcm.c:gcm_hash_update
```
```
In net/ipv4/tcp.c (ffffffff81f0a382)
Location: include/crypto/hash.h:709
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
In security/integrity/ima/ima_crypto.c (ffffffff81773ad8)
Location: include/crypto/hash.h:641
Inline: True
Inline callers:
  - security/integrity/ima/ima_crypto.c:ima_calc_buffer_hash
  - security/integrity/ima/ima_crypto.c:ima_calc_file_hash_atfm
```
```
In crypto/ahash.c (ffffffff817872c9)
Location: include/crypto/hash.h:641
Inline: True
```
```
In crypto/gcm.c (ffffffff81796afa)
Location: include/crypto/hash.h:641
Inline: True
Inline callers:
  - crypto/gcm.c:gcm_hash
  - crypto/gcm.c:gcm_hash_init_continue
  - crypto/gcm.c:gcm_hash_assoc_continue
  - crypto/gcm.c:gcm_hash_assoc_remain_continue
  - crypto/gcm.c:gcm_hash_crypt_continue
  - crypto/gcm.c:gcm_hash_len
```
```
In net/ipv4/tcp_sigpool.c (ffffffff8204c9cb)
Location: include/crypto/hash.h:641
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
In fs/verity/hash_algs.c (ffff8000104121d4)
Location: include/crypto/hash.h:636
Inline: True
Inline callers:
  - fs/verity/hash_algs.c:fsverity_hash_buffer
  - fs/verity/hash_algs.c:fsverity_hash_page
  - fs/verity/hash_algs.c:fsverity_prepare_hash_state
```
```
In security/integrity/ima/ima_crypto.c (ffff8000105b02dc)
Location: include/crypto/hash.h:636
Inline: True
Inline callers:
  - security/integrity/ima/ima_crypto.c:ima_calc_buffer_hash
  - security/integrity/ima/ima_crypto.c:ima_calc_file_hash_atfm
```
```
In crypto/ahash.c (ffff8000105c0088)
Location: include/crypto/hash.h:636
Inline: True
Inline callers:
  - crypto/ahash.c:ahash_restore_req
```
```
In crypto/gcm.c (ffff8000105ccc74)
Location: include/crypto/hash.h:636
Inline: True
Inline callers:
  - crypto/gcm.c:gcm_hash
  - crypto/gcm.c:gcm_hash_update
```
```
In net/ipv4/tcp.c (ffff800010c6f600)
Location: include/crypto/hash.h:636
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
In fs/verity/hash_algs.c (c05de850)
Location: include/crypto/hash.h:636
Inline: True
Inline callers:
  - fs/verity/hash_algs.c:fsverity_hash_buffer
  - fs/verity/hash_algs.c:fsverity_hash_page
  - fs/verity/hash_algs.c:fsverity_prepare_hash_state
```
```
In security/integrity/ima/ima_crypto.c (c075fa08)
Location: include/crypto/hash.h:636
Inline: True
Inline callers:
  - security/integrity/ima/ima_crypto.c:ima_calc_buffer_hash
  - security/integrity/ima/ima_crypto.c:ima_calc_file_hash_atfm
```
```
In crypto/ahash.c (c076dc54)
Location: include/crypto/hash.h:636
Inline: True
Inline callers:
  - crypto/ahash.c:ahash_restore_req
```
```
In crypto/gcm.c (c077a1a8)
Location: include/crypto/hash.h:636
Inline: True
Inline callers:
  - crypto/gcm.c:gcm_hash
  - crypto/gcm.c:gcm_hash_update
```
```
In net/ipv4/tcp.c (c0d7e808)
Location: include/crypto/hash.h:636
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
In fs/verity/hash_algs.c (c00000000051ff3c)
Location: include/crypto/hash.h:636
Inline: True
Inline callers:
  - fs/verity/hash_algs.c:fsverity_hash_buffer
  - fs/verity/hash_algs.c:fsverity_hash_page
  - fs/verity/hash_algs.c:fsverity_prepare_hash_state
```
```
In security/integrity/ima/ima_crypto.c (c00000000072fda4)
Location: include/crypto/hash.h:636
Inline: True
Inline callers:
  - security/integrity/ima/ima_crypto.c:ima_calc_buffer_hash
  - security/integrity/ima/ima_crypto.c:ima_calc_file_hash_atfm
```
```
In crypto/ahash.c (c00000000074804c)
Location: include/crypto/hash.h:636
Inline: True
Inline callers:
  - crypto/ahash.c:ahash_restore_req
```
```
In crypto/gcm.c (c000000000757454)
Location: include/crypto/hash.h:636
Inline: True
Inline callers:
  - crypto/gcm.c:gcm_hash
  - crypto/gcm.c:gcm_hash_update
```
```
In net/ipv4/tcp.c (c000000000d763a0)
Location: include/crypto/hash.h:636
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
In fs/verity/hash_algs.c (ffffffe0002ba240)
Location: include/crypto/hash.h:636
Inline: True
Inline callers:
  - fs/verity/hash_algs.c:fsverity_hash_buffer
  - fs/verity/hash_algs.c:fsverity_hash_page
  - fs/verity/hash_algs.c:fsverity_prepare_hash_state
```
```
In security/integrity/ima/ima_crypto.c (ffffffe0003f7f82)
Location: include/crypto/hash.h:636
Inline: True
Inline callers:
  - security/integrity/ima/ima_crypto.c:ima_calc_buffer_hash
  - security/integrity/ima/ima_crypto.c:ima_calc_file_hash_atfm
```
```
In crypto/ahash.c (ffffffe00040507e)
Location: include/crypto/hash.h:636
Inline: True
Inline callers:
  - crypto/ahash.c:ahash_restore_req
```
```
In crypto/gcm.c (ffffffe000410b0a)
Location: include/crypto/hash.h:636
Inline: True
Inline callers:
  - crypto/gcm.c:gcm_hash
  - crypto/gcm.c:gcm_hash_update
```
```
In net/ipv4/tcp.c (ffffffe0007d49b2)
Location: include/crypto/hash.h:636
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
In fs/verity/hash_algs.c (ffffffff81348af0)
Location: include/crypto/hash.h:636
Inline: True
Inline callers:
  - fs/verity/hash_algs.c:fsverity_hash_buffer
  - fs/verity/hash_algs.c:fsverity_hash_page
  - fs/verity/hash_algs.c:fsverity_prepare_hash_state
```
```
In security/integrity/ima/ima_crypto.c (ffffffff814b0502)
Location: include/crypto/hash.h:636
Inline: True
Inline callers:
  - security/integrity/ima/ima_crypto.c:ima_calc_buffer_hash
  - security/integrity/ima/ima_crypto.c:ima_calc_file_hash_atfm
```
```
In crypto/ahash.c (ffffffff814bda2a)
Location: include/crypto/hash.h:636
Inline: True
Inline callers:
  - crypto/ahash.c:ahash_restore_req
```
```
In crypto/gcm.c (ffffffff814c83f7)
Location: include/crypto/hash.h:636
Inline: True
Inline callers:
  - crypto/gcm.c:gcm_hash
  - crypto/gcm.c:gcm_hash_update
```
```
In net/ipv4/tcp.c (ffffffff8195d8bc)
Location: include/crypto/hash.h:636
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
In fs/verity/hash_algs.c (ffffffff813397d0)
Location: include/crypto/hash.h:636
Inline: True
Inline callers:
  - fs/verity/hash_algs.c:fsverity_hash_buffer
  - fs/verity/hash_algs.c:fsverity_hash_page
  - fs/verity/hash_algs.c:fsverity_prepare_hash_state
```
```
In security/integrity/ima/ima_crypto.c (ffffffff814a0f22)
Location: include/crypto/hash.h:636
Inline: True
Inline callers:
  - security/integrity/ima/ima_crypto.c:ima_calc_buffer_hash
  - security/integrity/ima/ima_crypto.c:ima_calc_file_hash_atfm
```
```
In crypto/ahash.c (ffffffff814ae44a)
Location: include/crypto/hash.h:636
Inline: True
Inline callers:
  - crypto/ahash.c:ahash_restore_req
```
```
In crypto/gcm.c (ffffffff814b8e17)
Location: include/crypto/hash.h:636
Inline: True
Inline callers:
  - crypto/gcm.c:gcm_hash
  - crypto/gcm.c:gcm_hash_update
```
```
In net/ipv4/tcp.c (ffffffff819173ac)
Location: include/crypto/hash.h:636
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
In fs/verity/hash_algs.c (ffffffff813465c0)
Location: include/crypto/hash.h:636
Inline: True
Inline callers:
  - fs/verity/hash_algs.c:fsverity_hash_buffer
  - fs/verity/hash_algs.c:fsverity_hash_page
  - fs/verity/hash_algs.c:fsverity_prepare_hash_state
```
```
In security/integrity/ima/ima_crypto.c (ffffffff814ac592)
Location: include/crypto/hash.h:636
Inline: True
Inline callers:
  - security/integrity/ima/ima_crypto.c:ima_calc_buffer_hash
  - security/integrity/ima/ima_crypto.c:ima_calc_file_hash_atfm
```
```
In crypto/ahash.c (ffffffff814b9aba)
Location: include/crypto/hash.h:636
Inline: True
Inline callers:
  - crypto/ahash.c:ahash_restore_req
```
```
In crypto/gcm.c (ffffffff814c4487)
Location: include/crypto/hash.h:636
Inline: True
Inline callers:
  - crypto/gcm.c:gcm_hash
  - crypto/gcm.c:gcm_hash_update
```
```
In net/ipv4/tcp.c (ffffffff819c808c)
Location: include/crypto/hash.h:636
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
In fs/verity/hash_algs.c (ffffffff813598a0)
Location: include/crypto/hash.h:636
Inline: True
Inline callers:
  - fs/verity/hash_algs.c:fsverity_hash_buffer
  - fs/verity/hash_algs.c:fsverity_hash_page
  - fs/verity/hash_algs.c:fsverity_prepare_hash_state
```
```
In security/integrity/ima/ima_crypto.c (ffffffff814c4fe2)
Location: include/crypto/hash.h:636
Inline: True
Inline callers:
  - security/integrity/ima/ima_crypto.c:ima_calc_buffer_hash
  - security/integrity/ima/ima_crypto.c:ima_calc_file_hash_atfm
```
```
In crypto/ahash.c (ffffffff814d256a)
Location: include/crypto/hash.h:636
Inline: True
Inline callers:
  - crypto/ahash.c:ahash_restore_req
```
```
In crypto/gcm.c (ffffffff814dcf57)
Location: include/crypto/hash.h:636
Inline: True
Inline callers:
  - crypto/gcm.c:gcm_hash
  - crypto/gcm.c:gcm_hash_update
```
```
In net/ipv4/tcp.c (ffffffff819d1bdc)
Location: include/crypto/hash.h:636
Inline: True
Inline callers:
  - net/ipv4/tcp.c:__tcp_alloc_md5sig_pool
```
</details>
</li>
</ul>

## Differences
