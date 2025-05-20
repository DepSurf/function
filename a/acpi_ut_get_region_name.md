# Function: <code>acpi_ut_get_region_name</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
char *acpi_ut_get_region_name(u8 space_id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/utdecode.c (ffffffff814a709e)
Location: drivers/acpi/acpica/utdecode.c:117
Inline: False
Direct callers:
  - drivers/acpi/acpica/evregion.c:acpi_ev_address_space_dispatch
  - drivers/acpi/acpica/evregion.c:acpi_ev_address_space_dispatch
  - drivers/acpi/acpica/evregion.c:acpi_ev_address_space_dispatch
  - drivers/acpi/acpica/evregion.c:acpi_ev_address_space_dispatch
  - drivers/acpi/acpica/evregion.c:acpi_ev_detach_region
  - drivers/acpi/acpica/evregion.c:acpi_ev_detach_region
  - drivers/acpi/acpica/utaddress.c:acpi_ut_check_address_range
```
**Symbols:**

```
ffffffff814a709e-ffffffff814a70e8: acpi_ut_get_region_name (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
const char *acpi_ut_get_region_name(u8 space_id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/utdecode.c (ffffffff814f6421)
Location: drivers/acpi/acpica/utdecode.c:117
Inline: False
Direct callers:
  - drivers/acpi/acpica/evregion.c:acpi_ev_detach_region
  - drivers/acpi/acpica/evregion.c:acpi_ev_detach_region
  - drivers/acpi/acpica/evregion.c:acpi_ev_address_space_dispatch
  - drivers/acpi/acpica/evregion.c:acpi_ev_address_space_dispatch
  - drivers/acpi/acpica/evregion.c:acpi_ev_address_space_dispatch
  - drivers/acpi/acpica/evregion.c:acpi_ev_address_space_dispatch
  - drivers/acpi/acpica/utaddress.c:acpi_ut_check_address_range
```
**Symbols:**

```
ffffffff814f6421-ffffffff814f646b: acpi_ut_get_region_name (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
const char *acpi_ut_get_region_name(u8 space_id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/utdecode.c (ffffffff81518fe4)
Location: drivers/acpi/acpica/utdecode.c:118
Inline: False
Direct callers:
  - drivers/acpi/acpica/evregion.c:acpi_ev_detach_region
  - drivers/acpi/acpica/evregion.c:acpi_ev_detach_region
  - drivers/acpi/acpica/evregion.c:acpi_ev_address_space_dispatch
  - drivers/acpi/acpica/evregion.c:acpi_ev_address_space_dispatch
  - drivers/acpi/acpica/evregion.c:acpi_ev_address_space_dispatch
  - drivers/acpi/acpica/evregion.c:acpi_ev_address_space_dispatch
  - drivers/acpi/acpica/utaddress.c:acpi_ut_check_address_range
```
**Symbols:**

```
ffffffff81518fe4-ffffffff8151902e: acpi_ut_get_region_name (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
const char *acpi_ut_get_region_name(u8 space_id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/utdecode.c (ffffffff815297fa)
Location: drivers/acpi/acpica/utdecode.c:118
Inline: False
Direct callers:
  - drivers/acpi/acpica/evregion.c:acpi_ev_detach_region
  - drivers/acpi/acpica/evregion.c:acpi_ev_detach_region
  - drivers/acpi/acpica/evregion.c:acpi_ev_address_space_dispatch
  - drivers/acpi/acpica/evregion.c:acpi_ev_address_space_dispatch
  - drivers/acpi/acpica/evregion.c:acpi_ev_address_space_dispatch
  - drivers/acpi/acpica/evregion.c:acpi_ev_address_space_dispatch
  - drivers/acpi/acpica/utaddress.c:acpi_ut_check_address_range
```
**Symbols:**

```
ffffffff815297fa-ffffffff81529844: acpi_ut_get_region_name (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
const char *acpi_ut_get_region_name(u8 space_id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/utdecode.c (ffffffff815821e5)
Location: drivers/acpi/acpica/utdecode.c:118
Inline: False
Direct callers:
  - drivers/acpi/acpica/evhandler.c:acpi_ev_install_space_handler
  - drivers/acpi/acpica/evregion.c:acpi_ev_execute_reg_methods
  - drivers/acpi/acpica/evregion.c:acpi_ev_execute_reg_methods
  - drivers/acpi/acpica/evregion.c:acpi_ev_attach_region
  - drivers/acpi/acpica/evregion.c:acpi_ev_detach_region
  - drivers/acpi/acpica/evregion.c:acpi_ev_detach_region
  - drivers/acpi/acpica/evregion.c:acpi_ev_address_space_dispatch
  - drivers/acpi/acpica/evregion.c:acpi_ev_address_space_dispatch
  - drivers/acpi/acpica/evregion.c:acpi_ev_address_space_dispatch
  - drivers/acpi/acpica/evregion.c:acpi_ev_address_space_dispatch
  - drivers/acpi/acpica/evregion.c:acpi_ev_address_space_dispatch
  - drivers/acpi/acpica/evrgnini.c:acpi_ev_initialize_region
  - drivers/acpi/acpica/excreate.c:acpi_ex_create_region
  - drivers/acpi/acpica/exfldio.c:acpi_ex_access_region
  - drivers/acpi/acpica/exfldio.c:acpi_ex_access_region
  - drivers/acpi/acpica/exfldio.c:acpi_ex_access_region
  - drivers/acpi/acpica/hwregs.c:acpi_hw_write
  - drivers/acpi/acpica/hwregs.c:acpi_hw_read
  - drivers/acpi/acpica/utaddress.c:acpi_ut_check_address_range
  - drivers/acpi/acpica/dbdisply.c:acpi_db_display_non_root_handlers
  - drivers/acpi/acpica/dbdisply.c:acpi_db_display_handlers
```
**Symbols:**

```
ffffffff815821e5-ffffffff8158222f: acpi_ut_get_region_name (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
const char *acpi_ut_get_region_name(u8 space_id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/utdecode.c (ffffffff815b939a)
Location: drivers/acpi/acpica/utdecode.c:84
Inline: False
Direct callers:
  - drivers/acpi/acpica/evhandler.c:acpi_ev_install_space_handler
  - drivers/acpi/acpica/evregion.c:acpi_ev_execute_reg_methods
  - drivers/acpi/acpica/evregion.c:acpi_ev_execute_reg_methods
  - drivers/acpi/acpica/evregion.c:acpi_ev_attach_region
  - drivers/acpi/acpica/evregion.c:acpi_ev_detach_region
  - drivers/acpi/acpica/evregion.c:acpi_ev_detach_region
  - drivers/acpi/acpica/evregion.c:acpi_ev_address_space_dispatch
  - drivers/acpi/acpica/evregion.c:acpi_ev_address_space_dispatch
  - drivers/acpi/acpica/evregion.c:acpi_ev_address_space_dispatch
  - drivers/acpi/acpica/evregion.c:acpi_ev_address_space_dispatch
  - drivers/acpi/acpica/evregion.c:acpi_ev_address_space_dispatch
  - drivers/acpi/acpica/evrgnini.c:acpi_ev_initialize_region
  - drivers/acpi/acpica/excreate.c:acpi_ex_create_region
  - drivers/acpi/acpica/exfldio.c:acpi_ex_access_region
  - drivers/acpi/acpica/exfldio.c:acpi_ex_access_region
  - drivers/acpi/acpica/exfldio.c:acpi_ex_access_region
  - drivers/acpi/acpica/hwregs.c:acpi_hw_write
  - drivers/acpi/acpica/hwregs.c:acpi_hw_read
  - drivers/acpi/acpica/utaddress.c:acpi_ut_check_address_range
  - drivers/acpi/acpica/dbdisply.c:acpi_db_display_non_root_handlers
  - drivers/acpi/acpica/dbdisply.c:acpi_db_display_handlers
```
**Symbols:**

```
ffffffff815b939a-ffffffff815b93e4: acpi_ut_get_region_name (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
const char *acpi_ut_get_region_name(u8 space_id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/utdecode.c (ffffffff815d276b)
Location: drivers/acpi/acpica/utdecode.c:84
Inline: False
Direct callers:
  - drivers/acpi/acpica/evhandler.c:acpi_ev_install_space_handler
  - drivers/acpi/acpica/evregion.c:acpi_ev_execute_reg_methods
  - drivers/acpi/acpica/evregion.c:acpi_ev_execute_reg_methods
  - drivers/acpi/acpica/evregion.c:acpi_ev_attach_region
  - drivers/acpi/acpica/evregion.c:acpi_ev_detach_region
  - drivers/acpi/acpica/evregion.c:acpi_ev_detach_region
  - drivers/acpi/acpica/evregion.c:acpi_ev_address_space_dispatch
  - drivers/acpi/acpica/evregion.c:acpi_ev_address_space_dispatch
  - drivers/acpi/acpica/evregion.c:acpi_ev_address_space_dispatch
  - drivers/acpi/acpica/evregion.c:acpi_ev_address_space_dispatch
  - drivers/acpi/acpica/evregion.c:acpi_ev_address_space_dispatch
  - drivers/acpi/acpica/evrgnini.c:acpi_ev_initialize_region
  - drivers/acpi/acpica/excreate.c:acpi_ex_create_region
  - drivers/acpi/acpica/exfldio.c:acpi_ex_access_region
  - drivers/acpi/acpica/exfldio.c:acpi_ex_access_region
  - drivers/acpi/acpica/exfldio.c:acpi_ex_access_region
  - drivers/acpi/acpica/hwregs.c:acpi_hw_write
  - drivers/acpi/acpica/hwregs.c:acpi_hw_read
  - drivers/acpi/acpica/utaddress.c:acpi_ut_check_address_range
  - drivers/acpi/acpica/dbdisply.c:acpi_db_display_non_root_handlers
  - drivers/acpi/acpica/dbdisply.c:acpi_db_display_handlers
```
**Symbols:**

```
ffffffff815d276b-ffffffff815d27b5: acpi_ut_get_region_name (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
const char *acpi_ut_get_region_name(u8 space_id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/utdecode.c (ffffffff81604069)
Location: drivers/acpi/acpica/utdecode.c:84
Inline: False
Direct callers:
  - drivers/acpi/acpica/evhandler.c:acpi_ev_install_space_handler
  - drivers/acpi/acpica/evregion.c:acpi_ev_execute_reg_methods
  - drivers/acpi/acpica/evregion.c:acpi_ev_execute_reg_methods
  - drivers/acpi/acpica/evregion.c:acpi_ev_attach_region
  - drivers/acpi/acpica/evregion.c:acpi_ev_detach_region
  - drivers/acpi/acpica/evregion.c:acpi_ev_detach_region
  - drivers/acpi/acpica/evregion.c:acpi_ev_address_space_dispatch
  - drivers/acpi/acpica/evregion.c:acpi_ev_address_space_dispatch
  - drivers/acpi/acpica/evregion.c:acpi_ev_address_space_dispatch
  - drivers/acpi/acpica/evregion.c:acpi_ev_address_space_dispatch
  - drivers/acpi/acpica/evregion.c:acpi_ev_address_space_dispatch
  - drivers/acpi/acpica/evrgnini.c:acpi_ev_initialize_region
  - drivers/acpi/acpica/excreate.c:acpi_ex_create_region
  - drivers/acpi/acpica/exfldio.c:acpi_ex_access_region
  - drivers/acpi/acpica/exfldio.c:acpi_ex_access_region
  - drivers/acpi/acpica/exfldio.c:acpi_ex_access_region
  - drivers/acpi/acpica/hwregs.c:acpi_hw_write
  - drivers/acpi/acpica/hwregs.c:acpi_hw_read
  - drivers/acpi/acpica/utaddress.c:acpi_ut_check_address_range
  - drivers/acpi/acpica/dbdisply.c:acpi_db_display_non_root_handlers
  - drivers/acpi/acpica/dbdisply.c:acpi_db_display_handlers
```
**Symbols:**

```
ffffffff81604069-ffffffff816040b3: acpi_ut_get_region_name (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
const char *acpi_ut_get_region_name(u8 space_id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/utdecode.c (ffffffff81625513)
Location: drivers/acpi/acpica/utdecode.c:84
Inline: False
Direct callers:
  - drivers/acpi/acpica/evhandler.c:acpi_ev_install_space_handler
  - drivers/acpi/acpica/evregion.c:acpi_ev_execute_reg_methods
  - drivers/acpi/acpica/evregion.c:acpi_ev_execute_reg_methods
  - drivers/acpi/acpica/evregion.c:acpi_ev_attach_region
  - drivers/acpi/acpica/evregion.c:acpi_ev_detach_region
  - drivers/acpi/acpica/evregion.c:acpi_ev_detach_region
  - drivers/acpi/acpica/evregion.c:acpi_ev_address_space_dispatch
  - drivers/acpi/acpica/evregion.c:acpi_ev_address_space_dispatch
  - drivers/acpi/acpica/evregion.c:acpi_ev_address_space_dispatch
  - drivers/acpi/acpica/evregion.c:acpi_ev_address_space_dispatch
  - drivers/acpi/acpica/evregion.c:acpi_ev_address_space_dispatch
  - drivers/acpi/acpica/evrgnini.c:acpi_ev_initialize_region
  - drivers/acpi/acpica/excreate.c:acpi_ex_create_region
  - drivers/acpi/acpica/exfldio.c:acpi_ex_access_region
  - drivers/acpi/acpica/exfldio.c:acpi_ex_access_region
  - drivers/acpi/acpica/exfldio.c:acpi_ex_access_region
  - drivers/acpi/acpica/hwregs.c:acpi_hw_write
  - drivers/acpi/acpica/hwregs.c:acpi_hw_read
  - drivers/acpi/acpica/utaddress.c:acpi_ut_check_address_range
  - drivers/acpi/acpica/dbdisply.c:acpi_db_display_non_root_handlers
  - drivers/acpi/acpica/dbdisply.c:acpi_db_display_handlers
```
**Symbols:**

```
ffffffff81625513-ffffffff8162555d: acpi_ut_get_region_name (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
const char *acpi_ut_get_region_name(u8 space_id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/utdecode.c (ffffffff816d1cb9)
Location: drivers/acpi/acpica/utdecode.c:85
Inline: False
Direct callers:
  - drivers/acpi/acpica/evhandler.c:acpi_ev_install_space_handler
  - drivers/acpi/acpica/evregion.c:acpi_ev_execute_reg_methods
  - drivers/acpi/acpica/evregion.c:acpi_ev_execute_reg_methods
  - drivers/acpi/acpica/evregion.c:acpi_ev_attach_region
  - drivers/acpi/acpica/evregion.c:acpi_ev_detach_region
  - drivers/acpi/acpica/evregion.c:acpi_ev_detach_region
  - drivers/acpi/acpica/evregion.c:acpi_ev_address_space_dispatch
  - drivers/acpi/acpica/evregion.c:acpi_ev_address_space_dispatch
  - drivers/acpi/acpica/evregion.c:acpi_ev_address_space_dispatch
  - drivers/acpi/acpica/evregion.c:acpi_ev_address_space_dispatch
  - drivers/acpi/acpica/evregion.c:acpi_ev_address_space_dispatch
  - drivers/acpi/acpica/evrgnini.c:acpi_ev_initialize_region
  - drivers/acpi/acpica/evxfregn.c:acpi_remove_address_space_handler
  - drivers/acpi/acpica/evxfregn.c:acpi_remove_address_space_handler
  - drivers/acpi/acpica/excreate.c:acpi_ex_create_region
  - drivers/acpi/acpica/exfldio.c:acpi_ex_access_region
  - drivers/acpi/acpica/exfldio.c:acpi_ex_access_region
  - drivers/acpi/acpica/exfldio.c:acpi_ex_access_region
  - drivers/acpi/acpica/hwregs.c:acpi_hw_write
  - drivers/acpi/acpica/hwregs.c:acpi_hw_read
  - drivers/acpi/acpica/nsdump.c:acpi_ns_dump_one_object
  - drivers/acpi/acpica/utaddress.c:acpi_ut_check_address_range
  - drivers/acpi/acpica/dbdisply.c:acpi_db_display_non_root_handlers
  - drivers/acpi/acpica/dbdisply.c:acpi_db_display_handlers
```
**Symbols:**

```
ffffffff816d1cb9-ffffffff816d1d03: acpi_ut_get_region_name (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
const char *acpi_ut_get_region_name(u8 space_id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/utdecode.c (ffffffff816efc97)
Location: drivers/acpi/acpica/utdecode.c:85
Inline: False
Direct callers:
  - drivers/acpi/acpica/evhandler.c:acpi_ev_install_space_handler
  - drivers/acpi/acpica/evregion.c:acpi_ev_execute_reg_methods
  - drivers/acpi/acpica/evregion.c:acpi_ev_execute_reg_methods
  - drivers/acpi/acpica/evregion.c:acpi_ev_attach_region
  - drivers/acpi/acpica/evregion.c:acpi_ev_detach_region
  - drivers/acpi/acpica/evregion.c:acpi_ev_detach_region
  - drivers/acpi/acpica/evregion.c:acpi_ev_address_space_dispatch
  - drivers/acpi/acpica/evregion.c:acpi_ev_address_space_dispatch
  - drivers/acpi/acpica/evregion.c:acpi_ev_address_space_dispatch
  - drivers/acpi/acpica/evregion.c:acpi_ev_address_space_dispatch
  - drivers/acpi/acpica/evregion.c:acpi_ev_address_space_dispatch
  - drivers/acpi/acpica/evrgnini.c:acpi_ev_initialize_region
  - drivers/acpi/acpica/evxfregn.c:acpi_remove_address_space_handler
  - drivers/acpi/acpica/evxfregn.c:acpi_remove_address_space_handler
  - drivers/acpi/acpica/excreate.c:acpi_ex_create_region
  - drivers/acpi/acpica/exfldio.c:acpi_ex_access_region
  - drivers/acpi/acpica/exfldio.c:acpi_ex_access_region
  - drivers/acpi/acpica/exfldio.c:acpi_ex_access_region
  - drivers/acpi/acpica/hwregs.c:acpi_hw_write
  - drivers/acpi/acpica/hwregs.c:acpi_hw_read
  - drivers/acpi/acpica/nsdump.c:acpi_ns_dump_one_object
  - drivers/acpi/acpica/utaddress.c:acpi_ut_check_address_range
  - drivers/acpi/acpica/dbdisply.c:acpi_db_display_non_root_handlers
  - drivers/acpi/acpica/dbdisply.c:acpi_db_display_handlers
```
**Symbols:**

```
ffffffff816efc97-ffffffff816efce1: acpi_ut_get_region_name (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
const char *acpi_ut_get_region_name(u8 space_id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/utdecode.c (ffffffff816d1afc)
Location: drivers/acpi/acpica/utdecode.c:85
Inline: False
Direct callers:
  - drivers/acpi/acpica/evhandler.c:acpi_ev_install_space_handler
  - drivers/acpi/acpica/evregion.c:acpi_ev_execute_reg_methods
  - drivers/acpi/acpica/evregion.c:acpi_ev_execute_reg_methods
  - drivers/acpi/acpica/evregion.c:acpi_ev_attach_region
  - drivers/acpi/acpica/evregion.c:acpi_ev_detach_region
  - drivers/acpi/acpica/evregion.c:acpi_ev_detach_region
  - drivers/acpi/acpica/evregion.c:acpi_ev_address_space_dispatch
  - drivers/acpi/acpica/evregion.c:acpi_ev_address_space_dispatch
  - drivers/acpi/acpica/evregion.c:acpi_ev_address_space_dispatch
  - drivers/acpi/acpica/evregion.c:acpi_ev_address_space_dispatch
  - drivers/acpi/acpica/evregion.c:acpi_ev_address_space_dispatch
  - drivers/acpi/acpica/evrgnini.c:acpi_ev_initialize_region
  - drivers/acpi/acpica/evxfregn.c:acpi_remove_address_space_handler
  - drivers/acpi/acpica/evxfregn.c:acpi_remove_address_space_handler
  - drivers/acpi/acpica/excreate.c:acpi_ex_create_region
  - drivers/acpi/acpica/exfldio.c:acpi_ex_access_region
  - drivers/acpi/acpica/exfldio.c:acpi_ex_access_region
  - drivers/acpi/acpica/exfldio.c:acpi_ex_access_region
  - drivers/acpi/acpica/hwregs.c:acpi_hw_write
  - drivers/acpi/acpica/hwregs.c:acpi_hw_read
  - drivers/acpi/acpica/nsdump.c:acpi_ns_dump_one_object
  - drivers/acpi/acpica/utaddress.c:acpi_ut_check_address_range
  - drivers/acpi/acpica/dbdisply.c:acpi_db_display_non_root_handlers
  - drivers/acpi/acpica/dbdisply.c:acpi_db_display_handlers
```
**Symbols:**

```
ffffffff816d1afc-ffffffff816d1b46: acpi_ut_get_region_name (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
const char *acpi_ut_get_region_name(u8 space_id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/utdecode.c (ffffffff81749256)
Location: drivers/acpi/acpica/utdecode.c:85
Inline: False
Direct callers:
  - drivers/acpi/acpica/evhandler.c:acpi_ev_install_space_handler
  - drivers/acpi/acpica/evregion.c:acpi_ev_execute_reg_methods
  - drivers/acpi/acpica/evregion.c:acpi_ev_execute_reg_methods
  - drivers/acpi/acpica/evregion.c:acpi_ev_attach_region
  - drivers/acpi/acpica/evregion.c:acpi_ev_detach_region
  - drivers/acpi/acpica/evregion.c:acpi_ev_detach_region
  - drivers/acpi/acpica/evregion.c:acpi_ev_address_space_dispatch
  - drivers/acpi/acpica/evregion.c:acpi_ev_address_space_dispatch
  - drivers/acpi/acpica/evregion.c:acpi_ev_address_space_dispatch
  - drivers/acpi/acpica/evregion.c:acpi_ev_address_space_dispatch
  - drivers/acpi/acpica/evregion.c:acpi_ev_address_space_dispatch
  - drivers/acpi/acpica/evrgnini.c:acpi_ev_initialize_region
  - drivers/acpi/acpica/evxfregn.c:acpi_remove_address_space_handler
  - drivers/acpi/acpica/evxfregn.c:acpi_remove_address_space_handler
  - drivers/acpi/acpica/excreate.c:acpi_ex_create_region
  - drivers/acpi/acpica/exfldio.c:acpi_ex_access_region
  - drivers/acpi/acpica/exfldio.c:acpi_ex_access_region
  - drivers/acpi/acpica/exfldio.c:acpi_ex_access_region
  - drivers/acpi/acpica/hwregs.c:acpi_hw_write
  - drivers/acpi/acpica/hwregs.c:acpi_hw_read
  - drivers/acpi/acpica/nsdump.c:acpi_ns_dump_one_object
  - drivers/acpi/acpica/utaddress.c:acpi_ut_check_address_range
  - drivers/acpi/acpica/dbdisply.c:acpi_db_display_non_root_handlers
  - drivers/acpi/acpica/dbdisply.c:acpi_db_display_handlers
```
**Symbols:**

```
ffffffff81749256-ffffffff817492b4: acpi_ut_get_region_name (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
const char *acpi_ut_get_region_name(u8 space_id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/utdecode.c (ffffffff8187b573)
Location: drivers/acpi/acpica/utdecode.c:85
Inline: False
Direct callers:
  - drivers/acpi/acpica/evhandler.c:acpi_ev_install_space_handler
  - drivers/acpi/acpica/evhandler.c:acpi_ev_install_handler
  - drivers/acpi/acpica/evregion.c:acpi_ev_execute_reg_methods
  - drivers/acpi/acpica/evregion.c:acpi_ev_execute_reg_methods
  - drivers/acpi/acpica/evregion.c:acpi_ev_attach_region
  - drivers/acpi/acpica/evregion.c:acpi_ev_detach_region
  - drivers/acpi/acpica/evregion.c:acpi_ev_detach_region
  - drivers/acpi/acpica/evregion.c:acpi_ev_address_space_dispatch
  - drivers/acpi/acpica/evregion.c:acpi_ev_address_space_dispatch
  - drivers/acpi/acpica/evregion.c:acpi_ev_address_space_dispatch
  - drivers/acpi/acpica/evregion.c:acpi_ev_address_space_dispatch
  - drivers/acpi/acpica/evregion.c:acpi_ev_address_space_dispatch
  - drivers/acpi/acpica/evrgnini.c:acpi_ev_initialize_region
  - drivers/acpi/acpica/evxfregn.c:acpi_remove_address_space_handler
  - drivers/acpi/acpica/evxfregn.c:acpi_remove_address_space_handler
  - drivers/acpi/acpica/excreate.c:acpi_ex_create_region
  - drivers/acpi/acpica/exfldio.c:acpi_ex_access_region
  - drivers/acpi/acpica/exfldio.c:acpi_ex_access_region
  - drivers/acpi/acpica/exfldio.c:acpi_ex_access_region
  - drivers/acpi/acpica/hwregs.c:acpi_hw_write
  - drivers/acpi/acpica/hwregs.c:acpi_hw_read
  - drivers/acpi/acpica/nsdump.c:acpi_ns_dump_one_object
  - drivers/acpi/acpica/utaddress.c:acpi_ut_check_address_range
  - drivers/acpi/acpica/dbdisply.c:acpi_db_display_non_root_handlers
  - drivers/acpi/acpica/dbdisply.c:acpi_db_display_handlers
```
**Symbols:**

```
ffffffff8187b573-ffffffff8187b5e1: acpi_ut_get_region_name (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
const char *acpi_ut_get_region_name(u8 space_id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/utdecode.c (ffffffff819be630)
Location: drivers/acpi/acpica/utdecode.c:85
Inline: False
Direct callers:
  - drivers/acpi/acpica/evhandler.c:acpi_ev_install_space_handler
  - drivers/acpi/acpica/evhandler.c:acpi_ev_install_handler
  - drivers/acpi/acpica/evregion.c:acpi_ev_execute_reg_methods
  - drivers/acpi/acpica/evregion.c:acpi_ev_execute_reg_methods
  - drivers/acpi/acpica/evregion.c:acpi_ev_attach_region
  - drivers/acpi/acpica/evregion.c:acpi_ev_detach_region
  - drivers/acpi/acpica/evregion.c:acpi_ev_detach_region
  - drivers/acpi/acpica/evregion.c:acpi_ev_detach_region
  - drivers/acpi/acpica/evregion.c:acpi_ev_address_space_dispatch
  - drivers/acpi/acpica/evregion.c:acpi_ev_address_space_dispatch
  - drivers/acpi/acpica/evregion.c:acpi_ev_address_space_dispatch
  - drivers/acpi/acpica/evregion.c:acpi_ev_address_space_dispatch
  - drivers/acpi/acpica/evregion.c:acpi_ev_address_space_dispatch
  - drivers/acpi/acpica/evrgnini.c:acpi_ev_initialize_region
  - drivers/acpi/acpica/evxfregn.c:acpi_remove_address_space_handler
  - drivers/acpi/acpica/evxfregn.c:acpi_remove_address_space_handler
  - drivers/acpi/acpica/excreate.c:acpi_ex_create_region
  - drivers/acpi/acpica/exfldio.c:acpi_ex_access_region
  - drivers/acpi/acpica/exfldio.c:acpi_ex_access_region
  - drivers/acpi/acpica/exfldio.c:acpi_ex_access_region
  - drivers/acpi/acpica/hwregs.c:acpi_hw_write
  - drivers/acpi/acpica/hwregs.c:acpi_hw_read
  - drivers/acpi/acpica/nsdump.c:acpi_ns_dump_one_object
  - drivers/acpi/acpica/utaddress.c:acpi_ut_check_address_range
  - drivers/acpi/acpica/dbdisply.c:acpi_db_display_non_root_handlers
  - drivers/acpi/acpica/dbdisply.c:acpi_db_display_handlers
```
**Symbols:**

```
ffffffff819be630-ffffffff819be6a3: acpi_ut_get_region_name (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
const char *acpi_ut_get_region_name(u8 space_id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/utdecode.c (ffffffff81a05820)
Location: drivers/acpi/acpica/utdecode.c:85
Inline: False
Direct callers:
  - drivers/acpi/acpica/evhandler.c:acpi_ev_install_space_handler
  - drivers/acpi/acpica/evhandler.c:acpi_ev_install_handler
  - drivers/acpi/acpica/evregion.c:acpi_ev_execute_reg_methods
  - drivers/acpi/acpica/evregion.c:acpi_ev_execute_reg_methods
  - drivers/acpi/acpica/evregion.c:acpi_ev_attach_region
  - drivers/acpi/acpica/evregion.c:acpi_ev_detach_region
  - drivers/acpi/acpica/evregion.c:acpi_ev_detach_region
  - drivers/acpi/acpica/evregion.c:acpi_ev_detach_region
  - drivers/acpi/acpica/evregion.c:acpi_ev_address_space_dispatch
  - drivers/acpi/acpica/evregion.c:acpi_ev_address_space_dispatch
  - drivers/acpi/acpica/evregion.c:acpi_ev_address_space_dispatch
  - drivers/acpi/acpica/evregion.c:acpi_ev_address_space_dispatch
  - drivers/acpi/acpica/evregion.c:acpi_ev_address_space_dispatch
  - drivers/acpi/acpica/evrgnini.c:acpi_ev_initialize_region
  - drivers/acpi/acpica/evxfregn.c:acpi_remove_address_space_handler
  - drivers/acpi/acpica/evxfregn.c:acpi_remove_address_space_handler
  - drivers/acpi/acpica/excreate.c:acpi_ex_create_region
  - drivers/acpi/acpica/exfldio.c:acpi_ex_access_region
  - drivers/acpi/acpica/exfldio.c:acpi_ex_access_region
  - drivers/acpi/acpica/exfldio.c:acpi_ex_access_region
  - drivers/acpi/acpica/hwregs.c:acpi_hw_write
  - drivers/acpi/acpica/hwregs.c:acpi_hw_read
  - drivers/acpi/acpica/nsdump.c:acpi_ns_dump_one_object
  - drivers/acpi/acpica/utaddress.c:acpi_ut_check_address_range
  - drivers/acpi/acpica/dbdisply.c:acpi_db_display_non_root_handlers
  - drivers/acpi/acpica/dbdisply.c:acpi_db_display_handlers
```
**Symbols:**

```
ffffffff81a05820-ffffffff81a05893: acpi_ut_get_region_name (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
const char *acpi_ut_get_region_name(u8 space_id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/utdecode.c (ffffffff81a506c0)
Location: drivers/acpi/acpica/utdecode.c:85
Inline: False
Direct callers:
  - drivers/acpi/acpica/evhandler.c:acpi_ev_install_space_handler
  - drivers/acpi/acpica/evhandler.c:acpi_ev_install_handler
  - drivers/acpi/acpica/evregion.c:acpi_ev_execute_reg_methods
  - drivers/acpi/acpica/evregion.c:acpi_ev_execute_reg_methods
  - drivers/acpi/acpica/evregion.c:acpi_ev_attach_region
  - drivers/acpi/acpica/evregion.c:acpi_ev_detach_region
  - drivers/acpi/acpica/evregion.c:acpi_ev_detach_region
  - drivers/acpi/acpica/evregion.c:acpi_ev_detach_region
  - drivers/acpi/acpica/evregion.c:acpi_ev_address_space_dispatch
  - drivers/acpi/acpica/evregion.c:acpi_ev_address_space_dispatch
  - drivers/acpi/acpica/evregion.c:acpi_ev_address_space_dispatch
  - drivers/acpi/acpica/evregion.c:acpi_ev_address_space_dispatch
  - drivers/acpi/acpica/evregion.c:acpi_ev_address_space_dispatch
  - drivers/acpi/acpica/evrgnini.c:acpi_ev_initialize_region
  - drivers/acpi/acpica/evxfregn.c:acpi_remove_address_space_handler
  - drivers/acpi/acpica/evxfregn.c:acpi_remove_address_space_handler
  - drivers/acpi/acpica/excreate.c:acpi_ex_create_region
  - drivers/acpi/acpica/exfldio.c:acpi_ex_access_region
  - drivers/acpi/acpica/exfldio.c:acpi_ex_access_region
  - drivers/acpi/acpica/exfldio.c:acpi_ex_access_region
  - drivers/acpi/acpica/hwregs.c:acpi_hw_write
  - drivers/acpi/acpica/hwregs.c:acpi_hw_read
  - drivers/acpi/acpica/nsdump.c:acpi_ns_dump_one_object
  - drivers/acpi/acpica/utaddress.c:acpi_ut_check_address_range
  - drivers/acpi/acpica/dbdisply.c:acpi_db_display_non_root_handlers
  - drivers/acpi/acpica/dbdisply.c:acpi_db_display_handlers
```
**Symbols:**

```
ffffffff81a506c0-ffffffff81a50733: acpi_ut_get_region_name (STB_GLOBAL)
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
const char *acpi_ut_get_region_name(u8 space_id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/utdecode.c (ffff80001079aed4)
Location: drivers/acpi/acpica/utdecode.c:84
Inline: False
Direct callers:
  - drivers/acpi/acpica/evregion.c:acpi_ev_detach_region
  - drivers/acpi/acpica/evregion.c:acpi_ev_detach_region
  - drivers/acpi/acpica/evregion.c:acpi_ev_address_space_dispatch
  - drivers/acpi/acpica/evregion.c:acpi_ev_address_space_dispatch
  - drivers/acpi/acpica/evregion.c:acpi_ev_address_space_dispatch
  - drivers/acpi/acpica/evregion.c:acpi_ev_address_space_dispatch
  - drivers/acpi/acpica/utaddress.c:acpi_ut_check_address_range
```
**Symbols:**

```
ffff80001079aed4-ffff80001079af50: acpi_ut_get_region_name (STB_GLOBAL)
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
const char *acpi_ut_get_region_name(u8 space_id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/utdecode.c (ffffffff815fe471)
Location: drivers/acpi/acpica/utdecode.c:84
Inline: False
Direct callers:
  - drivers/acpi/acpica/evregion.c:acpi_ev_detach_region
  - drivers/acpi/acpica/evregion.c:acpi_ev_detach_region
  - drivers/acpi/acpica/evregion.c:acpi_ev_address_space_dispatch
  - drivers/acpi/acpica/evregion.c:acpi_ev_address_space_dispatch
  - drivers/acpi/acpica/evregion.c:acpi_ev_address_space_dispatch
  - drivers/acpi/acpica/evregion.c:acpi_ev_address_space_dispatch
  - drivers/acpi/acpica/utaddress.c:acpi_ut_check_address_range
```
**Symbols:**

```
ffffffff815fe471-ffffffff815fe4bb: acpi_ut_get_region_name (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
const char *acpi_ut_get_region_name(u8 space_id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/utdecode.c (ffffffff815e9968)
Location: drivers/acpi/acpica/utdecode.c:84
Inline: False
Direct callers:
  - drivers/acpi/acpica/evregion.c:acpi_ev_detach_region
  - drivers/acpi/acpica/evregion.c:acpi_ev_detach_region
  - drivers/acpi/acpica/evregion.c:acpi_ev_address_space_dispatch
  - drivers/acpi/acpica/evregion.c:acpi_ev_address_space_dispatch
  - drivers/acpi/acpica/evregion.c:acpi_ev_address_space_dispatch
  - drivers/acpi/acpica/evregion.c:acpi_ev_address_space_dispatch
  - drivers/acpi/acpica/utaddress.c:acpi_ut_check_address_range
```
**Symbols:**

```
ffffffff815e9968-ffffffff815e99b2: acpi_ut_get_region_name (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
const char *acpi_ut_get_region_name(u8 space_id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/utdecode.c (ffffffff816197f3)
Location: drivers/acpi/acpica/utdecode.c:84
Inline: False
Direct callers:
  - drivers/acpi/acpica/evhandler.c:acpi_ev_install_space_handler
  - drivers/acpi/acpica/evregion.c:acpi_ev_execute_reg_methods
  - drivers/acpi/acpica/evregion.c:acpi_ev_execute_reg_methods
  - drivers/acpi/acpica/evregion.c:acpi_ev_attach_region
  - drivers/acpi/acpica/evregion.c:acpi_ev_detach_region
  - drivers/acpi/acpica/evregion.c:acpi_ev_detach_region
  - drivers/acpi/acpica/evregion.c:acpi_ev_address_space_dispatch
  - drivers/acpi/acpica/evregion.c:acpi_ev_address_space_dispatch
  - drivers/acpi/acpica/evregion.c:acpi_ev_address_space_dispatch
  - drivers/acpi/acpica/evregion.c:acpi_ev_address_space_dispatch
  - drivers/acpi/acpica/evregion.c:acpi_ev_address_space_dispatch
  - drivers/acpi/acpica/evrgnini.c:acpi_ev_initialize_region
  - drivers/acpi/acpica/excreate.c:acpi_ex_create_region
  - drivers/acpi/acpica/exfldio.c:acpi_ex_access_region
  - drivers/acpi/acpica/exfldio.c:acpi_ex_access_region
  - drivers/acpi/acpica/exfldio.c:acpi_ex_access_region
  - drivers/acpi/acpica/hwregs.c:acpi_hw_write
  - drivers/acpi/acpica/hwregs.c:acpi_hw_read
  - drivers/acpi/acpica/utaddress.c:acpi_ut_check_address_range
  - drivers/acpi/acpica/dbdisply.c:acpi_db_display_non_root_handlers
  - drivers/acpi/acpica/dbdisply.c:acpi_db_display_handlers
```
**Symbols:**

```
ffffffff816197f3-ffffffff8161983d: acpi_ut_get_region_name (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
const char *acpi_ut_get_region_name(u8 space_id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/utdecode.c (ffffffff816336a3)
Location: drivers/acpi/acpica/utdecode.c:84
Inline: False
Direct callers:
  - drivers/acpi/acpica/evhandler.c:acpi_ev_install_space_handler
  - drivers/acpi/acpica/evregion.c:acpi_ev_execute_reg_methods
  - drivers/acpi/acpica/evregion.c:acpi_ev_execute_reg_methods
  - drivers/acpi/acpica/evregion.c:acpi_ev_attach_region
  - drivers/acpi/acpica/evregion.c:acpi_ev_detach_region
  - drivers/acpi/acpica/evregion.c:acpi_ev_detach_region
  - drivers/acpi/acpica/evregion.c:acpi_ev_address_space_dispatch
  - drivers/acpi/acpica/evregion.c:acpi_ev_address_space_dispatch
  - drivers/acpi/acpica/evregion.c:acpi_ev_address_space_dispatch
  - drivers/acpi/acpica/evregion.c:acpi_ev_address_space_dispatch
  - drivers/acpi/acpica/evregion.c:acpi_ev_address_space_dispatch
  - drivers/acpi/acpica/evrgnini.c:acpi_ev_initialize_region
  - drivers/acpi/acpica/excreate.c:acpi_ex_create_region
  - drivers/acpi/acpica/exfldio.c:acpi_ex_access_region
  - drivers/acpi/acpica/exfldio.c:acpi_ex_access_region
  - drivers/acpi/acpica/exfldio.c:acpi_ex_access_region
  - drivers/acpi/acpica/hwregs.c:acpi_hw_write
  - drivers/acpi/acpica/hwregs.c:acpi_hw_read
  - drivers/acpi/acpica/utaddress.c:acpi_ut_check_address_range
  - drivers/acpi/acpica/dbdisply.c:acpi_db_display_non_root_handlers
  - drivers/acpi/acpica/dbdisply.c:acpi_db_display_handlers
```
**Symbols:**

```
ffffffff816336a3-ffffffff816336ed: acpi_ut_get_region_name (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
<details>
<summary>Changed between <code>4.4</code> and <code>4.8</code> ⚠️</summary>
<ul>
<li>
<b>Return type changed. </b>
<code>char *</code> ➡️ <code>const char *</code>
</li>
</ul>
</details>
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
