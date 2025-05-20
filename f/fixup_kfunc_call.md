# Function: <code>fixup_kfunc_call</code>

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
<summary>In <code>5.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/bpf/verifier.c (ffffffff8120f055)
Location: kernel/bpf/verifier.c:12287
Inline: True
Inline callers:
  - kernel/bpf/verifier.c:do_misc_fixups
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
In kernel/bpf/verifier.c (ffffffff812438c2)
Location: kernel/bpf/verifier.c:12674
Inline: True
Inline callers:
  - kernel/bpf/verifier.c:do_misc_fixups
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
In kernel/bpf/verifier.c (ffffffff8128901e)
Location: kernel/bpf/verifier.c:13737
Inline: True
Inline callers:
  - kernel/bpf/verifier.c:do_misc_fixups
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
In kernel/bpf/verifier.c (ffffffff812df7ee)
Location: kernel/bpf/verifier.c:15722
Inline: True
Inline callers:
  - kernel/bpf/verifier.c:do_misc_fixups
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int fixup_kfunc_call(struct bpf_verifier_env *env, struct bpf_insn *insn, struct bpf_insn *insn_buf, int insn_idx, int *cnt);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/verifier.c (ffffffff81301750)
Location: kernel/bpf/verifier.c:17988
Inline: False
Direct callers:
  - kernel/bpf/verifier.c:do_misc_fixups
```
**Symbols:**

```
ffffffff81301750-ffffffff81301a11: fixup_kfunc_call (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int fixup_kfunc_call(struct bpf_verifier_env *env, struct bpf_insn *insn, struct bpf_insn *insn_buf, int insn_idx, int *cnt);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/verifier.c (ffffffff813216a0)
Location: kernel/bpf/verifier.c:19163
Inline: False
Direct callers:
  - kernel/bpf/verifier.c:do_misc_fixups
```
**Symbols:**

```
ffffffff813216a0-ffffffff81321a51: fixup_kfunc_call (STB_LOCAL)
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
No changes between <code>6.5</code> and <code>6.8</code> ✅
</li>
</ul>
