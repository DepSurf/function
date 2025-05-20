# Function: <code>trace_aer_event</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/pci/pcie/aer/aerdrv_errprint.c (ffffffff81449698)
Location: include/ras/ras_event.h:207
Inline: True
Inline callers:
  - drivers/pci/pcie/aer/aerdrv_errprint.c:aer_print_error
  - drivers/pci/pcie/aer/aerdrv_errprint.c:cper_print_aer
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/pci/pcie/aer/aerdrv_errprint.c (ffffffff81495c0d)
Location: include/ras/ras_event.h:207
Inline: True
Inline callers:
  - drivers/pci/pcie/aer/aerdrv_errprint.c:cper_print_aer
  - drivers/pci/pcie/aer/aerdrv_errprint.c:aer_print_error
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/pci/pcie/aer/aerdrv_errprint.c (ffffffff814b75c1)
Location: include/ras/ras_event.h:207
Inline: True
Inline callers:
  - drivers/pci/pcie/aer/aerdrv_errprint.c:cper_print_aer
  - drivers/pci/pcie/aer/aerdrv_errprint.c:aer_print_error
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/pci/pcie/aer/aerdrv_errprint.c (ffffffff814c1eff)
Location: include/ras/ras_event.h:297
Inline: True
Inline callers:
  - drivers/pci/pcie/aer/aerdrv_errprint.c:cper_print_aer
  - drivers/pci/pcie/aer/aerdrv_errprint.c:aer_print_error
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/pci/pcie/aer/aerdrv_errprint.c (ffffffff81502113)
Location: include/ras/ras_event.h:298
Inline: True
Inline callers:
  - drivers/pci/pcie/aer/aerdrv_errprint.c:cper_print_aer
  - drivers/pci/pcie/aer/aerdrv_errprint.c:aer_print_error
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/pci/pcie/aer.c (ffffffff81533ff3)
Location: include/ras/ras_event.h:298
Inline: True
Inline callers:
  - drivers/pci/pcie/aer.c:aer_isr
  - drivers/pci/pcie/aer.c:aer_isr
  - drivers/pci/pcie/aer.c:cper_print_aer
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/pci/pcie/aer.c (ffffffff8154b8c6)
Location: include/ras/ras_event.h:298
Inline: True
Inline callers:
  - drivers/pci/pcie/aer.c:cper_print_aer
  - drivers/pci/pcie/aer.c:cper_print_aer
  - drivers/pci/pcie/aer.c:aer_print_error
  - drivers/pci/pcie/aer.c:aer_print_error
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
void trace_aer_event(const char *dev_name, const u32 status, const u8 severity, const u8 tlp_header_valid, struct aer_header_log_regs *tlp);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/pcie/aer.c (ffffffff8157b86f)
Location: include/ras/ras_event.h:298
Inline: True
Direct callers:
  - drivers/pci/pcie/aer.c:cper_print_aer
  - drivers/pci/pcie/aer.c:aer_print_error
```
**Symbols:**

```
ffffffff8157b86f-ffffffff8157b8eb: trace_aer_event (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
void trace_aer_event(const char *dev_name, const u32 status, const u8 severity, const u8 tlp_header_valid, struct aer_header_log_regs *tlp);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/pcie/aer.c (ffffffff8159d2d6)
Location: include/ras/ras_event.h:298
Inline: True
Direct callers:
  - drivers/pci/pcie/aer.c:cper_print_aer
  - drivers/pci/pcie/aer.c:aer_print_error
```
**Symbols:**

```
ffffffff8159d2d6-ffffffff8159d352: trace_aer_event (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
void trace_aer_event(const char *dev_name, const u32 status, const u8 severity, const u8 tlp_header_valid, struct aer_header_log_regs *tlp);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/pcie/aer.c (ffffffff8163ce76)
Location: include/ras/ras_event.h:298
Inline: True
Direct callers:
  - drivers/pci/pcie/aer.c:cper_print_aer
  - drivers/pci/pcie/aer.c:aer_print_error
```
**Symbols:**

```
ffffffff8163ce76-ffffffff8163cef2: trace_aer_event (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
void trace_aer_event(const char *dev_name, const u32 status, const u8 severity, const u8 tlp_header_valid, struct aer_header_log_regs *tlp);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/pcie/aer.c (ffffffff81bf9264)
Location: include/ras/ras_event.h:298
Inline: True
Direct callers:
  - drivers/pci/pcie/aer.c:cper_print_aer
  - drivers/pci/pcie/aer.c:aer_print_error
```
**Symbols:**

```
ffffffff81bf9264-ffffffff81bf92b2: trace_aer_event (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
void trace_aer_event(const char *dev_name, const u32 status, const u8 severity, const u8 tlp_header_valid, struct aer_header_log_regs *tlp);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/pcie/aer.c (ffffffff81beb0b9)
Location: include/ras/ras_event.h:298
Inline: True
Direct callers:
  - drivers/pci/pcie/aer.c:cper_print_aer
  - drivers/pci/pcie/aer.c:aer_print_error
```
**Symbols:**

```
ffffffff81beb0b9-ffffffff81beb107: trace_aer_event (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
void trace_aer_event(const char *dev_name, const u32 status, const u8 severity, const u8 tlp_header_valid, struct aer_header_log_regs *tlp);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/pcie/aer.c (ffffffff816b70fb)
Location: include/ras/ras_event.h:298
Inline: True
Inline callers:
  - drivers/pci/pcie/aer.c:aer_print_error
  - drivers/pci/pcie/aer.c:aer_print_error
Direct callers:
  - drivers/pci/pcie/aer.c:cper_print_aer
```
**Symbols:**

```
ffffffff816b6380-ffffffff816b63cb: trace_aer_event (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
void trace_aer_event(const char *dev_name, const u32 status, const u8 severity, const u8 tlp_header_valid, struct aer_header_log_regs *tlp);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/pcie/aer.c (ffffffff817dada6)
Location: include/ras/ras_event.h:298
Inline: True
Inline callers:
  - drivers/pci/pcie/aer.c:aer_print_error
  - drivers/pci/pcie/aer.c:aer_print_error
Direct callers:
  - drivers/pci/pcie/aer.c:cper_print_aer
```
**Symbols:**

```
ffffffff817d9e40-ffffffff817d9eed: trace_aer_event (STB_LOCAL)
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
In drivers/pci/pcie/aer.c (ffffffff818fcc17)
Location: include/ras/ras_event.h:298
Inline: True
Inline callers:
  - drivers/pci/pcie/aer.c:cper_print_aer
  - drivers/pci/pcie/aer.c:cper_print_aer
  - drivers/pci/pcie/aer.c:aer_print_error
  - drivers/pci/pcie/aer.c:aer_print_error
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
In drivers/pci/pcie/aer.c (ffffffff81940094)
Location: include/ras/ras_event.h:298
Inline: True
Inline callers:
  - drivers/pci/pcie/aer.c:cper_print_aer
  - drivers/pci/pcie/aer.c:cper_print_aer
  - drivers/pci/pcie/aer.c:aer_print_error
  - drivers/pci/pcie/aer.c:aer_print_error
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
In drivers/pci/pcie/aer.c (ffffffff819888e4)
Location: include/ras/ras_event.h:298
Inline: True
Inline callers:
  - drivers/pci/pcie/aer.c:pci_print_aer
  - drivers/pci/pcie/aer.c:pci_print_aer
  - drivers/pci/pcie/aer.c:aer_print_error
  - drivers/pci/pcie/aer.c:aer_print_error
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Selective Inline ⚠️</summary>

```c
void trace_aer_event(const char *dev_name, const u32 status, const u8 severity, const u8 tlp_header_valid, struct aer_header_log_regs *tlp);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/pcie/aer.c (ffff800010705410)
Location: include/ras/ras_event.h:298
Inline: True
Direct callers:
  - drivers/pci/pcie/aer.c:cper_print_aer
  - drivers/pci/pcie/aer.c:aer_print_error
```
**Symbols:**

```
ffff800010705410-ffff8000107054b8: trace_aer_event (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/pci/pcie/aer.c (c089c978)
Location: include/ras/ras_event.h:298
Inline: True
Inline callers:
  - drivers/pci/pcie/aer.c:aer_print_error
```
</details>
</li>
<li>
In <code>ppc64el</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/pci/pcie/aer.c (ffffffe0004d36ba)
Location: include/ras/ras_event.h:298
Inline: True
Inline callers:
  - drivers/pci/pcie/aer.c:aer_print_error
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/pci/pcie/aer.c (ffffffff81590f82)
Location: include/ras/ras_event.h:298
Inline: True
Inline callers:
  - drivers/pci/pcie/aer.c:aer_print_error
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
void trace_aer_event(const char *dev_name, const u32 status, const u8 severity, const u8 tlp_header_valid, struct aer_header_log_regs *tlp);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/pcie/aer.c (ffffffff8157fca6)
Location: include/ras/ras_event.h:298
Inline: True
Direct callers:
  - drivers/pci/pcie/aer.c:cper_print_aer
  - drivers/pci/pcie/aer.c:aer_print_error
```
**Symbols:**

```
ffffffff8157fca6-ffffffff8157fd22: trace_aer_event (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
void trace_aer_event(const char *dev_name, const u32 status, const u8 severity, const u8 tlp_header_valid, struct aer_header_log_regs *tlp);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/pcie/aer.c (ffffffff81591026)
Location: include/ras/ras_event.h:298
Inline: True
Direct callers:
  - drivers/pci/pcie/aer.c:cper_print_aer
  - drivers/pci/pcie/aer.c:aer_print_error
```
**Symbols:**

```
ffffffff81591026-ffffffff815910a2: trace_aer_event (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
void trace_aer_event(const char *dev_name, const u32 status, const u8 severity, const u8 tlp_header_valid, struct aer_header_log_regs *tlp);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/pcie/aer.c (ffffffff815ab4d6)
Location: include/ras/ras_event.h:298
Inline: True
Direct callers:
  - drivers/pci/pcie/aer.c:cper_print_aer
  - drivers/pci/pcie/aer.c:aer_print_error
```
**Symbols:**

```
ffffffff815ab4d6-ffffffff815ab567: trace_aer_event (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
