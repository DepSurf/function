# Function: <code>list_del_event</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline ⚠️</summary>

```c
void list_del_event(struct perf_event *event, struct perf_event_context *ctx);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff8117a0c0)
Location: kernel/events/core.c:1403
Inline: True
Direct callers:
  - kernel/events/core.c:__perf_remove_from_context
  - kernel/events/core.c:perf_remove_from_context
  - kernel/events/core.c:perf_free_event
```
**Symbols:**

```
ffffffff8117a0c0-ffffffff8117a1ce: list_del_event (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
void list_del_event(struct perf_event *event, struct perf_event_context *ctx);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff8118ae40)
Location: kernel/events/core.c:1656
Inline: True
Direct callers:
  - kernel/events/core.c:perf_free_event
  - kernel/events/core.c:perf_event_exit_task
```
**Symbols:**

```
ffffffff8118ae40-ffffffff8118af4f: list_del_event (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
void list_del_event(struct perf_event *event, struct perf_event_context *ctx);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff8119b6a0)
Location: kernel/events/core.c:1662
Inline: True
Direct callers:
  - kernel/events/core.c:perf_free_event
  - kernel/events/core.c:perf_event_exit_task
```
**Symbols:**

```
ffffffff8119b6a0-ffffffff8119b7ac: list_del_event (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
void list_del_event(struct perf_event *event, struct perf_event_context *ctx);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff811a1c60)
Location: kernel/events/core.c:1675
Inline: True
Direct callers:
  - kernel/events/core.c:perf_event_free_task
  - kernel/events/core.c:perf_event_exit_task
```
**Symbols:**

```
ffffffff811a1c60-ffffffff811a1d70: list_del_event (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void list_del_event(struct perf_event *event, struct perf_event_context *ctx);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff811b58d0)
Location: kernel/events/core.c:1674
Inline: False
Direct callers:
  - kernel/events/core.c:perf_event_free_task
  - kernel/events/core.c:perf_event_exit_task
  - kernel/events/core.c:__perf_remove_from_context
```
**Symbols:**

```
ffffffff811b58d0-ffffffff811b59e1: list_del_event (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void list_del_event(struct perf_event *event, struct perf_event_context *ctx);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff811d4830)
Location: kernel/events/core.c:1856
Inline: False
Direct callers:
  - kernel/events/core.c:perf_event_free_task
  - kernel/events/core.c:perf_event_exit_task
  - kernel/events/core.c:__perf_remove_from_context
```
**Symbols:**

```
ffffffff811d4830-ffffffff811d4948: list_del_event (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void list_del_event(struct perf_event *event, struct perf_event_context *ctx);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff811e44f0)
Location: kernel/events/core.c:1856
Inline: False
Direct callers:
  - kernel/events/core.c:perf_event_free_task
  - kernel/events/core.c:perf_event_exit_task
  - kernel/events/core.c:__perf_remove_from_context
```
**Symbols:**

```
ffffffff811e44f0-ffffffff811e4608: list_del_event (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void list_del_event(struct perf_event *event, struct perf_event_context *ctx);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff811fb7f0)
Location: kernel/events/core.c:1858
Inline: False
Direct callers:
  - kernel/events/core.c:perf_event_free_task
  - kernel/events/core.c:perf_event_exit_task
  - kernel/events/core.c:__perf_remove_from_context
```
**Symbols:**

```
ffffffff811fb7f0-ffffffff811fb913: list_del_event (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
void list_del_event(struct perf_event *event, struct perf_event_context *ctx);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff8120a1c0)
Location: kernel/events/core.c:1858
Inline: True
Direct callers:
  - kernel/events/core.c:perf_event_free_task
  - kernel/events/core.c:perf_event_exit_task
  - kernel/events/core.c:__perf_remove_from_context
```
**Symbols:**

```
ffffffff8120a1c0-ffffffff8120a2e3: list_del_event (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void list_del_event(struct perf_event *event, struct perf_event_context *ctx);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff81234a80)
Location: kernel/events/core.c:1985
Inline: False
Direct callers:
  - kernel/events/core.c:perf_event_free_task
  - kernel/events/core.c:perf_event_exit_task_context
  - kernel/events/core.c:__perf_remove_from_context
```
**Symbols:**

```
ffffffff81234a80-ffffffff81234bea: list_del_event (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void list_del_event(struct perf_event *event, struct perf_event_context *ctx);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff8123ea90)
Location: kernel/events/core.c:2009
Inline: False
Direct callers:
  - kernel/events/core.c:perf_event_free_task
  - kernel/events/core.c:perf_event_exit_task_context
  - kernel/events/core.c:__perf_remove_from_context
```
**Symbols:**

```
ffffffff8123ea90-ffffffff8123ebfa: list_del_event (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void list_del_event(struct perf_event *event, struct perf_event_context *ctx);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff81242720)
Location: kernel/events/core.c:1992
Inline: False
Direct callers:
  - kernel/events/core.c:perf_event_free_task
  - kernel/events/core.c:__perf_remove_from_context
```
**Symbols:**

```
ffffffff81242720-ffffffff8124287b: list_del_event (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void list_del_event(struct perf_event *event, struct perf_event_context *ctx);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff81280860)
Location: kernel/events/core.c:2060
Inline: False
Direct callers:
  - kernel/events/core.c:perf_event_free_task
  - kernel/events/core.c:__perf_remove_from_context
```
**Symbols:**

```
ffffffff81280860-ffffffff81280a02: list_del_event (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
void list_del_event(struct perf_event *event, struct perf_event_context *ctx);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff812d56d0)
Location: kernel/events/core.c:1971
Inline: True
Direct callers:
  - kernel/events/core.c:perf_event_free_task
  - kernel/events/core.c:__perf_remove_from_context
```
**Symbols:**

```
ffffffff812d56d0-ffffffff812d589e: list_del_event (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
void list_del_event(struct perf_event *event, struct perf_event_context *ctx);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff8133c3f0)
Location: kernel/events/core.c:1974
Inline: True
Direct callers:
  - kernel/events/core.c:perf_event_free_task
  - kernel/events/core.c:__perf_remove_from_context
```
**Symbols:**

```
ffffffff8133c3f0-ffffffff8133c58e: list_del_event (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
void list_del_event(struct perf_event *event, struct perf_event_context *ctx);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff8136d420)
Location: kernel/events/core.c:1974
Inline: True
Direct callers:
  - kernel/events/core.c:perf_event_free_task
  - kernel/events/core.c:__perf_remove_from_context
```
**Symbols:**

```
ffffffff8136d420-ffffffff8136d5b3: list_del_event (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
void list_del_event(struct perf_event *event, struct perf_event_context *ctx);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff81398110)
Location: kernel/events/core.c:2011
Inline: True
Direct callers:
  - kernel/events/core.c:perf_event_free_task
  - kernel/events/core.c:__perf_remove_from_context
```
**Symbols:**

```
ffffffff81398110-ffffffff813982af: list_del_event (STB_LOCAL)
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
void list_del_event(struct perf_event *event, struct perf_event_context *ctx);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffff800010293ab0)
Location: kernel/events/core.c:1858
Inline: False
Direct callers:
  - kernel/events/core.c:perf_event_free_task
  - kernel/events/core.c:perf_event_exit_task_context
  - kernel/events/core.c:__perf_remove_from_context
```
**Symbols:**

```
ffff800010293ab0-ffff800010293bd4: list_del_event (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
void list_del_event(struct perf_event *event, struct perf_event_context *ctx);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (c04c4b28)
Location: kernel/events/core.c:1858
Inline: True
Direct callers:
  - kernel/events/core.c:perf_event_free_task
  - kernel/events/core.c:perf_event_exit_task_context
  - kernel/events/core.c:__perf_remove_from_context
```
**Symbols:**

```
c04c4b28-c04c4c78: list_del_event (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
void list_del_event(struct perf_event *event, struct perf_event_context *ctx);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (c000000000342590)
Location: kernel/events/core.c:1858
Inline: True
Direct callers:
  - kernel/events/core.c:perf_event_free_task
  - kernel/events/core.c:perf_event_exit_task
  - kernel/events/core.c:__perf_remove_from_context
```
**Symbols:**

```
c000000000342590-c000000000342738: list_del_event (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
void list_del_event(struct perf_event *event, struct perf_event_context *ctx);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffe0001c65da)
Location: kernel/events/core.c:1858
Inline: True
Direct callers:
  - kernel/events/core.c:perf_event_free_task
  - kernel/events/core.c:perf_event_exit_task
  - kernel/events/core.c:__perf_remove_from_context
```
**Symbols:**

```
ffffffe0001c65da-ffffffe0001c66de: list_del_event (STB_LOCAL)
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
void list_del_event(struct perf_event *event, struct perf_event_context *ctx);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff812027e0)
Location: kernel/events/core.c:1858
Inline: True
Direct callers:
  - kernel/events/core.c:perf_event_free_task
  - kernel/events/core.c:perf_event_exit_task
  - kernel/events/core.c:__perf_remove_from_context
```
**Symbols:**

```
ffffffff812027e0-ffffffff81202903: list_del_event (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
void list_del_event(struct perf_event *event, struct perf_event_context *ctx);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff811f5530)
Location: kernel/events/core.c:1858
Inline: True
Direct callers:
  - kernel/events/core.c:perf_event_free_task
  - kernel/events/core.c:perf_event_exit_task
  - kernel/events/core.c:__perf_remove_from_context
```
**Symbols:**

```
ffffffff811f5530-ffffffff811f5653: list_del_event (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
void list_del_event(struct perf_event *event, struct perf_event_context *ctx);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff812005b0)
Location: kernel/events/core.c:1858
Inline: True
Direct callers:
  - kernel/events/core.c:perf_event_free_task
  - kernel/events/core.c:perf_event_exit_task
  - kernel/events/core.c:__perf_remove_from_context
```
**Symbols:**

```
ffffffff812005b0-ffffffff812006d3: list_del_event (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
void list_del_event(struct perf_event *event, struct perf_event_context *ctx);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff8120f640)
Location: kernel/events/core.c:1858
Inline: True
Direct callers:
  - kernel/events/core.c:perf_event_free_task
  - kernel/events/core.c:perf_event_exit_task
  - kernel/events/core.c:perf_event_exit_task
  - kernel/events/core.c:__perf_remove_from_context
```
**Symbols:**

```
ffffffff8120f640-ffffffff8120f763: list_del_event (STB_LOCAL)
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
