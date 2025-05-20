# Function: <code>__bpf_lru_node_move_in</code>

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
void __bpf_lru_node_move_in(struct bpf_lru_list *l, struct bpf_lru_node *node, enum bpf_lru_list_type tgt_type);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/bpf_lru_list.c (ffffffff81196210)
Location: kernel/bpf/bpf_lru_list.c:85
Inline: False
Direct callers:
  - kernel/bpf/bpf_lru_list.c:bpf_lru_pop_free
  - kernel/bpf/bpf_lru_list.c:bpf_lru_pop_free
```
**Symbols:**

```
ffffffff81196210-ffffffff811962a9: __bpf_lru_node_move_in (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void __bpf_lru_node_move_in(struct bpf_lru_list *l, struct bpf_lru_node *node, enum bpf_lru_list_type tgt_type);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/bpf_lru_list.c (ffffffff8119d730)
Location: kernel/bpf/bpf_lru_list.c:85
Inline: False
Direct callers:
  - kernel/bpf/bpf_lru_list.c:bpf_lru_pop_free
  - kernel/bpf/bpf_lru_list.c:bpf_lru_pop_free
```
**Symbols:**

```
ffffffff8119d730-ffffffff8119d779: __bpf_lru_node_move_in (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void __bpf_lru_node_move_in(struct bpf_lru_list *l, struct bpf_lru_node *node, enum bpf_lru_list_type tgt_type);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/bpf_lru_list.c (ffffffff811ad2f0)
Location: kernel/bpf/bpf_lru_list.c:85
Inline: False
Direct callers:
  - kernel/bpf/bpf_lru_list.c:bpf_lru_pop_free
  - kernel/bpf/bpf_lru_list.c:bpf_lru_pop_free
```
**Symbols:**

```
ffffffff811ad2f0-ffffffff811ad338: __bpf_lru_node_move_in (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void __bpf_lru_node_move_in(struct bpf_lru_list *l, struct bpf_lru_node *node, enum bpf_lru_list_type tgt_type);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/bpf_lru_list.c (ffffffff811c47e0)
Location: kernel/bpf/bpf_lru_list.c:85
Inline: False
Direct callers:
  - kernel/bpf/bpf_lru_list.c:bpf_lru_pop_free
  - kernel/bpf/bpf_lru_list.c:bpf_lru_pop_free
```
**Symbols:**

```
ffffffff811c47e0-ffffffff811c4828: __bpf_lru_node_move_in (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void __bpf_lru_node_move_in(struct bpf_lru_list *l, struct bpf_lru_node *node, enum bpf_lru_list_type tgt_type);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/bpf_lru_list.c (ffffffff811d63d0)
Location: kernel/bpf/bpf_lru_list.c:85
Inline: False
Direct callers:
  - kernel/bpf/bpf_lru_list.c:bpf_lru_pop_free
  - kernel/bpf/bpf_lru_list.c:bpf_lru_pop_free
```
**Symbols:**

```
ffffffff811d63d0-ffffffff811d6418: __bpf_lru_node_move_in (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void __bpf_lru_node_move_in(struct bpf_lru_list *l, struct bpf_lru_node *node, enum bpf_lru_list_type tgt_type);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/bpf_lru_list.c (ffffffff811eae20)
Location: kernel/bpf/bpf_lru_list.c:82
Inline: False
Direct callers:
  - kernel/bpf/bpf_lru_list.c:bpf_common_lru_pop_free
  - kernel/bpf/bpf_lru_list.c:bpf_common_lru_pop_free
```
**Symbols:**

```
ffffffff811eae20-ffffffff811eae76: __bpf_lru_node_move_in (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void __bpf_lru_node_move_in(struct bpf_lru_list *l, struct bpf_lru_node *node, enum bpf_lru_list_type tgt_type);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/bpf_lru_list.c (ffffffff811f7580)
Location: kernel/bpf/bpf_lru_list.c:82
Inline: False
Direct callers:
  - kernel/bpf/bpf_lru_list.c:bpf_common_lru_pop_free
  - kernel/bpf/bpf_lru_list.c:bpf_common_lru_pop_free
```
**Symbols:**

```
ffffffff811f7580-ffffffff811f75d6: __bpf_lru_node_move_in (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/bpf/bpf_lru_list.c (ffffffff8121b6f6)
Location: kernel/bpf/bpf_lru_list.c:82
Inline: True
Inline callers:
  - kernel/bpf/bpf_lru_list.c:__local_list_flush
  - kernel/bpf/bpf_lru_list.c:__local_list_flush
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/bpf/bpf_lru_list.c (ffffffff8121e676)
Location: kernel/bpf/bpf_lru_list.c:82
Inline: True
Inline callers:
  - kernel/bpf/bpf_lru_list.c:__local_list_flush
  - kernel/bpf/bpf_lru_list.c:__local_list_flush
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
In kernel/bpf/bpf_lru_list.c (ffffffff81221f8f)
Location: kernel/bpf/bpf_lru_list.c:82
Inline: True
Inline callers:
  - kernel/bpf/bpf_lru_list.c:bpf_lru_list_pop_free_to_local
  - kernel/bpf/bpf_lru_list.c:bpf_lru_list_pop_free_to_local
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
In kernel/bpf/bpf_lru_list.c (ffffffff81259b69)
Location: kernel/bpf/bpf_lru_list.c:82
Inline: True
Inline callers:
  - kernel/bpf/bpf_lru_list.c:bpf_lru_list_pop_free_to_local
  - kernel/bpf/bpf_lru_list.c:bpf_lru_list_pop_free_to_local
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
In kernel/bpf/bpf_lru_list.c (ffffffff812a2bdb)
Location: kernel/bpf/bpf_lru_list.c:82
Inline: True
Inline callers:
  - kernel/bpf/bpf_lru_list.c:bpf_lru_list_pop_free_to_local
  - kernel/bpf/bpf_lru_list.c:bpf_lru_list_pop_free_to_local
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
In kernel/bpf/bpf_lru_list.c (ffffffff813006eb)
Location: kernel/bpf/bpf_lru_list.c:82
Inline: True
Inline callers:
  - kernel/bpf/bpf_lru_list.c:bpf_lru_list_pop_free_to_local
  - kernel/bpf/bpf_lru_list.c:bpf_lru_list_pop_free_to_local
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
In kernel/bpf/bpf_lru_list.c (ffffffff8132f1f9)
Location: kernel/bpf/bpf_lru_list.c:87
Inline: True
Inline callers:
  - kernel/bpf/bpf_lru_list.c:bpf_lru_list_pop_free_to_local
  - kernel/bpf/bpf_lru_list.c:bpf_lru_list_pop_free_to_local
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
In kernel/bpf/bpf_lru_list.c (ffffffff81353719)
Location: kernel/bpf/bpf_lru_list.c:87
Inline: True
Inline callers:
  - kernel/bpf/bpf_lru_list.c:bpf_lru_list_pop_free_to_local
  - kernel/bpf/bpf_lru_list.c:bpf_lru_list_pop_free_to_local
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
void __bpf_lru_node_move_in(struct bpf_lru_list *l, struct bpf_lru_node *node, enum bpf_lru_list_type tgt_type);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/bpf_lru_list.c (ffff80001027c440)
Location: kernel/bpf/bpf_lru_list.c:82
Inline: False
Direct callers:
  - kernel/bpf/bpf_lru_list.c:bpf_lru_pop_free
```
**Symbols:**

```
ffff80001027c440-ffff80001027c4d0: __bpf_lru_node_move_in (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void __bpf_lru_node_move_in(struct bpf_lru_list *l, struct bpf_lru_node *node, enum bpf_lru_list_type tgt_type);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/bpf_lru_list.c (c04ae1a8)
Location: kernel/bpf/bpf_lru_list.c:82
Inline: False
Direct callers:
  - kernel/bpf/bpf_lru_list.c:bpf_common_lru_pop_free
```
**Symbols:**

```
c04ae1a8-c04ae240: __bpf_lru_node_move_in (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void __bpf_lru_node_move_in(struct bpf_lru_list *l, struct bpf_lru_node *node, enum bpf_lru_list_type tgt_type);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/bpf_lru_list.c (c000000000325ec0)
Location: kernel/bpf/bpf_lru_list.c:82
Inline: False
Direct callers:
  - kernel/bpf/bpf_lru_list.c:bpf_common_lru_pop_free
```
**Symbols:**

```
c000000000325ec0-c000000000325f88: __bpf_lru_node_move_in (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void __bpf_lru_node_move_in(struct bpf_lru_list *l, struct bpf_lru_node *node, enum bpf_lru_list_type tgt_type);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/bpf_lru_list.c (ffffffe0001b3e76)
Location: kernel/bpf/bpf_lru_list.c:82
Inline: False
Direct callers:
  - kernel/bpf/bpf_lru_list.c:bpf_common_lru_pop_free
```
**Symbols:**

```
ffffffe0001b3e76-ffffffe0001b3eec: __bpf_lru_node_move_in (STB_LOCAL)
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
void __bpf_lru_node_move_in(struct bpf_lru_list *l, struct bpf_lru_node *node, enum bpf_lru_list_type tgt_type);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/bpf_lru_list.c (ffffffff811efba0)
Location: kernel/bpf/bpf_lru_list.c:82
Inline: False
Direct callers:
  - kernel/bpf/bpf_lru_list.c:bpf_common_lru_pop_free
  - kernel/bpf/bpf_lru_list.c:bpf_common_lru_pop_free
```
**Symbols:**

```
ffffffff811efba0-ffffffff811efbf6: __bpf_lru_node_move_in (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void __bpf_lru_node_move_in(struct bpf_lru_list *l, struct bpf_lru_node *node, enum bpf_lru_list_type tgt_type);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/bpf_lru_list.c (ffffffff811e28f0)
Location: kernel/bpf/bpf_lru_list.c:82
Inline: False
Direct callers:
  - kernel/bpf/bpf_lru_list.c:bpf_common_lru_pop_free
  - kernel/bpf/bpf_lru_list.c:bpf_common_lru_pop_free
```
**Symbols:**

```
ffffffff811e28f0-ffffffff811e2946: __bpf_lru_node_move_in (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void __bpf_lru_node_move_in(struct bpf_lru_list *l, struct bpf_lru_node *node, enum bpf_lru_list_type tgt_type);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/bpf_lru_list.c (ffffffff811ed970)
Location: kernel/bpf/bpf_lru_list.c:82
Inline: False
Direct callers:
  - kernel/bpf/bpf_lru_list.c:bpf_common_lru_pop_free
  - kernel/bpf/bpf_lru_list.c:bpf_common_lru_pop_free
```
**Symbols:**

```
ffffffff811ed970-ffffffff811ed9c6: __bpf_lru_node_move_in (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void __bpf_lru_node_move_in(struct bpf_lru_list *l, struct bpf_lru_node *node, enum bpf_lru_list_type tgt_type);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/bpf_lru_list.c (ffffffff811fbe40)
Location: kernel/bpf/bpf_lru_list.c:82
Inline: False
Direct callers:
  - kernel/bpf/bpf_lru_list.c:bpf_common_lru_pop_free
  - kernel/bpf/bpf_lru_list.c:bpf_common_lru_pop_free
```
**Symbols:**

```
ffffffff811fbe40-ffffffff811fbe96: __bpf_lru_node_move_in (STB_LOCAL)
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
