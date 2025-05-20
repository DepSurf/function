# Function: <code>fn_trie_dump_leaf</code>

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
In net/ipv4/fib_trie.c (ffffffff817a1173)
Location: net/ipv4/fib_trie.c:1897
Inline: True
Inline callers:
  - net/ipv4/fib_trie.c:fib_table_dump
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
In net/ipv4/fib_trie.c (ffffffff8180ee23)
Location: net/ipv4/fib_trie.c:1896
Inline: True
Inline callers:
  - net/ipv4/fib_trie.c:fib_table_dump
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
In net/ipv4/fib_trie.c (ffffffff81840353)
Location: net/ipv4/fib_trie.c:2068
Inline: True
Inline callers:
  - net/ipv4/fib_trie.c:fib_table_dump
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
In net/ipv4/fib_trie.c (ffffffff81861aac)
Location: net/ipv4/fib_trie.c:1985
Inline: True
Inline callers:
  - net/ipv4/fib_trie.c:fib_table_dump
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
In net/ipv4/fib_trie.c (ffffffff818e1bbc)
Location: net/ipv4/fib_trie.c:1981
Inline: True
Inline callers:
  - net/ipv4/fib_trie.c:fib_table_dump
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
In net/ipv4/fib_trie.c (ffffffff819386ba)
Location: net/ipv4/fib_trie.c:2005
Inline: True
Inline callers:
  - net/ipv4/fib_trie.c:fib_table_dump
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
In net/ipv4/fib_trie.c (ffffffff819680b3)
Location: net/ipv4/fib_trie.c:2014
Inline: True
Inline callers:
  - net/ipv4/fib_trie.c:fib_table_dump
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
In net/ipv4/fib_trie.c (ffffffff819ce41f)
Location: net/ipv4/fib_trie.c:2087
Inline: True
Inline callers:
  - net/ipv4/fib_trie.c:fib_table_dump
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
In net/ipv4/fib_trie.c (ffffffff81a04fbf)
Location: net/ipv4/fib_trie.c:2087
Inline: True
Inline callers:
  - net/ipv4/fib_trie.c:fib_table_dump
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
In net/ipv4/fib_trie.c (ffffffff81af17e0)
Location: net/ipv4/fib_trie.c:2220
Inline: True
Direct callers:
  - net/ipv4/fib_trie.c:fib_table_dump
```
**Symbols:**

```
ffffffff81af17e0-ffffffff81af19f1: fn_trie_dump_leaf.isra.0 (STB_LOCAL)
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
In net/ipv4/fib_trie.c (ffffffff81afe860)
Location: net/ipv4/fib_trie.c:2211
Inline: True
Direct callers:
  - net/ipv4/fib_trie.c:fib_table_dump
```
**Symbols:**

```
ffffffff81afe860-ffffffff81afea71: fn_trie_dump_leaf.isra.0 (STB_LOCAL)
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
In net/ipv4/fib_trie.c (ffffffff81ae9e30)
Location: net/ipv4/fib_trie.c:2248
Inline: True
Direct callers:
  - net/ipv4/fib_trie.c:fib_table_dump
```
**Symbols:**

```
ffffffff81ae9e30-ffffffff81aea048: fn_trie_dump_leaf.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int fn_trie_dump_leaf(struct key_vector *l, struct fib_table *tb, struct sk_buff *skb, struct netlink_callback *cb, struct fib_dump_filter *filter);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ipv4/fib_trie.c (0)
Location: net/ipv4/fib_trie.c:2252
Inline: False
Direct callers:
  - net/ipv4/fib_trie.c:fib_table_dump
```
**Symbols:**

```
ffffffff81ba9630-ffffffff81ba98bd: fn_trie_dump_leaf (STB_LOCAL)
ffffffff81d3d256-ffffffff81d3d358: fn_trie_dump_leaf.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int fn_trie_dump_leaf(struct key_vector *l, struct fib_table *tb, struct sk_buff *skb, struct netlink_callback *cb, struct fib_dump_filter *filter);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ipv4/fib_trie.c (0)
Location: net/ipv4/fib_trie.c:2261
Inline: False
Direct callers:
  - net/ipv4/fib_trie.c:fib_table_dump
```
**Symbols:**

```
ffffffff81d3c0a0-ffffffff81d3c34a: fn_trie_dump_leaf (STB_LOCAL)
ffffffff81f09a7d-ffffffff81f09b4f: fn_trie_dump_leaf.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
int fn_trie_dump_leaf(struct key_vector *l, struct fib_table *tb, struct sk_buff *skb, struct netlink_callback *cb, struct fib_dump_filter *filter);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ipv4/fib_trie.c (0)
Location: net/ipv4/fib_trie.c:2263
Inline: False
Direct callers:
  - net/ipv4/fib_trie.c:fib_table_dump
```
**Symbols:**

```
ffffffff81f04b00-ffffffff81f04daa: fn_trie_dump_leaf (STB_LOCAL)
ffffffff820b1358-ffffffff820b142a: fn_trie_dump_leaf.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
int fn_trie_dump_leaf(struct key_vector *l, struct fib_table *tb, struct sk_buff *skb, struct netlink_callback *cb, struct fib_dump_filter *filter);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ipv4/fib_trie.c (0)
Location: net/ipv4/fib_trie.c:2263
Inline: False
Direct callers:
  - net/ipv4/fib_trie.c:fib_table_dump
```
**Symbols:**

```
ffffffff81f64550-ffffffff81f647fa: fn_trie_dump_leaf (STB_LOCAL)
ffffffff821325d8-ffffffff821326aa: fn_trie_dump_leaf.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
int fn_trie_dump_leaf(struct key_vector *l, struct fib_table *tb, struct sk_buff *skb, struct netlink_callback *cb, struct fib_dump_filter *filter);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ipv4/fib_trie.c (0)
Location: net/ipv4/fib_trie.c:2269
Inline: False
Direct callers:
  - net/ipv4/fib_trie.c:fib_table_dump
```
**Symbols:**

```
ffffffff8202ab20-ffffffff8202adca: fn_trie_dump_leaf (STB_LOCAL)
ffffffff82213f96-ffffffff82214068: fn_trie_dump_leaf.cold (STB_LOCAL)
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
In net/ipv4/fib_trie.c (ffff800010cbdb7c)
Location: net/ipv4/fib_trie.c:2087
Inline: True
Inline callers:
  - net/ipv4/fib_trie.c:fib_table_dump
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
In net/ipv4/fib_trie.c (c0dc9524)
Location: net/ipv4/fib_trie.c:2087
Inline: True
Inline callers:
  - net/ipv4/fib_trie.c:fib_table_dump
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
In net/ipv4/fib_trie.c (c000000000dd7ef4)
Location: net/ipv4/fib_trie.c:2087
Inline: True
Inline callers:
  - net/ipv4/fib_trie.c:fib_table_dump
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
In net/ipv4/fib_trie.c (ffffffe000813db0)
Location: net/ipv4/fib_trie.c:2087
Inline: True
Inline callers:
  - net/ipv4/fib_trie.c:fib_table_dump
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
In net/ipv4/fib_trie.c (ffffffff819a4d5f)
Location: net/ipv4/fib_trie.c:2087
Inline: True
Inline callers:
  - net/ipv4/fib_trie.c:fib_table_dump
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
In net/ipv4/fib_trie.c (ffffffff8195e81f)
Location: net/ipv4/fib_trie.c:2087
Inline: True
Inline callers:
  - net/ipv4/fib_trie.c:fib_table_dump
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
In net/ipv4/fib_trie.c (ffffffff81a0f5ff)
Location: net/ipv4/fib_trie.c:2087
Inline: True
Inline callers:
  - net/ipv4/fib_trie.c:fib_table_dump
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
In net/ipv4/fib_trie.c (ffffffff81a19e4f)
Location: net/ipv4/fib_trie.c:2087
Inline: True
Inline callers:
  - net/ipv4/fib_trie.c:fib_table_dump
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
