# Function: <code>pci_bus_add_resource</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void pci_bus_add_resource(struct pci_bus *bus, struct resource *res, unsigned int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/bus.c (ffffffff8142f620)
Location: drivers/pci/bus.c:48
Inline: False
Direct callers:
  - drivers/pci/probe.c:pci_read_bridge_bases
  - drivers/pci/probe.c:pci_create_root_bus
```
**Symbols:**

```
ffffffff8142f620-ffffffff8142f68f: pci_bus_add_resource (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void pci_bus_add_resource(struct pci_bus *bus, struct resource *res, unsigned int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/bus.c (ffffffff8147ac20)
Location: drivers/pci/bus.c:48
Inline: False
Direct callers:
  - drivers/pci/probe.c:pci_create_root_bus
  - drivers/pci/probe.c:pci_read_bridge_bases
```
**Symbols:**

```
ffffffff8147ac20-ffffffff8147ac8f: pci_bus_add_resource (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void pci_bus_add_resource(struct pci_bus *bus, struct resource *res, unsigned int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/bus.c (ffffffff8149c0a0)
Location: drivers/pci/bus.c:48
Inline: False
Direct callers:
  - drivers/pci/probe.c:pci_register_host_bridge
  - drivers/pci/probe.c:pci_read_bridge_bases
```
**Symbols:**

```
ffffffff8149c0a0-ffffffff8149c10f: pci_bus_add_resource (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void pci_bus_add_resource(struct pci_bus *bus, struct resource *res, unsigned int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/bus.c (ffffffff814a5e40)
Location: drivers/pci/bus.c:48
Inline: False
Direct callers:
  - drivers/pci/probe.c:pci_register_host_bridge
  - drivers/pci/probe.c:pci_read_bridge_bases
```
**Symbols:**

```
ffffffff814a5e40-ffffffff814a5eb4: pci_bus_add_resource (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void pci_bus_add_resource(struct pci_bus *bus, struct resource *res, unsigned int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/bus.c (ffffffff814e4c80)
Location: drivers/pci/bus.c:48
Inline: False
Direct callers:
  - drivers/pci/probe.c:pci_register_host_bridge
  - drivers/pci/probe.c:pci_read_bridge_bases
  - arch/x86/pci/fixup.c:pci_amd_enable_64bit_bar
```
**Symbols:**

```
ffffffff814e4c80-ffffffff814e4cf4: pci_bus_add_resource (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void pci_bus_add_resource(struct pci_bus *bus, struct resource *res, unsigned int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/bus.c (ffffffff81514160)
Location: drivers/pci/bus.c:47
Inline: False
Direct callers:
  - drivers/pci/probe.c:pci_register_host_bridge
  - drivers/pci/probe.c:pci_read_bridge_bases
  - arch/x86/pci/fixup.c:pci_amd_enable_64bit_bar
```
**Symbols:**

```
ffffffff81514160-ffffffff815141cf: pci_bus_add_resource (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void pci_bus_add_resource(struct pci_bus *bus, struct resource *res, unsigned int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/bus.c (ffffffff815298c0)
Location: drivers/pci/bus.c:47
Inline: False
Direct callers:
  - drivers/pci/probe.c:pci_register_host_bridge
  - drivers/pci/probe.c:pci_read_bridge_bases
  - arch/x86/pci/fixup.c:pci_amd_enable_64bit_bar
```
**Symbols:**

```
ffffffff815298c0-ffffffff8152992f: pci_bus_add_resource (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
void pci_bus_add_resource(struct pci_bus *bus, struct resource *res, unsigned int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pci/bus.c (0)
Location: drivers/pci/bus.c:47
Inline: False
Direct callers:
  - drivers/pci/probe.c:pci_register_host_bridge
  - drivers/pci/probe.c:pci_read_bridge_bases
  - arch/x86/pci/fixup.c:pci_amd_enable_64bit_bar
```
**Symbols:**

```
ffffffff81558e8e-ffffffff81558ea9: pci_bus_add_resource.cold (STB_LOCAL)
ffffffff81558b40-ffffffff81558b9b: pci_bus_add_resource (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
void pci_bus_add_resource(struct pci_bus *bus, struct resource *res, unsigned int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pci/bus.c (0)
Location: drivers/pci/bus.c:47
Inline: False
Direct callers:
  - drivers/pci/probe.c:pci_register_host_bridge
  - drivers/pci/probe.c:pci_read_bridge_bases
  - arch/x86/pci/fixup.c:pci_amd_enable_64bit_bar
```
**Symbols:**

```
ffffffff8157a481-ffffffff8157a49c: pci_bus_add_resource.cold (STB_LOCAL)
ffffffff8157a0d0-ffffffff8157a12b: pci_bus_add_resource (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
void pci_bus_add_resource(struct pci_bus *bus, struct resource *res, unsigned int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pci/bus.c (0)
Location: drivers/pci/bus.c:47
Inline: False
Direct callers:
  - drivers/pci/probe.c:pci_register_host_bridge
  - drivers/pci/probe.c:pci_read_bridge_bases
  - arch/x86/pci/fixup.c:pci_amd_enable_64bit_bar
```
**Symbols:**

```
ffffffff8161f5a5-ffffffff8161f5c0: pci_bus_add_resource.cold (STB_LOCAL)
ffffffff8161f1a0-ffffffff8161f1fb: pci_bus_add_resource (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
void pci_bus_add_resource(struct pci_bus *bus, struct resource *res, unsigned int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pci/bus.c (0)
Location: drivers/pci/bus.c:47
Inline: False
Direct callers:
  - drivers/pci/probe.c:pci_register_host_bridge
  - drivers/pci/probe.c:pci_read_bridge_bases
  - arch/x86/pci/fixup.c:pci_amd_enable_64bit_bar
```
**Symbols:**

```
ffffffff81bf6ea2-ffffffff81bf6ebd: pci_bus_add_resource.cold (STB_LOCAL)
ffffffff81645990-ffffffff816459eb: pci_bus_add_resource (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
void pci_bus_add_resource(struct pci_bus *bus, struct resource *res, unsigned int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pci/bus.c (0)
Location: drivers/pci/bus.c:47
Inline: False
Direct callers:
  - drivers/pci/probe.c:pci_register_host_bridge
  - drivers/pci/probe.c:pci_read_bridge_bases
  - arch/x86/pci/fixup.c:pci_amd_enable_64bit_bar
```
**Symbols:**

```
ffffffff81be8d11-ffffffff81be8d2c: pci_bus_add_resource.cold (STB_LOCAL)
ffffffff816286d0-ffffffff8162872b: pci_bus_add_resource (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
void pci_bus_add_resource(struct pci_bus *bus, struct resource *res, unsigned int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pci/bus.c (0)
Location: drivers/pci/bus.c:47
Inline: False
Direct callers:
  - drivers/pci/probe.c:pci_register_host_bridge
  - drivers/pci/probe.c:pci_read_bridge_bases
  - arch/x86/pci/fixup.c:pci_amd_enable_64bit_bar
```
**Symbols:**

```
ffffffff81ce310c-ffffffff81ce3127: pci_bus_add_resource.cold (STB_LOCAL)
ffffffff81698020-ffffffff8169807b: pci_bus_add_resource (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
void pci_bus_add_resource(struct pci_bus *bus, struct resource *res, unsigned int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pci/bus.c (0)
Location: drivers/pci/bus.c:47
Inline: False
Direct callers:
  - drivers/pci/probe.c:pci_register_host_bridge
  - drivers/pci/probe.c:pci_read_bridge_bases
  - arch/x86/pci/fixup.c:pci_amd_enable_64bit_bar
```
**Symbols:**

```
ffffffff81ea9c00-ffffffff81ea9c1b: pci_bus_add_resource.cold (STB_LOCAL)
ffffffff817b92d0-ffffffff817b9337: pci_bus_add_resource (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void pci_bus_add_resource(struct pci_bus *bus, struct resource *res, unsigned int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/bus.c (ffffffff818d3e20)
Location: drivers/pci/bus.c:47
Inline: False
Direct callers:
  - drivers/pci/probe.c:pci_register_host_bridge
  - drivers/pci/probe.c:pci_read_bridge_bases
  - arch/x86/pci/fixup.c:pci_amd_enable_64bit_bar
```
**Symbols:**

```
ffffffff818d3e20-ffffffff818d3e9b: pci_bus_add_resource (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void pci_bus_add_resource(struct pci_bus *bus, struct resource *res, unsigned int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/bus.c (ffffffff81916f50)
Location: drivers/pci/bus.c:48
Inline: False
Direct callers:
  - drivers/pci/probe.c:pci_register_host_bridge
  - drivers/pci/probe.c:pci_read_bridge_bases
  - arch/x86/pci/fixup.c:pci_amd_enable_64bit_bar
```
**Symbols:**

```
ffffffff81916f50-ffffffff81916fcb: pci_bus_add_resource (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void pci_bus_add_resource(struct pci_bus *bus, struct resource *res, unsigned int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/bus.c (ffffffff8195f020)
Location: drivers/pci/bus.c:48
Inline: False
Direct callers:
  - drivers/pci/probe.c:pci_register_host_bridge
  - drivers/pci/probe.c:pci_read_bridge_bases
  - arch/x86/pci/fixup.c:pci_amd_enable_64bit_bar
```
**Symbols:**

```
ffffffff8195f020-ffffffff8195f0ca: pci_bus_add_resource (STB_GLOBAL)
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
void pci_bus_add_resource(struct pci_bus *bus, struct resource *res, unsigned int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/bus.c (ffff8000106dc9a8)
Location: drivers/pci/bus.c:47
Inline: False
Direct callers:
  - drivers/pci/probe.c:pci_register_host_bridge
  - drivers/pci/probe.c:pci_read_bridge_bases
```
**Symbols:**

```
ffff8000106dc9a8-ffff8000106dca28: pci_bus_add_resource (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void pci_bus_add_resource(struct pci_bus *bus, struct resource *res, unsigned int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/bus.c (c08785cc)
Location: drivers/pci/bus.c:47
Inline: False
Direct callers:
  - drivers/pci/probe.c:pci_register_host_bridge
  - drivers/pci/probe.c:pci_read_bridge_bases
```
**Symbols:**

```
c08785cc-c0878640: pci_bus_add_resource (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void pci_bus_add_resource(struct pci_bus *bus, struct resource *res, unsigned int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/bus.c (c0000000008549c0)
Location: drivers/pci/bus.c:47
Inline: False
Direct callers:
  - drivers/pci/probe.c:pci_register_host_bridge
  - drivers/pci/probe.c:pci_read_bridge_bases
```
**Symbols:**

```
c0000000008549c0-c000000000854a70: pci_bus_add_resource (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void pci_bus_add_resource(struct pci_bus *bus, struct resource *res, unsigned int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/bus.c (ffffffe0004b4e66)
Location: drivers/pci/bus.c:47
Inline: False
Direct callers:
  - drivers/pci/probe.c:pci_register_host_bridge
  - drivers/pci/probe.c:pci_read_bridge_bases
```
**Symbols:**

```
ffffffe0004b4e66-ffffffe0004b4edc: pci_bus_add_resource (STB_GLOBAL)
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
void pci_bus_add_resource(struct pci_bus *bus, struct resource *res, unsigned int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pci/bus.c (0)
Location: drivers/pci/bus.c:47
Inline: False
Direct callers:
  - drivers/pci/probe.c:pci_register_host_bridge
  - drivers/pci/probe.c:pci_read_bridge_bases
  - arch/x86/pci/fixup.c:pci_amd_enable_64bit_bar
```
**Symbols:**

```
ffffffff8156e991-ffffffff8156e9ac: pci_bus_add_resource.cold (STB_LOCAL)
ffffffff8156e5f0-ffffffff8156e64b: pci_bus_add_resource (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Transformation ⚠️</summary>

```c
void pci_bus_add_resource(struct pci_bus *bus, struct resource *res, unsigned int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pci/bus.c (0)
Location: drivers/pci/bus.c:47
Inline: False
Direct callers:
  - drivers/pci/probe.c:pci_register_host_bridge
  - drivers/pci/probe.c:pci_read_bridge_bases
  - arch/x86/pci/fixup.c:pci_amd_enable_64bit_bar
```
**Symbols:**

```
ffffffff8155d101-ffffffff8155d11c: pci_bus_add_resource.cold (STB_LOCAL)
ffffffff8155cd50-ffffffff8155cdab: pci_bus_add_resource (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Transformation ⚠️</summary>

```c
void pci_bus_add_resource(struct pci_bus *bus, struct resource *res, unsigned int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pci/bus.c (0)
Location: drivers/pci/bus.c:47
Inline: False
Direct callers:
  - drivers/pci/probe.c:pci_register_host_bridge
  - drivers/pci/probe.c:pci_read_bridge_bases
  - arch/x86/pci/fixup.c:pci_amd_enable_64bit_bar
```
**Symbols:**

```
ffffffff8156e1d1-ffffffff8156e1ec: pci_bus_add_resource.cold (STB_LOCAL)
ffffffff8156de20-ffffffff8156de7b: pci_bus_add_resource (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
void pci_bus_add_resource(struct pci_bus *bus, struct resource *res, unsigned int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pci/bus.c (0)
Location: drivers/pci/bus.c:47
Inline: False
Direct callers:
  - drivers/pci/probe.c:pci_register_host_bridge
  - drivers/pci/probe.c:pci_read_bridge_bases
  - arch/x86/pci/fixup.c:pci_amd_enable_64bit_bar
```
**Symbols:**

```
ffffffff815886b1-ffffffff815886cc: pci_bus_add_resource.cold (STB_LOCAL)
ffffffff81588300-ffffffff8158835b: pci_bus_add_resource (STB_GLOBAL)
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
