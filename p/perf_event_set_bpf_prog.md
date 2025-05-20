# Function: <code>perf_event_set_bpf_prog</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff81182734)
Location: kernel/events/core.c:7074
Inline: True
Inline callers:
  - kernel/events/core.c:perf_ioctl
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff81194589)
Location: kernel/events/core.c:7672
Inline: True
Inline callers:
  - kernel/events/core.c:perf_ioctl
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff811a3f69)
Location: kernel/events/core.c:7853
Inline: True
Inline callers:
  - kernel/events/core.c:perf_ioctl
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff811ab5d2)
Location: kernel/events/core.c:8080
Inline: True
Inline callers:
  - kernel/events/core.c:perf_ioctl
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff811beef1)
Location: kernel/events/core.c:8071
Inline: True
Inline callers:
  - kernel/events/core.c:perf_ioctl
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff811df112)
Location: kernel/events/core.c:8590
Inline: True
Inline callers:
  - kernel/events/core.c:_perf_ioctl
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff811ef54f)
Location: kernel/events/core.c:8630
Inline: True
Inline callers:
  - kernel/events/core.c:_perf_ioctl
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff81206c76)
Location: kernel/events/core.c:8934
Inline: True
Inline callers:
  - kernel/events/core.c:_perf_ioctl
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff81213fe6)
Location: kernel/events/core.c:9050
Inline: True
Inline callers:
  - kernel/events/core.c:_perf_ioctl
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int perf_event_set_bpf_prog(struct perf_event *event, u32 prog_fd);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff812311f0)
Location: kernel/events/core.c:9598
Inline: False
Direct callers:
  - kernel/events/core.c:_perf_ioctl
```
**Symbols:**

```
ffffffff812311f0-ffffffff812313d4: perf_event_set_bpf_prog (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int perf_event_set_bpf_prog(struct perf_event *event, u32 prog_fd);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff8123ae10)
Location: kernel/events/core.c:9882
Inline: False
Direct callers:
  - kernel/events/core.c:_perf_ioctl
```
**Symbols:**

```
ffffffff8123ae10-ffffffff8123b043: perf_event_set_bpf_prog (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int perf_event_set_bpf_prog(struct perf_event *event, u32 prog_fd);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff8123f5d0)
Location: kernel/events/core.c:10012
Inline: False
Direct callers:
  - kernel/events/core.c:_perf_ioctl
```
**Symbols:**

```
ffffffff8123f5d0-ffffffff8123f803: perf_event_set_bpf_prog (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
int perf_event_set_bpf_prog(struct perf_event *event, struct bpf_prog *prog, u64 bpf_cookie);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff8128c480)
Location: kernel/events/core.c:10138
Inline: True
Direct callers:
  - kernel/bpf/syscall.c:link_create
  - kernel/events/core.c:_perf_ioctl
```
**Symbols:**

```
ffffffff8128c480-ffffffff8128c620: perf_event_set_bpf_prog (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
int perf_event_set_bpf_prog(struct perf_event *event, struct bpf_prog *prog, u64 bpf_cookie);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff812e1060)
Location: kernel/events/core.c:10073
Inline: True
Direct callers:
  - kernel/bpf/syscall.c:bpf_perf_link_attach
  - kernel/events/core.c:_perf_ioctl
```
**Symbols:**

```
ffffffff812e1060-ffffffff812e122d: perf_event_set_bpf_prog (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline, Transformation ⚠️</summary>

```c
int perf_event_set_bpf_prog(struct perf_event *event, struct bpf_prog *prog, u64 bpf_cookie);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/events/core.c (ffffffff81349651)
Location: kernel/events/core.c:10434
Inline: True
Direct callers:
  - kernel/bpf/syscall.c:bpf_perf_link_attach
  - kernel/events/core.c:_perf_ioctl
```
**Symbols:**

```
ffffffff82061e4c-ffffffff82061e67: perf_event_set_bpf_prog.cold (STB_LOCAL)
ffffffff81349570-ffffffff81349777: perf_event_set_bpf_prog (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline, Transformation ⚠️</summary>

```c
int perf_event_set_bpf_prog(struct perf_event *event, struct bpf_prog *prog, u64 bpf_cookie);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/events/core.c (ffffffff8137a661)
Location: kernel/events/core.c:10474
Inline: True
Direct callers:
  - kernel/bpf/syscall.c:bpf_perf_link_attach
  - kernel/events/core.c:_perf_ioctl
```
**Symbols:**

```
ffffffff820e15e6-ffffffff820e1601: perf_event_set_bpf_prog.cold (STB_LOCAL)
ffffffff8137a580-ffffffff8137a787: perf_event_set_bpf_prog (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline, Transformation ⚠️</summary>

```c
int perf_event_set_bpf_prog(struct perf_event *event, struct bpf_prog *prog, u64 bpf_cookie);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/events/core.c (ffffffff813a3861)
Location: kernel/events/core.c:10544
Inline: True
Direct callers:
  - kernel/bpf/syscall.c:bpf_perf_link_attach
  - kernel/events/core.c:_perf_ioctl
```
**Symbols:**

```
ffffffff821be049-ffffffff821be064: perf_event_set_bpf_prog.cold (STB_LOCAL)
ffffffff813a3780-ffffffff813a3987: perf_event_set_bpf_prog (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffff80001029e09c)
Location: kernel/events/core.c:9050
Inline: True
Inline callers:
  - kernel/events/core.c:_perf_ioctl
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (c04cda04)
Location: kernel/events/core.c:9050
Inline: True
Inline callers:
  - kernel/events/core.c:_perf_ioctl
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (c00000000034f1b0)
Location: kernel/events/core.c:9050
Inline: True
Inline callers:
  - kernel/events/core.c:_perf_ioctl
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
In kernel/events/core.c (ffffffe0001c8fbe)
Location: kernel/events/core.c:9050
Inline: True
Inline callers:
  - kernel/events/core.c:_perf_ioctl
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff8120c636)
Location: kernel/events/core.c:9050
Inline: True
Inline callers:
  - kernel/events/core.c:_perf_ioctl
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff811ff406)
Location: kernel/events/core.c:9050
Inline: True
Inline callers:
  - kernel/events/core.c:_perf_ioctl
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff8120a3d6)
Location: kernel/events/core.c:9050
Inline: True
Inline callers:
  - kernel/events/core.c:_perf_ioctl
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff812191a3)
Location: kernel/events/core.c:9050
Inline: True
Inline callers:
  - kernel/events/core.c:_perf_ioctl
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>5.8</code> and <code>5.11</code> ✅
</li>
<li>
No changes between <code>5.11</code> and <code>5.13</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>5.13</code> and <code>5.15</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>struct bpf_prog *prog</code>
</li>
<li>
<b>Param added. </b>
<code>u64 bpf_cookie</code>
</li>
<li>
<b>Param removed. </b>
<code>u32 prog_fd</code>
</li>
</ul>
</details>
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
