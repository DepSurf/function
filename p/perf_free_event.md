# Function: <code>perf_free_event</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void perf_free_event(struct perf_event *event, struct perf_event_context *ctx);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff81180ce0)
Location: kernel/events/core.c:8900
Inline: False
Direct callers:
  - kernel/events/core.c:perf_event_free_task
  - kernel/events/core.c:perf_event_free_task
```
**Symbols:**

```
ffffffff81180ce0-ffffffff81180daf: perf_free_event (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void perf_free_event(struct perf_event *event, struct perf_event_context *ctx);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff81192e30)
Location: kernel/events/core.c:10085
Inline: False
Direct callers:
  - kernel/events/core.c:perf_event_free_task
  - kernel/events/core.c:perf_event_free_task
```
**Symbols:**

```
ffffffff81192e30-ffffffff81192eff: perf_free_event (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void perf_free_event(struct perf_event *event, struct perf_event_context *ctx);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff811a2610)
Location: kernel/events/core.c:10345
Inline: False
Direct callers:
  - kernel/events/core.c:perf_event_free_task
  - kernel/events/core.c:perf_event_free_task
```
**Symbols:**

```
ffffffff811a2610-ffffffff811a26df: perf_free_event (STB_LOCAL)
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
In kernel/events/core.c (ffffffff811adbc6)
Location: kernel/events/core.c:10592
Inline: True
Inline callers:
  - kernel/events/core.c:perf_event_free_task
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
In kernel/events/core.c (ffffffff811c1736)
Location: kernel/events/core.c:10624
Inline: True
Inline callers:
  - kernel/events/core.c:perf_event_free_task
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
In kernel/events/core.c (ffffffff811e1a9b)
Location: kernel/events/core.c:11154
Inline: True
Inline callers:
  - kernel/events/core.c:perf_event_free_task
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
In kernel/events/core.c (ffffffff811f1f0b)
Location: kernel/events/core.c:11197
Inline: True
Inline callers:
  - kernel/events/core.c:perf_event_free_task
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
In kernel/events/core.c (ffffffff81209b12)
Location: kernel/events/core.c:11548
Inline: True
Inline callers:
  - kernel/events/core.c:perf_event_free_task
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
In kernel/events/core.c (ffffffff81216e82)
Location: kernel/events/core.c:11661
Inline: True
Inline callers:
  - kernel/events/core.c:perf_event_free_task
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff81242aa8)
Location: kernel/events/core.c:12264
Inline: True
Inline callers:
  - kernel/events/core.c:perf_event_free_task
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff8124d1f9)
Location: kernel/events/core.c:12548
Inline: True
Inline callers:
  - kernel/events/core.c:perf_event_free_task
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
In kernel/events/core.c (ffffffff81251ab9)
Location: kernel/events/core.c:12734
Inline: True
Inline callers:
  - kernel/events/core.c:perf_event_free_task
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
In kernel/events/core.c (ffffffff8128d2db)
Location: kernel/events/core.c:12855
Inline: True
Inline callers:
  - kernel/events/core.c:perf_event_free_task
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
In kernel/events/core.c (ffffffff812e1fdc)
Location: kernel/events/core.c:12825
Inline: True
Inline callers:
  - kernel/events/core.c:perf_event_free_task
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
In kernel/events/core.c (ffffffff8134a50d)
Location: kernel/events/core.c:13068
Inline: True
Inline callers:
  - kernel/events/core.c:perf_event_free_task
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
In kernel/events/core.c (ffffffff8137b54d)
Location: kernel/events/core.c:13110
Inline: True
Inline callers:
  - kernel/events/core.c:perf_event_free_task
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
In kernel/events/core.c (ffffffff813a474d)
Location: kernel/events/core.c:13206
Inline: True
Inline callers:
  - kernel/events/core.c:perf_event_free_task
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
In kernel/events/core.c (ffff8000102a1094)
Location: kernel/events/core.c:11661
Inline: True
Inline callers:
  - kernel/events/core.c:perf_event_free_task
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
In kernel/events/core.c (c04d1210)
Location: kernel/events/core.c:11661
Inline: True
Inline callers:
  - kernel/events/core.c:perf_event_free_task
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
In kernel/events/core.c (c000000000353294)
Location: kernel/events/core.c:11661
Inline: True
Inline callers:
  - kernel/events/core.c:perf_event_free_task
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
In kernel/events/core.c (ffffffe0001d042a)
Location: kernel/events/core.c:11661
Inline: True
Inline callers:
  - kernel/events/core.c:perf_event_free_task
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
In kernel/events/core.c (ffffffff8120f4d2)
Location: kernel/events/core.c:11661
Inline: True
Inline callers:
  - kernel/events/core.c:perf_event_free_task
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
In kernel/events/core.c (ffffffff8120226c)
Location: kernel/events/core.c:11661
Inline: True
Inline callers:
  - kernel/events/core.c:perf_event_free_task
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
In kernel/events/core.c (ffffffff8120d272)
Location: kernel/events/core.c:11661
Inline: True
Inline callers:
  - kernel/events/core.c:perf_event_free_task
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
In kernel/events/core.c (ffffffff8121c11e)
Location: kernel/events/core.c:11661
Inline: True
Inline callers:
  - kernel/events/core.c:perf_event_free_task
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
</ul>
