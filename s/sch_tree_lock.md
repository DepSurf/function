# Function: <code>sch_tree_lock</code>

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
In net/sched/sch_api.c (ffffffff81744629)
Location: include/net/sch_generic.h:329
Inline: True
Inline callers:
  - net/sched/sch_api.c:qdisc_class_hash_grow
```
```
In net/sched/cls_api.c (ffffffff81745e8e)
Location: include/net/sch_generic.h:329
Inline: True
Inline callers:
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
In net/sched/sch_api.c (ffffffff817b0999)
Location: include/net/sch_generic.h:316
Inline: True
Inline callers:
  - net/sched/sch_api.c:qdisc_class_hash_grow
```
```
In net/sched/cls_api.c (ffffffff817b2ee3)
Location: include/net/sch_generic.h:316
Inline: True
Inline callers:
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
In net/sched/sch_api.c (ffffffff817e00d9)
Location: include/net/sch_generic.h:324
Inline: True
Inline callers:
  - net/sched/sch_api.c:qdisc_class_hash_grow
```
```
In net/sched/cls_api.c (ffffffff817e2763)
Location: include/net/sch_generic.h:324
Inline: True
Inline callers:
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
In net/sched/sch_api.c (ffffffff817ff270)
Location: include/net/sch_generic.h:353
Inline: True
Inline callers:
  - net/sched/sch_api.c:qdisc_class_hash_grow
```
```
In net/sched/cls_api.c (ffffffff81802043)
Location: include/net/sch_generic.h:353
Inline: True
Inline callers:
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
In net/sched/sch_api.c (ffffffff8187cfde)
Location: include/net/sch_generic.h:360
Inline: True
Inline callers:
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
Location: include/net/sch_generic.h:428
Inline: True
Inline callers:
  - net/sched/sch_api.c:tcf_node_bind
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
Location: include/net/sch_generic.h:493
Inline: True
Inline callers:
  - net/sched/sch_api.c:tcf_node_bind
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
In net/sched/sch_api.c (ffffffff8195b65e)
Location: include/net/sch_generic.h:568
Inline: True
Inline callers:
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
Location: include/net/sch_generic.h:557
Inline: True
Inline callers:
  - net/sched/sch_api.c:tcf_node_bind
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
In net/sched/sch_api.c (ffffffff81a686c4)
Location: include/net/sch_generic.h:562
Inline: True
Inline callers:
  - net/sched/sch_api.c:tcf_node_bind
  - net/sched/sch_api.c:qdisc_class_hash_grow
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
Location: include/net/sch_generic.h:554
Inline: True
Inline callers:
  - net/sched/sch_api.c:tcf_node_bind
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
In net/sched/sch_api.c (ffffffff81a59724)
Location: include/net/sch_generic.h:601
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
<summary>In <code>5.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/sched/sch_api.c (ffffffff81b127d8)
Location: include/net/sch_generic.h:606
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
<summary>In <code>5.19</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/sched/sch_api.c (ffffffff81c9ab18)
Location: include/net/sch_generic.h:586
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
In net/sched/sch_api.c (ffffffff81e57177)
Location: include/net/sch_generic.h:562
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
In net/sched/sch_api.c (ffffffff81eb1877)
Location: include/net/sch_generic.h:571
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
In net/sched/sch_api.c (ffffffff81f74327)
Location: include/net/sch_generic.h:572
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
Location: include/net/sch_generic.h:557
Inline: True
Inline callers:
  - net/sched/sch_api.c:tcf_node_bind
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
Location: include/net/sch_generic.h:557
Inline: True
Inline callers:
  - net/sched/sch_api.c:tcf_node_bind
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
In net/sched/sch_api.c (c000000000d37ff4)
Location: include/net/sch_generic.h:557
Inline: True
Inline callers:
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
Location: include/net/sch_generic.h:557
Inline: True
Inline callers:
  - net/sched/sch_api.c:tcf_node_bind
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
Location: include/net/sch_generic.h:557
Inline: True
Inline callers:
  - net/sched/sch_api.c:tcf_node_bind
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
Location: include/net/sch_generic.h:557
Inline: True
Inline callers:
  - net/sched/sch_api.c:tcf_node_bind
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
Location: include/net/sch_generic.h:557
Inline: True
Inline callers:
  - net/sched/sch_api.c:tcf_node_bind
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
Location: include/net/sch_generic.h:557
Inline: True
Inline callers:
  - net/sched/sch_api.c:tcf_node_bind
  - net/sched/sch_api.c:qdisc_class_hash_grow
```
</details>
</li>
</ul>

## Differences
