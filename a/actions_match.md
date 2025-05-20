# Function: <code>actions_match</code>

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
In kernel/trace/trace_events_hist.c (ffffffff8119e891)
Location: kernel/trace/trace_events_hist.c:4369
Inline: True
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
In kernel/trace/trace_events_hist.c (ffffffff811ad4f1)
Location: kernel/trace/trace_events_hist.c:4455
Inline: True
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
In kernel/trace/trace_events_hist.c (ffffffff811bb725)
Location: kernel/trace/trace_events_hist.c:4959
Inline: True
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
In kernel/trace/trace_events_hist.c (ffffffff811c6f75)
Location: kernel/trace/trace_events_hist.c:5069
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
bool actions_match(struct hist_trigger_data *hist_data, struct hist_trigger_data *hist_data_test);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_events_hist.c (ffffffff811e0ff0)
Location: kernel/trace/trace_events_hist.c:4177
Inline: False
```
**Symbols:**

```
ffffffff811e0ff0-ffffffff811e1142: actions_match (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
bool actions_match(struct hist_trigger_data *hist_data, struct hist_trigger_data *hist_data_test);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_events_hist.c (ffffffff811de9b0)
Location: kernel/trace/trace_events_hist.c:4202
Inline: False
```
**Symbols:**

```
ffffffff811de9b0-ffffffff811deb02: actions_match (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
bool actions_match(struct hist_trigger_data *hist_data, struct hist_trigger_data *hist_data_test);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_events_hist.c (ffffffff811dfe50)
Location: kernel/trace/trace_events_hist.c:4270
Inline: False
```
**Symbols:**

```
ffffffff811dfe50-ffffffff811dffa2: actions_match (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
bool actions_match(struct hist_trigger_data *hist_data, struct hist_trigger_data *hist_data_test);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/trace/trace_events_hist.c (0)
Location: kernel/trace/trace_events_hist.c:4365
Inline: False
```
**Symbols:**

```
ffffffff81210250-ffffffff81210459: actions_match (STB_LOCAL)
ffffffff81cb6ec7-ffffffff81cb6ef9: actions_match.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
bool actions_match(struct hist_trigger_data *hist_data, struct hist_trigger_data *hist_data_test);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/trace/trace_events_hist.c (0)
Location: kernel/trace/trace_events_hist.c:4744
Inline: False
Direct callers:
  - kernel/trace/trace_events_hist.c:hist_trigger_match
```
**Symbols:**

```
ffffffff8124cf10-ffffffff8124d125: actions_match (STB_LOCAL)
ffffffff81e67f64-ffffffff81e67f96: actions_match.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
bool actions_match(struct hist_trigger_data *hist_data, struct hist_trigger_data *hist_data_test);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/trace/trace_events_hist.c (0)
Location: kernel/trace/trace_events_hist.c:4875
Inline: False
Direct callers:
  - kernel/trace/trace_events_hist.c:hist_trigger_match
```
**Symbols:**

```
ffffffff8129b0d0-ffffffff8129b2e5: actions_match (STB_LOCAL)
ffffffff8205e8e8-ffffffff8205e91a: actions_match.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
bool actions_match(struct hist_trigger_data *hist_data, struct hist_trigger_data *hist_data_test);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/trace/trace_events_hist.c (0)
Location: kernel/trace/trace_events_hist.c:4952
Inline: False
Direct callers:
  - kernel/trace/trace_events_hist.c:hist_trigger_match
```
**Symbols:**

```
ffffffff812b8840-ffffffff812b8a55: actions_match (STB_LOCAL)
ffffffff820dd42c-ffffffff820dd45e: actions_match.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
bool actions_match(struct hist_trigger_data *hist_data, struct hist_trigger_data *hist_data_test);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/trace/trace_events_hist.c (0)
Location: kernel/trace/trace_events_hist.c:4944
Inline: False
Direct callers:
  - kernel/trace/trace_events_hist.c:hist_trigger_match
```
**Symbols:**

```
ffffffff812d4e90-ffffffff812d50a5: actions_match (STB_LOCAL)
ffffffff821b9230-ffffffff821b9262: actions_match.cold (STB_LOCAL)
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
In kernel/trace/trace_events_hist.c (ffff800010247264)
Location: kernel/trace/trace_events_hist.c:5069
Inline: True
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
In kernel/trace/trace_events_hist.c (c0000000002dc3f0)
Location: kernel/trace/trace_events_hist.c:5069
Inline: True
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
In kernel/trace/trace_events_hist.c (ffffffff811bf595)
Location: kernel/trace/trace_events_hist.c:5069
Inline: True
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
In kernel/trace/trace_events_hist.c (ffffffff811b2375)
Location: kernel/trace/trace_events_hist.c:5069
Inline: True
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
In kernel/trace/trace_events_hist.c (ffffffff811bd365)
Location: kernel/trace/trace_events_hist.c:5069
Inline: True
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
In kernel/trace/trace_events_hist.c (ffffffff811cb405)
Location: kernel/trace/trace_events_hist.c:5069
Inline: True
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
