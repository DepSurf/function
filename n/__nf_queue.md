# Function: <code>__nf_queue</code>

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
<summary>In <code>4.10</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/netfilter/nf_queue.c (ffffffff817ee1e6)
Location: net/netfilter/nf_queue.c:110
Inline: True
Inline callers:
  - net/netfilter/nf_queue.c:nf_queue
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
In net/netfilter/nf_queue.c (ffffffff8180e2f7)
Location: net/netfilter/nf_queue.c:113
Inline: True
Inline callers:
  - net/netfilter/nf_queue.c:nf_queue
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
In net/netfilter/nf_queue.c (ffffffff8188d7e9)
Location: net/netfilter/nf_queue.c:114
Inline: True
Inline callers:
  - net/netfilter/nf_queue.c:nf_queue
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
In net/netfilter/nf_queue.c (ffffffff818e13d5)
Location: net/netfilter/nf_queue.c:142
Inline: True
Inline callers:
  - net/netfilter/nf_queue.c:nf_queue
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
In net/netfilter/nf_queue.c (ffffffff8190df85)
Location: net/netfilter/nf_queue.c:158
Inline: True
Inline callers:
  - net/netfilter/nf_queue.c:nf_queue
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
In net/netfilter/nf_queue.c (ffffffff8196faa5)
Location: net/netfilter/nf_queue.c:158
Inline: True
Inline callers:
  - net/netfilter/nf_queue.c:nf_queue
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
In net/netfilter/nf_queue.c (ffffffff819a64d5)
Location: net/netfilter/nf_queue.c:158
Inline: True
Inline callers:
  - net/netfilter/nf_queue.c:nf_queue
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int __nf_queue(struct sk_buff *skb, const struct nf_hook_state *state, unsigned int index, unsigned int queuenum);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/netfilter/nf_queue.c (ffffffff81a8f790)
Location: net/netfilter/nf_queue.c:155
Inline: False
Direct callers:
  - net/netfilter/nf_queue.c:nf_reinject
```
**Symbols:**

```
ffffffff81a8f790-ffffffff81a8fa35: __nf_queue (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int __nf_queue(struct sk_buff *skb, const struct nf_hook_state *state, unsigned int index, unsigned int queuenum);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/netfilter/nf_queue.c (ffffffff81a99780)
Location: net/netfilter/nf_queue.c:155
Inline: False
Direct callers:
  - net/netfilter/nf_queue.c:nf_reinject
```
**Symbols:**

```
ffffffff81a99780-ffffffff81a99a25: __nf_queue (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int __nf_queue(struct sk_buff *skb, const struct nf_hook_state *state, unsigned int index, unsigned int queuenum);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/netfilter/nf_queue.c (ffffffff81a84a90)
Location: net/netfilter/nf_queue.c:155
Inline: False
Direct callers:
  - net/netfilter/nf_queue.c:nf_reinject
```
**Symbols:**

```
ffffffff81a84a90-ffffffff81a84d35: __nf_queue (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int __nf_queue(struct sk_buff *skb, const struct nf_hook_state *state, unsigned int index, unsigned int queuenum);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/netfilter/nf_queue.c (0)
Location: net/netfilter/nf_queue.c:158
Inline: False
Direct callers:
  - net/netfilter/nf_queue.c:nf_reinject
```
**Symbols:**

```
ffffffff81b3f0a0-ffffffff81b3f3c3: __nf_queue (STB_LOCAL)
ffffffff81d39c06-ffffffff81d39c32: __nf_queue.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int __nf_queue(struct sk_buff *skb, const struct nf_hook_state *state, unsigned int index, unsigned int queuenum);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/netfilter/nf_queue.c (0)
Location: net/netfilter/nf_queue.c:158
Inline: False
Direct callers:
  - net/netfilter/nf_queue.c:nf_reinject
```
**Symbols:**

```
ffffffff81ccb7e0-ffffffff81ccbb1b: __nf_queue (STB_LOCAL)
ffffffff81f06349-ffffffff81f06375: __nf_queue.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
int __nf_queue(struct sk_buff *skb, const struct nf_hook_state *state, unsigned int index, unsigned int queuenum);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/netfilter/nf_queue.c (0)
Location: net/netfilter/nf_queue.c:158
Inline: False
Direct callers:
  - net/netfilter/nf_queue.c:nf_reinject
```
**Symbols:**

```
ffffffff81e8b630-ffffffff81e8b96b: __nf_queue (STB_LOCAL)
ffffffff820adf94-ffffffff820adfc0: __nf_queue.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
int __nf_queue(struct sk_buff *skb, const struct nf_hook_state *state, unsigned int index, unsigned int queuenum);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/netfilter/nf_queue.c (0)
Location: net/netfilter/nf_queue.c:158
Inline: False
Direct callers:
  - net/netfilter/nf_queue.c:nf_reinject
```
**Symbols:**

```
ffffffff81ee9680-ffffffff81ee99d0: __nf_queue (STB_LOCAL)
ffffffff8212f49a-ffffffff8212f4bd: __nf_queue.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
int __nf_queue(struct sk_buff *skb, const struct nf_hook_state *state, unsigned int index, unsigned int queuenum);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/netfilter/nf_queue.c (0)
Location: net/netfilter/nf_queue.c:156
Inline: False
Direct callers:
  - net/netfilter/nf_queue.c:nf_reinject
```
**Symbols:**

```
ffffffff81fad3f0-ffffffff81fad77e: __nf_queue (STB_LOCAL)
ffffffff8221122b-ffffffff8221124e: __nf_queue.cold (STB_LOCAL)
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
In net/netfilter/nf_queue.c (ffff800010c55da4)
Location: net/netfilter/nf_queue.c:158
Inline: True
Inline callers:
  - net/netfilter/nf_queue.c:nf_queue
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
In net/netfilter/nf_queue.c (c0d6578c)
Location: net/netfilter/nf_queue.c:158
Inline: True
Inline callers:
  - net/netfilter/nf_queue.c:nf_queue
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
In net/netfilter/nf_queue.c (c000000000d564c8)
Location: net/netfilter/nf_queue.c:158
Inline: True
Inline callers:
  - net/netfilter/nf_queue.c:nf_queue
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
In net/netfilter/nf_queue.c (ffffffe0007c00d6)
Location: net/netfilter/nf_queue.c:158
Inline: True
Inline callers:
  - net/netfilter/nf_queue.c:nf_queue
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
In net/netfilter/nf_queue.c (ffffffff81946345)
Location: net/netfilter/nf_queue.c:158
Inline: True
Inline callers:
  - net/netfilter/nf_queue.c:nf_queue
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
In net/netfilter/nf_queue.c (ffffffff818ffe35)
Location: net/netfilter/nf_queue.c:158
Inline: True
Inline callers:
  - net/netfilter/nf_queue.c:nf_queue
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
In net/netfilter/nf_queue.c (ffffffff819974d5)
Location: net/netfilter/nf_queue.c:158
Inline: True
Inline callers:
  - net/netfilter/nf_queue.c:nf_queue
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
In net/netfilter/nf_queue.c (ffffffff819ba1b5)
Location: net/netfilter/nf_queue.c:158
Inline: True
Inline callers:
  - net/netfilter/nf_queue.c:nf_queue
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
