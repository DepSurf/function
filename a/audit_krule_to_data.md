# Function: <code>audit_krule_to_data</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
struct audit_rule_data *audit_krule_to_data(struct audit_krule *krule);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/auditfilter.c (ffffffff81123f80)
Location: kernel/auditfilter.c:597
Inline: False
Direct callers:
  - kernel/auditfilter.c:audit_list_rules_send
```
**Symbols:**

```
ffffffff81123f80-ffffffff8112415b: audit_krule_to_data (STB_LOCAL)
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
In kernel/auditfilter.c (ffffffff8112bfe2)
Location: kernel/auditfilter.c:597
Inline: True
Inline callers:
  - kernel/auditfilter.c:audit_list_rules
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
In kernel/auditfilter.c (ffffffff81135cf2)
Location: kernel/auditfilter.c:599
Inline: True
Inline callers:
  - kernel/auditfilter.c:audit_list_rules
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
In kernel/auditfilter.c (ffffffff81138489)
Location: kernel/auditfilter.c:599
Inline: True
Inline callers:
  - kernel/auditfilter.c:audit_list_rules_send
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
In kernel/auditfilter.c (ffffffff81145199)
Location: kernel/auditfilter.c:618
Inline: True
Inline callers:
  - kernel/auditfilter.c:audit_list_rules_send
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
In kernel/auditfilter.c (ffffffff81153b22)
Location: kernel/auditfilter.c:617
Inline: True
Inline callers:
  - kernel/auditfilter.c:audit_list_rules_send
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
In kernel/auditfilter.c (ffffffff811608b2)
Location: kernel/auditfilter.c:615
Inline: True
Inline callers:
  - kernel/auditfilter.c:audit_list_rules_send
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
In kernel/auditfilter.c (ffffffff8116cf2f)
Location: kernel/auditfilter.c:619
Inline: True
Inline callers:
  - kernel/auditfilter.c:audit_list_rules_send
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
In kernel/auditfilter.c (ffffffff81178dcf)
Location: kernel/auditfilter.c:626
Inline: True
Inline callers:
  - kernel/auditfilter.c:audit_list_rules_send
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
struct audit_rule_data *audit_krule_to_data(struct audit_krule *krule);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/auditfilter.c (ffffffff8118ace0)
Location: kernel/auditfilter.c:627
Inline: False
Direct callers:
  - kernel/auditfilter.c:audit_list_rules
```
**Symbols:**

```
ffffffff8118ace0-ffffffff8118aef3: audit_krule_to_data (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
struct audit_rule_data *audit_krule_to_data(struct audit_krule *krule);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/auditfilter.c (ffffffff81187f40)
Location: kernel/auditfilter.c:627
Inline: False
Direct callers:
  - kernel/auditfilter.c:audit_list_rules
```
**Symbols:**

```
ffffffff81187f40-ffffffff81188142: audit_krule_to_data (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
struct audit_rule_data *audit_krule_to_data(struct audit_krule *krule);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/auditfilter.c (ffffffff81188fa0)
Location: kernel/auditfilter.c:627
Inline: False
Direct callers:
  - kernel/auditfilter.c:audit_list_rules_send
```
**Symbols:**

```
ffffffff81188fa0-ffffffff811891a2: audit_krule_to_data (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
struct audit_rule_data *audit_krule_to_data(struct audit_krule *krule);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/auditfilter.c (ffffffff811b1570)
Location: kernel/auditfilter.c:627
Inline: False
Direct callers:
  - kernel/auditfilter.c:audit_list_rules_send
```
**Symbols:**

```
ffffffff811b1570-ffffffff811b1a37: audit_krule_to_data (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
struct audit_rule_data *audit_krule_to_data(struct audit_krule *krule);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/auditfilter.c (ffffffff811e3840)
Location: kernel/auditfilter.c:634
Inline: False
Direct callers:
  - kernel/auditfilter.c:audit_list_rules_send
```
**Symbols:**

```
ffffffff811e3840-ffffffff811e3d0a: audit_krule_to_data (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
struct audit_rule_data *audit_krule_to_data(struct audit_krule *krule);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/auditfilter.c (ffffffff81228fd0)
Location: kernel/auditfilter.c:634
Inline: False
Direct callers:
  - kernel/auditfilter.c:audit_list_rules_send
```
**Symbols:**

```
ffffffff81228fd0-ffffffff8122943e: audit_krule_to_data (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
struct audit_rule_data *audit_krule_to_data(struct audit_krule *krule);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/auditfilter.c (ffffffff8123f5d0)
Location: kernel/auditfilter.c:634
Inline: False
Direct callers:
  - kernel/auditfilter.c:audit_list_rules_send
```
**Symbols:**

```
ffffffff8123f5d0-ffffffff8123fa35: audit_krule_to_data (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
struct audit_rule_data *audit_krule_to_data(struct audit_krule *krule);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/auditfilter.c (ffffffff81259430)
Location: kernel/auditfilter.c:634
Inline: False
Direct callers:
  - kernel/auditfilter.c:audit_list_rules_send
```
**Symbols:**

```
ffffffff81259430-ffffffff81259882: audit_krule_to_data (STB_LOCAL)
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
In kernel/auditfilter.c (ffff8000101edf18)
Location: kernel/auditfilter.c:626
Inline: True
Inline callers:
  - kernel/auditfilter.c:audit_list_rules_send
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
In kernel/auditfilter.c (c042e02c)
Location: kernel/auditfilter.c:626
Inline: True
Inline callers:
  - kernel/auditfilter.c:audit_list_rules_send
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
In kernel/auditfilter.c (c000000000260a10)
Location: kernel/auditfilter.c:626
Inline: True
Inline callers:
  - kernel/auditfilter.c:audit_list_rules_send
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
In kernel/auditfilter.c (ffffffe000161126)
Location: kernel/auditfilter.c:626
Inline: True
Inline callers:
  - kernel/auditfilter.c:audit_list_rules
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
In kernel/auditfilter.c (ffffffff811713ef)
Location: kernel/auditfilter.c:626
Inline: True
Inline callers:
  - kernel/auditfilter.c:audit_list_rules_send
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
In kernel/auditfilter.c (ffffffff8116458f)
Location: kernel/auditfilter.c:626
Inline: True
Inline callers:
  - kernel/auditfilter.c:audit_list_rules_send
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
In kernel/auditfilter.c (ffffffff8116f1bf)
Location: kernel/auditfilter.c:626
Inline: True
Inline callers:
  - kernel/auditfilter.c:audit_list_rules_send
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
In kernel/auditfilter.c (ffffffff8117c9af)
Location: kernel/auditfilter.c:626
Inline: True
Inline callers:
  - kernel/auditfilter.c:audit_list_rules_send
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
