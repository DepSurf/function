# Function: <code>check_stack_read_fixed_off</code>

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
int check_stack_read_fixed_off(struct bpf_verifier_env *env, struct bpf_func_state *reg_state, int off, int size, int dst_regno);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/verifier.c (ffffffff81212100)
Location: kernel/bpf/verifier.c:2853
Inline: False
Direct callers:
  - kernel/bpf/verifier.c:check_stack_read
```
**Symbols:**

```
ffffffff81212100-ffffffff812123b7: check_stack_read_fixed_off (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int check_stack_read_fixed_off(struct bpf_verifier_env *env, struct bpf_func_state *reg_state, int off, int size, int dst_regno);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/bpf/verifier.c (0)
Location: kernel/bpf/verifier.c:2919
Inline: False
Direct callers:
  - kernel/bpf/verifier.c:check_stack_read
```
**Symbols:**

```
ffffffff812476a0-ffffffff81247a92: check_stack_read_fixed_off (STB_LOCAL)
ffffffff81cb8aca-ffffffff81cb8ae6: check_stack_read_fixed_off.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int check_stack_read_fixed_off(struct bpf_verifier_env *env, struct bpf_func_state *reg_state, int off, int size, int dst_regno);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/bpf/verifier.c (0)
Location: kernel/bpf/verifier.c:3263
Inline: False
Direct callers:
  - kernel/bpf/verifier.c:check_stack_read
```
**Symbols:**

```
ffffffff8128d7a0-ffffffff8128dcf5: check_stack_read_fixed_off (STB_LOCAL)
ffffffff81e69d42-ffffffff81e69d67: check_stack_read_fixed_off.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
int check_stack_read_fixed_off(struct bpf_verifier_env *env, struct bpf_func_state *reg_state, int off, int size, int dst_regno);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/bpf/verifier.c (0)
Location: kernel/bpf/verifier.c:3705
Inline: False
Direct callers:
  - kernel/bpf/verifier.c:check_stack_read
```
**Symbols:**

```
ffffffff812e4bc0-ffffffff812e5117: check_stack_read_fixed_off (STB_LOCAL)
ffffffff82060b33-ffffffff82060b58: check_stack_read_fixed_off.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
int check_stack_read_fixed_off(struct bpf_verifier_env *env, struct bpf_func_state *reg_state, int off, int size, int dst_regno);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/bpf/verifier.c (0)
Location: kernel/bpf/verifier.c:4588
Inline: False
Direct callers:
  - kernel/bpf/verifier.c:check_mem_access
```
**Symbols:**

```
ffffffff813084c0-ffffffff81308a7e: check_stack_read_fixed_off (STB_LOCAL)
ffffffff820df6b9-ffffffff820df781: check_stack_read_fixed_off.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
int check_stack_read_fixed_off(struct bpf_verifier_env *env, struct bpf_func_state *reg_state, int off, int size, int dst_regno);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/bpf/verifier.c (0)
Location: kernel/bpf/verifier.c:4725
Inline: False
Direct callers:
  - kernel/bpf/verifier.c:check_mem_access
```
**Symbols:**

```
ffffffff8132ba30-ffffffff8132c221: check_stack_read_fixed_off (STB_LOCAL)
ffffffff821bc030-ffffffff821bc137: check_stack_read_fixed_off.cold (STB_LOCAL)
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
