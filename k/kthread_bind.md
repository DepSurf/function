# Function: <code>kthread_bind</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void kthread_bind(struct task_struct *p, unsigned int cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/kthread.c (ffffffff810a0710)
Location: kernel/kthread.c:378
Inline: False
```
**Symbols:**

```
ffffffff810a0710-ffffffff810a0744: kthread_bind (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void kthread_bind(struct task_struct *p, unsigned int cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/kthread.c (ffffffff810a3e00)
Location: kernel/kthread.c:378
Inline: False
```
**Symbols:**

```
ffffffff810a3e00-ffffffff810a3e38: kthread_bind (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
void kthread_bind(struct task_struct *p, unsigned int cpu);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/kthread.c (ffffffff810a9756)
Location: kernel/kthread.c:408
Inline: True
Inline callers:
  - kernel/kthread.c:__kthread_create_worker
  - kernel/kthread.c:kthread_create_on_cpu
```
**Symbols:**

```
ffffffff810a9470-ffffffff810a94a8: kthread_bind (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
void kthread_bind(struct task_struct *p, unsigned int cpu);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/kthread.c (ffffffff810a6407)
Location: kernel/kthread.c:412
Inline: True
Inline callers:
  - kernel/kthread.c:__kthread_create_worker
  - kernel/kthread.c:kthread_create_on_cpu
```
**Symbols:**

```
ffffffff810a6160-ffffffff810a6198: kthread_bind (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
void kthread_bind(struct task_struct *p, unsigned int cpu);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/kthread.c (ffffffff810aca37)
Location: kernel/kthread.c:419
Inline: True
Inline callers:
  - kernel/kthread.c:__kthread_create_worker
  - kernel/kthread.c:kthread_create_on_cpu
Direct callers:
  - kernel/bpf/cpumap.c:__cpu_map_entry_alloc
```
**Symbols:**

```
ffffffff810ac700-ffffffff810ac738: kthread_bind (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
void kthread_bind(struct task_struct *p, unsigned int cpu);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/kthread.c (ffffffff810b3487)
Location: kernel/kthread.c:433
Inline: True
Inline callers:
  - kernel/kthread.c:__kthread_create_worker
  - kernel/kthread.c:kthread_create_on_cpu
Direct callers:
  - kernel/bpf/cpumap.c:cpu_map_update_elem
```
**Symbols:**

```
ffffffff810b2da0-ffffffff810b2dd5: kthread_bind (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
void kthread_bind(struct task_struct *p, unsigned int cpu);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/kthread.c (ffffffff810bc5c7)
Location: kernel/kthread.c:433
Inline: True
Inline callers:
  - kernel/kthread.c:__kthread_create_worker
  - kernel/kthread.c:kthread_create_on_cpu
Direct callers:
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdtgroup_pseudo_lock_create
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:pseudo_lock_measure_trigger
  - kernel/bpf/cpumap.c:cpu_map_update_elem
```
**Symbols:**

```
ffffffff810bc230-ffffffff810bc265: kthread_bind (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
void kthread_bind(struct task_struct *p, unsigned int cpu);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/kthread.c (ffffffff810c24de)
Location: kernel/kthread.c:442
Inline: True
Inline callers:
  - kernel/kthread.c:__kthread_create_worker
  - kernel/kthread.c:kthread_create_on_cpu
Direct callers:
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdtgroup_pseudo_lock_create
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:pseudo_lock_measure_trigger
  - kernel/bpf/cpumap.c:cpu_map_update_elem
```
**Symbols:**

```
ffffffff810c2410-ffffffff810c2448: kthread_bind (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
void kthread_bind(struct task_struct *p, unsigned int cpu);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/kthread.c (ffffffff810c8c1e)
Location: kernel/kthread.c:442
Inline: True
Inline callers:
  - kernel/kthread.c:__kthread_create_worker
  - kernel/kthread.c:kthread_create_on_cpu
Direct callers:
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdtgroup_pseudo_lock_create
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:pseudo_lock_measure_trigger
  - kernel/bpf/cpumap.c:cpu_map_update_elem
```
**Symbols:**

```
ffffffff810c8b50-ffffffff810c8b88: kthread_bind (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
void kthread_bind(struct task_struct *p, unsigned int cpu);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/kthread.c (ffffffff810d0eca)
Location: kernel/kthread.c:478
Inline: True
Inline callers:
  - kernel/kthread.c:__kthread_create_worker
  - kernel/kthread.c:kthread_create_on_cpu
Direct callers:
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdtgroup_pseudo_lock_create
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:pseudo_lock_measure_cycles
  - kernel/bpf/cpumap.c:__cpu_map_entry_alloc
```
**Symbols:**

```
ffffffff810d0250-ffffffff810d0283: kthread_bind (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
void kthread_bind(struct task_struct *p, unsigned int cpu);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/kthread.c (ffffffff810cb97a)
Location: kernel/kthread.c:480
Inline: True
Inline callers:
  - kernel/kthread.c:__kthread_create_worker
  - kernel/kthread.c:kthread_create_on_cpu
Direct callers:
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdtgroup_pseudo_lock_create
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:pseudo_lock_measure_cycles
  - kernel/bpf/cpumap.c:__cpu_map_entry_alloc
```
**Symbols:**

```
ffffffff810cac40-ffffffff810cac73: kthread_bind (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
void kthread_bind(struct task_struct *p, unsigned int cpu);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/kthread.c (ffffffff810cd1fa)
Location: kernel/kthread.c:507
Inline: True
Inline callers:
  - kernel/kthread.c:__kthread_create_worker
  - kernel/kthread.c:kthread_create_on_cpu
Direct callers:
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdtgroup_pseudo_lock_create
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:pseudo_lock_measure_cycles
  - kernel/bpf/cpumap.c:__cpu_map_entry_alloc
```
**Symbols:**

```
ffffffff810cc920-ffffffff810cc958: kthread_bind (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
void kthread_bind(struct task_struct *p, unsigned int cpu);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/kthread.c (ffffffff810e03dc)
Location: kernel/kthread.c:507
Inline: True
Inline callers:
  - kernel/kthread.c:__kthread_create_worker
  - kernel/kthread.c:kthread_create_on_cpu
Direct callers:
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdtgroup_pseudo_lock_create
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:pseudo_lock_measure_cycles
  - kernel/bpf/cpumap.c:__cpu_map_entry_alloc
```
**Symbols:**

```
ffffffff810df8b0-ffffffff810df8c5: kthread_bind (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
void kthread_bind(struct task_struct *p, unsigned int cpu);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/kthread.c (ffffffff810fa105)
Location: kernel/kthread.c:566
Inline: True
Inline callers:
  - kernel/kthread.c:__kthread_create_worker
  - kernel/kthread.c:kthread_create_on_cpu
Direct callers:
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdtgroup_pseudo_lock_create
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:pseudo_lock_measure_cycles
  - kernel/bpf/cpumap.c:__cpu_map_entry_alloc
```
**Symbols:**

```
ffffffff810f9b40-ffffffff810f9b5f: kthread_bind (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
void kthread_bind(struct task_struct *p, unsigned int cpu);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/kthread.c (ffffffff8111ce85)
Location: kernel/kthread.c:566
Inline: True
Inline callers:
  - kernel/kthread.c:__kthread_create_worker
  - kernel/kthread.c:kthread_create_on_cpu
Direct callers:
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdtgroup_pseudo_lock_create
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:pseudo_lock_measure_cycles
  - kernel/bpf/cpumap.c:__cpu_map_entry_alloc
```
**Symbols:**

```
ffffffff8111c8c0-ffffffff8111c8df: kthread_bind (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
void kthread_bind(struct task_struct *p, unsigned int cpu);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/kthread.c (ffffffff81129fa5)
Location: kernel/kthread.c:567
Inline: True
Inline callers:
  - kernel/kthread.c:__kthread_create_worker
  - kernel/kthread.c:kthread_create_on_cpu
Direct callers:
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdtgroup_pseudo_lock_create
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:pseudo_lock_measure_cycles
  - kernel/bpf/cpumap.c:__cpu_map_entry_alloc
```
**Symbols:**

```
ffffffff81129a50-ffffffff81129a6f: kthread_bind (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
void kthread_bind(struct task_struct *p, unsigned int cpu);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/kthread.c (ffffffff81134642)
Location: kernel/kthread.c:566
Inline: True
Inline callers:
  - kernel/kthread.c:__kthread_create_worker
  - kernel/kthread.c:kthread_create_on_cpu
Direct callers:
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdtgroup_pseudo_lock_create
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:pseudo_lock_measure_cycles
  - kernel/bpf/cpumap.c:__cpu_map_entry_alloc
```
**Symbols:**

```
ffffffff81134090-ffffffff811340af: kthread_bind (STB_GLOBAL)
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
void kthread_bind(struct task_struct *p, unsigned int cpu);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/kthread.c (ffff800010128298)
Location: kernel/kthread.c:442
Inline: True
Inline callers:
  - kernel/kthread.c:__kthread_create_worker
  - kernel/kthread.c:kthread_create_on_cpu
Direct callers:
  - kernel/bpf/cpumap.c:cpu_map_update_elem
```
**Symbols:**

```
ffff800010128198-ffff8000101281e8: kthread_bind (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
void kthread_bind(struct task_struct *p, unsigned int cpu);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/kthread.c (c037b200)
Location: kernel/kthread.c:442
Inline: True
Inline callers:
  - kernel/kthread.c:__kthread_create_worker
  - kernel/kthread.c:kthread_create_on_cpu
Direct callers:
  - kernel/bpf/cpumap.c:cpu_map_update_elem
```
**Symbols:**

```
c037a980-c037a9b8: kthread_bind (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
void kthread_bind(struct task_struct *p, unsigned int cpu);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/kthread.c (c0000000001728c4)
Location: kernel/kthread.c:442
Inline: True
Inline callers:
  - kernel/kthread.c:__kthread_create_worker
  - kernel/kthread.c:kthread_create_on_cpu
Direct callers:
  - kernel/bpf/cpumap.c:cpu_map_update_elem
```
**Symbols:**

```
c0000000001727c0-c0000000001727f4: kthread_bind (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
void kthread_bind(struct task_struct *p, unsigned int cpu);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/kthread.c (ffffffe0000df852)
Location: kernel/kthread.c:442
Inline: True
Inline callers:
  - kernel/kthread.c:__kthread_create_worker
  - kernel/kthread.c:kthread_create_on_cpu
Direct callers:
  - kernel/bpf/cpumap.c:cpu_map_update_elem
```
**Symbols:**

```
ffffffe0000df284-ffffffe0000df2ce: kthread_bind (STB_GLOBAL)
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
void kthread_bind(struct task_struct *p, unsigned int cpu);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/kthread.c (ffffffff810c2f9e)
Location: kernel/kthread.c:442
Inline: True
Inline callers:
  - kernel/kthread.c:__kthread_create_worker
  - kernel/kthread.c:kthread_create_on_cpu
Direct callers:
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdtgroup_pseudo_lock_create
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:pseudo_lock_measure_trigger
  - kernel/bpf/cpumap.c:cpu_map_update_elem
```
**Symbols:**

```
ffffffff810c2ed0-ffffffff810c2f08: kthread_bind (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
void kthread_bind(struct task_struct *p, unsigned int cpu);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/kthread.c (ffffffff810b17de)
Location: kernel/kthread.c:442
Inline: True
Inline callers:
  - kernel/kthread.c:__kthread_create_worker
  - kernel/kthread.c:kthread_create_on_cpu
Direct callers:
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdtgroup_pseudo_lock_create
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:pseudo_lock_measure_trigger
  - kernel/bpf/cpumap.c:cpu_map_update_elem
```
**Symbols:**

```
ffffffff810b1710-ffffffff810b1748: kthread_bind (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
void kthread_bind(struct task_struct *p, unsigned int cpu);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/kthread.c (ffffffff810c24ee)
Location: kernel/kthread.c:442
Inline: True
Inline callers:
  - kernel/kthread.c:__kthread_create_worker
  - kernel/kthread.c:kthread_create_on_cpu
Direct callers:
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdtgroup_pseudo_lock_create
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:pseudo_lock_measure_trigger
  - kernel/bpf/cpumap.c:cpu_map_update_elem
```
**Symbols:**

```
ffffffff810c2420-ffffffff810c2458: kthread_bind (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
void kthread_bind(struct task_struct *p, unsigned int cpu);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/kthread.c (ffffffff810caaae)
Location: kernel/kthread.c:442
Inline: True
Inline callers:
  - kernel/kthread.c:__kthread_create_worker
  - kernel/kthread.c:kthread_create_on_cpu
Direct callers:
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdtgroup_pseudo_lock_create
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:pseudo_lock_measure_trigger
  - kernel/bpf/cpumap.c:cpu_map_update_elem
```
**Symbols:**

```
ffffffff810ca9e0-ffffffff810caa18: kthread_bind (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>4.4</code> and <code>4.8</code> ✅
</li>
<li>
No changes between <code>4.8</code> and <code>4.10</code> ✅
</li>
<li>
No changes between <code>4.10</code> and <code>4.13</code> ✅
</li>
<li>
No changes between <code>4.13</code> and <code>4.15</code> ✅
</li>
<li>
No changes between <code>4.15</code> and <code>4.18</code> ✅
</li>
<li>
No changes between <code>4.18</code> and <code>5.0</code> ✅
</li>
<li>
No changes between <code>5.0</code> and <code>5.3</code> ✅
</li>
<li>
No changes between <code>5.3</code> and <code>5.4</code> ✅
</li>
<li>
No changes between <code>5.4</code> and <code>5.8</code> ✅
</li>
<li>
No changes between <code>5.8</code> and <code>5.11</code> ✅
</li>
<li>
No changes between <code>5.11</code> and <code>5.13</code> ✅
</li>
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
