# Function: <code>perf_get_aux_event</code>

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
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
int perf_get_aux_event(struct perf_event *event, struct perf_event *group_leader);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff812098b0)
Location: kernel/events/core.c:1949
Inline: True
Direct callers:
  - kernel/events/core.c:__do_sys_perf_event_open
```
**Symbols:**

```
ffffffff812098b0-ffffffff81209929: perf_get_aux_event (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
int perf_get_aux_event(struct perf_event *event, struct perf_event *group_leader);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff81231720)
Location: kernel/events/core.c:2081
Inline: True
Direct callers:
  - kernel/events/core.c:__do_sys_perf_event_open
```
**Symbols:**

```
ffffffff81231720-ffffffff812317df: perf_get_aux_event (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
int perf_get_aux_event(struct perf_event *event, struct perf_event *group_leader);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff8123b390)
Location: kernel/events/core.c:2105
Inline: True
Direct callers:
  - kernel/events/core.c:__do_sys_perf_event_open
```
**Symbols:**

```
ffffffff8123b390-ffffffff8123b44f: perf_get_aux_event (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
int perf_get_aux_event(struct perf_event *event, struct perf_event *group_leader);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff8123fb50)
Location: kernel/events/core.c:2088
Inline: True
Direct callers:
  - kernel/events/core.c:__do_sys_perf_event_open
```
**Symbols:**

```
ffffffff8123fb50-ffffffff8123fc0f: perf_get_aux_event (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
int perf_get_aux_event(struct perf_event *event, struct perf_event *group_leader);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff8127a3f0)
Location: kernel/events/core.c:2156
Inline: True
Direct callers:
  - kernel/events/core.c:__do_sys_perf_event_open
```
**Symbols:**

```
ffffffff8127a3f0-ffffffff8127a4af: perf_get_aux_event (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int perf_get_aux_event(struct perf_event *event, struct perf_event *group_leader);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff812cc6a0)
Location: kernel/events/core.c:2069
Inline: False
Direct callers:
  - kernel/events/core.c:__do_sys_perf_event_open
```
**Symbols:**

```
ffffffff812cc6a0-ffffffff812cc78b: perf_get_aux_event (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int perf_get_aux_event(struct perf_event *event, struct perf_event *group_leader);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff81334500)
Location: kernel/events/core.c:2071
Inline: False
Direct callers:
  - kernel/events/core.c:__do_sys_perf_event_open
```
**Symbols:**

```
ffffffff81334500-ffffffff813345eb: perf_get_aux_event (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int perf_get_aux_event(struct perf_event *event, struct perf_event *group_leader);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff81365240)
Location: kernel/events/core.c:2071
Inline: False
Direct callers:
  - kernel/events/core.c:__do_sys_perf_event_open
```
**Symbols:**

```
ffffffff81365240-ffffffff8136532b: perf_get_aux_event (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int perf_get_aux_event(struct perf_event *event, struct perf_event *group_leader);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff8138e260)
Location: kernel/events/core.c:2108
Inline: False
Direct callers:
  - kernel/events/core.c:__do_sys_perf_event_open
```
**Symbols:**

```
ffffffff8138e260-ffffffff8138e34b: perf_get_aux_event (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Selective Inline ⚠️</summary>

```c
int perf_get_aux_event(struct perf_event *event, struct perf_event *group_leader);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffff800010293c98)
Location: kernel/events/core.c:1949
Inline: True
Direct callers:
  - kernel/events/core.c:__do_sys_perf_event_open
```
**Symbols:**

```
ffff800010293c98-ffff800010293d4c: perf_get_aux_event (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
int perf_get_aux_event(struct perf_event *event, struct perf_event *group_leader);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (c04c6148)
Location: kernel/events/core.c:1949
Inline: True
Direct callers:
  - kernel/events/core.c:__do_sys_perf_event_open
```
**Symbols:**

```
c04c6148-c04c61e0: perf_get_aux_event (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
int perf_get_aux_event(struct perf_event *event, struct perf_event *group_leader);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (c0000000003407c0)
Location: kernel/events/core.c:1949
Inline: True
Direct callers:
  - kernel/events/core.c:__do_sys_perf_event_open
```
**Symbols:**

```
c0000000003407c0-c0000000003408a0: perf_get_aux_event (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
int perf_get_aux_event(struct perf_event *event, struct perf_event *group_leader);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffe0001c48c6)
Location: kernel/events/core.c:1949
Inline: True
Direct callers:
  - kernel/events/core.c:__do_sys_perf_event_open
```
**Symbols:**

```
ffffffe0001c48c6-ffffffe0001c4930: perf_get_aux_event (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Selective Inline ⚠️</summary>

```c
int perf_get_aux_event(struct perf_event *event, struct perf_event *group_leader);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff81201ed0)
Location: kernel/events/core.c:1949
Inline: True
Direct callers:
  - kernel/events/core.c:__do_sys_perf_event_open
```
**Symbols:**

```
ffffffff81201ed0-ffffffff81201f49: perf_get_aux_event (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
int perf_get_aux_event(struct perf_event *event, struct perf_event *group_leader);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff811f4c20)
Location: kernel/events/core.c:1949
Inline: True
Direct callers:
  - kernel/events/core.c:__do_sys_perf_event_open
```
**Symbols:**

```
ffffffff811f4c20-ffffffff811f4c99: perf_get_aux_event (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
int perf_get_aux_event(struct perf_event *event, struct perf_event *group_leader);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff811ffca0)
Location: kernel/events/core.c:1949
Inline: True
Direct callers:
  - kernel/events/core.c:__do_sys_perf_event_open
```
**Symbols:**

```
ffffffff811ffca0-ffffffff811ffd19: perf_get_aux_event (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
int perf_get_aux_event(struct perf_event *event, struct perf_event *group_leader);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff8120ed30)
Location: kernel/events/core.c:1949
Inline: True
Direct callers:
  - kernel/events/core.c:__do_sys_perf_event_open
```
**Symbols:**

```
ffffffff8120ed30-ffffffff8120eda9: perf_get_aux_event (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
