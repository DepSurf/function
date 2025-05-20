# Function: <code>mbm_handle_overflow</code>

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
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void mbm_handle_overflow(struct work_struct *work);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/intel_rdt_monitor.c (ffffffff81044660)
Location: arch/x86/kernel/cpu/intel_rdt_monitor.c:365
Inline: False
```
**Symbols:**

```
ffffffff81044660-ffffffff8104473d: mbm_handle_overflow (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void mbm_handle_overflow(struct work_struct *work);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/intel_rdt_monitor.c (ffffffff81047e30)
Location: arch/x86/kernel/cpu/intel_rdt_monitor.c:365
Inline: False
```
**Symbols:**

```
ffffffff81047e30-ffffffff81047f0d: mbm_handle_overflow (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Transformation ⚠️</summary>

```c
void mbm_handle_overflow(struct work_struct *work);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/cpu/intel_rdt_monitor.c (0)
Location: arch/x86/kernel/cpu/intel_rdt_monitor.c:518
Inline: False
```
**Symbols:**

```
ffffffff8104a99e-ffffffff8104a9b6: mbm_handle_overflow.cold.10 (STB_LOCAL)
ffffffff8104a500-ffffffff8104a77f: mbm_handle_overflow (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Transformation ⚠️</summary>

```c
void mbm_handle_overflow(struct work_struct *work);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/cpu/resctrl/monitor.c (0)
Location: arch/x86/kernel/cpu/resctrl/monitor.c:515
Inline: False
```
**Symbols:**

```
ffffffff8105ad1e-ffffffff8105ad36: mbm_handle_overflow.cold.11 (STB_LOCAL)
ffffffff8105a880-ffffffff8105aaff: mbm_handle_overflow (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
void mbm_handle_overflow(struct work_struct *work);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/cpu/resctrl/monitor.c (0)
Location: arch/x86/kernel/cpu/resctrl/monitor.c:507
Inline: False
```
**Symbols:**

```
ffffffff8105e063-ffffffff8105e07b: mbm_handle_overflow.cold (STB_LOCAL)
ffffffff8105db70-ffffffff8105ddfa: mbm_handle_overflow (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
void mbm_handle_overflow(struct work_struct *work);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/cpu/resctrl/monitor.c (0)
Location: arch/x86/kernel/cpu/resctrl/monitor.c:507
Inline: False
```
**Symbols:**

```
ffffffff8105e8f1-ffffffff8105e909: mbm_handle_overflow.cold (STB_LOCAL)
ffffffff8105e430-ffffffff8105e6ba: mbm_handle_overflow (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void mbm_handle_overflow(struct work_struct *work);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/resctrl/monitor.c (ffffffff810640d0)
Location: arch/x86/kernel/cpu/resctrl/monitor.c:508
Inline: False
```
**Symbols:**

```
ffffffff810640d0-ffffffff810641c5: mbm_handle_overflow (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void mbm_handle_overflow(struct work_struct *work);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/resctrl/monitor.c (ffffffff810624e0)
Location: arch/x86/kernel/cpu/resctrl/monitor.c:563
Inline: False
```
**Symbols:**

```
ffffffff810624e0-ffffffff810625c4: mbm_handle_overflow (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void mbm_handle_overflow(struct work_struct *work);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/resctrl/monitor.c (ffffffff81062c50)
Location: arch/x86/kernel/cpu/resctrl/monitor.c:562
Inline: False
```
**Symbols:**

```
ffffffff81062c50-ffffffff81062d34: mbm_handle_overflow (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void mbm_handle_overflow(struct work_struct *work);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/resctrl/monitor.c (ffffffff8106cae0)
Location: arch/x86/kernel/cpu/resctrl/monitor.c:577
Inline: False
```
**Symbols:**

```
ffffffff8106cae0-ffffffff8106cbc4: mbm_handle_overflow (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void mbm_handle_overflow(struct work_struct *work);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/resctrl/monitor.c (ffffffff81079f90)
Location: arch/x86/kernel/cpu/resctrl/monitor.c:577
Inline: False
```
**Symbols:**

```
ffffffff81079f90-ffffffff8107a082: mbm_handle_overflow (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void mbm_handle_overflow(struct work_struct *work);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/resctrl/monitor.c (ffffffff8108b080)
Location: arch/x86/kernel/cpu/resctrl/monitor.c:658
Inline: False
```
**Symbols:**

```
ffffffff8108b080-ffffffff8108b172: mbm_handle_overflow (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void mbm_handle_overflow(struct work_struct *work);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/resctrl/monitor.c (ffffffff8108e120)
Location: arch/x86/kernel/cpu/resctrl/monitor.c:670
Inline: False
```
**Symbols:**

```
ffffffff8108e120-ffffffff8108e212: mbm_handle_overflow (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void mbm_handle_overflow(struct work_struct *work);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/resctrl/monitor.c (ffffffff810954b0)
Location: arch/x86/kernel/cpu/resctrl/monitor.c:670
Inline: False
```
**Symbols:**

```
ffffffff810954b0-ffffffff810955a2: mbm_handle_overflow (STB_GLOBAL)
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
void mbm_handle_overflow(struct work_struct *work);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/cpu/resctrl/monitor.c (0)
Location: arch/x86/kernel/cpu/resctrl/monitor.c:507
Inline: False
```
**Symbols:**

```
ffffffff8105e471-ffffffff8105e489: mbm_handle_overflow.cold (STB_LOCAL)
ffffffff8105dfb0-ffffffff8105e23a: mbm_handle_overflow (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Transformation ⚠️</summary>

```c
void mbm_handle_overflow(struct work_struct *work);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/cpu/resctrl/monitor.c (0)
Location: arch/x86/kernel/cpu/resctrl/monitor.c:507
Inline: False
```
**Symbols:**

```
ffffffff8104e7a1-ffffffff8104e7b9: mbm_handle_overflow.cold (STB_LOCAL)
ffffffff8104e2c0-ffffffff8104e565: mbm_handle_overflow (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Transformation ⚠️</summary>

```c
void mbm_handle_overflow(struct work_struct *work);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/cpu/resctrl/monitor.c (0)
Location: arch/x86/kernel/cpu/resctrl/monitor.c:507
Inline: False
```
**Symbols:**

```
ffffffff8105e8a1-ffffffff8105e8b9: mbm_handle_overflow.cold (STB_LOCAL)
ffffffff8105e3e0-ffffffff8105e66a: mbm_handle_overflow (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
void mbm_handle_overflow(struct work_struct *work);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/cpu/resctrl/monitor.c (0)
Location: arch/x86/kernel/cpu/resctrl/monitor.c:507
Inline: False
```
**Symbols:**

```
ffffffff8105fde1-ffffffff8105fdf9: mbm_handle_overflow.cold (STB_LOCAL)
ffffffff8105f920-ffffffff8105fbaa: mbm_handle_overflow (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
