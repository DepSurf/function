# Function: <code>fib_insert_node</code>

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
In net/ipv4/fib_trie.c (ffffffff817a035e)
Location: net/ipv4/fib_trie.c:995
Inline: True
Inline callers:
  - net/ipv4/fib_trie.c:fib_insert_alias
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
In net/ipv4/fib_trie.c (ffffffff8180df3e)
Location: net/ipv4/fib_trie.c:993
Inline: True
Inline callers:
  - net/ipv4/fib_trie.c:fib_insert_alias
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
In net/ipv4/fib_trie.c (ffffffff8183f395)
Location: net/ipv4/fib_trie.c:1111
Inline: True
Inline callers:
  - net/ipv4/fib_trie.c:fib_insert_alias
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
In net/ipv4/fib_trie.c (ffffffff81860935)
Location: net/ipv4/fib_trie.c:1016
Inline: True
Inline callers:
  - net/ipv4/fib_trie.c:fib_insert_alias
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
In net/ipv4/fib_trie.c (ffffffff818e09b5)
Location: net/ipv4/fib_trie.c:1017
Inline: True
Inline callers:
  - net/ipv4/fib_trie.c:fib_insert_alias
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
In net/ipv4/fib_trie.c (ffffffff819371c2)
Location: net/ipv4/fib_trie.c:1018
Inline: True
Inline callers:
  - net/ipv4/fib_trie.c:fib_insert_alias
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
In net/ipv4/fib_trie.c (ffffffff81966bb2)
Location: net/ipv4/fib_trie.c:1018
Inline: True
Inline callers:
  - net/ipv4/fib_trie.c:fib_insert_alias
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
In net/ipv4/fib_trie.c (ffffffff819ccc5a)
Location: net/ipv4/fib_trie.c:1014
Inline: True
Inline callers:
  - net/ipv4/fib_trie.c:fib_insert_alias
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
In net/ipv4/fib_trie.c (ffffffff81a037cf)
Location: net/ipv4/fib_trie.c:1014
Inline: True
Inline callers:
  - net/ipv4/fib_trie.c:fib_insert_alias
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int fib_insert_node(struct trie *t, struct key_vector *tp, struct fib_alias *new, t_key key);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/fib_trie.c (ffffffff81af2dd0)
Location: net/ipv4/fib_trie.c:1062
Inline: False
Direct callers:
  - net/ipv4/fib_trie.c:fib_insert_alias
```
**Symbols:**

```
ffffffff81af2dd0-ffffffff81af2f88: fib_insert_node (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int fib_insert_node(struct trie *t, struct key_vector *tp, struct fib_alias *new, t_key key);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/fib_trie.c (ffffffff81affce0)
Location: net/ipv4/fib_trie.c:1062
Inline: False
Direct callers:
  - net/ipv4/fib_trie.c:fib_insert_alias
```
**Symbols:**

```
ffffffff81affce0-ffffffff81affe98: fib_insert_node (STB_LOCAL)
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
In net/ipv4/fib_trie.c (ffffffff81aeb471)
Location: net/ipv4/fib_trie.c:1097
Inline: True
Inline callers:
  - net/ipv4/fib_trie.c:fib_insert_alias
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
In net/ipv4/fib_trie.c (ffffffff81bab7c1)
Location: net/ipv4/fib_trie.c:1101
Inline: True
Inline callers:
  - net/ipv4/fib_trie.c:fib_insert_alias
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
In net/ipv4/fib_trie.c (ffffffff81d3e640)
Location: net/ipv4/fib_trie.c:1109
Inline: True
Inline callers:
  - net/ipv4/fib_trie.c:fib_insert_alias
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
In net/ipv4/fib_trie.c (ffffffff81f07220)
Location: net/ipv4/fib_trie.c:1109
Inline: True
Inline callers:
  - net/ipv4/fib_trie.c:fib_insert_alias
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
In net/ipv4/fib_trie.c (ffffffff81f66ccd)
Location: net/ipv4/fib_trie.c:1109
Inline: True
Inline callers:
  - net/ipv4/fib_trie.c:fib_insert_alias
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
In net/ipv4/fib_trie.c (ffffffff8202d2a0)
Location: net/ipv4/fib_trie.c:1110
Inline: True
Inline callers:
  - net/ipv4/fib_trie.c:fib_insert_alias
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
In net/ipv4/fib_trie.c (ffff800010cbc268)
Location: net/ipv4/fib_trie.c:1014
Inline: True
Inline callers:
  - net/ipv4/fib_trie.c:fib_insert_alias
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
In net/ipv4/fib_trie.c (c0dc7ab0)
Location: net/ipv4/fib_trie.c:1014
Inline: True
Inline callers:
  - net/ipv4/fib_trie.c:fib_insert_alias
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
In net/ipv4/fib_trie.c (c000000000dd5e00)
Location: net/ipv4/fib_trie.c:1014
Inline: True
Inline callers:
  - net/ipv4/fib_trie.c:fib_insert_alias
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
In net/ipv4/fib_trie.c (ffffffe0008126bc)
Location: net/ipv4/fib_trie.c:1014
Inline: True
Inline callers:
  - net/ipv4/fib_trie.c:fib_insert_alias
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
In net/ipv4/fib_trie.c (ffffffff819a356f)
Location: net/ipv4/fib_trie.c:1014
Inline: True
Inline callers:
  - net/ipv4/fib_trie.c:fib_insert_alias
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
In net/ipv4/fib_trie.c (ffffffff8195d02f)
Location: net/ipv4/fib_trie.c:1014
Inline: True
Inline callers:
  - net/ipv4/fib_trie.c:fib_insert_alias
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
In net/ipv4/fib_trie.c (ffffffff81a0de0f)
Location: net/ipv4/fib_trie.c:1014
Inline: True
Inline callers:
  - net/ipv4/fib_trie.c:fib_insert_alias
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
In net/ipv4/fib_trie.c (ffffffff81a1861f)
Location: net/ipv4/fib_trie.c:1014
Inline: True
Inline callers:
  - net/ipv4/fib_trie.c:fib_insert_alias
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
</ul>
