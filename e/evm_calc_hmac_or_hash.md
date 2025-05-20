# Function: <code>evm_calc_hmac_or_hash</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int evm_calc_hmac_or_hash(struct dentry *dentry, const char *req_xattr_name, const char *req_xattr_value, size_t req_xattr_value_len, char type, char *digest);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/integrity/evm/evm_crypto.c (ffffffff8139b4b0)
Location: security/integrity/evm/evm_crypto.c:128
Inline: False
Direct callers:
  - security/integrity/evm/evm_crypto.c:evm_calc_hash
  - security/integrity/evm/evm_crypto.c:evm_update_evmxattr
```
**Symbols:**

```
ffffffff8139b4b0-ffffffff8139b635: evm_calc_hmac_or_hash (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int evm_calc_hmac_or_hash(struct dentry *dentry, const char *req_xattr_name, const char *req_xattr_value, size_t req_xattr_value_len, char type, char *digest);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/integrity/evm/evm_crypto.c (ffffffff813d8330)
Location: security/integrity/evm/evm_crypto.c:171
Inline: False
Direct callers:
  - security/integrity/evm/evm_crypto.c:evm_update_evmxattr
  - security/integrity/evm/evm_crypto.c:evm_calc_hash
```
**Symbols:**

```
ffffffff813d8330-ffffffff813d84be: evm_calc_hmac_or_hash (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int evm_calc_hmac_or_hash(struct dentry *dentry, const char *req_xattr_name, const char *req_xattr_value, size_t req_xattr_value_len, char type, char *digest);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/integrity/evm/evm_crypto.c (ffffffff813effe0)
Location: security/integrity/evm/evm_crypto.c:179
Inline: False
Direct callers:
  - security/integrity/evm/evm_crypto.c:evm_update_evmxattr
  - security/integrity/evm/evm_crypto.c:evm_calc_hash
```
**Symbols:**

```
ffffffff813effe0-ffffffff813f0164: evm_calc_hmac_or_hash (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int evm_calc_hmac_or_hash(struct dentry *dentry, const char *req_xattr_name, const char *req_xattr_value, size_t req_xattr_value_len, char type, char *digest);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/integrity/evm/evm_crypto.c (ffffffff813fc600)
Location: security/integrity/evm/evm_crypto.c:179
Inline: False
Direct callers:
  - security/integrity/evm/evm_crypto.c:evm_update_evmxattr
  - security/integrity/evm/evm_crypto.c:evm_calc_hash
```
**Symbols:**

```
ffffffff813fc600-ffffffff813fc7a0: evm_calc_hmac_or_hash (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int evm_calc_hmac_or_hash(struct dentry *dentry, const char *req_xattr_name, const char *req_xattr_value, size_t req_xattr_value_len, char type, char *digest);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/integrity/evm/evm_crypto.c (ffffffff81424b30)
Location: security/integrity/evm/evm_crypto.c:179
Inline: False
Direct callers:
  - security/integrity/evm/evm_crypto.c:evm_update_evmxattr
  - security/integrity/evm/evm_crypto.c:evm_calc_hash
```
**Symbols:**

```
ffffffff81424b30-ffffffff81424cd0: evm_calc_hmac_or_hash (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int evm_calc_hmac_or_hash(struct dentry *dentry, const char *req_xattr_name, const char *req_xattr_value, size_t req_xattr_value_len, char type, char *digest);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/integrity/evm/evm_crypto.c (ffffffff81457280)
Location: security/integrity/evm/evm_crypto.c:189
Inline: False
Direct callers:
  - security/integrity/evm/evm_crypto.c:evm_update_evmxattr
  - security/integrity/evm/evm_crypto.c:evm_calc_hash
```
**Symbols:**

```
ffffffff81457280-ffffffff8145746a: evm_calc_hmac_or_hash (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int evm_calc_hmac_or_hash(struct dentry *dentry, const char *req_xattr_name, const char *req_xattr_value, size_t req_xattr_value_len, uint8_t type, struct evm_digest *data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/integrity/evm/evm_crypto.c (ffffffff81474730)
Location: security/integrity/evm/evm_crypto.c:188
Inline: False
Direct callers:
  - security/integrity/evm/evm_crypto.c:evm_update_evmxattr
  - security/integrity/evm/evm_crypto.c:evm_calc_hash
```
**Symbols:**

```
ffffffff81474730-ffffffff8147495a: evm_calc_hmac_or_hash (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int evm_calc_hmac_or_hash(struct dentry *dentry, const char *req_xattr_name, const char *req_xattr_value, size_t req_xattr_value_len, uint8_t type, struct evm_digest *data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/integrity/evm/evm_crypto.c (ffffffff814a2440)
Location: security/integrity/evm/evm_crypto.c:186
Inline: False
Direct callers:
  - security/integrity/evm/evm_crypto.c:evm_update_evmxattr
  - security/integrity/evm/evm_crypto.c:evm_calc_hash
```
**Symbols:**

```
ffffffff814a2440-ffffffff814a2675: evm_calc_hmac_or_hash (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int evm_calc_hmac_or_hash(struct dentry *dentry, const char *req_xattr_name, const char *req_xattr_value, size_t req_xattr_value_len, uint8_t type, struct evm_digest *data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/integrity/evm/evm_crypto.c (ffffffff814bd110)
Location: security/integrity/evm/evm_crypto.c:186
Inline: False
Direct callers:
  - security/integrity/evm/evm_crypto.c:evm_update_evmxattr
  - security/integrity/evm/evm_crypto.c:evm_calc_hash
```
**Symbols:**

```
ffffffff814bd110-ffffffff814bd345: evm_calc_hmac_or_hash (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int evm_calc_hmac_or_hash(struct dentry *dentry, const char *req_xattr_name, const char *req_xattr_value, size_t req_xattr_value_len, uint8_t type, struct evm_digest *data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/integrity/evm/evm_crypto.c (ffffffff8151da30)
Location: security/integrity/evm/evm_crypto.c:184
Inline: False
Direct callers:
  - security/integrity/evm/evm_crypto.c:evm_update_evmxattr
  - security/integrity/evm/evm_crypto.c:evm_calc_hash
```
**Symbols:**

```
ffffffff8151da30-ffffffff8151dc62: evm_calc_hmac_or_hash (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int evm_calc_hmac_or_hash(struct dentry *dentry, const char *req_xattr_name, const char *req_xattr_value, size_t req_xattr_value_len, uint8_t type, struct evm_digest *data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/integrity/evm/evm_crypto.c (ffffffff8153a8b0)
Location: security/integrity/evm/evm_crypto.c:187
Inline: False
Direct callers:
  - security/integrity/evm/evm_crypto.c:evm_update_evmxattr
  - security/integrity/evm/evm_crypto.c:evm_calc_hash
```
**Symbols:**

```
ffffffff8153a8b0-ffffffff8153aae2: evm_calc_hmac_or_hash (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int evm_calc_hmac_or_hash(struct dentry *dentry, const char *req_xattr_name, const char *req_xattr_value, size_t req_xattr_value_len, uint8_t type, struct evm_digest *data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/integrity/evm/evm_crypto.c (ffffffff81542f70)
Location: security/integrity/evm/evm_crypto.c:187
Inline: False
Direct callers:
  - security/integrity/evm/evm_crypto.c:evm_update_evmxattr
  - security/integrity/evm/evm_crypto.c:evm_calc_hash
```
**Symbols:**

```
ffffffff81542f70-ffffffff815431af: evm_calc_hmac_or_hash (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int evm_calc_hmac_or_hash(struct dentry *dentry, const char *req_xattr_name, const char *req_xattr_value, size_t req_xattr_value_len, uint8_t type, struct evm_digest *data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In security/integrity/evm/evm_crypto.c (0)
Location: security/integrity/evm/evm_crypto.c:213
Inline: False
Direct callers:
  - security/integrity/evm/evm_crypto.c:evm_update_evmxattr
  - security/integrity/evm/evm_crypto.c:evm_calc_hash
```
**Symbols:**

```
ffffffff815a3580-ffffffff815a38d3: evm_calc_hmac_or_hash (STB_LOCAL)
ffffffff81cd756d-ffffffff81cd7582: evm_calc_hmac_or_hash.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int evm_calc_hmac_or_hash(struct dentry *dentry, const char *req_xattr_name, const char *req_xattr_value, size_t req_xattr_value_len, uint8_t type, struct evm_digest *data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In security/integrity/evm/evm_crypto.c (0)
Location: security/integrity/evm/evm_crypto.c:210
Inline: False
Direct callers:
  - security/integrity/evm/evm_crypto.c:evm_update_evmxattr
  - security/integrity/evm/evm_crypto.c:evm_calc_hash
```
**Symbols:**

```
ffffffff81649de0-ffffffff8164a174: evm_calc_hmac_or_hash (STB_LOCAL)
ffffffff81e8a838-ffffffff81e8a84d: evm_calc_hmac_or_hash.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
int evm_calc_hmac_or_hash(struct dentry *dentry, const char *req_xattr_name, const char *req_xattr_value, size_t req_xattr_value_len, uint8_t type, struct evm_digest *data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In security/integrity/evm/evm_crypto.c (0)
Location: security/integrity/evm/evm_crypto.c:210
Inline: False
Direct callers:
  - security/integrity/evm/evm_crypto.c:evm_update_evmxattr
  - security/integrity/evm/evm_crypto.c:evm_calc_hash
```
**Symbols:**

```
ffffffff81702e50-ffffffff817031e4: evm_calc_hmac_or_hash (STB_LOCAL)
ffffffff82075678-ffffffff8207568d: evm_calc_hmac_or_hash.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
int evm_calc_hmac_or_hash(struct dentry *dentry, const char *req_xattr_name, const char *req_xattr_value, size_t req_xattr_value_len, uint8_t type, struct evm_digest *data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In security/integrity/evm/evm_crypto.c (0)
Location: security/integrity/evm/evm_crypto.c:220
Inline: False
Direct callers:
  - security/integrity/evm/evm_crypto.c:evm_update_evmxattr
  - security/integrity/evm/evm_crypto.c:evm_calc_hash
```
**Symbols:**

```
ffffffff8173cef0-ffffffff8173d211: evm_calc_hmac_or_hash (STB_LOCAL)
ffffffff820f51da-ffffffff820f51ef: evm_calc_hmac_or_hash.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
int evm_calc_hmac_or_hash(struct dentry *dentry, const char *req_xattr_name, const char *req_xattr_value, size_t req_xattr_value_len, uint8_t type, struct evm_digest *data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In security/integrity/evm/evm_crypto.c (0)
Location: security/integrity/evm/evm_crypto.c:220
Inline: False
Direct callers:
  - security/integrity/evm/evm_crypto.c:evm_update_evmxattr
  - security/integrity/evm/evm_crypto.c:evm_calc_hash
```
**Symbols:**

```
ffffffff8177dd10-ffffffff8177e031: evm_calc_hmac_or_hash (STB_LOCAL)
ffffffff821d23ae-ffffffff821d23c3: evm_calc_hmac_or_hash.cold (STB_LOCAL)
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
int evm_calc_hmac_or_hash(struct dentry *dentry, const char *req_xattr_name, const char *req_xattr_value, size_t req_xattr_value_len, uint8_t type, struct evm_digest *data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/integrity/evm/evm_crypto.c (ffff8000105b5e48)
Location: security/integrity/evm/evm_crypto.c:186
Inline: False
Direct callers:
  - security/integrity/evm/evm_crypto.c:evm_update_evmxattr
  - security/integrity/evm/evm_crypto.c:evm_calc_hash
```
**Symbols:**

```
ffff8000105b5e48-ffff8000105b60b0: evm_calc_hmac_or_hash (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int evm_calc_hmac_or_hash(struct dentry *dentry, const char *req_xattr_name, const char *req_xattr_value, size_t req_xattr_value_len, uint8_t type, struct evm_digest *data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/integrity/evm/evm_crypto.c (c0764f58)
Location: security/integrity/evm/evm_crypto.c:186
Inline: False
Direct callers:
  - security/integrity/evm/evm_crypto.c:evm_update_evmxattr
  - security/integrity/evm/evm_crypto.c:evm_calc_hash
```
**Symbols:**

```
c0764f58-c07651c8: evm_calc_hmac_or_hash (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int evm_calc_hmac_or_hash(struct dentry *dentry, const char *req_xattr_name, const char *req_xattr_value, size_t req_xattr_value_len, uint8_t type, struct evm_digest *data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/integrity/evm/evm_crypto.c (c000000000739a80)
Location: security/integrity/evm/evm_crypto.c:186
Inline: False
Direct callers:
  - security/integrity/evm/evm_crypto.c:evm_update_evmxattr
  - security/integrity/evm/evm_crypto.c:evm_update_evmxattr
  - security/integrity/evm/evm_crypto.c:evm_calc_hash
```
**Symbols:**

```
c000000000739a80-c00000000073a0b0: evm_calc_hmac_or_hash (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int evm_calc_hmac_or_hash(struct dentry *dentry, const char *req_xattr_name, const char *req_xattr_value, size_t req_xattr_value_len, uint8_t type, struct evm_digest *data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/integrity/evm/evm_crypto.c (ffffffe0003fcc46)
Location: security/integrity/evm/evm_crypto.c:186
Inline: False
Direct callers:
  - security/integrity/evm/evm_crypto.c:evm_update_evmxattr
  - security/integrity/evm/evm_crypto.c:evm_calc_hash
```
**Symbols:**

```
ffffffe0003fcc46-ffffffe0003fce42: evm_calc_hmac_or_hash (STB_LOCAL)
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
int evm_calc_hmac_or_hash(struct dentry *dentry, const char *req_xattr_name, const char *req_xattr_value, size_t req_xattr_value_len, uint8_t type, struct evm_digest *data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/integrity/evm/evm_crypto.c (ffffffff814b56f0)
Location: security/integrity/evm/evm_crypto.c:186
Inline: False
Direct callers:
  - security/integrity/evm/evm_crypto.c:evm_update_evmxattr
  - security/integrity/evm/evm_crypto.c:evm_calc_hash
```
**Symbols:**

```
ffffffff814b56f0-ffffffff814b5925: evm_calc_hmac_or_hash (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int evm_calc_hmac_or_hash(struct dentry *dentry, const char *req_xattr_name, const char *req_xattr_value, size_t req_xattr_value_len, uint8_t type, struct evm_digest *data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/integrity/evm/evm_crypto.c (ffffffff814a6110)
Location: security/integrity/evm/evm_crypto.c:186
Inline: False
Direct callers:
  - security/integrity/evm/evm_crypto.c:evm_update_evmxattr
  - security/integrity/evm/evm_crypto.c:evm_calc_hash
```
**Symbols:**

```
ffffffff814a6110-ffffffff814a6345: evm_calc_hmac_or_hash (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int evm_calc_hmac_or_hash(struct dentry *dentry, const char *req_xattr_name, const char *req_xattr_value, size_t req_xattr_value_len, uint8_t type, struct evm_digest *data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/integrity/evm/evm_crypto.c (ffffffff814b1780)
Location: security/integrity/evm/evm_crypto.c:186
Inline: False
Direct callers:
  - security/integrity/evm/evm_crypto.c:evm_update_evmxattr
  - security/integrity/evm/evm_crypto.c:evm_calc_hash
```
**Symbols:**

```
ffffffff814b1780-ffffffff814b19b5: evm_calc_hmac_or_hash (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int evm_calc_hmac_or_hash(struct dentry *dentry, const char *req_xattr_name, const char *req_xattr_value, size_t req_xattr_value_len, uint8_t type, struct evm_digest *data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/integrity/evm/evm_crypto.c (ffffffff814ca200)
Location: security/integrity/evm/evm_crypto.c:186
Inline: False
Direct callers:
  - security/integrity/evm/evm_crypto.c:evm_update_evmxattr
  - security/integrity/evm/evm_crypto.c:evm_calc_hash
```
**Symbols:**

```
ffffffff814ca200-ffffffff814ca435: evm_calc_hmac_or_hash (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>4.4</code> and <code>4.8</code> ✅
</li>
<li>
No changes between <code>4.8</code> and <code>4.10</code> ✅
</li>
<li>
No changes between <code>4.10</code> and <code>4.13</code> ✅
</li>
<li>
No changes between <code>4.13</code> and <code>4.15</code> ✅
</li>
<li>
No changes between <code>4.15</code> and <code>4.18</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>4.18</code> and <code>5.0</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>struct evm_digest *data</code>
</li>
<li>
<b>Param removed. </b>
<code>char *digest</code>
</li>
<li>
<b>Param type changed. </b>
<code>char type</code> ➡️ <code>uint8_t type</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>5.0</code> and <code>5.3</code> ✅
</li>
<li>
No changes between <code>5.3</code> and <code>5.4</code> ✅
</li>
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
