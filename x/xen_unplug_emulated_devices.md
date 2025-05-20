# Function: <code>xen_unplug_emulated_devices</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void xen_unplug_emulated_devices();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/xen/platform-pci-unplug.c (ffffffff81024530)
Location: arch/x86/xen/platform-pci-unplug.c:145
Inline: False
Direct callers:
  - arch/x86/xen/suspend.c:xen_arch_post_suspend
```
**Symbols:**

```
ffffffff81024530-ffffffff8102460c: xen_unplug_emulated_devices (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void xen_unplug_emulated_devices();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/xen/platform-pci-unplug.c (ffffffff810237f0)
Location: arch/x86/xen/platform-pci-unplug.c:145
Inline: False
Direct callers:
  - arch/x86/xen/suspend.c:xen_arch_post_suspend
```
**Symbols:**

```
ffffffff810237f0-ffffffff810238cc: xen_unplug_emulated_devices (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void xen_unplug_emulated_devices();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/xen/platform-pci-unplug.c (ffffffff81023f20)
Location: arch/x86/xen/platform-pci-unplug.c:145
Inline: False
Direct callers:
  - arch/x86/xen/suspend.c:xen_arch_post_suspend
```
**Symbols:**

```
ffffffff81023f20-ffffffff81023ffc: xen_unplug_emulated_devices (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void xen_unplug_emulated_devices();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/xen/platform-pci-unplug.c (ffffffff8101b730)
Location: arch/x86/xen/platform-pci-unplug.c:145
Inline: False
Direct callers:
  - arch/x86/xen/suspend_hvm.c:xen_hvm_post_suspend
```
**Symbols:**

```
ffffffff8101b730-ffffffff8101b806: xen_unplug_emulated_devices (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void xen_unplug_emulated_devices();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/xen/platform-pci-unplug.c (ffffffff8101c410)
Location: arch/x86/xen/platform-pci-unplug.c:145
Inline: False
Direct callers:
  - arch/x86/xen/suspend_hvm.c:xen_hvm_post_suspend
```
**Symbols:**

```
ffffffff8101c410-ffffffff8101c4e6: xen_unplug_emulated_devices (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Transformation ⚠️</summary>

```c
void xen_unplug_emulated_devices();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/xen/platform-pci-unplug.c (0)
Location: arch/x86/xen/platform-pci-unplug.c:145
Inline: False
Direct callers:
  - arch/x86/xen/enlighten_hvm.c:xen_hvm_guest_init
  - arch/x86/xen/suspend_hvm.c:xen_hvm_post_suspend
  - arch/x86/xen/suspend_hvm.c:xen_hvm_post_suspend
```
**Symbols:**

```
ffffffff8101ce8c-ffffffff8101cf03: xen_unplug_emulated_devices.cold.2 (STB_LOCAL)
ffffffff8101ce10-ffffffff8101ce8c: xen_unplug_emulated_devices (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Transformation ⚠️</summary>

```c
void xen_unplug_emulated_devices();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/xen/platform-pci-unplug.c (0)
Location: arch/x86/xen/platform-pci-unplug.c:133
Inline: False
Direct callers:
  - arch/x86/xen/enlighten_hvm.c:xen_hvm_guest_init
  - arch/x86/xen/suspend_hvm.c:xen_hvm_post_suspend
  - arch/x86/xen/suspend_hvm.c:xen_hvm_post_suspend
```
**Symbols:**

```
ffffffff8101cb15-ffffffff8101cb8c: xen_unplug_emulated_devices.cold.2 (STB_LOCAL)
ffffffff8101ca90-ffffffff8101cb15: xen_unplug_emulated_devices (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
void xen_unplug_emulated_devices();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/xen/platform-pci-unplug.c (0)
Location: arch/x86/xen/platform-pci-unplug.c:133
Inline: False
Direct callers:
  - arch/x86/xen/enlighten_hvm.c:xen_hvm_guest_init
  - arch/x86/xen/suspend_hvm.c:xen_hvm_post_suspend
  - arch/x86/xen/suspend_hvm.c:xen_hvm_post_suspend
```
**Symbols:**

```
ffffffff8101e655-ffffffff8101e6cc: xen_unplug_emulated_devices.cold (STB_LOCAL)
ffffffff8101e5d0-ffffffff8101e655: xen_unplug_emulated_devices (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
void xen_unplug_emulated_devices();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/xen/platform-pci-unplug.c (0)
Location: arch/x86/xen/platform-pci-unplug.c:133
Inline: False
Direct callers:
  - arch/x86/xen/enlighten_hvm.c:xen_hvm_guest_init
  - arch/x86/xen/suspend_hvm.c:xen_hvm_post_suspend
  - arch/x86/xen/suspend_hvm.c:xen_hvm_post_suspend
```
**Symbols:**

```
ffffffff8101efd5-ffffffff8101f04c: xen_unplug_emulated_devices.cold (STB_LOCAL)
ffffffff8101ef50-ffffffff8101efd5: xen_unplug_emulated_devices (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
void xen_unplug_emulated_devices();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/xen/platform-pci-unplug.c (0)
Location: arch/x86/xen/platform-pci-unplug.c:133
Inline: False
Direct callers:
  - arch/x86/xen/enlighten_hvm.c:xen_hvm_guest_init
  - arch/x86/xen/suspend_hvm.c:xen_hvm_post_suspend
  - arch/x86/xen/suspend_hvm.c:xen_hvm_post_suspend
```
**Symbols:**

```
ffffffff810215e8-ffffffff8102165f: xen_unplug_emulated_devices.cold (STB_LOCAL)
ffffffff81021560-ffffffff810215e8: xen_unplug_emulated_devices (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
void xen_unplug_emulated_devices();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/xen/platform-pci-unplug.c (0)
Location: arch/x86/xen/platform-pci-unplug.c:133
Inline: False
Direct callers:
  - arch/x86/xen/enlighten_hvm.c:xen_hvm_guest_init
  - arch/x86/xen/suspend_hvm.c:xen_hvm_post_suspend
  - arch/x86/xen/suspend_hvm.c:xen_hvm_post_suspend
```
**Symbols:**

```
ffffffff81bd2953-ffffffff81bd29ca: xen_unplug_emulated_devices.cold (STB_LOCAL)
ffffffff81021d20-ffffffff81021da8: xen_unplug_emulated_devices (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
void xen_unplug_emulated_devices();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/xen/platform-pci-unplug.c (0)
Location: arch/x86/xen/platform-pci-unplug.c:133
Inline: False
Direct callers:
  - arch/x86/xen/enlighten_hvm.c:xen_hvm_guest_init
  - arch/x86/xen/suspend_hvm.c:xen_hvm_post_suspend
  - arch/x86/xen/suspend_hvm.c:xen_hvm_post_suspend
```
**Symbols:**

```
ffffffff81bc4af1-ffffffff81bc4b68: xen_unplug_emulated_devices.cold (STB_LOCAL)
ffffffff810240b0-ffffffff81024138: xen_unplug_emulated_devices (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
void xen_unplug_emulated_devices();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/xen/platform-pci-unplug.c (0)
Location: arch/x86/xen/platform-pci-unplug.c:135
Inline: False
Direct callers:
  - arch/x86/xen/enlighten_hvm.c:xen_hvm_guest_init
  - arch/x86/xen/suspend_hvm.c:xen_hvm_post_suspend
  - arch/x86/xen/suspend_hvm.c:xen_hvm_post_suspend
```
**Symbols:**

```
ffffffff81c971c2-ffffffff81c9724d: xen_unplug_emulated_devices.cold (STB_LOCAL)
ffffffff81028470-ffffffff81028512: xen_unplug_emulated_devices (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
void xen_unplug_emulated_devices();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/xen/platform-pci-unplug.c (0)
Location: arch/x86/xen/platform-pci-unplug.c:135
Inline: False
Direct callers:
  - arch/x86/xen/enlighten_hvm.c:xen_hvm_guest_init
  - arch/x86/xen/suspend_hvm.c:xen_hvm_post_suspend
  - arch/x86/xen/suspend_hvm.c:xen_hvm_post_suspend
```
**Symbols:**

```
ffffffff81e46674-ffffffff81e466ff: xen_unplug_emulated_devices.cold (STB_LOCAL)
ffffffff8102cad0-ffffffff8102cb8a: xen_unplug_emulated_devices (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
void xen_unplug_emulated_devices();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/xen/platform-pci-unplug.c (0)
Location: arch/x86/xen/platform-pci-unplug.c:135
Inline: False
Direct callers:
  - arch/x86/xen/enlighten_hvm.c:xen_hvm_guest_init
  - arch/x86/xen/suspend_hvm.c:xen_hvm_post_suspend
```
**Symbols:**

```
ffffffff8205190b-ffffffff8205191f: xen_unplug_emulated_devices.cold (STB_LOCAL)
ffffffff81033c50-ffffffff81033d83: xen_unplug_emulated_devices (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
void xen_unplug_emulated_devices();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/xen/platform-pci-unplug.c (0)
Location: arch/x86/xen/platform-pci-unplug.c:135
Inline: False
Direct callers:
  - arch/x86/xen/enlighten_hvm.c:xen_hvm_guest_init
  - arch/x86/xen/suspend_hvm.c:xen_hvm_post_suspend
```
**Symbols:**

```
ffffffff820cfdf7-ffffffff820cfe0b: xen_unplug_emulated_devices.cold (STB_LOCAL)
ffffffff81033be0-ffffffff81033d17: xen_unplug_emulated_devices (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
void xen_unplug_emulated_devices();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/xen/platform-pci-unplug.c (0)
Location: arch/x86/xen/platform-pci-unplug.c:135
Inline: False
Direct callers:
  - arch/x86/xen/enlighten_hvm.c:xen_hvm_guest_init
  - arch/x86/xen/suspend_hvm.c:xen_hvm_post_suspend
```
**Symbols:**

```
ffffffff821aa765-ffffffff821aa779: xen_unplug_emulated_devices.cold (STB_LOCAL)
ffffffff81039ee0-ffffffff8103a017: xen_unplug_emulated_devices (STB_GLOBAL)
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
<summary>In <code>aws</code>: Transformation ⚠️</summary>

```c
void xen_unplug_emulated_devices();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/xen/platform-pci-unplug.c (0)
Location: arch/x86/xen/platform-pci-unplug.c:133
Inline: False
Direct callers:
  - arch/x86/xen/enlighten_hvm.c:xen_hvm_guest_init
  - arch/x86/xen/suspend_hvm.c:xen_hvm_post_suspend
  - arch/x86/xen/suspend_hvm.c:xen_hvm_post_suspend
```
**Symbols:**

```
ffffffff8101f135-ffffffff8101f1ac: xen_unplug_emulated_devices.cold (STB_LOCAL)
ffffffff8101f0b0-ffffffff8101f135: xen_unplug_emulated_devices (STB_GLOBAL)
```
</details>
</li>
<li>
In <code>azure</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>gcp</code>: Transformation ⚠️</summary>

```c
void xen_unplug_emulated_devices();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/xen/platform-pci-unplug.c (0)
Location: arch/x86/xen/platform-pci-unplug.c:133
Inline: False
Direct callers:
  - arch/x86/xen/enlighten_hvm.c:xen_hvm_guest_init
  - arch/x86/xen/suspend_hvm.c:xen_hvm_post_suspend
  - arch/x86/xen/suspend_hvm.c:xen_hvm_post_suspend
```
**Symbols:**

```
ffffffff8101ef95-ffffffff8101f00c: xen_unplug_emulated_devices.cold (STB_LOCAL)
ffffffff8101ef10-ffffffff8101ef95: xen_unplug_emulated_devices (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
void xen_unplug_emulated_devices();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/xen/platform-pci-unplug.c (0)
Location: arch/x86/xen/platform-pci-unplug.c:133
Inline: False
Direct callers:
  - arch/x86/xen/enlighten_hvm.c:xen_hvm_guest_init
  - arch/x86/xen/suspend_hvm.c:xen_hvm_post_suspend
  - arch/x86/xen/suspend_hvm.c:xen_hvm_post_suspend
```
**Symbols:**

```
ffffffff8101f1e5-ffffffff8101f25c: xen_unplug_emulated_devices.cold (STB_LOCAL)
ffffffff8101f160-ffffffff8101f1e5: xen_unplug_emulated_devices (STB_GLOBAL)
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
