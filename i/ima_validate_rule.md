# Function: <code>ima_validate_rule</code>

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
In <code>5.3</code>: Absent ⚠️
</li>
<li>
In <code>5.4</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>5.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In security/integrity/ima/ima_policy.c (ffffffff815197b0)
Location: security/integrity/ima/ima_policy.c:1006
Inline: True
Inline callers:
  - security/integrity/ima/ima_policy.c:ima_parse_rule
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
In security/integrity/ima/ima_policy.c (ffffffff81536846)
Location: security/integrity/ima/ima_policy.c:1051
Inline: True
Inline callers:
  - security/integrity/ima/ima_policy.c:ima_parse_rule
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
bool ima_validate_rule(struct ima_rule_entry *entry);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/integrity/ima/ima_policy.c (ffffffff8153de60)
Location: security/integrity/ima/ima_policy.c:1092
Inline: False
Direct callers:
  - security/integrity/ima/ima_policy.c:ima_parse_rule
```
**Symbols:**

```
ffffffff8153de60-ffffffff8153df75: ima_validate_rule (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
bool ima_validate_rule(struct ima_rule_entry *entry);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/integrity/ima/ima_policy.c (ffffffff8159cd30)
Location: security/integrity/ima/ima_policy.c:1148
Inline: False
Direct callers:
  - security/integrity/ima/ima_policy.c:ima_parse_rule
```
**Symbols:**

```
ffffffff8159cd30-ffffffff8159ceb1: ima_validate_rule (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
bool ima_validate_rule(struct ima_rule_entry *entry);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/integrity/ima/ima_policy.c (ffffffff81641f10)
Location: security/integrity/ima/ima_policy.c:1226
Inline: False
Direct callers:
  - security/integrity/ima/ima_policy.c:ima_parse_rule
```
**Symbols:**

```
ffffffff81641f10-ffffffff8164211e: ima_validate_rule (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
bool ima_validate_rule(struct ima_rule_entry *entry);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/integrity/ima/ima_policy.c (ffffffff816fa0e0)
Location: security/integrity/ima/ima_policy.c:1273
Inline: False
Direct callers:
  - security/integrity/ima/ima_policy.c:ima_parse_rule
```
**Symbols:**

```
ffffffff816fa0e0-ffffffff816fa2ee: ima_validate_rule (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
bool ima_validate_rule(struct ima_rule_entry *entry);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/integrity/ima/ima_policy.c (ffffffff81734210)
Location: security/integrity/ima/ima_policy.c:1275
Inline: False
Direct callers:
  - security/integrity/ima/ima_policy.c:ima_parse_rule
```
**Symbols:**

```
ffffffff81734210-ffffffff817343ea: ima_validate_rule (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
bool ima_validate_rule(struct ima_rule_entry *entry);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/integrity/ima/ima_policy.c (ffffffff81774d00)
Location: security/integrity/ima/ima_policy.c:1268
Inline: False
Direct callers:
  - security/integrity/ima/ima_policy.c:ima_parse_rule
```
**Symbols:**

```
ffffffff81774d00-ffffffff81774efe: ima_validate_rule (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
In <code>arm64</code>: Absent ⚠️
</li>
<li>
In <code>armhf</code>: Absent ⚠️
</li>
<li>
In <code>ppc64el</code>: Absent ⚠️
</li>
<li>
In <code>riscv64</code>: Absent ⚠️
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
In <code>aws</code>: Absent ⚠️
</li>
<li>
In <code>azure</code>: Absent ⚠️
</li>
<li>
In <code>gcp</code>: Absent ⚠️
</li>
<li>
In <code>lowlatency</code>: Absent ⚠️
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
