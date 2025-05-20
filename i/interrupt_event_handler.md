# Function: <code>interrupt_event_handler</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void interrupt_event_handler(struct work_struct *work);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/hotplug/pciehp_ctrl.c (ffffffff8144f490)
Location: drivers/pci/hotplug/pciehp_ctrl.c:362
Inline: False
```
**Symbols:**

```
ffffffff8144f490-ffffffff8144f798: interrupt_event_handler (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Collision ⚠️</summary>

```c
void interrupt_event_handler(struct work_struct *work);
```

**Collision:** Static-Static Collision

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pcie/pcie-dpc.c (ffffffff81498350)
Location: drivers/pci/pcie/pcie-dpc.c:37
Inline: False
```
```
In drivers/pci/hotplug/pciehp_ctrl.c (ffffffff8149bc30)
Location: drivers/pci/hotplug/pciehp_ctrl.c:362
Inline: False
```
**Symbols:**

```
ffffffff81498350-ffffffff81498455: interrupt_event_handler (STB_LOCAL)
ffffffff8149bc30-ffffffff8149bf38: interrupt_event_handler (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Collision ⚠️</summary>

```c
void interrupt_event_handler(struct work_struct *work);
```

**Collision:** Static-Static Collision

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pcie/pcie-dpc.c (ffffffff814b9c00)
Location: drivers/pci/pcie/pcie-dpc.c:39
Inline: False
```
```
In drivers/pci/hotplug/pciehp_ctrl.c (ffffffff814bd7c0)
Location: drivers/pci/hotplug/pciehp_ctrl.c:347
Inline: False
```
**Symbols:**

```
ffffffff814b9c00-ffffffff814b9d05: interrupt_event_handler (STB_LOCAL)
ffffffff814bd7c0-ffffffff814bdace: interrupt_event_handler (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Collision ⚠️</summary>

```c
void interrupt_event_handler(struct work_struct *work);
```

**Collision:** Static-Static Collision

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pcie/pcie-dpc.c (ffffffff814c45b0)
Location: drivers/pci/pcie/pcie-dpc.c:60
Inline: False
```
```
In drivers/pci/hotplug/pciehp_ctrl.c (ffffffff814c7fa0)
Location: drivers/pci/hotplug/pciehp_ctrl.c:347
Inline: False
```
**Symbols:**

```
ffffffff814c45b0-ffffffff814c4742: interrupt_event_handler (STB_LOCAL)
ffffffff814c7fa0-ffffffff814c82ab: interrupt_event_handler (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Collision ⚠️</summary>

```c
void interrupt_event_handler(struct work_struct *work);
```

**Collision:** Static-Static Collision

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pcie/pcie-dpc.c (ffffffff81504ac0)
Location: drivers/pci/pcie/pcie-dpc.c:108
Inline: False
```
```
In drivers/pci/hotplug/pciehp_ctrl.c (ffffffff81508540)
Location: drivers/pci/hotplug/pciehp_ctrl.c:348
Inline: False
```
**Symbols:**

```
ffffffff81504ac0-ffffffff81504c95: interrupt_event_handler (STB_LOCAL)
ffffffff81508540-ffffffff8150885d: interrupt_event_handler (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Collision ⚠️</summary>

```c
void interrupt_event_handler(struct work_struct *work);
```

**Collision:** Static-Static Collision

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/hotplug/pciehp_ctrl.c (ffffffff81539480)
Location: drivers/pci/hotplug/pciehp_ctrl.c:334
Inline: False
```
```
In drivers/pci/hotplug/shpchp_ctrl.c (ffffffff8153c2d0)
Location: drivers/pci/hotplug/shpchp_ctrl.c:530
Inline: False
```
**Symbols:**

```
ffffffff81539480-ffffffff8153979d: interrupt_event_handler (STB_LOCAL)
ffffffff8153c2d0-ffffffff8153c577: interrupt_event_handler (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void interrupt_event_handler(struct work_struct *work);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/hotplug/shpchp_ctrl.c (ffffffff81553710)
Location: drivers/pci/hotplug/shpchp_ctrl.c:519
Inline: False
```
**Symbols:**

```
ffffffff81553710-ffffffff8155399b: interrupt_event_handler (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
void interrupt_event_handler(struct work_struct *work);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pci/hotplug/shpchp_ctrl.c (0)
Location: drivers/pci/hotplug/shpchp_ctrl.c:519
Inline: False
```
**Symbols:**

```
ffffffff81583710-ffffffff81583841: interrupt_event_handler (STB_LOCAL)
ffffffff81584479-ffffffff815845ed: interrupt_event_handler.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
void interrupt_event_handler(struct work_struct *work);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pci/hotplug/shpchp_ctrl.c (0)
Location: drivers/pci/hotplug/shpchp_ctrl.c:519
Inline: False
```
**Symbols:**

```
ffffffff815a50f0-ffffffff815a5221: interrupt_event_handler (STB_LOCAL)
ffffffff815a5e59-ffffffff815a5fcd: interrupt_event_handler.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
void interrupt_event_handler(struct work_struct *work);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pci/hotplug/shpchp_ctrl.c (0)
Location: drivers/pci/hotplug/shpchp_ctrl.c:518
Inline: False
```
**Symbols:**

```
ffffffff8164de40-ffffffff8164ded6: interrupt_event_handler (STB_LOCAL)
ffffffff8164ec97-ffffffff8164ecc6: interrupt_event_handler.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
void interrupt_event_handler(struct work_struct *work);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pci/hotplug/shpchp_ctrl.c (0)
Location: drivers/pci/hotplug/shpchp_ctrl.c:517
Inline: False
```
**Symbols:**

```
ffffffff81671db0-ffffffff81671e46: interrupt_event_handler (STB_LOCAL)
ffffffff81bfc6e8-ffffffff81bfc717: interrupt_event_handler.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
void interrupt_event_handler(struct work_struct *work);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pci/hotplug/shpchp_ctrl.c (0)
Location: drivers/pci/hotplug/shpchp_ctrl.c:517
Inline: False
```
**Symbols:**

```
ffffffff816542c0-ffffffff81654356: interrupt_event_handler (STB_LOCAL)
ffffffff81bee5d3-ffffffff81bee602: interrupt_event_handler.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
void interrupt_event_handler(struct work_struct *work);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pci/hotplug/shpchp_ctrl.c (0)
Location: drivers/pci/hotplug/shpchp_ctrl.c:517
Inline: False
```
**Symbols:**

```
ffffffff816c6160-ffffffff816c6202: interrupt_event_handler (STB_LOCAL)
ffffffff81ce955d-ffffffff81ce95a0: interrupt_event_handler.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
void interrupt_event_handler(struct work_struct *work);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pci/hotplug/shpchp_ctrl.c (0)
Location: drivers/pci/hotplug/shpchp_ctrl.c:517
Inline: False
```
**Symbols:**

```
ffffffff817ec070-ffffffff817ec120: interrupt_event_handler (STB_LOCAL)
ffffffff81eb05fd-ffffffff81eb0640: interrupt_event_handler.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
void interrupt_event_handler(struct work_struct *work);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pci/hotplug/shpchp_ctrl.c (0)
Location: drivers/pci/hotplug/shpchp_ctrl.c:517
Inline: False
```
**Symbols:**

```
ffffffff81912980-ffffffff81912a58: interrupt_event_handler (STB_LOCAL)
ffffffff8208fa5f-ffffffff8208fa73: interrupt_event_handler.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
void interrupt_event_handler(struct work_struct *work);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pci/hotplug/shpchp_ctrl.c (0)
Location: drivers/pci/hotplug/shpchp_ctrl.c:517
Inline: False
```
**Symbols:**

```
ffffffff81956000-ffffffff819560d8: interrupt_event_handler (STB_LOCAL)
ffffffff8210fdbf-ffffffff8210fdd3: interrupt_event_handler.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
void interrupt_event_handler(struct work_struct *work);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pci/hotplug/shpchp_ctrl.c (0)
Location: drivers/pci/hotplug/shpchp_ctrl.c:517
Inline: False
```
**Symbols:**

```
ffffffff8199f520-ffffffff8199f5f8: interrupt_event_handler (STB_LOCAL)
ffffffff821edae7-ffffffff821edafb: interrupt_event_handler.cold (STB_LOCAL)
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
void interrupt_event_handler(struct work_struct *work);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/hotplug/shpchp_ctrl.c (ffff80001070dcf8)
Location: drivers/pci/hotplug/shpchp_ctrl.c:519
Inline: False
```
**Symbols:**

```
ffff80001070dcf8-ffff80001070df8c: interrupt_event_handler (STB_LOCAL)
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
void interrupt_event_handler(struct work_struct *work);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/hotplug/shpchp_ctrl.c (ffffffe0004da352)
Location: drivers/pci/hotplug/shpchp_ctrl.c:519
Inline: False
```
**Symbols:**

```
ffffffe0004da352-ffffffe0004da578: interrupt_event_handler (STB_LOCAL)
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
void interrupt_event_handler(struct work_struct *work);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pci/hotplug/shpchp_ctrl.c (0)
Location: drivers/pci/hotplug/shpchp_ctrl.c:519
Inline: False
```
**Symbols:**

```
ffffffff81598900-ffffffff81598a31: interrupt_event_handler (STB_LOCAL)
ffffffff81599669-ffffffff815997dd: interrupt_event_handler.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Transformation ⚠️</summary>

```c
void interrupt_event_handler(struct work_struct *work);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pci/hotplug/shpchp_ctrl.c (0)
Location: drivers/pci/hotplug/shpchp_ctrl.c:519
Inline: False
```
**Symbols:**

```
ffffffff81587a90-ffffffff81587bc1: interrupt_event_handler (STB_LOCAL)
ffffffff815887f9-ffffffff8158896d: interrupt_event_handler.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Transformation ⚠️</summary>

```c
void interrupt_event_handler(struct work_struct *work);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pci/hotplug/shpchp_ctrl.c (0)
Location: drivers/pci/hotplug/shpchp_ctrl.c:519
Inline: False
```
**Symbols:**

```
ffffffff81598e40-ffffffff81598f71: interrupt_event_handler (STB_LOCAL)
ffffffff81599ba9-ffffffff81599d1d: interrupt_event_handler.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
void interrupt_event_handler(struct work_struct *work);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pci/hotplug/shpchp_ctrl.c (0)
Location: drivers/pci/hotplug/shpchp_ctrl.c:519
Inline: False
```
**Symbols:**

```
ffffffff815b3280-ffffffff815b33b1: interrupt_event_handler (STB_LOCAL)
ffffffff815b3fe9-ffffffff815b415d: interrupt_event_handler.cold (STB_LOCAL)
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
