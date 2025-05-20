# Function: <code>netif_xmit_frozen_or_stopped</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/core/netpoll.c (0)
Location: include/linux/netdevice.h:2718
Inline: True
```
```
In net/sched/sch_generic.c (0)
Location: include/linux/netdevice.h:2718
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/core/netpoll.c (0)
Location: include/linux/netdevice.h:2941
Inline: True
```
```
In net/sched/sch_generic.c (ffffffff817ae57e)
Location: include/linux/netdevice.h:2941
Inline: True
Inline callers:
  - net/sched/sch_generic.c:__qdisc_run
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/core/netpoll.c (0)
Location: include/linux/netdevice.h:2880
Inline: True
```
```
In net/sched/sch_generic.c (ffffffff817ddc0a)
Location: include/linux/netdevice.h:2880
Inline: True
Inline callers:
  - net/sched/sch_generic.c:__qdisc_run
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/core/netpoll.c (0)
Location: include/linux/netdevice.h:2907
Inline: True
```
```
In net/sched/sch_generic.c (ffffffff817fd210)
Location: include/linux/netdevice.h:2907
Inline: True
Inline callers:
  - net/sched/sch_generic.c:__qdisc_run
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/core/netpoll.c (0)
Location: include/linux/netdevice.h:2932
Inline: True
```
```
In net/sched/sch_generic.c (0)
Location: include/linux/netdevice.h:2932
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/core/netpoll.c (ffffffff818bf314)
Location: include/linux/netdevice.h:3041
Inline: True
Inline callers:
  - net/core/netpoll.c:queue_process
```
```
In net/sched/sch_generic.c (ffffffff818ccf0d)
Location: include/linux/netdevice.h:3041
Inline: True
Inline callers:
  - net/sched/sch_generic.c:__qdisc_run
  - net/sched/sch_generic.c:__qdisc_run
  - net/sched/sch_generic.c:__qdisc_run
  - net/sched/sch_generic.c:sch_direct_xmit
```
```
In net/xfrm/xfrm_device.c (ffffffff8195836c)
Location: include/linux/netdevice.h:3041
Inline: True
Inline callers:
  - net/xfrm/xfrm_device.c:xfrm_dev_resume
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/core/netpoll.c (ffffffff818e8131)
Location: include/linux/netdevice.h:3135
Inline: True
Inline callers:
  - net/core/netpoll.c:queue_process
```
```
In net/sched/sch_generic.c (ffffffff818f824e)
Location: include/linux/netdevice.h:3135
Inline: True
Inline callers:
  - net/sched/sch_generic.c:__qdisc_run
  - net/sched/sch_generic.c:__qdisc_run
  - net/sched/sch_generic.c:__qdisc_run
  - net/sched/sch_generic.c:sch_direct_xmit
```
```
In net/xfrm/xfrm_device.c (ffffffff8198cbbc)
Location: include/linux/netdevice.h:3135
Inline: True
Inline callers:
  - net/xfrm/xfrm_device.c:xfrm_dev_resume
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/core/netpoll.c (ffffffff81938371)
Location: include/linux/netdevice.h:3152
Inline: True
Inline callers:
  - net/core/netpoll.c:queue_process
```
```
In net/sched/sch_generic.c (ffffffff8195768b)
Location: include/linux/netdevice.h:3152
Inline: True
Inline callers:
  - net/sched/sch_generic.c:__qdisc_run
  - net/sched/sch_generic.c:__qdisc_run
  - net/sched/sch_generic.c:__qdisc_run
  - net/sched/sch_generic.c:sch_direct_xmit
```
```
In net/xfrm/xfrm_device.c (ffffffff819f81ab)
Location: include/linux/netdevice.h:3152
Inline: True
Inline callers:
  - net/xfrm/xfrm_device.c:xfrm_dev_resume
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/core/netpoll.c (ffffffff8196b231)
Location: include/linux/netdevice.h:3166
Inline: True
Inline callers:
  - net/core/netpoll.c:queue_process
```
```
In net/sched/sch_generic.c (ffffffff8198db2b)
Location: include/linux/netdevice.h:3166
Inline: True
Inline callers:
  - net/sched/sch_generic.c:__qdisc_run
  - net/sched/sch_generic.c:__qdisc_run
  - net/sched/sch_generic.c:__qdisc_run
  - net/sched/sch_generic.c:sch_direct_xmit
```
```
In net/xfrm/xfrm_device.c (ffffffff81a2edfb)
Location: include/linux/netdevice.h:3166
Inline: True
Inline callers:
  - net/xfrm/xfrm_device.c:xfrm_dev_resume
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/core/netpoll.c (ffffffff81a3e9e1)
Location: include/linux/netdevice.h:3279
Inline: True
Inline callers:
  - net/core/netpoll.c:queue_process
```
```
In net/sched/sch_generic.c (ffffffff81a65a24)
Location: include/linux/netdevice.h:3279
Inline: True
Inline callers:
  - net/sched/sch_generic.c:sch_direct_xmit
  - net/sched/sch_generic.c:dequeue_skb
  - net/sched/sch_generic.c:dequeue_skb
  - net/sched/sch_generic.c:dequeue_skb
```
```
In net/xfrm/xfrm_device.c (ffffffff81b21d0b)
Location: include/linux/netdevice.h:3279
Inline: True
Inline callers:
  - net/xfrm/xfrm_device.c:xfrm_dev_resume
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
In net/core/netpoll.c (ffffffff81a41781)
Location: include/linux/netdevice.h:3433
Inline: True
Inline callers:
  - net/core/netpoll.c:queue_process
```
```
In net/sched/sch_generic.c (ffffffff81a6db44)
Location: include/linux/netdevice.h:3433
Inline: True
Inline callers:
  - net/sched/sch_generic.c:sch_direct_xmit
  - net/sched/sch_generic.c:dequeue_skb
  - net/sched/sch_generic.c:dequeue_skb
  - net/sched/sch_generic.c:dequeue_skb
```
```
In net/xfrm/xfrm_device.c (ffffffff81b306db)
Location: include/linux/netdevice.h:3433
Inline: True
Inline callers:
  - net/xfrm/xfrm_device.c:xfrm_dev_resume
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
In net/core/dev.c (ffffffff819eef37)
Location: include/linux/netdevice.h:3500
Inline: True
Inline callers:
  - net/core/dev.c:__dev_xmit_skb
```
```
In net/core/netpoll.c (ffffffff81a26811)
Location: include/linux/netdevice.h:3500
Inline: True
Inline callers:
  - net/core/netpoll.c:queue_process
```
```
In net/sched/sch_generic.c (ffffffff81a5638c)
Location: include/linux/netdevice.h:3500
Inline: True
Inline callers:
  - net/sched/sch_generic.c:sch_direct_xmit
  - net/sched/sch_generic.c:dequeue_skb
  - net/sched/sch_generic.c:dequeue_skb
  - net/sched/sch_generic.c:dequeue_skb
  - net/sched/sch_generic.c:qdisc_maybe_clear_missed
```
```
In net/xfrm/xfrm_device.c (ffffffff81b1e00b)
Location: include/linux/netdevice.h:3500
Inline: True
Inline callers:
  - net/xfrm/xfrm_device.c:xfrm_dev_resume
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
In net/core/netpoll.c (ffffffff81adb591)
Location: include/linux/netdevice.h:3512
Inline: True
Inline callers:
  - net/core/netpoll.c:queue_process
```
```
In net/sched/sch_generic.c (ffffffff81b0f154)
Location: include/linux/netdevice.h:3512
Inline: True
Inline callers:
  - net/sched/sch_generic.c:sch_direct_xmit
  - net/sched/sch_generic.c:dequeue_skb
  - net/sched/sch_generic.c:dequeue_skb
  - net/sched/sch_generic.c:dequeue_skb
  - net/sched/sch_generic.c:qdisc_maybe_clear_missed
```
```
In net/xfrm/xfrm_device.c (ffffffff81be2afb)
Location: include/linux/netdevice.h:3512
Inline: True
Inline callers:
  - net/xfrm/xfrm_device.c:xfrm_dev_resume
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
In net/core/netpoll.c (ffffffff81c5ca37)
Location: include/linux/netdevice.h:3303
Inline: True
Inline callers:
  - net/core/netpoll.c:queue_process
```
```
In net/sched/sch_generic.c (ffffffff81c96358)
Location: include/linux/netdevice.h:3303
Inline: True
Inline callers:
  - net/sched/sch_generic.c:sch_direct_xmit
  - net/sched/sch_generic.c:dequeue_skb
  - net/sched/sch_generic.c:dequeue_skb
  - net/sched/sch_generic.c:dequeue_skb
  - net/sched/sch_generic.c:qdisc_maybe_clear_missed
```
```
In net/xfrm/xfrm_device.c (ffffffff81d79c60)
Location: include/linux/netdevice.h:3303
Inline: True
Inline callers:
  - net/xfrm/xfrm_device.c:xfrm_dev_resume
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
In net/core/netpoll.c (ffffffff81e13137)
Location: include/linux/netdevice.h:3328
Inline: True
Inline callers:
  - net/core/netpoll.c:queue_process
```
```
In net/sched/sch_generic.c (ffffffff81e51f48)
Location: include/linux/netdevice.h:3328
Inline: True
Inline callers:
  - net/sched/sch_generic.c:sch_direct_xmit
  - net/sched/sch_generic.c:dequeue_skb
  - net/sched/sch_generic.c:dequeue_skb
  - net/sched/sch_generic.c:dequeue_skb
  - net/sched/sch_generic.c:qdisc_maybe_clear_missed
```
```
In net/xfrm/xfrm_device.c (ffffffff81f46a70)
Location: include/linux/netdevice.h:3328
Inline: True
Inline callers:
  - net/xfrm/xfrm_device.c:xfrm_dev_resume
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
In net/core/netpoll.c (ffffffff81e86a77)
Location: include/linux/netdevice.h:3392
Inline: True
Inline callers:
  - net/core/netpoll.c:queue_process
```
```
In net/sched/sch_generic.c (ffffffff81ead7b8)
Location: include/linux/netdevice.h:3392
Inline: True
Inline callers:
  - net/sched/sch_generic.c:sch_direct_xmit
  - net/sched/sch_generic.c:dequeue_skb
  - net/sched/sch_generic.c:dequeue_skb
  - net/sched/sch_generic.c:dequeue_skb
  - net/sched/sch_generic.c:qdisc_maybe_clear_missed
```
```
In net/xfrm/xfrm_device.c (ffffffff81fa63b0)
Location: include/linux/netdevice.h:3392
Inline: True
Inline callers:
  - net/xfrm/xfrm_device.c:xfrm_dev_resume
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
In net/core/netpoll.c (ffffffff81f48a87)
Location: include/linux/netdevice.h:3471
Inline: True
Inline callers:
  - net/core/netpoll.c:queue_process
```
```
In net/sched/sch_generic.c (ffffffff81f70258)
Location: include/linux/netdevice.h:3471
Inline: True
Inline callers:
  - net/sched/sch_generic.c:sch_direct_xmit
  - net/sched/sch_generic.c:dequeue_skb
  - net/sched/sch_generic.c:dequeue_skb
  - net/sched/sch_generic.c:dequeue_skb
  - net/sched/sch_generic.c:qdisc_maybe_clear_missed
```
```
In net/xfrm/xfrm_device.c (ffffffff820736a0)
Location: include/linux/netdevice.h:3471
Inline: True
Inline callers:
  - net/xfrm/xfrm_device.c:xfrm_dev_resume
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
In net/core/netpoll.c (ffff800010c10dec)
Location: include/linux/netdevice.h:3166
Inline: True
Inline callers:
  - net/core/netpoll.c:queue_process
```
```
In net/sched/sch_generic.c (ffff800010c39210)
Location: include/linux/netdevice.h:3166
Inline: True
Inline callers:
  - net/sched/sch_generic.c:__qdisc_run
  - net/sched/sch_generic.c:__qdisc_run
  - net/sched/sch_generic.c:__qdisc_run
  - net/sched/sch_generic.c:sch_direct_xmit
```
```
In net/xfrm/xfrm_device.c (ffff800010cee1a0)
Location: include/linux/netdevice.h:3166
Inline: True
Inline callers:
  - net/xfrm/xfrm_device.c:xfrm_dev_resume
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
In net/core/netpoll.c (c0d28c48)
Location: include/linux/netdevice.h:3166
Inline: True
Inline callers:
  - net/core/netpoll.c:queue_process
```
```
In net/sched/sch_generic.c (c0d4b568)
Location: include/linux/netdevice.h:3166
Inline: True
Inline callers:
  - net/sched/sch_generic.c:__qdisc_run
  - net/sched/sch_generic.c:__qdisc_run
  - net/sched/sch_generic.c:__qdisc_run
  - net/sched/sch_generic.c:sch_direct_xmit
```
```
In net/xfrm/xfrm_device.c (c0df5d1c)
Location: include/linux/netdevice.h:3166
Inline: True
Inline callers:
  - net/xfrm/xfrm_device.c:xfrm_dev_resume
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/core/netpoll.c (c000000000cfdeb4)
Location: include/linux/netdevice.h:3166
Inline: True
Inline callers:
  - net/core/netpoll.c:queue_process
```
```
In net/sched/sch_generic.c (c000000000d321cc)
Location: include/linux/netdevice.h:3166
Inline: True
Inline callers:
  - net/sched/sch_generic.c:__qdisc_run
  - net/sched/sch_generic.c:__qdisc_run
  - net/sched/sch_generic.c:__qdisc_run
  - net/sched/sch_generic.c:sch_direct_xmit
```
```
In net/xfrm/xfrm_device.c (c000000000e12678)
Location: include/linux/netdevice.h:3166
Inline: True
Inline callers:
  - net/xfrm/xfrm_device.c:xfrm_dev_resume
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/core/netpoll.c (ffffffe00078da8a)
Location: include/linux/netdevice.h:3166
Inline: True
Inline callers:
  - net/core/netpoll.c:queue_process
```
```
In net/sched/sch_generic.c (ffffffe0007aa90c)
Location: include/linux/netdevice.h:3166
Inline: True
Inline callers:
  - net/sched/sch_generic.c:__qdisc_run
  - net/sched/sch_generic.c:__qdisc_run
  - net/sched/sch_generic.c:__qdisc_run
  - net/sched/sch_generic.c:sch_direct_xmit
```
```
In net/xfrm/xfrm_device.c (ffffffe00083b19e)
Location: include/linux/netdevice.h:3166
Inline: True
Inline callers:
  - net/xfrm/xfrm_device.c:xfrm_dev_resume
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/core/netpoll.c (ffffffff8190b201)
Location: include/linux/netdevice.h:3166
Inline: True
Inline callers:
  - net/core/netpoll.c:queue_process
```
```
In net/sched/sch_generic.c (ffffffff8192d99b)
Location: include/linux/netdevice.h:3166
Inline: True
Inline callers:
  - net/sched/sch_generic.c:__qdisc_run
  - net/sched/sch_generic.c:__qdisc_run
  - net/sched/sch_generic.c:__qdisc_run
  - net/sched/sch_generic.c:sch_direct_xmit
```
```
In net/xfrm/xfrm_device.c (ffffffff819ce48b)
Location: include/linux/netdevice.h:3166
Inline: True
Inline callers:
  - net/xfrm/xfrm_device.c:xfrm_dev_resume
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/core/netpoll.c (ffffffff818c4fd4)
Location: include/linux/netdevice.h:3166
Inline: True
Inline callers:
  - net/core/netpoll.c:queue_process
```
```
In net/sched/sch_generic.c (ffffffff818e749b)
Location: include/linux/netdevice.h:3166
Inline: True
Inline callers:
  - net/sched/sch_generic.c:__qdisc_run
  - net/sched/sch_generic.c:__qdisc_run
  - net/sched/sch_generic.c:__qdisc_run
  - net/sched/sch_generic.c:sch_direct_xmit
```
```
In net/xfrm/xfrm_device.c (ffffffff8198b27b)
Location: include/linux/netdevice.h:3166
Inline: True
Inline callers:
  - net/xfrm/xfrm_device.c:xfrm_dev_resume
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
In net/core/netpoll.c (ffffffff8195c231)
Location: include/linux/netdevice.h:3166
Inline: True
Inline callers:
  - net/core/netpoll.c:queue_process
```
```
In net/sched/sch_generic.c (ffffffff8197eb2b)
Location: include/linux/netdevice.h:3166
Inline: True
Inline callers:
  - net/sched/sch_generic.c:__qdisc_run
  - net/sched/sch_generic.c:__qdisc_run
  - net/sched/sch_generic.c:__qdisc_run
  - net/sched/sch_generic.c:sch_direct_xmit
```
```
In net/xfrm/xfrm_device.c (ffffffff81a38f0b)
Location: include/linux/netdevice.h:3166
Inline: True
Inline callers:
  - net/xfrm/xfrm_device.c:xfrm_dev_resume
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/core/netpoll.c (ffffffff8197dbe1)
Location: include/linux/netdevice.h:3166
Inline: True
Inline callers:
  - net/core/netpoll.c:queue_process
```
```
In net/sched/sch_generic.c (ffffffff819a109b)
Location: include/linux/netdevice.h:3166
Inline: True
Inline callers:
  - net/sched/sch_generic.c:__qdisc_run
  - net/sched/sch_generic.c:__qdisc_run
  - net/sched/sch_generic.c:__qdisc_run
  - net/sched/sch_generic.c:sch_direct_xmit
```
```
In net/xfrm/xfrm_device.c (ffffffff81a44930)
Location: include/linux/netdevice.h:3166
Inline: True
Inline callers:
  - net/xfrm/xfrm_device.c:xfrm_dev_resume
```
</details>
</li>
</ul>

## Differences
