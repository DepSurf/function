# Function: <code>rule_exists</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>4.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/core/fib_rules.c (ffffffff817a6822)
Location: net/core/fib_rules.c:272
Inline: True
Inline callers:
  - net/core/fib_rules.c:fib_nl_newrule
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
In net/core/fib_rules.c (ffffffff817d52ec)
Location: net/core/fib_rules.c:310
Inline: True
Inline callers:
  - net/core/fib_rules.c:fib_nl_newrule
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
In net/core/fib_rules.c (ffffffff817f494e)
Location: net/core/fib_rules.c:324
Inline: True
Inline callers:
  - net/core/fib_rules.c:fib_nl_newrule
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
In net/core/fib_rules.c (ffffffff81870140)
Location: net/core/fib_rules.c:387
Inline: True
Inline callers:
  - net/core/fib_rules.c:fib_nl_newrule
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
In net/core/fib_rules.c (ffffffff818c17e1)
Location: net/core/fib_rules.c:659
Inline: True
Inline callers:
  - net/core/fib_rules.c:fib_nl_newrule
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
In net/core/fib_rules.c (ffffffff818ea5ef)
Location: net/core/fib_rules.c:659
Inline: True
Inline callers:
  - net/core/fib_rules.c:fib_nl_newrule
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
In net/core/fib_rules.c (ffffffff8193a079)
Location: net/core/fib_rules.c:656
Inline: True
Inline callers:
  - net/core/fib_rules.c:fib_nl_newrule
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
In net/core/fib_rules.c (ffffffff8196cf39)
Location: net/core/fib_rules.c:656
Inline: True
Inline callers:
  - net/core/fib_rules.c:fib_nl_newrule
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int rule_exists(struct fib_rules_ops *ops, struct fib_rule_hdr *frh, struct nlattr **tb, struct fib_rule *rule);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/fib_rules.c (ffffffff81a3f590)
Location: net/core/fib_rules.c:663
Inline: False
Direct callers:
  - net/core/fib_rules.c:fib_nl_newrule
```
**Symbols:**

```
ffffffff81a3f590-ffffffff81a3f708: rule_exists (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int rule_exists(struct fib_rules_ops *ops, struct fib_rule_hdr *frh, struct nlattr **tb, struct fib_rule *rule);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/fib_rules.c (ffffffff81a421f0)
Location: net/core/fib_rules.c:686
Inline: False
Direct callers:
  - net/core/fib_rules.c:fib_nl_newrule
```
**Symbols:**

```
ffffffff81a421f0-ffffffff81a42368: rule_exists (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int rule_exists(struct fib_rules_ops *ops, struct fib_rule_hdr *frh, struct nlattr **tb, struct fib_rule *rule);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/fib_rules.c (ffffffff81a26ed0)
Location: net/core/fib_rules.c:686
Inline: False
Direct callers:
  - net/core/fib_rules.c:fib_nl_newrule
```
**Symbols:**

```
ffffffff81a26ed0-ffffffff81a27072: rule_exists (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int rule_exists(struct fib_rules_ops *ops, struct fib_rule_hdr *frh, struct nlattr **tb, struct fib_rule *rule);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/fib_rules.c (ffffffff81adbc00)
Location: net/core/fib_rules.c:686
Inline: False
Direct callers:
  - net/core/fib_rules.c:fib_nl_newrule
```
**Symbols:**

```
ffffffff81adbc00-ffffffff81adbda2: rule_exists (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int rule_exists(struct fib_rules_ops *ops, struct fib_rule_hdr *frh, struct nlattr **tb, struct fib_rule *rule);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/fib_rules.c (ffffffff81c5cfb0)
Location: net/core/fib_rules.c:686
Inline: False
Direct callers:
  - net/core/fib_rules.c:fib_nl_newrule
```
**Symbols:**

```
ffffffff81c5cfb0-ffffffff81c5d131: rule_exists (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int rule_exists(struct fib_rules_ops *ops, struct fib_rule_hdr *frh, struct nlattr **tb, struct fib_rule *rule);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/fib_rules.c (ffffffff81e13700)
Location: net/core/fib_rules.c:686
Inline: False
Direct callers:
  - net/core/fib_rules.c:fib_nl_newrule
```
**Symbols:**

```
ffffffff81e13700-ffffffff81e138bd: rule_exists (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int rule_exists(struct fib_rules_ops *ops, struct fib_rule_hdr *frh, struct nlattr **tb, struct fib_rule *rule);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/fib_rules.c (ffffffff81e87040)
Location: net/core/fib_rules.c:686
Inline: False
Direct callers:
  - net/core/fib_rules.c:fib_nl_newrule
```
**Symbols:**

```
ffffffff81e87040-ffffffff81e871fd: rule_exists (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int rule_exists(struct fib_rules_ops *ops, struct fib_rule_hdr *frh, struct nlattr **tb, struct fib_rule *rule);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/fib_rules.c (ffffffff81f49050)
Location: net/core/fib_rules.c:684
Inline: False
Direct callers:
  - net/core/fib_rules.c:fib_nl_newrule
```
**Symbols:**

```
ffffffff81f49050-ffffffff81f4920d: rule_exists (STB_LOCAL)
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
In net/core/fib_rules.c (ffff800010c136e8)
Location: net/core/fib_rules.c:656
Inline: True
Inline callers:
  - net/core/fib_rules.c:fib_nl_newrule
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
In net/core/fib_rules.c (c0d2af6c)
Location: net/core/fib_rules.c:656
Inline: True
Inline callers:
  - net/core/fib_rules.c:fib_nl_newrule
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
In net/core/fib_rules.c (c000000000d00828)
Location: net/core/fib_rules.c:656
Inline: True
Inline callers:
  - net/core/fib_rules.c:fib_nl_newrule
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
In net/core/fib_rules.c (ffffffe00078ee2c)
Location: net/core/fib_rules.c:656
Inline: True
Inline callers:
  - net/core/fib_rules.c:fib_nl_newrule
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
In net/core/fib_rules.c (ffffffff8190cf09)
Location: net/core/fib_rules.c:656
Inline: True
Inline callers:
  - net/core/fib_rules.c:fib_nl_newrule
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
In net/core/fib_rules.c (ffffffff818c6cc9)
Location: net/core/fib_rules.c:656
Inline: True
Inline callers:
  - net/core/fib_rules.c:fib_nl_newrule
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
In net/core/fib_rules.c (ffffffff8195df39)
Location: net/core/fib_rules.c:656
Inline: True
Inline callers:
  - net/core/fib_rules.c:fib_nl_newrule
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
In net/core/fib_rules.c (ffffffff81980189)
Location: net/core/fib_rules.c:656
Inline: True
Inline callers:
  - net/core/fib_rules.c:fib_nl_newrule
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
