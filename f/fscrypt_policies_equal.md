# Function: <code>fscrypt_policies_equal</code>

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
<summary>In <code>5.4</code>: ✅</summary>

```c
bool fscrypt_policies_equal(const union fscrypt_policy *policy1, const union fscrypt_policy *policy2);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/crypto/policy.c (ffffffff8134ea30)
Location: fs/crypto/policy.c:23
Inline: False
Direct callers:
  - fs/crypto/policy.c:fscrypt_ioctl_set_policy
```
**Symbols:**

```
ffffffff8134ea30-ffffffff8134ea70: fscrypt_policies_equal (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
bool fscrypt_policies_equal(const union fscrypt_policy *policy1, const union fscrypt_policy *policy2);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/crypto/policy.c (ffffffff81394e10)
Location: fs/crypto/policy.c:26
Inline: False
Direct callers:
  - fs/crypto/policy.c:fscrypt_ioctl_set_policy
```
**Symbols:**

```
ffffffff81394e10-ffffffff81394e50: fscrypt_policies_equal (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
bool fscrypt_policies_equal(const union fscrypt_policy *policy1, const union fscrypt_policy *policy2);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/crypto/policy.c (ffffffff813a6100)
Location: fs/crypto/policy.c:26
Inline: False
Direct callers:
  - fs/crypto/policy.c:fscrypt_set_test_dummy_encryption
  - fs/crypto/policy.c:fscrypt_ioctl_set_policy
```
**Symbols:**

```
ffffffff813a6100-ffffffff813a6140: fscrypt_policies_equal (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
bool fscrypt_policies_equal(const union fscrypt_policy *policy1, const union fscrypt_policy *policy2);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/crypto/policy.c (ffffffff813ad180)
Location: fs/crypto/policy.c:26
Inline: False
Direct callers:
  - fs/crypto/policy.c:fscrypt_set_test_dummy_encryption
  - fs/crypto/policy.c:fscrypt_ioctl_set_policy
```
**Symbols:**

```
ffffffff813ad180-ffffffff813ad1bc: fscrypt_policies_equal (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
bool fscrypt_policies_equal(const union fscrypt_policy *policy1, const union fscrypt_policy *policy2);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/crypto/policy.c (ffffffff813fcaf0)
Location: fs/crypto/policy.c:26
Inline: False
Direct callers:
  - fs/crypto/policy.c:fscrypt_set_test_dummy_encryption
  - fs/crypto/policy.c:fscrypt_ioctl_set_policy
```
**Symbols:**

```
ffffffff813fcaf0-ffffffff813fcb2c: fscrypt_policies_equal (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
bool fscrypt_policies_equal(const union fscrypt_policy *policy1, const union fscrypt_policy *policy2);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/crypto/policy.c (ffffffff81470087)
Location: fs/crypto/policy.c:27
Inline: True
Inline callers:
  - fs/crypto/policy.c:fscrypt_dummy_policies_equal
Direct callers:
  - fs/crypto/policy.c:fscrypt_parse_test_dummy_encryption
  - fs/crypto/policy.c:fscrypt_has_permitted_context
  - fs/crypto/policy.c:fscrypt_ioctl_set_policy
```
**Symbols:**

```
ffffffff814700f0-ffffffff8147013e: fscrypt_policies_equal (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
bool fscrypt_policies_equal(const union fscrypt_policy *policy1, const union fscrypt_policy *policy2);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/crypto/policy.c (ffffffff81501aa7)
Location: fs/crypto/policy.c:27
Inline: True
Inline callers:
  - fs/crypto/policy.c:fscrypt_dummy_policies_equal
Direct callers:
  - fs/crypto/policy.c:fscrypt_parse_test_dummy_encryption
  - fs/crypto/policy.c:fscrypt_has_permitted_context
  - fs/crypto/policy.c:fscrypt_ioctl_set_policy
```
**Symbols:**

```
ffffffff81501b20-ffffffff81501b6e: fscrypt_policies_equal (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
bool fscrypt_policies_equal(const union fscrypt_policy *policy1, const union fscrypt_policy *policy2);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/crypto/policy.c (ffffffff81539120)
Location: fs/crypto/policy.c:27
Inline: False
Direct callers:
  - fs/crypto/keysetup.c:setup_file_encryption_key
  - fs/crypto/policy.c:fscrypt_dummy_policies_equal
  - fs/crypto/policy.c:fscrypt_parse_test_dummy_encryption
  - fs/crypto/policy.c:fscrypt_has_permitted_context
  - fs/crypto/policy.c:fscrypt_ioctl_set_policy
```
**Symbols:**

```
ffffffff81539120-ffffffff8153916e: fscrypt_policies_equal (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
bool fscrypt_policies_equal(const union fscrypt_policy *policy1, const union fscrypt_policy *policy2);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/crypto/policy.c (ffffffff8156e2c0)
Location: fs/crypto/policy.c:27
Inline: False
Direct callers:
  - fs/crypto/keysetup.c:setup_file_encryption_key
  - fs/crypto/policy.c:fscrypt_dummy_policies_equal
  - fs/crypto/policy.c:fscrypt_parse_test_dummy_encryption
  - fs/crypto/policy.c:fscrypt_has_permitted_context
  - fs/crypto/policy.c:fscrypt_ioctl_set_policy
```
**Symbols:**

```
ffffffff8156e2c0-ffffffff8156e30e: fscrypt_policies_equal (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: ✅</summary>

```c
bool fscrypt_policies_equal(const union fscrypt_policy *policy1, const union fscrypt_policy *policy2);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/crypto/policy.c (ffff80001040ff60)
Location: fs/crypto/policy.c:23
Inline: False
Direct callers:
  - fs/crypto/policy.c:fscrypt_ioctl_set_policy
```
**Symbols:**

```
ffff80001040ff60-ffff80001040ffd0: fscrypt_policies_equal (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
bool fscrypt_policies_equal(const union fscrypt_policy *policy1, const union fscrypt_policy *policy2);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/crypto/policy.c (c05dc828)
Location: fs/crypto/policy.c:23
Inline: False
Direct callers:
  - fs/crypto/policy.c:fscrypt_ioctl_set_policy
```
**Symbols:**

```
c05dc828-c05dc87c: fscrypt_policies_equal (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
bool fscrypt_policies_equal(const union fscrypt_policy *policy1, const union fscrypt_policy *policy2);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/crypto/policy.c (c00000000051d940)
Location: fs/crypto/policy.c:23
Inline: False
Direct callers:
  - fs/crypto/policy.c:fscrypt_ioctl_set_policy
```
**Symbols:**

```
c00000000051d940-c00000000051d9e4: fscrypt_policies_equal (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
bool fscrypt_policies_equal(const union fscrypt_policy *policy1, const union fscrypt_policy *policy2);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/crypto/policy.c (ffffffe0002b897c)
Location: fs/crypto/policy.c:23
Inline: False
Direct callers:
  - fs/crypto/policy.c:fscrypt_ioctl_set_policy
```
**Symbols:**

```
ffffffe0002b897c-ffffffe0002b89e0: fscrypt_policies_equal (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: ✅</summary>

```c
bool fscrypt_policies_equal(const union fscrypt_policy *policy1, const union fscrypt_policy *policy2);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/crypto/policy.c (ffffffff81347010)
Location: fs/crypto/policy.c:23
Inline: False
Direct callers:
  - fs/crypto/policy.c:fscrypt_ioctl_set_policy
```
**Symbols:**

```
ffffffff81347010-ffffffff81347050: fscrypt_policies_equal (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
bool fscrypt_policies_equal(const union fscrypt_policy *policy1, const union fscrypt_policy *policy2);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/crypto/policy.c (ffffffff81337cf0)
Location: fs/crypto/policy.c:23
Inline: False
Direct callers:
  - fs/crypto/policy.c:fscrypt_ioctl_set_policy
```
**Symbols:**

```
ffffffff81337cf0-ffffffff81337d30: fscrypt_policies_equal (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
bool fscrypt_policies_equal(const union fscrypt_policy *policy1, const union fscrypt_policy *policy2);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/crypto/policy.c (ffffffff81344ae0)
Location: fs/crypto/policy.c:23
Inline: False
Direct callers:
  - fs/crypto/policy.c:fscrypt_ioctl_set_policy
```
**Symbols:**

```
ffffffff81344ae0-ffffffff81344b20: fscrypt_policies_equal (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
bool fscrypt_policies_equal(const union fscrypt_policy *policy1, const union fscrypt_policy *policy2);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/crypto/policy.c (ffffffff81357dc0)
Location: fs/crypto/policy.c:23
Inline: False
Direct callers:
  - fs/crypto/policy.c:fscrypt_ioctl_set_policy
```
**Symbols:**

```
ffffffff81357dc0-ffffffff81357e00: fscrypt_policies_equal (STB_GLOBAL)
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
