# Function: <code>fscrypt_supported_v2_policy</code>

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
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
bool fscrypt_supported_v2_policy(const struct fscrypt_policy_v2 *policy, const struct inode *inode);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/crypto/policy.c (0)
Location: fs/crypto/policy.c:142
Inline: False
Direct callers:
  - fs/crypto/policy.c:fscrypt_supported_policy
```
**Symbols:**

```
ffffffff81394cd0-ffffffff81394e05: fscrypt_supported_v2_policy (STB_LOCAL)
ffffffff813955c6-ffffffff81395689: fscrypt_supported_v2_policy.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
bool fscrypt_supported_v2_policy(const struct fscrypt_policy_v2 *policy, const struct inode *inode);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/crypto/policy.c (0)
Location: fs/crypto/policy.c:164
Inline: False
Direct callers:
  - fs/crypto/policy.c:fscrypt_supported_policy
```
**Symbols:**

```
ffffffff813a5fc0-ffffffff813a60f7: fscrypt_supported_v2_policy (STB_LOCAL)
ffffffff81beb0d7-ffffffff81beb19a: fscrypt_supported_v2_policy.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
bool fscrypt_supported_v2_policy(const struct fscrypt_policy_v2 *policy, const struct inode *inode);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/crypto/policy.c (0)
Location: fs/crypto/policy.c:164
Inline: False
Direct callers:
  - fs/crypto/policy.c:fscrypt_supported_policy
```
**Symbols:**

```
ffffffff813ad040-ffffffff813ad177: fscrypt_supported_v2_policy (STB_LOCAL)
ffffffff81bdd130-ffffffff81bdd1f3: fscrypt_supported_v2_policy.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
bool fscrypt_supported_v2_policy(const struct fscrypt_policy_v2 *policy, const struct inode *inode);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/crypto/policy.c (0)
Location: fs/crypto/policy.c:164
Inline: False
Direct callers:
  - fs/crypto/policy.c:fscrypt_supported_policy
```
**Symbols:**

```
ffffffff813fc9b0-ffffffff813fcae7: fscrypt_supported_v2_policy (STB_LOCAL)
ffffffff81cc6826-ffffffff81cc68ed: fscrypt_supported_v2_policy.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
bool fscrypt_supported_v2_policy(const struct fscrypt_policy_v2 *policy, const struct inode *inode);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/crypto/policy.c (0)
Location: fs/crypto/policy.c:185
Inline: False
Direct callers:
  - fs/crypto/policy.c:fscrypt_supported_policy
```
**Symbols:**

```
ffffffff8146ff10-ffffffff81470065: fscrypt_supported_v2_policy (STB_LOCAL)
ffffffff81e78c83-ffffffff81e78d2e: fscrypt_supported_v2_policy.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
bool fscrypt_supported_v2_policy(const struct fscrypt_policy_v2 *policy, const struct inode *inode);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/crypto/policy.c (ffffffff81501840)
Location: fs/crypto/policy.c:205
Inline: False
Direct callers:
  - fs/crypto/policy.c:fscrypt_supported_policy
```
**Symbols:**

```
ffffffff81501840-ffffffff81501a75: fscrypt_supported_v2_policy (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
bool fscrypt_supported_v2_policy(const struct fscrypt_policy_v2 *policy, const struct inode *inode);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/crypto/policy.c (ffffffff81538ed0)
Location: fs/crypto/policy.c:204
Inline: False
Direct callers:
  - fs/crypto/policy.c:fscrypt_supported_policy
```
**Symbols:**

```
ffffffff81538ed0-ffffffff81539101: fscrypt_supported_v2_policy (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
bool fscrypt_supported_v2_policy(const struct fscrypt_policy_v2 *policy, const struct inode *inode);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/crypto/policy.c (ffffffff8156dd00)
Location: fs/crypto/policy.c:215
Inline: False
Direct callers:
  - fs/crypto/policy.c:fscrypt_supported_policy
```
**Symbols:**

```
ffffffff8156dd00-ffffffff8156e0ba: fscrypt_supported_v2_policy (STB_LOCAL)
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
