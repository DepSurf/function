# Function: <code>pciehp_sysfs_enable_slot</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int pciehp_sysfs_enable_slot(struct slot *p_slot);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/hotplug/pciehp_ctrl.c (ffffffff8144fcb0)
Location: drivers/pci/hotplug/pciehp_ctrl.c:465
Inline: False
Direct callers:
  - drivers/pci/hotplug/pciehp_core.c:enable_slot
```
**Symbols:**

```
ffffffff8144fcb0-ffffffff8144fdb9: pciehp_sysfs_enable_slot (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int pciehp_sysfs_enable_slot(struct slot *p_slot);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/hotplug/pciehp_ctrl.c (ffffffff8149c460)
Location: drivers/pci/hotplug/pciehp_ctrl.c:465
Inline: False
Direct callers:
  - drivers/pci/hotplug/pciehp_core.c:enable_slot
```
**Symbols:**

```
ffffffff8149c460-ffffffff8149c569: pciehp_sysfs_enable_slot (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int pciehp_sysfs_enable_slot(struct slot *p_slot);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/hotplug/pciehp_ctrl.c (ffffffff814bdfe0)
Location: drivers/pci/hotplug/pciehp_ctrl.c:443
Inline: False
Direct callers:
  - drivers/pci/hotplug/pciehp_core.c:enable_slot
```
**Symbols:**

```
ffffffff814bdfe0-ffffffff814be0e9: pciehp_sysfs_enable_slot (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int pciehp_sysfs_enable_slot(struct slot *p_slot);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/hotplug/pciehp_ctrl.c (ffffffff814c87a0)
Location: drivers/pci/hotplug/pciehp_ctrl.c:443
Inline: False
Direct callers:
  - drivers/pci/hotplug/pciehp_core.c:enable_slot
```
**Symbols:**

```
ffffffff814c87a0-ffffffff814c88a6: pciehp_sysfs_enable_slot (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int pciehp_sysfs_enable_slot(struct slot *p_slot);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/hotplug/pciehp_ctrl.c (ffffffff81508d50)
Location: drivers/pci/hotplug/pciehp_ctrl.c:444
Inline: False
Direct callers:
  - drivers/pci/hotplug/pciehp_core.c:enable_slot
```
**Symbols:**

```
ffffffff81508d50-ffffffff81508e5c: pciehp_sysfs_enable_slot (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int pciehp_sysfs_enable_slot(struct slot *p_slot);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/hotplug/pciehp_ctrl.c (ffffffff81539cb0)
Location: drivers/pci/hotplug/pciehp_ctrl.c:430
Inline: False
Direct callers:
  - drivers/pci/hotplug/pciehp_core.c:enable_slot
```
**Symbols:**

```
ffffffff81539cb0-ffffffff81539dbc: pciehp_sysfs_enable_slot (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int pciehp_sysfs_enable_slot(struct hotplug_slot *hotplug_slot);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/hotplug/pciehp_ctrl.c (ffffffff81550f10)
Location: drivers/pci/hotplug/pciehp_ctrl.c:349
Inline: False
```
**Symbols:**

```
ffffffff81550f10-ffffffff81551078: pciehp_sysfs_enable_slot (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
int pciehp_sysfs_enable_slot(struct hotplug_slot *hotplug_slot);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pci/hotplug/pciehp_ctrl.c (0)
Location: drivers/pci/hotplug/pciehp_ctrl.c:355
Inline: False
```
**Symbols:**

```
ffffffff8158104f-ffffffff815810e6: pciehp_sysfs_enable_slot.cold (STB_LOCAL)
ffffffff81580a40-ffffffff81580b0f: pciehp_sysfs_enable_slot (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
int pciehp_sysfs_enable_slot(struct hotplug_slot *hotplug_slot);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pci/hotplug/pciehp_ctrl.c (0)
Location: drivers/pci/hotplug/pciehp_ctrl.c:362
Inline: False
```
**Symbols:**

```
ffffffff815a2b5d-ffffffff815a2bf4: pciehp_sysfs_enable_slot.cold (STB_LOCAL)
ffffffff815a2660-ffffffff815a273b: pciehp_sysfs_enable_slot (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
int pciehp_sysfs_enable_slot(struct hotplug_slot *hotplug_slot);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pci/hotplug/pciehp_ctrl.c (0)
Location: drivers/pci/hotplug/pciehp_ctrl.c:362
Inline: False
```
**Symbols:**

```
ffffffff8164b6dc-ffffffff8164b773: pciehp_sysfs_enable_slot.cold (STB_LOCAL)
ffffffff8164b1a0-ffffffff8164b295: pciehp_sysfs_enable_slot (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
int pciehp_sysfs_enable_slot(struct hotplug_slot *hotplug_slot);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pci/hotplug/pciehp_ctrl.c (0)
Location: drivers/pci/hotplug/pciehp_ctrl.c:360
Inline: False
```
**Symbols:**

```
ffffffff81bfc032-ffffffff81bfc0c9: pciehp_sysfs_enable_slot.cold (STB_LOCAL)
ffffffff8166f930-ffffffff8166fa25: pciehp_sysfs_enable_slot (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
int pciehp_sysfs_enable_slot(struct hotplug_slot *hotplug_slot);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pci/hotplug/pciehp_ctrl.c (0)
Location: drivers/pci/hotplug/pciehp_ctrl.c:360
Inline: False
```
**Symbols:**

```
ffffffff81bedeaa-ffffffff81bedf41: pciehp_sysfs_enable_slot.cold (STB_LOCAL)
ffffffff81651e30-ffffffff81651f25: pciehp_sysfs_enable_slot (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int pciehp_sysfs_enable_slot(struct hotplug_slot *hotplug_slot);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pci/hotplug/pciehp_ctrl.c (0)
Location: drivers/pci/hotplug/pciehp_ctrl.c:360
Inline: False
```
**Symbols:**

```
ffffffff81ce8c85-ffffffff81ce8d1c: pciehp_sysfs_enable_slot.cold (STB_LOCAL)
ffffffff816c3bb0-ffffffff816c3c8b: pciehp_sysfs_enable_slot (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int pciehp_sysfs_enable_slot(struct hotplug_slot *hotplug_slot);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pci/hotplug/pciehp_ctrl.c (0)
Location: drivers/pci/hotplug/pciehp_ctrl.c:360
Inline: False
```
**Symbols:**

```
ffffffff81eafd2f-ffffffff81eafdc6: pciehp_sysfs_enable_slot.cold (STB_LOCAL)
ffffffff817e9680-ffffffff817e978f: pciehp_sysfs_enable_slot (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int pciehp_sysfs_enable_slot(struct hotplug_slot *hotplug_slot);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/hotplug/pciehp_ctrl.c (ffffffff8190f550)
Location: drivers/pci/hotplug/pciehp_ctrl.c:360
Inline: False
```
**Symbols:**

```
ffffffff8190f550-ffffffff8190f702: pciehp_sysfs_enable_slot (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int pciehp_sysfs_enable_slot(struct hotplug_slot *hotplug_slot);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/hotplug/pciehp_ctrl.c (ffffffff81952c50)
Location: drivers/pci/hotplug/pciehp_ctrl.c:369
Inline: False
```
**Symbols:**

```
ffffffff81952c50-ffffffff81952dfe: pciehp_sysfs_enable_slot (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int pciehp_sysfs_enable_slot(struct hotplug_slot *hotplug_slot);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/hotplug/pciehp_ctrl.c (ffffffff8199c0e0)
Location: drivers/pci/hotplug/pciehp_ctrl.c:369
Inline: False
```
**Symbols:**

```
ffffffff8199c0e0-ffffffff8199c28e: pciehp_sysfs_enable_slot (STB_GLOBAL)
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
int pciehp_sysfs_enable_slot(struct hotplug_slot *hotplug_slot);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/hotplug/pciehp_ctrl.c (ffff80001070b1d0)
Location: drivers/pci/hotplug/pciehp_ctrl.c:362
Inline: False
```
**Symbols:**

```
ffff80001070b1d0-ffff80001070b34c: pciehp_sysfs_enable_slot (STB_GLOBAL)
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
int pciehp_sysfs_enable_slot(struct hotplug_slot *hotplug_slot);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/hotplug/pciehp_ctrl.c (ffffffe0004d7eac)
Location: drivers/pci/hotplug/pciehp_ctrl.c:362
Inline: False
```
**Symbols:**

```
ffffffe0004d7eac-ffffffe0004d7ff8: pciehp_sysfs_enable_slot (STB_GLOBAL)
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
int pciehp_sysfs_enable_slot(struct hotplug_slot *hotplug_slot);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pci/hotplug/pciehp_ctrl.c (0)
Location: drivers/pci/hotplug/pciehp_ctrl.c:362
Inline: False
```
**Symbols:**

```
ffffffff8159636d-ffffffff81596404: pciehp_sysfs_enable_slot.cold (STB_LOCAL)
ffffffff81595e70-ffffffff81595f4b: pciehp_sysfs_enable_slot (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Transformation ⚠️</summary>

```c
int pciehp_sysfs_enable_slot(struct hotplug_slot *hotplug_slot);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pci/hotplug/pciehp_ctrl.c (0)
Location: drivers/pci/hotplug/pciehp_ctrl.c:362
Inline: False
```
**Symbols:**

```
ffffffff815854fd-ffffffff81585594: pciehp_sysfs_enable_slot.cold (STB_LOCAL)
ffffffff81585000-ffffffff815850db: pciehp_sysfs_enable_slot (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Transformation ⚠️</summary>

```c
int pciehp_sysfs_enable_slot(struct hotplug_slot *hotplug_slot);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pci/hotplug/pciehp_ctrl.c (0)
Location: drivers/pci/hotplug/pciehp_ctrl.c:362
Inline: False
```
**Symbols:**

```
ffffffff815968ad-ffffffff81596944: pciehp_sysfs_enable_slot.cold (STB_LOCAL)
ffffffff815963b0-ffffffff8159648b: pciehp_sysfs_enable_slot (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
int pciehp_sysfs_enable_slot(struct hotplug_slot *hotplug_slot);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pci/hotplug/pciehp_ctrl.c (0)
Location: drivers/pci/hotplug/pciehp_ctrl.c:362
Inline: False
```
**Symbols:**

```
ffffffff815b0d28-ffffffff815b0dbf: pciehp_sysfs_enable_slot.cold (STB_LOCAL)
ffffffff815b0830-ffffffff815b0906: pciehp_sysfs_enable_slot (STB_GLOBAL)
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
