# Function: <code>perf_event_groups_insert</code>

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
<summary>In <code>4.18</code>: ✅</summary>

```c
void perf_event_groups_insert(struct perf_event_groups *groups, struct perf_event *event);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff811d3510)
Location: kernel/events/core.c:1550
Inline: False
Direct callers:
  - kernel/events/core.c:perf_group_detach
  - kernel/events/core.c:list_add_event
  - kernel/events/core.c:perf_mux_hrtimer_handler
  - kernel/events/core.c:perf_mux_hrtimer_handler
  - kernel/events/core.c:perf_mux_hrtimer_handler
```
**Symbols:**

```
ffffffff811d3510-ffffffff811d3589: perf_event_groups_insert (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void perf_event_groups_insert(struct perf_event_groups *groups, struct perf_event *event);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff811e38b0)
Location: kernel/events/core.c:1550
Inline: False
Direct callers:
  - kernel/events/core.c:perf_group_detach
  - kernel/events/core.c:list_add_event
  - kernel/events/core.c:perf_mux_hrtimer_handler
  - kernel/events/core.c:perf_mux_hrtimer_handler
  - kernel/events/core.c:perf_mux_hrtimer_handler
```
**Symbols:**

```
ffffffff811e38b0-ffffffff811e3929: perf_event_groups_insert (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void perf_event_groups_insert(struct perf_event_groups *groups, struct perf_event *event);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff811faa70)
Location: kernel/events/core.c:1552
Inline: False
Direct callers:
  - kernel/events/core.c:perf_group_detach
  - kernel/events/core.c:list_add_event
  - kernel/events/core.c:perf_mux_hrtimer_handler
  - kernel/events/core.c:perf_mux_hrtimer_handler
  - kernel/events/core.c:perf_mux_hrtimer_handler
```
**Symbols:**

```
ffffffff811faa70-ffffffff811faaf8: perf_event_groups_insert (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void perf_event_groups_insert(struct perf_event_groups *groups, struct perf_event *event);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff81207b40)
Location: kernel/events/core.c:1552
Inline: False
Direct callers:
  - kernel/events/core.c:perf_group_detach
  - kernel/events/core.c:list_add_event
  - kernel/events/core.c:perf_mux_hrtimer_handler
  - kernel/events/core.c:perf_mux_hrtimer_handler
  - kernel/events/core.c:perf_mux_hrtimer_handler
```
**Symbols:**

```
ffffffff81207b40-ffffffff81207bc8: perf_event_groups_insert (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void perf_event_groups_insert(struct perf_event_groups *groups, struct perf_event *event);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff81230a70)
Location: kernel/events/core.c:1638
Inline: False
Direct callers:
  - kernel/events/core.c:perf_rotate_context
  - kernel/events/core.c:perf_rotate_context
  - kernel/events/core.c:perf_group_detach
  - kernel/events/core.c:list_add_event
```
**Symbols:**

```
ffffffff81230a70-ffffffff81230b3c: perf_event_groups_insert (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void perf_event_groups_insert(struct perf_event_groups *groups, struct perf_event *event);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff8123a680)
Location: kernel/events/core.c:1656
Inline: False
Direct callers:
  - kernel/events/core.c:perf_rotate_context
  - kernel/events/core.c:perf_rotate_context
  - kernel/events/core.c:perf_group_detach
  - kernel/events/core.c:list_add_event
```
**Symbols:**

```
ffffffff8123a680-ffffffff8123a74c: perf_event_groups_insert (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void perf_event_groups_insert(struct perf_event_groups *groups, struct perf_event *event);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff8123eed0)
Location: kernel/events/core.c:1695
Inline: False
Direct callers:
  - kernel/events/core.c:perf_group_detach
  - kernel/events/core.c:list_add_event
  - kernel/events/core.c:perf_mux_hrtimer_handler
  - kernel/events/core.c:perf_mux_hrtimer_handler
```
**Symbols:**

```
ffffffff8123eed0-ffffffff8123efbc: perf_event_groups_insert (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void perf_event_groups_insert(struct perf_event_groups *groups, struct perf_event *event);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff81279900)
Location: kernel/events/core.c:1763
Inline: False
Direct callers:
  - kernel/events/core.c:perf_group_detach
  - kernel/events/core.c:list_add_event
  - kernel/events/core.c:perf_mux_hrtimer_handler
  - kernel/events/core.c:perf_mux_hrtimer_handler
```
**Symbols:**

```
ffffffff81279900-ffffffff812799ec: perf_event_groups_insert (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void perf_event_groups_insert(struct perf_event_groups *groups, struct perf_event *event);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff812ccae0)
Location: kernel/events/core.c:1672
Inline: False
Direct callers:
  - kernel/events/core.c:perf_group_detach
  - kernel/events/core.c:list_add_event
  - kernel/events/core.c:perf_mux_hrtimer_handler
  - kernel/events/core.c:perf_mux_hrtimer_handler
```
**Symbols:**

```
ffffffff812ccae0-ffffffff812ccbeb: perf_event_groups_insert (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void perf_event_groups_insert(struct perf_event_groups *groups, struct perf_event *event);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff81334ad0)
Location: kernel/events/core.c:1667
Inline: False
Direct callers:
  - kernel/events/core.c:perf_rotate_context
  - kernel/events/core.c:perf_rotate_context
  - kernel/events/core.c:perf_group_detach
  - kernel/events/core.c:list_add_event
```
**Symbols:**

```
ffffffff81334ad0-ffffffff81334c00: perf_event_groups_insert (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void perf_event_groups_insert(struct perf_event_groups *groups, struct perf_event *event);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff81365810)
Location: kernel/events/core.c:1667
Inline: False
Direct callers:
  - kernel/events/core.c:perf_rotate_context
  - kernel/events/core.c:perf_rotate_context
  - kernel/events/core.c:perf_group_detach
  - kernel/events/core.c:list_add_event
```
**Symbols:**

```
ffffffff81365810-ffffffff81365940: perf_event_groups_insert (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void perf_event_groups_insert(struct perf_event_groups *groups, struct perf_event *event);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff8138e930)
Location: kernel/events/core.c:1678
Inline: False
Direct callers:
  - kernel/events/core.c:perf_rotate_context
  - kernel/events/core.c:perf_rotate_context
  - kernel/events/core.c:perf_group_detach
  - kernel/events/core.c:list_add_event
```
**Symbols:**

```
ffffffff8138e930-ffffffff8138ea60: perf_event_groups_insert (STB_LOCAL)
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
void perf_event_groups_insert(struct perf_event_groups *groups, struct perf_event *event);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffff800010291340)
Location: kernel/events/core.c:1552
Inline: False
Direct callers:
  - kernel/events/core.c:perf_group_detach
  - kernel/events/core.c:list_add_event
  - kernel/events/core.c:perf_mux_hrtimer_handler
  - kernel/events/core.c:perf_mux_hrtimer_handler
  - kernel/events/core.c:perf_mux_hrtimer_handler
```
**Symbols:**

```
ffff800010291340-ffff8000102913e8: perf_event_groups_insert (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void perf_event_groups_insert(struct perf_event_groups *groups, struct perf_event *event);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (c04c2088)
Location: kernel/events/core.c:1552
Inline: False
Direct callers:
  - kernel/events/core.c:perf_group_detach
  - kernel/events/core.c:list_add_event
  - kernel/events/core.c:perf_mux_hrtimer_handler
  - kernel/events/core.c:perf_mux_hrtimer_handler
  - kernel/events/core.c:perf_mux_hrtimer_handler
```
**Symbols:**

```
c04c2088-c04c2138: perf_event_groups_insert (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void perf_event_groups_insert(struct perf_event_groups *groups, struct perf_event *event);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (c00000000033f210)
Location: kernel/events/core.c:1552
Inline: False
Direct callers:
  - kernel/events/core.c:perf_group_detach
  - kernel/events/core.c:list_add_event
  - kernel/events/core.c:perf_mux_hrtimer_handler
  - kernel/events/core.c:perf_mux_hrtimer_handler
  - kernel/events/core.c:perf_mux_hrtimer_handler
```
**Symbols:**

```
c00000000033f210-c00000000033f30c: perf_event_groups_insert (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void perf_event_groups_insert(struct perf_event_groups *groups, struct perf_event *event);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffe0001c3db6)
Location: kernel/events/core.c:1552
Inline: False
Direct callers:
  - kernel/events/core.c:perf_group_detach
  - kernel/events/core.c:list_add_event
  - kernel/events/core.c:perf_mux_hrtimer_handler
  - kernel/events/core.c:perf_mux_hrtimer_handler
  - kernel/events/core.c:perf_mux_hrtimer_handler
```
**Symbols:**

```
ffffffe0001c3db6-ffffffe0001c3e22: perf_event_groups_insert (STB_LOCAL)
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
void perf_event_groups_insert(struct perf_event_groups *groups, struct perf_event *event);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff81200160)
Location: kernel/events/core.c:1552
Inline: False
Direct callers:
  - kernel/events/core.c:perf_group_detach
  - kernel/events/core.c:list_add_event
  - kernel/events/core.c:perf_mux_hrtimer_handler
  - kernel/events/core.c:perf_mux_hrtimer_handler
  - kernel/events/core.c:perf_mux_hrtimer_handler
```
**Symbols:**

```
ffffffff81200160-ffffffff812001e8: perf_event_groups_insert (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void perf_event_groups_insert(struct perf_event_groups *groups, struct perf_event *event);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff811f2f60)
Location: kernel/events/core.c:1552
Inline: False
Direct callers:
  - kernel/events/core.c:perf_group_detach
  - kernel/events/core.c:list_add_event
  - kernel/events/core.c:perf_mux_hrtimer_handler
  - kernel/events/core.c:perf_mux_hrtimer_handler
  - kernel/events/core.c:perf_mux_hrtimer_handler
```
**Symbols:**

```
ffffffff811f2f60-ffffffff811f2fe8: perf_event_groups_insert (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void perf_event_groups_insert(struct perf_event_groups *groups, struct perf_event *event);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff811fdf30)
Location: kernel/events/core.c:1552
Inline: False
Direct callers:
  - kernel/events/core.c:perf_group_detach
  - kernel/events/core.c:list_add_event
  - kernel/events/core.c:perf_mux_hrtimer_handler
  - kernel/events/core.c:perf_mux_hrtimer_handler
  - kernel/events/core.c:perf_mux_hrtimer_handler
```
**Symbols:**

```
ffffffff811fdf30-ffffffff811fdfb8: perf_event_groups_insert (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void perf_event_groups_insert(struct perf_event_groups *groups, struct perf_event *event);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff8120d040)
Location: kernel/events/core.c:1552
Inline: False
Direct callers:
  - kernel/events/core.c:perf_group_detach
  - kernel/events/core.c:list_add_event
  - kernel/events/core.c:perf_mux_hrtimer_handler
  - kernel/events/core.c:perf_mux_hrtimer_handler
  - kernel/events/core.c:perf_mux_hrtimer_handler
```
**Symbols:**

```
ffffffff8120d040-ffffffff8120d0c8: perf_event_groups_insert (STB_LOCAL)
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
