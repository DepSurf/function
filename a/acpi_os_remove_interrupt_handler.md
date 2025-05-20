# Function: <code>acpi_os_remove_interrupt_handler</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline ⚠️</summary>

```c
acpi_status acpi_os_remove_interrupt_handler(u32 gsi, acpi_osd_handler handler);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/osl.c (ffffffff8147a025)
Location: drivers/acpi/osl.c:864
Inline: True
Direct callers:
  - drivers/acpi/osl.c:acpi_os_terminate
  - drivers/acpi/acpica/evgpeutil.c:acpi_ev_delete_gpe_xrupt
  - drivers/acpi/acpica/evsci.c:acpi_ev_remove_all_sci_handlers
```
**Symbols:**

```
ffffffff8147a025-ffffffff8147a06e: acpi_os_remove_interrupt_handler (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
acpi_status acpi_os_remove_interrupt_handler(u32 gsi, acpi_osd_handler handler);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/osl.c (ffffffff814c85dc)
Location: drivers/acpi/osl.c:586
Inline: True
Direct callers:
  - drivers/acpi/osl.c:acpi_os_terminate
  - drivers/acpi/acpica/evgpeutil.c:acpi_ev_delete_gpe_xrupt
  - drivers/acpi/acpica/evsci.c:acpi_ev_remove_all_sci_handlers
```
**Symbols:**

```
ffffffff814c85dc-ffffffff814c8625: acpi_os_remove_interrupt_handler (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
acpi_status acpi_os_remove_interrupt_handler(u32 gsi, acpi_osd_handler handler);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/osl.c (ffffffff814ea520)
Location: drivers/acpi/osl.c:581
Inline: True
Direct callers:
  - drivers/acpi/osl.c:acpi_os_terminate
  - drivers/acpi/acpica/evgpeutil.c:acpi_ev_delete_gpe_xrupt
  - drivers/acpi/acpica/evsci.c:acpi_ev_remove_all_sci_handlers
```
**Symbols:**

```
ffffffff814ea520-ffffffff814ea569: acpi_os_remove_interrupt_handler (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline, Transformation ⚠️</summary>

```c
acpi_status acpi_os_remove_interrupt_handler(u32 gsi, acpi_osd_handler handler);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/acpi/osl.c (ffffffff814f6a43)
Location: drivers/acpi/osl.c:580
Inline: True
Inline callers:
  - drivers/acpi/osl.c:acpi_os_terminate
Direct callers:
  - drivers/acpi/osl.c:acpi_os_terminate
  - drivers/acpi/acpica/evgpeutil.c:acpi_ev_delete_gpe_xrupt
  - drivers/acpi/acpica/evsci.c:acpi_ev_remove_all_sci_handlers
```
**Symbols:**

```
ffffffff814f5f20-ffffffff814f5f5f: acpi_os_remove_interrupt_handler.part.19 (STB_LOCAL)
ffffffff814f62e0-ffffffff814f6301: acpi_os_remove_interrupt_handler (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline, Transformation ⚠️</summary>

```c
acpi_status acpi_os_remove_interrupt_handler(u32 gsi, acpi_osd_handler handler);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/acpi/osl.c (ffffffff81537a93)
Location: drivers/acpi/osl.c:580
Inline: True
Inline callers:
  - drivers/acpi/osl.c:acpi_os_terminate
Direct callers:
  - drivers/acpi/osl.c:acpi_os_terminate
  - drivers/acpi/acpica/evgpeutil.c:acpi_ev_delete_gpe_xrupt
  - drivers/acpi/acpica/evsci.c:acpi_ev_remove_all_sci_handlers
```
**Symbols:**

```
ffffffff81536860-ffffffff8153689f: acpi_os_remove_interrupt_handler.part.15 (STB_LOCAL)
ffffffff81536a40-ffffffff81536a61: acpi_os_remove_interrupt_handler (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
acpi_status acpi_os_remove_interrupt_handler(u32 gsi, acpi_osd_handler handler);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/osl.c (ffffffff8156c630)
Location: drivers/acpi/osl.c:585
Inline: False
Direct callers:
  - drivers/acpi/osl.c:acpi_os_terminate
  - drivers/acpi/acpica/evgpeutil.c:acpi_ev_delete_gpe_xrupt
  - drivers/acpi/acpica/evsci.c:acpi_ev_remove_all_sci_handlers
```
**Symbols:**

```
ffffffff8156c630-ffffffff8156c67a: acpi_os_remove_interrupt_handler (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
acpi_status acpi_os_remove_interrupt_handler(u32 gsi, acpi_osd_handler handler);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/osl.c (ffffffff81584260)
Location: drivers/acpi/osl.c:585
Inline: False
Direct callers:
  - drivers/acpi/osl.c:acpi_os_terminate
  - drivers/acpi/acpica/evgpeutil.c:acpi_ev_delete_gpe_xrupt
  - drivers/acpi/acpica/evsci.c:acpi_ev_remove_all_sci_handlers
```
**Symbols:**

```
ffffffff81584260-ffffffff815842aa: acpi_os_remove_interrupt_handler (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
acpi_status acpi_os_remove_interrupt_handler(u32 gsi, acpi_osd_handler handler);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/osl.c (ffffffff815b4e60)
Location: drivers/acpi/osl.c:571
Inline: False
Direct callers:
  - drivers/acpi/osl.c:acpi_os_terminate
  - drivers/acpi/acpica/evgpeutil.c:acpi_ev_delete_gpe_xrupt
  - drivers/acpi/acpica/evsci.c:acpi_ev_remove_all_sci_handlers
```
**Symbols:**

```
ffffffff815b4e60-ffffffff815b4eaa: acpi_os_remove_interrupt_handler (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
acpi_status acpi_os_remove_interrupt_handler(u32 gsi, acpi_osd_handler handler);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/osl.c (ffffffff815d6090)
Location: drivers/acpi/osl.c:591
Inline: False
Direct callers:
  - drivers/acpi/osl.c:acpi_os_terminate
  - drivers/acpi/acpica/evgpeutil.c:acpi_ev_delete_gpe_xrupt
  - drivers/acpi/acpica/evsci.c:acpi_ev_remove_all_sci_handlers
```
**Symbols:**

```
ffffffff815d6090-ffffffff815d60da: acpi_os_remove_interrupt_handler (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
acpi_status acpi_os_remove_interrupt_handler(u32 gsi, acpi_osd_handler handler);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/osl.c (ffffffff81680d63)
Location: drivers/acpi/osl.c:591
Inline: True
Inline callers:
  - drivers/acpi/osl.c:acpi_os_terminate
Direct callers:
  - drivers/acpi/acpica/evgpeutil.c:acpi_ev_delete_gpe_xrupt
  - drivers/acpi/acpica/evsci.c:acpi_ev_remove_all_sci_handlers
```
**Symbols:**

```
ffffffff8167fd90-ffffffff8167fdda: acpi_os_remove_interrupt_handler (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
acpi_status acpi_os_remove_interrupt_handler(u32 gsi, acpi_osd_handler handler);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/osl.c (ffffffff8169f853)
Location: drivers/acpi/osl.c:595
Inline: True
Inline callers:
  - drivers/acpi/osl.c:acpi_os_terminate
Direct callers:
  - drivers/acpi/acpica/evgpeutil.c:acpi_ev_delete_gpe_xrupt
  - drivers/acpi/acpica/evsci.c:acpi_ev_remove_all_sci_handlers
```
**Symbols:**

```
ffffffff8169e840-ffffffff8169e88a: acpi_os_remove_interrupt_handler (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
acpi_status acpi_os_remove_interrupt_handler(u32 gsi, acpi_osd_handler handler);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/osl.c (ffffffff816824f3)
Location: drivers/acpi/osl.c:596
Inline: True
Inline callers:
  - drivers/acpi/osl.c:acpi_os_terminate
Direct callers:
  - drivers/acpi/acpica/evgpeutil.c:acpi_ev_delete_gpe_xrupt
  - drivers/acpi/acpica/evsci.c:acpi_ev_remove_all_sci_handlers
```
**Symbols:**

```
ffffffff816814f0-ffffffff8168153a: acpi_os_remove_interrupt_handler (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
acpi_status acpi_os_remove_interrupt_handler(u32 gsi, acpi_osd_handler handler);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/osl.c (ffffffff816f7663)
Location: drivers/acpi/osl.c:596
Inline: True
Inline callers:
  - drivers/acpi/osl.c:acpi_os_terminate
Direct callers:
  - drivers/acpi/acpica/evgpeutil.c:acpi_ev_delete_gpe_xrupt
  - drivers/acpi/acpica/evsci.c:acpi_ev_remove_all_sci_handlers
```
**Symbols:**

```
ffffffff816f65e0-ffffffff816f662a: acpi_os_remove_interrupt_handler (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
acpi_status acpi_os_remove_interrupt_handler(u32 gsi, acpi_osd_handler handler);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/osl.c (ffffffff818245f3)
Location: drivers/acpi/osl.c:595
Inline: True
Inline callers:
  - drivers/acpi/osl.c:acpi_os_terminate
Direct callers:
  - drivers/acpi/acpica/evgpeutil.c:acpi_ev_delete_gpe_xrupt
  - drivers/acpi/acpica/evsci.c:acpi_ev_remove_all_sci_handlers
```
**Symbols:**

```
ffffffff818233f0-ffffffff8182344e: acpi_os_remove_interrupt_handler (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
acpi_status acpi_os_remove_interrupt_handler(u32 gsi, acpi_osd_handler handler);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/osl.c (ffffffff81955a93)
Location: drivers/acpi/osl.c:595
Inline: True
Inline callers:
  - drivers/acpi/osl.c:acpi_os_terminate
Direct callers:
  - drivers/acpi/acpica/evgpeutil.c:acpi_ev_delete_gpe_xrupt
  - drivers/acpi/acpica/evsci.c:acpi_ev_remove_all_sci_handlers
```
**Symbols:**

```
ffffffff819545f0-ffffffff8195464e: acpi_os_remove_interrupt_handler (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
acpi_status acpi_os_remove_interrupt_handler(u32 gsi, acpi_osd_handler handler);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/osl.c (ffffffff8199be93)
Location: drivers/acpi/osl.c:595
Inline: True
Inline callers:
  - drivers/acpi/osl.c:acpi_os_terminate
Direct callers:
  - drivers/acpi/acpica/evgpeutil.c:acpi_ev_delete_gpe_xrupt
  - drivers/acpi/acpica/evsci.c:acpi_ev_remove_all_sci_handlers
```
**Symbols:**

```
ffffffff8199aa00-ffffffff8199aa5e: acpi_os_remove_interrupt_handler (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
acpi_status acpi_os_remove_interrupt_handler(u32 gsi, acpi_osd_handler handler);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/osl.c (ffffffff819e43e3)
Location: drivers/acpi/osl.c:592
Inline: True
Inline callers:
  - drivers/acpi/osl.c:acpi_os_terminate
Direct callers:
  - drivers/acpi/acpica/evgpeutil.c:acpi_ev_delete_gpe_xrupt
  - drivers/acpi/acpica/evsci.c:acpi_ev_remove_all_sci_handlers
```
**Symbols:**

```
ffffffff819e2e80-ffffffff819e2ede: acpi_os_remove_interrupt_handler (STB_GLOBAL)
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
acpi_status acpi_os_remove_interrupt_handler(u32 gsi, acpi_osd_handler handler);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/osl.c (ffff800010763938)
Location: drivers/acpi/osl.c:591
Inline: False
Direct callers:
  - drivers/acpi/osl.c:acpi_os_terminate
```
**Symbols:**

```
ffff800010763938-ffff8000107639bc: acpi_os_remove_interrupt_handler (STB_GLOBAL)
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
acpi_status acpi_os_remove_interrupt_handler(u32 gsi, acpi_osd_handler handler);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/osl.c (ffffffff815c9df0)
Location: drivers/acpi/osl.c:591
Inline: False
Direct callers:
  - drivers/acpi/osl.c:acpi_os_terminate
  - drivers/acpi/acpica/evgpeutil.c:acpi_ev_delete_gpe_xrupt
  - drivers/acpi/acpica/evsci.c:acpi_ev_remove_all_sci_handlers
```
**Symbols:**

```
ffffffff815c9df0-ffffffff815c9e3a: acpi_os_remove_interrupt_handler (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
acpi_status acpi_os_remove_interrupt_handler(u32 gsi, acpi_osd_handler handler);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/osl.c (ffffffff815b2e70)
Location: drivers/acpi/osl.c:591
Inline: False
Direct callers:
  - drivers/acpi/osl.c:acpi_os_terminate
  - drivers/acpi/acpica/evgpeutil.c:acpi_ev_delete_gpe_xrupt
  - drivers/acpi/acpica/evsci.c:acpi_ev_remove_all_sci_handlers
```
**Symbols:**

```
ffffffff815b2e70-ffffffff815b2eba: acpi_os_remove_interrupt_handler (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
acpi_status acpi_os_remove_interrupt_handler(u32 gsi, acpi_osd_handler handler);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/osl.c (ffffffff815ca370)
Location: drivers/acpi/osl.c:591
Inline: False
Direct callers:
  - drivers/acpi/osl.c:acpi_os_terminate
  - drivers/acpi/acpica/evgpeutil.c:acpi_ev_delete_gpe_xrupt
  - drivers/acpi/acpica/evsci.c:acpi_ev_remove_all_sci_handlers
```
**Symbols:**

```
ffffffff815ca370-ffffffff815ca3ba: acpi_os_remove_interrupt_handler (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
acpi_status acpi_os_remove_interrupt_handler(u32 gsi, acpi_osd_handler handler);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/osl.c (ffffffff815e41d0)
Location: drivers/acpi/osl.c:591
Inline: False
Direct callers:
  - drivers/acpi/osl.c:acpi_os_terminate
  - drivers/acpi/acpica/evgpeutil.c:acpi_ev_delete_gpe_xrupt
  - drivers/acpi/acpica/evsci.c:acpi_ev_remove_all_sci_handlers
```
**Symbols:**

```
ffffffff815e41d0-ffffffff815e421a: acpi_os_remove_interrupt_handler (STB_GLOBAL)
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
