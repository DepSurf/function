# Function: <code>efi_call_virt_check_flags</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void efi_call_virt_check_flags(long unsigned int flags, const char *call);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/firmware/efi/runtime-wrappers.c (ffffffff81738430)
Location: drivers/firmware/efi/runtime-wrappers.c:34
Inline: False
Direct callers:
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
ffffffff81738430-ffffffff817384d1: efi_call_virt_check_flags (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void efi_call_virt_check_flags(long unsigned int flags, const char *call);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/firmware/efi/runtime-wrappers.c (ffffffff8176b5c0)
Location: drivers/firmware/efi/runtime-wrappers.c:36
Inline: False
Direct callers:
  - drivers/firmware/efi/runtime-wrappers.c:virt_efi_reset_system
```
**Symbols:**

```
ffffffff8176b5c0-ffffffff8176b661: efi_call_virt_check_flags (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void efi_call_virt_check_flags(long unsigned int flags, const char *call);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/firmware/efi/runtime-wrappers.c (ffffffff81789a00)
Location: drivers/firmware/efi/runtime-wrappers.c:36
Inline: False
Direct callers:
  - drivers/firmware/efi/runtime-wrappers.c:virt_efi_reset_system
```
**Symbols:**

```
ffffffff81789a00-ffffffff81789a80: efi_call_virt_check_flags (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void efi_call_virt_check_flags(long unsigned int flags, const char *call);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/firmware/efi/runtime-wrappers.c (ffffffff817ffe50)
Location: drivers/firmware/efi/runtime-wrappers.c:36
Inline: False
Direct callers:
  - drivers/firmware/efi/runtime-wrappers.c:virt_efi_reset_system
```
**Symbols:**

```
ffffffff817ffe50-ffffffff817ffed0: efi_call_virt_check_flags (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Transformation ⚠️</summary>

```c
void efi_call_virt_check_flags(long unsigned int flags, const char *call);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/firmware/efi/runtime-wrappers.c (0)
Location: drivers/firmware/efi/runtime-wrappers.c:36
Inline: False
Direct callers:
  - drivers/firmware/efi/runtime-wrappers.c:virt_efi_reset_system
```
**Symbols:**

```
ffffffff8184a4b5-ffffffff8184a4cf: efi_call_virt_check_flags.cold.13 (STB_LOCAL)
ffffffff818495a0-ffffffff81849608: efi_call_virt_check_flags (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Transformation ⚠️</summary>

```c
void efi_call_virt_check_flags(long unsigned int flags, const char *call);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/firmware/efi/runtime-wrappers.c (0)
Location: drivers/firmware/efi/runtime-wrappers.c:92
Inline: False
Direct callers:
  - drivers/firmware/efi/runtime-wrappers.c:virt_efi_reset_system
  - drivers/firmware/efi/runtime-wrappers.c:efi_call_rts
  - drivers/firmware/efi/runtime-wrappers.c:efi_call_rts
  - drivers/firmware/efi/runtime-wrappers.c:efi_call_rts
  - drivers/firmware/efi/runtime-wrappers.c:efi_call_rts
```
**Symbols:**

```
ffffffff81877392-ffffffff818773ac: efi_call_virt_check_flags.cold.14 (STB_LOCAL)
ffffffff81876620-ffffffff81876688: efi_call_virt_check_flags (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
void efi_call_virt_check_flags(long unsigned int flags, const char *call);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/firmware/efi/runtime-wrappers.c (0)
Location: drivers/firmware/efi/runtime-wrappers.c:104
Inline: False
Direct callers:
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
ffffffff818bb822-ffffffff818bb83c: efi_call_virt_check_flags.cold (STB_LOCAL)
ffffffff818ba860-ffffffff818ba8d0: efi_call_virt_check_flags (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
void efi_call_virt_check_flags(long unsigned int flags, const char *call);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/firmware/efi/runtime-wrappers.c (0)
Location: drivers/firmware/efi/runtime-wrappers.c:104
Inline: False
Direct callers:
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
```
**Symbols:**

```
ffffffff818ee2c2-ffffffff818ee2dc: efi_call_virt_check_flags.cold (STB_LOCAL)
ffffffff818ed300-ffffffff818ed370: efi_call_virt_check_flags (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
void efi_call_virt_check_flags(long unsigned int flags, const char *call);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/firmware/efi/runtime-wrappers.c (0)
Location: drivers/firmware/efi/runtime-wrappers.c:104
Inline: False
Direct callers:
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
ffffffff819c1d92-ffffffff819c1dac: efi_call_virt_check_flags.cold (STB_LOCAL)
ffffffff819c0d90-ffffffff819c0e00: efi_call_virt_check_flags (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
void efi_call_virt_check_flags(long unsigned int flags, const char *call);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/firmware/efi/runtime-wrappers.c (0)
Location: drivers/firmware/efi/runtime-wrappers.c:104
Inline: False
Direct callers:
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
```
**Symbols:**

```
ffffffff81c2cc0e-ffffffff81c2cc28: efi_call_virt_check_flags.cold (STB_LOCAL)
ffffffff819c1c20-ffffffff819c1c90: efi_call_virt_check_flags (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
void efi_call_virt_check_flags(long unsigned int flags, const char *call);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/firmware/efi/runtime-wrappers.c (0)
Location: drivers/firmware/efi/runtime-wrappers.c:104
Inline: False
Direct callers:
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
```
**Symbols:**

```
ffffffff81c1ee3c-ffffffff81c1ee56: efi_call_virt_check_flags.cold (STB_LOCAL)
ffffffff819a61c0-ffffffff819a622a: efi_call_virt_check_flags (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
void efi_call_virt_check_flags(long unsigned int flags, const char *call);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/firmware/efi/runtime-wrappers.c (0)
Location: drivers/firmware/efi/runtime-wrappers.c:104
Inline: False
Direct callers:
  - arch/x86/platform/uv/bios_uv.c:__uv_bios_call
  - drivers/acpi/prmt.c:acpi_platformrt_space_handler
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
ffffffff81d30421-ffffffff81d3043b: efi_call_virt_check_flags.cold (STB_LOCAL)
ffffffff81a53560-ffffffff81a535ca: efi_call_virt_check_flags (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
void efi_call_virt_check_flags(long unsigned int flags, const char *call);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/firmware/efi/runtime-wrappers.c (0)
Location: drivers/firmware/efi/runtime-wrappers.c:104
Inline: False
Direct callers:
  - arch/x86/platform/uv/bios_uv.c:__uv_bios_call
  - drivers/acpi/prmt.c:acpi_platformrt_space_handler
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
ffffffff81efc855-ffffffff81efc86f: efi_call_virt_check_flags.cold (STB_LOCAL)
ffffffff81bc2760-ffffffff81bc27d2: efi_call_virt_check_flags (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void efi_call_virt_check_flags(long unsigned int flags, const char *call);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/firmware/efi/runtime-wrappers.c (ffffffff81d67470)
Location: drivers/firmware/efi/runtime-wrappers.c:106
Inline: False
Direct callers:
  - arch/x86/platform/uv/bios_uv.c:__uv_bios_call
  - drivers/acpi/prmt.c:acpi_platformrt_space_handler
  - drivers/firmware/efi/runtime-wrappers.c:efi_call_rts
  - drivers/firmware/efi/runtime-wrappers.c:efi_call_rts
```
**Symbols:**

```
ffffffff81d67470-ffffffff81d674f5: efi_call_virt_check_flags (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void efi_call_virt_check_flags(long unsigned int flags, const char *call);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/firmware/efi/runtime-wrappers.c (ffffffff81dd2580)
Location: drivers/firmware/efi/runtime-wrappers.c:106
Inline: False
Direct callers:
  - arch/x86/platform/uv/bios_uv.c:__uv_bios_call
  - drivers/acpi/prmt.c:acpi_platformrt_space_handler
  - drivers/firmware/efi/runtime-wrappers.c:efi_call_rts
```
**Symbols:**

```
ffffffff81dd2580-ffffffff81dd2605: efi_call_virt_check_flags (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void efi_call_virt_check_flags(long unsigned int flags, const void *caller);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/firmware/efi/runtime-wrappers.c (ffffffff81e8abb0)
Location: drivers/firmware/efi/runtime-wrappers.c:148
Inline: False
Direct callers:
  - arch/x86/platform/uv/bios_uv.c:__uv_bios_call
  - drivers/firmware/efi/runtime-wrappers.c:efi_call_rts
```
**Symbols:**

```
ffffffff81e8abb0-ffffffff81e8ac3e: efi_call_virt_check_flags (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: ✅</summary>

```c
void efi_call_virt_check_flags(long unsigned int flags, const char *call);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/firmware/efi/runtime-wrappers.c (ffff800010b60658)
Location: drivers/firmware/efi/runtime-wrappers.c:104
Inline: False
Direct callers:
  - drivers/firmware/efi/runtime-wrappers.c:virt_efi_reset_system
  - drivers/firmware/efi/runtime-wrappers.c:efi_call_rts
  - drivers/firmware/efi/runtime-wrappers.c:efi_call_rts
  - drivers/firmware/efi/runtime-wrappers.c:efi_call_rts
  - drivers/firmware/efi/runtime-wrappers.c:efi_call_rts
  - drivers/firmware/efi/runtime-wrappers.c:efi_call_rts
  - drivers/firmware/efi/runtime-wrappers.c:efi_call_rts
```
**Symbols:**

```
ffff800010b60658-ffff800010b606f8: efi_call_virt_check_flags (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void efi_call_virt_check_flags(long unsigned int flags, const char *call);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/firmware/efi/runtime-wrappers.c (c0c3fb50)
Location: drivers/firmware/efi/runtime-wrappers.c:104
Inline: False
Direct callers:
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
c0c3fb50-c0c3fc08: efi_call_virt_check_flags (STB_GLOBAL)
```
</details>
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
<summary>In <code>aws</code>: Transformation ⚠️</summary>

```c
void efi_call_virt_check_flags(long unsigned int flags, const char *call);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/firmware/efi/runtime-wrappers.c (0)
Location: drivers/firmware/efi/runtime-wrappers.c:104
Inline: False
Direct callers:
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
ffffffff8188fea2-ffffffff8188febc: efi_call_virt_check_flags.cold (STB_LOCAL)
ffffffff8188eee0-ffffffff8188ef50: efi_call_virt_check_flags (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Transformation ⚠️</summary>

```c
void efi_call_virt_check_flags(long unsigned int flags, const char *call);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/firmware/efi/runtime-wrappers.c (0)
Location: drivers/firmware/efi/runtime-wrappers.c:104
Inline: False
Direct callers:
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
ffffffff81848952-ffffffff8184896c: efi_call_virt_check_flags.cold (STB_LOCAL)
ffffffff818479f0-ffffffff81847a4e: efi_call_virt_check_flags (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Transformation ⚠️</summary>

```c
void efi_call_virt_check_flags(long unsigned int flags, const char *call);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/firmware/efi/runtime-wrappers.c (0)
Location: drivers/firmware/efi/runtime-wrappers.c:104
Inline: False
Direct callers:
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
ffffffff818e3122-ffffffff818e313c: efi_call_virt_check_flags.cold (STB_LOCAL)
ffffffff818e2160-ffffffff818e21d0: efi_call_virt_check_flags (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
void efi_call_virt_check_flags(long unsigned int flags, const char *call);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/firmware/efi/runtime-wrappers.c (0)
Location: drivers/firmware/efi/runtime-wrappers.c:104
Inline: False
Direct callers:
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
```
**Symbols:**

```
ffffffff818ffd62-ffffffff818ffd7c: efi_call_virt_check_flags.cold (STB_LOCAL)
ffffffff818fec00-ffffffff818fec70: efi_call_virt_check_flags (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
<li>
No changes between <code>5.8</code> and <code>5.11</code> ✅
</li>
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
<code>const void *caller</code>
</li>
<li>
<b>Param removed. </b>
<code>const char *call</code>
</li>
</ul>
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
No changes between <code>amd64</code> and <code>arm64</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>armhf</code> ✅
</li>
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
