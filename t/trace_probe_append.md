# Function: <code>trace_probe_append</code>

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
int trace_probe_append(struct trace_probe *tp, struct trace_probe *to);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_probe.c (ffffffff811d7780)
Location: kernel/trace/trace_probe.c:955
Inline: False
Direct callers:
  - kernel/trace/trace_kprobe.c:register_trace_kprobe
  - kernel/trace/trace_uprobe.c:trace_uprobe_create
```
**Symbols:**

```
ffffffff811d7780-ffffffff811d781b: trace_probe_append (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int trace_probe_append(struct trace_probe *tp, struct trace_probe *to);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_probe.c (ffffffff811f40a0)
Location: kernel/trace/trace_probe.c:955
Inline: False
Direct callers:
  - kernel/trace/trace_kprobe.c:append_trace_kprobe
  - kernel/trace/trace_uprobe.c:register_trace_uprobe
```
**Symbols:**

```
ffffffff811f40a0-ffffffff811f4164: trace_probe_append (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int trace_probe_append(struct trace_probe *tp, struct trace_probe *to);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_probe.c (ffffffff811f2a50)
Location: kernel/trace/trace_probe.c:955
Inline: False
Direct callers:
  - kernel/trace/trace_kprobe.c:append_trace_kprobe
  - kernel/trace/trace_uprobe.c:register_trace_uprobe
```
**Symbols:**

```
ffffffff811f2a50-ffffffff811f2b14: trace_probe_append (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int trace_probe_append(struct trace_probe *tp, struct trace_probe *to);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_probe.c (ffffffff811f38e0)
Location: kernel/trace/trace_probe.c:955
Inline: False
Direct callers:
  - kernel/trace/trace_kprobe.c:append_trace_kprobe
  - kernel/trace/trace_uprobe.c:append_trace_uprobe
```
**Symbols:**

```
ffffffff811f38e0-ffffffff811f39a4: trace_probe_append (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int trace_probe_append(struct trace_probe *tp, struct trace_probe *to);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_probe.c (ffffffff81224ba0)
Location: kernel/trace/trace_probe.c:987
Inline: False
Direct callers:
  - kernel/trace/trace_kprobe.c:append_trace_kprobe
  - kernel/trace/trace_uprobe.c:append_trace_uprobe
```
**Symbols:**

```
ffffffff81224ba0-ffffffff81224c64: trace_probe_append (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int trace_probe_append(struct trace_probe *tp, struct trace_probe *to);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_probe.c (ffffffff81264a00)
Location: kernel/trace/trace_probe.c:994
Inline: False
Direct callers:
  - kernel/trace/trace_kprobe.c:append_trace_kprobe
  - kernel/trace/trace_uprobe.c:append_trace_uprobe
```
**Symbols:**

```
ffffffff81264a00-ffffffff81264ad8: trace_probe_append (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int trace_probe_append(struct trace_probe *tp, struct trace_probe *to);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_probe.c (ffffffff812b6560)
Location: kernel/trace/trace_probe.c:1017
Inline: False
Direct callers:
  - kernel/trace/trace_kprobe.c:append_trace_kprobe
  - kernel/trace/trace_uprobe.c:append_trace_uprobe
```
**Symbols:**

```
ffffffff812b6560-ffffffff812b6638: trace_probe_append (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int trace_probe_append(struct trace_probe *tp, struct trace_probe *to);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_probe.c (ffffffff812d9a50)
Location: kernel/trace/trace_probe.c:1498
Inline: False
Direct callers:
  - kernel/trace/trace_kprobe.c:append_trace_kprobe
  - kernel/trace/trace_uprobe.c:append_trace_uprobe
  - kernel/trace/trace_fprobe.c:append_trace_fprobe
```
**Symbols:**

```
ffffffff812d9a50-ffffffff812d9b28: trace_probe_append (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int trace_probe_append(struct trace_probe *tp, struct trace_probe *to);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_probe.c (ffffffff812f79b0)
Location: kernel/trace/trace_probe.c:1735
Inline: False
Direct callers:
  - kernel/trace/trace_kprobe.c:append_trace_kprobe
  - kernel/trace/trace_uprobe.c:append_trace_uprobe
  - kernel/trace/trace_fprobe.c:append_trace_fprobe
```
**Symbols:**

```
ffffffff812f79b0-ffffffff812f7a88: trace_probe_append (STB_GLOBAL)
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
int trace_probe_append(struct trace_probe *tp, struct trace_probe *to);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_probe.c (ffff800010257ae8)
Location: kernel/trace/trace_probe.c:955
Inline: False
Direct callers:
  - kernel/trace/trace_kprobe.c:register_trace_kprobe
  - kernel/trace/trace_uprobe.c:trace_uprobe_create
```
**Symbols:**

```
ffff800010257ae8-ffff800010257b80: trace_probe_append (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int trace_probe_append(struct trace_probe *tp, struct trace_probe *to);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_probe.c (c048ac64)
Location: kernel/trace/trace_probe.c:955
Inline: False
Direct callers:
  - kernel/trace/trace_kprobe.c:register_trace_kprobe
  - kernel/trace/trace_uprobe.c:trace_uprobe_create
```
**Symbols:**

```
c048ac64-c048acec: trace_probe_append (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int trace_probe_append(struct trace_probe *tp, struct trace_probe *to);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_probe.c (c0000000002f9a20)
Location: kernel/trace/trace_probe.c:955
Inline: False
Direct callers:
  - kernel/trace/trace_kprobe.c:register_trace_kprobe
  - kernel/trace/trace_uprobe.c:trace_uprobe_create
```
**Symbols:**

```
c0000000002f9a20-c0000000002f9ae4: trace_probe_append (STB_GLOBAL)
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
int trace_probe_append(struct trace_probe *tp, struct trace_probe *to);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_probe.c (ffffffff811cfda0)
Location: kernel/trace/trace_probe.c:955
Inline: False
Direct callers:
  - kernel/trace/trace_kprobe.c:register_trace_kprobe
  - kernel/trace/trace_uprobe.c:trace_uprobe_create
```
**Symbols:**

```
ffffffff811cfda0-ffffffff811cfe3b: trace_probe_append (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int trace_probe_append(struct trace_probe *tp, struct trace_probe *to);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_probe.c (ffffffff811c2b70)
Location: kernel/trace/trace_probe.c:955
Inline: False
Direct callers:
  - kernel/trace/trace_kprobe.c:register_trace_kprobe
  - kernel/trace/trace_uprobe.c:trace_uprobe_create
```
**Symbols:**

```
ffffffff811c2b70-ffffffff811c2c0b: trace_probe_append (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int trace_probe_append(struct trace_probe *tp, struct trace_probe *to);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_probe.c (ffffffff811cdb70)
Location: kernel/trace/trace_probe.c:955
Inline: False
Direct callers:
  - kernel/trace/trace_kprobe.c:register_trace_kprobe
  - kernel/trace/trace_uprobe.c:trace_uprobe_create
```
**Symbols:**

```
ffffffff811cdb70-ffffffff811cdc0b: trace_probe_append (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int trace_probe_append(struct trace_probe *tp, struct trace_probe *to);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_probe.c (ffffffff811dbdd0)
Location: kernel/trace/trace_probe.c:955
Inline: False
Direct callers:
  - kernel/trace/trace_kprobe.c:register_trace_kprobe
  - kernel/trace/trace_uprobe.c:trace_uprobe_create
```
**Symbols:**

```
ffffffff811dbdd0-ffffffff811dbe6b: trace_probe_append (STB_GLOBAL)
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
