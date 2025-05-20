# Function: <code>check_stack_write</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/bpf/verifier.c (ffffffff811740a5)
Location: kernel/bpf/verifier.c:561
Inline: True
Inline callers:
  - kernel/bpf/verifier.c:check_mem_access
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/bpf/verifier.c (ffffffff811825ed)
Location: kernel/bpf/verifier.c:567
Inline: True
Inline callers:
  - kernel/bpf/verifier.c:check_mem_access
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/bpf/verifier.c (ffffffff8118f0ec)
Location: kernel/bpf/verifier.c:550
Inline: True
Inline callers:
  - kernel/bpf/verifier.c:check_mem_access
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/bpf/verifier.c (ffffffff811951ff)
Location: kernel/bpf/verifier.c:571
Inline: True
Inline callers:
  - kernel/bpf/verifier.c:check_mem_access
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/bpf/verifier.c (ffffffff811a5e3a)
Location: kernel/bpf/verifier.c:692
Inline: True
Inline callers:
  - kernel/bpf/verifier.c:check_mem_access
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/bpf/verifier.c (ffffffff811ba1e2)
Location: kernel/bpf/verifier.c:1012
Inline: True
Inline callers:
  - kernel/bpf/verifier.c:check_mem_access
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/bpf/verifier.c (ffffffff811c9c54)
Location: kernel/bpf/verifier.c:1219
Inline: True
Inline callers:
  - kernel/bpf/verifier.c:check_mem_access
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/bpf/verifier.c (ffffffff811e1420)
Location: kernel/bpf/verifier.c:1884
Inline: True
Inline callers:
  - kernel/bpf/verifier.c:check_mem_access
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/bpf/verifier.c (ffffffff811edc20)
Location: kernel/bpf/verifier.c:1885
Inline: True
Inline callers:
  - kernel/bpf/verifier.c:check_mem_access
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int check_stack_write(struct bpf_verifier_env *env, struct bpf_func_state *state, int off, int size, int value_regno, int insn_idx);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/verifier.c (ffffffff8120f6f0)
Location: kernel/bpf/verifier.c:2204
Inline: False
Direct callers:
  - kernel/bpf/verifier.c:check_mem_access
```
**Symbols:**

```
ffffffff8120f6f0-ffffffff8120fac9: check_stack_write (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int check_stack_write(struct bpf_verifier_env *env, struct bpf_func_state *state, int off, int size, int value_regno, int insn_idx);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/verifier.c (ffffffff81210680)
Location: kernel/bpf/verifier.c:2277
Inline: False
Direct callers:
  - kernel/bpf/verifier.c:check_mem_access
```
**Symbols:**

```
ffffffff81210680-ffffffff81210ad0: check_stack_write (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/bpf/verifier.c (ffffffff812133df)
Location: kernel/bpf/verifier.c:3049
Inline: True
Inline callers:
  - kernel/bpf/verifier.c:check_mem_access
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/bpf/verifier.c (ffffffff81248c69)
Location: kernel/bpf/verifier.c:3115
Inline: True
Inline callers:
  - kernel/bpf/verifier.c:check_mem_access
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/bpf/verifier.c (ffffffff8128ee8b)
Location: kernel/bpf/verifier.c:3478
Inline: True
Inline callers:
  - kernel/bpf/verifier.c:check_mem_access
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/bpf/verifier.c (ffffffff812e7694)
Location: kernel/bpf/verifier.c:3920
Inline: True
Inline callers:
  - kernel/bpf/verifier.c:check_mem_access
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/bpf/verifier.c (ffffffff81312a2a)
Location: kernel/bpf/verifier.c:4805
Inline: True
Inline callers:
  - kernel/bpf/verifier.c:check_mem_access
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/bpf/verifier.c (ffffffff81332915)
Location: kernel/bpf/verifier.c:4963
Inline: True
Inline callers:
  - kernel/bpf/verifier.c:check_mem_access
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
int check_stack_write(struct bpf_verifier_env *env, struct bpf_func_state *state, int off, int size, int value_regno, int insn_idx);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/verifier.c (ffff800010270d98)
Location: kernel/bpf/verifier.c:1885
Inline: False
Direct callers:
  - kernel/bpf/verifier.c:check_mem_access
```
**Symbols:**

```
ffff800010270d98-ffff800010271248: check_stack_write (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int check_stack_write(struct bpf_verifier_env *env, struct bpf_func_state *state, int off, int size, int value_regno, int insn_idx);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/verifier.c (c04a3058)
Location: kernel/bpf/verifier.c:1885
Inline: False
Direct callers:
  - kernel/bpf/verifier.c:check_mem_access
```
**Symbols:**

```
c04a3058-c04a3514: check_stack_write (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int check_stack_write(struct bpf_verifier_env *env, struct bpf_func_state *state, int off, int size, int value_regno, int insn_idx);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/verifier.c (c000000000317fd0)
Location: kernel/bpf/verifier.c:1885
Inline: False
Direct callers:
  - kernel/bpf/verifier.c:check_mem_access
```
**Symbols:**

```
c000000000317fd0-c0000000003185f0: check_stack_write (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int check_stack_write(struct bpf_verifier_env *env, struct bpf_func_state *state, int off, int size, int value_regno, int insn_idx);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/verifier.c (ffffffe0001aa2c2)
Location: kernel/bpf/verifier.c:1885
Inline: False
Direct callers:
  - kernel/bpf/verifier.c:check_mem_access
```
**Symbols:**

```
ffffffe0001aa2c2-ffffffe0001aa68a: check_stack_write (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/bpf/verifier.c (ffffffff811e6240)
Location: kernel/bpf/verifier.c:1885
Inline: True
Inline callers:
  - kernel/bpf/verifier.c:check_mem_access
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/bpf/verifier.c (ffffffff811d9000)
Location: kernel/bpf/verifier.c:1885
Inline: True
Inline callers:
  - kernel/bpf/verifier.c:check_mem_access
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/bpf/verifier.c (ffffffff811e4010)
Location: kernel/bpf/verifier.c:1885
Inline: True
Inline callers:
  - kernel/bpf/verifier.c:check_mem_access
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/bpf/verifier.c (ffffffff811f23e0)
Location: kernel/bpf/verifier.c:1885
Inline: True
Inline callers:
  - kernel/bpf/verifier.c:check_mem_access
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
</ul>
<b>Arch</b>
<ul>
</ul>
