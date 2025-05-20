# Function: <code>enqueue_to_backlog</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int enqueue_to_backlog(struct sk_buff *skb, int cpu, unsigned int *qtail);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff81719300)
Location: net/core/dev.c:3487
Inline: False
Direct callers:
  - net/core/dev.c:netif_rx_internal
  - net/core/dev.c:netif_rx_internal
  - net/core/dev.c:netif_receive_skb_internal
```
**Symbols:**

```
ffffffff81719300-ffffffff81719534: enqueue_to_backlog (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int enqueue_to_backlog(struct sk_buff *skb, int cpu, unsigned int *qtail);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff817817f0)
Location: net/core/dev.c:3740
Inline: False
Direct callers:
  - net/core/dev.c:netif_receive_skb_internal
  - net/core/dev.c:netif_rx_internal
  - net/core/dev.c:netif_rx_internal
```
**Symbols:**

```
ffffffff817817f0-ffffffff81781a1c: enqueue_to_backlog (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int enqueue_to_backlog(struct sk_buff *skb, int cpu, unsigned int *qtail);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff817af100)
Location: net/core/dev.c:3736
Inline: False
Direct callers:
  - net/core/dev.c:netif_receive_skb_internal
```
**Symbols:**

```
ffffffff817af100-ffffffff817af32c: enqueue_to_backlog (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int enqueue_to_backlog(struct sk_buff *skb, int cpu, unsigned int *qtail);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff817cda10)
Location: net/core/dev.c:3822
Inline: False
Direct callers:
  - net/core/dev.c:netif_receive_skb_internal
```
**Symbols:**

```
ffffffff817cda10-ffffffff817cdc3d: enqueue_to_backlog (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int enqueue_to_backlog(struct sk_buff *skb, int cpu, unsigned int *qtail);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff81847510)
Location: net/core/dev.c:3868
Inline: False
Direct callers:
  - net/core/dev.c:netif_receive_skb_internal
  - net/core/dev.c:netif_rx_internal
  - net/core/dev.c:netif_rx_internal
```
**Symbols:**

```
ffffffff81847510-ffffffff8184773d: enqueue_to_backlog (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int enqueue_to_backlog(struct sk_buff *skb, int cpu, unsigned int *qtail);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff81891d60)
Location: net/core/dev.c:3949
Inline: False
Direct callers:
  - net/core/dev.c:netif_rx_internal
  - net/core/dev.c:netif_rx_internal
```
**Symbols:**

```
ffffffff81891d60-ffffffff81891f89: enqueue_to_backlog (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int enqueue_to_backlog(struct sk_buff *skb, int cpu, unsigned int *qtail);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff818b26c0)
Location: net/core/dev.c:4244
Inline: False
Direct callers:
  - net/core/dev.c:netif_receive_skb_list
  - net/core/dev.c:netif_rx_internal
  - net/core/dev.c:netif_rx_internal
```
**Symbols:**

```
ffffffff818b26c0-ffffffff818b28e9: enqueue_to_backlog (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int enqueue_to_backlog(struct sk_buff *skb, int cpu, unsigned int *qtail);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff818fee70)
Location: net/core/dev.c:4253
Inline: False
Direct callers:
  - net/core/dev.c:netif_receive_skb_list
  - net/core/dev.c:netif_rx_internal
  - net/core/dev.c:netif_rx_internal
```
**Symbols:**

```
ffffffff818fee70-ffffffff818ff091: enqueue_to_backlog (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int enqueue_to_backlog(struct sk_buff *skb, int cpu, unsigned int *qtail);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff819311e0)
Location: net/core/dev.c:4155
Inline: False
Direct callers:
  - net/core/dev.c:netif_receive_skb_list_internal
  - net/core/dev.c:netif_rx_internal
  - net/core/dev.c:netif_rx_internal
```
**Symbols:**

```
ffffffff819311e0-ffffffff81931401: enqueue_to_backlog (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int enqueue_to_backlog(struct sk_buff *skb, int cpu, unsigned int *qtail);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff81a06a10)
Location: net/core/dev.c:4516
Inline: False
Direct callers:
  - net/core/dev.c:netif_receive_skb_list_internal
  - net/core/dev.c:netif_receive_skb_internal
  - net/core/dev.c:netif_rx_internal
  - net/core/dev.c:netif_rx_internal
```
**Symbols:**

```
ffffffff81a06a10-ffffffff81a06b8f: enqueue_to_backlog (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int enqueue_to_backlog(struct sk_buff *skb, int cpu, unsigned int *qtail);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff81a07fe0)
Location: net/core/dev.c:4545
Inline: False
Direct callers:
  - net/core/dev.c:netif_receive_skb_list_internal
  - net/core/dev.c:netif_receive_skb_internal
  - net/core/dev.c:netif_rx_internal
  - net/core/dev.c:netif_rx_internal
```
**Symbols:**

```
ffffffff81a07fe0-ffffffff81a0815f: enqueue_to_backlog (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int enqueue_to_backlog(struct sk_buff *skb, int cpu, unsigned int *qtail);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff819ee630)
Location: net/core/dev.c:4651
Inline: False
Direct callers:
  - net/core/dev.c:netif_receive_skb
  - net/core/dev.c:netif_receive_skb_list_internal
  - net/core/dev.c:netif_rx_internal
  - net/core/dev.c:netif_rx_internal
```
**Symbols:**

```
ffffffff819ee630-ffffffff819ee8b6: enqueue_to_backlog (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int enqueue_to_backlog(struct sk_buff *skb, int cpu, unsigned int *qtail);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff81a9f8c0)
Location: net/core/dev.c:4619
Inline: False
Direct callers:
  - net/core/dev.c:netif_receive_skb
  - net/core/dev.c:netif_receive_skb_list_internal
  - net/core/dev.c:netif_rx_internal
  - net/core/dev.c:netif_rx_internal
```
**Symbols:**

```
ffffffff81a9f8c0-ffffffff81a9fbf6: enqueue_to_backlog (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int enqueue_to_backlog(struct sk_buff *skb, int cpu, unsigned int *qtail);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff81c11050)
Location: net/core/dev.c:4660
Inline: False
Direct callers:
  - net/core/dev.c:netif_receive_skb
  - net/core/dev.c:netif_receive_skb_list_internal
  - net/core/dev.c:netif_rx_internal
  - net/core/dev.c:netif_rx_internal
```
**Symbols:**

```
ffffffff81c11050-ffffffff81c11402: enqueue_to_backlog (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int enqueue_to_backlog(struct sk_buff *skb, int cpu, unsigned int *qtail);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff81dc0cc0)
Location: net/core/dev.c:4647
Inline: False
Direct callers:
  - net/core/dev.c:netif_receive_skb
  - net/core/dev.c:netif_receive_skb_list_internal
  - net/core/dev.c:netif_rx_internal
  - net/core/dev.c:netif_rx_internal
```
**Symbols:**

```
ffffffff81dc0cc0-ffffffff81dc1072: enqueue_to_backlog (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
int enqueue_to_backlog(struct sk_buff *skb, int cpu, unsigned int *qtail);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/core/dev.c (0)
Location: net/core/dev.c:4622
Inline: False
Direct callers:
  - net/core/dev.c:netif_receive_skb
  - net/core/dev.c:netif_receive_skb_list_internal
  - net/core/dev.c:netif_rx_internal
  - net/core/dev.c:netif_rx_internal
```
**Symbols:**

```
ffffffff81e308d0-ffffffff81e30cc8: enqueue_to_backlog (STB_LOCAL)
ffffffff8212c976-ffffffff8212c9d3: enqueue_to_backlog.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
int enqueue_to_backlog(struct sk_buff *skb, int cpu, unsigned int *qtail);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/core/dev.c (0)
Location: net/core/dev.c:4770
Inline: False
Direct callers:
  - net/core/dev.c:netif_receive_skb
  - net/core/dev.c:netif_receive_skb_list_internal
  - net/core/dev.c:netif_rx_internal
  - net/core/dev.c:netif_rx_internal
```
**Symbols:**

```
ffffffff81eece60-ffffffff81eed23b: enqueue_to_backlog (STB_LOCAL)
ffffffff8220e5e0-ffffffff8220e63d: enqueue_to_backlog.cold (STB_LOCAL)
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
int enqueue_to_backlog(struct sk_buff *skb, int cpu, unsigned int *qtail);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffff800010bcf908)
Location: net/core/dev.c:4155
Inline: False
Direct callers:
  - net/core/dev.c:netif_receive_skb_list_internal
  - net/core/dev.c:netif_rx_internal
  - net/core/dev.c:netif_rx_internal
```
**Symbols:**

```
ffff800010bcf908-ffff800010bcfb88: enqueue_to_backlog (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int enqueue_to_backlog(struct sk_buff *skb, int cpu, unsigned int *qtail);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (c0ce40c4)
Location: net/core/dev.c:4155
Inline: False
Direct callers:
  - net/core/dev.c:netif_receive_skb_list_internal
  - net/core/dev.c:netif_rx_internal
```
**Symbols:**

```
c0ce40c4-c0ce430c: enqueue_to_backlog (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int enqueue_to_backlog(struct sk_buff *skb, int cpu, unsigned int *qtail);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (c000000000cac4b0)
Location: net/core/dev.c:4155
Inline: False
Direct callers:
  - net/core/dev.c:netif_receive_skb_list_internal
  - net/core/dev.c:netif_rx_internal
  - net/core/dev.c:netif_rx_internal
```
**Symbols:**

```
c000000000cac4b0-c000000000cac7ac: enqueue_to_backlog (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int enqueue_to_backlog(struct sk_buff *skb, int cpu, unsigned int *qtail);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffe000759b14)
Location: net/core/dev.c:4155
Inline: False
Direct callers:
  - net/core/dev.c:netif_receive_skb_list_internal
  - net/core/dev.c:netif_rx_internal
```
**Symbols:**

```
ffffffe000759b14-ffffffe000759d66: enqueue_to_backlog (STB_LOCAL)
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
int enqueue_to_backlog(struct sk_buff *skb, int cpu, unsigned int *qtail);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff818d11e0)
Location: net/core/dev.c:4155
Inline: False
Direct callers:
  - net/core/dev.c:netif_receive_skb_list_internal
  - net/core/dev.c:netif_receive_skb_internal
  - net/core/dev.c:netif_rx_internal
  - net/core/dev.c:netif_rx_internal
```
**Symbols:**

```
ffffffff818d11e0-ffffffff818d1401: enqueue_to_backlog (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int enqueue_to_backlog(struct sk_buff *skb, int cpu, unsigned int *qtail);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff8188b090)
Location: net/core/dev.c:4155
Inline: False
Direct callers:
  - net/core/dev.c:netif_receive_skb_list_internal
  - net/core/dev.c:netif_receive_skb_internal
  - net/core/dev.c:netif_rx_internal
  - net/core/dev.c:netif_rx_internal
```
**Symbols:**

```
ffffffff8188b090-ffffffff8188b297: enqueue_to_backlog (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int enqueue_to_backlog(struct sk_buff *skb, int cpu, unsigned int *qtail);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff819221e0)
Location: net/core/dev.c:4155
Inline: False
Direct callers:
  - net/core/dev.c:netif_receive_skb_list_internal
  - net/core/dev.c:netif_rx_internal
  - net/core/dev.c:netif_rx_internal
```
**Symbols:**

```
ffffffff819221e0-ffffffff81922401: enqueue_to_backlog (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int enqueue_to_backlog(struct sk_buff *skb, int cpu, unsigned int *qtail);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff819432b0)
Location: net/core/dev.c:4155
Inline: False
Direct callers:
  - net/core/dev.c:netif_receive_skb_list_internal
  - net/core/dev.c:netif_rx_internal
  - net/core/dev.c:netif_rx_internal
```
**Symbols:**

```
ffffffff819432b0-ffffffff819434fa: enqueue_to_backlog (STB_LOCAL)
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
No changes between <code>4.8</code> and <code>4.10</code> ✅
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
