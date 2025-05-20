# Function: <code>__lt_find</code>

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
In kernel/module.c (ffffffff811067ba)
Location: include/linux/rbtree_latch.h:104
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
In kernel/module.c (ffffffff8110df83)
Location: include/linux/rbtree_latch.h:104
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
In kernel/module.c (ffffffff81115963)
Location: include/linux/rbtree_latch.h:104
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
In kernel/module.c (ffffffff811166b3)
Location: include/linux/rbtree_latch.h:104
Inline: True
```
```
In kernel/bpf/core.c (ffffffff8118df00)
Location: include/linux/rbtree_latch.h:104
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
In kernel/module.c (ffffffff81121cb3)
Location: include/linux/rbtree_latch.h:105
Inline: True
```
```
In kernel/bpf/core.c (ffffffff8119c1af)
Location: include/linux/rbtree_latch.h:105
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
In kernel/module.c (ffffffff8112f7af)
Location: include/linux/rbtree_latch.h:106
Inline: True
```
```
In kernel/bpf/core.c (ffffffff811b1290)
Location: include/linux/rbtree_latch.h:106
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
In kernel/module.c (ffffffff8113b282)
Location: include/linux/rbtree_latch.h:106
Inline: True
```
```
In kernel/bpf/core.c (ffffffff811bf910)
Location: include/linux/rbtree_latch.h:106
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
In kernel/module.c (ffffffff811468c6)
Location: include/linux/rbtree_latch.h:106
Inline: True
```
```
In kernel/bpf/core.c (ffffffff811cfedb)
Location: include/linux/rbtree_latch.h:106
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
In kernel/module.c (ffffffff811524a6)
Location: include/linux/rbtree_latch.h:106
Inline: True
```
```
In kernel/bpf/core.c (ffffffff811dc48b)
Location: include/linux/rbtree_latch.h:106
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
In kernel/module.c (ffffffff81162155)
Location: include/linux/rbtree_latch.h:106
Inline: True
```
```
In kernel/bpf/core.c (ffffffff811f8e34)
Location: include/linux/rbtree_latch.h:106
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
In kernel/module.c (ffffffff811640f5)
Location: include/linux/rbtree_latch.h:106
Inline: True
```
```
In kernel/bpf/core.c (ffffffff811f7e74)
Location: include/linux/rbtree_latch.h:106
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
In kernel/module.c (ffffffff81164ec5)
Location: include/linux/rbtree_latch.h:106
Inline: True
```
```
In kernel/bpf/core.c (ffffffff811f8c54)
Location: include/linux/rbtree_latch.h:106
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
In kernel/module.c (ffffffff811846b0)
Location: include/linux/rbtree_latch.h:106
Inline: True
```
```
In kernel/bpf/core.c (ffffffff8122a2e4)
Location: include/linux/rbtree_latch.h:106
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
In kernel/module/tree_lookup.c (ffffffff81190ea0)
Location: include/linux/rbtree_latch.h:106
Inline: True
Inline callers:
  - kernel/module/tree_lookup.c:mod_find
```
```
In kernel/bpf/core.c (ffffffff8126bd9e)
Location: include/linux/rbtree_latch.h:106
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
In kernel/module/tree_lookup.c (ffffffff811ce4a0)
Location: include/linux/rbtree_latch.h:106
Inline: True
Inline callers:
  - kernel/module/tree_lookup.c:mod_find
```
```
In kernel/bpf/core.c (ffffffff812c0f5e)
Location: include/linux/rbtree_latch.h:106
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
In kernel/module/tree_lookup.c (ffffffff811e261b)
Location: include/linux/rbtree_latch.h:106
Inline: True
Inline callers:
  - kernel/module/tree_lookup.c:mod_find
```
```
In kernel/bpf/core.c (ffffffff812e5a69)
Location: include/linux/rbtree_latch.h:106
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
In kernel/module/tree_lookup.c (ffffffff811f83ab)
Location: include/linux/rbtree_latch.h:106
Inline: True
Inline callers:
  - kernel/module/tree_lookup.c:mod_find
```
```
In kernel/bpf/core.c (ffffffff81303b79)
Location: include/linux/rbtree_latch.h:106
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
In kernel/module.c (ffff8000101c1098)
Location: include/linux/rbtree_latch.h:106
Inline: True
```
```
In kernel/bpf/core.c (ffff80001025c55c)
Location: include/linux/rbtree_latch.h:106
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
In kernel/module.c (c0408840)
Location: include/linux/rbtree_latch.h:106
Inline: True
```
```
In kernel/bpf/core.c (c0490618)
Location: include/linux/rbtree_latch.h:106
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
In kernel/module.c (c000000000227978)
Location: include/linux/rbtree_latch.h:106
Inline: True
```
```
In kernel/bpf/core.c (c000000000301574)
Location: include/linux/rbtree_latch.h:106
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
Location: include/linux/rbtree_latch.h:106
Inline: True
```
```
In kernel/bpf/core.c (ffffffe00019b634)
Location: include/linux/rbtree_latch.h:106
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
In kernel/module.c (ffffffff8114aac6)
Location: include/linux/rbtree_latch.h:106
Inline: True
```
```
In kernel/bpf/core.c (ffffffff811d4aab)
Location: include/linux/rbtree_latch.h:106
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
In kernel/module.c (ffffffff8113dd76)
Location: include/linux/rbtree_latch.h:106
Inline: True
```
```
In kernel/bpf/core.c (ffffffff811c786b)
Location: include/linux/rbtree_latch.h:106
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
In kernel/module.c (ffffffff81148976)
Location: include/linux/rbtree_latch.h:106
Inline: True
```
```
In kernel/bpf/core.c (ffffffff811d287b)
Location: include/linux/rbtree_latch.h:106
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
In kernel/module.c (ffffffff811555e6)
Location: include/linux/rbtree_latch.h:106
Inline: True
```
```
In kernel/bpf/core.c (ffffffff811e0b6b)
Location: include/linux/rbtree_latch.h:106
Inline: True
```
</details>
</li>
</ul>

## Differences
