# Function: <code>__traceiter_workqueue_queue_work</code>

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
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int __traceiter_workqueue_queue_work(void *__data, unsigned int req_cpu, struct pool_workqueue *pwq, struct work_struct *work);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/workqueue.c (ffffffff810c1150)
Location: include/trace/events/workqueue.h:23
Inline: False
```
**Symbols:**

```
ffffffff810c1150-ffffffff810c11a1: __traceiter_workqueue_queue_work (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int __traceiter_workqueue_queue_work(void *__data, unsigned int req_cpu, struct pool_workqueue *pwq, struct work_struct *work);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/workqueue.c (ffffffff810c2b40)
Location: include/trace/events/workqueue.h:23
Inline: False
```
**Symbols:**

```
ffffffff810c2b40-ffffffff810c2b8f: __traceiter_workqueue_queue_work (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int __traceiter_workqueue_queue_work(void *__data, unsigned int req_cpu, struct pool_workqueue *pwq, struct work_struct *work);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/workqueue.c (ffffffff810d5680)
Location: include/trace/events/workqueue.h:23
Inline: False
```
**Symbols:**

```
ffffffff810d5680-ffffffff810d56cf: __traceiter_workqueue_queue_work (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int __traceiter_workqueue_queue_work(void *__data, int req_cpu, struct pool_workqueue *pwq, struct work_struct *work);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/workqueue.c (ffffffff810ee510)
Location: include/trace/events/workqueue.h:23
Inline: False
```
**Symbols:**

```
ffffffff810ee510-ffffffff810ee56b: __traceiter_workqueue_queue_work (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int __traceiter_workqueue_queue_work(void *__data, int req_cpu, struct pool_workqueue *pwq, struct work_struct *work);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/workqueue.c (ffffffff8110fa40)
Location: include/trace/events/workqueue.h:23
Inline: False
```
**Symbols:**

```
ffffffff8110fa40-ffffffff8110fa9b: __traceiter_workqueue_queue_work (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int __traceiter_workqueue_queue_work(void *__data, int req_cpu, struct pool_workqueue *pwq, struct work_struct *work);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/workqueue.c (ffffffff8111bec0)
Location: include/trace/events/workqueue.h:23
Inline: False
```
**Symbols:**

```
ffffffff8111bec0-ffffffff8111bf1b: __traceiter_workqueue_queue_work (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int __traceiter_workqueue_queue_work(void *__data, int req_cpu, struct pool_workqueue *pwq, struct work_struct *work);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/workqueue.c (ffffffff811259e0)
Location: include/trace/events/workqueue.h:23
Inline: False
```
**Symbols:**

```
ffffffff811259e0-ffffffff81125a3b: __traceiter_workqueue_queue_work (STB_GLOBAL)
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
<b>Regular</b>
<ul>
<li>
No changes between <code>5.11</code> and <code>5.13</code> ✅
</li>
<li>
No changes between <code>5.13</code> and <code>5.15</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>5.15</code> and <code>5.19</code> ⚠️</summary>
<ul>
<li>
<b>Param type changed. </b>
<code>unsigned int req_cpu</code> ➡️ <code>int req_cpu</code>
</li>
</ul>
</details>
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
