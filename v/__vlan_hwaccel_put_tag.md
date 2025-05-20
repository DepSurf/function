# Function: <code>__vlan_hwaccel_put_tag</code>

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
In net/core/skbuff.c (ffffffff81708e8f)
Location: include/linux/if_vlan.h:409
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_vlan_push
  - net/core/skbuff.c:skb_vlan_pop
  - net/core/skbuff.c:skb_vlan_untag
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
In net/core/skbuff.c (ffffffff817709af)
Location: include/linux/if_vlan.h:409
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_vlan_push
  - net/core/skbuff.c:skb_vlan_pop
  - net/core/skbuff.c:skb_vlan_untag
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
In net/core/skbuff.c (ffffffff8179db96)
Location: include/linux/if_vlan.h:411
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_vlan_push
  - net/core/skbuff.c:skb_vlan_pop
  - net/core/skbuff.c:skb_vlan_untag
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
In net/core/skbuff.c (ffffffff817bba4d)
Location: include/linux/if_vlan.h:411
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_vlan_push
  - net/core/skbuff.c:skb_vlan_pop
  - net/core/skbuff.c:skb_vlan_untag
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
In net/core/skbuff.c (ffffffff81834afd)
Location: include/linux/if_vlan.h:411
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_vlan_push
  - net/core/skbuff.c:skb_vlan_pop
  - net/core/skbuff.c:skb_vlan_untag
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
In net/core/skbuff.c (ffffffff8187f96c)
Location: include/linux/if_vlan.h:490
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_vlan_push
  - net/core/skbuff.c:skb_vlan_pop
  - net/core/skbuff.c:skb_vlan_untag
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
In net/core/skbuff.c (ffffffff8189fbc4)
Location: include/linux/if_vlan.h:526
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_vlan_push
  - net/core/skbuff.c:skb_vlan_pop
  - net/core/skbuff.c:skb_vlan_untag
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
In net/core/skbuff.c (ffffffff818ea5e6)
Location: include/linux/if_vlan.h:521
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_vlan_push
  - net/core/skbuff.c:skb_vlan_pop
  - net/core/skbuff.c:skb_vlan_untag
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
In net/core/skbuff.c (ffffffff8191c756)
Location: include/linux/if_vlan.h:510
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_vlan_push
  - net/core/skbuff.c:skb_vlan_pop
  - net/core/skbuff.c:skb_vlan_untag
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (ffffffff819f03cf)
Location: include/linux/if_vlan.h:512
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_vlan_push
  - net/core/skbuff.c:skb_vlan_pop
  - net/core/skbuff.c:skb_vlan_untag
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (ffffffff819f062f)
Location: include/linux/if_vlan.h:512
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_vlan_push
  - net/core/skbuff.c:skb_vlan_pop
  - net/core/skbuff.c:skb_vlan_untag
```
```
In net/sched/sch_frag.c (ffffffff81a6f4a6)
Location: include/linux/if_vlan.h:512
Inline: True
Inline callers:
  - net/sched/sch_frag.c:sch_frag_xmit
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (ffffffff819d4f79)
Location: include/linux/if_vlan.h:512
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_vlan_push
  - net/core/skbuff.c:skb_vlan_pop
  - net/core/skbuff.c:skb_vlan_untag
```
```
In net/sched/sch_frag.c (ffffffff81a57d88)
Location: include/linux/if_vlan.h:512
Inline: True
Inline callers:
  - net/sched/sch_frag.c:sch_frag_xmit
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (ffffffff81a84d09)
Location: include/linux/if_vlan.h:512
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_vlan_push
  - net/core/skbuff.c:skb_vlan_pop
  - net/core/skbuff.c:skb_vlan_untag
```
```
In net/sched/sch_frag.c (ffffffff81b10d4f)
Location: include/linux/if_vlan.h:512
Inline: True
Inline callers:
  - net/sched/sch_frag.c:sch_frag_xmit
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (ffffffff81bfacf6)
Location: include/linux/if_vlan.h:517
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_vlan_push
  - net/core/skbuff.c:skb_vlan_pop
  - net/core/skbuff.c:skb_vlan_untag
```
```
In net/sched/sch_frag.c (ffffffff81c97e60)
Location: include/linux/if_vlan.h:517
Inline: True
Inline callers:
  - net/sched/sch_frag.c:sch_frag_xmit
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (ffffffff81da9761)
Location: include/linux/if_vlan.h:515
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_vlan_push
  - net/core/skbuff.c:skb_vlan_pop
  - net/core/skbuff.c:skb_vlan_untag
```
```
In net/sched/sch_frag.c (ffffffff81e53e6c)
Location: include/linux/if_vlan.h:515
Inline: True
Inline callers:
  - net/sched/sch_frag.c:sch_frag_xmit
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (ffffffff81e18721)
Location: include/linux/if_vlan.h:524
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_vlan_push
  - net/core/skbuff.c:skb_vlan_pop
  - net/core/skbuff.c:skb_vlan_untag
```
```
In net/sched/sch_frag.c (ffffffff81eaf6e6)
Location: include/linux/if_vlan.h:524
Inline: True
Inline callers:
  - net/sched/sch_frag.c:sch_frag_xmit
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (ffffffff81ed5bc1)
Location: include/linux/if_vlan.h:524
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_vlan_push
  - net/core/skbuff.c:skb_vlan_pop
  - net/core/skbuff.c:skb_vlan_untag
```
```
In net/sched/sch_frag.c (ffffffff81f72166)
Location: include/linux/if_vlan.h:524
Inline: True
Inline callers:
  - net/sched/sch_frag.c:sch_frag_xmit
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/net/ethernet/freescale/fec_main.c (ffff8000109e6f54)
Location: include/linux/if_vlan.h:510
Inline: True
Inline callers:
  - drivers/net/ethernet/freescale/fec_main.c:fec_enet_rx_queue
```
```
In net/core/skbuff.c (ffff800010bb6cd4)
Location: include/linux/if_vlan.h:510
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_vlan_push
  - net/core/skbuff.c:skb_vlan_pop
  - net/core/skbuff.c:skb_vlan_untag
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/net/ethernet/freescale/fec_main.c (c0acbcb8)
Location: include/linux/if_vlan.h:510
Inline: True
Inline callers:
  - drivers/net/ethernet/freescale/fec_main.c:fec_enet_rx_queue
```
```
In drivers/net/ethernet/ti/cpsw.c (c0ad3044)
Location: include/linux/if_vlan.h:510
Inline: True
Inline callers:
  - drivers/net/ethernet/ti/cpsw.c:cpsw_rx_handler
```
```
In net/core/skbuff.c (c0cd3b78)
Location: include/linux/if_vlan.h:510
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_vlan_push
  - net/core/skbuff.c:skb_vlan_pop
  - net/core/skbuff.c:skb_vlan_untag
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
In net/core/skbuff.c (c000000000c8e660)
Location: include/linux/if_vlan.h:510
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_vlan_push
  - net/core/skbuff.c:skb_vlan_pop
  - net/core/skbuff.c:skb_vlan_untag
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
In net/core/skbuff.c (ffffffe000746986)
Location: include/linux/if_vlan.h:510
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_vlan_push
  - net/core/skbuff.c:skb_vlan_pop
  - net/core/skbuff.c:skb_vlan_untag
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
In net/core/skbuff.c (ffffffff818bc756)
Location: include/linux/if_vlan.h:510
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_vlan_push
  - net/core/skbuff.c:skb_vlan_pop
  - net/core/skbuff.c:skb_vlan_untag
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
In net/core/skbuff.c (ffffffff81876696)
Location: include/linux/if_vlan.h:510
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_vlan_push
  - net/core/skbuff.c:skb_vlan_pop
  - net/core/skbuff.c:skb_vlan_untag
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (ffffffff8190d756)
Location: include/linux/if_vlan.h:510
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_vlan_push
  - net/core/skbuff.c:skb_vlan_pop
  - net/core/skbuff.c:skb_vlan_untag
```
```
In net/netfilter/nfnetlink_queue.c (ffffffff81999a5f)
Location: include/linux/if_vlan.h:510
Inline: True
Inline callers:
  - net/netfilter/nfnetlink_queue.c:nfqnl_recv_verdict
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
In net/core/skbuff.c (ffffffff8192e886)
Location: include/linux/if_vlan.h:510
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_vlan_push
  - net/core/skbuff.c:skb_vlan_pop
  - net/core/skbuff.c:skb_vlan_untag
```
</details>
</li>
</ul>

## Differences
