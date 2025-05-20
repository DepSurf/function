# Function: <code>calc_timer_values</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff8117bb2c)
Location: kernel/events/core.c:4400
Inline: True
Inline callers:
  - kernel/events/core.c:perf_output_read
  - kernel/events/core.c:perf_event_update_userpage
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff8118d0bf)
Location: kernel/events/core.c:4690
Inline: True
Inline callers:
  - kernel/events/core.c:perf_output_read
  - kernel/events/core.c:perf_event_update_userpage
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff8119c6ff)
Location: kernel/events/core.c:4787
Inline: True
Inline callers:
  - kernel/events/core.c:perf_output_read
  - kernel/events/core.c:perf_event_update_userpage
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
In kernel/events/core.c (ffffffff811a4dc0)
Location: kernel/events/core.c:4879
Inline: True
Inline callers:
  - kernel/events/core.c:perf_output_read
  - kernel/events/core.c:perf_event_update_userpage
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void calc_timer_values(struct perf_event *event, u64 *now, u64 *enabled, u64 *running);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff811b3450)
Location: kernel/events/core.c:4830
Inline: False
Direct callers:
  - kernel/events/core.c:perf_output_read
  - kernel/events/core.c:perf_event_update_userpage
```
**Symbols:**

```
ffffffff811b3450-ffffffff811b34f0: calc_timer_values (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void calc_timer_values(struct perf_event *event, u64 *now, u64 *enabled, u64 *running);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff811d2bb0)
Location: kernel/events/core.c:5186
Inline: False
Direct callers:
  - kernel/events/core.c:perf_output_read
  - kernel/events/core.c:perf_event_update_userpage
```
**Symbols:**

```
ffffffff811d2bb0-ffffffff811d2c53: calc_timer_values (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void calc_timer_values(struct perf_event *event, u64 *now, u64 *enabled, u64 *running);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff811e2ec0)
Location: kernel/events/core.c:5195
Inline: False
Direct callers:
  - kernel/events/core.c:perf_output_read
  - kernel/events/core.c:perf_event_update_userpage
```
**Symbols:**

```
ffffffff811e2ec0-ffffffff811e2f63: calc_timer_values (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void calc_timer_values(struct perf_event *event, u64 *now, u64 *enabled, u64 *running);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff811fa090)
Location: kernel/events/core.c:5241
Inline: False
Direct callers:
  - kernel/events/core.c:perf_output_read
  - kernel/events/core.c:perf_event_update_userpage
```
**Symbols:**

```
ffffffff811fa090-ffffffff811fa139: calc_timer_values (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void calc_timer_values(struct perf_event *event, u64 *now, u64 *enabled, u64 *running);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff81207160)
Location: kernel/events/core.c:5336
Inline: False
Direct callers:
  - kernel/events/core.c:perf_output_read
  - kernel/events/core.c:perf_event_update_userpage
```
**Symbols:**

```
ffffffff81207160-ffffffff81207209: calc_timer_values (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void calc_timer_values(struct perf_event *event, u64 *now, u64 *enabled, u64 *running);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff81230650)
Location: kernel/events/core.c:5605
Inline: False
Direct callers:
  - kernel/events/core.c:perf_output_read
  - kernel/events/core.c:perf_event_update_userpage
```
**Symbols:**

```
ffffffff81230650-ffffffff812306f9: calc_timer_values (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void calc_timer_values(struct perf_event *event, u64 *now, u64 *enabled, u64 *running);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff8123a2b0)
Location: kernel/events/core.c:5684
Inline: False
Direct callers:
  - kernel/events/core.c:perf_output_read
  - kernel/events/core.c:perf_event_update_userpage
```
**Symbols:**

```
ffffffff8123a2b0-ffffffff8123a359: calc_timer_values (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void calc_timer_values(struct perf_event *event, u64 *now, u64 *enabled, u64 *running);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff8123eae0)
Location: kernel/events/core.c:5768
Inline: False
Direct callers:
  - kernel/events/core.c:perf_output_read
  - kernel/events/core.c:perf_event_update_userpage
```
**Symbols:**

```
ffffffff8123eae0-ffffffff8123eb86: calc_timer_values (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void calc_timer_values(struct perf_event *event, u64 *now, u64 *enabled, u64 *running);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff8127a950)
Location: kernel/events/core.c:4493
Inline: False
Direct callers:
  - kernel/events/core.c:perf_output_read
  - kernel/events/core.c:perf_event_update_userpage
  - kernel/events/core.c:perf_event_read_local
```
**Symbols:**

```
ffffffff8127a950-ffffffff8127aa99: calc_timer_values (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void calc_timer_values(struct perf_event *event, u64 *now, u64 *enabled, u64 *running);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff812ce500)
Location: kernel/events/core.c:4391
Inline: False
Direct callers:
  - kernel/events/core.c:perf_output_read
  - kernel/events/core.c:perf_event_update_userpage
  - kernel/events/core.c:perf_event_read_local
```
**Symbols:**

```
ffffffff812ce500-ffffffff812ce657: calc_timer_values (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void calc_timer_values(struct perf_event *event, u64 *now, u64 *enabled, u64 *running);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff81336090)
Location: kernel/events/core.c:4511
Inline: False
Direct callers:
  - kernel/events/core.c:perf_output_read
  - kernel/events/core.c:perf_event_update_userpage
  - kernel/events/core.c:perf_event_read_local
```
**Symbols:**

```
ffffffff81336090-ffffffff813361e4: calc_timer_values (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void calc_timer_values(struct perf_event *event, u64 *now, u64 *enabled, u64 *running);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff81366de0)
Location: kernel/events/core.c:4511
Inline: False
Direct callers:
  - kernel/events/core.c:perf_output_read
  - kernel/events/core.c:perf_event_update_userpage
  - kernel/events/core.c:perf_event_read_local
```
**Symbols:**

```
ffffffff81366de0-ffffffff81366f2d: calc_timer_values (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void calc_timer_values(struct perf_event *event, u64 *now, u64 *enabled, u64 *running);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff8138ff50)
Location: kernel/events/core.c:4546
Inline: False
Direct callers:
  - kernel/events/core.c:perf_output_read
  - kernel/events/core.c:perf_event_update_userpage
  - kernel/events/core.c:perf_event_read_local
```
**Symbols:**

```
ffffffff8138ff50-ffffffff8139009d: calc_timer_values (STB_LOCAL)
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
void calc_timer_values(struct perf_event *event, u64 *now, u64 *enabled, u64 *running);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffff800010290cf0)
Location: kernel/events/core.c:5336
Inline: False
Direct callers:
  - kernel/events/core.c:perf_output_read
  - kernel/events/core.c:perf_event_update_userpage
```
**Symbols:**

```
ffff800010290cf0-ffff800010290d90: calc_timer_values (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void calc_timer_values(struct perf_event *event, u64 *now, u64 *enabled, u64 *running);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (c04c046c)
Location: kernel/events/core.c:5336
Inline: False
Direct callers:
  - kernel/events/core.c:perf_output_read
  - kernel/events/core.c:perf_event_update_userpage
```
**Symbols:**

```
c04c046c-c04c0530: calc_timer_values (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void calc_timer_values(struct perf_event *event, u64 *now, u64 *enabled, u64 *running);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (c00000000033dc60)
Location: kernel/events/core.c:5336
Inline: False
Direct callers:
  - kernel/events/core.c:perf_output_read
  - kernel/events/core.c:perf_event_update_userpage
```
**Symbols:**

```
c00000000033dc60-c00000000033dd50: calc_timer_values (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void calc_timer_values(struct perf_event *event, u64 *now, u64 *enabled, u64 *running);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffe0001c36fa)
Location: kernel/events/core.c:5336
Inline: False
Direct callers:
  - kernel/events/core.c:perf_output_read
  - kernel/events/core.c:perf_event_update_userpage
```
**Symbols:**

```
ffffffe0001c36fa-ffffffe0001c3782: calc_timer_values (STB_LOCAL)
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
void calc_timer_values(struct perf_event *event, u64 *now, u64 *enabled, u64 *running);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff811ff780)
Location: kernel/events/core.c:5336
Inline: False
Direct callers:
  - kernel/events/core.c:perf_output_read
  - kernel/events/core.c:perf_event_update_userpage
```
**Symbols:**

```
ffffffff811ff780-ffffffff811ff829: calc_timer_values (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void calc_timer_values(struct perf_event *event, u64 *now, u64 *enabled, u64 *running);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff811f24d0)
Location: kernel/events/core.c:5336
Inline: False
Direct callers:
  - kernel/events/core.c:perf_output_read
  - kernel/events/core.c:perf_event_update_userpage
```
**Symbols:**

```
ffffffff811f24d0-ffffffff811f2579: calc_timer_values (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void calc_timer_values(struct perf_event *event, u64 *now, u64 *enabled, u64 *running);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff811fd550)
Location: kernel/events/core.c:5336
Inline: False
Direct callers:
  - kernel/events/core.c:perf_output_read
  - kernel/events/core.c:perf_event_update_userpage
```
**Symbols:**

```
ffffffff811fd550-ffffffff811fd5f9: calc_timer_values (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void calc_timer_values(struct perf_event *event, u64 *now, u64 *enabled, u64 *running);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff8120c2b0)
Location: kernel/events/core.c:5336
Inline: False
Direct callers:
  - kernel/events/core.c:perf_output_read
  - kernel/events/core.c:perf_event_update_userpage
```
**Symbols:**

```
ffffffff8120c2b0-ffffffff8120c359: calc_timer_values (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
