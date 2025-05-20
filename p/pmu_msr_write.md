# Function: <code>pmu_msr_write</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
bool pmu_msr_write(unsigned int msr, uint32_t low, uint32_t high, int *err);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/xen/pmu.c (ffffffff81026160)
Location: arch/x86/xen/pmu.c:306
Inline: False
Direct callers:
  - arch/x86/xen/enlighten.c:xen_write_msr_safe
```
**Symbols:**

```
ffffffff81026160-ffffffff8102625e: pmu_msr_write (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
bool pmu_msr_write(unsigned int msr, uint32_t low, uint32_t high, int *err);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/xen/pmu.c (ffffffff810255b0)
Location: arch/x86/xen/pmu.c:306
Inline: False
Direct callers:
  - arch/x86/xen/enlighten.c:xen_write_msr_safe
```
**Symbols:**

```
ffffffff810255b0-ffffffff810256d9: pmu_msr_write (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
bool pmu_msr_write(unsigned int msr, uint32_t low, uint32_t high, int *err);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/xen/pmu.c (ffffffff81025cd0)
Location: arch/x86/xen/pmu.c:306
Inline: False
Direct callers:
  - arch/x86/xen/enlighten.c:xen_write_msr_safe
```
**Symbols:**

```
ffffffff81025cd0-ffffffff81025df9: pmu_msr_write (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
bool pmu_msr_write(unsigned int msr, uint32_t low, uint32_t high, int *err);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/xen/pmu.c (ffffffff8101c640)
Location: arch/x86/xen/pmu.c:306
Inline: False
Direct callers:
  - arch/x86/xen/enlighten_pv.c:xen_write_msr_safe
```
**Symbols:**

```
ffffffff8101c640-ffffffff8101c75e: pmu_msr_write (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
bool pmu_msr_write(unsigned int msr, uint32_t low, uint32_t high, int *err);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/xen/pmu.c (ffffffff8101d2e0)
Location: arch/x86/xen/pmu.c:307
Inline: False
Direct callers:
  - arch/x86/xen/enlighten_pv.c:xen_write_msr_safe
```
**Symbols:**

```
ffffffff8101d2e0-ffffffff8101d3fe: pmu_msr_write (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
bool pmu_msr_write(unsigned int msr, uint32_t low, uint32_t high, int *err);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/xen/pmu.c (ffffffff8101dca0)
Location: arch/x86/xen/pmu.c:307
Inline: False
Direct callers:
  - arch/x86/xen/enlighten_pv.c:xen_write_msr_safe
```
**Symbols:**

```
ffffffff8101dca0-ffffffff8101ddd0: pmu_msr_write (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
bool pmu_msr_write(unsigned int msr, uint32_t low, uint32_t high, int *err);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/xen/pmu.c (ffffffff8101d520)
Location: arch/x86/xen/pmu.c:314
Inline: False
Direct callers:
  - arch/x86/xen/enlighten_pv.c:xen_write_msr_safe
```
**Symbols:**

```
ffffffff8101d520-ffffffff8101d646: pmu_msr_write (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
bool pmu_msr_write(unsigned int msr, uint32_t low, uint32_t high, int *err);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/xen/pmu.c (ffffffff8101f0a0)
Location: arch/x86/xen/pmu.c:314
Inline: False
Direct callers:
  - arch/x86/xen/enlighten_pv.c:xen_write_msr_safe
```
**Symbols:**

```
ffffffff8101f0a0-ffffffff8101f1c4: pmu_msr_write (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
bool pmu_msr_write(unsigned int msr, uint32_t low, uint32_t high, int *err);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/xen/pmu.c (ffffffff8101fa00)
Location: arch/x86/xen/pmu.c:314
Inline: False
Direct callers:
  - arch/x86/xen/enlighten_pv.c:xen_write_msr_safe
```
**Symbols:**

```
ffffffff8101fa00-ffffffff8101fb24: pmu_msr_write (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
bool pmu_msr_write(unsigned int msr, uint32_t low, uint32_t high, int *err);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/xen/pmu.c (ffffffff81022110)
Location: arch/x86/xen/pmu.c:314
Inline: False
Direct callers:
  - arch/x86/xen/enlighten_pv.c:xen_write_msr_safe
```
**Symbols:**

```
ffffffff81022110-ffffffff81022234: pmu_msr_write (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
bool pmu_msr_write(unsigned int msr, uint32_t low, uint32_t high, int *err);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/xen/pmu.c (ffffffff810227f0)
Location: arch/x86/xen/pmu.c:314
Inline: False
Direct callers:
  - arch/x86/xen/enlighten_pv.c:xen_write_msr_safe
```
**Symbols:**

```
ffffffff810227f0-ffffffff81022914: pmu_msr_write (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
bool pmu_msr_write(unsigned int msr, uint32_t low, uint32_t high, int *err);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/xen/pmu.c (ffffffff81024a70)
Location: arch/x86/xen/pmu.c:314
Inline: False
Direct callers:
  - arch/x86/xen/enlighten_pv.c:xen_write_msr_safe
```
**Symbols:**

```
ffffffff81024a70-ffffffff81024b94: pmu_msr_write (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
bool pmu_msr_write(unsigned int msr, uint32_t low, uint32_t high, int *err);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/xen/pmu.c (ffffffff81028eb0)
Location: arch/x86/xen/pmu.c:314
Inline: False
Direct callers:
  - arch/x86/xen/enlighten_pv.c:xen_write_msr_safe
```
**Symbols:**

```
ffffffff81028eb0-ffffffff81028fd1: pmu_msr_write (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
bool pmu_msr_write(unsigned int msr, uint32_t low, uint32_t high, int *err);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/xen/pmu.c (ffffffff8102d740)
Location: arch/x86/xen/pmu.c:314
Inline: False
Direct callers:
  - arch/x86/xen/enlighten_pv.c:xen_write_msr_safe
```
**Symbols:**

```
ffffffff8102d740-ffffffff8102d866: pmu_msr_write (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
bool pmu_msr_write(unsigned int msr, uint32_t low, uint32_t high, int *err);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/xen/pmu.c (0)
Location: arch/x86/xen/pmu.c:332
Inline: False
Direct callers:
  - arch/x86/xen/enlighten_pv.c:xen_do_write_msr
```
**Symbols:**

```
ffffffff8205198f-ffffffff820519aa: pmu_msr_write.cold (STB_LOCAL)
ffffffff81034ae0-ffffffff81034bcc: pmu_msr_write (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
bool pmu_msr_write(unsigned int msr, uint32_t low, uint32_t high, int *err);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/xen/pmu.c (0)
Location: arch/x86/xen/pmu.c:332
Inline: False
Direct callers:
  - arch/x86/xen/enlighten_pv.c:xen_do_write_msr
```
**Symbols:**

```
ffffffff820cfe7b-ffffffff820cfe96: pmu_msr_write.cold (STB_LOCAL)
ffffffff81034a60-ffffffff81034b4c: pmu_msr_write (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
bool pmu_msr_write(unsigned int msr, uint32_t low, uint32_t high, int *err);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/xen/pmu.c (0)
Location: arch/x86/xen/pmu.c:332
Inline: False
Direct callers:
  - arch/x86/xen/enlighten_pv.c:xen_do_write_msr
```
**Symbols:**

```
ffffffff821aa7e8-ffffffff821aa803: pmu_msr_write.cold (STB_LOCAL)
ffffffff8103ac60-ffffffff8103ad4c: pmu_msr_write (STB_GLOBAL)
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
bool pmu_msr_write(unsigned int msr, uint32_t low, uint32_t high, int *err);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/xen/pmu.c (ffffffff8101fb60)
Location: arch/x86/xen/pmu.c:314
Inline: False
Direct callers:
  - arch/x86/xen/enlighten_pv.c:xen_write_msr_safe
```
**Symbols:**

```
ffffffff8101fb60-ffffffff8101fc84: pmu_msr_write (STB_GLOBAL)
```
</details>
</li>
<li>
In <code>azure</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
bool pmu_msr_write(unsigned int msr, uint32_t low, uint32_t high, int *err);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/xen/pmu.c (ffffffff8101f9c0)
Location: arch/x86/xen/pmu.c:314
Inline: False
Direct callers:
  - arch/x86/xen/enlighten_pv.c:xen_write_msr_safe
```
**Symbols:**

```
ffffffff8101f9c0-ffffffff8101fae4: pmu_msr_write (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
bool pmu_msr_write(unsigned int msr, uint32_t low, uint32_t high, int *err);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/xen/pmu.c (ffffffff8101fc10)
Location: arch/x86/xen/pmu.c:314
Inline: False
Direct callers:
  - arch/x86/xen/enlighten_pv.c:xen_write_msr_safe
```
**Symbols:**

```
ffffffff8101fc10-ffffffff8101fd34: pmu_msr_write (STB_GLOBAL)
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
