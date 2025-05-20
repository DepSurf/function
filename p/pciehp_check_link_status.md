# Function: <code>pciehp_check_link_status</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int pciehp_check_link_status(struct controller *ctrl);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/hotplug/pciehp_hpc.c (ffffffff81450950)
Location: drivers/pci/hotplug/pciehp_hpc.c:298
Inline: False
Direct callers:
  - drivers/pci/hotplug/pciehp_ctrl.c:pciehp_enable_slot
```
**Symbols:**

```
ffffffff81450950-ffffffff81450b56: pciehp_check_link_status (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int pciehp_check_link_status(struct controller *ctrl);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/hotplug/pciehp_hpc.c (ffffffff8149d160)
Location: drivers/pci/hotplug/pciehp_hpc.c:298
Inline: False
Direct callers:
  - drivers/pci/hotplug/pciehp_ctrl.c:pciehp_enable_slot
```
**Symbols:**

```
ffffffff8149d160-ffffffff8149d36a: pciehp_check_link_status (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int pciehp_check_link_status(struct controller *ctrl);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/hotplug/pciehp_hpc.c (ffffffff814bece0)
Location: drivers/pci/hotplug/pciehp_hpc.c:298
Inline: False
Direct callers:
  - drivers/pci/hotplug/pciehp_ctrl.c:pciehp_enable_slot
```
**Symbols:**

```
ffffffff814bece0-ffffffff814beeea: pciehp_check_link_status (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int pciehp_check_link_status(struct controller *ctrl);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/hotplug/pciehp_hpc.c (ffffffff814c9470)
Location: drivers/pci/hotplug/pciehp_hpc.c:298
Inline: False
Direct callers:
  - drivers/pci/hotplug/pciehp_ctrl.c:pciehp_enable_slot
```
**Symbols:**

```
ffffffff814c9470-ffffffff814c9670: pciehp_check_link_status (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int pciehp_check_link_status(struct controller *ctrl);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/hotplug/pciehp_hpc.c (ffffffff81509a20)
Location: drivers/pci/hotplug/pciehp_hpc.c:295
Inline: False
Direct callers:
  - drivers/pci/hotplug/pciehp_ctrl.c:pciehp_enable_slot
```
**Symbols:**

```
ffffffff81509a20-ffffffff81509c20: pciehp_check_link_status (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Transformation ⚠️</summary>

```c
int pciehp_check_link_status(struct controller *ctrl);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pci/hotplug/pciehp_hpc.c (0)
Location: drivers/pci/hotplug/pciehp_hpc.c:275
Inline: False
Direct callers:
  - drivers/pci/hotplug/pciehp_ctrl.c:pciehp_enable_slot
```
**Symbols:**

```
ffffffff8153b945-ffffffff8153b977: pciehp_check_link_status.cold.14 (STB_LOCAL)
ffffffff8153aa10-ffffffff8153ab81: pciehp_check_link_status (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Transformation ⚠️</summary>

```c
int pciehp_check_link_status(struct controller *ctrl);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pci/hotplug/pciehp_hpc.c (0)
Location: drivers/pci/hotplug/pciehp_hpc.c:243
Inline: False
Direct callers:
  - drivers/pci/hotplug/pciehp_ctrl.c:pciehp_handle_presence_or_link_change
```
**Symbols:**

```
ffffffff81552e84-ffffffff81552eeb: pciehp_check_link_status.cold.17 (STB_LOCAL)
ffffffff81551c40-ffffffff81551da2: pciehp_check_link_status (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
int pciehp_check_link_status(struct controller *ctrl);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pci/hotplug/pciehp_hpc.c (0)
Location: drivers/pci/hotplug/pciehp_hpc.c:245
Inline: False
Direct callers:
  - drivers/pci/hotplug/pciehp_ctrl.c:pciehp_handle_presence_or_link_change
```
**Symbols:**

```
ffffffff81582dd0-ffffffff81582ded: pciehp_check_link_status.cold (STB_LOCAL)
ffffffff81581b80-ffffffff81581d16: pciehp_check_link_status (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
int pciehp_check_link_status(struct controller *ctrl);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pci/hotplug/pciehp_hpc.c (0)
Location: drivers/pci/hotplug/pciehp_hpc.c:257
Inline: False
Direct callers:
  - drivers/pci/hotplug/pciehp_ctrl.c:pciehp_handle_presence_or_link_change
```
**Symbols:**

```
ffffffff815a47b0-ffffffff815a47cd: pciehp_check_link_status.cold (STB_LOCAL)
ffffffff815a3610-ffffffff815a37a6: pciehp_check_link_status (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
int pciehp_check_link_status(struct controller *ctrl);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pci/hotplug/pciehp_hpc.c (0)
Location: drivers/pci/hotplug/pciehp_hpc.c:290
Inline: False
Direct callers:
  - drivers/pci/hotplug/pciehp_ctrl.c:board_added
```
**Symbols:**

```
ffffffff8164d3f5-ffffffff8164d42a: pciehp_check_link_status.cold (STB_LOCAL)
ffffffff8164c250-ffffffff8164c390: pciehp_check_link_status (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
int pciehp_check_link_status(struct controller *ctrl);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pci/hotplug/pciehp_hpc.c (0)
Location: drivers/pci/hotplug/pciehp_hpc.c:288
Inline: False
Direct callers:
  - drivers/pci/hotplug/pciehp_ctrl.c:board_added
```
**Symbols:**

```
ffffffff81bfc1e7-ffffffff81bfc271: pciehp_check_link_status.cold (STB_LOCAL)
ffffffff816705a0-ffffffff816706da: pciehp_check_link_status (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
int pciehp_check_link_status(struct controller *ctrl);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pci/hotplug/pciehp_hpc.c (0)
Location: drivers/pci/hotplug/pciehp_hpc.c:288
Inline: False
Direct callers:
  - drivers/pci/hotplug/pciehp_ctrl.c:pciehp_enable_slot
```
**Symbols:**

```
ffffffff81bee05f-ffffffff81bee0e4: pciehp_check_link_status.cold (STB_LOCAL)
ffffffff816529e0-ffffffff81652b99: pciehp_check_link_status (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int pciehp_check_link_status(struct controller *ctrl);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pci/hotplug/pciehp_hpc.c (0)
Location: drivers/pci/hotplug/pciehp_hpc.c:288
Inline: False
Direct callers:
  - drivers/pci/hotplug/pciehp_ctrl.c:pciehp_enable_slot
```
**Symbols:**

```
ffffffff81ce8e77-ffffffff81ce8efc: pciehp_check_link_status.cold (STB_LOCAL)
ffffffff816c4760-ffffffff816c4916: pciehp_check_link_status (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int pciehp_check_link_status(struct controller *ctrl);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pci/hotplug/pciehp_hpc.c (0)
Location: drivers/pci/hotplug/pciehp_hpc.c:290
Inline: False
Direct callers:
  - drivers/pci/hotplug/pciehp_ctrl.c:pciehp_enable_slot
```
**Symbols:**

```
ffffffff81eaff1f-ffffffff81eaff98: pciehp_check_link_status.cold (STB_LOCAL)
ffffffff817ea370-ffffffff817ea552: pciehp_check_link_status (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int pciehp_check_link_status(struct controller *ctrl);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/hotplug/pciehp_hpc.c (ffffffff81910480)
Location: drivers/pci/hotplug/pciehp_hpc.c:290
Inline: False
Direct callers:
  - drivers/pci/hotplug/pciehp_ctrl.c:pciehp_enable_slot
```
**Symbols:**

```
ffffffff81910480-ffffffff819106e8: pciehp_check_link_status (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int pciehp_check_link_status(struct controller *ctrl);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/hotplug/pciehp_hpc.c (ffffffff81953ba0)
Location: drivers/pci/hotplug/pciehp_hpc.c:290
Inline: False
Direct callers:
  - drivers/pci/hotplug/pciehp_ctrl.c:pciehp_enable_slot
```
**Symbols:**

```
ffffffff81953ba0-ffffffff81953e08: pciehp_check_link_status (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int pciehp_check_link_status(struct controller *ctrl);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/hotplug/pciehp_hpc.c (ffffffff8199d030)
Location: drivers/pci/hotplug/pciehp_hpc.c:291
Inline: False
Direct callers:
  - drivers/pci/hotplug/pciehp_ctrl.c:pciehp_enable_slot
```
**Symbols:**

```
ffffffff8199d030-ffffffff8199d298: pciehp_check_link_status (STB_GLOBAL)
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
int pciehp_check_link_status(struct controller *ctrl);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/hotplug/pciehp_hpc.c (ffff80001070c070)
Location: drivers/pci/hotplug/pciehp_hpc.c:257
Inline: False
Direct callers:
  - drivers/pci/hotplug/pciehp_ctrl.c:pciehp_handle_presence_or_link_change
```
**Symbols:**

```
ffff80001070c070-ffff80001070c258: pciehp_check_link_status (STB_GLOBAL)
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
int pciehp_check_link_status(struct controller *ctrl);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/hotplug/pciehp_hpc.c (ffffffe0004d8a5e)
Location: drivers/pci/hotplug/pciehp_hpc.c:257
Inline: False
Direct callers:
  - drivers/pci/hotplug/pciehp_ctrl.c:pciehp_handle_presence_or_link_change
```
**Symbols:**

```
ffffffe0004d8a5e-ffffffe0004d8c14: pciehp_check_link_status (STB_GLOBAL)
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
int pciehp_check_link_status(struct controller *ctrl);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pci/hotplug/pciehp_hpc.c (0)
Location: drivers/pci/hotplug/pciehp_hpc.c:257
Inline: False
Direct callers:
  - drivers/pci/hotplug/pciehp_ctrl.c:pciehp_handle_presence_or_link_change
```
**Symbols:**

```
ffffffff81597fc0-ffffffff81597fdd: pciehp_check_link_status.cold (STB_LOCAL)
ffffffff81596e20-ffffffff81596fb6: pciehp_check_link_status (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Transformation ⚠️</summary>

```c
int pciehp_check_link_status(struct controller *ctrl);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pci/hotplug/pciehp_hpc.c (0)
Location: drivers/pci/hotplug/pciehp_hpc.c:257
Inline: False
Direct callers:
  - drivers/pci/hotplug/pciehp_ctrl.c:pciehp_handle_presence_or_link_change
```
**Symbols:**

```
ffffffff81587150-ffffffff8158716d: pciehp_check_link_status.cold (STB_LOCAL)
ffffffff81585fb0-ffffffff81586146: pciehp_check_link_status (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Transformation ⚠️</summary>

```c
int pciehp_check_link_status(struct controller *ctrl);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pci/hotplug/pciehp_hpc.c (0)
Location: drivers/pci/hotplug/pciehp_hpc.c:257
Inline: False
Direct callers:
  - drivers/pci/hotplug/pciehp_ctrl.c:pciehp_handle_presence_or_link_change
```
**Symbols:**

```
ffffffff81598500-ffffffff8159851d: pciehp_check_link_status.cold (STB_LOCAL)
ffffffff81597360-ffffffff815974f6: pciehp_check_link_status (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
int pciehp_check_link_status(struct controller *ctrl);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pci/hotplug/pciehp_hpc.c (0)
Location: drivers/pci/hotplug/pciehp_hpc.c:257
Inline: False
Direct callers:
  - drivers/pci/hotplug/pciehp_ctrl.c:pciehp_handle_presence_or_link_change
```
**Symbols:**

```
ffffffff815b2944-ffffffff815b2961: pciehp_check_link_status.cold (STB_LOCAL)
ffffffff815b17a0-ffffffff815b1936: pciehp_check_link_status (STB_GLOBAL)
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
