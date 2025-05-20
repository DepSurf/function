# Function: <code>queued_spin_is_contended</code>

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
In security/keys/gc.c (ffffffff8132f070)
Location: include/asm-generic/qspinlock.h:53
Inline: True
Inline callers:
  - security/keys/gc.c:key_garbage_collector
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
In security/keys/gc.c (ffffffff81363d4e)
Location: include/asm-generic/qspinlock.h:73
Inline: True
Inline callers:
  - security/keys/gc.c:key_garbage_collector
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
In security/keys/gc.c (ffffffff8137a56e)
Location: include/asm-generic/qspinlock.h:73
Inline: True
Inline callers:
  - security/keys/gc.c:key_garbage_collector
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
In security/keys/gc.c (ffffffff8138e155)
Location: include/asm-generic/qspinlock.h:73
Inline: True
Inline callers:
  - security/keys/gc.c:key_garbage_collector
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
In security/keys/gc.c (ffffffff813b35ed)
Location: include/asm-generic/qspinlock.h:60
Inline: True
Inline callers:
  - security/keys/gc.c:key_garbage_collector
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
In security/keys/gc.c (ffffffff813e3d2f)
Location: include/asm-generic/qspinlock.h:58
Inline: True
Inline callers:
  - security/keys/gc.c:key_garbage_collector
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
In security/keys/gc.c (ffffffff813fe51f)
Location: include/asm-generic/qspinlock.h:58
Inline: True
Inline callers:
  - security/keys/gc.c:key_garbage_collector
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
In security/keys/gc.c (ffffffff8142ab6c)
Location: include/asm-generic/qspinlock.h:49
Inline: True
Inline callers:
  - security/keys/gc.c:key_garbage_collector
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
In security/keys/gc.c (ffffffff814448bc)
Location: include/asm-generic/qspinlock.h:49
Inline: True
Inline callers:
  - security/keys/gc.c:key_garbage_collector
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
In security/keys/gc.c (ffffffff8149591c)
Location: include/asm-generic/qspinlock.h:49
Inline: True
Inline callers:
  - security/keys/gc.c:key_garbage_collector
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
In security/keys/gc.c (ffffffff814b337c)
Location: include/asm-generic/qspinlock.h:52
Inline: True
Inline callers:
  - security/keys/gc.c:key_garbage_collector
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
In security/keys/gc.c (ffffffff814b91c1)
Location: include/asm-generic/qspinlock.h:52
Inline: True
Inline callers:
  - security/keys/gc.c:key_garbage_collector
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
In security/keys/gc.c (ffffffff815119f1)
Location: include/asm-generic/qspinlock.h:52
Inline: True
Inline callers:
  - security/keys/gc.c:key_garbage_collector
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
In kernel/sched/core.c (ffffffff8110b276)
Location: include/asm-generic/qspinlock.h:81
Inline: True
```
```
In kernel/cgroup/rstat.c (ffffffff811cdcdf)
Location: include/asm-generic/qspinlock.h:81
Inline: True
Inline callers:
  - kernel/cgroup/rstat.c:cgroup_rstat_flush_locked
```
```
In mm/memory.c (ffffffff813406be)
Location: include/asm-generic/qspinlock.h:81
Inline: True
Inline callers:
  - mm/memory.c:copy_pte_range
  - mm/memory.c:copy_pte_range
```
```
In fs/jbd2/checkpoint.c (ffffffff81544117)
Location: include/asm-generic/qspinlock.h:81
Inline: True
Inline callers:
  - fs/jbd2/checkpoint.c:jbd2_journal_shrink_checkpoint_list
  - fs/jbd2/checkpoint.c:jbd2_journal_shrink_checkpoint_list
  - fs/jbd2/checkpoint.c:jbd2_log_do_checkpoint
```
```
In security/keys/gc.c (ffffffff815a3d4a)
Location: include/asm-generic/qspinlock.h:81
Inline: True
Inline callers:
  - security/keys/gc.c:key_garbage_collector
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
In kernel/sched/core.c (ffffffff81131656)
Location: include/asm-generic/qspinlock.h:81
Inline: True
```
```
In kernel/cgroup/rstat.c (ffffffff81211633)
Location: include/asm-generic/qspinlock.h:81
Inline: True
Inline callers:
  - kernel/cgroup/rstat.c:cgroup_rstat_flush_locked
```
```
In mm/vmscan.c (ffffffff813872a8)
Location: include/asm-generic/qspinlock.h:81
Inline: True
Inline callers:
  - mm/vmscan.c:lru_gen_look_around
```
```
In mm/memory.c (ffffffff813b8678)
Location: include/asm-generic/qspinlock.h:81
Inline: True
Inline callers:
  - mm/memory.c:copy_pte_range
  - mm/memory.c:copy_pte_range
```
```
In mm/zsmalloc.c (ffffffff81469bc3)
Location: include/asm-generic/qspinlock.h:81
Inline: True
Inline callers:
  - mm/zsmalloc.c:__zs_compact
```
```
In fs/jbd2/checkpoint.c (ffffffff815e30f7)
Location: include/asm-generic/qspinlock.h:81
Inline: True
Inline callers:
  - fs/jbd2/checkpoint.c:jbd2_journal_shrink_checkpoint_list
  - fs/jbd2/checkpoint.c:jbd2_journal_shrink_checkpoint_list
  - fs/jbd2/checkpoint.c:jbd2_log_do_checkpoint
```
```
In security/keys/gc.c (ffffffff8164da0a)
Location: include/asm-generic/qspinlock.h:81
Inline: True
Inline callers:
  - security/keys/gc.c:key_garbage_collector
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
In kernel/sched/core.c (ffffffff8113f89d)
Location: include/asm-generic/qspinlock.h:81
Inline: True
```
```
In kernel/cgroup/rstat.c (ffffffff81227017)
Location: include/asm-generic/qspinlock.h:81
Inline: True
Inline callers:
  - kernel/cgroup/rstat.c:cgroup_rstat_flush_locked
```
```
In mm/vmscan.c (ffffffff813b7705)
Location: include/asm-generic/qspinlock.h:81
Inline: True
Inline callers:
  - mm/vmscan.c:lru_gen_look_around
```
```
In mm/memory.c (ffffffff813ed32a)
Location: include/asm-generic/qspinlock.h:81
Inline: True
Inline callers:
  - mm/memory.c:copy_pte_range
  - mm/memory.c:copy_pte_range
```
```
In mm/zsmalloc.c (ffffffff8149ed8d)
Location: include/asm-generic/qspinlock.h:81
Inline: True
Inline callers:
  - mm/zsmalloc.c:__zs_compact
```
```
In fs/jbd2/checkpoint.c (ffffffff8161a98f)
Location: include/asm-generic/qspinlock.h:81
Inline: True
Inline callers:
  - fs/jbd2/checkpoint.c:jbd2_journal_shrink_checkpoint_list
  - fs/jbd2/checkpoint.c:jbd2_log_do_checkpoint
```
```
In security/keys/gc.c (ffffffff816861ba)
Location: include/asm-generic/qspinlock.h:81
Inline: True
Inline callers:
  - security/keys/gc.c:key_garbage_collector
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
In kernel/sched/core.c (ffffffff8114a7fd)
Location: include/asm-generic/qspinlock.h:81
Inline: True
```
```
In kernel/cgroup/rstat.c (ffffffff8123ed95)
Location: include/asm-generic/qspinlock.h:81
Inline: True
Inline callers:
  - kernel/cgroup/rstat.c:cgroup_rstat_flush_locked
```
```
In mm/vmscan.c (ffffffff813e05a4)
Location: include/asm-generic/qspinlock.h:81
Inline: True
Inline callers:
  - mm/vmscan.c:lru_gen_look_around
```
```
In mm/memory.c (ffffffff814188fa)
Location: include/asm-generic/qspinlock.h:81
Inline: True
Inline callers:
  - mm/memory.c:copy_pte_range
  - mm/memory.c:copy_pte_range
```
```
In mm/zsmalloc.c (ffffffff814ce4fd)
Location: include/asm-generic/qspinlock.h:81
Inline: True
Inline callers:
  - mm/zsmalloc.c:__zs_compact
```
```
In fs/jbd2/checkpoint.c (ffffffff816538af)
Location: include/asm-generic/qspinlock.h:81
Inline: True
Inline callers:
  - fs/jbd2/checkpoint.c:jbd2_journal_shrink_checkpoint_list
  - fs/jbd2/checkpoint.c:jbd2_log_do_checkpoint
```
```
In security/keys/gc.c (ffffffff816c25e7)
Location: include/asm-generic/qspinlock.h:81
Inline: True
Inline callers:
  - security/keys/gc.c:key_garbage_collector
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
In security/keys/gc.c (ffff80001052d50c)
Location: include/asm-generic/qspinlock.h:49
Inline: True
Inline callers:
  - security/keys/gc.c:key_garbage_collector
```
</details>
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
<summary>In <code>aws</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In security/keys/gc.c (ffffffff8143ce9c)
Location: include/asm-generic/qspinlock.h:49
Inline: True
Inline callers:
  - security/keys/gc.c:key_garbage_collector
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
In security/keys/gc.c (ffffffff8142d90c)
Location: include/asm-generic/qspinlock.h:49
Inline: True
Inline callers:
  - security/keys/gc.c:key_garbage_collector
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
In security/keys/gc.c (ffffffff8143903c)
Location: include/asm-generic/qspinlock.h:49
Inline: True
Inline callers:
  - security/keys/gc.c:key_garbage_collector
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
In kernel/sched/core.c (ffffffff810da938)
Location: include/asm-generic/qspinlock.h:49
Inline: True
Inline callers:
  - kernel/sched/core.c:__cond_resched_lock
```
```
In kernel/cgroup/rstat.c (ffffffff8116aa86)
Location: include/asm-generic/qspinlock.h:49
Inline: True
Inline callers:
  - kernel/cgroup/rstat.c:cgroup_rstat_flush_locked
```
```
In mm/memory.c (ffffffff81264983)
Location: include/asm-generic/qspinlock.h:49
Inline: True
```
```
In fs/jbd2/checkpoint.c (ffffffff81400cc3)
Location: include/asm-generic/qspinlock.h:49
Inline: True
Inline callers:
  - fs/jbd2/checkpoint.c:jbd2_log_do_checkpoint
```
```
In security/keys/gc.c (ffffffff814501a1)
Location: include/asm-generic/qspinlock.h:49
Inline: True
Inline callers:
  - security/keys/gc.c:key_garbage_collector
```
</details>
</li>
</ul>

## Differences
