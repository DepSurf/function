# Function: <code>__netif_reschedule</code>

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
In net/core/dev.c (ffffffff81718f85)
Location: net/core/dev.c:2237
Inline: True
Inline callers:
  - net/core/dev.c:__netif_schedule
  - net/core/dev.c:net_tx_action
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
In net/core/dev.c (ffffffff817816b6)
Location: net/core/dev.c:2259
Inline: True
Inline callers:
  - net/core/dev.c:__netif_schedule
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
In net/core/dev.c (ffffffff817aefc6)
Location: net/core/dev.c:2391
Inline: True
Inline callers:
  - net/core/dev.c:__netif_schedule
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
In net/core/dev.c (ffffffff817cd907)
Location: net/core/dev.c:2425
Inline: True
Inline callers:
  - net/core/dev.c:__netif_schedule
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
In net/core/dev.c (ffffffff81846f85)
Location: net/core/dev.c:2452
Inline: True
Inline callers:
  - net/core/dev.c:__netif_schedule
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
In net/core/dev.c (ffffffff818905e9)
Location: net/core/dev.c:2496
Inline: True
Inline callers:
  - net/core/dev.c:__netif_schedule
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
In net/core/dev.c (ffffffff818b0ea9)
Location: net/core/dev.c:2731
Inline: True
Inline callers:
  - net/core/dev.c:__netif_schedule
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
In net/core/dev.c (ffffffff818fdeb2)
Location: net/core/dev.c:2741
Inline: True
Inline callers:
  - net/core/dev.c:__netif_schedule
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
In net/core/dev.c (ffffffff819301e2)
Location: net/core/dev.c:2659
Inline: True
Inline callers:
  - net/core/dev.c:__netif_schedule
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
In net/core/dev.c (ffffffff81a051b2)
Location: net/core/dev.c:3019
Inline: True
Inline callers:
  - net/core/dev.c:__netif_schedule
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff81a067b2)
Location: net/core/dev.c:3044
Inline: True
Inline callers:
  - net/core/dev.c:__netif_schedule
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
In net/core/dev.c (ffffffff819ee252)
Location: net/core/dev.c:3112
Inline: True
Inline callers:
  - net/core/dev.c:__netif_schedule
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
In net/core/dev.c (ffffffff81a9f4f2)
Location: net/core/dev.c:3033
Inline: True
Inline callers:
  - net/core/dev.c:__netif_schedule
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void __netif_reschedule(struct Qdisc *q);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff81c0cf20)
Location: net/core/dev.c:3068
Inline: False
Direct callers:
  - net/core/dev.c:net_tx_action
  - net/core/dev.c:__dev_xmit_skb
  - net/core/dev.c:__dev_xmit_skb
  - net/core/dev.c:__dev_xmit_skb
  - net/core/dev.c:__dev_xmit_skb
  - net/core/dev.c:netif_schedule_queue
```
**Symbols:**

```
ffffffff81c0cf20-ffffffff81c0cf8a: __netif_reschedule (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void __netif_reschedule(struct Qdisc *q);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff81dbcae0)
Location: net/core/dev.c:3053
Inline: False
Direct callers:
  - net/core/dev.c:net_tx_action
  - net/core/dev.c:__dev_xmit_skb
  - net/core/dev.c:__dev_xmit_skb
  - net/core/dev.c:__dev_xmit_skb
  - net/core/dev.c:__dev_xmit_skb
  - net/core/dev.c:netif_device_attach
  - net/core/dev.c:netif_schedule_queue
```
**Symbols:**

```
ffffffff81dbcae0-ffffffff81dbcb54: __netif_reschedule (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void __netif_reschedule(struct Qdisc *q);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff81e2d2f0)
Location: net/core/dev.c:3083
Inline: False
Direct callers:
  - net/core/dev.c:net_tx_action
  - net/core/dev.c:__dev_xmit_skb
  - net/core/dev.c:__dev_xmit_skb
  - net/core/dev.c:__dev_xmit_skb
  - net/core/dev.c:__dev_xmit_skb
  - net/core/dev.c:netif_device_attach
  - net/core/dev.c:netif_schedule_queue
```
**Symbols:**

```
ffffffff81e2d2f0-ffffffff81e2d364: __netif_reschedule (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void __netif_reschedule(struct Qdisc *q);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff81eeb5d0)
Location: net/core/dev.c:3086
Inline: False
Direct callers:
  - net/core/dev.c:net_tx_action
  - net/core/dev.c:__dev_xmit_skb
  - net/core/dev.c:__dev_xmit_skb
  - net/core/dev.c:__dev_xmit_skb
  - net/core/dev.c:__dev_xmit_skb
  - net/core/dev.c:netif_device_attach
  - net/core/dev.c:netif_schedule_queue
```
**Symbols:**

```
ffffffff81eeb5d0-ffffffff81eeb644: __netif_reschedule (STB_LOCAL)
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
In net/core/dev.c (ffff800010bce280)
Location: net/core/dev.c:2659
Inline: True
Inline callers:
  - net/core/dev.c:__netif_schedule
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
In net/core/dev.c (c0ce4530)
Location: net/core/dev.c:2659
Inline: True
Inline callers:
  - net/core/dev.c:__netif_schedule
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
In net/core/dev.c (c000000000ca4ca8)
Location: net/core/dev.c:2659
Inline: True
Inline callers:
  - net/core/dev.c:__netif_schedule
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void __netif_reschedule(struct Qdisc *q);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffe000754e56)
Location: net/core/dev.c:2659
Inline: False
Direct callers:
  - net/core/dev.c:netif_schedule_queue
```
**Symbols:**

```
ffffffe000754e56-ffffffe000754ebc: __netif_reschedule (STB_LOCAL)
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
In net/core/dev.c (ffffffff818d01e2)
Location: net/core/dev.c:2659
Inline: True
Inline callers:
  - net/core/dev.c:__netif_schedule
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
In net/core/dev.c (ffffffff818861b2)
Location: net/core/dev.c:2659
Inline: True
Inline callers:
  - net/core/dev.c:__netif_schedule
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
In net/core/dev.c (ffffffff819211e2)
Location: net/core/dev.c:2659
Inline: True
Inline callers:
  - net/core/dev.c:__netif_schedule
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
In net/core/dev.c (ffffffff819430c2)
Location: net/core/dev.c:2659
Inline: True
Inline callers:
  - net/core/dev.c:__netif_schedule
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
</ul>
