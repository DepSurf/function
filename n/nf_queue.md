# Function: <code>nf_queue</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int nf_queue(struct sk_buff *skb, struct nf_hook_ops *elem, struct nf_hook_state *state, unsigned int queuenum);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/netfilter/nf_queue.c (ffffffff817527d0)
Location: net/netfilter/nf_queue.c:116
Inline: False
Direct callers:
  - net/netfilter/core.c:nf_hook_slow
  - net/netfilter/nf_queue.c:nf_reinject
```
**Symbols:**

```
ffffffff817527d0-ffffffff81752952: nf_queue (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int nf_queue(struct sk_buff *skb, struct nf_hook_ops *elem, struct nf_hook_state *state, unsigned int queuenum);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/netfilter/nf_queue.c (ffffffff817be8f0)
Location: net/netfilter/nf_queue.c:114
Inline: False
Direct callers:
  - net/netfilter/core.c:nf_hook_slow
  - net/netfilter/nf_queue.c:nf_reinject
```
**Symbols:**

```
ffffffff817be8f0-ffffffff817bea6b: nf_queue (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int nf_queue(struct sk_buff *skb, struct nf_hook_state *state, struct nf_hook_entry **entryp, unsigned int verdict);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/netfilter/nf_queue.c (ffffffff817ee1c0)
Location: net/netfilter/nf_queue.c:161
Inline: False
Direct callers:
  - net/netfilter/core.c:nf_hook_slow
  - net/netfilter/nf_queue.c:nf_reinject
```
**Symbols:**

```
ffffffff817ee1c0-ffffffff817ee34e: nf_queue (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int nf_queue(struct sk_buff *skb, struct nf_hook_state *state, struct nf_hook_entry **entryp, unsigned int verdict);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/netfilter/nf_queue.c (ffffffff8180e2d0)
Location: net/netfilter/nf_queue.c:164
Inline: False
Direct callers:
  - net/netfilter/core.c:nf_hook_slow
  - net/netfilter/nf_queue.c:nf_reinject
```
**Symbols:**

```
ffffffff8180e2d0-ffffffff8180e454: nf_queue (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int nf_queue(struct sk_buff *skb, struct nf_hook_state *state, const struct nf_hook_entries *entries, unsigned int index, unsigned int verdict);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/netfilter/nf_queue.c (ffffffff8188d7d0)
Location: net/netfilter/nf_queue.c:166
Inline: False
Direct callers:
  - net/netfilter/core.c:nf_hook_slow
  - net/netfilter/nf_queue.c:nf_reinject
```
**Symbols:**

```
ffffffff8188d7d0-ffffffff8188d996: nf_queue (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int nf_queue(struct sk_buff *skb, struct nf_hook_state *state, const struct nf_hook_entries *entries, unsigned int index, unsigned int verdict);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/netfilter/nf_queue.c (ffffffff818e13d0)
Location: net/netfilter/nf_queue.c:211
Inline: False
Direct callers:
  - net/netfilter/core.c:nf_hook_slow
  - net/netfilter/nf_queue.c:nf_reinject
```
**Symbols:**

```
ffffffff818e13d0-ffffffff818e165e: nf_queue (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int nf_queue(struct sk_buff *skb, struct nf_hook_state *state, const struct nf_hook_entries *entries, unsigned int index, unsigned int verdict);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/netfilter/nf_queue.c (ffffffff8190df80)
Location: net/netfilter/nf_queue.c:227
Inline: False
Direct callers:
  - net/netfilter/core.c:nf_hook_slow
  - net/netfilter/nf_queue.c:nf_reinject
```
**Symbols:**

```
ffffffff8190df80-ffffffff8190e1e1: nf_queue (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int nf_queue(struct sk_buff *skb, struct nf_hook_state *state, unsigned int index, unsigned int verdict);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/netfilter/nf_queue.c (ffffffff8196faa0)
Location: net/netfilter/nf_queue.c:230
Inline: False
Direct callers:
  - net/netfilter/core.c:nf_hook_slow
  - net/netfilter/nf_queue.c:nf_reinject
```
**Symbols:**

```
ffffffff8196faa0-ffffffff8196fd3f: nf_queue (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int nf_queue(struct sk_buff *skb, struct nf_hook_state *state, unsigned int index, unsigned int verdict);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/netfilter/nf_queue.c (ffffffff819a64d0)
Location: net/netfilter/nf_queue.c:230
Inline: False
Direct callers:
  - net/netfilter/core.c:nf_hook_slow
  - net/netfilter/nf_queue.c:nf_reinject
```
**Symbols:**

```
ffffffff819a64d0-ffffffff819a673d: nf_queue (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
int nf_queue(struct sk_buff *skb, struct nf_hook_state *state, unsigned int index, unsigned int verdict);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/netfilter/nf_queue.c (ffffffff81a8fc59)
Location: net/netfilter/nf_queue.c:220
Inline: True
Inline callers:
  - net/netfilter/nf_queue.c:nf_reinject
Direct callers:
  - net/netfilter/core.c:nf_hook_slow
```
**Symbols:**

```
ffffffff81a8fa40-ffffffff81a8fa8b: nf_queue (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
int nf_queue(struct sk_buff *skb, struct nf_hook_state *state, unsigned int index, unsigned int verdict);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/netfilter/nf_queue.c (ffffffff81a99c48)
Location: net/netfilter/nf_queue.c:220
Inline: True
Inline callers:
  - net/netfilter/nf_queue.c:nf_reinject
Direct callers:
  - net/netfilter/core.c:nf_hook_slow
```
**Symbols:**

```
ffffffff81a99a30-ffffffff81a99a7b: nf_queue (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
int nf_queue(struct sk_buff *skb, struct nf_hook_state *state, unsigned int index, unsigned int verdict);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/netfilter/nf_queue.c (ffffffff81a84f58)
Location: net/netfilter/nf_queue.c:220
Inline: True
Inline callers:
  - net/netfilter/nf_queue.c:nf_reinject
Direct callers:
  - net/netfilter/core.c:nf_hook_slow
```
**Symbols:**

```
ffffffff81a84d40-ffffffff81a84d8b: nf_queue (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
int nf_queue(struct sk_buff *skb, struct nf_hook_state *state, unsigned int index, unsigned int verdict);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/netfilter/nf_queue.c (ffffffff81b3f60d)
Location: net/netfilter/nf_queue.c:237
Inline: True
Inline callers:
  - net/netfilter/nf_queue.c:nf_reinject
Direct callers:
  - net/netfilter/core.c:nf_hook_slow
```
**Symbols:**

```
ffffffff81b3f3d0-ffffffff81b3f41b: nf_queue (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
int nf_queue(struct sk_buff *skb, struct nf_hook_state *state, unsigned int index, unsigned int verdict);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/netfilter/nf_queue.c (ffffffff81ccbd0a)
Location: net/netfilter/nf_queue.c:237
Inline: True
Inline callers:
  - net/netfilter/nf_queue.c:nf_reinject
Direct callers:
  - net/netfilter/core.c:nf_hook_slow
```
**Symbols:**

```
ffffffff81ccbb20-ffffffff81ccbb73: nf_queue (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
int nf_queue(struct sk_buff *skb, struct nf_hook_state *state, unsigned int index, unsigned int verdict);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/netfilter/nf_queue.c (ffffffff81e8bb78)
Location: net/netfilter/nf_queue.c:237
Inline: True
Inline callers:
  - net/netfilter/nf_queue.c:nf_reinject
Direct callers:
  - net/netfilter/core.c:nf_hook_slow
```
**Symbols:**

```
ffffffff81e8b980-ffffffff81e8b9d3: nf_queue (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
int nf_queue(struct sk_buff *skb, struct nf_hook_state *state, unsigned int index, unsigned int verdict);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/netfilter/nf_queue.c (ffffffff81ee9bd5)
Location: net/netfilter/nf_queue.c:237
Inline: True
Inline callers:
  - net/netfilter/nf_queue.c:nf_reinject
Direct callers:
  - net/netfilter/core.c:nf_hook_slow
```
**Symbols:**

```
ffffffff81ee99e0-ffffffff81ee9a33: nf_queue (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
int nf_queue(struct sk_buff *skb, struct nf_hook_state *state, unsigned int index, unsigned int verdict);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/netfilter/nf_queue.c (ffffffff81fad985)
Location: net/netfilter/nf_queue.c:235
Inline: True
Inline callers:
  - net/netfilter/nf_queue.c:nf_reinject
Direct callers:
  - net/netfilter/core.c:nf_hook_slow
```
**Symbols:**

```
ffffffff81fad790-ffffffff81fad7e3: nf_queue (STB_GLOBAL)
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
int nf_queue(struct sk_buff *skb, struct nf_hook_state *state, unsigned int index, unsigned int verdict);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/netfilter/nf_queue.c (ffff800010c55d70)
Location: net/netfilter/nf_queue.c:230
Inline: False
Direct callers:
  - net/netfilter/core.c:nf_hook_slow
  - net/netfilter/nf_queue.c:nf_reinject
```
**Symbols:**

```
ffff800010c55d70-ffff800010c55fa0: nf_queue (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int nf_queue(struct sk_buff *skb, struct nf_hook_state *state, unsigned int index, unsigned int verdict);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/netfilter/nf_queue.c (c0d65774)
Location: net/netfilter/nf_queue.c:230
Inline: False
Direct callers:
  - net/netfilter/core.c:nf_hook_slow
  - net/netfilter/nf_queue.c:nf_reinject
```
**Symbols:**

```
c0d65774-c0d659b0: nf_queue (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int nf_queue(struct sk_buff *skb, struct nf_hook_state *state, unsigned int index, unsigned int verdict);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/netfilter/nf_queue.c (c000000000d564a0)
Location: net/netfilter/nf_queue.c:230
Inline: False
Direct callers:
  - net/netfilter/core.c:nf_hook_slow
  - net/netfilter/nf_queue.c:nf_reinject
```
**Symbols:**

```
c000000000d564a0-c000000000d567e0: nf_queue (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int nf_queue(struct sk_buff *skb, struct nf_hook_state *state, unsigned int index, unsigned int verdict);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/netfilter/nf_queue.c (ffffffe0007c00ae)
Location: net/netfilter/nf_queue.c:230
Inline: False
Direct callers:
  - net/netfilter/core.c:nf_hook_slow
  - net/netfilter/nf_queue.c:nf_reinject
```
**Symbols:**

```
ffffffe0007c00ae-ffffffe0007c02d0: nf_queue (STB_GLOBAL)
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
int nf_queue(struct sk_buff *skb, struct nf_hook_state *state, unsigned int index, unsigned int verdict);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/netfilter/nf_queue.c (ffffffff81946340)
Location: net/netfilter/nf_queue.c:230
Inline: False
Direct callers:
  - net/netfilter/core.c:nf_hook_slow
  - net/netfilter/nf_queue.c:nf_reinject
```
**Symbols:**

```
ffffffff81946340-ffffffff819465ad: nf_queue (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int nf_queue(struct sk_buff *skb, struct nf_hook_state *state, unsigned int index, unsigned int verdict);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/netfilter/nf_queue.c (ffffffff818ffe30)
Location: net/netfilter/nf_queue.c:230
Inline: False
Direct callers:
  - net/netfilter/core.c:nf_hook_slow
  - net/netfilter/nf_queue.c:nf_reinject
```
**Symbols:**

```
ffffffff818ffe30-ffffffff8190009d: nf_queue (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int nf_queue(struct sk_buff *skb, struct nf_hook_state *state, unsigned int index, unsigned int verdict);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/netfilter/nf_queue.c (ffffffff819974d0)
Location: net/netfilter/nf_queue.c:230
Inline: False
Direct callers:
  - net/netfilter/core.c:nf_hook_slow
  - net/netfilter/nf_queue.c:nf_reinject
```
**Symbols:**

```
ffffffff819974d0-ffffffff8199773d: nf_queue (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int nf_queue(struct sk_buff *skb, struct nf_hook_state *state, unsigned int index, unsigned int verdict);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/netfilter/nf_queue.c (ffffffff819ba1b0)
Location: net/netfilter/nf_queue.c:230
Inline: False
Direct callers:
  - net/netfilter/core.c:nf_hook_slow
  - net/netfilter/nf_queue.c:nf_reinject
```
**Symbols:**

```
ffffffff819ba1b0-ffffffff819ba41d: nf_queue (STB_GLOBAL)
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
<code>struct nf_hook_entry **entryp</code>
</li>
<li>
<b>Param added. </b>
<code>unsigned int verdict</code>
</li>
<li>
<b>Param removed. </b>
<code>struct nf_hook_ops *elem</code>
</li>
<li>
<b>Param removed. </b>
<code>unsigned int queuenum</code>
</li>
<li>
<b>Param reordered. </b>
<code>skb, elem, state, queuenum</code> ➡️ <code>skb, state, entryp, verdict</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>4.10</code> and <code>4.13</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>4.13</code> and <code>4.15</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>const struct nf_hook_entries *entries</code>
</li>
<li>
<b>Param added. </b>
<code>unsigned int index</code>
</li>
<li>
<b>Param removed. </b>
<code>struct nf_hook_entry **entryp</code>
</li>
<li>
<b>Param reordered. </b>
<code>skb, state, entryp, verdict</code> ➡️ <code>skb, state, entries, index, verdict</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>4.15</code> and <code>4.18</code> ✅
</li>
<li>
No changes between <code>4.18</code> and <code>5.0</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>5.0</code> and <code>5.3</code> ⚠️</summary>
<ul>
<li>
<b>Param removed. </b>
<code>const struct nf_hook_entries *entries</code>
</li>
<li>
<b>Param reordered. </b>
<code>skb, state, entries, index, verdict</code> ➡️ <code>skb, state, index, verdict</code>
</li>
</ul>
</details>
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
