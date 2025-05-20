# Function: <code>audit_add_rule</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/auditfilter.c (ffffffff8112500f)
Location: kernel/auditfilter.c:901
Inline: True
Inline callers:
  - kernel/auditfilter.c:audit_rule_change
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/auditfilter.c (ffffffff8112d0b7)
Location: kernel/auditfilter.c:901
Inline: True
Inline callers:
  - kernel/auditfilter.c:audit_rule_change
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/auditfilter.c (ffffffff81136da9)
Location: kernel/auditfilter.c:903
Inline: True
Inline callers:
  - kernel/auditfilter.c:audit_rule_change
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/auditfilter.c (ffffffff81137b79)
Location: kernel/auditfilter.c:903
Inline: True
Inline callers:
  - kernel/auditfilter.c:audit_rule_change
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/auditfilter.c (ffffffff81144a1d)
Location: kernel/auditfilter.c:922
Inline: True
Inline callers:
  - kernel/auditfilter.c:audit_rule_change
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/auditfilter.c (ffffffff811531d3)
Location: kernel/auditfilter.c:921
Inline: True
Inline callers:
  - kernel/auditfilter.c:audit_rule_change
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/auditfilter.c (ffffffff8115fe7c)
Location: kernel/auditfilter.c:919
Inline: True
Inline callers:
  - kernel/auditfilter.c:audit_rule_change
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/auditfilter.c (ffffffff8116caf9)
Location: kernel/auditfilter.c:923
Inline: True
Inline callers:
  - kernel/auditfilter.c:audit_rule_change
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
In kernel/auditfilter.c (ffffffff811789ac)
Location: kernel/auditfilter.c:930
Inline: True
Inline callers:
  - kernel/auditfilter.c:audit_rule_change
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int audit_add_rule(struct audit_entry *entry);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/auditfilter.c (ffffffff8118a9b0)
Location: kernel/auditfilter.c:931
Inline: False
Direct callers:
  - kernel/auditfilter.c:audit_rule_change
```
**Symbols:**

```
ffffffff8118a9b0-ffffffff8118ac12: audit_add_rule (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int audit_add_rule(struct audit_entry *entry);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/auditfilter.c (ffffffff81187c10)
Location: kernel/auditfilter.c:931
Inline: False
Direct callers:
  - kernel/auditfilter.c:audit_rule_change
```
**Symbols:**

```
ffffffff81187c10-ffffffff81187e72: audit_add_rule (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int audit_add_rule(struct audit_entry *entry);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/auditfilter.c (ffffffff81188c70)
Location: kernel/auditfilter.c:931
Inline: False
Direct callers:
  - kernel/auditfilter.c:audit_rule_change
```
**Symbols:**

```
ffffffff81188c70-ffffffff81188ed2: audit_add_rule (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int audit_add_rule(struct audit_entry *entry);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/auditfilter.c (ffffffff811b1210)
Location: kernel/auditfilter.c:931
Inline: False
Direct callers:
  - kernel/auditfilter.c:audit_rule_change
```
**Symbols:**

```
ffffffff811b1210-ffffffff811b14ad: audit_add_rule (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int audit_add_rule(struct audit_entry *entry);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/auditfilter.c (ffffffff811e34d0)
Location: kernel/auditfilter.c:938
Inline: False
Direct callers:
  - kernel/auditfilter.c:audit_rule_change
```
**Symbols:**

```
ffffffff811e34d0-ffffffff811e376f: audit_add_rule (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int audit_add_rule(struct audit_entry *entry);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/auditfilter.c (ffffffff812298f0)
Location: kernel/auditfilter.c:938
Inline: False
Direct callers:
  - kernel/auditfilter.c:audit_rule_change
```
**Symbols:**

```
ffffffff812298f0-ffffffff81229b8f: audit_add_rule (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int audit_add_rule(struct audit_entry *entry);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/auditfilter.c (ffffffff8123feb0)
Location: kernel/auditfilter.c:938
Inline: False
Direct callers:
  - kernel/auditfilter.c:audit_rule_change
```
**Symbols:**

```
ffffffff8123feb0-ffffffff8124014f: audit_add_rule (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int audit_add_rule(struct audit_entry *entry);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/auditfilter.c (ffffffff81259d30)
Location: kernel/auditfilter.c:939
Inline: False
Direct callers:
  - kernel/auditfilter.c:audit_rule_change
```
**Symbols:**

```
ffffffff81259d30-ffffffff81259fcf: audit_add_rule (STB_LOCAL)
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
In kernel/auditfilter.c (ffff8000101edb1c)
Location: kernel/auditfilter.c:930
Inline: True
Inline callers:
  - kernel/auditfilter.c:audit_rule_change
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
In kernel/auditfilter.c (c042dbfc)
Location: kernel/auditfilter.c:930
Inline: True
Inline callers:
  - kernel/auditfilter.c:audit_rule_change
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
In kernel/auditfilter.c (c0000000002604d8)
Location: kernel/auditfilter.c:930
Inline: True
Inline callers:
  - kernel/auditfilter.c:audit_rule_change
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
In kernel/auditfilter.c (ffffffe000161fe0)
Location: kernel/auditfilter.c:930
Inline: True
Inline callers:
  - kernel/auditfilter.c:audit_rule_change
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
In kernel/auditfilter.c (ffffffff81170fcc)
Location: kernel/auditfilter.c:930
Inline: True
Inline callers:
  - kernel/auditfilter.c:audit_rule_change
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
In kernel/auditfilter.c (ffffffff8116416c)
Location: kernel/auditfilter.c:930
Inline: True
Inline callers:
  - kernel/auditfilter.c:audit_rule_change
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
In kernel/auditfilter.c (ffffffff8116ed9c)
Location: kernel/auditfilter.c:930
Inline: True
Inline callers:
  - kernel/auditfilter.c:audit_rule_change
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
In kernel/auditfilter.c (ffffffff8117c58c)
Location: kernel/auditfilter.c:930
Inline: True
Inline callers:
  - kernel/auditfilter.c:audit_rule_change
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
