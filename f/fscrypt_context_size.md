# Function: <code>fscrypt_context_size</code>

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
<summary>In <code>5.4</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/crypto/policy.c (ffffffff8134eb7b)
Location: fs/crypto/fscrypt_private.h:65
Inline: True
Inline callers:
  - fs/crypto/policy.c:fscrypt_policy_from_context
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
In fs/crypto/keysetup.c (ffffffff81393b23)
Location: fs/crypto/fscrypt_private.h:66
Inline: True
Inline callers:
  - fs/crypto/keysetup.c:fscrypt_get_encryption_info
```
```
In fs/crypto/policy.c (ffffffff81394c68)
Location: fs/crypto/fscrypt_private.h:66
Inline: True
Inline callers:
  - fs/crypto/policy.c:fscrypt_ioctl_get_nonce
  - fs/crypto/policy.c:fscrypt_policy_from_context
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
In fs/crypto/policy.c (ffffffff813a5f58)
Location: fs/crypto/fscrypt_private.h:70
Inline: True
Inline callers:
  - fs/crypto/policy.c:fscrypt_ioctl_get_nonce
  - fs/crypto/policy.c:fscrypt_policy_from_context
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
In fs/crypto/policy.c (ffffffff813acfe8)
Location: fs/crypto/fscrypt_private.h:70
Inline: True
Inline callers:
  - fs/crypto/policy.c:fscrypt_ioctl_get_nonce
  - fs/crypto/policy.c:fscrypt_policy_from_context
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
In fs/crypto/policy.c (ffffffff813fc958)
Location: fs/crypto/fscrypt_private.h:70
Inline: True
Inline callers:
  - fs/crypto/policy.c:fscrypt_ioctl_get_nonce
  - fs/crypto/policy.c:fscrypt_policy_from_context
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
In fs/crypto/policy.c (ffffffff8146fe9f)
Location: fs/crypto/fscrypt_private.h:75
Inline: True
Inline callers:
  - fs/crypto/policy.c:fscrypt_ioctl_get_nonce
  - fs/crypto/policy.c:fscrypt_policy_from_context
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
In fs/crypto/policy.c (ffffffff815016bf)
Location: fs/crypto/fscrypt_private.h:75
Inline: True
Inline callers:
  - fs/crypto/policy.c:fscrypt_ioctl_get_nonce
  - fs/crypto/policy.c:fscrypt_policy_from_context
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
In fs/crypto/policy.c (ffffffff81538d52)
Location: fs/crypto/fscrypt_private.h:75
Inline: True
Inline callers:
  - fs/crypto/policy.c:fscrypt_ioctl_get_nonce
  - fs/crypto/policy.c:fscrypt_policy_from_context
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
In fs/crypto/policy.c (ffffffff8156e142)
Location: fs/crypto/fscrypt_private.h:76
Inline: True
Inline callers:
  - fs/crypto/policy.c:fscrypt_ioctl_get_nonce
  - fs/crypto/policy.c:fscrypt_policy_from_context
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/crypto/policy.c (ffff800010410148)
Location: fs/crypto/fscrypt_private.h:65
Inline: True
Inline callers:
  - fs/crypto/policy.c:fscrypt_policy_from_context
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/crypto/policy.c (c05dc9f4)
Location: fs/crypto/fscrypt_private.h:65
Inline: True
Inline callers:
  - fs/crypto/policy.c:fscrypt_policy_from_context
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/crypto/policy.c (c00000000051dc08)
Location: fs/crypto/fscrypt_private.h:65
Inline: True
Inline callers:
  - fs/crypto/policy.c:fscrypt_policy_from_context
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/crypto/policy.c (ffffffe0002b8b2c)
Location: fs/crypto/fscrypt_private.h:65
Inline: True
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/crypto/policy.c (ffffffff8134715b)
Location: fs/crypto/fscrypt_private.h:65
Inline: True
Inline callers:
  - fs/crypto/policy.c:fscrypt_policy_from_context
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/crypto/policy.c (ffffffff81337e3b)
Location: fs/crypto/fscrypt_private.h:65
Inline: True
Inline callers:
  - fs/crypto/policy.c:fscrypt_policy_from_context
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/crypto/policy.c (ffffffff81344c2b)
Location: fs/crypto/fscrypt_private.h:65
Inline: True
Inline callers:
  - fs/crypto/policy.c:fscrypt_policy_from_context
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/crypto/policy.c (ffffffff81357f0b)
Location: fs/crypto/fscrypt_private.h:65
Inline: True
Inline callers:
  - fs/crypto/policy.c:fscrypt_policy_from_context
```
</details>
</li>
</ul>

## Differences
