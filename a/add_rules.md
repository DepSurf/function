# Function: <code>add_rules</code>

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
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void add_rules(struct ima_rule_entry *entries, int count, enum policy_rule_list policy_rule);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/integrity/ima/ima_policy.c (ffffffff81472139)
Location: security/integrity/ima/ima_policy.c:484
Inline: False
Direct callers:
  - security/integrity/ima/ima_policy.c:ima_init_policy
  - security/integrity/ima/ima_policy.c:ima_init_policy
  - security/integrity/ima/ima_policy.c:ima_init_policy
  - security/integrity/ima/ima_policy.c:ima_init_policy
  - security/integrity/ima/ima_policy.c:ima_init_policy
  - security/integrity/ima/ima_policy.c:ima_init_policy
```
**Symbols:**

```
ffffffff81472139-ffffffff81472231: add_rules (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void add_rules(struct ima_rule_entry *entries, int count, enum policy_rule_list policy_rule);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/integrity/ima/ima_policy.c (ffffffff8149fe18)
Location: security/integrity/ima/ima_policy.c:567
Inline: False
Direct callers:
  - security/integrity/ima/ima_policy.c:ima_init_policy
  - security/integrity/ima/ima_policy.c:ima_init_policy
  - security/integrity/ima/ima_policy.c:ima_init_policy
  - security/integrity/ima/ima_policy.c:ima_init_policy
  - security/integrity/ima/ima_policy.c:ima_init_policy
  - security/integrity/ima/ima_policy.c:ima_init_policy
```
**Symbols:**

```
ffffffff8149fe18-ffffffff8149ff08: add_rules (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void add_rules(struct ima_rule_entry *entries, int count, enum policy_rule_list policy_rule);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/integrity/ima/ima_policy.c (ffffffff814ba3c8)
Location: security/integrity/ima/ima_policy.c:574
Inline: False
Direct callers:
  - security/integrity/ima/ima_policy.c:ima_init_policy
  - security/integrity/ima/ima_policy.c:ima_init_policy
  - security/integrity/ima/ima_policy.c:ima_init_policy
  - security/integrity/ima/ima_policy.c:ima_init_policy
  - security/integrity/ima/ima_policy.c:ima_init_policy
  - security/integrity/ima/ima_policy.c:ima_init_policy
```
**Symbols:**

```
ffffffff814ba3c8-ffffffff814ba4b8: add_rules (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In security/integrity/ima/ima_policy.c (ffffffff8151a6dd)
Location: security/integrity/ima/ima_policy.c:680
Inline: True
Direct callers:
  - security/integrity/ima/ima_policy.c:ima_init_policy
  - security/integrity/ima/ima_policy.c:ima_init_policy
  - security/integrity/ima/ima_policy.c:ima_init_policy
  - security/integrity/ima/ima_policy.c:ima_init_policy
  - security/integrity/ima/ima_policy.c:ima_init_policy
```
**Symbols:**

```
ffffffff8151a6dd-ffffffff8151a7c3: add_rules.constprop.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In security/integrity/ima/ima_policy.c (ffffffff81bf1d44)
Location: security/integrity/ima/ima_policy.c:726
Inline: True
Direct callers:
  - security/integrity/ima/ima_policy.c:ima_init_policy
  - security/integrity/ima/ima_policy.c:ima_init_policy
  - security/integrity/ima/ima_policy.c:ima_init_policy
  - security/integrity/ima/ima_policy.c:ima_init_policy
  - security/integrity/ima/ima_policy.c:ima_init_policy
```
**Symbols:**

```
ffffffff81bf1d44-ffffffff81bf1e2a: add_rules.constprop.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In security/integrity/ima/ima_policy.c (ffffffff81be3d64)
Location: security/integrity/ima/ima_policy.c:760
Inline: True
Direct callers:
  - security/integrity/ima/ima_policy.c:ima_init_policy
  - security/integrity/ima/ima_policy.c:ima_init_policy
  - security/integrity/ima/ima_policy.c:ima_init_policy
  - security/integrity/ima/ima_policy.c:ima_init_policy
  - security/integrity/ima/ima_policy.c:ima_init_policy
  - security/integrity/ima/ima_policy.c:ima_init_policy
```
**Symbols:**

```
ffffffff81be3d64-ffffffff81be3e3b: add_rules.constprop.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In security/integrity/ima/ima_policy.c (ffffffff81cd7007)
Location: security/integrity/ima/ima_policy.c:813
Inline: True
Direct callers:
  - security/integrity/ima/ima_policy.c:ima_init_policy
  - security/integrity/ima/ima_policy.c:ima_init_policy
  - security/integrity/ima/ima_policy.c:ima_init_policy
  - security/integrity/ima/ima_policy.c:ima_init_policy
  - security/integrity/ima/ima_policy.c:ima_init_policy
  - security/integrity/ima/ima_policy.c:ima_init_policy
```
**Symbols:**

```
ffffffff81cd7007-ffffffff81cd70de: add_rules.constprop.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void add_rules(struct ima_rule_entry *entries, int count, enum policy_rule_list policy_rule);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/integrity/ima/ima_policy.c (ffffffff81e8a21d)
Location: security/integrity/ima/ima_policy.c:847
Inline: False
Direct callers:
  - security/integrity/ima/ima_policy.c:ima_init_policy
  - security/integrity/ima/ima_policy.c:ima_init_policy
  - security/integrity/ima/ima_policy.c:ima_init_policy
  - security/integrity/ima/ima_policy.c:ima_init_policy
  - security/integrity/ima/ima_policy.c:ima_init_policy
  - security/integrity/ima/ima_policy.c:ima_init_policy
  - security/integrity/ima/ima_policy.c:ima_init_policy
```
**Symbols:**

```
ffffffff81e8a21d-ffffffff81e8a335: add_rules (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
void add_rules(struct ima_rule_entry *entries, int count, enum policy_rule_list policy_rule);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/integrity/ima/ima_policy.c (ffffffff83ed6d45)
Location: security/integrity/ima/ima_policy.c:894
Inline: True
Inline callers:
  - security/integrity/ima/ima_policy.c:ima_init_policy
  - security/integrity/ima/ima_policy.c:ima_init_policy
  - security/integrity/ima/ima_policy.c:ima_init_policy
  - security/integrity/ima/ima_policy.c:ima_init_policy
  - security/integrity/ima/ima_policy.c:ima_init_policy
  - security/integrity/ima/ima_policy.c:ima_init_policy
Direct callers:
  - security/integrity/ima/ima_policy.c:ima_init_policy
```
**Symbols:**

```
ffffffff816fa300-ffffffff816fa451: add_rules (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
void add_rules(struct ima_rule_entry *entries, int count, enum policy_rule_list policy_rule);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/integrity/ima/ima_policy.c (ffffffff81734400)
Location: security/integrity/ima/ima_policy.c:896
Inline: True
Inline callers:
  - security/integrity/ima/ima_policy.c:ima_init_policy
  - security/integrity/ima/ima_policy.c:ima_init_policy
  - security/integrity/ima/ima_policy.c:ima_init_policy
  - security/integrity/ima/ima_policy.c:ima_init_policy
  - security/integrity/ima/ima_policy.c:ima_init_policy
  - security/integrity/ima/ima_policy.c:ima_init_policy
Direct callers:
  - security/integrity/ima/ima_policy.c:ima_init_policy
```
**Symbols:**

```
ffffffff81734400-ffffffff81734551: add_rules (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
void add_rules(struct ima_rule_entry *entries, int count, enum policy_rule_list policy_rule);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/integrity/ima/ima_policy.c (ffffffff81774f10)
Location: security/integrity/ima/ima_policy.c:889
Inline: True
Inline callers:
  - security/integrity/ima/ima_policy.c:ima_init_policy
  - security/integrity/ima/ima_policy.c:ima_init_policy
  - security/integrity/ima/ima_policy.c:ima_init_policy
  - security/integrity/ima/ima_policy.c:ima_init_policy
  - security/integrity/ima/ima_policy.c:ima_init_policy
  - security/integrity/ima/ima_policy.c:ima_init_policy
Direct callers:
  - security/integrity/ima/ima_policy.c:ima_init_policy
```
**Symbols:**

```
ffffffff81774f10-ffffffff81775061: add_rules (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In security/integrity/ima/ima_policy.c (ffff8000105b27e0)
Location: security/integrity/ima/ima_policy.c:574
Inline: True
Direct callers:
  - security/integrity/ima/ima_policy.c:ima_init_policy
  - security/integrity/ima/ima_policy.c:ima_init_policy
  - security/integrity/ima/ima_policy.c:ima_init_policy
  - security/integrity/ima/ima_policy.c:ima_init_policy
  - security/integrity/ima/ima_policy.c:ima_init_policy
```
**Symbols:**

```
ffff8000105b27e0-ffff8000105b28b8: add_rules.constprop.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In security/integrity/ima/ima_policy.c (c0761eac)
Location: security/integrity/ima/ima_policy.c:574
Inline: True
Direct callers:
  - security/integrity/ima/ima_policy.c:ima_init_policy
  - security/integrity/ima/ima_policy.c:ima_init_policy
  - security/integrity/ima/ima_policy.c:ima_init_policy
  - security/integrity/ima/ima_policy.c:ima_init_policy
  - security/integrity/ima/ima_policy.c:ima_init_policy
```
**Symbols:**

```
c0761eac-c0761f5c: add_rules.constprop.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void add_rules(struct ima_rule_entry *entries, int count, enum policy_rule_list policy_rule);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/integrity/ima/ima_policy.c (c000000000734928)
Location: security/integrity/ima/ima_policy.c:574
Inline: False
Direct callers:
  - security/integrity/ima/ima_policy.c:ima_init_policy
  - security/integrity/ima/ima_policy.c:ima_init_policy
  - security/integrity/ima/ima_policy.c:ima_init_policy
  - security/integrity/ima/ima_policy.c:ima_init_policy
  - security/integrity/ima/ima_policy.c:ima_init_policy
  - security/integrity/ima/ima_policy.c:ima_init_policy
```
**Symbols:**

```
c000000000734928-c000000000734a8c: add_rules (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In security/integrity/ima/ima_policy.c (ffffffe0003fa00e)
Location: security/integrity/ima/ima_policy.c:574
Inline: True
Direct callers:
  - security/integrity/ima/ima_policy.c:ima_init_policy
  - security/integrity/ima/ima_policy.c:ima_init_policy
  - security/integrity/ima/ima_policy.c:ima_init_policy
  - security/integrity/ima/ima_policy.c:ima_init_policy
  - security/integrity/ima/ima_policy.c:ima_init_policy
```
**Symbols:**

```
ffffffe0003fa00e-ffffffe0003fa0aa: add_rules.constprop.0 (STB_LOCAL)
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
void add_rules(struct ima_rule_entry *entries, int count, enum policy_rule_list policy_rule);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/integrity/ima/ima_policy.c (ffffffff814b29a8)
Location: security/integrity/ima/ima_policy.c:574
Inline: False
Direct callers:
  - security/integrity/ima/ima_policy.c:ima_init_policy
  - security/integrity/ima/ima_policy.c:ima_init_policy
  - security/integrity/ima/ima_policy.c:ima_init_policy
  - security/integrity/ima/ima_policy.c:ima_init_policy
  - security/integrity/ima/ima_policy.c:ima_init_policy
  - security/integrity/ima/ima_policy.c:ima_init_policy
```
**Symbols:**

```
ffffffff814b29a8-ffffffff814b2a98: add_rules (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void add_rules(struct ima_rule_entry *entries, int count, enum policy_rule_list policy_rule);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/integrity/ima/ima_policy.c (ffffffff814a33c8)
Location: security/integrity/ima/ima_policy.c:574
Inline: False
Direct callers:
  - security/integrity/ima/ima_policy.c:ima_init_policy
  - security/integrity/ima/ima_policy.c:ima_init_policy
  - security/integrity/ima/ima_policy.c:ima_init_policy
  - security/integrity/ima/ima_policy.c:ima_init_policy
  - security/integrity/ima/ima_policy.c:ima_init_policy
  - security/integrity/ima/ima_policy.c:ima_init_policy
```
**Symbols:**

```
ffffffff814a33c8-ffffffff814a34b8: add_rules (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void add_rules(struct ima_rule_entry *entries, int count, enum policy_rule_list policy_rule);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/integrity/ima/ima_policy.c (ffffffff814aea38)
Location: security/integrity/ima/ima_policy.c:574
Inline: False
Direct callers:
  - security/integrity/ima/ima_policy.c:ima_init_policy
  - security/integrity/ima/ima_policy.c:ima_init_policy
  - security/integrity/ima/ima_policy.c:ima_init_policy
  - security/integrity/ima/ima_policy.c:ima_init_policy
  - security/integrity/ima/ima_policy.c:ima_init_policy
  - security/integrity/ima/ima_policy.c:ima_init_policy
```
**Symbols:**

```
ffffffff814aea38-ffffffff814aeb28: add_rules (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void add_rules(struct ima_rule_entry *entries, int count, enum policy_rule_list policy_rule);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/integrity/ima/ima_policy.c (ffffffff814c74a4)
Location: security/integrity/ima/ima_policy.c:574
Inline: False
Direct callers:
  - security/integrity/ima/ima_policy.c:ima_init_policy
  - security/integrity/ima/ima_policy.c:ima_init_policy
  - security/integrity/ima/ima_policy.c:ima_init_policy
  - security/integrity/ima/ima_policy.c:ima_init_policy
  - security/integrity/ima/ima_policy.c:ima_init_policy
  - security/integrity/ima/ima_policy.c:ima_init_policy
```
**Symbols:**

```
ffffffff814c74a4-ffffffff814c7594: add_rules (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>5.0</code> and <code>5.3</code> ✅
</li>
<li>
No changes between <code>5.3</code> and <code>5.4</code> ✅
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
<b>Arch</b>
<ul>
<li>
No changes between <code>amd64</code> and <code>ppc64el</code> ✅
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
