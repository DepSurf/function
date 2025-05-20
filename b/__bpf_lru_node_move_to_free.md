# Function: <code>__bpf_lru_node_move_to_free</code>

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
<summary>In <code>4.10</code>: ✅</summary>

```c
void __bpf_lru_node_move_to_free(struct bpf_lru_list *l, struct bpf_lru_node *node, struct list_head *free_list, enum bpf_lru_list_type tgt_free_type);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/bpf_lru_list.c (ffffffff811960b0)
Location: kernel/bpf/bpf_lru_list.c:64
Inline: False
Direct callers:
  - kernel/bpf/bpf_lru_list.c:bpf_lru_pop_free
  - kernel/bpf/bpf_lru_list.c:bpf_lru_pop_free
```
**Symbols:**

```
ffffffff811960b0-ffffffff81196128: __bpf_lru_node_move_to_free (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void __bpf_lru_node_move_to_free(struct bpf_lru_list *l, struct bpf_lru_node *node, struct list_head *free_list, enum bpf_lru_list_type tgt_free_type);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/bpf_lru_list.c (ffffffff8119d640)
Location: kernel/bpf/bpf_lru_list.c:64
Inline: False
Direct callers:
  - kernel/bpf/bpf_lru_list.c:bpf_lru_pop_free
  - kernel/bpf/bpf_lru_list.c:bpf_lru_pop_free
```
**Symbols:**

```
ffffffff8119d640-ffffffff8119d696: __bpf_lru_node_move_to_free (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void __bpf_lru_node_move_to_free(struct bpf_lru_list *l, struct bpf_lru_node *node, struct list_head *free_list, enum bpf_lru_list_type tgt_free_type);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/bpf_lru_list.c (ffffffff811ad200)
Location: kernel/bpf/bpf_lru_list.c:64
Inline: False
Direct callers:
  - kernel/bpf/bpf_lru_list.c:bpf_lru_pop_free
  - kernel/bpf/bpf_lru_list.c:bpf_lru_pop_free
```
**Symbols:**

```
ffffffff811ad200-ffffffff811ad255: __bpf_lru_node_move_to_free (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void __bpf_lru_node_move_to_free(struct bpf_lru_list *l, struct bpf_lru_node *node, struct list_head *free_list, enum bpf_lru_list_type tgt_free_type);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/bpf_lru_list.c (ffffffff811c4780)
Location: kernel/bpf/bpf_lru_list.c:64
Inline: False
Direct callers:
  - kernel/bpf/bpf_lru_list.c:bpf_lru_pop_free
  - kernel/bpf/bpf_lru_list.c:bpf_lru_pop_free
```
**Symbols:**

```
ffffffff811c4780-ffffffff811c47d5: __bpf_lru_node_move_to_free (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void __bpf_lru_node_move_to_free(struct bpf_lru_list *l, struct bpf_lru_node *node, struct list_head *free_list, enum bpf_lru_list_type tgt_free_type);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/bpf_lru_list.c (ffffffff811d6370)
Location: kernel/bpf/bpf_lru_list.c:64
Inline: False
Direct callers:
  - kernel/bpf/bpf_lru_list.c:bpf_lru_pop_free
  - kernel/bpf/bpf_lru_list.c:bpf_lru_pop_free
```
**Symbols:**

```
ffffffff811d6370-ffffffff811d63c5: __bpf_lru_node_move_to_free (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void __bpf_lru_node_move_to_free(struct bpf_lru_list *l, struct bpf_lru_node *node, struct list_head *free_list, enum bpf_lru_list_type tgt_free_type);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/bpf_lru_list.c (ffffffff811ead30)
Location: kernel/bpf/bpf_lru_list.c:61
Inline: False
Direct callers:
  - kernel/bpf/bpf_lru_list.c:bpf_common_lru_pop_free
  - kernel/bpf/bpf_lru_list.c:bpf_common_lru_pop_free
```
**Symbols:**

```
ffffffff811ead30-ffffffff811ead86: __bpf_lru_node_move_to_free (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void __bpf_lru_node_move_to_free(struct bpf_lru_list *l, struct bpf_lru_node *node, struct list_head *free_list, enum bpf_lru_list_type tgt_free_type);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/bpf_lru_list.c (ffffffff811f7490)
Location: kernel/bpf/bpf_lru_list.c:61
Inline: False
Direct callers:
  - kernel/bpf/bpf_lru_list.c:bpf_common_lru_pop_free
  - kernel/bpf/bpf_lru_list.c:bpf_common_lru_pop_free
```
**Symbols:**

```
ffffffff811f7490-ffffffff811f74e6: __bpf_lru_node_move_to_free (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
void __bpf_lru_node_move_to_free(struct bpf_lru_list *l, struct bpf_lru_node *node, struct list_head *free_list, enum bpf_lru_list_type tgt_free_type);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/bpf/bpf_lru_list.c (ffffffff8121b840)
Location: kernel/bpf/bpf_lru_list.c:61
Inline: True
Inline callers:
  - kernel/bpf/bpf_lru_list.c:bpf_lru_list_pop_free_to_local
```
**Symbols:**

```
ffffffff8121b160-ffffffff8121b1bb: __bpf_lru_node_move_to_free (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
void __bpf_lru_node_move_to_free(struct bpf_lru_list *l, struct bpf_lru_node *node, struct list_head *free_list, enum bpf_lru_list_type tgt_free_type);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/bpf/bpf_lru_list.c (ffffffff8121e7c0)
Location: kernel/bpf/bpf_lru_list.c:61
Inline: True
Inline callers:
  - kernel/bpf/bpf_lru_list.c:bpf_lru_list_pop_free_to_local
```
**Symbols:**

```
ffffffff8121e0e0-ffffffff8121e13b: __bpf_lru_node_move_to_free (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
void __bpf_lru_node_move_to_free(struct bpf_lru_list *l, struct bpf_lru_node *node, struct list_head *free_list, enum bpf_lru_list_type tgt_free_type);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/bpf/bpf_lru_list.c (ffffffff812220b5)
Location: kernel/bpf/bpf_lru_list.c:61
Inline: True
Inline callers:
  - kernel/bpf/bpf_lru_list.c:bpf_lru_list_pop_free_to_local
```
**Symbols:**

```
ffffffff81221bb0-ffffffff81221c12: __bpf_lru_node_move_to_free (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
void __bpf_lru_node_move_to_free(struct bpf_lru_list *l, struct bpf_lru_node *node, struct list_head *free_list, enum bpf_lru_list_type tgt_free_type);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/bpf/bpf_lru_list.c (ffffffff81259c79)
Location: kernel/bpf/bpf_lru_list.c:61
Inline: True
Inline callers:
  - kernel/bpf/bpf_lru_list.c:bpf_lru_list_pop_free_to_local
```
**Symbols:**

```
ffffffff81259690-ffffffff8125972b: __bpf_lru_node_move_to_free (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
void __bpf_lru_node_move_to_free(struct bpf_lru_list *l, struct bpf_lru_node *node, struct list_head *free_list, enum bpf_lru_list_type tgt_free_type);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/bpf/bpf_lru_list.c (ffffffff812a2c99)
Location: kernel/bpf/bpf_lru_list.c:61
Inline: True
Inline callers:
  - kernel/bpf/bpf_lru_list.c:bpf_lru_list_pop_free_to_local
```
**Symbols:**

```
ffffffff812a2610-ffffffff812a26cb: __bpf_lru_node_move_to_free (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
void __bpf_lru_node_move_to_free(struct bpf_lru_list *l, struct bpf_lru_node *node, struct list_head *free_list, enum bpf_lru_list_type tgt_free_type);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/bpf/bpf_lru_list.c (ffffffff813007a9)
Location: kernel/bpf/bpf_lru_list.c:61
Inline: True
Inline callers:
  - kernel/bpf/bpf_lru_list.c:bpf_lru_list_pop_free_to_local
```
**Symbols:**

```
ffffffff813000d0-ffffffff8130018b: __bpf_lru_node_move_to_free (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
void __bpf_lru_node_move_to_free(struct bpf_lru_list *l, struct bpf_lru_node *node, struct list_head *free_list, enum bpf_lru_list_type tgt_free_type);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/bpf/bpf_lru_list.c (ffffffff8132f312)
Location: kernel/bpf/bpf_lru_list.c:66
Inline: True
Inline callers:
  - kernel/bpf/bpf_lru_list.c:bpf_lru_list_pop_free_to_local
```
**Symbols:**

```
ffffffff8132ec30-ffffffff8132eceb: __bpf_lru_node_move_to_free (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
void __bpf_lru_node_move_to_free(struct bpf_lru_list *l, struct bpf_lru_node *node, struct list_head *free_list, enum bpf_lru_list_type tgt_free_type);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/bpf/bpf_lru_list.c (ffffffff81353832)
Location: kernel/bpf/bpf_lru_list.c:66
Inline: True
Inline callers:
  - kernel/bpf/bpf_lru_list.c:bpf_lru_list_pop_free_to_local
```
**Symbols:**

```
ffffffff81353150-ffffffff8135320b: __bpf_lru_node_move_to_free (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: ✅</summary>

```c
void __bpf_lru_node_move_to_free(struct bpf_lru_list *l, struct bpf_lru_node *node, struct list_head *free_list, enum bpf_lru_list_type tgt_free_type);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/bpf_lru_list.c (ffff80001027c2a8)
Location: kernel/bpf/bpf_lru_list.c:61
Inline: False
Direct callers:
  - kernel/bpf/bpf_lru_list.c:bpf_lru_pop_free
  - kernel/bpf/bpf_lru_list.c:bpf_lru_pop_free
```
**Symbols:**

```
ffff80001027c2a8-ffff80001027c354: __bpf_lru_node_move_to_free (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void __bpf_lru_node_move_to_free(struct bpf_lru_list *l, struct bpf_lru_node *node, struct list_head *free_list, enum bpf_lru_list_type tgt_free_type);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/bpf_lru_list.c (c04adf08)
Location: kernel/bpf/bpf_lru_list.c:61
Inline: False
Direct callers:
  - kernel/bpf/bpf_lru_list.c:bpf_common_lru_pop_free
  - kernel/bpf/bpf_lru_list.c:bpf_common_lru_pop_free
```
**Symbols:**

```
c04adf08-c04adfb8: __bpf_lru_node_move_to_free (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void __bpf_lru_node_move_to_free(struct bpf_lru_list *l, struct bpf_lru_node *node, struct list_head *free_list, enum bpf_lru_list_type tgt_free_type);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/bpf_lru_list.c (c000000000325b10)
Location: kernel/bpf/bpf_lru_list.c:61
Inline: False
Direct callers:
  - kernel/bpf/bpf_lru_list.c:bpf_common_lru_pop_free
  - kernel/bpf/bpf_lru_list.c:bpf_common_lru_pop_free
```
**Symbols:**

```
c000000000325b10-c000000000325b98: __bpf_lru_node_move_to_free (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void __bpf_lru_node_move_to_free(struct bpf_lru_list *l, struct bpf_lru_node *node, struct list_head *free_list, enum bpf_lru_list_type tgt_free_type);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/bpf_lru_list.c (ffffffe0001b3bfe)
Location: kernel/bpf/bpf_lru_list.c:61
Inline: False
Direct callers:
  - kernel/bpf/bpf_lru_list.c:bpf_common_lru_pop_free
  - kernel/bpf/bpf_lru_list.c:bpf_common_lru_pop_free
```
**Symbols:**

```
ffffffe0001b3bfe-ffffffe0001b3c90: __bpf_lru_node_move_to_free (STB_LOCAL)
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
void __bpf_lru_node_move_to_free(struct bpf_lru_list *l, struct bpf_lru_node *node, struct list_head *free_list, enum bpf_lru_list_type tgt_free_type);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/bpf_lru_list.c (ffffffff811efab0)
Location: kernel/bpf/bpf_lru_list.c:61
Inline: False
Direct callers:
  - kernel/bpf/bpf_lru_list.c:bpf_common_lru_pop_free
  - kernel/bpf/bpf_lru_list.c:bpf_common_lru_pop_free
```
**Symbols:**

```
ffffffff811efab0-ffffffff811efb06: __bpf_lru_node_move_to_free (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void __bpf_lru_node_move_to_free(struct bpf_lru_list *l, struct bpf_lru_node *node, struct list_head *free_list, enum bpf_lru_list_type tgt_free_type);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/bpf_lru_list.c (ffffffff811e2800)
Location: kernel/bpf/bpf_lru_list.c:61
Inline: False
Direct callers:
  - kernel/bpf/bpf_lru_list.c:bpf_common_lru_pop_free
  - kernel/bpf/bpf_lru_list.c:bpf_common_lru_pop_free
```
**Symbols:**

```
ffffffff811e2800-ffffffff811e2856: __bpf_lru_node_move_to_free (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void __bpf_lru_node_move_to_free(struct bpf_lru_list *l, struct bpf_lru_node *node, struct list_head *free_list, enum bpf_lru_list_type tgt_free_type);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/bpf_lru_list.c (ffffffff811ed880)
Location: kernel/bpf/bpf_lru_list.c:61
Inline: False
Direct callers:
  - kernel/bpf/bpf_lru_list.c:bpf_common_lru_pop_free
  - kernel/bpf/bpf_lru_list.c:bpf_common_lru_pop_free
```
**Symbols:**

```
ffffffff811ed880-ffffffff811ed8d6: __bpf_lru_node_move_to_free (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void __bpf_lru_node_move_to_free(struct bpf_lru_list *l, struct bpf_lru_node *node, struct list_head *free_list, enum bpf_lru_list_type tgt_free_type);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/bpf_lru_list.c (ffffffff811fbd50)
Location: kernel/bpf/bpf_lru_list.c:61
Inline: False
Direct callers:
  - kernel/bpf/bpf_lru_list.c:bpf_common_lru_pop_free
  - kernel/bpf/bpf_lru_list.c:bpf_common_lru_pop_free
```
**Symbols:**

```
ffffffff811fbd50-ffffffff811fbda6: __bpf_lru_node_move_to_free (STB_LOCAL)
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
<li>
No changes between <code>6.2</code> and <code>6.5</code> ✅
</li>
<li>
No changes between <code>6.5</code> and <code>6.8</code> ✅
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
