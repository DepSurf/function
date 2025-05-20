# Function: <code>__traceiter_workqueue_execute_end</code>

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
int __traceiter_workqueue_execute_end(void *__data, struct work_struct *work, work_func_t function);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/workqueue.c (ffffffff810c1230)
Location: include/trace/events/workqueue.h:108
Inline: False
```
**Symbols:**

```
ffffffff810c1230-ffffffff810c1277: __traceiter_workqueue_execute_end (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int __traceiter_workqueue_execute_end(void *__data, struct work_struct *work, work_func_t function);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/workqueue.c (ffffffff810c2c10)
Location: include/trace/events/workqueue.h:108
Inline: False
```
**Symbols:**

```
ffffffff810c2c10-ffffffff810c2c55: __traceiter_workqueue_execute_end (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int __traceiter_workqueue_execute_end(void *__data, struct work_struct *work, work_func_t function);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/workqueue.c (ffffffff810d5750)
Location: include/trace/events/workqueue.h:108
Inline: False
```
**Symbols:**

```
ffffffff810d5750-ffffffff810d5795: __traceiter_workqueue_execute_end (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int __traceiter_workqueue_execute_end(void *__data, struct work_struct *work, work_func_t function);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/workqueue.c (ffffffff810ee610)
Location: include/trace/events/workqueue.h:108
Inline: False
```
**Symbols:**

```
ffffffff810ee610-ffffffff810ee65f: __traceiter_workqueue_execute_end (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int __traceiter_workqueue_execute_end(void *__data, struct work_struct *work, work_func_t function);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/workqueue.c (ffffffff8110fb70)
Location: include/trace/events/workqueue.h:108
Inline: False
```
**Symbols:**

```
ffffffff8110fb70-ffffffff8110fbbf: __traceiter_workqueue_execute_end (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int __traceiter_workqueue_execute_end(void *__data, struct work_struct *work, work_func_t function);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/workqueue.c (ffffffff8111c030)
Location: include/trace/events/workqueue.h:108
Inline: False
```
**Symbols:**

```
ffffffff8111c030-ffffffff8111c07f: __traceiter_workqueue_execute_end (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int __traceiter_workqueue_execute_end(void *__data, struct work_struct *work, work_func_t function);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/workqueue.c (ffffffff81125b50)
Location: include/trace/events/workqueue.h:108
Inline: False
```
**Symbols:**

```
ffffffff81125b50-ffffffff81125b9f: __traceiter_workqueue_execute_end (STB_GLOBAL)
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
