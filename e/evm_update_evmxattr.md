# Function: <code>evm_update_evmxattr</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int evm_update_evmxattr(struct dentry *dentry, const char *xattr_name, const char *xattr_value, size_t xattr_value_len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/integrity/evm/evm_crypto.c (ffffffff8139b680)
Location: security/integrity/evm/evm_crypto.c:199
Inline: False
Direct callers:
  - security/integrity/evm/evm_main.c:evm_verify_hmac
  - security/integrity/evm/evm_main.c:evm_inode_post_setxattr
  - security/integrity/evm/evm_main.c:evm_inode_post_removexattr
  - security/integrity/evm/evm_main.c:evm_inode_post_setattr
```
**Symbols:**

```
ffffffff8139b680-ffffffff8139b71f: evm_update_evmxattr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int evm_update_evmxattr(struct dentry *dentry, const char *xattr_name, const char *xattr_value, size_t xattr_value_len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/integrity/evm/evm_crypto.c (ffffffff813d8570)
Location: security/integrity/evm/evm_crypto.c:242
Inline: False
Direct callers:
  - security/integrity/evm/evm_main.c:evm_inode_post_setattr
  - security/integrity/evm/evm_main.c:evm_inode_post_removexattr
  - security/integrity/evm/evm_main.c:evm_inode_post_setxattr
  - security/integrity/evm/evm_main.c:evm_verify_hmac
```
**Symbols:**

```
ffffffff813d8570-ffffffff813d860f: evm_update_evmxattr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int evm_update_evmxattr(struct dentry *dentry, const char *xattr_name, const char *xattr_value, size_t xattr_value_len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/integrity/evm/evm_crypto.c (ffffffff813f0220)
Location: security/integrity/evm/evm_crypto.c:251
Inline: False
Direct callers:
  - security/integrity/evm/evm_main.c:evm_inode_post_setattr
  - security/integrity/evm/evm_main.c:evm_inode_post_removexattr
  - security/integrity/evm/evm_main.c:evm_inode_post_setxattr
  - security/integrity/evm/evm_main.c:evm_verify_hmac
```
**Symbols:**

```
ffffffff813f0220-ffffffff813f02b9: evm_update_evmxattr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int evm_update_evmxattr(struct dentry *dentry, const char *xattr_name, const char *xattr_value, size_t xattr_value_len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/integrity/evm/evm_crypto.c (ffffffff813fc7e0)
Location: security/integrity/evm/evm_crypto.c:252
Inline: False
Direct callers:
  - security/integrity/evm/evm_main.c:evm_inode_post_setattr
  - security/integrity/evm/evm_main.c:evm_inode_post_removexattr
  - security/integrity/evm/evm_main.c:evm_inode_post_setxattr
  - security/integrity/evm/evm_main.c:evm_verify_hmac
```
**Symbols:**

```
ffffffff813fc7e0-ffffffff813fc879: evm_update_evmxattr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int evm_update_evmxattr(struct dentry *dentry, const char *xattr_name, const char *xattr_value, size_t xattr_value_len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/integrity/evm/evm_crypto.c (ffffffff81424d10)
Location: security/integrity/evm/evm_crypto.c:252
Inline: False
Direct callers:
  - security/integrity/evm/evm_main.c:evm_inode_post_setattr
  - security/integrity/evm/evm_main.c:evm_inode_post_removexattr
  - security/integrity/evm/evm_main.c:evm_inode_post_setxattr
  - security/integrity/evm/evm_main.c:evm_verify_hmac
```
**Symbols:**

```
ffffffff81424d10-ffffffff81424da9: evm_update_evmxattr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int evm_update_evmxattr(struct dentry *dentry, const char *xattr_name, const char *xattr_value, size_t xattr_value_len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/integrity/evm/evm_crypto.c (ffffffff81457520)
Location: security/integrity/evm/evm_crypto.c:303
Inline: False
Direct callers:
  - security/integrity/evm/evm_main.c:evm_inode_post_setattr
  - security/integrity/evm/evm_main.c:evm_inode_post_removexattr
  - security/integrity/evm/evm_main.c:evm_inode_post_setxattr
  - security/integrity/evm/evm_main.c:evm_verify_hmac
```
**Symbols:**

```
ffffffff81457520-ffffffff8145763d: evm_update_evmxattr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int evm_update_evmxattr(struct dentry *dentry, const char *xattr_name, const char *xattr_value, size_t xattr_value_len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/integrity/evm/evm_crypto.c (ffffffff81474a10)
Location: security/integrity/evm/evm_crypto.c:304
Inline: False
Direct callers:
  - security/integrity/evm/evm_main.c:evm_inode_post_setattr
  - security/integrity/evm/evm_main.c:evm_inode_post_removexattr
  - security/integrity/evm/evm_main.c:evm_inode_post_setxattr
  - security/integrity/evm/evm_main.c:evm_verify_hmac
```
**Symbols:**

```
ffffffff81474a10-ffffffff81474b31: evm_update_evmxattr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int evm_update_evmxattr(struct dentry *dentry, const char *xattr_name, const char *xattr_value, size_t xattr_value_len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/integrity/evm/evm_crypto.c (ffffffff814a2710)
Location: security/integrity/evm/evm_crypto.c:302
Inline: False
Direct callers:
  - security/integrity/evm/evm_main.c:evm_inode_post_setattr
  - security/integrity/evm/evm_main.c:evm_inode_post_removexattr
  - security/integrity/evm/evm_main.c:evm_inode_post_setxattr
  - security/integrity/evm/evm_main.c:evm_verify_hmac
```
**Symbols:**

```
ffffffff814a2710-ffffffff814a282b: evm_update_evmxattr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int evm_update_evmxattr(struct dentry *dentry, const char *xattr_name, const char *xattr_value, size_t xattr_value_len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/integrity/evm/evm_crypto.c (ffffffff814bd3e0)
Location: security/integrity/evm/evm_crypto.c:302
Inline: False
Direct callers:
  - security/integrity/evm/evm_main.c:evm_inode_post_setattr
  - security/integrity/evm/evm_main.c:evm_inode_post_removexattr
  - security/integrity/evm/evm_main.c:evm_inode_post_setxattr
  - security/integrity/evm/evm_main.c:evm_verify_hmac
```
**Symbols:**

```
ffffffff814bd3e0-ffffffff814bd4fb: evm_update_evmxattr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int evm_update_evmxattr(struct dentry *dentry, const char *xattr_name, const char *xattr_value, size_t xattr_value_len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/integrity/evm/evm_crypto.c (ffffffff8151dcb0)
Location: security/integrity/evm/evm_crypto.c:300
Inline: False
Direct callers:
  - security/integrity/evm/evm_main.c:evm_inode_post_setattr
  - security/integrity/evm/evm_main.c:evm_inode_post_removexattr
  - security/integrity/evm/evm_main.c:evm_inode_post_setxattr
  - security/integrity/evm/evm_main.c:evm_verify_hmac
```
**Symbols:**

```
ffffffff8151dcb0-ffffffff8151ddcb: evm_update_evmxattr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int evm_update_evmxattr(struct dentry *dentry, const char *xattr_name, const char *xattr_value, size_t xattr_value_len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/integrity/evm/evm_crypto.c (ffffffff8153ab30)
Location: security/integrity/evm/evm_crypto.c:303
Inline: False
Direct callers:
  - security/integrity/evm/evm_main.c:evm_inode_post_setattr
  - security/integrity/evm/evm_main.c:evm_inode_post_removexattr
  - security/integrity/evm/evm_main.c:evm_inode_post_setxattr
  - security/integrity/evm/evm_main.c:evm_verify_hmac
```
**Symbols:**

```
ffffffff8153ab30-ffffffff8153ac4b: evm_update_evmxattr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int evm_update_evmxattr(struct dentry *dentry, const char *xattr_name, const char *xattr_value, size_t xattr_value_len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/integrity/evm/evm_crypto.c (ffffffff815431f0)
Location: security/integrity/evm/evm_crypto.c:303
Inline: False
Direct callers:
  - security/integrity/evm/evm_main.c:evm_inode_post_setattr
  - security/integrity/evm/evm_main.c:evm_inode_post_removexattr
  - security/integrity/evm/evm_main.c:evm_inode_post_setxattr
  - security/integrity/evm/evm_main.c:evm_verify_hmac
```
**Symbols:**

```
ffffffff815431f0-ffffffff81543322: evm_update_evmxattr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int evm_update_evmxattr(struct dentry *dentry, const char *xattr_name, const char *xattr_value, size_t xattr_value_len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/integrity/evm/evm_crypto.c (ffffffff815a3920)
Location: security/integrity/evm/evm_crypto.c:359
Inline: False
Direct callers:
  - security/integrity/evm/evm_main.c:evm_inode_post_setattr
  - security/integrity/evm/evm_main.c:evm_inode_post_removexattr
  - security/integrity/evm/evm_main.c:evm_inode_post_setxattr
  - security/integrity/evm/evm_main.c:evm_verify_hmac
```
**Symbols:**

```
ffffffff815a3920-ffffffff815a3a52: evm_update_evmxattr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int evm_update_evmxattr(struct dentry *dentry, const char *xattr_name, const char *xattr_value, size_t xattr_value_len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/integrity/evm/evm_crypto.c (ffffffff8164a1e0)
Location: security/integrity/evm/evm_crypto.c:356
Inline: False
Direct callers:
  - security/integrity/evm/evm_main.c:evm_inode_post_setattr
  - security/integrity/evm/evm_main.c:evm_inode_post_removexattr
  - security/integrity/evm/evm_main.c:evm_inode_post_setxattr
  - security/integrity/evm/evm_main.c:evm_verify_hmac
```
**Symbols:**

```
ffffffff8164a1e0-ffffffff8164a35a: evm_update_evmxattr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int evm_update_evmxattr(struct dentry *dentry, const char *xattr_name, const char *xattr_value, size_t xattr_value_len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/integrity/evm/evm_crypto.c (ffffffff81703280)
Location: security/integrity/evm/evm_crypto.c:357
Inline: False
Direct callers:
  - security/integrity/evm/evm_main.c:evm_inode_post_setattr
  - security/integrity/evm/evm_main.c:evm_inode_post_removexattr
  - security/integrity/evm/evm_main.c:evm_inode_post_setxattr
  - security/integrity/evm/evm_main.c:evm_verify_hmac
```
**Symbols:**

```
ffffffff81703280-ffffffff81703422: evm_update_evmxattr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int evm_update_evmxattr(struct dentry *dentry, const char *xattr_name, const char *xattr_value, size_t xattr_value_len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/integrity/evm/evm_crypto.c (ffffffff8173d2b0)
Location: security/integrity/evm/evm_crypto.c:356
Inline: False
Direct callers:
  - security/integrity/evm/evm_main.c:evm_inode_post_setattr
  - security/integrity/evm/evm_main.c:evm_inode_post_removexattr
  - security/integrity/evm/evm_main.c:evm_inode_post_setxattr
  - security/integrity/evm/evm_main.c:evm_verify_hmac
```
**Symbols:**

```
ffffffff8173d2b0-ffffffff8173d452: evm_update_evmxattr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int evm_update_evmxattr(struct dentry *dentry, const char *xattr_name, const char *xattr_value, size_t xattr_value_len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/integrity/evm/evm_crypto.c (ffffffff8177e0d0)
Location: security/integrity/evm/evm_crypto.c:356
Inline: False
Direct callers:
  - security/integrity/evm/evm_main.c:evm_inode_post_setattr
  - security/integrity/evm/evm_main.c:evm_inode_post_removexattr
  - security/integrity/evm/evm_main.c:evm_inode_post_setxattr
  - security/integrity/evm/evm_main.c:evm_verify_hmac
```
**Symbols:**

```
ffffffff8177e0d0-ffffffff8177e272: evm_update_evmxattr (STB_GLOBAL)
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
int evm_update_evmxattr(struct dentry *dentry, const char *xattr_name, const char *xattr_value, size_t xattr_value_len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/integrity/evm/evm_crypto.c (ffff8000105b6288)
Location: security/integrity/evm/evm_crypto.c:302
Inline: False
Direct callers:
  - security/integrity/evm/evm_main.c:evm_inode_post_setattr
  - security/integrity/evm/evm_main.c:evm_inode_post_removexattr
  - security/integrity/evm/evm_main.c:evm_inode_post_setxattr
  - security/integrity/evm/evm_main.c:evm_verify_hmac
```
**Symbols:**

```
ffff8000105b6288-ffff8000105b63ec: evm_update_evmxattr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int evm_update_evmxattr(struct dentry *dentry, const char *xattr_name, const char *xattr_value, size_t xattr_value_len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/integrity/evm/evm_crypto.c (c07652cc)
Location: security/integrity/evm/evm_crypto.c:302
Inline: False
Direct callers:
  - security/integrity/evm/evm_main.c:evm_inode_post_setattr
  - security/integrity/evm/evm_main.c:evm_inode_post_removexattr
  - security/integrity/evm/evm_main.c:evm_inode_post_setxattr
  - security/integrity/evm/evm_main.c:evm_verify_hmac
```
**Symbols:**

```
c07652cc-c076542c: evm_update_evmxattr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int evm_update_evmxattr(struct dentry *dentry, const char *xattr_name, const char *xattr_value, size_t xattr_value_len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/integrity/evm/evm_crypto.c (c00000000073a1d0)
Location: security/integrity/evm/evm_crypto.c:302
Inline: False
Direct callers:
  - security/integrity/evm/evm_main.c:evm_inode_post_setattr
  - security/integrity/evm/evm_main.c:evm_inode_post_removexattr
  - security/integrity/evm/evm_main.c:evm_inode_post_setxattr
  - security/integrity/evm/evm_main.c:evm_verify_hmac
```
**Symbols:**

```
c00000000073a1d0-c00000000073a3e0: evm_update_evmxattr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int evm_update_evmxattr(struct dentry *dentry, const char *xattr_name, const char *xattr_value, size_t xattr_value_len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/integrity/evm/evm_crypto.c (ffffffe0003fcf76)
Location: security/integrity/evm/evm_crypto.c:302
Inline: False
Direct callers:
  - security/integrity/evm/evm_main.c:evm_inode_post_setattr
  - security/integrity/evm/evm_main.c:evm_inode_post_removexattr
  - security/integrity/evm/evm_main.c:evm_inode_post_setxattr
  - security/integrity/evm/evm_main.c:evm_verify_hmac
```
**Symbols:**

```
ffffffe0003fcf76-ffffffe0003fd082: evm_update_evmxattr (STB_GLOBAL)
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
int evm_update_evmxattr(struct dentry *dentry, const char *xattr_name, const char *xattr_value, size_t xattr_value_len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/integrity/evm/evm_crypto.c (ffffffff814b59c0)
Location: security/integrity/evm/evm_crypto.c:302
Inline: False
Direct callers:
  - security/integrity/evm/evm_main.c:evm_inode_post_setattr
  - security/integrity/evm/evm_main.c:evm_inode_post_removexattr
  - security/integrity/evm/evm_main.c:evm_inode_post_setxattr
  - security/integrity/evm/evm_main.c:evm_verify_hmac
```
**Symbols:**

```
ffffffff814b59c0-ffffffff814b5adb: evm_update_evmxattr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int evm_update_evmxattr(struct dentry *dentry, const char *xattr_name, const char *xattr_value, size_t xattr_value_len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/integrity/evm/evm_crypto.c (ffffffff814a63e0)
Location: security/integrity/evm/evm_crypto.c:302
Inline: False
Direct callers:
  - security/integrity/evm/evm_main.c:evm_inode_post_setattr
  - security/integrity/evm/evm_main.c:evm_inode_post_removexattr
  - security/integrity/evm/evm_main.c:evm_inode_post_setxattr
  - security/integrity/evm/evm_main.c:evm_verify_hmac
```
**Symbols:**

```
ffffffff814a63e0-ffffffff814a64fb: evm_update_evmxattr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int evm_update_evmxattr(struct dentry *dentry, const char *xattr_name, const char *xattr_value, size_t xattr_value_len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/integrity/evm/evm_crypto.c (ffffffff814b1a50)
Location: security/integrity/evm/evm_crypto.c:302
Inline: False
Direct callers:
  - security/integrity/evm/evm_main.c:evm_inode_post_setattr
  - security/integrity/evm/evm_main.c:evm_inode_post_removexattr
  - security/integrity/evm/evm_main.c:evm_inode_post_setxattr
  - security/integrity/evm/evm_main.c:evm_verify_hmac
```
**Symbols:**

```
ffffffff814b1a50-ffffffff814b1b6b: evm_update_evmxattr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int evm_update_evmxattr(struct dentry *dentry, const char *xattr_name, const char *xattr_value, size_t xattr_value_len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/integrity/evm/evm_crypto.c (ffffffff814ca4d0)
Location: security/integrity/evm/evm_crypto.c:302
Inline: False
Direct callers:
  - security/integrity/evm/evm_main.c:evm_inode_post_setattr
  - security/integrity/evm/evm_main.c:evm_inode_post_removexattr
  - security/integrity/evm/evm_main.c:evm_inode_post_setxattr
  - security/integrity/evm/evm_main.c:evm_verify_hmac
```
**Symbols:**

```
ffffffff814ca4d0-ffffffff814ca5eb: evm_update_evmxattr (STB_GLOBAL)
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
No changes between <code>4.18</code> and <code>5.0</code> ✅
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
