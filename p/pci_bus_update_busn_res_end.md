# Function: <code>pci_bus_update_busn_res_end</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int pci_bus_update_busn_res_end(struct pci_bus *b, int bus_max);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/probe.c (ffffffff814322f0)
Location: drivers/pci/probe.c:2225
Inline: False
Direct callers:
  - drivers/pci/probe.c:pci_scan_bridge
  - drivers/pci/probe.c:pci_scan_bridge
  - drivers/pci/probe.c:pci_scan_root_bus_msi
```
**Symbols:**

```
ffffffff814322f0-ffffffff8143241e: pci_bus_update_busn_res_end (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int pci_bus_update_busn_res_end(struct pci_bus *b, int bus_max);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/probe.c (ffffffff8147db00)
Location: drivers/pci/probe.c:2265
Inline: False
Direct callers:
  - drivers/pci/probe.c:pci_scan_root_bus_msi
  - drivers/pci/probe.c:pci_scan_bridge
  - drivers/pci/probe.c:pci_scan_bridge
```
**Symbols:**

```
ffffffff8147db00-ffffffff8147dc36: pci_bus_update_busn_res_end (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int pci_bus_update_busn_res_end(struct pci_bus *b, int bus_max);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/probe.c (ffffffff8149f1c0)
Location: drivers/pci/probe.c:2345
Inline: False
Direct callers:
  - drivers/pci/probe.c:pci_scan_root_bus_msi
  - drivers/pci/probe.c:pci_scan_bridge
  - drivers/pci/probe.c:pci_scan_bridge
```
**Symbols:**

```
ffffffff8149f1c0-ffffffff8149f2f6: pci_bus_update_busn_res_end (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int pci_bus_update_busn_res_end(struct pci_bus *b, int bus_max);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/probe.c (ffffffff814a8fd0)
Location: drivers/pci/probe.c:2461
Inline: False
Direct callers:
  - drivers/pci/probe.c:pci_scan_root_bus
  - drivers/pci/probe.c:pci_scan_root_bus_bridge
  - drivers/pci/probe.c:pci_scan_bridge
  - drivers/pci/probe.c:pci_scan_bridge
```
**Symbols:**

```
ffffffff814a8fd0-ffffffff814a9105: pci_bus_update_busn_res_end (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int pci_bus_update_busn_res_end(struct pci_bus *b, int bus_max);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/probe.c (ffffffff814e8000)
Location: drivers/pci/probe.c:2688
Inline: False
Direct callers:
  - drivers/pci/probe.c:pci_scan_root_bus
  - drivers/pci/probe.c:pci_scan_root_bus_bridge
  - drivers/pci/probe.c:pci_scan_bridge_extend
  - drivers/pci/probe.c:pci_scan_bridge_extend
```
**Symbols:**

```
ffffffff814e8000-ffffffff814e8135: pci_bus_update_busn_res_end (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int pci_bus_update_busn_res_end(struct pci_bus *b, int bus_max);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/probe.c (ffffffff81517660)
Location: drivers/pci/probe.c:2905
Inline: False
Direct callers:
  - drivers/pci/probe.c:pci_scan_root_bus
  - drivers/pci/probe.c:pci_scan_root_bus_bridge
  - drivers/pci/probe.c:pci_scan_bridge_extend
  - drivers/pci/probe.c:pci_scan_bridge_extend
```
**Symbols:**

```
ffffffff81517660-ffffffff81517797: pci_bus_update_busn_res_end (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int pci_bus_update_busn_res_end(struct pci_bus *b, int bus_max);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/probe.c (ffffffff8152d0e0)
Location: drivers/pci/probe.c:3031
Inline: False
Direct callers:
  - drivers/pci/probe.c:pci_scan_root_bus
  - drivers/pci/probe.c:pci_scan_root_bus_bridge
  - drivers/pci/probe.c:pci_scan_bridge_extend
  - drivers/pci/probe.c:pci_scan_bridge_extend
```
**Symbols:**

```
ffffffff8152d0e0-ffffffff8152d217: pci_bus_update_busn_res_end (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
int pci_bus_update_busn_res_end(struct pci_bus *b, int bus_max);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pci/probe.c (0)
Location: drivers/pci/probe.c:3257
Inline: False
Direct callers:
  - drivers/pci/probe.c:pci_scan_root_bus
  - drivers/pci/probe.c:pci_scan_root_bus_bridge
  - drivers/pci/probe.c:pci_scan_bridge_extend
  - drivers/pci/probe.c:pci_scan_bridge_extend
  - drivers/pci/probe.c:pci_scan_bridge_extend
  - drivers/pci/probe.c:pci_scan_bridge_extend
```
**Symbols:**

```
ffffffff8155d65d-ffffffff8155d6c2: pci_bus_update_busn_res_end.cold (STB_LOCAL)
ffffffff8155b890-ffffffff8155b96c: pci_bus_update_busn_res_end (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
int pci_bus_update_busn_res_end(struct pci_bus *b, int bus_max);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pci/probe.c (0)
Location: drivers/pci/probe.c:2991
Inline: False
Direct callers:
  - drivers/pci/probe.c:pci_scan_root_bus
  - drivers/pci/probe.c:pci_scan_root_bus_bridge
  - drivers/pci/probe.c:pci_scan_bridge_extend
  - drivers/pci/probe.c:pci_scan_bridge_extend
  - drivers/pci/probe.c:pci_scan_bridge_extend
  - drivers/pci/probe.c:pci_scan_bridge_extend
```
**Symbols:**

```
ffffffff8157e6d1-ffffffff8157e736: pci_bus_update_busn_res_end.cold (STB_LOCAL)
ffffffff8157c940-ffffffff8157ca1c: pci_bus_update_busn_res_end (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
int pci_bus_update_busn_res_end(struct pci_bus *b, int bus_max);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pci/probe.c (0)
Location: drivers/pci/probe.c:3043
Inline: False
Direct callers:
  - drivers/pci/probe.c:pci_scan_root_bus
  - drivers/pci/probe.c:pci_scan_root_bus_bridge
  - drivers/pci/probe.c:pci_scan_bridge_extend
  - drivers/pci/probe.c:pci_scan_bridge_extend
  - drivers/pci/probe.c:pci_scan_bridge_extend
  - drivers/pci/probe.c:pci_scan_bridge_extend
```
**Symbols:**

```
ffffffff81623be8-ffffffff81623c4d: pci_bus_update_busn_res_end.cold (STB_LOCAL)
ffffffff81621ed0-ffffffff81621fac: pci_bus_update_busn_res_end (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
int pci_bus_update_busn_res_end(struct pci_bus *b, int bus_max);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pci/probe.c (0)
Location: drivers/pci/probe.c:3050
Inline: False
Direct callers:
  - drivers/pci/probe.c:pci_scan_root_bus
  - drivers/pci/probe.c:pci_scan_root_bus_bridge
  - drivers/pci/probe.c:pci_scan_bridge_extend
  - drivers/pci/probe.c:pci_scan_bridge_extend
  - drivers/pci/probe.c:pci_scan_bridge_extend
  - drivers/pci/probe.c:pci_scan_bridge_extend
```
**Symbols:**

```
ffffffff81bf7900-ffffffff81bf7965: pci_bus_update_busn_res_end.cold (STB_LOCAL)
ffffffff81648ac0-ffffffff81648b9c: pci_bus_update_busn_res_end (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
int pci_bus_update_busn_res_end(struct pci_bus *b, int bus_max);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pci/probe.c (0)
Location: drivers/pci/probe.c:3094
Inline: False
Direct callers:
  - drivers/pci/probe.c:pci_scan_root_bus
  - drivers/pci/probe.c:pci_scan_root_bus_bridge
  - drivers/pci/probe.c:pci_scan_bridge_extend
  - drivers/pci/probe.c:pci_scan_bridge_extend
  - drivers/pci/probe.c:pci_scan_bridge_extend
  - drivers/pci/probe.c:pci_scan_bridge_extend
```
**Symbols:**

```
ffffffff81be97a6-ffffffff81be980b: pci_bus_update_busn_res_end.cold (STB_LOCAL)
ffffffff8162b680-ffffffff8162b75c: pci_bus_update_busn_res_end (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int pci_bus_update_busn_res_end(struct pci_bus *b, int bus_max);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pci/probe.c (0)
Location: drivers/pci/probe.c:3136
Inline: False
Direct callers:
  - drivers/pci/probe.c:pci_scan_root_bus
  - drivers/pci/probe.c:pci_scan_root_bus_bridge
  - drivers/pci/probe.c:pci_scan_bridge_extend
  - drivers/pci/probe.c:pci_scan_bridge_extend
  - drivers/pci/probe.c:pci_scan_bridge_extend
  - drivers/pci/probe.c:pci_scan_bridge_extend
```
**Symbols:**

```
ffffffff81ce414c-ffffffff81ce41b1: pci_bus_update_busn_res_end.cold (STB_LOCAL)
ffffffff8169ab50-ffffffff8169ac2c: pci_bus_update_busn_res_end (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int pci_bus_update_busn_res_end(struct pci_bus *b, int bus_max);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pci/probe.c (0)
Location: drivers/pci/probe.c:3107
Inline: False
Direct callers:
  - drivers/pci/probe.c:pci_scan_root_bus
  - drivers/pci/probe.c:pci_scan_root_bus_bridge
  - drivers/pci/probe.c:pci_scan_bridge_extend
```
**Symbols:**

```
ffffffff81eaab61-ffffffff81eaabc1: pci_bus_update_busn_res_end.cold (STB_LOCAL)
ffffffff817bc2e0-ffffffff817bc3cb: pci_bus_update_busn_res_end (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int pci_bus_update_busn_res_end(struct pci_bus *b, int bus_max);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/probe.c (ffffffff818d8160)
Location: drivers/pci/probe.c:3117
Inline: False
Direct callers:
  - drivers/pci/probe.c:pci_scan_root_bus
  - drivers/pci/probe.c:pci_scan_root_bus_bridge
  - drivers/pci/probe.c:pci_scan_bridge_extend
```
**Symbols:**

```
ffffffff818d8160-ffffffff818d8293: pci_bus_update_busn_res_end (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int pci_bus_update_busn_res_end(struct pci_bus *b, int bus_max);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/probe.c (ffffffff8191b430)
Location: drivers/pci/probe.c:3131
Inline: False
Direct callers:
  - drivers/pci/probe.c:pci_scan_root_bus
  - drivers/pci/probe.c:pci_scan_root_bus_bridge
  - drivers/pci/probe.c:pci_scan_bridge_extend
```
**Symbols:**

```
ffffffff8191b430-ffffffff8191b563: pci_bus_update_busn_res_end (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int pci_bus_update_busn_res_end(struct pci_bus *b, int bus_max);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/probe.c (ffffffff81963860)
Location: drivers/pci/probe.c:3180
Inline: False
Direct callers:
  - drivers/pci/probe.c:pci_scan_root_bus
  - drivers/pci/probe.c:pci_scan_root_bus_bridge
  - drivers/pci/probe.c:pci_scan_bridge_extend
```
**Symbols:**

```
ffffffff81963860-ffffffff81963993: pci_bus_update_busn_res_end (STB_GLOBAL)
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
int pci_bus_update_busn_res_end(struct pci_bus *b, int bus_max);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/probe.c (ffff8000106e0068)
Location: drivers/pci/probe.c:2991
Inline: False
Direct callers:
  - drivers/pci/probe.c:pci_scan_root_bus
  - drivers/pci/probe.c:pci_scan_root_bus_bridge
  - drivers/pci/probe.c:pci_scan_bridge_extend
  - drivers/pci/probe.c:pci_scan_bridge_extend
```
**Symbols:**

```
ffff8000106e0068-ffff8000106e0178: pci_bus_update_busn_res_end (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int pci_bus_update_busn_res_end(struct pci_bus *b, int bus_max);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/probe.c (c087bd1c)
Location: drivers/pci/probe.c:2991
Inline: False
Direct callers:
  - drivers/pci/probe.c:pci_scan_root_bus
  - drivers/pci/probe.c:pci_scan_root_bus_bridge
  - drivers/pci/probe.c:pci_scan_bridge_extend
  - drivers/pci/probe.c:pci_scan_bridge_extend
  - drivers/pci/probe.c:pci_scan_bridge_extend
  - drivers/pci/probe.c:pci_scan_bridge_extend
```
**Symbols:**

```
c087bd1c-c087be20: pci_bus_update_busn_res_end (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int pci_bus_update_busn_res_end(struct pci_bus *b, int bus_max);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/probe.c (c000000000858dd0)
Location: drivers/pci/probe.c:2991
Inline: False
Direct callers:
  - arch/powerpc/kernel/pci-common.c:pcibios_scan_phb
  - arch/powerpc/kernel/pci-common.c:pcibios_scan_phb
  - drivers/pci/probe.c:pci_scan_root_bus
  - drivers/pci/probe.c:pci_scan_root_bus_bridge
  - drivers/pci/probe.c:pci_scan_bridge_extend
  - drivers/pci/probe.c:pci_scan_bridge_extend
  - drivers/pci/probe.c:pci_scan_bridge_extend
```
**Symbols:**

```
c000000000858dd0-c000000000858f30: pci_bus_update_busn_res_end (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int pci_bus_update_busn_res_end(struct pci_bus *b, int bus_max);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/probe.c (ffffffe0004b7f8a)
Location: drivers/pci/probe.c:2991
Inline: False
Direct callers:
  - drivers/pci/probe.c:pci_scan_root_bus
  - drivers/pci/probe.c:pci_scan_root_bus_bridge
  - drivers/pci/probe.c:pci_scan_bridge_extend
  - drivers/pci/probe.c:pci_scan_bridge_extend
  - drivers/pci/probe.c:pci_scan_bridge_extend
  - drivers/pci/probe.c:pci_scan_bridge_extend
```
**Symbols:**

```
ffffffe0004b7f8a-ffffffe0004b8062: pci_bus_update_busn_res_end (STB_GLOBAL)
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
int pci_bus_update_busn_res_end(struct pci_bus *b, int bus_max);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pci/probe.c (0)
Location: drivers/pci/probe.c:2991
Inline: False
Direct callers:
  - drivers/pci/probe.c:pci_scan_root_bus
  - drivers/pci/probe.c:pci_scan_root_bus_bridge
  - drivers/pci/probe.c:pci_scan_bridge_extend
  - drivers/pci/probe.c:pci_scan_bridge_extend
  - drivers/pci/probe.c:pci_scan_bridge_extend
  - drivers/pci/probe.c:pci_scan_bridge_extend
```
**Symbols:**

```
ffffffff81572bf1-ffffffff81572c56: pci_bus_update_busn_res_end.cold (STB_LOCAL)
ffffffff81570e60-ffffffff81570f3c: pci_bus_update_busn_res_end (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Transformation ⚠️</summary>

```c
int pci_bus_update_busn_res_end(struct pci_bus *b, int bus_max);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pci/probe.c (0)
Location: drivers/pci/probe.c:2991
Inline: False
Direct callers:
  - drivers/pci/probe.c:pci_scan_root_bus
  - drivers/pci/probe.c:pci_scan_root_bus_bridge
  - drivers/pci/probe.c:pci_scan_bridge_extend
  - drivers/pci/probe.c:pci_scan_bridge_extend
  - drivers/pci/probe.c:pci_scan_bridge_extend
  - drivers/pci/probe.c:pci_scan_bridge_extend
```
**Symbols:**

```
ffffffff81561351-ffffffff815613b6: pci_bus_update_busn_res_end.cold (STB_LOCAL)
ffffffff8155f5c0-ffffffff8155f69c: pci_bus_update_busn_res_end (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Transformation ⚠️</summary>

```c
int pci_bus_update_busn_res_end(struct pci_bus *b, int bus_max);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pci/probe.c (0)
Location: drivers/pci/probe.c:2991
Inline: False
Direct callers:
  - drivers/pci/probe.c:pci_scan_root_bus
  - drivers/pci/probe.c:pci_scan_root_bus_bridge
  - drivers/pci/probe.c:pci_scan_bridge_extend
  - drivers/pci/probe.c:pci_scan_bridge_extend
  - drivers/pci/probe.c:pci_scan_bridge_extend
  - drivers/pci/probe.c:pci_scan_bridge_extend
```
**Symbols:**

```
ffffffff81572421-ffffffff81572486: pci_bus_update_busn_res_end.cold (STB_LOCAL)
ffffffff81570690-ffffffff8157076c: pci_bus_update_busn_res_end (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
int pci_bus_update_busn_res_end(struct pci_bus *b, int bus_max);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pci/probe.c (0)
Location: drivers/pci/probe.c:2991
Inline: False
Direct callers:
  - drivers/pci/probe.c:pci_scan_root_bus
  - drivers/pci/probe.c:pci_scan_root_bus_bridge
  - drivers/pci/probe.c:pci_scan_bridge_extend
  - drivers/pci/probe.c:pci_scan_bridge_extend
  - drivers/pci/probe.c:pci_scan_bridge_extend
  - drivers/pci/probe.c:pci_scan_bridge_extend
```
**Symbols:**

```
ffffffff8158c901-ffffffff8158c966: pci_bus_update_busn_res_end.cold (STB_LOCAL)
ffffffff8158ab70-ffffffff8158ac4c: pci_bus_update_busn_res_end (STB_GLOBAL)
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
