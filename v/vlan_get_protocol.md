# Function: <code>vlan_get_protocol</code>

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
In net/core/tso.c (ffffffff817342a2)
Location: include/linux/if_vlan.h:525
Inline: True
Inline callers:
  - net/core/tso.c:tso_start
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
In net/core/dev.c (ffffffff81780858)
Location: include/linux/if_vlan.h:525
Inline: True
Inline callers:
  - net/core/dev.c:__skb_csum_offload_chk
```
```
In net/core/tso.c (ffffffff8179fd62)
Location: include/linux/if_vlan.h:525
Inline: True
Inline callers:
  - net/core/tso.c:tso_start
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
In net/core/tso.c (ffffffff817ce732)
Location: include/linux/if_vlan.h:525
Inline: True
Inline callers:
  - net/core/tso.c:tso_start
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
In net/core/tso.c (ffffffff817edbe2)
Location: include/linux/if_vlan.h:525
Inline: True
Inline callers:
  - net/core/tso.c:tso_start
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
In net/core/tso.c (ffffffff81869e22)
Location: include/linux/if_vlan.h:525
Inline: True
Inline callers:
  - net/core/tso.c:tso_start
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
In net/core/tso.c (ffffffff818b9af2)
Location: include/linux/if_vlan.h:604
Inline: True
Inline callers:
  - net/core/tso.c:tso_start
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
In net/core/tso.c (ffffffff818e08b2)
Location: include/linux/if_vlan.h:639
Inline: True
Inline callers:
  - net/core/tso.c:tso_start
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
In net/core/tso.c (ffffffff8192ef42)
Location: include/linux/if_vlan.h:634
Inline: True
Inline callers:
  - net/core/tso.c:tso_start
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
In net/core/tso.c (ffffffff819611b2)
Location: include/linux/if_vlan.h:623
Inline: True
Inline callers:
  - net/core/tso.c:tso_start
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
In net/core/filter.c (ffffffff81a2d384)
Location: include/linux/if_vlan.h:624
Inline: True
Inline callers:
  - net/core/filter.c:bpf_skb_ecn_set_ce
  - net/core/filter.c:INET_ECN_set_ce
```
```
In net/core/tso.c (ffffffff81a346c5)
Location: include/linux/if_vlan.h:624
Inline: True
Inline callers:
  - net/core/tso.c:tso_start
```
```
In net/sched/cls_api.c (0)
Location: include/linux/if_vlan.h:624
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
In net/core/filter.c (ffffffff81a2ec24)
Location: include/linux/if_vlan.h:624
Inline: True
Inline callers:
  - net/core/filter.c:bpf_skb_ecn_set_ce
  - net/core/filter.c:INET_ECN_set_ce
```
```
In net/core/tso.c (ffffffff81a369c6)
Location: include/linux/if_vlan.h:624
Inline: True
Inline callers:
  - net/core/tso.c:tso_start
```
```
In net/sched/sch_frag.c (ffffffff81a6f65b)
Location: include/linux/if_vlan.h:624
Inline: True
Inline callers:
  - net/sched/sch_frag.c:sch_fragment
  - net/sched/sch_frag.c:sch_fragment
  - net/sched/sch_frag.c:sch_fragment
```
```
In net/sched/cls_api.c (0)
Location: include/linux/if_vlan.h:624
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
In net/core/filter.c (ffffffff81a16283)
Location: include/linux/if_vlan.h:624
Inline: True
Inline callers:
  - net/core/filter.c:bpf_skb_ecn_set_ce
  - net/core/filter.c:INET_ECN_set_ce
```
```
In net/core/tso.c (ffffffff81a1db42)
Location: include/linux/if_vlan.h:624
Inline: True
Inline callers:
  - net/core/tso.c:tso_start
```
```
In net/sched/sch_frag.c (ffffffff81a57f28)
Location: include/linux/if_vlan.h:624
Inline: True
Inline callers:
  - net/sched/sch_frag.c:sch_fragment
  - net/sched/sch_frag.c:sch_fragment
  - net/sched/sch_frag.c:sch_fragment
```
```
In net/sched/cls_api.c (0)
Location: include/linux/if_vlan.h:624
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
In net/core/filter.c (ffffffff81ac71e3)
Location: include/linux/if_vlan.h:624
Inline: True
Inline callers:
  - net/core/filter.c:bpf_skb_ecn_set_ce
  - net/core/filter.c:INET_ECN_set_ce
```
```
In net/core/tso.c (ffffffff81ad15e2)
Location: include/linux/if_vlan.h:624
Inline: True
Inline callers:
  - net/core/tso.c:tso_start
```
```
In net/sched/sch_frag.c (ffffffff81b10ef8)
Location: include/linux/if_vlan.h:624
Inline: True
Inline callers:
  - net/sched/sch_frag.c:sch_fragment
  - net/sched/sch_frag.c:sch_fragment
  - net/sched/sch_frag.c:sch_fragment
```
```
In net/sched/cls_api.c (0)
Location: include/linux/if_vlan.h:624
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
In net/core/filter.c (ffffffff81c42944)
Location: include/linux/if_vlan.h:629
Inline: True
Inline callers:
  - net/core/filter.c:bpf_skb_ecn_set_ce
  - net/core/filter.c:INET_ECN_set_ce
```
```
In net/core/tso.c (ffffffff81c4eed6)
Location: include/linux/if_vlan.h:629
Inline: True
Inline callers:
  - net/core/tso.c:tso_start
```
```
In net/sched/sch_frag.c (ffffffff81c97fc1)
Location: include/linux/if_vlan.h:629
Inline: True
Inline callers:
  - net/sched/sch_frag.c:sch_fragment
  - net/sched/sch_frag.c:sch_fragment
  - net/sched/sch_frag.c:sch_fragment
```
```
In net/sched/cls_api.c (0)
Location: include/linux/if_vlan.h:629
Inline: True
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
Location: include/linux/if_vlan.h:626
Inline: True
Inline callers:
  - net/core/filter.c:bpf_skb_ecn_set_ce
  - net/core/filter.c:INET_ECN_set_ce
```
```
In net/core/tso.c (ffffffff81e03f86)
Location: include/linux/if_vlan.h:626
Inline: True
Inline callers:
  - net/core/tso.c:tso_start
```
```
In net/sched/sch_frag.c (ffffffff81e53f71)
Location: include/linux/if_vlan.h:626
Inline: True
Inline callers:
  - net/sched/sch_frag.c:sch_fragment
  - net/sched/sch_frag.c:sch_fragment
  - net/sched/sch_frag.c:sch_fragment
```
```
In net/sched/cls_api.c (0)
Location: include/linux/if_vlan.h:626
Inline: True
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
Location: include/linux/if_vlan.h:635
Inline: True
Inline callers:
  - net/core/filter.c:bpf_skb_ecn_set_ce
  - net/core/filter.c:INET_ECN_set_ce
```
```
In net/core/tso.c (ffffffff81e76773)
Location: include/linux/if_vlan.h:635
Inline: True
Inline callers:
  - net/core/tso.c:tso_start
```
```
In net/sched/sch_frag.c (ffffffff81eaf7f1)
Location: include/linux/if_vlan.h:635
Inline: True
Inline callers:
  - net/sched/sch_frag.c:sch_fragment
  - net/sched/sch_frag.c:sch_fragment
  - net/sched/sch_frag.c:sch_fragment
```
```
In net/sched/cls_api.c (0)
Location: include/linux/if_vlan.h:635
Inline: True
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
Location: include/linux/if_vlan.h:635
Inline: True
Inline callers:
  - net/core/filter.c:bpf_skb_ecn_set_ce
  - net/core/filter.c:INET_ECN_set_ce
```
```
In net/core/tso.c (ffffffff81f36736)
Location: include/linux/if_vlan.h:635
Inline: True
Inline callers:
  - net/core/tso.c:tso_start
```
```
In net/sched/sch_frag.c (ffffffff81f72271)
Location: include/linux/if_vlan.h:635
Inline: True
Inline callers:
  - net/sched/sch_frag.c:sch_fragment
  - net/sched/sch_frag.c:sch_fragment
  - net/sched/sch_frag.c:sch_fragment
```
```
In net/sched/cls_api.c (0)
Location: include/linux/if_vlan.h:635
Inline: True
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
In net/core/tso.c (ffff800010c04a78)
Location: include/linux/if_vlan.h:623
Inline: True
Inline callers:
  - net/core/tso.c:tso_start
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
In net/core/tso.c (c0d1dedc)
Location: include/linux/if_vlan.h:623
Inline: True
Inline callers:
  - net/core/tso.c:tso_start
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
In net/core/tso.c (c000000000ceea24)
Location: include/linux/if_vlan.h:623
Inline: True
Inline callers:
  - net/core/tso.c:tso_start
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
In net/core/tso.c (ffffffe000783676)
Location: include/linux/if_vlan.h:623
Inline: True
Inline callers:
  - net/core/tso.c:tso_start
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
In net/core/tso.c (ffffffff81901182)
Location: include/linux/if_vlan.h:623
Inline: True
Inline callers:
  - net/core/tso.c:tso_start
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
In net/core/tso.c (ffffffff818bafb2)
Location: include/linux/if_vlan.h:623
Inline: True
Inline callers:
  - net/core/tso.c:tso_start
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
In net/core/tso.c (ffffffff819521b2)
Location: include/linux/if_vlan.h:623
Inline: True
Inline callers:
  - net/core/tso.c:tso_start
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
In net/core/tso.c (ffffffff81973bf2)
Location: include/linux/if_vlan.h:623
Inline: True
Inline callers:
  - net/core/tso.c:tso_start
```
</details>
</li>
</ul>

## Differences
