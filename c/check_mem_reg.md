# Function: <code>check_mem_reg</code>

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
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int check_mem_reg(struct bpf_verifier_env *env, struct bpf_reg_state *reg, u32 regno, u32 mem_size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/verifier.c (ffffffff81216190)
Location: kernel/bpf/verifier.c:4531
Inline: False
Direct callers:
  - kernel/bpf/btf.c:btf_check_func_arg_match
```
**Symbols:**

```
ffffffff81216190-ffffffff81216332: check_mem_reg (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int check_mem_reg(struct bpf_verifier_env *env, struct bpf_reg_state *reg, u32 regno, u32 mem_size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/verifier.c (ffffffff8124c8c0)
Location: kernel/bpf/verifier.c:4645
Inline: False
Direct callers:
  - kernel/bpf/btf.c:btf_check_func_arg_match
```
**Symbols:**

```
ffffffff8124c8c0-ffffffff8124ca62: check_mem_reg (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int check_mem_reg(struct bpf_verifier_env *env, struct bpf_reg_state *reg, u32 regno, u32 mem_size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/verifier.c (ffffffff81290180)
Location: kernel/bpf/verifier.c:5294
Inline: False
Direct callers:
  - kernel/bpf/btf.c:btf_check_func_arg_match
```
**Symbols:**

```
ffffffff81290180-ffffffff81290413: check_mem_reg (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int check_mem_reg(struct bpf_verifier_env *env, struct bpf_reg_state *reg, u32 regno, u32 mem_size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/verifier.c (ffffffff812e9160)
Location: kernel/bpf/verifier.c:5844
Inline: False
Direct callers:
  - kernel/bpf/verifier.c:check_kfunc_args
  - kernel/bpf/btf.c:btf_check_func_arg_match
```
**Symbols:**

```
ffffffff812e9160-ffffffff812e93f3: check_mem_reg (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int check_mem_reg(struct bpf_verifier_env *env, struct bpf_reg_state *reg, u32 regno, u32 mem_size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/verifier.c (ffffffff813153b0)
Location: kernel/bpf/verifier.c:6928
Inline: False
Direct callers:
  - kernel/bpf/verifier.c:check_kfunc_args
  - kernel/bpf/btf.c:btf_check_func_arg_match
```
**Symbols:**

```
ffffffff813153b0-ffffffff81315610: check_mem_reg (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int check_mem_reg(struct bpf_verifier_env *env, struct bpf_reg_state *reg, u32 regno, u32 mem_size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/verifier.c (ffffffff81333ed0)
Location: kernel/bpf/verifier.c:7305
Inline: False
Direct callers:
  - kernel/bpf/verifier.c:check_kfunc_args
```
**Symbols:**

```
ffffffff81333ed0-ffffffff81334130: check_mem_reg (STB_LOCAL)
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
