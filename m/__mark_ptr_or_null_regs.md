# Function: <code>__mark_ptr_or_null_regs</code>

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
<summary>In <code>5.3</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/bpf/verifier.c (ffffffff811d874f)
Location: kernel/bpf/verifier.c:5651
Inline: True
Inline callers:
  - kernel/bpf/verifier.c:mark_ptr_or_null_regs
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
In kernel/bpf/verifier.c (ffffffff811e4e3f)
Location: kernel/bpf/verifier.c:5661
Inline: True
Inline callers:
  - kernel/bpf/verifier.c:mark_ptr_or_null_regs
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void __mark_ptr_or_null_regs(struct bpf_func_state *state, u32 id, bool is_null);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/verifier.c (ffffffff812034e0)
Location: kernel/bpf/verifier.c:6730
Inline: False
Direct callers:
  - kernel/bpf/verifier.c:mark_ptr_or_null_regs
```
**Symbols:**

```
ffffffff812034e0-ffffffff812035c9: __mark_ptr_or_null_regs (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void __mark_ptr_or_null_regs(struct bpf_func_state *state, u32 id, bool is_null);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/verifier.c (ffffffff81203450)
Location: kernel/bpf/verifier.c:7387
Inline: False
Direct callers:
  - kernel/bpf/verifier.c:mark_ptr_or_null_regs
```
**Symbols:**

```
ffffffff81203450-ffffffff81203523: __mark_ptr_or_null_regs (STB_LOCAL)
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
In kernel/bpf/verifier.c (ffffffff81204091)
Location: kernel/bpf/verifier.c:8526
Inline: True
Inline callers:
  - kernel/bpf/verifier.c:mark_ptr_or_null_regs
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
In kernel/bpf/verifier.c (ffffffff8123632c)
Location: kernel/bpf/verifier.c:8819
Inline: True
Inline callers:
  - kernel/bpf/verifier.c:mark_ptr_or_null_regs
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
In kernel/bpf/verifier.c (ffffffff8127a86c)
Location: kernel/bpf/verifier.c:9801
Inline: True
Inline callers:
  - kernel/bpf/verifier.c:mark_ptr_or_null_regs
```
</details>
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
In kernel/bpf/verifier.c (ffff8000102676e4)
Location: kernel/bpf/verifier.c:5661
Inline: True
Inline callers:
  - kernel/bpf/verifier.c:mark_ptr_or_null_regs
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
In kernel/bpf/verifier.c (c049a3f0)
Location: kernel/bpf/verifier.c:5661
Inline: True
Inline callers:
  - kernel/bpf/verifier.c:mark_ptr_or_null_regs
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
In kernel/bpf/verifier.c (c00000000030cec4)
Location: kernel/bpf/verifier.c:5661
Inline: True
Inline callers:
  - kernel/bpf/verifier.c:mark_ptr_or_null_regs
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
In kernel/bpf/verifier.c (ffffffe0001a2bc6)
Location: kernel/bpf/verifier.c:5661
Inline: True
Inline callers:
  - kernel/bpf/verifier.c:mark_ptr_or_null_regs
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
In kernel/bpf/verifier.c (ffffffff811dd45f)
Location: kernel/bpf/verifier.c:5661
Inline: True
Inline callers:
  - kernel/bpf/verifier.c:mark_ptr_or_null_regs
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
In kernel/bpf/verifier.c (ffffffff811d021f)
Location: kernel/bpf/verifier.c:5661
Inline: True
Inline callers:
  - kernel/bpf/verifier.c:mark_ptr_or_null_regs
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
In kernel/bpf/verifier.c (ffffffff811db22f)
Location: kernel/bpf/verifier.c:5661
Inline: True
Inline callers:
  - kernel/bpf/verifier.c:mark_ptr_or_null_regs
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
In kernel/bpf/verifier.c (ffffffff811e963f)
Location: kernel/bpf/verifier.c:5661
Inline: True
Inline callers:
  - kernel/bpf/verifier.c:mark_ptr_or_null_regs
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
