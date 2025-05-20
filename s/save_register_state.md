# Function: <code>save_register_state</code>

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
<details>
<summary>In <code>5.3</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/bpf/verifier.c (ffffffff811d7710)
Location: kernel/bpf/verifier.c:1869
Inline: True
Direct callers:
  - kernel/bpf/verifier.c:check_mem_access
```
**Symbols:**

```
ffffffff811d7710-ffffffff811d77c5: save_register_state.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/bpf/verifier.c (ffffffff811e3e00)
Location: kernel/bpf/verifier.c:1870
Inline: True
Direct callers:
  - kernel/bpf/verifier.c:check_mem_access
```
**Symbols:**

```
ffffffff811e3e00-ffffffff811e3eb5: save_register_state.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void save_register_state(struct bpf_func_state *state, int spi, struct bpf_reg_state *reg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/verifier.c (ffffffff81201e20)
Location: kernel/bpf/verifier.c:2189
Inline: False
Direct callers:
  - kernel/bpf/verifier.c:check_stack_write
```
**Symbols:**

```
ffffffff81201e20-ffffffff81201ee8: save_register_state (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void save_register_state(struct bpf_func_state *state, int spi, struct bpf_reg_state *reg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/verifier.c (ffffffff81201890)
Location: kernel/bpf/verifier.c:2262
Inline: False
Direct callers:
  - kernel/bpf/verifier.c:check_stack_write
```
**Symbols:**

```
ffffffff81201890-ffffffff81201958: save_register_state (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void save_register_state(struct bpf_func_state *state, int spi, struct bpf_reg_state *reg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/verifier.c (ffffffff812027f0)
Location: kernel/bpf/verifier.c:2567
Inline: False
Direct callers:
  - kernel/bpf/verifier.c:check_stack_write_fixed_off
```
**Symbols:**

```
ffffffff812027f0-ffffffff812028bb: save_register_state (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void save_register_state(struct bpf_func_state *state, int spi, struct bpf_reg_state *reg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/verifier.c (ffffffff81234850)
Location: kernel/bpf/verifier.c:2635
Inline: False
Direct callers:
  - kernel/bpf/verifier.c:check_stack_write_fixed_off
```
**Symbols:**

```
ffffffff81234850-ffffffff8123491b: save_register_state (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
void save_register_state(struct bpf_func_state *state, int spi, struct bpf_reg_state *reg, int size);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/bpf/verifier.c (ffffffff8128e19f)
Location: kernel/bpf/verifier.c:2971
Inline: True
Inline callers:
  - kernel/bpf/verifier.c:check_stack_write_fixed_off
Direct callers:
  - kernel/bpf/verifier.c:check_stack_write_fixed_off
```
**Symbols:**

```
ffffffff81278090-ffffffff812781a4: save_register_state (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void save_register_state(struct bpf_func_state *state, int spi, struct bpf_reg_state *reg, int size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/verifier.c (ffffffff812ce670)
Location: kernel/bpf/verifier.c:3396
Inline: False
Direct callers:
  - kernel/bpf/verifier.c:check_stack_write_fixed_off
  - kernel/bpf/verifier.c:check_stack_write_fixed_off
```
**Symbols:**

```
ffffffff812ce670-ffffffff812ce789: save_register_state (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void save_register_state(struct bpf_func_state *state, int spi, struct bpf_reg_state *reg, int size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/verifier.c (ffffffff812f5bb0)
Location: kernel/bpf/verifier.c:4259
Inline: False
Direct callers:
  - kernel/bpf/verifier.c:check_stack_write_fixed_off
  - kernel/bpf/verifier.c:check_stack_write_fixed_off
  - kernel/bpf/verifier.c:check_stack_write_fixed_off
```
**Symbols:**

```
ffffffff812f5bb0-ffffffff812f5d16: save_register_state (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
void save_register_state(struct bpf_verifier_env *env, struct bpf_func_state *state, int spi, struct bpf_reg_state *reg, int size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/bpf/verifier.c (0)
Location: kernel/bpf/verifier.c:4417
Inline: False
Direct callers:
  - kernel/bpf/verifier.c:check_stack_write_fixed_off
  - kernel/bpf/verifier.c:check_stack_write_fixed_off
  - kernel/bpf/verifier.c:check_stack_write_fixed_off
```
**Symbols:**

```
ffffffff81317530-ffffffff813176d1: save_register_state (STB_LOCAL)
ffffffff821ba98a-ffffffff821ba9ad: save_register_state.cold (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/bpf/verifier.c (ffff800010266cd0)
Location: kernel/bpf/verifier.c:1870
Inline: True
Direct callers:
  - kernel/bpf/verifier.c:check_stack_write
```
**Symbols:**

```
ffff800010266cd0-ffff800010266d84: save_register_state.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void save_register_state(struct bpf_func_state *state, int spi, struct bpf_reg_state *reg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/verifier.c (c04980bc)
Location: kernel/bpf/verifier.c:1870
Inline: False
Direct callers:
  - kernel/bpf/verifier.c:check_stack_write
```
**Symbols:**

```
c04980bc-c049812c: save_register_state (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/bpf/verifier.c (c00000000030c200)
Location: kernel/bpf/verifier.c:1870
Inline: True
Direct callers:
  - kernel/bpf/verifier.c:check_stack_write
```
**Symbols:**

```
c00000000030c200-c00000000030c2a4: save_register_state.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/bpf/verifier.c (ffffffe0001a221a)
Location: kernel/bpf/verifier.c:1870
Inline: True
Direct callers:
  - kernel/bpf/verifier.c:check_stack_write
```
**Symbols:**

```
ffffffe0001a221a-ffffffe0001a22a6: save_register_state.isra.0 (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/bpf/verifier.c (ffffffff811dc420)
Location: kernel/bpf/verifier.c:1870
Inline: True
Direct callers:
  - kernel/bpf/verifier.c:check_mem_access
```
**Symbols:**

```
ffffffff811dc420-ffffffff811dc4d5: save_register_state.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/bpf/verifier.c (ffffffff811cf1e0)
Location: kernel/bpf/verifier.c:1870
Inline: True
Direct callers:
  - kernel/bpf/verifier.c:check_mem_access
```
**Symbols:**

```
ffffffff811cf1e0-ffffffff811cf295: save_register_state.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/bpf/verifier.c (ffffffff811da1f0)
Location: kernel/bpf/verifier.c:1870
Inline: True
Direct callers:
  - kernel/bpf/verifier.c:check_mem_access
```
**Symbols:**

```
ffffffff811da1f0-ffffffff811da2a5: save_register_state.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/bpf/verifier.c (ffffffff811e8600)
Location: kernel/bpf/verifier.c:1870
Inline: True
Direct callers:
  - kernel/bpf/verifier.c:check_mem_access
```
**Symbols:**

```
ffffffff811e8600-ffffffff811e86b5: save_register_state.isra.0 (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
<code>int size</code>
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
<details>
<summary>Changed between <code>6.5</code> and <code>6.8</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>struct bpf_verifier_env *env</code>
</li>
<li>
<b>Param reordered. </b>
<code>state, spi, reg, size</code> ➡️ <code>env, state, spi, reg, size</code>
</li>
</ul>
</details>
</li>
</ul>
<b>Arch</b>
<ul>
</ul>
