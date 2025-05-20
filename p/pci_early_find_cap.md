# Function: <code>pci_early_find_cap</code>

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
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
u32 pci_early_find_cap(int bus, int slot, int func, int cap);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/pci/early.c (ffffffff8188c600)
Location: arch/x86/pci/early.c:54
Inline: False
Direct callers:
  - arch/x86/kernel/early-quirks.c:early_pci_clear_msi
  - arch/x86/kernel/early-quirks.c:early_pci_clear_msi
  - arch/x86/kernel/aperture_64.c:search_agp_bridge
```
**Symbols:**

```
ffffffff8188c600-ffffffff8188c6e4: pci_early_find_cap (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
u32 pci_early_find_cap(int bus, int slot, int func, int cap);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/pci/early.c (ffffffff818d6f40)
Location: arch/x86/pci/early.c:54
Inline: False
Direct callers:
  - arch/x86/kernel/early-quirks.c:early_pci_clear_msi
  - arch/x86/kernel/early-quirks.c:early_pci_clear_msi
  - arch/x86/kernel/aperture_64.c:search_agp_bridge
```
**Symbols:**

```
ffffffff818d6f40-ffffffff818d703d: pci_early_find_cap (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
u32 pci_early_find_cap(int bus, int slot, int func, int cap);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/pci/early.c (ffffffff819092c0)
Location: arch/x86/pci/early.c:54
Inline: False
Direct callers:
  - arch/x86/kernel/early-quirks.c:early_pci_clear_msi
  - arch/x86/kernel/early-quirks.c:early_pci_clear_msi
  - arch/x86/kernel/aperture_64.c:search_agp_bridge
```
**Symbols:**

```
ffffffff819092c0-ffffffff819093bd: pci_early_find_cap (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
u32 pci_early_find_cap(int bus, int slot, int func, int cap);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/pci/early.c (ffffffff81bb9ba0)
Location: arch/x86/pci/early.c:54
Inline: False
Direct callers:
  - arch/x86/kernel/early-quirks.c:early_pci_clear_msi
  - arch/x86/kernel/early-quirks.c:early_pci_clear_msi
  - arch/x86/kernel/aperture_64.c:search_agp_bridge
```
**Symbols:**

```
ffffffff81bb9ba0-ffffffff81bb9ca3: pci_early_find_cap (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
u32 pci_early_find_cap(int bus, int slot, int func, int cap);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/pci/early.c (ffffffff81bce4a0)
Location: arch/x86/pci/early.c:54
Inline: False
Direct callers:
  - arch/x86/kernel/early-quirks.c:early_pci_clear_msi
  - arch/x86/kernel/early-quirks.c:early_pci_clear_msi
  - arch/x86/kernel/aperture_64.c:search_agp_bridge
```
**Symbols:**

```
ffffffff81bce4a0-ffffffff81bce5a3: pci_early_find_cap (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
u32 pci_early_find_cap(int bus, int slot, int func, int cap);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/pci/early.c (ffffffff81bc1e50)
Location: arch/x86/pci/early.c:54
Inline: False
Direct callers:
  - arch/x86/kernel/early-quirks.c:early_pci_clear_msi
  - arch/x86/kernel/early-quirks.c:early_pci_clear_msi
  - arch/x86/kernel/aperture_64.c:search_agp_bridge
```
**Symbols:**

```
ffffffff81bc1e50-ffffffff81bc1f55: pci_early_find_cap (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
u32 pci_early_find_cap(int bus, int slot, int func, int cap);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/pci/early.c (ffffffff81c92460)
Location: arch/x86/pci/early.c:54
Inline: False
Direct callers:
  - arch/x86/kernel/early-quirks.c:early_pci_clear_msi
  - arch/x86/kernel/early-quirks.c:early_pci_clear_msi
  - arch/x86/kernel/aperture_64.c:search_agp_bridge
```
**Symbols:**

```
ffffffff81c92460-ffffffff81c92565: pci_early_find_cap (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
u32 pci_early_find_cap(int bus, int slot, int func, int cap);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/pci/early.c (ffffffff81e41b50)
Location: arch/x86/pci/early.c:54
Inline: False
Direct callers:
  - arch/x86/kernel/early-quirks.c:early_pci_clear_msi
  - arch/x86/kernel/early-quirks.c:early_pci_clear_msi
```
**Symbols:**

```
ffffffff81e41b50-ffffffff81e41c63: pci_early_find_cap (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
u32 pci_early_find_cap(int bus, int slot, int func, int cap);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/pci/early.c (ffffffff8201c240)
Location: arch/x86/pci/early.c:54
Inline: False
Direct callers:
  - arch/x86/kernel/early-quirks.c:early_pci_clear_msi
  - arch/x86/kernel/early-quirks.c:early_pci_clear_msi
```
**Symbols:**

```
ffffffff8201c240-ffffffff8201c353: pci_early_find_cap (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
u32 pci_early_find_cap(int bus, int slot, int func, int cap);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/pci/early.c (ffffffff8209c8e0)
Location: arch/x86/pci/early.c:54
Inline: False
Direct callers:
  - arch/x86/kernel/early-quirks.c:early_pci_clear_msi
  - arch/x86/kernel/early-quirks.c:early_pci_clear_msi
```
**Symbols:**

```
ffffffff8209c8e0-ffffffff8209c9f3: pci_early_find_cap (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
u32 pci_early_find_cap(int bus, int slot, int func, int cap);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/pci/early.c (ffffffff821740c0)
Location: arch/x86/pci/early.c:54
Inline: False
Direct callers:
  - arch/x86/kernel/early-quirks.c:early_pci_clear_msi
  - arch/x86/kernel/early-quirks.c:early_pci_clear_msi
```
**Symbols:**

```
ffffffff821740c0-ffffffff821741d3: pci_early_find_cap (STB_GLOBAL)
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
<summary>In <code>aws</code>: ✅</summary>

```c
u32 pci_early_find_cap(int bus, int slot, int func, int cap);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/pci/early.c (ffffffff818a8680)
Location: arch/x86/pci/early.c:54
Inline: False
Direct callers:
  - arch/x86/kernel/early-quirks.c:early_pci_clear_msi
  - arch/x86/kernel/early-quirks.c:early_pci_clear_msi
  - arch/x86/kernel/aperture_64.c:search_agp_bridge
```
**Symbols:**

```
ffffffff818a8680-ffffffff818a877d: pci_early_find_cap (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
u32 pci_early_find_cap(int bus, int slot, int func, int cap);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/pci/early.c (ffffffff81863090)
Location: arch/x86/pci/early.c:54
Inline: False
Direct callers:
  - arch/x86/kernel/early-quirks.c:early_pci_clear_msi
  - arch/x86/kernel/early-quirks.c:early_pci_clear_msi
  - arch/x86/kernel/aperture_64.c:search_agp_bridge
```
**Symbols:**

```
ffffffff81863090-ffffffff8186318d: pci_early_find_cap (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
u32 pci_early_find_cap(int bus, int slot, int func, int cap);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/pci/early.c (ffffffff818f9ce0)
Location: arch/x86/pci/early.c:54
Inline: False
Direct callers:
  - arch/x86/kernel/early-quirks.c:early_pci_clear_msi
  - arch/x86/kernel/early-quirks.c:early_pci_clear_msi
  - arch/x86/kernel/aperture_64.c:search_agp_bridge
```
**Symbols:**

```
ffffffff818f9ce0-ffffffff818f9ddd: pci_early_find_cap (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
u32 pci_early_find_cap(int bus, int slot, int func, int cap);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/pci/early.c (ffffffff8191ae40)
Location: arch/x86/pci/early.c:54
Inline: False
Direct callers:
  - arch/x86/kernel/early-quirks.c:early_pci_clear_msi
  - arch/x86/kernel/early-quirks.c:early_pci_clear_msi
  - arch/x86/kernel/aperture_64.c:search_agp_bridge
```
**Symbols:**

```
ffffffff8191ae40-ffffffff8191af3d: pci_early_find_cap (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
