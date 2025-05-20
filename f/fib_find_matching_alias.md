# Function: <code>fib_find_matching_alias</code>

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
In <code>4.13</code>: Absent ⚠️
</li>
<li>
In <code>4.15</code>: Absent ⚠️
</li>
<li>
In <code>4.18</code>: Absent ⚠️
</li>
<li>
In <code>5.0</code>: Absent ⚠️
</li>
<li>
In <code>5.3</code>: Absent ⚠️
</li>
<li>
In <code>5.4</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
struct fib_alias *fib_find_matching_alias(struct net *net, const struct fib_rt_info *fri);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/fib_trie.c (ffffffff81af2340)
Location: net/ipv4/fib_trie.c:1011
Inline: False
Direct callers:
  - net/ipv4/fib_trie.c:fib_alias_hw_flags_set
```
**Symbols:**

```
ffffffff81af2340-ffffffff81af23f2: fib_find_matching_alias (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
struct fib_alias *fib_find_matching_alias(struct net *net, const struct fib_rt_info *fri);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/fib_trie.c (ffffffff81aff250)
Location: net/ipv4/fib_trie.c:1011
Inline: False
Direct callers:
  - net/ipv4/fib_trie.c:fib_alias_hw_flags_set
```
**Symbols:**

```
ffffffff81aff250-ffffffff81aff302: fib_find_matching_alias (STB_LOCAL)
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
In net/ipv4/fib_trie.c (ffffffff81aea826)
Location: net/ipv4/fib_trie.c:1011
Inline: True
Inline callers:
  - net/ipv4/fib_trie.c:fib_alias_hw_flags_set
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
In net/ipv4/fib_trie.c (ffffffff81ba9bf9)
Location: net/ipv4/fib_trie.c:1011
Inline: True
Inline callers:
  - net/ipv4/fib_trie.c:fib_alias_hw_flags_set
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
In net/ipv4/fib_trie.c (ffffffff81d3c79c)
Location: net/ipv4/fib_trie.c:1016
Inline: True
Inline callers:
  - net/ipv4/fib_trie.c:fib_alias_hw_flags_set
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
In net/ipv4/fib_trie.c (ffffffff81f0523c)
Location: net/ipv4/fib_trie.c:1016
Inline: True
Inline callers:
  - net/ipv4/fib_trie.c:fib_alias_hw_flags_set
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
In net/ipv4/fib_trie.c (ffffffff81f64c8c)
Location: net/ipv4/fib_trie.c:1016
Inline: True
Inline callers:
  - net/ipv4/fib_trie.c:fib_alias_hw_flags_set
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
In net/ipv4/fib_trie.c (ffffffff8202b25c)
Location: net/ipv4/fib_trie.c:1017
Inline: True
Inline callers:
  - net/ipv4/fib_trie.c:fib_alias_hw_flags_set
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
In <code>arm64</code>: Absent ⚠️
</li>
<li>
In <code>armhf</code>: Absent ⚠️
</li>
<li>
In <code>ppc64el</code>: Absent ⚠️
</li>
<li>
In <code>riscv64</code>: Absent ⚠️
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
In <code>aws</code>: Absent ⚠️
</li>
<li>
In <code>azure</code>: Absent ⚠️
</li>
<li>
In <code>gcp</code>: Absent ⚠️
</li>
<li>
In <code>lowlatency</code>: Absent ⚠️
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>5.8</code> and <code>5.11</code> ✅
</li>
</ul>
