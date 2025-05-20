# Function: <code>raw_tp_prog_is_valid_access</code>

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
bool raw_tp_prog_is_valid_access(int off, int size, enum bpf_access_type type, const struct bpf_prog *prog, struct bpf_insn_access_aux *info);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/bpf_trace.c (ffffffff811a4610)
Location: kernel/trace/bpf_trace.c:854
Inline: False
```
**Symbols:**

```
ffffffff811a4610-ffffffff811a4628: raw_tp_prog_is_valid_access (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
bool raw_tp_prog_is_valid_access(int off, int size, enum bpf_access_type type, const struct bpf_prog *prog, struct bpf_insn_access_aux *info);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/bpf_trace.c (ffffffff811b2740)
Location: kernel/trace/bpf_trace.c:890
Inline: False
```
**Symbols:**

```
ffffffff811b2740-ffffffff811b2758: raw_tp_prog_is_valid_access (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
bool raw_tp_prog_is_valid_access(int off, int size, enum bpf_access_type type, const struct bpf_prog *prog, struct bpf_insn_access_aux *info);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/trace/bpf_trace.c (ffffffff811c0fba)
Location: kernel/trace/bpf_trace.c:1039
Inline: True
Inline callers:
  - kernel/trace/bpf_trace.c:raw_tp_writable_prog_is_valid_access
```
**Symbols:**

```
ffffffff811c0f80-ffffffff811c0f98: raw_tp_prog_is_valid_access (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
bool raw_tp_prog_is_valid_access(int off, int size, enum bpf_access_type type, const struct bpf_prog *prog, struct bpf_insn_access_aux *info);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/trace/bpf_trace.c (ffffffff811cc76a)
Location: kernel/trace/bpf_trace.c:1063
Inline: True
Inline callers:
  - kernel/trace/bpf_trace.c:raw_tp_writable_prog_is_valid_access
```
**Symbols:**

```
ffffffff811cc730-ffffffff811cc748: raw_tp_prog_is_valid_access (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
bool raw_tp_prog_is_valid_access(int off, int size, enum bpf_access_type type, const struct bpf_prog *prog, struct bpf_insn_access_aux *info);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/trace/bpf_trace.c (ffffffff811e814a)
Location: kernel/trace/bpf_trace.c:1529
Inline: True
Inline callers:
  - kernel/trace/bpf_trace.c:raw_tp_writable_prog_is_valid_access
```
**Symbols:**

```
ffffffff811e8100-ffffffff811e8118: raw_tp_prog_is_valid_access (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
bool raw_tp_prog_is_valid_access(int off, int size, enum bpf_access_type type, const struct bpf_prog *prog, struct bpf_insn_access_aux *info);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/trace/bpf_trace.c (ffffffff811e5b4a)
Location: kernel/trace/bpf_trace.c:1780
Inline: True
Inline callers:
  - kernel/trace/bpf_trace.c:raw_tp_writable_prog_is_valid_access
```
**Symbols:**

```
ffffffff811e5b00-ffffffff811e5b18: raw_tp_prog_is_valid_access (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
bool raw_tp_prog_is_valid_access(int off, int size, enum bpf_access_type type, const struct bpf_prog *prog, struct bpf_insn_access_aux *info);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/trace/bpf_trace.c (ffffffff811e725a)
Location: kernel/trace/bpf_trace.c:1476
Inline: True
Inline callers:
  - kernel/trace/bpf_trace.c:raw_tp_writable_prog_is_valid_access
```
**Symbols:**

```
ffffffff811e7210-ffffffff811e7228: raw_tp_prog_is_valid_access (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
bool raw_tp_prog_is_valid_access(int off, int size, enum bpf_access_type type, const struct bpf_prog *prog, struct bpf_insn_access_aux *info);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/trace/bpf_trace.c (ffffffff81217eda)
Location: kernel/trace/bpf_trace.c:1558
Inline: True
Inline callers:
  - kernel/trace/bpf_trace.c:raw_tp_writable_prog_is_valid_access
```
**Symbols:**

```
ffffffff81217e90-ffffffff81217ea8: raw_tp_prog_is_valid_access (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
bool raw_tp_prog_is_valid_access(int off, int size, enum bpf_access_type type, const struct bpf_prog *prog, struct bpf_insn_access_aux *info);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/trace/bpf_trace.c (ffffffff81255da5)
Location: kernel/trace/bpf_trace.c:1751
Inline: True
Inline callers:
  - kernel/trace/bpf_trace.c:raw_tp_writable_prog_is_valid_access
```
**Symbols:**

```
ffffffff81255d50-ffffffff81255d7c: raw_tp_prog_is_valid_access (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
bool raw_tp_prog_is_valid_access(int off, int size, enum bpf_access_type type, const struct bpf_prog *prog, struct bpf_insn_access_aux *info);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/trace/bpf_trace.c (ffffffff812a5385)
Location: kernel/trace/bpf_trace.c:1968
Inline: True
Inline callers:
  - kernel/trace/bpf_trace.c:raw_tp_writable_prog_is_valid_access
```
**Symbols:**

```
ffffffff812a5310-ffffffff812a533c: raw_tp_prog_is_valid_access (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
bool raw_tp_prog_is_valid_access(int off, int size, enum bpf_access_type type, const struct bpf_prog *prog, struct bpf_insn_access_aux *info);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/trace/bpf_trace.c (ffffffff812c7835)
Location: kernel/trace/bpf_trace.c:1977
Inline: True
Inline callers:
  - kernel/trace/bpf_trace.c:raw_tp_writable_prog_is_valid_access
```
**Symbols:**

```
ffffffff812c77c0-ffffffff812c77ec: raw_tp_prog_is_valid_access (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
bool raw_tp_prog_is_valid_access(int off, int size, enum bpf_access_type type, const struct bpf_prog *prog, struct bpf_insn_access_aux *info);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/trace/bpf_trace.c (ffffffff812e41b5)
Location: kernel/trace/bpf_trace.c:2082
Inline: True
Inline callers:
  - kernel/trace/bpf_trace.c:raw_tp_writable_prog_is_valid_access
```
**Symbols:**

```
ffffffff812e4140-ffffffff812e416c: raw_tp_prog_is_valid_access (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Selective Inline ⚠️</summary>

```c
bool raw_tp_prog_is_valid_access(int off, int size, enum bpf_access_type type, const struct bpf_prog *prog, struct bpf_insn_access_aux *info);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/trace/bpf_trace.c (ffff80001024c420)
Location: kernel/trace/bpf_trace.c:1063
Inline: True
Inline callers:
  - kernel/trace/bpf_trace.c:raw_tp_writable_prog_is_valid_access
```
**Symbols:**

```
ffff80001024c3d0-ffff80001024c3f8: raw_tp_prog_is_valid_access (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
bool raw_tp_prog_is_valid_access(int off, int size, enum bpf_access_type type, const struct bpf_prog *prog, struct bpf_insn_access_aux *info);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/trace/bpf_trace.c (c047ea38)
Location: kernel/trace/bpf_trace.c:1063
Inline: True
Inline callers:
  - kernel/trace/bpf_trace.c:raw_tp_writable_prog_is_valid_access
```
**Symbols:**

```
c047e9d0-c047ea00: raw_tp_prog_is_valid_access (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
bool raw_tp_prog_is_valid_access(int off, int size, enum bpf_access_type type, const struct bpf_prog *prog, struct bpf_insn_access_aux *info);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/trace/bpf_trace.c (c0000000002e78b0)
Location: kernel/trace/bpf_trace.c:1063
Inline: True
```
**Symbols:**

```
c0000000002e78b0-c0000000002e78e8: raw_tp_prog_is_valid_access (STB_LOCAL)
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
<summary>In <code>aws</code>: Selective Inline ⚠️</summary>

```c
bool raw_tp_prog_is_valid_access(int off, int size, enum bpf_access_type type, const struct bpf_prog *prog, struct bpf_insn_access_aux *info);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/trace/bpf_trace.c (ffffffff811c4d8a)
Location: kernel/trace/bpf_trace.c:1063
Inline: True
Inline callers:
  - kernel/trace/bpf_trace.c:raw_tp_writable_prog_is_valid_access
```
**Symbols:**

```
ffffffff811c4d50-ffffffff811c4d68: raw_tp_prog_is_valid_access (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
bool raw_tp_prog_is_valid_access(int off, int size, enum bpf_access_type type, const struct bpf_prog *prog, struct bpf_insn_access_aux *info);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/trace/bpf_trace.c (ffffffff811b7b6a)
Location: kernel/trace/bpf_trace.c:1063
Inline: True
Inline callers:
  - kernel/trace/bpf_trace.c:raw_tp_writable_prog_is_valid_access
```
**Symbols:**

```
ffffffff811b7b30-ffffffff811b7b48: raw_tp_prog_is_valid_access (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
bool raw_tp_prog_is_valid_access(int off, int size, enum bpf_access_type type, const struct bpf_prog *prog, struct bpf_insn_access_aux *info);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/trace/bpf_trace.c (ffffffff811c2b5a)
Location: kernel/trace/bpf_trace.c:1063
Inline: True
Inline callers:
  - kernel/trace/bpf_trace.c:raw_tp_writable_prog_is_valid_access
```
**Symbols:**

```
ffffffff811c2b20-ffffffff811c2b38: raw_tp_prog_is_valid_access (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
bool raw_tp_prog_is_valid_access(int off, int size, enum bpf_access_type type, const struct bpf_prog *prog, struct bpf_insn_access_aux *info);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/trace/bpf_trace.c (ffffffff811d0bfa)
Location: kernel/trace/bpf_trace.c:1063
Inline: True
Inline callers:
  - kernel/trace/bpf_trace.c:raw_tp_writable_prog_is_valid_access
```
**Symbols:**

```
ffffffff811d0bc0-ffffffff811d0bd8: raw_tp_prog_is_valid_access (STB_LOCAL)
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
