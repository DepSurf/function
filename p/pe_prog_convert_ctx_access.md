# Function: <code>pe_prog_convert_ctx_access</code>

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
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
u32 pe_prog_convert_ctx_access(enum bpf_access_type type, int dst_reg, int src_reg, int ctx_off, struct bpf_insn *insn_buf, struct bpf_prog *prog);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/bpf_trace.c (ffffffff8117f5a0)
Location: kernel/trace/bpf_trace.c:575
Inline: False
```
**Symbols:**

```
ffffffff8117f5a0-ffffffff8117f636: pe_prog_convert_ctx_access (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
u32 pe_prog_convert_ctx_access(enum bpf_access_type type, const struct bpf_insn *si, struct bpf_insn *insn_buf, struct bpf_prog *prog, u32 *target_size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/bpf_trace.c (ffffffff811822a0)
Location: kernel/trace/bpf_trace.c:648
Inline: False
```
**Symbols:**

```
ffffffff811822a0-ffffffff8118233e: pe_prog_convert_ctx_access (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
u32 pe_prog_convert_ctx_access(enum bpf_access_type type, const struct bpf_insn *si, struct bpf_insn *insn_buf, struct bpf_prog *prog, u32 *target_size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/bpf_trace.c (ffffffff8118fc60)
Location: kernel/trace/bpf_trace.c:740
Inline: False
```
**Symbols:**

```
ffffffff8118fc60-ffffffff8118fcfe: pe_prog_convert_ctx_access (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
u32 pe_prog_convert_ctx_access(enum bpf_access_type type, const struct bpf_insn *si, struct bpf_insn *insn_buf, struct bpf_prog *prog, u32 *target_size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/bpf_trace.c (ffffffff811a4690)
Location: kernel/trace/bpf_trace.c:915
Inline: False
```
**Symbols:**

```
ffffffff811a4690-ffffffff811a478d: pe_prog_convert_ctx_access (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
u32 pe_prog_convert_ctx_access(enum bpf_access_type type, const struct bpf_insn *si, struct bpf_insn *insn_buf, struct bpf_prog *prog, u32 *target_size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/bpf_trace.c (ffffffff811b2760)
Location: kernel/trace/bpf_trace.c:951
Inline: False
```
**Symbols:**

```
ffffffff811b2760-ffffffff811b285d: pe_prog_convert_ctx_access (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
u32 pe_prog_convert_ctx_access(enum bpf_access_type type, const struct bpf_insn *si, struct bpf_insn *insn_buf, struct bpf_prog *prog, u32 *target_size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/bpf_trace.c (ffffffff811c0fe0)
Location: kernel/trace/bpf_trace.c:1121
Inline: False
```
**Symbols:**

```
ffffffff811c0fe0-ffffffff811c10dd: pe_prog_convert_ctx_access (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
u32 pe_prog_convert_ctx_access(enum bpf_access_type type, const struct bpf_insn *si, struct bpf_insn *insn_buf, struct bpf_prog *prog, u32 *target_size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/bpf_trace.c (ffffffff811cc790)
Location: kernel/trace/bpf_trace.c:1145
Inline: False
```
**Symbols:**

```
ffffffff811cc790-ffffffff811cc88d: pe_prog_convert_ctx_access (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
u32 pe_prog_convert_ctx_access(enum bpf_access_type type, const struct bpf_insn *si, struct bpf_insn *insn_buf, struct bpf_prog *prog, u32 *target_size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/bpf_trace.c (ffffffff811e8170)
Location: kernel/trace/bpf_trace.c:1640
Inline: False
```
**Symbols:**

```
ffffffff811e8170-ffffffff811e826d: pe_prog_convert_ctx_access (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
u32 pe_prog_convert_ctx_access(enum bpf_access_type type, const struct bpf_insn *si, struct bpf_insn *insn_buf, struct bpf_prog *prog, u32 *target_size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/bpf_trace.c (ffffffff811e5b70)
Location: kernel/trace/bpf_trace.c:1894
Inline: False
```
**Symbols:**

```
ffffffff811e5b70-ffffffff811e5c6d: pe_prog_convert_ctx_access (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
u32 pe_prog_convert_ctx_access(enum bpf_access_type type, const struct bpf_insn *si, struct bpf_insn *insn_buf, struct bpf_prog *prog, u32 *target_size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/bpf_trace.c (ffffffff811e7280)
Location: kernel/trace/bpf_trace.c:1590
Inline: False
```
**Symbols:**

```
ffffffff811e7280-ffffffff811e7346: pe_prog_convert_ctx_access (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
u32 pe_prog_convert_ctx_access(enum bpf_access_type type, const struct bpf_insn *si, struct bpf_insn *insn_buf, struct bpf_prog *prog, u32 *target_size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/bpf_trace.c (ffffffff81217f00)
Location: kernel/trace/bpf_trace.c:1672
Inline: False
```
**Symbols:**

```
ffffffff81217f00-ffffffff81217fc6: pe_prog_convert_ctx_access (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
u32 pe_prog_convert_ctx_access(enum bpf_access_type type, const struct bpf_insn *si, struct bpf_insn *insn_buf, struct bpf_prog *prog, u32 *target_size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/bpf_trace.c (ffffffff81255e70)
Location: kernel/trace/bpf_trace.c:1853
Inline: False
```
**Symbols:**

```
ffffffff81255e70-ffffffff81255f4c: pe_prog_convert_ctx_access (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
u32 pe_prog_convert_ctx_access(enum bpf_access_type type, const struct bpf_insn *si, struct bpf_insn *insn_buf, struct bpf_prog *prog, u32 *target_size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/bpf_trace.c (ffffffff812a5470)
Location: kernel/trace/bpf_trace.c:2070
Inline: False
```
**Symbols:**

```
ffffffff812a5470-ffffffff812a554f: pe_prog_convert_ctx_access (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
u32 pe_prog_convert_ctx_access(enum bpf_access_type type, const struct bpf_insn *si, struct bpf_insn *insn_buf, struct bpf_prog *prog, u32 *target_size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/bpf_trace.c (ffffffff812c7920)
Location: kernel/trace/bpf_trace.c:2079
Inline: False
```
**Symbols:**

```
ffffffff812c7920-ffffffff812c79ff: pe_prog_convert_ctx_access (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
u32 pe_prog_convert_ctx_access(enum bpf_access_type type, const struct bpf_insn *si, struct bpf_insn *insn_buf, struct bpf_prog *prog, u32 *target_size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/bpf_trace.c (ffffffff812e42a0)
Location: kernel/trace/bpf_trace.c:2184
Inline: False
```
**Symbols:**

```
ffffffff812e42a0-ffffffff812e437f: pe_prog_convert_ctx_access (STB_LOCAL)
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
u32 pe_prog_convert_ctx_access(enum bpf_access_type type, const struct bpf_insn *si, struct bpf_insn *insn_buf, struct bpf_prog *prog, u32 *target_size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/bpf_trace.c (ffff80001024c448)
Location: kernel/trace/bpf_trace.c:1145
Inline: False
```
**Symbols:**

```
ffff80001024c448-ffff80001024c570: pe_prog_convert_ctx_access (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
u32 pe_prog_convert_ctx_access(enum bpf_access_type type, const struct bpf_insn *si, struct bpf_insn *insn_buf, struct bpf_prog *prog, u32 *target_size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/bpf_trace.c (c047ea60)
Location: kernel/trace/bpf_trace.c:1145
Inline: False
```
**Symbols:**

```
c047ea60-c047ebac: pe_prog_convert_ctx_access (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
u32 pe_prog_convert_ctx_access(enum bpf_access_type type, const struct bpf_insn *si, struct bpf_insn *insn_buf, struct bpf_prog *prog, u32 *target_size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/bpf_trace.c (c0000000002e78f0)
Location: kernel/trace/bpf_trace.c:1145
Inline: False
```
**Symbols:**

```
c0000000002e78f0-c0000000002e7a14: pe_prog_convert_ctx_access (STB_LOCAL)
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
u32 pe_prog_convert_ctx_access(enum bpf_access_type type, const struct bpf_insn *si, struct bpf_insn *insn_buf, struct bpf_prog *prog, u32 *target_size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/bpf_trace.c (ffffffff811c4db0)
Location: kernel/trace/bpf_trace.c:1145
Inline: False
```
**Symbols:**

```
ffffffff811c4db0-ffffffff811c4ead: pe_prog_convert_ctx_access (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
u32 pe_prog_convert_ctx_access(enum bpf_access_type type, const struct bpf_insn *si, struct bpf_insn *insn_buf, struct bpf_prog *prog, u32 *target_size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/bpf_trace.c (ffffffff811b7b90)
Location: kernel/trace/bpf_trace.c:1145
Inline: False
```
**Symbols:**

```
ffffffff811b7b90-ffffffff811b7c8d: pe_prog_convert_ctx_access (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
u32 pe_prog_convert_ctx_access(enum bpf_access_type type, const struct bpf_insn *si, struct bpf_insn *insn_buf, struct bpf_prog *prog, u32 *target_size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/bpf_trace.c (ffffffff811c2b80)
Location: kernel/trace/bpf_trace.c:1145
Inline: False
```
**Symbols:**

```
ffffffff811c2b80-ffffffff811c2c7d: pe_prog_convert_ctx_access (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
u32 pe_prog_convert_ctx_access(enum bpf_access_type type, const struct bpf_insn *si, struct bpf_insn *insn_buf, struct bpf_prog *prog, u32 *target_size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/bpf_trace.c (ffffffff811d0c20)
Location: kernel/trace/bpf_trace.c:1145
Inline: False
```
**Symbols:**

```
ffffffff811d0c20-ffffffff811d0d1d: pe_prog_convert_ctx_access (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
<details>
<summary>Changed between <code>4.10</code> and <code>4.13</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>const struct bpf_insn *si</code>
</li>
<li>
<b>Param added. </b>
<code>u32 *target_size</code>
</li>
<li>
<b>Param removed. </b>
<code>int dst_reg</code>
</li>
<li>
<b>Param removed. </b>
<code>int src_reg</code>
</li>
<li>
<b>Param removed. </b>
<code>int ctx_off</code>
</li>
<li>
<b>Param reordered. </b>
<code>type, dst_reg, src_reg, ctx_off, insn_buf, prog</code> ➡️ <code>type, si, insn_buf, prog, target_size</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>4.13</code> and <code>4.15</code> ✅
</li>
<li>
No changes between <code>4.15</code> and <code>4.18</code> ✅
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
