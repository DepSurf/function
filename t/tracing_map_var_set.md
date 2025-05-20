# Function: <code>tracing_map_var_set</code>

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
bool tracing_map_var_set(struct tracing_map_elt *elt, unsigned int i);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/tracing_map.c (ffffffff811898e0)
Location: kernel/trace/tracing_map.c:94
Inline: False
Direct callers:
  - kernel/trace/trace_events_hist.c:resolve_var_refs
```
**Symbols:**

```
ffffffff811898e0-ffffffff811898eb: tracing_map_var_set (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
bool tracing_map_var_set(struct tracing_map_elt *elt, unsigned int i);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/tracing_map.c (ffffffff81197190)
Location: kernel/trace/tracing_map.c:85
Inline: False
Direct callers:
  - kernel/trace/trace_events_hist.c:resolve_var_refs
```
**Symbols:**

```
ffffffff81197190-ffffffff8119719b: tracing_map_var_set (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
bool tracing_map_var_set(struct tracing_map_elt *elt, unsigned int i);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/tracing_map.c (ffffffff811a53e0)
Location: kernel/trace/tracing_map.c:85
Inline: False
Direct callers:
  - kernel/trace/trace_events_hist.c:resolve_var_refs
```
**Symbols:**

```
ffffffff811a53e0-ffffffff811a53eb: tracing_map_var_set (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
bool tracing_map_var_set(struct tracing_map_elt *elt, unsigned int i);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/tracing_map.c (ffffffff811b0c10)
Location: kernel/trace/tracing_map.c:85
Inline: False
Direct callers:
  - kernel/trace/trace_events_hist.c:resolve_var_refs
```
**Symbols:**

```
ffffffff811b0c10-ffffffff811b0c1b: tracing_map_var_set (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
bool tracing_map_var_set(struct tracing_map_elt *elt, unsigned int i);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/tracing_map.c (ffffffff811c93d0)
Location: kernel/trace/tracing_map.c:85
Inline: False
Direct callers:
  - kernel/trace/trace_events_hist.c:resolve_var_refs
```
**Symbols:**

```
ffffffff811c93d0-ffffffff811c93db: tracing_map_var_set (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
bool tracing_map_var_set(struct tracing_map_elt *elt, unsigned int i);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/tracing_map.c (ffffffff811c6a90)
Location: kernel/trace/tracing_map.c:85
Inline: False
Direct callers:
  - kernel/trace/trace_events_hist.c:resolve_var_refs
```
**Symbols:**

```
ffffffff811c6a90-ffffffff811c6a9b: tracing_map_var_set (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
bool tracing_map_var_set(struct tracing_map_elt *elt, unsigned int i);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/tracing_map.c (ffffffff811c7a80)
Location: kernel/trace/tracing_map.c:85
Inline: False
Direct callers:
  - kernel/trace/trace_events_hist.c:resolve_var_refs
```
**Symbols:**

```
ffffffff811c7a80-ffffffff811c7a8b: tracing_map_var_set (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
bool tracing_map_var_set(struct tracing_map_elt *elt, unsigned int i);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/trace/tracing_map.c (0)
Location: kernel/trace/tracing_map.c:86
Inline: False
Direct callers:
  - kernel/trace/trace_events_hist.c:resolve_var_refs
```
**Symbols:**

```
ffffffff81cb5bb0-ffffffff81cb5bd0: tracing_map_var_set.cold (STB_LOCAL)
ffffffff811f32e0-ffffffff811f32f6: tracing_map_var_set (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
bool tracing_map_var_set(struct tracing_map_elt *elt, unsigned int i);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/trace/tracing_map.c (0)
Location: kernel/trace/tracing_map.c:86
Inline: False
Direct callers:
  - kernel/trace/trace_events_hist.c:resolve_var_refs
```
**Symbols:**

```
ffffffff81e66bb7-ffffffff81e66be1: tracing_map_var_set.cold (STB_LOCAL)
ffffffff8122c920-ffffffff8122c940: tracing_map_var_set (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
bool tracing_map_var_set(struct tracing_map_elt *elt, unsigned int i);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/trace/tracing_map.c (0)
Location: kernel/trace/tracing_map.c:86
Inline: False
Direct callers:
  - kernel/trace/trace_events_hist.c:resolve_var_refs
```
**Symbols:**

```
ffffffff8205dc75-ffffffff8205dc9f: tracing_map_var_set.cold (STB_LOCAL)
ffffffff812784c0-ffffffff812784e0: tracing_map_var_set (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
bool tracing_map_var_set(struct tracing_map_elt *elt, unsigned int i);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/trace/tracing_map.c (0)
Location: kernel/trace/tracing_map.c:86
Inline: False
Direct callers:
  - kernel/trace/trace_events_hist.c:resolve_var_refs
```
**Symbols:**

```
ffffffff820dc59d-ffffffff820dc5c7: tracing_map_var_set.cold (STB_LOCAL)
ffffffff8128ff00-ffffffff8128ff20: tracing_map_var_set (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
bool tracing_map_var_set(struct tracing_map_elt *elt, unsigned int i);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/trace/tracing_map.c (0)
Location: kernel/trace/tracing_map.c:86
Inline: False
Direct callers:
  - kernel/trace/trace_events_hist.c:resolve_var_refs
```
**Symbols:**

```
ffffffff821b83cc-ffffffff821b83f6: tracing_map_var_set.cold (STB_LOCAL)
ffffffff812ab4c0-ffffffff812ab4e0: tracing_map_var_set (STB_GLOBAL)
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
bool tracing_map_var_set(struct tracing_map_elt *elt, unsigned int i);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/tracing_map.c (ffff80001022e4b8)
Location: kernel/trace/tracing_map.c:85
Inline: False
Direct callers:
  - kernel/trace/trace_events_hist.c:resolve_var_refs
```
**Symbols:**

```
ffff80001022e4b8-ffff80001022e4c4: tracing_map_var_set (STB_GLOBAL)
```
</details>
</li>
<li>
In <code>armhf</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
bool tracing_map_var_set(struct tracing_map_elt *elt, unsigned int i);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/tracing_map.c (c0000000002b7820)
Location: kernel/trace/tracing_map.c:85
Inline: False
Direct callers:
  - kernel/trace/trace_events_hist.c:resolve_var_refs
```
**Symbols:**

```
c0000000002b7820-c0000000002b782c: tracing_map_var_set (STB_GLOBAL)
```
</details>
</li>
<li>
In <code>riscv64</code>: Absent ⚠️
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: ✅</summary>

```c
bool tracing_map_var_set(struct tracing_map_elt *elt, unsigned int i);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/tracing_map.c (ffffffff811a9230)
Location: kernel/trace/tracing_map.c:85
Inline: False
Direct callers:
  - kernel/trace/trace_events_hist.c:resolve_var_refs
```
**Symbols:**

```
ffffffff811a9230-ffffffff811a923b: tracing_map_var_set (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
bool tracing_map_var_set(struct tracing_map_elt *elt, unsigned int i);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/tracing_map.c (ffffffff8119c1b0)
Location: kernel/trace/tracing_map.c:85
Inline: False
Direct callers:
  - kernel/trace/trace_events_hist.c:resolve_var_refs
```
**Symbols:**

```
ffffffff8119c1b0-ffffffff8119c1bb: tracing_map_var_set (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
bool tracing_map_var_set(struct tracing_map_elt *elt, unsigned int i);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/tracing_map.c (ffffffff811a7000)
Location: kernel/trace/tracing_map.c:85
Inline: False
Direct callers:
  - kernel/trace/trace_events_hist.c:resolve_var_refs
```
**Symbols:**

```
ffffffff811a7000-ffffffff811a700b: tracing_map_var_set (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
bool tracing_map_var_set(struct tracing_map_elt *elt, unsigned int i);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/tracing_map.c (ffffffff811b4da0)
Location: kernel/trace/tracing_map.c:85
Inline: False
Direct callers:
  - kernel/trace/trace_events_hist.c:resolve_var_refs
```
**Symbols:**

```
ffffffff811b4da0-ffffffff811b4dab: tracing_map_var_set (STB_GLOBAL)
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
No changes between <code>amd64</code> and <code>ppc64el</code> ✅
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
