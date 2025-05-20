# Function: <code>pci_find_next_bus</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
struct pci_bus *pci_find_next_bus(const struct pci_bus *from);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/search.c (ffffffff8143a9c0)
Location: drivers/pci/search.c:156
Inline: False
Direct callers:
  - drivers/pci/search.c:pci_find_bus
  - drivers/pci/pci-sysfs.c:bus_rescan_store
```
**Symbols:**

```
ffffffff8143a9c0-ffffffff8143aa2d: pci_find_next_bus (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
struct pci_bus *pci_find_next_bus(const struct pci_bus *from);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/search.c (ffffffff814868f0)
Location: drivers/pci/search.c:160
Inline: False
Direct callers:
  - drivers/pci/search.c:pci_find_bus
  - drivers/pci/pci-sysfs.c:bus_rescan_store
```
**Symbols:**

```
ffffffff814868f0-ffffffff8148695c: pci_find_next_bus (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
struct pci_bus *pci_find_next_bus(const struct pci_bus *from);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/search.c (ffffffff814a80a0)
Location: drivers/pci/search.c:160
Inline: False
Direct callers:
  - drivers/pci/search.c:pci_find_bus
  - drivers/pci/pci-sysfs.c:bus_rescan_store
```
**Symbols:**

```
ffffffff814a80a0-ffffffff814a810c: pci_find_next_bus (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
struct pci_bus *pci_find_next_bus(const struct pci_bus *from);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/search.c (ffffffff814b2080)
Location: drivers/pci/search.c:164
Inline: False
Direct callers:
  - drivers/pci/search.c:pci_find_bus
  - drivers/pci/pci-sysfs.c:bus_rescan_store
```
**Symbols:**

```
ffffffff814b2080-ffffffff814b20de: pci_find_next_bus (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
struct pci_bus *pci_find_next_bus(const struct pci_bus *from);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/search.c (ffffffff814f1770)
Location: drivers/pci/search.c:164
Inline: False
Direct callers:
  - drivers/pci/search.c:pci_find_bus
  - drivers/pci/pci-sysfs.c:bus_rescan_store
```
**Symbols:**

```
ffffffff814f1770-ffffffff814f17ce: pci_find_next_bus (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
struct pci_bus *pci_find_next_bus(const struct pci_bus *from);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/search.c (ffffffff81521a00)
Location: drivers/pci/search.c:165
Inline: False
Direct callers:
  - drivers/pci/search.c:pci_find_bus
  - drivers/pci/pci-sysfs.c:bus_rescan_store
```
**Symbols:**

```
ffffffff81521a00-ffffffff81521a5e: pci_find_next_bus (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
struct pci_bus *pci_find_next_bus(const struct pci_bus *from);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/search.c (ffffffff81537830)
Location: drivers/pci/search.c:165
Inline: False
Direct callers:
  - drivers/pci/search.c:pci_find_bus
  - drivers/pci/pci-sysfs.c:bus_rescan_store
```
**Symbols:**

```
ffffffff81537830-ffffffff8153788e: pci_find_next_bus (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
struct pci_bus *pci_find_next_bus(const struct pci_bus *from);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pci/search.c (0)
Location: drivers/pci/search.c:161
Inline: False
Direct callers:
  - drivers/pci/search.c:pci_find_bus
  - drivers/pci/pci-sysfs.c:rescan_store
```
**Symbols:**

```
ffffffff815676d6-ffffffff815676e9: pci_find_next_bus.cold (STB_LOCAL)
ffffffff815671c0-ffffffff81567220: pci_find_next_bus (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
struct pci_bus *pci_find_next_bus(const struct pci_bus *from);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/search.c (ffffffff81588520)
Location: drivers/pci/search.c:160
Inline: False
Direct callers:
  - drivers/pci/search.c:pci_find_bus
  - drivers/pci/pci-sysfs.c:rescan_store
```
**Symbols:**

```
ffffffff81588520-ffffffff81588580: pci_find_next_bus (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
struct pci_bus *pci_find_next_bus(const struct pci_bus *from);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/search.c (ffffffff8162f150)
Location: drivers/pci/search.c:166
Inline: False
Direct callers:
  - drivers/pci/search.c:pci_find_bus
  - drivers/pci/pci-sysfs.c:rescan_store
```
**Symbols:**

```
ffffffff8162f150-ffffffff8162f1b0: pci_find_next_bus (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
struct pci_bus *pci_find_next_bus(const struct pci_bus *from);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/search.c (ffffffff816547e0)
Location: drivers/pci/search.c:166
Inline: False
Direct callers:
  - arch/x86/events/intel/uncore_snbep.c:skx_iio_get_topology
  - arch/x86/events/intel/uncore_snbep.c:skx_iio_mapping_show
  - drivers/pci/search.c:pci_find_bus
  - drivers/pci/pci-sysfs.c:rescan_store
```
**Symbols:**

```
ffffffff816547e0-ffffffff81654840: pci_find_next_bus (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
struct pci_bus *pci_find_next_bus(const struct pci_bus *from);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/search.c (ffffffff816379a2)
Location: drivers/pci/search.c:166
Inline: True
Inline callers:
  - drivers/pci/search.c:pci_find_bus
Direct callers:
  - arch/x86/events/intel/uncore.c:uncore_die_to_segment
  - drivers/pci/pci-sysfs.c:pci_sysfs_init
  - drivers/pci/pci-sysfs.c:rescan_store
```
**Symbols:**

```
ffffffff81637260-ffffffff816372ab: pci_find_next_bus (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
struct pci_bus *pci_find_next_bus(const struct pci_bus *from);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/search.c (ffffffff816a7c32)
Location: drivers/pci/search.c:166
Inline: True
Inline callers:
  - drivers/pci/search.c:pci_find_bus
Direct callers:
  - arch/x86/events/intel/uncore.c:uncore_die_to_segment
  - drivers/pci/pci-sysfs.c:pci_sysfs_init
  - drivers/pci/pci-sysfs.c:rescan_store
```
**Symbols:**

```
ffffffff816a74d0-ffffffff816a751b: pci_find_next_bus (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
struct pci_bus *pci_find_next_bus(const struct pci_bus *from);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/search.c (ffffffff817ca6f5)
Location: drivers/pci/search.c:166
Inline: True
Inline callers:
  - drivers/pci/search.c:pci_find_bus
Direct callers:
  - arch/x86/events/intel/uncore.c:uncore_die_to_segment
  - drivers/pci/pci-sysfs.c:pci_sysfs_init
  - drivers/pci/pci-sysfs.c:rescan_store
```
**Symbols:**

```
ffffffff817c9ec0-ffffffff817c9f12: pci_find_next_bus (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
struct pci_bus *pci_find_next_bus(const struct pci_bus *from);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/search.c (ffffffff818e81e5)
Location: drivers/pci/search.c:166
Inline: True
Inline callers:
  - drivers/pci/search.c:pci_find_bus
Direct callers:
  - arch/x86/events/intel/uncore.c:uncore_die_to_segment
  - drivers/pci/pci-sysfs.c:pci_sysfs_init
  - drivers/pci/pci-sysfs.c:rescan_store
```
**Symbols:**

```
ffffffff818e7930-ffffffff818e7982: pci_find_next_bus (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
struct pci_bus *pci_find_next_bus(const struct pci_bus *from);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/search.c (ffffffff8192b7f5)
Location: drivers/pci/search.c:166
Inline: True
Inline callers:
  - drivers/pci/search.c:pci_find_bus
Direct callers:
  - arch/x86/events/intel/uncore.c:uncore_die_to_segment
  - drivers/pci/pci-sysfs.c:pci_sysfs_init
  - drivers/pci/pci-sysfs.c:rescan_store
```
**Symbols:**

```
ffffffff8192af50-ffffffff8192afa2: pci_find_next_bus (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
struct pci_bus *pci_find_next_bus(const struct pci_bus *from);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/search.c (ffffffff81974145)
Location: drivers/pci/search.c:166
Inline: True
Inline callers:
  - drivers/pci/search.c:pci_find_bus
Direct callers:
  - arch/x86/events/intel/uncore.c:uncore_die_to_segment
  - drivers/pci/pci-sysfs.c:pci_sysfs_init
  - drivers/pci/pci-sysfs.c:rescan_store
```
**Symbols:**

```
ffffffff819737d0-ffffffff81973822: pci_find_next_bus (STB_GLOBAL)
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
struct pci_bus *pci_find_next_bus(const struct pci_bus *from);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/search.c (ffff8000106eca18)
Location: drivers/pci/search.c:160
Inline: False
Direct callers:
  - drivers/pci/search.c:pci_find_bus
  - drivers/pci/pci-sysfs.c:rescan_store
```
**Symbols:**

```
ffff8000106eca18-ffff8000106eca90: pci_find_next_bus (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
struct pci_bus *pci_find_next_bus(const struct pci_bus *from);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/search.c (c0887c38)
Location: drivers/pci/search.c:160
Inline: False
Direct callers:
  - drivers/pci/search.c:pci_find_bus
  - drivers/pci/pci-sysfs.c:rescan_store
```
**Symbols:**

```
c0887c38-c0887cd4: pci_find_next_bus (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
struct pci_bus *pci_find_next_bus(const struct pci_bus *from);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/search.c (c000000000868750)
Location: drivers/pci/search.c:160
Inline: False
Direct callers:
  - drivers/pci/search.c:pci_find_bus
  - drivers/pci/pci-sysfs.c:rescan_store
```
**Symbols:**

```
c000000000868750-c00000000086882c: pci_find_next_bus (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
struct pci_bus *pci_find_next_bus(const struct pci_bus *from);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/search.c (ffffffe0004c191c)
Location: drivers/pci/search.c:160
Inline: False
Direct callers:
  - drivers/pci/search.c:pci_find_bus
  - drivers/pci/pci-sysfs.c:rescan_store
```
**Symbols:**

```
ffffffe0004c191c-ffffffe0004c1996: pci_find_next_bus (STB_GLOBAL)
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
struct pci_bus *pci_find_next_bus(const struct pci_bus *from);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/search.c (ffffffff8157c3b0)
Location: drivers/pci/search.c:160
Inline: False
Direct callers:
  - drivers/pci/search.c:pci_find_bus
  - drivers/pci/pci-sysfs.c:rescan_store
```
**Symbols:**

```
ffffffff8157c3b0-ffffffff8157c410: pci_find_next_bus (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
struct pci_bus *pci_find_next_bus(const struct pci_bus *from);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/search.c (ffffffff8156b180)
Location: drivers/pci/search.c:160
Inline: False
Direct callers:
  - drivers/pci/search.c:pci_find_bus
  - drivers/pci/pci-sysfs.c:rescan_store
```
**Symbols:**

```
ffffffff8156b180-ffffffff8156b1e0: pci_find_next_bus (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
struct pci_bus *pci_find_next_bus(const struct pci_bus *from);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/search.c (ffffffff8157c270)
Location: drivers/pci/search.c:160
Inline: False
Direct callers:
  - drivers/pci/search.c:pci_find_bus
  - drivers/pci/pci-sysfs.c:rescan_store
```
**Symbols:**

```
ffffffff8157c270-ffffffff8157c2d0: pci_find_next_bus (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
struct pci_bus *pci_find_next_bus(const struct pci_bus *from);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/search.c (ffffffff81596720)
Location: drivers/pci/search.c:160
Inline: False
Direct callers:
  - drivers/pci/search.c:pci_find_bus
  - drivers/pci/pci-sysfs.c:rescan_store
```
**Symbols:**

```
ffffffff81596720-ffffffff81596780: pci_find_next_bus (STB_GLOBAL)
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
