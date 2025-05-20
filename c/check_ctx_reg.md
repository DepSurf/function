# Function: <code>check_ctx_reg</code>

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
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
int check_ctx_reg(struct bpf_verifier_env *env, const struct bpf_reg_state *reg, int regno);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/bpf/verifier.c (ffffffff811b98e0)
Location: kernel/bpf/verifier.c:1620
Inline: True
Direct callers:
  - kernel/bpf/verifier.c:check_func_arg
  - kernel/bpf/verifier.c:check_mem_access
```
**Symbols:**

```
ffffffff811b98e0-ffffffff811b9975: check_ctx_reg (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
int check_ctx_reg(struct bpf_verifier_env *env, const struct bpf_reg_state *reg, int regno);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/bpf/verifier.c (ffffffff811c9270)
Location: kernel/bpf/verifier.c:1879
Inline: True
Direct callers:
  - kernel/bpf/verifier.c:check_func_arg
  - kernel/bpf/verifier.c:check_mem_access
```
**Symbols:**

```
ffffffff811c9270-ffffffff811c9305: check_ctx_reg (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
int check_ctx_reg(struct bpf_verifier_env *env, const struct bpf_reg_state *reg, int regno);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/bpf/verifier.c (ffffffff811dcd80)
Location: kernel/bpf/verifier.c:2669
Inline: True
Direct callers:
  - kernel/bpf/verifier.c:check_func_arg
  - kernel/bpf/verifier.c:check_mem_access
```
**Symbols:**

```
ffffffff811dcd80-ffffffff811dce1d: check_ctx_reg (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
int check_ctx_reg(struct bpf_verifier_env *env, const struct bpf_reg_state *reg, int regno);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/bpf/verifier.c (ffffffff811e9520)
Location: kernel/bpf/verifier.c:2670
Inline: True
Direct callers:
  - kernel/bpf/verifier.c:do_check
  - kernel/bpf/verifier.c:check_func_arg
  - kernel/bpf/verifier.c:check_mem_access
```
**Symbols:**

```
ffffffff811e9520-ffffffff811e95bd: check_ctx_reg (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
int check_ctx_reg(struct bpf_verifier_env *env, const struct bpf_reg_state *reg, int regno);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/bpf/verifier.c (ffffffff812101c0)
Location: kernel/bpf/verifier.c:3018
Inline: True
Direct callers:
  - kernel/bpf/verifier.c:check_ld_abs
  - kernel/bpf/verifier.c:check_func_arg
  - kernel/bpf/verifier.c:check_mem_access
  - kernel/bpf/btf.c:btf_check_func_arg_match
```
**Symbols:**

```
ffffffff812101c0-ffffffff81210259: check_ctx_reg (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
int check_ctx_reg(struct bpf_verifier_env *env, const struct bpf_reg_state *reg, int regno);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/bpf/verifier.c (ffffffff81210e70)
Location: kernel/bpf/verifier.c:3142
Inline: True
Direct callers:
  - kernel/bpf/verifier.c:check_ld_abs
  - kernel/bpf/verifier.c:check_func_arg
  - kernel/bpf/verifier.c:check_mem_access
  - kernel/bpf/btf.c:btf_check_func_arg_match
```
**Symbols:**

```
ffffffff81210e70-ffffffff81210f09: check_ctx_reg (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
int check_ctx_reg(struct bpf_verifier_env *env, const struct bpf_reg_state *reg, int regno);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/bpf/verifier.c (ffffffff81212ac0)
Location: kernel/bpf/verifier.c:3685
Inline: True
Direct callers:
  - kernel/bpf/verifier.c:check_ld_abs
  - kernel/bpf/verifier.c:check_func_arg
  - kernel/bpf/verifier.c:check_mem_access
  - kernel/bpf/btf.c:btf_check_func_arg_match
```
**Symbols:**

```
ffffffff81212ac0-ffffffff81212b56: check_ctx_reg (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
int check_ctx_reg(struct bpf_verifier_env *env, const struct bpf_reg_state *reg, int regno);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/bpf/verifier.c (ffffffff812483c0)
Location: kernel/bpf/verifier.c:3771
Inline: True
Direct callers:
  - kernel/bpf/verifier.c:check_ld_abs
  - kernel/bpf/verifier.c:check_func_arg
  - kernel/bpf/verifier.c:check_mem_access
  - kernel/bpf/btf.c:btf_check_func_arg_match
```
**Symbols:**

```
ffffffff812483c0-ffffffff81248456: check_ctx_reg (STB_GLOBAL)
```
</details>
</li>
<li>
In <code>5.19</code>: Absent ⚠️
</li>
<li>
In <code>6.2</code>: Absent ⚠️
</li>
<li>
In <code>6.5</code>: Absent ⚠️
</li>
<li>
In <code>6.8</code>: Absent ⚠️
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Selective Inline ⚠️</summary>

```c
int check_ctx_reg(struct bpf_verifier_env *env, const struct bpf_reg_state *reg, int regno);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/bpf/verifier.c (ffff80001026cc50)
Location: kernel/bpf/verifier.c:2670
Inline: True
Direct callers:
  - kernel/bpf/verifier.c:do_check
  - kernel/bpf/verifier.c:check_func_arg
  - kernel/bpf/verifier.c:check_mem_access
```
**Symbols:**

```
ffff80001026cc50-ffff80001026cd10: check_ctx_reg (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
int check_ctx_reg(struct bpf_verifier_env *env, const struct bpf_reg_state *reg, int regno);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/bpf/verifier.c (c049f218)
Location: kernel/bpf/verifier.c:2670
Inline: True
Direct callers:
  - kernel/bpf/verifier.c:do_check
  - kernel/bpf/verifier.c:check_func_arg
  - kernel/bpf/verifier.c:check_mem_access
```
**Symbols:**

```
c049f218-c049f2e0: check_ctx_reg (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
int check_ctx_reg(struct bpf_verifier_env *env, const struct bpf_reg_state *reg, int regno);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/bpf/verifier.c (c0000000003132f0)
Location: kernel/bpf/verifier.c:2670
Inline: True
Direct callers:
  - kernel/bpf/verifier.c:do_check
  - kernel/bpf/verifier.c:check_func_arg
  - kernel/bpf/verifier.c:check_mem_access
```
**Symbols:**

```
c0000000003132f0-c0000000003133e0: check_ctx_reg (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
int check_ctx_reg(struct bpf_verifier_env *env, const struct bpf_reg_state *reg, int regno);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/bpf/verifier.c (ffffffe0001a6eba)
Location: kernel/bpf/verifier.c:2670
Inline: True
Direct callers:
  - kernel/bpf/verifier.c:do_check
  - kernel/bpf/verifier.c:check_func_arg
  - kernel/bpf/verifier.c:check_mem_access
```
**Symbols:**

```
ffffffe0001a6eba-ffffffe0001a6f3a: check_ctx_reg (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Selective Inline ⚠️</summary>

```c
int check_ctx_reg(struct bpf_verifier_env *env, const struct bpf_reg_state *reg, int regno);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/bpf/verifier.c (ffffffff811e1b40)
Location: kernel/bpf/verifier.c:2670
Inline: True
Direct callers:
  - kernel/bpf/verifier.c:do_check
  - kernel/bpf/verifier.c:check_func_arg
  - kernel/bpf/verifier.c:check_mem_access
```
**Symbols:**

```
ffffffff811e1b40-ffffffff811e1bdd: check_ctx_reg (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
int check_ctx_reg(struct bpf_verifier_env *env, const struct bpf_reg_state *reg, int regno);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/bpf/verifier.c (ffffffff811d4900)
Location: kernel/bpf/verifier.c:2670
Inline: True
Direct callers:
  - kernel/bpf/verifier.c:do_check
  - kernel/bpf/verifier.c:check_func_arg
  - kernel/bpf/verifier.c:check_mem_access
```
**Symbols:**

```
ffffffff811d4900-ffffffff811d499d: check_ctx_reg (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
int check_ctx_reg(struct bpf_verifier_env *env, const struct bpf_reg_state *reg, int regno);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/bpf/verifier.c (ffffffff811df910)
Location: kernel/bpf/verifier.c:2670
Inline: True
Direct callers:
  - kernel/bpf/verifier.c:do_check
  - kernel/bpf/verifier.c:check_func_arg
  - kernel/bpf/verifier.c:check_mem_access
```
**Symbols:**

```
ffffffff811df910-ffffffff811df9ad: check_ctx_reg (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
int check_ctx_reg(struct bpf_verifier_env *env, const struct bpf_reg_state *reg, int regno);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/bpf/verifier.c (ffffffff811edd20)
Location: kernel/bpf/verifier.c:2670
Inline: True
Direct callers:
  - kernel/bpf/verifier.c:do_check
  - kernel/bpf/verifier.c:check_func_arg
  - kernel/bpf/verifier.c:check_mem_access
```
**Symbols:**

```
ffffffff811edd20-ffffffff811eddbd: check_ctx_reg (STB_LOCAL)
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
<li>
No changes between <code>amd64</code> and <code>riscv64</code> ✅
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
