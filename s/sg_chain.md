# Function: <code>sg_chain</code>

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
In crypto/scatterwalk.c (ffffffff8139eb4f)
Location: include/linux/scatterlist.h:161
Inline: True
Inline callers:
  - crypto/scatterwalk.c:scatterwalk_ffwd
```
```
In crypto/eseqiv.c (ffffffff813a268a)
Location: include/linux/scatterlist.h:161
Inline: True
Inline callers:
  - crypto/eseqiv.c:eseqiv_givencrypt
  - crypto/eseqiv.c:eseqiv_givencrypt
```
```
In lib/scatterlist.c (ffffffff813f9f83)
Location: include/linux/scatterlist.h:161
Inline: True
Inline callers:
  - lib/scatterlist.c:__sg_alloc_table
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
In crypto/scatterwalk.c (ffffffff813db912)
Location: include/linux/scatterlist.h:161
Inline: True
```
```
In crypto/rsa-pkcs1pad.c (ffffffff813e0f39)
Location: include/linux/scatterlist.h:161
Inline: True
Inline callers:
  - crypto/rsa-pkcs1pad.c:pkcs1pad_sg_set_buf
```
```
In lib/scatterlist.c (ffffffff81440f53)
Location: include/linux/scatterlist.h:161
Inline: True
Inline callers:
  - lib/scatterlist.c:__sg_alloc_table
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
In crypto/scatterwalk.c (ffffffff813f3252)
Location: include/linux/scatterlist.h:161
Inline: True
```
```
In crypto/rsa-pkcs1pad.c (ffffffff813f9cf5)
Location: include/linux/scatterlist.h:161
Inline: True
```
```
In crypto/xts.c (ffffffff81401b21)
Location: include/linux/scatterlist.h:161
Inline: True
Inline callers:
  - crypto/xts.c:pre_crypt
  - crypto/xts.c:post_crypt
```
```
In lib/scatterlist.c (ffffffff8145e173)
Location: include/linux/scatterlist.h:161
Inline: True
Inline callers:
  - lib/scatterlist.c:__sg_alloc_table
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
In crypto/scatterwalk.c (ffffffff813ff572)
Location: include/linux/scatterlist.h:161
Inline: True
```
```
In crypto/rsa-pkcs1pad.c (ffffffff81406535)
Location: include/linux/scatterlist.h:161
Inline: True
```
```
In crypto/xts.c (ffffffff8140eeed)
Location: include/linux/scatterlist.h:161
Inline: True
Inline callers:
  - crypto/xts.c:pre_crypt
  - crypto/xts.c:post_crypt
```
```
In lib/scatterlist.c (ffffffff814637c3)
Location: include/linux/scatterlist.h:161
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
In crypto/scatterwalk.c (ffffffff81427b32)
Location: include/linux/scatterlist.h:168
Inline: True
```
```
In crypto/rsa-pkcs1pad.c (ffffffff8142ee75)
Location: include/linux/scatterlist.h:168
Inline: True
```
```
In crypto/xts.c (ffffffff814379bd)
Location: include/linux/scatterlist.h:168
Inline: True
Inline callers:
  - crypto/xts.c:pre_crypt
  - crypto/xts.c:post_crypt
```
```
In crypto/gcm.c (ffffffff81439de5)
Location: include/linux/scatterlist.h:168
Inline: True
Inline callers:
  - crypto/gcm.c:crypto_rfc4106_crypt
  - crypto/gcm.c:crypto_rfc4106_crypt
  - crypto/gcm.c:crypto_gcm_init_common
  - crypto/gcm.c:crypto_gcm_init_common
```
```
In lib/scatterlist.c (ffffffff8148f6d3)
Location: include/linux/scatterlist.h:168
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
In crypto/scatterwalk.c (ffffffff8145a992)
Location: include/linux/scatterlist.h:164
Inline: True
```
```
In crypto/rsa-pkcs1pad.c (ffffffff81461ad5)
Location: include/linux/scatterlist.h:164
Inline: True
```
```
In crypto/xts.c (ffffffff8146a2dc)
Location: include/linux/scatterlist.h:164
Inline: True
Inline callers:
  - crypto/xts.c:pre_crypt
  - crypto/xts.c:post_crypt
```
```
In crypto/gcm.c (ffffffff8146cad5)
Location: include/linux/scatterlist.h:164
Inline: True
Inline callers:
  - crypto/gcm.c:crypto_rfc4106_crypt
  - crypto/gcm.c:crypto_rfc4106_crypt
  - crypto/gcm.c:crypto_gcm_init_common
  - crypto/gcm.c:crypto_gcm_init_common
```
```
In lib/scatterlist.c (ffffffff814c4361)
Location: include/linux/scatterlist.h:164
Inline: True
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
In crypto/scatterwalk.c (ffffffff81478502)
Location: include/linux/scatterlist.h:164
Inline: True
```
```
In crypto/rsa-pkcs1pad.c (ffffffff8147f925)
Location: include/linux/scatterlist.h:164
Inline: True
```
```
In crypto/gcm.c (ffffffff8148a245)
Location: include/linux/scatterlist.h:164
Inline: True
Inline callers:
  - crypto/gcm.c:crypto_rfc4106_crypt
  - crypto/gcm.c:crypto_rfc4106_crypt
  - crypto/gcm.c:crypto_gcm_init_common
  - crypto/gcm.c:crypto_gcm_init_common
```
```
In lib/scatterlist.c (ffffffff814d8a51)
Location: include/linux/scatterlist.h:164
Inline: True
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
In crypto/scatterwalk.c (ffffffff814a6320)
Location: include/linux/scatterlist.h:164
Inline: True
```
```
In crypto/rsa-pkcs1pad.c (ffffffff814ad925)
Location: include/linux/scatterlist.h:164
Inline: True
```
```
In crypto/gcm.c (ffffffff814b7a2b)
Location: include/linux/scatterlist.h:164
Inline: True
Inline callers:
  - crypto/gcm.c:crypto_rfc4106_crypt
  - crypto/gcm.c:crypto_rfc4106_crypt
  - crypto/gcm.c:crypto_gcm_init_common
  - crypto/gcm.c:crypto_gcm_init_common
```
```
In lib/scatterlist.c (ffffffff815044c7)
Location: include/linux/scatterlist.h:164
Inline: True
Inline callers:
  - lib/scatterlist.c:__sg_alloc_table
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
In crypto/scatterwalk.c (ffffffff814c0fb0)
Location: include/linux/scatterlist.h:164
Inline: True
```
```
In crypto/rsa-pkcs1pad.c (ffffffff814c85d5)
Location: include/linux/scatterlist.h:164
Inline: True
```
```
In crypto/gcm.c (ffffffff814d0c4b)
Location: include/linux/scatterlist.h:164
Inline: True
Inline callers:
  - crypto/gcm.c:crypto_rfc4106_crypt
  - crypto/gcm.c:crypto_rfc4106_crypt
  - crypto/gcm.c:crypto_gcm_init_common
  - crypto/gcm.c:crypto_gcm_init_common
```
```
In lib/scatterlist.c (ffffffff815224d7)
Location: include/linux/scatterlist.h:164
Inline: True
Inline callers:
  - lib/scatterlist.c:__sg_alloc_table
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
In crypto/scatterwalk.c (ffffffff81521860)
Location: include/linux/scatterlist.h:178
Inline: True
Inline callers:
  - crypto/scatterwalk.c:scatterwalk_ffwd
```
```
In crypto/rsa-pkcs1pad.c (ffffffff81527b95)
Location: include/linux/scatterlist.h:178
Inline: True
```
```
In crypto/gcm.c (ffffffff8152f92b)
Location: include/linux/scatterlist.h:178
Inline: True
Inline callers:
  - crypto/gcm.c:crypto_rfc4106_crypt
  - crypto/gcm.c:crypto_rfc4106_crypt
  - crypto/gcm.c:crypto_gcm_init_common
  - crypto/gcm.c:crypto_gcm_init_common
```
```
In lib/scatterlist.c (ffffffff81585837)
Location: include/linux/scatterlist.h:178
Inline: True
Inline callers:
  - lib/scatterlist.c:__sg_alloc_table
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
In crypto/scatterwalk.c (ffffffff8153e6d0)
Location: include/linux/scatterlist.h:188
Inline: True
Inline callers:
  - crypto/scatterwalk.c:scatterwalk_ffwd
```
```
In crypto/rsa-pkcs1pad.c (ffffffff81544b05)
Location: include/linux/scatterlist.h:188
Inline: True
```
```
In crypto/gcm.c (ffffffff8154c4eb)
Location: include/linux/scatterlist.h:188
Inline: True
Inline callers:
  - crypto/gcm.c:crypto_rfc4106_crypt
  - crypto/gcm.c:crypto_rfc4106_crypt
  - crypto/gcm.c:crypto_gcm_init_common
  - crypto/gcm.c:crypto_gcm_init_common
```
```
In lib/scatterlist.c (ffffffff815a2917)
Location: include/linux/scatterlist.h:188
Inline: True
Inline callers:
  - lib/scatterlist.c:__sg_alloc_table
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
In crypto/scatterwalk.c (ffffffff81546d80)
Location: include/linux/scatterlist.h:188
Inline: True
Inline callers:
  - crypto/scatterwalk.c:scatterwalk_ffwd
```
```
In crypto/rsa-pkcs1pad.c (ffffffff8154d1a6)
Location: include/linux/scatterlist.h:188
Inline: True
```
```
In crypto/gcm.c (ffffffff8155534b)
Location: include/linux/scatterlist.h:188
Inline: True
Inline callers:
  - crypto/gcm.c:crypto_rfc4106_crypt
  - crypto/gcm.c:crypto_rfc4106_crypt
  - crypto/gcm.c:crypto_gcm_init_common
  - crypto/gcm.c:crypto_gcm_init_common
```
```
In lib/scatterlist.c (ffffffff815a9851)
Location: include/linux/scatterlist.h:188
Inline: True
Inline callers:
  - lib/scatterlist.c:__sg_alloc_table
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
In crypto/scatterwalk.c (ffffffff815a7560)
Location: include/linux/scatterlist.h:194
Inline: True
Inline callers:
  - crypto/scatterwalk.c:scatterwalk_ffwd
```
```
In crypto/rsa-pkcs1pad.c (ffffffff815ad986)
Location: include/linux/scatterlist.h:194
Inline: True
```
```
In crypto/gcm.c (ffffffff815b637b)
Location: include/linux/scatterlist.h:194
Inline: True
Inline callers:
  - crypto/gcm.c:crypto_rfc4106_crypt
  - crypto/gcm.c:crypto_rfc4106_crypt
  - crypto/gcm.c:crypto_gcm_init_common
  - crypto/gcm.c:crypto_gcm_init_common
```
```
In lib/scatterlist.c (ffffffff81612a91)
Location: include/linux/scatterlist.h:194
Inline: True
Inline callers:
  - lib/scatterlist.c:__sg_alloc_table
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
In crypto/scatterwalk.c (ffffffff8164e65f)
Location: include/linux/scatterlist.h:211
Inline: True
Inline callers:
  - crypto/scatterwalk.c:scatterwalk_ffwd
```
```
In crypto/rsa-pkcs1pad.c (ffffffff81655e86)
Location: include/linux/scatterlist.h:211
Inline: True
```
```
In crypto/gcm.c (ffffffff8165f625)
Location: include/linux/scatterlist.h:211
Inline: True
Inline callers:
  - crypto/gcm.c:crypto_rfc4106_crypt
  - crypto/gcm.c:crypto_rfc4106_crypt
  - crypto/gcm.c:crypto_gcm_init_common
  - crypto/gcm.c:crypto_gcm_init_common
```
```
In lib/scatterlist.c (ffffffff816df17b)
Location: include/linux/scatterlist.h:211
Inline: True
Inline callers:
  - lib/scatterlist.c:__sg_alloc_table
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
In crypto/scatterwalk.c (ffffffff81707aaf)
Location: include/linux/scatterlist.h:214
Inline: True
Inline callers:
  - crypto/scatterwalk.c:scatterwalk_ffwd
```
```
In crypto/rsa-pkcs1pad.c (ffffffff81710046)
Location: include/linux/scatterlist.h:214
Inline: True
```
```
In crypto/gcm.c (ffffffff81719455)
Location: include/linux/scatterlist.h:214
Inline: True
Inline callers:
  - crypto/gcm.c:crypto_rfc4106_crypt
  - crypto/gcm.c:crypto_rfc4106_crypt
  - crypto/gcm.c:crypto_gcm_init_common
  - crypto/gcm.c:crypto_gcm_init_common
```
```
In lib/scatterlist.c (ffffffff817cf38b)
Location: include/linux/scatterlist.h:214
Inline: True
Inline callers:
  - lib/scatterlist.c:__sg_alloc_table
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
In crypto/scatterwalk.c (ffffffff8174121f)
Location: include/linux/scatterlist.h:238
Inline: True
Inline callers:
  - crypto/scatterwalk.c:scatterwalk_ffwd
```
```
In crypto/rsa-pkcs1pad.c (ffffffff8174a9d6)
Location: include/linux/scatterlist.h:238
Inline: True
```
```
In crypto/gcm.c (ffffffff81754de5)
Location: include/linux/scatterlist.h:238
Inline: True
Inline callers:
  - crypto/gcm.c:crypto_rfc4106_crypt
  - crypto/gcm.c:crypto_rfc4106_crypt
  - crypto/gcm.c:crypto_gcm_init_common
  - crypto/gcm.c:crypto_gcm_init_common
```
```
In lib/scatterlist.c (ffffffff8180d83b)
Location: include/linux/scatterlist.h:238
Inline: True
Inline callers:
  - lib/scatterlist.c:__sg_alloc_table
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
In crypto/scatterwalk.c (ffffffff817820bf)
Location: include/linux/scatterlist.h:238
Inline: True
Inline callers:
  - crypto/scatterwalk.c:scatterwalk_ffwd
```
```
In crypto/rsa-pkcs1pad.c (ffffffff8178c8a6)
Location: include/linux/scatterlist.h:238
Inline: True
```
```
In crypto/gcm.c (ffffffff81796da5)
Location: include/linux/scatterlist.h:238
Inline: True
Inline callers:
  - crypto/gcm.c:crypto_rfc4106_crypt
  - crypto/gcm.c:crypto_rfc4106_crypt
  - crypto/gcm.c:crypto_gcm_init_common
  - crypto/gcm.c:crypto_gcm_init_common
```
```
In lib/scatterlist.c (ffffffff818534eb)
Location: include/linux/scatterlist.h:238
Inline: True
Inline callers:
  - lib/scatterlist.c:__sg_alloc_table
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
In crypto/scatterwalk.c (ffff8000105baf94)
Location: include/linux/scatterlist.h:164
Inline: True
```
```
In crypto/rsa-pkcs1pad.c (ffff8000105c3ed4)
Location: include/linux/scatterlist.h:164
Inline: True
Inline callers:
  - crypto/rsa-pkcs1pad.c:pkcs1pad_sg_set_buf
```
```
In crypto/gcm.c (ffff8000105ccfe0)
Location: include/linux/scatterlist.h:164
Inline: True
Inline callers:
  - crypto/gcm.c:crypto_rfc4106_crypt
  - crypto/gcm.c:crypto_rfc4106_crypt
  - crypto/gcm.c:crypto_gcm_init_common
  - crypto/gcm.c:crypto_gcm_init_common
```
```
In lib/scatterlist.c (ffff80001062c14c)
Location: include/linux/scatterlist.h:164
Inline: True
Inline callers:
  - lib/scatterlist.c:__sg_alloc_table
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
In crypto/scatterwalk.c (c07692cc)
Location: include/linux/scatterlist.h:164
Inline: True
```
```
In crypto/rsa-pkcs1pad.c (c0771238)
Location: include/linux/scatterlist.h:164
Inline: True
```
```
In crypto/gcm.c (c077a85c)
Location: include/linux/scatterlist.h:164
Inline: True
Inline callers:
  - crypto/gcm.c:crypto_rfc4106_crypt
  - crypto/gcm.c:crypto_rfc4106_crypt
  - crypto/gcm.c:crypto_gcm_init_common
  - crypto/gcm.c:crypto_gcm_init_common
```
```
In lib/scatterlist.c (c07d2b2c)
Location: include/linux/scatterlist.h:164
Inline: True
Inline callers:
  - lib/scatterlist.c:__sg_alloc_table
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
In crypto/scatterwalk.c (c000000000741628)
Location: include/linux/scatterlist.h:164
Inline: True
```
```
In crypto/rsa-pkcs1pad.c (c00000000074ca04)
Location: include/linux/scatterlist.h:164
Inline: True
Inline callers:
  - crypto/rsa-pkcs1pad.c:pkcs1pad_sg_set_buf
```
```
In crypto/gcm.c (c000000000757e5c)
Location: include/linux/scatterlist.h:164
Inline: True
Inline callers:
  - crypto/gcm.c:crypto_rfc4106_crypt
  - crypto/gcm.c:crypto_rfc4106_crypt
  - crypto/gcm.c:crypto_gcm_init_common
  - crypto/gcm.c:crypto_gcm_init_common
```
```
In lib/scatterlist.c (c0000000007ceab4)
Location: include/linux/scatterlist.h:164
Inline: True
Inline callers:
  - lib/scatterlist.c:__sg_alloc_table
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
In crypto/scatterwalk.c (ffffffe000400ce8)
Location: include/linux/scatterlist.h:164
Inline: True
```
```
In crypto/rsa-pkcs1pad.c (ffffffe000407e92)
Location: include/linux/scatterlist.h:164
Inline: True
Inline callers:
  - crypto/rsa-pkcs1pad.c:pkcs1pad_sg_set_buf
```
```
In crypto/gcm.c (ffffffe00040ffe8)
Location: include/linux/scatterlist.h:164
Inline: True
Inline callers:
  - crypto/gcm.c:crypto_rfc4106_crypt
  - crypto/gcm.c:crypto_rfc4106_crypt
  - crypto/gcm.c:crypto_gcm_init_common
  - crypto/gcm.c:crypto_gcm_init_common
```
```
In lib/scatterlist.c (ffffffe00045c388)
Location: include/linux/scatterlist.h:164
Inline: True
Inline callers:
  - lib/scatterlist.c:__sg_alloc_table
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
In crypto/scatterwalk.c (ffffffff814b9590)
Location: include/linux/scatterlist.h:164
Inline: True
```
```
In crypto/rsa-pkcs1pad.c (ffffffff814c0bb5)
Location: include/linux/scatterlist.h:164
Inline: True
```
```
In crypto/gcm.c (ffffffff814c922b)
Location: include/linux/scatterlist.h:164
Inline: True
Inline callers:
  - crypto/gcm.c:crypto_rfc4106_crypt
  - crypto/gcm.c:crypto_rfc4106_crypt
  - crypto/gcm.c:crypto_gcm_init_common
  - crypto/gcm.c:crypto_gcm_init_common
```
```
In lib/scatterlist.c (ffffffff8151aab7)
Location: include/linux/scatterlist.h:164
Inline: True
Inline callers:
  - lib/scatterlist.c:__sg_alloc_table
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
In crypto/scatterwalk.c (ffffffff814a9fb0)
Location: include/linux/scatterlist.h:164
Inline: True
```
```
In crypto/rsa-pkcs1pad.c (ffffffff814b15d5)
Location: include/linux/scatterlist.h:164
Inline: True
```
```
In crypto/gcm.c (ffffffff814b9c4b)
Location: include/linux/scatterlist.h:164
Inline: True
Inline callers:
  - crypto/gcm.c:crypto_rfc4106_crypt
  - crypto/gcm.c:crypto_rfc4106_crypt
  - crypto/gcm.c:crypto_gcm_init_common
  - crypto/gcm.c:crypto_gcm_init_common
```
```
In lib/scatterlist.c (ffffffff8150ada7)
Location: include/linux/scatterlist.h:164
Inline: True
Inline callers:
  - lib/scatterlist.c:__sg_alloc_table
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
In crypto/scatterwalk.c (ffffffff814b5620)
Location: include/linux/scatterlist.h:164
Inline: True
```
```
In crypto/rsa-pkcs1pad.c (ffffffff814bcc45)
Location: include/linux/scatterlist.h:164
Inline: True
```
```
In crypto/gcm.c (ffffffff814c52bb)
Location: include/linux/scatterlist.h:164
Inline: True
Inline callers:
  - crypto/gcm.c:crypto_rfc4106_crypt
  - crypto/gcm.c:crypto_rfc4106_crypt
  - crypto/gcm.c:crypto_gcm_init_common
  - crypto/gcm.c:crypto_gcm_init_common
```
```
In lib/scatterlist.c (ffffffff81516b47)
Location: include/linux/scatterlist.h:164
Inline: True
Inline callers:
  - lib/scatterlist.c:__sg_alloc_table
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
In crypto/scatterwalk.c (ffffffff814ce0c0)
Location: include/linux/scatterlist.h:164
Inline: True
```
```
In crypto/rsa-pkcs1pad.c (ffffffff814d5715)
Location: include/linux/scatterlist.h:164
Inline: True
```
```
In crypto/gcm.c (ffffffff814ddd8b)
Location: include/linux/scatterlist.h:164
Inline: True
Inline callers:
  - crypto/gcm.c:crypto_rfc4106_crypt
  - crypto/gcm.c:crypto_rfc4106_crypt
  - crypto/gcm.c:crypto_gcm_init_common
  - crypto/gcm.c:crypto_gcm_init_common
```
```
In lib/scatterlist.c (ffffffff815302d7)
Location: include/linux/scatterlist.h:164
Inline: True
Inline callers:
  - lib/scatterlist.c:__sg_alloc_table
```
</details>
</li>
</ul>

## Differences
