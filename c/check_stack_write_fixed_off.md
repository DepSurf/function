# Function: <code>check_stack_write_fixed_off</code>

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
int check_stack_write_fixed_off(struct bpf_verifier_env *env, struct bpf_func_state *state, int off, int size, int value_regno, int insn_idx);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/verifier.c (ffffffff81212550)
Location: kernel/bpf/verifier.c:2582
Inline: False
Direct callers:
  - kernel/bpf/verifier.c:check_mem_access
```
**Symbols:**

```
ffffffff81212550-ffffffff8121297d: check_stack_write_fixed_off (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int check_stack_write_fixed_off(struct bpf_verifier_env *env, struct bpf_func_state *state, int off, int size, int value_regno, int insn_idx);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/bpf/verifier.c (0)
Location: kernel/bpf/verifier.c:2650
Inline: False
Direct callers:
  - kernel/bpf/verifier.c:check_mem_access
```
**Symbols:**

```
ffffffff81247d40-ffffffff8124827f: check_stack_write_fixed_off (STB_LOCAL)
ffffffff81cb8b2d-ffffffff81cb8c24: check_stack_write_fixed_off.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int check_stack_write_fixed_off(struct bpf_verifier_env *env, struct bpf_func_state *state, int off, int size, int value_regno, int insn_idx);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/bpf/verifier.c (0)
Location: kernel/bpf/verifier.c:2992
Inline: False
Direct callers:
  - kernel/bpf/verifier.c:check_mem_access
```
**Symbols:**

```
ffffffff8128dfe0-ffffffff8128e60c: check_stack_write_fixed_off (STB_LOCAL)
ffffffff81e69dae-ffffffff81e69f35: check_stack_write_fixed_off.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
int check_stack_write_fixed_off(struct bpf_verifier_env *env, struct bpf_func_state *state, int off, int size, int value_regno, int insn_idx);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/bpf/verifier.c (0)
Location: kernel/bpf/verifier.c:3417
Inline: False
Direct callers:
  - kernel/bpf/verifier.c:check_mem_access
```
**Symbols:**

```
ffffffff812e6850-ffffffff812e6e05: check_stack_write_fixed_off (STB_LOCAL)
ffffffff82060c86-ffffffff82060d7f: check_stack_write_fixed_off.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
int check_stack_write_fixed_off(struct bpf_verifier_env *env, struct bpf_func_state *state, int off, int size, int value_regno, int insn_idx);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/bpf/verifier.c (0)
Location: kernel/bpf/verifier.c:4285
Inline: False
Direct callers:
  - kernel/bpf/verifier.c:check_mem_access
```
**Symbols:**

```
ffffffff8130dfc0-ffffffff8130e8f8: check_stack_write_fixed_off (STB_LOCAL)
ffffffff820dfc8d-ffffffff820dfe70: check_stack_write_fixed_off.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
int check_stack_write_fixed_off(struct bpf_verifier_env *env, struct bpf_func_state *state, int off, int size, int value_regno, int insn_idx);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/bpf/verifier.c (0)
Location: kernel/bpf/verifier.c:4444
Inline: False
Direct callers:
  - kernel/bpf/verifier.c:check_mem_access
```
**Symbols:**

```
ffffffff8132a9f0-ffffffff8132b268: check_stack_write_fixed_off (STB_LOCAL)
ffffffff821bbd14-ffffffff821bbef6: check_stack_write_fixed_off.cold (STB_LOCAL)
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
