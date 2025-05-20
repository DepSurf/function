# Function: <code>__trace_early_add_event_dirs</code>

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
In kernel/trace/trace_events.c (ffffffff81f8473f)
Location: kernel/trace/trace_events.c:2850
Inline: True
Inline callers:
  - kernel/trace/trace_events.c:event_trace_init
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
In kernel/trace/trace_events.c (ffffffff81fadc0e)
Location: kernel/trace/trace_events.c:2755
Inline: True
Inline callers:
  - kernel/trace/trace_events.c:event_trace_init
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
In kernel/trace/trace_events.c (ffffffff81fea08b)
Location: kernel/trace/trace_events.c:2724
Inline: True
Inline callers:
  - kernel/trace/trace_events.c:event_trace_init
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
In kernel/trace/trace_events.c (ffffffff820caa82)
Location: kernel/trace/trace_events.c:2821
Inline: True
Inline callers:
  - kernel/trace/trace_events.c:event_trace_init
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
In kernel/trace/trace_events.c (ffffffff826d312e)
Location: kernel/trace/trace_events.c:2834
Inline: True
Inline callers:
  - kernel/trace/trace_events.c:event_trace_init
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
In kernel/trace/trace_events.c (ffffffff826fd9fe)
Location: kernel/trace/trace_events.c:2846
Inline: True
Inline callers:
  - kernel/trace/trace_events.c:event_trace_init
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
In kernel/trace/trace_events.c (ffffffff828b4918)
Location: kernel/trace/trace_events.c:2847
Inline: True
Inline callers:
  - kernel/trace/trace_events.c:event_trace_init
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
In kernel/trace/trace_events.c (ffffffff828cd70f)
Location: kernel/trace/trace_events.c:2837
Inline: True
Inline callers:
  - kernel/trace/trace_events.c:event_trace_init
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
In kernel/trace/trace_events.c (ffffffff828d5c66)
Location: kernel/trace/trace_events.c:2836
Inline: True
Inline callers:
  - kernel/trace/trace_events.c:event_trace_init
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
In kernel/trace/trace_events.c (ffffffff82cf650b)
Location: kernel/trace/trace_events.c:3126
Inline: True
Inline callers:
  - kernel/trace/trace_events.c:event_trace_init
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
void __trace_early_add_event_dirs(struct trace_array *tr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/trace/trace_events.c (0)
Location: kernel/trace/trace_events.c:3141
Inline: False
Direct callers:
  - kernel/trace/trace_events.c:event_trace_init
  - kernel/trace/trace_events.c:event_trace_add_tracer
```
**Symbols:**

```
ffffffff811d2a90-ffffffff811d2ad6: __trace_early_add_event_dirs (STB_LOCAL)
ffffffff81be616e-ffffffff81be6192: __trace_early_add_event_dirs.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
void __trace_early_add_event_dirs(struct trace_array *tr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/trace/trace_events.c (0)
Location: kernel/trace/trace_events.c:3352
Inline: False
Direct callers:
  - kernel/trace/trace_events.c:event_trace_init
  - kernel/trace/trace_events.c:event_trace_add_tracer
```
**Symbols:**

```
ffffffff811d4650-ffffffff811d4696: __trace_early_add_event_dirs (STB_LOCAL)
ffffffff81bd7e24-ffffffff81bd7e48: __trace_early_add_event_dirs.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
void __trace_early_add_event_dirs(struct trace_array *tr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/trace/trace_events.c (0)
Location: kernel/trace/trace_events.c:3369
Inline: False
Direct callers:
  - kernel/trace/trace_events.c:event_trace_init
  - kernel/trace/trace_events.c:event_trace_add_tracer
```
**Symbols:**

```
ffffffff812014b0-ffffffff812014f6: __trace_early_add_event_dirs (STB_LOCAL)
ffffffff81cb6461-ffffffff81cb6485: __trace_early_add_event_dirs.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
void __trace_early_add_event_dirs(struct trace_array *tr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/trace/trace_events.c (0)
Location: kernel/trace/trace_events.c:3472
Inline: False
Direct callers:
  - kernel/trace/trace_events.c:event_trace_init
  - kernel/trace/trace_events.c:event_trace_add_tracer
```
**Symbols:**

```
ffffffff8123c5d0-ffffffff8123c620: __trace_early_add_event_dirs (STB_LOCAL)
ffffffff81e673d9-ffffffff81e673fd: __trace_early_add_event_dirs.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void __trace_early_add_event_dirs(struct trace_array *tr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_events.c (ffffffff81288f50)
Location: kernel/trace/trace_events.c:3563
Inline: False
Direct callers:
  - kernel/trace/trace_events.c:event_trace_init
  - kernel/trace/trace_events.c:event_trace_add_tracer
```
**Symbols:**

```
ffffffff81288f50-ffffffff81288fce: __trace_early_add_event_dirs (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void __trace_early_add_event_dirs(struct trace_array *tr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_events.c (ffffffff812a5c70)
Location: kernel/trace/trace_events.c:3557
Inline: False
Direct callers:
  - kernel/trace/trace_events.c:event_trace_init
  - kernel/trace/trace_events.c:event_trace_add_tracer
```
**Symbols:**

```
ffffffff812a5c70-ffffffff812a5cee: __trace_early_add_event_dirs (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void __trace_early_add_event_dirs(struct trace_array *tr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_events.c (ffffffff812c1570)
Location: kernel/trace/trace_events.c:3749
Inline: False
Direct callers:
  - kernel/trace/trace_events.c:event_trace_init
  - kernel/trace/trace_events.c:event_trace_add_tracer
```
**Symbols:**

```
ffffffff812c1570-ffffffff812c15ee: __trace_early_add_event_dirs (STB_LOCAL)
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
In kernel/trace/trace_events.c (ffff80001144e55c)
Location: kernel/trace/trace_events.c:2836
Inline: True
Inline callers:
  - kernel/trace/trace_events.c:event_trace_init
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
In kernel/trace/trace_events.c (c1528bdc)
Location: kernel/trace/trace_events.c:2836
Inline: True
Inline callers:
  - kernel/trace/trace_events.c:event_trace_init
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
In kernel/trace/trace_events.c (c000000001374fd4)
Location: kernel/trace/trace_events.c:2836
Inline: True
Inline callers:
  - kernel/trace/trace_events.c:event_trace_init
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
In kernel/trace/trace_events.c (ffffffe00000ebaa)
Location: kernel/trace/trace_events.c:2836
Inline: True
Inline callers:
  - kernel/trace/trace_events.c:event_trace_init
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
In kernel/trace/trace_events.c (ffffffff828beb17)
Location: kernel/trace/trace_events.c:2836
Inline: True
Inline callers:
  - kernel/trace/trace_events.c:event_trace_init
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
In kernel/trace/trace_events.c (ffffffff828b71b7)
Location: kernel/trace/trace_events.c:2836
Inline: True
Inline callers:
  - kernel/trace/trace_events.c:event_trace_init
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
In kernel/trace/trace_events.c (ffffffff828d189a)
Location: kernel/trace/trace_events.c:2836
Inline: True
Inline callers:
  - kernel/trace/trace_events.c:event_trace_init
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
In kernel/trace/trace_events.c (ffffffff828d6cbb)
Location: kernel/trace/trace_events.c:2836
Inline: True
Inline callers:
  - kernel/trace/trace_events.c:event_trace_init
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
