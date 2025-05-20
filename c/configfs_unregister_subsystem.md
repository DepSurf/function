# Function: <code>configfs_unregister_subsystem</code>

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
void configfs_unregister_subsystem(struct configfs_subsystem *subsys);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/configfs/dir.c (ffffffff812dfc90)
Location: fs/configfs/dir.c:1891
Inline: False
Direct callers:
  - drivers/pci/endpoint/pci-ep-cfs.c:pci_ep_cfs_exit
  - drivers/pci/endpoint/pci-ep-cfs.c:pci_ep_cfs_init
```
**Symbols:**

```
ffffffff812dfc90-ffffffff812dfdaf: configfs_unregister_subsystem (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void configfs_unregister_subsystem(struct configfs_subsystem *subsys);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/configfs/dir.c (ffffffff81304610)
Location: fs/configfs/dir.c:1891
Inline: False
Direct callers:
  - drivers/pci/endpoint/pci-ep-cfs.c:pci_ep_cfs_exit
  - drivers/pci/endpoint/pci-ep-cfs.c:pci_ep_cfs_init
```
**Symbols:**

```
ffffffff81304610-ffffffff8130472f: configfs_unregister_subsystem (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Transformation ⚠️</summary>

```c
void configfs_unregister_subsystem(struct configfs_subsystem *subsys);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/configfs/dir.c (0)
Location: fs/configfs/dir.c:1902
Inline: False
Direct callers:
  - drivers/pci/endpoint/pci-ep-cfs.c:pci_ep_cfs_exit
  - drivers/pci/endpoint/pci-ep-cfs.c:pci_ep_cfs_init
```
**Symbols:**

```
ffffffff81333950-ffffffff81333972: configfs_unregister_subsystem.cold.37 (STB_LOCAL)
ffffffff813320e0-ffffffff813321e0: configfs_unregister_subsystem (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Transformation ⚠️</summary>

```c
void configfs_unregister_subsystem(struct configfs_subsystem *subsys);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/configfs/dir.c (0)
Location: fs/configfs/dir.c:1902
Inline: False
Direct callers:
  - drivers/pci/endpoint/pci-ep-cfs.c:pci_ep_cfs_exit
  - drivers/pci/endpoint/pci-ep-cfs.c:pci_ep_cfs_init
```
**Symbols:**

```
ffffffff8134ace0-ffffffff8134ad02: configfs_unregister_subsystem.cold.36 (STB_LOCAL)
ffffffff813494d0-ffffffff813495d0: configfs_unregister_subsystem (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
void configfs_unregister_subsystem(struct configfs_subsystem *subsys);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/configfs/dir.c (0)
Location: fs/configfs/dir.c:1962
Inline: False
Direct callers:
  - drivers/pci/endpoint/pci-ep-cfs.c:pci_ep_cfs_exit
  - drivers/pci/endpoint/pci-ep-cfs.c:pci_ep_cfs_init
```
**Symbols:**

```
ffffffff81373602-ffffffff81373624: configfs_unregister_subsystem.cold (STB_LOCAL)
ffffffff813720c0-ffffffff8137221d: configfs_unregister_subsystem (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
void configfs_unregister_subsystem(struct configfs_subsystem *subsys);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/configfs/dir.c (0)
Location: fs/configfs/dir.c:1919
Inline: False
Direct callers:
  - drivers/pci/endpoint/pci-ep-cfs.c:pci_ep_cfs_exit
  - drivers/pci/endpoint/pci-ep-cfs.c:pci_ep_cfs_init
```
**Symbols:**

```
ffffffff8138b98f-ffffffff8138b9b1: configfs_unregister_subsystem.cold (STB_LOCAL)
ffffffff8138a6d0-ffffffff8138a82d: configfs_unregister_subsystem (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
void configfs_unregister_subsystem(struct configfs_subsystem *subsys);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/configfs/dir.c (0)
Location: fs/configfs/dir.c:1920
Inline: False
Direct callers:
  - drivers/pci/endpoint/pci-ep-cfs.c:pci_ep_cfs_exit
  - drivers/pci/endpoint/pci-ep-cfs.c:pci_ep_cfs_init
```
**Symbols:**

```
ffffffff813d6c4f-ffffffff813d6c71: configfs_unregister_subsystem.cold (STB_LOCAL)
ffffffff813d5a70-ffffffff813d5c08: configfs_unregister_subsystem (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
void configfs_unregister_subsystem(struct configfs_subsystem *subsys);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/configfs/dir.c (0)
Location: fs/configfs/dir.c:1921
Inline: False
Direct callers:
  - drivers/pci/endpoint/pci-ep-cfs.c:pci_ep_cfs_exit
  - drivers/pci/endpoint/pci-ep-cfs.c:pci_ep_cfs_init
```
**Symbols:**

```
ffffffff81bec193-ffffffff81bec1b5: configfs_unregister_subsystem.cold (STB_LOCAL)
ffffffff813e7760-ffffffff813e78d7: configfs_unregister_subsystem (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
void configfs_unregister_subsystem(struct configfs_subsystem *subsys);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/configfs/dir.c (0)
Location: fs/configfs/dir.c:1920
Inline: False
Direct callers:
  - drivers/pci/endpoint/pci-ep-cfs.c:pci_ep_cfs_exit
  - drivers/pci/endpoint/pci-ep-cfs.c:pci_ep_cfs_init
```
**Symbols:**

```
ffffffff81bde1f1-ffffffff81bde213: configfs_unregister_subsystem.cold (STB_LOCAL)
ffffffff813ee130-ffffffff813ee2a7: configfs_unregister_subsystem (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
void configfs_unregister_subsystem(struct configfs_subsystem *subsys);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/configfs/dir.c (0)
Location: fs/configfs/dir.c:1907
Inline: False
Direct callers:
  - drivers/pci/endpoint/pci-ep-cfs.c:pci_ep_cfs_exit
  - drivers/pci/endpoint/pci-ep-cfs.c:pci_ep_cfs_init
```
**Symbols:**

```
ffffffff81cc87c8-ffffffff81cc87ea: configfs_unregister_subsystem.cold (STB_LOCAL)
ffffffff8143f940-ffffffff8143faf8: configfs_unregister_subsystem (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
void configfs_unregister_subsystem(struct configfs_subsystem *subsys);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/configfs/dir.c (0)
Location: fs/configfs/dir.c:1907
Inline: False
Direct callers:
  - drivers/pci/endpoint/pci-ep-cfs.c:pci_ep_cfs_exit
  - drivers/pci/endpoint/pci-ep-cfs.c:pci_ep_cfs_init
```
**Symbols:**

```
ffffffff81e7b513-ffffffff81e7b535: configfs_unregister_subsystem.cold (STB_LOCAL)
ffffffff814bbeb0-ffffffff814bc06d: configfs_unregister_subsystem (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void configfs_unregister_subsystem(struct configfs_subsystem *subsys);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/configfs/dir.c (ffffffff815539b0)
Location: fs/configfs/dir.c:1909
Inline: False
Direct callers:
  - drivers/pci/endpoint/pci-ep-cfs.c:pci_ep_cfs_exit
  - drivers/pci/endpoint/pci-ep-cfs.c:pci_ep_cfs_init
```
**Symbols:**

```
ffffffff815539b0-ffffffff81553ba7: configfs_unregister_subsystem (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void configfs_unregister_subsystem(struct configfs_subsystem *subsys);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/configfs/dir.c (ffffffff8158b740)
Location: fs/configfs/dir.c:1904
Inline: False
Direct callers:
  - drivers/pci/endpoint/pci-ep-cfs.c:pci_ep_cfs_exit
  - drivers/pci/endpoint/pci-ep-cfs.c:pci_ep_cfs_init
```
**Symbols:**

```
ffffffff8158b740-ffffffff8158b937: configfs_unregister_subsystem (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void configfs_unregister_subsystem(struct configfs_subsystem *subsys);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/configfs/dir.c (ffffffff815c4470)
Location: fs/configfs/dir.c:1904
Inline: False
Direct callers:
  - drivers/pci/endpoint/pci-ep-cfs.c:pci_ep_cfs_exit
  - drivers/pci/endpoint/pci-ep-cfs.c:pci_ep_cfs_init
```
**Symbols:**

```
ffffffff815c4470-ffffffff815c466d: configfs_unregister_subsystem (STB_GLOBAL)
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
void configfs_unregister_subsystem(struct configfs_subsystem *subsys);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/configfs/dir.c (ffff80001045acb0)
Location: fs/configfs/dir.c:1919
Inline: False
Direct callers:
  - drivers/pci/endpoint/pci-ep-cfs.c:pci_ep_cfs_exit
  - drivers/pci/endpoint/pci-ep-cfs.c:pci_ep_cfs_init
```
**Symbols:**

```
ffff80001045acb0-ffff80001045aec0: configfs_unregister_subsystem (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void configfs_unregister_subsystem(struct configfs_subsystem *subsys);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/configfs/dir.c (c061c884)
Location: fs/configfs/dir.c:1919
Inline: False
Direct callers:
  - drivers/pci/endpoint/pci-ep-cfs.c:pci_ep_cfs_exit
  - drivers/pci/endpoint/pci-ep-cfs.c:pci_ep_cfs_init
```
**Symbols:**

```
c061c884-c061ca58: configfs_unregister_subsystem (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void configfs_unregister_subsystem(struct configfs_subsystem *subsys);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/configfs/dir.c (c0000000005766d0)
Location: fs/configfs/dir.c:1919
Inline: False
Direct callers:
  - drivers/pci/endpoint/pci-ep-cfs.c:pci_ep_cfs_exit
  - drivers/pci/endpoint/pci-ep-cfs.c:pci_ep_cfs_init
```
**Symbols:**

```
c0000000005766d0-c000000000576940: configfs_unregister_subsystem (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void configfs_unregister_subsystem(struct configfs_subsystem *subsys);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/configfs/dir.c (ffffffe0002eb5b2)
Location: fs/configfs/dir.c:1919
Inline: False
Direct callers:
  - drivers/pci/endpoint/pci-ep-cfs.c:pci_ep_cfs_exit
  - drivers/pci/endpoint/pci-ep-cfs.c:pci_ep_cfs_init
```
**Symbols:**

```
ffffffe0002eb5b2-ffffffe0002eb7a6: configfs_unregister_subsystem (STB_GLOBAL)
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
void configfs_unregister_subsystem(struct configfs_subsystem *subsys);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/configfs/dir.c (0)
Location: fs/configfs/dir.c:1919
Inline: False
Direct callers:
  - drivers/pci/endpoint/pci-ep-cfs.c:pci_ep_cfs_exit
  - drivers/pci/endpoint/pci-ep-cfs.c:pci_ep_cfs_init
```
**Symbols:**

```
ffffffff81383f6f-ffffffff81383f91: configfs_unregister_subsystem.cold (STB_LOCAL)
ffffffff81382cb0-ffffffff81382e0d: configfs_unregister_subsystem (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Transformation ⚠️</summary>

```c
void configfs_unregister_subsystem(struct configfs_subsystem *subsys);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/configfs/dir.c (0)
Location: fs/configfs/dir.c:1919
Inline: False
Direct callers:
  - drivers/pci/endpoint/pci-ep-cfs.c:pci_ep_cfs_exit
  - drivers/pci/endpoint/pci-ep-cfs.c:pci_ep_cfs_init
```
**Symbols:**

```
ffffffff813749ff-ffffffff81374a21: configfs_unregister_subsystem.cold (STB_LOCAL)
ffffffff81373740-ffffffff8137389d: configfs_unregister_subsystem (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Transformation ⚠️</summary>

```c
void configfs_unregister_subsystem(struct configfs_subsystem *subsys);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/configfs/dir.c (0)
Location: fs/configfs/dir.c:1919
Inline: False
Direct callers:
  - drivers/pci/endpoint/pci-ep-cfs.c:pci_ep_cfs_exit
  - drivers/pci/endpoint/pci-ep-cfs.c:pci_ep_cfs_init
```
**Symbols:**

```
ffffffff81381a3f-ffffffff81381a61: configfs_unregister_subsystem.cold (STB_LOCAL)
ffffffff81380780-ffffffff813808dd: configfs_unregister_subsystem (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
void configfs_unregister_subsystem(struct configfs_subsystem *subsys);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/configfs/dir.c (0)
Location: fs/configfs/dir.c:1919
Inline: False
Direct callers:
  - drivers/pci/endpoint/pci-ep-cfs.c:pci_ep_cfs_exit
  - drivers/pci/endpoint/pci-ep-cfs.c:pci_ep_cfs_init
```
**Symbols:**

```
ffffffff8139556f-ffffffff81395591: configfs_unregister_subsystem.cold (STB_LOCAL)
ffffffff81394240-ffffffff81394399: configfs_unregister_subsystem (STB_GLOBAL)
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
