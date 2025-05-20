# Function: <code>latch_tree_insert</code>

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
In kernel/module.c (ffffffff8110691d)
Location: include/linux/rbtree_latch.h:142
Inline: True
Inline callers:
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
In kernel/module.c (ffffffff8110e0df)
Location: include/linux/rbtree_latch.h:142
Inline: True
Inline callers:
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
In kernel/module.c (ffffffff81115abf)
Location: include/linux/rbtree_latch.h:142
Inline: True
Inline callers:
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
In kernel/module.c (ffffffff81116a1f)
Location: include/linux/rbtree_latch.h:142
Inline: True
Inline callers:
  - kernel/module.c:__mod_tree_insert
```
```
In kernel/bpf/core.c (ffffffff8118f155)
Location: include/linux/rbtree_latch.h:142
Inline: True
Inline callers:
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
In kernel/module.c (ffffffff8112201f)
Location: include/linux/rbtree_latch.h:143
Inline: True
Inline callers:
  - kernel/module.c:__mod_tree_insert
```
```
In kernel/bpf/core.c (ffffffff8119d5c5)
Location: include/linux/rbtree_latch.h:143
Inline: True
Inline callers:
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
In kernel/module.c (ffffffff8112fb15)
Location: include/linux/rbtree_latch.h:144
Inline: True
Inline callers:
  - kernel/module.c:__mod_tree_insert
```
```
In kernel/bpf/core.c (ffffffff811b1cf8)
Location: include/linux/rbtree_latch.h:144
Inline: True
Inline callers:
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
In kernel/module.c (ffffffff8113b3c5)
Location: include/linux/rbtree_latch.h:144
Inline: True
Inline callers:
  - kernel/module.c:__mod_tree_insert
```
```
In kernel/bpf/core.c (ffffffff811c05a8)
Location: include/linux/rbtree_latch.h:144
Inline: True
Inline callers:
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
In kernel/module.c (ffffffff81146a05)
Location: include/linux/rbtree_latch.h:144
Inline: True
Inline callers:
  - kernel/module.c:__mod_tree_insert
```
```
In kernel/bpf/core.c (ffffffff811d10b2)
Location: include/linux/rbtree_latch.h:144
Inline: True
Inline callers:
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
In kernel/module.c (ffffffff811525e5)
Location: include/linux/rbtree_latch.h:144
Inline: True
Inline callers:
  - kernel/module.c:__mod_tree_insert
```
```
In kernel/bpf/core.c (ffffffff811dd642)
Location: include/linux/rbtree_latch.h:144
Inline: True
Inline callers:
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
In kernel/module.c (ffffffff81162635)
Location: include/linux/rbtree_latch.h:144
Inline: True
Inline callers:
  - kernel/module.c:__mod_tree_insert
```
```
In kernel/bpf/core.c (ffffffff811f9f83)
Location: include/linux/rbtree_latch.h:144
Inline: True
Inline callers:
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
In kernel/module.c (ffffffff8115e695)
Location: include/linux/rbtree_latch.h:144
Inline: True
Inline callers:
  - kernel/module.c:__mod_tree_insert
```
```
In kernel/bpf/core.c (ffffffff811f8fb3)
Location: include/linux/rbtree_latch.h:144
Inline: True
Inline callers:
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
In kernel/module.c (ffffffff8115f6e5)
Location: include/linux/rbtree_latch.h:144
Inline: True
Inline callers:
  - kernel/module.c:__mod_tree_insert
```
```
In kernel/bpf/core.c (ffffffff811f9d93)
Location: include/linux/rbtree_latch.h:144
Inline: True
Inline callers:
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
In kernel/module.c (ffffffff81184aa5)
Location: include/linux/rbtree_latch.h:144
Inline: True
Inline callers:
  - kernel/module.c:__mod_tree_insert
```
```
In kernel/bpf/core.c (ffffffff8122b463)
Location: include/linux/rbtree_latch.h:144
Inline: True
Inline callers:
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
In kernel/module/tree_lookup.c (ffffffff81190c15)
Location: include/linux/rbtree_latch.h:144
Inline: True
```
```
In kernel/bpf/core.c (ffffffff8126ceb3)
Location: include/linux/rbtree_latch.h:144
Inline: True
Inline callers:
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
In kernel/module/tree_lookup.c (ffffffff811ce1d5)
Location: include/linux/rbtree_latch.h:144
Inline: True
```
```
In kernel/bpf/core.c (ffffffff812c1fe3)
Location: include/linux/rbtree_latch.h:144
Inline: True
Inline callers:
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
In kernel/module/tree_lookup.c (ffffffff811e22e5)
Location: include/linux/rbtree_latch.h:144
Inline: True
```
```
In kernel/bpf/core.c (ffffffff812e8ea3)
Location: include/linux/rbtree_latch.h:144
Inline: True
Inline callers:
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
In kernel/module/tree_lookup.c (ffffffff811f8075)
Location: include/linux/rbtree_latch.h:144
Inline: True
```
```
In kernel/bpf/core.c (ffffffff81307213)
Location: include/linux/rbtree_latch.h:144
Inline: True
Inline callers:
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
In kernel/module.c (ffff8000101c11ec)
Location: include/linux/rbtree_latch.h:144
Inline: True
Inline callers:
  - kernel/module.c:__mod_tree_insert
```
```
In kernel/bpf/core.c (ffff80001025e240)
Location: include/linux/rbtree_latch.h:144
Inline: True
Inline callers:
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
In kernel/module.c (c04089b0)
Location: include/linux/rbtree_latch.h:144
Inline: True
Inline callers:
  - kernel/module.c:__mod_tree_insert
```
```
In kernel/bpf/core.c (c04918dc)
Location: include/linux/rbtree_latch.h:144
Inline: True
Inline callers:
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
In kernel/module.c (c000000000227ca4)
Location: include/linux/rbtree_latch.h:144
Inline: True
Inline callers:
  - kernel/module.c:__mod_tree_insert
```
```
In kernel/bpf/core.c (c000000000302f14)
Location: include/linux/rbtree_latch.h:144
Inline: True
Inline callers:
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
In kernel/module.c (ffffffe00014351c)
Location: include/linux/rbtree_latch.h:144
Inline: True
Inline callers:
  - kernel/module.c:__mod_tree_insert
```
```
In kernel/bpf/core.c (ffffffe00019c6e4)
Location: include/linux/rbtree_latch.h:144
Inline: True
Inline callers:
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
In kernel/module.c (ffffffff8114ac05)
Location: include/linux/rbtree_latch.h:144
Inline: True
Inline callers:
  - kernel/module.c:__mod_tree_insert
```
```
In kernel/bpf/core.c (ffffffff811d5c62)
Location: include/linux/rbtree_latch.h:144
Inline: True
Inline callers:
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
In kernel/module.c (ffffffff8113deb5)
Location: include/linux/rbtree_latch.h:144
Inline: True
Inline callers:
  - kernel/module.c:__mod_tree_insert
```
```
In kernel/bpf/core.c (ffffffff811c8a22)
Location: include/linux/rbtree_latch.h:144
Inline: True
Inline callers:
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
In kernel/module.c (ffffffff81148ab5)
Location: include/linux/rbtree_latch.h:144
Inline: True
Inline callers:
  - kernel/module.c:__mod_tree_insert
```
```
In kernel/bpf/core.c (ffffffff811d3a32)
Location: include/linux/rbtree_latch.h:144
Inline: True
Inline callers:
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
In kernel/module.c (ffffffff81155735)
Location: include/linux/rbtree_latch.h:144
Inline: True
Inline callers:
  - kernel/module.c:__mod_tree_insert
```
```
In kernel/bpf/core.c (ffffffff811e1d22)
Location: include/linux/rbtree_latch.h:144
Inline: True
Inline callers:
  - kernel/bpf/core.c:bpf_prog_kallsyms_add
```
</details>
</li>
</ul>

## Differences
