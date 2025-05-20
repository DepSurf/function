# Function: <code>latch_tree_find</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/module.c (ffffffff811067b3)
Location: include/linux/rbtree_latch.h:198
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/module.c (ffffffff8110df7a)
Location: include/linux/rbtree_latch.h:198
Inline: True
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
In kernel/module.c (ffffffff8111595a)
Location: include/linux/rbtree_latch.h:198
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/module.c (ffffffff811166aa)
Location: include/linux/rbtree_latch.h:198
Inline: True
```
```
In kernel/bpf/core.c (ffffffff8118def7)
Location: include/linux/rbtree_latch.h:198
Inline: True
Inline callers:
  - kernel/bpf/core.c:bpf_prog_kallsyms_find
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/module.c (ffffffff81121caa)
Location: include/linux/rbtree_latch.h:199
Inline: True
```
```
In kernel/bpf/core.c (ffffffff8119c1a6)
Location: include/linux/rbtree_latch.h:199
Inline: True
Inline callers:
  - kernel/bpf/core.c:bpf_prog_kallsyms_find
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/module.c (0)
Location: include/linux/rbtree_latch.h:200
Inline: True
```
```
In kernel/bpf/core.c (0)
Location: include/linux/rbtree_latch.h:200
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/module.c (0)
Location: include/linux/rbtree_latch.h:200
Inline: True
```
```
In kernel/bpf/core.c (0)
Location: include/linux/rbtree_latch.h:200
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/module.c (0)
Location: include/linux/rbtree_latch.h:200
Inline: True
```
```
In kernel/bpf/core.c (0)
Location: include/linux/rbtree_latch.h:200
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/module.c (0)
Location: include/linux/rbtree_latch.h:200
Inline: True
```
```
In kernel/bpf/core.c (0)
Location: include/linux/rbtree_latch.h:200
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/module.c (0)
Location: include/linux/rbtree_latch.h:200
Inline: True
```
```
In kernel/bpf/core.c (0)
Location: include/linux/rbtree_latch.h:200
Inline: True
Inline callers:
  - kernel/bpf/core.c:bpf_ksym_find
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/module.c (0)
Location: include/linux/rbtree_latch.h:200
Inline: True
```
```
In kernel/bpf/core.c (0)
Location: include/linux/rbtree_latch.h:200
Inline: True
Inline callers:
  - kernel/bpf/core.c:bpf_ksym_find
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/module.c (0)
Location: include/linux/rbtree_latch.h:200
Inline: True
```
```
In kernel/bpf/core.c (0)
Location: include/linux/rbtree_latch.h:200
Inline: True
Inline callers:
  - kernel/bpf/core.c:bpf_ksym_find
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/module.c (ffffffff81184689)
Location: include/linux/rbtree_latch.h:200
Inline: True
```
```
In kernel/bpf/core.c (0)
Location: include/linux/rbtree_latch.h:200
Inline: True
Inline callers:
  - kernel/bpf/core.c:bpf_ksym_find
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/module/tree_lookup.c (ffffffff81190e79)
Location: include/linux/rbtree_latch.h:200
Inline: True
Inline callers:
  - kernel/module/tree_lookup.c:mod_find
```
```
In kernel/bpf/core.c (0)
Location: include/linux/rbtree_latch.h:200
Inline: True
Inline callers:
  - kernel/bpf/core.c:bpf_ksym_find
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/module/tree_lookup.c (ffffffff811ce479)
Location: include/linux/rbtree_latch.h:200
Inline: True
Inline callers:
  - kernel/module/tree_lookup.c:mod_find
```
```
In kernel/bpf/core.c (0)
Location: include/linux/rbtree_latch.h:200
Inline: True
Inline callers:
  - kernel/bpf/core.c:bpf_ksym_find
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/module/tree_lookup.c (ffffffff811e2609)
Location: include/linux/rbtree_latch.h:200
Inline: True
Inline callers:
  - kernel/module/tree_lookup.c:mod_find
```
```
In kernel/bpf/core.c (0)
Location: include/linux/rbtree_latch.h:200
Inline: True
Inline callers:
  - kernel/bpf/core.c:bpf_ksym_find
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/module/tree_lookup.c (ffffffff811f8399)
Location: include/linux/rbtree_latch.h:200
Inline: True
Inline callers:
  - kernel/module/tree_lookup.c:mod_find
```
```
In kernel/bpf/core.c (0)
Location: include/linux/rbtree_latch.h:200
Inline: True
Inline callers:
  - kernel/bpf/core.c:bpf_ksym_find
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/module.c (0)
Location: include/linux/rbtree_latch.h:200
Inline: True
```
```
In kernel/bpf/core.c (0)
Location: include/linux/rbtree_latch.h:200
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/module.c (0)
Location: include/linux/rbtree_latch.h:200
Inline: True
```
```
In kernel/bpf/core.c (0)
Location: include/linux/rbtree_latch.h:200
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/module.c (c000000000227940)
Location: include/linux/rbtree_latch.h:200
Inline: True
```
```
In kernel/bpf/core.c (0)
Location: include/linux/rbtree_latch.h:200
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/module.c (ffffffe0001433ac)
Location: include/linux/rbtree_latch.h:200
Inline: True
```
```
In kernel/bpf/core.c (ffffffe00019b634)
Location: include/linux/rbtree_latch.h:200
Inline: True
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/module.c (0)
Location: include/linux/rbtree_latch.h:200
Inline: True
```
```
In kernel/bpf/core.c (0)
Location: include/linux/rbtree_latch.h:200
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/module.c (0)
Location: include/linux/rbtree_latch.h:200
Inline: True
```
```
In kernel/bpf/core.c (0)
Location: include/linux/rbtree_latch.h:200
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/module.c (0)
Location: include/linux/rbtree_latch.h:200
Inline: True
```
```
In kernel/bpf/core.c (0)
Location: include/linux/rbtree_latch.h:200
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/module.c (0)
Location: include/linux/rbtree_latch.h:200
Inline: True
```
```
In kernel/bpf/core.c (0)
Location: include/linux/rbtree_latch.h:200
Inline: True
```
</details>
</li>
</ul>

## Differences
