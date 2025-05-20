# Function: <code>print_hex_dump</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void print_hex_dump(const char *level, const char *prefix_str, int prefix_type, int rowsize, int groupsize, const void *buf, size_t len, bool ascii);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/hexdump.c (ffffffff81401aa0)
Location: lib/hexdump.c:242
Inline: False
Direct callers:
  - arch/x86/kernel/mpparse.c:smp_dump_mptable
  - arch/x86/net/bpf_jit_comp.c:bpf_int_jit_compile
  - mm/slub.c:print_trailer
  - mm/slub.c:print_trailer
  - mm/slub.c:print_trailer
  - mm/slub.c:print_trailer
  - mm/slub.c:free_debug_processing
  - fs/ext4/super.c:ext4_destroy_inode
  - drivers/ata/libata-core.c:ata_dev_read_id
  - drivers/net/tun.c:tun_do_read
```
**Symbols:**

```
ffffffff81401aa0-ffffffff81401c0a: print_hex_dump (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void print_hex_dump(const char *level, const char *prefix_str, int prefix_type, int rowsize, int groupsize, const void *buf, size_t len, bool ascii);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/hexdump.c (ffffffff81449480)
Location: lib/hexdump.c:242
Inline: False
Direct callers:
  - arch/x86/kernel/mpparse.c:smp_dump_mptable
  - arch/x86/net/bpf_jit_comp.c:bpf_int_jit_compile
  - mm/slub.c:free_debug_processing
  - mm/slub.c:print_trailer
  - mm/slub.c:print_trailer
  - mm/slub.c:print_trailer
  - mm/slub.c:print_trailer
  - mm/slub.c:print_trailer
  - fs/ext4/super.c:ext4_destroy_inode
  - drivers/ata/libata-core.c:ata_dev_read_id
  - drivers/usb/core/devio.c:snoop_urb_data
  - drivers/usb/core/devio.c:snoop_urb_data
```
**Symbols:**

```
ffffffff81449480-ffffffff814495ea: print_hex_dump (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void print_hex_dump(const char *level, const char *prefix_str, int prefix_type, int rowsize, int groupsize, const void *buf, size_t len, bool ascii);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/hexdump.c (ffffffff81467e70)
Location: lib/hexdump.c:242
Inline: False
Direct callers:
  - arch/x86/kernel/mpparse.c:smp_dump_mptable
  - arch/x86/net/bpf_jit_comp.c:bpf_int_jit_compile
  - mm/debug.c:__dump_page
  - mm/slub.c:free_debug_processing
  - mm/slub.c:print_trailer
  - mm/slub.c:print_trailer
  - mm/slub.c:print_trailer
  - mm/slub.c:print_trailer
  - mm/slub.c:print_trailer
  - fs/ext4/super.c:ext4_destroy_inode
  - drivers/ata/libata-core.c:ata_dev_read_id
  - drivers/usb/core/devio.c:snoop_urb_data
  - drivers/usb/core/devio.c:snoop_urb_data
  - drivers/firmware/efi/apple-properties.c:map_properties
  - drivers/firmware/efi/apple-properties.c:map_properties
  - drivers/firmware/efi/apple-properties.c:map_properties
  - drivers/firmware/efi/apple-properties.c:map_properties
  - drivers/firmware/efi/apple-properties.c:map_properties
```
**Symbols:**

```
ffffffff81467e70-ffffffff81467fda: print_hex_dump (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void print_hex_dump(const char *level, const char *prefix_str, int prefix_type, int rowsize, int groupsize, const void *buf, size_t len, bool ascii);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/hexdump.c (ffffffff8146d580)
Location: lib/hexdump.c:242
Inline: False
Direct callers:
  - arch/x86/kernel/mpparse.c:smp_dump_mptable
  - arch/x86/net/bpf_jit_comp.c:bpf_int_jit_compile
  - mm/debug.c:__dump_page
  - mm/slub.c:free_debug_processing
  - mm/slub.c:print_trailer
  - mm/slub.c:print_trailer
  - mm/slub.c:print_trailer
  - mm/slub.c:print_trailer
  - mm/slub.c:print_trailer
  - fs/ext4/super.c:ext4_destroy_inode
  - drivers/ata/libata-core.c:ata_dev_read_id
  - drivers/usb/core/devio.c:snoop_urb_data
  - drivers/usb/core/devio.c:snoop_urb_data
  - drivers/firmware/efi/cper.c:cper_estatus_print_section
  - drivers/firmware/efi/apple-properties.c:map_properties
  - drivers/firmware/efi/apple-properties.c:map_properties
  - drivers/firmware/efi/apple-properties.c:map_properties
  - drivers/firmware/efi/apple-properties.c:map_properties
  - drivers/firmware/efi/apple-properties.c:map_properties
```
**Symbols:**

```
ffffffff8146d580-ffffffff8146d6e4: print_hex_dump (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void print_hex_dump(const char *level, const char *prefix_str, int prefix_type, int rowsize, int groupsize, const void *buf, size_t len, bool ascii);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/hexdump.c (ffffffff814998b0)
Location: lib/hexdump.c:243
Inline: False
Direct callers:
  - arch/x86/kernel/mpparse.c:smp_dump_mptable
  - arch/x86/net/bpf_jit_comp.c:bpf_int_jit_compile
  - mm/debug.c:__dump_page
  - mm/slub.c:free_debug_processing
  - mm/slub.c:print_trailer
  - mm/slub.c:print_trailer
  - mm/slub.c:print_trailer
  - mm/slub.c:print_trailer
  - mm/slub.c:print_trailer
  - fs/ext4/super.c:ext4_destroy_inode
  - drivers/ata/libata-core.c:ata_dev_read_id
  - drivers/usb/core/devio.c:snoop_urb_data
  - drivers/usb/core/devio.c:snoop_urb_data
  - drivers/firmware/efi/cper.c:cper_estatus_print_section
```
**Symbols:**

```
ffffffff814998b0-ffffffff81499a14: print_hex_dump (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Transformation ⚠️</summary>

```c
void print_hex_dump(const char *level, const char *prefix_str, int prefix_type, int rowsize, int groupsize, const void *buf, size_t len, bool ascii);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In lib/hexdump.c (0)
Location: lib/hexdump.c:243
Inline: False
Direct callers:
  - arch/x86/kernel/mpparse.c:smp_dump_mptable
  - arch/x86/net/bpf_jit_comp.c:bpf_int_jit_compile
  - mm/debug.c:__dump_page
  - mm/debug.c:__dump_page
  - mm/slub.c:free_debug_processing
  - mm/slub.c:print_trailer
  - mm/slub.c:print_trailer
  - mm/slub.c:print_trailer
  - mm/slub.c:print_trailer
  - mm/slub.c:print_trailer
  - fs/ext4/super.c:ext4_destroy_inode
  - drivers/ata/libata-core.c:ata_dev_read_id
  - drivers/net/tun.c:tun_do_read
  - drivers/usb/core/devio.c:snoop_urb_data
  - drivers/usb/core/devio.c:snoop_urb_data
  - drivers/firmware/efi/cper.c:cper_estatus_print_section
  - drivers/firmware/efi/apple-properties.c:map_properties
  - drivers/firmware/efi/apple-properties.c:map_properties
  - drivers/firmware/efi/apple-properties.c:map_properties
  - drivers/firmware/efi/apple-properties.c:map_properties
  - drivers/firmware/efi/apple-properties.c:map_properties
  - drivers/firmware/efi/cper-x86.c:cper_print_proc_ia
  - drivers/firmware/efi/cper-x86.c:cper_print_proc_ia
  - arch/x86/pci/early.c:early_dump_pci_device
```
**Symbols:**

```
ffffffff814cec5b-ffffffff814cecc4: print_hex_dump.cold.1 (STB_LOCAL)
ffffffff814cea90-ffffffff814ceb93: print_hex_dump (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Transformation ⚠️</summary>

```c
void print_hex_dump(const char *level, const char *prefix_str, int prefix_type, int rowsize, int groupsize, const void *buf, size_t len, bool ascii);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In lib/hexdump.c (0)
Location: lib/hexdump.c:243
Inline: False
Direct callers:
  - arch/x86/kernel/mpparse.c:smp_dump_mptable
  - arch/x86/net/bpf_jit_comp.c:bpf_int_jit_compile
  - mm/debug.c:__dump_page
  - mm/debug.c:__dump_page
  - mm/slub.c:free_debug_processing
  - mm/slub.c:print_trailer
  - mm/slub.c:print_trailer
  - mm/slub.c:print_trailer
  - mm/slub.c:print_trailer
  - mm/slub.c:print_trailer
  - fs/ext4/super.c:ext4_destroy_inode
  - drivers/pci/probe.c:early_dump_pci_device
  - drivers/ata/libata-core.c:ata_dev_read_id
  - drivers/net/tun.c:tun_do_read
  - drivers/usb/core/devio.c:snoop_urb_data
  - drivers/usb/core/devio.c:snoop_urb_data
  - drivers/firmware/efi/cper.c:cper_estatus_print_section
  - drivers/firmware/efi/apple-properties.c:map_properties
  - drivers/firmware/efi/apple-properties.c:map_properties
  - drivers/firmware/efi/apple-properties.c:map_properties
  - drivers/firmware/efi/apple-properties.c:map_properties
  - drivers/firmware/efi/apple-properties.c:map_properties
  - drivers/firmware/efi/cper-x86.c:cper_print_proc_ia
  - drivers/firmware/efi/cper-x86.c:cper_print_proc_ia
```
**Symbols:**

```
ffffffff814e354b-ffffffff814e35b4: print_hex_dump.cold.1 (STB_LOCAL)
ffffffff814e3380-ffffffff814e3483: print_hex_dump (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
void print_hex_dump(const char *level, const char *prefix_str, int prefix_type, int rowsize, int groupsize, const void *buf, size_t len, bool ascii);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In lib/hexdump.c (0)
Location: lib/hexdump.c:239
Inline: False
Direct callers:
  - arch/x86/kernel/mpparse.c:smp_dump_mptable
  - arch/x86/net/bpf_jit_comp.c:bpf_int_jit_compile
  - mm/debug.c:__dump_page
  - mm/debug.c:__dump_page
  - mm/slub.c:free_debug_processing
  - mm/slub.c:print_trailer
  - mm/slub.c:print_trailer
  - mm/slub.c:print_trailer
  - mm/slub.c:print_trailer
  - mm/slub.c:print_trailer
  - drivers/pci/probe.c:early_dump_pci_device
  - drivers/ata/libata-core.c:ata_dev_read_id
  - drivers/net/tun.c:tun_do_read
  - drivers/usb/core/devio.c:snoop_urb_data
  - drivers/usb/core/devio.c:snoop_urb_data
  - drivers/firmware/efi/cper.c:cper_estatus_print_section
  - drivers/firmware/efi/apple-properties.c:map_properties
  - drivers/firmware/efi/apple-properties.c:map_properties
  - drivers/firmware/efi/apple-properties.c:unmarshal_devices
  - drivers/firmware/efi/apple-properties.c:unmarshal_devices
  - drivers/firmware/efi/apple-properties.c:unmarshal_devices
  - drivers/firmware/efi/cper-x86.c:cper_print_proc_ia
  - drivers/firmware/efi/cper-x86.c:cper_print_proc_ia
  - net/core/skbuff.c:skb_dump
  - net/core/skbuff.c:skb_dump
  - net/core/skbuff.c:skb_dump
  - net/core/skbuff.c:skb_dump
```
**Symbols:**

```
ffffffff8150f907-ffffffff8150f970: print_hex_dump.cold (STB_LOCAL)
ffffffff8150f710-ffffffff8150f821: print_hex_dump (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
void print_hex_dump(const char *level, const char *prefix_str, int prefix_type, int rowsize, int groupsize, const void *buf, size_t len, bool ascii);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In lib/hexdump.c (0)
Location: lib/hexdump.c:239
Inline: False
Direct callers:
  - arch/x86/kernel/mpparse.c:smp_dump_mptable
  - arch/x86/net/bpf_jit_comp.c:bpf_int_jit_compile
  - mm/debug.c:__dump_page
  - mm/debug.c:__dump_page
  - mm/slub.c:free_debug_processing
  - mm/slub.c:print_trailer
  - mm/slub.c:print_trailer
  - mm/slub.c:print_trailer
  - mm/slub.c:print_trailer
  - mm/slub.c:print_trailer
  - drivers/pci/probe.c:early_dump_pci_device
  - drivers/ata/libata-core.c:ata_dev_read_id
  - drivers/net/tun.c:tun_do_read
  - drivers/usb/core/devio.c:snoop_urb_data
  - drivers/usb/core/devio.c:snoop_urb_data
  - drivers/firmware/efi/cper.c:cper_estatus_print_section
  - drivers/firmware/efi/apple-properties.c:map_properties
  - drivers/firmware/efi/apple-properties.c:map_properties
  - drivers/firmware/efi/apple-properties.c:unmarshal_devices
  - drivers/firmware/efi/apple-properties.c:unmarshal_devices
  - drivers/firmware/efi/apple-properties.c:unmarshal_devices
  - drivers/firmware/efi/cper-x86.c:cper_print_proc_ia
  - drivers/firmware/efi/cper-x86.c:cper_print_proc_ia
  - net/core/skbuff.c:skb_dump
  - net/core/skbuff.c:skb_dump
  - net/core/skbuff.c:skb_dump
  - net/core/skbuff.c:skb_dump
```
**Symbols:**

```
ffffffff8152d801-ffffffff8152d86a: print_hex_dump.cold (STB_LOCAL)
ffffffff8152d6f0-ffffffff8152d801: print_hex_dump (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
void print_hex_dump(const char *level, const char *prefix_str, int prefix_type, int rowsize, int groupsize, const void *buf, size_t len, bool ascii);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In lib/hexdump.c (0)
Location: lib/hexdump.c:239
Inline: False
Direct callers:
  - arch/x86/kernel/mpparse.c:smp_dump_mptable
  - arch/x86/net/bpf_jit_comp.c:bpf_int_jit_compile
  - mm/debug.c:__dump_page
  - mm/debug.c:__dump_page
  - mm/slub.c:print_section
  - fs/ecryptfs/debug.c:ecryptfs_dump_auth_tok
  - fs/ecryptfs/debug.c:ecryptfs_dump_auth_tok
  - drivers/pci/probe.c:early_dump_pci_device
  - drivers/ata/libata-core.c:ata_dev_read_id
  - drivers/usb/core/devio.c:snoop_urb_data
  - drivers/usb/core/devio.c:snoop_urb_data
  - drivers/firmware/efi/cper.c:cper_estatus_print_section
  - drivers/firmware/efi/cper.c:cper_print_fw_err
  - drivers/firmware/efi/apple-properties.c:map_properties
  - drivers/firmware/efi/apple-properties.c:map_properties
  - drivers/firmware/efi/apple-properties.c:unmarshal_devices
  - drivers/firmware/efi/apple-properties.c:unmarshal_key_value_pairs
  - drivers/firmware/efi/apple-properties.c:unmarshal_key_value_pairs
  - drivers/firmware/efi/cper-x86.c:cper_print_proc_ia
  - drivers/firmware/efi/cper-x86.c:cper_print_proc_ia
  - net/core/skbuff.c:skb_dump
  - net/core/skbuff.c:skb_dump
  - net/core/skbuff.c:skb_dump
  - net/core/skbuff.c:skb_dump
  - net/ipv4/route.c:ip_handle_martian_source
```
**Symbols:**

```
ffffffff8159150b-ffffffff81591574: print_hex_dump.cold (STB_LOCAL)
ffffffff81591340-ffffffff81591452: print_hex_dump (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
void print_hex_dump(const char *level, const char *prefix_str, int prefix_type, int rowsize, int groupsize, const void *buf, size_t len, bool ascii);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In lib/hexdump.c (0)
Location: lib/hexdump.c:240
Inline: False
Direct callers:
  - arch/x86/kernel/mpparse.c:smp_dump_mptable
  - arch/x86/net/bpf_jit_comp.c:bpf_int_jit_compile
  - mm/debug.c:__dump_page
  - mm/debug.c:__dump_page
  - mm/slub.c:print_section
  - fs/ecryptfs/debug.c:ecryptfs_dump_auth_tok
  - fs/ecryptfs/debug.c:ecryptfs_dump_auth_tok
  - drivers/pci/probe.c:early_dump_pci_device
  - drivers/ata/libata-core.c:ata_dev_read_id
  - drivers/usb/core/devio.c:snoop_urb_data
  - drivers/usb/core/devio.c:snoop_urb_data
  - drivers/firmware/efi/cper.c:cper_estatus_print_section
  - drivers/firmware/efi/cper.c:cper_print_fw_err
  - drivers/firmware/efi/apple-properties.c:map_properties
  - drivers/firmware/efi/apple-properties.c:map_properties
  - drivers/firmware/efi/apple-properties.c:unmarshal_devices
  - drivers/firmware/efi/apple-properties.c:unmarshal_key_value_pairs
  - drivers/firmware/efi/apple-properties.c:unmarshal_key_value_pairs
  - drivers/firmware/efi/cper-x86.c:cper_print_proc_ia
  - drivers/firmware/efi/cper-x86.c:cper_print_proc_ia
  - net/core/skbuff.c:skb_dump
  - net/core/skbuff.c:skb_dump
  - net/core/skbuff.c:skb_dump
  - net/core/skbuff.c:skb_dump
  - net/ipv4/route.c:ip_handle_martian_source
```
**Symbols:**

```
ffffffff81bf3fd0-ffffffff81bf4039: print_hex_dump.cold (STB_LOCAL)
ffffffff815adef0-ffffffff815ae002: print_hex_dump (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
void print_hex_dump(const char *level, const char *prefix_str, int prefix_type, int rowsize, int groupsize, const void *buf, size_t len, bool ascii);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In lib/hexdump.c (0)
Location: lib/hexdump.c:240
Inline: False
Direct callers:
  - arch/x86/kernel/mpparse.c:smp_dump_mptable
  - arch/x86/net/bpf_jit_comp.c:bpf_int_jit_compile
  - mm/debug.c:__dump_page
  - mm/debug.c:__dump_page
  - mm/page_poison.c:__kernel_unpoison_pages
  - mm/slub.c:print_section
  - fs/ecryptfs/debug.c:ecryptfs_dump_auth_tok
  - fs/ecryptfs/debug.c:ecryptfs_dump_auth_tok
  - drivers/pci/probe.c:early_dump_pci_device
  - drivers/ata/libata-core.c:ata_dev_read_id
  - drivers/usb/core/devio.c:snoop_urb_data
  - drivers/usb/core/devio.c:snoop_urb_data
  - drivers/firmware/efi/cper.c:cper_estatus_print_section
  - drivers/firmware/efi/apple-properties.c:map_properties
  - drivers/firmware/efi/apple-properties.c:map_properties
  - drivers/firmware/efi/apple-properties.c:unmarshal_devices
  - drivers/firmware/efi/apple-properties.c:unmarshal_key_value_pairs
  - drivers/firmware/efi/apple-properties.c:unmarshal_key_value_pairs
  - drivers/firmware/efi/cper-x86.c:cper_print_proc_ia
  - drivers/firmware/efi/cper-x86.c:cper_print_proc_ia
  - net/core/skbuff.c:skb_dump
  - net/core/skbuff.c:skb_dump
  - net/core/skbuff.c:skb_dump
  - net/core/skbuff.c:skb_dump
  - net/ipv4/route.c:ip_handle_martian_source
```
**Symbols:**

```
ffffffff81be5e4f-ffffffff81be5eb8: print_hex_dump.cold (STB_LOCAL)
ffffffff815b8b80-ffffffff815b8c92: print_hex_dump (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
void print_hex_dump(const char *level, const char *prefix_str, int prefix_type, int rowsize, int groupsize, const void *buf, size_t len, bool ascii);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In lib/hexdump.c (0)
Location: lib/hexdump.c:240
Inline: False
Direct callers:
  - arch/x86/kernel/mpparse.c:smp_dump_mptable
  - arch/x86/net/bpf_jit_comp.c:bpf_int_jit_compile
  - mm/debug.c:__dump_page
  - mm/debug.c:__dump_page
  - mm/page_poison.c:__kernel_unpoison_pages
  - mm/slub.c:print_section
  - fs/ext4/super.c:ext4_destroy_inode
  - fs/ecryptfs/debug.c:ecryptfs_dump_auth_tok
  - fs/ecryptfs/debug.c:ecryptfs_dump_auth_tok
  - drivers/pci/probe.c:early_dump_pci_device
  - drivers/ata/libata-core.c:ata_dev_read_id
  - drivers/usb/core/devio.c:snoop_urb_data
  - drivers/usb/core/devio.c:snoop_urb_data
  - drivers/firmware/efi/cper.c:cper_estatus_print_section
  - drivers/firmware/efi/apple-properties.c:map_properties
  - drivers/firmware/efi/apple-properties.c:map_properties
  - drivers/firmware/efi/apple-properties.c:unmarshal_devices
  - drivers/firmware/efi/apple-properties.c:unmarshal_key_value_pairs
  - drivers/firmware/efi/apple-properties.c:unmarshal_key_value_pairs
  - drivers/firmware/efi/cper-x86.c:cper_print_proc_ia
  - drivers/firmware/efi/cper-x86.c:cper_print_proc_ia
  - net/core/skbuff.c:skb_dump
  - net/core/skbuff.c:skb_dump
  - net/core/skbuff.c:skb_dump
  - net/core/skbuff.c:skb_dump
  - net/ipv4/route.c:ip_handle_martian_source
```
**Symbols:**

```
ffffffff81cdaf40-ffffffff81cdafa9: print_hex_dump.cold (STB_LOCAL)
ffffffff8161f3d0-ffffffff8161f4e2: print_hex_dump (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
void print_hex_dump(const char *level, const char *prefix_str, int prefix_type, int rowsize, int groupsize, const void *buf, size_t len, bool ascii);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In lib/hexdump.c (0)
Location: lib/hexdump.c:261
Inline: False
Direct callers:
  - arch/x86/kernel/mpparse.c:smp_dump_mptable
  - arch/x86/net/bpf_jit_comp.c:bpf_int_jit_compile
  - mm/debug.c:__dump_page
  - mm/debug.c:__dump_page
  - mm/page_poison.c:__kernel_unpoison_pages
  - mm/slub.c:print_section
  - fs/ext4/super.c:ext4_destroy_inode
  - fs/ecryptfs/debug.c:ecryptfs_dump_auth_tok
  - fs/ecryptfs/debug.c:ecryptfs_dump_auth_tok
  - drivers/pci/probe.c:early_dump_pci_device
  - drivers/ata/libata-core.c:ata_dev_read_id
  - drivers/usb/core/devio.c:snoop_urb_data
  - drivers/usb/core/devio.c:snoop_urb_data
  - drivers/firmware/efi/cper.c:cper_estatus_print_section
  - drivers/firmware/efi/apple-properties.c:map_properties
  - drivers/firmware/efi/apple-properties.c:map_properties
  - drivers/firmware/efi/apple-properties.c:unmarshal_devices
  - drivers/firmware/efi/apple-properties.c:unmarshal_key_value_pairs
  - drivers/firmware/efi/apple-properties.c:unmarshal_key_value_pairs
  - drivers/firmware/efi/cper-x86.c:cper_print_proc_ia
  - drivers/firmware/efi/cper-x86.c:cper_print_proc_ia
  - net/core/skbuff.c:skb_dump
  - net/core/skbuff.c:skb_dump
  - net/core/skbuff.c:skb_dump
  - net/core/skbuff.c:skb_dump
  - net/ipv4/route.c:ip_handle_martian_source
```
**Symbols:**

```
ffffffff81e93809-ffffffff81e93872: print_hex_dump.cold (STB_LOCAL)
ffffffff816ed690-ffffffff816ed7f8: print_hex_dump (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void print_hex_dump(const char *level, const char *prefix_str, int prefix_type, int rowsize, int groupsize, const void *buf, size_t len, bool ascii);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/hexdump.c (ffffffff817de040)
Location: lib/hexdump.c:261
Inline: False
Direct callers:
  - arch/x86/kernel/mpparse.c:check_physptr
  - arch/x86/net/bpf_jit_comp.c:bpf_int_jit_compile
  - mm/debug.c:__dump_page
  - mm/debug.c:__dump_page
  - mm/page_poison.c:__kernel_unpoison_pages
  - mm/slub.c:free_debug_processing
  - mm/slub.c:slab_pad_check
  - mm/slub.c:print_trailer
  - mm/slub.c:print_trailer
  - mm/slub.c:print_trailer
  - mm/slub.c:print_trailer
  - mm/slub.c:print_trailer
  - fs/ext4/super.c:ext4_destroy_inode
  - fs/ecryptfs/debug.c:ecryptfs_dump_auth_tok
  - fs/ecryptfs/debug.c:ecryptfs_dump_auth_tok
  - drivers/pci/probe.c:early_dump_pci_device
  - drivers/ata/libata-core.c:ata_dev_read_id
  - drivers/usb/core/devio.c:snoop_urb_data
  - drivers/usb/core/devio.c:snoop_urb_data
  - drivers/firmware/efi/cper.c:cper_estatus_print_section
  - drivers/firmware/efi/cper_cxl.c:cper_print_prot_err
  - drivers/firmware/efi/cper_cxl.c:cper_print_prot_err
  - drivers/firmware/efi/cper_cxl.c:cper_print_prot_err
  - drivers/firmware/efi/apple-properties.c:map_properties
  - drivers/firmware/efi/apple-properties.c:map_properties
  - drivers/firmware/efi/apple-properties.c:unmarshal_devices
  - drivers/firmware/efi/apple-properties.c:unmarshal_key_value_pairs
  - drivers/firmware/efi/apple-properties.c:unmarshal_key_value_pairs
  - drivers/firmware/efi/cper-x86.c:cper_print_proc_ia
  - drivers/firmware/efi/cper-x86.c:cper_print_proc_ia
  - net/core/skbuff.c:skb_dump
  - net/core/skbuff.c:skb_dump
  - net/core/skbuff.c:skb_dump
  - net/core/skbuff.c:skb_dump
  - net/ipv4/route.c:ip_handle_martian_source
```
**Symbols:**

```
ffffffff817de040-ffffffff817de1f0: print_hex_dump (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void print_hex_dump(const char *level, const char *prefix_str, int prefix_type, int rowsize, int groupsize, const void *buf, size_t len, bool ascii);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/hexdump.c (ffffffff8181d830)
Location: lib/hexdump.c:261
Inline: False
Direct callers:
  - arch/x86/kernel/mpparse.c:check_physptr
  - arch/x86/net/bpf_jit_comp.c:bpf_int_jit_compile
  - mm/debug.c:__dump_page
  - mm/debug.c:__dump_page
  - mm/page_poison.c:__kernel_unpoison_pages
  - mm/slub.c:free_debug_processing
  - mm/slub.c:slab_pad_check
  - mm/slub.c:print_trailer
  - mm/slub.c:print_trailer
  - mm/slub.c:print_trailer
  - mm/slub.c:print_trailer
  - mm/slub.c:print_trailer
  - fs/ext4/super.c:ext4_destroy_inode
  - fs/ecryptfs/debug.c:ecryptfs_dump_auth_tok
  - fs/ecryptfs/debug.c:ecryptfs_dump_auth_tok
  - drivers/pci/probe.c:early_dump_pci_device
  - drivers/ata/libata-core.c:ata_dev_read_id
  - drivers/usb/core/devio.c:snoop_urb_data
  - drivers/usb/core/devio.c:snoop_urb_data
  - drivers/firmware/efi/cper.c:cper_estatus_print_section
  - drivers/firmware/efi/cper_cxl.c:cper_print_prot_err
  - drivers/firmware/efi/cper_cxl.c:cper_print_prot_err
  - drivers/firmware/efi/cper_cxl.c:cper_print_prot_err
  - drivers/firmware/efi/apple-properties.c:map_properties
  - drivers/firmware/efi/apple-properties.c:map_properties
  - drivers/firmware/efi/apple-properties.c:unmarshal_devices
  - drivers/firmware/efi/apple-properties.c:unmarshal_key_value_pairs
  - drivers/firmware/efi/apple-properties.c:unmarshal_key_value_pairs
  - drivers/firmware/efi/cper-x86.c:cper_print_proc_ia
  - drivers/firmware/efi/cper-x86.c:cper_print_proc_ia
  - net/core/skbuff.c:skb_dump
  - net/core/skbuff.c:skb_dump
  - net/core/skbuff.c:skb_dump
  - net/core/skbuff.c:skb_dump
  - net/ipv4/route.c:ip_handle_martian_source
```
**Symbols:**

```
ffffffff8181d830-ffffffff8181d9de: print_hex_dump (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void print_hex_dump(const char *level, const char *prefix_str, int prefix_type, int rowsize, int groupsize, const void *buf, size_t len, bool ascii);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/hexdump.c (ffffffff818636a0)
Location: lib/hexdump.c:261
Inline: False
Direct callers:
  - arch/x86/kernel/mpparse.c:check_physptr
  - arch/x86/net/bpf_jit_comp.c:bpf_int_jit_compile
  - mm/debug.c:__dump_page
  - mm/debug.c:__dump_page
  - mm/slub.c:free_debug_processing
  - mm/slub.c:slab_pad_check
  - mm/slub.c:print_trailer
  - mm/slub.c:print_trailer
  - mm/slub.c:print_trailer
  - mm/slub.c:print_trailer
  - mm/slub.c:print_trailer
  - mm/page_poison.c:__kernel_unpoison_pages
  - fs/ext4/super.c:ext4_destroy_inode
  - fs/ecryptfs/debug.c:ecryptfs_dump_auth_tok
  - fs/ecryptfs/debug.c:ecryptfs_dump_auth_tok
  - drivers/pci/probe.c:early_dump_pci_device
  - drivers/ata/libata-core.c:ata_dev_read_id
  - drivers/gpu/drm/drm_edid.c:edid_block_dump
  - drivers/usb/core/devio.c:snoop_urb_data
  - drivers/usb/core/devio.c:snoop_urb_data
  - drivers/firmware/efi/cper.c:cper_estatus_print_section
  - drivers/firmware/efi/cper_cxl.c:cper_print_prot_err
  - drivers/firmware/efi/cper_cxl.c:cper_print_prot_err
  - drivers/firmware/efi/cper_cxl.c:cper_print_prot_err
  - drivers/firmware/efi/apple-properties.c:map_properties
  - drivers/firmware/efi/apple-properties.c:map_properties
  - drivers/firmware/efi/apple-properties.c:unmarshal_devices
  - drivers/firmware/efi/apple-properties.c:unmarshal_key_value_pairs
  - drivers/firmware/efi/apple-properties.c:unmarshal_key_value_pairs
  - drivers/firmware/efi/cper-x86.c:cper_print_proc_ia
  - drivers/firmware/efi/cper-x86.c:cper_print_proc_ia
  - net/core/skbuff.c:skb_dump
  - net/core/skbuff.c:skb_dump
  - net/core/skbuff.c:skb_dump
  - net/core/skbuff.c:skb_dump
  - net/ipv4/route.c:ip_handle_martian_source
```
**Symbols:**

```
ffffffff818636a0-ffffffff8186384e: print_hex_dump (STB_GLOBAL)
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
void print_hex_dump(const char *level, const char *prefix_str, int prefix_type, int rowsize, int groupsize, const void *buf, size_t len, bool ascii);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/hexdump.c (ffff8000106397d8)
Location: lib/hexdump.c:239
Inline: False
Direct callers:
  - arch/arm64/net/bpf_jit_comp.c:bpf_int_jit_compile
  - mm/debug.c:__dump_page
  - mm/debug.c:__dump_page
  - mm/slub.c:free_debug_processing
  - mm/slub.c:print_trailer
  - mm/slub.c:print_trailer
  - mm/slub.c:print_trailer
  - mm/slub.c:print_trailer
  - mm/slub.c:print_trailer
  - drivers/pci/probe.c:early_dump_pci_device
  - drivers/ata/libata-core.c:ata_dev_read_id
  - drivers/net/tun.c:tun_do_read
  - drivers/usb/core/devio.c:snoop_urb_data
  - drivers/usb/core/devio.c:snoop_urb_data
  - drivers/firmware/efi/cper.c:cper_estatus_print_section
  - drivers/firmware/efi/cper-arm.c:cper_print_proc_arm
  - drivers/firmware/efi/cper-arm.c:cper_print_proc_arm
  - net/core/skbuff.c:skb_dump
  - net/core/skbuff.c:skb_dump
  - net/core/skbuff.c:skb_dump
  - net/core/skbuff.c:skb_dump
```
**Symbols:**

```
ffff8000106397d8-ffff80001063994c: print_hex_dump (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void print_hex_dump(const char *level, const char *prefix_str, int prefix_type, int rowsize, int groupsize, const void *buf, size_t len, bool ascii);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/hexdump.c (c07df1b8)
Location: lib/hexdump.c:239
Inline: False
Direct callers:
  - arch/arm/net/bpf_jit_32.c:bpf_int_jit_compile
  - mm/debug.c:__dump_page
  - mm/debug.c:__dump_page
  - mm/slub.c:free_debug_processing
  - mm/slub.c:print_trailer
  - mm/slub.c:print_trailer
  - mm/slub.c:print_trailer
  - mm/slub.c:print_trailer
  - mm/slub.c:print_trailer
  - drivers/pci/probe.c:early_dump_pci_device
  - drivers/ata/libata-core.c:ata_dev_read_id
  - drivers/net/tun.c:tun_do_read
  - drivers/usb/core/devio.c:snoop_urb_data
  - drivers/usb/core/devio.c:snoop_urb_data
  - net/core/skbuff.c:skb_dump
  - net/core/skbuff.c:skb_dump
  - net/core/skbuff.c:skb_dump
  - net/core/skbuff.c:skb_dump
  - net/ipv4/route.c:ip_handle_martian_source
```
**Symbols:**

```
c07df1b8-c07df31c: print_hex_dump (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void print_hex_dump(const char *level, const char *prefix_str, int prefix_type, int rowsize, int groupsize, const void *buf, size_t len, bool ascii);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/hexdump.c (c0000000007e0320)
Location: lib/hexdump.c:239
Inline: False
Direct callers:
  - arch/powerpc/net/bpf_jit_comp64.c:bpf_int_jit_compile
  - mm/debug.c:__dump_page
  - mm/debug.c:__dump_page
  - mm/slub.c:free_debug_processing
  - mm/slub.c:print_trailer
  - mm/slub.c:print_trailer
  - mm/slub.c:print_trailer
  - mm/slub.c:print_trailer
  - mm/slub.c:print_trailer
  - security/integrity/ima/ima_kexec.c:ima_dump_measurement_list
  - drivers/pci/probe.c:early_dump_pci_device
  - drivers/ata/libata-core.c:ata_dev_read_id
  - drivers/net/tun.c:tun_do_read
  - drivers/usb/core/devio.c:snoop_urb_data
  - drivers/usb/core/devio.c:snoop_urb_data
  - net/core/skbuff.c:skb_dump
  - net/core/skbuff.c:skb_dump
  - net/core/skbuff.c:skb_dump
  - net/core/skbuff.c:skb_dump
  - net/core/skbuff.c:skb_dump
  - net/ipv4/route.c:ip_handle_martian_source
```
**Symbols:**

```
c0000000007e0320-c0000000007e0540: print_hex_dump (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void print_hex_dump(const char *level, const char *prefix_str, int prefix_type, int rowsize, int groupsize, const void *buf, size_t len, bool ascii);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/hexdump.c (ffffffe00046631c)
Location: lib/hexdump.c:239
Inline: False
Direct callers:
  - arch/riscv/net/bpf_jit_comp.c:bpf_int_jit_compile
  - mm/debug.c:__dump_page
  - mm/debug.c:__dump_page
  - mm/slub.c:free_debug_processing
  - mm/slub.c:print_trailer
  - mm/slub.c:print_trailer
  - mm/slub.c:print_trailer
  - mm/slub.c:print_trailer
  - mm/slub.c:print_trailer
  - drivers/pci/probe.c:early_dump_pci_device
  - drivers/ata/libata-core.c:ata_dev_read_id
  - drivers/net/tun.c:tun_do_read
  - drivers/usb/core/devio.c:snoop_urb_data
  - drivers/usb/core/devio.c:snoop_urb_data
  - net/core/skbuff.c:skb_dump
  - net/core/skbuff.c:skb_dump
  - net/core/skbuff.c:skb_dump
  - net/core/skbuff.c:skb_dump
  - net/core/skbuff.c:skb_dump
  - net/ipv4/route.c:ip_handle_martian_source
```
**Symbols:**

```
ffffffe00046631c-ffffffe00046643c: print_hex_dump (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Transformation ⚠️</summary>

```c
void print_hex_dump(const char *level, const char *prefix_str, int prefix_type, int rowsize, int groupsize, const void *buf, size_t len, bool ascii);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In lib/hexdump.c (0)
Location: lib/hexdump.c:239
Inline: False
Direct callers:
  - arch/x86/kernel/mpparse.c:smp_dump_mptable
  - arch/x86/net/bpf_jit_comp.c:bpf_int_jit_compile
  - mm/debug.c:__dump_page
  - mm/debug.c:__dump_page
  - mm/slub.c:free_debug_processing
  - mm/slub.c:print_trailer
  - mm/slub.c:print_trailer
  - mm/slub.c:print_trailer
  - mm/slub.c:print_trailer
  - mm/slub.c:print_trailer
  - drivers/pci/probe.c:early_dump_pci_device
  - drivers/ata/libata-core.c:ata_dev_read_id
  - drivers/net/tun.c:tun_do_read
  - drivers/usb/core/devio.c:snoop_urb_data
  - drivers/usb/core/devio.c:snoop_urb_data
  - drivers/firmware/efi/apple-properties.c:map_properties
  - drivers/firmware/efi/apple-properties.c:map_properties
  - drivers/firmware/efi/apple-properties.c:unmarshal_devices
  - drivers/firmware/efi/apple-properties.c:unmarshal_devices
  - drivers/firmware/efi/apple-properties.c:unmarshal_devices
  - net/core/skbuff.c:skb_dump
  - net/core/skbuff.c:skb_dump
  - net/core/skbuff.c:skb_dump
  - net/core/skbuff.c:skb_dump
```
**Symbols:**

```
ffffffff81525de1-ffffffff81525e4a: print_hex_dump.cold (STB_LOCAL)
ffffffff81525cd0-ffffffff81525de1: print_hex_dump (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Transformation ⚠️</summary>

```c
void print_hex_dump(const char *level, const char *prefix_str, int prefix_type, int rowsize, int groupsize, const void *buf, size_t len, bool ascii);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In lib/hexdump.c (0)
Location: lib/hexdump.c:239
Inline: False
Direct callers:
  - arch/x86/kernel/mpparse.c:smp_dump_mptable
  - arch/x86/net/bpf_jit_comp.c:bpf_int_jit_compile
  - mm/debug.c:__dump_page
  - mm/debug.c:__dump_page
  - mm/slub.c:free_debug_processing
  - mm/slub.c:print_trailer
  - mm/slub.c:print_trailer
  - mm/slub.c:print_trailer
  - mm/slub.c:print_trailer
  - mm/slub.c:print_trailer
  - drivers/pci/probe.c:early_dump_pci_device
  - drivers/acpi/nfit/core.c:acpi_nfit_ctl
  - drivers/acpi/nfit/core.c:acpi_nfit_ctl
  - drivers/ata/libata-core.c:ata_dev_read_id
  - drivers/net/tun.c:tun_do_read
  - drivers/usb/core/devio.c:snoop_urb_data
  - drivers/usb/core/devio.c:snoop_urb_data
  - drivers/firmware/efi/cper.c:cper_estatus_print_section
  - drivers/firmware/efi/apple-properties.c:map_properties
  - drivers/firmware/efi/apple-properties.c:map_properties
  - drivers/firmware/efi/apple-properties.c:unmarshal_devices
  - drivers/firmware/efi/apple-properties.c:unmarshal_devices
  - drivers/firmware/efi/apple-properties.c:unmarshal_devices
  - drivers/firmware/efi/cper-x86.c:cper_print_proc_ia
  - drivers/firmware/efi/cper-x86.c:cper_print_proc_ia
  - drivers/hv/channel_mgmt.c:vmbus_onmessage
  - drivers/hv/channel_mgmt.c:vmbus_onoffer
  - drivers/hv/channel_mgmt.c:vmbus_onoffer
  - net/core/skbuff.c:skb_dump
  - net/core/skbuff.c:skb_dump
  - net/core/skbuff.c:skb_dump
  - net/core/skbuff.c:skb_dump
```
**Symbols:**

```
ffffffff815160c1-ffffffff8151612a: print_hex_dump.cold (STB_LOCAL)
ffffffff81515fb0-ffffffff815160c1: print_hex_dump (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Transformation ⚠️</summary>

```c
void print_hex_dump(const char *level, const char *prefix_str, int prefix_type, int rowsize, int groupsize, const void *buf, size_t len, bool ascii);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In lib/hexdump.c (0)
Location: lib/hexdump.c:239
Inline: False
Direct callers:
  - arch/x86/kernel/mpparse.c:smp_dump_mptable
  - arch/x86/net/bpf_jit_comp.c:bpf_int_jit_compile
  - mm/debug.c:__dump_page
  - mm/debug.c:__dump_page
  - mm/slub.c:free_debug_processing
  - mm/slub.c:print_trailer
  - mm/slub.c:print_trailer
  - mm/slub.c:print_trailer
  - mm/slub.c:print_trailer
  - mm/slub.c:print_trailer
  - drivers/pci/probe.c:early_dump_pci_device
  - drivers/ata/libata-core.c:ata_dev_read_id
  - drivers/net/tun.c:tun_do_read
  - drivers/usb/core/devio.c:snoop_urb_data
  - drivers/usb/core/devio.c:snoop_urb_data
  - drivers/firmware/efi/cper.c:cper_estatus_print_section
  - drivers/firmware/efi/apple-properties.c:map_properties
  - drivers/firmware/efi/apple-properties.c:map_properties
  - drivers/firmware/efi/apple-properties.c:unmarshal_devices
  - drivers/firmware/efi/apple-properties.c:unmarshal_devices
  - drivers/firmware/efi/apple-properties.c:unmarshal_devices
  - drivers/firmware/efi/cper-x86.c:cper_print_proc_ia
  - drivers/firmware/efi/cper-x86.c:cper_print_proc_ia
  - net/core/skbuff.c:skb_dump
  - net/core/skbuff.c:skb_dump
  - net/core/skbuff.c:skb_dump
  - net/core/skbuff.c:skb_dump
```
**Symbols:**

```
ffffffff81521e71-ffffffff81521eda: print_hex_dump.cold (STB_LOCAL)
ffffffff81521d60-ffffffff81521e71: print_hex_dump (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
void print_hex_dump(const char *level, const char *prefix_str, int prefix_type, int rowsize, int groupsize, const void *buf, size_t len, bool ascii);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In lib/hexdump.c (0)
Location: lib/hexdump.c:239
Inline: False
Direct callers:
  - arch/x86/kernel/mpparse.c:smp_dump_mptable
  - arch/x86/net/bpf_jit_comp.c:bpf_int_jit_compile
  - mm/debug.c:__dump_page
  - mm/debug.c:__dump_page
  - mm/slub.c:free_debug_processing
  - mm/slub.c:print_trailer
  - mm/slub.c:print_trailer
  - mm/slub.c:print_trailer
  - mm/slub.c:print_trailer
  - mm/slub.c:print_trailer
  - drivers/pci/probe.c:early_dump_pci_device
  - drivers/ata/libata-core.c:ata_dev_read_id
  - drivers/net/tun.c:tun_do_read
  - drivers/usb/core/devio.c:snoop_urb_data
  - drivers/usb/core/devio.c:snoop_urb_data
  - drivers/firmware/efi/cper.c:cper_estatus_print_section
  - drivers/firmware/efi/apple-properties.c:map_properties
  - drivers/firmware/efi/apple-properties.c:map_properties
  - drivers/firmware/efi/apple-properties.c:unmarshal_devices
  - drivers/firmware/efi/apple-properties.c:unmarshal_devices
  - drivers/firmware/efi/apple-properties.c:unmarshal_devices
  - drivers/firmware/efi/cper-x86.c:cper_print_proc_ia
  - drivers/firmware/efi/cper-x86.c:cper_print_proc_ia
  - net/core/skbuff.c:skb_dump
  - net/core/skbuff.c:skb_dump
  - net/core/skbuff.c:skb_dump
  - net/core/skbuff.c:skb_dump
```
**Symbols:**

```
ffffffff8153b7f1-ffffffff8153b85a: print_hex_dump.cold (STB_LOCAL)
ffffffff8153b6e0-ffffffff8153b7f1: print_hex_dump (STB_GLOBAL)
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
