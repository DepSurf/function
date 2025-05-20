# Function: <code>aer_recover_queue</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void aer_recover_queue(int domain, unsigned int bus, unsigned int devfn, int severity, struct aer_capability_regs *aer_regs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pcie/aer/aerdrv_core.c (ffffffff8144a230)
Location: drivers/pci/pcie/aer/aerdrv_core.c:590
Inline: False
```
**Symbols:**

```
ffffffff8144a230-ffffffff8144a307: aer_recover_queue (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void aer_recover_queue(int domain, unsigned int bus, unsigned int devfn, int severity, struct aer_capability_regs *aer_regs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pcie/aer/aerdrv_core.c (ffffffff814964f0)
Location: drivers/pci/pcie/aer/aerdrv_core.c:590
Inline: False
```
**Symbols:**

```
ffffffff814964f0-ffffffff814965c7: aer_recover_queue (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void aer_recover_queue(int domain, unsigned int bus, unsigned int devfn, int severity, struct aer_capability_regs *aer_regs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pcie/aer/aerdrv_core.c (ffffffff814b7e90)
Location: drivers/pci/pcie/aer/aerdrv_core.c:592
Inline: False
```
**Symbols:**

```
ffffffff814b7e90-ffffffff814b7f67: aer_recover_queue (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void aer_recover_queue(int domain, unsigned int bus, unsigned int devfn, int severity, struct aer_capability_regs *aer_regs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pcie/aer/aerdrv_core.c (ffffffff814c2710)
Location: drivers/pci/pcie/aer/aerdrv_core.c:592
Inline: False
```
**Symbols:**

```
ffffffff814c2710-ffffffff814c27e9: aer_recover_queue (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void aer_recover_queue(int domain, unsigned int bus, unsigned int devfn, int severity, struct aer_capability_regs *aer_regs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pcie/aer/aerdrv_core.c (ffffffff81502950)
Location: drivers/pci/pcie/aer/aerdrv_core.c:599
Inline: False
Direct callers:
  - drivers/acpi/apei/ghes.c:ghes_do_proc
```
**Symbols:**

```
ffffffff81502950-ffffffff81502a29: aer_recover_queue (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void aer_recover_queue(int domain, unsigned int bus, unsigned int devfn, int severity, struct aer_capability_regs *aer_regs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pcie/aer.c (ffffffff815331f0)
Location: drivers/pci/pcie/aer.c:861
Inline: False
```
**Symbols:**

```
ffffffff815331f0-ffffffff815332c4: aer_recover_queue (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline, Transformation ⚠️</summary>

```c
void aer_recover_queue(int domain, unsigned int bus, unsigned int devfn, int severity, struct aer_capability_regs *aer_regs);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/pci/pcie/aer.c (ffffffff8154c0d4)
Location: drivers/pci/pcie/aer.c:1056
Inline: True
```
**Symbols:**

```
ffffffff8154c0d4-ffffffff8154c0f9: aer_recover_queue.cold.22 (STB_LOCAL)
ffffffff8154aa40-ffffffff8154aaf9: aer_recover_queue (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline, Transformation ⚠️</summary>

```c
void aer_recover_queue(int domain, unsigned int bus, unsigned int devfn, int severity, struct aer_capability_regs *aer_regs);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/pci/pcie/aer.c (ffffffff8157b8eb)
Location: drivers/pci/pcie/aer.c:1056
Inline: True
```
**Symbols:**

```
ffffffff8157b8eb-ffffffff8157b910: aer_recover_queue.cold (STB_LOCAL)
ffffffff8157a980-ffffffff8157aa39: aer_recover_queue (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline, Transformation ⚠️</summary>

```c
void aer_recover_queue(int domain, unsigned int bus, unsigned int devfn, int severity, struct aer_capability_regs *aer_regs);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/pci/pcie/aer.c (ffffffff8159d352)
Location: drivers/pci/pcie/aer.c:1056
Inline: True
```
**Symbols:**

```
ffffffff8159d352-ffffffff8159d377: aer_recover_queue.cold (STB_LOCAL)
ffffffff8159c3c0-ffffffff8159c479: aer_recover_queue (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
void aer_recover_queue(int domain, unsigned int bus, unsigned int devfn, int severity, struct aer_capability_regs *aer_regs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pci/pcie/aer.c (0)
Location: drivers/pci/pcie/aer.c:982
Inline: False
```
**Symbols:**

```
ffffffff8163cef2-ffffffff8163cf17: aer_recover_queue.cold (STB_LOCAL)
ffffffff8163bfb0-ffffffff8163c069: aer_recover_queue (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
void aer_recover_queue(int domain, unsigned int bus, unsigned int devfn, int severity, struct aer_capability_regs *aer_regs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pci/pcie/aer.c (0)
Location: drivers/pci/pcie/aer.c:1010
Inline: False
```
**Symbols:**

```
ffffffff81bf92b2-ffffffff81bf92d7: aer_recover_queue.cold (STB_LOCAL)
ffffffff81662f50-ffffffff81663009: aer_recover_queue (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
void aer_recover_queue(int domain, unsigned int bus, unsigned int devfn, int severity, struct aer_capability_regs *aer_regs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pci/pcie/aer.c (0)
Location: drivers/pci/pcie/aer.c:1010
Inline: False
```
**Symbols:**

```
ffffffff81beb107-ffffffff81beb12c: aer_recover_queue.cold (STB_LOCAL)
ffffffff81645410-ffffffff816454c9: aer_recover_queue (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
void aer_recover_queue(int domain, unsigned int bus, unsigned int devfn, int severity, struct aer_capability_regs *aer_regs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pci/pcie/aer.c (0)
Location: drivers/pci/pcie/aer.c:1012
Inline: False
```
**Symbols:**

```
ffffffff81ce5fea-ffffffff81ce600f: aer_recover_queue.cold (STB_LOCAL)
ffffffff816b63d0-ffffffff816b6489: aer_recover_queue (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
void aer_recover_queue(int domain, unsigned int bus, unsigned int devfn, int severity, struct aer_capability_regs *aer_regs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pci/pcie/aer.c (0)
Location: drivers/pci/pcie/aer.c:1017
Inline: False
```
**Symbols:**

```
ffffffff81eacad5-ffffffff81eacafa: aer_recover_queue.cold (STB_LOCAL)
ffffffff817d9f20-ffffffff817d9fea: aer_recover_queue (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void aer_recover_queue(int domain, unsigned int bus, unsigned int devfn, int severity, struct aer_capability_regs *aer_regs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pcie/aer.c (ffffffff818fb900)
Location: drivers/pci/pcie/aer.c:1028
Inline: False
```
**Symbols:**

```
ffffffff818fb900-ffffffff818fb9e8: aer_recover_queue (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void aer_recover_queue(int domain, unsigned int bus, unsigned int devfn, int severity, struct aer_capability_regs *aer_regs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pcie/aer.c (ffffffff8193edf0)
Location: drivers/pci/pcie/aer.c:1031
Inline: False
```
**Symbols:**

```
ffffffff8193edf0-ffffffff8193eed8: aer_recover_queue (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void aer_recover_queue(int domain, unsigned int bus, unsigned int devfn, int severity, struct aer_capability_regs *aer_regs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pcie/aer.c (ffffffff81987ec0)
Location: drivers/pci/pcie/aer.c:1179
Inline: False
Direct callers:
  - drivers/acpi/apei/ghes.c:ghes_handle_aer
```
**Symbols:**

```
ffffffff81987ec0-ffffffff81987fa8: aer_recover_queue (STB_GLOBAL)
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
void aer_recover_queue(int domain, unsigned int bus, unsigned int devfn, int severity, struct aer_capability_regs *aer_regs);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/pcie/aer.c (ffff8000107047c8)
Location: drivers/pci/pcie/aer.c:1056
Inline: True
```
**Symbols:**

```
ffff8000107047c8-ffff80001070491c: aer_recover_queue (STB_GLOBAL)
```
</details>
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
In <code>aws</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline, Transformation ⚠️</summary>

```c
void aer_recover_queue(int domain, unsigned int bus, unsigned int devfn, int severity, struct aer_capability_regs *aer_regs);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/pci/pcie/aer.c (ffffffff8157fd22)
Location: drivers/pci/pcie/aer.c:1056
Inline: True
```
**Symbols:**

```
ffffffff8157fd22-ffffffff8157fd47: aer_recover_queue.cold (STB_LOCAL)
ffffffff8157ed90-ffffffff8157ee49: aer_recover_queue (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline, Transformation ⚠️</summary>

```c
void aer_recover_queue(int domain, unsigned int bus, unsigned int devfn, int severity, struct aer_capability_regs *aer_regs);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/pci/pcie/aer.c (ffffffff815910a2)
Location: drivers/pci/pcie/aer.c:1056
Inline: True
```
**Symbols:**

```
ffffffff815910a2-ffffffff815910c7: aer_recover_queue.cold (STB_LOCAL)
ffffffff81590110-ffffffff815901c9: aer_recover_queue (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline, Transformation ⚠️</summary>

```c
void aer_recover_queue(int domain, unsigned int bus, unsigned int devfn, int severity, struct aer_capability_regs *aer_regs);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/pci/pcie/aer.c (ffffffff815ab567)
Location: drivers/pci/pcie/aer.c:1056
Inline: True
```
**Symbols:**

```
ffffffff815ab567-ffffffff815ab58c: aer_recover_queue.cold (STB_LOCAL)
ffffffff815aa5c0-ffffffff815aa679: aer_recover_queue (STB_GLOBAL)
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
