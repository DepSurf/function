# Function: <code>probe_event_enable</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int probe_event_enable(struct trace_uprobe *tu, struct trace_event_file *file, filter_func_t filter);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_uprobe.c (ffffffff8116f580)
Location: kernel/trace/trace_uprobe.c:899
Inline: False
Direct callers:
  - kernel/trace/trace_uprobe.c:trace_uprobe_register
  - kernel/trace/trace_uprobe.c:trace_uprobe_register
```
**Symbols:**

```
ffffffff8116f580-ffffffff8116f876: probe_event_enable (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int probe_event_enable(struct trace_uprobe *tu, struct trace_event_file *file, filter_func_t filter);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_uprobe.c (ffffffff8117cc60)
Location: kernel/trace/trace_uprobe.c:899
Inline: False
Direct callers:
  - kernel/trace/trace_uprobe.c:trace_uprobe_register
  - kernel/trace/trace_uprobe.c:trace_uprobe_register
```
**Symbols:**

```
ffffffff8117cc60-ffffffff8117cf62: probe_event_enable (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int probe_event_enable(struct trace_uprobe *tu, struct trace_event_file *file, filter_func_t filter);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_uprobe.c (ffffffff81188870)
Location: kernel/trace/trace_uprobe.c:899
Inline: False
Direct callers:
  - kernel/trace/trace_uprobe.c:trace_uprobe_register
  - kernel/trace/trace_uprobe.c:trace_uprobe_register
```
**Symbols:**

```
ffffffff81188870-ffffffff81188b76: probe_event_enable (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int probe_event_enable(struct trace_uprobe *tu, struct trace_event_file *file, filter_func_t filter);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_uprobe.c (ffffffff8118b4c0)
Location: kernel/trace/trace_uprobe.c:902
Inline: False
Direct callers:
  - kernel/trace/trace_uprobe.c:trace_uprobe_register
  - kernel/trace/trace_uprobe.c:trace_uprobe_register
```
**Symbols:**

```
ffffffff8118b4c0-ffffffff8118b79a: probe_event_enable (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int probe_event_enable(struct trace_uprobe *tu, struct trace_event_file *file, filter_func_t filter);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_uprobe.c (ffffffff81198f80)
Location: kernel/trace/trace_uprobe.c:902
Inline: False
Direct callers:
  - kernel/trace/trace_uprobe.c:trace_uprobe_register
  - kernel/trace/trace_uprobe.c:trace_uprobe_register
```
**Symbols:**

```
ffffffff81198f80-ffffffff8119923d: probe_event_enable (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int probe_event_enable(struct trace_uprobe *tu, struct trace_event_file *file, filter_func_t filter);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_uprobe.c (ffffffff811ae640)
Location: kernel/trace/trace_uprobe.c:883
Inline: False
Direct callers:
  - kernel/trace/trace_uprobe.c:trace_uprobe_register
  - kernel/trace/trace_uprobe.c:trace_uprobe_register
```
**Symbols:**

```
ffffffff811ae640-ffffffff811ae92f: probe_event_enable (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int probe_event_enable(struct trace_uprobe *tu, struct trace_event_file *file, filter_func_t filter);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_uprobe.c (ffffffff811bccb0)
Location: kernel/trace/trace_uprobe.c:890
Inline: False
Direct callers:
  - kernel/trace/trace_uprobe.c:trace_uprobe_register
  - kernel/trace/trace_uprobe.c:trace_uprobe_register
```
**Symbols:**

```
ffffffff811bccb0-ffffffff811bcfbf: probe_event_enable (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
int probe_event_enable(struct trace_uprobe *tu, struct trace_event_file *file, filter_func_t filter);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/trace/trace_uprobe.c (0)
Location: kernel/trace/trace_uprobe.c:928
Inline: False
Direct callers:
  - kernel/trace/trace_uprobe.c:trace_uprobe_register
  - kernel/trace/trace_uprobe.c:trace_uprobe_register
```
**Symbols:**

```
ffffffff811cc3f0-ffffffff811cc675: probe_event_enable (STB_LOCAL)
ffffffff811ce1a5-ffffffff811ce1b8: probe_event_enable.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int probe_event_enable(struct trace_event_call *call, struct trace_event_file *file, filter_func_t filter);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_uprobe.c (ffffffff811d8920)
Location: kernel/trace/trace_uprobe.c:1076
Inline: False
```
**Symbols:**

```
ffffffff811d8920-ffffffff811d8c0f: probe_event_enable (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int probe_event_enable(struct trace_event_call *call, struct trace_event_file *file, filter_func_t filter);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_uprobe.c (ffffffff811f5700)
Location: kernel/trace/trace_uprobe.c:1076
Inline: False
Direct callers:
  - kernel/trace/trace_uprobe.c:trace_uprobe_register
  - kernel/trace/trace_uprobe.c:trace_uprobe_register
```
**Symbols:**

```
ffffffff811f5700-ffffffff811f58e0: probe_event_enable (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int probe_event_enable(struct trace_event_call *call, struct trace_event_file *file, filter_func_t filter);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_uprobe.c (ffffffff811f4090)
Location: kernel/trace/trace_uprobe.c:1089
Inline: False
Direct callers:
  - kernel/trace/trace_uprobe.c:trace_uprobe_register
  - kernel/trace/trace_uprobe.c:trace_uprobe_register
```
**Symbols:**

```
ffffffff811f4090-ffffffff811f4270: probe_event_enable (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int probe_event_enable(struct trace_event_call *call, struct trace_event_file *file, filter_func_t filter);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_uprobe.c (ffffffff811f4c30)
Location: kernel/trace/trace_uprobe.c:1094
Inline: False
Direct callers:
  - kernel/trace/trace_uprobe.c:trace_uprobe_register
  - kernel/trace/trace_uprobe.c:trace_uprobe_register
```
**Symbols:**

```
ffffffff811f4c30-ffffffff811f4f18: probe_event_enable (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int probe_event_enable(struct trace_event_call *call, struct trace_event_file *file, filter_func_t filter);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_uprobe.c (ffffffff81226e40)
Location: kernel/trace/trace_uprobe.c:1094
Inline: False
Direct callers:
  - kernel/trace/trace_uprobe.c:trace_uprobe_register
  - kernel/trace/trace_uprobe.c:trace_uprobe_register
```
**Symbols:**

```
ffffffff81226e40-ffffffff812271dc: probe_event_enable (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int probe_event_enable(struct trace_event_call *call, struct trace_event_file *file, filter_func_t filter);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_uprobe.c (ffffffff81266960)
Location: kernel/trace/trace_uprobe.c:1087
Inline: False
Direct callers:
  - kernel/trace/trace_uprobe.c:trace_uprobe_register
  - kernel/trace/trace_uprobe.c:trace_uprobe_register
```
**Symbols:**

```
ffffffff81266960-ffffffff81266d22: probe_event_enable (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int probe_event_enable(struct trace_event_call *call, struct trace_event_file *file, filter_func_t filter);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_uprobe.c (ffffffff812b8bc0)
Location: kernel/trace/trace_uprobe.c:1093
Inline: False
Direct callers:
  - kernel/trace/trace_uprobe.c:trace_uprobe_register
  - kernel/trace/trace_uprobe.c:trace_uprobe_register
```
**Symbols:**

```
ffffffff812b8bc0-ffffffff812b8def: probe_event_enable (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int probe_event_enable(struct trace_event_call *call, struct trace_event_file *file, filter_func_t filter);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_uprobe.c (ffffffff812dc210)
Location: kernel/trace/trace_uprobe.c:1093
Inline: False
Direct callers:
  - kernel/trace/trace_uprobe.c:trace_uprobe_register
  - kernel/trace/trace_uprobe.c:trace_uprobe_register
```
**Symbols:**

```
ffffffff812dc210-ffffffff812dc450: probe_event_enable (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int probe_event_enable(struct trace_event_call *call, struct trace_event_file *file, filter_func_t filter);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_uprobe.c (ffffffff812fa2f0)
Location: kernel/trace/trace_uprobe.c:1089
Inline: False
Direct callers:
  - kernel/trace/trace_uprobe.c:trace_uprobe_register
  - kernel/trace/trace_uprobe.c:trace_uprobe_register
```
**Symbols:**

```
ffffffff812fa2f0-ffffffff812fa530: probe_event_enable (STB_LOCAL)
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
int probe_event_enable(struct trace_event_call *call, struct trace_event_file *file, filter_func_t filter);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_uprobe.c (ffff8000102599b8)
Location: kernel/trace/trace_uprobe.c:1076
Inline: False
```
**Symbols:**

```
ffff8000102599b8-ffff800010259cf0: probe_event_enable (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int probe_event_enable(struct trace_event_call *call, struct trace_event_file *file, filter_func_t filter);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_uprobe.c (c048b93c)
Location: kernel/trace/trace_uprobe.c:1076
Inline: False
```
**Symbols:**

```
c048b93c-c048bc90: probe_event_enable (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int probe_event_enable(struct trace_event_call *call, struct trace_event_file *file, filter_func_t filter);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_uprobe.c (c0000000002fd140)
Location: kernel/trace/trace_uprobe.c:1076
Inline: False
```
**Symbols:**

```
c0000000002fd140-c0000000002fd5e8: probe_event_enable (STB_LOCAL)
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
int probe_event_enable(struct trace_event_call *call, struct trace_event_file *file, filter_func_t filter);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_uprobe.c (ffffffff811d0f40)
Location: kernel/trace/trace_uprobe.c:1076
Inline: False
```
**Symbols:**

```
ffffffff811d0f40-ffffffff811d122f: probe_event_enable (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int probe_event_enable(struct trace_event_call *call, struct trace_event_file *file, filter_func_t filter);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_uprobe.c (ffffffff811c3d10)
Location: kernel/trace/trace_uprobe.c:1076
Inline: False
```
**Symbols:**

```
ffffffff811c3d10-ffffffff811c3fff: probe_event_enable (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int probe_event_enable(struct trace_event_call *call, struct trace_event_file *file, filter_func_t filter);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_uprobe.c (ffffffff811ced10)
Location: kernel/trace/trace_uprobe.c:1076
Inline: False
```
**Symbols:**

```
ffffffff811ced10-ffffffff811cefff: probe_event_enable (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int probe_event_enable(struct trace_event_call *call, struct trace_event_file *file, filter_func_t filter);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_uprobe.c (ffffffff811dcfa0)
Location: kernel/trace/trace_uprobe.c:1076
Inline: False
```
**Symbols:**

```
ffffffff811dcfa0-ffffffff811dd28f: probe_event_enable (STB_LOCAL)
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
<details>
<summary>Changed between <code>5.3</code> and <code>5.4</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>struct trace_event_call *call</code>
</li>
<li>
<b>Param removed. </b>
<code>struct trace_uprobe *tu</code>
</li>
</ul>
</details>
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
