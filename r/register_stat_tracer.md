# Function: <code>register_stat_tracer</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int register_stat_tracer(struct tracer_stat *trace);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_stat.c (ffffffff81155e90)
Location: kernel/trace/trace_stat.c:302
Inline: False
Direct callers:
  - kernel/trace/ftrace.c:ftrace_init_tracefs
```
**Symbols:**

```
ffffffff81155e90-ffffffff8115603b: register_stat_tracer (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int register_stat_tracer(struct tracer_stat *trace);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_stat.c (ffffffff8115f1c0)
Location: kernel/trace/trace_stat.c:301
Inline: False
Direct callers:
  - kernel/trace/ftrace.c:ftrace_init_tracefs_toplevel
```
**Symbols:**

```
ffffffff8115f1c0-ffffffff8115f36b: register_stat_tracer (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int register_stat_tracer(struct tracer_stat *trace);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_stat.c (ffffffff81169c20)
Location: kernel/trace/trace_stat.c:301
Inline: False
Direct callers:
  - kernel/trace/ftrace.c:ftrace_init_tracefs_toplevel
```
**Symbols:**

```
ffffffff81169c20-ffffffff81169dcb: register_stat_tracer (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int register_stat_tracer(struct tracer_stat *trace);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_stat.c (ffffffff8116cbb0)
Location: kernel/trace/trace_stat.c:301
Inline: False
Direct callers:
  - kernel/trace/ftrace.c:ftrace_init_tracefs_toplevel
```
**Symbols:**

```
ffffffff8116cbb0-ffffffff8116cd72: register_stat_tracer (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int register_stat_tracer(struct tracer_stat *trace);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_stat.c (ffffffff81179c60)
Location: kernel/trace/trace_stat.c:302
Inline: False
Direct callers:
  - kernel/trace/ftrace.c:ftrace_init_tracefs_toplevel
```
**Symbols:**

```
ffffffff81179c60-ffffffff81179e22: register_stat_tracer (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Transformation ⚠️</summary>

```c
int register_stat_tracer(struct tracer_stat *trace);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/trace/trace_stat.c (0)
Location: kernel/trace/trace_stat.c:302
Inline: False
Direct callers:
  - kernel/trace/ftrace.c:ftrace_init_tracefs_toplevel
```
**Symbols:**

```
ffffffff8118906a-ffffffff81189082: register_stat_tracer.cold.5 (STB_LOCAL)
ffffffff81188e10-ffffffff81188fcb: register_stat_tracer (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Transformation ⚠️</summary>

```c
int register_stat_tracer(struct tracer_stat *trace);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/trace/trace_stat.c (0)
Location: kernel/trace/trace_stat.c:302
Inline: False
Direct callers:
  - kernel/trace/ftrace.c:ftrace_init_tracefs_toplevel
```
**Symbols:**

```
ffffffff8119691a-ffffffff81196932: register_stat_tracer.cold.4 (STB_LOCAL)
ffffffff811966c0-ffffffff8119687b: register_stat_tracer (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
int register_stat_tracer(struct tracer_stat *trace);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/trace/trace_stat.c (0)
Location: kernel/trace/trace_stat.c:302
Inline: False
Direct callers:
  - kernel/trace/ftrace.c:ftrace_init_tracefs_toplevel
```
**Symbols:**

```
ffffffff811a47c6-ffffffff811a47de: register_stat_tracer.cold (STB_LOCAL)
ffffffff811a4580-ffffffff811a472c: register_stat_tracer (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
int register_stat_tracer(struct tracer_stat *trace);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/trace/trace_stat.c (0)
Location: kernel/trace/trace_stat.c:310
Inline: False
Direct callers:
  - kernel/trace/ftrace.c:ftrace_init_tracefs_toplevel
```
**Symbols:**

```
ffffffff811affd6-ffffffff811afff2: register_stat_tracer.cold (STB_LOCAL)
ffffffff811afda0-ffffffff811aff36: register_stat_tracer (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
int register_stat_tracer(struct tracer_stat *trace);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/trace/trace_stat.c (0)
Location: kernel/trace/trace_stat.c:308
Inline: False
Direct callers:
  - kernel/trace/ftrace.c:ftrace_profile_tracefs
```
**Symbols:**

```
ffffffff811c8186-ffffffff811c819c: register_stat_tracer.cold (STB_LOCAL)
ffffffff811c7f60-ffffffff811c80ed: register_stat_tracer (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
int register_stat_tracer(struct tracer_stat *trace);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/trace/trace_stat.c (0)
Location: kernel/trace/trace_stat.c:308
Inline: False
Direct callers:
  - kernel/trace/ftrace.c:ftrace_profile_tracefs
```
**Symbols:**

```
ffffffff81be5ac5-ffffffff81be5adb: register_stat_tracer.cold (STB_LOCAL)
ffffffff811c5660-ffffffff811c57e8: register_stat_tracer (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
int register_stat_tracer(struct tracer_stat *trace);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/trace/trace_stat.c (0)
Location: kernel/trace/trace_stat.c:308
Inline: False
Direct callers:
  - kernel/trace/ftrace.c:ftrace_init_tracefs_toplevel
```
**Symbols:**

```
ffffffff81bd797b-ffffffff81bd7991: register_stat_tracer.cold (STB_LOCAL)
ffffffff811c6850-ffffffff811c69d8: register_stat_tracer (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int register_stat_tracer(struct tracer_stat *trace);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/trace/trace_stat.c (0)
Location: kernel/trace/trace_stat.c:308
Inline: False
Direct callers:
  - kernel/trace/ftrace.c:ftrace_init_tracefs_toplevel
```
**Symbols:**

```
ffffffff81cb58a5-ffffffff81cb58bb: register_stat_tracer.cold (STB_LOCAL)
ffffffff811f1e40-ffffffff811f1fc8: register_stat_tracer (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int register_stat_tracer(struct tracer_stat *trace);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/trace/trace_stat.c (0)
Location: kernel/trace/trace_stat.c:308
Inline: False
Direct callers:
  - kernel/trace/ftrace.c:ftrace_init_tracefs_toplevel
```
**Symbols:**

```
ffffffff81e668a9-ffffffff81e668c4: register_stat_tracer.cold (STB_LOCAL)
ffffffff8122a880-ffffffff8122aa15: register_stat_tracer (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int register_stat_tracer(struct tracer_stat *trace);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_stat.c (ffffffff81276130)
Location: kernel/trace/trace_stat.c:308
Inline: False
Direct callers:
  - kernel/trace/ftrace.c:ftrace_init_tracefs_toplevel
```
**Symbols:**

```
ffffffff81276130-ffffffff812762d8: register_stat_tracer (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int register_stat_tracer(struct tracer_stat *trace);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_stat.c (ffffffff8128daf0)
Location: kernel/trace/trace_stat.c:308
Inline: False
Direct callers:
  - kernel/trace/ftrace.c:ftrace_profile_tracefs
```
**Symbols:**

```
ffffffff8128daf0-ffffffff8128dc98: register_stat_tracer (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int register_stat_tracer(struct tracer_stat *trace);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_stat.c (ffffffff812a8f10)
Location: kernel/trace/trace_stat.c:308
Inline: False
Direct callers:
  - kernel/trace/ftrace.c:ftrace_profile_tracefs
```
**Symbols:**

```
ffffffff812a8f10-ffffffff812a90e7: register_stat_tracer (STB_GLOBAL)
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
int register_stat_tracer(struct tracer_stat *trace);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_stat.c (ffff80001022d378)
Location: kernel/trace/trace_stat.c:310
Inline: False
Direct callers:
  - kernel/trace/ftrace.c:ftrace_init_tracefs_toplevel
```
**Symbols:**

```
ffff80001022d378-ffff80001022d504: register_stat_tracer (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int register_stat_tracer(struct tracer_stat *trace);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_stat.c (c046aa54)
Location: kernel/trace/trace_stat.c:310
Inline: False
Direct callers:
  - kernel/trace/ftrace.c:ftrace_init_tracefs_toplevel
```
**Symbols:**

```
c046aa54-c046ac00: register_stat_tracer (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int register_stat_tracer(struct tracer_stat *trace);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_stat.c (c0000000002b5f60)
Location: kernel/trace/trace_stat.c:310
Inline: False
Direct callers:
  - kernel/trace/ftrace.c:ftrace_init_tracefs_toplevel
```
**Symbols:**

```
c0000000002b5f60-c0000000002b6190: register_stat_tracer (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int register_stat_tracer(struct tracer_stat *trace);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_stat.c (ffffffe000186eca)
Location: kernel/trace/trace_stat.c:310
Inline: False
Direct callers:
  - kernel/trace/ftrace.c:ftrace_init_tracefs_toplevel
```
**Symbols:**

```
ffffffe000186eca-ffffffe000187048: register_stat_tracer (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Transformation ⚠️</summary>

```c
int register_stat_tracer(struct tracer_stat *trace);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/trace/trace_stat.c (0)
Location: kernel/trace/trace_stat.c:310
Inline: False
Direct callers:
  - kernel/trace/ftrace.c:ftrace_init_tracefs_toplevel
```
**Symbols:**

```
ffffffff811a85f6-ffffffff811a8612: register_stat_tracer.cold (STB_LOCAL)
ffffffff811a83c0-ffffffff811a8556: register_stat_tracer (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Transformation ⚠️</summary>

```c
int register_stat_tracer(struct tracer_stat *trace);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/trace/trace_stat.c (0)
Location: kernel/trace/trace_stat.c:310
Inline: False
Direct callers:
  - kernel/trace/ftrace.c:ftrace_init_tracefs_toplevel
```
**Symbols:**

```
ffffffff8119b576-ffffffff8119b592: register_stat_tracer.cold (STB_LOCAL)
ffffffff8119b340-ffffffff8119b4d6: register_stat_tracer (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Transformation ⚠️</summary>

```c
int register_stat_tracer(struct tracer_stat *trace);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/trace/trace_stat.c (0)
Location: kernel/trace/trace_stat.c:310
Inline: False
Direct callers:
  - kernel/trace/ftrace.c:ftrace_init_tracefs_toplevel
```
**Symbols:**

```
ffffffff811a63c6-ffffffff811a63e2: register_stat_tracer.cold (STB_LOCAL)
ffffffff811a6190-ffffffff811a6326: register_stat_tracer (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
int register_stat_tracer(struct tracer_stat *trace);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/trace/trace_stat.c (0)
Location: kernel/trace/trace_stat.c:310
Inline: False
Direct callers:
  - kernel/trace/ftrace.c:ftrace_init_tracefs_toplevel
```
**Symbols:**

```
ffffffff811b4166-ffffffff811b4182: register_stat_tracer.cold (STB_LOCAL)
ffffffff811b3f30-ffffffff811b40c6: register_stat_tracer (STB_GLOBAL)
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
