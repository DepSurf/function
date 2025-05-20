# Function: <code>security_audit_rule_match</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int security_audit_rule_match(u32 secid, u32 field, u32 op, void *lsmrule, struct audit_context *actx);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff8133fbc0)
Location: security/security.c:1543
Inline: False
Direct callers:
  - kernel/auditfilter.c:audit_filter_user
  - kernel/auditsc.c:audit_filter_rules
  - kernel/auditsc.c:audit_filter_rules
  - kernel/auditsc.c:audit_filter_rules
  - kernel/auditsc.c:audit_filter_rules
  - security/integrity/ima/ima_policy.c:ima_match_policy
  - security/integrity/ima/ima_policy.c:ima_match_policy
```
**Symbols:**

```
ffffffff8133fbc0-ffffffff8133fc3b: security_audit_rule_match (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int security_audit_rule_match(u32 secid, u32 field, u32 op, void *lsmrule, struct audit_context *actx);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff813751e0)
Location: security/security.c:1573
Inline: False
Direct callers:
  - kernel/auditfilter.c:audit_filter
  - security/integrity/ima/ima_policy.c:ima_match_policy
  - security/integrity/ima/ima_policy.c:ima_match_policy
```
**Symbols:**

```
ffffffff813751e0-ffffffff8137525b: security_audit_rule_match (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int security_audit_rule_match(u32 secid, u32 field, u32 op, void *lsmrule, struct audit_context *actx);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff8138bb10)
Location: security/security.c:1594
Inline: False
Direct callers:
  - kernel/auditfilter.c:audit_filter
  - security/integrity/ima/ima_policy.c:ima_match_policy
  - security/integrity/ima/ima_policy.c:ima_match_policy
```
**Symbols:**

```
ffffffff8138bb10-ffffffff8138bb8b: security_audit_rule_match (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int security_audit_rule_match(u32 secid, u32 field, u32 op, void *lsmrule, struct audit_context *actx);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff813a17a0)
Location: security/security.c:2576
Inline: False
Direct callers:
  - kernel/auditfilter.c:audit_filter
  - security/integrity/ima/ima_policy.c:ima_match_policy
  - security/integrity/ima/ima_policy.c:ima_match_policy
```
**Symbols:**

```
ffffffff813a17a0-ffffffff813a181b: security_audit_rule_match (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int security_audit_rule_match(u32 secid, u32 field, u32 op, void *lsmrule, struct audit_context *actx);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff813c7350)
Location: security/security.c:2440
Inline: False
Direct callers:
  - kernel/auditfilter.c:audit_filter
  - security/integrity/ima/ima_policy.c:ima_match_policy
  - security/integrity/ima/ima_policy.c:ima_match_policy
```
**Symbols:**

```
ffffffff813c7350-ffffffff813c73d1: security_audit_rule_match (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int security_audit_rule_match(u32 secid, u32 field, u32 op, void *lsmrule, struct audit_context *actx);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff813f6a20)
Location: security/security.c:1753
Inline: False
Direct callers:
  - kernel/auditfilter.c:audit_filter
  - security/integrity/ima/ima_policy.c:ima_match_policy
  - security/integrity/ima/ima_policy.c:ima_match_policy
```
**Symbols:**

```
ffffffff813f6a20-ffffffff813f6a88: security_audit_rule_match (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int security_audit_rule_match(u32 secid, u32 field, u32 op, void *lsmrule, struct audit_context *actx);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff814124d0)
Location: security/security.c:2513
Inline: False
Direct callers:
  - kernel/auditfilter.c:audit_filter
  - security/integrity/ima/ima_policy.c:ima_match_policy
  - security/integrity/ima/ima_policy.c:ima_match_policy
```
**Symbols:**

```
ffffffff814124d0-ffffffff81412538: security_audit_rule_match (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int security_audit_rule_match(u32 secid, u32 field, u32 op, void *lsmrule);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff8143fe90)
Location: security/security.c:2532
Inline: False
Direct callers:
  - kernel/auditfilter.c:audit_filter
  - security/integrity/ima/ima_policy.c:ima_match_policy
  - security/integrity/ima/ima_policy.c:ima_match_policy
```
**Symbols:**

```
ffffffff8143fe90-ffffffff8143fef5: security_audit_rule_match (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int security_audit_rule_match(u32 secid, u32 field, u32 op, void *lsmrule);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff81459720)
Location: security/security.c:2571
Inline: False
Direct callers:
  - kernel/auditfilter.c:audit_filter
  - security/integrity/ima/ima_policy.c:ima_match_policy
  - security/integrity/ima/ima_policy.c:ima_match_policy
```
**Symbols:**

```
ffffffff81459720-ffffffff81459778: security_audit_rule_match (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int security_audit_rule_match(struct lsmblob *blob, u32 field, u32 op, void **lsmrule);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff814ac800)
Location: security/security.c:2925
Inline: False
Direct callers:
  - kernel/auditfilter.c:audit_filter
```
**Symbols:**

```
ffffffff814ac800-ffffffff814ac883: security_audit_rule_match (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int security_audit_rule_match(struct lsmblob *blob, u32 field, u32 op, void **lsmrule);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff814c9e00)
Location: security/security.c:2943
Inline: False
Direct callers:
  - kernel/auditfilter.c:audit_filter
```
**Symbols:**

```
ffffffff814c9e00-ffffffff814c9e83: security_audit_rule_match (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int security_audit_rule_match(struct lsmblob *blob, u32 field, u32 op, void **lsmrule);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff814d0430)
Location: security/security.c:3006
Inline: False
Direct callers:
  - kernel/auditfilter.c:audit_filter
```
**Symbols:**

```
ffffffff814d0430-ffffffff814d04b3: security_audit_rule_match (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int security_audit_rule_match(struct lsmblob *blob, u32 field, u32 op, void **lsmrule);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff81529160)
Location: security/security.c:3014
Inline: False
Direct callers:
  - kernel/auditfilter.c:audit_filter
```
**Symbols:**

```
ffffffff81529160-ffffffff815291e3: security_audit_rule_match (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int security_audit_rule_match(struct lsmblob *blob, u32 field, u32 op, struct audit_lsm_rules *lsmrules);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff815be620)
Location: security/security.c:3050
Inline: False
Direct callers:
  - kernel/auditfilter.c:audit_filter
```
**Symbols:**

```
ffffffff815be620-ffffffff815be6bb: security_audit_rule_match (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int security_audit_rule_match(struct lsmblob *blob, u32 field, u32 op, struct audit_lsm_rules *lsmrules);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff8166a860)
Location: security/security.c:3030
Inline: False
Direct callers:
  - kernel/auditfilter.c:audit_filter
```
**Symbols:**

```
ffffffff8166a860-ffffffff8166a8fb: security_audit_rule_match (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int security_audit_rule_match(struct lsmblob *blob, u32 field, u32 op, struct audit_lsm_rules *lsmrules);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff816a2f20)
Location: security/security.c:5419
Inline: False
Direct callers:
  - kernel/auditfilter.c:audit_filter
```
**Symbols:**

```
ffffffff816a2f20-ffffffff816a302c: security_audit_rule_match (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int security_audit_rule_match(struct lsmblob *blob, u32 field, u32 op, void *lsmrule);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff816dfa10)
Location: security/security.c:5593
Inline: False
Direct callers:
  - kernel/auditfilter.c:audit_filter
```
**Symbols:**

```
ffffffff816dfa10-ffffffff816dfa96: security_audit_rule_match (STB_GLOBAL)
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
int security_audit_rule_match(u32 secid, u32 field, u32 op, void *lsmrule);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffff8000105458e0)
Location: security/security.c:2571
Inline: False
Direct callers:
  - kernel/auditfilter.c:audit_filter
  - security/integrity/ima/ima_policy.c:ima_match_policy
  - security/integrity/ima/ima_policy.c:ima_match_policy
```
**Symbols:**

```
ffff8000105458e0-ffff800010545954: security_audit_rule_match (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int security_audit_rule_match(u32 secid, u32 field, u32 op, void *lsmrule);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (c06fb74c)
Location: security/security.c:2571
Inline: False
Direct callers:
  - kernel/auditfilter.c:audit_filter
  - security/integrity/ima/ima_policy.c:ima_match_policy
  - security/integrity/ima/ima_policy.c:ima_match_policy
```
**Symbols:**

```
c06fb74c-c06fb7b8: security_audit_rule_match (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int security_audit_rule_match(u32 secid, u32 field, u32 op, void *lsmrule);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (c00000000069bee0)
Location: security/security.c:2571
Inline: False
Direct callers:
  - kernel/auditfilter.c:audit_filter
  - security/integrity/ima/ima_policy.c:ima_match_policy
  - security/integrity/ima/ima_policy.c:ima_match_policy
```
**Symbols:**

```
c00000000069bee0-c00000000069bfc4: security_audit_rule_match (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int security_audit_rule_match(u32 secid, u32 field, u32 op, void *lsmrule);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffe0003a1564)
Location: security/security.c:2571
Inline: False
Direct callers:
  - kernel/auditfilter.c:audit_filter
  - security/integrity/ima/ima_policy.c:ima_match_policy
  - security/integrity/ima/ima_policy.c:ima_match_policy
```
**Symbols:**

```
ffffffe0003a1564-ffffffe0003a15b8: security_audit_rule_match (STB_GLOBAL)
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
int security_audit_rule_match(u32 secid, u32 field, u32 op, void *lsmrule);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff81451d00)
Location: security/security.c:2571
Inline: False
Direct callers:
  - kernel/auditfilter.c:audit_filter
  - security/integrity/ima/ima_policy.c:ima_match_policy
  - security/integrity/ima/ima_policy.c:ima_match_policy
```
**Symbols:**

```
ffffffff81451d00-ffffffff81451d58: security_audit_rule_match (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int security_audit_rule_match(u32 secid, u32 field, u32 op, void *lsmrule);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff81442750)
Location: security/security.c:2571
Inline: False
Direct callers:
  - kernel/auditfilter.c:audit_filter
  - security/integrity/ima/ima_policy.c:ima_match_policy
  - security/integrity/ima/ima_policy.c:ima_match_policy
```
**Symbols:**

```
ffffffff81442750-ffffffff814427a8: security_audit_rule_match (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int security_audit_rule_match(u32 secid, u32 field, u32 op, void *lsmrule);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff8144dda0)
Location: security/security.c:2571
Inline: False
Direct callers:
  - kernel/auditfilter.c:audit_filter
  - security/integrity/ima/ima_policy.c:ima_match_policy
  - security/integrity/ima/ima_policy.c:ima_match_policy
```
**Symbols:**

```
ffffffff8144dda0-ffffffff8144ddf8: security_audit_rule_match (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int security_audit_rule_match(u32 secid, u32 field, u32 op, void *lsmrule);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff81465170)
Location: security/security.c:2571
Inline: False
Direct callers:
  - kernel/auditfilter.c:audit_filter
  - security/integrity/ima/ima_policy.c:ima_match_policy
  - security/integrity/ima/ima_policy.c:ima_match_policy
```
**Symbols:**

```
ffffffff81465170-ffffffff814651c8: security_audit_rule_match (STB_GLOBAL)
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
<details>
<summary>Changed between <code>5.0</code> and <code>5.3</code> ⚠️</summary>
<ul>
<li>
<b>Param removed. </b>
<code>struct audit_context *actx</code>
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
<b>Param removed. </b>
<code>u32 secid</code>
</li>
<li>
<b>Param type changed. </b>
<code>void *lsmrule</code> ➡️ <code>void **lsmrule</code>
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
<details>
<summary>Changed between <code>5.15</code> and <code>5.19</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>struct audit_lsm_rules *lsmrules</code>
</li>
<li>
<b>Param removed. </b>
<code>void **lsmrule</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>5.19</code> and <code>6.2</code> ✅
</li>
<li>
No changes between <code>6.2</code> and <code>6.5</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>6.5</code> and <code>6.8</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>void *lsmrule</code>
</li>
<li>
<b>Param removed. </b>
<code>struct audit_lsm_rules *lsmrules</code>
</li>
</ul>
</details>
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
