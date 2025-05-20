# Function: <code>sync_runqueues_membarrier_state</code>

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
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
int sync_runqueues_membarrier_state(struct mm_struct *mm);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/sched/membarrier.c (ffffffff81101560)
Location: kernel/sched/membarrier.c:200
Inline: True
Direct callers:
  - kernel/sched/membarrier.c:membarrier_register_private_expedited
  - kernel/sched/membarrier.c:membarrier_register_global_expedited
```
**Symbols:**

```
ffffffff81101560-ffffffff8110166e: sync_runqueues_membarrier_state (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/sched/membarrier.c (ffffffff8110bf49)
Location: kernel/sched/membarrier.c:200
Inline: True
Inline callers:
  - kernel/sched/membarrier.c:membarrier_register_private_expedited
  - kernel/sched/membarrier.c:membarrier_register_global_expedited
Direct callers:
  - kernel/sched/membarrier.c:membarrier_register_private_expedited
  - kernel/sched/membarrier.c:membarrier_register_global_expedited
```
**Symbols:**

```
ffffffff8110bd90-ffffffff8110be6f: sync_runqueues_membarrier_state.part.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/sched/membarrier.c (ffffffff8110904f)
Location: kernel/sched/membarrier.c:425
Inline: True
Inline callers:
  - kernel/sched/membarrier.c:membarrier_register_private_expedited
  - kernel/sched/membarrier.c:membarrier_register_global_expedited
Direct callers:
  - kernel/sched/membarrier.c:membarrier_register_private_expedited
  - kernel/sched/membarrier.c:membarrier_register_global_expedited
```
**Symbols:**

```
ffffffff81108c40-ffffffff81108d24: sync_runqueues_membarrier_state.part.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
int sync_runqueues_membarrier_state(struct mm_struct *mm);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/sched/membarrier.c (ffffffff8110ab20)
Location: kernel/sched/membarrier.c:425
Inline: True
Direct callers:
  - kernel/sched/membarrier.c:membarrier_register_private_expedited
  - kernel/sched/membarrier.c:membarrier_register_global_expedited
```
**Symbols:**

```
ffffffff8110ab20-ffffffff8110ac35: sync_runqueues_membarrier_state (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
int sync_runqueues_membarrier_state(struct mm_struct *mm);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/sched/membarrier.c (ffffffff81129300)
Location: kernel/sched/membarrier.c:426
Inline: True
Direct callers:
  - kernel/sched/membarrier.c:membarrier_register_private_expedited
  - kernel/sched/membarrier.c:membarrier_register_global_expedited
```
**Symbols:**

```
ffffffff81129300-ffffffff81129444: sync_runqueues_membarrier_state (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int sync_runqueues_membarrier_state(struct mm_struct *mm);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/build_utility.c (ffffffff8113dd40)
Location: kernel/sched/membarrier.c:425
Inline: False
Direct callers:
  - kernel/sched/build_utility.c:membarrier_register_private_expedited
  - kernel/sched/build_utility.c:membarrier_register_global_expedited
```
**Symbols:**

```
ffffffff8113dd40-ffffffff8113de9a: sync_runqueues_membarrier_state (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int sync_runqueues_membarrier_state(struct mm_struct *mm);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/build_utility.c (ffffffff8116dc40)
Location: kernel/sched/membarrier.c:425
Inline: False
Direct callers:
  - kernel/sched/build_utility.c:membarrier_register_private_expedited
  - kernel/sched/build_utility.c:membarrier_register_global_expedited
```
**Symbols:**

```
ffffffff8116dc40-ffffffff8116ddaa: sync_runqueues_membarrier_state (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int sync_runqueues_membarrier_state(struct mm_struct *mm);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/build_utility.c (ffffffff8117e200)
Location: kernel/sched/membarrier.c:426
Inline: False
Direct callers:
  - kernel/sched/build_utility.c:membarrier_register_private_expedited
  - kernel/sched/build_utility.c:membarrier_register_global_expedited
```
**Symbols:**

```
ffffffff8117e200-ffffffff8117e370: sync_runqueues_membarrier_state (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int sync_runqueues_membarrier_state(struct mm_struct *mm);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/build_utility.c (ffffffff8118bd90)
Location: kernel/sched/membarrier.c:431
Inline: False
Direct callers:
  - kernel/sched/build_utility.c:__do_sys_membarrier
  - kernel/sched/build_utility.c:membarrier_register_private_expedited
```
**Symbols:**

```
ffffffff8118bd90-ffffffff8118bf18: sync_runqueues_membarrier_state (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Selective Inline ⚠️</summary>

```c
int sync_runqueues_membarrier_state(struct mm_struct *mm);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/sched/membarrier.c (ffff800010165cf8)
Location: kernel/sched/membarrier.c:200
Inline: True
Direct callers:
  - kernel/sched/membarrier.c:__arm64_sys_membarrier
  - kernel/sched/membarrier.c:membarrier_register_private_expedited
```
**Symbols:**

```
ffff800010165cf8-ffff800010165e78: sync_runqueues_membarrier_state (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
int sync_runqueues_membarrier_state(struct mm_struct *mm);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/sched/membarrier.c (c03b2268)
Location: kernel/sched/membarrier.c:200
Inline: True
Direct callers:
  - kernel/sched/membarrier.c:__se_sys_membarrier
  - kernel/sched/membarrier.c:membarrier_register_private_expedited
```
**Symbols:**

```
c03b2268-c03b23c4: sync_runqueues_membarrier_state (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline, Transformation ⚠️</summary>

```c
int sync_runqueues_membarrier_state(struct mm_struct *mm);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/sched/membarrier.c (c0000000001bd3f0)
Location: kernel/sched/membarrier.c:200
Inline: True
Direct callers:
  - kernel/sched/membarrier.c:__se_sys_membarrier
  - kernel/sched/membarrier.c:membarrier_register_private_expedited
```
**Symbols:**

```
c0000000001bd3f0-c0000000001bd574: sync_runqueues_membarrier_state.part.0 (STB_LOCAL)
c0000000001bd580-c0000000001bd61c: sync_runqueues_membarrier_state (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
int sync_runqueues_membarrier_state(struct mm_struct *mm);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/sched/membarrier.c (ffffffe0001083bc)
Location: kernel/sched/membarrier.c:200
Inline: True
Direct callers:
  - kernel/sched/membarrier.c:__se_sys_membarrier
  - kernel/sched/membarrier.c:membarrier_register_private_expedited
```
**Symbols:**

```
ffffffe0001083bc-ffffffe0001084e6: sync_runqueues_membarrier_state (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Selective Inline ⚠️</summary>

```c
int sync_runqueues_membarrier_state(struct mm_struct *mm);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/sched/membarrier.c (ffffffff810fa870)
Location: kernel/sched/membarrier.c:200
Inline: True
Direct callers:
  - kernel/sched/membarrier.c:membarrier_register_private_expedited
  - kernel/sched/membarrier.c:membarrier_register_global_expedited
```
**Symbols:**

```
ffffffff810fa870-ffffffff810fa97e: sync_runqueues_membarrier_state (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
int sync_runqueues_membarrier_state(struct mm_struct *mm);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/sched/membarrier.c (ffffffff810eaa50)
Location: kernel/sched/membarrier.c:200
Inline: True
Direct callers:
  - kernel/sched/membarrier.c:membarrier_register_private_expedited
  - kernel/sched/membarrier.c:membarrier_register_global_expedited
```
**Symbols:**

```
ffffffff810eaa50-ffffffff810eab5e: sync_runqueues_membarrier_state (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
int sync_runqueues_membarrier_state(struct mm_struct *mm);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/sched/membarrier.c (ffffffff810f7a30)
Location: kernel/sched/membarrier.c:200
Inline: True
Direct callers:
  - kernel/sched/membarrier.c:membarrier_register_private_expedited
  - kernel/sched/membarrier.c:membarrier_register_global_expedited
```
**Symbols:**

```
ffffffff810f7a30-ffffffff810f7b3e: sync_runqueues_membarrier_state (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
int sync_runqueues_membarrier_state(struct mm_struct *mm);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/sched/membarrier.c (ffffffff81102b50)
Location: kernel/sched/membarrier.c:200
Inline: True
Direct callers:
  - kernel/sched/membarrier.c:membarrier_register_private_expedited
  - kernel/sched/membarrier.c:membarrier_register_global_expedited
```
**Symbols:**

```
ffffffff81102b50-ffffffff81102c7f: sync_runqueues_membarrier_state (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>5.13</code> and <code>5.15</code> ✅
</li>
<li>
No changes between <code>5.15</code> and <code>5.19</code> ✅
</li>
<li>
No changes between <code>5.19</code> and <code>6.2</code> ✅
</li>
<li>
No changes between <code>6.2</code> and <code>6.5</code> ✅
</li>
<li>
No changes between <code>6.5</code> and <code>6.8</code> ✅
</li>
</ul>
<b>Arch</b>
<ul>
<li>
No changes between <code>amd64</code> and <code>arm64</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>armhf</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>ppc64el</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>riscv64</code> ✅
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
No changes between <code>generic</code> and <code>aws</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>azure</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>gcp</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>lowlatency</code> ✅
</li>
</ul>
