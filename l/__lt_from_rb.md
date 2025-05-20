# Function: <code>__lt_from_rb</code>

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
In kernel/module.c (ffffffff811067db)
Location: include/linux/rbtree_latch.h:68
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
In kernel/module.c (ffffffff8110dfa2)
Location: include/linux/rbtree_latch.h:68
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
In kernel/module.c (ffffffff81115982)
Location: include/linux/rbtree_latch.h:68
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
In kernel/module.c (ffffffff811166c4)
Location: include/linux/rbtree_latch.h:68
Inline: True
```
```
In kernel/bpf/core.c (ffffffff8118df11)
Location: include/linux/rbtree_latch.h:68
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
In kernel/module.c (ffffffff81121cc4)
Location: include/linux/rbtree_latch.h:69
Inline: True
```
```
In kernel/bpf/core.c (ffffffff8119c1c0)
Location: include/linux/rbtree_latch.h:69
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
In kernel/module.c (ffffffff8112fb35)
Location: include/linux/rbtree_latch.h:70
Inline: True
Inline callers:
  - kernel/module.c:__mod_tree_insert
  - kernel/module.c:__mod_tree_insert
```
```
In kernel/bpf/core.c (ffffffff811b1d15)
Location: include/linux/rbtree_latch.h:70
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
In kernel/module.c (ffffffff8113b3e5)
Location: include/linux/rbtree_latch.h:70
Inline: True
Inline callers:
  - kernel/module.c:__mod_tree_insert
  - kernel/module.c:__mod_tree_insert
```
```
In kernel/bpf/core.c (ffffffff811c05c5)
Location: include/linux/rbtree_latch.h:70
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
In kernel/module.c (ffffffff81146a31)
Location: include/linux/rbtree_latch.h:70
Inline: True
Inline callers:
  - kernel/module.c:__mod_tree_insert
  - kernel/module.c:__mod_tree_insert
```
```
In kernel/bpf/core.c (ffffffff811d10eb)
Location: include/linux/rbtree_latch.h:70
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
In kernel/module.c (ffffffff81152611)
Location: include/linux/rbtree_latch.h:70
Inline: True
Inline callers:
  - kernel/module.c:__mod_tree_insert
  - kernel/module.c:__mod_tree_insert
```
```
In kernel/bpf/core.c (ffffffff811dd67b)
Location: include/linux/rbtree_latch.h:70
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
In kernel/module.c (ffffffff81162661)
Location: include/linux/rbtree_latch.h:70
Inline: True
Inline callers:
  - kernel/module.c:__mod_tree_insert
  - kernel/module.c:__mod_tree_insert
```
```
In kernel/bpf/core.c (ffffffff811f8e51)
Location: include/linux/rbtree_latch.h:70
Inline: True
Inline callers:
  - kernel/bpf/core.c:bpf_ksym_find
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
In kernel/module.c (ffffffff8115e6c1)
Location: include/linux/rbtree_latch.h:70
Inline: True
Inline callers:
  - kernel/module.c:__mod_tree_insert
  - kernel/module.c:__mod_tree_insert
```
```
In kernel/bpf/core.c (ffffffff811f7e91)
Location: include/linux/rbtree_latch.h:70
Inline: True
Inline callers:
  - kernel/bpf/core.c:bpf_ksym_find
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
In kernel/module.c (ffffffff8115f711)
Location: include/linux/rbtree_latch.h:70
Inline: True
Inline callers:
  - kernel/module.c:__mod_tree_insert
  - kernel/module.c:__mod_tree_insert
```
```
In kernel/bpf/core.c (ffffffff811f8c71)
Location: include/linux/rbtree_latch.h:70
Inline: True
Inline callers:
  - kernel/bpf/core.c:bpf_ksym_find
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
In kernel/module.c (ffffffff81184ad1)
Location: include/linux/rbtree_latch.h:70
Inline: True
Inline callers:
  - kernel/module.c:__mod_tree_insert
  - kernel/module.c:__mod_tree_insert
```
```
In kernel/bpf/core.c (ffffffff8122a301)
Location: include/linux/rbtree_latch.h:70
Inline: True
Inline callers:
  - kernel/bpf/core.c:bpf_ksym_find
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
In kernel/module/tree_lookup.c (ffffffff81190eb5)
Location: include/linux/rbtree_latch.h:70
Inline: True
Inline callers:
  - kernel/module/tree_lookup.c:mod_find
```
```
In kernel/bpf/core.c (ffffffff8126bdb6)
Location: include/linux/rbtree_latch.h:70
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
In kernel/module/tree_lookup.c (ffffffff811ce4b5)
Location: include/linux/rbtree_latch.h:70
Inline: True
Inline callers:
  - kernel/module/tree_lookup.c:mod_find
```
```
In kernel/bpf/core.c (ffffffff812c0f76)
Location: include/linux/rbtree_latch.h:70
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
In kernel/module/tree_lookup.c (ffffffff811e2632)
Location: include/linux/rbtree_latch.h:70
Inline: True
Inline callers:
  - kernel/module/tree_lookup.c:mod_find
```
```
In kernel/bpf/core.c (ffffffff812e5a81)
Location: include/linux/rbtree_latch.h:70
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
In kernel/module/tree_lookup.c (ffffffff811f83c2)
Location: include/linux/rbtree_latch.h:70
Inline: True
Inline callers:
  - kernel/module/tree_lookup.c:mod_find
```
```
In kernel/bpf/core.c (ffffffff81303b91)
Location: include/linux/rbtree_latch.h:70
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
In kernel/module.c (ffff8000101c1220)
Location: include/linux/rbtree_latch.h:70
Inline: True
Inline callers:
  - kernel/module.c:__mod_tree_insert
  - kernel/module.c:__mod_tree_insert
```
```
In kernel/bpf/core.c (ffff80001025e270)
Location: include/linux/rbtree_latch.h:70
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
In kernel/module.c (c04089ec)
Location: include/linux/rbtree_latch.h:70
Inline: True
Inline callers:
  - kernel/module.c:__mod_tree_insert
  - kernel/module.c:__mod_tree_insert
```
```
In kernel/bpf/core.c (c049192c)
Location: include/linux/rbtree_latch.h:70
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
In kernel/module.c (c000000000227cf4)
Location: include/linux/rbtree_latch.h:70
Inline: True
Inline callers:
  - kernel/module.c:__mod_tree_insert
  - kernel/module.c:__mod_tree_insert
```
```
In kernel/bpf/core.c (c000000000302f60)
Location: include/linux/rbtree_latch.h:70
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
In kernel/module.c (ffffffe000143548)
Location: include/linux/rbtree_latch.h:70
Inline: True
Inline callers:
  - kernel/module.c:__mod_tree_insert
  - kernel/module.c:__mod_tree_insert
```
```
In kernel/bpf/core.c (ffffffe00019c716)
Location: include/linux/rbtree_latch.h:70
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
In kernel/module.c (ffffffff8114ac31)
Location: include/linux/rbtree_latch.h:70
Inline: True
Inline callers:
  - kernel/module.c:__mod_tree_insert
  - kernel/module.c:__mod_tree_insert
```
```
In kernel/bpf/core.c (ffffffff811d5c9b)
Location: include/linux/rbtree_latch.h:70
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
In kernel/module.c (ffffffff8113dee1)
Location: include/linux/rbtree_latch.h:70
Inline: True
Inline callers:
  - kernel/module.c:__mod_tree_insert
  - kernel/module.c:__mod_tree_insert
```
```
In kernel/bpf/core.c (ffffffff811c8a5b)
Location: include/linux/rbtree_latch.h:70
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
In kernel/module.c (ffffffff81148ae1)
Location: include/linux/rbtree_latch.h:70
Inline: True
Inline callers:
  - kernel/module.c:__mod_tree_insert
  - kernel/module.c:__mod_tree_insert
```
```
In kernel/bpf/core.c (ffffffff811d3a6b)
Location: include/linux/rbtree_latch.h:70
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
In kernel/module.c (ffffffff81155761)
Location: include/linux/rbtree_latch.h:70
Inline: True
Inline callers:
  - kernel/module.c:__mod_tree_insert
  - kernel/module.c:__mod_tree_insert
```
```
In kernel/bpf/core.c (ffffffff811e1d5b)
Location: include/linux/rbtree_latch.h:70
Inline: True
Inline callers:
  - kernel/bpf/core.c:bpf_prog_kallsyms_add
  - kernel/bpf/core.c:bpf_prog_kallsyms_add
```
</details>
</li>
</ul>

## Differences
