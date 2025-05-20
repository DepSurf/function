# Function: <code>crypto_set_spawn</code>

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
Location: include/crypto/algapi.h:157
Inline: True
```
```
In crypto/blkcipher.c (ffffffff813a0df1)
Location: include/crypto/algapi.h:157
Inline: True
Inline callers:
  - crypto/blkcipher.c:skcipher_geniv_alloc
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
Location: include/crypto/algapi.h:227
Inline: True
```
```
In crypto/rsa-pkcs1pad.c (0)
Location: include/crypto/algapi.h:227
Inline: True
```
```
In crypto/cts.c (ffffffff813e7eb5)
Location: include/crypto/algapi.h:227
Inline: True
Inline callers:
  - crypto/cts.c:crypto_cts_create
```
```
In crypto/ctr.c (0)
Location: include/crypto/algapi.h:227
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
In crypto/aead.c (0)
Location: include/crypto/algapi.h:157
Inline: True
```
```
In crypto/rsa-pkcs1pad.c (0)
Location: include/crypto/algapi.h:157
Inline: True
```
```
In crypto/cts.c (ffffffff81400ce5)
Location: include/crypto/algapi.h:157
Inline: True
Inline callers:
  - crypto/cts.c:crypto_cts_create
```
```
In crypto/xts.c (ffffffff81401637)
Location: include/crypto/algapi.h:157
Inline: True
Inline callers:
  - crypto/xts.c:create
```
```
In crypto/ctr.c (0)
Location: include/crypto/algapi.h:157
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
In crypto/aead.c (0)
Location: include/crypto/algapi.h:157
Inline: True
```
```
In crypto/rsa-pkcs1pad.c (0)
Location: include/crypto/algapi.h:157
Inline: True
```
```
In crypto/cts.c (ffffffff8140dc8d)
Location: include/crypto/algapi.h:157
Inline: True
Inline callers:
  - crypto/cts.c:crypto_cts_create
```
```
In crypto/xts.c (ffffffff8140e9f2)
Location: include/crypto/algapi.h:157
Inline: True
Inline callers:
  - crypto/xts.c:create
```
```
In crypto/ctr.c (0)
Location: include/crypto/algapi.h:157
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
In crypto/aead.c (0)
Location: include/crypto/algapi.h:157
Inline: True
```
```
In crypto/rsa-pkcs1pad.c (0)
Location: include/crypto/algapi.h:157
Inline: True
```
```
In crypto/cts.c (ffffffff8143672d)
Location: include/crypto/algapi.h:157
Inline: True
Inline callers:
  - crypto/cts.c:crypto_cts_create
```
```
In crypto/xts.c (ffffffff814374c2)
Location: include/crypto/algapi.h:157
Inline: True
Inline callers:
  - crypto/xts.c:create
```
```
In crypto/ctr.c (0)
Location: include/crypto/algapi.h:157
Inline: True
```
```
In crypto/gcm.c (ffffffff814398fa)
Location: include/crypto/algapi.h:157
Inline: True
Inline callers:
  - crypto/gcm.c:crypto_gcm_create_common
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
In crypto/aead.c (ffffffff8145b3f5)
Location: include/crypto/algapi.h:164
Inline: True
Inline callers:
  - crypto/aead.c:aead_geniv_alloc
```
```
In crypto/rsa-pkcs1pad.c (ffffffff81461911)
Location: include/crypto/algapi.h:164
Inline: True
Inline callers:
  - crypto/rsa-pkcs1pad.c:pkcs1pad_create
```
```
In crypto/cts.c (ffffffff814692a7)
Location: include/crypto/algapi.h:164
Inline: True
Inline callers:
  - crypto/cts.c:crypto_cts_create
```
```
In crypto/xts.c (ffffffff81469dee)
Location: include/crypto/algapi.h:164
Inline: True
Inline callers:
  - crypto/xts.c:create
```
```
In crypto/ctr.c (ffffffff8146aa8e)
Location: include/crypto/algapi.h:164
Inline: True
Inline callers:
  - crypto/ctr.c:crypto_rfc3686_create
```
```
In crypto/gcm.c (ffffffff8146be26)
Location: include/crypto/algapi.h:164
Inline: True
Inline callers:
  - crypto/gcm.c:crypto_rfc4543_create
  - crypto/gcm.c:crypto_rfc4106_create
  - crypto/gcm.c:crypto_gcm_create_common
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
In crypto/aead.c (ffffffff81478f94)
Location: include/crypto/algapi.h:166
Inline: True
Inline callers:
  - crypto/aead.c:aead_geniv_alloc
```
```
In crypto/rsa-pkcs1pad.c (ffffffff8147f71b)
Location: include/crypto/algapi.h:166
Inline: True
Inline callers:
  - crypto/rsa-pkcs1pad.c:pkcs1pad_create
```
```
In crypto/cts.c (ffffffff81486c72)
Location: include/crypto/algapi.h:166
Inline: True
Inline callers:
  - crypto/cts.c:crypto_cts_create
```
```
In crypto/xts.c (ffffffff81487ade)
Location: include/crypto/algapi.h:166
Inline: True
Inline callers:
  - crypto/xts.c:create
```
```
In crypto/ctr.c (ffffffff8148830f)
Location: include/crypto/algapi.h:166
Inline: True
Inline callers:
  - crypto/ctr.c:crypto_rfc3686_create
```
```
In crypto/gcm.c (ffffffff814898c6)
Location: include/crypto/algapi.h:166
Inline: True
Inline callers:
  - crypto/gcm.c:crypto_rfc4543_create
  - crypto/gcm.c:crypto_rfc4106_create
  - crypto/gcm.c:crypto_gcm_create_common
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
In crypto/aead.c (ffffffff814a6eca)
Location: include/crypto/algapi.h:163
Inline: True
Inline callers:
  - crypto/aead.c:aead_geniv_alloc
```
```
In crypto/rsa-pkcs1pad.c (ffffffff814ad6f2)
Location: include/crypto/algapi.h:163
Inline: True
Inline callers:
  - crypto/rsa-pkcs1pad.c:pkcs1pad_create
```
```
In crypto/cts.c (ffffffff814b4d88)
Location: include/crypto/algapi.h:163
Inline: True
Inline callers:
  - crypto/cts.c:crypto_cts_create
```
```
In crypto/xts.c (ffffffff814b57e7)
Location: include/crypto/algapi.h:163
Inline: True
Inline callers:
  - crypto/xts.c:create
```
```
In crypto/ctr.c (ffffffff814b5d58)
Location: include/crypto/algapi.h:163
Inline: True
Inline callers:
  - crypto/ctr.c:crypto_rfc3686_create
```
```
In crypto/gcm.c (ffffffff814b71bb)
Location: include/crypto/algapi.h:163
Inline: True
Inline callers:
  - crypto/gcm.c:crypto_rfc4543_create
  - crypto/gcm.c:crypto_rfc4106_create
  - crypto/gcm.c:crypto_gcm_create_common
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
In crypto/aead.c (ffffffff814c1b3a)
Location: include/crypto/algapi.h:163
Inline: True
Inline callers:
  - crypto/aead.c:aead_geniv_alloc
```
```
In crypto/rsa-pkcs1pad.c (ffffffff814c83a2)
Location: include/crypto/algapi.h:163
Inline: True
Inline callers:
  - crypto/rsa-pkcs1pad.c:pkcs1pad_create
```
```
In crypto/cts.c (ffffffff814cd858)
Location: include/crypto/algapi.h:163
Inline: True
Inline callers:
  - crypto/cts.c:crypto_cts_create
```
```
In crypto/xts.c (ffffffff814ce9e7)
Location: include/crypto/algapi.h:163
Inline: True
Inline callers:
  - crypto/xts.c:create
```
```
In crypto/ctr.c (ffffffff814cef58)
Location: include/crypto/algapi.h:163
Inline: True
Inline callers:
  - crypto/ctr.c:crypto_rfc3686_create
```
```
In crypto/gcm.c (ffffffff814d03db)
Location: include/crypto/algapi.h:163
Inline: True
Inline callers:
  - crypto/gcm.c:crypto_rfc4543_create
  - crypto/gcm.c:crypto_rfc4106_create
  - crypto/gcm.c:crypto_gcm_create_common
```
</details>
</li>
<li>
In <code>5.8</code>: Absent ⚠️
</li>
<li>
In <code>5.11</code>: Absent ⚠️
</li>
<li>
In <code>5.13</code>: Absent ⚠️
</li>
<li>
In <code>5.15</code>: Absent ⚠️
</li>
<li>
In <code>5.19</code>: Absent ⚠️
</li>
<li>
In <code>6.2</code>: Absent ⚠️
</li>
<li>
In <code>6.5</code>: Absent ⚠️
</li>
<li>
In <code>6.8</code>: Absent ⚠️
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
In crypto/aead.c (ffff8000105bb92c)
Location: include/crypto/algapi.h:163
Inline: True
Inline callers:
  - crypto/aead.c:aead_geniv_alloc
```
```
In crypto/rsa-pkcs1pad.c (ffff8000105c3bb0)
Location: include/crypto/algapi.h:163
Inline: True
Inline callers:
  - crypto/rsa-pkcs1pad.c:pkcs1pad_create
```
```
In crypto/cts.c (ffff8000105c9734)
Location: include/crypto/algapi.h:163
Inline: True
Inline callers:
  - crypto/cts.c:crypto_cts_create
```
```
In crypto/xts.c (ffff8000105ca654)
Location: include/crypto/algapi.h:163
Inline: True
Inline callers:
  - crypto/xts.c:create
```
```
In crypto/ctr.c (ffff8000105cadc0)
Location: include/crypto/algapi.h:163
Inline: True
Inline callers:
  - crypto/ctr.c:crypto_rfc3686_create
```
```
In crypto/gcm.c (ffff8000105cbb48)
Location: include/crypto/algapi.h:163
Inline: True
Inline callers:
  - crypto/gcm.c:crypto_rfc4543_create
  - crypto/gcm.c:crypto_rfc4106_create
  - crypto/gcm.c:crypto_gcm_create_common
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
In crypto/aead.c (c0769b04)
Location: include/crypto/algapi.h:163
Inline: True
Inline callers:
  - crypto/aead.c:aead_geniv_alloc
```
```
In crypto/rsa-pkcs1pad.c (c0770dd4)
Location: include/crypto/algapi.h:163
Inline: True
Inline callers:
  - crypto/rsa-pkcs1pad.c:pkcs1pad_create
```
```
In crypto/cts.c (c07772c4)
Location: include/crypto/algapi.h:163
Inline: True
Inline callers:
  - crypto/cts.c:crypto_cts_create
```
```
In crypto/xts.c (c0778264)
Location: include/crypto/algapi.h:163
Inline: True
Inline callers:
  - crypto/xts.c:create
```
```
In crypto/ctr.c (c0778980)
Location: include/crypto/algapi.h:163
Inline: True
Inline callers:
  - crypto/ctr.c:crypto_rfc3686_create
```
```
In crypto/gcm.c (c0779530)
Location: include/crypto/algapi.h:163
Inline: True
Inline callers:
  - crypto/gcm.c:crypto_rfc4543_create
  - crypto/gcm.c:crypto_rfc4106_create
  - crypto/gcm.c:crypto_gcm_create_common
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
In crypto/aead.c (c000000000742c4c)
Location: include/crypto/algapi.h:163
Inline: True
Inline callers:
  - crypto/aead.c:aead_geniv_alloc
```
```
In crypto/rsa-pkcs1pad.c (c00000000074cef4)
Location: include/crypto/algapi.h:163
Inline: True
Inline callers:
  - crypto/rsa-pkcs1pad.c:pkcs1pad_create
```
```
In crypto/cts.c (c000000000753e34)
Location: include/crypto/algapi.h:163
Inline: True
Inline callers:
  - crypto/cts.c:crypto_cts_create
```
```
In crypto/xts.c (c0000000007555e0)
Location: include/crypto/algapi.h:163
Inline: True
Inline callers:
  - crypto/xts.c:create
```
```
In crypto/ctr.c (c000000000755dc8)
Location: include/crypto/algapi.h:163
Inline: True
Inline callers:
  - crypto/ctr.c:crypto_rfc3686_create
```
```
In crypto/gcm.c (c0000000007587c0)
Location: include/crypto/algapi.h:163
Inline: True
Inline callers:
  - crypto/gcm.c:crypto_rfc4543_create
  - crypto/gcm.c:crypto_rfc4106_create
  - crypto/gcm.c:crypto_gcm_create_common
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
In crypto/aead.c (ffffffe000401968)
Location: include/crypto/algapi.h:163
Inline: True
Inline callers:
  - crypto/aead.c:aead_geniv_alloc
```
```
In crypto/rsa-pkcs1pad.c (ffffffe00040880e)
Location: include/crypto/algapi.h:163
Inline: True
Inline callers:
  - crypto/rsa-pkcs1pad.c:pkcs1pad_create
```
```
In crypto/cts.c (ffffffe00040e414)
Location: include/crypto/algapi.h:163
Inline: True
Inline callers:
  - crypto/cts.c:crypto_cts_create
```
```
In crypto/xts.c (ffffffe00040edcc)
Location: include/crypto/algapi.h:163
Inline: True
Inline callers:
  - crypto/xts.c:create
```
```
In crypto/ctr.c (ffffffe00040f4f8)
Location: include/crypto/algapi.h:163
Inline: True
Inline callers:
  - crypto/ctr.c:crypto_rfc3686_create
```
```
In crypto/gcm.c (ffffffe0004110fa)
Location: include/crypto/algapi.h:163
Inline: True
Inline callers:
  - crypto/gcm.c:crypto_rfc4543_create
  - crypto/gcm.c:crypto_rfc4106_create
  - crypto/gcm.c:crypto_gcm_create_common
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
In crypto/aead.c (ffffffff814ba11a)
Location: include/crypto/algapi.h:163
Inline: True
Inline callers:
  - crypto/aead.c:aead_geniv_alloc
```
```
In crypto/rsa-pkcs1pad.c (ffffffff814c0982)
Location: include/crypto/algapi.h:163
Inline: True
Inline callers:
  - crypto/rsa-pkcs1pad.c:pkcs1pad_create
```
```
In crypto/cts.c (ffffffff814c5e38)
Location: include/crypto/algapi.h:163
Inline: True
Inline callers:
  - crypto/cts.c:crypto_cts_create
```
```
In crypto/xts.c (ffffffff814c6fc7)
Location: include/crypto/algapi.h:163
Inline: True
Inline callers:
  - crypto/xts.c:create
```
```
In crypto/ctr.c (ffffffff814c7538)
Location: include/crypto/algapi.h:163
Inline: True
Inline callers:
  - crypto/ctr.c:crypto_rfc3686_create
```
```
In crypto/gcm.c (ffffffff814c89bb)
Location: include/crypto/algapi.h:163
Inline: True
Inline callers:
  - crypto/gcm.c:crypto_rfc4543_create
  - crypto/gcm.c:crypto_rfc4106_create
  - crypto/gcm.c:crypto_gcm_create_common
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
In crypto/aead.c (ffffffff814aab3a)
Location: include/crypto/algapi.h:163
Inline: True
Inline callers:
  - crypto/aead.c:aead_geniv_alloc
```
```
In crypto/rsa-pkcs1pad.c (ffffffff814b13a2)
Location: include/crypto/algapi.h:163
Inline: True
Inline callers:
  - crypto/rsa-pkcs1pad.c:pkcs1pad_create
```
```
In crypto/cts.c (ffffffff814b6858)
Location: include/crypto/algapi.h:163
Inline: True
Inline callers:
  - crypto/cts.c:crypto_cts_create
```
```
In crypto/xts.c (ffffffff814b79e7)
Location: include/crypto/algapi.h:163
Inline: True
Inline callers:
  - crypto/xts.c:create
```
```
In crypto/ctr.c (ffffffff814b7f58)
Location: include/crypto/algapi.h:163
Inline: True
Inline callers:
  - crypto/ctr.c:crypto_rfc3686_create
```
```
In crypto/gcm.c (ffffffff814b93db)
Location: include/crypto/algapi.h:163
Inline: True
Inline callers:
  - crypto/gcm.c:crypto_rfc4543_create
  - crypto/gcm.c:crypto_rfc4106_create
  - crypto/gcm.c:crypto_gcm_create_common
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
In crypto/aead.c (ffffffff814b61aa)
Location: include/crypto/algapi.h:163
Inline: True
Inline callers:
  - crypto/aead.c:aead_geniv_alloc
```
```
In crypto/rsa-pkcs1pad.c (ffffffff814bca12)
Location: include/crypto/algapi.h:163
Inline: True
Inline callers:
  - crypto/rsa-pkcs1pad.c:pkcs1pad_create
```
```
In crypto/cts.c (ffffffff814c1ec8)
Location: include/crypto/algapi.h:163
Inline: True
Inline callers:
  - crypto/cts.c:crypto_cts_create
```
```
In crypto/xts.c (ffffffff814c3057)
Location: include/crypto/algapi.h:163
Inline: True
Inline callers:
  - crypto/xts.c:create
```
```
In crypto/ctr.c (ffffffff814c35c8)
Location: include/crypto/algapi.h:163
Inline: True
Inline callers:
  - crypto/ctr.c:crypto_rfc3686_create
```
```
In crypto/gcm.c (ffffffff814c4a4b)
Location: include/crypto/algapi.h:163
Inline: True
Inline callers:
  - crypto/gcm.c:crypto_rfc4543_create
  - crypto/gcm.c:crypto_rfc4106_create
  - crypto/gcm.c:crypto_gcm_create_common
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
In crypto/aead.c (ffffffff814cec4a)
Location: include/crypto/algapi.h:163
Inline: True
Inline callers:
  - crypto/aead.c:aead_geniv_alloc
```
```
In crypto/rsa-pkcs1pad.c (ffffffff814d54e2)
Location: include/crypto/algapi.h:163
Inline: True
Inline callers:
  - crypto/rsa-pkcs1pad.c:pkcs1pad_create
```
```
In crypto/cts.c (ffffffff814da998)
Location: include/crypto/algapi.h:163
Inline: True
Inline callers:
  - crypto/cts.c:crypto_cts_create
```
```
In crypto/xts.c (ffffffff814dbb27)
Location: include/crypto/algapi.h:163
Inline: True
Inline callers:
  - crypto/xts.c:create
```
```
In crypto/ctr.c (ffffffff814dc098)
Location: include/crypto/algapi.h:163
Inline: True
Inline callers:
  - crypto/ctr.c:crypto_rfc3686_create
```
```
In crypto/gcm.c (ffffffff814dd51b)
Location: include/crypto/algapi.h:163
Inline: True
Inline callers:
  - crypto/gcm.c:crypto_rfc4543_create
  - crypto/gcm.c:crypto_rfc4106_create
  - crypto/gcm.c:crypto_gcm_create_common
```
</details>
</li>
</ul>

## Differences
