# Function: <code>realloc_reference_state</code>

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
<summary>In <code>5.0</code>: ✅</summary>

```c
int realloc_reference_state(struct bpf_func_state *state, int size, bool copy_old);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/verifier.c (ffffffff811c6990)
Location: kernel/bpf/verifier.c:571
Inline: False
Direct callers:
  - kernel/bpf/verifier.c:check_helper_call
  - kernel/bpf/verifier.c:check_mem_access
  - kernel/bpf/verifier.c:copy_verifier_state
```
**Symbols:**

```
ffffffff811c6990-ffffffff811c6a92: realloc_reference_state (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int realloc_reference_state(struct bpf_func_state *state, int size, bool copy_old);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/verifier.c (ffffffff811d8b80)
Location: kernel/bpf/verifier.c:594
Inline: False
Direct callers:
  - kernel/bpf/verifier.c:check_helper_call
  - kernel/bpf/verifier.c:check_mem_access
  - kernel/bpf/verifier.c:copy_verifier_state
```
**Symbols:**

```
ffffffff811d8b80-ffffffff811d8c7b: realloc_reference_state (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int realloc_reference_state(struct bpf_func_state *state, int size, bool copy_old);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/verifier.c (ffffffff811e5270)
Location: kernel/bpf/verifier.c:594
Inline: False
Direct callers:
  - kernel/bpf/verifier.c:check_helper_call
  - kernel/bpf/verifier.c:check_mem_access
  - kernel/bpf/verifier.c:copy_verifier_state
```
**Symbols:**

```
ffffffff811e5270-ffffffff811e536b: realloc_reference_state (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int realloc_reference_state(struct bpf_func_state *state, int size, bool copy_old);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/verifier.c (ffffffff812048a0)
Location: kernel/bpf/verifier.c:721
Inline: False
Direct callers:
  - kernel/bpf/verifier.c:check_helper_call
  - kernel/bpf/verifier.c:prepare_func_exit
  - kernel/bpf/verifier.c:check_func_call
  - kernel/bpf/verifier.c:check_stack_write
  - kernel/bpf/verifier.c:copy_verifier_state
```
**Symbols:**

```
ffffffff812048a0-ffffffff8120499b: realloc_reference_state (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int realloc_reference_state(struct bpf_func_state *state, int size, bool copy_old);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/verifier.c (ffffffff81204860)
Location: kernel/bpf/verifier.c:747
Inline: False
Direct callers:
  - kernel/bpf/verifier.c:check_helper_call
  - kernel/bpf/verifier.c:prepare_func_exit
  - kernel/bpf/verifier.c:check_func_call
  - kernel/bpf/verifier.c:check_stack_write
  - kernel/bpf/verifier.c:copy_verifier_state
```
**Symbols:**

```
ffffffff81204860-ffffffff81204958: realloc_reference_state (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int realloc_reference_state(struct bpf_func_state *state, int size, bool copy_old);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/verifier.c (ffffffff81204770)
Location: kernel/bpf/verifier.c:796
Inline: False
Direct callers:
  - kernel/bpf/verifier.c:prepare_func_exit
  - kernel/bpf/verifier.c:check_stack_write_var_off
  - kernel/bpf/verifier.c:check_stack_write_fixed_off
  - kernel/bpf/verifier.c:copy_verifier_state
```
**Symbols:**

```
ffffffff81204770-ffffffff81204868: realloc_reference_state (STB_LOCAL)
```
</details>
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
<summary>In <code>arm64</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/bpf/verifier.c (ffff800010268508)
Location: kernel/bpf/verifier.c:594
Inline: True
Direct callers:
  - kernel/bpf/verifier.c:check_helper_call
  - kernel/bpf/verifier.c:check_stack_write
  - kernel/bpf/verifier.c:copy_verifier_state
```
**Symbols:**

```
ffff800010268508-ffff800010268618: realloc_reference_state.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int realloc_reference_state(struct bpf_func_state *state, int size, bool copy_old);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/verifier.c (c049a998)
Location: kernel/bpf/verifier.c:594
Inline: False
Direct callers:
  - kernel/bpf/verifier.c:check_helper_call
  - kernel/bpf/verifier.c:check_stack_write
  - kernel/bpf/verifier.c:copy_verifier_state
```
**Symbols:**

```
c049a998-c049aa7c: realloc_reference_state (STB_LOCAL)
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
In kernel/bpf/verifier.c (c00000000030e0b0)
Location: kernel/bpf/verifier.c:594
Inline: True
Direct callers:
  - kernel/bpf/verifier.c:check_helper_call
  - kernel/bpf/verifier.c:check_stack_write
  - kernel/bpf/verifier.c:copy_verifier_state
```
**Symbols:**

```
c00000000030e0b0-c00000000030e258: realloc_reference_state.isra.0 (STB_LOCAL)
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
In kernel/bpf/verifier.c (ffffffe0001a3742)
Location: kernel/bpf/verifier.c:594
Inline: True
Direct callers:
  - kernel/bpf/verifier.c:check_helper_call
  - kernel/bpf/verifier.c:check_stack_write
  - kernel/bpf/verifier.c:copy_verifier_state
```
**Symbols:**

```
ffffffe0001a3742-ffffffe0001a382a: realloc_reference_state.isra.0 (STB_LOCAL)
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
int realloc_reference_state(struct bpf_func_state *state, int size, bool copy_old);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/verifier.c (ffffffff811dd890)
Location: kernel/bpf/verifier.c:594
Inline: False
Direct callers:
  - kernel/bpf/verifier.c:check_helper_call
  - kernel/bpf/verifier.c:check_mem_access
  - kernel/bpf/verifier.c:copy_verifier_state
```
**Symbols:**

```
ffffffff811dd890-ffffffff811dd98b: realloc_reference_state (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int realloc_reference_state(struct bpf_func_state *state, int size, bool copy_old);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/verifier.c (ffffffff811d0650)
Location: kernel/bpf/verifier.c:594
Inline: False
Direct callers:
  - kernel/bpf/verifier.c:check_helper_call
  - kernel/bpf/verifier.c:check_mem_access
  - kernel/bpf/verifier.c:copy_verifier_state
```
**Symbols:**

```
ffffffff811d0650-ffffffff811d074b: realloc_reference_state (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int realloc_reference_state(struct bpf_func_state *state, int size, bool copy_old);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/verifier.c (ffffffff811db660)
Location: kernel/bpf/verifier.c:594
Inline: False
Direct callers:
  - kernel/bpf/verifier.c:check_helper_call
  - kernel/bpf/verifier.c:check_mem_access
  - kernel/bpf/verifier.c:copy_verifier_state
```
**Symbols:**

```
ffffffff811db660-ffffffff811db75b: realloc_reference_state (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int realloc_reference_state(struct bpf_func_state *state, int size, bool copy_old);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/verifier.c (ffffffff811e9a70)
Location: kernel/bpf/verifier.c:594
Inline: False
Direct callers:
  - kernel/bpf/verifier.c:check_helper_call
  - kernel/bpf/verifier.c:check_mem_access
  - kernel/bpf/verifier.c:copy_verifier_state
```
**Symbols:**

```
ffffffff811e9a70-ffffffff811e9b6b: realloc_reference_state (STB_LOCAL)
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
<li>
No changes between <code>5.11</code> and <code>5.13</code> ✅
</li>
</ul>
<b>Arch</b>
<ul>
<li>
No changes between <code>amd64</code> and <code>armhf</code> ✅
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
