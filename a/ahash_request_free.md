# Function: <code>ahash_request_free</code>

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
In security/integrity/ima/ima_crypto.c (ffffffff81397e43)
Location: include/crypto/hash.h:548
Inline: True
Inline callers:
  - security/integrity/ima/ima_crypto.c:ima_calc_file_hash_atfm
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In security/integrity/ima/ima_crypto.c (ffffffff813d49a5)
Location: include/crypto/hash.h:570
Inline: True
Inline callers:
  - security/integrity/ima/ima_crypto.c:ima_calc_buffer_hash
  - security/integrity/ima/ima_crypto.c:ima_calc_file_hash
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In security/integrity/ima/ima_crypto.c (ffffffff813ec3f5)
Location: include/crypto/hash.h:570
Inline: True
Inline callers:
  - security/integrity/ima/ima_crypto.c:ima_calc_buffer_hash
  - security/integrity/ima/ima_crypto.c:ima_calc_file_hash
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In security/integrity/ima/ima_crypto.c (ffffffff813f87b0)
Location: include/crypto/hash.h:576
Inline: True
Inline callers:
  - security/integrity/ima/ima_crypto.c:ima_calc_buffer_hash
  - security/integrity/ima/ima_crypto.c:ima_calc_file_hash
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In security/integrity/ima/ima_crypto.c (ffffffff81420be5)
Location: include/crypto/hash.h:584
Inline: True
Inline callers:
  - security/integrity/ima/ima_crypto.c:ima_calc_buffer_hash
  - security/integrity/ima/ima_crypto.c:ima_calc_file_hash
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In security/integrity/ima/ima_crypto.c (ffffffff81453063)
Location: include/crypto/hash.h:583
Inline: True
Inline callers:
  - security/integrity/ima/ima_crypto.c:ima_calc_buffer_hash
  - security/integrity/ima/ima_crypto.c:ima_calc_file_hash
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In security/integrity/ima/ima_crypto.c (ffffffff81470213)
Location: include/crypto/hash.h:595
Inline: True
Inline callers:
  - security/integrity/ima/ima_crypto.c:ima_calc_buffer_hash
  - security/integrity/ima/ima_crypto.c:ima_calc_file_hash
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In security/integrity/ima/ima_crypto.c (ffffffff8149dbe2)
Location: include/crypto/hash.h:594
Inline: True
Inline callers:
  - security/integrity/ima/ima_crypto.c:ima_calc_buffer_hash
  - security/integrity/ima/ima_crypto.c:ima_calc_file_hash_atfm
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
In fs/verity/enable.c (ffffffff8134f7fe)
Location: include/crypto/hash.h:594
Inline: True
Inline callers:
  - fs/verity/enable.c:build_merkle_tree
```
```
In fs/verity/hash_algs.c (ffffffff8135054f)
Location: include/crypto/hash.h:594
Inline: True
Inline callers:
  - fs/verity/hash_algs.c:fsverity_hash_buffer
  - fs/verity/hash_algs.c:fsverity_prepare_hash_state
```
```
In fs/verity/verify.c (ffffffff81351852)
Location: include/crypto/hash.h:594
Inline: True
Inline callers:
  - fs/verity/verify.c:fsverity_verify_bio
  - fs/verity/verify.c:fsverity_verify_page
```
```
In security/integrity/ima/ima_crypto.c (ffffffff814b8022)
Location: include/crypto/hash.h:594
Inline: True
Inline callers:
  - security/integrity/ima/ima_crypto.c:ima_calc_buffer_hash
  - security/integrity/ima/ima_crypto.c:ima_calc_file_hash_atfm
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In security/integrity/ima/ima_crypto.c (ffffffff81517090)
Location: include/crypto/hash.h:607
Inline: True
Inline callers:
  - security/integrity/ima/ima_crypto.c:calc_buffer_ahash_atfm
  - security/integrity/ima/ima_crypto.c:ima_calc_file_hash_atfm
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In security/integrity/ima/ima_crypto.c (ffffffff81534250)
Location: include/crypto/hash.h:615
Inline: True
Inline callers:
  - security/integrity/ima/ima_crypto.c:calc_buffer_ahash_atfm
  - security/integrity/ima/ima_crypto.c:ima_calc_file_hash_atfm
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In security/integrity/ima/ima_crypto.c (ffffffff8153d208)
Location: include/crypto/hash.h:617
Inline: True
Inline callers:
  - security/integrity/ima/ima_crypto.c:ima_calc_buffer_hash
  - security/integrity/ima/ima_crypto.c:ima_calc_file_hash_atfm
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In security/integrity/ima/ima_crypto.c (ffffffff8159c088)
Location: include/crypto/hash.h:617
Inline: True
Inline callers:
  - security/integrity/ima/ima_crypto.c:ima_calc_buffer_hash
  - security/integrity/ima/ima_crypto.c:ima_calc_file_hash_atfm
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In security/integrity/ima/ima_crypto.c (ffffffff81641073)
Location: include/crypto/hash.h:617
Inline: True
Inline callers:
  - security/integrity/ima/ima_crypto.c:ima_calc_buffer_hash
  - security/integrity/ima/ima_crypto.c:ima_calc_file_hash_atfm
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In security/integrity/ima/ima_crypto.c (ffffffff816f8fe3)
Location: include/crypto/hash.h:617
Inline: True
Inline callers:
  - security/integrity/ima/ima_crypto.c:ima_calc_buffer_hash
  - security/integrity/ima/ima_crypto.c:ima_calc_file_hash_atfm
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In security/integrity/ima/ima_crypto.c (ffffffff81733199)
Location: include/crypto/hash.h:667
Inline: True
Inline callers:
  - security/integrity/ima/ima_crypto.c:ima_calc_buffer_hash
  - security/integrity/ima/ima_crypto.c:ima_calc_file_hash_atfm
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
In security/integrity/ima/ima_crypto.c (ffffffff81773ba1)
Location: include/crypto/hash.h:599
Inline: True
Inline callers:
  - security/integrity/ima/ima_crypto.c:ima_calc_buffer_hash
  - security/integrity/ima/ima_crypto.c:ima_calc_file_hash_atfm
```
```
In net/ipv4/tcp_sigpool.c (ffffffff8204c5c8)
Location: include/crypto/hash.h:599
Inline: True
Inline callers:
  - net/ipv4/tcp_sigpool.c:tcp_sigpool_end
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
In fs/verity/enable.c (ffff80001041125c)
Location: include/crypto/hash.h:594
Inline: True
Inline callers:
  - fs/verity/enable.c:build_merkle_tree
```
```
In fs/verity/hash_algs.c (ffff800010412214)
Location: include/crypto/hash.h:594
Inline: True
Inline callers:
  - fs/verity/hash_algs.c:fsverity_hash_buffer
  - fs/verity/hash_algs.c:fsverity_prepare_hash_state
```
```
In fs/verity/verify.c (ffff80001041398c)
Location: include/crypto/hash.h:594
Inline: True
Inline callers:
  - fs/verity/verify.c:fsverity_verify_bio
  - fs/verity/verify.c:fsverity_verify_page
```
```
In security/integrity/ima/ima_crypto.c (ffff8000105b03bc)
Location: include/crypto/hash.h:594
Inline: True
Inline callers:
  - security/integrity/ima/ima_crypto.c:ima_calc_buffer_hash
  - security/integrity/ima/ima_crypto.c:ima_calc_file_hash_atfm
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
In fs/verity/enable.c (c05dd920)
Location: include/crypto/hash.h:594
Inline: True
Inline callers:
  - fs/verity/enable.c:build_merkle_tree
```
```
In fs/verity/hash_algs.c (c05de894)
Location: include/crypto/hash.h:594
Inline: True
Inline callers:
  - fs/verity/hash_algs.c:fsverity_hash_buffer
  - fs/verity/hash_algs.c:fsverity_prepare_hash_state
```
```
In fs/verity/verify.c (c05dfc38)
Location: include/crypto/hash.h:594
Inline: True
Inline callers:
  - fs/verity/verify.c:fsverity_verify_bio
  - fs/verity/verify.c:fsverity_verify_page
```
```
In security/integrity/ima/ima_crypto.c (c075fb10)
Location: include/crypto/hash.h:594
Inline: True
Inline callers:
  - security/integrity/ima/ima_crypto.c:ima_calc_buffer_hash
  - security/integrity/ima/ima_crypto.c:ima_calc_file_hash_atfm
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
In fs/verity/enable.c (c00000000051eda0)
Location: include/crypto/hash.h:594
Inline: True
Inline callers:
  - fs/verity/enable.c:build_merkle_tree
```
```
In fs/verity/hash_algs.c (c00000000051ff84)
Location: include/crypto/hash.h:594
Inline: True
Inline callers:
  - fs/verity/hash_algs.c:fsverity_hash_buffer
  - fs/verity/hash_algs.c:fsverity_prepare_hash_state
```
```
In fs/verity/verify.c (c000000000521970)
Location: include/crypto/hash.h:594
Inline: True
Inline callers:
  - fs/verity/verify.c:fsverity_verify_bio
  - fs/verity/verify.c:fsverity_verify_page
```
```
In security/integrity/ima/ima_crypto.c (c00000000072fec4)
Location: include/crypto/hash.h:594
Inline: True
Inline callers:
  - security/integrity/ima/ima_crypto.c:ima_calc_buffer_hash
  - security/integrity/ima/ima_crypto.c:ima_calc_file_hash_atfm
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
In fs/verity/enable.c (ffffffe0002b966a)
Location: include/crypto/hash.h:594
Inline: True
Inline callers:
  - fs/verity/enable.c:build_merkle_tree
```
```
In fs/verity/hash_algs.c (ffffffe0002ba27c)
Location: include/crypto/hash.h:594
Inline: True
Inline callers:
  - fs/verity/hash_algs.c:fsverity_hash_buffer
  - fs/verity/hash_algs.c:fsverity_prepare_hash_state
```
```
In fs/verity/verify.c (ffffffe0002bb35a)
Location: include/crypto/hash.h:594
Inline: True
Inline callers:
  - fs/verity/verify.c:fsverity_verify_bio
  - fs/verity/verify.c:fsverity_verify_page
```
```
In security/integrity/ima/ima_crypto.c (ffffffe0003f8048)
Location: include/crypto/hash.h:594
Inline: True
Inline callers:
  - security/integrity/ima/ima_crypto.c:ima_calc_buffer_hash
  - security/integrity/ima/ima_crypto.c:ima_calc_file_hash_atfm
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
In fs/verity/enable.c (ffffffff81347dde)
Location: include/crypto/hash.h:594
Inline: True
Inline callers:
  - fs/verity/enable.c:build_merkle_tree
```
```
In fs/verity/hash_algs.c (ffffffff81348b2f)
Location: include/crypto/hash.h:594
Inline: True
Inline callers:
  - fs/verity/hash_algs.c:fsverity_hash_buffer
  - fs/verity/hash_algs.c:fsverity_prepare_hash_state
```
```
In fs/verity/verify.c (ffffffff81349e32)
Location: include/crypto/hash.h:594
Inline: True
Inline callers:
  - fs/verity/verify.c:fsverity_verify_bio
  - fs/verity/verify.c:fsverity_verify_page
```
```
In security/integrity/ima/ima_crypto.c (ffffffff814b0602)
Location: include/crypto/hash.h:594
Inline: True
Inline callers:
  - security/integrity/ima/ima_crypto.c:ima_calc_buffer_hash
  - security/integrity/ima/ima_crypto.c:ima_calc_file_hash_atfm
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
In fs/verity/enable.c (ffffffff81338abe)
Location: include/crypto/hash.h:594
Inline: True
Inline callers:
  - fs/verity/enable.c:build_merkle_tree
```
```
In fs/verity/hash_algs.c (ffffffff8133980f)
Location: include/crypto/hash.h:594
Inline: True
Inline callers:
  - fs/verity/hash_algs.c:fsverity_hash_buffer
  - fs/verity/hash_algs.c:fsverity_prepare_hash_state
```
```
In fs/verity/verify.c (ffffffff8133ab12)
Location: include/crypto/hash.h:594
Inline: True
Inline callers:
  - fs/verity/verify.c:fsverity_verify_bio
  - fs/verity/verify.c:fsverity_verify_page
```
```
In security/integrity/ima/ima_crypto.c (ffffffff814a1022)
Location: include/crypto/hash.h:594
Inline: True
Inline callers:
  - security/integrity/ima/ima_crypto.c:ima_calc_buffer_hash
  - security/integrity/ima/ima_crypto.c:ima_calc_file_hash_atfm
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
In fs/verity/enable.c (ffffffff813458ae)
Location: include/crypto/hash.h:594
Inline: True
Inline callers:
  - fs/verity/enable.c:build_merkle_tree
```
```
In fs/verity/hash_algs.c (ffffffff813465ff)
Location: include/crypto/hash.h:594
Inline: True
Inline callers:
  - fs/verity/hash_algs.c:fsverity_hash_buffer
  - fs/verity/hash_algs.c:fsverity_prepare_hash_state
```
```
In fs/verity/verify.c (ffffffff81347902)
Location: include/crypto/hash.h:594
Inline: True
Inline callers:
  - fs/verity/verify.c:fsverity_verify_bio
  - fs/verity/verify.c:fsverity_verify_page
```
```
In security/integrity/ima/ima_crypto.c (ffffffff814ac692)
Location: include/crypto/hash.h:594
Inline: True
Inline callers:
  - security/integrity/ima/ima_crypto.c:ima_calc_buffer_hash
  - security/integrity/ima/ima_crypto.c:ima_calc_file_hash_atfm
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
In fs/verity/enable.c (ffffffff81358b89)
Location: include/crypto/hash.h:594
Inline: True
Inline callers:
  - fs/verity/enable.c:build_merkle_tree
```
```
In fs/verity/hash_algs.c (ffffffff813598df)
Location: include/crypto/hash.h:594
Inline: True
Inline callers:
  - fs/verity/hash_algs.c:fsverity_hash_buffer
  - fs/verity/hash_algs.c:fsverity_prepare_hash_state
```
```
In fs/verity/verify.c (ffffffff8135ac02)
Location: include/crypto/hash.h:594
Inline: True
Inline callers:
  - fs/verity/verify.c:fsverity_verify_bio
  - fs/verity/verify.c:fsverity_verify_page
```
```
In security/integrity/ima/ima_crypto.c (ffffffff814c50e2)
Location: include/crypto/hash.h:594
Inline: True
Inline callers:
  - security/integrity/ima/ima_crypto.c:ima_calc_buffer_hash
  - security/integrity/ima/ima_crypto.c:ima_calc_file_hash_atfm
```
</details>
</li>
</ul>

## Differences
