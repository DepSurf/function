# Function: <code>ima_match_policy</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int ima_match_policy(struct inode *inode, enum ima_hooks func, int mask, int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/integrity/ima/ima_policy.c (ffffffff81399630)
Location: security/integrity/ima/ima_policy.c:326
Inline: False
Direct callers:
  - security/integrity/ima/ima_api.c:ima_get_action
  - security/integrity/ima/ima_appraise.c:ima_inode_post_setattr
```
**Symbols:**

```
ffffffff81399630-ffffffff813999b8: ima_match_policy (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int ima_match_policy(struct inode *inode, enum ima_hooks func, int mask, int flags, int *pcr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/integrity/ima/ima_policy.c (ffffffff813d5f00)
Location: security/integrity/ima/ima_policy.c:336
Inline: False
Direct callers:
  - security/integrity/ima/ima_api.c:ima_get_action
  - security/integrity/ima/ima_appraise.c:ima_inode_post_setattr
```
**Symbols:**

```
ffffffff813d5f00-ffffffff813d627d: ima_match_policy (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int ima_match_policy(struct inode *inode, enum ima_hooks func, int mask, int flags, int *pcr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/integrity/ima/ima_policy.c (ffffffff813ed7d0)
Location: security/integrity/ima/ima_policy.c:336
Inline: False
Direct callers:
  - security/integrity/ima/ima_api.c:ima_get_action
  - security/integrity/ima/ima_appraise.c:ima_inode_post_setattr
```
**Symbols:**

```
ffffffff813ed7d0-ffffffff813edb4d: ima_match_policy (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int ima_match_policy(struct inode *inode, enum ima_hooks func, int mask, int flags, int *pcr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/integrity/ima/ima_policy.c (ffffffff813f9c00)
Location: security/integrity/ima/ima_policy.c:365
Inline: False
Direct callers:
  - security/integrity/ima/ima_api.c:ima_get_action
  - security/integrity/ima/ima_appraise.c:ima_inode_post_setattr
```
**Symbols:**

```
ffffffff813f9c00-ffffffff813f9fa6: ima_match_policy (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int ima_match_policy(struct inode *inode, enum ima_hooks func, int mask, int flags, int *pcr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/integrity/ima/ima_policy.c (ffffffff81422090)
Location: security/integrity/ima/ima_policy.c:365
Inline: False
Direct callers:
  - security/integrity/ima/ima_api.c:ima_get_action
  - security/integrity/ima/ima_appraise.c:ima_inode_post_setattr
```
**Symbols:**

```
ffffffff81422090-ffffffff81422450: ima_match_policy (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int ima_match_policy(struct inode *inode, const struct cred *cred, u32 secid, enum ima_hooks func, int mask, int flags, int *pcr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/integrity/ima/ima_policy.c (ffffffff81454780)
Location: security/integrity/ima/ima_policy.c:382
Inline: False
Direct callers:
  - security/integrity/ima/ima_api.c:ima_get_action
```
**Symbols:**

```
ffffffff81454780-ffffffff81454b8f: ima_match_policy (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int ima_match_policy(struct inode *inode, const struct cred *cred, u32 secid, enum ima_hooks func, int mask, int flags, int *pcr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/integrity/ima/ima_policy.c (ffffffff81471a50)
Location: security/integrity/ima/ima_policy.c:410
Inline: False
Direct callers:
  - security/integrity/ima/ima_api.c:ima_get_action
```
**Symbols:**

```
ffffffff81471a50-ffffffff81471e5f: ima_match_policy (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int ima_match_policy(struct inode *inode, const struct cred *cred, u32 secid, enum ima_hooks func, int mask, int flags, int *pcr, struct ima_template_desc **template_desc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/integrity/ima/ima_policy.c (ffffffff8149f6a0)
Location: security/integrity/ima/ima_policy.c:487
Inline: False
Direct callers:
  - security/integrity/ima/ima_api.c:ima_get_action
```
**Symbols:**

```
ffffffff8149f6a0-ffffffff8149fac4: ima_match_policy (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int ima_match_policy(struct inode *inode, const struct cred *cred, u32 secid, enum ima_hooks func, int mask, int flags, int *pcr, struct ima_template_desc **template_desc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/integrity/ima/ima_policy.c (ffffffff814b9c70)
Location: security/integrity/ima/ima_policy.c:492
Inline: False
Direct callers:
  - security/integrity/ima/ima_api.c:ima_get_action
```
**Symbols:**

```
ffffffff814b9c70-ffffffff814ba073: ima_match_policy (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int ima_match_policy(struct inode *inode, const struct cred *cred, struct lsmblob *blob, enum ima_hooks func, int mask, int flags, int *pcr, struct ima_template_desc **template_desc, const char *keyring);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/integrity/ima/ima_policy.c (ffffffff8151a120)
Location: security/integrity/ima/ima_policy.c:595
Inline: False
Direct callers:
  - security/integrity/ima/ima_api.c:ima_get_action
  - security/integrity/ima/ima_appraise.c:ima_inode_post_setattr
```
**Symbols:**

```
ffffffff8151a120-ffffffff8151a286: ima_match_policy (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int ima_match_policy(struct inode *inode, const struct cred *cred, struct lsmblob *blob, enum ima_hooks func, int mask, int flags, int *pcr, struct ima_template_desc **template_desc, const char *keyring);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/integrity/ima/ima_policy.c (ffffffff81537180)
Location: security/integrity/ima/ima_policy.c:641
Inline: False
Direct callers:
  - security/integrity/ima/ima_api.c:ima_get_action
  - security/integrity/ima/ima_appraise.c:ima_inode_post_setattr
```
**Symbols:**

```
ffffffff81537180-ffffffff81537306: ima_match_policy (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int ima_match_policy(struct user_namespace *mnt_userns, struct inode *inode, const struct cred *cred, struct lsmblob *blob, enum ima_hooks func, int mask, int flags, int *pcr, struct ima_template_desc **template_desc, const char *func_data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/integrity/ima/ima_policy.c (ffffffff8153f870)
Location: security/integrity/ima/ima_policy.c:675
Inline: False
Direct callers:
  - security/integrity/ima/ima_api.c:ima_get_action
  - security/integrity/ima/ima_appraise.c:ima_inode_post_setattr
```
**Symbols:**

```
ffffffff8153f870-ffffffff8153f9f9: ima_match_policy (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int ima_match_policy(struct user_namespace *mnt_userns, struct inode *inode, const struct cred *cred, struct lsmblob *blob, enum ima_hooks func, int mask, int flags, int *pcr, struct ima_template_desc **template_desc, const char *func_data, unsigned int *allowed_algos);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In security/integrity/ima/ima_policy.c (0)
Location: security/integrity/ima/ima_policy.c:688
Inline: False
Direct callers:
  - security/integrity/ima/ima_api.c:ima_get_action
  - security/integrity/ima/ima_appraise.c:ima_inode_post_setattr
```
**Symbols:**

```
ffffffff81cd717b-ffffffff81cd71a6: ima_match_policy.cold (STB_LOCAL)
ffffffff8159ede0-ffffffff8159efa6: ima_match_policy (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int ima_match_policy(struct user_namespace *mnt_userns, struct inode *inode, const struct cred *cred, struct lsmblob *blob, enum ima_hooks func, int mask, int flags, int *pcr, struct ima_template_desc **template_desc, const char *func_data, unsigned int *allowed_algos);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In security/integrity/ima/ima_policy.c (0)
Location: security/integrity/ima/ima_policy.c:722
Inline: False
Direct callers:
  - security/integrity/ima/ima_api.c:ima_get_action
  - security/integrity/ima/ima_appraise.c:ima_inode_post_setattr
```
**Symbols:**

```
ffffffff81e8a402-ffffffff81e8a41d: ima_match_policy.cold (STB_LOCAL)
ffffffff81644710-ffffffff81644919: ima_match_policy (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
int ima_match_policy(struct user_namespace *mnt_userns, struct inode *inode, const struct cred *cred, struct lsmblob *blob, enum ima_hooks func, int mask, int flags, int *pcr, struct ima_template_desc **template_desc, const char *func_data, unsigned int *allowed_algos);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In security/integrity/ima/ima_policy.c (0)
Location: security/integrity/ima/ima_policy.c:769
Inline: False
Direct callers:
  - security/integrity/ima/ima_api.c:ima_get_action
  - security/integrity/ima/ima_appraise.c:ima_inode_post_setattr
```
**Symbols:**

```
ffffffff820753f5-ffffffff82075410: ima_match_policy.cold (STB_LOCAL)
ffffffff816fcb80-ffffffff816fcd89: ima_match_policy (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
int ima_match_policy(struct mnt_idmap *idmap, struct inode *inode, const struct cred *cred, struct lsmblob *blob, enum ima_hooks func, int mask, int flags, int *pcr, struct ima_template_desc **template_desc, const char *func_data, unsigned int *allowed_algos);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In security/integrity/ima/ima_policy.c (0)
Location: security/integrity/ima/ima_policy.c:771
Inline: False
Direct callers:
  - security/integrity/ima/ima_api.c:ima_get_action
  - security/integrity/ima/ima_appraise.c:ima_inode_post_setattr
```
**Symbols:**

```
ffffffff820f4f5d-ffffffff820f4f78: ima_match_policy.cold (STB_LOCAL)
ffffffff81736bb0-ffffffff81736db1: ima_match_policy (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
int ima_match_policy(struct mnt_idmap *idmap, struct inode *inode, const struct cred *cred, struct lsmblob *blob, enum ima_hooks func, int mask, int flags, int *pcr, struct ima_template_desc **template_desc, const char *func_data, unsigned int *allowed_algos);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In security/integrity/ima/ima_policy.c (0)
Location: security/integrity/ima/ima_policy.c:764
Inline: False
Direct callers:
  - security/integrity/ima/ima_api.c:ima_get_action
  - security/integrity/ima/ima_appraise.c:ima_inode_post_setattr
```
**Symbols:**

```
ffffffff821d20eb-ffffffff821d2106: ima_match_policy.cold (STB_LOCAL)
ffffffff81777670-ffffffff81777871: ima_match_policy (STB_GLOBAL)
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
int ima_match_policy(struct inode *inode, const struct cred *cred, u32 secid, enum ima_hooks func, int mask, int flags, int *pcr, struct ima_template_desc **template_desc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/integrity/ima/ima_policy.c (ffff8000105b2028)
Location: security/integrity/ima/ima_policy.c:492
Inline: False
Direct callers:
  - security/integrity/ima/ima_api.c:ima_get_action
```
**Symbols:**

```
ffff8000105b2028-ffff8000105b23fc: ima_match_policy (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int ima_match_policy(struct inode *inode, const struct cred *cred, u32 secid, enum ima_hooks func, int mask, int flags, int *pcr, struct ima_template_desc **template_desc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/integrity/ima/ima_policy.c (c07616a0)
Location: security/integrity/ima/ima_policy.c:492
Inline: False
Direct callers:
  - security/integrity/ima/ima_api.c:ima_get_action
```
**Symbols:**

```
c07616a0-c0761aec: ima_match_policy (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int ima_match_policy(struct inode *inode, const struct cred *cred, u32 secid, enum ima_hooks func, int mask, int flags, int *pcr, struct ima_template_desc **template_desc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/integrity/ima/ima_policy.c (c0000000007332b0)
Location: security/integrity/ima/ima_policy.c:492
Inline: False
Direct callers:
  - security/integrity/ima/ima_api.c:ima_get_action
```
**Symbols:**

```
c0000000007332b0-c0000000007339e4: ima_match_policy (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int ima_match_policy(struct inode *inode, const struct cred *cred, u32 secid, enum ima_hooks func, int mask, int flags, int *pcr, struct ima_template_desc **template_desc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/integrity/ima/ima_policy.c (ffffffe0003f9920)
Location: security/integrity/ima/ima_policy.c:492
Inline: False
Direct callers:
  - security/integrity/ima/ima_api.c:ima_get_action
```
**Symbols:**

```
ffffffe0003f9920-ffffffe0003f9c72: ima_match_policy (STB_GLOBAL)
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
int ima_match_policy(struct inode *inode, const struct cred *cred, u32 secid, enum ima_hooks func, int mask, int flags, int *pcr, struct ima_template_desc **template_desc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/integrity/ima/ima_policy.c (ffffffff814b2250)
Location: security/integrity/ima/ima_policy.c:492
Inline: False
Direct callers:
  - security/integrity/ima/ima_api.c:ima_get_action
```
**Symbols:**

```
ffffffff814b2250-ffffffff814b2653: ima_match_policy (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int ima_match_policy(struct inode *inode, const struct cred *cred, u32 secid, enum ima_hooks func, int mask, int flags, int *pcr, struct ima_template_desc **template_desc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/integrity/ima/ima_policy.c (ffffffff814a2c70)
Location: security/integrity/ima/ima_policy.c:492
Inline: False
Direct callers:
  - security/integrity/ima/ima_api.c:ima_get_action
```
**Symbols:**

```
ffffffff814a2c70-ffffffff814a3073: ima_match_policy (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int ima_match_policy(struct inode *inode, const struct cred *cred, u32 secid, enum ima_hooks func, int mask, int flags, int *pcr, struct ima_template_desc **template_desc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/integrity/ima/ima_policy.c (ffffffff814ae2e0)
Location: security/integrity/ima/ima_policy.c:492
Inline: False
Direct callers:
  - security/integrity/ima/ima_api.c:ima_get_action
```
**Symbols:**

```
ffffffff814ae2e0-ffffffff814ae6e3: ima_match_policy (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int ima_match_policy(struct inode *inode, const struct cred *cred, u32 secid, enum ima_hooks func, int mask, int flags, int *pcr, struct ima_template_desc **template_desc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/integrity/ima/ima_policy.c (ffffffff814c6d30)
Location: security/integrity/ima/ima_policy.c:492
Inline: False
Direct callers:
  - security/integrity/ima/ima_api.c:ima_get_action
```
**Symbols:**

```
ffffffff814c6d30-ffffffff814c713d: ima_match_policy (STB_GLOBAL)
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
<code>int *pcr</code>
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
<code>inode, func, mask, flags, pcr</code> ➡️ <code>inode, cred, secid, func, mask, flags, pcr</code>
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
<code>inode, cred, blob, func, mask, flags, pcr, template_desc, keyring</code> ➡️ <code>mnt_userns, inode, cred, blob, func, mask, flags, pcr, template_desc, func_data</code>
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
