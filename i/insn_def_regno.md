# Function: <code>insn_def_regno</code>

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
int insn_def_regno(const struct bpf_insn *insn);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/bpf/verifier.c (ffffffff81202780)
Location: kernel/bpf/verifier.c:1965
Inline: True
Direct callers:
  - kernel/bpf/verifier.c:adjust_insn_aux_data
  - kernel/bpf/verifier.c:adjust_insn_aux_data
```
**Symbols:**

```
ffffffff81202780-ffffffff812027e3: insn_def_regno (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
int insn_def_regno(const struct bpf_insn *insn);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/bpf/verifier.c (ffffffff812347e0)
Location: kernel/bpf/verifier.c:2033
Inline: True
Direct callers:
  - kernel/bpf/verifier.c:adjust_insn_aux_data
  - kernel/bpf/verifier.c:adjust_insn_aux_data
```
**Symbols:**

```
ffffffff812347e0-ffffffff81234843: insn_def_regno (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
int insn_def_regno(const struct bpf_insn *insn);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/bpf/verifier.c (ffffffff81278000)
Location: kernel/bpf/verifier.c:2376
Inline: True
Direct callers:
  - kernel/bpf/verifier.c:adjust_insn_aux_data
  - kernel/bpf/verifier.c:adjust_insn_aux_data
```
**Symbols:**

```
ffffffff81278000-ffffffff81278083: insn_def_regno (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
int insn_def_regno(const struct bpf_insn *insn);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/bpf/verifier.c (ffffffff812ce5d0)
Location: kernel/bpf/verifier.c:2617
Inline: True
Direct callers:
  - kernel/bpf/verifier.c:adjust_insn_aux_data
  - kernel/bpf/verifier.c:adjust_insn_aux_data
```
**Symbols:**

```
ffffffff812ce5d0-ffffffff812ce653: insn_def_regno (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
int insn_def_regno(const struct bpf_insn *insn);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/bpf/verifier.c (ffffffff812f5b20)
Location: kernel/bpf/verifier.c:3067
Inline: True
Direct callers:
  - kernel/bpf/verifier.c:adjust_insn_aux_data
  - kernel/bpf/verifier.c:adjust_insn_aux_data
```
**Symbols:**

```
ffffffff812f5b20-ffffffff812f5b99: insn_def_regno (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
int insn_def_regno(const struct bpf_insn *insn);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/bpf/verifier.c (ffffffff81314bd0)
Location: kernel/bpf/verifier.c:3167
Inline: True
Direct callers:
  - kernel/bpf/verifier.c:adjust_insn_aux_data
  - kernel/bpf/verifier.c:adjust_insn_aux_data
```
**Symbols:**

```
ffffffff81314bd0-ffffffff81314c49: insn_def_regno (STB_LOCAL)
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
No changes between <code>5.19</code> and <code>6.2</code> ✅
</li>
<li>
No changes between <code>6.2</code> and <code>6.5</code> ✅
</li>
<li>
No changes between <code>6.5</code> and <code>6.8</code> ✅
</li>
</ul>
