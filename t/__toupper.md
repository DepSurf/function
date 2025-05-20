# Function: <code>__toupper</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/kallsyms.c (ffffffff8110ae90)
Location: include/linux/ctype.h:45
Inline: True
Inline callers:
  - kernel/kallsyms.c:s_show
```
```
In lib/vsprintf.c (ffffffff813f3c43)
Location: include/linux/ctype.h:45
Inline: True
```
```
In drivers/acpi/acpi_pnp.c (ffffffff814885b2)
Location: include/linux/ctype.h:45
Inline: True
Inline callers:
  - drivers/acpi/acpi_pnp.c:acpi_pnp_match
  - drivers/acpi/acpi_pnp.c:acpi_pnp_match
```
```
In drivers/acpi/acpica/nsrepair2.c (ffffffff8149e8ed)
Location: include/linux/ctype.h:45
Inline: True
```
```
In drivers/acpi/acpica/nsutils.c (ffffffff8149f03e)
Location: include/linux/ctype.h:45
Inline: True
Inline callers:
  - drivers/acpi/acpica/nsutils.c:acpi_ns_build_internal_name
```
```
In drivers/acpi/acpica/utnonansi.c (ffffffff814a8d1c)
Location: include/linux/ctype.h:45
Inline: True
Inline callers:
  - drivers/acpi/acpica/utnonansi.c:acpi_ut_strupr
  - drivers/acpi/acpica/utnonansi.c:acpi_ut_strtoul64
```
```
In drivers/pnp/driver.c (ffffffff814b8213)
Location: include/linux/ctype.h:45
Inline: True
```
```
In drivers/tty/n_tty.c (ffffffff814e45fb)
Location: include/linux/ctype.h:45
Inline: True
Inline callers:
  - drivers/tty/n_tty.c:do_output_char
```
```
In drivers/power/power_supply_sysfs.c (ffffffff8167fce7)
Location: include/linux/ctype.h:45
Inline: True
Inline callers:
  - drivers/power/power_supply_sysfs.c:power_supply_uevent
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/kallsyms.c (ffffffff8111264d)
Location: include/linux/ctype.h:45
Inline: True
Inline callers:
  - kernel/kallsyms.c:s_show
```
```
In drivers/acpi/acpi_pnp.c (ffffffff814d7389)
Location: include/linux/ctype.h:45
Inline: True
Inline callers:
  - drivers/acpi/acpi_pnp.c:acpi_pnp_match
  - drivers/acpi/acpi_pnp.c:acpi_pnp_match
```
```
In drivers/acpi/acpica/nsrepair2.c (ffffffff814edb7b)
Location: include/linux/ctype.h:45
Inline: True
```
```
In drivers/acpi/acpica/nsutils.c (ffffffff814ee354)
Location: include/linux/ctype.h:45
Inline: True
Inline callers:
  - drivers/acpi/acpica/nsutils.c:acpi_ns_build_internal_name
```
```
In drivers/acpi/acpica/utnonansi.c (ffffffff814f8157)
Location: include/linux/ctype.h:45
Inline: True
Inline callers:
  - drivers/acpi/acpica/utnonansi.c:acpi_ut_strtoul64
  - drivers/acpi/acpica/utnonansi.c:acpi_ut_strupr
```
```
In drivers/pnp/driver.c (ffffffff81507c74)
Location: include/linux/ctype.h:45
Inline: True
```
```
In drivers/tty/n_tty.c (ffffffff815358fa)
Location: include/linux/ctype.h:45
Inline: True
Inline callers:
  - drivers/tty/n_tty.c:do_output_char
```
```
In drivers/power/power_supply_sysfs.c (ffffffff816e0ba0)
Location: include/linux/ctype.h:45
Inline: True
Inline callers:
  - drivers/power/power_supply_sysfs.c:power_supply_uevent
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/kallsyms.c (ffffffff81119d6a)
Location: include/linux/ctype.h:48
Inline: True
Inline callers:
  - kernel/kallsyms.c:s_show
```
```
In drivers/acpi/acpi_pnp.c (ffffffff814f9a71)
Location: include/linux/ctype.h:48
Inline: True
Inline callers:
  - drivers/acpi/acpi_pnp.c:acpi_pnp_match
  - drivers/acpi/acpi_pnp.c:acpi_pnp_match
```
```
In drivers/acpi/acpica/nsrepair2.c (ffffffff815105c4)
Location: include/linux/ctype.h:48
Inline: True
```
```
In drivers/acpi/acpica/nsutils.c (ffffffff81510dbc)
Location: include/linux/ctype.h:48
Inline: True
Inline callers:
  - drivers/acpi/acpica/nsutils.c:acpi_ns_build_internal_name
```
```
In drivers/acpi/acpica/utnonansi.c (ffffffff8151ac03)
Location: include/linux/ctype.h:48
Inline: True
Inline callers:
  - drivers/acpi/acpica/utnonansi.c:acpi_ut_strupr
```
```
In drivers/pnp/driver.c (ffffffff8152be94)
Location: include/linux/ctype.h:48
Inline: True
```
```
In drivers/tty/n_tty.c (ffffffff8156201a)
Location: include/linux/ctype.h:48
Inline: True
Inline callers:
  - drivers/tty/n_tty.c:do_output_char
```
```
In drivers/power/supply/power_supply_sysfs.c (ffffffff81711010)
Location: include/linux/ctype.h:48
Inline: True
Inline callers:
  - drivers/power/supply/power_supply_sysfs.c:power_supply_uevent
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/kallsyms.c (ffffffff8111b856)
Location: include/linux/ctype.h:48
Inline: True
Inline callers:
  - kernel/kallsyms.c:s_show
```
```
In drivers/acpi/acpi_pnp.c (ffffffff81508ba5)
Location: include/linux/ctype.h:48
Inline: True
Inline callers:
  - drivers/acpi/acpi_pnp.c:acpi_pnp_match
  - drivers/acpi/acpi_pnp.c:acpi_pnp_match
```
```
In drivers/acpi/acpica/nsrepair2.c (ffffffff81520c8c)
Location: include/linux/ctype.h:48
Inline: True
```
```
In drivers/acpi/acpica/nsutils.c (ffffffff81521472)
Location: include/linux/ctype.h:48
Inline: True
Inline callers:
  - drivers/acpi/acpica/nsutils.c:acpi_ns_build_internal_name
```
```
In drivers/acpi/acpica/utnonansi.c (ffffffff8152b426)
Location: include/linux/ctype.h:48
Inline: True
Inline callers:
  - drivers/acpi/acpica/utnonansi.c:acpi_ut_strupr
```
```
In drivers/pnp/driver.c (ffffffff8153ef9d)
Location: include/linux/ctype.h:48
Inline: True
```
```
In drivers/tty/n_tty.c (ffffffff815759b1)
Location: include/linux/ctype.h:48
Inline: True
Inline callers:
  - drivers/tty/n_tty.c:do_output_char
```
```
In drivers/power/supply/power_supply_sysfs.c (ffffffff8172940e)
Location: include/linux/ctype.h:48
Inline: True
Inline callers:
  - drivers/power/supply/power_supply_sysfs.c:power_supply_uevent
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/kallsyms.c (ffffffff81126de4)
Location: include/linux/ctype.h:49
Inline: True
Inline callers:
  - kernel/kallsyms.c:s_show
```
```
In drivers/acpi/acpi_pnp.c (ffffffff8154af85)
Location: include/linux/ctype.h:49
Inline: True
Inline callers:
  - drivers/acpi/acpi_pnp.c:acpi_pnp_match
  - drivers/acpi/acpi_pnp.c:acpi_pnp_match
```
```
In drivers/acpi/acpica/nsrepair2.c (ffffffff8157435a)
Location: include/linux/ctype.h:49
Inline: True
Inline callers:
  - drivers/acpi/acpica/nsrepair2.c:acpi_ns_repair_HID
```
```
In drivers/acpi/acpica/nsutils.c (ffffffff815753bd)
Location: include/linux/ctype.h:49
Inline: True
Inline callers:
  - drivers/acpi/acpica/nsutils.c:acpi_ns_build_internal_name
```
```
In drivers/acpi/acpica/utnonansi.c (ffffffff8158520e)
Location: include/linux/ctype.h:49
Inline: True
Inline callers:
  - drivers/acpi/acpica/utnonansi.c:acpi_ut_strupr
```
```
In drivers/acpi/acpica/dbconvert.c (ffffffff81588d3a)
Location: include/linux/ctype.h:49
Inline: True
Inline callers:
  - drivers/acpi/acpica/dbconvert.c:acpi_db_hex_char_to_value
```
```
In drivers/pnp/driver.c (ffffffff815a204d)
Location: include/linux/ctype.h:49
Inline: True
```
```
In drivers/tty/n_tty.c (ffffffff815da2d1)
Location: include/linux/ctype.h:49
Inline: True
Inline callers:
  - drivers/tty/n_tty.c:do_output_char
```
```
In drivers/power/supply/power_supply_sysfs.c (ffffffff8179ab9e)
Location: include/linux/ctype.h:49
Inline: True
Inline callers:
  - drivers/power/supply/power_supply_sysfs.c:power_supply_uevent
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/kallsyms.c (ffffffff81134c9c)
Location: include/linux/ctype.h:49
Inline: True
Inline callers:
  - kernel/kallsyms.c:s_show
```
```
In drivers/acpi/acpi_pnp.c (ffffffff815815c5)
Location: include/linux/ctype.h:49
Inline: True
Inline callers:
  - drivers/acpi/acpi_pnp.c:acpi_pnp_match
  - drivers/acpi/acpi_pnp.c:acpi_pnp_match
```
```
In drivers/acpi/acpica/nsrepair2.c (ffffffff815ab2be)
Location: include/linux/ctype.h:49
Inline: True
Inline callers:
  - drivers/acpi/acpica/nsrepair2.c:acpi_ns_repair_HID
```
```
In drivers/acpi/acpica/nsutils.c (ffffffff815ac332)
Location: include/linux/ctype.h:49
Inline: True
Inline callers:
  - drivers/acpi/acpica/nsutils.c:acpi_ns_build_internal_name
```
```
In drivers/acpi/acpica/utnonansi.c (ffffffff815bc3a9)
Location: include/linux/ctype.h:49
Inline: True
Inline callers:
  - drivers/acpi/acpica/utnonansi.c:acpi_ut_strupr
```
```
In drivers/acpi/acpica/dbconvert.c (ffffffff815bfeb0)
Location: include/linux/ctype.h:49
Inline: True
Inline callers:
  - drivers/acpi/acpica/dbconvert.c:acpi_db_hex_char_to_value
```
```
In drivers/pnp/driver.c (ffffffff815d9c96)
Location: include/linux/ctype.h:49
Inline: True
```
```
In drivers/tty/n_tty.c (ffffffff81613606)
Location: include/linux/ctype.h:49
Inline: True
Inline callers:
  - drivers/tty/n_tty.c:do_output_char
```
```
In drivers/power/supply/power_supply_sysfs.c (ffffffff817e2084)
Location: include/linux/ctype.h:49
Inline: True
Inline callers:
  - drivers/power/supply/power_supply_sysfs.c:power_supply_uevent
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/kallsyms.c (ffffffff8114043c)
Location: include/linux/ctype.h:49
Inline: True
Inline callers:
  - kernel/kallsyms.c:s_show
```
```
In drivers/acpi/acpi_pnp.c (ffffffff81599685)
Location: include/linux/ctype.h:49
Inline: True
Inline callers:
  - drivers/acpi/acpi_pnp.c:acpi_pnp_match
  - drivers/acpi/acpi_pnp.c:acpi_pnp_match
```
```
In drivers/acpi/acpica/nsrepair2.c (ffffffff815c42c3)
Location: include/linux/ctype.h:49
Inline: True
Inline callers:
  - drivers/acpi/acpica/nsrepair2.c:acpi_ns_repair_HID
```
```
In drivers/acpi/acpica/nsutils.c (ffffffff815c5329)
Location: include/linux/ctype.h:49
Inline: True
Inline callers:
  - drivers/acpi/acpica/nsutils.c:acpi_ns_build_internal_name
```
```
In drivers/acpi/acpica/utnonansi.c (ffffffff815d57ef)
Location: include/linux/ctype.h:49
Inline: True
Inline callers:
  - drivers/acpi/acpica/utnonansi.c:acpi_ut_strupr
```
```
In drivers/acpi/acpica/dbconvert.c (ffffffff815d9321)
Location: include/linux/ctype.h:49
Inline: True
Inline callers:
  - drivers/acpi/acpica/dbconvert.c:acpi_db_hex_char_to_value
```
```
In drivers/pnp/driver.c (ffffffff815f35b6)
Location: include/linux/ctype.h:49
Inline: True
```
```
In drivers/tty/n_tty.c (ffffffff816306b6)
Location: include/linux/ctype.h:49
Inline: True
Inline callers:
  - drivers/tty/n_tty.c:do_output_char
```
```
In drivers/power/supply/power_supply_sysfs.c (ffffffff8180d8d4)
Location: include/linux/ctype.h:49
Inline: True
Inline callers:
  - drivers/power/supply/power_supply_sysfs.c:power_supply_uevent
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/kallsyms.c (ffffffff8114b82c)
Location: include/linux/ctype.h:49
Inline: True
Inline callers:
  - kernel/kallsyms.c:s_show
```
```
In drivers/acpi/acpi_pnp.c (ffffffff815caaec)
Location: include/linux/ctype.h:49
Inline: True
Inline callers:
  - drivers/acpi/acpi_pnp.c:acpi_pnp_match
  - drivers/acpi/acpi_pnp.c:acpi_pnp_match
```
```
In drivers/acpi/acpica/nsrepair2.c (ffffffff815f5ba9)
Location: include/linux/ctype.h:49
Inline: True
Inline callers:
  - drivers/acpi/acpica/nsrepair2.c:acpi_ns_repair_HID
```
```
In drivers/acpi/acpica/nsutils.c (ffffffff815f6c1d)
Location: include/linux/ctype.h:49
Inline: True
Inline callers:
  - drivers/acpi/acpica/nsutils.c:acpi_ns_build_internal_name
```
```
In drivers/acpi/acpica/utnonansi.c (ffffffff8160718b)
Location: include/linux/ctype.h:49
Inline: True
Inline callers:
  - drivers/acpi/acpica/utnonansi.c:acpi_ut_strupr
```
```
In drivers/acpi/acpica/dbconvert.c (ffffffff8160ae35)
Location: include/linux/ctype.h:49
Inline: True
Inline callers:
  - drivers/acpi/acpica/dbconvert.c:acpi_db_hex_char_to_value
```
```
In drivers/pnp/driver.c (ffffffff816254a9)
Location: include/linux/ctype.h:49
Inline: True
```
```
In drivers/tty/n_tty.c (ffffffff8166460c)
Location: include/linux/ctype.h:49
Inline: True
Inline callers:
  - drivers/tty/n_tty.c:do_output_char
```
```
In drivers/power/supply/power_supply_sysfs.c (ffffffff8184f568)
Location: include/linux/ctype.h:49
Inline: True
Inline callers:
  - drivers/power/supply/power_supply_sysfs.c:power_supply_uevent
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/kallsyms.c (ffffffff811574fc)
Location: include/linux/ctype.h:49
Inline: True
Inline callers:
  - kernel/kallsyms.c:s_show
```
```
In drivers/acpi/acpi_pnp.c (ffffffff815ebd6c)
Location: include/linux/ctype.h:49
Inline: True
Inline callers:
  - drivers/acpi/acpi_pnp.c:acpi_pnp_match
  - drivers/acpi/acpi_pnp.c:acpi_pnp_match
```
```
In drivers/acpi/acpica/nsrepair2.c (ffffffff8161704d)
Location: include/linux/ctype.h:49
Inline: True
Inline callers:
  - drivers/acpi/acpica/nsrepair2.c:acpi_ns_repair_HID
```
```
In drivers/acpi/acpica/nsutils.c (ffffffff816180c3)
Location: include/linux/ctype.h:49
Inline: True
Inline callers:
  - drivers/acpi/acpica/nsutils.c:acpi_ns_build_internal_name
```
```
In drivers/acpi/acpica/utnonansi.c (ffffffff81628626)
Location: include/linux/ctype.h:49
Inline: True
Inline callers:
  - drivers/acpi/acpica/utnonansi.c:acpi_ut_strupr
```
```
In drivers/acpi/acpica/dbconvert.c (ffffffff8162c2d6)
Location: include/linux/ctype.h:49
Inline: True
Inline callers:
  - drivers/acpi/acpica/dbconvert.c:acpi_db_hex_char_to_value
```
```
In drivers/pnp/driver.c (ffffffff81646f99)
Location: include/linux/ctype.h:49
Inline: True
```
```
In drivers/tty/n_tty.c (ffffffff81686c5c)
Location: include/linux/ctype.h:49
Inline: True
Inline callers:
  - drivers/tty/n_tty.c:do_output_char
```
```
In drivers/power/supply/power_supply_sysfs.c (ffffffff81880f78)
Location: include/linux/ctype.h:49
Inline: True
Inline callers:
  - drivers/power/supply/power_supply_sysfs.c:power_supply_uevent
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/kallsyms.c (ffffffff8116808c)
Location: include/linux/ctype.h:49
Inline: True
Inline callers:
  - kernel/kallsyms.c:s_show
```
```
In drivers/acpi/acpi_pnp.c (ffffffff816977ca)
Location: include/linux/ctype.h:49
Inline: True
Inline callers:
  - drivers/acpi/acpi_pnp.c:matching_id
  - drivers/acpi/acpi_pnp.c:matching_id
```
```
In drivers/acpi/acpica/nsrepair2.c (ffffffff816c3585)
Location: include/linux/ctype.h:49
Inline: True
Inline callers:
  - drivers/acpi/acpica/nsrepair2.c:acpi_ns_repair_HID
```
```
In drivers/acpi/acpica/nsutils.c (ffffffff816c45f6)
Location: include/linux/ctype.h:49
Inline: True
Inline callers:
  - drivers/acpi/acpica/nsutils.c:acpi_ns_build_internal_name
```
```
In drivers/acpi/acpica/utnonansi.c (ffffffff816d4dcc)
Location: include/linux/ctype.h:49
Inline: True
Inline callers:
  - drivers/acpi/acpica/utnonansi.c:acpi_ut_strupr
```
```
In drivers/acpi/acpica/dbconvert.c (ffffffff816d8aad)
Location: include/linux/ctype.h:49
Inline: True
Inline callers:
  - drivers/acpi/acpica/dbconvert.c:acpi_db_hex_char_to_value
```
```
In drivers/pnp/driver.c (ffffffff816f5c99)
Location: include/linux/ctype.h:49
Inline: True
Inline callers:
  - drivers/pnp/driver.c:compare_pnp_id
  - drivers/pnp/driver.c:compare_pnp_id
```
```
In drivers/tty/n_tty.c (ffffffff81738b2e)
Location: include/linux/ctype.h:49
Inline: True
Inline callers:
  - drivers/tty/n_tty.c:do_output_char
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/kallsyms.c (ffffffff8116467c)
Location: include/linux/ctype.h:56
Inline: True
Inline callers:
  - kernel/kallsyms.c:s_show
```
```
In drivers/acpi/acpi_pnp.c (ffffffff816b4908)
Location: include/linux/ctype.h:56
Inline: True
Inline callers:
  - drivers/acpi/acpi_pnp.c:matching_id
  - drivers/acpi/acpi_pnp.c:matching_id
```
```
In drivers/acpi/acpica/nsrepair2.c (ffffffff816e1487)
Location: include/linux/ctype.h:56
Inline: True
Inline callers:
  - drivers/acpi/acpica/nsrepair2.c:acpi_ns_repair_HID
```
```
In drivers/acpi/acpica/nsutils.c (ffffffff816e263a)
Location: include/linux/ctype.h:56
Inline: True
Inline callers:
  - drivers/acpi/acpica/nsutils.c:acpi_ns_build_internal_name
```
```
In drivers/acpi/acpica/utnonansi.c (ffffffff816f2d99)
Location: include/linux/ctype.h:56
Inline: True
Inline callers:
  - drivers/acpi/acpica/utnonansi.c:acpi_ut_strupr
```
```
In drivers/acpi/acpica/dbconvert.c (ffffffff816f6a3c)
Location: include/linux/ctype.h:56
Inline: True
Inline callers:
  - drivers/acpi/acpica/dbconvert.c:acpi_db_hex_char_to_value
```
```
In drivers/pnp/driver.c (ffffffff81712cd9)
Location: include/linux/ctype.h:56
Inline: True
Inline callers:
  - drivers/pnp/driver.c:compare_pnp_id
  - drivers/pnp/driver.c:compare_pnp_id
```
```
In drivers/tty/n_tty.c (ffffffff81754b2e)
Location: include/linux/ctype.h:56
Inline: True
Inline callers:
  - drivers/tty/n_tty.c:do_output_char
```
```
In drivers/tty/sysrq.c (ffffffff8175fb84)
Location: include/linux/ctype.h:56
Inline: True
Inline callers:
  - drivers/tty/sysrq.c:sysrq_handle_keypress
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/kallsyms.c (ffffffff8116545c)
Location: include/linux/ctype.h:56
Inline: True
Inline callers:
  - kernel/kallsyms.c:s_show
```
```
In drivers/acpi/acpi_pnp.c (ffffffff81696b38)
Location: include/linux/ctype.h:56
Inline: True
Inline callers:
  - drivers/acpi/acpi_pnp.c:matching_id
  - drivers/acpi/acpi_pnp.c:matching_id
```
```
In drivers/acpi/acpica/nsrepair2.c (ffffffff816c3373)
Location: include/linux/ctype.h:56
Inline: True
Inline callers:
  - drivers/acpi/acpica/nsrepair2.c:acpi_ns_repair_HID
```
```
In drivers/acpi/acpica/nsutils.c (ffffffff816c4502)
Location: include/linux/ctype.h:56
Inline: True
Inline callers:
  - drivers/acpi/acpica/nsutils.c:acpi_ns_build_internal_name
```
```
In drivers/acpi/acpica/utnonansi.c (ffffffff816d4c49)
Location: include/linux/ctype.h:56
Inline: True
Inline callers:
  - drivers/acpi/acpica/utnonansi.c:acpi_ut_strupr
```
```
In drivers/acpi/acpica/dbconvert.c (ffffffff816d88ad)
Location: include/linux/ctype.h:56
Inline: True
Inline callers:
  - drivers/acpi/acpica/dbconvert.c:acpi_db_hex_char_to_value
```
```
In drivers/pnp/driver.c (ffffffff816f4099)
Location: include/linux/ctype.h:56
Inline: True
Inline callers:
  - drivers/pnp/driver.c:compare_pnp_id
  - drivers/pnp/driver.c:compare_pnp_id
```
```
In drivers/tty/n_tty.c (ffffffff81738a7d)
Location: include/linux/ctype.h:56
Inline: True
Inline callers:
  - drivers/tty/n_tty.c:do_output_char
```
```
In drivers/tty/sysrq.c (ffffffff817439e6)
Location: include/linux/ctype.h:56
Inline: True
Inline callers:
  - drivers/tty/sysrq.c:sysrq_handle_keypress
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/kallsyms.c (ffffffff8118ab7c)
Location: include/linux/ctype.h:56
Inline: True
Inline callers:
  - kernel/kallsyms.c:s_show
```
```
In drivers/acpi/acpi_pnp.c (ffffffff8170c8d8)
Location: include/linux/ctype.h:56
Inline: True
Inline callers:
  - drivers/acpi/acpi_pnp.c:matching_id
  - drivers/acpi/acpi_pnp.c:matching_id
```
```
In drivers/acpi/acpica/nsrepair2.c (ffffffff8173a6a7)
Location: include/linux/ctype.h:56
Inline: True
Inline callers:
  - drivers/acpi/acpica/nsrepair2.c:acpi_ns_repair_HID
```
```
In drivers/acpi/acpica/nsutils.c (ffffffff8173b84f)
Location: include/linux/ctype.h:56
Inline: True
Inline callers:
  - drivers/acpi/acpica/nsutils.c:acpi_ns_build_internal_name
```
```
In drivers/acpi/acpica/utnonansi.c (ffffffff8174c670)
Location: include/linux/ctype.h:56
Inline: True
Inline callers:
  - drivers/acpi/acpica/utnonansi.c:acpi_ut_strupr
```
```
In drivers/acpi/acpica/dbconvert.c (ffffffff81750461)
Location: include/linux/ctype.h:56
Inline: True
Inline callers:
  - drivers/acpi/acpica/dbconvert.c:acpi_db_hex_char_to_value
```
```
In drivers/pnp/driver.c (ffffffff8176e4d9)
Location: include/linux/ctype.h:56
Inline: True
Inline callers:
  - drivers/pnp/driver.c:compare_pnp_id
  - drivers/pnp/driver.c:compare_pnp_id
```
```
In drivers/tty/n_tty.c (ffffffff817b950d)
Location: include/linux/ctype.h:56
Inline: True
Inline callers:
  - drivers/tty/n_tty.c:do_output_char
```
```
In drivers/tty/sysrq.c (ffffffff817c4655)
Location: include/linux/ctype.h:56
Inline: True
Inline callers:
  - drivers/tty/sysrq.c:sysrq_handle_keypress
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/kallsyms.c (ffffffff811b9c90)
Location: include/linux/ctype.h:56
Inline: True
Inline callers:
  - kernel/kallsyms.c:s_show
```
```
In drivers/acpi/acpi_pnp.c (ffffffff8183afd5)
Location: include/linux/ctype.h:56
Inline: True
Inline callers:
  - drivers/acpi/acpi_pnp.c:matching_id
  - drivers/acpi/acpi_pnp.c:matching_id
```
```
In drivers/acpi/acpica/nsrepair2.c (ffffffff8186bbed)
Location: include/linux/ctype.h:56
Inline: True
Inline callers:
  - drivers/acpi/acpica/nsrepair2.c:acpi_ns_repair_HID
```
```
In drivers/acpi/acpica/nsutils.c (ffffffff8186cec6)
Location: include/linux/ctype.h:56
Inline: True
Inline callers:
  - drivers/acpi/acpica/nsutils.c:acpi_ns_build_internal_name
```
```
In drivers/acpi/acpica/utnonansi.c (ffffffff8187ed26)
Location: include/linux/ctype.h:56
Inline: True
Inline callers:
  - drivers/acpi/acpica/utnonansi.c:acpi_ut_strupr
```
```
In drivers/acpi/acpica/dbconvert.c (ffffffff81883095)
Location: include/linux/ctype.h:56
Inline: True
Inline callers:
  - drivers/acpi/acpica/dbconvert.c:acpi_db_hex_char_to_value
```
```
In drivers/pnp/driver.c (ffffffff818a36ac)
Location: include/linux/ctype.h:56
Inline: True
Inline callers:
  - drivers/pnp/driver.c:compare_pnp_id
  - drivers/pnp/driver.c:compare_pnp_id
```
```
In drivers/tty/n_tty.c (ffffffff818f5586)
Location: include/linux/ctype.h:56
Inline: True
Inline callers:
  - drivers/tty/n_tty.c:do_output_char
```
```
In drivers/tty/sysrq.c (ffffffff81901277)
Location: include/linux/ctype.h:56
Inline: True
Inline callers:
  - drivers/tty/sysrq.c:sysrq_handle_keypress
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/kallsyms.c (ffffffff811fb3b5)
Location: include/linux/ctype.h:56
Inline: True
Inline callers:
  - kernel/kallsyms.c:s_show
```
```
In drivers/acpi/acpi_pnp.c (ffffffff81970714)
Location: include/linux/ctype.h:56
Inline: True
Inline callers:
  - drivers/acpi/acpi_pnp.c:matching_id
  - drivers/acpi/acpi_pnp.c:matching_id
```
```
In drivers/acpi/acpica/nsrepair2.c (ffffffff819ab180)
Location: include/linux/ctype.h:56
Inline: True
Inline callers:
  - drivers/acpi/acpica/nsrepair2.c:acpi_ns_repair_HID
```
```
In drivers/acpi/acpica/nsutils.c (ffffffff819ac982)
Location: include/linux/ctype.h:56
Inline: True
Inline callers:
  - drivers/acpi/acpica/nsutils.c:acpi_ns_build_internal_name
```
```
In drivers/acpi/acpica/utnonansi.c (ffffffff819c2b09)
Location: include/linux/ctype.h:56
Inline: True
Inline callers:
  - drivers/acpi/acpica/utnonansi.c:acpi_ut_strupr
```
```
In drivers/acpi/acpica/dbconvert.c (ffffffff819c80ec)
Location: include/linux/ctype.h:56
Inline: True
Inline callers:
  - drivers/acpi/acpica/dbconvert.c:acpi_db_convert_to_buffer
  - drivers/acpi/acpica/dbconvert.c:acpi_db_convert_to_buffer
```
```
In drivers/pnp/driver.c (ffffffff819ed0bc)
Location: include/linux/ctype.h:56
Inline: True
Inline callers:
  - drivers/pnp/driver.c:compare_pnp_id
  - drivers/pnp/driver.c:compare_pnp_id
```
```
In drivers/tty/n_tty.c (ffffffff81a4de86)
Location: include/linux/ctype.h:56
Inline: True
Inline callers:
  - drivers/tty/n_tty.c:do_output_char
```
```
In drivers/tty/sysrq.c (ffffffff81a5b177)
Location: include/linux/ctype.h:56
Inline: True
Inline callers:
  - drivers/tty/sysrq.c:sysrq_handle_keypress
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/kallsyms.c (ffffffff81210911)
Location: include/linux/ctype.h:56
Inline: True
Inline callers:
  - kernel/kallsyms.c:s_show
```
```
In drivers/acpi/acpi_pnp.c (ffffffff819b6dc4)
Location: include/linux/ctype.h:56
Inline: True
Inline callers:
  - drivers/acpi/acpi_pnp.c:matching_id
  - drivers/acpi/acpi_pnp.c:matching_id
```
```
In drivers/acpi/acpica/nsrepair2.c (ffffffff819f204d)
Location: include/linux/ctype.h:56
Inline: True
Inline callers:
  - drivers/acpi/acpica/nsrepair2.c:acpi_ns_repair_HID
```
```
In drivers/acpi/acpica/nsutils.c (ffffffff819f3844)
Location: include/linux/ctype.h:56
Inline: True
Inline callers:
  - drivers/acpi/acpica/nsutils.c:acpi_ns_build_internal_name
```
```
In drivers/acpi/acpica/utnonansi.c (ffffffff81a09e59)
Location: include/linux/ctype.h:56
Inline: True
Inline callers:
  - drivers/acpi/acpica/utnonansi.c:acpi_ut_strupr
```
```
In drivers/acpi/acpica/dbconvert.c (ffffffff81a0f50c)
Location: include/linux/ctype.h:56
Inline: True
Inline callers:
  - drivers/acpi/acpica/dbconvert.c:acpi_db_convert_to_buffer
  - drivers/acpi/acpica/dbconvert.c:acpi_db_convert_to_buffer
```
```
In drivers/pnp/driver.c (ffffffff81a3583c)
Location: include/linux/ctype.h:56
Inline: True
Inline callers:
  - drivers/pnp/driver.c:compare_pnp_id
  - drivers/pnp/driver.c:compare_pnp_id
```
```
In drivers/tty/n_tty.c (ffffffff81a98152)
Location: include/linux/ctype.h:56
Inline: True
Inline callers:
  - drivers/tty/n_tty.c:do_output_char
```
```
In drivers/tty/sysrq.c (ffffffff81aa57c3)
Location: include/linux/ctype.h:56
Inline: True
Inline callers:
  - drivers/tty/sysrq.c:sysrq_handle_keypress
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/kallsyms.c (ffffffff81227f91)
Location: include/linux/ctype.h:56
Inline: True
Inline callers:
  - kernel/kallsyms.c:s_show
```
```
In drivers/acpi/acpi_pnp.c (ffffffff81a01374)
Location: include/linux/ctype.h:56
Inline: True
Inline callers:
  - drivers/acpi/acpi_pnp.c:matching_id
  - drivers/acpi/acpi_pnp.c:matching_id
```
```
In drivers/acpi/acpica/nsrepair2.c (ffffffff81a3ce6d)
Location: include/linux/ctype.h:56
Inline: True
Inline callers:
  - drivers/acpi/acpica/nsrepair2.c:acpi_ns_repair_HID
```
```
In drivers/acpi/acpica/nsutils.c (ffffffff81a3e664)
Location: include/linux/ctype.h:56
Inline: True
Inline callers:
  - drivers/acpi/acpica/nsutils.c:acpi_ns_build_internal_name
```
```
In drivers/acpi/acpica/utnonansi.c (ffffffff81a54df9)
Location: include/linux/ctype.h:56
Inline: True
Inline callers:
  - drivers/acpi/acpica/utnonansi.c:acpi_ut_strupr
```
```
In drivers/acpi/acpica/dbconvert.c (ffffffff81a5a64c)
Location: include/linux/ctype.h:56
Inline: True
Inline callers:
  - drivers/acpi/acpica/dbconvert.c:acpi_db_convert_to_buffer
  - drivers/acpi/acpica/dbconvert.c:acpi_db_convert_to_buffer
```
```
In drivers/pnp/driver.c (ffffffff81a80d6c)
Location: include/linux/ctype.h:56
Inline: True
Inline callers:
  - drivers/pnp/driver.c:compare_pnp_id
  - drivers/pnp/driver.c:compare_pnp_id
```
```
In drivers/tty/n_tty.c (ffffffff81aead54)
Location: include/linux/ctype.h:56
Inline: True
Inline callers:
  - drivers/tty/n_tty.c:do_output_char
```
```
In drivers/tty/sysrq.c (ffffffff81af8213)
Location: include/linux/ctype.h:56
Inline: True
Inline callers:
  - drivers/tty/sysrq.c:sysrq_handle_keypress
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
In kernel/kallsyms.c (ffff8000101c6858)
Location: include/linux/ctype.h:49
Inline: True
Inline callers:
  - kernel/kallsyms.c:s_show
```
```
In drivers/acpi/acpi_pnp.c (ffff800010777244)
Location: include/linux/ctype.h:49
Inline: True
Inline callers:
  - drivers/acpi/acpi_pnp.c:acpi_pnp_match
  - drivers/acpi/acpi_pnp.c:acpi_pnp_match
```
```
In drivers/acpi/acpica/nsrepair2.c (ffff80001078f810)
Location: include/linux/ctype.h:49
Inline: True
```
```
In drivers/acpi/acpica/nsutils.c (ffff80001079016c)
Location: include/linux/ctype.h:49
Inline: True
Inline callers:
  - drivers/acpi/acpica/nsutils.c:acpi_ns_build_internal_name
```
```
In drivers/acpi/acpica/utnonansi.c (ffff80001079d254)
Location: include/linux/ctype.h:49
Inline: True
Inline callers:
  - drivers/acpi/acpica/utnonansi.c:acpi_ut_strupr
```
```
In drivers/pnp/driver.c (ffff8000107b41b0)
Location: include/linux/ctype.h:49
Inline: True
```
```
In drivers/tty/n_tty.c (ffff800010854508)
Location: include/linux/ctype.h:49
Inline: True
Inline callers:
  - drivers/tty/n_tty.c:do_output_char
```
```
In drivers/power/supply/power_supply_sysfs.c (ffff800010acd390)
Location: include/linux/ctype.h:49
Inline: True
Inline callers:
  - drivers/power/supply/power_supply_sysfs.c:power_supply_uevent
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/kallsyms.c (c040d7b0)
Location: include/linux/ctype.h:49
Inline: True
Inline callers:
  - kernel/kallsyms.c:s_show
```
```
In drivers/tty/n_tty.c (c095ebb0)
Location: include/linux/ctype.h:49
Inline: True
Inline callers:
  - drivers/tty/n_tty.c:do_output_char
```
```
In drivers/power/supply/power_supply_sysfs.c (c0badcfc)
Location: include/linux/ctype.h:49
Inline: True
Inline callers:
  - drivers/power/supply/power_supply_sysfs.c:power_supply_uevent
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/kallsyms.c (c00000000022e620)
Location: include/linux/ctype.h:49
Inline: True
Inline callers:
  - kernel/kallsyms.c:s_show
```
```
In drivers/tty/n_tty.c (c0000000008f3a28)
Location: include/linux/ctype.h:49
Inline: True
Inline callers:
  - drivers/tty/n_tty.c:do_output_char
```
```
In drivers/power/supply/power_supply_sysfs.c (c000000000bafd1c)
Location: include/linux/ctype.h:49
Inline: True
Inline callers:
  - drivers/power/supply/power_supply_sysfs.c:power_supply_uevent
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/kallsyms.c (ffffffe000146d6e)
Location: include/linux/ctype.h:49
Inline: True
Inline callers:
  - kernel/kallsyms.c:s_show
```
```
In drivers/tty/n_tty.c (ffffffe000530af6)
Location: include/linux/ctype.h:49
Inline: True
Inline callers:
  - drivers/tty/n_tty.c:do_output_char
```
```
In drivers/power/supply/power_supply_sysfs.c (ffffffe0006ca40e)
Location: include/linux/ctype.h:49
Inline: True
Inline callers:
  - drivers/power/supply/power_supply_sysfs.c:power_supply_uevent
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/kallsyms.c (ffffffff8114fb1c)
Location: include/linux/ctype.h:49
Inline: True
Inline callers:
  - kernel/kallsyms.c:s_show
```
```
In drivers/acpi/acpi_pnp.c (ffffffff815db14c)
Location: include/linux/ctype.h:49
Inline: True
Inline callers:
  - drivers/acpi/acpi_pnp.c:acpi_pnp_match
  - drivers/acpi/acpi_pnp.c:acpi_pnp_match
```
```
In drivers/acpi/acpica/nsrepair2.c (ffffffff815f5287)
Location: include/linux/ctype.h:49
Inline: True
```
```
In drivers/acpi/acpica/nsutils.c (ffffffff815f5a87)
Location: include/linux/ctype.h:49
Inline: True
Inline callers:
  - drivers/acpi/acpica/nsutils.c:acpi_ns_build_internal_name
```
```
In drivers/acpi/acpica/utnonansi.c (ffffffff816001dd)
Location: include/linux/ctype.h:49
Inline: True
Inline callers:
  - drivers/acpi/acpica/utnonansi.c:acpi_ut_strupr
```
```
In drivers/pnp/driver.c (ffffffff8160cff9)
Location: include/linux/ctype.h:49
Inline: True
```
```
In drivers/tty/n_tty.c (ffffffff8164c6dc)
Location: include/linux/ctype.h:49
Inline: True
Inline callers:
  - drivers/tty/n_tty.c:do_output_char
```
```
In drivers/power/supply/power_supply_sysfs.c (ffffffff818294e8)
Location: include/linux/ctype.h:49
Inline: True
Inline callers:
  - drivers/power/supply/power_supply_sysfs.c:power_supply_uevent
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/kallsyms.c (ffffffff81142dcc)
Location: include/linux/ctype.h:49
Inline: True
Inline callers:
  - kernel/kallsyms.c:s_show
```
```
In drivers/acpi/acpi_pnp.c (ffffffff815c678c)
Location: include/linux/ctype.h:49
Inline: True
Inline callers:
  - drivers/acpi/acpi_pnp.c:acpi_pnp_match
  - drivers/acpi/acpi_pnp.c:acpi_pnp_match
```
```
In drivers/acpi/acpica/nsrepair2.c (ffffffff815e0806)
Location: include/linux/ctype.h:49
Inline: True
```
```
In drivers/acpi/acpica/nsutils.c (ffffffff815e1012)
Location: include/linux/ctype.h:49
Inline: True
Inline callers:
  - drivers/acpi/acpica/nsutils.c:acpi_ns_build_internal_name
```
```
In drivers/acpi/acpica/utnonansi.c (ffffffff815eb6c5)
Location: include/linux/ctype.h:49
Inline: True
Inline callers:
  - drivers/acpi/acpica/utnonansi.c:acpi_ut_strupr
```
```
In drivers/pnp/driver.c (ffffffff81601549)
Location: include/linux/ctype.h:49
Inline: True
```
```
In drivers/tty/n_tty.c (ffffffff8162cb2c)
Location: include/linux/ctype.h:49
Inline: True
Inline callers:
  - drivers/tty/n_tty.c:do_output_char
```
```
In drivers/power/supply/power_supply_sysfs.c (ffffffff817f0b78)
Location: include/linux/ctype.h:49
Inline: True
Inline callers:
  - drivers/power/supply/power_supply_sysfs.c:power_supply_uevent
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/kallsyms.c (ffffffff8114d9cc)
Location: include/linux/ctype.h:49
Inline: True
Inline callers:
  - kernel/kallsyms.c:s_show
```
```
In drivers/acpi/acpi_pnp.c (ffffffff815e004c)
Location: include/linux/ctype.h:49
Inline: True
Inline callers:
  - drivers/acpi/acpi_pnp.c:acpi_pnp_match
  - drivers/acpi/acpi_pnp.c:acpi_pnp_match
```
```
In drivers/acpi/acpica/nsrepair2.c (ffffffff8160b32d)
Location: include/linux/ctype.h:49
Inline: True
Inline callers:
  - drivers/acpi/acpica/nsrepair2.c:acpi_ns_repair_HID
```
```
In drivers/acpi/acpica/nsutils.c (ffffffff8160c3a3)
Location: include/linux/ctype.h:49
Inline: True
Inline callers:
  - drivers/acpi/acpica/nsutils.c:acpi_ns_build_internal_name
```
```
In drivers/acpi/acpica/utnonansi.c (ffffffff8161c906)
Location: include/linux/ctype.h:49
Inline: True
Inline callers:
  - drivers/acpi/acpica/utnonansi.c:acpi_ut_strupr
```
```
In drivers/acpi/acpica/dbconvert.c (ffffffff816205b6)
Location: include/linux/ctype.h:49
Inline: True
Inline callers:
  - drivers/acpi/acpica/dbconvert.c:acpi_db_hex_char_to_value
```
```
In drivers/pnp/driver.c (ffffffff8163add9)
Location: include/linux/ctype.h:49
Inline: True
```
```
In drivers/tty/n_tty.c (ffffffff8167aa9c)
Location: include/linux/ctype.h:49
Inline: True
Inline callers:
  - drivers/tty/n_tty.c:do_output_char
```
```
In drivers/power/supply/power_supply_sysfs.c (ffffffff81876428)
Location: include/linux/ctype.h:49
Inline: True
Inline callers:
  - drivers/power/supply/power_supply_sysfs.c:power_supply_uevent
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/kallsyms.c (ffffffff8115a7ac)
Location: include/linux/ctype.h:49
Inline: True
Inline callers:
  - kernel/kallsyms.c:s_show
```
```
In drivers/acpi/acpi_pnp.c (ffffffff815f9f0c)
Location: include/linux/ctype.h:49
Inline: True
Inline callers:
  - drivers/acpi/acpi_pnp.c:acpi_pnp_match
  - drivers/acpi/acpi_pnp.c:acpi_pnp_match
```
```
In drivers/acpi/acpica/nsrepair2.c (ffffffff816251dd)
Location: include/linux/ctype.h:49
Inline: True
Inline callers:
  - drivers/acpi/acpica/nsrepair2.c:acpi_ns_repair_HID
```
```
In drivers/acpi/acpica/nsutils.c (ffffffff81626253)
Location: include/linux/ctype.h:49
Inline: True
Inline callers:
  - drivers/acpi/acpica/nsutils.c:acpi_ns_build_internal_name
```
```
In drivers/acpi/acpica/utnonansi.c (ffffffff816367b6)
Location: include/linux/ctype.h:49
Inline: True
Inline callers:
  - drivers/acpi/acpica/utnonansi.c:acpi_ut_strupr
```
```
In drivers/acpi/acpica/dbconvert.c (ffffffff8163a466)
Location: include/linux/ctype.h:49
Inline: True
Inline callers:
  - drivers/acpi/acpica/dbconvert.c:acpi_db_hex_char_to_value
```
```
In drivers/pnp/driver.c (ffffffff81655129)
Location: include/linux/ctype.h:49
Inline: True
```
```
In drivers/tty/n_tty.c (ffffffff816950fc)
Location: include/linux/ctype.h:49
Inline: True
Inline callers:
  - drivers/tty/n_tty.c:do_output_char
```
```
In drivers/power/supply/power_supply_sysfs.c (ffffffff81891dc8)
Location: include/linux/ctype.h:49
Inline: True
Inline callers:
  - drivers/power/supply/power_supply_sysfs.c:power_supply_uevent
```
</details>
</li>
</ul>

## Differences
