# Function: <code>print_action_spec</code>

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
In <code>4.18</code>: Absent ⚠️
</li>
<li>
In <code>5.0</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
void print_action_spec(struct seq_file *m, struct hist_trigger_data *hist_data, struct action_data *data);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_events_hist.c (ffffffff811b9e80)
Location: kernel/trace/trace_events_hist.c:4906
Inline: True
Direct callers:
  - kernel/trace/trace_events_hist.c:event_hist_trigger_print
```
**Symbols:**

```
ffffffff811b9e80-ffffffff811b9f71: print_action_spec (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
void print_action_spec(struct seq_file *m, struct hist_trigger_data *hist_data, struct action_data *data);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_events_hist.c (ffffffff811c5480)
Location: kernel/trace/trace_events_hist.c:5016
Inline: True
Direct callers:
  - kernel/trace/trace_events_hist.c:event_hist_trigger_print
```
**Symbols:**

```
ffffffff811c5480-ffffffff811c5571: print_action_spec (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void print_action_spec(struct seq_file *m, struct hist_trigger_data *hist_data, struct action_data *data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_events_hist.c (ffffffff811e0360)
Location: kernel/trace/trace_events_hist.c:4124
Inline: False
Direct callers:
  - kernel/trace/trace_events_hist.c:print_actions_spec
```
**Symbols:**

```
ffffffff811e0360-ffffffff811e0451: print_action_spec (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void print_action_spec(struct seq_file *m, struct hist_trigger_data *hist_data, struct action_data *data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_events_hist.c (ffffffff811ddd20)
Location: kernel/trace/trace_events_hist.c:4149
Inline: False
Direct callers:
  - kernel/trace/trace_events_hist.c:print_actions_spec
```
**Symbols:**

```
ffffffff811ddd20-ffffffff811dde11: print_action_spec (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void print_action_spec(struct seq_file *m, struct hist_trigger_data *hist_data, struct action_data *data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_events_hist.c (ffffffff811df3a0)
Location: kernel/trace/trace_events_hist.c:4217
Inline: False
Direct callers:
  - kernel/trace/trace_events_hist.c:event_hist_trigger_print
```
**Symbols:**

```
ffffffff811df3a0-ffffffff811df491: print_action_spec (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
void print_action_spec(struct seq_file *m, struct hist_trigger_data *hist_data, struct action_data *data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/trace/trace_events_hist.c (0)
Location: kernel/trace/trace_events_hist.c:4312
Inline: False
Direct callers:
  - kernel/trace/trace_events_hist.c:event_hist_trigger_print
```
**Symbols:**

```
ffffffff8120fc70-ffffffff8120fdc6: print_action_spec (STB_LOCAL)
ffffffff81cb6e6f-ffffffff81cb6e98: print_action_spec.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
void print_action_spec(struct seq_file *m, struct hist_trigger_data *hist_data, struct action_data *data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/trace/trace_events_hist.c (0)
Location: kernel/trace/trace_events_hist.c:4691
Inline: False
Direct callers:
  - kernel/trace/trace_events_hist.c:event_hist_trigger_print
```
**Symbols:**

```
ffffffff8124c8a0-ffffffff8124ca10: print_action_spec (STB_LOCAL)
ffffffff81e67f0d-ffffffff81e67f35: print_action_spec.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
void print_action_spec(struct seq_file *m, struct hist_trigger_data *hist_data, struct action_data *data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/trace/trace_events_hist.c (0)
Location: kernel/trace/trace_events_hist.c:4822
Inline: False
Direct callers:
  - kernel/trace/trace_events_hist.c:event_hist_trigger_print
```
**Symbols:**

```
ffffffff8129ac50-ffffffff8129adc0: print_action_spec (STB_LOCAL)
ffffffff8205e89d-ffffffff8205e8c5: print_action_spec.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
void print_action_spec(struct seq_file *m, struct hist_trigger_data *hist_data, struct action_data *data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/trace/trace_events_hist.c (0)
Location: kernel/trace/trace_events_hist.c:4899
Inline: False
Direct callers:
  - kernel/trace/trace_events_hist.c:event_hist_trigger_print
```
**Symbols:**

```
ffffffff812b83c0-ffffffff812b8530: print_action_spec (STB_LOCAL)
ffffffff820dd3e1-ffffffff820dd409: print_action_spec.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
void print_action_spec(struct seq_file *m, struct hist_trigger_data *hist_data, struct action_data *data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/trace/trace_events_hist.c (0)
Location: kernel/trace/trace_events_hist.c:4891
Inline: False
Direct callers:
  - kernel/trace/trace_events_hist.c:event_hist_trigger_print
```
**Symbols:**

```
ffffffff812d4a10-ffffffff812d4b80: print_action_spec (STB_LOCAL)
ffffffff821b91e5-ffffffff821b920d: print_action_spec.cold (STB_LOCAL)
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
void print_action_spec(struct seq_file *m, struct hist_trigger_data *hist_data, struct action_data *data);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_events_hist.c (ffff800010245388)
Location: kernel/trace/trace_events_hist.c:5016
Inline: True
Direct callers:
  - kernel/trace/trace_events_hist.c:event_hist_trigger_print
```
**Symbols:**

```
ffff800010245388-ffff8000102454c8: print_action_spec (STB_LOCAL)
```
</details>
</li>
<li>
In <code>armhf</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
void print_action_spec(struct seq_file *m, struct hist_trigger_data *hist_data, struct action_data *data);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_events_hist.c (c0000000002d93c0)
Location: kernel/trace/trace_events_hist.c:5016
Inline: True
Direct callers:
  - kernel/trace/trace_events_hist.c:event_hist_trigger_print
```
**Symbols:**

```
c0000000002d93c0-c0000000002d95c8: print_action_spec (STB_LOCAL)
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
<summary>In <code>aws</code>: Selective Inline ⚠️</summary>

```c
void print_action_spec(struct seq_file *m, struct hist_trigger_data *hist_data, struct action_data *data);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_events_hist.c (ffffffff811bdaa0)
Location: kernel/trace/trace_events_hist.c:5016
Inline: True
Direct callers:
  - kernel/trace/trace_events_hist.c:event_hist_trigger_print
```
**Symbols:**

```
ffffffff811bdaa0-ffffffff811bdb91: print_action_spec (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
void print_action_spec(struct seq_file *m, struct hist_trigger_data *hist_data, struct action_data *data);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_events_hist.c (ffffffff811b0880)
Location: kernel/trace/trace_events_hist.c:5016
Inline: True
Direct callers:
  - kernel/trace/trace_events_hist.c:event_hist_trigger_print
```
**Symbols:**

```
ffffffff811b0880-ffffffff811b0971: print_action_spec (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
void print_action_spec(struct seq_file *m, struct hist_trigger_data *hist_data, struct action_data *data);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_events_hist.c (ffffffff811bb870)
Location: kernel/trace/trace_events_hist.c:5016
Inline: True
Direct callers:
  - kernel/trace/trace_events_hist.c:event_hist_trigger_print
```
**Symbols:**

```
ffffffff811bb870-ffffffff811bb961: print_action_spec (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
void print_action_spec(struct seq_file *m, struct hist_trigger_data *hist_data, struct action_data *data);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_events_hist.c (ffffffff811c9910)
Location: kernel/trace/trace_events_hist.c:5016
Inline: True
Direct callers:
  - kernel/trace/trace_events_hist.c:event_hist_trigger_print
```
**Symbols:**

```
ffffffff811c9910-ffffffff811c9a01: print_action_spec (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
