# Function: <code>free_event_filter</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void free_event_filter(struct event_filter *filter);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_events_filter.c (ffffffff81164e90)
Location: kernel/trace/trace_events_filter.c:847
Inline: False
Direct callers:
  - kernel/trace/trace_events.c:remove_event_file_dir
  - kernel/trace/trace_events.c:trace_module_notify
  - kernel/trace/trace_events.c:trace_remove_event_call
  - kernel/trace/trace_events_trigger.c:set_trigger_filter
  - kernel/trace/trace_events_trigger.c:set_trigger_filter
```
**Symbols:**

```
ffffffff81164e90-ffffffff81164e9b: free_event_filter (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void free_event_filter(struct event_filter *filter);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_events_filter.c (ffffffff8116f6a0)
Location: kernel/trace/trace_events_filter.c:844
Inline: False
Direct callers:
  - kernel/trace/trace_events.c:trace_module_notify
  - kernel/trace/trace_events.c:trace_remove_event_call
  - kernel/trace/trace_events.c:remove_event_file_dir
  - kernel/trace/trace_events_trigger.c:set_trigger_filter
  - kernel/trace/trace_events_trigger.c:set_trigger_filter
```
**Symbols:**

```
ffffffff8116f6a0-ffffffff8116f6ab: free_event_filter (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void free_event_filter(struct event_filter *filter);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_events_filter.c (ffffffff8117ae10)
Location: kernel/trace/trace_events_filter.c:875
Inline: False
Direct callers:
  - kernel/trace/trace_events.c:trace_module_notify
  - kernel/trace/trace_events.c:trace_remove_event_call
  - kernel/trace/trace_events.c:remove_event_file_dir
  - kernel/trace/trace_events_trigger.c:set_trigger_filter
  - kernel/trace/trace_events_trigger.c:set_trigger_filter
```
**Symbols:**

```
ffffffff8117ae10-ffffffff8117ae1b: free_event_filter (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
void free_event_filter(struct event_filter *filter);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_events_filter.c (ffffffff8117d983)
Location: kernel/trace/trace_events_filter.c:875
Inline: True
Inline callers:
  - kernel/trace/trace_events_filter.c:create_filter
Direct callers:
  - kernel/trace/trace_events.c:trace_module_notify
  - kernel/trace/trace_events.c:trace_remove_event_call
  - kernel/trace/trace_events.c:remove_event_file_dir
  - kernel/trace/trace_events_trigger.c:set_trigger_filter
  - kernel/trace/trace_events_trigger.c:set_trigger_filter
```
**Symbols:**

```
ffffffff8117dab0-ffffffff8117dac2: free_event_filter (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
void free_event_filter(struct event_filter *filter);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_events_filter.c (ffffffff8118b213)
Location: kernel/trace/trace_events_filter.c:874
Inline: True
Inline callers:
  - kernel/trace/trace_events_filter.c:create_filter
Direct callers:
  - kernel/trace/trace_events.c:trace_module_notify
  - kernel/trace/trace_events.c:trace_remove_event_call
  - kernel/trace/trace_events.c:remove_event_file_dir
  - kernel/trace/trace_events_trigger.c:set_trigger_filter
  - kernel/trace/trace_events_trigger.c:set_trigger_filter
```
**Symbols:**

```
ffffffff8118b340-ffffffff8118b352: free_event_filter (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void free_event_filter(struct event_filter *filter);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_events_filter.c (ffffffff81199c80)
Location: kernel/trace/trace_events_filter.c:1029
Inline: False
Direct callers:
  - kernel/trace/trace_events.c:trace_module_notify
  - kernel/trace/trace_events.c:trace_remove_event_call
  - kernel/trace/trace_events.c:remove_event_file_dir
  - kernel/trace/trace_events_trigger.c:set_trigger_filter
  - kernel/trace/trace_events_trigger.c:set_trigger_filter
```
**Symbols:**

```
ffffffff81199c80-ffffffff81199c91: free_event_filter (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void free_event_filter(struct event_filter *filter);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_events_filter.c (ffffffff811a7e20)
Location: kernel/trace/trace_events_filter.c:1019
Inline: False
Direct callers:
  - kernel/trace/trace_events.c:trace_module_notify
  - kernel/trace/trace_events.c:trace_remove_event_call
  - kernel/trace/trace_events.c:remove_event_file_dir
  - kernel/trace/trace_events_trigger.c:set_trigger_filter
  - kernel/trace/trace_events_trigger.c:set_trigger_filter
```
**Symbols:**

```
ffffffff811a7e20-ffffffff811a7e31: free_event_filter (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void free_event_filter(struct event_filter *filter);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_events_filter.c (ffffffff811b5cf0)
Location: kernel/trace/trace_events_filter.c:1038
Inline: False
Direct callers:
  - kernel/trace/trace_events.c:trace_module_notify
  - kernel/trace/trace_events.c:trace_remove_event_call
  - kernel/trace/trace_events.c:remove_event_file_dir
  - kernel/trace/trace_events_trigger.c:set_trigger_filter
  - kernel/trace/trace_events_trigger.c:set_trigger_filter
```
**Symbols:**

```
ffffffff811b5cf0-ffffffff811b5d01: free_event_filter (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void free_event_filter(struct event_filter *filter);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_events_filter.c (ffffffff811c1380)
Location: kernel/trace/trace_events_filter.c:1040
Inline: False
Direct callers:
  - kernel/trace/trace_events.c:trace_module_notify
  - kernel/trace/trace_events.c:trace_remove_event_call
  - kernel/trace/trace_events.c:remove_event_file_dir
  - kernel/trace/trace_events_trigger.c:set_trigger_filter
  - kernel/trace/trace_events_trigger.c:set_trigger_filter
```
**Symbols:**

```
ffffffff811c1380-ffffffff811c1391: free_event_filter (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void free_event_filter(struct event_filter *filter);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_events_filter.c (ffffffff811db2c0)
Location: kernel/trace/trace_events_filter.c:1040
Inline: False
Direct callers:
  - kernel/trace/trace_events.c:trace_module_notify
  - kernel/trace/trace_events.c:trace_remove_event_call
  - kernel/trace/trace_events.c:remove_event_file_dir
  - kernel/trace/trace_events_trigger.c:set_trigger_filter
  - kernel/trace/trace_events_trigger.c:set_trigger_filter
```
**Symbols:**

```
ffffffff811db2c0-ffffffff811db2d1: free_event_filter (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void free_event_filter(struct event_filter *filter);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_events_filter.c (ffffffff811d83f0)
Location: kernel/trace/trace_events_filter.c:1040
Inline: False
Direct callers:
  - kernel/trace/trace_events.c:trace_module_notify
  - kernel/trace/trace_events.c:trace_remove_event_call
  - kernel/trace/trace_events.c:remove_event_file_dir
  - kernel/trace/trace_events_trigger.c:set_trigger_filter
  - kernel/trace/trace_events_trigger.c:set_trigger_filter
```
**Symbols:**

```
ffffffff811d83f0-ffffffff811d8401: free_event_filter (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void free_event_filter(struct event_filter *filter);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_events_filter.c (ffffffff811d9890)
Location: kernel/trace/trace_events_filter.c:1040
Inline: False
Direct callers:
  - kernel/trace/trace_events.c:trace_module_notify
  - kernel/trace/trace_events.c:trace_remove_event_call
  - kernel/trace/trace_events.c:remove_event_file_dir
  - kernel/trace/trace_events_trigger.c:set_trigger_filter
  - kernel/trace/trace_events_trigger.c:set_trigger_filter
```
**Symbols:**

```
ffffffff811d9890-ffffffff811d98a1: free_event_filter (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void free_event_filter(struct event_filter *filter);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_events_filter.c (ffffffff81206ba0)
Location: kernel/trace/trace_events_filter.c:1111
Inline: False
Direct callers:
  - kernel/trace/trace_events.c:trace_module_notify
  - kernel/trace/trace_events.c:trace_remove_event_call
  - kernel/trace/trace_events.c:remove_event_file_dir
  - kernel/trace/trace_events_trigger.c:set_trigger_filter
  - kernel/trace/trace_events_trigger.c:set_trigger_filter
```
**Symbols:**

```
ffffffff81206ba0-ffffffff81206bb1: free_event_filter (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void free_event_filter(struct event_filter *filter);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_events_filter.c (ffffffff81242430)
Location: kernel/trace/trace_events_filter.c:1134
Inline: False
Direct callers:
  - kernel/trace/trace_events.c:trace_module_notify
  - kernel/trace/trace_events.c:trace_remove_event_call
  - kernel/trace/trace_events.c:remove_event_file_dir
  - kernel/trace/trace_events_trigger.c:set_trigger_filter
  - kernel/trace/trace_events_trigger.c:set_trigger_filter
```
**Symbols:**

```
ffffffff81242430-ffffffff8124244d: free_event_filter (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void free_event_filter(struct event_filter *filter);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_events_filter.c (ffffffff8128fe20)
Location: kernel/trace/trace_events_filter.c:1182
Inline: False
Direct callers:
  - kernel/trace/trace_events.c:trace_module_notify
  - kernel/trace/trace_events.c:trace_remove_event_call
  - kernel/trace/trace_events.c:remove_event_file_dir
  - kernel/trace/trace_events_trigger.c:set_trigger_filter
  - kernel/trace/trace_events_trigger.c:set_trigger_filter
  - kernel/trace/trace_eprobe.c:trace_eprobe_parse_filter
  - kernel/trace/trace_eprobe.c:enable_trace_eprobe
  - kernel/trace/trace_eprobe.c:enable_trace_eprobe
```
**Symbols:**

```
ffffffff8128fe20-ffffffff8128fe3d: free_event_filter (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void free_event_filter(struct event_filter *filter);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_events_filter.c (ffffffff812acfe0)
Location: kernel/trace/trace_events_filter.c:1196
Inline: False
Direct callers:
  - kernel/trace/trace_events.c:trace_module_notify
  - kernel/trace/trace_events.c:trace_remove_event_call
  - kernel/trace/trace_events.c:remove_event_file_dir
  - kernel/trace/trace_events_trigger.c:set_trigger_filter
  - kernel/trace/trace_events_trigger.c:set_trigger_filter
  - kernel/trace/trace_eprobe.c:trace_eprobe_parse_filter
  - kernel/trace/trace_eprobe.c:enable_trace_eprobe
```
**Symbols:**

```
ffffffff812acfe0-ffffffff812acffd: free_event_filter (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void free_event_filter(struct event_filter *filter);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_events_filter.c (ffffffff812c94d0)
Location: kernel/trace/trace_events_filter.c:1315
Inline: False
Direct callers:
  - kernel/trace/trace_events.c:trace_module_notify
  - kernel/trace/trace_events.c:trace_remove_event_call
  - kernel/trace/trace_events.c:remove_event_file_dir
  - kernel/trace/trace_events_trigger.c:set_trigger_filter
  - kernel/trace/trace_events_trigger.c:set_trigger_filter
  - kernel/trace/trace_eprobe.c:trace_eprobe_parse_filter
  - kernel/trace/trace_eprobe.c:enable_trace_eprobe
```
**Symbols:**

```
ffffffff812c94d0-ffffffff812c94ed: free_event_filter (STB_GLOBAL)
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
void free_event_filter(struct event_filter *filter);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_events_filter.c (ffff800010240a78)
Location: kernel/trace/trace_events_filter.c:1040
Inline: False
Direct callers:
  - kernel/trace/trace_events.c:trace_module_notify
  - kernel/trace/trace_events.c:trace_remove_event_call
  - kernel/trace/trace_events.c:remove_event_file_dir
  - kernel/trace/trace_events_trigger.c:set_trigger_filter
  - kernel/trace/trace_events_trigger.c:set_trigger_filter
```
**Symbols:**

```
ffff800010240a78-ffff800010240a94: free_event_filter (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void free_event_filter(struct event_filter *filter);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_events_filter.c (c047c48c)
Location: kernel/trace/trace_events_filter.c:1040
Inline: False
Direct callers:
  - kernel/trace/trace_events.c:trace_module_notify
  - kernel/trace/trace_events.c:trace_remove_event_call
  - kernel/trace/trace_events.c:remove_event_file_dir
  - kernel/trace/trace_events_trigger.c:set_trigger_filter
  - kernel/trace/trace_events_trigger.c:set_trigger_filter
```
**Symbols:**

```
c047c48c-c047c4a8: free_event_filter (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void free_event_filter(struct event_filter *filter);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_events_filter.c (c0000000002d17e0)
Location: kernel/trace/trace_events_filter.c:1040
Inline: False
Direct callers:
  - kernel/trace/trace_events.c:trace_module_notify
  - kernel/trace/trace_events.c:trace_remove_event_call
  - kernel/trace/trace_events.c:remove_event_file_dir
  - kernel/trace/trace_events.c:remove_event_file_dir
  - kernel/trace/trace_events_trigger.c:set_trigger_filter
  - kernel/trace/trace_events_trigger.c:set_trigger_filter
```
**Symbols:**

```
c0000000002d17e0-c0000000002d17f4: free_event_filter (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void free_event_filter(struct event_filter *filter);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_events_filter.c (ffffffe000195c24)
Location: kernel/trace/trace_events_filter.c:1040
Inline: False
Direct callers:
  - kernel/trace/trace_events.c:trace_module_notify
  - kernel/trace/trace_events.c:trace_remove_event_call
  - kernel/trace/trace_events.c:remove_event_file_dir
  - kernel/trace/trace_events_trigger.c:set_trigger_filter
  - kernel/trace/trace_events_trigger.c:set_trigger_filter
```
**Symbols:**

```
ffffffe000195c24-ffffffe000195c40: free_event_filter (STB_GLOBAL)
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
void free_event_filter(struct event_filter *filter);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_events_filter.c (ffffffff811b99a0)
Location: kernel/trace/trace_events_filter.c:1040
Inline: False
Direct callers:
  - kernel/trace/trace_events.c:trace_module_notify
  - kernel/trace/trace_events.c:trace_remove_event_call
  - kernel/trace/trace_events.c:remove_event_file_dir
  - kernel/trace/trace_events_trigger.c:set_trigger_filter
  - kernel/trace/trace_events_trigger.c:set_trigger_filter
```
**Symbols:**

```
ffffffff811b99a0-ffffffff811b99b1: free_event_filter (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void free_event_filter(struct event_filter *filter);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_events_filter.c (ffffffff811ac780)
Location: kernel/trace/trace_events_filter.c:1040
Inline: False
Direct callers:
  - kernel/trace/trace_events.c:trace_module_notify
  - kernel/trace/trace_events.c:trace_remove_event_call
  - kernel/trace/trace_events.c:remove_event_file_dir
  - kernel/trace/trace_events_trigger.c:set_trigger_filter
  - kernel/trace/trace_events_trigger.c:set_trigger_filter
```
**Symbols:**

```
ffffffff811ac780-ffffffff811ac791: free_event_filter (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void free_event_filter(struct event_filter *filter);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_events_filter.c (ffffffff811b7770)
Location: kernel/trace/trace_events_filter.c:1040
Inline: False
Direct callers:
  - kernel/trace/trace_events.c:trace_module_notify
  - kernel/trace/trace_events.c:trace_remove_event_call
  - kernel/trace/trace_events.c:remove_event_file_dir
  - kernel/trace/trace_events_trigger.c:set_trigger_filter
  - kernel/trace/trace_events_trigger.c:set_trigger_filter
```
**Symbols:**

```
ffffffff811b7770-ffffffff811b7781: free_event_filter (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void free_event_filter(struct event_filter *filter);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_events_filter.c (ffffffff811c5810)
Location: kernel/trace/trace_events_filter.c:1040
Inline: False
Direct callers:
  - kernel/trace/trace_events.c:trace_module_notify
  - kernel/trace/trace_events.c:trace_remove_event_call
  - kernel/trace/trace_events.c:remove_event_file_dir
  - kernel/trace/trace_events_trigger.c:set_trigger_filter
  - kernel/trace/trace_events_trigger.c:set_trigger_filter
```
**Symbols:**

```
ffffffff811c5810-ffffffff811c5821: free_event_filter (STB_GLOBAL)
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
