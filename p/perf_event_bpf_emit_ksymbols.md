# Function: <code>perf_event_bpf_emit_ksymbols</code>

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
void perf_event_bpf_emit_ksymbols(struct bpf_prog *prog, enum perf_bpf_event_type type);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff812091b0)
Location: kernel/events/core.c:7903
Inline: False
Direct callers:
  - kernel/events/core.c:perf_event_bpf_event
```
**Symbols:**

```
ffffffff812091b0-ffffffff8120927d: perf_event_bpf_emit_ksymbols (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void perf_event_bpf_emit_ksymbols(struct bpf_prog *prog, enum perf_bpf_event_type type);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff81216520)
Location: kernel/events/core.c:8019
Inline: False
Direct callers:
  - kernel/events/core.c:perf_event_bpf_event
```
**Symbols:**

```
ffffffff81216520-ffffffff812165ed: perf_event_bpf_emit_ksymbols (STB_LOCAL)
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
In kernel/events/core.c (ffffffff81242477)
Location: kernel/events/core.c:8570
Inline: True
Inline callers:
  - kernel/events/core.c:perf_event_bpf_event
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
In kernel/events/core.c (ffffffff8124cbc7)
Location: kernel/events/core.c:8752
Inline: True
Inline callers:
  - kernel/events/core.c:perf_event_bpf_event
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff81251227)
Location: kernel/events/core.c:8881
Inline: True
Inline callers:
  - kernel/events/core.c:perf_event_bpf_event
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff8128c027)
Location: kernel/events/core.c:9000
Inline: True
Inline callers:
  - kernel/events/core.c:perf_event_bpf_event
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff812e09dd)
Location: kernel/events/core.c:8905
Inline: True
Inline callers:
  - kernel/events/core.c:perf_event_bpf_event
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff81348e4d)
Location: kernel/events/core.c:9182
Inline: True
Inline callers:
  - kernel/events/core.c:perf_event_bpf_event
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff81379f8d)
Location: kernel/events/core.c:9210
Inline: True
Inline callers:
  - kernel/events/core.c:perf_event_bpf_event
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff813a324d)
Location: kernel/events/core.c:9280
Inline: True
Inline callers:
  - kernel/events/core.c:perf_event_bpf_event
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
void perf_event_bpf_emit_ksymbols(struct bpf_prog *prog, enum perf_bpf_event_type type);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffff8000102a0560)
Location: kernel/events/core.c:8019
Inline: False
Direct callers:
  - kernel/events/core.c:perf_event_bpf_event
```
**Symbols:**

```
ffff8000102a0560-ffff8000102a0634: perf_event_bpf_emit_ksymbols (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void perf_event_bpf_emit_ksymbols(struct bpf_prog *prog, enum perf_bpf_event_type type);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (c04d048c)
Location: kernel/events/core.c:8019
Inline: False
Direct callers:
  - kernel/events/core.c:perf_event_bpf_event
```
**Symbols:**

```
c04d048c-c04d0570: perf_event_bpf_emit_ksymbols (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void perf_event_bpf_emit_ksymbols(struct bpf_prog *prog, enum perf_bpf_event_type type);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (c000000000351e60)
Location: kernel/events/core.c:8019
Inline: False
Direct callers:
  - kernel/events/core.c:perf_event_bpf_event
```
**Symbols:**

```
c000000000351e60-c000000000351f78: perf_event_bpf_emit_ksymbols (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void perf_event_bpf_emit_ksymbols(struct bpf_prog *prog, enum perf_bpf_event_type type);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffe0001cfaae)
Location: kernel/events/core.c:8019
Inline: False
Direct callers:
  - kernel/events/core.c:perf_event_bpf_event
```
**Symbols:**

```
ffffffe0001cfaae-ffffffe0001cfb52: perf_event_bpf_emit_ksymbols (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: ✅</summary>

```c
void perf_event_bpf_emit_ksymbols(struct bpf_prog *prog, enum perf_bpf_event_type type);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff8120eb70)
Location: kernel/events/core.c:8019
Inline: False
Direct callers:
  - kernel/events/core.c:perf_event_bpf_event
```
**Symbols:**

```
ffffffff8120eb70-ffffffff8120ec3d: perf_event_bpf_emit_ksymbols (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void perf_event_bpf_emit_ksymbols(struct bpf_prog *prog, enum perf_bpf_event_type type);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff81201920)
Location: kernel/events/core.c:8019
Inline: False
Direct callers:
  - kernel/events/core.c:perf_event_bpf_event
```
**Symbols:**

```
ffffffff81201920-ffffffff812019ed: perf_event_bpf_emit_ksymbols (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void perf_event_bpf_emit_ksymbols(struct bpf_prog *prog, enum perf_bpf_event_type type);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff8120c910)
Location: kernel/events/core.c:8019
Inline: False
Direct callers:
  - kernel/events/core.c:perf_event_bpf_event
```
**Symbols:**

```
ffffffff8120c910-ffffffff8120c9dd: perf_event_bpf_emit_ksymbols (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void perf_event_bpf_emit_ksymbols(struct bpf_prog *prog, enum perf_bpf_event_type type);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff8121b790)
Location: kernel/events/core.c:8019
Inline: False
Direct callers:
  - kernel/events/core.c:perf_event_bpf_event
```
**Symbols:**

```
ffffffff8121b790-ffffffff8121b85d: perf_event_bpf_emit_ksymbols (STB_LOCAL)
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
<li>
No changes between <code>amd64</code> and <code>riscv64</code> ✅
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
