# Function: <code>__lt_insert</code>

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
In kernel/module.c (ffffffff81106924)
Location: include/linux/rbtree_latch.h:74
Inline: True
Inline callers:
  - kernel/module.c:__mod_tree_insert
  - kernel/module.c:__mod_tree_insert
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
In kernel/module.c (ffffffff8110e0e6)
Location: include/linux/rbtree_latch.h:74
Inline: True
Inline callers:
  - kernel/module.c:__mod_tree_insert
  - kernel/module.c:__mod_tree_insert
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
In kernel/module.c (ffffffff81115ac6)
Location: include/linux/rbtree_latch.h:74
Inline: True
Inline callers:
  - kernel/module.c:__mod_tree_insert
  - kernel/module.c:__mod_tree_insert
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
In kernel/module.c (ffffffff81116a26)
Location: include/linux/rbtree_latch.h:74
Inline: True
Inline callers:
  - kernel/module.c:__mod_tree_insert
  - kernel/module.c:__mod_tree_insert
```
```
In kernel/bpf/core.c (ffffffff8118f15c)
Location: include/linux/rbtree_latch.h:74
Inline: True
Inline callers:
  - kernel/bpf/core.c:bpf_prog_kallsyms_add
  - kernel/bpf/core.c:bpf_prog_kallsyms_add
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
In kernel/module.c (ffffffff81122026)
Location: include/linux/rbtree_latch.h:75
Inline: True
Inline callers:
  - kernel/module.c:__mod_tree_insert
  - kernel/module.c:__mod_tree_insert
```
```
In kernel/bpf/core.c (ffffffff8119d5cc)
Location: include/linux/rbtree_latch.h:75
Inline: True
Inline callers:
  - kernel/bpf/core.c:bpf_prog_kallsyms_add
  - kernel/bpf/core.c:bpf_prog_kallsyms_add
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
In kernel/module.c (ffffffff8112fb26)
Location: include/linux/rbtree_latch.h:76
Inline: True
Inline callers:
  - kernel/module.c:__mod_tree_insert
  - kernel/module.c:__mod_tree_insert
```
```
In kernel/bpf/core.c (ffffffff811b1cff)
Location: include/linux/rbtree_latch.h:76
Inline: True
Inline callers:
  - kernel/bpf/core.c:bpf_prog_kallsyms_add
  - kernel/bpf/core.c:bpf_prog_kallsyms_add
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
In kernel/module.c (ffffffff8113b3d6)
Location: include/linux/rbtree_latch.h:76
Inline: True
Inline callers:
  - kernel/module.c:__mod_tree_insert
  - kernel/module.c:__mod_tree_insert
```
```
In kernel/bpf/core.c (ffffffff811c05af)
Location: include/linux/rbtree_latch.h:76
Inline: True
Inline callers:
  - kernel/bpf/core.c:bpf_prog_kallsyms_add
  - kernel/bpf/core.c:bpf_prog_kallsyms_add
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
In kernel/module.c (ffffffff81146a14)
Location: include/linux/rbtree_latch.h:76
Inline: True
Inline callers:
  - kernel/module.c:__mod_tree_insert
  - kernel/module.c:__mod_tree_insert
```
```
In kernel/bpf/core.c (ffffffff811d10b9)
Location: include/linux/rbtree_latch.h:76
Inline: True
Inline callers:
  - kernel/bpf/core.c:bpf_prog_kallsyms_add
  - kernel/bpf/core.c:bpf_prog_kallsyms_add
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
In kernel/module.c (ffffffff811525f4)
Location: include/linux/rbtree_latch.h:76
Inline: True
Inline callers:
  - kernel/module.c:__mod_tree_insert
  - kernel/module.c:__mod_tree_insert
```
```
In kernel/bpf/core.c (ffffffff811dd649)
Location: include/linux/rbtree_latch.h:76
Inline: True
Inline callers:
  - kernel/bpf/core.c:bpf_prog_kallsyms_add
  - kernel/bpf/core.c:bpf_prog_kallsyms_add
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
In kernel/module.c (ffffffff81162644)
Location: include/linux/rbtree_latch.h:76
Inline: True
Inline callers:
  - kernel/module.c:__mod_tree_insert
  - kernel/module.c:__mod_tree_insert
```
```
In kernel/bpf/core.c (ffffffff811f9f8a)
Location: include/linux/rbtree_latch.h:76
Inline: True
Inline callers:
  - kernel/bpf/core.c:bpf_ksym_add
  - kernel/bpf/core.c:bpf_ksym_add
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
In kernel/module.c (ffffffff8115e6a4)
Location: include/linux/rbtree_latch.h:76
Inline: True
Inline callers:
  - kernel/module.c:__mod_tree_insert
  - kernel/module.c:__mod_tree_insert
```
```
In kernel/bpf/core.c (ffffffff811f8fba)
Location: include/linux/rbtree_latch.h:76
Inline: True
Inline callers:
  - kernel/bpf/core.c:bpf_ksym_add
  - kernel/bpf/core.c:bpf_ksym_add
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
In kernel/module.c (ffffffff8115f6f4)
Location: include/linux/rbtree_latch.h:76
Inline: True
Inline callers:
  - kernel/module.c:__mod_tree_insert
  - kernel/module.c:__mod_tree_insert
```
```
In kernel/bpf/core.c (ffffffff811f9d9a)
Location: include/linux/rbtree_latch.h:76
Inline: True
Inline callers:
  - kernel/bpf/core.c:bpf_ksym_add
  - kernel/bpf/core.c:bpf_ksym_add
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
In kernel/module.c (ffffffff81184ab4)
Location: include/linux/rbtree_latch.h:76
Inline: True
Inline callers:
  - kernel/module.c:__mod_tree_insert
  - kernel/module.c:__mod_tree_insert
```
```
In kernel/bpf/core.c (ffffffff8122b46a)
Location: include/linux/rbtree_latch.h:76
Inline: True
Inline callers:
  - kernel/bpf/core.c:bpf_ksym_add
  - kernel/bpf/core.c:bpf_ksym_add
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
In kernel/module/tree_lookup.c (ffffffff81190c24)
Location: include/linux/rbtree_latch.h:76
Inline: True
```
```
In kernel/bpf/core.c (ffffffff8126ceba)
Location: include/linux/rbtree_latch.h:76
Inline: True
Inline callers:
  - kernel/bpf/core.c:bpf_ksym_add
  - kernel/bpf/core.c:bpf_ksym_add
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
In kernel/module/tree_lookup.c (ffffffff811ce1e4)
Location: include/linux/rbtree_latch.h:76
Inline: True
```
```
In kernel/bpf/core.c (ffffffff812c1fea)
Location: include/linux/rbtree_latch.h:76
Inline: True
Inline callers:
  - kernel/bpf/core.c:bpf_ksym_add
  - kernel/bpf/core.c:bpf_ksym_add
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
In kernel/module/tree_lookup.c (ffffffff811e22f4)
Location: include/linux/rbtree_latch.h:76
Inline: True
```
```
In kernel/bpf/core.c (ffffffff812e8eaa)
Location: include/linux/rbtree_latch.h:76
Inline: True
Inline callers:
  - kernel/bpf/core.c:bpf_ksym_add
  - kernel/bpf/core.c:bpf_ksym_add
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
In kernel/module/tree_lookup.c (ffffffff811f8084)
Location: include/linux/rbtree_latch.h:76
Inline: True
```
```
In kernel/bpf/core.c (ffffffff8130721a)
Location: include/linux/rbtree_latch.h:76
Inline: True
Inline callers:
  - kernel/bpf/core.c:bpf_ksym_add
  - kernel/bpf/core.c:bpf_ksym_add
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
In kernel/module.c (ffff8000101c1208)
Location: include/linux/rbtree_latch.h:76
Inline: True
Inline callers:
  - kernel/module.c:__mod_tree_insert
  - kernel/module.c:__mod_tree_insert
```
```
In kernel/bpf/core.c (ffff80001025e25c)
Location: include/linux/rbtree_latch.h:76
Inline: True
Inline callers:
  - kernel/bpf/core.c:bpf_prog_kallsyms_add
  - kernel/bpf/core.c:bpf_prog_kallsyms_add
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
In kernel/module.c (c04089d0)
Location: include/linux/rbtree_latch.h:76
Inline: True
Inline callers:
  - kernel/module.c:__mod_tree_insert
  - kernel/module.c:__mod_tree_insert
```
```
In kernel/bpf/core.c (c04918f8)
Location: include/linux/rbtree_latch.h:76
Inline: True
Inline callers:
  - kernel/bpf/core.c:bpf_prog_kallsyms_add
  - kernel/bpf/core.c:bpf_prog_kallsyms_add
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
In kernel/module.c (c000000000227cc8)
Location: include/linux/rbtree_latch.h:76
Inline: True
Inline callers:
  - kernel/module.c:__mod_tree_insert
  - kernel/module.c:__mod_tree_insert
```
```
In kernel/bpf/core.c (c000000000302f34)
Location: include/linux/rbtree_latch.h:76
Inline: True
Inline callers:
  - kernel/bpf/core.c:bpf_prog_kallsyms_add
  - kernel/bpf/core.c:bpf_prog_kallsyms_add
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
In kernel/module.c (ffffffe000143536)
Location: include/linux/rbtree_latch.h:76
Inline: True
Inline callers:
  - kernel/module.c:__mod_tree_insert
  - kernel/module.c:__mod_tree_insert
```
```
In kernel/bpf/core.c (ffffffe00019c6fe)
Location: include/linux/rbtree_latch.h:76
Inline: True
Inline callers:
  - kernel/bpf/core.c:bpf_prog_kallsyms_add
  - kernel/bpf/core.c:bpf_prog_kallsyms_add
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
In kernel/module.c (ffffffff8114ac14)
Location: include/linux/rbtree_latch.h:76
Inline: True
Inline callers:
  - kernel/module.c:__mod_tree_insert
  - kernel/module.c:__mod_tree_insert
```
```
In kernel/bpf/core.c (ffffffff811d5c69)
Location: include/linux/rbtree_latch.h:76
Inline: True
Inline callers:
  - kernel/bpf/core.c:bpf_prog_kallsyms_add
  - kernel/bpf/core.c:bpf_prog_kallsyms_add
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
In kernel/module.c (ffffffff8113dec4)
Location: include/linux/rbtree_latch.h:76
Inline: True
Inline callers:
  - kernel/module.c:__mod_tree_insert
  - kernel/module.c:__mod_tree_insert
```
```
In kernel/bpf/core.c (ffffffff811c8a29)
Location: include/linux/rbtree_latch.h:76
Inline: True
Inline callers:
  - kernel/bpf/core.c:bpf_prog_kallsyms_add
  - kernel/bpf/core.c:bpf_prog_kallsyms_add
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
In kernel/module.c (ffffffff81148ac4)
Location: include/linux/rbtree_latch.h:76
Inline: True
Inline callers:
  - kernel/module.c:__mod_tree_insert
  - kernel/module.c:__mod_tree_insert
```
```
In kernel/bpf/core.c (ffffffff811d3a39)
Location: include/linux/rbtree_latch.h:76
Inline: True
Inline callers:
  - kernel/bpf/core.c:bpf_prog_kallsyms_add
  - kernel/bpf/core.c:bpf_prog_kallsyms_add
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
In kernel/module.c (ffffffff81155744)
Location: include/linux/rbtree_latch.h:76
Inline: True
Inline callers:
  - kernel/module.c:__mod_tree_insert
  - kernel/module.c:__mod_tree_insert
```
```
In kernel/bpf/core.c (ffffffff811e1d29)
Location: include/linux/rbtree_latch.h:76
Inline: True
Inline callers:
  - kernel/bpf/core.c:bpf_prog_kallsyms_add
  - kernel/bpf/core.c:bpf_prog_kallsyms_add
```
</details>
</li>
</ul>

## Differences
