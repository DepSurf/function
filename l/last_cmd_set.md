# Function: <code>last_cmd_set</code>

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
<summary>In <code>4.18</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_events_hist.c (ffffffff811a1d7c)
Location: kernel/trace/trace_events_hist.c:359
Inline: True
Inline callers:
  - kernel/trace/trace_events_hist.c:event_hist_trigger_func
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
In kernel/trace/trace_events_hist.c (ffffffff811b1202)
Location: kernel/trace/trace_events_hist.c:425
Inline: True
Inline callers:
  - kernel/trace/trace_events_hist.c:event_hist_trigger_func
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
In kernel/trace/trace_events_hist.c (ffffffff811bf514)
Location: kernel/trace/trace_events_hist.c:597
Inline: True
Inline callers:
  - kernel/trace/trace_events_hist.c:event_hist_trigger_func
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
In kernel/trace/trace_events_hist.c (ffffffff811cad64)
Location: kernel/trace/trace_events_hist.c:604
Inline: True
Inline callers:
  - kernel/trace/trace_events_hist.c:event_hist_trigger_func
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
In kernel/trace/trace_events_hist.c (ffffffff811e6b9e)
Location: kernel/trace/trace_events_hist.c:543
Inline: True
Inline callers:
  - kernel/trace/trace_events_hist.c:event_hist_trigger_func
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Collision, Full Inline ⚠️</summary>

**Collision:** Static-Static Collision

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_events_synth.c (ffffffff811dcd7b)
Location: kernel/trace/trace_events_synth.c:51
Inline: True
Inline callers:
  - kernel/trace/trace_events_synth.c:save_cmdstr
```
```
In kernel/trace/trace_events_hist.c (ffffffff811e455e)
Location: kernel/trace/trace_events_hist.c:546
Inline: True
Inline callers:
  - kernel/trace/trace_events_hist.c:event_hist_trigger_func
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Collision, Full Inline ⚠️</summary>

**Collision:** Static-Static Collision

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_events_synth.c (ffffffff811decc5)
Location: kernel/trace/trace_events_synth.c:52
Inline: True
Inline callers:
  - kernel/trace/trace_events_synth.c:create_synth_event
  - kernel/trace/trace_events_synth.c:create_synth_event
  - kernel/trace/trace_events_synth.c:create_or_delete_synth_event
  - kernel/trace/trace_events_synth.c:create_or_delete_synth_event
```
```
In kernel/trace/trace_events_hist.c (ffffffff811e5b3e)
Location: kernel/trace/trace_events_hist.c:559
Inline: True
Inline callers:
  - kernel/trace/trace_events_hist.c:event_hist_trigger_func
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Collision, Full Inline ⚠️</summary>

**Collision:** Static-Static Collision

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_events_synth.c (ffffffff8120e5a6)
Location: kernel/trace/trace_events_synth.c:52
Inline: True
Inline callers:
  - kernel/trace/trace_events_synth.c:create_synth_event
  - kernel/trace/trace_events_synth.c:create_synth_event
  - kernel/trace/trace_events_synth.c:create_or_delete_synth_event
  - kernel/trace/trace_events_synth.c:create_or_delete_synth_event
```
```
In kernel/trace/trace_events_hist.c (ffffffff812169b5)
Location: kernel/trace/trace_events_hist.c:583
Inline: True
Inline callers:
  - kernel/trace/trace_events_hist.c:event_hist_trigger_func
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Collision, Selective Inline ⚠️</summary>

```c
void last_cmd_set(const char *str);
```

**Collision:** Static-Static Collision

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_events_synth.c (ffffffff8124ab46)
Location: kernel/trace/trace_events_synth.c:55
Inline: True
Inline callers:
  - kernel/trace/trace_events_synth.c:create_synth_event
  - kernel/trace/trace_events_synth.c:create_synth_event
  - kernel/trace/trace_events_synth.c:create_or_delete_synth_event
  - kernel/trace/trace_events_synth.c:create_or_delete_synth_event
```
```
In kernel/trace/trace_events_hist.c (ffffffff8124f010)
Location: kernel/trace/trace_events_hist.c:743
Inline: False
Direct callers:
  - kernel/trace/trace_events_hist.c:event_hist_trigger_parse
```
**Symbols:**

```
ffffffff8124f010-ffffffff8124f0ec: last_cmd_set (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Collision, Selective Inline ⚠️</summary>

```c
void last_cmd_set(const char *str);
```

**Collision:** Static-Static Collision

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_events_synth.c (ffffffff81299736)
Location: kernel/trace/trace_events_synth.c:57
Inline: True
Inline callers:
  - kernel/trace/trace_events_synth.c:create_synth_event
  - kernel/trace/trace_events_synth.c:create_synth_event
  - kernel/trace/trace_events_synth.c:create_or_delete_synth_event
  - kernel/trace/trace_events_synth.c:create_or_delete_synth_event
```
```
In kernel/trace/trace_events_hist.c (ffffffff8129e180)
Location: kernel/trace/trace_events_hist.c:776
Inline: False
Direct callers:
  - kernel/trace/trace_events_hist.c:event_hist_trigger_parse
```
**Symbols:**

```
ffffffff8129e180-ffffffff8129e25c: last_cmd_set (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Collision, Selective Inline ⚠️</summary>

```c
void last_cmd_set(const char *str);
```

**Collision:** Static-Static Collision

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_events_synth.c (ffffffff812b6ae6)
Location: kernel/trace/trace_events_synth.c:64
Inline: True
Inline callers:
  - kernel/trace/trace_events_synth.c:create_synth_event
  - kernel/trace/trace_events_synth.c:create_synth_event
  - kernel/trace/trace_events_synth.c:create_or_delete_synth_event
  - kernel/trace/trace_events_synth.c:create_or_delete_synth_event
```
```
In kernel/trace/trace_events_hist.c (ffffffff812bbd30)
Location: kernel/trace/trace_events_hist.c:773
Inline: False
Direct callers:
  - kernel/trace/trace_events_hist.c:event_hist_trigger_parse
```
**Symbols:**

```
ffffffff812bbd30-ffffffff812bbed4: last_cmd_set (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Collision, Full Inline ⚠️</summary>

**Collision:** Static-Static Collision

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_events_synth.c (ffffffff812d3136)
Location: kernel/trace/trace_events_synth.c:64
Inline: True
Inline callers:
  - kernel/trace/trace_events_synth.c:create_synth_event
  - kernel/trace/trace_events_synth.c:create_synth_event
  - kernel/trace/trace_events_synth.c:create_or_delete_synth_event
  - kernel/trace/trace_events_synth.c:create_or_delete_synth_event
```
```
In kernel/trace/trace_events_hist.c (ffffffff812de64b)
Location: kernel/trace/trace_events_hist.c:773
Inline: True
Inline callers:
  - kernel/trace/trace_events_hist.c:event_hist_trigger_parse
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
In kernel/trace/trace_events_hist.c (ffff80001024a1b8)
Location: kernel/trace/trace_events_hist.c:604
Inline: True
Inline callers:
  - kernel/trace/trace_events_hist.c:event_hist_trigger_func
```
</details>
</li>
<li>
In <code>armhf</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_events_hist.c (c0000000002e5080)
Location: kernel/trace/trace_events_hist.c:604
Inline: True
Inline callers:
  - kernel/trace/trace_events_hist.c:event_hist_trigger_func
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
<summary>In <code>aws</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_events_hist.c (ffffffff811c3384)
Location: kernel/trace/trace_events_hist.c:604
Inline: True
Inline callers:
  - kernel/trace/trace_events_hist.c:event_hist_trigger_func
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
In kernel/trace/trace_events_hist.c (ffffffff811b6164)
Location: kernel/trace/trace_events_hist.c:604
Inline: True
Inline callers:
  - kernel/trace/trace_events_hist.c:event_hist_trigger_func
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
In kernel/trace/trace_events_hist.c (ffffffff811c1154)
Location: kernel/trace/trace_events_hist.c:604
Inline: True
Inline callers:
  - kernel/trace/trace_events_hist.c:event_hist_trigger_func
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
In kernel/trace/trace_events_hist.c (ffffffff811cf1f4)
Location: kernel/trace/trace_events_hist.c:604
Inline: True
Inline callers:
  - kernel/trace/trace_events_hist.c:event_hist_trigger_func
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>5.19</code> and <code>6.2</code> ✅
</li>
<li>
No changes between <code>6.2</code> and <code>6.5</code> ✅
</li>
</ul>
