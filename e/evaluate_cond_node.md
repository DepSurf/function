# Function: <code>evaluate_cond_node</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int evaluate_cond_node(struct policydb *p, struct cond_node *node);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/ss/conditional.c (ffffffff8135add0)
Location: security/selinux/ss/conditional.c:90
Inline: False
Direct callers:
  - security/selinux/ss/services.c:security_load_policy
  - security/selinux/ss/services.c:security_set_bools
```
**Symbols:**

```
ffffffff8135add0-ffffffff8135afda: evaluate_cond_node (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int evaluate_cond_node(struct policydb *p, struct cond_node *node);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/ss/conditional.c (ffffffff81390d70)
Location: security/selinux/ss/conditional.c:90
Inline: False
Direct callers:
  - security/selinux/ss/services.c:security_set_bools
  - security/selinux/ss/services.c:security_load_policy
```
**Symbols:**

```
ffffffff81390d70-ffffffff81390f7a: evaluate_cond_node (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int evaluate_cond_node(struct policydb *p, struct cond_node *node);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/ss/conditional.c (ffffffff813a7990)
Location: security/selinux/ss/conditional.c:90
Inline: False
Direct callers:
  - security/selinux/ss/services.c:security_set_bools
  - security/selinux/ss/services.c:security_load_policy
```
**Symbols:**

```
ffffffff813a7990-ffffffff813a7b9a: evaluate_cond_node (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int evaluate_cond_node(struct policydb *p, struct cond_node *node);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/ss/conditional.c (ffffffff813be340)
Location: security/selinux/ss/conditional.c:90
Inline: False
Direct callers:
  - security/selinux/ss/services.c:security_set_bools
  - security/selinux/ss/services.c:security_load_policy
```
**Symbols:**

```
ffffffff813be340-ffffffff813be567: evaluate_cond_node (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int evaluate_cond_node(struct policydb *p, struct cond_node *node);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/ss/conditional.c (ffffffff813e44e0)
Location: security/selinux/ss/conditional.c:90
Inline: False
Direct callers:
  - security/selinux/ss/services.c:security_set_bools
  - security/selinux/ss/services.c:security_load_policy
```
**Symbols:**

```
ffffffff813e44e0-ffffffff813e470d: evaluate_cond_node (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Transformation ⚠️</summary>

```c
int evaluate_cond_node(struct policydb *p, struct cond_node *node);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In security/selinux/ss/conditional.c (0)
Location: security/selinux/ss/conditional.c:90
Inline: False
Direct callers:
  - security/selinux/ss/services.c:security_set_bools
  - security/selinux/ss/services.c:security_load_policy
```
**Symbols:**

```
ffffffff81415c11-ffffffff81415c33: evaluate_cond_node.cold.10 (STB_LOCAL)
ffffffff81415180-ffffffff81415394: evaluate_cond_node (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Transformation ⚠️</summary>

```c
int evaluate_cond_node(struct policydb *p, struct cond_node *node);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In security/selinux/ss/conditional.c (0)
Location: security/selinux/ss/conditional.c:90
Inline: False
Direct callers:
  - security/selinux/ss/services.c:security_set_bools
  - security/selinux/ss/services.c:security_load_policy
```
**Symbols:**

```
ffffffff814321d1-ffffffff814321f3: evaluate_cond_node.cold.9 (STB_LOCAL)
ffffffff81431730-ffffffff81431960: evaluate_cond_node (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
int evaluate_cond_node(struct policydb *p, struct cond_node *node);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In security/selinux/ss/conditional.c (0)
Location: security/selinux/ss/conditional.c:88
Inline: False
Direct callers:
  - security/selinux/ss/services.c:security_set_bools
  - security/selinux/ss/services.c:security_load_policy
```
**Symbols:**

```
ffffffff8145fc04-ffffffff8145fc2e: evaluate_cond_node.cold (STB_LOCAL)
ffffffff8145f1e0-ffffffff8145f418: evaluate_cond_node (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
int evaluate_cond_node(struct policydb *p, struct cond_node *node);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In security/selinux/ss/conditional.c (0)
Location: security/selinux/ss/conditional.c:88
Inline: False
Direct callers:
  - security/selinux/ss/services.c:security_set_bools
  - security/selinux/ss/services.c:security_load_policy
```
**Symbols:**

```
ffffffff814799b4-ffffffff814799de: evaluate_cond_node.cold (STB_LOCAL)
ffffffff81478f90-ffffffff814791c8: evaluate_cond_node (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
void evaluate_cond_node(struct policydb *p, struct cond_node *node);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In security/selinux/ss/conditional.c (0)
Location: security/selinux/ss/conditional.c:92
Inline: False
Direct callers:
  - security/selinux/ss/conditional.c:evaluate_cond_nodes
```
**Symbols:**

```
ffffffff814ce3e0-ffffffff814ce47a: evaluate_cond_node (STB_LOCAL)
ffffffff814cef34-ffffffff814cef45: evaluate_cond_node.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
void evaluate_cond_node(struct policydb *p, struct cond_node *node);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In security/selinux/ss/conditional.c (0)
Location: security/selinux/ss/conditional.c:92
Inline: False
Direct callers:
  - security/selinux/ss/conditional.c:evaluate_cond_nodes
```
**Symbols:**

```
ffffffff814eb5a0-ffffffff814eb63a: evaluate_cond_node (STB_LOCAL)
ffffffff81bf11bc-ffffffff81bf11cd: evaluate_cond_node.cold (STB_LOCAL)
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
In security/selinux/ss/conditional.c (ffffffff814f25f0)
Location: security/selinux/ss/conditional.c:92
Inline: True
Inline callers:
  - security/selinux/ss/conditional.c:evaluate_cond_nodes
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
In security/selinux/ss/conditional.c (ffffffff8154d050)
Location: security/selinux/ss/conditional.c:92
Inline: True
Inline callers:
  - security/selinux/ss/conditional.c:evaluate_cond_nodes
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
In security/selinux/ss/conditional.c (ffffffff815e5ff0)
Location: security/selinux/ss/conditional.c:92
Inline: True
Inline callers:
  - security/selinux/ss/conditional.c:evaluate_cond_nodes
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
In security/selinux/ss/conditional.c (ffffffff816955b0)
Location: security/selinux/ss/conditional.c:92
Inline: True
Inline callers:
  - security/selinux/ss/conditional.c:evaluate_cond_nodes
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
In security/selinux/ss/conditional.c (ffffffff816cda8d)
Location: security/selinux/ss/conditional.c:92
Inline: True
Inline callers:
  - security/selinux/ss/conditional.c:evaluate_cond_nodes
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
In security/selinux/ss/conditional.c (ffffffff8170a07d)
Location: security/selinux/ss/conditional.c:92
Inline: True
Inline callers:
  - security/selinux/ss/conditional.c:evaluate_cond_nodes
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
int evaluate_cond_node(struct policydb *p, struct cond_node *node);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/ss/conditional.c (ffff800010569360)
Location: security/selinux/ss/conditional.c:88
Inline: False
Direct callers:
  - security/selinux/ss/services.c:security_set_bools
  - security/selinux/ss/services.c:security_load_policy
```
**Symbols:**

```
ffff800010569360-ffff8000105695d0: evaluate_cond_node (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int evaluate_cond_node(struct policydb *p, struct cond_node *node);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/ss/conditional.c (c071cf68)
Location: security/selinux/ss/conditional.c:88
Inline: False
Direct callers:
  - security/selinux/ss/services.c:security_set_bools
  - security/selinux/ss/services.c:security_load_policy
```
**Symbols:**

```
c071cf68-c071d218: evaluate_cond_node (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int evaluate_cond_node(struct policydb *p, struct cond_node *node);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/ss/conditional.c (c0000000006cc630)
Location: security/selinux/ss/conditional.c:88
Inline: False
Direct callers:
  - security/selinux/ss/services.c:security_set_bools
  - security/selinux/ss/services.c:security_load_policy
```
**Symbols:**

```
c0000000006cc630-c0000000006cc9d8: evaluate_cond_node (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int evaluate_cond_node(struct policydb *p, struct cond_node *node);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/ss/conditional.c (ffffffe0003be40a)
Location: security/selinux/ss/conditional.c:88
Inline: False
Direct callers:
  - security/selinux/ss/services.c:security_set_bools
  - security/selinux/ss/services.c:security_load_policy
```
**Symbols:**

```
ffffffe0003be40a-ffffffe0003be5fe: evaluate_cond_node (STB_GLOBAL)
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
int evaluate_cond_node(struct policydb *p, struct cond_node *node);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In security/selinux/ss/conditional.c (0)
Location: security/selinux/ss/conditional.c:88
Inline: False
Direct callers:
  - security/selinux/ss/services.c:security_set_bools
  - security/selinux/ss/services.c:security_load_policy
```
**Symbols:**

```
ffffffff81471f94-ffffffff81471fbe: evaluate_cond_node.cold (STB_LOCAL)
ffffffff81471570-ffffffff814717a8: evaluate_cond_node (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Transformation ⚠️</summary>

```c
int evaluate_cond_node(struct policydb *p, struct cond_node *node);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In security/selinux/ss/conditional.c (0)
Location: security/selinux/ss/conditional.c:88
Inline: False
Direct callers:
  - security/selinux/ss/services.c:security_set_bools
  - security/selinux/ss/services.c:security_load_policy
```
**Symbols:**

```
ffffffff814629b4-ffffffff814629de: evaluate_cond_node.cold (STB_LOCAL)
ffffffff81461f90-ffffffff814621c8: evaluate_cond_node (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Transformation ⚠️</summary>

```c
int evaluate_cond_node(struct policydb *p, struct cond_node *node);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In security/selinux/ss/conditional.c (0)
Location: security/selinux/ss/conditional.c:88
Inline: False
Direct callers:
  - security/selinux/ss/services.c:security_set_bools
  - security/selinux/ss/services.c:security_load_policy
```
**Symbols:**

```
ffffffff8146e034-ffffffff8146e05e: evaluate_cond_node.cold (STB_LOCAL)
ffffffff8146d610-ffffffff8146d848: evaluate_cond_node (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
int evaluate_cond_node(struct policydb *p, struct cond_node *node);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In security/selinux/ss/conditional.c (0)
Location: security/selinux/ss/conditional.c:88
Inline: False
Direct callers:
  - security/selinux/ss/services.c:security_set_bools
  - security/selinux/ss/services.c:security_load_policy
```
**Symbols:**

```
ffffffff814858a4-ffffffff814858ce: evaluate_cond_node.cold (STB_LOCAL)
ffffffff81484e80-ffffffff814850b8: evaluate_cond_node (STB_GLOBAL)
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
<details>
<summary>Changed between <code>5.4</code> and <code>5.8</code> ⚠️</summary>
<ul>
<li>
<b>Return type changed. </b>
<code>int</code> ➡️ <code>void</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>5.8</code> and <code>5.11</code> ✅
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
