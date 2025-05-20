# Function: <code>__irq_build_affinity_masks</code>

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
<summary>In <code>5.0</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/irq/affinity.c (ffffffff8110be70)
Location: kernel/irq/affinity.c:97
Inline: True
Direct callers:
  - kernel/irq/affinity.c:irq_create_affinity_masks
  - kernel/irq/affinity.c:irq_create_affinity_masks
  - kernel/irq/affinity.c:irq_create_affinity_masks
```
**Symbols:**

```
ffffffff8110be70-ffffffff8110c2a7: __irq_build_affinity_masks.isra.1 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int __irq_build_affinity_masks(unsigned int startvec, unsigned int numvecs, unsigned int firstvec, cpumask_var_t *node_to_cpumask, const struct cpumask *cpu_mask, struct cpumask *nmsk, struct irq_affinity_desc *masks);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/affinity.c (ffffffff811155e0)
Location: kernel/irq/affinity.c:97
Inline: False
Direct callers:
  - kernel/irq/affinity.c:irq_create_affinity_masks
  - kernel/irq/affinity.c:irq_create_affinity_masks
  - kernel/irq/affinity.c:irq_create_affinity_masks
```
**Symbols:**

```
ffffffff811155e0-ffffffff81115a36: __irq_build_affinity_masks (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int __irq_build_affinity_masks(unsigned int startvec, unsigned int numvecs, unsigned int firstvec, cpumask_var_t *node_to_cpumask, const struct cpumask *cpu_mask, struct cpumask *nmsk, struct irq_affinity_desc *masks);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/affinity.c (ffffffff811217e0)
Location: kernel/irq/affinity.c:247
Inline: False
Direct callers:
  - kernel/irq/affinity.c:irq_create_affinity_masks
  - kernel/irq/affinity.c:irq_create_affinity_masks
```
**Symbols:**

```
ffffffff811217e0-ffffffff81121e45: __irq_build_affinity_masks (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int __irq_build_affinity_masks(unsigned int startvec, unsigned int numvecs, unsigned int firstvec, cpumask_var_t *node_to_cpumask, const struct cpumask *cpu_mask, struct cpumask *nmsk, struct irq_affinity_desc *masks);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/affinity.c (ffffffff8112e0d0)
Location: kernel/irq/affinity.c:247
Inline: False
Direct callers:
  - kernel/irq/affinity.c:irq_build_affinity_masks
  - kernel/irq/affinity.c:irq_build_affinity_masks
```
**Symbols:**

```
ffffffff8112e0d0-ffffffff8112e406: __irq_build_affinity_masks (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int __irq_build_affinity_masks(unsigned int startvec, unsigned int numvecs, unsigned int firstvec, cpumask_var_t *node_to_cpumask, const struct cpumask *cpu_mask, struct cpumask *nmsk, struct irq_affinity_desc *masks);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/affinity.c (ffffffff81129cc0)
Location: kernel/irq/affinity.c:247
Inline: False
Direct callers:
  - kernel/irq/affinity.c:irq_build_affinity_masks
  - kernel/irq/affinity.c:irq_build_affinity_masks
```
**Symbols:**

```
ffffffff81129cc0-ffffffff81129ff6: __irq_build_affinity_masks (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int __irq_build_affinity_masks(unsigned int startvec, unsigned int numvecs, unsigned int firstvec, cpumask_var_t *node_to_cpumask, const struct cpumask *cpu_mask, struct cpumask *nmsk, struct irq_affinity_desc *masks);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/affinity.c (ffffffff81129e80)
Location: kernel/irq/affinity.c:247
Inline: False
Direct callers:
  - kernel/irq/affinity.c:irq_build_affinity_masks
  - kernel/irq/affinity.c:irq_build_affinity_masks
```
**Symbols:**

```
ffffffff81129e80-ffffffff8112a27f: __irq_build_affinity_masks (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int __irq_build_affinity_masks(unsigned int startvec, unsigned int numvecs, unsigned int firstvec, cpumask_var_t *node_to_cpumask, const struct cpumask *cpu_mask, struct cpumask *nmsk, struct irq_affinity_desc *masks);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/affinity.c (ffffffff8114a7e0)
Location: kernel/irq/affinity.c:247
Inline: False
Direct callers:
  - kernel/irq/affinity.c:irq_build_affinity_masks
  - kernel/irq/affinity.c:irq_build_affinity_masks
```
**Symbols:**

```
ffffffff8114a7e0-ffffffff8114abdd: __irq_build_affinity_masks (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int __irq_build_affinity_masks(unsigned int startvec, unsigned int numvecs, unsigned int firstvec, cpumask_var_t *node_to_cpumask, const struct cpumask *cpu_mask, struct cpumask *nmsk, struct irq_affinity_desc *masks);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/affinity.c (ffffffff8116fdf0)
Location: kernel/irq/affinity.c:247
Inline: False
Direct callers:
  - kernel/irq/affinity.c:irq_build_affinity_masks
  - kernel/irq/affinity.c:irq_build_affinity_masks
```
**Symbols:**

```
ffffffff8116fdf0-ffffffff81170228: __irq_build_affinity_masks (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int __irq_build_affinity_masks(unsigned int startvec, unsigned int numvecs, unsigned int firstvec, cpumask_var_t *node_to_cpumask, const struct cpumask *cpu_mask, struct cpumask *nmsk, struct irq_affinity_desc *masks);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/affinity.c (ffffffff811a6250)
Location: kernel/irq/affinity.c:247
Inline: False
Direct callers:
  - kernel/irq/affinity.c:irq_build_affinity_masks
  - kernel/irq/affinity.c:irq_build_affinity_masks
```
**Symbols:**

```
ffffffff811a6250-ffffffff811a6678: __irq_build_affinity_masks (STB_LOCAL)
```
</details>
</li>
<li>
In <code>6.5</code>: Absent ⚠️
</li>
<li>
In <code>6.8</code>: Absent ⚠️
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: ✅</summary>

```c
int __irq_build_affinity_masks(unsigned int startvec, unsigned int numvecs, unsigned int firstvec, cpumask_var_t *node_to_cpumask, const struct cpumask *cpu_mask, struct cpumask *nmsk, struct irq_affinity_desc *masks);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/affinity.c (ffff800010187aa8)
Location: kernel/irq/affinity.c:247
Inline: False
Direct callers:
  - kernel/irq/affinity.c:irq_create_affinity_masks
  - kernel/irq/affinity.c:irq_create_affinity_masks
```
**Symbols:**

```
ffff800010187aa8-ffff800010188084: __irq_build_affinity_masks (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int __irq_build_affinity_masks(unsigned int startvec, unsigned int numvecs, unsigned int firstvec, cpumask_var_t *node_to_cpumask, const struct cpumask *cpu_mask, struct cpumask *nmsk, struct irq_affinity_desc *masks);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/affinity.c (c03d6648)
Location: kernel/irq/affinity.c:247
Inline: False
Direct callers:
  - kernel/irq/affinity.c:irq_create_affinity_masks
  - kernel/irq/affinity.c:irq_create_affinity_masks
```
**Symbols:**

```
c03d6648-c03d6a60: __irq_build_affinity_masks (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int __irq_build_affinity_masks(unsigned int startvec, unsigned int numvecs, unsigned int firstvec, cpumask_var_t *node_to_cpumask, const struct cpumask *cpu_mask, struct cpumask *nmsk, struct irq_affinity_desc *masks);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/affinity.c (c0000000001e1700)
Location: kernel/irq/affinity.c:247
Inline: False
Direct callers:
  - kernel/irq/affinity.c:irq_build_affinity_masks
  - kernel/irq/affinity.c:irq_build_affinity_masks
```
**Symbols:**

```
c0000000001e1700-c0000000001e1ec0: __irq_build_affinity_masks (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int __irq_build_affinity_masks(unsigned int startvec, unsigned int numvecs, unsigned int firstvec, cpumask_var_t *node_to_cpumask, const struct cpumask *cpu_mask, struct cpumask *nmsk, struct irq_affinity_desc *masks);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/affinity.c (ffffffe00011d5ac)
Location: kernel/irq/affinity.c:247
Inline: False
Direct callers:
  - kernel/irq/affinity.c:irq_create_affinity_masks
  - kernel/irq/affinity.c:irq_create_affinity_masks
```
**Symbols:**

```
ffffffe00011d5ac-ffffffe00011d882: __irq_build_affinity_masks (STB_LOCAL)
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
int __irq_build_affinity_masks(unsigned int startvec, unsigned int numvecs, unsigned int firstvec, cpumask_var_t *node_to_cpumask, const struct cpumask *cpu_mask, struct cpumask *nmsk, struct irq_affinity_desc *masks);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/affinity.c (ffffffff81119dc0)
Location: kernel/irq/affinity.c:247
Inline: False
Direct callers:
  - kernel/irq/affinity.c:irq_create_affinity_masks
  - kernel/irq/affinity.c:irq_create_affinity_masks
```
**Symbols:**

```
ffffffff81119dc0-ffffffff8111a425: __irq_build_affinity_masks (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int __irq_build_affinity_masks(unsigned int startvec, unsigned int numvecs, unsigned int firstvec, cpumask_var_t *node_to_cpumask, const struct cpumask *cpu_mask, struct cpumask *nmsk, struct irq_affinity_desc *masks);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/affinity.c (ffffffff8110ae30)
Location: kernel/irq/affinity.c:247
Inline: False
Direct callers:
  - kernel/irq/affinity.c:irq_create_affinity_masks
  - kernel/irq/affinity.c:irq_create_affinity_masks
```
**Symbols:**

```
ffffffff8110ae30-ffffffff8110b495: __irq_build_affinity_masks (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int __irq_build_affinity_masks(unsigned int startvec, unsigned int numvecs, unsigned int firstvec, cpumask_var_t *node_to_cpumask, const struct cpumask *cpu_mask, struct cpumask *nmsk, struct irq_affinity_desc *masks);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/affinity.c (ffffffff81117cb0)
Location: kernel/irq/affinity.c:247
Inline: False
Direct callers:
  - kernel/irq/affinity.c:irq_create_affinity_masks
  - kernel/irq/affinity.c:irq_create_affinity_masks
```
**Symbols:**

```
ffffffff81117cb0-ffffffff81118315: __irq_build_affinity_masks (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int __irq_build_affinity_masks(unsigned int startvec, unsigned int numvecs, unsigned int firstvec, cpumask_var_t *node_to_cpumask, const struct cpumask *cpu_mask, struct cpumask *nmsk, struct irq_affinity_desc *masks);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/affinity.c (ffffffff81123340)
Location: kernel/irq/affinity.c:247
Inline: False
Direct callers:
  - kernel/irq/affinity.c:irq_create_affinity_masks
  - kernel/irq/affinity.c:irq_create_affinity_masks
```
**Symbols:**

```
ffffffff81123340-ffffffff811239a5: __irq_build_affinity_masks (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
