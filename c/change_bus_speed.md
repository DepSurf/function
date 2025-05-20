# Function: <code>change_bus_speed</code>

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
<summary>In <code>4.18</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/pci/hotplug/shpchp_ctrl.c (ffffffff8153c8b0)
Location: drivers/pci/hotplug/shpchp_ctrl.c:178
Inline: True
Direct callers:
  - drivers/pci/hotplug/shpchp_ctrl.c:board_added
  - drivers/pci/hotplug/shpchp_ctrl.c:board_added
```
**Symbols:**

```
ffffffff8153c8b0-ffffffff8153c939: change_bus_speed.isra.6 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/pci/hotplug/shpchp_ctrl.c (ffffffff81553cc0)
Location: drivers/pci/hotplug/shpchp_ctrl.c:178
Inline: True
Direct callers:
  - drivers/pci/hotplug/shpchp_ctrl.c:board_added
  - drivers/pci/hotplug/shpchp_ctrl.c:board_added
```
**Symbols:**

```
ffffffff81553cc0-ffffffff81553d49: change_bus_speed.isra.5 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/pci/hotplug/shpchp_ctrl.c (ffffffff81584728)
Location: drivers/pci/hotplug/shpchp_ctrl.c:178
Inline: True
Direct callers:
  - drivers/pci/hotplug/shpchp_ctrl.c:board_added
  - drivers/pci/hotplug/shpchp_ctrl.c:board_added
```
**Symbols:**

```
ffffffff81583a90-ffffffff81583ad7: change_bus_speed.isra.0 (STB_LOCAL)
ffffffff81584704-ffffffff8158474f: change_bus_speed.isra.0.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/pci/hotplug/shpchp_ctrl.c (ffffffff815a6108)
Location: drivers/pci/hotplug/shpchp_ctrl.c:178
Inline: True
Direct callers:
  - drivers/pci/hotplug/shpchp_ctrl.c:board_added
  - drivers/pci/hotplug/shpchp_ctrl.c:board_added
```
**Symbols:**

```
ffffffff815a5470-ffffffff815a54b7: change_bus_speed.isra.0 (STB_LOCAL)
ffffffff815a60e4-ffffffff815a612f: change_bus_speed.isra.0.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline, Transformation ⚠️</summary>

```c
int change_bus_speed(struct controller *ctrl, struct slot *p_slot, enum pci_bus_speed speed);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/pci/hotplug/shpchp_ctrl.c (ffffffff8164ed17)
Location: drivers/pci/hotplug/shpchp_ctrl.c:178
Inline: True
Direct callers:
  - drivers/pci/hotplug/shpchp_ctrl.c:board_added
```
**Symbols:**

```
ffffffff8164e020-ffffffff8164e067: change_bus_speed (STB_LOCAL)
ffffffff8164ecf2-ffffffff8164ed3f: change_bus_speed.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline, Transformation ⚠️</summary>

```c
int change_bus_speed(struct controller *ctrl, struct slot *p_slot, enum pci_bus_speed speed);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/pci/hotplug/shpchp_ctrl.c (ffffffff81bfc768)
Location: drivers/pci/hotplug/shpchp_ctrl.c:178
Inline: True
Direct callers:
  - drivers/pci/hotplug/shpchp_ctrl.c:board_added
```
**Symbols:**

```
ffffffff81671f90-ffffffff81671fd7: change_bus_speed (STB_LOCAL)
ffffffff81bfc743-ffffffff81bfc790: change_bus_speed.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline, Transformation ⚠️</summary>

```c
int change_bus_speed(struct controller *ctrl, struct slot *p_slot, enum pci_bus_speed speed);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/pci/hotplug/shpchp_ctrl.c (ffffffff81bee653)
Location: drivers/pci/hotplug/shpchp_ctrl.c:178
Inline: True
Direct callers:
  - drivers/pci/hotplug/shpchp_ctrl.c:board_added
```
**Symbols:**

```
ffffffff816544a0-ffffffff816544e7: change_bus_speed (STB_LOCAL)
ffffffff81bee62e-ffffffff81bee67b: change_bus_speed.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int change_bus_speed(struct controller *ctrl, struct slot *p_slot, enum pci_bus_speed speed);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pci/hotplug/shpchp_ctrl.c (0)
Location: drivers/pci/hotplug/shpchp_ctrl.c:178
Inline: False
Direct callers:
  - drivers/pci/hotplug/shpchp_ctrl.c:board_added
```
**Symbols:**

```
ffffffff816c6100-ffffffff816c615a: change_bus_speed (STB_LOCAL)
ffffffff81ce94fa-ffffffff81ce955d: change_bus_speed.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int change_bus_speed(struct controller *ctrl, struct slot *p_slot, enum pci_bus_speed speed);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pci/hotplug/shpchp_ctrl.c (0)
Location: drivers/pci/hotplug/shpchp_ctrl.c:178
Inline: False
Direct callers:
  - drivers/pci/hotplug/shpchp_ctrl.c:board_added
  - drivers/pci/hotplug/shpchp_ctrl.c:board_added
```
**Symbols:**

```
ffffffff817ec000-ffffffff817ec065: change_bus_speed (STB_LOCAL)
ffffffff81eb0598-ffffffff81eb05fd: change_bus_speed.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
int change_bus_speed(struct controller *ctrl, struct slot *p_slot, enum pci_bus_speed speed);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pci/hotplug/shpchp_ctrl.c (0)
Location: drivers/pci/hotplug/shpchp_ctrl.c:178
Inline: False
Direct callers:
  - drivers/pci/hotplug/shpchp_ctrl.c:board_added
```
**Symbols:**

```
ffffffff819128b0-ffffffff8191296a: change_bus_speed (STB_LOCAL)
ffffffff8208fa4a-ffffffff8208fa5f: change_bus_speed.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
int change_bus_speed(struct controller *ctrl, struct slot *p_slot, enum pci_bus_speed speed);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pci/hotplug/shpchp_ctrl.c (0)
Location: drivers/pci/hotplug/shpchp_ctrl.c:178
Inline: False
Direct callers:
  - drivers/pci/hotplug/shpchp_ctrl.c:board_added
```
**Symbols:**

```
ffffffff81955f30-ffffffff81955fea: change_bus_speed (STB_LOCAL)
ffffffff8210fdaa-ffffffff8210fdbf: change_bus_speed.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
int change_bus_speed(struct controller *ctrl, struct slot *p_slot, enum pci_bus_speed speed);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pci/hotplug/shpchp_ctrl.c (0)
Location: drivers/pci/hotplug/shpchp_ctrl.c:178
Inline: False
Direct callers:
  - drivers/pci/hotplug/shpchp_ctrl.c:board_added
```
**Symbols:**

```
ffffffff8199f450-ffffffff8199f50a: change_bus_speed (STB_LOCAL)
ffffffff821edad2-ffffffff821edae7: change_bus_speed.cold (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/pci/hotplug/shpchp_ctrl.c (ffff80001070e2a0)
Location: drivers/pci/hotplug/shpchp_ctrl.c:178
Inline: True
Direct callers:
  - drivers/pci/hotplug/shpchp_ctrl.c:board_added
  - drivers/pci/hotplug/shpchp_ctrl.c:board_added
```
**Symbols:**

```
ffff80001070e2a0-ffff80001070e344: change_bus_speed.isra.0 (STB_LOCAL)
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
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
int change_bus_speed(struct controller *ctrl, struct slot *p_slot, enum pci_bus_speed speed);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/hotplug/shpchp_ctrl.c (ffffffe0004da7f6)
Location: drivers/pci/hotplug/shpchp_ctrl.c:178
Inline: True
Direct callers:
  - drivers/pci/hotplug/shpchp_ctrl.c:board_added
  - drivers/pci/hotplug/shpchp_ctrl.c:board_added
```
**Symbols:**

```
ffffffe0004da7f6-ffffffe0004da880: change_bus_speed (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/pci/hotplug/shpchp_ctrl.c (ffffffff81599918)
Location: drivers/pci/hotplug/shpchp_ctrl.c:178
Inline: True
Direct callers:
  - drivers/pci/hotplug/shpchp_ctrl.c:board_added
  - drivers/pci/hotplug/shpchp_ctrl.c:board_added
```
**Symbols:**

```
ffffffff81598c80-ffffffff81598cc7: change_bus_speed.isra.0 (STB_LOCAL)
ffffffff815998f4-ffffffff8159993f: change_bus_speed.isra.0.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/pci/hotplug/shpchp_ctrl.c (ffffffff81588aa8)
Location: drivers/pci/hotplug/shpchp_ctrl.c:178
Inline: True
Direct callers:
  - drivers/pci/hotplug/shpchp_ctrl.c:board_added
  - drivers/pci/hotplug/shpchp_ctrl.c:board_added
```
**Symbols:**

```
ffffffff81587e10-ffffffff81587e57: change_bus_speed.isra.0 (STB_LOCAL)
ffffffff81588a84-ffffffff81588acf: change_bus_speed.isra.0.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/pci/hotplug/shpchp_ctrl.c (ffffffff81599e58)
Location: drivers/pci/hotplug/shpchp_ctrl.c:178
Inline: True
Direct callers:
  - drivers/pci/hotplug/shpchp_ctrl.c:board_added
  - drivers/pci/hotplug/shpchp_ctrl.c:board_added
```
**Symbols:**

```
ffffffff815991c0-ffffffff81599207: change_bus_speed.isra.0 (STB_LOCAL)
ffffffff81599e34-ffffffff81599e7f: change_bus_speed.isra.0.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/pci/hotplug/shpchp_ctrl.c (ffffffff815b4298)
Location: drivers/pci/hotplug/shpchp_ctrl.c:178
Inline: True
Direct callers:
  - drivers/pci/hotplug/shpchp_ctrl.c:board_added
  - drivers/pci/hotplug/shpchp_ctrl.c:board_added
```
**Symbols:**

```
ffffffff815b3600-ffffffff815b3647: change_bus_speed.isra.0 (STB_LOCAL)
ffffffff815b4274-ffffffff815b42bf: change_bus_speed.isra.0.cold (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
