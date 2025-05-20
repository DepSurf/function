# Function: <code>realloc_stack_state</code>

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
int realloc_stack_state(struct bpf_func_state *state, int size, bool copy_old);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/verifier.c (ffffffff811c6ae0)
Location: kernel/bpf/verifier.c:573
Inline: False
Direct callers:
  - kernel/bpf/verifier.c:check_mem_access
  - kernel/bpf/verifier.c:copy_verifier_state
```
**Symbols:**

```
ffffffff811c6ae0-ffffffff811c6c1d: realloc_stack_state (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int realloc_stack_state(struct bpf_func_state *state, int size, bool copy_old);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/verifier.c (ffffffff811d8cc0)
Location: kernel/bpf/verifier.c:596
Inline: False
Direct callers:
  - kernel/bpf/verifier.c:check_mem_access
  - kernel/bpf/verifier.c:copy_verifier_state
```
**Symbols:**

```
ffffffff811d8cc0-ffffffff811d8e1d: realloc_stack_state (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int realloc_stack_state(struct bpf_func_state *state, int size, bool copy_old);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/verifier.c (ffffffff811e53b0)
Location: kernel/bpf/verifier.c:596
Inline: False
Direct callers:
  - kernel/bpf/verifier.c:check_mem_access
  - kernel/bpf/verifier.c:copy_verifier_state
```
**Symbols:**

```
ffffffff811e53b0-ffffffff811e550d: realloc_stack_state (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int realloc_stack_state(struct bpf_func_state *state, int size, bool copy_old);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/verifier.c (ffffffff812049a0)
Location: kernel/bpf/verifier.c:723
Inline: False
Direct callers:
  - kernel/bpf/verifier.c:check_stack_write
  - kernel/bpf/verifier.c:copy_verifier_state
```
**Symbols:**

```
ffffffff812049a0-ffffffff81204ade: realloc_stack_state (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int realloc_stack_state(struct bpf_func_state *state, int size, bool copy_old);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/verifier.c (ffffffff81204960)
Location: kernel/bpf/verifier.c:749
Inline: False
Direct callers:
  - kernel/bpf/verifier.c:check_stack_write
  - kernel/bpf/verifier.c:copy_verifier_state
```
**Symbols:**

```
ffffffff81204960-ffffffff81204a9b: realloc_stack_state (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int realloc_stack_state(struct bpf_func_state *state, int size, bool copy_old);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/verifier.c (ffffffff81204870)
Location: kernel/bpf/verifier.c:798
Inline: False
Direct callers:
  - kernel/bpf/verifier.c:check_stack_write_var_off
  - kernel/bpf/verifier.c:check_stack_write_fixed_off
  - kernel/bpf/verifier.c:copy_verifier_state
```
**Symbols:**

```
ffffffff81204870-ffffffff812049ab: realloc_stack_state (STB_LOCAL)
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
<summary>In <code>arm64</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/bpf/verifier.c (ffff800010270e20)
Location: kernel/bpf/verifier.c:596
Inline: True
Inline callers:
  - kernel/bpf/verifier.c:check_stack_write
  - kernel/bpf/verifier.c:copy_verifier_state
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/bpf/verifier.c (c04a30c8)
Location: kernel/bpf/verifier.c:596
Inline: True
Inline callers:
  - kernel/bpf/verifier.c:check_stack_write
  - kernel/bpf/verifier.c:copy_verifier_state
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/bpf/verifier.c (c0000000003180b4)
Location: kernel/bpf/verifier.c:596
Inline: True
Inline callers:
  - kernel/bpf/verifier.c:check_stack_write
  - kernel/bpf/verifier.c:copy_verifier_state
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/bpf/verifier.c (ffffffe0001aa34c)
Location: kernel/bpf/verifier.c:596
Inline: True
Inline callers:
  - kernel/bpf/verifier.c:check_stack_write
  - kernel/bpf/verifier.c:copy_verifier_state
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
int realloc_stack_state(struct bpf_func_state *state, int size, bool copy_old);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/verifier.c (ffffffff811dd9d0)
Location: kernel/bpf/verifier.c:596
Inline: False
Direct callers:
  - kernel/bpf/verifier.c:check_mem_access
  - kernel/bpf/verifier.c:copy_verifier_state
```
**Symbols:**

```
ffffffff811dd9d0-ffffffff811ddb2d: realloc_stack_state (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int realloc_stack_state(struct bpf_func_state *state, int size, bool copy_old);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/verifier.c (ffffffff811d0790)
Location: kernel/bpf/verifier.c:596
Inline: False
Direct callers:
  - kernel/bpf/verifier.c:check_mem_access
  - kernel/bpf/verifier.c:copy_verifier_state
```
**Symbols:**

```
ffffffff811d0790-ffffffff811d08ed: realloc_stack_state (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int realloc_stack_state(struct bpf_func_state *state, int size, bool copy_old);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/verifier.c (ffffffff811db7a0)
Location: kernel/bpf/verifier.c:596
Inline: False
Direct callers:
  - kernel/bpf/verifier.c:check_mem_access
  - kernel/bpf/verifier.c:copy_verifier_state
```
**Symbols:**

```
ffffffff811db7a0-ffffffff811db8fd: realloc_stack_state (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int realloc_stack_state(struct bpf_func_state *state, int size, bool copy_old);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/verifier.c (ffffffff811e9bb0)
Location: kernel/bpf/verifier.c:596
Inline: False
Direct callers:
  - kernel/bpf/verifier.c:check_mem_access
  - kernel/bpf/verifier.c:copy_verifier_state
```
**Symbols:**

```
ffffffff811e9bb0-ffffffff811e9d0d: realloc_stack_state (STB_LOCAL)
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
