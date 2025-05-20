# Function: <code>pmu_apic_update</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int pmu_apic_update(uint32_t val);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/xen/pmu.c (ffffffff81026350)
Location: arch/x86/xen/pmu.c:387
Inline: False
Direct callers:
  - arch/x86/xen/apic.c:xen_apic_write
```
**Symbols:**

```
ffffffff81026350-ffffffff810263c3: pmu_apic_update (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int pmu_apic_update(uint32_t val);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/xen/pmu.c (ffffffff810257f0)
Location: arch/x86/xen/pmu.c:387
Inline: False
Direct callers:
  - arch/x86/xen/apic.c:xen_apic_write
```
**Symbols:**

```
ffffffff810257f0-ffffffff81025865: pmu_apic_update (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int pmu_apic_update(uint32_t val);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/xen/pmu.c (ffffffff81025f10)
Location: arch/x86/xen/pmu.c:387
Inline: False
Direct callers:
  - arch/x86/xen/apic.c:xen_apic_write
```
**Symbols:**

```
ffffffff81025f10-ffffffff81025f85: pmu_apic_update (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int pmu_apic_update(uint32_t val);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/xen/pmu.c (ffffffff8101c870)
Location: arch/x86/xen/pmu.c:387
Inline: False
```
**Symbols:**

```
ffffffff8101c870-ffffffff8101c8e5: pmu_apic_update (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int pmu_apic_update(uint32_t val);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/xen/pmu.c (ffffffff8101d510)
Location: arch/x86/xen/pmu.c:388
Inline: False
```
**Symbols:**

```
ffffffff8101d510-ffffffff8101d585: pmu_apic_update (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Transformation ⚠️</summary>

```c
int pmu_apic_update(uint32_t val);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/xen/pmu.c (0)
Location: arch/x86/xen/pmu.c:388
Inline: False
Direct callers:
  - arch/x86/xen/apic.c:xen_apic_write
```
**Symbols:**

```
ffffffff8101e404-ffffffff8101e428: pmu_apic_update.cold.7 (STB_LOCAL)
ffffffff8101dee0-ffffffff8101df38: pmu_apic_update (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Transformation ⚠️</summary>

```c
int pmu_apic_update(uint32_t val);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/xen/pmu.c (0)
Location: arch/x86/xen/pmu.c:395
Inline: False
Direct callers:
  - arch/x86/xen/apic.c:xen_apic_write
```
**Symbols:**

```
ffffffff8101dc94-ffffffff8101dcb8: pmu_apic_update.cold.7 (STB_LOCAL)
ffffffff8101d760-ffffffff8101d7b8: pmu_apic_update (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
int pmu_apic_update(uint32_t val);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/xen/pmu.c (0)
Location: arch/x86/xen/pmu.c:395
Inline: False
Direct callers:
  - arch/x86/xen/apic.c:xen_apic_write
```
**Symbols:**

```
ffffffff8101f836-ffffffff8101f85a: pmu_apic_update.cold (STB_LOCAL)
ffffffff8101f2f0-ffffffff8101f348: pmu_apic_update (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
int pmu_apic_update(uint32_t val);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/xen/pmu.c (0)
Location: arch/x86/xen/pmu.c:395
Inline: False
Direct callers:
  - arch/x86/xen/apic.c:xen_apic_write
```
**Symbols:**

```
ffffffff81020196-ffffffff810201ba: pmu_apic_update.cold (STB_LOCAL)
ffffffff8101fc50-ffffffff8101fca8: pmu_apic_update (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
int pmu_apic_update(uint32_t val);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/xen/pmu.c (0)
Location: arch/x86/xen/pmu.c:395
Inline: False
Direct callers:
  - arch/x86/xen/apic.c:xen_apic_write
```
**Symbols:**

```
ffffffff810227e6-ffffffff8102280b: pmu_apic_update.cold (STB_LOCAL)
ffffffff81022370-ffffffff810223d0: pmu_apic_update (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
int pmu_apic_update(uint32_t val);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/xen/pmu.c (0)
Location: arch/x86/xen/pmu.c:395
Inline: False
Direct callers:
  - arch/x86/xen/apic.c:xen_apic_write
```
**Symbols:**

```
ffffffff81bd2a96-ffffffff81bd2abb: pmu_apic_update.cold (STB_LOCAL)
ffffffff81022a50-ffffffff81022ab0: pmu_apic_update (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
int pmu_apic_update(uint32_t val);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/xen/pmu.c (0)
Location: arch/x86/xen/pmu.c:395
Inline: False
Direct callers:
  - arch/x86/xen/apic.c:xen_apic_write
```
**Symbols:**

```
ffffffff81bc4c37-ffffffff81bc4c5b: pmu_apic_update.cold (STB_LOCAL)
ffffffff81024cb0-ffffffff81024d08: pmu_apic_update (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int pmu_apic_update(uint32_t val);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/xen/pmu.c (0)
Location: arch/x86/xen/pmu.c:395
Inline: False
Direct callers:
  - arch/x86/xen/apic.c:xen_apic_write
```
**Symbols:**

```
ffffffff81c9737d-ffffffff81c973b5: pmu_apic_update.cold (STB_LOCAL)
ffffffff810290f0-ffffffff81029159: pmu_apic_update (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int pmu_apic_update(uint32_t val);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/xen/pmu.c (0)
Location: arch/x86/xen/pmu.c:395
Inline: False
```
**Symbols:**

```
ffffffff81e467fc-ffffffff81e46810: pmu_apic_update.cold (STB_LOCAL)
ffffffff8102d9d0-ffffffff8102da56: pmu_apic_update (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
int pmu_apic_update(uint32_t val);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/xen/pmu.c (0)
Location: arch/x86/xen/pmu.c:408
Inline: False
```
**Symbols:**

```
ffffffff820519aa-ffffffff820519be: pmu_apic_update.cold (STB_LOCAL)
ffffffff81034d50-ffffffff81034dd6: pmu_apic_update (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
int pmu_apic_update(uint32_t val);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/xen/pmu.c (0)
Location: arch/x86/xen/pmu.c:408
Inline: False
```
**Symbols:**

```
ffffffff820cfe96-ffffffff820cfeaa: pmu_apic_update.cold (STB_LOCAL)
ffffffff81034cd0-ffffffff81034d56: pmu_apic_update (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
int pmu_apic_update(uint32_t val);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/xen/pmu.c (0)
Location: arch/x86/xen/pmu.c:408
Inline: False
```
**Symbols:**

```
ffffffff821aa803-ffffffff821aa817: pmu_apic_update.cold (STB_LOCAL)
ffffffff8103aed0-ffffffff8103af56: pmu_apic_update (STB_GLOBAL)
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
int pmu_apic_update(uint32_t val);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/xen/pmu.c (0)
Location: arch/x86/xen/pmu.c:395
Inline: False
Direct callers:
  - arch/x86/xen/apic.c:xen_apic_write
```
**Symbols:**

```
ffffffff810202f6-ffffffff8102031a: pmu_apic_update.cold (STB_LOCAL)
ffffffff8101fdb0-ffffffff8101fe08: pmu_apic_update (STB_GLOBAL)
```
</details>
</li>
<li>
In <code>azure</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>gcp</code>: Transformation ⚠️</summary>

```c
int pmu_apic_update(uint32_t val);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/xen/pmu.c (0)
Location: arch/x86/xen/pmu.c:395
Inline: False
Direct callers:
  - arch/x86/xen/apic.c:xen_apic_write
```
**Symbols:**

```
ffffffff81020156-ffffffff8102017a: pmu_apic_update.cold (STB_LOCAL)
ffffffff8101fc10-ffffffff8101fc68: pmu_apic_update (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
int pmu_apic_update(uint32_t val);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/xen/pmu.c (0)
Location: arch/x86/xen/pmu.c:395
Inline: False
Direct callers:
  - arch/x86/xen/apic.c:xen_apic_write
```
**Symbols:**

```
ffffffff810203a6-ffffffff810203ca: pmu_apic_update.cold (STB_LOCAL)
ffffffff8101fe60-ffffffff8101feb8: pmu_apic_update (STB_GLOBAL)
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
No changes between <code>generic</code> and <code>gcp</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>lowlatency</code> ✅
</li>
</ul>
