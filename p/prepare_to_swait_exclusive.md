# Function: <code>prepare_to_swait_exclusive</code>

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
<summary>In <code>5.0</code>: ✅</summary>

```c
void prepare_to_swait_exclusive(struct swait_queue_head *q, struct swait_queue *wait, int state);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/swait.c (ffffffff810e3610)
Location: kernel/sched/swait.c:79
Inline: False
Direct callers:
  - arch/x86/kernel/kvm.c:kvm_async_pf_task_wait
```
**Symbols:**

```
ffffffff810e3610-ffffffff810e3695: prepare_to_swait_exclusive (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void prepare_to_swait_exclusive(struct swait_queue_head *q, struct swait_queue *wait, int state);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/swait.c (ffffffff810ea220)
Location: kernel/sched/swait.c:79
Inline: False
Direct callers:
  - arch/x86/kernel/kvm.c:kvm_async_pf_task_wait
```
**Symbols:**

```
ffffffff810ea220-ffffffff810ea2a5: prepare_to_swait_exclusive (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void prepare_to_swait_exclusive(struct swait_queue_head *q, struct swait_queue *wait, int state);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/swait.c (ffffffff810f5bf0)
Location: kernel/sched/swait.c:79
Inline: False
Direct callers:
  - arch/x86/kernel/kvm.c:kvm_async_pf_task_wait
```
**Symbols:**

```
ffffffff810f5bf0-ffffffff810f5c75: prepare_to_swait_exclusive (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void prepare_to_swait_exclusive(struct swait_queue_head *q, struct swait_queue *wait, int state);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/swait.c (ffffffff810ff3d0)
Location: kernel/sched/swait.c:92
Inline: False
Direct callers:
  - arch/x86/kernel/kvm.c:kvm_async_pf_task_wait_schedule
```
**Symbols:**

```
ffffffff810ff3d0-ffffffff810ff455: prepare_to_swait_exclusive (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void prepare_to_swait_exclusive(struct swait_queue_head *q, struct swait_queue *wait, int state);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/swait.c (ffffffff810fded0)
Location: kernel/sched/swait.c:92
Inline: False
Direct callers:
  - arch/x86/kernel/kvm.c:kvm_async_pf_task_wait_schedule
```
**Symbols:**

```
ffffffff810fded0-ffffffff810fdf55: prepare_to_swait_exclusive (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void prepare_to_swait_exclusive(struct swait_queue_head *q, struct swait_queue *wait, int state);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/swait.c (ffffffff811002b0)
Location: kernel/sched/swait.c:92
Inline: False
Direct callers:
  - arch/x86/kernel/kvm.c:kvm_async_pf_task_wait_schedule
```
**Symbols:**

```
ffffffff811002b0-ffffffff81100335: prepare_to_swait_exclusive (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void prepare_to_swait_exclusive(struct swait_queue_head *q, struct swait_queue *wait, int state);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/swait.c (ffffffff8111c350)
Location: kernel/sched/swait.c:92
Inline: False
Direct callers:
  - arch/x86/kernel/kvm.c:kvm_async_pf_task_wait_schedule
```
**Symbols:**

```
ffffffff8111c350-ffffffff8111c3bf: prepare_to_swait_exclusive (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void prepare_to_swait_exclusive(struct swait_queue_head *q, struct swait_queue *wait, int state);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/build_utility.c (ffffffff8113b730)
Location: kernel/sched/swait.c:91
Inline: False
Direct callers:
  - arch/x86/kernel/kvm.c:kvm_async_pf_task_wait_schedule
```
**Symbols:**

```
ffffffff8113b730-ffffffff8113b7ad: prepare_to_swait_exclusive (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void prepare_to_swait_exclusive(struct swait_queue_head *q, struct swait_queue *wait, int state);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/build_utility.c (ffffffff81166130)
Location: kernel/sched/swait.c:91
Inline: False
Direct callers:
  - arch/x86/kernel/kvm.c:kvm_async_pf_task_wait_schedule
```
**Symbols:**

```
ffffffff81166130-ffffffff811661ad: prepare_to_swait_exclusive (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void prepare_to_swait_exclusive(struct swait_queue_head *q, struct swait_queue *wait, int state);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/build_utility.c (ffffffff811765a0)
Location: kernel/sched/swait.c:91
Inline: False
Direct callers:
  - arch/x86/kernel/kvm.c:kvm_async_pf_task_wait_schedule
```
**Symbols:**

```
ffffffff811765a0-ffffffff8117661d: prepare_to_swait_exclusive (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void prepare_to_swait_exclusive(struct swait_queue_head *q, struct swait_queue *wait, int state);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/build_utility.c (ffffffff81184820)
Location: kernel/sched/swait.c:91
Inline: False
Direct callers:
  - arch/x86/kernel/kvm.c:kvm_async_pf_task_wait_schedule
```
**Symbols:**

```
ffffffff81184820-ffffffff8118489d: prepare_to_swait_exclusive (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: ✅</summary>

```c
void prepare_to_swait_exclusive(struct swait_queue_head *q, struct swait_queue *wait, int state);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/swait.c (ffff8000101596c0)
Location: kernel/sched/swait.c:79
Inline: False
Direct callers:
  - virt/kvm/kvm_main.c:kvm_vcpu_block
```
**Symbols:**

```
ffff8000101596c0-ffff8000101597e0: prepare_to_swait_exclusive (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void prepare_to_swait_exclusive(struct swait_queue_head *q, struct swait_queue *wait, int state);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/swait.c (c03a65f8)
Location: kernel/sched/swait.c:79
Inline: False
```
**Symbols:**

```
c03a65f8-c03a66bc: prepare_to_swait_exclusive (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void prepare_to_swait_exclusive(struct swait_queue_head *q, struct swait_queue *wait, int state);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/swait.c (c0000000001ad730)
Location: kernel/sched/swait.c:79
Inline: False
```
**Symbols:**

```
c0000000001ad730-c0000000001ad804: prepare_to_swait_exclusive (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void prepare_to_swait_exclusive(struct swait_queue_head *q, struct swait_queue *wait, int state);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/swait.c (ffffffe0000ff320)
Location: kernel/sched/swait.c:79
Inline: False
```
**Symbols:**

```
ffffffe0000ff320-ffffffe0000ff38c: prepare_to_swait_exclusive (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: ✅</summary>

```c
void prepare_to_swait_exclusive(struct swait_queue_head *q, struct swait_queue *wait, int state);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/swait.c (ffffffff810eeff0)
Location: kernel/sched/swait.c:79
Inline: False
Direct callers:
  - arch/x86/kernel/kvm.c:kvm_async_pf_task_wait
```
**Symbols:**

```
ffffffff810eeff0-ffffffff810ef075: prepare_to_swait_exclusive (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void prepare_to_swait_exclusive(struct swait_queue_head *q, struct swait_queue *wait, int state);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/swait.c (ffffffff810df070)
Location: kernel/sched/swait.c:79
Inline: False
Direct callers:
  - arch/x86/kernel/kvm.c:kvm_async_pf_task_wait
```
**Symbols:**

```
ffffffff810df070-ffffffff810df0f5: prepare_to_swait_exclusive (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void prepare_to_swait_exclusive(struct swait_queue_head *q, struct swait_queue *wait, int state);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/swait.c (ffffffff810ec120)
Location: kernel/sched/swait.c:79
Inline: False
Direct callers:
  - arch/x86/kernel/kvm.c:kvm_async_pf_task_wait
```
**Symbols:**

```
ffffffff810ec120-ffffffff810ec1a5: prepare_to_swait_exclusive (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void prepare_to_swait_exclusive(struct swait_queue_head *q, struct swait_queue *wait, int state);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/swait.c (ffffffff810f7170)
Location: kernel/sched/swait.c:79
Inline: False
Direct callers:
  - arch/x86/kernel/kvm.c:kvm_async_pf_task_wait
```
**Symbols:**

```
ffffffff810f7170-ffffffff810f71f5: prepare_to_swait_exclusive (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
