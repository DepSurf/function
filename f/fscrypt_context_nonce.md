# Function: <code>fscrypt_context_nonce</code>

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
<details>
<summary>In <code>5.8</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/crypto/keysetup.c (ffffffff81393bab)
Location: fs/crypto/fscrypt_private.h:87
Inline: True
Inline callers:
  - fs/crypto/keysetup.c:fscrypt_get_encryption_info
```
```
In fs/crypto/policy.c (ffffffff81394c76)
Location: fs/crypto/fscrypt_private.h:87
Inline: True
Inline callers:
  - fs/crypto/policy.c:fscrypt_ioctl_get_nonce
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
In fs/crypto/keysetup.c (ffffffff813a54a1)
Location: fs/crypto/fscrypt_private.h:91
Inline: True
Inline callers:
  - fs/crypto/keysetup.c:fscrypt_get_encryption_info
```
```
In fs/crypto/policy.c (ffffffff813a5f66)
Location: fs/crypto/fscrypt_private.h:91
Inline: True
Inline callers:
  - fs/crypto/policy.c:fscrypt_ioctl_get_nonce
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
In fs/crypto/keysetup.c (ffffffff813ac581)
Location: fs/crypto/fscrypt_private.h:91
Inline: True
Inline callers:
  - fs/crypto/keysetup.c:fscrypt_get_encryption_info
```
```
In fs/crypto/policy.c (ffffffff813acff6)
Location: fs/crypto/fscrypt_private.h:91
Inline: True
Inline callers:
  - fs/crypto/policy.c:fscrypt_ioctl_get_nonce
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
In fs/crypto/keysetup.c (ffffffff813fbef1)
Location: fs/crypto/fscrypt_private.h:91
Inline: True
Inline callers:
  - fs/crypto/keysetup.c:fscrypt_get_encryption_info
```
```
In fs/crypto/policy.c (ffffffff813fc966)
Location: fs/crypto/fscrypt_private.h:91
Inline: True
Inline callers:
  - fs/crypto/policy.c:fscrypt_ioctl_get_nonce
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
In fs/crypto/keysetup.c (ffffffff8146f2fa)
Location: fs/crypto/fscrypt_private.h:96
Inline: True
Inline callers:
  - fs/crypto/keysetup.c:fscrypt_get_encryption_info
```
```
In fs/crypto/policy.c (ffffffff8146fead)
Location: fs/crypto/fscrypt_private.h:96
Inline: True
Inline callers:
  - fs/crypto/policy.c:fscrypt_ioctl_get_nonce
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
In fs/crypto/keysetup.c (ffffffff81500a12)
Location: fs/crypto/fscrypt_private.h:96
Inline: True
Inline callers:
  - fs/crypto/keysetup.c:fscrypt_get_encryption_info
```
```
In fs/crypto/policy.c (ffffffff815016cd)
Location: fs/crypto/fscrypt_private.h:96
Inline: True
Inline callers:
  - fs/crypto/policy.c:fscrypt_ioctl_get_nonce
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
In fs/crypto/keysetup.c (ffffffff815380a2)
Location: fs/crypto/fscrypt_private.h:96
Inline: True
Inline callers:
  - fs/crypto/keysetup.c:fscrypt_get_encryption_info
```
```
In fs/crypto/policy.c (ffffffff81538d84)
Location: fs/crypto/fscrypt_private.h:96
Inline: True
Inline callers:
  - fs/crypto/policy.c:fscrypt_ioctl_get_nonce
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
In fs/crypto/keysetup.c (ffffffff8156d1f2)
Location: fs/crypto/fscrypt_private.h:97
Inline: True
Inline callers:
  - fs/crypto/keysetup.c:fscrypt_get_encryption_info
```
```
In fs/crypto/policy.c (ffffffff8156e174)
Location: fs/crypto/fscrypt_private.h:97
Inline: True
Inline callers:
  - fs/crypto/policy.c:fscrypt_ioctl_get_nonce
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
