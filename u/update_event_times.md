# Function: <code>update_event_times</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void update_event_times(struct perf_event *event);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff81178480)
Location: kernel/events/core.c:1154
Inline: False
Direct callers:
  - kernel/events/core.c:update_group_times
  - kernel/events/core.c:update_group_times
  - kernel/events/core.c:__perf_event_read
  - kernel/events/core.c:__perf_event_read
  - kernel/events/core.c:__perf_event_task_sched_out
```
**Symbols:**

```
ffffffff81178480-ffffffff8117853f: update_event_times (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void update_event_times(struct perf_event *event);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff81188730)
Location: kernel/events/core.c:1402
Inline: False
Direct callers:
  - kernel/events/core.c:__perf_event_read
  - kernel/events/core.c:__perf_event_read
  - kernel/events/core.c:__perf_event_task_sched_out
  - kernel/events/core.c:update_group_times
  - kernel/events/core.c:update_group_times
```
**Symbols:**

```
ffffffff81188730-ffffffff811887f5: update_event_times (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void update_event_times(struct perf_event *event);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff81197b10)
Location: kernel/events/core.c:1410
Inline: False
Direct callers:
  - kernel/events/core.c:__perf_event_read
  - kernel/events/core.c:__perf_event_read
  - kernel/events/core.c:__perf_event_task_sched_out
  - kernel/events/core.c:update_group_times
  - kernel/events/core.c:update_group_times
```
**Symbols:**

```
ffffffff81197b10-ffffffff81197bd2: update_event_times (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void update_event_times(struct perf_event *event);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff8119f6d0)
Location: kernel/events/core.c:1402
Inline: False
Direct callers:
  - kernel/events/core.c:__perf_event_read
  - kernel/events/core.c:__perf_event_read
  - kernel/events/core.c:__perf_event_task_sched_out
  - kernel/events/core.c:update_group_times
  - kernel/events/core.c:update_group_times
```
**Symbols:**

```
ffffffff8119f6d0-ffffffff8119f7a0: update_event_times (STB_LOCAL)
```
</details>
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
No changes between <code>4.4</code> and <code>4.8</code> ✅
</li>
<li>
No changes between <code>4.8</code> and <code>4.10</code> ✅
</li>
<li>
No changes between <code>4.10</code> and <code>4.13</code> ✅
</li>
</ul>
