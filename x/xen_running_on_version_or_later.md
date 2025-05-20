# Function: <code>xen_running_on_version_or_later</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline, Transformation ⚠️</summary>

```c
bool xen_running_on_version_or_later(unsigned int major, unsigned int minor);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/x86/xen/enlighten.c (ffffffff8101c820)
Location: arch/x86/xen/enlighten.c:282
Inline: True
Inline callers:
  - arch/x86/xen/enlighten.c:xen_check_mwait
Direct callers:
  - arch/x86/xen/enlighten.c:xen_check_mwait
  - drivers/xen/xen-acpi-pad.c:xen_acpi_pad_init
```
**Symbols:**

```
ffffffff8101c820-ffffffff8101c855: xen_running_on_version_or_later.part.21 (STB_LOCAL)
ffffffff8101d550-ffffffff8101d56d: xen_running_on_version_or_later (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline, Transformation ⚠️</summary>

```c
bool xen_running_on_version_or_later(unsigned int major, unsigned int minor);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/x86/xen/enlighten.c (ffffffff81f88275)
Location: arch/x86/xen/enlighten.c:288
Inline: True
Inline callers:
  - arch/x86/xen/enlighten.c:xen_check_mwait
Direct callers:
  - arch/x86/xen/enlighten.c:xen_check_mwait
  - drivers/xen/xen-acpi-pad.c:xen_acpi_pad_init
```
**Symbols:**

```
ffffffff8101bab0-ffffffff8101bae5: xen_running_on_version_or_later.part.20 (STB_LOCAL)
ffffffff8101c8f0-ffffffff8101c90d: xen_running_on_version_or_later (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline, Transformation ⚠️</summary>

```c
bool xen_running_on_version_or_later(unsigned int major, unsigned int minor);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/x86/xen/enlighten.c (ffffffff81fc3663)
Location: arch/x86/xen/enlighten.c:290
Inline: True
Inline callers:
  - arch/x86/xen/enlighten.c:xen_check_mwait
Direct callers:
  - arch/x86/xen/enlighten.c:xen_check_mwait
  - drivers/xen/xen-acpi-pad.c:xen_acpi_pad_init
```
**Symbols:**

```
ffffffff8101c2d0-ffffffff8101c305: xen_running_on_version_or_later.part.20 (STB_LOCAL)
ffffffff8101d020-ffffffff8101d03d: xen_running_on_version_or_later (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline, Transformation ⚠️</summary>

```c
bool xen_running_on_version_or_later(unsigned int major, unsigned int minor);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/x86/xen/enlighten_pv.c (ffffffff820a582e)
Location: arch/x86/xen/enlighten_pv.c:121
Inline: True
Inline callers:
  - arch/x86/xen/enlighten_pv.c:xen_check_mwait
Direct callers:
  - arch/x86/xen/enlighten_pv.c:xen_check_mwait
  - drivers/xen/xen-acpi-pad.c:xen_acpi_pad_init
```
**Symbols:**

```
ffffffff8101f180-ffffffff8101f1b5: xen_running_on_version_or_later.part.16 (STB_LOCAL)
ffffffff8101fac0-ffffffff8101fadd: xen_running_on_version_or_later (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline, Transformation ⚠️</summary>

```c
bool xen_running_on_version_or_later(unsigned int major, unsigned int minor);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/x86/xen/enlighten_pv.c (ffffffff826abef5)
Location: arch/x86/xen/enlighten_pv.c:124
Inline: True
Inline callers:
  - arch/x86/xen/enlighten_pv.c:xen_check_mwait
Direct callers:
  - arch/x86/xen/enlighten_pv.c:xen_check_mwait
  - drivers/xen/xen-acpi-pad.c:xen_acpi_pad_init
```
**Symbols:**

```
ffffffff8101fca0-ffffffff8101fcd5: xen_running_on_version_or_later.part.17 (STB_LOCAL)
ffffffff81020720-ffffffff8102073d: xen_running_on_version_or_later (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline, Transformation ⚠️</summary>

```c
bool xen_running_on_version_or_later(unsigned int major, unsigned int minor);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/x86/xen/enlighten_pv.c (ffffffff826d5028)
Location: arch/x86/xen/enlighten_pv.c:124
Inline: True
Inline callers:
  - arch/x86/xen/enlighten_pv.c:xen_check_mwait
Direct callers:
  - arch/x86/xen/enlighten_pv.c:xen_check_mwait
  - drivers/xen/xen-acpi-pad.c:xen_acpi_pad_init
```
**Symbols:**

```
ffffffff810204e0-ffffffff81020510: xen_running_on_version_or_later.part.16 (STB_LOCAL)
ffffffff810211b0-ffffffff810211cd: xen_running_on_version_or_later (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline, Transformation ⚠️</summary>

```c
bool xen_running_on_version_or_later(unsigned int major, unsigned int minor);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/x86/xen/enlighten_pv.c (ffffffff8288b046)
Location: arch/x86/xen/enlighten_pv.c:146
Inline: True
Inline callers:
  - arch/x86/xen/enlighten_pv.c:xen_check_mwait
Direct callers:
  - arch/x86/xen/enlighten_pv.c:xen_check_mwait
  - drivers/xen/xen-acpi-pad.c:xen_acpi_pad_init
```
**Symbols:**

```
ffffffff8101ff50-ffffffff8101ff80: xen_running_on_version_or_later.part.16 (STB_LOCAL)
ffffffff81020a80-ffffffff81020a9d: xen_running_on_version_or_later (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline, Transformation ⚠️</summary>

```c
bool xen_running_on_version_or_later(unsigned int major, unsigned int minor);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/x86/xen/enlighten_pv.c (ffffffff828a2492)
Location: arch/x86/xen/enlighten_pv.c:146
Inline: True
Inline callers:
  - arch/x86/xen/enlighten_pv.c:xen_check_mwait
Direct callers:
  - arch/x86/xen/enlighten_pv.c:xen_check_mwait
  - drivers/xen/xen-acpi-pad.c:xen_acpi_pad_init
```
**Symbols:**

```
ffffffff81021ad0-ffffffff81021b03: xen_running_on_version_or_later.part.0 (STB_LOCAL)
ffffffff810225c0-ffffffff810225dd: xen_running_on_version_or_later (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline, Transformation ⚠️</summary>

```c
bool xen_running_on_version_or_later(unsigned int major, unsigned int minor);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/x86/xen/enlighten_pv.c (ffffffff828a5546)
Location: arch/x86/xen/enlighten_pv.c:154
Inline: True
Inline callers:
  - arch/x86/xen/enlighten_pv.c:xen_check_mwait
Direct callers:
  - arch/x86/xen/enlighten_pv.c:xen_check_mwait
  - drivers/xen/xen-acpi-pad.c:xen_acpi_pad_init
```
**Symbols:**

```
ffffffff81022410-ffffffff81022443: xen_running_on_version_or_later.part.0 (STB_LOCAL)
ffffffff81022f00-ffffffff81022f1d: xen_running_on_version_or_later (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline, Transformation ⚠️</summary>

```c
bool xen_running_on_version_or_later(unsigned int major, unsigned int minor);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/x86/xen/enlighten_pv.c (ffffffff82ccb8ee)
Location: arch/x86/xen/enlighten_pv.c:156
Inline: True
Inline callers:
  - arch/x86/xen/enlighten_pv.c:xen_check_mwait
Direct callers:
  - arch/x86/xen/enlighten_pv.c:xen_check_mwait
  - drivers/xen/xen-acpi-pad.c:xen_acpi_pad_init
```
**Symbols:**

```
ffffffff81024970-ffffffff810249a3: xen_running_on_version_or_later.part.0 (STB_LOCAL)
ffffffff81025670-ffffffff810256bb: xen_running_on_version_or_later (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline, Transformation ⚠️</summary>

```c
bool xen_running_on_version_or_later(unsigned int major, unsigned int minor);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/x86/xen/enlighten_pv.c (ffffffff82fb775c)
Location: arch/x86/xen/enlighten_pv.c:148
Inline: True
Inline callers:
  - arch/x86/xen/enlighten_pv.c:xen_check_mwait
Direct callers:
  - arch/x86/xen/enlighten_pv.c:xen_check_mwait
  - drivers/xen/xen-acpi-pad.c:xen_acpi_pad_init
```
**Symbols:**

```
ffffffff810250f0-ffffffff81025123: xen_running_on_version_or_later.part.0 (STB_LOCAL)
ffffffff81025da0-ffffffff81025deb: xen_running_on_version_or_later (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
bool xen_running_on_version_or_later(unsigned int major, unsigned int minor);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/xen/enlighten_pv.c (ffffffff831c2275)
Location: arch/x86/xen/enlighten_pv.c:148
Inline: True
Inline callers:
  - arch/x86/xen/enlighten_pv.c:xen_start_kernel
  - arch/x86/xen/enlighten_pv.c:xen_start_kernel
Direct callers:
  - drivers/xen/xen-acpi-pad.c:xen_acpi_pad_init
```
**Symbols:**

```
ffffffff81027da0-ffffffff81027deb: xen_running_on_version_or_later (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
bool xen_running_on_version_or_later(unsigned int major, unsigned int minor);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/xen/enlighten.c (ffffffff81026e90)
Location: arch/x86/xen/enlighten.c:279
Inline: False
Direct callers:
  - arch/x86/xen/enlighten_pv.c:xen_start_kernel
  - drivers/xen/xen-acpi-pad.c:xen_acpi_pad_init
```
**Symbols:**

```
ffffffff81026e90-ffffffff81026edb: xen_running_on_version_or_later (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
bool xen_running_on_version_or_later(unsigned int major, unsigned int minor);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/xen/enlighten.c (ffffffff8102afe0)
Location: arch/x86/xen/enlighten.c:215
Inline: False
Direct callers:
  - arch/x86/xen/enlighten_pv.c:xen_check_mwait
  - drivers/xen/xen-acpi-pad.c:xen_acpi_pad_init
```
**Symbols:**

```
ffffffff8102afe0-ffffffff8102b064: xen_running_on_version_or_later (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
bool xen_running_on_version_or_later(unsigned int major, unsigned int minor);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/xen/enlighten.c (ffffffff81031c80)
Location: arch/x86/xen/enlighten.c:215
Inline: False
Direct callers:
  - arch/x86/xen/enlighten_pv.c:xen_check_mwait
  - drivers/xen/xen-acpi-pad.c:xen_acpi_pad_init
```
**Symbols:**

```
ffffffff81031c80-ffffffff81031d04: xen_running_on_version_or_later (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
bool xen_running_on_version_or_later(unsigned int major, unsigned int minor);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/xen/enlighten.c (ffffffff81031c80)
Location: arch/x86/xen/enlighten.c:215
Inline: False
Direct callers:
  - arch/x86/xen/enlighten_pv.c:xen_check_mwait
  - drivers/xen/xen-acpi-pad.c:xen_acpi_pad_init
```
**Symbols:**

```
ffffffff81031c80-ffffffff81031d04: xen_running_on_version_or_later (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
bool xen_running_on_version_or_later(unsigned int major, unsigned int minor);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/xen/enlighten.c (ffffffff81037f70)
Location: arch/x86/xen/enlighten.c:219
Inline: False
Direct callers:
  - arch/x86/xen/enlighten_pv.c:xen_check_mwait
  - drivers/xen/xen-acpi-pad.c:xen_acpi_pad_init
```
**Symbols:**

```
ffffffff81037f70-ffffffff81037ff4: xen_running_on_version_or_later (STB_GLOBAL)
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
<summary>In <code>aws</code>: Selective Inline, Transformation ⚠️</summary>

```c
bool xen_running_on_version_or_later(unsigned int major, unsigned int minor);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/x86/xen/enlighten_pv.c (ffffffff8289354f)
Location: arch/x86/xen/enlighten_pv.c:154
Inline: True
Inline callers:
  - arch/x86/xen/enlighten_pv.c:xen_check_mwait
Direct callers:
  - arch/x86/xen/enlighten_pv.c:xen_check_mwait
  - drivers/xen/xen-acpi-pad.c:xen_acpi_pad_init
```
**Symbols:**

```
ffffffff81022570-ffffffff810225a3: xen_running_on_version_or_later.part.0 (STB_LOCAL)
ffffffff81023060-ffffffff8102307d: xen_running_on_version_or_later (STB_GLOBAL)
```
</details>
</li>
<li>
In <code>azure</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline, Transformation ⚠️</summary>

```c
bool xen_running_on_version_or_later(unsigned int major, unsigned int minor);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/x86/xen/enlighten_pv.c (ffffffff828a6546)
Location: arch/x86/xen/enlighten_pv.c:154
Inline: True
Inline callers:
  - arch/x86/xen/enlighten_pv.c:xen_check_mwait
Direct callers:
  - arch/x86/xen/enlighten_pv.c:xen_check_mwait
  - drivers/xen/xen-acpi-pad.c:xen_acpi_pad_init
```
**Symbols:**

```
ffffffff810223d0-ffffffff81022403: xen_running_on_version_or_later.part.0 (STB_LOCAL)
ffffffff81022ec0-ffffffff81022edd: xen_running_on_version_or_later (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline, Transformation ⚠️</summary>

```c
bool xen_running_on_version_or_later(unsigned int major, unsigned int minor);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/x86/xen/enlighten_pv.c (ffffffff828a651a)
Location: arch/x86/xen/enlighten_pv.c:154
Inline: True
Inline callers:
  - arch/x86/xen/enlighten_pv.c:xen_check_mwait
Direct callers:
  - arch/x86/xen/enlighten_pv.c:xen_check_mwait
  - drivers/xen/xen-acpi-pad.c:xen_acpi_pad_init
```
**Symbols:**

```
ffffffff810227a0-ffffffff810227d3: xen_running_on_version_or_later.part.0 (STB_LOCAL)
ffffffff81023330-ffffffff8102334d: xen_running_on_version_or_later (STB_GLOBAL)
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
</ul>
<b>Flavor</b>
<ul>
<li>
No changes between <code>generic</code> and <code>aws</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>gcp</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>lowlatency</code> ✅
</li>
</ul>
