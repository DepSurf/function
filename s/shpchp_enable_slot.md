# Function: <code>shpchp_enable_slot</code>

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
int shpchp_enable_slot(struct slot *p_slot);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/hotplug/shpchp_ctrl.c (ffffffff8153cd60)
Location: drivers/pci/hotplug/shpchp_ctrl.c:555
Inline: False
Direct callers:
  - drivers/pci/hotplug/shpchp_ctrl.c:shpchp_sysfs_enable_slot
  - drivers/pci/hotplug/shpchp_ctrl.c:shpchp_pushbutton_thread
```
**Symbols:**

```
ffffffff8153cd60-ffffffff8153d107: shpchp_enable_slot (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int shpchp_enable_slot(struct slot *p_slot);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/hotplug/shpchp_ctrl.c (ffffffff81554170)
Location: drivers/pci/hotplug/shpchp_ctrl.c:544
Inline: False
Direct callers:
  - drivers/pci/hotplug/shpchp_ctrl.c:shpchp_sysfs_enable_slot
  - drivers/pci/hotplug/shpchp_ctrl.c:shpchp_pushbutton_thread
```
**Symbols:**

```
ffffffff81554170-ffffffff8155450b: shpchp_enable_slot (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
int shpchp_enable_slot(struct slot *p_slot);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pci/hotplug/shpchp_ctrl.c (0)
Location: drivers/pci/hotplug/shpchp_ctrl.c:544
Inline: False
Direct callers:
  - drivers/pci/hotplug/shpchp_ctrl.c:shpchp_sysfs_enable_slot
  - drivers/pci/hotplug/shpchp_ctrl.c:shpchp_pushbutton_thread
```
**Symbols:**

```
ffffffff81583d20-ffffffff81583fd8: shpchp_enable_slot (STB_LOCAL)
ffffffff81584988-ffffffff81584a65: shpchp_enable_slot.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
int shpchp_enable_slot(struct slot *p_slot);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pci/hotplug/shpchp_ctrl.c (0)
Location: drivers/pci/hotplug/shpchp_ctrl.c:544
Inline: False
Direct callers:
  - drivers/pci/hotplug/shpchp_ctrl.c:shpchp_sysfs_enable_slot
  - drivers/pci/hotplug/shpchp_ctrl.c:shpchp_pushbutton_thread
```
**Symbols:**

```
ffffffff815a5700-ffffffff815a59b8: shpchp_enable_slot (STB_LOCAL)
ffffffff815a6368-ffffffff815a6445: shpchp_enable_slot.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
int shpchp_enable_slot(struct slot *p_slot);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pci/hotplug/shpchp_ctrl.c (0)
Location: drivers/pci/hotplug/shpchp_ctrl.c:543
Inline: False
Direct callers:
  - drivers/pci/hotplug/shpchp_ctrl.c:shpchp_sysfs_enable_slot
  - drivers/pci/hotplug/shpchp_ctrl.c:shpchp_pushbutton_thread
```
**Symbols:**

```
ffffffff8164e2a0-ffffffff8164e465: shpchp_enable_slot (STB_LOCAL)
ffffffff8164ef78-ffffffff8164f029: shpchp_enable_slot.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
int shpchp_enable_slot(struct slot *p_slot);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pci/hotplug/shpchp_ctrl.c (0)
Location: drivers/pci/hotplug/shpchp_ctrl.c:542
Inline: False
Direct callers:
  - drivers/pci/hotplug/shpchp_ctrl.c:shpchp_sysfs_enable_slot
  - drivers/pci/hotplug/shpchp_ctrl.c:shpchp_pushbutton_thread
```
**Symbols:**

```
ffffffff81672210-ffffffff816723d5: shpchp_enable_slot (STB_LOCAL)
ffffffff81bfc9c9-ffffffff81bfca7a: shpchp_enable_slot.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
int shpchp_enable_slot(struct slot *p_slot);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pci/hotplug/shpchp_ctrl.c (0)
Location: drivers/pci/hotplug/shpchp_ctrl.c:542
Inline: False
Direct callers:
  - drivers/pci/hotplug/shpchp_ctrl.c:shpchp_sysfs_enable_slot
  - drivers/pci/hotplug/shpchp_ctrl.c:shpchp_pushbutton_thread
```
**Symbols:**

```
ffffffff81654720-ffffffff816548e5: shpchp_enable_slot (STB_LOCAL)
ffffffff81bee8b4-ffffffff81bee965: shpchp_enable_slot.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int shpchp_enable_slot(struct slot *p_slot);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pci/hotplug/shpchp_ctrl.c (0)
Location: drivers/pci/hotplug/shpchp_ctrl.c:542
Inline: False
Direct callers:
  - drivers/pci/hotplug/shpchp_ctrl.c:shpchp_sysfs_enable_slot
  - drivers/pci/hotplug/shpchp_ctrl.c:shpchp_pushbutton_thread
```
**Symbols:**

```
ffffffff816c65d0-ffffffff816c67a8: shpchp_enable_slot (STB_LOCAL)
ffffffff81ce9864-ffffffff81ce9926: shpchp_enable_slot.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int shpchp_enable_slot(struct slot *p_slot);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pci/hotplug/shpchp_ctrl.c (0)
Location: drivers/pci/hotplug/shpchp_ctrl.c:542
Inline: False
Direct callers:
  - drivers/pci/hotplug/shpchp_ctrl.c:shpchp_sysfs_enable_slot
  - drivers/pci/hotplug/shpchp_ctrl.c:shpchp_pushbutton_thread
```
**Symbols:**

```
ffffffff817ec530-ffffffff817ec71e: shpchp_enable_slot (STB_LOCAL)
ffffffff81eb0948-ffffffff81eb09f8: shpchp_enable_slot.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
int shpchp_enable_slot(struct slot *p_slot);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pci/hotplug/shpchp_ctrl.c (0)
Location: drivers/pci/hotplug/shpchp_ctrl.c:542
Inline: False
Direct callers:
  - drivers/pci/hotplug/shpchp_ctrl.c:shpchp_sysfs_enable_slot
  - drivers/pci/hotplug/shpchp_ctrl.c:shpchp_pushbutton_thread
```
**Symbols:**

```
ffffffff819130b0-ffffffff81913343: shpchp_enable_slot (STB_LOCAL)
ffffffff8208fb30-ffffffff8208fb45: shpchp_enable_slot.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
int shpchp_enable_slot(struct slot *p_slot);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pci/hotplug/shpchp_ctrl.c (0)
Location: drivers/pci/hotplug/shpchp_ctrl.c:542
Inline: False
Direct callers:
  - drivers/pci/hotplug/shpchp_ctrl.c:shpchp_sysfs_enable_slot
  - drivers/pci/hotplug/shpchp_ctrl.c:shpchp_pushbutton_thread
```
**Symbols:**

```
ffffffff81956720-ffffffff819569b3: shpchp_enable_slot (STB_LOCAL)
ffffffff8210fe8c-ffffffff8210fea1: shpchp_enable_slot.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
int shpchp_enable_slot(struct slot *p_slot);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pci/hotplug/shpchp_ctrl.c (0)
Location: drivers/pci/hotplug/shpchp_ctrl.c:542
Inline: False
Direct callers:
  - drivers/pci/hotplug/shpchp_ctrl.c:shpchp_sysfs_enable_slot
  - drivers/pci/hotplug/shpchp_ctrl.c:shpchp_pushbutton_thread
```
**Symbols:**

```
ffffffff8199fc40-ffffffff8199fed3: shpchp_enable_slot (STB_LOCAL)
ffffffff821edbb4-ffffffff821edbc9: shpchp_enable_slot.cold (STB_LOCAL)
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
int shpchp_enable_slot(struct slot *p_slot);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/hotplug/shpchp_ctrl.c (ffff80001070e748)
Location: drivers/pci/hotplug/shpchp_ctrl.c:544
Inline: False
Direct callers:
  - drivers/pci/hotplug/shpchp_ctrl.c:shpchp_sysfs_enable_slot
  - drivers/pci/hotplug/shpchp_ctrl.c:shpchp_pushbutton_thread
```
**Symbols:**

```
ffff80001070e748-ffff80001070eaac: shpchp_enable_slot (STB_LOCAL)
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
int shpchp_enable_slot(struct slot *p_slot);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/hotplug/shpchp_ctrl.c (ffffffe0004dabc4)
Location: drivers/pci/hotplug/shpchp_ctrl.c:544
Inline: False
Direct callers:
  - drivers/pci/hotplug/shpchp_ctrl.c:shpchp_sysfs_enable_slot
  - drivers/pci/hotplug/shpchp_ctrl.c:shpchp_pushbutton_thread
```
**Symbols:**

```
ffffffe0004dabc4-ffffffe0004daed8: shpchp_enable_slot (STB_LOCAL)
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
int shpchp_enable_slot(struct slot *p_slot);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pci/hotplug/shpchp_ctrl.c (0)
Location: drivers/pci/hotplug/shpchp_ctrl.c:544
Inline: False
Direct callers:
  - drivers/pci/hotplug/shpchp_ctrl.c:shpchp_sysfs_enable_slot
  - drivers/pci/hotplug/shpchp_ctrl.c:shpchp_pushbutton_thread
```
**Symbols:**

```
ffffffff81598f10-ffffffff815991c8: shpchp_enable_slot (STB_LOCAL)
ffffffff81599b78-ffffffff81599c55: shpchp_enable_slot.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Transformation ⚠️</summary>

```c
int shpchp_enable_slot(struct slot *p_slot);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pci/hotplug/shpchp_ctrl.c (0)
Location: drivers/pci/hotplug/shpchp_ctrl.c:544
Inline: False
Direct callers:
  - drivers/pci/hotplug/shpchp_ctrl.c:shpchp_sysfs_enable_slot
  - drivers/pci/hotplug/shpchp_ctrl.c:shpchp_pushbutton_thread
```
**Symbols:**

```
ffffffff815880a0-ffffffff81588358: shpchp_enable_slot (STB_LOCAL)
ffffffff81588d08-ffffffff81588de5: shpchp_enable_slot.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Transformation ⚠️</summary>

```c
int shpchp_enable_slot(struct slot *p_slot);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pci/hotplug/shpchp_ctrl.c (0)
Location: drivers/pci/hotplug/shpchp_ctrl.c:544
Inline: False
Direct callers:
  - drivers/pci/hotplug/shpchp_ctrl.c:shpchp_sysfs_enable_slot
  - drivers/pci/hotplug/shpchp_ctrl.c:shpchp_pushbutton_thread
```
**Symbols:**

```
ffffffff81599450-ffffffff81599708: shpchp_enable_slot (STB_LOCAL)
ffffffff8159a0b8-ffffffff8159a195: shpchp_enable_slot.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
int shpchp_enable_slot(struct slot *p_slot);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pci/hotplug/shpchp_ctrl.c (0)
Location: drivers/pci/hotplug/shpchp_ctrl.c:544
Inline: False
Direct callers:
  - drivers/pci/hotplug/shpchp_ctrl.c:shpchp_sysfs_enable_slot
  - drivers/pci/hotplug/shpchp_ctrl.c:shpchp_pushbutton_thread
```
**Symbols:**

```
ffffffff815b3890-ffffffff815b3b48: shpchp_enable_slot (STB_LOCAL)
ffffffff815b44f8-ffffffff815b45d5: shpchp_enable_slot.cold (STB_LOCAL)
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
