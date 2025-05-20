# Function: <code>trace_probe_unlink</code>

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
void trace_probe_unlink(struct trace_probe *tp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_probe.c (ffffffff811d7820)
Location: kernel/trace/trace_probe.c:969
Inline: False
Direct callers:
  - kernel/trace/trace_kprobe.c:register_trace_kprobe
  - kernel/trace/trace_probe.c:trace_probe_cleanup
  - kernel/trace/trace_uprobe.c:trace_uprobe_release
```
**Symbols:**

```
ffffffff811d7820-ffffffff811d786f: trace_probe_unlink (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void trace_probe_unlink(struct trace_probe *tp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_probe.c (ffffffff811f4170)
Location: kernel/trace/trace_probe.c:969
Inline: False
Direct callers:
  - kernel/trace/trace_kprobe.c:append_trace_kprobe
  - kernel/trace/trace_probe.c:trace_probe_init
  - kernel/trace/trace_uprobe.c:trace_uprobe_release
```
**Symbols:**

```
ffffffff811f4170-ffffffff811f41eb: trace_probe_unlink (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void trace_probe_unlink(struct trace_probe *tp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_probe.c (ffffffff811f2b20)
Location: kernel/trace/trace_probe.c:969
Inline: False
Direct callers:
  - kernel/trace/trace_kprobe.c:append_trace_kprobe
  - kernel/trace/trace_probe.c:trace_probe_init
  - kernel/trace/trace_uprobe.c:trace_uprobe_release
```
**Symbols:**

```
ffffffff811f2b20-ffffffff811f2b9b: trace_probe_unlink (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void trace_probe_unlink(struct trace_probe *tp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_probe.c (ffffffff811f39b0)
Location: kernel/trace/trace_probe.c:969
Inline: False
Direct callers:
  - kernel/trace/trace_kprobe.c:append_trace_kprobe
  - kernel/trace/trace_probe.c:trace_probe_init
  - kernel/trace/trace_uprobe.c:trace_uprobe_release
```
**Symbols:**

```
ffffffff811f39b0-ffffffff811f3a2b: trace_probe_unlink (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void trace_probe_unlink(struct trace_probe *tp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_probe.c (ffffffff81224c70)
Location: kernel/trace/trace_probe.c:1001
Inline: False
Direct callers:
  - kernel/trace/trace_eprobe.c:eprobe_dyn_event_release
  - kernel/trace/trace_kprobe.c:append_trace_kprobe
  - kernel/trace/trace_probe.c:trace_probe_init
  - kernel/trace/trace_uprobe.c:trace_uprobe_release
```
**Symbols:**

```
ffffffff81224c70-ffffffff81224ceb: trace_probe_unlink (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void trace_probe_unlink(struct trace_probe *tp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_probe.c (ffffffff81264ae0)
Location: kernel/trace/trace_probe.c:1008
Inline: False
Direct callers:
  - kernel/trace/trace_eprobe.c:eprobe_dyn_event_release
  - kernel/trace/trace_kprobe.c:append_trace_kprobe
  - kernel/trace/trace_probe.c:trace_probe_init
  - kernel/trace/trace_uprobe.c:trace_uprobe_release
```
**Symbols:**

```
ffffffff81264ae0-ffffffff81264b6f: trace_probe_unlink (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void trace_probe_unlink(struct trace_probe *tp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_probe.c (ffffffff812b6650)
Location: kernel/trace/trace_probe.c:1031
Inline: False
Direct callers:
  - kernel/trace/trace_eprobe.c:eprobe_dyn_event_release
  - kernel/trace/trace_kprobe.c:append_trace_kprobe
  - kernel/trace/trace_probe.c:trace_probe_init
  - kernel/trace/trace_uprobe.c:trace_uprobe_release
```
**Symbols:**

```
ffffffff812b6650-ffffffff812b66df: trace_probe_unlink (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void trace_probe_unlink(struct trace_probe *tp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_probe.c (ffffffff812d9b40)
Location: kernel/trace/trace_probe.c:1512
Inline: False
Direct callers:
  - kernel/trace/trace_eprobe.c:eprobe_dyn_event_release
  - kernel/trace/trace_kprobe.c:append_trace_kprobe
  - kernel/trace/trace_probe.c:trace_probe_init
  - kernel/trace/trace_uprobe.c:trace_uprobe_release
  - kernel/trace/trace_fprobe.c:append_trace_fprobe
```
**Symbols:**

```
ffffffff812d9b40-ffffffff812d9bcf: trace_probe_unlink (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void trace_probe_unlink(struct trace_probe *tp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_probe.c (ffffffff812f7aa0)
Location: kernel/trace/trace_probe.c:1749
Inline: False
Direct callers:
  - kernel/trace/trace_eprobe.c:eprobe_dyn_event_release
  - kernel/trace/trace_kprobe.c:append_trace_kprobe
  - kernel/trace/trace_probe.c:trace_probe_init
  - kernel/trace/trace_uprobe.c:trace_uprobe_release
  - kernel/trace/trace_fprobe.c:append_trace_fprobe
```
**Symbols:**

```
ffffffff812f7aa0-ffffffff812f7b2f: trace_probe_unlink (STB_GLOBAL)
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
void trace_probe_unlink(struct trace_probe *tp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_probe.c (ffff800010257b80)
Location: kernel/trace/trace_probe.c:969
Inline: False
Direct callers:
  - kernel/trace/trace_kprobe.c:register_trace_kprobe
  - kernel/trace/trace_probe.c:trace_probe_cleanup
  - kernel/trace/trace_uprobe.c:trace_uprobe_release
```
**Symbols:**

```
ffff800010257b80-ffff800010257bdc: trace_probe_unlink (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void trace_probe_unlink(struct trace_probe *tp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_probe.c (c048acec)
Location: kernel/trace/trace_probe.c:969
Inline: False
Direct callers:
  - kernel/trace/trace_kprobe.c:register_trace_kprobe
  - kernel/trace/trace_probe.c:trace_probe_cleanup
  - kernel/trace/trace_uprobe.c:trace_uprobe_release
```
**Symbols:**

```
c048acec-c048ad38: trace_probe_unlink (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void trace_probe_unlink(struct trace_probe *tp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_probe.c (c0000000002f9af0)
Location: kernel/trace/trace_probe.c:969
Inline: False
Direct callers:
  - kernel/trace/trace_kprobe.c:register_trace_kprobe
  - kernel/trace/trace_probe.c:trace_probe_cleanup
  - kernel/trace/trace_uprobe.c:trace_uprobe_release
```
**Symbols:**

```
c0000000002f9af0-c0000000002f9b78: trace_probe_unlink (STB_GLOBAL)
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
void trace_probe_unlink(struct trace_probe *tp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_probe.c (ffffffff811cfe40)
Location: kernel/trace/trace_probe.c:969
Inline: False
Direct callers:
  - kernel/trace/trace_kprobe.c:register_trace_kprobe
  - kernel/trace/trace_probe.c:trace_probe_cleanup
  - kernel/trace/trace_uprobe.c:trace_uprobe_release
```
**Symbols:**

```
ffffffff811cfe40-ffffffff811cfe8f: trace_probe_unlink (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void trace_probe_unlink(struct trace_probe *tp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_probe.c (ffffffff811c2c10)
Location: kernel/trace/trace_probe.c:969
Inline: False
Direct callers:
  - kernel/trace/trace_kprobe.c:register_trace_kprobe
  - kernel/trace/trace_probe.c:trace_probe_cleanup
  - kernel/trace/trace_uprobe.c:trace_uprobe_release
```
**Symbols:**

```
ffffffff811c2c10-ffffffff811c2c5f: trace_probe_unlink (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void trace_probe_unlink(struct trace_probe *tp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_probe.c (ffffffff811cdc10)
Location: kernel/trace/trace_probe.c:969
Inline: False
Direct callers:
  - kernel/trace/trace_kprobe.c:register_trace_kprobe
  - kernel/trace/trace_probe.c:trace_probe_cleanup
  - kernel/trace/trace_uprobe.c:trace_uprobe_release
```
**Symbols:**

```
ffffffff811cdc10-ffffffff811cdc5f: trace_probe_unlink (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void trace_probe_unlink(struct trace_probe *tp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_probe.c (ffffffff811dbe70)
Location: kernel/trace/trace_probe.c:969
Inline: False
Direct callers:
  - kernel/trace/trace_kprobe.c:register_trace_kprobe
  - kernel/trace/trace_probe.c:trace_probe_cleanup
  - kernel/trace/trace_uprobe.c:trace_uprobe_release
```
**Symbols:**

```
ffffffff811dbe70-ffffffff811dbebf: trace_probe_unlink (STB_GLOBAL)
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
