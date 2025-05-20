# Function: <code>insert_rule</code>

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
In security/safesetid/securityfs.c (ffffffff814996b1)
Location: security/safesetid/securityfs.c:79
Inline: True
Inline callers:
  - security/safesetid/securityfs.c:safesetid_file_write
  - security/safesetid/securityfs.c:safesetid_file_write
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
In security/safesetid/securityfs.c (ffffffff814b35d1)
Location: security/safesetid/securityfs.c:79
Inline: True
Inline callers:
  - security/safesetid/securityfs.c:safesetid_file_write
  - security/safesetid/securityfs.c:safesetid_file_write
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
In security/safesetid/securityfs.c (ffffffff81512a7b)
Location: security/safesetid/securityfs.c:79
Inline: True
Inline callers:
  - security/safesetid/securityfs.c:handle_policy_update
  - security/safesetid/securityfs.c:verify_ruleset
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
void insert_rule(struct setid_ruleset *pol, struct setid_rule *rule);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/safesetid/securityfs.c (ffffffff8152f9d0)
Location: security/safesetid/securityfs.c:88
Inline: True
Direct callers:
  - security/safesetid/securityfs.c:handle_policy_update
  - security/safesetid/securityfs.c:verify_ruleset
```
**Symbols:**

```
ffffffff8152f9d0-ffffffff8152fa0f: insert_rule (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Collision, Selective Inline ⚠️</summary>

```c
void insert_rule(struct setid_ruleset *pol, struct setid_rule *rule);
```

**Collision:** Static-Static Collision

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/safesetid/securityfs.c (ffffffff81535ae0)
Location: security/safesetid/securityfs.c:88
Inline: True
Direct callers:
  - security/safesetid/securityfs.c:handle_policy_update
  - security/safesetid/securityfs.c:handle_policy_update
```
```
In security/landlock/ruleset.c (ffffffff81537be0)
Location: security/landlock/ruleset.c:144
Inline: False
Direct callers:
  - security/landlock/ruleset.c:inherit_ruleset
  - security/landlock/ruleset.c:merge_ruleset
  - security/landlock/ruleset.c:landlock_insert_rule
```
**Symbols:**

```
ffffffff81535ae0-ffffffff81535b1f: insert_rule (STB_LOCAL)
ffffffff81537be0-ffffffff81537da6: insert_rule (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Collision, Selective Inline ⚠️</summary>

```c
void insert_rule(struct setid_ruleset *pol, struct setid_rule *rule);
```

**Collision:** Static-Static Collision

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/safesetid/securityfs.c (ffffffff815940e0)
Location: security/safesetid/securityfs.c:88
Inline: True
Direct callers:
  - security/safesetid/securityfs.c:handle_policy_update
  - security/safesetid/securityfs.c:handle_policy_update
```
```
In security/landlock/ruleset.c (ffffffff815963e0)
Location: security/landlock/ruleset.c:144
Inline: False
Direct callers:
  - security/landlock/ruleset.c:landlock_merge_ruleset
  - security/landlock/ruleset.c:merge_ruleset
  - security/landlock/ruleset.c:landlock_insert_rule
```
**Symbols:**

```
ffffffff815940e0-ffffffff8159411f: insert_rule (STB_LOCAL)
ffffffff815963e0-ffffffff815965a6: insert_rule (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Collision, Selective Inline ⚠️</summary>

```c
void insert_rule(struct setid_ruleset *pol, struct setid_rule *rule);
```

**Collision:** Static-Static Collision

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/safesetid/securityfs.c (ffffffff81636120)
Location: security/safesetid/securityfs.c:88
Inline: True
Direct callers:
  - security/safesetid/securityfs.c:handle_policy_update
  - security/safesetid/securityfs.c:handle_policy_update
```
```
In security/landlock/ruleset.c (ffffffff81638760)
Location: security/landlock/ruleset.c:145
Inline: False
Direct callers:
  - security/landlock/ruleset.c:inherit_ruleset
  - security/landlock/ruleset.c:merge_ruleset
  - security/landlock/ruleset.c:landlock_insert_rule
```
**Symbols:**

```
ffffffff81636120-ffffffff8163616b: insert_rule (STB_LOCAL)
ffffffff81638760-ffffffff81638929: insert_rule (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Collision, Selective Inline ⚠️</summary>

```c
void insert_rule(struct setid_ruleset *pol, struct setid_rule *rule);
```

**Collision:** Static-Static Collision

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/safesetid/securityfs.c (ffffffff816ed110)
Location: security/safesetid/securityfs.c:88
Inline: True
Direct callers:
  - security/safesetid/securityfs.c:handle_policy_update
  - security/safesetid/securityfs.c:handle_policy_update
```
```
In security/landlock/ruleset.c (ffffffff816efc10)
Location: security/landlock/ruleset.c:145
Inline: False
Direct callers:
  - security/landlock/ruleset.c:inherit_ruleset
  - security/landlock/ruleset.c:merge_ruleset
  - security/landlock/ruleset.c:landlock_insert_rule
```
**Symbols:**

```
ffffffff816ed110-ffffffff816ed15b: insert_rule (STB_LOCAL)
ffffffff816efc10-ffffffff816efdd9: insert_rule (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Collision, Selective Inline ⚠️</summary>

```c
void insert_rule(struct setid_ruleset *pol, struct setid_rule *rule);
```

**Collision:** Static-Static Collision

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/safesetid/securityfs.c (ffffffff81727530)
Location: security/safesetid/securityfs.c:88
Inline: True
Direct callers:
  - security/safesetid/securityfs.c:handle_policy_update
  - security/safesetid/securityfs.c:handle_policy_update
```
```
In security/landlock/ruleset.c (ffffffff8172a130)
Location: security/landlock/ruleset.c:145
Inline: False
Direct callers:
  - security/landlock/ruleset.c:landlock_merge_ruleset
  - security/landlock/ruleset.c:inherit_ruleset
  - security/landlock/ruleset.c:landlock_insert_rule
```
**Symbols:**

```
ffffffff81727530-ffffffff8172757b: insert_rule (STB_LOCAL)
ffffffff8172a130-ffffffff8172a2f9: insert_rule (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Collision, Selective Inline ⚠️</summary>

```c
void insert_rule(struct setid_ruleset *pol, struct setid_rule *rule);
```

**Collision:** Static-Static Collision

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/safesetid/securityfs.c (ffffffff817687d0)
Location: security/safesetid/securityfs.c:88
Inline: True
Direct callers:
  - security/safesetid/securityfs.c:handle_policy_update
  - security/safesetid/securityfs.c:handle_policy_update
```
```
In security/landlock/ruleset.c (ffffffff8176b530)
Location: security/landlock/ruleset.c:199
Inline: False
Direct callers:
  - security/landlock/ruleset.c:inherit_tree
  - security/landlock/ruleset.c:merge_tree
  - security/landlock/ruleset.c:landlock_insert_rule
```
**Symbols:**

```
ffffffff817687d0-ffffffff8176881b: insert_rule (STB_LOCAL)
ffffffff8176b530-ffffffff8176b7a1: insert_rule (STB_LOCAL)
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
In security/safesetid/securityfs.c (ffff8000105ab2a8)
Location: security/safesetid/securityfs.c:79
Inline: True
Inline callers:
  - security/safesetid/securityfs.c:safesetid_file_write
  - security/safesetid/securityfs.c:safesetid_file_write
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
In security/safesetid/securityfs.c (c075ae54)
Location: security/safesetid/securityfs.c:79
Inline: True
Inline callers:
  - security/safesetid/securityfs.c:safesetid_file_write
  - security/safesetid/securityfs.c:safesetid_file_write
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
In security/safesetid/securityfs.c (c00000000072900c)
Location: security/safesetid/securityfs.c:79
Inline: True
Inline callers:
  - security/safesetid/securityfs.c:safesetid_file_write
  - security/safesetid/securityfs.c:safesetid_file_write
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
In security/safesetid/securityfs.c (ffffffe0003f3d7e)
Location: security/safesetid/securityfs.c:79
Inline: True
Inline callers:
  - security/safesetid/securityfs.c:safesetid_file_write
  - security/safesetid/securityfs.c:safesetid_file_write
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
In security/safesetid/securityfs.c (ffffffff814abbb1)
Location: security/safesetid/securityfs.c:79
Inline: True
Inline callers:
  - security/safesetid/securityfs.c:safesetid_file_write
  - security/safesetid/securityfs.c:safesetid_file_write
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
In security/safesetid/securityfs.c (ffffffff8149c5d1)
Location: security/safesetid/securityfs.c:79
Inline: True
Inline callers:
  - security/safesetid/securityfs.c:safesetid_file_write
  - security/safesetid/securityfs.c:safesetid_file_write
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
In security/safesetid/securityfs.c (ffffffff814a7c51)
Location: security/safesetid/securityfs.c:79
Inline: True
Inline callers:
  - security/safesetid/securityfs.c:safesetid_file_write
  - security/safesetid/securityfs.c:safesetid_file_write
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
In security/safesetid/securityfs.c (ffffffff814c05e1)
Location: security/safesetid/securityfs.c:79
Inline: True
Inline callers:
  - security/safesetid/securityfs.c:safesetid_file_write
  - security/safesetid/securityfs.c:safesetid_file_write
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
