# Function: <code>evm_calc_hmac</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline ⚠️</summary>

```c
int evm_calc_hmac(struct dentry *dentry, const char *req_xattr_name, const char *req_xattr_value, size_t req_xattr_value_len, char *digest);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/integrity/evm/evm_crypto.c (ffffffff8139b640)
Location: security/integrity/evm/evm_crypto.c:178
Inline: True
Inline callers:
  - security/integrity/evm/evm_crypto.c:evm_update_evmxattr
Direct callers:
  - security/integrity/evm/evm_main.c:evm_verify_hmac
```
**Symbols:**

```
ffffffff8139b640-ffffffff8139b659: evm_calc_hmac (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
int evm_calc_hmac(struct dentry *dentry, const char *req_xattr_name, const char *req_xattr_value, size_t req_xattr_value_len, char *digest);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/integrity/evm/evm_crypto.c (ffffffff813d8576)
Location: security/integrity/evm/evm_crypto.c:221
Inline: True
Inline callers:
  - security/integrity/evm/evm_crypto.c:evm_update_evmxattr
Direct callers:
  - security/integrity/evm/evm_main.c:evm_verify_hmac
```
**Symbols:**

```
ffffffff813d8530-ffffffff813d8549: evm_calc_hmac (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
int evm_calc_hmac(struct dentry *dentry, const char *req_xattr_name, const char *req_xattr_value, size_t req_xattr_value_len, char *digest);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/integrity/evm/evm_crypto.c (ffffffff813f0226)
Location: security/integrity/evm/evm_crypto.c:230
Inline: True
Inline callers:
  - security/integrity/evm/evm_crypto.c:evm_update_evmxattr
Direct callers:
  - security/integrity/evm/evm_main.c:evm_verify_hmac
```
**Symbols:**

```
ffffffff813f01e0-ffffffff813f01f9: evm_calc_hmac (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
int evm_calc_hmac(struct dentry *dentry, const char *req_xattr_name, const char *req_xattr_value, size_t req_xattr_value_len, char *digest);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/integrity/evm/evm_crypto.c (ffffffff813fc7e6)
Location: security/integrity/evm/evm_crypto.c:231
Inline: True
Inline callers:
  - security/integrity/evm/evm_crypto.c:evm_update_evmxattr
Direct callers:
  - security/integrity/evm/evm_main.c:evm_verify_hmac
```
**Symbols:**

```
ffffffff813fc7a0-ffffffff813fc7b9: evm_calc_hmac (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
int evm_calc_hmac(struct dentry *dentry, const char *req_xattr_name, const char *req_xattr_value, size_t req_xattr_value_len, char *digest);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/integrity/evm/evm_crypto.c (ffffffff81424d16)
Location: security/integrity/evm/evm_crypto.c:231
Inline: True
Inline callers:
  - security/integrity/evm/evm_crypto.c:evm_update_evmxattr
Direct callers:
  - security/integrity/evm/evm_main.c:evm_verify_hmac
```
**Symbols:**

```
ffffffff81424cd0-ffffffff81424ce9: evm_calc_hmac (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
int evm_calc_hmac(struct dentry *dentry, const char *req_xattr_name, const char *req_xattr_value, size_t req_xattr_value_len, char *digest);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/integrity/evm/evm_crypto.c (ffffffff814575a1)
Location: security/integrity/evm/evm_crypto.c:254
Inline: True
Inline callers:
  - security/integrity/evm/evm_crypto.c:evm_update_evmxattr
Direct callers:
  - security/integrity/evm/evm_main.c:evm_verify_hmac
```
**Symbols:**

```
ffffffff814574e0-ffffffff814574f9: evm_calc_hmac (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
int evm_calc_hmac(struct dentry *dentry, const char *req_xattr_name, const char *req_xattr_value, size_t req_xattr_value_len, struct evm_digest *data);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/integrity/evm/evm_crypto.c (ffffffff81474aab)
Location: security/integrity/evm/evm_crypto.c:255
Inline: True
Inline callers:
  - security/integrity/evm/evm_crypto.c:evm_update_evmxattr
Direct callers:
  - security/integrity/evm/evm_main.c:evm_verify_hmac
```
**Symbols:**

```
ffffffff814749d0-ffffffff814749e9: evm_calc_hmac (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
int evm_calc_hmac(struct dentry *dentry, const char *req_xattr_name, const char *req_xattr_value, size_t req_xattr_value_len, struct evm_digest *data);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/integrity/evm/evm_crypto.c (ffffffff814a27ab)
Location: security/integrity/evm/evm_crypto.c:253
Inline: True
Inline callers:
  - security/integrity/evm/evm_crypto.c:evm_update_evmxattr
Direct callers:
  - security/integrity/evm/evm_main.c:evm_verify_hmac
```
**Symbols:**

```
ffffffff814a26d0-ffffffff814a26e9: evm_calc_hmac (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
int evm_calc_hmac(struct dentry *dentry, const char *req_xattr_name, const char *req_xattr_value, size_t req_xattr_value_len, struct evm_digest *data);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/integrity/evm/evm_crypto.c (ffffffff814bd47b)
Location: security/integrity/evm/evm_crypto.c:253
Inline: True
Inline callers:
  - security/integrity/evm/evm_crypto.c:evm_update_evmxattr
Direct callers:
  - security/integrity/evm/evm_main.c:evm_verify_hmac
```
**Symbols:**

```
ffffffff814bd3a0-ffffffff814bd3b9: evm_calc_hmac (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
int evm_calc_hmac(struct dentry *dentry, const char *req_xattr_name, const char *req_xattr_value, size_t req_xattr_value_len, struct evm_digest *data);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/integrity/evm/evm_crypto.c (ffffffff8151dd4b)
Location: security/integrity/evm/evm_crypto.c:251
Inline: True
Inline callers:
  - security/integrity/evm/evm_crypto.c:evm_update_evmxattr
Direct callers:
  - security/integrity/evm/evm_main.c:evm_verify_hmac
```
**Symbols:**

```
ffffffff8151dc70-ffffffff8151dc89: evm_calc_hmac (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
int evm_calc_hmac(struct dentry *dentry, const char *req_xattr_name, const char *req_xattr_value, size_t req_xattr_value_len, struct evm_digest *data);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/integrity/evm/evm_crypto.c (ffffffff8153abcb)
Location: security/integrity/evm/evm_crypto.c:254
Inline: True
Inline callers:
  - security/integrity/evm/evm_crypto.c:evm_update_evmxattr
Direct callers:
  - security/integrity/evm/evm_main.c:evm_verify_hmac
```
**Symbols:**

```
ffffffff8153aaf0-ffffffff8153ab09: evm_calc_hmac (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
int evm_calc_hmac(struct dentry *dentry, const char *req_xattr_name, const char *req_xattr_value, size_t req_xattr_value_len, struct evm_digest *data);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/integrity/evm/evm_crypto.c (ffffffff81543293)
Location: security/integrity/evm/evm_crypto.c:254
Inline: True
Inline callers:
  - security/integrity/evm/evm_crypto.c:evm_update_evmxattr
Direct callers:
  - security/integrity/evm/evm_main.c:evm_verify_hmac
```
**Symbols:**

```
ffffffff815431b0-ffffffff815431c9: evm_calc_hmac (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
int evm_calc_hmac(struct dentry *dentry, const char *req_xattr_name, const char *req_xattr_value, size_t req_xattr_value_len, struct evm_digest *data);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/integrity/evm/evm_crypto.c (ffffffff815a39c3)
Location: security/integrity/evm/evm_crypto.c:310
Inline: True
Inline callers:
  - security/integrity/evm/evm_crypto.c:evm_update_evmxattr
Direct callers:
  - security/integrity/evm/evm_main.c:evm_verify_hmac
```
**Symbols:**

```
ffffffff815a38e0-ffffffff815a38f9: evm_calc_hmac (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
int evm_calc_hmac(struct dentry *dentry, const char *req_xattr_name, const char *req_xattr_value, size_t req_xattr_value_len, struct evm_digest *data);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/integrity/evm/evm_crypto.c (ffffffff8164a2b1)
Location: security/integrity/evm/evm_crypto.c:307
Inline: True
Inline callers:
  - security/integrity/evm/evm_crypto.c:evm_update_evmxattr
Direct callers:
  - security/integrity/evm/evm_main.c:evm_verify_hmac
```
**Symbols:**

```
ffffffff8164a180-ffffffff8164a1ab: evm_calc_hmac (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
int evm_calc_hmac(struct dentry *dentry, const char *req_xattr_name, const char *req_xattr_value, size_t req_xattr_value_len, struct evm_digest *data);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/integrity/evm/evm_crypto.c (ffffffff81703355)
Location: security/integrity/evm/evm_crypto.c:307
Inline: True
Inline callers:
  - security/integrity/evm/evm_crypto.c:evm_update_evmxattr
Direct callers:
  - security/integrity/evm/evm_main.c:evm_verify_hmac
```
**Symbols:**

```
ffffffff81703200-ffffffff8170322b: evm_calc_hmac (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
int evm_calc_hmac(struct dentry *dentry, const char *req_xattr_name, const char *req_xattr_value, size_t req_xattr_value_len, struct evm_digest *data);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/integrity/evm/evm_crypto.c (ffffffff8173d385)
Location: security/integrity/evm/evm_crypto.c:306
Inline: True
Inline callers:
  - security/integrity/evm/evm_crypto.c:evm_update_evmxattr
Direct callers:
  - security/integrity/evm/evm_main.c:evm_verify_hmac
```
**Symbols:**

```
ffffffff8173d230-ffffffff8173d25b: evm_calc_hmac (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
int evm_calc_hmac(struct dentry *dentry, const char *req_xattr_name, const char *req_xattr_value, size_t req_xattr_value_len, struct evm_digest *data);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/integrity/evm/evm_crypto.c (ffffffff8177e1a5)
Location: security/integrity/evm/evm_crypto.c:306
Inline: True
Inline callers:
  - security/integrity/evm/evm_crypto.c:evm_update_evmxattr
Direct callers:
  - security/integrity/evm/evm_main.c:evm_verify_hmac
```
**Symbols:**

```
ffffffff8177e050-ffffffff8177e07b: evm_calc_hmac (STB_GLOBAL)
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
int evm_calc_hmac(struct dentry *dentry, const char *req_xattr_name, const char *req_xattr_value, size_t req_xattr_value_len, struct evm_digest *data);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/integrity/evm/evm_crypto.c (ffff8000105b6340)
Location: security/integrity/evm/evm_crypto.c:253
Inline: True
Inline callers:
  - security/integrity/evm/evm_crypto.c:evm_update_evmxattr
Direct callers:
  - security/integrity/evm/evm_main.c:evm_verify_hmac
```
**Symbols:**

```
ffff8000105b61c0-ffff8000105b6220: evm_calc_hmac (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
int evm_calc_hmac(struct dentry *dentry, const char *req_xattr_name, const char *req_xattr_value, size_t req_xattr_value_len, struct evm_digest *data);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/integrity/evm/evm_crypto.c (c0765390)
Location: security/integrity/evm/evm_crypto.c:253
Inline: True
Inline callers:
  - security/integrity/evm/evm_crypto.c:evm_update_evmxattr
Direct callers:
  - security/integrity/evm/evm_main.c:evm_verify_hmac
```
**Symbols:**

```
c0765264-c0765298: evm_calc_hmac (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
int evm_calc_hmac(struct dentry *dentry, const char *req_xattr_name, const char *req_xattr_value, size_t req_xattr_value_len, struct evm_digest *data);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/integrity/evm/evm_crypto.c (c00000000073a2b4)
Location: security/integrity/evm/evm_crypto.c:253
Inline: True
Inline callers:
  - security/integrity/evm/evm_crypto.c:evm_update_evmxattr
Direct callers:
  - security/integrity/evm/evm_main.c:evm_verify_hmac
```
**Symbols:**

```
c00000000073a190-c00000000073a1ac: evm_calc_hmac (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
int evm_calc_hmac(struct dentry *dentry, const char *req_xattr_name, const char *req_xattr_value, size_t req_xattr_value_len, struct evm_digest *data);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/integrity/evm/evm_crypto.c (ffffffe0003fcff6)
Location: security/integrity/evm/evm_crypto.c:253
Inline: True
Inline callers:
  - security/integrity/evm/evm_crypto.c:evm_update_evmxattr
Direct callers:
  - security/integrity/evm/evm_main.c:evm_verify_hmac
```
**Symbols:**

```
ffffffe0003fced8-ffffffe0003fcf24: evm_calc_hmac (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Selective Inline ⚠️</summary>

```c
int evm_calc_hmac(struct dentry *dentry, const char *req_xattr_name, const char *req_xattr_value, size_t req_xattr_value_len, struct evm_digest *data);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/integrity/evm/evm_crypto.c (ffffffff814b5a5b)
Location: security/integrity/evm/evm_crypto.c:253
Inline: True
Inline callers:
  - security/integrity/evm/evm_crypto.c:evm_update_evmxattr
Direct callers:
  - security/integrity/evm/evm_main.c:evm_verify_hmac
```
**Symbols:**

```
ffffffff814b5980-ffffffff814b5999: evm_calc_hmac (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
int evm_calc_hmac(struct dentry *dentry, const char *req_xattr_name, const char *req_xattr_value, size_t req_xattr_value_len, struct evm_digest *data);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/integrity/evm/evm_crypto.c (ffffffff814a647b)
Location: security/integrity/evm/evm_crypto.c:253
Inline: True
Inline callers:
  - security/integrity/evm/evm_crypto.c:evm_update_evmxattr
Direct callers:
  - security/integrity/evm/evm_main.c:evm_verify_hmac
```
**Symbols:**

```
ffffffff814a63a0-ffffffff814a63b9: evm_calc_hmac (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
int evm_calc_hmac(struct dentry *dentry, const char *req_xattr_name, const char *req_xattr_value, size_t req_xattr_value_len, struct evm_digest *data);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/integrity/evm/evm_crypto.c (ffffffff814b1aeb)
Location: security/integrity/evm/evm_crypto.c:253
Inline: True
Inline callers:
  - security/integrity/evm/evm_crypto.c:evm_update_evmxattr
Direct callers:
  - security/integrity/evm/evm_main.c:evm_verify_hmac
```
**Symbols:**

```
ffffffff814b1a10-ffffffff814b1a29: evm_calc_hmac (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
int evm_calc_hmac(struct dentry *dentry, const char *req_xattr_name, const char *req_xattr_value, size_t req_xattr_value_len, struct evm_digest *data);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/integrity/evm/evm_crypto.c (ffffffff814ca56b)
Location: security/integrity/evm/evm_crypto.c:253
Inline: True
Inline callers:
  - security/integrity/evm/evm_crypto.c:evm_update_evmxattr
Direct callers:
  - security/integrity/evm/evm_main.c:evm_verify_hmac
```
**Symbols:**

```
ffffffff814ca490-ffffffff814ca4a9: evm_calc_hmac (STB_GLOBAL)
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
