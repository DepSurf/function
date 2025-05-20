# Function: <code>acpi_ev_install_gpe_handler</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/acpi/acpica/evxface.c (ffffffff81492ecd)
Location: drivers/acpi/acpica/evxface.c:750
Inline: True
Inline callers:
  - drivers/acpi/acpica/evxface.c:acpi_install_gpe_handler
  - drivers/acpi/acpica/evxface.c:acpi_install_gpe_raw_handler
Direct callers:
  - drivers/acpi/acpica/evxface.c:acpi_install_gpe_handler
  - drivers/acpi/acpica/evxface.c:acpi_install_gpe_raw_handler
```
**Symbols:**

```
ffffffff81492ecd-ffffffff8149305f: acpi_ev_install_gpe_handler.part.7 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/acpi/acpica/evxface.c (ffffffff814e1e8b)
Location: drivers/acpi/acpica/evxface.c:750
Inline: True
Inline callers:
  - drivers/acpi/acpica/evxface.c:acpi_install_gpe_raw_handler
  - drivers/acpi/acpica/evxface.c:acpi_install_gpe_handler
Direct callers:
  - drivers/acpi/acpica/evxface.c:acpi_install_gpe_raw_handler
  - drivers/acpi/acpica/evxface.c:acpi_install_gpe_handler
```
**Symbols:**

```
ffffffff814e1ccb-ffffffff814e1e5c: acpi_ev_install_gpe_handler.part.7 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/acpi/acpica/evxface.c (ffffffff815047a0)
Location: drivers/acpi/acpica/evxface.c:750
Inline: True
Inline callers:
  - drivers/acpi/acpica/evxface.c:acpi_install_gpe_raw_handler
  - drivers/acpi/acpica/evxface.c:acpi_install_gpe_handler
Direct callers:
  - drivers/acpi/acpica/evxface.c:acpi_install_gpe_raw_handler
  - drivers/acpi/acpica/evxface.c:acpi_install_gpe_handler
```
**Symbols:**

```
ffffffff8150460a-ffffffff8150479b: acpi_ev_install_gpe_handler.part.7 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/acpi/acpica/evxface.c (ffffffff81514d33)
Location: drivers/acpi/acpica/evxface.c:750
Inline: True
Inline callers:
  - drivers/acpi/acpica/evxface.c:acpi_install_gpe_raw_handler
  - drivers/acpi/acpica/evxface.c:acpi_install_gpe_handler
Direct callers:
  - drivers/acpi/acpica/evxface.c:acpi_install_gpe_raw_handler
  - drivers/acpi/acpica/evxface.c:acpi_install_gpe_handler
```
**Symbols:**

```
ffffffff81514b4f-ffffffff81514ccf: acpi_ev_install_gpe_handler.part.6 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
acpi_status acpi_ev_install_gpe_handler(acpi_handle gpe_device, u32 gpe_number, u32 type, u8 is_raw_handler, acpi_gpe_handler address, void *context);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/evxface.c (ffffffff8155e90b)
Location: drivers/acpi/acpica/evxface.c:750
Inline: True
Direct callers:
  - drivers/acpi/acpica/evxface.c:acpi_install_gpe_raw_handler
  - drivers/acpi/acpica/evxface.c:acpi_install_gpe_handler
```
**Symbols:**

```
ffffffff8155e90b-ffffffff8155eb2f: acpi_ev_install_gpe_handler (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
acpi_status acpi_ev_install_gpe_handler(acpi_handle gpe_device, u32 gpe_number, u32 type, u8 is_raw_handler, acpi_gpe_handler address, void *context);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/evxface.c (ffffffff815954f0)
Location: drivers/acpi/acpica/evxface.c:716
Inline: True
Direct callers:
  - drivers/acpi/acpica/evxface.c:acpi_install_gpe_raw_handler
  - drivers/acpi/acpica/evxface.c:acpi_install_gpe_handler
```
**Symbols:**

```
ffffffff815954f0-ffffffff81595714: acpi_ev_install_gpe_handler (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
acpi_status acpi_ev_install_gpe_handler(acpi_handle gpe_device, u32 gpe_number, u32 type, u8 is_raw_handler, acpi_gpe_handler address, void *context);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/evxface.c (ffffffff815adbfe)
Location: drivers/acpi/acpica/evxface.c:716
Inline: True
Direct callers:
  - drivers/acpi/acpica/evxface.c:acpi_install_gpe_raw_handler
  - drivers/acpi/acpica/evxface.c:acpi_install_gpe_handler
```
**Symbols:**

```
ffffffff815adbfe-ffffffff815ade22: acpi_ev_install_gpe_handler (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
acpi_status acpi_ev_install_gpe_handler(acpi_handle gpe_device, u32 gpe_number, u32 type, u8 is_raw_handler, acpi_gpe_handler address, void *context);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/evxface.c (ffffffff815df428)
Location: drivers/acpi/acpica/evxface.c:716
Inline: True
Direct callers:
  - drivers/acpi/acpica/evxface.c:acpi_install_gpe_raw_handler
  - drivers/acpi/acpica/evxface.c:acpi_install_gpe_handler
```
**Symbols:**

```
ffffffff815df428-ffffffff815df64f: acpi_ev_install_gpe_handler (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
acpi_status acpi_ev_install_gpe_handler(acpi_handle gpe_device, u32 gpe_number, u32 type, u8 is_raw_handler, acpi_gpe_handler address, void *context);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/evxface.c (ffffffff8160076b)
Location: drivers/acpi/acpica/evxface.c:716
Inline: True
Direct callers:
  - drivers/acpi/acpica/evxface.c:acpi_install_gpe_raw_handler
  - drivers/acpi/acpica/evxface.c:acpi_install_gpe_handler
```
**Symbols:**

```
ffffffff8160076b-ffffffff81600992: acpi_ev_install_gpe_handler (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
acpi_status acpi_ev_install_gpe_handler(acpi_handle gpe_device, u32 gpe_number, u32 type, u8 is_raw_handler, acpi_gpe_handler address, void *context);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/evxface.c (ffffffff816ac99f)
Location: drivers/acpi/acpica/evxface.c:716
Inline: False
Direct callers:
  - drivers/acpi/acpica/evxface.c:acpi_install_gpe_raw_handler
  - drivers/acpi/acpica/evxface.c:acpi_install_gpe_handler
```
**Symbols:**

```
ffffffff816ac99f-ffffffff816acbc3: acpi_ev_install_gpe_handler (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
acpi_status acpi_ev_install_gpe_handler(acpi_handle gpe_device, u32 gpe_number, u32 type, u8 is_raw_handler, acpi_gpe_handler address, void *context);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/evxface.c (ffffffff816ca2de)
Location: drivers/acpi/acpica/evxface.c:716
Inline: False
Direct callers:
  - drivers/acpi/acpica/evxface.c:acpi_install_gpe_raw_handler
  - drivers/acpi/acpica/evxface.c:acpi_install_gpe_handler
```
**Symbols:**

```
ffffffff816ca2de-ffffffff816ca502: acpi_ev_install_gpe_handler (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
acpi_status acpi_ev_install_gpe_handler(acpi_handle gpe_device, u32 gpe_number, u32 type, u8 is_raw_handler, acpi_gpe_handler address, void *context);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/evxface.c (ffffffff816ac2bf)
Location: drivers/acpi/acpica/evxface.c:716
Inline: False
Direct callers:
  - drivers/acpi/acpica/evxface.c:acpi_install_gpe_raw_handler
  - drivers/acpi/acpica/evxface.c:acpi_install_gpe_handler
```
**Symbols:**

```
ffffffff816ac2bf-ffffffff816ac4e3: acpi_ev_install_gpe_handler (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
acpi_status acpi_ev_install_gpe_handler(acpi_handle gpe_device, u32 gpe_number, u32 type, u8 is_raw_handler, acpi_gpe_handler address, void *context);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/evxface.c (ffffffff81722fdc)
Location: drivers/acpi/acpica/evxface.c:716
Inline: False
Direct callers:
  - drivers/acpi/acpica/evxface.c:acpi_install_gpe_raw_handler
  - drivers/acpi/acpica/evxface.c:acpi_install_gpe_handler
```
**Symbols:**

```
ffffffff81722fdc-ffffffff81723200: acpi_ev_install_gpe_handler (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
acpi_status acpi_ev_install_gpe_handler(acpi_handle gpe_device, u32 gpe_number, u32 type, u8 is_raw_handler, acpi_gpe_handler address, void *context);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/evxface.c (ffffffff818534ad)
Location: drivers/acpi/acpica/evxface.c:716
Inline: False
Direct callers:
  - drivers/acpi/acpica/evxface.c:acpi_install_gpe_raw_handler
  - drivers/acpi/acpica/evxface.c:acpi_install_gpe_handler
```
**Symbols:**

```
ffffffff818534ad-ffffffff818536df: acpi_ev_install_gpe_handler (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
acpi_status acpi_ev_install_gpe_handler(acpi_handle gpe_device, u32 gpe_number, u32 type, u8 is_raw_handler, acpi_gpe_handler address, void *context);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/evxface.c (ffffffff8198dad0)
Location: drivers/acpi/acpica/evxface.c:716
Inline: False
Direct callers:
  - drivers/acpi/acpica/evxface.c:acpi_install_gpe_raw_handler
  - drivers/acpi/acpica/evxface.c:acpi_install_gpe_handler
```
**Symbols:**

```
ffffffff8198dad0-ffffffff8198dd3a: acpi_ev_install_gpe_handler (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
acpi_status acpi_ev_install_gpe_handler(acpi_handle gpe_device, u32 gpe_number, u32 type, u8 is_raw_handler, acpi_gpe_handler address, void *context);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/evxface.c (ffffffff819d4560)
Location: drivers/acpi/acpica/evxface.c:716
Inline: False
Direct callers:
  - drivers/acpi/acpica/evxface.c:acpi_install_gpe_raw_handler
  - drivers/acpi/acpica/evxface.c:acpi_install_gpe_handler
```
**Symbols:**

```
ffffffff819d4560-ffffffff819d47ca: acpi_ev_install_gpe_handler (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
acpi_status acpi_ev_install_gpe_handler(acpi_handle gpe_device, u32 gpe_number, u32 type, u8 is_raw_handler, acpi_gpe_handler address, void *context);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/evxface.c (ffffffff81a1f1c0)
Location: drivers/acpi/acpica/evxface.c:716
Inline: False
Direct callers:
  - drivers/acpi/acpica/evxface.c:acpi_install_gpe_raw_handler
  - drivers/acpi/acpica/evxface.c:acpi_install_gpe_handler
```
**Symbols:**

```
ffffffff81a1f1c0-ffffffff81a1f459: acpi_ev_install_gpe_handler (STB_LOCAL)
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

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/acpi/acpica/evxface.c (ffffffff815e8ab7)
Location: drivers/acpi/acpica/evxface.c:716
Inline: True
Inline callers:
  - drivers/acpi/acpica/evxface.c:acpi_install_gpe_raw_handler
  - drivers/acpi/acpica/evxface.c:acpi_install_gpe_handler
Direct callers:
  - drivers/acpi/acpica/evxface.c:acpi_install_gpe_raw_handler
  - drivers/acpi/acpica/evxface.c:acpi_install_gpe_handler
```
**Symbols:**

```
ffffffff815e88da-ffffffff815e8a54: acpi_ev_install_gpe_handler.part.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/acpi/acpica/evxface.c (ffffffff815d4081)
Location: drivers/acpi/acpica/evxface.c:716
Inline: True
Inline callers:
  - drivers/acpi/acpica/evxface.c:acpi_install_gpe_raw_handler
  - drivers/acpi/acpica/evxface.c:acpi_install_gpe_handler
Direct callers:
  - drivers/acpi/acpica/evxface.c:acpi_install_gpe_raw_handler
  - drivers/acpi/acpica/evxface.c:acpi_install_gpe_handler
```
**Symbols:**

```
ffffffff815d3f05-ffffffff815d407c: acpi_ev_install_gpe_handler.part.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
acpi_status acpi_ev_install_gpe_handler(acpi_handle gpe_device, u32 gpe_number, u32 type, u8 is_raw_handler, acpi_gpe_handler address, void *context);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/evxface.c (ffffffff815f4a4b)
Location: drivers/acpi/acpica/evxface.c:716
Inline: True
Direct callers:
  - drivers/acpi/acpica/evxface.c:acpi_install_gpe_raw_handler
  - drivers/acpi/acpica/evxface.c:acpi_install_gpe_handler
```
**Symbols:**

```
ffffffff815f4a4b-ffffffff815f4c72: acpi_ev_install_gpe_handler (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
acpi_status acpi_ev_install_gpe_handler(acpi_handle gpe_device, u32 gpe_number, u32 type, u8 is_raw_handler, acpi_gpe_handler address, void *context);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/evxface.c (ffffffff8160e8fb)
Location: drivers/acpi/acpica/evxface.c:716
Inline: True
Direct callers:
  - drivers/acpi/acpica/evxface.c:acpi_install_gpe_raw_handler
  - drivers/acpi/acpica/evxface.c:acpi_install_gpe_handler
```
**Symbols:**

```
ffffffff8160e8fb-ffffffff8160eb22: acpi_ev_install_gpe_handler (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
No changes between <code>generic</code> and <code>gcp</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>lowlatency</code> ✅
</li>
</ul>
