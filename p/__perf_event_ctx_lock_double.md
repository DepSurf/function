# Function: <code>__perf_event_ctx_lock_double</code>

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
<details>
<summary>In <code>4.10</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff811a36bf)
Location: kernel/events/core.c:9585
Inline: True
Inline callers:
  - kernel/events/core.c:SYSC_perf_event_open
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff811aad2a)
Location: kernel/events/core.c:9808
Inline: True
Inline callers:
  - kernel/events/core.c:SYSC_perf_event_open
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff811be646)
Location: kernel/events/core.c:9835
Inline: True
Inline callers:
  - kernel/events/core.c:SYSC_perf_event_open
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (0)
Location: kernel/events/core.c:10364
Inline: True
Inline callers:
  - kernel/events/core.c:__do_sys_perf_event_open
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (0)
Location: kernel/events/core.c:10407
Inline: True
Inline callers:
  - kernel/events/core.c:__do_sys_perf_event_open
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (0)
Location: kernel/events/core.c:10754
Inline: True
Inline callers:
  - kernel/events/core.c:__do_sys_perf_event_open
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (0)
Location: kernel/events/core.c:10855
Inline: True
Inline callers:
  - kernel/events/core.c:__do_sys_perf_event_open
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
struct perf_event_context *__perf_event_ctx_lock_double(struct perf_event *group_leader, struct perf_event_context *ctx);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff812344f0)
Location: kernel/events/core.c:11450
Inline: False
Direct callers:
  - kernel/events/core.c:__do_sys_perf_event_open
```
**Symbols:**

```
ffffffff812344f0-ffffffff81234596: __perf_event_ctx_lock_double (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
struct perf_event_context *__perf_event_ctx_lock_double(struct perf_event *group_leader, struct perf_event_context *ctx);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff8123ee20)
Location: kernel/events/core.c:11734
Inline: False
Direct callers:
  - kernel/events/core.c:__do_sys_perf_event_open
```
**Symbols:**

```
ffffffff8123ee20-ffffffff8123eed4: __perf_event_ctx_lock_double (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (0)
Location: kernel/events/core.c:11901
Inline: True
Inline callers:
  - kernel/events/core.c:__do_sys_perf_event_open
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (0)
Location: kernel/events/core.c:12013
Inline: True
Inline callers:
  - kernel/events/core.c:__do_sys_perf_event_open
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (0)
Location: kernel/events/core.c:11969
Inline: True
Inline callers:
  - kernel/events/core.c:__do_sys_perf_event_open
```
</details>
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
<summary>In <code>arm64</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (0)
Location: kernel/events/core.c:10855
Inline: True
Inline callers:
  - kernel/events/core.c:__do_sys_perf_event_open
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (0)
Location: kernel/events/core.c:10855
Inline: True
Inline callers:
  - kernel/events/core.c:__do_sys_perf_event_open
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (0)
Location: kernel/events/core.c:10855
Inline: True
Inline callers:
  - kernel/events/core.c:__do_sys_perf_event_open
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffe0001cba7e)
Location: kernel/events/core.c:10855
Inline: True
Inline callers:
  - kernel/events/core.c:__do_sys_perf_event_open
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (0)
Location: kernel/events/core.c:10855
Inline: True
Inline callers:
  - kernel/events/core.c:__do_sys_perf_event_open
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (0)
Location: kernel/events/core.c:10855
Inline: True
Inline callers:
  - kernel/events/core.c:__do_sys_perf_event_open
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (0)
Location: kernel/events/core.c:10855
Inline: True
Inline callers:
  - kernel/events/core.c:__do_sys_perf_event_open
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (0)
Location: kernel/events/core.c:10855
Inline: True
Inline callers:
  - kernel/events/core.c:__do_sys_perf_event_open
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>5.8</code> and <code>5.11</code> ✅
</li>
</ul>
