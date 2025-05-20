# Function: <code>crypto_aead_ivsize</code>

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
In crypto/aead.c (0)
Location: include/crypto/aead.h:213
Inline: True
```
```
In crypto/blkcipher.c (0)
Location: include/crypto/aead.h:213
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
In crypto/aead.c (0)
Location: include/crypto/aead.h:216
Inline: True
```
```
In crypto/blkcipher.c (0)
Location: include/crypto/aead.h:216
Inline: True
```
```
In crypto/seqiv.c (ffffffff813de896)
Location: include/crypto/aead.h:216
Inline: True
Inline callers:
  - crypto/seqiv.c:seqiv_aead_encrypt_complete2
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
In crypto/aead.c (0)
Location: include/crypto/aead.h:216
Inline: True
```
```
In crypto/blkcipher.c (0)
Location: include/crypto/aead.h:216
Inline: True
```
```
In crypto/skcipher.c (0)
Location: include/crypto/aead.h:216
Inline: True
```
```
In crypto/seqiv.c (ffffffff813f6e36)
Location: include/crypto/aead.h:216
Inline: True
Inline callers:
  - crypto/seqiv.c:seqiv_aead_encrypt_complete2
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
In crypto/aead.c (0)
Location: include/crypto/aead.h:216
Inline: True
```
```
In crypto/blkcipher.c (0)
Location: include/crypto/aead.h:216
Inline: True
```
```
In crypto/skcipher.c (0)
Location: include/crypto/aead.h:216
Inline: True
```
```
In crypto/seqiv.c (ffffffff81403208)
Location: include/crypto/aead.h:216
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
In security/keys/big_key.c (ffffffff813bbf85)
Location: include/crypto/aead.h:216
Inline: True
Inline callers:
  - security/keys/big_key.c:big_key_crypt
```
```
In crypto/aead.c (ffffffff8142807f)
Location: include/crypto/aead.h:216
Inline: True
Inline callers:
  - crypto/aead.c:aead_init_geniv
```
```
In crypto/blkcipher.c (ffffffff8142a01a)
Location: include/crypto/aead.h:216
Inline: True
Inline callers:
  - crypto/blkcipher.c:blkcipher_aead_walk_virt_block
```
```
In crypto/skcipher.c (ffffffff8142b69c)
Location: include/crypto/aead.h:216
Inline: True
Inline callers:
  - crypto/skcipher.c:skcipher_walk_aead_common
```
```
In crypto/seqiv.c (ffffffff8142b8e8)
Location: include/crypto/aead.h:216
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
In security/keys/big_key.c (ffffffff82715b9a)
Location: include/crypto/aead.h:216
Inline: True
Inline callers:
  - security/keys/big_key.c:big_key_init
```
```
In crypto/aead.c (ffffffff8145aeb8)
Location: include/crypto/aead.h:216
Inline: True
Inline callers:
  - crypto/aead.c:aead_init_geniv
```
```
In crypto/blkcipher.c (ffffffff8145cd57)
Location: include/crypto/aead.h:216
Inline: True
Inline callers:
  - crypto/blkcipher.c:blkcipher_aead_walk_virt_block
```
```
In crypto/skcipher.c (ffffffff8145e3a8)
Location: include/crypto/aead.h:216
Inline: True
Inline callers:
  - crypto/skcipher.c:skcipher_walk_aead_common
```
```
In crypto/seqiv.c (ffffffff8145e5fd)
Location: include/crypto/aead.h:216
Inline: True
Inline callers:
  - crypto/seqiv.c:seqiv_aead_encrypt_complete2
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
In security/keys/big_key.c (ffffffff828ccfe5)
Location: include/crypto/aead.h:213
Inline: True
Inline callers:
  - security/keys/big_key.c:big_key_init
```
```
In crypto/aead.c (ffffffff81478e28)
Location: include/crypto/aead.h:213
Inline: True
Inline callers:
  - crypto/aead.c:aead_init_geniv
```
```
In crypto/blkcipher.c (ffffffff8147a5e7)
Location: include/crypto/aead.h:213
Inline: True
Inline callers:
  - crypto/blkcipher.c:blkcipher_aead_walk_virt_block
```
```
In crypto/skcipher.c (ffffffff8147bc68)
Location: include/crypto/aead.h:213
Inline: True
Inline callers:
  - crypto/skcipher.c:skcipher_walk_aead_common
```
```
In crypto/seqiv.c (ffffffff8147beed)
Location: include/crypto/aead.h:213
Inline: True
Inline callers:
  - crypto/seqiv.c:seqiv_aead_encrypt_complete2
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
In security/keys/big_key.c (ffffffff828e69b4)
Location: include/crypto/aead.h:208
Inline: True
Inline callers:
  - security/keys/big_key.c:big_key_init
```
```
In crypto/aead.c (ffffffff814a6d4a)
Location: include/crypto/aead.h:208
Inline: True
Inline callers:
  - crypto/aead.c:aead_init_geniv
```
```
In crypto/blkcipher.c (ffffffff814a8617)
Location: include/crypto/aead.h:208
Inline: True
Inline callers:
  - crypto/blkcipher.c:blkcipher_aead_walk_virt_block
```
```
In crypto/skcipher.c (ffffffff814aa00a)
Location: include/crypto/aead.h:208
Inline: True
Inline callers:
  - crypto/skcipher.c:skcipher_walk_aead_common
```
```
In crypto/seqiv.c (ffffffff814aa28d)
Location: include/crypto/aead.h:208
Inline: True
Inline callers:
  - crypto/seqiv.c:seqiv_aead_encrypt_complete2
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
In security/keys/big_key.c (ffffffff828ef46d)
Location: include/crypto/aead.h:208
Inline: True
Inline callers:
  - security/keys/big_key.c:big_key_init
```
```
In crypto/aead.c (ffffffff814c19ba)
Location: include/crypto/aead.h:208
Inline: True
Inline callers:
  - crypto/aead.c:aead_init_geniv
```
```
In crypto/blkcipher.c (ffffffff814c3287)
Location: include/crypto/aead.h:208
Inline: True
Inline callers:
  - crypto/blkcipher.c:blkcipher_aead_walk_virt_block
```
```
In crypto/skcipher.c (ffffffff814c4cfa)
Location: include/crypto/aead.h:208
Inline: True
Inline callers:
  - crypto/skcipher.c:skcipher_walk_aead_common
```
```
In crypto/seqiv.c (ffffffff814c4f4d)
Location: include/crypto/aead.h:208
Inline: True
Inline callers:
  - crypto/seqiv.c:seqiv_aead_encrypt_complete2
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
In crypto/geniv.c (ffffffff815222fa)
Location: include/crypto/aead.h:214
Inline: True
Inline callers:
  - crypto/geniv.c:aead_init_geniv
```
```
In crypto/skcipher.c (ffffffff81523b8a)
Location: include/crypto/aead.h:214
Inline: True
Inline callers:
  - crypto/skcipher.c:skcipher_walk_aead_common
```
```
In crypto/seqiv.c (ffffffff81523e5d)
Location: include/crypto/aead.h:214
Inline: True
Inline callers:
  - crypto/seqiv.c:seqiv_aead_encrypt_complete2
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
In crypto/geniv.c (ffffffff8153f1da)
Location: include/crypto/aead.h:219
Inline: True
Inline callers:
  - crypto/geniv.c:aead_init_geniv
```
```
In crypto/skcipher.c (ffffffff81540ada)
Location: include/crypto/aead.h:219
Inline: True
Inline callers:
  - crypto/skcipher.c:skcipher_walk_aead_common
```
```
In crypto/seqiv.c (ffffffff81540d66)
Location: include/crypto/aead.h:219
Inline: True
Inline callers:
  - crypto/seqiv.c:seqiv_aead_encrypt_complete2
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
In crypto/geniv.c (ffffffff8154785a)
Location: include/crypto/aead.h:221
Inline: True
Inline callers:
  - crypto/geniv.c:aead_init_geniv
```
```
In crypto/skcipher.c (ffffffff8154913a)
Location: include/crypto/aead.h:221
Inline: True
Inline callers:
  - crypto/skcipher.c:skcipher_walk_aead_common
```
```
In crypto/seqiv.c (ffffffff815493c6)
Location: include/crypto/aead.h:221
Inline: True
Inline callers:
  - crypto/seqiv.c:seqiv_aead_encrypt_complete2
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
In crypto/geniv.c (ffffffff815a803a)
Location: include/crypto/aead.h:221
Inline: True
Inline callers:
  - crypto/geniv.c:aead_init_geniv
```
```
In crypto/skcipher.c (ffffffff815a991a)
Location: include/crypto/aead.h:221
Inline: True
Inline callers:
  - crypto/skcipher.c:skcipher_walk_aead_common
```
```
In crypto/seqiv.c (ffffffff815a9ba6)
Location: include/crypto/aead.h:221
Inline: True
Inline callers:
  - crypto/seqiv.c:seqiv_aead_encrypt_complete2
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
In crypto/geniv.c (ffffffff8164f3e7)
Location: include/crypto/aead.h:223
Inline: True
Inline callers:
  - crypto/geniv.c:aead_init_geniv
```
```
In crypto/skcipher.c (ffffffff81650d7a)
Location: include/crypto/aead.h:223
Inline: True
Inline callers:
  - crypto/skcipher.c:skcipher_walk_aead_common
```
```
In crypto/seqiv.c (ffffffff81651086)
Location: include/crypto/aead.h:223
Inline: True
Inline callers:
  - crypto/seqiv.c:seqiv_aead_encrypt_complete2
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
In crypto/geniv.c (ffffffff817089e7)
Location: include/crypto/aead.h:223
Inline: True
Inline callers:
  - crypto/geniv.c:aead_init_geniv
```
```
In crypto/skcipher.c (ffffffff8170a56a)
Location: include/crypto/aead.h:223
Inline: True
Inline callers:
  - crypto/skcipher.c:skcipher_walk_aead_common
```
```
In crypto/seqiv.c (ffffffff8170a8db)
Location: include/crypto/aead.h:223
Inline: True
Inline callers:
  - crypto/seqiv.c:seqiv_aead_encrypt_complete2
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
In crypto/geniv.c (ffffffff81742193)
Location: include/crypto/aead.h:245
Inline: True
Inline callers:
  - crypto/geniv.c:aead_init_geniv
```
```
In crypto/skcipher.c (ffffffff81743dba)
Location: include/crypto/aead.h:245
Inline: True
Inline callers:
  - crypto/skcipher.c:skcipher_walk_aead_common
```
```
In crypto/seqiv.c (ffffffff8174412b)
Location: include/crypto/aead.h:245
Inline: True
Inline callers:
  - crypto/seqiv.c:seqiv_aead_encrypt_complete2
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
In crypto/geniv.c (ffffffff81783073)
Location: include/crypto/aead.h:257
Inline: True
Inline callers:
  - crypto/geniv.c:aead_init_geniv
```
```
In crypto/skcipher.c (ffffffff8178619a)
Location: include/crypto/aead.h:257
Inline: True
Inline callers:
  - crypto/skcipher.c:skcipher_walk_aead_common
```
```
In crypto/seqiv.c (ffffffff817866eb)
Location: include/crypto/aead.h:257
Inline: True
Inline callers:
  - crypto/seqiv.c:seqiv_aead_encrypt_complete2
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
In security/keys/big_key.c (ffff80001146911c)
Location: include/crypto/aead.h:208
Inline: True
Inline callers:
  - security/keys/big_key.c:big_key_init
```
```
In crypto/aead.c (ffff8000105bc0cc)
Location: include/crypto/aead.h:208
Inline: True
Inline callers:
  - crypto/aead.c:aead_init_geniv
```
```
In crypto/blkcipher.c (ffff8000105bda50)
Location: include/crypto/aead.h:208
Inline: True
Inline callers:
  - crypto/blkcipher.c:blkcipher_aead_walk_virt_block
```
```
In crypto/skcipher.c (ffff8000105bf7c0)
Location: include/crypto/aead.h:208
Inline: True
Inline callers:
  - crypto/skcipher.c:skcipher_walk_aead_common
```
```
In crypto/seqiv.c (ffff8000105bfb00)
Location: include/crypto/aead.h:208
Inline: True
Inline callers:
  - crypto/seqiv.c:seqiv_aead_encrypt_complete2
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
In security/keys/big_key.c (c1541c54)
Location: include/crypto/aead.h:208
Inline: True
Inline callers:
  - security/keys/big_key.c:big_key_init
```
```
In crypto/aead.c (c076a128)
Location: include/crypto/aead.h:208
Inline: True
Inline callers:
  - crypto/aead.c:aead_init_geniv
```
```
In crypto/blkcipher.c (c076b89c)
Location: include/crypto/aead.h:208
Inline: True
Inline callers:
  - crypto/blkcipher.c:blkcipher_aead_walk_virt_block
```
```
In crypto/skcipher.c (c076d4e0)
Location: include/crypto/aead.h:208
Inline: True
Inline callers:
  - crypto/skcipher.c:skcipher_walk_aead_common
```
```
In crypto/seqiv.c (c076d75c)
Location: include/crypto/aead.h:208
Inline: True
Inline callers:
  - crypto/seqiv.c:seqiv_aead_encrypt_complete2
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
In security/keys/big_key.c (c0000000013971b4)
Location: include/crypto/aead.h:208
Inline: True
Inline callers:
  - security/keys/big_key.c:big_key_init
```
```
In crypto/aead.c (c000000000742a28)
Location: include/crypto/aead.h:208
Inline: True
Inline callers:
  - crypto/aead.c:aead_init_geniv
```
```
In crypto/blkcipher.c (c000000000744e6c)
Location: include/crypto/aead.h:208
Inline: True
Inline callers:
  - crypto/blkcipher.c:blkcipher_aead_walk_virt_block
```
```
In crypto/skcipher.c (c000000000747568)
Location: include/crypto/aead.h:208
Inline: True
Inline callers:
  - crypto/skcipher.c:skcipher_walk_aead_common
```
```
In crypto/seqiv.c (c000000000747908)
Location: include/crypto/aead.h:208
Inline: True
Inline callers:
  - crypto/seqiv.c:seqiv_aead_encrypt_complete2
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
In security/keys/big_key.c (ffffffe000024362)
Location: include/crypto/aead.h:208
Inline: True
Inline callers:
  - security/keys/big_key.c:big_key_init
```
```
In crypto/aead.c (ffffffe00040184c)
Location: include/crypto/aead.h:208
Inline: True
Inline callers:
  - crypto/aead.c:aead_init_geniv
```
```
In crypto/blkcipher.c (ffffffe000403000)
Location: include/crypto/aead.h:208
Inline: True
Inline callers:
  - crypto/blkcipher.c:blkcipher_aead_walk_virt_block
```
```
In crypto/skcipher.c (ffffffe000404906)
Location: include/crypto/aead.h:208
Inline: True
Inline callers:
  - crypto/skcipher.c:skcipher_walk_aead_common
```
```
In crypto/seqiv.c (ffffffe000404bdc)
Location: include/crypto/aead.h:208
Inline: True
Inline callers:
  - crypto/seqiv.c:seqiv_aead_encrypt_complete2
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
In security/keys/big_key.c (ffffffff828d8321)
Location: include/crypto/aead.h:208
Inline: True
Inline callers:
  - security/keys/big_key.c:big_key_init
```
```
In crypto/aead.c (ffffffff814b9f9a)
Location: include/crypto/aead.h:208
Inline: True
Inline callers:
  - crypto/aead.c:aead_init_geniv
```
```
In crypto/blkcipher.c (ffffffff814bb867)
Location: include/crypto/aead.h:208
Inline: True
Inline callers:
  - crypto/blkcipher.c:blkcipher_aead_walk_virt_block
```
```
In crypto/skcipher.c (ffffffff814bd2da)
Location: include/crypto/aead.h:208
Inline: True
Inline callers:
  - crypto/skcipher.c:skcipher_walk_aead_common
```
```
In crypto/seqiv.c (ffffffff814bd52d)
Location: include/crypto/aead.h:208
Inline: True
Inline callers:
  - crypto/seqiv.c:seqiv_aead_encrypt_complete2
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
In security/keys/big_key.c (ffffffff828d0a3d)
Location: include/crypto/aead.h:208
Inline: True
Inline callers:
  - security/keys/big_key.c:big_key_init
```
```
In crypto/aead.c (ffffffff814aa9ba)
Location: include/crypto/aead.h:208
Inline: True
Inline callers:
  - crypto/aead.c:aead_init_geniv
```
```
In crypto/blkcipher.c (ffffffff814ac287)
Location: include/crypto/aead.h:208
Inline: True
Inline callers:
  - crypto/blkcipher.c:blkcipher_aead_walk_virt_block
```
```
In crypto/skcipher.c (ffffffff814adcfa)
Location: include/crypto/aead.h:208
Inline: True
Inline callers:
  - crypto/skcipher.c:skcipher_walk_aead_common
```
```
In crypto/seqiv.c (ffffffff814adf4d)
Location: include/crypto/aead.h:208
Inline: True
Inline callers:
  - crypto/seqiv.c:seqiv_aead_encrypt_complete2
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
In security/keys/big_key.c (ffffffff828eb0a1)
Location: include/crypto/aead.h:208
Inline: True
Inline callers:
  - security/keys/big_key.c:big_key_init
```
```
In crypto/aead.c (ffffffff814b602a)
Location: include/crypto/aead.h:208
Inline: True
Inline callers:
  - crypto/aead.c:aead_init_geniv
```
```
In crypto/blkcipher.c (ffffffff814b78f7)
Location: include/crypto/aead.h:208
Inline: True
Inline callers:
  - crypto/blkcipher.c:blkcipher_aead_walk_virt_block
```
```
In crypto/skcipher.c (ffffffff814b936a)
Location: include/crypto/aead.h:208
Inline: True
Inline callers:
  - crypto/skcipher.c:skcipher_walk_aead_common
```
```
In crypto/seqiv.c (ffffffff814b95bd)
Location: include/crypto/aead.h:208
Inline: True
Inline callers:
  - crypto/seqiv.c:seqiv_aead_encrypt_complete2
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
In security/keys/big_key.c (ffffffff828f04b7)
Location: include/crypto/aead.h:208
Inline: True
Inline callers:
  - security/keys/big_key.c:big_key_init
```
```
In crypto/aead.c (ffffffff814ceaca)
Location: include/crypto/aead.h:208
Inline: True
Inline callers:
  - crypto/aead.c:aead_init_geniv
```
```
In crypto/blkcipher.c (ffffffff814d03d7)
Location: include/crypto/aead.h:208
Inline: True
Inline callers:
  - crypto/blkcipher.c:blkcipher_aead_walk_virt_block
```
```
In crypto/skcipher.c (ffffffff814d1e0a)
Location: include/crypto/aead.h:208
Inline: True
Inline callers:
  - crypto/skcipher.c:skcipher_walk_aead_common
```
```
In crypto/seqiv.c (ffffffff814d205d)
Location: include/crypto/aead.h:208
Inline: True
Inline callers:
  - crypto/seqiv.c:seqiv_aead_encrypt_complete2
```
</details>
</li>
</ul>

## Differences
