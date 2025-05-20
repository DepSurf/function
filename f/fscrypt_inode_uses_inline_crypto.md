# Function: <code>fscrypt_inode_uses_inline_crypto</code>

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
In fs/crypto/bio.c (ffffffff813a6e1f)
Location: include/linux/fscrypt.h:651
Inline: True
Inline callers:
  - fs/crypto/bio.c:fscrypt_zeroout_range
```
```
In fs/crypto/inline_crypt.c (ffffffff813a727f)
Location: include/linux/fscrypt.h:651
Inline: True
Inline callers:
  - fs/crypto/inline_crypt.c:fscrypt_mergeable_bio
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
In fs/crypto/bio.c (ffffffff813ade8f)
Location: include/linux/fscrypt.h:658
Inline: True
Inline callers:
  - fs/crypto/bio.c:fscrypt_zeroout_range
```
```
In fs/crypto/inline_crypt.c (ffffffff813ae2e3)
Location: include/linux/fscrypt.h:658
Inline: True
Inline callers:
  - fs/crypto/inline_crypt.c:fscrypt_mergeable_bio
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
In fs/crypto/bio.c (ffffffff813fd853)
Location: include/linux/fscrypt.h:759
Inline: True
Inline callers:
  - fs/crypto/bio.c:fscrypt_zeroout_range
```
```
In fs/crypto/inline_crypt.c (ffffffff813fdf69)
Location: include/linux/fscrypt.h:759
Inline: True
Inline callers:
  - fs/crypto/inline_crypt.c:fscrypt_mergeable_bio
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
In fs/crypto/bio.c (ffffffff8147104f)
Location: include/linux/fscrypt.h:823
Inline: True
Inline callers:
  - fs/crypto/bio.c:fscrypt_zeroout_range
```
```
In fs/crypto/inline_crypt.c (ffffffff814717cb)
Location: include/linux/fscrypt.h:823
Inline: True
Inline callers:
  - fs/crypto/inline_crypt.c:fscrypt_dio_supported
  - fs/crypto/inline_crypt.c:fscrypt_mergeable_bio
  - fs/crypto/inline_crypt.c:fscrypt_set_bio_crypt_ctx
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
In fs/crypto/bio.c (ffffffff81502b3f)
Location: include/linux/fscrypt.h:821
Inline: True
Inline callers:
  - fs/crypto/bio.c:fscrypt_zeroout_range
```
```
In fs/crypto/inline_crypt.c (ffffffff81503529)
Location: include/linux/fscrypt.h:821
Inline: True
Inline callers:
  - fs/crypto/inline_crypt.c:fscrypt_mergeable_bio
  - fs/crypto/inline_crypt.c:fscrypt_set_bio_crypt_ctx
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
In fs/crypto/bio.c (ffffffff8153a11f)
Location: include/linux/fscrypt.h:839
Inline: True
Inline callers:
  - fs/crypto/bio.c:fscrypt_zeroout_range
```
```
In fs/crypto/inline_crypt.c (ffffffff8153add9)
Location: include/linux/fscrypt.h:839
Inline: True
Inline callers:
  - fs/crypto/inline_crypt.c:fscrypt_mergeable_bio
  - fs/crypto/inline_crypt.c:fscrypt_set_bio_crypt_ctx
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
In fs/crypto/bio.c (ffffffff8156f499)
Location: include/linux/fscrypt.h:855
Inline: True
Inline callers:
  - fs/crypto/bio.c:fscrypt_zeroout_range
```
```
In fs/crypto/inline_crypt.c (ffffffff815700f9)
Location: include/linux/fscrypt.h:855
Inline: True
Inline callers:
  - fs/crypto/inline_crypt.c:fscrypt_mergeable_bio
  - fs/crypto/inline_crypt.c:fscrypt_set_bio_crypt_ctx
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
