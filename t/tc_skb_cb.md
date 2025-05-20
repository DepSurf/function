# Function: <code>tc_skb_cb</code>

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
In <code>4.18</code>: Absent ⚠️
</li>
<li>
In <code>5.0</code>: Absent ⚠️
</li>
<li>
In <code>5.3</code>: Absent ⚠️
</li>
<li>
In <code>5.4</code>: Absent ⚠️
</li>
<li>
In <code>5.8</code>: Absent ⚠️
</li>
<li>
In <code>5.11</code>: Absent ⚠️
</li>
<li>
In <code>5.13</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>5.15</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff81aa1833)
Location: include/net/pkt_sched.h:206
Inline: True
Inline callers:
  - net/core/dev.c:__dev_queue_xmit
  - net/core/dev.c:__dev_queue_xmit
```
```
In net/sched/sch_frag.c (ffffffff81b11325)
Location: include/net/pkt_sched.h:206
Inline: True
Inline callers:
  - net/sched/sch_frag.c:sch_frag_xmit_hook
```
```
In net/sched/cls_api.c (ffffffff81b16955)
Location: include/net/pkt_sched.h:206
Inline: True
Inline callers:
  - net/sched/cls_api.c:tcf_classify
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
In net/core/dev.c (ffffffff81c198a8)
Location: include/net/pkt_sched.h:217
Inline: True
Inline callers:
  - net/core/dev.c:__dev_queue_xmit
  - net/core/dev.c:__dev_queue_xmit
```
```
In net/sched/sch_frag.c (ffffffff81c98405)
Location: include/net/pkt_sched.h:217
Inline: True
Inline callers:
  - net/sched/sch_frag.c:sch_frag_xmit_hook
```
```
In net/sched/cls_api.c (ffffffff81c9e07f)
Location: include/net/pkt_sched.h:217
Inline: True
Inline callers:
  - net/sched/cls_api.c:tcf_classify
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
In net/core/dev.c (ffffffff81dca8e4)
Location: include/net/pkt_sched.h:227
Inline: True
Inline callers:
  - net/core/dev.c:__dev_queue_xmit
  - net/core/dev.c:__dev_queue_xmit
```
```
In net/sched/sch_frag.c (ffffffff81e54415)
Location: include/net/pkt_sched.h:227
Inline: True
Inline callers:
  - net/sched/sch_frag.c:sch_frag_xmit_hook
```
```
In net/sched/cls_api.c (ffffffff81e5a78f)
Location: include/net/pkt_sched.h:227
Inline: True
Inline callers:
  - net/sched/cls_api.c:tcf_classify
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
In net/core/dev.c (ffffffff81e3b46a)
Location: include/net/pkt_sched.h:288
Inline: True
Inline callers:
  - net/core/dev.c:__dev_queue_xmit
  - net/core/dev.c:__dev_queue_xmit
```
```
In net/sched/sch_frag.c (ffffffff81eafcb5)
Location: include/net/pkt_sched.h:288
Inline: True
Inline callers:
  - net/sched/sch_frag.c:sch_frag_xmit_hook
```
```
In net/sched/cls_api.c (ffffffff81eb63b4)
Location: include/net/pkt_sched.h:288
Inline: True
Inline callers:
  - net/sched/cls_api.c:tcf_classify
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
In net/core/dev.c (ffffffff81eedf4c)
Location: include/net/sch_generic.h:1053
Inline: True
Inline callers:
  - net/core/dev.c:tc_run
  - net/core/dev.c:tc_run
  - net/core/dev.c:tc_run
  - net/core/dev.c:tc_run
  - net/core/dev.c:__dev_xmit_skb
  - net/core/dev.c:__dev_xmit_skb
```
```
In net/sched/sch_frag.c (ffffffff81f72725)
Location: include/net/sch_generic.h:1053
Inline: True
Inline callers:
  - net/sched/sch_frag.c:sch_frag_xmit_hook
```
```
In net/sched/cls_api.c (ffffffff81f790b4)
Location: include/net/sch_generic.h:1053
Inline: True
Inline callers:
  - net/sched/cls_api.c:tcf_classify
  - net/sched/cls_api.c:tcf_classify
  - net/sched/cls_api.c:__tcf_classify
  - net/sched/cls_api.c:__tcf_classify
```
```
In net/sched/act_api.c (ffffffff81f802d5)
Location: include/net/sch_generic.h:1053
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
In <code>arm64</code>: Absent ⚠️
</li>
<li>
In <code>armhf</code>: Absent ⚠️
</li>
<li>
In <code>ppc64el</code>: Absent ⚠️
</li>
<li>
In <code>riscv64</code>: Absent ⚠️
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
In <code>aws</code>: Absent ⚠️
</li>
<li>
In <code>azure</code>: Absent ⚠️
</li>
<li>
In <code>gcp</code>: Absent ⚠️
</li>
<li>
In <code>lowlatency</code>: Absent ⚠️
</li>
</ul>

## Differences
