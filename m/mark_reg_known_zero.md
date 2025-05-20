# Function: <code>mark_reg_known_zero</code>

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
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
void mark_reg_known_zero(struct bpf_verifier_env *env, struct bpf_reg_state *regs, u32 regno);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/bpf/verifier.c (ffffffff811a44c0)
Location: kernel/bpf/verifier.c:452
Inline: True
Direct callers:
  - kernel/bpf/verifier.c:do_check
  - kernel/bpf/verifier.c:do_check
  - kernel/bpf/verifier.c:do_check
  - kernel/bpf/verifier.c:check_mem_access
```
**Symbols:**

```
ffffffff811a44c0-ffffffff811a45a3: mark_reg_known_zero (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
void mark_reg_known_zero(struct bpf_verifier_env *env, struct bpf_reg_state *regs, u32 regno);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/bpf/verifier.c (ffffffff811b7dc0)
Location: kernel/bpf/verifier.c:579
Inline: True
Direct callers:
  - kernel/bpf/verifier.c:check_helper_call
  - kernel/bpf/verifier.c:check_mem_access
  - kernel/bpf/verifier.c:init_reg_state
  - kernel/bpf/verifier.c:init_reg_state
```
**Symbols:**

```
ffffffff811b7dc0-ffffffff811b7ea4: mark_reg_known_zero (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
void mark_reg_known_zero(struct bpf_verifier_env *env, struct bpf_reg_state *regs, u32 regno);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/bpf/verifier.c (ffffffff811c71d0)
Location: kernel/bpf/verifier.c:827
Inline: True
Direct callers:
  - kernel/bpf/verifier.c:check_helper_call
  - kernel/bpf/verifier.c:check_helper_call
  - kernel/bpf/verifier.c:check_mem_access
  - kernel/bpf/verifier.c:init_reg_state
  - kernel/bpf/verifier.c:init_reg_state
```
**Symbols:**

```
ffffffff811c71d0-ffffffff811c7230: mark_reg_known_zero (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline, Transformation ⚠️</summary>

```c
void mark_reg_known_zero(struct bpf_verifier_env *env, struct bpf_reg_state *regs, u32 regno);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/bpf/verifier.c (ffffffff811e54c7)
Location: kernel/bpf/verifier.c:886
Inline: True
Direct callers:
  - kernel/bpf/verifier.c:do_check
  - kernel/bpf/verifier.c:check_helper_call
  - kernel/bpf/verifier.c:check_helper_call
  - kernel/bpf/verifier.c:check_helper_call
  - kernel/bpf/verifier.c:check_helper_call
  - kernel/bpf/verifier.c:check_mem_access
  - kernel/bpf/verifier.c:init_reg_state
  - kernel/bpf/verifier.c:init_reg_state
```
**Symbols:**

```
ffffffff811d9fc0-ffffffff811d9ffa: mark_reg_known_zero (STB_LOCAL)
ffffffff811e549a-ffffffff811e54e4: mark_reg_known_zero.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
void mark_reg_known_zero(struct bpf_verifier_env *env, struct bpf_reg_state *regs, u32 regno);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/bpf/verifier.c (ffffffff811e6700)
Location: kernel/bpf/verifier.c:887
Inline: True
Direct callers:
  - kernel/bpf/verifier.c:do_check
  - kernel/bpf/verifier.c:check_helper_call
  - kernel/bpf/verifier.c:check_helper_call
  - kernel/bpf/verifier.c:check_helper_call
  - kernel/bpf/verifier.c:check_helper_call
  - kernel/bpf/verifier.c:check_mem_access
  - kernel/bpf/verifier.c:init_reg_state
  - kernel/bpf/verifier.c:init_reg_state
```
**Symbols:**

```
ffffffff811e6700-ffffffff811e6794: mark_reg_known_zero (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
void mark_reg_known_zero(struct bpf_verifier_env *env, struct bpf_reg_state *regs, u32 regno);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/bpf/verifier.c (ffffffff81206bd0)
Location: kernel/bpf/verifier.c:1031
Inline: True
Direct callers:
  - kernel/bpf/verifier.c:do_check_common
  - kernel/bpf/verifier.c:do_check_common
  - kernel/bpf/verifier.c:check_ld_imm
  - kernel/bpf/verifier.c:check_helper_call
  - kernel/bpf/verifier.c:check_helper_call
  - kernel/bpf/verifier.c:check_helper_call
  - kernel/bpf/verifier.c:check_helper_call
  - kernel/bpf/verifier.c:check_helper_call
  - kernel/bpf/verifier.c:check_mem_access
  - kernel/bpf/verifier.c:check_ptr_to_btf_access
  - kernel/bpf/verifier.c:init_reg_state
```
**Symbols:**

```
ffffffff81206bd0-ffffffff81206c3e: mark_reg_known_zero (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
void mark_reg_known_zero(struct bpf_verifier_env *env, struct bpf_reg_state *regs, u32 regno);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/bpf/verifier.c (ffffffff812069a0)
Location: kernel/bpf/verifier.c:1063
Inline: True
Direct callers:
  - kernel/bpf/verifier.c:do_check_common
  - kernel/bpf/verifier.c:do_check_common
  - kernel/bpf/verifier.c:check_ld_imm
  - kernel/bpf/verifier.c:check_ld_imm
  - kernel/bpf/verifier.c:check_helper_call
  - kernel/bpf/verifier.c:check_helper_call
  - kernel/bpf/verifier.c:check_helper_call
  - kernel/bpf/verifier.c:check_helper_call
  - kernel/bpf/verifier.c:check_helper_call
  - kernel/bpf/verifier.c:check_helper_call
  - kernel/bpf/verifier.c:check_helper_call
  - kernel/bpf/verifier.c:check_mem_access
  - kernel/bpf/verifier.c:check_ptr_to_map_access
  - kernel/bpf/verifier.c:check_ptr_to_btf_access
  - kernel/bpf/verifier.c:init_reg_state
```
**Symbols:**

```
ffffffff812069a0-ffffffff81206a0e: mark_reg_known_zero (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
void mark_reg_known_zero(struct bpf_verifier_env *env, struct bpf_reg_state *regs, u32 regno);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/bpf/verifier.c (ffffffff81208850)
Location: kernel/bpf/verifier.c:1112
Inline: True
Direct callers:
  - kernel/bpf/verifier.c:do_check_common
  - kernel/bpf/verifier.c:do_check_common
  - kernel/bpf/verifier.c:do_check_common
  - kernel/bpf/verifier.c:check_ld_imm
  - kernel/bpf/verifier.c:check_ld_imm
  - kernel/bpf/verifier.c:check_mem_access
  - kernel/bpf/verifier.c:check_ptr_to_map_access
  - kernel/bpf/verifier.c:check_ptr_to_btf_access
  - kernel/bpf/verifier.c:init_reg_state
```
**Symbols:**

```
ffffffff81208850-ffffffff812088be: mark_reg_known_zero (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
void mark_reg_known_zero(struct bpf_verifier_env *env, struct bpf_reg_state *regs, u32 regno);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/bpf/verifier.c (ffffffff8124c786)
Location: kernel/bpf/verifier.c:1121
Inline: True
Inline callers:
  - kernel/bpf/verifier.c:do_check_common
  - kernel/bpf/verifier.c:check_kfunc_call
  - kernel/bpf/verifier.c:check_helper_call
  - kernel/bpf/verifier.c:check_helper_call
  - kernel/bpf/verifier.c:check_helper_call
  - kernel/bpf/verifier.c:check_helper_call
  - kernel/bpf/verifier.c:check_helper_call
  - kernel/bpf/verifier.c:check_helper_call
  - kernel/bpf/verifier.c:check_helper_call
  - kernel/bpf/verifier.c:init_reg_state
Direct callers:
  - kernel/bpf/verifier.c:do_check_common
  - kernel/bpf/verifier.c:do_check_common
  - kernel/bpf/verifier.c:check_ld_imm
  - kernel/bpf/verifier.c:check_mem_access
  - kernel/bpf/verifier.c:check_ptr_to_map_access
  - kernel/bpf/verifier.c:check_ptr_to_btf_access
```
**Symbols:**

```
ffffffff8123c320-ffffffff8123c38e: mark_reg_known_zero (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
void mark_reg_known_zero(struct bpf_verifier_env *env, struct bpf_reg_state *regs, u32 regno);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/bpf/verifier.c (ffffffff812938fb)
Location: kernel/bpf/verifier.c:1348
Inline: True
Inline callers:
  - kernel/bpf/verifier.c:do_check_common
  - kernel/bpf/verifier.c:check_kfunc_call
  - kernel/bpf/verifier.c:check_helper_call
  - kernel/bpf/verifier.c:check_helper_call
  - kernel/bpf/verifier.c:check_helper_call
  - kernel/bpf/verifier.c:check_helper_call
  - kernel/bpf/verifier.c:check_helper_call
  - kernel/bpf/verifier.c:check_helper_call
  - kernel/bpf/verifier.c:check_helper_call
  - kernel/bpf/verifier.c:init_reg_state
Direct callers:
  - kernel/bpf/verifier.c:do_check_common
  - kernel/bpf/verifier.c:do_check_common
  - kernel/bpf/verifier.c:check_ld_imm
  - kernel/bpf/verifier.c:check_mem_access
  - kernel/bpf/verifier.c:check_mem_access
  - kernel/bpf/verifier.c:check_ptr_to_map_access
  - kernel/bpf/verifier.c:check_ptr_to_btf_access
```
**Symbols:**

```
ffffffff81282010-ffffffff81282085: mark_reg_known_zero (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
void mark_reg_known_zero(struct bpf_verifier_env *env, struct bpf_reg_state *regs, u32 regno);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/bpf/verifier.c (ffffffff812ee38c)
Location: kernel/bpf/verifier.c:1549
Inline: True
Inline callers:
  - kernel/bpf/verifier.c:do_check_common
  - kernel/bpf/verifier.c:check_kfunc_call
  - kernel/bpf/verifier.c:check_kfunc_call
  - kernel/bpf/verifier.c:check_helper_call
  - kernel/bpf/verifier.c:check_helper_call
  - kernel/bpf/verifier.c:check_helper_call
  - kernel/bpf/verifier.c:check_helper_call
  - kernel/bpf/verifier.c:check_helper_call
  - kernel/bpf/verifier.c:check_helper_call
  - kernel/bpf/verifier.c:check_helper_call
  - kernel/bpf/verifier.c:check_ptr_to_map_access
  - kernel/bpf/verifier.c:init_reg_state
Direct callers:
  - kernel/bpf/verifier.c:do_check_common
  - kernel/bpf/verifier.c:do_check_common
  - kernel/bpf/verifier.c:check_ld_imm
  - kernel/bpf/verifier.c:check_kfunc_call
  - kernel/bpf/verifier.c:check_kfunc_call
  - kernel/bpf/verifier.c:check_kfunc_call
  - kernel/bpf/verifier.c:check_kfunc_call
  - kernel/bpf/verifier.c:check_mem_access
  - kernel/bpf/verifier.c:check_mem_access
  - kernel/bpf/verifier.c:check_ptr_to_map_access
  - kernel/bpf/verifier.c:check_ptr_to_btf_access
```
**Symbols:**

```
ffffffff812d7490-ffffffff812d7505: mark_reg_known_zero (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
void mark_reg_known_zero(struct bpf_verifier_env *env, struct bpf_reg_state *regs, u32 regno);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/bpf/verifier.c (ffffffff8131ac5c)
Location: kernel/bpf/verifier.c:1928
Inline: True
Inline callers:
  - kernel/bpf/verifier.c:do_check_common
  - kernel/bpf/verifier.c:check_kfunc_call
  - kernel/bpf/verifier.c:check_kfunc_call
  - kernel/bpf/verifier.c:check_helper_call
  - kernel/bpf/verifier.c:check_helper_call
  - kernel/bpf/verifier.c:check_helper_call
  - kernel/bpf/verifier.c:check_helper_call
  - kernel/bpf/verifier.c:check_helper_call
  - kernel/bpf/verifier.c:check_helper_call
  - kernel/bpf/verifier.c:check_helper_call
  - kernel/bpf/verifier.c:check_ptr_to_map_access
  - kernel/bpf/verifier.c:init_reg_state
Direct callers:
  - kernel/bpf/verifier.c:do_check_common
  - kernel/bpf/verifier.c:do_check_common
  - kernel/bpf/verifier.c:check_ld_imm
  - kernel/bpf/verifier.c:check_kfunc_call
  - kernel/bpf/verifier.c:check_kfunc_call
  - kernel/bpf/verifier.c:check_kfunc_call
  - kernel/bpf/verifier.c:check_kfunc_call
  - kernel/bpf/verifier.c:check_kfunc_call
  - kernel/bpf/verifier.c:check_mem_access
  - kernel/bpf/verifier.c:check_ptr_to_map_access
  - kernel/bpf/verifier.c:check_ptr_to_btf_access
```
**Symbols:**

```
ffffffff812fc680-ffffffff812fc6f5: mark_reg_known_zero (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
void mark_reg_known_zero(struct bpf_verifier_env *env, struct bpf_reg_state *regs, u32 regno);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/bpf/verifier.c (ffffffff8133c805)
Location: kernel/bpf/verifier.c:1782
Inline: True
Inline callers:
  - kernel/bpf/verifier.c:do_check_common
  - kernel/bpf/verifier.c:check_kfunc_call
  - kernel/bpf/verifier.c:check_kfunc_call
  - kernel/bpf/verifier.c:check_ptr_to_map_access
  - kernel/bpf/verifier.c:init_reg_state
Direct callers:
  - kernel/bpf/verifier.c:do_check_common
  - kernel/bpf/verifier.c:do_check_common
  - kernel/bpf/verifier.c:check_ld_imm
  - kernel/bpf/verifier.c:check_kfunc_call
  - kernel/bpf/verifier.c:check_kfunc_call
  - kernel/bpf/verifier.c:check_kfunc_call
  - kernel/bpf/verifier.c:check_kfunc_call
  - kernel/bpf/verifier.c:check_kfunc_call
  - kernel/bpf/verifier.c:check_mem_access
  - kernel/bpf/verifier.c:check_ptr_to_map_access
  - kernel/bpf/verifier.c:check_ptr_to_btf_access
```
**Symbols:**

```
ffffffff8131aa60-ffffffff8131aad5: mark_reg_known_zero (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Selective Inline ⚠️</summary>

```c
void mark_reg_known_zero(struct bpf_verifier_env *env, struct bpf_reg_state *regs, u32 regno);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/bpf/verifier.c (ffff800010269ec8)
Location: kernel/bpf/verifier.c:887
Inline: True
Direct callers:
  - kernel/bpf/verifier.c:do_check
  - kernel/bpf/verifier.c:check_helper_call
  - kernel/bpf/verifier.c:check_helper_call
  - kernel/bpf/verifier.c:check_helper_call
  - kernel/bpf/verifier.c:check_helper_call
  - kernel/bpf/verifier.c:check_mem_access
  - kernel/bpf/verifier.c:init_reg_state
  - kernel/bpf/verifier.c:init_reg_state
```
**Symbols:**

```
ffff800010269ec8-ffff800010269f70: mark_reg_known_zero (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
void mark_reg_known_zero(struct bpf_verifier_env *env, struct bpf_reg_state *regs, u32 regno);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/bpf/verifier.c (c049bf20)
Location: kernel/bpf/verifier.c:887
Inline: True
Direct callers:
  - kernel/bpf/verifier.c:do_check
  - kernel/bpf/verifier.c:check_helper_call
  - kernel/bpf/verifier.c:check_helper_call
  - kernel/bpf/verifier.c:check_helper_call
  - kernel/bpf/verifier.c:check_helper_call
  - kernel/bpf/verifier.c:check_mem_access
  - kernel/bpf/verifier.c:init_reg_state
  - kernel/bpf/verifier.c:init_reg_state
```
**Symbols:**

```
c049bf20-c049bfb0: mark_reg_known_zero (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
void mark_reg_known_zero(struct bpf_verifier_env *env, struct bpf_reg_state *regs, u32 regno);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/bpf/verifier.c (c00000000030fa20)
Location: kernel/bpf/verifier.c:887
Inline: True
Direct callers:
  - kernel/bpf/verifier.c:do_check
  - kernel/bpf/verifier.c:check_helper_call
  - kernel/bpf/verifier.c:check_helper_call
  - kernel/bpf/verifier.c:check_helper_call
  - kernel/bpf/verifier.c:check_helper_call
  - kernel/bpf/verifier.c:check_mem_access
  - kernel/bpf/verifier.c:init_reg_state
  - kernel/bpf/verifier.c:init_reg_state
```
**Symbols:**

```
c00000000030fa20-c00000000030fae4: mark_reg_known_zero (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
void mark_reg_known_zero(struct bpf_verifier_env *env, struct bpf_reg_state *regs, u32 regno);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/bpf/verifier.c (ffffffe0001a4790)
Location: kernel/bpf/verifier.c:887
Inline: True
Direct callers:
  - kernel/bpf/verifier.c:do_check
  - kernel/bpf/verifier.c:check_helper_call
  - kernel/bpf/verifier.c:check_helper_call
  - kernel/bpf/verifier.c:check_helper_call
  - kernel/bpf/verifier.c:check_helper_call
  - kernel/bpf/verifier.c:check_mem_access
  - kernel/bpf/verifier.c:init_reg_state
  - kernel/bpf/verifier.c:init_reg_state
```
**Symbols:**

```
ffffffe0001a4790-ffffffe0001a4830: mark_reg_known_zero (STB_LOCAL)
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
void mark_reg_known_zero(struct bpf_verifier_env *env, struct bpf_reg_state *regs, u32 regno);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/bpf/verifier.c (ffffffff811ded20)
Location: kernel/bpf/verifier.c:887
Inline: True
Direct callers:
  - kernel/bpf/verifier.c:do_check
  - kernel/bpf/verifier.c:check_helper_call
  - kernel/bpf/verifier.c:check_helper_call
  - kernel/bpf/verifier.c:check_helper_call
  - kernel/bpf/verifier.c:check_helper_call
  - kernel/bpf/verifier.c:check_mem_access
  - kernel/bpf/verifier.c:init_reg_state
  - kernel/bpf/verifier.c:init_reg_state
```
**Symbols:**

```
ffffffff811ded20-ffffffff811dedb4: mark_reg_known_zero (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
void mark_reg_known_zero(struct bpf_verifier_env *env, struct bpf_reg_state *regs, u32 regno);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/bpf/verifier.c (ffffffff811d1ae0)
Location: kernel/bpf/verifier.c:887
Inline: True
Direct callers:
  - kernel/bpf/verifier.c:do_check
  - kernel/bpf/verifier.c:check_helper_call
  - kernel/bpf/verifier.c:check_helper_call
  - kernel/bpf/verifier.c:check_helper_call
  - kernel/bpf/verifier.c:check_helper_call
  - kernel/bpf/verifier.c:check_mem_access
  - kernel/bpf/verifier.c:init_reg_state
  - kernel/bpf/verifier.c:init_reg_state
```
**Symbols:**

```
ffffffff811d1ae0-ffffffff811d1b74: mark_reg_known_zero (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
void mark_reg_known_zero(struct bpf_verifier_env *env, struct bpf_reg_state *regs, u32 regno);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/bpf/verifier.c (ffffffff811dcaf0)
Location: kernel/bpf/verifier.c:887
Inline: True
Direct callers:
  - kernel/bpf/verifier.c:do_check
  - kernel/bpf/verifier.c:check_helper_call
  - kernel/bpf/verifier.c:check_helper_call
  - kernel/bpf/verifier.c:check_helper_call
  - kernel/bpf/verifier.c:check_helper_call
  - kernel/bpf/verifier.c:check_mem_access
  - kernel/bpf/verifier.c:init_reg_state
  - kernel/bpf/verifier.c:init_reg_state
```
**Symbols:**

```
ffffffff811dcaf0-ffffffff811dcb84: mark_reg_known_zero (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
void mark_reg_known_zero(struct bpf_verifier_env *env, struct bpf_reg_state *regs, u32 regno);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/bpf/verifier.c (ffffffff811eaf00)
Location: kernel/bpf/verifier.c:887
Inline: True
Direct callers:
  - kernel/bpf/verifier.c:do_check
  - kernel/bpf/verifier.c:check_helper_call
  - kernel/bpf/verifier.c:check_helper_call
  - kernel/bpf/verifier.c:check_helper_call
  - kernel/bpf/verifier.c:check_helper_call
  - kernel/bpf/verifier.c:check_mem_access
  - kernel/bpf/verifier.c:init_reg_state
  - kernel/bpf/verifier.c:init_reg_state
```
**Symbols:**

```
ffffffff811eaf00-ffffffff811eaf94: mark_reg_known_zero (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>4.15</code> and <code>4.18</code> ✅
</li>
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
