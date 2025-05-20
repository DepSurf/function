# Function: <code>nf_reroute</code>

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
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int nf_reroute(struct sk_buff *skb, struct nf_queue_entry *entry);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/netfilter/utils.c (ffffffff818e1d20)
Location: net/netfilter/utils.c:74
Inline: False
Direct callers:
  - net/netfilter/nf_queue.c:nf_reinject
```
**Symbols:**

```
ffffffff818e1d20-ffffffff818e1d59: nf_reroute (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int nf_reroute(struct sk_buff *skb, struct nf_queue_entry *entry);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/netfilter/utils.c (ffffffff8190ebc0)
Location: net/netfilter/utils.c:183
Inline: False
Direct callers:
  - net/netfilter/nf_queue.c:nf_reinject
```
**Symbols:**

```
ffffffff8190ebc0-ffffffff8190ebf9: nf_reroute (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int nf_reroute(struct sk_buff *skb, struct nf_queue_entry *entry);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/netfilter/utils.c (ffffffff81970780)
Location: net/netfilter/utils.c:201
Inline: False
Direct callers:
  - net/netfilter/nf_queue.c:nf_reinject
```
**Symbols:**

```
ffffffff81970780-ffffffff819707ff: nf_reroute (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int nf_reroute(struct sk_buff *skb, struct nf_queue_entry *entry);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/netfilter/utils.c (ffffffff819a7170)
Location: net/netfilter/utils.c:201
Inline: False
Direct callers:
  - net/netfilter/nf_queue.c:nf_reinject
```
**Symbols:**

```
ffffffff819a7170-ffffffff819a71ef: nf_reroute (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int nf_reroute(struct sk_buff *skb, struct nf_queue_entry *entry);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/netfilter/utils.c (ffffffff81a904d0)
Location: net/netfilter/utils.c:201
Inline: False
Direct callers:
  - net/netfilter/nf_queue.c:nf_reinject
```
**Symbols:**

```
ffffffff81a904d0-ffffffff81a9054f: nf_reroute (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int nf_reroute(struct sk_buff *skb, struct nf_queue_entry *entry);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/netfilter/utils.c (ffffffff81a9a3a0)
Location: net/netfilter/utils.c:201
Inline: False
Direct callers:
  - net/netfilter/nf_queue.c:nf_reinject
```
**Symbols:**

```
ffffffff81a9a3a0-ffffffff81a9a426: nf_reroute (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int nf_reroute(struct sk_buff *skb, struct nf_queue_entry *entry);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/netfilter/utils.c (ffffffff81a85690)
Location: net/netfilter/utils.c:201
Inline: False
Direct callers:
  - net/netfilter/nf_queue.c:nf_reinject
```
**Symbols:**

```
ffffffff81a85690-ffffffff81a85716: nf_reroute (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int nf_reroute(struct sk_buff *skb, struct nf_queue_entry *entry);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/netfilter/utils.c (ffffffff81b3fd80)
Location: net/netfilter/utils.c:201
Inline: False
Direct callers:
  - net/netfilter/nf_queue.c:nf_reinject
```
**Symbols:**

```
ffffffff81b3fd80-ffffffff81b3fe06: nf_reroute (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int nf_reroute(struct sk_buff *skb, struct nf_queue_entry *entry);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/netfilter/utils.c (ffffffff81ccc5f0)
Location: net/netfilter/utils.c:201
Inline: False
Direct callers:
  - net/netfilter/nf_queue.c:nf_reinject
```
**Symbols:**

```
ffffffff81ccc5f0-ffffffff81ccc6a3: nf_reroute (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int nf_reroute(struct sk_buff *skb, struct nf_queue_entry *entry);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/netfilter/utils.c (ffffffff81e8c510)
Location: net/netfilter/utils.c:201
Inline: False
Direct callers:
  - net/netfilter/nf_queue.c:nf_reinject
```
**Symbols:**

```
ffffffff81e8c510-ffffffff81e8c5c3: nf_reroute (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int nf_reroute(struct sk_buff *skb, struct nf_queue_entry *entry);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/netfilter/utils.c (ffffffff81eea710)
Location: net/netfilter/utils.c:201
Inline: False
Direct callers:
  - net/netfilter/nf_queue.c:nf_reinject
```
**Symbols:**

```
ffffffff81eea710-ffffffff81eea7c3: nf_reroute (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int nf_reroute(struct sk_buff *skb, struct nf_queue_entry *entry);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/netfilter/utils.c (ffffffff81fae4c0)
Location: net/netfilter/utils.c:201
Inline: False
Direct callers:
  - net/netfilter/nf_queue.c:nf_reinject
```
**Symbols:**

```
ffffffff81fae4c0-ffffffff81fae573: nf_reroute (STB_GLOBAL)
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
int nf_reroute(struct sk_buff *skb, struct nf_queue_entry *entry);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/netfilter/utils.c (ffff800010c56c70)
Location: net/netfilter/utils.c:201
Inline: False
Direct callers:
  - net/netfilter/nf_queue.c:nf_reinject
```
**Symbols:**

```
ffff800010c56c70-ffff800010c56d54: nf_reroute (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int nf_reroute(struct sk_buff *skb, struct nf_queue_entry *entry);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/netfilter/utils.c (c0d66394)
Location: net/netfilter/utils.c:201
Inline: False
Direct callers:
  - net/netfilter/nf_queue.c:nf_reinject
```
**Symbols:**

```
c0d66394-c0d66458: nf_reroute (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int nf_reroute(struct sk_buff *skb, struct nf_queue_entry *entry);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/netfilter/utils.c (c000000000d578c0)
Location: net/netfilter/utils.c:201
Inline: False
Direct callers:
  - net/netfilter/nf_queue.c:nf_reinject
```
**Symbols:**

```
c000000000d578c0-c000000000d579e8: nf_reroute (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int nf_reroute(struct sk_buff *skb, struct nf_queue_entry *entry);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/netfilter/utils.c (ffffffe0007c0bec)
Location: net/netfilter/utils.c:201
Inline: False
Direct callers:
  - net/netfilter/nf_queue.c:nf_reinject
```
**Symbols:**

```
ffffffe0007c0bec-ffffffe0007c0c8c: nf_reroute (STB_GLOBAL)
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
int nf_reroute(struct sk_buff *skb, struct nf_queue_entry *entry);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/netfilter/utils.c (ffffffff81946fe0)
Location: net/netfilter/utils.c:201
Inline: False
Direct callers:
  - net/netfilter/nf_queue.c:nf_reinject
```
**Symbols:**

```
ffffffff81946fe0-ffffffff8194705f: nf_reroute (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int nf_reroute(struct sk_buff *skb, struct nf_queue_entry *entry);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/netfilter/utils.c (ffffffff81900ad0)
Location: net/netfilter/utils.c:201
Inline: False
Direct callers:
  - net/netfilter/nf_queue.c:nf_reinject
```
**Symbols:**

```
ffffffff81900ad0-ffffffff81900b4f: nf_reroute (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int nf_reroute(struct sk_buff *skb, struct nf_queue_entry *entry);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/netfilter/utils.c (ffffffff81998170)
Location: net/netfilter/utils.c:201
Inline: False
Direct callers:
  - net/netfilter/nf_queue.c:nf_reinject
```
**Symbols:**

```
ffffffff81998170-ffffffff819981ef: nf_reroute (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int nf_reroute(struct sk_buff *skb, struct nf_queue_entry *entry);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/netfilter/utils.c (ffffffff819bae50)
Location: net/netfilter/utils.c:201
Inline: False
Direct callers:
  - net/netfilter/nf_queue.c:nf_reinject
```
**Symbols:**

```
ffffffff819bae50-ffffffff819baecf: nf_reroute (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
