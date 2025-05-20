# Function: <code>rb_add</code>

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
<details>
<summary>In <code>5.13</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/events/intel/uncore_discovery.c (ffffffff81021e56)
Location: include/linux/rbtree.h:222
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore_discovery.c:uncore_insert_box_info
```
```
In kernel/events/core.c (ffffffff8123eeef)
Location: include/linux/rbtree.h:222
Inline: True
Inline callers:
  - kernel/events/core.c:perf_event_groups_insert
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
In arch/x86/events/intel/uncore_discovery.c (ffffffff810259ba)
Location: include/linux/rbtree.h:195
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore_discovery.c:uncore_insert_box_info
```
```
In kernel/sched/core.c (ffffffff810f1e00)
Location: include/linux/rbtree.h:195
Inline: True
```
```
In kernel/events/core.c (ffffffff8127991f)
Location: include/linux/rbtree.h:195
Inline: True
Inline callers:
  - kernel/events/core.c:perf_event_groups_insert
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
In arch/x86/events/intel/uncore_discovery.c (ffffffff810299a7)
Location: include/linux/rbtree.h:195
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore_discovery.c:uncore_insert_box_info
```
```
In kernel/sched/core.c (ffffffff8110db80)
Location: include/linux/rbtree.h:195
Inline: True
```
```
In kernel/events/core.c (ffffffff812ccb04)
Location: include/linux/rbtree.h:195
Inline: True
Inline callers:
  - kernel/events/core.c:perf_event_groups_insert
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
In arch/x86/events/intel/uncore_discovery.c (ffffffff81030417)
Location: include/linux/rbtree.h:195
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore_discovery.c:uncore_insert_box_info
```
```
In kernel/sched/core.c (ffffffff811348b0)
Location: include/linux/rbtree.h:195
Inline: True
```
```
In kernel/events/core.c (ffffffff81334af6)
Location: include/linux/rbtree.h:195
Inline: True
Inline callers:
  - kernel/events/core.c:perf_event_groups_insert
```
```
In fs/xattr.c (ffffffff814b7614)
Location: include/linux/rbtree.h:195
Inline: True
Inline callers:
  - fs/xattr.c:simple_xattr_add
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
In arch/x86/events/intel/uncore_discovery.c (ffffffff8103050d)
Location: include/linux/rbtree.h:195
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore_discovery.c:uncore_insert_box_info
```
```
In kernel/sched/core.c (ffffffff81143ab0)
Location: include/linux/rbtree.h:195
Inline: True
```
```
In kernel/events/core.c (ffffffff81365836)
Location: include/linux/rbtree.h:195
Inline: True
Inline callers:
  - kernel/events/core.c:perf_event_groups_insert
```
```
In fs/xattr.c (ffffffff814ec464)
Location: include/linux/rbtree.h:195
Inline: True
Inline callers:
  - fs/xattr.c:simple_xattr_add
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
In arch/x86/events/intel/uncore_discovery.c (ffffffff810367dd)
Location: include/linux/rbtree.h:195
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore_discovery.c:uncore_insert_box_info
```
```
In kernel/sched/core.c (ffffffff8114efd0)
Location: include/linux/rbtree.h:195
Inline: True
```
```
In kernel/events/core.c (ffffffff8138e956)
Location: include/linux/rbtree.h:195
Inline: True
Inline callers:
  - kernel/events/core.c:perf_event_groups_insert
```
```
In fs/xattr.c (ffffffff81520344)
Location: include/linux/rbtree.h:195
Inline: True
Inline callers:
  - fs/xattr.c:simple_xattr_add
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
