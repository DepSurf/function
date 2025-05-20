# Function: <code>arch_apei_enable_cmcff</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int arch_apei_enable_cmcff(struct acpi_hest_header *hest_hdr, void *data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/acpi/apei.c (ffffffff8104fde0)
Location: arch/x86/kernel/acpi/apei.c:20
Inline: False
Direct callers:
  - drivers/acpi/apei/hest.c:hest_parse_cmc
```
**Symbols:**

```
ffffffff8104fde0-ffffffff8104fe4f: arch_apei_enable_cmcff (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int arch_apei_enable_cmcff(struct acpi_hest_header *hest_hdr, void *data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/acpi/apei.c (ffffffff8104ff60)
Location: arch/x86/kernel/acpi/apei.c:20
Inline: False
Direct callers:
  - drivers/acpi/apei/hest.c:hest_parse_cmc
```
**Symbols:**

```
ffffffff8104ff60-ffffffff8104ffc8: arch_apei_enable_cmcff (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int arch_apei_enable_cmcff(struct acpi_hest_header *hest_hdr, void *data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/acpi/apei.c (ffffffff81052780)
Location: arch/x86/kernel/acpi/apei.c:20
Inline: False
```
**Symbols:**

```
ffffffff81052780-ffffffff810527ec: arch_apei_enable_cmcff (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int arch_apei_enable_cmcff(struct acpi_hest_header *hest_hdr, void *data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/acpi/apei.c (ffffffff810522a0)
Location: arch/x86/kernel/acpi/apei.c:20
Inline: False
```
**Symbols:**

```
ffffffff810522a0-ffffffff81052302: arch_apei_enable_cmcff (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int arch_apei_enable_cmcff(struct acpi_hest_header *hest_hdr, void *data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/acpi/apei.c (ffffffff81055f00)
Location: arch/x86/kernel/acpi/apei.c:20
Inline: False
```
**Symbols:**

```
ffffffff81055f00-ffffffff81055f62: arch_apei_enable_cmcff (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Transformation ⚠️</summary>

```c
int arch_apei_enable_cmcff(struct acpi_hest_header *hest_hdr, void *data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/acpi/apei.c (ffffffff815d3dd0)
Location: arch/x86/kernel/acpi/apei.c:20
Inline: False
Direct callers:
  - drivers/acpi/apei/hest.c:hest_parse_cmc
```
**Symbols:**

```
ffffffff81058dd0-ffffffff81058e04: arch_apei_enable_cmcff.cold.0 (STB_LOCAL)
ffffffff81058d80-ffffffff81058db5: arch_apei_enable_cmcff (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Transformation ⚠️</summary>

```c
int arch_apei_enable_cmcff(struct acpi_hest_header *hest_hdr, void *data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/acpi/apei.c (ffffffff815ed580)
Location: arch/x86/kernel/acpi/apei.c:20
Inline: False
Direct callers:
  - drivers/acpi/apei/hest.c:hest_parse_cmc
```
**Symbols:**

```
ffffffff8105ea20-ffffffff8105ea54: arch_apei_enable_cmcff.cold.0 (STB_LOCAL)
ffffffff8105e9d0-ffffffff8105ea05: arch_apei_enable_cmcff (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
int arch_apei_enable_cmcff(struct acpi_hest_header *hest_hdr, void *data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/acpi/apei.c (ffffffff8161f330)
Location: arch/x86/kernel/acpi/apei.c:11
Inline: False
Direct callers:
  - drivers/acpi/apei/hest.c:hest_parse_cmc
```
**Symbols:**

```
ffffffff81061e10-ffffffff81061e41: arch_apei_enable_cmcff.cold (STB_LOCAL)
ffffffff81061dc0-ffffffff81061dfc: arch_apei_enable_cmcff (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
int arch_apei_enable_cmcff(struct acpi_hest_header *hest_hdr, void *data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/acpi/apei.c (ffffffff81640e10)
Location: arch/x86/kernel/acpi/apei.c:11
Inline: False
Direct callers:
  - drivers/acpi/apei/hest.c:hest_parse_cmc
```
**Symbols:**

```
ffffffff810626d0-ffffffff81062701: arch_apei_enable_cmcff.cold (STB_LOCAL)
ffffffff81062680-ffffffff810626bc: arch_apei_enable_cmcff (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
int arch_apei_enable_cmcff(struct acpi_hest_header *hest_hdr, void *data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/acpi/apei.c (ffffffff816edeb0)
Location: arch/x86/kernel/acpi/apei.c:11
Inline: False
Direct callers:
  - drivers/acpi/apei/hest.c:hest_parse_cmc
```
**Symbols:**

```
ffffffff810686b0-ffffffff810686e1: arch_apei_enable_cmcff.cold (STB_LOCAL)
ffffffff81068660-ffffffff8106869c: arch_apei_enable_cmcff (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
int arch_apei_enable_cmcff(struct acpi_hest_header *hest_hdr, void *data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/acpi/apei.c (ffffffff8170b4c0)
Location: arch/x86/kernel/acpi/apei.c:11
Inline: False
Direct callers:
  - drivers/acpi/apei/hest.c:hest_parse_cmc
```
**Symbols:**

```
ffffffff81bd66a3-ffffffff81bd66d4: arch_apei_enable_cmcff.cold (STB_LOCAL)
ffffffff8106a330-ffffffff8106a36c: arch_apei_enable_cmcff (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
int arch_apei_enable_cmcff(struct acpi_hest_header *hest_hdr, void *data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/acpi/apei.c (ffffffff816ecb10)
Location: arch/x86/kernel/acpi/apei.c:11
Inline: False
Direct callers:
  - drivers/acpi/apei/hest.c:hest_parse_cmc
```
**Symbols:**

```
ffffffff81bc8955-ffffffff81bc8986: arch_apei_enable_cmcff.cold (STB_LOCAL)
ffffffff8106ae00-ffffffff8106ae3c: arch_apei_enable_cmcff (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int arch_apei_enable_cmcff(struct acpi_hest_header *hest_hdr, void *data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/acpi/apei.c (ffffffff81766c50)
Location: arch/x86/kernel/acpi/apei.c:11
Inline: False
Direct callers:
  - drivers/acpi/apei/hest.c:hest_parse_cmc
```
**Symbols:**

```
ffffffff81c9d145-ffffffff81c9d176: arch_apei_enable_cmcff.cold (STB_LOCAL)
ffffffff810757a0-ffffffff810757dc: arch_apei_enable_cmcff (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int arch_apei_enable_cmcff(struct acpi_hest_header *hest_hdr, void *data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/acpi/apei.c (ffffffff8189b280)
Location: arch/x86/kernel/acpi/apei.c:11
Inline: False
Direct callers:
  - drivers/acpi/apei/hest.c:hest_parse_cmc
```
**Symbols:**

```
ffffffff81e4c539-ffffffff81e4c56a: arch_apei_enable_cmcff.cold (STB_LOCAL)
ffffffff81084220-ffffffff8108426e: arch_apei_enable_cmcff (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int arch_apei_enable_cmcff(struct acpi_hest_header *hest_hdr, void *data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/acpi/apei.c (ffffffff810970f0)
Location: arch/x86/kernel/acpi/apei.c:11
Inline: False
Direct callers:
  - drivers/acpi/apei/hest.c:hest_parse_cmc
```
**Symbols:**

```
ffffffff810970f0-ffffffff81097164: arch_apei_enable_cmcff (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int arch_apei_enable_cmcff(struct acpi_hest_header *hest_hdr, void *data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/acpi/apei.c (ffffffff8109a1c0)
Location: arch/x86/kernel/acpi/apei.c:11
Inline: False
Direct callers:
  - drivers/acpi/apei/hest.c:hest_parse_cmc
```
**Symbols:**

```
ffffffff8109a1c0-ffffffff8109a234: arch_apei_enable_cmcff (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int arch_apei_enable_cmcff(struct acpi_hest_header *hest_hdr, void *data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/acpi/apei.c (ffffffff810a19f0)
Location: arch/x86/kernel/acpi/apei.c:11
Inline: False
Direct callers:
  - drivers/acpi/apei/hest.c:hest_parse_cmc
```
**Symbols:**

```
ffffffff810a19f0-ffffffff810a1a64: arch_apei_enable_cmcff (STB_GLOBAL)
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
int arch_apei_enable_cmcff(struct acpi_hest_header *hest_hdr, void *data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/apei/apei-base.c (ffff8000107aba88)
Location: drivers/acpi/apei/apei-base.c:758
Inline: False
```
**Symbols:**

```
ffff8000107aba88-ffff8000107abaa4: arch_apei_enable_cmcff (STB_WEAK)
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
<summary>In <code>azure</code>: Transformation ⚠️</summary>

```c
int arch_apei_enable_cmcff(struct acpi_hest_header *hest_hdr, void *data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/acpi/apei.c (ffffffff815fd220)
Location: arch/x86/kernel/acpi/apei.c:11
Inline: False
Direct callers:
  - drivers/acpi/apei/hest.c:hest_parse_cmc
```
**Symbols:**

```
ffffffff81052650-ffffffff81052681: arch_apei_enable_cmcff.cold (STB_LOCAL)
ffffffff81052600-ffffffff8105263c: arch_apei_enable_cmcff (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Transformation ⚠️</summary>

```c
int arch_apei_enable_cmcff(struct acpi_hest_header *hest_hdr, void *data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/acpi/apei.c (ffffffff81634c50)
Location: arch/x86/kernel/acpi/apei.c:11
Inline: False
Direct callers:
  - drivers/acpi/apei/hest.c:hest_parse_cmc
```
**Symbols:**

```
ffffffff81062670-ffffffff810626a1: arch_apei_enable_cmcff.cold (STB_LOCAL)
ffffffff81062620-ffffffff8106265c: arch_apei_enable_cmcff (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
int arch_apei_enable_cmcff(struct acpi_hest_header *hest_hdr, void *data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/acpi/apei.c (ffffffff8164ef60)
Location: arch/x86/kernel/acpi/apei.c:11
Inline: False
Direct callers:
  - drivers/acpi/apei/hest.c:hest_parse_cmc
```
**Symbols:**

```
ffffffff81063c30-ffffffff81063c61: arch_apei_enable_cmcff.cold (STB_LOCAL)
ffffffff81063be0-ffffffff81063c1c: arch_apei_enable_cmcff (STB_GLOBAL)
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
