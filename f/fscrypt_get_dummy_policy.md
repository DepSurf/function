# Function: <code>fscrypt_get_dummy_policy</code>

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
<summary>In <code>5.11</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/crypto/policy.c (ffffffff813a5de5)
Location: fs/crypto/policy.c:36
Inline: True
Inline callers:
  - fs/crypto/policy.c:fscrypt_show_test_dummy_encryption
  - fs/crypto/policy.c:fscrypt_policy_to_inherit
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
In fs/crypto/policy.c (ffffffff813ace75)
Location: fs/crypto/policy.c:36
Inline: True
Inline callers:
  - fs/crypto/policy.c:fscrypt_show_test_dummy_encryption
  - fs/crypto/policy.c:fscrypt_policy_to_inherit
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
In fs/crypto/policy.c (ffffffff813fc7e5)
Location: fs/crypto/policy.c:36
Inline: True
Inline callers:
  - fs/crypto/policy.c:fscrypt_show_test_dummy_encryption
  - fs/crypto/policy.c:fscrypt_policy_to_inherit
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
In fs/crypto/policy.c (ffffffff8146fce5)
Location: fs/crypto/policy.c:57
Inline: True
Inline callers:
  - fs/crypto/policy.c:fscrypt_show_test_dummy_encryption
  - fs/crypto/policy.c:fscrypt_policy_to_inherit
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
In fs/crypto/policy.c (ffffffff81501335)
Location: fs/crypto/policy.c:57
Inline: True
Inline callers:
  - fs/crypto/policy.c:fscrypt_show_test_dummy_encryption
  - fs/crypto/policy.c:fscrypt_policy_to_inherit
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
const union fscrypt_policy *fscrypt_get_dummy_policy(struct super_block *sb);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/crypto/policy.c (ffffffff815389c5)
Location: fs/crypto/policy.c:56
Inline: True
Inline callers:
  - fs/crypto/policy.c:fscrypt_show_test_dummy_encryption
  - fs/crypto/policy.c:fscrypt_policy_to_inherit
Direct callers:
  - fs/crypto/keysetup.c:setup_file_encryption_key
```
**Symbols:**

```
ffffffff81539390-ffffffff815393bf: fscrypt_get_dummy_policy (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
const union fscrypt_policy *fscrypt_get_dummy_policy(struct super_block *sb);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/crypto/policy.c (ffffffff8156db45)
Location: fs/crypto/policy.c:56
Inline: True
Inline callers:
  - fs/crypto/policy.c:fscrypt_show_test_dummy_encryption
  - fs/crypto/policy.c:fscrypt_policy_to_inherit
Direct callers:
  - fs/crypto/keysetup.c:setup_file_encryption_key
```
**Symbols:**

```
ffffffff8156e580-ffffffff8156e5af: fscrypt_get_dummy_policy (STB_GLOBAL)
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
<b>Regular</b>
<ul>
<li>
No changes between <code>6.5</code> and <code>6.8</code> ✅
</li>
</ul>
