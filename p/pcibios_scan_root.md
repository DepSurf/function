# Function: <code>pcibios_scan_root</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void pcibios_scan_root(int busnum);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/pci/common.c (ffffffff816fa600)
Location: arch/x86/pci/common.c:475
Inline: False
Direct callers:
  - arch/x86/pci/fixup.c:pci_fixup_i450nx
  - arch/x86/pci/fixup.c:pci_fixup_i450nx
  - arch/x86/pci/fixup.c:pci_fixup_i450gx
  - arch/x86/pci/legacy.c:pcibios_scan_specific_bus
  - arch/x86/pci/legacy.c:pci_legacy_init
  - arch/x86/pci/irq.c:pirq_peer_trick
```
**Symbols:**

```
ffffffff816fa600-ffffffff816fa6da: pcibios_scan_root (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void pcibios_scan_root(int busnum);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/pci/common.c (ffffffff8175f410)
Location: arch/x86/pci/common.c:474
Inline: False
Direct callers:
  - arch/x86/pci/fixup.c:pci_fixup_i450gx
  - arch/x86/pci/fixup.c:pci_fixup_i450nx
  - arch/x86/pci/fixup.c:pci_fixup_i450nx
  - arch/x86/pci/legacy.c:pcibios_scan_specific_bus
  - arch/x86/pci/legacy.c:pci_legacy_init
  - arch/x86/pci/irq.c:pirq_peer_trick
```
**Symbols:**

```
ffffffff8175f410-ffffffff8175f4ea: pcibios_scan_root (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void pcibios_scan_root(int busnum);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/pci/common.c (ffffffff8178b940)
Location: arch/x86/pci/common.c:474
Inline: False
Direct callers:
  - arch/x86/pci/fixup.c:pci_fixup_i450gx
  - arch/x86/pci/fixup.c:pci_fixup_i450nx
  - arch/x86/pci/fixup.c:pci_fixup_i450nx
  - arch/x86/pci/legacy.c:pcibios_scan_specific_bus
  - arch/x86/pci/legacy.c:pci_legacy_init
  - arch/x86/pci/irq.c:pirq_peer_trick
```
**Symbols:**

```
ffffffff8178b940-ffffffff8178ba1a: pcibios_scan_root (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void pcibios_scan_root(int busnum);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/pci/common.c (ffffffff817aa8b0)
Location: arch/x86/pci/common.c:457
Inline: False
Direct callers:
  - arch/x86/pci/fixup.c:pci_fixup_i450gx
  - arch/x86/pci/fixup.c:pci_fixup_i450nx
  - arch/x86/pci/fixup.c:pci_fixup_i450nx
  - arch/x86/pci/legacy.c:pcibios_scan_specific_bus
  - arch/x86/pci/irq.c:pirq_peer_trick
```
**Symbols:**

```
ffffffff817aa8b0-ffffffff817aa98a: pcibios_scan_root (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void pcibios_scan_root(int busnum);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/pci/common.c (ffffffff81821d80)
Location: arch/x86/pci/common.c:457
Inline: False
Direct callers:
  - arch/x86/pci/fixup.c:pci_fixup_i450gx
  - arch/x86/pci/fixup.c:pci_fixup_i450nx
  - arch/x86/pci/fixup.c:pci_fixup_i450nx
  - arch/x86/pci/legacy.c:pcibios_scan_specific_bus
  - arch/x86/pci/irq.c:pirq_peer_trick
```
**Symbols:**

```
ffffffff81821d80-ffffffff81821e5a: pcibios_scan_root (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Transformation ⚠️</summary>

```c
void pcibios_scan_root(int busnum);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/pci/common.c (0)
Location: arch/x86/pci/common.c:457
Inline: False
Direct callers:
  - arch/x86/pci/fixup.c:pci_fixup_i450gx
  - arch/x86/pci/fixup.c:pci_fixup_i450nx
  - arch/x86/pci/fixup.c:pci_fixup_i450nx
  - arch/x86/pci/legacy.c:pcibios_scan_specific_bus
  - arch/x86/pci/legacy.c:pci_legacy_init
  - arch/x86/pci/irq.c:pirq_peer_trick
```
**Symbols:**

```
ffffffff8186c358-ffffffff8186c36c: pcibios_scan_root.cold.10 (STB_LOCAL)
ffffffff8186c050-ffffffff8186c11d: pcibios_scan_root (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Transformation ⚠️</summary>

```c
void pcibios_scan_root(int busnum);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/pci/common.c (0)
Location: arch/x86/pci/common.c:457
Inline: False
Direct callers:
  - arch/x86/pci/fixup.c:pci_fixup_i450gx
  - arch/x86/pci/fixup.c:pci_fixup_i450nx
  - arch/x86/pci/fixup.c:pci_fixup_i450nx
  - arch/x86/pci/legacy.c:pcibios_scan_specific_bus
  - arch/x86/pci/legacy.c:pci_legacy_init
  - arch/x86/pci/irq.c:pirq_peer_trick
```
**Symbols:**

```
ffffffff8188c438-ffffffff8188c44c: pcibios_scan_root.cold.9 (STB_LOCAL)
ffffffff8188c130-ffffffff8188c1fd: pcibios_scan_root (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
void pcibios_scan_root(int busnum);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/pci/common.c (0)
Location: arch/x86/pci/common.c:458
Inline: False
Direct callers:
  - arch/x86/pci/fixup.c:pci_fixup_i450gx
  - arch/x86/pci/fixup.c:pci_fixup_i450nx
  - arch/x86/pci/fixup.c:pci_fixup_i450nx
  - arch/x86/pci/legacy.c:pcibios_scan_specific_bus
  - arch/x86/pci/legacy.c:pci_legacy_init
  - arch/x86/pci/irq.c:pirq_peer_trick
```
**Symbols:**

```
ffffffff818d6d78-ffffffff818d6d8c: pcibios_scan_root.cold (STB_LOCAL)
ffffffff818d6a80-ffffffff818d6b4e: pcibios_scan_root (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
void pcibios_scan_root(int busnum);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/pci/common.c (0)
Location: arch/x86/pci/common.c:458
Inline: False
Direct callers:
  - arch/x86/pci/fixup.c:pci_fixup_i450gx
  - arch/x86/pci/fixup.c:pci_fixup_i450nx
  - arch/x86/pci/fixup.c:pci_fixup_i450nx
  - arch/x86/pci/legacy.c:pcibios_scan_specific_bus
  - arch/x86/pci/legacy.c:pci_legacy_init
  - arch/x86/pci/irq.c:pirq_peer_trick
```
**Symbols:**

```
ffffffff819090f8-ffffffff8190910c: pcibios_scan_root.cold (STB_LOCAL)
ffffffff81908e00-ffffffff81908ece: pcibios_scan_root (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
void pcibios_scan_root(int busnum);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/pci/common.c (0)
Location: arch/x86/pci/common.c:458
Inline: False
Direct callers:
  - arch/x86/pci/fixup.c:pci_fixup_i450gx
  - arch/x86/pci/fixup.c:pci_fixup_i450nx
  - arch/x86/pci/fixup.c:pci_fixup_i450nx
  - arch/x86/pci/legacy.c:pcibios_scan_specific_bus
  - arch/x86/pci/legacy.c:pci_legacy_init
  - arch/x86/pci/irq.c:pirq_peer_trick
```
**Symbols:**

```
ffffffff81bb99e1-ffffffff81bb99f5: pcibios_scan_root.cold (STB_LOCAL)
ffffffff81bb9710-ffffffff81bb97de: pcibios_scan_root (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
void pcibios_scan_root(int busnum);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/pci/common.c (0)
Location: arch/x86/pci/common.c:459
Inline: False
Direct callers:
  - arch/x86/pci/fixup.c:pci_fixup_i450gx
  - arch/x86/pci/fixup.c:pci_fixup_i450nx
  - arch/x86/pci/fixup.c:pci_fixup_i450nx
  - arch/x86/pci/legacy.c:pcibios_scan_specific_bus
  - arch/x86/pci/legacy.c:pci_legacy_init
  - arch/x86/pci/irq.c:pirq_peer_trick
```
**Symbols:**

```
ffffffff81c34a5d-ffffffff81c34a71: pcibios_scan_root.cold (STB_LOCAL)
ffffffff81bce000-ffffffff81bce0ce: pcibios_scan_root (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
void pcibios_scan_root(int busnum);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/pci/common.c (0)
Location: arch/x86/pci/common.c:459
Inline: False
Direct callers:
  - arch/x86/pci/fixup.c:pci_fixup_i450gx
  - arch/x86/pci/fixup.c:pci_fixup_i450nx
  - arch/x86/pci/fixup.c:pci_fixup_i450nx
  - arch/x86/pci/legacy.c:pcibios_scan_specific_bus
  - arch/x86/pci/legacy.c:pci_legacy_init
  - arch/x86/pci/irq.c:pirq_peer_trick
```
**Symbols:**

```
ffffffff81c26e45-ffffffff81c26e59: pcibios_scan_root.cold (STB_LOCAL)
ffffffff81bc19c0-ffffffff81bc1a8e: pcibios_scan_root (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
void pcibios_scan_root(int busnum);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/pci/common.c (0)
Location: arch/x86/pci/common.c:459
Inline: False
Direct callers:
  - arch/x86/pci/fixup.c:pci_fixup_i450gx
  - arch/x86/pci/fixup.c:pci_fixup_i450nx
  - arch/x86/pci/fixup.c:pci_fixup_i450nx
  - arch/x86/pci/legacy.c:pcibios_scan_specific_bus
  - arch/x86/pci/legacy.c:pci_legacy_init
  - arch/x86/pci/irq.c:pirq_peer_trick
```
**Symbols:**

```
ffffffff81d44dd0-ffffffff81d44de4: pcibios_scan_root.cold (STB_LOCAL)
ffffffff81c91fd0-ffffffff81c9209e: pcibios_scan_root (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
void pcibios_scan_root(int busnum);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/pci/common.c (0)
Location: arch/x86/pci/common.c:459
Inline: False
Direct callers:
  - arch/x86/pci/fixup.c:pci_fixup_i450gx
  - arch/x86/pci/fixup.c:pci_fixup_i450nx
  - arch/x86/pci/fixup.c:pci_fixup_i450nx
  - arch/x86/pci/legacy.c:pcibios_scan_specific_bus
  - arch/x86/pci/legacy.c:pci_legacy_init
  - arch/x86/pci/irq.c:pirq_peer_trick
```
**Symbols:**

```
ffffffff81f11d1f-ffffffff81f11d32: pcibios_scan_root.cold (STB_LOCAL)
ffffffff81e41600-ffffffff81e416d9: pcibios_scan_root (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void pcibios_scan_root(int busnum);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/pci/common.c (ffffffff8201bc00)
Location: arch/x86/pci/common.c:459
Inline: False
Direct callers:
  - arch/x86/pci/fixup.c:pci_fixup_i450gx
  - arch/x86/pci/fixup.c:pci_fixup_i450nx
  - arch/x86/pci/fixup.c:pci_fixup_i450nx
  - arch/x86/pci/legacy.c:pci_subsys_init
  - arch/x86/pci/legacy.c:pcibios_scan_specific_bus
  - arch/x86/pci/irq.c:pirq_peer_trick
```
**Symbols:**

```
ffffffff8201bc00-ffffffff8201bce9: pcibios_scan_root (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void pcibios_scan_root(int busnum);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/pci/common.c (ffffffff8209c2a0)
Location: arch/x86/pci/common.c:459
Inline: False
Direct callers:
  - arch/x86/pci/fixup.c:pci_fixup_i450gx
  - arch/x86/pci/fixup.c:pci_fixup_i450nx
  - arch/x86/pci/fixup.c:pci_fixup_i450nx
  - arch/x86/pci/legacy.c:pci_subsys_init
  - arch/x86/pci/legacy.c:pcibios_scan_specific_bus
  - arch/x86/pci/irq.c:pirq_peer_trick
```
**Symbols:**

```
ffffffff8209c2a0-ffffffff8209c389: pcibios_scan_root (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void pcibios_scan_root(int busnum);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/pci/common.c (ffffffff82173a50)
Location: arch/x86/pci/common.c:459
Inline: False
Direct callers:
  - arch/x86/pci/fixup.c:pci_fixup_i450gx
  - arch/x86/pci/fixup.c:pci_fixup_i450nx
  - arch/x86/pci/fixup.c:pci_fixup_i450nx
  - arch/x86/pci/legacy.c:pci_subsys_init
  - arch/x86/pci/legacy.c:pcibios_scan_specific_bus
  - arch/x86/pci/irq.c:pirq_peer_trick
```
**Symbols:**

```
ffffffff82173a50-ffffffff82173b68: pcibios_scan_root (STB_GLOBAL)
```
</details>
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
void pcibios_scan_root(int busnum);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/pci/common.c (0)
Location: arch/x86/pci/common.c:458
Inline: False
Direct callers:
  - arch/x86/pci/fixup.c:pci_fixup_i450gx
  - arch/x86/pci/fixup.c:pci_fixup_i450nx
  - arch/x86/pci/fixup.c:pci_fixup_i450nx
  - arch/x86/pci/legacy.c:pcibios_scan_specific_bus
  - arch/x86/pci/legacy.c:pci_legacy_init
  - arch/x86/pci/irq.c:pirq_peer_trick
```
**Symbols:**

```
ffffffff818a84b8-ffffffff818a84cc: pcibios_scan_root.cold (STB_LOCAL)
ffffffff818a81c0-ffffffff818a828e: pcibios_scan_root (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Transformation ⚠️</summary>

```c
void pcibios_scan_root(int busnum);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/pci/common.c (0)
Location: arch/x86/pci/common.c:458
Inline: False
Direct callers:
  - arch/x86/pci/fixup.c:pci_fixup_i450gx
  - arch/x86/pci/fixup.c:pci_fixup_i450nx
  - arch/x86/pci/fixup.c:pci_fixup_i450nx
  - arch/x86/pci/legacy.c:pcibios_scan_specific_bus
  - arch/x86/pci/legacy.c:pci_legacy_init
  - arch/x86/pci/irq.c:pirq_peer_trick
```
**Symbols:**

```
ffffffff81862ec8-ffffffff81862edc: pcibios_scan_root.cold (STB_LOCAL)
ffffffff81862c40-ffffffff81862d0e: pcibios_scan_root (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Transformation ⚠️</summary>

```c
void pcibios_scan_root(int busnum);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/pci/common.c (0)
Location: arch/x86/pci/common.c:458
Inline: False
Direct callers:
  - arch/x86/pci/fixup.c:pci_fixup_i450gx
  - arch/x86/pci/fixup.c:pci_fixup_i450nx
  - arch/x86/pci/fixup.c:pci_fixup_i450nx
  - arch/x86/pci/legacy.c:pcibios_scan_specific_bus
  - arch/x86/pci/legacy.c:pci_legacy_init
  - arch/x86/pci/irq.c:pirq_peer_trick
```
**Symbols:**

```
ffffffff818f9b18-ffffffff818f9b2c: pcibios_scan_root.cold (STB_LOCAL)
ffffffff818f9820-ffffffff818f98ee: pcibios_scan_root (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
void pcibios_scan_root(int busnum);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/pci/common.c (0)
Location: arch/x86/pci/common.c:458
Inline: False
Direct callers:
  - arch/x86/pci/fixup.c:pci_fixup_i450gx
  - arch/x86/pci/fixup.c:pci_fixup_i450nx
  - arch/x86/pci/fixup.c:pci_fixup_i450nx
  - arch/x86/pci/legacy.c:pcibios_scan_specific_bus
  - arch/x86/pci/legacy.c:pci_legacy_init
  - arch/x86/pci/irq.c:pirq_peer_trick
```
**Symbols:**

```
ffffffff8191ac78-ffffffff8191ac8c: pcibios_scan_root.cold (STB_LOCAL)
ffffffff8191a980-ffffffff8191aa4e: pcibios_scan_root (STB_GLOBAL)
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
