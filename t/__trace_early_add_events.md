# Function: <code>__trace_early_add_events</code>

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
In kernel/trace/trace_events.c (ffffffff81f848b3)
Location: kernel/trace/trace_events.c:2871
Inline: True
Inline callers:
  - kernel/trace/trace_events.c:trace_event_init
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
In kernel/trace/trace_events.c (ffffffff81fade28)
Location: kernel/trace/trace_events.c:2776
Inline: True
Inline callers:
  - kernel/trace/trace_events.c:trace_event_init
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
In kernel/trace/trace_events.c (ffffffff81fea2a5)
Location: kernel/trace/trace_events.c:2745
Inline: True
Inline callers:
  - kernel/trace/trace_events.c:trace_event_init
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
In kernel/trace/trace_events.c (ffffffff820cacd6)
Location: kernel/trace/trace_events.c:2842
Inline: True
Inline callers:
  - kernel/trace/trace_events.c:trace_event_init
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
In kernel/trace/trace_events.c (ffffffff826d3345)
Location: kernel/trace/trace_events.c:2855
Inline: True
Inline callers:
  - kernel/trace/trace_events.c:trace_event_init
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
In kernel/trace/trace_events.c (ffffffff826fdb3b)
Location: kernel/trace/trace_events.c:2867
Inline: True
Inline callers:
  - kernel/trace/trace_events.c:trace_event_init
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
In kernel/trace/trace_events.c (ffffffff828b4a55)
Location: kernel/trace/trace_events.c:2868
Inline: True
Inline callers:
  - kernel/trace/trace_events.c:trace_event_init
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
In kernel/trace/trace_events.c (ffffffff828cd84f)
Location: kernel/trace/trace_events.c:2858
Inline: True
Inline callers:
  - kernel/trace/trace_events.c:trace_event_init
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
In kernel/trace/trace_events.c (ffffffff828d5dc5)
Location: kernel/trace/trace_events.c:2857
Inline: True
Inline callers:
  - kernel/trace/trace_events.c:trace_event_init
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
In kernel/trace/trace_events.c (ffffffff82cf635b)
Location: kernel/trace/trace_events.c:3147
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
void __trace_early_add_events(struct trace_array *tr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/trace/trace_events.c (0)
Location: kernel/trace/trace_events.c:3161
Inline: False
Direct callers:
  - kernel/trace/trace.c:trace_array_create
```
**Symbols:**

```
ffffffff81be61d4-ffffffff81be61f4: __trace_early_add_events.cold (STB_LOCAL)
ffffffff811d4260-ffffffff811d4343: __trace_early_add_events (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
void __trace_early_add_events(struct trace_array *tr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/trace/trace_events.c (0)
Location: kernel/trace/trace_events.c:3372
Inline: False
Direct callers:
  - kernel/trace/trace.c:trace_array_create
  - kernel/trace/trace_events.c:trace_event_init
```
**Symbols:**

```
ffffffff81bd7e8e-ffffffff81bd7eae: __trace_early_add_events.cold (STB_LOCAL)
ffffffff811d5950-ffffffff811d59fc: __trace_early_add_events (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
void __trace_early_add_events(struct trace_array *tr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/trace/trace_events.c (0)
Location: kernel/trace/trace_events.c:3389
Inline: False
Direct callers:
  - kernel/trace/trace.c:trace_array_create
  - kernel/trace/trace_events.c:trace_event_init
```
**Symbols:**

```
ffffffff81cb658b-ffffffff81cb65ab: __trace_early_add_events.cold (STB_LOCAL)
ffffffff812027d0-ffffffff81202830: __trace_early_add_events (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
void __trace_early_add_events(struct trace_array *tr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/trace/trace_events.c (0)
Location: kernel/trace/trace_events.c:3492
Inline: False
Direct callers:
  - kernel/trace/trace.c:trace_array_create
  - kernel/trace/trace_events.c:trace_event_init
```
**Symbols:**

```
ffffffff81e6755e-ffffffff81e6757e: __trace_early_add_events.cold (STB_LOCAL)
ffffffff8123dc40-ffffffff8123dcaa: __trace_early_add_events (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void __trace_early_add_events(struct trace_array *tr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_events.c (ffffffff8128b390)
Location: kernel/trace/trace_events.c:3583
Inline: False
Direct callers:
  - kernel/trace/trace.c:trace_array_create
  - kernel/trace/trace_events.c:trace_event_init
```
**Symbols:**

```
ffffffff8128b390-ffffffff8128b5bc: __trace_early_add_events (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void __trace_early_add_events(struct trace_array *tr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_events.c (ffffffff812a82e0)
Location: kernel/trace/trace_events.c:3577
Inline: False
Direct callers:
  - kernel/trace/trace.c:trace_array_create
  - kernel/trace/trace_events.c:trace_event_init
```
**Symbols:**

```
ffffffff812a82e0-ffffffff812a84bf: __trace_early_add_events (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void __trace_early_add_events(struct trace_array *tr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_events.c (ffffffff812c3fb0)
Location: kernel/trace/trace_events.c:3769
Inline: False
Direct callers:
  - kernel/trace/trace.c:trace_array_create_systems
  - kernel/trace/trace_events.c:trace_event_init
```
**Symbols:**

```
ffffffff812c3fb0-ffffffff812c41c8: __trace_early_add_events (STB_GLOBAL)
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
In kernel/trace/trace_events.c (ffff80001144e6b4)
Location: kernel/trace/trace_events.c:2857
Inline: True
Inline callers:
  - kernel/trace/trace_events.c:trace_event_init
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
In kernel/trace/trace_events.c (c1528d44)
Location: kernel/trace/trace_events.c:2857
Inline: True
Inline callers:
  - kernel/trace/trace_events.c:trace_event_init
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
In kernel/trace/trace_events.c (c000000001375190)
Location: kernel/trace/trace_events.c:2857
Inline: True
Inline callers:
  - kernel/trace/trace_events.c:trace_event_init
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
In kernel/trace/trace_events.c (ffffffe00000ed10)
Location: kernel/trace/trace_events.c:2857
Inline: True
Inline callers:
  - kernel/trace/trace_events.c:trace_event_init
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
In kernel/trace/trace_events.c (ffffffff828bec76)
Location: kernel/trace/trace_events.c:2857
Inline: True
Inline callers:
  - kernel/trace/trace_events.c:trace_event_init
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
In kernel/trace/trace_events.c (ffffffff828b7316)
Location: kernel/trace/trace_events.c:2857
Inline: True
Inline callers:
  - kernel/trace/trace_events.c:trace_event_init
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
In kernel/trace/trace_events.c (ffffffff828d19f9)
Location: kernel/trace/trace_events.c:2857
Inline: True
Inline callers:
  - kernel/trace/trace_events.c:trace_event_init
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
In kernel/trace/trace_events.c (ffffffff828d6e1a)
Location: kernel/trace/trace_events.c:2857
Inline: True
Inline callers:
  - kernel/trace/trace_events.c:trace_event_init
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
