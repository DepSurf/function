# Function: <code>__bpf_prog_exit</code>

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
void __bpf_prog_exit(struct bpf_prog *prog, u64 start);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/trampoline.c (ffffffff8121f1e0)
Location: kernel/bpf/trampoline.c:375
Inline: False
```
**Symbols:**

```
ffffffff8121f1e0-ffffffff8121f225: __bpf_prog_exit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void __bpf_prog_exit(struct bpf_prog *prog, u64 start);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/trampoline.c (ffffffff81222a80)
Location: kernel/bpf/trampoline.c:511
Inline: False
```
**Symbols:**

```
ffffffff81222a80-ffffffff81222ad0: __bpf_prog_exit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void __bpf_prog_exit(struct bpf_prog *prog, u64 start);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/trampoline.c (ffffffff81227260)
Location: kernel/bpf/trampoline.c:590
Inline: False
```
**Symbols:**

```
ffffffff81227260-ffffffff81227284: __bpf_prog_exit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void __bpf_prog_exit(struct bpf_prog *prog, u64 start);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/trampoline.c (ffffffff8125f360)
Location: kernel/bpf/trampoline.c:599
Inline: False
```
**Symbols:**

```
ffffffff8125f360-ffffffff8125f384: __bpf_prog_exit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void __bpf_prog_exit(struct bpf_prog *prog, u64 start, struct bpf_tramp_run_ctx *run_ctx);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/trampoline.c (ffffffff812a9a10)
Location: kernel/bpf/trampoline.c:617
Inline: False
```
**Symbols:**

```
ffffffff812a9a10-ffffffff812a9a54: __bpf_prog_exit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void __bpf_prog_exit(struct bpf_prog *prog, u64 start, struct bpf_tramp_run_ctx *run_ctx);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/trampoline.c (ffffffff81308360)
Location: kernel/bpf/trampoline.c:1006
Inline: False
```
**Symbols:**

```
ffffffff81308360-ffffffff81308395: __bpf_prog_exit (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void __bpf_prog_exit(struct bpf_prog *prog, u64 start, struct bpf_tramp_run_ctx *run_ctx);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/trampoline.c (ffffffff81337580)
Location: kernel/bpf/trampoline.c:984
Inline: False
```
**Symbols:**

```
ffffffff81337580-ffffffff813375f7: __bpf_prog_exit (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void __bpf_prog_exit(struct bpf_prog *prog, u64 start, struct bpf_tramp_run_ctx *run_ctx);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/trampoline.c (ffffffff8135d3c0)
Location: kernel/bpf/trampoline.c:994
Inline: False
```
**Symbols:**

```
ffffffff8135d3c0-ffffffff8135d437: __bpf_prog_exit (STB_LOCAL)
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
No changes between <code>5.8</code> and <code>5.11</code> ✅
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
