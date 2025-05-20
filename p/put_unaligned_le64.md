# Function: <code>put_unaligned_le64</code>

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
In lib/lzo/lzo1x_compress.c (ffffffff8140dced)
Location: include/linux/unaligned/access_ok.h:47
Inline: True
Inline callers:
  - lib/lzo/lzo1x_compress.c:lzo1x_1_do_compress
  - lib/lzo/lzo1x_compress.c:lzo1x_1_do_compress
  - lib/lzo/lzo1x_compress.c:lzo1x_1_do_compress
  - lib/lzo/lzo1x_compress.c:lzo1x_1_do_compress
  - lib/lzo/lzo1x_compress.c:lzo1x_1_compress
  - lib/lzo/lzo1x_compress.c:lzo1x_1_compress
```
```
In lib/lzo/lzo1x_decompress_safe.c (ffffffff8140e1dd)
Location: include/linux/unaligned/access_ok.h:47
Inline: True
Inline callers:
  - lib/lzo/lzo1x_decompress_safe.c:lzo1x_decompress_safe
  - lib/lzo/lzo1x_decompress_safe.c:lzo1x_decompress_safe
  - lib/lzo/lzo1x_decompress_safe.c:lzo1x_decompress_safe
  - lib/lzo/lzo1x_decompress_safe.c:lzo1x_decompress_safe
```
```
In drivers/usb/core/hcd.c (ffffffff8160cb09)
Location: include/linux/unaligned/access_ok.h:47
Inline: True
```
```
In net/ipv4/tcp.c (ffffffff817668e9)
Location: include/linux/unaligned/access_ok.h:47
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_get_info
  - net/ipv4/tcp.c:tcp_get_info
  - net/ipv4/tcp.c:tcp_get_info
  - net/ipv4/tcp.c:tcp_get_info
```
```
In net/ipv6/addrconf.c (ffffffff817cb021)
Location: include/linux/unaligned/access_ok.h:47
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:inet6_fill_ifla6_attrs
  - net/ipv6/addrconf.c:inet6_fill_ifla6_attrs
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
In lib/lzo/lzo1x_compress.c (ffffffff81455d7f)
Location: include/linux/unaligned/access_ok.h:47
Inline: True
Inline callers:
  - lib/lzo/lzo1x_compress.c:lzo1x_1_compress
  - lib/lzo/lzo1x_compress.c:lzo1x_1_compress
  - lib/lzo/lzo1x_compress.c:lzo1x_1_do_compress
  - lib/lzo/lzo1x_compress.c:lzo1x_1_do_compress
  - lib/lzo/lzo1x_compress.c:lzo1x_1_do_compress
  - lib/lzo/lzo1x_compress.c:lzo1x_1_do_compress
```
```
In lib/lzo/lzo1x_decompress_safe.c (ffffffff81455f1d)
Location: include/linux/unaligned/access_ok.h:47
Inline: True
Inline callers:
  - lib/lzo/lzo1x_decompress_safe.c:lzo1x_decompress_safe
  - lib/lzo/lzo1x_decompress_safe.c:lzo1x_decompress_safe
  - lib/lzo/lzo1x_decompress_safe.c:lzo1x_decompress_safe
  - lib/lzo/lzo1x_decompress_safe.c:lzo1x_decompress_safe
```
```
In drivers/usb/core/hcd.c (ffffffff8166c689)
Location: include/linux/unaligned/access_ok.h:47
Inline: True
```
```
In net/ipv4/tcp.c (ffffffff817d2e03)
Location: include/linux/unaligned/access_ok.h:47
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_get_info
  - net/ipv4/tcp.c:tcp_get_info
  - net/ipv4/tcp.c:tcp_get_info
  - net/ipv4/tcp.c:tcp_get_info
```
```
In net/ipv6/addrconf.c (ffffffff8183824b)
Location: include/linux/unaligned/access_ok.h:47
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:inet6_fill_ifla6_attrs
  - net/ipv6/addrconf.c:inet6_fill_ifla6_attrs
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
In lib/lzo/lzo1x_compress.c (ffffffff8147473f)
Location: include/linux/unaligned/access_ok.h:47
Inline: True
Inline callers:
  - lib/lzo/lzo1x_compress.c:lzo1x_1_compress
  - lib/lzo/lzo1x_compress.c:lzo1x_1_compress
  - lib/lzo/lzo1x_compress.c:lzo1x_1_do_compress
  - lib/lzo/lzo1x_compress.c:lzo1x_1_do_compress
  - lib/lzo/lzo1x_compress.c:lzo1x_1_do_compress
  - lib/lzo/lzo1x_compress.c:lzo1x_1_do_compress
```
```
In lib/lzo/lzo1x_decompress_safe.c (ffffffff814748dd)
Location: include/linux/unaligned/access_ok.h:47
Inline: True
Inline callers:
  - lib/lzo/lzo1x_decompress_safe.c:lzo1x_decompress_safe
  - lib/lzo/lzo1x_decompress_safe.c:lzo1x_decompress_safe
  - lib/lzo/lzo1x_decompress_safe.c:lzo1x_decompress_safe
  - lib/lzo/lzo1x_decompress_safe.c:lzo1x_decompress_safe
```
```
In drivers/ata/libata-scsi.c (ffffffff8165b0f3)
Location: include/linux/unaligned/access_ok.h:47
Inline: True
Inline callers:
  - drivers/ata/libata-scsi.c:ata_scsi_write_same_xlat
  - drivers/ata/libata-scsi.c:ata_scsi_write_same_xlat
```
```
In drivers/usb/core/hcd.c (ffffffff8169a389)
Location: include/linux/unaligned/access_ok.h:47
Inline: True
```
```
In net/ipv6/addrconf.c (ffffffff81869aa9)
Location: include/linux/unaligned/access_ok.h:47
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:inet6_fill_ifla6_attrs
  - net/ipv6/addrconf.c:inet6_fill_ifla6_attrs
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
In lib/lzo/lzo1x_compress.c (ffffffff81479a18)
Location: include/linux/unaligned/access_ok.h:47
Inline: True
Inline callers:
  - lib/lzo/lzo1x_compress.c:lzo1x_1_compress
  - lib/lzo/lzo1x_compress.c:lzo1x_1_compress
  - lib/lzo/lzo1x_compress.c:lzo1x_1_do_compress
  - lib/lzo/lzo1x_compress.c:lzo1x_1_do_compress
  - lib/lzo/lzo1x_compress.c:lzo1x_1_do_compress
  - lib/lzo/lzo1x_compress.c:lzo1x_1_do_compress
```
```
In lib/lzo/lzo1x_decompress_safe.c (ffffffff81479ba0)
Location: include/linux/unaligned/access_ok.h:47
Inline: True
Inline callers:
  - lib/lzo/lzo1x_decompress_safe.c:lzo1x_decompress_safe
  - lib/lzo/lzo1x_decompress_safe.c:lzo1x_decompress_safe
  - lib/lzo/lzo1x_decompress_safe.c:lzo1x_decompress_safe
  - lib/lzo/lzo1x_decompress_safe.c:lzo1x_decompress_safe
```
```
In lib/lz4/lz4_decompress.c (ffffffff8147dd3a)
Location: include/linux/unaligned/access_ok.h:47
Inline: True
Inline callers:
  - lib/lz4/lz4_decompress.c:LZ4_decompress_fast_usingDict
  - lib/lz4/lz4_decompress.c:LZ4_decompress_fast_usingDict
  - lib/lz4/lz4_decompress.c:LZ4_decompress_fast_usingDict
  - lib/lz4/lz4_decompress.c:LZ4_decompress_fast_usingDict
  - lib/lz4/lz4_decompress.c:LZ4_decompress_fast_usingDict
  - lib/lz4/lz4_decompress.c:LZ4_decompress_fast_usingDict
  - lib/lz4/lz4_decompress.c:LZ4_decompress_fast_usingDict
  - lib/lz4/lz4_decompress.c:LZ4_decompress_fast_usingDict
  - lib/lz4/lz4_decompress.c:LZ4_decompress_fast_usingDict
  - lib/lz4/lz4_decompress.c:LZ4_decompress_fast_usingDict
  - lib/lz4/lz4_decompress.c:LZ4_decompress_fast_usingDict
  - lib/lz4/lz4_decompress.c:LZ4_decompress_fast_usingDict
  - lib/lz4/lz4_decompress.c:LZ4_decompress_fast_usingDict
  - lib/lz4/lz4_decompress.c:LZ4_decompress_fast_usingDict
  - lib/lz4/lz4_decompress.c:LZ4_decompress_fast_usingDict
  - lib/lz4/lz4_decompress.c:LZ4_decompress_fast_usingDict
  - lib/lz4/lz4_decompress.c:LZ4_decompress_fast_usingDict
  - lib/lz4/lz4_decompress.c:LZ4_decompress_fast_usingDict
  - lib/lz4/lz4_decompress.c:LZ4_decompress_fast_usingDict
  - lib/lz4/lz4_decompress.c:LZ4_decompress_fast_usingDict
  - lib/lz4/lz4_decompress.c:LZ4_decompress_safe_usingDict
  - lib/lz4/lz4_decompress.c:LZ4_decompress_safe_usingDict
  - lib/lz4/lz4_decompress.c:LZ4_decompress_safe_usingDict
  - lib/lz4/lz4_decompress.c:LZ4_decompress_safe_usingDict
  - lib/lz4/lz4_decompress.c:LZ4_decompress_safe_usingDict
  - lib/lz4/lz4_decompress.c:LZ4_decompress_safe_usingDict
  - lib/lz4/lz4_decompress.c:LZ4_decompress_safe_usingDict
  - lib/lz4/lz4_decompress.c:LZ4_decompress_safe_usingDict
  - lib/lz4/lz4_decompress.c:LZ4_decompress_safe_usingDict
  - lib/lz4/lz4_decompress.c:LZ4_decompress_safe_usingDict
  - lib/lz4/lz4_decompress.c:LZ4_decompress_safe_usingDict
  - lib/lz4/lz4_decompress.c:LZ4_decompress_safe_usingDict
  - lib/lz4/lz4_decompress.c:LZ4_decompress_safe_usingDict
  - lib/lz4/lz4_decompress.c:LZ4_decompress_safe_usingDict
  - lib/lz4/lz4_decompress.c:LZ4_decompress_safe_usingDict
  - lib/lz4/lz4_decompress.c:LZ4_decompress_safe_usingDict
  - lib/lz4/lz4_decompress.c:LZ4_decompress_safe_usingDict
  - lib/lz4/lz4_decompress.c:LZ4_decompress_safe_usingDict
  - lib/lz4/lz4_decompress.c:LZ4_decompress_safe_usingDict
  - lib/lz4/lz4_decompress.c:LZ4_decompress_safe_usingDict
  - lib/lz4/lz4_decompress.c:LZ4_decompress_fast_continue
  - lib/lz4/lz4_decompress.c:LZ4_decompress_fast_continue
  - lib/lz4/lz4_decompress.c:LZ4_decompress_fast_continue
  - lib/lz4/lz4_decompress.c:LZ4_decompress_fast_continue
  - lib/lz4/lz4_decompress.c:LZ4_decompress_fast_continue
  - lib/lz4/lz4_decompress.c:LZ4_decompress_fast_continue
  - lib/lz4/lz4_decompress.c:LZ4_decompress_fast_continue
  - lib/lz4/lz4_decompress.c:LZ4_decompress_fast_continue
  - lib/lz4/lz4_decompress.c:LZ4_decompress_fast_continue
  - lib/lz4/lz4_decompress.c:LZ4_decompress_fast_continue
  - lib/lz4/lz4_decompress.c:LZ4_decompress_safe_continue
  - lib/lz4/lz4_decompress.c:LZ4_decompress_safe_continue
  - lib/lz4/lz4_decompress.c:LZ4_decompress_safe_continue
  - lib/lz4/lz4_decompress.c:LZ4_decompress_safe_continue
  - lib/lz4/lz4_decompress.c:LZ4_decompress_safe_continue
  - lib/lz4/lz4_decompress.c:LZ4_decompress_safe_continue
  - lib/lz4/lz4_decompress.c:LZ4_decompress_safe_continue
  - lib/lz4/lz4_decompress.c:LZ4_decompress_safe_continue
  - lib/lz4/lz4_decompress.c:LZ4_decompress_safe_continue
  - lib/lz4/lz4_decompress.c:LZ4_decompress_safe_continue
  - lib/lz4/lz4_decompress.c:LZ4_decompress_fast
  - lib/lz4/lz4_decompress.c:LZ4_decompress_fast
  - lib/lz4/lz4_decompress.c:LZ4_decompress_fast
  - lib/lz4/lz4_decompress.c:LZ4_decompress_fast
  - lib/lz4/lz4_decompress.c:LZ4_decompress_fast
  - lib/lz4/lz4_decompress.c:LZ4_decompress_safe_partial
  - lib/lz4/lz4_decompress.c:LZ4_decompress_safe_partial
  - lib/lz4/lz4_decompress.c:LZ4_decompress_safe_partial
  - lib/lz4/lz4_decompress.c:LZ4_decompress_safe_partial
  - lib/lz4/lz4_decompress.c:LZ4_decompress_safe_partial
  - lib/lz4/lz4_decompress.c:LZ4_decompress_safe
  - lib/lz4/lz4_decompress.c:LZ4_decompress_safe
  - lib/lz4/lz4_decompress.c:LZ4_decompress_safe
  - lib/lz4/lz4_decompress.c:LZ4_decompress_safe
  - lib/lz4/lz4_decompress.c:LZ4_decompress_safe
```
```
In drivers/usb/core/hcd.c (ffffffff816af213)
Location: include/linux/unaligned/access_ok.h:47
Inline: True
Inline callers:
  - drivers/usb/core/hcd.c:hcd_alloc_coherent
```
```
In net/ipv6/addrconf.c (ffffffff8188df63)
Location: include/linux/unaligned/access_ok.h:47
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:inet6_fill_ifla6_attrs
  - net/ipv6/addrconf.c:inet6_fill_ifla6_attrs
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
In lib/lzo/lzo1x_compress.c (ffffffff814a6db8)
Location: include/linux/unaligned/access_ok.h:48
Inline: True
Inline callers:
  - lib/lzo/lzo1x_compress.c:lzo1x_1_compress
  - lib/lzo/lzo1x_compress.c:lzo1x_1_compress
  - lib/lzo/lzo1x_compress.c:lzo1x_1_do_compress
  - lib/lzo/lzo1x_compress.c:lzo1x_1_do_compress
  - lib/lzo/lzo1x_compress.c:lzo1x_1_do_compress
  - lib/lzo/lzo1x_compress.c:lzo1x_1_do_compress
```
```
In lib/lzo/lzo1x_decompress_safe.c (ffffffff814a6f40)
Location: include/linux/unaligned/access_ok.h:48
Inline: True
Inline callers:
  - lib/lzo/lzo1x_decompress_safe.c:lzo1x_decompress_safe
  - lib/lzo/lzo1x_decompress_safe.c:lzo1x_decompress_safe
  - lib/lzo/lzo1x_decompress_safe.c:lzo1x_decompress_safe
  - lib/lzo/lzo1x_decompress_safe.c:lzo1x_decompress_safe
```
```
In lib/lz4/lz4_decompress.c (ffffffff814aa981)
Location: include/linux/unaligned/access_ok.h:48
Inline: True
Inline callers:
  - lib/lz4/lz4_decompress.c:LZ4_decompress_fast_usingDict
  - lib/lz4/lz4_decompress.c:LZ4_decompress_fast_usingDict
  - lib/lz4/lz4_decompress.c:LZ4_decompress_fast_usingDict
  - lib/lz4/lz4_decompress.c:LZ4_decompress_fast_usingDict
  - lib/lz4/lz4_decompress.c:LZ4_decompress_fast_usingDict
  - lib/lz4/lz4_decompress.c:LZ4_decompress_fast_usingDict
  - lib/lz4/lz4_decompress.c:LZ4_decompress_fast_usingDict
  - lib/lz4/lz4_decompress.c:LZ4_decompress_fast_usingDict
  - lib/lz4/lz4_decompress.c:LZ4_decompress_fast_usingDict
  - lib/lz4/lz4_decompress.c:LZ4_decompress_fast_usingDict
  - lib/lz4/lz4_decompress.c:LZ4_decompress_fast_usingDict
  - lib/lz4/lz4_decompress.c:LZ4_decompress_fast_usingDict
  - lib/lz4/lz4_decompress.c:LZ4_decompress_fast_usingDict
  - lib/lz4/lz4_decompress.c:LZ4_decompress_fast_usingDict
  - lib/lz4/lz4_decompress.c:LZ4_decompress_fast_usingDict
  - lib/lz4/lz4_decompress.c:LZ4_decompress_fast_usingDict
  - lib/lz4/lz4_decompress.c:LZ4_decompress_fast_usingDict
  - lib/lz4/lz4_decompress.c:LZ4_decompress_fast_usingDict
  - lib/lz4/lz4_decompress.c:LZ4_decompress_fast_usingDict
  - lib/lz4/lz4_decompress.c:LZ4_decompress_fast_usingDict
  - lib/lz4/lz4_decompress.c:LZ4_decompress_safe_usingDict
  - lib/lz4/lz4_decompress.c:LZ4_decompress_safe_usingDict
  - lib/lz4/lz4_decompress.c:LZ4_decompress_safe_usingDict
  - lib/lz4/lz4_decompress.c:LZ4_decompress_safe_usingDict
  - lib/lz4/lz4_decompress.c:LZ4_decompress_safe_usingDict
  - lib/lz4/lz4_decompress.c:LZ4_decompress_safe_usingDict
  - lib/lz4/lz4_decompress.c:LZ4_decompress_safe_usingDict
  - lib/lz4/lz4_decompress.c:LZ4_decompress_safe_usingDict
  - lib/lz4/lz4_decompress.c:LZ4_decompress_safe_usingDict
  - lib/lz4/lz4_decompress.c:LZ4_decompress_safe_usingDict
  - lib/lz4/lz4_decompress.c:LZ4_decompress_safe_usingDict
  - lib/lz4/lz4_decompress.c:LZ4_decompress_safe_usingDict
  - lib/lz4/lz4_decompress.c:LZ4_decompress_safe_usingDict
  - lib/lz4/lz4_decompress.c:LZ4_decompress_safe_usingDict
  - lib/lz4/lz4_decompress.c:LZ4_decompress_safe_usingDict
  - lib/lz4/lz4_decompress.c:LZ4_decompress_safe_usingDict
  - lib/lz4/lz4_decompress.c:LZ4_decompress_safe_usingDict
  - lib/lz4/lz4_decompress.c:LZ4_decompress_safe_usingDict
  - lib/lz4/lz4_decompress.c:LZ4_decompress_safe_usingDict
  - lib/lz4/lz4_decompress.c:LZ4_decompress_safe_usingDict
  - lib/lz4/lz4_decompress.c:LZ4_decompress_fast_continue
  - lib/lz4/lz4_decompress.c:LZ4_decompress_fast_continue
  - lib/lz4/lz4_decompress.c:LZ4_decompress_fast_continue
  - lib/lz4/lz4_decompress.c:LZ4_decompress_fast_continue
  - lib/lz4/lz4_decompress.c:LZ4_decompress_fast_continue
  - lib/lz4/lz4_decompress.c:LZ4_decompress_fast_continue
  - lib/lz4/lz4_decompress.c:LZ4_decompress_fast_continue
  - lib/lz4/lz4_decompress.c:LZ4_decompress_fast_continue
  - lib/lz4/lz4_decompress.c:LZ4_decompress_fast_continue
  - lib/lz4/lz4_decompress.c:LZ4_decompress_fast_continue
  - lib/lz4/lz4_decompress.c:LZ4_decompress_safe_continue
  - lib/lz4/lz4_decompress.c:LZ4_decompress_safe_continue
  - lib/lz4/lz4_decompress.c:LZ4_decompress_safe_continue
  - lib/lz4/lz4_decompress.c:LZ4_decompress_safe_continue
  - lib/lz4/lz4_decompress.c:LZ4_decompress_safe_continue
  - lib/lz4/lz4_decompress.c:LZ4_decompress_safe_continue
  - lib/lz4/lz4_decompress.c:LZ4_decompress_safe_continue
  - lib/lz4/lz4_decompress.c:LZ4_decompress_safe_continue
  - lib/lz4/lz4_decompress.c:LZ4_decompress_safe_continue
  - lib/lz4/lz4_decompress.c:LZ4_decompress_safe_continue
  - lib/lz4/lz4_decompress.c:LZ4_decompress_fast
  - lib/lz4/lz4_decompress.c:LZ4_decompress_fast
  - lib/lz4/lz4_decompress.c:LZ4_decompress_fast
  - lib/lz4/lz4_decompress.c:LZ4_decompress_fast
  - lib/lz4/lz4_decompress.c:LZ4_decompress_fast
  - lib/lz4/lz4_decompress.c:LZ4_decompress_safe_partial
  - lib/lz4/lz4_decompress.c:LZ4_decompress_safe_partial
  - lib/lz4/lz4_decompress.c:LZ4_decompress_safe_partial
  - lib/lz4/lz4_decompress.c:LZ4_decompress_safe_partial
  - lib/lz4/lz4_decompress.c:LZ4_decompress_safe_partial
  - lib/lz4/lz4_decompress.c:LZ4_decompress_safe
  - lib/lz4/lz4_decompress.c:LZ4_decompress_safe
  - lib/lz4/lz4_decompress.c:LZ4_decompress_safe
  - lib/lz4/lz4_decompress.c:LZ4_decompress_safe
  - lib/lz4/lz4_decompress.c:LZ4_decompress_safe
```
```
In drivers/usb/core/hcd.c (ffffffff8171a803)
Location: include/linux/unaligned/access_ok.h:48
Inline: True
Inline callers:
  - drivers/usb/core/hcd.c:hcd_alloc_coherent
```
```
In net/ipv6/addrconf.c (ffffffff8190eff1)
Location: include/linux/unaligned/access_ok.h:48
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:inet6_fill_ifla6_attrs
  - net/ipv6/addrconf.c:inet6_fill_ifla6_attrs
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
In lib/lzo/lzo1x_compress.c (ffffffff814dc27e)
Location: include/linux/unaligned/access_ok.h:48
Inline: True
Inline callers:
  - lib/lzo/lzo1x_compress.c:lzo1x_1_compress
  - lib/lzo/lzo1x_compress.c:lzo1x_1_compress
  - lib/lzo/lzo1x_compress.c:lzo1x_1_do_compress
  - lib/lzo/lzo1x_compress.c:lzo1x_1_do_compress
  - lib/lzo/lzo1x_compress.c:lzo1x_1_do_compress
  - lib/lzo/lzo1x_compress.c:lzo1x_1_do_compress
```
```
In lib/lzo/lzo1x_decompress_safe.c (ffffffff814dc3dc)
Location: include/linux/unaligned/access_ok.h:48
Inline: True
Inline callers:
  - lib/lzo/lzo1x_decompress_safe.c:lzo1x_decompress_safe
  - lib/lzo/lzo1x_decompress_safe.c:lzo1x_decompress_safe
  - lib/lzo/lzo1x_decompress_safe.c:lzo1x_decompress_safe
  - lib/lzo/lzo1x_decompress_safe.c:lzo1x_decompress_safe
```
```
In lib/lz4/lz4_decompress.c (ffffffff814dfcf3)
Location: include/linux/unaligned/access_ok.h:48
Inline: True
Inline callers:
  - lib/lz4/lz4_decompress.c:LZ4_decompress_fast_usingDict
  - lib/lz4/lz4_decompress.c:LZ4_decompress_fast_usingDict
  - lib/lz4/lz4_decompress.c:LZ4_decompress_fast_usingDict
  - lib/lz4/lz4_decompress.c:LZ4_decompress_fast_usingDict
  - lib/lz4/lz4_decompress.c:LZ4_decompress_fast_usingDict
  - lib/lz4/lz4_decompress.c:LZ4_decompress_fast_usingDict
  - lib/lz4/lz4_decompress.c:LZ4_decompress_fast_usingDict
  - lib/lz4/lz4_decompress.c:LZ4_decompress_fast_usingDict
  - lib/lz4/lz4_decompress.c:LZ4_decompress_fast_usingDict
  - lib/lz4/lz4_decompress.c:LZ4_decompress_fast_usingDict
  - lib/lz4/lz4_decompress.c:LZ4_decompress_fast_usingDict
  - lib/lz4/lz4_decompress.c:LZ4_decompress_fast_usingDict
  - lib/lz4/lz4_decompress.c:LZ4_decompress_fast_usingDict
  - lib/lz4/lz4_decompress.c:LZ4_decompress_fast_usingDict
  - lib/lz4/lz4_decompress.c:LZ4_decompress_fast_usingDict
  - lib/lz4/lz4_decompress.c:LZ4_decompress_fast_usingDict
  - lib/lz4/lz4_decompress.c:LZ4_decompress_fast_usingDict
  - lib/lz4/lz4_decompress.c:LZ4_decompress_fast_usingDict
  - lib/lz4/lz4_decompress.c:LZ4_decompress_fast_usingDict
  - lib/lz4/lz4_decompress.c:LZ4_decompress_fast_usingDict
  - lib/lz4/lz4_decompress.c:LZ4_decompress_safe_usingDict
  - lib/lz4/lz4_decompress.c:LZ4_decompress_safe_usingDict
  - lib/lz4/lz4_decompress.c:LZ4_decompress_safe_usingDict
  - lib/lz4/lz4_decompress.c:LZ4_decompress_safe_usingDict
  - lib/lz4/lz4_decompress.c:LZ4_decompress_safe_usingDict
  - lib/lz4/lz4_decompress.c:LZ4_decompress_safe_usingDict
  - lib/lz4/lz4_decompress.c:LZ4_decompress_safe_usingDict
  - lib/lz4/lz4_decompress.c:LZ4_decompress_safe_usingDict
  - lib/lz4/lz4_decompress.c:LZ4_decompress_safe_usingDict
  - lib/lz4/lz4_decompress.c:LZ4_decompress_safe_usingDict
  - lib/lz4/lz4_decompress.c:LZ4_decompress_safe_usingDict
  - lib/lz4/lz4_decompress.c:LZ4_decompress_safe_usingDict
  - lib/lz4/lz4_decompress.c:LZ4_decompress_safe_usingDict
  - lib/lz4/lz4_decompress.c:LZ4_decompress_safe_usingDict
  - lib/lz4/lz4_decompress.c:LZ4_decompress_safe_usingDict
  - lib/lz4/lz4_decompress.c:LZ4_decompress_safe_usingDict
  - lib/lz4/lz4_decompress.c:LZ4_decompress_safe_usingDict
  - lib/lz4/lz4_decompress.c:LZ4_decompress_safe_usingDict
  - lib/lz4/lz4_decompress.c:LZ4_decompress_safe_usingDict
  - lib/lz4/lz4_decompress.c:LZ4_decompress_safe_usingDict
  - lib/lz4/lz4_decompress.c:LZ4_decompress_fast_continue
  - lib/lz4/lz4_decompress.c:LZ4_decompress_fast_continue
  - lib/lz4/lz4_decompress.c:LZ4_decompress_fast_continue
  - lib/lz4/lz4_decompress.c:LZ4_decompress_fast_continue
  - lib/lz4/lz4_decompress.c:LZ4_decompress_fast_continue
  - lib/lz4/lz4_decompress.c:LZ4_decompress_fast_continue
  - lib/lz4/lz4_decompress.c:LZ4_decompress_fast_continue
  - lib/lz4/lz4_decompress.c:LZ4_decompress_fast_continue
  - lib/lz4/lz4_decompress.c:LZ4_decompress_fast_continue
  - lib/lz4/lz4_decompress.c:LZ4_decompress_fast_continue
  - lib/lz4/lz4_decompress.c:LZ4_decompress_safe_continue
  - lib/lz4/lz4_decompress.c:LZ4_decompress_safe_continue
  - lib/lz4/lz4_decompress.c:LZ4_decompress_safe_continue
  - lib/lz4/lz4_decompress.c:LZ4_decompress_safe_continue
  - lib/lz4/lz4_decompress.c:LZ4_decompress_safe_continue
  - lib/lz4/lz4_decompress.c:LZ4_decompress_safe_continue
  - lib/lz4/lz4_decompress.c:LZ4_decompress_safe_continue
  - lib/lz4/lz4_decompress.c:LZ4_decompress_safe_continue
  - lib/lz4/lz4_decompress.c:LZ4_decompress_safe_continue
  - lib/lz4/lz4_decompress.c:LZ4_decompress_safe_continue
  - lib/lz4/lz4_decompress.c:LZ4_decompress_fast
  - lib/lz4/lz4_decompress.c:LZ4_decompress_fast
  - lib/lz4/lz4_decompress.c:LZ4_decompress_fast
  - lib/lz4/lz4_decompress.c:LZ4_decompress_fast
  - lib/lz4/lz4_decompress.c:LZ4_decompress_fast
  - lib/lz4/lz4_decompress.c:LZ4_decompress_safe_partial
  - lib/lz4/lz4_decompress.c:LZ4_decompress_safe_partial
  - lib/lz4/lz4_decompress.c:LZ4_decompress_safe_partial
  - lib/lz4/lz4_decompress.c:LZ4_decompress_safe_partial
  - lib/lz4/lz4_decompress.c:LZ4_decompress_safe_partial
  - lib/lz4/lz4_decompress.c:LZ4_decompress_safe
  - lib/lz4/lz4_decompress.c:LZ4_decompress_safe
  - lib/lz4/lz4_decompress.c:LZ4_decompress_safe
  - lib/lz4/lz4_decompress.c:LZ4_decompress_safe
  - lib/lz4/lz4_decompress.c:LZ4_decompress_safe
```
```
In drivers/usb/core/hcd.c (ffffffff81759533)
Location: include/linux/unaligned/access_ok.h:48
Inline: True
Inline callers:
  - drivers/usb/core/hcd.c:hcd_alloc_coherent
```
```
In net/ipv6/addrconf.c (ffffffff81966109)
Location: include/linux/unaligned/access_ok.h:48
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:inet6_fill_ifla6_attrs
  - net/ipv6/addrconf.c:inet6_fill_ifla6_attrs
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
In lib/lzo/lzo1x_compress.c (ffffffff814f0cee)
Location: include/linux/unaligned/access_ok.h:48
Inline: True
Inline callers:
  - lib/lzo/lzo1x_compress.c:lzo1x_1_compress
  - lib/lzo/lzo1x_compress.c:lzo1x_1_compress
  - lib/lzo/lzo1x_compress.c:lzo1x_1_do_compress
  - lib/lzo/lzo1x_compress.c:lzo1x_1_do_compress
  - lib/lzo/lzo1x_compress.c:lzo1x_1_do_compress
  - lib/lzo/lzo1x_compress.c:lzo1x_1_do_compress
```
```
In lib/lzo/lzo1x_decompress_safe.c (ffffffff814f0e4c)
Location: include/linux/unaligned/access_ok.h:48
Inline: True
Inline callers:
  - lib/lzo/lzo1x_decompress_safe.c:lzo1x_decompress_safe
  - lib/lzo/lzo1x_decompress_safe.c:lzo1x_decompress_safe
  - lib/lzo/lzo1x_decompress_safe.c:lzo1x_decompress_safe
  - lib/lzo/lzo1x_decompress_safe.c:lzo1x_decompress_safe
```
```
In lib/lz4/lz4_decompress.c (ffffffff814f2c53)
Location: include/linux/unaligned/access_ok.h:48
Inline: True
Inline callers:
  - lib/lz4/lz4_decompress.c:LZ4_decompress_fast_continue
  - lib/lz4/lz4_decompress.c:LZ4_decompress_fast_continue
  - lib/lz4/lz4_decompress.c:LZ4_decompress_fast_continue
  - lib/lz4/lz4_decompress.c:LZ4_decompress_fast_continue
  - lib/lz4/lz4_decompress.c:LZ4_decompress_fast_continue
  - lib/lz4/lz4_decompress.c:LZ4_decompress_safe_continue
  - lib/lz4/lz4_decompress.c:LZ4_decompress_safe_continue
  - lib/lz4/lz4_decompress.c:LZ4_decompress_safe_continue
  - lib/lz4/lz4_decompress.c:LZ4_decompress_safe_continue
  - lib/lz4/lz4_decompress.c:LZ4_decompress_safe_continue
  - lib/lz4/lz4_decompress.c:LZ4_decompress_fast_extDict
  - lib/lz4/lz4_decompress.c:LZ4_decompress_fast_extDict
  - lib/lz4/lz4_decompress.c:LZ4_decompress_fast_extDict
  - lib/lz4/lz4_decompress.c:LZ4_decompress_fast_extDict
  - lib/lz4/lz4_decompress.c:LZ4_decompress_fast_extDict
  - lib/lz4/lz4_decompress.c:LZ4_decompress_safe_forceExtDict
  - lib/lz4/lz4_decompress.c:LZ4_decompress_safe_forceExtDict
  - lib/lz4/lz4_decompress.c:LZ4_decompress_safe_forceExtDict
  - lib/lz4/lz4_decompress.c:LZ4_decompress_safe_forceExtDict
  - lib/lz4/lz4_decompress.c:LZ4_decompress_safe_forceExtDict
  - lib/lz4/lz4_decompress.c:LZ4_decompress_safe_withSmallPrefix
  - lib/lz4/lz4_decompress.c:LZ4_decompress_safe_withSmallPrefix
  - lib/lz4/lz4_decompress.c:LZ4_decompress_safe_withSmallPrefix
  - lib/lz4/lz4_decompress.c:LZ4_decompress_safe_withSmallPrefix
  - lib/lz4/lz4_decompress.c:LZ4_decompress_safe_withSmallPrefix
  - lib/lz4/lz4_decompress.c:LZ4_decompress_safe_withPrefix64k
  - lib/lz4/lz4_decompress.c:LZ4_decompress_safe_withPrefix64k
  - lib/lz4/lz4_decompress.c:LZ4_decompress_safe_withPrefix64k
  - lib/lz4/lz4_decompress.c:LZ4_decompress_safe_withPrefix64k
  - lib/lz4/lz4_decompress.c:LZ4_decompress_safe_withPrefix64k
  - lib/lz4/lz4_decompress.c:LZ4_decompress_fast
  - lib/lz4/lz4_decompress.c:LZ4_decompress_fast
  - lib/lz4/lz4_decompress.c:LZ4_decompress_fast
  - lib/lz4/lz4_decompress.c:LZ4_decompress_fast
  - lib/lz4/lz4_decompress.c:LZ4_decompress_fast
  - lib/lz4/lz4_decompress.c:LZ4_decompress_safe_partial
  - lib/lz4/lz4_decompress.c:LZ4_decompress_safe_partial
  - lib/lz4/lz4_decompress.c:LZ4_decompress_safe_partial
  - lib/lz4/lz4_decompress.c:LZ4_decompress_safe_partial
  - lib/lz4/lz4_decompress.c:LZ4_decompress_safe
  - lib/lz4/lz4_decompress.c:LZ4_decompress_safe
  - lib/lz4/lz4_decompress.c:LZ4_decompress_safe
  - lib/lz4/lz4_decompress.c:LZ4_decompress_safe
  - lib/lz4/lz4_decompress.c:LZ4_decompress_safe
```
```
In drivers/usb/core/hcd.c (ffffffff8177daa3)
Location: include/linux/unaligned/access_ok.h:48
Inline: True
Inline callers:
  - drivers/usb/core/hcd.c:hcd_alloc_coherent
```
```
In net/ipv6/addrconf.c (ffffffff8199b579)
Location: include/linux/unaligned/access_ok.h:48
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:inet6_fill_ifla6_attrs
  - net/ipv6/addrconf.c:inet6_fill_ifla6_attrs
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
In lib/lzo/lzo1x_compress.c (ffffffff8151db9a)
Location: include/linux/unaligned/access_ok.h:48
Inline: True
Inline callers:
  - lib/lzo/lzo1x_compress.c:lzogeneric1x_1_compress
  - lib/lzo/lzo1x_compress.c:lzogeneric1x_1_compress
  - lib/lzo/lzo1x_compress.c:lzo1x_1_do_compress
  - lib/lzo/lzo1x_compress.c:lzo1x_1_do_compress
  - lib/lzo/lzo1x_compress.c:lzo1x_1_do_compress
  - lib/lzo/lzo1x_compress.c:lzo1x_1_do_compress
```
```
In lib/lzo/lzo1x_decompress_safe.c (ffffffff8151dd69)
Location: include/linux/unaligned/access_ok.h:48
Inline: True
Inline callers:
  - lib/lzo/lzo1x_decompress_safe.c:lzo1x_decompress_safe
  - lib/lzo/lzo1x_decompress_safe.c:lzo1x_decompress_safe
  - lib/lzo/lzo1x_decompress_safe.c:lzo1x_decompress_safe
  - lib/lzo/lzo1x_decompress_safe.c:lzo1x_decompress_safe
```
```
In lib/lz4/lz4_decompress.c (ffffffff8151fca2)
Location: include/linux/unaligned/access_ok.h:48
Inline: True
Inline callers:
  - lib/lz4/lz4_decompress.c:LZ4_decompress_fast_continue
  - lib/lz4/lz4_decompress.c:LZ4_decompress_fast_continue
  - lib/lz4/lz4_decompress.c:LZ4_decompress_fast_continue
  - lib/lz4/lz4_decompress.c:LZ4_decompress_fast_continue
  - lib/lz4/lz4_decompress.c:LZ4_decompress_fast_continue
  - lib/lz4/lz4_decompress.c:LZ4_decompress_safe_continue
  - lib/lz4/lz4_decompress.c:LZ4_decompress_safe_continue
  - lib/lz4/lz4_decompress.c:LZ4_decompress_safe_continue
  - lib/lz4/lz4_decompress.c:LZ4_decompress_safe_continue
  - lib/lz4/lz4_decompress.c:LZ4_decompress_safe_continue
  - lib/lz4/lz4_decompress.c:LZ4_decompress_fast_extDict
  - lib/lz4/lz4_decompress.c:LZ4_decompress_fast_extDict
  - lib/lz4/lz4_decompress.c:LZ4_decompress_fast_extDict
  - lib/lz4/lz4_decompress.c:LZ4_decompress_fast_extDict
  - lib/lz4/lz4_decompress.c:LZ4_decompress_fast_extDict
  - lib/lz4/lz4_decompress.c:LZ4_decompress_safe_forceExtDict
  - lib/lz4/lz4_decompress.c:LZ4_decompress_safe_forceExtDict
  - lib/lz4/lz4_decompress.c:LZ4_decompress_safe_forceExtDict
  - lib/lz4/lz4_decompress.c:LZ4_decompress_safe_forceExtDict
  - lib/lz4/lz4_decompress.c:LZ4_decompress_safe_forceExtDict
  - lib/lz4/lz4_decompress.c:LZ4_decompress_safe_withSmallPrefix
  - lib/lz4/lz4_decompress.c:LZ4_decompress_safe_withSmallPrefix
  - lib/lz4/lz4_decompress.c:LZ4_decompress_safe_withSmallPrefix
  - lib/lz4/lz4_decompress.c:LZ4_decompress_safe_withSmallPrefix
  - lib/lz4/lz4_decompress.c:LZ4_decompress_safe_withSmallPrefix
  - lib/lz4/lz4_decompress.c:LZ4_decompress_safe_withPrefix64k
  - lib/lz4/lz4_decompress.c:LZ4_decompress_safe_withPrefix64k
  - lib/lz4/lz4_decompress.c:LZ4_decompress_safe_withPrefix64k
  - lib/lz4/lz4_decompress.c:LZ4_decompress_safe_withPrefix64k
  - lib/lz4/lz4_decompress.c:LZ4_decompress_safe_withPrefix64k
  - lib/lz4/lz4_decompress.c:LZ4_decompress_fast
  - lib/lz4/lz4_decompress.c:LZ4_decompress_fast
  - lib/lz4/lz4_decompress.c:LZ4_decompress_fast
  - lib/lz4/lz4_decompress.c:LZ4_decompress_fast
  - lib/lz4/lz4_decompress.c:LZ4_decompress_fast
  - lib/lz4/lz4_decompress.c:LZ4_decompress_safe_partial
  - lib/lz4/lz4_decompress.c:LZ4_decompress_safe_partial
  - lib/lz4/lz4_decompress.c:LZ4_decompress_safe_partial
  - lib/lz4/lz4_decompress.c:LZ4_decompress_safe_partial
  - lib/lz4/lz4_decompress.c:LZ4_decompress_safe
  - lib/lz4/lz4_decompress.c:LZ4_decompress_safe
  - lib/lz4/lz4_decompress.c:LZ4_decompress_safe
  - lib/lz4/lz4_decompress.c:LZ4_decompress_safe
  - lib/lz4/lz4_decompress.c:LZ4_decompress_safe
```
```
In drivers/usb/core/hcd.c (ffffffff817bc0d6)
Location: include/linux/unaligned/access_ok.h:48
Inline: True
```
```
In net/ipv6/addrconf.c (ffffffff81a074a9)
Location: include/linux/unaligned/access_ok.h:48
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:inet6_fill_ifla6_attrs
  - net/ipv6/addrconf.c:inet6_fill_ifla6_attrs
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
In lib/lzo/lzo1x_compress.c (ffffffff8153ea2a)
Location: include/linux/unaligned/access_ok.h:48
Inline: True
Inline callers:
  - lib/lzo/lzo1x_compress.c:lzogeneric1x_1_compress
  - lib/lzo/lzo1x_compress.c:lzogeneric1x_1_compress
  - lib/lzo/lzo1x_compress.c:lzo1x_1_do_compress
  - lib/lzo/lzo1x_compress.c:lzo1x_1_do_compress
  - lib/lzo/lzo1x_compress.c:lzo1x_1_do_compress
  - lib/lzo/lzo1x_compress.c:lzo1x_1_do_compress
```
```
In lib/lzo/lzo1x_decompress_safe.c (ffffffff8153ebf9)
Location: include/linux/unaligned/access_ok.h:48
Inline: True
Inline callers:
  - lib/lzo/lzo1x_decompress_safe.c:lzo1x_decompress_safe
  - lib/lzo/lzo1x_decompress_safe.c:lzo1x_decompress_safe
  - lib/lzo/lzo1x_decompress_safe.c:lzo1x_decompress_safe
  - lib/lzo/lzo1x_decompress_safe.c:lzo1x_decompress_safe
```
```
In lib/lz4/lz4_decompress.c (ffffffff81540b32)
Location: include/linux/unaligned/access_ok.h:48
Inline: True
Inline callers:
  - lib/lz4/lz4_decompress.c:LZ4_decompress_fast_continue
  - lib/lz4/lz4_decompress.c:LZ4_decompress_fast_continue
  - lib/lz4/lz4_decompress.c:LZ4_decompress_fast_continue
  - lib/lz4/lz4_decompress.c:LZ4_decompress_fast_continue
  - lib/lz4/lz4_decompress.c:LZ4_decompress_fast_continue
  - lib/lz4/lz4_decompress.c:LZ4_decompress_safe_continue
  - lib/lz4/lz4_decompress.c:LZ4_decompress_safe_continue
  - lib/lz4/lz4_decompress.c:LZ4_decompress_safe_continue
  - lib/lz4/lz4_decompress.c:LZ4_decompress_safe_continue
  - lib/lz4/lz4_decompress.c:LZ4_decompress_safe_continue
  - lib/lz4/lz4_decompress.c:LZ4_decompress_fast_extDict
  - lib/lz4/lz4_decompress.c:LZ4_decompress_fast_extDict
  - lib/lz4/lz4_decompress.c:LZ4_decompress_fast_extDict
  - lib/lz4/lz4_decompress.c:LZ4_decompress_fast_extDict
  - lib/lz4/lz4_decompress.c:LZ4_decompress_fast_extDict
  - lib/lz4/lz4_decompress.c:LZ4_decompress_safe_forceExtDict
  - lib/lz4/lz4_decompress.c:LZ4_decompress_safe_forceExtDict
  - lib/lz4/lz4_decompress.c:LZ4_decompress_safe_forceExtDict
  - lib/lz4/lz4_decompress.c:LZ4_decompress_safe_forceExtDict
  - lib/lz4/lz4_decompress.c:LZ4_decompress_safe_forceExtDict
  - lib/lz4/lz4_decompress.c:LZ4_decompress_safe_withSmallPrefix
  - lib/lz4/lz4_decompress.c:LZ4_decompress_safe_withSmallPrefix
  - lib/lz4/lz4_decompress.c:LZ4_decompress_safe_withSmallPrefix
  - lib/lz4/lz4_decompress.c:LZ4_decompress_safe_withSmallPrefix
  - lib/lz4/lz4_decompress.c:LZ4_decompress_safe_withSmallPrefix
  - lib/lz4/lz4_decompress.c:LZ4_decompress_safe_withPrefix64k
  - lib/lz4/lz4_decompress.c:LZ4_decompress_safe_withPrefix64k
  - lib/lz4/lz4_decompress.c:LZ4_decompress_safe_withPrefix64k
  - lib/lz4/lz4_decompress.c:LZ4_decompress_safe_withPrefix64k
  - lib/lz4/lz4_decompress.c:LZ4_decompress_safe_withPrefix64k
  - lib/lz4/lz4_decompress.c:LZ4_decompress_fast
  - lib/lz4/lz4_decompress.c:LZ4_decompress_fast
  - lib/lz4/lz4_decompress.c:LZ4_decompress_fast
  - lib/lz4/lz4_decompress.c:LZ4_decompress_fast
  - lib/lz4/lz4_decompress.c:LZ4_decompress_fast
  - lib/lz4/lz4_decompress.c:LZ4_decompress_safe_partial
  - lib/lz4/lz4_decompress.c:LZ4_decompress_safe_partial
  - lib/lz4/lz4_decompress.c:LZ4_decompress_safe_partial
  - lib/lz4/lz4_decompress.c:LZ4_decompress_safe_partial
  - lib/lz4/lz4_decompress.c:LZ4_decompress_safe
  - lib/lz4/lz4_decompress.c:LZ4_decompress_safe
  - lib/lz4/lz4_decompress.c:LZ4_decompress_safe
  - lib/lz4/lz4_decompress.c:LZ4_decompress_safe
  - lib/lz4/lz4_decompress.c:LZ4_decompress_safe
```
```
In drivers/usb/core/hcd.c (ffffffff817ec906)
Location: include/linux/unaligned/access_ok.h:48
Inline: True
```
```
In net/ipv6/addrconf.c (ffffffff81a3e019)
Location: include/linux/unaligned/access_ok.h:48
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:inet6_fill_ifla6_attrs
  - net/ipv6/addrconf.c:inet6_fill_ifla6_attrs
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
In lib/lzo/lzo1x_compress.c (ffffffff815a307a)
Location: include/linux/unaligned/access_ok.h:48
Inline: True
Inline callers:
  - lib/lzo/lzo1x_compress.c:lzogeneric1x_1_compress
  - lib/lzo/lzo1x_compress.c:lzogeneric1x_1_compress
  - lib/lzo/lzo1x_compress.c:lzo1x_1_do_compress
  - lib/lzo/lzo1x_compress.c:lzo1x_1_do_compress
  - lib/lzo/lzo1x_compress.c:lzo1x_1_do_compress
  - lib/lzo/lzo1x_compress.c:lzo1x_1_do_compress
```
```
In lib/lzo/lzo1x_decompress_safe.c (ffffffff815a324c)
Location: include/linux/unaligned/access_ok.h:48
Inline: True
Inline callers:
  - lib/lzo/lzo1x_decompress_safe.c:lzo1x_decompress_safe
  - lib/lzo/lzo1x_decompress_safe.c:lzo1x_decompress_safe
  - lib/lzo/lzo1x_decompress_safe.c:lzo1x_decompress_safe
  - lib/lzo/lzo1x_decompress_safe.c:lzo1x_decompress_safe
```
```
In lib/lz4/lz4_compress.c (ffffffff815a5639)
Location: include/linux/unaligned/access_ok.h:48
Inline: True
Inline callers:
  - lib/lz4/lz4_compress.c:LZ4_compress_fast_continue
  - lib/lz4/lz4_compress.c:LZ4_compress_fast_continue
  - lib/lz4/lz4_compress.c:LZ4_compress_fast_continue
  - lib/lz4/lz4_compress.c:LZ4_compress_fast_continue
  - lib/lz4/lz4_compress.c:LZ4_compress_destSize_generic
  - lib/lz4/lz4_compress.c:LZ4_compress_fast_extState
  - lib/lz4/lz4_compress.c:LZ4_compress_fast_extState
  - lib/lz4/lz4_compress.c:LZ4_compress_fast_extState
  - lib/lz4/lz4_compress.c:LZ4_compress_fast_extState
```
```
In lib/lz4/lz4_decompress.c (ffffffff815aa4a7)
Location: include/linux/unaligned/access_ok.h:48
Inline: True
Inline callers:
  - lib/lz4/lz4_decompress.c:LZ4_decompress_fast_continue
  - lib/lz4/lz4_decompress.c:LZ4_decompress_fast_continue
  - lib/lz4/lz4_decompress.c:LZ4_decompress_fast_continue
  - lib/lz4/lz4_decompress.c:LZ4_decompress_fast_continue
  - lib/lz4/lz4_decompress.c:LZ4_decompress_fast_continue
  - lib/lz4/lz4_decompress.c:LZ4_decompress_safe_continue
  - lib/lz4/lz4_decompress.c:LZ4_decompress_safe_continue
  - lib/lz4/lz4_decompress.c:LZ4_decompress_safe_continue
  - lib/lz4/lz4_decompress.c:LZ4_decompress_safe_continue
  - lib/lz4/lz4_decompress.c:LZ4_decompress_safe_continue
  - lib/lz4/lz4_decompress.c:LZ4_decompress_fast_extDict
  - lib/lz4/lz4_decompress.c:LZ4_decompress_fast_extDict
  - lib/lz4/lz4_decompress.c:LZ4_decompress_fast_extDict
  - lib/lz4/lz4_decompress.c:LZ4_decompress_fast_extDict
  - lib/lz4/lz4_decompress.c:LZ4_decompress_fast_extDict
  - lib/lz4/lz4_decompress.c:LZ4_decompress_safe_forceExtDict
  - lib/lz4/lz4_decompress.c:LZ4_decompress_safe_forceExtDict
  - lib/lz4/lz4_decompress.c:LZ4_decompress_safe_forceExtDict
  - lib/lz4/lz4_decompress.c:LZ4_decompress_safe_forceExtDict
  - lib/lz4/lz4_decompress.c:LZ4_decompress_safe_forceExtDict
  - lib/lz4/lz4_decompress.c:LZ4_decompress_safe_withSmallPrefix
  - lib/lz4/lz4_decompress.c:LZ4_decompress_safe_withSmallPrefix
  - lib/lz4/lz4_decompress.c:LZ4_decompress_safe_withSmallPrefix
  - lib/lz4/lz4_decompress.c:LZ4_decompress_safe_withSmallPrefix
  - lib/lz4/lz4_decompress.c:LZ4_decompress_safe_withSmallPrefix
  - lib/lz4/lz4_decompress.c:LZ4_decompress_safe_withPrefix64k
  - lib/lz4/lz4_decompress.c:LZ4_decompress_safe_withPrefix64k
  - lib/lz4/lz4_decompress.c:LZ4_decompress_safe_withPrefix64k
  - lib/lz4/lz4_decompress.c:LZ4_decompress_safe_withPrefix64k
  - lib/lz4/lz4_decompress.c:LZ4_decompress_safe_withPrefix64k
  - lib/lz4/lz4_decompress.c:LZ4_decompress_fast
  - lib/lz4/lz4_decompress.c:LZ4_decompress_fast
  - lib/lz4/lz4_decompress.c:LZ4_decompress_fast
  - lib/lz4/lz4_decompress.c:LZ4_decompress_fast
  - lib/lz4/lz4_decompress.c:LZ4_decompress_fast
  - lib/lz4/lz4_decompress.c:LZ4_decompress_safe_partial
  - lib/lz4/lz4_decompress.c:LZ4_decompress_safe_partial
  - lib/lz4/lz4_decompress.c:LZ4_decompress_safe_partial
  - lib/lz4/lz4_decompress.c:LZ4_decompress_safe_partial
  - lib/lz4/lz4_decompress.c:LZ4_decompress_safe
  - lib/lz4/lz4_decompress.c:LZ4_decompress_safe
  - lib/lz4/lz4_decompress.c:LZ4_decompress_safe
  - lib/lz4/lz4_decompress.c:LZ4_decompress_safe
  - lib/lz4/lz4_decompress.c:LZ4_decompress_safe
```
```
In lib/zstd/fse_compress.c (ffffffff815abe4e)
Location: include/linux/unaligned/access_ok.h:48
Inline: True
Inline callers:
  - lib/zstd/fse_compress.c:FSE_compress_usingCTable_generic
  - lib/zstd/fse_compress.c:FSE_compress_usingCTable_generic
  - lib/zstd/fse_compress.c:FSE_compress_usingCTable_generic
  - lib/zstd/fse_compress.c:FSE_compress_usingCTable_generic
  - lib/zstd/fse_compress.c:FSE_compress_usingCTable_generic
  - lib/zstd/fse_compress.c:FSE_compress_usingCTable_generic
  - lib/zstd/fse_compress.c:FSE_compress_usingCTable_generic
  - lib/zstd/fse_compress.c:FSE_compress_usingCTable_generic
  - lib/zstd/fse_compress.c:FSE_compress_usingCTable_generic
```
```
In lib/zstd/huf_compress.c (ffffffff815ad5a9)
Location: include/linux/unaligned/access_ok.h:48
Inline: True
```
```
In lib/zstd/compress.c (ffffffff815c9430)
Location: include/linux/unaligned/access_ok.h:48
Inline: True
Inline callers:
  - lib/zstd/compress.c:ZSTD_compressSequences_internal
  - lib/zstd/compress.c:ZSTD_compressSequences_internal
  - lib/zstd/compress.c:ZSTD_compressSequences_internal
  - lib/zstd/compress.c:ZSTD_compressSequences_internal
  - lib/zstd/compress.c:ZSTD_compressSequences_internal
  - lib/zstd/compress.c:ZSTD_compressSequences_internal
  - lib/zstd/compress.c:ZSTD_compressSequences_internal
  - lib/zstd/compress.c:ZSTD_compressSequences_internal
  - lib/zstd/compress.c:ZSTD_compressSequences_internal
```
```
In drivers/base/regmap/regmap.c (ffffffff817d9885)
Location: include/linux/unaligned/access_ok.h:48
Inline: True
Inline callers:
  - drivers/base/regmap/regmap.c:regmap_format_64_le
```
```
In drivers/usb/core/hcd.c (ffffffff818bbcf6)
Location: include/linux/unaligned/access_ok.h:48
Inline: True
Inline callers:
  - drivers/usb/core/hcd.c:hcd_alloc_coherent
```
```
In net/ipv4/tcp_fastopen.c (ffffffff81acd529)
Location: include/linux/unaligned/access_ok.h:48
Inline: True
Inline callers:
  - net/ipv4/tcp_fastopen.c:tcp_fastopen_get_cipher
  - net/ipv4/tcp_fastopen.c:tcp_fastopen_get_cipher
```
```
In net/ipv6/addrconf.c (ffffffff81b33845)
Location: include/linux/unaligned/access_ok.h:48
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:inet6_fill_ifla6_attrs
  - net/ipv6/addrconf.c:inet6_fill_ifla6_attrs
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
In lib/lzo/lzo1x_compress.c (ffffffff815beb90)
Location: include/linux/unaligned/access_ok.h:48
Inline: True
Inline callers:
  - lib/lzo/lzo1x_compress.c:lzogeneric1x_1_compress
  - lib/lzo/lzo1x_compress.c:lzogeneric1x_1_compress
  - lib/lzo/lzo1x_compress.c:lzo1x_1_do_compress
  - lib/lzo/lzo1x_compress.c:lzo1x_1_do_compress
  - lib/lzo/lzo1x_compress.c:lzo1x_1_do_compress
  - lib/lzo/lzo1x_compress.c:lzo1x_1_do_compress
```
```
In lib/lzo/lzo1x_decompress_safe.c (ffffffff815bed81)
Location: include/linux/unaligned/access_ok.h:48
Inline: True
Inline callers:
  - lib/lzo/lzo1x_decompress_safe.c:lzo1x_decompress_safe
  - lib/lzo/lzo1x_decompress_safe.c:lzo1x_decompress_safe
  - lib/lzo/lzo1x_decompress_safe.c:lzo1x_decompress_safe
  - lib/lzo/lzo1x_decompress_safe.c:lzo1x_decompress_safe
```
```
In lib/lz4/lz4_compress.c (ffffffff815c11c5)
Location: include/linux/unaligned/access_ok.h:48
Inline: True
Inline callers:
  - lib/lz4/lz4_compress.c:LZ4_compress_fast_continue
  - lib/lz4/lz4_compress.c:LZ4_compress_fast_continue
  - lib/lz4/lz4_compress.c:LZ4_compress_fast_continue
  - lib/lz4/lz4_compress.c:LZ4_compress_fast_continue
  - lib/lz4/lz4_compress.c:LZ4_compress_destSize_generic
  - lib/lz4/lz4_compress.c:LZ4_compress_fast_extState
  - lib/lz4/lz4_compress.c:LZ4_compress_fast_extState
  - lib/lz4/lz4_compress.c:LZ4_compress_fast_extState
  - lib/lz4/lz4_compress.c:LZ4_compress_fast_extState
```
```
In lib/lz4/lz4_decompress.c (ffffffff815c5c1c)
Location: include/linux/unaligned/access_ok.h:48
Inline: True
Inline callers:
  - lib/lz4/lz4_decompress.c:LZ4_decompress_fast_continue
  - lib/lz4/lz4_decompress.c:LZ4_decompress_fast_continue
  - lib/lz4/lz4_decompress.c:LZ4_decompress_fast_continue
  - lib/lz4/lz4_decompress.c:LZ4_decompress_fast_continue
  - lib/lz4/lz4_decompress.c:LZ4_decompress_fast_continue
  - lib/lz4/lz4_decompress.c:LZ4_decompress_safe_continue
  - lib/lz4/lz4_decompress.c:LZ4_decompress_safe_continue
  - lib/lz4/lz4_decompress.c:LZ4_decompress_safe_continue
  - lib/lz4/lz4_decompress.c:LZ4_decompress_safe_continue
  - lib/lz4/lz4_decompress.c:LZ4_decompress_safe_continue
  - lib/lz4/lz4_decompress.c:LZ4_decompress_fast_extDict
  - lib/lz4/lz4_decompress.c:LZ4_decompress_fast_extDict
  - lib/lz4/lz4_decompress.c:LZ4_decompress_fast_extDict
  - lib/lz4/lz4_decompress.c:LZ4_decompress_fast_extDict
  - lib/lz4/lz4_decompress.c:LZ4_decompress_fast_extDict
  - lib/lz4/lz4_decompress.c:LZ4_decompress_safe_forceExtDict
  - lib/lz4/lz4_decompress.c:LZ4_decompress_safe_forceExtDict
  - lib/lz4/lz4_decompress.c:LZ4_decompress_safe_forceExtDict
  - lib/lz4/lz4_decompress.c:LZ4_decompress_safe_forceExtDict
  - lib/lz4/lz4_decompress.c:LZ4_decompress_safe_forceExtDict
  - lib/lz4/lz4_decompress.c:LZ4_decompress_safe_withSmallPrefix
  - lib/lz4/lz4_decompress.c:LZ4_decompress_safe_withSmallPrefix
  - lib/lz4/lz4_decompress.c:LZ4_decompress_safe_withSmallPrefix
  - lib/lz4/lz4_decompress.c:LZ4_decompress_safe_withSmallPrefix
  - lib/lz4/lz4_decompress.c:LZ4_decompress_safe_withSmallPrefix
  - lib/lz4/lz4_decompress.c:LZ4_decompress_safe_withPrefix64k
  - lib/lz4/lz4_decompress.c:LZ4_decompress_safe_withPrefix64k
  - lib/lz4/lz4_decompress.c:LZ4_decompress_safe_withPrefix64k
  - lib/lz4/lz4_decompress.c:LZ4_decompress_safe_withPrefix64k
  - lib/lz4/lz4_decompress.c:LZ4_decompress_safe_withPrefix64k
  - lib/lz4/lz4_decompress.c:LZ4_decompress_fast
  - lib/lz4/lz4_decompress.c:LZ4_decompress_fast
  - lib/lz4/lz4_decompress.c:LZ4_decompress_fast
  - lib/lz4/lz4_decompress.c:LZ4_decompress_fast
  - lib/lz4/lz4_decompress.c:LZ4_decompress_fast
  - lib/lz4/lz4_decompress.c:LZ4_decompress_safe_partial
  - lib/lz4/lz4_decompress.c:LZ4_decompress_safe_partial
  - lib/lz4/lz4_decompress.c:LZ4_decompress_safe_partial
  - lib/lz4/lz4_decompress.c:LZ4_decompress_safe_partial
  - lib/lz4/lz4_decompress.c:LZ4_decompress_safe
  - lib/lz4/lz4_decompress.c:LZ4_decompress_safe
  - lib/lz4/lz4_decompress.c:LZ4_decompress_safe
  - lib/lz4/lz4_decompress.c:LZ4_decompress_safe
  - lib/lz4/lz4_decompress.c:LZ4_decompress_safe
```
```
In lib/zstd/fse_compress.c (ffffffff815c7955)
Location: include/linux/unaligned/access_ok.h:48
Inline: True
Inline callers:
  - lib/zstd/fse_compress.c:FSE_compress_usingCTable_generic
  - lib/zstd/fse_compress.c:FSE_compress_usingCTable_generic
  - lib/zstd/fse_compress.c:FSE_compress_usingCTable_generic
  - lib/zstd/fse_compress.c:FSE_compress_usingCTable_generic
  - lib/zstd/fse_compress.c:FSE_compress_usingCTable_generic
  - lib/zstd/fse_compress.c:FSE_compress_usingCTable_generic
  - lib/zstd/fse_compress.c:FSE_compress_usingCTable_generic
  - lib/zstd/fse_compress.c:FSE_compress_usingCTable_generic
  - lib/zstd/fse_compress.c:FSE_compress_usingCTable_generic
```
```
In lib/zstd/huf_compress.c (ffffffff815c910e)
Location: include/linux/unaligned/access_ok.h:48
Inline: True
```
```
In lib/zstd/compress.c (ffffffff815e6fa9)
Location: include/linux/unaligned/access_ok.h:48
Inline: True
Inline callers:
  - lib/zstd/compress.c:ZSTD_compressSequences_internal
  - lib/zstd/compress.c:ZSTD_compressSequences_internal
  - lib/zstd/compress.c:ZSTD_compressSequences_internal
  - lib/zstd/compress.c:ZSTD_compressSequences_internal
  - lib/zstd/compress.c:ZSTD_compressSequences_internal
  - lib/zstd/compress.c:ZSTD_compressSequences_internal
  - lib/zstd/compress.c:ZSTD_compressSequences_internal
  - lib/zstd/compress.c:ZSTD_compressSequences_internal
  - lib/zstd/compress.c:ZSTD_compressSequences_internal
```
```
In drivers/base/regmap/regmap.c (ffffffff817ee6d5)
Location: include/linux/unaligned/access_ok.h:48
Inline: True
Inline callers:
  - drivers/base/regmap/regmap.c:regmap_format_64_le
```
```
In drivers/usb/core/hcd.c (ffffffff818c8ab6)
Location: include/linux/unaligned/access_ok.h:48
Inline: True
Inline callers:
  - drivers/usb/core/hcd.c:hcd_alloc_coherent
```
```
In net/ipv4/tcp_fastopen.c (ffffffff81ad954b)
Location: include/linux/unaligned/access_ok.h:48
Inline: True
Inline callers:
  - net/ipv4/tcp_fastopen.c:tcp_fastopen_get_cipher
  - net/ipv4/tcp_fastopen.c:tcp_fastopen_get_cipher
```
```
In net/ipv6/addrconf.c (ffffffff81b42185)
Location: include/linux/unaligned/access_ok.h:48
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:inet6_fill_ifla6_attrs
  - net/ipv6/addrconf.c:inet6_fill_ifla6_attrs
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
In lib/lzo/lzo1x_compress.c (ffffffff815c980d)
Location: include/linux/unaligned/access_ok.h:48
Inline: True
Inline callers:
  - lib/lzo/lzo1x_compress.c:lzogeneric1x_1_compress
  - lib/lzo/lzo1x_compress.c:lzogeneric1x_1_compress
  - lib/lzo/lzo1x_compress.c:lzo1x_1_do_compress
  - lib/lzo/lzo1x_compress.c:lzo1x_1_do_compress
  - lib/lzo/lzo1x_compress.c:lzo1x_1_do_compress
  - lib/lzo/lzo1x_compress.c:lzo1x_1_do_compress
```
```
In lib/lzo/lzo1x_decompress_safe.c (ffffffff815c99f0)
Location: include/linux/unaligned/access_ok.h:48
Inline: True
Inline callers:
  - lib/lzo/lzo1x_decompress_safe.c:lzo1x_decompress_safe
  - lib/lzo/lzo1x_decompress_safe.c:lzo1x_decompress_safe
  - lib/lzo/lzo1x_decompress_safe.c:lzo1x_decompress_safe
  - lib/lzo/lzo1x_decompress_safe.c:lzo1x_decompress_safe
```
```
In lib/lz4/lz4_decompress.c (ffffffff815cb8e3)
Location: include/linux/unaligned/access_ok.h:48
Inline: True
Inline callers:
  - lib/lz4/lz4_decompress.c:LZ4_decompress_fast_continue
  - lib/lz4/lz4_decompress.c:LZ4_decompress_fast_continue
  - lib/lz4/lz4_decompress.c:LZ4_decompress_fast_continue
  - lib/lz4/lz4_decompress.c:LZ4_decompress_fast_continue
  - lib/lz4/lz4_decompress.c:LZ4_decompress_fast_continue
  - lib/lz4/lz4_decompress.c:LZ4_decompress_safe_continue
  - lib/lz4/lz4_decompress.c:LZ4_decompress_safe_continue
  - lib/lz4/lz4_decompress.c:LZ4_decompress_safe_continue
  - lib/lz4/lz4_decompress.c:LZ4_decompress_safe_continue
  - lib/lz4/lz4_decompress.c:LZ4_decompress_safe_continue
  - lib/lz4/lz4_decompress.c:LZ4_decompress_fast_extDict
  - lib/lz4/lz4_decompress.c:LZ4_decompress_fast_extDict
  - lib/lz4/lz4_decompress.c:LZ4_decompress_fast_extDict
  - lib/lz4/lz4_decompress.c:LZ4_decompress_fast_extDict
  - lib/lz4/lz4_decompress.c:LZ4_decompress_fast_extDict
  - lib/lz4/lz4_decompress.c:LZ4_decompress_safe_forceExtDict
  - lib/lz4/lz4_decompress.c:LZ4_decompress_safe_forceExtDict
  - lib/lz4/lz4_decompress.c:LZ4_decompress_safe_forceExtDict
  - lib/lz4/lz4_decompress.c:LZ4_decompress_safe_forceExtDict
  - lib/lz4/lz4_decompress.c:LZ4_decompress_safe_forceExtDict
  - lib/lz4/lz4_decompress.c:LZ4_decompress_safe_withSmallPrefix
  - lib/lz4/lz4_decompress.c:LZ4_decompress_safe_withSmallPrefix
  - lib/lz4/lz4_decompress.c:LZ4_decompress_safe_withSmallPrefix
  - lib/lz4/lz4_decompress.c:LZ4_decompress_safe_withSmallPrefix
  - lib/lz4/lz4_decompress.c:LZ4_decompress_safe_withSmallPrefix
  - lib/lz4/lz4_decompress.c:LZ4_decompress_safe_withPrefix64k
  - lib/lz4/lz4_decompress.c:LZ4_decompress_safe_withPrefix64k
  - lib/lz4/lz4_decompress.c:LZ4_decompress_safe_withPrefix64k
  - lib/lz4/lz4_decompress.c:LZ4_decompress_safe_withPrefix64k
  - lib/lz4/lz4_decompress.c:LZ4_decompress_safe_withPrefix64k
  - lib/lz4/lz4_decompress.c:LZ4_decompress_fast
  - lib/lz4/lz4_decompress.c:LZ4_decompress_fast
  - lib/lz4/lz4_decompress.c:LZ4_decompress_fast
  - lib/lz4/lz4_decompress.c:LZ4_decompress_fast
  - lib/lz4/lz4_decompress.c:LZ4_decompress_fast
  - lib/lz4/lz4_decompress.c:LZ4_decompress_safe_partial
  - lib/lz4/lz4_decompress.c:LZ4_decompress_safe_partial
  - lib/lz4/lz4_decompress.c:LZ4_decompress_safe_partial
  - lib/lz4/lz4_decompress.c:LZ4_decompress_safe_partial
  - lib/lz4/lz4_decompress.c:LZ4_decompress_safe
  - lib/lz4/lz4_decompress.c:LZ4_decompress_safe
  - lib/lz4/lz4_decompress.c:LZ4_decompress_safe
  - lib/lz4/lz4_decompress.c:LZ4_decompress_safe
  - lib/lz4/lz4_decompress.c:LZ4_decompress_safe
```
```
In drivers/base/regmap/regmap.c (ffffffff817d2f85)
Location: include/linux/unaligned/access_ok.h:48
Inline: True
Inline callers:
  - drivers/base/regmap/regmap.c:regmap_format_64_le
```
```
In drivers/usb/core/hcd.c (ffffffff818ac0f6)
Location: include/linux/unaligned/access_ok.h:48
Inline: True
Inline callers:
  - drivers/usb/core/hcd.c:hcd_alloc_coherent
```
```
In net/ipv4/tcp_fastopen.c (ffffffff81ac423b)
Location: include/linux/unaligned/access_ok.h:48
Inline: True
Inline callers:
  - net/ipv4/tcp_fastopen.c:tcp_fastopen_get_cipher
  - net/ipv4/tcp_fastopen.c:tcp_fastopen_get_cipher
```
```
In net/ipv6/addrconf.c (ffffffff81b30103)
Location: include/linux/unaligned/access_ok.h:48
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:inet6_fill_ifla6_attrs
  - net/ipv6/addrconf.c:inet6_fill_ifla6_attrs
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
In drivers/base/regmap/regmap.c (ffffffff8185ec4e)
Location: include/asm-generic/unaligned.h:50
Inline: True
Inline callers:
  - drivers/base/regmap/regmap.c:regmap_format_64_le
```
```
In net/ipv4/tcp_fastopen.c (ffffffff81b828c0)
Location: include/asm-generic/unaligned.h:50
Inline: True
Inline callers:
  - net/ipv4/tcp_fastopen.c:tcp_fastopen_get_cipher
  - net/ipv4/tcp_fastopen.c:tcp_fastopen_get_cipher
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
In crypto/crc64_rocksoft_generic.c (ffffffff81662476)
Location: include/asm-generic/unaligned.h:50
Inline: True
Inline callers:
  - crypto/crc64_rocksoft_generic.c:chksum_digest
  - crypto/crc64_rocksoft_generic.c:chksum_finup
  - crypto/crc64_rocksoft_generic.c:chksum_final
```
```
In lib/zstd/compress/fse_compress.c (ffffffff8170e1fd)
Location: include/asm-generic/unaligned.h:50
Inline: True
Inline callers:
  - lib/zstd/compress/fse_compress.c:FSE_compress_usingCTable_generic
  - lib/zstd/compress/fse_compress.c:FSE_compress_usingCTable_generic
  - lib/zstd/compress/fse_compress.c:FSE_compress_usingCTable_generic
  - lib/zstd/compress/fse_compress.c:FSE_compress_usingCTable_generic
  - lib/zstd/compress/fse_compress.c:FSE_compress_usingCTable_generic
  - lib/zstd/compress/fse_compress.c:FSE_compress_usingCTable_generic
  - lib/zstd/compress/fse_compress.c:FSE_compress_usingCTable_generic
  - lib/zstd/compress/fse_compress.c:FSE_compress_usingCTable_generic
  - lib/zstd/compress/fse_compress.c:FSE_compress_usingCTable_generic
```
```
In lib/zstd/compress/huf_compress.c (ffffffff8170faeb)
Location: include/asm-generic/unaligned.h:50
Inline: True
Inline callers:
  - lib/zstd/compress/huf_compress.c:HUF_compress1X_usingCTable_internal_default
  - lib/zstd/compress/huf_compress.c:HUF_compress1X_usingCTable_internal_default
  - lib/zstd/compress/huf_compress.c:HUF_compress1X_usingCTable_internal_default
  - lib/zstd/compress/huf_compress.c:HUF_compress1X_usingCTable_internal_bmi2
  - lib/zstd/compress/huf_compress.c:HUF_compress1X_usingCTable_internal_bmi2
  - lib/zstd/compress/huf_compress.c:HUF_compress1X_usingCTable_internal_bmi2
```
```
In lib/zstd/compress/zstd_compress.c (ffffffff81711d6b)
Location: include/asm-generic/unaligned.h:50
Inline: True
Inline callers:
  - lib/zstd/compress/zstd_compress.c:ZSTD_writeFrameHeader
```
```
In lib/zstd/compress/zstd_compress_sequences.c (ffffffff81e97e05)
Location: include/asm-generic/unaligned.h:50
Inline: True
Inline callers:
  - lib/zstd/compress/zstd_compress_sequences.c:ZSTD_encodeSequences_bmi2
  - lib/zstd/compress/zstd_compress_sequences.c:ZSTD_encodeSequences_bmi2
  - lib/zstd/compress/zstd_compress_sequences.c:ZSTD_encodeSequences_bmi2
  - lib/zstd/compress/zstd_compress_sequences.c:ZSTD_encodeSequences_bmi2
  - lib/zstd/compress/zstd_compress_sequences.c:ZSTD_encodeSequences_bmi2
  - lib/zstd/compress/zstd_compress_sequences.c:ZSTD_encodeSequences_bmi2
  - lib/zstd/compress/zstd_compress_sequences.c:ZSTD_encodeSequences_bmi2
  - lib/zstd/compress/zstd_compress_sequences.c:ZSTD_encodeSequences_bmi2
  - lib/zstd/compress/zstd_compress_sequences.c:ZSTD_encodeSequences_bmi2
  - lib/zstd/compress/zstd_compress_sequences.c:ZSTD_encodeSequences_bmi2
  - lib/zstd/compress/zstd_compress_sequences.c:ZSTD_encodeSequences_default
  - lib/zstd/compress/zstd_compress_sequences.c:ZSTD_encodeSequences_default
  - lib/zstd/compress/zstd_compress_sequences.c:ZSTD_encodeSequences_default
  - lib/zstd/compress/zstd_compress_sequences.c:ZSTD_encodeSequences_default
  - lib/zstd/compress/zstd_compress_sequences.c:ZSTD_encodeSequences_default
  - lib/zstd/compress/zstd_compress_sequences.c:ZSTD_encodeSequences_default
  - lib/zstd/compress/zstd_compress_sequences.c:ZSTD_encodeSequences_default
  - lib/zstd/compress/zstd_compress_sequences.c:ZSTD_encodeSequences_default
  - lib/zstd/compress/zstd_compress_sequences.c:ZSTD_encodeSequences_default
  - lib/zstd/compress/zstd_compress_sequences.c:ZSTD_encodeSequences_default
```
```
In drivers/base/regmap/regmap.c (ffffffff819a661e)
Location: include/asm-generic/unaligned.h:50
Inline: True
Inline callers:
  - drivers/base/regmap/regmap.c:regmap_format_64_le
```
```
In net/ipv4/tcp_fastopen.c (ffffffff81d12e6e)
Location: include/asm-generic/unaligned.h:50
Inline: True
Inline callers:
  - net/ipv4/tcp_fastopen.c:tcp_fastopen_get_cipher
  - net/ipv4/tcp_fastopen.c:tcp_fastopen_get_cipher
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
In crypto/crc64_rocksoft_generic.c (ffffffff8171c4e6)
Location: include/asm-generic/unaligned.h:50
Inline: True
Inline callers:
  - crypto/crc64_rocksoft_generic.c:chksum_digest
  - crypto/crc64_rocksoft_generic.c:chksum_finup
  - crypto/crc64_rocksoft_generic.c:chksum_final
```
```
In lib/zstd/compress/fse_compress.c (ffffffff817fd16d)
Location: include/asm-generic/unaligned.h:50
Inline: True
Inline callers:
  - lib/zstd/compress/fse_compress.c:FSE_compress_usingCTable_generic
  - lib/zstd/compress/fse_compress.c:FSE_compress_usingCTable_generic
  - lib/zstd/compress/fse_compress.c:FSE_compress_usingCTable_generic
  - lib/zstd/compress/fse_compress.c:FSE_compress_usingCTable_generic
  - lib/zstd/compress/fse_compress.c:FSE_compress_usingCTable_generic
  - lib/zstd/compress/fse_compress.c:FSE_compress_usingCTable_generic
  - lib/zstd/compress/fse_compress.c:FSE_compress_usingCTable_generic
  - lib/zstd/compress/fse_compress.c:FSE_compress_usingCTable_generic
  - lib/zstd/compress/fse_compress.c:FSE_compress_usingCTable_generic
```
```
In lib/zstd/compress/huf_compress.c (ffffffff817feead)
Location: include/asm-generic/unaligned.h:50
Inline: True
Inline callers:
  - lib/zstd/compress/huf_compress.c:HUF_compress1X_usingCTable_internal_default
  - lib/zstd/compress/huf_compress.c:HUF_compress1X_usingCTable_internal_default
  - lib/zstd/compress/huf_compress.c:HUF_compress1X_usingCTable_internal_default
  - lib/zstd/compress/huf_compress.c:HUF_compress1X_usingCTable_internal_default
  - lib/zstd/compress/huf_compress.c:HUF_compress1X_usingCTable_internal_default
  - lib/zstd/compress/huf_compress.c:HUF_compress1X_usingCTable_internal_default
  - lib/zstd/compress/huf_compress.c:HUF_compress1X_usingCTable_internal_default
  - lib/zstd/compress/huf_compress.c:HUF_compress1X_usingCTable_internal_default
  - lib/zstd/compress/huf_compress.c:HUF_compress1X_usingCTable_internal_default
  - lib/zstd/compress/huf_compress.c:HUF_compress1X_usingCTable_internal_default
  - lib/zstd/compress/huf_compress.c:HUF_compress1X_usingCTable_internal_default
  - lib/zstd/compress/huf_compress.c:HUF_compress1X_usingCTable_internal_default
  - lib/zstd/compress/huf_compress.c:HUF_compress1X_usingCTable_internal_default
  - lib/zstd/compress/huf_compress.c:HUF_compress1X_usingCTable_internal_default
  - lib/zstd/compress/huf_compress.c:HUF_compress1X_usingCTable_internal_default
  - lib/zstd/compress/huf_compress.c:HUF_compress1X_usingCTable_internal_default
  - lib/zstd/compress/huf_compress.c:HUF_compress1X_usingCTable_internal_default
  - lib/zstd/compress/huf_compress.c:HUF_compress1X_usingCTable_internal_default
  - lib/zstd/compress/huf_compress.c:HUF_compress1X_usingCTable_internal_default
  - lib/zstd/compress/huf_compress.c:HUF_compress1X_usingCTable_internal_default
  - lib/zstd/compress/huf_compress.c:HUF_compress1X_usingCTable_internal_default
  - lib/zstd/compress/huf_compress.c:HUF_compress1X_usingCTable_internal_default
  - lib/zstd/compress/huf_compress.c:HUF_compress1X_usingCTable_internal_default
  - lib/zstd/compress/huf_compress.c:HUF_compress1X_usingCTable_internal_default
  - lib/zstd/compress/huf_compress.c:HUF_compress1X_usingCTable_internal_default
  - lib/zstd/compress/huf_compress.c:HUF_compress1X_usingCTable_internal_default
  - lib/zstd/compress/huf_compress.c:HUF_compress1X_usingCTable_internal_default
  - lib/zstd/compress/huf_compress.c:HUF_compress1X_usingCTable_internal_default
  - lib/zstd/compress/huf_compress.c:HUF_compress1X_usingCTable_internal_bmi2
  - lib/zstd/compress/huf_compress.c:HUF_compress1X_usingCTable_internal_bmi2
  - lib/zstd/compress/huf_compress.c:HUF_compress1X_usingCTable_internal_bmi2
  - lib/zstd/compress/huf_compress.c:HUF_compress1X_usingCTable_internal_bmi2
  - lib/zstd/compress/huf_compress.c:HUF_compress1X_usingCTable_internal_bmi2
  - lib/zstd/compress/huf_compress.c:HUF_compress1X_usingCTable_internal_bmi2
  - lib/zstd/compress/huf_compress.c:HUF_compress1X_usingCTable_internal_bmi2
  - lib/zstd/compress/huf_compress.c:HUF_compress1X_usingCTable_internal_bmi2
  - lib/zstd/compress/huf_compress.c:HUF_compress1X_usingCTable_internal_bmi2
  - lib/zstd/compress/huf_compress.c:HUF_compress1X_usingCTable_internal_bmi2
  - lib/zstd/compress/huf_compress.c:HUF_compress1X_usingCTable_internal_bmi2
  - lib/zstd/compress/huf_compress.c:HUF_compress1X_usingCTable_internal_bmi2
  - lib/zstd/compress/huf_compress.c:HUF_compress1X_usingCTable_internal_bmi2
  - lib/zstd/compress/huf_compress.c:HUF_compress1X_usingCTable_internal_bmi2
  - lib/zstd/compress/huf_compress.c:HUF_compress1X_usingCTable_internal_bmi2
  - lib/zstd/compress/huf_compress.c:HUF_compress1X_usingCTable_internal_bmi2
  - lib/zstd/compress/huf_compress.c:HUF_compress1X_usingCTable_internal_bmi2
  - lib/zstd/compress/huf_compress.c:HUF_compress1X_usingCTable_internal_bmi2
  - lib/zstd/compress/huf_compress.c:HUF_compress1X_usingCTable_internal_bmi2
  - lib/zstd/compress/huf_compress.c:HUF_compress1X_usingCTable_internal_bmi2
  - lib/zstd/compress/huf_compress.c:HUF_compress1X_usingCTable_internal_bmi2
  - lib/zstd/compress/huf_compress.c:HUF_compress1X_usingCTable_internal_bmi2
  - lib/zstd/compress/huf_compress.c:HUF_compress1X_usingCTable_internal_bmi2
  - lib/zstd/compress/huf_compress.c:HUF_compress1X_usingCTable_internal_bmi2
  - lib/zstd/compress/huf_compress.c:HUF_compress1X_usingCTable_internal_bmi2
  - lib/zstd/compress/huf_compress.c:HUF_compress1X_usingCTable_internal_bmi2
  - lib/zstd/compress/huf_compress.c:HUF_compress1X_usingCTable_internal_bmi2
  - lib/zstd/compress/huf_compress.c:HUF_compress1X_usingCTable_internal_bmi2
  - lib/zstd/compress/huf_compress.c:HUF_closeCStream
```
```
In lib/zstd/compress/zstd_compress.c (ffffffff8180499b)
Location: include/asm-generic/unaligned.h:50
Inline: True
Inline callers:
  - lib/zstd/compress/zstd_compress.c:ZSTD_writeFrameHeader
```
```
In lib/zstd/compress/zstd_compress_sequences.c (ffffffff8207e12d)
Location: include/asm-generic/unaligned.h:50
Inline: True
Inline callers:
  - lib/zstd/compress/zstd_compress_sequences.c:ZSTD_encodeSequences_bmi2
  - lib/zstd/compress/zstd_compress_sequences.c:ZSTD_encodeSequences_bmi2
  - lib/zstd/compress/zstd_compress_sequences.c:ZSTD_encodeSequences_bmi2
  - lib/zstd/compress/zstd_compress_sequences.c:ZSTD_encodeSequences_bmi2
  - lib/zstd/compress/zstd_compress_sequences.c:ZSTD_encodeSequences_bmi2
  - lib/zstd/compress/zstd_compress_sequences.c:ZSTD_encodeSequences_bmi2
  - lib/zstd/compress/zstd_compress_sequences.c:ZSTD_encodeSequences_bmi2
  - lib/zstd/compress/zstd_compress_sequences.c:ZSTD_encodeSequences_bmi2
  - lib/zstd/compress/zstd_compress_sequences.c:ZSTD_encodeSequences_bmi2
  - lib/zstd/compress/zstd_compress_sequences.c:ZSTD_encodeSequences_bmi2
  - lib/zstd/compress/zstd_compress_sequences.c:ZSTD_encodeSequences_default
  - lib/zstd/compress/zstd_compress_sequences.c:ZSTD_encodeSequences_default
  - lib/zstd/compress/zstd_compress_sequences.c:ZSTD_encodeSequences_default
  - lib/zstd/compress/zstd_compress_sequences.c:ZSTD_encodeSequences_default
  - lib/zstd/compress/zstd_compress_sequences.c:ZSTD_encodeSequences_default
  - lib/zstd/compress/zstd_compress_sequences.c:ZSTD_encodeSequences_default
  - lib/zstd/compress/zstd_compress_sequences.c:ZSTD_encodeSequences_default
  - lib/zstd/compress/zstd_compress_sequences.c:ZSTD_encodeSequences_default
  - lib/zstd/compress/zstd_compress_sequences.c:ZSTD_encodeSequences_default
  - lib/zstd/compress/zstd_compress_sequences.c:ZSTD_encodeSequences_default
```
```
In drivers/base/regmap/regmap.c (ffffffff81b18d4e)
Location: include/asm-generic/unaligned.h:50
Inline: True
Inline callers:
  - drivers/base/regmap/regmap.c:regmap_format_64_le
```
```
In net/ipv4/tcp_fastopen.c (ffffffff81ed8dbe)
Location: include/asm-generic/unaligned.h:50
Inline: True
Inline callers:
  - net/ipv4/tcp_fastopen.c:tcp_fastopen_get_cipher
  - net/ipv4/tcp_fastopen.c:tcp_fastopen_get_cipher
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
In crypto/sha3_generic.c (ffffffff81750402)
Location: include/asm-generic/unaligned.h:50
Inline: True
Inline callers:
  - crypto/sha3_generic.c:crypto_sha3_final
```
```
In crypto/crc64_rocksoft_generic.c (ffffffff81757c86)
Location: include/asm-generic/unaligned.h:50
Inline: True
Inline callers:
  - crypto/crc64_rocksoft_generic.c:chksum_digest
  - crypto/crc64_rocksoft_generic.c:chksum_finup
  - crypto/crc64_rocksoft_generic.c:chksum_final
```
```
In lib/zstd/compress/fse_compress.c (ffffffff8183da3e)
Location: include/asm-generic/unaligned.h:50
Inline: True
Inline callers:
  - lib/zstd/compress/fse_compress.c:FSE_compress_usingCTable_generic
  - lib/zstd/compress/fse_compress.c:FSE_compress_usingCTable_generic
  - lib/zstd/compress/fse_compress.c:FSE_compress_usingCTable_generic
  - lib/zstd/compress/fse_compress.c:FSE_compress_usingCTable_generic
  - lib/zstd/compress/fse_compress.c:FSE_compress_usingCTable_generic
  - lib/zstd/compress/fse_compress.c:FSE_compress_usingCTable_generic
  - lib/zstd/compress/fse_compress.c:FSE_compress_usingCTable_generic
  - lib/zstd/compress/fse_compress.c:FSE_compress_usingCTable_generic
  - lib/zstd/compress/fse_compress.c:FSE_compress_usingCTable_generic
```
```
In lib/zstd/compress/huf_compress.c (ffffffff8183f79d)
Location: include/asm-generic/unaligned.h:50
Inline: True
Inline callers:
  - lib/zstd/compress/huf_compress.c:HUF_compress1X_usingCTable_internal_default
  - lib/zstd/compress/huf_compress.c:HUF_compress1X_usingCTable_internal_default
  - lib/zstd/compress/huf_compress.c:HUF_compress1X_usingCTable_internal_default
  - lib/zstd/compress/huf_compress.c:HUF_compress1X_usingCTable_internal_default
  - lib/zstd/compress/huf_compress.c:HUF_compress1X_usingCTable_internal_default
  - lib/zstd/compress/huf_compress.c:HUF_compress1X_usingCTable_internal_default
  - lib/zstd/compress/huf_compress.c:HUF_compress1X_usingCTable_internal_default
  - lib/zstd/compress/huf_compress.c:HUF_compress1X_usingCTable_internal_default
  - lib/zstd/compress/huf_compress.c:HUF_compress1X_usingCTable_internal_default
  - lib/zstd/compress/huf_compress.c:HUF_compress1X_usingCTable_internal_default
  - lib/zstd/compress/huf_compress.c:HUF_compress1X_usingCTable_internal_default
  - lib/zstd/compress/huf_compress.c:HUF_compress1X_usingCTable_internal_default
  - lib/zstd/compress/huf_compress.c:HUF_compress1X_usingCTable_internal_default
  - lib/zstd/compress/huf_compress.c:HUF_compress1X_usingCTable_internal_default
  - lib/zstd/compress/huf_compress.c:HUF_compress1X_usingCTable_internal_default
  - lib/zstd/compress/huf_compress.c:HUF_compress1X_usingCTable_internal_default
  - lib/zstd/compress/huf_compress.c:HUF_compress1X_usingCTable_internal_default
  - lib/zstd/compress/huf_compress.c:HUF_compress1X_usingCTable_internal_default
  - lib/zstd/compress/huf_compress.c:HUF_compress1X_usingCTable_internal_default
  - lib/zstd/compress/huf_compress.c:HUF_compress1X_usingCTable_internal_default
  - lib/zstd/compress/huf_compress.c:HUF_compress1X_usingCTable_internal_default
  - lib/zstd/compress/huf_compress.c:HUF_compress1X_usingCTable_internal_default
  - lib/zstd/compress/huf_compress.c:HUF_compress1X_usingCTable_internal_default
  - lib/zstd/compress/huf_compress.c:HUF_compress1X_usingCTable_internal_default
  - lib/zstd/compress/huf_compress.c:HUF_compress1X_usingCTable_internal_default
  - lib/zstd/compress/huf_compress.c:HUF_compress1X_usingCTable_internal_default
  - lib/zstd/compress/huf_compress.c:HUF_compress1X_usingCTable_internal_default
  - lib/zstd/compress/huf_compress.c:HUF_compress1X_usingCTable_internal_default
  - lib/zstd/compress/huf_compress.c:HUF_compress1X_usingCTable_internal_bmi2
  - lib/zstd/compress/huf_compress.c:HUF_compress1X_usingCTable_internal_bmi2
  - lib/zstd/compress/huf_compress.c:HUF_compress1X_usingCTable_internal_bmi2
  - lib/zstd/compress/huf_compress.c:HUF_compress1X_usingCTable_internal_bmi2
  - lib/zstd/compress/huf_compress.c:HUF_compress1X_usingCTable_internal_bmi2
  - lib/zstd/compress/huf_compress.c:HUF_compress1X_usingCTable_internal_bmi2
  - lib/zstd/compress/huf_compress.c:HUF_compress1X_usingCTable_internal_bmi2
  - lib/zstd/compress/huf_compress.c:HUF_compress1X_usingCTable_internal_bmi2
  - lib/zstd/compress/huf_compress.c:HUF_compress1X_usingCTable_internal_bmi2
  - lib/zstd/compress/huf_compress.c:HUF_compress1X_usingCTable_internal_bmi2
  - lib/zstd/compress/huf_compress.c:HUF_compress1X_usingCTable_internal_bmi2
  - lib/zstd/compress/huf_compress.c:HUF_compress1X_usingCTable_internal_bmi2
  - lib/zstd/compress/huf_compress.c:HUF_compress1X_usingCTable_internal_bmi2
  - lib/zstd/compress/huf_compress.c:HUF_compress1X_usingCTable_internal_bmi2
  - lib/zstd/compress/huf_compress.c:HUF_compress1X_usingCTable_internal_bmi2
  - lib/zstd/compress/huf_compress.c:HUF_compress1X_usingCTable_internal_bmi2
  - lib/zstd/compress/huf_compress.c:HUF_compress1X_usingCTable_internal_bmi2
  - lib/zstd/compress/huf_compress.c:HUF_compress1X_usingCTable_internal_bmi2
  - lib/zstd/compress/huf_compress.c:HUF_compress1X_usingCTable_internal_bmi2
  - lib/zstd/compress/huf_compress.c:HUF_compress1X_usingCTable_internal_bmi2
  - lib/zstd/compress/huf_compress.c:HUF_compress1X_usingCTable_internal_bmi2
  - lib/zstd/compress/huf_compress.c:HUF_compress1X_usingCTable_internal_bmi2
  - lib/zstd/compress/huf_compress.c:HUF_compress1X_usingCTable_internal_bmi2
  - lib/zstd/compress/huf_compress.c:HUF_compress1X_usingCTable_internal_bmi2
  - lib/zstd/compress/huf_compress.c:HUF_compress1X_usingCTable_internal_bmi2
  - lib/zstd/compress/huf_compress.c:HUF_compress1X_usingCTable_internal_bmi2
  - lib/zstd/compress/huf_compress.c:HUF_compress1X_usingCTable_internal_bmi2
  - lib/zstd/compress/huf_compress.c:HUF_compress1X_usingCTable_internal_bmi2
  - lib/zstd/compress/huf_compress.c:HUF_closeCStream
```
```
In lib/zstd/compress/zstd_compress.c (ffffffff81845396)
Location: include/asm-generic/unaligned.h:50
Inline: True
Inline callers:
  - lib/zstd/compress/zstd_compress.c:ZSTD_writeFrameHeader
```
```
In lib/zstd/compress/zstd_compress_sequences.c (ffffffff820fe69b)
Location: include/asm-generic/unaligned.h:50
Inline: True
Inline callers:
  - lib/zstd/compress/zstd_compress_sequences.c:ZSTD_encodeSequences_bmi2
  - lib/zstd/compress/zstd_compress_sequences.c:ZSTD_encodeSequences_bmi2
  - lib/zstd/compress/zstd_compress_sequences.c:ZSTD_encodeSequences_bmi2
  - lib/zstd/compress/zstd_compress_sequences.c:ZSTD_encodeSequences_bmi2
  - lib/zstd/compress/zstd_compress_sequences.c:ZSTD_encodeSequences_bmi2
  - lib/zstd/compress/zstd_compress_sequences.c:ZSTD_encodeSequences_bmi2
  - lib/zstd/compress/zstd_compress_sequences.c:ZSTD_encodeSequences_bmi2
  - lib/zstd/compress/zstd_compress_sequences.c:ZSTD_encodeSequences_bmi2
  - lib/zstd/compress/zstd_compress_sequences.c:ZSTD_encodeSequences_bmi2
  - lib/zstd/compress/zstd_compress_sequences.c:ZSTD_encodeSequences_bmi2
  - lib/zstd/compress/zstd_compress_sequences.c:ZSTD_encodeSequences_default
  - lib/zstd/compress/zstd_compress_sequences.c:ZSTD_encodeSequences_default
  - lib/zstd/compress/zstd_compress_sequences.c:ZSTD_encodeSequences_default
  - lib/zstd/compress/zstd_compress_sequences.c:ZSTD_encodeSequences_default
  - lib/zstd/compress/zstd_compress_sequences.c:ZSTD_encodeSequences_default
  - lib/zstd/compress/zstd_compress_sequences.c:ZSTD_encodeSequences_default
  - lib/zstd/compress/zstd_compress_sequences.c:ZSTD_encodeSequences_default
  - lib/zstd/compress/zstd_compress_sequences.c:ZSTD_encodeSequences_default
  - lib/zstd/compress/zstd_compress_sequences.c:ZSTD_encodeSequences_default
  - lib/zstd/compress/zstd_compress_sequences.c:ZSTD_encodeSequences_default
```
```
In drivers/base/regmap/regmap.c (ffffffff81b67b3e)
Location: include/asm-generic/unaligned.h:50
Inline: True
Inline callers:
  - drivers/base/regmap/regmap.c:regmap_format_64_le
```
```
In net/ipv4/tcp_fastopen.c (ffffffff81f37ece)
Location: include/asm-generic/unaligned.h:50
Inline: True
Inline callers:
  - net/ipv4/tcp_fastopen.c:tcp_fastopen_get_cipher
  - net/ipv4/tcp_fastopen.c:tcp_fastopen_get_cipher
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
In crypto/sha3_generic.c (ffffffff81792052)
Location: include/asm-generic/unaligned.h:50
Inline: True
Inline callers:
  - crypto/sha3_generic.c:crypto_sha3_final
```
```
In crypto/crc64_rocksoft_generic.c (ffffffff81799b86)
Location: include/asm-generic/unaligned.h:50
Inline: True
Inline callers:
  - crypto/crc64_rocksoft_generic.c:chksum_digest
  - crypto/crc64_rocksoft_generic.c:chksum_finup
  - crypto/crc64_rocksoft_generic.c:chksum_final
```
```
In lib/zstd/compress/fse_compress.c (ffffffff8188f5fe)
Location: include/asm-generic/unaligned.h:50
Inline: True
Inline callers:
  - lib/zstd/compress/fse_compress.c:FSE_compress_usingCTable_generic
  - lib/zstd/compress/fse_compress.c:FSE_compress_usingCTable_generic
  - lib/zstd/compress/fse_compress.c:FSE_compress_usingCTable_generic
  - lib/zstd/compress/fse_compress.c:FSE_compress_usingCTable_generic
  - lib/zstd/compress/fse_compress.c:FSE_compress_usingCTable_generic
  - lib/zstd/compress/fse_compress.c:FSE_compress_usingCTable_generic
  - lib/zstd/compress/fse_compress.c:FSE_compress_usingCTable_generic
  - lib/zstd/compress/fse_compress.c:FSE_compress_usingCTable_generic
  - lib/zstd/compress/fse_compress.c:FSE_compress_usingCTable_generic
```
```
In lib/zstd/compress/huf_compress.c (ffffffff8189135d)
Location: include/asm-generic/unaligned.h:50
Inline: True
Inline callers:
  - lib/zstd/compress/huf_compress.c:HUF_compress1X_usingCTable_internal_default
  - lib/zstd/compress/huf_compress.c:HUF_compress1X_usingCTable_internal_default
  - lib/zstd/compress/huf_compress.c:HUF_compress1X_usingCTable_internal_default
  - lib/zstd/compress/huf_compress.c:HUF_compress1X_usingCTable_internal_default
  - lib/zstd/compress/huf_compress.c:HUF_compress1X_usingCTable_internal_default
  - lib/zstd/compress/huf_compress.c:HUF_compress1X_usingCTable_internal_default
  - lib/zstd/compress/huf_compress.c:HUF_compress1X_usingCTable_internal_default
  - lib/zstd/compress/huf_compress.c:HUF_compress1X_usingCTable_internal_default
  - lib/zstd/compress/huf_compress.c:HUF_compress1X_usingCTable_internal_default
  - lib/zstd/compress/huf_compress.c:HUF_compress1X_usingCTable_internal_default
  - lib/zstd/compress/huf_compress.c:HUF_compress1X_usingCTable_internal_default
  - lib/zstd/compress/huf_compress.c:HUF_compress1X_usingCTable_internal_default
  - lib/zstd/compress/huf_compress.c:HUF_compress1X_usingCTable_internal_default
  - lib/zstd/compress/huf_compress.c:HUF_compress1X_usingCTable_internal_default
  - lib/zstd/compress/huf_compress.c:HUF_compress1X_usingCTable_internal_default
  - lib/zstd/compress/huf_compress.c:HUF_compress1X_usingCTable_internal_default
  - lib/zstd/compress/huf_compress.c:HUF_compress1X_usingCTable_internal_default
  - lib/zstd/compress/huf_compress.c:HUF_compress1X_usingCTable_internal_default
  - lib/zstd/compress/huf_compress.c:HUF_compress1X_usingCTable_internal_default
  - lib/zstd/compress/huf_compress.c:HUF_compress1X_usingCTable_internal_default
  - lib/zstd/compress/huf_compress.c:HUF_compress1X_usingCTable_internal_default
  - lib/zstd/compress/huf_compress.c:HUF_compress1X_usingCTable_internal_default
  - lib/zstd/compress/huf_compress.c:HUF_compress1X_usingCTable_internal_default
  - lib/zstd/compress/huf_compress.c:HUF_compress1X_usingCTable_internal_default
  - lib/zstd/compress/huf_compress.c:HUF_compress1X_usingCTable_internal_default
  - lib/zstd/compress/huf_compress.c:HUF_compress1X_usingCTable_internal_default
  - lib/zstd/compress/huf_compress.c:HUF_compress1X_usingCTable_internal_default
  - lib/zstd/compress/huf_compress.c:HUF_compress1X_usingCTable_internal_default
  - lib/zstd/compress/huf_compress.c:HUF_compress1X_usingCTable_internal_bmi2
  - lib/zstd/compress/huf_compress.c:HUF_compress1X_usingCTable_internal_bmi2
  - lib/zstd/compress/huf_compress.c:HUF_compress1X_usingCTable_internal_bmi2
  - lib/zstd/compress/huf_compress.c:HUF_compress1X_usingCTable_internal_bmi2
  - lib/zstd/compress/huf_compress.c:HUF_compress1X_usingCTable_internal_bmi2
  - lib/zstd/compress/huf_compress.c:HUF_compress1X_usingCTable_internal_bmi2
  - lib/zstd/compress/huf_compress.c:HUF_compress1X_usingCTable_internal_bmi2
  - lib/zstd/compress/huf_compress.c:HUF_compress1X_usingCTable_internal_bmi2
  - lib/zstd/compress/huf_compress.c:HUF_compress1X_usingCTable_internal_bmi2
  - lib/zstd/compress/huf_compress.c:HUF_compress1X_usingCTable_internal_bmi2
  - lib/zstd/compress/huf_compress.c:HUF_compress1X_usingCTable_internal_bmi2
  - lib/zstd/compress/huf_compress.c:HUF_compress1X_usingCTable_internal_bmi2
  - lib/zstd/compress/huf_compress.c:HUF_compress1X_usingCTable_internal_bmi2
  - lib/zstd/compress/huf_compress.c:HUF_compress1X_usingCTable_internal_bmi2
  - lib/zstd/compress/huf_compress.c:HUF_compress1X_usingCTable_internal_bmi2
  - lib/zstd/compress/huf_compress.c:HUF_compress1X_usingCTable_internal_bmi2
  - lib/zstd/compress/huf_compress.c:HUF_compress1X_usingCTable_internal_bmi2
  - lib/zstd/compress/huf_compress.c:HUF_compress1X_usingCTable_internal_bmi2
  - lib/zstd/compress/huf_compress.c:HUF_compress1X_usingCTable_internal_bmi2
  - lib/zstd/compress/huf_compress.c:HUF_compress1X_usingCTable_internal_bmi2
  - lib/zstd/compress/huf_compress.c:HUF_compress1X_usingCTable_internal_bmi2
  - lib/zstd/compress/huf_compress.c:HUF_compress1X_usingCTable_internal_bmi2
  - lib/zstd/compress/huf_compress.c:HUF_compress1X_usingCTable_internal_bmi2
  - lib/zstd/compress/huf_compress.c:HUF_compress1X_usingCTable_internal_bmi2
  - lib/zstd/compress/huf_compress.c:HUF_compress1X_usingCTable_internal_bmi2
  - lib/zstd/compress/huf_compress.c:HUF_compress1X_usingCTable_internal_bmi2
  - lib/zstd/compress/huf_compress.c:HUF_compress1X_usingCTable_internal_bmi2
  - lib/zstd/compress/huf_compress.c:HUF_compress1X_usingCTable_internal_bmi2
  - lib/zstd/compress/huf_compress.c:HUF_closeCStream
```
```
In lib/zstd/compress/zstd_compress.c (ffffffff81896f56)
Location: include/asm-generic/unaligned.h:50
Inline: True
Inline callers:
  - lib/zstd/compress/zstd_compress.c:ZSTD_writeFrameHeader
```
```
In lib/zstd/compress/zstd_compress_sequences.c (ffffffff821dc808)
Location: include/asm-generic/unaligned.h:50
Inline: True
Inline callers:
  - lib/zstd/compress/zstd_compress_sequences.c:ZSTD_encodeSequences_bmi2
  - lib/zstd/compress/zstd_compress_sequences.c:ZSTD_encodeSequences_bmi2
  - lib/zstd/compress/zstd_compress_sequences.c:ZSTD_encodeSequences_bmi2
  - lib/zstd/compress/zstd_compress_sequences.c:ZSTD_encodeSequences_bmi2
  - lib/zstd/compress/zstd_compress_sequences.c:ZSTD_encodeSequences_bmi2
  - lib/zstd/compress/zstd_compress_sequences.c:ZSTD_encodeSequences_bmi2
  - lib/zstd/compress/zstd_compress_sequences.c:ZSTD_encodeSequences_bmi2
  - lib/zstd/compress/zstd_compress_sequences.c:ZSTD_encodeSequences_bmi2
  - lib/zstd/compress/zstd_compress_sequences.c:ZSTD_encodeSequences_bmi2
  - lib/zstd/compress/zstd_compress_sequences.c:ZSTD_encodeSequences_bmi2
  - lib/zstd/compress/zstd_compress_sequences.c:ZSTD_encodeSequences_default
  - lib/zstd/compress/zstd_compress_sequences.c:ZSTD_encodeSequences_default
  - lib/zstd/compress/zstd_compress_sequences.c:ZSTD_encodeSequences_default
  - lib/zstd/compress/zstd_compress_sequences.c:ZSTD_encodeSequences_default
  - lib/zstd/compress/zstd_compress_sequences.c:ZSTD_encodeSequences_default
  - lib/zstd/compress/zstd_compress_sequences.c:ZSTD_encodeSequences_default
  - lib/zstd/compress/zstd_compress_sequences.c:ZSTD_encodeSequences_default
  - lib/zstd/compress/zstd_compress_sequences.c:ZSTD_encodeSequences_default
  - lib/zstd/compress/zstd_compress_sequences.c:ZSTD_encodeSequences_default
  - lib/zstd/compress/zstd_compress_sequences.c:ZSTD_encodeSequences_default
```
```
In net/ipv4/tcp_fastopen.c (ffffffff81ffdf8e)
Location: include/asm-generic/unaligned.h:50
Inline: True
Inline callers:
  - net/ipv4/tcp_fastopen.c:tcp_fastopen_get_cipher
  - net/ipv4/tcp_fastopen.c:tcp_fastopen_get_cipher
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
In lib/lzo/lzo1x_compress.c (ffff80001064b15c)
Location: include/linux/unaligned/access_ok.h:48
Inline: True
Inline callers:
  - lib/lzo/lzo1x_compress.c:lzogeneric1x_1_compress
  - lib/lzo/lzo1x_compress.c:lzogeneric1x_1_compress
  - lib/lzo/lzo1x_compress.c:lzo1x_1_do_compress
  - lib/lzo/lzo1x_compress.c:lzo1x_1_do_compress
  - lib/lzo/lzo1x_compress.c:lzo1x_1_do_compress
  - lib/lzo/lzo1x_compress.c:lzo1x_1_do_compress
```
```
In lib/lzo/lzo1x_decompress_safe.c (ffff80001064b2cc)
Location: include/linux/unaligned/access_ok.h:48
Inline: True
Inline callers:
  - lib/lzo/lzo1x_decompress_safe.c:lzo1x_decompress_safe
  - lib/lzo/lzo1x_decompress_safe.c:lzo1x_decompress_safe
  - lib/lzo/lzo1x_decompress_safe.c:lzo1x_decompress_safe
  - lib/lzo/lzo1x_decompress_safe.c:lzo1x_decompress_safe
```
```
In lib/lz4/lz4_decompress.c (ffff80001064dbf8)
Location: include/linux/unaligned/access_ok.h:48
Inline: True
Inline callers:
  - lib/lz4/lz4_decompress.c:LZ4_decompress_fast_continue
  - lib/lz4/lz4_decompress.c:LZ4_decompress_fast_continue
  - lib/lz4/lz4_decompress.c:LZ4_decompress_fast_continue
  - lib/lz4/lz4_decompress.c:LZ4_decompress_fast_continue
  - lib/lz4/lz4_decompress.c:LZ4_decompress_fast_continue
  - lib/lz4/lz4_decompress.c:LZ4_decompress_safe_continue
  - lib/lz4/lz4_decompress.c:LZ4_decompress_safe_continue
  - lib/lz4/lz4_decompress.c:LZ4_decompress_safe_continue
  - lib/lz4/lz4_decompress.c:LZ4_decompress_safe_continue
  - lib/lz4/lz4_decompress.c:LZ4_decompress_safe_continue
  - lib/lz4/lz4_decompress.c:LZ4_decompress_fast_extDict
  - lib/lz4/lz4_decompress.c:LZ4_decompress_fast_extDict
  - lib/lz4/lz4_decompress.c:LZ4_decompress_fast_extDict
  - lib/lz4/lz4_decompress.c:LZ4_decompress_fast_extDict
  - lib/lz4/lz4_decompress.c:LZ4_decompress_fast_extDict
  - lib/lz4/lz4_decompress.c:LZ4_decompress_safe_forceExtDict
  - lib/lz4/lz4_decompress.c:LZ4_decompress_safe_forceExtDict
  - lib/lz4/lz4_decompress.c:LZ4_decompress_safe_forceExtDict
  - lib/lz4/lz4_decompress.c:LZ4_decompress_safe_forceExtDict
  - lib/lz4/lz4_decompress.c:LZ4_decompress_safe_forceExtDict
  - lib/lz4/lz4_decompress.c:LZ4_decompress_safe_withSmallPrefix
  - lib/lz4/lz4_decompress.c:LZ4_decompress_safe_withSmallPrefix
  - lib/lz4/lz4_decompress.c:LZ4_decompress_safe_withSmallPrefix
  - lib/lz4/lz4_decompress.c:LZ4_decompress_safe_withSmallPrefix
  - lib/lz4/lz4_decompress.c:LZ4_decompress_safe_withSmallPrefix
  - lib/lz4/lz4_decompress.c:LZ4_decompress_safe_withPrefix64k
  - lib/lz4/lz4_decompress.c:LZ4_decompress_safe_withPrefix64k
  - lib/lz4/lz4_decompress.c:LZ4_decompress_safe_withPrefix64k
  - lib/lz4/lz4_decompress.c:LZ4_decompress_safe_withPrefix64k
  - lib/lz4/lz4_decompress.c:LZ4_decompress_safe_withPrefix64k
  - lib/lz4/lz4_decompress.c:LZ4_decompress_fast
  - lib/lz4/lz4_decompress.c:LZ4_decompress_fast
  - lib/lz4/lz4_decompress.c:LZ4_decompress_fast
  - lib/lz4/lz4_decompress.c:LZ4_decompress_fast
  - lib/lz4/lz4_decompress.c:LZ4_decompress_fast
  - lib/lz4/lz4_decompress.c:LZ4_decompress_safe_partial
  - lib/lz4/lz4_decompress.c:LZ4_decompress_safe_partial
  - lib/lz4/lz4_decompress.c:LZ4_decompress_safe_partial
  - lib/lz4/lz4_decompress.c:LZ4_decompress_safe_partial
  - lib/lz4/lz4_decompress.c:LZ4_decompress_safe
  - lib/lz4/lz4_decompress.c:LZ4_decompress_safe
  - lib/lz4/lz4_decompress.c:LZ4_decompress_safe
  - lib/lz4/lz4_decompress.c:LZ4_decompress_safe
  - lib/lz4/lz4_decompress.c:LZ4_decompress_safe
```
```
In drivers/usb/core/hcd.c (ffff800010a1ba80)
Location: include/linux/unaligned/access_ok.h:48
Inline: True
```
```
In net/ipv6/addrconf.c (ffff800010d024ec)
Location: include/linux/unaligned/access_ok.h:48
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:inet6_fill_ifla6_attrs
  - net/ipv6/addrconf.c:inet6_fill_ifla6_attrs
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv6/addrconf.c (c0e07850)
Location: include/linux/unaligned/le_struct.h:32
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:inet6_fill_ifla6_attrs
  - net/ipv6/addrconf.c:inet6_fill_ifla6_attrs
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
In lib/lz4/lz4_decompress.c (c0000000007fbf84)
Location: include/linux/unaligned/access_ok.h:48
Inline: True
Inline callers:
  - lib/lz4/lz4_decompress.c:LZ4_decompress_fast_continue
  - lib/lz4/lz4_decompress.c:LZ4_decompress_fast_continue
  - lib/lz4/lz4_decompress.c:LZ4_decompress_fast_continue
  - lib/lz4/lz4_decompress.c:LZ4_decompress_fast_continue
  - lib/lz4/lz4_decompress.c:LZ4_decompress_fast_continue
  - lib/lz4/lz4_decompress.c:LZ4_decompress_safe_continue
  - lib/lz4/lz4_decompress.c:LZ4_decompress_safe_continue
  - lib/lz4/lz4_decompress.c:LZ4_decompress_safe_continue
  - lib/lz4/lz4_decompress.c:LZ4_decompress_safe_continue
  - lib/lz4/lz4_decompress.c:LZ4_decompress_safe_continue
  - lib/lz4/lz4_decompress.c:LZ4_decompress_fast_extDict
  - lib/lz4/lz4_decompress.c:LZ4_decompress_fast_extDict
  - lib/lz4/lz4_decompress.c:LZ4_decompress_fast_extDict
  - lib/lz4/lz4_decompress.c:LZ4_decompress_fast_extDict
  - lib/lz4/lz4_decompress.c:LZ4_decompress_fast_extDict
  - lib/lz4/lz4_decompress.c:LZ4_decompress_safe_forceExtDict
  - lib/lz4/lz4_decompress.c:LZ4_decompress_safe_forceExtDict
  - lib/lz4/lz4_decompress.c:LZ4_decompress_safe_forceExtDict
  - lib/lz4/lz4_decompress.c:LZ4_decompress_safe_forceExtDict
  - lib/lz4/lz4_decompress.c:LZ4_decompress_safe_forceExtDict
  - lib/lz4/lz4_decompress.c:LZ4_decompress_safe_withSmallPrefix
  - lib/lz4/lz4_decompress.c:LZ4_decompress_safe_withSmallPrefix
  - lib/lz4/lz4_decompress.c:LZ4_decompress_safe_withSmallPrefix
  - lib/lz4/lz4_decompress.c:LZ4_decompress_safe_withSmallPrefix
  - lib/lz4/lz4_decompress.c:LZ4_decompress_safe_withSmallPrefix
  - lib/lz4/lz4_decompress.c:LZ4_decompress_safe_withPrefix64k
  - lib/lz4/lz4_decompress.c:LZ4_decompress_safe_withPrefix64k
  - lib/lz4/lz4_decompress.c:LZ4_decompress_safe_withPrefix64k
  - lib/lz4/lz4_decompress.c:LZ4_decompress_safe_withPrefix64k
  - lib/lz4/lz4_decompress.c:LZ4_decompress_safe_withPrefix64k
  - lib/lz4/lz4_decompress.c:LZ4_decompress_fast
  - lib/lz4/lz4_decompress.c:LZ4_decompress_fast
  - lib/lz4/lz4_decompress.c:LZ4_decompress_fast
  - lib/lz4/lz4_decompress.c:LZ4_decompress_fast
  - lib/lz4/lz4_decompress.c:LZ4_decompress_fast
  - lib/lz4/lz4_decompress.c:LZ4_decompress_safe_partial
  - lib/lz4/lz4_decompress.c:LZ4_decompress_safe_partial
  - lib/lz4/lz4_decompress.c:LZ4_decompress_safe_partial
  - lib/lz4/lz4_decompress.c:LZ4_decompress_safe_partial
  - lib/lz4/lz4_decompress.c:LZ4_decompress_safe
  - lib/lz4/lz4_decompress.c:LZ4_decompress_safe
  - lib/lz4/lz4_decompress.c:LZ4_decompress_safe
  - lib/lz4/lz4_decompress.c:LZ4_decompress_safe
  - lib/lz4/lz4_decompress.c:LZ4_decompress_safe
```
```
In drivers/usb/core/hcd.c (c000000000ad4f20)
Location: include/linux/unaligned/access_ok.h:48
Inline: True
Inline callers:
  - drivers/usb/core/hcd.c:hcd_alloc_coherent
```
```
In net/ipv6/addrconf.c (c000000000e28448)
Location: include/linux/unaligned/access_ok.h:48
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:inet6_fill_ifla6_attrs
  - net/ipv6/addrconf.c:inet6_fill_ifla6_attrs
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
In lib/lz4/lz4_decompress.c (ffffffe00047a2a8)
Location: include/linux/unaligned/le_struct.h:32
Inline: True
Inline callers:
  - lib/lz4/lz4_decompress.c:LZ4_decompress_fast_continue
  - lib/lz4/lz4_decompress.c:LZ4_decompress_fast_continue
  - lib/lz4/lz4_decompress.c:LZ4_decompress_fast_continue
  - lib/lz4/lz4_decompress.c:LZ4_decompress_fast_continue
  - lib/lz4/lz4_decompress.c:LZ4_decompress_fast_continue
  - lib/lz4/lz4_decompress.c:LZ4_decompress_safe_continue
  - lib/lz4/lz4_decompress.c:LZ4_decompress_safe_continue
  - lib/lz4/lz4_decompress.c:LZ4_decompress_safe_continue
  - lib/lz4/lz4_decompress.c:LZ4_decompress_safe_continue
  - lib/lz4/lz4_decompress.c:LZ4_decompress_safe_continue
  - lib/lz4/lz4_decompress.c:LZ4_decompress_fast_extDict
  - lib/lz4/lz4_decompress.c:LZ4_decompress_fast_extDict
  - lib/lz4/lz4_decompress.c:LZ4_decompress_fast_extDict
  - lib/lz4/lz4_decompress.c:LZ4_decompress_fast_extDict
  - lib/lz4/lz4_decompress.c:LZ4_decompress_fast_extDict
  - lib/lz4/lz4_decompress.c:LZ4_decompress_safe_forceExtDict
  - lib/lz4/lz4_decompress.c:LZ4_decompress_safe_forceExtDict
  - lib/lz4/lz4_decompress.c:LZ4_decompress_safe_forceExtDict
  - lib/lz4/lz4_decompress.c:LZ4_decompress_safe_forceExtDict
  - lib/lz4/lz4_decompress.c:LZ4_decompress_safe_forceExtDict
  - lib/lz4/lz4_decompress.c:LZ4_decompress_safe_withSmallPrefix
  - lib/lz4/lz4_decompress.c:LZ4_decompress_safe_withSmallPrefix
  - lib/lz4/lz4_decompress.c:LZ4_decompress_safe_withSmallPrefix
  - lib/lz4/lz4_decompress.c:LZ4_decompress_safe_withSmallPrefix
  - lib/lz4/lz4_decompress.c:LZ4_decompress_safe_withSmallPrefix
  - lib/lz4/lz4_decompress.c:LZ4_decompress_safe_withPrefix64k
  - lib/lz4/lz4_decompress.c:LZ4_decompress_safe_withPrefix64k
  - lib/lz4/lz4_decompress.c:LZ4_decompress_safe_withPrefix64k
  - lib/lz4/lz4_decompress.c:LZ4_decompress_safe_withPrefix64k
  - lib/lz4/lz4_decompress.c:LZ4_decompress_safe_withPrefix64k
  - lib/lz4/lz4_decompress.c:LZ4_decompress_fast
  - lib/lz4/lz4_decompress.c:LZ4_decompress_fast
  - lib/lz4/lz4_decompress.c:LZ4_decompress_fast
  - lib/lz4/lz4_decompress.c:LZ4_decompress_fast
  - lib/lz4/lz4_decompress.c:LZ4_decompress_fast
  - lib/lz4/lz4_decompress.c:LZ4_decompress_safe_partial
  - lib/lz4/lz4_decompress.c:LZ4_decompress_safe_partial
  - lib/lz4/lz4_decompress.c:LZ4_decompress_safe_partial
  - lib/lz4/lz4_decompress.c:LZ4_decompress_safe_partial
  - lib/lz4/lz4_decompress.c:LZ4_decompress_safe
  - lib/lz4/lz4_decompress.c:LZ4_decompress_safe
  - lib/lz4/lz4_decompress.c:LZ4_decompress_safe
  - lib/lz4/lz4_decompress.c:LZ4_decompress_safe
  - lib/lz4/lz4_decompress.c:LZ4_decompress_safe
```
```
In drivers/usb/core/hcd.c (ffffffe000641414)
Location: include/linux/unaligned/le_struct.h:32
Inline: True
Inline callers:
  - drivers/usb/core/hcd.c:usb_hcd_map_urb_for_dma
  - drivers/usb/core/hcd.c:usb_hcd_map_urb_for_dma
```
```
In net/ipv6/addrconf.c (ffffffe000849928)
Location: include/linux/unaligned/le_struct.h:32
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:inet6_fill_ifla6_attrs
  - net/ipv6/addrconf.c:inet6_fill_ifla6_attrs
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
In lib/lzo/lzo1x_compress.c (ffffffff8153700a)
Location: include/linux/unaligned/access_ok.h:48
Inline: True
Inline callers:
  - lib/lzo/lzo1x_compress.c:lzogeneric1x_1_compress
  - lib/lzo/lzo1x_compress.c:lzogeneric1x_1_compress
  - lib/lzo/lzo1x_compress.c:lzo1x_1_do_compress
  - lib/lzo/lzo1x_compress.c:lzo1x_1_do_compress
  - lib/lzo/lzo1x_compress.c:lzo1x_1_do_compress
  - lib/lzo/lzo1x_compress.c:lzo1x_1_do_compress
```
```
In lib/lzo/lzo1x_decompress_safe.c (ffffffff815371d9)
Location: include/linux/unaligned/access_ok.h:48
Inline: True
Inline callers:
  - lib/lzo/lzo1x_decompress_safe.c:lzo1x_decompress_safe
  - lib/lzo/lzo1x_decompress_safe.c:lzo1x_decompress_safe
  - lib/lzo/lzo1x_decompress_safe.c:lzo1x_decompress_safe
  - lib/lzo/lzo1x_decompress_safe.c:lzo1x_decompress_safe
```
```
In lib/lz4/lz4_decompress.c (ffffffff81539112)
Location: include/linux/unaligned/access_ok.h:48
Inline: True
Inline callers:
  - lib/lz4/lz4_decompress.c:LZ4_decompress_fast_continue
  - lib/lz4/lz4_decompress.c:LZ4_decompress_fast_continue
  - lib/lz4/lz4_decompress.c:LZ4_decompress_fast_continue
  - lib/lz4/lz4_decompress.c:LZ4_decompress_fast_continue
  - lib/lz4/lz4_decompress.c:LZ4_decompress_fast_continue
  - lib/lz4/lz4_decompress.c:LZ4_decompress_safe_continue
  - lib/lz4/lz4_decompress.c:LZ4_decompress_safe_continue
  - lib/lz4/lz4_decompress.c:LZ4_decompress_safe_continue
  - lib/lz4/lz4_decompress.c:LZ4_decompress_safe_continue
  - lib/lz4/lz4_decompress.c:LZ4_decompress_safe_continue
  - lib/lz4/lz4_decompress.c:LZ4_decompress_fast_extDict
  - lib/lz4/lz4_decompress.c:LZ4_decompress_fast_extDict
  - lib/lz4/lz4_decompress.c:LZ4_decompress_fast_extDict
  - lib/lz4/lz4_decompress.c:LZ4_decompress_fast_extDict
  - lib/lz4/lz4_decompress.c:LZ4_decompress_fast_extDict
  - lib/lz4/lz4_decompress.c:LZ4_decompress_safe_forceExtDict
  - lib/lz4/lz4_decompress.c:LZ4_decompress_safe_forceExtDict
  - lib/lz4/lz4_decompress.c:LZ4_decompress_safe_forceExtDict
  - lib/lz4/lz4_decompress.c:LZ4_decompress_safe_forceExtDict
  - lib/lz4/lz4_decompress.c:LZ4_decompress_safe_forceExtDict
  - lib/lz4/lz4_decompress.c:LZ4_decompress_safe_withSmallPrefix
  - lib/lz4/lz4_decompress.c:LZ4_decompress_safe_withSmallPrefix
  - lib/lz4/lz4_decompress.c:LZ4_decompress_safe_withSmallPrefix
  - lib/lz4/lz4_decompress.c:LZ4_decompress_safe_withSmallPrefix
  - lib/lz4/lz4_decompress.c:LZ4_decompress_safe_withSmallPrefix
  - lib/lz4/lz4_decompress.c:LZ4_decompress_safe_withPrefix64k
  - lib/lz4/lz4_decompress.c:LZ4_decompress_safe_withPrefix64k
  - lib/lz4/lz4_decompress.c:LZ4_decompress_safe_withPrefix64k
  - lib/lz4/lz4_decompress.c:LZ4_decompress_safe_withPrefix64k
  - lib/lz4/lz4_decompress.c:LZ4_decompress_safe_withPrefix64k
  - lib/lz4/lz4_decompress.c:LZ4_decompress_fast
  - lib/lz4/lz4_decompress.c:LZ4_decompress_fast
  - lib/lz4/lz4_decompress.c:LZ4_decompress_fast
  - lib/lz4/lz4_decompress.c:LZ4_decompress_fast
  - lib/lz4/lz4_decompress.c:LZ4_decompress_fast
  - lib/lz4/lz4_decompress.c:LZ4_decompress_safe_partial
  - lib/lz4/lz4_decompress.c:LZ4_decompress_safe_partial
  - lib/lz4/lz4_decompress.c:LZ4_decompress_safe_partial
  - lib/lz4/lz4_decompress.c:LZ4_decompress_safe_partial
  - lib/lz4/lz4_decompress.c:LZ4_decompress_safe
  - lib/lz4/lz4_decompress.c:LZ4_decompress_safe
  - lib/lz4/lz4_decompress.c:LZ4_decompress_safe
  - lib/lz4/lz4_decompress.c:LZ4_decompress_safe
  - lib/lz4/lz4_decompress.c:LZ4_decompress_safe
```
```
In drivers/nvme/host/core.c (ffffffff81745422)
Location: include/linux/unaligned/access_ok.h:48
Inline: True
Inline callers:
  - drivers/nvme/host/core.c:nvme_pr_command
  - drivers/nvme/host/core.c:nvme_pr_command
```
```
In drivers/usb/core/hcd.c (ffffffff817a4ce6)
Location: include/linux/unaligned/access_ok.h:48
Inline: True
```
```
In net/ipv6/addrconf.c (ffffffff819dd6a9)
Location: include/linux/unaligned/access_ok.h:48
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:inet6_fill_ifla6_attrs
  - net/ipv6/addrconf.c:inet6_fill_ifla6_attrs
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
In lib/lzo/lzo1x_compress.c (ffffffff815272ea)
Location: include/linux/unaligned/access_ok.h:48
Inline: True
Inline callers:
  - lib/lzo/lzo1x_compress.c:lzogeneric1x_1_compress
  - lib/lzo/lzo1x_compress.c:lzogeneric1x_1_compress
  - lib/lzo/lzo1x_compress.c:lzo1x_1_do_compress
  - lib/lzo/lzo1x_compress.c:lzo1x_1_do_compress
  - lib/lzo/lzo1x_compress.c:lzo1x_1_do_compress
  - lib/lzo/lzo1x_compress.c:lzo1x_1_do_compress
```
```
In lib/lzo/lzo1x_decompress_safe.c (ffffffff815274b9)
Location: include/linux/unaligned/access_ok.h:48
Inline: True
Inline callers:
  - lib/lzo/lzo1x_decompress_safe.c:lzo1x_decompress_safe
  - lib/lzo/lzo1x_decompress_safe.c:lzo1x_decompress_safe
  - lib/lzo/lzo1x_decompress_safe.c:lzo1x_decompress_safe
  - lib/lzo/lzo1x_decompress_safe.c:lzo1x_decompress_safe
```
```
In lib/lz4/lz4_decompress.c (ffffffff815293f2)
Location: include/linux/unaligned/access_ok.h:48
Inline: True
Inline callers:
  - lib/lz4/lz4_decompress.c:LZ4_decompress_fast_continue
  - lib/lz4/lz4_decompress.c:LZ4_decompress_fast_continue
  - lib/lz4/lz4_decompress.c:LZ4_decompress_fast_continue
  - lib/lz4/lz4_decompress.c:LZ4_decompress_fast_continue
  - lib/lz4/lz4_decompress.c:LZ4_decompress_fast_continue
  - lib/lz4/lz4_decompress.c:LZ4_decompress_safe_continue
  - lib/lz4/lz4_decompress.c:LZ4_decompress_safe_continue
  - lib/lz4/lz4_decompress.c:LZ4_decompress_safe_continue
  - lib/lz4/lz4_decompress.c:LZ4_decompress_safe_continue
  - lib/lz4/lz4_decompress.c:LZ4_decompress_safe_continue
  - lib/lz4/lz4_decompress.c:LZ4_decompress_fast_extDict
  - lib/lz4/lz4_decompress.c:LZ4_decompress_fast_extDict
  - lib/lz4/lz4_decompress.c:LZ4_decompress_fast_extDict
  - lib/lz4/lz4_decompress.c:LZ4_decompress_fast_extDict
  - lib/lz4/lz4_decompress.c:LZ4_decompress_fast_extDict
  - lib/lz4/lz4_decompress.c:LZ4_decompress_safe_forceExtDict
  - lib/lz4/lz4_decompress.c:LZ4_decompress_safe_forceExtDict
  - lib/lz4/lz4_decompress.c:LZ4_decompress_safe_forceExtDict
  - lib/lz4/lz4_decompress.c:LZ4_decompress_safe_forceExtDict
  - lib/lz4/lz4_decompress.c:LZ4_decompress_safe_forceExtDict
  - lib/lz4/lz4_decompress.c:LZ4_decompress_safe_withSmallPrefix
  - lib/lz4/lz4_decompress.c:LZ4_decompress_safe_withSmallPrefix
  - lib/lz4/lz4_decompress.c:LZ4_decompress_safe_withSmallPrefix
  - lib/lz4/lz4_decompress.c:LZ4_decompress_safe_withSmallPrefix
  - lib/lz4/lz4_decompress.c:LZ4_decompress_safe_withSmallPrefix
  - lib/lz4/lz4_decompress.c:LZ4_decompress_safe_withPrefix64k
  - lib/lz4/lz4_decompress.c:LZ4_decompress_safe_withPrefix64k
  - lib/lz4/lz4_decompress.c:LZ4_decompress_safe_withPrefix64k
  - lib/lz4/lz4_decompress.c:LZ4_decompress_safe_withPrefix64k
  - lib/lz4/lz4_decompress.c:LZ4_decompress_safe_withPrefix64k
  - lib/lz4/lz4_decompress.c:LZ4_decompress_fast
  - lib/lz4/lz4_decompress.c:LZ4_decompress_fast
  - lib/lz4/lz4_decompress.c:LZ4_decompress_fast
  - lib/lz4/lz4_decompress.c:LZ4_decompress_fast
  - lib/lz4/lz4_decompress.c:LZ4_decompress_fast
  - lib/lz4/lz4_decompress.c:LZ4_decompress_safe_partial
  - lib/lz4/lz4_decompress.c:LZ4_decompress_safe_partial
  - lib/lz4/lz4_decompress.c:LZ4_decompress_safe_partial
  - lib/lz4/lz4_decompress.c:LZ4_decompress_safe_partial
  - lib/lz4/lz4_decompress.c:LZ4_decompress_safe
  - lib/lz4/lz4_decompress.c:LZ4_decompress_safe
  - lib/lz4/lz4_decompress.c:LZ4_decompress_safe
  - lib/lz4/lz4_decompress.c:LZ4_decompress_safe
  - lib/lz4/lz4_decompress.c:LZ4_decompress_safe
```
```
In drivers/nvme/host/core.c (ffffffff817270b2)
Location: include/linux/unaligned/access_ok.h:48
Inline: True
Inline callers:
  - drivers/nvme/host/core.c:nvme_pr_command
  - drivers/nvme/host/core.c:nvme_pr_command
```
```
In drivers/usb/core/hcd.c (ffffffff817967f6)
Location: include/linux/unaligned/access_ok.h:48
Inline: True
```
```
In net/ipv6/addrconf.c (ffffffff8199a469)
Location: include/linux/unaligned/access_ok.h:48
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:inet6_fill_ifla6_attrs
  - net/ipv6/addrconf.c:inet6_fill_ifla6_attrs
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
In lib/lzo/lzo1x_compress.c (ffffffff81532d4a)
Location: include/linux/unaligned/access_ok.h:48
Inline: True
Inline callers:
  - lib/lzo/lzo1x_compress.c:lzogeneric1x_1_compress
  - lib/lzo/lzo1x_compress.c:lzogeneric1x_1_compress
  - lib/lzo/lzo1x_compress.c:lzo1x_1_do_compress
  - lib/lzo/lzo1x_compress.c:lzo1x_1_do_compress
  - lib/lzo/lzo1x_compress.c:lzo1x_1_do_compress
  - lib/lzo/lzo1x_compress.c:lzo1x_1_do_compress
```
```
In lib/lzo/lzo1x_decompress_safe.c (ffffffff81532f19)
Location: include/linux/unaligned/access_ok.h:48
Inline: True
Inline callers:
  - lib/lzo/lzo1x_decompress_safe.c:lzo1x_decompress_safe
  - lib/lzo/lzo1x_decompress_safe.c:lzo1x_decompress_safe
  - lib/lzo/lzo1x_decompress_safe.c:lzo1x_decompress_safe
  - lib/lzo/lzo1x_decompress_safe.c:lzo1x_decompress_safe
```
```
In lib/lz4/lz4_decompress.c (ffffffff81534e52)
Location: include/linux/unaligned/access_ok.h:48
Inline: True
Inline callers:
  - lib/lz4/lz4_decompress.c:LZ4_decompress_fast_continue
  - lib/lz4/lz4_decompress.c:LZ4_decompress_fast_continue
  - lib/lz4/lz4_decompress.c:LZ4_decompress_fast_continue
  - lib/lz4/lz4_decompress.c:LZ4_decompress_fast_continue
  - lib/lz4/lz4_decompress.c:LZ4_decompress_fast_continue
  - lib/lz4/lz4_decompress.c:LZ4_decompress_safe_continue
  - lib/lz4/lz4_decompress.c:LZ4_decompress_safe_continue
  - lib/lz4/lz4_decompress.c:LZ4_decompress_safe_continue
  - lib/lz4/lz4_decompress.c:LZ4_decompress_safe_continue
  - lib/lz4/lz4_decompress.c:LZ4_decompress_safe_continue
  - lib/lz4/lz4_decompress.c:LZ4_decompress_fast_extDict
  - lib/lz4/lz4_decompress.c:LZ4_decompress_fast_extDict
  - lib/lz4/lz4_decompress.c:LZ4_decompress_fast_extDict
  - lib/lz4/lz4_decompress.c:LZ4_decompress_fast_extDict
  - lib/lz4/lz4_decompress.c:LZ4_decompress_fast_extDict
  - lib/lz4/lz4_decompress.c:LZ4_decompress_safe_forceExtDict
  - lib/lz4/lz4_decompress.c:LZ4_decompress_safe_forceExtDict
  - lib/lz4/lz4_decompress.c:LZ4_decompress_safe_forceExtDict
  - lib/lz4/lz4_decompress.c:LZ4_decompress_safe_forceExtDict
  - lib/lz4/lz4_decompress.c:LZ4_decompress_safe_forceExtDict
  - lib/lz4/lz4_decompress.c:LZ4_decompress_safe_withSmallPrefix
  - lib/lz4/lz4_decompress.c:LZ4_decompress_safe_withSmallPrefix
  - lib/lz4/lz4_decompress.c:LZ4_decompress_safe_withSmallPrefix
  - lib/lz4/lz4_decompress.c:LZ4_decompress_safe_withSmallPrefix
  - lib/lz4/lz4_decompress.c:LZ4_decompress_safe_withSmallPrefix
  - lib/lz4/lz4_decompress.c:LZ4_decompress_safe_withPrefix64k
  - lib/lz4/lz4_decompress.c:LZ4_decompress_safe_withPrefix64k
  - lib/lz4/lz4_decompress.c:LZ4_decompress_safe_withPrefix64k
  - lib/lz4/lz4_decompress.c:LZ4_decompress_safe_withPrefix64k
  - lib/lz4/lz4_decompress.c:LZ4_decompress_safe_withPrefix64k
  - lib/lz4/lz4_decompress.c:LZ4_decompress_fast
  - lib/lz4/lz4_decompress.c:LZ4_decompress_fast
  - lib/lz4/lz4_decompress.c:LZ4_decompress_fast
  - lib/lz4/lz4_decompress.c:LZ4_decompress_fast
  - lib/lz4/lz4_decompress.c:LZ4_decompress_fast
  - lib/lz4/lz4_decompress.c:LZ4_decompress_safe_partial
  - lib/lz4/lz4_decompress.c:LZ4_decompress_safe_partial
  - lib/lz4/lz4_decompress.c:LZ4_decompress_safe_partial
  - lib/lz4/lz4_decompress.c:LZ4_decompress_safe_partial
  - lib/lz4/lz4_decompress.c:LZ4_decompress_safe
  - lib/lz4/lz4_decompress.c:LZ4_decompress_safe
  - lib/lz4/lz4_decompress.c:LZ4_decompress_safe
  - lib/lz4/lz4_decompress.c:LZ4_decompress_safe
  - lib/lz4/lz4_decompress.c:LZ4_decompress_safe
```
```
In drivers/usb/core/hcd.c (ffffffff817e1786)
Location: include/linux/unaligned/access_ok.h:48
Inline: True
```
```
In net/ipv6/addrconf.c (ffffffff81a48129)
Location: include/linux/unaligned/access_ok.h:48
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:inet6_fill_ifla6_attrs
  - net/ipv6/addrconf.c:inet6_fill_ifla6_attrs
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
In lib/lzo/lzo1x_compress.c (ffffffff8154cb7a)
Location: include/linux/unaligned/access_ok.h:48
Inline: True
Inline callers:
  - lib/lzo/lzo1x_compress.c:lzogeneric1x_1_compress
  - lib/lzo/lzo1x_compress.c:lzogeneric1x_1_compress
  - lib/lzo/lzo1x_compress.c:lzo1x_1_do_compress
  - lib/lzo/lzo1x_compress.c:lzo1x_1_do_compress
  - lib/lzo/lzo1x_compress.c:lzo1x_1_do_compress
  - lib/lzo/lzo1x_compress.c:lzo1x_1_do_compress
```
```
In lib/lzo/lzo1x_decompress_safe.c (ffffffff8154cd49)
Location: include/linux/unaligned/access_ok.h:48
Inline: True
Inline callers:
  - lib/lzo/lzo1x_decompress_safe.c:lzo1x_decompress_safe
  - lib/lzo/lzo1x_decompress_safe.c:lzo1x_decompress_safe
  - lib/lzo/lzo1x_decompress_safe.c:lzo1x_decompress_safe
  - lib/lzo/lzo1x_decompress_safe.c:lzo1x_decompress_safe
```
```
In lib/lz4/lz4_decompress.c (ffffffff8154ec82)
Location: include/linux/unaligned/access_ok.h:48
Inline: True
Inline callers:
  - lib/lz4/lz4_decompress.c:LZ4_decompress_fast_continue
  - lib/lz4/lz4_decompress.c:LZ4_decompress_fast_continue
  - lib/lz4/lz4_decompress.c:LZ4_decompress_fast_continue
  - lib/lz4/lz4_decompress.c:LZ4_decompress_fast_continue
  - lib/lz4/lz4_decompress.c:LZ4_decompress_fast_continue
  - lib/lz4/lz4_decompress.c:LZ4_decompress_safe_continue
  - lib/lz4/lz4_decompress.c:LZ4_decompress_safe_continue
  - lib/lz4/lz4_decompress.c:LZ4_decompress_safe_continue
  - lib/lz4/lz4_decompress.c:LZ4_decompress_safe_continue
  - lib/lz4/lz4_decompress.c:LZ4_decompress_safe_continue
  - lib/lz4/lz4_decompress.c:LZ4_decompress_fast_extDict
  - lib/lz4/lz4_decompress.c:LZ4_decompress_fast_extDict
  - lib/lz4/lz4_decompress.c:LZ4_decompress_fast_extDict
  - lib/lz4/lz4_decompress.c:LZ4_decompress_fast_extDict
  - lib/lz4/lz4_decompress.c:LZ4_decompress_fast_extDict
  - lib/lz4/lz4_decompress.c:LZ4_decompress_safe_forceExtDict
  - lib/lz4/lz4_decompress.c:LZ4_decompress_safe_forceExtDict
  - lib/lz4/lz4_decompress.c:LZ4_decompress_safe_forceExtDict
  - lib/lz4/lz4_decompress.c:LZ4_decompress_safe_forceExtDict
  - lib/lz4/lz4_decompress.c:LZ4_decompress_safe_forceExtDict
  - lib/lz4/lz4_decompress.c:LZ4_decompress_safe_withSmallPrefix
  - lib/lz4/lz4_decompress.c:LZ4_decompress_safe_withSmallPrefix
  - lib/lz4/lz4_decompress.c:LZ4_decompress_safe_withSmallPrefix
  - lib/lz4/lz4_decompress.c:LZ4_decompress_safe_withSmallPrefix
  - lib/lz4/lz4_decompress.c:LZ4_decompress_safe_withSmallPrefix
  - lib/lz4/lz4_decompress.c:LZ4_decompress_safe_withPrefix64k
  - lib/lz4/lz4_decompress.c:LZ4_decompress_safe_withPrefix64k
  - lib/lz4/lz4_decompress.c:LZ4_decompress_safe_withPrefix64k
  - lib/lz4/lz4_decompress.c:LZ4_decompress_safe_withPrefix64k
  - lib/lz4/lz4_decompress.c:LZ4_decompress_safe_withPrefix64k
  - lib/lz4/lz4_decompress.c:LZ4_decompress_fast
  - lib/lz4/lz4_decompress.c:LZ4_decompress_fast
  - lib/lz4/lz4_decompress.c:LZ4_decompress_fast
  - lib/lz4/lz4_decompress.c:LZ4_decompress_fast
  - lib/lz4/lz4_decompress.c:LZ4_decompress_fast
  - lib/lz4/lz4_decompress.c:LZ4_decompress_safe_partial
  - lib/lz4/lz4_decompress.c:LZ4_decompress_safe_partial
  - lib/lz4/lz4_decompress.c:LZ4_decompress_safe_partial
  - lib/lz4/lz4_decompress.c:LZ4_decompress_safe_partial
  - lib/lz4/lz4_decompress.c:LZ4_decompress_safe
  - lib/lz4/lz4_decompress.c:LZ4_decompress_safe
  - lib/lz4/lz4_decompress.c:LZ4_decompress_safe
  - lib/lz4/lz4_decompress.c:LZ4_decompress_safe
  - lib/lz4/lz4_decompress.c:LZ4_decompress_safe
```
```
In drivers/usb/core/hcd.c (ffffffff817fbb76)
Location: include/linux/unaligned/access_ok.h:48
Inline: True
```
```
In net/ipv6/addrconf.c (ffffffff81a5405a)
Location: include/linux/unaligned/access_ok.h:48
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:inet6_fill_ifla6_attrs
  - net/ipv6/addrconf.c:inet6_fill_ifla6_attrs
```
</details>
</li>
</ul>

## Differences
