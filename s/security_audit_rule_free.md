# Function: <code>security_audit_rule_free</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void security_audit_rule_free(void *lsmrule);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff8133fb80)
Location: security/security.c:1538
Inline: False
Direct callers:
  - kernel/auditfilter.c:audit_free_rule_rcu
  - kernel/auditfilter.c:audit_dupe_rule
  - kernel/auditfilter.c:audit_rule_change
  - kernel/auditfilter.c:audit_rule_change
```
**Symbols:**

```
ffffffff8133fb80-ffffffff8133fbb6: security_audit_rule_free (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void security_audit_rule_free(void *lsmrule);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff813751a0)
Location: security/security.c:1568
Inline: False
Direct callers:
  - kernel/auditfilter.c:audit_rule_change
  - kernel/auditfilter.c:audit_rule_change
  - kernel/auditfilter.c:audit_dupe_rule
  - kernel/auditfilter.c:audit_free_rule_rcu
```
**Symbols:**

```
ffffffff813751a0-ffffffff813751d6: security_audit_rule_free (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void security_audit_rule_free(void *lsmrule);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff8138bad0)
Location: security/security.c:1589
Inline: False
Direct callers:
  - kernel/auditfilter.c:audit_rule_change
  - kernel/auditfilter.c:audit_rule_change
  - kernel/auditfilter.c:audit_dupe_rule
  - kernel/auditfilter.c:audit_free_rule_rcu
```
**Symbols:**

```
ffffffff8138bad0-ffffffff8138bb06: security_audit_rule_free (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void security_audit_rule_free(void *lsmrule);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff813a1760)
Location: security/security.c:2571
Inline: False
Direct callers:
  - kernel/auditfilter.c:audit_rule_change
  - kernel/auditfilter.c:audit_rule_change
  - kernel/auditfilter.c:audit_dupe_rule
  - kernel/auditfilter.c:audit_free_rule_rcu
```
**Symbols:**

```
ffffffff813a1760-ffffffff813a1796: security_audit_rule_free (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void security_audit_rule_free(void *lsmrule);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff813c7310)
Location: security/security.c:2435
Inline: False
Direct callers:
  - kernel/auditfilter.c:audit_rule_change
  - kernel/auditfilter.c:audit_rule_change
  - kernel/auditfilter.c:audit_dupe_rule
  - kernel/auditfilter.c:audit_free_rule_rcu
```
**Symbols:**

```
ffffffff813c7310-ffffffff813c734c: security_audit_rule_free (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void security_audit_rule_free(void *lsmrule);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff813f69e0)
Location: security/security.c:1748
Inline: False
Direct callers:
  - kernel/auditfilter.c:audit_rule_change
  - kernel/auditfilter.c:audit_rule_change
  - kernel/auditfilter.c:audit_dupe_rule
  - kernel/auditfilter.c:audit_free_rule_rcu
```
**Symbols:**

```
ffffffff813f69e0-ffffffff813f6a14: security_audit_rule_free (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void security_audit_rule_free(void *lsmrule);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff81412490)
Location: security/security.c:2508
Inline: False
Direct callers:
  - kernel/auditfilter.c:audit_rule_change
  - kernel/auditfilter.c:audit_rule_change
  - kernel/auditfilter.c:audit_dupe_rule
  - kernel/auditfilter.c:audit_free_rule_rcu
```
**Symbols:**

```
ffffffff81412490-ffffffff814124c4: security_audit_rule_free (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void security_audit_rule_free(void *lsmrule);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff8143fe50)
Location: security/security.c:2527
Inline: False
Direct callers:
  - kernel/auditfilter.c:audit_rule_change
  - kernel/auditfilter.c:audit_dupe_rule
  - kernel/auditfilter.c:audit_data_to_entry
  - kernel/auditfilter.c:audit_free_rule_rcu
```
**Symbols:**

```
ffffffff8143fe50-ffffffff8143fe86: security_audit_rule_free (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void security_audit_rule_free(void *lsmrule);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff814596e0)
Location: security/security.c:2566
Inline: False
Direct callers:
  - kernel/auditfilter.c:audit_rule_change
  - kernel/auditfilter.c:audit_dupe_rule
  - kernel/auditfilter.c:audit_data_to_entry
  - kernel/auditfilter.c:audit_free_rule_rcu
```
**Symbols:**

```
ffffffff814596e0-ffffffff81459714: security_audit_rule_free (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void security_audit_rule_free(void **lsmrule);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff814ac7a0)
Location: security/security.c:2912
Inline: False
Direct callers:
  - kernel/auditfilter.c:audit_rule_change
  - kernel/auditfilter.c:audit_dupe_rule
  - kernel/auditfilter.c:audit_data_to_entry
  - kernel/auditfilter.c:audit_free_rule_rcu
  - security/integrity/ima/ima_policy.c:ima_delete_rules
  - security/integrity/ima/ima_policy.c:ima_delete_rules
  - security/integrity/ima/ima_policy.c:ima_delete_rules
  - security/integrity/ima/ima_policy.c:ima_parse_add_rule
  - security/integrity/ima/ima_policy.c:ima_parse_add_rule
  - security/integrity/ima/ima_policy.c:ima_parse_add_rule
  - security/integrity/ima/ima_policy.c:ima_lsm_update_rules
  - security/integrity/ima/ima_policy.c:ima_lsm_update_rules
  - security/integrity/ima/ima_policy.c:ima_lsm_update_rules
  - security/integrity/ima/ima_policy.c:ima_lsm_copy_rule
  - security/integrity/ima/ima_policy.c:ima_lsm_copy_rule
  - security/integrity/ima/ima_policy.c:ima_lsm_copy_rule
```
**Symbols:**

```
ffffffff814ac7a0-ffffffff814ac7fa: security_audit_rule_free (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void security_audit_rule_free(void **lsmrule);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff814c9da0)
Location: security/security.c:2930
Inline: False
Direct callers:
  - kernel/auditfilter.c:audit_rule_change
  - kernel/auditfilter.c:audit_dupe_rule
  - kernel/auditfilter.c:audit_data_to_entry
  - kernel/auditfilter.c:audit_free_rule_rcu
  - security/integrity/ima/ima_policy.c:ima_delete_rules
  - security/integrity/ima/ima_policy.c:ima_delete_rules
  - security/integrity/ima/ima_policy.c:ima_delete_rules
  - security/integrity/ima/ima_policy.c:ima_delete_rules
  - security/integrity/ima/ima_policy.c:ima_parse_add_rule
  - security/integrity/ima/ima_policy.c:ima_parse_add_rule
  - security/integrity/ima/ima_policy.c:ima_parse_add_rule
  - security/integrity/ima/ima_policy.c:ima_parse_add_rule
  - security/integrity/ima/ima_policy.c:ima_lsm_update_rules
  - security/integrity/ima/ima_policy.c:ima_lsm_update_rules
  - security/integrity/ima/ima_policy.c:ima_lsm_update_rules
  - security/integrity/ima/ima_policy.c:ima_lsm_update_rules
```
**Symbols:**

```
ffffffff814c9da0-ffffffff814c9dfa: security_audit_rule_free (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void security_audit_rule_free(void **lsmrule);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff814d03d0)
Location: security/security.c:2993
Inline: False
Direct callers:
  - kernel/auditfilter.c:audit_rule_change
  - kernel/auditfilter.c:audit_dupe_rule
  - kernel/auditfilter.c:audit_data_to_entry
  - kernel/auditfilter.c:audit_free_rule_rcu
  - security/integrity/ima/ima_policy.c:ima_delete_rules
  - security/integrity/ima/ima_policy.c:ima_delete_rules
  - security/integrity/ima/ima_policy.c:ima_delete_rules
  - security/integrity/ima/ima_policy.c:ima_delete_rules
  - security/integrity/ima/ima_policy.c:ima_parse_add_rule
  - security/integrity/ima/ima_policy.c:ima_parse_add_rule
  - security/integrity/ima/ima_policy.c:ima_parse_add_rule
  - security/integrity/ima/ima_policy.c:ima_parse_add_rule
  - security/integrity/ima/ima_policy.c:ima_lsm_update_rules
  - security/integrity/ima/ima_policy.c:ima_lsm_update_rules
  - security/integrity/ima/ima_policy.c:ima_lsm_update_rules
  - security/integrity/ima/ima_policy.c:ima_lsm_update_rules
```
**Symbols:**

```
ffffffff814d03d0-ffffffff814d042a: security_audit_rule_free (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void security_audit_rule_free(void **lsmrule);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff81529100)
Location: security/security.c:3001
Inline: False
Direct callers:
  - kernel/auditfilter.c:audit_rule_change
  - kernel/auditfilter.c:audit_dupe_rule
  - kernel/auditfilter.c:audit_data_to_entry
  - kernel/auditfilter.c:audit_free_rule_rcu
  - security/integrity/ima/ima_policy.c:ima_delete_rules
  - security/integrity/ima/ima_policy.c:ima_delete_rules
  - security/integrity/ima/ima_policy.c:ima_delete_rules
  - security/integrity/ima/ima_policy.c:ima_delete_rules
  - security/integrity/ima/ima_policy.c:ima_parse_add_rule
  - security/integrity/ima/ima_policy.c:ima_parse_add_rule
  - security/integrity/ima/ima_policy.c:ima_parse_add_rule
  - security/integrity/ima/ima_policy.c:ima_parse_add_rule
  - security/integrity/ima/ima_policy.c:ima_lsm_update_rules
  - security/integrity/ima/ima_policy.c:ima_lsm_update_rules
  - security/integrity/ima/ima_policy.c:ima_lsm_update_rules
  - security/integrity/ima/ima_policy.c:ima_lsm_update_rules
```
**Symbols:**

```
ffffffff81529100-ffffffff8152915a: security_audit_rule_free (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void security_audit_rule_free(struct audit_lsm_rules *lsmrules);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff815be5b0)
Location: security/security.c:3037
Inline: False
Direct callers:
  - kernel/auditfilter.c:audit_rule_change
  - kernel/auditfilter.c:audit_dupe_rule
  - kernel/auditfilter.c:audit_data_to_entry
  - kernel/auditfilter.c:audit_free_rule_rcu
```
**Symbols:**

```
ffffffff815be5b0-ffffffff815be612: security_audit_rule_free (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void security_audit_rule_free(struct audit_lsm_rules *lsmrules);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff8166a7e0)
Location: security/security.c:3017
Inline: False
Direct callers:
  - kernel/auditfilter.c:audit_rule_change
  - kernel/auditfilter.c:audit_dupe_rule
  - kernel/auditfilter.c:audit_data_to_entry
  - kernel/auditfilter.c:audit_free_rule_rcu
```
**Symbols:**

```
ffffffff8166a7e0-ffffffff8166a842: security_audit_rule_free (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void security_audit_rule_free(struct audit_lsm_rules *lsmrules);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff816a2e60)
Location: security/security.c:5393
Inline: False
Direct callers:
  - kernel/auditfilter.c:audit_rule_change
  - kernel/auditfilter.c:audit_dupe_rule
  - kernel/auditfilter.c:audit_data_to_entry
  - kernel/auditfilter.c:audit_free_rule_rcu
```
**Symbols:**

```
ffffffff816a2e60-ffffffff816a2f09: security_audit_rule_free (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void security_audit_rule_free(void *lsmrule);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff816df9c0)
Location: security/security.c:5575
Inline: False
Direct callers:
  - kernel/auditfilter.c:audit_rule_change
  - kernel/auditfilter.c:audit_dupe_rule
  - kernel/auditfilter.c:audit_data_to_entry
  - kernel/auditfilter.c:audit_free_rule_rcu
```
**Symbols:**

```
ffffffff816df9c0-ffffffff816dfa00: security_audit_rule_free (STB_GLOBAL)
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
void security_audit_rule_free(void *lsmrule);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffff800010545898)
Location: security/security.c:2566
Inline: False
Direct callers:
  - kernel/auditfilter.c:audit_rule_change
  - kernel/auditfilter.c:audit_dupe_rule
  - kernel/auditfilter.c:audit_data_to_entry
  - kernel/auditfilter.c:audit_free_rule_rcu
```
**Symbols:**

```
ffff800010545898-ffff8000105458e0: security_audit_rule_free (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void security_audit_rule_free(void *lsmrule);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (c06fb704)
Location: security/security.c:2566
Inline: False
Direct callers:
  - kernel/auditfilter.c:audit_rule_change
  - kernel/auditfilter.c:audit_dupe_rule
  - kernel/auditfilter.c:audit_data_to_entry
  - kernel/auditfilter.c:audit_free_rule_rcu
```
**Symbols:**

```
c06fb704-c06fb74c: security_audit_rule_free (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void security_audit_rule_free(void *lsmrule);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (c00000000069be60)
Location: security/security.c:2566
Inline: False
Direct callers:
  - kernel/auditfilter.c:audit_rule_change
  - kernel/auditfilter.c:audit_dupe_rule
  - kernel/auditfilter.c:audit_data_to_entry
  - kernel/auditfilter.c:audit_free_rule_rcu
```
**Symbols:**

```
c00000000069be60-c00000000069bed8: security_audit_rule_free (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void security_audit_rule_free(void *lsmrule);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffe0003a152c)
Location: security/security.c:2566
Inline: False
Direct callers:
  - kernel/auditfilter.c:audit_rule_change
  - kernel/auditfilter.c:audit_dupe_rule
  - kernel/auditfilter.c:audit_data_to_entry
  - kernel/auditfilter.c:audit_free_rule_rcu
```
**Symbols:**

```
ffffffe0003a152c-ffffffe0003a1564: security_audit_rule_free (STB_GLOBAL)
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
void security_audit_rule_free(void *lsmrule);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff81451cc0)
Location: security/security.c:2566
Inline: False
Direct callers:
  - kernel/auditfilter.c:audit_rule_change
  - kernel/auditfilter.c:audit_dupe_rule
  - kernel/auditfilter.c:audit_data_to_entry
  - kernel/auditfilter.c:audit_free_rule_rcu
```
**Symbols:**

```
ffffffff81451cc0-ffffffff81451cf4: security_audit_rule_free (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void security_audit_rule_free(void *lsmrule);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff81442710)
Location: security/security.c:2566
Inline: False
Direct callers:
  - kernel/auditfilter.c:audit_rule_change
  - kernel/auditfilter.c:audit_dupe_rule
  - kernel/auditfilter.c:audit_data_to_entry
  - kernel/auditfilter.c:audit_free_rule_rcu
```
**Symbols:**

```
ffffffff81442710-ffffffff81442744: security_audit_rule_free (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void security_audit_rule_free(void *lsmrule);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff8144dd60)
Location: security/security.c:2566
Inline: False
Direct callers:
  - kernel/auditfilter.c:audit_rule_change
  - kernel/auditfilter.c:audit_dupe_rule
  - kernel/auditfilter.c:audit_data_to_entry
  - kernel/auditfilter.c:audit_free_rule_rcu
```
**Symbols:**

```
ffffffff8144dd60-ffffffff8144dd94: security_audit_rule_free (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void security_audit_rule_free(void *lsmrule);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff81465130)
Location: security/security.c:2566
Inline: False
Direct callers:
  - kernel/auditfilter.c:audit_rule_change
  - kernel/auditfilter.c:audit_dupe_rule
  - kernel/auditfilter.c:audit_data_to_entry
  - kernel/auditfilter.c:audit_free_rule_rcu
```
**Symbols:**

```
ffffffff81465130-ffffffff81465164: security_audit_rule_free (STB_GLOBAL)
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
<details>
<summary>Changed between <code>5.4</code> and <code>5.8</code> ⚠️</summary>
<ul>
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
