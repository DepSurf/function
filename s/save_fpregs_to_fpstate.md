# Function: <code>save_fpregs_to_fpstate</code>

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
In <code>5.13</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void save_fpregs_to_fpstate(struct fpu *fpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/fpu/core.c (ffffffff81049180)
Location: arch/x86/kernel/fpu/core.c:99
Inline: False
Direct callers:
  - arch/x86/kernel/process_64.c:__switch_to
  - arch/x86/kernel/fpu/core.c:fpu_clone
  - arch/x86/kernel/fpu/core.c:fpu_sync_fpstate
  - arch/x86/kernel/fpu/core.c:kernel_fpu_begin_mask
```
**Symbols:**

```
ffffffff81049180-ffffffff810491dc: save_fpregs_to_fpstate (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void save_fpregs_to_fpstate(struct fpu *fpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/fpu/core.c (ffffffff81052dd0)
Location: arch/x86/kernel/fpu/core.c:115
Inline: False
Direct callers:
  - arch/x86/kernel/process_64.c:__switch_to
  - arch/x86/kernel/fpu/core.c:fpu_clone
  - arch/x86/kernel/fpu/core.c:fpu_sync_fpstate
  - arch/x86/kernel/fpu/core.c:kernel_fpu_begin_mask
  - arch/x86/kernel/fpu/core.c:fpu_swap_kvm_fpstate
```
**Symbols:**

```
ffffffff81052dd0-ffffffff81052e28: save_fpregs_to_fpstate (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void save_fpregs_to_fpstate(struct fpu *fpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/fpu/core.c (ffffffff81060760)
Location: arch/x86/kernel/fpu/core.c:115
Inline: False
Direct callers:
  - arch/x86/kernel/process_64.c:__switch_to
  - arch/x86/kernel/fpu/core.c:fpu_clone
  - arch/x86/kernel/fpu/core.c:fpu_sync_fpstate
  - arch/x86/kernel/fpu/core.c:kernel_fpu_begin_mask
  - arch/x86/kernel/fpu/core.c:fpu_swap_kvm_fpstate
```
**Symbols:**

```
ffffffff81060760-ffffffff810607b8: save_fpregs_to_fpstate (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void save_fpregs_to_fpstate(struct fpu *fpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/fpu/core.c (ffffffff81062130)
Location: arch/x86/kernel/fpu/core.c:115
Inline: False
Direct callers:
  - arch/x86/kernel/process_64.c:__switch_to
  - arch/x86/kernel/fpu/core.c:fpu_clone
  - arch/x86/kernel/fpu/core.c:fpu_sync_fpstate
  - arch/x86/kernel/fpu/core.c:kernel_fpu_begin_mask
  - arch/x86/kernel/fpu/core.c:fpu_swap_kvm_fpstate
```
**Symbols:**

```
ffffffff81062130-ffffffff81062188: save_fpregs_to_fpstate (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void save_fpregs_to_fpstate(struct fpu *fpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/fpu/core.c (ffffffff81069250)
Location: arch/x86/kernel/fpu/core.c:115
Inline: False
Direct callers:
  - arch/x86/kernel/process_64.c:__switch_to
  - arch/x86/kernel/fpu/core.c:fpu_clone
  - arch/x86/kernel/fpu/core.c:fpu_sync_fpstate
  - arch/x86/kernel/fpu/core.c:kernel_fpu_begin_mask
  - arch/x86/kernel/fpu/core.c:fpu_swap_kvm_fpstate
```
**Symbols:**

```
ffffffff81069250-ffffffff810692a8: save_fpregs_to_fpstate (STB_GLOBAL)
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
