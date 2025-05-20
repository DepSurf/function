# Function: <code>btf_check_func_arg_match</code>

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
int btf_check_func_arg_match(struct bpf_verifier_env *env, int subprog, struct bpf_reg_state *reg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/btf.c (ffffffff81225650)
Location: kernel/bpf/btf.c:4374
Inline: False
Direct callers:
  - kernel/bpf/verifier.c:do_check_common
  - kernel/bpf/verifier.c:check_func_call
  - kernel/bpf/verifier.c:check_func_call
```
**Symbols:**

```
ffffffff81225650-ffffffff81225981: btf_check_func_arg_match (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int btf_check_func_arg_match(struct bpf_verifier_env *env, int subprog, struct bpf_reg_state *reg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/btf.c (ffffffff8122bea0)
Location: kernel/bpf/btf.c:5298
Inline: False
Direct callers:
  - kernel/bpf/verifier.c:do_check_common
  - kernel/bpf/verifier.c:check_func_call
  - kernel/bpf/verifier.c:check_func_call
```
**Symbols:**

```
ffffffff8122bea0-ffffffff8122c288: btf_check_func_arg_match (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int btf_check_func_arg_match(struct bpf_verifier_env *env, const struct btf *btf, u32 func_id, struct bpf_reg_state *regs, bool ptr_to_mem_ok);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/btf.c (ffffffff812306a0)
Location: kernel/bpf/btf.c:5384
Inline: False
Direct callers:
  - kernel/bpf/btf.c:btf_check_kfunc_arg_match
  - kernel/bpf/btf.c:btf_check_subprog_arg_match
```
**Symbols:**

```
ffffffff812306a0-ffffffff81230c92: btf_check_func_arg_match (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int btf_check_func_arg_match(struct bpf_verifier_env *env, const struct btf *btf, u32 func_id, struct bpf_reg_state *regs, bool ptr_to_mem_ok);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/bpf/btf.c (0)
Location: kernel/bpf/btf.c:5437
Inline: False
Direct callers:
  - kernel/bpf/btf.c:btf_check_kfunc_arg_match
  - kernel/bpf/btf.c:btf_check_subprog_arg_match
```
**Symbols:**

```
ffffffff81269420-ffffffff81269b69: btf_check_func_arg_match (STB_LOCAL)
ffffffff81cb94f6-ffffffff81cb9519: btf_check_func_arg_match.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int btf_check_func_arg_match(struct bpf_verifier_env *env, const struct btf *btf, u32 func_id, struct bpf_reg_state *regs, bool ptr_to_mem_ok);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/bpf/btf.c (0)
Location: kernel/bpf/btf.c:6057
Inline: False
Direct callers:
  - kernel/bpf/btf.c:btf_check_kfunc_arg_match
  - kernel/bpf/btf.c:btf_check_subprog_arg_match
```
**Symbols:**

```
ffffffff812b8080-ffffffff812b8d33: btf_check_func_arg_match (STB_LOCAL)
ffffffff81e6a995-ffffffff81e6a9b1: btf_check_func_arg_match.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int btf_check_func_arg_match(struct bpf_verifier_env *env, const struct btf *btf, u32 func_id, struct bpf_reg_state *regs, bool ptr_to_mem_ok, bool processing_call);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/btf.c (ffffffff81316440)
Location: kernel/bpf/btf.c:6656
Inline: False
Direct callers:
  - kernel/bpf/btf.c:btf_check_subprog_call
  - kernel/bpf/btf.c:btf_check_subprog_arg_match
```
**Symbols:**

```
ffffffff81316440-ffffffff8131699e: btf_check_func_arg_match (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int btf_check_func_arg_match(struct bpf_verifier_env *env, const struct btf *btf, u32 func_id, struct bpf_reg_state *regs, bool ptr_to_mem_ok, bool processing_call);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/btf.c (ffffffff81346310)
Location: kernel/bpf/btf.c:6758
Inline: False
Direct callers:
  - kernel/bpf/btf.c:btf_check_subprog_call
  - kernel/bpf/btf.c:btf_check_subprog_arg_match
```
**Symbols:**

```
ffffffff81346310-ffffffff8134688a: btf_check_func_arg_match (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/bpf/verifier.c (ffffffff813355f0)
Location: kernel/bpf/verifier.c:9254
Inline: True
Direct callers:
  - kernel/bpf/verifier.c:btf_check_subprog_call
```
**Symbols:**

```
ffffffff813355f0-ffffffff81335814: btf_check_func_arg_match.isra.0 (STB_LOCAL)
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
<details>
<summary>Changed between <code>5.11</code> and <code>5.13</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>const struct btf *btf</code>
</li>
<li>
<b>Param added. </b>
<code>u32 func_id</code>
</li>
<li>
<b>Param added. </b>
<code>struct bpf_reg_state *regs</code>
</li>
<li>
<b>Param added. </b>
<code>bool ptr_to_mem_ok</code>
</li>
<li>
<b>Param removed. </b>
<code>int subprog</code>
</li>
<li>
<b>Param removed. </b>
<code>struct bpf_reg_state *reg</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>5.13</code> and <code>5.15</code> ✅
</li>
<li>
No changes between <code>5.15</code> and <code>5.19</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>5.19</code> and <code>6.2</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>bool processing_call</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>6.2</code> and <code>6.5</code> ✅
</li>
</ul>
