# Function: <code>pciehp_resume</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int pciehp_resume(struct pcie_device *dev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/hotplug/pciehp_core.c (ffffffff8144ee60)
Location: drivers/pci/hotplug/pciehp_core.c:289
Inline: False
```
**Symbols:**

```
ffffffff8144ee60-ffffffff8144eee6: pciehp_resume (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int pciehp_resume(struct pcie_device *dev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/hotplug/pciehp_core.c (ffffffff8149b600)
Location: drivers/pci/hotplug/pciehp_core.c:289
Inline: False
```
**Symbols:**

```
ffffffff8149b600-ffffffff8149b686: pciehp_resume (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int pciehp_resume(struct pcie_device *dev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/hotplug/pciehp_core.c (ffffffff814bd1e0)
Location: drivers/pci/hotplug/pciehp_core.c:291
Inline: False
```
**Symbols:**

```
ffffffff814bd1e0-ffffffff814bd266: pciehp_resume (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int pciehp_resume(struct pcie_device *dev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/hotplug/pciehp_core.c (ffffffff814c79b0)
Location: drivers/pci/hotplug/pciehp_core.c:291
Inline: False
```
**Symbols:**

```
ffffffff814c79b0-ffffffff814c7a36: pciehp_resume (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int pciehp_resume(struct pcie_device *dev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/hotplug/pciehp_core.c (ffffffff81507f50)
Location: drivers/pci/hotplug/pciehp_core.c:291
Inline: False
```
**Symbols:**

```
ffffffff81507f50-ffffffff81507fd6: pciehp_resume (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int pciehp_resume(struct pcie_device *dev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/hotplug/pciehp_core.c (ffffffff81538e70)
Location: drivers/pci/hotplug/pciehp_core.c:284
Inline: False
```
**Symbols:**

```
ffffffff81538e70-ffffffff81538ef6: pciehp_resume (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int pciehp_resume(struct pcie_device *dev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/hotplug/pciehp_core.c (ffffffff815506d0)
Location: drivers/pci/hotplug/pciehp_core.c:280
Inline: False
Direct callers:
  - drivers/pci/hotplug/pciehp_core.c:pciehp_runtime_resume
  - drivers/pci/hotplug/pciehp_core.c:pciehp_runtime_resume
```
**Symbols:**

```
ffffffff815506d0-ffffffff8155070d: pciehp_resume (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int pciehp_resume(struct pcie_device *dev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/hotplug/pciehp_core.c (ffffffff81580460)
Location: drivers/pci/hotplug/pciehp_core.c:278
Inline: False
Direct callers:
  - drivers/pci/hotplug/pciehp_core.c:pciehp_runtime_resume
  - drivers/pci/hotplug/pciehp_core.c:pciehp_runtime_resume
```
**Symbols:**

```
ffffffff81580460-ffffffff815804a0: pciehp_resume (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int pciehp_resume(struct pcie_device *dev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/hotplug/pciehp_core.c (ffffffff815a1f20)
Location: drivers/pci/hotplug/pciehp_core.c:301
Inline: False
Direct callers:
  - drivers/pci/hotplug/pciehp_core.c:pciehp_runtime_resume
  - drivers/pci/hotplug/pciehp_core.c:pciehp_runtime_resume
```
**Symbols:**

```
ffffffff815a1f20-ffffffff815a1f60: pciehp_resume (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
int pciehp_resume(struct pcie_device *dev);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/hotplug/pciehp_core.c (ffffffff8164aa13)
Location: drivers/pci/hotplug/pciehp_core.c:301
Inline: True
Inline callers:
  - drivers/pci/hotplug/pciehp_core.c:pciehp_runtime_resume
```
**Symbols:**

```
ffffffff8164a980-ffffffff8164a9d6: pciehp_resume (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
int pciehp_resume(struct pcie_device *dev);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/hotplug/pciehp_core.c (ffffffff8166f273)
Location: drivers/pci/hotplug/pciehp_core.c:302
Inline: True
Inline callers:
  - drivers/pci/hotplug/pciehp_core.c:pciehp_runtime_resume
```
**Symbols:**

```
ffffffff8166f1e0-ffffffff8166f236: pciehp_resume (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
int pciehp_resume(struct pcie_device *dev);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/hotplug/pciehp_core.c (ffffffff81651793)
Location: drivers/pci/hotplug/pciehp_core.c:302
Inline: True
Inline callers:
  - drivers/pci/hotplug/pciehp_core.c:pciehp_runtime_resume
```
**Symbols:**

```
ffffffff81651700-ffffffff81651756: pciehp_resume (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline, Transformation ⚠️</summary>

```c
int pciehp_resume(struct pcie_device *dev);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/pci/hotplug/pciehp_core.c (ffffffff816c34e9)
Location: drivers/pci/hotplug/pciehp_core.c:302
Inline: True
Inline callers:
  - drivers/pci/hotplug/pciehp_core.c:pciehp_runtime_resume
```
**Symbols:**

```
ffffffff816c3450-ffffffff816c34ac: pciehp_resume (STB_LOCAL)
ffffffff81ce8958-ffffffff81ce8974: pciehp_resume.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline, Transformation ⚠️</summary>

```c
int pciehp_resume(struct pcie_device *dev);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/pci/hotplug/pciehp_core.c (ffffffff817e8f39)
Location: drivers/pci/hotplug/pciehp_core.c:302
Inline: True
Inline callers:
  - drivers/pci/hotplug/pciehp_core.c:pciehp_runtime_resume
```
**Symbols:**

```
ffffffff817e8e90-ffffffff817e8ef2: pciehp_resume (STB_LOCAL)
ffffffff81eaf9f3-ffffffff81eafa0f: pciehp_resume.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline, Transformation ⚠️</summary>

```c
int pciehp_resume(struct pcie_device *dev);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/pci/hotplug/pciehp_core.c (ffffffff8190eab9)
Location: drivers/pci/hotplug/pciehp_core.c:302
Inline: True
Inline callers:
  - drivers/pci/hotplug/pciehp_core.c:pciehp_runtime_resume
```
**Symbols:**

```
ffffffff8190ea00-ffffffff8190ea62: pciehp_resume (STB_LOCAL)
ffffffff8208f835-ffffffff8208f851: pciehp_resume.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline, Transformation ⚠️</summary>

```c
int pciehp_resume(struct pcie_device *dev);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/pci/hotplug/pciehp_core.c (ffffffff81952139)
Location: drivers/pci/hotplug/pciehp_core.c:302
Inline: True
Inline callers:
  - drivers/pci/hotplug/pciehp_core.c:pciehp_runtime_resume
```
**Symbols:**

```
ffffffff81952080-ffffffff819520e2: pciehp_resume (STB_LOCAL)
ffffffff8210fb95-ffffffff8210fbb1: pciehp_resume.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline, Transformation ⚠️</summary>

```c
int pciehp_resume(struct pcie_device *dev);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/pci/hotplug/pciehp_core.c (ffffffff8199b5c9)
Location: drivers/pci/hotplug/pciehp_core.c:303
Inline: True
Inline callers:
  - drivers/pci/hotplug/pciehp_core.c:pciehp_runtime_resume
```
**Symbols:**

```
ffffffff8199b510-ffffffff8199b572: pciehp_resume (STB_LOCAL)
ffffffff821ed8bd-ffffffff821ed8d9: pciehp_resume.cold (STB_LOCAL)
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
int pciehp_resume(struct pcie_device *dev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/hotplug/pciehp_core.c (ffff80001070a860)
Location: drivers/pci/hotplug/pciehp_core.c:301
Inline: False
Direct callers:
  - drivers/pci/hotplug/pciehp_core.c:pciehp_runtime_resume
  - drivers/pci/hotplug/pciehp_core.c:pciehp_runtime_resume
```
**Symbols:**

```
ffff80001070a860-ffff80001070a8c4: pciehp_resume (STB_LOCAL)
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
<summary>In <code>riscv64</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/pci/hotplug/pciehp_core.c (ffffffe0004d7252)
Location: drivers/pci/hotplug/pciehp_core.c:301
Inline: True
Inline callers:
  - drivers/pci/hotplug/pciehp_core.c:pciehp_runtime_resume
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
int pciehp_resume(struct pcie_device *dev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/hotplug/pciehp_core.c (ffffffff81595730)
Location: drivers/pci/hotplug/pciehp_core.c:301
Inline: False
Direct callers:
  - drivers/pci/hotplug/pciehp_core.c:pciehp_runtime_resume
  - drivers/pci/hotplug/pciehp_core.c:pciehp_runtime_resume
```
**Symbols:**

```
ffffffff81595730-ffffffff81595770: pciehp_resume (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int pciehp_resume(struct pcie_device *dev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/hotplug/pciehp_core.c (ffffffff815848c0)
Location: drivers/pci/hotplug/pciehp_core.c:301
Inline: False
Direct callers:
  - drivers/pci/hotplug/pciehp_core.c:pciehp_runtime_resume
  - drivers/pci/hotplug/pciehp_core.c:pciehp_runtime_resume
```
**Symbols:**

```
ffffffff815848c0-ffffffff81584900: pciehp_resume (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int pciehp_resume(struct pcie_device *dev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/hotplug/pciehp_core.c (ffffffff81595c70)
Location: drivers/pci/hotplug/pciehp_core.c:301
Inline: False
Direct callers:
  - drivers/pci/hotplug/pciehp_core.c:pciehp_runtime_resume
  - drivers/pci/hotplug/pciehp_core.c:pciehp_runtime_resume
```
**Symbols:**

```
ffffffff81595c70-ffffffff81595cb0: pciehp_resume (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int pciehp_resume(struct pcie_device *dev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/hotplug/pciehp_core.c (ffffffff815b00f0)
Location: drivers/pci/hotplug/pciehp_core.c:301
Inline: False
Direct callers:
  - drivers/pci/hotplug/pciehp_core.c:pciehp_runtime_resume
  - drivers/pci/hotplug/pciehp_core.c:pciehp_runtime_resume
```
**Symbols:**

```
ffffffff815b00f0-ffffffff815b0130: pciehp_resume (STB_LOCAL)
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
