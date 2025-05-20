# Function: <code>__bpf_lru_node_move</code>

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
void __bpf_lru_node_move(struct bpf_lru_list *l, struct bpf_lru_node *node, enum bpf_lru_list_type tgt_type);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/bpf_lru_list.c (ffffffff81196130)
Location: kernel/bpf/bpf_lru_list.c:103
Inline: False
Direct callers:
  - kernel/bpf/bpf_lru_list.c:bpf_lru_push_free
  - kernel/bpf/bpf_lru_list.c:bpf_lru_pop_free
```
**Symbols:**

```
ffffffff81196130-ffffffff81196203: __bpf_lru_node_move (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void __bpf_lru_node_move(struct bpf_lru_list *l, struct bpf_lru_node *node, enum bpf_lru_list_type tgt_type);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/bpf_lru_list.c (ffffffff8119d6a0)
Location: kernel/bpf/bpf_lru_list.c:103
Inline: False
Direct callers:
  - kernel/bpf/bpf_lru_list.c:bpf_lru_push_free
  - kernel/bpf/bpf_lru_list.c:bpf_lru_pop_free
```
**Symbols:**

```
ffffffff8119d6a0-ffffffff8119d722: __bpf_lru_node_move (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void __bpf_lru_node_move(struct bpf_lru_list *l, struct bpf_lru_node *node, enum bpf_lru_list_type tgt_type);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/bpf_lru_list.c (ffffffff811ad260)
Location: kernel/bpf/bpf_lru_list.c:103
Inline: False
Direct callers:
  - kernel/bpf/bpf_lru_list.c:bpf_lru_push_free
  - kernel/bpf/bpf_lru_list.c:bpf_lru_pop_free
```
**Symbols:**

```
ffffffff811ad260-ffffffff811ad2e1: __bpf_lru_node_move (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void __bpf_lru_node_move(struct bpf_lru_list *l, struct bpf_lru_node *node, enum bpf_lru_list_type tgt_type);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/bpf_lru_list.c (ffffffff811c4830)
Location: kernel/bpf/bpf_lru_list.c:103
Inline: False
Direct callers:
  - kernel/bpf/bpf_lru_list.c:bpf_lru_push_free
  - kernel/bpf/bpf_lru_list.c:bpf_lru_pop_free
```
**Symbols:**

```
ffffffff811c4830-ffffffff811c48b1: __bpf_lru_node_move (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void __bpf_lru_node_move(struct bpf_lru_list *l, struct bpf_lru_node *node, enum bpf_lru_list_type tgt_type);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/bpf_lru_list.c (ffffffff811d6420)
Location: kernel/bpf/bpf_lru_list.c:103
Inline: False
Direct callers:
  - kernel/bpf/bpf_lru_list.c:bpf_lru_push_free
  - kernel/bpf/bpf_lru_list.c:bpf_lru_pop_free
```
**Symbols:**

```
ffffffff811d6420-ffffffff811d64a1: __bpf_lru_node_move (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void __bpf_lru_node_move(struct bpf_lru_list *l, struct bpf_lru_node *node, enum bpf_lru_list_type tgt_type);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/bpf_lru_list.c (ffffffff811ead90)
Location: kernel/bpf/bpf_lru_list.c:100
Inline: False
Direct callers:
  - kernel/bpf/bpf_lru_list.c:bpf_lru_push_free
  - kernel/bpf/bpf_lru_list.c:bpf_lru_pop_free
```
**Symbols:**

```
ffffffff811ead90-ffffffff811eae1b: __bpf_lru_node_move (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void __bpf_lru_node_move(struct bpf_lru_list *l, struct bpf_lru_node *node, enum bpf_lru_list_type tgt_type);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/bpf_lru_list.c (ffffffff811f74f0)
Location: kernel/bpf/bpf_lru_list.c:100
Inline: False
Direct callers:
  - kernel/bpf/bpf_lru_list.c:bpf_lru_push_free
  - kernel/bpf/bpf_lru_list.c:bpf_lru_pop_free
```
**Symbols:**

```
ffffffff811f74f0-ffffffff811f757b: __bpf_lru_node_move (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void __bpf_lru_node_move(struct bpf_lru_list *l, struct bpf_lru_node *node, enum bpf_lru_list_type tgt_type);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/bpf_lru_list.c (ffffffff8121b1c0)
Location: kernel/bpf/bpf_lru_list.c:100
Inline: False
Direct callers:
  - kernel/bpf/bpf_lru_list.c:bpf_lru_push_free
  - kernel/bpf/bpf_lru_list.c:bpf_common_lru_push_free
  - kernel/bpf/bpf_lru_list.c:bpf_percpu_lru_pop_free
  - kernel/bpf/bpf_lru_list.c:__bpf_lru_list_rotate_inactive
  - kernel/bpf/bpf_lru_list.c:__bpf_lru_list_rotate_active
  - kernel/bpf/bpf_lru_list.c:__bpf_lru_list_rotate_active
```
**Symbols:**

```
ffffffff8121b1c0-ffffffff8121b23d: __bpf_lru_node_move (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void __bpf_lru_node_move(struct bpf_lru_list *l, struct bpf_lru_node *node, enum bpf_lru_list_type tgt_type);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/bpf_lru_list.c (ffffffff8121e140)
Location: kernel/bpf/bpf_lru_list.c:100
Inline: False
Direct callers:
  - kernel/bpf/bpf_lru_list.c:bpf_lru_push_free
  - kernel/bpf/bpf_lru_list.c:bpf_common_lru_push_free
  - kernel/bpf/bpf_lru_list.c:bpf_percpu_lru_pop_free
  - kernel/bpf/bpf_lru_list.c:__bpf_lru_list_rotate_inactive
  - kernel/bpf/bpf_lru_list.c:__bpf_lru_list_rotate_active
  - kernel/bpf/bpf_lru_list.c:__bpf_lru_list_rotate_active
```
**Symbols:**

```
ffffffff8121e140-ffffffff8121e1bd: __bpf_lru_node_move (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void __bpf_lru_node_move(struct bpf_lru_list *l, struct bpf_lru_node *node, enum bpf_lru_list_type tgt_type);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/bpf_lru_list.c (ffffffff81221c20)
Location: kernel/bpf/bpf_lru_list.c:100
Inline: False
Direct callers:
  - kernel/bpf/bpf_lru_list.c:bpf_lru_push_free
  - kernel/bpf/bpf_lru_list.c:bpf_lru_pop_free
  - kernel/bpf/bpf_lru_list.c:__bpf_lru_list_rotate_inactive
  - kernel/bpf/bpf_lru_list.c:__bpf_lru_list_rotate_active
  - kernel/bpf/bpf_lru_list.c:__bpf_lru_list_rotate_active
```
**Symbols:**

```
ffffffff81221c20-ffffffff81221ca1: __bpf_lru_node_move (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
void __bpf_lru_node_move(struct bpf_lru_list *l, struct bpf_lru_node *node, enum bpf_lru_list_type tgt_type);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/bpf/bpf_lru_list.c (ffffffff81259a69)
Location: kernel/bpf/bpf_lru_list.c:100
Inline: True
Inline callers:
  - kernel/bpf/bpf_lru_list.c:__bpf_lru_list_rotate_active
Direct callers:
  - kernel/bpf/bpf_lru_list.c:bpf_lru_push_free
  - kernel/bpf/bpf_lru_list.c:bpf_lru_pop_free
  - kernel/bpf/bpf_lru_list.c:__bpf_lru_list_rotate_inactive
  - kernel/bpf/bpf_lru_list.c:__bpf_lru_list_rotate_active
```
**Symbols:**

```
ffffffff81259730-ffffffff81259821: __bpf_lru_node_move (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
void __bpf_lru_node_move(struct bpf_lru_list *l, struct bpf_lru_node *node, enum bpf_lru_list_type tgt_type);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/bpf/bpf_lru_list.c (ffffffff812a2a96)
Location: kernel/bpf/bpf_lru_list.c:100
Inline: True
Inline callers:
  - kernel/bpf/bpf_lru_list.c:__bpf_lru_list_rotate_active
Direct callers:
  - kernel/bpf/bpf_lru_list.c:bpf_lru_push_free
  - kernel/bpf/bpf_lru_list.c:bpf_lru_pop_free
  - kernel/bpf/bpf_lru_list.c:__bpf_lru_list_rotate_inactive
  - kernel/bpf/bpf_lru_list.c:__bpf_lru_list_rotate_active
```
**Symbols:**

```
ffffffff812a26d0-ffffffff812a27dc: __bpf_lru_node_move (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
void __bpf_lru_node_move(struct bpf_lru_list *l, struct bpf_lru_node *node, enum bpf_lru_list_type tgt_type);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/bpf/bpf_lru_list.c (ffffffff81300569)
Location: kernel/bpf/bpf_lru_list.c:100
Inline: True
Inline callers:
  - kernel/bpf/bpf_lru_list.c:__bpf_lru_list_rotate_active
Direct callers:
  - kernel/bpf/bpf_lru_list.c:bpf_lru_push_free
  - kernel/bpf/bpf_lru_list.c:bpf_lru_pop_free
  - kernel/bpf/bpf_lru_list.c:__bpf_lru_list_rotate_inactive
  - kernel/bpf/bpf_lru_list.c:__bpf_lru_list_rotate_active
```
**Symbols:**

```
ffffffff813001a0-ffffffff813002ac: __bpf_lru_node_move (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
void __bpf_lru_node_move(struct bpf_lru_list *l, struct bpf_lru_node *node, enum bpf_lru_list_type tgt_type);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/bpf/bpf_lru_list.c (ffffffff8132f0c9)
Location: kernel/bpf/bpf_lru_list.c:105
Inline: True
Inline callers:
  - kernel/bpf/bpf_lru_list.c:__bpf_lru_list_rotate_active
Direct callers:
  - kernel/bpf/bpf_lru_list.c:bpf_lru_push_free
  - kernel/bpf/bpf_lru_list.c:bpf_lru_pop_free
  - kernel/bpf/bpf_lru_list.c:__bpf_lru_list_rotate_inactive
  - kernel/bpf/bpf_lru_list.c:__bpf_lru_list_rotate_active
```
**Symbols:**

```
ffffffff8132ed00-ffffffff8132ee0c: __bpf_lru_node_move (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
void __bpf_lru_node_move(struct bpf_lru_list *l, struct bpf_lru_node *node, enum bpf_lru_list_type tgt_type);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/bpf/bpf_lru_list.c (ffffffff813535e9)
Location: kernel/bpf/bpf_lru_list.c:105
Inline: True
Inline callers:
  - kernel/bpf/bpf_lru_list.c:__bpf_lru_list_rotate_active
Direct callers:
  - kernel/bpf/bpf_lru_list.c:bpf_lru_push_free
  - kernel/bpf/bpf_lru_list.c:bpf_lru_pop_free
  - kernel/bpf/bpf_lru_list.c:__bpf_lru_list_rotate_inactive
  - kernel/bpf/bpf_lru_list.c:__bpf_lru_list_rotate_active
```
**Symbols:**

```
ffffffff81353220-ffffffff8135332c: __bpf_lru_node_move (STB_LOCAL)
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
void __bpf_lru_node_move(struct bpf_lru_list *l, struct bpf_lru_node *node, enum bpf_lru_list_type tgt_type);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/bpf_lru_list.c (ffff80001027c358)
Location: kernel/bpf/bpf_lru_list.c:100
Inline: False
Direct callers:
  - kernel/bpf/bpf_lru_list.c:bpf_lru_push_free
  - kernel/bpf/bpf_lru_list.c:bpf_lru_pop_free
```
**Symbols:**

```
ffff80001027c358-ffff80001027c440: __bpf_lru_node_move (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void __bpf_lru_node_move(struct bpf_lru_list *l, struct bpf_lru_node *node, enum bpf_lru_list_type tgt_type);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/bpf_lru_list.c (c04adfb8)
Location: kernel/bpf/bpf_lru_list.c:100
Inline: False
Direct callers:
  - kernel/bpf/bpf_lru_list.c:bpf_lru_push_free
  - kernel/bpf/bpf_lru_list.c:bpf_lru_pop_free
  - kernel/bpf/bpf_lru_list.c:__bpf_lru_list_rotate_inactive
  - kernel/bpf/bpf_lru_list.c:__bpf_lru_list_rotate_active
```
**Symbols:**

```
c04adfb8-c04ae080: __bpf_lru_node_move (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void __bpf_lru_node_move(struct bpf_lru_list *l, struct bpf_lru_node *node, enum bpf_lru_list_type tgt_type);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/bpf_lru_list.c (c000000000325ba0)
Location: kernel/bpf/bpf_lru_list.c:100
Inline: False
Direct callers:
  - kernel/bpf/bpf_lru_list.c:bpf_lru_push_free
  - kernel/bpf/bpf_lru_list.c:bpf_lru_pop_free
  - kernel/bpf/bpf_lru_list.c:__bpf_lru_list_rotate_inactive
  - kernel/bpf/bpf_lru_list.c:__bpf_lru_list_rotate_active
```
**Symbols:**

```
c000000000325ba0-c000000000325cb8: __bpf_lru_node_move (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void __bpf_lru_node_move(struct bpf_lru_list *l, struct bpf_lru_node *node, enum bpf_lru_list_type tgt_type);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/bpf_lru_list.c (ffffffe0001b3c90)
Location: kernel/bpf/bpf_lru_list.c:100
Inline: False
Direct callers:
  - kernel/bpf/bpf_lru_list.c:bpf_lru_push_free
  - kernel/bpf/bpf_lru_list.c:bpf_lru_pop_free
  - kernel/bpf/bpf_lru_list.c:__bpf_lru_list_rotate_inactive
  - kernel/bpf/bpf_lru_list.c:__bpf_lru_list_rotate_active
```
**Symbols:**

```
ffffffe0001b3c90-ffffffe0001b3d5a: __bpf_lru_node_move (STB_LOCAL)
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
void __bpf_lru_node_move(struct bpf_lru_list *l, struct bpf_lru_node *node, enum bpf_lru_list_type tgt_type);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/bpf_lru_list.c (ffffffff811efb10)
Location: kernel/bpf/bpf_lru_list.c:100
Inline: False
Direct callers:
  - kernel/bpf/bpf_lru_list.c:bpf_lru_push_free
  - kernel/bpf/bpf_lru_list.c:bpf_lru_pop_free
```
**Symbols:**

```
ffffffff811efb10-ffffffff811efb9b: __bpf_lru_node_move (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void __bpf_lru_node_move(struct bpf_lru_list *l, struct bpf_lru_node *node, enum bpf_lru_list_type tgt_type);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/bpf_lru_list.c (ffffffff811e2860)
Location: kernel/bpf/bpf_lru_list.c:100
Inline: False
Direct callers:
  - kernel/bpf/bpf_lru_list.c:bpf_lru_push_free
  - kernel/bpf/bpf_lru_list.c:bpf_lru_pop_free
```
**Symbols:**

```
ffffffff811e2860-ffffffff811e28eb: __bpf_lru_node_move (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void __bpf_lru_node_move(struct bpf_lru_list *l, struct bpf_lru_node *node, enum bpf_lru_list_type tgt_type);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/bpf_lru_list.c (ffffffff811ed8e0)
Location: kernel/bpf/bpf_lru_list.c:100
Inline: False
Direct callers:
  - kernel/bpf/bpf_lru_list.c:bpf_lru_push_free
  - kernel/bpf/bpf_lru_list.c:bpf_lru_pop_free
```
**Symbols:**

```
ffffffff811ed8e0-ffffffff811ed96b: __bpf_lru_node_move (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void __bpf_lru_node_move(struct bpf_lru_list *l, struct bpf_lru_node *node, enum bpf_lru_list_type tgt_type);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/bpf_lru_list.c (ffffffff811fbdb0)
Location: kernel/bpf/bpf_lru_list.c:100
Inline: False
Direct callers:
  - kernel/bpf/bpf_lru_list.c:bpf_lru_push_free
  - kernel/bpf/bpf_lru_list.c:bpf_lru_pop_free
```
**Symbols:**

```
ffffffff811fbdb0-ffffffff811fbe3b: __bpf_lru_node_move (STB_LOCAL)
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
