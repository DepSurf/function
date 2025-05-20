# Function: <code>crypto_aead_authsize</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>4.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In crypto/seqiv.c (0)
Location: include/crypto/aead.h:233
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
In crypto/skcipher.c (ffffffff813f6c65)
Location: include/crypto/aead.h:233
Inline: True
Inline callers:
  - crypto/skcipher.c:skcipher_walk_aead_decrypt
```
```
In crypto/seqiv.c (0)
Location: include/crypto/aead.h:233
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
In crypto/skcipher.c (ffffffff81403035)
Location: include/crypto/aead.h:233
Inline: True
Inline callers:
  - crypto/skcipher.c:skcipher_walk_aead_decrypt
```
```
In crypto/seqiv.c (0)
Location: include/crypto/aead.h:233
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
In security/keys/big_key.c (0)
Location: include/crypto/aead.h:233
Inline: True
```
```
In crypto/skcipher.c (ffffffff8142b715)
Location: include/crypto/aead.h:233
Inline: True
Inline callers:
  - crypto/skcipher.c:skcipher_walk_aead_decrypt
```
```
In crypto/seqiv.c (0)
Location: include/crypto/aead.h:233
Inline: True
```
```
In crypto/gcm.c (ffffffff81438f7c)
Location: include/crypto/aead.h:233
Inline: True
Inline callers:
  - crypto/gcm.c:crypto_rfc4543_crypt
  - crypto/gcm.c:crypto_gcm_verify
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
In security/keys/big_key.c (ffffffff813ecdf8)
Location: include/crypto/aead.h:233
Inline: True
Inline callers:
  - security/keys/big_key.c:big_key_crypt
```
```
In crypto/skcipher.c (ffffffff8145e425)
Location: include/crypto/aead.h:233
Inline: True
Inline callers:
  - crypto/skcipher.c:skcipher_walk_aead_decrypt
```
```
In crypto/seqiv.c (ffffffff8145e51c)
Location: include/crypto/aead.h:233
Inline: True
Inline callers:
  - crypto/seqiv.c:seqiv_aead_decrypt
  - crypto/seqiv.c:seqiv_aead_decrypt
```
```
In crypto/gcm.c (ffffffff8146b284)
Location: include/crypto/aead.h:233
Inline: True
Inline callers:
  - crypto/gcm.c:crypto_rfc4543_crypt
  - crypto/gcm.c:crypto_rfc4543_crypt
  - crypto/gcm.c:crypto_rfc4106_decrypt
  - crypto/gcm.c:crypto_gcm_decrypt
  - crypto/gcm.c:crypto_gcm_verify
  - crypto/gcm.c:gcm_enc_copy_hash
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
In security/keys/big_key.c (ffffffff81407fa9)
Location: include/crypto/aead.h:230
Inline: True
Inline callers:
  - security/keys/big_key.c:big_key_crypt
```
```
In crypto/skcipher.c (ffffffff8147bce5)
Location: include/crypto/aead.h:230
Inline: True
Inline callers:
  - crypto/skcipher.c:skcipher_walk_aead_decrypt
```
```
In crypto/seqiv.c (ffffffff8147bde9)
Location: include/crypto/aead.h:230
Inline: True
Inline callers:
  - crypto/seqiv.c:seqiv_aead_decrypt
  - crypto/seqiv.c:seqiv_aead_decrypt
```
```
In crypto/gcm.c (ffffffff8148955e)
Location: include/crypto/aead.h:230
Inline: True
Inline callers:
  - crypto/gcm.c:crypto_rfc4543_copy_src_to_dst
  - crypto/gcm.c:crypto_rfc4543_crypt
  - crypto/gcm.c:crypto_rfc4543_crypt
  - crypto/gcm.c:crypto_rfc4106_decrypt
  - crypto/gcm.c:crypto_gcm_decrypt
  - crypto/gcm.c:crypto_gcm_verify
  - crypto/gcm.c:gcm_enc_copy_hash
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
In crypto/aead.c (ffffffff814a67ac)
Location: include/crypto/aead.h:225
Inline: True
Inline callers:
  - crypto/aead.c:crypto_aead_decrypt
```
```
In crypto/skcipher.c (ffffffff814aa095)
Location: include/crypto/aead.h:225
Inline: True
Inline callers:
  - crypto/skcipher.c:skcipher_walk_aead_decrypt
```
```
In crypto/seqiv.c (ffffffff814aa1dc)
Location: include/crypto/aead.h:225
Inline: True
Inline callers:
  - crypto/seqiv.c:seqiv_aead_decrypt
```
```
In crypto/gcm.c (ffffffff814b6213)
Location: include/crypto/aead.h:225
Inline: True
Inline callers:
  - crypto/gcm.c:crypto_rfc4543_copy_src_to_dst
  - crypto/gcm.c:crypto_rfc4543_crypt
  - crypto/gcm.c:crypto_gcm_decrypt
  - crypto/gcm.c:crypto_gcm_verify
  - crypto/gcm.c:gcm_enc_copy_hash
```
```
In net/xfrm/xfrm_state.c (ffffffff819eec08)
Location: include/crypto/aead.h:225
Inline: True
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
In crypto/aead.c (ffffffff814c141c)
Location: include/crypto/aead.h:225
Inline: True
Inline callers:
  - crypto/aead.c:crypto_aead_decrypt
```
```
In crypto/skcipher.c (ffffffff814c4d85)
Location: include/crypto/aead.h:225
Inline: True
Inline callers:
  - crypto/skcipher.c:skcipher_walk_aead_decrypt
```
```
In crypto/seqiv.c (ffffffff814c4e9c)
Location: include/crypto/aead.h:225
Inline: True
Inline callers:
  - crypto/seqiv.c:seqiv_aead_decrypt
```
```
In crypto/gcm.c (ffffffff814cf413)
Location: include/crypto/aead.h:225
Inline: True
Inline callers:
  - crypto/gcm.c:crypto_rfc4543_copy_src_to_dst
  - crypto/gcm.c:crypto_rfc4543_crypt
  - crypto/gcm.c:crypto_gcm_decrypt
  - crypto/gcm.c:crypto_gcm_verify
  - crypto/gcm.c:gcm_enc_copy_hash
```
```
In net/xfrm/xfrm_state.c (ffffffff81a25ae8)
Location: include/crypto/aead.h:225
Inline: True
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
In crypto/aead.c (ffffffff81521dec)
Location: include/crypto/aead.h:231
Inline: True
Inline callers:
  - crypto/aead.c:crypto_aead_decrypt
```
```
In crypto/skcipher.c (ffffffff81523bf5)
Location: include/crypto/aead.h:231
Inline: True
Inline callers:
  - crypto/skcipher.c:skcipher_walk_aead_decrypt
```
```
In crypto/seqiv.c (ffffffff81523dac)
Location: include/crypto/aead.h:231
Inline: True
Inline callers:
  - crypto/seqiv.c:seqiv_aead_decrypt
```
```
In crypto/gcm.c (ffffffff8152e633)
Location: include/crypto/aead.h:231
Inline: True
Inline callers:
  - crypto/gcm.c:crypto_rfc4543_copy_src_to_dst
  - crypto/gcm.c:crypto_rfc4543_crypt
  - crypto/gcm.c:crypto_gcm_decrypt
  - crypto/gcm.c:crypto_gcm_verify
  - crypto/gcm.c:gcm_enc_copy_hash
```
```
In net/xfrm/xfrm_state.c (ffffffff81b175c9)
Location: include/crypto/aead.h:231
Inline: True
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
In crypto/aead.c (ffffffff8153ec3c)
Location: include/crypto/aead.h:236
Inline: True
Inline callers:
  - crypto/aead.c:crypto_aead_decrypt
```
```
In crypto/skcipher.c (ffffffff81540b45)
Location: include/crypto/aead.h:236
Inline: True
Inline callers:
  - crypto/skcipher.c:skcipher_walk_aead_decrypt
```
```
In crypto/seqiv.c (ffffffff81540c2c)
Location: include/crypto/aead.h:236
Inline: True
Inline callers:
  - crypto/seqiv.c:seqiv_aead_decrypt
```
```
In crypto/gcm.c (ffffffff8154b5d3)
Location: include/crypto/aead.h:236
Inline: True
Inline callers:
  - crypto/gcm.c:crypto_rfc4543_copy_src_to_dst
  - crypto/gcm.c:crypto_rfc4543_crypt
  - crypto/gcm.c:crypto_gcm_decrypt
  - crypto/gcm.c:crypto_gcm_verify
  - crypto/gcm.c:gcm_enc_copy_hash
```
```
In net/xfrm/xfrm_state.c (ffffffff81b25689)
Location: include/crypto/aead.h:236
Inline: True
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
In crypto/aead.c (ffffffff815472dc)
Location: include/crypto/aead.h:238
Inline: True
Inline callers:
  - crypto/aead.c:crypto_aead_decrypt
```
```
In crypto/skcipher.c (ffffffff815491a5)
Location: include/crypto/aead.h:238
Inline: True
Inline callers:
  - crypto/skcipher.c:skcipher_walk_aead_decrypt
```
```
In crypto/seqiv.c (ffffffff81549299)
Location: include/crypto/aead.h:238
Inline: True
Inline callers:
  - crypto/seqiv.c:seqiv_aead_decrypt
```
```
In crypto/gcm.c (ffffffff81553be3)
Location: include/crypto/aead.h:238
Inline: True
Inline callers:
  - crypto/gcm.c:crypto_rfc4543_copy_src_to_dst
  - crypto/gcm.c:crypto_rfc4543_crypt
  - crypto/gcm.c:crypto_gcm_decrypt
  - crypto/gcm.c:crypto_gcm_verify
  - crypto/gcm.c:gcm_enc_copy_hash
```
```
In net/xfrm/xfrm_state.c (ffffffff81b131a1)
Location: include/crypto/aead.h:238
Inline: True
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
In crypto/aead.c (ffffffff815a7abc)
Location: include/crypto/aead.h:238
Inline: True
Inline callers:
  - crypto/aead.c:crypto_aead_decrypt
```
```
In crypto/skcipher.c (ffffffff815a9985)
Location: include/crypto/aead.h:238
Inline: True
Inline callers:
  - crypto/skcipher.c:skcipher_walk_aead_decrypt
```
```
In crypto/seqiv.c (ffffffff815a9a79)
Location: include/crypto/aead.h:238
Inline: True
Inline callers:
  - crypto/seqiv.c:seqiv_aead_decrypt
```
```
In crypto/gcm.c (ffffffff815b4c13)
Location: include/crypto/aead.h:238
Inline: True
Inline callers:
  - crypto/gcm.c:crypto_rfc4543_copy_src_to_dst
  - crypto/gcm.c:crypto_rfc4543_crypt
  - crypto/gcm.c:crypto_gcm_decrypt
  - crypto/gcm.c:crypto_gcm_verify
  - crypto/gcm.c:gcm_enc_copy_hash
```
```
In net/xfrm/xfrm_state.c (ffffffff81bd70a1)
Location: include/crypto/aead.h:238
Inline: True
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
In crypto/aead.c (ffffffff8164ee1f)
Location: include/crypto/aead.h:240
Inline: True
Inline callers:
  - crypto/aead.c:crypto_aead_decrypt
```
```
In crypto/skcipher.c (ffffffff81650e15)
Location: include/crypto/aead.h:240
Inline: True
Inline callers:
  - crypto/skcipher.c:skcipher_walk_aead_decrypt
```
```
In crypto/seqiv.c (ffffffff81650f38)
Location: include/crypto/aead.h:240
Inline: True
Inline callers:
  - crypto/seqiv.c:seqiv_aead_decrypt
```
```
In crypto/gcm.c (ffffffff8165db9b)
Location: include/crypto/aead.h:240
Inline: True
Inline callers:
  - crypto/gcm.c:crypto_rfc4543_copy_src_to_dst
  - crypto/gcm.c:crypto_rfc4543_crypt
  - crypto/gcm.c:crypto_gcm_decrypt
  - crypto/gcm.c:crypto_gcm_verify
  - crypto/gcm.c:gcm_enc_copy_hash
```
```
In net/xfrm/xfrm_state.c (ffffffff81d6da61)
Location: include/crypto/aead.h:240
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
In crypto/aead.c (ffffffff8170822f)
Location: include/crypto/aead.h:240
Inline: True
Inline callers:
  - crypto/aead.c:crypto_aead_decrypt
```
```
In crypto/skcipher.c (ffffffff8170a625)
Location: include/crypto/aead.h:240
Inline: True
Inline callers:
  - crypto/skcipher.c:skcipher_walk_aead_decrypt
```
```
In crypto/seqiv.c (ffffffff8170a768)
Location: include/crypto/aead.h:240
Inline: True
Inline callers:
  - crypto/seqiv.c:seqiv_aead_decrypt
```
```
In crypto/gcm.c (ffffffff8171774b)
Location: include/crypto/aead.h:240
Inline: True
Inline callers:
  - crypto/gcm.c:crypto_rfc4543_copy_src_to_dst
  - crypto/gcm.c:crypto_rfc4543_crypt
  - crypto/gcm.c:crypto_gcm_decrypt
  - crypto/gcm.c:crypto_gcm_verify
  - crypto/gcm.c:gcm_enc_copy_hash
```
```
In net/xfrm/xfrm_state.c (ffffffff81f39061)
Location: include/crypto/aead.h:240
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
In crypto/aead.c (ffffffff81741eb5)
Location: include/crypto/aead.h:262
Inline: True
Inline callers:
  - crypto/aead.c:crypto_aead_decrypt
```
```
In crypto/skcipher.c (ffffffff81743e75)
Location: include/crypto/aead.h:262
Inline: True
Inline callers:
  - crypto/skcipher.c:skcipher_walk_aead_decrypt
```
```
In crypto/seqiv.c (ffffffff81743fb8)
Location: include/crypto/aead.h:262
Inline: True
Inline callers:
  - crypto/seqiv.c:seqiv_aead_decrypt
```
```
In crypto/gcm.c (ffffffff8175313b)
Location: include/crypto/aead.h:262
Inline: True
Inline callers:
  - crypto/gcm.c:crypto_rfc4543_copy_src_to_dst
  - crypto/gcm.c:crypto_rfc4543_crypt
  - crypto/gcm.c:crypto_gcm_decrypt
  - crypto/gcm.c:crypto_gcm_verify
  - crypto/gcm.c:gcm_enc_copy_hash
```
```
In net/xfrm/xfrm_state.c (ffffffff81f988f1)
Location: include/crypto/aead.h:262
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
In crypto/aead.c (ffffffff81782d95)
Location: include/crypto/aead.h:274
Inline: True
Inline callers:
  - crypto/aead.c:crypto_aead_decrypt
```
```
In crypto/skcipher.c (ffffffff81786255)
Location: include/crypto/aead.h:274
Inline: True
Inline callers:
  - crypto/skcipher.c:skcipher_walk_aead_decrypt
```
```
In crypto/seqiv.c (ffffffff81786578)
Location: include/crypto/aead.h:274
Inline: True
Inline callers:
  - crypto/seqiv.c:seqiv_aead_decrypt
```
```
In crypto/gcm.c (ffffffff8179500b)
Location: include/crypto/aead.h:274
Inline: True
Inline callers:
  - crypto/gcm.c:crypto_rfc4543_copy_src_to_dst
  - crypto/gcm.c:crypto_rfc4543_crypt
  - crypto/gcm.c:crypto_gcm_decrypt
  - crypto/gcm.c:crypto_gcm_verify
  - crypto/gcm.c:gcm_enc_copy_hash
```
```
In net/xfrm/xfrm_state.c (ffffffff82065c61)
Location: include/crypto/aead.h:274
Inline: True
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
In crypto/aead.c (ffff8000105bb770)
Location: include/crypto/aead.h:225
Inline: True
Inline callers:
  - crypto/aead.c:crypto_aead_decrypt
```
```
In crypto/skcipher.c (ffff8000105bf8c4)
Location: include/crypto/aead.h:225
Inline: True
Inline callers:
  - crypto/skcipher.c:skcipher_walk_aead_decrypt
```
```
In crypto/seqiv.c (ffff8000105bfa50)
Location: include/crypto/aead.h:225
Inline: True
Inline callers:
  - crypto/seqiv.c:seqiv_aead_decrypt
```
```
In crypto/gcm.c (ffff8000105cb420)
Location: include/crypto/aead.h:225
Inline: True
Inline callers:
  - crypto/gcm.c:crypto_rfc4543_copy_src_to_dst
  - crypto/gcm.c:crypto_rfc4543_crypt
  - crypto/gcm.c:crypto_gcm_decrypt
  - crypto/gcm.c:crypto_gcm_verify
  - crypto/gcm.c:gcm_enc_copy_hash
```
```
In net/xfrm/xfrm_state.c (ffff800010ce2fac)
Location: include/crypto/aead.h:225
Inline: True
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
In crypto/aead.c (c07699a8)
Location: include/crypto/aead.h:225
Inline: True
Inline callers:
  - crypto/aead.c:crypto_aead_decrypt
```
```
In crypto/skcipher.c (c076d570)
Location: include/crypto/aead.h:225
Inline: True
Inline callers:
  - crypto/skcipher.c:skcipher_walk_aead_decrypt
```
```
In crypto/seqiv.c (c076d6a8)
Location: include/crypto/aead.h:225
Inline: True
Inline callers:
  - crypto/seqiv.c:seqiv_aead_decrypt
```
```
In crypto/gcm.c (c0778f28)
Location: include/crypto/aead.h:225
Inline: True
Inline callers:
  - crypto/gcm.c:crypto_rfc4543_copy_src_to_dst
  - crypto/gcm.c:crypto_rfc4543_crypt
  - crypto/gcm.c:crypto_gcm_decrypt
  - crypto/gcm.c:crypto_gcm_verify
  - crypto/gcm.c:gcm_enc_copy_hash
```
```
In net/xfrm/xfrm_state.c (c0dec77c)
Location: include/crypto/aead.h:225
Inline: True
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
In crypto/aead.c (c0000000007420e8)
Location: include/crypto/aead.h:225
Inline: True
Inline callers:
  - crypto/aead.c:crypto_aead_decrypt
```
```
In crypto/skcipher.c (c000000000747630)
Location: include/crypto/aead.h:225
Inline: True
Inline callers:
  - crypto/skcipher.c:skcipher_walk_aead_decrypt
```
```
In crypto/seqiv.c (c000000000747818)
Location: include/crypto/aead.h:225
Inline: True
Inline callers:
  - crypto/seqiv.c:seqiv_aead_decrypt
```
```
In crypto/gcm.c (c000000000756444)
Location: include/crypto/aead.h:225
Inline: True
Inline callers:
  - crypto/gcm.c:crypto_rfc4543_copy_src_to_dst
  - crypto/gcm.c:crypto_rfc4543_crypt
  - crypto/gcm.c:crypto_gcm_decrypt
  - crypto/gcm.c:crypto_gcm_verify
  - crypto/gcm.c:gcm_enc_copy_hash
```
```
In net/xfrm/xfrm_state.c (c000000000e06458)
Location: include/crypto/aead.h:225
Inline: True
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
In crypto/aead.c (ffffffe0004011b8)
Location: include/crypto/aead.h:225
Inline: True
Inline callers:
  - crypto/aead.c:crypto_aead_decrypt
```
```
In crypto/skcipher.c (ffffffe0004049f4)
Location: include/crypto/aead.h:225
Inline: True
Inline callers:
  - crypto/skcipher.c:skcipher_walk_aead_decrypt
```
```
In crypto/seqiv.c (ffffffe000404b2c)
Location: include/crypto/aead.h:225
Inline: True
Inline callers:
  - crypto/seqiv.c:seqiv_aead_decrypt
```
```
In crypto/gcm.c (ffffffe00040f79c)
Location: include/crypto/aead.h:225
Inline: True
Inline callers:
  - crypto/gcm.c:crypto_rfc4543_copy_src_to_dst
  - crypto/gcm.c:crypto_rfc4543_crypt
  - crypto/gcm.c:crypto_gcm_decrypt
  - crypto/gcm.c:crypto_gcm_verify
  - crypto/gcm.c:gcm_enc_copy_hash
```
```
In net/xfrm/xfrm_state.c (ffffffe00083186e)
Location: include/crypto/aead.h:225
Inline: True
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
In crypto/aead.c (ffffffff814b99fc)
Location: include/crypto/aead.h:225
Inline: True
Inline callers:
  - crypto/aead.c:crypto_aead_decrypt
```
```
In crypto/skcipher.c (ffffffff814bd365)
Location: include/crypto/aead.h:225
Inline: True
Inline callers:
  - crypto/skcipher.c:skcipher_walk_aead_decrypt
```
```
In crypto/seqiv.c (ffffffff814bd47c)
Location: include/crypto/aead.h:225
Inline: True
Inline callers:
  - crypto/seqiv.c:seqiv_aead_decrypt
```
```
In crypto/gcm.c (ffffffff814c79f3)
Location: include/crypto/aead.h:225
Inline: True
Inline callers:
  - crypto/gcm.c:crypto_rfc4543_copy_src_to_dst
  - crypto/gcm.c:crypto_rfc4543_crypt
  - crypto/gcm.c:crypto_gcm_decrypt
  - crypto/gcm.c:crypto_gcm_verify
  - crypto/gcm.c:gcm_enc_copy_hash
```
```
In net/xfrm/xfrm_state.c (ffffffff819c5178)
Location: include/crypto/aead.h:225
Inline: True
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
In crypto/aead.c (ffffffff814aa41c)
Location: include/crypto/aead.h:225
Inline: True
Inline callers:
  - crypto/aead.c:crypto_aead_decrypt
```
```
In crypto/skcipher.c (ffffffff814add85)
Location: include/crypto/aead.h:225
Inline: True
Inline callers:
  - crypto/skcipher.c:skcipher_walk_aead_decrypt
```
```
In crypto/seqiv.c (ffffffff814ade9c)
Location: include/crypto/aead.h:225
Inline: True
Inline callers:
  - crypto/seqiv.c:seqiv_aead_decrypt
```
```
In crypto/gcm.c (ffffffff814b8413)
Location: include/crypto/aead.h:225
Inline: True
Inline callers:
  - crypto/gcm.c:crypto_rfc4543_copy_src_to_dst
  - crypto/gcm.c:crypto_rfc4543_crypt
  - crypto/gcm.c:crypto_gcm_decrypt
  - crypto/gcm.c:crypto_gcm_verify
  - crypto/gcm.c:gcm_enc_copy_hash
```
```
In net/xfrm/xfrm_state.c (ffffffff81981f68)
Location: include/crypto/aead.h:225
Inline: True
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
In crypto/aead.c (ffffffff814b5a8c)
Location: include/crypto/aead.h:225
Inline: True
Inline callers:
  - crypto/aead.c:crypto_aead_decrypt
```
```
In crypto/skcipher.c (ffffffff814b93f5)
Location: include/crypto/aead.h:225
Inline: True
Inline callers:
  - crypto/skcipher.c:skcipher_walk_aead_decrypt
```
```
In crypto/seqiv.c (ffffffff814b950c)
Location: include/crypto/aead.h:225
Inline: True
Inline callers:
  - crypto/seqiv.c:seqiv_aead_decrypt
```
```
In crypto/gcm.c (ffffffff814c3a83)
Location: include/crypto/aead.h:225
Inline: True
Inline callers:
  - crypto/gcm.c:crypto_rfc4543_copy_src_to_dst
  - crypto/gcm.c:crypto_rfc4543_crypt
  - crypto/gcm.c:crypto_gcm_decrypt
  - crypto/gcm.c:crypto_gcm_verify
  - crypto/gcm.c:gcm_enc_copy_hash
```
```
In net/xfrm/xfrm_state.c (ffffffff81a2fbf8)
Location: include/crypto/aead.h:225
Inline: True
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
In crypto/aead.c (ffffffff814ce52c)
Location: include/crypto/aead.h:225
Inline: True
Inline callers:
  - crypto/aead.c:crypto_aead_decrypt
```
```
In crypto/skcipher.c (ffffffff814d1e95)
Location: include/crypto/aead.h:225
Inline: True
Inline callers:
  - crypto/skcipher.c:skcipher_walk_aead_decrypt
```
```
In crypto/seqiv.c (ffffffff814d1fac)
Location: include/crypto/aead.h:225
Inline: True
Inline callers:
  - crypto/seqiv.c:seqiv_aead_decrypt
```
```
In crypto/gcm.c (ffffffff814dc553)
Location: include/crypto/aead.h:225
Inline: True
Inline callers:
  - crypto/gcm.c:crypto_rfc4543_copy_src_to_dst
  - crypto/gcm.c:crypto_rfc4543_crypt
  - crypto/gcm.c:crypto_gcm_decrypt
  - crypto/gcm.c:crypto_gcm_verify
  - crypto/gcm.c:gcm_enc_copy_hash
```
```
In net/xfrm/xfrm_state.c (ffffffff81a3b598)
Location: include/crypto/aead.h:225
Inline: True
```
</details>
</li>
</ul>

## Differences
