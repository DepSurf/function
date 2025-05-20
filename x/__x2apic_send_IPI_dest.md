# Function: <code>__x2apic_send_IPI_dest</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/x2apic_phys.c (ffffffff81059889)
Location: arch/x86/include/asm/x2apic.h:23
Inline: True
Inline callers:
  - arch/x86/kernel/apic/x2apic_phys.c:__x2apic_send_IPI_mask
```
```
In arch/x86/kernel/apic/x2apic_cluster.c (ffffffff81059d2a)
Location: arch/x86/include/asm/x2apic.h:23
Inline: True
Inline callers:
  - arch/x86/kernel/apic/x2apic_cluster.c:__x2apic_send_IPI_mask
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Duplicate, Selective Inline, Transformation ⚠️</summary>

```c
void __x2apic_send_IPI_dest(unsigned int apicid, int vector, unsigned int dest);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/apic/x2apic_phys.c (ffffffff81059a30)
Location: arch/x86/include/asm/x2apic.h:23
Inline: True
Direct callers:
  - arch/x86/kernel/apic/x2apic_phys.c:__x2apic_send_IPI_mask
  - arch/x86/kernel/apic/x2apic_phys.c:x2apic_send_IPI
```
```
In arch/x86/kernel/apic/x2apic_cluster.c (ffffffff81059d20)
Location: arch/x86/include/asm/x2apic.h:23
Inline: False
Direct callers:
  - arch/x86/kernel/apic/x2apic_cluster.c:__x2apic_send_IPI_mask
  - arch/x86/kernel/apic/x2apic_cluster.c:x2apic_send_IPI
```
**Symbols:**

```
ffffffff81059a30-ffffffff81059a65: __x2apic_send_IPI_dest.constprop.4 (STB_LOCAL)
ffffffff81059d20-ffffffff81059d56: __x2apic_send_IPI_dest (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Duplicate, Selective Inline, Transformation ⚠️</summary>

```c
void __x2apic_send_IPI_dest(unsigned int apicid, int vector, unsigned int dest);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/apic/x2apic_phys.c (ffffffff8105c7e0)
Location: arch/x86/include/asm/x2apic.h:23
Inline: True
Direct callers:
  - arch/x86/kernel/apic/x2apic_phys.c:__x2apic_send_IPI_mask
  - arch/x86/kernel/apic/x2apic_phys.c:x2apic_send_IPI
```
```
In arch/x86/kernel/apic/x2apic_cluster.c (ffffffff8105cae0)
Location: arch/x86/include/asm/x2apic.h:23
Inline: False
Direct callers:
  - arch/x86/kernel/apic/x2apic_cluster.c:__x2apic_send_IPI_mask
  - arch/x86/kernel/apic/x2apic_cluster.c:x2apic_send_IPI
```
**Symbols:**

```
ffffffff8105c7e0-ffffffff8105c815: __x2apic_send_IPI_dest.constprop.4 (STB_LOCAL)
ffffffff8105cae0-ffffffff8105cb16: __x2apic_send_IPI_dest (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Duplicate, Selective Inline, Transformation ⚠️</summary>

```c
void __x2apic_send_IPI_dest(unsigned int apicid, int vector, unsigned int dest);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/apic/x2apic_phys.c (ffffffff8105bef0)
Location: arch/x86/include/asm/x2apic.h:23
Inline: True
Direct callers:
  - arch/x86/kernel/apic/x2apic_phys.c:__x2apic_send_IPI_mask
  - arch/x86/kernel/apic/x2apic_phys.c:x2apic_send_IPI
```
```
In arch/x86/kernel/apic/x2apic_cluster.c (ffffffff8105c220)
Location: arch/x86/include/asm/x2apic.h:23
Inline: False
Direct callers:
  - arch/x86/kernel/apic/x2apic_cluster.c:__x2apic_send_IPI_mask
  - arch/x86/kernel/apic/x2apic_cluster.c:x2apic_send_IPI
```
**Symbols:**

```
ffffffff8105bef0-ffffffff8105bf25: __x2apic_send_IPI_dest.constprop.3 (STB_LOCAL)
ffffffff8105c220-ffffffff8105c256: __x2apic_send_IPI_dest (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
void __x2apic_send_IPI_dest(unsigned int apicid, int vector, unsigned int dest);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/x2apic_phys.c (ffffffff81060085)
Location: arch/x86/kernel/apic/x2apic_phys.c:114
Inline: True
Inline callers:
  - arch/x86/kernel/apic/x2apic_phys.c:__x2apic_send_IPI_mask
  - arch/x86/kernel/apic/x2apic_phys.c:x2apic_send_IPI
Direct callers:
  - arch/x86/kernel/apic/x2apic_cluster.c:__x2apic_send_IPI_mask
  - arch/x86/kernel/apic/x2apic_cluster.c:x2apic_send_IPI
```
**Symbols:**

```
ffffffff81060180-ffffffff810601b6: __x2apic_send_IPI_dest (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
void __x2apic_send_IPI_dest(unsigned int apicid, int vector, unsigned int dest);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/x2apic_phys.c (ffffffff8106306f)
Location: arch/x86/kernel/apic/x2apic_phys.c:114
Inline: True
Inline callers:
  - arch/x86/kernel/apic/x2apic_phys.c:__x2apic_send_IPI_mask
  - arch/x86/kernel/apic/x2apic_phys.c:x2apic_send_IPI
Direct callers:
  - arch/x86/kernel/apic/x2apic_cluster.c:__x2apic_send_IPI_mask
  - arch/x86/kernel/apic/x2apic_cluster.c:x2apic_send_IPI
```
**Symbols:**

```
ffffffff81063240-ffffffff81063276: __x2apic_send_IPI_dest (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
void __x2apic_send_IPI_dest(unsigned int apicid, int vector, unsigned int dest);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/x2apic_phys.c (ffffffff81068e4f)
Location: arch/x86/kernel/apic/x2apic_phys.c:114
Inline: True
Inline callers:
  - arch/x86/kernel/apic/x2apic_phys.c:__x2apic_send_IPI_mask
  - arch/x86/kernel/apic/x2apic_phys.c:x2apic_send_IPI
Direct callers:
  - arch/x86/kernel/apic/x2apic_cluster.c:__x2apic_send_IPI_mask
  - arch/x86/kernel/apic/x2apic_cluster.c:x2apic_send_IPI
```
**Symbols:**

```
ffffffff81068f40-ffffffff81068f76: __x2apic_send_IPI_dest (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
void __x2apic_send_IPI_dest(unsigned int apicid, int vector, unsigned int dest);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/x2apic_phys.c (ffffffff8106c66f)
Location: arch/x86/kernel/apic/x2apic_phys.c:114
Inline: True
Inline callers:
  - arch/x86/kernel/apic/x2apic_phys.c:__x2apic_send_IPI_mask
  - arch/x86/kernel/apic/x2apic_phys.c:x2apic_send_IPI
Direct callers:
  - arch/x86/kernel/apic/x2apic_cluster.c:__x2apic_send_IPI_mask
  - arch/x86/kernel/apic/x2apic_cluster.c:x2apic_send_IPI
```
**Symbols:**

```
ffffffff8106c770-ffffffff8106c7a6: __x2apic_send_IPI_dest (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
void __x2apic_send_IPI_dest(unsigned int apicid, int vector, unsigned int dest);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/x2apic_phys.c (ffffffff8106dd6f)
Location: arch/x86/kernel/apic/x2apic_phys.c:109
Inline: True
Inline callers:
  - arch/x86/kernel/apic/x2apic_phys.c:__x2apic_send_IPI_mask
  - arch/x86/kernel/apic/x2apic_phys.c:x2apic_send_IPI
Direct callers:
  - arch/x86/kernel/apic/x2apic_cluster.c:__x2apic_send_IPI_mask
  - arch/x86/kernel/apic/x2apic_cluster.c:x2apic_send_IPI
```
**Symbols:**

```
ffffffff8106de90-ffffffff8106dec6: __x2apic_send_IPI_dest (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
void __x2apic_send_IPI_dest(unsigned int apicid, int vector, unsigned int dest);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/x2apic_phys.c (ffffffff810751ef)
Location: arch/x86/kernel/apic/x2apic_phys.c:109
Inline: True
Inline callers:
  - arch/x86/kernel/apic/x2apic_phys.c:__x2apic_send_IPI_mask
  - arch/x86/kernel/apic/x2apic_phys.c:x2apic_send_IPI
Direct callers:
  - arch/x86/kernel/apic/x2apic_cluster.c:__x2apic_send_IPI_mask
  - arch/x86/kernel/apic/x2apic_cluster.c:x2apic_send_IPI
```
**Symbols:**

```
ffffffff81075360-ffffffff81075396: __x2apic_send_IPI_dest (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
void __x2apic_send_IPI_dest(unsigned int apicid, int vector, unsigned int dest);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/x2apic_phys.c (ffffffff81075822)
Location: arch/x86/kernel/apic/x2apic_phys.c:120
Inline: True
Inline callers:
  - arch/x86/kernel/apic/x2apic_phys.c:__x2apic_send_IPI_mask
  - arch/x86/kernel/apic/x2apic_phys.c:x2apic_send_IPI
Direct callers:
  - arch/x86/kernel/apic/x2apic_cluster.c:__x2apic_send_IPI_mask
  - arch/x86/kernel/apic/x2apic_cluster.c:x2apic_send_IPI
```
**Symbols:**

```
ffffffff810759c0-ffffffff810759f6: __x2apic_send_IPI_dest (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
void __x2apic_send_IPI_dest(unsigned int apicid, int vector, unsigned int dest);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/x2apic_phys.c (ffffffff810762f0)
Location: arch/x86/kernel/apic/x2apic_phys.c:120
Inline: True
Inline callers:
  - arch/x86/kernel/apic/x2apic_phys.c:__x2apic_send_IPI_mask
  - arch/x86/kernel/apic/x2apic_phys.c:x2apic_send_IPI
Direct callers:
  - arch/x86/kernel/apic/x2apic_cluster.c:__x2apic_send_IPI_mask
  - arch/x86/kernel/apic/x2apic_cluster.c:x2apic_send_IPI
```
**Symbols:**

```
ffffffff81076460-ffffffff81076496: __x2apic_send_IPI_dest (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
void __x2apic_send_IPI_dest(unsigned int apicid, int vector, unsigned int dest);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/x2apic_phys.c (ffffffff810838f9)
Location: arch/x86/kernel/apic/x2apic_phys.c:120
Inline: True
Inline callers:
  - arch/x86/kernel/apic/x2apic_phys.c:__x2apic_send_IPI_mask
  - arch/x86/kernel/apic/x2apic_phys.c:x2apic_send_IPI
Direct callers:
  - arch/x86/kernel/apic/x2apic_cluster.c:__x2apic_send_IPI_mask
  - arch/x86/kernel/apic/x2apic_cluster.c:x2apic_send_IPI
```
**Symbols:**

```
ffffffff81083ab0-ffffffff81083ae6: __x2apic_send_IPI_dest (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
void __x2apic_send_IPI_dest(unsigned int apicid, int vector, unsigned int dest);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/x2apic_phys.c (ffffffff810938b7)
Location: arch/x86/kernel/apic/x2apic_phys.c:120
Inline: True
Inline callers:
  - arch/x86/kernel/apic/x2apic_phys.c:__x2apic_send_IPI_mask
  - arch/x86/kernel/apic/x2apic_phys.c:x2apic_send_IPI
Direct callers:
  - arch/x86/kernel/apic/x2apic_cluster.c:__x2apic_send_IPI_mask
  - arch/x86/kernel/apic/x2apic_cluster.c:x2apic_send_IPI
```
**Symbols:**

```
ffffffff81093ab0-ffffffff81093aff: __x2apic_send_IPI_dest (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
void __x2apic_send_IPI_dest(unsigned int apicid, int vector, unsigned int dest);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/x2apic_phys.c (ffffffff810a8fda)
Location: arch/x86/kernel/apic/x2apic_phys.c:120
Inline: True
Inline callers:
  - arch/x86/kernel/apic/x2apic_phys.c:__x2apic_send_IPI_mask
  - arch/x86/kernel/apic/x2apic_phys.c:x2apic_send_IPI
Direct callers:
  - arch/x86/kernel/apic/x2apic_cluster.c:__x2apic_send_IPI_mask
  - arch/x86/kernel/apic/x2apic_cluster.c:x2apic_send_IPI
```
**Symbols:**

```
ffffffff810a91a0-ffffffff810a91ef: __x2apic_send_IPI_dest (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
void __x2apic_send_IPI_dest(unsigned int apicid, int vector, unsigned int dest);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/x2apic_phys.c (ffffffff810ac1fa)
Location: arch/x86/kernel/apic/x2apic_phys.c:123
Inline: True
Inline callers:
  - arch/x86/kernel/apic/x2apic_phys.c:__x2apic_send_IPI_mask
  - arch/x86/kernel/apic/x2apic_phys.c:x2apic_send_IPI
Direct callers:
  - arch/x86/kernel/apic/x2apic_cluster.c:__x2apic_send_IPI_mask
  - arch/x86/kernel/apic/x2apic_cluster.c:x2apic_send_IPI
```
**Symbols:**

```
ffffffff810ac3c0-ffffffff810ac40f: __x2apic_send_IPI_dest (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
void __x2apic_send_IPI_dest(unsigned int apicid, int vector, unsigned int dest);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/x2apic_phys.c (ffffffff810b2f9a)
Location: arch/x86/kernel/apic/x2apic_phys.c:110
Inline: True
Inline callers:
  - arch/x86/kernel/apic/x2apic_phys.c:__x2apic_send_IPI_mask
  - arch/x86/kernel/apic/x2apic_phys.c:x2apic_send_IPI
Direct callers:
  - arch/x86/kernel/apic/x2apic_cluster.c:__x2apic_send_IPI_mask
  - arch/x86/kernel/apic/x2apic_cluster.c:x2apic_send_IPI
```
**Symbols:**

```
ffffffff810b3140-ffffffff810b318f: __x2apic_send_IPI_dest (STB_GLOBAL)
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
<summary>In <code>aws</code>: Selective Inline ⚠️</summary>

```c
void __x2apic_send_IPI_dest(unsigned int apicid, int vector, unsigned int dest);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/x2apic_phys.c (ffffffff8106cd0f)
Location: arch/x86/kernel/apic/x2apic_phys.c:109
Inline: True
Inline callers:
  - arch/x86/kernel/apic/x2apic_phys.c:__x2apic_send_IPI_mask
  - arch/x86/kernel/apic/x2apic_phys.c:x2apic_send_IPI
Direct callers:
  - arch/x86/kernel/apic/x2apic_cluster.c:__x2apic_send_IPI_mask
  - arch/x86/kernel/apic/x2apic_cluster.c:x2apic_send_IPI
```
**Symbols:**

```
ffffffff8106ce30-ffffffff8106ce66: __x2apic_send_IPI_dest (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
void __x2apic_send_IPI_dest(unsigned int apicid, int vector, unsigned int dest);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/x2apic_phys.c (ffffffff8105d04e)
Location: arch/x86/kernel/apic/x2apic_phys.c:109
Inline: True
Inline callers:
  - arch/x86/kernel/apic/x2apic_phys.c:__x2apic_send_IPI_mask
  - arch/x86/kernel/apic/x2apic_phys.c:x2apic_send_IPI
Direct callers:
  - arch/x86/kernel/apic/x2apic_cluster.c:__x2apic_send_IPI_mask
  - arch/x86/kernel/apic/x2apic_cluster.c:x2apic_send_IPI
```
**Symbols:**

```
ffffffff8105d210-ffffffff8105d254: __x2apic_send_IPI_dest (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
void __x2apic_send_IPI_dest(unsigned int apicid, int vector, unsigned int dest);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/x2apic_phys.c (ffffffff8106d1bf)
Location: arch/x86/kernel/apic/x2apic_phys.c:109
Inline: True
Inline callers:
  - arch/x86/kernel/apic/x2apic_phys.c:__x2apic_send_IPI_mask
  - arch/x86/kernel/apic/x2apic_phys.c:x2apic_send_IPI
Direct callers:
  - arch/x86/kernel/apic/x2apic_cluster.c:__x2apic_send_IPI_mask
  - arch/x86/kernel/apic/x2apic_cluster.c:x2apic_send_IPI
```
**Symbols:**

```
ffffffff8106d2e0-ffffffff8106d316: __x2apic_send_IPI_dest (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
void __x2apic_send_IPI_dest(unsigned int apicid, int vector, unsigned int dest);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/x2apic_phys.c (ffffffff8106f43f)
Location: arch/x86/kernel/apic/x2apic_phys.c:109
Inline: True
Inline callers:
  - arch/x86/kernel/apic/x2apic_phys.c:__x2apic_send_IPI_mask
  - arch/x86/kernel/apic/x2apic_phys.c:x2apic_send_IPI
Direct callers:
  - arch/x86/kernel/apic/x2apic_cluster.c:__x2apic_send_IPI_mask
  - arch/x86/kernel/apic/x2apic_cluster.c:x2apic_send_IPI
```
**Symbols:**

```
ffffffff8106f560-ffffffff8106f596: __x2apic_send_IPI_dest (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
