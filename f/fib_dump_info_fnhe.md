# Function: <code>fib_dump_info_fnhe</code>

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
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int fib_dump_info_fnhe(struct sk_buff *skb, struct netlink_callback *cb, u32 table_id, struct fib_info *fi, int *fa_index, int fa_start, unsigned int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/route.c (ffffffff81976700)
Location: net/ipv4/route.c:2906
Inline: False
Direct callers:
  - net/ipv4/fib_trie.c:fib_table_dump
```
**Symbols:**

```
ffffffff81976700-ffffffff81976926: fib_dump_info_fnhe (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int fib_dump_info_fnhe(struct sk_buff *skb, struct netlink_callback *cb, u32 table_id, struct fib_info *fi, int *fa_index, int fa_start, unsigned int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/route.c (ffffffff819ad120)
Location: net/ipv4/route.c:2917
Inline: False
Direct callers:
  - net/ipv4/fib_trie.c:fib_table_dump
```
**Symbols:**

```
ffffffff819ad120-ffffffff819ad343: fib_dump_info_fnhe (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int fib_dump_info_fnhe(struct sk_buff *skb, struct netlink_callback *cb, u32 table_id, struct fib_info *fi, int *fa_index, int fa_start, unsigned int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/route.c (ffffffff81a96fb0)
Location: net/ipv4/route.c:3004
Inline: False
```
**Symbols:**

```
ffffffff81a96fb0-ffffffff81a970e3: fib_dump_info_fnhe (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int fib_dump_info_fnhe(struct sk_buff *skb, struct netlink_callback *cb, u32 table_id, struct fib_info *fi, int *fa_index, int fa_start, unsigned int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/route.c (ffffffff81aa10a0)
Location: net/ipv4/route.c:2986
Inline: False
```
**Symbols:**

```
ffffffff81aa10a0-ffffffff81aa11dd: fib_dump_info_fnhe (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int fib_dump_info_fnhe(struct sk_buff *skb, struct netlink_callback *cb, u32 table_id, struct fib_info *fi, int *fa_index, int fa_start, unsigned int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/route.c (ffffffff81a8c020)
Location: net/ipv4/route.c:2987
Inline: False
```
**Symbols:**

```
ffffffff81a8c020-ffffffff81a8c238: fib_dump_info_fnhe (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int fib_dump_info_fnhe(struct sk_buff *skb, struct netlink_callback *cb, u32 table_id, struct fib_info *fi, int *fa_index, int fa_start, unsigned int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ipv4/route.c (0)
Location: net/ipv4/route.c:3105
Inline: False
Direct callers:
  - net/ipv4/fib_trie.c:fn_trie_dump_leaf
```
**Symbols:**

```
ffffffff81d39fd0-ffffffff81d3a045: fib_dump_info_fnhe.cold (STB_LOCAL)
ffffffff81b46fb0-ffffffff81b47206: fib_dump_info_fnhe (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int fib_dump_info_fnhe(struct sk_buff *skb, struct netlink_callback *cb, u32 table_id, struct fib_info *fi, int *fa_index, int fa_start, unsigned int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ipv4/route.c (0)
Location: net/ipv4/route.c:3129
Inline: False
Direct callers:
  - net/ipv4/fib_trie.c:fn_trie_dump_leaf
```
**Symbols:**

```
ffffffff81f06726-ffffffff81f067da: fib_dump_info_fnhe.cold (STB_LOCAL)
ffffffff81cd4080-ffffffff81cd4312: fib_dump_info_fnhe (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
int fib_dump_info_fnhe(struct sk_buff *skb, struct netlink_callback *cb, u32 table_id, struct fib_info *fi, int *fa_index, int fa_start, unsigned int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ipv4/route.c (0)
Location: net/ipv4/route.c:3120
Inline: False
Direct callers:
  - net/ipv4/fib_trie.c:fn_trie_dump_leaf
```
**Symbols:**

```
ffffffff820ae24d-ffffffff820ae301: fib_dump_info_fnhe.cold (STB_LOCAL)
ffffffff81e942e0-ffffffff81e94572: fib_dump_info_fnhe (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
int fib_dump_info_fnhe(struct sk_buff *skb, struct netlink_callback *cb, u32 table_id, struct fib_info *fi, int *fa_index, int fa_start, unsigned int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ipv4/route.c (0)
Location: net/ipv4/route.c:3116
Inline: False
Direct callers:
  - net/ipv4/fib_trie.c:fn_trie_dump_leaf
```
**Symbols:**

```
ffffffff8212f74b-ffffffff8212f7ff: fib_dump_info_fnhe.cold (STB_LOCAL)
ffffffff81ef2ab0-ffffffff81ef2d42: fib_dump_info_fnhe (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
int fib_dump_info_fnhe(struct sk_buff *skb, struct netlink_callback *cb, u32 table_id, struct fib_info *fi, int *fa_index, int fa_start, unsigned int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ipv4/route.c (0)
Location: net/ipv4/route.c:3071
Inline: False
Direct callers:
  - net/ipv4/fib_trie.c:fn_trie_dump_leaf
```
**Symbols:**

```
ffffffff82211508-ffffffff822115bc: fib_dump_info_fnhe.cold (STB_LOCAL)
ffffffff81fb6a40-ffffffff81fb6cd2: fib_dump_info_fnhe (STB_GLOBAL)
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
int fib_dump_info_fnhe(struct sk_buff *skb, struct netlink_callback *cb, u32 table_id, struct fib_info *fi, int *fa_index, int fa_start, unsigned int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/route.c (ffff800010c5d180)
Location: net/ipv4/route.c:2917
Inline: False
Direct callers:
  - net/ipv4/fib_trie.c:fib_table_dump
```
**Symbols:**

```
ffff800010c5d180-ffff800010c5d398: fib_dump_info_fnhe (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int fib_dump_info_fnhe(struct sk_buff *skb, struct netlink_callback *cb, u32 table_id, struct fib_info *fi, int *fa_index, int fa_start, unsigned int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/route.c (c0d6c8f8)
Location: net/ipv4/route.c:2917
Inline: False
Direct callers:
  - net/ipv4/fib_trie.c:fib_table_dump
```
**Symbols:**

```
c0d6c8f8-c0d6cb50: fib_dump_info_fnhe (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int fib_dump_info_fnhe(struct sk_buff *skb, struct netlink_callback *cb, u32 table_id, struct fib_info *fi, int *fa_index, int fa_start, unsigned int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/route.c (c000000000d5f8d0)
Location: net/ipv4/route.c:2917
Inline: False
Direct callers:
  - net/ipv4/fib_trie.c:fib_table_dump
```
**Symbols:**

```
c000000000d5f8d0-c000000000d5fbdc: fib_dump_info_fnhe (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int fib_dump_info_fnhe(struct sk_buff *skb, struct netlink_callback *cb, u32 table_id, struct fib_info *fi, int *fa_index, int fa_start, unsigned int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/route.c (ffffffe0007c5ece)
Location: net/ipv4/route.c:2917
Inline: False
Direct callers:
  - net/ipv4/fib_trie.c:fib_table_dump
```
**Symbols:**

```
ffffffe0007c5ece-ffffffe0007c605e: fib_dump_info_fnhe (STB_GLOBAL)
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
int fib_dump_info_fnhe(struct sk_buff *skb, struct netlink_callback *cb, u32 table_id, struct fib_info *fi, int *fa_index, int fa_start, unsigned int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/route.c (ffffffff8194cf90)
Location: net/ipv4/route.c:2917
Inline: False
Direct callers:
  - net/ipv4/fib_trie.c:fib_table_dump
```
**Symbols:**

```
ffffffff8194cf90-ffffffff8194d1b3: fib_dump_info_fnhe (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int fib_dump_info_fnhe(struct sk_buff *skb, struct netlink_callback *cb, u32 table_id, struct fib_info *fi, int *fa_index, int fa_start, unsigned int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/route.c (ffffffff81906a80)
Location: net/ipv4/route.c:2917
Inline: False
Direct callers:
  - net/ipv4/fib_trie.c:fib_table_dump
```
**Symbols:**

```
ffffffff81906a80-ffffffff81906ca3: fib_dump_info_fnhe (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int fib_dump_info_fnhe(struct sk_buff *skb, struct netlink_callback *cb, u32 table_id, struct fib_info *fi, int *fa_index, int fa_start, unsigned int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/route.c (ffffffff819b7760)
Location: net/ipv4/route.c:2917
Inline: False
Direct callers:
  - net/ipv4/fib_trie.c:fib_table_dump
```
**Symbols:**

```
ffffffff819b7760-ffffffff819b7983: fib_dump_info_fnhe (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int fib_dump_info_fnhe(struct sk_buff *skb, struct netlink_callback *cb, u32 table_id, struct fib_info *fi, int *fa_index, int fa_start, unsigned int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/route.c (ffffffff819c0ff0)
Location: net/ipv4/route.c:2917
Inline: False
Direct callers:
  - net/ipv4/fib_trie.c:fib_table_dump
```
**Symbols:**

```
ffffffff819c0ff0-ffffffff819c1200: fib_dump_info_fnhe (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
