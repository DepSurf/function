# Function: <code>hash_del_rcu</code>

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
<details>
<summary>In <code>4.10</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/sched/sch_api.c (ffffffff817df677)
Location: include/linux/hashtable.h:113
Inline: True
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
In net/sched/sch_api.c (ffffffff817febc8)
Location: include/linux/hashtable.h:113
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
In kernel/livepatch/shadow.c (ffffffff8110316b)
Location: include/linux/hashtable.h:114
Inline: True
Inline callers:
  - kernel/livepatch/shadow.c:klp_shadow_free_all
  - kernel/livepatch/shadow.c:klp_shadow_free
```
```
In net/sched/sch_api.c (ffffffff8187c854)
Location: include/linux/hashtable.h:114
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
In kernel/livepatch/shadow.c (ffffffff8110b6b5)
Location: include/linux/hashtable.h:114
Inline: True
Inline callers:
  - kernel/livepatch/shadow.c:klp_shadow_free_struct
```
```
In net/sched/sch_api.c (ffffffff818cf073)
Location: include/linux/hashtable.h:114
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
In kernel/livepatch/shadow.c (ffffffff81116ea5)
Location: include/linux/hashtable.h:114
Inline: True
Inline callers:
  - kernel/livepatch/shadow.c:klp_shadow_free_struct
```
```
In net/sched/sch_api.c (ffffffff818fa713)
Location: include/linux/hashtable.h:114
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
In kernel/livepatch/shadow.c (ffffffff81121125)
Location: include/linux/hashtable.h:114
Inline: True
Inline callers:
  - kernel/livepatch/shadow.c:klp_shadow_free_struct
```
```
In net/sched/sch_api.c (ffffffff81959fc5)
Location: include/linux/hashtable.h:114
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
In kernel/livepatch/shadow.c (ffffffff8112d745)
Location: include/linux/hashtable.h:114
Inline: True
Inline callers:
  - kernel/livepatch/shadow.c:klp_shadow_free_struct
```
```
In net/sched/sch_api.c (ffffffff81990465)
Location: include/linux/hashtable.h:114
Inline: True
```
```
In net/sched/cls_api.c (ffffffff819953e0)
Location: include/linux/hashtable.h:114
Inline: True
Inline callers:
  - net/sched/cls_api.c:tcf_proto_destroy
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
In kernel/livepatch/shadow.c (ffffffff8113bec5)
Location: include/linux/hashtable.h:114
Inline: True
Inline callers:
  - kernel/livepatch/shadow.c:klp_shadow_free_struct
```
```
In net/sched/sch_api.c (ffffffff81a67f78)
Location: include/linux/hashtable.h:114
Inline: True
```
```
In net/sched/cls_api.c (ffffffff81a6e230)
Location: include/linux/hashtable.h:114
Inline: True
Inline callers:
  - net/sched/cls_api.c:tcf_proto_destroy
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
In kernel/livepatch/shadow.c (ffffffff811365d5)
Location: include/linux/hashtable.h:114
Inline: True
Inline callers:
  - kernel/livepatch/shadow.c:klp_shadow_free_struct
```
```
In net/sched/sch_api.c (ffffffff81a70688)
Location: include/linux/hashtable.h:114
Inline: True
```
```
In net/sched/cls_api.c (ffffffff81a76c00)
Location: include/linux/hashtable.h:114
Inline: True
Inline callers:
  - net/sched/cls_api.c:tcf_proto_destroy
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
In kernel/livepatch/shadow.c (ffffffff811373c5)
Location: include/linux/hashtable.h:114
Inline: True
Inline callers:
  - kernel/livepatch/shadow.c:klp_shadow_free_struct
```
```
In net/sched/sch_api.c (ffffffff81a58f88)
Location: include/linux/hashtable.h:114
Inline: True
```
```
In net/sched/cls_api.c (ffffffff81a5e9d0)
Location: include/linux/hashtable.h:114
Inline: True
Inline callers:
  - net/sched/cls_api.c:tcf_proto_destroy
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
In kernel/livepatch/shadow.c (ffffffff8115a075)
Location: include/linux/hashtable.h:114
Inline: True
Inline callers:
  - kernel/livepatch/shadow.c:klp_shadow_free_struct
```
```
In net/sched/sch_api.c (ffffffff81b122c9)
Location: include/linux/hashtable.h:114
Inline: True
```
```
In net/sched/cls_api.c (ffffffff81b17ba0)
Location: include/linux/hashtable.h:114
Inline: True
Inline callers:
  - net/sched/cls_api.c:tcf_proto_destroy
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
In kernel/livepatch/shadow.c (ffffffff81183504)
Location: include/linux/hashtable.h:114
Inline: True
```
```
In net/sched/sch_api.c (ffffffff81c995d5)
Location: include/linux/hashtable.h:114
Inline: True
```
```
In net/sched/cls_api.c (ffffffff81c9fa1e)
Location: include/linux/hashtable.h:114
Inline: True
Inline callers:
  - net/sched/cls_api.c:tcf_proto_destroy
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
In kernel/livepatch/shadow.c (ffffffff811be684)
Location: include/linux/hashtable.h:114
Inline: True
```
```
In net/sched/sch_api.c (ffffffff81e558d5)
Location: include/linux/hashtable.h:114
Inline: True
```
```
In net/sched/cls_api.c (ffffffff81e5bcce)
Location: include/linux/hashtable.h:114
Inline: True
Inline callers:
  - net/sched/cls_api.c:tcf_proto_destroy
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
In kernel/livepatch/shadow.c (ffffffff811d10b4)
Location: include/linux/hashtable.h:114
Inline: True
```
```
In net/sched/sch_api.c (ffffffff81eb1175)
Location: include/linux/hashtable.h:114
Inline: True
```
```
In net/sched/cls_api.c (ffffffff81eb84cc)
Location: include/linux/hashtable.h:114
Inline: True
Inline callers:
  - net/sched/cls_api.c:tcf_proto_destroy
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
In kernel/livepatch/shadow.c (ffffffff811e5d34)
Location: include/linux/hashtable.h:114
Inline: True
```
```
In net/sched/sch_api.c (ffffffff81f73c15)
Location: include/linux/hashtable.h:114
Inline: True
```
```
In net/sched/cls_api.c (ffffffff81f7b59c)
Location: include/linux/hashtable.h:114
Inline: True
Inline callers:
  - net/sched/cls_api.c:tcf_proto_destroy
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
In net/sched/sch_api.c (ffff800010c3c3c0)
Location: include/linux/hashtable.h:114
Inline: True
```
```
In net/sched/cls_api.c (ffff800010c41fe4)
Location: include/linux/hashtable.h:114
Inline: True
Inline callers:
  - net/sched/cls_api.c:tcf_proto_destroy
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
In net/sched/sch_api.c (c0d4e304)
Location: include/linux/hashtable.h:114
Inline: True
```
```
In net/sched/cls_api.c (c0d53d78)
Location: include/linux/hashtable.h:114
Inline: True
Inline callers:
  - net/sched/cls_api.c:tcf_proto_destroy
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
In kernel/livepatch/shadow.c (c0000000001f2360)
Location: include/linux/hashtable.h:114
Inline: True
Inline callers:
  - kernel/livepatch/shadow.c:klp_shadow_free_struct
```
```
In net/sched/sch_api.c (c000000000d36038)
Location: include/linux/hashtable.h:114
Inline: True
```
```
In net/sched/cls_api.c (c000000000d3df98)
Location: include/linux/hashtable.h:114
Inline: True
Inline callers:
  - net/sched/cls_api.c:tcf_proto_destroy
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
In net/sched/sch_api.c (ffffffe0007accf0)
Location: include/linux/hashtable.h:114
Inline: True
```
```
In net/sched/cls_api.c (ffffffe0007b1824)
Location: include/linux/hashtable.h:114
Inline: True
Inline callers:
  - net/sched/cls_api.c:tcf_proto_destroy
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
In kernel/livepatch/shadow.c (ffffffff81125d25)
Location: include/linux/hashtable.h:114
Inline: True
Inline callers:
  - kernel/livepatch/shadow.c:klp_shadow_free_struct
```
```
In net/sched/sch_api.c (ffffffff819302d5)
Location: include/linux/hashtable.h:114
Inline: True
```
```
In net/sched/cls_api.c (ffffffff81935250)
Location: include/linux/hashtable.h:114
Inline: True
Inline callers:
  - net/sched/cls_api.c:tcf_proto_destroy
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
In kernel/livepatch/shadow.c (ffffffff81118785)
Location: include/linux/hashtable.h:114
Inline: True
Inline callers:
  - kernel/livepatch/shadow.c:klp_shadow_free_struct
```
```
In net/sched/sch_api.c (ffffffff818e9dd5)
Location: include/linux/hashtable.h:114
Inline: True
```
```
In net/sched/cls_api.c (ffffffff818eed50)
Location: include/linux/hashtable.h:114
Inline: True
Inline callers:
  - net/sched/cls_api.c:tcf_proto_destroy
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
In kernel/livepatch/shadow.c (ffffffff81123c15)
Location: include/linux/hashtable.h:114
Inline: True
Inline callers:
  - kernel/livepatch/shadow.c:klp_shadow_free_struct
```
```
In net/sched/sch_api.c (ffffffff81981465)
Location: include/linux/hashtable.h:114
Inline: True
```
```
In net/sched/cls_api.c (ffffffff819863e0)
Location: include/linux/hashtable.h:114
Inline: True
Inline callers:
  - net/sched/cls_api.c:tcf_proto_destroy
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
In kernel/livepatch/shadow.c (ffffffff81130255)
Location: include/linux/hashtable.h:114
Inline: True
Inline callers:
  - kernel/livepatch/shadow.c:klp_shadow_free_struct
```
```
In net/sched/sch_api.c (ffffffff819a39e5)
Location: include/linux/hashtable.h:114
Inline: True
```
```
In net/sched/cls_api.c (ffffffff819a93e0)
Location: include/linux/hashtable.h:114
Inline: True
Inline callers:
  - net/sched/cls_api.c:tcf_proto_destroy
```
</details>
</li>
</ul>

## Differences
