# Function: <code>hpc_set_bus_speed_mode</code>

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
int hpc_set_bus_speed_mode(struct slot *slot, enum pci_bus_speed value);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/hotplug/shpchp_hpc.c (ffffffff8153eb20)
Location: drivers/pci/hotplug/shpchp_hpc.c:706
Inline: False
```
**Symbols:**

```
ffffffff8153eb20-ffffffff8153ec1b: hpc_set_bus_speed_mode (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int hpc_set_bus_speed_mode(struct slot *slot, enum pci_bus_speed value);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/hotplug/shpchp_hpc.c (ffffffff81555ef0)
Location: drivers/pci/hotplug/shpchp_hpc.c:706
Inline: False
```
**Symbols:**

```
ffffffff81555ef0-ffffffff81556044: hpc_set_bus_speed_mode (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
int hpc_set_bus_speed_mode(struct slot *slot, enum pci_bus_speed value);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pci/hotplug/shpchp_hpc.c (0)
Location: drivers/pci/hotplug/shpchp_hpc.c:706
Inline: False
```
**Symbols:**

```
ffffffff81585dc0-ffffffff81585ef1: hpc_set_bus_speed_mode (STB_LOCAL)
ffffffff81586306-ffffffff81586329: hpc_set_bus_speed_mode.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
int hpc_set_bus_speed_mode(struct slot *slot, enum pci_bus_speed value);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pci/hotplug/shpchp_hpc.c (0)
Location: drivers/pci/hotplug/shpchp_hpc.c:706
Inline: False
```
**Symbols:**

```
ffffffff815a77a0-ffffffff815a78d1: hpc_set_bus_speed_mode (STB_LOCAL)
ffffffff815a7ce6-ffffffff815a7d09: hpc_set_bus_speed_mode.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
int hpc_set_bus_speed_mode(struct slot *slot, enum pci_bus_speed value);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pci/hotplug/shpchp_hpc.c (0)
Location: drivers/pci/hotplug/shpchp_hpc.c:706
Inline: False
```
**Symbols:**

```
ffffffff81650470-ffffffff816505a1: hpc_set_bus_speed_mode (STB_LOCAL)
ffffffff81650a9f-ffffffff81650ac2: hpc_set_bus_speed_mode.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
int hpc_set_bus_speed_mode(struct slot *slot, enum pci_bus_speed value);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pci/hotplug/shpchp_hpc.c (0)
Location: drivers/pci/hotplug/shpchp_hpc.c:706
Inline: False
```
**Symbols:**

```
ffffffff81673910-ffffffff81673a41: hpc_set_bus_speed_mode (STB_LOCAL)
ffffffff81bfd3c9-ffffffff81bfd3ec: hpc_set_bus_speed_mode.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
int hpc_set_bus_speed_mode(struct slot *slot, enum pci_bus_speed value);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pci/hotplug/shpchp_hpc.c (0)
Location: drivers/pci/hotplug/shpchp_hpc.c:701
Inline: False
```
**Symbols:**

```
ffffffff81655e40-ffffffff81655f74: hpc_set_bus_speed_mode (STB_LOCAL)
ffffffff81bef1b8-ffffffff81bef1db: hpc_set_bus_speed_mode.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int hpc_set_bus_speed_mode(struct slot *slot, enum pci_bus_speed value);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pci/hotplug/shpchp_hpc.c (0)
Location: drivers/pci/hotplug/shpchp_hpc.c:701
Inline: False
```
**Symbols:**

```
ffffffff816c7e00-ffffffff816c7f34: hpc_set_bus_speed_mode (STB_LOCAL)
ffffffff81cea35c-ffffffff81cea37f: hpc_set_bus_speed_mode.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int hpc_set_bus_speed_mode(struct slot *slot, enum pci_bus_speed value);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pci/hotplug/shpchp_hpc.c (0)
Location: drivers/pci/hotplug/shpchp_hpc.c:701
Inline: False
```
**Symbols:**

```
ffffffff817edf00-ffffffff817ee00f: hpc_set_bus_speed_mode (STB_LOCAL)
ffffffff81eb1421-ffffffff81eb1445: hpc_set_bus_speed_mode.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int hpc_set_bus_speed_mode(struct slot *slot, enum pci_bus_speed value);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/hotplug/shpchp_hpc.c (ffffffff81915500)
Location: drivers/pci/hotplug/shpchp_hpc.c:684
Inline: False
```
**Symbols:**

```
ffffffff81915500-ffffffff8191565e: hpc_set_bus_speed_mode (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int hpc_set_bus_speed_mode(struct slot *slot, enum pci_bus_speed value);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/hotplug/shpchp_hpc.c (ffffffff81958b20)
Location: drivers/pci/hotplug/shpchp_hpc.c:684
Inline: False
```
**Symbols:**

```
ffffffff81958b20-ffffffff81958c6a: hpc_set_bus_speed_mode (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int hpc_set_bus_speed_mode(struct slot *slot, enum pci_bus_speed value);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/hotplug/shpchp_hpc.c (ffffffff819a2090)
Location: drivers/pci/hotplug/shpchp_hpc.c:684
Inline: False
```
**Symbols:**

```
ffffffff819a2090-ffffffff819a21da: hpc_set_bus_speed_mode (STB_LOCAL)
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
int hpc_set_bus_speed_mode(struct slot *slot, enum pci_bus_speed value);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/hotplug/shpchp_hpc.c (ffff800010710090)
Location: drivers/pci/hotplug/shpchp_hpc.c:706
Inline: False
```
**Symbols:**

```
ffff800010710090-ffff800010710220: hpc_set_bus_speed_mode (STB_LOCAL)
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
int hpc_set_bus_speed_mode(struct slot *slot, enum pci_bus_speed value);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/hotplug/shpchp_hpc.c (ffffffe0004dc97e)
Location: drivers/pci/hotplug/shpchp_hpc.c:706
Inline: False
```
**Symbols:**

```
ffffffe0004dc97e-ffffffe0004dca84: hpc_set_bus_speed_mode (STB_LOCAL)
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
int hpc_set_bus_speed_mode(struct slot *slot, enum pci_bus_speed value);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pci/hotplug/shpchp_hpc.c (0)
Location: drivers/pci/hotplug/shpchp_hpc.c:706
Inline: False
```
**Symbols:**

```
ffffffff8159afb0-ffffffff8159b0e1: hpc_set_bus_speed_mode (STB_LOCAL)
ffffffff8159b4f6-ffffffff8159b519: hpc_set_bus_speed_mode.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Transformation ⚠️</summary>

```c
int hpc_set_bus_speed_mode(struct slot *slot, enum pci_bus_speed value);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pci/hotplug/shpchp_hpc.c (0)
Location: drivers/pci/hotplug/shpchp_hpc.c:706
Inline: False
```
**Symbols:**

```
ffffffff8158a140-ffffffff8158a271: hpc_set_bus_speed_mode (STB_LOCAL)
ffffffff8158a686-ffffffff8158a6a9: hpc_set_bus_speed_mode.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Transformation ⚠️</summary>

```c
int hpc_set_bus_speed_mode(struct slot *slot, enum pci_bus_speed value);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pci/hotplug/shpchp_hpc.c (0)
Location: drivers/pci/hotplug/shpchp_hpc.c:706
Inline: False
```
**Symbols:**

```
ffffffff8159b4f0-ffffffff8159b621: hpc_set_bus_speed_mode (STB_LOCAL)
ffffffff8159ba36-ffffffff8159ba59: hpc_set_bus_speed_mode.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
int hpc_set_bus_speed_mode(struct slot *slot, enum pci_bus_speed value);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pci/hotplug/shpchp_hpc.c (0)
Location: drivers/pci/hotplug/shpchp_hpc.c:706
Inline: False
```
**Symbols:**

```
ffffffff815b5920-ffffffff815b5a51: hpc_set_bus_speed_mode (STB_LOCAL)
ffffffff815b5e66-ffffffff815b5e89: hpc_set_bus_speed_mode.cold (STB_LOCAL)
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
