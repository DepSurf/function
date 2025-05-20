# Function: <code>__bpf_trace_workqueue_work</code>

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
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
void __bpf_trace_workqueue_work(void *__data, struct work_struct *work);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/workqueue.c (ffffffff810aa550)
Location: include/trace/events/workqueue.h:11
Inline: True
```
**Symbols:**

```
ffffffff810aa550-ffffffff810aa55b: __bpf_trace_workqueue_work (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
void __bpf_trace_workqueue_work(void *__data, struct work_struct *work);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/workqueue.c (ffffffff810b3620)
Location: include/trace/events/workqueue.h:11
Inline: True
```
**Symbols:**

```
ffffffff810b3620-ffffffff810b362b: __bpf_trace_workqueue_work (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void __bpf_trace_workqueue_work(void *__data, struct work_struct *work);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/workqueue.c (ffffffff810b91d0)
Location: include/trace/events/workqueue.h:11
Inline: False
```
**Symbols:**

```
ffffffff810b91d0-ffffffff810b91db: __bpf_trace_workqueue_work (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void __bpf_trace_workqueue_work(void *__data, struct work_struct *work);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/workqueue.c (ffffffff810bf710)
Location: include/trace/events/workqueue.h:11
Inline: False
```
**Symbols:**

```
ffffffff810bf710-ffffffff810bf71b: __bpf_trace_workqueue_work (STB_LOCAL)
```
</details>
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
<details>
<summary>In <code>arm64</code>: Selective Inline ⚠️</summary>

```c
void __bpf_trace_workqueue_work(void *__data, struct work_struct *work);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/workqueue.c (ffff80001011c198)
Location: include/trace/events/workqueue.h:11
Inline: True
```
**Symbols:**

```
ffff80001011c198-ffff80001011c1ac: __bpf_trace_workqueue_work (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void __bpf_trace_workqueue_work(void *__data, struct work_struct *work);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/workqueue.c (c0370f08)
Location: include/trace/events/workqueue.h:11
Inline: False
```
**Symbols:**

```
c0370f08-c0370f24: __bpf_trace_workqueue_work (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void __bpf_trace_workqueue_work(void *__data, struct work_struct *work);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/workqueue.c (c000000000164960)
Location: include/trace/events/workqueue.h:11
Inline: False
```
**Symbols:**

```
c000000000164960-c00000000016498c: __bpf_trace_workqueue_work (STB_LOCAL)
```
</details>
</li>
<li>
In <code>riscv64</code>: Absent ⚠️
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: ✅</summary>

```c
void __bpf_trace_workqueue_work(void *__data, struct work_struct *work);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/workqueue.c (ffffffff810b9a80)
Location: include/trace/events/workqueue.h:11
Inline: False
```
**Symbols:**

```
ffffffff810b9a80-ffffffff810b9a8b: __bpf_trace_workqueue_work (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void __bpf_trace_workqueue_work(void *__data, struct work_struct *work);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/workqueue.c (ffffffff810a83c0)
Location: include/trace/events/workqueue.h:11
Inline: False
```
**Symbols:**

```
ffffffff810a83c0-ffffffff810a83cb: __bpf_trace_workqueue_work (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void __bpf_trace_workqueue_work(void *__data, struct work_struct *work);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/workqueue.c (ffffffff810b8fe0)
Location: include/trace/events/workqueue.h:11
Inline: False
```
**Symbols:**

```
ffffffff810b8fe0-ffffffff810b8feb: __bpf_trace_workqueue_work (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void __bpf_trace_workqueue_work(void *__data, struct work_struct *work);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/workqueue.c (ffffffff810c1a40)
Location: include/trace/events/workqueue.h:11
Inline: False
```
**Symbols:**

```
ffffffff810c1a40-ffffffff810c1a4b: __bpf_trace_workqueue_work (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>4.18</code> and <code>5.0</code> ✅
</li>
<li>
No changes between <code>5.0</code> and <code>5.3</code> ✅
</li>
<li>
No changes between <code>5.3</code> and <code>5.4</code> ✅
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
