# Function: <code>raw_atomic64_xchg</code>

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
In <code>5.15</code>: Absent ⚠️
</li>
<li>
In <code>5.19</code>: Absent ⚠️
</li>
<li>
In <code>6.2</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>6.5</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/sched/build_utility.c (ffffffff81187d7f)
Location: include/linux/atomic/atomic-arch-fallback.h:4017
Inline: True
Inline callers:
  - kernel/sched/build_utility.c:calc_global_load
```
```
In mm/vmscan.c (ffffffff813ac68a)
Location: include/linux/atomic/atomic-arch-fallback.h:4017
Inline: True
Inline callers:
  - mm/vmscan.c:do_shrink_slab
  - mm/vmscan.c:do_shrink_slab
```
```
In mm/page_counter.c (ffffffff8148278d)
Location: include/linux/atomic/atomic-arch-fallback.h:4017
Inline: True
Inline callers:
  - mm/page_counter.c:propagate_protected_usage
  - mm/page_counter.c:propagate_protected_usage
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
In kernel/sched/build_utility.c (ffffffff8119652f)
Location: include/linux/atomic/atomic-arch-fallback.h:4022
Inline: True
Inline callers:
  - kernel/sched/build_utility.c:calc_global_load
```
```
In mm/shrinker.c (ffffffff813e3f38)
Location: include/linux/atomic/atomic-arch-fallback.h:4022
Inline: True
Inline callers:
  - mm/shrinker.c:do_shrink_slab
  - mm/shrinker.c:do_shrink_slab
```
```
In mm/page_counter.c (ffffffff814b1b0d)
Location: include/linux/atomic/atomic-arch-fallback.h:4022
Inline: True
Inline callers:
  - mm/page_counter.c:propagate_protected_usage
  - mm/page_counter.c:propagate_protected_usage
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
