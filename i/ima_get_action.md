# Function: <code>ima_get_action</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int ima_get_action(struct inode *inode, int mask, int function);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/integrity/ima/ima_api.c (ffffffff81398870)
Location: security/integrity/ima/ima_api.c:171
Inline: False
Direct callers:
  - security/integrity/ima/ima_main.c:process_measurement
```
**Symbols:**

```
ffffffff81398870-ffffffff8139888f: ima_get_action (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int ima_get_action(struct inode *inode, int mask, enum ima_hooks func, int *pcr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/integrity/ima/ima_api.c (ffffffff813d4e30)
Location: security/integrity/ima/ima_api.c:174
Inline: False
Direct callers:
  - security/integrity/ima/ima_main.c:process_measurement
```
**Symbols:**

```
ffffffff813d4e30-ffffffff813d4e54: ima_get_action (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int ima_get_action(struct inode *inode, int mask, enum ima_hooks func, int *pcr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/integrity/ima/ima_api.c (ffffffff813ec880)
Location: security/integrity/ima/ima_api.c:174
Inline: False
Direct callers:
  - security/integrity/ima/ima_main.c:process_measurement
```
**Symbols:**

```
ffffffff813ec880-ffffffff813ec8a4: ima_get_action (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int ima_get_action(struct inode *inode, int mask, enum ima_hooks func, int *pcr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/integrity/ima/ima_api.c (ffffffff813f8c70)
Location: security/integrity/ima/ima_api.c:175
Inline: False
Direct callers:
  - security/integrity/ima/ima_main.c:process_measurement
```
**Symbols:**

```
ffffffff813f8c70-ffffffff813f8c94: ima_get_action (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int ima_get_action(struct inode *inode, int mask, enum ima_hooks func, int *pcr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/integrity/ima/ima_api.c (ffffffff814210a0)
Location: security/integrity/ima/ima_api.c:175
Inline: False
Direct callers:
  - security/integrity/ima/ima_main.c:process_measurement
```
**Symbols:**

```
ffffffff814210a0-ffffffff814210c4: ima_get_action (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int ima_get_action(struct inode *inode, const struct cred *cred, u32 secid, int mask, enum ima_hooks func, int *pcr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/integrity/ima/ima_api.c (ffffffff81453600)
Location: security/integrity/ima/ima_api.c:178
Inline: False
Direct callers:
  - security/integrity/ima/ima_main.c:process_measurement
```
**Symbols:**

```
ffffffff81453600-ffffffff81453628: ima_get_action (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int ima_get_action(struct inode *inode, const struct cred *cred, u32 secid, int mask, enum ima_hooks func, int *pcr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/integrity/ima/ima_api.c (ffffffff814707e0)
Location: security/integrity/ima/ima_api.c:178
Inline: False
Direct callers:
  - security/integrity/ima/ima_main.c:process_measurement
```
**Symbols:**

```
ffffffff814707e0-ffffffff81470808: ima_get_action (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int ima_get_action(struct inode *inode, const struct cred *cred, u32 secid, int mask, enum ima_hooks func, int *pcr, struct ima_template_desc **template_desc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/integrity/ima/ima_api.c (ffffffff8149e1b0)
Location: security/integrity/ima/ima_api.c:184
Inline: False
Direct callers:
  - security/integrity/ima/ima_main.c:process_measurement
```
**Symbols:**

```
ffffffff8149e1b0-ffffffff8149e1dc: ima_get_action (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int ima_get_action(struct inode *inode, const struct cred *cred, u32 secid, int mask, enum ima_hooks func, int *pcr, struct ima_template_desc **template_desc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/integrity/ima/ima_api.c (ffffffff814b8630)
Location: security/integrity/ima/ima_api.c:184
Inline: False
Direct callers:
  - security/integrity/ima/ima_main.c:process_buffer_measurement
  - security/integrity/ima/ima_main.c:process_measurement
```
**Symbols:**

```
ffffffff814b8630-ffffffff814b865c: ima_get_action (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int ima_get_action(struct inode *inode, const struct cred *cred, struct lsmblob *blob, int mask, enum ima_hooks func, int *pcr, struct ima_template_desc **template_desc, const char *keyring);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/integrity/ima/ima_api.c (ffffffff81518240)
Location: security/integrity/ima/ima_api.c:186
Inline: False
Direct callers:
  - security/integrity/ima/ima_main.c:process_buffer_measurement
  - security/integrity/ima/ima_main.c:ima_file_mprotect
  - security/integrity/ima/ima_main.c:process_measurement
```
**Symbols:**

```
ffffffff81518240-ffffffff8151826f: ima_get_action (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int ima_get_action(struct inode *inode, const struct cred *cred, struct lsmblob *blob, int mask, enum ima_hooks func, int *pcr, struct ima_template_desc **template_desc, const char *keyring);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/integrity/ima/ima_api.c (ffffffff81535210)
Location: security/integrity/ima/ima_api.c:186
Inline: False
Direct callers:
  - security/integrity/ima/ima_main.c:process_buffer_measurement
  - security/integrity/ima/ima_main.c:ima_file_mprotect
  - security/integrity/ima/ima_main.c:process_measurement
```
**Symbols:**

```
ffffffff81535210-ffffffff8153523f: ima_get_action (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int ima_get_action(struct user_namespace *mnt_userns, struct inode *inode, const struct cred *cred, struct lsmblob *blob, int mask, enum ima_hooks func, int *pcr, struct ima_template_desc **template_desc, const char *func_data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/integrity/ima/ima_api.c (ffffffff8153d830)
Location: security/integrity/ima/ima_api.c:187
Inline: False
Direct callers:
  - security/integrity/ima/ima_main.c:process_buffer_measurement
  - security/integrity/ima/ima_main.c:ima_file_mprotect
  - security/integrity/ima/ima_main.c:process_measurement
```
**Symbols:**

```
ffffffff8153d830-ffffffff8153d85e: ima_get_action (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int ima_get_action(struct user_namespace *mnt_userns, struct inode *inode, const struct cred *cred, struct lsmblob *blob, int mask, enum ima_hooks func, int *pcr, struct ima_template_desc **template_desc, const char *func_data, unsigned int *allowed_algos);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/integrity/ima/ima_api.c (ffffffff8159c6b0)
Location: security/integrity/ima/ima_api.c:188
Inline: False
Direct callers:
  - security/integrity/ima/ima_main.c:process_buffer_measurement
  - security/integrity/ima/ima_main.c:ima_file_mprotect
  - security/integrity/ima/ima_main.c:process_measurement
```
**Symbols:**

```
ffffffff8159c6b0-ffffffff8159c6e1: ima_get_action (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int ima_get_action(struct user_namespace *mnt_userns, struct inode *inode, const struct cred *cred, struct lsmblob *blob, int mask, enum ima_hooks func, int *pcr, struct ima_template_desc **template_desc, const char *func_data, unsigned int *allowed_algos);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/integrity/ima/ima_api.c (ffffffff816416e0)
Location: security/integrity/ima/ima_api.c:189
Inline: False
Direct callers:
  - security/integrity/ima/ima_main.c:process_buffer_measurement
  - security/integrity/ima/ima_main.c:ima_file_mprotect
  - security/integrity/ima/ima_main.c:process_measurement
```
**Symbols:**

```
ffffffff816416e0-ffffffff81641726: ima_get_action (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int ima_get_action(struct user_namespace *mnt_userns, struct inode *inode, const struct cred *cred, struct lsmblob *blob, int mask, enum ima_hooks func, int *pcr, struct ima_template_desc **template_desc, const char *func_data, unsigned int *allowed_algos);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/integrity/ima/ima_api.c (ffffffff816f96e0)
Location: security/integrity/ima/ima_api.c:189
Inline: False
Direct callers:
  - security/integrity/ima/ima_main.c:process_buffer_measurement
  - security/integrity/ima/ima_main.c:ima_file_mprotect
  - security/integrity/ima/ima_main.c:process_measurement
```
**Symbols:**

```
ffffffff816f96e0-ffffffff816f9726: ima_get_action (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int ima_get_action(struct mnt_idmap *idmap, struct inode *inode, const struct cred *cred, struct lsmblob *blob, int mask, enum ima_hooks func, int *pcr, struct ima_template_desc **template_desc, const char *func_data, unsigned int *allowed_algos);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/integrity/ima/ima_api.c (ffffffff81733860)
Location: security/integrity/ima/ima_api.c:189
Inline: False
Direct callers:
  - security/integrity/ima/ima_main.c:process_buffer_measurement
  - security/integrity/ima/ima_main.c:ima_file_mprotect
  - security/integrity/ima/ima_main.c:ima_file_mprotect
  - security/integrity/ima/ima_main.c:process_measurement
```
**Symbols:**

```
ffffffff81733860-ffffffff817338a6: ima_get_action (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int ima_get_action(struct mnt_idmap *idmap, struct inode *inode, const struct cred *cred, struct lsmblob *blob, int mask, enum ima_hooks func, int *pcr, struct ima_template_desc **template_desc, const char *func_data, unsigned int *allowed_algos);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/integrity/ima/ima_api.c (ffffffff81774280)
Location: security/integrity/ima/ima_api.c:189
Inline: False
Direct callers:
  - security/integrity/ima/ima_main.c:process_buffer_measurement
  - security/integrity/ima/ima_main.c:ima_file_mprotect
  - security/integrity/ima/ima_main.c:ima_file_mprotect
  - security/integrity/ima/ima_main.c:process_measurement
```
**Symbols:**

```
ffffffff81774280-ffffffff817742c6: ima_get_action (STB_GLOBAL)
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
int ima_get_action(struct inode *inode, const struct cred *cred, u32 secid, int mask, enum ima_hooks func, int *pcr, struct ima_template_desc **template_desc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/integrity/ima/ima_api.c (ffff8000105b0900)
Location: security/integrity/ima/ima_api.c:184
Inline: False
Direct callers:
  - security/integrity/ima/ima_main.c:process_buffer_measurement
  - security/integrity/ima/ima_main.c:process_measurement
```
**Symbols:**

```
ffff8000105b0900-ffff8000105b0984: ima_get_action (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int ima_get_action(struct inode *inode, const struct cred *cred, u32 secid, int mask, enum ima_hooks func, int *pcr, struct ima_template_desc **template_desc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/integrity/ima/ima_api.c (c075ffac)
Location: security/integrity/ima/ima_api.c:184
Inline: False
Direct callers:
  - security/integrity/ima/ima_main.c:process_buffer_measurement
  - security/integrity/ima/ima_main.c:process_measurement
```
**Symbols:**

```
c075ffac-c0760000: ima_get_action (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int ima_get_action(struct inode *inode, const struct cred *cred, u32 secid, int mask, enum ima_hooks func, int *pcr, struct ima_template_desc **template_desc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/integrity/ima/ima_api.c (c000000000730610)
Location: security/integrity/ima/ima_api.c:184
Inline: False
Direct callers:
  - security/integrity/ima/ima_main.c:process_buffer_measurement
  - security/integrity/ima/ima_main.c:process_measurement
```
**Symbols:**

```
c000000000730610-c000000000730668: ima_get_action (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int ima_get_action(struct inode *inode, const struct cred *cred, u32 secid, int mask, enum ima_hooks func, int *pcr, struct ima_template_desc **template_desc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/integrity/ima/ima_api.c (ffffffe0003f8482)
Location: security/integrity/ima/ima_api.c:184
Inline: False
Direct callers:
  - security/integrity/ima/ima_main.c:process_buffer_measurement
  - security/integrity/ima/ima_main.c:process_measurement
```
**Symbols:**

```
ffffffe0003f8482-ffffffe0003f84e8: ima_get_action (STB_GLOBAL)
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
int ima_get_action(struct inode *inode, const struct cred *cred, u32 secid, int mask, enum ima_hooks func, int *pcr, struct ima_template_desc **template_desc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/integrity/ima/ima_api.c (ffffffff814b0c10)
Location: security/integrity/ima/ima_api.c:184
Inline: False
Direct callers:
  - security/integrity/ima/ima_main.c:process_buffer_measurement
  - security/integrity/ima/ima_main.c:process_measurement
```
**Symbols:**

```
ffffffff814b0c10-ffffffff814b0c3c: ima_get_action (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int ima_get_action(struct inode *inode, const struct cred *cred, u32 secid, int mask, enum ima_hooks func, int *pcr, struct ima_template_desc **template_desc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/integrity/ima/ima_api.c (ffffffff814a1630)
Location: security/integrity/ima/ima_api.c:184
Inline: False
Direct callers:
  - security/integrity/ima/ima_main.c:process_buffer_measurement
  - security/integrity/ima/ima_main.c:process_measurement
```
**Symbols:**

```
ffffffff814a1630-ffffffff814a165c: ima_get_action (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int ima_get_action(struct inode *inode, const struct cred *cred, u32 secid, int mask, enum ima_hooks func, int *pcr, struct ima_template_desc **template_desc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/integrity/ima/ima_api.c (ffffffff814acca0)
Location: security/integrity/ima/ima_api.c:184
Inline: False
Direct callers:
  - security/integrity/ima/ima_main.c:process_buffer_measurement
  - security/integrity/ima/ima_main.c:process_measurement
```
**Symbols:**

```
ffffffff814acca0-ffffffff814acccc: ima_get_action (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int ima_get_action(struct inode *inode, const struct cred *cred, u32 secid, int mask, enum ima_hooks func, int *pcr, struct ima_template_desc **template_desc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/integrity/ima/ima_api.c (ffffffff814c56f0)
Location: security/integrity/ima/ima_api.c:184
Inline: False
Direct callers:
  - security/integrity/ima/ima_main.c:process_buffer_measurement
  - security/integrity/ima/ima_main.c:process_measurement
```
**Symbols:**

```
ffffffff814c56f0-ffffffff814c571c: ima_get_action (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
<details>
<summary>Changed between <code>4.4</code> and <code>4.8</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>enum ima_hooks func</code>
</li>
<li>
<b>Param added. </b>
<code>int *pcr</code>
</li>
<li>
<b>Param removed. </b>
<code>int function</code>
</li>
</ul>
</details>
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
<code>const struct cred *cred</code>
</li>
<li>
<b>Param added. </b>
<code>u32 secid</code>
</li>
<li>
<b>Param reordered. </b>
<code>inode, mask, func, pcr</code> ➡️ <code>inode, cred, secid, mask, func, pcr</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>4.18</code> and <code>5.0</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>5.0</code> and <code>5.3</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>struct ima_template_desc **template_desc</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>5.3</code> and <code>5.4</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>5.4</code> and <code>5.8</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>struct lsmblob *blob</code>
</li>
<li>
<b>Param added. </b>
<code>const char *keyring</code>
</li>
<li>
<b>Param removed. </b>
<code>u32 secid</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>5.8</code> and <code>5.11</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>5.11</code> and <code>5.13</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>struct user_namespace *mnt_userns</code>
</li>
<li>
<b>Param added. </b>
<code>const char *func_data</code>
</li>
<li>
<b>Param removed. </b>
<code>const char *keyring</code>
</li>
<li>
<b>Param reordered. </b>
<code>inode, cred, blob, mask, func, pcr, template_desc, keyring</code> ➡️ <code>mnt_userns, inode, cred, blob, mask, func, pcr, template_desc, func_data</code>
</li>
</ul>
</details>
</li>
<li>
<details>
<summary>Changed between <code>5.13</code> and <code>5.15</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>unsigned int *allowed_algos</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>5.15</code> and <code>5.19</code> ✅
</li>
<li>
No changes between <code>5.19</code> and <code>6.2</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>6.2</code> and <code>6.5</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>struct mnt_idmap *idmap</code>
</li>
<li>
<b>Param removed. </b>
<code>struct user_namespace *mnt_userns</code>
</li>
</ul>
</details>
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
