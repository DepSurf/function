# Function: <code>perf_event_init_context</code>

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
In kernel/events/core.c (ffffffff81184d37)
Location: kernel/events/core.c:9146
Inline: True
Inline callers:
  - kernel/events/core.c:perf_event_init_task
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
In kernel/events/core.c (ffffffff81196b47)
Location: kernel/events/core.c:10336
Inline: True
Inline callers:
  - kernel/events/core.c:perf_event_init_task
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
In kernel/events/core.c (ffffffff811a6617)
Location: kernel/events/core.c:10607
Inline: True
Inline callers:
  - kernel/events/core.c:perf_event_init_task
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
In kernel/events/core.c (ffffffff811add68)
Location: kernel/events/core.c:10874
Inline: True
Inline callers:
  - kernel/events/core.c:perf_event_init_task
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
In kernel/events/core.c (ffffffff811c1925)
Location: kernel/events/core.c:10906
Inline: True
Inline callers:
  - kernel/events/core.c:perf_event_init_task
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
In kernel/events/core.c (ffffffff811e1ca0)
Location: kernel/events/core.c:11458
Inline: True
Inline callers:
  - kernel/events/core.c:perf_event_init_task
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
In kernel/events/core.c (ffffffff811f2110)
Location: kernel/events/core.c:11501
Inline: True
Inline callers:
  - kernel/events/core.c:perf_event_init_task
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
In kernel/events/core.c (ffffffff81209d61)
Location: kernel/events/core.c:11866
Inline: True
Inline callers:
  - kernel/events/core.c:perf_event_init_task
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
In kernel/events/core.c (ffffffff812170d1)
Location: kernel/events/core.c:11983
Inline: True
Inline callers:
  - kernel/events/core.c:perf_event_init_task
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int perf_event_init_context(struct task_struct *child, int ctxn);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff8123df90)
Location: kernel/events/core.c:12586
Inline: False
Direct callers:
  - kernel/events/core.c:perf_event_init_task
  - kernel/events/core.c:perf_event_init_task
```
**Symbols:**

```
ffffffff8123df90-ffffffff8123e213: perf_event_init_context (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int perf_event_init_context(struct task_struct *child, int ctxn);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff81248350)
Location: kernel/events/core.c:12869
Inline: False
Direct callers:
  - kernel/events/core.c:perf_event_init_task
  - kernel/events/core.c:perf_event_init_task
```
**Symbols:**

```
ffffffff81248350-ffffffff812485d3: perf_event_init_context (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int perf_event_init_context(struct task_struct *child, int ctxn, u64 clone_flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff8124c240)
Location: kernel/events/core.c:13059
Inline: False
Direct callers:
  - kernel/events/core.c:perf_event_init_task
  - kernel/events/core.c:perf_event_init_task
```
**Symbols:**

```
ffffffff8124c240-ffffffff8124c4c7: perf_event_init_context (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int perf_event_init_context(struct task_struct *child, int ctxn, u64 clone_flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff81287b30)
Location: kernel/events/core.c:13180
Inline: False
Direct callers:
  - kernel/events/core.c:perf_event_init_task
  - kernel/events/core.c:perf_event_init_task
```
**Symbols:**

```
ffffffff81287b30-ffffffff81287df5: perf_event_init_context (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int perf_event_init_context(struct task_struct *child, int ctxn, u64 clone_flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff812dc330)
Location: kernel/events/core.c:13150
Inline: False
Direct callers:
  - kernel/events/core.c:perf_event_init_task
  - kernel/events/core.c:perf_event_init_task
```
**Symbols:**

```
ffffffff812dc330-ffffffff812dc612: perf_event_init_context (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int perf_event_init_context(struct task_struct *child, u64 clone_flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff81344650)
Location: kernel/events/core.c:13382
Inline: False
Direct callers:
  - kernel/events/core.c:perf_event_init_task
```
**Symbols:**

```
ffffffff81344650-ffffffff813448aa: perf_event_init_context (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int perf_event_init_context(struct task_struct *child, u64 clone_flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff813756f0)
Location: kernel/events/core.c:13424
Inline: False
Direct callers:
  - kernel/events/core.c:perf_event_init_task
```
**Symbols:**

```
ffffffff813756f0-ffffffff8137594a: perf_event_init_context (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int perf_event_init_context(struct task_struct *child, u64 clone_flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff8139ea20)
Location: kernel/events/core.c:13522
Inline: False
Direct callers:
  - kernel/events/core.c:perf_event_init_task
```
**Symbols:**

```
ffffffff8139ea20-ffffffff8139ec7a: perf_event_init_context (STB_LOCAL)
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
In kernel/events/core.c (ffff8000102a134c)
Location: kernel/events/core.c:11983
Inline: True
Inline callers:
  - kernel/events/core.c:perf_event_init_task
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
In kernel/events/core.c (c04d14e8)
Location: kernel/events/core.c:11983
Inline: True
Inline callers:
  - kernel/events/core.c:perf_event_init_task
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
In kernel/events/core.c (c000000000353634)
Location: kernel/events/core.c:11983
Inline: True
Inline callers:
  - kernel/events/core.c:perf_event_init_task
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
In kernel/events/core.c (ffffffe0001d069e)
Location: kernel/events/core.c:11983
Inline: True
Inline callers:
  - kernel/events/core.c:perf_event_init_task
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
In kernel/events/core.c (ffffffff8120f721)
Location: kernel/events/core.c:11983
Inline: True
Inline callers:
  - kernel/events/core.c:perf_event_init_task
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
In kernel/events/core.c (ffffffff812024b1)
Location: kernel/events/core.c:11983
Inline: True
Inline callers:
  - kernel/events/core.c:perf_event_init_task
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
In kernel/events/core.c (ffffffff8120d4c1)
Location: kernel/events/core.c:11983
Inline: True
Inline callers:
  - kernel/events/core.c:perf_event_init_task
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
In kernel/events/core.c (ffffffff8121c361)
Location: kernel/events/core.c:11983
Inline: True
Inline callers:
  - kernel/events/core.c:perf_event_init_task
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
<li>
<details>
<summary>Changed between <code>5.11</code> and <code>5.13</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>u64 clone_flags</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>5.13</code> and <code>5.15</code> ✅
</li>
<li>
No changes between <code>5.15</code> and <code>5.19</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>5.19</code> and <code>6.2</code> ⚠️</summary>
<ul>
<li>
<b>Param removed. </b>
<code>int ctxn</code>
</li>
<li>
<b>Param reordered. </b>
<code>child, ctxn, clone_flags</code> ➡️ <code>child, clone_flags</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>6.2</code> and <code>6.5</code> ✅
</li>
<li>
No changes between <code>6.5</code> and <code>6.8</code> ✅
</li>
</ul>
