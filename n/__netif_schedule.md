# Function: <code>__netif_schedule</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void __netif_schedule(struct Qdisc *q);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff81718f70)
Location: net/core/dev.c:2251
Inline: False
Direct callers:
  - net/core/dev.c:netif_schedule_queue
  - net/core/dev.c:netif_wake_subqueue
  - net/core/dev.c:netif_tx_wake_queue
  - net/sched/sch_generic.c:sch_direct_xmit
  - net/sched/sch_generic.c:sch_direct_xmit
  - net/sched/sch_generic.c:__qdisc_run
  - net/sched/sch_api.c:qdisc_watchdog
```
**Symbols:**

```
ffffffff81718f70-ffffffff81718fd7: __netif_schedule (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void __netif_schedule(struct Qdisc *q);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff817816a0)
Location: net/core/dev.c:2273
Inline: False
Direct callers:
  - net/core/dev.c:netif_tx_wake_queue
  - net/core/dev.c:netif_wake_subqueue
  - net/core/dev.c:netif_schedule_queue
  - net/sched/sch_generic.c:__qdisc_run
  - net/sched/sch_generic.c:sch_direct_xmit
  - net/sched/sch_api.c:qdisc_watchdog
```
**Symbols:**

```
ffffffff817816a0-ffffffff8178170a: __netif_schedule (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void __netif_schedule(struct Qdisc *q);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff817aefb0)
Location: net/core/dev.c:2405
Inline: False
Direct callers:
  - net/core/dev.c:netif_tx_wake_queue
  - net/core/dev.c:netif_wake_subqueue
  - net/core/dev.c:netif_schedule_queue
  - net/sched/sch_generic.c:__qdisc_run
  - net/sched/sch_generic.c:sch_direct_xmit
  - net/sched/sch_api.c:qdisc_watchdog
```
**Symbols:**

```
ffffffff817aefb0-ffffffff817af01a: __netif_schedule (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void __netif_schedule(struct Qdisc *q);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff817cd8f0)
Location: net/core/dev.c:2439
Inline: False
Direct callers:
  - net/core/dev.c:netif_tx_wake_queue
  - net/core/dev.c:netif_schedule_queue
  - net/sched/sch_generic.c:__qdisc_run
  - net/sched/sch_generic.c:sch_direct_xmit
  - net/sched/sch_api.c:qdisc_watchdog
```
**Symbols:**

```
ffffffff817cd8f0-ffffffff817cd95b: __netif_schedule (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void __netif_schedule(struct Qdisc *q);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff81846f70)
Location: net/core/dev.c:2466
Inline: False
Direct callers:
  - net/core/dev.c:netif_tx_wake_queue
  - net/core/dev.c:netif_schedule_queue
  - net/sched/sch_generic.c:__qdisc_run
  - net/sched/sch_generic.c:sch_direct_xmit
  - net/sched/sch_api.c:qdisc_watchdog
```
**Symbols:**

```
ffffffff81846f70-ffffffff81846fd9: __netif_schedule (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void __netif_schedule(struct Qdisc *q);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff818905d0)
Location: net/core/dev.c:2510
Inline: False
Direct callers:
  - net/core/dev.c:netif_tx_wake_queue
  - net/core/dev.c:netif_schedule_queue
  - net/sched/sch_generic.c:__qdisc_run
  - net/sched/sch_generic.c:sch_direct_xmit
  - net/sched/sch_api.c:qdisc_watchdog
```
**Symbols:**

```
ffffffff818905d0-ffffffff8189063d: __netif_schedule (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void __netif_schedule(struct Qdisc *q);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff818b0e90)
Location: net/core/dev.c:2745
Inline: False
Direct callers:
  - net/core/dev.c:netif_tx_wake_queue
  - net/core/dev.c:netif_schedule_queue
  - net/sched/sch_generic.c:__qdisc_run
  - net/sched/sch_generic.c:sch_direct_xmit
  - net/sched/sch_api.c:qdisc_watchdog
```
**Symbols:**

```
ffffffff818b0e90-ffffffff818b0efd: __netif_schedule (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void __netif_schedule(struct Qdisc *q);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff818fdea0)
Location: net/core/dev.c:2755
Inline: False
Direct callers:
  - net/core/dev.c:netif_schedule_queue
  - net/sched/sch_generic.c:__qdisc_run
  - net/sched/sch_generic.c:sch_direct_xmit
  - net/sched/sch_api.c:qdisc_watchdog
```
**Symbols:**

```
ffffffff818fdea0-ffffffff818fdf0b: __netif_schedule (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void __netif_schedule(struct Qdisc *q);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff819301d0)
Location: net/core/dev.c:2673
Inline: False
Direct callers:
  - net/core/dev.c:netif_schedule_queue
  - net/sched/sch_generic.c:__qdisc_run
  - net/sched/sch_generic.c:sch_direct_xmit
  - net/sched/sch_api.c:qdisc_watchdog
```
**Symbols:**

```
ffffffff819301d0-ffffffff8193023b: __netif_schedule (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void __netif_schedule(struct Qdisc *q);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff81a051a0)
Location: net/core/dev.c:3033
Inline: False
Direct callers:
  - net/core/dev.c:netif_schedule_queue
  - net/sched/sch_generic.c:__qdisc_run
  - net/sched/sch_generic.c:sch_direct_xmit
  - net/sched/sch_api.c:qdisc_watchdog
```
**Symbols:**

```
ffffffff81a051a0-ffffffff81a0520e: __netif_schedule (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void __netif_schedule(struct Qdisc *q);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff81a067a0)
Location: net/core/dev.c:3058
Inline: False
Direct callers:
  - net/core/dev.c:netif_schedule_queue
  - net/sched/sch_generic.c:__qdisc_run
  - net/sched/sch_generic.c:sch_direct_xmit
  - net/sched/sch_api.c:qdisc_watchdog
```
**Symbols:**

```
ffffffff81a067a0-ffffffff81a0680e: __netif_schedule (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void __netif_schedule(struct Qdisc *q);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff819ee240)
Location: net/core/dev.c:3126
Inline: False
Direct callers:
  - net/core/dev.c:net_tx_action
  - net/core/dev.c:__dev_xmit_skb
  - net/core/dev.c:__dev_xmit_skb
  - net/core/dev.c:netif_schedule_queue
  - net/sched/sch_generic.c:__qdisc_run
  - net/sched/sch_generic.c:sch_direct_xmit
  - net/sched/sch_api.c:qdisc_watchdog
```
**Symbols:**

```
ffffffff819ee240-ffffffff819ee2b6: __netif_schedule (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void __netif_schedule(struct Qdisc *q);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff81a9f4e0)
Location: net/core/dev.c:3047
Inline: False
Direct callers:
  - net/core/dev.c:net_tx_action
  - net/core/dev.c:__dev_xmit_skb
  - net/core/dev.c:__dev_xmit_skb
  - net/core/dev.c:__dev_xmit_skb
  - net/core/dev.c:netif_schedule_queue
  - net/sched/sch_generic.c:__qdisc_run
  - net/sched/sch_generic.c:sch_direct_xmit
  - net/sched/sch_api.c:qdisc_watchdog
```
**Symbols:**

```
ffffffff81a9f4e0-ffffffff81a9f556: __netif_schedule (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
void __netif_schedule(struct Qdisc *q);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff81c17f62)
Location: net/core/dev.c:3082
Inline: True
Inline callers:
  - net/core/dev.c:net_tx_action
  - net/core/dev.c:__dev_xmit_skb
  - net/core/dev.c:__dev_xmit_skb
  - net/core/dev.c:__dev_xmit_skb
  - net/core/dev.c:__dev_xmit_skb
  - net/core/dev.c:netif_schedule_queue
Direct callers:
  - net/core/dev.c:__dev_xmit_skb
  - net/sched/sch_generic.c:__qdisc_run
  - net/sched/sch_generic.c:sch_direct_xmit
  - net/sched/sch_api.c:qdisc_watchdog
```
**Symbols:**

```
ffffffff81c0cf90-ffffffff81c0cfb9: __netif_schedule (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
void __netif_schedule(struct Qdisc *q);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff81dc8e8a)
Location: net/core/dev.c:3067
Inline: True
Inline callers:
  - net/core/dev.c:net_tx_action
  - net/core/dev.c:__dev_xmit_skb
  - net/core/dev.c:__dev_xmit_skb
  - net/core/dev.c:__dev_xmit_skb
  - net/core/dev.c:__dev_xmit_skb
  - net/core/dev.c:netif_device_attach
  - net/core/dev.c:netif_schedule_queue
Direct callers:
  - net/sched/sch_generic.c:__qdisc_run
  - net/sched/sch_generic.c:sch_direct_xmit
  - net/sched/sch_api.c:qdisc_watchdog
```
**Symbols:**

```
ffffffff81dbcb70-ffffffff81dbcb99: __netif_schedule (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
void __netif_schedule(struct Qdisc *q);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff81e373f3)
Location: net/core/dev.c:3097
Inline: True
Inline callers:
  - net/core/dev.c:net_tx_action
  - net/core/dev.c:__dev_xmit_skb
  - net/core/dev.c:__dev_xmit_skb
  - net/core/dev.c:__dev_xmit_skb
  - net/core/dev.c:__dev_xmit_skb
  - net/core/dev.c:netif_device_attach
  - net/core/dev.c:netif_schedule_queue
Direct callers:
  - net/sched/sch_generic.c:__qdisc_run
  - net/sched/sch_generic.c:sch_direct_xmit
  - net/sched/sch_api.c:qdisc_watchdog
```
**Symbols:**

```
ffffffff81e2d380-ffffffff81e2d3a9: __netif_schedule (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
void __netif_schedule(struct Qdisc *q);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff81ef5413)
Location: net/core/dev.c:3100
Inline: True
Inline callers:
  - net/core/dev.c:net_tx_action
  - net/core/dev.c:__dev_xmit_skb
  - net/core/dev.c:__dev_xmit_skb
  - net/core/dev.c:__dev_xmit_skb
  - net/core/dev.c:__dev_xmit_skb
  - net/core/dev.c:netif_device_attach
  - net/core/dev.c:netif_schedule_queue
Direct callers:
  - net/sched/sch_generic.c:__qdisc_run
  - net/sched/sch_generic.c:sch_direct_xmit
  - net/sched/sch_api.c:qdisc_watchdog
```
**Symbols:**

```
ffffffff81eeb660-ffffffff81eeb689: __netif_schedule (STB_GLOBAL)
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
void __netif_schedule(struct Qdisc *q);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffff800010bce218)
Location: net/core/dev.c:2673
Inline: False
Direct callers:
  - net/core/dev.c:netif_schedule_queue
  - net/sched/sch_generic.c:__qdisc_run
  - net/sched/sch_generic.c:sch_direct_xmit
  - net/sched/sch_api.c:qdisc_watchdog
```
**Symbols:**

```
ffff800010bce218-ffff800010bce2ec: __netif_schedule (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void __netif_schedule(struct Qdisc *q);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (c0ce4504)
Location: net/core/dev.c:2673
Inline: False
Direct callers:
  - net/core/dev.c:netif_schedule_queue
  - net/sched/sch_generic.c:__qdisc_run
  - net/sched/sch_generic.c:sch_direct_xmit
  - net/sched/sch_api.c:qdisc_watchdog
```
**Symbols:**

```
c0ce4504-c0ce456c: __netif_schedule (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void __netif_schedule(struct Qdisc *q);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (c000000000ca4c60)
Location: net/core/dev.c:2673
Inline: False
Direct callers:
  - net/core/dev.c:netif_schedule_queue
  - net/sched/sch_generic.c:__qdisc_run
  - net/sched/sch_generic.c:sch_direct_xmit
  - net/sched/sch_api.c:qdisc_watchdog
```
**Symbols:**

```
c000000000ca4c60-c000000000ca4d04: __netif_schedule (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
void __netif_schedule(struct Qdisc *q);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffe000754f1c)
Location: net/core/dev.c:2673
Inline: True
Inline callers:
  - net/core/dev.c:netif_schedule_queue
Direct callers:
  - net/sched/sch_generic.c:__qdisc_run
  - net/sched/sch_generic.c:sch_direct_xmit
  - net/sched/sch_api.c:qdisc_watchdog
```
**Symbols:**

```
ffffffe000754ebc-ffffffe000754efe: __netif_schedule (STB_GLOBAL)
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
void __netif_schedule(struct Qdisc *q);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff818d01d0)
Location: net/core/dev.c:2673
Inline: False
Direct callers:
  - net/core/dev.c:netif_schedule_queue
  - net/sched/sch_generic.c:__qdisc_run
  - net/sched/sch_generic.c:sch_direct_xmit
  - net/sched/sch_api.c:qdisc_watchdog
```
**Symbols:**

```
ffffffff818d01d0-ffffffff818d023b: __netif_schedule (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void __netif_schedule(struct Qdisc *q);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff818861a0)
Location: net/core/dev.c:2673
Inline: False
Direct callers:
  - net/core/dev.c:netif_schedule_queue
  - net/sched/sch_generic.c:__qdisc_run
  - net/sched/sch_generic.c:sch_direct_xmit
  - net/sched/sch_api.c:qdisc_watchdog
```
**Symbols:**

```
ffffffff818861a0-ffffffff818861f5: __netif_schedule (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void __netif_schedule(struct Qdisc *q);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff819211d0)
Location: net/core/dev.c:2673
Inline: False
Direct callers:
  - net/core/dev.c:netif_schedule_queue
  - net/sched/sch_generic.c:__qdisc_run
  - net/sched/sch_generic.c:sch_direct_xmit
  - net/sched/sch_api.c:qdisc_watchdog
```
**Symbols:**

```
ffffffff819211d0-ffffffff8192123b: __netif_schedule (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void __netif_schedule(struct Qdisc *q);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff819430b0)
Location: net/core/dev.c:2673
Inline: False
Direct callers:
  - net/core/dev.c:netif_schedule_queue
  - net/sched/sch_generic.c:__qdisc_run
  - net/sched/sch_generic.c:sch_direct_xmit
  - net/sched/sch_api.c:qdisc_watchdog
```
**Symbols:**

```
ffffffff819430b0-ffffffff8194311b: __netif_schedule (STB_GLOBAL)
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
