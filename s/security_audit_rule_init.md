# Function: <code>security_audit_rule_init</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int security_audit_rule_init(u32 field, u32 op, char *rulestr, void **lsmrule);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff8133fac0)
Location: security/security.c:1528
Inline: False
Direct callers:
  - kernel/auditfilter.c:audit_dupe_rule
  - kernel/auditfilter.c:audit_rule_change
  - security/integrity/ima/ima_policy.c:ima_match_policy
```
**Symbols:**

```
ffffffff8133fac0-ffffffff8133fb27: security_audit_rule_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int security_audit_rule_init(u32 field, u32 op, char *rulestr, void **lsmrule);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff813750e0)
Location: security/security.c:1558
Inline: False
Direct callers:
  - kernel/auditfilter.c:audit_rule_change
  - kernel/auditfilter.c:audit_dupe_rule
  - security/integrity/ima/ima_policy.c:ima_match_policy
```
**Symbols:**

```
ffffffff813750e0-ffffffff81375147: security_audit_rule_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int security_audit_rule_init(u32 field, u32 op, char *rulestr, void **lsmrule);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff8138ba10)
Location: security/security.c:1579
Inline: False
Direct callers:
  - kernel/auditfilter.c:audit_rule_change
  - kernel/auditfilter.c:audit_dupe_rule
  - security/integrity/ima/ima_policy.c:ima_match_policy
```
**Symbols:**

```
ffffffff8138ba10-ffffffff8138ba77: security_audit_rule_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int security_audit_rule_init(u32 field, u32 op, char *rulestr, void **lsmrule);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff813a16a0)
Location: security/security.c:2561
Inline: False
Direct callers:
  - kernel/auditfilter.c:audit_rule_change
  - kernel/auditfilter.c:audit_dupe_rule
  - security/integrity/ima/ima_policy.c:ima_lsm_rule_init
  - security/integrity/ima/ima_policy.c:ima_match_policy
```
**Symbols:**

```
ffffffff813a16a0-ffffffff813a1707: security_audit_rule_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int security_audit_rule_init(u32 field, u32 op, char *rulestr, void **lsmrule);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff813c7250)
Location: security/security.c:2425
Inline: False
Direct callers:
  - kernel/auditfilter.c:audit_rule_change
  - kernel/auditfilter.c:audit_dupe_rule
  - security/integrity/ima/ima_policy.c:ima_lsm_rule_init
  - security/integrity/ima/ima_policy.c:ima_match_policy
```
**Symbols:**

```
ffffffff813c7250-ffffffff813c72bd: security_audit_rule_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int security_audit_rule_init(u32 field, u32 op, char *rulestr, void **lsmrule);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff813f6940)
Location: security/security.c:1738
Inline: False
Direct callers:
  - kernel/auditfilter.c:audit_rule_change
  - kernel/auditfilter.c:audit_dupe_rule
  - security/integrity/ima/ima_policy.c:ima_lsm_rule_init
  - security/integrity/ima/ima_policy.c:ima_match_policy
```
**Symbols:**

```
ffffffff813f6940-ffffffff813f6998: security_audit_rule_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int security_audit_rule_init(u32 field, u32 op, char *rulestr, void **lsmrule);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff814123f0)
Location: security/security.c:2498
Inline: False
Direct callers:
  - kernel/auditfilter.c:audit_rule_change
  - kernel/auditfilter.c:audit_dupe_rule
  - security/integrity/ima/ima_policy.c:ima_lsm_rule_init
  - security/integrity/ima/ima_policy.c:ima_match_policy
```
**Symbols:**

```
ffffffff814123f0-ffffffff81412448: security_audit_rule_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int security_audit_rule_init(u32 field, u32 op, char *rulestr, void **lsmrule);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff8143fd90)
Location: security/security.c:2517
Inline: False
Direct callers:
  - kernel/auditfilter.c:audit_dupe_rule
  - kernel/auditfilter.c:audit_data_to_entry
  - security/integrity/ima/ima_policy.c:ima_lsm_rule_init
  - security/integrity/ima/ima_policy.c:ima_lsm_policy_change
```
**Symbols:**

```
ffffffff8143fd90-ffffffff8143fdf5: security_audit_rule_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int security_audit_rule_init(u32 field, u32 op, char *rulestr, void **lsmrule);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff81459640)
Location: security/security.c:2556
Inline: False
Direct callers:
  - kernel/auditfilter.c:audit_dupe_rule
  - kernel/auditfilter.c:audit_data_to_entry
  - security/integrity/ima/ima_policy.c:ima_lsm_policy_change
```
**Symbols:**

```
ffffffff81459640-ffffffff81459698: security_audit_rule_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int security_audit_rule_init(u32 field, u32 op, char *rulestr, void **lsmrule);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff814ac6e0)
Location: security/security.c:2891
Inline: False
Direct callers:
  - kernel/auditfilter.c:audit_dupe_rule
  - kernel/auditfilter.c:audit_data_to_entry
  - security/integrity/ima/ima_policy.c:ima_lsm_rule_init
  - security/integrity/ima/ima_policy.c:ima_lsm_copy_rule
```
**Symbols:**

```
ffffffff814ac6e0-ffffffff814ac75c: security_audit_rule_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int security_audit_rule_init(u32 field, u32 op, char *rulestr, void **lsmrule);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff814c9ce0)
Location: security/security.c:2909
Inline: False
Direct callers:
  - kernel/auditfilter.c:audit_dupe_rule
  - kernel/auditfilter.c:audit_data_to_entry
  - security/integrity/ima/ima_policy.c:ima_lsm_rule_init
  - security/integrity/ima/ima_policy.c:ima_lsm_copy_rule
```
**Symbols:**

```
ffffffff814c9ce0-ffffffff814c9d5c: security_audit_rule_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int security_audit_rule_init(u32 field, u32 op, char *rulestr, void **lsmrule);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff814d0310)
Location: security/security.c:2972
Inline: False
Direct callers:
  - kernel/auditfilter.c:audit_dupe_rule
  - kernel/auditfilter.c:audit_data_to_entry
  - security/integrity/ima/ima_policy.c:ima_lsm_rule_init
  - security/integrity/ima/ima_policy.c:ima_lsm_update_rules
```
**Symbols:**

```
ffffffff814d0310-ffffffff814d038f: security_audit_rule_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int security_audit_rule_init(u32 field, u32 op, char *rulestr, void **lsmrule);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff81529040)
Location: security/security.c:2980
Inline: False
Direct callers:
  - kernel/auditfilter.c:audit_dupe_rule
  - kernel/auditfilter.c:audit_data_to_entry
  - security/integrity/ima/ima_policy.c:ima_lsm_rule_init
  - security/integrity/ima/ima_policy.c:ima_lsm_update_rules
```
**Symbols:**

```
ffffffff81529040-ffffffff815290bf: security_audit_rule_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int security_audit_rule_init(u32 field, u32 op, char *rulestr, struct audit_lsm_rules *lsmrules);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff815be4b0)
Location: security/security.c:3009
Inline: False
Direct callers:
  - kernel/auditfilter.c:audit_dupe_rule
  - kernel/auditfilter.c:audit_data_to_entry
```
**Symbols:**

```
ffffffff815be4b0-ffffffff815be55a: security_audit_rule_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int security_audit_rule_init(u32 field, u32 op, char *rulestr, struct audit_lsm_rules *lsmrules);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff8166a6c0)
Location: security/security.c:2989
Inline: False
Direct callers:
  - kernel/auditfilter.c:audit_dupe_rule
  - kernel/auditfilter.c:audit_data_to_entry
```
**Symbols:**

```
ffffffff8166a6c0-ffffffff8166a76a: security_audit_rule_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int security_audit_rule_init(u32 field, u32 op, char *rulestr, struct audit_lsm_rules *lsmrules);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff816a2d10)
Location: security/security.c:5349
Inline: False
Direct callers:
  - kernel/auditfilter.c:audit_dupe_rule
  - kernel/auditfilter.c:audit_data_to_entry
```
**Symbols:**

```
ffffffff816a2d10-ffffffff816a2de9: security_audit_rule_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int security_audit_rule_init(u32 field, u32 op, char *rulestr, void **lsmrule);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff816df8c0)
Location: security/security.c:5548
Inline: False
Direct callers:
  - kernel/auditfilter.c:audit_dupe_rule
  - kernel/auditfilter.c:audit_data_to_entry
```
**Symbols:**

```
ffffffff816df8c0-ffffffff816df946: security_audit_rule_init (STB_GLOBAL)
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
int security_audit_rule_init(u32 field, u32 op, char *rulestr, void **lsmrule);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffff8000105457c8)
Location: security/security.c:2556
Inline: False
Direct callers:
  - kernel/auditfilter.c:audit_dupe_rule
  - kernel/auditfilter.c:audit_data_to_entry
  - security/integrity/ima/ima_policy.c:ima_lsm_policy_change
```
**Symbols:**

```
ffff8000105457c8-ffff800010545844: security_audit_rule_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int security_audit_rule_init(u32 field, u32 op, char *rulestr, void **lsmrule);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (c06fb644)
Location: security/security.c:2556
Inline: False
Direct callers:
  - kernel/auditfilter.c:audit_dupe_rule
  - kernel/auditfilter.c:audit_data_to_entry
  - security/integrity/ima/ima_policy.c:ima_lsm_policy_change
```
**Symbols:**

```
c06fb644-c06fb6b0: security_audit_rule_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int security_audit_rule_init(u32 field, u32 op, char *rulestr, void **lsmrule);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (c00000000069bcc0)
Location: security/security.c:2556
Inline: False
Direct callers:
  - kernel/auditfilter.c:audit_dupe_rule
  - kernel/auditfilter.c:audit_data_to_entry
  - security/integrity/ima/ima_policy.c:ima_lsm_policy_change
```
**Symbols:**

```
c00000000069bcc0-c00000000069bda4: security_audit_rule_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int security_audit_rule_init(u32 field, u32 op, char *rulestr, void **lsmrule);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffe0003a149c)
Location: security/security.c:2556
Inline: False
Direct callers:
  - kernel/auditfilter.c:audit_dupe_rule
  - kernel/auditfilter.c:audit_data_to_entry
  - security/integrity/ima/ima_policy.c:ima_lsm_policy_change
```
**Symbols:**

```
ffffffe0003a149c-ffffffe0003a14f0: security_audit_rule_init (STB_GLOBAL)
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
int security_audit_rule_init(u32 field, u32 op, char *rulestr, void **lsmrule);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff81451c20)
Location: security/security.c:2556
Inline: False
Direct callers:
  - kernel/auditfilter.c:audit_dupe_rule
  - kernel/auditfilter.c:audit_data_to_entry
  - security/integrity/ima/ima_policy.c:ima_lsm_policy_change
```
**Symbols:**

```
ffffffff81451c20-ffffffff81451c78: security_audit_rule_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int security_audit_rule_init(u32 field, u32 op, char *rulestr, void **lsmrule);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff81442670)
Location: security/security.c:2556
Inline: False
Direct callers:
  - kernel/auditfilter.c:audit_dupe_rule
  - kernel/auditfilter.c:audit_data_to_entry
  - security/integrity/ima/ima_policy.c:ima_lsm_policy_change
```
**Symbols:**

```
ffffffff81442670-ffffffff814426c8: security_audit_rule_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int security_audit_rule_init(u32 field, u32 op, char *rulestr, void **lsmrule);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff8144dcc0)
Location: security/security.c:2556
Inline: False
Direct callers:
  - kernel/auditfilter.c:audit_dupe_rule
  - kernel/auditfilter.c:audit_data_to_entry
  - security/integrity/ima/ima_policy.c:ima_lsm_policy_change
```
**Symbols:**

```
ffffffff8144dcc0-ffffffff8144dd18: security_audit_rule_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int security_audit_rule_init(u32 field, u32 op, char *rulestr, void **lsmrule);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff81465090)
Location: security/security.c:2556
Inline: False
Direct callers:
  - kernel/auditfilter.c:audit_dupe_rule
  - kernel/auditfilter.c:audit_data_to_entry
  - security/integrity/ima/ima_policy.c:ima_lsm_policy_change
```
**Symbols:**

```
ffffffff81465090-ffffffff814650e8: security_audit_rule_init (STB_GLOBAL)
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
<code>void **lsmrule</code>
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
