# Function: <code>event_function_call</code>

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
void event_function_call(struct perf_event *event, event_f func, void *data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff8118fd20)
Location: kernel/events/core.c:245
Inline: False
Direct callers:
  - kernel/events/core.c:perf_pmu_migrate_context
  - kernel/events/core.c:SYSC_perf_event_open
  - kernel/events/core.c:SYSC_perf_event_open
  - kernel/events/core.c:perf_ioctl
  - kernel/events/core.c:perf_event_release_kernel
  - kernel/events/core.c:perf_event_release_kernel
  - kernel/events/core.c:_perf_event_enable
  - kernel/events/core.c:_perf_event_disable
```
**Symbols:**

```
ffffffff8118fd20-ffffffff8118fe44: event_function_call (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void event_function_call(struct perf_event *event, event_f func, void *data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff8119fc90)
Location: kernel/events/core.c:245
Inline: False
Direct callers:
  - kernel/events/core.c:perf_ioctl
  - kernel/events/core.c:_perf_event_enable
  - kernel/events/core.c:_perf_event_disable
  - kernel/events/core.c:perf_remove_from_context
```
**Symbols:**

```
ffffffff8119fc90-ffffffff8119fdb1: event_function_call (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void event_function_call(struct perf_event *event, event_f func, void *data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff811a78b0)
Location: kernel/events/core.c:249
Inline: False
Direct callers:
  - kernel/events/core.c:perf_ioctl
  - kernel/events/core.c:_perf_event_enable
  - kernel/events/core.c:_perf_event_disable
  - kernel/events/core.c:perf_remove_from_context
```
**Symbols:**

```
ffffffff811a78b0-ffffffff811a79d1: event_function_call (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void event_function_call(struct perf_event *event, event_f func, void *data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff811bb020)
Location: kernel/events/core.c:249
Inline: False
Direct callers:
  - kernel/events/core.c:perf_ioctl
  - kernel/events/core.c:_perf_event_enable
  - kernel/events/core.c:_perf_event_disable
  - kernel/events/core.c:perf_remove_from_context
```
**Symbols:**

```
ffffffff811bb020-ffffffff811bb143: event_function_call (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void event_function_call(struct perf_event *event, event_f func, void *data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff811daf40)
Location: kernel/events/core.c:249
Inline: False
Direct callers:
  - kernel/events/core.c:_perf_ioctl
  - kernel/events/core.c:_perf_event_enable
  - kernel/events/core.c:_perf_event_disable
  - kernel/events/core.c:perf_remove_from_context
```
**Symbols:**

```
ffffffff811daf40-ffffffff811db066: event_function_call (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void event_function_call(struct perf_event *event, event_f func, void *data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff811eb280)
Location: kernel/events/core.c:249
Inline: False
Direct callers:
  - kernel/events/core.c:_perf_ioctl
  - kernel/events/core.c:_perf_event_enable
  - kernel/events/core.c:_perf_event_disable
  - kernel/events/core.c:perf_remove_from_context
```
**Symbols:**

```
ffffffff811eb280-ffffffff811eb3a6: event_function_call (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void event_function_call(struct perf_event *event, event_f func, void *data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff81201d30)
Location: kernel/events/core.c:248
Inline: False
Direct callers:
  - kernel/events/core.c:_perf_ioctl
  - kernel/events/core.c:_perf_event_enable
  - kernel/events/core.c:_perf_event_disable
  - kernel/events/core.c:perf_remove_from_context
```
**Symbols:**

```
ffffffff81201d30-ffffffff81201e52: event_function_call (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void event_function_call(struct perf_event *event, event_f func, void *data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff8120ebe0)
Location: kernel/events/core.c:248
Inline: False
Direct callers:
  - kernel/events/core.c:_perf_ioctl
  - kernel/events/core.c:_perf_event_enable
  - kernel/events/core.c:_perf_event_disable
  - kernel/events/core.c:perf_remove_from_context
```
**Symbols:**

```
ffffffff8120ebe0-ffffffff8120ed02: event_function_call (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void event_function_call(struct perf_event *event, event_f func, void *data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff81238a60)
Location: kernel/events/core.c:255
Inline: False
Direct callers:
  - kernel/events/core.c:perf_pmu_migrate_context
  - kernel/events/core.c:__do_sys_perf_event_open
  - kernel/events/core.c:_perf_event_period
  - kernel/events/core.c:_perf_event_enable
  - kernel/events/core.c:_perf_event_disable
```
**Symbols:**

```
ffffffff81238a60-ffffffff81238bbe: event_function_call (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void event_function_call(struct perf_event *event, event_f func, void *data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff812429e0)
Location: kernel/events/core.c:258
Inline: False
Direct callers:
  - kernel/events/core.c:perf_pmu_migrate_context
  - kernel/events/core.c:__do_sys_perf_event_open
  - kernel/events/core.c:_perf_event_period
  - kernel/events/core.c:_perf_event_enable
  - kernel/events/core.c:_perf_event_disable
```
**Symbols:**

```
ffffffff812429e0-ffffffff81242b3d: event_function_call (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void event_function_call(struct perf_event *event, event_f func, void *data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff81247e40)
Location: kernel/events/core.c:259
Inline: False
Direct callers:
  - kernel/events/core.c:_perf_event_period
  - kernel/events/core.c:_perf_event_enable
  - kernel/events/core.c:_perf_event_disable
  - kernel/events/core.c:perf_remove_from_context
```
**Symbols:**

```
ffffffff81247e40-ffffffff81247f9d: event_function_call (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void event_function_call(struct perf_event *event, event_f func, void *data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff812821a0)
Location: kernel/events/core.c:260
Inline: False
Direct callers:
  - kernel/events/core.c:_perf_event_period
  - kernel/events/core.c:_perf_event_enable
  - kernel/events/core.c:_perf_event_disable
  - kernel/events/core.c:perf_remove_from_context
```
**Symbols:**

```
ffffffff812821a0-ffffffff812822fd: event_function_call (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void event_function_call(struct perf_event *event, event_f func, void *data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff812d1980)
Location: kernel/events/core.c:260
Inline: False
Direct callers:
  - kernel/events/core.c:perf_event_task_disable
  - kernel/events/core.c:perf_event_task_disable
  - kernel/events/core.c:_perf_ioctl
  - kernel/events/core.c:_perf_ioctl
  - kernel/events/core.c:_perf_event_period
  - kernel/events/core.c:perf_event_pause
  - kernel/events/core.c:_perf_event_enable
  - kernel/events/core.c:perf_event_disable
  - kernel/events/core.c:perf_remove_from_context
```
**Symbols:**

```
ffffffff812d1980-ffffffff812d1ae7: event_function_call (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void event_function_call(struct perf_event *event, event_f func, void *data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff8133a750)
Location: kernel/events/core.c:263
Inline: False
Direct callers:
  - kernel/events/core.c:perf_event_task_disable
  - kernel/events/core.c:perf_event_task_disable
  - kernel/events/core.c:_perf_ioctl
  - kernel/events/core.c:_perf_ioctl
  - kernel/events/core.c:_perf_event_period
  - kernel/events/core.c:perf_event_pause
  - kernel/events/core.c:_perf_event_enable
  - kernel/events/core.c:perf_event_disable
  - kernel/events/core.c:perf_remove_from_context
```
**Symbols:**

```
ffffffff8133a750-ffffffff8133a8b0: event_function_call (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void event_function_call(struct perf_event *event, event_f func, void *data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff8136b630)
Location: kernel/events/core.c:263
Inline: False
Direct callers:
  - kernel/events/core.c:perf_event_task_disable
  - kernel/events/core.c:perf_event_task_disable
  - kernel/events/core.c:_perf_ioctl
  - kernel/events/core.c:_perf_ioctl
  - kernel/events/core.c:_perf_event_period
  - kernel/events/core.c:perf_event_pause
  - kernel/events/core.c:_perf_event_enable
  - kernel/events/core.c:perf_event_disable
  - kernel/events/core.c:perf_remove_from_context
```
**Symbols:**

```
ffffffff8136b630-ffffffff8136b790: event_function_call (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void event_function_call(struct perf_event *event, event_f func, void *data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff813942b0)
Location: kernel/events/core.c:263
Inline: False
Direct callers:
  - kernel/events/core.c:perf_event_task_disable
  - kernel/events/core.c:perf_event_task_disable
  - kernel/events/core.c:_perf_ioctl
  - kernel/events/core.c:_perf_ioctl
  - kernel/events/core.c:_perf_event_period
  - kernel/events/core.c:perf_event_pause
  - kernel/events/core.c:_perf_event_enable
  - kernel/events/core.c:perf_event_disable
  - kernel/events/core.c:perf_remove_from_context
```
**Symbols:**

```
ffffffff813942b0-ffffffff81394410: event_function_call (STB_LOCAL)
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
void event_function_call(struct perf_event *event, event_f func, void *data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffff8000102956d8)
Location: kernel/events/core.c:248
Inline: False
Direct callers:
  - kernel/events/core.c:_perf_ioctl
  - kernel/events/core.c:_perf_event_enable
  - kernel/events/core.c:_perf_event_disable
  - kernel/events/core.c:perf_remove_from_context
```
**Symbols:**

```
ffff8000102956d8-ffff8000102958a0: event_function_call (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void event_function_call(struct perf_event *event, event_f func, void *data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (c04c0d78)
Location: kernel/events/core.c:248
Inline: False
Direct callers:
  - kernel/events/core.c:_perf_ioctl
  - kernel/events/core.c:_perf_event_enable
  - kernel/events/core.c:_perf_event_disable
  - kernel/events/core.c:perf_remove_from_context
```
**Symbols:**

```
c04c0d78-c04c0ec0: event_function_call (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void event_function_call(struct perf_event *event, event_f func, void *data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (c000000000345b10)
Location: kernel/events/core.c:248
Inline: False
Direct callers:
  - kernel/events/core.c:_perf_ioctl
  - kernel/events/core.c:_perf_event_enable
  - kernel/events/core.c:_perf_event_disable
  - kernel/events/core.c:perf_remove_from_context
```
**Symbols:**

```
c000000000345b10-c000000000345d7c: event_function_call (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void event_function_call(struct perf_event *event, event_f func, void *data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffe0001c8ac0)
Location: kernel/events/core.c:248
Inline: False
Direct callers:
  - kernel/events/core.c:_perf_ioctl
  - kernel/events/core.c:_perf_event_enable
  - kernel/events/core.c:_perf_event_disable
  - kernel/events/core.c:perf_remove_from_context
```
**Symbols:**

```
ffffffe0001c8ac0-ffffffe0001c8c16: event_function_call (STB_LOCAL)
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
void event_function_call(struct perf_event *event, event_f func, void *data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff81207200)
Location: kernel/events/core.c:248
Inline: False
Direct callers:
  - kernel/events/core.c:_perf_ioctl
  - kernel/events/core.c:_perf_event_enable
  - kernel/events/core.c:_perf_event_disable
  - kernel/events/core.c:perf_remove_from_context
```
**Symbols:**

```
ffffffff81207200-ffffffff81207322: event_function_call (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void event_function_call(struct perf_event *event, event_f func, void *data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff811f9e30)
Location: kernel/events/core.c:248
Inline: False
Direct callers:
  - kernel/events/core.c:_perf_ioctl
  - kernel/events/core.c:_perf_event_enable
  - kernel/events/core.c:_perf_event_disable
  - kernel/events/core.c:perf_remove_from_context
```
**Symbols:**

```
ffffffff811f9e30-ffffffff811f9f46: event_function_call (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void event_function_call(struct perf_event *event, event_f func, void *data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff81204fd0)
Location: kernel/events/core.c:248
Inline: False
Direct callers:
  - kernel/events/core.c:_perf_ioctl
  - kernel/events/core.c:_perf_event_enable
  - kernel/events/core.c:_perf_event_disable
  - kernel/events/core.c:perf_remove_from_context
```
**Symbols:**

```
ffffffff81204fd0-ffffffff812050f2: event_function_call (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void event_function_call(struct perf_event *event, event_f func, void *data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff8120c800)
Location: kernel/events/core.c:248
Inline: False
Direct callers:
  - kernel/events/core.c:_perf_ioctl
  - kernel/events/core.c:_perf_event_enable
  - kernel/events/core.c:_perf_event_disable
  - kernel/events/core.c:perf_remove_from_context
```
**Symbols:**

```
ffffffff8120c800-ffffffff8120c919: event_function_call (STB_LOCAL)
```
</details>
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
