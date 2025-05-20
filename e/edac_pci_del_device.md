# Function: <code>edac_pci_del_device</code>

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
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
struct edac_pci_ctl_info *edac_pci_del_device(struct device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/edac/edac_pci.c (ffffffff8175f8d0)
Location: drivers/edac/edac_pci.c:249
Inline: False
Direct callers:
  - drivers/edac/edac_pci.c:edac_pci_release_generic_ctl
```
**Symbols:**

```
ffffffff8175f8d0-ffffffff8175f9a1: edac_pci_del_device (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
struct edac_pci_ctl_info *edac_pci_del_device(struct device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/edac/edac_pci.c (ffffffff817d1960)
Location: drivers/edac/edac_pci.c:249
Inline: False
Direct callers:
  - drivers/edac/edac_pci.c:edac_pci_release_generic_ctl
```
**Symbols:**

```
ffffffff817d1960-ffffffff817d1a31: edac_pci_del_device (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Transformation ⚠️</summary>

```c
struct edac_pci_ctl_info *edac_pci_del_device(struct device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/edac/edac_pci.c (0)
Location: drivers/edac/edac_pci.c:249
Inline: False
Direct callers:
  - drivers/edac/edac_pci.c:edac_pci_release_generic_ctl
```
**Symbols:**

```
ffffffff8181abbd-ffffffff8181abe6: edac_pci_del_device.cold.10 (STB_LOCAL)
ffffffff8181a710-ffffffff8181a7c4: edac_pci_del_device (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Transformation ⚠️</summary>

```c
struct edac_pci_ctl_info *edac_pci_del_device(struct device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/edac/edac_pci.c (0)
Location: drivers/edac/edac_pci.c:249
Inline: False
Direct callers:
  - drivers/edac/edac_pci.c:edac_pci_release_generic_ctl
```
**Symbols:**

```
ffffffff818463ad-ffffffff818463d6: edac_pci_del_device.cold.10 (STB_LOCAL)
ffffffff81845f00-ffffffff81845fb4: edac_pci_del_device (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
struct edac_pci_ctl_info *edac_pci_del_device(struct device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/edac/edac_pci.c (0)
Location: drivers/edac/edac_pci.c:249
Inline: False
Direct callers:
  - drivers/edac/edac_pci.c:edac_pci_release_generic_ctl
```
**Symbols:**

```
ffffffff8188915b-ffffffff81889189: edac_pci_del_device.cold (STB_LOCAL)
ffffffff81888ce0-ffffffff81888da0: edac_pci_del_device (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
struct edac_pci_ctl_info *edac_pci_del_device(struct device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/edac/edac_pci.c (0)
Location: drivers/edac/edac_pci.c:249
Inline: False
Direct callers:
  - drivers/edac/edac_pci.c:edac_pci_release_generic_ctl
```
**Symbols:**

```
ffffffff818bb10b-ffffffff818bb139: edac_pci_del_device.cold (STB_LOCAL)
ffffffff818bac90-ffffffff818bad50: edac_pci_del_device (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
struct edac_pci_ctl_info *edac_pci_del_device(struct device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/edac/edac_pci.c (0)
Location: drivers/edac/edac_pci.c:249
Inline: False
Direct callers:
  - drivers/edac/edac_pci.c:edac_pci_release_generic_ctl
```
**Symbols:**

```
ffffffff8198ba61-ffffffff8198ba8f: edac_pci_del_device.cold (STB_LOCAL)
ffffffff8198b8e0-ffffffff8198b9a0: edac_pci_del_device (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
struct edac_pci_ctl_info *edac_pci_del_device(struct device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/edac/edac_pci.c (0)
Location: drivers/edac/edac_pci.c:249
Inline: False
Direct callers:
  - drivers/edac/edac_pci.c:edac_pci_release_generic_ctl
```
**Symbols:**

```
ffffffff81c28bab-ffffffff81c28bd9: edac_pci_del_device.cold (STB_LOCAL)
ffffffff8198f4d0-ffffffff8198f590: edac_pci_del_device (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
struct edac_pci_ctl_info *edac_pci_del_device(struct device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/edac/edac_pci.c (0)
Location: drivers/edac/edac_pci.c:249
Inline: False
Direct callers:
  - drivers/edac/edac_pci.c:edac_pci_release_generic_ctl
```
**Symbols:**

```
ffffffff81c1ad9e-ffffffff81c1adcc: edac_pci_del_device.cold (STB_LOCAL)
ffffffff81973ae0-ffffffff81973ba0: edac_pci_del_device (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
struct edac_pci_ctl_info *edac_pci_del_device(struct device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/edac/edac_pci.c (0)
Location: drivers/edac/edac_pci.c:249
Inline: False
Direct callers:
  - drivers/edac/edac_pci.c:edac_pci_release_generic_ctl
```
**Symbols:**

```
ffffffff81d2acce-ffffffff81d2acfc: edac_pci_del_device.cold (STB_LOCAL)
ffffffff81a1c7e0-ffffffff81a1c8a0: edac_pci_del_device (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
struct edac_pci_ctl_info *edac_pci_del_device(struct device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/edac/edac_pci.c (0)
Location: drivers/edac/edac_pci.c:248
Inline: False
Direct callers:
  - drivers/edac/edac_pci.c:edac_pci_release_generic_ctl
```
**Symbols:**

```
ffffffff81ef6e72-ffffffff81ef6e9b: edac_pci_del_device.cold (STB_LOCAL)
ffffffff81b858c0-ffffffff81b85983: edac_pci_del_device (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
struct edac_pci_ctl_info *edac_pci_del_device(struct device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/edac/edac_pci.c (ffffffff81d24870)
Location: drivers/edac/edac_pci.c:245
Inline: False
Direct callers:
  - drivers/edac/edac_pci.c:edac_pci_release_generic_ctl
```
**Symbols:**

```
ffffffff81d24870-ffffffff81d2495b: edac_pci_del_device (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
struct edac_pci_ctl_info *edac_pci_del_device(struct device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/edac/edac_pci.c (ffffffff81d8da80)
Location: drivers/edac/edac_pci.c:245
Inline: False
Direct callers:
  - drivers/edac/edac_pci.c:edac_pci_release_generic_ctl
```
**Symbols:**

```
ffffffff81d8da80-ffffffff81d8db80: edac_pci_del_device (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
struct edac_pci_ctl_info *edac_pci_del_device(struct device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/edac/edac_pci.c (ffffffff81e45330)
Location: drivers/edac/edac_pci.c:245
Inline: False
Direct callers:
  - drivers/edac/edac_pci.c:edac_pci_release_generic_ctl
```
**Symbols:**

```
ffffffff81e45330-ffffffff81e45430: edac_pci_del_device (STB_GLOBAL)
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
struct edac_pci_ctl_info *edac_pci_del_device(struct device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/edac/edac_pci.c (ffff800010b13258)
Location: drivers/edac/edac_pci.c:249
Inline: False
Direct callers:
  - drivers/edac/edac_pci.c:edac_pci_release_generic_ctl
```
**Symbols:**

```
ffff800010b13258-ffff800010b13334: edac_pci_del_device (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
struct edac_pci_ctl_info *edac_pci_del_device(struct device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/edac/edac_pci.c (c0bf1204)
Location: drivers/edac/edac_pci.c:249
Inline: False
Direct callers:
  - drivers/edac/edac_pci.c:edac_pci_release_generic_ctl
```
**Symbols:**

```
c0bf1204-c0bf12ec: edac_pci_del_device (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
struct edac_pci_ctl_info *edac_pci_del_device(struct device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/edac/edac_pci.c (c000000000c07bf0)
Location: drivers/edac/edac_pci.c:249
Inline: False
Direct callers:
  - drivers/edac/edac_pci.c:edac_pci_release_generic_ctl
```
**Symbols:**

```
c000000000c07bf0-c000000000c07d28: edac_pci_del_device (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
struct edac_pci_ctl_info *edac_pci_del_device(struct device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/edac/edac_pci.c (ffffffe0006ffce4)
Location: drivers/edac/edac_pci.c:249
Inline: False
Direct callers:
  - drivers/edac/edac_pci.c:edac_pci_release_generic_ctl
```
**Symbols:**

```
ffffffe0006ffce4-ffffffe0006ffda6: edac_pci_del_device (STB_GLOBAL)
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
struct edac_pci_ctl_info *edac_pci_del_device(struct device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/edac/edac_pci.c (0)
Location: drivers/edac/edac_pci.c:249
Inline: False
Direct callers:
  - drivers/edac/edac_pci.c:edac_pci_release_generic_ctl
```
**Symbols:**

```
ffffffff81860f8b-ffffffff81860fb9: edac_pci_del_device.cold (STB_LOCAL)
ffffffff81860b10-ffffffff81860bd0: edac_pci_del_device (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Transformation ⚠️</summary>

```c
struct edac_pci_ctl_info *edac_pci_del_device(struct device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/edac/edac_pci.c (0)
Location: drivers/edac/edac_pci.c:249
Inline: False
Direct callers:
  - drivers/edac/edac_pci.c:edac_pci_release_generic_ctl
```
**Symbols:**

```
ffffffff8182855b-ffffffff81828589: edac_pci_del_device.cold (STB_LOCAL)
ffffffff818280e0-ffffffff818281a0: edac_pci_del_device (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Transformation ⚠️</summary>

```c
struct edac_pci_ctl_info *edac_pci_del_device(struct device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/edac/edac_pci.c (0)
Location: drivers/edac/edac_pci.c:249
Inline: False
Direct callers:
  - drivers/edac/edac_pci.c:edac_pci_release_generic_ctl
```
**Symbols:**

```
ffffffff818b05bb-ffffffff818b05e9: edac_pci_del_device.cold (STB_LOCAL)
ffffffff818b0140-ffffffff818b0200: edac_pci_del_device (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
struct edac_pci_ctl_info *edac_pci_del_device(struct device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/edac/edac_pci.c (0)
Location: drivers/edac/edac_pci.c:249
Inline: False
Direct callers:
  - drivers/edac/edac_pci.c:edac_pci_release_generic_ctl
```
**Symbols:**

```
ffffffff818cc84b-ffffffff818cc879: edac_pci_del_device.cold (STB_LOCAL)
ffffffff818cc3d0-ffffffff818cc490: edac_pci_del_device (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
No changes between <code>amd64</code> and <code>armhf</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>ppc64el</code> ✅
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
