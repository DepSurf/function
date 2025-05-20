# Function: <code>fscrypt_new_context_from_policy</code>

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
int fscrypt_new_context_from_policy(union fscrypt_context *ctx_u, const union fscrypt_policy *policy_u);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/crypto/policy.c (ffffffff8134e8c0)
Location: fs/crypto/policy.c:107
Inline: False
Direct callers:
  - fs/crypto/policy.c:fscrypt_ioctl_set_policy
```
**Symbols:**

```
ffffffff8134e8c0-ffffffff8134e973: fscrypt_new_context_from_policy (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int fscrypt_new_context_from_policy(union fscrypt_context *ctx_u, const union fscrypt_policy *policy_u);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/crypto/policy.c (ffffffff813947d0)
Location: fs/crypto/policy.c:230
Inline: False
Direct callers:
  - fs/crypto/policy.c:fscrypt_inherit_context
  - fs/crypto/policy.c:set_encryption_policy
```
**Symbols:**

```
ffffffff813947d0-ffffffff81394883: fscrypt_new_context_from_policy (STB_LOCAL)
```
</details>
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
<summary>In <code>arm64</code>: ✅</summary>

```c
int fscrypt_new_context_from_policy(union fscrypt_context *ctx_u, const union fscrypt_policy *policy_u);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/crypto/policy.c (ffff80001040fc40)
Location: fs/crypto/policy.c:107
Inline: False
Direct callers:
  - fs/crypto/policy.c:fscrypt_ioctl_set_policy
```
**Symbols:**

```
ffff80001040fc40-ffff80001040fd00: fscrypt_new_context_from_policy (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int fscrypt_new_context_from_policy(union fscrypt_context *ctx_u, const union fscrypt_policy *policy_u);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/crypto/policy.c (c05dc684)
Location: fs/crypto/policy.c:107
Inline: False
Direct callers:
  - fs/crypto/policy.c:fscrypt_ioctl_set_policy
```
**Symbols:**

```
c05dc684-c05dc760: fscrypt_new_context_from_policy (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int fscrypt_new_context_from_policy(union fscrypt_context *ctx_u, const union fscrypt_policy *policy_u);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/crypto/policy.c (c00000000051d740)
Location: fs/crypto/policy.c:107
Inline: False
Direct callers:
  - fs/crypto/policy.c:fscrypt_ioctl_set_policy
```
**Symbols:**

```
c00000000051d740-c00000000051d840: fscrypt_new_context_from_policy (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int fscrypt_new_context_from_policy(union fscrypt_context *ctx_u, const union fscrypt_policy *policy_u);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/crypto/policy.c (ffffffe0002b87ec)
Location: fs/crypto/policy.c:107
Inline: False
Direct callers:
  - fs/crypto/policy.c:fscrypt_ioctl_set_policy
```
**Symbols:**

```
ffffffe0002b87ec-ffffffe0002b88ee: fscrypt_new_context_from_policy (STB_LOCAL)
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
int fscrypt_new_context_from_policy(union fscrypt_context *ctx_u, const union fscrypt_policy *policy_u);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/crypto/policy.c (ffffffff81346ea0)
Location: fs/crypto/policy.c:107
Inline: False
Direct callers:
  - fs/crypto/policy.c:fscrypt_ioctl_set_policy
```
**Symbols:**

```
ffffffff81346ea0-ffffffff81346f53: fscrypt_new_context_from_policy (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int fscrypt_new_context_from_policy(union fscrypt_context *ctx_u, const union fscrypt_policy *policy_u);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/crypto/policy.c (ffffffff81337b80)
Location: fs/crypto/policy.c:107
Inline: False
Direct callers:
  - fs/crypto/policy.c:fscrypt_ioctl_set_policy
```
**Symbols:**

```
ffffffff81337b80-ffffffff81337c33: fscrypt_new_context_from_policy (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int fscrypt_new_context_from_policy(union fscrypt_context *ctx_u, const union fscrypt_policy *policy_u);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/crypto/policy.c (ffffffff81344970)
Location: fs/crypto/policy.c:107
Inline: False
Direct callers:
  - fs/crypto/policy.c:fscrypt_ioctl_set_policy
```
**Symbols:**

```
ffffffff81344970-ffffffff81344a23: fscrypt_new_context_from_policy (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int fscrypt_new_context_from_policy(union fscrypt_context *ctx_u, const union fscrypt_policy *policy_u);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/crypto/policy.c (ffffffff81357c50)
Location: fs/crypto/policy.c:107
Inline: False
Direct callers:
  - fs/crypto/policy.c:fscrypt_ioctl_set_policy
```
**Symbols:**

```
ffffffff81357c50-ffffffff81357d03: fscrypt_new_context_from_policy (STB_LOCAL)
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
