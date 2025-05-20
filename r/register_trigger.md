# Function: <code>register_trigger</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline, Transformation ⚠️</summary>

```c
int register_trigger(char *glob, struct event_trigger_ops *ops, struct event_trigger_data *data, struct trace_event_file *file);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/trace/trace_events_trigger.c (ffffffff81166430)
Location: kernel/trace/trace_events_trigger.c:523
Inline: True
Direct callers:
  - kernel/trace/trace_events_trigger.c:register_snapshot_trigger
```
**Symbols:**

```
ffffffff81166360-ffffffff8116642d: register_trigger.part.9 (STB_LOCAL)
ffffffff81166430-ffffffff81166482: register_trigger (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int register_trigger(char *glob, struct event_trigger_ops *ops, struct event_trigger_data *data, struct trace_event_file *file);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_events_trigger.c (ffffffff811713f0)
Location: kernel/trace/trace_events_trigger.c:536
Inline: False
Direct callers:
  - kernel/trace/trace_events_trigger.c:register_snapshot_trigger
```
**Symbols:**

```
ffffffff811713f0-ffffffff811714fb: register_trigger (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int register_trigger(char *glob, struct event_trigger_ops *ops, struct event_trigger_data *data, struct trace_event_file *file);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_events_trigger.c (ffffffff8117cb60)
Location: kernel/trace/trace_events_trigger.c:536
Inline: False
Direct callers:
  - kernel/trace/trace_events_trigger.c:register_snapshot_trigger
```
**Symbols:**

```
ffffffff8117cb60-ffffffff8117cc6b: register_trigger (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int register_trigger(char *glob, struct event_trigger_ops *ops, struct event_trigger_data *data, struct trace_event_file *file);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_events_trigger.c (ffffffff8117f7b0)
Location: kernel/trace/trace_events_trigger.c:537
Inline: False
Direct callers:
  - kernel/trace/trace_events_trigger.c:register_snapshot_trigger
```
**Symbols:**

```
ffffffff8117f7b0-ffffffff8117f8b2: register_trigger (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int register_trigger(char *glob, struct event_trigger_ops *ops, struct event_trigger_data *data, struct trace_event_file *file);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_events_trigger.c (ffffffff8118d0b0)
Location: kernel/trace/trace_events_trigger.c:537
Inline: False
Direct callers:
  - kernel/trace/trace_events_trigger.c:register_snapshot_trigger
```
**Symbols:**

```
ffffffff8118d0b0-ffffffff8118d1b5: register_trigger (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int register_trigger(char *glob, struct event_trigger_ops *ops, struct event_trigger_data *data, struct trace_event_file *file);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_events_trigger.c (ffffffff8119bbf0)
Location: kernel/trace/trace_events_trigger.c:537
Inline: False
Direct callers:
  - kernel/trace/trace_events_trigger.c:register_snapshot_trigger
```
**Symbols:**

```
ffffffff8119bbf0-ffffffff8119bd01: register_trigger (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int register_trigger(char *glob, struct event_trigger_ops *ops, struct event_trigger_data *data, struct trace_event_file *file);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_events_trigger.c (ffffffff811a9df0)
Location: kernel/trace/trace_events_trigger.c:526
Inline: False
Direct callers:
  - kernel/trace/trace_events_trigger.c:register_snapshot_trigger
```
**Symbols:**

```
ffffffff811a9df0-ffffffff811a9f01: register_trigger (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int register_trigger(char *glob, struct event_trigger_ops *ops, struct event_trigger_data *data, struct trace_event_file *file);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_events_trigger.c (ffffffff811b7d70)
Location: kernel/trace/trace_events_trigger.c:526
Inline: False
Direct callers:
  - kernel/trace/trace_events_trigger.c:register_snapshot_trigger
```
**Symbols:**

```
ffffffff811b7d70-ffffffff811b7e59: register_trigger (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int register_trigger(char *glob, struct event_trigger_ops *ops, struct event_trigger_data *data, struct trace_event_file *file);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_events_trigger.c (ffffffff811c33e0)
Location: kernel/trace/trace_events_trigger.c:535
Inline: False
Direct callers:
  - kernel/trace/trace_events_trigger.c:register_snapshot_trigger
```
**Symbols:**

```
ffffffff811c33e0-ffffffff811c34c9: register_trigger (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int register_trigger(char *glob, struct event_trigger_ops *ops, struct event_trigger_data *data, struct trace_event_file *file);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_events_trigger.c (ffffffff811dcfe0)
Location: kernel/trace/trace_events_trigger.c:541
Inline: False
Direct callers:
  - kernel/trace/trace_events_trigger.c:register_snapshot_trigger
```
**Symbols:**

```
ffffffff811dcfe0-ffffffff811dd0cb: register_trigger (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int register_trigger(char *glob, struct event_trigger_ops *ops, struct event_trigger_data *data, struct trace_event_file *file);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_events_trigger.c (ffffffff811da110)
Location: kernel/trace/trace_events_trigger.c:541
Inline: False
Direct callers:
  - kernel/trace/trace_events_trigger.c:register_snapshot_trigger
```
**Symbols:**

```
ffffffff811da110-ffffffff811da1fb: register_trigger (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int register_trigger(char *glob, struct event_trigger_ops *ops, struct event_trigger_data *data, struct trace_event_file *file);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_events_trigger.c (ffffffff811db670)
Location: kernel/trace/trace_events_trigger.c:542
Inline: False
Direct callers:
  - kernel/trace/trace_events_trigger.c:register_snapshot_trigger
```
**Symbols:**

```
ffffffff811db670-ffffffff811db75b: register_trigger (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int register_trigger(char *glob, struct event_trigger_ops *ops, struct event_trigger_data *data, struct trace_event_file *file);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_events_trigger.c (ffffffff81208c80)
Location: kernel/trace/trace_events_trigger.c:554
Inline: False
Direct callers:
  - kernel/trace/trace_events_trigger.c:register_snapshot_trigger
```
**Symbols:**

```
ffffffff81208c80-ffffffff81208d6b: register_trigger (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int register_trigger(char *glob, struct event_trigger_data *data, struct trace_event_file *file);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_events_trigger.c (ffffffff812442f0)
Location: kernel/trace/trace_events_trigger.c:563
Inline: False
Direct callers:
  - kernel/trace/trace_events_trigger.c:register_snapshot_trigger
```
**Symbols:**

```
ffffffff812442f0-ffffffff812443dd: register_trigger (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int register_trigger(char *glob, struct event_trigger_data *data, struct trace_event_file *file);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_events_trigger.c (ffffffff81291f80)
Location: kernel/trace/trace_events_trigger.c:564
Inline: False
Direct callers:
  - kernel/trace/trace_events_trigger.c:register_snapshot_trigger
```
**Symbols:**

```
ffffffff81291f80-ffffffff8129206d: register_trigger (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int register_trigger(char *glob, struct event_trigger_data *data, struct trace_event_file *file);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_events_trigger.c (ffffffff812af1e0)
Location: kernel/trace/trace_events_trigger.c:566
Inline: False
Direct callers:
  - kernel/trace/trace_events_trigger.c:register_snapshot_trigger
```
**Symbols:**

```
ffffffff812af1e0-ffffffff812af2cd: register_trigger (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int register_trigger(char *glob, struct event_trigger_data *data, struct trace_event_file *file);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_events_trigger.c (ffffffff812cb700)
Location: kernel/trace/trace_events_trigger.c:566
Inline: False
Direct callers:
  - kernel/trace/trace_events_trigger.c:register_snapshot_trigger
```
**Symbols:**

```
ffffffff812cb700-ffffffff812cb7ed: register_trigger (STB_LOCAL)
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
int register_trigger(char *glob, struct event_trigger_ops *ops, struct event_trigger_data *data, struct trace_event_file *file);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_events_trigger.c (ffff800010242dd0)
Location: kernel/trace/trace_events_trigger.c:535
Inline: False
Direct callers:
  - kernel/trace/trace_events_trigger.c:register_snapshot_trigger
```
**Symbols:**

```
ffff800010242dd0-ffff800010242ee4: register_trigger (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int register_trigger(char *glob, struct event_trigger_ops *ops, struct event_trigger_data *data, struct trace_event_file *file);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_events_trigger.c (c047e658)
Location: kernel/trace/trace_events_trigger.c:535
Inline: False
Direct callers:
  - kernel/trace/trace_events_trigger.c:register_snapshot_trigger
```
**Symbols:**

```
c047e658-c047e74c: register_trigger (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int register_trigger(char *glob, struct event_trigger_ops *ops, struct event_trigger_data *data, struct trace_event_file *file);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_events_trigger.c (c0000000002d5680)
Location: kernel/trace/trace_events_trigger.c:535
Inline: False
Direct callers:
  - kernel/trace/trace_events_trigger.c:register_snapshot_trigger
```
**Symbols:**

```
c0000000002d5680-c0000000002d582c: register_trigger (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int register_trigger(char *glob, struct event_trigger_ops *ops, struct event_trigger_data *data, struct trace_event_file *file);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_events_trigger.c (ffffffe000197844)
Location: kernel/trace/trace_events_trigger.c:535
Inline: False
Direct callers:
  - kernel/trace/trace_events_trigger.c:register_snapshot_trigger
```
**Symbols:**

```
ffffffe000197844-ffffffe00019792a: register_trigger (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: ✅</summary>

```c
int register_trigger(char *glob, struct event_trigger_ops *ops, struct event_trigger_data *data, struct trace_event_file *file);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_events_trigger.c (ffffffff811bba00)
Location: kernel/trace/trace_events_trigger.c:535
Inline: False
Direct callers:
  - kernel/trace/trace_events_trigger.c:register_snapshot_trigger
```
**Symbols:**

```
ffffffff811bba00-ffffffff811bbae9: register_trigger (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int register_trigger(char *glob, struct event_trigger_ops *ops, struct event_trigger_data *data, struct trace_event_file *file);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_events_trigger.c (ffffffff811ae7e0)
Location: kernel/trace/trace_events_trigger.c:535
Inline: False
Direct callers:
  - kernel/trace/trace_events_trigger.c:register_snapshot_trigger
```
**Symbols:**

```
ffffffff811ae7e0-ffffffff811ae8c9: register_trigger (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int register_trigger(char *glob, struct event_trigger_ops *ops, struct event_trigger_data *data, struct trace_event_file *file);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_events_trigger.c (ffffffff811b97d0)
Location: kernel/trace/trace_events_trigger.c:535
Inline: False
Direct callers:
  - kernel/trace/trace_events_trigger.c:register_snapshot_trigger
```
**Symbols:**

```
ffffffff811b97d0-ffffffff811b98b9: register_trigger (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int register_trigger(char *glob, struct event_trigger_ops *ops, struct event_trigger_data *data, struct trace_event_file *file);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_events_trigger.c (ffffffff811c7870)
Location: kernel/trace/trace_events_trigger.c:535
Inline: False
Direct callers:
  - kernel/trace/trace_events_trigger.c:register_snapshot_trigger
```
**Symbols:**

```
ffffffff811c7870-ffffffff811c7959: register_trigger (STB_LOCAL)
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
<details>
<summary>Changed between <code>5.15</code> and <code>5.19</code> ⚠️</summary>
<ul>
<li>
<b>Param removed. </b>
<code>struct event_trigger_ops *ops</code>
</li>
<li>
<b>Param reordered. </b>
<code>glob, ops, data, file</code> ➡️ <code>glob, data, file</code>
</li>
</ul>
</details>
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
