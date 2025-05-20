# Function: <code>fib_table_flush</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int fib_table_flush(struct fib_table *tb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/fib_trie.c (ffffffff817a0f40)
Location: net/ipv4/fib_trie.c:1809
Inline: False
Direct callers:
  - net/ipv4/fib_frontend.c:fib_flush
  - net/ipv4/fib_frontend.c:ip_fib_net_exit
  - net/ipv4/fib_frontend.c:ip_fib_net_exit
```
**Symbols:**

```
ffffffff817a0f40-ffffffff817a10e3: fib_table_flush (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int fib_table_flush(struct fib_table *tb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/fib_trie.c (ffffffff8180ebe0)
Location: net/ipv4/fib_trie.c:1808
Inline: False
Direct callers:
  - net/ipv4/fib_frontend.c:ip_fib_net_exit
  - net/ipv4/fib_frontend.c:ip_fib_net_exit
  - net/ipv4/fib_frontend.c:ip_fib_net_exit
  - net/ipv4/fib_frontend.c:fib_flush
```
**Symbols:**

```
ffffffff8180ebe0-ffffffff8180ed91: fib_table_flush (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int fib_table_flush(struct net *net, struct fib_table *tb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/fib_trie.c (ffffffff818400c0)
Location: net/ipv4/fib_trie.c:1918
Inline: False
Direct callers:
  - net/ipv4/fib_frontend.c:ip_fib_net_exit
  - net/ipv4/fib_frontend.c:ip_fib_net_exit
  - net/ipv4/fib_frontend.c:ip_fib_net_exit
  - net/ipv4/fib_frontend.c:fib_flush
```
**Symbols:**

```
ffffffff818400c0-ffffffff818402cb: fib_table_flush (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int fib_table_flush(struct net *net, struct fib_table *tb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/fib_trie.c (ffffffff81861690)
Location: net/ipv4/fib_trie.c:1837
Inline: False
Direct callers:
  - net/ipv4/fib_frontend.c:ip_fib_net_exit
  - net/ipv4/fib_frontend.c:ip_fib_net_exit
  - net/ipv4/fib_frontend.c:ip_fib_net_exit
  - net/ipv4/fib_frontend.c:fib_flush
```
**Symbols:**

```
ffffffff81861690-ffffffff818618fb: fib_table_flush (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int fib_table_flush(struct net *net, struct fib_table *tb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/fib_trie.c (ffffffff818e17b0)
Location: net/ipv4/fib_trie.c:1835
Inline: False
Direct callers:
  - net/ipv4/fib_frontend.c:ip_fib_net_exit
  - net/ipv4/fib_frontend.c:ip_fib_net_exit
  - net/ipv4/fib_frontend.c:ip_fib_net_exit
  - net/ipv4/fib_frontend.c:fib_flush
```
**Symbols:**

```
ffffffff818e17b0-ffffffff818e1a00: fib_table_flush (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int fib_table_flush(struct net *net, struct fib_table *tb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/fib_trie.c (ffffffff819382e0)
Location: net/ipv4/fib_trie.c:1859
Inline: False
Direct callers:
  - net/ipv4/fib_frontend.c:ip_fib_net_exit
  - net/ipv4/fib_frontend.c:ip_fib_net_exit
  - net/ipv4/fib_frontend.c:ip_fib_net_exit
  - net/ipv4/fib_frontend.c:fib_flush
```
**Symbols:**

```
ffffffff819382e0-ffffffff819384f5: fib_table_flush (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int fib_table_flush(struct net *net, struct fib_table *tb, bool flush_all);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/fib_trie.c (ffffffff81967cd0)
Location: net/ipv4/fib_trie.c:1859
Inline: False
Direct callers:
  - net/ipv4/fib_frontend.c:ip_fib_net_exit
  - net/ipv4/fib_frontend.c:ip_fib_net_exit
  - net/ipv4/fib_frontend.c:ip_fib_net_exit
  - net/ipv4/fib_frontend.c:fib_flush
```
**Symbols:**

```
ffffffff81967cd0-ffffffff81967ee1: fib_table_flush (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int fib_table_flush(struct net *net, struct fib_table *tb, bool flush_all);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/fib_trie.c (ffffffff819cdec0)
Location: net/ipv4/fib_trie.c:1861
Inline: False
Direct callers:
  - net/ipv4/fib_frontend.c:ip_fib_net_exit
  - net/ipv4/fib_frontend.c:ip_fib_net_exit
  - net/ipv4/fib_frontend.c:fib_flush
```
**Symbols:**

```
ffffffff819cdec0-ffffffff819ce0ef: fib_table_flush (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int fib_table_flush(struct net *net, struct fib_table *tb, bool flush_all);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/fib_trie.c (ffffffff81a04a10)
Location: net/ipv4/fib_trie.c:1861
Inline: False
Direct callers:
  - net/ipv4/fib_frontend.c:ip_fib_net_exit
  - net/ipv4/fib_frontend.c:ip_fib_net_exit
  - net/ipv4/fib_frontend.c:fib_flush
```
**Symbols:**

```
ffffffff81a04a10-ffffffff81a04c41: fib_table_flush (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int fib_table_flush(struct net *net, struct fib_table *tb, bool flush_all);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/fib_trie.c (ffffffff81af4450)
Location: net/ipv4/fib_trie.c:1974
Inline: False
Direct callers:
  - net/ipv4/fib_frontend.c:ip_fib_net_exit
  - net/ipv4/fib_frontend.c:ip_fib_net_exit
  - net/ipv4/fib_frontend.c:fib_flush
```
**Symbols:**

```
ffffffff81af4450-ffffffff81af4670: fib_table_flush (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int fib_table_flush(struct net *net, struct fib_table *tb, bool flush_all);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/fib_trie.c (ffffffff81b01250)
Location: net/ipv4/fib_trie.c:1974
Inline: False
Direct callers:
  - net/ipv4/fib_frontend.c:ip_fib_net_exit
  - net/ipv4/fib_frontend.c:ip_fib_net_exit
  - net/ipv4/fib_frontend.c:fib_flush
```
**Symbols:**

```
ffffffff81b01250-ffffffff81b01470: fib_table_flush (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int fib_table_flush(struct net *net, struct fib_table *tb, bool flush_all);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/fib_trie.c (ffffffff81aec910)
Location: net/ipv4/fib_trie.c:2011
Inline: False
Direct callers:
  - net/ipv4/fib_frontend.c:ip_fib_net_exit
  - net/ipv4/fib_frontend.c:ip_fib_net_exit
  - net/ipv4/fib_frontend.c:fib_flush
```
**Symbols:**

```
ffffffff81aec910-ffffffff81aecb33: fib_table_flush (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int fib_table_flush(struct net *net, struct fib_table *tb, bool flush_all);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ipv4/fib_trie.c (0)
Location: net/ipv4/fib_trie.c:2015
Inline: False
Direct callers:
  - net/ipv4/fib_frontend.c:ip_fib_net_exit
  - net/ipv4/fib_frontend.c:ip_fib_net_exit
  - net/ipv4/fib_frontend.c:fib_flush
```
**Symbols:**

```
ffffffff81d3d9d5-ffffffff81d3da1b: fib_table_flush.cold (STB_LOCAL)
ffffffff81bacc60-ffffffff81bacee6: fib_table_flush (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int fib_table_flush(struct net *net, struct fib_table *tb, bool flush_all);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ipv4/fib_trie.c (0)
Location: net/ipv4/fib_trie.c:2024
Inline: False
Direct callers:
  - net/ipv4/fib_frontend.c:ip_fib_net_exit
  - net/ipv4/fib_frontend.c:ip_fib_net_exit
  - net/ipv4/fib_frontend.c:fib_flush
```
**Symbols:**

```
ffffffff81f0a2c8-ffffffff81f0a302: fib_table_flush.cold (STB_LOCAL)
ffffffff81d3fb80-ffffffff81d3fe11: fib_table_flush (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
int fib_table_flush(struct net *net, struct fib_table *tb, bool flush_all);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ipv4/fib_trie.c (0)
Location: net/ipv4/fib_trie.c:2026
Inline: False
Direct callers:
  - net/ipv4/fib_frontend.c:ip_fib_net_exit
  - net/ipv4/fib_frontend.c:ip_fib_net_exit
  - net/ipv4/fib_frontend.c:fib_flush
```
**Symbols:**

```
ffffffff820b1b92-ffffffff820b1bcc: fib_table_flush.cold (STB_LOCAL)
ffffffff81f087b0-ffffffff81f08a41: fib_table_flush (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
int fib_table_flush(struct net *net, struct fib_table *tb, bool flush_all);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ipv4/fib_trie.c (0)
Location: net/ipv4/fib_trie.c:2026
Inline: False
Direct callers:
  - net/ipv4/fib_frontend.c:ip_fib_net_exit
  - net/ipv4/fib_frontend.c:ip_fib_net_exit
  - net/ipv4/fib_frontend.c:fib_flush
```
**Symbols:**

```
ffffffff82132dca-ffffffff82132e04: fib_table_flush.cold (STB_LOCAL)
ffffffff81f682c0-ffffffff81f68551: fib_table_flush (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
int fib_table_flush(struct net *net, struct fib_table *tb, bool flush_all);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ipv4/fib_trie.c (0)
Location: net/ipv4/fib_trie.c:2028
Inline: False
Direct callers:
  - net/ipv4/fib_frontend.c:ip_fib_net_exit
  - net/ipv4/fib_frontend.c:ip_fib_net_exit
  - net/ipv4/fib_frontend.c:fib_flush
```
**Symbols:**

```
ffffffff82214788-ffffffff822147e5: fib_table_flush.cold (STB_LOCAL)
ffffffff8202e8a0-ffffffff8202ebde: fib_table_flush (STB_GLOBAL)
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
int fib_table_flush(struct net *net, struct fib_table *tb, bool flush_all);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/fib_trie.c (ffff800010cbd5f0)
Location: net/ipv4/fib_trie.c:1861
Inline: False
Direct callers:
  - net/ipv4/fib_frontend.c:ip_fib_net_exit
  - net/ipv4/fib_frontend.c:ip_fib_net_exit
  - net/ipv4/fib_frontend.c:fib_flush
```
**Symbols:**

```
ffff800010cbd5f0-ffff800010cbd838: fib_table_flush (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int fib_table_flush(struct net *net, struct fib_table *tb, bool flush_all);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/fib_trie.c (c0dc8f70)
Location: net/ipv4/fib_trie.c:1861
Inline: False
Direct callers:
  - net/ipv4/fib_frontend.c:ip_fib_net_exit
  - net/ipv4/fib_frontend.c:ip_fib_net_exit
  - net/ipv4/fib_frontend.c:fib_flush
```
**Symbols:**

```
c0dc8f70-c0dc91d0: fib_table_flush (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int fib_table_flush(struct net *net, struct fib_table *tb, bool flush_all);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/fib_trie.c (c000000000dd7730)
Location: net/ipv4/fib_trie.c:1861
Inline: False
Direct callers:
  - net/ipv4/fib_frontend.c:ip_fib_net_exit
  - net/ipv4/fib_frontend.c:ip_fib_net_exit
  - net/ipv4/fib_frontend.c:fib_flush
```
**Symbols:**

```
c000000000dd7730-c000000000dd7a5c: fib_table_flush (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int fib_table_flush(struct net *net, struct fib_table *tb, bool flush_all);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/fib_trie.c (ffffffe0008138f2)
Location: net/ipv4/fib_trie.c:1861
Inline: False
Direct callers:
  - net/ipv4/fib_frontend.c:ip_fib_net_exit
  - net/ipv4/fib_frontend.c:ip_fib_net_exit
  - net/ipv4/fib_frontend.c:fib_flush
```
**Symbols:**

```
ffffffe0008138f2-ffffffe000813af0: fib_table_flush (STB_GLOBAL)
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
int fib_table_flush(struct net *net, struct fib_table *tb, bool flush_all);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/fib_trie.c (ffffffff819a47b0)
Location: net/ipv4/fib_trie.c:1861
Inline: False
Direct callers:
  - net/ipv4/fib_frontend.c:ip_fib_net_exit
  - net/ipv4/fib_frontend.c:ip_fib_net_exit
  - net/ipv4/fib_frontend.c:fib_flush
```
**Symbols:**

```
ffffffff819a47b0-ffffffff819a49e1: fib_table_flush (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int fib_table_flush(struct net *net, struct fib_table *tb, bool flush_all);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/fib_trie.c (ffffffff8195e270)
Location: net/ipv4/fib_trie.c:1861
Inline: False
Direct callers:
  - net/ipv4/fib_frontend.c:ip_fib_net_exit
  - net/ipv4/fib_frontend.c:ip_fib_net_exit
  - net/ipv4/fib_frontend.c:fib_flush
```
**Symbols:**

```
ffffffff8195e270-ffffffff8195e4a1: fib_table_flush (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int fib_table_flush(struct net *net, struct fib_table *tb, bool flush_all);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/fib_trie.c (ffffffff81a0f050)
Location: net/ipv4/fib_trie.c:1861
Inline: False
Direct callers:
  - net/ipv4/fib_frontend.c:ip_fib_net_exit
  - net/ipv4/fib_frontend.c:ip_fib_net_exit
  - net/ipv4/fib_frontend.c:fib_flush
```
**Symbols:**

```
ffffffff81a0f050-ffffffff81a0f281: fib_table_flush (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int fib_table_flush(struct net *net, struct fib_table *tb, bool flush_all);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/fib_trie.c (ffffffff81a198a0)
Location: net/ipv4/fib_trie.c:1861
Inline: False
Direct callers:
  - net/ipv4/fib_frontend.c:ip_fib_net_exit
  - net/ipv4/fib_frontend.c:ip_fib_net_exit
  - net/ipv4/fib_frontend.c:fib_flush
```
**Symbols:**

```
ffffffff81a198a0-ffffffff81a19ad1: fib_table_flush (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>4.4</code> and <code>4.8</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>4.8</code> and <code>4.10</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>struct net *net</code>
</li>
<li>
<b>Param reordered. </b>
<code>tb</code> ➡️ <code>net, tb</code>
</li>
</ul>
</details>
</li>
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
<details>
<summary>Changed between <code>4.18</code> and <code>5.0</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>bool flush_all</code>
</li>
</ul>
</details>
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
