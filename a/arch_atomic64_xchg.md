# Function: <code>arch_atomic64_xchg</code>

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
<details>
<summary>In <code>4.18</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/sched/loadavg.c (ffffffff810c3233)
Location: arch/x86/include/asm/atomic64_64.h:186
Inline: True
Inline callers:
  - kernel/sched/loadavg.c:calc_global_load
```
```
In mm/vmscan.c (ffffffff81206340)
Location: arch/x86/include/asm/atomic64_64.h:186
Inline: True
```
```
In mm/page_counter.c (ffffffff8127e2a5)
Location: arch/x86/include/asm/atomic64_64.h:186
Inline: True
Inline callers:
  - mm/page_counter.c:propagate_protected_usage
  - mm/page_counter.c:propagate_protected_usage
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
In kernel/sched/loadavg.c (ffffffff810cc4e3)
Location: arch/x86/include/asm/atomic64_64.h:189
Inline: True
Inline callers:
  - kernel/sched/loadavg.c:calc_global_load
```
```
In mm/vmscan.c (ffffffff81218abf)
Location: arch/x86/include/asm/atomic64_64.h:189
Inline: True
Inline callers:
  - mm/vmscan.c:do_shrink_slab
```
```
In mm/page_counter.c (ffffffff81292995)
Location: arch/x86/include/asm/atomic64_64.h:189
Inline: True
Inline callers:
  - mm/page_counter.c:propagate_protected_usage
  - mm/page_counter.c:propagate_protected_usage
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
In kernel/sched/loadavg.c (ffffffff810d491f)
Location: arch/x86/include/asm/atomic64_64.h:189
Inline: True
Inline callers:
  - kernel/sched/loadavg.c:calc_global_load
```
```
In mm/vmscan.c (ffffffff812284ff)
Location: arch/x86/include/asm/atomic64_64.h:189
Inline: True
Inline callers:
  - mm/vmscan.c:do_shrink_slab
```
```
In mm/page_counter.c (ffffffff812ad365)
Location: arch/x86/include/asm/atomic64_64.h:189
Inline: True
Inline callers:
  - mm/page_counter.c:propagate_protected_usage
  - mm/page_counter.c:propagate_protected_usage
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
In kernel/sched/loadavg.c (ffffffff810deedf)
Location: arch/x86/include/asm/atomic64_64.h:189
Inline: True
Inline callers:
  - kernel/sched/loadavg.c:calc_global_load
```
```
In mm/vmscan.c (ffffffff8123639f)
Location: arch/x86/include/asm/atomic64_64.h:189
Inline: True
Inline callers:
  - mm/vmscan.c:do_shrink_slab
```
```
In mm/page_counter.c (ffffffff812beeb5)
Location: arch/x86/include/asm/atomic64_64.h:189
Inline: True
Inline callers:
  - mm/page_counter.c:propagate_protected_usage
  - mm/page_counter.c:propagate_protected_usage
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
In kernel/sched/loadavg.c (ffffffff810e728a)
Location: arch/x86/include/asm/atomic64_64.h:194
Inline: True
Inline callers:
  - kernel/sched/loadavg.c:calc_global_load
```
```
In mm/vmscan.c (ffffffff81264f10)
Location: arch/x86/include/asm/atomic64_64.h:194
Inline: True
Inline callers:
  - mm/vmscan.c:do_shrink_slab
```
```
In mm/page_counter.c (ffffffff812f4190)
Location: arch/x86/include/asm/atomic64_64.h:194
Inline: True
Inline callers:
  - mm/page_counter.c:propagate_protected_usage
  - mm/page_counter.c:propagate_protected_usage
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
In kernel/sched/loadavg.c (ffffffff810e4eca)
Location: arch/x86/include/asm/atomic64_64.h:194
Inline: True
Inline callers:
  - kernel/sched/loadavg.c:calc_global_load
```
```
In mm/vmscan.c (ffffffff8126f88a)
Location: arch/x86/include/asm/atomic64_64.h:194
Inline: True
Inline callers:
  - mm/vmscan.c:do_shrink_slab
```
```
In mm/page_counter.c (ffffffff812ffa80)
Location: arch/x86/include/asm/atomic64_64.h:194
Inline: True
Inline callers:
  - mm/page_counter.c:propagate_protected_usage
  - mm/page_counter.c:propagate_protected_usage
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
In kernel/sched/loadavg.c (ffffffff810e6da7)
Location: arch/x86/include/asm/atomic64_64.h:194
Inline: True
Inline callers:
  - kernel/sched/loadavg.c:calc_global_load
```
```
In mm/vmscan.c (ffffffff8127356a)
Location: arch/x86/include/asm/atomic64_64.h:194
Inline: True
Inline callers:
  - mm/vmscan.c:do_shrink_slab
  - mm/vmscan.c:do_shrink_slab
```
```
In mm/page_counter.c (ffffffff81306723)
Location: arch/x86/include/asm/atomic64_64.h:194
Inline: True
Inline callers:
  - mm/page_counter.c:propagate_protected_usage
  - mm/page_counter.c:propagate_protected_usage
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
In kernel/sched/loadavg.c (ffffffff810fe377)
Location: arch/x86/include/asm/atomic64_64.h:194
Inline: True
Inline callers:
  - kernel/sched/loadavg.c:calc_global_load
```
```
In mm/vmscan.c (ffffffff812b083e)
Location: arch/x86/include/asm/atomic64_64.h:194
Inline: True
Inline callers:
  - mm/vmscan.c:do_shrink_slab
  - mm/vmscan.c:do_shrink_slab
```
```
In mm/page_counter.c (ffffffff81350553)
Location: arch/x86/include/asm/atomic64_64.h:194
Inline: True
Inline callers:
  - mm/page_counter.c:propagate_protected_usage
  - mm/page_counter.c:propagate_protected_usage
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
In kernel/sched/build_utility.c (ffffffff8114890f)
Location: arch/x86/include/asm/atomic64_64.h:194
Inline: True
Inline callers:
  - kernel/sched/build_utility.c:calc_global_load
```
```
In mm/vmscan.c (ffffffff8130c0ba)
Location: arch/x86/include/asm/atomic64_64.h:194
Inline: True
Inline callers:
  - mm/vmscan.c:do_shrink_slab
  - mm/vmscan.c:do_shrink_slab
```
```
In mm/page_counter.c (ffffffff813c8803)
Location: arch/x86/include/asm/atomic64_64.h:194
Inline: True
Inline callers:
  - mm/page_counter.c:propagate_protected_usage
  - mm/page_counter.c:propagate_protected_usage
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
In kernel/sched/build_utility.c (ffffffff8117712f)
Location: arch/x86/include/asm/atomic64_64.h:194
Inline: True
Inline callers:
  - kernel/sched/build_utility.c:calc_global_load
```
```
In mm/vmscan.c (ffffffff8137838a)
Location: arch/x86/include/asm/atomic64_64.h:194
Inline: True
Inline callers:
  - mm/vmscan.c:do_shrink_slab
  - mm/vmscan.c:do_shrink_slab
```
```
In mm/page_counter.c (ffffffff8144cecd)
Location: arch/x86/include/asm/atomic64_64.h:194
Inline: True
Inline callers:
  - mm/page_counter.c:propagate_protected_usage
  - mm/page_counter.c:propagate_protected_usage
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
In kernel/sched/build_utility.c (ffffffff81187d7f)
Location: arch/x86/include/asm/atomic64_64.h:113
Inline: True
Inline callers:
  - kernel/sched/build_utility.c:calc_global_load
```
```
In mm/vmscan.c (ffffffff813ac68a)
Location: arch/x86/include/asm/atomic64_64.h:113
Inline: True
Inline callers:
  - mm/vmscan.c:do_shrink_slab
  - mm/vmscan.c:do_shrink_slab
```
```
In mm/page_counter.c (ffffffff8148278d)
Location: arch/x86/include/asm/atomic64_64.h:113
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
Location: arch/x86/include/asm/atomic64_64.h:113
Inline: True
Inline callers:
  - kernel/sched/build_utility.c:calc_global_load
```
```
In mm/shrinker.c (ffffffff813e3f38)
Location: arch/x86/include/asm/atomic64_64.h:113
Inline: True
Inline callers:
  - mm/shrinker.c:do_shrink_slab
  - mm/shrinker.c:do_shrink_slab
```
```
In mm/page_counter.c (ffffffff814b1b0d)
Location: arch/x86/include/asm/atomic64_64.h:113
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
<details>
<summary>In <code>aws</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/sched/loadavg.c (ffffffff810d90cf)
Location: arch/x86/include/asm/atomic64_64.h:189
Inline: True
Inline callers:
  - kernel/sched/loadavg.c:calc_global_load
```
```
In mm/vmscan.c (ffffffff8122e9ef)
Location: arch/x86/include/asm/atomic64_64.h:189
Inline: True
Inline callers:
  - mm/vmscan.c:do_shrink_slab
```
```
In mm/page_counter.c (ffffffff812b7495)
Location: arch/x86/include/asm/atomic64_64.h:189
Inline: True
Inline callers:
  - mm/page_counter.c:propagate_protected_usage
  - mm/page_counter.c:propagate_protected_usage
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
In kernel/sched/loadavg.c (ffffffff810c7acf)
Location: arch/x86/include/asm/atomic64_64.h:189
Inline: True
Inline callers:
  - kernel/sched/loadavg.c:calc_global_load
```
```
In kernel/rcu/rcu_segcblist.c (ffffffff81116691)
Location: arch/x86/include/asm/atomic64_64.h:189
Inline: True
Inline callers:
  - kernel/rcu/rcu_segcblist.c:rcu_segcblist_merge
```
```
In mm/vmscan.c (ffffffff81221aaf)
Location: arch/x86/include/asm/atomic64_64.h:189
Inline: True
Inline callers:
  - mm/vmscan.c:do_shrink_slab
```
```
In mm/page_counter.c (ffffffff812a8665)
Location: arch/x86/include/asm/atomic64_64.h:189
Inline: True
Inline callers:
  - mm/page_counter.c:propagate_protected_usage
  - mm/page_counter.c:propagate_protected_usage
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
In kernel/sched/loadavg.c (ffffffff810d540f)
Location: arch/x86/include/asm/atomic64_64.h:189
Inline: True
Inline callers:
  - kernel/sched/loadavg.c:calc_global_load
```
```
In mm/vmscan.c (ffffffff8122c78f)
Location: arch/x86/include/asm/atomic64_64.h:189
Inline: True
Inline callers:
  - mm/vmscan.c:do_shrink_slab
```
```
In mm/page_counter.c (ffffffff812b52a5)
Location: arch/x86/include/asm/atomic64_64.h:189
Inline: True
Inline callers:
  - mm/page_counter.c:propagate_protected_usage
  - mm/page_counter.c:propagate_protected_usage
```
```
In net/netfilter/nf_conntrack_netlink.c (ffffffff819ac1dc)
Location: arch/x86/include/asm/atomic64_64.h:189
Inline: True
Inline callers:
  - net/netfilter/nf_conntrack_netlink.c:dump_counters
  - net/netfilter/nf_conntrack_netlink.c:dump_counters
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
In kernel/sched/loadavg.c (ffffffff810e0cbf)
Location: arch/x86/include/asm/atomic64_64.h:189
Inline: True
Inline callers:
  - kernel/sched/loadavg.c:calc_global_load
```
```
In mm/vmscan.c (ffffffff8123bb7a)
Location: arch/x86/include/asm/atomic64_64.h:189
Inline: True
Inline callers:
  - mm/vmscan.c:do_shrink_slab
```
```
In mm/page_counter.c (ffffffff812c57e5)
Location: arch/x86/include/asm/atomic64_64.h:189
Inline: True
Inline callers:
  - mm/page_counter.c:propagate_protected_usage
  - mm/page_counter.c:propagate_protected_usage
```
</details>
</li>
</ul>

## Differences
