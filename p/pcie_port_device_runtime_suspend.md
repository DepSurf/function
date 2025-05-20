# Function: <code>pcie_port_device_runtime_suspend</code>

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
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int pcie_port_device_runtime_suspend(struct device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pcie/portdrv_core.c (ffffffff81547dd0)
Location: drivers/pci/pcie/portdrv_core.c:403
Inline: False
Direct callers:
  - drivers/pci/pcie/portdrv_pci.c:pcie_port_runtime_suspend
```
**Symbols:**

```
ffffffff81547dd0-ffffffff81547e1a: pcie_port_device_runtime_suspend (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int pcie_port_device_runtime_suspend(struct device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pcie/portdrv_core.c (ffffffff81577e60)
Location: drivers/pci/pcie/portdrv_core.c:411
Inline: False
Direct callers:
  - drivers/pci/pcie/portdrv_pci.c:pcie_port_runtime_suspend
```
**Symbols:**

```
ffffffff81577e60-ffffffff81577eaa: pcie_port_device_runtime_suspend (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int pcie_port_device_runtime_suspend(struct device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pcie/portdrv_core.c (ffffffff815995f0)
Location: drivers/pci/pcie/portdrv_core.c:416
Inline: False
Direct callers:
  - drivers/pci/pcie/portdrv_pci.c:pcie_port_runtime_suspend
```
**Symbols:**

```
ffffffff815995f0-ffffffff8159963a: pcie_port_device_runtime_suspend (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int pcie_port_device_runtime_suspend(struct device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pcie/portdrv_core.c (ffffffff81638e30)
Location: drivers/pci/pcie/portdrv_core.c:416
Inline: False
Direct callers:
  - drivers/pci/pcie/portdrv_pci.c:pcie_port_runtime_suspend
```
**Symbols:**

```
ffffffff81638e30-ffffffff81638e7a: pcie_port_device_runtime_suspend (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int pcie_port_device_runtime_suspend(struct device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pcie/portdrv_core.c (ffffffff8165f940)
Location: drivers/pci/pcie/portdrv_core.c:413
Inline: False
Direct callers:
  - drivers/pci/pcie/portdrv_pci.c:pcie_port_runtime_suspend
```
**Symbols:**

```
ffffffff8165f940-ffffffff8165f98a: pcie_port_device_runtime_suspend (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int pcie_port_device_runtime_suspend(struct device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pcie/portdrv_core.c (ffffffff81641e10)
Location: drivers/pci/pcie/portdrv_core.c:413
Inline: False
Direct callers:
  - drivers/pci/pcie/portdrv_pci.c:pcie_port_runtime_suspend
```
**Symbols:**

```
ffffffff81641e10-ffffffff81641e5a: pcie_port_device_runtime_suspend (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int pcie_port_device_runtime_suspend(struct device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pcie/portdrv_core.c (ffffffff816b2ae0)
Location: drivers/pci/pcie/portdrv_core.c:418
Inline: False
Direct callers:
  - drivers/pci/pcie/portdrv_pci.c:pcie_port_runtime_suspend
```
**Symbols:**

```
ffffffff816b2ae0-ffffffff816b2b2a: pcie_port_device_runtime_suspend (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int pcie_port_device_runtime_suspend(struct device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pcie/portdrv_core.c (ffffffff817d6470)
Location: drivers/pci/pcie/portdrv_core.c:418
Inline: False
Direct callers:
  - drivers/pci/pcie/portdrv_pci.c:pcie_port_runtime_suspend
```
**Symbols:**

```
ffffffff817d6470-ffffffff817d64c4: pcie_port_device_runtime_suspend (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/pci/pcie/portdrv.c (ffffffff818f7062)
Location: drivers/pci/pcie/portdrv.c:426
Inline: True
Inline callers:
  - drivers/pci/pcie/portdrv.c:pcie_port_runtime_suspend
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/pci/pcie/portdrv.c (ffffffff8193a4c2)
Location: drivers/pci/pcie/portdrv.c:426
Inline: True
Inline callers:
  - drivers/pci/pcie/portdrv.c:pcie_port_runtime_suspend
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/pci/pcie/portdrv.c (ffffffff81983322)
Location: drivers/pci/pcie/portdrv.c:427
Inline: True
Inline callers:
  - drivers/pci/pcie/portdrv.c:pcie_port_runtime_suspend
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
int pcie_port_device_runtime_suspend(struct device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pcie/portdrv_core.c (ffff800010700ca0)
Location: drivers/pci/pcie/portdrv_core.c:416
Inline: False
Direct callers:
  - drivers/pci/pcie/portdrv_pci.c:pcie_port_runtime_suspend
```
**Symbols:**

```
ffff800010700ca0-ffff800010700d04: pcie_port_device_runtime_suspend (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int pcie_port_device_runtime_suspend(struct device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pcie/portdrv_core.c (c0898a38)
Location: drivers/pci/pcie/portdrv_core.c:416
Inline: False
Direct callers:
  - drivers/pci/pcie/portdrv_pci.c:pcie_port_runtime_suspend
```
**Symbols:**

```
c0898a38-c0898aa0: pcie_port_device_runtime_suspend (STB_GLOBAL)
```
</details>
</li>
<li>
In <code>ppc64el</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int pcie_port_device_runtime_suspend(struct device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pcie/portdrv_core.c (ffffffe0004cfb0c)
Location: drivers/pci/pcie/portdrv_core.c:416
Inline: False
Direct callers:
  - drivers/pci/pcie/portdrv_pci.c:pcie_port_runtime_suspend
```
**Symbols:**

```
ffffffe0004cfb0c-ffffffe0004cfb4a: pcie_port_device_runtime_suspend (STB_GLOBAL)
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
int pcie_port_device_runtime_suspend(struct device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pcie/portdrv_core.c (ffffffff8158d480)
Location: drivers/pci/pcie/portdrv_core.c:416
Inline: False
Direct callers:
  - drivers/pci/pcie/portdrv_pci.c:pcie_port_runtime_suspend
```
**Symbols:**

```
ffffffff8158d480-ffffffff8158d4ca: pcie_port_device_runtime_suspend (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int pcie_port_device_runtime_suspend(struct device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pcie/portdrv_core.c (ffffffff8157bfc0)
Location: drivers/pci/pcie/portdrv_core.c:416
Inline: False
Direct callers:
  - drivers/pci/pcie/portdrv_pci.c:pcie_port_runtime_suspend
```
**Symbols:**

```
ffffffff8157bfc0-ffffffff8157c00a: pcie_port_device_runtime_suspend (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int pcie_port_device_runtime_suspend(struct device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pcie/portdrv_core.c (ffffffff8158d340)
Location: drivers/pci/pcie/portdrv_core.c:416
Inline: False
Direct callers:
  - drivers/pci/pcie/portdrv_pci.c:pcie_port_runtime_suspend
```
**Symbols:**

```
ffffffff8158d340-ffffffff8158d38a: pcie_port_device_runtime_suspend (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int pcie_port_device_runtime_suspend(struct device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pcie/portdrv_core.c (ffffffff815a77f0)
Location: drivers/pci/pcie/portdrv_core.c:416
Inline: False
Direct callers:
  - drivers/pci/pcie/portdrv_pci.c:pcie_port_runtime_suspend
```
**Symbols:**

```
ffffffff815a77f0-ffffffff815a783a: pcie_port_device_runtime_suspend (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
</ul>
<b>Arch</b>
<ul>
<li>
No changes between <code>amd64</code> and <code>arm64</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>armhf</code> ✅
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
