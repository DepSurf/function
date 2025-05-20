# Function: <code>latch_tree_erase</code>

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
In kernel/module.c (ffffffff8110529d)
Location: include/linux/rbtree_latch.h:169
Inline: True
Inline callers:
  - kernel/module.c:__mod_tree_remove
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
In kernel/module.c (ffffffff8110cb7d)
Location: include/linux/rbtree_latch.h:169
Inline: True
Inline callers:
  - kernel/module.c:__mod_tree_remove
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
In kernel/module.c (ffffffff811145bd)
Location: include/linux/rbtree_latch.h:169
Inline: True
Inline callers:
  - kernel/module.c:__mod_tree_remove
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
In kernel/module.c (ffffffff8111575d)
Location: include/linux/rbtree_latch.h:169
Inline: True
Inline callers:
  - kernel/module.c:__mod_tree_remove
```
```
In kernel/bpf/core.c (ffffffff8118f2bf)
Location: include/linux/rbtree_latch.h:169
Inline: True
Inline callers:
  - kernel/bpf/core.c:bpf_prog_kallsyms_del
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
In kernel/module.c (ffffffff81120d0d)
Location: include/linux/rbtree_latch.h:170
Inline: True
Inline callers:
  - kernel/module.c:__mod_tree_remove
```
```
In kernel/bpf/core.c (ffffffff8119d72f)
Location: include/linux/rbtree_latch.h:170
Inline: True
Inline callers:
  - kernel/bpf/core.c:bpf_prog_kallsyms_del
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
In kernel/module.c (ffffffff8112e635)
Location: include/linux/rbtree_latch.h:171
Inline: True
Inline callers:
  - kernel/module.c:__mod_tree_remove
```
```
In kernel/bpf/core.c (ffffffff811b1e6b)
Location: include/linux/rbtree_latch.h:171
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
In kernel/module.c (ffffffff81139f35)
Location: include/linux/rbtree_latch.h:171
Inline: True
Inline callers:
  - kernel/module.c:__mod_tree_remove
```
```
In kernel/bpf/core.c (ffffffff811c071b)
Location: include/linux/rbtree_latch.h:171
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
In kernel/module.c (ffffffff81145665)
Location: include/linux/rbtree_latch.h:171
Inline: True
Inline callers:
  - kernel/module.c:__mod_tree_remove
```
```
In kernel/bpf/core.c (ffffffff811d125b)
Location: include/linux/rbtree_latch.h:171
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
In kernel/module.c (ffffffff81151175)
Location: include/linux/rbtree_latch.h:171
Inline: True
Inline callers:
  - kernel/module.c:__mod_tree_remove
```
```
In kernel/bpf/core.c (ffffffff811dd7eb)
Location: include/linux/rbtree_latch.h:171
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
In kernel/module.c (ffffffff81166f36)
Location: include/linux/rbtree_latch.h:171
Inline: True
Inline callers:
  - kernel/module.c:load_module
  - kernel/module.c:load_module
  - kernel/module.c:do_init_module
  - kernel/module.c:free_module
  - kernel/module.c:free_module
```
```
In kernel/bpf/core.c (ffffffff811fa0bc)
Location: include/linux/rbtree_latch.h:171
Inline: True
Inline callers:
  - kernel/bpf/core.c:bpf_ksym_del
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
In kernel/module.c (ffffffff811635e6)
Location: include/linux/rbtree_latch.h:171
Inline: True
Inline callers:
  - kernel/module.c:load_module
  - kernel/module.c:load_module
  - kernel/module.c:do_init_module
  - kernel/module.c:free_module
  - kernel/module.c:free_module
```
```
In kernel/bpf/core.c (ffffffff811f90ec)
Location: include/linux/rbtree_latch.h:171
Inline: True
Inline callers:
  - kernel/bpf/core.c:bpf_ksym_del
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
In kernel/module.c (ffffffff811641ae)
Location: include/linux/rbtree_latch.h:171
Inline: True
Inline callers:
  - kernel/module.c:load_module
  - kernel/module.c:load_module
  - kernel/module.c:do_init_module
  - kernel/module.c:free_module
  - kernel/module.c:free_module
```
```
In kernel/bpf/core.c (ffffffff811f9ecc)
Location: include/linux/rbtree_latch.h:171
Inline: True
Inline callers:
  - kernel/bpf/core.c:bpf_ksym_del
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
In kernel/module.c (ffffffff811898bc)
Location: include/linux/rbtree_latch.h:171
Inline: True
Inline callers:
  - kernel/module.c:load_module
  - kernel/module.c:load_module
  - kernel/module.c:do_init_module
  - kernel/module.c:free_module
  - kernel/module.c:free_module
```
```
In kernel/bpf/core.c (ffffffff8122b59c)
Location: include/linux/rbtree_latch.h:171
Inline: True
Inline callers:
  - kernel/bpf/core.c:bpf_ksym_del
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
In kernel/module/tree_lookup.c (ffffffff81190dd5)
Location: include/linux/rbtree_latch.h:171
Inline: True
Inline callers:
  - kernel/module/tree_lookup.c:mod_tree_remove
  - kernel/module/tree_lookup.c:mod_tree_remove
```
```
In kernel/bpf/core.c (ffffffff8126cffc)
Location: include/linux/rbtree_latch.h:171
Inline: True
Inline callers:
  - kernel/bpf/core.c:bpf_ksym_del
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
In kernel/module/tree_lookup.c (ffffffff811ce3c5)
Location: include/linux/rbtree_latch.h:171
Inline: True
Inline callers:
  - kernel/module/tree_lookup.c:mod_tree_remove
  - kernel/module/tree_lookup.c:mod_tree_remove
```
```
In kernel/bpf/core.c (ffffffff812c213c)
Location: include/linux/rbtree_latch.h:171
Inline: True
Inline callers:
  - kernel/bpf/core.c:bpf_ksym_del
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
In kernel/module/tree_lookup.c (ffffffff811e257d)
Location: include/linux/rbtree_latch.h:171
Inline: True
Inline callers:
  - kernel/module/tree_lookup.c:mod_tree_remove
```
```
In kernel/bpf/core.c (ffffffff812e8ffc)
Location: include/linux/rbtree_latch.h:171
Inline: True
Inline callers:
  - kernel/bpf/core.c:bpf_ksym_del
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
In kernel/module/tree_lookup.c (ffffffff811f830d)
Location: include/linux/rbtree_latch.h:171
Inline: True
Inline callers:
  - kernel/module/tree_lookup.c:mod_tree_remove
```
```
In kernel/bpf/core.c (ffffffff8130736c)
Location: include/linux/rbtree_latch.h:171
Inline: True
Inline callers:
  - kernel/bpf/core.c:bpf_ksym_del
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
In kernel/module.c (ffff8000101c0054)
Location: include/linux/rbtree_latch.h:171
Inline: True
Inline callers:
  - kernel/module.c:__mod_tree_remove
```
```
In kernel/bpf/core.c (ffff80001025e464)
Location: include/linux/rbtree_latch.h:171
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
In kernel/module.c (c0407770)
Location: include/linux/rbtree_latch.h:171
Inline: True
Inline callers:
  - kernel/module.c:__mod_tree_remove
```
```
In kernel/bpf/core.c (c0491bcc)
Location: include/linux/rbtree_latch.h:171
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
In kernel/module.c (c000000000225cb8)
Location: include/linux/rbtree_latch.h:171
Inline: True
Inline callers:
  - kernel/module.c:__mod_tree_remove
```
```
In kernel/bpf/core.c (c0000000003031a8)
Location: include/linux/rbtree_latch.h:171
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
In kernel/module.c (ffffffe000142464)
Location: include/linux/rbtree_latch.h:171
Inline: True
Inline callers:
  - kernel/module.c:__mod_tree_remove
```
```
In kernel/bpf/core.c (ffffffe00019c870)
Location: include/linux/rbtree_latch.h:171
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
In kernel/module.c (ffffffff81149795)
Location: include/linux/rbtree_latch.h:171
Inline: True
Inline callers:
  - kernel/module.c:__mod_tree_remove
```
```
In kernel/bpf/core.c (ffffffff811d5e0b)
Location: include/linux/rbtree_latch.h:171
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
In kernel/module.c (ffffffff8113ca45)
Location: include/linux/rbtree_latch.h:171
Inline: True
Inline callers:
  - kernel/module.c:__mod_tree_remove
```
```
In kernel/bpf/core.c (ffffffff811c8bcb)
Location: include/linux/rbtree_latch.h:171
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
In kernel/module.c (ffffffff81147645)
Location: include/linux/rbtree_latch.h:171
Inline: True
Inline callers:
  - kernel/module.c:__mod_tree_remove
```
```
In kernel/bpf/core.c (ffffffff811d3bdb)
Location: include/linux/rbtree_latch.h:171
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
In kernel/module.c (ffffffff81154255)
Location: include/linux/rbtree_latch.h:171
Inline: True
Inline callers:
  - kernel/module.c:__mod_tree_remove
```
```
In kernel/bpf/core.c (ffffffff811e1ecb)
Location: include/linux/rbtree_latch.h:171
Inline: True
```
</details>
</li>
</ul>

## Differences
