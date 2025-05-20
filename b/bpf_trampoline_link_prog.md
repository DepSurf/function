# Function: <code>bpf_trampoline_link_prog</code>

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
In <code>5.4</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int bpf_trampoline_link_prog(struct bpf_prog *prog);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/trampoline.c (ffffffff8121f420)
Location: kernel/bpf/trampoline.c:259
Inline: False
Direct callers:
  - kernel/bpf/syscall.c:bpf_raw_tracepoint_open
```
**Symbols:**

```
ffffffff8121f420-ffffffff8121f5cc: bpf_trampoline_link_prog (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int bpf_trampoline_link_prog(struct bpf_prog *prog, struct bpf_trampoline *tr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/trampoline.c (ffffffff81222de0)
Location: kernel/bpf/trampoline.c:377
Inline: False
Direct callers:
  - kernel/bpf/syscall.c:bpf_tracing_prog_attach
```
**Symbols:**

```
ffffffff81222de0-ffffffff81222fb9: bpf_trampoline_link_prog (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int bpf_trampoline_link_prog(struct bpf_prog *prog, struct bpf_trampoline *tr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/trampoline.c (ffffffff81227880)
Location: kernel/bpf/trampoline.c:407
Inline: False
Direct callers:
  - kernel/bpf/syscall.c:bpf_tracing_prog_attach
```
**Symbols:**

```
ffffffff81227880-ffffffff81227a52: bpf_trampoline_link_prog (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int bpf_trampoline_link_prog(struct bpf_prog *prog, struct bpf_trampoline *tr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/trampoline.c (ffffffff8125fab0)
Location: kernel/bpf/trampoline.c:413
Inline: False
Direct callers:
  - kernel/bpf/syscall.c:bpf_tracing_prog_attach
```
**Symbols:**

```
ffffffff8125fab0-ffffffff8125fcbb: bpf_trampoline_link_prog (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int bpf_trampoline_link_prog(struct bpf_tramp_link *link, struct bpf_trampoline *tr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/trampoline.c (ffffffff812aa220)
Location: kernel/bpf/trampoline.c:413
Inline: False
Direct callers:
  - kernel/bpf/syscall.c:bpf_tracing_prog_attach
```
**Symbols:**

```
ffffffff812aa220-ffffffff812aa4ed: bpf_trampoline_link_prog (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int bpf_trampoline_link_prog(struct bpf_tramp_link *link, struct bpf_trampoline *tr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/trampoline.c (ffffffff81309790)
Location: kernel/bpf/trampoline.c:582
Inline: False
Direct callers:
  - kernel/bpf/syscall.c:bpf_tracing_prog_attach
```
**Symbols:**

```
ffffffff81309790-ffffffff813097d6: bpf_trampoline_link_prog (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int bpf_trampoline_link_prog(struct bpf_tramp_link *link, struct bpf_trampoline *tr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/trampoline.c (ffffffff813385c0)
Location: kernel/bpf/trampoline.c:560
Inline: False
Direct callers:
  - kernel/bpf/syscall.c:bpf_tracing_prog_attach
```
**Symbols:**

```
ffffffff813385c0-ffffffff81338606: bpf_trampoline_link_prog (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int bpf_trampoline_link_prog(struct bpf_tramp_link *link, struct bpf_trampoline *tr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/trampoline.c (ffffffff8135e6c0)
Location: kernel/bpf/trampoline.c:571
Inline: False
Direct callers:
  - kernel/bpf/syscall.c:bpf_tracing_prog_attach
```
**Symbols:**

```
ffffffff8135e6c0-ffffffff8135e706: bpf_trampoline_link_prog (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
In <code>arm64</code>: Absent ⚠️
</li>
<li>
In <code>armhf</code>: Absent ⚠️
</li>
<li>
In <code>ppc64el</code>: Absent ⚠️
</li>
<li>
In <code>riscv64</code>: Absent ⚠️
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
In <code>aws</code>: Absent ⚠️
</li>
<li>
In <code>azure</code>: Absent ⚠️
</li>
<li>
In <code>gcp</code>: Absent ⚠️
</li>
<li>
In <code>lowlatency</code>: Absent ⚠️
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
<details>
<summary>Changed between <code>5.8</code> and <code>5.11</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>struct bpf_trampoline *tr</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>5.11</code> and <code>5.13</code> ✅
</li>
<li>
No changes between <code>5.13</code> and <code>5.15</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>5.15</code> and <code>5.19</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>struct bpf_tramp_link *link</code>
</li>
<li>
<b>Param removed. </b>
<code>struct bpf_prog *prog</code>
</li>
</ul>
</details>
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
