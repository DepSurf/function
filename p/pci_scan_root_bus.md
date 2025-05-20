# Function: <code>pci_scan_root_bus</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
struct pci_bus *pci_scan_root_bus(struct device *parent, int bus, struct pci_ops *ops, void *sysdata, struct list_head *resources);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/probe.c (ffffffff81432e20)
Location: drivers/pci/probe.c:2297
Inline: False
Direct callers:
  - arch/x86/pci/common.c:pcibios_scan_root
```
**Symbols:**

```
ffffffff81432e20-ffffffff81432e33: pci_scan_root_bus (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
struct pci_bus *pci_scan_root_bus(struct device *parent, int bus, struct pci_ops *ops, void *sysdata, struct list_head *resources);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/probe.c (ffffffff8147e680)
Location: drivers/pci/probe.c:2337
Inline: False
Direct callers:
  - arch/x86/pci/common.c:pcibios_scan_root
```
**Symbols:**

```
ffffffff8147e680-ffffffff8147e693: pci_scan_root_bus (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
struct pci_bus *pci_scan_root_bus(struct device *parent, int bus, struct pci_ops *ops, void *sysdata, struct list_head *resources);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/probe.c (ffffffff8149fd20)
Location: drivers/pci/probe.c:2415
Inline: False
Direct callers:
  - arch/x86/pci/common.c:pcibios_scan_root
```
**Symbols:**

```
ffffffff8149fd20-ffffffff8149fd33: pci_scan_root_bus (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
struct pci_bus *pci_scan_root_bus(struct device *parent, int bus, struct pci_ops *ops, void *sysdata, struct list_head *resources);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/probe.c (ffffffff814a9a80)
Location: drivers/pci/probe.c:2536
Inline: False
Direct callers:
  - arch/x86/pci/common.c:pcibios_scan_root
```
**Symbols:**

```
ffffffff814a9a80-ffffffff814a9b1b: pci_scan_root_bus (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
struct pci_bus *pci_scan_root_bus(struct device *parent, int bus, struct pci_ops *ops, void *sysdata, struct list_head *resources);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/probe.c (ffffffff814e8ce0)
Location: drivers/pci/probe.c:2763
Inline: False
Direct callers:
  - arch/x86/pci/common.c:pcibios_scan_root
```
**Symbols:**

```
ffffffff814e8ce0-ffffffff814e8d7f: pci_scan_root_bus (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
struct pci_bus *pci_scan_root_bus(struct device *parent, int bus, struct pci_ops *ops, void *sysdata, struct list_head *resources);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/probe.c (ffffffff815183c0)
Location: drivers/pci/probe.c:2980
Inline: False
Direct callers:
  - arch/x86/pci/common.c:pcibios_scan_root
```
**Symbols:**

```
ffffffff815183c0-ffffffff8151845f: pci_scan_root_bus (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
struct pci_bus *pci_scan_root_bus(struct device *parent, int bus, struct pci_ops *ops, void *sysdata, struct list_head *resources);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/probe.c (ffffffff8152de40)
Location: drivers/pci/probe.c:3106
Inline: False
Direct callers:
  - arch/x86/pci/common.c:pcibios_scan_root
```
**Symbols:**

```
ffffffff8152de40-ffffffff8152dedf: pci_scan_root_bus (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
struct pci_bus *pci_scan_root_bus(struct device *parent, int bus, struct pci_ops *ops, void *sysdata, struct list_head *resources);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pci/probe.c (0)
Location: drivers/pci/probe.c:3330
Inline: False
Direct callers:
  - arch/x86/pci/common.c:pcibios_scan_root
```
**Symbols:**

```
ffffffff8155d7a8-ffffffff8155d7e8: pci_scan_root_bus.cold (STB_LOCAL)
ffffffff8155c560-ffffffff8155c5cc: pci_scan_root_bus (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
struct pci_bus *pci_scan_root_bus(struct device *parent, int bus, struct pci_ops *ops, void *sysdata, struct list_head *resources);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pci/probe.c (0)
Location: drivers/pci/probe.c:3064
Inline: False
Direct callers:
  - arch/x86/pci/common.c:pcibios_scan_root
```
**Symbols:**

```
ffffffff8157e81c-ffffffff8157e85c: pci_scan_root_bus.cold (STB_LOCAL)
ffffffff8157d630-ffffffff8157d69c: pci_scan_root_bus (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
struct pci_bus *pci_scan_root_bus(struct device *parent, int bus, struct pci_ops *ops, void *sysdata, struct list_head *resources);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pci/probe.c (0)
Location: drivers/pci/probe.c:3116
Inline: False
Direct callers:
  - arch/x86/pci/common.c:pcibios_scan_root
```
**Symbols:**

```
ffffffff81623d33-ffffffff81623d73: pci_scan_root_bus.cold (STB_LOCAL)
ffffffff81622c20-ffffffff81622c8c: pci_scan_root_bus (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
struct pci_bus *pci_scan_root_bus(struct device *parent, int bus, struct pci_ops *ops, void *sysdata, struct list_head *resources);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pci/probe.c (0)
Location: drivers/pci/probe.c:3124
Inline: False
Direct callers:
  - arch/x86/pci/common.c:pcibios_scan_root
```
**Symbols:**

```
ffffffff81bf7a4b-ffffffff81bf7a8b: pci_scan_root_bus.cold (STB_LOCAL)
ffffffff81649820-ffffffff8164988c: pci_scan_root_bus (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
struct pci_bus *pci_scan_root_bus(struct device *parent, int bus, struct pci_ops *ops, void *sysdata, struct list_head *resources);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pci/probe.c (0)
Location: drivers/pci/probe.c:3168
Inline: False
Direct callers:
  - arch/x86/pci/common.c:pcibios_scan_root
```
**Symbols:**

```
ffffffff81be98f2-ffffffff81be9932: pci_scan_root_bus.cold (STB_LOCAL)
ffffffff8162c3e0-ffffffff8162c44c: pci_scan_root_bus (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
struct pci_bus *pci_scan_root_bus(struct device *parent, int bus, struct pci_ops *ops, void *sysdata, struct list_head *resources);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pci/probe.c (0)
Location: drivers/pci/probe.c:3210
Inline: False
Direct callers:
  - arch/x86/pci/common.c:pcibios_scan_root
```
**Symbols:**

```
ffffffff81ce4298-ffffffff81ce42d8: pci_scan_root_bus.cold (STB_LOCAL)
ffffffff8169b8b0-ffffffff8169b91c: pci_scan_root_bus (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
struct pci_bus *pci_scan_root_bus(struct device *parent, int bus, struct pci_ops *ops, void *sysdata, struct list_head *resources);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pci/probe.c (0)
Location: drivers/pci/probe.c:3181
Inline: False
Direct callers:
  - arch/x86/pci/common.c:pcibios_scan_root
```
**Symbols:**

```
ffffffff81eaacaa-ffffffff81eaace9: pci_scan_root_bus.cold (STB_LOCAL)
ffffffff817bd0b0-ffffffff817bd128: pci_scan_root_bus (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
struct pci_bus *pci_scan_root_bus(struct device *parent, int bus, struct pci_ops *ops, void *sysdata, struct list_head *resources);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/probe.c (ffffffff818d90d0)
Location: drivers/pci/probe.c:3191
Inline: False
Direct callers:
  - arch/x86/pci/common.c:pcibios_scan_root
```
**Symbols:**

```
ffffffff818d90d0-ffffffff818d9198: pci_scan_root_bus (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
struct pci_bus *pci_scan_root_bus(struct device *parent, int bus, struct pci_ops *ops, void *sysdata, struct list_head *resources);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/probe.c (ffffffff8191c410)
Location: drivers/pci/probe.c:3205
Inline: False
Direct callers:
  - arch/x86/pci/common.c:pcibios_scan_root
```
**Symbols:**

```
ffffffff8191c410-ffffffff8191c4d0: pci_scan_root_bus (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
struct pci_bus *pci_scan_root_bus(struct device *parent, int bus, struct pci_ops *ops, void *sysdata, struct list_head *resources);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/probe.c (ffffffff81964840)
Location: drivers/pci/probe.c:3254
Inline: False
Direct callers:
  - arch/x86/pci/common.c:pcibios_scan_root
```
**Symbols:**

```
ffffffff81964840-ffffffff81964900: pci_scan_root_bus (STB_GLOBAL)
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
struct pci_bus *pci_scan_root_bus(struct device *parent, int bus, struct pci_ops *ops, void *sysdata, struct list_head *resources);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/probe.c (ffff8000106e0e78)
Location: drivers/pci/probe.c:3064
Inline: False
```
**Symbols:**

```
ffff8000106e0e78-ffff8000106e0f88: pci_scan_root_bus (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
struct pci_bus *pci_scan_root_bus(struct device *parent, int bus, struct pci_ops *ops, void *sysdata, struct list_head *resources);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/probe.c (c087cbac)
Location: drivers/pci/probe.c:3064
Inline: False
```
**Symbols:**

```
c087cbac-c087cc80: pci_scan_root_bus (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
struct pci_bus *pci_scan_root_bus(struct device *parent, int bus, struct pci_ops *ops, void *sysdata, struct list_head *resources);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/probe.c (c00000000085a040)
Location: drivers/pci/probe.c:3064
Inline: False
```
**Symbols:**

```
c00000000085a040-c00000000085a144: pci_scan_root_bus (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
struct pci_bus *pci_scan_root_bus(struct device *parent, int bus, struct pci_ops *ops, void *sysdata, struct list_head *resources);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/probe.c (ffffffe0004b8b82)
Location: drivers/pci/probe.c:3064
Inline: False
```
**Symbols:**

```
ffffffe0004b8b82-ffffffe0004b8c54: pci_scan_root_bus (STB_GLOBAL)
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
struct pci_bus *pci_scan_root_bus(struct device *parent, int bus, struct pci_ops *ops, void *sysdata, struct list_head *resources);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pci/probe.c (0)
Location: drivers/pci/probe.c:3064
Inline: False
Direct callers:
  - arch/x86/pci/common.c:pcibios_scan_root
```
**Symbols:**

```
ffffffff81572d3c-ffffffff81572d7c: pci_scan_root_bus.cold (STB_LOCAL)
ffffffff81571b50-ffffffff81571bbc: pci_scan_root_bus (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Transformation ⚠️</summary>

```c
struct pci_bus *pci_scan_root_bus(struct device *parent, int bus, struct pci_ops *ops, void *sysdata, struct list_head *resources);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pci/probe.c (0)
Location: drivers/pci/probe.c:3064
Inline: False
Direct callers:
  - arch/x86/pci/common.c:pcibios_scan_root
```
**Symbols:**

```
ffffffff8156149c-ffffffff815614dc: pci_scan_root_bus.cold (STB_LOCAL)
ffffffff815602b0-ffffffff8156031c: pci_scan_root_bus (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Transformation ⚠️</summary>

```c
struct pci_bus *pci_scan_root_bus(struct device *parent, int bus, struct pci_ops *ops, void *sysdata, struct list_head *resources);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pci/probe.c (0)
Location: drivers/pci/probe.c:3064
Inline: False
Direct callers:
  - arch/x86/pci/common.c:pcibios_scan_root
```
**Symbols:**

```
ffffffff8157256c-ffffffff815725ac: pci_scan_root_bus.cold (STB_LOCAL)
ffffffff81571380-ffffffff815713ec: pci_scan_root_bus (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
struct pci_bus *pci_scan_root_bus(struct device *parent, int bus, struct pci_ops *ops, void *sysdata, struct list_head *resources);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pci/probe.c (0)
Location: drivers/pci/probe.c:3064
Inline: False
Direct callers:
  - arch/x86/pci/common.c:pcibios_scan_root
```
**Symbols:**

```
ffffffff8158ca4c-ffffffff8158ca8c: pci_scan_root_bus.cold (STB_LOCAL)
ffffffff8158b860-ffffffff8158b8cc: pci_scan_root_bus (STB_GLOBAL)
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
