# Function: <code>tracing_alloc_snapshot_instance</code>

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
<summary>In <code>4.18</code>: Selective Inline, Transformation ⚠️</summary>

```c
int tracing_alloc_snapshot_instance(struct trace_array *tr);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/trace/trace.c (ffffffff8117ed3c)
Location: kernel/trace/trace.c:952
Inline: True
Inline callers:
  - kernel/trace/trace.c:ftrace_trace_snapshot_callback
  - kernel/trace/trace.c:tracing_snapshot_write
  - kernel/trace/trace.c:tracing_set_tracer
Direct callers:
  - kernel/trace/trace.c:ftrace_trace_snapshot_callback
  - kernel/trace/trace.c:tracing_snapshot_write
  - kernel/trace/trace.c:tracing_set_tracer
  - kernel/trace/trace_events_trigger.c:register_snapshot_trigger
```
**Symbols:**

```
ffffffff8117eca0-ffffffff8117eccb: tracing_alloc_snapshot_instance.part.54 (STB_LOCAL)
ffffffff81180e00-ffffffff81180e14: tracing_alloc_snapshot_instance (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline, Transformation ⚠️</summary>

```c
int tracing_alloc_snapshot_instance(struct trace_array *tr);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/trace/trace.c (ffffffff8118c63c)
Location: kernel/trace/trace.c:953
Inline: True
Inline callers:
  - kernel/trace/trace.c:ftrace_trace_snapshot_callback
  - kernel/trace/trace.c:tracing_snapshot_write
  - kernel/trace/trace.c:tracing_set_tracer
Direct callers:
  - kernel/trace/trace.c:ftrace_trace_snapshot_callback
  - kernel/trace/trace.c:tracing_snapshot_write
  - kernel/trace/trace.c:tracing_set_tracer
  - kernel/trace/trace_events_trigger.c:register_snapshot_trigger
```
**Symbols:**

```
ffffffff8118c5a0-ffffffff8118c5cb: tracing_alloc_snapshot_instance.part.55 (STB_LOCAL)
ffffffff8118e7c0-ffffffff8118e7d4: tracing_alloc_snapshot_instance (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline, Transformation ⚠️</summary>

```c
int tracing_alloc_snapshot_instance(struct trace_array *tr);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/trace/trace.c (ffffffff81199e69)
Location: kernel/trace/trace.c:1010
Inline: True
Inline callers:
  - kernel/trace/trace.c:ftrace_trace_snapshot_callback
  - kernel/trace/trace.c:tracing_snapshot_write
  - kernel/trace/trace.c:tracing_set_tracer
  - kernel/trace/trace.c:tracing_snapshot_cond_enable
Direct callers:
  - kernel/trace/trace.c:ftrace_trace_snapshot_callback
  - kernel/trace/trace.c:tracing_snapshot_write
  - kernel/trace/trace.c:tracing_set_tracer
  - kernel/trace/trace.c:tracing_snapshot_cond_enable
  - kernel/trace/trace_events_trigger.c:register_snapshot_trigger
```
**Symbols:**

```
ffffffff81199ca0-ffffffff81199ccb: tracing_alloc_snapshot_instance.part.0 (STB_LOCAL)
ffffffff8119c1c0-ffffffff8119c1d4: tracing_alloc_snapshot_instance (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline, Transformation ⚠️</summary>

```c
int tracing_alloc_snapshot_instance(struct trace_array *tr);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/trace/trace.c (ffffffff811a5819)
Location: kernel/trace/trace.c:1028
Inline: True
Inline callers:
  - kernel/trace/trace.c:ftrace_trace_snapshot_callback
  - kernel/trace/trace.c:tracing_snapshot_write
  - kernel/trace/trace.c:tracing_set_tracer
  - kernel/trace/trace.c:tracing_snapshot_cond_enable
Direct callers:
  - kernel/trace/trace.c:ftrace_trace_snapshot_callback
  - kernel/trace/trace.c:tracing_snapshot_write
  - kernel/trace/trace.c:tracing_set_tracer
  - kernel/trace/trace.c:tracing_snapshot_cond_enable
  - kernel/trace/trace_events_trigger.c:register_snapshot_trigger
```
**Symbols:**

```
ffffffff811a5650-ffffffff811a567b: tracing_alloc_snapshot_instance.part.0 (STB_LOCAL)
ffffffff811a7bb0-ffffffff811a7bc4: tracing_alloc_snapshot_instance (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
int tracing_alloc_snapshot_instance(struct trace_array *tr);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/trace/trace.c (ffffffff811bc769)
Location: kernel/trace/trace.c:1060
Inline: True
Inline callers:
  - kernel/trace/trace.c:ftrace_trace_snapshot_callback
  - kernel/trace/trace.c:ftrace_trace_snapshot_callback
  - kernel/trace/trace.c:tracing_snapshot_write
  - kernel/trace/trace.c:tracing_snapshot_write
  - kernel/trace/trace.c:tracing_set_tracer
  - kernel/trace/trace.c:tracing_set_tracer
  - kernel/trace/trace.c:tracing_snapshot_cond_enable
  - kernel/trace/trace.c:tracing_snapshot_cond_enable
Direct callers:
  - kernel/trace/trace_events_trigger.c:register_snapshot_trigger
```
**Symbols:**

```
ffffffff811bff70-ffffffff811bffa3: tracing_alloc_snapshot_instance (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
int tracing_alloc_snapshot_instance(struct trace_array *tr);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/trace/trace.c (ffffffff811ba379)
Location: kernel/trace/trace.c:1211
Inline: True
Inline callers:
  - kernel/trace/trace.c:ftrace_trace_snapshot_callback
  - kernel/trace/trace.c:ftrace_trace_snapshot_callback
  - kernel/trace/trace.c:tracing_snapshot_write
  - kernel/trace/trace.c:tracing_snapshot_write
  - kernel/trace/trace.c:tracing_set_tracer
  - kernel/trace/trace.c:tracing_set_tracer
  - kernel/trace/trace.c:tracing_snapshot_cond_enable
  - kernel/trace/trace.c:tracing_snapshot_cond_enable
Direct callers:
  - kernel/trace/trace_events_trigger.c:register_snapshot_trigger
  - kernel/trace/trace_boot.c:trace_boot_enable_tracer
```
**Symbols:**

```
ffffffff811bdba0-ffffffff811bdbd3: tracing_alloc_snapshot_instance (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
int tracing_alloc_snapshot_instance(struct trace_array *tr);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/trace/trace.c (ffffffff811ba7e9)
Location: kernel/trace/trace.c:1208
Inline: True
Inline callers:
  - kernel/trace/trace.c:ftrace_trace_snapshot_callback
  - kernel/trace/trace.c:ftrace_trace_snapshot_callback
  - kernel/trace/trace.c:tracing_snapshot_write
  - kernel/trace/trace.c:tracing_snapshot_write
  - kernel/trace/trace.c:tracing_set_tracer
  - kernel/trace/trace.c:tracing_set_tracer
  - kernel/trace/trace.c:tracing_snapshot_cond_enable
  - kernel/trace/trace.c:tracing_snapshot_cond_enable
Direct callers:
  - kernel/trace/trace_events_trigger.c:register_snapshot_trigger
  - kernel/trace/trace_boot.c:trace_boot_init_one_instance
```
**Symbols:**

```
ffffffff811bd6b0-ffffffff811bd6e3: tracing_alloc_snapshot_instance (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline, Transformation ⚠️</summary>

```c
int tracing_alloc_snapshot_instance(struct trace_array *tr);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/trace/trace.c (ffffffff811e52a5)
Location: kernel/trace/trace.c:1221
Inline: True
Inline callers:
  - kernel/trace/trace.c:ftrace_trace_snapshot_callback
  - kernel/trace/trace.c:ftrace_trace_snapshot_callback
  - kernel/trace/trace.c:tracing_snapshot_write
  - kernel/trace/trace.c:tracing_snapshot_write
  - kernel/trace/trace.c:tracing_set_tracer
  - kernel/trace/trace.c:tracing_set_tracer
  - kernel/trace/trace.c:tracing_snapshot_cond_enable
  - kernel/trace/trace.c:tracing_snapshot_cond_enable
Direct callers:
  - kernel/trace/trace_events_trigger.c:register_snapshot_trigger
  - kernel/trace/trace_boot.c:trace_boot_init_one_instance
```
**Symbols:**

```
ffffffff81cb5242-ffffffff81cb5257: tracing_alloc_snapshot_instance.cold (STB_LOCAL)
ffffffff811e81a0-ffffffff811e81e7: tracing_alloc_snapshot_instance (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline, Transformation ⚠️</summary>

```c
int tracing_alloc_snapshot_instance(struct trace_array *tr);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/trace/trace.c (ffffffff8121cebd)
Location: kernel/trace/trace.c:1211
Inline: True
Inline callers:
  - kernel/trace/trace.c:ftrace_trace_snapshot_callback
  - kernel/trace/trace.c:tracing_snapshot_write
  - kernel/trace/trace.c:tracing_set_tracer
  - kernel/trace/trace.c:tracing_snapshot_cond_enable
Direct callers:
  - kernel/trace/trace_events_trigger.c:register_snapshot_trigger
  - kernel/trace/trace_boot.c:trace_boot_init_one_instance
```
**Symbols:**

```
ffffffff81e662d8-ffffffff81e662ed: tracing_alloc_snapshot_instance.cold (STB_LOCAL)
ffffffff8121fcd0-ffffffff8121fd1c: tracing_alloc_snapshot_instance (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline, Transformation ⚠️</summary>

```c
int tracing_alloc_snapshot_instance(struct trace_array *tr);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/trace/trace.c (ffffffff812678ad)
Location: kernel/trace/trace.c:1212
Inline: True
Inline callers:
  - kernel/trace/trace.c:ftrace_trace_snapshot_callback
  - kernel/trace/trace.c:tracing_snapshot_write
  - kernel/trace/trace.c:tracing_set_tracer
  - kernel/trace/trace.c:tracing_snapshot_cond_enable
Direct callers:
  - kernel/trace/trace_events_trigger.c:register_snapshot_trigger
  - kernel/trace/trace_boot.c:trace_boot_init_one_instance
```
**Symbols:**

```
ffffffff8205d575-ffffffff8205d58a: tracing_alloc_snapshot_instance.cold (STB_LOCAL)
ffffffff8126a940-ffffffff8126a98c: tracing_alloc_snapshot_instance (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline, Transformation ⚠️</summary>

```c
int tracing_alloc_snapshot_instance(struct trace_array *tr);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/trace/trace.c (ffffffff8127e6bd)
Location: kernel/trace/trace.c:1263
Inline: True
Inline callers:
  - kernel/trace/trace.c:ftrace_trace_snapshot_callback
  - kernel/trace/trace.c:tracing_snapshot_write
  - kernel/trace/trace.c:tracing_set_tracer
  - kernel/trace/trace.c:tracing_snapshot_cond_enable
Direct callers:
  - kernel/trace/trace_events_trigger.c:register_snapshot_trigger
  - kernel/trace/trace_boot.c:trace_boot_init_one_instance
```
**Symbols:**

```
ffffffff820dbf2e-ffffffff820dbf43: tracing_alloc_snapshot_instance.cold (STB_LOCAL)
ffffffff81281ac0-ffffffff81281b0c: tracing_alloc_snapshot_instance (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline, Transformation ⚠️</summary>

```c
int tracing_alloc_snapshot_instance(struct trace_array *tr);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/trace/trace.c (ffffffff812992b0)
Location: kernel/trace/trace.c:1265
Inline: True
Direct callers:
  - kernel/trace/trace.c:ftrace_trace_snapshot_callback
  - kernel/trace/trace.c:tracing_snapshot_write
  - kernel/trace/trace.c:tracing_set_tracer
  - kernel/trace/trace.c:tracing_snapshot_cond_enable
  - kernel/trace/trace_events_trigger.c:register_snapshot_trigger
  - kernel/trace/trace_boot.c:trace_boot_init_one_instance
```
**Symbols:**

```
ffffffff821b7da7-ffffffff821b7dbc: tracing_alloc_snapshot_instance.cold (STB_LOCAL)
ffffffff8129c970-ffffffff8129c9d4: tracing_alloc_snapshot_instance (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Selective Inline, Transformation ⚠️</summary>

```c
int tracing_alloc_snapshot_instance(struct trace_array *tr);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/trace/trace.c (ffff80001022088c)
Location: kernel/trace/trace.c:1028
Inline: True
Inline callers:
  - kernel/trace/trace.c:ftrace_trace_snapshot_callback
  - kernel/trace/trace.c:tracing_snapshot_write
  - kernel/trace/trace.c:tracing_set_tracer
  - kernel/trace/trace.c:tracing_snapshot_cond_enable
Direct callers:
  - kernel/trace/trace.c:ftrace_trace_snapshot_callback
  - kernel/trace/trace.c:tracing_snapshot_write
  - kernel/trace/trace.c:tracing_set_tracer
  - kernel/trace/trace.c:tracing_snapshot_cond_enable
  - kernel/trace/trace_events_trigger.c:register_snapshot_trigger
```
**Symbols:**

```
ffff8000102207e8-ffff800010220828: tracing_alloc_snapshot_instance.part.0 (STB_LOCAL)
ffff8000102241d0-ffff8000102241f4: tracing_alloc_snapshot_instance (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline, Transformation ⚠️</summary>

```c
int tracing_alloc_snapshot_instance(struct trace_array *tr);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/trace/trace.c (c045e61c)
Location: kernel/trace/trace.c:1028
Inline: True
Inline callers:
  - kernel/trace/trace.c:ftrace_trace_snapshot_callback
  - kernel/trace/trace.c:tracing_snapshot_write
  - kernel/trace/trace.c:tracing_set_tracer
  - kernel/trace/trace.c:tracing_snapshot_cond_enable
Direct callers:
  - kernel/trace/trace.c:ftrace_trace_snapshot_callback
  - kernel/trace/trace.c:tracing_snapshot_write
  - kernel/trace/trace.c:tracing_set_tracer
  - kernel/trace/trace.c:tracing_snapshot_cond_enable
  - kernel/trace/trace_events_trigger.c:register_snapshot_trigger
```
**Symbols:**

```
c045e56c-c045e5a0: tracing_alloc_snapshot_instance.part.0 (STB_LOCAL)
c046194c-c0461974: tracing_alloc_snapshot_instance (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline, Transformation ⚠️</summary>

```c
int tracing_alloc_snapshot_instance(struct trace_array *tr);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/trace/trace.c (c0000000002a4a54)
Location: kernel/trace/trace.c:1028
Inline: True
Inline callers:
  - kernel/trace/trace.c:ftrace_trace_snapshot_callback
  - kernel/trace/trace.c:tracing_snapshot_write
  - kernel/trace/trace.c:tracing_set_tracer
  - kernel/trace/trace.c:tracing_snapshot_cond_enable
  - kernel/trace/trace.c:tracing_alloc_snapshot
Direct callers:
  - kernel/trace/trace.c:ftrace_trace_snapshot_callback
  - kernel/trace/trace.c:tracing_snapshot_write
  - kernel/trace/trace.c:tracing_set_tracer
  - kernel/trace/trace.c:tracing_snapshot_cond_enable
  - kernel/trace/trace.c:tracing_alloc_snapshot
  - kernel/trace/trace_events_trigger.c:register_snapshot_trigger
```
**Symbols:**

```
c0000000002a4910-c0000000002a4968: tracing_alloc_snapshot_instance.part.0 (STB_LOCAL)
c0000000002a90e0-c0000000002a9104: tracing_alloc_snapshot_instance (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline, Transformation ⚠️</summary>

```c
int tracing_alloc_snapshot_instance(struct trace_array *tr);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/trace/trace.c (ffffffe00017d266)
Location: kernel/trace/trace.c:1028
Inline: True
Inline callers:
  - kernel/trace/trace.c:ftrace_trace_snapshot_callback
  - kernel/trace/trace.c:tracing_snapshot_write
  - kernel/trace/trace.c:tracing_set_tracer
  - kernel/trace/trace.c:tracing_snapshot_cond_enable
Direct callers:
  - kernel/trace/trace.c:ftrace_trace_snapshot_callback
  - kernel/trace/trace.c:tracing_snapshot_write
  - kernel/trace/trace.c:tracing_set_tracer
  - kernel/trace/trace.c:tracing_snapshot_cond_enable
  - kernel/trace/trace_events_trigger.c:register_snapshot_trigger
```
**Symbols:**

```
ffffffe00017d0ee-ffffffe00017d126: tracing_alloc_snapshot_instance.part.0 (STB_LOCAL)
ffffffe00017f708-ffffffe00017f72a: tracing_alloc_snapshot_instance (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Selective Inline, Transformation ⚠️</summary>

```c
int tracing_alloc_snapshot_instance(struct trace_array *tr);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/trace/trace.c (ffffffff8119de39)
Location: kernel/trace/trace.c:1028
Inline: True
Inline callers:
  - kernel/trace/trace.c:ftrace_trace_snapshot_callback
  - kernel/trace/trace.c:tracing_snapshot_write
  - kernel/trace/trace.c:tracing_set_tracer
  - kernel/trace/trace.c:tracing_snapshot_cond_enable
Direct callers:
  - kernel/trace/trace.c:ftrace_trace_snapshot_callback
  - kernel/trace/trace.c:tracing_snapshot_write
  - kernel/trace/trace.c:tracing_set_tracer
  - kernel/trace/trace.c:tracing_snapshot_cond_enable
  - kernel/trace/trace_events_trigger.c:register_snapshot_trigger
```
**Symbols:**

```
ffffffff8119dc70-ffffffff8119dc9b: tracing_alloc_snapshot_instance.part.0 (STB_LOCAL)
ffffffff811a01d0-ffffffff811a01e4: tracing_alloc_snapshot_instance (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline, Transformation ⚠️</summary>

```c
int tracing_alloc_snapshot_instance(struct trace_array *tr);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/trace/trace.c (ffffffff81190e99)
Location: kernel/trace/trace.c:1028
Inline: True
Inline callers:
  - kernel/trace/trace.c:ftrace_trace_snapshot_callback
  - kernel/trace/trace.c:tracing_snapshot_write
  - kernel/trace/trace.c:tracing_set_tracer
  - kernel/trace/trace.c:tracing_snapshot_cond_enable
Direct callers:
  - kernel/trace/trace.c:ftrace_trace_snapshot_callback
  - kernel/trace/trace.c:tracing_snapshot_write
  - kernel/trace/trace.c:tracing_set_tracer
  - kernel/trace/trace.c:tracing_snapshot_cond_enable
  - kernel/trace/trace_events_trigger.c:register_snapshot_trigger
```
**Symbols:**

```
ffffffff81190cd0-ffffffff81190cfb: tracing_alloc_snapshot_instance.part.0 (STB_LOCAL)
ffffffff811931e0-ffffffff811931f4: tracing_alloc_snapshot_instance (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline, Transformation ⚠️</summary>

```c
int tracing_alloc_snapshot_instance(struct trace_array *tr);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/trace/trace.c (ffffffff8119bc09)
Location: kernel/trace/trace.c:1028
Inline: True
Inline callers:
  - kernel/trace/trace.c:ftrace_trace_snapshot_callback
  - kernel/trace/trace.c:tracing_snapshot_write
  - kernel/trace/trace.c:tracing_set_tracer
  - kernel/trace/trace.c:tracing_snapshot_cond_enable
Direct callers:
  - kernel/trace/trace.c:ftrace_trace_snapshot_callback
  - kernel/trace/trace.c:tracing_snapshot_write
  - kernel/trace/trace.c:tracing_set_tracer
  - kernel/trace/trace.c:tracing_snapshot_cond_enable
  - kernel/trace/trace_events_trigger.c:register_snapshot_trigger
```
**Symbols:**

```
ffffffff8119ba40-ffffffff8119ba6b: tracing_alloc_snapshot_instance.part.0 (STB_LOCAL)
ffffffff8119dfa0-ffffffff8119dfb4: tracing_alloc_snapshot_instance (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline, Transformation ⚠️</summary>

```c
int tracing_alloc_snapshot_instance(struct trace_array *tr);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/trace/trace.c (ffffffff811a98a9)
Location: kernel/trace/trace.c:1028
Inline: True
Inline callers:
  - kernel/trace/trace.c:ftrace_trace_snapshot_callback
  - kernel/trace/trace.c:tracing_snapshot_write
  - kernel/trace/trace.c:tracing_set_tracer
  - kernel/trace/trace.c:tracing_snapshot_cond_enable
Direct callers:
  - kernel/trace/trace.c:ftrace_trace_snapshot_callback
  - kernel/trace/trace.c:tracing_snapshot_write
  - kernel/trace/trace.c:tracing_set_tracer
  - kernel/trace/trace.c:tracing_snapshot_cond_enable
  - kernel/trace/trace_events_trigger.c:register_snapshot_trigger
```
**Symbols:**

```
ffffffff811a96e0-ffffffff811a970b: tracing_alloc_snapshot_instance.part.0 (STB_LOCAL)
ffffffff811abc80-ffffffff811abc94: tracing_alloc_snapshot_instance (STB_GLOBAL)
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
