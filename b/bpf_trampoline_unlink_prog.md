# Function: <code>bpf_trampoline_unlink_prog</code>

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
int bpf_trampoline_unlink_prog(struct bpf_prog *prog);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/trampoline.c (ffffffff8121f5d0)
Location: kernel/bpf/trampoline.c:310
Inline: False
Direct callers:
  - kernel/bpf/syscall.c:bpf_tracing_link_release
```
**Symbols:**

```
ffffffff8121f5d0-ffffffff8121f6fb: bpf_trampoline_unlink_prog (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int bpf_trampoline_unlink_prog(struct bpf_prog *prog, struct bpf_trampoline *tr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/trampoline.c (ffffffff81222fc0)
Location: kernel/bpf/trampoline.c:426
Inline: False
Direct callers:
  - kernel/bpf/syscall.c:bpf_tracing_link_release
```
**Symbols:**

```
ffffffff81222fc0-ffffffff812230fa: bpf_trampoline_unlink_prog (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int bpf_trampoline_unlink_prog(struct bpf_prog *prog, struct bpf_trampoline *tr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/trampoline.c (ffffffff81227a60)
Location: kernel/bpf/trampoline.c:456
Inline: False
Direct callers:
  - kernel/bpf/syscall.c:bpf_tracing_link_release
```
**Symbols:**

```
ffffffff81227a60-ffffffff81227b93: bpf_trampoline_unlink_prog (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int bpf_trampoline_unlink_prog(struct bpf_prog *prog, struct bpf_trampoline *tr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/trampoline.c (ffffffff8125fcc0)
Location: kernel/bpf/trampoline.c:462
Inline: False
Direct callers:
  - kernel/bpf/syscall.c:bpf_tracing_link_release
```
**Symbols:**

```
ffffffff8125fcc0-ffffffff8125fe21: bpf_trampoline_unlink_prog (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int bpf_trampoline_unlink_prog(struct bpf_tramp_link *link, struct bpf_trampoline *tr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/trampoline.c (ffffffff812aa4f0)
Location: kernel/bpf/trampoline.c:474
Inline: False
Direct callers:
  - kernel/bpf/syscall.c:bpf_tracing_link_release
```
**Symbols:**

```
ffffffff812aa4f0-ffffffff812aa63e: bpf_trampoline_unlink_prog (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int bpf_trampoline_unlink_prog(struct bpf_tramp_link *link, struct bpf_trampoline *tr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/trampoline.c (ffffffff81309ac0)
Location: kernel/bpf/trampoline.c:611
Inline: False
Direct callers:
  - kernel/bpf/syscall.c:bpf_tracing_link_release
  - kernel/bpf/trampoline.c:bpf_shim_tramp_link_release
```
**Symbols:**

```
ffffffff81309ac0-ffffffff81309bef: bpf_trampoline_unlink_prog (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int bpf_trampoline_unlink_prog(struct bpf_tramp_link *link, struct bpf_trampoline *tr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/trampoline.c (ffffffff81338900)
Location: kernel/bpf/trampoline.c:589
Inline: False
Direct callers:
  - kernel/bpf/syscall.c:bpf_tracing_link_release
  - kernel/bpf/trampoline.c:bpf_shim_tramp_link_release
```
**Symbols:**

```
ffffffff81338900-ffffffff81338a2f: bpf_trampoline_unlink_prog (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int bpf_trampoline_unlink_prog(struct bpf_tramp_link *link, struct bpf_trampoline *tr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/trampoline.c (ffffffff8135ea30)
Location: kernel/bpf/trampoline.c:600
Inline: False
Direct callers:
  - kernel/bpf/syscall.c:bpf_tracing_link_release
  - kernel/bpf/trampoline.c:bpf_shim_tramp_link_release
```
**Symbols:**

```
ffffffff8135ea30-ffffffff8135eb5f: bpf_trampoline_unlink_prog (STB_GLOBAL)
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
