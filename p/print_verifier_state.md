# Function: <code>print_verifier_state</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void print_verifier_state(struct verifier_env *env);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/verifier.c (ffffffff81173ae0)
Location: kernel/bpf/verifier.c:251
Inline: False
Direct callers:
  - kernel/bpf/verifier.c:do_check
  - kernel/bpf/verifier.c:do_check
```
**Symbols:**

```
ffffffff81173ae0-ffffffff81173be9: print_verifier_state (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void print_verifier_state(struct verifier_state *state);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/verifier.c (ffffffff81181d20)
Location: kernel/bpf/verifier.c:250
Inline: False
Direct callers:
  - kernel/bpf/verifier.c:do_check
  - kernel/bpf/verifier.c:do_check
```
**Symbols:**

```
ffffffff81181d20-ffffffff81181e82: print_verifier_state (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void print_verifier_state(struct bpf_verifier_state *state);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/verifier.c (ffffffff8118e170)
Location: kernel/bpf/verifier.c:210
Inline: False
Direct callers:
  - kernel/bpf/verifier.c:do_check
  - kernel/bpf/verifier.c:do_check
  - kernel/bpf/verifier.c:check_mem_access
```
**Symbols:**

```
ffffffff8118e170-ffffffff8118e325: print_verifier_state (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void print_verifier_state(struct bpf_verifier_state *state);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/verifier.c (ffffffff81193d30)
Location: kernel/bpf/verifier.c:212
Inline: False
Direct callers:
  - kernel/bpf/verifier.c:do_check
  - kernel/bpf/verifier.c:do_check
  - kernel/bpf/verifier.c:check_map_access_adj
```
**Symbols:**

```
ffffffff81193d30-ffffffff81193f3c: print_verifier_state (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void print_verifier_state(struct bpf_verifier_env *env, struct bpf_verifier_state *state);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/verifier.c (ffffffff811a1900)
Location: kernel/bpf/verifier.c:219
Inline: False
Direct callers:
  - kernel/bpf/verifier.c:do_check
  - kernel/bpf/verifier.c:check_cond_jmp_op
  - kernel/bpf/verifier.c:adjust_reg_min_max_vals
  - kernel/bpf/verifier.c:check_map_access
```
**Symbols:**

```
ffffffff811a1900-ffffffff811a1ba2: print_verifier_state (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void print_verifier_state(struct bpf_verifier_env *env, const struct bpf_func_state *state);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/verifier.c (ffffffff811b80e0)
Location: kernel/bpf/verifier.c:285
Inline: False
Direct callers:
  - kernel/bpf/verifier.c:do_check
  - kernel/bpf/verifier.c:do_check
  - kernel/bpf/verifier.c:do_check
  - kernel/bpf/verifier.c:do_check
  - kernel/bpf/verifier.c:do_check
  - kernel/bpf/verifier.c:check_cond_jmp_op
  - kernel/bpf/verifier.c:adjust_reg_min_max_vals
  - kernel/bpf/verifier.c:check_map_access
```
**Symbols:**

```
ffffffff811b80e0-ffffffff811b8482: print_verifier_state (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void print_verifier_state(struct bpf_verifier_env *env, const struct bpf_func_state *state);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/verifier.c (ffffffff811c73c0)
Location: kernel/bpf/verifier.c:418
Inline: False
Direct callers:
  - kernel/bpf/verifier.c:do_check
  - kernel/bpf/verifier.c:do_check
  - kernel/bpf/verifier.c:do_check
  - kernel/bpf/verifier.c:do_check
  - kernel/bpf/verifier.c:do_check
  - kernel/bpf/verifier.c:check_cond_jmp_op
  - kernel/bpf/verifier.c:adjust_reg_min_max_vals
  - kernel/bpf/verifier.c:check_map_access
```
**Symbols:**

```
ffffffff811c73c0-ffffffff811c7815: print_verifier_state (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void print_verifier_state(struct bpf_verifier_env *env, const struct bpf_func_state *state);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/verifier.c (ffffffff811da5a0)
Location: kernel/bpf/verifier.c:433
Inline: False
Direct callers:
  - kernel/bpf/verifier.c:do_check
  - kernel/bpf/verifier.c:do_check
  - kernel/bpf/verifier.c:do_check
  - kernel/bpf/verifier.c:do_check
  - kernel/bpf/verifier.c:do_check
  - kernel/bpf/verifier.c:check_cond_jmp_op
  - kernel/bpf/verifier.c:adjust_reg_min_max_vals
  - kernel/bpf/verifier.c:check_map_access
  - kernel/bpf/verifier.c:__mark_chain_precision
```
**Symbols:**

```
ffffffff811da5a0-ffffffff811daa45: print_verifier_state (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void print_verifier_state(struct bpf_verifier_env *env, const struct bpf_func_state *state);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/verifier.c (ffffffff811e69d0)
Location: kernel/bpf/verifier.c:433
Inline: False
Direct callers:
  - kernel/bpf/verifier.c:do_check
  - kernel/bpf/verifier.c:do_check
  - kernel/bpf/verifier.c:do_check
  - kernel/bpf/verifier.c:do_check
  - kernel/bpf/verifier.c:do_check
  - kernel/bpf/verifier.c:check_cond_jmp_op
  - kernel/bpf/verifier.c:adjust_reg_min_max_vals
  - kernel/bpf/verifier.c:check_map_access
  - kernel/bpf/verifier.c:__mark_chain_precision
```
**Symbols:**

```
ffffffff811e69d0-ffffffff811e6e75: print_verifier_state (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void print_verifier_state(struct bpf_verifier_env *env, const struct bpf_func_state *state);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/verifier.c (ffffffff8120bbc0)
Location: kernel/bpf/verifier.c:542
Inline: False
Direct callers:
  - kernel/bpf/verifier.c:do_check
  - kernel/bpf/verifier.c:check_cond_jmp_op
  - kernel/bpf/verifier.c:adjust_reg_min_max_vals
  - kernel/bpf/verifier.c:prepare_func_exit
  - kernel/bpf/verifier.c:prepare_func_exit
  - kernel/bpf/verifier.c:check_func_call
  - kernel/bpf/verifier.c:check_func_call
  - kernel/bpf/verifier.c:check_mem_region_access
  - kernel/bpf/verifier.c:__mark_chain_precision
```
**Symbols:**

```
ffffffff8120bbc0-ffffffff8120c145: print_verifier_state (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void print_verifier_state(struct bpf_verifier_env *env, const struct bpf_func_state *state);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/verifier.c (ffffffff81207140)
Location: kernel/bpf/verifier.c:566
Inline: False
Direct callers:
  - kernel/bpf/verifier.c:do_check
  - kernel/bpf/verifier.c:check_cond_jmp_op
  - kernel/bpf/verifier.c:adjust_reg_min_max_vals
  - kernel/bpf/verifier.c:prepare_func_exit
  - kernel/bpf/verifier.c:prepare_func_exit
  - kernel/bpf/verifier.c:check_func_call
  - kernel/bpf/verifier.c:check_func_call
  - kernel/bpf/verifier.c:check_mem_region_access
  - kernel/bpf/verifier.c:__mark_chain_precision
```
**Symbols:**

```
ffffffff81207140-ffffffff81207693: print_verifier_state (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void print_verifier_state(struct bpf_verifier_env *env, const struct bpf_func_state *state);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/verifier.c (ffffffff81206190)
Location: kernel/bpf/verifier.c:614
Inline: False
Direct callers:
  - kernel/bpf/verifier.c:do_check
  - kernel/bpf/verifier.c:check_cond_jmp_op
  - kernel/bpf/verifier.c:adjust_reg_min_max_vals
  - kernel/bpf/verifier.c:prepare_func_exit
  - kernel/bpf/verifier.c:prepare_func_exit
  - kernel/bpf/verifier.c:check_mem_region_access
  - kernel/bpf/verifier.c:__mark_chain_precision
```
**Symbols:**

```
ffffffff81206190-ffffffff812066d6: print_verifier_state (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
void print_verifier_state(struct bpf_verifier_env *env, const struct bpf_func_state *state);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/bpf/verifier.c (0)
Location: kernel/bpf/verifier.c:615
Inline: False
Direct callers:
  - kernel/bpf/verifier.c:do_check
  - kernel/bpf/verifier.c:check_cond_jmp_op
  - kernel/bpf/verifier.c:adjust_reg_min_max_vals
  - kernel/bpf/verifier.c:prepare_func_exit
  - kernel/bpf/verifier.c:prepare_func_exit
  - kernel/bpf/verifier.c:__check_func_call
  - kernel/bpf/verifier.c:__check_func_call
  - kernel/bpf/verifier.c:check_mem_region_access
  - kernel/bpf/verifier.c:__mark_chain_precision
```
**Symbols:**

```
ffffffff812390a0-ffffffff812397b9: print_verifier_state (STB_LOCAL)
ffffffff81cb7d6d-ffffffff81cb7dd6: print_verifier_state.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
void print_verifier_state(struct bpf_verifier_env *env, const struct bpf_func_state *state, bool print_all);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/bpf/verifier.c (0)
Location: kernel/bpf/verifier.c:814
Inline: False
Direct callers:
  - kernel/bpf/verifier.c:do_check
  - kernel/bpf/verifier.c:adjust_reg_min_max_vals
  - kernel/bpf/verifier.c:prepare_func_exit
  - kernel/bpf/verifier.c:prepare_func_exit
  - kernel/bpf/verifier.c:__check_func_call
  - kernel/bpf/verifier.c:__check_func_call
  - kernel/bpf/verifier.c:__mark_chain_precision
  - kernel/bpf/verifier.c:print_insn_state
```
**Symbols:**

```
ffffffff8127f210-ffffffff8127fb12: print_verifier_state (STB_LOCAL)
ffffffff81e690f0-ffffffff81e6916e: print_verifier_state.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
void print_verifier_state(struct bpf_verifier_env *env, const struct bpf_func_state *state, bool print_all);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/bpf/verifier.c (0)
Location: kernel/bpf/verifier.c:1003
Inline: False
Direct callers:
  - kernel/bpf/verifier.c:do_check
  - kernel/bpf/verifier.c:adjust_reg_min_max_vals
  - kernel/bpf/verifier.c:prepare_func_exit
  - kernel/bpf/verifier.c:prepare_func_exit
  - kernel/bpf/verifier.c:__check_func_call
  - kernel/bpf/verifier.c:__check_func_call
  - kernel/bpf/verifier.c:__mark_chain_precision
  - kernel/bpf/verifier.c:print_insn_state
```
**Symbols:**

```
ffffffff812d4860-ffffffff812d50fe: print_verifier_state (STB_LOCAL)
ffffffff8205fcc5-ffffffff8205fd5a: print_verifier_state.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
void print_verifier_state(struct bpf_verifier_env *env, const struct bpf_func_state *state, bool print_all);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/bpf/verifier.c (0)
Location: kernel/bpf/verifier.c:1342
Inline: False
Direct callers:
  - kernel/bpf/verifier.c:do_check
  - kernel/bpf/verifier.c:adjust_reg_min_max_vals
  - kernel/bpf/verifier.c:prepare_func_exit
  - kernel/bpf/verifier.c:prepare_func_exit
  - kernel/bpf/verifier.c:__check_func_call
  - kernel/bpf/verifier.c:__check_func_call
  - kernel/bpf/verifier.c:__mark_chain_precision
  - kernel/bpf/verifier.c:print_insn_state
```
**Symbols:**

```
ffffffff81305a70-ffffffff81306683: print_verifier_state (STB_LOCAL)
ffffffff820df459-ffffffff820df4f0: print_verifier_state.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
void print_verifier_state(struct bpf_verifier_env *env, const struct bpf_func_state *state, bool print_all);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/bpf/log.c (0)
Location: kernel/bpf/log.c:710
Inline: False
Direct callers:
  - kernel/bpf/verifier.c:do_check
  - kernel/bpf/verifier.c:is_state_visited
  - kernel/bpf/verifier.c:is_state_visited
  - kernel/bpf/verifier.c:adjust_reg_min_max_vals
  - kernel/bpf/verifier.c:prepare_func_exit
  - kernel/bpf/verifier.c:prepare_func_exit
  - kernel/bpf/verifier.c:__mark_chain_precision
  - kernel/bpf/log.c:print_insn_state
```
**Symbols:**

```
ffffffff821bd246-ffffffff821bd28c: print_verifier_state.cold (STB_LOCAL)
ffffffff813461f0-ffffffff813468e2: print_verifier_state (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: ✅</summary>

```c
void print_verifier_state(struct bpf_verifier_env *env, const struct bpf_func_state *state);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/verifier.c (ffff80001026a608)
Location: kernel/bpf/verifier.c:433
Inline: False
Direct callers:
  - kernel/bpf/verifier.c:do_check
  - kernel/bpf/verifier.c:do_check
  - kernel/bpf/verifier.c:do_check
  - kernel/bpf/verifier.c:do_check
  - kernel/bpf/verifier.c:do_check
  - kernel/bpf/verifier.c:do_check
  - kernel/bpf/verifier.c:check_cond_jmp_op
  - kernel/bpf/verifier.c:adjust_reg_min_max_vals
  - kernel/bpf/verifier.c:check_map_access
  - kernel/bpf/verifier.c:__mark_chain_precision
```
**Symbols:**

```
ffff80001026a608-ffff80001026aaf0: print_verifier_state (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void print_verifier_state(struct bpf_verifier_env *env, const struct bpf_func_state *state);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/verifier.c (c049c218)
Location: kernel/bpf/verifier.c:433
Inline: False
Direct callers:
  - kernel/bpf/verifier.c:do_check
  - kernel/bpf/verifier.c:do_check
  - kernel/bpf/verifier.c:do_check
  - kernel/bpf/verifier.c:do_check
  - kernel/bpf/verifier.c:do_check
  - kernel/bpf/verifier.c:check_cond_jmp_op
  - kernel/bpf/verifier.c:check_alu_op
  - kernel/bpf/verifier.c:check_map_access
  - kernel/bpf/verifier.c:__mark_chain_precision
```
**Symbols:**

```
c049c218-c049c780: print_verifier_state (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void print_verifier_state(struct bpf_verifier_env *env, const struct bpf_func_state *state);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/verifier.c (c00000000030fe60)
Location: kernel/bpf/verifier.c:433
Inline: False
Direct callers:
  - kernel/bpf/verifier.c:do_check
  - kernel/bpf/verifier.c:do_check
  - kernel/bpf/verifier.c:do_check
  - kernel/bpf/verifier.c:do_check
  - kernel/bpf/verifier.c:do_check
  - kernel/bpf/verifier.c:do_check
  - kernel/bpf/verifier.c:check_cond_jmp_op
  - kernel/bpf/verifier.c:adjust_reg_min_max_vals
  - kernel/bpf/verifier.c:check_map_access
  - kernel/bpf/verifier.c:__mark_chain_precision
```
**Symbols:**

```
c00000000030fe60-c000000000310480: print_verifier_state (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void print_verifier_state(struct bpf_verifier_env *env, const struct bpf_func_state *state);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/verifier.c (ffffffe0001a4ddc)
Location: kernel/bpf/verifier.c:433
Inline: False
Direct callers:
  - kernel/bpf/verifier.c:do_check
  - kernel/bpf/verifier.c:do_check
  - kernel/bpf/verifier.c:do_check
  - kernel/bpf/verifier.c:do_check
  - kernel/bpf/verifier.c:do_check
  - kernel/bpf/verifier.c:check_cond_jmp_op
  - kernel/bpf/verifier.c:adjust_reg_min_max_vals
  - kernel/bpf/verifier.c:check_map_access
  - kernel/bpf/verifier.c:__mark_chain_precision
```
**Symbols:**

```
ffffffe0001a4ddc-ffffffe0001a5274: print_verifier_state (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: ✅</summary>

```c
void print_verifier_state(struct bpf_verifier_env *env, const struct bpf_func_state *state);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/verifier.c (ffffffff811deff0)
Location: kernel/bpf/verifier.c:433
Inline: False
Direct callers:
  - kernel/bpf/verifier.c:do_check
  - kernel/bpf/verifier.c:do_check
  - kernel/bpf/verifier.c:do_check
  - kernel/bpf/verifier.c:do_check
  - kernel/bpf/verifier.c:do_check
  - kernel/bpf/verifier.c:check_cond_jmp_op
  - kernel/bpf/verifier.c:adjust_reg_min_max_vals
  - kernel/bpf/verifier.c:check_map_access
  - kernel/bpf/verifier.c:__mark_chain_precision
```
**Symbols:**

```
ffffffff811deff0-ffffffff811df495: print_verifier_state (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void print_verifier_state(struct bpf_verifier_env *env, const struct bpf_func_state *state);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/verifier.c (ffffffff811d1db0)
Location: kernel/bpf/verifier.c:433
Inline: False
Direct callers:
  - kernel/bpf/verifier.c:do_check
  - kernel/bpf/verifier.c:do_check
  - kernel/bpf/verifier.c:do_check
  - kernel/bpf/verifier.c:do_check
  - kernel/bpf/verifier.c:do_check
  - kernel/bpf/verifier.c:check_cond_jmp_op
  - kernel/bpf/verifier.c:adjust_reg_min_max_vals
  - kernel/bpf/verifier.c:check_map_access
  - kernel/bpf/verifier.c:__mark_chain_precision
```
**Symbols:**

```
ffffffff811d1db0-ffffffff811d2255: print_verifier_state (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void print_verifier_state(struct bpf_verifier_env *env, const struct bpf_func_state *state);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/verifier.c (ffffffff811dcdc0)
Location: kernel/bpf/verifier.c:433
Inline: False
Direct callers:
  - kernel/bpf/verifier.c:do_check
  - kernel/bpf/verifier.c:do_check
  - kernel/bpf/verifier.c:do_check
  - kernel/bpf/verifier.c:do_check
  - kernel/bpf/verifier.c:do_check
  - kernel/bpf/verifier.c:check_cond_jmp_op
  - kernel/bpf/verifier.c:adjust_reg_min_max_vals
  - kernel/bpf/verifier.c:check_map_access
  - kernel/bpf/verifier.c:__mark_chain_precision
```
**Symbols:**

```
ffffffff811dcdc0-ffffffff811dd265: print_verifier_state (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void print_verifier_state(struct bpf_verifier_env *env, const struct bpf_func_state *state);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/verifier.c (ffffffff811eb1d0)
Location: kernel/bpf/verifier.c:433
Inline: False
Direct callers:
  - kernel/bpf/verifier.c:do_check
  - kernel/bpf/verifier.c:do_check
  - kernel/bpf/verifier.c:do_check
  - kernel/bpf/verifier.c:do_check
  - kernel/bpf/verifier.c:do_check
  - kernel/bpf/verifier.c:check_cond_jmp_op
  - kernel/bpf/verifier.c:adjust_reg_min_max_vals
  - kernel/bpf/verifier.c:check_map_access
  - kernel/bpf/verifier.c:__mark_chain_precision
```
**Symbols:**

```
ffffffff811eb1d0-ffffffff811eb675: print_verifier_state (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
<details>
<summary>Changed between <code>4.4</code> and <code>4.8</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>struct verifier_state *state</code>
</li>
<li>
<b>Param removed. </b>
<code>struct verifier_env *env</code>
</li>
</ul>
</details>
</li>
<li>
<details>
<summary>Changed between <code>4.8</code> and <code>4.10</code> ⚠️</summary>
<ul>
<li>
<b>Param type changed. </b>
<code>struct verifier_state *state</code> ➡️ <code>struct bpf_verifier_state *state</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>4.10</code> and <code>4.13</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>4.13</code> and <code>4.15</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>struct bpf_verifier_env *env</code>
</li>
<li>
<b>Param reordered. </b>
<code>state</code> ➡️ <code>env, state</code>
</li>
</ul>
</details>
</li>
<li>
<details>
<summary>Changed between <code>4.15</code> and <code>4.18</code> ⚠️</summary>
<ul>
<li>
<b>Param type changed. </b>
<code>struct bpf_verifier_state *state</code> ➡️ <code>const struct bpf_func_state *state</code>
</li>
</ul>
</details>
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
<details>
<summary>Changed between <code>5.15</code> and <code>5.19</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>bool print_all</code>
</li>
</ul>
</details>
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
