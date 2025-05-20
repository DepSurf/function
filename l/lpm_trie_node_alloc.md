# Function: <code>lpm_trie_node_alloc</code>

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
In <code>4.10</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/bpf/lpm_trie.c (ffffffff8119e530)
Location: kernel/bpf/lpm_trie.c:238
Inline: True
Direct callers:
  - kernel/bpf/lpm_trie.c:trie_update_elem
  - kernel/bpf/lpm_trie.c:trie_update_elem
```
**Symbols:**

```
ffffffff8119e530-ffffffff8119e5b9: lpm_trie_node_alloc.isra.1 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
struct lpm_trie_node *lpm_trie_node_alloc(const struct lpm_trie *trie, const void *value);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/lpm_trie.c (ffffffff811ae330)
Location: kernel/bpf/lpm_trie.c:238
Inline: False
Direct callers:
  - kernel/bpf/lpm_trie.c:trie_update_elem
  - kernel/bpf/lpm_trie.c:trie_update_elem
```
**Symbols:**

```
ffffffff811ae330-ffffffff811ae3bd: lpm_trie_node_alloc (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
struct lpm_trie_node *lpm_trie_node_alloc(const struct lpm_trie *trie, const void *value);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/lpm_trie.c (ffffffff811c5880)
Location: kernel/bpf/lpm_trie.c:238
Inline: False
Direct callers:
  - kernel/bpf/lpm_trie.c:trie_update_elem
  - kernel/bpf/lpm_trie.c:trie_update_elem
```
**Symbols:**

```
ffffffff811c5880-ffffffff811c590d: lpm_trie_node_alloc (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
struct lpm_trie_node *lpm_trie_node_alloc(const struct lpm_trie *trie, const void *value);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/lpm_trie.c (ffffffff811d70e0)
Location: kernel/bpf/lpm_trie.c:279
Inline: False
Direct callers:
  - kernel/bpf/lpm_trie.c:trie_update_elem
  - kernel/bpf/lpm_trie.c:trie_update_elem
```
**Symbols:**

```
ffffffff811d70e0-ffffffff811d716d: lpm_trie_node_alloc (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
struct lpm_trie_node *lpm_trie_node_alloc(const struct lpm_trie *trie, const void *value);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/lpm_trie.c (ffffffff811ebab0)
Location: kernel/bpf/lpm_trie.c:276
Inline: False
Direct callers:
  - kernel/bpf/lpm_trie.c:trie_update_elem
  - kernel/bpf/lpm_trie.c:trie_update_elem
```
**Symbols:**

```
ffffffff811ebab0-ffffffff811ebb3d: lpm_trie_node_alloc (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
struct lpm_trie_node *lpm_trie_node_alloc(const struct lpm_trie *trie, const void *value);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/lpm_trie.c (ffffffff811f8210)
Location: kernel/bpf/lpm_trie.c:276
Inline: False
Direct callers:
  - kernel/bpf/lpm_trie.c:trie_update_elem
  - kernel/bpf/lpm_trie.c:trie_update_elem
```
**Symbols:**

```
ffffffff811f8210-ffffffff811f829d: lpm_trie_node_alloc (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
struct lpm_trie_node *lpm_trie_node_alloc(const struct lpm_trie *trie, const void *value);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/lpm_trie.c (ffffffff8121bfb0)
Location: kernel/bpf/lpm_trie.c:276
Inline: False
Direct callers:
  - kernel/bpf/lpm_trie.c:trie_update_elem
  - kernel/bpf/lpm_trie.c:trie_update_elem
```
**Symbols:**

```
ffffffff8121bfb0-ffffffff8121c049: lpm_trie_node_alloc (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
struct lpm_trie_node *lpm_trie_node_alloc(const struct lpm_trie *trie, const void *value);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/bpf/lpm_trie.c (ffffffff8121f7bb)
Location: kernel/bpf/lpm_trie.c:276
Inline: True
Inline callers:
  - kernel/bpf/lpm_trie.c:trie_update_elem
Direct callers:
  - kernel/bpf/lpm_trie.c:trie_update_elem
```
**Symbols:**

```
ffffffff8121ef80-ffffffff8121f011: lpm_trie_node_alloc (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
struct lpm_trie_node *lpm_trie_node_alloc(const struct lpm_trie *trie, const void *value);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/bpf/lpm_trie.c (ffffffff81223239)
Location: kernel/bpf/lpm_trie.c:276
Inline: True
Inline callers:
  - kernel/bpf/lpm_trie.c:trie_update_elem
Direct callers:
  - kernel/bpf/lpm_trie.c:trie_update_elem
```
**Symbols:**

```
ffffffff81222a10-ffffffff81222aa1: lpm_trie_node_alloc (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
struct lpm_trie_node *lpm_trie_node_alloc(const struct lpm_trie *trie, const void *value);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/bpf/lpm_trie.c (ffffffff8125afea)
Location: kernel/bpf/lpm_trie.c:278
Inline: True
Inline callers:
  - kernel/bpf/lpm_trie.c:trie_update_elem
Direct callers:
  - kernel/bpf/lpm_trie.c:trie_update_elem
```
**Symbols:**

```
ffffffff8125a7c0-ffffffff8125a851: lpm_trie_node_alloc (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
struct lpm_trie_node *lpm_trie_node_alloc(const struct lpm_trie *trie, const void *value);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/bpf/lpm_trie.c (ffffffff812a41d3)
Location: kernel/bpf/lpm_trie.c:279
Inline: True
Inline callers:
  - kernel/bpf/lpm_trie.c:trie_update_elem
Direct callers:
  - kernel/bpf/lpm_trie.c:trie_update_elem
```
**Symbols:**

```
ffffffff812a38d0-ffffffff812a3977: lpm_trie_node_alloc (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
struct lpm_trie_node *lpm_trie_node_alloc(const struct lpm_trie *trie, const void *value);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/bpf/lpm_trie.c (ffffffff81301e13)
Location: kernel/bpf/lpm_trie.c:279
Inline: True
Inline callers:
  - kernel/bpf/lpm_trie.c:trie_update_elem
Direct callers:
  - kernel/bpf/lpm_trie.c:trie_update_elem
```
**Symbols:**

```
ffffffff813014b0-ffffffff81301557: lpm_trie_node_alloc (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
struct lpm_trie_node *lpm_trie_node_alloc(const struct lpm_trie *trie, const void *value);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/bpf/lpm_trie.c (ffffffff813309c3)
Location: kernel/bpf/lpm_trie.c:279
Inline: True
Inline callers:
  - kernel/bpf/lpm_trie.c:trie_update_elem
Direct callers:
  - kernel/bpf/lpm_trie.c:trie_update_elem
```
**Symbols:**

```
ffffffff81330040-ffffffff813300e2: lpm_trie_node_alloc (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
struct lpm_trie_node *lpm_trie_node_alloc(const struct lpm_trie *trie, const void *value);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/bpf/lpm_trie.c (ffffffff81354f23)
Location: kernel/bpf/lpm_trie.c:282
Inline: True
Inline callers:
  - kernel/bpf/lpm_trie.c:trie_update_elem
Direct callers:
  - kernel/bpf/lpm_trie.c:trie_update_elem
```
**Symbols:**

```
ffffffff81354560-ffffffff81354602: lpm_trie_node_alloc (STB_LOCAL)
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
struct lpm_trie_node *lpm_trie_node_alloc(const struct lpm_trie *trie, const void *value);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/lpm_trie.c (ffff80001027d4e8)
Location: kernel/bpf/lpm_trie.c:276
Inline: False
Direct callers:
  - kernel/bpf/lpm_trie.c:trie_update_elem
  - kernel/bpf/lpm_trie.c:trie_update_elem
```
**Symbols:**

```
ffff80001027d4e8-ffff80001027d584: lpm_trie_node_alloc (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
struct lpm_trie_node *lpm_trie_node_alloc(const struct lpm_trie *trie, const void *value);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/lpm_trie.c (c04af1e4)
Location: kernel/bpf/lpm_trie.c:276
Inline: False
Direct callers:
  - kernel/bpf/lpm_trie.c:trie_update_elem
  - kernel/bpf/lpm_trie.c:trie_update_elem
```
**Symbols:**

```
c04af1e4-c04af268: lpm_trie_node_alloc (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
struct lpm_trie_node *lpm_trie_node_alloc(const struct lpm_trie *trie, const void *value);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/lpm_trie.c (c000000000327530)
Location: kernel/bpf/lpm_trie.c:276
Inline: False
Direct callers:
  - kernel/bpf/lpm_trie.c:trie_update_elem
  - kernel/bpf/lpm_trie.c:trie_update_elem
```
**Symbols:**

```
c000000000327530-c00000000032760c: lpm_trie_node_alloc (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
struct lpm_trie_node *lpm_trie_node_alloc(const struct lpm_trie *trie, const void *value);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/lpm_trie.c (ffffffe0001b4ce2)
Location: kernel/bpf/lpm_trie.c:276
Inline: False
Direct callers:
  - kernel/bpf/lpm_trie.c:trie_update_elem
  - kernel/bpf/lpm_trie.c:trie_update_elem
```
**Symbols:**

```
ffffffe0001b4ce2-ffffffe0001b4d74: lpm_trie_node_alloc (STB_LOCAL)
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
struct lpm_trie_node *lpm_trie_node_alloc(const struct lpm_trie *trie, const void *value);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/lpm_trie.c (ffffffff811f0830)
Location: kernel/bpf/lpm_trie.c:276
Inline: False
Direct callers:
  - kernel/bpf/lpm_trie.c:trie_update_elem
  - kernel/bpf/lpm_trie.c:trie_update_elem
```
**Symbols:**

```
ffffffff811f0830-ffffffff811f08bd: lpm_trie_node_alloc (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
struct lpm_trie_node *lpm_trie_node_alloc(const struct lpm_trie *trie, const void *value);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/lpm_trie.c (ffffffff811e3580)
Location: kernel/bpf/lpm_trie.c:276
Inline: False
Direct callers:
  - kernel/bpf/lpm_trie.c:trie_update_elem
  - kernel/bpf/lpm_trie.c:trie_update_elem
```
**Symbols:**

```
ffffffff811e3580-ffffffff811e360d: lpm_trie_node_alloc (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
struct lpm_trie_node *lpm_trie_node_alloc(const struct lpm_trie *trie, const void *value);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/lpm_trie.c (ffffffff811ee600)
Location: kernel/bpf/lpm_trie.c:276
Inline: False
Direct callers:
  - kernel/bpf/lpm_trie.c:trie_update_elem
  - kernel/bpf/lpm_trie.c:trie_update_elem
```
**Symbols:**

```
ffffffff811ee600-ffffffff811ee68d: lpm_trie_node_alloc (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
struct lpm_trie_node *lpm_trie_node_alloc(const struct lpm_trie *trie, const void *value);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/lpm_trie.c (ffffffff811fcad0)
Location: kernel/bpf/lpm_trie.c:276
Inline: False
Direct callers:
  - kernel/bpf/lpm_trie.c:trie_update_elem
  - kernel/bpf/lpm_trie.c:trie_update_elem
```
**Symbols:**

```
ffffffff811fcad0-ffffffff811fcb5d: lpm_trie_node_alloc (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
