# Function: <code>validate_user_xstate_header</code>

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
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int validate_user_xstate_header(const struct xstate_header *hdr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/fpu/xstate.c (ffffffff810437a0)
Location: arch/x86/kernel/fpu/xstate.c:513
Inline: False
Direct callers:
  - arch/x86/kernel/fpu/regset.c:xstateregs_set
  - arch/x86/kernel/fpu/signal.c:__fpu__restore_sig
  - arch/x86/kernel/fpu/xstate.c:copy_user_to_xstate
  - arch/x86/kernel/fpu/xstate.c:copy_kernel_to_xstate
```
**Symbols:**

```
ffffffff810437a0-ffffffff810437ed: validate_user_xstate_header (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int validate_user_xstate_header(const struct xstate_header *hdr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/fpu/xstate.c (ffffffff81043830)
Location: arch/x86/kernel/fpu/xstate.c:518
Inline: False
Direct callers:
  - arch/x86/kernel/fpu/regset.c:xstateregs_set
  - arch/x86/kernel/fpu/signal.c:__fpu__restore_sig
  - arch/x86/kernel/fpu/xstate.c:copy_user_to_xstate
  - arch/x86/kernel/fpu/xstate.c:copy_kernel_to_xstate
```
**Symbols:**

```
ffffffff81043830-ffffffff8104387d: validate_user_xstate_header (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int validate_user_xstate_header(const struct xstate_header *hdr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/fpu/xstate.c (ffffffff81045080)
Location: arch/x86/kernel/fpu/xstate.c:553
Inline: False
Direct callers:
  - arch/x86/kernel/fpu/regset.c:xstateregs_set
  - arch/x86/kernel/fpu/xstate.c:copy_user_to_xstate
  - arch/x86/kernel/fpu/xstate.c:copy_kernel_to_xstate
```
**Symbols:**

```
ffffffff81045080-ffffffff810450cd: validate_user_xstate_header (STB_GLOBAL)
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
In arch/x86/kernel/fpu/xstate.c (ffffffff8104b212)
Location: arch/x86/kernel/fpu/xstate.c:454
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/xstate.c:copy_uabi_to_xstate
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
In arch/x86/kernel/fpu/xstate.c (ffffffff81055994)
Location: arch/x86/kernel/fpu/xstate.c:399
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/xstate.c:copy_uabi_to_xstate
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
In arch/x86/kernel/fpu/xstate.c (ffffffff810634ab)
Location: arch/x86/kernel/fpu/xstate.c:399
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/xstate.c:copy_uabi_to_xstate
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/fpu/xstate.c (ffffffff81064dfb)
Location: arch/x86/kernel/fpu/xstate.c:399
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/xstate.c:copy_uabi_to_xstate
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/fpu/xstate.c (ffffffff8106c4ab)
Location: arch/x86/kernel/fpu/xstate.c:402
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/xstate.c:copy_uabi_to_xstate
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
No changes between <code>5.8</code> and <code>5.11</code> ✅
</li>
<li>
No changes between <code>5.11</code> and <code>5.13</code> ✅
</li>
</ul>
