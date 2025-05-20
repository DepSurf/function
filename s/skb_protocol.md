# Function: <code>skb_protocol</code>

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
<details>
<summary>In <code>5.8</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/core/filter.c (ffffffff81a2d384)
Location: include/linux/if_vlan.h:632
Inline: True
Inline callers:
  - net/core/filter.c:bpf_skb_ecn_set_ce
  - net/core/filter.c:bpf_skb_ecn_set_ce
  - net/core/filter.c:INET_ECN_set_ce
  - net/core/filter.c:INET_ECN_set_ce
```
```
In net/sched/cls_api.c (ffffffff81a6bd23)
Location: include/linux/if_vlan.h:632
Inline: True
Inline callers:
  - net/sched/cls_api.c:__tcf_classify
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
In net/core/filter.c (ffffffff81a2ec24)
Location: include/linux/if_vlan.h:632
Inline: True
Inline callers:
  - net/core/filter.c:bpf_skb_ecn_set_ce
  - net/core/filter.c:bpf_skb_ecn_set_ce
  - net/core/filter.c:INET_ECN_set_ce
  - net/core/filter.c:INET_ECN_set_ce
```
```
In net/sched/sch_frag.c (ffffffff81a6f65b)
Location: include/linux/if_vlan.h:632
Inline: True
Inline callers:
  - net/sched/sch_frag.c:sch_fragment
  - net/sched/sch_frag.c:sch_fragment
  - net/sched/sch_frag.c:sch_fragment
  - net/sched/sch_frag.c:sch_fragment
  - net/sched/sch_frag.c:sch_fragment
  - net/sched/sch_frag.c:sch_fragment
```
```
In net/sched/cls_api.c (ffffffff81a745b3)
Location: include/linux/if_vlan.h:632
Inline: True
Inline callers:
  - net/sched/cls_api.c:__tcf_classify
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
In net/core/filter.c (ffffffff81a16283)
Location: include/linux/if_vlan.h:632
Inline: True
Inline callers:
  - net/core/filter.c:bpf_skb_ecn_set_ce
  - net/core/filter.c:bpf_skb_ecn_set_ce
  - net/core/filter.c:INET_ECN_set_ce
  - net/core/filter.c:INET_ECN_set_ce
```
```
In net/sched/sch_frag.c (ffffffff81a57f28)
Location: include/linux/if_vlan.h:632
Inline: True
Inline callers:
  - net/sched/sch_frag.c:sch_fragment
  - net/sched/sch_frag.c:sch_fragment
  - net/sched/sch_frag.c:sch_fragment
  - net/sched/sch_frag.c:sch_fragment
  - net/sched/sch_frag.c:sch_fragment
  - net/sched/sch_frag.c:sch_fragment
```
```
In net/sched/cls_api.c (ffffffff81a5d133)
Location: include/linux/if_vlan.h:632
Inline: True
Inline callers:
  - net/sched/cls_api.c:__tcf_classify
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
In net/core/filter.c (ffffffff81ac71e3)
Location: include/linux/if_vlan.h:632
Inline: True
Inline callers:
  - net/core/filter.c:bpf_skb_ecn_set_ce
  - net/core/filter.c:bpf_skb_ecn_set_ce
  - net/core/filter.c:INET_ECN_set_ce
  - net/core/filter.c:INET_ECN_set_ce
```
```
In net/sched/sch_frag.c (ffffffff81b10ef8)
Location: include/linux/if_vlan.h:632
Inline: True
Inline callers:
  - net/sched/sch_frag.c:sch_fragment
  - net/sched/sch_frag.c:sch_fragment
  - net/sched/sch_frag.c:sch_fragment
  - net/sched/sch_frag.c:sch_fragment
  - net/sched/sch_frag.c:sch_fragment
  - net/sched/sch_frag.c:sch_fragment
```
```
In net/sched/cls_api.c (ffffffff81b162d3)
Location: include/linux/if_vlan.h:632
Inline: True
Inline callers:
  - net/sched/cls_api.c:__tcf_classify
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
In net/core/filter.c (ffffffff81c42944)
Location: include/linux/if_vlan.h:637
Inline: True
Inline callers:
  - net/core/filter.c:bpf_skb_ecn_set_ce
  - net/core/filter.c:bpf_skb_ecn_set_ce
  - net/core/filter.c:INET_ECN_set_ce
  - net/core/filter.c:INET_ECN_set_ce
```
```
In net/sched/sch_frag.c (ffffffff81c97fc1)
Location: include/linux/if_vlan.h:637
Inline: True
Inline callers:
  - net/sched/sch_frag.c:sch_fragment
  - net/sched/sch_frag.c:sch_fragment
  - net/sched/sch_frag.c:sch_fragment
  - net/sched/sch_frag.c:sch_fragment
  - net/sched/sch_frag.c:sch_fragment
  - net/sched/sch_frag.c:sch_fragment
```
```
In net/sched/cls_api.c (ffffffff81c9db73)
Location: include/linux/if_vlan.h:637
Inline: True
Inline callers:
  - net/sched/cls_api.c:__tcf_classify
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
In net/core/filter.c (ffffffff81df7934)
Location: include/linux/if_vlan.h:634
Inline: True
Inline callers:
  - net/core/filter.c:bpf_skb_ecn_set_ce
  - net/core/filter.c:bpf_skb_ecn_set_ce
  - net/core/filter.c:INET_ECN_set_ce
  - net/core/filter.c:INET_ECN_set_ce
```
```
In net/sched/sch_frag.c (ffffffff81e53f71)
Location: include/linux/if_vlan.h:634
Inline: True
Inline callers:
  - net/sched/sch_frag.c:sch_fragment
  - net/sched/sch_frag.c:sch_fragment
  - net/sched/sch_frag.c:sch_fragment
  - net/sched/sch_frag.c:sch_fragment
  - net/sched/sch_frag.c:sch_fragment
  - net/sched/sch_frag.c:sch_fragment
```
```
In net/sched/cls_api.c (ffffffff81e5a1ab)
Location: include/linux/if_vlan.h:634
Inline: True
Inline callers:
  - net/sched/cls_api.c:__tcf_classify
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
In net/core/filter.c (ffffffff81e69634)
Location: include/linux/if_vlan.h:660
Inline: True
Inline callers:
  - net/core/filter.c:bpf_skb_ecn_set_ce
  - net/core/filter.c:bpf_skb_ecn_set_ce
  - net/core/filter.c:INET_ECN_set_ce
  - net/core/filter.c:INET_ECN_set_ce
```
```
In net/sched/sch_frag.c (ffffffff81eaf7f1)
Location: include/linux/if_vlan.h:660
Inline: True
Inline callers:
  - net/sched/sch_frag.c:sch_fragment
  - net/sched/sch_frag.c:sch_fragment
  - net/sched/sch_frag.c:sch_fragment
  - net/sched/sch_frag.c:sch_fragment
  - net/sched/sch_frag.c:sch_fragment
  - net/sched/sch_frag.c:sch_fragment
```
```
In net/sched/cls_api.c (ffffffff81eb6091)
Location: include/linux/if_vlan.h:660
Inline: True
Inline callers:
  - net/sched/cls_api.c:__tcf_classify
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
In net/core/filter.c (ffffffff81f28c14)
Location: include/linux/if_vlan.h:660
Inline: True
Inline callers:
  - net/core/filter.c:bpf_skb_ecn_set_ce
  - net/core/filter.c:bpf_skb_ecn_set_ce
  - net/core/filter.c:INET_ECN_set_ce
  - net/core/filter.c:INET_ECN_set_ce
```
```
In net/sched/sch_frag.c (ffffffff81f72271)
Location: include/linux/if_vlan.h:660
Inline: True
Inline callers:
  - net/sched/sch_frag.c:sch_fragment
  - net/sched/sch_frag.c:sch_fragment
  - net/sched/sch_frag.c:sch_fragment
  - net/sched/sch_frag.c:sch_fragment
  - net/sched/sch_frag.c:sch_fragment
  - net/sched/sch_frag.c:sch_fragment
```
```
In net/sched/cls_api.c (ffffffff81f78e5d)
Location: include/linux/if_vlan.h:660
Inline: True
Inline callers:
  - net/sched/cls_api.c:__tcf_classify
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
