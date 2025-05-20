# Function: <code>fscrypt_is_direct_key_policy</code>

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
Location: fs/crypto/fscrypt_private.h:140
Inline: True
Inline callers:
  - fs/crypto/crypto.c:fscrypt_generate_iv
```
```
In fs/crypto/keysetup.c (ffffffff8134d6a1)
Location: fs/crypto/fscrypt_private.h:140
Inline: True
Inline callers:
  - fs/crypto/keysetup.c:put_crypt_info
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
In fs/crypto/crypto.c (ffff80001040ae0c)
Location: fs/crypto/fscrypt_private.h:140
Inline: True
Inline callers:
  - fs/crypto/crypto.c:fscrypt_generate_iv
```
```
In fs/crypto/keysetup.c (ffff80001040e6fc)
Location: fs/crypto/fscrypt_private.h:140
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
Location: fs/crypto/fscrypt_private.h:140
Inline: True
Inline callers:
  - fs/crypto/crypto.c:fscrypt_generate_iv
```
```
In fs/crypto/keysetup.c (c05db1e4)
Location: fs/crypto/fscrypt_private.h:140
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
Location: fs/crypto/fscrypt_private.h:140
Inline: True
Inline callers:
  - fs/crypto/crypto.c:fscrypt_generate_iv
```
```
In fs/crypto/keysetup.c (c00000000051bcdc)
Location: fs/crypto/fscrypt_private.h:140
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
Location: fs/crypto/fscrypt_private.h:140
Inline: True
Inline callers:
  - fs/crypto/crypto.c:fscrypt_generate_iv
```
```
In fs/crypto/keysetup.c (ffffffe0002b77b6)
Location: fs/crypto/fscrypt_private.h:140
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
Location: fs/crypto/fscrypt_private.h:140
Inline: True
Inline callers:
  - fs/crypto/crypto.c:fscrypt_generate_iv
```
```
In fs/crypto/keysetup.c (ffffffff81345c81)
Location: fs/crypto/fscrypt_private.h:140
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
Location: fs/crypto/fscrypt_private.h:140
Inline: True
Inline callers:
  - fs/crypto/crypto.c:fscrypt_generate_iv
```
```
In fs/crypto/keysetup.c (ffffffff81336961)
Location: fs/crypto/fscrypt_private.h:140
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
Location: fs/crypto/fscrypt_private.h:140
Inline: True
Inline callers:
  - fs/crypto/crypto.c:fscrypt_generate_iv
```
```
In fs/crypto/keysetup.c (ffffffff81343751)
Location: fs/crypto/fscrypt_private.h:140
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
Location: fs/crypto/fscrypt_private.h:140
Inline: True
Inline callers:
  - fs/crypto/crypto.c:fscrypt_generate_iv
```
```
In fs/crypto/keysetup.c (ffffffff813569ef)
Location: fs/crypto/fscrypt_private.h:140
Inline: True
Inline callers:
  - fs/crypto/keysetup.c:put_crypt_info
```
</details>
</li>
</ul>

## Differences
