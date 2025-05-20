# Function: <code>get_uv_systab_phys</code>

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
<details>
<summary>In <code>5.11</code>: Selective Inline, Transformation ⚠️</summary>

```c
long unsigned int get_uv_systab_phys(bool msg);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/x86/platform/uv/bios_uv.c (ffffffff810996e8)
Location: arch/x86/platform/uv/bios_uv.c:229
Inline: True
Inline callers:
  - arch/x86/platform/uv/bios_uv.c:uv_bios_init
  - arch/x86/platform/uv/bios_uv.c:uv_bios_init
Direct callers:
  - arch/x86/kernel/apic/x2apic_uv_x.c:early_get_arch_type
```
**Symbols:**

```
ffffffff81bda4f8-ffffffff81bda50b: get_uv_systab_phys.cold (STB_LOCAL)
ffffffff81099680-ffffffff810996c3: get_uv_systab_phys (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline, Transformation ⚠️</summary>

```c
long unsigned int get_uv_systab_phys(bool msg);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/x86/platform/uv/bios_uv.c (ffffffff81099ef8)
Location: arch/x86/platform/uv/bios_uv.c:229
Inline: True
Inline callers:
  - arch/x86/platform/uv/bios_uv.c:uv_bios_init
  - arch/x86/platform/uv/bios_uv.c:uv_bios_init
Direct callers:
  - arch/x86/kernel/apic/x2apic_uv_x.c:early_get_arch_type
```
**Symbols:**

```
ffffffff81bcc620-ffffffff81bcc633: get_uv_systab_phys.cold (STB_LOCAL)
ffffffff81099e90-ffffffff81099ed3: get_uv_systab_phys (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline, Transformation ⚠️</summary>

```c
long unsigned int get_uv_systab_phys(bool msg);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/x86/platform/uv/bios_uv.c (ffffffff810a9f18)
Location: arch/x86/platform/uv/bios_uv.c:229
Inline: True
Inline callers:
  - arch/x86/platform/uv/bios_uv.c:uv_bios_init
  - arch/x86/platform/uv/bios_uv.c:uv_bios_init
Direct callers:
  - arch/x86/kernel/apic/x2apic_uv_x.c:early_get_arch_type
```
**Symbols:**

```
ffffffff81ca28cc-ffffffff81ca28df: get_uv_systab_phys.cold (STB_LOCAL)
ffffffff810a9eb0-ffffffff810a9ef3: get_uv_systab_phys (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline, Transformation ⚠️</summary>

```c
long unsigned int get_uv_systab_phys(bool msg);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/x86/platform/uv/bios_uv.c (ffffffff810bf938)
Location: arch/x86/platform/uv/bios_uv.c:229
Inline: True
Inline callers:
  - arch/x86/platform/uv/bios_uv.c:uv_bios_init
  - arch/x86/platform/uv/bios_uv.c:uv_bios_init
Direct callers:
  - arch/x86/kernel/apic/x2apic_uv_x.c:early_get_arch_type
```
**Symbols:**

```
ffffffff81e52136-ffffffff81e52147: get_uv_systab_phys.cold (STB_LOCAL)
ffffffff810bf8d0-ffffffff810bf920: get_uv_systab_phys (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
long unsigned int get_uv_systab_phys(bool msg);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/platform/uv/bios_uv.c (ffffffff810db798)
Location: arch/x86/platform/uv/bios_uv.c:229
Inline: True
Inline callers:
  - arch/x86/platform/uv/bios_uv.c:uv_bios_init
  - arch/x86/platform/uv/bios_uv.c:uv_bios_init
Direct callers:
  - arch/x86/kernel/apic/x2apic_uv_x.c:uv_set_system_type
```
**Symbols:**

```
ffffffff810db710-ffffffff810db769: get_uv_systab_phys (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
long unsigned int get_uv_systab_phys(bool msg);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/platform/uv/bios_uv.c (ffffffff810e6d28)
Location: arch/x86/platform/uv/bios_uv.c:229
Inline: True
Inline callers:
  - arch/x86/platform/uv/bios_uv.c:uv_bios_init
  - arch/x86/platform/uv/bios_uv.c:uv_bios_init
Direct callers:
  - arch/x86/kernel/apic/x2apic_uv_x.c:uv_set_system_type
```
**Symbols:**

```
ffffffff810e6ca0-ffffffff810e6cf9: get_uv_systab_phys (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
long unsigned int get_uv_systab_phys(bool msg);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/platform/uv/bios_uv.c (ffffffff810ef0a8)
Location: arch/x86/platform/uv/bios_uv.c:229
Inline: True
Inline callers:
  - arch/x86/platform/uv/bios_uv.c:uv_bios_init
  - arch/x86/platform/uv/bios_uv.c:uv_bios_init
Direct callers:
  - arch/x86/kernel/apic/x2apic_uv_x.c:uv_set_system_type
```
**Symbols:**

```
ffffffff810ef020-ffffffff810ef079: get_uv_systab_phys (STB_GLOBAL)
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
