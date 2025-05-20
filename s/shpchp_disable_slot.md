# Function: <code>shpchp_disable_slot</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4</code>: Absent ⚠️
</li>
<li>
In <code>4.8</code>: Absent ⚠️
</li>
<li>
In <code>4.10</code>: Absent ⚠️
</li>
<li>
In <code>4.13</code>: Absent ⚠️
</li>
<li>
In <code>4.15</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int shpchp_disable_slot(struct slot *p_slot);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/hotplug/shpchp_ctrl.c (ffffffff8153c600)
Location: drivers/pci/hotplug/shpchp_ctrl.c:612
Inline: False
Direct callers:
  - drivers/pci/hotplug/shpchp_ctrl.c:shpchp_sysfs_disable_slot
  - drivers/pci/hotplug/shpchp_ctrl.c:shpchp_pushbutton_thread
```
**Symbols:**

```
ffffffff8153c600-ffffffff8153c8ac: shpchp_disable_slot (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int shpchp_disable_slot(struct slot *p_slot);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/hotplug/shpchp_ctrl.c (ffffffff81553a20)
Location: drivers/pci/hotplug/shpchp_ctrl.c:601
Inline: False
Direct callers:
  - drivers/pci/hotplug/shpchp_ctrl.c:shpchp_sysfs_disable_slot
  - drivers/pci/hotplug/shpchp_ctrl.c:shpchp_pushbutton_thread
```
**Symbols:**

```
ffffffff81553a20-ffffffff81553cbc: shpchp_disable_slot (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
int shpchp_disable_slot(struct slot *p_slot);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pci/hotplug/shpchp_ctrl.c (0)
Location: drivers/pci/hotplug/shpchp_ctrl.c:601
Inline: False
Direct callers:
  - drivers/pci/hotplug/shpchp_ctrl.c:shpchp_sysfs_disable_slot
  - drivers/pci/hotplug/shpchp_ctrl.c:shpchp_pushbutton_thread
```
**Symbols:**

```
ffffffff815838d0-ffffffff81583a82: shpchp_disable_slot (STB_LOCAL)
ffffffff815845ed-ffffffff81584704: shpchp_disable_slot.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
int shpchp_disable_slot(struct slot *p_slot);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pci/hotplug/shpchp_ctrl.c (0)
Location: drivers/pci/hotplug/shpchp_ctrl.c:601
Inline: False
Direct callers:
  - drivers/pci/hotplug/shpchp_ctrl.c:shpchp_sysfs_disable_slot
  - drivers/pci/hotplug/shpchp_ctrl.c:shpchp_pushbutton_thread
```
**Symbols:**

```
ffffffff815a52b0-ffffffff815a5462: shpchp_disable_slot (STB_LOCAL)
ffffffff815a5fcd-ffffffff815a60e4: shpchp_disable_slot.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
int shpchp_disable_slot(struct slot *p_slot);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pci/hotplug/shpchp_ctrl.c (0)
Location: drivers/pci/hotplug/shpchp_ctrl.c:600
Inline: False
Direct callers:
  - drivers/pci/hotplug/shpchp_ctrl.c:shpchp_sysfs_disable_slot
  - drivers/pci/hotplug/shpchp_ctrl.c:shpchp_pushbutton_thread
```
**Symbols:**

```
ffffffff8164e5a0-ffffffff8164e691: shpchp_disable_slot (STB_LOCAL)
ffffffff8164f0ce-ffffffff8164f14f: shpchp_disable_slot.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
int shpchp_disable_slot(struct slot *p_slot);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pci/hotplug/shpchp_ctrl.c (0)
Location: drivers/pci/hotplug/shpchp_ctrl.c:599
Inline: False
Direct callers:
  - drivers/pci/hotplug/shpchp_ctrl.c:shpchp_sysfs_disable_slot
  - drivers/pci/hotplug/shpchp_ctrl.c:shpchp_pushbutton_thread
```
**Symbols:**

```
ffffffff81672510-ffffffff81672601: shpchp_disable_slot (STB_LOCAL)
ffffffff81bfcb1f-ffffffff81bfcba0: shpchp_disable_slot.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
int shpchp_disable_slot(struct slot *p_slot);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pci/hotplug/shpchp_ctrl.c (0)
Location: drivers/pci/hotplug/shpchp_ctrl.c:599
Inline: False
Direct callers:
  - drivers/pci/hotplug/shpchp_ctrl.c:shpchp_sysfs_disable_slot
  - drivers/pci/hotplug/shpchp_ctrl.c:shpchp_pushbutton_thread
```
**Symbols:**

```
ffffffff816548f0-ffffffff81654a88: shpchp_disable_slot (STB_LOCAL)
ffffffff81bee965-ffffffff81beea7b: shpchp_disable_slot.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int shpchp_disable_slot(struct slot *p_slot);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pci/hotplug/shpchp_ctrl.c (0)
Location: drivers/pci/hotplug/shpchp_ctrl.c:599
Inline: False
Direct callers:
  - drivers/pci/hotplug/shpchp_ctrl.c:shpchp_sysfs_disable_slot
  - drivers/pci/hotplug/shpchp_ctrl.c:shpchp_pushbutton_thread
```
**Symbols:**

```
ffffffff816c67b0-ffffffff816c6957: shpchp_disable_slot (STB_LOCAL)
ffffffff81ce9926-ffffffff81ce9a5f: shpchp_disable_slot.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int shpchp_disable_slot(struct slot *p_slot);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pci/hotplug/shpchp_ctrl.c (0)
Location: drivers/pci/hotplug/shpchp_ctrl.c:599
Inline: False
Direct callers:
  - drivers/pci/hotplug/shpchp_ctrl.c:shpchp_sysfs_disable_slot
  - drivers/pci/hotplug/shpchp_ctrl.c:shpchp_pushbutton_thread
```
**Symbols:**

```
ffffffff817ec720-ffffffff817ec8dd: shpchp_disable_slot (STB_LOCAL)
ffffffff81eb09f8-ffffffff81eb0b25: shpchp_disable_slot.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
int shpchp_disable_slot(struct slot *p_slot);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pci/hotplug/shpchp_ctrl.c (0)
Location: drivers/pci/hotplug/shpchp_ctrl.c:599
Inline: False
Direct callers:
  - drivers/pci/hotplug/shpchp_ctrl.c:shpchp_sysfs_disable_slot
  - drivers/pci/hotplug/shpchp_ctrl.c:shpchp_pushbutton_thread
```
**Symbols:**

```
ffffffff81913360-ffffffff8191361e: shpchp_disable_slot (STB_LOCAL)
ffffffff8208fb45-ffffffff8208fb61: shpchp_disable_slot.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
int shpchp_disable_slot(struct slot *p_slot);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pci/hotplug/shpchp_ctrl.c (0)
Location: drivers/pci/hotplug/shpchp_ctrl.c:599
Inline: False
Direct callers:
  - drivers/pci/hotplug/shpchp_ctrl.c:shpchp_sysfs_disable_slot
  - drivers/pci/hotplug/shpchp_ctrl.c:shpchp_pushbutton_thread
```
**Symbols:**

```
ffffffff819569d0-ffffffff81956c8e: shpchp_disable_slot (STB_LOCAL)
ffffffff8210fea1-ffffffff8210febd: shpchp_disable_slot.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
int shpchp_disable_slot(struct slot *p_slot);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pci/hotplug/shpchp_ctrl.c (0)
Location: drivers/pci/hotplug/shpchp_ctrl.c:599
Inline: False
Direct callers:
  - drivers/pci/hotplug/shpchp_ctrl.c:shpchp_sysfs_disable_slot
  - drivers/pci/hotplug/shpchp_ctrl.c:shpchp_pushbutton_thread
```
**Symbols:**

```
ffffffff8199fef0-ffffffff819a01ae: shpchp_disable_slot (STB_LOCAL)
ffffffff821edbc9-ffffffff821edbe5: shpchp_disable_slot.cold (STB_LOCAL)
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
int shpchp_disable_slot(struct slot *p_slot);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/hotplug/shpchp_ctrl.c (ffff80001070e010)
Location: drivers/pci/hotplug/shpchp_ctrl.c:601
Inline: False
Direct callers:
  - drivers/pci/hotplug/shpchp_ctrl.c:shpchp_sysfs_disable_slot
  - drivers/pci/hotplug/shpchp_ctrl.c:shpchp_pushbutton_thread
```
**Symbols:**

```
ffff80001070e010-ffff80001070e2a0: shpchp_disable_slot (STB_LOCAL)
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
int shpchp_disable_slot(struct slot *p_slot);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/hotplug/shpchp_ctrl.c (ffffffe0004da5f2)
Location: drivers/pci/hotplug/shpchp_ctrl.c:601
Inline: False
Direct callers:
  - drivers/pci/hotplug/shpchp_ctrl.c:shpchp_sysfs_disable_slot
  - drivers/pci/hotplug/shpchp_ctrl.c:shpchp_pushbutton_thread
```
**Symbols:**

```
ffffffe0004da5f2-ffffffe0004da7f6: shpchp_disable_slot (STB_LOCAL)
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
int shpchp_disable_slot(struct slot *p_slot);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pci/hotplug/shpchp_ctrl.c (0)
Location: drivers/pci/hotplug/shpchp_ctrl.c:601
Inline: False
Direct callers:
  - drivers/pci/hotplug/shpchp_ctrl.c:shpchp_sysfs_disable_slot
  - drivers/pci/hotplug/shpchp_ctrl.c:shpchp_pushbutton_thread
```
**Symbols:**

```
ffffffff81598ac0-ffffffff81598c72: shpchp_disable_slot (STB_LOCAL)
ffffffff815997dd-ffffffff815998f4: shpchp_disable_slot.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Transformation ⚠️</summary>

```c
int shpchp_disable_slot(struct slot *p_slot);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pci/hotplug/shpchp_ctrl.c (0)
Location: drivers/pci/hotplug/shpchp_ctrl.c:601
Inline: False
Direct callers:
  - drivers/pci/hotplug/shpchp_ctrl.c:shpchp_sysfs_disable_slot
  - drivers/pci/hotplug/shpchp_ctrl.c:shpchp_pushbutton_thread
```
**Symbols:**

```
ffffffff81587c50-ffffffff81587e02: shpchp_disable_slot (STB_LOCAL)
ffffffff8158896d-ffffffff81588a84: shpchp_disable_slot.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Transformation ⚠️</summary>

```c
int shpchp_disable_slot(struct slot *p_slot);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pci/hotplug/shpchp_ctrl.c (0)
Location: drivers/pci/hotplug/shpchp_ctrl.c:601
Inline: False
Direct callers:
  - drivers/pci/hotplug/shpchp_ctrl.c:shpchp_sysfs_disable_slot
  - drivers/pci/hotplug/shpchp_ctrl.c:shpchp_pushbutton_thread
```
**Symbols:**

```
ffffffff81599000-ffffffff815991b2: shpchp_disable_slot (STB_LOCAL)
ffffffff81599d1d-ffffffff81599e34: shpchp_disable_slot.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
int shpchp_disable_slot(struct slot *p_slot);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pci/hotplug/shpchp_ctrl.c (0)
Location: drivers/pci/hotplug/shpchp_ctrl.c:601
Inline: False
Direct callers:
  - drivers/pci/hotplug/shpchp_ctrl.c:shpchp_sysfs_disable_slot
  - drivers/pci/hotplug/shpchp_ctrl.c:shpchp_pushbutton_thread
```
**Symbols:**

```
ffffffff815b3440-ffffffff815b35f2: shpchp_disable_slot (STB_LOCAL)
ffffffff815b415d-ffffffff815b4274: shpchp_disable_slot.cold (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
