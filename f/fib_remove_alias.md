# Function: <code>fib_remove_alias</code>

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
In net/ipv4/fib_trie.c (ffffffff817a0c5e)
Location: net/ipv4/fib_trie.c:1460
Inline: True
Inline callers:
  - net/ipv4/fib_trie.c:fib_table_delete
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
In net/ipv4/fib_trie.c (ffffffff8180e8f7)
Location: net/ipv4/fib_trie.c:1459
Inline: True
Inline callers:
  - net/ipv4/fib_trie.c:fib_table_delete
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
In net/ipv4/fib_trie.c (ffffffff8183fdee)
Location: net/ipv4/fib_trie.c:1569
Inline: True
Inline callers:
  - net/ipv4/fib_trie.c:fib_table_delete
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv4/fib_trie.c (ffffffff81861397)
Location: net/ipv4/fib_trie.c:1491
Inline: True
Inline callers:
  - net/ipv4/fib_trie.c:fib_table_delete
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv4/fib_trie.c (ffffffff818e14b4)
Location: net/ipv4/fib_trie.c:1489
Inline: True
Inline callers:
  - net/ipv4/fib_trie.c:fib_table_delete
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv4/fib_trie.c (ffffffff81937fdd)
Location: net/ipv4/fib_trie.c:1513
Inline: True
Inline callers:
  - net/ipv4/fib_trie.c:fib_table_delete
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv4/fib_trie.c (ffffffff819679cd)
Location: net/ipv4/fib_trie.c:1513
Inline: True
Inline callers:
  - net/ipv4/fib_trie.c:fib_table_delete
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv4/fib_trie.c (ffffffff819cdbce)
Location: net/ipv4/fib_trie.c:1515
Inline: True
Inline callers:
  - net/ipv4/fib_trie.c:fib_table_delete
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv4/fib_trie.c (ffffffff81a0471e)
Location: net/ipv4/fib_trie.c:1515
Inline: True
Inline callers:
  - net/ipv4/fib_trie.c:fib_table_delete
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
void fib_remove_alias(struct trie *t, struct key_vector *tp, struct key_vector *l, struct fib_alias *old);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv4/fib_trie.c (ffffffff81af3070)
Location: net/ipv4/fib_trie.c:1599
Inline: True
Direct callers:
  - net/ipv4/fib_trie.c:fib_table_delete
  - net/ipv4/fib_trie.c:fib_table_insert
```
**Symbols:**

```
ffffffff81af3070-ffffffff81af31bb: fib_remove_alias (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
void fib_remove_alias(struct trie *t, struct key_vector *tp, struct key_vector *l, struct fib_alias *old);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv4/fib_trie.c (ffffffff81afff80)
Location: net/ipv4/fib_trie.c:1599
Inline: True
Direct callers:
  - net/ipv4/fib_trie.c:fib_table_delete
  - net/ipv4/fib_trie.c:fib_table_insert
```
**Symbols:**

```
ffffffff81afff80-ffffffff81b000cb: fib_remove_alias (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
void fib_remove_alias(struct trie *t, struct key_vector *tp, struct key_vector *l, struct fib_alias *old);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv4/fib_trie.c (ffffffff81aeb5f0)
Location: net/ipv4/fib_trie.c:1636
Inline: True
Direct callers:
  - net/ipv4/fib_trie.c:fib_table_delete
  - net/ipv4/fib_trie.c:fib_table_insert
```
**Symbols:**

```
ffffffff81aeb5f0-ffffffff81aeb724: fib_remove_alias (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
void fib_remove_alias(struct trie *t, struct key_vector *tp, struct key_vector *l, struct fib_alias *old);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv4/fib_trie.c (ffffffff81baaf40)
Location: net/ipv4/fib_trie.c:1640
Inline: True
Direct callers:
  - net/ipv4/fib_trie.c:fib_table_delete
  - net/ipv4/fib_trie.c:fib_table_insert
```
**Symbols:**

```
ffffffff81baaf40-ffffffff81bab074: fib_remove_alias (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
void fib_remove_alias(struct trie *t, struct key_vector *tp, struct key_vector *l, struct fib_alias *old);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv4/fib_trie.c (ffffffff81d3dcd0)
Location: net/ipv4/fib_trie.c:1647
Inline: True
Direct callers:
  - net/ipv4/fib_trie.c:fib_table_delete
  - net/ipv4/fib_trie.c:fib_table_insert
```
**Symbols:**

```
ffffffff81d3dcd0-ffffffff81d3de2d: fib_remove_alias (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
void fib_remove_alias(struct trie *t, struct key_vector *tp, struct key_vector *l, struct fib_alias *old);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv4/fib_trie.c (ffffffff81f06fa0)
Location: net/ipv4/fib_trie.c:1649
Inline: True
Direct callers:
  - net/ipv4/fib_trie.c:fib_table_delete
  - net/ipv4/fib_trie.c:fib_table_insert
```
**Symbols:**

```
ffffffff81f06fa0-ffffffff81f070fd: fib_remove_alias (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
void fib_remove_alias(struct trie *t, struct key_vector *tp, struct key_vector *l, struct fib_alias *old);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv4/fib_trie.c (ffffffff81f66a60)
Location: net/ipv4/fib_trie.c:1649
Inline: True
Direct callers:
  - net/ipv4/fib_trie.c:fib_table_delete
  - net/ipv4/fib_trie.c:fib_table_insert
```
**Symbols:**

```
ffffffff81f66a60-ffffffff81f66bbd: fib_remove_alias (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
void fib_remove_alias(struct trie *t, struct key_vector *tp, struct key_vector *l, struct fib_alias *old);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv4/fib_trie.c (ffffffff8202d030)
Location: net/ipv4/fib_trie.c:1651
Inline: True
Direct callers:
  - net/ipv4/fib_trie.c:fib_table_delete
  - net/ipv4/fib_trie.c:fib_table_insert
```
**Symbols:**

```
ffffffff8202d030-ffffffff8202d18d: fib_remove_alias (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv4/fib_trie.c (ffff800010cbd2a0)
Location: net/ipv4/fib_trie.c:1515
Inline: True
Inline callers:
  - net/ipv4/fib_trie.c:fib_table_delete
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv4/fib_trie.c (c0dc8c40)
Location: net/ipv4/fib_trie.c:1515
Inline: True
Inline callers:
  - net/ipv4/fib_trie.c:fib_table_delete
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv4/fib_trie.c (c000000000dd72a4)
Location: net/ipv4/fib_trie.c:1515
Inline: True
Inline callers:
  - net/ipv4/fib_trie.c:fib_table_delete
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv4/fib_trie.c (ffffffe00081365c)
Location: net/ipv4/fib_trie.c:1515
Inline: True
Inline callers:
  - net/ipv4/fib_trie.c:fib_table_delete
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv4/fib_trie.c (ffffffff819a44be)
Location: net/ipv4/fib_trie.c:1515
Inline: True
Inline callers:
  - net/ipv4/fib_trie.c:fib_table_delete
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv4/fib_trie.c (ffffffff8195df7e)
Location: net/ipv4/fib_trie.c:1515
Inline: True
Inline callers:
  - net/ipv4/fib_trie.c:fib_table_delete
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv4/fib_trie.c (ffffffff81a0ed5e)
Location: net/ipv4/fib_trie.c:1515
Inline: True
Inline callers:
  - net/ipv4/fib_trie.c:fib_table_delete
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv4/fib_trie.c (ffffffff81a195ae)
Location: net/ipv4/fib_trie.c:1515
Inline: True
Inline callers:
  - net/ipv4/fib_trie.c:fib_table_delete
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
