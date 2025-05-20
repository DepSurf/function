# Function: <code>hex_to_bin</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline ⚠️</summary>

```c
int hex_to_bin(char ch);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/hexdump.c (ffffffff814014d0)
Location: lib/hexdump.c:28
Inline: True
Inline callers:
  - lib/hexdump.c:hex2bin
  - lib/hexdump.c:hex2bin
Direct callers:
  - kernel/debug/gdbstub.c:kgdb_hex2mem
  - kernel/debug/gdbstub.c:kgdb_hex2mem
  - kernel/debug/gdbstub.c:kgdb_hex2long
  - kernel/debug/gdbstub.c:gdb_serial_stub
  - kernel/debug/gdbstub.c:gdb_serial_stub
  - kernel/debug/gdbstub.c:gdb_serial_stub
  - fs/efivarfs/inode.c:efivarfs_create
  - fs/efivarfs/inode.c:efivarfs_create
  - fs/efivarfs/inode.c:efivarfs_create
  - fs/efivarfs/inode.c:efivarfs_create
  - fs/efivarfs/inode.c:efivarfs_create
  - fs/efivarfs/inode.c:efivarfs_create
  - fs/efivarfs/inode.c:efivarfs_create
  - fs/efivarfs/inode.c:efivarfs_create
  - fs/efivarfs/inode.c:efivarfs_create
  - fs/efivarfs/inode.c:efivarfs_create
  - fs/efivarfs/inode.c:efivarfs_create
  - fs/efivarfs/inode.c:efivarfs_create
  - fs/efivarfs/inode.c:efivarfs_create
  - fs/efivarfs/inode.c:efivarfs_create
  - fs/efivarfs/inode.c:efivarfs_create
  - fs/efivarfs/inode.c:efivarfs_create
  - fs/efivarfs/inode.c:efivarfs_create
  - fs/efivarfs/inode.c:efivarfs_create
  - fs/efivarfs/inode.c:efivarfs_create
  - fs/efivarfs/inode.c:efivarfs_create
  - fs/efivarfs/inode.c:efivarfs_create
  - fs/efivarfs/inode.c:efivarfs_create
  - fs/efivarfs/inode.c:efivarfs_create
  - fs/efivarfs/inode.c:efivarfs_create
  - fs/efivarfs/inode.c:efivarfs_create
  - fs/efivarfs/inode.c:efivarfs_create
  - fs/efivarfs/inode.c:efivarfs_create
  - fs/efivarfs/inode.c:efivarfs_create
  - fs/efivarfs/inode.c:efivarfs_create
  - fs/efivarfs/inode.c:efivarfs_create
  - fs/efivarfs/inode.c:efivarfs_create
  - fs/efivarfs/inode.c:efivarfs_create
  - security/selinux/selinuxfs.c:sel_write_create
  - security/selinux/selinuxfs.c:sel_write_create
  - security/integrity/ima/ima_policy.c:ima_parse_rule
  - security/integrity/ima/ima_policy.c:ima_parse_rule
  - lib/bitmap.c:__bitmap_parse
  - lib/string_helpers.c:string_unescape
  - lib/string_helpers.c:string_unescape
  - drivers/tty/vt/vt.c:do_con_trol
  - drivers/nvdimm/core.c:nd_uuid_store
  - drivers/nvdimm/core.c:nd_uuid_store
  - net/core/utils.c:in4_pton
  - net/core/utils.c:in6_pton
```
**Symbols:**

```
ffffffff814014d0-ffffffff8140150f: hex_to_bin (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
int hex_to_bin(char ch);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/hexdump.c (ffffffff81448efb)
Location: lib/hexdump.c:28
Inline: True
Inline callers:
  - lib/hexdump.c:hex2bin
  - lib/hexdump.c:hex2bin
Direct callers:
  - kernel/debug/gdbstub.c:gdb_serial_stub
  - kernel/debug/gdbstub.c:gdb_serial_stub
  - kernel/debug/gdbstub.c:gdb_serial_stub
  - kernel/debug/gdbstub.c:kgdb_hex2long
  - kernel/debug/gdbstub.c:kgdb_hex2mem
  - kernel/debug/gdbstub.c:kgdb_hex2mem
  - security/selinux/selinuxfs.c:sel_write_create
  - security/selinux/selinuxfs.c:sel_write_create
  - lib/bitmap.c:__bitmap_parse
  - lib/uuid.c:__uuid_to_bin
  - lib/uuid.c:__uuid_to_bin
  - lib/string_helpers.c:string_unescape
  - lib/string_helpers.c:string_unescape
  - drivers/tty/vt/vt.c:do_con_trol
  - drivers/nvdimm/core.c:nd_uuid_store
  - drivers/nvdimm/core.c:nd_uuid_store
  - net/core/utils.c:in6_pton
  - net/core/utils.c:in4_pton
```
**Symbols:**

```
ffffffff81448ea0-ffffffff81448edc: hex_to_bin (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
int hex_to_bin(char ch);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/hexdump.c (ffffffff814678eb)
Location: lib/hexdump.c:28
Inline: True
Inline callers:
  - lib/hexdump.c:hex2bin
  - lib/hexdump.c:hex2bin
Direct callers:
  - kernel/debug/gdbstub.c:gdb_serial_stub
  - kernel/debug/gdbstub.c:gdb_serial_stub
  - kernel/debug/gdbstub.c:gdb_serial_stub
  - kernel/debug/gdbstub.c:kgdb_hex2long
  - kernel/debug/gdbstub.c:kgdb_hex2mem
  - kernel/debug/gdbstub.c:kgdb_hex2mem
  - security/selinux/selinuxfs.c:sel_write_create
  - security/selinux/selinuxfs.c:sel_write_create
  - lib/bitmap.c:__bitmap_parse
  - lib/uuid.c:__uuid_to_bin
  - lib/uuid.c:__uuid_to_bin
  - lib/string_helpers.c:string_unescape
  - lib/string_helpers.c:string_unescape
  - drivers/tty/vt/vt.c:do_con_trol
  - drivers/nvdimm/core.c:nd_uuid_store
  - drivers/nvdimm/core.c:nd_uuid_store
  - net/core/utils.c:in6_pton
  - net/core/utils.c:in4_pton
```
**Symbols:**

```
ffffffff81467890-ffffffff814678cc: hex_to_bin (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
int hex_to_bin(char ch);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/hexdump.c (ffffffff8146cfe0)
Location: lib/hexdump.c:28
Inline: True
Inline callers:
  - lib/hexdump.c:hex2bin
  - lib/hexdump.c:hex2bin
Direct callers:
  - kernel/debug/gdbstub.c:gdb_serial_stub
  - kernel/debug/gdbstub.c:gdb_serial_stub
  - kernel/debug/gdbstub.c:gdb_serial_stub
  - kernel/debug/gdbstub.c:kgdb_hex2long
  - kernel/debug/gdbstub.c:kgdb_hex2mem
  - kernel/debug/gdbstub.c:kgdb_hex2mem
  - security/selinux/selinuxfs.c:sel_write_create
  - security/selinux/selinuxfs.c:sel_write_create
  - lib/bitmap.c:__bitmap_parse
  - lib/string_helpers.c:string_unescape
  - lib/string_helpers.c:string_unescape
  - drivers/tty/vt/vt.c:do_con_trol
  - drivers/nvdimm/core.c:nd_uuid_store
  - drivers/nvdimm/core.c:nd_uuid_store
  - net/core/utils.c:in6_pton
  - net/core/utils.c:in4_pton
```
**Symbols:**

```
ffffffff8146cf90-ffffffff8146cfcf: hex_to_bin (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
int hex_to_bin(char ch);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/hexdump.c (ffffffff81499310)
Location: lib/hexdump.c:29
Inline: True
Inline callers:
  - lib/hexdump.c:hex2bin
  - lib/hexdump.c:hex2bin
Direct callers:
  - kernel/debug/gdbstub.c:gdb_serial_stub
  - kernel/debug/gdbstub.c:gdb_serial_stub
  - kernel/debug/gdbstub.c:gdb_serial_stub
  - kernel/debug/gdbstub.c:kgdb_hex2long
  - kernel/debug/gdbstub.c:kgdb_hex2mem
  - kernel/debug/gdbstub.c:kgdb_hex2mem
  - security/selinux/selinuxfs.c:sel_write_create
  - security/selinux/selinuxfs.c:sel_write_create
  - lib/bitmap.c:__bitmap_parse
  - lib/string_helpers.c:string_unescape
  - lib/string_helpers.c:string_unescape
  - drivers/tty/vt/vt.c:do_con_trol
  - drivers/nvdimm/core.c:nd_uuid_store
  - drivers/nvdimm/core.c:nd_uuid_store
  - net/core/utils.c:in6_pton
  - net/core/utils.c:in4_pton
```
**Symbols:**

```
ffffffff814992c0-ffffffff814992ff: hex_to_bin (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline, Transformation ⚠️</summary>

```c
int hex_to_bin(char ch);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In lib/hexdump.c (ffffffff814cec05)
Location: lib/hexdump.c:29
Inline: True
Inline callers:
  - lib/hexdump.c:hex2bin
  - lib/hexdump.c:hex2bin
Direct callers:
  - kernel/debug/gdbstub.c:gdb_serial_stub
  - kernel/debug/gdbstub.c:gdb_serial_stub
  - kernel/debug/gdbstub.c:gdb_serial_stub
  - kernel/debug/gdbstub.c:kgdb_hex2long
  - kernel/debug/gdbstub.c:kgdb_hex2mem
  - kernel/debug/gdbstub.c:kgdb_hex2mem
  - security/selinux/selinuxfs.c:sel_write_create
  - security/selinux/selinuxfs.c:sel_write_create
  - lib/bitmap.c:__bitmap_parse
  - lib/string_helpers.c:string_unescape
  - lib/string_helpers.c:string_unescape
  - lib/hexdump.c:hex2bin
  - lib/hexdump.c:hex2bin
  - drivers/tty/vt/vt.c:do_con_trol
  - drivers/nvdimm/core.c:nd_uuid_store
  - drivers/nvdimm/core.c:nd_uuid_store
  - net/core/utils.c:in6_pton
  - net/core/utils.c:in4_pton
```
**Symbols:**

```
ffffffff814ceba0-ffffffff814cebc6: hex_to_bin.part.0 (STB_LOCAL)
ffffffff814cebd0-ffffffff814cebed: hex_to_bin (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline, Transformation ⚠️</summary>

```c
int hex_to_bin(char ch);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In lib/hexdump.c (ffffffff814e34f5)
Location: lib/hexdump.c:29
Inline: True
Inline callers:
  - lib/hexdump.c:hex2bin
  - lib/hexdump.c:hex2bin
Direct callers:
  - kernel/debug/gdbstub.c:gdb_serial_stub
  - kernel/debug/gdbstub.c:gdb_serial_stub
  - kernel/debug/gdbstub.c:gdb_serial_stub
  - kernel/debug/gdbstub.c:kgdb_hex2long
  - kernel/debug/gdbstub.c:kgdb_hex2mem
  - kernel/debug/gdbstub.c:kgdb_hex2mem
  - security/selinux/selinuxfs.c:sel_write_create
  - security/selinux/selinuxfs.c:sel_write_create
  - lib/bitmap.c:__bitmap_parse
  - lib/string_helpers.c:string_unescape
  - lib/string_helpers.c:string_unescape
  - lib/hexdump.c:hex2bin
  - lib/hexdump.c:hex2bin
  - drivers/tty/vt/vt.c:do_con_trol
  - drivers/nvdimm/core.c:nd_uuid_store
  - drivers/nvdimm/core.c:nd_uuid_store
  - net/core/utils.c:in6_pton
  - net/core/utils.c:in4_pton
```
**Symbols:**

```
ffffffff814e3490-ffffffff814e34b6: hex_to_bin.part.0 (STB_LOCAL)
ffffffff814e34c0-ffffffff814e34dd: hex_to_bin (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline, Transformation ⚠️</summary>

```c
int hex_to_bin(char ch);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In lib/hexdump.c (ffffffff8150f8dd)
Location: lib/hexdump.c:25
Inline: True
Inline callers:
  - lib/hexdump.c:hex2bin
  - lib/hexdump.c:hex2bin
Direct callers:
  - kernel/debug/gdbstub.c:gdb_serial_stub
  - kernel/debug/gdbstub.c:gdb_serial_stub
  - kernel/debug/gdbstub.c:gdb_serial_stub
  - kernel/debug/gdbstub.c:kgdb_hex2long
  - kernel/debug/gdbstub.c:kgdb_hex2mem
  - kernel/debug/gdbstub.c:kgdb_hex2mem
  - security/selinux/selinuxfs.c:sel_write_create
  - security/selinux/selinuxfs.c:sel_write_create
  - lib/bitmap.c:__bitmap_parse
  - lib/string_helpers.c:string_unescape
  - lib/string_helpers.c:string_unescape
  - lib/hexdump.c:hex2bin
  - lib/hexdump.c:hex2bin
  - drivers/tty/vt/vt.c:do_con_trol
  - drivers/nvdimm/core.c:nd_uuid_store
  - drivers/nvdimm/core.c:nd_uuid_store
  - net/core/utils.c:in6_pton
  - net/core/utils.c:in4_pton
```
**Symbols:**

```
ffffffff8150f830-ffffffff8150f857: hex_to_bin.part.0 (STB_LOCAL)
ffffffff8150f860-ffffffff8150f880: hex_to_bin (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
int hex_to_bin(char ch);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/hexdump.c (ffffffff8152d1f8)
Location: lib/hexdump.c:25
Inline: True
Inline callers:
  - lib/hexdump.c:hex2bin
  - lib/hexdump.c:hex2bin
Direct callers:
  - kernel/debug/gdbstub.c:gdb_serial_stub
  - kernel/debug/gdbstub.c:gdb_serial_stub
  - kernel/debug/gdbstub.c:gdb_serial_stub
  - kernel/debug/gdbstub.c:kgdb_hex2long
  - kernel/debug/gdbstub.c:kgdb_hex2mem
  - kernel/debug/gdbstub.c:kgdb_hex2mem
  - security/selinux/selinuxfs.c:sel_write_create
  - security/selinux/selinuxfs.c:sel_write_create
  - lib/bitmap.c:__bitmap_parse
  - lib/string_helpers.c:string_unescape
  - lib/string_helpers.c:string_unescape
  - drivers/tty/vt/vt.c:do_con_trol
  - drivers/nvdimm/core.c:nd_uuid_store
  - drivers/nvdimm/core.c:nd_uuid_store
  - net/core/utils.c:in6_pton
  - net/core/utils.c:in4_pton
```
**Symbols:**

```
ffffffff8152d130-ffffffff8152d16b: hex_to_bin (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
int hex_to_bin(char ch);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/hexdump.c (ffffffff815914e0)
Location: lib/hexdump.c:25
Inline: True
Inline callers:
  - lib/hexdump.c:hex2bin
  - lib/hexdump.c:hex2bin
Direct callers:
  - kernel/debug/gdbstub.c:gdb_serial_stub
  - kernel/debug/gdbstub.c:gdb_serial_stub
  - kernel/debug/gdbstub.c:gdb_cmd_reg_set
  - kernel/debug/gdbstub.c:kgdb_hex2long
  - security/selinux/selinuxfs.c:sel_write_create
  - security/selinux/selinuxfs.c:sel_write_create
  - lib/bitmap.c:bitmap_parse
  - lib/bitmap.c:bitmap_parse
  - lib/string_helpers.c:string_unescape
  - lib/string_helpers.c:string_unescape
  - lib/net_utils.c:mac_pton
  - lib/net_utils.c:mac_pton
  - drivers/tty/vt/vt.c:do_con_trol
  - drivers/firmware/efi/vars.c:validate_load_option
  - net/core/utils.c:in6_pton
  - net/core/utils.c:in4_pton
```
**Symbols:**

```
ffffffff81590e30-ffffffff81590e67: hex_to_bin (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
int hex_to_bin(char ch);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/hexdump.c (ffffffff815ae090)
Location: lib/hexdump.c:26
Inline: True
Inline callers:
  - lib/hexdump.c:hex2bin
  - lib/hexdump.c:hex2bin
Direct callers:
  - kernel/debug/gdbstub.c:gdb_serial_stub
  - kernel/debug/gdbstub.c:gdb_serial_stub
  - kernel/debug/gdbstub.c:gdb_cmd_reg_set
  - kernel/debug/gdbstub.c:kgdb_hex2long
  - security/selinux/selinuxfs.c:sel_write_create
  - security/selinux/selinuxfs.c:sel_write_create
  - lib/bitmap.c:bitmap_parse
  - lib/bitmap.c:bitmap_parse
  - lib/string_helpers.c:string_unescape
  - lib/string_helpers.c:string_unescape
  - lib/net_utils.c:mac_pton
  - lib/net_utils.c:mac_pton
  - drivers/tty/vt/vt.c:do_con_trol
  - drivers/firmware/efi/vars.c:validate_load_option
  - net/core/utils.c:in6_pton
  - net/core/utils.c:in4_pton
```
**Symbols:**

```
ffffffff815ad9d0-ffffffff815ada07: hex_to_bin (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
int hex_to_bin(char ch);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/hexdump.c (ffffffff815b8d23)
Location: lib/hexdump.c:26
Inline: True
Inline callers:
  - lib/hexdump.c:hex2bin
  - lib/hexdump.c:hex2bin
Direct callers:
  - kernel/debug/gdbstub.c:gdb_serial_stub
  - kernel/debug/gdbstub.c:gdb_serial_stub
  - kernel/debug/gdbstub.c:gdb_serial_stub
  - kernel/debug/gdbstub.c:gdb_serial_stub
  - kernel/debug/gdbstub.c:gdb_serial_stub
  - kernel/debug/gdbstub.c:kgdb_hex2long
  - security/selinux/selinuxfs.c:sel_write_create
  - security/selinux/selinuxfs.c:sel_write_create
  - lib/bitmap.c:bitmap_parse
  - lib/bitmap.c:bitmap_parse
  - lib/string_helpers.c:string_unescape
  - lib/string_helpers.c:string_unescape
  - lib/net_utils.c:mac_pton
  - lib/net_utils.c:mac_pton
  - drivers/tty/vt/vt.c:do_con_trol
  - drivers/nvdimm/core.c:nd_uuid_store
  - drivers/nvdimm/core.c:nd_uuid_store
  - drivers/firmware/efi/vars.c:validate_load_option
  - net/core/utils.c:in6_pton
  - net/core/utils.c:in4_pton
```
**Symbols:**

```
ffffffff815b8670-ffffffff815b86a7: hex_to_bin (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
int hex_to_bin(char ch);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/hexdump.c (ffffffff8161f573)
Location: lib/hexdump.c:26
Inline: True
Inline callers:
  - lib/hexdump.c:hex2bin
  - lib/hexdump.c:hex2bin
Direct callers:
  - kernel/debug/gdbstub.c:gdb_serial_stub
  - kernel/debug/gdbstub.c:gdb_serial_stub
  - kernel/debug/gdbstub.c:gdb_serial_stub
  - kernel/debug/gdbstub.c:gdb_serial_stub
  - kernel/debug/gdbstub.c:gdb_serial_stub
  - kernel/debug/gdbstub.c:kgdb_hex2long
  - security/selinux/selinuxfs.c:sel_write_create
  - security/selinux/selinuxfs.c:sel_write_create
  - lib/bitmap.c:bitmap_parse
  - lib/bitmap.c:bitmap_parse
  - lib/string_helpers.c:string_unescape
  - lib/string_helpers.c:string_unescape
  - lib/net_utils.c:mac_pton
  - lib/net_utils.c:mac_pton
  - drivers/tty/vt/vt.c:do_con_trol
  - drivers/nvdimm/core.c:nd_uuid_store
  - drivers/nvdimm/core.c:nd_uuid_store
  - drivers/firmware/efi/vars.c:validate_load_option
  - net/core/utils.c:in6_pton
  - net/core/utils.c:in4_pton
```
**Symbols:**

```
ffffffff8161eec0-ffffffff8161eef7: hex_to_bin (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
int hex_to_bin(unsigned char ch);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/hexdump.c (ffffffff816ed831)
Location: lib/hexdump.c:46
Inline: True
Inline callers:
  - lib/hexdump.c:hex2bin
  - lib/hexdump.c:hex2bin
Direct callers:
  - kernel/debug/gdbstub.c:gdb_serial_stub
  - kernel/debug/gdbstub.c:gdb_serial_stub
  - kernel/debug/gdbstub.c:gdb_serial_stub
  - kernel/debug/gdbstub.c:gdb_serial_stub
  - kernel/debug/gdbstub.c:gdb_serial_stub
  - kernel/debug/gdbstub.c:kgdb_hex2long
  - security/selinux/selinuxfs.c:sel_write_create
  - security/selinux/selinuxfs.c:sel_write_create
  - lib/bitmap.c:bitmap_parse
  - lib/bitmap.c:bitmap_parse
  - lib/string_helpers.c:string_unescape
  - lib/string_helpers.c:string_unescape
  - lib/net_utils.c:mac_pton
  - lib/net_utils.c:mac_pton
  - drivers/tty/vt/vt.c:do_con_trol
  - drivers/firmware/efi/vars.c:validate_load_option
  - net/core/utils.c:in6_pton
  - net/core/utils.c:in4_pton
```
**Symbols:**

```
ffffffff816ed0c0-ffffffff816ed101: hex_to_bin (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
int hex_to_bin(unsigned char ch);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/hexdump.c (ffffffff817de231)
Location: lib/hexdump.c:46
Inline: True
Inline callers:
  - lib/hexdump.c:hex2bin
  - lib/hexdump.c:hex2bin
Direct callers:
  - kernel/debug/gdbstub.c:gdb_serial_stub
  - kernel/debug/gdbstub.c:gdb_serial_stub
  - kernel/debug/gdbstub.c:gdb_serial_stub
  - kernel/debug/gdbstub.c:gdb_serial_stub
  - kernel/debug/gdbstub.c:gdb_serial_stub
  - kernel/debug/gdbstub.c:kgdb_hex2long
  - fs/efivarfs/vars.c:validate_load_option
  - security/selinux/selinuxfs.c:sel_write_create
  - security/selinux/selinuxfs.c:sel_write_create
  - lib/bitmap.c:bitmap_parse
  - lib/bitmap.c:bitmap_parse
  - lib/string_helpers.c:string_unescape
  - lib/string_helpers.c:string_unescape
  - lib/net_utils.c:mac_pton
  - lib/net_utils.c:mac_pton
  - drivers/tty/vt/vt.c:do_con_trol
  - net/core/utils.c:in6_pton
  - net/core/utils.c:in4_pton
```
**Symbols:**

```
ffffffff817dda40-ffffffff817dda81: hex_to_bin (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
int hex_to_bin(unsigned char ch);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/hexdump.c (ffffffff8181da21)
Location: lib/hexdump.c:46
Inline: True
Inline callers:
  - lib/hexdump.c:hex2bin
  - lib/hexdump.c:hex2bin
Direct callers:
  - kernel/debug/gdbstub.c:gdb_serial_stub
  - kernel/debug/gdbstub.c:gdb_serial_stub
  - kernel/debug/gdbstub.c:gdb_serial_stub
  - kernel/debug/gdbstub.c:gdb_serial_stub
  - kernel/debug/gdbstub.c:gdb_serial_stub
  - kernel/debug/gdbstub.c:kgdb_hex2long
  - fs/efivarfs/vars.c:validate_load_option
  - security/selinux/selinuxfs.c:sel_write_create
  - security/selinux/selinuxfs.c:sel_write_create
  - lib/bitmap.c:bitmap_parse
  - lib/bitmap.c:bitmap_parse
  - lib/string_helpers.c:string_unescape
  - lib/string_helpers.c:string_unescape
  - lib/net_utils.c:mac_pton
  - lib/net_utils.c:mac_pton
  - drivers/tty/vt/vt.c:do_con_trol
  - net/core/utils.c:in6_pton
  - net/core/utils.c:in4_pton
```
**Symbols:**

```
ffffffff8181d250-ffffffff8181d291: hex_to_bin (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
int hex_to_bin(unsigned char ch);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/hexdump.c (ffffffff81863891)
Location: lib/hexdump.c:46
Inline: True
Inline callers:
  - lib/hexdump.c:hex2bin
  - lib/hexdump.c:hex2bin
Direct callers:
  - kernel/debug/gdbstub.c:gdb_serial_stub
  - kernel/debug/gdbstub.c:gdb_serial_stub
  - kernel/debug/gdbstub.c:gdb_serial_stub
  - kernel/debug/gdbstub.c:gdb_serial_stub
  - kernel/debug/gdbstub.c:gdb_serial_stub
  - kernel/debug/gdbstub.c:kgdb_hex2long
  - fs/efivarfs/vars.c:validate_load_option
  - security/selinux/selinuxfs.c:sel_write_create
  - security/selinux/selinuxfs.c:sel_write_create
  - lib/bitmap-str.c:bitmap_parse
  - lib/bitmap-str.c:bitmap_parse
  - lib/string_helpers.c:string_unescape
  - lib/string_helpers.c:string_unescape
  - lib/net_utils.c:mac_pton
  - lib/net_utils.c:mac_pton
  - drivers/tty/vt/vt.c:do_con_trol
  - net/core/utils.c:in6_pton
  - net/core/utils.c:in4_pton
```
**Symbols:**

```
ffffffff818630c0-ffffffff81863101: hex_to_bin (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Selective Inline, Transformation ⚠️</summary>

```c
int hex_to_bin(char ch);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In lib/hexdump.c (ffff800010639a18)
Location: lib/hexdump.c:25
Inline: True
Inline callers:
  - lib/hexdump.c:hex2bin
  - lib/hexdump.c:hex2bin
Direct callers:
  - kernel/debug/gdbstub.c:gdb_serial_stub
  - kernel/debug/gdbstub.c:gdb_serial_stub
  - kernel/debug/gdbstub.c:gdb_serial_stub
  - kernel/debug/gdbstub.c:kgdb_hex2long
  - kernel/debug/gdbstub.c:kgdb_hex2mem
  - kernel/debug/gdbstub.c:kgdb_hex2mem
  - security/selinux/selinuxfs.c:sel_write_create
  - security/selinux/selinuxfs.c:sel_write_create
  - lib/bitmap.c:__bitmap_parse
  - lib/string_helpers.c:string_unescape
  - lib/string_helpers.c:string_unescape
  - lib/hexdump.c:hex2bin
  - lib/hexdump.c:hex2bin
  - drivers/tty/vt/vt.c:do_con_trol
  - drivers/nvdimm/core.c:nd_uuid_store
  - drivers/nvdimm/core.c:nd_uuid_store
  - net/core/utils.c:in6_pton
  - net/core/utils.c:in4_pton
```
**Symbols:**

```
ffff800010639950-ffff800010639988: hex_to_bin.part.0 (STB_LOCAL)
ffff800010639988-ffff8000106399b8: hex_to_bin (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline, Transformation ⚠️</summary>

```c
int hex_to_bin(char ch);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In lib/hexdump.c (c07df3b4)
Location: lib/hexdump.c:25
Inline: True
Inline callers:
  - lib/hexdump.c:hex2bin
  - lib/hexdump.c:hex2bin
Direct callers:
  - kernel/debug/gdbstub.c:gdb_serial_stub
  - kernel/debug/gdbstub.c:gdb_serial_stub
  - kernel/debug/gdbstub.c:gdb_serial_stub
  - kernel/debug/gdbstub.c:kgdb_hex2long
  - kernel/debug/gdbstub.c:kgdb_hex2mem
  - kernel/debug/gdbstub.c:kgdb_hex2mem
  - security/selinux/selinuxfs.c:sel_write_create
  - security/selinux/selinuxfs.c:sel_write_create
  - lib/bitmap.c:__bitmap_parse
  - lib/string_helpers.c:string_unescape
  - lib/string_helpers.c:string_unescape
  - lib/hexdump.c:hex2bin
  - lib/hexdump.c:hex2bin
  - drivers/tty/vt/vt.c:do_con_trol
  - net/core/utils.c:in6_pton
  - net/core/utils.c:in4_pton
```
**Symbols:**

```
c07df31c-c07df354: hex_to_bin.part.0 (STB_LOCAL)
c07df354-c07df380: hex_to_bin (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline, Transformation ⚠️</summary>

```c
int hex_to_bin(char ch);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In lib/hexdump.c (c0000000007e064c)
Location: lib/hexdump.c:25
Inline: True
Inline callers:
  - lib/hexdump.c:hex2bin
  - lib/hexdump.c:hex2bin
Direct callers:
  - kernel/debug/gdbstub.c:gdb_serial_stub
  - kernel/debug/gdbstub.c:gdb_serial_stub
  - kernel/debug/gdbstub.c:gdb_serial_stub
  - kernel/debug/gdbstub.c:kgdb_hex2long
  - kernel/debug/gdbstub.c:kgdb_hex2mem
  - kernel/debug/gdbstub.c:kgdb_hex2mem
  - security/selinux/selinuxfs.c:sel_write_create
  - security/selinux/selinuxfs.c:sel_write_create
  - lib/bitmap.c:__bitmap_parse
  - lib/string_helpers.c:string_unescape
  - lib/string_helpers.c:string_unescape
  - lib/hexdump.c:hex2bin
  - lib/hexdump.c:hex2bin
  - lib/hexdump.c:hex2bin
  - drivers/tty/vt/vt.c:do_con_trol
  - drivers/nvdimm/core.c:nd_uuid_store
  - drivers/nvdimm/core.c:nd_uuid_store
  - net/core/utils.c:in6_pton
  - net/core/utils.c:in4_pton
```
**Symbols:**

```
c0000000007e0540-c0000000007e0588: hex_to_bin.part.0 (STB_LOCAL)
c0000000007e0590-c0000000007e05b8: hex_to_bin (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline, Transformation ⚠️</summary>

```c
int hex_to_bin(char ch);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In lib/hexdump.c (ffffffe0004664d0)
Location: lib/hexdump.c:25
Inline: True
Inline callers:
  - lib/hexdump.c:hex2bin
  - lib/hexdump.c:hex2bin
Direct callers:
  - security/selinux/selinuxfs.c:sel_write_create
  - security/selinux/selinuxfs.c:sel_write_create
  - lib/bitmap.c:__bitmap_parse
  - lib/string_helpers.c:string_unescape
  - lib/string_helpers.c:string_unescape
  - lib/hexdump.c:hex2bin
  - lib/hexdump.c:hex2bin
  - lib/hexdump.c:hex2bin
  - drivers/tty/vt/vt.c:do_con_trol
  - drivers/nvdimm/core.c:nd_uuid_store
  - drivers/nvdimm/core.c:nd_uuid_store
  - net/core/utils.c:in6_pton
  - net/core/utils.c:in4_pton
```
**Symbols:**

```
ffffffe00046643c-ffffffe000466478: hex_to_bin.part.0 (STB_LOCAL)
ffffffe000466478-ffffffe0004664a4: hex_to_bin (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Selective Inline ⚠️</summary>

```c
int hex_to_bin(char ch);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/hexdump.c (ffffffff815257d8)
Location: lib/hexdump.c:25
Inline: True
Inline callers:
  - lib/hexdump.c:hex2bin
  - lib/hexdump.c:hex2bin
Direct callers:
  - kernel/debug/gdbstub.c:gdb_serial_stub
  - kernel/debug/gdbstub.c:gdb_serial_stub
  - kernel/debug/gdbstub.c:gdb_serial_stub
  - kernel/debug/gdbstub.c:kgdb_hex2long
  - kernel/debug/gdbstub.c:kgdb_hex2mem
  - kernel/debug/gdbstub.c:kgdb_hex2mem
  - security/selinux/selinuxfs.c:sel_write_create
  - security/selinux/selinuxfs.c:sel_write_create
  - lib/bitmap.c:__bitmap_parse
  - lib/string_helpers.c:string_unescape
  - lib/string_helpers.c:string_unescape
  - drivers/tty/vt/vt.c:do_con_trol
  - drivers/nvdimm/core.c:nd_uuid_store
  - drivers/nvdimm/core.c:nd_uuid_store
  - net/core/utils.c:in6_pton
  - net/core/utils.c:in4_pton
```
**Symbols:**

```
ffffffff81525710-ffffffff8152574b: hex_to_bin (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
int hex_to_bin(char ch);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/hexdump.c (ffffffff81515ab8)
Location: lib/hexdump.c:25
Inline: True
Inline callers:
  - lib/hexdump.c:hex2bin
  - lib/hexdump.c:hex2bin
Direct callers:
  - kernel/debug/gdbstub.c:gdb_serial_stub
  - kernel/debug/gdbstub.c:gdb_serial_stub
  - kernel/debug/gdbstub.c:gdb_serial_stub
  - kernel/debug/gdbstub.c:kgdb_hex2long
  - kernel/debug/gdbstub.c:kgdb_hex2mem
  - kernel/debug/gdbstub.c:kgdb_hex2mem
  - security/selinux/selinuxfs.c:sel_write_create
  - security/selinux/selinuxfs.c:sel_write_create
  - lib/bitmap.c:__bitmap_parse
  - lib/string_helpers.c:string_unescape
  - lib/string_helpers.c:string_unescape
  - drivers/tty/vt/vt.c:do_con_trol
  - drivers/nvdimm/core.c:nd_uuid_store
  - drivers/nvdimm/core.c:nd_uuid_store
  - drivers/scsi/scsi_transport_fc.c:fc_parse_wwn
  - net/core/utils.c:in6_pton
  - net/core/utils.c:in4_pton
```
**Symbols:**

```
ffffffff815159f0-ffffffff81515a2b: hex_to_bin (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
int hex_to_bin(char ch);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/hexdump.c (ffffffff81521868)
Location: lib/hexdump.c:25
Inline: True
Inline callers:
  - lib/hexdump.c:hex2bin
  - lib/hexdump.c:hex2bin
Direct callers:
  - kernel/debug/gdbstub.c:gdb_serial_stub
  - kernel/debug/gdbstub.c:gdb_serial_stub
  - kernel/debug/gdbstub.c:gdb_serial_stub
  - kernel/debug/gdbstub.c:kgdb_hex2long
  - kernel/debug/gdbstub.c:kgdb_hex2mem
  - kernel/debug/gdbstub.c:kgdb_hex2mem
  - security/selinux/selinuxfs.c:sel_write_create
  - security/selinux/selinuxfs.c:sel_write_create
  - lib/bitmap.c:__bitmap_parse
  - lib/string_helpers.c:string_unescape
  - lib/string_helpers.c:string_unescape
  - drivers/tty/vt/vt.c:do_con_trol
  - drivers/nvdimm/core.c:nd_uuid_store
  - drivers/nvdimm/core.c:nd_uuid_store
  - net/core/utils.c:in6_pton
  - net/core/utils.c:in4_pton
```
**Symbols:**

```
ffffffff815217a0-ffffffff815217db: hex_to_bin (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
int hex_to_bin(char ch);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/hexdump.c (ffffffff8153b1e8)
Location: lib/hexdump.c:25
Inline: True
Inline callers:
  - lib/hexdump.c:hex2bin
  - lib/hexdump.c:hex2bin
Direct callers:
  - kernel/debug/gdbstub.c:gdb_serial_stub
  - kernel/debug/gdbstub.c:gdb_serial_stub
  - kernel/debug/gdbstub.c:gdb_serial_stub
  - kernel/debug/gdbstub.c:kgdb_hex2long
  - kernel/debug/gdbstub.c:kgdb_hex2mem
  - kernel/debug/gdbstub.c:kgdb_hex2mem
  - security/selinux/selinuxfs.c:sel_write_create
  - security/selinux/selinuxfs.c:sel_write_create
  - lib/bitmap.c:__bitmap_parse
  - lib/string_helpers.c:string_unescape
  - lib/string_helpers.c:string_unescape
  - drivers/tty/vt/vt.c:do_con_trol
  - drivers/nvdimm/core.c:nd_uuid_store
  - drivers/nvdimm/core.c:nd_uuid_store
  - net/core/utils.c:in6_pton
  - net/core/utils.c:in4_pton
```
**Symbols:**

```
ffffffff8153b120-ffffffff8153b15b: hex_to_bin (STB_GLOBAL)
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
<details>
<summary>Changed between <code>5.15</code> and <code>5.19</code> ⚠️</summary>
<ul>
<li>
<b>Param type changed. </b>
<code>char ch</code> ➡️ <code>unsigned char ch</code>
</li>
</ul>
</details>
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
<li>
No changes between <code>amd64</code> and <code>armhf</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>ppc64el</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>riscv64</code> ✅
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
