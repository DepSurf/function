# Function: <code>__sg_chain</code>

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
In <code>4.10</code>: Absent ⚠️
</li>
<li>
In <code>4.13</code>: Absent ⚠️
</li>
<li>
In <code>4.15</code>: Absent ⚠️
</li>
<li>
In <code>4.18</code>: Absent ⚠️
</li>
<li>
In <code>5.0</code>: Absent ⚠️
</li>
<li>
In <code>5.3</code>: Absent ⚠️
</li>
<li>
In <code>5.4</code>: Absent ⚠️
</li>
<li>
In <code>5.8</code>: Absent ⚠️
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
Location: include/linux/scatterlist.h:162
Inline: True
Inline callers:
  - crypto/scatterwalk.c:scatterwalk_ffwd
```
```
In crypto/rsa-pkcs1pad.c (ffffffff81544b18)
Location: include/linux/scatterlist.h:162
Inline: True
```
```
In crypto/gcm.c (ffffffff8154c4eb)
Location: include/linux/scatterlist.h:162
Inline: True
Inline callers:
  - crypto/gcm.c:crypto_rfc4106_crypt
  - crypto/gcm.c:crypto_rfc4106_crypt
  - crypto/gcm.c:crypto_gcm_init_common
  - crypto/gcm.c:crypto_gcm_init_common
```
```
In lib/scatterlist.c (ffffffff815a3628)
Location: include/linux/scatterlist.h:162
Inline: True
Inline callers:
  - lib/scatterlist.c:__sg_alloc_table_from_pages
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
Location: include/linux/scatterlist.h:162
Inline: True
Inline callers:
  - crypto/scatterwalk.c:scatterwalk_ffwd
```
```
In crypto/rsa-pkcs1pad.c (ffffffff8154d1b9)
Location: include/linux/scatterlist.h:162
Inline: True
```
```
In crypto/gcm.c (ffffffff8155534b)
Location: include/linux/scatterlist.h:162
Inline: True
Inline callers:
  - crypto/gcm.c:crypto_rfc4106_crypt
  - crypto/gcm.c:crypto_rfc4106_crypt
  - crypto/gcm.c:crypto_gcm_init_common
  - crypto/gcm.c:crypto_gcm_init_common
```
```
In lib/scatterlist.c (ffffffff815aa1e4)
Location: include/linux/scatterlist.h:162
Inline: True
Inline callers:
  - lib/scatterlist.c:__sg_alloc_table_from_pages
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
Location: include/linux/scatterlist.h:168
Inline: True
Inline callers:
  - crypto/scatterwalk.c:scatterwalk_ffwd
```
```
In crypto/rsa-pkcs1pad.c (ffffffff815ad999)
Location: include/linux/scatterlist.h:168
Inline: True
```
```
In crypto/gcm.c (ffffffff815b637b)
Location: include/linux/scatterlist.h:168
Inline: True
Inline callers:
  - crypto/gcm.c:crypto_rfc4106_crypt
  - crypto/gcm.c:crypto_rfc4106_crypt
  - crypto/gcm.c:crypto_gcm_init_common
  - crypto/gcm.c:crypto_gcm_init_common
```
```
In lib/scatterlist.c (ffffffff8161328b)
Location: include/linux/scatterlist.h:168
Inline: True
Inline callers:
  - lib/scatterlist.c:sg_alloc_append_table_from_pages
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
Location: include/linux/scatterlist.h:185
Inline: True
Inline callers:
  - crypto/scatterwalk.c:scatterwalk_ffwd
```
```
In crypto/rsa-pkcs1pad.c (ffffffff81655e99)
Location: include/linux/scatterlist.h:185
Inline: True
```
```
In crypto/gcm.c (ffffffff8165f625)
Location: include/linux/scatterlist.h:185
Inline: True
Inline callers:
  - crypto/gcm.c:crypto_rfc4106_crypt
  - crypto/gcm.c:crypto_rfc4106_crypt
  - crypto/gcm.c:crypto_gcm_init_common
  - crypto/gcm.c:crypto_gcm_init_common
```
```
In lib/scatterlist.c (ffffffff816df878)
Location: include/linux/scatterlist.h:185
Inline: True
Inline callers:
  - lib/scatterlist.c:sg_alloc_append_table_from_pages
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
Location: include/linux/scatterlist.h:188
Inline: True
Inline callers:
  - crypto/scatterwalk.c:scatterwalk_ffwd
```
```
In crypto/rsa-pkcs1pad.c (ffffffff81710059)
Location: include/linux/scatterlist.h:188
Inline: True
```
```
In crypto/gcm.c (ffffffff81719455)
Location: include/linux/scatterlist.h:188
Inline: True
Inline callers:
  - crypto/gcm.c:crypto_rfc4106_crypt
  - crypto/gcm.c:crypto_rfc4106_crypt
  - crypto/gcm.c:crypto_gcm_init_common
  - crypto/gcm.c:crypto_gcm_init_common
```
```
In lib/scatterlist.c (ffffffff817cfdc2)
Location: include/linux/scatterlist.h:188
Inline: True
Inline callers:
  - lib/scatterlist.c:sg_alloc_append_table_from_pages
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
Location: include/linux/scatterlist.h:212
Inline: True
Inline callers:
  - crypto/scatterwalk.c:scatterwalk_ffwd
```
```
In crypto/rsa-pkcs1pad.c (ffffffff8174a9e9)
Location: include/linux/scatterlist.h:212
Inline: True
```
```
In crypto/gcm.c (ffffffff81754de5)
Location: include/linux/scatterlist.h:212
Inline: True
Inline callers:
  - crypto/gcm.c:crypto_rfc4106_crypt
  - crypto/gcm.c:crypto_rfc4106_crypt
  - crypto/gcm.c:crypto_gcm_init_common
  - crypto/gcm.c:crypto_gcm_init_common
```
```
In lib/scatterlist.c (ffffffff8180ec3c)
Location: include/linux/scatterlist.h:212
Inline: True
Inline callers:
  - lib/scatterlist.c:sg_alloc_append_table_from_pages
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
Location: include/linux/scatterlist.h:212
Inline: True
Inline callers:
  - crypto/scatterwalk.c:scatterwalk_ffwd
```
```
In crypto/rsa-pkcs1pad.c (ffffffff8178c8b9)
Location: include/linux/scatterlist.h:212
Inline: True
```
```
In crypto/gcm.c (ffffffff81796da5)
Location: include/linux/scatterlist.h:212
Inline: True
Inline callers:
  - crypto/gcm.c:crypto_rfc4106_crypt
  - crypto/gcm.c:crypto_rfc4106_crypt
  - crypto/gcm.c:crypto_gcm_init_common
  - crypto/gcm.c:crypto_gcm_init_common
```
```
In lib/scatterlist.c (ffffffff818548bf)
Location: include/linux/scatterlist.h:212
Inline: True
Inline callers:
  - lib/scatterlist.c:sg_alloc_append_table_from_pages
  - lib/scatterlist.c:__sg_alloc_table
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
In <code>arm64</code>: Absent ⚠️
</li>
<li>
In <code>armhf</code>: Absent ⚠️
</li>
<li>
In <code>ppc64el</code>: Absent ⚠️
</li>
<li>
In <code>riscv64</code>: Absent ⚠️
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
In <code>aws</code>: Absent ⚠️
</li>
<li>
In <code>azure</code>: Absent ⚠️
</li>
<li>
In <code>gcp</code>: Absent ⚠️
</li>
<li>
In <code>lowlatency</code>: Absent ⚠️
</li>
</ul>

## Differences
