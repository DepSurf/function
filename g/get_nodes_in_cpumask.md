# Function: <code>get_nodes_in_cpumask</code>

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
<details>
<summary>In <code>4.10</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/irq/affinity.c (ffffffff810ef996)
Location: kernel/irq/affinity.c:38
Inline: True
Inline callers:
  - kernel/irq/affinity.c:irq_create_affinity_masks
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
In kernel/irq/affinity.c (ffffffff810ef94a)
Location: kernel/irq/affinity.c:81
Inline: True
Inline callers:
  - kernel/irq/affinity.c:irq_create_affinity_masks
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
In kernel/irq/affinity.c (ffffffff810f8531)
Location: kernel/irq/affinity.c:82
Inline: True
Inline callers:
  - kernel/irq/affinity.c:irq_create_affinity_masks
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
In kernel/irq/affinity.c (ffffffff81100754)
Location: kernel/irq/affinity.c:82
Inline: True
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
In kernel/irq/affinity.c (ffffffff8110bf19)
Location: kernel/irq/affinity.c:82
Inline: True
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
In kernel/irq/affinity.c (ffffffff8111567c)
Location: kernel/irq/affinity.c:82
Inline: True
Inline callers:
  - kernel/irq/affinity.c:__irq_build_affinity_masks
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
In kernel/irq/affinity.c (ffffffff8112187b)
Location: kernel/irq/affinity.c:83
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
int get_nodes_in_cpumask(cpumask_var_t *node_to_cpumask, const struct cpumask *mask, nodemask_t *nodemsk);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/affinity.c (ffffffff8112e000)
Location: kernel/irq/affinity.c:83
Inline: False
Direct callers:
  - kernel/irq/affinity.c:__irq_build_affinity_masks
```
**Symbols:**

```
ffffffff8112e000-ffffffff8112e0c3: get_nodes_in_cpumask (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int get_nodes_in_cpumask(cpumask_var_t *node_to_cpumask, const struct cpumask *mask, nodemask_t *nodemsk);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/affinity.c (ffffffff81129bf0)
Location: kernel/irq/affinity.c:83
Inline: False
Direct callers:
  - kernel/irq/affinity.c:__irq_build_affinity_masks
```
**Symbols:**

```
ffffffff81129bf0-ffffffff81129cb3: get_nodes_in_cpumask (STB_LOCAL)
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
In kernel/irq/affinity.c (ffffffff81129f18)
Location: kernel/irq/affinity.c:83
Inline: True
Inline callers:
  - kernel/irq/affinity.c:__irq_build_affinity_masks
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
In kernel/irq/affinity.c (ffffffff8114a878)
Location: kernel/irq/affinity.c:83
Inline: True
Inline callers:
  - kernel/irq/affinity.c:__irq_build_affinity_masks
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
In kernel/irq/affinity.c (ffffffff8116fe9f)
Location: kernel/irq/affinity.c:83
Inline: True
Inline callers:
  - kernel/irq/affinity.c:__irq_build_affinity_masks
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
In kernel/irq/affinity.c (ffffffff811a62ff)
Location: kernel/irq/affinity.c:83
Inline: True
Inline callers:
  - kernel/irq/affinity.c:__irq_build_affinity_masks
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
In lib/group_cpus.c (ffffffff818e6d32)
Location: lib/group_cpus.c:85
Inline: True
Inline callers:
  - lib/group_cpus.c:__group_cpus_evenly
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
In lib/group_cpus.c (ffffffff8192dd52)
Location: lib/group_cpus.c:85
Inline: True
Inline callers:
  - lib/group_cpus.c:__group_cpus_evenly
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
In kernel/irq/affinity.c (ffff800010187b60)
Location: kernel/irq/affinity.c:83
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
In kernel/irq/affinity.c (c03d66b8)
Location: kernel/irq/affinity.c:83
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
In kernel/irq/affinity.c (c0000000001e17e0)
Location: kernel/irq/affinity.c:83
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
In kernel/irq/affinity.c (ffffffe00011d606)
Location: kernel/irq/affinity.c:83
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
In kernel/irq/affinity.c (ffffffff81119e5b)
Location: kernel/irq/affinity.c:83
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
In kernel/irq/affinity.c (ffffffff8110aecb)
Location: kernel/irq/affinity.c:83
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
In kernel/irq/affinity.c (ffffffff81117d4b)
Location: kernel/irq/affinity.c:83
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
In kernel/irq/affinity.c (ffffffff811233db)
Location: kernel/irq/affinity.c:83
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
</ul>
