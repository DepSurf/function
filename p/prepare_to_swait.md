# Function: <code>prepare_to_swait</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void prepare_to_swait(struct swait_queue_head *q, struct swait_queue *wait, int state);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/swait.c (ffffffff810c7460)
Location: kernel/sched/swait.c:82
Inline: False
Direct callers:
  - arch/x86/kernel/kvm.c:kvm_async_pf_task_wait
  - kernel/sched/swait.c:prepare_to_swait_event
```
**Symbols:**

```
ffffffff810c7460-ffffffff810c74e5: prepare_to_swait (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void prepare_to_swait(struct swait_queue_head *q, struct swait_queue *wait, int state);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/swait.c (ffffffff810cd330)
Location: kernel/sched/swait.c:82
Inline: False
Direct callers:
  - arch/x86/kernel/kvm.c:kvm_async_pf_task_wait
  - kernel/sched/swait.c:prepare_to_swait_event
```
**Symbols:**

```
ffffffff810cd330-ffffffff810cd3b6: prepare_to_swait (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void prepare_to_swait(struct swait_queue_head *q, struct swait_queue *wait, int state);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/swait.c (ffffffff810c9d30)
Location: kernel/sched/swait.c:82
Inline: False
Direct callers:
  - arch/x86/kernel/kvm.c:kvm_async_pf_task_wait
  - kernel/sched/swait.c:prepare_to_swait_event
```
**Symbols:**

```
ffffffff810c9d30-ffffffff810c9db7: prepare_to_swait (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void prepare_to_swait(struct swait_queue_head *q, struct swait_queue *wait, int state);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/swait.c (ffffffff810d1550)
Location: kernel/sched/swait.c:77
Inline: False
Direct callers:
  - arch/x86/kernel/kvm.c:kvm_async_pf_task_wait
  - kernel/sched/swait.c:prepare_to_swait_event
```
**Symbols:**

```
ffffffff810d1550-ffffffff810d15d7: prepare_to_swait (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void prepare_to_swait(struct swait_queue_head *q, struct swait_queue *wait, int state);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/swait.c (ffffffff810d9b10)
Location: kernel/sched/swait.c:79
Inline: False
Direct callers:
  - arch/x86/kernel/kvm.c:kvm_async_pf_task_wait
  - kernel/sched/swait.c:prepare_to_swait_event
```
**Symbols:**

```
ffffffff810d9b10-ffffffff810d9b96: prepare_to_swait (STB_GLOBAL)
```
</details>
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
In <code>6.5</code>: Absent ⚠️
</li>
<li>
In <code>6.8</code>: Absent ⚠️
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
<b>Regular</b>
<ul>
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
</ul>
