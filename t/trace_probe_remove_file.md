# Function: <code>trace_probe_remove_file</code>

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
int trace_probe_remove_file(struct trace_probe *tp, struct trace_event_file *file);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_probe.c (ffffffff811cbaa0)
Location: kernel/trace/trace_probe.c:973
Inline: False
Direct callers:
  - kernel/trace/trace_kprobe.c:disable_trace_kprobe
  - kernel/trace/trace_uprobe.c:trace_uprobe_register
  - kernel/trace/trace_uprobe.c:probe_event_enable
```
**Symbols:**

```
ffffffff811cbaa0-ffffffff811cbb38: trace_probe_remove_file (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int trace_probe_remove_file(struct trace_probe *tp, struct trace_event_file *file);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_probe.c (ffffffff811d7b00)
Location: kernel/trace/trace_probe.c:1076
Inline: False
Direct callers:
  - kernel/trace/trace_kprobe.c:disable_trace_kprobe
  - kernel/trace/trace_kprobe.c:enable_trace_kprobe
  - kernel/trace/trace_uprobe.c:probe_event_disable
  - kernel/trace/trace_uprobe.c:probe_event_enable
```
**Symbols:**

```
ffffffff811d7b00-ffffffff811d7bb6: trace_probe_remove_file (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int trace_probe_remove_file(struct trace_probe *tp, struct trace_event_file *file);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_probe.c (ffffffff811f44a0)
Location: kernel/trace/trace_probe.c:1076
Inline: False
Direct callers:
  - kernel/trace/trace_kprobe.c:disable_trace_kprobe
  - kernel/trace/trace_kprobe.c:enable_trace_kprobe
  - kernel/trace/trace_uprobe.c:probe_event_disable
  - kernel/trace/trace_uprobe.c:probe_event_enable
```
**Symbols:**

```
ffffffff811f44a0-ffffffff811f4556: trace_probe_remove_file (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int trace_probe_remove_file(struct trace_probe *tp, struct trace_event_file *file);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_probe.c (ffffffff811f2e50)
Location: kernel/trace/trace_probe.c:1076
Inline: False
Direct callers:
  - kernel/trace/trace_kprobe.c:disable_trace_kprobe
  - kernel/trace/trace_kprobe.c:enable_trace_kprobe
  - kernel/trace/trace_uprobe.c:probe_event_disable
  - kernel/trace/trace_uprobe.c:probe_event_enable
```
**Symbols:**

```
ffffffff811f2e50-ffffffff811f2f06: trace_probe_remove_file (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int trace_probe_remove_file(struct trace_probe *tp, struct trace_event_file *file);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_probe.c (ffffffff811f3cd0)
Location: kernel/trace/trace_probe.c:1076
Inline: False
Direct callers:
  - kernel/trace/trace_kprobe.c:disable_trace_kprobe
  - kernel/trace/trace_kprobe.c:enable_trace_kprobe
  - kernel/trace/trace_uprobe.c:probe_event_disable
  - kernel/trace/trace_uprobe.c:probe_event_enable
```
**Symbols:**

```
ffffffff811f3cd0-ffffffff811f3d82: trace_probe_remove_file (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int trace_probe_remove_file(struct trace_probe *tp, struct trace_event_file *file);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_probe.c (ffffffff81225020)
Location: kernel/trace/trace_probe.c:1133
Inline: False
Direct callers:
  - kernel/trace/trace_eprobe.c:eprobe_register
  - kernel/trace/trace_eprobe.c:enable_trace_eprobe
  - kernel/trace/trace_kprobe.c:enable_trace_kprobe
  - kernel/trace/trace_uprobe.c:probe_event_enable
```
**Symbols:**

```
ffffffff81225020-ffffffff812250d2: trace_probe_remove_file (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int trace_probe_remove_file(struct trace_probe *tp, struct trace_event_file *file);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_probe.c (ffffffff81264f10)
Location: kernel/trace/trace_probe.c:1140
Inline: False
Direct callers:
  - kernel/trace/trace_eprobe.c:eprobe_register
  - kernel/trace/trace_eprobe.c:enable_trace_eprobe
  - kernel/trace/trace_kprobe.c:enable_trace_kprobe
  - kernel/trace/trace_uprobe.c:probe_event_enable
```
**Symbols:**

```
ffffffff81264f10-ffffffff81264fd0: trace_probe_remove_file (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int trace_probe_remove_file(struct trace_probe *tp, struct trace_event_file *file);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_probe.c (ffffffff812b6ae0)
Location: kernel/trace/trace_probe.c:1163
Inline: False
Direct callers:
  - kernel/trace/trace_eprobe.c:eprobe_register
  - kernel/trace/trace_eprobe.c:enable_trace_eprobe
  - kernel/trace/trace_kprobe.c:enable_trace_kprobe
  - kernel/trace/trace_uprobe.c:probe_event_enable
```
**Symbols:**

```
ffffffff812b6ae0-ffffffff812b6ba0: trace_probe_remove_file (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int trace_probe_remove_file(struct trace_probe *tp, struct trace_event_file *file);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_probe.c (ffffffff812d9fd0)
Location: kernel/trace/trace_probe.c:1644
Inline: False
Direct callers:
  - kernel/trace/trace_eprobe.c:eprobe_register
  - kernel/trace/trace_eprobe.c:enable_trace_eprobe
  - kernel/trace/trace_kprobe.c:enable_trace_kprobe
  - kernel/trace/trace_uprobe.c:probe_event_enable
  - kernel/trace/trace_fprobe.c:disable_trace_fprobe
```
**Symbols:**

```
ffffffff812d9fd0-ffffffff812da090: trace_probe_remove_file (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int trace_probe_remove_file(struct trace_probe *tp, struct trace_event_file *file);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_probe.c (ffffffff812f7f60)
Location: kernel/trace/trace_probe.c:1881
Inline: False
Direct callers:
  - kernel/trace/trace_eprobe.c:eprobe_register
  - kernel/trace/trace_eprobe.c:enable_trace_eprobe
  - kernel/trace/trace_kprobe.c:enable_trace_kprobe
  - kernel/trace/trace_uprobe.c:probe_event_enable
  - kernel/trace/trace_fprobe.c:disable_trace_fprobe
```
**Symbols:**

```
ffffffff812f7f60-ffffffff812f8020: trace_probe_remove_file (STB_GLOBAL)
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
int trace_probe_remove_file(struct trace_probe *tp, struct trace_event_file *file);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_probe.c (ffff800010257e88)
Location: kernel/trace/trace_probe.c:1076
Inline: False
Direct callers:
  - kernel/trace/trace_kprobe.c:disable_trace_kprobe
  - kernel/trace/trace_kprobe.c:enable_trace_kprobe
  - kernel/trace/trace_uprobe.c:probe_event_disable
  - kernel/trace/trace_uprobe.c:probe_event_enable
```
**Symbols:**

```
ffff800010257e88-ffff800010257f40: trace_probe_remove_file (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int trace_probe_remove_file(struct trace_probe *tp, struct trace_event_file *file);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_probe.c (c048afb4)
Location: kernel/trace/trace_probe.c:1076
Inline: False
Direct callers:
  - kernel/trace/trace_kprobe.c:disable_trace_kprobe
  - kernel/trace/trace_kprobe.c:enable_trace_kprobe
  - kernel/trace/trace_uprobe.c:probe_event_disable
  - kernel/trace/trace_uprobe.c:probe_event_enable
```
**Symbols:**

```
c048afb4-c048b05c: trace_probe_remove_file (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int trace_probe_remove_file(struct trace_probe *tp, struct trace_event_file *file);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_probe.c (c0000000002f9f20)
Location: kernel/trace/trace_probe.c:1076
Inline: False
Direct callers:
  - kernel/trace/trace_kprobe.c:disable_trace_kprobe
  - kernel/trace/trace_kprobe.c:enable_trace_kprobe
  - kernel/trace/trace_uprobe.c:probe_event_disable
  - kernel/trace/trace_uprobe.c:probe_event_enable
```
**Symbols:**

```
c0000000002f9f20-c0000000002fa03c: trace_probe_remove_file (STB_GLOBAL)
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
int trace_probe_remove_file(struct trace_probe *tp, struct trace_event_file *file);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_probe.c (ffffffff811d0120)
Location: kernel/trace/trace_probe.c:1076
Inline: False
Direct callers:
  - kernel/trace/trace_kprobe.c:disable_trace_kprobe
  - kernel/trace/trace_kprobe.c:enable_trace_kprobe
  - kernel/trace/trace_uprobe.c:probe_event_disable
  - kernel/trace/trace_uprobe.c:probe_event_enable
```
**Symbols:**

```
ffffffff811d0120-ffffffff811d01d6: trace_probe_remove_file (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int trace_probe_remove_file(struct trace_probe *tp, struct trace_event_file *file);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_probe.c (ffffffff811c2ef0)
Location: kernel/trace/trace_probe.c:1076
Inline: False
Direct callers:
  - kernel/trace/trace_kprobe.c:disable_trace_kprobe
  - kernel/trace/trace_kprobe.c:enable_trace_kprobe
  - kernel/trace/trace_uprobe.c:probe_event_disable
  - kernel/trace/trace_uprobe.c:probe_event_enable
```
**Symbols:**

```
ffffffff811c2ef0-ffffffff811c2fa6: trace_probe_remove_file (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int trace_probe_remove_file(struct trace_probe *tp, struct trace_event_file *file);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_probe.c (ffffffff811cdef0)
Location: kernel/trace/trace_probe.c:1076
Inline: False
Direct callers:
  - kernel/trace/trace_kprobe.c:disable_trace_kprobe
  - kernel/trace/trace_kprobe.c:enable_trace_kprobe
  - kernel/trace/trace_uprobe.c:probe_event_disable
  - kernel/trace/trace_uprobe.c:probe_event_enable
```
**Symbols:**

```
ffffffff811cdef0-ffffffff811cdfa6: trace_probe_remove_file (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int trace_probe_remove_file(struct trace_probe *tp, struct trace_event_file *file);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_probe.c (ffffffff811dc150)
Location: kernel/trace/trace_probe.c:1076
Inline: False
Direct callers:
  - kernel/trace/trace_kprobe.c:disable_trace_kprobe
  - kernel/trace/trace_kprobe.c:enable_trace_kprobe
  - kernel/trace/trace_uprobe.c:probe_event_disable
  - kernel/trace/trace_uprobe.c:probe_event_enable
```
**Symbols:**

```
ffffffff811dc150-ffffffff811dc206: trace_probe_remove_file (STB_GLOBAL)
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
