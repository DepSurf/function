# Function: <code>ima_lsm_copy_rule</code>

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
<summary>In <code>5.3</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In security/integrity/ima/ima_policy.c (ffffffff8149f57b)
Location: security/integrity/ima/ima_policy.c:260
Inline: True
Inline callers:
  - security/integrity/ima/ima_policy.c:ima_lsm_policy_change
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In security/integrity/ima/ima_policy.c (ffffffff814b9b4b)
Location: security/integrity/ima/ima_policy.c:263
Inline: True
Inline callers:
  - security/integrity/ima/ima_policy.c:ima_lsm_policy_change
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
struct ima_rule_entry *ima_lsm_copy_rule(struct ima_rule_entry *entry);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In security/integrity/ima/ima_policy.c (0)
Location: security/integrity/ima/ima_policy.c:300
Inline: False
Direct callers:
  - security/integrity/ima/ima_policy.c:ima_lsm_update_rules
```
**Symbols:**

```
ffffffff81518870-ffffffff8151897c: ima_lsm_copy_rule (STB_LOCAL)
ffffffff8151a67f-ffffffff8151a694: ima_lsm_copy_rule.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
struct ima_rule_entry *ima_lsm_copy_rule(struct ima_rule_entry *entry);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/integrity/ima/ima_policy.c (ffffffff81535830)
Location: security/integrity/ima/ima_policy.c:370
Inline: False
Direct callers:
  - security/integrity/ima/ima_policy.c:ima_lsm_update_rules
```
**Symbols:**

```
ffffffff81535830-ffffffff8153590f: ima_lsm_copy_rule (STB_LOCAL)
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
In security/integrity/ima/ima_policy.c (ffffffff8153e25c)
Location: security/integrity/ima/ima_policy.c:379
Inline: True
Inline callers:
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
In security/integrity/ima/ima_policy.c (ffffffff8159d375)
Location: security/integrity/ima/ima_policy.c:391
Inline: True
Inline callers:
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
In security/integrity/ima/ima_policy.c (ffffffff81642606)
Location: security/integrity/ima/ima_policy.c:407
Inline: True
Inline callers:
  - security/integrity/ima/ima_policy.c:ima_lsm_update_rules
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
struct ima_rule_entry *ima_lsm_copy_rule(struct ima_rule_entry *entry);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/integrity/ima/ima_policy.c (ffffffff816fa470)
Location: security/integrity/ima/ima_policy.c:431
Inline: False
Direct callers:
  - security/integrity/ima/ima_policy.c:ima_match_rules
  - security/integrity/ima/ima_policy.c:ima_lsm_policy_change
```
**Symbols:**

```
ffffffff816fa470-ffffffff816fa6c3: ima_lsm_copy_rule (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
struct ima_rule_entry *ima_lsm_copy_rule(struct ima_rule_entry *entry);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/integrity/ima/ima_policy.c (ffffffff81734570)
Location: security/integrity/ima/ima_policy.c:431
Inline: False
Direct callers:
  - security/integrity/ima/ima_policy.c:ima_match_rules
  - security/integrity/ima/ima_policy.c:ima_lsm_policy_change
```
**Symbols:**

```
ffffffff81734570-ffffffff817347c3: ima_lsm_copy_rule (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
struct ima_rule_entry *ima_lsm_copy_rule(struct ima_rule_entry *entry);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/integrity/ima/ima_policy.c (ffffffff81775080)
Location: security/integrity/ima/ima_policy.c:426
Inline: False
Direct callers:
  - security/integrity/ima/ima_policy.c:ima_lsm_policy_change
```
**Symbols:**

```
ffffffff81775080-ffffffff817752d3: ima_lsm_copy_rule (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In security/integrity/ima/ima_policy.c (ffff8000105b1efc)
Location: security/integrity/ima/ima_policy.c:263
Inline: True
Inline callers:
  - security/integrity/ima/ima_policy.c:ima_lsm_policy_change
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In security/integrity/ima/ima_policy.c (c076159c)
Location: security/integrity/ima/ima_policy.c:263
Inline: True
Inline callers:
  - security/integrity/ima/ima_policy.c:ima_lsm_policy_change
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In security/integrity/ima/ima_policy.c (c000000000733120)
Location: security/integrity/ima/ima_policy.c:263
Inline: True
Inline callers:
  - security/integrity/ima/ima_policy.c:ima_lsm_policy_change
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In security/integrity/ima/ima_policy.c (ffffffe0003f97fa)
Location: security/integrity/ima/ima_policy.c:263
Inline: True
Inline callers:
  - security/integrity/ima/ima_policy.c:ima_lsm_policy_change
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In security/integrity/ima/ima_policy.c (ffffffff814b212b)
Location: security/integrity/ima/ima_policy.c:263
Inline: True
Inline callers:
  - security/integrity/ima/ima_policy.c:ima_lsm_policy_change
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In security/integrity/ima/ima_policy.c (ffffffff814a2b4b)
Location: security/integrity/ima/ima_policy.c:263
Inline: True
Inline callers:
  - security/integrity/ima/ima_policy.c:ima_lsm_policy_change
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In security/integrity/ima/ima_policy.c (ffffffff814ae1bb)
Location: security/integrity/ima/ima_policy.c:263
Inline: True
Inline callers:
  - security/integrity/ima/ima_policy.c:ima_lsm_policy_change
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In security/integrity/ima/ima_policy.c (ffffffff814c6c0b)
Location: security/integrity/ima/ima_policy.c:263
Inline: True
Inline callers:
  - security/integrity/ima/ima_policy.c:ima_lsm_policy_change
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>5.8</code> and <code>5.11</code> ✅
</li>
<li>
No changes between <code>6.2</code> and <code>6.5</code> ✅
</li>
<li>
No changes between <code>6.5</code> and <code>6.8</code> ✅
</li>
</ul>
