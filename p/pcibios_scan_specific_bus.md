# Function: <code>pcibios_scan_specific_bus</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void pcibios_scan_specific_bus(int busn);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/pci/legacy.c (ffffffff816f8fc0)
Location: arch/x86/pci/legacy.c:37
Inline: False
Direct callers:
  - arch/x86/pci/legacy.c:pci_subsys_init
```
**Symbols:**

```
ffffffff816f8fc0-ffffffff816f905f: pcibios_scan_specific_bus (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void pcibios_scan_specific_bus(int busn);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/pci/legacy.c (ffffffff8175dcd0)
Location: arch/x86/pci/legacy.c:37
Inline: False
Direct callers:
  - arch/x86/pci/legacy.c:pci_subsys_init
```
**Symbols:**

```
ffffffff8175dcd0-ffffffff8175dd6f: pcibios_scan_specific_bus (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void pcibios_scan_specific_bus(int busn);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/pci/legacy.c (ffffffff8178a200)
Location: arch/x86/pci/legacy.c:37
Inline: False
Direct callers:
  - arch/x86/pci/legacy.c:pci_subsys_init
```
**Symbols:**

```
ffffffff8178a200-ffffffff8178a29f: pcibios_scan_specific_bus (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void pcibios_scan_specific_bus(int busn);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/pci/legacy.c (ffffffff817a9340)
Location: arch/x86/pci/legacy.c:35
Inline: False
Direct callers:
  - arch/x86/pci/legacy.c:pci_subsys_init
```
**Symbols:**

```
ffffffff817a9340-ffffffff817a93df: pcibios_scan_specific_bus (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void pcibios_scan_specific_bus(int busn);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/pci/legacy.c (ffffffff818207f0)
Location: arch/x86/pci/legacy.c:35
Inline: False
Direct callers:
  - arch/x86/pci/legacy.c:pci_subsys_init
```
**Symbols:**

```
ffffffff818207f0-ffffffff8182088f: pcibios_scan_specific_bus (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void pcibios_scan_specific_bus(int busn);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/pci/legacy.c (ffffffff8186aa70)
Location: arch/x86/pci/legacy.c:36
Inline: False
Direct callers:
  - arch/x86/pci/legacy.c:pci_subsys_init
```
**Symbols:**

```
ffffffff8186aa70-ffffffff8186ab26: pcibios_scan_specific_bus (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void pcibios_scan_specific_bus(int busn);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/pci/legacy.c (ffffffff8188ab40)
Location: arch/x86/pci/legacy.c:36
Inline: False
Direct callers:
  - arch/x86/pci/legacy.c:pci_subsys_init
```
**Symbols:**

```
ffffffff8188ab40-ffffffff8188abf6: pcibios_scan_specific_bus (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
void pcibios_scan_specific_bus(int busn);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/pci/legacy.c (0)
Location: arch/x86/pci/legacy.c:37
Inline: False
Direct callers:
  - arch/x86/pci/legacy.c:pci_subsys_init
```
**Symbols:**

```
ffffffff818d5512-ffffffff818d552e: pcibios_scan_specific_bus.cold (STB_LOCAL)
ffffffff818d5470-ffffffff818d5512: pcibios_scan_specific_bus (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
void pcibios_scan_specific_bus(int busn);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/pci/legacy.c (0)
Location: arch/x86/pci/legacy.c:37
Inline: False
Direct callers:
  - arch/x86/pci/legacy.c:pci_subsys_init
```
**Symbols:**

```
ffffffff81907892-ffffffff819078ae: pcibios_scan_specific_bus.cold (STB_LOCAL)
ffffffff819077f0-ffffffff81907892: pcibios_scan_specific_bus (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
void pcibios_scan_specific_bus(int busn);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/pci/legacy.c (0)
Location: arch/x86/pci/legacy.c:37
Inline: False
Direct callers:
  - arch/x86/pci/legacy.c:pci_subsys_init
```
**Symbols:**

```
ffffffff81bb7fb2-ffffffff81bb7fce: pcibios_scan_specific_bus.cold (STB_LOCAL)
ffffffff81bb7f10-ffffffff81bb7fb2: pcibios_scan_specific_bus (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
void pcibios_scan_specific_bus(int busn);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/pci/legacy.c (0)
Location: arch/x86/pci/legacy.c:37
Inline: False
Direct callers:
  - arch/x86/pci/legacy.c:pci_subsys_init
```
**Symbols:**

```
ffffffff81c346f6-ffffffff81c34712: pcibios_scan_specific_bus.cold (STB_LOCAL)
ffffffff81bccb30-ffffffff81bccbd2: pcibios_scan_specific_bus (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
void pcibios_scan_specific_bus(int busn);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/pci/legacy.c (0)
Location: arch/x86/pci/legacy.c:37
Inline: False
Direct callers:
  - arch/x86/pci/legacy.c:pci_subsys_init
```
**Symbols:**

```
ffffffff81c26ad2-ffffffff81c26aee: pcibios_scan_specific_bus.cold (STB_LOCAL)
ffffffff81bc0560-ffffffff81bc0602: pcibios_scan_specific_bus (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
void pcibios_scan_specific_bus(int busn);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/pci/legacy.c (0)
Location: arch/x86/pci/legacy.c:37
Inline: False
Direct callers:
  - arch/x86/pci/legacy.c:pci_subsys_init
```
**Symbols:**

```
ffffffff81d4496f-ffffffff81d4498b: pcibios_scan_specific_bus.cold (STB_LOCAL)
ffffffff81c90530-ffffffff81c905d2: pcibios_scan_specific_bus (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
void pcibios_scan_specific_bus(int busn);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/pci/legacy.c (0)
Location: arch/x86/pci/legacy.c:37
Inline: False
Direct callers:
  - arch/x86/pci/legacy.c:pci_subsys_init
```
**Symbols:**

```
ffffffff81f1187e-ffffffff81f1189a: pcibios_scan_specific_bus.cold (STB_LOCAL)
ffffffff81e3f660-ffffffff81e3f71d: pcibios_scan_specific_bus (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void pcibios_scan_specific_bus(int busn);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/pci/legacy.c (ffffffff82019560)
Location: arch/x86/pci/legacy.c:37
Inline: False
Direct callers:
  - arch/x86/pci/legacy.c:pci_subsys_init
```
**Symbols:**

```
ffffffff82019560-ffffffff82019631: pcibios_scan_specific_bus (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void pcibios_scan_specific_bus(int busn);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/pci/legacy.c (ffffffff82099be0)
Location: arch/x86/pci/legacy.c:37
Inline: False
Direct callers:
  - arch/x86/pci/legacy.c:pci_subsys_init
```
**Symbols:**

```
ffffffff82099be0-ffffffff82099cb1: pcibios_scan_specific_bus (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void pcibios_scan_specific_bus(int busn);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/pci/legacy.c (ffffffff82171310)
Location: arch/x86/pci/legacy.c:37
Inline: False
Direct callers:
  - arch/x86/pci/legacy.c:pci_subsys_init
```
**Symbols:**

```
ffffffff82171310-ffffffff821713e1: pcibios_scan_specific_bus (STB_GLOBAL)
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
void pcibios_scan_specific_bus(int busn);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/pci/legacy.c (0)
Location: arch/x86/pci/legacy.c:37
Inline: False
Direct callers:
  - arch/x86/pci/legacy.c:pci_subsys_init
```
**Symbols:**

```
ffffffff818a6c52-ffffffff818a6c6e: pcibios_scan_specific_bus.cold (STB_LOCAL)
ffffffff818a6bb0-ffffffff818a6c52: pcibios_scan_specific_bus (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Transformation ⚠️</summary>

```c
void pcibios_scan_specific_bus(int busn);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/pci/legacy.c (0)
Location: arch/x86/pci/legacy.c:37
Inline: False
Direct callers:
  - arch/x86/pci/legacy.c:pci_subsys_init
```
**Symbols:**

```
ffffffff81861772-ffffffff8186178e: pcibios_scan_specific_bus.cold (STB_LOCAL)
ffffffff818616d0-ffffffff81861772: pcibios_scan_specific_bus (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Transformation ⚠️</summary>

```c
void pcibios_scan_specific_bus(int busn);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/pci/legacy.c (0)
Location: arch/x86/pci/legacy.c:37
Inline: False
Direct callers:
  - arch/x86/pci/legacy.c:pci_subsys_init
```
**Symbols:**

```
ffffffff818f82b2-ffffffff818f82ce: pcibios_scan_specific_bus.cold (STB_LOCAL)
ffffffff818f8210-ffffffff818f82b2: pcibios_scan_specific_bus (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
void pcibios_scan_specific_bus(int busn);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/pci/legacy.c (0)
Location: arch/x86/pci/legacy.c:37
Inline: False
Direct callers:
  - arch/x86/pci/legacy.c:pci_subsys_init
```
**Symbols:**

```
ffffffff819193b2-ffffffff819193ce: pcibios_scan_specific_bus.cold (STB_LOCAL)
ffffffff81919310-ffffffff819193b2: pcibios_scan_specific_bus (STB_GLOBAL)
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
