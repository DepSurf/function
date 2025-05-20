# Function: <code>mark_reg_read</code>

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
<summary>In <code>4.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/bpf/verifier.c (ffffffff811a36c0)
Location: kernel/bpf/verifier.c:623
Inline: True
Inline callers:
  - kernel/bpf/verifier.c:check_reg_arg
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int mark_reg_read(struct bpf_verifier_env *env, const struct bpf_verifier_state *state, struct bpf_verifier_state *parent, u32 regno);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/verifier.c (ffffffff811b7f40)
Location: kernel/bpf/verifier.c:927
Inline: False
Direct callers:
  - kernel/bpf/verifier.c:do_check
  - kernel/bpf/verifier.c:check_reg_arg
```
**Symbols:**

```
ffffffff811b7f40-ffffffff811b807f: mark_reg_read (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int mark_reg_read(struct bpf_verifier_env *env, const struct bpf_reg_state *state, struct bpf_reg_state *parent);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/verifier.c (ffffffff811c72d0)
Location: kernel/bpf/verifier.c:1130
Inline: False
Direct callers:
  - kernel/bpf/verifier.c:do_check
  - kernel/bpf/verifier.c:do_check
  - kernel/bpf/verifier.c:check_helper_mem_access
  - kernel/bpf/verifier.c:check_mem_access
  - kernel/bpf/verifier.c:check_mem_access
  - kernel/bpf/verifier.c:check_reg_arg
```
**Symbols:**

```
ffffffff811c72d0-ffffffff811c7331: mark_reg_read (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int mark_reg_read(struct bpf_verifier_env *env, const struct bpf_reg_state *state, struct bpf_reg_state *parent, u8 flag);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/verifier.c (ffffffff811da0a0)
Location: kernel/bpf/verifier.c:1195
Inline: False
Direct callers:
  - kernel/bpf/verifier.c:propagate_liveness_reg
  - kernel/bpf/verifier.c:check_helper_mem_access
  - kernel/bpf/verifier.c:check_mem_access
  - kernel/bpf/verifier.c:check_mem_access
  - kernel/bpf/verifier.c:check_mem_access
  - kernel/bpf/verifier.c:check_reg_arg
```
**Symbols:**

```
ffffffff811da0a0-ffffffff811da147: mark_reg_read (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int mark_reg_read(struct bpf_verifier_env *env, const struct bpf_reg_state *state, struct bpf_reg_state *parent, u8 flag);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/verifier.c (ffffffff811e6840)
Location: kernel/bpf/verifier.c:1196
Inline: False
Direct callers:
  - kernel/bpf/verifier.c:propagate_liveness_reg
  - kernel/bpf/verifier.c:check_helper_mem_access
  - kernel/bpf/verifier.c:check_mem_access
  - kernel/bpf/verifier.c:check_mem_access
  - kernel/bpf/verifier.c:check_mem_access
  - kernel/bpf/verifier.c:check_reg_arg
```
**Symbols:**

```
ffffffff811e6840-ffffffff811e68e7: mark_reg_read (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int mark_reg_read(struct bpf_verifier_env *env, const struct bpf_reg_state *state, struct bpf_reg_state *parent, u8 flag);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/verifier.c (ffffffff81206cd0)
Location: kernel/bpf/verifier.c:1505
Inline: False
Direct callers:
  - kernel/bpf/verifier.c:propagate_liveness
  - kernel/bpf/verifier.c:propagate_liveness
  - kernel/bpf/verifier.c:check_stack_boundary
  - kernel/bpf/verifier.c:check_stack_read
  - kernel/bpf/verifier.c:check_stack_read
  - kernel/bpf/verifier.c:check_reg_arg
```
**Symbols:**

```
ffffffff81206cd0-ffffffff81206d78: mark_reg_read (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int mark_reg_read(struct bpf_verifier_env *env, const struct bpf_reg_state *state, struct bpf_reg_state *parent, u8 flag);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/verifier.c (ffffffff81206aa0)
Location: kernel/bpf/verifier.c:1557
Inline: False
Direct callers:
  - kernel/bpf/verifier.c:propagate_liveness
  - kernel/bpf/verifier.c:propagate_liveness
  - kernel/bpf/verifier.c:check_stack_boundary
  - kernel/bpf/verifier.c:check_stack_read
  - kernel/bpf/verifier.c:check_stack_read
  - kernel/bpf/verifier.c:check_reg_arg
```
**Symbols:**

```
ffffffff81206aa0-ffffffff81206b48: mark_reg_read (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int mark_reg_read(struct bpf_verifier_env *env, const struct bpf_reg_state *state, struct bpf_reg_state *parent, u8 flag);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/verifier.c (ffffffff81206ab0)
Location: kernel/bpf/verifier.c:1828
Inline: False
Direct callers:
  - kernel/bpf/verifier.c:propagate_liveness
  - kernel/bpf/verifier.c:propagate_liveness
  - kernel/bpf/verifier.c:check_stack_range_initialized
  - kernel/bpf/verifier.c:check_stack_read_fixed_off
  - kernel/bpf/verifier.c:check_stack_read_fixed_off
  - kernel/bpf/verifier.c:check_reg_arg
```
**Symbols:**

```
ffffffff81206ab0-ffffffff81206b5d: mark_reg_read (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int mark_reg_read(struct bpf_verifier_env *env, const struct bpf_reg_state *state, struct bpf_reg_state *parent, u8 flag);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/verifier.c (ffffffff81239d60)
Location: kernel/bpf/verifier.c:1896
Inline: False
Direct callers:
  - kernel/bpf/verifier.c:propagate_liveness
  - kernel/bpf/verifier.c:propagate_liveness
  - kernel/bpf/verifier.c:check_stack_range_initialized
  - kernel/bpf/verifier.c:check_stack_read_fixed_off
  - kernel/bpf/verifier.c:check_stack_read_fixed_off
  - kernel/bpf/verifier.c:check_reg_arg
```
**Symbols:**

```
ffffffff81239d60-ffffffff81239e4c: mark_reg_read (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int mark_reg_read(struct bpf_verifier_env *env, const struct bpf_reg_state *state, struct bpf_reg_state *parent, u8 flag);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/verifier.c (ffffffff8127de60)
Location: kernel/bpf/verifier.c:2239
Inline: False
Direct callers:
  - kernel/bpf/verifier.c:propagate_liveness
  - kernel/bpf/verifier.c:propagate_liveness
  - kernel/bpf/verifier.c:check_stack_range_initialized
  - kernel/bpf/verifier.c:check_stack_read_fixed_off
  - kernel/bpf/verifier.c:check_stack_read_fixed_off
  - kernel/bpf/verifier.c:check_stack_read_fixed_off
  - kernel/bpf/verifier.c:check_reg_arg
```
**Symbols:**

```
ffffffff8127de60-ffffffff8127df51: mark_reg_read (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int mark_reg_read(struct bpf_verifier_env *env, const struct bpf_reg_state *state, struct bpf_reg_state *parent, u8 flag);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/verifier.c (ffffffff812d6560)
Location: kernel/bpf/verifier.c:2454
Inline: False
Direct callers:
  - kernel/bpf/verifier.c:propagate_liveness
  - kernel/bpf/verifier.c:propagate_liveness
  - kernel/bpf/verifier.c:process_dynptr_func
  - kernel/bpf/verifier.c:process_dynptr_func
  - kernel/bpf/verifier.c:check_stack_range_initialized
  - kernel/bpf/verifier.c:check_stack_read_fixed_off
  - kernel/bpf/verifier.c:check_stack_read_fixed_off
  - kernel/bpf/verifier.c:check_stack_read_fixed_off
  - kernel/bpf/verifier.c:check_reg_arg
```
**Symbols:**

```
ffffffff812d6560-ffffffff812d6651: mark_reg_read (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int mark_reg_read(struct bpf_verifier_env *env, const struct bpf_reg_state *state, struct bpf_reg_state *parent, u8 flag);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/verifier.c (ffffffff812f71d0)
Location: kernel/bpf/verifier.c:2885
Inline: False
Direct callers:
  - kernel/bpf/verifier.c:propagate_liveness
  - kernel/bpf/verifier.c:propagate_liveness
  - kernel/bpf/verifier.c:process_iter_arg
  - kernel/bpf/verifier.c:process_dynptr_func
  - kernel/bpf/verifier.c:process_dynptr_func
  - kernel/bpf/verifier.c:check_stack_range_initialized
  - kernel/bpf/verifier.c:check_stack_read_fixed_off
  - kernel/bpf/verifier.c:check_stack_read_fixed_off
  - kernel/bpf/verifier.c:check_stack_read_fixed_off
  - kernel/bpf/verifier.c:check_reg_arg
```
**Symbols:**

```
ffffffff812f71d0-ffffffff812f72c1: mark_reg_read (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int mark_reg_read(struct bpf_verifier_env *env, const struct bpf_reg_state *state, struct bpf_reg_state *parent, u8 flag);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/verifier.c (ffffffff813166f0)
Location: kernel/bpf/verifier.c:2983
Inline: False
Direct callers:
  - kernel/bpf/verifier.c:propagate_liveness
  - kernel/bpf/verifier.c:propagate_liveness
  - kernel/bpf/verifier.c:prepare_func_exit
  - kernel/bpf/verifier.c:process_iter_arg
  - kernel/bpf/verifier.c:process_dynptr_func
  - kernel/bpf/verifier.c:process_dynptr_func
  - kernel/bpf/verifier.c:check_stack_range_initialized
  - kernel/bpf/verifier.c:check_stack_read_fixed_off
  - kernel/bpf/verifier.c:check_stack_read_fixed_off
  - kernel/bpf/verifier.c:check_stack_read_fixed_off
  - kernel/bpf/verifier.c:check_stack_read_fixed_off
  - kernel/bpf/verifier.c:__check_reg_arg
```
**Symbols:**

```
ffffffff813166f0-ffffffff813167e1: mark_reg_read (STB_LOCAL)
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
int mark_reg_read(struct bpf_verifier_env *env, const struct bpf_reg_state *state, struct bpf_reg_state *parent, u8 flag);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/verifier.c (ffff80001026a008)
Location: kernel/bpf/verifier.c:1196
Inline: False
Direct callers:
  - kernel/bpf/verifier.c:propagate_liveness_reg
  - kernel/bpf/verifier.c:check_helper_mem_access
  - kernel/bpf/verifier.c:check_mem_access
  - kernel/bpf/verifier.c:check_mem_access
  - kernel/bpf/verifier.c:check_mem_access
  - kernel/bpf/verifier.c:check_reg_arg
```
**Symbols:**

```
ffff80001026a008-ffff80001026a104: mark_reg_read (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int mark_reg_read(struct bpf_verifier_env *env, const struct bpf_reg_state *state, struct bpf_reg_state *parent, u8 flag);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/verifier.c (c049c040)
Location: kernel/bpf/verifier.c:1196
Inline: False
Direct callers:
  - kernel/bpf/verifier.c:propagate_liveness_reg
  - kernel/bpf/verifier.c:check_helper_mem_access
  - kernel/bpf/verifier.c:check_mem_access
  - kernel/bpf/verifier.c:check_mem_access
  - kernel/bpf/verifier.c:check_mem_access
  - kernel/bpf/verifier.c:check_reg_arg
```
**Symbols:**

```
c049c040-c049c128: mark_reg_read (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int mark_reg_read(struct bpf_verifier_env *env, const struct bpf_reg_state *state, struct bpf_reg_state *parent, u8 flag);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/verifier.c (c00000000030fbd0)
Location: kernel/bpf/verifier.c:1196
Inline: False
Direct callers:
  - kernel/bpf/verifier.c:propagate_liveness_reg
  - kernel/bpf/verifier.c:check_helper_mem_access
  - kernel/bpf/verifier.c:check_mem_access
  - kernel/bpf/verifier.c:check_mem_access
  - kernel/bpf/verifier.c:check_mem_access
  - kernel/bpf/verifier.c:check_reg_arg
  - kernel/bpf/verifier.c:check_reg_arg
```
**Symbols:**

```
c00000000030fbd0-c00000000030fce0: mark_reg_read (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int mark_reg_read(struct bpf_verifier_env *env, const struct bpf_reg_state *state, struct bpf_reg_state *parent, u8 flag);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/verifier.c (ffffffe0001a48be)
Location: kernel/bpf/verifier.c:1196
Inline: False
Direct callers:
  - kernel/bpf/verifier.c:propagate_liveness_reg
  - kernel/bpf/verifier.c:check_helper_mem_access
  - kernel/bpf/verifier.c:check_mem_access
  - kernel/bpf/verifier.c:check_mem_access
  - kernel/bpf/verifier.c:check_mem_access
  - kernel/bpf/verifier.c:check_mem_access
  - kernel/bpf/verifier.c:check_reg_arg
```
**Symbols:**

```
ffffffe0001a48be-ffffffe0001a4990: mark_reg_read (STB_LOCAL)
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
int mark_reg_read(struct bpf_verifier_env *env, const struct bpf_reg_state *state, struct bpf_reg_state *parent, u8 flag);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/verifier.c (ffffffff811dee60)
Location: kernel/bpf/verifier.c:1196
Inline: False
Direct callers:
  - kernel/bpf/verifier.c:propagate_liveness_reg
  - kernel/bpf/verifier.c:check_helper_mem_access
  - kernel/bpf/verifier.c:check_mem_access
  - kernel/bpf/verifier.c:check_mem_access
  - kernel/bpf/verifier.c:check_mem_access
  - kernel/bpf/verifier.c:check_reg_arg
```
**Symbols:**

```
ffffffff811dee60-ffffffff811def07: mark_reg_read (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int mark_reg_read(struct bpf_verifier_env *env, const struct bpf_reg_state *state, struct bpf_reg_state *parent, u8 flag);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/verifier.c (ffffffff811d1c20)
Location: kernel/bpf/verifier.c:1196
Inline: False
Direct callers:
  - kernel/bpf/verifier.c:propagate_liveness_reg
  - kernel/bpf/verifier.c:check_helper_mem_access
  - kernel/bpf/verifier.c:check_mem_access
  - kernel/bpf/verifier.c:check_mem_access
  - kernel/bpf/verifier.c:check_mem_access
  - kernel/bpf/verifier.c:check_reg_arg
```
**Symbols:**

```
ffffffff811d1c20-ffffffff811d1cc7: mark_reg_read (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int mark_reg_read(struct bpf_verifier_env *env, const struct bpf_reg_state *state, struct bpf_reg_state *parent, u8 flag);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/verifier.c (ffffffff811dcc30)
Location: kernel/bpf/verifier.c:1196
Inline: False
Direct callers:
  - kernel/bpf/verifier.c:propagate_liveness_reg
  - kernel/bpf/verifier.c:check_helper_mem_access
  - kernel/bpf/verifier.c:check_mem_access
  - kernel/bpf/verifier.c:check_mem_access
  - kernel/bpf/verifier.c:check_mem_access
  - kernel/bpf/verifier.c:check_reg_arg
```
**Symbols:**

```
ffffffff811dcc30-ffffffff811dccd7: mark_reg_read (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int mark_reg_read(struct bpf_verifier_env *env, const struct bpf_reg_state *state, struct bpf_reg_state *parent, u8 flag);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/verifier.c (ffffffff811eb040)
Location: kernel/bpf/verifier.c:1196
Inline: False
Direct callers:
  - kernel/bpf/verifier.c:propagate_liveness_reg
  - kernel/bpf/verifier.c:check_helper_mem_access
  - kernel/bpf/verifier.c:check_mem_access
  - kernel/bpf/verifier.c:check_mem_access
  - kernel/bpf/verifier.c:check_mem_access
  - kernel/bpf/verifier.c:check_reg_arg
```
**Symbols:**

```
ffffffff811eb040-ffffffff811eb0e7: mark_reg_read (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
<details>
<summary>Changed between <code>4.18</code> and <code>5.0</code> ⚠️</summary>
<ul>
<li>
<b>Param removed. </b>
<code>u32 regno</code>
</li>
<li>
<b>Param type changed. </b>
<code>const struct bpf_verifier_state *state</code> ➡️ <code>const struct bpf_reg_state *state</code>
</li>
<li>
<b>Param type changed. </b>
<code>struct bpf_verifier_state *parent</code> ➡️ <code>struct bpf_reg_state *parent</code>
</li>
</ul>
</details>
</li>
<li>
<details>
<summary>Changed between <code>5.0</code> and <code>5.3</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>u8 flag</code>
</li>
</ul>
</details>
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
