# Function: <code>crc32_le</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
u32 crc32_le(u32 crc, const unsigned char *p, size_t len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/crc32.c (ffffffff81406c10)
Location: lib/crc32.c:194
Inline: False
Direct callers:
  - kernel/power/swap.c:crc32_threadfn
  - block/partitions/efi.c:is_gpt_valid
  - block/partitions/efi.c:is_gpt_valid
  - lib/xz/xz_dec_stream.c:xz_dec_run
  - lib/xz/xz_dec_stream.c:xz_dec_run
  - lib/xz/xz_dec_stream.c:xz_dec_run
  - lib/xz/xz_dec_stream.c:xz_dec_run
  - lib/xz/xz_dec_stream.c:xz_dec_run
  - lib/xz/xz_dec_stream.c:xz_dec_run
  - drivers/video/console/fbcon.c:fbcon_set_font
  - drivers/net/tun.c:tun_net_xmit
  - drivers/net/tun.c:__tun_chr_ioctl
```
**Symbols:**

```
ffffffff81406c10-ffffffff81406d0e: crc32_le (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
u32 crc32_le(u32 crc, const unsigned char *p, size_t len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/crc32.c (ffffffff8144e920)
Location: lib/crc32.c:194
Inline: False
Direct callers:
  - kernel/power/swap.c:crc32_threadfn
  - block/partitions/efi.c:is_gpt_valid
  - block/partitions/efi.c:is_gpt_valid
  - lib/xz/xz_dec_stream.c:xz_dec_run
  - lib/xz/xz_dec_stream.c:xz_dec_run
  - lib/xz/xz_dec_stream.c:xz_dec_run
  - lib/xz/xz_dec_stream.c:xz_dec_run
  - lib/xz/xz_dec_stream.c:xz_dec_run
  - lib/xz/xz_dec_stream.c:xz_dec_run
  - drivers/video/console/fbcon.c:fbcon_set_font
  - drivers/net/tun.c:__tun_chr_ioctl
  - drivers/net/tun.c:tun_net_xmit
```
**Symbols:**

```
ffffffff8144e920-ffffffff8144ea81: crc32_le (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
u32 crc32_le(u32 crc, const unsigned char *p, size_t len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/crc32.c (ffffffff8146d2e0)
Location: lib/crc32.c:194
Inline: False
Direct callers:
  - kernel/power/swap.c:crc32_threadfn
  - block/partitions/efi.c:is_gpt_valid
  - block/partitions/efi.c:is_gpt_valid
  - lib/xz/xz_dec_stream.c:xz_dec_run
  - lib/xz/xz_dec_stream.c:xz_dec_run
  - lib/xz/xz_dec_stream.c:xz_dec_run
  - lib/xz/xz_dec_stream.c:xz_dec_run
  - lib/xz/xz_dec_stream.c:xz_dec_run
  - lib/xz/xz_dec_stream.c:xz_dec_run
  - drivers/video/console/fbcon.c:fbcon_set_font
  - drivers/net/tun.c:__tun_chr_ioctl
  - drivers/net/tun.c:tun_net_xmit
```
**Symbols:**

```
ffffffff8146d2e0-ffffffff8146d441: crc32_le (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
u32 crc32_le(u32 crc, const unsigned char *p, size_t len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/crc32.c (ffffffff814729c0)
Location: lib/crc32.c:194
Inline: False
Direct callers:
  - kernel/power/swap.c:crc32_threadfn
  - lib/xz/xz_dec_stream.c:xz_dec_run
  - lib/xz/xz_dec_stream.c:xz_dec_run
  - lib/xz/xz_dec_stream.c:xz_dec_run
  - lib/xz/xz_dec_stream.c:xz_dec_run
  - lib/xz/xz_dec_stream.c:xz_dec_run
  - lib/xz/xz_dec_stream.c:xz_dec_run
  - drivers/video/console/fbcon.c:fbcon_set_font
  - drivers/net/tun.c:__tun_chr_ioctl
  - drivers/net/tun.c:tun_net_xmit
```
**Symbols:**

```
ffffffff814729c0-ffffffff81472b1d: crc32_le (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
u32 crc32_le(u32 crc, const unsigned char *p, size_t len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/crc32.c (ffffffff8149f110)
Location: lib/crc32.c:194
Inline: False
Direct callers:
  - kernel/power/swap.c:crc32_threadfn
  - lib/xz/xz_dec_stream.c:xz_dec_run
  - lib/xz/xz_dec_stream.c:xz_dec_run
  - lib/xz/xz_dec_stream.c:xz_dec_run
  - lib/xz/xz_dec_stream.c:xz_dec_run
  - lib/xz/xz_dec_stream.c:xz_dec_run
  - lib/xz/xz_dec_stream.c:xz_dec_run
  - drivers/video/fbdev/core/fbcon.c:fbcon_set_font
  - drivers/net/tun.c:__tun_chr_ioctl
  - drivers/net/tun.c:tun_net_xmit
```
**Symbols:**

```
ffffffff8149f110-ffffffff8149f26d: crc32_le (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
u32 crc32_le(u32 crc, const unsigned char *p, size_t len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/crc32.c (ffffffff814d4330)
Location: lib/crc32.c:194
Inline: False
Direct callers:
  - kernel/power/swap.c:crc32_threadfn
  - lib/xz/xz_dec_stream.c:dec_main
  - lib/xz/xz_dec_stream.c:dec_main
  - lib/xz/xz_dec_stream.c:dec_main
  - lib/xz/xz_dec_stream.c:dec_main
  - lib/xz/xz_dec_stream.c:dec_main
  - lib/xz/xz_dec_stream.c:dec_main
  - drivers/video/fbdev/core/fbcon.c:fbcon_set_font
  - drivers/net/tun.c:__tun_chr_ioctl
  - drivers/net/tun.c:tun_net_xmit
```
**Symbols:**

```
ffffffff814d4330-ffffffff814d447b: crc32_le (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
u32 crc32_le(u32 crc, const unsigned char *p, size_t len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/crc32.c (ffffffff814e8d80)
Location: lib/crc32.c:195
Inline: False
Direct callers:
  - kernel/power/swap.c:crc32_threadfn
  - lib/xz/xz_dec_stream.c:xz_dec_run
  - lib/xz/xz_dec_stream.c:xz_dec_run
  - lib/xz/xz_dec_stream.c:xz_dec_run
  - lib/xz/xz_dec_stream.c:xz_dec_run
  - lib/xz/xz_dec_stream.c:xz_dec_run
  - lib/xz/xz_dec_stream.c:xz_dec_run
  - drivers/video/fbdev/core/fbcon.c:fbcon_set_font
  - drivers/net/tun.c:__tun_chr_ioctl
  - drivers/net/tun.c:tun_net_xmit
```
**Symbols:**

```
ffffffff814e8d80-ffffffff814e8ecb: crc32_le (STB_WEAK)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
u32 crc32_le(u32 crc, const unsigned char *p, size_t len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/crc32.c (ffffffff81515990)
Location: lib/crc32.c:195
Inline: False
Direct callers:
  - kernel/power/swap.c:crc32_threadfn
  - lib/xz/xz_dec_stream.c:xz_dec_run
  - lib/xz/xz_dec_stream.c:xz_dec_run
  - lib/xz/xz_dec_stream.c:xz_dec_run
  - lib/xz/xz_dec_stream.c:xz_dec_run
  - lib/xz/xz_dec_stream.c:xz_dec_run
  - lib/xz/xz_dec_stream.c:xz_dec_run
  - drivers/video/fbdev/core/fbcon.c:fbcon_set_font
  - drivers/net/tun.c:__tun_chr_ioctl
  - drivers/net/tun.c:tun_net_xmit
```
**Symbols:**

```
ffffffff81515990-ffffffff81515a86: crc32_le (STB_WEAK)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
u32 crc32_le(u32 crc, const unsigned char *p, size_t len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/crc32.c (ffffffff815363d0)
Location: lib/crc32.c:195
Inline: False
Direct callers:
  - kernel/power/swap.c:crc32_threadfn
  - lib/xz/xz_dec_stream.c:xz_dec_run
  - lib/xz/xz_dec_stream.c:xz_dec_run
  - lib/xz/xz_dec_stream.c:xz_dec_run
  - lib/xz/xz_dec_stream.c:xz_dec_run
  - lib/xz/xz_dec_stream.c:xz_dec_run
  - lib/xz/xz_dec_stream.c:xz_dec_run
  - drivers/video/fbdev/core/fbcon.c:fbcon_set_font
  - drivers/net/tun.c:__tun_chr_ioctl
  - drivers/net/tun.c:tun_net_xmit
```
**Symbols:**

```
ffffffff815363d0-ffffffff815364c6: crc32_le (STB_WEAK)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
u32 crc32_le(u32 crc, const unsigned char *p, size_t len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/crc32.c (ffffffff8159a910)
Location: lib/crc32.c:195
Inline: False
Direct callers:
  - kernel/power/swap.c:crc32_threadfn
  - lib/xz/xz_dec_stream.c:dec_main
  - lib/xz/xz_dec_stream.c:dec_main
  - lib/xz/xz_dec_stream.c:dec_main
  - lib/xz/xz_dec_stream.c:dec_main
  - lib/xz/xz_dec_stream.c:dec_block_header
  - lib/xz/xz_dec_stream.c:dec_index
  - lib/xz/xz_dec_stream.c:dec_index
  - lib/xz/xz_dec_stream.c:dec_block
  - lib/xz/xz_dec_stream.c:dec_block
  - drivers/video/fbdev/core/fbcon.c:fbcon_set_font
  - drivers/net/tun.c:addr_hash_test
  - drivers/net/tun.c:addr_hash_set
```
**Symbols:**

```
ffffffff8159a910-ffffffff8159a922: crc32_le (STB_WEAK)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
u32 crc32_le(u32 crc, const unsigned char *p, size_t len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/crc32.c (ffffffff815b6300)
Location: lib/crc32.c:195
Inline: False
Direct callers:
  - kernel/power/swap.c:crc32_threadfn
  - lib/xz/xz_dec_stream.c:dec_main
  - lib/xz/xz_dec_stream.c:dec_main
  - lib/xz/xz_dec_stream.c:dec_main
  - lib/xz/xz_dec_stream.c:dec_main
  - lib/xz/xz_dec_stream.c:dec_block_header
  - lib/xz/xz_dec_stream.c:dec_index
  - lib/xz/xz_dec_stream.c:dec_index
  - lib/xz/xz_dec_stream.c:dec_block
  - lib/xz/xz_dec_stream.c:dec_block
  - lib/pldmfw/pldmfw.c:pldm_parse_image
  - drivers/video/fbdev/core/fbcon.c:fbcon_set_font
  - drivers/net/tun.c:addr_hash_test
  - drivers/net/tun.c:addr_hash_set
```
**Symbols:**

```
ffffffff815b6300-ffffffff815b6312: crc32_le (STB_WEAK)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
u32 crc32_le(u32 crc, const unsigned char *p, size_t len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/crc32.c (ffffffff815c1150)
Location: lib/crc32.c:195
Inline: False
Direct callers:
  - kernel/power/swap.c:crc32_threadfn
  - lib/xz/xz_dec_stream.c:dec_main
  - lib/xz/xz_dec_stream.c:dec_main
  - lib/xz/xz_dec_stream.c:dec_main
  - lib/xz/xz_dec_stream.c:dec_main
  - lib/xz/xz_dec_stream.c:dec_main
  - lib/xz/xz_dec_stream.c:dec_main
  - lib/xz/xz_dec_stream.c:dec_main
  - lib/xz/xz_dec_stream.c:dec_main
  - lib/xz/xz_dec_stream.c:dec_block_header
  - lib/pldmfw/pldmfw.c:pldmfw_flash_image
  - drivers/video/fbdev/core/fbcon.c:fbcon_set_font
  - drivers/net/tun.c:tun_net_xmit
  - drivers/net/tun.c:update_filter
  - arch/x86/power/hibernate.c:arch_hibernation_header_restore
  - arch/x86/power/hibernate.c:arch_hibernation_header_save
```
**Symbols:**

```
ffffffff815c1150-ffffffff815c1162: crc32_le (STB_WEAK)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
u32 crc32_le(u32 crc, const unsigned char *p, size_t len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/crc32.c (ffffffff81628fc0)
Location: lib/crc32.c:195
Inline: False
Direct callers:
  - kernel/power/swap.c:crc32_threadfn
  - lib/xz/xz_dec_stream.c:dec_main
  - lib/xz/xz_dec_stream.c:dec_main
  - lib/xz/xz_dec_stream.c:dec_main
  - lib/xz/xz_dec_stream.c:dec_main
  - lib/xz/xz_dec_stream.c:dec_main
  - lib/xz/xz_dec_stream.c:dec_main
  - lib/xz/xz_dec_stream.c:dec_block_header
  - lib/xz/xz_dec_stream.c:dec_block
  - lib/xz/xz_dec_stream.c:dec_block
  - lib/pldmfw/pldmfw.c:pldmfw_flash_image
  - drivers/video/fbdev/core/fbcon.c:fbcon_set_font
  - drivers/net/tun.c:tun_net_xmit
  - drivers/net/tun.c:update_filter
  - arch/x86/power/hibernate.c:arch_hibernation_header_restore
  - arch/x86/power/hibernate.c:arch_hibernation_header_save
```
**Symbols:**

```
ffffffff81628fc0-ffffffff81628fd2: crc32_le (STB_WEAK)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
u32 crc32_le(u32 crc, const unsigned char *p, size_t len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/crc32.c (ffffffff816f9e60)
Location: lib/crc32.c:195
Inline: False
Direct callers:
  - kernel/power/swap.c:crc32_threadfn
  - block/partitions/efi.c:is_gpt_valid
  - block/partitions/efi.c:is_gpt_valid
  - lib/xz/xz_dec_stream.c:dec_main
  - lib/xz/xz_dec_stream.c:dec_main
  - lib/xz/xz_dec_stream.c:dec_main
  - lib/xz/xz_dec_stream.c:dec_main
  - lib/xz/xz_dec_stream.c:dec_main
  - lib/xz/xz_dec_stream.c:dec_main
  - lib/xz/xz_dec_stream.c:dec_block_header
  - lib/xz/xz_dec_stream.c:dec_block
  - lib/xz/xz_dec_stream.c:dec_block
  - lib/pldmfw/pldmfw.c:pldmfw_flash_image
  - drivers/video/fbdev/core/fbcon.c:fbcon_set_font
  - drivers/acpi/scan.c:__acpi_device_add
  - drivers/net/tun.c:tun_net_xmit
  - drivers/net/tun.c:update_filter
  - arch/x86/power/hibernate.c:arch_hibernation_header_restore
  - arch/x86/power/hibernate.c:arch_hibernation_header_save
```
**Symbols:**

```
ffffffff816f9e60-ffffffff816f9e7e: crc32_le (STB_WEAK)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
u32 crc32_le(u32 crc, const unsigned char *p, size_t len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/crc32.c (ffffffff817ec7e0)
Location: lib/crc32.c:195
Inline: False
Direct callers:
  - kernel/power/swap.c:crc32_threadfn
  - block/partitions/efi.c:is_gpt_valid
  - block/partitions/efi.c:is_gpt_valid
  - lib/xz/xz_dec_stream.c:dec_main
  - lib/xz/xz_dec_stream.c:dec_main
  - lib/xz/xz_dec_stream.c:dec_main
  - lib/xz/xz_dec_stream.c:dec_main
  - lib/xz/xz_dec_stream.c:dec_main
  - lib/xz/xz_dec_stream.c:dec_main
  - lib/xz/xz_dec_stream.c:dec_block_header
  - lib/xz/xz_dec_stream.c:dec_block
  - lib/xz/xz_dec_stream.c:dec_block
  - lib/pldmfw/pldmfw.c:pldmfw_flash_image
  - drivers/video/fbdev/core/fbcon.c:fbcon_set_font
  - drivers/acpi/scan.c:acpi_device_add
  - drivers/net/tun.c:tun_net_xmit
  - drivers/net/tun.c:update_filter
  - arch/x86/power/hibernate.c:arch_hibernation_header_restore
  - arch/x86/power/hibernate.c:arch_hibernation_header_save
```
**Symbols:**

```
ffffffff817ec7e0-ffffffff817ec7fe: crc32_le (STB_WEAK)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
u32 crc32_le(u32 crc, const unsigned char *p, size_t len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/crc32.c (ffffffff8182c9d0)
Location: lib/crc32.c:195
Inline: False
Direct callers:
  - kernel/power/swap.c:crc32_threadfn
  - block/partitions/efi.c:is_gpt_valid
  - block/partitions/efi.c:is_gpt_valid
  - lib/xz/xz_dec_stream.c:dec_main
  - lib/xz/xz_dec_stream.c:dec_main
  - lib/xz/xz_dec_stream.c:dec_main
  - lib/xz/xz_dec_stream.c:dec_main
  - lib/xz/xz_dec_stream.c:dec_main
  - lib/xz/xz_dec_stream.c:dec_main
  - lib/xz/xz_dec_stream.c:dec_block_header
  - lib/xz/xz_dec_stream.c:dec_block
  - lib/xz/xz_dec_stream.c:dec_block
  - lib/pldmfw/pldmfw.c:pldmfw_flash_image
  - drivers/video/fbdev/core/fbcon.c:fbcon_set_font
  - drivers/acpi/scan.c:acpi_device_add
  - drivers/net/tun.c:tun_net_xmit
  - drivers/net/tun.c:update_filter
  - arch/x86/power/hibernate.c:arch_hibernation_header_restore
  - arch/x86/power/hibernate.c:arch_hibernation_header_save
```
**Symbols:**

```
ffffffff8182c9d0-ffffffff8182c9ee: crc32_le (STB_WEAK)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
u32 crc32_le(u32 crc, const unsigned char *p, size_t len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/crc32.c (ffffffff8187e560)
Location: lib/crc32.c:195
Inline: False
Direct callers:
  - kernel/power/swap.c:crc32_threadfn
  - block/partitions/efi.c:is_gpt_valid
  - block/partitions/efi.c:is_gpt_valid
  - lib/xz/xz_dec_stream.c:dec_main
  - lib/xz/xz_dec_stream.c:dec_main
  - lib/xz/xz_dec_stream.c:dec_main
  - lib/xz/xz_dec_stream.c:dec_main
  - lib/xz/xz_dec_stream.c:dec_main
  - lib/xz/xz_dec_stream.c:dec_main
  - lib/xz/xz_dec_stream.c:dec_block_header
  - lib/xz/xz_dec_stream.c:dec_block
  - lib/xz/xz_dec_stream.c:dec_block
  - lib/pldmfw/pldmfw.c:pldmfw_flash_image
  - drivers/video/fbdev/core/fbcon.c:fbcon_set_font
  - drivers/acpi/scan.c:acpi_device_add
  - drivers/net/tun.c:tun_net_xmit
  - drivers/net/tun.c:update_filter
  - arch/x86/power/hibernate.c:arch_hibernation_header_restore
  - arch/x86/power/hibernate.c:arch_hibernation_header_save
```
**Symbols:**

```
ffffffff8187e560-ffffffff8187e57e: crc32_le (STB_WEAK)
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
u32 crc32_le(u32 crc, const unsigned char *p, size_t len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/crc32.c (ffff800010642d78)
Location: lib/crc32.c:195
Inline: False
Direct callers:
  - lib/xz/xz_dec_stream.c:xz_dec_run
  - lib/xz/xz_dec_stream.c:xz_dec_run
  - lib/xz/xz_dec_stream.c:xz_dec_run
  - lib/xz/xz_dec_stream.c:xz_dec_run
  - lib/xz/xz_dec_stream.c:xz_dec_run
  - lib/xz/xz_dec_stream.c:xz_dec_run
  - drivers/video/fbdev/core/fbcon.c:fbcon_set_font
  - drivers/net/tun.c:__tun_chr_ioctl
  - drivers/net/tun.c:tun_net_xmit
  - drivers/net/ethernet/freescale/fman/fman_dtsec.c:dtsec_del_hash_mac_address
  - drivers/net/ethernet/freescale/fman/fman_dtsec.c:dtsec_del_hash_mac_address
  - drivers/net/ethernet/freescale/fman/fman_dtsec.c:dtsec_add_hash_mac_address
  - drivers/net/ethernet/freescale/fman/fman_dtsec.c:dtsec_add_hash_mac_address
  - drivers/net/ethernet/freescale/fman/fman_tgec.c:tgec_del_hash_mac_address
  - drivers/net/ethernet/freescale/fman/fman_tgec.c:tgec_add_hash_mac_address
  - drivers/net/ethernet/smsc/smc91x.c:smc_set_multicast_list
```
**Symbols:**

```
ffff800010628e00-ffff800010628edc: crc32_le (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
u32 crc32_le(u32 crc, const unsigned char *p, size_t len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/crc32.c (c07e885c)
Location: lib/crc32.c:195
Inline: False
Direct callers:
  - kernel/power/swap.c:crc32_threadfn
  - lib/xz/xz_dec_stream.c:xz_dec_run
  - lib/xz/xz_dec_stream.c:xz_dec_run
  - lib/xz/xz_dec_stream.c:xz_dec_run
  - lib/xz/xz_dec_stream.c:xz_dec_run
  - lib/xz/xz_dec_stream.c:xz_dec_run
  - lib/xz/xz_dec_stream.c:xz_dec_run
  - lib/xz/xz_dec_stream.c:index_update
  - drivers/video/fbdev/core/fbcon.c:fbcon_set_font
  - drivers/net/tun.c:tun_net_xmit
```
**Symbols:**

```
c07e885c-c07e8994: crc32_le (STB_WEAK)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
u32 crc32_le(u32 crc, const unsigned char *p, size_t len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/crc32.c (c0000000007edee0)
Location: lib/crc32.c:195
Inline: False
Direct callers:
  - lib/xz/xz_dec_stream.c:xz_dec_run
  - lib/xz/xz_dec_stream.c:xz_dec_run
  - lib/xz/xz_dec_stream.c:xz_dec_run
  - lib/xz/xz_dec_stream.c:xz_dec_run
  - lib/xz/xz_dec_stream.c:xz_dec_run
  - lib/xz/xz_dec_stream.c:xz_dec_run
  - drivers/video/fbdev/core/fbcon.c:fbcon_set_font
  - drivers/net/tun.c:__tun_chr_ioctl
  - drivers/net/tun.c:tun_net_xmit
```
**Symbols:**

```
c0000000007edee0-c0000000007ee0c8: crc32_le (STB_WEAK)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
u32 crc32_le(u32 crc, const unsigned char *p, size_t len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/crc32.c (ffffffe00046f0b8)
Location: lib/crc32.c:195
Inline: False
Direct callers:
  - lib/xz/xz_dec_stream.c:xz_dec_run
  - lib/xz/xz_dec_stream.c:xz_dec_run
  - lib/xz/xz_dec_stream.c:xz_dec_run
  - lib/xz/xz_dec_stream.c:xz_dec_run
  - lib/xz/xz_dec_stream.c:xz_dec_run
  - lib/xz/xz_dec_stream.c:xz_dec_run
  - drivers/video/fbdev/core/fbcon.c:fbcon_set_font
  - drivers/net/tun.c:tun_net_xmit
```
**Symbols:**

```
ffffffe00046f0b8-ffffffe00046f24c: crc32_le (STB_WEAK)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: ✅</summary>

```c
u32 crc32_le(u32 crc, const unsigned char *p, size_t len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/crc32.c (ffffffff8152e9b0)
Location: lib/crc32.c:195
Inline: False
Direct callers:
  - kernel/power/swap.c:crc32_threadfn
  - lib/xz/xz_dec_stream.c:xz_dec_run
  - lib/xz/xz_dec_stream.c:xz_dec_run
  - lib/xz/xz_dec_stream.c:xz_dec_run
  - lib/xz/xz_dec_stream.c:xz_dec_run
  - lib/xz/xz_dec_stream.c:xz_dec_run
  - lib/xz/xz_dec_stream.c:xz_dec_run
  - drivers/video/fbdev/core/fbcon.c:fbcon_set_font
  - drivers/net/tun.c:__tun_chr_ioctl
  - drivers/net/tun.c:tun_net_xmit
```
**Symbols:**

```
ffffffff8152e9b0-ffffffff8152eaa6: crc32_le (STB_WEAK)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
u32 crc32_le(u32 crc, const unsigned char *p, size_t len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/crc32.c (ffffffff8151ec90)
Location: lib/crc32.c:195
Inline: False
Direct callers:
  - kernel/power/swap.c:crc32_threadfn
  - lib/xz/xz_dec_stream.c:xz_dec_run
  - lib/xz/xz_dec_stream.c:xz_dec_run
  - lib/xz/xz_dec_stream.c:xz_dec_run
  - lib/xz/xz_dec_stream.c:xz_dec_run
  - lib/xz/xz_dec_stream.c:xz_dec_run
  - lib/xz/xz_dec_stream.c:xz_dec_run
  - drivers/video/fbdev/core/fbcon.c:fbcon_set_font
  - drivers/net/tun.c:__tun_chr_ioctl
  - drivers/net/tun.c:tun_net_xmit
```
**Symbols:**

```
ffffffff8151ec90-ffffffff8151ed86: crc32_le (STB_WEAK)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
u32 crc32_le(u32 crc, const unsigned char *p, size_t len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/crc32.c (ffffffff8152a650)
Location: lib/crc32.c:195
Inline: False
Direct callers:
  - kernel/power/swap.c:crc32_threadfn
  - lib/xz/xz_dec_stream.c:xz_dec_run
  - lib/xz/xz_dec_stream.c:xz_dec_run
  - lib/xz/xz_dec_stream.c:xz_dec_run
  - lib/xz/xz_dec_stream.c:xz_dec_run
  - lib/xz/xz_dec_stream.c:xz_dec_run
  - lib/xz/xz_dec_stream.c:xz_dec_run
  - drivers/video/fbdev/core/fbcon.c:fbcon_set_font
  - drivers/net/tun.c:__tun_chr_ioctl
  - drivers/net/tun.c:tun_net_xmit
```
**Symbols:**

```
ffffffff8152a650-ffffffff8152a746: crc32_le (STB_WEAK)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
u32 crc32_le(u32 crc, const unsigned char *p, size_t len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/crc32.c (ffffffff81544450)
Location: lib/crc32.c:195
Inline: False
Direct callers:
  - kernel/power/swap.c:crc32_threadfn
  - lib/xz/xz_dec_stream.c:xz_dec_run
  - lib/xz/xz_dec_stream.c:xz_dec_run
  - lib/xz/xz_dec_stream.c:xz_dec_run
  - lib/xz/xz_dec_stream.c:xz_dec_run
  - lib/xz/xz_dec_stream.c:xz_dec_run
  - lib/xz/xz_dec_stream.c:xz_dec_run
  - drivers/video/fbdev/core/fbcon.c:fbcon_set_font
  - drivers/net/tun.c:__tun_chr_ioctl
  - drivers/net/tun.c:tun_net_xmit
```
**Symbols:**

```
ffffffff81544450-ffffffff81544546: crc32_le (STB_WEAK)
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
