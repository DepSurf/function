# Function: <code>crypto_get_attr_type</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline ⚠️</summary>

```c
struct crypto_attr_type *crypto_get_attr_type(struct rtattr **tb);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In crypto/algapi.c (ffffffff8139d0d0)
Location: crypto/algapi.c:732
Inline: True
Inline callers:
  - crypto/algapi.c:crypto_check_attr_type
Direct callers:
  - crypto/aead.c:aead_geniv_alloc
  - crypto/blkcipher.c:skcipher_geniv_alloc
  - crypto/chainiv.c:chainiv_alloc
```
**Symbols:**

```
ffffffff8139d0d0-ffffffff8139d10b: crypto_get_attr_type (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
struct crypto_attr_type *crypto_get_attr_type(struct rtattr **tb);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In crypto/algapi.c (ffffffff813da105)
Location: crypto/algapi.c:731
Inline: True
Inline callers:
  - crypto/algapi.c:crypto_check_attr_type
Direct callers:
  - crypto/aead.c:aead_geniv_alloc
  - crypto/seqiv.c:seqiv_create
  - crypto/rsa-pkcs1pad.c:pkcs1pad_create
  - crypto/cts.c:crypto_cts_create
  - crypto/ctr.c:crypto_rfc3686_create
```
**Symbols:**

```
ffffffff813d9fa0-ffffffff813d9fdb: crypto_get_attr_type (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
struct crypto_attr_type *crypto_get_attr_type(struct rtattr **tb);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In crypto/algapi.c (ffffffff813f1a45)
Location: crypto/algapi.c:732
Inline: True
Inline callers:
  - crypto/algapi.c:crypto_check_attr_type
Direct callers:
  - crypto/aead.c:aead_geniv_alloc
  - crypto/seqiv.c:seqiv_create
  - crypto/rsa-pkcs1pad.c:pkcs1pad_create
  - crypto/cts.c:crypto_cts_create
  - crypto/xts.c:create
  - crypto/ctr.c:crypto_rfc3686_create
```
**Symbols:**

```
ffffffff813f18e0-ffffffff813f191b: crypto_get_attr_type (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
struct crypto_attr_type *crypto_get_attr_type(struct rtattr **tb);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In crypto/algapi.c (ffffffff813fdce5)
Location: crypto/algapi.c:732
Inline: True
Inline callers:
  - crypto/algapi.c:crypto_check_attr_type
Direct callers:
  - crypto/aead.c:aead_geniv_alloc
  - crypto/seqiv.c:seqiv_create
  - crypto/rsa-pkcs1pad.c:pkcs1pad_create
  - crypto/cts.c:crypto_cts_create
  - crypto/xts.c:create
  - crypto/ctr.c:crypto_rfc3686_create
```
**Symbols:**

```
ffffffff813fdb60-ffffffff813fdb9b: crypto_get_attr_type (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
struct crypto_attr_type *crypto_get_attr_type(struct rtattr **tb);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In crypto/algapi.c (ffffffff81426295)
Location: crypto/algapi.c:744
Inline: True
Inline callers:
  - crypto/algapi.c:crypto_check_attr_type
Direct callers:
  - crypto/aead.c:aead_geniv_alloc
  - crypto/seqiv.c:seqiv_create
  - crypto/rsa-pkcs1pad.c:pkcs1pad_create
  - crypto/cts.c:crypto_cts_create
  - crypto/xts.c:create
  - crypto/ctr.c:crypto_rfc3686_create
  - crypto/gcm.c:crypto_rfc4543_create
  - crypto/gcm.c:crypto_rfc4106_create
  - crypto/gcm.c:crypto_gcm_create_common
```
**Symbols:**

```
ffffffff81426100-ffffffff8142613b: crypto_get_attr_type (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
struct crypto_attr_type *crypto_get_attr_type(struct rtattr **tb);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In crypto/algapi.c (ffffffff81459045)
Location: crypto/algapi.c:741
Inline: True
Inline callers:
  - crypto/algapi.c:crypto_check_attr_type
Direct callers:
  - crypto/aead.c:aead_geniv_alloc
  - crypto/seqiv.c:seqiv_create
  - crypto/rsa-pkcs1pad.c:pkcs1pad_create
  - crypto/cts.c:crypto_cts_create
  - crypto/xts.c:create
  - crypto/ctr.c:crypto_rfc3686_create
  - crypto/gcm.c:crypto_rfc4543_create
  - crypto/gcm.c:crypto_rfc4106_create
  - crypto/gcm.c:crypto_gcm_create_common
```
**Symbols:**

```
ffffffff81459000-ffffffff8145903b: crypto_get_attr_type (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
struct crypto_attr_type *crypto_get_attr_type(struct rtattr **tb);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In crypto/algapi.c (ffffffff814764c5)
Location: crypto/algapi.c:750
Inline: True
Inline callers:
  - crypto/algapi.c:crypto_check_attr_type
Direct callers:
  - crypto/aead.c:aead_geniv_alloc
  - crypto/seqiv.c:seqiv_create
  - crypto/rsa-pkcs1pad.c:pkcs1pad_create
  - crypto/cts.c:crypto_cts_create
  - crypto/xts.c:create
  - crypto/ctr.c:crypto_rfc3686_create
  - crypto/gcm.c:crypto_rfc4543_create
  - crypto/gcm.c:crypto_rfc4106_create
  - crypto/gcm.c:crypto_gcm_create_common
```
**Symbols:**

```
ffffffff81476480-ffffffff814764bb: crypto_get_attr_type (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
struct crypto_attr_type *crypto_get_attr_type(struct rtattr **tb);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In crypto/algapi.c (ffffffff814a4405)
Location: crypto/algapi.c:761
Inline: True
Inline callers:
  - crypto/algapi.c:crypto_check_attr_type
Direct callers:
  - crypto/aead.c:aead_geniv_alloc
  - crypto/skcipher.c:skcipher_alloc_instance_simple
  - crypto/seqiv.c:seqiv_create
  - crypto/rsa-pkcs1pad.c:pkcs1pad_create
  - crypto/cts.c:crypto_cts_create
  - crypto/xts.c:create
  - crypto/ctr.c:crypto_rfc3686_create
  - crypto/gcm.c:crypto_rfc4543_create
  - crypto/gcm.c:crypto_rfc4106_create
  - crypto/gcm.c:crypto_gcm_create_common
```
**Symbols:**

```
ffffffff814a4280-ffffffff814a42c6: crypto_get_attr_type (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
struct crypto_attr_type *crypto_get_attr_type(struct rtattr **tb);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In crypto/algapi.c (ffffffff814bf035)
Location: crypto/algapi.c:771
Inline: True
Inline callers:
  - crypto/algapi.c:crypto_check_attr_type
Direct callers:
  - crypto/aead.c:aead_geniv_alloc
  - crypto/skcipher.c:skcipher_alloc_instance_simple
  - crypto/seqiv.c:seqiv_create
  - crypto/rsa-pkcs1pad.c:pkcs1pad_create
  - crypto/cts.c:crypto_cts_create
  - crypto/xts.c:create
  - crypto/ctr.c:crypto_rfc3686_create
  - crypto/gcm.c:crypto_rfc4543_create
  - crypto/gcm.c:crypto_rfc4106_create
  - crypto/gcm.c:crypto_gcm_create_common
```
**Symbols:**

```
ffffffff814beeb0-ffffffff814beef6: crypto_get_attr_type (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
struct crypto_attr_type *crypto_get_attr_type(struct rtattr **tb);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In crypto/algapi.c (ffffffff81520255)
Location: crypto/algapi.c:801
Inline: True
Inline callers:
  - crypto/algapi.c:crypto_check_attr_type
Direct callers:
  - crypto/geniv.c:aead_geniv_alloc
  - crypto/skcipher.c:skcipher_alloc_instance_simple
  - crypto/seqiv.c:seqiv_create
  - crypto/rsa-pkcs1pad.c:pkcs1pad_create
  - crypto/cts.c:crypto_cts_create
  - crypto/xts.c:create
  - crypto/ctr.c:crypto_rfc3686_create
  - crypto/gcm.c:crypto_rfc4543_create
  - crypto/gcm.c:crypto_rfc4106_create
  - crypto/gcm.c:crypto_gcm_create_common
```
**Symbols:**

```
ffffffff8151f610-ffffffff8151f656: crypto_get_attr_type (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
struct crypto_attr_type *crypto_get_attr_type(struct rtattr **tb);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In crypto/algapi.c (ffffffff8153d0c5)
Location: crypto/algapi.c:803
Inline: True
Inline callers:
  - crypto/algapi.c:crypto_check_attr_type
```
**Symbols:**

```
ffffffff8153c470-ffffffff8153c4b6: crypto_get_attr_type (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
struct crypto_attr_type *crypto_get_attr_type(struct rtattr **tb);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In crypto/algapi.c (ffffffff815457a5)
Location: crypto/algapi.c:803
Inline: True
Inline callers:
  - crypto/algapi.c:crypto_check_attr_type
```
**Symbols:**

```
ffffffff81544b50-ffffffff81544b96: crypto_get_attr_type (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
struct crypto_attr_type *crypto_get_attr_type(struct rtattr **tb);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In crypto/algapi.c (ffffffff815a5f75)
Location: crypto/algapi.c:803
Inline: True
Inline callers:
  - crypto/algapi.c:crypto_check_attr_type
```
**Symbols:**

```
ffffffff815a52f0-ffffffff815a5336: crypto_get_attr_type (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
struct crypto_attr_type *crypto_get_attr_type(struct rtattr **tb);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In crypto/algapi.c (ffffffff8164d2f5)
Location: crypto/algapi.c:827
Inline: True
Inline callers:
  - crypto/algapi.c:crypto_check_attr_type
```
**Symbols:**

```
ffffffff8164bf90-ffffffff8164bff4: crypto_get_attr_type (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
struct crypto_attr_type *crypto_get_attr_type(struct rtattr **tb);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In crypto/algapi.c (ffffffff81706345)
Location: crypto/algapi.c:846
Inline: True
Inline callers:
  - crypto/algapi.c:crypto_check_attr_type
```
**Symbols:**

```
ffffffff817051a0-ffffffff81705204: crypto_get_attr_type (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
struct crypto_attr_type *crypto_get_attr_type(struct rtattr **tb);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In crypto/algapi.c (ffffffff81741115)
Location: crypto/algapi.c:858
Inline: True
Inline callers:
  - crypto/algapi.c:crypto_check_attr_type
```
**Symbols:**

```
ffffffff8173f470-ffffffff8173f4d4: crypto_get_attr_type (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
struct crypto_attr_type *crypto_get_attr_type(struct rtattr **tb);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In crypto/algapi.c (ffffffff81781fb5)
Location: crypto/algapi.c:859
Inline: True
Inline callers:
  - crypto/algapi.c:crypto_check_attr_type
```
**Symbols:**

```
ffffffff817802f0-ffffffff81780354: crypto_get_attr_type (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Selective Inline ⚠️</summary>

```c
struct crypto_attr_type *crypto_get_attr_type(struct rtattr **tb);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In crypto/algapi.c (ffff8000105b8364)
Location: crypto/algapi.c:771
Inline: True
Inline callers:
  - crypto/algapi.c:crypto_check_attr_type
Direct callers:
  - crypto/aead.c:aead_geniv_alloc
  - crypto/skcipher.c:skcipher_alloc_instance_simple
  - crypto/seqiv.c:seqiv_create
  - crypto/rsa-pkcs1pad.c:pkcs1pad_create
  - crypto/cts.c:crypto_cts_create
  - crypto/xts.c:create
  - crypto/ctr.c:crypto_rfc3686_create
  - crypto/gcm.c:crypto_rfc4543_create
  - crypto/gcm.c:crypto_rfc4106_create
  - crypto/gcm.c:crypto_gcm_create_common
```
**Symbols:**

```
ffff8000105b8148-ffff8000105b81a8: crypto_get_attr_type (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
struct crypto_attr_type *crypto_get_attr_type(struct rtattr **tb);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In crypto/algapi.c (c0766f70)
Location: crypto/algapi.c:771
Inline: True
Inline callers:
  - crypto/algapi.c:crypto_check_attr_type
Direct callers:
  - crypto/aead.c:aead_geniv_alloc
  - crypto/skcipher.c:skcipher_alloc_instance_simple
  - crypto/seqiv.c:seqiv_create
  - crypto/rsa-pkcs1pad.c:pkcs1pad_create
  - crypto/cts.c:crypto_cts_create
  - crypto/xts.c:create
  - crypto/ctr.c:crypto_rfc3686_create
  - crypto/gcm.c:crypto_rfc4543_create
  - crypto/gcm.c:crypto_rfc4106_create
  - crypto/gcm.c:crypto_gcm_create_common
```
**Symbols:**

```
c0766dc0-c0766e14: crypto_get_attr_type (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
struct crypto_attr_type *crypto_get_attr_type(struct rtattr **tb);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In crypto/algapi.c (c00000000073d5a8)
Location: crypto/algapi.c:771
Inline: True
Inline callers:
  - crypto/algapi.c:crypto_check_attr_type
Direct callers:
  - crypto/aead.c:aead_geniv_alloc
  - crypto/skcipher.c:skcipher_alloc_instance_simple
  - crypto/seqiv.c:seqiv_create
  - crypto/rsa-pkcs1pad.c:pkcs1pad_create
  - crypto/cts.c:crypto_cts_create
  - crypto/xts.c:create
  - crypto/ctr.c:crypto_rfc3686_create
  - crypto/gcm.c:crypto_rfc4543_create
  - crypto/gcm.c:crypto_rfc4106_create
  - crypto/gcm.c:crypto_gcm_create_common
```
**Symbols:**

```
c00000000073d200-c00000000073d248: crypto_get_attr_type (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
struct crypto_attr_type *crypto_get_attr_type(struct rtattr **tb);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In crypto/algapi.c (ffffffe0003feb76)
Location: crypto/algapi.c:771
Inline: True
Inline callers:
  - crypto/algapi.c:crypto_check_attr_type
Direct callers:
  - crypto/aead.c:aead_geniv_alloc
  - crypto/skcipher.c:skcipher_alloc_instance_simple
  - crypto/seqiv.c:seqiv_create
  - crypto/rsa-pkcs1pad.c:pkcs1pad_create
  - crypto/cts.c:crypto_cts_create
  - crypto/xts.c:create
  - crypto/ctr.c:crypto_rfc3686_create
  - crypto/gcm.c:crypto_rfc4543_create
  - crypto/gcm.c:crypto_rfc4106_create
  - crypto/gcm.c:crypto_gcm_create_common
```
**Symbols:**

```
ffffffe0003fe89a-ffffffe0003fe8f0: crypto_get_attr_type (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Selective Inline ⚠️</summary>

```c
struct crypto_attr_type *crypto_get_attr_type(struct rtattr **tb);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In crypto/algapi.c (ffffffff814b7615)
Location: crypto/algapi.c:771
Inline: True
Inline callers:
  - crypto/algapi.c:crypto_check_attr_type
Direct callers:
  - crypto/aead.c:aead_geniv_alloc
  - crypto/skcipher.c:skcipher_alloc_instance_simple
  - crypto/seqiv.c:seqiv_create
  - crypto/rsa-pkcs1pad.c:pkcs1pad_create
  - crypto/cts.c:crypto_cts_create
  - crypto/xts.c:create
  - crypto/ctr.c:crypto_rfc3686_create
  - crypto/gcm.c:crypto_rfc4543_create
  - crypto/gcm.c:crypto_rfc4106_create
  - crypto/gcm.c:crypto_gcm_create_common
```
**Symbols:**

```
ffffffff814b7490-ffffffff814b74d6: crypto_get_attr_type (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
struct crypto_attr_type *crypto_get_attr_type(struct rtattr **tb);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In crypto/algapi.c (ffffffff814a8035)
Location: crypto/algapi.c:771
Inline: True
Inline callers:
  - crypto/algapi.c:crypto_check_attr_type
Direct callers:
  - crypto/aead.c:aead_geniv_alloc
  - crypto/skcipher.c:skcipher_alloc_instance_simple
  - crypto/seqiv.c:seqiv_create
  - crypto/rsa-pkcs1pad.c:pkcs1pad_create
  - crypto/cts.c:crypto_cts_create
  - crypto/xts.c:create
  - crypto/ctr.c:crypto_rfc3686_create
  - crypto/gcm.c:crypto_rfc4543_create
  - crypto/gcm.c:crypto_rfc4106_create
  - crypto/gcm.c:crypto_gcm_create_common
```
**Symbols:**

```
ffffffff814a7eb0-ffffffff814a7ef6: crypto_get_attr_type (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
struct crypto_attr_type *crypto_get_attr_type(struct rtattr **tb);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In crypto/algapi.c (ffffffff814b36a5)
Location: crypto/algapi.c:771
Inline: True
Inline callers:
  - crypto/algapi.c:crypto_check_attr_type
Direct callers:
  - crypto/aead.c:aead_geniv_alloc
  - crypto/skcipher.c:skcipher_alloc_instance_simple
  - crypto/seqiv.c:seqiv_create
  - crypto/rsa-pkcs1pad.c:pkcs1pad_create
  - crypto/cts.c:crypto_cts_create
  - crypto/xts.c:create
  - crypto/ctr.c:crypto_rfc3686_create
  - crypto/gcm.c:crypto_rfc4543_create
  - crypto/gcm.c:crypto_rfc4106_create
  - crypto/gcm.c:crypto_gcm_create_common
```
**Symbols:**

```
ffffffff814b3520-ffffffff814b3566: crypto_get_attr_type (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
struct crypto_attr_type *crypto_get_attr_type(struct rtattr **tb);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In crypto/algapi.c (ffffffff814cc125)
Location: crypto/algapi.c:771
Inline: True
Inline callers:
  - crypto/algapi.c:crypto_check_attr_type
Direct callers:
  - crypto/aead.c:aead_geniv_alloc
  - crypto/skcipher.c:skcipher_alloc_instance_simple
  - crypto/seqiv.c:seqiv_create
  - crypto/rsa-pkcs1pad.c:pkcs1pad_create
  - crypto/cts.c:crypto_cts_create
  - crypto/xts.c:create
  - crypto/ctr.c:crypto_rfc3686_create
  - crypto/gcm.c:crypto_rfc4543_create
  - crypto/gcm.c:crypto_rfc4106_create
  - crypto/gcm.c:crypto_gcm_create_common
```
**Symbols:**

```
ffffffff814cbfa0-ffffffff814cbfe6: crypto_get_attr_type (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>4.4</code> and <code>4.8</code> ✅
</li>
<li>
No changes between <code>4.8</code> and <code>4.10</code> ✅
</li>
<li>
No changes between <code>4.10</code> and <code>4.13</code> ✅
</li>
<li>
No changes between <code>4.13</code> and <code>4.15</code> ✅
</li>
<li>
No changes between <code>4.15</code> and <code>4.18</code> ✅
</li>
<li>
No changes between <code>4.18</code> and <code>5.0</code> ✅
</li>
<li>
No changes between <code>5.0</code> and <code>5.3</code> ✅
</li>
<li>
No changes between <code>5.3</code> and <code>5.4</code> ✅
</li>
<li>
No changes between <code>5.4</code> and <code>5.8</code> ✅
</li>
<li>
No changes between <code>5.8</code> and <code>5.11</code> ✅
</li>
<li>
No changes between <code>5.11</code> and <code>5.13</code> ✅
</li>
<li>
No changes between <code>5.13</code> and <code>5.15</code> ✅
</li>
<li>
No changes between <code>5.15</code> and <code>5.19</code> ✅
</li>
<li>
No changes between <code>5.19</code> and <code>6.2</code> ✅
</li>
<li>
No changes between <code>6.2</code> and <code>6.5</code> ✅
</li>
<li>
No changes between <code>6.5</code> and <code>6.8</code> ✅
</li>
</ul>
<b>Arch</b>
<ul>
<li>
No changes between <code>amd64</code> and <code>arm64</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>armhf</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>ppc64el</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>riscv64</code> ✅
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
No changes between <code>generic</code> and <code>aws</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>azure</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>gcp</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>lowlatency</code> ✅
</li>
</ul>
