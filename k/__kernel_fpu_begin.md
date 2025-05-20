# Function: <code>__kernel_fpu_begin</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void __kernel_fpu_begin();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/fpu/core.c (ffffffff81039ce0)
Location: arch/x86/kernel/fpu/core.c:108
Inline: False
Direct callers:
  - arch/x86/kernel/fpu/core.c:kernel_fpu_begin
  - drivers/firmware/efi/runtime-wrappers.c:virt_efi_reset_system
  - drivers/firmware/efi/runtime-wrappers.c:virt_efi_get_next_high_mono_count
  - drivers/firmware/efi/runtime-wrappers.c:virt_efi_set_variable_nonblocking
  - drivers/firmware/efi/runtime-wrappers.c:virt_efi_set_variable
  - drivers/firmware/efi/runtime-wrappers.c:virt_efi_get_next_variable
  - drivers/firmware/efi/runtime-wrappers.c:virt_efi_get_variable
  - drivers/firmware/efi/runtime-wrappers.c:virt_efi_set_wakeup_time
  - drivers/firmware/efi/runtime-wrappers.c:virt_efi_get_wakeup_time
  - drivers/firmware/efi/runtime-wrappers.c:virt_efi_set_time
  - drivers/firmware/efi/runtime-wrappers.c:virt_efi_get_time
```
**Symbols:**

```
ffffffff81039ce0-ffffffff81039ddf: __kernel_fpu_begin (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void __kernel_fpu_begin();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/fpu/core.c (ffffffff81038ed0)
Location: arch/x86/kernel/fpu/core.c:112
Inline: False
Direct callers:
  - arch/x86/kernel/fpu/core.c:kernel_fpu_begin
  - arch/x86/platform/efi/efi_64.c:efi_thunk_reset_system
  - arch/x86/platform/efi/efi_64.c:efi_thunk_get_next_high_mono_count
  - arch/x86/platform/efi/efi_64.c:efi_thunk_get_next_variable
  - arch/x86/platform/efi/efi_64.c:efi_thunk_set_variable
  - arch/x86/platform/efi/efi_64.c:efi_thunk_get_variable
  - arch/x86/platform/efi/efi_64.c:efi_thunk_set_wakeup_time
  - arch/x86/platform/efi/efi_64.c:efi_thunk_get_wakeup_time
  - arch/x86/platform/efi/efi_64.c:efi_thunk_set_time
  - arch/x86/platform/efi/efi_64.c:efi_thunk_get_time
  - drivers/firmware/efi/runtime-wrappers.c:virt_efi_reset_system
  - drivers/firmware/efi/runtime-wrappers.c:virt_efi_get_next_high_mono_count
  - drivers/firmware/efi/runtime-wrappers.c:virt_efi_set_variable
  - drivers/firmware/efi/runtime-wrappers.c:virt_efi_get_next_variable
  - drivers/firmware/efi/runtime-wrappers.c:virt_efi_get_variable
  - drivers/firmware/efi/runtime-wrappers.c:virt_efi_set_wakeup_time
  - drivers/firmware/efi/runtime-wrappers.c:virt_efi_get_wakeup_time
  - drivers/firmware/efi/runtime-wrappers.c:virt_efi_set_time
  - drivers/firmware/efi/runtime-wrappers.c:virt_efi_get_time
```
**Symbols:**

```
ffffffff81038ed0-ffffffff81038fbe: __kernel_fpu_begin (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void __kernel_fpu_begin();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/fpu/core.c (ffffffff810386a0)
Location: arch/x86/kernel/fpu/core.c:96
Inline: False
Direct callers:
  - arch/x86/kernel/fpu/core.c:kernel_fpu_begin
  - arch/x86/platform/efi/efi_64.c:efi_thunk_reset_system
  - arch/x86/platform/efi/efi_64.c:efi_thunk_reset_system
  - arch/x86/platform/efi/efi_64.c:efi_thunk_get_next_high_mono_count
  - arch/x86/platform/efi/efi_64.c:efi_thunk_get_next_variable
  - arch/x86/platform/efi/efi_64.c:efi_thunk_get_next_variable
  - arch/x86/platform/efi/efi_64.c:efi_thunk_set_variable
  - arch/x86/platform/efi/efi_64.c:efi_thunk_set_variable
  - arch/x86/platform/efi/efi_64.c:efi_thunk_get_variable
  - arch/x86/platform/efi/efi_64.c:efi_thunk_get_variable
  - arch/x86/platform/efi/efi_64.c:efi_thunk_set_wakeup_time
  - arch/x86/platform/efi/efi_64.c:efi_thunk_get_wakeup_time
  - arch/x86/platform/efi/efi_64.c:efi_thunk_set_time
  - arch/x86/platform/efi/efi_64.c:efi_thunk_get_time
  - drivers/firmware/efi/runtime-wrappers.c:virt_efi_reset_system
```
**Symbols:**

```
ffffffff810386a0-ffffffff81038798: __kernel_fpu_begin (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void __kernel_fpu_begin();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/fpu/core.c (ffffffff81036800)
Location: arch/x86/kernel/fpu/core.c:95
Inline: False
Direct callers:
  - arch/x86/kernel/fpu/core.c:kernel_fpu_begin
  - arch/x86/platform/efi/efi_64.c:efi_thunk_reset_system
  - arch/x86/platform/efi/efi_64.c:efi_thunk_reset_system
  - arch/x86/platform/efi/efi_64.c:efi_thunk_get_next_high_mono_count
  - arch/x86/platform/efi/efi_64.c:efi_thunk_get_next_variable
  - arch/x86/platform/efi/efi_64.c:efi_thunk_get_next_variable
  - arch/x86/platform/efi/efi_64.c:efi_thunk_set_variable
  - arch/x86/platform/efi/efi_64.c:efi_thunk_set_variable
  - arch/x86/platform/efi/efi_64.c:efi_thunk_get_variable
  - arch/x86/platform/efi/efi_64.c:efi_thunk_get_variable
  - arch/x86/platform/efi/efi_64.c:efi_thunk_set_wakeup_time
  - arch/x86/platform/efi/efi_64.c:efi_thunk_get_wakeup_time
  - arch/x86/platform/efi/efi_64.c:efi_thunk_set_time
  - arch/x86/platform/efi/efi_64.c:efi_thunk_get_time
  - drivers/firmware/efi/runtime-wrappers.c:virt_efi_reset_system
```
**Symbols:**

```
ffffffff81036800-ffffffff810368ac: __kernel_fpu_begin (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void __kernel_fpu_begin();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/fpu/core.c (ffffffff81038bd0)
Location: arch/x86/kernel/fpu/core.c:95
Inline: False
Direct callers:
  - arch/x86/kernel/fpu/core.c:kernel_fpu_begin
  - arch/x86/platform/efi/efi_64.c:efi_thunk_reset_system
  - arch/x86/platform/efi/efi_64.c:efi_thunk_get_next_high_mono_count
  - arch/x86/platform/efi/efi_64.c:efi_thunk_get_next_variable
  - arch/x86/platform/efi/efi_64.c:efi_thunk_set_variable
  - arch/x86/platform/efi/efi_64.c:efi_thunk_get_variable
  - arch/x86/platform/efi/efi_64.c:efi_thunk_set_wakeup_time
  - arch/x86/platform/efi/efi_64.c:efi_thunk_get_wakeup_time
  - arch/x86/platform/efi/efi_64.c:efi_thunk_set_time
  - arch/x86/platform/efi/efi_64.c:efi_thunk_get_time
  - drivers/firmware/efi/runtime-wrappers.c:virt_efi_reset_system
```
**Symbols:**

```
ffffffff81038bd0-ffffffff81038c7a: __kernel_fpu_begin (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void __kernel_fpu_begin();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/fpu/core.c (ffffffff8103a380)
Location: arch/x86/kernel/fpu/core.c:96
Inline: False
Direct callers:
  - arch/x86/kernel/fpu/core.c:kernel_fpu_begin
  - arch/x86/platform/efi/efi_64.c:efi_thunk_query_variable_info
  - arch/x86/platform/efi/efi_64.c:efi_thunk_reset_system
  - arch/x86/platform/efi/efi_64.c:efi_thunk_get_next_high_mono_count
  - arch/x86/platform/efi/efi_64.c:efi_thunk_get_next_variable
  - arch/x86/platform/efi/efi_64.c:efi_thunk_set_variable
  - arch/x86/platform/efi/efi_64.c:efi_thunk_get_variable
  - arch/x86/platform/efi/efi_64.c:efi_thunk_set_wakeup_time
  - arch/x86/platform/efi/efi_64.c:efi_thunk_get_wakeup_time
  - arch/x86/platform/efi/efi_64.c:efi_thunk_set_time
  - arch/x86/platform/efi/efi_64.c:efi_thunk_get_time
  - drivers/firmware/efi/runtime-wrappers.c:virt_efi_reset_system
```
**Symbols:**

```
ffffffff8103a380-ffffffff8103a42b: __kernel_fpu_begin (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/fpu/core.c (ffffffff8103ba1a)
Location: arch/x86/kernel/fpu/core.c:96
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/core.c:kernel_fpu_begin
```
</details>
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
In <code>5.19</code>: Absent ⚠️
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
No changes between <code>4.4</code> and <code>4.8</code> ✅
</li>
<li>
No changes between <code>4.8</code> and <code>4.10</code> ✅
</li>
<li>
No changes between <code>4.10</code> and <code>4.13</code> ✅
</li>
<li>
No changes between <code>4.13</code> and <code>4.15</code> ✅
</li>
<li>
No changes between <code>4.15</code> and <code>4.18</code> ✅
</li>
</ul>
