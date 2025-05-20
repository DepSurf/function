# Function: <code>__bpf_prog_exit_sleepable</code>

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
In <code>5.8</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void __bpf_prog_exit_sleepable();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/trampoline.c (ffffffff81222af0)
Location: kernel/bpf/trampoline.c:539
Inline: False
```
**Symbols:**

```
ffffffff81222af0-ffffffff81222b2e: __bpf_prog_exit_sleepable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void __bpf_prog_exit_sleepable(struct bpf_prog *prog, u64 start);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/trampoline.c (ffffffff81227310)
Location: kernel/bpf/trampoline.c:611
Inline: False
```
**Symbols:**

```
ffffffff81227310-ffffffff81227368: __bpf_prog_exit_sleepable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void __bpf_prog_exit_sleepable(struct bpf_prog *prog, u64 start);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/trampoline.c (ffffffff8125f410)
Location: kernel/bpf/trampoline.c:620
Inline: False
```
**Symbols:**

```
ffffffff8125f410-ffffffff8125f468: __bpf_prog_exit_sleepable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void __bpf_prog_exit_sleepable(struct bpf_prog *prog, u64 start, struct bpf_tramp_run_ctx *run_ctx);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/trampoline.c (ffffffff812a9b20)
Location: kernel/bpf/trampoline.c:644
Inline: False
Direct callers:
  - kernel/bpf/syscall.c:kern_sys_bpf
```
**Symbols:**

```
ffffffff812a9b20-ffffffff812a9b92: __bpf_prog_exit_sleepable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void __bpf_prog_exit_sleepable(struct bpf_prog *prog, u64 start, struct bpf_tramp_run_ctx *run_ctx);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/trampoline.c (ffffffff81308700)
Location: kernel/bpf/trampoline.c:984
Inline: False
```
**Symbols:**

```
ffffffff81308700-ffffffff81308767: __bpf_prog_exit_sleepable (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void __bpf_prog_exit_sleepable(struct bpf_prog *prog, u64 start, struct bpf_tramp_run_ctx *run_ctx);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/trampoline.c (ffffffff81337690)
Location: kernel/bpf/trampoline.c:962
Inline: False
```
**Symbols:**

```
ffffffff81337690-ffffffff81337721: __bpf_prog_exit_sleepable (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void __bpf_prog_exit_sleepable(struct bpf_prog *prog, u64 start, struct bpf_tramp_run_ctx *run_ctx);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/trampoline.c (ffffffff8135d4d0)
Location: kernel/bpf/trampoline.c:972
Inline: False
```
**Symbols:**

```
ffffffff8135d4d0-ffffffff8135d561: __bpf_prog_exit_sleepable (STB_LOCAL)
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
<summary>Changed between <code>5.11</code> and <code>5.13</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>struct bpf_prog *prog</code>
</li>
<li>
<b>Param added. </b>
<code>u64 start</code>
</li>
</ul>
</details>
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
<code>struct bpf_tramp_run_ctx *run_ctx</code>
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
