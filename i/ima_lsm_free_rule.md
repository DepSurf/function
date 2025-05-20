# Function: <code>ima_lsm_free_rule</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4</code>: Absent ⚠️
</li>
<li>
In <code>4.8</code>: Absent ⚠️
</li>
<li>
In <code>4.10</code>: Absent ⚠️
</li>
<li>
In <code>4.13</code>: Absent ⚠️
</li>
<li>
In <code>4.15</code>: Absent ⚠️
</li>
<li>
In <code>4.18</code>: Absent ⚠️
</li>
<li>
In <code>5.0</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void ima_lsm_free_rule(struct ima_rule_entry *entry);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/integrity/ima/ima_policy.c (ffffffff8149e760)
Location: security/integrity/ima/ima_policy.c:249
Inline: False
Direct callers:
  - security/integrity/ima/ima_policy.c:ima_lsm_policy_change
  - security/integrity/ima/ima_policy.c:ima_lsm_policy_change
```
**Symbols:**

```
ffffffff8149e760-ffffffff8149e7a5: ima_lsm_free_rule (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void ima_lsm_free_rule(struct ima_rule_entry *entry);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/integrity/ima/ima_policy.c (ffffffff814b8c10)
Location: security/integrity/ima/ima_policy.c:252
Inline: False
Direct callers:
  - security/integrity/ima/ima_policy.c:ima_lsm_policy_change
  - security/integrity/ima/ima_policy.c:ima_lsm_policy_change
```
**Symbols:**

```
ffffffff814b8c10-ffffffff814b8c55: ima_lsm_free_rule (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In security/integrity/ima/ima_policy.c (ffffffff8151a5c2)
Location: security/integrity/ima/ima_policy.c:272
Inline: True
Inline callers:
  - security/integrity/ima/ima_policy.c:ima_delete_rules
  - security/integrity/ima/ima_policy.c:ima_parse_add_rule
  - security/integrity/ima/ima_policy.c:ima_lsm_update_rules
  - security/integrity/ima/ima_policy.c:ima_lsm_copy_rule
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In security/integrity/ima/ima_policy.c (ffffffff81537688)
Location: security/integrity/ima/ima_policy.c:342
Inline: True
Inline callers:
  - security/integrity/ima/ima_policy.c:ima_delete_rules
  - security/integrity/ima/ima_policy.c:ima_parse_add_rule
  - security/integrity/ima/ima_policy.c:ima_lsm_update_rules
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In security/integrity/ima/ima_policy.c (ffffffff8153fd78)
Location: security/integrity/ima/ima_policy.c:351
Inline: True
Inline callers:
  - security/integrity/ima/ima_policy.c:ima_delete_rules
  - security/integrity/ima/ima_policy.c:ima_parse_add_rule
  - security/integrity/ima/ima_policy.c:ima_lsm_update_rules
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In security/integrity/ima/ima_policy.c (ffffffff8159d4d1)
Location: security/integrity/ima/ima_policy.c:363
Inline: True
Inline callers:
  - security/integrity/ima/ima_policy.c:ima_delete_rules
  - security/integrity/ima/ima_policy.c:ima_parse_add_rule
  - security/integrity/ima/ima_policy.c:ima_lsm_update_rules
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In security/integrity/ima/ima_policy.c (ffffffff81642747)
Location: security/integrity/ima/ima_policy.c:380
Inline: True
Inline callers:
  - security/integrity/ima/ima_policy.c:ima_delete_rules
  - security/integrity/ima/ima_policy.c:ima_parse_add_rule
  - security/integrity/ima/ima_policy.c:ima_lsm_update_rules
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In security/integrity/ima/ima_policy.c (0)
Location: security/integrity/ima/ima_policy.c:404
Inline: True
Inline callers:
  - security/integrity/ima/ima_policy.c:ima_delete_rules
  - security/integrity/ima/ima_policy.c:ima_parse_add_rule
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In security/integrity/ima/ima_policy.c (0)
Location: security/integrity/ima/ima_policy.c:404
Inline: True
Inline callers:
  - security/integrity/ima/ima_policy.c:ima_delete_rules
  - security/integrity/ima/ima_policy.c:ima_parse_add_rule
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In security/integrity/ima/ima_policy.c (0)
Location: security/integrity/ima/ima_policy.c:399
Inline: True
Inline callers:
  - security/integrity/ima/ima_policy.c:ima_delete_rules
  - security/integrity/ima/ima_policy.c:ima_parse_add_rule
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
void ima_lsm_free_rule(struct ima_rule_entry *entry);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/integrity/ima/ima_policy.c (ffff8000105b0f38)
Location: security/integrity/ima/ima_policy.c:252
Inline: False
Direct callers:
  - security/integrity/ima/ima_policy.c:ima_lsm_policy_change
  - security/integrity/ima/ima_policy.c:ima_lsm_policy_change
```
**Symbols:**

```
ffff8000105b0f38-ffff8000105b0f94: ima_lsm_free_rule (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void ima_lsm_free_rule(struct ima_rule_entry *entry);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/integrity/ima/ima_policy.c (c07605d8)
Location: security/integrity/ima/ima_policy.c:252
Inline: False
Direct callers:
  - security/integrity/ima/ima_policy.c:ima_lsm_policy_change
  - security/integrity/ima/ima_policy.c:ima_lsm_policy_change
```
**Symbols:**

```
c07605d8-c0760620: ima_lsm_free_rule (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void ima_lsm_free_rule(struct ima_rule_entry *entry);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/integrity/ima/ima_policy.c (c000000000730e00)
Location: security/integrity/ima/ima_policy.c:252
Inline: False
Direct callers:
  - security/integrity/ima/ima_policy.c:ima_lsm_policy_change
  - security/integrity/ima/ima_policy.c:ima_lsm_policy_change
```
**Symbols:**

```
c000000000730e00-c000000000730e8c: ima_lsm_free_rule (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void ima_lsm_free_rule(struct ima_rule_entry *entry);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/integrity/ima/ima_policy.c (ffffffe0003f89d0)
Location: security/integrity/ima/ima_policy.c:252
Inline: False
Direct callers:
  - security/integrity/ima/ima_policy.c:ima_lsm_policy_change
  - security/integrity/ima/ima_policy.c:ima_lsm_policy_change
```
**Symbols:**

```
ffffffe0003f89d0-ffffffe0003f8a26: ima_lsm_free_rule (STB_LOCAL)
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
void ima_lsm_free_rule(struct ima_rule_entry *entry);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/integrity/ima/ima_policy.c (ffffffff814b11f0)
Location: security/integrity/ima/ima_policy.c:252
Inline: False
Direct callers:
  - security/integrity/ima/ima_policy.c:ima_lsm_policy_change
  - security/integrity/ima/ima_policy.c:ima_lsm_policy_change
```
**Symbols:**

```
ffffffff814b11f0-ffffffff814b1235: ima_lsm_free_rule (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void ima_lsm_free_rule(struct ima_rule_entry *entry);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/integrity/ima/ima_policy.c (ffffffff814a1c10)
Location: security/integrity/ima/ima_policy.c:252
Inline: False
Direct callers:
  - security/integrity/ima/ima_policy.c:ima_lsm_policy_change
  - security/integrity/ima/ima_policy.c:ima_lsm_policy_change
```
**Symbols:**

```
ffffffff814a1c10-ffffffff814a1c55: ima_lsm_free_rule (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void ima_lsm_free_rule(struct ima_rule_entry *entry);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/integrity/ima/ima_policy.c (ffffffff814ad280)
Location: security/integrity/ima/ima_policy.c:252
Inline: False
Direct callers:
  - security/integrity/ima/ima_policy.c:ima_lsm_policy_change
  - security/integrity/ima/ima_policy.c:ima_lsm_policy_change
```
**Symbols:**

```
ffffffff814ad280-ffffffff814ad2c5: ima_lsm_free_rule (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void ima_lsm_free_rule(struct ima_rule_entry *entry);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/integrity/ima/ima_policy.c (ffffffff814c5cd0)
Location: security/integrity/ima/ima_policy.c:252
Inline: False
Direct callers:
  - security/integrity/ima/ima_policy.c:ima_lsm_policy_change
  - security/integrity/ima/ima_policy.c:ima_lsm_policy_change
```
**Symbols:**

```
ffffffff814c5cd0-ffffffff814c5d15: ima_lsm_free_rule (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>5.3</code> and <code>5.4</code> ✅
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
