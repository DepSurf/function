# Function: <code>vga_default_device</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline ⚠️</summary>

```c
struct pci_dev *vga_default_device();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/gpu/vga/vgaarb.c (ffffffff8153ebb0)
Location: drivers/gpu/vga/vgaarb.c:135
Inline: True
Inline callers:
  - drivers/gpu/vga/vgaarb.c:vga_put
  - drivers/gpu/vga/vgaarb.c:vga_arb_open
  - drivers/gpu/vga/vgaarb.c:vga_tryget
  - drivers/gpu/vga/vgaarb.c:vga_get
  - drivers/gpu/vga/vgaarb.c:vga_arb_device_init
Direct callers:
  - drivers/gpu/vga/vga_switcheroo.c:vga_switcheroo_register_client
  - arch/x86/pci/fixup.c:pci_fixup_video
  - arch/x86/pci/fixup.c:pci_fixup_video
  - arch/x86/video/fbdev.c:fb_is_primary_device
```
**Symbols:**

```
ffffffff8153ebb0-ffffffff8153ebc2: vga_default_device (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
struct pci_dev *vga_default_device();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/gpu/vga/vgaarb.c (ffffffff81fdc56d)
Location: drivers/gpu/vga/vgaarb.c:135
Inline: True
Inline callers:
  - drivers/gpu/vga/vgaarb.c:vga_arb_device_init
  - drivers/gpu/vga/vgaarb.c:vga_arb_open
  - drivers/gpu/vga/vgaarb.c:vga_put
  - drivers/gpu/vga/vgaarb.c:vga_tryget
  - drivers/gpu/vga/vgaarb.c:vga_get
Direct callers:
  - drivers/gpu/vga/vga_switcheroo.c:vga_switcheroo_register_client
  - arch/x86/pci/fixup.c:pci_fixup_video
  - arch/x86/pci/fixup.c:pci_fixup_video
  - arch/x86/video/fbdev.c:fb_is_primary_device
```
**Symbols:**

```
ffffffff8163fa20-ffffffff8163fa32: vga_default_device (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
struct pci_dev *vga_default_device();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/gpu/vga/vgaarb.c (ffffffff8201a09b)
Location: drivers/gpu/vga/vgaarb.c:156
Inline: True
Inline callers:
  - drivers/gpu/vga/vgaarb.c:vga_arb_device_init
  - drivers/gpu/vga/vgaarb.c:vga_arb_open
  - drivers/gpu/vga/vgaarb.c:vga_put
  - drivers/gpu/vga/vgaarb.c:vga_tryget
  - drivers/gpu/vga/vgaarb.c:vga_get
Direct callers:
  - drivers/gpu/vga/vga_switcheroo.c:vga_switcheroo_register_client
  - arch/x86/pci/fixup.c:pci_fixup_video
  - arch/x86/pci/fixup.c:pci_fixup_video
  - arch/x86/video/fbdev.c:fb_is_primary_device
```
**Symbols:**

```
ffffffff81670b30-ffffffff81670b42: vga_default_device (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
struct pci_dev *vga_default_device();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/gpu/vga/vgaarb.c (ffffffff820fc0c0)
Location: drivers/gpu/vga/vgaarb.c:156
Inline: True
Inline callers:
  - drivers/gpu/vga/vgaarb.c:vga_arb_device_init
  - drivers/gpu/vga/vgaarb.c:vga_arb_open
  - drivers/gpu/vga/vgaarb.c:vga_put
  - drivers/gpu/vga/vgaarb.c:vga_tryget
  - drivers/gpu/vga/vgaarb.c:vga_get
Direct callers:
  - drivers/pci/quirks.c:hibmc_fixup_vgaarb
  - drivers/gpu/vga/vga_switcheroo.c:vga_switcheroo_register_client
  - arch/x86/pci/fixup.c:pci_fixup_video
  - arch/x86/pci/fixup.c:pci_fixup_video
  - arch/x86/video/fbdev.c:fb_is_primary_device
```
**Symbols:**

```
ffffffff81685170-ffffffff81685182: vga_default_device (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
struct pci_dev *vga_default_device();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/gpu/vga/vgaarb.c (ffffffff816ef570)
Location: drivers/gpu/vga/vgaarb.c:156
Inline: True
Inline callers:
  - drivers/gpu/vga/vgaarb.c:vga_arb_open
  - drivers/gpu/vga/vgaarb.c:vga_put
  - drivers/gpu/vga/vgaarb.c:vga_tryget
  - drivers/gpu/vga/vgaarb.c:vga_get
Direct callers:
  - drivers/gpu/vga/vga_switcheroo.c:vga_switcheroo_register_client
  - arch/x86/pci/fixup.c:pci_fixup_video
  - arch/x86/pci/fixup.c:pci_fixup_video
  - arch/x86/video/fbdev.c:fb_is_primary_device
```
**Symbols:**

```
ffffffff816ee9d0-ffffffff816ee9e2: vga_default_device (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
struct pci_dev *vga_default_device();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/gpu/vga/vgaarb.c (ffffffff8272f63b)
Location: drivers/gpu/vga/vgaarb.c:156
Inline: True
Inline callers:
  - drivers/gpu/vga/vgaarb.c:vga_arb_device_init
  - drivers/gpu/vga/vgaarb.c:vga_arb_device_init
  - drivers/gpu/vga/vgaarb.c:vga_arb_open
  - drivers/gpu/vga/vgaarb.c:vga_arb_write
  - drivers/gpu/vga/vgaarb.c:vga_put
  - drivers/gpu/vga/vgaarb.c:vga_tryget
  - drivers/gpu/vga/vgaarb.c:vga_get
Direct callers:
  - drivers/gpu/vga/vga_switcheroo.c:vga_switcheroo_register_client
  - arch/x86/pci/fixup.c:pci_fixup_video
  - arch/x86/pci/fixup.c:pci_fixup_video
  - arch/x86/video/fbdev.c:fb_is_primary_device
```
**Symbols:**

```
ffffffff8172b410-ffffffff8172b422: vga_default_device (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
struct pci_dev *vga_default_device();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/gpu/vga/vgaarb.c (ffffffff828e8097)
Location: drivers/gpu/vga/vgaarb.c:156
Inline: True
Inline callers:
  - drivers/gpu/vga/vgaarb.c:vga_arb_device_init
  - drivers/gpu/vga/vgaarb.c:vga_arb_device_init
  - drivers/gpu/vga/vgaarb.c:vga_arb_open
  - drivers/gpu/vga/vgaarb.c:vga_arb_write
  - drivers/gpu/vga/vgaarb.c:vga_put
  - drivers/gpu/vga/vgaarb.c:vga_tryget
  - drivers/gpu/vga/vgaarb.c:vga_get
Direct callers:
  - drivers/gpu/vga/vga_switcheroo.c:vga_switcheroo_register_client
  - arch/x86/pci/fixup.c:pci_fixup_video
  - arch/x86/pci/fixup.c:pci_fixup_video
  - arch/x86/video/fbdev.c:fb_is_primary_device
```
**Symbols:**

```
ffffffff8174dbc0-ffffffff8174dbd2: vga_default_device (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
struct pci_dev *vga_default_device();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/gpu/vga/vgaarb.c (ffffffff829028d4)
Location: drivers/gpu/vga/vgaarb.c:158
Inline: True
Inline callers:
  - drivers/gpu/vga/vgaarb.c:vga_arb_device_init
  - drivers/gpu/vga/vgaarb.c:vga_arb_device_init
  - drivers/gpu/vga/vgaarb.c:vga_arb_open
  - drivers/gpu/vga/vgaarb.c:vga_arb_write
  - drivers/gpu/vga/vgaarb.c:vga_put
  - drivers/gpu/vga/vgaarb.c:vga_tryget
  - drivers/gpu/vga/vgaarb.c:vga_get
Direct callers:
  - drivers/gpu/vga/vga_switcheroo.c:vga_switcheroo_register_client
  - arch/x86/pci/fixup.c:pci_fixup_video
  - arch/x86/pci/fixup.c:pci_fixup_video
  - arch/x86/video/fbdev.c:fb_is_primary_device
```
**Symbols:**

```
ffffffff81789a80-ffffffff81789a92: vga_default_device (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
struct pci_dev *vga_default_device();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/gpu/vga/vgaarb.c (ffffffff8290badd)
Location: drivers/gpu/vga/vgaarb.c:158
Inline: True
Inline callers:
  - drivers/gpu/vga/vgaarb.c:vga_arb_device_init
  - drivers/gpu/vga/vgaarb.c:vga_arb_device_init
  - drivers/gpu/vga/vgaarb.c:vga_arb_open
  - drivers/gpu/vga/vgaarb.c:vga_arb_write
  - drivers/gpu/vga/vgaarb.c:vga_put
  - drivers/gpu/vga/vgaarb.c:vga_tryget
  - drivers/gpu/vga/vgaarb.c:vga_get
Direct callers:
  - drivers/gpu/vga/vga_switcheroo.c:vga_switcheroo_register_client
  - arch/x86/pci/fixup.c:pci_fixup_video
  - arch/x86/pci/fixup.c:pci_fixup_video
  - arch/x86/video/fbdev.c:fb_is_primary_device
```
**Symbols:**

```
ffffffff817ad680-ffffffff817ad692: vga_default_device (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
struct pci_dev *vga_default_device();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/gpu/vga/vgaarb.c (ffffffff82d20bcf)
Location: drivers/gpu/vga/vgaarb.c:158
Inline: True
Inline callers:
  - drivers/gpu/vga/vgaarb.c:vga_arb_select_default_device
  - drivers/gpu/vga/vgaarb.c:vga_arb_select_default_device
  - drivers/gpu/vga/vgaarb.c:vga_arb_select_default_device
  - drivers/gpu/vga/vgaarb.c:vga_arb_open
  - drivers/gpu/vga/vgaarb.c:vga_arb_write
  - drivers/gpu/vga/vgaarb.c:vga_put
  - drivers/gpu/vga/vgaarb.c:vga_tryget
  - drivers/gpu/vga/vgaarb.c:vga_get
Direct callers:
  - drivers/gpu/vga/vga_switcheroo.c:vga_switcheroo_register_client
  - arch/x86/pci/fixup.c:pci_fixup_video
  - arch/x86/pci/fixup.c:pci_fixup_video
  - arch/x86/video/fbdev.c:fb_is_primary_device
```
**Symbols:**

```
ffffffff818736b0-ffffffff818736c2: vga_default_device (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
struct pci_dev *vga_default_device();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/gpu/vga/vgaarb.c (ffffffff8300e9ae)
Location: drivers/gpu/vga/vgaarb.c:158
Inline: True
Inline callers:
  - drivers/gpu/vga/vgaarb.c:vga_arb_select_default_device
  - drivers/gpu/vga/vgaarb.c:vga_arb_select_default_device
  - drivers/gpu/vga/vgaarb.c:vga_arb_select_default_device
  - drivers/gpu/vga/vgaarb.c:vga_arb_open
  - drivers/gpu/vga/vgaarb.c:vga_arb_write
  - drivers/gpu/vga/vgaarb.c:vga_put
  - drivers/gpu/vga/vgaarb.c:vga_get
Direct callers:
  - drivers/gpu/vga/vga_switcheroo.c:vga_switcheroo_register_client
  - arch/x86/pci/fixup.c:pci_fixup_video
  - arch/x86/pci/fixup.c:pci_fixup_video
  - arch/x86/video/fbdev.c:fb_is_primary_device
```
**Symbols:**

```
ffffffff81882250-ffffffff81882262: vga_default_device (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
struct pci_dev *vga_default_device();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/gpu/vga/vgaarb.c (ffffffff83219949)
Location: drivers/gpu/vga/vgaarb.c:159
Inline: True
Inline callers:
  - drivers/gpu/vga/vgaarb.c:vga_arb_select_default_device
  - drivers/gpu/vga/vgaarb.c:vga_arb_select_default_device
  - drivers/gpu/vga/vgaarb.c:vga_arb_select_default_device
  - drivers/gpu/vga/vgaarb.c:vga_arb_open
  - drivers/gpu/vga/vgaarb.c:vga_arb_write
  - drivers/gpu/vga/vgaarb.c:vga_put
  - drivers/gpu/vga/vgaarb.c:vga_get
Direct callers:
  - drivers/gpu/vga/vga_switcheroo.c:vga_switcheroo_register_client
  - arch/x86/pci/fixup.c:pci_fixup_video
  - arch/x86/pci/fixup.c:pci_fixup_video
  - arch/x86/video/fbdev.c:fb_is_primary_device
```
**Symbols:**

```
ffffffff81864aa0-ffffffff81864ab2: vga_default_device (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
struct pci_dev *vga_default_device();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/gpu/vga/vgaarb.c (ffffffff833034a4)
Location: drivers/gpu/vga/vgaarb.c:156
Inline: True
Inline callers:
  - drivers/gpu/vga/vgaarb.c:vga_arb_select_default_device
  - drivers/gpu/vga/vgaarb.c:vga_arb_select_default_device
  - drivers/gpu/vga/vgaarb.c:vga_arb_select_default_device
  - drivers/gpu/vga/vgaarb.c:vga_arb_open
  - drivers/gpu/vga/vgaarb.c:vga_arb_write
  - drivers/gpu/vga/vgaarb.c:vga_put
  - drivers/gpu/vga/vgaarb.c:vga_get
Direct callers:
  - drivers/gpu/vga/vga_switcheroo.c:vga_switcheroo_register_client
  - arch/x86/pci/fixup.c:pci_fixup_video
  - arch/x86/pci/fixup.c:pci_fixup_video
  - arch/x86/video/fbdev.c:fb_is_primary_device
```
**Symbols:**

```
ffffffff818f3de0-ffffffff818f3df2: vga_default_device (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
struct pci_dev *vga_default_device();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/vgaarb.c (ffffffff817f4220)
Location: drivers/pci/vgaarb.c:134
Inline: True
Inline callers:
  - drivers/pci/vgaarb.c:vga_arb_open
  - drivers/pci/vgaarb.c:vga_arb_write
  - drivers/pci/vgaarb.c:vga_arbiter_add_pci_device
  - drivers/pci/vgaarb.c:vga_is_boot_device
  - drivers/pci/vgaarb.c:vga_put
  - drivers/pci/vgaarb.c:vga_get
Direct callers:
  - drivers/gpu/vga/vga_switcheroo.c:vga_switcheroo_client_probe_defer
  - drivers/gpu/vga/vga_switcheroo.c:vga_switcheroo_register_client
  - arch/x86/pci/fixup.c:pci_fixup_video
  - arch/x86/pci/fixup.c:pci_fixup_video
  - arch/x86/video/fbdev.c:fb_is_primary_device
```
**Symbols:**

```
ffffffff817f30e0-ffffffff817f30f6: vga_default_device (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
struct pci_dev *vga_default_device();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/vgaarb.c (ffffffff8191e8d0)
Location: drivers/pci/vgaarb.c:134
Inline: True
Inline callers:
  - drivers/pci/vgaarb.c:vga_arb_open
  - drivers/pci/vgaarb.c:vga_arb_write
  - drivers/pci/vgaarb.c:vga_arbiter_add_pci_device
  - drivers/pci/vgaarb.c:vga_is_boot_device
  - drivers/pci/vgaarb.c:vga_put
  - drivers/pci/vgaarb.c:vga_get
Direct callers:
  - drivers/gpu/vga/vga_switcheroo.c:vga_switcheroo_client_probe_defer
  - drivers/gpu/vga/vga_switcheroo.c:vga_switcheroo_register_client
  - arch/x86/pci/fixup.c:pci_fixup_video
  - arch/x86/pci/fixup.c:pci_fixup_video
  - arch/x86/video/fbdev.c:fb_is_primary_device
```
**Symbols:**

```
ffffffff8191d4e0-ffffffff8191d4f6: vga_default_device (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
struct pci_dev *vga_default_device();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/vgaarb.c (ffffffff81961ac0)
Location: drivers/pci/vgaarb.c:134
Inline: True
Inline callers:
  - drivers/pci/vgaarb.c:vga_arb_open
  - drivers/pci/vgaarb.c:vga_arb_write
  - drivers/pci/vgaarb.c:vga_arbiter_add_pci_device
  - drivers/pci/vgaarb.c:vga_is_boot_device
  - drivers/pci/vgaarb.c:vga_put
  - drivers/pci/vgaarb.c:vga_get
Direct callers:
  - drivers/video/aperture.c:aperture_remove_conflicting_pci_devices
  - drivers/gpu/vga/vga_switcheroo.c:vga_switcheroo_client_probe_defer
  - drivers/gpu/vga/vga_switcheroo.c:vga_switcheroo_register_client
  - arch/x86/pci/fixup.c:pci_fixup_video
  - arch/x86/pci/fixup.c:pci_fixup_video
  - arch/x86/video/fbdev.c:fb_is_primary_device
```
**Symbols:**

```
ffffffff81960ab0-ffffffff81960ac6: vga_default_device (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
struct pci_dev *vga_default_device();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/vgaarb.c (ffffffff819ab03f)
Location: drivers/pci/vgaarb.c:132
Inline: True
Inline callers:
  - drivers/pci/vgaarb.c:vga_arb_open
  - drivers/pci/vgaarb.c:vga_arb_write
  - drivers/pci/vgaarb.c:vga_arbiter_add_pci_device
  - drivers/pci/vgaarb.c:vga_is_boot_device
  - drivers/pci/vgaarb.c:vga_put
  - drivers/pci/vgaarb.c:vga_get
Direct callers:
  - drivers/video/aperture.c:aperture_remove_conflicting_pci_devices
  - drivers/gpu/vga/vga_switcheroo.c:vga_switcheroo_client_probe_defer
  - drivers/gpu/vga/vga_switcheroo.c:vga_switcheroo_register_client
  - arch/x86/pci/fixup.c:pci_fixup_video
  - arch/x86/pci/fixup.c:pci_fixup_video
  - arch/x86/video/fbdev.c:fb_is_primary_device
```
**Symbols:**

```
ffffffff819aa1c0-ffffffff819aa1d6: vga_default_device (STB_GLOBAL)
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
struct pci_dev *vga_default_device();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/gpu/vga/vgaarb.c (ffff80001149b200)
Location: drivers/gpu/vga/vgaarb.c:158
Inline: True
Inline callers:
  - drivers/gpu/vga/vgaarb.c:vga_arb_device_init
  - drivers/gpu/vga/vgaarb.c:vga_arb_device_init
  - drivers/gpu/vga/vgaarb.c:vga_arb_open
  - drivers/gpu/vga/vgaarb.c:vga_arb_write
  - drivers/gpu/vga/vgaarb.c:vga_put
  - drivers/gpu/vga/vgaarb.c:vga_tryget
  - drivers/gpu/vga/vgaarb.c:vga_get
```
**Symbols:**

```
ffff8000109bf480-ffff8000109bf4a0: vga_default_device (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
struct pci_dev *vga_default_device();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/gpu/vga/vgaarb.c (c159c168)
Location: drivers/gpu/vga/vgaarb.c:158
Inline: True
Inline callers:
  - drivers/gpu/vga/vgaarb.c:vga_arb_device_init
  - drivers/gpu/vga/vgaarb.c:vga_arb_device_init
  - drivers/gpu/vga/vgaarb.c:vga_arb_open
  - drivers/gpu/vga/vgaarb.c:vga_arb_write
  - drivers/gpu/vga/vgaarb.c:vga_put
  - drivers/gpu/vga/vgaarb.c:vga_tryget
  - drivers/gpu/vga/vgaarb.c:vga_get
```
**Symbols:**

```
c0a8c8b4-c0a8c8d8: vga_default_device (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
struct pci_dev *vga_default_device();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/gpu/vga/vgaarb.c (c0000000013af410)
Location: drivers/gpu/vga/vgaarb.c:158
Inline: True
Inline callers:
  - drivers/gpu/vga/vgaarb.c:vga_arb_device_init
  - drivers/gpu/vga/vgaarb.c:vga_arb_device_init
  - drivers/gpu/vga/vgaarb.c:vga_arb_open
  - drivers/gpu/vga/vgaarb.c:vga_arb_write
  - drivers/gpu/vga/vgaarb.c:vga_put
  - drivers/gpu/vga/vgaarb.c:vga_tryget
  - drivers/gpu/vga/vgaarb.c:vga_get
```
**Symbols:**

```
c000000000a7ffe0-c000000000a7fffc: vga_default_device (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
struct pci_dev *vga_default_device();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/gpu/vga/vgaarb.c (ffffffe0000344fa)
Location: drivers/gpu/vga/vgaarb.c:158
Inline: True
Inline callers:
  - drivers/gpu/vga/vgaarb.c:vga_arb_device_init
  - drivers/gpu/vga/vgaarb.c:vga_arb_device_init
  - drivers/gpu/vga/vgaarb.c:vga_arb_open
  - drivers/gpu/vga/vgaarb.c:vga_arb_write
  - drivers/gpu/vga/vgaarb.c:vga_put
  - drivers/gpu/vga/vgaarb.c:vga_tryget
  - drivers/gpu/vga/vgaarb.c:vga_get
```
**Symbols:**

```
ffffffe0006123ee-ffffffe000612410: vga_default_device (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Selective Inline ⚠️</summary>

```c
struct pci_dev *vga_default_device();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/gpu/vga/vgaarb.c (ffffffff828f349a)
Location: drivers/gpu/vga/vgaarb.c:158
Inline: True
Inline callers:
  - drivers/gpu/vga/vgaarb.c:vga_arb_device_init
  - drivers/gpu/vga/vgaarb.c:vga_arb_device_init
  - drivers/gpu/vga/vgaarb.c:vga_arb_open
  - drivers/gpu/vga/vgaarb.c:vga_arb_write
  - drivers/gpu/vga/vgaarb.c:vga_put
  - drivers/gpu/vga/vgaarb.c:vga_tryget
  - drivers/gpu/vga/vgaarb.c:vga_get
Direct callers:
  - drivers/gpu/vga/vga_switcheroo.c:vga_switcheroo_register_client
  - arch/x86/pci/fixup.c:pci_fixup_video
  - arch/x86/pci/fixup.c:pci_fixup_video
  - arch/x86/video/fbdev.c:fb_is_primary_device
```
**Symbols:**

```
ffffffff817721a0-ffffffff817721b2: vga_default_device (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
struct pci_dev *vga_default_device();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/gpu/vga/vgaarb.c (ffffffff828ea945)
Location: drivers/gpu/vga/vgaarb.c:158
Inline: True
Inline callers:
  - drivers/gpu/vga/vgaarb.c:vga_arb_device_init
  - drivers/gpu/vga/vgaarb.c:vga_arb_device_init
  - drivers/gpu/vga/vgaarb.c:vga_arb_open
  - drivers/gpu/vga/vgaarb.c:vga_arb_write
  - drivers/gpu/vga/vgaarb.c:vga_put
  - drivers/gpu/vga/vgaarb.c:vga_tryget
  - drivers/gpu/vga/vgaarb.c:vga_get
Direct callers:
  - drivers/gpu/vga/vga_switcheroo.c:vga_switcheroo_register_client
  - arch/x86/pci/fixup.c:pci_fixup_video
  - arch/x86/pci/fixup.c:pci_fixup_video
  - arch/x86/video/fbdev.c:fb_is_primary_device
```
**Symbols:**

```
ffffffff81751f50-ffffffff81751f62: vga_default_device (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
struct pci_dev *vga_default_device();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/gpu/vga/vgaarb.c (ffffffff82906ed8)
Location: drivers/gpu/vga/vgaarb.c:158
Inline: True
Inline callers:
  - drivers/gpu/vga/vgaarb.c:vga_arb_device_init
  - drivers/gpu/vga/vgaarb.c:vga_arb_device_init
  - drivers/gpu/vga/vgaarb.c:vga_arb_open
  - drivers/gpu/vga/vgaarb.c:vga_arb_write
  - drivers/gpu/vga/vgaarb.c:vga_put
  - drivers/gpu/vga/vgaarb.c:vga_tryget
  - drivers/gpu/vga/vgaarb.c:vga_get
Direct callers:
  - drivers/gpu/vga/vga_switcheroo.c:vga_switcheroo_register_client
  - arch/x86/pci/fixup.c:pci_fixup_video
  - arch/x86/pci/fixup.c:pci_fixup_video
  - arch/x86/video/fbdev.c:fb_is_primary_device
```
**Symbols:**

```
ffffffff817a2500-ffffffff817a2512: vga_default_device (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
struct pci_dev *vga_default_device();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/gpu/vga/vgaarb.c (ffffffff8290cb3f)
Location: drivers/gpu/vga/vgaarb.c:158
Inline: True
Inline callers:
  - drivers/gpu/vga/vgaarb.c:vga_arb_device_init
  - drivers/gpu/vga/vgaarb.c:vga_arb_device_init
  - drivers/gpu/vga/vgaarb.c:vga_arb_open
  - drivers/gpu/vga/vgaarb.c:vga_arb_write
  - drivers/gpu/vga/vgaarb.c:vga_put
  - drivers/gpu/vga/vgaarb.c:vga_tryget
  - drivers/gpu/vga/vgaarb.c:vga_get
Direct callers:
  - drivers/gpu/vga/vga_switcheroo.c:vga_switcheroo_register_client
  - arch/x86/pci/fixup.c:pci_fixup_video
  - arch/x86/pci/fixup.c:pci_fixup_video
  - arch/x86/video/fbdev.c:fb_is_primary_device
```
**Symbols:**

```
ffffffff817bc380-ffffffff817bc392: vga_default_device (STB_GLOBAL)
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
