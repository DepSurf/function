# Function: <code>xen_reboot</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline ⚠️</summary>

```c
void xen_reboot(int reason);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/xen/enlighten.c (ffffffff8101c540)
Location: arch/x86/xen/enlighten.c:1274
Inline: True
Direct callers:
  - arch/x86/xen/enlighten.c:xen_panic_event
  - arch/x86/xen/enlighten.c:xen_emergency_restart
  - arch/x86/xen/enlighten.c:xen_crash_shutdown
  - arch/x86/xen/enlighten.c:xen_machine_power_off
  - arch/x86/xen/enlighten.c:xen_machine_halt
  - arch/x86/xen/enlighten.c:xen_restart
  - arch/x86/xen/enlighten.c:xen_hvm_crash_shutdown
  - arch/x86/xen/enlighten.c:xen_hvm_shutdown
```
**Symbols:**

```
ffffffff8101c540-ffffffff8101c5a2: xen_reboot (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
void xen_reboot(int reason);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/xen/enlighten.c (ffffffff8101b7d0)
Location: arch/x86/xen/enlighten.c:1293
Inline: True
Direct callers:
  - arch/x86/xen/enlighten.c:xen_hvm_crash_shutdown
  - arch/x86/xen/enlighten.c:xen_hvm_shutdown
  - arch/x86/xen/enlighten.c:xen_panic_event
  - arch/x86/xen/enlighten.c:xen_crash_shutdown
  - arch/x86/xen/enlighten.c:xen_machine_power_off
  - arch/x86/xen/enlighten.c:xen_machine_halt
  - arch/x86/xen/enlighten.c:xen_emergency_restart
  - arch/x86/xen/enlighten.c:xen_restart
```
**Symbols:**

```
ffffffff8101b7d0-ffffffff8101b832: xen_reboot (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
void xen_reboot(int reason);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/xen/enlighten.c (ffffffff8101bff0)
Location: arch/x86/xen/enlighten.c:1281
Inline: True
Direct callers:
  - arch/x86/xen/enlighten.c:xen_hvm_crash_shutdown
  - arch/x86/xen/enlighten.c:xen_hvm_shutdown
  - arch/x86/xen/enlighten.c:xen_panic_event
  - arch/x86/xen/enlighten.c:xen_crash_shutdown
  - arch/x86/xen/enlighten.c:xen_machine_power_off
  - arch/x86/xen/enlighten.c:xen_machine_halt
  - arch/x86/xen/enlighten.c:xen_emergency_restart
  - arch/x86/xen/enlighten.c:xen_restart
```
**Symbols:**

```
ffffffff8101bff0-ffffffff8101c054: xen_reboot (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
void xen_reboot(int reason);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/xen/enlighten.c (ffffffff81019ca0)
Location: arch/x86/xen/enlighten.c:246
Inline: True
Direct callers:
  - arch/x86/xen/enlighten.c:xen_panic_event
  - arch/x86/xen/enlighten.c:xen_emergency_restart
  - arch/x86/xen/enlighten_hvm.c:xen_hvm_crash_shutdown
  - arch/x86/xen/enlighten_hvm.c:xen_hvm_shutdown
  - arch/x86/xen/enlighten_pv.c:xen_crash_shutdown
  - arch/x86/xen/enlighten_pv.c:xen_machine_power_off
  - arch/x86/xen/enlighten_pv.c:xen_machine_halt
  - arch/x86/xen/enlighten_pv.c:xen_restart
```
**Symbols:**

```
ffffffff81019ca0-ffffffff81019d26: xen_reboot (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
void xen_reboot(int reason);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/xen/enlighten.c (ffffffff8101a540)
Location: arch/x86/xen/enlighten.c:250
Inline: True
Direct callers:
  - arch/x86/xen/enlighten.c:xen_panic_event
  - arch/x86/xen/enlighten.c:xen_emergency_restart
  - arch/x86/xen/enlighten_hvm.c:xen_hvm_crash_shutdown
  - arch/x86/xen/enlighten_hvm.c:xen_hvm_shutdown
  - arch/x86/xen/enlighten_pv.c:xen_crash_shutdown
  - arch/x86/xen/enlighten_pv.c:xen_machine_power_off
  - arch/x86/xen/enlighten_pv.c:xen_machine_halt
  - arch/x86/xen/enlighten_pv.c:xen_restart
```
**Symbols:**

```
ffffffff8101a540-ffffffff8101a5bc: xen_reboot (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
void xen_reboot(int reason);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/xen/enlighten.c (ffffffff8101aef0)
Location: arch/x86/xen/enlighten.c:258
Inline: True
Direct callers:
  - arch/x86/xen/enlighten.c:xen_panic_event
  - arch/x86/xen/enlighten.c:xen_emergency_restart
  - arch/x86/xen/enlighten_hvm.c:xen_hvm_crash_shutdown
  - arch/x86/xen/enlighten_hvm.c:xen_hvm_shutdown
  - arch/x86/xen/enlighten_pv.c:xen_crash_shutdown
  - arch/x86/xen/enlighten_pv.c:xen_machine_power_off
  - arch/x86/xen/enlighten_pv.c:xen_machine_halt
  - arch/x86/xen/enlighten_pv.c:xen_restart
```
**Symbols:**

```
ffffffff8101aef0-ffffffff8101af6c: xen_reboot (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
void xen_reboot(int reason);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/xen/enlighten.c (ffffffff8101b6c0)
Location: arch/x86/xen/enlighten.c:260
Inline: True
Direct callers:
  - arch/x86/xen/enlighten.c:xen_panic_event
  - arch/x86/xen/enlighten.c:xen_emergency_restart
  - arch/x86/xen/enlighten_hvm.c:xen_hvm_crash_shutdown
  - arch/x86/xen/enlighten_hvm.c:xen_hvm_shutdown
  - arch/x86/xen/enlighten_pv.c:xen_crash_shutdown
  - arch/x86/xen/enlighten_pv.c:xen_machine_power_off
  - arch/x86/xen/enlighten_pv.c:xen_machine_halt
  - arch/x86/xen/enlighten_pv.c:xen_restart
```
**Symbols:**

```
ffffffff8101b6c0-ffffffff8101b73c: xen_reboot (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
void xen_reboot(int reason);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/xen/enlighten.c (ffffffff8101d1f0)
Location: arch/x86/xen/enlighten.c:260
Inline: True
Direct callers:
  - arch/x86/xen/enlighten.c:xen_panic_event
  - arch/x86/xen/enlighten.c:xen_emergency_restart
  - arch/x86/xen/enlighten_hvm.c:xen_hvm_crash_shutdown
  - arch/x86/xen/enlighten_hvm.c:xen_hvm_shutdown
  - arch/x86/xen/enlighten_pv.c:xen_crash_shutdown
  - arch/x86/xen/enlighten_pv.c:xen_machine_power_off
  - arch/x86/xen/enlighten_pv.c:xen_machine_halt
  - arch/x86/xen/enlighten_pv.c:xen_restart
```
**Symbols:**

```
ffffffff8101d1f0-ffffffff8101d26b: xen_reboot (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
void xen_reboot(int reason);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/xen/enlighten.c (ffffffff8101db70)
Location: arch/x86/xen/enlighten.c:260
Inline: True
Direct callers:
  - arch/x86/xen/enlighten.c:xen_emergency_restart
  - arch/x86/xen/enlighten_hvm.c:xen_hvm_crash_shutdown
  - arch/x86/xen/enlighten_hvm.c:xen_hvm_shutdown
  - arch/x86/xen/enlighten_pv.c:xen_crash_shutdown
  - arch/x86/xen/enlighten_pv.c:xen_machine_power_off
  - arch/x86/xen/enlighten_pv.c:xen_machine_halt
  - arch/x86/xen/enlighten_pv.c:xen_restart
```
**Symbols:**

```
ffffffff8101db70-ffffffff8101dbeb: xen_reboot (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
void xen_reboot(int reason);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/xen/enlighten.c (ffffffff8101ff60)
Location: arch/x86/xen/enlighten.c:260
Inline: True
Direct callers:
  - arch/x86/xen/enlighten.c:xen_emergency_restart
  - arch/x86/xen/enlighten_hvm.c:xen_hvm_crash_shutdown
  - arch/x86/xen/enlighten_hvm.c:xen_hvm_shutdown
  - arch/x86/xen/enlighten_pv.c:xen_crash_shutdown
  - arch/x86/xen/enlighten_pv.c:xen_machine_power_off
  - arch/x86/xen/enlighten_pv.c:xen_machine_halt
  - arch/x86/xen/enlighten_pv.c:xen_restart
```
**Symbols:**

```
ffffffff8101ff60-ffffffff8101ffd9: xen_reboot (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
void xen_reboot(int reason);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/xen/enlighten.c (ffffffff81020a00)
Location: arch/x86/xen/enlighten.c:260
Inline: True
Direct callers:
  - arch/x86/xen/enlighten.c:xen_emergency_restart
  - arch/x86/xen/enlighten_hvm.c:xen_hvm_crash_shutdown
  - arch/x86/xen/enlighten_hvm.c:xen_hvm_shutdown
  - arch/x86/xen/enlighten_pv.c:xen_crash_shutdown
  - arch/x86/xen/enlighten_pv.c:xen_machine_power_off
  - arch/x86/xen/enlighten_pv.c:xen_machine_halt
  - arch/x86/xen/enlighten_pv.c:xen_restart
```
**Symbols:**

```
ffffffff81020a00-ffffffff81020a79: xen_reboot (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
void xen_reboot(int reason);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/xen/enlighten.c (ffffffff81022da0)
Location: arch/x86/xen/enlighten.c:260
Inline: True
Direct callers:
  - arch/x86/xen/enlighten.c:xen_emergency_restart
  - arch/x86/xen/enlighten_hvm.c:xen_hvm_crash_shutdown
  - arch/x86/xen/enlighten_hvm.c:xen_hvm_shutdown
  - arch/x86/xen/enlighten_pv.c:xen_crash_shutdown
  - arch/x86/xen/enlighten_pv.c:xen_machine_power_off
  - arch/x86/xen/enlighten_pv.c:xen_machine_halt
  - arch/x86/xen/enlighten_pv.c:xen_restart
```
**Symbols:**

```
ffffffff81022da0-ffffffff81022e19: xen_reboot (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void xen_reboot(int reason);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/xen/enlighten.c (ffffffff81026ee0)
Location: arch/x86/xen/enlighten.c:303
Inline: False
Direct callers:
  - arch/x86/xen/enlighten.c:xen_emergency_restart
  - arch/x86/xen/enlighten_hvm.c:xen_hvm_crash_shutdown
  - arch/x86/xen/enlighten_hvm.c:xen_hvm_shutdown
  - arch/x86/xen/enlighten_pv.c:xen_crash_shutdown
  - arch/x86/xen/enlighten_pv.c:xen_machine_power_off
  - arch/x86/xen/enlighten_pv.c:xen_machine_halt
  - arch/x86/xen/enlighten_pv.c:xen_restart
  - drivers/xen/efi.c:xen_efi_reset_system
  - drivers/xen/efi.c:xen_efi_reset_system
```
**Symbols:**

```
ffffffff81026ee0-ffffffff81026f59: xen_reboot (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void xen_reboot(int reason);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/xen/enlighten.c (ffffffff8102b070)
Location: arch/x86/xen/enlighten.c:239
Inline: False
Direct callers:
  - arch/x86/xen/enlighten.c:xen_emergency_restart
  - arch/x86/xen/enlighten_hvm.c:xen_hvm_crash_shutdown
  - arch/x86/xen/enlighten_pv.c:xen_crash_shutdown
  - arch/x86/xen/enlighten_pv.c:xen_machine_power_off
  - arch/x86/xen/enlighten_pv.c:xen_machine_halt
  - arch/x86/xen/enlighten_pv.c:xen_restart
```
**Symbols:**

```
ffffffff8102b070-ffffffff8102b0f6: xen_reboot (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void xen_reboot(int reason);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/xen/enlighten.c (ffffffff81031d20)
Location: arch/x86/xen/enlighten.c:239
Inline: False
Direct callers:
  - arch/x86/xen/enlighten.c:xen_emergency_restart
  - arch/x86/xen/enlighten_hvm.c:xen_hvm_crash_shutdown
  - arch/x86/xen/enlighten_pv.c:xen_crash_shutdown
  - arch/x86/xen/enlighten_pv.c:xen_machine_power_off
  - arch/x86/xen/enlighten_pv.c:xen_machine_halt
  - arch/x86/xen/enlighten_pv.c:xen_restart
```
**Symbols:**

```
ffffffff81031d20-ffffffff81031dae: xen_reboot (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void xen_reboot(int reason);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/xen/enlighten.c (ffffffff81031d20)
Location: arch/x86/xen/enlighten.c:239
Inline: False
Direct callers:
  - arch/x86/xen/enlighten.c:xen_emergency_restart
  - arch/x86/xen/enlighten_hvm.c:xen_hvm_crash_shutdown
  - arch/x86/xen/enlighten_pv.c:xen_crash_shutdown
  - arch/x86/xen/enlighten_pv.c:xen_machine_power_off
  - arch/x86/xen/enlighten_pv.c:xen_machine_halt
  - arch/x86/xen/enlighten_pv.c:xen_restart
```
**Symbols:**

```
ffffffff81031d20-ffffffff81031dae: xen_reboot (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void xen_reboot(int reason);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/xen/enlighten.c (ffffffff81038010)
Location: arch/x86/xen/enlighten.c:243
Inline: False
Direct callers:
  - arch/x86/xen/enlighten.c:xen_emergency_restart
  - arch/x86/xen/enlighten_hvm.c:xen_hvm_crash_shutdown
  - arch/x86/xen/enlighten_pv.c:xen_crash_shutdown
  - arch/x86/xen/enlighten_pv.c:xen_machine_power_off
  - arch/x86/xen/enlighten_pv.c:xen_machine_halt
  - arch/x86/xen/enlighten_pv.c:xen_restart
```
**Symbols:**

```
ffffffff81038010-ffffffff8103809e: xen_reboot (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Selective Inline ⚠️</summary>

```c
void xen_reboot(int reason);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/arm/xen/enlighten.c (ffff8000100f0200)
Location: arch/arm/xen/enlighten.c:174
Inline: True
Direct callers:
  - arch/arm/xen/enlighten.c:xen_power_off
  - arch/arm/xen/enlighten.c:xen_restart
```
**Symbols:**

```
ffff8000100f0200-ffff8000100f0264: xen_reboot (STB_GLOBAL)
```
</details>
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
<summary>In <code>aws</code>: Selective Inline ⚠️</summary>

```c
void xen_reboot(int reason);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/xen/enlighten.c (ffffffff8101db70)
Location: arch/x86/xen/enlighten.c:260
Inline: True
Direct callers:
  - arch/x86/xen/enlighten.c:xen_emergency_restart
  - arch/x86/xen/enlighten_hvm.c:xen_hvm_crash_shutdown
  - arch/x86/xen/enlighten_hvm.c:xen_hvm_shutdown
  - arch/x86/xen/enlighten_pv.c:xen_crash_shutdown
  - arch/x86/xen/enlighten_pv.c:xen_machine_power_off
  - arch/x86/xen/enlighten_pv.c:xen_machine_halt
  - arch/x86/xen/enlighten_pv.c:xen_restart
```
**Symbols:**

```
ffffffff8101db70-ffffffff8101dbeb: xen_reboot (STB_GLOBAL)
```
</details>
</li>
<li>
In <code>azure</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
void xen_reboot(int reason);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/xen/enlighten.c (ffffffff8101db30)
Location: arch/x86/xen/enlighten.c:260
Inline: True
Direct callers:
  - arch/x86/xen/enlighten.c:xen_emergency_restart
  - arch/x86/xen/enlighten_hvm.c:xen_hvm_crash_shutdown
  - arch/x86/xen/enlighten_hvm.c:xen_hvm_shutdown
  - arch/x86/xen/enlighten_pv.c:xen_crash_shutdown
  - arch/x86/xen/enlighten_pv.c:xen_machine_power_off
  - arch/x86/xen/enlighten_pv.c:xen_machine_halt
  - arch/x86/xen/enlighten_pv.c:xen_restart
```
**Symbols:**

```
ffffffff8101db30-ffffffff8101dbab: xen_reboot (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
void xen_reboot(int reason);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/xen/enlighten.c (ffffffff8101dd80)
Location: arch/x86/xen/enlighten.c:260
Inline: True
Direct callers:
  - arch/x86/xen/enlighten.c:xen_emergency_restart
  - arch/x86/xen/enlighten_hvm.c:xen_hvm_crash_shutdown
  - arch/x86/xen/enlighten_hvm.c:xen_hvm_shutdown
  - arch/x86/xen/enlighten_pv.c:xen_crash_shutdown
  - arch/x86/xen/enlighten_pv.c:xen_machine_power_off
  - arch/x86/xen/enlighten_pv.c:xen_machine_halt
  - arch/x86/xen/enlighten_pv.c:xen_restart
```
**Symbols:**

```
ffffffff8101dd80-ffffffff8101ddfb: xen_reboot (STB_GLOBAL)
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
