# Function: <code>kernel_fpu_begin</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void kernel_fpu_begin();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/fpu/core.c (ffffffff81039de0)
Location: arch/x86/kernel/fpu/core.c:138
Inline: False
Direct callers:
  - arch/x86/kernel/fpu/bugs.c:fpu__init_check_bugs
  - arch/x86/power/cpu.c:save_processor_state
```
**Symbols:**

```
ffffffff81039de0-ffffffff81039df0: kernel_fpu_begin (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void kernel_fpu_begin();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/fpu/core.c (ffffffff81038fc0)
Location: arch/x86/kernel/fpu/core.c:146
Inline: False
Direct callers:
  - arch/x86/kernel/fpu/bugs.c:fpu__init_check_bugs
  - arch/x86/power/cpu.c:save_processor_state
```
**Symbols:**

```
ffffffff81038fc0-ffffffff81038fd0: kernel_fpu_begin (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void kernel_fpu_begin();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/fpu/core.c (ffffffff810387a0)
Location: arch/x86/kernel/fpu/core.c:127
Inline: False
Direct callers:
  - arch/x86/kernel/fpu/bugs.c:fpu__init_check_bugs
  - arch/x86/power/cpu.c:save_processor_state
```
**Symbols:**

```
ffffffff810387a0-ffffffff810387b0: kernel_fpu_begin (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void kernel_fpu_begin();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/fpu/core.c (ffffffff810368b0)
Location: arch/x86/kernel/fpu/core.c:126
Inline: False
Direct callers:
  - arch/x86/kernel/fpu/bugs.c:fpu__init_check_bugs
  - arch/x86/power/cpu.c:save_processor_state
```
**Symbols:**

```
ffffffff810368b0-ffffffff810368c0: kernel_fpu_begin (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void kernel_fpu_begin();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/fpu/core.c (ffffffff81038c80)
Location: arch/x86/kernel/fpu/core.c:126
Inline: False
Direct callers:
  - arch/x86/kernel/fpu/bugs.c:fpu__init_check_bugs
  - arch/x86/power/cpu.c:save_processor_state
```
**Symbols:**

```
ffffffff81038c80-ffffffff81038c90: kernel_fpu_begin (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void kernel_fpu_begin();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/fpu/core.c (ffffffff8103a430)
Location: arch/x86/kernel/fpu/core.c:127
Inline: False
Direct callers:
  - arch/x86/kernel/fpu/bugs.c:fpu__init_check_bugs
  - arch/x86/power/cpu.c:save_processor_state
```
**Symbols:**

```
ffffffff8103a430-ffffffff8103a440: kernel_fpu_begin (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void kernel_fpu_begin();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/fpu/core.c (ffffffff8103ba10)
Location: arch/x86/kernel/fpu/core.c:125
Inline: False
Direct callers:
  - arch/x86/kernel/fpu/bugs.c:fpu__init_check_bugs
  - arch/x86/platform/efi/efi_64.c:efi_thunk_reset_system
  - arch/x86/platform/efi/efi_64.c:efi_thunk_get_next_high_mono_count
  - arch/x86/platform/efi/efi_64.c:efi_thunk_get_next_variable
  - arch/x86/platform/efi/efi_64.c:efi_thunk_set_variable_nonblocking
  - arch/x86/platform/efi/efi_64.c:efi_thunk_set_variable
  - arch/x86/platform/efi/efi_64.c:efi_thunk_get_variable
  - arch/x86/platform/efi/efi_64.c:efi_thunk_set_wakeup_time
  - arch/x86/platform/efi/efi_64.c:efi_thunk_get_wakeup_time
  - arch/x86/platform/efi/efi_64.c:efi_thunk_set_time
  - arch/x86/platform/efi/efi_64.c:efi_thunk_get_time
  - drivers/firmware/efi/runtime-wrappers.c:virt_efi_reset_system
  - drivers/firmware/efi/runtime-wrappers.c:efi_call_rts
  - drivers/firmware/efi/runtime-wrappers.c:efi_call_rts
  - drivers/firmware/efi/runtime-wrappers.c:efi_call_rts
  - drivers/firmware/efi/runtime-wrappers.c:efi_call_rts
  - drivers/firmware/efi/runtime-wrappers.c:efi_call_rts
  - drivers/firmware/efi/runtime-wrappers.c:efi_call_rts
  - drivers/firmware/efi/runtime-wrappers.c:efi_call_rts
  - drivers/firmware/efi/runtime-wrappers.c:efi_call_rts
  - drivers/firmware/efi/runtime-wrappers.c:efi_call_rts
  - drivers/firmware/efi/runtime-wrappers.c:efi_call_rts
  - drivers/firmware/efi/runtime-wrappers.c:efi_call_rts
  - arch/x86/power/cpu.c:save_processor_state
```
**Symbols:**

```
ffffffff8103ba10-ffffffff8103babb: kernel_fpu_begin (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void kernel_fpu_begin();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/fpu/core.c (ffffffff8103dd20)
Location: arch/x86/kernel/fpu/core.c:85
Inline: False
Direct callers:
  - arch/x86/kernel/fpu/bugs.c:fpu__init_check_bugs
  - arch/x86/platform/efi/efi_64.c:efi_thunk_reset_system
  - arch/x86/platform/efi/efi_64.c:efi_thunk_get_next_high_mono_count
  - arch/x86/platform/efi/efi_64.c:efi_thunk_get_next_variable
  - arch/x86/platform/efi/efi_64.c:efi_thunk_set_variable_nonblocking
  - arch/x86/platform/efi/efi_64.c:efi_thunk_set_variable
  - arch/x86/platform/efi/efi_64.c:efi_thunk_get_variable
  - arch/x86/platform/efi/efi_64.c:efi_thunk_set_wakeup_time
  - arch/x86/platform/efi/efi_64.c:efi_thunk_get_wakeup_time
  - arch/x86/platform/efi/efi_64.c:efi_thunk_set_time
  - arch/x86/platform/efi/efi_64.c:efi_thunk_get_time
  - drivers/firmware/efi/runtime-wrappers.c:virt_efi_reset_system
  - drivers/firmware/efi/runtime-wrappers.c:efi_call_rts
  - drivers/firmware/efi/runtime-wrappers.c:efi_call_rts
  - drivers/firmware/efi/runtime-wrappers.c:efi_call_rts
  - drivers/firmware/efi/runtime-wrappers.c:efi_call_rts
  - drivers/firmware/efi/runtime-wrappers.c:efi_call_rts
  - drivers/firmware/efi/runtime-wrappers.c:efi_call_rts
  - drivers/firmware/efi/runtime-wrappers.c:efi_call_rts
  - drivers/firmware/efi/runtime-wrappers.c:efi_call_rts
  - drivers/firmware/efi/runtime-wrappers.c:efi_call_rts
  - drivers/firmware/efi/runtime-wrappers.c:efi_call_rts
  - drivers/firmware/efi/runtime-wrappers.c:efi_call_rts
```
**Symbols:**

```
ffffffff8103dd20-ffffffff8103ddf6: kernel_fpu_begin (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void kernel_fpu_begin();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/fpu/core.c (ffffffff8103e4e0)
Location: arch/x86/kernel/fpu/core.c:85
Inline: False
Direct callers:
  - arch/x86/kernel/fpu/bugs.c:fpu__init_check_bugs
  - arch/x86/platform/efi/efi_64.c:efi_thunk_reset_system
  - arch/x86/platform/efi/efi_64.c:efi_thunk_get_next_high_mono_count
  - arch/x86/platform/efi/efi_64.c:efi_thunk_get_next_variable
  - arch/x86/platform/efi/efi_64.c:efi_thunk_set_variable_nonblocking
  - arch/x86/platform/efi/efi_64.c:efi_thunk_set_variable
  - arch/x86/platform/efi/efi_64.c:efi_thunk_get_variable
  - arch/x86/platform/efi/efi_64.c:efi_thunk_set_wakeup_time
  - arch/x86/platform/efi/efi_64.c:efi_thunk_get_wakeup_time
  - arch/x86/platform/efi/efi_64.c:efi_thunk_set_time
  - arch/x86/platform/efi/efi_64.c:efi_thunk_get_time
  - arch/x86/platform/uv/bios_uv.c:__uv_bios_call
  - drivers/firmware/efi/runtime-wrappers.c:virt_efi_reset_system
  - drivers/firmware/efi/runtime-wrappers.c:efi_call_rts
  - drivers/firmware/efi/runtime-wrappers.c:efi_call_rts
  - drivers/firmware/efi/runtime-wrappers.c:efi_call_rts
  - drivers/firmware/efi/runtime-wrappers.c:efi_call_rts
  - drivers/firmware/efi/runtime-wrappers.c:efi_call_rts
  - drivers/firmware/efi/runtime-wrappers.c:efi_call_rts
  - drivers/firmware/efi/runtime-wrappers.c:efi_call_rts
  - drivers/firmware/efi/runtime-wrappers.c:efi_call_rts
  - drivers/firmware/efi/runtime-wrappers.c:efi_call_rts
  - drivers/firmware/efi/runtime-wrappers.c:efi_call_rts
  - drivers/firmware/efi/runtime-wrappers.c:efi_call_rts
  - arch/x86/power/cpu.c:save_processor_state
```
**Symbols:**

```
ffffffff8103e4e0-ffffffff8103e5b6: kernel_fpu_begin (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void kernel_fpu_begin();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/fpu/core.c (ffffffff810418c0)
Location: arch/x86/kernel/fpu/core.c:85
Inline: False
Direct callers:
  - arch/x86/kernel/fpu/bugs.c:fpu__init_check_bugs
  - arch/x86/crypto/crc32c-intel_glue.c:crc32c_pcl_intel_digest
  - arch/x86/crypto/crc32c-intel_glue.c:crc32c_pcl_intel_finup
  - arch/x86/platform/efi/efi_64.c:efi_set_virtual_address_map
  - arch/x86/platform/efi/efi_64.c:efi_thunk_reset_system
  - arch/x86/platform/efi/efi_64.c:efi_thunk_get_next_variable
  - arch/x86/platform/efi/efi_64.c:efi_thunk_set_variable_nonblocking
  - arch/x86/platform/efi/efi_64.c:efi_thunk_set_variable
  - arch/x86/platform/efi/efi_64.c:efi_thunk_get_variable
  - drivers/firmware/efi/runtime-wrappers.c:virt_efi_reset_system
  - drivers/firmware/efi/runtime-wrappers.c:efi_call_rts
  - drivers/firmware/efi/runtime-wrappers.c:efi_call_rts
  - drivers/firmware/efi/runtime-wrappers.c:efi_call_rts
  - drivers/firmware/efi/runtime-wrappers.c:efi_call_rts
  - drivers/firmware/efi/runtime-wrappers.c:efi_call_rts
  - drivers/firmware/efi/runtime-wrappers.c:efi_call_rts
  - drivers/firmware/efi/runtime-wrappers.c:efi_call_rts
  - drivers/firmware/efi/runtime-wrappers.c:efi_call_rts
  - drivers/firmware/efi/runtime-wrappers.c:efi_call_rts
  - drivers/firmware/efi/runtime-wrappers.c:efi_call_rts
  - drivers/firmware/efi/runtime-wrappers.c:efi_call_rts
```
**Symbols:**

```
ffffffff810418c0-ffffffff8104197f: kernel_fpu_begin (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/fpu/bugs.c (ffffffff82fbef4e)
Location: arch/x86/include/asm/fpu/api.h:33
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/bugs.c:fpu__init_check_bugs
```
```
In arch/x86/crypto/crc32c-intel_glue.c (ffffffff8109473a)
Location: arch/x86/include/asm/fpu/api.h:33
Inline: True
Inline callers:
  - arch/x86/crypto/crc32c-intel_glue.c:crc32c_pcl_intel_digest
  - arch/x86/crypto/crc32c-intel_glue.c:crc32c_pcl_intel_finup
```
```
In arch/x86/platform/efi/efi_64.c (ffffffff82fd8984)
Location: arch/x86/include/asm/fpu/api.h:33
Inline: True
Inline callers:
  - arch/x86/platform/efi/efi_64.c:efi_set_virtual_address_map
  - arch/x86/platform/efi/efi_64.c:efi_thunk_reset_system
  - arch/x86/platform/efi/efi_64.c:efi_thunk_get_next_variable
  - arch/x86/platform/efi/efi_64.c:efi_thunk_set_variable_nonblocking
  - arch/x86/platform/efi/efi_64.c:efi_thunk_set_variable
  - arch/x86/platform/efi/efi_64.c:efi_thunk_get_variable
```
```
In arch/x86/platform/uv/bios_uv.c (ffffffff81098f5e)
Location: arch/x86/include/asm/fpu/api.h:33
Inline: True
Inline callers:
  - arch/x86/platform/uv/bios_uv.c:__uv_bios_call
```
```
In drivers/firmware/efi/runtime-wrappers.c (ffffffff819c25a5)
Location: arch/x86/include/asm/fpu/api.h:33
Inline: True
Inline callers:
  - drivers/firmware/efi/runtime-wrappers.c:virt_efi_reset_system
  - drivers/firmware/efi/runtime-wrappers.c:efi_call_rts
  - drivers/firmware/efi/runtime-wrappers.c:efi_call_rts
  - drivers/firmware/efi/runtime-wrappers.c:efi_call_rts
  - drivers/firmware/efi/runtime-wrappers.c:efi_call_rts
  - drivers/firmware/efi/runtime-wrappers.c:efi_call_rts
  - drivers/firmware/efi/runtime-wrappers.c:efi_call_rts
  - drivers/firmware/efi/runtime-wrappers.c:efi_call_rts
  - drivers/firmware/efi/runtime-wrappers.c:efi_call_rts
  - drivers/firmware/efi/runtime-wrappers.c:efi_call_rts
  - drivers/firmware/efi/runtime-wrappers.c:efi_call_rts
  - drivers/firmware/efi/runtime-wrappers.c:efi_call_rts
```
```
In arch/x86/power/cpu.c (ffffffff81bce985)
Location: arch/x86/include/asm/fpu/api.h:33
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/fpu/bugs.c (ffffffff831c95ac)
Location: arch/x86/include/asm/fpu/api.h:33
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/bugs.c:fpu__init_check_bugs
```
```
In arch/x86/crypto/crc32c-intel_glue.c (ffffffff810950aa)
Location: arch/x86/include/asm/fpu/api.h:33
Inline: True
Inline callers:
  - arch/x86/crypto/crc32c-intel_glue.c:crc32c_pcl_intel_digest
  - arch/x86/crypto/crc32c-intel_glue.c:crc32c_pcl_intel_finup
```
```
In arch/x86/power/cpu.c (ffffffff81bc2335)
Location: arch/x86/include/asm/fpu/api.h:33
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/fpu/bugs.c (ffffffff832aa879)
Location: arch/x86/include/asm/fpu/api.h:33
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/bugs.c:fpu__init_check_bugs
```
```
In arch/x86/crypto/crc32c-intel_glue.c (ffffffff810a504a)
Location: arch/x86/include/asm/fpu/api.h:33
Inline: True
Inline callers:
  - arch/x86/crypto/crc32c-intel_glue.c:crc32c_pcl_intel_digest
  - arch/x86/crypto/crc32c-intel_glue.c:crc32c_pcl_intel_finup
```
```
In arch/x86/power/cpu.c (ffffffff81c92995)
Location: arch/x86/include/asm/fpu/api.h:33
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/fpu/bugs.c (ffffffff8345a057)
Location: arch/x86/include/asm/fpu/api.h:35
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/bugs.c:fpu__init_check_bugs
```
```
In arch/x86/crypto/blake2s-glue.c (ffffffff810b9fda)
Location: arch/x86/include/asm/fpu/api.h:35
Inline: True
Inline callers:
  - arch/x86/crypto/blake2s-glue.c:blake2s_compress
```
```
In arch/x86/crypto/crc32c-intel_glue.c (ffffffff810ba1a2)
Location: arch/x86/include/asm/fpu/api.h:35
Inline: True
Inline callers:
  - arch/x86/crypto/crc32c-intel_glue.c:crc32c_pcl_intel_digest
  - arch/x86/crypto/crc32c-intel_glue.c:crc32c_pcl_intel_finup
```
```
In arch/x86/power/cpu.c (ffffffff81e422e5)
Location: arch/x86/include/asm/fpu/api.h:35
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/fpu/bugs.c (ffffffff83e79c98)
Location: arch/x86/include/asm/fpu/api.h:35
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/bugs.c:fpu__init_check_bugs
```
```
In arch/x86/crypto/blake2s-glue.c (ffffffff810d5d2a)
Location: arch/x86/include/asm/fpu/api.h:35
Inline: True
Inline callers:
  - arch/x86/crypto/blake2s-glue.c:blake2s_compress
```
```
In arch/x86/crypto/crc32c-intel_glue.c (ffffffff810d5f42)
Location: arch/x86/include/asm/fpu/api.h:35
Inline: True
Inline callers:
  - arch/x86/crypto/crc32c-intel_glue.c:crc32c_pcl_intel_digest
  - arch/x86/crypto/crc32c-intel_glue.c:crc32c_pcl_intel_finup
```
```
In arch/x86/power/cpu.c (ffffffff8201ccb5)
Location: arch/x86/include/asm/fpu/api.h:35
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/fpu/bugs.c (ffffffff8369c3b8)
Location: arch/x86/include/asm/fpu/api.h:35
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/bugs.c:fpu__init_check_bugs
```
```
In arch/x86/crypto/sha512_ssse3_glue.c (ffffffff810e0a4b)
Location: arch/x86/include/asm/fpu/api.h:35
Inline: True
```
```
In arch/x86/crypto/blake2s-glue.c (ffffffff810e126a)
Location: arch/x86/include/asm/fpu/api.h:35
Inline: True
Inline callers:
  - arch/x86/crypto/blake2s-glue.c:blake2s_compress
```
```
In arch/x86/crypto/crc32c-intel_glue.c (ffffffff810e1482)
Location: arch/x86/include/asm/fpu/api.h:35
Inline: True
Inline callers:
  - arch/x86/crypto/crc32c-intel_glue.c:crc32c_pcl_intel_digest
  - arch/x86/crypto/crc32c-intel_glue.c:crc32c_pcl_intel_finup
```
```
In arch/x86/power/cpu.c (ffffffff8209d345)
Location: arch/x86/include/asm/fpu/api.h:35
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/fpu/bugs.c (ffffffff838cc098)
Location: arch/x86/include/asm/fpu/api.h:35
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/bugs.c:fpu__init_check_bugs
```
```
In arch/x86/crypto/sha512_ssse3_glue.c (ffffffff810e92cb)
Location: arch/x86/include/asm/fpu/api.h:35
Inline: True
```
```
In arch/x86/crypto/blake2s-glue.c (ffffffff810e9aea)
Location: arch/x86/include/asm/fpu/api.h:35
Inline: True
Inline callers:
  - arch/x86/crypto/blake2s-glue.c:blake2s_compress
```
```
In arch/x86/crypto/crc32c-intel_glue.c (ffffffff810e9d02)
Location: arch/x86/include/asm/fpu/api.h:35
Inline: True
Inline callers:
  - arch/x86/crypto/crc32c-intel_glue.c:crc32c_pcl_intel_digest
  - arch/x86/crypto/crc32c-intel_glue.c:crc32c_pcl_intel_finup
```
```
In drivers/gpu/drm/drm_cache.c (ffffffff81c80e45)
Location: arch/x86/include/asm/fpu/api.h:35
Inline: True
Inline callers:
  - drivers/gpu/drm/drm_cache.c:__drm_memcpy_from_wc
```
```
In arch/x86/power/cpu.c (ffffffff82174b45)
Location: arch/x86/include/asm/fpu/api.h:35
Inline: True
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
<details>
<summary>In <code>aws</code>: ✅</summary>

```c
void kernel_fpu_begin();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/fpu/core.c (ffffffff8103e660)
Location: arch/x86/kernel/fpu/core.c:85
Inline: False
Direct callers:
  - arch/x86/kernel/fpu/bugs.c:fpu__init_check_bugs
  - arch/x86/platform/efi/efi_64.c:efi_thunk_reset_system
  - arch/x86/platform/efi/efi_64.c:efi_thunk_get_next_high_mono_count
  - arch/x86/platform/efi/efi_64.c:efi_thunk_get_next_variable
  - arch/x86/platform/efi/efi_64.c:efi_thunk_set_variable_nonblocking
  - arch/x86/platform/efi/efi_64.c:efi_thunk_set_variable
  - arch/x86/platform/efi/efi_64.c:efi_thunk_get_variable
  - arch/x86/platform/efi/efi_64.c:efi_thunk_set_wakeup_time
  - arch/x86/platform/efi/efi_64.c:efi_thunk_get_wakeup_time
  - arch/x86/platform/efi/efi_64.c:efi_thunk_set_time
  - arch/x86/platform/efi/efi_64.c:efi_thunk_get_time
  - drivers/firmware/efi/runtime-wrappers.c:virt_efi_reset_system
  - drivers/firmware/efi/runtime-wrappers.c:efi_call_rts
  - drivers/firmware/efi/runtime-wrappers.c:efi_call_rts
  - drivers/firmware/efi/runtime-wrappers.c:efi_call_rts
  - drivers/firmware/efi/runtime-wrappers.c:efi_call_rts
  - drivers/firmware/efi/runtime-wrappers.c:efi_call_rts
  - drivers/firmware/efi/runtime-wrappers.c:efi_call_rts
  - drivers/firmware/efi/runtime-wrappers.c:efi_call_rts
  - drivers/firmware/efi/runtime-wrappers.c:efi_call_rts
  - drivers/firmware/efi/runtime-wrappers.c:efi_call_rts
  - drivers/firmware/efi/runtime-wrappers.c:efi_call_rts
  - drivers/firmware/efi/runtime-wrappers.c:efi_call_rts
  - arch/x86/power/cpu.c:save_processor_state
```
**Symbols:**

```
ffffffff8103e660-ffffffff8103e736: kernel_fpu_begin (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void kernel_fpu_begin();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/fpu/core.c (ffffffff8102de60)
Location: arch/x86/kernel/fpu/core.c:85
Inline: False
Direct callers:
  - arch/x86/kernel/fpu/bugs.c:fpu__init_check_bugs
  - arch/x86/platform/efi/efi_64.c:efi_thunk_reset_system
  - arch/x86/platform/efi/efi_64.c:efi_thunk_get_next_high_mono_count
  - arch/x86/platform/efi/efi_64.c:efi_thunk_get_next_variable
  - arch/x86/platform/efi/efi_64.c:efi_thunk_set_variable_nonblocking
  - arch/x86/platform/efi/efi_64.c:efi_thunk_set_variable
  - arch/x86/platform/efi/efi_64.c:efi_thunk_get_variable
  - arch/x86/platform/efi/efi_64.c:efi_thunk_set_wakeup_time
  - arch/x86/platform/efi/efi_64.c:efi_thunk_get_wakeup_time
  - arch/x86/platform/efi/efi_64.c:efi_thunk_set_time
  - arch/x86/platform/efi/efi_64.c:efi_thunk_get_time
  - drivers/firmware/efi/runtime-wrappers.c:virt_efi_reset_system
  - drivers/firmware/efi/runtime-wrappers.c:efi_call_rts
  - drivers/firmware/efi/runtime-wrappers.c:efi_call_rts
  - drivers/firmware/efi/runtime-wrappers.c:efi_call_rts
  - drivers/firmware/efi/runtime-wrappers.c:efi_call_rts
  - drivers/firmware/efi/runtime-wrappers.c:efi_call_rts
  - drivers/firmware/efi/runtime-wrappers.c:efi_call_rts
  - drivers/firmware/efi/runtime-wrappers.c:efi_call_rts
  - drivers/firmware/efi/runtime-wrappers.c:efi_call_rts
  - drivers/firmware/efi/runtime-wrappers.c:efi_call_rts
  - drivers/firmware/efi/runtime-wrappers.c:efi_call_rts
  - drivers/firmware/efi/runtime-wrappers.c:efi_call_rts
  - arch/x86/power/cpu.c:save_processor_state
```
**Symbols:**

```
ffffffff8102de60-ffffffff8102df36: kernel_fpu_begin (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void kernel_fpu_begin();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/fpu/core.c (ffffffff8103e4a0)
Location: arch/x86/kernel/fpu/core.c:85
Inline: False
Direct callers:
  - arch/x86/kernel/fpu/bugs.c:fpu__init_check_bugs
  - arch/x86/platform/efi/efi_64.c:efi_thunk_reset_system
  - arch/x86/platform/efi/efi_64.c:efi_thunk_get_next_high_mono_count
  - arch/x86/platform/efi/efi_64.c:efi_thunk_get_next_variable
  - arch/x86/platform/efi/efi_64.c:efi_thunk_set_variable_nonblocking
  - arch/x86/platform/efi/efi_64.c:efi_thunk_set_variable
  - arch/x86/platform/efi/efi_64.c:efi_thunk_get_variable
  - arch/x86/platform/efi/efi_64.c:efi_thunk_set_wakeup_time
  - arch/x86/platform/efi/efi_64.c:efi_thunk_get_wakeup_time
  - arch/x86/platform/efi/efi_64.c:efi_thunk_set_time
  - arch/x86/platform/efi/efi_64.c:efi_thunk_get_time
  - drivers/firmware/efi/runtime-wrappers.c:virt_efi_reset_system
  - drivers/firmware/efi/runtime-wrappers.c:efi_call_rts
  - drivers/firmware/efi/runtime-wrappers.c:efi_call_rts
  - drivers/firmware/efi/runtime-wrappers.c:efi_call_rts
  - drivers/firmware/efi/runtime-wrappers.c:efi_call_rts
  - drivers/firmware/efi/runtime-wrappers.c:efi_call_rts
  - drivers/firmware/efi/runtime-wrappers.c:efi_call_rts
  - drivers/firmware/efi/runtime-wrappers.c:efi_call_rts
  - drivers/firmware/efi/runtime-wrappers.c:efi_call_rts
  - drivers/firmware/efi/runtime-wrappers.c:efi_call_rts
  - drivers/firmware/efi/runtime-wrappers.c:efi_call_rts
  - drivers/firmware/efi/runtime-wrappers.c:efi_call_rts
  - arch/x86/power/cpu.c:save_processor_state
```
**Symbols:**

```
ffffffff8103e4a0-ffffffff8103e576: kernel_fpu_begin (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void kernel_fpu_begin();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/fpu/core.c (ffffffff8103f630)
Location: arch/x86/kernel/fpu/core.c:85
Inline: False
Direct callers:
  - arch/x86/kernel/fpu/bugs.c:fpu__init_check_bugs
  - arch/x86/platform/efi/efi_64.c:efi_thunk_reset_system
  - arch/x86/platform/efi/efi_64.c:efi_thunk_get_next_high_mono_count
  - arch/x86/platform/efi/efi_64.c:efi_thunk_get_next_variable
  - arch/x86/platform/efi/efi_64.c:efi_thunk_set_variable_nonblocking
  - arch/x86/platform/efi/efi_64.c:efi_thunk_set_variable
  - arch/x86/platform/efi/efi_64.c:efi_thunk_get_variable
  - arch/x86/platform/efi/efi_64.c:efi_thunk_set_wakeup_time
  - arch/x86/platform/efi/efi_64.c:efi_thunk_get_wakeup_time
  - arch/x86/platform/efi/efi_64.c:efi_thunk_set_time
  - arch/x86/platform/efi/efi_64.c:efi_thunk_get_time
  - arch/x86/platform/uv/bios_uv.c:__uv_bios_call
  - drivers/firmware/efi/runtime-wrappers.c:virt_efi_reset_system
  - drivers/firmware/efi/runtime-wrappers.c:efi_call_rts
  - drivers/firmware/efi/runtime-wrappers.c:efi_call_rts
  - drivers/firmware/efi/runtime-wrappers.c:efi_call_rts
  - drivers/firmware/efi/runtime-wrappers.c:efi_call_rts
  - drivers/firmware/efi/runtime-wrappers.c:efi_call_rts
  - drivers/firmware/efi/runtime-wrappers.c:efi_call_rts
  - drivers/firmware/efi/runtime-wrappers.c:efi_call_rts
  - drivers/firmware/efi/runtime-wrappers.c:efi_call_rts
  - drivers/firmware/efi/runtime-wrappers.c:efi_call_rts
  - drivers/firmware/efi/runtime-wrappers.c:efi_call_rts
  - drivers/firmware/efi/runtime-wrappers.c:efi_call_rts
  - arch/x86/power/cpu.c:save_processor_state
```
**Symbols:**

```
ffffffff8103f630-ffffffff8103f70d: kernel_fpu_begin (STB_GLOBAL)
```
</details>
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
<li>
No changes between <code>4.18</code> and <code>5.0</code> ✅
</li>
<li>
No changes between <code>5.0</code> and <code>5.3</code> ✅
</li>
<li>
No changes between <code>5.3</code> and <code>5.4</code> ✅
</li>
<li>
No changes between <code>5.4</code> and <code>5.8</code> ✅
</li>
</ul>
<b>Arch</b>
<ul>
</ul>
<b>Flavor</b>
<ul>
<li>
No changes between <code>generic</code> and <code>aws</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>azure</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>gcp</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>lowlatency</code> ✅
</li>
</ul>
