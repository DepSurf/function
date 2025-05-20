# Function: <code>btf_ctx_access</code>

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
bool btf_ctx_access(int off, int size, enum bpf_access_type type, const struct bpf_prog *prog, struct bpf_insn_access_aux *info);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/btf.c (ffffffff81224b20)
Location: kernel/bpf/btf.c:3686
Inline: False
```
**Symbols:**

```
ffffffff81224b20-ffffffff81224f4e: btf_ctx_access (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
bool btf_ctx_access(int off, int size, enum bpf_access_type type, const struct bpf_prog *prog, struct bpf_insn_access_aux *info);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/btf.c (ffffffff8122b480)
Location: kernel/bpf/btf.c:4582
Inline: False
```
**Symbols:**

```
ffffffff8122b480-ffffffff8122b9e3: btf_ctx_access (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
bool btf_ctx_access(int off, int size, enum bpf_access_type type, const struct bpf_prog *prog, struct bpf_insn_access_aux *info);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/btf.c (ffffffff8122fe80)
Location: kernel/bpf/btf.c:4653
Inline: False
```
**Symbols:**

```
ffffffff8122fe80-ffffffff812303e4: btf_ctx_access (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
bool btf_ctx_access(int off, int size, enum bpf_access_type type, const struct bpf_prog *prog, struct bpf_insn_access_aux *info);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/bpf/btf.c (0)
Location: kernel/bpf/btf.c:4701
Inline: False
```
**Symbols:**

```
ffffffff81cb94a1-ffffffff81cb94e2: btf_ctx_access.cold (STB_LOCAL)
ffffffff81268b30-ffffffff81269169: btf_ctx_access (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
bool btf_ctx_access(int off, int size, enum bpf_access_type type, const struct bpf_prog *prog, struct bpf_insn_access_aux *info);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/bpf/btf.c (0)
Location: kernel/bpf/btf.c:5219
Inline: False
Direct callers:
  - kernel/trace/bpf_trace.c:tracing_prog_is_valid_access
  - net/bpf/bpf_dummy_struct_ops.c:bpf_dummy_ops_is_valid_access
```
**Symbols:**

```
ffffffff81e6a857-ffffffff81e6a8a0: btf_ctx_access.cold (STB_LOCAL)
ffffffff812b5e40-ffffffff812b65d5: btf_ctx_access (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
bool btf_ctx_access(int off, int size, enum bpf_access_type type, const struct bpf_prog *prog, struct bpf_insn_access_aux *info);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/bpf/btf.c (0)
Location: kernel/bpf/btf.c:5851
Inline: False
Direct callers:
  - kernel/trace/bpf_trace.c:tracing_prog_is_valid_access
  - net/bpf/bpf_dummy_struct_ops.c:bpf_dummy_ops_is_valid_access
```
**Symbols:**

```
ffffffff8206190a-ffffffff82061944: btf_ctx_access.cold (STB_LOCAL)
ffffffff81316cb0-ffffffff8131758c: btf_ctx_access (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
bool btf_ctx_access(int off, int size, enum bpf_access_type type, const struct bpf_prog *prog, struct bpf_insn_access_aux *info);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/bpf/btf.c (0)
Location: kernel/bpf/btf.c:5925
Inline: False
Direct callers:
  - kernel/trace/bpf_trace.c:tracing_prog_is_valid_access
  - net/bpf/bpf_dummy_struct_ops.c:bpf_dummy_ops_is_valid_access
```
**Symbols:**

```
ffffffff820e0fc0-ffffffff820e0ffa: btf_ctx_access.cold (STB_LOCAL)
ffffffff81346ba0-ffffffff8134743b: btf_ctx_access (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
bool btf_ctx_access(int off, int size, enum bpf_access_type type, const struct bpf_prog *prog, struct bpf_insn_access_aux *info);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/bpf/btf.c (0)
Location: kernel/bpf/btf.c:6095
Inline: False
Direct callers:
  - kernel/trace/bpf_trace.c:tracing_prog_is_valid_access
  - net/bpf/bpf_dummy_struct_ops.c:bpf_dummy_ops_is_valid_access
```
**Symbols:**

```
ffffffff821bd808-ffffffff821bd842: btf_ctx_access.cold (STB_LOCAL)
ffffffff8136cf90-ffffffff8136d877: btf_ctx_access (STB_GLOBAL)
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
