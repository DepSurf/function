# Function: <code>acpi_os_write_memory</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
acpi_status acpi_os_write_memory(acpi_physical_address phys_addr, u64 value, u32 width);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/osl.c (ffffffff8147a1b2)
Location: drivers/acpi/osl.c:997
Inline: False
Direct callers:
  - drivers/acpi/acpica/hwregs.c:acpi_hw_write
  - drivers/acpi/acpica/hwxface.c:acpi_write
  - drivers/acpi/apei/apei-base.c:apei_write
```
**Symbols:**

```
ffffffff8147a1b2-ffffffff8147a24c: acpi_os_write_memory (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
acpi_status acpi_os_write_memory(acpi_physical_address phys_addr, u64 value, u32 width);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/osl.c (ffffffff814c8769)
Location: drivers/acpi/osl.c:719
Inline: False
Direct callers:
  - drivers/acpi/acpica/hwregs.c:acpi_hw_write
  - drivers/acpi/acpica/hwxface.c:acpi_write
  - drivers/acpi/apei/apei-base.c:apei_write
```
**Symbols:**

```
ffffffff814c8769-ffffffff814c8803: acpi_os_write_memory (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
acpi_status acpi_os_write_memory(acpi_physical_address phys_addr, u64 value, u32 width);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/osl.c (ffffffff814ea6ad)
Location: drivers/acpi/osl.c:714
Inline: False
Direct callers:
  - drivers/acpi/acpica/hwregs.c:acpi_hw_write
  - drivers/acpi/acpica/hwxface.c:acpi_write
  - drivers/acpi/cppc_acpi.c:cppc_set_perf
  - drivers/acpi/apei/apei-base.c:apei_write
```
**Symbols:**

```
ffffffff814ea6ad-ffffffff814ea747: acpi_os_write_memory (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
acpi_status acpi_os_write_memory(acpi_physical_address phys_addr, u64 value, u32 width);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/osl.c (ffffffff814f64b0)
Location: drivers/acpi/osl.c:713
Inline: False
Direct callers:
  - drivers/acpi/acpica/hwregs.c:acpi_hw_write
  - drivers/acpi/acpica/hwxface.c:acpi_write
  - drivers/acpi/cppc_acpi.c:cppc_set_perf
  - drivers/acpi/apei/apei-base.c:apei_write
```
**Symbols:**

```
ffffffff814f64b0-ffffffff814f6581: acpi_os_write_memory (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
acpi_status acpi_os_write_memory(acpi_physical_address phys_addr, u64 value, u32 width);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/osl.c (ffffffff81536c60)
Location: drivers/acpi/osl.c:723
Inline: False
Direct callers:
  - drivers/acpi/acpica/hwregs.c:acpi_hw_write
  - drivers/acpi/cppc_acpi.c:cppc_set_perf
  - drivers/acpi/apei/apei-base.c:apei_write
```
**Symbols:**

```
ffffffff81536c60-ffffffff81536d31: acpi_os_write_memory (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
acpi_status acpi_os_write_memory(acpi_physical_address phys_addr, u64 value, u32 width);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/osl.c (ffffffff8156c880)
Location: drivers/acpi/osl.c:728
Inline: False
Direct callers:
  - drivers/acpi/acpica/hwregs.c:acpi_hw_write
  - drivers/acpi/cppc_acpi.c:cppc_set_perf
  - drivers/acpi/apei/apei-base.c:apei_write
```
**Symbols:**

```
ffffffff8156c880-ffffffff8156c945: acpi_os_write_memory (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
acpi_status acpi_os_write_memory(acpi_physical_address phys_addr, u64 value, u32 width);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/osl.c (ffffffff815844b0)
Location: drivers/acpi/osl.c:731
Inline: False
Direct callers:
  - drivers/acpi/acpica/hwregs.c:acpi_hw_write
  - drivers/acpi/cppc_acpi.c:cppc_set_perf
  - drivers/acpi/apei/apei-base.c:apei_write
```
**Symbols:**

```
ffffffff815844b0-ffffffff81584575: acpi_os_write_memory (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
acpi_status acpi_os_write_memory(acpi_physical_address phys_addr, u64 value, u32 width);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/osl.c (ffffffff815b50b0)
Location: drivers/acpi/osl.c:717
Inline: False
Direct callers:
  - drivers/acpi/acpica/hwregs.c:acpi_hw_write
  - drivers/acpi/cppc_acpi.c:cppc_set_perf
  - drivers/acpi/apei/apei-base.c:apei_write
```
**Symbols:**

```
ffffffff815b50b0-ffffffff815b5176: acpi_os_write_memory (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
acpi_status acpi_os_write_memory(acpi_physical_address phys_addr, u64 value, u32 width);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/osl.c (ffffffff815d62e0)
Location: drivers/acpi/osl.c:737
Inline: False
Direct callers:
  - drivers/acpi/acpica/hwregs.c:acpi_hw_write
  - drivers/acpi/cppc_acpi.c:cppc_set_perf
  - drivers/acpi/apei/apei-base.c:apei_write
```
**Symbols:**

```
ffffffff815d62e0-ffffffff815d63a6: acpi_os_write_memory (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
acpi_status acpi_os_write_memory(acpi_physical_address phys_addr, u64 value, u32 width);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/osl.c (ffffffff8167ffe0)
Location: drivers/acpi/osl.c:737
Inline: False
Direct callers:
  - drivers/acpi/acpica/hwregs.c:acpi_hw_write
  - drivers/acpi/apei/apei-base.c:apei_write
```
**Symbols:**

```
ffffffff8167ffe0-ffffffff816800a6: acpi_os_write_memory (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
acpi_status acpi_os_write_memory(acpi_physical_address phys_addr, u64 value, u32 width);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/osl.c (ffffffff8169eab0)
Location: drivers/acpi/osl.c:741
Inline: False
Direct callers:
  - drivers/acpi/acpica/hwregs.c:acpi_hw_write
  - drivers/acpi/apei/apei-base.c:apei_write
```
**Symbols:**

```
ffffffff8169eab0-ffffffff8169eb97: acpi_os_write_memory (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
acpi_status acpi_os_write_memory(acpi_physical_address phys_addr, u64 value, u32 width);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/osl.c (ffffffff81681760)
Location: drivers/acpi/osl.c:742
Inline: False
Direct callers:
  - drivers/acpi/acpica/hwregs.c:acpi_hw_write
  - drivers/acpi/cppc_acpi.c:cppc_set_perf
  - drivers/acpi/apei/apei-base.c:apei_write
```
**Symbols:**

```
ffffffff81681760-ffffffff81681849: acpi_os_write_memory (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
acpi_status acpi_os_write_memory(acpi_physical_address phys_addr, u64 value, u32 width);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/osl.c (ffffffff816f6850)
Location: drivers/acpi/osl.c:742
Inline: False
Direct callers:
  - drivers/acpi/acpica/hwregs.c:acpi_hw_write
  - drivers/acpi/cppc_acpi.c:cppc_set_perf
  - drivers/acpi/apei/apei-base.c:apei_write
```
**Symbols:**

```
ffffffff816f6850-ffffffff816f6939: acpi_os_write_memory (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
acpi_status acpi_os_write_memory(acpi_physical_address phys_addr, u64 value, u32 width);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/osl.c (ffffffff818236a0)
Location: drivers/acpi/osl.c:744
Inline: False
Direct callers:
  - drivers/acpi/acpica/hwregs.c:acpi_hw_write
  - drivers/acpi/cppc_acpi.c:cpc_write
  - drivers/acpi/apei/apei-base.c:apei_write
```
**Symbols:**

```
ffffffff818236a0-ffffffff818237c0: acpi_os_write_memory (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
acpi_status acpi_os_write_memory(acpi_physical_address phys_addr, u64 value, u32 width);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/osl.c (ffffffff81954900)
Location: drivers/acpi/osl.c:744
Inline: False
Direct callers:
  - drivers/acpi/acpica/hwregs.c:acpi_hw_write
  - drivers/acpi/cppc_acpi.c:cpc_write
  - drivers/acpi/apei/apei-base.c:apei_write
```
**Symbols:**

```
ffffffff81954900-ffffffff81954a20: acpi_os_write_memory (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
acpi_status acpi_os_write_memory(acpi_physical_address phys_addr, u64 value, u32 width);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/osl.c (ffffffff8199ad00)
Location: drivers/acpi/osl.c:744
Inline: False
Direct callers:
  - drivers/acpi/acpica/hwregs.c:acpi_hw_write
  - drivers/acpi/cppc_acpi.c:cpc_write
  - drivers/acpi/apei/apei-base.c:apei_write
```
**Symbols:**

```
ffffffff8199ad00-ffffffff8199ae20: acpi_os_write_memory (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
acpi_status acpi_os_write_memory(acpi_physical_address phys_addr, u64 value, u32 width);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/osl.c (ffffffff819e3180)
Location: drivers/acpi/osl.c:741
Inline: False
Direct callers:
  - drivers/acpi/acpica/hwregs.c:acpi_hw_write
  - drivers/acpi/cppc_acpi.c:cpc_write
  - drivers/acpi/apei/apei-base.c:apei_write
```
**Symbols:**

```
ffffffff819e3180-ffffffff819e32a0: acpi_os_write_memory (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: ✅</summary>

```c
acpi_status acpi_os_write_memory(acpi_physical_address phys_addr, u64 value, u32 width);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/osl.c (ffff800010763ce0)
Location: drivers/acpi/osl.c:737
Inline: False
Direct callers:
  - drivers/acpi/acpica/hwregs.c:acpi_hw_write
  - drivers/acpi/cppc_acpi.c:cppc_set_perf
  - drivers/acpi/apei/apei-base.c:apei_write
```
**Symbols:**

```
ffff800010763ce0-ffff800010763e34: acpi_os_write_memory (STB_GLOBAL)
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
<details>
<summary>In <code>aws</code>: ✅</summary>

```c
acpi_status acpi_os_write_memory(acpi_physical_address phys_addr, u64 value, u32 width);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/osl.c (ffffffff815ca040)
Location: drivers/acpi/osl.c:737
Inline: False
Direct callers:
  - drivers/acpi/acpica/hwregs.c:acpi_hw_write
  - drivers/acpi/cppc_acpi.c:cppc_set_perf
```
**Symbols:**

```
ffffffff815ca040-ffffffff815ca106: acpi_os_write_memory (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
acpi_status acpi_os_write_memory(acpi_physical_address phys_addr, u64 value, u32 width);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/osl.c (ffffffff815b30c0)
Location: drivers/acpi/osl.c:737
Inline: False
Direct callers:
  - drivers/acpi/acpica/hwregs.c:acpi_hw_write
  - drivers/acpi/cppc_acpi.c:cppc_set_perf
  - drivers/acpi/apei/apei-base.c:apei_write
```
**Symbols:**

```
ffffffff815b30c0-ffffffff815b3186: acpi_os_write_memory (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
acpi_status acpi_os_write_memory(acpi_physical_address phys_addr, u64 value, u32 width);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/osl.c (ffffffff815ca5c0)
Location: drivers/acpi/osl.c:737
Inline: False
Direct callers:
  - drivers/acpi/acpica/hwregs.c:acpi_hw_write
  - drivers/acpi/cppc_acpi.c:cppc_set_perf
  - drivers/acpi/apei/apei-base.c:apei_write
```
**Symbols:**

```
ffffffff815ca5c0-ffffffff815ca686: acpi_os_write_memory (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
acpi_status acpi_os_write_memory(acpi_physical_address phys_addr, u64 value, u32 width);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/osl.c (ffffffff815e4440)
Location: drivers/acpi/osl.c:737
Inline: False
Direct callers:
  - drivers/acpi/acpica/hwregs.c:acpi_hw_write
  - drivers/acpi/cppc_acpi.c:cppc_set_perf
  - drivers/acpi/apei/apei-base.c:apei_write
```
**Symbols:**

```
ffffffff815e4440-ffffffff815e452f: acpi_os_write_memory (STB_GLOBAL)
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
