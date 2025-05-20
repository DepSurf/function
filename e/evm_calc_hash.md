# Function: <code>evm_calc_hash</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int evm_calc_hash(struct dentry *dentry, const char *req_xattr_name, const char *req_xattr_value, size_t req_xattr_value_len, char *digest);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/integrity/evm/evm_crypto.c (ffffffff8139b660)
Location: security/integrity/evm/evm_crypto.c:186
Inline: False
Direct callers:
  - security/integrity/evm/evm_main.c:evm_verify_hmac
```
**Symbols:**

```
ffffffff8139b660-ffffffff8139b679: evm_calc_hash (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int evm_calc_hash(struct dentry *dentry, const char *req_xattr_name, const char *req_xattr_value, size_t req_xattr_value_len, char *digest);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/integrity/evm/evm_crypto.c (ffffffff813d8550)
Location: security/integrity/evm/evm_crypto.c:229
Inline: False
Direct callers:
  - security/integrity/evm/evm_main.c:evm_verify_hmac
```
**Symbols:**

```
ffffffff813d8550-ffffffff813d8569: evm_calc_hash (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int evm_calc_hash(struct dentry *dentry, const char *req_xattr_name, const char *req_xattr_value, size_t req_xattr_value_len, char *digest);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/integrity/evm/evm_crypto.c (ffffffff813f0200)
Location: security/integrity/evm/evm_crypto.c:238
Inline: False
Direct callers:
  - security/integrity/evm/evm_main.c:evm_verify_hmac
```
**Symbols:**

```
ffffffff813f0200-ffffffff813f0219: evm_calc_hash (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int evm_calc_hash(struct dentry *dentry, const char *req_xattr_name, const char *req_xattr_value, size_t req_xattr_value_len, char *digest);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/integrity/evm/evm_crypto.c (ffffffff813fc7c0)
Location: security/integrity/evm/evm_crypto.c:239
Inline: False
Direct callers:
  - security/integrity/evm/evm_main.c:evm_verify_hmac
```
**Symbols:**

```
ffffffff813fc7c0-ffffffff813fc7d9: evm_calc_hash (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int evm_calc_hash(struct dentry *dentry, const char *req_xattr_name, const char *req_xattr_value, size_t req_xattr_value_len, char *digest);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/integrity/evm/evm_crypto.c (ffffffff81424cf0)
Location: security/integrity/evm/evm_crypto.c:239
Inline: False
Direct callers:
  - security/integrity/evm/evm_main.c:evm_verify_hmac
```
**Symbols:**

```
ffffffff81424cf0-ffffffff81424d09: evm_calc_hash (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int evm_calc_hash(struct dentry *dentry, const char *req_xattr_name, const char *req_xattr_value, size_t req_xattr_value_len, char type, char *digest);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/integrity/evm/evm_crypto.c (ffffffff81457500)
Location: security/integrity/evm/evm_crypto.c:262
Inline: False
Direct callers:
  - security/integrity/evm/evm_main.c:evm_verify_hmac
```
**Symbols:**

```
ffffffff81457500-ffffffff81457514: evm_calc_hash (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int evm_calc_hash(struct dentry *dentry, const char *req_xattr_name, const char *req_xattr_value, size_t req_xattr_value_len, char type, struct evm_digest *data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/integrity/evm/evm_crypto.c (ffffffff814749f0)
Location: security/integrity/evm/evm_crypto.c:263
Inline: False
Direct callers:
  - security/integrity/evm/evm_main.c:evm_verify_hmac
```
**Symbols:**

```
ffffffff814749f0-ffffffff81474a04: evm_calc_hash (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int evm_calc_hash(struct dentry *dentry, const char *req_xattr_name, const char *req_xattr_value, size_t req_xattr_value_len, char type, struct evm_digest *data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/integrity/evm/evm_crypto.c (ffffffff814a26f0)
Location: security/integrity/evm/evm_crypto.c:261
Inline: False
Direct callers:
  - security/integrity/evm/evm_main.c:evm_verify_hmac
```
**Symbols:**

```
ffffffff814a26f0-ffffffff814a2704: evm_calc_hash (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int evm_calc_hash(struct dentry *dentry, const char *req_xattr_name, const char *req_xattr_value, size_t req_xattr_value_len, char type, struct evm_digest *data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/integrity/evm/evm_crypto.c (ffffffff814bd3c0)
Location: security/integrity/evm/evm_crypto.c:261
Inline: False
Direct callers:
  - security/integrity/evm/evm_main.c:evm_verify_hmac
```
**Symbols:**

```
ffffffff814bd3c0-ffffffff814bd3d4: evm_calc_hash (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int evm_calc_hash(struct dentry *dentry, const char *req_xattr_name, const char *req_xattr_value, size_t req_xattr_value_len, char type, struct evm_digest *data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/integrity/evm/evm_crypto.c (ffffffff8151dc90)
Location: security/integrity/evm/evm_crypto.c:259
Inline: False
Direct callers:
  - security/integrity/evm/evm_main.c:evm_verify_hmac
```
**Symbols:**

```
ffffffff8151dc90-ffffffff8151dca4: evm_calc_hash (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int evm_calc_hash(struct dentry *dentry, const char *req_xattr_name, const char *req_xattr_value, size_t req_xattr_value_len, char type, struct evm_digest *data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/integrity/evm/evm_crypto.c (ffffffff8153ab10)
Location: security/integrity/evm/evm_crypto.c:262
Inline: False
Direct callers:
  - security/integrity/evm/evm_main.c:evm_verify_hmac
```
**Symbols:**

```
ffffffff8153ab10-ffffffff8153ab24: evm_calc_hash (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int evm_calc_hash(struct dentry *dentry, const char *req_xattr_name, const char *req_xattr_value, size_t req_xattr_value_len, char type, struct evm_digest *data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/integrity/evm/evm_crypto.c (ffffffff815431d0)
Location: security/integrity/evm/evm_crypto.c:262
Inline: False
Direct callers:
  - security/integrity/evm/evm_main.c:evm_verify_hmac
```
**Symbols:**

```
ffffffff815431d0-ffffffff815431e4: evm_calc_hash (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int evm_calc_hash(struct dentry *dentry, const char *req_xattr_name, const char *req_xattr_value, size_t req_xattr_value_len, char type, struct evm_digest *data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/integrity/evm/evm_crypto.c (ffffffff815a3900)
Location: security/integrity/evm/evm_crypto.c:318
Inline: False
Direct callers:
  - security/integrity/evm/evm_main.c:evm_verify_hmac
```
**Symbols:**

```
ffffffff815a3900-ffffffff815a3914: evm_calc_hash (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int evm_calc_hash(struct dentry *dentry, const char *req_xattr_name, const char *req_xattr_value, size_t req_xattr_value_len, char type, struct evm_digest *data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/integrity/evm/evm_crypto.c (ffffffff8164a1b0)
Location: security/integrity/evm/evm_crypto.c:315
Inline: False
Direct callers:
  - security/integrity/evm/evm_main.c:evm_verify_hmac
```
**Symbols:**

```
ffffffff8164a1b0-ffffffff8164a1d6: evm_calc_hash (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int evm_calc_hash(struct dentry *dentry, const char *req_xattr_name, const char *req_xattr_value, size_t req_xattr_value_len, char type, struct evm_digest *data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/integrity/evm/evm_crypto.c (ffffffff81703240)
Location: security/integrity/evm/evm_crypto.c:315
Inline: False
Direct callers:
  - security/integrity/evm/evm_main.c:evm_verify_hmac
```
**Symbols:**

```
ffffffff81703240-ffffffff81703266: evm_calc_hash (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int evm_calc_hash(struct dentry *dentry, const char *req_xattr_name, const char *req_xattr_value, size_t req_xattr_value_len, char type, struct evm_digest *data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/integrity/evm/evm_crypto.c (ffffffff8173d270)
Location: security/integrity/evm/evm_crypto.c:314
Inline: False
Direct callers:
  - security/integrity/evm/evm_main.c:evm_verify_hmac
```
**Symbols:**

```
ffffffff8173d270-ffffffff8173d296: evm_calc_hash (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int evm_calc_hash(struct dentry *dentry, const char *req_xattr_name, const char *req_xattr_value, size_t req_xattr_value_len, char type, struct evm_digest *data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/integrity/evm/evm_crypto.c (ffffffff8177e090)
Location: security/integrity/evm/evm_crypto.c:314
Inline: False
Direct callers:
  - security/integrity/evm/evm_main.c:evm_verify_hmac
```
**Symbols:**

```
ffffffff8177e090-ffffffff8177e0b6: evm_calc_hash (STB_GLOBAL)
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
int evm_calc_hash(struct dentry *dentry, const char *req_xattr_name, const char *req_xattr_value, size_t req_xattr_value_len, char type, struct evm_digest *data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/integrity/evm/evm_crypto.c (ffff8000105b6220)
Location: security/integrity/evm/evm_crypto.c:261
Inline: False
Direct callers:
  - security/integrity/evm/evm_main.c:evm_verify_hmac
```
**Symbols:**

```
ffff8000105b6220-ffff8000105b6284: evm_calc_hash (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int evm_calc_hash(struct dentry *dentry, const char *req_xattr_name, const char *req_xattr_value, size_t req_xattr_value_len, char type, struct evm_digest *data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/integrity/evm/evm_crypto.c (c0765298)
Location: security/integrity/evm/evm_crypto.c:261
Inline: False
Direct callers:
  - security/integrity/evm/evm_main.c:evm_verify_hmac
```
**Symbols:**

```
c0765298-c07652cc: evm_calc_hash (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int evm_calc_hash(struct dentry *dentry, const char *req_xattr_name, const char *req_xattr_value, size_t req_xattr_value_len, char type, struct evm_digest *data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/integrity/evm/evm_crypto.c (c00000000073a1b0)
Location: security/integrity/evm/evm_crypto.c:261
Inline: False
Direct callers:
  - security/integrity/evm/evm_main.c:evm_verify_hmac
```
**Symbols:**

```
c00000000073a1b0-c00000000073a1c4: evm_calc_hash (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int evm_calc_hash(struct dentry *dentry, const char *req_xattr_name, const char *req_xattr_value, size_t req_xattr_value_len, char type, struct evm_digest *data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/integrity/evm/evm_crypto.c (ffffffe0003fcf24)
Location: security/integrity/evm/evm_crypto.c:261
Inline: False
Direct callers:
  - security/integrity/evm/evm_main.c:evm_verify_hmac
```
**Symbols:**

```
ffffffe0003fcf24-ffffffe0003fcf76: evm_calc_hash (STB_GLOBAL)
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
int evm_calc_hash(struct dentry *dentry, const char *req_xattr_name, const char *req_xattr_value, size_t req_xattr_value_len, char type, struct evm_digest *data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/integrity/evm/evm_crypto.c (ffffffff814b59a0)
Location: security/integrity/evm/evm_crypto.c:261
Inline: False
Direct callers:
  - security/integrity/evm/evm_main.c:evm_verify_hmac
```
**Symbols:**

```
ffffffff814b59a0-ffffffff814b59b4: evm_calc_hash (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int evm_calc_hash(struct dentry *dentry, const char *req_xattr_name, const char *req_xattr_value, size_t req_xattr_value_len, char type, struct evm_digest *data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/integrity/evm/evm_crypto.c (ffffffff814a63c0)
Location: security/integrity/evm/evm_crypto.c:261
Inline: False
Direct callers:
  - security/integrity/evm/evm_main.c:evm_verify_hmac
```
**Symbols:**

```
ffffffff814a63c0-ffffffff814a63d4: evm_calc_hash (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int evm_calc_hash(struct dentry *dentry, const char *req_xattr_name, const char *req_xattr_value, size_t req_xattr_value_len, char type, struct evm_digest *data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/integrity/evm/evm_crypto.c (ffffffff814b1a30)
Location: security/integrity/evm/evm_crypto.c:261
Inline: False
Direct callers:
  - security/integrity/evm/evm_main.c:evm_verify_hmac
```
**Symbols:**

```
ffffffff814b1a30-ffffffff814b1a44: evm_calc_hash (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int evm_calc_hash(struct dentry *dentry, const char *req_xattr_name, const char *req_xattr_value, size_t req_xattr_value_len, char type, struct evm_digest *data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/integrity/evm/evm_crypto.c (ffffffff814ca4b0)
Location: security/integrity/evm/evm_crypto.c:261
Inline: False
Direct callers:
  - security/integrity/evm/evm_main.c:evm_verify_hmac
```
**Symbols:**

```
ffffffff814ca4b0-ffffffff814ca4c4: evm_calc_hash (STB_GLOBAL)
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
<details>
<summary>Changed between <code>4.15</code> and <code>4.18</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>char type</code>
</li>
<li>
<b>Param reordered. </b>
<code>dentry, req_xattr_name, req_xattr_value, req_xattr_value_len, digest</code> ➡️ <code>dentry, req_xattr_name, req_xattr_value, req_xattr_value_len, type, digest</code>
</li>
</ul>
</details>
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
