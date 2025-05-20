# Function: <code>check_stack_access</code>

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
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
int check_stack_access(struct bpf_verifier_env *env, const struct bpf_reg_state *reg, int off, int size);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/bpf/verifier.c (ffffffff811c7e40)
Location: kernel/bpf/verifier.c:1393
Inline: True
Direct callers:
  - kernel/bpf/verifier.c:adjust_ptr_min_max_vals
  - kernel/bpf/verifier.c:check_mem_access
```
**Symbols:**

```
ffffffff811c7e40-ffffffff811c7ee6: check_stack_access (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
int check_stack_access(struct bpf_verifier_env *env, const struct bpf_reg_state *reg, int off, int size);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/bpf/verifier.c (ffffffff811db5b0)
Location: kernel/bpf/verifier.c:2103
Inline: True
Direct callers:
  - kernel/bpf/verifier.c:adjust_ptr_min_max_vals
  - kernel/bpf/verifier.c:check_mem_access
```
**Symbols:**

```
ffffffff811db5b0-ffffffff811db660: check_stack_access (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
int check_stack_access(struct bpf_verifier_env *env, const struct bpf_reg_state *reg, int off, int size);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/bpf/verifier.c (ffffffff811e7d00)
Location: kernel/bpf/verifier.c:2104
Inline: True
Direct callers:
  - kernel/bpf/verifier.c:adjust_ptr_min_max_vals
  - kernel/bpf/verifier.c:check_mem_access
```
**Symbols:**

```
ffffffff811e7d00-ffffffff811e7db0: check_stack_access (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
int check_stack_access(struct bpf_verifier_env *env, const struct bpf_reg_state *reg, int off, int size);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/bpf/verifier.c (ffffffff8120d7d0)
Location: kernel/bpf/verifier.c:2433
Inline: True
Direct callers:
  - kernel/bpf/verifier.c:adjust_ptr_min_max_vals
  - kernel/bpf/verifier.c:check_mem_access
```
**Symbols:**

```
ffffffff8120d7d0-ffffffff8120d880: check_stack_access (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
int check_stack_access(struct bpf_verifier_env *env, const struct bpf_reg_state *reg, int off, int size);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/bpf/verifier.c (ffffffff8120dfa0)
Location: kernel/bpf/verifier.c:2506
Inline: True
Direct callers:
  - kernel/bpf/verifier.c:adjust_ptr_min_max_vals
  - kernel/bpf/verifier.c:check_mem_access
```
**Symbols:**

```
ffffffff8120dfa0-ffffffff8120e050: check_stack_access (STB_LOCAL)
```
</details>
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
int check_stack_access(struct bpf_verifier_env *env, const struct bpf_reg_state *reg, int off, int size);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/bpf/verifier.c (ffff80001026b7a0)
Location: kernel/bpf/verifier.c:2104
Inline: True
Direct callers:
  - kernel/bpf/verifier.c:adjust_ptr_min_max_vals
  - kernel/bpf/verifier.c:check_mem_access
```
**Symbols:**

```
ffff80001026b7a0-ffff80001026b874: check_stack_access (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
int check_stack_access(struct bpf_verifier_env *env, const struct bpf_reg_state *reg, int off, int size);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/bpf/verifier.c (c049d81c)
Location: kernel/bpf/verifier.c:2104
Inline: True
Direct callers:
  - kernel/bpf/verifier.c:adjust_ptr_min_max_vals
  - kernel/bpf/verifier.c:check_mem_access
```
**Symbols:**

```
c049d81c-c049d8e4: check_stack_access (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
int check_stack_access(struct bpf_verifier_env *env, const struct bpf_reg_state *reg, int off, int size);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/bpf/verifier.c (c000000000311810)
Location: kernel/bpf/verifier.c:2104
Inline: True
Direct callers:
  - kernel/bpf/verifier.c:adjust_ptr_min_max_vals
  - kernel/bpf/verifier.c:check_mem_access
```
**Symbols:**

```
c000000000311810-c000000000311918: check_stack_access (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
int check_stack_access(struct bpf_verifier_env *env, const struct bpf_reg_state *reg, int off, int size);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/bpf/verifier.c (ffffffe0001a5cee)
Location: kernel/bpf/verifier.c:2104
Inline: True
Direct callers:
  - kernel/bpf/verifier.c:adjust_ptr_min_max_vals
  - kernel/bpf/verifier.c:check_mem_access
```
**Symbols:**

```
ffffffe0001a5cee-ffffffe0001a5d7c: check_stack_access (STB_LOCAL)
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
int check_stack_access(struct bpf_verifier_env *env, const struct bpf_reg_state *reg, int off, int size);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/bpf/verifier.c (ffffffff811e0320)
Location: kernel/bpf/verifier.c:2104
Inline: True
Direct callers:
  - kernel/bpf/verifier.c:adjust_ptr_min_max_vals
  - kernel/bpf/verifier.c:check_mem_access
```
**Symbols:**

```
ffffffff811e0320-ffffffff811e03d0: check_stack_access (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
int check_stack_access(struct bpf_verifier_env *env, const struct bpf_reg_state *reg, int off, int size);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/bpf/verifier.c (ffffffff811d30e0)
Location: kernel/bpf/verifier.c:2104
Inline: True
Direct callers:
  - kernel/bpf/verifier.c:adjust_ptr_min_max_vals
  - kernel/bpf/verifier.c:check_mem_access
```
**Symbols:**

```
ffffffff811d30e0-ffffffff811d3190: check_stack_access (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
int check_stack_access(struct bpf_verifier_env *env, const struct bpf_reg_state *reg, int off, int size);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/bpf/verifier.c (ffffffff811de0f0)
Location: kernel/bpf/verifier.c:2104
Inline: True
Direct callers:
  - kernel/bpf/verifier.c:adjust_ptr_min_max_vals
  - kernel/bpf/verifier.c:check_mem_access
```
**Symbols:**

```
ffffffff811de0f0-ffffffff811de1a0: check_stack_access (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
int check_stack_access(struct bpf_verifier_env *env, const struct bpf_reg_state *reg, int off, int size);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/bpf/verifier.c (ffffffff811ec500)
Location: kernel/bpf/verifier.c:2104
Inline: True
Direct callers:
  - kernel/bpf/verifier.c:adjust_ptr_min_max_vals
  - kernel/bpf/verifier.c:check_mem_access
```
**Symbols:**

```
ffffffff811ec500-ffffffff811ec5b0: check_stack_access (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
