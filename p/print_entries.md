# Function: <code>print_entries</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>4.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_events_hist.c (ffffffff81172df3)
Location: kernel/trace/trace_events_hist.c:1037
Inline: True
Inline callers:
  - kernel/trace/trace_events_hist.c:hist_show
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
In kernel/trace/trace_events_hist.c (ffffffff8117e5f0)
Location: kernel/trace/trace_events_hist.c:1037
Inline: True
Inline callers:
  - kernel/trace/trace_events_hist.c:hist_show
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
In kernel/trace/trace_events_hist.c (ffffffff811811ec)
Location: kernel/trace/trace_events_hist.c:1038
Inline: True
Inline callers:
  - kernel/trace/trace_events_hist.c:hist_show
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
In kernel/trace/trace_events_hist.c (ffffffff8118eb2f)
Location: kernel/trace/trace_events_hist.c:1082
Inline: True
Inline callers:
  - kernel/trace/trace_events_hist.c:hist_show
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
In kernel/trace/trace_events_hist.c (ffffffff8119fc44)
Location: kernel/trace/trace_events_hist.c:4814
Inline: True
Inline callers:
  - kernel/trace/trace_events_hist.c:hist_show
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
In kernel/trace/trace_events_hist.c (ffffffff811aed54)
Location: kernel/trace/trace_events_hist.c:4900
Inline: True
Inline callers:
  - kernel/trace/trace_events_hist.c:hist_show
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
In kernel/trace/trace_events_hist.c (ffffffff811bd271)
Location: kernel/trace/trace_events_hist.c:5422
Inline: True
Inline callers:
  - kernel/trace/trace_events_hist.c:hist_show
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
In kernel/trace/trace_events_hist.c (ffffffff811c8611)
Location: kernel/trace/trace_events_hist.c:5532
Inline: True
Inline callers:
  - kernel/trace/trace_events_hist.c:hist_show
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
In kernel/trace/trace_events_hist.c (ffffffff811e2b0d)
Location: kernel/trace/trace_events_hist.c:4640
Inline: True
Inline callers:
  - kernel/trace/trace_events_hist.c:hist_show
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_events_hist.c (ffffffff811e072d)
Location: kernel/trace/trace_events_hist.c:4681
Inline: True
Inline callers:
  - kernel/trace/trace_events_hist.c:hist_show
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int print_entries(struct seq_file *m, struct hist_trigger_data *hist_data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_events_hist.c (ffffffff811e1540)
Location: kernel/trace/trace_events_hist.c:4750
Inline: False
Direct callers:
  - kernel/trace/trace_events_hist.c:hist_show
```
**Symbols:**

```
ffffffff811e1540-ffffffff811e17d6: print_entries (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int print_entries(struct seq_file *m, struct hist_trigger_data *hist_data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_events_hist.c (ffffffff812115e0)
Location: kernel/trace/trace_events_hist.c:4853
Inline: False
Direct callers:
  - kernel/trace/trace_events_hist.c:hist_show
```
**Symbols:**

```
ffffffff812115e0-ffffffff8121195e: print_entries (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int print_entries(struct seq_file *m, struct hist_trigger_data *hist_data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_events_hist.c (ffffffff8124daf0)
Location: kernel/trace/trace_events_hist.c:5228
Inline: False
Direct callers:
  - kernel/trace/trace_events_hist.c:hist_show
```
**Symbols:**

```
ffffffff8124daf0-ffffffff8124de61: print_entries (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
int print_entries(struct seq_file *m, struct hist_trigger_data *hist_data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/trace/trace_events_hist.c (0)
Location: kernel/trace/trace_events_hist.c:5430
Inline: False
Direct callers:
  - kernel/trace/trace_events_hist.c:hist_show
```
**Symbols:**

```
ffffffff8129c860-ffffffff8129cf68: print_entries (STB_LOCAL)
ffffffff8205eab6-ffffffff8205eacb: print_entries.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
int print_entries(struct seq_file *m, struct hist_trigger_data *hist_data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/trace/trace_events_hist.c (0)
Location: kernel/trace/trace_events_hist.c:5531
Inline: False
Direct callers:
  - kernel/trace/trace_events_hist.c:hist_show
```
**Symbols:**

```
ffffffff812ba1a0-ffffffff812ba8f5: print_entries (STB_LOCAL)
ffffffff820dd5f3-ffffffff820dd608: print_entries.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
int print_entries(struct seq_file *m, struct hist_trigger_data *hist_data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/trace/trace_events_hist.c (0)
Location: kernel/trace/trace_events_hist.c:5523
Inline: False
Direct callers:
  - kernel/trace/trace_events_hist.c:hist_show
```
**Symbols:**

```
ffffffff812d67f0-ffffffff812d6f45: print_entries (STB_LOCAL)
ffffffff821b93f7-ffffffff821b940c: print_entries.cold (STB_LOCAL)
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
In kernel/trace/trace_events_hist.c (ffff800010248d2c)
Location: kernel/trace/trace_events_hist.c:5532
Inline: True
Inline callers:
  - kernel/trace/trace_events_hist.c:hist_show
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
In kernel/trace/trace_events_hist.c (c0000000002dd4d0)
Location: kernel/trace/trace_events_hist.c:5532
Inline: True
Inline callers:
  - kernel/trace/trace_events_hist.c:hist_show
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
In kernel/trace/trace_events_hist.c (ffffffff811c0c31)
Location: kernel/trace/trace_events_hist.c:5532
Inline: True
Inline callers:
  - kernel/trace/trace_events_hist.c:hist_show
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
In kernel/trace/trace_events_hist.c (ffffffff811b3a11)
Location: kernel/trace/trace_events_hist.c:5532
Inline: True
Inline callers:
  - kernel/trace/trace_events_hist.c:hist_show
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
In kernel/trace/trace_events_hist.c (ffffffff811bea01)
Location: kernel/trace/trace_events_hist.c:5532
Inline: True
Inline callers:
  - kernel/trace/trace_events_hist.c:hist_show
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
In kernel/trace/trace_events_hist.c (ffffffff811ccaa1)
Location: kernel/trace/trace_events_hist.c:5532
Inline: True
Inline callers:
  - kernel/trace/trace_events_hist.c:hist_show
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
