# Function: <code>bpf_probe_register</code>

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
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int bpf_probe_register(struct bpf_raw_event_map *btp, struct bpf_prog *prog);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/bpf_trace.c (ffffffff811a5eb0)
Location: kernel/trace/bpf_trace.c:1160
Inline: False
```
**Symbols:**

```
ffffffff811a5eb0-ffffffff811a5f08: bpf_probe_register (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int bpf_probe_register(struct bpf_raw_event_map *btp, struct bpf_prog *prog);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/bpf_trace.c (ffffffff811b42a0)
Location: kernel/trace/bpf_trace.c:1205
Inline: False
```
**Symbols:**

```
ffffffff811b42a0-ffffffff811b42d1: bpf_probe_register (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int bpf_probe_register(struct bpf_raw_event_map *btp, struct bpf_prog *prog);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/bpf_trace.c (ffffffff811c32b0)
Location: kernel/trace/bpf_trace.c:1377
Inline: False
```
**Symbols:**

```
ffffffff811c32b0-ffffffff811c32e9: bpf_probe_register (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int bpf_probe_register(struct bpf_raw_event_map *btp, struct bpf_prog *prog);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/bpf_trace.c (ffffffff811cea60)
Location: kernel/trace/bpf_trace.c:1401
Inline: False
```
**Symbols:**

```
ffffffff811cea60-ffffffff811cea99: bpf_probe_register (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int bpf_probe_register(struct bpf_raw_event_map *btp, struct bpf_prog *prog);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/bpf_trace.c (ffffffff811eaf80)
Location: kernel/trace/bpf_trace.c:1895
Inline: False
Direct callers:
  - kernel/bpf/syscall.c:bpf_raw_tracepoint_open
```
**Symbols:**

```
ffffffff811eaf80-ffffffff811eafb9: bpf_probe_register (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int bpf_probe_register(struct bpf_raw_event_map *btp, struct bpf_prog *prog);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/bpf_trace.c (ffffffff811e9120)
Location: kernel/trace/bpf_trace.c:2151
Inline: False
Direct callers:
  - kernel/bpf/syscall.c:bpf_raw_tracepoint_open
```
**Symbols:**

```
ffffffff811e9120-ffffffff811e9159: bpf_probe_register (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int bpf_probe_register(struct bpf_raw_event_map *btp, struct bpf_prog *prog);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/bpf_trace.c (ffffffff811ea010)
Location: kernel/trace/bpf_trace.c:1848
Inline: False
Direct callers:
  - kernel/bpf/syscall.c:bpf_raw_tracepoint_open
```
**Symbols:**

```
ffffffff811ea010-ffffffff811ea04e: bpf_probe_register (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int bpf_probe_register(struct bpf_raw_event_map *btp, struct bpf_prog *prog);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/bpf_trace.c (ffffffff8121ae40)
Location: kernel/trace/bpf_trace.c:1932
Inline: False
Direct callers:
  - kernel/bpf/syscall.c:bpf_raw_tracepoint_open
```
**Symbols:**

```
ffffffff8121ae40-ffffffff8121ae7e: bpf_probe_register (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int bpf_probe_register(struct bpf_raw_event_map *btp, struct bpf_prog *prog);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/bpf_trace.c (ffffffff81259b70)
Location: kernel/trace/bpf_trace.c:2113
Inline: False
Direct callers:
  - kernel/bpf/syscall.c:bpf_raw_tp_link_attach
```
**Symbols:**

```
ffffffff81259b70-ffffffff81259bcc: bpf_probe_register (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int bpf_probe_register(struct bpf_raw_event_map *btp, struct bpf_prog *prog);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/bpf_trace.c (ffffffff812a9df0)
Location: kernel/trace/bpf_trace.c:2336
Inline: False
Direct callers:
  - kernel/bpf/syscall.c:bpf_raw_tp_link_attach
```
**Symbols:**

```
ffffffff812a9df0-ffffffff812a9e4c: bpf_probe_register (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int bpf_probe_register(struct bpf_raw_event_map *btp, struct bpf_prog *prog);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/bpf_trace.c (ffffffff812cc660)
Location: kernel/trace/bpf_trace.c:2345
Inline: False
Direct callers:
  - kernel/bpf/syscall.c:bpf_raw_tp_link_attach
```
**Symbols:**

```
ffffffff812cc660-ffffffff812cc6bc: bpf_probe_register (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int bpf_probe_register(struct bpf_raw_event_map *btp, struct bpf_prog *prog);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/bpf_trace.c (ffffffff812e9ae0)
Location: kernel/trace/bpf_trace.c:2450
Inline: False
Direct callers:
  - kernel/bpf/syscall.c:bpf_raw_tp_link_attach
```
**Symbols:**

```
ffffffff812e9ae0-ffffffff812e9b3c: bpf_probe_register (STB_GLOBAL)
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
int bpf_probe_register(struct bpf_raw_event_map *btp, struct bpf_prog *prog);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/bpf_trace.c (ffff80001024ed20)
Location: kernel/trace/bpf_trace.c:1401
Inline: False
```
**Symbols:**

```
ffff80001024ed20-ffff80001024ed70: bpf_probe_register (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int bpf_probe_register(struct bpf_raw_event_map *btp, struct bpf_prog *prog);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/bpf_trace.c (c0481c74)
Location: kernel/trace/bpf_trace.c:1401
Inline: False
Direct callers:
  - kernel/bpf/syscall.c:bpf_raw_tracepoint_open
```
**Symbols:**

```
c0481c74-c0481cc4: bpf_probe_register (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int bpf_probe_register(struct bpf_raw_event_map *btp, struct bpf_prog *prog);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/bpf_trace.c (c0000000002eb320)
Location: kernel/trace/bpf_trace.c:1401
Inline: False
```
**Symbols:**

```
c0000000002eb320-c0000000002eb398: bpf_probe_register (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/bpf/syscall.c (0)
Location: include/linux/trace_events.h:507
Inline: True
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
int bpf_probe_register(struct bpf_raw_event_map *btp, struct bpf_prog *prog);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/bpf_trace.c (ffffffff811c7080)
Location: kernel/trace/bpf_trace.c:1401
Inline: False
```
**Symbols:**

```
ffffffff811c7080-ffffffff811c70b9: bpf_probe_register (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int bpf_probe_register(struct bpf_raw_event_map *btp, struct bpf_prog *prog);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/bpf_trace.c (ffffffff811b9e60)
Location: kernel/trace/bpf_trace.c:1401
Inline: False
```
**Symbols:**

```
ffffffff811b9e60-ffffffff811b9e99: bpf_probe_register (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int bpf_probe_register(struct bpf_raw_event_map *btp, struct bpf_prog *prog);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/bpf_trace.c (ffffffff811c4e50)
Location: kernel/trace/bpf_trace.c:1401
Inline: False
```
**Symbols:**

```
ffffffff811c4e50-ffffffff811c4e89: bpf_probe_register (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int bpf_probe_register(struct bpf_raw_event_map *btp, struct bpf_prog *prog);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/bpf_trace.c (ffffffff811d30b0)
Location: kernel/trace/bpf_trace.c:1401
Inline: False
```
**Symbols:**

```
ffffffff811d30b0-ffffffff811d30e9: bpf_probe_register (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>4.18</code> and <code>5.0</code> ✅
</li>
<li>
No changes between <code>5.0</code> and <code>5.3</code> ✅
</li>
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
