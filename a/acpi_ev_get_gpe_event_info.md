# Function: <code>acpi_ev_get_gpe_event_info</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
struct acpi_gpe_event_info *acpi_ev_get_gpe_event_info(acpi_handle gpe_device, u32 gpe_number);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/evgpe.c (ffffffff81490148)
Location: drivers/acpi/acpica/evgpe.c:272
Inline: False
Direct callers:
  - drivers/acpi/acpica/evxfgpe.c:acpi_enable_gpe
  - drivers/acpi/acpica/evxfgpe.c:acpi_mark_gpe_for_wake
  - drivers/acpi/acpica/evxfgpe.c:acpi_disable_gpe
  - drivers/acpi/acpica/evxfgpe.c:acpi_set_gpe
  - drivers/acpi/acpica/evxfgpe.c:acpi_set_gpe_wake_mask
  - drivers/acpi/acpica/evxfgpe.c:acpi_clear_gpe
  - drivers/acpi/acpica/evxfgpe.c:acpi_get_gpe_status
  - drivers/acpi/acpica/evxfgpe.c:acpi_finish_gpe
  - drivers/acpi/acpica/evxfgpe.c:acpi_setup_gpe_for_wake
```
**Symbols:**

```
ffffffff81490148-ffffffff8149019d: acpi_ev_get_gpe_event_info (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
struct acpi_gpe_event_info *acpi_ev_get_gpe_event_info(acpi_handle gpe_device, u32 gpe_number);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/evgpe.c (ffffffff814def3f)
Location: drivers/acpi/acpica/evgpe.c:272
Inline: False
Direct callers:
  - drivers/acpi/acpica/evxfgpe.c:acpi_finish_gpe
  - drivers/acpi/acpica/evxfgpe.c:acpi_get_gpe_status
  - drivers/acpi/acpica/evxfgpe.c:acpi_clear_gpe
  - drivers/acpi/acpica/evxfgpe.c:acpi_set_gpe_wake_mask
  - drivers/acpi/acpica/evxfgpe.c:acpi_setup_gpe_for_wake
  - drivers/acpi/acpica/evxfgpe.c:acpi_mark_gpe_for_wake
  - drivers/acpi/acpica/evxfgpe.c:acpi_set_gpe
  - drivers/acpi/acpica/evxfgpe.c:acpi_disable_gpe
  - drivers/acpi/acpica/evxfgpe.c:acpi_enable_gpe
```
**Symbols:**

```
ffffffff814def3f-ffffffff814def8e: acpi_ev_get_gpe_event_info (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
struct acpi_gpe_event_info *acpi_ev_get_gpe_event_info(acpi_handle gpe_device, u32 gpe_number);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/evgpe.c (ffffffff8150189e)
Location: drivers/acpi/acpica/evgpe.c:326
Inline: False
Direct callers:
  - drivers/acpi/acpica/evxfgpe.c:acpi_finish_gpe
  - drivers/acpi/acpica/evxfgpe.c:acpi_get_gpe_status
  - drivers/acpi/acpica/evxfgpe.c:acpi_clear_gpe
  - drivers/acpi/acpica/evxfgpe.c:acpi_set_gpe_wake_mask
  - drivers/acpi/acpica/evxfgpe.c:acpi_setup_gpe_for_wake
  - drivers/acpi/acpica/evxfgpe.c:acpi_mark_gpe_for_wake
  - drivers/acpi/acpica/evxfgpe.c:acpi_mask_gpe
  - drivers/acpi/acpica/evxfgpe.c:acpi_set_gpe
  - drivers/acpi/acpica/evxfgpe.c:acpi_disable_gpe
  - drivers/acpi/acpica/evxfgpe.c:acpi_enable_gpe
```
**Symbols:**

```
ffffffff8150189e-ffffffff815018ed: acpi_ev_get_gpe_event_info (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
struct acpi_gpe_event_info *acpi_ev_get_gpe_event_info(acpi_handle gpe_device, u32 gpe_number);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/evgpe.c (ffffffff81511d76)
Location: drivers/acpi/acpica/evgpe.c:326
Inline: False
Direct callers:
  - drivers/acpi/acpica/evxfgpe.c:acpi_finish_gpe
  - drivers/acpi/acpica/evxfgpe.c:acpi_get_gpe_status
  - drivers/acpi/acpica/evxfgpe.c:acpi_clear_gpe
  - drivers/acpi/acpica/evxfgpe.c:acpi_set_gpe_wake_mask
  - drivers/acpi/acpica/evxfgpe.c:acpi_setup_gpe_for_wake
  - drivers/acpi/acpica/evxfgpe.c:acpi_mark_gpe_for_wake
  - drivers/acpi/acpica/evxfgpe.c:acpi_mask_gpe
  - drivers/acpi/acpica/evxfgpe.c:acpi_set_gpe
  - drivers/acpi/acpica/evxfgpe.c:acpi_disable_gpe
  - drivers/acpi/acpica/evxfgpe.c:acpi_enable_gpe
```
**Symbols:**

```
ffffffff81511d76-ffffffff81511dc5: acpi_ev_get_gpe_event_info (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
struct acpi_gpe_event_info *acpi_ev_get_gpe_event_info(acpi_handle gpe_device, u32 gpe_number);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/evgpe.c (ffffffff81559c70)
Location: drivers/acpi/acpica/evgpe.c:326
Inline: False
Direct callers:
  - drivers/acpi/acpica/evxfgpe.c:acpi_finish_gpe
  - drivers/acpi/acpica/evxfgpe.c:acpi_get_gpe_status
  - drivers/acpi/acpica/evxfgpe.c:acpi_clear_gpe
  - drivers/acpi/acpica/evxfgpe.c:acpi_set_gpe_wake_mask
  - drivers/acpi/acpica/evxfgpe.c:acpi_setup_gpe_for_wake
  - drivers/acpi/acpica/evxfgpe.c:acpi_mark_gpe_for_wake
  - drivers/acpi/acpica/evxfgpe.c:acpi_mask_gpe
  - drivers/acpi/acpica/evxfgpe.c:acpi_set_gpe
  - drivers/acpi/acpica/evxfgpe.c:acpi_disable_gpe
  - drivers/acpi/acpica/evxfgpe.c:acpi_enable_gpe
  - drivers/acpi/acpica/dbcmds.c:acpi_db_generate_gpe
```
**Symbols:**

```
ffffffff81559c70-ffffffff81559cce: acpi_ev_get_gpe_event_info (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
struct acpi_gpe_event_info *acpi_ev_get_gpe_event_info(acpi_handle gpe_device, u32 gpe_number);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/evgpe.c (ffffffff81590770)
Location: drivers/acpi/acpica/evgpe.c:285
Inline: True
Direct callers:
  - drivers/acpi/acpica/evgpe.c:acpi_ev_detect_gpe
  - drivers/acpi/acpica/evxfgpe.c:acpi_finish_gpe
  - drivers/acpi/acpica/evxfgpe.c:acpi_get_gpe_status
  - drivers/acpi/acpica/evxfgpe.c:acpi_clear_gpe
  - drivers/acpi/acpica/evxfgpe.c:acpi_set_gpe_wake_mask
  - drivers/acpi/acpica/evxfgpe.c:acpi_setup_gpe_for_wake
  - drivers/acpi/acpica/evxfgpe.c:acpi_mark_gpe_for_wake
  - drivers/acpi/acpica/evxfgpe.c:acpi_mask_gpe
  - drivers/acpi/acpica/evxfgpe.c:acpi_set_gpe
  - drivers/acpi/acpica/evxfgpe.c:acpi_disable_gpe
  - drivers/acpi/acpica/evxfgpe.c:acpi_enable_gpe
  - drivers/acpi/acpica/dbcmds.c:acpi_db_generate_gpe
```
**Symbols:**

```
ffffffff81590770-ffffffff815907ce: acpi_ev_get_gpe_event_info (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
struct acpi_gpe_event_info *acpi_ev_get_gpe_event_info(acpi_handle gpe_device, u32 gpe_number);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/evgpe.c (ffffffff815a8dfa)
Location: drivers/acpi/acpica/evgpe.c:285
Inline: True
Direct callers:
  - drivers/acpi/acpica/evgpe.c:acpi_ev_detect_gpe
  - drivers/acpi/acpica/evxfgpe.c:acpi_finish_gpe
  - drivers/acpi/acpica/evxfgpe.c:acpi_get_gpe_status
  - drivers/acpi/acpica/evxfgpe.c:acpi_clear_gpe
  - drivers/acpi/acpica/evxfgpe.c:acpi_set_gpe_wake_mask
  - drivers/acpi/acpica/evxfgpe.c:acpi_setup_gpe_for_wake
  - drivers/acpi/acpica/evxfgpe.c:acpi_mark_gpe_for_wake
  - drivers/acpi/acpica/evxfgpe.c:acpi_mask_gpe
  - drivers/acpi/acpica/evxfgpe.c:acpi_set_gpe
  - drivers/acpi/acpica/evxfgpe.c:acpi_disable_gpe
  - drivers/acpi/acpica/evxfgpe.c:acpi_enable_gpe
  - drivers/acpi/acpica/dbcmds.c:acpi_db_generate_gpe
```
**Symbols:**

```
ffffffff815a8dfa-ffffffff815a8e56: acpi_ev_get_gpe_event_info (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
struct acpi_gpe_event_info *acpi_ev_get_gpe_event_info(acpi_handle gpe_device, u32 gpe_number);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/evgpe.c (ffffffff815da57f)
Location: drivers/acpi/acpica/evgpe.c:291
Inline: True
Direct callers:
  - drivers/acpi/acpica/evgpe.c:acpi_ev_detect_gpe
  - drivers/acpi/acpica/evxfgpe.c:acpi_finish_gpe
  - drivers/acpi/acpica/evxfgpe.c:acpi_get_gpe_status
  - drivers/acpi/acpica/evxfgpe.c:acpi_clear_gpe
  - drivers/acpi/acpica/evxfgpe.c:acpi_set_gpe_wake_mask
  - drivers/acpi/acpica/evxfgpe.c:acpi_setup_gpe_for_wake
  - drivers/acpi/acpica/evxfgpe.c:acpi_mark_gpe_for_wake
  - drivers/acpi/acpica/evxfgpe.c:acpi_mask_gpe
  - drivers/acpi/acpica/evxfgpe.c:acpi_set_gpe
  - drivers/acpi/acpica/evxfgpe.c:acpi_disable_gpe
  - drivers/acpi/acpica/evxfgpe.c:acpi_enable_gpe
  - drivers/acpi/acpica/dbcmds.c:acpi_db_generate_gpe
```
**Symbols:**

```
ffffffff815da57f-ffffffff815da5e0: acpi_ev_get_gpe_event_info (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
struct acpi_gpe_event_info *acpi_ev_get_gpe_event_info(acpi_handle gpe_device, u32 gpe_number);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/evgpe.c (ffffffff815fb8bf)
Location: drivers/acpi/acpica/evgpe.c:291
Inline: True
Direct callers:
  - drivers/acpi/acpica/evgpe.c:acpi_ev_detect_gpe
  - drivers/acpi/acpica/evxfgpe.c:acpi_finish_gpe
  - drivers/acpi/acpica/evxfgpe.c:acpi_get_gpe_status
  - drivers/acpi/acpica/evxfgpe.c:acpi_clear_gpe
  - drivers/acpi/acpica/evxfgpe.c:acpi_set_gpe_wake_mask
  - drivers/acpi/acpica/evxfgpe.c:acpi_setup_gpe_for_wake
  - drivers/acpi/acpica/evxfgpe.c:acpi_mark_gpe_for_wake
  - drivers/acpi/acpica/evxfgpe.c:acpi_mask_gpe
  - drivers/acpi/acpica/evxfgpe.c:acpi_set_gpe
  - drivers/acpi/acpica/evxfgpe.c:acpi_disable_gpe
  - drivers/acpi/acpica/evxfgpe.c:acpi_enable_gpe
  - drivers/acpi/acpica/dbcmds.c:acpi_db_generate_gpe
```
**Symbols:**

```
ffffffff815fb8bf-ffffffff815fb920: acpi_ev_get_gpe_event_info (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
struct acpi_gpe_event_info *acpi_ev_get_gpe_event_info(acpi_handle gpe_device, u32 gpe_number);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/evgpe.c (ffffffff816a79e2)
Location: drivers/acpi/acpica/evgpe.c:291
Inline: True
Direct callers:
  - drivers/acpi/acpica/evgpe.c:acpi_ev_detect_gpe
  - drivers/acpi/acpica/evxface.c:acpi_remove_gpe_handler
  - drivers/acpi/acpica/evxface.c:acpi_ev_install_gpe_handler
  - drivers/acpi/acpica/evxfgpe.c:acpi_finish_gpe
  - drivers/acpi/acpica/evxfgpe.c:acpi_get_gpe_status
  - drivers/acpi/acpica/evxfgpe.c:acpi_clear_gpe
  - drivers/acpi/acpica/evxfgpe.c:acpi_set_gpe_wake_mask
  - drivers/acpi/acpica/evxfgpe.c:acpi_setup_gpe_for_wake
  - drivers/acpi/acpica/evxfgpe.c:acpi_mark_gpe_for_wake
  - drivers/acpi/acpica/evxfgpe.c:acpi_mask_gpe
  - drivers/acpi/acpica/evxfgpe.c:acpi_set_gpe
  - drivers/acpi/acpica/evxfgpe.c:acpi_disable_gpe
  - drivers/acpi/acpica/evxfgpe.c:acpi_enable_gpe
  - drivers/acpi/acpica/hwgpe.c:acpi_hw_check_all_gpes
  - drivers/acpi/acpica/dbcmds.c:acpi_db_generate_gpe
```
**Symbols:**

```
ffffffff816a79e2-ffffffff816a7a43: acpi_ev_get_gpe_event_info (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
struct acpi_gpe_event_info *acpi_ev_get_gpe_event_info(acpi_handle gpe_device, u32 gpe_number);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/evgpe.c (ffffffff816c51d8)
Location: drivers/acpi/acpica/evgpe.c:291
Inline: True
Direct callers:
  - drivers/acpi/acpica/evgpe.c:acpi_ev_detect_gpe
  - drivers/acpi/acpica/evxface.c:acpi_remove_gpe_handler
  - drivers/acpi/acpica/evxface.c:acpi_ev_install_gpe_handler
  - drivers/acpi/acpica/evxfgpe.c:acpi_finish_gpe
  - drivers/acpi/acpica/evxfgpe.c:acpi_get_gpe_status
  - drivers/acpi/acpica/evxfgpe.c:acpi_clear_gpe
  - drivers/acpi/acpica/evxfgpe.c:acpi_set_gpe_wake_mask
  - drivers/acpi/acpica/evxfgpe.c:acpi_setup_gpe_for_wake
  - drivers/acpi/acpica/evxfgpe.c:acpi_mark_gpe_for_wake
  - drivers/acpi/acpica/evxfgpe.c:acpi_mask_gpe
  - drivers/acpi/acpica/evxfgpe.c:acpi_set_gpe
  - drivers/acpi/acpica/evxfgpe.c:acpi_disable_gpe
  - drivers/acpi/acpica/evxfgpe.c:acpi_enable_gpe
  - drivers/acpi/acpica/hwgpe.c:acpi_hw_check_all_gpes
  - drivers/acpi/acpica/dbcmds.c:acpi_db_generate_gpe
```
**Symbols:**

```
ffffffff816c51d8-ffffffff816c5239: acpi_ev_get_gpe_event_info (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
struct acpi_gpe_event_info *acpi_ev_get_gpe_event_info(acpi_handle gpe_device, u32 gpe_number);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/evgpe.c (ffffffff816a725a)
Location: drivers/acpi/acpica/evgpe.c:291
Inline: True
Direct callers:
  - drivers/acpi/acpica/evgpe.c:acpi_ev_detect_gpe
  - drivers/acpi/acpica/evxface.c:acpi_remove_gpe_handler
  - drivers/acpi/acpica/evxface.c:acpi_ev_install_gpe_handler
  - drivers/acpi/acpica/evxfgpe.c:acpi_finish_gpe
  - drivers/acpi/acpica/evxfgpe.c:acpi_get_gpe_status
  - drivers/acpi/acpica/evxfgpe.c:acpi_clear_gpe
  - drivers/acpi/acpica/evxfgpe.c:acpi_set_gpe_wake_mask
  - drivers/acpi/acpica/evxfgpe.c:acpi_setup_gpe_for_wake
  - drivers/acpi/acpica/evxfgpe.c:acpi_mark_gpe_for_wake
  - drivers/acpi/acpica/evxfgpe.c:acpi_mask_gpe
  - drivers/acpi/acpica/evxfgpe.c:acpi_set_gpe
  - drivers/acpi/acpica/evxfgpe.c:acpi_disable_gpe
  - drivers/acpi/acpica/evxfgpe.c:acpi_enable_gpe
  - drivers/acpi/acpica/hwgpe.c:acpi_hw_check_all_gpes
  - drivers/acpi/acpica/dbcmds.c:acpi_db_generate_gpe
```
**Symbols:**

```
ffffffff816a725a-ffffffff816a72bb: acpi_ev_get_gpe_event_info (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
struct acpi_gpe_event_info *acpi_ev_get_gpe_event_info(acpi_handle gpe_device, u32 gpe_number);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/evgpe.c (ffffffff8171dea1)
Location: drivers/acpi/acpica/evgpe.c:291
Inline: True
Direct callers:
  - drivers/acpi/acpica/evgpe.c:acpi_ev_detect_gpe
  - drivers/acpi/acpica/evxface.c:acpi_remove_gpe_handler
  - drivers/acpi/acpica/evxface.c:acpi_ev_install_gpe_handler
  - drivers/acpi/acpica/evxfgpe.c:acpi_finish_gpe
  - drivers/acpi/acpica/evxfgpe.c:acpi_get_gpe_status
  - drivers/acpi/acpica/evxfgpe.c:acpi_clear_gpe
  - drivers/acpi/acpica/evxfgpe.c:acpi_set_gpe_wake_mask
  - drivers/acpi/acpica/evxfgpe.c:acpi_setup_gpe_for_wake
  - drivers/acpi/acpica/evxfgpe.c:acpi_mark_gpe_for_wake
  - drivers/acpi/acpica/evxfgpe.c:acpi_mask_gpe
  - drivers/acpi/acpica/evxfgpe.c:acpi_set_gpe
  - drivers/acpi/acpica/evxfgpe.c:acpi_disable_gpe
  - drivers/acpi/acpica/evxfgpe.c:acpi_enable_gpe
  - drivers/acpi/acpica/hwgpe.c:acpi_hw_check_all_gpes
  - drivers/acpi/acpica/dbcmds.c:acpi_db_generate_gpe
```
**Symbols:**

```
ffffffff8171dea1-ffffffff8171df02: acpi_ev_get_gpe_event_info (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
struct acpi_gpe_event_info *acpi_ev_get_gpe_event_info(acpi_handle gpe_device, u32 gpe_number);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/evgpe.c (ffffffff8184df56)
Location: drivers/acpi/acpica/evgpe.c:291
Inline: False
Direct callers:
  - drivers/acpi/acpica/evgpe.c:acpi_ev_detect_gpe
  - drivers/acpi/acpica/evxface.c:acpi_remove_gpe_handler
  - drivers/acpi/acpica/evxface.c:acpi_ev_install_gpe_handler
  - drivers/acpi/acpica/evxfgpe.c:acpi_finish_gpe
  - drivers/acpi/acpica/evxfgpe.c:acpi_get_gpe_status
  - drivers/acpi/acpica/evxfgpe.c:acpi_clear_gpe
  - drivers/acpi/acpica/evxfgpe.c:acpi_set_gpe_wake_mask
  - drivers/acpi/acpica/evxfgpe.c:acpi_setup_gpe_for_wake
  - drivers/acpi/acpica/evxfgpe.c:acpi_mark_gpe_for_wake
  - drivers/acpi/acpica/evxfgpe.c:acpi_mask_gpe
  - drivers/acpi/acpica/evxfgpe.c:acpi_set_gpe
  - drivers/acpi/acpica/evxfgpe.c:acpi_disable_gpe
  - drivers/acpi/acpica/evxfgpe.c:acpi_enable_gpe
  - drivers/acpi/acpica/hwgpe.c:acpi_hw_check_all_gpes
  - drivers/acpi/acpica/dbcmds.c:acpi_db_generate_gpe
```
**Symbols:**

```
ffffffff8184df56-ffffffff8184dfbe: acpi_ev_get_gpe_event_info (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
struct acpi_gpe_event_info *acpi_ev_get_gpe_event_info(acpi_handle gpe_device, u32 gpe_number);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/evgpe.c (ffffffff81987580)
Location: drivers/acpi/acpica/evgpe.c:291
Inline: False
Direct callers:
  - drivers/acpi/acpica/evgpe.c:acpi_ev_detect_gpe
  - drivers/acpi/acpica/evxface.c:acpi_remove_gpe_handler
  - drivers/acpi/acpica/evxface.c:acpi_ev_install_gpe_handler
  - drivers/acpi/acpica/evxfgpe.c:acpi_finish_gpe
  - drivers/acpi/acpica/evxfgpe.c:acpi_get_gpe_status
  - drivers/acpi/acpica/evxfgpe.c:acpi_clear_gpe
  - drivers/acpi/acpica/evxfgpe.c:acpi_set_gpe_wake_mask
  - drivers/acpi/acpica/evxfgpe.c:acpi_setup_gpe_for_wake
  - drivers/acpi/acpica/evxfgpe.c:acpi_mark_gpe_for_wake
  - drivers/acpi/acpica/evxfgpe.c:acpi_mask_gpe
  - drivers/acpi/acpica/evxfgpe.c:acpi_set_gpe
  - drivers/acpi/acpica/evxfgpe.c:acpi_disable_gpe
  - drivers/acpi/acpica/evxfgpe.c:acpi_enable_gpe
  - drivers/acpi/acpica/hwgpe.c:acpi_hw_check_all_gpes
  - drivers/acpi/acpica/dbcmds.c:acpi_db_generate_gpe
  - drivers/acpi/acpica/dbcmds.c:acpi_db_generate_gpe
```
**Symbols:**

```
ffffffff81987580-ffffffff81987636: acpi_ev_get_gpe_event_info (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
struct acpi_gpe_event_info *acpi_ev_get_gpe_event_info(acpi_handle gpe_device, u32 gpe_number);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/evgpe.c (ffffffff819cdfc0)
Location: drivers/acpi/acpica/evgpe.c:291
Inline: False
Direct callers:
  - drivers/acpi/acpica/evgpe.c:acpi_ev_detect_gpe
  - drivers/acpi/acpica/evxface.c:acpi_remove_gpe_handler
  - drivers/acpi/acpica/evxface.c:acpi_ev_install_gpe_handler
  - drivers/acpi/acpica/evxfgpe.c:acpi_finish_gpe
  - drivers/acpi/acpica/evxfgpe.c:acpi_get_gpe_status
  - drivers/acpi/acpica/evxfgpe.c:acpi_clear_gpe
  - drivers/acpi/acpica/evxfgpe.c:acpi_set_gpe_wake_mask
  - drivers/acpi/acpica/evxfgpe.c:acpi_setup_gpe_for_wake
  - drivers/acpi/acpica/evxfgpe.c:acpi_mark_gpe_for_wake
  - drivers/acpi/acpica/evxfgpe.c:acpi_mask_gpe
  - drivers/acpi/acpica/evxfgpe.c:acpi_set_gpe
  - drivers/acpi/acpica/evxfgpe.c:acpi_disable_gpe
  - drivers/acpi/acpica/evxfgpe.c:acpi_enable_gpe
  - drivers/acpi/acpica/hwgpe.c:acpi_hw_check_all_gpes
  - drivers/acpi/acpica/dbcmds.c:acpi_db_generate_gpe
  - drivers/acpi/acpica/dbcmds.c:acpi_db_generate_gpe
```
**Symbols:**

```
ffffffff819cdfc0-ffffffff819ce076: acpi_ev_get_gpe_event_info (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
struct acpi_gpe_event_info *acpi_ev_get_gpe_event_info(acpi_handle gpe_device, u32 gpe_number);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/evgpe.c (ffffffff81a18a90)
Location: drivers/acpi/acpica/evgpe.c:291
Inline: False
Direct callers:
  - drivers/acpi/acpica/evgpe.c:acpi_ev_detect_gpe
  - drivers/acpi/acpica/evxface.c:acpi_remove_gpe_handler
  - drivers/acpi/acpica/evxface.c:acpi_ev_install_gpe_handler
  - drivers/acpi/acpica/evxfgpe.c:acpi_finish_gpe
  - drivers/acpi/acpica/evxfgpe.c:acpi_get_gpe_status
  - drivers/acpi/acpica/evxfgpe.c:acpi_clear_gpe
  - drivers/acpi/acpica/evxfgpe.c:acpi_set_gpe_wake_mask
  - drivers/acpi/acpica/evxfgpe.c:acpi_setup_gpe_for_wake
  - drivers/acpi/acpica/evxfgpe.c:acpi_mark_gpe_for_wake
  - drivers/acpi/acpica/evxfgpe.c:acpi_mask_gpe
  - drivers/acpi/acpica/evxfgpe.c:acpi_set_gpe
  - drivers/acpi/acpica/evxfgpe.c:acpi_disable_gpe
  - drivers/acpi/acpica/evxfgpe.c:acpi_enable_gpe
  - drivers/acpi/acpica/hwgpe.c:acpi_hw_check_all_gpes
  - drivers/acpi/acpica/dbcmds.c:acpi_db_generate_gpe
  - drivers/acpi/acpica/dbcmds.c:acpi_db_generate_gpe
```
**Symbols:**

```
ffffffff81a18a90-ffffffff81a18b46: acpi_ev_get_gpe_event_info (STB_GLOBAL)
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
<summary>In <code>aws</code>: Selective Inline ⚠️</summary>

```c
struct acpi_gpe_event_info *acpi_ev_get_gpe_event_info(acpi_handle gpe_device, u32 gpe_number);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/evgpe.c (ffffffff815e5955)
Location: drivers/acpi/acpica/evgpe.c:291
Inline: True
Direct callers:
  - drivers/acpi/acpica/evgpe.c:acpi_ev_detect_gpe
  - drivers/acpi/acpica/evxfgpe.c:acpi_finish_gpe
  - drivers/acpi/acpica/evxfgpe.c:acpi_get_gpe_status
  - drivers/acpi/acpica/evxfgpe.c:acpi_clear_gpe
  - drivers/acpi/acpica/evxfgpe.c:acpi_set_gpe_wake_mask
  - drivers/acpi/acpica/evxfgpe.c:acpi_setup_gpe_for_wake
  - drivers/acpi/acpica/evxfgpe.c:acpi_mark_gpe_for_wake
  - drivers/acpi/acpica/evxfgpe.c:acpi_mask_gpe
  - drivers/acpi/acpica/evxfgpe.c:acpi_set_gpe
  - drivers/acpi/acpica/evxfgpe.c:acpi_disable_gpe
  - drivers/acpi/acpica/evxfgpe.c:acpi_enable_gpe
```
**Symbols:**

```
ffffffff815e5955-ffffffff815e59a7: acpi_ev_get_gpe_event_info (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
struct acpi_gpe_event_info *acpi_ev_get_gpe_event_info(acpi_handle gpe_device, u32 gpe_number);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/evgpe.c (ffffffff815d0fbc)
Location: drivers/acpi/acpica/evgpe.c:291
Inline: True
Direct callers:
  - drivers/acpi/acpica/evgpe.c:acpi_ev_detect_gpe
  - drivers/acpi/acpica/evxfgpe.c:acpi_finish_gpe
  - drivers/acpi/acpica/evxfgpe.c:acpi_get_gpe_status
  - drivers/acpi/acpica/evxfgpe.c:acpi_clear_gpe
  - drivers/acpi/acpica/evxfgpe.c:acpi_set_gpe_wake_mask
  - drivers/acpi/acpica/evxfgpe.c:acpi_setup_gpe_for_wake
  - drivers/acpi/acpica/evxfgpe.c:acpi_mark_gpe_for_wake
  - drivers/acpi/acpica/evxfgpe.c:acpi_mask_gpe
  - drivers/acpi/acpica/evxfgpe.c:acpi_set_gpe
  - drivers/acpi/acpica/evxfgpe.c:acpi_disable_gpe
  - drivers/acpi/acpica/evxfgpe.c:acpi_enable_gpe
```
**Symbols:**

```
ffffffff815d0fbc-ffffffff815d100e: acpi_ev_get_gpe_event_info (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
struct acpi_gpe_event_info *acpi_ev_get_gpe_event_info(acpi_handle gpe_device, u32 gpe_number);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/evgpe.c (ffffffff815efb9f)
Location: drivers/acpi/acpica/evgpe.c:291
Inline: True
Direct callers:
  - drivers/acpi/acpica/evgpe.c:acpi_ev_detect_gpe
  - drivers/acpi/acpica/evxfgpe.c:acpi_finish_gpe
  - drivers/acpi/acpica/evxfgpe.c:acpi_get_gpe_status
  - drivers/acpi/acpica/evxfgpe.c:acpi_clear_gpe
  - drivers/acpi/acpica/evxfgpe.c:acpi_set_gpe_wake_mask
  - drivers/acpi/acpica/evxfgpe.c:acpi_setup_gpe_for_wake
  - drivers/acpi/acpica/evxfgpe.c:acpi_mark_gpe_for_wake
  - drivers/acpi/acpica/evxfgpe.c:acpi_mask_gpe
  - drivers/acpi/acpica/evxfgpe.c:acpi_set_gpe
  - drivers/acpi/acpica/evxfgpe.c:acpi_disable_gpe
  - drivers/acpi/acpica/evxfgpe.c:acpi_enable_gpe
  - drivers/acpi/acpica/dbcmds.c:acpi_db_generate_gpe
```
**Symbols:**

```
ffffffff815efb9f-ffffffff815efc00: acpi_ev_get_gpe_event_info (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
struct acpi_gpe_event_info *acpi_ev_get_gpe_event_info(acpi_handle gpe_device, u32 gpe_number);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/evgpe.c (ffffffff81609a4f)
Location: drivers/acpi/acpica/evgpe.c:291
Inline: True
Direct callers:
  - drivers/acpi/acpica/evgpe.c:acpi_ev_detect_gpe
  - drivers/acpi/acpica/evxfgpe.c:acpi_finish_gpe
  - drivers/acpi/acpica/evxfgpe.c:acpi_get_gpe_status
  - drivers/acpi/acpica/evxfgpe.c:acpi_clear_gpe
  - drivers/acpi/acpica/evxfgpe.c:acpi_set_gpe_wake_mask
  - drivers/acpi/acpica/evxfgpe.c:acpi_setup_gpe_for_wake
  - drivers/acpi/acpica/evxfgpe.c:acpi_mark_gpe_for_wake
  - drivers/acpi/acpica/evxfgpe.c:acpi_mask_gpe
  - drivers/acpi/acpica/evxfgpe.c:acpi_set_gpe
  - drivers/acpi/acpica/evxfgpe.c:acpi_disable_gpe
  - drivers/acpi/acpica/evxfgpe.c:acpi_enable_gpe
  - drivers/acpi/acpica/dbcmds.c:acpi_db_generate_gpe
```
**Symbols:**

```
ffffffff81609a4f-ffffffff81609ab0: acpi_ev_get_gpe_event_info (STB_GLOBAL)
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
