# Function: <code>tracing_snapshot</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void tracing_snapshot();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace.c (ffffffff8114eed0)
Location: kernel/trace/trace.c:641
Inline: False
Direct callers:
  - kernel/trace/trace.c:tracing_snapshot_alloc
  - kernel/trace/trace.c:ftrace_snapshot
  - kernel/trace/trace.c:ftrace_count_snapshot
  - kernel/trace/trace_events_trigger.c:snapshot_count_trigger
```
**Symbols:**

```
ffffffff8114eed0-ffffffff8114f04c: tracing_snapshot (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void tracing_snapshot();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace.c (ffffffff81157e90)
Location: kernel/trace/trace.c:876
Inline: False
Direct callers:
  - kernel/trace/trace.c:ftrace_count_snapshot
  - kernel/trace/trace.c:ftrace_snapshot
  - kernel/trace/trace.c:tracing_snapshot_alloc
  - kernel/trace/trace_events_trigger.c:snapshot_count_trigger
```
**Symbols:**

```
ffffffff81157e90-ffffffff8115800c: tracing_snapshot (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void tracing_snapshot();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace.c (ffffffff81162890)
Location: kernel/trace/trace.c:919
Inline: False
Direct callers:
  - kernel/trace/trace.c:ftrace_count_snapshot
  - kernel/trace/trace.c:ftrace_snapshot
  - kernel/trace/trace.c:tracing_snapshot_alloc
  - kernel/trace/trace_events_trigger.c:snapshot_count_trigger
```
**Symbols:**

```
ffffffff81162890-ffffffff81162a0c: tracing_snapshot (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
void tracing_snapshot();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/trace/trace.c (ffffffff81165ddd)
Location: kernel/trace/trace.c:941
Inline: True
Inline callers:
  - kernel/trace/trace.c:tracing_snapshot_alloc
Direct callers:
  - kernel/trace/trace_events_trigger.c:snapshot_count_trigger
```
**Symbols:**

```
ffffffff81165db0-ffffffff81165dc2: tracing_snapshot (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
void tracing_snapshot();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/trace/trace.c (ffffffff81172d6d)
Location: kernel/trace/trace.c:941
Inline: True
Inline callers:
  - kernel/trace/trace.c:tracing_snapshot_alloc
Direct callers:
  - kernel/trace/trace_events_trigger.c:snapshot_count_trigger
```
**Symbols:**

```
ffffffff81172d40-ffffffff81172d52: tracing_snapshot (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
void tracing_snapshot();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/trace/trace.c (ffffffff81181d4d)
Location: kernel/trace/trace.c:940
Inline: True
Inline callers:
  - kernel/trace/trace.c:tracing_snapshot_alloc
```
**Symbols:**

```
ffffffff81181d20-ffffffff81181d32: tracing_snapshot (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
void tracing_snapshot();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/trace/trace.c (ffffffff8118f70d)
Location: kernel/trace/trace.c:941
Inline: True
Inline callers:
  - kernel/trace/trace.c:tracing_snapshot_alloc
```
**Symbols:**

```
ffffffff8118f6e0-ffffffff8118f6f2: tracing_snapshot (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
void tracing_snapshot();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/trace/trace.c (ffffffff8119d100)
Location: kernel/trace/trace.c:950
Inline: True
```
**Symbols:**

```
ffffffff8119d100-ffffffff8119d114: tracing_snapshot (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
void tracing_snapshot();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/trace/trace.c (ffffffff811a8ab0)
Location: kernel/trace/trace.c:968
Inline: True
```
**Symbols:**

```
ffffffff811a8ab0-ffffffff811a8ac4: tracing_snapshot (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
void tracing_snapshot();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/trace/trace.c (ffffffff811c0c00)
Location: kernel/trace/trace.c:1000
Inline: True
Direct callers:
  - kernel/trace/trace_events_trigger.c:snapshot_count_trigger
```
**Symbols:**

```
ffffffff811c0c00-ffffffff811c0c14: tracing_snapshot (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
void tracing_snapshot();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/trace/trace.c (ffffffff811be830)
Location: kernel/trace/trace.c:1151
Inline: True
Direct callers:
  - kernel/trace/trace_events_trigger.c:snapshot_count_trigger
```
**Symbols:**

```
ffffffff811be830-ffffffff811be844: tracing_snapshot (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
void tracing_snapshot();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/trace/trace.c (ffffffff811becf0)
Location: kernel/trace/trace.c:1148
Inline: True
```
**Symbols:**

```
ffffffff811becf0-ffffffff811bed04: tracing_snapshot (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
void tracing_snapshot();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/trace/trace.c (ffffffff811e9510)
Location: kernel/trace/trace.c:1161
Inline: True
```
**Symbols:**

```
ffffffff811e9510-ffffffff811e9524: tracing_snapshot (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
void tracing_snapshot();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/trace/trace.c (ffffffff83485dcb)
Location: kernel/trace/trace.c:1151
Inline: True
Inline callers:
  - kernel/trace/trace.c:ftrace_boot_snapshot
```
**Symbols:**

```
ffffffff81221970-ffffffff8122198c: tracing_snapshot (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
void tracing_snapshot();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/trace/trace.c (ffffffff83eb4c48)
Location: kernel/trace/trace.c:1150
Inline: True
Inline callers:
  - kernel/trace/trace.c:ftrace_boot_snapshot
```
**Symbols:**

```
ffffffff8126c880-ffffffff8126c89c: tracing_snapshot (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
void tracing_snapshot();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/trace/trace.c (ffffffff81283a10)
Location: kernel/trace/trace.c:1201
Inline: True
```
**Symbols:**

```
ffffffff81283a10-ffffffff81283a2c: tracing_snapshot (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
void tracing_snapshot();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/trace/trace.c (ffffffff8129eb10)
Location: kernel/trace/trace.c:1203
Inline: True
```
**Symbols:**

```
ffffffff8129eb10-ffffffff8129eb2c: tracing_snapshot (STB_GLOBAL)
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
void tracing_snapshot();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/trace/trace.c (ffff800010225670)
Location: kernel/trace/trace.c:968
Inline: True
```
**Symbols:**

```
ffff800010225670-ffff800010225690: tracing_snapshot (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
void tracing_snapshot();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/trace/trace.c (c0462b58)
Location: kernel/trace/trace.c:968
Inline: True
```
**Symbols:**

```
c0462b58-c0462b78: tracing_snapshot (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
void tracing_snapshot();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/trace/trace.c (c0000000002aad40)
Location: kernel/trace/trace.c:968
Inline: True
```
**Symbols:**

```
c0000000002aad40-c0000000002aad58: tracing_snapshot (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
void tracing_snapshot();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/trace/trace.c (ffffffe00018053c)
Location: kernel/trace/trace.c:968
Inline: True
```
**Symbols:**

```
ffffffe00018053c-ffffffe00018055e: tracing_snapshot (STB_GLOBAL)
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
void tracing_snapshot();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/trace/trace.c (ffffffff811a10d0)
Location: kernel/trace/trace.c:968
Inline: True
```
**Symbols:**

```
ffffffff811a10d0-ffffffff811a10e4: tracing_snapshot (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
void tracing_snapshot();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/trace/trace.c (ffffffff811940a0)
Location: kernel/trace/trace.c:968
Inline: True
```
**Symbols:**

```
ffffffff811940a0-ffffffff811940b4: tracing_snapshot (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
void tracing_snapshot();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/trace/trace.c (ffffffff8119eea0)
Location: kernel/trace/trace.c:968
Inline: True
```
**Symbols:**

```
ffffffff8119eea0-ffffffff8119eeb4: tracing_snapshot (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
void tracing_snapshot();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/trace/trace.c (ffffffff811acba0)
Location: kernel/trace/trace.c:968
Inline: True
```
**Symbols:**

```
ffffffff811acba0-ffffffff811acbb4: tracing_snapshot (STB_GLOBAL)
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
