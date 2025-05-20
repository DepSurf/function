# Function: <code>insert_resource</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int insert_resource(struct resource *parent, struct resource *new);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/resource.c (ffffffff81087680)
Location: kernel/resource.c:834
Inline: False
Direct callers:
  - arch/x86/kernel/setup.c:setup_arch
  - arch/x86/kernel/setup.c:setup_arch
  - arch/x86/kernel/setup.c:setup_arch
  - arch/x86/kernel/setup.c:setup_arch
  - arch/x86/kernel/setup.c:setup_arch
  - arch/x86/kernel/e820.c:e820_reserve_resources
  - arch/x86/kernel/acpi/boot.c:hpet_insert_resource
  - arch/x86/kernel/apic/apic.c:lapic_insert_resource
  - arch/x86/kernel/apic/io_apic.c:ioapic_insert_resources
  - kernel/kexec_core.c:crash_shrink_memory
  - drivers/base/platform.c:platform_device_add
  - drivers/base/platform.c:platform_device_add
```
**Symbols:**

```
ffffffff81087680-ffffffff810876c0: insert_resource (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int insert_resource(struct resource *parent, struct resource *new);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/resource.c (ffffffff81089400)
Location: kernel/resource.c:871
Inline: False
Direct callers:
  - arch/x86/kernel/setup.c:setup_arch
  - arch/x86/kernel/setup.c:setup_arch
  - arch/x86/kernel/setup.c:setup_arch
  - arch/x86/kernel/setup.c:setup_arch
  - arch/x86/kernel/setup.c:setup_arch
  - arch/x86/kernel/e820.c:e820_reserve_resources
  - arch/x86/kernel/acpi/boot.c:hpet_insert_resource
  - arch/x86/kernel/apic/apic.c:lapic_insert_resource
  - arch/x86/kernel/apic/io_apic.c:ioapic_insert_resources
  - kernel/kexec_core.c:crash_shrink_memory
  - drivers/base/platform.c:platform_device_add
```
**Symbols:**

```
ffffffff81089400-ffffffff81089440: insert_resource (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int insert_resource(struct resource *parent, struct resource *new);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/resource.c (ffffffff8108e350)
Location: kernel/resource.c:871
Inline: False
Direct callers:
  - arch/x86/kernel/setup.c:setup_arch
  - arch/x86/kernel/setup.c:setup_arch
  - arch/x86/kernel/setup.c:setup_arch
  - arch/x86/kernel/setup.c:setup_arch
  - arch/x86/kernel/setup.c:setup_arch
  - arch/x86/kernel/e820.c:e820_reserve_resources
  - arch/x86/kernel/acpi/boot.c:hpet_insert_resource
  - arch/x86/kernel/apic/apic.c:lapic_insert_resource
  - arch/x86/kernel/apic/io_apic.c:ioapic_insert_resources
  - kernel/kexec_core.c:crash_shrink_memory
  - drivers/acpi/ioapic.c:handle_ioapic_add
  - drivers/base/platform.c:platform_device_add
```
**Symbols:**

```
ffffffff8108e350-ffffffff8108e390: insert_resource (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int insert_resource(struct resource *parent, struct resource *new);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/resource.c (ffffffff8108b370)
Location: kernel/resource.c:871
Inline: False
Direct callers:
  - arch/x86/kernel/setup.c:setup_arch
  - arch/x86/kernel/setup.c:setup_arch
  - arch/x86/kernel/setup.c:setup_arch
  - arch/x86/kernel/setup.c:setup_arch
  - arch/x86/kernel/setup.c:setup_arch
  - arch/x86/kernel/e820.c:e820__reserve_resources
  - arch/x86/kernel/acpi/boot.c:hpet_insert_resource
  - arch/x86/kernel/apic/apic.c:lapic_insert_resource
  - arch/x86/kernel/apic/io_apic.c:ioapic_insert_resources
  - kernel/kexec_core.c:crash_shrink_memory
  - drivers/acpi/ioapic.c:handle_ioapic_add
  - drivers/acpi/ioapic.c:handle_ioapic_add
  - drivers/base/platform.c:platform_device_add
```
**Symbols:**

```
ffffffff8108b370-ffffffff8108b3b0: insert_resource (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int insert_resource(struct resource *parent, struct resource *new);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/resource.c (ffffffff81092050)
Location: kernel/resource.c:889
Inline: False
Direct callers:
  - arch/x86/xen/enlighten.c:arch_xen_balloon_init
  - arch/x86/kernel/setup.c:setup_arch
  - arch/x86/kernel/setup.c:setup_arch
  - arch/x86/kernel/setup.c:setup_arch
  - arch/x86/kernel/setup.c:setup_arch
  - arch/x86/kernel/setup.c:setup_arch
  - arch/x86/kernel/e820.c:e820__reserve_resources
  - arch/x86/kernel/acpi/boot.c:hpet_insert_resource
  - arch/x86/kernel/apic/apic.c:lapic_insert_resource
  - arch/x86/kernel/apic/io_apic.c:ioapic_insert_resources
  - kernel/kexec_core.c:crash_shrink_memory
  - drivers/acpi/ioapic.c:handle_ioapic_add
  - drivers/acpi/ioapic.c:handle_ioapic_add
  - drivers/xen/balloon.c:reserve_additional_memory
  - drivers/base/platform.c:platform_device_add
```
**Symbols:**

```
ffffffff81092050-ffffffff81092090: insert_resource (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int insert_resource(struct resource *parent, struct resource *new);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/resource.c (ffffffff81096c10)
Location: kernel/resource.c:858
Inline: False
Direct callers:
  - arch/x86/xen/enlighten.c:arch_xen_balloon_init
  - arch/x86/kernel/setup.c:setup_arch
  - arch/x86/kernel/setup.c:setup_arch
  - arch/x86/kernel/setup.c:setup_arch
  - arch/x86/kernel/setup.c:setup_arch
  - arch/x86/kernel/setup.c:setup_arch
  - arch/x86/kernel/e820.c:e820__reserve_resources
  - arch/x86/kernel/acpi/boot.c:hpet_insert_resource
  - arch/x86/kernel/apic/apic.c:lapic_insert_resource
  - arch/x86/kernel/apic/io_apic.c:ioapic_insert_resources
  - kernel/kexec_core.c:crash_shrink_memory
  - drivers/acpi/ioapic.c:handle_ioapic_add
  - drivers/acpi/ioapic.c:handle_ioapic_add
  - drivers/xen/balloon.c:reserve_additional_memory
  - drivers/base/platform.c:platform_device_add
  - arch/x86/pci/mmconfig-shared.c:pci_mmcfg_late_insert_resources
```
**Symbols:**

```
ffffffff81096c10-ffffffff81096c2b: insert_resource (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int insert_resource(struct resource *parent, struct resource *new);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/resource.c (ffffffff8109ef30)
Location: kernel/resource.c:852
Inline: False
Direct callers:
  - arch/x86/kernel/setup.c:setup_arch
  - arch/x86/kernel/setup.c:setup_arch
  - arch/x86/kernel/setup.c:setup_arch
  - arch/x86/kernel/setup.c:setup_arch
  - arch/x86/kernel/setup.c:setup_arch
  - arch/x86/kernel/e820.c:e820__reserve_resources
  - arch/x86/kernel/acpi/boot.c:hpet_insert_resource
  - arch/x86/kernel/apic/apic.c:lapic_insert_resource
  - arch/x86/kernel/apic/io_apic.c:ioapic_insert_resources
  - kernel/kexec_core.c:crash_shrink_memory
  - drivers/acpi/ioapic.c:handle_ioapic_add
  - drivers/acpi/ioapic.c:handle_ioapic_add
  - drivers/base/platform.c:platform_device_add
  - arch/x86/pci/mmconfig-shared.c:pci_mmcfg_late_insert_resources
```
**Symbols:**

```
ffffffff8109ef30-ffffffff8109ef4b: insert_resource (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int insert_resource(struct resource *parent, struct resource *new);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/resource.c (ffffffff810a3560)
Location: kernel/resource.c:866
Inline: False
Direct callers:
  - arch/x86/kernel/setup.c:setup_arch
  - arch/x86/kernel/setup.c:setup_arch
  - arch/x86/kernel/setup.c:setup_arch
  - arch/x86/kernel/setup.c:reserve_crashkernel
  - arch/x86/kernel/setup.c:reserve_crashkernel
  - arch/x86/kernel/e820.c:e820__reserve_resources
  - arch/x86/kernel/acpi/boot.c:hpet_insert_resource
  - arch/x86/kernel/apic/apic.c:lapic_insert_resource
  - arch/x86/kernel/apic/io_apic.c:ioapic_insert_resources
  - kernel/kexec_core.c:crash_shrink_memory
  - drivers/acpi/ioapic.c:handle_ioapic_add
  - drivers/acpi/ioapic.c:handle_ioapic_add
  - drivers/base/platform.c:platform_device_add
  - arch/x86/pci/mmconfig-shared.c:pci_mmcfg_late_insert_resources
```
**Symbols:**

```
ffffffff810a3560-ffffffff810a357b: insert_resource (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int insert_resource(struct resource *parent, struct resource *new);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/resource.c (ffffffff810a9b90)
Location: kernel/resource.c:866
Inline: False
Direct callers:
  - arch/x86/kernel/setup.c:setup_arch
  - arch/x86/kernel/setup.c:setup_arch
  - arch/x86/kernel/setup.c:setup_arch
  - arch/x86/kernel/setup.c:reserve_crashkernel
  - arch/x86/kernel/setup.c:reserve_crashkernel
  - arch/x86/kernel/e820.c:e820__reserve_resources
  - arch/x86/kernel/acpi/boot.c:hpet_insert_resource
  - arch/x86/kernel/apic/apic.c:lapic_insert_resource
  - arch/x86/kernel/apic/io_apic.c:ioapic_insert_resources
  - kernel/kexec_core.c:crash_shrink_memory
  - drivers/acpi/ioapic.c:handle_ioapic_add
  - drivers/acpi/ioapic.c:handle_ioapic_add
  - drivers/base/platform.c:platform_device_add
  - arch/x86/pci/mmconfig-shared.c:pci_mmcfg_late_insert_resources
```
**Symbols:**

```
ffffffff810a9b90-ffffffff810a9bab: insert_resource (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int insert_resource(struct resource *parent, struct resource *new);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/resource.c (ffffffff810b0dc0)
Location: kernel/resource.c:866
Inline: False
Direct callers:
  - arch/x86/kernel/setup.c:setup_arch
  - arch/x86/kernel/setup.c:setup_arch
  - arch/x86/kernel/setup.c:setup_arch
  - arch/x86/kernel/setup.c:setup_arch
  - arch/x86/kernel/setup.c:reserve_crashkernel
  - arch/x86/kernel/setup.c:reserve_crashkernel_low
  - arch/x86/kernel/e820.c:e820__reserve_resources
  - arch/x86/kernel/acpi/boot.c:hpet_insert_resource
  - arch/x86/kernel/apic/apic.c:lapic_insert_resource
  - arch/x86/kernel/apic/io_apic.c:ioapic_insert_resources
  - kernel/kexec_core.c:crash_shrink_memory
  - drivers/acpi/ioapic.c:handle_ioapic_add
  - drivers/acpi/ioapic.c:handle_ioapic_add
  - drivers/base/platform.c:platform_device_add
  - arch/x86/pci/mmconfig-shared.c:pci_mmcfg_late_insert_resources
```
**Symbols:**

```
ffffffff810b0dc0-ffffffff810b0e02: insert_resource (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int insert_resource(struct resource *parent, struct resource *new);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/resource.c (ffffffff810ac520)
Location: kernel/resource.c:873
Inline: False
Direct callers:
  - arch/x86/kernel/setup.c:setup_arch
  - arch/x86/kernel/setup.c:setup_arch
  - arch/x86/kernel/setup.c:setup_arch
  - arch/x86/kernel/setup.c:setup_arch
  - arch/x86/kernel/setup.c:reserve_crashkernel
  - arch/x86/kernel/setup.c:reserve_crashkernel_low
  - arch/x86/kernel/e820.c:e820__reserve_resources
  - arch/x86/kernel/acpi/boot.c:hpet_insert_resource
  - arch/x86/kernel/apic/apic.c:lapic_insert_resource
  - arch/x86/kernel/apic/io_apic.c:ioapic_insert_resources
  - kernel/kexec_core.c:crash_shrink_memory
  - drivers/acpi/ioapic.c:handle_ioapic_add
  - drivers/acpi/ioapic.c:handle_ioapic_add
  - drivers/base/platform.c:platform_device_add
  - arch/x86/pci/mmconfig-shared.c:pci_mmcfg_late_insert_resources
```
**Symbols:**

```
ffffffff810ac520-ffffffff810ac562: insert_resource (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int insert_resource(struct resource *parent, struct resource *new);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/resource.c (ffffffff810ad740)
Location: kernel/resource.c:865
Inline: False
Direct callers:
  - arch/x86/kernel/setup.c:setup_arch
  - arch/x86/kernel/setup.c:setup_arch
  - arch/x86/kernel/setup.c:setup_arch
  - arch/x86/kernel/setup.c:setup_arch
  - arch/x86/kernel/setup.c:reserve_crashkernel
  - arch/x86/kernel/setup.c:reserve_crashkernel
  - arch/x86/kernel/e820.c:e820__reserve_resources
  - arch/x86/kernel/acpi/boot.c:hpet_insert_resource
  - arch/x86/kernel/apic/apic.c:lapic_insert_resource
  - arch/x86/kernel/apic/io_apic.c:ioapic_insert_resources
  - kernel/kexec_core.c:crash_shrink_memory
  - drivers/acpi/ioapic.c:handle_ioapic_add
  - drivers/acpi/ioapic.c:handle_ioapic_add
  - drivers/base/platform.c:platform_device_add
  - arch/x86/pci/mmconfig-shared.c:pci_mmcfg_late_insert_resources
```
**Symbols:**

```
ffffffff810ad740-ffffffff810ad77f: insert_resource (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int insert_resource(struct resource *parent, struct resource *new);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/resource.c (ffffffff810bf2c0)
Location: kernel/resource.c:865
Inline: False
Direct callers:
  - arch/x86/kernel/setup.c:setup_arch
  - arch/x86/kernel/setup.c:setup_arch
  - arch/x86/kernel/setup.c:setup_arch
  - arch/x86/kernel/setup.c:setup_arch
  - arch/x86/kernel/setup.c:reserve_crashkernel
  - arch/x86/kernel/setup.c:reserve_crashkernel
  - arch/x86/kernel/e820.c:e820__reserve_resources
  - arch/x86/kernel/acpi/boot.c:hpet_insert_resource
  - arch/x86/kernel/apic/apic.c:lapic_insert_resource
  - arch/x86/kernel/apic/io_apic.c:ioapic_insert_resources
  - kernel/kexec_core.c:crash_shrink_memory
  - drivers/acpi/ioapic.c:handle_ioapic_add
  - drivers/acpi/ioapic.c:handle_ioapic_add
  - drivers/base/platform.c:platform_device_add
  - arch/x86/pci/mmconfig-shared.c:pci_mmcfg_late_insert_resources
```
**Symbols:**

```
ffffffff810bf2c0-ffffffff810bf2ff: insert_resource (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int insert_resource(struct resource *parent, struct resource *new);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/resource.c (ffffffff810d6620)
Location: kernel/resource.c:852
Inline: False
Direct callers:
  - arch/x86/kernel/setup.c:setup_arch
  - arch/x86/kernel/setup.c:setup_arch
  - arch/x86/kernel/setup.c:setup_arch
  - arch/x86/kernel/setup.c:setup_arch
  - arch/x86/kernel/setup.c:reserve_crashkernel
  - arch/x86/kernel/setup.c:reserve_crashkernel
  - arch/x86/kernel/e820.c:e820__reserve_resources
  - arch/x86/kernel/acpi/boot.c:hpet_insert_resource
  - arch/x86/kernel/apic/apic.c:lapic_insert_resource
  - arch/x86/kernel/apic/io_apic.c:ioapic_insert_resources
  - kernel/kexec_core.c:crash_shrink_memory
  - drivers/pci/quirks.c:quirk_alder_ioapic
  - drivers/acpi/ioapic.c:handle_ioapic_add
  - drivers/acpi/ioapic.c:handle_ioapic_add
  - drivers/base/platform.c:platform_device_add
  - arch/x86/pci/mmconfig-shared.c:pci_mmcfg_late_insert_resources
```
**Symbols:**

```
ffffffff810d6620-ffffffff810d666d: insert_resource (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int insert_resource(struct resource *parent, struct resource *new);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/resource.c (ffffffff810f5760)
Location: kernel/resource.c:853
Inline: False
Direct callers:
  - arch/x86/kernel/setup.c:setup_arch
  - arch/x86/kernel/setup.c:setup_arch
  - arch/x86/kernel/setup.c:setup_arch
  - arch/x86/kernel/setup.c:setup_arch
  - arch/x86/kernel/setup.c:reserve_crashkernel
  - arch/x86/kernel/setup.c:reserve_crashkernel
  - arch/x86/kernel/e820.c:e820__reserve_resources
  - arch/x86/kernel/acpi/boot.c:hpet_insert_resource
  - arch/x86/kernel/apic/apic.c:lapic_insert_resource
  - arch/x86/kernel/apic/io_apic.c:ioapic_insert_resources
  - kernel/kexec_core.c:crash_shrink_memory
  - drivers/pci/quirks.c:quirk_alder_ioapic
  - drivers/acpi/ioapic.c:handle_ioapic_add
  - drivers/acpi/ioapic.c:handle_ioapic_add
  - drivers/base/platform.c:platform_device_add
  - drivers/base/platform.c:platform_device_add
  - arch/x86/pci/mmconfig-shared.c:pci_mmcfg_late_insert_resources
```
**Symbols:**

```
ffffffff810f5760-ffffffff810f57ad: insert_resource (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int insert_resource(struct resource *parent, struct resource *new);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/resource.c (ffffffff81101ba0)
Location: kernel/resource.c:853
Inline: False
Direct callers:
  - arch/x86/kernel/setup.c:setup_arch
  - arch/x86/kernel/setup.c:setup_arch
  - arch/x86/kernel/setup.c:setup_arch
  - arch/x86/kernel/setup.c:setup_arch
  - arch/x86/kernel/setup.c:reserve_crashkernel
  - arch/x86/kernel/setup.c:reserve_crashkernel
  - arch/x86/kernel/e820.c:e820__reserve_resources
  - arch/x86/kernel/acpi/boot.c:hpet_insert_resource
  - arch/x86/kernel/apic/apic.c:lapic_insert_resource
  - arch/x86/kernel/apic/io_apic.c:ioapic_insert_resources
  - kernel/kexec_core.c:crash_shrink_memory
  - kernel/kexec_core.c:__crash_shrink_memory
  - drivers/pci/quirks.c:quirk_alder_ioapic
  - drivers/acpi/ioapic.c:handle_ioapic_add
  - drivers/acpi/ioapic.c:handle_ioapic_add
  - drivers/base/platform.c:platform_device_add
  - drivers/base/platform.c:platform_device_add
  - arch/x86/pci/mmconfig-shared.c:pci_mmcfg_late_insert_resources
```
**Symbols:**

```
ffffffff81101ba0-ffffffff81101bed: insert_resource (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int insert_resource(struct resource *parent, struct resource *new);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/resource.c (ffffffff8110b2f0)
Location: kernel/resource.c:908
Inline: False
Direct callers:
  - arch/x86/kernel/setup.c:setup_arch
  - arch/x86/kernel/setup.c:setup_arch
  - arch/x86/kernel/setup.c:setup_arch
  - arch/x86/kernel/setup.c:setup_arch
  - arch/x86/kernel/e820.c:e820__reserve_resources
  - arch/x86/kernel/acpi/boot.c:hpet_insert_resource
  - arch/x86/kernel/apic/apic.c:lapic_insert_resource
  - arch/x86/kernel/apic/io_apic.c:ioapic_insert_resources
  - kernel/crash_core.c:insert_crashkernel_resources
  - kernel/crash_core.c:insert_crashkernel_resources
  - kernel/kexec_core.c:crash_shrink_memory
  - kernel/kexec_core.c:__crash_shrink_memory
  - drivers/pci/quirks.c:quirk_alder_ioapic
  - drivers/acpi/ioapic.c:handle_ioapic_add
  - drivers/acpi/ioapic.c:handle_ioapic_add
  - drivers/base/platform.c:platform_device_add
  - drivers/base/platform.c:platform_device_add
  - arch/x86/pci/mmconfig-shared.c:pci_mmcfg_late_insert_resources
```
**Symbols:**

```
ffffffff8110b2f0-ffffffff8110b33d: insert_resource (STB_GLOBAL)
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
int insert_resource(struct resource *parent, struct resource *new);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/resource.c (ffff800010101b40)
Location: kernel/resource.c:866
Inline: False
Direct callers:
  - kernel/kexec_core.c:crash_shrink_memory
  - drivers/base/platform.c:platform_device_add
```
**Symbols:**

```
ffff800010101b40-ffff800010101b80: insert_resource (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int insert_resource(struct resource *parent, struct resource *new);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/resource.c (c035df7c)
Location: kernel/resource.c:866
Inline: False
Direct callers:
  - arch/arm/kernel/setup.c:setup_arch
  - arch/arm/kernel/setup.c:setup_arch
  - kernel/kexec_core.c:crash_shrink_memory
  - drivers/base/platform.c:platform_device_add
```
**Symbols:**

```
c035df7c-c035dfa4: insert_resource (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int insert_resource(struct resource *parent, struct resource *new);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/resource.c (c000000000149310)
Location: kernel/resource.c:866
Inline: False
Direct callers:
  - kernel/kexec_core.c:crash_shrink_memory
  - drivers/base/platform.c:platform_device_add
```
**Symbols:**

```
c000000000149310-c000000000149358: insert_resource (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int insert_resource(struct resource *parent, struct resource *new);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/resource.c (ffffffe0000c8c00)
Location: kernel/resource.c:866
Inline: False
Direct callers:
  - drivers/base/platform.c:platform_device_add
```
**Symbols:**

```
ffffffe0000c8c00-ffffffe0000c8c38: insert_resource (STB_GLOBAL)
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
int insert_resource(struct resource *parent, struct resource *new);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/resource.c (ffffffff810a34b0)
Location: kernel/resource.c:866
Inline: False
Direct callers:
  - arch/x86/kernel/setup.c:setup_arch
  - arch/x86/kernel/setup.c:setup_arch
  - arch/x86/kernel/setup.c:setup_arch
  - arch/x86/kernel/setup.c:reserve_crashkernel
  - arch/x86/kernel/setup.c:reserve_crashkernel
  - arch/x86/kernel/e820.c:e820__reserve_resources
  - arch/x86/kernel/acpi/boot.c:hpet_insert_resource
  - arch/x86/kernel/apic/apic.c:lapic_insert_resource
  - arch/x86/kernel/apic/io_apic.c:ioapic_insert_resources
  - kernel/kexec_core.c:crash_shrink_memory
  - drivers/acpi/ioapic.c:handle_ioapic_add
  - drivers/acpi/ioapic.c:handle_ioapic_add
  - drivers/base/platform.c:platform_device_add
  - arch/x86/pci/mmconfig-shared.c:pci_mmcfg_late_insert_resources
```
**Symbols:**

```
ffffffff810a34b0-ffffffff810a34cb: insert_resource (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int insert_resource(struct resource *parent, struct resource *new);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/resource.c (ffffffff81091e90)
Location: kernel/resource.c:866
Inline: False
Direct callers:
  - arch/x86/kernel/setup.c:setup_arch
  - arch/x86/kernel/setup.c:setup_arch
  - arch/x86/kernel/setup.c:setup_arch
  - arch/x86/kernel/setup.c:reserve_crashkernel
  - arch/x86/kernel/setup.c:reserve_crashkernel
  - arch/x86/kernel/e820.c:e820__reserve_resources
  - arch/x86/kernel/acpi/boot.c:hpet_insert_resource
  - arch/x86/kernel/apic/apic.c:lapic_insert_resource
  - arch/x86/kernel/apic/io_apic.c:ioapic_insert_resources
  - kernel/kexec_core.c:crash_shrink_memory
  - drivers/acpi/nfit/core.c:acpi_nfit_register_region
  - drivers/acpi/ioapic.c:handle_ioapic_add
  - drivers/acpi/ioapic.c:handle_ioapic_add
  - drivers/base/platform.c:platform_device_add
  - arch/x86/pci/mmconfig-shared.c:pci_mmcfg_late_insert_resources
```
**Symbols:**

```
ffffffff81091e90-ffffffff81091eab: insert_resource (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int insert_resource(struct resource *parent, struct resource *new);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/resource.c (ffffffff810a3460)
Location: kernel/resource.c:866
Inline: False
Direct callers:
  - arch/x86/kernel/setup.c:setup_arch
  - arch/x86/kernel/setup.c:setup_arch
  - arch/x86/kernel/setup.c:setup_arch
  - arch/x86/kernel/setup.c:reserve_crashkernel
  - arch/x86/kernel/setup.c:reserve_crashkernel
  - arch/x86/kernel/e820.c:e820__reserve_resources
  - arch/x86/kernel/acpi/boot.c:hpet_insert_resource
  - arch/x86/kernel/apic/apic.c:lapic_insert_resource
  - arch/x86/kernel/apic/io_apic.c:ioapic_insert_resources
  - kernel/kexec_core.c:crash_shrink_memory
  - drivers/acpi/ioapic.c:handle_ioapic_add
  - drivers/acpi/ioapic.c:handle_ioapic_add
  - drivers/base/platform.c:platform_device_add
  - arch/x86/pci/mmconfig-shared.c:pci_mmcfg_late_insert_resources
```
**Symbols:**

```
ffffffff810a3460-ffffffff810a347b: insert_resource (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int insert_resource(struct resource *parent, struct resource *new);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/resource.c (ffffffff810ab510)
Location: kernel/resource.c:866
Inline: False
Direct callers:
  - arch/x86/kernel/setup.c:setup_arch
  - arch/x86/kernel/setup.c:setup_arch
  - arch/x86/kernel/setup.c:setup_arch
  - arch/x86/kernel/setup.c:reserve_crashkernel
  - arch/x86/kernel/setup.c:reserve_crashkernel
  - arch/x86/kernel/e820.c:e820__reserve_resources
  - arch/x86/kernel/acpi/boot.c:hpet_insert_resource
  - arch/x86/kernel/apic/apic.c:lapic_insert_resource
  - arch/x86/kernel/apic/io_apic.c:ioapic_insert_resources
  - kernel/kexec_core.c:crash_shrink_memory
  - drivers/acpi/ioapic.c:handle_ioapic_add
  - drivers/acpi/ioapic.c:handle_ioapic_add
  - drivers/base/platform.c:platform_device_add
  - arch/x86/pci/mmconfig-shared.c:pci_mmcfg_late_insert_resources
```
**Symbols:**

```
ffffffff810ab510-ffffffff810ab52b: insert_resource (STB_GLOBAL)
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
