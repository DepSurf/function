# Function: <code>efi_guidcmp</code>

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
In arch/x86/platform/efi/quirks.c (ffffffff81f79b5c)
Location: include/linux/efi.h:872
Inline: True
Inline callers:
  - arch/x86/platform/efi/quirks.c:efi_reuse_config
```
```
In block/partitions/efi.c (ffffffff813d4069)
Location: include/linux/efi.h:872
Inline: True
Inline callers:
  - block/partitions/efi.c:compare_gpts
  - block/partitions/efi.c:efi_partition
  - block/partitions/efi.c:efi_partition
```
```
In drivers/firmware/efi/efi.c (ffffffff81fb6405)
Location: include/linux/efi.h:872
Inline: True
Inline callers:
  - drivers/firmware/efi/efi.c:match_config_table
  - drivers/firmware/efi/efi.c:match_config_table
```
```
In drivers/firmware/efi/vars.c (ffffffff816d0b2d)
Location: include/linux/efi.h:872
Inline: True
Inline callers:
  - drivers/firmware/efi/vars.c:efivar_validate
  - drivers/firmware/efi/vars.c:efivar_variable_is_removable
  - drivers/firmware/efi/vars.c:efivar_entry_find
  - drivers/firmware/efi/vars.c:efivar_init
```
```
In drivers/firmware/efi/efivars.c (ffffffff816d2f1c)
Location: include/linux/efi.h:872
Inline: True
Inline callers:
  - drivers/firmware/efi/efivars.c:efivar_store_raw
  - drivers/firmware/efi/efivars.c:efivar_store_raw
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
In arch/x86/platform/efi/quirks.c (ffffffff81fa229e)
Location: include/linux/efi.h:901
Inline: True
Inline callers:
  - arch/x86/platform/efi/quirks.c:efi_reuse_config
```
```
In crypto/asymmetric_keys/efi_parser.c (ffffffff81fc58c5)
Location: include/linux/efi.h:901
Inline: True
Inline callers:
  - crypto/asymmetric_keys/efi_parser.c:parse_efi_signature_list
```
```
In block/partitions/efi.c (ffffffff8141a198)
Location: include/linux/efi.h:901
Inline: True
Inline callers:
  - block/partitions/efi.c:efi_partition
  - block/partitions/efi.c:efi_partition
  - block/partitions/efi.c:compare_gpts
```
```
In drivers/firmware/efi/efi.c (ffffffff81fe3a1d)
Location: include/linux/efi.h:901
Inline: True
Inline callers:
  - drivers/firmware/efi/efi.c:match_config_table
  - drivers/firmware/efi/efi.c:match_config_table
```
```
In drivers/firmware/efi/vars.c (ffffffff8173401f)
Location: include/linux/efi.h:901
Inline: True
Inline callers:
  - drivers/firmware/efi/vars.c:efivar_entry_find
  - drivers/firmware/efi/vars.c:efivar_init
  - drivers/firmware/efi/vars.c:efivar_variable_is_removable
  - drivers/firmware/efi/vars.c:efivar_validate
```
```
In drivers/firmware/efi/efivars.c (ffffffff81736720)
Location: include/linux/efi.h:901
Inline: True
Inline callers:
  - drivers/firmware/efi/efivars.c:efivar_store_raw
  - drivers/firmware/efi/efivars.c:efivar_store_raw
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
In arch/x86/platform/efi/quirks.c (ffffffff81fdd8df)
Location: include/linux/efi.h:942
Inline: True
Inline callers:
  - arch/x86/platform/efi/quirks.c:efi_reuse_config
```
```
In crypto/asymmetric_keys/efi_parser.c (ffffffff820022d5)
Location: include/linux/efi.h:942
Inline: True
Inline callers:
  - crypto/asymmetric_keys/efi_parser.c:parse_efi_signature_list
```
```
In block/partitions/efi.c (ffffffff814356c8)
Location: include/linux/efi.h:942
Inline: True
Inline callers:
  - block/partitions/efi.c:efi_partition
  - block/partitions/efi.c:efi_partition
  - block/partitions/efi.c:compare_gpts
```
```
In drivers/firmware/efi/efi.c (ffffffff820217ec)
Location: include/linux/efi.h:942
Inline: True
Inline callers:
  - drivers/firmware/efi/efi.c:match_config_table
  - drivers/firmware/efi/efi.c:match_config_table
```
```
In drivers/firmware/efi/vars.c (ffffffff8176707f)
Location: include/linux/efi.h:942
Inline: True
Inline callers:
  - drivers/firmware/efi/vars.c:efivar_entry_find
  - drivers/firmware/efi/vars.c:efivar_init
  - drivers/firmware/efi/vars.c:efivar_variable_is_removable
  - drivers/firmware/efi/vars.c:efivar_validate
```
```
In drivers/firmware/efi/efivars.c (ffffffff81769c93)
Location: include/linux/efi.h:942
Inline: True
Inline callers:
  - drivers/firmware/efi/efivars.c:efivar_store_raw
  - drivers/firmware/efi/efivars.c:efivar_store_raw
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
In arch/x86/platform/efi/quirks.c (ffffffff820be71f)
Location: include/linux/efi.h:956
Inline: True
Inline callers:
  - arch/x86/platform/efi/quirks.c:efi_reuse_config
```
```
In certs/load_uefi.c (ffffffff820cdda3)
Location: include/linux/efi.h:956
Inline: True
Inline callers:
  - certs/load_uefi.c:get_handler_for_db
```
```
In block/partitions/efi.c (ffffffff8144217a)
Location: include/linux/efi.h:956
Inline: True
Inline callers:
  - block/partitions/efi.c:efi_partition
  - block/partitions/efi.c:efi_partition
  - block/partitions/efi.c:compare_gpts
```
```
In drivers/firmware/efi/efi.c (ffffffff8210451c)
Location: include/linux/efi.h:956
Inline: True
```
```
In drivers/firmware/efi/vars.c (ffffffff8178598c)
Location: include/linux/efi.h:956
Inline: True
Inline callers:
  - drivers/firmware/efi/vars.c:efivar_entry_find
  - drivers/firmware/efi/vars.c:efivar_init
  - drivers/firmware/efi/vars.c:efivar_variable_is_removable
  - drivers/firmware/efi/vars.c:efivar_validate
```
```
In drivers/firmware/efi/efivars.c (ffffffff81788138)
Location: include/linux/efi.h:956
Inline: True
Inline callers:
  - drivers/firmware/efi/efivars.c:efivar_store_raw
  - drivers/firmware/efi/efivars.c:efivar_store_raw
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
In arch/x86/platform/efi/quirks.c (ffffffff826c6844)
Location: include/linux/efi.h:959
Inline: True
Inline callers:
  - arch/x86/platform/efi/quirks.c:efi_reuse_config
```
```
In certs/load_uefi.c (ffffffff826d67d9)
Location: include/linux/efi.h:959
Inline: True
Inline callers:
  - certs/load_uefi.c:get_handler_for_db
```
```
In block/partitions/efi.c (ffffffff8146eaea)
Location: include/linux/efi.h:959
Inline: True
Inline callers:
  - block/partitions/efi.c:efi_partition
  - block/partitions/efi.c:efi_partition
  - block/partitions/efi.c:compare_gpts
```
```
In drivers/firmware/efi/efi.c (ffffffff8270dbcb)
Location: include/linux/efi.h:959
Inline: True
```
```
In drivers/firmware/efi/vars.c (ffffffff817fbdcc)
Location: include/linux/efi.h:959
Inline: True
Inline callers:
  - drivers/firmware/efi/vars.c:efivar_entry_find
  - drivers/firmware/efi/vars.c:efivar_init
  - drivers/firmware/efi/vars.c:efivar_variable_is_removable
  - drivers/firmware/efi/vars.c:efivar_validate
```
```
In drivers/firmware/efi/efivars.c (ffffffff817fe5d5)
Location: include/linux/efi.h:959
Inline: True
Inline callers:
  - drivers/firmware/efi/efivars.c:efivar_store_raw
  - drivers/firmware/efi/efivars.c:efivar_store_raw
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
In arch/x86/platform/efi/quirks.c (ffffffff826f094a)
Location: include/linux/efi.h:999
Inline: True
Inline callers:
  - arch/x86/platform/efi/quirks.c:efi_reuse_config
```
```
In certs/load_uefi.c (ffffffff82700923)
Location: include/linux/efi.h:999
Inline: True
Inline callers:
  - certs/load_uefi.c:get_handler_for_dbx
  - certs/load_uefi.c:get_handler_for_dbx
  - certs/load_uefi.c:get_handler_for_db
```
```
In block/partitions/efi.c (ffffffff814a2b6b)
Location: include/linux/efi.h:999
Inline: True
Inline callers:
  - block/partitions/efi.c:efi_partition
  - block/partitions/efi.c:efi_partition
  - block/partitions/efi.c:find_valid_gpt
```
```
In drivers/firmware/efi/efi.c (ffffffff8273814a)
Location: include/linux/efi.h:999
Inline: True
```
```
In drivers/firmware/efi/vars.c (ffffffff818452ff)
Location: include/linux/efi.h:999
Inline: True
Inline callers:
  - drivers/firmware/efi/vars.c:efivar_entry_find
  - drivers/firmware/efi/vars.c:efivar_init
  - drivers/firmware/efi/vars.c:efivar_variable_is_removable
  - drivers/firmware/efi/vars.c:efivar_validate
```
```
In drivers/firmware/efi/efivars.c (ffffffff81847bc5)
Location: include/linux/efi.h:999
Inline: True
Inline callers:
  - drivers/firmware/efi/efivars.c:efivar_store_raw
  - drivers/firmware/efi/efivars.c:efivar_store_raw
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
In arch/x86/platform/efi/quirks.c (ffffffff828a7652)
Location: include/linux/efi.h:1012
Inline: True
Inline callers:
  - arch/x86/platform/efi/quirks.c:efi_reuse_config
```
```
In certs/load_uefi.c (ffffffff828b7c79)
Location: include/linux/efi.h:1012
Inline: True
Inline callers:
  - certs/load_uefi.c:get_handler_for_dbx
  - certs/load_uefi.c:get_handler_for_dbx
  - certs/load_uefi.c:get_handler_for_db
```
```
In security/integrity/platform_certs/load_uefi.c (ffffffff828cf74c)
Location: include/linux/efi.h:1012
Inline: True
Inline callers:
  - security/integrity/platform_certs/load_uefi.c:get_handler_for_dbx
  - security/integrity/platform_certs/load_uefi.c:get_handler_for_dbx
  - security/integrity/platform_certs/load_uefi.c:get_handler_for_db
```
```
In block/partitions/efi.c (ffffffff814bcd4d)
Location: include/linux/efi.h:1012
Inline: True
Inline callers:
  - block/partitions/efi.c:efi_partition
  - block/partitions/efi.c:efi_partition
  - block/partitions/efi.c:compare_gpts
```
```
In drivers/firmware/efi/efi.c (ffffffff828f2128)
Location: include/linux/efi.h:1012
Inline: True
```
```
In drivers/firmware/efi/vars.c (ffffffff8187144f)
Location: include/linux/efi.h:1012
Inline: True
Inline callers:
  - drivers/firmware/efi/vars.c:efivar_entry_find
  - drivers/firmware/efi/vars.c:efivar_init
  - drivers/firmware/efi/vars.c:efivar_variable_is_removable
  - drivers/firmware/efi/vars.c:efivar_validate
```
```
In drivers/firmware/efi/efivars.c (ffffffff81873f72)
Location: include/linux/efi.h:1012
Inline: True
Inline callers:
  - drivers/firmware/efi/efivars.c:efivar_store_raw
  - drivers/firmware/efi/efivars.c:efivar_store_raw
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
In arch/x86/platform/efi/quirks.c (ffffffff828bfd48)
Location: include/linux/efi.h:1027
Inline: True
Inline callers:
  - arch/x86/platform/efi/quirks.c:efi_reuse_config
```
```
In security/integrity/platform_certs/load_uefi.c (ffffffff828e9447)
Location: include/linux/efi.h:1027
Inline: True
Inline callers:
  - security/integrity/platform_certs/load_uefi.c:get_handler_for_dbx
  - security/integrity/platform_certs/load_uefi.c:get_handler_for_dbx
  - security/integrity/platform_certs/load_uefi.c:get_handler_for_db
```
```
In block/partitions/efi.c (ffffffff814eb3d9)
Location: include/linux/efi.h:1027
Inline: True
Inline callers:
  - block/partitions/efi.c:efi_partition
  - block/partitions/efi.c:efi_partition
  - block/partitions/efi.c:compare_gpts
```
```
In drivers/firmware/efi/efi.c (ffffffff8290d78c)
Location: include/linux/efi.h:1027
Inline: True
```
```
In drivers/firmware/efi/vars.c (ffffffff818b5790)
Location: include/linux/efi.h:1027
Inline: True
Inline callers:
  - drivers/firmware/efi/vars.c:efivar_entry_find
  - drivers/firmware/efi/vars.c:efivar_init
  - drivers/firmware/efi/vars.c:efivar_variable_is_removable
  - drivers/firmware/efi/vars.c:efivar_validate
```
```
In drivers/firmware/efi/efivars.c (ffffffff818b817a)
Location: include/linux/efi.h:1027
Inline: True
Inline callers:
  - drivers/firmware/efi/efivars.c:efivar_store_raw
  - drivers/firmware/efi/efivars.c:efivar_store_raw
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
In arch/x86/platform/efi/quirks.c (ffffffff828c61c6)
Location: include/linux/efi.h:1028
Inline: True
Inline callers:
  - arch/x86/platform/efi/quirks.c:efi_reuse_config
```
```
In security/integrity/platform_certs/keyring_handler.c (ffffffff828f250a)
Location: include/linux/efi.h:1028
Inline: True
Inline callers:
  - security/integrity/platform_certs/keyring_handler.c:get_handler_for_dbx
  - security/integrity/platform_certs/keyring_handler.c:get_handler_for_dbx
  - security/integrity/platform_certs/keyring_handler.c:get_handler_for_db
```
```
In block/partitions/efi.c (ffffffff8150479f)
Location: include/linux/efi.h:1028
Inline: True
Inline callers:
  - block/partitions/efi.c:efi_partition
  - block/partitions/efi.c:efi_partition
  - block/partitions/efi.c:compare_gpts
```
```
In drivers/firmware/efi/efi.c (ffffffff82916e51)
Location: include/linux/efi.h:1028
Inline: True
```
```
In drivers/firmware/efi/vars.c (ffffffff818e80f0)
Location: include/linux/efi.h:1028
Inline: True
Inline callers:
  - drivers/firmware/efi/vars.c:efivar_entry_find
  - drivers/firmware/efi/vars.c:efivar_init
  - drivers/firmware/efi/vars.c:efivar_variable_is_removable
  - drivers/firmware/efi/vars.c:efivar_validate
```
```
In drivers/firmware/efi/efivars.c (ffffffff818eab3d)
Location: include/linux/efi.h:1028
Inline: True
Inline callers:
  - drivers/firmware/efi/efivars.c:efivar_store_raw
  - drivers/firmware/efi/efivars.c:efivar_store_raw
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
In arch/x86/platform/efi/quirks.c (ffffffff82ce95a2)
Location: include/linux/efi.h:594
Inline: True
Inline callers:
  - arch/x86/platform/efi/quirks.c:efi_reuse_config
```
```
In security/integrity/platform_certs/keyring_handler.c (ffffffff82d074be)
Location: include/linux/efi.h:594
Inline: True
Inline callers:
  - security/integrity/platform_certs/keyring_handler.c:get_handler_for_dbx
  - security/integrity/platform_certs/keyring_handler.c:get_handler_for_dbx
  - security/integrity/platform_certs/keyring_handler.c:get_handler_for_db
```
```
In block/partitions/efi.c (ffffffff815651ee)
Location: include/linux/efi.h:594
Inline: True
Inline callers:
  - block/partitions/efi.c:efi_partition
  - block/partitions/efi.c:efi_partition
  - block/partitions/efi.c:compare_gpts
```
```
In drivers/firmware/efi/efi.c (ffffffff82d29390)
Location: include/linux/efi.h:594
Inline: True
Inline callers:
  - drivers/firmware/efi/efi.c:match_config_table
  - drivers/firmware/efi/efi.c:match_config_table
```
```
In drivers/firmware/efi/vars.c (ffffffff819bb7ba)
Location: include/linux/efi.h:594
Inline: True
Inline callers:
  - drivers/firmware/efi/vars.c:efivar_entry_find
  - drivers/firmware/efi/vars.c:variable_is_present
  - drivers/firmware/efi/vars.c:efivar_variable_is_removable
  - drivers/firmware/efi/vars.c:efivar_validate
```
```
In drivers/firmware/efi/efivars.c (ffffffff819be275)
Location: include/linux/efi.h:594
Inline: True
Inline callers:
  - drivers/firmware/efi/efivars.c:efivar_store_raw
  - drivers/firmware/efi/efivars.c:efivar_store_raw
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
In arch/x86/platform/efi/quirks.c (ffffffff82fd7018)
Location: include/linux/efi.h:599
Inline: True
Inline callers:
  - arch/x86/platform/efi/quirks.c:efi_reuse_config
```
```
In security/integrity/platform_certs/keyring_handler.c (ffffffff82ff497d)
Location: include/linux/efi.h:599
Inline: True
Inline callers:
  - security/integrity/platform_certs/keyring_handler.c:get_handler_for_dbx
  - security/integrity/platform_certs/keyring_handler.c:get_handler_for_dbx
  - security/integrity/platform_certs/keyring_handler.c:get_handler_for_db
```
```
In block/partitions/efi.c (ffffffff815802e8)
Location: include/linux/efi.h:599
Inline: True
Inline callers:
  - block/partitions/efi.c:efi_partition
  - block/partitions/efi.c:efi_partition
  - block/partitions/efi.c:compare_gpts
```
```
In drivers/firmware/efi/efi.c (ffffffff83017aa8)
Location: include/linux/efi.h:599
Inline: True
Inline callers:
  - drivers/firmware/efi/efi.c:match_config_table
  - drivers/firmware/efi/efi.c:match_config_table
```
```
In drivers/firmware/efi/vars.c (ffffffff819bd94a)
Location: include/linux/efi.h:599
Inline: True
Inline callers:
  - drivers/firmware/efi/vars.c:efivar_entry_find
  - drivers/firmware/efi/vars.c:variable_is_present
  - drivers/firmware/efi/vars.c:efivar_variable_is_removable
  - drivers/firmware/efi/vars.c:efivar_validate
```
```
In drivers/firmware/efi/efivars.c (ffffffff819bfef5)
Location: include/linux/efi.h:599
Inline: True
Inline callers:
  - drivers/firmware/efi/efivars.c:efivar_store_raw
  - drivers/firmware/efi/efivars.c:efivar_store_raw
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
In arch/x86/platform/efi/quirks.c (ffffffff831e1a63)
Location: include/linux/efi.h:597
Inline: True
Inline callers:
  - arch/x86/platform/efi/quirks.c:efi_reuse_config
```
```
In security/integrity/platform_certs/keyring_handler.c (ffffffff831ff646)
Location: include/linux/efi.h:597
Inline: True
Inline callers:
  - security/integrity/platform_certs/keyring_handler.c:get_handler_for_dbx
  - security/integrity/platform_certs/keyring_handler.c:get_handler_for_dbx
  - security/integrity/platform_certs/keyring_handler.c:get_handler_for_dbx
  - security/integrity/platform_certs/keyring_handler.c:get_handler_for_db
```
```
In block/partitions/efi.c (ffffffff81587e60)
Location: include/linux/efi.h:597
Inline: True
Inline callers:
  - block/partitions/efi.c:efi_partition
  - block/partitions/efi.c:efi_partition
  - block/partitions/efi.c:compare_gpts
```
```
In drivers/firmware/efi/efi.c (ffffffff83222980)
Location: include/linux/efi.h:597
Inline: True
Inline callers:
  - drivers/firmware/efi/efi.c:match_config_table
  - drivers/firmware/efi/efi.c:match_config_table
```
```
In drivers/firmware/efi/vars.c (ffffffff819a1fbe)
Location: include/linux/efi.h:597
Inline: True
Inline callers:
  - drivers/firmware/efi/vars.c:efivar_entry_find
  - drivers/firmware/efi/vars.c:efivar_init
  - drivers/firmware/efi/vars.c:efivar_variable_is_removable
  - drivers/firmware/efi/vars.c:efivar_validate
```
```
In drivers/firmware/efi/efivars.c (ffffffff819a45fd)
Location: include/linux/efi.h:597
Inline: True
Inline callers:
  - drivers/firmware/efi/efivars.c:efivar_store_raw
  - drivers/firmware/efi/efivars.c:efivar_store_raw
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
In arch/x86/platform/efi/quirks.c (ffffffff832c5371)
Location: include/linux/efi.h:597
Inline: True
Inline callers:
  - arch/x86/platform/efi/quirks.c:efi_reuse_config
```
```
In security/integrity/platform_certs/keyring_handler.c (ffffffff832e6a2f)
Location: include/linux/efi.h:597
Inline: True
Inline callers:
  - security/integrity/platform_certs/keyring_handler.c:get_handler_for_dbx
  - security/integrity/platform_certs/keyring_handler.c:get_handler_for_dbx
  - security/integrity/platform_certs/keyring_handler.c:get_handler_for_dbx
  - security/integrity/platform_certs/keyring_handler.c:get_handler_for_db
```
```
In block/partitions/efi.c (ffffffff815edb08)
Location: include/linux/efi.h:597
Inline: True
Inline callers:
  - block/partitions/efi.c:efi_partition
  - block/partitions/efi.c:efi_partition
  - block/partitions/efi.c:compare_gpts
```
```
In drivers/firmware/efi/efi.c (ffffffff8330c6e4)
Location: include/linux/efi.h:597
Inline: True
Inline callers:
  - drivers/firmware/efi/efi.c:match_config_table
  - drivers/firmware/efi/efi.c:match_config_table
```
```
In drivers/firmware/efi/vars.c (ffffffff81a4f3de)
Location: include/linux/efi.h:597
Inline: True
Inline callers:
  - drivers/firmware/efi/vars.c:efivar_entry_find
  - drivers/firmware/efi/vars.c:efivar_init
  - drivers/firmware/efi/vars.c:efivar_variable_is_removable
  - drivers/firmware/efi/vars.c:efivar_validate
```
```
In drivers/firmware/efi/efivars.c (ffffffff81a518ad)
Location: include/linux/efi.h:597
Inline: True
Inline callers:
  - drivers/firmware/efi/efivars.c:efivar_store_raw
  - drivers/firmware/efi/efivars.c:efivar_store_raw
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
In arch/x86/platform/efi/quirks.c (ffffffff83477f2d)
Location: include/linux/efi.h:664
Inline: True
Inline callers:
  - arch/x86/platform/efi/quirks.c:efi_reuse_config
```
```
In security/integrity/platform_certs/keyring_handler.c (ffffffff8349dae9)
Location: include/linux/efi.h:664
Inline: True
Inline callers:
  - security/integrity/platform_certs/keyring_handler.c:get_handler_for_dbx
  - security/integrity/platform_certs/keyring_handler.c:get_handler_for_dbx
  - security/integrity/platform_certs/keyring_handler.c:get_handler_for_dbx
  - security/integrity/platform_certs/keyring_handler.c:get_handler_for_mok
  - security/integrity/platform_certs/keyring_handler.c:get_handler_for_db
```
```
In block/partitions/efi.c (ffffffff8169e0af)
Location: include/linux/efi.h:664
Inline: True
Inline callers:
  - block/partitions/efi.c:efi_partition
  - block/partitions/efi.c:efi_partition
  - block/partitions/efi.c:compare_gpts
```
```
In drivers/firmware/efi/efi.c (ffffffff834c5fc0)
Location: include/linux/efi.h:664
Inline: True
Inline callers:
  - drivers/firmware/efi/efi.c:match_config_table
  - drivers/firmware/efi/efi.c:match_config_table
```
```
In drivers/firmware/efi/vars.c (ffffffff81bbe13e)
Location: include/linux/efi.h:664
Inline: True
Inline callers:
  - drivers/firmware/efi/vars.c:efivar_entry_find
  - drivers/firmware/efi/vars.c:efivar_init
  - drivers/firmware/efi/vars.c:efivar_variable_is_removable
  - drivers/firmware/efi/vars.c:efivar_validate
```
```
In drivers/firmware/efi/efivars.c (ffffffff81bc06fb)
Location: include/linux/efi.h:664
Inline: True
Inline callers:
  - drivers/firmware/efi/efivars.c:efivar_store_raw
  - drivers/firmware/efi/efivars.c:efivar_store_raw
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
In arch/x86/platform/efi/quirks.c (ffffffff83ea1d01)
Location: include/linux/efi.h:680
Inline: True
Inline callers:
  - arch/x86/platform/efi/quirks.c:efi_reuse_config
```
```
In fs/efivarfs/vars.c (ffffffff8163b2f6)
Location: include/linux/efi.h:680
Inline: True
Inline callers:
  - fs/efivarfs/vars.c:efivar_init
  - fs/efivarfs/vars.c:efivar_variable_is_removable
  - fs/efivarfs/vars.c:efivar_validate
```
```
In security/integrity/platform_certs/keyring_handler.c (ffffffff83ed57c6)
Location: include/linux/efi.h:680
Inline: True
Inline callers:
  - security/integrity/platform_certs/keyring_handler.c:get_handler_for_dbx
  - security/integrity/platform_certs/keyring_handler.c:get_handler_for_dbx
  - security/integrity/platform_certs/keyring_handler.c:get_handler_for_dbx
  - security/integrity/platform_certs/keyring_handler.c:get_handler_for_mok
  - security/integrity/platform_certs/keyring_handler.c:get_handler_for_db
```
```
In block/partitions/efi.c (ffffffff8175caef)
Location: include/linux/efi.h:680
Inline: True
Inline callers:
  - block/partitions/efi.c:efi_partition
  - block/partitions/efi.c:efi_partition
  - block/partitions/efi.c:compare_gpts
```
```
In drivers/firmware/efi/efi.c (ffffffff83f06bc0)
Location: include/linux/efi.h:680
Inline: True
Inline callers:
  - drivers/firmware/efi/efi.c:match_config_table
  - drivers/firmware/efi/efi.c:match_config_table
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
In arch/x86/platform/efi/quirks.c (ffffffff836c5f61)
Location: include/linux/efi.h:699
Inline: True
Inline callers:
  - arch/x86/platform/efi/quirks.c:efi_reuse_config
```
```
In fs/efivarfs/vars.c (ffffffff8167392a)
Location: include/linux/efi.h:699
Inline: True
Inline callers:
  - fs/efivarfs/vars.c:efivar_init
  - fs/efivarfs/vars.c:efivar_variable_is_removable
  - fs/efivarfs/vars.c:efivar_validate
```
```
In security/integrity/platform_certs/keyring_handler.c (ffffffff836fa926)
Location: include/linux/efi.h:699
Inline: True
Inline callers:
  - security/integrity/platform_certs/keyring_handler.c:get_handler_for_dbx
  - security/integrity/platform_certs/keyring_handler.c:get_handler_for_dbx
  - security/integrity/platform_certs/keyring_handler.c:get_handler_for_dbx
  - security/integrity/platform_certs/keyring_handler.c:get_handler_for_mok
  - security/integrity/platform_certs/keyring_handler.c:get_handler_for_db
```
```
In block/partitions/efi.c (ffffffff8179b38b)
Location: include/linux/efi.h:699
Inline: True
Inline callers:
  - block/partitions/efi.c:efi_partition
  - block/partitions/efi.c:efi_partition
  - block/partitions/efi.c:compare_gpts
```
```
In drivers/firmware/efi/efi.c (ffffffff8372cbf2)
Location: include/linux/efi.h:699
Inline: True
Inline callers:
  - drivers/firmware/efi/efi.c:match_config_table
  - drivers/firmware/efi/efi.c:match_config_table
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
In arch/x86/platform/efi/quirks.c (ffffffff838f6b61)
Location: include/linux/efi.h:698
Inline: True
Inline callers:
  - arch/x86/platform/efi/quirks.c:efi_reuse_config
```
```
In fs/efivarfs/vars.c (ffffffff816afcc6)
Location: include/linux/efi.h:698
Inline: True
Inline callers:
  - fs/efivarfs/vars.c:efivar_init
  - fs/efivarfs/vars.c:efivar_variable_is_removable
  - fs/efivarfs/vars.c:efivar_validate
```
```
In security/integrity/platform_certs/keyring_handler.c (ffffffff8392df26)
Location: include/linux/efi.h:698
Inline: True
Inline callers:
  - security/integrity/platform_certs/keyring_handler.c:get_handler_for_dbx
  - security/integrity/platform_certs/keyring_handler.c:get_handler_for_dbx
  - security/integrity/platform_certs/keyring_handler.c:get_handler_for_dbx
  - security/integrity/platform_certs/keyring_handler.c:get_handler_for_code_signing_keys
  - security/integrity/platform_certs/keyring_handler.c:get_handler_for_ca_keys
  - security/integrity/platform_certs/keyring_handler.c:get_handler_for_mok
  - security/integrity/platform_certs/keyring_handler.c:get_handler_for_db
```
```
In block/partitions/efi.c (ffffffff817dedeb)
Location: include/linux/efi.h:698
Inline: True
Inline callers:
  - block/partitions/efi.c:efi_partition
  - block/partitions/efi.c:efi_partition
  - block/partitions/efi.c:compare_gpts
```
```
In drivers/firmware/efi/efi.c (ffffffff83960fd2)
Location: include/linux/efi.h:698
Inline: True
Inline callers:
  - drivers/firmware/efi/efi.c:match_config_table
  - drivers/firmware/efi/efi.c:match_config_table
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
In drivers/firmware/efi/libstub/efi-stub-helper.c (ffff80001143ca28)
Location: include/linux/efi.h:1028
Inline: True
Inline callers:
  - drivers/firmware/efi/libstub/efi-stub-helper.c:get_efi_config_table
```
```
In security/integrity/platform_certs/keyring_handler.c (ffff80001146c954)
Location: include/linux/efi.h:1028
Inline: True
Inline callers:
  - security/integrity/platform_certs/keyring_handler.c:get_handler_for_dbx
  - security/integrity/platform_certs/keyring_handler.c:get_handler_for_dbx
  - security/integrity/platform_certs/keyring_handler.c:get_handler_for_db
```
```
In block/partitions/efi.c (ffff800010606830)
Location: include/linux/efi.h:1028
Inline: True
Inline callers:
  - block/partitions/efi.c:efi_partition
  - block/partitions/efi.c:efi_partition
  - block/partitions/efi.c:compare_gpts
```
```
In drivers/firmware/efi/efi.c (ffff8000114a551c)
Location: include/linux/efi.h:1028
Inline: True
```
```
In drivers/firmware/efi/vars.c (ffff800010b5b314)
Location: include/linux/efi.h:1028
Inline: True
Inline callers:
  - drivers/firmware/efi/vars.c:efivar_entry_find
  - drivers/firmware/efi/vars.c:efivar_init
  - drivers/firmware/efi/vars.c:efivar_variable_is_removable
  - drivers/firmware/efi/vars.c:efivar_validate
```
```
In drivers/firmware/efi/efivars.c (ffff800010b5de08)
Location: include/linux/efi.h:1028
Inline: True
Inline callers:
  - drivers/firmware/efi/efivars.c:efivar_store_raw
  - drivers/firmware/efi/efivars.c:efivar_store_raw
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
In security/integrity/platform_certs/keyring_handler.c (c15455ac)
Location: include/linux/efi.h:1028
Inline: True
Inline callers:
  - security/integrity/platform_certs/keyring_handler.c:get_handler_for_dbx
  - security/integrity/platform_certs/keyring_handler.c:get_handler_for_dbx
  - security/integrity/platform_certs/keyring_handler.c:get_handler_for_db
```
```
In block/partitions/efi.c (c07b1c08)
Location: include/linux/efi.h:1028
Inline: True
Inline callers:
  - block/partitions/efi.c:efi_partition
  - block/partitions/efi.c:compare_gpts
  - block/partitions/efi.c:is_pte_valid
```
```
In drivers/firmware/efi/efi.c (c15a77fc)
Location: include/linux/efi.h:1028
Inline: True
Inline callers:
  - drivers/firmware/efi/efi.c:match_config_table
  - drivers/firmware/efi/efi.c:match_config_table
```
```
In drivers/firmware/efi/vars.c (c0c3becc)
Location: include/linux/efi.h:1028
Inline: True
Inline callers:
  - drivers/firmware/efi/vars.c:efivar_entry_find
  - drivers/firmware/efi/vars.c:efivar_init
  - drivers/firmware/efi/vars.c:efivar_variable_is_removable
  - drivers/firmware/efi/vars.c:efivar_validate
```
```
In drivers/firmware/efi/efivars.c (c0c3db94)
Location: include/linux/efi.h:1028
Inline: True
Inline callers:
  - drivers/firmware/efi/efivars.c:efivar_store_raw
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
In security/integrity/platform_certs/keyring_handler.c (c00000000139b6b8)
Location: include/linux/efi.h:1028
Inline: True
Inline callers:
  - security/integrity/platform_certs/keyring_handler.c:get_handler_for_dbx
  - security/integrity/platform_certs/keyring_handler.c:get_handler_for_dbx
  - security/integrity/platform_certs/keyring_handler.c:get_handler_for_db
```
```
In block/partitions/efi.c (c0000000007a2f68)
Location: include/linux/efi.h:1028
Inline: True
Inline callers:
  - block/partitions/efi.c:efi_partition
  - block/partitions/efi.c:efi_partition
  - block/partitions/efi.c:find_valid_gpt
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In block/partitions/efi.c (ffffffe000441760)
Location: include/linux/efi.h:1028
Inline: True
Inline callers:
  - block/partitions/efi.c:efi_partition
  - block/partitions/efi.c:efi_partition
  - block/partitions/efi.c:compare_gpts
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
In arch/x86/platform/efi/quirks.c (ffffffff828b115e)
Location: include/linux/efi.h:1028
Inline: True
Inline callers:
  - arch/x86/platform/efi/quirks.c:efi_reuse_config
```
```
In security/integrity/platform_certs/keyring_handler.c (ffffffff828db3be)
Location: include/linux/efi.h:1028
Inline: True
Inline callers:
  - security/integrity/platform_certs/keyring_handler.c:get_handler_for_dbx
  - security/integrity/platform_certs/keyring_handler.c:get_handler_for_dbx
  - security/integrity/platform_certs/keyring_handler.c:get_handler_for_db
```
```
In block/partitions/efi.c (ffffffff814fcd7f)
Location: include/linux/efi.h:1028
Inline: True
Inline callers:
  - block/partitions/efi.c:efi_partition
  - block/partitions/efi.c:efi_partition
  - block/partitions/efi.c:compare_gpts
```
```
In drivers/firmware/efi/efi.c (ffffffff828fc257)
Location: include/linux/efi.h:1028
Inline: True
```
```
In drivers/firmware/efi/vars.c (ffffffff8188ae70)
Location: include/linux/efi.h:1028
Inline: True
Inline callers:
  - drivers/firmware/efi/vars.c:efivar_entry_find
  - drivers/firmware/efi/vars.c:efivar_init
  - drivers/firmware/efi/vars.c:efivar_variable_is_removable
  - drivers/firmware/efi/vars.c:efivar_validate
```
```
In drivers/firmware/efi/efivars.c (ffffffff8188d8bd)
Location: include/linux/efi.h:1028
Inline: True
Inline callers:
  - drivers/firmware/efi/efivars.c:efivar_store_raw
  - drivers/firmware/efi/efivars.c:efivar_store_raw
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
In arch/x86/platform/efi/quirks.c (ffffffff828a92e3)
Location: include/linux/efi.h:1028
Inline: True
Inline callers:
  - arch/x86/platform/efi/quirks.c:efi_reuse_config
```
```
In security/integrity/platform_certs/keyring_handler.c (ffffffff828d3ada)
Location: include/linux/efi.h:1028
Inline: True
Inline callers:
  - security/integrity/platform_certs/keyring_handler.c:get_handler_for_dbx
  - security/integrity/platform_certs/keyring_handler.c:get_handler_for_dbx
  - security/integrity/platform_certs/keyring_handler.c:get_handler_for_db
```
```
In block/partitions/efi.c (ffffffff814ed28f)
Location: include/linux/efi.h:1028
Inline: True
Inline callers:
  - block/partitions/efi.c:efi_partition
  - block/partitions/efi.c:efi_partition
  - block/partitions/efi.c:compare_gpts
```
```
In drivers/firmware/efi/efi.c (ffffffff828f3af3)
Location: include/linux/efi.h:1028
Inline: True
```
```
In drivers/firmware/efi/vars.c (ffffffff818427f0)
Location: include/linux/efi.h:1028
Inline: True
Inline callers:
  - drivers/firmware/efi/vars.c:efivar_entry_find
  - drivers/firmware/efi/vars.c:efivar_init
  - drivers/firmware/efi/vars.c:efivar_variable_is_removable
  - drivers/firmware/efi/vars.c:efivar_validate
```
```
In drivers/firmware/efi/efivars.c (ffffffff8184523d)
Location: include/linux/efi.h:1028
Inline: True
Inline callers:
  - drivers/firmware/efi/efivars.c:efivar_store_raw
  - drivers/firmware/efi/efivars.c:efivar_store_raw
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
In arch/x86/platform/efi/quirks.c (ffffffff828c405d)
Location: include/linux/efi.h:1028
Inline: True
Inline callers:
  - arch/x86/platform/efi/quirks.c:efi_reuse_config
```
```
In security/integrity/platform_certs/keyring_handler.c (ffffffff828ee132)
Location: include/linux/efi.h:1028
Inline: True
Inline callers:
  - security/integrity/platform_certs/keyring_handler.c:get_handler_for_dbx
  - security/integrity/platform_certs/keyring_handler.c:get_handler_for_dbx
  - security/integrity/platform_certs/keyring_handler.c:get_handler_for_db
```
```
In block/partitions/efi.c (ffffffff814f8e0f)
Location: include/linux/efi.h:1028
Inline: True
Inline callers:
  - block/partitions/efi.c:efi_partition
  - block/partitions/efi.c:efi_partition
  - block/partitions/efi.c:compare_gpts
```
```
In drivers/firmware/efi/efi.c (ffffffff82911486)
Location: include/linux/efi.h:1028
Inline: True
```
```
In drivers/firmware/efi/vars.c (ffffffff818dcf50)
Location: include/linux/efi.h:1028
Inline: True
Inline callers:
  - drivers/firmware/efi/vars.c:efivar_entry_find
  - drivers/firmware/efi/vars.c:efivar_init
  - drivers/firmware/efi/vars.c:efivar_variable_is_removable
  - drivers/firmware/efi/vars.c:efivar_validate
```
```
In drivers/firmware/efi/efivars.c (ffffffff818df99d)
Location: include/linux/efi.h:1028
Inline: True
Inline callers:
  - drivers/firmware/efi/efivars.c:efivar_store_raw
  - drivers/firmware/efi/efivars.c:efivar_store_raw
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
In arch/x86/platform/efi/quirks.c (ffffffff828c7203)
Location: include/linux/efi.h:1028
Inline: True
Inline callers:
  - arch/x86/platform/efi/quirks.c:efi_reuse_config
```
```
In security/integrity/platform_certs/keyring_handler.c (ffffffff828f3554)
Location: include/linux/efi.h:1028
Inline: True
Inline callers:
  - security/integrity/platform_certs/keyring_handler.c:get_handler_for_dbx
  - security/integrity/platform_certs/keyring_handler.c:get_handler_for_dbx
  - security/integrity/platform_certs/keyring_handler.c:get_handler_for_db
```
```
In block/partitions/efi.c (ffffffff81511e6f)
Location: include/linux/efi.h:1028
Inline: True
Inline callers:
  - block/partitions/efi.c:efi_partition
  - block/partitions/efi.c:efi_partition
  - block/partitions/efi.c:compare_gpts
```
```
In drivers/firmware/efi/efi.c (ffffffff82917eb3)
Location: include/linux/efi.h:1028
Inline: True
```
```
In drivers/firmware/efi/vars.c (ffffffff818f9a60)
Location: include/linux/efi.h:1028
Inline: True
Inline callers:
  - drivers/firmware/efi/vars.c:efivar_entry_find
  - drivers/firmware/efi/vars.c:efivar_init
  - drivers/firmware/efi/vars.c:efivar_variable_is_removable
  - drivers/firmware/efi/vars.c:efivar_validate
```
```
In drivers/firmware/efi/efivars.c (ffffffff818fc43d)
Location: include/linux/efi.h:1028
Inline: True
Inline callers:
  - drivers/firmware/efi/efivars.c:efivar_store_raw
  - drivers/firmware/efi/efivars.c:efivar_store_raw
```
</details>
</li>
</ul>

## Differences
