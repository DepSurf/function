# Function: <code>ima_parse_rule</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int ima_parse_rule(char *rule, struct ima_rule_entry *entry);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/integrity/ima/ima_policy.c (ffffffff81398e50)
Location: security/integrity/ima/ima_policy.c:499
Inline: False
Direct callers:
  - security/integrity/ima/ima_policy.c:ima_parse_add_rule
```
**Symbols:**

```
ffffffff81398e50-ffffffff8139962e: ima_parse_rule (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int ima_parse_rule(char *rule, struct ima_rule_entry *entry);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/integrity/ima/ima_policy.c (ffffffff813d55a0)
Location: security/integrity/ima/ima_policy.c:551
Inline: False
Direct callers:
  - security/integrity/ima/ima_policy.c:ima_parse_add_rule
```
**Symbols:**

```
ffffffff813d55a0-ffffffff813d5ef5: ima_parse_rule (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int ima_parse_rule(char *rule, struct ima_rule_entry *entry);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/integrity/ima/ima_policy.c (ffffffff813ece70)
Location: security/integrity/ima/ima_policy.c:551
Inline: False
Direct callers:
  - security/integrity/ima/ima_policy.c:ima_parse_add_rule
```
**Symbols:**

```
ffffffff813ece70-ffffffff813ed7c5: ima_parse_rule (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int ima_parse_rule(char *rule, struct ima_rule_entry *entry);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/integrity/ima/ima_policy.c (ffffffff813f92d0)
Location: security/integrity/ima/ima_policy.c:608
Inline: False
Direct callers:
  - security/integrity/ima/ima_policy.c:ima_parse_add_rule
```
**Symbols:**

```
ffffffff813f92d0-ffffffff813f9bfb: ima_parse_rule (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int ima_parse_rule(char *rule, struct ima_rule_entry *entry);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/integrity/ima/ima_policy.c (ffffffff81421760)
Location: security/integrity/ima/ima_policy.c:608
Inline: False
Direct callers:
  - security/integrity/ima/ima_policy.c:ima_parse_add_rule
```
**Symbols:**

```
ffffffff81421760-ffffffff8142208a: ima_parse_rule (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int ima_parse_rule(char *rule, struct ima_rule_entry *entry);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/integrity/ima/ima_policy.c (ffffffff81453c90)
Location: security/integrity/ima/ima_policy.c:632
Inline: False
Direct callers:
  - security/integrity/ima/ima_policy.c:ima_parse_add_rule
```
**Symbols:**

```
ffffffff81453c90-ffffffff81454775: ima_parse_rule (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int ima_parse_rule(char *rule, struct ima_rule_entry *entry);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/integrity/ima/ima_policy.c (ffffffff81470e60)
Location: security/integrity/ima/ima_policy.c:761
Inline: False
Direct callers:
  - security/integrity/ima/ima_policy.c:ima_parse_add_rule
  - security/integrity/ima/ima_policy.c:ima_init_arch_policy
```
**Symbols:**

```
ffffffff81470e60-ffffffff81471a42: ima_parse_rule (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int ima_parse_rule(char *rule, struct ima_rule_entry *entry);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/integrity/ima/ima_policy.c (ffffffff8149e8b0)
Location: security/integrity/ima/ima_policy.c:846
Inline: False
Direct callers:
  - security/integrity/ima/ima_policy.c:ima_parse_add_rule
  - security/integrity/ima/ima_policy.c:ima_init_arch_policy
```
**Symbols:**

```
ffffffff8149e8b0-ffffffff8149f508: ima_parse_rule (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
int ima_parse_rule(char *rule, struct ima_rule_entry *entry);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In security/integrity/ima/ima_policy.c (0)
Location: security/integrity/ima/ima_policy.c:892
Inline: False
Direct callers:
  - security/integrity/ima/ima_policy.c:ima_parse_add_rule
  - security/integrity/ima/ima_policy.c:ima_init_arch_policy
```
**Symbols:**

```
ffffffff814b8d50-ffffffff814b9ad2: ima_parse_rule (STB_LOCAL)
ffffffff814ba4f6-ffffffff814ba507: ima_parse_rule.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
int ima_parse_rule(char *rule, struct ima_rule_entry *entry);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In security/integrity/ima/ima_policy.c (0)
Location: security/integrity/ima/ima_policy.c:1065
Inline: False
Direct callers:
  - security/integrity/ima/ima_policy.c:ima_parse_add_rule
```
**Symbols:**

```
ffffffff81518f20-ffffffff8151a0f2: ima_parse_rule (STB_LOCAL)
ffffffff8151a7c3-ffffffff8151a7d4: ima_parse_rule.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
int ima_parse_rule(char *rule, struct ima_rule_entry *entry);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In security/integrity/ima/ima_policy.c (0)
Location: security/integrity/ima/ima_policy.c:1141
Inline: False
Direct callers:
  - security/integrity/ima/ima_policy.c:ima_parse_add_rule
```
**Symbols:**

```
ffffffff81535fc0-ffffffff8153715b: ima_parse_rule (STB_LOCAL)
ffffffff81bf1e2a-ffffffff81bf1e3b: ima_parse_rule.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
int ima_parse_rule(char *rule, struct ima_rule_entry *entry);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In security/integrity/ima/ima_policy.c (0)
Location: security/integrity/ima/ima_policy.c:1194
Inline: False
Direct callers:
  - security/integrity/ima/ima_policy.c:ima_parse_add_rule
```
**Symbols:**

```
ffffffff8153e6e0-ffffffff8153f841: ima_parse_rule (STB_LOCAL)
ffffffff81be3e51-ffffffff81be3e62: ima_parse_rule.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int ima_parse_rule(char *rule, struct ima_rule_entry *entry);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In security/integrity/ima/ima_policy.c (0)
Location: security/integrity/ima/ima_policy.c:1296
Inline: False
Direct callers:
  - security/integrity/ima/ima_policy.c:ima_parse_add_rule
```
**Symbols:**

```
ffffffff8159dad0-ffffffff8159edb3: ima_parse_rule (STB_LOCAL)
ffffffff81cd70f4-ffffffff81cd717b: ima_parse_rule.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int ima_parse_rule(char *rule, struct ima_rule_entry *entry);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In security/integrity/ima/ima_policy.c (0)
Location: security/integrity/ima/ima_policy.c:1390
Inline: False
Direct callers:
  - security/integrity/ima/ima_policy.c:ima_parse_add_rule
  - security/integrity/ima/ima_policy.c:ima_init_arch_policy
```
**Symbols:**

```
ffffffff81642fe0-ffffffff816446d1: ima_parse_rule (STB_LOCAL)
ffffffff81e8a34b-ffffffff81e8a402: ima_parse_rule.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
int ima_parse_rule(char *rule, struct ima_rule_entry *entry);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In security/integrity/ima/ima_policy.c (0)
Location: security/integrity/ima/ima_policy.c:1437
Inline: False
Direct callers:
  - security/integrity/ima/ima_policy.c:ima_parse_add_rule
  - security/integrity/ima/ima_policy.c:ima_init_arch_policy
```
**Symbols:**

```
ffffffff816fb2a0-ffffffff816fc9cf: ima_parse_rule (STB_LOCAL)
ffffffff820753ab-ffffffff820753f5: ima_parse_rule.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
int ima_parse_rule(char *rule, struct ima_rule_entry *entry);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In security/integrity/ima/ima_policy.c (0)
Location: security/integrity/ima/ima_policy.c:1440
Inline: False
Direct callers:
  - security/integrity/ima/ima_policy.c:ima_parse_add_rule
  - security/integrity/ima/ima_policy.c:ima_init_arch_policy
```
**Symbols:**

```
ffffffff81735360-ffffffff817369f7: ima_parse_rule (STB_LOCAL)
ffffffff820f4f09-ffffffff820f4f5d: ima_parse_rule.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
int ima_parse_rule(char *rule, struct ima_rule_entry *entry);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In security/integrity/ima/ima_policy.c (0)
Location: security/integrity/ima/ima_policy.c:1433
Inline: False
Direct callers:
  - security/integrity/ima/ima_policy.c:ima_parse_add_rule
  - security/integrity/ima/ima_policy.c:ima_init_arch_policy
```
**Symbols:**

```
ffffffff81775e40-ffffffff817774bd: ima_parse_rule (STB_LOCAL)
ffffffff821d2097-ffffffff821d20eb: ima_parse_rule.cold (STB_LOCAL)
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
int ima_parse_rule(char *rule, struct ima_rule_entry *entry);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/integrity/ima/ima_policy.c (ffff8000105b1128)
Location: security/integrity/ima/ima_policy.c:892
Inline: False
Direct callers:
  - security/integrity/ima/ima_policy.c:ima_parse_add_rule
```
**Symbols:**

```
ffff8000105b1128-ffff8000105b1e3c: ima_parse_rule (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int ima_parse_rule(char *rule, struct ima_rule_entry *entry);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/integrity/ima/ima_policy.c (c0760764)
Location: security/integrity/ima/ima_policy.c:892
Inline: False
Direct callers:
  - security/integrity/ima/ima_policy.c:ima_parse_add_rule
```
**Symbols:**

```
c0760764-c0761500: ima_parse_rule (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int ima_parse_rule(char *rule, struct ima_rule_entry *entry);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/integrity/ima/ima_policy.c (c0000000007310a0)
Location: security/integrity/ima/ima_policy.c:892
Inline: False
Direct callers:
  - security/integrity/ima/ima_policy.c:ima_parse_add_rule
  - security/integrity/ima/ima_policy.c:ima_init_arch_policy
```
**Symbols:**

```
c0000000007310a0-c000000000733048: ima_parse_rule (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int ima_parse_rule(char *rule, struct ima_rule_entry *entry);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/integrity/ima/ima_policy.c (ffffffe0003f8b8c)
Location: security/integrity/ima/ima_policy.c:892
Inline: False
Direct callers:
  - security/integrity/ima/ima_policy.c:ima_parse_add_rule
```
**Symbols:**

```
ffffffe0003f8b8c-ffffffe0003f9796: ima_parse_rule (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Transformation ⚠️</summary>

```c
int ima_parse_rule(char *rule, struct ima_rule_entry *entry);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In security/integrity/ima/ima_policy.c (0)
Location: security/integrity/ima/ima_policy.c:892
Inline: False
Direct callers:
  - security/integrity/ima/ima_policy.c:ima_parse_add_rule
  - security/integrity/ima/ima_policy.c:ima_init_arch_policy
```
**Symbols:**

```
ffffffff814b1330-ffffffff814b20b2: ima_parse_rule (STB_LOCAL)
ffffffff814b2ad6-ffffffff814b2ae7: ima_parse_rule.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Transformation ⚠️</summary>

```c
int ima_parse_rule(char *rule, struct ima_rule_entry *entry);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In security/integrity/ima/ima_policy.c (0)
Location: security/integrity/ima/ima_policy.c:892
Inline: False
Direct callers:
  - security/integrity/ima/ima_policy.c:ima_parse_add_rule
  - security/integrity/ima/ima_policy.c:ima_init_arch_policy
```
**Symbols:**

```
ffffffff814a1d50-ffffffff814a2ad2: ima_parse_rule (STB_LOCAL)
ffffffff814a34f6-ffffffff814a3507: ima_parse_rule.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Transformation ⚠️</summary>

```c
int ima_parse_rule(char *rule, struct ima_rule_entry *entry);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In security/integrity/ima/ima_policy.c (0)
Location: security/integrity/ima/ima_policy.c:892
Inline: False
Direct callers:
  - security/integrity/ima/ima_policy.c:ima_parse_add_rule
  - security/integrity/ima/ima_policy.c:ima_init_arch_policy
```
**Symbols:**

```
ffffffff814ad3c0-ffffffff814ae142: ima_parse_rule (STB_LOCAL)
ffffffff814aeb66-ffffffff814aeb77: ima_parse_rule.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
int ima_parse_rule(char *rule, struct ima_rule_entry *entry);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In security/integrity/ima/ima_policy.c (0)
Location: security/integrity/ima/ima_policy.c:892
Inline: False
Direct callers:
  - security/integrity/ima/ima_policy.c:ima_parse_add_rule
  - security/integrity/ima/ima_policy.c:ima_init_arch_policy
```
**Symbols:**

```
ffffffff814c5e10-ffffffff814c6b92: ima_parse_rule (STB_LOCAL)
ffffffff814c75d2-ffffffff814c75e3: ima_parse_rule.cold (STB_LOCAL)
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
No changes between <code>5.4</code> and <code>5.8</code> ✅
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
