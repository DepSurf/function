# Function: <code>check_mem_size_reg</code>

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
int check_mem_size_reg(struct bpf_verifier_env *env, struct bpf_reg_state *reg, u32 regno, bool zero_size_allowed, struct bpf_call_arg_meta *meta);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/verifier.c (ffffffff81280180)
Location: kernel/bpf/verifier.c:5239
Inline: False
Direct callers:
  - kernel/bpf/verifier.c:check_func_arg
  - kernel/bpf/verifier.c:check_kfunc_mem_size_reg
  - kernel/bpf/verifier.c:check_kfunc_mem_size_reg
  - kernel/bpf/verifier.c:check_kfunc_mem_size_reg
  - kernel/bpf/verifier.c:check_kfunc_mem_size_reg
```
**Symbols:**

```
ffffffff81280180-ffffffff81280291: check_mem_size_reg (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int check_mem_size_reg(struct bpf_verifier_env *env, struct bpf_reg_state *reg, u32 regno, bool zero_size_allowed, struct bpf_call_arg_meta *meta);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/verifier.c (ffffffff812e8730)
Location: kernel/bpf/verifier.c:5789
Inline: False
Direct callers:
  - kernel/bpf/verifier.c:check_func_arg
  - kernel/bpf/verifier.c:check_func_arg
  - kernel/bpf/verifier.c:check_kfunc_mem_size_reg
  - kernel/bpf/verifier.c:check_kfunc_mem_size_reg
  - kernel/bpf/verifier.c:check_kfunc_mem_size_reg
  - kernel/bpf/verifier.c:check_kfunc_mem_size_reg
```
**Symbols:**

```
ffffffff812e8730-ffffffff812e8849: check_mem_size_reg (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int check_mem_size_reg(struct bpf_verifier_env *env, struct bpf_reg_state *reg, u32 regno, bool zero_size_allowed, struct bpf_call_arg_meta *meta);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/verifier.c (ffffffff81313b20)
Location: kernel/bpf/verifier.c:6873
Inline: False
Direct callers:
  - kernel/bpf/verifier.c:check_func_arg
  - kernel/bpf/verifier.c:check_func_arg
  - kernel/bpf/verifier.c:check_kfunc_mem_size_reg
  - kernel/bpf/verifier.c:check_kfunc_mem_size_reg
  - kernel/bpf/verifier.c:check_kfunc_mem_size_reg
  - kernel/bpf/verifier.c:check_kfunc_mem_size_reg
```
**Symbols:**

```
ffffffff81313b20-ffffffff81313c2c: check_mem_size_reg (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int check_mem_size_reg(struct bpf_verifier_env *env, struct bpf_reg_state *reg, u32 regno, bool zero_size_allowed, struct bpf_call_arg_meta *meta);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/verifier.c (ffffffff81334140)
Location: kernel/bpf/verifier.c:7252
Inline: False
Direct callers:
  - kernel/bpf/verifier.c:check_func_arg
  - kernel/bpf/verifier.c:check_func_arg
  - kernel/bpf/verifier.c:check_kfunc_mem_size_reg
  - kernel/bpf/verifier.c:check_kfunc_mem_size_reg
  - kernel/bpf/verifier.c:check_kfunc_mem_size_reg
  - kernel/bpf/verifier.c:check_kfunc_mem_size_reg
```
**Symbols:**

```
ffffffff81334140-ffffffff8133420b: check_mem_size_reg (STB_LOCAL)
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
