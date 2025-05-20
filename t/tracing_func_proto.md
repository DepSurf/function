# Function: <code>tracing_func_proto</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
const struct bpf_func_proto *tracing_func_proto(enum bpf_func_id func_id);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/bpf_trace.c (ffffffff81174250)
Location: kernel/trace/bpf_trace.c:379
Inline: False
Direct callers:
  - kernel/trace/bpf_trace.c:tp_prog_func_proto
  - kernel/trace/bpf_trace.c:kprobe_prog_func_proto
```
**Symbols:**

```
ffffffff81174250-ffffffff81174332: tracing_func_proto (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
const struct bpf_func_proto *tracing_func_proto(enum bpf_func_id func_id);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/bpf_trace.c (ffffffff8117fcf0)
Location: kernel/trace/bpf_trace.c:398
Inline: False
Direct callers:
  - kernel/trace/bpf_trace.c:tp_prog_func_proto
  - kernel/trace/bpf_trace.c:kprobe_prog_func_proto
```
**Symbols:**

```
ffffffff8117fcf0-ffffffff8117fded: tracing_func_proto (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
const struct bpf_func_proto *tracing_func_proto(enum bpf_func_id func_id);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/bpf_trace.c (ffffffff81182b60)
Location: kernel/trace/bpf_trace.c:462
Inline: False
Direct callers:
  - kernel/trace/bpf_trace.c:tp_prog_func_proto
  - kernel/trace/bpf_trace.c:kprobe_prog_func_proto
```
**Symbols:**

```
ffffffff81182b60-ffffffff81182c66: tracing_func_proto (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
const struct bpf_func_proto *tracing_func_proto(enum bpf_func_id func_id);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/bpf_trace.c (ffffffff811905a0)
Location: kernel/trace/bpf_trace.c:506
Inline: False
Direct callers:
  - kernel/trace/bpf_trace.c:pe_prog_func_proto
  - kernel/trace/bpf_trace.c:tp_prog_func_proto
  - kernel/trace/bpf_trace.c:kprobe_prog_func_proto
```
**Symbols:**

```
ffffffff811905a0-ffffffff811906ac: tracing_func_proto (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/trace/bpf_trace.c (0)
Location: kernel/trace/bpf_trace.c:528
Inline: True
Direct callers:
  - kernel/trace/bpf_trace.c:raw_tp_prog_func_proto
  - kernel/trace/bpf_trace.c:pe_prog_func_proto
  - kernel/trace/bpf_trace.c:tp_prog_func_proto
  - kernel/trace/bpf_trace.c:kprobe_prog_func_proto
```
**Symbols:**

```
ffffffff811a5700-ffffffff811a57ee: tracing_func_proto.isra.7 (STB_LOCAL)
ffffffff811a6069-ffffffff811a6097: tracing_func_proto.isra.7.cold.9 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/trace/bpf_trace.c (0)
Location: kernel/trace/bpf_trace.c:564
Inline: True
Direct callers:
  - kernel/trace/bpf_trace.c:raw_tp_prog_func_proto
  - kernel/trace/bpf_trace.c:pe_prog_func_proto
  - kernel/trace/bpf_trace.c:tp_prog_func_proto
  - kernel/trace/bpf_trace.c:kprobe_prog_func_proto
```
**Symbols:**

```
ffffffff811b39a0-ffffffff811b3aff: tracing_func_proto.isra.12 (STB_LOCAL)
ffffffff811b4419-ffffffff811b4447: tracing_func_proto.isra.12.cold.14 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/trace/bpf_trace.c (0)
Location: kernel/trace/bpf_trace.c:661
Inline: True
Direct callers:
  - kernel/trace/bpf_trace.c:raw_tp_prog_func_proto
  - kernel/trace/bpf_trace.c:pe_prog_func_proto
  - kernel/trace/bpf_trace.c:tp_prog_func_proto
  - kernel/trace/bpf_trace.c:kprobe_prog_func_proto
```
**Symbols:**

```
ffffffff811c2740-ffffffff811c2907: tracing_func_proto.isra.0 (STB_LOCAL)
ffffffff811c342b-ffffffff811c3459: tracing_func_proto.isra.0.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/trace/bpf_trace.c (0)
Location: kernel/trace/bpf_trace.c:685
Inline: True
Direct callers:
  - kernel/trace/bpf_trace.c:raw_tp_prog_func_proto
  - kernel/trace/bpf_trace.c:pe_prog_func_proto
  - kernel/trace/bpf_trace.c:tp_prog_func_proto
  - kernel/trace/bpf_trace.c:kprobe_prog_func_proto
```
**Symbols:**

```
ffffffff811cdeb0-ffffffff811ce077: tracing_func_proto.isra.0 (STB_LOCAL)
ffffffff811cebdb-ffffffff811cec09: tracing_func_proto.isra.0.cold (STB_LOCAL)
```
</details>
</li>
<li>
In <code>5.8</code>: Absent ⚠️
</li>
<li>
In <code>5.11</code>: Absent ⚠️
</li>
<li>
In <code>5.13</code>: Absent ⚠️
</li>
<li>
In <code>5.15</code>: Absent ⚠️
</li>
<li>
In <code>5.19</code>: Absent ⚠️
</li>
<li>
In <code>6.2</code>: Absent ⚠️
</li>
<li>
In <code>6.5</code>: Absent ⚠️
</li>
<li>
In <code>6.8</code>: Absent ⚠️
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/trace/bpf_trace.c (ffff80001024ce80)
Location: kernel/trace/bpf_trace.c:685
Inline: True
Direct callers:
  - kernel/trace/bpf_trace.c:raw_tp_prog_func_proto
  - kernel/trace/bpf_trace.c:pe_prog_func_proto
  - kernel/trace/bpf_trace.c:tp_prog_func_proto
  - kernel/trace/bpf_trace.c:kprobe_prog_func_proto
```
**Symbols:**

```
ffff80001024ce80-ffff80001024d028: tracing_func_proto.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/trace/bpf_trace.c (c0480c5c)
Location: kernel/trace/bpf_trace.c:685
Inline: True
Direct callers:
  - kernel/trace/bpf_trace.c:raw_tp_prog_func_proto
  - kernel/trace/bpf_trace.c:pe_prog_func_proto
  - kernel/trace/bpf_trace.c:tp_prog_func_proto
  - kernel/trace/bpf_trace.c:kprobe_prog_func_proto
```
**Symbols:**

```
c0480c5c-c0480f94: tracing_func_proto.constprop.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/trace/bpf_trace.c (c0000000002e9bf0)
Location: kernel/trace/bpf_trace.c:685
Inline: True
Direct callers:
  - kernel/trace/bpf_trace.c:raw_tp_prog_func_proto
  - kernel/trace/bpf_trace.c:pe_prog_func_proto
  - kernel/trace/bpf_trace.c:pe_prog_func_proto
  - kernel/trace/bpf_trace.c:tp_prog_func_proto
  - kernel/trace/bpf_trace.c:kprobe_prog_func_proto
```
**Symbols:**

```
c0000000002e9bf0-c0000000002e9f7c: tracing_func_proto.isra.0 (STB_LOCAL)
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
<summary>In <code>aws</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/trace/bpf_trace.c (0)
Location: kernel/trace/bpf_trace.c:685
Inline: True
Direct callers:
  - kernel/trace/bpf_trace.c:raw_tp_prog_func_proto
  - kernel/trace/bpf_trace.c:pe_prog_func_proto
  - kernel/trace/bpf_trace.c:tp_prog_func_proto
  - kernel/trace/bpf_trace.c:kprobe_prog_func_proto
```
**Symbols:**

```
ffffffff811c64d0-ffffffff811c6697: tracing_func_proto.isra.0 (STB_LOCAL)
ffffffff811c71fb-ffffffff811c7229: tracing_func_proto.isra.0.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/trace/bpf_trace.c (0)
Location: kernel/trace/bpf_trace.c:685
Inline: True
Direct callers:
  - kernel/trace/bpf_trace.c:raw_tp_prog_func_proto
  - kernel/trace/bpf_trace.c:pe_prog_func_proto
  - kernel/trace/bpf_trace.c:tp_prog_func_proto
  - kernel/trace/bpf_trace.c:kprobe_prog_func_proto
```
**Symbols:**

```
ffffffff811b92b0-ffffffff811b9477: tracing_func_proto.isra.0 (STB_LOCAL)
ffffffff811b9fdb-ffffffff811ba009: tracing_func_proto.isra.0.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/trace/bpf_trace.c (0)
Location: kernel/trace/bpf_trace.c:685
Inline: True
Direct callers:
  - kernel/trace/bpf_trace.c:raw_tp_prog_func_proto
  - kernel/trace/bpf_trace.c:pe_prog_func_proto
  - kernel/trace/bpf_trace.c:tp_prog_func_proto
  - kernel/trace/bpf_trace.c:kprobe_prog_func_proto
```
**Symbols:**

```
ffffffff811c42a0-ffffffff811c4467: tracing_func_proto.isra.0 (STB_LOCAL)
ffffffff811c4fcb-ffffffff811c4ff9: tracing_func_proto.isra.0.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/trace/bpf_trace.c (0)
Location: kernel/trace/bpf_trace.c:685
Inline: True
Direct callers:
  - kernel/trace/bpf_trace.c:raw_tp_prog_func_proto
  - kernel/trace/bpf_trace.c:pe_prog_func_proto
  - kernel/trace/bpf_trace.c:tp_prog_func_proto
  - kernel/trace/bpf_trace.c:kprobe_prog_func_proto
```
**Symbols:**

```
ffffffff811d1bc0-ffffffff811d1d87: tracing_func_proto.isra.0 (STB_LOCAL)
ffffffff811d322b-ffffffff811d3259: tracing_func_proto.isra.0.cold (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>4.8</code> and <code>4.10</code> ✅
</li>
<li>
No changes between <code>4.10</code> and <code>4.13</code> ✅
</li>
<li>
No changes between <code>4.13</code> and <code>4.15</code> ✅
</li>
</ul>
