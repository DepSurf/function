# Function: <code>pcibios_add_bus</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void pcibios_add_bus(struct pci_bus *bus);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/pci/common.c (ffffffff816fa5e0)
Location: arch/x86/pci/common.c:174
Inline: False
```
**Symbols:**

```
ffffffff816fa5e0-ffffffff816fa5f0: pcibios_add_bus (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void pcibios_add_bus(struct pci_bus *bus);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/probe.c (ffffffff8175f3f0)
Location: drivers/pci/probe.c:2121
Inline: False
Direct callers:
  - drivers/pci/probe.c:pci_create_root_bus
  - drivers/pci/probe.c:pci_create_root_bus
  - drivers/pci/probe.c:pci_add_new_bus
```
**Symbols:**

```
ffffffff8175f3f0-ffffffff8175f400: pcibios_add_bus (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void pcibios_add_bus(struct pci_bus *bus);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/probe.c (ffffffff8178b920)
Location: drivers/pci/probe.c:2271
Inline: False
Direct callers:
  - drivers/pci/probe.c:pci_add_new_bus
  - drivers/pci/probe.c:pci_register_host_bridge
```
**Symbols:**

```
ffffffff8178b920-ffffffff8178b930: pcibios_add_bus (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
void pcibios_add_bus(struct pci_bus *bus);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/probe.c (ffffffff814a8510)
Location: drivers/pci/probe.c:2397
Inline: True
Direct callers:
  - drivers/pci/probe.c:pci_add_new_bus
  - drivers/pci/probe.c:pci_register_host_bridge
```
**Symbols:**

```
ffffffff817aa890-ffffffff817aa8a0: pcibios_add_bus (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
void pcibios_add_bus(struct pci_bus *bus);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/probe.c (ffffffff814e7540)
Location: drivers/pci/probe.c:2624
Inline: True
Direct callers:
  - drivers/pci/probe.c:pci_add_new_bus
  - drivers/pci/probe.c:pci_register_host_bridge
```
**Symbols:**

```
ffffffff81821d60-ffffffff81821d70: pcibios_add_bus (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
void pcibios_add_bus(struct pci_bus *bus);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/probe.c (ffffffff81516b80)
Location: drivers/pci/probe.c:2808
Inline: True
Direct callers:
  - drivers/pci/probe.c:pci_add_new_bus
  - drivers/pci/probe.c:pci_register_host_bridge
```
**Symbols:**

```
ffffffff8186c030-ffffffff8186c040: pcibios_add_bus (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
void pcibios_add_bus(struct pci_bus *bus);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/probe.c (ffffffff8152c5e0)
Location: drivers/pci/probe.c:2934
Inline: True
Direct callers:
  - drivers/pci/probe.c:pci_add_new_bus
  - drivers/pci/probe.c:pci_register_host_bridge
```
**Symbols:**

```
ffffffff8188c110-ffffffff8188c120: pcibios_add_bus (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void pcibios_add_bus(struct pci_bus *bus);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/probe.c (ffffffff8155af80)
Location: drivers/pci/probe.c:3160
Inline: False
Direct callers:
  - drivers/pci/probe.c:pci_add_new_bus
  - drivers/pci/probe.c:pci_register_host_bridge
```
**Symbols:**

```
ffffffff818d6a60-ffffffff818d6a70: pcibios_add_bus (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void pcibios_add_bus(struct pci_bus *bus);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/probe.c (ffffffff8157c030)
Location: drivers/pci/probe.c:2894
Inline: False
Direct callers:
  - drivers/pci/probe.c:pci_add_new_bus
  - drivers/pci/probe.c:pci_register_host_bridge
```
**Symbols:**

```
ffffffff81908de0-ffffffff81908df0: pcibios_add_bus (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
void pcibios_add_bus(struct pci_bus *bus);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/probe.c (ffffffff81621720)
Location: drivers/pci/probe.c:2946
Inline: True
Direct callers:
  - drivers/pci/probe.c:pci_alloc_child_bus
  - drivers/pci/probe.c:pci_register_host_bridge
```
**Symbols:**

```
ffffffff81bb96f0-ffffffff81bb9700: pcibios_add_bus (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
void pcibios_add_bus(struct pci_bus *bus);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/probe.c (ffffffff816482b0)
Location: drivers/pci/probe.c:2953
Inline: True
Direct callers:
  - drivers/pci/probe.c:pci_alloc_child_bus
  - drivers/pci/probe.c:pci_register_host_bridge
```
**Symbols:**

```
ffffffff81bcdfe0-ffffffff81bcdff0: pcibios_add_bus (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
void pcibios_add_bus(struct pci_bus *bus);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/probe.c (ffffffff8162aed0)
Location: drivers/pci/probe.c:2997
Inline: True
Direct callers:
  - drivers/pci/probe.c:pci_alloc_child_bus
  - drivers/pci/probe.c:pci_register_host_bridge
```
**Symbols:**

```
ffffffff81bc19a0-ffffffff81bc19b0: pcibios_add_bus (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
void pcibios_add_bus(struct pci_bus *bus);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/probe.c (ffffffff8169a3a0)
Location: drivers/pci/probe.c:3039
Inline: True
Direct callers:
  - drivers/pci/probe.c:pci_alloc_child_bus
  - drivers/pci/probe.c:pci_register_host_bridge
```
**Symbols:**

```
ffffffff81c91fb0-ffffffff81c91fc0: pcibios_add_bus (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
void pcibios_add_bus(struct pci_bus *bus);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/probe.c (ffffffff817bbb00)
Location: drivers/pci/probe.c:3010
Inline: True
Direct callers:
  - drivers/pci/probe.c:pci_alloc_child_bus
  - drivers/pci/probe.c:pci_register_host_bridge
```
**Symbols:**

```
ffffffff81e415c0-ffffffff81e415d6: pcibios_add_bus (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
void pcibios_add_bus(struct pci_bus *bus);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/probe.c (ffffffff818d7650)
Location: drivers/pci/probe.c:3020
Inline: True
Direct callers:
  - drivers/pci/probe.c:pci_alloc_child_bus
  - drivers/pci/probe.c:pci_register_host_bridge
```
**Symbols:**

```
ffffffff8201bba0-ffffffff8201bbb6: pcibios_add_bus (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
void pcibios_add_bus(struct pci_bus *bus);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/probe.c (ffffffff8191a8e0)
Location: drivers/pci/probe.c:3034
Inline: True
Direct callers:
  - drivers/pci/probe.c:pci_alloc_child_bus
  - drivers/pci/probe.c:pci_register_host_bridge
```
**Symbols:**

```
ffffffff8209c240-ffffffff8209c256: pcibios_add_bus (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
void pcibios_add_bus(struct pci_bus *bus);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/probe.c (ffffffff81962ce0)
Location: drivers/pci/probe.c:3083
Inline: True
Direct callers:
  - drivers/pci/probe.c:pci_alloc_child_bus
  - drivers/pci/probe.c:pci_register_host_bridge
```
**Symbols:**

```
ffffffff821739f0-ffffffff82173a06: pcibios_add_bus (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Selective Inline ⚠️</summary>

```c
void pcibios_add_bus(struct pci_bus *bus);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/arm64/kernel/pci.c (ffff8000100a7ec0)
Location: arch/arm64/kernel/pci.c:210
Inline: True
Direct callers:
  - drivers/pci/probe.c:pci_add_new_bus
  - drivers/pci/probe.c:pci_register_host_bridge
```
**Symbols:**

```
ffff8000100a7ec0-ffff8000100a7eec: pcibios_add_bus (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
void pcibios_add_bus(struct pci_bus *bus);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/probe.c (c087b2e8)
Location: drivers/pci/probe.c:2894
Inline: True
Direct callers:
  - drivers/pci/probe.c:pci_add_new_bus
  - drivers/pci/probe.c:pci_register_host_bridge
```
**Symbols:**

```
c087b2e8-c087b300: pcibios_add_bus (STB_WEAK)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void pcibios_add_bus(struct pci_bus *bus);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/probe.c (c0000000008580c0)
Location: drivers/pci/probe.c:2894
Inline: False
Direct callers:
  - drivers/pci/probe.c:pci_add_new_bus
  - drivers/pci/probe.c:pci_register_host_bridge
```
**Symbols:**

```
c0000000008580c0-c0000000008580cc: pcibios_add_bus (STB_WEAK)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
void pcibios_add_bus(struct pci_bus *bus);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/probe.c (ffffffe0004b765c)
Location: drivers/pci/probe.c:2894
Inline: True
Direct callers:
  - drivers/pci/probe.c:pci_add_new_bus
  - drivers/pci/probe.c:pci_register_host_bridge
```
**Symbols:**

```
ffffffe0004b765c-ffffffe0004b7676: pcibios_add_bus (STB_WEAK)
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
void pcibios_add_bus(struct pci_bus *bus);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/probe.c (ffffffff81570550)
Location: drivers/pci/probe.c:2894
Inline: False
Direct callers:
  - drivers/pci/probe.c:pci_add_new_bus
  - drivers/pci/probe.c:pci_register_host_bridge
```
**Symbols:**

```
ffffffff818a81a0-ffffffff818a81b0: pcibios_add_bus (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void pcibios_add_bus(struct pci_bus *bus);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/probe.c (ffffffff8155ecb0)
Location: drivers/pci/probe.c:2894
Inline: False
Direct callers:
  - drivers/pci/probe.c:pci_add_new_bus
  - drivers/pci/probe.c:pci_register_host_bridge
```
**Symbols:**

```
ffffffff81862c20-ffffffff81862c30: pcibios_add_bus (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void pcibios_add_bus(struct pci_bus *bus);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/probe.c (ffffffff8156fd80)
Location: drivers/pci/probe.c:2894
Inline: False
Direct callers:
  - drivers/pci/probe.c:pci_add_new_bus
  - drivers/pci/probe.c:pci_register_host_bridge
```
**Symbols:**

```
ffffffff818f9800-ffffffff818f9810: pcibios_add_bus (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void pcibios_add_bus(struct pci_bus *bus);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/probe.c (ffffffff8158a260)
Location: drivers/pci/probe.c:2894
Inline: False
Direct callers:
  - drivers/pci/probe.c:pci_add_new_bus
  - drivers/pci/probe.c:pci_register_host_bridge
```
**Symbols:**

```
ffffffff8191a960-ffffffff8191a970: pcibios_add_bus (STB_GLOBAL)
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
