# Function: <code>__bpf_lru_list_shrink</code>

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
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
unsigned int __bpf_lru_list_shrink(struct bpf_lru *lru, struct bpf_lru_list *l, unsigned int tgt_nshrink, struct list_head *free_list, enum bpf_lru_list_type tgt_free_type);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/bpf/bpf_lru_list.c (ffffffff811963f0)
Location: kernel/bpf/bpf_lru_list.c:259
Inline: True
Direct callers:
  - kernel/bpf/bpf_lru_list.c:bpf_lru_pop_free
  - kernel/bpf/bpf_lru_list.c:bpf_lru_pop_free
```
**Symbols:**

```
ffffffff811963f0-ffffffff81196520: __bpf_lru_list_shrink (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
unsigned int __bpf_lru_list_shrink(struct bpf_lru *lru, struct bpf_lru_list *l, unsigned int tgt_nshrink, struct list_head *free_list, enum bpf_lru_list_type tgt_free_type);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/bpf/bpf_lru_list.c (ffffffff8119d8c0)
Location: kernel/bpf/bpf_lru_list.c:258
Inline: True
Direct callers:
  - kernel/bpf/bpf_lru_list.c:bpf_lru_pop_free
  - kernel/bpf/bpf_lru_list.c:bpf_lru_pop_free
```
**Symbols:**

```
ffffffff8119d8c0-ffffffff8119d9f5: __bpf_lru_list_shrink (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
unsigned int __bpf_lru_list_shrink(struct bpf_lru *lru, struct bpf_lru_list *l, unsigned int tgt_nshrink, struct list_head *free_list, enum bpf_lru_list_type tgt_free_type);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/bpf/bpf_lru_list.c (ffffffff811ad480)
Location: kernel/bpf/bpf_lru_list.c:258
Inline: True
Direct callers:
  - kernel/bpf/bpf_lru_list.c:bpf_lru_pop_free
  - kernel/bpf/bpf_lru_list.c:bpf_lru_pop_free
```
**Symbols:**

```
ffffffff811ad480-ffffffff811ad5bf: __bpf_lru_list_shrink (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
unsigned int __bpf_lru_list_shrink(struct bpf_lru *lru, struct bpf_lru_list *l, unsigned int tgt_nshrink, struct list_head *free_list, enum bpf_lru_list_type tgt_free_type);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/bpf/bpf_lru_list.c (ffffffff811c4a00)
Location: kernel/bpf/bpf_lru_list.c:258
Inline: True
Direct callers:
  - kernel/bpf/bpf_lru_list.c:bpf_lru_pop_free
  - kernel/bpf/bpf_lru_list.c:bpf_lru_pop_free
```
**Symbols:**

```
ffffffff811c4a00-ffffffff811c4b4a: __bpf_lru_list_shrink (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
unsigned int __bpf_lru_list_shrink(struct bpf_lru *lru, struct bpf_lru_list *l, unsigned int tgt_nshrink, struct list_head *free_list, enum bpf_lru_list_type tgt_free_type);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/bpf/bpf_lru_list.c (ffffffff811d65f0)
Location: kernel/bpf/bpf_lru_list.c:258
Inline: True
Direct callers:
  - kernel/bpf/bpf_lru_list.c:bpf_lru_pop_free
  - kernel/bpf/bpf_lru_list.c:bpf_lru_pop_free
```
**Symbols:**

```
ffffffff811d65f0-ffffffff811d673a: __bpf_lru_list_shrink (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
unsigned int __bpf_lru_list_shrink(struct bpf_lru *lru, struct bpf_lru_list *l, unsigned int tgt_nshrink, struct list_head *free_list, enum bpf_lru_list_type tgt_free_type);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/bpf/bpf_lru_list.c (ffffffff811eafc0)
Location: kernel/bpf/bpf_lru_list.c:255
Inline: True
Direct callers:
  - kernel/bpf/bpf_lru_list.c:bpf_lru_pop_free
  - kernel/bpf/bpf_lru_list.c:bpf_common_lru_pop_free
```
**Symbols:**

```
ffffffff811eafc0-ffffffff811eb103: __bpf_lru_list_shrink (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
unsigned int __bpf_lru_list_shrink(struct bpf_lru *lru, struct bpf_lru_list *l, unsigned int tgt_nshrink, struct list_head *free_list, enum bpf_lru_list_type tgt_free_type);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/bpf/bpf_lru_list.c (ffffffff811f7720)
Location: kernel/bpf/bpf_lru_list.c:255
Inline: True
Direct callers:
  - kernel/bpf/bpf_lru_list.c:bpf_lru_pop_free
  - kernel/bpf/bpf_lru_list.c:bpf_common_lru_pop_free
```
**Symbols:**

```
ffffffff811f7720-ffffffff811f7863: __bpf_lru_list_shrink (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/bpf/bpf_lru_list.c (ffffffff8121b4b0)
Location: kernel/bpf/bpf_lru_list.c:255
Inline: True
Direct callers:
  - kernel/bpf/bpf_lru_list.c:bpf_percpu_lru_pop_free
  - kernel/bpf/bpf_lru_list.c:bpf_lru_list_pop_free_to_local
```
**Symbols:**

```
ffffffff8121b4b0-ffffffff8121b5dd: __bpf_lru_list_shrink.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/bpf/bpf_lru_list.c (ffffffff8121e430)
Location: kernel/bpf/bpf_lru_list.c:255
Inline: True
Direct callers:
  - kernel/bpf/bpf_lru_list.c:bpf_percpu_lru_pop_free
  - kernel/bpf/bpf_lru_list.c:bpf_lru_list_pop_free_to_local
```
**Symbols:**

```
ffffffff8121e430-ffffffff8121e55d: __bpf_lru_list_shrink.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/bpf/bpf_lru_list.c (ffffffff81221e20)
Location: kernel/bpf/bpf_lru_list.c:255
Inline: True
Direct callers:
  - kernel/bpf/bpf_lru_list.c:bpf_lru_pop_free
  - kernel/bpf/bpf_lru_list.c:bpf_lru_list_pop_free_to_local
```
**Symbols:**

```
ffffffff81221e20-ffffffff81221f4d: __bpf_lru_list_shrink.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/bpf/bpf_lru_list.c (ffffffff81259900)
Location: kernel/bpf/bpf_lru_list.c:255
Inline: True
Direct callers:
  - kernel/bpf/bpf_lru_list.c:bpf_lru_pop_free
  - kernel/bpf/bpf_lru_list.c:bpf_lru_list_pop_free_to_local
```
**Symbols:**

```
ffffffff81259900-ffffffff81259a2d: __bpf_lru_list_shrink.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/bpf/bpf_lru_list.c (ffffffff812a28d0)
Location: kernel/bpf/bpf_lru_list.c:255
Inline: True
Direct callers:
  - kernel/bpf/bpf_lru_list.c:bpf_lru_pop_free
  - kernel/bpf/bpf_lru_list.c:bpf_lru_list_pop_free_to_local
```
**Symbols:**

```
ffffffff812a28d0-ffffffff812a2a1c: __bpf_lru_list_shrink.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/bpf/bpf_lru_list.c (ffffffff813003d0)
Location: kernel/bpf/bpf_lru_list.c:255
Inline: True
Direct callers:
  - kernel/bpf/bpf_lru_list.c:bpf_lru_pop_free
  - kernel/bpf/bpf_lru_list.c:bpf_lru_list_pop_free_to_local
```
**Symbols:**

```
ffffffff813003d0-ffffffff8130051c: __bpf_lru_list_shrink.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/bpf/bpf_lru_list.c (ffffffff8132ef30)
Location: kernel/bpf/bpf_lru_list.c:260
Inline: True
Direct callers:
  - kernel/bpf/bpf_lru_list.c:bpf_lru_pop_free
  - kernel/bpf/bpf_lru_list.c:bpf_lru_list_pop_free_to_local
```
**Symbols:**

```
ffffffff8132ef30-ffffffff8132f07a: __bpf_lru_list_shrink.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/bpf/bpf_lru_list.c (ffffffff81353450)
Location: kernel/bpf/bpf_lru_list.c:260
Inline: True
Direct callers:
  - kernel/bpf/bpf_lru_list.c:bpf_lru_pop_free
  - kernel/bpf/bpf_lru_list.c:bpf_lru_list_pop_free_to_local
```
**Symbols:**

```
ffffffff81353450-ffffffff8135359a: __bpf_lru_list_shrink.isra.0 (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Selective Inline ⚠️</summary>

```c
unsigned int __bpf_lru_list_shrink(struct bpf_lru *lru, struct bpf_lru_list *l, unsigned int tgt_nshrink, struct list_head *free_list, enum bpf_lru_list_type tgt_free_type);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/bpf/bpf_lru_list.c (ffff80001027c630)
Location: kernel/bpf/bpf_lru_list.c:255
Inline: True
Direct callers:
  - kernel/bpf/bpf_lru_list.c:bpf_lru_pop_free
  - kernel/bpf/bpf_lru_list.c:bpf_lru_pop_free
```
**Symbols:**

```
ffff80001027c630-ffff80001027c7b0: __bpf_lru_list_shrink (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
unsigned int __bpf_lru_list_shrink(struct bpf_lru *lru, struct bpf_lru_list *l, unsigned int tgt_nshrink, struct list_head *free_list, enum bpf_lru_list_type tgt_free_type);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/bpf/bpf_lru_list.c (c04ae240)
Location: kernel/bpf/bpf_lru_list.c:255
Inline: True
Direct callers:
  - kernel/bpf/bpf_lru_list.c:bpf_lru_pop_free
  - kernel/bpf/bpf_lru_list.c:bpf_common_lru_pop_free
```
**Symbols:**

```
c04ae240-c04ae390: __bpf_lru_list_shrink (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
unsigned int __bpf_lru_list_shrink(struct bpf_lru *lru, struct bpf_lru_list *l, unsigned int tgt_nshrink, struct list_head *free_list, enum bpf_lru_list_type tgt_free_type);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/bpf/bpf_lru_list.c (c000000000325f90)
Location: kernel/bpf/bpf_lru_list.c:255
Inline: True
Direct callers:
  - kernel/bpf/bpf_lru_list.c:bpf_lru_pop_free
  - kernel/bpf/bpf_lru_list.c:bpf_common_lru_pop_free
```
**Symbols:**

```
c000000000325f90-c0000000003261b8: __bpf_lru_list_shrink (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
unsigned int __bpf_lru_list_shrink(struct bpf_lru *lru, struct bpf_lru_list *l, unsigned int tgt_nshrink, struct list_head *free_list, enum bpf_lru_list_type tgt_free_type);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/bpf/bpf_lru_list.c (ffffffe0001b3eec)
Location: kernel/bpf/bpf_lru_list.c:255
Inline: True
Direct callers:
  - kernel/bpf/bpf_lru_list.c:bpf_lru_pop_free
  - kernel/bpf/bpf_lru_list.c:bpf_common_lru_pop_free
```
**Symbols:**

```
ffffffe0001b3eec-ffffffe0001b3ff0: __bpf_lru_list_shrink (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Selective Inline ⚠️</summary>

```c
unsigned int __bpf_lru_list_shrink(struct bpf_lru *lru, struct bpf_lru_list *l, unsigned int tgt_nshrink, struct list_head *free_list, enum bpf_lru_list_type tgt_free_type);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/bpf/bpf_lru_list.c (ffffffff811efd40)
Location: kernel/bpf/bpf_lru_list.c:255
Inline: True
Direct callers:
  - kernel/bpf/bpf_lru_list.c:bpf_lru_pop_free
  - kernel/bpf/bpf_lru_list.c:bpf_common_lru_pop_free
```
**Symbols:**

```
ffffffff811efd40-ffffffff811efe83: __bpf_lru_list_shrink (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
unsigned int __bpf_lru_list_shrink(struct bpf_lru *lru, struct bpf_lru_list *l, unsigned int tgt_nshrink, struct list_head *free_list, enum bpf_lru_list_type tgt_free_type);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/bpf/bpf_lru_list.c (ffffffff811e2a90)
Location: kernel/bpf/bpf_lru_list.c:255
Inline: True
Direct callers:
  - kernel/bpf/bpf_lru_list.c:bpf_lru_pop_free
  - kernel/bpf/bpf_lru_list.c:bpf_common_lru_pop_free
```
**Symbols:**

```
ffffffff811e2a90-ffffffff811e2bd3: __bpf_lru_list_shrink (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
unsigned int __bpf_lru_list_shrink(struct bpf_lru *lru, struct bpf_lru_list *l, unsigned int tgt_nshrink, struct list_head *free_list, enum bpf_lru_list_type tgt_free_type);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/bpf/bpf_lru_list.c (ffffffff811edb10)
Location: kernel/bpf/bpf_lru_list.c:255
Inline: True
Direct callers:
  - kernel/bpf/bpf_lru_list.c:bpf_lru_pop_free
  - kernel/bpf/bpf_lru_list.c:bpf_common_lru_pop_free
```
**Symbols:**

```
ffffffff811edb10-ffffffff811edc53: __bpf_lru_list_shrink (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
unsigned int __bpf_lru_list_shrink(struct bpf_lru *lru, struct bpf_lru_list *l, unsigned int tgt_nshrink, struct list_head *free_list, enum bpf_lru_list_type tgt_free_type);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/bpf/bpf_lru_list.c (ffffffff811fbfe0)
Location: kernel/bpf/bpf_lru_list.c:255
Inline: True
Direct callers:
  - kernel/bpf/bpf_lru_list.c:bpf_lru_pop_free
  - kernel/bpf/bpf_lru_list.c:bpf_common_lru_pop_free
```
**Symbols:**

```
ffffffff811fbfe0-ffffffff811fc123: __bpf_lru_list_shrink (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>4.10</code> and <code>4.13</code> ✅
</li>
<li>
No changes between <code>4.13</code> and <code>4.15</code> ✅
</li>
<li>
No changes between <code>4.15</code> and <code>4.18</code> ✅
</li>
<li>
No changes between <code>4.18</code> and <code>5.0</code> ✅
</li>
<li>
No changes between <code>5.0</code> and <code>5.3</code> ✅
</li>
<li>
No changes between <code>5.3</code> and <code>5.4</code> ✅
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
