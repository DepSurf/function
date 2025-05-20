# Function: <code>crypto_aead_reqsize</code>

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
In crypto/aead.c (0)
Location: include/crypto/aead.h:379
Inline: True
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
In crypto/aead.c (0)
Location: include/crypto/aead.h:382
Inline: True
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
In crypto/aead.c (0)
Location: include/crypto/aead.h:382
Inline: True
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
In crypto/aead.c (0)
Location: include/crypto/aead.h:382
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
Location: include/crypto/aead.h:382
Inline: True
```
```
In crypto/aead.c (0)
Location: include/crypto/aead.h:382
Inline: True
```
```
In crypto/gcm.c (0)
Location: include/crypto/aead.h:382
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
In security/keys/big_key.c (ffffffff813ecd59)
Location: include/crypto/aead.h:390
Inline: True
Inline callers:
  - security/keys/big_key.c:big_key_crypt
```
```
In crypto/aead.c (ffffffff8145af29)
Location: include/crypto/aead.h:390
Inline: True
Inline callers:
  - crypto/aead.c:aead_init_geniv
```
```
In crypto/gcm.c (ffffffff8146b53e)
Location: include/crypto/aead.h:390
Inline: True
Inline callers:
  - crypto/gcm.c:crypto_rfc4543_init_tfm
  - crypto/gcm.c:crypto_rfc4543_crypt
  - crypto/gcm.c:crypto_rfc4106_init_tfm
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
In security/keys/big_key.c (ffffffff81407ef9)
Location: include/crypto/aead.h:398
Inline: True
Inline callers:
  - security/keys/big_key.c:big_key_crypt
```
```
In crypto/aead.c (ffffffff81478eb2)
Location: include/crypto/aead.h:398
Inline: True
Inline callers:
  - crypto/aead.c:aead_init_geniv
```
```
In crypto/gcm.c (ffffffff81488bbe)
Location: include/crypto/aead.h:398
Inline: True
Inline callers:
  - crypto/gcm.c:crypto_rfc4543_init_tfm
  - crypto/gcm.c:crypto_rfc4543_crypt
  - crypto/gcm.c:crypto_rfc4106_init_tfm
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
In security/keys/big_key.c (ffffffff814351f0)
Location: include/crypto/aead.h:363
Inline: True
Inline callers:
  - security/keys/big_key.c:big_key_crypt
```
```
In crypto/aead.c (ffffffff814a6dc5)
Location: include/crypto/aead.h:363
Inline: True
Inline callers:
  - crypto/aead.c:aead_init_geniv
```
```
In crypto/gcm.c (ffffffff814b6613)
Location: include/crypto/aead.h:363
Inline: True
Inline callers:
  - crypto/gcm.c:crypto_rfc4543_init_tfm
  - crypto/gcm.c:crypto_rfc4543_crypt
  - crypto/gcm.c:crypto_rfc4106_init_tfm
  - crypto/gcm.c:crypto_rfc4106_crypt
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
In security/keys/big_key.c (ffffffff8144ef70)
Location: include/crypto/aead.h:363
Inline: True
Inline callers:
  - security/keys/big_key.c:big_key_crypt
```
```
In crypto/aead.c (ffffffff814c1a35)
Location: include/crypto/aead.h:363
Inline: True
Inline callers:
  - crypto/aead.c:aead_init_geniv
```
```
In crypto/gcm.c (ffffffff814cf833)
Location: include/crypto/aead.h:363
Inline: True
Inline callers:
  - crypto/gcm.c:crypto_rfc4543_init_tfm
  - crypto/gcm.c:crypto_rfc4543_crypt
  - crypto/gcm.c:crypto_rfc4106_init_tfm
  - crypto/gcm.c:crypto_rfc4106_crypt
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
In crypto/geniv.c (ffffffff81522375)
Location: include/crypto/aead.h:379
Inline: True
Inline callers:
  - crypto/geniv.c:aead_init_geniv
```
```
In crypto/gcm.c (ffffffff8152ea33)
Location: include/crypto/aead.h:379
Inline: True
Inline callers:
  - crypto/gcm.c:crypto_rfc4543_init_tfm
  - crypto/gcm.c:crypto_rfc4543_crypt
  - crypto/gcm.c:crypto_rfc4106_init_tfm
  - crypto/gcm.c:crypto_rfc4106_crypt
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
In crypto/geniv.c (ffffffff8153f255)
Location: include/crypto/aead.h:384
Inline: True
Inline callers:
  - crypto/geniv.c:aead_init_geniv
```
```
In crypto/gcm.c (ffffffff8154b9b3)
Location: include/crypto/aead.h:384
Inline: True
Inline callers:
  - crypto/gcm.c:crypto_rfc4543_init_tfm
  - crypto/gcm.c:crypto_rfc4543_crypt
  - crypto/gcm.c:crypto_rfc4106_init_tfm
  - crypto/gcm.c:crypto_rfc4106_crypt
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
In crypto/geniv.c (ffffffff815478d5)
Location: include/crypto/aead.h:386
Inline: True
Inline callers:
  - crypto/geniv.c:aead_init_geniv
```
```
In crypto/gcm.c (ffffffff81553fb3)
Location: include/crypto/aead.h:386
Inline: True
Inline callers:
  - crypto/gcm.c:crypto_rfc4543_init_tfm
  - crypto/gcm.c:crypto_rfc4543_crypt
  - crypto/gcm.c:crypto_rfc4106_init_tfm
  - crypto/gcm.c:crypto_rfc4106_crypt
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
In crypto/geniv.c (ffffffff815a80b5)
Location: include/crypto/aead.h:386
Inline: True
Inline callers:
  - crypto/geniv.c:aead_init_geniv
```
```
In crypto/gcm.c (ffffffff815b4fe3)
Location: include/crypto/aead.h:386
Inline: True
Inline callers:
  - crypto/gcm.c:crypto_rfc4543_init_tfm
  - crypto/gcm.c:crypto_rfc4543_crypt
  - crypto/gcm.c:crypto_rfc4106_init_tfm
  - crypto/gcm.c:crypto_rfc4106_crypt
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
In crypto/geniv.c (ffffffff8164f462)
Location: include/crypto/aead.h:388
Inline: True
Inline callers:
  - crypto/geniv.c:aead_init_geniv
```
```
In crypto/gcm.c (ffffffff8165e065)
Location: include/crypto/aead.h:388
Inline: True
Inline callers:
  - crypto/gcm.c:crypto_rfc4543_init_tfm
  - crypto/gcm.c:crypto_rfc4543_crypt
  - crypto/gcm.c:crypto_rfc4106_init_tfm
  - crypto/gcm.c:crypto_rfc4106_crypt
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
In crypto/geniv.c (ffffffff81708a62)
Location: include/crypto/aead.h:388
Inline: True
Inline callers:
  - crypto/geniv.c:aead_init_geniv
```
```
In crypto/gcm.c (ffffffff817179b5)
Location: include/crypto/aead.h:388
Inline: True
Inline callers:
  - crypto/gcm.c:crypto_rfc4543_init_tfm
  - crypto/gcm.c:crypto_rfc4543_crypt
  - crypto/gcm.c:crypto_rfc4106_init_tfm
  - crypto/gcm.c:crypto_rfc4106_crypt
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
In crypto/geniv.c (ffffffff8174222d)
Location: include/crypto/aead.h:410
Inline: True
Inline callers:
  - crypto/geniv.c:aead_init_geniv
```
```
In crypto/gcm.c (ffffffff81753395)
Location: include/crypto/aead.h:410
Inline: True
Inline callers:
  - crypto/gcm.c:crypto_rfc4543_init_tfm
  - crypto/gcm.c:crypto_rfc4543_crypt
  - crypto/gcm.c:crypto_rfc4106_init_tfm
  - crypto/gcm.c:crypto_rfc4106_crypt
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
In crypto/geniv.c (ffffffff8178310d)
Location: include/crypto/aead.h:422
Inline: True
Inline callers:
  - crypto/geniv.c:aead_init_geniv
```
```
In crypto/gcm.c (ffffffff81795265)
Location: include/crypto/aead.h:422
Inline: True
Inline callers:
  - crypto/gcm.c:crypto_rfc4543_init_tfm
  - crypto/gcm.c:crypto_rfc4543_crypt
  - crypto/gcm.c:crypto_rfc4106_init_tfm
  - crypto/gcm.c:crypto_rfc4106_crypt
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
In security/keys/big_key.c (ffff800010539964)
Location: include/crypto/aead.h:363
Inline: True
Inline callers:
  - security/keys/big_key.c:big_key_crypt
```
```
In crypto/aead.c (ffff8000105bc13c)
Location: include/crypto/aead.h:363
Inline: True
Inline callers:
  - crypto/aead.c:aead_init_geniv
```
```
In crypto/gcm.c (ffff8000105cb930)
Location: include/crypto/aead.h:363
Inline: True
Inline callers:
  - crypto/gcm.c:crypto_rfc4543_init_tfm
  - crypto/gcm.c:crypto_rfc4543_crypt
  - crypto/gcm.c:crypto_rfc4106_init_tfm
  - crypto/gcm.c:crypto_rfc4106_crypt
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
In security/keys/big_key.c (c06f012c)
Location: include/crypto/aead.h:363
Inline: True
Inline callers:
  - security/keys/big_key.c:big_key_crypt
```
```
In crypto/aead.c (c076a1a0)
Location: include/crypto/aead.h:363
Inline: True
Inline callers:
  - crypto/aead.c:aead_init_geniv
```
```
In crypto/gcm.c (c0779368)
Location: include/crypto/aead.h:363
Inline: True
Inline callers:
  - crypto/gcm.c:crypto_rfc4543_init_tfm
  - crypto/gcm.c:crypto_rfc4543_crypt
  - crypto/gcm.c:crypto_rfc4106_init_tfm
  - crypto/gcm.c:crypto_rfc4106_crypt
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
In security/keys/big_key.c (c000000000688914)
Location: include/crypto/aead.h:363
Inline: True
Inline callers:
  - security/keys/big_key.c:big_key_crypt
```
```
In crypto/aead.c (c000000000742ac0)
Location: include/crypto/aead.h:363
Inline: True
Inline callers:
  - crypto/aead.c:aead_init_geniv
```
```
In crypto/gcm.c (c000000000756a78)
Location: include/crypto/aead.h:363
Inline: True
Inline callers:
  - crypto/gcm.c:crypto_rfc4543_init_tfm
  - crypto/gcm.c:crypto_rfc4543_crypt
  - crypto/gcm.c:crypto_rfc4106_init_tfm
  - crypto/gcm.c:crypto_rfc4106_crypt
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
In security/keys/big_key.c (ffffffe000398016)
Location: include/crypto/aead.h:363
Inline: True
Inline callers:
  - security/keys/big_key.c:big_key_crypt
```
```
In crypto/aead.c (ffffffe0004018b6)
Location: include/crypto/aead.h:363
Inline: True
Inline callers:
  - crypto/aead.c:aead_init_geniv
```
```
In crypto/gcm.c (ffffffe00040fc7c)
Location: include/crypto/aead.h:363
Inline: True
Inline callers:
  - crypto/gcm.c:crypto_rfc4543_init_tfm
  - crypto/gcm.c:crypto_rfc4543_crypt
  - crypto/gcm.c:crypto_rfc4106_init_tfm
  - crypto/gcm.c:crypto_rfc4106_crypt
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
In security/keys/big_key.c (ffffffff81447550)
Location: include/crypto/aead.h:363
Inline: True
Inline callers:
  - security/keys/big_key.c:big_key_crypt
```
```
In crypto/aead.c (ffffffff814ba015)
Location: include/crypto/aead.h:363
Inline: True
Inline callers:
  - crypto/aead.c:aead_init_geniv
```
```
In crypto/gcm.c (ffffffff814c7e13)
Location: include/crypto/aead.h:363
Inline: True
Inline callers:
  - crypto/gcm.c:crypto_rfc4543_init_tfm
  - crypto/gcm.c:crypto_rfc4543_crypt
  - crypto/gcm.c:crypto_rfc4106_init_tfm
  - crypto/gcm.c:crypto_rfc4106_crypt
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
In security/keys/big_key.c (ffffffff81437fa0)
Location: include/crypto/aead.h:363
Inline: True
Inline callers:
  - security/keys/big_key.c:big_key_crypt
```
```
In crypto/aead.c (ffffffff814aaa35)
Location: include/crypto/aead.h:363
Inline: True
Inline callers:
  - crypto/aead.c:aead_init_geniv
```
```
In crypto/gcm.c (ffffffff814b8833)
Location: include/crypto/aead.h:363
Inline: True
Inline callers:
  - crypto/gcm.c:crypto_rfc4543_init_tfm
  - crypto/gcm.c:crypto_rfc4543_crypt
  - crypto/gcm.c:crypto_rfc4106_init_tfm
  - crypto/gcm.c:crypto_rfc4106_crypt
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
In security/keys/big_key.c (ffffffff814435f0)
Location: include/crypto/aead.h:363
Inline: True
Inline callers:
  - security/keys/big_key.c:big_key_crypt
```
```
In crypto/aead.c (ffffffff814b60a5)
Location: include/crypto/aead.h:363
Inline: True
Inline callers:
  - crypto/aead.c:aead_init_geniv
```
```
In crypto/gcm.c (ffffffff814c3ea3)
Location: include/crypto/aead.h:363
Inline: True
Inline callers:
  - crypto/gcm.c:crypto_rfc4543_init_tfm
  - crypto/gcm.c:crypto_rfc4543_crypt
  - crypto/gcm.c:crypto_rfc4106_init_tfm
  - crypto/gcm.c:crypto_rfc4106_crypt
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
In security/keys/big_key.c (ffffffff8145a920)
Location: include/crypto/aead.h:363
Inline: True
Inline callers:
  - security/keys/big_key.c:big_key_crypt
```
```
In crypto/aead.c (ffffffff814ceb45)
Location: include/crypto/aead.h:363
Inline: True
Inline callers:
  - crypto/aead.c:aead_init_geniv
```
```
In crypto/gcm.c (ffffffff814dc973)
Location: include/crypto/aead.h:363
Inline: True
Inline callers:
  - crypto/gcm.c:crypto_rfc4543_init_tfm
  - crypto/gcm.c:crypto_rfc4543_crypt
  - crypto/gcm.c:crypto_rfc4106_init_tfm
  - crypto/gcm.c:crypto_rfc4106_crypt
```
</details>
</li>
</ul>

## Differences
