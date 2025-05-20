# Function: <code>qdisc_root_sleeping</code>

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
In net/sched/sch_api.c (ffffffff81743489)
Location: include/net/sch_generic.h:292
Inline: True
Inline callers:
  - net/sched/sch_api.c:tc_fill_tclass
  - net/sched/sch_api.c:tc_fill_qdisc
  - net/sched/sch_api.c:qdisc_class_hash_grow
  - net/sched/sch_api.c:qdisc_class_hash_grow
  - net/sched/sch_api.c:qdisc_create
  - net/sched/sch_api.c:tc_modify_qdisc
```
```
In net/sched/cls_api.c (ffffffff81745e8e)
Location: include/net/sch_generic.h:292
Inline: True
Inline callers:
  - net/sched/cls_api.c:tcf_exts_change
  - net/sched/cls_api.c:tcf_exts_change
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
In net/sched/sch_api.c (ffffffff817b0ceb)
Location: include/net/sch_generic.h:271
Inline: True
Inline callers:
  - net/sched/sch_api.c:tc_fill_qdisc
  - net/sched/sch_api.c:tc_modify_qdisc
  - net/sched/sch_api.c:qdisc_create
  - net/sched/sch_api.c:qdisc_class_hash_grow
  - net/sched/sch_api.c:qdisc_class_hash_grow
```
```
In net/sched/cls_api.c (ffffffff817b2ee3)
Location: include/net/sch_generic.h:271
Inline: True
Inline callers:
  - net/sched/cls_api.c:tcf_exts_change
  - net/sched/cls_api.c:tcf_exts_change
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
In net/sched/sch_api.c (ffffffff817e0423)
Location: include/net/sch_generic.h:279
Inline: True
Inline callers:
  - net/sched/sch_api.c:tc_fill_qdisc
  - net/sched/sch_api.c:tc_modify_qdisc
  - net/sched/sch_api.c:qdisc_create
  - net/sched/sch_api.c:qdisc_class_hash_grow
  - net/sched/sch_api.c:qdisc_class_hash_grow
```
```
In net/sched/cls_api.c (ffffffff817e2763)
Location: include/net/sch_generic.h:279
Inline: True
Inline callers:
  - net/sched/cls_api.c:tcf_exts_change
  - net/sched/cls_api.c:tcf_exts_change
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
In net/sched/sch_api.c (ffffffff817ff8aa)
Location: include/net/sch_generic.h:308
Inline: True
Inline callers:
  - net/sched/sch_api.c:tc_fill_qdisc
  - net/sched/sch_api.c:tc_modify_qdisc
  - net/sched/sch_api.c:qdisc_create
  - net/sched/sch_api.c:qdisc_class_hash_grow
  - net/sched/sch_api.c:qdisc_class_hash_grow
```
```
In net/sched/cls_api.c (ffffffff81802043)
Location: include/net/sch_generic.h:308
Inline: True
Inline callers:
  - net/sched/cls_api.c:tcf_exts_change
  - net/sched/cls_api.c:tcf_exts_change
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
In net/sched/sch_api.c (ffffffff8187f268)
Location: include/net/sch_generic.h:315
Inline: True
Inline callers:
  - net/sched/sch_api.c:tc_modify_qdisc
  - net/sched/sch_api.c:qdisc_create
  - net/sched/sch_api.c:tc_fill_qdisc
  - net/sched/sch_api.c:qdisc_class_hash_grow
  - net/sched/sch_api.c:qdisc_class_hash_grow
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
In net/sched/sch_api.c (ffffffff818cfa81)
Location: include/net/sch_generic.h:383
Inline: True
Inline callers:
  - net/sched/sch_api.c:tcf_node_bind
  - net/sched/sch_api.c:tcf_node_bind
  - net/sched/sch_api.c:tc_modify_qdisc
  - net/sched/sch_api.c:qdisc_create
  - net/sched/sch_api.c:tc_fill_qdisc
  - net/sched/sch_api.c:qdisc_class_hash_grow
  - net/sched/sch_api.c:qdisc_class_hash_grow
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
In net/sched/sch_api.c (ffffffff818fb751)
Location: include/net/sch_generic.h:448
Inline: True
Inline callers:
  - net/sched/sch_api.c:tcf_node_bind
  - net/sched/sch_api.c:tcf_node_bind
  - net/sched/sch_api.c:tc_modify_qdisc
  - net/sched/sch_api.c:qdisc_create
  - net/sched/sch_api.c:tc_fill_qdisc
  - net/sched/sch_api.c:qdisc_class_hash_grow
  - net/sched/sch_api.c:qdisc_class_hash_grow
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
In net/sched/sch_api.c (ffffffff8195ca94)
Location: include/net/sch_generic.h:523
Inline: True
Inline callers:
  - net/sched/sch_api.c:tc_modify_qdisc
  - net/sched/sch_api.c:qdisc_create
  - net/sched/sch_api.c:tc_fill_qdisc
  - net/sched/sch_api.c:qdisc_class_hash_grow
  - net/sched/sch_api.c:qdisc_class_hash_grow
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
In net/sched/sch_api.c (ffffffff81990b94)
Location: include/net/sch_generic.h:512
Inline: True
Inline callers:
  - net/sched/sch_api.c:tcf_node_bind
  - net/sched/sch_api.c:tcf_node_bind
  - net/sched/sch_api.c:tc_modify_qdisc
  - net/sched/sch_api.c:qdisc_create
  - net/sched/sch_api.c:tc_fill_qdisc
  - net/sched/sch_api.c:qdisc_class_hash_grow
  - net/sched/sch_api.c:qdisc_class_hash_grow
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
In net/sched/sch_api.c (ffffffff81a69b95)
Location: include/net/sch_generic.h:517
Inline: True
Inline callers:
  - net/sched/sch_api.c:qdisc_change
  - net/sched/sch_api.c:qdisc_create
  - net/sched/sch_api.c:tc_fill_qdisc
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
In net/sched/sch_api.c (ffffffff81a70dd4)
Location: include/net/sch_generic.h:509
Inline: True
Inline callers:
  - net/sched/sch_api.c:tcf_node_bind
  - net/sched/sch_api.c:tcf_node_bind
  - net/sched/sch_api.c:qdisc_change
  - net/sched/sch_api.c:qdisc_create
  - net/sched/sch_api.c:tc_fill_qdisc
  - net/sched/sch_api.c:qdisc_class_hash_grow
  - net/sched/sch_api.c:qdisc_class_hash_grow
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
In net/sched/sch_api.c (ffffffff81a5972b)
Location: include/net/sch_generic.h:556
Inline: True
Inline callers:
  - net/sched/sch_api.c:tcf_node_bind
  - net/sched/sch_api.c:tcf_node_bind
  - net/sched/sch_api.c:tc_modify_qdisc
  - net/sched/sch_api.c:qdisc_create
  - net/sched/sch_api.c:tc_fill_qdisc
  - net/sched/sch_api.c:qdisc_class_hash_grow
  - net/sched/sch_api.c:qdisc_class_hash_grow
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
In net/sched/sch_api.c (ffffffff81b127df)
Location: include/net/sch_generic.h:561
Inline: True
Inline callers:
  - net/sched/sch_api.c:tcf_node_bind
  - net/sched/sch_api.c:tcf_node_bind
  - net/sched/sch_api.c:tc_modify_qdisc
  - net/sched/sch_api.c:qdisc_create
  - net/sched/sch_api.c:tc_fill_qdisc
  - net/sched/sch_api.c:qdisc_class_hash_grow
  - net/sched/sch_api.c:qdisc_class_hash_grow
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/sched/sch_api.c (ffffffff81c9ab1f)
Location: include/net/sch_generic.h:549
Inline: True
Inline callers:
  - net/sched/sch_api.c:tcf_node_bind
  - net/sched/sch_api.c:tcf_node_bind
  - net/sched/sch_api.c:qdisc_class_hash_grow
  - net/sched/sch_api.c:qdisc_class_hash_grow
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/sched/sch_api.c (ffffffff81e572a7)
Location: include/net/sch_generic.h:544
Inline: True
Inline callers:
  - net/sched/sch_api.c:qdisc_class_hash_grow
  - net/sched/sch_api.c:qdisc_class_hash_grow
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/sched/sch_api.c (ffffffff81eb19a7)
Location: include/net/sch_generic.h:553
Inline: True
Inline callers:
  - net/sched/sch_api.c:qdisc_class_hash_grow
  - net/sched/sch_api.c:qdisc_class_hash_grow
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/sched/sch_api.c (ffffffff81f74457)
Location: include/net/sch_generic.h:554
Inline: True
Inline callers:
  - net/sched/sch_api.c:qdisc_class_hash_grow
  - net/sched/sch_api.c:qdisc_class_hash_grow
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
In net/sched/sch_api.c (ffff800010c3d084)
Location: include/net/sch_generic.h:512
Inline: True
Inline callers:
  - net/sched/sch_api.c:tcf_node_bind
  - net/sched/sch_api.c:tcf_node_bind
  - net/sched/sch_api.c:tc_modify_qdisc
  - net/sched/sch_api.c:qdisc_create
  - net/sched/sch_api.c:tc_fill_qdisc
  - net/sched/sch_api.c:qdisc_class_hash_grow
  - net/sched/sch_api.c:qdisc_class_hash_grow
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
In net/sched/sch_api.c (c0d4eb8c)
Location: include/net/sch_generic.h:512
Inline: True
Inline callers:
  - net/sched/sch_api.c:tcf_node_bind
  - net/sched/sch_api.c:tcf_node_bind
  - net/sched/sch_api.c:tc_modify_qdisc
  - net/sched/sch_api.c:qdisc_create
  - net/sched/sch_api.c:tc_fill_qdisc
  - net/sched/sch_api.c:qdisc_class_hash_grow
  - net/sched/sch_api.c:qdisc_class_hash_grow
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
In net/sched/sch_api.c (c000000000d39a30)
Location: include/net/sch_generic.h:512
Inline: True
Inline callers:
  - net/sched/sch_api.c:tc_modify_qdisc
  - net/sched/sch_api.c:qdisc_create
  - net/sched/sch_api.c:tc_fill_qdisc
  - net/sched/sch_api.c:qdisc_class_hash_grow
  - net/sched/sch_api.c:qdisc_class_hash_grow
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
In net/sched/sch_api.c (ffffffe0007ad600)
Location: include/net/sch_generic.h:512
Inline: True
Inline callers:
  - net/sched/sch_api.c:tcf_node_bind
  - net/sched/sch_api.c:tcf_node_bind
  - net/sched/sch_api.c:tc_modify_qdisc
  - net/sched/sch_api.c:qdisc_create
  - net/sched/sch_api.c:tc_fill_qdisc
  - net/sched/sch_api.c:qdisc_class_hash_grow
  - net/sched/sch_api.c:qdisc_class_hash_grow
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
In net/sched/sch_api.c (ffffffff81930a04)
Location: include/net/sch_generic.h:512
Inline: True
Inline callers:
  - net/sched/sch_api.c:tcf_node_bind
  - net/sched/sch_api.c:tcf_node_bind
  - net/sched/sch_api.c:tc_modify_qdisc
  - net/sched/sch_api.c:qdisc_create
  - net/sched/sch_api.c:tc_fill_qdisc
  - net/sched/sch_api.c:qdisc_class_hash_grow
  - net/sched/sch_api.c:qdisc_class_hash_grow
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
In net/sched/sch_api.c (ffffffff818ea504)
Location: include/net/sch_generic.h:512
Inline: True
Inline callers:
  - net/sched/sch_api.c:tcf_node_bind
  - net/sched/sch_api.c:tcf_node_bind
  - net/sched/sch_api.c:tc_modify_qdisc
  - net/sched/sch_api.c:qdisc_create
  - net/sched/sch_api.c:tc_fill_qdisc
  - net/sched/sch_api.c:qdisc_class_hash_grow
  - net/sched/sch_api.c:qdisc_class_hash_grow
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
In net/sched/sch_api.c (ffffffff81981b94)
Location: include/net/sch_generic.h:512
Inline: True
Inline callers:
  - net/sched/sch_api.c:tcf_node_bind
  - net/sched/sch_api.c:tcf_node_bind
  - net/sched/sch_api.c:tc_modify_qdisc
  - net/sched/sch_api.c:qdisc_create
  - net/sched/sch_api.c:tc_fill_qdisc
  - net/sched/sch_api.c:qdisc_class_hash_grow
  - net/sched/sch_api.c:qdisc_class_hash_grow
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
In net/sched/sch_api.c (ffffffff819a40f4)
Location: include/net/sch_generic.h:512
Inline: True
Inline callers:
  - net/sched/sch_api.c:tcf_node_bind
  - net/sched/sch_api.c:tcf_node_bind
  - net/sched/sch_api.c:tc_modify_qdisc
  - net/sched/sch_api.c:qdisc_create
  - net/sched/sch_api.c:tc_fill_qdisc
  - net/sched/sch_api.c:qdisc_class_hash_grow
  - net/sched/sch_api.c:qdisc_class_hash_grow
```
</details>
</li>
</ul>

## Differences
