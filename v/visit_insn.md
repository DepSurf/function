# Function: <code>visit_insn</code>

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
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int visit_insn(int t, int insn_cnt, struct bpf_verifier_env *env);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/verifier.c (ffffffff8120fc40)
Location: kernel/bpf/verifier.c:8151
Inline: False
Direct callers:
  - kernel/bpf/verifier.c:check_cfg
```
**Symbols:**

```
ffffffff8120fc40-ffffffff8120fe42: visit_insn (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int visit_insn(int t, int insn_cnt, struct bpf_verifier_env *env);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/verifier.c (ffffffff81211690)
Location: kernel/bpf/verifier.c:9336
Inline: False
Direct callers:
  - kernel/bpf/verifier.c:check_cfg
```
**Symbols:**

```
ffffffff81211690-ffffffff81211848: visit_insn (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int visit_insn(int t, int insn_cnt, struct bpf_verifier_env *env);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/verifier.c (ffffffff81246870)
Location: kernel/bpf/verifier.c:9655
Inline: False
Direct callers:
  - kernel/bpf/verifier.c:check_cfg
```
**Symbols:**

```
ffffffff81246870-ffffffff81246a44: visit_insn (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int visit_insn(int t, int insn_cnt, struct bpf_verifier_env *env);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/verifier.c (ffffffff8128c950)
Location: kernel/bpf/verifier.c:10637
Inline: False
Direct callers:
  - kernel/bpf/verifier.c:check_cfg
```
**Symbols:**

```
ffffffff8128c950-ffffffff8128cb4b: visit_insn (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int visit_insn(int t, struct bpf_verifier_env *env);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/verifier.c (ffffffff812e5710)
Location: kernel/bpf/verifier.c:12616
Inline: False
Direct callers:
  - kernel/bpf/verifier.c:check_cfg
```
**Symbols:**

```
ffffffff812e5710-ffffffff812e5903: visit_insn (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int visit_insn(int t, struct bpf_verifier_env *env);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/verifier.c (ffffffff81304e40)
Location: kernel/bpf/verifier.c:14576
Inline: False
Direct callers:
  - kernel/bpf/verifier.c:check_cfg
```
**Symbols:**

```
ffffffff81304e40-ffffffff813050b1: visit_insn (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int visit_insn(int t, struct bpf_verifier_env *env);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/verifier.c (ffffffff813251d0)
Location: kernel/bpf/verifier.c:15514
Inline: False
Direct callers:
  - kernel/bpf/verifier.c:check_cfg
```
**Symbols:**

```
ffffffff813251d0-ffffffff813254a4: visit_insn (STB_LOCAL)
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
No changes between <code>5.11</code> and <code>5.13</code> ✅
</li>
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
<code>t, insn_cnt, env</code> ➡️ <code>t, env</code>
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
