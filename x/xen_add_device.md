# Function: <code>xen_add_device</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/xen/pci.c (ffffffff814d194d)
Location: drivers/xen/pci.c:36
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/xen/pci.c (ffffffff8152263d)
Location: drivers/xen/pci.c:36
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/xen/pci.c (ffffffff8154eb1d)
Location: drivers/xen/pci.c:36
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/xen/pci.c (ffffffff81563092)
Location: drivers/xen/pci.c:36
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/xen/pci.c (ffffffff815c739a)
Location: drivers/xen/pci.c:36
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/xen/pci.c (ffffffff815ffc03)
Location: drivers/xen/pci.c:36
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/xen/pci.c (ffffffff8161acd3)
Location: drivers/xen/pci.c:36
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/xen/pci.c (ffffffff8164ea30)
Location: drivers/xen/pci.c:24
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
int xen_add_device(struct device *dev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/xen/pci.c (0)
Location: drivers/xen/pci.c:26
Inline: False
```
**Symbols:**

```
ffffffff81670e70-ffffffff81671241: xen_add_device (STB_LOCAL)
ffffffff8167132d-ffffffff81671344: xen_add_device.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int xen_add_device(struct device *dev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/xen/pci.c (ffffffff81721550)
Location: drivers/xen/pci.c:26
Inline: False
```
**Symbols:**

```
ffffffff81721550-ffffffff817218a2: xen_add_device (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int xen_add_device(struct device *dev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/xen/pci.c (ffffffff8173e220)
Location: drivers/xen/pci.c:26
Inline: False
```
**Symbols:**

```
ffffffff8173e220-ffffffff8173e578: xen_add_device (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
int xen_add_device(struct device *dev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/xen/pci.c (0)
Location: drivers/xen/pci.c:26
Inline: False
```
**Symbols:**

```
ffffffff81721cc0-ffffffff81722094: xen_add_device (STB_LOCAL)
ffffffff81bf76cf-ffffffff81bf76e4: xen_add_device.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int xen_add_device(struct device *dev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/xen/pci.c (0)
Location: drivers/xen/pci.c:26
Inline: False
```
**Symbols:**

```
ffffffff817a0ae0-ffffffff817a0ed2: xen_add_device (STB_LOCAL)
ffffffff81cf65ce-ffffffff81cf660d: xen_add_device.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int xen_add_device(struct device *dev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/xen/pci.c (0)
Location: drivers/xen/pci.c:27
Inline: False
Direct callers:
  - drivers/xen/pci.c:xen_pci_notifier
```
**Symbols:**

```
ffffffff818da900-ffffffff818dad2a: xen_add_device (STB_LOCAL)
ffffffff81ebe703-ffffffff81ebe742: xen_add_device.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
int xen_add_device(struct device *dev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/xen/pci.c (0)
Location: drivers/xen/pci.c:27
Inline: False
Direct callers:
  - drivers/xen/pci.c:xen_pci_notifier
```
**Symbols:**

```
ffffffff81a2d8c0-ffffffff81a2dcfa: xen_add_device (STB_LOCAL)
ffffffff82094921-ffffffff8209494b: xen_add_device.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
int xen_add_device(struct device *dev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/xen/pci.c (0)
Location: drivers/xen/pci.c:27
Inline: False
Direct callers:
  - drivers/xen/pci.c:xen_pci_notifier
```
**Symbols:**

```
ffffffff81a77060-ffffffff81a7749a: xen_add_device (STB_LOCAL)
ffffffff82115745-ffffffff8211576f: xen_add_device.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
int xen_add_device(struct device *dev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/xen/pci.c (0)
Location: drivers/xen/pci.c:27
Inline: False
Direct callers:
  - drivers/xen/pci.c:xen_pci_notifier
```
**Symbols:**

```
ffffffff81ac9270-ffffffff81ac96aa: xen_add_device (STB_LOCAL)
ffffffff821f33cb-ffffffff821f33f5: xen_add_device.cold (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/xen/pci.c (ffff80001083c55c)
Location: drivers/xen/pci.c:26
Inline: True
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
In <code>riscv64</code>: Absent ⚠️
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Transformation ⚠️</summary>

```c
int xen_add_device(struct device *dev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/xen/pci.c (0)
Location: drivers/xen/pci.c:26
Inline: False
```
**Symbols:**

```
ffffffff81636f30-ffffffff81637301: xen_add_device (STB_LOCAL)
ffffffff816373ed-ffffffff81637404: xen_add_device.cold (STB_LOCAL)
```
</details>
</li>
<li>
In <code>azure</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>gcp</code>: Transformation ⚠️</summary>

```c
int xen_add_device(struct device *dev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/xen/pci.c (0)
Location: drivers/xen/pci.c:26
Inline: False
```
**Symbols:**

```
ffffffff81664cb0-ffffffff81665081: xen_add_device (STB_LOCAL)
ffffffff8166516d-ffffffff81665184: xen_add_device.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
int xen_add_device(struct device *dev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/xen/pci.c (0)
Location: drivers/xen/pci.c:26
Inline: False
```
**Symbols:**

```
ffffffff8167f260-ffffffff8167f631: xen_add_device (STB_LOCAL)
ffffffff8167f71d-ffffffff8167f734: xen_add_device.cold (STB_LOCAL)
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
</ul>
<b>Flavor</b>
<ul>
<li>
No changes between <code>generic</code> and <code>aws</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>gcp</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>lowlatency</code> ✅
</li>
</ul>
