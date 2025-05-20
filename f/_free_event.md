# Function: <code>_free_event</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void _free_event(struct perf_event *event);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff811806b0)
Location: kernel/events/core.c:3715
Inline: False
Direct callers:
  - kernel/events/core.c:free_event
```
**Symbols:**

```
ffffffff811806b0-ffffffff811808ce: _free_event (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void _free_event(struct perf_event *event);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff81192410)
Location: kernel/events/core.c:3966
Inline: False
Direct callers:
  - kernel/events/core.c:put_event
  - kernel/events/core.c:free_event
```
**Symbols:**

```
ffffffff81192410-ffffffff811926fa: _free_event (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void _free_event(struct perf_event *event);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff811a1bc0)
Location: kernel/events/core.c:4063
Inline: False
Direct callers:
  - kernel/events/core.c:put_event
  - kernel/events/core.c:free_event
```
**Symbols:**

```
ffffffff811a1bc0-ffffffff811a1ed4: _free_event (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void _free_event(struct perf_event *event);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff811a93b0)
Location: kernel/events/core.c:4150
Inline: False
Direct callers:
  - kernel/events/core.c:put_event
  - kernel/events/core.c:free_event
```
**Symbols:**

```
ffffffff811a93b0-ffffffff811a96a3: _free_event (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void _free_event(struct perf_event *event);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff811bcc10)
Location: kernel/events/core.c:4084
Inline: False
Direct callers:
  - kernel/events/core.c:put_event
  - kernel/events/core.c:free_event
```
**Symbols:**

```
ffffffff811bcc10-ffffffff811bcefe: _free_event (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void _free_event(struct perf_event *event);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff811dcdd0)
Location: kernel/events/core.c:4419
Inline: False
Direct callers:
  - kernel/events/core.c:put_event
  - kernel/events/core.c:free_event
```
**Symbols:**

```
ffffffff811dcdd0-ffffffff811dd0ff: _free_event (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void _free_event(struct perf_event *event);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff811ed1d0)
Location: kernel/events/core.c:4420
Inline: False
Direct callers:
  - kernel/events/core.c:put_event
  - kernel/events/core.c:free_event
```
**Symbols:**

```
ffffffff811ed1d0-ffffffff811ed4ff: _free_event (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void _free_event(struct perf_event *event);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff81204bc0)
Location: kernel/events/core.c:4446
Inline: False
Direct callers:
  - kernel/events/core.c:put_event
  - kernel/events/core.c:free_event
```
**Symbols:**

```
ffffffff81204bc0-ffffffff81204f32: _free_event (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void _free_event(struct perf_event *event);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff812117b0)
Location: kernel/events/core.c:4541
Inline: False
Direct callers:
  - kernel/events/core.c:put_event
  - kernel/events/core.c:free_event
```
**Symbols:**

```
ffffffff812117b0-ffffffff81211b22: _free_event (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void _free_event(struct perf_event *event);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff8123d890)
Location: kernel/events/core.c:4767
Inline: False
Direct callers:
  - kernel/events/core.c:perf_event_free_task
  - kernel/events/core.c:perf_event_exit_task_context
  - kernel/events/core.c:perf_mmap_close
  - kernel/events/core.c:perf_event_release_kernel
  - kernel/events/core.c:perf_event_release_kernel
  - kernel/events/core.c:free_event
  - kernel/events/core.c:perf_group_detach
  - kernel/events/core.c:perf_group_detach
```
**Symbols:**

```
ffffffff8123d890-ffffffff8123da5e: _free_event (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void _free_event(struct perf_event *event);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff81247c30)
Location: kernel/events/core.c:4846
Inline: False
Direct callers:
  - kernel/events/core.c:perf_event_free_task
  - kernel/events/core.c:perf_event_exit_task_context
  - kernel/events/core.c:perf_mmap_close
  - kernel/events/core.c:perf_event_release_kernel
  - kernel/events/core.c:perf_event_release_kernel
  - kernel/events/core.c:free_event
  - kernel/events/core.c:perf_group_detach
  - kernel/events/core.c:perf_group_detach
```
**Symbols:**

```
ffffffff81247c30-ffffffff81247e12: _free_event (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void _free_event(struct perf_event *event);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff8124baf0)
Location: kernel/events/core.c:4930
Inline: False
Direct callers:
  - kernel/events/core.c:perf_event_free_task
  - kernel/events/core.c:perf_event_exit_event
  - kernel/events/core.c:perf_mmap_close
  - kernel/events/core.c:perf_event_release_kernel
  - kernel/events/core.c:perf_event_release_kernel
  - kernel/events/core.c:free_event
  - kernel/events/core.c:perf_group_detach
  - kernel/events/core.c:perf_group_detach
```
**Symbols:**

```
ffffffff8124baf0-ffffffff8124bcd2: _free_event (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void _free_event(struct perf_event *event);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff812873b0)
Location: kernel/events/core.c:5036
Inline: False
Direct callers:
  - kernel/events/core.c:perf_event_free_task
  - kernel/events/core.c:perf_event_exit_event
  - kernel/events/core.c:perf_mmap_close
  - kernel/events/core.c:perf_event_release_kernel
  - kernel/events/core.c:perf_event_release_kernel
  - kernel/events/core.c:free_event
  - kernel/events/core.c:perf_group_detach
  - kernel/events/core.c:perf_group_detach
```
**Symbols:**

```
ffffffff812873b0-ffffffff81287592: _free_event (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void _free_event(struct perf_event *event);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff812dbb30)
Location: kernel/events/core.c:4934
Inline: False
Direct callers:
  - kernel/events/core.c:perf_event_free_task
  - kernel/events/core.c:perf_event_exit_event
  - kernel/events/core.c:perf_mmap_close
  - kernel/events/core.c:perf_event_release_kernel
  - kernel/events/core.c:perf_event_release_kernel
  - kernel/events/core.c:free_event
  - kernel/events/core.c:perf_group_detach
  - kernel/events/core.c:perf_group_detach
```
**Symbols:**

```
ffffffff812dbb30-ffffffff812dbd2f: _free_event (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void _free_event(struct perf_event *event);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff81343e00)
Location: kernel/events/core.c:5146
Inline: False
Direct callers:
  - kernel/events/core.c:perf_event_free_task
  - kernel/events/core.c:perf_event_exit_event
  - kernel/events/core.c:perf_pending_task
  - kernel/events/core.c:perf_mmap_close
  - kernel/events/core.c:perf_event_release_kernel
  - kernel/events/core.c:perf_event_release_kernel
  - kernel/events/core.c:free_event
  - kernel/events/core.c:perf_group_detach
  - kernel/events/core.c:perf_group_detach
```
**Symbols:**

```
ffffffff81343e00-ffffffff81344010: _free_event (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void _free_event(struct perf_event *event);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff81374e90)
Location: kernel/events/core.c:5146
Inline: False
Direct callers:
  - kernel/events/core.c:perf_event_free_task
  - kernel/events/core.c:perf_event_exit_event
  - kernel/events/core.c:perf_pending_task
  - kernel/events/core.c:perf_mmap_close
  - kernel/events/core.c:perf_event_release_kernel
  - kernel/events/core.c:perf_event_release_kernel
  - kernel/events/core.c:perf_group_detach
  - kernel/events/core.c:perf_group_detach
```
**Symbols:**

```
ffffffff81374e90-ffffffff813750a0: _free_event (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void _free_event(struct perf_event *event);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff8139e1c0)
Location: kernel/events/core.c:5195
Inline: False
Direct callers:
  - kernel/events/core.c:perf_event_free_task
  - kernel/events/core.c:perf_event_exit_event
  - kernel/events/core.c:perf_pending_task
  - kernel/events/core.c:perf_mmap_close
  - kernel/events/core.c:perf_event_release_kernel
  - kernel/events/core.c:perf_event_release_kernel
  - kernel/events/core.c:perf_group_detach
  - kernel/events/core.c:perf_group_detach
```
**Symbols:**

```
ffffffff8139e1c0-ffffffff8139e3d0: _free_event (STB_LOCAL)
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
void _free_event(struct perf_event *event);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffff80001029bb80)
Location: kernel/events/core.c:4541
Inline: False
Direct callers:
  - kernel/events/core.c:put_event
  - kernel/events/core.c:free_event
```
**Symbols:**

```
ffff80001029bb80-ffff80001029bfa0: _free_event (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void _free_event(struct perf_event *event);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (c04cb0b0)
Location: kernel/events/core.c:4541
Inline: False
Direct callers:
  - kernel/events/core.c:put_event
  - kernel/events/core.c:free_event
```
**Symbols:**

```
c04cb0b0-c04cb550: _free_event (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void _free_event(struct perf_event *event);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (c00000000034bbe0)
Location: kernel/events/core.c:4541
Inline: False
Direct callers:
  - kernel/events/core.c:put_event
  - kernel/events/core.c:free_event
```
**Symbols:**

```
c00000000034bbe0-c00000000034c1e8: _free_event (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void _free_event(struct perf_event *event);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffe0001c96be)
Location: kernel/events/core.c:4541
Inline: False
Direct callers:
  - kernel/events/core.c:perf_event_free_task
  - kernel/events/core.c:perf_event_exit_task
  - kernel/events/core.c:perf_mmap_close
  - kernel/events/core.c:perf_event_release_kernel
  - kernel/events/core.c:perf_event_release_kernel
  - kernel/events/core.c:free_event
  - kernel/events/core.c:perf_group_detach
  - kernel/events/core.c:perf_group_detach
```
**Symbols:**

```
ffffffe0001c96be-ffffffe0001c9a5e: _free_event (STB_LOCAL)
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
void _free_event(struct perf_event *event);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff81209e00)
Location: kernel/events/core.c:4541
Inline: False
Direct callers:
  - kernel/events/core.c:put_event
  - kernel/events/core.c:free_event
```
**Symbols:**

```
ffffffff81209e00-ffffffff8120a172: _free_event (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void _free_event(struct perf_event *event);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff811fcbb0)
Location: kernel/events/core.c:4541
Inline: False
Direct callers:
  - kernel/events/core.c:put_event
  - kernel/events/core.c:free_event
```
**Symbols:**

```
ffffffff811fcbb0-ffffffff811fcf6f: _free_event (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void _free_event(struct perf_event *event);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff81207ba0)
Location: kernel/events/core.c:4541
Inline: False
Direct callers:
  - kernel/events/core.c:put_event
  - kernel/events/core.c:free_event
```
**Symbols:**

```
ffffffff81207ba0-ffffffff81207f12: _free_event (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void _free_event(struct perf_event *event);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff81216930)
Location: kernel/events/core.c:4541
Inline: False
Direct callers:
  - kernel/events/core.c:put_event
  - kernel/events/core.c:free_event
```
**Symbols:**

```
ffffffff81216930-ffffffff81216cb9: _free_event (STB_LOCAL)
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
