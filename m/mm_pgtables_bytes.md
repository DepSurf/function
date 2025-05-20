# Function: <code>mm_pgtables_bytes</code>

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
<details>
<summary>In <code>4.15</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/fork.c (ffffffff8108786b)
Location: include/linux/mm.h:1709
Inline: True
```
```
In mm/oom_kill.c (ffffffff811d2bc3)
Location: include/linux/mm.h:1709
Inline: True
Inline callers:
  - mm/oom_kill.c:dump_header
```
```
In fs/proc/task_mmu.c (ffffffff812ecf46)
Location: include/linux/mm.h:1709
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:task_mem
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
In kernel/fork.c (ffffffff8108a8b3)
Location: include/linux/mm.h:1796
Inline: True
Inline callers:
  - kernel/fork.c:__mmdrop
  - kernel/fork.c:__mmdrop
```
```
In mm/oom_kill.c (ffffffff811f3abb)
Location: include/linux/mm.h:1796
Inline: True
Inline callers:
  - mm/oom_kill.c:dump_header
```
```
In fs/proc/task_mmu.c (ffffffff8131a44b)
Location: include/linux/mm.h:1796
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:task_mem
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
In kernel/fork.c (ffffffff81092853)
Location: include/linux/mm.h:1874
Inline: True
Inline callers:
  - kernel/fork.c:__mmdrop
  - kernel/fork.c:__mmdrop
```
```
In mm/oom_kill.c (ffffffff81205b22)
Location: include/linux/mm.h:1874
Inline: True
Inline callers:
  - mm/oom_kill.c:dump_header
```
```
In fs/proc/task_mmu.c (ffffffff8133150b)
Location: include/linux/mm.h:1874
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:task_mem
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
In kernel/fork.c (ffffffff8109670d)
Location: include/linux/mm.h:1869
Inline: True
Inline callers:
  - kernel/fork.c:__mmdrop
  - kernel/fork.c:__mmdrop
```
```
In mm/oom_kill.c (ffffffff8121bd30)
Location: include/linux/mm.h:1869
Inline: True
```
```
In fs/proc/task_mmu.c (ffffffff813592f8)
Location: include/linux/mm.h:1869
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:task_mem
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
In kernel/fork.c (ffffffff8109cddf)
Location: include/linux/mm.h:1841
Inline: True
Inline callers:
  - kernel/fork.c:__mmdrop
  - kernel/fork.c:__mmdrop
```
```
In mm/oom_kill.c (ffffffff81229ad8)
Location: include/linux/mm.h:1841
Inline: True
Inline callers:
  - mm/oom_kill.c:__oom_kill_process
```
```
In fs/proc/task_mmu.c (ffffffff81371548)
Location: include/linux/mm.h:1841
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:task_mem
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
In kernel/fork.c (ffffffff810a3a0f)
Location: include/linux/mm.h:2073
Inline: True
Inline callers:
  - kernel/fork.c:__mmdrop
  - kernel/fork.c:__mmdrop
```
```
In mm/oom_kill.c (ffffffff8125692e)
Location: include/linux/mm.h:2073
Inline: True
Inline callers:
  - mm/oom_kill.c:__oom_kill_process
```
```
In fs/proc/task_mmu.c (ffffffff813b9298)
Location: include/linux/mm.h:2073
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:task_mem
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
In kernel/fork.c (ffffffff8109f853)
Location: include/linux/mm.h:2118
Inline: True
Inline callers:
  - kernel/fork.c:__mmdrop
  - kernel/fork.c:__mmdrop
```
```
In mm/oom_kill.c (ffffffff812614c9)
Location: include/linux/mm.h:2118
Inline: True
Inline callers:
  - mm/oom_kill.c:__oom_kill_process
```
```
In fs/proc/task_mmu.c (ffffffff813caca8)
Location: include/linux/mm.h:2118
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:task_mem
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
In kernel/fork.c (ffffffff810a0983)
Location: include/linux/mm.h:2126
Inline: True
Inline callers:
  - kernel/fork.c:__mmdrop
  - kernel/fork.c:__mmdrop
```
```
In mm/oom_kill.c (ffffffff81265d05)
Location: include/linux/mm.h:2126
Inline: True
Inline callers:
  - mm/oom_kill.c:__oom_kill_process
```
```
In fs/proc/task_mmu.c (ffffffff813d1cde)
Location: include/linux/mm.h:2126
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:task_mem
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
In kernel/fork.c (ffffffff810b1da5)
Location: include/linux/mm.h:2155
Inline: True
Inline callers:
  - kernel/fork.c:__mmdrop
  - kernel/fork.c:__mmdrop
```
```
In mm/oom_kill.c (ffffffff812a252f)
Location: include/linux/mm.h:2155
Inline: True
Inline callers:
  - mm/oom_kill.c:__oom_kill_process
```
```
In fs/proc/task_mmu.c (ffffffff814231de)
Location: include/linux/mm.h:2155
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:task_mem
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
In kernel/fork.c (ffffffff810c8469)
Location: include/linux/mm.h:2233
Inline: True
Inline callers:
  - kernel/fork.c:__mmdrop
  - kernel/fork.c:__mmdrop
```
```
In mm/oom_kill.c (ffffffff812fa06c)
Location: include/linux/mm.h:2233
Inline: True
Inline callers:
  - mm/oom_kill.c:__oom_kill_process
  - mm/oom_kill.c:oom_badness
```
```
In fs/proc/task_mmu.c (ffffffff8149bbe2)
Location: include/linux/mm.h:2233
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:task_mem
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
In kernel/fork.c (ffffffff810e56d2)
Location: include/linux/mm.h:2397
Inline: True
Inline callers:
  - kernel/fork.c:__mmdrop
  - kernel/fork.c:__mmdrop
```
```
In mm/oom_kill.c (ffffffff81364793)
Location: include/linux/mm.h:2397
Inline: True
Inline callers:
  - mm/oom_kill.c:__oom_kill_process
  - mm/oom_kill.c:oom_badness
```
```
In fs/proc/task_mmu.c (ffffffff81530462)
Location: include/linux/mm.h:2397
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:task_mem
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
In kernel/fork.c (ffffffff810f0d85)
Location: include/linux/mm.h:2717
Inline: True
Inline callers:
  - kernel/fork.c:__mmdrop
  - kernel/fork.c:__mmdrop
```
```
In mm/oom_kill.c (ffffffff81396c72)
Location: include/linux/mm.h:2717
Inline: True
Inline callers:
  - mm/oom_kill.c:__oom_kill_process
  - mm/oom_kill.c:oom_badness
```
```
In fs/proc/task_mmu.c (ffffffff815685e2)
Location: include/linux/mm.h:2717
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:task_mem
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
In kernel/fork.c (ffffffff810fa175)
Location: include/linux/mm.h:2758
Inline: True
Inline callers:
  - kernel/fork.c:__mmdrop
  - kernel/fork.c:__mmdrop
```
```
In mm/oom_kill.c (ffffffff813c09e2)
Location: include/linux/mm.h:2758
Inline: True
Inline callers:
  - mm/oom_kill.c:__oom_kill_process
  - mm/oom_kill.c:oom_badness
```
```
In fs/proc/task_mmu.c (ffffffff815a0c02)
Location: include/linux/mm.h:2758
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:task_mem
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
In kernel/fork.c (ffff8000100f1d9c)
Location: include/linux/mm.h:1841
Inline: True
Inline callers:
  - kernel/fork.c:__mmdrop
  - kernel/fork.c:__mmdrop
```
```
In mm/oom_kill.c (ffff8000102b78f0)
Location: include/linux/mm.h:1841
Inline: True
Inline callers:
  - mm/oom_kill.c:__oom_kill_process
```
```
In fs/proc/task_mmu.c (ffff80001043ae5c)
Location: include/linux/mm.h:1841
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:task_mem
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
In kernel/fork.c (c0350288)
Location: include/linux/mm.h:1841
Inline: True
Inline callers:
  - kernel/fork.c:__mmdrop
  - kernel/fork.c:__mmdrop
```
```
In mm/oom_kill.c (c04e455c)
Location: include/linux/mm.h:1841
Inline: True
Inline callers:
  - mm/oom_kill.c:__oom_kill_process
```
```
In fs/proc/task_mmu.c (c06016b8)
Location: include/linux/mm.h:1841
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:task_mem
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
In kernel/fork.c (c00000000013777c)
Location: include/linux/mm.h:1841
Inline: True
Inline callers:
  - kernel/fork.c:__mmdrop
  - kernel/fork.c:__mmdrop
```
```
In mm/oom_kill.c (c00000000036f714)
Location: include/linux/mm.h:1841
Inline: True
Inline callers:
  - mm/oom_kill.c:__oom_kill_process
```
```
In fs/proc/task_mmu.c (c00000000054eb00)
Location: include/linux/mm.h:1841
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:task_mem
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
In kernel/fork.c (ffffffe0000be82e)
Location: include/linux/mm.h:1841
Inline: True
Inline callers:
  - kernel/fork.c:__mmdrop
  - kernel/fork.c:__mmdrop
```
```
In mm/oom_kill.c (ffffffe0001dbbdc)
Location: include/linux/mm.h:1841
Inline: True
Inline callers:
  - mm/oom_kill.c:__oom_kill_process
```
```
In fs/proc/task_mmu.c (ffffffe0002d38d2)
Location: include/linux/mm.h:1841
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:task_mem
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
In kernel/fork.c (ffffffff810966ff)
Location: include/linux/mm.h:1841
Inline: True
Inline callers:
  - kernel/fork.c:__mmdrop
  - kernel/fork.c:__mmdrop
```
```
In mm/oom_kill.c (ffffffff81222128)
Location: include/linux/mm.h:1841
Inline: True
Inline callers:
  - mm/oom_kill.c:__oom_kill_process
```
```
In fs/proc/task_mmu.c (ffffffff81369b28)
Location: include/linux/mm.h:1841
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:task_mem
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
In kernel/fork.c (ffffffff8108517f)
Location: include/linux/mm.h:1841
Inline: True
Inline callers:
  - kernel/fork.c:__mmdrop
  - kernel/fork.c:__mmdrop
```
```
In mm/oom_kill.c (ffffffff812152d8)
Location: include/linux/mm.h:1841
Inline: True
Inline callers:
  - mm/oom_kill.c:__oom_kill_process
```
```
In fs/proc/task_mmu.c (ffffffff8135a5b8)
Location: include/linux/mm.h:1841
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:task_mem
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
In kernel/fork.c (ffffffff810966af)
Location: include/linux/mm.h:1841
Inline: True
Inline callers:
  - kernel/fork.c:__mmdrop
  - kernel/fork.c:__mmdrop
```
```
In mm/oom_kill.c (ffffffff8121fec8)
Location: include/linux/mm.h:1841
Inline: True
Inline callers:
  - mm/oom_kill.c:__oom_kill_process
```
```
In fs/proc/task_mmu.c (ffffffff813675f8)
Location: include/linux/mm.h:1841
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:task_mem
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
In kernel/fork.c (ffffffff8109e28f)
Location: include/linux/mm.h:1841
Inline: True
Inline callers:
  - kernel/fork.c:__mmdrop
  - kernel/fork.c:__mmdrop
```
```
In mm/oom_kill.c (ffffffff8122efb2)
Location: include/linux/mm.h:1841
Inline: True
Inline callers:
  - mm/oom_kill.c:__oom_kill_process
```
```
In fs/proc/task_mmu.c (ffffffff8137ac48)
Location: include/linux/mm.h:1841
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:task_mem
```
</details>
</li>
</ul>

## Differences
