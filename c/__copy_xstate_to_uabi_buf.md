# Function: <code>__copy_xstate_to_uabi_buf</code>

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
In <code>5.15</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void __copy_xstate_to_uabi_buf(struct membuf to, struct fpstate *fpstate, u32 pkru_val, enum xstate_copy_mode copy_mode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/fpu/xstate.c (ffffffff81056410)
Location: arch/x86/kernel/fpu/xstate.c:1063
Inline: False
Direct callers:
  - arch/x86/kernel/fpu/core.c:fpu_copy_guest_fpstate_to_uabi
  - arch/x86/kernel/fpu/xstate.c:copy_xstate_to_uabi_buf
```
**Symbols:**

```
ffffffff81056410-ffffffff81056ea4: __copy_xstate_to_uabi_buf (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void __copy_xstate_to_uabi_buf(struct membuf to, struct fpstate *fpstate, u32 pkru_val, enum xstate_copy_mode copy_mode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/fpu/xstate.c (ffffffff810640b0)
Location: arch/x86/kernel/fpu/xstate.c:1058
Inline: False
Direct callers:
  - arch/x86/kernel/fpu/core.c:fpu_copy_guest_fpstate_to_uabi
  - arch/x86/kernel/fpu/xstate.c:copy_xstate_to_uabi_buf
```
**Symbols:**

```
ffffffff810640b0-ffffffff81064521: __copy_xstate_to_uabi_buf (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void __copy_xstate_to_uabi_buf(struct membuf to, struct fpstate *fpstate, u32 pkru_val, enum xstate_copy_mode copy_mode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/fpu/xstate.c (ffffffff81065a00)
Location: arch/x86/kernel/fpu/xstate.c:1065
Inline: False
Direct callers:
  - arch/x86/kernel/fpu/core.c:fpu_copy_guest_fpstate_to_uabi
  - arch/x86/kernel/fpu/xstate.c:copy_xstate_to_uabi_buf
```
**Symbols:**

```
ffffffff81065a00-ffffffff81065e37: __copy_xstate_to_uabi_buf (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void __copy_xstate_to_uabi_buf(struct membuf to, struct fpstate *fpstate, u64 xfeatures, u32 pkru_val, enum xstate_copy_mode copy_mode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/fpu/xstate.c (ffffffff8106ce60)
Location: arch/x86/kernel/fpu/xstate.c:1062
Inline: False
Direct callers:
  - arch/x86/kernel/fpu/core.c:fpu_copy_guest_fpstate_to_uabi
  - arch/x86/kernel/fpu/xstate.c:copy_xstate_to_uabi_buf
```
**Symbols:**

```
ffffffff8106ce60-ffffffff8106d2a1: __copy_xstate_to_uabi_buf (STB_GLOBAL)
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
No changes between <code>5.19</code> and <code>6.2</code> ✅
</li>
<li>
No changes between <code>6.2</code> and <code>6.5</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>6.5</code> and <code>6.8</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>u64 xfeatures</code>
</li>
<li>
<b>Param reordered. </b>
<code>to, fpstate, pkru_val, copy_mode</code> ➡️ <code>to, fpstate, xfeatures, pkru_val, copy_mode</code>
</li>
</ul>
</details>
</li>
</ul>
