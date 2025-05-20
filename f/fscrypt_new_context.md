# Function: <code>fscrypt_new_context</code>

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
<summary>In <code>5.11</code>: ✅</summary>

```c
int fscrypt_new_context(union fscrypt_context *ctx_u, const union fscrypt_policy *policy_u, const u8 *nonce);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/crypto/policy.c (ffffffff813a5c60)
Location: fs/crypto/policy.c:260
Inline: False
Direct callers:
  - fs/crypto/policy.c:fscrypt_set_context
  - fs/crypto/policy.c:set_encryption_policy
```
**Symbols:**

```
ffffffff813a5c60-ffffffff813a5d15: fscrypt_new_context (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int fscrypt_new_context(union fscrypt_context *ctx_u, const union fscrypt_policy *policy_u, const u8 *nonce);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/crypto/policy.c (ffffffff813accf0)
Location: fs/crypto/policy.c:260
Inline: False
Direct callers:
  - fs/crypto/policy.c:fscrypt_set_context
  - fs/crypto/policy.c:set_encryption_policy
```
**Symbols:**

```
ffffffff813accf0-ffffffff813acda9: fscrypt_new_context (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int fscrypt_new_context(union fscrypt_context *ctx_u, const union fscrypt_policy *policy_u, const u8 *nonce);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/crypto/policy.c (ffffffff813fc660)
Location: fs/crypto/policy.c:260
Inline: False
Direct callers:
  - fs/crypto/policy.c:fscrypt_set_context
  - fs/crypto/policy.c:set_encryption_policy
```
**Symbols:**

```
ffffffff813fc660-ffffffff813fc719: fscrypt_new_context (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int fscrypt_new_context(union fscrypt_context *ctx_u, const union fscrypt_policy *policy_u, const u8 *nonce);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/crypto/policy.c (ffffffff8146fb20)
Location: fs/crypto/policy.c:281
Inline: False
Direct callers:
  - fs/crypto/policy.c:fscrypt_set_context
  - fs/crypto/policy.c:set_encryption_policy
```
**Symbols:**

```
ffffffff8146fb20-ffffffff8146fbee: fscrypt_new_context (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int fscrypt_new_context(union fscrypt_context *ctx_u, const union fscrypt_policy *policy_u, const u8 *nonce);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/crypto/policy.c (ffffffff815013b0)
Location: fs/crypto/policy.c:301
Inline: False
Direct callers:
  - fs/crypto/policy.c:fscrypt_set_context
  - fs/crypto/policy.c:set_encryption_policy
```
**Symbols:**

```
ffffffff815013b0-ffffffff8150147e: fscrypt_new_context (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int fscrypt_new_context(union fscrypt_context *ctx_u, const union fscrypt_policy *policy_u, const u8 *nonce);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/crypto/policy.c (ffffffff81538a40)
Location: fs/crypto/policy.c:300
Inline: False
Direct callers:
  - fs/crypto/policy.c:fscrypt_set_context
  - fs/crypto/policy.c:set_encryption_policy
```
**Symbols:**

```
ffffffff81538a40-ffffffff81538b0e: fscrypt_new_context (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int fscrypt_new_context(union fscrypt_context *ctx_u, const union fscrypt_policy *policy_u, const u8 *nonce);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/crypto/policy.c (ffffffff8156dbc0)
Location: fs/crypto/policy.c:325
Inline: False
Direct callers:
  - fs/crypto/policy.c:fscrypt_set_context
  - fs/crypto/policy.c:set_encryption_policy
```
**Symbols:**

```
ffffffff8156dbc0-ffffffff8156dc95: fscrypt_new_context (STB_LOCAL)
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
