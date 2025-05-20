# Function: <code>vfio_del_group_dev</code>

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
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
void *vfio_del_group_dev(struct device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/vfio/vfio.c (0)
Location: drivers/vfio/vfio.c:905
Inline: False
Direct callers:
  - drivers/vfio/pci/vfio_pci.c:vfio_pci_probe
```
**Symbols:**

```
ffffffff817d2572-ffffffff817d25a1: vfio_del_group_dev.cold (STB_LOCAL)
ffffffff817d1ac0-ffffffff817d1d4a: vfio_del_group_dev (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
void *vfio_del_group_dev(struct device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/vfio/vfio.c (0)
Location: drivers/vfio/vfio.c:920
Inline: False
Direct callers:
  - drivers/vfio/pci/vfio_pci.c:vfio_pci_remove
  - drivers/vfio/pci/vfio_pci.c:vfio_pci_probe
```
**Symbols:**

```
ffffffff8189d6d4-ffffffff8189d703: vfio_del_group_dev.cold (STB_LOCAL)
ffffffff8189c6c0-ffffffff8189c9aa: vfio_del_group_dev (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
void *vfio_del_group_dev(struct device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/vfio/vfio.c (0)
Location: drivers/vfio/vfio.c:921
Inline: False
Direct callers:
  - drivers/vfio/pci/vfio_pci.c:vfio_pci_remove
  - drivers/vfio/pci/vfio_pci.c:vfio_pci_probe
```
**Symbols:**

```
ffffffff81c19f70-ffffffff81c19f9f: vfio_del_group_dev.cold (STB_LOCAL)
ffffffff818ab2d0-ffffffff818ab5d5: vfio_del_group_dev (STB_GLOBAL)
```
</details>
</li>
<li>
In <code>5.13</code>: Absent ⚠️
</li>
<li>
In <code>5.15</code>: Absent ⚠️
</li>
<li>
In <code>5.19</code>: Absent ⚠️
</li>
<li>
In <code>6.2</code>: Absent ⚠️
</li>
<li>
In <code>6.5</code>: Absent ⚠️
</li>
<li>
In <code>6.8</code>: Absent ⚠️
</li>
</ul>
<b>Arch</b>
<ul>
<li>
In <code>arm64</code>: Absent ⚠️
</li>
<li>
In <code>armhf</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void *vfio_del_group_dev(struct device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/vfio/vfio.c (c000000000ab1460)
Location: drivers/vfio/vfio.c:905
Inline: False
Direct callers:
  - drivers/vfio/pci/vfio_pci.c:vfio_pci_probe
```
**Symbols:**

```
c000000000ab1460-c000000000ab17a4: vfio_del_group_dev (STB_GLOBAL)
```
</details>
</li>
<li>
In <code>riscv64</code>: Absent ⚠️
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
In <code>aws</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>azure</code>: Transformation ⚠️</summary>

```c
void *vfio_del_group_dev(struct device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/vfio/vfio.c (0)
Location: drivers/vfio/vfio.c:905
Inline: False
Direct callers:
  - drivers/vfio/pci/vfio_pci.c:vfio_pci_probe
```
**Symbols:**

```
ffffffff8177c622-ffffffff8177c651: vfio_del_group_dev.cold (STB_LOCAL)
ffffffff8177bb70-ffffffff8177bdfa: vfio_del_group_dev (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Transformation ⚠️</summary>

```c
void *vfio_del_group_dev(struct device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/vfio/vfio.c (0)
Location: drivers/vfio/vfio.c:905
Inline: False
Direct callers:
  - drivers/vfio/pci/vfio_pci.c:vfio_pci_probe
```
**Symbols:**

```
ffffffff817c73f2-ffffffff817c7421: vfio_del_group_dev.cold (STB_LOCAL)
ffffffff817c6940-ffffffff817c6bca: vfio_del_group_dev (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
void *vfio_del_group_dev(struct device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/vfio/vfio.c (0)
Location: drivers/vfio/vfio.c:905
Inline: False
Direct callers:
  - drivers/vfio/pci/vfio_pci.c:vfio_pci_probe
```
**Symbols:**

```
ffffffff817e1692-ffffffff817e16c1: vfio_del_group_dev.cold (STB_LOCAL)
ffffffff817e0be0-ffffffff817e0e65: vfio_del_group_dev (STB_GLOBAL)
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
</ul>
<b>Arch</b>
<ul>
<li>
No changes between <code>amd64</code> and <code>ppc64el</code> ✅
</li>
</ul>
<b>Flavor</b>
<ul>
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
