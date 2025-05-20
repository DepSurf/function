# Function: <code>crypto_requires_off</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4</code>: Absent ⚠️
</li>
<li>
In <code>4.8</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>4.10</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In crypto/aead.c (ffffffff813f3c4f)
Location: include/crypto/algapi.h:347
Inline: True
Inline callers:
  - crypto/aead.c:aead_geniv_alloc
```
```
In crypto/rsa-pkcs1pad.c (ffffffff813f9b06)
Location: include/crypto/algapi.h:347
Inline: True
Inline callers:
  - crypto/rsa-pkcs1pad.c:pkcs1pad_create
```
```
In crypto/cts.c (ffffffff81400cec)
Location: include/crypto/algapi.h:347
Inline: True
Inline callers:
  - crypto/cts.c:crypto_cts_create
```
```
In crypto/xts.c (ffffffff8140163e)
Location: include/crypto/algapi.h:347
Inline: True
Inline callers:
  - crypto/xts.c:create
```
```
In crypto/ctr.c (ffffffff814024d7)
Location: include/crypto/algapi.h:347
Inline: True
Inline callers:
  - crypto/ctr.c:crypto_rfc3686_create
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
In crypto/aead.c (ffffffff813fffb3)
Location: include/crypto/algapi.h:363
Inline: True
Inline callers:
  - crypto/aead.c:aead_geniv_alloc
```
```
In crypto/rsa-pkcs1pad.c (ffffffff8140635f)
Location: include/crypto/algapi.h:363
Inline: True
Inline callers:
  - crypto/rsa-pkcs1pad.c:pkcs1pad_create
```
```
In crypto/cbc.c (ffffffff8140d38e)
Location: include/crypto/algapi.h:363
Inline: True
```
```
In crypto/cts.c (ffffffff8140dc94)
Location: include/crypto/algapi.h:363
Inline: True
Inline callers:
  - crypto/cts.c:crypto_cts_create
```
```
In crypto/xts.c (ffffffff8140e9f9)
Location: include/crypto/algapi.h:363
Inline: True
Inline callers:
  - crypto/xts.c:create
```
```
In crypto/ctr.c (ffffffff8140f5fe)
Location: include/crypto/algapi.h:363
Inline: True
Inline callers:
  - crypto/ctr.c:crypto_rfc3686_create
  - crypto/ctr.c:crypto_rfc3686_create
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
In crypto/aead.c (ffffffff814285a3)
Location: include/crypto/algapi.h:382
Inline: True
Inline callers:
  - crypto/aead.c:aead_geniv_alloc
```
```
In crypto/rsa-pkcs1pad.c (ffffffff8142ec9f)
Location: include/crypto/algapi.h:382
Inline: True
Inline callers:
  - crypto/rsa-pkcs1pad.c:pkcs1pad_create
```
```
In crypto/cbc.c (ffffffff81435dfe)
Location: include/crypto/algapi.h:382
Inline: True
```
```
In crypto/cts.c (ffffffff81436734)
Location: include/crypto/algapi.h:382
Inline: True
Inline callers:
  - crypto/cts.c:crypto_cts_create
```
```
In crypto/xts.c (ffffffff814374c9)
Location: include/crypto/algapi.h:382
Inline: True
Inline callers:
  - crypto/xts.c:create
```
```
In crypto/ctr.c (ffffffff814380fe)
Location: include/crypto/algapi.h:382
Inline: True
Inline callers:
  - crypto/ctr.c:crypto_rfc3686_create
  - crypto/ctr.c:crypto_rfc3686_create
```
```
In crypto/gcm.c (ffffffff81439680)
Location: include/crypto/algapi.h:382
Inline: True
Inline callers:
  - crypto/gcm.c:crypto_rfc4543_create
  - crypto/gcm.c:crypto_rfc4106_create
  - crypto/gcm.c:crypto_gcm_create_common
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
In crypto/aead.c (ffffffff8145b3c4)
Location: include/crypto/algapi.h:389
Inline: True
Inline callers:
  - crypto/aead.c:aead_geniv_alloc
```
```
In crypto/rsa-pkcs1pad.c (ffffffff81461911)
Location: include/crypto/algapi.h:389
Inline: True
Inline callers:
  - crypto/rsa-pkcs1pad.c:pkcs1pad_create
```
```
In crypto/cbc.c (ffffffff81468994)
Location: include/crypto/algapi.h:389
Inline: True
```
```
In crypto/cts.c (ffffffff814692b0)
Location: include/crypto/algapi.h:389
Inline: True
Inline callers:
  - crypto/cts.c:crypto_cts_create
```
```
In crypto/xts.c (ffffffff81469dee)
Location: include/crypto/algapi.h:389
Inline: True
Inline callers:
  - crypto/xts.c:create
```
```
In crypto/ctr.c (ffffffff8146aa80)
Location: include/crypto/algapi.h:389
Inline: True
Inline callers:
  - crypto/ctr.c:crypto_rfc3686_create
  - crypto/ctr.c:crypto_rfc3686_create
```
```
In crypto/gcm.c (ffffffff8146be36)
Location: include/crypto/algapi.h:389
Inline: True
Inline callers:
  - crypto/gcm.c:crypto_rfc4543_create
  - crypto/gcm.c:crypto_rfc4106_create
  - crypto/gcm.c:crypto_gcm_create_common
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
In crypto/aead.c (ffffffff81478f63)
Location: include/crypto/algapi.h:391
Inline: True
Inline callers:
  - crypto/aead.c:aead_geniv_alloc
```
```
In crypto/rsa-pkcs1pad.c (ffffffff8147f71b)
Location: include/crypto/algapi.h:391
Inline: True
Inline callers:
  - crypto/rsa-pkcs1pad.c:pkcs1pad_create
```
```
In crypto/cbc.c (ffffffff8148661b)
Location: include/crypto/algapi.h:391
Inline: True
```
```
In crypto/cts.c (ffffffff81486c87)
Location: include/crypto/algapi.h:391
Inline: True
Inline callers:
  - crypto/cts.c:crypto_cts_create
```
```
In crypto/xts.c (ffffffff81487ade)
Location: include/crypto/algapi.h:391
Inline: True
Inline callers:
  - crypto/xts.c:create
```
```
In crypto/ctr.c (ffffffff81488301)
Location: include/crypto/algapi.h:391
Inline: True
Inline callers:
  - crypto/ctr.c:crypto_rfc3686_create
  - crypto/ctr.c:crypto_rfc3686_create
```
```
In crypto/gcm.c (ffffffff814898d6)
Location: include/crypto/algapi.h:391
Inline: True
Inline callers:
  - crypto/gcm.c:crypto_rfc4543_create
  - crypto/gcm.c:crypto_rfc4106_create
  - crypto/gcm.c:crypto_gcm_create_common
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
In crypto/aead.c (ffffffff814a6e95)
Location: include/crypto/algapi.h:379
Inline: True
Inline callers:
  - crypto/aead.c:aead_geniv_alloc
```
```
In crypto/skcipher.c (ffffffff814a92b3)
Location: include/crypto/algapi.h:379
Inline: True
Inline callers:
  - crypto/skcipher.c:skcipher_alloc_instance_simple
```
```
In crypto/rsa-pkcs1pad.c (ffffffff814ad6f2)
Location: include/crypto/algapi.h:379
Inline: True
Inline callers:
  - crypto/rsa-pkcs1pad.c:pkcs1pad_create
```
```
In crypto/cts.c (ffffffff814b4d94)
Location: include/crypto/algapi.h:379
Inline: True
Inline callers:
  - crypto/cts.c:crypto_cts_create
```
```
In crypto/xts.c (ffffffff814b57e7)
Location: include/crypto/algapi.h:379
Inline: True
Inline callers:
  - crypto/xts.c:create
```
```
In crypto/ctr.c (ffffffff814b5d4a)
Location: include/crypto/algapi.h:379
Inline: True
Inline callers:
  - crypto/ctr.c:crypto_rfc3686_create
  - crypto/ctr.c:crypto_rfc3686_create
```
```
In crypto/gcm.c (ffffffff814b71cb)
Location: include/crypto/algapi.h:379
Inline: True
Inline callers:
  - crypto/gcm.c:crypto_rfc4543_create
  - crypto/gcm.c:crypto_rfc4106_create
  - crypto/gcm.c:crypto_gcm_create_common
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
In crypto/aead.c (ffffffff814c1b05)
Location: include/crypto/algapi.h:379
Inline: True
Inline callers:
  - crypto/aead.c:aead_geniv_alloc
```
```
In crypto/skcipher.c (ffffffff814c3f23)
Location: include/crypto/algapi.h:379
Inline: True
Inline callers:
  - crypto/skcipher.c:skcipher_alloc_instance_simple
```
```
In crypto/rsa-pkcs1pad.c (ffffffff814c83a2)
Location: include/crypto/algapi.h:379
Inline: True
Inline callers:
  - crypto/rsa-pkcs1pad.c:pkcs1pad_create
```
```
In crypto/cts.c (ffffffff814cd864)
Location: include/crypto/algapi.h:379
Inline: True
Inline callers:
  - crypto/cts.c:crypto_cts_create
```
```
In crypto/xts.c (ffffffff814ce9e7)
Location: include/crypto/algapi.h:379
Inline: True
Inline callers:
  - crypto/xts.c:create
```
```
In crypto/ctr.c (ffffffff814cef4a)
Location: include/crypto/algapi.h:379
Inline: True
Inline callers:
  - crypto/ctr.c:crypto_rfc3686_create
  - crypto/ctr.c:crypto_rfc3686_create
```
```
In crypto/gcm.c (ffffffff814d03eb)
Location: include/crypto/algapi.h:379
Inline: True
Inline callers:
  - crypto/gcm.c:crypto_rfc4543_create
  - crypto/gcm.c:crypto_rfc4106_create
  - crypto/gcm.c:crypto_gcm_create_common
  - crypto/gcm.c:crypto_gcm_create_common
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
In crypto/geniv.c (ffffffff8152242d)
Location: include/crypto/algapi.h:238
Inline: True
Inline callers:
  - crypto/geniv.c:aead_geniv_alloc
```
```
In crypto/skcipher.c (ffffffff81522ffb)
Location: include/crypto/algapi.h:238
Inline: True
Inline callers:
  - crypto/skcipher.c:skcipher_alloc_instance_simple
```
```
In crypto/rsa-pkcs1pad.c (ffffffff815278c2)
Location: include/crypto/algapi.h:238
Inline: True
Inline callers:
  - crypto/rsa-pkcs1pad.c:pkcs1pad_create
```
```
In crypto/cts.c (ffffffff8152cc33)
Location: include/crypto/algapi.h:238
Inline: True
Inline callers:
  - crypto/cts.c:crypto_cts_create
```
```
In crypto/xts.c (ffffffff8152dca0)
Location: include/crypto/algapi.h:238
Inline: True
Inline callers:
  - crypto/xts.c:create
```
```
In crypto/ctr.c (ffffffff8152e239)
Location: include/crypto/algapi.h:238
Inline: True
Inline callers:
  - crypto/ctr.c:crypto_rfc3686_create
  - crypto/ctr.c:crypto_rfc3686_create
```
```
In crypto/gcm.c (ffffffff8152f66e)
Location: include/crypto/algapi.h:238
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
<summary>In <code>5.11</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In crypto/algapi.c (ffffffff8153d106)
Location: include/crypto/algapi.h:238
Inline: True
Inline callers:
  - crypto/algapi.c:crypto_check_attr_type
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
In crypto/algapi.c (ffffffff815457e3)
Location: include/crypto/algapi.h:199
Inline: True
Inline callers:
  - crypto/algapi.c:crypto_check_attr_type
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
In crypto/algapi.c (ffffffff815a5fb3)
Location: include/crypto/algapi.h:207
Inline: True
Inline callers:
  - crypto/algapi.c:crypto_check_attr_type
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
In crypto/algapi.c (ffffffff8164d332)
Location: include/crypto/algapi.h:216
Inline: True
Inline callers:
  - crypto/algapi.c:crypto_check_attr_type
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
In crypto/algapi.c (ffffffff81706382)
Location: include/crypto/algapi.h:253
Inline: True
Inline callers:
  - crypto/algapi.c:crypto_check_attr_type
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
In crypto/algapi.c (ffffffff81741152)
Location: include/crypto/algapi.h:236
Inline: True
Inline callers:
  - crypto/algapi.c:crypto_check_attr_type
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In crypto/algapi.c (ffffffff81781ff2)
Location: include/crypto/algapi.h:231
Inline: True
Inline callers:
  - crypto/algapi.c:crypto_check_attr_type
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
In crypto/aead.c (ffff8000105bb92c)
Location: include/crypto/algapi.h:379
Inline: True
Inline callers:
  - crypto/aead.c:aead_geniv_alloc
```
```
In crypto/skcipher.c (ffff8000105bea3c)
Location: include/crypto/algapi.h:379
Inline: True
Inline callers:
  - crypto/skcipher.c:skcipher_alloc_instance_simple
```
```
In crypto/rsa-pkcs1pad.c (ffff8000105c3bb8)
Location: include/crypto/algapi.h:379
Inline: True
Inline callers:
  - crypto/rsa-pkcs1pad.c:pkcs1pad_create
```
```
In crypto/cts.c (ffff8000105c9734)
Location: include/crypto/algapi.h:379
Inline: True
Inline callers:
  - crypto/cts.c:crypto_cts_create
```
```
In crypto/xts.c (ffff8000105ca65c)
Location: include/crypto/algapi.h:379
Inline: True
Inline callers:
  - crypto/xts.c:create
```
```
In crypto/ctr.c (ffff8000105cadc0)
Location: include/crypto/algapi.h:379
Inline: True
Inline callers:
  - crypto/ctr.c:crypto_rfc3686_create
  - crypto/ctr.c:crypto_rfc3686_create
```
```
In crypto/gcm.c (ffff8000105cbb48)
Location: include/crypto/algapi.h:379
Inline: True
Inline callers:
  - crypto/gcm.c:crypto_rfc4543_create
  - crypto/gcm.c:crypto_rfc4106_create
  - crypto/gcm.c:crypto_gcm_create_common
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
Location: include/crypto/algapi.h:379
Inline: True
Inline callers:
  - crypto/aead.c:aead_geniv_alloc
```
```
In crypto/skcipher.c (c076c680)
Location: include/crypto/algapi.h:379
Inline: True
Inline callers:
  - crypto/skcipher.c:skcipher_alloc_instance_simple
```
```
In crypto/rsa-pkcs1pad.c (c0770dd4)
Location: include/crypto/algapi.h:379
Inline: True
Inline callers:
  - crypto/rsa-pkcs1pad.c:pkcs1pad_create
```
```
In crypto/cts.c (c07772c4)
Location: include/crypto/algapi.h:379
Inline: True
Inline callers:
  - crypto/cts.c:crypto_cts_create
```
```
In crypto/xts.c (c0778268)
Location: include/crypto/algapi.h:379
Inline: True
Inline callers:
  - crypto/xts.c:create
```
```
In crypto/ctr.c (c0778980)
Location: include/crypto/algapi.h:379
Inline: True
Inline callers:
  - crypto/ctr.c:crypto_rfc3686_create
  - crypto/ctr.c:crypto_rfc3686_create
```
```
In crypto/gcm.c (c0779530)
Location: include/crypto/algapi.h:379
Inline: True
Inline callers:
  - crypto/gcm.c:crypto_rfc4543_create
  - crypto/gcm.c:crypto_rfc4106_create
  - crypto/gcm.c:crypto_gcm_create_common
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
Location: include/crypto/algapi.h:379
Inline: True
Inline callers:
  - crypto/aead.c:aead_geniv_alloc
```
```
In crypto/skcipher.c (c000000000746d80)
Location: include/crypto/algapi.h:379
Inline: True
Inline callers:
  - crypto/skcipher.c:skcipher_alloc_instance_simple
```
```
In crypto/rsa-pkcs1pad.c (c00000000074cf00)
Location: include/crypto/algapi.h:379
Inline: True
Inline callers:
  - crypto/rsa-pkcs1pad.c:pkcs1pad_create
```
```
In crypto/cts.c (c000000000753e40)
Location: include/crypto/algapi.h:379
Inline: True
Inline callers:
  - crypto/cts.c:crypto_cts_create
```
```
In crypto/xts.c (c0000000007555f4)
Location: include/crypto/algapi.h:379
Inline: True
Inline callers:
  - crypto/xts.c:create
```
```
In crypto/ctr.c (c000000000755dc8)
Location: include/crypto/algapi.h:379
Inline: True
Inline callers:
  - crypto/ctr.c:crypto_rfc3686_create
  - crypto/ctr.c:crypto_rfc3686_create
```
```
In crypto/gcm.c (c0000000007587cc)
Location: include/crypto/algapi.h:379
Inline: True
Inline callers:
  - crypto/gcm.c:crypto_rfc4543_create
  - crypto/gcm.c:crypto_rfc4106_create
  - crypto/gcm.c:crypto_gcm_create_common
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
Location: include/crypto/algapi.h:379
Inline: True
Inline callers:
  - crypto/aead.c:aead_geniv_alloc
```
```
In crypto/skcipher.c (ffffffe000403ebe)
Location: include/crypto/algapi.h:379
Inline: True
Inline callers:
  - crypto/skcipher.c:skcipher_alloc_instance_simple
```
```
In crypto/rsa-pkcs1pad.c (ffffffe000408812)
Location: include/crypto/algapi.h:379
Inline: True
Inline callers:
  - crypto/rsa-pkcs1pad.c:pkcs1pad_create
```
```
In crypto/cts.c (ffffffe00040e418)
Location: include/crypto/algapi.h:379
Inline: True
Inline callers:
  - crypto/cts.c:crypto_cts_create
```
```
In crypto/xts.c (ffffffe00040edd0)
Location: include/crypto/algapi.h:379
Inline: True
Inline callers:
  - crypto/xts.c:create
```
```
In crypto/ctr.c (ffffffe00040f4f4)
Location: include/crypto/algapi.h:379
Inline: True
Inline callers:
  - crypto/ctr.c:crypto_rfc3686_create
  - crypto/ctr.c:crypto_rfc3686_create
```
```
In crypto/gcm.c (ffffffe0004110fe)
Location: include/crypto/algapi.h:379
Inline: True
Inline callers:
  - crypto/gcm.c:crypto_rfc4543_create
  - crypto/gcm.c:crypto_rfc4106_create
  - crypto/gcm.c:crypto_gcm_create_common
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
In crypto/aead.c (ffffffff814ba0e5)
Location: include/crypto/algapi.h:379
Inline: True
Inline callers:
  - crypto/aead.c:aead_geniv_alloc
```
```
In crypto/skcipher.c (ffffffff814bc503)
Location: include/crypto/algapi.h:379
Inline: True
Inline callers:
  - crypto/skcipher.c:skcipher_alloc_instance_simple
```
```
In crypto/rsa-pkcs1pad.c (ffffffff814c0982)
Location: include/crypto/algapi.h:379
Inline: True
Inline callers:
  - crypto/rsa-pkcs1pad.c:pkcs1pad_create
```
```
In crypto/cts.c (ffffffff814c5e44)
Location: include/crypto/algapi.h:379
Inline: True
Inline callers:
  - crypto/cts.c:crypto_cts_create
```
```
In crypto/xts.c (ffffffff814c6fc7)
Location: include/crypto/algapi.h:379
Inline: True
Inline callers:
  - crypto/xts.c:create
```
```
In crypto/ctr.c (ffffffff814c752a)
Location: include/crypto/algapi.h:379
Inline: True
Inline callers:
  - crypto/ctr.c:crypto_rfc3686_create
  - crypto/ctr.c:crypto_rfc3686_create
```
```
In crypto/gcm.c (ffffffff814c89cb)
Location: include/crypto/algapi.h:379
Inline: True
Inline callers:
  - crypto/gcm.c:crypto_rfc4543_create
  - crypto/gcm.c:crypto_rfc4106_create
  - crypto/gcm.c:crypto_gcm_create_common
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
In crypto/aead.c (ffffffff814aab05)
Location: include/crypto/algapi.h:379
Inline: True
Inline callers:
  - crypto/aead.c:aead_geniv_alloc
```
```
In crypto/skcipher.c (ffffffff814acf23)
Location: include/crypto/algapi.h:379
Inline: True
Inline callers:
  - crypto/skcipher.c:skcipher_alloc_instance_simple
```
```
In crypto/rsa-pkcs1pad.c (ffffffff814b13a2)
Location: include/crypto/algapi.h:379
Inline: True
Inline callers:
  - crypto/rsa-pkcs1pad.c:pkcs1pad_create
```
```
In crypto/cts.c (ffffffff814b6864)
Location: include/crypto/algapi.h:379
Inline: True
Inline callers:
  - crypto/cts.c:crypto_cts_create
```
```
In crypto/xts.c (ffffffff814b79e7)
Location: include/crypto/algapi.h:379
Inline: True
Inline callers:
  - crypto/xts.c:create
```
```
In crypto/ctr.c (ffffffff814b7f4a)
Location: include/crypto/algapi.h:379
Inline: True
Inline callers:
  - crypto/ctr.c:crypto_rfc3686_create
  - crypto/ctr.c:crypto_rfc3686_create
```
```
In crypto/gcm.c (ffffffff814b93eb)
Location: include/crypto/algapi.h:379
Inline: True
Inline callers:
  - crypto/gcm.c:crypto_rfc4543_create
  - crypto/gcm.c:crypto_rfc4106_create
  - crypto/gcm.c:crypto_gcm_create_common
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
In crypto/aead.c (ffffffff814b6175)
Location: include/crypto/algapi.h:379
Inline: True
Inline callers:
  - crypto/aead.c:aead_geniv_alloc
```
```
In crypto/skcipher.c (ffffffff814b8593)
Location: include/crypto/algapi.h:379
Inline: True
Inline callers:
  - crypto/skcipher.c:skcipher_alloc_instance_simple
```
```
In crypto/rsa-pkcs1pad.c (ffffffff814bca12)
Location: include/crypto/algapi.h:379
Inline: True
Inline callers:
  - crypto/rsa-pkcs1pad.c:pkcs1pad_create
```
```
In crypto/cts.c (ffffffff814c1ed4)
Location: include/crypto/algapi.h:379
Inline: True
Inline callers:
  - crypto/cts.c:crypto_cts_create
```
```
In crypto/xts.c (ffffffff814c3057)
Location: include/crypto/algapi.h:379
Inline: True
Inline callers:
  - crypto/xts.c:create
```
```
In crypto/ctr.c (ffffffff814c35ba)
Location: include/crypto/algapi.h:379
Inline: True
Inline callers:
  - crypto/ctr.c:crypto_rfc3686_create
  - crypto/ctr.c:crypto_rfc3686_create
```
```
In crypto/gcm.c (ffffffff814c4a5b)
Location: include/crypto/algapi.h:379
Inline: True
Inline callers:
  - crypto/gcm.c:crypto_rfc4543_create
  - crypto/gcm.c:crypto_rfc4106_create
  - crypto/gcm.c:crypto_gcm_create_common
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
In crypto/aead.c (ffffffff814cec15)
Location: include/crypto/algapi.h:379
Inline: True
Inline callers:
  - crypto/aead.c:aead_geniv_alloc
```
```
In crypto/skcipher.c (ffffffff814d1073)
Location: include/crypto/algapi.h:379
Inline: True
Inline callers:
  - crypto/skcipher.c:skcipher_alloc_instance_simple
```
```
In crypto/rsa-pkcs1pad.c (ffffffff814d54e2)
Location: include/crypto/algapi.h:379
Inline: True
Inline callers:
  - crypto/rsa-pkcs1pad.c:pkcs1pad_create
```
```
In crypto/cts.c (ffffffff814da9a4)
Location: include/crypto/algapi.h:379
Inline: True
Inline callers:
  - crypto/cts.c:crypto_cts_create
```
```
In crypto/xts.c (ffffffff814dbb27)
Location: include/crypto/algapi.h:379
Inline: True
Inline callers:
  - crypto/xts.c:create
```
```
In crypto/ctr.c (ffffffff814dc08a)
Location: include/crypto/algapi.h:379
Inline: True
Inline callers:
  - crypto/ctr.c:crypto_rfc3686_create
  - crypto/ctr.c:crypto_rfc3686_create
```
```
In crypto/gcm.c (ffffffff814dd52b)
Location: include/crypto/algapi.h:379
Inline: True
Inline callers:
  - crypto/gcm.c:crypto_rfc4543_create
  - crypto/gcm.c:crypto_rfc4106_create
  - crypto/gcm.c:crypto_gcm_create_common
  - crypto/gcm.c:crypto_gcm_create_common
```
</details>
</li>
</ul>

## Differences
