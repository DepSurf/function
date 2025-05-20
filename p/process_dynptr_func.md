# Function: <code>process_dynptr_func</code>

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
In <code>5.19</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
int process_dynptr_func(struct bpf_verifier_env *env, int regno, enum bpf_arg_type arg_type, struct bpf_call_arg_meta *meta);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/bpf/verifier.c (0)
Location: kernel/bpf/verifier.c:6120
Inline: False
Direct callers:
  - kernel/bpf/verifier.c:check_kfunc_args
  - kernel/bpf/verifier.c:check_func_arg
```
**Symbols:**

```
ffffffff82060f92-ffffffff82060fc5: process_dynptr_func.cold (STB_LOCAL)
ffffffff812e9410-ffffffff812e9955: process_dynptr_func (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
int process_dynptr_func(struct bpf_verifier_env *env, int regno, int insn_idx, enum bpf_arg_type arg_type, int clone_ref_obj_id);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/bpf/verifier.c (0)
Location: kernel/bpf/verifier.c:7188
Inline: False
Direct callers:
  - kernel/bpf/verifier.c:check_kfunc_args
  - kernel/bpf/verifier.c:check_kfunc_args
  - kernel/bpf/verifier.c:check_kfunc_args
  - kernel/bpf/verifier.c:check_func_arg
```
**Symbols:**

```
ffffffff81314330-ffffffff8131496a: process_dynptr_func (STB_LOCAL)
ffffffff820e03ad-ffffffff820e03de: process_dynptr_func.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
int process_dynptr_func(struct bpf_verifier_env *env, int regno, int insn_idx, enum bpf_arg_type arg_type, int clone_ref_obj_id);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/bpf/verifier.c (0)
Location: kernel/bpf/verifier.c:7565
Inline: False
Direct callers:
  - kernel/bpf/verifier.c:check_kfunc_args
  - kernel/bpf/verifier.c:check_kfunc_args
  - kernel/bpf/verifier.c:check_kfunc_args
  - kernel/bpf/verifier.c:check_func_arg
```
**Symbols:**

```
ffffffff813344b0-ffffffff81334aef: process_dynptr_func (STB_LOCAL)
ffffffff821bc6bb-ffffffff821bc6ec: process_dynptr_func.cold (STB_LOCAL)
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
<summary>Changed between <code>6.2</code> and <code>6.5</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>int insn_idx</code>
</li>
<li>
<b>Param added. </b>
<code>int clone_ref_obj_id</code>
</li>
<li>
<b>Param removed. </b>
<code>struct bpf_call_arg_meta *meta</code>
</li>
<li>
<b>Param reordered. </b>
<code>env, regno, arg_type, meta</code> ➡️ <code>env, regno, insn_idx, arg_type, clone_ref_obj_id</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>6.5</code> and <code>6.8</code> ✅
</li>
</ul>
