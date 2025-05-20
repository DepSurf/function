# Function: <code>acquire_reference_state</code>

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
<summary>In <code>5.0</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/bpf/verifier.c (ffffffff811caf9f)
Location: kernel/bpf/verifier.c:597
Inline: True
Inline callers:
  - kernel/bpf/verifier.c:check_helper_call
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
In kernel/bpf/verifier.c (ffffffff811e262b)
Location: kernel/bpf/verifier.c:620
Inline: True
Inline callers:
  - kernel/bpf/verifier.c:check_helper_call
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
In kernel/bpf/verifier.c (ffffffff811eee67)
Location: kernel/bpf/verifier.c:620
Inline: True
Inline callers:
  - kernel/bpf/verifier.c:check_helper_call
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/bpf/verifier.c (ffffffff81211d6c)
Location: kernel/bpf/verifier.c:747
Inline: True
Inline callers:
  - kernel/bpf/verifier.c:check_helper_call
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/bpf/verifier.c (ffffffff8121294e)
Location: kernel/bpf/verifier.c:773
Inline: True
Inline callers:
  - kernel/bpf/verifier.c:check_helper_call
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
In kernel/bpf/verifier.c (ffffffff81214db6)
Location: kernel/bpf/verifier.c:822
Inline: True
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
In kernel/bpf/verifier.c (ffffffff8124b11d)
Location: kernel/bpf/verifier.c:850
Inline: True
Inline callers:
  - kernel/bpf/verifier.c:check_helper_call
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int acquire_reference_state(struct bpf_verifier_env *env, int insn_idx);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/verifier.c (ffffffff81278dc0)
Location: kernel/bpf/verifier.c:1077
Inline: False
Direct callers:
  - kernel/bpf/verifier.c:check_kfunc_call
  - kernel/bpf/verifier.c:check_helper_call
  - kernel/bpf/verifier.c:check_helper_call
```
**Symbols:**

```
ffffffff81278dc0-ffffffff81278e79: acquire_reference_state (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
int acquire_reference_state(struct bpf_verifier_env *env, int insn_idx);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/bpf/verifier.c (0)
Location: kernel/bpf/verifier.c:1275
Inline: False
Direct callers:
  - kernel/bpf/verifier.c:check_kfunc_call
  - kernel/bpf/verifier.c:check_helper_call
  - kernel/bpf/verifier.c:mark_stack_slots_dynptr
```
**Symbols:**

```
ffffffff812cfaf0-ffffffff812cfbf4: acquire_reference_state (STB_LOCAL)
ffffffff8205fa86-ffffffff8205faa1: acquire_reference_state.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
int acquire_reference_state(struct bpf_verifier_env *env, int insn_idx);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/bpf/verifier.c (0)
Location: kernel/bpf/verifier.c:1652
Inline: False
Direct callers:
  - kernel/bpf/verifier.c:check_kfunc_call
  - kernel/bpf/verifier.c:check_helper_call
  - kernel/bpf/verifier.c:process_iter_arg
  - kernel/bpf/verifier.c:mark_stack_slots_dynptr
```
**Symbols:**

```
ffffffff812f9a90-ffffffff812f9b91: acquire_reference_state (STB_LOCAL)
ffffffff820dec33-ffffffff820dec4e: acquire_reference_state.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
int acquire_reference_state(struct bpf_verifier_env *env, int insn_idx);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/bpf/verifier.c (0)
Location: kernel/bpf/verifier.c:1305
Inline: False
Direct callers:
  - kernel/bpf/verifier.c:check_kfunc_call
  - kernel/bpf/verifier.c:process_iter_arg
  - kernel/bpf/verifier.c:mark_stack_slots_dynptr
```
**Symbols:**

```
ffffffff81318970-ffffffff81318a71: acquire_reference_state (STB_LOCAL)
ffffffff821bab61-ffffffff821bab7c: acquire_reference_state.cold (STB_LOCAL)
```
</details>
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
In kernel/bpf/verifier.c (ffff800010272720)
Location: kernel/bpf/verifier.c:620
Inline: True
Inline callers:
  - kernel/bpf/verifier.c:check_helper_call
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
In kernel/bpf/verifier.c (c04a4f40)
Location: kernel/bpf/verifier.c:620
Inline: True
Inline callers:
  - kernel/bpf/verifier.c:check_helper_call
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
In kernel/bpf/verifier.c (c00000000031a13c)
Location: kernel/bpf/verifier.c:620
Inline: True
Inline callers:
  - kernel/bpf/verifier.c:check_helper_call
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
In kernel/bpf/verifier.c (ffffffe0001ab756)
Location: kernel/bpf/verifier.c:620
Inline: True
Inline callers:
  - kernel/bpf/verifier.c:check_helper_call
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
In kernel/bpf/verifier.c (ffffffff811e7487)
Location: kernel/bpf/verifier.c:620
Inline: True
Inline callers:
  - kernel/bpf/verifier.c:check_helper_call
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
In kernel/bpf/verifier.c (ffffffff811da247)
Location: kernel/bpf/verifier.c:620
Inline: True
Inline callers:
  - kernel/bpf/verifier.c:check_helper_call
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
In kernel/bpf/verifier.c (ffffffff811e5257)
Location: kernel/bpf/verifier.c:620
Inline: True
Inline callers:
  - kernel/bpf/verifier.c:check_helper_call
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
In kernel/bpf/verifier.c (ffffffff811f3627)
Location: kernel/bpf/verifier.c:620
Inline: True
Inline callers:
  - kernel/bpf/verifier.c:check_helper_call
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
