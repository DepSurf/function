# Function: <code>check_kfunc_call</code>

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
<summary>In <code>5.13</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/bpf/verifier.c (ffffffff81210960)
Location: kernel/bpf/verifier.c:6237
Inline: True
Direct callers:
  - kernel/bpf/verifier.c:do_check
```
**Symbols:**

```
ffffffff81210960-ffffffff81210be4: check_kfunc_call.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int check_kfunc_call(struct bpf_verifier_env *env, struct bpf_insn *insn);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/verifier.c (ffffffff81245b00)
Location: kernel/bpf/verifier.c:6526
Inline: False
Direct callers:
  - kernel/bpf/verifier.c:do_check
```
**Symbols:**

```
ffffffff81245b00-ffffffff81245e04: check_kfunc_call (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int check_kfunc_call(struct bpf_verifier_env *env, struct bpf_insn *insn, int *insn_idx_p);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/verifier.c (ffffffff8128b9c0)
Location: kernel/bpf/verifier.c:7480
Inline: False
Direct callers:
  - kernel/bpf/verifier.c:do_check
```
**Symbols:**

```
ffffffff8128b9c0-ffffffff8128be57: check_kfunc_call (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
int check_kfunc_call(struct bpf_verifier_env *env, struct bpf_insn *insn, int *insn_idx_p);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/bpf/verifier.c (0)
Location: kernel/bpf/verifier.c:9276
Inline: False
Direct callers:
  - kernel/bpf/verifier.c:do_check
```
**Symbols:**

```
ffffffff812ea530-ffffffff812eb088: check_kfunc_call (STB_LOCAL)
ffffffff82060fd9-ffffffff820610da: check_kfunc_call.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
int check_kfunc_call(struct bpf_verifier_env *env, struct bpf_insn *insn, int *insn_idx_p);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/bpf/verifier.c (0)
Location: kernel/bpf/verifier.c:11110
Inline: False
Direct callers:
  - kernel/bpf/verifier.c:do_check
```
**Symbols:**

```
ffffffff81316620-ffffffff813178e9: check_kfunc_call (STB_LOCAL)
ffffffff820e0452-ffffffff820e053b: check_kfunc_call.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
int check_kfunc_call(struct bpf_verifier_env *env, struct bpf_insn *insn, int *insn_idx_p);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/bpf/verifier.c (0)
Location: kernel/bpf/verifier.c:11972
Inline: False
Direct callers:
  - kernel/bpf/verifier.c:do_check
```
**Symbols:**

```
ffffffff81338810-ffffffff813399d1: check_kfunc_call (STB_LOCAL)
ffffffff821bc92e-ffffffff821bcb52: check_kfunc_call.cold (STB_LOCAL)
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
<details>
<summary>Changed between <code>5.15</code> and <code>5.19</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>int *insn_idx_p</code>
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
