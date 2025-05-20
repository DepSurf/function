# Function: <code>event_hist_trigger_func</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int event_hist_trigger_func(struct event_command *cmd_ops, struct trace_event_file *file, char *glob, char *cmd, char *param);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_events_hist.c (ffffffff811738e0)
Location: kernel/trace/trace_events_hist.c:1516
Inline: False
```
**Symbols:**

```
ffffffff811738e0-ffffffff81173d51: event_hist_trigger_func (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int event_hist_trigger_func(struct event_command *cmd_ops, struct trace_event_file *file, char *glob, char *cmd, char *param);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_events_hist.c (ffffffff8117e8f0)
Location: kernel/trace/trace_events_hist.c:1516
Inline: False
```
**Symbols:**

```
ffffffff8117e8f0-ffffffff8117f521: event_hist_trigger_func (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int event_hist_trigger_func(struct event_command *cmd_ops, struct trace_event_file *file, char *glob, char *cmd, char *param);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_events_hist.c (ffffffff811814c0)
Location: kernel/trace/trace_events_hist.c:1517
Inline: False
```
**Symbols:**

```
ffffffff811814c0-ffffffff81182208: event_hist_trigger_func (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int event_hist_trigger_func(struct event_command *cmd_ops, struct trace_event_file *file, char *glob, char *cmd, char *param);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_events_hist.c (ffffffff8118ee50)
Location: kernel/trace/trace_events_hist.c:1561
Inline: False
```
**Symbols:**

```
ffffffff8118ee50-ffffffff8118fbc6: event_hist_trigger_func (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int event_hist_trigger_func(struct event_command *cmd_ops, struct trace_event_file *file, char *glob, char *cmd, char *param);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_events_hist.c (ffffffff811a1260)
Location: kernel/trace/trace_events_hist.c:5467
Inline: False
Direct callers:
  - kernel/trace/trace_events_hist.c:event_hist_trigger_free
```
**Symbols:**

```
ffffffff811a1260-ffffffff811a2cc8: event_hist_trigger_func (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int event_hist_trigger_func(struct event_command *cmd_ops, struct trace_event_file *file, char *glob, char *cmd, char *param);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_events_hist.c (ffffffff811b0cb0)
Location: kernel/trace/trace_events_hist.c:5553
Inline: False
Direct callers:
  - kernel/trace/trace_events_hist.c:event_hist_trigger_free
```
**Symbols:**

```
ffffffff811b0cb0-ffffffff811b1712: event_hist_trigger_func (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int event_hist_trigger_func(struct event_command *cmd_ops, struct trace_event_file *file, char *glob, char *cmd, char *param);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_events_hist.c (ffffffff811bf2b0)
Location: kernel/trace/trace_events_hist.c:6073
Inline: False
Direct callers:
  - kernel/trace/trace_events_hist.c:event_hist_trigger_free
  - kernel/trace/trace_events_hist.c:create_field_var_hist
```
**Symbols:**

```
ffffffff811bf2b0-ffffffff811bfb80: event_hist_trigger_func (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int event_hist_trigger_func(struct event_command *cmd_ops, struct trace_event_file *file, char *glob, char *cmd, char *param);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_events_hist.c (ffffffff811cab00)
Location: kernel/trace/trace_events_hist.c:6199
Inline: False
Direct callers:
  - kernel/trace/trace_events_hist.c:event_hist_trigger_free
  - kernel/trace/trace_events_hist.c:create_field_var_hist
```
**Symbols:**

```
ffffffff811cab00-ffffffff811cb3d0: event_hist_trigger_func (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
int event_hist_trigger_func(struct event_command *cmd_ops, struct trace_event_file *file, char *glob, char *cmd, char *param);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/trace/trace_events_hist.c (0)
Location: kernel/trace/trace_events_hist.c:5580
Inline: False
Direct callers:
  - kernel/trace/trace_events_hist.c:event_hist_trigger_free
  - kernel/trace/trace_events_hist.c:create_field_var_hist
```
**Symbols:**

```
ffffffff811e6930-ffffffff811e7169: event_hist_trigger_func (STB_LOCAL)
ffffffff811e809c-ffffffff811e80c0: event_hist_trigger_func.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
int event_hist_trigger_func(struct event_command *cmd_ops, struct trace_event_file *file, char *glob, char *cmd, char *param);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/trace/trace_events_hist.c (0)
Location: kernel/trace/trace_events_hist.c:5621
Inline: False
Direct callers:
  - kernel/trace/trace_events_hist.c:event_hist_trigger_free
  - kernel/trace/trace_events_hist.c:create_field_var_hist
```
**Symbols:**

```
ffffffff811e42f0-ffffffff811e4b29: event_hist_trigger_func (STB_LOCAL)
ffffffff81be6364-ffffffff81be6388: event_hist_trigger_func.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
int event_hist_trigger_func(struct event_command *cmd_ops, struct trace_event_file *file, char *glob, char *cmd, char *param);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/trace/trace_events_hist.c (0)
Location: kernel/trace/trace_events_hist.c:5690
Inline: False
Direct callers:
  - kernel/trace/trace_events_hist.c:event_hist_trigger_free
  - kernel/trace/trace_events_hist.c:create_field_var_hist
```
**Symbols:**

```
ffffffff811e58d0-ffffffff811e6109: event_hist_trigger_func (STB_LOCAL)
ffffffff81bd801f-ffffffff81bd8043: event_hist_trigger_func.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int event_hist_trigger_func(struct event_command *cmd_ops, struct trace_event_file *file, char *glob, char *cmd, char *param);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/trace/trace_events_hist.c (0)
Location: kernel/trace/trace_events_hist.c:5796
Inline: False
Direct callers:
  - kernel/trace/trace_events_hist.c:event_hist_trigger_free
  - kernel/trace/trace_events_hist.c:create_field_var_hist
```
**Symbols:**

```
ffffffff812166d0-ffffffff81216f76: event_hist_trigger_func (STB_LOCAL)
ffffffff81cb70f5-ffffffff81cb7158: event_hist_trigger_func.cold (STB_LOCAL)
```
</details>
</li>
<li>
In <code>5.19</code>: Absent ⚠️
</li>
<li>
In <code>6.2</code>: Absent ⚠️
</li>
<li>
In <code>6.5</code>: Absent ⚠️
</li>
<li>
In <code>6.8</code>: Absent ⚠️
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: ✅</summary>

```c
int event_hist_trigger_func(struct event_command *cmd_ops, struct trace_event_file *file, char *glob, char *cmd, char *param);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_events_hist.c (ffff800010249f70)
Location: kernel/trace/trace_events_hist.c:6199
Inline: False
Direct callers:
  - kernel/trace/trace_events_hist.c:event_hist_trigger_free
  - kernel/trace/trace_events_hist.c:create_field_var_hist
```
**Symbols:**

```
ffff800010249f70-ffff80001024a7d8: event_hist_trigger_func (STB_LOCAL)
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
int event_hist_trigger_func(struct event_command *cmd_ops, struct trace_event_file *file, char *glob, char *cmd, char *param);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_events_hist.c (c0000000002e4d60)
Location: kernel/trace/trace_events_hist.c:6199
Inline: False
Direct callers:
  - kernel/trace/trace_events_hist.c:event_hist_trigger_free
  - kernel/trace/trace_events_hist.c:create_field_var_hist
```
**Symbols:**

```
c0000000002e4d60-c0000000002e58c8: event_hist_trigger_func (STB_LOCAL)
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
int event_hist_trigger_func(struct event_command *cmd_ops, struct trace_event_file *file, char *glob, char *cmd, char *param);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_events_hist.c (ffffffff811c3120)
Location: kernel/trace/trace_events_hist.c:6199
Inline: False
Direct callers:
  - kernel/trace/trace_events_hist.c:event_hist_trigger_free
  - kernel/trace/trace_events_hist.c:create_field_var_hist
```
**Symbols:**

```
ffffffff811c3120-ffffffff811c39f0: event_hist_trigger_func (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int event_hist_trigger_func(struct event_command *cmd_ops, struct trace_event_file *file, char *glob, char *cmd, char *param);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_events_hist.c (ffffffff811b5f00)
Location: kernel/trace/trace_events_hist.c:6199
Inline: False
Direct callers:
  - kernel/trace/trace_events_hist.c:event_hist_trigger_free
  - kernel/trace/trace_events_hist.c:create_field_var_hist
```
**Symbols:**

```
ffffffff811b5f00-ffffffff811b67d0: event_hist_trigger_func (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int event_hist_trigger_func(struct event_command *cmd_ops, struct trace_event_file *file, char *glob, char *cmd, char *param);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_events_hist.c (ffffffff811c0ef0)
Location: kernel/trace/trace_events_hist.c:6199
Inline: False
Direct callers:
  - kernel/trace/trace_events_hist.c:event_hist_trigger_free
  - kernel/trace/trace_events_hist.c:create_field_var_hist
```
**Symbols:**

```
ffffffff811c0ef0-ffffffff811c17c0: event_hist_trigger_func (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int event_hist_trigger_func(struct event_command *cmd_ops, struct trace_event_file *file, char *glob, char *cmd, char *param);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_events_hist.c (ffffffff811cef90)
Location: kernel/trace/trace_events_hist.c:6199
Inline: False
Direct callers:
  - kernel/trace/trace_events_hist.c:event_hist_trigger_free
  - kernel/trace/trace_events_hist.c:create_field_var_hist
```
**Symbols:**

```
ffffffff811cef90-ffffffff811cf860: event_hist_trigger_func (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
