# Function: <code>hex_byte_pack</code>

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
In kernel/debug/gdbstub.c (ffffffff811307ca)
Location: include/linux/kernel.h:499
Inline: True
Inline callers:
  - kernel/debug/gdbstub.c:pack_threadid
  - kernel/debug/gdbstub.c:pack_threadid
  - kernel/debug/gdbstub.c:gdbstub_msg_write
  - kernel/debug/gdbstub.c:kgdb_mem2hex
  - kernel/debug/gdbstub.c:gdb_serial_stub
  - kernel/debug/gdbstub.c:gdb_serial_stub
```
```
In fs/fat/dir.c (ffffffff812f7b7d)
Location: include/linux/kernel.h:499
Inline: True
Inline callers:
  - fs/fat/dir.c:fat_parse_short
  - fs/fat/dir.c:fat_parse_short
  - fs/fat/dir.c:fat_search_long
  - fs/fat/dir.c:fat_search_long
  - fs/fat/dir.c:__fat_readdir
  - fs/fat/dir.c:__fat_readdir
```
```
In security/keys/trusted.c (ffffffff813368b2)
Location: include/linux/kernel.h:499
Inline: True
Inline callers:
  - security/keys/trusted.c:trusted_read
```
```
In security/keys/encrypted-keys/encrypted.c (ffffffff81339987)
Location: include/linux/kernel.h:499
Inline: True
Inline callers:
  - security/keys/encrypted-keys/encrypted.c:encrypted_read
```
```
In security/integrity/ima/ima_api.c (ffffffff81398c05)
Location: include/linux/kernel.h:499
Inline: True
Inline callers:
  - security/integrity/ima/ima_api.c:ima_audit_measurement
```
```
In lib/vsprintf.c (ffffffff813f261d)
Location: include/linux/kernel.h:499
Inline: True
Inline callers:
  - lib/vsprintf.c:ip6_string
  - lib/vsprintf.c:ip6_string
  - lib/vsprintf.c:ip6_compressed_string
  - lib/vsprintf.c:ip6_compressed_string
  - lib/vsprintf.c:ip6_compressed_string
```
```
In lib/hexdump.c (ffffffff814015cf)
Location: include/linux/kernel.h:499
Inline: True
Inline callers:
  - lib/hexdump.c:bin2hex
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
In kernel/debug/gdbstub.c (ffffffff81139e5d)
Location: include/linux/kernel.h:517
Inline: True
Inline callers:
  - kernel/debug/gdbstub.c:gdb_serial_stub
  - kernel/debug/gdbstub.c:gdb_serial_stub
  - kernel/debug/gdbstub.c:pack_threadid
  - kernel/debug/gdbstub.c:pack_threadid
  - kernel/debug/gdbstub.c:kgdb_mem2hex
  - kernel/debug/gdbstub.c:gdbstub_msg_write
```
```
In fs/fat/dir.c (ffffffff8132c3a3)
Location: include/linux/kernel.h:517
Inline: True
Inline callers:
  - fs/fat/dir.c:__fat_readdir
  - fs/fat/dir.c:__fat_readdir
  - fs/fat/dir.c:fat_search_long
  - fs/fat/dir.c:fat_search_long
  - fs/fat/dir.c:fat_parse_short
  - fs/fat/dir.c:fat_parse_short
```
```
In security/keys/trusted.c (ffffffff8136be80)
Location: include/linux/kernel.h:517
Inline: True
Inline callers:
  - security/keys/trusted.c:trusted_read
```
```
In security/keys/encrypted-keys/encrypted.c (ffffffff8136f077)
Location: include/linux/kernel.h:517
Inline: True
Inline callers:
  - security/keys/encrypted-keys/encrypted.c:encrypted_read
```
```
In security/integrity/ima/ima_api.c (ffffffff813d51cc)
Location: include/linux/kernel.h:517
Inline: True
Inline callers:
  - security/integrity/ima/ima_api.c:ima_audit_measurement
```
```
In lib/vsprintf.c (ffffffff81439ced)
Location: include/linux/kernel.h:517
Inline: True
Inline callers:
  - lib/vsprintf.c:uuid_string
  - lib/vsprintf.c:ip6_string
  - lib/vsprintf.c:ip6_string
  - lib/vsprintf.c:ip6_compressed_string
  - lib/vsprintf.c:ip6_compressed_string
  - lib/vsprintf.c:ip6_compressed_string
  - lib/vsprintf.c:mac_address_string
```
```
In lib/hexdump.c (ffffffff81448fb3)
Location: include/linux/kernel.h:517
Inline: True
Inline callers:
  - lib/hexdump.c:bin2hex
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
In kernel/debug/gdbstub.c (ffffffff81143bef)
Location: include/linux/kernel.h:528
Inline: True
Inline callers:
  - kernel/debug/gdbstub.c:gdb_serial_stub
  - kernel/debug/gdbstub.c:gdb_serial_stub
  - kernel/debug/gdbstub.c:pack_threadid
  - kernel/debug/gdbstub.c:pack_threadid
  - kernel/debug/gdbstub.c:kgdb_mem2hex
  - kernel/debug/gdbstub.c:gdbstub_msg_write
```
```
In fs/fat/dir.c (ffffffff813420e3)
Location: include/linux/kernel.h:528
Inline: True
Inline callers:
  - fs/fat/dir.c:__fat_readdir
  - fs/fat/dir.c:__fat_readdir
  - fs/fat/dir.c:fat_search_long
  - fs/fat/dir.c:fat_search_long
  - fs/fat/dir.c:fat_parse_short
  - fs/fat/dir.c:fat_parse_short
```
```
In security/keys/trusted.c (ffffffff813826a0)
Location: include/linux/kernel.h:528
Inline: True
Inline callers:
  - security/keys/trusted.c:trusted_read
```
```
In security/keys/encrypted-keys/encrypted.c (ffffffff813858a7)
Location: include/linux/kernel.h:528
Inline: True
Inline callers:
  - security/keys/encrypted-keys/encrypted.c:encrypted_read
```
```
In security/integrity/ima/ima_api.c (ffffffff813ecc1c)
Location: include/linux/kernel.h:528
Inline: True
Inline callers:
  - security/integrity/ima/ima_api.c:ima_audit_measurement
```
```
In lib/vsprintf.c (ffffffff81456ccd)
Location: include/linux/kernel.h:528
Inline: True
Inline callers:
  - lib/vsprintf.c:uuid_string
  - lib/vsprintf.c:ip6_string
  - lib/vsprintf.c:ip6_string
  - lib/vsprintf.c:ip6_compressed_string
  - lib/vsprintf.c:ip6_compressed_string
  - lib/vsprintf.c:ip6_compressed_string
  - lib/vsprintf.c:mac_address_string
```
```
In lib/hexdump.c (ffffffff814679a3)
Location: include/linux/kernel.h:528
Inline: True
Inline callers:
  - lib/hexdump.c:bin2hex
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
In kernel/debug/gdbstub.c (ffffffff811456ab)
Location: include/linux/kernel.h:546
Inline: True
Inline callers:
  - kernel/debug/gdbstub.c:gdb_serial_stub
  - kernel/debug/gdbstub.c:gdb_serial_stub
  - kernel/debug/gdbstub.c:pack_threadid
  - kernel/debug/gdbstub.c:pack_threadid
  - kernel/debug/gdbstub.c:kgdb_mem2hex
  - kernel/debug/gdbstub.c:gdbstub_msg_write
```
```
In fs/fat/dir.c (ffffffff813568a9)
Location: include/linux/kernel.h:546
Inline: True
Inline callers:
  - fs/fat/dir.c:__fat_readdir
  - fs/fat/dir.c:__fat_readdir
  - fs/fat/dir.c:fat_search_long
  - fs/fat/dir.c:fat_search_long
  - fs/fat/dir.c:fat_parse_short
  - fs/fat/dir.c:fat_parse_short
```
```
In security/keys/trusted.c (ffffffff81396d90)
Location: include/linux/kernel.h:546
Inline: True
Inline callers:
  - security/keys/trusted.c:trusted_read
```
```
In security/keys/encrypted-keys/encrypted.c (ffffffff8139a0f8)
Location: include/linux/kernel.h:546
Inline: True
Inline callers:
  - security/keys/encrypted-keys/encrypted.c:encrypted_read
```
```
In security/integrity/ima/ima_api.c (ffffffff813f9012)
Location: include/linux/kernel.h:546
Inline: True
Inline callers:
  - security/integrity/ima/ima_api.c:ima_audit_measurement
```
```
In lib/hexdump.c (ffffffff8146d0a3)
Location: include/linux/kernel.h:546
Inline: True
Inline callers:
  - lib/hexdump.c:bin2hex
```
```
In lib/vsprintf.c (ffffffff818f854e)
Location: include/linux/kernel.h:546
Inline: True
Inline callers:
  - lib/vsprintf.c:uuid_string
  - lib/vsprintf.c:ip6_string
  - lib/vsprintf.c:ip6_string
  - lib/vsprintf.c:ip6_compressed_string
  - lib/vsprintf.c:ip6_compressed_string
  - lib/vsprintf.c:ip6_compressed_string
  - lib/vsprintf.c:mac_address_string
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
In kernel/debug/gdbstub.c (ffffffff81152129)
Location: include/linux/kernel.h:584
Inline: True
Inline callers:
  - kernel/debug/gdbstub.c:gdb_serial_stub
  - kernel/debug/gdbstub.c:gdb_serial_stub
  - kernel/debug/gdbstub.c:pack_threadid
  - kernel/debug/gdbstub.c:pack_threadid
  - kernel/debug/gdbstub.c:kgdb_mem2hex
  - kernel/debug/gdbstub.c:gdbstub_msg_write
```
```
In fs/fat/dir.c (ffffffff8137b4e1)
Location: include/linux/kernel.h:584
Inline: True
Inline callers:
  - fs/fat/dir.c:__fat_readdir
  - fs/fat/dir.c:__fat_readdir
  - fs/fat/dir.c:fat_search_long
  - fs/fat/dir.c:fat_search_long
  - fs/fat/dir.c:fat_parse_short
  - fs/fat/dir.c:fat_parse_short
```
```
In security/keys/trusted.c (ffffffff813bc571)
Location: include/linux/kernel.h:584
Inline: True
Inline callers:
  - security/keys/trusted.c:trusted_read
```
```
In security/keys/encrypted-keys/encrypted.c (ffffffff813bf788)
Location: include/linux/kernel.h:584
Inline: True
Inline callers:
  - security/keys/encrypted-keys/encrypted.c:encrypted_read
```
```
In security/integrity/ima/ima_api.c (ffffffff814214a2)
Location: include/linux/kernel.h:584
Inline: True
Inline callers:
  - security/integrity/ima/ima_api.c:ima_audit_measurement
```
```
In lib/hexdump.c (ffffffff814993d3)
Location: include/linux/kernel.h:584
Inline: True
Inline callers:
  - lib/hexdump.c:bin2hex
```
```
In lib/vsprintf.c (ffffffff8197f00e)
Location: include/linux/kernel.h:584
Inline: True
Inline callers:
  - lib/vsprintf.c:uuid_string
  - lib/vsprintf.c:ip6_string
  - lib/vsprintf.c:ip6_string
  - lib/vsprintf.c:ip6_compressed_string
  - lib/vsprintf.c:ip6_compressed_string
  - lib/vsprintf.c:ip6_compressed_string
  - lib/vsprintf.c:mac_address_string
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
In kernel/debug/gdbstub.c (ffffffff81160c92)
Location: include/linux/kernel.h:614
Inline: True
Inline callers:
  - kernel/debug/gdbstub.c:gdb_serial_stub
  - kernel/debug/gdbstub.c:gdb_serial_stub
  - kernel/debug/gdbstub.c:pack_threadid
  - kernel/debug/gdbstub.c:pack_threadid
  - kernel/debug/gdbstub.c:kgdb_mem2hex
  - kernel/debug/gdbstub.c:gdbstub_msg_write
```
```
In fs/fat/dir.c (ffffffff813aa00b)
Location: include/linux/kernel.h:614
Inline: True
Inline callers:
  - fs/fat/dir.c:__fat_readdir
  - fs/fat/dir.c:__fat_readdir
  - fs/fat/dir.c:fat_search_long
  - fs/fat/dir.c:fat_search_long
  - fs/fat/dir.c:fat_parse_short
  - fs/fat/dir.c:fat_parse_short
```
```
In security/keys/trusted.c (ffffffff813ee285)
Location: include/linux/kernel.h:614
Inline: True
Inline callers:
  - security/keys/trusted.c:trusted_read
```
```
In security/keys/encrypted-keys/encrypted.c (ffffffff813f0546)
Location: include/linux/kernel.h:614
Inline: True
Inline callers:
  - security/keys/encrypted-keys/encrypted.c:encrypted_read
```
```
In security/integrity/ima/ima_api.c (ffffffff81453a0b)
Location: include/linux/kernel.h:614
Inline: True
Inline callers:
  - security/integrity/ima/ima_api.c:ima_audit_measurement
```
```
In lib/hexdump.c (ffffffff814ce5db)
Location: include/linux/kernel.h:614
Inline: True
Inline callers:
  - lib/hexdump.c:bin2hex
```
```
In lib/vsprintf.c (ffffffff819db588)
Location: include/linux/kernel.h:614
Inline: True
Inline callers:
  - lib/vsprintf.c:uuid_string
  - lib/vsprintf.c:ip6_string
  - lib/vsprintf.c:ip6_string
  - lib/vsprintf.c:ip6_compressed_string
  - lib/vsprintf.c:ip6_compressed_string
  - lib/vsprintf.c:ip6_compressed_string
  - lib/vsprintf.c:mac_address_string
  - lib/vsprintf.c:mac_address_string
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
In kernel/debug/gdbstub.c (ffffffff8116da5e)
Location: include/linux/kernel.h:648
Inline: True
Inline callers:
  - kernel/debug/gdbstub.c:gdb_serial_stub
  - kernel/debug/gdbstub.c:gdb_serial_stub
  - kernel/debug/gdbstub.c:pack_threadid
  - kernel/debug/gdbstub.c:pack_threadid
  - kernel/debug/gdbstub.c:kgdb_mem2hex
  - kernel/debug/gdbstub.c:gdbstub_msg_write
```
```
In fs/fat/dir.c (ffffffff813c2deb)
Location: include/linux/kernel.h:648
Inline: True
Inline callers:
  - fs/fat/dir.c:__fat_readdir
  - fs/fat/dir.c:__fat_readdir
  - fs/fat/dir.c:fat_search_long
  - fs/fat/dir.c:fat_search_long
  - fs/fat/dir.c:fat_parse_short
  - fs/fat/dir.c:fat_parse_short
```
```
In security/keys/trusted.c (ffffffff81409505)
Location: include/linux/kernel.h:648
Inline: True
Inline callers:
  - security/keys/trusted.c:trusted_read
```
```
In security/keys/encrypted-keys/encrypted.c (ffffffff8140b826)
Location: include/linux/kernel.h:648
Inline: True
Inline callers:
  - security/keys/encrypted-keys/encrypted.c:encrypted_read
```
```
In security/integrity/ima/ima_api.c (ffffffff81470be6)
Location: include/linux/kernel.h:648
Inline: True
Inline callers:
  - security/integrity/ima/ima_api.c:ima_audit_measurement
```
```
In lib/hexdump.c (ffffffff814e2ecb)
Location: include/linux/kernel.h:648
Inline: True
Inline callers:
  - lib/hexdump.c:bin2hex
```
```
In lib/vsprintf.c (ffffffff81a13868)
Location: include/linux/kernel.h:648
Inline: True
Inline callers:
  - lib/vsprintf.c:uuid_string
  - lib/vsprintf.c:ip6_string
  - lib/vsprintf.c:ip6_string
  - lib/vsprintf.c:ip6_compressed_string
  - lib/vsprintf.c:ip6_compressed_string
  - lib/vsprintf.c:ip6_compressed_string
  - lib/vsprintf.c:mac_address_string
  - lib/vsprintf.c:mac_address_string
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
In kernel/debug/gdbstub.c (ffffffff8117aa41)
Location: include/linux/kernel.h:608
Inline: True
Inline callers:
  - kernel/debug/gdbstub.c:gdb_serial_stub
  - kernel/debug/gdbstub.c:gdb_serial_stub
  - kernel/debug/gdbstub.c:pack_threadid
  - kernel/debug/gdbstub.c:pack_threadid
  - kernel/debug/gdbstub.c:kgdb_mem2hex
  - kernel/debug/gdbstub.c:gdbstub_msg_write
```
```
In fs/fat/dir.c (ffffffff813ed5a4)
Location: include/linux/kernel.h:608
Inline: True
Inline callers:
  - fs/fat/dir.c:__fat_readdir
  - fs/fat/dir.c:__fat_readdir
  - fs/fat/dir.c:fat_search_long
  - fs/fat/dir.c:fat_search_long
  - fs/fat/dir.c:fat_parse_short
  - fs/fat/dir.c:fat_parse_short
```
```
In security/keys/trusted.c (ffffffff81437549)
Location: include/linux/kernel.h:608
Inline: True
Inline callers:
  - security/keys/trusted.c:trusted_read
```
```
In security/keys/encrypted-keys/encrypted.c (ffffffff81438568)
Location: include/linux/kernel.h:608
Inline: True
Inline callers:
  - security/keys/encrypted-keys/encrypted.c:encrypted_read
```
```
In security/integrity/ima/ima_api.c (ffffffff8149e5bf)
Location: include/linux/kernel.h:608
Inline: True
Inline callers:
  - security/integrity/ima/ima_api.c:ima_audit_measurement
```
```
In lib/hexdump.c (ffffffff8150f24f)
Location: include/linux/kernel.h:608
Inline: True
Inline callers:
  - lib/hexdump.c:bin2hex
```
```
In lib/vsprintf.c (ffffffff81a82f78)
Location: include/linux/kernel.h:608
Inline: True
Inline callers:
  - lib/vsprintf.c:uuid_string
  - lib/vsprintf.c:ip6_string
  - lib/vsprintf.c:ip6_string
  - lib/vsprintf.c:ip6_compressed_string
  - lib/vsprintf.c:ip6_compressed_string
  - lib/vsprintf.c:ip6_compressed_string
  - lib/vsprintf.c:mac_address_string
  - lib/vsprintf.c:mac_address_string
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
In kernel/debug/gdbstub.c (ffffffff811868d1)
Location: include/linux/kernel.h:612
Inline: True
Inline callers:
  - kernel/debug/gdbstub.c:gdb_serial_stub
  - kernel/debug/gdbstub.c:gdb_serial_stub
  - kernel/debug/gdbstub.c:pack_threadid
  - kernel/debug/gdbstub.c:pack_threadid
  - kernel/debug/gdbstub.c:kgdb_mem2hex
  - kernel/debug/gdbstub.c:gdbstub_msg_write
```
```
In fs/fat/dir.c (ffffffff814076c4)
Location: include/linux/kernel.h:612
Inline: True
Inline callers:
  - fs/fat/dir.c:__fat_readdir
  - fs/fat/dir.c:__fat_readdir
  - fs/fat/dir.c:fat_search_long
  - fs/fat/dir.c:fat_search_long
  - fs/fat/dir.c:fat_parse_short
  - fs/fat/dir.c:fat_parse_short
```
```
In security/keys/trusted.c (ffffffff814512ed)
Location: include/linux/kernel.h:612
Inline: True
Inline callers:
  - security/keys/trusted.c:trusted_read
```
```
In security/keys/encrypted-keys/encrypted.c (ffffffff81452340)
Location: include/linux/kernel.h:612
Inline: True
Inline callers:
  - security/keys/encrypted-keys/encrypted.c:encrypted_read
```
```
In security/integrity/ima/ima_api.c (ffffffff814b8a6f)
Location: include/linux/kernel.h:612
Inline: True
Inline callers:
  - security/integrity/ima/ima_api.c:ima_audit_measurement
```
```
In lib/hexdump.c (ffffffff8152d22f)
Location: include/linux/kernel.h:612
Inline: True
Inline callers:
  - lib/hexdump.c:bin2hex
```
```
In lib/vsprintf.c (ffffffff81aba188)
Location: include/linux/kernel.h:612
Inline: True
Inline callers:
  - lib/vsprintf.c:uuid_string
  - lib/vsprintf.c:ip6_string
  - lib/vsprintf.c:ip6_string
  - lib/vsprintf.c:ip6_compressed_string
  - lib/vsprintf.c:ip6_compressed_string
  - lib/vsprintf.c:ip6_compressed_string
  - lib/vsprintf.c:mac_address_string
  - lib/vsprintf.c:mac_address_string
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
In kernel/debug/gdbstub.c (ffffffff8119ae04)
Location: include/linux/kernel.h:621
Inline: True
Inline callers:
  - kernel/debug/gdbstub.c:gdb_serial_stub
  - kernel/debug/gdbstub.c:gdb_serial_stub
  - kernel/debug/gdbstub.c:gdb_serial_stub
  - kernel/debug/gdbstub.c:gdb_cmd_query
  - kernel/debug/gdbstub.c:pack_threadid
  - kernel/debug/gdbstub.c:pack_threadid
  - kernel/debug/gdbstub.c:gdbstub_msg_write
```
```
In fs/fat/dir.c (ffffffff81452cf6)
Location: include/linux/kernel.h:621
Inline: True
Inline callers:
  - fs/fat/dir.c:uni16_to_x8
  - fs/fat/dir.c:uni16_to_x8
```
```
In security/keys/trusted-keys/trusted_tpm1.c (ffffffff814a0cc6)
Location: include/linux/kernel.h:621
Inline: True
Inline callers:
  - security/keys/trusted-keys/trusted_tpm1.c:trusted_read
```
```
In security/keys/encrypted-keys/encrypted.c (ffffffff814a40a9)
Location: include/linux/kernel.h:621
Inline: True
Inline callers:
  - security/keys/encrypted-keys/encrypted.c:datablob_format
```
```
In security/integrity/ima/ima_api.c (ffffffff815186df)
Location: include/linux/kernel.h:621
Inline: True
Inline callers:
  - security/integrity/ima/ima_api.c:ima_audit_measurement
```
```
In lib/hexdump.c (ffffffff81590e85)
Location: include/linux/kernel.h:621
Inline: True
Inline callers:
  - lib/hexdump.c:bin2hex
```
```
In lib/vsprintf.c (ffffffff815f6876)
Location: include/linux/kernel.h:621
Inline: True
Inline callers:
  - lib/vsprintf.c:uuid_string
  - lib/vsprintf.c:ip6_string
  - lib/vsprintf.c:ip6_string
  - lib/vsprintf.c:ip6_compressed_string
  - lib/vsprintf.c:ip6_compressed_string
  - lib/vsprintf.c:ip6_compressed_string
  - lib/vsprintf.c:mac_address_string
  - lib/vsprintf.c:mac_address_string
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
In kernel/debug/gdbstub.c (ffffffff81197f74)
Location: include/linux/kernel.h:461
Inline: True
Inline callers:
  - kernel/debug/gdbstub.c:gdb_serial_stub
  - kernel/debug/gdbstub.c:gdb_serial_stub
  - kernel/debug/gdbstub.c:gdb_serial_stub
  - kernel/debug/gdbstub.c:gdb_cmd_query
  - kernel/debug/gdbstub.c:pack_threadid
  - kernel/debug/gdbstub.c:pack_threadid
  - kernel/debug/gdbstub.c:gdbstub_msg_write
```
```
In fs/fat/dir.c (ffffffff8146f1a6)
Location: include/linux/kernel.h:461
Inline: True
Inline callers:
  - fs/fat/dir.c:uni16_to_x8
  - fs/fat/dir.c:uni16_to_x8
```
```
In security/keys/trusted-keys/trusted_tpm1.c (ffffffff814be696)
Location: include/linux/kernel.h:461
Inline: True
Inline callers:
  - security/keys/trusted-keys/trusted_tpm1.c:trusted_read
```
```
In security/keys/encrypted-keys/encrypted.c (ffffffff814c18a9)
Location: include/linux/kernel.h:461
Inline: True
Inline callers:
  - security/keys/encrypted-keys/encrypted.c:datablob_format
```
```
In security/integrity/ima/ima_api.c (ffffffff815356af)
Location: include/linux/kernel.h:461
Inline: True
Inline callers:
  - security/integrity/ima/ima_api.c:ima_audit_measurement
```
```
In lib/hexdump.c (ffffffff815ada29)
Location: include/linux/kernel.h:461
Inline: True
Inline callers:
  - lib/hexdump.c:bin2hex
```
```
In lib/vsprintf.c (ffffffff8161af06)
Location: include/linux/kernel.h:461
Inline: True
Inline callers:
  - lib/vsprintf.c:uuid_string
  - lib/vsprintf.c:ip6_string
  - lib/vsprintf.c:ip6_string
  - lib/vsprintf.c:ip6_compressed_string
  - lib/vsprintf.c:ip6_compressed_string
  - lib/vsprintf.c:ip6_compressed_string
  - lib/vsprintf.c:mac_address_string
  - lib/vsprintf.c:mac_address_string
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
In kernel/debug/gdbstub.c (ffffffff81198dbc)
Location: include/linux/kernel.h:471
Inline: True
Inline callers:
  - kernel/debug/gdbstub.c:gdb_serial_stub
  - kernel/debug/gdbstub.c:gdb_serial_stub
  - kernel/debug/gdbstub.c:gdb_serial_stub
  - kernel/debug/gdbstub.c:gdb_cmd_query
  - kernel/debug/gdbstub.c:pack_threadid
  - kernel/debug/gdbstub.c:pack_threadid
  - kernel/debug/gdbstub.c:gdbstub_msg_write
```
```
In fs/fat/dir.c (ffffffff81477020)
Location: include/linux/kernel.h:471
Inline: True
Inline callers:
  - fs/fat/dir.c:__fat_readdir
  - fs/fat/dir.c:__fat_readdir
  - fs/fat/dir.c:fat_search_long
  - fs/fat/dir.c:fat_search_long
  - fs/fat/dir.c:fat_parse_short
  - fs/fat/dir.c:fat_parse_short
```
```
In security/keys/trusted-keys/trusted_core.c (ffffffff814c44d6)
Location: include/linux/kernel.h:471
Inline: True
Inline callers:
  - security/keys/trusted-keys/trusted_core.c:trusted_read
```
```
In security/keys/encrypted-keys/encrypted.c (ffffffff814c7d29)
Location: include/linux/kernel.h:471
Inline: True
Inline callers:
  - security/keys/encrypted-keys/encrypted.c:datablob_format
```
```
In security/integrity/ima/ima_api.c (ffffffff8153dcd5)
Location: include/linux/kernel.h:471
Inline: True
Inline callers:
  - security/integrity/ima/ima_api.c:ima_audit_measurement
```
```
In lib/hexdump.c (ffffffff815b86c3)
Location: include/linux/kernel.h:471
Inline: True
Inline callers:
  - lib/hexdump.c:bin2hex
```
```
In lib/vsprintf.c (ffffffff815ff139)
Location: include/linux/kernel.h:471
Inline: True
Inline callers:
  - lib/vsprintf.c:uuid_string
  - lib/vsprintf.c:ip6_string
  - lib/vsprintf.c:ip6_string
  - lib/vsprintf.c:ip6_compressed_string
  - lib/vsprintf.c:ip6_compressed_string
  - lib/vsprintf.c:ip6_compressed_string
  - lib/vsprintf.c:mac_address_string
  - lib/vsprintf.c:mac_address_string
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
In kernel/debug/gdbstub.c (ffffffff811c2b80)
Location: include/linux/kernel.h:262
Inline: True
Inline callers:
  - kernel/debug/gdbstub.c:gdb_serial_stub
  - kernel/debug/gdbstub.c:gdb_serial_stub
  - kernel/debug/gdbstub.c:gdb_serial_stub
  - kernel/debug/gdbstub.c:gdb_cmd_query
  - kernel/debug/gdbstub.c:pack_threadid
  - kernel/debug/gdbstub.c:pack_threadid
  - kernel/debug/gdbstub.c:gdbstub_msg_write
```
```
In fs/fat/dir.c (ffffffff814ce7c3)
Location: include/linux/kernel.h:262
Inline: True
Inline callers:
  - fs/fat/dir.c:__fat_readdir
  - fs/fat/dir.c:__fat_readdir
  - fs/fat/dir.c:fat_search_long
  - fs/fat/dir.c:fat_search_long
  - fs/fat/dir.c:fat_parse_short
  - fs/fat/dir.c:fat_parse_short
```
```
In security/keys/trusted-keys/trusted_core.c (ffffffff8151cea6)
Location: include/linux/kernel.h:262
Inline: True
Inline callers:
  - security/keys/trusted-keys/trusted_core.c:trusted_read
```
```
In security/keys/encrypted-keys/encrypted.c (ffffffff81520819)
Location: include/linux/kernel.h:262
Inline: True
Inline callers:
  - security/keys/encrypted-keys/encrypted.c:datablob_format
```
```
In security/integrity/ima/ima_api.c (ffffffff8159cb91)
Location: include/linux/kernel.h:262
Inline: True
Inline callers:
  - security/integrity/ima/ima_api.c:ima_audit_measurement
```
```
In lib/hexdump.c (ffffffff8161ef13)
Location: include/linux/kernel.h:262
Inline: True
Inline callers:
  - lib/hexdump.c:bin2hex
```
```
In lib/vsprintf.c (ffffffff8166ceaf)
Location: include/linux/kernel.h:262
Inline: True
Inline callers:
  - lib/vsprintf.c:uuid_string
  - lib/vsprintf.c:ip6_string
  - lib/vsprintf.c:ip6_string
  - lib/vsprintf.c:ip6_compressed_string
  - lib/vsprintf.c:ip6_compressed_string
  - lib/vsprintf.c:ip6_compressed_string
  - lib/vsprintf.c:mac_address_string
  - lib/vsprintf.c:mac_address_string
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
In kernel/debug/gdbstub.c (ffffffff811f6358)
Location: include/linux/kernel.h:270
Inline: True
Inline callers:
  - kernel/debug/gdbstub.c:gdb_serial_stub
  - kernel/debug/gdbstub.c:gdb_serial_stub
  - kernel/debug/gdbstub.c:gdb_serial_stub
  - kernel/debug/gdbstub.c:gdb_cmd_query
  - kernel/debug/gdbstub.c:pack_threadid
  - kernel/debug/gdbstub.c:pack_threadid
  - kernel/debug/gdbstub.c:gdbstub_msg_write
```
```
In fs/fat/dir.c (ffffffff8155b02a)
Location: include/linux/kernel.h:270
Inline: True
Inline callers:
  - fs/fat/dir.c:__fat_readdir
  - fs/fat/dir.c:__fat_readdir
  - fs/fat/dir.c:fat_search_long
  - fs/fat/dir.c:fat_search_long
  - fs/fat/dir.c:fat_parse_short
  - fs/fat/dir.c:fat_parse_short
```
```
In security/keys/trusted-keys/trusted_core.c (ffffffff815b0154)
Location: include/linux/kernel.h:270
Inline: True
Inline callers:
  - security/keys/trusted-keys/trusted_core.c:trusted_read
```
```
In security/keys/encrypted-keys/encrypted.c (ffffffff815b3f51)
Location: include/linux/kernel.h:270
Inline: True
Inline callers:
  - security/keys/encrypted-keys/encrypted.c:datablob_format
```
```
In security/integrity/ima/ima_api.c (ffffffff81641d23)
Location: include/linux/kernel.h:270
Inline: True
Inline callers:
  - security/integrity/ima/ima_api.c:ima_audit_measurement
```
```
In lib/hexdump.c (ffffffff816ed129)
Location: include/linux/kernel.h:270
Inline: True
Inline callers:
  - lib/hexdump.c:bin2hex
```
```
In lib/vsprintf.c (ffffffff817871b2)
Location: include/linux/kernel.h:270
Inline: True
Inline callers:
  - lib/vsprintf.c:uuid_string
  - lib/vsprintf.c:ip6_string
  - lib/vsprintf.c:ip6_string
  - lib/vsprintf.c:ip6_compressed_string
  - lib/vsprintf.c:ip6_compressed_string
  - lib/vsprintf.c:ip6_compressed_string
  - lib/vsprintf.c:mac_address_string
  - lib/vsprintf.c:mac_address_string
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
In kernel/debug/gdbstub.c (ffffffff8123d519)
Location: include/linux/kernel.h:270
Inline: True
Inline callers:
  - kernel/debug/gdbstub.c:gdb_serial_stub
  - kernel/debug/gdbstub.c:gdb_serial_stub
  - kernel/debug/gdbstub.c:gdb_serial_stub
  - kernel/debug/gdbstub.c:gdb_cmd_query
  - kernel/debug/gdbstub.c:pack_threadid
  - kernel/debug/gdbstub.c:pack_threadid
  - kernel/debug/gdbstub.c:gdbstub_msg_write
```
```
In fs/fat/dir.c (ffffffff815fbdce)
Location: include/linux/kernel.h:270
Inline: True
Inline callers:
  - fs/fat/dir.c:__fat_readdir
  - fs/fat/dir.c:__fat_readdir
  - fs/fat/dir.c:fat_search_long
  - fs/fat/dir.c:fat_search_long
  - fs/fat/dir.c:fat_parse_short
  - fs/fat/dir.c:fat_parse_short
```
```
In security/keys/trusted-keys/trusted_core.c (ffffffff8165a9e4)
Location: include/linux/kernel.h:270
Inline: True
Inline callers:
  - security/keys/trusted-keys/trusted_core.c:trusted_read
```
```
In security/keys/encrypted-keys/encrypted.c (ffffffff8165ecd1)
Location: include/linux/kernel.h:270
Inline: True
Inline callers:
  - security/keys/encrypted-keys/encrypted.c:datablob_format
```
```
In security/integrity/ima/ima_api.c (ffffffff816f9d93)
Location: include/linux/kernel.h:270
Inline: True
Inline callers:
  - security/integrity/ima/ima_api.c:ima_audit_measurement
```
```
In lib/hexdump.c (ffffffff817ddab9)
Location: include/linux/kernel.h:270
Inline: True
Inline callers:
  - lib/hexdump.c:bin2hex
```
```
In lib/vsprintf.c (ffffffff82044352)
Location: include/linux/kernel.h:270
Inline: True
Inline callers:
  - lib/vsprintf.c:uuid_string
  - lib/vsprintf.c:ip6_string
  - lib/vsprintf.c:ip6_string
  - lib/vsprintf.c:ip6_compressed_string
  - lib/vsprintf.c:ip6_compressed_string
  - lib/vsprintf.c:ip6_compressed_string
  - lib/vsprintf.c:mac_address_string
  - lib/vsprintf.c:mac_address_string
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
In kernel/debug/gdbstub.c (ffffffff81254551)
Location: include/linux/hex.h:11
Inline: True
Inline callers:
  - kernel/debug/gdbstub.c:gdb_serial_stub
  - kernel/debug/gdbstub.c:gdb_serial_stub
  - kernel/debug/gdbstub.c:gdb_serial_stub
  - kernel/debug/gdbstub.c:gdb_cmd_query
  - kernel/debug/gdbstub.c:pack_threadid
  - kernel/debug/gdbstub.c:pack_threadid
  - kernel/debug/gdbstub.c:gdbstub_msg_write
```
```
In fs/fat/dir.c (ffffffff81633d66)
Location: include/linux/hex.h:11
Inline: True
Inline callers:
  - fs/fat/dir.c:__fat_readdir
  - fs/fat/dir.c:__fat_readdir
  - fs/fat/dir.c:fat_search_long
  - fs/fat/dir.c:fat_search_long
  - fs/fat/dir.c:fat_parse_short
  - fs/fat/dir.c:fat_parse_short
```
```
In security/keys/trusted-keys/trusted_core.c (ffffffff816932dc)
Location: include/linux/hex.h:11
Inline: True
Inline callers:
  - security/keys/trusted-keys/trusted_core.c:trusted_read
```
```
In security/keys/encrypted-keys/encrypted.c (ffffffff81697621)
Location: include/linux/hex.h:11
Inline: True
Inline callers:
  - security/keys/encrypted-keys/encrypted.c:datablob_format
```
```
In security/integrity/ima/ima_api.c (ffffffff81733ec2)
Location: include/linux/hex.h:11
Inline: True
Inline callers:
  - security/integrity/ima/ima_api.c:ima_audit_measurement
```
```
In lib/hexdump.c (ffffffff8181d2c9)
Location: include/linux/hex.h:11
Inline: True
Inline callers:
  - lib/hexdump.c:bin2hex
```
```
In lib/vsprintf.c (ffffffff820c295c)
Location: include/linux/hex.h:11
Inline: True
Inline callers:
  - lib/vsprintf.c:uuid_string
  - lib/vsprintf.c:ip6_string
  - lib/vsprintf.c:ip6_string
  - lib/vsprintf.c:ip6_compressed_string
  - lib/vsprintf.c:ip6_compressed_string
  - lib/vsprintf.c:ip6_compressed_string
  - lib/vsprintf.c:mac_address_string
  - lib/vsprintf.c:mac_address_string
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
In kernel/debug/gdbstub.c (ffffffff8126e3c1)
Location: include/linux/hex.h:11
Inline: True
Inline callers:
  - kernel/debug/gdbstub.c:gdb_serial_stub
  - kernel/debug/gdbstub.c:gdb_serial_stub
  - kernel/debug/gdbstub.c:gdb_serial_stub
  - kernel/debug/gdbstub.c:gdb_cmd_query
  - kernel/debug/gdbstub.c:pack_threadid
  - kernel/debug/gdbstub.c:pack_threadid
  - kernel/debug/gdbstub.c:gdbstub_msg_write
```
```
In fs/fat/dir.c (ffffffff8166d236)
Location: include/linux/hex.h:11
Inline: True
Inline callers:
  - fs/fat/dir.c:__fat_readdir
  - fs/fat/dir.c:__fat_readdir
  - fs/fat/dir.c:fat_search_long
  - fs/fat/dir.c:fat_search_long
  - fs/fat/dir.c:fat_parse_short
  - fs/fat/dir.c:fat_parse_short
```
```
In security/keys/trusted-keys/trusted_core.c (ffffffff816cf8ac)
Location: include/linux/hex.h:11
Inline: True
Inline callers:
  - security/keys/trusted-keys/trusted_core.c:trusted_read
```
```
In security/keys/encrypted-keys/encrypted.c (ffffffff816d3ca1)
Location: include/linux/hex.h:11
Inline: True
Inline callers:
  - security/keys/encrypted-keys/encrypted.c:datablob_format
```
```
In security/integrity/ima/ima_api.c (ffffffff817749b2)
Location: include/linux/hex.h:11
Inline: True
Inline callers:
  - security/integrity/ima/ima_api.c:ima_audit_measurement
```
```
In lib/hexdump.c (ffffffff81863139)
Location: include/linux/hex.h:11
Inline: True
Inline callers:
  - lib/hexdump.c:bin2hex
```
```
In lib/vsprintf.c (ffffffff8219d2dc)
Location: include/linux/hex.h:11
Inline: True
Inline callers:
  - lib/vsprintf.c:uuid_string
  - lib/vsprintf.c:ip6_string
  - lib/vsprintf.c:ip6_string
  - lib/vsprintf.c:ip6_compressed_string
  - lib/vsprintf.c:ip6_compressed_string
  - lib/vsprintf.c:ip6_compressed_string
  - lib/vsprintf.c:mac_address_string
  - lib/vsprintf.c:mac_address_string
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
In kernel/debug/gdbstub.c (ffff8000101fc92c)
Location: include/linux/kernel.h:612
Inline: True
Inline callers:
  - kernel/debug/gdbstub.c:gdb_serial_stub
  - kernel/debug/gdbstub.c:gdb_serial_stub
  - kernel/debug/gdbstub.c:pack_threadid
  - kernel/debug/gdbstub.c:pack_threadid
  - kernel/debug/gdbstub.c:kgdb_mem2hex
  - kernel/debug/gdbstub.c:gdbstub_msg_write
```
```
In fs/fat/dir.c (ffff8000104e6414)
Location: include/linux/kernel.h:612
Inline: True
Inline callers:
  - fs/fat/dir.c:__fat_readdir
  - fs/fat/dir.c:__fat_readdir
  - fs/fat/dir.c:fat_search_long
  - fs/fat/dir.c:fat_search_long
  - fs/fat/dir.c:fat_parse_short
  - fs/fat/dir.c:fat_parse_short
```
```
In security/keys/trusted.c (ffff80001053b4ac)
Location: include/linux/kernel.h:612
Inline: True
Inline callers:
  - security/keys/trusted.c:trusted_read
```
```
In security/keys/encrypted-keys/encrypted.c (ffff80001053dcfc)
Location: include/linux/kernel.h:612
Inline: True
Inline callers:
  - security/keys/encrypted-keys/encrypted.c:encrypted_read
```
```
In security/integrity/ima/ima_api.c (ffff8000105b0d70)
Location: include/linux/kernel.h:612
Inline: True
Inline callers:
  - security/integrity/ima/ima_api.c:ima_audit_measurement
```
```
In lib/hexdump.c (ffff8000106392fc)
Location: include/linux/kernel.h:612
Inline: True
Inline callers:
  - lib/hexdump.c:bin2hex
```
```
In lib/vsprintf.c (ffff800010d9497c)
Location: include/linux/kernel.h:612
Inline: True
Inline callers:
  - lib/vsprintf.c:uuid_string
  - lib/vsprintf.c:ip6_string
  - lib/vsprintf.c:ip6_string
  - lib/vsprintf.c:ip6_compressed_string
  - lib/vsprintf.c:ip6_compressed_string
  - lib/vsprintf.c:ip6_compressed_string
  - lib/vsprintf.c:mac_address_string
  - lib/vsprintf.c:mac_address_string
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
In kernel/debug/gdbstub.c (c043c958)
Location: include/linux/kernel.h:612
Inline: True
Inline callers:
  - kernel/debug/gdbstub.c:gdb_serial_stub
  - kernel/debug/gdbstub.c:gdb_serial_stub
  - kernel/debug/gdbstub.c:pack_threadid
  - kernel/debug/gdbstub.c:pack_threadid
  - kernel/debug/gdbstub.c:kgdb_mem2hex
  - kernel/debug/gdbstub.c:gdbstub_msg_write
```
```
In fs/fat/dir.c (c06a5cf8)
Location: include/linux/kernel.h:612
Inline: True
Inline callers:
  - fs/fat/dir.c:__fat_readdir
  - fs/fat/dir.c:__fat_readdir
  - fs/fat/dir.c:fat_search_long
  - fs/fat/dir.c:fat_search_long
  - fs/fat/dir.c:fat_parse_short
  - fs/fat/dir.c:fat_parse_short
```
```
In security/keys/trusted.c (c06f24f0)
Location: include/linux/kernel.h:612
Inline: True
Inline callers:
  - security/keys/trusted.c:trusted_read
```
```
In security/keys/encrypted-keys/encrypted.c (c06f34a4)
Location: include/linux/kernel.h:612
Inline: True
Inline callers:
  - security/keys/encrypted-keys/encrypted.c:encrypted_read
```
```
In security/integrity/ima/ima_api.c (c0760438)
Location: include/linux/kernel.h:612
Inline: True
Inline callers:
  - security/integrity/ima/ima_api.c:ima_audit_measurement
```
```
In lib/hexdump.c (c07dec78)
Location: include/linux/kernel.h:612
Inline: True
Inline callers:
  - lib/hexdump.c:bin2hex
```
```
In lib/vsprintf.c (c0e90b18)
Location: include/linux/kernel.h:612
Inline: True
Inline callers:
  - lib/vsprintf.c:uuid_string
  - lib/vsprintf.c:ip6_string
  - lib/vsprintf.c:ip6_string
  - lib/vsprintf.c:ip6_compressed_string
  - lib/vsprintf.c:ip6_compressed_string
  - lib/vsprintf.c:ip6_compressed_string
  - lib/vsprintf.c:mac_address_string
  - lib/vsprintf.c:mac_address_string
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
In kernel/debug/gdbstub.c (c000000000274da8)
Location: include/linux/kernel.h:612
Inline: True
Inline callers:
  - kernel/debug/gdbstub.c:gdb_serial_stub
  - kernel/debug/gdbstub.c:gdb_serial_stub
  - kernel/debug/gdbstub.c:pack_threadid
  - kernel/debug/gdbstub.c:pack_threadid
  - kernel/debug/gdbstub.c:kgdb_mem2hex
  - kernel/debug/gdbstub.c:gdbstub_msg_write
```
```
In fs/fat/dir.c (c000000000624540)
Location: include/linux/kernel.h:612
Inline: True
Inline callers:
  - fs/fat/dir.c:__fat_readdir
  - fs/fat/dir.c:__fat_readdir
  - fs/fat/dir.c:fat_search_long
  - fs/fat/dir.c:fat_search_long
  - fs/fat/dir.c:fat_parse_short
  - fs/fat/dir.c:fat_parse_short
```
```
In security/keys/trusted.c (c000000000689bb0)
Location: include/linux/kernel.h:612
Inline: True
Inline callers:
  - security/keys/trusted.c:trusted_read
```
```
In security/keys/encrypted-keys/encrypted.c (c00000000068d114)
Location: include/linux/kernel.h:612
Inline: True
Inline callers:
  - security/keys/encrypted-keys/encrypted.c:encrypted_read
```
```
In security/integrity/ima/ima_api.c (c000000000730ba0)
Location: include/linux/kernel.h:612
Inline: True
Inline callers:
  - security/integrity/ima/ima_api.c:ima_audit_measurement
```
```
In lib/hexdump.c (c0000000007dfbc4)
Location: include/linux/kernel.h:612
Inline: True
Inline callers:
  - lib/hexdump.c:bin2hex
```
```
In lib/vsprintf.c (c000000000ed945c)
Location: include/linux/kernel.h:612
Inline: True
Inline callers:
  - lib/vsprintf.c:uuid_string
  - lib/vsprintf.c:ip6_string
  - lib/vsprintf.c:ip6_string
  - lib/vsprintf.c:ip6_compressed_string
  - lib/vsprintf.c:ip6_compressed_string
  - lib/vsprintf.c:ip6_compressed_string
  - lib/vsprintf.c:mac_address_string
  - lib/vsprintf.c:mac_address_string
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
In fs/fat/dir.c (ffffffe000358f48)
Location: include/linux/kernel.h:612
Inline: True
Inline callers:
  - fs/fat/dir.c:__fat_readdir
  - fs/fat/dir.c:__fat_readdir
  - fs/fat/dir.c:fat_search_long
  - fs/fat/dir.c:fat_search_long
  - fs/fat/dir.c:fat_parse_short
  - fs/fat/dir.c:fat_parse_short
```
```
In security/keys/trusted.c (ffffffe000399260)
Location: include/linux/kernel.h:612
Inline: True
Inline callers:
  - security/keys/trusted.c:trusted_read
```
```
In security/keys/encrypted-keys/encrypted.c (ffffffe00039b174)
Location: include/linux/kernel.h:612
Inline: True
Inline callers:
  - security/keys/encrypted-keys/encrypted.c:encrypted_read
```
```
In security/integrity/ima/ima_api.c (ffffffe0003f8848)
Location: include/linux/kernel.h:612
Inline: True
Inline callers:
  - security/integrity/ima/ima_api.c:ima_audit_measurement
```
```
In lib/hexdump.c (ffffffe000465eea)
Location: include/linux/kernel.h:612
Inline: True
Inline callers:
  - lib/hexdump.c:bin2hex
```
```
In lib/vsprintf.c (ffffffe0008be728)
Location: include/linux/kernel.h:612
Inline: True
Inline callers:
  - lib/vsprintf.c:uuid_string
  - lib/vsprintf.c:ip6_string
  - lib/vsprintf.c:ip6_string
  - lib/vsprintf.c:ip6_compressed_string
  - lib/vsprintf.c:ip6_compressed_string
  - lib/vsprintf.c:ip6_compressed_string
  - lib/vsprintf.c:mac_address_string
  - lib/vsprintf.c:mac_address_string
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
In kernel/debug/gdbstub.c (ffffffff8117eef1)
Location: include/linux/kernel.h:612
Inline: True
Inline callers:
  - kernel/debug/gdbstub.c:gdb_serial_stub
  - kernel/debug/gdbstub.c:gdb_serial_stub
  - kernel/debug/gdbstub.c:pack_threadid
  - kernel/debug/gdbstub.c:pack_threadid
  - kernel/debug/gdbstub.c:kgdb_mem2hex
  - kernel/debug/gdbstub.c:gdbstub_msg_write
```
```
In fs/fat/dir.c (ffffffff813ffca4)
Location: include/linux/kernel.h:612
Inline: True
Inline callers:
  - fs/fat/dir.c:__fat_readdir
  - fs/fat/dir.c:__fat_readdir
  - fs/fat/dir.c:fat_search_long
  - fs/fat/dir.c:fat_search_long
  - fs/fat/dir.c:fat_parse_short
  - fs/fat/dir.c:fat_parse_short
```
```
In security/keys/trusted.c (ffffffff814498cd)
Location: include/linux/kernel.h:612
Inline: True
Inline callers:
  - security/keys/trusted.c:trusted_read
```
```
In security/keys/encrypted-keys/encrypted.c (ffffffff8144a920)
Location: include/linux/kernel.h:612
Inline: True
Inline callers:
  - security/keys/encrypted-keys/encrypted.c:encrypted_read
```
```
In security/integrity/ima/ima_api.c (ffffffff814b104f)
Location: include/linux/kernel.h:612
Inline: True
Inline callers:
  - security/integrity/ima/ima_api.c:ima_audit_measurement
```
```
In lib/hexdump.c (ffffffff8152580f)
Location: include/linux/kernel.h:612
Inline: True
Inline callers:
  - lib/hexdump.c:bin2hex
```
```
In lib/vsprintf.c (ffffffff81a58fd8)
Location: include/linux/kernel.h:612
Inline: True
Inline callers:
  - lib/vsprintf.c:uuid_string
  - lib/vsprintf.c:ip6_string
  - lib/vsprintf.c:ip6_string
  - lib/vsprintf.c:ip6_compressed_string
  - lib/vsprintf.c:ip6_compressed_string
  - lib/vsprintf.c:ip6_compressed_string
  - lib/vsprintf.c:mac_address_string
  - lib/vsprintf.c:mac_address_string
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
In kernel/debug/gdbstub.c (ffffffff81172041)
Location: include/linux/kernel.h:612
Inline: True
Inline callers:
  - kernel/debug/gdbstub.c:gdb_serial_stub
  - kernel/debug/gdbstub.c:gdb_serial_stub
  - kernel/debug/gdbstub.c:pack_threadid
  - kernel/debug/gdbstub.c:pack_threadid
  - kernel/debug/gdbstub.c:kgdb_mem2hex
  - kernel/debug/gdbstub.c:gdbstub_msg_write
```
```
In fs/fat/dir.c (ffffffff813f0724)
Location: include/linux/kernel.h:612
Inline: True
Inline callers:
  - fs/fat/dir.c:__fat_readdir
  - fs/fat/dir.c:__fat_readdir
  - fs/fat/dir.c:fat_search_long
  - fs/fat/dir.c:fat_search_long
  - fs/fat/dir.c:fat_parse_short
  - fs/fat/dir.c:fat_parse_short
```
```
In security/keys/trusted.c (ffffffff8143a31d)
Location: include/linux/kernel.h:612
Inline: True
Inline callers:
  - security/keys/trusted.c:trusted_read
```
```
In security/keys/encrypted-keys/encrypted.c (ffffffff8143b370)
Location: include/linux/kernel.h:612
Inline: True
Inline callers:
  - security/keys/encrypted-keys/encrypted.c:encrypted_read
```
```
In security/integrity/ima/ima_api.c (ffffffff814a1a6f)
Location: include/linux/kernel.h:612
Inline: True
Inline callers:
  - security/integrity/ima/ima_api.c:ima_audit_measurement
```
```
In lib/hexdump.c (ffffffff81515aef)
Location: include/linux/kernel.h:612
Inline: True
Inline callers:
  - lib/hexdump.c:bin2hex
```
```
In lib/vsprintf.c (ffffffff81a160b8)
Location: include/linux/kernel.h:612
Inline: True
Inline callers:
  - lib/vsprintf.c:uuid_string
  - lib/vsprintf.c:ip6_string
  - lib/vsprintf.c:ip6_string
  - lib/vsprintf.c:ip6_compressed_string
  - lib/vsprintf.c:ip6_compressed_string
  - lib/vsprintf.c:ip6_compressed_string
  - lib/vsprintf.c:mac_address_string
  - lib/vsprintf.c:mac_address_string
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
In kernel/debug/gdbstub.c (ffffffff8117ccc1)
Location: include/linux/kernel.h:612
Inline: True
Inline callers:
  - kernel/debug/gdbstub.c:gdb_serial_stub
  - kernel/debug/gdbstub.c:gdb_serial_stub
  - kernel/debug/gdbstub.c:pack_threadid
  - kernel/debug/gdbstub.c:pack_threadid
  - kernel/debug/gdbstub.c:kgdb_mem2hex
  - kernel/debug/gdbstub.c:gdbstub_msg_write
```
```
In fs/fat/dir.c (ffffffff813fd024)
Location: include/linux/kernel.h:612
Inline: True
Inline callers:
  - fs/fat/dir.c:__fat_readdir
  - fs/fat/dir.c:__fat_readdir
  - fs/fat/dir.c:fat_search_long
  - fs/fat/dir.c:fat_search_long
  - fs/fat/dir.c:fat_parse_short
  - fs/fat/dir.c:fat_parse_short
```
```
In security/keys/trusted.c (ffffffff8144596d)
Location: include/linux/kernel.h:612
Inline: True
Inline callers:
  - security/keys/trusted.c:trusted_read
```
```
In security/keys/encrypted-keys/encrypted.c (ffffffff814469c0)
Location: include/linux/kernel.h:612
Inline: True
Inline callers:
  - security/keys/encrypted-keys/encrypted.c:encrypted_read
```
```
In security/integrity/ima/ima_api.c (ffffffff814ad0df)
Location: include/linux/kernel.h:612
Inline: True
Inline callers:
  - security/integrity/ima/ima_api.c:ima_audit_measurement
```
```
In lib/hexdump.c (ffffffff8152189f)
Location: include/linux/kernel.h:612
Inline: True
Inline callers:
  - lib/hexdump.c:bin2hex
```
```
In lib/vsprintf.c (ffffffff81ac53c8)
Location: include/linux/kernel.h:612
Inline: True
Inline callers:
  - lib/vsprintf.c:uuid_string
  - lib/vsprintf.c:ip6_string
  - lib/vsprintf.c:ip6_string
  - lib/vsprintf.c:ip6_compressed_string
  - lib/vsprintf.c:ip6_compressed_string
  - lib/vsprintf.c:ip6_compressed_string
  - lib/vsprintf.c:mac_address_string
  - lib/vsprintf.c:mac_address_string
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
In kernel/debug/gdbstub.c (ffffffff8118a5e1)
Location: include/linux/kernel.h:612
Inline: True
Inline callers:
  - kernel/debug/gdbstub.c:gdb_serial_stub
  - kernel/debug/gdbstub.c:gdb_serial_stub
  - kernel/debug/gdbstub.c:pack_threadid
  - kernel/debug/gdbstub.c:pack_threadid
  - kernel/debug/gdbstub.c:kgdb_mem2hex
  - kernel/debug/gdbstub.c:gdbstub_msg_write
```
```
In fs/fat/dir.c (ffffffff81412c5b)
Location: include/linux/kernel.h:612
Inline: True
Inline callers:
  - fs/fat/dir.c:__fat_readdir
  - fs/fat/dir.c:__fat_readdir
  - fs/fat/dir.c:fat_search_long
  - fs/fat/dir.c:fat_search_long
  - fs/fat/dir.c:fat_parse_short
  - fs/fat/dir.c:fat_parse_short
```
```
In security/keys/trusted.c (ffffffff8145cc9d)
Location: include/linux/kernel.h:612
Inline: True
Inline callers:
  - security/keys/trusted.c:trusted_read
```
```
In security/keys/encrypted-keys/encrypted.c (ffffffff8145dcf0)
Location: include/linux/kernel.h:612
Inline: True
Inline callers:
  - security/keys/encrypted-keys/encrypted.c:encrypted_read
```
```
In security/integrity/ima/ima_api.c (ffffffff814c5b2f)
Location: include/linux/kernel.h:612
Inline: True
Inline callers:
  - security/integrity/ima/ima_api.c:ima_audit_measurement
```
```
In lib/hexdump.c (ffffffff8153b21f)
Location: include/linux/kernel.h:612
Inline: True
Inline callers:
  - lib/hexdump.c:bin2hex
```
```
In lib/vsprintf.c (ffffffff81ad1898)
Location: include/linux/kernel.h:612
Inline: True
Inline callers:
  - lib/vsprintf.c:uuid_string
  - lib/vsprintf.c:ip6_string
  - lib/vsprintf.c:ip6_string
  - lib/vsprintf.c:ip6_compressed_string
  - lib/vsprintf.c:ip6_compressed_string
  - lib/vsprintf.c:ip6_compressed_string
  - lib/vsprintf.c:mac_address_string
  - lib/vsprintf.c:mac_address_string
```
</details>
</li>
</ul>

## Differences
