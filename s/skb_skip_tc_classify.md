# Function: <code>skb_skip_tc_classify</code>

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
<details>
<summary>In <code>4.13</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff817ce77b)
Location: include/net/sch_generic.h:455
Inline: True
Inline callers:
  - net/core/dev.c:__netif_receive_skb_core
```
```
In net/sched/act_api.c (ffffffff818037d5)
Location: include/net/sch_generic.h:455
Inline: True
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
In net/core/dev.c (ffffffff8184800c)
Location: include/net/sch_generic.h:470
Inline: True
Inline callers:
  - net/core/dev.c:__netif_receive_skb_core
```
```
In net/sched/act_api.c (ffffffff81881cc5)
Location: include/net/sch_generic.h:470
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
In net/core/dev.c (ffffffff81892054)
Location: include/net/sch_generic.h:541
Inline: True
Inline callers:
  - net/core/dev.c:__netif_receive_skb_core
```
```
In net/sched/act_api.c (ffffffff818d5515)
Location: include/net/sch_generic.h:541
Inline: True
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
In net/core/dev.c (ffffffff818b5eb2)
Location: include/net/sch_generic.h:640
Inline: True
Inline callers:
  - net/core/dev.c:__netif_receive_skb_core
```
```
In net/sched/act_api.c (ffffffff819020f5)
Location: include/net/sch_generic.h:640
Inline: True
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
In net/core/dev.c (ffffffff81901e58)
Location: include/net/sch_generic.h:714
Inline: True
Inline callers:
  - net/core/dev.c:__netif_receive_skb_core
```
```
In net/sched/act_api.c (ffffffff81963555)
Location: include/net/sch_generic.h:714
Inline: True
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
In net/core/dev.c (ffffffff81934098)
Location: include/net/sch_generic.h:687
Inline: True
Inline callers:
  - net/core/dev.c:__netif_receive_skb_core
```
```
In net/sched/act_api.c (ffffffff8199a0d5)
Location: include/net/sch_generic.h:687
Inline: True
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
In net/core/dev.c (ffffffff81a08a9c)
Location: include/net/sch_generic.h:692
Inline: True
Inline callers:
  - net/core/dev.c:__netif_receive_skb_core
```
```
In net/sched/act_api.c (ffffffff81a72745)
Location: include/net/sch_generic.h:692
Inline: True
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
In net/core/dev.c (ffffffff81a0a044)
Location: include/net/sch_generic.h:684
Inline: True
Inline callers:
  - net/core/dev.c:__netif_receive_skb_core
```
```
In net/sched/act_api.c (ffffffff81a7b305)
Location: include/net/sch_generic.h:684
Inline: True
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
In net/core/dev.c (ffffffff819f09d5)
Location: include/net/sch_generic.h:737
Inline: True
```
```
In net/sched/act_api.c (ffffffff81a63f84)
Location: include/net/sch_generic.h:737
Inline: True
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
In net/core/dev.c (ffffffff81aa2335)
Location: include/net/sch_generic.h:744
Inline: True
```
```
In net/sched/act_api.c (ffffffff81b1d304)
Location: include/net/sch_generic.h:744
Inline: True
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
In net/core/dev.c (ffffffff81c1a64e)
Location: include/net/sch_generic.h:724
Inline: True
```
```
In net/sched/act_api.c (ffffffff81ca45b1)
Location: include/net/sch_generic.h:724
Inline: True
Inline callers:
  - net/sched/act_api.c:tcf_action_exec
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
In net/core/dev.c (ffffffff81dcb6f8)
Location: include/net/sch_generic.h:703
Inline: True
```
```
In net/sched/act_api.c (ffffffff81e60f91)
Location: include/net/sch_generic.h:703
Inline: True
Inline callers:
  - net/sched/act_api.c:tcf_action_exec
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
In net/core/dev.c (ffffffff81e3c288)
Location: include/net/sch_generic.h:713
Inline: True
```
```
In net/sched/act_api.c (ffffffff81ebcf94)
Location: include/net/sch_generic.h:713
Inline: True
Inline callers:
  - net/sched/act_api.c:tcf_action_exec
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
In net/core/dev.c (ffffffff81efa7a8)
Location: include/net/sch_generic.h:741
Inline: True
```
```
In net/sched/act_api.c (ffffffff81f80195)
Location: include/net/sch_generic.h:741
Inline: True
Inline callers:
  - net/sched/act_api.c:tcf_action_exec
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
In net/core/dev.c (ffff800010bd241c)
Location: include/net/sch_generic.h:687
Inline: True
Inline callers:
  - net/core/dev.c:__netif_receive_skb_core
```
```
In net/sched/act_api.c (ffff800010c46b2c)
Location: include/net/sch_generic.h:687
Inline: True
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
In net/core/dev.c (c0cecfdc)
Location: include/net/sch_generic.h:687
Inline: True
Inline callers:
  - net/core/dev.c:__netif_receive_skb_core
```
```
In net/sched/act_api.c (c0d57d34)
Location: include/net/sch_generic.h:687
Inline: True
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
In net/core/dev.c (c000000000cb0a58)
Location: include/net/sch_generic.h:687
Inline: True
Inline callers:
  - net/core/dev.c:__netif_receive_skb_core
```
```
In net/sched/act_api.c (c000000000d43f24)
Location: include/net/sch_generic.h:687
Inline: True
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
In net/core/dev.c (ffffffe00075c8a2)
Location: include/net/sch_generic.h:687
Inline: True
Inline callers:
  - net/core/dev.c:__netif_receive_skb_core
```
```
In net/sched/act_api.c (ffffffe0007b50fe)
Location: include/net/sch_generic.h:687
Inline: True
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
In net/core/dev.c (ffffffff818d4098)
Location: include/net/sch_generic.h:687
Inline: True
Inline callers:
  - net/core/dev.c:__netif_receive_skb_core
```
```
In net/sched/act_api.c (ffffffff81939f45)
Location: include/net/sch_generic.h:687
Inline: True
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
In net/core/dev.c (ffffffff8188df28)
Location: include/net/sch_generic.h:687
Inline: True
Inline callers:
  - net/core/dev.c:__netif_receive_skb_core
```
```
In net/sched/act_api.c (ffffffff818f3a45)
Location: include/net/sch_generic.h:687
Inline: True
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
In net/core/dev.c (ffffffff81925098)
Location: include/net/sch_generic.h:687
Inline: True
Inline callers:
  - net/core/dev.c:__netif_receive_skb_core
```
```
In net/sched/act_api.c (ffffffff8198b0d5)
Location: include/net/sch_generic.h:687
Inline: True
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
In net/core/dev.c (ffffffff81946578)
Location: include/net/sch_generic.h:687
Inline: True
Inline callers:
  - net/core/dev.c:__netif_receive_skb_core
```
```
In net/sched/act_api.c (ffffffff819ad945)
Location: include/net/sch_generic.h:687
Inline: True
```
</details>
</li>
</ul>

## Differences
