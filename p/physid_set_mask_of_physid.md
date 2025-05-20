# Function: <code>physid_set_mask_of_physid</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Duplicate, Selective Inline, Transformation ⚠️</summary>

```c
void physid_set_mask_of_physid(int physid, physid_mask_t *map);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/x86/xen/apic.c (ffffffff81025ad0)
Location: arch/x86/include/asm/mpspec.h:142
Inline: False
```
```
In arch/x86/kernel/smpboot.c (ffffffff8107ce81)
Location: arch/x86/include/asm/mpspec.h:142
Inline: True
Direct callers:
  - arch/x86/kernel/smpboot.c:disable_smp
  - arch/x86/kernel/smpboot.c:disable_smp
```
```
In arch/x86/kernel/apic/apic.c (ffffffff81f71c92)
Location: arch/x86/include/asm/mpspec.h:142
Inline: True
Inline callers:
  - arch/x86/kernel/apic/apic.c:apic_bsp_setup
```
```
In arch/x86/kernel/apic/apic_noop.c (ffffffff810549b0)
Location: arch/x86/include/asm/mpspec.h:142
Inline: False
```
**Symbols:**

```
ffffffff81025ad0-ffffffff81025b0c: physid_set_mask_of_physid (STB_LOCAL)
ffffffff8107ce81-ffffffff8107cea6: physid_set_mask_of_physid.constprop.9 (STB_LOCAL)
ffffffff810549b0-ffffffff810549ec: physid_set_mask_of_physid (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Duplicate, Selective Inline, Transformation ⚠️</summary>

```c
void physid_set_mask_of_physid(int physid, physid_mask_t *map);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/x86/xen/apic.c (ffffffff81024ed0)
Location: arch/x86/include/asm/mpspec.h:142
Inline: False
```
```
In arch/x86/kernel/smpboot.c (ffffffff8107e95d)
Location: arch/x86/include/asm/mpspec.h:142
Inline: True
Direct callers:
  - arch/x86/kernel/smpboot.c:disable_smp
  - arch/x86/kernel/smpboot.c:disable_smp
```
```
In arch/x86/kernel/apic/apic.c (ffffffff81f9a47e)
Location: arch/x86/include/asm/mpspec.h:142
Inline: True
Inline callers:
  - arch/x86/kernel/apic/apic.c:apic_bsp_setup
```
```
In arch/x86/kernel/apic/apic_noop.c (ffffffff81054b30)
Location: arch/x86/include/asm/mpspec.h:142
Inline: False
```
**Symbols:**

```
ffffffff81024ed0-ffffffff81024f0c: physid_set_mask_of_physid (STB_LOCAL)
ffffffff8107e95d-ffffffff8107e982: physid_set_mask_of_physid.constprop.9 (STB_LOCAL)
ffffffff81054b30-ffffffff81054b6c: physid_set_mask_of_physid (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Duplicate, Selective Inline, Transformation ⚠️</summary>

```c
void physid_set_mask_of_physid(int physid, physid_mask_t *map);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/x86/xen/apic.c (ffffffff81025620)
Location: arch/x86/include/asm/mpspec.h:143
Inline: False
```
```
In arch/x86/kernel/smpboot.c (ffffffff81082ff4)
Location: arch/x86/include/asm/mpspec.h:143
Inline: True
Direct callers:
  - arch/x86/kernel/smpboot.c:disable_smp
  - arch/x86/kernel/smpboot.c:disable_smp
```
```
In arch/x86/kernel/apic/apic.c (ffffffff81fd5945)
Location: arch/x86/include/asm/mpspec.h:143
Inline: True
Inline callers:
  - arch/x86/kernel/apic/apic.c:apic_bsp_setup
```
```
In arch/x86/kernel/apic/apic_noop.c (ffffffff81057910)
Location: arch/x86/include/asm/mpspec.h:143
Inline: False
```
**Symbols:**

```
ffffffff81025620-ffffffff8102565c: physid_set_mask_of_physid (STB_LOCAL)
ffffffff81082ff4-ffffffff81083019: physid_set_mask_of_physid.constprop.7 (STB_LOCAL)
ffffffff81057910-ffffffff8105794c: physid_set_mask_of_physid (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Duplicate, Selective Inline, Transformation ⚠️</summary>

```c
void physid_set_mask_of_physid(int physid, physid_mask_t *map);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/x86/xen/apic.c (ffffffff8101c0a0)
Location: arch/x86/include/asm/mpspec.h:143
Inline: False
```
```
In arch/x86/kernel/smpboot.c (ffffffff81054bdc)
Location: arch/x86/include/asm/mpspec.h:143
Inline: True
Direct callers:
  - arch/x86/kernel/smpboot.c:disable_smp
  - arch/x86/kernel/smpboot.c:disable_smp
```
```
In arch/x86/kernel/apic/apic.c (ffffffff820b668b)
Location: arch/x86/include/asm/mpspec.h:143
Inline: True
Inline callers:
  - arch/x86/kernel/apic/apic.c:apic_bsp_setup
```
```
In arch/x86/kernel/apic/apic_noop.c (ffffffff81057190)
Location: arch/x86/include/asm/mpspec.h:143
Inline: False
```
**Symbols:**

```
ffffffff8101c0a0-ffffffff8101c0dc: physid_set_mask_of_physid (STB_LOCAL)
ffffffff81054bdc-ffffffff81054c01: physid_set_mask_of_physid.constprop.7 (STB_LOCAL)
ffffffff81057190-ffffffff810571cc: physid_set_mask_of_physid (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Duplicate, Selective Inline, Transformation ⚠️</summary>

```c
void physid_set_mask_of_physid(int physid, physid_mask_t *map);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/x86/xen/apic.c (ffffffff8101cd20)
Location: arch/x86/include/asm/mpspec.h:143
Inline: False
```
```
In arch/x86/kernel/smpboot.c (ffffffff810589a8)
Location: arch/x86/include/asm/mpspec.h:143
Inline: True
Direct callers:
  - arch/x86/kernel/smpboot.c:disable_smp
  - arch/x86/kernel/smpboot.c:disable_smp
```
```
In arch/x86/kernel/apic/apic.c (ffffffff826bceba)
Location: arch/x86/include/asm/mpspec.h:143
Inline: True
Inline callers:
  - arch/x86/kernel/apic/apic.c:apic_bsp_setup
```
```
In arch/x86/kernel/apic/apic_noop.c (ffffffff8105ae20)
Location: arch/x86/include/asm/mpspec.h:143
Inline: False
```
**Symbols:**

```
ffffffff8101cd20-ffffffff8101cd5c: physid_set_mask_of_physid (STB_LOCAL)
ffffffff810589a8-ffffffff810589cd: physid_set_mask_of_physid.constprop.6 (STB_LOCAL)
ffffffff8105ae20-ffffffff8105ae5c: physid_set_mask_of_physid (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Duplicate, Selective Inline, Transformation ⚠️</summary>

```c
void physid_set_mask_of_physid(int physid, physid_mask_t *map);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/x86/xen/apic.c (ffffffff8101d730)
Location: arch/x86/include/asm/mpspec.h:143
Inline: False
```
```
In arch/x86/kernel/smpboot.c (ffffffff8105b629)
Location: arch/x86/include/asm/mpspec.h:143
Inline: True
Direct callers:
  - arch/x86/kernel/smpboot.c:disable_smp
  - arch/x86/kernel/smpboot.c:disable_smp
```
```
In arch/x86/kernel/apic/apic.c (ffffffff826e6c71)
Location: arch/x86/include/asm/mpspec.h:143
Inline: True
Inline callers:
  - arch/x86/kernel/apic/apic.c:apic_bsp_setup
```
```
In arch/x86/kernel/apic/apic_noop.c (ffffffff8105de20)
Location: arch/x86/include/asm/mpspec.h:143
Inline: False
```
**Symbols:**

```
ffffffff8101d730-ffffffff8101d76c: physid_set_mask_of_physid (STB_LOCAL)
ffffffff8105b629-ffffffff8105b64e: physid_set_mask_of_physid.constprop.6 (STB_LOCAL)
ffffffff8105de20-ffffffff8105de5c: physid_set_mask_of_physid (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Duplicate, Selective Inline, Transformation ⚠️</summary>

```c
void physid_set_mask_of_physid(int physid, physid_mask_t *map);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/x86/xen/apic.c (ffffffff8101cfc0)
Location: arch/x86/include/asm/mpspec.h:143
Inline: False
```
```
In arch/x86/kernel/smpboot.c (ffffffff810612b3)
Location: arch/x86/include/asm/mpspec.h:143
Inline: True
Direct callers:
  - arch/x86/kernel/smpboot.c:disable_smp
  - arch/x86/kernel/smpboot.c:disable_smp
```
```
In arch/x86/kernel/apic/apic.c (ffffffff8289d7ba)
Location: arch/x86/include/asm/mpspec.h:143
Inline: True
Inline callers:
  - arch/x86/kernel/apic/apic.c:apic_bsp_setup
```
```
In arch/x86/kernel/apic/apic_noop.c (ffffffff81063ab0)
Location: arch/x86/include/asm/mpspec.h:143
Inline: False
```
**Symbols:**

```
ffffffff8101cfc0-ffffffff8101cffc: physid_set_mask_of_physid (STB_LOCAL)
ffffffff810612b3-ffffffff810612d8: physid_set_mask_of_physid.constprop.8 (STB_LOCAL)
ffffffff81063ab0-ffffffff81063aec: physid_set_mask_of_physid (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Duplicate, Selective Inline ⚠️</summary>

```c
void physid_set_mask_of_physid(int physid, physid_mask_t *map);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/xen/apic.c (ffffffff8101ead0)
Location: arch/x86/include/asm/mpspec.h:143
Inline: False
```
```
In arch/x86/kernel/smpboot.c (ffffffff828b2bd8)
Location: arch/x86/include/asm/mpspec.h:143
Inline: True
Inline callers:
  - arch/x86/kernel/smpboot.c:disable_smp
  - arch/x86/kernel/smpboot.c:disable_smp
```
```
In arch/x86/kernel/apic/apic.c (ffffffff828b535e)
Location: arch/x86/include/asm/mpspec.h:143
Inline: True
Inline callers:
  - arch/x86/kernel/apic/apic.c:apic_intr_mode_init
```
```
In arch/x86/kernel/apic/apic_noop.c (ffffffff810671b0)
Location: arch/x86/include/asm/mpspec.h:143
Inline: False
```
**Symbols:**

```
ffffffff8101ead0-ffffffff8101eb07: physid_set_mask_of_physid (STB_LOCAL)
ffffffff810671b0-ffffffff810671e7: physid_set_mask_of_physid (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Duplicate, Selective Inline ⚠️</summary>

```c
void physid_set_mask_of_physid(int physid, physid_mask_t *map);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/xen/apic.c (ffffffff8101f470)
Location: arch/x86/include/asm/mpspec.h:143
Inline: False
```
```
In arch/x86/kernel/smpboot.c (ffffffff828b602b)
Location: arch/x86/include/asm/mpspec.h:143
Inline: True
Inline callers:
  - arch/x86/kernel/smpboot.c:disable_smp
  - arch/x86/kernel/smpboot.c:disable_smp
```
```
In arch/x86/kernel/apic/apic.c (ffffffff828b8899)
Location: arch/x86/include/asm/mpspec.h:143
Inline: True
Inline callers:
  - arch/x86/kernel/apic/apic.c:apic_intr_mode_init
```
```
In arch/x86/kernel/apic/apic_noop.c (ffffffff81067820)
Location: arch/x86/include/asm/mpspec.h:143
Inline: False
```
**Symbols:**

```
ffffffff8101f470-ffffffff8101f4a7: physid_set_mask_of_physid (STB_LOCAL)
ffffffff81067820-ffffffff81067857: physid_set_mask_of_physid (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Duplicate, Selective Inline ⚠️</summary>

```c
void physid_set_mask_of_physid(int physid, physid_mask_t *map);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/xen/apic.c (ffffffff81021a30)
Location: arch/x86/include/asm/mpspec.h:143
Inline: False
```
```
In arch/x86/kernel/smpboot.c (ffffffff82cdb23a)
Location: arch/x86/include/asm/mpspec.h:143
Inline: True
Inline callers:
  - arch/x86/kernel/smpboot.c:disable_smp
  - arch/x86/kernel/smpboot.c:disable_smp
```
```
In arch/x86/kernel/apic/apic.c (ffffffff82cdd926)
Location: arch/x86/include/asm/mpspec.h:143
Inline: True
Inline callers:
  - arch/x86/kernel/apic/apic.c:apic_intr_mode_init
```
```
In arch/x86/kernel/apic/apic_noop.c (ffffffff8106e530)
Location: arch/x86/include/asm/mpspec.h:143
Inline: False
```
**Symbols:**

```
ffffffff81021a30-ffffffff81021a67: physid_set_mask_of_physid (STB_LOCAL)
ffffffff8106e530-ffffffff8106e567: physid_set_mask_of_physid (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Duplicate, Selective Inline ⚠️</summary>

```c
void physid_set_mask_of_physid(int physid, physid_mask_t *map);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/xen/apic.c (ffffffff81022110)
Location: arch/x86/include/asm/mpspec.h:133
Inline: False
```
```
In arch/x86/kernel/smpboot.c (ffffffff82fc768e)
Location: arch/x86/include/asm/mpspec.h:133
Inline: True
Inline callers:
  - arch/x86/kernel/smpboot.c:disable_smp
  - arch/x86/kernel/smpboot.c:disable_smp
```
```
In arch/x86/kernel/apic/apic.c (ffffffff82fc9cdf)
Location: arch/x86/include/asm/mpspec.h:133
Inline: True
Inline callers:
  - arch/x86/kernel/apic/apic.c:apic_intr_mode_init
```
```
In arch/x86/kernel/apic/apic_noop.c (ffffffff8106f9b0)
Location: arch/x86/include/asm/mpspec.h:133
Inline: False
```
**Symbols:**

```
ffffffff81022110-ffffffff81022147: physid_set_mask_of_physid (STB_LOCAL)
ffffffff8106f9b0-ffffffff8106f9e7: physid_set_mask_of_physid (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Duplicate, Selective Inline ⚠️</summary>

```c
void physid_set_mask_of_physid(int physid, physid_mask_t *map);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/xen/apic.c (ffffffff810244a0)
Location: arch/x86/include/asm/mpspec.h:133
Inline: False
```
```
In arch/x86/kernel/smpboot.c (ffffffff831d1eac)
Location: arch/x86/include/asm/mpspec.h:133
Inline: True
Inline callers:
  - arch/x86/kernel/smpboot.c:disable_smp
  - arch/x86/kernel/smpboot.c:disable_smp
```
```
In arch/x86/kernel/apic/apic.c (ffffffff831d45f3)
Location: arch/x86/include/asm/mpspec.h:133
Inline: True
Inline callers:
  - arch/x86/kernel/apic/apic.c:apic_intr_mode_init
```
```
In arch/x86/kernel/apic/apic_noop.c (ffffffff810704e0)
Location: arch/x86/include/asm/mpspec.h:133
Inline: False
```
**Symbols:**

```
ffffffff810244a0-ffffffff810244d7: physid_set_mask_of_physid (STB_LOCAL)
ffffffff810704e0-ffffffff81070517: physid_set_mask_of_physid (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Duplicate, Selective Inline ⚠️</summary>

```c
void physid_set_mask_of_physid(int physid, physid_mask_t *map);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/xen/apic.c (ffffffff81028880)
Location: arch/x86/include/asm/mpspec.h:133
Inline: False
```
```
In arch/x86/kernel/smpboot.c (ffffffff832b4630)
Location: arch/x86/include/asm/mpspec.h:133
Inline: True
Inline callers:
  - arch/x86/kernel/smpboot.c:disable_smp
  - arch/x86/kernel/smpboot.c:disable_smp
```
```
In arch/x86/kernel/apic/apic.c (ffffffff832b717f)
Location: arch/x86/include/asm/mpspec.h:133
Inline: True
Inline callers:
  - arch/x86/kernel/apic/apic.c:apic_intr_mode_init
```
```
In arch/x86/kernel/apic/apic_noop.c (ffffffff8107c080)
Location: arch/x86/include/asm/mpspec.h:133
Inline: False
```
**Symbols:**

```
ffffffff81028880-ffffffff810288b7: physid_set_mask_of_physid (STB_LOCAL)
ffffffff8107c080-ffffffff8107c0b7: physid_set_mask_of_physid (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Duplicate, Selective Inline, Transformation ⚠️</summary>

```c
void physid_set_mask_of_physid(int physid, physid_mask_t *map);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/x86/xen/apic.c (ffffffff8102d050)
Location: arch/x86/include/asm/mpspec.h:133
Inline: False
```
```
In arch/x86/kernel/smpboot.c (ffffffff81e4c84c)
Location: arch/x86/include/asm/mpspec.h:133
Inline: True
Direct callers:
  - arch/x86/kernel/smpboot.c:disable_smp
  - arch/x86/kernel/smpboot.c:disable_smp
```
```
In arch/x86/kernel/apic/apic.c (ffffffff83468ce5)
Location: arch/x86/include/asm/mpspec.h:133
Inline: True
Inline callers:
  - arch/x86/kernel/apic/apic.c:apic_intr_mode_init
```
```
In arch/x86/kernel/apic/apic_noop.c (ffffffff8108b380)
Location: arch/x86/include/asm/mpspec.h:133
Inline: False
```
**Symbols:**

```
ffffffff8102d050-ffffffff8102d095: physid_set_mask_of_physid (STB_LOCAL)
ffffffff81e4c84c-ffffffff81e4c876: physid_set_mask_of_physid.constprop.0 (STB_LOCAL)
ffffffff8108b380-ffffffff8108b3c5: physid_set_mask_of_physid (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Duplicate, Selective Inline ⚠️</summary>

```c
void physid_set_mask_of_physid(int physid, physid_mask_t *map);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/xen/apic.c (ffffffff81034390)
Location: arch/x86/include/asm/mpspec.h:133
Inline: False
```
```
In arch/x86/kernel/smpboot.c (ffffffff83e897b0)
Location: arch/x86/include/asm/mpspec.h:133
Inline: True
Inline callers:
  - arch/x86/kernel/smpboot.c:disable_smp
  - arch/x86/kernel/smpboot.c:disable_smp
```
```
In arch/x86/kernel/apic/apic.c (ffffffff83e8d5c1)
Location: arch/x86/include/asm/mpspec.h:133
Inline: True
Inline callers:
  - arch/x86/kernel/apic/apic.c:apic_intr_mode_init
```
```
In arch/x86/kernel/apic/apic_noop.c (ffffffff8109f6d0)
Location: arch/x86/include/asm/mpspec.h:133
Inline: False
```
**Symbols:**

```
ffffffff81034390-ffffffff810343d5: physid_set_mask_of_physid (STB_LOCAL)
ffffffff8109f6d0-ffffffff8109f715: physid_set_mask_of_physid (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Duplicate, Selective Inline ⚠️</summary>

```c
void physid_set_mask_of_physid(int physid, physid_mask_t *map);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/xen/apic.c (ffffffff81034320)
Location: arch/x86/include/asm/mpspec.h:133
Inline: False
```
```
In arch/x86/kernel/smpboot.c (ffffffff836ace70)
Location: arch/x86/include/asm/mpspec.h:133
Inline: True
Inline callers:
  - arch/x86/kernel/smpboot.c:disable_smp
  - arch/x86/kernel/smpboot.c:disable_smp
```
```
In arch/x86/kernel/apic/apic.c (ffffffff836b0e2f)
Location: arch/x86/include/asm/mpspec.h:133
Inline: True
Inline callers:
  - arch/x86/kernel/apic/apic.c:apic_intr_mode_init
```
```
In arch/x86/kernel/apic/apic_noop.c (ffffffff810a2660)
Location: arch/x86/include/asm/mpspec.h:133
Inline: False
```
**Symbols:**

```
ffffffff81034320-ffffffff81034365: physid_set_mask_of_physid (STB_LOCAL)
ffffffff810a2660-ffffffff810a26a5: physid_set_mask_of_physid (STB_LOCAL)
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
In arch/x86/kernel/smpboot.c (ffffffff838dd3a0)
Location: arch/x86/include/asm/mpspec.h:104
Inline: True
Inline callers:
  - arch/x86/kernel/smpboot.c:disable_smp
  - arch/x86/kernel/smpboot.c:disable_smp
```
```
In arch/x86/kernel/apic/apic.c (ffffffff838e1517)
Location: arch/x86/include/asm/mpspec.h:104
Inline: True
Inline callers:
  - arch/x86/kernel/apic/apic.c:apic_intr_mode_init
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
<summary>In <code>aws</code>: Duplicate, Selective Inline ⚠️</summary>

```c
void physid_set_mask_of_physid(int physid, physid_mask_t *map);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/xen/apic.c (ffffffff8101f5d0)
Location: arch/x86/include/asm/mpspec.h:143
Inline: False
```
```
In arch/x86/kernel/smpboot.c (ffffffff828a4037)
Location: arch/x86/include/asm/mpspec.h:143
Inline: True
Inline callers:
  - arch/x86/kernel/smpboot.c:disable_smp
  - arch/x86/kernel/smpboot.c:disable_smp
```
```
In arch/x86/kernel/apic/apic.c (ffffffff828a68a0)
Location: arch/x86/include/asm/mpspec.h:143
Inline: True
Inline callers:
  - arch/x86/kernel/apic/apic.c:apic_intr_mode_init
```
```
In arch/x86/kernel/apic/apic_noop.c (ffffffff81067310)
Location: arch/x86/include/asm/mpspec.h:143
Inline: False
```
**Symbols:**

```
ffffffff8101f5d0-ffffffff8101f607: physid_set_mask_of_physid (STB_LOCAL)
ffffffff81067310-ffffffff81067347: physid_set_mask_of_physid (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Duplicate, Selective Inline ⚠️</summary>

```c
void physid_set_mask_of_physid(int physid, physid_mask_t *map);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/smpboot.c (ffffffff8289c179)
Location: arch/x86/include/asm/mpspec.h:143
Inline: True
Inline callers:
  - arch/x86/kernel/smpboot.c:disable_smp
  - arch/x86/kernel/smpboot.c:disable_smp
```
```
In arch/x86/kernel/apic/apic.c (ffffffff8289e9c0)
Location: arch/x86/include/asm/mpspec.h:143
Inline: True
Inline callers:
  - arch/x86/kernel/apic/apic.c:apic_intr_mode_init
```
```
In arch/x86/kernel/apic/apic_noop.c (ffffffff810576d0)
Location: arch/x86/include/asm/mpspec.h:143
Inline: False
```
**Symbols:**

```
ffffffff810576d0-ffffffff81057707: physid_set_mask_of_physid (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Duplicate, Selective Inline ⚠️</summary>

```c
void physid_set_mask_of_physid(int physid, physid_mask_t *map);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/xen/apic.c (ffffffff8101f430)
Location: arch/x86/include/asm/mpspec.h:143
Inline: False
```
```
In arch/x86/kernel/smpboot.c (ffffffff828b6f47)
Location: arch/x86/include/asm/mpspec.h:143
Inline: True
Inline callers:
  - arch/x86/kernel/smpboot.c:disable_smp
  - arch/x86/kernel/smpboot.c:disable_smp
```
```
In arch/x86/kernel/apic/apic.c (ffffffff828b97b0)
Location: arch/x86/include/asm/mpspec.h:143
Inline: True
Inline callers:
  - arch/x86/kernel/apic/apic.c:apic_intr_mode_init
```
```
In arch/x86/kernel/apic/apic_noop.c (ffffffff810677c0)
Location: arch/x86/include/asm/mpspec.h:143
Inline: False
```
**Symbols:**

```
ffffffff8101f430-ffffffff8101f467: physid_set_mask_of_physid (STB_LOCAL)
ffffffff810677c0-ffffffff810677f7: physid_set_mask_of_physid (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Duplicate, Selective Inline ⚠️</summary>

```c
void physid_set_mask_of_physid(int physid, physid_mask_t *map);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/xen/apic.c (ffffffff8101f680)
Location: arch/x86/include/asm/mpspec.h:143
Inline: False
```
```
In arch/x86/kernel/smpboot.c (ffffffff828b702e)
Location: arch/x86/include/asm/mpspec.h:143
Inline: True
Inline callers:
  - arch/x86/kernel/smpboot.c:disable_smp
  - arch/x86/kernel/smpboot.c:disable_smp
```
```
In arch/x86/kernel/apic/apic.c (ffffffff828b98b1)
Location: arch/x86/include/asm/mpspec.h:143
Inline: True
Inline callers:
  - arch/x86/kernel/apic/apic.c:apic_intr_mode_init
```
```
In arch/x86/kernel/apic/apic_noop.c (ffffffff81068da0)
Location: arch/x86/include/asm/mpspec.h:143
Inline: False
```
**Symbols:**

```
ffffffff8101f680-ffffffff8101f6b7: physid_set_mask_of_physid (STB_LOCAL)
ffffffff81068da0-ffffffff81068dd7: physid_set_mask_of_physid (STB_LOCAL)
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
