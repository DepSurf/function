# Function: <code>btf_check_subprog_arg_match</code>

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
int btf_check_subprog_arg_match(struct bpf_verifier_env *env, int subprog, struct bpf_reg_state *regs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/btf.c (ffffffff81230f00)
Location: kernel/bpf/btf.c:5524
Inline: False
Direct callers:
  - kernel/bpf/verifier.c:do_check_common
```
**Symbols:**

```
ffffffff81230f00-ffffffff81230f89: btf_check_subprog_arg_match (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int btf_check_subprog_arg_match(struct bpf_verifier_env *env, int subprog, struct bpf_reg_state *regs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/bpf/btf.c (0)
Location: kernel/bpf/btf.c:5577
Inline: False
Direct callers:
  - kernel/bpf/verifier.c:do_check_common
  - kernel/bpf/verifier.c:__check_func_call
  - kernel/bpf/verifier.c:__check_func_call
```
**Symbols:**

```
ffffffff81cb9519-ffffffff81cb9544: btf_check_subprog_arg_match.cold (STB_LOCAL)
ffffffff81269e10-ffffffff81269ecb: btf_check_subprog_arg_match (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int btf_check_subprog_arg_match(struct bpf_verifier_env *env, int subprog, struct bpf_reg_state *regs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/bpf/btf.c (0)
Location: kernel/bpf/btf.c:6310
Inline: False
Direct callers:
  - kernel/bpf/verifier.c:do_check_common
  - kernel/bpf/verifier.c:__check_func_call
  - kernel/bpf/verifier.c:__check_func_call
```
**Symbols:**

```
ffffffff81e6a9b1-ffffffff81e6a9dc: btf_check_subprog_arg_match.cold (STB_LOCAL)
ffffffff812b8d40-ffffffff812b8e15: btf_check_subprog_arg_match (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
int btf_check_subprog_arg_match(struct bpf_verifier_env *env, int subprog, struct bpf_reg_state *regs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/bpf/btf.c (0)
Location: kernel/bpf/btf.c:6765
Inline: False
Direct callers:
  - kernel/bpf/verifier.c:do_check_common
```
**Symbols:**

```
ffffffff82061958-ffffffff82061981: btf_check_subprog_arg_match.cold (STB_LOCAL)
ffffffff81317f90-ffffffff81318064: btf_check_subprog_arg_match (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
int btf_check_subprog_arg_match(struct bpf_verifier_env *env, int subprog, struct bpf_reg_state *regs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/bpf/btf.c (0)
Location: kernel/bpf/btf.c:6867
Inline: False
Direct callers:
  - kernel/bpf/verifier.c:do_check_common
```
**Symbols:**

```
ffffffff820e100e-ffffffff820e1037: btf_check_subprog_arg_match.cold (STB_LOCAL)
ffffffff81347f20-ffffffff81347ff4: btf_check_subprog_arg_match (STB_GLOBAL)
```
</details>
</li>
<li>
In <code>6.8</code>: Absent ⚠️
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
</ul>
