# Function: <code>visit_func_call_insn</code>

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
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
int visit_func_call_insn(int t, int insn_cnt, struct bpf_insn *insns, struct bpf_verifier_env *env, bool visit_callee);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/bpf/verifier.c (ffffffff812115d0)
Location: kernel/bpf/verifier.c:9310
Inline: True
Direct callers:
  - kernel/bpf/verifier.c:visit_insn
  - kernel/bpf/verifier.c:visit_insn
```
**Symbols:**

```
ffffffff812115d0-ffffffff8121168d: visit_func_call_insn (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
int visit_func_call_insn(int t, int insn_cnt, struct bpf_insn *insns, struct bpf_verifier_env *env, bool visit_callee);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/bpf/verifier.c (ffffffff812467a0)
Location: kernel/bpf/verifier.c:9625
Inline: True
Direct callers:
  - kernel/bpf/verifier.c:visit_insn
  - kernel/bpf/verifier.c:visit_insn
```
**Symbols:**

```
ffffffff812467a0-ffffffff81246870: visit_func_call_insn (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
int visit_func_call_insn(int t, int insn_cnt, struct bpf_insn *insns, struct bpf_verifier_env *env, bool visit_callee);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/bpf/verifier.c (ffffffff8128c860)
Location: kernel/bpf/verifier.c:10607
Inline: True
Direct callers:
  - kernel/bpf/verifier.c:visit_insn
  - kernel/bpf/verifier.c:visit_insn
```
**Symbols:**

```
ffffffff8128c860-ffffffff8128c94e: visit_func_call_insn (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int visit_func_call_insn(int t, struct bpf_insn *insns, struct bpf_verifier_env *env, bool visit_callee);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/verifier.c (ffffffff812e5620)
Location: kernel/bpf/verifier.c:12585
Inline: False
Direct callers:
  - kernel/bpf/verifier.c:visit_insn
  - kernel/bpf/verifier.c:visit_insn
```
**Symbols:**

```
ffffffff812e5620-ffffffff812e5700: visit_func_call_insn (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int visit_func_call_insn(int t, struct bpf_insn *insns, struct bpf_verifier_env *env, bool visit_callee);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/verifier.c (ffffffff812fc3d0)
Location: kernel/bpf/verifier.c:14545
Inline: False
Direct callers:
  - kernel/bpf/verifier.c:visit_insn
  - kernel/bpf/verifier.c:visit_insn
```
**Symbols:**

```
ffffffff812fc3d0-ffffffff812fc4b0: visit_func_call_insn (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int visit_func_call_insn(int t, struct bpf_insn *insns, struct bpf_verifier_env *env, bool visit_callee);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/verifier.c (ffffffff81318650)
Location: kernel/bpf/verifier.c:15487
Inline: False
Direct callers:
  - kernel/bpf/verifier.c:visit_insn
  - kernel/bpf/verifier.c:visit_insn
```
**Symbols:**

```
ffffffff81318650-ffffffff8131873c: visit_func_call_insn (STB_LOCAL)
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
<details>
<summary>Changed between <code>5.19</code> and <code>6.2</code> ⚠️</summary>
<ul>
<li>
<b>Param removed. </b>
<code>int insn_cnt</code>
</li>
<li>
<b>Param reordered. </b>
<code>t, insn_cnt, insns, env, visit_callee</code> ➡️ <code>t, insns, env, visit_callee</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>6.2</code> and <code>6.5</code> ✅
</li>
<li>
No changes between <code>6.5</code> and <code>6.8</code> ✅
</li>
</ul>
