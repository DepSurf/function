# Function: <code>audit_init_entry</code>

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
In kernel/auditfilter.c (ffffffff811242f6)
Location: kernel/auditfilter.c:115
Inline: True
Inline callers:
  - kernel/auditfilter.c:audit_dupe_rule
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
In kernel/auditfilter.c (ffffffff8112c8f9)
Location: kernel/auditfilter.c:115
Inline: True
Inline callers:
  - kernel/auditfilter.c:audit_rule_change
  - kernel/auditfilter.c:audit_dupe_rule
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
In kernel/auditfilter.c (ffffffff81136609)
Location: kernel/auditfilter.c:115
Inline: True
Inline callers:
  - kernel/auditfilter.c:audit_rule_change
  - kernel/auditfilter.c:audit_dupe_rule
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
In kernel/auditfilter.c (ffffffff811378fc)
Location: kernel/auditfilter.c:115
Inline: True
Inline callers:
  - kernel/auditfilter.c:audit_rule_change
  - kernel/auditfilter.c:audit_dupe_rule
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
In kernel/auditfilter.c (ffffffff811445fb)
Location: kernel/auditfilter.c:117
Inline: True
Inline callers:
  - kernel/auditfilter.c:audit_rule_change
  - kernel/auditfilter.c:audit_dupe_rule
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
In kernel/auditfilter.c (ffffffff81152f74)
Location: kernel/auditfilter.c:117
Inline: True
Inline callers:
  - kernel/auditfilter.c:audit_rule_change
  - kernel/auditfilter.c:audit_dupe_rule
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
In kernel/auditfilter.c (ffffffff8115fc24)
Location: kernel/auditfilter.c:117
Inline: True
Inline callers:
  - kernel/auditfilter.c:audit_rule_change
  - kernel/auditfilter.c:audit_dupe_rule
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
In kernel/auditfilter.c (ffffffff8116c689)
Location: kernel/auditfilter.c:104
Inline: True
Inline callers:
  - kernel/auditfilter.c:audit_dupe_rule
  - kernel/auditfilter.c:audit_data_to_entry
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
In kernel/auditfilter.c (ffffffff81178509)
Location: kernel/auditfilter.c:104
Inline: True
Inline callers:
  - kernel/auditfilter.c:audit_dupe_rule
  - kernel/auditfilter.c:audit_data_to_entry
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
struct audit_entry *audit_init_entry(u32 field_count);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/auditfilter.c (ffffffff8118a850)
Location: kernel/auditfilter.c:104
Inline: False
Direct callers:
  - kernel/auditfilter.c:audit_dupe_rule
  - kernel/auditfilter.c:audit_data_to_entry
```
**Symbols:**

```
ffffffff8118a850-ffffffff8118a8b8: audit_init_entry (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
struct audit_entry *audit_init_entry(u32 field_count);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/auditfilter.c (ffffffff81187ac0)
Location: kernel/auditfilter.c:104
Inline: False
Direct callers:
  - kernel/auditfilter.c:audit_dupe_rule
  - kernel/auditfilter.c:audit_data_to_entry
```
**Symbols:**

```
ffffffff81187ac0-ffffffff81187b19: audit_init_entry (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
struct audit_entry *audit_init_entry(u32 field_count);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/auditfilter.c (ffffffff81188b20)
Location: kernel/auditfilter.c:104
Inline: False
Direct callers:
  - kernel/auditfilter.c:audit_dupe_rule
  - kernel/auditfilter.c:audit_data_to_entry
```
**Symbols:**

```
ffffffff81188b20-ffffffff81188b79: audit_init_entry (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
struct audit_entry *audit_init_entry(u32 field_count);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/auditfilter.c (ffffffff811b10c0)
Location: kernel/auditfilter.c:104
Inline: False
Direct callers:
  - kernel/auditfilter.c:audit_dupe_rule
  - kernel/auditfilter.c:audit_data_to_entry
```
**Symbols:**

```
ffffffff811b10c0-ffffffff811b1119: audit_init_entry (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
struct audit_entry *audit_init_entry(u32 field_count);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/auditfilter.c (ffffffff811e3360)
Location: kernel/auditfilter.c:106
Inline: False
Direct callers:
  - kernel/auditfilter.c:audit_dupe_rule
  - kernel/auditfilter.c:audit_data_to_entry
```
**Symbols:**

```
ffffffff811e3360-ffffffff811e33ce: audit_init_entry (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
struct audit_entry *audit_init_entry(u32 field_count);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/auditfilter.c (ffffffff81229510)
Location: kernel/auditfilter.c:106
Inline: False
Direct callers:
  - kernel/auditfilter.c:audit_dupe_rule
  - kernel/auditfilter.c:audit_data_to_entry
```
**Symbols:**

```
ffffffff81229510-ffffffff8122957e: audit_init_entry (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
struct audit_entry *audit_init_entry(u32 field_count);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/auditfilter.c (ffffffff8123fb10)
Location: kernel/auditfilter.c:106
Inline: False
Direct callers:
  - kernel/auditfilter.c:audit_dupe_rule
  - kernel/auditfilter.c:audit_data_to_entry
```
**Symbols:**

```
ffffffff8123fb10-ffffffff8123fb7e: audit_init_entry (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
struct audit_entry *audit_init_entry(u32 field_count);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/auditfilter.c (ffffffff81259960)
Location: kernel/auditfilter.c:106
Inline: False
Direct callers:
  - kernel/auditfilter.c:audit_dupe_rule
  - kernel/auditfilter.c:audit_data_to_entry
```
**Symbols:**

```
ffffffff81259960-ffffffff812599f2: audit_init_entry (STB_LOCAL)
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
In kernel/auditfilter.c (ffff8000101ed684)
Location: kernel/auditfilter.c:104
Inline: True
Inline callers:
  - kernel/auditfilter.c:audit_dupe_rule
  - kernel/auditfilter.c:audit_data_to_entry
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
In kernel/auditfilter.c (c042d728)
Location: kernel/auditfilter.c:104
Inline: True
Inline callers:
  - kernel/auditfilter.c:audit_dupe_rule
  - kernel/auditfilter.c:audit_data_to_entry
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
In kernel/auditfilter.c (c00000000025fea4)
Location: kernel/auditfilter.c:104
Inline: True
Inline callers:
  - kernel/auditfilter.c:audit_dupe_rule
  - kernel/auditfilter.c:audit_data_to_entry
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
In kernel/auditfilter.c (ffffffe000161c00)
Location: kernel/auditfilter.c:104
Inline: True
Inline callers:
  - kernel/auditfilter.c:audit_dupe_rule
  - kernel/auditfilter.c:audit_data_to_entry
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
In kernel/auditfilter.c (ffffffff81170b29)
Location: kernel/auditfilter.c:104
Inline: True
Inline callers:
  - kernel/auditfilter.c:audit_dupe_rule
  - kernel/auditfilter.c:audit_data_to_entry
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
In kernel/auditfilter.c (ffffffff81163cc9)
Location: kernel/auditfilter.c:104
Inline: True
Inline callers:
  - kernel/auditfilter.c:audit_dupe_rule
  - kernel/auditfilter.c:audit_data_to_entry
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
In kernel/auditfilter.c (ffffffff8116e8f9)
Location: kernel/auditfilter.c:104
Inline: True
Inline callers:
  - kernel/auditfilter.c:audit_dupe_rule
  - kernel/auditfilter.c:audit_data_to_entry
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
In kernel/auditfilter.c (ffffffff8117c0e9)
Location: kernel/auditfilter.c:104
Inline: True
Inline callers:
  - kernel/auditfilter.c:audit_dupe_rule
  - kernel/auditfilter.c:audit_data_to_entry
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
