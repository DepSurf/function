# Function: <code>get_rps_cpu</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int get_rps_cpu(struct net_device *dev, struct sk_buff *skb, struct rps_dev_flow **rflowp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff817151a0)
Location: net/core/dev.c:3276
Inline: False
Direct callers:
  - net/core/dev.c:netif_rx_internal
  - net/core/dev.c:netif_receive_skb_internal
```
**Symbols:**

```
ffffffff817151a0-ffffffff817154d0: get_rps_cpu (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int get_rps_cpu(struct net_device *dev, struct sk_buff *skb, struct rps_dev_flow **rflowp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff8177d1f0)
Location: net/core/dev.c:3529
Inline: False
Direct callers:
  - net/core/dev.c:netif_receive_skb_internal
  - net/core/dev.c:netif_rx_internal
```
**Symbols:**

```
ffffffff8177d1f0-ffffffff8177d500: get_rps_cpu (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int get_rps_cpu(struct net_device *dev, struct sk_buff *skb, struct rps_dev_flow **rflowp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff817aa720)
Location: net/core/dev.c:3525
Inline: False
Direct callers:
  - net/core/dev.c:netif_receive_skb_internal
```
**Symbols:**

```
ffffffff817aa720-ffffffff817aaa30: get_rps_cpu (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int get_rps_cpu(struct net_device *dev, struct sk_buff *skb, struct rps_dev_flow **rflowp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff817c8d80)
Location: net/core/dev.c:3611
Inline: False
Direct callers:
  - net/core/dev.c:netif_receive_skb_internal
```
**Symbols:**

```
ffffffff817c8d80-ffffffff817c907b: get_rps_cpu (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int get_rps_cpu(struct net_device *dev, struct sk_buff *skb, struct rps_dev_flow **rflowp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff81842a20)
Location: net/core/dev.c:3657
Inline: False
Direct callers:
  - net/core/dev.c:netif_receive_skb_internal
  - net/core/dev.c:netif_rx_internal
```
**Symbols:**

```
ffffffff81842a20-ffffffff81842d1c: get_rps_cpu (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int get_rps_cpu(struct net_device *dev, struct sk_buff *skb, struct rps_dev_flow **rflowp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff8188ce60)
Location: net/core/dev.c:3738
Inline: False
Direct callers:
  - net/core/dev.c:netif_rx_internal
```
**Symbols:**

```
ffffffff8188ce60-ffffffff8188d162: get_rps_cpu (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int get_rps_cpu(struct net_device *dev, struct sk_buff *skb, struct rps_dev_flow **rflowp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff818ae0b0)
Location: net/core/dev.c:4033
Inline: False
Direct callers:
  - net/core/dev.c:netif_receive_skb_list
  - net/core/dev.c:netif_rx_internal
```
**Symbols:**

```
ffffffff818ae0b0-ffffffff818ae3a4: get_rps_cpu (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int get_rps_cpu(struct net_device *dev, struct sk_buff *skb, struct rps_dev_flow **rflowp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff818f99e0)
Location: net/core/dev.c:4042
Inline: False
Direct callers:
  - net/core/dev.c:netif_receive_skb_list
  - net/core/dev.c:netif_rx_internal
```
**Symbols:**

```
ffffffff818f99e0-ffffffff818f9cdf: get_rps_cpu (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int get_rps_cpu(struct net_device *dev, struct sk_buff *skb, struct rps_dev_flow **rflowp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff8192bb40)
Location: net/core/dev.c:3944
Inline: False
Direct callers:
  - net/core/dev.c:netif_receive_skb_list_internal
  - net/core/dev.c:netif_rx_internal
```
**Symbols:**

```
ffffffff8192bb40-ffffffff8192be3f: get_rps_cpu (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int get_rps_cpu(struct net_device *dev, struct sk_buff *skb, struct rps_dev_flow **rflowp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff81a062a0)
Location: net/core/dev.c:4305
Inline: False
Direct callers:
  - net/core/dev.c:netif_receive_skb_list_internal
  - net/core/dev.c:netif_receive_skb_internal
  - net/core/dev.c:netif_rx_internal
```
**Symbols:**

```
ffffffff81a062a0-ffffffff81a0659a: get_rps_cpu (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int get_rps_cpu(struct net_device *dev, struct sk_buff *skb, struct rps_dev_flow **rflowp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff81a07850)
Location: net/core/dev.c:4334
Inline: False
Direct callers:
  - net/core/dev.c:netif_receive_skb_list_internal
  - net/core/dev.c:netif_receive_skb_internal
  - net/core/dev.c:netif_rx_internal
```
**Symbols:**

```
ffffffff81a07850-ffffffff81a07b41: get_rps_cpu (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int get_rps_cpu(struct net_device *dev, struct sk_buff *skb, struct rps_dev_flow **rflowp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff819ebbe0)
Location: net/core/dev.c:4440
Inline: False
Direct callers:
  - net/core/dev.c:netif_receive_skb
  - net/core/dev.c:netif_receive_skb_list_internal
  - net/core/dev.c:netif_rx_internal
```
**Symbols:**

```
ffffffff819ebbe0-ffffffff819ebed6: get_rps_cpu (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int get_rps_cpu(struct net_device *dev, struct sk_buff *skb, struct rps_dev_flow **rflowp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/core/dev.c (0)
Location: net/core/dev.c:4408
Inline: False
Direct callers:
  - net/core/dev.c:netif_receive_skb
  - net/core/dev.c:netif_receive_skb_list_internal
  - net/core/dev.c:netif_rx_internal
```
**Symbols:**

```
ffffffff81a9cad0-ffffffff81a9ce6b: get_rps_cpu (STB_LOCAL)
ffffffff81d36149-ffffffff81d3615d: get_rps_cpu.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int get_rps_cpu(struct net_device *dev, struct sk_buff *skb, struct rps_dev_flow **rflowp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/core/dev.c (0)
Location: net/core/dev.c:4439
Inline: False
Direct callers:
  - net/core/dev.c:netif_receive_skb
  - net/core/dev.c:netif_receive_skb_list_internal
  - net/core/dev.c:netif_rx_internal
```
**Symbols:**

```
ffffffff81c151f0-ffffffff81c155c8: get_rps_cpu (STB_LOCAL)
ffffffff81f0292b-ffffffff81f0293f: get_rps_cpu.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
int get_rps_cpu(struct net_device *dev, struct sk_buff *skb, struct rps_dev_flow **rflowp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/core/dev.c (0)
Location: net/core/dev.c:4426
Inline: False
Direct callers:
  - net/core/dev.c:netif_receive_skb
  - net/core/dev.c:netif_receive_skb_list_internal
  - net/core/dev.c:netif_rx_internal
```
**Symbols:**

```
ffffffff81dc6550-ffffffff81dc6928: get_rps_cpu (STB_LOCAL)
ffffffff820ab4eb-ffffffff820ab4ff: get_rps_cpu.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
int get_rps_cpu(struct net_device *dev, struct sk_buff *skb, struct rps_dev_flow **rflowp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/core/dev.c (0)
Location: net/core/dev.c:4391
Inline: False
Direct callers:
  - net/core/dev.c:netif_receive_skb
  - net/core/dev.c:netif_receive_skb_list_internal
  - net/core/dev.c:netif_rx_internal
```
**Symbols:**

```
ffffffff81e358f0-ffffffff81e35cc7: get_rps_cpu (STB_LOCAL)
ffffffff8212cb57-ffffffff8212cb6b: get_rps_cpu.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
int get_rps_cpu(struct net_device *dev, struct sk_buff *skb, struct rps_dev_flow **rflowp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/core/dev.c (0)
Location: net/core/dev.c:4539
Inline: False
Direct callers:
  - net/core/dev.c:netif_receive_skb
  - net/core/dev.c:netif_receive_skb_list_internal
  - net/core/dev.c:netif_rx_internal
```
**Symbols:**

```
ffffffff81ef3bb0-ffffffff81ef3f88: get_rps_cpu (STB_LOCAL)
ffffffff8220e895-ffffffff8220e8a9: get_rps_cpu.cold (STB_LOCAL)
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
int get_rps_cpu(struct net_device *dev, struct sk_buff *skb, struct rps_dev_flow **rflowp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffff800010bc81c8)
Location: net/core/dev.c:3944
Inline: False
Direct callers:
  - net/core/dev.c:netif_receive_skb_list_internal
  - net/core/dev.c:netif_rx_internal
```
**Symbols:**

```
ffff800010bc81c8-ffff800010bc8514: get_rps_cpu (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int get_rps_cpu(struct net_device *dev, struct sk_buff *skb, struct rps_dev_flow **rflowp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (c0ce3a50)
Location: net/core/dev.c:3944
Inline: False
Direct callers:
  - net/core/dev.c:netif_receive_skb_list_internal
```
**Symbols:**

```
c0ce3a50-c0ce3dec: get_rps_cpu (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int get_rps_cpu(struct net_device *dev, struct sk_buff *skb, struct rps_dev_flow **rflowp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (c000000000ca4070)
Location: net/core/dev.c:3944
Inline: False
Direct callers:
  - net/core/dev.c:netif_receive_skb_list_internal
  - net/core/dev.c:netif_rx_internal
```
**Symbols:**

```
c000000000ca4070-c000000000ca4520: get_rps_cpu (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int get_rps_cpu(struct net_device *dev, struct sk_buff *skb, struct rps_dev_flow **rflowp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffe00075470c)
Location: net/core/dev.c:3944
Inline: False
Direct callers:
  - net/core/dev.c:netif_receive_skb_list_internal
```
**Symbols:**

```
ffffffe00075470c-ffffffe000754a0e: get_rps_cpu (STB_LOCAL)
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
int get_rps_cpu(struct net_device *dev, struct sk_buff *skb, struct rps_dev_flow **rflowp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff818cbb40)
Location: net/core/dev.c:3944
Inline: False
Direct callers:
  - net/core/dev.c:netif_receive_skb_list_internal
  - net/core/dev.c:netif_receive_skb_internal
  - net/core/dev.c:netif_rx_internal
```
**Symbols:**

```
ffffffff818cbb40-ffffffff818cbe3f: get_rps_cpu (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int get_rps_cpu(struct net_device *dev, struct sk_buff *skb, struct rps_dev_flow **rflowp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff81885a80)
Location: net/core/dev.c:3944
Inline: False
Direct callers:
  - net/core/dev.c:netif_receive_skb_list_internal
  - net/core/dev.c:netif_receive_skb_internal
  - net/core/dev.c:netif_rx_internal
```
**Symbols:**

```
ffffffff81885a80-ffffffff81885d7f: get_rps_cpu (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int get_rps_cpu(struct net_device *dev, struct sk_buff *skb, struct rps_dev_flow **rflowp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff8191cb40)
Location: net/core/dev.c:3944
Inline: False
Direct callers:
  - net/core/dev.c:netif_receive_skb_list_internal
  - net/core/dev.c:netif_rx_internal
```
**Symbols:**

```
ffffffff8191cb40-ffffffff8191ce3f: get_rps_cpu (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int get_rps_cpu(struct net_device *dev, struct sk_buff *skb, struct rps_dev_flow **rflowp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff8193e010)
Location: net/core/dev.c:3944
Inline: False
Direct callers:
  - net/core/dev.c:netif_receive_skb_list_internal
  - net/core/dev.c:netif_rx_internal
```
**Symbols:**

```
ffffffff8193e010-ffffffff8193e30f: get_rps_cpu (STB_LOCAL)
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
