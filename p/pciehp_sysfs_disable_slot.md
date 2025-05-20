# Function: <code>pciehp_sysfs_disable_slot</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int pciehp_sysfs_disable_slot(struct slot *p_slot);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/hotplug/pciehp_ctrl.c (ffffffff8144fdc0)
Location: drivers/pci/hotplug/pciehp_ctrl.c:502
Inline: False
Direct callers:
  - drivers/pci/hotplug/pciehp_core.c:disable_slot
```
**Symbols:**

```
ffffffff8144fdc0-ffffffff8144feae: pciehp_sysfs_disable_slot (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int pciehp_sysfs_disable_slot(struct slot *p_slot);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/hotplug/pciehp_ctrl.c (ffffffff8149c570)
Location: drivers/pci/hotplug/pciehp_ctrl.c:502
Inline: False
Direct callers:
  - drivers/pci/hotplug/pciehp_core.c:disable_slot
```
**Symbols:**

```
ffffffff8149c570-ffffffff8149c679: pciehp_sysfs_disable_slot (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int pciehp_sysfs_disable_slot(struct slot *p_slot);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/hotplug/pciehp_ctrl.c (ffffffff814be0f0)
Location: drivers/pci/hotplug/pciehp_ctrl.c:480
Inline: False
Direct callers:
  - drivers/pci/hotplug/pciehp_core.c:disable_slot
```
**Symbols:**

```
ffffffff814be0f0-ffffffff814be1f9: pciehp_sysfs_disable_slot (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int pciehp_sysfs_disable_slot(struct slot *p_slot);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/hotplug/pciehp_ctrl.c (ffffffff814c88b0)
Location: drivers/pci/hotplug/pciehp_ctrl.c:480
Inline: False
Direct callers:
  - drivers/pci/hotplug/pciehp_core.c:disable_slot
```
**Symbols:**

```
ffffffff814c88b0-ffffffff814c89b6: pciehp_sysfs_disable_slot (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int pciehp_sysfs_disable_slot(struct slot *p_slot);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/hotplug/pciehp_ctrl.c (ffffffff81508e60)
Location: drivers/pci/hotplug/pciehp_ctrl.c:481
Inline: False
Direct callers:
  - drivers/pci/hotplug/pciehp_core.c:disable_slot
```
**Symbols:**

```
ffffffff81508e60-ffffffff81508f6c: pciehp_sysfs_disable_slot (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int pciehp_sysfs_disable_slot(struct slot *p_slot);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/hotplug/pciehp_ctrl.c (ffffffff81539dc0)
Location: drivers/pci/hotplug/pciehp_ctrl.c:467
Inline: False
Direct callers:
  - drivers/pci/hotplug/pciehp_core.c:disable_slot
```
**Symbols:**

```
ffffffff81539dc0-ffffffff81539ecc: pciehp_sysfs_disable_slot (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int pciehp_sysfs_disable_slot(struct hotplug_slot *hotplug_slot);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/hotplug/pciehp_ctrl.c (ffffffff81551080)
Location: drivers/pci/hotplug/pciehp_ctrl.c:387
Inline: False
```
**Symbols:**

```
ffffffff81551080-ffffffff815511df: pciehp_sysfs_disable_slot (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
int pciehp_sysfs_disable_slot(struct hotplug_slot *hotplug_slot);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pci/hotplug/pciehp_ctrl.c (0)
Location: drivers/pci/hotplug/pciehp_ctrl.c:393
Inline: False
```
**Symbols:**

```
ffffffff815810e6-ffffffff81581152: pciehp_sysfs_disable_slot.cold (STB_LOCAL)
ffffffff81580b10-ffffffff81580c1d: pciehp_sysfs_disable_slot (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
int pciehp_sysfs_disable_slot(struct hotplug_slot *hotplug_slot);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pci/hotplug/pciehp_ctrl.c (0)
Location: drivers/pci/hotplug/pciehp_ctrl.c:401
Inline: False
```
**Symbols:**

```
ffffffff815a2bf4-ffffffff815a2c60: pciehp_sysfs_disable_slot.cold (STB_LOCAL)
ffffffff815a2740-ffffffff815a2856: pciehp_sysfs_disable_slot (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
int pciehp_sysfs_disable_slot(struct hotplug_slot *hotplug_slot);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pci/hotplug/pciehp_ctrl.c (0)
Location: drivers/pci/hotplug/pciehp_ctrl.c:401
Inline: False
```
**Symbols:**

```
ffffffff8164b773-ffffffff8164b7df: pciehp_sysfs_disable_slot.cold (STB_LOCAL)
ffffffff8164b2a0-ffffffff8164b3d0: pciehp_sysfs_disable_slot (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
int pciehp_sysfs_disable_slot(struct hotplug_slot *hotplug_slot);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pci/hotplug/pciehp_ctrl.c (0)
Location: drivers/pci/hotplug/pciehp_ctrl.c:399
Inline: False
```
**Symbols:**

```
ffffffff81bfc0c9-ffffffff81bfc135: pciehp_sysfs_disable_slot.cold (STB_LOCAL)
ffffffff8166fa30-ffffffff8166fb60: pciehp_sysfs_disable_slot (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
int pciehp_sysfs_disable_slot(struct hotplug_slot *hotplug_slot);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pci/hotplug/pciehp_ctrl.c (0)
Location: drivers/pci/hotplug/pciehp_ctrl.c:399
Inline: False
```
**Symbols:**

```
ffffffff81bedf41-ffffffff81bedfad: pciehp_sysfs_disable_slot.cold (STB_LOCAL)
ffffffff81651f30-ffffffff81652060: pciehp_sysfs_disable_slot (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int pciehp_sysfs_disable_slot(struct hotplug_slot *hotplug_slot);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pci/hotplug/pciehp_ctrl.c (0)
Location: drivers/pci/hotplug/pciehp_ctrl.c:399
Inline: False
```
**Symbols:**

```
ffffffff81ce8d1c-ffffffff81ce8d88: pciehp_sysfs_disable_slot.cold (STB_LOCAL)
ffffffff816c3c90-ffffffff816c3da6: pciehp_sysfs_disable_slot (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int pciehp_sysfs_disable_slot(struct hotplug_slot *hotplug_slot);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pci/hotplug/pciehp_ctrl.c (0)
Location: drivers/pci/hotplug/pciehp_ctrl.c:399
Inline: False
```
**Symbols:**

```
ffffffff81eafdc6-ffffffff81eafe32: pciehp_sysfs_disable_slot.cold (STB_LOCAL)
ffffffff817e9790-ffffffff817e98d3: pciehp_sysfs_disable_slot (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int pciehp_sysfs_disable_slot(struct hotplug_slot *hotplug_slot);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/hotplug/pciehp_ctrl.c (ffffffff8190f720)
Location: drivers/pci/hotplug/pciehp_ctrl.c:399
Inline: False
```
**Symbols:**

```
ffffffff8190f720-ffffffff8190f8c4: pciehp_sysfs_disable_slot (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int pciehp_sysfs_disable_slot(struct hotplug_slot *hotplug_slot);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/hotplug/pciehp_ctrl.c (ffffffff81952e10)
Location: drivers/pci/hotplug/pciehp_ctrl.c:408
Inline: False
```
**Symbols:**

```
ffffffff81952e10-ffffffff81952fb1: pciehp_sysfs_disable_slot (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int pciehp_sysfs_disable_slot(struct hotplug_slot *hotplug_slot);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/hotplug/pciehp_ctrl.c (ffffffff8199c2a0)
Location: drivers/pci/hotplug/pciehp_ctrl.c:408
Inline: False
```
**Symbols:**

```
ffffffff8199c2a0-ffffffff8199c441: pciehp_sysfs_disable_slot (STB_GLOBAL)
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
int pciehp_sysfs_disable_slot(struct hotplug_slot *hotplug_slot);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/hotplug/pciehp_ctrl.c (ffff80001070b350)
Location: drivers/pci/hotplug/pciehp_ctrl.c:401
Inline: False
```
**Symbols:**

```
ffff80001070b350-ffff80001070b4cc: pciehp_sysfs_disable_slot (STB_GLOBAL)
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
int pciehp_sysfs_disable_slot(struct hotplug_slot *hotplug_slot);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/hotplug/pciehp_ctrl.c (ffffffe0004d7ff8)
Location: drivers/pci/hotplug/pciehp_ctrl.c:401
Inline: False
```
**Symbols:**

```
ffffffe0004d7ff8-ffffffe0004d813a: pciehp_sysfs_disable_slot (STB_GLOBAL)
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
int pciehp_sysfs_disable_slot(struct hotplug_slot *hotplug_slot);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pci/hotplug/pciehp_ctrl.c (0)
Location: drivers/pci/hotplug/pciehp_ctrl.c:401
Inline: False
```
**Symbols:**

```
ffffffff81596404-ffffffff81596470: pciehp_sysfs_disable_slot.cold (STB_LOCAL)
ffffffff81595f50-ffffffff81596066: pciehp_sysfs_disable_slot (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Transformation ⚠️</summary>

```c
int pciehp_sysfs_disable_slot(struct hotplug_slot *hotplug_slot);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pci/hotplug/pciehp_ctrl.c (0)
Location: drivers/pci/hotplug/pciehp_ctrl.c:401
Inline: False
```
**Symbols:**

```
ffffffff81585594-ffffffff81585600: pciehp_sysfs_disable_slot.cold (STB_LOCAL)
ffffffff815850e0-ffffffff815851f6: pciehp_sysfs_disable_slot (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Transformation ⚠️</summary>

```c
int pciehp_sysfs_disable_slot(struct hotplug_slot *hotplug_slot);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pci/hotplug/pciehp_ctrl.c (0)
Location: drivers/pci/hotplug/pciehp_ctrl.c:401
Inline: False
```
**Symbols:**

```
ffffffff81596944-ffffffff815969b0: pciehp_sysfs_disable_slot.cold (STB_LOCAL)
ffffffff81596490-ffffffff815965a6: pciehp_sysfs_disable_slot (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
int pciehp_sysfs_disable_slot(struct hotplug_slot *hotplug_slot);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pci/hotplug/pciehp_ctrl.c (0)
Location: drivers/pci/hotplug/pciehp_ctrl.c:401
Inline: False
```
**Symbols:**

```
ffffffff815b0dbf-ffffffff815b0e2b: pciehp_sysfs_disable_slot.cold (STB_LOCAL)
ffffffff815b0910-ffffffff815b0a21: pciehp_sysfs_disable_slot (STB_GLOBAL)
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
<code>struct hotplug_slot *hotplug_slot</code>
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
