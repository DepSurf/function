# Function: <code>cgroup_ancestor</code>

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
<details>
<summary>In <code>5.0</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/core/filter.c (ffffffff818d2d7c)
Location: include/linux/cgroup.h:569
Inline: True
Inline callers:
  - net/core/filter.c:bpf_skb_ancestor_cgroup_id
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
In net/core/filter.c (ffffffff8191fe70)
Location: include/linux/cgroup.h:582
Inline: True
Inline callers:
  - net/core/filter.c:bpf_skb_ancestor_cgroup_id
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
In net/core/filter.c (ffffffff819520b5)
Location: include/linux/cgroup.h:584
Inline: True
Inline callers:
  - net/core/filter.c:bpf_skb_ancestor_cgroup_id
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
In kernel/bpf/helpers.c (ffffffff8121488d)
Location: include/linux/cgroup.h:590
Inline: True
Inline callers:
  - kernel/bpf/helpers.c:bpf_get_current_ancestor_cgroup_id
```
```
In net/core/filter.c (ffffffff81a2c165)
Location: include/linux/cgroup.h:590
Inline: True
Inline callers:
  - net/core/filter.c:bpf_sk_ancestor_cgroup_id
  - net/core/filter.c:bpf_skb_ancestor_cgroup_id
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
In kernel/bpf/helpers.c (ffffffff8121636d)
Location: include/linux/cgroup.h:590
Inline: True
Inline callers:
  - kernel/bpf/helpers.c:bpf_get_current_ancestor_cgroup_id
```
```
In net/core/filter.c (ffffffff81a2e890)
Location: include/linux/cgroup.h:590
Inline: True
Inline callers:
  - net/core/filter.c:bpf_sk_ancestor_cgroup_id
  - net/core/filter.c:bpf_skb_ancestor_cgroup_id
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
In kernel/bpf/helpers.c (ffffffff81219080)
Location: include/linux/cgroup.h:590
Inline: True
Inline callers:
  - kernel/bpf/helpers.c:bpf_get_current_ancestor_cgroup_id
```
```
In net/core/filter.c (ffffffff81a15ed9)
Location: include/linux/cgroup.h:590
Inline: True
Inline callers:
  - net/core/filter.c:bpf_sk_ancestor_cgroup_id
  - net/core/filter.c:bpf_skb_ancestor_cgroup_id
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
In kernel/bpf/helpers.c (ffffffff8124fc22)
Location: include/linux/cgroup.h:590
Inline: True
Inline callers:
  - kernel/bpf/helpers.c:bpf_get_current_ancestor_cgroup_id
```
```
In net/core/filter.c (ffffffff81acc057)
Location: include/linux/cgroup.h:590
Inline: True
Inline callers:
  - net/core/filter.c:bpf_sk_ancestor_cgroup_id
  - net/core/filter.c:bpf_skb_ancestor_cgroup_id
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
In kernel/bpf/helpers.c (ffffffff8129705d)
Location: include/linux/cgroup.h:591
Inline: True
Inline callers:
  - kernel/bpf/helpers.c:bpf_get_current_ancestor_cgroup_id
```
```
In net/core/filter.c (ffffffff81c488ac)
Location: include/linux/cgroup.h:591
Inline: True
Inline callers:
  - net/core/filter.c:bpf_sk_ancestor_cgroup_id
  - net/core/filter.c:bpf_skb_ancestor_cgroup_id
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
In kernel/bpf/helpers.c (ffffffff812f1e59)
Location: include/linux/cgroup.h:533
Inline: True
Inline callers:
  - kernel/bpf/helpers.c:bpf_get_current_ancestor_cgroup_id
```
```
In net/core/filter.c (ffffffff81dfd3d9)
Location: include/linux/cgroup.h:533
Inline: True
Inline callers:
  - net/core/filter.c:bpf_sk_ancestor_cgroup_id
  - net/core/filter.c:bpf_skb_ancestor_cgroup_id
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
In kernel/bpf/helpers.c (ffffffff8131e9d9)
Location: include/linux/cgroup.h:532
Inline: True
Inline callers:
  - kernel/bpf/helpers.c:bpf_get_current_ancestor_cgroup_id
```
```
In net/core/filter.c (ffffffff81e6dea4)
Location: include/linux/cgroup.h:532
Inline: True
Inline callers:
  - net/core/filter.c:bpf_sk_ancestor_cgroup_id
  - net/core/filter.c:bpf_skb_ancestor_cgroup_id
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
In kernel/bpf/helpers.c (ffffffff81340e09)
Location: include/linux/cgroup.h:530
Inline: True
Inline callers:
  - kernel/bpf/helpers.c:bpf_get_current_ancestor_cgroup_id
```
```
In net/core/filter.c (ffffffff81f2cf34)
Location: include/linux/cgroup.h:530
Inline: True
Inline callers:
  - net/core/filter.c:bpf_sk_ancestor_cgroup_id
  - net/core/filter.c:bpf_skb_ancestor_cgroup_id
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
In net/core/filter.c (ffff800010bf4294)
Location: include/linux/cgroup.h:584
Inline: True
Inline callers:
  - net/core/filter.c:bpf_skb_ancestor_cgroup_id
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
In net/core/filter.c (c0d0ca68)
Location: include/linux/cgroup.h:584
Inline: True
Inline callers:
  - net/core/filter.c:bpf_skb_ancestor_cgroup_id
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
In net/core/filter.c (c000000000cd93e4)
Location: include/linux/cgroup.h:584
Inline: True
Inline callers:
  - net/core/filter.c:bpf_skb_ancestor_cgroup_id
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
In net/core/filter.c (ffffffe000775740)
Location: include/linux/cgroup.h:584
Inline: True
Inline callers:
  - net/core/filter.c:bpf_skb_ancestor_cgroup_id
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
In net/core/filter.c (ffffffff818f2085)
Location: include/linux/cgroup.h:584
Inline: True
Inline callers:
  - net/core/filter.c:bpf_skb_ancestor_cgroup_id
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
In net/core/filter.c (ffffffff818abeb5)
Location: include/linux/cgroup.h:584
Inline: True
Inline callers:
  - net/core/filter.c:bpf_skb_ancestor_cgroup_id
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
In net/core/filter.c (ffffffff819430b5)
Location: include/linux/cgroup.h:584
Inline: True
Inline callers:
  - net/core/filter.c:bpf_skb_ancestor_cgroup_id
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
In net/core/filter.c (ffffffff819649a5)
Location: include/linux/cgroup.h:584
Inline: True
Inline callers:
  - net/core/filter.c:bpf_skb_ancestor_cgroup_id
```
</details>
</li>
</ul>

## Differences
