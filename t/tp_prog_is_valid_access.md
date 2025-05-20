# Function: <code>tp_prog_is_valid_access</code>

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
bool tp_prog_is_valid_access(int off, int size, enum bpf_access_type type, enum bpf_reg_type *reg_type);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/bpf_trace.c (ffffffff81173da0)
Location: kernel/trace/bpf_trace.c:501
Inline: False
```
**Symbols:**

```
ffffffff81173da0-ffffffff81173dcc: tp_prog_is_valid_access (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
bool tp_prog_is_valid_access(int off, int size, enum bpf_access_type type, enum bpf_reg_type *reg_type);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/bpf_trace.c (ffffffff8117f570)
Location: kernel/trace/bpf_trace.c:534
Inline: False
```
**Symbols:**

```
ffffffff8117f570-ffffffff8117f59c: tp_prog_is_valid_access (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
bool tp_prog_is_valid_access(int off, int size, enum bpf_access_type type, struct bpf_insn_access_aux *info);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/bpf_trace.c (ffffffff81182220)
Location: kernel/trace/bpf_trace.c:602
Inline: False
```
**Symbols:**

```
ffffffff81182220-ffffffff8118224c: tp_prog_is_valid_access (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
bool tp_prog_is_valid_access(int off, int size, enum bpf_access_type type, struct bpf_insn_access_aux *info);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/bpf_trace.c (ffffffff8118fbe0)
Location: kernel/trace/bpf_trace.c:651
Inline: False
```
**Symbols:**

```
ffffffff8118fbe0-ffffffff8118fc0c: tp_prog_is_valid_access (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
bool tp_prog_is_valid_access(int off, int size, enum bpf_access_type type, const struct bpf_prog *prog, struct bpf_insn_access_aux *info);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/bpf_trace.c (ffffffff811a45e0)
Location: kernel/trace/bpf_trace.c:707
Inline: False
```
**Symbols:**

```
ffffffff811a45e0-ffffffff811a4606: tp_prog_is_valid_access (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
bool tp_prog_is_valid_access(int off, int size, enum bpf_access_type type, const struct bpf_prog *prog, struct bpf_insn_access_aux *info);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/bpf_trace.c (ffffffff811b2710)
Location: kernel/trace/bpf_trace.c:743
Inline: False
```
**Symbols:**

```
ffffffff811b2710-ffffffff811b2736: tp_prog_is_valid_access (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
bool tp_prog_is_valid_access(int off, int size, enum bpf_access_type type, const struct bpf_prog *prog, struct bpf_insn_access_aux *info);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/bpf_trace.c (ffffffff811c0f50)
Location: kernel/trace/bpf_trace.c:848
Inline: False
```
**Symbols:**

```
ffffffff811c0f50-ffffffff811c0f76: tp_prog_is_valid_access (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
bool tp_prog_is_valid_access(int off, int size, enum bpf_access_type type, const struct bpf_prog *prog, struct bpf_insn_access_aux *info);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/bpf_trace.c (ffffffff811cc700)
Location: kernel/trace/bpf_trace.c:872
Inline: False
```
**Symbols:**

```
ffffffff811cc700-ffffffff811cc726: tp_prog_is_valid_access (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
bool tp_prog_is_valid_access(int off, int size, enum bpf_access_type type, const struct bpf_prog *prog, struct bpf_insn_access_aux *info);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/bpf_trace.c (ffffffff811e80d0)
Location: kernel/trace/bpf_trace.c:1271
Inline: False
```
**Symbols:**

```
ffffffff811e80d0-ffffffff811e80f6: tp_prog_is_valid_access (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
bool tp_prog_is_valid_access(int off, int size, enum bpf_access_type type, const struct bpf_prog *prog, struct bpf_insn_access_aux *info);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/bpf_trace.c (ffffffff811e5ad0)
Location: kernel/trace/bpf_trace.c:1500
Inline: False
```
**Symbols:**

```
ffffffff811e5ad0-ffffffff811e5af6: tp_prog_is_valid_access (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
bool tp_prog_is_valid_access(int off, int size, enum bpf_access_type type, const struct bpf_prog *prog, struct bpf_insn_access_aux *info);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/bpf_trace.c (ffffffff811e71e0)
Location: kernel/trace/bpf_trace.c:1194
Inline: False
```
**Symbols:**

```
ffffffff811e71e0-ffffffff811e720a: tp_prog_is_valid_access (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
bool tp_prog_is_valid_access(int off, int size, enum bpf_access_type type, const struct bpf_prog *prog, struct bpf_insn_access_aux *info);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/bpf_trace.c (ffffffff81217e60)
Location: kernel/trace/bpf_trace.c:1273
Inline: False
```
**Symbols:**

```
ffffffff81217e60-ffffffff81217e8a: tp_prog_is_valid_access (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
bool tp_prog_is_valid_access(int off, int size, enum bpf_access_type type, const struct bpf_prog *prog, struct bpf_insn_access_aux *info);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/bpf_trace.c (ffffffff81255d10)
Location: kernel/trace/bpf_trace.c:1451
Inline: False
```
**Symbols:**

```
ffffffff81255d10-ffffffff81255d50: tp_prog_is_valid_access (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
bool tp_prog_is_valid_access(int off, int size, enum bpf_access_type type, const struct bpf_prog *prog, struct bpf_insn_access_aux *info);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/bpf_trace.c (ffffffff812a52c0)
Location: kernel/trace/bpf_trace.c:1665
Inline: False
```
**Symbols:**

```
ffffffff812a52c0-ffffffff812a5300: tp_prog_is_valid_access (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
bool tp_prog_is_valid_access(int off, int size, enum bpf_access_type type, const struct bpf_prog *prog, struct bpf_insn_access_aux *info);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/bpf_trace.c (ffffffff812c7770)
Location: kernel/trace/bpf_trace.c:1674
Inline: False
```
**Symbols:**

```
ffffffff812c7770-ffffffff812c77b0: tp_prog_is_valid_access (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
bool tp_prog_is_valid_access(int off, int size, enum bpf_access_type type, const struct bpf_prog *prog, struct bpf_insn_access_aux *info);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/bpf_trace.c (ffffffff812e40f0)
Location: kernel/trace/bpf_trace.c:1779
Inline: False
```
**Symbols:**

```
ffffffff812e40f0-ffffffff812e4130: tp_prog_is_valid_access (STB_LOCAL)
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
bool tp_prog_is_valid_access(int off, int size, enum bpf_access_type type, const struct bpf_prog *prog, struct bpf_insn_access_aux *info);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/bpf_trace.c (ffff80001024c3a0)
Location: kernel/trace/bpf_trace.c:872
Inline: False
```
**Symbols:**

```
ffff80001024c3a0-ffff80001024c3cc: tp_prog_is_valid_access (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
bool tp_prog_is_valid_access(int off, int size, enum bpf_access_type type, const struct bpf_prog *prog, struct bpf_insn_access_aux *info);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/bpf_trace.c (c047e98c)
Location: kernel/trace/bpf_trace.c:872
Inline: False
```
**Symbols:**

```
c047e98c-c047e9d0: tp_prog_is_valid_access (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
bool tp_prog_is_valid_access(int off, int size, enum bpf_access_type type, const struct bpf_prog *prog, struct bpf_insn_access_aux *info);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/bpf_trace.c (c0000000002e7860)
Location: kernel/trace/bpf_trace.c:872
Inline: False
```
**Symbols:**

```
c0000000002e7860-c0000000002e78a8: tp_prog_is_valid_access (STB_LOCAL)
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
<summary>In <code>aws</code>: ✅</summary>

```c
bool tp_prog_is_valid_access(int off, int size, enum bpf_access_type type, const struct bpf_prog *prog, struct bpf_insn_access_aux *info);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/bpf_trace.c (ffffffff811c4d20)
Location: kernel/trace/bpf_trace.c:872
Inline: False
```
**Symbols:**

```
ffffffff811c4d20-ffffffff811c4d46: tp_prog_is_valid_access (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
bool tp_prog_is_valid_access(int off, int size, enum bpf_access_type type, const struct bpf_prog *prog, struct bpf_insn_access_aux *info);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/bpf_trace.c (ffffffff811b7b00)
Location: kernel/trace/bpf_trace.c:872
Inline: False
```
**Symbols:**

```
ffffffff811b7b00-ffffffff811b7b26: tp_prog_is_valid_access (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
bool tp_prog_is_valid_access(int off, int size, enum bpf_access_type type, const struct bpf_prog *prog, struct bpf_insn_access_aux *info);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/bpf_trace.c (ffffffff811c2af0)
Location: kernel/trace/bpf_trace.c:872
Inline: False
```
**Symbols:**

```
ffffffff811c2af0-ffffffff811c2b16: tp_prog_is_valid_access (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
bool tp_prog_is_valid_access(int off, int size, enum bpf_access_type type, const struct bpf_prog *prog, struct bpf_insn_access_aux *info);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/bpf_trace.c (ffffffff811d0b90)
Location: kernel/trace/bpf_trace.c:872
Inline: False
```
**Symbols:**

```
ffffffff811d0b90-ffffffff811d0bb6: tp_prog_is_valid_access (STB_LOCAL)
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
<details>
<summary>Changed between <code>4.10</code> and <code>4.13</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>struct bpf_insn_access_aux *info</code>
</li>
<li>
<b>Param removed. </b>
<code>enum bpf_reg_type *reg_type</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>4.13</code> and <code>4.15</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>4.15</code> and <code>4.18</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>const struct bpf_prog *prog</code>
</li>
<li>
<b>Param reordered. </b>
<code>off, size, type, info</code> ➡️ <code>off, size, type, prog, info</code>
</li>
</ul>
</details>
</li>
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
