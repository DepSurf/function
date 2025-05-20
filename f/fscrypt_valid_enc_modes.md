# Function: <code>fscrypt_valid_enc_modes</code>

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
<details>
<summary>In <code>4.13</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/crypto/policy.c (ffffffff812ad3f8)
Location: include/linux/fscrypt_common.h:97
Inline: True
Inline callers:
  - fs/crypto/policy.c:fscrypt_ioctl_set_policy
```
```
In fs/crypto/keyinfo.c (ffffffff812adcac)
Location: include/linux/fscrypt_common.h:97
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
In fs/crypto/keyinfo.c (ffffffff812d1186)
Location: include/linux/fscrypt.h:100
Inline: True
```
```
In fs/crypto/policy.c (ffffffff812d1727)
Location: include/linux/fscrypt.h:100
Inline: True
Inline callers:
  - fs/crypto/policy.c:fscrypt_ioctl_set_policy
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
In fs/crypto/keyinfo.c (ffffffff812fbb32)
Location: fs/crypto/fscrypt_private.h:75
Inline: True
```
```
In fs/crypto/policy.c (ffffffff812fc221)
Location: fs/crypto/fscrypt_private.h:75
Inline: True
Inline callers:
  - fs/crypto/policy.c:fscrypt_ioctl_set_policy
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
In fs/crypto/keyinfo.c (ffffffff813112d1)
Location: fs/crypto/fscrypt_private.h:100
Inline: True
```
```
In fs/crypto/policy.c (ffffffff81311a91)
Location: fs/crypto/fscrypt_private.h:100
Inline: True
Inline callers:
  - fs/crypto/policy.c:fscrypt_ioctl_set_policy
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
In fs/crypto/keyinfo.c (ffffffff813387f8)
Location: fs/crypto/fscrypt_private.h:98
Inline: True
```
```
In fs/crypto/policy.c (ffffffff81339006)
Location: fs/crypto/fscrypt_private.h:98
Inline: True
Inline callers:
  - fs/crypto/policy.c:fscrypt_ioctl_set_policy
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/crypto/policy.c (ffffffff8134ea91)
Location: fs/crypto/fscrypt_private.h:214
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/crypto/policy.c (ffffffff81394e7a)
Location: fs/crypto/policy.c:35
Inline: True
Inline callers:
  - fs/crypto/policy.c:fscrypt_supported_policy
  - fs/crypto/policy.c:fscrypt_supported_policy
  - fs/crypto/policy.c:fscrypt_supported_v2_policy
  - fs/crypto/policy.c:fscrypt_supported_v2_policy
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
In fs/crypto/policy.c (ffffffff813a632a)
Location: fs/crypto/policy.c:43
Inline: True
Inline callers:
  - fs/crypto/policy.c:fscrypt_supported_policy
  - fs/crypto/policy.c:fscrypt_supported_policy
  - fs/crypto/policy.c:fscrypt_supported_v2_policy
  - fs/crypto/policy.c:fscrypt_supported_v2_policy
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
In fs/crypto/policy.c (ffffffff813ad3aa)
Location: fs/crypto/policy.c:43
Inline: True
Inline callers:
  - fs/crypto/policy.c:fscrypt_supported_policy
  - fs/crypto/policy.c:fscrypt_supported_policy
  - fs/crypto/policy.c:fscrypt_supported_v2_policy
  - fs/crypto/policy.c:fscrypt_supported_v2_policy
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
In fs/crypto/policy.c (ffffffff813fcd1a)
Location: fs/crypto/policy.c:43
Inline: True
Inline callers:
  - fs/crypto/policy.c:fscrypt_supported_policy
  - fs/crypto/policy.c:fscrypt_supported_policy
  - fs/crypto/policy.c:fscrypt_supported_v2_policy
  - fs/crypto/policy.c:fscrypt_supported_v2_policy
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
In fs/crypto/policy.c (ffffffff814703ba)
Location: fs/crypto/policy.c:64
Inline: True
Inline callers:
  - fs/crypto/policy.c:fscrypt_supported_policy
  - fs/crypto/policy.c:fscrypt_supported_policy
  - fs/crypto/policy.c:fscrypt_supported_v2_policy
  - fs/crypto/policy.c:fscrypt_supported_v2_policy
```
</details>
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
<summary>In <code>arm64</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/crypto/policy.c (ffff80001041000c)
Location: fs/crypto/fscrypt_private.h:214
Inline: True
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
In fs/crypto/policy.c (c05dc8b4)
Location: fs/crypto/fscrypt_private.h:214
Inline: True
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
In fs/crypto/policy.c (c00000000051dac4)
Location: fs/crypto/fscrypt_private.h:214
Inline: True
Inline callers:
  - fs/crypto/policy.c:fscrypt_supported_policy
  - fs/crypto/policy.c:fscrypt_supported_policy
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
In fs/crypto/policy.c (ffffffe0002b8a7a)
Location: fs/crypto/fscrypt_private.h:214
Inline: True
Inline callers:
  - fs/crypto/policy.c:fscrypt_supported_policy
  - fs/crypto/policy.c:fscrypt_supported_policy
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
In fs/crypto/policy.c (ffffffff81347071)
Location: fs/crypto/fscrypt_private.h:214
Inline: True
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
In fs/crypto/policy.c (ffffffff81337d51)
Location: fs/crypto/fscrypt_private.h:214
Inline: True
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
In fs/crypto/policy.c (ffffffff81344b41)
Location: fs/crypto/fscrypt_private.h:214
Inline: True
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
In fs/crypto/policy.c (ffffffff81357e21)
Location: fs/crypto/fscrypt_private.h:214
Inline: True
```
</details>
</li>
</ul>

## Differences
