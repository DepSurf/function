# Function: <code>_bcd2bin</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
unsigned int _bcd2bin(unsigned char val);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/bcd.c (ffffffff813f7de0)
Location: lib/bcd.c:4
Inline: False
Direct callers:
  - arch/x86/kernel/rtc.c:mach_get_cmos_time
  - arch/x86/kernel/rtc.c:mach_get_cmos_time
  - arch/x86/kernel/rtc.c:mach_get_cmos_time
  - arch/x86/kernel/rtc.c:mach_get_cmos_time
  - arch/x86/kernel/rtc.c:mach_get_cmos_time
  - arch/x86/kernel/rtc.c:mach_get_cmos_time
  - arch/x86/kernel/rtc.c:mach_get_cmos_time
  - arch/x86/kernel/hpet.c:hpet_rtc_interrupt
  - arch/x86/kernel/hpet.c:hpet_rtc_interrupt
  - arch/x86/kernel/hpet.c:hpet_rtc_interrupt
  - arch/x86/kernel/hpet.c:hpet_rtc_interrupt
  - arch/x86/kernel/hpet.c:hpet_rtc_interrupt
  - arch/x86/kernel/hpet.c:hpet_rtc_interrupt
  - arch/x86/kernel/hpet.c:hpet_rtc_interrupt
  - drivers/base/power/trace.c:early_resume_init
  - drivers/base/power/trace.c:early_resume_init
  - drivers/base/power/trace.c:early_resume_init
  - drivers/base/power/trace.c:early_resume_init
  - drivers/base/power/trace.c:early_resume_init
  - drivers/base/power/trace.c:early_resume_init
  - drivers/base/power/trace.c:early_resume_init
  - drivers/rtc/rtc-cmos.c:cmos_aie_poweroff
  - drivers/rtc/rtc-cmos.c:cmos_aie_poweroff
  - drivers/rtc/rtc-cmos.c:cmos_aie_poweroff
  - drivers/rtc/rtc-cmos.c:cmos_aie_poweroff
  - drivers/rtc/rtc-cmos.c:cmos_aie_poweroff
  - drivers/rtc/rtc-cmos.c:cmos_aie_poweroff
  - drivers/rtc/rtc-cmos.c:cmos_aie_poweroff
  - drivers/rtc/rtc-cmos.c:cmos_read_alarm
  - drivers/rtc/rtc-cmos.c:cmos_read_alarm
  - drivers/rtc/rtc-cmos.c:cmos_read_alarm
  - drivers/rtc/rtc-cmos.c:cmos_read_alarm
  - drivers/rtc/rtc-cmos.c:cmos_read_alarm
```
**Symbols:**

```
ffffffff813f7de0-ffffffff813f7df7: _bcd2bin (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
unsigned int _bcd2bin(unsigned char val);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/bcd.c (ffffffff8143eca0)
Location: lib/bcd.c:4
Inline: False
Direct callers:
  - arch/x86/kernel/rtc.c:mach_get_cmos_time
  - arch/x86/kernel/rtc.c:mach_get_cmos_time
  - arch/x86/kernel/rtc.c:mach_get_cmos_time
  - arch/x86/kernel/rtc.c:mach_get_cmos_time
  - arch/x86/kernel/rtc.c:mach_get_cmos_time
  - arch/x86/kernel/rtc.c:mach_get_cmos_time
  - arch/x86/kernel/rtc.c:mach_get_cmos_time
  - drivers/rtc/rtc-mc146818-lib.c:mc146818_get_time
  - drivers/rtc/rtc-mc146818-lib.c:mc146818_get_time
  - drivers/rtc/rtc-mc146818-lib.c:mc146818_get_time
  - drivers/rtc/rtc-mc146818-lib.c:mc146818_get_time
  - drivers/rtc/rtc-mc146818-lib.c:mc146818_get_time
  - drivers/rtc/rtc-mc146818-lib.c:mc146818_get_time
  - drivers/rtc/rtc-mc146818-lib.c:mc146818_get_time
  - drivers/rtc/rtc-cmos.c:cmos_read_alarm
  - drivers/rtc/rtc-cmos.c:cmos_read_alarm
  - drivers/rtc/rtc-cmos.c:cmos_read_alarm
  - drivers/rtc/rtc-cmos.c:cmos_read_alarm
  - drivers/rtc/rtc-cmos.c:cmos_read_alarm
```
**Symbols:**

```
ffffffff8143eca0-ffffffff8143ecb7: _bcd2bin (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
unsigned int _bcd2bin(unsigned char val);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/bcd.c (ffffffff8145bcf0)
Location: lib/bcd.c:4
Inline: False
Direct callers:
  - arch/x86/kernel/rtc.c:mach_get_cmos_time
  - arch/x86/kernel/rtc.c:mach_get_cmos_time
  - arch/x86/kernel/rtc.c:mach_get_cmos_time
  - arch/x86/kernel/rtc.c:mach_get_cmos_time
  - arch/x86/kernel/rtc.c:mach_get_cmos_time
  - arch/x86/kernel/rtc.c:mach_get_cmos_time
  - arch/x86/kernel/rtc.c:mach_get_cmos_time
  - drivers/rtc/rtc-mc146818-lib.c:mc146818_get_time
  - drivers/rtc/rtc-mc146818-lib.c:mc146818_get_time
  - drivers/rtc/rtc-mc146818-lib.c:mc146818_get_time
  - drivers/rtc/rtc-mc146818-lib.c:mc146818_get_time
  - drivers/rtc/rtc-mc146818-lib.c:mc146818_get_time
  - drivers/rtc/rtc-mc146818-lib.c:mc146818_get_time
  - drivers/rtc/rtc-mc146818-lib.c:mc146818_get_time
  - drivers/rtc/rtc-cmos.c:cmos_read_alarm
  - drivers/rtc/rtc-cmos.c:cmos_read_alarm
  - drivers/rtc/rtc-cmos.c:cmos_read_alarm
  - drivers/rtc/rtc-cmos.c:cmos_read_alarm
  - drivers/rtc/rtc-cmos.c:cmos_read_alarm
```
**Symbols:**

```
ffffffff8145bcf0-ffffffff8145bd07: _bcd2bin (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
unsigned int _bcd2bin(unsigned char val);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/bcd.c (ffffffff814611d0)
Location: lib/bcd.c:4
Inline: False
Direct callers:
  - arch/x86/kernel/rtc.c:mach_get_cmos_time
  - arch/x86/kernel/rtc.c:mach_get_cmos_time
  - arch/x86/kernel/rtc.c:mach_get_cmos_time
  - arch/x86/kernel/rtc.c:mach_get_cmos_time
  - arch/x86/kernel/rtc.c:mach_get_cmos_time
  - arch/x86/kernel/rtc.c:mach_get_cmos_time
  - arch/x86/kernel/rtc.c:mach_get_cmos_time
  - drivers/rtc/rtc-mc146818-lib.c:mc146818_get_time
  - drivers/rtc/rtc-mc146818-lib.c:mc146818_get_time
  - drivers/rtc/rtc-mc146818-lib.c:mc146818_get_time
  - drivers/rtc/rtc-mc146818-lib.c:mc146818_get_time
  - drivers/rtc/rtc-mc146818-lib.c:mc146818_get_time
  - drivers/rtc/rtc-mc146818-lib.c:mc146818_get_time
  - drivers/rtc/rtc-mc146818-lib.c:mc146818_get_time
  - drivers/rtc/rtc-cmos.c:cmos_read_alarm
  - drivers/rtc/rtc-cmos.c:cmos_read_alarm
  - drivers/rtc/rtc-cmos.c:cmos_read_alarm
  - drivers/rtc/rtc-cmos.c:cmos_read_alarm
  - drivers/rtc/rtc-cmos.c:cmos_read_alarm
  - drivers/firmware/efi/cper.c:cper_estatus_print_section
  - drivers/firmware/efi/cper.c:cper_estatus_print_section
  - drivers/firmware/efi/cper.c:cper_estatus_print_section
  - drivers/firmware/efi/cper.c:cper_estatus_print_section
  - drivers/firmware/efi/cper.c:cper_estatus_print_section
  - drivers/firmware/efi/cper.c:cper_estatus_print_section
  - drivers/firmware/efi/cper.c:cper_estatus_print_section
```
**Symbols:**

```
ffffffff814611d0-ffffffff814611e7: _bcd2bin (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
unsigned int _bcd2bin(unsigned char val);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/bcd.c (ffffffff8148d0a0)
Location: lib/bcd.c:5
Inline: False
Direct callers:
  - arch/x86/kernel/rtc.c:mach_get_cmos_time
  - arch/x86/kernel/rtc.c:mach_get_cmos_time
  - arch/x86/kernel/rtc.c:mach_get_cmos_time
  - arch/x86/kernel/rtc.c:mach_get_cmos_time
  - arch/x86/kernel/rtc.c:mach_get_cmos_time
  - arch/x86/kernel/rtc.c:mach_get_cmos_time
  - arch/x86/kernel/rtc.c:mach_get_cmos_time
  - drivers/rtc/rtc-mc146818-lib.c:mc146818_get_time
  - drivers/rtc/rtc-mc146818-lib.c:mc146818_get_time
  - drivers/rtc/rtc-mc146818-lib.c:mc146818_get_time
  - drivers/rtc/rtc-mc146818-lib.c:mc146818_get_time
  - drivers/rtc/rtc-mc146818-lib.c:mc146818_get_time
  - drivers/rtc/rtc-mc146818-lib.c:mc146818_get_time
  - drivers/rtc/rtc-mc146818-lib.c:mc146818_get_time
  - drivers/rtc/rtc-cmos.c:cmos_read_alarm
  - drivers/rtc/rtc-cmos.c:cmos_read_alarm
  - drivers/rtc/rtc-cmos.c:cmos_read_alarm
  - drivers/rtc/rtc-cmos.c:cmos_read_alarm
  - drivers/rtc/rtc-cmos.c:cmos_read_alarm
  - drivers/firmware/efi/cper.c:cper_estatus_print_section
  - drivers/firmware/efi/cper.c:cper_estatus_print_section
  - drivers/firmware/efi/cper.c:cper_estatus_print_section
  - drivers/firmware/efi/cper.c:cper_estatus_print_section
  - drivers/firmware/efi/cper.c:cper_estatus_print_section
  - drivers/firmware/efi/cper.c:cper_estatus_print_section
  - drivers/firmware/efi/cper.c:cper_estatus_print_section
```
**Symbols:**

```
ffffffff8148d0a0-ffffffff8148d0b7: _bcd2bin (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
unsigned int _bcd2bin(unsigned char val);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/bcd.c (ffffffff814c1e20)
Location: lib/bcd.c:5
Inline: False
Direct callers:
  - arch/x86/kernel/rtc.c:mach_get_cmos_time
  - arch/x86/kernel/rtc.c:mach_get_cmos_time
  - arch/x86/kernel/rtc.c:mach_get_cmos_time
  - arch/x86/kernel/rtc.c:mach_get_cmos_time
  - arch/x86/kernel/rtc.c:mach_get_cmos_time
  - arch/x86/kernel/rtc.c:mach_get_cmos_time
  - arch/x86/kernel/rtc.c:mach_get_cmos_time
  - drivers/rtc/rtc-mc146818-lib.c:mc146818_get_time
  - drivers/rtc/rtc-mc146818-lib.c:mc146818_get_time
  - drivers/rtc/rtc-mc146818-lib.c:mc146818_get_time
  - drivers/rtc/rtc-mc146818-lib.c:mc146818_get_time
  - drivers/rtc/rtc-mc146818-lib.c:mc146818_get_time
  - drivers/rtc/rtc-mc146818-lib.c:mc146818_get_time
  - drivers/rtc/rtc-mc146818-lib.c:mc146818_get_time
  - drivers/rtc/rtc-cmos.c:cmos_read_alarm
  - drivers/rtc/rtc-cmos.c:cmos_read_alarm
  - drivers/rtc/rtc-cmos.c:cmos_read_alarm
  - drivers/rtc/rtc-cmos.c:cmos_read_alarm
  - drivers/rtc/rtc-cmos.c:cmos_read_alarm
  - drivers/firmware/efi/cper.c:cper_estatus_print_section
  - drivers/firmware/efi/cper.c:cper_estatus_print_section
  - drivers/firmware/efi/cper.c:cper_estatus_print_section
  - drivers/firmware/efi/cper.c:cper_estatus_print_section
  - drivers/firmware/efi/cper.c:cper_estatus_print_section
  - drivers/firmware/efi/cper.c:cper_estatus_print_section
  - drivers/firmware/efi/cper.c:cper_estatus_print_section
```
**Symbols:**

```
ffffffff814c1e20-ffffffff814c1e32: _bcd2bin (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
unsigned int _bcd2bin(unsigned char val);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/bcd.c (ffffffff814d6510)
Location: lib/bcd.c:5
Inline: False
Direct callers:
  - arch/x86/kernel/rtc.c:mach_get_cmos_time
  - arch/x86/kernel/rtc.c:mach_get_cmos_time
  - arch/x86/kernel/rtc.c:mach_get_cmos_time
  - arch/x86/kernel/rtc.c:mach_get_cmos_time
  - arch/x86/kernel/rtc.c:mach_get_cmos_time
  - arch/x86/kernel/rtc.c:mach_get_cmos_time
  - arch/x86/kernel/rtc.c:mach_get_cmos_time
  - drivers/rtc/rtc-mc146818-lib.c:mc146818_get_time
  - drivers/rtc/rtc-mc146818-lib.c:mc146818_get_time
  - drivers/rtc/rtc-mc146818-lib.c:mc146818_get_time
  - drivers/rtc/rtc-mc146818-lib.c:mc146818_get_time
  - drivers/rtc/rtc-mc146818-lib.c:mc146818_get_time
  - drivers/rtc/rtc-mc146818-lib.c:mc146818_get_time
  - drivers/rtc/rtc-mc146818-lib.c:mc146818_get_time
  - drivers/rtc/rtc-cmos.c:cmos_read_alarm
  - drivers/rtc/rtc-cmos.c:cmos_read_alarm
  - drivers/rtc/rtc-cmos.c:cmos_read_alarm
  - drivers/rtc/rtc-cmos.c:cmos_read_alarm
  - drivers/rtc/rtc-cmos.c:cmos_read_alarm
  - drivers/firmware/efi/cper.c:cper_estatus_print_section
  - drivers/firmware/efi/cper.c:cper_estatus_print_section
  - drivers/firmware/efi/cper.c:cper_estatus_print_section
  - drivers/firmware/efi/cper.c:cper_estatus_print_section
  - drivers/firmware/efi/cper.c:cper_estatus_print_section
  - drivers/firmware/efi/cper.c:cper_estatus_print_section
  - drivers/firmware/efi/cper.c:cper_estatus_print_section
```
**Symbols:**

```
ffffffff814d6510-ffffffff814d6522: _bcd2bin (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
unsigned int _bcd2bin(unsigned char val);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/bcd.c (ffffffff815023c0)
Location: lib/bcd.c:5
Inline: False
Direct callers:
  - arch/x86/kernel/rtc.c:mach_get_cmos_time
  - arch/x86/kernel/rtc.c:mach_get_cmos_time
  - arch/x86/kernel/rtc.c:mach_get_cmos_time
  - arch/x86/kernel/rtc.c:mach_get_cmos_time
  - arch/x86/kernel/rtc.c:mach_get_cmos_time
  - arch/x86/kernel/rtc.c:mach_get_cmos_time
  - arch/x86/kernel/rtc.c:mach_get_cmos_time
  - drivers/rtc/rtc-mc146818-lib.c:mc146818_get_time
  - drivers/rtc/rtc-mc146818-lib.c:mc146818_get_time
  - drivers/rtc/rtc-mc146818-lib.c:mc146818_get_time
  - drivers/rtc/rtc-mc146818-lib.c:mc146818_get_time
  - drivers/rtc/rtc-mc146818-lib.c:mc146818_get_time
  - drivers/rtc/rtc-mc146818-lib.c:mc146818_get_time
  - drivers/rtc/rtc-mc146818-lib.c:mc146818_get_time
  - drivers/rtc/rtc-cmos.c:cmos_read_alarm
  - drivers/rtc/rtc-cmos.c:cmos_read_alarm
  - drivers/rtc/rtc-cmos.c:cmos_read_alarm
  - drivers/rtc/rtc-cmos.c:cmos_read_alarm
  - drivers/rtc/rtc-cmos.c:cmos_read_alarm
  - drivers/firmware/efi/cper.c:cper_estatus_print_section
  - drivers/firmware/efi/cper.c:cper_estatus_print_section
  - drivers/firmware/efi/cper.c:cper_estatus_print_section
  - drivers/firmware/efi/cper.c:cper_estatus_print_section
  - drivers/firmware/efi/cper.c:cper_estatus_print_section
  - drivers/firmware/efi/cper.c:cper_estatus_print_section
  - drivers/firmware/efi/cper.c:cper_estatus_print_section
```
**Symbols:**

```
ffffffff815023c0-ffffffff815023d2: _bcd2bin (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
unsigned int _bcd2bin(unsigned char val);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/bcd.c (ffffffff815202d0)
Location: lib/bcd.c:5
Inline: False
Direct callers:
  - arch/x86/kernel/rtc.c:mach_get_cmos_time
  - arch/x86/kernel/rtc.c:mach_get_cmos_time
  - arch/x86/kernel/rtc.c:mach_get_cmos_time
  - arch/x86/kernel/rtc.c:mach_get_cmos_time
  - arch/x86/kernel/rtc.c:mach_get_cmos_time
  - arch/x86/kernel/rtc.c:mach_get_cmos_time
  - arch/x86/kernel/rtc.c:mach_get_cmos_time
  - drivers/rtc/rtc-mc146818-lib.c:mc146818_get_time
  - drivers/rtc/rtc-mc146818-lib.c:mc146818_get_time
  - drivers/rtc/rtc-mc146818-lib.c:mc146818_get_time
  - drivers/rtc/rtc-mc146818-lib.c:mc146818_get_time
  - drivers/rtc/rtc-mc146818-lib.c:mc146818_get_time
  - drivers/rtc/rtc-mc146818-lib.c:mc146818_get_time
  - drivers/rtc/rtc-mc146818-lib.c:mc146818_get_time
  - drivers/rtc/rtc-cmos.c:cmos_read_alarm
  - drivers/rtc/rtc-cmos.c:cmos_read_alarm
  - drivers/rtc/rtc-cmos.c:cmos_read_alarm
  - drivers/rtc/rtc-cmos.c:cmos_read_alarm
  - drivers/rtc/rtc-cmos.c:cmos_read_alarm
  - drivers/firmware/efi/cper.c:cper_estatus_print_section
  - drivers/firmware/efi/cper.c:cper_estatus_print_section
  - drivers/firmware/efi/cper.c:cper_estatus_print_section
  - drivers/firmware/efi/cper.c:cper_estatus_print_section
  - drivers/firmware/efi/cper.c:cper_estatus_print_section
  - drivers/firmware/efi/cper.c:cper_estatus_print_section
  - drivers/firmware/efi/cper.c:cper_estatus_print_section
```
**Symbols:**

```
ffffffff815202d0-ffffffff815202e2: _bcd2bin (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
unsigned int _bcd2bin(unsigned char val);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/bcd.c (ffffffff81583480)
Location: lib/bcd.c:5
Inline: False
Direct callers:
  - arch/x86/kernel/rtc.c:mach_get_cmos_time
  - arch/x86/kernel/rtc.c:mach_get_cmos_time
  - arch/x86/kernel/rtc.c:mach_get_cmos_time
  - arch/x86/kernel/rtc.c:mach_get_cmos_time
  - arch/x86/kernel/rtc.c:mach_get_cmos_time
  - arch/x86/kernel/rtc.c:mach_get_cmos_time
  - arch/x86/kernel/rtc.c:mach_get_cmos_time
  - drivers/scsi/sr_vendor.c:sr_cd_check
  - drivers/scsi/sr_vendor.c:sr_cd_check
  - drivers/scsi/sr_vendor.c:sr_cd_check
  - drivers/scsi/sr_vendor.c:sr_cd_check
  - drivers/scsi/sr_vendor.c:sr_cd_check
  - drivers/scsi/sr_vendor.c:sr_cd_check
  - drivers/rtc/rtc-mc146818-lib.c:mc146818_get_time
  - drivers/rtc/rtc-mc146818-lib.c:mc146818_get_time
  - drivers/rtc/rtc-mc146818-lib.c:mc146818_get_time
  - drivers/rtc/rtc-mc146818-lib.c:mc146818_get_time
  - drivers/rtc/rtc-mc146818-lib.c:mc146818_get_time
  - drivers/rtc/rtc-mc146818-lib.c:mc146818_get_time
  - drivers/rtc/rtc-mc146818-lib.c:mc146818_get_time
  - drivers/rtc/rtc-cmos.c:cmos_read_alarm
  - drivers/rtc/rtc-cmos.c:cmos_read_alarm
  - drivers/rtc/rtc-cmos.c:cmos_read_alarm
  - drivers/rtc/rtc-cmos.c:cmos_read_alarm
  - drivers/rtc/rtc-cmos.c:cmos_read_alarm
  - drivers/firmware/efi/cper.c:cper_estatus_print_section
  - drivers/firmware/efi/cper.c:cper_estatus_print_section
  - drivers/firmware/efi/cper.c:cper_estatus_print_section
  - drivers/firmware/efi/cper.c:cper_estatus_print_section
  - drivers/firmware/efi/cper.c:cper_estatus_print_section
  - drivers/firmware/efi/cper.c:cper_estatus_print_section
  - drivers/firmware/efi/cper.c:cper_estatus_print_section
```
**Symbols:**

```
ffffffff81583480-ffffffff81583492: _bcd2bin (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
unsigned int _bcd2bin(unsigned char val);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/bcd.c (ffffffff815a0300)
Location: lib/bcd.c:5
Inline: False
Direct callers:
  - arch/x86/kernel/rtc.c:mach_get_cmos_time
  - arch/x86/kernel/rtc.c:mach_get_cmos_time
  - arch/x86/kernel/rtc.c:mach_get_cmos_time
  - arch/x86/kernel/rtc.c:mach_get_cmos_time
  - arch/x86/kernel/rtc.c:mach_get_cmos_time
  - arch/x86/kernel/rtc.c:mach_get_cmos_time
  - arch/x86/kernel/rtc.c:mach_get_cmos_time
  - drivers/scsi/sr_vendor.c:sr_cd_check
  - drivers/scsi/sr_vendor.c:sr_cd_check
  - drivers/scsi/sr_vendor.c:sr_cd_check
  - drivers/scsi/sr_vendor.c:sr_cd_check
  - drivers/scsi/sr_vendor.c:sr_cd_check
  - drivers/scsi/sr_vendor.c:sr_cd_check
  - drivers/rtc/rtc-mc146818-lib.c:mc146818_get_time
  - drivers/rtc/rtc-mc146818-lib.c:mc146818_get_time
  - drivers/rtc/rtc-mc146818-lib.c:mc146818_get_time
  - drivers/rtc/rtc-mc146818-lib.c:mc146818_get_time
  - drivers/rtc/rtc-mc146818-lib.c:mc146818_get_time
  - drivers/rtc/rtc-mc146818-lib.c:mc146818_get_time
  - drivers/rtc/rtc-mc146818-lib.c:mc146818_get_time
  - drivers/rtc/rtc-cmos.c:cmos_read_alarm
  - drivers/rtc/rtc-cmos.c:cmos_read_alarm
  - drivers/rtc/rtc-cmos.c:cmos_read_alarm
  - drivers/rtc/rtc-cmos.c:cmos_read_alarm
  - drivers/rtc/rtc-cmos.c:cmos_read_alarm
  - drivers/firmware/efi/cper.c:cper_estatus_print_section
  - drivers/firmware/efi/cper.c:cper_estatus_print_section
  - drivers/firmware/efi/cper.c:cper_estatus_print_section
  - drivers/firmware/efi/cper.c:cper_estatus_print_section
  - drivers/firmware/efi/cper.c:cper_estatus_print_section
  - drivers/firmware/efi/cper.c:cper_estatus_print_section
  - drivers/firmware/efi/cper.c:cper_estatus_print_section
```
**Symbols:**

```
ffffffff815a0300-ffffffff815a0312: _bcd2bin (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
unsigned int _bcd2bin(unsigned char val);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/bcd.c (ffffffff815a70f0)
Location: lib/bcd.c:5
Inline: False
Direct callers:
  - arch/x86/kernel/rtc.c:mach_get_cmos_time
  - arch/x86/kernel/rtc.c:mach_get_cmos_time
  - arch/x86/kernel/rtc.c:mach_get_cmos_time
  - arch/x86/kernel/rtc.c:mach_get_cmos_time
  - arch/x86/kernel/rtc.c:mach_get_cmos_time
  - arch/x86/kernel/rtc.c:mach_get_cmos_time
  - arch/x86/kernel/rtc.c:mach_get_cmos_time
  - drivers/scsi/sr_vendor.c:sr_cd_check
  - drivers/scsi/sr_vendor.c:sr_cd_check
  - drivers/scsi/sr_vendor.c:sr_cd_check
  - drivers/scsi/sr_vendor.c:sr_cd_check
  - drivers/scsi/sr_vendor.c:sr_cd_check
  - drivers/scsi/sr_vendor.c:sr_cd_check
  - drivers/rtc/rtc-mc146818-lib.c:mc146818_get_time
  - drivers/rtc/rtc-mc146818-lib.c:mc146818_get_time
  - drivers/rtc/rtc-mc146818-lib.c:mc146818_get_time
  - drivers/rtc/rtc-mc146818-lib.c:mc146818_get_time
  - drivers/rtc/rtc-mc146818-lib.c:mc146818_get_time
  - drivers/rtc/rtc-mc146818-lib.c:mc146818_get_time
  - drivers/rtc/rtc-mc146818-lib.c:mc146818_get_time
  - drivers/rtc/rtc-cmos.c:cmos_read_alarm
  - drivers/rtc/rtc-cmos.c:cmos_read_alarm
  - drivers/rtc/rtc-cmos.c:cmos_read_alarm
  - drivers/rtc/rtc-cmos.c:cmos_read_alarm
  - drivers/rtc/rtc-cmos.c:cmos_read_alarm
  - drivers/firmware/efi/cper.c:cper_estatus_print_section
  - drivers/firmware/efi/cper.c:cper_estatus_print_section
  - drivers/firmware/efi/cper.c:cper_estatus_print_section
  - drivers/firmware/efi/cper.c:cper_estatus_print_section
  - drivers/firmware/efi/cper.c:cper_estatus_print_section
  - drivers/firmware/efi/cper.c:cper_estatus_print_section
  - drivers/firmware/efi/cper.c:cper_estatus_print_section
```
**Symbols:**

```
ffffffff815a70f0-ffffffff815a7102: _bcd2bin (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
unsigned int _bcd2bin(unsigned char val);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/bcd.c (ffffffff81610030)
Location: lib/bcd.c:5
Inline: False
Direct callers:
  - arch/x86/kernel/rtc.c:mach_get_cmos_time
  - arch/x86/kernel/rtc.c:mach_get_cmos_time
  - arch/x86/kernel/rtc.c:mach_get_cmos_time
  - arch/x86/kernel/rtc.c:mach_get_cmos_time
  - arch/x86/kernel/rtc.c:mach_get_cmos_time
  - arch/x86/kernel/rtc.c:mach_get_cmos_time
  - arch/x86/kernel/rtc.c:mach_get_cmos_time
  - drivers/scsi/sr_vendor.c:sr_cd_check
  - drivers/scsi/sr_vendor.c:sr_cd_check
  - drivers/scsi/sr_vendor.c:sr_cd_check
  - drivers/scsi/sr_vendor.c:sr_cd_check
  - drivers/scsi/sr_vendor.c:sr_cd_check
  - drivers/scsi/sr_vendor.c:sr_cd_check
  - drivers/rtc/rtc-mc146818-lib.c:mc146818_get_time
  - drivers/rtc/rtc-mc146818-lib.c:mc146818_get_time
  - drivers/rtc/rtc-mc146818-lib.c:mc146818_get_time
  - drivers/rtc/rtc-mc146818-lib.c:mc146818_get_time
  - drivers/rtc/rtc-mc146818-lib.c:mc146818_get_time
  - drivers/rtc/rtc-mc146818-lib.c:mc146818_get_time
  - drivers/rtc/rtc-mc146818-lib.c:mc146818_get_time
  - drivers/rtc/rtc-cmos.c:cmos_read_alarm
  - drivers/rtc/rtc-cmos.c:cmos_read_alarm
  - drivers/rtc/rtc-cmos.c:cmos_read_alarm
  - drivers/rtc/rtc-cmos.c:cmos_read_alarm
  - drivers/rtc/rtc-cmos.c:cmos_read_alarm
  - drivers/firmware/efi/cper.c:cper_estatus_print_section
  - drivers/firmware/efi/cper.c:cper_estatus_print_section
  - drivers/firmware/efi/cper.c:cper_estatus_print_section
  - drivers/firmware/efi/cper.c:cper_estatus_print_section
  - drivers/firmware/efi/cper.c:cper_estatus_print_section
  - drivers/firmware/efi/cper.c:cper_estatus_print_section
  - drivers/firmware/efi/cper.c:cper_estatus_print_section
```
**Symbols:**

```
ffffffff81610030-ffffffff81610042: _bcd2bin (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
unsigned int _bcd2bin(unsigned char val);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/bcd.c (ffffffff816dc390)
Location: lib/bcd.c:5
Inline: False
Direct callers:
  - arch/x86/kernel/rtc.c:mach_get_cmos_time
  - arch/x86/kernel/rtc.c:mach_get_cmos_time
  - arch/x86/kernel/rtc.c:mach_get_cmos_time
  - arch/x86/kernel/rtc.c:mach_get_cmos_time
  - arch/x86/kernel/rtc.c:mach_get_cmos_time
  - arch/x86/kernel/rtc.c:mach_get_cmos_time
  - arch/x86/kernel/rtc.c:mach_get_cmos_time
  - drivers/scsi/sr_vendor.c:sr_cd_check
  - drivers/scsi/sr_vendor.c:sr_cd_check
  - drivers/scsi/sr_vendor.c:sr_cd_check
  - drivers/scsi/sr_vendor.c:sr_cd_check
  - drivers/scsi/sr_vendor.c:sr_cd_check
  - drivers/scsi/sr_vendor.c:sr_cd_check
  - drivers/rtc/rtc-mc146818-lib.c:mc146818_get_time
  - drivers/rtc/rtc-mc146818-lib.c:mc146818_get_time
  - drivers/rtc/rtc-mc146818-lib.c:mc146818_get_time
  - drivers/rtc/rtc-mc146818-lib.c:mc146818_get_time
  - drivers/rtc/rtc-mc146818-lib.c:mc146818_get_time
  - drivers/rtc/rtc-mc146818-lib.c:mc146818_get_time
  - drivers/rtc/rtc-mc146818-lib.c:mc146818_get_time
  - drivers/rtc/rtc-cmos.c:cmos_read_alarm
  - drivers/rtc/rtc-cmos.c:cmos_read_alarm
  - drivers/rtc/rtc-cmos.c:cmos_read_alarm
  - drivers/rtc/rtc-cmos.c:cmos_read_alarm
  - drivers/rtc/rtc-cmos.c:cmos_read_alarm
  - drivers/firmware/efi/cper.c:cper_estatus_print_section
  - drivers/firmware/efi/cper.c:cper_estatus_print_section
  - drivers/firmware/efi/cper.c:cper_estatus_print_section
  - drivers/firmware/efi/cper.c:cper_estatus_print_section
  - drivers/firmware/efi/cper.c:cper_estatus_print_section
  - drivers/firmware/efi/cper.c:cper_estatus_print_section
  - drivers/firmware/efi/cper.c:cper_estatus_print_section
```
**Symbols:**

```
ffffffff816dc390-ffffffff816dc3a8: _bcd2bin (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
unsigned int _bcd2bin(unsigned char val);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/bcd.c (ffffffff817cc070)
Location: lib/bcd.c:5
Inline: False
Direct callers:
  - drivers/scsi/sr_vendor.c:sr_cd_check
  - drivers/scsi/sr_vendor.c:sr_cd_check
  - drivers/scsi/sr_vendor.c:sr_cd_check
  - drivers/scsi/sr_vendor.c:sr_cd_check
  - drivers/scsi/sr_vendor.c:sr_cd_check
  - drivers/scsi/sr_vendor.c:sr_cd_check
  - drivers/rtc/rtc-mc146818-lib.c:mc146818_get_time
  - drivers/rtc/rtc-mc146818-lib.c:mc146818_get_time
  - drivers/rtc/rtc-mc146818-lib.c:mc146818_get_time
  - drivers/rtc/rtc-mc146818-lib.c:mc146818_get_time
  - drivers/rtc/rtc-mc146818-lib.c:mc146818_get_time
  - drivers/rtc/rtc-mc146818-lib.c:mc146818_get_time
  - drivers/rtc/rtc-mc146818-lib.c:mc146818_get_time
  - drivers/rtc/rtc-cmos.c:cmos_read_alarm
  - drivers/rtc/rtc-cmos.c:cmos_read_alarm
  - drivers/rtc/rtc-cmos.c:cmos_read_alarm
  - drivers/rtc/rtc-cmos.c:cmos_read_alarm
  - drivers/rtc/rtc-cmos.c:cmos_read_alarm
  - drivers/firmware/efi/cper.c:cper_estatus_print_section
  - drivers/firmware/efi/cper.c:cper_estatus_print_section
  - drivers/firmware/efi/cper.c:cper_estatus_print_section
  - drivers/firmware/efi/cper.c:cper_estatus_print_section
  - drivers/firmware/efi/cper.c:cper_estatus_print_section
  - drivers/firmware/efi/cper.c:cper_estatus_print_section
  - drivers/firmware/efi/cper.c:cper_estatus_print_section
```
**Symbols:**

```
ffffffff817cc070-ffffffff817cc088: _bcd2bin (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
unsigned int _bcd2bin(unsigned char val);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/bcd.c (ffffffff8180a4b0)
Location: lib/bcd.c:5
Inline: False
Direct callers:
  - drivers/scsi/sr_vendor.c:sr_cd_check
  - drivers/scsi/sr_vendor.c:sr_cd_check
  - drivers/scsi/sr_vendor.c:sr_cd_check
  - drivers/scsi/sr_vendor.c:sr_cd_check
  - drivers/scsi/sr_vendor.c:sr_cd_check
  - drivers/scsi/sr_vendor.c:sr_cd_check
  - drivers/rtc/rtc-mc146818-lib.c:mc146818_get_time
  - drivers/rtc/rtc-mc146818-lib.c:mc146818_get_time
  - drivers/rtc/rtc-mc146818-lib.c:mc146818_get_time
  - drivers/rtc/rtc-mc146818-lib.c:mc146818_get_time
  - drivers/rtc/rtc-mc146818-lib.c:mc146818_get_time
  - drivers/rtc/rtc-mc146818-lib.c:mc146818_get_time
  - drivers/rtc/rtc-mc146818-lib.c:mc146818_get_time
  - drivers/rtc/rtc-cmos.c:cmos_read_alarm
  - drivers/rtc/rtc-cmos.c:cmos_read_alarm
  - drivers/rtc/rtc-cmos.c:cmos_read_alarm
  - drivers/rtc/rtc-cmos.c:cmos_read_alarm
  - drivers/rtc/rtc-cmos.c:cmos_read_alarm
  - drivers/firmware/efi/cper.c:cper_estatus_print_section
  - drivers/firmware/efi/cper.c:cper_estatus_print_section
  - drivers/firmware/efi/cper.c:cper_estatus_print_section
  - drivers/firmware/efi/cper.c:cper_estatus_print_section
  - drivers/firmware/efi/cper.c:cper_estatus_print_section
  - drivers/firmware/efi/cper.c:cper_estatus_print_section
  - drivers/firmware/efi/cper.c:cper_estatus_print_section
```
**Symbols:**

```
ffffffff8180a4b0-ffffffff8180a4c8: _bcd2bin (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
unsigned int _bcd2bin(unsigned char val);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/bcd.c (ffffffff81850c90)
Location: lib/bcd.c:5
Inline: False
Direct callers:
  - drivers/scsi/sr_vendor.c:sr_cd_check
  - drivers/scsi/sr_vendor.c:sr_cd_check
  - drivers/scsi/sr_vendor.c:sr_cd_check
  - drivers/scsi/sr_vendor.c:sr_cd_check
  - drivers/scsi/sr_vendor.c:sr_cd_check
  - drivers/scsi/sr_vendor.c:sr_cd_check
  - drivers/rtc/rtc-mc146818-lib.c:mc146818_get_time
  - drivers/rtc/rtc-mc146818-lib.c:mc146818_get_time
  - drivers/rtc/rtc-mc146818-lib.c:mc146818_get_time
  - drivers/rtc/rtc-mc146818-lib.c:mc146818_get_time
  - drivers/rtc/rtc-mc146818-lib.c:mc146818_get_time
  - drivers/rtc/rtc-mc146818-lib.c:mc146818_get_time
  - drivers/rtc/rtc-mc146818-lib.c:mc146818_get_time
  - drivers/rtc/rtc-cmos.c:cmos_read_alarm
  - drivers/rtc/rtc-cmos.c:cmos_read_alarm
  - drivers/rtc/rtc-cmos.c:cmos_read_alarm
  - drivers/rtc/rtc-cmos.c:cmos_read_alarm
  - drivers/rtc/rtc-cmos.c:cmos_read_alarm
  - drivers/firmware/efi/cper.c:cper_estatus_print_section
  - drivers/firmware/efi/cper.c:cper_estatus_print_section
  - drivers/firmware/efi/cper.c:cper_estatus_print_section
  - drivers/firmware/efi/cper.c:cper_estatus_print_section
  - drivers/firmware/efi/cper.c:cper_estatus_print_section
  - drivers/firmware/efi/cper.c:cper_estatus_print_section
  - drivers/firmware/efi/cper.c:cper_estatus_print_section
```
**Symbols:**

```
ffffffff81850c90-ffffffff81850ca8: _bcd2bin (STB_GLOBAL)
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
unsigned int _bcd2bin(unsigned char val);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/bcd.c (ffff8000106297e0)
Location: lib/bcd.c:5
Inline: False
Direct callers:
  - drivers/rtc/rtc-mv.c:mv_rtc_read_alarm
  - drivers/rtc/rtc-mv.c:mv_rtc_read_alarm
  - drivers/rtc/rtc-mv.c:mv_rtc_read_alarm
  - drivers/rtc/rtc-mv.c:mv_rtc_read_alarm
  - drivers/rtc/rtc-mv.c:mv_rtc_read_alarm
  - drivers/rtc/rtc-mv.c:mv_rtc_read_alarm
  - drivers/rtc/rtc-mv.c:mv_rtc_read_alarm
  - drivers/rtc/rtc-mv.c:mv_rtc_read_time
  - drivers/rtc/rtc-mv.c:mv_rtc_read_time
  - drivers/rtc/rtc-mv.c:mv_rtc_read_time
  - drivers/rtc/rtc-mv.c:mv_rtc_read_time
  - drivers/rtc/rtc-mv.c:mv_rtc_read_time
  - drivers/rtc/rtc-mv.c:mv_rtc_read_time
  - drivers/rtc/rtc-mv.c:mv_rtc_read_time
  - drivers/firmware/efi/cper.c:cper_estatus_print_section
  - drivers/firmware/efi/cper.c:cper_estatus_print_section
  - drivers/firmware/efi/cper.c:cper_estatus_print_section
  - drivers/firmware/efi/cper.c:cper_estatus_print_section
  - drivers/firmware/efi/cper.c:cper_estatus_print_section
  - drivers/firmware/efi/cper.c:cper_estatus_print_section
  - drivers/firmware/efi/cper.c:cper_estatus_print_section
```
**Symbols:**

```
ffff8000106297e0-ffff8000106297f4: _bcd2bin (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
unsigned int _bcd2bin(unsigned char val);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/bcd.c (c07d0a30)
Location: lib/bcd.c:5
Inline: False
Direct callers:
  - drivers/rtc/rtc-mc146818-lib.c:mc146818_get_time
  - drivers/rtc/rtc-mc146818-lib.c:mc146818_get_time
  - drivers/rtc/rtc-mc146818-lib.c:mc146818_get_time
  - drivers/rtc/rtc-mc146818-lib.c:mc146818_get_time
  - drivers/rtc/rtc-mc146818-lib.c:mc146818_get_time
  - drivers/rtc/rtc-mc146818-lib.c:mc146818_get_time
  - drivers/rtc/rtc-mv.c:mv_rtc_read_alarm
  - drivers/rtc/rtc-mv.c:mv_rtc_read_alarm
  - drivers/rtc/rtc-mv.c:mv_rtc_read_alarm
  - drivers/rtc/rtc-mv.c:mv_rtc_read_alarm
  - drivers/rtc/rtc-mv.c:mv_rtc_read_alarm
  - drivers/rtc/rtc-mv.c:mv_rtc_read_alarm
  - drivers/rtc/rtc-mv.c:mv_rtc_read_alarm
  - drivers/rtc/rtc-mv.c:mv_rtc_read_time
  - drivers/rtc/rtc-mv.c:mv_rtc_read_time
  - drivers/rtc/rtc-mv.c:mv_rtc_read_time
  - drivers/rtc/rtc-mv.c:mv_rtc_read_time
  - drivers/rtc/rtc-mv.c:mv_rtc_read_time
  - drivers/rtc/rtc-mv.c:mv_rtc_read_time
  - drivers/rtc/rtc-mv.c:mv_rtc_read_time
  - drivers/rtc/rtc-omap.c:bcd2tm
  - drivers/rtc/rtc-omap.c:bcd2tm
  - drivers/rtc/rtc-omap.c:bcd2tm
  - drivers/rtc/rtc-omap.c:bcd2tm
  - drivers/rtc/rtc-omap.c:bcd2tm
  - drivers/rtc/rtc-omap.c:bcd2tm
  - drivers/rtc/rtc-pcf8523.c:pcf8523_rtc_read_time
  - drivers/rtc/rtc-pcf8523.c:pcf8523_rtc_read_time
  - drivers/rtc/rtc-pcf8523.c:pcf8523_rtc_read_time
  - drivers/rtc/rtc-pcf8523.c:pcf8523_rtc_read_time
  - drivers/rtc/rtc-pcf8523.c:pcf8523_rtc_read_time
  - drivers/rtc/rtc-pcf8523.c:pcf8523_rtc_read_time
  - drivers/rtc/rtc-pl031.c:pl031_stv2_time_to_tm
  - drivers/rtc/rtc-pl031.c:pl031_stv2_time_to_tm
  - drivers/rtc/rtc-s3c.c:s3c_rtc_getalarm
  - drivers/rtc/rtc-s3c.c:s3c_rtc_getalarm
  - drivers/rtc/rtc-s3c.c:s3c_rtc_getalarm
  - drivers/rtc/rtc-s3c.c:s3c_rtc_getalarm
  - drivers/rtc/rtc-s3c.c:s3c_rtc_getalarm
  - drivers/rtc/rtc-s3c.c:s3c_rtc_getalarm
  - drivers/rtc/rtc-s3c.c:s3c_rtc_gettime
  - drivers/rtc/rtc-s3c.c:s3c_rtc_gettime
  - drivers/rtc/rtc-s3c.c:s3c_rtc_gettime
  - drivers/rtc/rtc-s3c.c:s3c_rtc_gettime
  - drivers/rtc/rtc-s3c.c:s3c_rtc_gettime
  - drivers/rtc/rtc-s3c.c:s3c_rtc_gettime
  - drivers/rtc/rtc-twl.c:twl_rtc_read_alarm
  - drivers/rtc/rtc-twl.c:twl_rtc_read_alarm
  - drivers/rtc/rtc-twl.c:twl_rtc_read_alarm
  - drivers/rtc/rtc-twl.c:twl_rtc_read_alarm
  - drivers/rtc/rtc-twl.c:twl_rtc_read_alarm
  - drivers/rtc/rtc-twl.c:twl_rtc_read_alarm
  - drivers/rtc/rtc-twl.c:twl_rtc_read_time
  - drivers/rtc/rtc-twl.c:twl_rtc_read_time
  - drivers/rtc/rtc-twl.c:twl_rtc_read_time
  - drivers/rtc/rtc-twl.c:twl_rtc_read_time
  - drivers/rtc/rtc-twl.c:twl_rtc_read_time
  - drivers/rtc/rtc-twl.c:twl_rtc_read_time
```
**Symbols:**

```
c07d0a30-c07d0a50: _bcd2bin (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
unsigned int _bcd2bin(unsigned char val);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/bcd.c (c0000000007cb0f0)
Location: lib/bcd.c:5
Inline: False
Direct callers:
  - arch/powerpc/platforms/powernv/opal-rtc.c:opal_get_boot_time
  - arch/powerpc/platforms/powernv/opal-rtc.c:opal_get_boot_time
  - arch/powerpc/platforms/powernv/opal-rtc.c:opal_get_boot_time
  - arch/powerpc/platforms/powernv/opal-rtc.c:opal_get_boot_time
  - arch/powerpc/platforms/powernv/opal-rtc.c:opal_get_boot_time
  - arch/powerpc/platforms/powernv/opal-rtc.c:opal_get_boot_time
  - arch/powerpc/platforms/powernv/opal-rtc.c:opal_get_boot_time
  - drivers/rtc/rtc-mc146818-lib.c:mc146818_get_time
  - drivers/rtc/rtc-mc146818-lib.c:mc146818_get_time
  - drivers/rtc/rtc-mc146818-lib.c:mc146818_get_time
  - drivers/rtc/rtc-mc146818-lib.c:mc146818_get_time
  - drivers/rtc/rtc-mc146818-lib.c:mc146818_get_time
  - drivers/rtc/rtc-mc146818-lib.c:mc146818_get_time
  - drivers/rtc/rtc-opal.c:opal_to_tm
  - drivers/rtc/rtc-opal.c:opal_to_tm
  - drivers/rtc/rtc-opal.c:opal_to_tm
  - drivers/rtc/rtc-opal.c:opal_to_tm
  - drivers/rtc/rtc-opal.c:opal_to_tm
  - drivers/rtc/rtc-opal.c:opal_to_tm
  - drivers/rtc/rtc-opal.c:opal_to_tm
```
**Symbols:**

```
c0000000007cb0f0-c0000000007cb108: _bcd2bin (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
unsigned int _bcd2bin(unsigned char val);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/bcd.c (ffffffe00045a42c)
Location: lib/bcd.c:5
Inline: False
```
**Symbols:**

```
ffffffe00045a42c-ffffffe00045a44a: _bcd2bin (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: ✅</summary>

```c
unsigned int _bcd2bin(unsigned char val);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/bcd.c (ffffffff815188b0)
Location: lib/bcd.c:5
Inline: False
Direct callers:
  - arch/x86/kernel/rtc.c:mach_get_cmos_time
  - arch/x86/kernel/rtc.c:mach_get_cmos_time
  - arch/x86/kernel/rtc.c:mach_get_cmos_time
  - arch/x86/kernel/rtc.c:mach_get_cmos_time
  - arch/x86/kernel/rtc.c:mach_get_cmos_time
  - arch/x86/kernel/rtc.c:mach_get_cmos_time
  - arch/x86/kernel/rtc.c:mach_get_cmos_time
  - drivers/rtc/rtc-mc146818-lib.c:mc146818_get_time
  - drivers/rtc/rtc-mc146818-lib.c:mc146818_get_time
  - drivers/rtc/rtc-mc146818-lib.c:mc146818_get_time
  - drivers/rtc/rtc-mc146818-lib.c:mc146818_get_time
  - drivers/rtc/rtc-mc146818-lib.c:mc146818_get_time
  - drivers/rtc/rtc-mc146818-lib.c:mc146818_get_time
  - drivers/rtc/rtc-mc146818-lib.c:mc146818_get_time
  - drivers/rtc/rtc-cmos.c:cmos_read_alarm
  - drivers/rtc/rtc-cmos.c:cmos_read_alarm
  - drivers/rtc/rtc-cmos.c:cmos_read_alarm
  - drivers/rtc/rtc-cmos.c:cmos_read_alarm
  - drivers/rtc/rtc-cmos.c:cmos_read_alarm
```
**Symbols:**

```
ffffffff815188b0-ffffffff815188c2: _bcd2bin (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
unsigned int _bcd2bin(unsigned char val);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/bcd.c (ffffffff81508bb0)
Location: lib/bcd.c:5
Inline: False
Direct callers:
  - arch/x86/kernel/rtc.c:mach_get_cmos_time
  - arch/x86/kernel/rtc.c:mach_get_cmos_time
  - arch/x86/kernel/rtc.c:mach_get_cmos_time
  - arch/x86/kernel/rtc.c:mach_get_cmos_time
  - arch/x86/kernel/rtc.c:mach_get_cmos_time
  - arch/x86/kernel/rtc.c:mach_get_cmos_time
  - arch/x86/kernel/rtc.c:mach_get_cmos_time
  - drivers/rtc/rtc-mc146818-lib.c:mc146818_get_time
  - drivers/rtc/rtc-mc146818-lib.c:mc146818_get_time
  - drivers/rtc/rtc-mc146818-lib.c:mc146818_get_time
  - drivers/rtc/rtc-mc146818-lib.c:mc146818_get_time
  - drivers/rtc/rtc-mc146818-lib.c:mc146818_get_time
  - drivers/rtc/rtc-mc146818-lib.c:mc146818_get_time
  - drivers/rtc/rtc-mc146818-lib.c:mc146818_get_time
  - drivers/rtc/rtc-cmos.c:cmos_read_alarm
  - drivers/rtc/rtc-cmos.c:cmos_read_alarm
  - drivers/rtc/rtc-cmos.c:cmos_read_alarm
  - drivers/rtc/rtc-cmos.c:cmos_read_alarm
  - drivers/rtc/rtc-cmos.c:cmos_read_alarm
  - drivers/firmware/efi/cper.c:cper_estatus_print_section
  - drivers/firmware/efi/cper.c:cper_estatus_print_section
  - drivers/firmware/efi/cper.c:cper_estatus_print_section
  - drivers/firmware/efi/cper.c:cper_estatus_print_section
  - drivers/firmware/efi/cper.c:cper_estatus_print_section
  - drivers/firmware/efi/cper.c:cper_estatus_print_section
  - drivers/firmware/efi/cper.c:cper_estatus_print_section
```
**Symbols:**

```
ffffffff81508bb0-ffffffff81508bc2: _bcd2bin (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
unsigned int _bcd2bin(unsigned char val);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/bcd.c (ffffffff81514940)
Location: lib/bcd.c:5
Inline: False
Direct callers:
  - arch/x86/kernel/rtc.c:mach_get_cmos_time
  - arch/x86/kernel/rtc.c:mach_get_cmos_time
  - arch/x86/kernel/rtc.c:mach_get_cmos_time
  - arch/x86/kernel/rtc.c:mach_get_cmos_time
  - arch/x86/kernel/rtc.c:mach_get_cmos_time
  - arch/x86/kernel/rtc.c:mach_get_cmos_time
  - arch/x86/kernel/rtc.c:mach_get_cmos_time
  - drivers/rtc/rtc-mc146818-lib.c:mc146818_get_time
  - drivers/rtc/rtc-mc146818-lib.c:mc146818_get_time
  - drivers/rtc/rtc-mc146818-lib.c:mc146818_get_time
  - drivers/rtc/rtc-mc146818-lib.c:mc146818_get_time
  - drivers/rtc/rtc-mc146818-lib.c:mc146818_get_time
  - drivers/rtc/rtc-mc146818-lib.c:mc146818_get_time
  - drivers/rtc/rtc-mc146818-lib.c:mc146818_get_time
  - drivers/rtc/rtc-cmos.c:cmos_read_alarm
  - drivers/rtc/rtc-cmos.c:cmos_read_alarm
  - drivers/rtc/rtc-cmos.c:cmos_read_alarm
  - drivers/rtc/rtc-cmos.c:cmos_read_alarm
  - drivers/rtc/rtc-cmos.c:cmos_read_alarm
  - drivers/firmware/efi/cper.c:cper_estatus_print_section
  - drivers/firmware/efi/cper.c:cper_estatus_print_section
  - drivers/firmware/efi/cper.c:cper_estatus_print_section
  - drivers/firmware/efi/cper.c:cper_estatus_print_section
  - drivers/firmware/efi/cper.c:cper_estatus_print_section
  - drivers/firmware/efi/cper.c:cper_estatus_print_section
  - drivers/firmware/efi/cper.c:cper_estatus_print_section
```
**Symbols:**

```
ffffffff81514940-ffffffff81514952: _bcd2bin (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
unsigned int _bcd2bin(unsigned char val);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/bcd.c (ffffffff8152e0b0)
Location: lib/bcd.c:5
Inline: False
Direct callers:
  - arch/x86/kernel/rtc.c:mach_get_cmos_time
  - arch/x86/kernel/rtc.c:mach_get_cmos_time
  - arch/x86/kernel/rtc.c:mach_get_cmos_time
  - arch/x86/kernel/rtc.c:mach_get_cmos_time
  - arch/x86/kernel/rtc.c:mach_get_cmos_time
  - arch/x86/kernel/rtc.c:mach_get_cmos_time
  - arch/x86/kernel/rtc.c:mach_get_cmos_time
  - drivers/rtc/rtc-mc146818-lib.c:mc146818_get_time
  - drivers/rtc/rtc-mc146818-lib.c:mc146818_get_time
  - drivers/rtc/rtc-mc146818-lib.c:mc146818_get_time
  - drivers/rtc/rtc-mc146818-lib.c:mc146818_get_time
  - drivers/rtc/rtc-mc146818-lib.c:mc146818_get_time
  - drivers/rtc/rtc-mc146818-lib.c:mc146818_get_time
  - drivers/rtc/rtc-mc146818-lib.c:mc146818_get_time
  - drivers/rtc/rtc-cmos.c:cmos_read_alarm
  - drivers/rtc/rtc-cmos.c:cmos_read_alarm
  - drivers/rtc/rtc-cmos.c:cmos_read_alarm
  - drivers/rtc/rtc-cmos.c:cmos_read_alarm
  - drivers/rtc/rtc-cmos.c:cmos_read_alarm
  - drivers/firmware/efi/cper.c:cper_estatus_print_section
  - drivers/firmware/efi/cper.c:cper_estatus_print_section
  - drivers/firmware/efi/cper.c:cper_estatus_print_section
  - drivers/firmware/efi/cper.c:cper_estatus_print_section
  - drivers/firmware/efi/cper.c:cper_estatus_print_section
  - drivers/firmware/efi/cper.c:cper_estatus_print_section
  - drivers/firmware/efi/cper.c:cper_estatus_print_section
```
**Symbols:**

```
ffffffff8152e0b0-ffffffff8152e0c2: _bcd2bin (STB_GLOBAL)
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
No changes between <code>6.5</code> and <code>6.8</code> ✅
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
<li>
No changes between <code>amd64</code> and <code>ppc64el</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>riscv64</code> ✅
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
