# Function: <code>evaluate_cond_nodes</code>

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
In <code>5.0</code>: Absent ⚠️
</li>
<li>
In <code>5.3</code>: Absent ⚠️
</li>
<li>
In <code>5.4</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void evaluate_cond_nodes(struct policydb *p);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/ss/conditional.c (ffffffff814ce800)
Location: security/selinux/ss/conditional.c:123
Inline: False
Direct callers:
  - security/selinux/ss/services.c:security_preserve_bools
  - security/selinux/ss/services.c:security_set_bools
```
**Symbols:**

```
ffffffff814ce800-ffffffff814ce84f: evaluate_cond_nodes (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void evaluate_cond_nodes(struct policydb *p);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/ss/conditional.c (ffffffff814ebc40)
Location: security/selinux/ss/conditional.c:123
Inline: False
Direct callers:
  - security/selinux/ss/services.c:security_preserve_bools
  - security/selinux/ss/services.c:security_set_bools
```
**Symbols:**

```
ffffffff814ebc40-ffffffff814ebc8f: evaluate_cond_nodes (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
void evaluate_cond_nodes(struct policydb *p);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In security/selinux/ss/conditional.c (0)
Location: security/selinux/ss/conditional.c:123
Inline: False
Direct callers:
  - security/selinux/ss/services.c:security_set_bools
  - security/selinux/ss/services.c:security_load_policy
```
**Symbols:**

```
ffffffff81be32ff-ffffffff81be3310: evaluate_cond_nodes.cold (STB_LOCAL)
ffffffff814f25b0-ffffffff814f2691: evaluate_cond_nodes (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
void evaluate_cond_nodes(struct policydb *p);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In security/selinux/ss/conditional.c (0)
Location: security/selinux/ss/conditional.c:123
Inline: False
Direct callers:
  - security/selinux/ss/services.c:security_set_bools
  - security/selinux/ss/services.c:security_load_policy
```
**Symbols:**

```
ffffffff81cd53b8-ffffffff81cd53c9: evaluate_cond_nodes.cold (STB_LOCAL)
ffffffff8154d010-ffffffff8154d0f1: evaluate_cond_nodes (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
void evaluate_cond_nodes(struct policydb *p);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In security/selinux/ss/conditional.c (0)
Location: security/selinux/ss/conditional.c:123
Inline: False
Direct callers:
  - security/selinux/ss/services.c:security_set_bools
  - security/selinux/ss/services.c:security_load_policy
  - security/selinux/ss/services.c:security_load_policy
```
**Symbols:**

```
ffffffff81e881dc-ffffffff81e881ed: evaluate_cond_nodes.cold (STB_LOCAL)
ffffffff815e5fb0-ffffffff815e60ad: evaluate_cond_nodes (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void evaluate_cond_nodes(struct policydb *p);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/ss/conditional.c (ffffffff81695570)
Location: security/selinux/ss/conditional.c:123
Inline: False
Direct callers:
  - security/selinux/ss/services.c:security_set_bools
  - security/selinux/ss/services.c:security_load_policy
  - security/selinux/ss/services.c:security_load_policy
```
**Symbols:**

```
ffffffff81695570-ffffffff8169567e: evaluate_cond_nodes (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void evaluate_cond_nodes(struct policydb *p);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/ss/conditional.c (ffffffff816cda50)
Location: security/selinux/ss/conditional.c:123
Inline: False
Direct callers:
  - security/selinux/ss/services.c:security_set_bools
  - security/selinux/ss/services.c:security_load_policy
  - security/selinux/ss/services.c:security_load_policy
```
**Symbols:**

```
ffffffff816cda50-ffffffff816cdb59: evaluate_cond_nodes (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void evaluate_cond_nodes(struct policydb *p);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/ss/conditional.c (ffffffff8170a040)
Location: security/selinux/ss/conditional.c:123
Inline: False
Direct callers:
  - security/selinux/ss/services.c:security_set_bools
  - security/selinux/ss/services.c:security_load_policy
  - security/selinux/ss/services.c:security_load_policy
```
**Symbols:**

```
ffffffff8170a040-ffffffff8170a149: evaluate_cond_nodes (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
In <code>arm64</code>: Absent ⚠️
</li>
<li>
In <code>armhf</code>: Absent ⚠️
</li>
<li>
In <code>ppc64el</code>: Absent ⚠️
</li>
<li>
In <code>riscv64</code>: Absent ⚠️
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
In <code>aws</code>: Absent ⚠️
</li>
<li>
In <code>azure</code>: Absent ⚠️
</li>
<li>
In <code>gcp</code>: Absent ⚠️
</li>
<li>
In <code>lowlatency</code>: Absent ⚠️
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
