# Function: <code>pciehp_runtime_suspend</code>

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
In <code>4.18</code>: Absent ⚠️
</li>
<li>
In <code>5.0</code>: Absent ⚠️
</li>
<li>
In <code>5.3</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int pciehp_runtime_suspend(struct pcie_device *dev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/hotplug/pciehp_core.c (ffffffff815a1fd0)
Location: drivers/pci/hotplug/pciehp_core.c:313
Inline: False
```
**Symbols:**

```
ffffffff815a1fd0-ffffffff815a1ffd: pciehp_runtime_suspend (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int pciehp_runtime_suspend(struct pcie_device *dev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/hotplug/pciehp_core.c (ffffffff8164a930)
Location: drivers/pci/hotplug/pciehp_core.c:313
Inline: False
```
**Symbols:**

```
ffffffff8164a930-ffffffff8164a975: pciehp_runtime_suspend (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int pciehp_runtime_suspend(struct pcie_device *dev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/hotplug/pciehp_core.c (ffffffff8166f190)
Location: drivers/pci/hotplug/pciehp_core.c:314
Inline: False
```
**Symbols:**

```
ffffffff8166f190-ffffffff8166f1d5: pciehp_runtime_suspend (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int pciehp_runtime_suspend(struct pcie_device *dev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/hotplug/pciehp_core.c (ffffffff816516b0)
Location: drivers/pci/hotplug/pciehp_core.c:314
Inline: False
```
**Symbols:**

```
ffffffff816516b0-ffffffff816516f5: pciehp_runtime_suspend (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int pciehp_runtime_suspend(struct pcie_device *dev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pci/hotplug/pciehp_core.c (0)
Location: drivers/pci/hotplug/pciehp_core.c:314
Inline: False
```
**Symbols:**

```
ffffffff816c33f0-ffffffff816c3450: pciehp_runtime_suspend (STB_LOCAL)
ffffffff81ce893b-ffffffff81ce8958: pciehp_runtime_suspend.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int pciehp_runtime_suspend(struct pcie_device *dev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pci/hotplug/pciehp_core.c (0)
Location: drivers/pci/hotplug/pciehp_core.c:314
Inline: False
```
**Symbols:**

```
ffffffff817e8e30-ffffffff817e8e8d: pciehp_runtime_suspend (STB_LOCAL)
ffffffff81eaf9d6-ffffffff81eaf9f3: pciehp_runtime_suspend.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
int pciehp_runtime_suspend(struct pcie_device *dev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pci/hotplug/pciehp_core.c (0)
Location: drivers/pci/hotplug/pciehp_core.c:314
Inline: False
```
**Symbols:**

```
ffffffff8190e990-ffffffff8190e9ed: pciehp_runtime_suspend (STB_LOCAL)
ffffffff8208f818-ffffffff8208f835: pciehp_runtime_suspend.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
int pciehp_runtime_suspend(struct pcie_device *dev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pci/hotplug/pciehp_core.c (0)
Location: drivers/pci/hotplug/pciehp_core.c:314
Inline: False
```
**Symbols:**

```
ffffffff81952010-ffffffff8195206d: pciehp_runtime_suspend (STB_LOCAL)
ffffffff8210fb78-ffffffff8210fb95: pciehp_runtime_suspend.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
int pciehp_runtime_suspend(struct pcie_device *dev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pci/hotplug/pciehp_core.c (0)
Location: drivers/pci/hotplug/pciehp_core.c:315
Inline: False
```
**Symbols:**

```
ffffffff8199b4a0-ffffffff8199b4fd: pciehp_runtime_suspend (STB_LOCAL)
ffffffff821ed8a0-ffffffff821ed8bd: pciehp_runtime_suspend.cold (STB_LOCAL)
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
int pciehp_runtime_suspend(struct pcie_device *dev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/hotplug/pciehp_core.c (ffff80001070a950)
Location: drivers/pci/hotplug/pciehp_core.c:313
Inline: False
```
**Symbols:**

```
ffff80001070a950-ffff80001070a9a0: pciehp_runtime_suspend (STB_LOCAL)
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
int pciehp_runtime_suspend(struct pcie_device *dev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/hotplug/pciehp_core.c (ffffffe0004d72a8)
Location: drivers/pci/hotplug/pciehp_core.c:313
Inline: False
```
**Symbols:**

```
ffffffe0004d72a8-ffffffe0004d72ec: pciehp_runtime_suspend (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: ✅</summary>

```c
int pciehp_runtime_suspend(struct pcie_device *dev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/hotplug/pciehp_core.c (ffffffff815957e0)
Location: drivers/pci/hotplug/pciehp_core.c:313
Inline: False
```
**Symbols:**

```
ffffffff815957e0-ffffffff8159580d: pciehp_runtime_suspend (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int pciehp_runtime_suspend(struct pcie_device *dev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/hotplug/pciehp_core.c (ffffffff81584970)
Location: drivers/pci/hotplug/pciehp_core.c:313
Inline: False
```
**Symbols:**

```
ffffffff81584970-ffffffff8158499d: pciehp_runtime_suspend (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int pciehp_runtime_suspend(struct pcie_device *dev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/hotplug/pciehp_core.c (ffffffff81595d20)
Location: drivers/pci/hotplug/pciehp_core.c:313
Inline: False
```
**Symbols:**

```
ffffffff81595d20-ffffffff81595d4d: pciehp_runtime_suspend (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int pciehp_runtime_suspend(struct pcie_device *dev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/hotplug/pciehp_core.c (ffffffff815b01a0)
Location: drivers/pci/hotplug/pciehp_core.c:313
Inline: False
```
**Symbols:**

```
ffffffff815b01a0-ffffffff815b01cd: pciehp_runtime_suspend (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
