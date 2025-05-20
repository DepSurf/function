# Function: <code>acpi_register_lapic</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline ⚠️</summary>

```c
int acpi_register_lapic(int id, u8 enabled);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/acpi/boot.c (ffffffff8104f800)
Location: arch/x86/kernel/acpi/boot.c:168
Inline: True
Direct callers:
  - arch/x86/kernel/acpi/boot.c:acpi_map_cpu
  - arch/x86/kernel/acpi/boot.c:acpi_parse_x2apic
  - arch/x86/kernel/acpi/boot.c:acpi_parse_lapic
  - arch/x86/kernel/acpi/boot.c:acpi_parse_sapic
```
**Symbols:**

```
ffffffff8104f800-ffffffff8104f852: acpi_register_lapic (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
int acpi_register_lapic(int id, u32 acpiid, u8 enabled);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/acpi/boot.c (ffffffff8104f900)
Location: arch/x86/kernel/acpi/boot.c:169
Inline: True
Direct callers:
  - arch/x86/kernel/acpi/boot.c:acpi_map_cpu
  - arch/x86/kernel/acpi/boot.c:acpi_parse_sapic
  - arch/x86/kernel/acpi/boot.c:acpi_parse_lapic
  - arch/x86/kernel/acpi/boot.c:acpi_parse_x2apic
```
**Symbols:**

```
ffffffff8104f900-ffffffff8104f982: acpi_register_lapic (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int acpi_register_lapic(int id, u32 acpiid, u8 enabled);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/acpi/boot.c (ffffffff81051e60)
Location: arch/x86/kernel/acpi/boot.c:171
Inline: False
Direct callers:
  - arch/x86/kernel/acpi/boot.c:acpi_map_cpu
  - arch/x86/kernel/acpi/boot.c:acpi_parse_sapic
  - arch/x86/kernel/acpi/boot.c:acpi_parse_lapic
  - arch/x86/kernel/acpi/boot.c:acpi_parse_x2apic
```
**Symbols:**

```
ffffffff81051e60-ffffffff81051eda: acpi_register_lapic (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
int acpi_register_lapic(int id, u32 acpiid, u8 enabled);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/acpi/boot.c (ffffffff81051c40)
Location: arch/x86/kernel/acpi/boot.c:173
Inline: True
Direct callers:
  - arch/x86/kernel/acpi/boot.c:acpi_map_cpu
  - arch/x86/kernel/acpi/boot.c:acpi_parse_sapic
  - arch/x86/kernel/acpi/boot.c:acpi_parse_lapic
  - arch/x86/kernel/acpi/boot.c:acpi_parse_x2apic
```
**Symbols:**

```
ffffffff81051c40-ffffffff81051cc2: acpi_register_lapic (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
int acpi_register_lapic(int id, u32 acpiid, u8 enabled);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/acpi/boot.c (ffffffff810558b0)
Location: arch/x86/kernel/acpi/boot.c:173
Inline: True
Direct callers:
  - arch/x86/kernel/acpi/boot.c:acpi_map_cpu
  - arch/x86/kernel/acpi/boot.c:acpi_parse_sapic
  - arch/x86/kernel/acpi/boot.c:acpi_parse_lapic
  - arch/x86/kernel/acpi/boot.c:acpi_parse_x2apic
```
**Symbols:**

```
ffffffff810558b0-ffffffff81055932: acpi_register_lapic (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline, Transformation ⚠️</summary>

```c
int acpi_register_lapic(int id, u32 acpiid, u8 enabled);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/acpi/boot.c (0)
Location: arch/x86/kernel/acpi/boot.c:173
Inline: True
Direct callers:
  - arch/x86/kernel/acpi/boot.c:acpi_map_cpu
  - arch/x86/kernel/acpi/boot.c:acpi_parse_sapic
  - arch/x86/kernel/acpi/boot.c:acpi_parse_lapic
  - arch/x86/kernel/acpi/boot.c:acpi_parse_x2apic
```
**Symbols:**

```
ffffffff81058740-ffffffff810587b3: acpi_register_lapic (STB_LOCAL)
ffffffff81058a41-ffffffff81058a57: acpi_register_lapic.cold.6 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline, Transformation ⚠️</summary>

```c
int acpi_register_lapic(int id, u32 acpiid, u8 enabled);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/acpi/boot.c (ffffffff8105e3c5)
Location: arch/x86/kernel/acpi/boot.c:174
Inline: True
Direct callers:
  - arch/x86/kernel/acpi/boot.c:acpi_map_cpu
  - arch/x86/kernel/acpi/boot.c:acpi_parse_sapic
  - arch/x86/kernel/acpi/boot.c:acpi_parse_lapic
  - arch/x86/kernel/acpi/boot.c:acpi_parse_x2apic
```
**Symbols:**

```
ffffffff8105e360-ffffffff8105e3d3: acpi_register_lapic (STB_LOCAL)
ffffffff8105e682-ffffffff8105e698: acpi_register_lapic.cold.8 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline, Transformation ⚠️</summary>

```c
int acpi_register_lapic(int id, u32 acpiid, u8 enabled);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/acpi/boot.c (ffffffff810617d5)
Location: arch/x86/kernel/acpi/boot.c:157
Inline: True
Direct callers:
  - arch/x86/kernel/acpi/boot.c:acpi_map_cpu
  - arch/x86/kernel/acpi/boot.c:acpi_parse_sapic
  - arch/x86/kernel/acpi/boot.c:acpi_parse_lapic
  - arch/x86/kernel/acpi/boot.c:acpi_parse_x2apic
```
**Symbols:**

```
ffffffff81061770-ffffffff810617e3: acpi_register_lapic (STB_LOCAL)
ffffffff81061a82-ffffffff81061a98: acpi_register_lapic.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline, Transformation ⚠️</summary>

```c
int acpi_register_lapic(int id, u32 acpiid, u8 enabled);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/acpi/boot.c (ffffffff81062065)
Location: arch/x86/kernel/acpi/boot.c:157
Inline: True
Direct callers:
  - arch/x86/kernel/acpi/boot.c:acpi_map_cpu
  - arch/x86/kernel/acpi/boot.c:acpi_parse_sapic
  - arch/x86/kernel/acpi/boot.c:acpi_parse_lapic
  - arch/x86/kernel/acpi/boot.c:acpi_parse_x2apic
```
**Symbols:**

```
ffffffff81062000-ffffffff81062073: acpi_register_lapic (STB_LOCAL)
ffffffff81062332-ffffffff81062348: acpi_register_lapic.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
int acpi_register_lapic(int id, u32 acpiid, u8 enabled);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/acpi/boot.c (0)
Location: arch/x86/kernel/acpi/boot.c:158
Inline: False
Direct callers:
  - arch/x86/kernel/acpi/boot.c:acpi_map_cpu
  - arch/x86/kernel/acpi/boot.c:acpi_parse_sapic
  - arch/x86/kernel/acpi/boot.c:acpi_parse_lapic
  - arch/x86/kernel/acpi/boot.c:acpi_parse_x2apic
```
**Symbols:**

```
ffffffff81067cf0-ffffffff81067d66: acpi_register_lapic (STB_LOCAL)
ffffffff810682f2-ffffffff81068308: acpi_register_lapic.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
int acpi_register_lapic(int id, u32 acpiid, u8 enabled);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/acpi/boot.c (0)
Location: arch/x86/kernel/acpi/boot.c:158
Inline: False
Direct callers:
  - arch/x86/kernel/acpi/boot.c:acpi_map_cpu
  - arch/x86/kernel/acpi/boot.c:acpi_parse_sapic
  - arch/x86/kernel/acpi/boot.c:acpi_parse_lapic
  - arch/x86/kernel/acpi/boot.c:acpi_parse_x2apic
```
**Symbols:**

```
ffffffff810699f0-ffffffff81069a66: acpi_register_lapic (STB_LOCAL)
ffffffff81bd6666-ffffffff81bd667c: acpi_register_lapic.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
int acpi_register_lapic(int id, u32 acpiid, u8 enabled);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/acpi/boot.c (0)
Location: arch/x86/kernel/acpi/boot.c:158
Inline: False
Direct callers:
  - arch/x86/kernel/acpi/boot.c:acpi_map_cpu
  - arch/x86/kernel/acpi/boot.c:acpi_parse_sapic
  - arch/x86/kernel/acpi/boot.c:acpi_parse_lapic
  - arch/x86/kernel/acpi/boot.c:acpi_parse_x2apic
```
**Symbols:**

```
ffffffff8106a4d0-ffffffff8106a546: acpi_register_lapic (STB_LOCAL)
ffffffff81bc8918-ffffffff81bc892e: acpi_register_lapic.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int acpi_register_lapic(int id, u32 acpiid, u8 enabled);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/acpi/boot.c (0)
Location: arch/x86/kernel/acpi/boot.c:156
Inline: False
Direct callers:
  - arch/x86/kernel/acpi/boot.c:acpi_map_cpu
  - arch/x86/kernel/acpi/boot.c:acpi_parse_sapic
  - arch/x86/kernel/acpi/boot.c:acpi_parse_lapic
  - arch/x86/kernel/acpi/boot.c:acpi_parse_x2apic
```
**Symbols:**

```
ffffffff81074d10-ffffffff81074db7: acpi_register_lapic (STB_LOCAL)
ffffffff81c9d108-ffffffff81c9d11e: acpi_register_lapic.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int acpi_register_lapic(int id, u32 acpiid, u8 enabled);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/acpi/boot.c (0)
Location: arch/x86/kernel/acpi/boot.c:166
Inline: False
Direct callers:
  - arch/x86/kernel/acpi/boot.c:acpi_map_cpu
  - arch/x86/kernel/acpi/boot.c:acpi_parse_sapic
  - arch/x86/kernel/acpi/boot.c:acpi_parse_lapic
  - arch/x86/kernel/acpi/boot.c:acpi_parse_x2apic
```
**Symbols:**

```
ffffffff81083730-ffffffff810837e3: acpi_register_lapic (STB_LOCAL)
ffffffff81e4c501-ffffffff81e4c512: acpi_register_lapic.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int acpi_register_lapic(int id, u32 acpiid, u8 enabled);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/acpi/boot.c (ffffffff81096490)
Location: arch/x86/kernel/acpi/boot.c:166
Inline: False
Direct callers:
  - arch/x86/kernel/acpi/boot.c:acpi_map_cpu
  - arch/x86/kernel/acpi/boot.c:acpi_parse_sapic
  - arch/x86/kernel/acpi/boot.c:acpi_parse_lapic
  - arch/x86/kernel/acpi/boot.c:acpi_parse_x2apic
```
**Symbols:**

```
ffffffff81096490-ffffffff8109654d: acpi_register_lapic (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int acpi_register_lapic(int id, u32 acpiid, u8 enabled);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/acpi/boot.c (ffffffff810995b0)
Location: arch/x86/kernel/acpi/boot.c:171
Inline: False
Direct callers:
  - arch/x86/kernel/acpi/boot.c:acpi_map_cpu
  - arch/x86/kernel/acpi/boot.c:acpi_parse_sapic
  - arch/x86/kernel/acpi/boot.c:acpi_parse_lapic
  - arch/x86/kernel/acpi/boot.c:acpi_parse_x2apic
```
**Symbols:**

```
ffffffff810995b0-ffffffff8109966d: acpi_register_lapic (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int acpi_register_lapic(int id, u32 acpiid, u8 enabled);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/acpi/boot.c (ffffffff810a0df0)
Location: arch/x86/kernel/acpi/boot.c:175
Inline: False
Direct callers:
  - arch/x86/kernel/acpi/boot.c:acpi_map_cpu
  - arch/x86/kernel/acpi/boot.c:acpi_parse_sapic
  - arch/x86/kernel/acpi/boot.c:acpi_parse_lapic
  - arch/x86/kernel/acpi/boot.c:acpi_parse_x2apic
```
**Symbols:**

```
ffffffff810a0df0-ffffffff810a0e9b: acpi_register_lapic (STB_LOCAL)
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
<summary>In <code>aws</code>: Selective Inline, Transformation ⚠️</summary>

```c
int acpi_register_lapic(int id, u32 acpiid, u8 enabled);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/acpi/boot.c (ffffffff81061be5)
Location: arch/x86/kernel/acpi/boot.c:157
Inline: True
Direct callers:
  - arch/x86/kernel/acpi/boot.c:acpi_map_cpu
  - arch/x86/kernel/acpi/boot.c:acpi_parse_sapic
  - arch/x86/kernel/acpi/boot.c:acpi_parse_lapic
  - arch/x86/kernel/acpi/boot.c:acpi_parse_x2apic
```
**Symbols:**

```
ffffffff81061b80-ffffffff81061bf3: acpi_register_lapic (STB_LOCAL)
ffffffff81061eb2-ffffffff81061ec8: acpi_register_lapic.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline, Transformation ⚠️</summary>

```c
int acpi_register_lapic(int id, u32 acpiid, u8 enabled);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/acpi/boot.c (ffffffff81051fb5)
Location: arch/x86/kernel/acpi/boot.c:157
Inline: True
Direct callers:
  - arch/x86/kernel/acpi/boot.c:acpi_map_cpu
  - arch/x86/kernel/acpi/boot.c:acpi_parse_sapic
  - arch/x86/kernel/acpi/boot.c:acpi_parse_lapic
  - arch/x86/kernel/acpi/boot.c:acpi_parse_x2apic
```
**Symbols:**

```
ffffffff81051f50-ffffffff81051fc3: acpi_register_lapic (STB_LOCAL)
ffffffff81052282-ffffffff81052298: acpi_register_lapic.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline, Transformation ⚠️</summary>

```c
int acpi_register_lapic(int id, u32 acpiid, u8 enabled);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/acpi/boot.c (ffffffff81062005)
Location: arch/x86/kernel/acpi/boot.c:157
Inline: True
Direct callers:
  - arch/x86/kernel/acpi/boot.c:acpi_map_cpu
  - arch/x86/kernel/acpi/boot.c:acpi_parse_sapic
  - arch/x86/kernel/acpi/boot.c:acpi_parse_lapic
  - arch/x86/kernel/acpi/boot.c:acpi_parse_x2apic
```
**Symbols:**

```
ffffffff81061fa0-ffffffff81062013: acpi_register_lapic (STB_LOCAL)
ffffffff810622d2-ffffffff810622e8: acpi_register_lapic.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline, Transformation ⚠️</summary>

```c
int acpi_register_lapic(int id, u32 acpiid, u8 enabled);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/acpi/boot.c (ffffffff810635c5)
Location: arch/x86/kernel/acpi/boot.c:157
Inline: True
Direct callers:
  - arch/x86/kernel/acpi/boot.c:acpi_map_cpu
  - arch/x86/kernel/acpi/boot.c:acpi_parse_sapic
  - arch/x86/kernel/acpi/boot.c:acpi_parse_lapic
  - arch/x86/kernel/acpi/boot.c:acpi_parse_x2apic
```
**Symbols:**

```
ffffffff81063560-ffffffff810635d3: acpi_register_lapic (STB_LOCAL)
ffffffff81063892-ffffffff810638a8: acpi_register_lapic.cold (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
<details>
<summary>Changed between <code>4.4</code> and <code>4.8</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>u32 acpiid</code>
</li>
<li>
<b>Param reordered. </b>
<code>id, enabled</code> ➡️ <code>id, acpiid, enabled</code>
</li>
</ul>
</details>
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
