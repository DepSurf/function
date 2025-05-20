# Function: <code>ahash_request_alloc</code>

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
In security/integrity/ima/ima_crypto.c (ffffffff81397dbf)
Location: include/crypto/hash.h:530
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
In security/integrity/ima/ima_crypto.c (ffffffff813d4923)
Location: include/crypto/hash.h:552
Inline: True
Inline callers:
  - security/integrity/ima/ima_crypto.c:ima_calc_buffer_hash
  - security/integrity/ima/ima_crypto.c:ima_calc_file_hash
```
```
In net/ipv4/tcp.c (ffffffff817d4828)
Location: include/crypto/hash.h:552
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
In security/integrity/ima/ima_crypto.c (ffffffff813ec373)
Location: include/crypto/hash.h:552
Inline: True
Inline callers:
  - security/integrity/ima/ima_crypto.c:ima_calc_buffer_hash
  - security/integrity/ima/ima_crypto.c:ima_calc_file_hash
```
```
In net/ipv4/tcp.c (ffffffff8180456a)
Location: include/crypto/hash.h:552
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
In security/integrity/ima/ima_crypto.c (ffffffff813f872f)
Location: include/crypto/hash.h:558
Inline: True
Inline callers:
  - security/integrity/ima/ima_crypto.c:ima_calc_buffer_hash
  - security/integrity/ima/ima_crypto.c:ima_calc_file_hash
```
```
In net/ipv4/tcp.c (ffffffff818247f8)
Location: include/crypto/hash.h:558
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
In security/integrity/ima/ima_crypto.c (ffffffff81420ab0)
Location: include/crypto/hash.h:566
Inline: True
Inline callers:
  - security/integrity/ima/ima_crypto.c:ima_calc_buffer_hash
  - security/integrity/ima/ima_crypto.c:ima_calc_file_hash
```
```
In net/ipv4/tcp.c (ffffffff818a35a8)
Location: include/crypto/hash.h:566
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
In security/integrity/ima/ima_crypto.c (ffffffff81452f46)
Location: include/crypto/hash.h:565
Inline: True
Inline callers:
  - security/integrity/ima/ima_crypto.c:ima_calc_buffer_hash
  - security/integrity/ima/ima_crypto.c:ima_calc_file_hash
```
```
In net/ipv4/tcp.c (ffffffff818f7aca)
Location: include/crypto/hash.h:565
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
Location: include/crypto/hash.h:577
Inline: True
Inline callers:
  - security/integrity/ima/ima_crypto.c:ima_calc_buffer_hash
  - security/integrity/ima/ima_crypto.c:ima_calc_file_hash
```
```
In net/ipv4/tcp.c (ffffffff8192613e)
Location: include/crypto/hash.h:577
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
Location: include/crypto/hash.h:576
Inline: True
Inline callers:
  - security/integrity/ima/ima_crypto.c:ima_calc_buffer_hash
  - security/integrity/ima/ima_crypto.c:ima_calc_file_hash_atfm
```
```
In net/ipv4/tcp.c (ffffffff8198726f)
Location: include/crypto/hash.h:576
Inline: True
Inline callers:
  - net/ipv4/tcp.c:__tcp_alloc_md5sig_pool
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Duplicate, Selective Inline, Transformation ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/verity/enable.c (ffffffff8134f5f7)
Location: include/crypto/hash.h:576
Inline: True
Inline callers:
  - fs/verity/enable.c:build_merkle_tree
```
```
In fs/verity/hash_algs.c (ffffffff813504de)
Location: include/crypto/hash.h:576
Inline: True
Inline callers:
  - fs/verity/hash_algs.c:fsverity_hash_buffer
  - fs/verity/hash_algs.c:fsverity_prepare_hash_state
```
```
In fs/verity/verify.c (ffffffff8135193e)
Location: include/crypto/hash.h:576
Inline: True
Inline callers:
  - fs/verity/verify.c:fsverity_verify_page
Direct callers:
  - fs/verity/verify.c:fsverity_verify_bio
```
```
In security/integrity/ima/ima_crypto.c (ffffffff814b7edd)
Location: include/crypto/hash.h:576
Inline: True
Inline callers:
  - security/integrity/ima/ima_crypto.c:ima_calc_buffer_hash
  - security/integrity/ima/ima_crypto.c:ima_calc_file_hash_atfm
```
```
In net/ipv4/tcp.c (ffffffff819bda0f)
Location: include/crypto/hash.h:576
Inline: True
Inline callers:
  - net/ipv4/tcp.c:__tcp_alloc_md5sig_pool
```
**Symbols:**

```
ffffffff81351130-ffffffff81351159: ahash_request_alloc.constprop.0 (STB_LOCAL)
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
In security/integrity/ima/ima_crypto.c (ffffffff81516f0f)
Location: include/crypto/hash.h:589
Inline: True
Inline callers:
  - security/integrity/ima/ima_crypto.c:calc_buffer_ahash_atfm
  - security/integrity/ima/ima_crypto.c:ima_calc_file_hash_atfm
```
```
In net/ipv4/tcp.c (ffffffff81aa85b2)
Location: include/crypto/hash.h:589
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
In security/integrity/ima/ima_crypto.c (ffffffff815340cf)
Location: include/crypto/hash.h:597
Inline: True
Inline callers:
  - security/integrity/ima/ima_crypto.c:calc_buffer_ahash_atfm
  - security/integrity/ima/ima_crypto.c:ima_calc_file_hash_atfm
```
```
In net/ipv4/tcp.c (ffffffff81ab2b22)
Location: include/crypto/hash.h:597
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
In security/integrity/ima/ima_crypto.c (ffffffff8153d0b9)
Location: include/crypto/hash.h:599
Inline: True
Inline callers:
  - security/integrity/ima/ima_crypto.c:ima_calc_buffer_hash
  - security/integrity/ima/ima_crypto.c:ima_calc_file_hash_atfm
```
```
In net/ipv4/tcp.c (ffffffff81a9dd72)
Location: include/crypto/hash.h:599
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
In security/integrity/ima/ima_crypto.c (ffffffff8159bf39)
Location: include/crypto/hash.h:599
Inline: True
Inline callers:
  - security/integrity/ima/ima_crypto.c:ima_calc_buffer_hash
  - security/integrity/ima/ima_crypto.c:ima_calc_file_hash_atfm
```
```
In net/ipv4/tcp.c (ffffffff81b597d7)
Location: include/crypto/hash.h:599
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
In security/integrity/ima/ima_crypto.c (ffffffff81640f13)
Location: include/crypto/hash.h:599
Inline: True
Inline callers:
  - security/integrity/ima/ima_crypto.c:ima_calc_buffer_hash
  - security/integrity/ima/ima_crypto.c:ima_calc_file_hash_atfm
```
```
In net/ipv4/tcp.c (ffffffff81ce823d)
Location: include/crypto/hash.h:599
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
In security/integrity/ima/ima_crypto.c (ffffffff816f8e83)
Location: include/crypto/hash.h:599
Inline: True
Inline callers:
  - security/integrity/ima/ima_crypto.c:ima_calc_buffer_hash
  - security/integrity/ima/ima_crypto.c:ima_calc_file_hash_atfm
```
```
In net/ipv4/tcp.c (ffffffff81eabb97)
Location: include/crypto/hash.h:599
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
Location: include/crypto/hash.h:649
Inline: True
Inline callers:
  - security/integrity/ima/ima_crypto.c:ima_calc_buffer_hash
  - security/integrity/ima/ima_crypto.c:ima_calc_file_hash_atfm
```
```
In net/ipv4/tcp.c (ffffffff81f0a357)
Location: include/crypto/hash.h:649
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
Location: include/crypto/hash.h:581
Inline: True
Inline callers:
  - security/integrity/ima/ima_crypto.c:ima_calc_buffer_hash
  - security/integrity/ima/ima_crypto.c:ima_calc_file_hash_atfm
```
```
In net/ipv4/tcp_sigpool.c (ffffffff8204c9a4)
Location: include/crypto/hash.h:581
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
Location: include/crypto/hash.h:576
Inline: True
Inline callers:
  - fs/verity/enable.c:build_merkle_tree
```
```
In fs/verity/hash_algs.c (ffff8000104121a4)
Location: include/crypto/hash.h:576
Inline: True
Inline callers:
  - fs/verity/hash_algs.c:fsverity_hash_buffer
  - fs/verity/hash_algs.c:fsverity_prepare_hash_state
```
```
In fs/verity/verify.c (ffff8000104138bc)
Location: include/crypto/hash.h:576
Inline: True
Inline callers:
  - fs/verity/verify.c:fsverity_verify_bio
  - fs/verity/verify.c:fsverity_verify_page
```
```
In security/integrity/ima/ima_crypto.c (ffff8000105b02ac)
Location: include/crypto/hash.h:576
Inline: True
Inline callers:
  - security/integrity/ima/ima_crypto.c:ima_calc_buffer_hash
  - security/integrity/ima/ima_crypto.c:ima_calc_file_hash_atfm
```
```
In net/ipv4/tcp.c (ffff800010c6f5d4)
Location: include/crypto/hash.h:576
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
Location: include/crypto/hash.h:576
Inline: True
Inline callers:
  - fs/verity/enable.c:build_merkle_tree
```
```
In fs/verity/hash_algs.c (c05de81c)
Location: include/crypto/hash.h:576
Inline: True
Inline callers:
  - fs/verity/hash_algs.c:fsverity_hash_buffer
  - fs/verity/hash_algs.c:fsverity_prepare_hash_state
```
```
In fs/verity/verify.c (c05dfb68)
Location: include/crypto/hash.h:576
Inline: True
Inline callers:
  - fs/verity/verify.c:fsverity_verify_bio
  - fs/verity/verify.c:fsverity_verify_page
```
```
In security/integrity/ima/ima_crypto.c (c075f9cc)
Location: include/crypto/hash.h:576
Inline: True
Inline callers:
  - security/integrity/ima/ima_crypto.c:ima_calc_buffer_hash
  - security/integrity/ima/ima_crypto.c:ima_calc_file_hash_atfm
```
```
In net/ipv4/tcp.c (c0d7e7d4)
Location: include/crypto/hash.h:576
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_alloc_md5sig_pool
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Duplicate, Selective Inline, Transformation ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/verity/enable.c (c00000000051ead8)
Location: include/crypto/hash.h:576
Inline: True
Inline callers:
  - fs/verity/enable.c:build_merkle_tree
```
```
In fs/verity/hash_algs.c (c00000000051ff00)
Location: include/crypto/hash.h:576
Inline: True
Inline callers:
  - fs/verity/hash_algs.c:fsverity_hash_buffer
  - fs/verity/hash_algs.c:fsverity_prepare_hash_state
```
```
In fs/verity/verify.c (c000000000521b2c)
Location: include/crypto/hash.h:576
Inline: True
Inline callers:
  - fs/verity/verify.c:fsverity_verify_page
Direct callers:
  - fs/verity/verify.c:fsverity_verify_bio
  - fs/verity/verify.c:fsverity_verify_bio
```
```
In security/integrity/ima/ima_crypto.c (c00000000072fd58)
Location: include/crypto/hash.h:576
Inline: True
Inline callers:
  - security/integrity/ima/ima_crypto.c:ima_calc_buffer_hash
  - security/integrity/ima/ima_crypto.c:ima_calc_file_hash_atfm
```
```
In net/ipv4/tcp.c (c000000000d7637c)
Location: include/crypto/hash.h:576
Inline: True
Inline callers:
  - net/ipv4/tcp.c:__tcp_alloc_md5sig_pool
```
**Symbols:**

```
c000000000520f40-c000000000520f94: ahash_request_alloc.constprop.0 (STB_LOCAL)
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
In fs/verity/enable.c (ffffffe0002b9474)
Location: include/crypto/hash.h:576
Inline: True
Inline callers:
  - fs/verity/enable.c:build_merkle_tree
```
```
In fs/verity/hash_algs.c (ffffffe0002ba206)
Location: include/crypto/hash.h:576
Inline: True
Inline callers:
  - fs/verity/hash_algs.c:fsverity_hash_buffer
  - fs/verity/hash_algs.c:fsverity_prepare_hash_state
```
```
In fs/verity/verify.c (ffffffe0002bb298)
Location: include/crypto/hash.h:576
Inline: True
Inline callers:
  - fs/verity/verify.c:fsverity_verify_bio
  - fs/verity/verify.c:fsverity_verify_page
```
```
In security/integrity/ima/ima_crypto.c (ffffffe0003f7f36)
Location: include/crypto/hash.h:576
Inline: True
Inline callers:
  - security/integrity/ima/ima_crypto.c:ima_calc_buffer_hash
  - security/integrity/ima/ima_crypto.c:ima_calc_file_hash_atfm
```
```
In net/ipv4/tcp.c (ffffffe0007d4956)
Location: include/crypto/hash.h:576
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
<summary>In <code>aws</code>: Duplicate, Selective Inline, Transformation ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/verity/enable.c (ffffffff81347bd7)
Location: include/crypto/hash.h:576
Inline: True
Inline callers:
  - fs/verity/enable.c:build_merkle_tree
```
```
In fs/verity/hash_algs.c (ffffffff81348abe)
Location: include/crypto/hash.h:576
Inline: True
Inline callers:
  - fs/verity/hash_algs.c:fsverity_hash_buffer
  - fs/verity/hash_algs.c:fsverity_prepare_hash_state
```
```
In fs/verity/verify.c (ffffffff81349f1e)
Location: include/crypto/hash.h:576
Inline: True
Inline callers:
  - fs/verity/verify.c:fsverity_verify_page
Direct callers:
  - fs/verity/verify.c:fsverity_verify_bio
```
```
In security/integrity/ima/ima_crypto.c (ffffffff814b04bd)
Location: include/crypto/hash.h:576
Inline: True
Inline callers:
  - security/integrity/ima/ima_crypto.c:ima_calc_buffer_hash
  - security/integrity/ima/ima_crypto.c:ima_calc_file_hash_atfm
```
```
In net/ipv4/tcp.c (ffffffff8195d87f)
Location: include/crypto/hash.h:576
Inline: True
Inline callers:
  - net/ipv4/tcp.c:__tcp_alloc_md5sig_pool
```
**Symbols:**

```
ffffffff81349710-ffffffff81349739: ahash_request_alloc.constprop.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Duplicate, Selective Inline, Transformation ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/verity/enable.c (ffffffff813388b7)
Location: include/crypto/hash.h:576
Inline: True
Inline callers:
  - fs/verity/enable.c:build_merkle_tree
```
```
In fs/verity/hash_algs.c (ffffffff8133979e)
Location: include/crypto/hash.h:576
Inline: True
Inline callers:
  - fs/verity/hash_algs.c:fsverity_hash_buffer
  - fs/verity/hash_algs.c:fsverity_prepare_hash_state
```
```
In fs/verity/verify.c (ffffffff8133abfe)
Location: include/crypto/hash.h:576
Inline: True
Inline callers:
  - fs/verity/verify.c:fsverity_verify_page
Direct callers:
  - fs/verity/verify.c:fsverity_verify_bio
```
```
In security/integrity/ima/ima_crypto.c (ffffffff814a0edd)
Location: include/crypto/hash.h:576
Inline: True
Inline callers:
  - security/integrity/ima/ima_crypto.c:ima_calc_buffer_hash
  - security/integrity/ima/ima_crypto.c:ima_calc_file_hash_atfm
```
```
In net/ipv4/tcp.c (ffffffff8191736f)
Location: include/crypto/hash.h:576
Inline: True
Inline callers:
  - net/ipv4/tcp.c:__tcp_alloc_md5sig_pool
```
**Symbols:**

```
ffffffff8133a3f0-ffffffff8133a419: ahash_request_alloc.constprop.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Duplicate, Selective Inline, Transformation ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/verity/enable.c (ffffffff813456a7)
Location: include/crypto/hash.h:576
Inline: True
Inline callers:
  - fs/verity/enable.c:build_merkle_tree
```
```
In fs/verity/hash_algs.c (ffffffff8134658e)
Location: include/crypto/hash.h:576
Inline: True
Inline callers:
  - fs/verity/hash_algs.c:fsverity_hash_buffer
  - fs/verity/hash_algs.c:fsverity_prepare_hash_state
```
```
In fs/verity/verify.c (ffffffff813479ee)
Location: include/crypto/hash.h:576
Inline: True
Inline callers:
  - fs/verity/verify.c:fsverity_verify_page
Direct callers:
  - fs/verity/verify.c:fsverity_verify_bio
```
```
In security/integrity/ima/ima_crypto.c (ffffffff814ac54d)
Location: include/crypto/hash.h:576
Inline: True
Inline callers:
  - security/integrity/ima/ima_crypto.c:ima_calc_buffer_hash
  - security/integrity/ima/ima_crypto.c:ima_calc_file_hash_atfm
```
```
In net/ipv4/tcp.c (ffffffff819c804f)
Location: include/crypto/hash.h:576
Inline: True
Inline callers:
  - net/ipv4/tcp.c:__tcp_alloc_md5sig_pool
```
**Symbols:**

```
ffffffff813471e0-ffffffff81347209: ahash_request_alloc.constprop.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Duplicate, Selective Inline, Transformation ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/verity/enable.c (ffffffff81358987)
Location: include/crypto/hash.h:576
Inline: True
Inline callers:
  - fs/verity/enable.c:build_merkle_tree
```
```
In fs/verity/hash_algs.c (ffffffff8135986e)
Location: include/crypto/hash.h:576
Inline: True
Inline callers:
  - fs/verity/hash_algs.c:fsverity_hash_buffer
  - fs/verity/hash_algs.c:fsverity_prepare_hash_state
```
```
In fs/verity/verify.c (ffffffff8135acee)
Location: include/crypto/hash.h:576
Inline: True
Inline callers:
  - fs/verity/verify.c:fsverity_verify_page
Direct callers:
  - fs/verity/verify.c:fsverity_verify_bio
```
```
In security/integrity/ima/ima_crypto.c (ffffffff814c4f9d)
Location: include/crypto/hash.h:576
Inline: True
Inline callers:
  - security/integrity/ima/ima_crypto.c:ima_calc_buffer_hash
  - security/integrity/ima/ima_crypto.c:ima_calc_file_hash_atfm
```
```
In net/ipv4/tcp.c (ffffffff819d1b9f)
Location: include/crypto/hash.h:576
Inline: True
Inline callers:
  - net/ipv4/tcp.c:__tcp_alloc_md5sig_pool
```
**Symbols:**

```
ffffffff8135a4e0-ffffffff8135a509: ahash_request_alloc.constprop.0 (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
