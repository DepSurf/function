# Function: <code>__tolower</code>

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
In kernel/kallsyms.c (ffffffff8110aec2)
Location: include/linux/ctype.h:38
Inline: True
Inline callers:
  - kernel/kallsyms.c:s_show
```
```
In mm/slub.c (ffffffff81f8cd55)
Location: include/linux/ctype.h:38
Inline: True
Inline callers:
  - mm/slub.c:setup_slub_debug
```
```
In fs/efivarfs/super.c (ffffffff8132178c)
Location: include/linux/ctype.h:38
Inline: True
Inline callers:
  - fs/efivarfs/super.c:efivarfs_d_hash
```
```
In lib/string.c (ffffffff813f1732)
Location: include/linux/ctype.h:38
Inline: True
Inline callers:
  - lib/string.c:strcasecmp
  - lib/string.c:strcasecmp
```
```
In lib/hexdump.c (ffffffff814014dc)
Location: include/linux/ctype.h:38
Inline: True
Inline callers:
  - lib/hexdump.c:hex2bin
  - lib/hexdump.c:hex2bin
```
```
In drivers/acpi/device_sysfs.c (ffffffff8147be3a)
Location: include/linux/ctype.h:38
Inline: True
Inline callers:
  - drivers/acpi/device_sysfs.c:create_of_modalias
```
```
In drivers/acpi/acpica/utnonansi.c (ffffffff814a8cee)
Location: include/linux/ctype.h:38
Inline: True
Inline callers:
  - drivers/acpi/acpica/utnonansi.c:acpi_ut_strlwr
  - drivers/acpi/acpica/utnonansi.c:acpi_ut_stricmp
  - drivers/acpi/acpica/utnonansi.c:acpi_ut_stricmp
  - drivers/acpi/acpica/utnonansi.c:acpi_ut_strtoul64
```
```
In drivers/pnp/card.c (ffffffff814b7a2f)
Location: include/linux/ctype.h:38
Inline: True
Inline callers:
  - drivers/pnp/card.c:pnp_alloc_card
  - drivers/pnp/card.c:pnp_alloc_card
  - drivers/pnp/card.c:pnp_alloc_card
  - drivers/pnp/card.c:pnp_alloc_card
```
```
In drivers/pnp/driver.c (ffffffff814b83f8)
Location: include/linux/ctype.h:38
Inline: True
Inline callers:
  - drivers/pnp/driver.c:pnp_add_id
  - drivers/pnp/driver.c:pnp_add_id
  - drivers/pnp/driver.c:pnp_add_id
  - drivers/pnp/driver.c:pnp_add_id
```
```
In drivers/tty/n_tty.c (ffffffff814e5db4)
Location: include/linux/ctype.h:38
Inline: True
Inline callers:
  - drivers/tty/n_tty.c:n_tty_receive_char_lnext
  - drivers/tty/n_tty.c:n_tty_receive_buf_common
  - drivers/tty/n_tty.c:n_tty_receive_buf_common
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
In kernel/kallsyms.c (ffffffff8111267f)
Location: include/linux/ctype.h:38
Inline: True
Inline callers:
  - kernel/kallsyms.c:s_show
```
```
In mm/slub.c (ffffffff81fb6ad0)
Location: include/linux/ctype.h:38
Inline: True
Inline callers:
  - mm/slub.c:setup_slub_debug
```
```
In fs/efivarfs/super.c (ffffffff81356b63)
Location: include/linux/ctype.h:38
Inline: True
Inline callers:
  - fs/efivarfs/super.c:efivarfs_d_hash
```
```
In lib/string.c (ffffffff814380c9)
Location: include/linux/ctype.h:38
Inline: True
Inline callers:
  - lib/string.c:strcasecmp
  - lib/string.c:strcasecmp
```
```
In lib/hexdump.c (ffffffff81448f32)
Location: include/linux/ctype.h:38
Inline: True
Inline callers:
  - lib/hexdump.c:hex2bin
  - lib/hexdump.c:hex2bin
```
```
In drivers/acpi/device_sysfs.c (ffffffff814ca511)
Location: include/linux/ctype.h:38
Inline: True
Inline callers:
  - drivers/acpi/device_sysfs.c:create_of_modalias
```
```
In drivers/acpi/acpica/utnonansi.c (ffffffff814f8212)
Location: include/linux/ctype.h:38
Inline: True
Inline callers:
  - drivers/acpi/acpica/utnonansi.c:acpi_ut_strtoul64
  - drivers/acpi/acpica/utnonansi.c:acpi_ut_stricmp
  - drivers/acpi/acpica/utnonansi.c:acpi_ut_stricmp
  - drivers/acpi/acpica/utnonansi.c:acpi_ut_strlwr
```
```
In drivers/pnp/card.c (ffffffff8150745f)
Location: include/linux/ctype.h:38
Inline: True
Inline callers:
  - drivers/pnp/card.c:pnp_alloc_card
  - drivers/pnp/card.c:pnp_alloc_card
  - drivers/pnp/card.c:pnp_alloc_card
  - drivers/pnp/card.c:pnp_alloc_card
```
```
In drivers/pnp/driver.c (ffffffff81507e5a)
Location: include/linux/ctype.h:38
Inline: True
Inline callers:
  - drivers/pnp/driver.c:pnp_add_id
  - drivers/pnp/driver.c:pnp_add_id
  - drivers/pnp/driver.c:pnp_add_id
  - drivers/pnp/driver.c:pnp_add_id
```
```
In drivers/tty/n_tty.c (ffffffff81538847)
Location: include/linux/ctype.h:38
Inline: True
Inline callers:
  - drivers/tty/n_tty.c:n_tty_receive_buf_common
  - drivers/tty/n_tty.c:n_tty_receive_buf_common
  - drivers/tty/n_tty.c:n_tty_receive_char_lnext
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
In kernel/kallsyms.c (ffffffff81119d9c)
Location: include/linux/ctype.h:41
Inline: True
Inline callers:
  - kernel/kallsyms.c:s_show
```
```
In mm/slub.c (ffffffff81ff34df)
Location: include/linux/ctype.h:41
Inline: True
Inline callers:
  - mm/slub.c:setup_slub_debug
```
```
In fs/efivarfs/super.c (ffffffff8136cfc3)
Location: include/linux/ctype.h:41
Inline: True
Inline callers:
  - fs/efivarfs/super.c:efivarfs_d_hash
```
```
In lib/string.c (ffffffff814550b9)
Location: include/linux/ctype.h:41
Inline: True
Inline callers:
  - lib/string.c:strcasecmp
  - lib/string.c:strcasecmp
```
```
In lib/hexdump.c (ffffffff81467922)
Location: include/linux/ctype.h:41
Inline: True
Inline callers:
  - lib/hexdump.c:hex2bin
  - lib/hexdump.c:hex2bin
```
```
In drivers/acpi/device_sysfs.c (ffffffff814ec42d)
Location: include/linux/ctype.h:41
Inline: True
Inline callers:
  - drivers/acpi/device_sysfs.c:create_of_modalias
```
```
In drivers/acpi/acpica/utnonansi.c (ffffffff8151ac25)
Location: include/linux/ctype.h:41
Inline: True
Inline callers:
  - drivers/acpi/acpica/utnonansi.c:acpi_ut_stricmp
  - drivers/acpi/acpica/utnonansi.c:acpi_ut_stricmp
  - drivers/acpi/acpica/utnonansi.c:acpi_ut_strlwr
```
```
In drivers/acpi/acpica/utstrtoul64.c (ffffffff8151be59)
Location: include/linux/ctype.h:41
Inline: True
Inline callers:
  - drivers/acpi/acpica/utstrtoul64.c:acpi_ut_strtoul64
```
```
In drivers/pnp/card.c (ffffffff8152b67f)
Location: include/linux/ctype.h:41
Inline: True
Inline callers:
  - drivers/pnp/card.c:pnp_alloc_card
  - drivers/pnp/card.c:pnp_alloc_card
  - drivers/pnp/card.c:pnp_alloc_card
  - drivers/pnp/card.c:pnp_alloc_card
```
```
In drivers/pnp/driver.c (ffffffff8152c07a)
Location: include/linux/ctype.h:41
Inline: True
Inline callers:
  - drivers/pnp/driver.c:pnp_add_id
  - drivers/pnp/driver.c:pnp_add_id
  - drivers/pnp/driver.c:pnp_add_id
  - drivers/pnp/driver.c:pnp_add_id
```
```
In drivers/tty/n_tty.c (ffffffff81564f57)
Location: include/linux/ctype.h:41
Inline: True
Inline callers:
  - drivers/tty/n_tty.c:n_tty_receive_buf_common
  - drivers/tty/n_tty.c:n_tty_receive_buf_common
  - drivers/tty/n_tty.c:n_tty_receive_char_lnext
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
In kernel/kallsyms.c (ffffffff8111b82e)
Location: include/linux/ctype.h:41
Inline: True
Inline callers:
  - kernel/kallsyms.c:s_show
```
```
In mm/slub.c (ffffffff820d5c0a)
Location: include/linux/ctype.h:41
Inline: True
Inline callers:
  - mm/slub.c:setup_slub_debug
```
```
In fs/efivarfs/super.c (ffffffff8138151a)
Location: include/linux/ctype.h:41
Inline: True
Inline callers:
  - fs/efivarfs/super.c:efivarfs_d_hash
```
```
In lib/hexdump.c (ffffffff8146d012)
Location: include/linux/ctype.h:41
Inline: True
Inline callers:
  - lib/hexdump.c:hex2bin
  - lib/hexdump.c:hex2bin
```
```
In drivers/acpi/device_sysfs.c (ffffffff814f929e)
Location: include/linux/ctype.h:41
Inline: True
```
```
In drivers/acpi/acpica/utnonansi.c (ffffffff8152b446)
Location: include/linux/ctype.h:41
Inline: True
Inline callers:
  - drivers/acpi/acpica/utnonansi.c:acpi_ut_stricmp
  - drivers/acpi/acpica/utnonansi.c:acpi_ut_stricmp
  - drivers/acpi/acpica/utnonansi.c:acpi_ut_strlwr
```
```
In drivers/acpi/acpica/utstrtoul64.c (ffffffff8152c66e)
Location: include/linux/ctype.h:41
Inline: True
Inline callers:
  - drivers/acpi/acpica/utstrtoul64.c:acpi_ut_strtoul64
```
```
In drivers/pnp/card.c (ffffffff8153e75f)
Location: include/linux/ctype.h:41
Inline: True
Inline callers:
  - drivers/pnp/card.c:pnp_alloc_card
  - drivers/pnp/card.c:pnp_alloc_card
  - drivers/pnp/card.c:pnp_alloc_card
  - drivers/pnp/card.c:pnp_alloc_card
```
```
In drivers/pnp/driver.c (ffffffff8153f16a)
Location: include/linux/ctype.h:41
Inline: True
Inline callers:
  - drivers/pnp/driver.c:pnp_add_id
  - drivers/pnp/driver.c:pnp_add_id
  - drivers/pnp/driver.c:pnp_add_id
  - drivers/pnp/driver.c:pnp_add_id
```
```
In drivers/tty/n_tty.c (ffffffff81577ec7)
Location: include/linux/ctype.h:41
Inline: True
Inline callers:
  - drivers/tty/n_tty.c:n_tty_receive_buf_common
  - drivers/tty/n_tty.c:n_tty_receive_buf_common
  - drivers/tty/n_tty.c:n_tty_receive_char_lnext
```
```
In lib/string.c (ffffffff818f6c19)
Location: include/linux/ctype.h:41
Inline: True
Inline callers:
  - lib/string.c:strcasecmp
  - lib/string.c:strcasecmp
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
In kernel/kallsyms.c (ffffffff81126dbc)
Location: include/linux/ctype.h:42
Inline: True
Inline callers:
  - kernel/kallsyms.c:s_show
```
```
In mm/slub.c (ffffffff826de852)
Location: include/linux/ctype.h:42
Inline: True
Inline callers:
  - mm/slub.c:setup_slub_debug
```
```
In fs/efivarfs/super.c (ffffffff813a652a)
Location: include/linux/ctype.h:42
Inline: True
Inline callers:
  - fs/efivarfs/super.c:efivarfs_d_hash
```
```
In lib/hexdump.c (ffffffff81499342)
Location: include/linux/ctype.h:42
Inline: True
Inline callers:
  - lib/hexdump.c:hex2bin
  - lib/hexdump.c:hex2bin
```
```
In drivers/acpi/device_sysfs.c (ffffffff8153ab0e)
Location: include/linux/ctype.h:42
Inline: True
```
```
In drivers/acpi/acpica/utnonansi.c (ffffffff8158522f)
Location: include/linux/ctype.h:42
Inline: True
Inline callers:
  - drivers/acpi/acpica/utnonansi.c:acpi_ut_stricmp
  - drivers/acpi/acpica/utnonansi.c:acpi_ut_stricmp
  - drivers/acpi/acpica/utnonansi.c:acpi_ut_strlwr
```
```
In drivers/acpi/acpica/utstrsuppt.c (ffffffff815870e7)
Location: include/linux/ctype.h:42
Inline: True
Inline callers:
  - drivers/acpi/acpica/utstrsuppt.c:acpi_ut_detect_hex_prefix
```
```
In drivers/acpi/acpica/dbinput.c (ffffffff8158af27)
Location: include/linux/ctype.h:42
Inline: True
Inline callers:
  - drivers/acpi/acpica/dbinput.c:acpi_db_display_command_info
  - drivers/acpi/acpica/dbinput.c:acpi_db_display_command_info
```
```
In drivers/pnp/card.c (ffffffff815a17ef)
Location: include/linux/ctype.h:42
Inline: True
Inline callers:
  - drivers/pnp/card.c:pnp_alloc_card
  - drivers/pnp/card.c:pnp_alloc_card
  - drivers/pnp/card.c:pnp_alloc_card
  - drivers/pnp/card.c:pnp_alloc_card
```
```
In drivers/pnp/driver.c (ffffffff815a221a)
Location: include/linux/ctype.h:42
Inline: True
Inline callers:
  - drivers/pnp/driver.c:pnp_add_id
  - drivers/pnp/driver.c:pnp_add_id
  - drivers/pnp/driver.c:pnp_add_id
  - drivers/pnp/driver.c:pnp_add_id
```
```
In drivers/tty/n_tty.c (ffffffff815dc84a)
Location: include/linux/ctype.h:42
Inline: True
Inline callers:
  - drivers/tty/n_tty.c:n_tty_receive_buf_common
  - drivers/tty/n_tty.c:n_tty_receive_buf_common
  - drivers/tty/n_tty.c:n_tty_receive_char_lnext
```
```
In lib/string.c (ffffffff8197d619)
Location: include/linux/ctype.h:42
Inline: True
Inline callers:
  - lib/string.c:strcasecmp
  - lib/string.c:strcasecmp
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
In kernel/kallsyms.c (ffffffff81134cd7)
Location: include/linux/ctype.h:42
Inline: True
Inline callers:
  - kernel/kallsyms.c:s_show
```
```
In mm/slub.c (ffffffff82708d8e)
Location: include/linux/ctype.h:42
Inline: True
Inline callers:
  - mm/slub.c:setup_slub_debug
```
```
In fs/efivarfs/super.c (ffffffff813d583e)
Location: include/linux/ctype.h:42
Inline: True
Inline callers:
  - fs/efivarfs/super.c:efivarfs_d_hash
```
```
In lib/hexdump.c (ffffffff814ceba0)
Location: include/linux/ctype.h:42
Inline: True
```
```
In drivers/acpi/device_sysfs.c (ffffffff8157098d)
Location: include/linux/ctype.h:42
Inline: True
```
```
In drivers/acpi/acpica/utnonansi.c (ffffffff815bc3db)
Location: include/linux/ctype.h:42
Inline: True
Inline callers:
  - drivers/acpi/acpica/utnonansi.c:acpi_ut_stricmp
  - drivers/acpi/acpica/utnonansi.c:acpi_ut_stricmp
  - drivers/acpi/acpica/utnonansi.c:acpi_ut_strlwr
```
```
In drivers/acpi/acpica/utstrsuppt.c (ffffffff815be293)
Location: include/linux/ctype.h:42
Inline: True
Inline callers:
  - drivers/acpi/acpica/utstrsuppt.c:acpi_ut_detect_hex_prefix
```
```
In drivers/acpi/acpica/dbinput.c (ffffffff815c2246)
Location: include/linux/ctype.h:42
Inline: True
Inline callers:
  - drivers/acpi/acpica/dbinput.c:acpi_db_display_command_info
  - drivers/acpi/acpica/dbinput.c:acpi_db_display_command_info
```
```
In drivers/pnp/card.c (ffffffff815d948a)
Location: include/linux/ctype.h:42
Inline: True
Inline callers:
  - drivers/pnp/card.c:pnp_alloc_card
  - drivers/pnp/card.c:pnp_alloc_card
  - drivers/pnp/card.c:pnp_alloc_card
  - drivers/pnp/card.c:pnp_alloc_card
```
```
In drivers/pnp/driver.c (ffffffff815d9e95)
Location: include/linux/ctype.h:42
Inline: True
Inline callers:
  - drivers/pnp/driver.c:pnp_add_id
  - drivers/pnp/driver.c:pnp_add_id
  - drivers/pnp/driver.c:pnp_add_id
  - drivers/pnp/driver.c:pnp_add_id
```
```
In drivers/tty/n_tty.c (ffffffff81615b62)
Location: include/linux/ctype.h:42
Inline: True
Inline callers:
  - drivers/tty/n_tty.c:n_tty_receive_buf_common
  - drivers/tty/n_tty.c:n_tty_receive_buf_common
  - drivers/tty/n_tty.c:n_tty_receive_char_lnext
```
```
In lib/string.c (ffffffff819d9b24)
Location: include/linux/ctype.h:42
Inline: True
Inline callers:
  - lib/string.c:strcasecmp
  - lib/string.c:strcasecmp
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
In kernel/kallsyms.c (ffffffff81140477)
Location: include/linux/ctype.h:42
Inline: True
Inline callers:
  - kernel/kallsyms.c:s_show
```
```
In mm/slub.c (ffffffff828c0033)
Location: include/linux/ctype.h:42
Inline: True
Inline callers:
  - mm/slub.c:setup_slub_debug
```
```
In fs/efivarfs/super.c (ffffffff813efe8e)
Location: include/linux/ctype.h:42
Inline: True
Inline callers:
  - fs/efivarfs/super.c:efivarfs_d_hash
```
```
In lib/hexdump.c (ffffffff814e3490)
Location: include/linux/ctype.h:42
Inline: True
```
```
In drivers/acpi/device_sysfs.c (ffffffff81588555)
Location: include/linux/ctype.h:42
Inline: True
```
```
In drivers/acpi/acpica/utnonansi.c (ffffffff815d5821)
Location: include/linux/ctype.h:42
Inline: True
Inline callers:
  - drivers/acpi/acpica/utnonansi.c:acpi_ut_stricmp
  - drivers/acpi/acpica/utnonansi.c:acpi_ut_stricmp
  - drivers/acpi/acpica/utnonansi.c:acpi_ut_strlwr
```
```
In drivers/acpi/acpica/utstrsuppt.c (ffffffff815d76dc)
Location: include/linux/ctype.h:42
Inline: True
Inline callers:
  - drivers/acpi/acpica/utstrsuppt.c:acpi_ut_remove_hex_prefix
```
```
In drivers/acpi/acpica/dbinput.c (ffffffff815db6cc)
Location: include/linux/ctype.h:42
Inline: True
Inline callers:
  - drivers/acpi/acpica/dbinput.c:acpi_db_display_command_info
  - drivers/acpi/acpica/dbinput.c:acpi_db_display_command_info
```
```
In drivers/pnp/card.c (ffffffff815f2daa)
Location: include/linux/ctype.h:42
Inline: True
Inline callers:
  - drivers/pnp/card.c:pnp_alloc_card
  - drivers/pnp/card.c:pnp_alloc_card
  - drivers/pnp/card.c:pnp_alloc_card
  - drivers/pnp/card.c:pnp_alloc_card
```
```
In drivers/pnp/driver.c (ffffffff815f37b5)
Location: include/linux/ctype.h:42
Inline: True
Inline callers:
  - drivers/pnp/driver.c:pnp_add_id
  - drivers/pnp/driver.c:pnp_add_id
  - drivers/pnp/driver.c:pnp_add_id
  - drivers/pnp/driver.c:pnp_add_id
```
```
In drivers/tty/n_tty.c (ffffffff81632b58)
Location: include/linux/ctype.h:42
Inline: True
Inline callers:
  - drivers/tty/n_tty.c:n_tty_receive_buf_common
  - drivers/tty/n_tty.c:n_tty_receive_buf_common
  - drivers/tty/n_tty.c:n_tty_receive_char_lnext
```
```
In lib/string.c (ffffffff81a11d44)
Location: include/linux/ctype.h:42
Inline: True
Inline callers:
  - lib/string.c:strcasecmp
  - lib/string.c:strcasecmp
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
In kernel/kallsyms.c (ffffffff8114b867)
Location: include/linux/ctype.h:42
Inline: True
Inline callers:
  - kernel/kallsyms.c:s_show
```
```
In mm/slub.c (ffffffff828d939b)
Location: include/linux/ctype.h:42
Inline: True
Inline callers:
  - mm/slub.c:setup_slub_debug
```
```
In fs/efivarfs/super.c (ffffffff8141c1c4)
Location: include/linux/ctype.h:42
Inline: True
Inline callers:
  - fs/efivarfs/super.c:efivarfs_d_hash
```
```
In lib/hexdump.c (ffffffff8150f830)
Location: include/linux/ctype.h:42
Inline: True
```
```
In drivers/acpi/device_sysfs.c (ffffffff815b920f)
Location: include/linux/ctype.h:42
Inline: True
```
```
In drivers/acpi/acpica/utnonansi.c (ffffffff816071b6)
Location: include/linux/ctype.h:42
Inline: True
Inline callers:
  - drivers/acpi/acpica/utnonansi.c:acpi_ut_stricmp
  - drivers/acpi/acpica/utnonansi.c:acpi_ut_stricmp
  - drivers/acpi/acpica/utnonansi.c:acpi_ut_strlwr
```
```
In drivers/acpi/acpica/utstrsuppt.c (ffffffff816090dd)
Location: include/linux/ctype.h:42
Inline: True
Inline callers:
  - drivers/acpi/acpica/utstrsuppt.c:acpi_ut_remove_hex_prefix
```
```
In drivers/acpi/acpica/dbinput.c (ffffffff8160d1cb)
Location: include/linux/ctype.h:42
Inline: True
Inline callers:
  - drivers/acpi/acpica/dbinput.c:acpi_db_display_command_info
  - drivers/acpi/acpica/dbinput.c:acpi_db_display_command_info
```
```
In drivers/pnp/card.c (ffffffff81624c99)
Location: include/linux/ctype.h:42
Inline: True
Inline callers:
  - drivers/pnp/card.c:pnp_alloc_card
  - drivers/pnp/card.c:pnp_alloc_card
  - drivers/pnp/card.c:pnp_alloc_card
  - drivers/pnp/card.c:pnp_alloc_card
```
```
In drivers/pnp/driver.c (ffffffff81625685)
Location: include/linux/ctype.h:42
Inline: True
Inline callers:
  - drivers/pnp/driver.c:pnp_add_id
  - drivers/pnp/driver.c:pnp_add_id
  - drivers/pnp/driver.c:pnp_add_id
  - drivers/pnp/driver.c:pnp_add_id
```
```
In drivers/tty/n_tty.c (ffffffff8166764f)
Location: include/linux/ctype.h:42
Inline: True
Inline callers:
  - drivers/tty/n_tty.c:n_tty_receive_buf_common
  - drivers/tty/n_tty.c:n_tty_receive_buf_common
  - drivers/tty/n_tty.c:n_tty_receive_char_lnext
```
```
In lib/string.c (ffffffff81a8125d)
Location: include/linux/ctype.h:42
Inline: True
Inline callers:
  - lib/string.c:strcasecmp
  - lib/string.c:strcasecmp
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
In kernel/kallsyms.c (ffffffff81157537)
Location: include/linux/ctype.h:42
Inline: True
Inline callers:
  - kernel/kallsyms.c:s_show
```
```
In mm/slub.c (ffffffff828e17ee)
Location: include/linux/ctype.h:42
Inline: True
Inline callers:
  - mm/slub.c:setup_slub_debug
```
```
In fs/efivarfs/super.c (ffffffff81436014)
Location: include/linux/ctype.h:42
Inline: True
Inline callers:
  - fs/efivarfs/super.c:efivarfs_d_hash
```
```
In lib/hexdump.c (ffffffff8152d184)
Location: include/linux/ctype.h:42
Inline: True
Inline callers:
  - lib/hexdump.c:hex2bin
  - lib/hexdump.c:hex2bin
```
```
In drivers/acpi/device_sysfs.c (ffffffff815da44f)
Location: include/linux/ctype.h:42
Inline: True
```
```
In drivers/acpi/acpica/utnonansi.c (ffffffff81628651)
Location: include/linux/ctype.h:42
Inline: True
Inline callers:
  - drivers/acpi/acpica/utnonansi.c:acpi_ut_stricmp
  - drivers/acpi/acpica/utnonansi.c:acpi_ut_stricmp
  - drivers/acpi/acpica/utnonansi.c:acpi_ut_strlwr
```
```
In drivers/acpi/acpica/utstrsuppt.c (ffffffff8162a57e)
Location: include/linux/ctype.h:42
Inline: True
Inline callers:
  - drivers/acpi/acpica/utstrsuppt.c:acpi_ut_remove_hex_prefix
```
```
In drivers/acpi/acpica/dbinput.c (ffffffff8162e66c)
Location: include/linux/ctype.h:42
Inline: True
Inline callers:
  - drivers/acpi/acpica/dbinput.c:acpi_db_display_command_info
  - drivers/acpi/acpica/dbinput.c:acpi_db_display_command_info
```
```
In drivers/pnp/card.c (ffffffff81646789)
Location: include/linux/ctype.h:42
Inline: True
Inline callers:
  - drivers/pnp/card.c:pnp_alloc_card
  - drivers/pnp/card.c:pnp_alloc_card
  - drivers/pnp/card.c:pnp_alloc_card
  - drivers/pnp/card.c:pnp_alloc_card
```
```
In drivers/pnp/driver.c (ffffffff81647175)
Location: include/linux/ctype.h:42
Inline: True
Inline callers:
  - drivers/pnp/driver.c:pnp_add_id
  - drivers/pnp/driver.c:pnp_add_id
  - drivers/pnp/driver.c:pnp_add_id
  - drivers/pnp/driver.c:pnp_add_id
```
```
In drivers/tty/n_tty.c (ffffffff81689d9f)
Location: include/linux/ctype.h:42
Inline: True
Inline callers:
  - drivers/tty/n_tty.c:n_tty_receive_buf_common
  - drivers/tty/n_tty.c:n_tty_receive_buf_common
  - drivers/tty/n_tty.c:n_tty_receive_char_lnext
```
```
In lib/string.c (ffffffff81ab845d)
Location: include/linux/ctype.h:42
Inline: True
Inline callers:
  - lib/string.c:strcasecmp
  - lib/string.c:strcasecmp
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Duplicate, Selective Inline ⚠️</summary>

```c
unsigned char __tolower(unsigned char c);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/kallsyms.c (ffffffff811680c7)
Location: include/linux/ctype.h:42
Inline: True
Inline callers:
  - kernel/kallsyms.c:s_show
```
```
In mm/slub.c (ffffffff82cfedad)
Location: include/linux/ctype.h:42
Inline: True
Inline callers:
  - mm/slub.c:setup_slub_debug
```
```
In fs/efivarfs/super.c (ffffffff81485da9)
Location: include/linux/ctype.h:42
Inline: True
Inline callers:
  - fs/efivarfs/super.c:efivarfs_d_hash
```
```
In lib/hexdump.c (ffffffff81591474)
Location: include/linux/ctype.h:42
Inline: True
Inline callers:
  - lib/hexdump.c:hex2bin
  - lib/hexdump.c:hex2bin
```
```
In lib/string.c (ffffffff815f3082)
Location: include/linux/ctype.h:42
Inline: True
Inline callers:
  - lib/string.c:strcasecmp
  - lib/string.c:strcasecmp
```
```
In drivers/acpi/device_sysfs.c (ffffffff81683f63)
Location: include/linux/ctype.h:42
Inline: True
Inline callers:
  - drivers/acpi/device_sysfs.c:create_of_modalias
```
```
In drivers/acpi/acpica/utnonansi.c (ffffffff816d4d6d)
Location: include/linux/ctype.h:42
Inline: False
Direct callers:
  - drivers/acpi/acpica/utnonansi.c:acpi_ut_stricmp
  - drivers/acpi/acpica/utnonansi.c:acpi_ut_stricmp
  - drivers/acpi/acpica/utnonansi.c:acpi_ut_strlwr
```
```
In drivers/acpi/acpica/utstrsuppt.c (ffffffff816d6d57)
Location: include/linux/ctype.h:42
Inline: True
Inline callers:
  - drivers/acpi/acpica/utstrsuppt.c:acpi_ut_remove_hex_prefix
```
```
In drivers/acpi/acpica/dbinput.c (ffffffff816daf79)
Location: include/linux/ctype.h:42
Inline: True
Inline callers:
  - drivers/acpi/acpica/dbinput.c:acpi_db_match_command_help
  - drivers/acpi/acpica/dbinput.c:acpi_db_match_command_help
```
```
In drivers/pnp/card.c (ffffffff816f514a)
Location: include/linux/ctype.h:42
Inline: True
```
```
In drivers/pnp/driver.c (ffffffff816f5efa)
Location: include/linux/ctype.h:42
Inline: True
Inline callers:
  - drivers/pnp/driver.c:pnp_add_id
  - drivers/pnp/driver.c:pnp_add_id
  - drivers/pnp/driver.c:pnp_add_id
  - drivers/pnp/driver.c:pnp_add_id
```
```
In drivers/tty/n_tty.c (ffffffff8173ba87)
Location: include/linux/ctype.h:42
Inline: True
Inline callers:
  - drivers/tty/n_tty.c:n_tty_receive_buf_standard
  - drivers/tty/n_tty.c:n_tty_receive_buf_closing
  - drivers/tty/n_tty.c:n_tty_receive_char_lnext
```
```
In drivers/power/supply/power_supply_sysfs.c (ffffffff8194f543)
Location: include/linux/ctype.h:42
Inline: True
Inline callers:
  - drivers/power/supply/power_supply_sysfs.c:power_supply_init_attrs
```
**Symbols:**

```
ffffffff816d4d6d-ffffffff816d4d80: __tolower (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Duplicate, Selective Inline ⚠️</summary>

```c
unsigned char __tolower(unsigned char c);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/kallsyms.c (ffffffff811646b7)
Location: include/linux/ctype.h:49
Inline: True
Inline callers:
  - kernel/kallsyms.c:s_show
```
```
In mm/slub.c (ffffffff812e2eef)
Location: include/linux/ctype.h:49
Inline: True
Inline callers:
  - mm/slub.c:parse_slub_debug_flags
```
```
In fs/efivarfs/super.c (ffffffff814a3399)
Location: include/linux/ctype.h:49
Inline: True
Inline callers:
  - fs/efivarfs/super.c:efivarfs_d_hash
```
```
In lib/hexdump.c (ffffffff815ae024)
Location: include/linux/ctype.h:49
Inline: True
Inline callers:
  - lib/hexdump.c:hex2bin
  - lib/hexdump.c:hex2bin
```
```
In lib/string.c (ffffffff81617732)
Location: include/linux/ctype.h:49
Inline: True
Inline callers:
  - lib/string.c:strcasecmp
  - lib/string.c:strcasecmp
```
```
In drivers/acpi/device_sysfs.c (ffffffff816a1d23)
Location: include/linux/ctype.h:49
Inline: True
Inline callers:
  - drivers/acpi/device_sysfs.c:create_of_modalias
```
```
In drivers/acpi/acpica/utnonansi.c (ffffffff816f2d3a)
Location: include/linux/ctype.h:49
Inline: False
Direct callers:
  - drivers/acpi/acpica/utnonansi.c:acpi_ut_stricmp
  - drivers/acpi/acpica/utnonansi.c:acpi_ut_stricmp
  - drivers/acpi/acpica/utnonansi.c:acpi_ut_strlwr
```
```
In drivers/acpi/acpica/utstrsuppt.c (ffffffff816f4cfd)
Location: include/linux/ctype.h:49
Inline: True
Inline callers:
  - drivers/acpi/acpica/utstrsuppt.c:acpi_ut_remove_hex_prefix
```
```
In drivers/acpi/acpica/dbinput.c (ffffffff816f8f3e)
Location: include/linux/ctype.h:49
Inline: True
Inline callers:
  - drivers/acpi/acpica/dbinput.c:acpi_db_match_command_help
  - drivers/acpi/acpica/dbinput.c:acpi_db_match_command_help
```
```
In drivers/pnp/card.c (ffffffff817121aa)
Location: include/linux/ctype.h:49
Inline: True
```
```
In drivers/pnp/driver.c (ffffffff81712f3a)
Location: include/linux/ctype.h:49
Inline: True
Inline callers:
  - drivers/pnp/driver.c:pnp_add_id
  - drivers/pnp/driver.c:pnp_add_id
  - drivers/pnp/driver.c:pnp_add_id
  - drivers/pnp/driver.c:pnp_add_id
```
```
In drivers/tty/n_tty.c (ffffffff81757bf7)
Location: include/linux/ctype.h:49
Inline: True
Inline callers:
  - drivers/tty/n_tty.c:n_tty_receive_buf_standard
  - drivers/tty/n_tty.c:n_tty_receive_buf_closing
  - drivers/tty/n_tty.c:n_tty_receive_char_lnext
```
```
In drivers/power/supply/power_supply_sysfs.c (ffffffff81954f63)
Location: include/linux/ctype.h:49
Inline: True
Inline callers:
  - drivers/power/supply/power_supply_sysfs.c:power_supply_init_attrs
```
**Symbols:**

```
ffffffff816f2d3a-ffffffff816f2d4d: __tolower (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Duplicate, Selective Inline ⚠️</summary>

```c
unsigned char __tolower(unsigned char c);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/kallsyms.c (ffffffff81165497)
Location: include/linux/ctype.h:49
Inline: True
Inline callers:
  - kernel/kallsyms.c:s_show
```
```
In mm/slub.c (ffffffff812ea675)
Location: include/linux/ctype.h:49
Inline: True
Inline callers:
  - mm/slub.c:parse_slub_debug_flags
```
```
In fs/efivarfs/super.c (ffffffff814a93b8)
Location: include/linux/ctype.h:49
Inline: True
Inline callers:
  - fs/efivarfs/super.c:efivarfs_d_hash
```
```
In lib/hexdump.c (ffffffff815b8cb7)
Location: include/linux/ctype.h:49
Inline: True
Inline callers:
  - lib/hexdump.c:hex2bin
  - lib/hexdump.c:hex2bin
```
```
In lib/string.c (ffffffff815fadaf)
Location: include/linux/ctype.h:49
Inline: True
Inline callers:
  - lib/string.c:strcasecmp
  - lib/string.c:strcasecmp
```
```
In drivers/acpi/device_sysfs.c (ffffffff81684b13)
Location: include/linux/ctype.h:49
Inline: True
Inline callers:
  - drivers/acpi/device_sysfs.c:create_of_modalias
```
```
In drivers/acpi/acpica/utnonansi.c (ffffffff816d4bea)
Location: include/linux/ctype.h:49
Inline: False
Direct callers:
  - drivers/acpi/acpica/utnonansi.c:acpi_ut_stricmp
  - drivers/acpi/acpica/utnonansi.c:acpi_ut_stricmp
  - drivers/acpi/acpica/utnonansi.c:acpi_ut_strlwr
```
```
In drivers/acpi/acpica/utstrsuppt.c (ffffffff816d6b9a)
Location: include/linux/ctype.h:49
Inline: True
Inline callers:
  - drivers/acpi/acpica/utstrsuppt.c:acpi_ut_remove_hex_prefix
```
```
In drivers/acpi/acpica/dbinput.c (ffffffff816dadbd)
Location: include/linux/ctype.h:49
Inline: True
Inline callers:
  - drivers/acpi/acpica/dbinput.c:acpi_db_display_command_info
  - drivers/acpi/acpica/dbinput.c:acpi_db_display_command_info
```
```
In drivers/pnp/card.c (ffffffff816f385c)
Location: include/linux/ctype.h:49
Inline: True
Inline callers:
  - drivers/pnp/card.c:pnp_alloc_card
  - drivers/pnp/card.c:pnp_alloc_card
  - drivers/pnp/card.c:pnp_alloc_card
  - drivers/pnp/card.c:pnp_alloc_card
```
```
In drivers/pnp/driver.c (ffffffff816f42fa)
Location: include/linux/ctype.h:49
Inline: True
Inline callers:
  - drivers/pnp/driver.c:pnp_add_id
  - drivers/pnp/driver.c:pnp_add_id
  - drivers/pnp/driver.c:pnp_add_id
  - drivers/pnp/driver.c:pnp_add_id
```
```
In drivers/tty/n_tty.c (ffffffff8173c2cc)
Location: include/linux/ctype.h:49
Inline: True
Inline callers:
  - drivers/tty/n_tty.c:__receive_buf
  - drivers/tty/n_tty.c:n_tty_receive_buf_standard
  - drivers/tty/n_tty.c:n_tty_receive_char_lnext
```
```
In drivers/power/supply/power_supply_sysfs.c (ffffffff81938d95)
Location: include/linux/ctype.h:49
Inline: True
Inline callers:
  - drivers/power/supply/power_supply_sysfs.c:power_supply_init_attrs
```
**Symbols:**

```
ffffffff816d4bea-ffffffff816d4bfd: __tolower (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Duplicate, Selective Inline ⚠️</summary>

```c
unsigned char __tolower(unsigned char c);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/kallsyms.c (ffffffff8118abb7)
Location: include/linux/ctype.h:49
Inline: True
Inline callers:
  - kernel/kallsyms.c:s_show
```
```
In kernel/debug/kdb/kdb_support.c (ffffffff811c9d4e)
Location: include/linux/ctype.h:49
Inline: True
```
```
In mm/slub.c (ffffffff813325b5)
Location: include/linux/ctype.h:49
Inline: True
Inline callers:
  - mm/slub.c:parse_slub_debug_flags
```
```
In fs/efivarfs/super.c (ffffffff81501748)
Location: include/linux/ctype.h:49
Inline: True
Inline callers:
  - fs/efivarfs/super.c:efivarfs_d_hash
```
```
In lib/hexdump.c (ffffffff8161f507)
Location: include/linux/ctype.h:49
Inline: True
Inline callers:
  - lib/hexdump.c:hex2bin
  - lib/hexdump.c:hex2bin
```
```
In lib/string.c (ffffffff8166865f)
Location: include/linux/ctype.h:49
Inline: True
Inline callers:
  - lib/string.c:strcasecmp
  - lib/string.c:strcasecmp
```
```
In drivers/acpi/device_sysfs.c (ffffffff816f9dd3)
Location: include/linux/ctype.h:49
Inline: True
Inline callers:
  - drivers/acpi/device_sysfs.c:create_of_modalias
```
```
In drivers/acpi/acpica/utnonansi.c (ffffffff8174c611)
Location: include/linux/ctype.h:49
Inline: False
Direct callers:
  - drivers/acpi/acpica/utnonansi.c:acpi_ut_stricmp
  - drivers/acpi/acpica/utnonansi.c:acpi_ut_stricmp
  - drivers/acpi/acpica/utnonansi.c:acpi_ut_strlwr
```
```
In drivers/acpi/acpica/utstrsuppt.c (ffffffff8174e706)
Location: include/linux/ctype.h:49
Inline: True
Inline callers:
  - drivers/acpi/acpica/utstrsuppt.c:acpi_ut_remove_hex_prefix
```
```
In drivers/acpi/acpica/dbinput.c (ffffffff81752bb8)
Location: include/linux/ctype.h:49
Inline: True
Inline callers:
  - drivers/acpi/acpica/dbinput.c:acpi_db_display_command_info
  - drivers/acpi/acpica/dbinput.c:acpi_db_display_command_info
```
```
In drivers/pnp/card.c (ffffffff8176dc7c)
Location: include/linux/ctype.h:49
Inline: True
Inline callers:
  - drivers/pnp/card.c:pnp_alloc_card
  - drivers/pnp/card.c:pnp_alloc_card
  - drivers/pnp/card.c:pnp_alloc_card
  - drivers/pnp/card.c:pnp_alloc_card
```
```
In drivers/pnp/driver.c (ffffffff8176e73a)
Location: include/linux/ctype.h:49
Inline: True
Inline callers:
  - drivers/pnp/driver.c:pnp_add_id
  - drivers/pnp/driver.c:pnp_add_id
  - drivers/pnp/driver.c:pnp_add_id
  - drivers/pnp/driver.c:pnp_add_id
```
```
In drivers/tty/n_tty.c (ffffffff817bc893)
Location: include/linux/ctype.h:49
Inline: True
Inline callers:
  - drivers/tty/n_tty.c:__receive_buf
  - drivers/tty/n_tty.c:n_tty_receive_buf_standard
  - drivers/tty/n_tty.c:n_tty_receive_buf_standard
```
```
In drivers/power/supply/power_supply_sysfs.c (ffffffff819dd3f5)
Location: include/linux/ctype.h:49
Inline: True
Inline callers:
  - drivers/power/supply/power_supply_sysfs.c:power_supply_init_attrs
```
**Symbols:**

```
ffffffff8174c611-ffffffff8174c624: __tolower (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Duplicate, Selective Inline ⚠️</summary>

```c
unsigned char __tolower(unsigned char c);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/kallsyms.c (ffffffff811b9d0a)
Location: include/linux/ctype.h:49
Inline: True
Inline callers:
  - kernel/kallsyms.c:s_show
```
```
In kernel/debug/kdb/kdb_support.c (ffffffff811fd939)
Location: include/linux/ctype.h:49
Inline: True
```
```
In mm/slub.c (ffffffff813a3a91)
Location: include/linux/ctype.h:49
Inline: True
Inline callers:
  - mm/slub.c:parse_slub_debug_flags
```
```
In fs/efivarfs/super.c (ffffffff81592b2a)
Location: include/linux/ctype.h:49
Inline: True
Inline callers:
  - fs/efivarfs/super.c:efivarfs_d_hash
```
```
In lib/string.c (ffffffff81781b9f)
Location: include/linux/ctype.h:49
Inline: True
Inline callers:
  - lib/string.c:strcasecmp
  - lib/string.c:strcasecmp
```
```
In drivers/acpi/device_sysfs.c (ffffffff81827133)
Location: include/linux/ctype.h:49
Inline: True
Inline callers:
  - drivers/acpi/device_sysfs.c:create_of_modalias
```
```
In drivers/acpi/acpica/utnonansi.c (ffffffff8187ecb7)
Location: include/linux/ctype.h:49
Inline: False
Direct callers:
  - drivers/acpi/acpica/utnonansi.c:acpi_ut_stricmp
  - drivers/acpi/acpica/utnonansi.c:acpi_ut_stricmp
  - drivers/acpi/acpica/utnonansi.c:acpi_ut_strlwr
```
```
In drivers/acpi/acpica/utstrsuppt.c (ffffffff81881009)
Location: include/linux/ctype.h:49
Inline: True
Inline callers:
  - drivers/acpi/acpica/utstrsuppt.c:acpi_ut_remove_hex_prefix
```
```
In drivers/acpi/acpica/dbinput.c (ffffffff818859bf)
Location: include/linux/ctype.h:49
Inline: True
Inline callers:
  - drivers/acpi/acpica/dbinput.c:acpi_db_display_command_info
  - drivers/acpi/acpica/dbinput.c:acpi_db_display_command_info
```
```
In drivers/pnp/card.c (ffffffff818a2dd4)
Location: include/linux/ctype.h:49
Inline: True
Inline callers:
  - drivers/pnp/card.c:pnp_alloc_card
  - drivers/pnp/card.c:pnp_alloc_card
  - drivers/pnp/card.c:pnp_alloc_card
  - drivers/pnp/card.c:pnp_alloc_card
```
```
In drivers/pnp/driver.c (ffffffff818a395e)
Location: include/linux/ctype.h:49
Inline: True
Inline callers:
  - drivers/pnp/driver.c:pnp_add_id
  - drivers/pnp/driver.c:pnp_add_id
  - drivers/pnp/driver.c:pnp_add_id
  - drivers/pnp/driver.c:pnp_add_id
```
```
In drivers/tty/n_tty.c (ffffffff818f8aeb)
Location: include/linux/ctype.h:49
Inline: True
Inline callers:
  - drivers/tty/n_tty.c:__receive_buf
  - drivers/tty/n_tty.c:n_tty_receive_buf_standard
  - drivers/tty/n_tty.c:n_tty_receive_buf_standard
```
```
In drivers/power/supply/power_supply_sysfs.c (ffffffff81b41a15)
Location: include/linux/ctype.h:49
Inline: True
Inline callers:
  - drivers/power/supply/power_supply_sysfs.c:power_supply_init_attrs
```
**Symbols:**

```
ffffffff8187ecb7-ffffffff8187ecd2: __tolower (STB_LOCAL)
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
In kernel/kallsyms.c (ffffffff811fb433)
Location: include/linux/ctype.h:49
Inline: True
Inline callers:
  - kernel/kallsyms.c:s_show
```
```
In kernel/debug/kdb/kdb_support.c (ffffffff8124510b)
Location: include/linux/ctype.h:49
Inline: True
```
```
In mm/vmscan.c (ffffffff8137c4c0)
Location: include/linux/ctype.h:49
Inline: True
Inline callers:
  - mm/vmscan.c:store_enabled
```
```
In mm/slub.c (ffffffff81423969)
Location: include/linux/ctype.h:49
Inline: True
Inline callers:
  - mm/slub.c:parse_slub_debug_flags
```
```
In fs/efivarfs/super.c (ffffffff8163a55a)
Location: include/linux/ctype.h:49
Inline: True
Inline callers:
  - fs/efivarfs/super.c:efivarfs_d_hash
```
```
In drivers/acpi/device_sysfs.c (ffffffff81959023)
Location: include/linux/ctype.h:49
Inline: True
Inline callers:
  - drivers/acpi/device_sysfs.c:create_of_modalias
```
```
In drivers/acpi/acpica/utnonansi.c (ffffffff819c2b68)
Location: include/linux/ctype.h:49
Inline: True
Inline callers:
  - drivers/acpi/acpica/utnonansi.c:acpi_ut_stricmp
  - drivers/acpi/acpica/utnonansi.c:acpi_ut_stricmp
  - drivers/acpi/acpica/utnonansi.c:acpi_ut_strlwr
```
```
In drivers/acpi/acpica/utstrsuppt.c (ffffffff819c57fe)
Location: include/linux/ctype.h:49
Inline: True
Inline callers:
  - drivers/acpi/acpica/utstrsuppt.c:acpi_ut_detect_hex_prefix
```
```
In drivers/acpi/acpica/dbinput.c (ffffffff819cb14a)
Location: include/linux/ctype.h:49
Inline: True
Inline callers:
  - drivers/acpi/acpica/dbinput.c:acpi_db_display_command_info
  - drivers/acpi/acpica/dbinput.c:acpi_db_display_command_info
```
```
In drivers/pnp/card.c (ffffffff819ec6a4)
Location: include/linux/ctype.h:49
Inline: True
Inline callers:
  - drivers/pnp/card.c:pnp_alloc_card
  - drivers/pnp/card.c:pnp_alloc_card
  - drivers/pnp/card.c:pnp_alloc_card
  - drivers/pnp/card.c:pnp_alloc_card
```
```
In drivers/pnp/driver.c (ffffffff819ed39e)
Location: include/linux/ctype.h:49
Inline: True
Inline callers:
  - drivers/pnp/driver.c:pnp_add_id
  - drivers/pnp/driver.c:pnp_add_id
  - drivers/pnp/driver.c:pnp_add_id
  - drivers/pnp/driver.c:pnp_add_id
```
```
In drivers/tty/n_tty.c (ffffffff81a514c3)
Location: include/linux/ctype.h:49
Inline: True
Inline callers:
  - drivers/tty/n_tty.c:n_tty_receive_buf_standard
  - drivers/tty/n_tty.c:n_tty_receive_buf_standard
  - drivers/tty/n_tty.c:n_tty_receive_buf_closing
```
```
In drivers/power/supply/power_supply_sysfs.c (ffffffff81cd8055)
Location: include/linux/ctype.h:49
Inline: True
Inline callers:
  - drivers/power/supply/power_supply_sysfs.c:power_supply_init_attrs
```
```
In lib/string.c (ffffffff8203e8bf)
Location: include/linux/ctype.h:49
Inline: True
Inline callers:
  - lib/string.c:strcasecmp
  - lib/string.c:strcasecmp
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
In kernel/kallsyms.c (ffffffff8121098e)
Location: include/linux/ctype.h:49
Inline: True
Inline callers:
  - kernel/kallsyms.c:s_show
```
```
In kernel/debug/kdb/kdb_support.c (ffffffff8125c19b)
Location: include/linux/ctype.h:49
Inline: True
```
```
In mm/vmscan.c (ffffffff813ab866)
Location: include/linux/ctype.h:49
Inline: True
Inline callers:
  - mm/vmscan.c:enabled_store
```
```
In mm/slub.c (ffffffff81458c6f)
Location: include/linux/ctype.h:49
Inline: True
Inline callers:
  - mm/slub.c:parse_slub_debug_flags
```
```
In fs/efivarfs/super.c (ffffffff816729ba)
Location: include/linux/ctype.h:49
Inline: True
Inline callers:
  - fs/efivarfs/super.c:efivarfs_d_hash
```
```
In drivers/acpi/device_sysfs.c (ffffffff8199f493)
Location: include/linux/ctype.h:49
Inline: True
Inline callers:
  - drivers/acpi/device_sysfs.c:create_of_modalias
```
```
In drivers/acpi/acpica/utnonansi.c (ffffffff81a09eb8)
Location: include/linux/ctype.h:49
Inline: True
Inline callers:
  - drivers/acpi/acpica/utnonansi.c:acpi_ut_stricmp
  - drivers/acpi/acpica/utnonansi.c:acpi_ut_stricmp
  - drivers/acpi/acpica/utnonansi.c:acpi_ut_strlwr
```
```
In drivers/acpi/acpica/utstrsuppt.c (ffffffff81a0cbfe)
Location: include/linux/ctype.h:49
Inline: True
Inline callers:
  - drivers/acpi/acpica/utstrsuppt.c:acpi_ut_detect_hex_prefix
```
```
In drivers/acpi/acpica/dbinput.c (ffffffff81a125ba)
Location: include/linux/ctype.h:49
Inline: True
Inline callers:
  - drivers/acpi/acpica/dbinput.c:acpi_db_display_command_info
  - drivers/acpi/acpica/dbinput.c:acpi_db_display_command_info
```
```
In drivers/pnp/card.c (ffffffff81a34e24)
Location: include/linux/ctype.h:49
Inline: True
Inline callers:
  - drivers/pnp/card.c:pnp_alloc_card
  - drivers/pnp/card.c:pnp_alloc_card
  - drivers/pnp/card.c:pnp_alloc_card
  - drivers/pnp/card.c:pnp_alloc_card
```
```
In drivers/pnp/driver.c (ffffffff81a35b1e)
Location: include/linux/ctype.h:49
Inline: True
Inline callers:
  - drivers/pnp/driver.c:pnp_add_id
  - drivers/pnp/driver.c:pnp_add_id
  - drivers/pnp/driver.c:pnp_add_id
  - drivers/pnp/driver.c:pnp_add_id
```
```
In drivers/tty/n_tty.c (ffffffff81a9b793)
Location: include/linux/ctype.h:49
Inline: True
Inline callers:
  - drivers/tty/n_tty.c:n_tty_receive_buf_standard
  - drivers/tty/n_tty.c:n_tty_receive_buf_standard
  - drivers/tty/n_tty.c:n_tty_receive_buf_closing
```
```
In drivers/power/supply/power_supply_sysfs.c (ffffffff81d401a5)
Location: include/linux/ctype.h:49
Inline: True
Inline callers:
  - drivers/power/supply/power_supply_sysfs.c:power_supply_init_attrs
```
```
In lib/string.c (ffffffff820bcdbf)
Location: include/linux/ctype.h:49
Inline: True
Inline callers:
  - lib/string.c:strcasecmp
  - lib/string.c:strcasecmp
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
In kernel/kallsyms.c (ffffffff8122800e)
Location: include/linux/ctype.h:49
Inline: True
Inline callers:
  - kernel/kallsyms.c:s_show
```
```
In kernel/debug/kdb/kdb_support.c (ffffffff812760dd)
Location: include/linux/ctype.h:49
Inline: True
```
```
In mm/vmscan.c (ffffffff813d50f6)
Location: include/linux/ctype.h:49
Inline: True
Inline callers:
  - mm/vmscan.c:enabled_store
```
```
In mm/slub.c (ffffffff81453c2f)
Location: include/linux/ctype.h:49
Inline: True
Inline callers:
  - mm/slub.c:parse_slub_debug_flags
```
```
In fs/efivarfs/super.c (ffffffff816aea3a)
Location: include/linux/ctype.h:49
Inline: True
Inline callers:
  - fs/efivarfs/super.c:efivarfs_d_hash
```
```
In drivers/acpi/device_sysfs.c (ffffffff819e7b32)
Location: include/linux/ctype.h:49
Inline: True
Inline callers:
  - drivers/acpi/device_sysfs.c:create_of_modalias
```
```
In drivers/acpi/acpica/utnonansi.c (ffffffff81a54e58)
Location: include/linux/ctype.h:49
Inline: True
Inline callers:
  - drivers/acpi/acpica/utnonansi.c:acpi_ut_stricmp
  - drivers/acpi/acpica/utnonansi.c:acpi_ut_stricmp
  - drivers/acpi/acpica/utnonansi.c:acpi_ut_strlwr
```
```
In drivers/acpi/acpica/utstrsuppt.c (ffffffff81a57bce)
Location: include/linux/ctype.h:49
Inline: True
Inline callers:
  - drivers/acpi/acpica/utstrsuppt.c:acpi_ut_detect_hex_prefix
```
```
In drivers/acpi/acpica/dbinput.c (ffffffff81a5d74a)
Location: include/linux/ctype.h:49
Inline: True
Inline callers:
  - drivers/acpi/acpica/dbinput.c:acpi_db_display_command_info
  - drivers/acpi/acpica/dbinput.c:acpi_db_display_command_info
```
```
In drivers/pnp/card.c (ffffffff81a80352)
Location: include/linux/ctype.h:49
Inline: True
Inline callers:
  - drivers/pnp/card.c:pnp_alloc_card
  - drivers/pnp/card.c:pnp_alloc_card
  - drivers/pnp/card.c:pnp_alloc_card
  - drivers/pnp/card.c:pnp_alloc_card
```
```
In drivers/pnp/driver.c (ffffffff81a8107d)
Location: include/linux/ctype.h:49
Inline: True
Inline callers:
  - drivers/pnp/driver.c:pnp_add_id
  - drivers/pnp/driver.c:pnp_add_id
  - drivers/pnp/driver.c:pnp_add_id
  - drivers/pnp/driver.c:pnp_add_id
```
```
In drivers/tty/n_tty.c (ffffffff81aee2e2)
Location: include/linux/ctype.h:49
Inline: True
Inline callers:
  - drivers/tty/n_tty.c:n_tty_receive_buf_standard
  - drivers/tty/n_tty.c:n_tty_receive_buf_standard
  - drivers/tty/n_tty.c:n_tty_receive_buf_closing
```
```
In drivers/power/supply/power_supply_sysfs.c (ffffffff81df6b57)
Location: include/linux/ctype.h:49
Inline: True
Inline callers:
  - drivers/power/supply/power_supply_sysfs.c:power_supply_init_attrs
```
```
In lib/string.c (ffffffff821976bf)
Location: include/linux/ctype.h:49
Inline: True
Inline callers:
  - lib/string.c:strcasecmp
  - lib/string.c:strcasecmp
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
In kernel/kallsyms.c (ffff8000101c68ac)
Location: include/linux/ctype.h:42
Inline: True
Inline callers:
  - kernel/kallsyms.c:s_show
```
```
In mm/slub.c (ffff80001145a9f4)
Location: include/linux/ctype.h:42
Inline: True
Inline callers:
  - mm/slub.c:setup_slub_debug
```
```
In fs/efivarfs/super.c (ffff80001051c364)
Location: include/linux/ctype.h:42
Inline: True
Inline callers:
  - fs/efivarfs/super.c:efivarfs_d_hash
```
```
In lib/hexdump.c (ffff800010639950)
Location: include/linux/ctype.h:42
Inline: True
```
```
In drivers/acpi/device_sysfs.c (ffff800010766908)
Location: include/linux/ctype.h:42
Inline: True
```
```
In drivers/acpi/acpica/utnonansi.c (ffff80001079d29c)
Location: include/linux/ctype.h:42
Inline: True
Inline callers:
  - drivers/acpi/acpica/utnonansi.c:acpi_ut_stricmp
  - drivers/acpi/acpica/utnonansi.c:acpi_ut_stricmp
  - drivers/acpi/acpica/utnonansi.c:acpi_ut_strlwr
```
```
In drivers/acpi/acpica/utstrsuppt.c (ffff80001079ed08)
Location: include/linux/ctype.h:42
Inline: True
Inline callers:
  - drivers/acpi/acpica/utstrsuppt.c:acpi_ut_remove_hex_prefix
```
```
In drivers/pnp/card.c (ffff8000107b394c)
Location: include/linux/ctype.h:42
Inline: True
Inline callers:
  - drivers/pnp/card.c:pnp_alloc_card
  - drivers/pnp/card.c:pnp_alloc_card
  - drivers/pnp/card.c:pnp_alloc_card
  - drivers/pnp/card.c:pnp_alloc_card
```
```
In drivers/pnp/driver.c (ffff8000107b4478)
Location: include/linux/ctype.h:42
Inline: True
Inline callers:
  - drivers/pnp/driver.c:pnp_add_id
  - drivers/pnp/driver.c:pnp_add_id
  - drivers/pnp/driver.c:pnp_add_id
  - drivers/pnp/driver.c:pnp_add_id
```
```
In drivers/tty/n_tty.c (ffff800010858180)
Location: include/linux/ctype.h:42
Inline: True
Inline callers:
  - drivers/tty/n_tty.c:n_tty_receive_buf_common
  - drivers/tty/n_tty.c:n_tty_receive_buf_common
  - drivers/tty/n_tty.c:n_tty_receive_char_lnext
```
```
In drivers/perf/arm-ccn.c (ffff800010b923a4)
Location: include/linux/ctype.h:42
Inline: True
Inline callers:
  - drivers/perf/arm-ccn.c:arm_ccn_pmu_get_cmp_mask
```
```
In lib/string.c (ffff800010d92964)
Location: include/linux/ctype.h:42
Inline: True
Inline callers:
  - lib/string.c:strcasecmp
  - lib/string.c:strcasecmp
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
In kernel/kallsyms.c (c040d7fc)
Location: include/linux/ctype.h:42
Inline: True
Inline callers:
  - kernel/kallsyms.c:s_show
```
```
In mm/slub.c (c1533644)
Location: include/linux/ctype.h:42
Inline: True
Inline callers:
  - mm/slub.c:setup_slub_debug
```
```
In fs/efivarfs/super.c (c06d8a54)
Location: include/linux/ctype.h:42
Inline: True
Inline callers:
  - fs/efivarfs/super.c:efivarfs_d_hash
```
```
In lib/hexdump.c (c07df328)
Location: include/linux/ctype.h:42
Inline: True
```
```
In drivers/tty/n_tty.c (c0961efc)
Location: include/linux/ctype.h:42
Inline: True
Inline callers:
  - drivers/tty/n_tty.c:n_tty_receive_buf_common
  - drivers/tty/n_tty.c:n_tty_receive_buf_common
  - drivers/tty/n_tty.c:n_tty_receive_char_lnext
```
```
In drivers/perf/arm-ccn.c (c0c7c4fc)
Location: include/linux/ctype.h:42
Inline: True
Inline callers:
  - drivers/perf/arm-ccn.c:arm_ccn_pmu_get_cmp_mask
```
```
In sound/soc/fsl/fsl_ssi.c (c0cc09f4)
Location: include/linux/ctype.h:42
Inline: True
Inline callers:
  - sound/soc/fsl/fsl_ssi.c:fsl_ssi_probe
```
```
In lib/string.c (c0e8eff0)
Location: include/linux/ctype.h:42
Inline: True
Inline callers:
  - lib/string.c:strcasecmp
  - lib/string.c:strcasecmp
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
In kernel/kallsyms.c (c00000000022e6a0)
Location: include/linux/ctype.h:42
Inline: True
Inline callers:
  - kernel/kallsyms.c:s_show
```
```
In mm/slub.c (c000000001384b60)
Location: include/linux/ctype.h:42
Inline: True
Inline callers:
  - mm/slub.c:setup_slub_debug
```
```
In lib/hexdump.c (c0000000007e0548)
Location: include/linux/ctype.h:42
Inline: True
```
```
In drivers/tty/n_tty.c (c0000000008f7248)
Location: include/linux/ctype.h:42
Inline: True
Inline callers:
  - drivers/tty/n_tty.c:n_tty_receive_buf_common
  - drivers/tty/n_tty.c:n_tty_receive_buf_common
  - drivers/tty/n_tty.c:n_tty_receive_char_lnext
```
```
In lib/string.c (c000000000ed6788)
Location: include/linux/ctype.h:42
Inline: True
Inline callers:
  - lib/string.c:strcasecmp
  - lib/string.c:strcasecmp
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
In kernel/kallsyms.c (ffffffe000146dba)
Location: include/linux/ctype.h:42
Inline: True
Inline callers:
  - kernel/kallsyms.c:s_show
```
```
In mm/slub.c (ffffffe000018b02)
Location: include/linux/ctype.h:42
Inline: True
Inline callers:
  - mm/slub.c:setup_slub_debug
```
```
In lib/hexdump.c (ffffffe00046643c)
Location: include/linux/ctype.h:42
Inline: True
```
```
In drivers/tty/n_tty.c (ffffffe000532d10)
Location: include/linux/ctype.h:42
Inline: True
Inline callers:
  - drivers/tty/n_tty.c:n_tty_receive_buf_common
  - drivers/tty/n_tty.c:n_tty_receive_buf_common
  - drivers/tty/n_tty.c:n_tty_receive_char_lnext
```
```
In lib/string.c (ffffffe0008bc912)
Location: include/linux/ctype.h:42
Inline: True
Inline callers:
  - lib/string.c:strcasecmp
  - lib/string.c:strcasecmp
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
In kernel/kallsyms.c (ffffffff8114fb57)
Location: include/linux/ctype.h:42
Inline: True
Inline callers:
  - kernel/kallsyms.c:s_show
```
```
In mm/slub.c (ffffffff828ca6a2)
Location: include/linux/ctype.h:42
Inline: True
Inline callers:
  - mm/slub.c:setup_slub_debug
```
```
In fs/efivarfs/super.c (ffffffff8142e5f4)
Location: include/linux/ctype.h:42
Inline: True
Inline callers:
  - fs/efivarfs/super.c:efivarfs_d_hash
```
```
In lib/hexdump.c (ffffffff81525764)
Location: include/linux/ctype.h:42
Inline: True
Inline callers:
  - lib/hexdump.c:hex2bin
  - lib/hexdump.c:hex2bin
```
```
In drivers/acpi/device_sysfs.c (ffffffff815ccc1f)
Location: include/linux/ctype.h:42
Inline: True
```
```
In drivers/acpi/acpica/utnonansi.c (ffffffff81600207)
Location: include/linux/ctype.h:42
Inline: True
Inline callers:
  - drivers/acpi/acpica/utnonansi.c:acpi_ut_stricmp
  - drivers/acpi/acpica/utnonansi.c:acpi_ut_stricmp
  - drivers/acpi/acpica/utnonansi.c:acpi_ut_strlwr
```
```
In drivers/acpi/acpica/utstrsuppt.c (ffffffff81601668)
Location: include/linux/ctype.h:42
Inline: True
Inline callers:
  - drivers/acpi/acpica/utstrsuppt.c:acpi_ut_remove_hex_prefix
```
```
In drivers/pnp/card.c (ffffffff8160c7e9)
Location: include/linux/ctype.h:42
Inline: True
Inline callers:
  - drivers/pnp/card.c:pnp_alloc_card
  - drivers/pnp/card.c:pnp_alloc_card
  - drivers/pnp/card.c:pnp_alloc_card
  - drivers/pnp/card.c:pnp_alloc_card
```
```
In drivers/pnp/driver.c (ffffffff8160d1d5)
Location: include/linux/ctype.h:42
Inline: True
Inline callers:
  - drivers/pnp/driver.c:pnp_add_id
  - drivers/pnp/driver.c:pnp_add_id
  - drivers/pnp/driver.c:pnp_add_id
  - drivers/pnp/driver.c:pnp_add_id
```
```
In drivers/tty/n_tty.c (ffffffff8164f81f)
Location: include/linux/ctype.h:42
Inline: True
Inline callers:
  - drivers/tty/n_tty.c:n_tty_receive_buf_common
  - drivers/tty/n_tty.c:n_tty_receive_buf_common
  - drivers/tty/n_tty.c:n_tty_receive_char_lnext
```
```
In lib/string.c (ffffffff81a572ad)
Location: include/linux/ctype.h:42
Inline: True
Inline callers:
  - lib/string.c:strcasecmp
  - lib/string.c:strcasecmp
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
In kernel/kallsyms.c (ffffffff81142e07)
Location: include/linux/ctype.h:42
Inline: True
Inline callers:
  - kernel/kallsyms.c:s_show
```
```
In mm/slub.c (ffffffff828c2dc7)
Location: include/linux/ctype.h:42
Inline: True
Inline callers:
  - mm/slub.c:setup_slub_debug
```
```
In fs/efivarfs/super.c (ffffffff8141f074)
Location: include/linux/ctype.h:42
Inline: True
Inline callers:
  - fs/efivarfs/super.c:efivarfs_d_hash
```
```
In lib/hexdump.c (ffffffff81515a44)
Location: include/linux/ctype.h:42
Inline: True
Inline callers:
  - lib/hexdump.c:hex2bin
  - lib/hexdump.c:hex2bin
```
```
In drivers/acpi/device_sysfs.c (ffffffff815b679f)
Location: include/linux/ctype.h:42
Inline: True
```
```
In drivers/acpi/acpica/utnonansi.c (ffffffff815eb6ef)
Location: include/linux/ctype.h:42
Inline: True
Inline callers:
  - drivers/acpi/acpica/utnonansi.c:acpi_ut_stricmp
  - drivers/acpi/acpica/utnonansi.c:acpi_ut_stricmp
  - drivers/acpi/acpica/utnonansi.c:acpi_ut_strlwr
```
```
In drivers/acpi/acpica/utstrsuppt.c (ffffffff815ecb23)
Location: include/linux/ctype.h:42
Inline: True
Inline callers:
  - drivers/acpi/acpica/utstrsuppt.c:acpi_ut_remove_hex_prefix
```
```
In drivers/pnp/card.c (ffffffff81600d39)
Location: include/linux/ctype.h:42
Inline: True
Inline callers:
  - drivers/pnp/card.c:pnp_alloc_card
  - drivers/pnp/card.c:pnp_alloc_card
  - drivers/pnp/card.c:pnp_alloc_card
  - drivers/pnp/card.c:pnp_alloc_card
```
```
In drivers/pnp/driver.c (ffffffff81601725)
Location: include/linux/ctype.h:42
Inline: True
Inline callers:
  - drivers/pnp/driver.c:pnp_add_id
  - drivers/pnp/driver.c:pnp_add_id
  - drivers/pnp/driver.c:pnp_add_id
  - drivers/pnp/driver.c:pnp_add_id
```
```
In drivers/tty/n_tty.c (ffffffff8162fc6f)
Location: include/linux/ctype.h:42
Inline: True
Inline callers:
  - drivers/tty/n_tty.c:n_tty_receive_buf_common
  - drivers/tty/n_tty.c:n_tty_receive_buf_common
  - drivers/tty/n_tty.c:n_tty_receive_char_lnext
```
```
In lib/string.c (ffffffff81a1438d)
Location: include/linux/ctype.h:42
Inline: True
Inline callers:
  - lib/string.c:strcasecmp
  - lib/string.c:strcasecmp
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
In kernel/kallsyms.c (ffffffff8114da07)
Location: include/linux/ctype.h:42
Inline: True
Inline callers:
  - kernel/kallsyms.c:s_show
```
```
In mm/slub.c (ffffffff828dd422)
Location: include/linux/ctype.h:42
Inline: True
Inline callers:
  - mm/slub.c:setup_slub_debug
```
```
In fs/efivarfs/super.c (ffffffff8142a794)
Location: include/linux/ctype.h:42
Inline: True
Inline callers:
  - fs/efivarfs/super.c:efivarfs_d_hash
```
```
In lib/hexdump.c (ffffffff815217f4)
Location: include/linux/ctype.h:42
Inline: True
Inline callers:
  - lib/hexdump.c:hex2bin
  - lib/hexdump.c:hex2bin
```
```
In drivers/acpi/device_sysfs.c (ffffffff815ce72f)
Location: include/linux/ctype.h:42
Inline: True
```
```
In drivers/acpi/acpica/utnonansi.c (ffffffff8161c931)
Location: include/linux/ctype.h:42
Inline: True
Inline callers:
  - drivers/acpi/acpica/utnonansi.c:acpi_ut_stricmp
  - drivers/acpi/acpica/utnonansi.c:acpi_ut_stricmp
  - drivers/acpi/acpica/utnonansi.c:acpi_ut_strlwr
```
```
In drivers/acpi/acpica/utstrsuppt.c (ffffffff8161e85e)
Location: include/linux/ctype.h:42
Inline: True
Inline callers:
  - drivers/acpi/acpica/utstrsuppt.c:acpi_ut_remove_hex_prefix
```
```
In drivers/acpi/acpica/dbinput.c (ffffffff8162294c)
Location: include/linux/ctype.h:42
Inline: True
Inline callers:
  - drivers/acpi/acpica/dbinput.c:acpi_db_display_command_info
  - drivers/acpi/acpica/dbinput.c:acpi_db_display_command_info
```
```
In drivers/pnp/card.c (ffffffff8163a5c9)
Location: include/linux/ctype.h:42
Inline: True
Inline callers:
  - drivers/pnp/card.c:pnp_alloc_card
  - drivers/pnp/card.c:pnp_alloc_card
  - drivers/pnp/card.c:pnp_alloc_card
  - drivers/pnp/card.c:pnp_alloc_card
```
```
In drivers/pnp/driver.c (ffffffff8163afb5)
Location: include/linux/ctype.h:42
Inline: True
Inline callers:
  - drivers/pnp/driver.c:pnp_add_id
  - drivers/pnp/driver.c:pnp_add_id
  - drivers/pnp/driver.c:pnp_add_id
  - drivers/pnp/driver.c:pnp_add_id
```
```
In drivers/tty/n_tty.c (ffffffff8167dbdf)
Location: include/linux/ctype.h:42
Inline: True
Inline callers:
  - drivers/tty/n_tty.c:n_tty_receive_buf_common
  - drivers/tty/n_tty.c:n_tty_receive_buf_common
  - drivers/tty/n_tty.c:n_tty_receive_char_lnext
```
```
In lib/string.c (ffffffff81ac369d)
Location: include/linux/ctype.h:42
Inline: True
Inline callers:
  - lib/string.c:strcasecmp
  - lib/string.c:strcasecmp
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
In kernel/kallsyms.c (ffffffff8115a7e7)
Location: include/linux/ctype.h:42
Inline: True
Inline callers:
  - kernel/kallsyms.c:s_show
```
```
In mm/slub.c (ffffffff828e2839)
Location: include/linux/ctype.h:42
Inline: True
Inline callers:
  - mm/slub.c:setup_slub_debug
```
```
In fs/efivarfs/super.c (ffffffff81441654)
Location: include/linux/ctype.h:42
Inline: True
Inline callers:
  - fs/efivarfs/super.c:efivarfs_d_hash
```
```
In lib/hexdump.c (ffffffff8153b174)
Location: include/linux/ctype.h:42
Inline: True
Inline callers:
  - lib/hexdump.c:hex2bin
  - lib/hexdump.c:hex2bin
```
```
In drivers/acpi/device_sysfs.c (ffffffff815e85ef)
Location: include/linux/ctype.h:42
Inline: True
```
```
In drivers/acpi/acpica/utnonansi.c (ffffffff816367e1)
Location: include/linux/ctype.h:42
Inline: True
Inline callers:
  - drivers/acpi/acpica/utnonansi.c:acpi_ut_stricmp
  - drivers/acpi/acpica/utnonansi.c:acpi_ut_stricmp
  - drivers/acpi/acpica/utnonansi.c:acpi_ut_strlwr
```
```
In drivers/acpi/acpica/utstrsuppt.c (ffffffff8163870e)
Location: include/linux/ctype.h:42
Inline: True
Inline callers:
  - drivers/acpi/acpica/utstrsuppt.c:acpi_ut_remove_hex_prefix
```
```
In drivers/acpi/acpica/dbinput.c (ffffffff8163c7fc)
Location: include/linux/ctype.h:42
Inline: True
Inline callers:
  - drivers/acpi/acpica/dbinput.c:acpi_db_display_command_info
  - drivers/acpi/acpica/dbinput.c:acpi_db_display_command_info
```
```
In drivers/pnp/card.c (ffffffff81654919)
Location: include/linux/ctype.h:42
Inline: True
Inline callers:
  - drivers/pnp/card.c:pnp_alloc_card
  - drivers/pnp/card.c:pnp_alloc_card
  - drivers/pnp/card.c:pnp_alloc_card
  - drivers/pnp/card.c:pnp_alloc_card
```
```
In drivers/pnp/driver.c (ffffffff81655305)
Location: include/linux/ctype.h:42
Inline: True
Inline callers:
  - drivers/pnp/driver.c:pnp_add_id
  - drivers/pnp/driver.c:pnp_add_id
  - drivers/pnp/driver.c:pnp_add_id
  - drivers/pnp/driver.c:pnp_add_id
```
```
In drivers/tty/n_tty.c (ffffffff8169823f)
Location: include/linux/ctype.h:42
Inline: True
Inline callers:
  - drivers/tty/n_tty.c:n_tty_receive_buf_common
  - drivers/tty/n_tty.c:n_tty_receive_buf_common
  - drivers/tty/n_tty.c:n_tty_receive_char_lnext
```
```
In lib/string.c (ffffffff81acfb6d)
Location: include/linux/ctype.h:42
Inline: True
Inline callers:
  - lib/string.c:strcasecmp
  - lib/string.c:strcasecmp
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
