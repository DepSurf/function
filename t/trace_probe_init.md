# Function: <code>trace_probe_init</code>

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
int trace_probe_init(struct trace_probe *tp, const char *event, const char *group);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_probe.c (ffffffff811cb900)
Location: kernel/trace/trace_probe.c:904
Inline: False
Direct callers:
  - kernel/trace/trace_kprobe.c:alloc_trace_kprobe
  - kernel/trace/trace_uprobe.c:alloc_trace_uprobe
```
**Symbols:**

```
ffffffff811cb900-ffffffff811cb9a3: trace_probe_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int trace_probe_init(struct trace_probe *tp, const char *event, const char *group, bool alloc_filter);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_probe.c (ffffffff811d78c0)
Location: kernel/trace/trace_probe.c:988
Inline: False
Direct callers:
  - kernel/trace/trace_kprobe.c:alloc_trace_kprobe
  - kernel/trace/trace_uprobe.c:alloc_trace_uprobe
```
**Symbols:**

```
ffffffff811d78c0-ffffffff811d79e4: trace_probe_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int trace_probe_init(struct trace_probe *tp, const char *event, const char *group, bool alloc_filter);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_probe.c (ffffffff811f4240)
Location: kernel/trace/trace_probe.c:988
Inline: False
Direct callers:
  - kernel/trace/trace_kprobe.c:alloc_trace_kprobe
  - kernel/trace/trace_uprobe.c:alloc_trace_uprobe
```
**Symbols:**

```
ffffffff811f4240-ffffffff811f4388: trace_probe_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int trace_probe_init(struct trace_probe *tp, const char *event, const char *group, bool alloc_filter);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_probe.c (ffffffff811f2bf0)
Location: kernel/trace/trace_probe.c:988
Inline: False
Direct callers:
  - kernel/trace/trace_kprobe.c:alloc_trace_kprobe
  - kernel/trace/trace_uprobe.c:alloc_trace_uprobe
```
**Symbols:**

```
ffffffff811f2bf0-ffffffff811f2d38: trace_probe_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int trace_probe_init(struct trace_probe *tp, const char *event, const char *group, bool alloc_filter);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_probe.c (ffffffff811f3a80)
Location: kernel/trace/trace_probe.c:988
Inline: False
Direct callers:
  - kernel/trace/trace_kprobe.c:alloc_trace_kprobe
  - kernel/trace/trace_uprobe.c:alloc_trace_uprobe
```
**Symbols:**

```
ffffffff811f3a80-ffffffff811f3bb8: trace_probe_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int trace_probe_init(struct trace_probe *tp, const char *event, const char *group, bool alloc_filter);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_probe.c (ffffffff81224d40)
Location: kernel/trace/trace_probe.c:1020
Inline: False
Direct callers:
  - kernel/trace/trace_eprobe.c:__trace_eprobe_create
  - kernel/trace/trace_kprobe.c:alloc_trace_kprobe
  - kernel/trace/trace_uprobe.c:alloc_trace_uprobe
```
**Symbols:**

```
ffffffff81224d40-ffffffff81224e78: trace_probe_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int trace_probe_init(struct trace_probe *tp, const char *event, const char *group, bool alloc_filter);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_probe.c (ffffffff81264bd0)
Location: kernel/trace/trace_probe.c:1027
Inline: False
Direct callers:
  - kernel/trace/trace_eprobe.c:__trace_eprobe_create
  - kernel/trace/trace_kprobe.c:alloc_trace_kprobe
  - kernel/trace/trace_uprobe.c:alloc_trace_uprobe
```
**Symbols:**

```
ffffffff81264bd0-ffffffff81264d2c: trace_probe_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int trace_probe_init(struct trace_probe *tp, const char *event, const char *group, bool alloc_filter);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_probe.c (ffffffff812b6760)
Location: kernel/trace/trace_probe.c:1050
Inline: False
Direct callers:
  - kernel/trace/trace_eprobe.c:__trace_eprobe_create
  - kernel/trace/trace_kprobe.c:alloc_trace_kprobe
  - kernel/trace/trace_uprobe.c:alloc_trace_uprobe
```
**Symbols:**

```
ffffffff812b6760-ffffffff812b68bc: trace_probe_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int trace_probe_init(struct trace_probe *tp, const char *event, const char *group, bool alloc_filter);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_probe.c (ffffffff812d9c50)
Location: kernel/trace/trace_probe.c:1531
Inline: False
Direct callers:
  - kernel/trace/trace_eprobe.c:__trace_eprobe_create
  - kernel/trace/trace_kprobe.c:alloc_trace_kprobe
  - kernel/trace/trace_uprobe.c:alloc_trace_uprobe
  - kernel/trace/trace_fprobe.c:alloc_trace_fprobe
```
**Symbols:**

```
ffffffff812d9c50-ffffffff812d9dac: trace_probe_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int trace_probe_init(struct trace_probe *tp, const char *event, const char *group, bool alloc_filter);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_probe.c (ffffffff812f7bb0)
Location: kernel/trace/trace_probe.c:1768
Inline: False
Direct callers:
  - kernel/trace/trace_eprobe.c:__trace_eprobe_create
  - kernel/trace/trace_kprobe.c:alloc_trace_kprobe
  - kernel/trace/trace_uprobe.c:alloc_trace_uprobe
  - kernel/trace/trace_fprobe.c:alloc_trace_fprobe
```
**Symbols:**

```
ffffffff812f7bb0-ffffffff812f7d0c: trace_probe_init (STB_GLOBAL)
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
int trace_probe_init(struct trace_probe *tp, const char *event, const char *group, bool alloc_filter);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_probe.c (ffff800010257c48)
Location: kernel/trace/trace_probe.c:988
Inline: False
Direct callers:
  - kernel/trace/trace_kprobe.c:alloc_trace_kprobe
  - kernel/trace/trace_uprobe.c:alloc_trace_uprobe
```
**Symbols:**

```
ffff800010257c48-ffff800010257d60: trace_probe_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int trace_probe_init(struct trace_probe *tp, const char *event, const char *group, bool alloc_filter);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_probe.c (c048ad90)
Location: kernel/trace/trace_probe.c:988
Inline: False
Direct callers:
  - kernel/trace/trace_kprobe.c:alloc_trace_kprobe
  - kernel/trace/trace_uprobe.c:alloc_trace_uprobe
```
**Symbols:**

```
c048ad90-c048ae94: trace_probe_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int trace_probe_init(struct trace_probe *tp, const char *event, const char *group, bool alloc_filter);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_probe.c (c0000000002f9c10)
Location: kernel/trace/trace_probe.c:988
Inline: False
Direct callers:
  - kernel/trace/trace_kprobe.c:alloc_trace_kprobe
  - kernel/trace/trace_kprobe.c:alloc_trace_kprobe
  - kernel/trace/trace_uprobe.c:alloc_trace_uprobe
```
**Symbols:**

```
c0000000002f9c10-c0000000002f9d70: trace_probe_init (STB_GLOBAL)
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
int trace_probe_init(struct trace_probe *tp, const char *event, const char *group, bool alloc_filter);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_probe.c (ffffffff811cfee0)
Location: kernel/trace/trace_probe.c:988
Inline: False
Direct callers:
  - kernel/trace/trace_kprobe.c:alloc_trace_kprobe
  - kernel/trace/trace_uprobe.c:alloc_trace_uprobe
```
**Symbols:**

```
ffffffff811cfee0-ffffffff811d0004: trace_probe_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int trace_probe_init(struct trace_probe *tp, const char *event, const char *group, bool alloc_filter);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_probe.c (ffffffff811c2cb0)
Location: kernel/trace/trace_probe.c:988
Inline: False
Direct callers:
  - kernel/trace/trace_kprobe.c:alloc_trace_kprobe
  - kernel/trace/trace_uprobe.c:alloc_trace_uprobe
```
**Symbols:**

```
ffffffff811c2cb0-ffffffff811c2dd4: trace_probe_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int trace_probe_init(struct trace_probe *tp, const char *event, const char *group, bool alloc_filter);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_probe.c (ffffffff811cdcb0)
Location: kernel/trace/trace_probe.c:988
Inline: False
Direct callers:
  - kernel/trace/trace_kprobe.c:alloc_trace_kprobe
  - kernel/trace/trace_uprobe.c:alloc_trace_uprobe
```
**Symbols:**

```
ffffffff811cdcb0-ffffffff811cddd4: trace_probe_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int trace_probe_init(struct trace_probe *tp, const char *event, const char *group, bool alloc_filter);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_probe.c (ffffffff811dbf10)
Location: kernel/trace/trace_probe.c:988
Inline: False
Direct callers:
  - kernel/trace/trace_kprobe.c:alloc_trace_kprobe
  - kernel/trace/trace_uprobe.c:alloc_trace_uprobe
```
**Symbols:**

```
ffffffff811dbf10-ffffffff811dc034: trace_probe_init (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
<details>
<summary>Changed between <code>5.3</code> and <code>5.4</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>bool alloc_filter</code>
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
