# Function: <code>security_inode_getsecid</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void security_inode_getsecid(const struct inode *inode, u32 *secid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff8133dd40)
Location: security/security.c:732
Inline: False
Direct callers:
  - kernel/audit.c:audit_copy_inode
  - security/integrity/ima/ima_policy.c:ima_match_policy
```
**Symbols:**

```
ffffffff8133dd40-ffffffff8133dd80: security_inode_getsecid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void security_inode_getsecid(struct inode *inode, u32 *secid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff813733a0)
Location: security/security.c:754
Inline: False
Direct callers:
  - kernel/audit.c:audit_copy_inode
  - security/integrity/ima/ima_policy.c:ima_match_policy
```
**Symbols:**

```
ffffffff813733a0-ffffffff813733e0: security_inode_getsecid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void security_inode_getsecid(struct inode *inode, u32 *secid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff81389cd0)
Location: security/security.c:763
Inline: False
Direct callers:
  - kernel/audit.c:audit_copy_inode
  - security/integrity/ima/ima_policy.c:ima_match_policy
```
**Symbols:**

```
ffffffff81389cd0-ffffffff81389d10: security_inode_getsecid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void security_inode_getsecid(struct inode *inode, u32 *secid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff8139f0a0)
Location: security/security.c:1368
Inline: False
Direct callers:
  - kernel/audit.c:audit_copy_inode
  - security/integrity/ima/ima_policy.c:ima_match_policy
```
**Symbols:**

```
ffffffff8139f0a0-ffffffff8139f0e0: security_inode_getsecid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void security_inode_getsecid(struct inode *inode, u32 *secid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff813c4b60)
Location: security/security.c:1317
Inline: False
Direct callers:
  - kernel/audit.c:audit_copy_inode
  - security/integrity/ima/ima_policy.c:ima_match_policy
```
**Symbols:**

```
ffffffff813c4b60-ffffffff813c4ba6: security_inode_getsecid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void security_inode_getsecid(struct inode *inode, u32 *secid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff813f4f00)
Location: security/security.c:859
Inline: False
Direct callers:
  - kernel/audit.c:audit_copy_inode
  - security/integrity/ima/ima_policy.c:ima_match_policy
```
**Symbols:**

```
ffffffff813f4f00-ffffffff813f4f3e: security_inode_getsecid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void security_inode_getsecid(struct inode *inode, u32 *secid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff814102d0)
Location: security/security.c:1380
Inline: False
Direct callers:
  - kernel/audit.c:audit_copy_inode
  - security/integrity/ima/ima_policy.c:ima_match_policy
```
**Symbols:**

```
ffffffff814102d0-ffffffff8141030e: security_inode_getsecid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void security_inode_getsecid(struct inode *inode, u32 *secid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff8143d9b0)
Location: security/security.c:1393
Inline: False
Direct callers:
  - kernel/auditsc.c:audit_copy_inode
  - security/integrity/ima/ima_policy.c:ima_match_policy
```
**Symbols:**

```
ffffffff8143d9b0-ffffffff8143d9f0: security_inode_getsecid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void security_inode_getsecid(struct inode *inode, u32 *secid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff81457400)
Location: security/security.c:1433
Inline: False
Direct callers:
  - kernel/auditsc.c:audit_copy_inode
  - security/integrity/ima/ima_policy.c:ima_match_policy
```
**Symbols:**

```
ffffffff81457400-ffffffff8145743e: security_inode_getsecid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void security_inode_getsecid(struct inode *inode, struct lsmblob *blob);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff814aa210)
Location: security/security.c:1581
Inline: False
Direct callers:
  - kernel/auditsc.c:__audit_inode_child
```
**Symbols:**

```
ffffffff814aa210-ffffffff814aa27d: security_inode_getsecid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void security_inode_getsecid(struct inode *inode, struct lsmblob *blob);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff814c7820)
Location: security/security.c:1583
Inline: False
Direct callers:
  - kernel/auditsc.c:__audit_inode_child
```
**Symbols:**

```
ffffffff814c7820-ffffffff814c788e: security_inode_getsecid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void security_inode_getsecid(struct inode *inode, struct lsmblob *blob);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff814cdcf0)
Location: security/security.c:1634
Inline: False
Direct callers:
  - kernel/auditsc.c:__audit_inode_child
```
**Symbols:**

```
ffffffff814cdcf0-ffffffff814cdd5e: security_inode_getsecid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void security_inode_getsecid(struct inode *inode, struct lsmblob *blob);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff81526c00)
Location: security/security.c:1641
Inline: False
Direct callers:
  - kernel/auditsc.c:__audit_inode_child
```
**Symbols:**

```
ffffffff81526c00-ffffffff81526c6e: security_inode_getsecid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void security_inode_getsecid(struct inode *inode, struct lsmblob *blob);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff815bb6a0)
Location: security/security.c:1647
Inline: False
Direct callers:
  - kernel/auditsc.c:__audit_inode_child
  - security/integrity/ima/ima_policy.c:ima_match_rules
```
**Symbols:**

```
ffffffff815bb6a0-ffffffff815bb718: security_inode_getsecid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void security_inode_getsecid(struct inode *inode, struct lsmblob *blob);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff81667460)
Location: security/security.c:1688
Inline: False
Direct callers:
  - kernel/auditsc.c:__audit_inode_child
  - security/integrity/ima/ima_policy.c:ima_match_rules
```
**Symbols:**

```
ffffffff81667460-ffffffff816674d8: security_inode_getsecid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void security_inode_getsecid(struct inode *inode, struct lsmblob *blob);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff8169fa50)
Location: security/security.c:2604
Inline: False
Direct callers:
  - kernel/auditsc.c:__audit_inode_child
  - security/integrity/ima/ima_policy.c:ima_match_rules
```
**Symbols:**

```
ffffffff8169fa50-ffffffff8169faf4: security_inode_getsecid (STB_GLOBAL)
```
</details>
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
void security_inode_getsecid(struct inode *inode, u32 *secid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffff800010542f88)
Location: security/security.c:1433
Inline: False
Direct callers:
  - kernel/auditsc.c:audit_copy_inode
  - security/integrity/ima/ima_policy.c:ima_match_policy
```
**Symbols:**

```
ffff800010542f88-ffff800010542fe0: security_inode_getsecid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void security_inode_getsecid(struct inode *inode, u32 *secid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (c06f8f1c)
Location: security/security.c:1433
Inline: False
Direct callers:
  - kernel/auditsc.c:audit_copy_inode
  - security/integrity/ima/ima_policy.c:ima_match_policy
```
**Symbols:**

```
c06f8f1c-c06f8f6c: security_inode_getsecid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void security_inode_getsecid(struct inode *inode, u32 *secid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (c000000000696b30)
Location: security/security.c:1433
Inline: False
Direct callers:
  - kernel/auditsc.c:audit_copy_inode
  - security/integrity/ima/ima_policy.c:ima_match_policy
```
**Symbols:**

```
c000000000696b30-c000000000696bc0: security_inode_getsecid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void security_inode_getsecid(struct inode *inode, u32 *secid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffe00039f622)
Location: security/security.c:1433
Inline: False
Direct callers:
  - kernel/auditsc.c:audit_copy_inode
  - security/integrity/ima/ima_policy.c:ima_match_policy
```
**Symbols:**

```
ffffffe00039f622-ffffffe00039f662: security_inode_getsecid (STB_GLOBAL)
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
void security_inode_getsecid(struct inode *inode, u32 *secid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff8144f9e0)
Location: security/security.c:1433
Inline: False
Direct callers:
  - kernel/auditsc.c:audit_copy_inode
  - security/integrity/ima/ima_policy.c:ima_match_policy
```
**Symbols:**

```
ffffffff8144f9e0-ffffffff8144fa1e: security_inode_getsecid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void security_inode_getsecid(struct inode *inode, u32 *secid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff81440430)
Location: security/security.c:1433
Inline: False
Direct callers:
  - kernel/auditsc.c:audit_copy_inode
  - security/integrity/ima/ima_policy.c:ima_match_policy
```
**Symbols:**

```
ffffffff81440430-ffffffff8144046e: security_inode_getsecid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void security_inode_getsecid(struct inode *inode, u32 *secid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff8144ba80)
Location: security/security.c:1433
Inline: False
Direct callers:
  - kernel/auditsc.c:audit_copy_inode
  - security/integrity/ima/ima_policy.c:ima_match_policy
```
**Symbols:**

```
ffffffff8144ba80-ffffffff8144babe: security_inode_getsecid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void security_inode_getsecid(struct inode *inode, u32 *secid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff81462e50)
Location: security/security.c:1433
Inline: False
Direct callers:
  - kernel/auditsc.c:audit_copy_inode
  - security/integrity/ima/ima_policy.c:ima_match_policy
```
**Symbols:**

```
ffffffff81462e50-ffffffff81462e8e: security_inode_getsecid (STB_GLOBAL)
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
<b>Param type changed. </b>
<code>const struct inode *inode</code> ➡️ <code>struct inode *inode</code>
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
<details>
<summary>Changed between <code>5.4</code> and <code>5.8</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>struct lsmblob *blob</code>
</li>
<li>
<b>Param removed. </b>
<code>u32 *secid</code>
</li>
</ul>
</details>
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
