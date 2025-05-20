# Function: <code>fscrypt_is_key_prepared</code>

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
In fs/crypto/keysetup.c (ffffffff813a489a)
Location: fs/crypto/fscrypt_private.h:352
Inline: True
Inline callers:
  - fs/crypto/keysetup.c:setup_per_mode_enc_key
  - fs/crypto/keysetup.c:setup_per_mode_enc_key
```
```
In fs/crypto/keysetup_v1.c (ffffffff813a5889)
Location: fs/crypto/fscrypt_private.h:352
Inline: True
Inline callers:
  - fs/crypto/keysetup_v1.c:find_or_insert_direct_key
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
In fs/crypto/keysetup.c (ffffffff813abac0)
Location: fs/crypto/fscrypt_private.h:352
Inline: True
Inline callers:
  - fs/crypto/keysetup.c:setup_per_mode_enc_key
  - fs/crypto/keysetup.c:setup_per_mode_enc_key
```
```
In fs/crypto/keysetup_v1.c (ffffffff813ac8e9)
Location: fs/crypto/fscrypt_private.h:352
Inline: True
Inline callers:
  - fs/crypto/keysetup_v1.c:find_or_insert_direct_key
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
In fs/crypto/keysetup.c (ffffffff813fb37e)
Location: fs/crypto/fscrypt_private.h:352
Inline: True
Inline callers:
  - fs/crypto/keysetup.c:setup_per_mode_enc_key
  - fs/crypto/keysetup.c:setup_per_mode_enc_key
```
```
In fs/crypto/keysetup_v1.c (ffffffff813fc25a)
Location: fs/crypto/fscrypt_private.h:352
Inline: True
Inline callers:
  - fs/crypto/keysetup_v1.c:find_or_insert_direct_key
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
In fs/crypto/keysetup.c (ffffffff8146e6f6)
Location: fs/crypto/fscrypt_private.h:357
Inline: True
Inline callers:
  - fs/crypto/keysetup.c:setup_per_mode_enc_key
  - fs/crypto/keysetup.c:setup_per_mode_enc_key
```
```
In fs/crypto/keysetup_v1.c (ffffffff8146f6d8)
Location: fs/crypto/fscrypt_private.h:357
Inline: True
Inline callers:
  - fs/crypto/keysetup_v1.c:find_or_insert_direct_key
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
In fs/crypto/keysetup.c (ffffffff814ffdc5)
Location: fs/crypto/fscrypt_private.h:355
Inline: True
Inline callers:
  - fs/crypto/keysetup.c:setup_per_mode_enc_key
  - fs/crypto/keysetup.c:setup_per_mode_enc_key
```
```
In fs/crypto/keysetup_v1.c (ffffffff81500eb7)
Location: fs/crypto/fscrypt_private.h:355
Inline: True
Inline callers:
  - fs/crypto/keysetup_v1.c:find_or_insert_direct_key
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
In fs/crypto/keysetup.c (ffffffff81537395)
Location: fs/crypto/fscrypt_private.h:355
Inline: True
Inline callers:
  - fs/crypto/keysetup.c:setup_per_mode_enc_key
  - fs/crypto/keysetup.c:setup_per_mode_enc_key
```
```
In fs/crypto/keysetup_v1.c (ffffffff81538547)
Location: fs/crypto/fscrypt_private.h:355
Inline: True
Inline callers:
  - fs/crypto/keysetup_v1.c:find_or_insert_direct_key
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
In fs/crypto/keysetup.c (ffffffff8156c465)
Location: fs/crypto/fscrypt_private.h:397
Inline: True
Inline callers:
  - fs/crypto/keysetup.c:setup_per_mode_enc_key
  - fs/crypto/keysetup.c:setup_per_mode_enc_key
```
```
In fs/crypto/keysetup_v1.c (ffffffff8156d697)
Location: fs/crypto/fscrypt_private.h:397
Inline: True
Inline callers:
  - fs/crypto/keysetup_v1.c:find_or_insert_direct_key
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
