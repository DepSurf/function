# Function: <code>pci_generic_config_write32</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int pci_generic_config_write32(struct pci_bus *bus, unsigned int devfn, int where, int size, u32 val);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/access.c (ffffffff8142de20)
Location: drivers/pci/access.c:132
Inline: False
```
**Symbols:**

```
ffffffff8142de20-ffffffff8142de97: pci_generic_config_write32 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int pci_generic_config_write32(struct pci_bus *bus, unsigned int devfn, int where, int size, u32 val);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/access.c (ffffffff814791b0)
Location: drivers/pci/access.c:132
Inline: False
```
**Symbols:**

```
ffffffff814791b0-ffffffff8147922a: pci_generic_config_write32 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int pci_generic_config_write32(struct pci_bus *bus, unsigned int devfn, int where, int size, u32 val);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/access.c (ffffffff8149a730)
Location: drivers/pci/access.c:132
Inline: False
```
**Symbols:**

```
ffffffff8149a730-ffffffff8149a82e: pci_generic_config_write32 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int pci_generic_config_write32(struct pci_bus *bus, unsigned int devfn, int where, int size, u32 val);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/access.c (ffffffff814a4390)
Location: drivers/pci/access.c:140
Inline: False
```
**Symbols:**

```
ffffffff814a4390-ffffffff814a449a: pci_generic_config_write32 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int pci_generic_config_write32(struct pci_bus *bus, unsigned int devfn, int where, int size, u32 val);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/access.c (ffffffff814e3130)
Location: drivers/pci/access.c:140
Inline: False
```
**Symbols:**

```
ffffffff814e3130-ffffffff814e3240: pci_generic_config_write32 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int pci_generic_config_write32(struct pci_bus *bus, unsigned int devfn, int where, int size, u32 val);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/access.c (ffffffff815130a0)
Location: drivers/pci/access.c:139
Inline: False
```
**Symbols:**

```
ffffffff815130a0-ffffffff815131b4: pci_generic_config_write32 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int pci_generic_config_write32(struct pci_bus *bus, unsigned int devfn, int where, int size, u32 val);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/access.c (ffffffff81528790)
Location: drivers/pci/access.c:139
Inline: False
```
**Symbols:**

```
ffffffff81528790-ffffffff815288a4: pci_generic_config_write32 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
int pci_generic_config_write32(struct pci_bus *bus, unsigned int devfn, int where, int size, u32 val);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pci/access.c (0)
Location: drivers/pci/access.c:139
Inline: False
```
**Symbols:**

```
ffffffff8155861b-ffffffff8155865e: pci_generic_config_write32.cold (STB_LOCAL)
ffffffff81557a20-ffffffff81557af7: pci_generic_config_write32 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
int pci_generic_config_write32(struct pci_bus *bus, unsigned int devfn, int where, int size, u32 val);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pci/access.c (0)
Location: drivers/pci/access.c:139
Inline: False
```
**Symbols:**

```
ffffffff81579c16-ffffffff81579c59: pci_generic_config_write32.cold (STB_LOCAL)
ffffffff81579050-ffffffff81579127: pci_generic_config_write32 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
int pci_generic_config_write32(struct pci_bus *bus, unsigned int devfn, int where, int size, u32 val);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pci/access.c (0)
Location: drivers/pci/access.c:139
Inline: False
```
**Symbols:**

```
ffffffff8161ec83-ffffffff8161ecc6: pci_generic_config_write32.cold (STB_LOCAL)
ffffffff8161e060-ffffffff8161e137: pci_generic_config_write32 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
int pci_generic_config_write32(struct pci_bus *bus, unsigned int devfn, int where, int size, u32 val);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pci/access.c (0)
Location: drivers/pci/access.c:139
Inline: False
```
**Symbols:**

```
ffffffff81bf6e37-ffffffff81bf6e7a: pci_generic_config_write32.cold (STB_LOCAL)
ffffffff81644880-ffffffff81644957: pci_generic_config_write32 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
int pci_generic_config_write32(struct pci_bus *bus, unsigned int devfn, int where, int size, u32 val);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pci/access.c (0)
Location: drivers/pci/access.c:139
Inline: False
```
**Symbols:**

```
ffffffff81be8ca6-ffffffff81be8ce9: pci_generic_config_write32.cold (STB_LOCAL)
ffffffff81627600-ffffffff816276d0: pci_generic_config_write32 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int pci_generic_config_write32(struct pci_bus *bus, unsigned int devfn, int where, int size, u32 val);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pci/access.c (0)
Location: drivers/pci/access.c:139
Inline: False
```
**Symbols:**

```
ffffffff81ce3082-ffffffff81ce30e4: pci_generic_config_write32.cold (STB_LOCAL)
ffffffff81696ef0-ffffffff81696fcd: pci_generic_config_write32 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int pci_generic_config_write32(struct pci_bus *bus, unsigned int devfn, int where, int size, u32 val);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pci/access.c (0)
Location: drivers/pci/access.c:138
Inline: False
```
**Symbols:**

```
ffffffff81ea9b6f-ffffffff81ea9bd8: pci_generic_config_write32.cold (STB_LOCAL)
ffffffff817b7f80-ffffffff817b8055: pci_generic_config_write32 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
int pci_generic_config_write32(struct pci_bus *bus, unsigned int devfn, int where, int size, u32 val);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pci/access.c (0)
Location: drivers/pci/access.c:138
Inline: False
```
**Symbols:**

```
ffffffff8208ef2b-ffffffff8208ef4a: pci_generic_config_write32.cold (STB_LOCAL)
ffffffff818d2870-ffffffff818d298f: pci_generic_config_write32 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
int pci_generic_config_write32(struct pci_bus *bus, unsigned int devfn, int where, int size, u32 val);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pci/access.c (0)
Location: drivers/pci/access.c:138
Inline: False
```
**Symbols:**

```
ffffffff8210f273-ffffffff8210f292: pci_generic_config_write32.cold (STB_LOCAL)
ffffffff81915870-ffffffff8191598f: pci_generic_config_write32 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
int pci_generic_config_write32(struct pci_bus *bus, unsigned int devfn, int where, int size, u32 val);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pci/access.c (0)
Location: drivers/pci/access.c:138
Inline: False
```
**Symbols:**

```
ffffffff821ecf1b-ffffffff821ecf3a: pci_generic_config_write32.cold (STB_LOCAL)
ffffffff8195d7e0-ffffffff8195d8ff: pci_generic_config_write32 (STB_GLOBAL)
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
int pci_generic_config_write32(struct pci_bus *bus, unsigned int devfn, int where, int size, u32 val);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/access.c (ffff8000106da4c0)
Location: drivers/pci/access.c:139
Inline: False
Direct callers:
  - drivers/pci/controller/dwc/pcie-hisi.c:hisi_pcie_wr_conf
```
**Symbols:**

```
ffff8000106da4c0-ffff8000106da5ec: pci_generic_config_write32 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int pci_generic_config_write32(struct pci_bus *bus, unsigned int devfn, int where, int size, u32 val);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/access.c (c087740c)
Location: drivers/pci/access.c:139
Inline: False
Direct callers:
  - drivers/pci/controller/pci-tegra.c:tegra_pcie_config_write
```
**Symbols:**

```
c087740c-c0877510: pci_generic_config_write32 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int pci_generic_config_write32(struct pci_bus *bus, unsigned int devfn, int where, int size, u32 val);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/access.c (c000000000852a10)
Location: drivers/pci/access.c:139
Inline: False
```
**Symbols:**

```
c000000000852a10-c000000000852c08: pci_generic_config_write32 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int pci_generic_config_write32(struct pci_bus *bus, unsigned int devfn, int where, int size, u32 val);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/access.c (ffffffe0004b3cfc)
Location: drivers/pci/access.c:139
Inline: False
```
**Symbols:**

```
ffffffe0004b3cfc-ffffffe0004b3e02: pci_generic_config_write32 (STB_GLOBAL)
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
int pci_generic_config_write32(struct pci_bus *bus, unsigned int devfn, int where, int size, u32 val);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pci/access.c (0)
Location: drivers/pci/access.c:139
Inline: False
```
**Symbols:**

```
ffffffff8156e136-ffffffff8156e179: pci_generic_config_write32.cold (STB_LOCAL)
ffffffff8156d570-ffffffff8156d647: pci_generic_config_write32 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Transformation ⚠️</summary>

```c
int pci_generic_config_write32(struct pci_bus *bus, unsigned int devfn, int where, int size, u32 val);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pci/access.c (0)
Location: drivers/pci/access.c:139
Inline: False
```
**Symbols:**

```
ffffffff8155c896-ffffffff8155c8d9: pci_generic_config_write32.cold (STB_LOCAL)
ffffffff8155bce0-ffffffff8155bdb7: pci_generic_config_write32 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Transformation ⚠️</summary>

```c
int pci_generic_config_write32(struct pci_bus *bus, unsigned int devfn, int where, int size, u32 val);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pci/access.c (0)
Location: drivers/pci/access.c:139
Inline: False
```
**Symbols:**

```
ffffffff8156d966-ffffffff8156d9a9: pci_generic_config_write32.cold (STB_LOCAL)
ffffffff8156cda0-ffffffff8156ce77: pci_generic_config_write32 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
int pci_generic_config_write32(struct pci_bus *bus, unsigned int devfn, int where, int size, u32 val);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pci/access.c (0)
Location: drivers/pci/access.c:139
Inline: False
```
**Symbols:**

```
ffffffff81587e46-ffffffff81587e89: pci_generic_config_write32.cold (STB_LOCAL)
ffffffff815872a0-ffffffff81587377: pci_generic_config_write32 (STB_GLOBAL)
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
