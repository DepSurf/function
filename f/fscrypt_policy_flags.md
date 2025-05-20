# Function: <code>fscrypt_policy_flags</code>

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
<details>
<summary>In <code>5.4</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/crypto/crypto.c (ffffffff8134a628)
Location: fs/crypto/fscrypt_private.h:128
Inline: True
Inline callers:
  - fs/crypto/crypto.c:fscrypt_generate_iv
```
```
In fs/crypto/fname.c (ffffffff8134b30d)
Location: fs/crypto/fscrypt_private.h:128
Inline: True
```
```
In fs/crypto/keysetup.c (ffffffff8134d6a1)
Location: fs/crypto/fscrypt_private.h:128
Inline: True
Inline callers:
  - fs/crypto/keysetup.c:put_crypt_info
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
In fs/crypto/crypto.c (ffffffff8138fda5)
Location: fs/crypto/fscrypt_private.h:149
Inline: True
Inline callers:
  - fs/crypto/crypto.c:fscrypt_generate_iv
```
```
In fs/crypto/fname.c (ffffffff81390ce5)
Location: fs/crypto/fscrypt_private.h:149
Inline: True
Inline callers:
  - fs/crypto/fname.c:fscrypt_fname_encrypted_size
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Duplicate, Selective Inline, Transformation ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/crypto/crypto.c (ffffffff813a13e5)
Location: fs/crypto/fscrypt_private.h:152
Inline: True
Inline callers:
  - fs/crypto/crypto.c:fscrypt_generate_iv
```
```
In fs/crypto/fname.c (ffffffff813a2195)
Location: fs/crypto/fscrypt_private.h:152
Inline: True
Inline callers:
  - fs/crypto/fname.c:fscrypt_fname_encrypted_size
```
```
In fs/crypto/inline_crypt.c (ffffffff813a759c)
Location: fs/crypto/fscrypt_private.h:152
Inline: True
Inline callers:
  - fs/crypto/inline_crypt.c:fscrypt_select_encryption_impl
  - fs/crypto/inline_crypt.c:fscrypt_get_dun_bytes
Direct callers:
  - fs/crypto/inline_crypt.c:fscrypt_select_encryption_impl
  - fs/crypto/inline_crypt.c:fscrypt_get_dun_bytes
```
**Symbols:**

```
ffffffff813a7380-ffffffff813a7382: fscrypt_policy_flags.part.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Duplicate, Selective Inline, Transformation ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/crypto/crypto.c (ffffffff813a8575)
Location: fs/crypto/fscrypt_private.h:152
Inline: True
Inline callers:
  - fs/crypto/crypto.c:fscrypt_generate_iv
```
```
In fs/crypto/fname.c (ffffffff813a9315)
Location: fs/crypto/fscrypt_private.h:152
Inline: True
Inline callers:
  - fs/crypto/fname.c:fscrypt_fname_encrypted_size
```
```
In fs/crypto/inline_crypt.c (ffffffff813ae602)
Location: fs/crypto/fscrypt_private.h:152
Inline: True
Inline callers:
  - fs/crypto/inline_crypt.c:fscrypt_select_encryption_impl
  - fs/crypto/inline_crypt.c:fscrypt_get_dun_bytes
Direct callers:
  - fs/crypto/inline_crypt.c:fscrypt_select_encryption_impl
  - fs/crypto/inline_crypt.c:fscrypt_get_dun_bytes
```
**Symbols:**

```
ffffffff813ae3d0-ffffffff813ae3d2: fscrypt_policy_flags.part.0 (STB_LOCAL)
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
In fs/crypto/crypto.c (ffffffff813f7cb5)
Location: fs/crypto/fscrypt_private.h:152
Inline: True
Inline callers:
  - fs/crypto/crypto.c:fscrypt_generate_iv
```
```
In fs/crypto/fname.c (ffffffff813f8b9f)
Location: fs/crypto/fscrypt_private.h:152
Inline: True
Inline callers:
  - fs/crypto/fname.c:fscrypt_setup_filename
```
```
In fs/crypto/inline_crypt.c (ffffffff813fe188)
Location: fs/crypto/fscrypt_private.h:152
Inline: True
Inline callers:
  - fs/crypto/inline_crypt.c:fscrypt_select_encryption_impl
  - fs/crypto/inline_crypt.c:fscrypt_get_dun_bytes
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
In fs/crypto/crypto.c (ffffffff8146a995)
Location: fs/crypto/fscrypt_private.h:157
Inline: True
Inline callers:
  - fs/crypto/crypto.c:fscrypt_generate_iv
```
```
In fs/crypto/fname.c (ffffffff8146b93d)
Location: fs/crypto/fscrypt_private.h:157
Inline: True
Inline callers:
  - fs/crypto/fname.c:fscrypt_setup_filename
```
```
In fs/crypto/inline_crypt.c (ffffffff81471c8d)
Location: fs/crypto/fscrypt_private.h:157
Inline: True
Inline callers:
  - fs/crypto/inline_crypt.c:fscrypt_select_encryption_impl
  - fs/crypto/inline_crypt.c:fscrypt_get_dun_bytes
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
In fs/crypto/crypto.c (ffffffff814fb945)
Location: fs/crypto/fscrypt_private.h:157
Inline: True
Inline callers:
  - fs/crypto/crypto.c:fscrypt_generate_iv
```
```
In fs/crypto/fname.c (ffffffff814fcc1d)
Location: fs/crypto/fscrypt_private.h:157
Inline: True
Inline callers:
  - fs/crypto/fname.c:fscrypt_setup_filename
```
```
In fs/crypto/inline_crypt.c (ffffffff815038a4)
Location: fs/crypto/fscrypt_private.h:157
Inline: True
Inline callers:
  - fs/crypto/inline_crypt.c:fscrypt_select_encryption_impl
  - fs/crypto/inline_crypt.c:fscrypt_get_dun_bytes
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
In fs/crypto/crypto.c (ffffffff81532c65)
Location: fs/crypto/fscrypt_private.h:157
Inline: True
Inline callers:
  - fs/crypto/crypto.c:fscrypt_generate_iv
```
```
In fs/crypto/fname.c (ffffffff8153419d)
Location: fs/crypto/fscrypt_private.h:157
Inline: True
Inline callers:
  - fs/crypto/fname.c:fscrypt_setup_filename
```
```
In fs/crypto/inline_crypt.c (ffffffff8153b154)
Location: fs/crypto/fscrypt_private.h:157
Inline: True
Inline callers:
  - fs/crypto/inline_crypt.c:fscrypt_select_encryption_impl
  - fs/crypto/inline_crypt.c:fscrypt_get_dun_bytes
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
In fs/crypto/crypto.c (ffffffff81567b65)
Location: fs/crypto/fscrypt_private.h:158
Inline: True
Inline callers:
  - fs/crypto/crypto.c:fscrypt_generate_iv
```
```
In fs/crypto/fname.c (ffffffff8156912d)
Location: fs/crypto/fscrypt_private.h:158
Inline: True
Inline callers:
  - fs/crypto/fname.c:fscrypt_setup_filename
```
```
In fs/crypto/inline_crypt.c (ffffffff815703d4)
Location: fs/crypto/fscrypt_private.h:158
Inline: True
Inline callers:
  - fs/crypto/inline_crypt.c:fscrypt_select_encryption_impl
  - fs/crypto/inline_crypt.c:fscrypt_get_dun_bytes
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
In fs/crypto/crypto.c (ffff80001040ae0c)
Location: fs/crypto/fscrypt_private.h:128
Inline: True
Inline callers:
  - fs/crypto/crypto.c:fscrypt_generate_iv
```
```
In fs/crypto/fname.c (ffff80001040bd44)
Location: fs/crypto/fscrypt_private.h:128
Inline: True
Inline callers:
  - fs/crypto/fname.c:fscrypt_fname_encrypted_size
```
```
In fs/crypto/keysetup.c (ffff80001040e6fc)
Location: fs/crypto/fscrypt_private.h:128
Inline: True
Inline callers:
  - fs/crypto/keysetup.c:put_crypt_info
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
In fs/crypto/crypto.c (c05d7f90)
Location: fs/crypto/fscrypt_private.h:128
Inline: True
Inline callers:
  - fs/crypto/crypto.c:fscrypt_generate_iv
```
```
In fs/crypto/fname.c (c05d8e80)
Location: fs/crypto/fscrypt_private.h:128
Inline: True
Inline callers:
  - fs/crypto/fname.c:fscrypt_fname_encrypted_size
```
```
In fs/crypto/keysetup.c (c05db1e4)
Location: fs/crypto/fscrypt_private.h:128
Inline: True
Inline callers:
  - fs/crypto/keysetup.c:put_crypt_info
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
In fs/crypto/crypto.c (c0000000005177bc)
Location: fs/crypto/fscrypt_private.h:128
Inline: True
Inline callers:
  - fs/crypto/crypto.c:fscrypt_generate_iv
```
```
In fs/crypto/fname.c (c000000000518a8c)
Location: fs/crypto/fscrypt_private.h:128
Inline: True
```
```
In fs/crypto/keysetup.c (c00000000051bcdc)
Location: fs/crypto/fscrypt_private.h:128
Inline: True
Inline callers:
  - fs/crypto/keysetup.c:put_crypt_info
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
In fs/crypto/crypto.c (ffffffe0002b4b48)
Location: fs/crypto/fscrypt_private.h:128
Inline: True
Inline callers:
  - fs/crypto/crypto.c:fscrypt_generate_iv
```
```
In fs/crypto/fname.c (ffffffe0002b57b6)
Location: fs/crypto/fscrypt_private.h:128
Inline: True
```
```
In fs/crypto/keysetup.c (ffffffe0002b77b6)
Location: fs/crypto/fscrypt_private.h:128
Inline: True
Inline callers:
  - fs/crypto/keysetup.c:put_crypt_info
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
In fs/crypto/crypto.c (ffffffff81342c08)
Location: fs/crypto/fscrypt_private.h:128
Inline: True
Inline callers:
  - fs/crypto/crypto.c:fscrypt_generate_iv
```
```
In fs/crypto/fname.c (ffffffff813438ed)
Location: fs/crypto/fscrypt_private.h:128
Inline: True
```
```
In fs/crypto/keysetup.c (ffffffff81345c81)
Location: fs/crypto/fscrypt_private.h:128
Inline: True
Inline callers:
  - fs/crypto/keysetup.c:put_crypt_info
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
In fs/crypto/crypto.c (ffffffff813338e8)
Location: fs/crypto/fscrypt_private.h:128
Inline: True
Inline callers:
  - fs/crypto/crypto.c:fscrypt_generate_iv
```
```
In fs/crypto/fname.c (ffffffff813345cd)
Location: fs/crypto/fscrypt_private.h:128
Inline: True
```
```
In fs/crypto/keysetup.c (ffffffff81336961)
Location: fs/crypto/fscrypt_private.h:128
Inline: True
Inline callers:
  - fs/crypto/keysetup.c:put_crypt_info
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
In fs/crypto/crypto.c (ffffffff813406d8)
Location: fs/crypto/fscrypt_private.h:128
Inline: True
Inline callers:
  - fs/crypto/crypto.c:fscrypt_generate_iv
```
```
In fs/crypto/fname.c (ffffffff813413bd)
Location: fs/crypto/fscrypt_private.h:128
Inline: True
```
```
In fs/crypto/keysetup.c (ffffffff81343751)
Location: fs/crypto/fscrypt_private.h:128
Inline: True
Inline callers:
  - fs/crypto/keysetup.c:put_crypt_info
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
In fs/crypto/crypto.c (ffffffff813539d8)
Location: fs/crypto/fscrypt_private.h:128
Inline: True
Inline callers:
  - fs/crypto/crypto.c:fscrypt_generate_iv
```
```
In fs/crypto/fname.c (ffffffff813546bd)
Location: fs/crypto/fscrypt_private.h:128
Inline: True
```
```
In fs/crypto/keysetup.c (ffffffff813569ef)
Location: fs/crypto/fscrypt_private.h:128
Inline: True
Inline callers:
  - fs/crypto/keysetup.c:put_crypt_info
```
</details>
</li>
</ul>

## Differences
