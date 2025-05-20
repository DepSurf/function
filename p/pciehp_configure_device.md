# Function: <code>pciehp_configure_device</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int pciehp_configure_device(struct slot *p_slot);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/hotplug/pciehp_pci.c (ffffffff8144feb0)
Location: drivers/pci/hotplug/pciehp_pci.c:37
Inline: False
Direct callers:
  - drivers/pci/hotplug/pciehp_ctrl.c:pciehp_enable_slot
```
**Symbols:**

```
ffffffff8144feb0-ffffffff8144ffc6: pciehp_configure_device (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int pciehp_configure_device(struct slot *p_slot);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/hotplug/pciehp_pci.c (ffffffff8149c680)
Location: drivers/pci/hotplug/pciehp_pci.c:37
Inline: False
Direct callers:
  - drivers/pci/hotplug/pciehp_ctrl.c:pciehp_enable_slot
```
**Symbols:**

```
ffffffff8149c680-ffffffff8149c796: pciehp_configure_device (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int pciehp_configure_device(struct slot *p_slot);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/hotplug/pciehp_pci.c (ffffffff814be200)
Location: drivers/pci/hotplug/pciehp_pci.c:37
Inline: False
Direct callers:
  - drivers/pci/hotplug/pciehp_ctrl.c:pciehp_enable_slot
```
**Symbols:**

```
ffffffff814be200-ffffffff814be316: pciehp_configure_device (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int pciehp_configure_device(struct slot *p_slot);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/hotplug/pciehp_pci.c (ffffffff814c89d0)
Location: drivers/pci/hotplug/pciehp_pci.c:37
Inline: False
Direct callers:
  - drivers/pci/hotplug/pciehp_ctrl.c:pciehp_enable_slot
```
**Symbols:**

```
ffffffff814c89d0-ffffffff814c8ae4: pciehp_configure_device (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int pciehp_configure_device(struct slot *p_slot);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/hotplug/pciehp_pci.c (ffffffff81508f80)
Location: drivers/pci/hotplug/pciehp_pci.c:37
Inline: False
Direct callers:
  - drivers/pci/hotplug/pciehp_ctrl.c:pciehp_enable_slot
```
**Symbols:**

```
ffffffff81508f80-ffffffff815090aa: pciehp_configure_device (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int pciehp_configure_device(struct slot *p_slot);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/hotplug/pciehp_pci.c (ffffffff81539ee0)
Location: drivers/pci/hotplug/pciehp_pci.c:23
Inline: False
Direct callers:
  - drivers/pci/hotplug/pciehp_ctrl.c:pciehp_enable_slot
```
**Symbols:**

```
ffffffff81539ee0-ffffffff8153a008: pciehp_configure_device (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int pciehp_configure_device(struct controller *ctrl);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/hotplug/pciehp_pci.c (ffffffff81551220)
Location: drivers/pci/hotplug/pciehp_pci.c:30
Inline: False
Direct callers:
  - drivers/pci/hotplug/pciehp_ctrl.c:pciehp_handle_presence_or_link_change
```
**Symbols:**

```
ffffffff81551220-ffffffff81551344: pciehp_configure_device (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
int pciehp_configure_device(struct controller *ctrl);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pci/hotplug/pciehp_pci.c (0)
Location: drivers/pci/hotplug/pciehp_pci.c:32
Inline: False
Direct callers:
  - drivers/pci/hotplug/pciehp_ctrl.c:pciehp_handle_presence_or_link_change
```
**Symbols:**

```
ffffffff815813ef-ffffffff81581414: pciehp_configure_device.cold (STB_LOCAL)
ffffffff815811a0-ffffffff815812b1: pciehp_configure_device (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
int pciehp_configure_device(struct controller *ctrl);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pci/hotplug/pciehp_pci.c (0)
Location: drivers/pci/hotplug/pciehp_pci.c:32
Inline: False
Direct callers:
  - drivers/pci/hotplug/pciehp_ctrl.c:pciehp_handle_presence_or_link_change
```
**Symbols:**

```
ffffffff815a2eef-ffffffff815a2f14: pciehp_configure_device.cold (STB_LOCAL)
ffffffff815a2ca0-ffffffff815a2db1: pciehp_configure_device (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
int pciehp_configure_device(struct controller *ctrl);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pci/hotplug/pciehp_pci.c (0)
Location: drivers/pci/hotplug/pciehp_pci.c:32
Inline: False
Direct callers:
  - drivers/pci/hotplug/pciehp_ctrl.c:board_added
```
**Symbols:**

```
ffffffff8164ba6d-ffffffff8164ba92: pciehp_configure_device.cold (STB_LOCAL)
ffffffff8164b820-ffffffff8164b931: pciehp_configure_device (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
int pciehp_configure_device(struct controller *ctrl);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pci/hotplug/pciehp_pci.c (0)
Location: drivers/pci/hotplug/pciehp_pci.c:32
Inline: False
Direct callers:
  - drivers/pci/hotplug/pciehp_ctrl.c:board_added
```
**Symbols:**

```
ffffffff81bfc135-ffffffff81bfc15a: pciehp_configure_device.cold (STB_LOCAL)
ffffffff8166fba0-ffffffff8166fcb1: pciehp_configure_device (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
int pciehp_configure_device(struct controller *ctrl);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pci/hotplug/pciehp_pci.c (0)
Location: drivers/pci/hotplug/pciehp_pci.c:32
Inline: False
Direct callers:
  - drivers/pci/hotplug/pciehp_ctrl.c:pciehp_enable_slot
```
**Symbols:**

```
ffffffff81bedfad-ffffffff81bedfd2: pciehp_configure_device.cold (STB_LOCAL)
ffffffff816520a0-ffffffff816521b1: pciehp_configure_device (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int pciehp_configure_device(struct controller *ctrl);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pci/hotplug/pciehp_pci.c (0)
Location: drivers/pci/hotplug/pciehp_pci.c:32
Inline: False
Direct callers:
  - drivers/pci/hotplug/pciehp_ctrl.c:pciehp_enable_slot
```
**Symbols:**

```
ffffffff81ce8d88-ffffffff81ce8dad: pciehp_configure_device.cold (STB_LOCAL)
ffffffff816c3df0-ffffffff816c3efe: pciehp_configure_device (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int pciehp_configure_device(struct controller *ctrl);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pci/hotplug/pciehp_pci.c (0)
Location: drivers/pci/hotplug/pciehp_pci.c:32
Inline: False
Direct callers:
  - drivers/pci/hotplug/pciehp_ctrl.c:pciehp_enable_slot
```
**Symbols:**

```
ffffffff81eafe32-ffffffff81eafe57: pciehp_configure_device.cold (STB_LOCAL)
ffffffff817e9930-ffffffff817e9a52: pciehp_configure_device (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int pciehp_configure_device(struct controller *ctrl);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/hotplug/pciehp_pci.c (ffffffff8190f910)
Location: drivers/pci/hotplug/pciehp_pci.c:32
Inline: False
Direct callers:
  - drivers/pci/hotplug/pciehp_ctrl.c:pciehp_enable_slot
```
**Symbols:**

```
ffffffff8190f910-ffffffff8190fa57: pciehp_configure_device (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int pciehp_configure_device(struct controller *ctrl);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/hotplug/pciehp_pci.c (ffffffff81953000)
Location: drivers/pci/hotplug/pciehp_pci.c:32
Inline: False
Direct callers:
  - drivers/pci/hotplug/pciehp_ctrl.c:pciehp_enable_slot
```
**Symbols:**

```
ffffffff81953000-ffffffff81953160: pciehp_configure_device (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int pciehp_configure_device(struct controller *ctrl);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/hotplug/pciehp_pci.c (ffffffff8199c490)
Location: drivers/pci/hotplug/pciehp_pci.c:32
Inline: False
Direct callers:
  - drivers/pci/hotplug/pciehp_ctrl.c:pciehp_enable_slot
```
**Symbols:**

```
ffffffff8199c490-ffffffff8199c5f0: pciehp_configure_device (STB_GLOBAL)
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
int pciehp_configure_device(struct controller *ctrl);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/hotplug/pciehp_pci.c (ffff80001070b550)
Location: drivers/pci/hotplug/pciehp_pci.c:32
Inline: False
Direct callers:
  - drivers/pci/hotplug/pciehp_ctrl.c:pciehp_handle_presence_or_link_change
```
**Symbols:**

```
ffff80001070b550-ffff80001070b68c: pciehp_configure_device (STB_GLOBAL)
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
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int pciehp_configure_device(struct controller *ctrl);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/hotplug/pciehp_pci.c (ffffffe0004d8180)
Location: drivers/pci/hotplug/pciehp_pci.c:32
Inline: False
Direct callers:
  - drivers/pci/hotplug/pciehp_ctrl.c:pciehp_handle_presence_or_link_change
```
**Symbols:**

```
ffffffe0004d8180-ffffffe0004d82b0: pciehp_configure_device (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Transformation ⚠️</summary>

```c
int pciehp_configure_device(struct controller *ctrl);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pci/hotplug/pciehp_pci.c (0)
Location: drivers/pci/hotplug/pciehp_pci.c:32
Inline: False
Direct callers:
  - drivers/pci/hotplug/pciehp_ctrl.c:pciehp_handle_presence_or_link_change
```
**Symbols:**

```
ffffffff815966ff-ffffffff81596724: pciehp_configure_device.cold (STB_LOCAL)
ffffffff815964b0-ffffffff815965c1: pciehp_configure_device (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Transformation ⚠️</summary>

```c
int pciehp_configure_device(struct controller *ctrl);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pci/hotplug/pciehp_pci.c (0)
Location: drivers/pci/hotplug/pciehp_pci.c:32
Inline: False
Direct callers:
  - drivers/pci/hotplug/pciehp_ctrl.c:pciehp_handle_presence_or_link_change
```
**Symbols:**

```
ffffffff8158588f-ffffffff815858b4: pciehp_configure_device.cold (STB_LOCAL)
ffffffff81585640-ffffffff81585751: pciehp_configure_device (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Transformation ⚠️</summary>

```c
int pciehp_configure_device(struct controller *ctrl);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pci/hotplug/pciehp_pci.c (0)
Location: drivers/pci/hotplug/pciehp_pci.c:32
Inline: False
Direct callers:
  - drivers/pci/hotplug/pciehp_ctrl.c:pciehp_handle_presence_or_link_change
```
**Symbols:**

```
ffffffff81596c3f-ffffffff81596c64: pciehp_configure_device.cold (STB_LOCAL)
ffffffff815969f0-ffffffff81596b01: pciehp_configure_device (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
int pciehp_configure_device(struct controller *ctrl);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pci/hotplug/pciehp_pci.c (0)
Location: drivers/pci/hotplug/pciehp_pci.c:32
Inline: False
Direct callers:
  - drivers/pci/hotplug/pciehp_ctrl.c:pciehp_handle_presence_or_link_change
```
**Symbols:**

```
ffffffff815b10bf-ffffffff815b10e4: pciehp_configure_device.cold (STB_LOCAL)
ffffffff815b0e70-ffffffff815b0f81: pciehp_configure_device (STB_GLOBAL)
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
<details>
<summary>Changed between <code>4.18</code> and <code>5.0</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>struct controller *ctrl</code>
</li>
<li>
<b>Param removed. </b>
<code>struct slot *p_slot</code>
</li>
</ul>
</details>
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
