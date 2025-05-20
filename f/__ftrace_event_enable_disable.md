# Function: <code>__ftrace_event_enable_disable</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int __ftrace_event_enable_disable(struct trace_event_file *file, int enable, int soft_disable);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_events.c (ffffffff8115de00)
Location: kernel/trace/trace_events.c:361
Inline: False
Direct callers:
  - kernel/trace/trace_events.c:__ftrace_set_clr_event_nolock
  - kernel/trace/trace_events.c:event_enable_write
  - kernel/trace/trace_events.c:ftrace_event_set_open
  - kernel/trace/trace_events.c:event_enable_free
  - kernel/trace/trace_events.c:event_remove
  - kernel/trace/trace_events.c:trace_event_enable_disable
  - kernel/trace/trace_events.c:event_enable_func
  - kernel/trace/trace_events.c:event_enable_func
```
**Symbols:**

```
ffffffff8115de00-ffffffff8115df80: __ftrace_event_enable_disable (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int __ftrace_event_enable_disable(struct trace_event_file *file, int enable, int soft_disable);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_events.c (ffffffff81168740)
Location: kernel/trace/trace_events.c:386
Inline: False
Direct callers:
  - kernel/trace/trace_events.c:event_enable_func
  - kernel/trace/trace_events.c:event_enable_func
  - kernel/trace/trace_events.c:event_enable_free
  - kernel/trace/trace_events.c:event_remove
  - kernel/trace/trace_events.c:ftrace_event_set_open
  - kernel/trace/trace_events.c:event_enable_write
  - kernel/trace/trace_events.c:__ftrace_set_clr_event_nolock
  - kernel/trace/trace_events.c:trace_event_enable_disable
```
**Symbols:**

```
ffffffff81168740-ffffffff81168931: __ftrace_event_enable_disable (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int __ftrace_event_enable_disable(struct trace_event_file *file, int enable, int soft_disable);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_events.c (ffffffff81173b70)
Location: kernel/trace/trace_events.c:346
Inline: False
Direct callers:
  - kernel/trace/trace_events.c:event_enable_func
  - kernel/trace/trace_events.c:event_enable_func
  - kernel/trace/trace_events.c:event_enable_free
  - kernel/trace/trace_events.c:event_remove
  - kernel/trace/trace_events.c:ftrace_event_set_open
  - kernel/trace/trace_events.c:event_enable_write
  - kernel/trace/trace_events.c:__ftrace_set_clr_event_nolock
  - kernel/trace/trace_events.c:trace_event_enable_disable
```
**Symbols:**

```
ffffffff81173b70-ffffffff81173d61: __ftrace_event_enable_disable (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int __ftrace_event_enable_disable(struct trace_event_file *file, int enable, int soft_disable);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_events.c (ffffffff811767d0)
Location: kernel/trace/trace_events.c:368
Inline: False
Direct callers:
  - kernel/trace/trace_events.c:event_enable_func
  - kernel/trace/trace_events.c:event_enable_func
  - kernel/trace/trace_events.c:event_remove
  - kernel/trace/trace_events.c:ftrace_event_set_open
  - kernel/trace/trace_events.c:event_enable_write
  - kernel/trace/trace_events.c:__ftrace_set_clr_event_nolock
  - kernel/trace/trace_events.c:trace_event_enable_disable
```
**Symbols:**

```
ffffffff811767d0-ffffffff81176a22: __ftrace_event_enable_disable (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int __ftrace_event_enable_disable(struct trace_event_file *file, int enable, int soft_disable);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_events.c (ffffffff81183f90)
Location: kernel/trace/trace_events.c:368
Inline: False
Direct callers:
  - kernel/trace/trace_events.c:event_enable_func
  - kernel/trace/trace_events.c:event_enable_func
  - kernel/trace/trace_events.c:event_remove
  - kernel/trace/trace_events.c:ftrace_event_set_open
  - kernel/trace/trace_events.c:event_enable_write
  - kernel/trace/trace_events.c:__ftrace_set_clr_event_nolock
  - kernel/trace/trace_events.c:trace_event_enable_disable
```
**Symbols:**

```
ffffffff81183f90-ffffffff811841f2: __ftrace_event_enable_disable (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Transformation ⚠️</summary>

```c
int __ftrace_event_enable_disable(struct trace_event_file *file, int enable, int soft_disable);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/trace/trace_events.c (0)
Location: kernel/trace/trace_events.c:368
Inline: False
Direct callers:
  - kernel/trace/trace_events.c:event_enable_func
  - kernel/trace/trace_events.c:event_enable_func
  - kernel/trace/trace_events.c:event_remove
  - kernel/trace/trace_events.c:ftrace_event_set_open
  - kernel/trace/trace_events.c:event_enable_write
  - kernel/trace/trace_events.c:__ftrace_set_clr_event_nolock
  - kernel/trace/trace_events.c:trace_event_enable_disable
```
**Symbols:**

```
ffffffff811930d0-ffffffff8119330e: __ftrace_event_enable_disable (STB_LOCAL)
ffffffff8119645b-ffffffff8119648a: __ftrace_event_enable_disable.cold.26 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Transformation ⚠️</summary>

```c
int __ftrace_event_enable_disable(struct trace_event_file *file, int enable, int soft_disable);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/trace/trace_events.c (0)
Location: kernel/trace/trace_events.c:369
Inline: False
Direct callers:
  - kernel/trace/trace_events.c:event_enable_func
  - kernel/trace/trace_events.c:event_enable_func
  - kernel/trace/trace_events.c:event_remove
  - kernel/trace/trace_events.c:ftrace_event_set_open
  - kernel/trace/trace_events.c:event_enable_write
  - kernel/trace/trace_events.c:__ftrace_set_clr_event_nolock
  - kernel/trace/trace_events.c:trace_event_enable_disable
```
**Symbols:**

```
ffffffff811a1240-ffffffff811a147e: __ftrace_event_enable_disable (STB_LOCAL)
ffffffff811a459c-ffffffff811a45cb: __ftrace_event_enable_disable.cold.25 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
int __ftrace_event_enable_disable(struct trace_event_file *file, int enable, int soft_disable);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/trace/trace_events.c (0)
Location: kernel/trace/trace_events.c:361
Inline: False
Direct callers:
  - kernel/trace/trace_events.c:event_enable_func
  - kernel/trace/trace_events.c:event_enable_func
  - kernel/trace/trace_events.c:event_remove
  - kernel/trace/trace_events.c:ftrace_event_set_open
  - kernel/trace/trace_events.c:event_enable_write
  - kernel/trace/trace_events.c:__ftrace_set_clr_event_nolock
  - kernel/trace/trace_events.c:trace_event_enable_disable
```
**Symbols:**

```
ffffffff811af170-ffffffff811af3a5: __ftrace_event_enable_disable (STB_LOCAL)
ffffffff811b24bf-ffffffff811b24ee: __ftrace_event_enable_disable.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
int __ftrace_event_enable_disable(struct trace_event_file *file, int enable, int soft_disable);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/trace/trace_events.c (0)
Location: kernel/trace/trace_events.c:362
Inline: False
Direct callers:
  - kernel/trace/trace_events.c:event_enable_func
  - kernel/trace/trace_events.c:event_enable_func
  - kernel/trace/trace_events.c:event_remove
  - kernel/trace/trace_events.c:ftrace_event_set_open
  - kernel/trace/trace_events.c:event_enable_write
  - kernel/trace/trace_events.c:__ftrace_set_clr_event_nolock
  - kernel/trace/trace_events.c:trace_event_enable_disable
```
**Symbols:**

```
ffffffff811ba640-ffffffff811ba875: __ftrace_event_enable_disable (STB_LOCAL)
ffffffff811bdadd-ffffffff811bdb0c: __ftrace_event_enable_disable.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
int __ftrace_event_enable_disable(struct trace_event_file *file, int enable, int soft_disable);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/trace/trace_events.c (0)
Location: kernel/trace/trace_events.c:367
Inline: False
Direct callers:
  - kernel/trace/trace_events.c:event_enable_func
  - kernel/trace/trace_events.c:event_enable_func
  - kernel/trace/trace_events.c:event_remove
  - kernel/trace/trace_events.c:ftrace_event_set_open
  - kernel/trace/trace_events.c:event_enable_write
  - kernel/trace/trace_events.c:__ftrace_set_clr_event_nolock
  - kernel/trace/trace_events.c:trace_event_enable_disable
```
**Symbols:**

```
ffffffff811d58e0-ffffffff811d5afa: __ftrace_event_enable_disable (STB_LOCAL)
ffffffff811d73f0-ffffffff811d741c: __ftrace_event_enable_disable.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
int __ftrace_event_enable_disable(struct trace_event_file *file, int enable, int soft_disable);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/trace/trace_events.c (0)
Location: kernel/trace/trace_events.c:368
Inline: False
Direct callers:
  - kernel/trace/trace_events.c:event_enable_func
  - kernel/trace/trace_events.c:event_enable_func
  - kernel/trace/trace_events.c:event_remove
  - kernel/trace/trace_events.c:ftrace_event_set_open
  - kernel/trace/trace_events.c:event_enable_write
  - kernel/trace/trace_events.c:__ftrace_set_clr_event_nolock
  - kernel/trace/trace_events.c:trace_event_enable_disable
```
**Symbols:**

```
ffffffff811d2bb0-ffffffff811d2dca: __ftrace_event_enable_disable (STB_LOCAL)
ffffffff81be6192-ffffffff81be61be: __ftrace_event_enable_disable.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
int __ftrace_event_enable_disable(struct trace_event_file *file, int enable, int soft_disable);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/trace/trace_events.c (0)
Location: kernel/trace/trace_events.c:575
Inline: False
Direct callers:
  - kernel/trace/trace_events.c:event_enable_func
  - kernel/trace/trace_events.c:event_enable_func
  - kernel/trace/trace_events.c:event_remove
  - kernel/trace/trace_events.c:ftrace_event_set_open
  - kernel/trace/trace_events.c:event_enable_write
  - kernel/trace/trace_events.c:__ftrace_set_clr_event_nolock
  - kernel/trace/trace_events.c:trace_event_enable_disable
```
**Symbols:**

```
ffffffff811d3860-ffffffff811d3a7c: __ftrace_event_enable_disable (STB_LOCAL)
ffffffff81bd7db6-ffffffff81bd7de2: __ftrace_event_enable_disable.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int __ftrace_event_enable_disable(struct trace_event_file *file, int enable, int soft_disable);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/trace/trace_events.c (0)
Location: kernel/trace/trace_events.c:576
Inline: False
Direct callers:
  - kernel/trace/trace_events.c:event_enable_func
  - kernel/trace/trace_events.c:event_enable_func
  - kernel/trace/trace_events.c:event_remove
  - kernel/trace/trace_events.c:ftrace_event_set_open
  - kernel/trace/trace_events.c:event_enable_write
  - kernel/trace/trace_events.c:__ftrace_set_clr_event_nolock
  - kernel/trace/trace_events.c:trace_event_enable_disable
```
**Symbols:**

```
ffffffff812006e0-ffffffff812008fc: __ftrace_event_enable_disable (STB_LOCAL)
ffffffff81cb63f3-ffffffff81cb641f: __ftrace_event_enable_disable.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int __ftrace_event_enable_disable(struct trace_event_file *file, int enable, int soft_disable);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/trace/trace_events.c (0)
Location: kernel/trace/trace_events.c:592
Inline: False
Direct callers:
  - kernel/trace/trace_events.c:event_enable_func
  - kernel/trace/trace_events.c:event_enable_func
  - kernel/trace/trace_events.c:event_remove
  - kernel/trace/trace_events.c:ftrace_event_set_open
  - kernel/trace/trace_events.c:event_enable_write
  - kernel/trace/trace_events.c:__ftrace_set_clr_event_nolock
  - kernel/trace/trace_events.c:trace_event_enable_disable
```
**Symbols:**

```
ffffffff8123a800-ffffffff8123aa60: __ftrace_event_enable_disable (STB_LOCAL)
ffffffff81e6730d-ffffffff81e67339: __ftrace_event_enable_disable.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int __ftrace_event_enable_disable(struct trace_event_file *file, int enable, int soft_disable);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_events.c (ffffffff81289330)
Location: kernel/trace/trace_events.c:607
Inline: False
Direct callers:
  - kernel/trace/trace_events.c:event_enable_func
  - kernel/trace/trace_events.c:event_enable_func
  - kernel/trace/trace_events.c:event_remove
  - kernel/trace/trace_events.c:ftrace_event_set_open
  - kernel/trace/trace_events.c:event_enable_write
  - kernel/trace/trace_events.c:__ftrace_set_clr_event_nolock
  - kernel/trace/trace_events.c:trace_event_enable_disable
```
**Symbols:**

```
ffffffff81289330-ffffffff812895bb: __ftrace_event_enable_disable (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int __ftrace_event_enable_disable(struct trace_event_file *file, int enable, int soft_disable);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_events.c (ffffffff812a6040)
Location: kernel/trace/trace_events.c:609
Inline: False
Direct callers:
  - kernel/trace/trace_events.c:event_enable_func
  - kernel/trace/trace_events.c:event_enable_func
  - kernel/trace/trace_events.c:event_remove
  - kernel/trace/trace_events.c:ftrace_event_set_open
  - kernel/trace/trace_events.c:event_enable_write
  - kernel/trace/trace_events.c:__ftrace_set_clr_event_nolock
  - kernel/trace/trace_events.c:trace_event_enable_disable
```
**Symbols:**

```
ffffffff812a6040-ffffffff812a6254: __ftrace_event_enable_disable (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int __ftrace_event_enable_disable(struct trace_event_file *file, int enable, int soft_disable);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_events.c (ffffffff812c1b60)
Location: kernel/trace/trace_events.c:609
Inline: False
Direct callers:
  - kernel/trace/trace_events.c:event_enable_func
  - kernel/trace/trace_events.c:event_enable_func
  - kernel/trace/trace_events.c:event_remove
  - kernel/trace/trace_events.c:ftrace_event_set_open
  - kernel/trace/trace_events.c:event_enable_write
  - kernel/trace/trace_events.c:__ftrace_set_clr_event_nolock
  - kernel/trace/trace_events.c:trace_event_enable_disable
```
**Symbols:**

```
ffffffff812c1b60-ffffffff812c1d74: __ftrace_event_enable_disable (STB_LOCAL)
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
int __ftrace_event_enable_disable(struct trace_event_file *file, int enable, int soft_disable);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_events.c (ffff80001023b260)
Location: kernel/trace/trace_events.c:362
Inline: False
Direct callers:
  - kernel/trace/trace_events.c:event_enable_func
  - kernel/trace/trace_events.c:event_enable_func
  - kernel/trace/trace_events.c:event_remove
  - kernel/trace/trace_events.c:ftrace_event_set_open
  - kernel/trace/trace_events.c:event_enable_write
  - kernel/trace/trace_events.c:__ftrace_set_clr_event_nolock
  - kernel/trace/trace_events.c:trace_event_enable_disable
```
**Symbols:**

```
ffff80001023b260-ffff80001023b684: __ftrace_event_enable_disable (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int __ftrace_event_enable_disable(struct trace_event_file *file, int enable, int soft_disable);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_events.c (c04759e0)
Location: kernel/trace/trace_events.c:362
Inline: False
Direct callers:
  - kernel/trace/trace_events.c:event_enable_func
  - kernel/trace/trace_events.c:event_enable_func
  - kernel/trace/trace_events.c:event_remove
  - kernel/trace/trace_events.c:ftrace_event_set_open
  - kernel/trace/trace_events.c:event_enable_write
  - kernel/trace/trace_events.c:__ftrace_set_clr_event_nolock
  - kernel/trace/trace_events.c:trace_event_enable_disable
```
**Symbols:**

```
c04759e0-c0475cdc: __ftrace_event_enable_disable (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int __ftrace_event_enable_disable(struct trace_event_file *file, int enable, int soft_disable);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_events.c (c0000000002c5780)
Location: kernel/trace/trace_events.c:362
Inline: False
Direct callers:
  - kernel/trace/trace_events.c:event_enable_func
  - kernel/trace/trace_events.c:event_enable_func
  - kernel/trace/trace_events.c:event_remove
  - kernel/trace/trace_events.c:ftrace_event_set_open
  - kernel/trace/trace_events.c:event_enable_write
  - kernel/trace/trace_events.c:__ftrace_set_clr_event_nolock
  - kernel/trace/trace_events.c:trace_event_enable_disable
```
**Symbols:**

```
c0000000002c5780-c0000000002c5c0c: __ftrace_event_enable_disable (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int __ftrace_event_enable_disable(struct trace_event_file *file, int enable, int soft_disable);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_events.c (ffffffe00018fcba)
Location: kernel/trace/trace_events.c:362
Inline: False
Direct callers:
  - kernel/trace/trace_events.c:event_enable_func
  - kernel/trace/trace_events.c:event_enable_func
  - kernel/trace/trace_events.c:event_remove
  - kernel/trace/trace_events.c:ftrace_event_set_open
  - kernel/trace/trace_events.c:event_enable_write
  - kernel/trace/trace_events.c:__ftrace_set_clr_event_nolock
  - kernel/trace/trace_events.c:trace_event_enable_disable
```
**Symbols:**

```
ffffffe00018fcba-ffffffe00018fef4: __ftrace_event_enable_disable (STB_LOCAL)
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
int __ftrace_event_enable_disable(struct trace_event_file *file, int enable, int soft_disable);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/trace/trace_events.c (0)
Location: kernel/trace/trace_events.c:362
Inline: False
Direct callers:
  - kernel/trace/trace_events.c:event_enable_func
  - kernel/trace/trace_events.c:event_enable_func
  - kernel/trace/trace_events.c:event_remove
  - kernel/trace/trace_events.c:ftrace_event_set_open
  - kernel/trace/trace_events.c:event_enable_write
  - kernel/trace/trace_events.c:__ftrace_set_clr_event_nolock
  - kernel/trace/trace_events.c:trace_event_enable_disable
```
**Symbols:**

```
ffffffff811b2c60-ffffffff811b2e95: __ftrace_event_enable_disable (STB_LOCAL)
ffffffff811b60fd-ffffffff811b612c: __ftrace_event_enable_disable.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Transformation ⚠️</summary>

```c
int __ftrace_event_enable_disable(struct trace_event_file *file, int enable, int soft_disable);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/trace/trace_events.c (0)
Location: kernel/trace/trace_events.c:362
Inline: False
Direct callers:
  - kernel/trace/trace_events.c:event_enable_func
  - kernel/trace/trace_events.c:event_enable_func
  - kernel/trace/trace_events.c:event_remove
  - kernel/trace/trace_events.c:ftrace_event_set_open
  - kernel/trace/trace_events.c:event_enable_write
  - kernel/trace/trace_events.c:__ftrace_set_clr_event_nolock
  - kernel/trace/trace_events.c:trace_event_enable_disable
```
**Symbols:**

```
ffffffff811a5a60-ffffffff811a5c95: __ftrace_event_enable_disable (STB_LOCAL)
ffffffff811a8efd-ffffffff811a8f2c: __ftrace_event_enable_disable.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Transformation ⚠️</summary>

```c
int __ftrace_event_enable_disable(struct trace_event_file *file, int enable, int soft_disable);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/trace/trace_events.c (0)
Location: kernel/trace/trace_events.c:362
Inline: False
Direct callers:
  - kernel/trace/trace_events.c:event_enable_func
  - kernel/trace/trace_events.c:event_enable_func
  - kernel/trace/trace_events.c:event_remove
  - kernel/trace/trace_events.c:ftrace_event_set_open
  - kernel/trace/trace_events.c:event_enable_write
  - kernel/trace/trace_events.c:__ftrace_set_clr_event_nolock
  - kernel/trace/trace_events.c:trace_event_enable_disable
```
**Symbols:**

```
ffffffff811b0a30-ffffffff811b0c65: __ftrace_event_enable_disable (STB_LOCAL)
ffffffff811b3ecd-ffffffff811b3efc: __ftrace_event_enable_disable.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
int __ftrace_event_enable_disable(struct trace_event_file *file, int enable, int soft_disable);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/trace/trace_events.c (0)
Location: kernel/trace/trace_events.c:362
Inline: False
Direct callers:
  - kernel/trace/trace_events.c:event_enable_func
  - kernel/trace/trace_events.c:event_enable_func
  - kernel/trace/trace_events.c:event_remove
  - kernel/trace/trace_events.c:ftrace_event_set_open
  - kernel/trace/trace_events.c:event_enable_write
  - kernel/trace/trace_events.c:__ftrace_set_clr_event_nolock
  - kernel/trace/trace_events.c:trace_event_enable_disable
```
**Symbols:**

```
ffffffff811beac0-ffffffff811becf5: __ftrace_event_enable_disable (STB_LOCAL)
ffffffff811c1f6d-ffffffff811c1f9c: __ftrace_event_enable_disable.cold (STB_LOCAL)
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
