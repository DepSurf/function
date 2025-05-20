# Function: <code>acpi_get_gpe_status</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
acpi_status acpi_get_gpe_status(acpi_handle gpe_device, u32 gpe_number, acpi_event_status *event_status);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/evxfgpe.c (ffffffff814936ef)
Location: drivers/acpi/acpica/evxfgpe.c:574
Inline: False
Direct callers:
  - drivers/acpi/scan.c:acpi_add_single_object
  - drivers/acpi/ec.c:advance_transaction
```
**Symbols:**

```
ffffffff814936ef-ffffffff81493751: acpi_get_gpe_status (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
acpi_status acpi_get_gpe_status(acpi_handle gpe_device, u32 gpe_number, acpi_event_status *event_status);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/evxfgpe.c (ffffffff814e24e7)
Location: drivers/acpi/acpica/evxfgpe.c:574
Inline: False
Direct callers:
  - drivers/acpi/scan.c:acpi_add_single_object
  - drivers/acpi/ec.c:advance_transaction
```
**Symbols:**

```
ffffffff814e24e7-ffffffff814e2549: acpi_get_gpe_status (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
acpi_status acpi_get_gpe_status(acpi_handle gpe_device, u32 gpe_number, acpi_event_status *event_status);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/evxfgpe.c (ffffffff81504ea0)
Location: drivers/acpi/acpica/evxfgpe.c:617
Inline: False
Direct callers:
  - drivers/acpi/scan.c:acpi_add_single_object
  - drivers/acpi/ec.c:advance_transaction
```
**Symbols:**

```
ffffffff81504ea0-ffffffff81504f02: acpi_get_gpe_status (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
acpi_status acpi_get_gpe_status(acpi_handle gpe_device, u32 gpe_number, acpi_event_status *event_status);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/evxfgpe.c (ffffffff81515414)
Location: drivers/acpi/acpica/evxfgpe.c:625
Inline: False
Direct callers:
  - drivers/acpi/ec.c:ec_install_handlers
  - drivers/acpi/ec.c:advance_transaction
  - drivers/acpi/ec.c:acpi_ec_submit_request
```
**Symbols:**

```
ffffffff81515414-ffffffff81515476: acpi_get_gpe_status (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
acpi_status acpi_get_gpe_status(acpi_handle gpe_device, u32 gpe_number, acpi_event_status *event_status);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/evxfgpe.c (ffffffff8155fa80)
Location: drivers/acpi/acpica/evxfgpe.c:625
Inline: False
Direct callers:
  - drivers/acpi/ec.c:ec_install_handlers
  - drivers/acpi/ec.c:advance_transaction
  - drivers/acpi/ec.c:acpi_ec_submit_request
```
**Symbols:**

```
ffffffff8155fa80-ffffffff8155fb21: acpi_get_gpe_status (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
acpi_status acpi_get_gpe_status(acpi_handle gpe_device, u32 gpe_number, acpi_event_status *event_status);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/evxfgpe.c (ffffffff81596872)
Location: drivers/acpi/acpica/evxfgpe.c:610
Inline: False
Direct callers:
  - drivers/acpi/ec.c:ec_install_handlers
  - drivers/acpi/ec.c:advance_transaction
  - drivers/acpi/ec.c:acpi_ec_submit_request
```
**Symbols:**

```
ffffffff81596872-ffffffff81596913: acpi_get_gpe_status (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
acpi_status acpi_get_gpe_status(acpi_handle gpe_device, u32 gpe_number, acpi_event_status *event_status);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/evxfgpe.c (ffffffff815aef76)
Location: drivers/acpi/acpica/evxfgpe.c:610
Inline: False
Direct callers:
  - drivers/acpi/ec.c:ec_install_handlers
  - drivers/acpi/ec.c:advance_transaction
  - drivers/acpi/ec.c:acpi_ec_submit_request
```
**Symbols:**

```
ffffffff815aef76-ffffffff815af017: acpi_get_gpe_status (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
acpi_status acpi_get_gpe_status(acpi_handle gpe_device, u32 gpe_number, acpi_event_status *event_status);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/evxfgpe.c (ffffffff815e07db)
Location: drivers/acpi/acpica/evxfgpe.c:610
Inline: False
Direct callers:
  - drivers/acpi/ec.c:ec_install_handlers
  - drivers/acpi/ec.c:advance_transaction
  - drivers/acpi/ec.c:acpi_ec_submit_request
```
**Symbols:**

```
ffffffff815e07db-ffffffff815e0881: acpi_get_gpe_status (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
acpi_status acpi_get_gpe_status(acpi_handle gpe_device, u32 gpe_number, acpi_event_status *event_status);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/evxfgpe.c (ffffffff81601b1e)
Location: drivers/acpi/acpica/evxfgpe.c:610
Inline: False
Direct callers:
  - drivers/acpi/ec.c:ec_install_handlers
  - drivers/acpi/ec.c:advance_transaction
  - drivers/acpi/ec.c:acpi_ec_submit_request
```
**Symbols:**

```
ffffffff81601b1e-ffffffff81601bc4: acpi_get_gpe_status (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
acpi_status acpi_get_gpe_status(acpi_handle gpe_device, u32 gpe_number, acpi_event_status *event_status);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/evxfgpe.c (ffffffff816add63)
Location: drivers/acpi/acpica/evxfgpe.c:610
Inline: False
Direct callers:
  - drivers/acpi/ec.c:ec_install_handlers
  - drivers/acpi/ec.c:acpi_ec_start
  - drivers/acpi/ec.c:acpi_ec_transaction_unlocked
  - drivers/acpi/ec.c:advance_transaction
  - drivers/acpi/sysfs.c:get_status
```
**Symbols:**

```
ffffffff816add63-ffffffff816ade09: acpi_get_gpe_status (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
acpi_status acpi_get_gpe_status(acpi_handle gpe_device, u32 gpe_number, acpi_event_status *event_status);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/evxfgpe.c (ffffffff816cb6a2)
Location: drivers/acpi/acpica/evxfgpe.c:610
Inline: False
Direct callers:
  - drivers/acpi/ec.c:ec_install_handlers
  - drivers/acpi/ec.c:acpi_ec_start
  - drivers/acpi/ec.c:acpi_ec_transaction_unlocked
  - drivers/acpi/ec.c:advance_transaction
  - drivers/acpi/sysfs.c:get_status
```
**Symbols:**

```
ffffffff816cb6a2-ffffffff816cb748: acpi_get_gpe_status (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
acpi_status acpi_get_gpe_status(acpi_handle gpe_device, u32 gpe_number, acpi_event_status *event_status);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/evxfgpe.c (ffffffff816ad66e)
Location: drivers/acpi/acpica/evxfgpe.c:610
Inline: False
Direct callers:
  - drivers/acpi/ec.c:ec_install_handlers
  - drivers/acpi/ec.c:acpi_ec_start
  - drivers/acpi/ec.c:acpi_ec_transaction_unlocked
  - drivers/acpi/ec.c:advance_transaction
  - drivers/acpi/sysfs.c:get_status
```
**Symbols:**

```
ffffffff816ad66e-ffffffff816ad714: acpi_get_gpe_status (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
acpi_status acpi_get_gpe_status(acpi_handle gpe_device, u32 gpe_number, acpi_event_status *event_status);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/evxfgpe.c (ffffffff8172442d)
Location: drivers/acpi/acpica/evxfgpe.c:610
Inline: False
Direct callers:
  - drivers/acpi/ec.c:ec_install_handlers
  - drivers/acpi/ec.c:acpi_ec_start
  - drivers/acpi/ec.c:acpi_ec_transaction_unlocked
  - drivers/acpi/ec.c:advance_transaction
  - drivers/acpi/sysfs.c:get_status
```
**Symbols:**

```
ffffffff8172442d-ffffffff817244d3: acpi_get_gpe_status (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
acpi_status acpi_get_gpe_status(acpi_handle gpe_device, u32 gpe_number, acpi_event_status *event_status);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/evxfgpe.c (ffffffff81854a14)
Location: drivers/acpi/acpica/evxfgpe.c:610
Inline: False
Direct callers:
  - drivers/acpi/ec.c:acpi_ec_dispatch_gpe
  - drivers/acpi/ec.c:ec_install_handlers
  - drivers/acpi/ec.c:acpi_ec_start
  - drivers/acpi/ec.c:acpi_ec_transaction_unlocked
  - drivers/acpi/ec.c:advance_transaction
  - drivers/acpi/sysfs.c:get_status
```
**Symbols:**

```
ffffffff81854a14-ffffffff81854ac4: acpi_get_gpe_status (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
acpi_status acpi_get_gpe_status(acpi_handle gpe_device, u32 gpe_number, acpi_event_status *event_status);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/evxfgpe.c (ffffffff8198f3c0)
Location: drivers/acpi/acpica/evxfgpe.c:610
Inline: False
Direct callers:
  - drivers/acpi/ec.c:acpi_ec_dispatch_gpe
  - drivers/acpi/ec.c:ec_install_handlers
  - drivers/acpi/ec.c:advance_transaction
  - drivers/acpi/ec.c:acpi_ec_unmask_events
  - drivers/acpi/ec.c:acpi_ec_submit_request
  - drivers/acpi/sysfs.c:get_status
```
**Symbols:**

```
ffffffff8198f3c0-ffffffff8198f472: acpi_get_gpe_status (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
acpi_status acpi_get_gpe_status(acpi_handle gpe_device, u32 gpe_number, acpi_event_status *event_status);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/evxfgpe.c (ffffffff819d5e60)
Location: drivers/acpi/acpica/evxfgpe.c:610
Inline: False
Direct callers:
  - drivers/acpi/ec.c:acpi_ec_dispatch_gpe
  - drivers/acpi/ec.c:ec_install_handlers
  - drivers/acpi/ec.c:acpi_ec_unmask_events
  - drivers/acpi/ec.c:acpi_ec_submit_request
  - drivers/acpi/sysfs.c:get_status
```
**Symbols:**

```
ffffffff819d5e60-ffffffff819d5f12: acpi_get_gpe_status (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
acpi_status acpi_get_gpe_status(acpi_handle gpe_device, u32 gpe_number, acpi_event_status *event_status);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/evxfgpe.c (ffffffff81a20af0)
Location: drivers/acpi/acpica/evxfgpe.c:610
Inline: False
Direct callers:
  - drivers/acpi/ec.c:acpi_ec_dispatch_gpe
  - drivers/acpi/ec.c:ec_install_handlers
  - drivers/acpi/ec.c:acpi_ec_unmask_events
  - drivers/acpi/ec.c:acpi_ec_submit_request
  - drivers/acpi/sysfs.c:get_status
```
**Symbols:**

```
ffffffff81a20af0-ffffffff81a20ba2: acpi_get_gpe_status (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/acpi/ec.c (0)
Location: include/acpi/acpixf.h:742
Inline: True
```
```
In drivers/acpi/sysfs.c (0)
Location: include/acpi/acpixf.h:742
Inline: True
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
acpi_status acpi_get_gpe_status(acpi_handle gpe_device, u32 gpe_number, acpi_event_status *event_status);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/evxfgpe.c (ffffffff815e92a9)
Location: drivers/acpi/acpica/evxfgpe.c:610
Inline: False
Direct callers:
  - drivers/acpi/ec.c:ec_install_handlers
  - drivers/acpi/ec.c:advance_transaction
  - drivers/acpi/ec.c:acpi_ec_submit_request
```
**Symbols:**

```
ffffffff815e92a9-ffffffff815e930f: acpi_get_gpe_status (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
acpi_status acpi_get_gpe_status(acpi_handle gpe_device, u32 gpe_number, acpi_event_status *event_status);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/evxfgpe.c (ffffffff815d48d1)
Location: drivers/acpi/acpica/evxfgpe.c:610
Inline: False
Direct callers:
  - drivers/acpi/ec.c:ec_install_handlers
  - drivers/acpi/ec.c:advance_transaction
  - drivers/acpi/ec.c:acpi_ec_submit_request
```
**Symbols:**

```
ffffffff815d48d1-ffffffff815d4937: acpi_get_gpe_status (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
acpi_status acpi_get_gpe_status(acpi_handle gpe_device, u32 gpe_number, acpi_event_status *event_status);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/evxfgpe.c (ffffffff815f5dfe)
Location: drivers/acpi/acpica/evxfgpe.c:610
Inline: False
Direct callers:
  - drivers/acpi/ec.c:ec_install_handlers
  - drivers/acpi/ec.c:advance_transaction
  - drivers/acpi/ec.c:acpi_ec_submit_request
```
**Symbols:**

```
ffffffff815f5dfe-ffffffff815f5ea4: acpi_get_gpe_status (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
acpi_status acpi_get_gpe_status(acpi_handle gpe_device, u32 gpe_number, acpi_event_status *event_status);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/evxfgpe.c (ffffffff8160fcae)
Location: drivers/acpi/acpica/evxfgpe.c:610
Inline: False
Direct callers:
  - drivers/acpi/ec.c:ec_install_handlers
  - drivers/acpi/ec.c:advance_transaction
  - drivers/acpi/ec.c:acpi_ec_submit_request
```
**Symbols:**

```
ffffffff8160fcae-ffffffff8160fd54: acpi_get_gpe_status (STB_GLOBAL)
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
