# Function: <code>hist_field_print</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/trace/trace_events_hist.c (ffffffff81171f90)
Location: kernel/trace/trace_events_hist.c:1142
Inline: True
Direct callers:
  - kernel/trace/trace_events_hist.c:event_hist_trigger_print
  - kernel/trace/trace_events_hist.c:event_hist_trigger_print
  - kernel/trace/trace_events_hist.c:event_hist_trigger_print
```
**Symbols:**

```
ffffffff81171f90-ffffffff8117201a: hist_field_print.isra.5 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/trace/trace_events_hist.c (ffffffff8117d790)
Location: kernel/trace/trace_events_hist.c:1142
Inline: True
Direct callers:
  - kernel/trace/trace_events_hist.c:event_hist_trigger_print
  - kernel/trace/trace_events_hist.c:event_hist_trigger_print
  - kernel/trace/trace_events_hist.c:event_hist_trigger_print
```
**Symbols:**

```
ffffffff8117d790-ffffffff8117d81a: hist_field_print.isra.7 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/trace/trace_events_hist.c (ffffffff81180310)
Location: kernel/trace/trace_events_hist.c:1143
Inline: True
Direct callers:
  - kernel/trace/trace_events_hist.c:event_hist_trigger_print
  - kernel/trace/trace_events_hist.c:event_hist_trigger_print
  - kernel/trace/trace_events_hist.c:event_hist_trigger_print
```
**Symbols:**

```
ffffffff81180310-ffffffff8118039a: hist_field_print.isra.7 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void hist_field_print(struct seq_file *m, struct hist_field *hist_field);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_events_hist.c (ffffffff8118dc00)
Location: kernel/trace/trace_events_hist.c:1185
Inline: False
Direct callers:
  - kernel/trace/trace_events_hist.c:event_hist_trigger_print
  - kernel/trace/trace_events_hist.c:event_hist_trigger_print
  - kernel/trace/trace_events_hist.c:event_hist_trigger_print
```
**Symbols:**

```
ffffffff8118dc00-ffffffff8118dc96: hist_field_print (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void hist_field_print(struct seq_file *m, struct hist_field *hist_field);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_events_hist.c (ffffffff8119d840)
Location: kernel/trace/trace_events_hist.c:4902
Inline: False
Direct callers:
  - kernel/trace/trace_events_hist.c:event_hist_trigger_print
  - kernel/trace/trace_events_hist.c:event_hist_trigger_print
  - kernel/trace/trace_events_hist.c:event_hist_trigger_print
  - kernel/trace/trace_events_hist.c:event_hist_trigger_print
```
**Symbols:**

```
ffffffff8119d840-ffffffff8119d917: hist_field_print (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void hist_field_print(struct seq_file *m, struct hist_field *hist_field);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_events_hist.c (ffffffff811aba30)
Location: kernel/trace/trace_events_hist.c:4988
Inline: False
Direct callers:
  - kernel/trace/trace_events_hist.c:event_hist_trigger_print
  - kernel/trace/trace_events_hist.c:event_hist_trigger_print
  - kernel/trace/trace_events_hist.c:event_hist_trigger_print
  - kernel/trace/trace_events_hist.c:event_hist_trigger_print
```
**Symbols:**

```
ffffffff811aba30-ffffffff811abb07: hist_field_print (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void hist_field_print(struct seq_file *m, struct hist_field *hist_field);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_events_hist.c (ffffffff811b9d30)
Location: kernel/trace/trace_events_hist.c:5507
Inline: False
Direct callers:
  - kernel/trace/trace_events_hist.c:event_hist_trigger_print
  - kernel/trace/trace_events_hist.c:event_hist_trigger_print
  - kernel/trace/trace_events_hist.c:event_hist_trigger_print
  - kernel/trace/trace_events_hist.c:event_hist_trigger_print
```
**Symbols:**

```
ffffffff811b9d30-ffffffff811b9e09: hist_field_print (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void hist_field_print(struct seq_file *m, struct hist_field *hist_field);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_events_hist.c (ffffffff811c5300)
Location: kernel/trace/trace_events_hist.c:5623
Inline: False
Direct callers:
  - kernel/trace/trace_events_hist.c:event_hist_trigger_print
  - kernel/trace/trace_events_hist.c:event_hist_trigger_print
  - kernel/trace/trace_events_hist.c:event_hist_trigger_print
  - kernel/trace/trace_events_hist.c:event_hist_trigger_print
```
**Symbols:**

```
ffffffff811c5300-ffffffff811c53d9: hist_field_print (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void hist_field_print(struct seq_file *m, struct hist_field *hist_field);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_events_hist.c (ffffffff811e2e90)
Location: kernel/trace/trace_events_hist.c:5004
Inline: False
Direct callers:
  - kernel/trace/trace_events_hist.c:event_hist_trigger_print
  - kernel/trace/trace_events_hist.c:event_hist_trigger_print
  - kernel/trace/trace_events_hist.c:event_hist_trigger_print
  - kernel/trace/trace_events_hist.c:event_hist_trigger_print
```
**Symbols:**

```
ffffffff811e2e90-ffffffff811e2f67: hist_field_print (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void hist_field_print(struct seq_file *m, struct hist_field *hist_field);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_events_hist.c (ffffffff811e0ab0)
Location: kernel/trace/trace_events_hist.c:5045
Inline: False
Direct callers:
  - kernel/trace/trace_events_hist.c:event_hist_trigger_print
  - kernel/trace/trace_events_hist.c:event_hist_trigger_print
  - kernel/trace/trace_events_hist.c:event_hist_trigger_print
  - kernel/trace/trace_events_hist.c:event_hist_trigger_print
```
**Symbols:**

```
ffffffff811e0ab0-ffffffff811e0b87: hist_field_print (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void hist_field_print(struct seq_file *m, struct hist_field *hist_field);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_events_hist.c (ffffffff811e1c80)
Location: kernel/trace/trace_events_hist.c:5114
Inline: False
Direct callers:
  - kernel/trace/trace_events_hist.c:event_hist_trigger_print
  - kernel/trace/trace_events_hist.c:event_hist_trigger_print
  - kernel/trace/trace_events_hist.c:event_hist_trigger_print
  - kernel/trace/trace_events_hist.c:event_hist_trigger_print
```
**Symbols:**

```
ffffffff811e1c80-ffffffff811e1d57: hist_field_print (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void hist_field_print(struct seq_file *m, struct hist_field *hist_field);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_events_hist.c (ffffffff81211c30)
Location: kernel/trace/trace_events_hist.c:5217
Inline: False
Direct callers:
  - kernel/trace/trace_events_hist.c:event_hist_trigger_print
  - kernel/trace/trace_events_hist.c:event_hist_trigger_print
  - kernel/trace/trace_events_hist.c:event_hist_trigger_print
  - kernel/trace/trace_events_hist.c:event_hist_trigger_print
```
**Symbols:**

```
ffffffff81211c30-ffffffff81211d2a: hist_field_print (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void hist_field_print(struct seq_file *m, struct hist_field *hist_field);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_events_hist.c (ffffffff8124e460)
Location: kernel/trace/trace_events_hist.c:5597
Inline: False
Direct callers:
  - kernel/trace/trace_events_hist.c:event_hist_trigger_print
  - kernel/trace/trace_events_hist.c:event_hist_trigger_print
  - kernel/trace/trace_events_hist.c:event_hist_trigger_print
  - kernel/trace/trace_events_hist.c:event_hist_trigger_print
```
**Symbols:**

```
ffffffff8124e460-ffffffff8124e5a5: hist_field_print (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void hist_field_print(struct seq_file *m, struct hist_field *hist_field);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_events_hist.c (ffffffff8129bf50)
Location: kernel/trace/trace_events_hist.c:5824
Inline: False
Direct callers:
  - kernel/trace/trace_events_hist.c:event_hist_trigger_print
  - kernel/trace/trace_events_hist.c:event_hist_trigger_print
  - kernel/trace/trace_events_hist.c:event_hist_trigger_print
  - kernel/trace/trace_events_hist.c:event_hist_trigger_print
```
**Symbols:**

```
ffffffff8129bf50-ffffffff8129c095: hist_field_print (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void hist_field_print(struct seq_file *m, struct hist_field *hist_field);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_events_hist.c (ffffffff812b96d0)
Location: kernel/trace/trace_events_hist.c:5925
Inline: False
Direct callers:
  - kernel/trace/trace_events_hist.c:event_hist_trigger_print
  - kernel/trace/trace_events_hist.c:event_hist_trigger_print
  - kernel/trace/trace_events_hist.c:event_hist_trigger_print
  - kernel/trace/trace_events_hist.c:event_hist_trigger_print
```
**Symbols:**

```
ffffffff812b96d0-ffffffff812b9815: hist_field_print (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void hist_field_print(struct seq_file *m, struct hist_field *hist_field);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_events_hist.c (ffffffff812d5d20)
Location: kernel/trace/trace_events_hist.c:5921
Inline: False
Direct callers:
  - kernel/trace/trace_events_hist.c:event_hist_trigger_print
  - kernel/trace/trace_events_hist.c:event_hist_trigger_print
  - kernel/trace/trace_events_hist.c:event_hist_trigger_print
  - kernel/trace/trace_events_hist.c:event_hist_trigger_print
```
**Symbols:**

```
ffffffff812d5d20-ffffffff812d5e65: hist_field_print (STB_LOCAL)
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
void hist_field_print(struct seq_file *m, struct hist_field *hist_field);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_events_hist.c (ffff800010245118)
Location: kernel/trace/trace_events_hist.c:5623
Inline: False
Direct callers:
  - kernel/trace/trace_events_hist.c:event_hist_trigger_print
  - kernel/trace/trace_events_hist.c:event_hist_trigger_print
  - kernel/trace/trace_events_hist.c:event_hist_trigger_print
  - kernel/trace/trace_events_hist.c:event_hist_trigger_print
```
**Symbols:**

```
ffff800010245118-ffff800010245204: hist_field_print (STB_LOCAL)
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
void hist_field_print(struct seq_file *m, struct hist_field *hist_field);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_events_hist.c (c0000000002d9060)
Location: kernel/trace/trace_events_hist.c:5623
Inline: False
Direct callers:
  - kernel/trace/trace_events_hist.c:event_hist_trigger_print
  - kernel/trace/trace_events_hist.c:event_hist_trigger_print
  - kernel/trace/trace_events_hist.c:event_hist_trigger_print
  - kernel/trace/trace_events_hist.c:event_hist_trigger_print
```
**Symbols:**

```
c0000000002d9060-c0000000002d91b4: hist_field_print (STB_LOCAL)
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
void hist_field_print(struct seq_file *m, struct hist_field *hist_field);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_events_hist.c (ffffffff811bd920)
Location: kernel/trace/trace_events_hist.c:5623
Inline: False
Direct callers:
  - kernel/trace/trace_events_hist.c:event_hist_trigger_print
  - kernel/trace/trace_events_hist.c:event_hist_trigger_print
  - kernel/trace/trace_events_hist.c:event_hist_trigger_print
  - kernel/trace/trace_events_hist.c:event_hist_trigger_print
```
**Symbols:**

```
ffffffff811bd920-ffffffff811bd9f9: hist_field_print (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void hist_field_print(struct seq_file *m, struct hist_field *hist_field);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_events_hist.c (ffffffff811b0700)
Location: kernel/trace/trace_events_hist.c:5623
Inline: False
Direct callers:
  - kernel/trace/trace_events_hist.c:event_hist_trigger_print
  - kernel/trace/trace_events_hist.c:event_hist_trigger_print
  - kernel/trace/trace_events_hist.c:event_hist_trigger_print
  - kernel/trace/trace_events_hist.c:event_hist_trigger_print
```
**Symbols:**

```
ffffffff811b0700-ffffffff811b07d9: hist_field_print (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void hist_field_print(struct seq_file *m, struct hist_field *hist_field);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_events_hist.c (ffffffff811bb6f0)
Location: kernel/trace/trace_events_hist.c:5623
Inline: False
Direct callers:
  - kernel/trace/trace_events_hist.c:event_hist_trigger_print
  - kernel/trace/trace_events_hist.c:event_hist_trigger_print
  - kernel/trace/trace_events_hist.c:event_hist_trigger_print
  - kernel/trace/trace_events_hist.c:event_hist_trigger_print
```
**Symbols:**

```
ffffffff811bb6f0-ffffffff811bb7c9: hist_field_print (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void hist_field_print(struct seq_file *m, struct hist_field *hist_field);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_events_hist.c (ffffffff811c9790)
Location: kernel/trace/trace_events_hist.c:5623
Inline: False
Direct callers:
  - kernel/trace/trace_events_hist.c:event_hist_trigger_print
  - kernel/trace/trace_events_hist.c:event_hist_trigger_print
  - kernel/trace/trace_events_hist.c:event_hist_trigger_print
  - kernel/trace/trace_events_hist.c:event_hist_trigger_print
```
**Symbols:**

```
ffffffff811c9790-ffffffff811c9869: hist_field_print (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
