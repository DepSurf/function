# Function: <code>trace_probe_add_file</code>

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
<summary>In <code>5.3</code>: ✅</summary>

```c
int trace_probe_add_file(struct trace_probe *tp, struct trace_event_file *file);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_probe.c (ffffffff811cba00)
Location: kernel/trace/trace_probe.c:945
Inline: False
Direct callers:
  - kernel/trace/trace_kprobe.c:kprobe_register
  - kernel/trace/trace_uprobe.c:probe_event_enable
```
**Symbols:**

```
ffffffff811cba00-ffffffff811cba64: trace_probe_add_file (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int trace_probe_add_file(struct trace_probe *tp, struct trace_event_file *file);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_probe.c (ffffffff811d7a50)
Location: kernel/trace/trace_probe.c:1048
Inline: False
Direct callers:
  - kernel/trace/trace_kprobe.c:enable_trace_kprobe
  - kernel/trace/trace_uprobe.c:probe_event_enable
```
**Symbols:**

```
ffffffff811d7a50-ffffffff811d7ac0: trace_probe_add_file (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int trace_probe_add_file(struct trace_probe *tp, struct trace_event_file *file);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_probe.c (ffffffff811f43f0)
Location: kernel/trace/trace_probe.c:1048
Inline: False
Direct callers:
  - kernel/trace/trace_kprobe.c:enable_trace_kprobe
  - kernel/trace/trace_uprobe.c:probe_event_enable
```
**Symbols:**

```
ffffffff811f43f0-ffffffff811f4460: trace_probe_add_file (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int trace_probe_add_file(struct trace_probe *tp, struct trace_event_file *file);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_probe.c (ffffffff811f2da0)
Location: kernel/trace/trace_probe.c:1048
Inline: False
Direct callers:
  - kernel/trace/trace_kprobe.c:enable_trace_kprobe
  - kernel/trace/trace_uprobe.c:probe_event_enable
```
**Symbols:**

```
ffffffff811f2da0-ffffffff811f2e10: trace_probe_add_file (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int trace_probe_add_file(struct trace_probe *tp, struct trace_event_file *file);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_probe.c (ffffffff811f3c20)
Location: kernel/trace/trace_probe.c:1048
Inline: False
Direct callers:
  - kernel/trace/trace_kprobe.c:enable_trace_kprobe
  - kernel/trace/trace_uprobe.c:probe_event_enable
```
**Symbols:**

```
ffffffff811f3c20-ffffffff811f3c90: trace_probe_add_file (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int trace_probe_add_file(struct trace_probe *tp, struct trace_event_file *file);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_probe.c (ffffffff81224f70)
Location: kernel/trace/trace_probe.c:1105
Inline: False
Direct callers:
  - kernel/trace/trace_eprobe.c:enable_trace_eprobe
  - kernel/trace/trace_kprobe.c:enable_trace_kprobe
  - kernel/trace/trace_uprobe.c:probe_event_enable
```
**Symbols:**

```
ffffffff81224f70-ffffffff81224fe0: trace_probe_add_file (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int trace_probe_add_file(struct trace_probe *tp, struct trace_event_file *file);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_probe.c (ffffffff81264e40)
Location: kernel/trace/trace_probe.c:1112
Inline: False
Direct callers:
  - kernel/trace/trace_eprobe.c:enable_trace_eprobe
  - kernel/trace/trace_kprobe.c:enable_trace_kprobe
  - kernel/trace/trace_uprobe.c:probe_event_enable
```
**Symbols:**

```
ffffffff81264e40-ffffffff81264ebc: trace_probe_add_file (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int trace_probe_add_file(struct trace_probe *tp, struct trace_event_file *file);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_probe.c (ffffffff812b69f0)
Location: kernel/trace/trace_probe.c:1135
Inline: False
Direct callers:
  - kernel/trace/trace_eprobe.c:enable_trace_eprobe
  - kernel/trace/trace_kprobe.c:enable_trace_kprobe
  - kernel/trace/trace_uprobe.c:probe_event_enable
```
**Symbols:**

```
ffffffff812b69f0-ffffffff812b6a6c: trace_probe_add_file (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int trace_probe_add_file(struct trace_probe *tp, struct trace_event_file *file);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_probe.c (ffffffff812d9ee0)
Location: kernel/trace/trace_probe.c:1616
Inline: False
Direct callers:
  - kernel/trace/trace_eprobe.c:enable_trace_eprobe
  - kernel/trace/trace_kprobe.c:enable_trace_kprobe
  - kernel/trace/trace_uprobe.c:probe_event_enable
  - kernel/trace/trace_fprobe.c:enable_trace_fprobe
```
**Symbols:**

```
ffffffff812d9ee0-ffffffff812d9f5c: trace_probe_add_file (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int trace_probe_add_file(struct trace_probe *tp, struct trace_event_file *file);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_probe.c (ffffffff812f7e40)
Location: kernel/trace/trace_probe.c:1853
Inline: False
Direct callers:
  - kernel/trace/trace_eprobe.c:enable_trace_eprobe
  - kernel/trace/trace_kprobe.c:enable_trace_kprobe
  - kernel/trace/trace_uprobe.c:probe_event_enable
  - kernel/trace/trace_fprobe.c:enable_trace_fprobe
```
**Symbols:**

```
ffffffff812f7e40-ffffffff812f7eed: trace_probe_add_file (STB_GLOBAL)
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
int trace_probe_add_file(struct trace_probe *tp, struct trace_event_file *file);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_probe.c (ffff800010257dc8)
Location: kernel/trace/trace_probe.c:1048
Inline: False
Direct callers:
  - kernel/trace/trace_kprobe.c:enable_trace_kprobe
  - kernel/trace/trace_uprobe.c:probe_event_enable
```
**Symbols:**

```
ffff800010257dc8-ffff800010257e44: trace_probe_add_file (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int trace_probe_add_file(struct trace_probe *tp, struct trace_event_file *file);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_probe.c (c048aeec)
Location: kernel/trace/trace_probe.c:1048
Inline: False
Direct callers:
  - kernel/trace/trace_kprobe.c:enable_trace_kprobe
  - kernel/trace/trace_uprobe.c:probe_event_enable
```
**Symbols:**

```
c048aeec-c048af70: trace_probe_add_file (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int trace_probe_add_file(struct trace_probe *tp, struct trace_event_file *file);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_probe.c (c0000000002f9e20)
Location: kernel/trace/trace_probe.c:1048
Inline: False
Direct callers:
  - kernel/trace/trace_kprobe.c:enable_trace_kprobe
  - kernel/trace/trace_uprobe.c:probe_event_enable
```
**Symbols:**

```
c0000000002f9e20-c0000000002f9ecc: trace_probe_add_file (STB_GLOBAL)
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
int trace_probe_add_file(struct trace_probe *tp, struct trace_event_file *file);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_probe.c (ffffffff811d0070)
Location: kernel/trace/trace_probe.c:1048
Inline: False
Direct callers:
  - kernel/trace/trace_kprobe.c:enable_trace_kprobe
  - kernel/trace/trace_uprobe.c:probe_event_enable
```
**Symbols:**

```
ffffffff811d0070-ffffffff811d00e0: trace_probe_add_file (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int trace_probe_add_file(struct trace_probe *tp, struct trace_event_file *file);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_probe.c (ffffffff811c2e40)
Location: kernel/trace/trace_probe.c:1048
Inline: False
Direct callers:
  - kernel/trace/trace_kprobe.c:enable_trace_kprobe
  - kernel/trace/trace_uprobe.c:probe_event_enable
```
**Symbols:**

```
ffffffff811c2e40-ffffffff811c2eb0: trace_probe_add_file (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int trace_probe_add_file(struct trace_probe *tp, struct trace_event_file *file);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_probe.c (ffffffff811cde40)
Location: kernel/trace/trace_probe.c:1048
Inline: False
Direct callers:
  - kernel/trace/trace_kprobe.c:enable_trace_kprobe
  - kernel/trace/trace_uprobe.c:probe_event_enable
```
**Symbols:**

```
ffffffff811cde40-ffffffff811cdeb0: trace_probe_add_file (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int trace_probe_add_file(struct trace_probe *tp, struct trace_event_file *file);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_probe.c (ffffffff811dc0a0)
Location: kernel/trace/trace_probe.c:1048
Inline: False
Direct callers:
  - kernel/trace/trace_kprobe.c:enable_trace_kprobe
  - kernel/trace/trace_uprobe.c:probe_event_enable
```
**Symbols:**

```
ffffffff811dc0a0-ffffffff811dc110: trace_probe_add_file (STB_GLOBAL)
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
