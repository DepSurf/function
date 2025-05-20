# Function: <code>audit_list_rules</code>

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
In kernel/auditfilter.c (ffffffff811253c4)
Location: kernel/auditfilter.c:1034
Inline: True
Inline callers:
  - kernel/auditfilter.c:audit_list_rules_send
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void audit_list_rules(__u32 portid, int seq, struct sk_buff_head *q);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/auditfilter.c (ffffffff8112bfa0)
Location: kernel/auditfilter.c:1034
Inline: False
Direct callers:
  - kernel/auditfilter.c:audit_list_rules_send
```
**Symbols:**

```
ffffffff8112bfa0-ffffffff8112c260: audit_list_rules (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void audit_list_rules(__u32 portid, int seq, struct sk_buff_head *q);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/auditfilter.c (ffffffff81135cb0)
Location: kernel/auditfilter.c:1036
Inline: False
Direct callers:
  - kernel/auditfilter.c:audit_list_rules_send
```
**Symbols:**

```
ffffffff81135cb0-ffffffff81135f70: audit_list_rules (STB_LOCAL)
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
In kernel/auditfilter.c (ffffffff8113846f)
Location: kernel/auditfilter.c:1036
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
In kernel/auditfilter.c (ffffffff8114517f)
Location: kernel/auditfilter.c:1061
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
In kernel/auditfilter.c (ffffffff81153b06)
Location: kernel/auditfilter.c:1060
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
In kernel/auditfilter.c (ffffffff81160896)
Location: kernel/auditfilter.c:1058
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
In kernel/auditfilter.c (ffffffff8116cf10)
Location: kernel/auditfilter.c:1062
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
In kernel/auditfilter.c (ffffffff81178db0)
Location: kernel/auditfilter.c:1069
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
void audit_list_rules(int seq, struct sk_buff_head *q);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/auditfilter.c (ffffffff8118af00)
Location: kernel/auditfilter.c:1070
Inline: False
Direct callers:
  - kernel/auditfilter.c:audit_list_rules_send
```
**Symbols:**

```
ffffffff8118af00-ffffffff8118afd5: audit_list_rules (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void audit_list_rules(int seq, struct sk_buff_head *q);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/auditfilter.c (ffffffff81188150)
Location: kernel/auditfilter.c:1070
Inline: False
Direct callers:
  - kernel/auditfilter.c:audit_list_rules_send
```
**Symbols:**

```
ffffffff81188150-ffffffff81188225: audit_list_rules (STB_LOCAL)
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
In kernel/auditfilter.c (ffffffff81189ff5)
Location: kernel/auditfilter.c:1070
Inline: True
Inline callers:
  - kernel/auditfilter.c:audit_list_rules_send
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
In kernel/auditfilter.c (ffffffff811b2a39)
Location: kernel/auditfilter.c:1070
Inline: True
Inline callers:
  - kernel/auditfilter.c:audit_list_rules_send
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
In kernel/auditfilter.c (ffffffff811e4d99)
Location: kernel/auditfilter.c:1078
Inline: True
Inline callers:
  - kernel/auditfilter.c:audit_list_rules_send
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
In kernel/auditfilter.c (ffffffff8122adb9)
Location: kernel/auditfilter.c:1078
Inline: True
Inline callers:
  - kernel/auditfilter.c:audit_list_rules_send
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
In kernel/auditfilter.c (ffffffff812413b9)
Location: kernel/auditfilter.c:1078
Inline: True
Inline callers:
  - kernel/auditfilter.c:audit_list_rules_send
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
In kernel/auditfilter.c (ffffffff8125b1e8)
Location: kernel/auditfilter.c:1079
Inline: True
Inline callers:
  - kernel/auditfilter.c:audit_list_rules_send
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
In kernel/auditfilter.c (ffff8000101edefc)
Location: kernel/auditfilter.c:1069
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
In kernel/auditfilter.c (c042e018)
Location: kernel/auditfilter.c:1069
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
In kernel/auditfilter.c (c0000000002609f0)
Location: kernel/auditfilter.c:1069
Inline: True
Inline callers:
  - kernel/auditfilter.c:audit_list_rules_send
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void audit_list_rules(int seq, struct sk_buff_head *q);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/auditfilter.c (ffffffe000161108)
Location: kernel/auditfilter.c:1069
Inline: False
Direct callers:
  - kernel/auditfilter.c:audit_list_rules_send
```
**Symbols:**

```
ffffffe000161108-ffffffe000161374: audit_list_rules (STB_LOCAL)
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
In kernel/auditfilter.c (ffffffff811713d0)
Location: kernel/auditfilter.c:1069
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
In kernel/auditfilter.c (ffffffff81164570)
Location: kernel/auditfilter.c:1069
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
In kernel/auditfilter.c (ffffffff8116f1a0)
Location: kernel/auditfilter.c:1069
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
In kernel/auditfilter.c (ffffffff8117c990)
Location: kernel/auditfilter.c:1069
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
No changes between <code>4.8</code> and <code>4.10</code> ✅
</li>
<li>
No changes between <code>5.8</code> and <code>5.11</code> ✅
</li>
</ul>
<b>Arch</b>
<ul>
</ul>
