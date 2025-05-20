# Function: <code>crypto_aead_tfm</code>

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
In crypto/aead.c (ffffffff8139f17d)
Location: include/crypto/aead.h:179
Inline: True
Inline callers:
  - crypto/aead.c:aead_exit_geniv
```
```
In crypto/blkcipher.c (0)
Location: include/crypto/aead.h:179
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
In crypto/aead.c (ffffffff813dbf1d)
Location: include/crypto/aead.h:182
Inline: True
Inline callers:
  - crypto/aead.c:aead_exit_geniv
```
```
In crypto/blkcipher.c (0)
Location: include/crypto/aead.h:182
Inline: True
```
```
In crypto/seqiv.c (ffffffff813de7d7)
Location: include/crypto/aead.h:182
Inline: True
Inline callers:
  - crypto/seqiv.c:seqiv_aead_decrypt
  - crypto/seqiv.c:seqiv_aead_encrypt
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
In crypto/aead.c (ffffffff813f37fd)
Location: include/crypto/aead.h:182
Inline: True
Inline callers:
  - crypto/aead.c:aead_exit_geniv
```
```
In crypto/blkcipher.c (0)
Location: include/crypto/aead.h:182
Inline: True
```
```
In crypto/skcipher.c (0)
Location: include/crypto/aead.h:182
Inline: True
```
```
In crypto/seqiv.c (ffffffff813f6d77)
Location: include/crypto/aead.h:182
Inline: True
Inline callers:
  - crypto/seqiv.c:seqiv_aead_decrypt
  - crypto/seqiv.c:seqiv_aead_encrypt
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
In crypto/aead.c (ffffffff813ffb1d)
Location: include/crypto/aead.h:182
Inline: True
Inline callers:
  - crypto/aead.c:aead_exit_geniv
```
```
In crypto/blkcipher.c (0)
Location: include/crypto/aead.h:182
Inline: True
```
```
In crypto/skcipher.c (0)
Location: include/crypto/aead.h:182
Inline: True
```
```
In crypto/seqiv.c (ffffffff81403157)
Location: include/crypto/aead.h:182
Inline: True
Inline callers:
  - crypto/seqiv.c:seqiv_aead_decrypt
  - crypto/seqiv.c:seqiv_aead_encrypt
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
In security/keys/big_key.c (ffffffff826eb6de)
Location: include/crypto/aead.h:182
Inline: True
Inline callers:
  - security/keys/big_key.c:big_key_init
  - security/keys/big_key.c:big_key_crypt
```
```
In crypto/aead.c (ffffffff8142810d)
Location: include/crypto/aead.h:182
Inline: True
Inline callers:
  - crypto/aead.c:aead_exit_geniv
```
```
In crypto/blkcipher.c (0)
Location: include/crypto/aead.h:182
Inline: True
```
```
In crypto/skcipher.c (0)
Location: include/crypto/aead.h:182
Inline: True
```
```
In crypto/seqiv.c (ffffffff8142b837)
Location: include/crypto/aead.h:182
Inline: True
Inline callers:
  - crypto/seqiv.c:seqiv_aead_decrypt
  - crypto/seqiv.c:seqiv_aead_encrypt
```
```
In crypto/gcm.c (ffffffff8143919d)
Location: include/crypto/aead.h:182
Inline: True
Inline callers:
  - crypto/gcm.c:crypto_rfc4543_exit_tfm
  - crypto/gcm.c:crypto_rfc4543_init_tfm
  - crypto/gcm.c:crypto_rfc4543_crypt
  - crypto/gcm.c:crypto_rfc4106_exit_tfm
  - crypto/gcm.c:crypto_rfc4106_crypt
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
In security/keys/big_key.c (ffffffff82715c03)
Location: include/crypto/aead.h:182
Inline: True
Inline callers:
  - security/keys/big_key.c:big_key_init
  - security/keys/big_key.c:big_key_crypt
```
```
In crypto/aead.c (ffffffff8145af5a)
Location: include/crypto/aead.h:182
Inline: True
Inline callers:
  - crypto/aead.c:aead_exit_geniv
```
```
In crypto/blkcipher.c (0)
Location: include/crypto/aead.h:182
Inline: True
```
```
In crypto/skcipher.c (0)
Location: include/crypto/aead.h:182
Inline: True
```
```
In crypto/seqiv.c (ffffffff8145e542)
Location: include/crypto/aead.h:182
Inline: True
Inline callers:
  - crypto/seqiv.c:seqiv_aead_decrypt
  - crypto/seqiv.c:seqiv_aead_encrypt
```
```
In crypto/gcm.c (ffffffff8146b4da)
Location: include/crypto/aead.h:182
Inline: True
Inline callers:
  - crypto/gcm.c:crypto_rfc4543_exit_tfm
  - crypto/gcm.c:crypto_rfc4543_init_tfm
  - crypto/gcm.c:crypto_rfc4543_crypt
  - crypto/gcm.c:crypto_rfc4106_exit_tfm
  - crypto/gcm.c:crypto_rfc4106_crypt
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
In security/keys/big_key.c (ffffffff828cd04e)
Location: include/crypto/aead.h:179
Inline: True
Inline callers:
  - security/keys/big_key.c:big_key_init
  - security/keys/big_key.c:big_key_crypt
```
```
In crypto/aead.c (ffffffff81478a1a)
Location: include/crypto/aead.h:179
Inline: True
Inline callers:
  - crypto/aead.c:aead_exit_geniv
```
```
In crypto/blkcipher.c (0)
Location: include/crypto/aead.h:179
Inline: True
```
```
In crypto/skcipher.c (0)
Location: include/crypto/aead.h:179
Inline: True
```
```
In crypto/seqiv.c (ffffffff8147be02)
Location: include/crypto/aead.h:179
Inline: True
Inline callers:
  - crypto/seqiv.c:seqiv_aead_decrypt
  - crypto/seqiv.c:seqiv_aead_encrypt
```
```
In crypto/gcm.c (ffffffff81488b5a)
Location: include/crypto/aead.h:179
Inline: True
Inline callers:
  - crypto/gcm.c:crypto_rfc4543_exit_tfm
  - crypto/gcm.c:crypto_rfc4543_init_tfm
  - crypto/gcm.c:crypto_rfc4543_crypt
  - crypto/gcm.c:crypto_rfc4106_exit_tfm
  - crypto/gcm.c:crypto_rfc4106_crypt
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
In security/keys/big_key.c (ffffffff828e6a1d)
Location: include/crypto/aead.h:174
Inline: True
Inline callers:
  - security/keys/big_key.c:big_key_init
  - security/keys/big_key.c:big_key_crypt
```
```
In crypto/aead.c (ffffffff814a683a)
Location: include/crypto/aead.h:174
Inline: True
Inline callers:
  - crypto/aead.c:aead_exit_geniv
```
```
In crypto/blkcipher.c (0)
Location: include/crypto/aead.h:174
Inline: True
```
```
In crypto/skcipher.c (0)
Location: include/crypto/aead.h:174
Inline: True
```
```
In crypto/seqiv.c (ffffffff814aa1fa)
Location: include/crypto/aead.h:174
Inline: True
Inline callers:
  - crypto/seqiv.c:seqiv_aead_decrypt
  - crypto/seqiv.c:seqiv_aead_encrypt
```
```
In crypto/gcm.c (ffffffff814b656a)
Location: include/crypto/aead.h:174
Inline: True
Inline callers:
  - crypto/gcm.c:crypto_rfc4543_exit_tfm
  - crypto/gcm.c:crypto_rfc4543_init_tfm
  - crypto/gcm.c:crypto_rfc4543_crypt
  - crypto/gcm.c:crypto_rfc4106_exit_tfm
  - crypto/gcm.c:crypto_rfc4106_crypt
```
```
In net/xfrm/xfrm_state.c (0)
Location: include/crypto/aead.h:174
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
In security/keys/big_key.c (ffffffff828ef4d6)
Location: include/crypto/aead.h:174
Inline: True
Inline callers:
  - security/keys/big_key.c:big_key_init
  - security/keys/big_key.c:big_key_crypt
```
```
In crypto/aead.c (ffffffff814c14aa)
Location: include/crypto/aead.h:174
Inline: True
Inline callers:
  - crypto/aead.c:aead_exit_geniv
```
```
In crypto/blkcipher.c (0)
Location: include/crypto/aead.h:174
Inline: True
```
```
In crypto/skcipher.c (0)
Location: include/crypto/aead.h:174
Inline: True
```
```
In crypto/seqiv.c (ffffffff814c4eba)
Location: include/crypto/aead.h:174
Inline: True
Inline callers:
  - crypto/seqiv.c:seqiv_aead_decrypt
  - crypto/seqiv.c:seqiv_aead_encrypt
```
```
In crypto/gcm.c (ffffffff814cf78a)
Location: include/crypto/aead.h:174
Inline: True
Inline callers:
  - crypto/gcm.c:crypto_rfc4543_exit_tfm
  - crypto/gcm.c:crypto_rfc4543_init_tfm
  - crypto/gcm.c:crypto_rfc4543_crypt
  - crypto/gcm.c:crypto_rfc4106_exit_tfm
  - crypto/gcm.c:crypto_rfc4106_crypt
```
```
In net/xfrm/xfrm_state.c (0)
Location: include/crypto/aead.h:174
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
In crypto/aead.c (0)
Location: include/crypto/aead.h:180
Inline: True
```
```
In crypto/geniv.c (ffffffff815222aa)
Location: include/crypto/aead.h:180
Inline: True
Inline callers:
  - crypto/geniv.c:aead_exit_geniv
```
```
In crypto/skcipher.c (0)
Location: include/crypto/aead.h:180
Inline: True
```
```
In crypto/seqiv.c (ffffffff81523dce)
Location: include/crypto/aead.h:180
Inline: True
Inline callers:
  - crypto/seqiv.c:seqiv_aead_decrypt
  - crypto/seqiv.c:seqiv_aead_encrypt
```
```
In crypto/gcm.c (ffffffff8152e98a)
Location: include/crypto/aead.h:180
Inline: True
Inline callers:
  - crypto/gcm.c:crypto_rfc4543_exit_tfm
  - crypto/gcm.c:crypto_rfc4543_init_tfm
  - crypto/gcm.c:crypto_rfc4543_crypt
  - crypto/gcm.c:crypto_rfc4106_exit_tfm
  - crypto/gcm.c:crypto_rfc4106_crypt
```
```
In net/xfrm/xfrm_state.c (0)
Location: include/crypto/aead.h:180
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
In crypto/aead.c (0)
Location: include/crypto/aead.h:180
Inline: True
```
```
In crypto/geniv.c (ffffffff8153f18a)
Location: include/crypto/aead.h:180
Inline: True
Inline callers:
  - crypto/geniv.c:aead_exit_geniv
```
```
In crypto/skcipher.c (0)
Location: include/crypto/aead.h:180
Inline: True
```
```
In crypto/seqiv.c (ffffffff81540c4e)
Location: include/crypto/aead.h:180
Inline: True
Inline callers:
  - crypto/seqiv.c:seqiv_aead_decrypt
  - crypto/seqiv.c:seqiv_aead_encrypt
```
```
In crypto/gcm.c (ffffffff8154b90a)
Location: include/crypto/aead.h:180
Inline: True
Inline callers:
  - crypto/gcm.c:crypto_rfc4543_exit_tfm
  - crypto/gcm.c:crypto_rfc4543_init_tfm
  - crypto/gcm.c:crypto_rfc4543_crypt
  - crypto/gcm.c:crypto_rfc4106_exit_tfm
  - crypto/gcm.c:crypto_rfc4106_crypt
```
```
In net/xfrm/xfrm_state.c (0)
Location: include/crypto/aead.h:180
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
In crypto/aead.c (0)
Location: include/crypto/aead.h:180
Inline: True
```
```
In crypto/geniv.c (ffffffff8154780a)
Location: include/crypto/aead.h:180
Inline: True
Inline callers:
  - crypto/geniv.c:aead_exit_geniv
```
```
In crypto/skcipher.c (0)
Location: include/crypto/aead.h:180
Inline: True
```
```
In crypto/seqiv.c (ffffffff815492a3)
Location: include/crypto/aead.h:180
Inline: True
Inline callers:
  - crypto/seqiv.c:seqiv_aead_decrypt
  - crypto/seqiv.c:seqiv_aead_encrypt
```
```
In crypto/gcm.c (ffffffff81553f0a)
Location: include/crypto/aead.h:180
Inline: True
Inline callers:
  - crypto/gcm.c:crypto_rfc4543_exit_tfm
  - crypto/gcm.c:crypto_rfc4543_init_tfm
  - crypto/gcm.c:crypto_rfc4543_crypt
  - crypto/gcm.c:crypto_rfc4106_exit_tfm
  - crypto/gcm.c:crypto_rfc4106_crypt
```
```
In net/xfrm/xfrm_state.c (0)
Location: include/crypto/aead.h:180
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
In crypto/aead.c (0)
Location: include/crypto/aead.h:180
Inline: True
```
```
In crypto/geniv.c (ffffffff815a7fea)
Location: include/crypto/aead.h:180
Inline: True
Inline callers:
  - crypto/geniv.c:aead_exit_geniv
```
```
In crypto/skcipher.c (0)
Location: include/crypto/aead.h:180
Inline: True
```
```
In crypto/seqiv.c (ffffffff815a9a83)
Location: include/crypto/aead.h:180
Inline: True
Inline callers:
  - crypto/seqiv.c:seqiv_aead_decrypt
  - crypto/seqiv.c:seqiv_aead_encrypt
```
```
In crypto/gcm.c (ffffffff815b4f3a)
Location: include/crypto/aead.h:180
Inline: True
Inline callers:
  - crypto/gcm.c:crypto_rfc4543_exit_tfm
  - crypto/gcm.c:crypto_rfc4543_init_tfm
  - crypto/gcm.c:crypto_rfc4543_crypt
  - crypto/gcm.c:crypto_rfc4106_exit_tfm
  - crypto/gcm.c:crypto_rfc4106_crypt
```
```
In net/xfrm/xfrm_state.c (0)
Location: include/crypto/aead.h:180
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
In crypto/aead.c (0)
Location: include/crypto/aead.h:182
Inline: True
```
```
In crypto/geniv.c (ffffffff8164f37a)
Location: include/crypto/aead.h:182
Inline: True
Inline callers:
  - crypto/geniv.c:aead_exit_geniv
```
```
In crypto/skcipher.c (0)
Location: include/crypto/aead.h:182
Inline: True
```
```
In crypto/seqiv.c (ffffffff81650f46)
Location: include/crypto/aead.h:182
Inline: True
Inline callers:
  - crypto/seqiv.c:seqiv_aead_decrypt
  - crypto/seqiv.c:seqiv_aead_encrypt
```
```
In crypto/gcm.c (ffffffff8165df9a)
Location: include/crypto/aead.h:182
Inline: True
Inline callers:
  - crypto/gcm.c:crypto_rfc4543_exit_tfm
  - crypto/gcm.c:crypto_rfc4543_init_tfm
  - crypto/gcm.c:crypto_rfc4543_crypt
  - crypto/gcm.c:crypto_rfc4106_exit_tfm
  - crypto/gcm.c:crypto_rfc4106_crypt
```
```
In net/xfrm/xfrm_state.c (0)
Location: include/crypto/aead.h:182
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
In crypto/aead.c (0)
Location: include/crypto/aead.h:182
Inline: True
```
```
In crypto/geniv.c (ffffffff8170896a)
Location: include/crypto/aead.h:182
Inline: True
Inline callers:
  - crypto/geniv.c:aead_exit_geniv
```
```
In crypto/skcipher.c (0)
Location: include/crypto/aead.h:182
Inline: True
```
```
In crypto/seqiv.c (ffffffff8170a776)
Location: include/crypto/aead.h:182
Inline: True
Inline callers:
  - crypto/seqiv.c:seqiv_aead_decrypt
  - crypto/seqiv.c:seqiv_aead_encrypt
```
```
In crypto/gcm.c (ffffffff817178ba)
Location: include/crypto/aead.h:182
Inline: True
Inline callers:
  - crypto/gcm.c:crypto_rfc4543_exit_tfm
  - crypto/gcm.c:crypto_rfc4543_init_tfm
  - crypto/gcm.c:crypto_rfc4543_crypt
  - crypto/gcm.c:crypto_rfc4106_exit_tfm
  - crypto/gcm.c:crypto_rfc4106_crypt
```
```
In net/xfrm/xfrm_state.c (0)
Location: include/crypto/aead.h:182
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
In crypto/aead.c (0)
Location: include/crypto/aead.h:204
Inline: True
```
```
In crypto/geniv.c (ffffffff8174211a)
Location: include/crypto/aead.h:204
Inline: True
Inline callers:
  - crypto/geniv.c:aead_exit_geniv
```
```
In crypto/skcipher.c (0)
Location: include/crypto/aead.h:204
Inline: True
```
```
In crypto/seqiv.c (ffffffff81743fc6)
Location: include/crypto/aead.h:204
Inline: True
Inline callers:
  - crypto/seqiv.c:seqiv_aead_decrypt
  - crypto/seqiv.c:seqiv_aead_encrypt
```
```
In crypto/gcm.c (ffffffff8175329a)
Location: include/crypto/aead.h:204
Inline: True
Inline callers:
  - crypto/gcm.c:crypto_rfc4543_exit_tfm
  - crypto/gcm.c:crypto_rfc4543_init_tfm
  - crypto/gcm.c:crypto_rfc4543_crypt
  - crypto/gcm.c:crypto_rfc4106_exit_tfm
  - crypto/gcm.c:crypto_rfc4106_crypt
```
```
In net/xfrm/xfrm_state.c (0)
Location: include/crypto/aead.h:204
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
In crypto/aead.c (0)
Location: include/crypto/aead.h:204
Inline: True
```
```
In crypto/geniv.c (ffffffff81782ffa)
Location: include/crypto/aead.h:204
Inline: True
Inline callers:
  - crypto/geniv.c:aead_exit_geniv
```
```
In crypto/skcipher.c (0)
Location: include/crypto/aead.h:204
Inline: True
```
```
In crypto/seqiv.c (ffffffff81786586)
Location: include/crypto/aead.h:204
Inline: True
Inline callers:
  - crypto/seqiv.c:seqiv_aead_decrypt
  - crypto/seqiv.c:seqiv_aead_encrypt
```
```
In crypto/gcm.c (ffffffff8179516a)
Location: include/crypto/aead.h:204
Inline: True
Inline callers:
  - crypto/gcm.c:crypto_rfc4543_exit_tfm
  - crypto/gcm.c:crypto_rfc4543_init_tfm
  - crypto/gcm.c:crypto_rfc4543_crypt
  - crypto/gcm.c:crypto_rfc4106_exit_tfm
  - crypto/gcm.c:crypto_rfc4106_crypt
```
```
In net/xfrm/xfrm_state.c (0)
Location: include/crypto/aead.h:204
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
In security/keys/big_key.c (ffff800011469190)
Location: include/crypto/aead.h:174
Inline: True
Inline callers:
  - security/keys/big_key.c:big_key_init
  - security/keys/big_key.c:big_key_crypt
```
```
In crypto/aead.c (ffff8000105bb81c)
Location: include/crypto/aead.h:174
Inline: True
Inline callers:
  - crypto/aead.c:aead_exit_geniv
```
```
In crypto/blkcipher.c (0)
Location: include/crypto/aead.h:174
Inline: True
```
```
In crypto/skcipher.c (0)
Location: include/crypto/aead.h:174
Inline: True
```
```
In crypto/seqiv.c (ffff8000105bfa64)
Location: include/crypto/aead.h:174
Inline: True
Inline callers:
  - crypto/seqiv.c:seqiv_aead_decrypt
  - crypto/seqiv.c:seqiv_aead_encrypt
```
```
In crypto/gcm.c (ffff8000105cb85c)
Location: include/crypto/aead.h:174
Inline: True
Inline callers:
  - crypto/gcm.c:crypto_rfc4543_exit_tfm
  - crypto/gcm.c:crypto_rfc4543_init_tfm
  - crypto/gcm.c:crypto_rfc4543_crypt
  - crypto/gcm.c:crypto_rfc4106_exit_tfm
  - crypto/gcm.c:crypto_rfc4106_crypt
```
```
In net/xfrm/xfrm_state.c (0)
Location: include/crypto/aead.h:174
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
In security/keys/big_key.c (c1541cd8)
Location: include/crypto/aead.h:174
Inline: True
Inline callers:
  - security/keys/big_key.c:big_key_init
  - security/keys/big_key.c:big_key_crypt
```
```
In crypto/aead.c (c0769a38)
Location: include/crypto/aead.h:174
Inline: True
Inline callers:
  - crypto/aead.c:aead_exit_geniv
```
```
In crypto/blkcipher.c (0)
Location: include/crypto/aead.h:174
Inline: True
```
```
In crypto/skcipher.c (0)
Location: include/crypto/aead.h:174
Inline: True
```
```
In crypto/seqiv.c (c076d6b8)
Location: include/crypto/aead.h:174
Inline: True
Inline callers:
  - crypto/seqiv.c:seqiv_aead_decrypt
  - crypto/seqiv.c:seqiv_aead_encrypt
```
```
In crypto/gcm.c (c07792b0)
Location: include/crypto/aead.h:174
Inline: True
Inline callers:
  - crypto/gcm.c:crypto_rfc4543_exit_tfm
  - crypto/gcm.c:crypto_rfc4543_init_tfm
  - crypto/gcm.c:crypto_rfc4543_crypt
  - crypto/gcm.c:crypto_rfc4106_exit_tfm
  - crypto/gcm.c:crypto_rfc4106_crypt
```
```
In net/xfrm/xfrm_state.c (0)
Location: include/crypto/aead.h:174
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
In security/keys/big_key.c (c000000001397248)
Location: include/crypto/aead.h:174
Inline: True
Inline callers:
  - security/keys/big_key.c:big_key_init
  - security/keys/big_key.c:big_key_crypt
```
```
In crypto/aead.c (c0000000007421e0)
Location: include/crypto/aead.h:174
Inline: True
Inline callers:
  - crypto/aead.c:aead_exit_geniv
```
```
In crypto/blkcipher.c (0)
Location: include/crypto/aead.h:174
Inline: True
```
```
In crypto/skcipher.c (0)
Location: include/crypto/aead.h:174
Inline: True
```
```
In crypto/seqiv.c (c000000000747854)
Location: include/crypto/aead.h:174
Inline: True
Inline callers:
  - crypto/seqiv.c:seqiv_aead_decrypt
  - crypto/seqiv.c:seqiv_aead_encrypt
```
```
In crypto/gcm.c (c000000000756940)
Location: include/crypto/aead.h:174
Inline: True
Inline callers:
  - crypto/gcm.c:crypto_rfc4543_exit_tfm
  - crypto/gcm.c:crypto_rfc4543_init_tfm
  - crypto/gcm.c:crypto_rfc4543_crypt
  - crypto/gcm.c:crypto_rfc4106_exit_tfm
  - crypto/gcm.c:crypto_rfc4106_crypt
```
```
In net/xfrm/xfrm_state.c (0)
Location: include/crypto/aead.h:174
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
In security/keys/big_key.c (ffffffe0000243d4)
Location: include/crypto/aead.h:174
Inline: True
Inline callers:
  - security/keys/big_key.c:big_key_init
  - security/keys/big_key.c:big_key_crypt
```
```
In crypto/aead.c (ffffffe000401248)
Location: include/crypto/aead.h:174
Inline: True
Inline callers:
  - crypto/aead.c:aead_exit_geniv
```
```
In crypto/blkcipher.c (0)
Location: include/crypto/aead.h:174
Inline: True
```
```
In crypto/skcipher.c (0)
Location: include/crypto/aead.h:174
Inline: True
```
```
In crypto/seqiv.c (ffffffe000404b36)
Location: include/crypto/aead.h:174
Inline: True
Inline callers:
  - crypto/seqiv.c:seqiv_aead_decrypt
  - crypto/seqiv.c:seqiv_aead_encrypt
```
```
In crypto/gcm.c (ffffffe00040fbac)
Location: include/crypto/aead.h:174
Inline: True
Inline callers:
  - crypto/gcm.c:crypto_rfc4543_exit_tfm
  - crypto/gcm.c:crypto_rfc4543_init_tfm
  - crypto/gcm.c:crypto_rfc4543_crypt
  - crypto/gcm.c:crypto_rfc4106_exit_tfm
  - crypto/gcm.c:crypto_rfc4106_crypt
```
```
In net/xfrm/xfrm_state.c (0)
Location: include/crypto/aead.h:174
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
In security/keys/big_key.c (ffffffff828d838a)
Location: include/crypto/aead.h:174
Inline: True
Inline callers:
  - security/keys/big_key.c:big_key_init
  - security/keys/big_key.c:big_key_crypt
```
```
In crypto/aead.c (ffffffff814b9a8a)
Location: include/crypto/aead.h:174
Inline: True
Inline callers:
  - crypto/aead.c:aead_exit_geniv
```
```
In crypto/blkcipher.c (0)
Location: include/crypto/aead.h:174
Inline: True
```
```
In crypto/skcipher.c (0)
Location: include/crypto/aead.h:174
Inline: True
```
```
In crypto/seqiv.c (ffffffff814bd49a)
Location: include/crypto/aead.h:174
Inline: True
Inline callers:
  - crypto/seqiv.c:seqiv_aead_decrypt
  - crypto/seqiv.c:seqiv_aead_encrypt
```
```
In crypto/gcm.c (ffffffff814c7d6a)
Location: include/crypto/aead.h:174
Inline: True
Inline callers:
  - crypto/gcm.c:crypto_rfc4543_exit_tfm
  - crypto/gcm.c:crypto_rfc4543_init_tfm
  - crypto/gcm.c:crypto_rfc4543_crypt
  - crypto/gcm.c:crypto_rfc4106_exit_tfm
  - crypto/gcm.c:crypto_rfc4106_crypt
```
```
In net/xfrm/xfrm_state.c (0)
Location: include/crypto/aead.h:174
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
In security/keys/big_key.c (ffffffff828d0aa6)
Location: include/crypto/aead.h:174
Inline: True
Inline callers:
  - security/keys/big_key.c:big_key_init
  - security/keys/big_key.c:big_key_crypt
```
```
In crypto/aead.c (ffffffff814aa4aa)
Location: include/crypto/aead.h:174
Inline: True
Inline callers:
  - crypto/aead.c:aead_exit_geniv
```
```
In crypto/blkcipher.c (0)
Location: include/crypto/aead.h:174
Inline: True
```
```
In crypto/skcipher.c (0)
Location: include/crypto/aead.h:174
Inline: True
```
```
In crypto/seqiv.c (ffffffff814adeba)
Location: include/crypto/aead.h:174
Inline: True
Inline callers:
  - crypto/seqiv.c:seqiv_aead_decrypt
  - crypto/seqiv.c:seqiv_aead_encrypt
```
```
In crypto/gcm.c (ffffffff814b878a)
Location: include/crypto/aead.h:174
Inline: True
Inline callers:
  - crypto/gcm.c:crypto_rfc4543_exit_tfm
  - crypto/gcm.c:crypto_rfc4543_init_tfm
  - crypto/gcm.c:crypto_rfc4543_crypt
  - crypto/gcm.c:crypto_rfc4106_exit_tfm
  - crypto/gcm.c:crypto_rfc4106_crypt
```
```
In net/xfrm/xfrm_state.c (0)
Location: include/crypto/aead.h:174
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
In security/keys/big_key.c (ffffffff828eb10a)
Location: include/crypto/aead.h:174
Inline: True
Inline callers:
  - security/keys/big_key.c:big_key_init
  - security/keys/big_key.c:big_key_crypt
```
```
In crypto/aead.c (ffffffff814b5b1a)
Location: include/crypto/aead.h:174
Inline: True
Inline callers:
  - crypto/aead.c:aead_exit_geniv
```
```
In crypto/blkcipher.c (0)
Location: include/crypto/aead.h:174
Inline: True
```
```
In crypto/skcipher.c (0)
Location: include/crypto/aead.h:174
Inline: True
```
```
In crypto/seqiv.c (ffffffff814b952a)
Location: include/crypto/aead.h:174
Inline: True
Inline callers:
  - crypto/seqiv.c:seqiv_aead_decrypt
  - crypto/seqiv.c:seqiv_aead_encrypt
```
```
In crypto/gcm.c (ffffffff814c3dfa)
Location: include/crypto/aead.h:174
Inline: True
Inline callers:
  - crypto/gcm.c:crypto_rfc4543_exit_tfm
  - crypto/gcm.c:crypto_rfc4543_init_tfm
  - crypto/gcm.c:crypto_rfc4543_crypt
  - crypto/gcm.c:crypto_rfc4106_exit_tfm
  - crypto/gcm.c:crypto_rfc4106_crypt
```
```
In net/xfrm/xfrm_state.c (0)
Location: include/crypto/aead.h:174
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
In security/keys/big_key.c (ffffffff828f0520)
Location: include/crypto/aead.h:174
Inline: True
Inline callers:
  - security/keys/big_key.c:big_key_init
  - security/keys/big_key.c:big_key_crypt
```
```
In crypto/aead.c (ffffffff814ce5ba)
Location: include/crypto/aead.h:174
Inline: True
Inline callers:
  - crypto/aead.c:aead_exit_geniv
```
```
In crypto/blkcipher.c (0)
Location: include/crypto/aead.h:174
Inline: True
```
```
In crypto/skcipher.c (0)
Location: include/crypto/aead.h:174
Inline: True
```
```
In crypto/seqiv.c (ffffffff814d1fca)
Location: include/crypto/aead.h:174
Inline: True
Inline callers:
  - crypto/seqiv.c:seqiv_aead_decrypt
  - crypto/seqiv.c:seqiv_aead_encrypt
```
```
In crypto/gcm.c (ffffffff814dc8ca)
Location: include/crypto/aead.h:174
Inline: True
Inline callers:
  - crypto/gcm.c:crypto_rfc4543_exit_tfm
  - crypto/gcm.c:crypto_rfc4543_init_tfm
  - crypto/gcm.c:crypto_rfc4543_crypt
  - crypto/gcm.c:crypto_rfc4106_exit_tfm
  - crypto/gcm.c:crypto_rfc4106_crypt
```
```
In net/xfrm/xfrm_state.c (0)
Location: include/crypto/aead.h:174
Inline: True
```
</details>
</li>
</ul>

## Differences
