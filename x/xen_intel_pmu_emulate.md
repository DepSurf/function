# Function: <code>xen_intel_pmu_emulate</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
bool xen_intel_pmu_emulate(unsigned int msr, u64 *val, int type, int index, bool is_read);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/xen/pmu.c (ffffffff81025c20)
Location: arch/x86/xen/pmu.c:181
Inline: False
Direct callers:
  - arch/x86/xen/pmu.c:pmu_msr_read
  - arch/x86/xen/pmu.c:pmu_msr_write
```
**Symbols:**

```
ffffffff81025c20-ffffffff81025d1a: xen_intel_pmu_emulate (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
bool xen_intel_pmu_emulate(unsigned int msr, u64 *val, int type, int index, bool is_read);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/xen/pmu.c (ffffffff81025010)
Location: arch/x86/xen/pmu.c:181
Inline: False
Direct callers:
  - arch/x86/xen/pmu.c:pmu_msr_write
  - arch/x86/xen/pmu.c:pmu_msr_read
```
**Symbols:**

```
ffffffff81025010-ffffffff81025129: xen_intel_pmu_emulate (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
bool xen_intel_pmu_emulate(unsigned int msr, u64 *val, int type, int index, bool is_read);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/xen/pmu.c (ffffffff81025730)
Location: arch/x86/xen/pmu.c:181
Inline: False
Direct callers:
  - arch/x86/xen/pmu.c:pmu_msr_write
  - arch/x86/xen/pmu.c:pmu_msr_read
```
**Symbols:**

```
ffffffff81025730-ffffffff81025849: xen_intel_pmu_emulate (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
bool xen_intel_pmu_emulate(unsigned int msr, u64 *val, int type, int index, bool is_read);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/xen/pmu.c (ffffffff8101c0e0)
Location: arch/x86/xen/pmu.c:181
Inline: False
Direct callers:
  - arch/x86/xen/pmu.c:pmu_msr_write
  - arch/x86/xen/pmu.c:pmu_msr_read
```
**Symbols:**

```
ffffffff8101c0e0-ffffffff8101c1e8: xen_intel_pmu_emulate (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
bool xen_intel_pmu_emulate(unsigned int msr, u64 *val, int type, int index, bool is_read);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/xen/pmu.c (ffffffff8101cd60)
Location: arch/x86/xen/pmu.c:182
Inline: False
Direct callers:
  - arch/x86/xen/pmu.c:pmu_msr_write
  - arch/x86/xen/pmu.c:pmu_msr_read
```
**Symbols:**

```
ffffffff8101cd60-ffffffff8101ce68: xen_intel_pmu_emulate (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
bool xen_intel_pmu_emulate(unsigned int msr, u64 *val, int type, int index, bool is_read);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/xen/pmu.c (ffffffff8101d770)
Location: arch/x86/xen/pmu.c:182
Inline: False
Direct callers:
  - arch/x86/xen/pmu.c:pmu_msr_write
  - arch/x86/xen/pmu.c:pmu_msr_read
```
**Symbols:**

```
ffffffff8101d770-ffffffff8101d876: xen_intel_pmu_emulate (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
bool xen_intel_pmu_emulate(unsigned int msr, u64 *val, int type, int index, bool is_read);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/xen/pmu.c (ffffffff8101d000)
Location: arch/x86/xen/pmu.c:189
Inline: False
Direct callers:
  - arch/x86/xen/pmu.c:pmu_msr_write
  - arch/x86/xen/pmu.c:pmu_msr_read
```
**Symbols:**

```
ffffffff8101d000-ffffffff8101d106: xen_intel_pmu_emulate (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
bool xen_intel_pmu_emulate(unsigned int msr, u64 *val, int type, int index, bool is_read);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/xen/pmu.c (ffffffff8101eb50)
Location: arch/x86/xen/pmu.c:189
Inline: False
Direct callers:
  - arch/x86/xen/pmu.c:pmu_msr_write
  - arch/x86/xen/pmu.c:pmu_msr_read
```
**Symbols:**

```
ffffffff8101eb50-ffffffff8101ec5d: xen_intel_pmu_emulate (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
bool xen_intel_pmu_emulate(unsigned int msr, u64 *val, int type, int index, bool is_read);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/xen/pmu.c (ffffffff8101f4b0)
Location: arch/x86/xen/pmu.c:189
Inline: False
Direct callers:
  - arch/x86/xen/pmu.c:pmu_msr_write
  - arch/x86/xen/pmu.c:pmu_msr_read
```
**Symbols:**

```
ffffffff8101f4b0-ffffffff8101f5bd: xen_intel_pmu_emulate (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
bool xen_intel_pmu_emulate(unsigned int msr, u64 *val, int type, int index, bool is_read);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/xen/pmu.c (ffffffff81021ab0)
Location: arch/x86/xen/pmu.c:189
Inline: False
Direct callers:
  - arch/x86/xen/pmu.c:pmu_msr_write
  - arch/x86/xen/pmu.c:pmu_msr_read
```
**Symbols:**

```
ffffffff81021ab0-ffffffff81021bc7: xen_intel_pmu_emulate (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
bool xen_intel_pmu_emulate(unsigned int msr, u64 *val, int type, int index, bool is_read);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/xen/pmu.c (ffffffff81022190)
Location: arch/x86/xen/pmu.c:189
Inline: False
Direct callers:
  - arch/x86/xen/pmu.c:pmu_msr_write
  - arch/x86/xen/pmu.c:pmu_msr_read
```
**Symbols:**

```
ffffffff81022190-ffffffff810222a7: xen_intel_pmu_emulate (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
bool xen_intel_pmu_emulate(unsigned int msr, u64 *val, int type, int index, bool is_read);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/xen/pmu.c (ffffffff81024520)
Location: arch/x86/xen/pmu.c:189
Inline: False
Direct callers:
  - arch/x86/xen/pmu.c:pmu_msr_write
  - arch/x86/xen/pmu.c:pmu_msr_read
```
**Symbols:**

```
ffffffff81024520-ffffffff81024636: xen_intel_pmu_emulate (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
bool xen_intel_pmu_emulate(unsigned int msr, u64 *val, int type, int index, bool is_read);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/xen/pmu.c (ffffffff81028920)
Location: arch/x86/xen/pmu.c:189
Inline: False
Direct callers:
  - arch/x86/xen/pmu.c:pmu_msr_write
  - arch/x86/xen/pmu.c:pmu_msr_read
```
**Symbols:**

```
ffffffff81028920-ffffffff81028a36: xen_intel_pmu_emulate (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
bool xen_intel_pmu_emulate(unsigned int msr, u64 *val, int type, int index, bool is_read);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/xen/pmu.c (ffffffff8102d1a0)
Location: arch/x86/xen/pmu.c:189
Inline: False
Direct callers:
  - arch/x86/xen/pmu.c:pmu_msr_write
  - arch/x86/xen/pmu.c:pmu_msr_read
```
**Symbols:**

```
ffffffff8102d1a0-ffffffff8102d353: xen_intel_pmu_emulate (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/xen/pmu.c (ffffffff81034744)
Location: arch/x86/xen/pmu.c:198
Inline: True
Inline callers:
  - arch/x86/xen/pmu.c:pmu_msr_chk_emulated
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/xen/pmu.c (ffffffff81034646)
Location: arch/x86/xen/pmu.c:198
Inline: True
Inline callers:
  - arch/x86/xen/pmu.c:pmu_msr_chk_emulated
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/xen/pmu.c (ffffffff8103a846)
Location: arch/x86/xen/pmu.c:198
Inline: True
Inline callers:
  - arch/x86/xen/pmu.c:pmu_msr_chk_emulated
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
bool xen_intel_pmu_emulate(unsigned int msr, u64 *val, int type, int index, bool is_read);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/xen/pmu.c (ffffffff8101f610)
Location: arch/x86/xen/pmu.c:189
Inline: False
Direct callers:
  - arch/x86/xen/pmu.c:pmu_msr_write
  - arch/x86/xen/pmu.c:pmu_msr_read
```
**Symbols:**

```
ffffffff8101f610-ffffffff8101f71d: xen_intel_pmu_emulate (STB_LOCAL)
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
bool xen_intel_pmu_emulate(unsigned int msr, u64 *val, int type, int index, bool is_read);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/xen/pmu.c (ffffffff8101f470)
Location: arch/x86/xen/pmu.c:189
Inline: False
Direct callers:
  - arch/x86/xen/pmu.c:pmu_msr_write
  - arch/x86/xen/pmu.c:pmu_msr_read
```
**Symbols:**

```
ffffffff8101f470-ffffffff8101f57d: xen_intel_pmu_emulate (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
bool xen_intel_pmu_emulate(unsigned int msr, u64 *val, int type, int index, bool is_read);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/xen/pmu.c (ffffffff8101f6c0)
Location: arch/x86/xen/pmu.c:189
Inline: False
Direct callers:
  - arch/x86/xen/pmu.c:pmu_msr_write
  - arch/x86/xen/pmu.c:pmu_msr_read
```
**Symbols:**

```
ffffffff8101f6c0-ffffffff8101f7cd: xen_intel_pmu_emulate (STB_LOCAL)
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
