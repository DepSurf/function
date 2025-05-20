# Function: <code>acpi_os_signal</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
acpi_status acpi_os_signal(u32 function, void *info);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/osl.c (ffffffff8147a5a5)
Location: drivers/acpi/osl.c:1367
Inline: False
Direct callers:
  - drivers/acpi/acpica/dscontrol.c:acpi_ds_exec_end_control_op
  - drivers/acpi/acpica/exoparg3.c:acpi_ex_opcode_3A_0T_0R
```
**Symbols:**

```
ffffffff8147a5a5-ffffffff8147a5c5: acpi_os_signal (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
acpi_status acpi_os_signal(u32 function, void *info);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/osl.c (ffffffff814c8b73)
Location: drivers/acpi/osl.c:1329
Inline: False
Direct callers:
  - drivers/acpi/acpica/dscontrol.c:acpi_ds_exec_end_control_op
  - drivers/acpi/acpica/exoparg3.c:acpi_ex_opcode_3A_0T_0R
```
**Symbols:**

```
ffffffff814c8b73-ffffffff814c8b93: acpi_os_signal (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
acpi_status acpi_os_signal(u32 function, void *info);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/osl.c (ffffffff814eaab7)
Location: drivers/acpi/osl.c:1324
Inline: False
Direct callers:
  - drivers/acpi/acpica/dscontrol.c:acpi_ds_exec_end_control_op
  - drivers/acpi/acpica/exoparg3.c:acpi_ex_opcode_3A_0T_0R
```
**Symbols:**

```
ffffffff814eaab7-ffffffff814eaad7: acpi_os_signal (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
acpi_status acpi_os_signal(u32 function, void *info);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/osl.c (ffffffff814f6950)
Location: drivers/acpi/osl.c:1323
Inline: False
Direct callers:
  - drivers/acpi/acpica/dscontrol.c:acpi_ds_exec_end_control_op
  - drivers/acpi/acpica/exoparg3.c:acpi_ex_opcode_3A_0T_0R
```
**Symbols:**

```
ffffffff814f6950-ffffffff814f6970: acpi_os_signal (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
acpi_status acpi_os_signal(u32 function, void *info);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/osl.c (ffffffff815379a0)
Location: drivers/acpi/osl.c:1333
Inline: False
Direct callers:
  - drivers/acpi/acpica/dscontrol.c:acpi_ds_exec_end_control_op
  - drivers/acpi/acpica/exoparg3.c:acpi_ex_opcode_3A_0T_0R
```
**Symbols:**

```
ffffffff815379a0-ffffffff815379c0: acpi_os_signal (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Transformation ⚠️</summary>

```c
acpi_status acpi_os_signal(u32 function, void *info);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/acpi/osl.c (0)
Location: drivers/acpi/osl.c:1338
Inline: False
Direct callers:
  - drivers/acpi/acpica/dscontrol.c:acpi_ds_exec_end_control_op
  - drivers/acpi/acpica/exoparg3.c:acpi_ex_opcode_3A_0T_0R
```
**Symbols:**

```
ffffffff8156d8a3-ffffffff8156d8b4: acpi_os_signal.cold.22 (STB_LOCAL)
ffffffff8156d530-ffffffff8156d545: acpi_os_signal (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Transformation ⚠️</summary>

```c
acpi_status acpi_os_signal(u32 function, void *info);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/acpi/osl.c (0)
Location: drivers/acpi/osl.c:1344
Inline: False
Direct callers:
  - drivers/acpi/acpica/dscontrol.c:acpi_ds_exec_end_control_op
  - drivers/acpi/acpica/exoparg3.c:acpi_ex_opcode_3A_0T_0R
```
**Symbols:**

```
ffffffff81585463-ffffffff81585474: acpi_os_signal.cold.23 (STB_LOCAL)
ffffffff815850f0-ffffffff81585105: acpi_os_signal (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
acpi_status acpi_os_signal(u32 function, void *info);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/acpi/osl.c (0)
Location: drivers/acpi/osl.c:1330
Inline: False
Direct callers:
  - drivers/acpi/acpica/dscontrol.c:acpi_ds_exec_end_control_op
  - drivers/acpi/acpica/exoparg3.c:acpi_ex_opcode_3A_0T_0R
```
**Symbols:**

```
ffffffff815b60c3-ffffffff815b60d4: acpi_os_signal.cold (STB_LOCAL)
ffffffff815b5d10-ffffffff815b5d25: acpi_os_signal (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
acpi_status acpi_os_signal(u32 function, void *info);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/acpi/osl.c (0)
Location: drivers/acpi/osl.c:1350
Inline: False
Direct callers:
  - drivers/acpi/acpica/dscontrol.c:acpi_ds_exec_end_control_op
  - drivers/acpi/acpica/exoparg3.c:acpi_ex_opcode_3A_0T_0R
```
**Symbols:**

```
ffffffff815d72f3-ffffffff815d7304: acpi_os_signal.cold (STB_LOCAL)
ffffffff815d6f40-ffffffff815d6f55: acpi_os_signal (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
acpi_status acpi_os_signal(u32 function, void *info);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/acpi/osl.c (0)
Location: drivers/acpi/osl.c:1350
Inline: False
Direct callers:
  - drivers/acpi/acpica/dscontrol.c:acpi_ds_exec_end_control_op
  - drivers/acpi/acpica/exoparg3.c:acpi_ex_opcode_3A_0T_0R
```
**Symbols:**

```
ffffffff8168107f-ffffffff81681090: acpi_os_signal.cold (STB_LOCAL)
ffffffff81680c70-ffffffff81680c85: acpi_os_signal (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
acpi_status acpi_os_signal(u32 function, void *info);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/acpi/osl.c (0)
Location: drivers/acpi/osl.c:1354
Inline: False
Direct callers:
  - drivers/acpi/acpica/dscontrol.c:acpi_ds_exec_end_control_op
  - drivers/acpi/acpica/exoparg3.c:acpi_ex_opcode_3A_0T_0R
```
**Symbols:**

```
ffffffff81c009e7-ffffffff81c009f8: acpi_os_signal.cold (STB_LOCAL)
ffffffff8169f760-ffffffff8169f775: acpi_os_signal (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
acpi_status acpi_os_signal(u32 function, void *info);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/acpi/osl.c (0)
Location: drivers/acpi/osl.c:1354
Inline: False
Direct callers:
  - drivers/acpi/acpica/dscontrol.c:acpi_ds_exec_end_control_op
  - drivers/acpi/acpica/exoparg3.c:acpi_ex_opcode_3A_0T_0R
```
**Symbols:**

```
ffffffff81bf24e8-ffffffff81bf24fc: acpi_os_signal.cold (STB_LOCAL)
ffffffff81682410-ffffffff81682420: acpi_os_signal (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
acpi_status acpi_os_signal(u32 function, void *info);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/acpi/osl.c (0)
Location: drivers/acpi/osl.c:1354
Inline: False
Direct callers:
  - drivers/acpi/acpica/dscontrol.c:acpi_ds_exec_end_control_op
  - drivers/acpi/acpica/exoparg3.c:acpi_ex_opcode_3A_0T_0R
```
**Symbols:**

```
ffffffff81ceee1a-ffffffff81ceee2e: acpi_os_signal.cold (STB_LOCAL)
ffffffff816f7580-ffffffff816f7590: acpi_os_signal (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
acpi_status acpi_os_signal(u32 function, void *info);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/acpi/osl.c (0)
Location: drivers/acpi/osl.c:1356
Inline: False
Direct callers:
  - drivers/acpi/acpica/dscontrol.c:acpi_ds_exec_end_control_op
  - drivers/acpi/acpica/exoparg3.c:acpi_ex_opcode_3A_0T_0R
```
**Symbols:**

```
ffffffff81eb658b-ffffffff81eb65a5: acpi_os_signal.cold (STB_LOCAL)
ffffffff818244c0-ffffffff818244d6: acpi_os_signal (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
acpi_status acpi_os_signal(u32 function, void *info);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/osl.c (ffffffff819558d0)
Location: drivers/acpi/osl.c:1356
Inline: False
Direct callers:
  - drivers/acpi/acpica/dscontrol.c:acpi_ds_exec_end_control_op
  - drivers/acpi/acpica/exoparg3.c:acpi_ex_opcode_3A_0T_0R
```
**Symbols:**

```
ffffffff819558d0-ffffffff819558fc: acpi_os_signal (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
acpi_status acpi_os_signal(u32 function, void *info);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/osl.c (ffffffff8199bcd0)
Location: drivers/acpi/osl.c:1356
Inline: False
Direct callers:
  - drivers/acpi/acpica/dscontrol.c:acpi_ds_exec_end_control_op
  - drivers/acpi/acpica/exoparg3.c:acpi_ex_opcode_3A_0T_0R
```
**Symbols:**

```
ffffffff8199bcd0-ffffffff8199bcfc: acpi_os_signal (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
acpi_status acpi_os_signal(u32 function, void *info);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/osl.c (ffffffff819e4220)
Location: drivers/acpi/osl.c:1350
Inline: False
Direct callers:
  - drivers/acpi/acpica/dscontrol.c:acpi_ds_exec_end_control_op
  - drivers/acpi/acpica/exoparg3.c:acpi_ex_opcode_3A_0T_0R
```
**Symbols:**

```
ffffffff819e4220-ffffffff819e424c: acpi_os_signal (STB_GLOBAL)
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
acpi_status acpi_os_signal(u32 function, void *info);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/osl.c (ffff8000107642d8)
Location: drivers/acpi/osl.c:1350
Inline: False
Direct callers:
  - drivers/acpi/acpica/dscontrol.c:acpi_ds_exec_end_control_op
  - drivers/acpi/acpica/exoparg3.c:acpi_ex_opcode_3A_0T_0R
```
**Symbols:**

```
ffff8000107642d8-ffff800010764314: acpi_os_signal (STB_GLOBAL)
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
<summary>In <code>aws</code>: Transformation ⚠️</summary>

```c
acpi_status acpi_os_signal(u32 function, void *info);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/acpi/osl.c (0)
Location: drivers/acpi/osl.c:1350
Inline: False
Direct callers:
  - drivers/acpi/acpica/dscontrol.c:acpi_ds_exec_end_control_op
  - drivers/acpi/acpica/exoparg3.c:acpi_ex_opcode_3A_0T_0R
```
**Symbols:**

```
ffffffff815ca8a8-ffffffff815ca8b9: acpi_os_signal.cold (STB_LOCAL)
ffffffff815ca470-ffffffff815ca485: acpi_os_signal (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Transformation ⚠️</summary>

```c
acpi_status acpi_os_signal(u32 function, void *info);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/acpi/osl.c (0)
Location: drivers/acpi/osl.c:1350
Inline: False
Direct callers:
  - drivers/acpi/acpica/dscontrol.c:acpi_ds_exec_end_control_op
  - drivers/acpi/acpica/exoparg3.c:acpi_ex_opcode_3A_0T_0R
```
**Symbols:**

```
ffffffff815b390b-ffffffff815b391c: acpi_os_signal.cold (STB_LOCAL)
ffffffff815b34f0-ffffffff815b3505: acpi_os_signal (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Transformation ⚠️</summary>

```c
acpi_status acpi_os_signal(u32 function, void *info);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/acpi/osl.c (0)
Location: drivers/acpi/osl.c:1350
Inline: False
Direct callers:
  - drivers/acpi/acpica/dscontrol.c:acpi_ds_exec_end_control_op
  - drivers/acpi/acpica/exoparg3.c:acpi_ex_opcode_3A_0T_0R
```
**Symbols:**

```
ffffffff815cb5d3-ffffffff815cb5e4: acpi_os_signal.cold (STB_LOCAL)
ffffffff815cb220-ffffffff815cb235: acpi_os_signal (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
acpi_status acpi_os_signal(u32 function, void *info);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/acpi/osl.c (0)
Location: drivers/acpi/osl.c:1350
Inline: False
Direct callers:
  - drivers/acpi/acpica/dscontrol.c:acpi_ds_exec_end_control_op
  - drivers/acpi/acpica/exoparg3.c:acpi_ex_opcode_3A_0T_0R
```
**Symbols:**

```
ffffffff815e5473-ffffffff815e5484: acpi_os_signal.cold (STB_LOCAL)
ffffffff815e50c0-ffffffff815e50d5: acpi_os_signal (STB_GLOBAL)
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
