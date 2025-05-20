# Function: <code>rule_find</code>

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
<details>
<summary>In <code>4.18</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/core/fib_rules.c (ffffffff818c1a3e)
Location: net/core/fib_rules.c:390
Inline: True
Inline callers:
  - net/core/fib_rules.c:fib_nl_delrule
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
In net/core/fib_rules.c (ffffffff818ea8ae)
Location: net/core/fib_rules.c:390
Inline: True
Inline callers:
  - net/core/fib_rules.c:fib_nl_delrule
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
In net/core/fib_rules.c (ffffffff8193a317)
Location: net/core/fib_rules.c:387
Inline: True
Inline callers:
  - net/core/fib_rules.c:fib_nl_delrule
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
In net/core/fib_rules.c (ffffffff8196d1d7)
Location: net/core/fib_rules.c:387
Inline: True
Inline callers:
  - net/core/fib_rules.c:fib_nl_delrule
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
struct fib_rule *rule_find(struct fib_rules_ops *ops, struct fib_rule_hdr *frh, struct nlattr **tb, struct fib_rule *rule, bool user_priority);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/fib_rules.c (ffffffff81a3f340)
Location: net/core/fib_rules.c:394
Inline: False
Direct callers:
  - net/core/fib_rules.c:fib_nl_delrule
```
**Symbols:**

```
ffffffff81a3f340-ffffffff81a3f589: rule_find (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
struct fib_rule *rule_find(struct fib_rules_ops *ops, struct fib_rule_hdr *frh, struct nlattr **tb, struct fib_rule *rule, bool user_priority);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/fib_rules.c (ffffffff81a41fa0)
Location: net/core/fib_rules.c:417
Inline: False
Direct callers:
  - net/core/fib_rules.c:fib_nl_delrule
```
**Symbols:**

```
ffffffff81a41fa0-ffffffff81a421e9: rule_find (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
struct fib_rule *rule_find(struct fib_rules_ops *ops, struct fib_rule_hdr *frh, struct nlattr **tb, struct fib_rule *rule, bool user_priority);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/fib_rules.c (ffffffff81a26c80)
Location: net/core/fib_rules.c:417
Inline: False
Direct callers:
  - net/core/fib_rules.c:fib_nl_delrule
```
**Symbols:**

```
ffffffff81a26c80-ffffffff81a26ec7: rule_find (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
struct fib_rule *rule_find(struct fib_rules_ops *ops, struct fib_rule_hdr *frh, struct nlattr **tb, struct fib_rule *rule, bool user_priority);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/fib_rules.c (ffffffff81adb9b0)
Location: net/core/fib_rules.c:417
Inline: False
Direct callers:
  - net/core/fib_rules.c:fib_nl_delrule
```
**Symbols:**

```
ffffffff81adb9b0-ffffffff81adbbf7: rule_find (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
struct fib_rule *rule_find(struct fib_rules_ops *ops, struct fib_rule_hdr *frh, struct nlattr **tb, struct fib_rule *rule, bool user_priority);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/fib_rules.c (ffffffff81c5cd60)
Location: net/core/fib_rules.c:417
Inline: False
Direct callers:
  - net/core/fib_rules.c:fib_nl_delrule
```
**Symbols:**

```
ffffffff81c5cd60-ffffffff81c5cfaf: rule_find (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
struct fib_rule *rule_find(struct fib_rules_ops *ops, struct fib_rule_hdr *frh, struct nlattr **tb, struct fib_rule *rule, bool user_priority);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/fib_rules.c (ffffffff81e134a0)
Location: net/core/fib_rules.c:417
Inline: False
Direct callers:
  - net/core/fib_rules.c:fib_nl_delrule
```
**Symbols:**

```
ffffffff81e134a0-ffffffff81e136e4: rule_find (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
struct fib_rule *rule_find(struct fib_rules_ops *ops, struct fib_rule_hdr *frh, struct nlattr **tb, struct fib_rule *rule, bool user_priority);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/fib_rules.c (ffffffff81e86de0)
Location: net/core/fib_rules.c:417
Inline: False
Direct callers:
  - net/core/fib_rules.c:fib_nl_delrule
```
**Symbols:**

```
ffffffff81e86de0-ffffffff81e87024: rule_find (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
struct fib_rule *rule_find(struct fib_rules_ops *ops, struct fib_rule_hdr *frh, struct nlattr **tb, struct fib_rule *rule, bool user_priority);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/fib_rules.c (ffffffff81f48df0)
Location: net/core/fib_rules.c:416
Inline: False
Direct callers:
  - net/core/fib_rules.c:fib_nl_delrule
```
**Symbols:**

```
ffffffff81f48df0-ffffffff81f49034: rule_find (STB_LOCAL)
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
In net/core/fib_rules.c (ffff800010c138f0)
Location: net/core/fib_rules.c:387
Inline: True
Inline callers:
  - net/core/fib_rules.c:fib_nl_delrule
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
In net/core/fib_rules.c (c0d2b2d4)
Location: net/core/fib_rules.c:387
Inline: True
Inline callers:
  - net/core/fib_rules.c:fib_nl_delrule
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
In net/core/fib_rules.c (c000000000d00d40)
Location: net/core/fib_rules.c:387
Inline: True
Inline callers:
  - net/core/fib_rules.c:fib_nl_delrule
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
In net/core/fib_rules.c (ffffffe00078f106)
Location: net/core/fib_rules.c:387
Inline: True
Inline callers:
  - net/core/fib_rules.c:fib_nl_delrule
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
In net/core/fib_rules.c (ffffffff8190d1a7)
Location: net/core/fib_rules.c:387
Inline: True
Inline callers:
  - net/core/fib_rules.c:fib_nl_delrule
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
In net/core/fib_rules.c (ffffffff818c6f67)
Location: net/core/fib_rules.c:387
Inline: True
Inline callers:
  - net/core/fib_rules.c:fib_nl_delrule
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
In net/core/fib_rules.c (ffffffff8195e1d7)
Location: net/core/fib_rules.c:387
Inline: True
Inline callers:
  - net/core/fib_rules.c:fib_nl_delrule
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
In net/core/fib_rules.c (ffffffff81980427)
Location: net/core/fib_rules.c:387
Inline: True
Inline callers:
  - net/core/fib_rules.c:fib_nl_delrule
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
