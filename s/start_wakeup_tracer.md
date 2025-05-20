# Function: <code>start_wakeup_tracer</code>

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
In kernel/trace/trace_sched_wakeup.c (ffffffff81157ad3)
Location: kernel/trace/trace_sched_wakeup.c:599
Inline: True
Inline callers:
  - kernel/trace/trace_sched_wakeup.c:__wakeup_tracer_init
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
In kernel/trace/trace_sched_wakeup.c (ffffffff81162353)
Location: kernel/trace/trace_sched_wakeup.c:599
Inline: True
Inline callers:
  - kernel/trace/trace_sched_wakeup.c:__wakeup_tracer_init
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
In kernel/trace/trace_sched_wakeup.c (ffffffff8116ceb3)
Location: kernel/trace/trace_sched_wakeup.c:611
Inline: True
Inline callers:
  - kernel/trace/trace_sched_wakeup.c:__wakeup_tracer_init
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
In kernel/trace/trace_sched_wakeup.c (ffffffff8116ffd3)
Location: kernel/trace/trace_sched_wakeup.c:611
Inline: True
Inline callers:
  - kernel/trace/trace_sched_wakeup.c:__wakeup_tracer_init
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
In kernel/trace/trace_sched_wakeup.c (ffffffff8117d153)
Location: kernel/trace/trace_sched_wakeup.c:612
Inline: True
Inline callers:
  - kernel/trace/trace_sched_wakeup.c:__wakeup_tracer_init
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
In kernel/trace/trace_sched_wakeup.c (ffffffff8118c473)
Location: kernel/trace/trace_sched_wakeup.c:612
Inline: True
Inline callers:
  - kernel/trace/trace_sched_wakeup.c:__wakeup_tracer_init
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
In kernel/trace/trace_sched_wakeup.c (ffffffff81199bc3)
Location: kernel/trace/trace_sched_wakeup.c:600
Inline: True
Inline callers:
  - kernel/trace/trace_sched_wakeup.c:__wakeup_tracer_init
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
In kernel/trace/trace_sched_wakeup.c (ffffffff811a7805)
Location: kernel/trace/trace_sched_wakeup.c:605
Inline: True
Inline callers:
  - kernel/trace/trace_sched_wakeup.c:__wakeup_tracer_init
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
In kernel/trace/trace_sched_wakeup.c (ffffffff811b2ff5)
Location: kernel/trace/trace_sched_wakeup.c:604
Inline: True
Inline callers:
  - kernel/trace/trace_sched_wakeup.c:__wakeup_tracer_init
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
void start_wakeup_tracer(struct trace_array *tr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/trace/trace_sched_wakeup.c (0)
Location: kernel/trace/trace_sched_wakeup.c:604
Inline: False
Direct callers:
  - kernel/trace/trace_sched_wakeup.c:wakeup_dl_tracer_init
  - kernel/trace/trace_sched_wakeup.c:wakeup_rt_tracer_init
  - kernel/trace/trace_sched_wakeup.c:wakeup_tracer_init
```
**Symbols:**

```
ffffffff811cb460-ffffffff811cb509: start_wakeup_tracer (STB_LOCAL)
ffffffff811cbbce-ffffffff811cbc5c: start_wakeup_tracer.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
void start_wakeup_tracer(struct trace_array *tr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/trace/trace_sched_wakeup.c (0)
Location: kernel/trace/trace_sched_wakeup.c:604
Inline: False
Direct callers:
  - kernel/trace/trace_sched_wakeup.c:wakeup_dl_tracer_init
  - kernel/trace/trace_sched_wakeup.c:wakeup_rt_tracer_init
  - kernel/trace/trace_sched_wakeup.c:wakeup_tracer_init
```
**Symbols:**

```
ffffffff811c8b40-ffffffff811c8be9: start_wakeup_tracer (STB_LOCAL)
ffffffff81be5b35-ffffffff81be5bc3: start_wakeup_tracer.cold (STB_LOCAL)
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
In kernel/trace/trace_sched_wakeup.c (ffffffff811ca1d5)
Location: kernel/trace/trace_sched_wakeup.c:599
Inline: True
Inline callers:
  - kernel/trace/trace_sched_wakeup.c:__wakeup_tracer_init
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
In kernel/trace/trace_sched_wakeup.c (ffffffff811f5b35)
Location: kernel/trace/trace_sched_wakeup.c:599
Inline: True
Inline callers:
  - kernel/trace/trace_sched_wakeup.c:__wakeup_tracer_init
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
In kernel/trace/trace_sched_wakeup.c (ffffffff8122f0e3)
Location: kernel/trace/trace_sched_wakeup.c:600
Inline: True
Inline callers:
  - kernel/trace/trace_sched_wakeup.c:__wakeup_tracer_init
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_sched_wakeup.c (ffffffff8127b143)
Location: kernel/trace/trace_sched_wakeup.c:600
Inline: True
Inline callers:
  - kernel/trace/trace_sched_wakeup.c:__wakeup_tracer_init
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_sched_wakeup.c (ffffffff81292c63)
Location: kernel/trace/trace_sched_wakeup.c:602
Inline: True
Inline callers:
  - kernel/trace/trace_sched_wakeup.c:__wakeup_tracer_init
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_sched_wakeup.c (ffffffff812ae793)
Location: kernel/trace/trace_sched_wakeup.c:602
Inline: True
Inline callers:
  - kernel/trace/trace_sched_wakeup.c:__wakeup_tracer_init
```
</details>
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
In kernel/trace/trace_sched_wakeup.c (ffff800010230d28)
Location: kernel/trace/trace_sched_wakeup.c:604
Inline: True
Inline callers:
  - kernel/trace/trace_sched_wakeup.c:__wakeup_tracer_init
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
In kernel/trace/trace_sched_wakeup.c (c046cd30)
Location: kernel/trace/trace_sched_wakeup.c:604
Inline: True
Inline callers:
  - kernel/trace/trace_sched_wakeup.c:__wakeup_tracer_init
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
In kernel/trace/trace_sched_wakeup.c (c0000000002bb5f0)
Location: kernel/trace/trace_sched_wakeup.c:604
Inline: True
Inline callers:
  - kernel/trace/trace_sched_wakeup.c:__wakeup_tracer_init
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
In kernel/trace/trace_sched_wakeup.c (ffffffe000188ab6)
Location: kernel/trace/trace_sched_wakeup.c:604
Inline: True
Inline callers:
  - kernel/trace/trace_sched_wakeup.c:__wakeup_tracer_init
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
In kernel/trace/trace_sched_wakeup.c (ffffffff811ab615)
Location: kernel/trace/trace_sched_wakeup.c:604
Inline: True
Inline callers:
  - kernel/trace/trace_sched_wakeup.c:__wakeup_tracer_init
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
In kernel/trace/trace_sched_wakeup.c (ffffffff8119e1c5)
Location: kernel/trace/trace_sched_wakeup.c:604
Inline: True
Inline callers:
  - kernel/trace/trace_sched_wakeup.c:__wakeup_tracer_init
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
In kernel/trace/trace_sched_wakeup.c (ffffffff811a93e5)
Location: kernel/trace/trace_sched_wakeup.c:604
Inline: True
Inline callers:
  - kernel/trace/trace_sched_wakeup.c:__wakeup_tracer_init
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
In kernel/trace/trace_sched_wakeup.c (ffffffff811b7225)
Location: kernel/trace/trace_sched_wakeup.c:604
Inline: True
Inline callers:
  - kernel/trace/trace_sched_wakeup.c:__wakeup_tracer_init
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
