# Function: <code>hpc_power_on_slot</code>

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
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
int hpc_power_on_slot(struct slot *slot);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/hotplug/shpchp_hpc.c (ffffffff8153eac0)
Location: drivers/pci/hotplug/shpchp_hpc.c:600
Inline: True
```
**Symbols:**

```
ffffffff8153eac0-ffffffff8153eb1c: hpc_power_on_slot (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
int hpc_power_on_slot(struct slot *slot);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/hotplug/shpchp_hpc.c (ffffffff81555e90)
Location: drivers/pci/hotplug/shpchp_hpc.c:600
Inline: True
```
**Symbols:**

```
ffffffff81555e90-ffffffff81555eec: hpc_power_on_slot (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline, Transformation ⚠️</summary>

```c
int hpc_power_on_slot(struct slot *slot);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/pci/hotplug/shpchp_hpc.c (ffffffff815862e7)
Location: drivers/pci/hotplug/shpchp_hpc.c:600
Inline: True
```
**Symbols:**

```
ffffffff81585d80-ffffffff81585db1: hpc_power_on_slot (STB_LOCAL)
ffffffff815862d9-ffffffff81586306: hpc_power_on_slot.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline, Transformation ⚠️</summary>

```c
int hpc_power_on_slot(struct slot *slot);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/pci/hotplug/shpchp_hpc.c (ffffffff815a7cc7)
Location: drivers/pci/hotplug/shpchp_hpc.c:600
Inline: True
```
**Symbols:**

```
ffffffff815a7760-ffffffff815a7791: hpc_power_on_slot (STB_LOCAL)
ffffffff815a7cb9-ffffffff815a7ce6: hpc_power_on_slot.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline, Transformation ⚠️</summary>

```c
int hpc_power_on_slot(struct slot *slot);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/pci/hotplug/shpchp_hpc.c (ffffffff81650a80)
Location: drivers/pci/hotplug/shpchp_hpc.c:600
Inline: True
```
**Symbols:**

```
ffffffff81650440-ffffffff81650470: hpc_power_on_slot (STB_LOCAL)
ffffffff81650a72-ffffffff81650a9f: hpc_power_on_slot.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline, Transformation ⚠️</summary>

```c
int hpc_power_on_slot(struct slot *slot);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/pci/hotplug/shpchp_hpc.c (ffffffff81bfd3aa)
Location: drivers/pci/hotplug/shpchp_hpc.c:600
Inline: True
```
**Symbols:**

```
ffffffff816738e0-ffffffff81673910: hpc_power_on_slot (STB_LOCAL)
ffffffff81bfd39c-ffffffff81bfd3c9: hpc_power_on_slot.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline, Transformation ⚠️</summary>

```c
int hpc_power_on_slot(struct slot *slot);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/pci/hotplug/shpchp_hpc.c (ffffffff81bef199)
Location: drivers/pci/hotplug/shpchp_hpc.c:595
Inline: True
```
**Symbols:**

```
ffffffff81655e10-ffffffff81655e40: hpc_power_on_slot (STB_LOCAL)
ffffffff81bef18b-ffffffff81bef1b8: hpc_power_on_slot.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline, Transformation ⚠️</summary>

```c
int hpc_power_on_slot(struct slot *slot);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/pci/hotplug/shpchp_hpc.c (ffffffff81cea33d)
Location: drivers/pci/hotplug/shpchp_hpc.c:595
Inline: True
```
**Symbols:**

```
ffffffff816c7dd0-ffffffff816c7e00: hpc_power_on_slot (STB_LOCAL)
ffffffff81cea32f-ffffffff81cea35c: hpc_power_on_slot.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline, Transformation ⚠️</summary>

```c
int hpc_power_on_slot(struct slot *slot);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/pci/hotplug/shpchp_hpc.c (ffffffff81eb1402)
Location: drivers/pci/hotplug/shpchp_hpc.c:595
Inline: True
```
**Symbols:**

```
ffffffff817edec0-ffffffff817edefa: hpc_power_on_slot (STB_LOCAL)
ffffffff81eb13f4-ffffffff81eb1421: hpc_power_on_slot.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
int hpc_power_on_slot(struct slot *slot);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/hotplug/shpchp_hpc.c (ffffffff81915480)
Location: drivers/pci/hotplug/shpchp_hpc.c:578
Inline: True
```
**Symbols:**

```
ffffffff81915480-ffffffff819154ed: hpc_power_on_slot (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
int hpc_power_on_slot(struct slot *slot);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/hotplug/shpchp_hpc.c (ffffffff81958aa0)
Location: drivers/pci/hotplug/shpchp_hpc.c:578
Inline: True
```
**Symbols:**

```
ffffffff81958aa0-ffffffff81958b0d: hpc_power_on_slot (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
int hpc_power_on_slot(struct slot *slot);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/hotplug/shpchp_hpc.c (ffffffff819a2010)
Location: drivers/pci/hotplug/shpchp_hpc.c:578
Inline: True
```
**Symbols:**

```
ffffffff819a2010-ffffffff819a207d: hpc_power_on_slot (STB_LOCAL)
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
int hpc_power_on_slot(struct slot *slot);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/hotplug/shpchp_hpc.c (ffff800010710028)
Location: drivers/pci/hotplug/shpchp_hpc.c:600
Inline: True
```
**Symbols:**

```
ffff800010710028-ffff800010710090: hpc_power_on_slot (STB_LOCAL)
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
int hpc_power_on_slot(struct slot *slot);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/hotplug/shpchp_hpc.c (ffffffe0004dc922)
Location: drivers/pci/hotplug/shpchp_hpc.c:600
Inline: True
```
**Symbols:**

```
ffffffe0004dc922-ffffffe0004dc97e: hpc_power_on_slot (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Selective Inline, Transformation ⚠️</summary>

```c
int hpc_power_on_slot(struct slot *slot);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/pci/hotplug/shpchp_hpc.c (ffffffff8159b4d7)
Location: drivers/pci/hotplug/shpchp_hpc.c:600
Inline: True
```
**Symbols:**

```
ffffffff8159af70-ffffffff8159afa1: hpc_power_on_slot (STB_LOCAL)
ffffffff8159b4c9-ffffffff8159b4f6: hpc_power_on_slot.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline, Transformation ⚠️</summary>

```c
int hpc_power_on_slot(struct slot *slot);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/pci/hotplug/shpchp_hpc.c (ffffffff8158a667)
Location: drivers/pci/hotplug/shpchp_hpc.c:600
Inline: True
```
**Symbols:**

```
ffffffff8158a100-ffffffff8158a131: hpc_power_on_slot (STB_LOCAL)
ffffffff8158a659-ffffffff8158a686: hpc_power_on_slot.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline, Transformation ⚠️</summary>

```c
int hpc_power_on_slot(struct slot *slot);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/pci/hotplug/shpchp_hpc.c (ffffffff8159ba17)
Location: drivers/pci/hotplug/shpchp_hpc.c:600
Inline: True
```
**Symbols:**

```
ffffffff8159b4b0-ffffffff8159b4e1: hpc_power_on_slot (STB_LOCAL)
ffffffff8159ba09-ffffffff8159ba36: hpc_power_on_slot.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline, Transformation ⚠️</summary>

```c
int hpc_power_on_slot(struct slot *slot);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/pci/hotplug/shpchp_hpc.c (ffffffff815b5e47)
Location: drivers/pci/hotplug/shpchp_hpc.c:600
Inline: True
```
**Symbols:**

```
ffffffff815b58e0-ffffffff815b5911: hpc_power_on_slot (STB_LOCAL)
ffffffff815b5e39-ffffffff815b5e66: hpc_power_on_slot.cold (STB_LOCAL)
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
