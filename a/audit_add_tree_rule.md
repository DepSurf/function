# Function: <code>audit_add_tree_rule</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int audit_add_tree_rule(struct audit_krule *rule);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/audit_tree.c (ffffffff8112c0d0)
Location: kernel/audit_tree.c:709
Inline: False
Direct callers:
  - kernel/auditfilter.c:audit_rule_change
```
**Symbols:**

```
ffffffff8112c0d0-ffffffff8112c3d2: audit_add_tree_rule (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int audit_add_tree_rule(struct audit_krule *rule);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/audit_tree.c (ffffffff811342b0)
Location: kernel/audit_tree.c:707
Inline: False
Direct callers:
  - kernel/auditfilter.c:audit_rule_change
```
**Symbols:**

```
ffffffff811342b0-ffffffff811345cf: audit_add_tree_rule (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int audit_add_tree_rule(struct audit_krule *rule);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/audit_tree.c (ffffffff8113e030)
Location: kernel/audit_tree.c:716
Inline: False
Direct callers:
  - kernel/auditfilter.c:audit_rule_change
```
**Symbols:**

```
ffffffff8113e030-ffffffff8113e34f: audit_add_tree_rule (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int audit_add_tree_rule(struct audit_krule *rule);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/audit_tree.c (ffffffff8113f6d0)
Location: kernel/audit_tree.c:749
Inline: False
Direct callers:
  - kernel/auditfilter.c:audit_rule_change
```
**Symbols:**

```
ffffffff8113f6d0-ffffffff8113f9ef: audit_add_tree_rule (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int audit_add_tree_rule(struct audit_krule *rule);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/audit_tree.c (ffffffff8114c520)
Location: kernel/audit_tree.c:750
Inline: False
Direct callers:
  - kernel/auditfilter.c:audit_rule_change
```
**Symbols:**

```
ffffffff8114c520-ffffffff8114c85b: audit_add_tree_rule (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int audit_add_tree_rule(struct audit_krule *rule);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/audit_tree.c (ffffffff8115af70)
Location: kernel/audit_tree.c:750
Inline: False
Direct callers:
  - kernel/auditfilter.c:audit_rule_change
```
**Symbols:**

```
ffffffff8115af70-ffffffff8115b2cc: audit_add_tree_rule (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int audit_add_tree_rule(struct audit_krule *rule);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/audit_tree.c (ffffffff81167cd0)
Location: kernel/audit_tree.c:801
Inline: False
Direct callers:
  - kernel/auditfilter.c:audit_rule_change
```
**Symbols:**

```
ffffffff81167cd0-ffffffff8116802c: audit_add_tree_rule (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
int audit_add_tree_rule(struct audit_krule *rule);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/audit_tree.c (0)
Location: kernel/audit_tree.c:802
Inline: False
Direct callers:
  - kernel/auditfilter.c:audit_rule_change
```
**Symbols:**

```
ffffffff81175116-ffffffff8117513f: audit_add_tree_rule.cold (STB_LOCAL)
ffffffff81174910-ffffffff81174c5b: audit_add_tree_rule (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
int audit_add_tree_rule(struct audit_krule *rule);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/audit_tree.c (0)
Location: kernel/audit_tree.c:802
Inline: False
Direct callers:
  - kernel/auditfilter.c:audit_rule_change
```
**Symbols:**

```
ffffffff81180f86-ffffffff81180faf: audit_add_tree_rule.cold (STB_LOCAL)
ffffffff81180780-ffffffff81180acb: audit_add_tree_rule (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
int audit_add_tree_rule(struct audit_krule *rule);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/audit_tree.c (0)
Location: kernel/audit_tree.c:802
Inline: False
Direct callers:
  - kernel/auditfilter.c:audit_add_rule
```
**Symbols:**

```
ffffffff81194906-ffffffff8119492f: audit_add_tree_rule.cold (STB_LOCAL)
ffffffff81193f70-ffffffff81194353: audit_add_tree_rule (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
int audit_add_tree_rule(struct audit_krule *rule);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/audit_tree.c (0)
Location: kernel/audit_tree.c:800
Inline: False
Direct callers:
  - kernel/auditfilter.c:audit_add_rule
```
**Symbols:**

```
ffffffff81be4a02-ffffffff81be4a2b: audit_add_tree_rule.cold (STB_LOCAL)
ffffffff811910e0-ffffffff811914c3: audit_add_tree_rule (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
int audit_add_tree_rule(struct audit_krule *rule);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/audit_tree.c (0)
Location: kernel/audit_tree.c:800
Inline: False
Direct callers:
  - kernel/auditfilter.c:audit_add_rule
```
**Symbols:**

```
ffffffff81bd6863-ffffffff81bd688c: audit_add_tree_rule.cold (STB_LOCAL)
ffffffff81192030-ffffffff8119240c: audit_add_tree_rule (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int audit_add_tree_rule(struct audit_krule *rule);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/audit_tree.c (0)
Location: kernel/audit_tree.c:799
Inline: False
Direct callers:
  - kernel/auditfilter.c:audit_add_rule
```
**Symbols:**

```
ffffffff81cb36d5-ffffffff81cb36fe: audit_add_tree_rule.cold (STB_LOCAL)
ffffffff811baee0-ffffffff811bb2bc: audit_add_tree_rule (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int audit_add_tree_rule(struct audit_krule *rule);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/audit_tree.c (0)
Location: kernel/audit_tree.c:800
Inline: False
Direct callers:
  - kernel/auditfilter.c:audit_add_rule
```
**Symbols:**

```
ffffffff81e644c2-ffffffff81e644e8: audit_add_tree_rule.cold (STB_LOCAL)
ffffffff811ee300-ffffffff811ee6c8: audit_add_tree_rule (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int audit_add_tree_rule(struct audit_krule *rule);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/audit_tree.c (ffffffff81234990)
Location: kernel/audit_tree.c:800
Inline: False
Direct callers:
  - kernel/auditfilter.c:audit_add_rule
```
**Symbols:**

```
ffffffff81234990-ffffffff81234d79: audit_add_tree_rule (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int audit_add_tree_rule(struct audit_krule *rule);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/audit_tree.c (ffffffff8124b680)
Location: kernel/audit_tree.c:800
Inline: False
Direct callers:
  - kernel/auditfilter.c:audit_add_rule
```
**Symbols:**

```
ffffffff8124b680-ffffffff8124ba63: audit_add_tree_rule (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int audit_add_tree_rule(struct audit_krule *rule);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/audit_tree.c (ffffffff81265580)
Location: kernel/audit_tree.c:800
Inline: False
Direct callers:
  - kernel/auditfilter.c:audit_add_rule
```
**Symbols:**

```
ffffffff81265580-ffffffff81265963: audit_add_tree_rule (STB_GLOBAL)
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
int audit_add_tree_rule(struct audit_krule *rule);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/audit_tree.c (ffff8000101f5c18)
Location: kernel/audit_tree.c:802
Inline: False
Direct callers:
  - kernel/auditfilter.c:audit_rule_change
```
**Symbols:**

```
ffff8000101f5c18-ffff8000101f5f68: audit_add_tree_rule (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int audit_add_tree_rule(struct audit_krule *rule);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/audit_tree.c (c0435c78)
Location: kernel/audit_tree.c:802
Inline: False
Direct callers:
  - kernel/auditfilter.c:audit_rule_change
```
**Symbols:**

```
c0435c78-c0435fd4: audit_add_tree_rule (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int audit_add_tree_rule(struct audit_krule *rule);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/audit_tree.c (c00000000026b3c0)
Location: kernel/audit_tree.c:802
Inline: False
Direct callers:
  - kernel/auditfilter.c:audit_rule_change
```
**Symbols:**

```
c00000000026b3c0-c00000000026b964: audit_add_tree_rule (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int audit_add_tree_rule(struct audit_krule *rule);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/audit_tree.c (ffffffe000168d46)
Location: kernel/audit_tree.c:802
Inline: False
Direct callers:
  - kernel/auditfilter.c:audit_rule_change
```
**Symbols:**

```
ffffffe000168d46-ffffffe00016902a: audit_add_tree_rule (STB_GLOBAL)
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
int audit_add_tree_rule(struct audit_krule *rule);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/audit_tree.c (0)
Location: kernel/audit_tree.c:802
Inline: False
Direct callers:
  - kernel/auditfilter.c:audit_rule_change
```
**Symbols:**

```
ffffffff811795a6-ffffffff811795cf: audit_add_tree_rule.cold (STB_LOCAL)
ffffffff81178da0-ffffffff811790eb: audit_add_tree_rule (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Transformation ⚠️</summary>

```c
int audit_add_tree_rule(struct audit_krule *rule);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/audit_tree.c (0)
Location: kernel/audit_tree.c:802
Inline: False
Direct callers:
  - kernel/auditfilter.c:audit_rule_change
```
**Symbols:**

```
ffffffff8116c746-ffffffff8116c76f: audit_add_tree_rule.cold (STB_LOCAL)
ffffffff8116bf40-ffffffff8116c28b: audit_add_tree_rule (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Transformation ⚠️</summary>

```c
int audit_add_tree_rule(struct audit_krule *rule);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/audit_tree.c (0)
Location: kernel/audit_tree.c:802
Inline: False
Direct callers:
  - kernel/auditfilter.c:audit_rule_change
```
**Symbols:**

```
ffffffff81177376-ffffffff8117739f: audit_add_tree_rule.cold (STB_LOCAL)
ffffffff81176b70-ffffffff81176ebb: audit_add_tree_rule (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
int audit_add_tree_rule(struct audit_krule *rule);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/audit_tree.c (0)
Location: kernel/audit_tree.c:802
Inline: False
Direct callers:
  - kernel/auditfilter.c:audit_rule_change
```
**Symbols:**

```
ffffffff81184c46-ffffffff81184c6e: audit_add_tree_rule.cold (STB_LOCAL)
ffffffff81184450-ffffffff81184783: audit_add_tree_rule (STB_GLOBAL)
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
