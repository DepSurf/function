# Function: <code>perf_event_create_kernel_counter</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
struct perf_event *perf_event_create_kernel_counter(struct perf_event_attr *attr, int cpu, struct task_struct *task, perf_overflow_handler_t overflow_handler, void *context);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff81180b80)
Location: kernel/events/core.c:8606
Inline: False
Direct callers:
  - kernel/watchdog.c:watchdog_enable
  - kernel/events/hw_breakpoint.c:register_user_hw_breakpoint
  - kernel/events/hw_breakpoint.c:register_wide_hw_breakpoint
```
**Symbols:**

```
ffffffff81180b80-ffffffff81180cd4: perf_event_create_kernel_counter (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
struct perf_event *perf_event_create_kernel_counter(struct perf_event_attr *attr, int cpu, struct task_struct *task, perf_overflow_handler_t overflow_handler, void *context);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff81192750)
Location: kernel/events/core.c:9786
Inline: False
Direct callers:
  - kernel/watchdog.c:watchdog_enable
  - kernel/events/hw_breakpoint.c:register_wide_hw_breakpoint
  - kernel/events/hw_breakpoint.c:register_user_hw_breakpoint
```
**Symbols:**

```
ffffffff81192750-ffffffff81192887: perf_event_create_kernel_counter (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
struct perf_event *perf_event_create_kernel_counter(struct perf_event_attr *attr, int cpu, struct task_struct *task, perf_overflow_handler_t overflow_handler, void *context);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff811a1f30)
Location: kernel/events/core.c:10046
Inline: False
Direct callers:
  - kernel/watchdog_hld.c:watchdog_nmi_enable
  - kernel/events/hw_breakpoint.c:register_wide_hw_breakpoint
  - kernel/events/hw_breakpoint.c:register_user_hw_breakpoint
```
**Symbols:**

```
ffffffff811a1f30-ffffffff811a2067: perf_event_create_kernel_counter (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
struct perf_event *perf_event_create_kernel_counter(struct perf_event_attr *attr, int cpu, struct task_struct *task, perf_overflow_handler_t overflow_handler, void *context);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff811a96f0)
Location: kernel/events/core.c:10278
Inline: False
Direct callers:
  - kernel/watchdog_hld.c:watchdog_nmi_enable
  - kernel/watchdog_hld.c:watchdog_nmi_enable
  - kernel/events/hw_breakpoint.c:register_wide_hw_breakpoint
  - kernel/events/hw_breakpoint.c:register_user_hw_breakpoint
```
**Symbols:**

```
ffffffff811a96f0-ffffffff811a9820: perf_event_create_kernel_counter (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
struct perf_event *perf_event_create_kernel_counter(struct perf_event_attr *attr, int cpu, struct task_struct *task, perf_overflow_handler_t overflow_handler, void *context);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff811bcf40)
Location: kernel/events/core.c:10310
Inline: False
Direct callers:
  - kernel/watchdog_hld.c:hardlockup_detector_event_create
  - kernel/events/hw_breakpoint.c:register_wide_hw_breakpoint
  - kernel/events/hw_breakpoint.c:register_user_hw_breakpoint
```
**Symbols:**

```
ffffffff811bcf40-ffffffff811bd070: perf_event_create_kernel_counter (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
struct perf_event *perf_event_create_kernel_counter(struct perf_event_attr *attr, int cpu, struct task_struct *task, perf_overflow_handler_t overflow_handler, void *context);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff811dd140)
Location: kernel/events/core.c:10840
Inline: False
Direct callers:
  - kernel/watchdog_hld.c:hardlockup_detector_event_create
  - kernel/events/hw_breakpoint.c:register_wide_hw_breakpoint
  - kernel/events/hw_breakpoint.c:register_user_hw_breakpoint
```
**Symbols:**

```
ffffffff811dd140-ffffffff811dd275: perf_event_create_kernel_counter (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
struct perf_event *perf_event_create_kernel_counter(struct perf_event_attr *attr, int cpu, struct task_struct *task, perf_overflow_handler_t overflow_handler, void *context);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff811ed540)
Location: kernel/events/core.c:10883
Inline: False
Direct callers:
  - kernel/watchdog_hld.c:hardlockup_detector_event_create
  - kernel/events/hw_breakpoint.c:register_wide_hw_breakpoint
  - kernel/events/hw_breakpoint.c:register_user_hw_breakpoint
```
**Symbols:**

```
ffffffff811ed540-ffffffff811ed675: perf_event_create_kernel_counter (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
struct perf_event *perf_event_create_kernel_counter(struct perf_event_attr *attr, int cpu, struct task_struct *task, perf_overflow_handler_t overflow_handler, void *context);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff81204f80)
Location: kernel/events/core.c:11234
Inline: False
Direct callers:
  - kernel/watchdog_hld.c:hardlockup_detector_event_create
  - kernel/events/hw_breakpoint.c:register_wide_hw_breakpoint
  - kernel/events/hw_breakpoint.c:register_user_hw_breakpoint
```
**Symbols:**

```
ffffffff81204f80-ffffffff812050aa: perf_event_create_kernel_counter (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
struct perf_event *perf_event_create_kernel_counter(struct perf_event_attr *attr, int cpu, struct task_struct *task, perf_overflow_handler_t overflow_handler, void *context);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff81211b70)
Location: kernel/events/core.c:11341
Inline: True
Direct callers:
  - kernel/watchdog_hld.c:hardlockup_detector_event_create
  - kernel/events/hw_breakpoint.c:register_wide_hw_breakpoint
  - kernel/events/hw_breakpoint.c:register_user_hw_breakpoint
```
**Symbols:**

```
ffffffff81211b70-ffffffff81211cab: perf_event_create_kernel_counter (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline, Transformation ⚠️</summary>

```c
struct perf_event *perf_event_create_kernel_counter(struct perf_event_attr *attr, int cpu, struct task_struct *task, perf_overflow_handler_t overflow_handler, void *context);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/events/core.c (ffffffff8123daa0)
Location: kernel/events/core.c:11944
Inline: True
Direct callers:
  - kernel/watchdog_hld.c:hardlockup_detector_event_create
  - kernel/events/hw_breakpoint.c:register_wide_hw_breakpoint
  - kernel/events/hw_breakpoint.c:register_user_hw_breakpoint
```
**Symbols:**

```
ffffffff8123daa0-ffffffff8123dbfb: perf_event_create_kernel_counter.part.0 (STB_LOCAL)
ffffffff8123dc00-ffffffff8123dc19: perf_event_create_kernel_counter (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline, Transformation ⚠️</summary>

```c
struct perf_event *perf_event_create_kernel_counter(struct perf_event_attr *attr, int cpu, struct task_struct *task, perf_overflow_handler_t overflow_handler, void *context);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/events/core.c (ffffffff81247e60)
Location: kernel/events/core.c:12228
Inline: True
Direct callers:
  - kernel/watchdog_hld.c:hardlockup_detector_event_create
  - kernel/events/hw_breakpoint.c:register_wide_hw_breakpoint
  - kernel/events/hw_breakpoint.c:register_user_hw_breakpoint
```
**Symbols:**

```
ffffffff81247e60-ffffffff81247fb8: perf_event_create_kernel_counter.part.0 (STB_LOCAL)
ffffffff81247fc0-ffffffff81247fd9: perf_event_create_kernel_counter (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
struct perf_event *perf_event_create_kernel_counter(struct perf_event_attr *attr, int cpu, struct task_struct *task, perf_overflow_handler_t overflow_handler, void *context);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff8124bd20)
Location: kernel/events/core.c:12418
Inline: True
Direct callers:
  - kernel/watchdog_hld.c:hardlockup_detector_event_create
  - kernel/events/hw_breakpoint.c:register_wide_hw_breakpoint
  - kernel/events/hw_breakpoint.c:register_user_hw_breakpoint
```
**Symbols:**

```
ffffffff8124bd20-ffffffff8124be94: perf_event_create_kernel_counter (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
struct perf_event *perf_event_create_kernel_counter(struct perf_event_attr *attr, int cpu, struct task_struct *task, perf_overflow_handler_t overflow_handler, void *context);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff812875e0)
Location: kernel/events/core.c:12539
Inline: True
Direct callers:
  - kernel/watchdog_hld.c:hardlockup_detector_event_create
  - kernel/events/hw_breakpoint.c:register_wide_hw_breakpoint
  - kernel/events/hw_breakpoint.c:register_user_hw_breakpoint
```
**Symbols:**

```
ffffffff812875e0-ffffffff81287754: perf_event_create_kernel_counter (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
struct perf_event *perf_event_create_kernel_counter(struct perf_event_attr *attr, int cpu, struct task_struct *task, perf_overflow_handler_t overflow_handler, void *context);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff812dbd90)
Location: kernel/events/core.c:12509
Inline: True
Direct callers:
  - kernel/watchdog_hld.c:hardlockup_detector_event_create
  - kernel/events/hw_breakpoint.c:register_wide_hw_breakpoint
  - kernel/events/hw_breakpoint.c:register_user_hw_breakpoint
```
**Symbols:**

```
ffffffff812dbd90-ffffffff812dbf11: perf_event_create_kernel_counter (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
struct perf_event *perf_event_create_kernel_counter(struct perf_event_attr *attr, int cpu, struct task_struct *task, perf_overflow_handler_t overflow_handler, void *context);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff81344090)
Location: kernel/events/core.c:12708
Inline: True
Direct callers:
  - kernel/watchdog_hld.c:hardlockup_detector_event_create
  - kernel/events/hw_breakpoint.c:register_wide_hw_breakpoint
  - kernel/events/hw_breakpoint.c:register_user_hw_breakpoint
```
**Symbols:**

```
ffffffff81344090-ffffffff81344275: perf_event_create_kernel_counter (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
struct perf_event *perf_event_create_kernel_counter(struct perf_event_attr *attr, int cpu, struct task_struct *task, perf_overflow_handler_t overflow_handler, void *context);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff81375120)
Location: kernel/events/core.c:12748
Inline: True
Direct callers:
  - kernel/watchdog_perf.c:hardlockup_detector_event_create
  - kernel/events/hw_breakpoint.c:register_wide_hw_breakpoint
  - kernel/events/hw_breakpoint.c:register_user_hw_breakpoint
```
**Symbols:**

```
ffffffff81375120-ffffffff81375313: perf_event_create_kernel_counter (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
struct perf_event *perf_event_create_kernel_counter(struct perf_event_attr *attr, int cpu, struct task_struct *task, perf_overflow_handler_t overflow_handler, void *context);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff8139e450)
Location: kernel/events/core.c:12832
Inline: True
Direct callers:
  - kernel/watchdog_perf.c:hardlockup_detector_event_create
  - kernel/events/hw_breakpoint.c:register_wide_hw_breakpoint
  - kernel/events/hw_breakpoint.c:register_user_hw_breakpoint
```
**Symbols:**

```
ffffffff8139e450-ffffffff8139e643: perf_event_create_kernel_counter (STB_GLOBAL)
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
struct perf_event *perf_event_create_kernel_counter(struct perf_event_attr *attr, int cpu, struct task_struct *task, perf_overflow_handler_t overflow_handler, void *context);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffff80001029c018)
Location: kernel/events/core.c:11341
Inline: True
Direct callers:
  - virt/kvm/arm/pmu.c:kvm_pmu_create_perf_event
  - virt/kvm/arm/pmu.c:kvm_pmu_create_perf_event
  - kernel/events/hw_breakpoint.c:register_wide_hw_breakpoint
  - kernel/events/hw_breakpoint.c:register_user_hw_breakpoint
```
**Symbols:**

```
ffff80001029c018-ffff80001029c160: perf_event_create_kernel_counter (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
struct perf_event *perf_event_create_kernel_counter(struct perf_event_attr *attr, int cpu, struct task_struct *task, perf_overflow_handler_t overflow_handler, void *context);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (c04cb5d0)
Location: kernel/events/core.c:11341
Inline: True
Direct callers:
  - kernel/events/hw_breakpoint.c:register_wide_hw_breakpoint
  - kernel/events/hw_breakpoint.c:register_user_hw_breakpoint
```
**Symbols:**

```
c04cb5d0-c04cb740: perf_event_create_kernel_counter (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
struct perf_event *perf_event_create_kernel_counter(struct perf_event_attr *attr, int cpu, struct task_struct *task, perf_overflow_handler_t overflow_handler, void *context);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (c00000000034c270)
Location: kernel/events/core.c:11341
Inline: True
Direct callers:
  - kernel/events/hw_breakpoint.c:register_wide_hw_breakpoint
  - kernel/events/hw_breakpoint.c:register_user_hw_breakpoint
```
**Symbols:**

```
c00000000034c270-c00000000034c4a0: perf_event_create_kernel_counter (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
struct perf_event *perf_event_create_kernel_counter(struct perf_event_attr *attr, int cpu, struct task_struct *task, perf_overflow_handler_t overflow_handler, void *context);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffe0001ca6aa)
Location: kernel/events/core.c:11341
Inline: True
```
**Symbols:**

```
ffffffe0001ca6aa-ffffffe0001ca7ca: perf_event_create_kernel_counter (STB_GLOBAL)
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
struct perf_event *perf_event_create_kernel_counter(struct perf_event_attr *attr, int cpu, struct task_struct *task, perf_overflow_handler_t overflow_handler, void *context);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff8120a1c0)
Location: kernel/events/core.c:11341
Inline: True
Direct callers:
  - kernel/watchdog_hld.c:hardlockup_detector_event_create
  - kernel/events/hw_breakpoint.c:register_wide_hw_breakpoint
  - kernel/events/hw_breakpoint.c:register_user_hw_breakpoint
```
**Symbols:**

```
ffffffff8120a1c0-ffffffff8120a2fb: perf_event_create_kernel_counter (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
struct perf_event *perf_event_create_kernel_counter(struct perf_event_attr *attr, int cpu, struct task_struct *task, perf_overflow_handler_t overflow_handler, void *context);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff811fcfb0)
Location: kernel/events/core.c:11341
Inline: True
Direct callers:
  - kernel/watchdog_hld.c:hardlockup_detector_event_create
  - kernel/events/hw_breakpoint.c:register_wide_hw_breakpoint
  - kernel/events/hw_breakpoint.c:register_user_hw_breakpoint
```
**Symbols:**

```
ffffffff811fcfb0-ffffffff811fd0eb: perf_event_create_kernel_counter (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
struct perf_event *perf_event_create_kernel_counter(struct perf_event_attr *attr, int cpu, struct task_struct *task, perf_overflow_handler_t overflow_handler, void *context);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff81207f60)
Location: kernel/events/core.c:11341
Inline: True
Direct callers:
  - kernel/watchdog_hld.c:hardlockup_detector_event_create
  - kernel/events/hw_breakpoint.c:register_wide_hw_breakpoint
  - kernel/events/hw_breakpoint.c:register_user_hw_breakpoint
```
**Symbols:**

```
ffffffff81207f60-ffffffff8120809b: perf_event_create_kernel_counter (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
struct perf_event *perf_event_create_kernel_counter(struct perf_event_attr *attr, int cpu, struct task_struct *task, perf_overflow_handler_t overflow_handler, void *context);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff81216d00)
Location: kernel/events/core.c:11341
Inline: True
Direct callers:
  - kernel/watchdog_hld.c:hardlockup_detector_event_create
  - kernel/events/hw_breakpoint.c:register_wide_hw_breakpoint
  - kernel/events/hw_breakpoint.c:register_user_hw_breakpoint
```
**Symbols:**

```
ffffffff81216d00-ffffffff81216e3b: perf_event_create_kernel_counter (STB_GLOBAL)
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
