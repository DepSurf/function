# Function: <code>bpf_core_apply</code>

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
In <code>5.11</code>: Absent ⚠️
</li>
<li>
In <code>5.13</code>: Absent ⚠️
</li>
<li>
In <code>5.15</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int bpf_core_apply(struct bpf_core_ctx *ctx, const struct bpf_core_relo *relo, int relo_idx, void *insn);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/btf.c (ffffffff812b93f0)
Location: kernel/bpf/btf.c:7733
Inline: False
Direct callers:
  - kernel/bpf/verifier.c:check_core_relo
```
**Symbols:**

```
ffffffff812b93f0-ffffffff812b974b: bpf_core_apply (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int bpf_core_apply(struct bpf_core_ctx *ctx, const struct bpf_core_relo *relo, int relo_idx, void *insn);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/btf.c (ffffffff8131b420)
Location: kernel/bpf/btf.c:8154
Inline: False
Direct callers:
  - kernel/bpf/verifier.c:check_core_relo
```
**Symbols:**

```
ffffffff8131b420-ffffffff8131b78a: bpf_core_apply (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int bpf_core_apply(struct bpf_core_ctx *ctx, const struct bpf_core_relo *relo, int relo_idx, void *insn);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/btf.c (ffffffff8134aa20)
Location: kernel/bpf/btf.c:8413
Inline: False
Direct callers:
  - kernel/bpf/verifier.c:check_core_relo
```
**Symbols:**

```
ffffffff8134aa20-ffffffff8134ad8b: bpf_core_apply (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int bpf_core_apply(struct bpf_core_ctx *ctx, const struct bpf_core_relo *relo, int relo_idx, void *insn);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/btf.c (ffffffff813711d0)
Location: kernel/bpf/btf.c:8478
Inline: False
Direct callers:
  - kernel/bpf/verifier.c:check_core_relo
```
**Symbols:**

```
ffffffff813711d0-ffffffff81371575: bpf_core_apply (STB_GLOBAL)
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
No changes between <code>5.19</code> and <code>6.2</code> ✅
</li>
<li>
No changes between <code>6.2</code> and <code>6.5</code> ✅
</li>
<li>
No changes between <code>6.5</code> and <code>6.8</code> ✅
</li>
</ul>
