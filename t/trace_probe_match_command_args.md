# Function: <code>trace_probe_match_command_args</code>

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
In <code>5.3</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
bool trace_probe_match_command_args(struct trace_probe *tp, int argc, const char **argv);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_probe.c (ffffffff811d7c90)
Location: kernel/trace/trace_probe.c:1120
Inline: False
Direct callers:
  - kernel/trace/trace_kprobe.c:trace_kprobe_match
  - kernel/trace/trace_uprobe.c:trace_uprobe_match
```
**Symbols:**

```
ffffffff811d7c90-ffffffff811d7d28: trace_probe_match_command_args (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
bool trace_probe_match_command_args(struct trace_probe *tp, int argc, const char **argv);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_probe.c (ffffffff811f4640)
Location: kernel/trace/trace_probe.c:1120
Inline: False
Direct callers:
  - kernel/trace/trace_kprobe.c:trace_kprobe_match
  - kernel/trace/trace_uprobe.c:trace_uprobe_match
```
**Symbols:**

```
ffffffff811f4640-ffffffff811f46d8: trace_probe_match_command_args (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
bool trace_probe_match_command_args(struct trace_probe *tp, int argc, const char **argv);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_probe.c (ffffffff811f2ff0)
Location: kernel/trace/trace_probe.c:1120
Inline: False
Direct callers:
  - kernel/trace/trace_kprobe.c:trace_kprobe_match
  - kernel/trace/trace_uprobe.c:trace_uprobe_match
```
**Symbols:**

```
ffffffff811f2ff0-ffffffff811f3088: trace_probe_match_command_args (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
bool trace_probe_match_command_args(struct trace_probe *tp, int argc, const char **argv);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_probe.c (ffffffff811f3e70)
Location: kernel/trace/trace_probe.c:1120
Inline: False
Direct callers:
  - kernel/trace/trace_kprobe.c:trace_kprobe_match
  - kernel/trace/trace_uprobe.c:trace_uprobe_match
```
**Symbols:**

```
ffffffff811f3e70-ffffffff811f3f08: trace_probe_match_command_args (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
bool trace_probe_match_command_args(struct trace_probe *tp, int argc, const char **argv);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_probe.c (ffffffff812251c0)
Location: kernel/trace/trace_probe.c:1177
Inline: False
Direct callers:
  - kernel/trace/trace_eprobe.c:eprobe_dyn_event_match
  - kernel/trace/trace_kprobe.c:trace_kprobe_match
  - kernel/trace/trace_uprobe.c:trace_uprobe_match
```
**Symbols:**

```
ffffffff812251c0-ffffffff81225258: trace_probe_match_command_args (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
bool trace_probe_match_command_args(struct trace_probe *tp, int argc, const char **argv);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_probe.c (ffffffff81265090)
Location: kernel/trace/trace_probe.c:1183
Inline: False
Direct callers:
  - kernel/trace/trace_eprobe.c:eprobe_dyn_event_match
  - kernel/trace/trace_kprobe.c:trace_kprobe_match
  - kernel/trace/trace_uprobe.c:trace_uprobe_match_command_head
```
**Symbols:**

```
ffffffff81265090-ffffffff8126514d: trace_probe_match_command_args (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
bool trace_probe_match_command_args(struct trace_probe *tp, int argc, const char **argv);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_probe.c (ffffffff812b6c80)
Location: kernel/trace/trace_probe.c:1206
Inline: False
Direct callers:
  - kernel/trace/trace_eprobe.c:eprobe_dyn_event_match
  - kernel/trace/trace_kprobe.c:trace_kprobe_match
  - kernel/trace/trace_uprobe.c:trace_uprobe_match_command_head
```
**Symbols:**

```
ffffffff812b6c80-ffffffff812b6d3d: trace_probe_match_command_args (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
bool trace_probe_match_command_args(struct trace_probe *tp, int argc, const char **argv);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_probe.c (ffffffff812da170)
Location: kernel/trace/trace_probe.c:1687
Inline: False
Direct callers:
  - kernel/trace/trace_eprobe.c:eprobe_dyn_event_match
  - kernel/trace/trace_kprobe.c:trace_kprobe_match
  - kernel/trace/trace_uprobe.c:trace_uprobe_match_command_head
  - kernel/trace/trace_fprobe.c:trace_fprobe_match
```
**Symbols:**

```
ffffffff812da170-ffffffff812da22d: trace_probe_match_command_args (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
bool trace_probe_match_command_args(struct trace_probe *tp, int argc, const char **argv);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_probe.c (ffffffff812f8100)
Location: kernel/trace/trace_probe.c:1924
Inline: False
Direct callers:
  - kernel/trace/trace_eprobe.c:eprobe_dyn_event_match
  - kernel/trace/trace_kprobe.c:trace_kprobe_match
  - kernel/trace/trace_uprobe.c:trace_uprobe_match_command_head
  - kernel/trace/trace_fprobe.c:trace_fprobe_match
```
**Symbols:**

```
ffffffff812f8100-ffffffff812f81bd: trace_probe_match_command_args (STB_GLOBAL)
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
bool trace_probe_match_command_args(struct trace_probe *tp, int argc, const char **argv);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_probe.c (ffff800010258030)
Location: kernel/trace/trace_probe.c:1120
Inline: False
Direct callers:
  - kernel/trace/trace_kprobe.c:trace_kprobe_match
  - kernel/trace/trace_uprobe.c:trace_uprobe_match
```
**Symbols:**

```
ffff800010258030-ffff800010258108: trace_probe_match_command_args (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
bool trace_probe_match_command_args(struct trace_probe *tp, int argc, const char **argv);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_probe.c (c048b11c)
Location: kernel/trace/trace_probe.c:1120
Inline: False
Direct callers:
  - kernel/trace/trace_kprobe.c:trace_kprobe_match
  - kernel/trace/trace_uprobe.c:trace_uprobe_match
```
**Symbols:**

```
c048b11c-c048b1e0: trace_probe_match_command_args (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
bool trace_probe_match_command_args(struct trace_probe *tp, int argc, const char **argv);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_probe.c (c0000000002fa320)
Location: kernel/trace/trace_probe.c:1120
Inline: False
Direct callers:
  - kernel/trace/trace_kprobe.c:trace_kprobe_match
  - kernel/trace/trace_uprobe.c:trace_uprobe_match
```
**Symbols:**

```
c0000000002fa320-c0000000002fa620: trace_probe_match_command_args (STB_GLOBAL)
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
bool trace_probe_match_command_args(struct trace_probe *tp, int argc, const char **argv);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_probe.c (ffffffff811d02b0)
Location: kernel/trace/trace_probe.c:1120
Inline: False
Direct callers:
  - kernel/trace/trace_kprobe.c:trace_kprobe_match
  - kernel/trace/trace_uprobe.c:trace_uprobe_match
```
**Symbols:**

```
ffffffff811d02b0-ffffffff811d0348: trace_probe_match_command_args (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
bool trace_probe_match_command_args(struct trace_probe *tp, int argc, const char **argv);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_probe.c (ffffffff811c3080)
Location: kernel/trace/trace_probe.c:1120
Inline: False
Direct callers:
  - kernel/trace/trace_kprobe.c:trace_kprobe_match
  - kernel/trace/trace_uprobe.c:trace_uprobe_match
```
**Symbols:**

```
ffffffff811c3080-ffffffff811c3118: trace_probe_match_command_args (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
bool trace_probe_match_command_args(struct trace_probe *tp, int argc, const char **argv);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_probe.c (ffffffff811ce080)
Location: kernel/trace/trace_probe.c:1120
Inline: False
Direct callers:
  - kernel/trace/trace_kprobe.c:trace_kprobe_match
  - kernel/trace/trace_uprobe.c:trace_uprobe_match
```
**Symbols:**

```
ffffffff811ce080-ffffffff811ce118: trace_probe_match_command_args (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
bool trace_probe_match_command_args(struct trace_probe *tp, int argc, const char **argv);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_probe.c (ffffffff811dc2e0)
Location: kernel/trace/trace_probe.c:1120
Inline: False
Direct callers:
  - kernel/trace/trace_kprobe.c:trace_kprobe_match
  - kernel/trace/trace_uprobe.c:trace_uprobe_match
```
**Symbols:**

```
ffffffff811dc2e0-ffffffff811dc378: trace_probe_match_command_args (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
