# Function: <code>bpf_tracing_prog_attach</code>

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
<summary>In <code>5.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/bpf/syscall.c (ffffffff81201102)
Location: kernel/bpf/syscall.c:2530
Inline: True
Inline callers:
  - kernel/bpf/syscall.c:bpf_raw_tracepoint_open
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int bpf_tracing_prog_attach(struct bpf_prog *prog, int tgt_prog_fd, u32 btf_id);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/syscall.c (ffffffff81200320)
Location: kernel/bpf/syscall.c:2558
Inline: False
Direct callers:
  - kernel/bpf/syscall.c:link_create
  - kernel/bpf/syscall.c:bpf_raw_tracepoint_open
```
**Symbols:**

```
ffffffff81200320-ffffffff812007cc: bpf_tracing_prog_attach (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int bpf_tracing_prog_attach(struct bpf_prog *prog, int tgt_prog_fd, u32 btf_id);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/syscall.c (ffffffff81200cd0)
Location: kernel/bpf/syscall.c:2569
Inline: False
Direct callers:
  - kernel/bpf/syscall.c:link_create
  - kernel/bpf/syscall.c:bpf_raw_tracepoint_open
```
**Symbols:**

```
ffffffff81200cd0-ffffffff812011f5: bpf_tracing_prog_attach (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int bpf_tracing_prog_attach(struct bpf_prog *prog, int tgt_prog_fd, u32 btf_id);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/syscall.c (ffffffff81232a40)
Location: kernel/bpf/syscall.c:2679
Inline: False
Direct callers:
  - kernel/bpf/syscall.c:link_create
  - kernel/bpf/syscall.c:bpf_raw_tracepoint_open
```
**Symbols:**

```
ffffffff81232a40-ffffffff81232f65: bpf_tracing_prog_attach (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int bpf_tracing_prog_attach(struct bpf_prog *prog, int tgt_prog_fd, u32 btf_id, u64 bpf_cookie);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/syscall.c (ffffffff81275e50)
Location: kernel/bpf/syscall.c:2922
Inline: False
Direct callers:
  - kernel/bpf/syscall.c:link_create
  - kernel/bpf/syscall.c:bpf_raw_tp_link_attach
```
**Symbols:**

```
ffffffff81275e50-ffffffff81276369: bpf_tracing_prog_attach (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int bpf_tracing_prog_attach(struct bpf_prog *prog, int tgt_prog_fd, u32 btf_id, u64 bpf_cookie);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/syscall.c (ffffffff812cbf80)
Location: kernel/bpf/syscall.c:2956
Inline: False
Direct callers:
  - kernel/bpf/syscall.c:link_create
  - kernel/bpf/syscall.c:bpf_raw_tp_link_attach
```
**Symbols:**

```
ffffffff812cbf80-ffffffff812cc4d0: bpf_tracing_prog_attach (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int bpf_tracing_prog_attach(struct bpf_prog *prog, int tgt_prog_fd, u32 btf_id, u64 bpf_cookie);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/syscall.c (ffffffff812f38f0)
Location: kernel/bpf/syscall.c:3082
Inline: False
Direct callers:
  - kernel/bpf/syscall.c:link_create
  - kernel/bpf/syscall.c:bpf_raw_tp_link_attach
```
**Symbols:**

```
ffffffff812f38f0-ffffffff812f3e6f: bpf_tracing_prog_attach (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int bpf_tracing_prog_attach(struct bpf_prog *prog, int tgt_prog_fd, u32 btf_id, u64 bpf_cookie);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/syscall.c (ffffffff81312780)
Location: kernel/bpf/syscall.c:3146
Inline: False
Direct callers:
  - kernel/bpf/syscall.c:link_create
  - kernel/bpf/syscall.c:bpf_raw_tp_link_attach
```
**Symbols:**

```
ffffffff81312780-ffffffff81312d64: bpf_tracing_prog_attach (STB_LOCAL)
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
<code>u64 bpf_cookie</code>
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
