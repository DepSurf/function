# Function: <code>trigger_process_regex</code>

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
In kernel/trace/trace_events_trigger.c (ffffffff81165cca)
Location: kernel/trace/trace_events_trigger.c:204
Inline: True
Inline callers:
  - kernel/trace/trace_events_trigger.c:event_trigger_write
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
In kernel/trace/trace_events_trigger.c (ffffffff8117042c)
Location: kernel/trace/trace_events_trigger.c:222
Inline: True
Inline callers:
  - kernel/trace/trace_events_trigger.c:event_trigger_write
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
In kernel/trace/trace_events_trigger.c (ffffffff8117bb9c)
Location: kernel/trace/trace_events_trigger.c:222
Inline: True
Inline callers:
  - kernel/trace/trace_events_trigger.c:event_trigger_write
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
In kernel/trace/trace_events_trigger.c (ffffffff8117e875)
Location: kernel/trace/trace_events_trigger.c:223
Inline: True
Inline callers:
  - kernel/trace/trace_events_trigger.c:event_trigger_write
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
In kernel/trace/trace_events_trigger.c (ffffffff8118c115)
Location: kernel/trace/trace_events_trigger.c:223
Inline: True
Inline callers:
  - kernel/trace/trace_events_trigger.c:event_trigger_write
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
In kernel/trace/trace_events_trigger.c (ffffffff8119ab8f)
Location: kernel/trace/trace_events_trigger.c:222
Inline: True
Inline callers:
  - kernel/trace/trace_events_trigger.c:event_trigger_write
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
In kernel/trace/trace_events_trigger.c (ffffffff811a8d7f)
Location: kernel/trace/trace_events_trigger.c:211
Inline: True
Inline callers:
  - kernel/trace/trace_events_trigger.c:event_trigger_write
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
In kernel/trace/trace_events_trigger.c (ffffffff811b6cd8)
Location: kernel/trace/trace_events_trigger.c:211
Inline: True
Inline callers:
  - kernel/trace/trace_events_trigger.c:event_trigger_write
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
In kernel/trace/trace_events_trigger.c (ffffffff811c2328)
Location: kernel/trace/trace_events_trigger.c:217
Inline: True
Inline callers:
  - kernel/trace/trace_events_trigger.c:event_trigger_write
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int trigger_process_regex(struct trace_event_file *file, char *buff);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_events_trigger.c (ffffffff811dca20)
Location: kernel/trace/trace_events_trigger.c:217
Inline: False
Direct callers:
  - kernel/trace/trace_events_trigger.c:event_trigger_write
  - kernel/trace/trace_boot.c:trace_boot_init_one_event
```
**Symbols:**

```
ffffffff811dca20-ffffffff811dcb2a: trigger_process_regex (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int trigger_process_regex(struct trace_event_file *file, char *buff);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_events_trigger.c (ffffffff811d9b50)
Location: kernel/trace/trace_events_trigger.c:217
Inline: False
Direct callers:
  - kernel/trace/trace_events_trigger.c:event_trigger_write
  - kernel/trace/trace_boot.c:trace_boot_init_one_event
```
**Symbols:**

```
ffffffff811d9b50-ffffffff811d9c5a: trigger_process_regex (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int trigger_process_regex(struct trace_event_file *file, char *buff);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_events_trigger.c (ffffffff811db0b0)
Location: kernel/trace/trace_events_trigger.c:218
Inline: False
Direct callers:
  - kernel/trace/trace_events_trigger.c:event_trigger_write
  - kernel/trace/trace_boot.c:trace_boot_init_one_event
```
**Symbols:**

```
ffffffff811db0b0-ffffffff811db1ba: trigger_process_regex (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int trigger_process_regex(struct trace_event_file *file, char *buff);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_events_trigger.c (ffffffff812086c0)
Location: kernel/trace/trace_events_trigger.c:230
Inline: False
Direct callers:
  - kernel/trace/trace_events_trigger.c:event_trigger_write
  - kernel/trace/trace_boot.c:trace_boot_init_one_event
  - kernel/trace/trace_boot.c:trace_boot_init_one_event
  - kernel/trace/trace_boot.c:trace_boot_init_one_event
```
**Symbols:**

```
ffffffff812086c0-ffffffff812087ca: trigger_process_regex (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int trigger_process_regex(struct trace_event_file *file, char *buff);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_events_trigger.c (ffffffff81243c90)
Location: kernel/trace/trace_events_trigger.c:244
Inline: False
Direct callers:
  - kernel/trace/trace_events_trigger.c:event_trigger_write
  - kernel/trace/trace_boot.c:trace_boot_init_one_event
  - kernel/trace/trace_boot.c:trace_boot_init_one_event
  - kernel/trace/trace_boot.c:trace_boot_init_one_event
```
**Symbols:**

```
ffffffff81243c90-ffffffff81243daa: trigger_process_regex (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int trigger_process_regex(struct trace_event_file *file, char *buff);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_events_trigger.c (ffffffff812918a0)
Location: kernel/trace/trace_events_trigger.c:245
Inline: False
Direct callers:
  - kernel/trace/trace_events.c:__trace_early_add_events
  - kernel/trace/trace_events_trigger.c:event_trigger_write
  - kernel/trace/trace_boot.c:trace_boot_init_one_event
  - kernel/trace/trace_boot.c:trace_boot_init_one_event
  - kernel/trace/trace_boot.c:trace_boot_init_one_event
```
**Symbols:**

```
ffffffff812918a0-ffffffff812919ba: trigger_process_regex (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int trigger_process_regex(struct trace_event_file *file, char *buff);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_events_trigger.c (ffffffff812aeb00)
Location: kernel/trace/trace_events_trigger.c:247
Inline: False
Direct callers:
  - kernel/trace/trace_events.c:__trace_early_add_events
  - kernel/trace/trace_events_trigger.c:event_trigger_write
  - kernel/trace/trace_boot.c:trace_boot_init_one_event
  - kernel/trace/trace_boot.c:trace_boot_init_one_event
  - kernel/trace/trace_boot.c:trace_boot_init_one_event
```
**Symbols:**

```
ffffffff812aeb00-ffffffff812aec1a: trigger_process_regex (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int trigger_process_regex(struct trace_event_file *file, char *buff);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_events_trigger.c (ffffffff812cb020)
Location: kernel/trace/trace_events_trigger.c:247
Inline: False
Direct callers:
  - kernel/trace/trace_events.c:__trace_early_add_events
  - kernel/trace/trace_events_trigger.c:event_trigger_write
  - kernel/trace/trace_boot.c:trace_boot_init_one_event
  - kernel/trace/trace_boot.c:trace_boot_init_one_event
  - kernel/trace/trace_boot.c:trace_boot_init_one_event
```
**Symbols:**

```
ffffffff812cb020-ffffffff812cb13a: trigger_process_regex (STB_GLOBAL)
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
In kernel/trace/trace_events_trigger.c (ffff800010241aa0)
Location: kernel/trace/trace_events_trigger.c:217
Inline: True
Inline callers:
  - kernel/trace/trace_events_trigger.c:event_trigger_write
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
In kernel/trace/trace_events_trigger.c (c047d3d4)
Location: kernel/trace/trace_events_trigger.c:217
Inline: True
Inline callers:
  - kernel/trace/trace_events_trigger.c:event_trigger_write
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
In kernel/trace/trace_events_trigger.c (c0000000002d3164)
Location: kernel/trace/trace_events_trigger.c:217
Inline: True
Inline callers:
  - kernel/trace/trace_events_trigger.c:event_trigger_write
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
In kernel/trace/trace_events_trigger.c (ffffffe0001969ea)
Location: kernel/trace/trace_events_trigger.c:217
Inline: True
Inline callers:
  - kernel/trace/trace_events_trigger.c:event_trigger_write
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
In kernel/trace/trace_events_trigger.c (ffffffff811ba948)
Location: kernel/trace/trace_events_trigger.c:217
Inline: True
Inline callers:
  - kernel/trace/trace_events_trigger.c:event_trigger_write
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
In kernel/trace/trace_events_trigger.c (ffffffff811ad728)
Location: kernel/trace/trace_events_trigger.c:217
Inline: True
Inline callers:
  - kernel/trace/trace_events_trigger.c:event_trigger_write
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
In kernel/trace/trace_events_trigger.c (ffffffff811b8718)
Location: kernel/trace/trace_events_trigger.c:217
Inline: True
Inline callers:
  - kernel/trace/trace_events_trigger.c:event_trigger_write
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
In kernel/trace/trace_events_trigger.c (ffffffff811c67b8)
Location: kernel/trace/trace_events_trigger.c:217
Inline: True
Inline callers:
  - kernel/trace/trace_events_trigger.c:event_trigger_write
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
