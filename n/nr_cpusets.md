# Function: <code>nr_cpusets</code>

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
In kernel/cpuset.c (ffffffff8111a83e)
Location: include/linux/cpuset.h:25
Inline: True
Inline callers:
  - kernel/cpuset.c:generate_sched_domains
```
```
In mm/oom_kill.c (ffffffff81191103)
Location: include/linux/cpuset.h:25
Inline: True
```
```
In mm/page_alloc.c (ffffffff81196007)
Location: include/linux/cpuset.h:25
Inline: True
Inline callers:
  - mm/page_alloc.c:get_page_from_freelist
```
```
In mm/vmscan.c (ffffffff811a2a33)
Location: include/linux/cpuset.h:25
Inline: True
Inline callers:
  - mm/vmscan.c:wakeup_kswapd
  - mm/vmscan.c:do_try_to_free_pages
```
```
In mm/hugetlb.c (ffffffff811dca48)
Location: include/linux/cpuset.h:25
Inline: True
Inline callers:
  - mm/hugetlb.c:alloc_huge_page
```
```
In mm/slub.c (ffffffff811eaaf3)
Location: include/linux/cpuset.h:25
Inline: True
Inline callers:
  - mm/slub.c:___slab_alloc
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/cpuset.c (ffffffff8112279c)
Location: include/linux/cpuset.h:25
Inline: True
Inline callers:
  - kernel/cpuset.c:generate_sched_domains
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
In kernel/cpuset.c (ffffffff8112c843)
Location: include/linux/cpuset.h:25
Inline: True
Inline callers:
  - kernel/cpuset.c:generate_sched_domains
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
In kernel/cgroup/cpuset.c (ffffffff8112dabb)
Location: include/linux/cpuset.h:40
Inline: True
Inline callers:
  - kernel/cgroup/cpuset.c:generate_sched_domains
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
In kernel/cgroup/cpuset.c (ffffffff8113a64a)
Location: kernel/cgroup/cpuset.c:591
Inline: True
Inline callers:
  - kernel/cgroup/cpuset.c:generate_sched_domains
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
In kernel/cgroup/cpuset.c (ffffffff81149b50)
Location: kernel/cgroup/cpuset.c:591
Inline: True
Inline callers:
  - kernel/cgroup/cpuset.c:rebuild_sched_domains_locked
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
In kernel/cgroup/cpuset.c (ffffffff811557b9)
Location: kernel/cgroup/cpuset.c:700
Inline: True
Inline callers:
  - kernel/cgroup/cpuset.c:rebuild_sched_domains_locked
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
In kernel/cgroup/cpuset.c (ffffffff81162a9c)
Location: kernel/cgroup/cpuset.c:662
Inline: True
Inline callers:
  - kernel/cgroup/cpuset.c:generate_sched_domains
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
In kernel/cgroup/cpuset.c (ffffffff8116e77c)
Location: kernel/cgroup/cpuset.c:674
Inline: True
Inline callers:
  - kernel/cgroup/cpuset.c:generate_sched_domains
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
In kernel/cgroup/cpuset.c (ffffffff8117f9fc)
Location: kernel/cgroup/cpuset.c:678
Inline: True
Inline callers:
  - kernel/cgroup/cpuset.c:generate_sched_domains
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
In kernel/cgroup/cpuset.c (ffffffff8117cb2c)
Location: kernel/cgroup/cpuset.c:678
Inline: True
Inline callers:
  - kernel/cgroup/cpuset.c:generate_sched_domains
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
In kernel/cgroup/cpuset.c (ffffffff8117bcac)
Location: kernel/cgroup/cpuset.c:678
Inline: True
Inline callers:
  - kernel/cgroup/cpuset.c:generate_sched_domains
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
In kernel/cgroup/cpuset.c (ffffffff811a383c)
Location: kernel/cgroup/cpuset.c:706
Inline: True
Inline callers:
  - kernel/cgroup/cpuset.c:generate_sched_domains
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
In kernel/cgroup/cpuset.c (ffffffff811d506f)
Location: kernel/cgroup/cpuset.c:746
Inline: True
Inline callers:
  - kernel/cgroup/cpuset.c:generate_sched_domains
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
In kernel/cgroup/cpuset.c (ffffffff8121965b)
Location: kernel/cgroup/cpuset.c:833
Inline: True
Inline callers:
  - kernel/cgroup/cpuset.c:generate_sched_domains
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
In kernel/cgroup/cpuset.c (ffffffff8122f51b)
Location: kernel/cgroup/cpuset.c:833
Inline: True
Inline callers:
  - kernel/cgroup/cpuset.c:generate_sched_domains
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
In kernel/cgroup/cpuset.c (ffffffff81247ebb)
Location: kernel/cgroup/cpuset.c:897
Inline: True
Inline callers:
  - kernel/cgroup/cpuset.c:generate_sched_domains
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
In kernel/cgroup/cpuset.c (ffff8000101e085c)
Location: kernel/cgroup/cpuset.c:674
Inline: True
Inline callers:
  - kernel/cgroup/cpuset.c:generate_sched_domains
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
In kernel/cgroup/cpuset.c (c042245c)
Location: kernel/cgroup/cpuset.c:674
Inline: True
Inline callers:
  - kernel/cgroup/cpuset.c:generate_sched_domains
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
In kernel/cgroup/cpuset.c (c000000000251504)
Location: kernel/cgroup/cpuset.c:674
Inline: True
Inline callers:
  - kernel/cgroup/cpuset.c:generate_sched_domains
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
In kernel/cgroup/cpuset.c (ffffffe000157772)
Location: kernel/cgroup/cpuset.c:674
Inline: True
Inline callers:
  - kernel/cgroup/cpuset.c:generate_sched_domains
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
In kernel/cgroup/cpuset.c (ffffffff81166d9c)
Location: kernel/cgroup/cpuset.c:674
Inline: True
Inline callers:
  - kernel/cgroup/cpuset.c:generate_sched_domains
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
In kernel/cgroup/cpuset.c (ffffffff81159fcc)
Location: kernel/cgroup/cpuset.c:674
Inline: True
Inline callers:
  - kernel/cgroup/cpuset.c:generate_sched_domains
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
In kernel/cgroup/cpuset.c (ffffffff81164b6c)
Location: kernel/cgroup/cpuset.c:674
Inline: True
Inline callers:
  - kernel/cgroup/cpuset.c:generate_sched_domains
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
In kernel/cgroup/cpuset.c (ffffffff81171ffc)
Location: kernel/cgroup/cpuset.c:674
Inline: True
Inline callers:
  - kernel/cgroup/cpuset.c:generate_sched_domains
```
</details>
</li>
</ul>

## Differences
