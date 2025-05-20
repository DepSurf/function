# Function: <code>sld_state_setup</code>

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
In <code>5.0</code>: Absent ⚠️
</li>
<li>
In <code>5.3</code>: Absent ⚠️
</li>
<li>
In <code>5.4</code>: Absent ⚠️
</li>
<li>
In <code>5.8</code>: Absent ⚠️
</li>
<li>
In <code>5.11</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>5.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/intel.c (ffffffff831cb763)
Location: arch/x86/kernel/cpu/intel.c:1025
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/intel.c:sld_setup
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void sld_state_setup();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/intel.c (ffffffff832acdb3)
Location: arch/x86/kernel/cpu/intel.c:1046
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/intel.c:sld_setup
```
**Symbols:**

```
ffffffff832acdb3-ffffffff832acf1d: sld_state_setup (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void sld_state_setup();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/intel.c (ffffffff8345db58)
Location: arch/x86/kernel/cpu/intel.c:1076
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/intel.c:sld_setup
```
**Symbols:**

```
ffffffff8345db58-ffffffff8345dce5: sld_state_setup (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void sld_state_setup();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/intel.c (ffffffff83e7eb00)
Location: arch/x86/kernel/cpu/intel.c:1242
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/intel.c:sld_setup
```
**Symbols:**

```
ffffffff83e7eb00-ffffffff83e7ecbd: sld_state_setup (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void sld_state_setup();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/intel.c (ffffffff836a1860)
Location: arch/x86/kernel/cpu/intel.c:1242
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/intel.c:sld_setup
```
**Symbols:**

```
ffffffff836a1860-ffffffff836a1a1d: sld_state_setup (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void sld_state_setup();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/intel.c (ffffffff838d1960)
Location: arch/x86/kernel/cpu/intel.c:1058
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/intel.c:sld_setup
```
**Symbols:**

```
ffffffff838d1960-ffffffff838d1b1d: sld_state_setup (STB_LOCAL)
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
In <code>aws</code>: Absent ⚠️
</li>
<li>
In <code>azure</code>: Absent ⚠️
</li>
<li>
In <code>gcp</code>: Absent ⚠️
</li>
<li>
In <code>lowlatency</code>: Absent ⚠️
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
