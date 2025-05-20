# Function: <code>fscrypt_supported_policy</code>

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
<summary>In <code>5.4</code>: Selective Inline, Transformation ⚠️</summary>

```c
bool fscrypt_supported_policy(const union fscrypt_policy *policy_u, const struct inode *inode);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/crypto/policy.c (ffffffff8134ea8d)
Location: fs/crypto/policy.c:42
Inline: True
Direct callers:
  - fs/crypto/keysetup.c:fscrypt_get_encryption_info
  - fs/crypto/policy.c:fscrypt_ioctl_set_policy
```
**Symbols:**

```
ffffffff8134f162-ffffffff8134f1fd: fscrypt_supported_policy.cold (STB_LOCAL)
ffffffff8134ea70-ffffffff8134eb44: fscrypt_supported_policy (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
bool fscrypt_supported_policy(const union fscrypt_policy *policy_u, const struct inode *inode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/crypto/policy.c (0)
Location: fs/crypto/policy.c:207
Inline: False
Direct callers:
  - fs/crypto/keysetup.c:fscrypt_get_encryption_info
  - fs/crypto/policy.c:set_encryption_policy
```
**Symbols:**

```
ffffffff81395689-ffffffff81395729: fscrypt_supported_policy.cold (STB_LOCAL)
ffffffff81394e50-ffffffff81394eee: fscrypt_supported_policy (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
bool fscrypt_supported_policy(const union fscrypt_policy *policy_u, const struct inode *inode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/crypto/policy.c (0)
Location: fs/crypto/policy.c:237
Inline: False
Direct callers:
  - fs/crypto/keysetup.c:fscrypt_get_encryption_info
  - fs/crypto/policy.c:set_encryption_policy
```
**Symbols:**

```
ffffffff81beb19a-ffffffff81beb23a: fscrypt_supported_policy.cold (STB_LOCAL)
ffffffff813a6300-ffffffff813a639e: fscrypt_supported_policy (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
bool fscrypt_supported_policy(const union fscrypt_policy *policy_u, const struct inode *inode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/crypto/policy.c (0)
Location: fs/crypto/policy.c:237
Inline: False
Direct callers:
  - fs/crypto/keysetup.c:fscrypt_get_encryption_info
  - fs/crypto/policy.c:set_encryption_policy
```
**Symbols:**

```
ffffffff81bdd1f3-ffffffff81bdd293: fscrypt_supported_policy.cold (STB_LOCAL)
ffffffff813ad380-ffffffff813ad41e: fscrypt_supported_policy (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
bool fscrypt_supported_policy(const union fscrypt_policy *policy_u, const struct inode *inode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/crypto/policy.c (0)
Location: fs/crypto/policy.c:237
Inline: False
Direct callers:
  - fs/crypto/keysetup.c:fscrypt_get_encryption_info
  - fs/crypto/policy.c:set_encryption_policy
```
**Symbols:**

```
ffffffff81cc68ed-ffffffff81cc6991: fscrypt_supported_policy.cold (STB_LOCAL)
ffffffff813fccf0-ffffffff813fcd8e: fscrypt_supported_policy (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
bool fscrypt_supported_policy(const union fscrypt_policy *policy_u, const struct inode *inode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/crypto/policy.c (0)
Location: fs/crypto/policy.c:258
Inline: False
Direct callers:
  - fs/crypto/keysetup.c:fscrypt_get_encryption_info
  - fs/crypto/policy.c:set_encryption_policy
```
**Symbols:**

```
ffffffff81e78d2e-ffffffff81e78dbf: fscrypt_supported_policy.cold (STB_LOCAL)
ffffffff81470370-ffffffff81470451: fscrypt_supported_policy (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
bool fscrypt_supported_policy(const union fscrypt_policy *policy_u, const struct inode *inode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/crypto/policy.c (ffffffff81501d30)
Location: fs/crypto/policy.c:278
Inline: False
Direct callers:
  - fs/crypto/keysetup.c:fscrypt_get_encryption_info
  - fs/crypto/policy.c:set_encryption_policy
```
**Symbols:**

```
ffffffff81501d30-ffffffff81501e61: fscrypt_supported_policy (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
bool fscrypt_supported_policy(const union fscrypt_policy *policy_u, const struct inode *inode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/crypto/policy.c (ffffffff815393d0)
Location: fs/crypto/policy.c:277
Inline: False
Direct callers:
  - fs/crypto/keysetup.c:fscrypt_get_encryption_info
  - fs/crypto/policy.c:set_encryption_policy
```
**Symbols:**

```
ffffffff815393d0-ffffffff8153950e: fscrypt_supported_policy (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
bool fscrypt_supported_policy(const union fscrypt_policy *policy_u, const struct inode *inode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/crypto/policy.c (ffffffff8156e5c0)
Location: fs/crypto/policy.c:302
Inline: False
Direct callers:
  - fs/crypto/keysetup.c:fscrypt_get_encryption_info
  - fs/crypto/policy.c:set_encryption_policy
```
**Symbols:**

```
ffffffff8156e5c0-ffffffff8156e6fe: fscrypt_supported_policy (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Selective Inline ⚠️</summary>

```c
bool fscrypt_supported_policy(const union fscrypt_policy *policy_u, const struct inode *inode);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/crypto/policy.c (ffff80001040ffd0)
Location: fs/crypto/policy.c:42
Inline: True
Direct callers:
  - fs/crypto/keysetup.c:fscrypt_get_encryption_info
  - fs/crypto/policy.c:fscrypt_ioctl_set_policy
```
**Symbols:**

```
ffff80001040ffd0-ffff80001041010c: fscrypt_supported_policy (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
bool fscrypt_supported_policy(const union fscrypt_policy *policy_u, const struct inode *inode);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/crypto/policy.c (c05dc87c)
Location: fs/crypto/policy.c:42
Inline: True
Direct callers:
  - fs/crypto/keysetup.c:fscrypt_get_encryption_info
  - fs/crypto/policy.c:fscrypt_ioctl_set_policy
```
**Symbols:**

```
c05dc87c-c05dc9b8: fscrypt_supported_policy (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
bool fscrypt_supported_policy(const union fscrypt_policy *policy_u, const struct inode *inode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/crypto/policy.c (c00000000051d9f0)
Location: fs/crypto/policy.c:42
Inline: False
Direct callers:
  - fs/crypto/keysetup.c:fscrypt_get_encryption_info
  - fs/crypto/policy.c:fscrypt_ioctl_set_policy
```
**Symbols:**

```
c00000000051d9f0-c00000000051dbd8: fscrypt_supported_policy (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
bool fscrypt_supported_policy(const union fscrypt_policy *policy_u, const struct inode *inode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/crypto/policy.c (ffffffe0002b89e0)
Location: fs/crypto/policy.c:42
Inline: False
Direct callers:
  - fs/crypto/keysetup.c:fscrypt_get_encryption_info
  - fs/crypto/policy.c:fscrypt_ioctl_set_policy
```
**Symbols:**

```
ffffffe0002b89e0-ffffffe0002b8af8: fscrypt_supported_policy (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Selective Inline, Transformation ⚠️</summary>

```c
bool fscrypt_supported_policy(const union fscrypt_policy *policy_u, const struct inode *inode);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/crypto/policy.c (ffffffff8134706d)
Location: fs/crypto/policy.c:42
Inline: True
Direct callers:
  - fs/crypto/keysetup.c:fscrypt_get_encryption_info
  - fs/crypto/policy.c:fscrypt_ioctl_set_policy
```
**Symbols:**

```
ffffffff81347742-ffffffff813477dd: fscrypt_supported_policy.cold (STB_LOCAL)
ffffffff81347050-ffffffff81347124: fscrypt_supported_policy (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline, Transformation ⚠️</summary>

```c
bool fscrypt_supported_policy(const union fscrypt_policy *policy_u, const struct inode *inode);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/crypto/policy.c (ffffffff81337d4d)
Location: fs/crypto/policy.c:42
Inline: True
Direct callers:
  - fs/crypto/keysetup.c:fscrypt_get_encryption_info
  - fs/crypto/policy.c:fscrypt_ioctl_set_policy
```
**Symbols:**

```
ffffffff81338422-ffffffff813384bd: fscrypt_supported_policy.cold (STB_LOCAL)
ffffffff81337d30-ffffffff81337e04: fscrypt_supported_policy (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline, Transformation ⚠️</summary>

```c
bool fscrypt_supported_policy(const union fscrypt_policy *policy_u, const struct inode *inode);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/crypto/policy.c (ffffffff81344b3d)
Location: fs/crypto/policy.c:42
Inline: True
Direct callers:
  - fs/crypto/keysetup.c:fscrypt_get_encryption_info
  - fs/crypto/policy.c:fscrypt_ioctl_set_policy
```
**Symbols:**

```
ffffffff81345212-ffffffff813452ad: fscrypt_supported_policy.cold (STB_LOCAL)
ffffffff81344b20-ffffffff81344bf4: fscrypt_supported_policy (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline, Transformation ⚠️</summary>

```c
bool fscrypt_supported_policy(const union fscrypt_policy *policy_u, const struct inode *inode);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/crypto/policy.c (ffffffff81357e1d)
Location: fs/crypto/policy.c:42
Inline: True
Direct callers:
  - fs/crypto/keysetup.c:fscrypt_get_encryption_info
  - fs/crypto/policy.c:fscrypt_ioctl_set_policy
```
**Symbols:**

```
ffffffff813584f2-ffffffff8135858d: fscrypt_supported_policy.cold (STB_LOCAL)
ffffffff81357e00-ffffffff81357ed4: fscrypt_supported_policy (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>5.4</code> and <code>5.8</code> ✅
</li>
<li>
No changes between <code>5.8</code> and <code>5.11</code> ✅
</li>
<li>
No changes between <code>5.11</code> and <code>5.13</code> ✅
</li>
<li>
No changes between <code>5.13</code> and <code>5.15</code> ✅
</li>
<li>
No changes between <code>5.15</code> and <code>5.19</code> ✅
</li>
<li>
No changes between <code>5.19</code> and <code>6.2</code> ✅
</li>
<li>
No changes between <code>6.2</code> and <code>6.5</code> ✅
</li>
<li>
No changes between <code>6.5</code> and <code>6.8</code> ✅
</li>
</ul>
<b>Arch</b>
<ul>
<li>
No changes between <code>amd64</code> and <code>arm64</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>armhf</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>ppc64el</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>riscv64</code> ✅
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
No changes between <code>generic</code> and <code>aws</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>azure</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>gcp</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>lowlatency</code> ✅
</li>
</ul>
