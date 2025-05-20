# Function: <code>find_synth_event</code>

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
struct synth_event *find_synth_event(const char *name);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_events_hist.c (ffffffff8119cb50)
Location: kernel/trace/trace_events_hist.c:860
Inline: False
Direct callers:
  - kernel/trace/trace_events_hist.c:event_hist_trigger_func
  - kernel/trace/trace_events_hist.c:event_hist_trigger_func
  - kernel/trace/trace_events_hist.c:create_synth_event
  - kernel/trace/trace_events_hist.c:create_synth_event
```
**Symbols:**

```
ffffffff8119cb50-ffffffff8119cb9a: find_synth_event (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
struct synth_event *find_synth_event(const char *name);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_events_hist.c (ffffffff811aaf30)
Location: kernel/trace/trace_events_hist.c:946
Inline: False
Direct callers:
  - kernel/trace/trace_events_hist.c:event_hist_trigger_func
  - kernel/trace/trace_events_hist.c:event_hist_trigger_func
  - kernel/trace/trace_events_hist.c:create_or_delete_synth_event
  - kernel/trace/trace_events_hist.c:__create_synth_event
```
**Symbols:**

```
ffffffff811aaf30-ffffffff811aaf84: find_synth_event (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
struct synth_event *find_synth_event(const char *name);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_events_hist.c (ffffffff811b8fb0)
Location: kernel/trace/trace_events_hist.c:1100
Inline: False
Direct callers:
  - kernel/trace/trace_events_hist.c:event_hist_trigger_func
  - kernel/trace/trace_events_hist.c:event_hist_trigger_func
  - kernel/trace/trace_events_hist.c:trace_action_create
  - kernel/trace/trace_events_hist.c:create_or_delete_synth_event
  - kernel/trace/trace_events_hist.c:__create_synth_event
```
**Symbols:**

```
ffffffff811b8fb0-ffffffff811b9008: find_synth_event (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
struct synth_event *find_synth_event(const char *name);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_events_hist.c (ffffffff811c4590)
Location: kernel/trace/trace_events_hist.c:1170
Inline: False
Direct callers:
  - kernel/trace/trace_events_hist.c:event_hist_trigger_func
  - kernel/trace/trace_events_hist.c:event_hist_trigger_func
  - kernel/trace/trace_events_hist.c:trace_action_create
  - kernel/trace/trace_events_hist.c:create_or_delete_synth_event
  - kernel/trace/trace_events_hist.c:__create_synth_event
```
**Symbols:**

```
ffffffff811c4590-ffffffff811c45e8: find_synth_event (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
struct synth_event *find_synth_event(const char *name);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_events_synth.c (ffffffff811dfc93)
Location: kernel/trace/trace_events_synth.c:568
Inline: True
Inline callers:
  - kernel/trace/trace_events_synth.c:__create_synth_event
Direct callers:
  - kernel/trace/trace_events_hist.c:event_hist_trigger_func
  - kernel/trace/trace_events_hist.c:event_hist_trigger_func
  - kernel/trace/trace_events_hist.c:trace_action_create
```
**Symbols:**

```
ffffffff811dff80-ffffffff811dffd8: find_synth_event (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
struct synth_event *find_synth_event(const char *name);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_events_synth.c (ffffffff811dd58b)
Location: kernel/trace/trace_events_synth.c:730
Inline: True
Inline callers:
  - kernel/trace/trace_events_synth.c:__create_synth_event
Direct callers:
  - kernel/trace/trace_events_hist.c:event_hist_trigger_func
  - kernel/trace/trace_events_hist.c:event_hist_trigger_func
  - kernel/trace/trace_events_hist.c:trace_action_create
```
**Symbols:**

```
ffffffff811dd970-ffffffff811dd9c8: find_synth_event (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
struct synth_event *find_synth_event(const char *name);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_events_synth.c (ffffffff811de8ae)
Location: kernel/trace/trace_events_synth.c:748
Inline: True
Inline callers:
  - kernel/trace/trace_events_synth.c:__create_synth_event
Direct callers:
  - kernel/trace/trace_events_hist.c:event_hist_trigger_func
  - kernel/trace/trace_events_hist.c:event_hist_trigger_func
  - kernel/trace/trace_events_hist.c:trace_action_create
```
**Symbols:**

```
ffffffff811deff0-ffffffff811df048: find_synth_event (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
struct synth_event *find_synth_event(const char *name);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_events_synth.c (ffffffff8120e12e)
Location: kernel/trace/trace_events_synth.c:748
Inline: True
Inline callers:
  - kernel/trace/trace_events_synth.c:__create_synth_event
Direct callers:
  - kernel/trace/trace_events_hist.c:event_hist_trigger_func
  - kernel/trace/trace_events_hist.c:event_hist_trigger_func
  - kernel/trace/trace_events_hist.c:trace_action_create
```
**Symbols:**

```
ffffffff8120e8f0-ffffffff8120e948: find_synth_event (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
struct synth_event *find_synth_event(const char *name);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_events_synth.c (ffffffff8124a5f1)
Location: kernel/trace/trace_events_synth.c:756
Inline: True
Inline callers:
  - kernel/trace/trace_events_synth.c:__create_synth_event
Direct callers:
  - kernel/trace/trace_events_hist.c:event_hist_trigger_parse
  - kernel/trace/trace_events_hist.c:event_hist_trigger_parse
  - kernel/trace/trace_events_hist.c:trace_action_create
```
**Symbols:**

```
ffffffff8124af00-ffffffff8124af64: find_synth_event (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
struct synth_event *find_synth_event(const char *name);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_events_synth.c (ffffffff81298a58)
Location: kernel/trace/trace_events_synth.c:767
Inline: True
Inline callers:
  - kernel/trace/trace_events_synth.c:synth_event_delete
  - kernel/trace/trace_events_synth.c:__create_synth_event
Direct callers:
  - kernel/trace/trace_events_hist.c:event_hist_trigger_parse
  - kernel/trace/trace_events_hist.c:event_hist_trigger_parse
  - kernel/trace/trace_events_hist.c:trace_action_create
```
**Symbols:**

```
ffffffff81299b20-ffffffff81299b84: find_synth_event (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
struct synth_event *find_synth_event(const char *name);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_events_synth.c (ffffffff812b58a8)
Location: kernel/trace/trace_events_synth.c:839
Inline: True
Inline callers:
  - kernel/trace/trace_events_synth.c:synth_event_delete
  - kernel/trace/trace_events_synth.c:__create_synth_event
Direct callers:
  - kernel/trace/trace_events_hist.c:event_hist_trigger_parse
  - kernel/trace/trace_events_hist.c:event_hist_trigger_parse
  - kernel/trace/trace_events_hist.c:trace_action_create
```
**Symbols:**

```
ffffffff812b6fd0-ffffffff812b7034: find_synth_event (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
struct synth_event *find_synth_event(const char *name);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_events_synth.c (ffffffff812d1f18)
Location: kernel/trace/trace_events_synth.c:840
Inline: True
Inline callers:
  - kernel/trace/trace_events_synth.c:synth_event_delete
  - kernel/trace/trace_events_synth.c:__create_synth_event
Direct callers:
  - kernel/trace/trace_events_hist.c:event_hist_trigger_parse
  - kernel/trace/trace_events_hist.c:event_hist_trigger_parse
  - kernel/trace/trace_events_hist.c:trace_action_create
```
**Symbols:**

```
ffffffff812d3620-ffffffff812d3684: find_synth_event (STB_GLOBAL)
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
struct synth_event *find_synth_event(const char *name);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_events_hist.c (ffff800010244128)
Location: kernel/trace/trace_events_hist.c:1170
Inline: False
Direct callers:
  - kernel/trace/trace_events_hist.c:event_hist_trigger_func
  - kernel/trace/trace_events_hist.c:event_hist_trigger_func
  - kernel/trace/trace_events_hist.c:trace_action_create
  - kernel/trace/trace_events_hist.c:create_or_delete_synth_event
  - kernel/trace/trace_events_hist.c:__create_synth_event
```
**Symbols:**

```
ffff800010244128-ffff8000102441b4: find_synth_event (STB_LOCAL)
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
struct synth_event *find_synth_event(const char *name);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_events_hist.c (c0000000002d7330)
Location: kernel/trace/trace_events_hist.c:1170
Inline: False
Direct callers:
  - kernel/trace/trace_events_hist.c:event_hist_trigger_func
  - kernel/trace/trace_events_hist.c:event_hist_trigger_func
  - kernel/trace/trace_events_hist.c:trace_action_create
  - kernel/trace/trace_events_hist.c:create_or_delete_synth_event
  - kernel/trace/trace_events_hist.c:__create_synth_event
```
**Symbols:**

```
c0000000002d7330-c0000000002d7570: find_synth_event (STB_LOCAL)
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
struct synth_event *find_synth_event(const char *name);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_events_hist.c (ffffffff811bcbb0)
Location: kernel/trace/trace_events_hist.c:1170
Inline: False
Direct callers:
  - kernel/trace/trace_events_hist.c:event_hist_trigger_func
  - kernel/trace/trace_events_hist.c:event_hist_trigger_func
  - kernel/trace/trace_events_hist.c:trace_action_create
  - kernel/trace/trace_events_hist.c:create_or_delete_synth_event
  - kernel/trace/trace_events_hist.c:__create_synth_event
```
**Symbols:**

```
ffffffff811bcbb0-ffffffff811bcc08: find_synth_event (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
struct synth_event *find_synth_event(const char *name);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_events_hist.c (ffffffff811af990)
Location: kernel/trace/trace_events_hist.c:1170
Inline: False
Direct callers:
  - kernel/trace/trace_events_hist.c:event_hist_trigger_func
  - kernel/trace/trace_events_hist.c:event_hist_trigger_func
  - kernel/trace/trace_events_hist.c:trace_action_create
  - kernel/trace/trace_events_hist.c:create_or_delete_synth_event
  - kernel/trace/trace_events_hist.c:__create_synth_event
```
**Symbols:**

```
ffffffff811af990-ffffffff811af9e8: find_synth_event (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
struct synth_event *find_synth_event(const char *name);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_events_hist.c (ffffffff811ba980)
Location: kernel/trace/trace_events_hist.c:1170
Inline: False
Direct callers:
  - kernel/trace/trace_events_hist.c:event_hist_trigger_func
  - kernel/trace/trace_events_hist.c:event_hist_trigger_func
  - kernel/trace/trace_events_hist.c:trace_action_create
  - kernel/trace/trace_events_hist.c:create_or_delete_synth_event
  - kernel/trace/trace_events_hist.c:__create_synth_event
```
**Symbols:**

```
ffffffff811ba980-ffffffff811ba9d8: find_synth_event (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
struct synth_event *find_synth_event(const char *name);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_events_hist.c (ffffffff811c8a20)
Location: kernel/trace/trace_events_hist.c:1170
Inline: False
Direct callers:
  - kernel/trace/trace_events_hist.c:event_hist_trigger_func
  - kernel/trace/trace_events_hist.c:event_hist_trigger_func
  - kernel/trace/trace_events_hist.c:trace_action_create
  - kernel/trace/trace_events_hist.c:create_or_delete_synth_event
  - kernel/trace/trace_events_hist.c:__create_synth_event
```
**Symbols:**

```
ffffffff811c8a20-ffffffff811c8a78: find_synth_event (STB_LOCAL)
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
