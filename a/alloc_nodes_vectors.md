# Function: <code>alloc_nodes_vectors</code>

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
<details>
<summary>In <code>5.4</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/irq/affinity.c (ffffffff81121a38)
Location: kernel/irq/affinity.c:128
Inline: True
Inline callers:
  - kernel/irq/affinity.c:__irq_build_affinity_masks
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void alloc_nodes_vectors(unsigned int numvecs, cpumask_var_t *node_to_cpumask, const struct cpumask *cpu_mask, const nodemask_t nodemsk, struct cpumask *nmsk, struct node_vectors *node_vectors);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/affinity.c (ffffffff8112dde0)
Location: kernel/irq/affinity.c:128
Inline: False
Direct callers:
  - kernel/irq/affinity.c:__irq_build_affinity_masks
```
**Symbols:**

```
ffffffff8112dde0-ffffffff8112df5c: alloc_nodes_vectors (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void alloc_nodes_vectors(unsigned int numvecs, cpumask_var_t *node_to_cpumask, const struct cpumask *cpu_mask, const nodemask_t nodemsk, struct cpumask *nmsk, struct node_vectors *node_vectors);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/affinity.c (ffffffff811299d0)
Location: kernel/irq/affinity.c:128
Inline: False
Direct callers:
  - kernel/irq/affinity.c:__irq_build_affinity_masks
```
**Symbols:**

```
ffffffff811299d0-ffffffff81129b4c: alloc_nodes_vectors (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void alloc_nodes_vectors(unsigned int numvecs, cpumask_var_t *node_to_cpumask, const struct cpumask *cpu_mask, const nodemask_t nodemsk, struct cpumask *nmsk, struct node_vectors *node_vectors);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/affinity.c (ffffffff81129c60)
Location: kernel/irq/affinity.c:128
Inline: False
Direct callers:
  - kernel/irq/affinity.c:__irq_build_affinity_masks
```
**Symbols:**

```
ffffffff81129c60-ffffffff81129ddf: alloc_nodes_vectors (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void alloc_nodes_vectors(unsigned int numvecs, cpumask_var_t *node_to_cpumask, const struct cpumask *cpu_mask, const nodemask_t nodemsk, struct cpumask *nmsk, struct node_vectors *node_vectors);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/affinity.c (ffffffff8114a590)
Location: kernel/irq/affinity.c:128
Inline: False
Direct callers:
  - kernel/irq/affinity.c:__irq_build_affinity_masks
```
**Symbols:**

```
ffffffff8114a590-ffffffff8114a70f: alloc_nodes_vectors (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void alloc_nodes_vectors(unsigned int numvecs, cpumask_var_t *node_to_cpumask, const struct cpumask *cpu_mask, const nodemask_t nodemsk, struct cpumask *nmsk, struct node_vectors *node_vectors);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/affinity.c (ffffffff8116fc60)
Location: kernel/irq/affinity.c:128
Inline: False
Direct callers:
  - kernel/irq/affinity.c:__irq_build_affinity_masks
```
**Symbols:**

```
ffffffff8116fc60-ffffffff8116fde9: alloc_nodes_vectors (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void alloc_nodes_vectors(unsigned int numvecs, cpumask_var_t *node_to_cpumask, const struct cpumask *cpu_mask, const nodemask_t nodemsk, struct cpumask *nmsk, struct node_vectors *node_vectors);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/affinity.c (ffffffff811a60c0)
Location: kernel/irq/affinity.c:128
Inline: False
Direct callers:
  - kernel/irq/affinity.c:__irq_build_affinity_masks
```
**Symbols:**

```
ffffffff811a60c0-ffffffff811a623e: alloc_nodes_vectors (STB_LOCAL)
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
<summary>In <code>arm64</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/irq/affinity.c (ffff800010187c34)
Location: kernel/irq/affinity.c:128
Inline: True
Inline callers:
  - kernel/irq/affinity.c:__irq_build_affinity_masks
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
In kernel/irq/affinity.c (c03d66fc)
Location: kernel/irq/affinity.c:128
Inline: True
Inline callers:
  - kernel/irq/affinity.c:__irq_build_affinity_masks
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
In kernel/irq/affinity.c (c0000000001e193c)
Location: kernel/irq/affinity.c:128
Inline: True
Inline callers:
  - kernel/irq/affinity.c:__irq_build_affinity_masks
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
In kernel/irq/affinity.c (ffffffe00011d646)
Location: kernel/irq/affinity.c:128
Inline: True
Inline callers:
  - kernel/irq/affinity.c:__irq_build_affinity_masks
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
In kernel/irq/affinity.c (ffffffff8111a018)
Location: kernel/irq/affinity.c:128
Inline: True
Inline callers:
  - kernel/irq/affinity.c:__irq_build_affinity_masks
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
In kernel/irq/affinity.c (ffffffff8110b088)
Location: kernel/irq/affinity.c:128
Inline: True
Inline callers:
  - kernel/irq/affinity.c:__irq_build_affinity_masks
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
In kernel/irq/affinity.c (ffffffff81117f08)
Location: kernel/irq/affinity.c:128
Inline: True
Inline callers:
  - kernel/irq/affinity.c:__irq_build_affinity_masks
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
In kernel/irq/affinity.c (ffffffff81123598)
Location: kernel/irq/affinity.c:128
Inline: True
Inline callers:
  - kernel/irq/affinity.c:__irq_build_affinity_masks
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
</ul>
