# Function: <code>put_unaligned_le32</code>

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
In lib/random32.c (ffffffff813f88d0)
Location: include/linux/unaligned/access_ok.h:42
Inline: True
Inline callers:
  - lib/random32.c:prandom_bytes_state
```
```
In lib/lzo/lzo1x_compress.c (ffffffff8140dc1b)
Location: include/linux/unaligned/access_ok.h:42
Inline: True
Inline callers:
  - lib/lzo/lzo1x_compress.c:lzo1x_1_do_compress
```
```
In lib/lzo/lzo1x_decompress_safe.c (ffffffff8140e23e)
Location: include/linux/unaligned/access_ok.h:42
Inline: True
Inline callers:
  - lib/lzo/lzo1x_decompress_safe.c:lzo1x_decompress_safe
  - lib/lzo/lzo1x_decompress_safe.c:lzo1x_decompress_safe
```
```
In lib/xz/xz_dec_bcj.c (ffffffff814111ff)
Location: include/linux/unaligned/access_ok.h:42
Inline: True
Inline callers:
  - lib/xz/xz_dec_bcj.c:bcj_apply
```
```
In drivers/usb/host/ehci-hcd.c (ffffffff81636a91)
Location: include/linux/unaligned/access_ok.h:42
Inline: True
Inline callers:
  - drivers/usb/host/ehci-hcd.c:ehci_hub_control
```
```
In drivers/usb/host/ohci-hcd.c (ffffffff8163e5f5)
Location: include/linux/unaligned/access_ok.h:42
Inline: True
Inline callers:
  - drivers/usb/host/ohci-hcd.c:ohci_hub_control
  - drivers/usb/host/ohci-hcd.c:ohci_hub_control
```
```
In drivers/usb/host/xhci-hub.c (ffffffff8165df9e)
Location: include/linux/unaligned/access_ok.h:42
Inline: True
Inline callers:
  - drivers/usb/host/xhci-hub.c:xhci_hub_control
  - drivers/usb/host/xhci-hub.c:xhci_hub_control
  - drivers/usb/host/xhci-hub.c:xhci_hub_control
  - drivers/usb/host/xhci-hub.c:xhci_hub_control
  - drivers/usb/host/xhci-hub.c:xhci_hub_control
```
```
In net/core/netpoll.c (ffffffff817394e1)
Location: include/linux/unaligned/access_ok.h:42
Inline: True
Inline callers:
  - net/core/netpoll.c:netpoll_send_udp
  - net/core/netpoll.c:netpoll_send_udp
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
In lib/random32.c (ffffffff8143f753)
Location: include/linux/unaligned/access_ok.h:42
Inline: True
Inline callers:
  - lib/random32.c:prandom_bytes_state
```
```
In lib/lzo/lzo1x_compress.c (ffffffff81455940)
Location: include/linux/unaligned/access_ok.h:42
Inline: True
Inline callers:
  - lib/lzo/lzo1x_compress.c:lzo1x_1_do_compress
```
```
In lib/lzo/lzo1x_decompress_safe.c (ffffffff814560e1)
Location: include/linux/unaligned/access_ok.h:42
Inline: True
Inline callers:
  - lib/lzo/lzo1x_decompress_safe.c:lzo1x_decompress_safe
  - lib/lzo/lzo1x_decompress_safe.c:lzo1x_decompress_safe
```
```
In lib/xz/xz_dec_bcj.c (ffffffff81458f6d)
Location: include/linux/unaligned/access_ok.h:42
Inline: True
Inline callers:
  - lib/xz/xz_dec_bcj.c:bcj_apply
```
```
In drivers/usb/host/ehci-hcd.c (ffffffff816977f4)
Location: include/linux/unaligned/access_ok.h:42
Inline: True
Inline callers:
  - drivers/usb/host/ehci-hcd.c:ehci_hub_control
```
```
In drivers/usb/host/ohci-hcd.c (ffffffff8169f1f3)
Location: include/linux/unaligned/access_ok.h:42
Inline: True
Inline callers:
  - drivers/usb/host/ohci-hcd.c:ohci_hub_control
```
```
In drivers/usb/host/xhci-hub.c (ffffffff816be6b0)
Location: include/linux/unaligned/access_ok.h:42
Inline: True
Inline callers:
  - drivers/usb/host/xhci-hub.c:xhci_hub_control
  - drivers/usb/host/xhci-hub.c:xhci_hub_control
  - drivers/usb/host/xhci-hub.c:xhci_hub_control
```
```
In net/core/netpoll.c (ffffffff817a5795)
Location: include/linux/unaligned/access_ok.h:42
Inline: True
Inline callers:
  - net/core/netpoll.c:netpoll_send_udp
  - net/core/netpoll.c:netpoll_send_udp
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
In lib/random32.c (ffffffff8145c853)
Location: include/linux/unaligned/access_ok.h:42
Inline: True
Inline callers:
  - lib/random32.c:prandom_bytes_state
```
```
In lib/lzo/lzo1x_compress.c (ffffffff81474300)
Location: include/linux/unaligned/access_ok.h:42
Inline: True
Inline callers:
  - lib/lzo/lzo1x_compress.c:lzo1x_1_do_compress
```
```
In lib/lzo/lzo1x_decompress_safe.c (ffffffff81474aa1)
Location: include/linux/unaligned/access_ok.h:42
Inline: True
Inline callers:
  - lib/lzo/lzo1x_decompress_safe.c:lzo1x_decompress_safe
  - lib/lzo/lzo1x_decompress_safe.c:lzo1x_decompress_safe
```
```
In lib/xz/xz_dec_bcj.c (ffffffff8147792d)
Location: include/linux/unaligned/access_ok.h:42
Inline: True
Inline callers:
  - lib/xz/xz_dec_bcj.c:bcj_apply
```
```
In drivers/ata/libata-scsi.c (ffffffff8165b0fe)
Location: include/linux/unaligned/access_ok.h:42
Inline: True
Inline callers:
  - drivers/ata/libata-scsi.c:ata_scsi_write_same_xlat
```
```
In drivers/usb/host/ehci-hcd.c (ffffffff816c5ce4)
Location: include/linux/unaligned/access_ok.h:42
Inline: True
Inline callers:
  - drivers/usb/host/ehci-hcd.c:ehci_hub_control
```
```
In drivers/usb/host/ohci-hcd.c (ffffffff816cd343)
Location: include/linux/unaligned/access_ok.h:42
Inline: True
Inline callers:
  - drivers/usb/host/ohci-hcd.c:ohci_hub_control
```
```
In drivers/usb/host/xhci-hub.c (ffffffff816ec560)
Location: include/linux/unaligned/access_ok.h:42
Inline: True
Inline callers:
  - drivers/usb/host/xhci-hub.c:xhci_hub_control
  - drivers/usb/host/xhci-hub.c:xhci_hub_control
  - drivers/usb/host/xhci-hub.c:xhci_hub_control
```
```
In net/core/netpoll.c (ffffffff817d4205)
Location: include/linux/unaligned/access_ok.h:42
Inline: True
Inline callers:
  - net/core/netpoll.c:netpoll_send_udp
  - net/core/netpoll.c:netpoll_send_udp
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
In crypto/aes_generic.c (ffffffff81411c4f)
Location: include/linux/unaligned/access_ok.h:42
Inline: True
Inline callers:
  - crypto/aes_generic.c:aes_decrypt
  - crypto/aes_generic.c:aes_decrypt
  - crypto/aes_generic.c:aes_decrypt
  - crypto/aes_generic.c:aes_decrypt
  - crypto/aes_generic.c:aes_encrypt
  - crypto/aes_generic.c:aes_encrypt
  - crypto/aes_generic.c:aes_encrypt
  - crypto/aes_generic.c:aes_encrypt
```
```
In lib/random32.c (ffffffff81461a79)
Location: include/linux/unaligned/access_ok.h:42
Inline: True
Inline callers:
  - lib/random32.c:prandom_bytes_state
```
```
In lib/lzo/lzo1x_compress.c (ffffffff814795fa)
Location: include/linux/unaligned/access_ok.h:42
Inline: True
Inline callers:
  - lib/lzo/lzo1x_compress.c:lzo1x_1_do_compress
```
```
In lib/lzo/lzo1x_decompress_safe.c (ffffffff81479cb5)
Location: include/linux/unaligned/access_ok.h:42
Inline: True
Inline callers:
  - lib/lzo/lzo1x_decompress_safe.c:lzo1x_decompress_safe
  - lib/lzo/lzo1x_decompress_safe.c:lzo1x_decompress_safe
```
```
In lib/lz4/lz4_decompress.c (0)
Location: include/linux/unaligned/access_ok.h:42
Inline: True
```
```
In lib/xz/xz_dec_bcj.c (ffffffff81480d06)
Location: include/linux/unaligned/access_ok.h:42
Inline: True
Inline callers:
  - lib/xz/xz_dec_bcj.c:bcj_apply
```
```
In drivers/usb/host/ehci-hcd.c (ffffffff816da465)
Location: include/linux/unaligned/access_ok.h:42
Inline: True
Inline callers:
  - drivers/usb/host/ehci-hcd.c:ehci_hub_control
```
```
In drivers/usb/host/ohci-hcd.c (ffffffff816e1ad2)
Location: include/linux/unaligned/access_ok.h:42
Inline: True
Inline callers:
  - drivers/usb/host/ohci-hcd.c:ohci_hub_control
```
```
In drivers/usb/host/xhci-hub.c (ffffffff81700a94)
Location: include/linux/unaligned/access_ok.h:42
Inline: True
Inline callers:
  - drivers/usb/host/xhci-hub.c:xhci_hub_control
  - drivers/usb/host/xhci-hub.c:xhci_hub_control
  - drivers/usb/host/xhci-hub.c:xhci_hub_control
```
```
In net/core/netpoll.c (ffffffff817f3547)
Location: include/linux/unaligned/access_ok.h:42
Inline: True
Inline callers:
  - net/core/netpoll.c:netpoll_send_udp
  - net/core/netpoll.c:netpoll_send_udp
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
In crypto/aes_generic.c (ffffffff8143c420)
Location: include/linux/unaligned/access_ok.h:43
Inline: True
Inline callers:
  - crypto/aes_generic.c:aes_decrypt
  - crypto/aes_generic.c:aes_decrypt
  - crypto/aes_generic.c:aes_decrypt
  - crypto/aes_generic.c:aes_decrypt
  - crypto/aes_generic.c:aes_encrypt
  - crypto/aes_generic.c:aes_encrypt
  - crypto/aes_generic.c:aes_encrypt
  - crypto/aes_generic.c:aes_encrypt
```
```
In lib/random32.c (ffffffff8148d979)
Location: include/linux/unaligned/access_ok.h:43
Inline: True
Inline callers:
  - lib/random32.c:prandom_bytes_state
```
```
In lib/lzo/lzo1x_compress.c (ffffffff814a699a)
Location: include/linux/unaligned/access_ok.h:43
Inline: True
Inline callers:
  - lib/lzo/lzo1x_compress.c:lzo1x_1_do_compress
```
```
In lib/lzo/lzo1x_decompress_safe.c (ffffffff814a7055)
Location: include/linux/unaligned/access_ok.h:43
Inline: True
Inline callers:
  - lib/lzo/lzo1x_decompress_safe.c:lzo1x_decompress_safe
  - lib/lzo/lzo1x_decompress_safe.c:lzo1x_decompress_safe
```
```
In lib/lz4/lz4_decompress.c (0)
Location: include/linux/unaligned/access_ok.h:43
Inline: True
```
```
In lib/xz/xz_dec_bcj.c (ffffffff814bcb3c)
Location: include/linux/unaligned/access_ok.h:43
Inline: True
Inline callers:
  - lib/xz/xz_dec_bcj.c:bcj_apply
```
```
In drivers/usb/host/ehci-hcd.c (ffffffff81746b95)
Location: include/linux/unaligned/access_ok.h:43
Inline: True
Inline callers:
  - drivers/usb/host/ehci-hcd.c:ehci_hub_control
```
```
In drivers/usb/host/ohci-hcd.c (ffffffff8174e2d2)
Location: include/linux/unaligned/access_ok.h:43
Inline: True
Inline callers:
  - drivers/usb/host/ohci-hcd.c:ohci_hub_control
```
```
In drivers/usb/host/xhci-hub.c (ffffffff8176d740)
Location: include/linux/unaligned/access_ok.h:43
Inline: True
Inline callers:
  - drivers/usb/host/xhci-hub.c:xhci_hub_control
  - drivers/usb/host/xhci-hub.c:xhci_hub_control
  - drivers/usb/host/xhci-hub.c:xhci_hub_control
```
```
In net/core/netpoll.c (ffffffff8186e937)
Location: include/linux/unaligned/access_ok.h:43
Inline: True
Inline callers:
  - net/core/netpoll.c:netpoll_send_udp
  - net/core/netpoll.c:netpoll_send_udp
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
In crypto/aes_generic.c (ffffffff8146ed5a)
Location: include/linux/unaligned/access_ok.h:43
Inline: True
Inline callers:
  - crypto/aes_generic.c:aes_decrypt
  - crypto/aes_generic.c:aes_decrypt
  - crypto/aes_generic.c:aes_decrypt
  - crypto/aes_generic.c:aes_decrypt
  - crypto/aes_generic.c:aes_encrypt
  - crypto/aes_generic.c:aes_encrypt
  - crypto/aes_generic.c:aes_encrypt
  - crypto/aes_generic.c:aes_encrypt
```
```
In crypto/crc32c_generic.c (ffffffff8146f36a)
Location: include/linux/unaligned/access_ok.h:43
Inline: True
Inline callers:
  - crypto/crc32c_generic.c:chksum_digest
  - crypto/crc32c_generic.c:chksum_finup
  - crypto/crc32c_generic.c:chksum_final
```
```
In lib/random32.c (ffffffff814c26f9)
Location: include/linux/unaligned/access_ok.h:43
Inline: True
Inline callers:
  - lib/random32.c:prandom_bytes_state
```
```
In lib/lzo/lzo1x_compress.c (ffffffff814dbebc)
Location: include/linux/unaligned/access_ok.h:43
Inline: True
Inline callers:
  - lib/lzo/lzo1x_compress.c:lzo1x_1_do_compress
```
```
In lib/lzo/lzo1x_decompress_safe.c (ffffffff814dc56b)
Location: include/linux/unaligned/access_ok.h:43
Inline: True
Inline callers:
  - lib/lzo/lzo1x_decompress_safe.c:lzo1x_decompress_safe
  - lib/lzo/lzo1x_decompress_safe.c:lzo1x_decompress_safe
```
```
In lib/lz4/lz4_decompress.c (ffffffff814df8cb)
Location: include/linux/unaligned/access_ok.h:43
Inline: True
Inline callers:
  - lib/lz4/lz4_decompress.c:LZ4_decompress_fast_usingDict
  - lib/lz4/lz4_decompress.c:LZ4_decompress_fast_usingDict
  - lib/lz4/lz4_decompress.c:LZ4_decompress_fast_usingDict
  - lib/lz4/lz4_decompress.c:LZ4_decompress_fast_usingDict
  - lib/lz4/lz4_decompress.c:LZ4_decompress_safe_usingDict
  - lib/lz4/lz4_decompress.c:LZ4_decompress_safe_usingDict
  - lib/lz4/lz4_decompress.c:LZ4_decompress_safe_usingDict
  - lib/lz4/lz4_decompress.c:LZ4_decompress_safe_usingDict
  - lib/lz4/lz4_decompress.c:LZ4_decompress_fast_continue
  - lib/lz4/lz4_decompress.c:LZ4_decompress_fast_continue
  - lib/lz4/lz4_decompress.c:LZ4_decompress_safe_continue
  - lib/lz4/lz4_decompress.c:LZ4_decompress_safe_continue
  - lib/lz4/lz4_decompress.c:LZ4_decompress_fast
  - lib/lz4/lz4_decompress.c:LZ4_decompress_safe_partial
  - lib/lz4/lz4_decompress.c:LZ4_decompress_safe
```
```
In lib/xz/xz_dec_bcj.c (ffffffff814ef300)
Location: include/linux/unaligned/access_ok.h:43
Inline: True
Inline callers:
  - lib/xz/xz_dec_bcj.c:bcj_apply
```
```
In drivers/usb/host/ehci-hcd.c (ffffffff8178771c)
Location: include/linux/unaligned/access_ok.h:43
Inline: True
Inline callers:
  - drivers/usb/host/ehci-hcd.c:ehci_hub_control
```
```
In drivers/usb/host/ohci-hcd.c (ffffffff8178ead0)
Location: include/linux/unaligned/access_ok.h:43
Inline: True
Inline callers:
  - drivers/usb/host/ohci-hcd.c:ohci_hub_control
  - drivers/usb/host/ohci-hcd.c:ohci_hub_control
```
```
In drivers/usb/host/xhci-hub.c (ffffffff817ae506)
Location: include/linux/unaligned/access_ok.h:43
Inline: True
Inline callers:
  - drivers/usb/host/xhci-hub.c:xhci_hub_control
  - drivers/usb/host/xhci-hub.c:xhci_hub_control
  - drivers/usb/host/xhci-hub.c:xhci_hub_control
  - drivers/usb/host/xhci-hub.c:xhci_hub_control
  - drivers/usb/host/xhci-hub.c:xhci_hub_control
```
```
In net/core/netpoll.c (ffffffff818bfac3)
Location: include/linux/unaligned/access_ok.h:43
Inline: True
Inline callers:
  - net/core/netpoll.c:netpoll_send_udp
  - net/core/netpoll.c:netpoll_send_udp
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
In crypto/aes_generic.c (ffffffff8148c70a)
Location: include/linux/unaligned/access_ok.h:43
Inline: True
Inline callers:
  - crypto/aes_generic.c:aes_decrypt
  - crypto/aes_generic.c:aes_decrypt
  - crypto/aes_generic.c:aes_decrypt
  - crypto/aes_generic.c:aes_decrypt
  - crypto/aes_generic.c:aes_encrypt
  - crypto/aes_generic.c:aes_encrypt
  - crypto/aes_generic.c:aes_encrypt
  - crypto/aes_generic.c:aes_encrypt
```
```
In crypto/crc32c_generic.c (ffffffff8148cd1a)
Location: include/linux/unaligned/access_ok.h:43
Inline: True
Inline callers:
  - crypto/crc32c_generic.c:chksum_digest
  - crypto/crc32c_generic.c:chksum_finup
  - crypto/crc32c_generic.c:chksum_final
```
```
In lib/random32.c (ffffffff814d6da9)
Location: include/linux/unaligned/access_ok.h:43
Inline: True
Inline callers:
  - lib/random32.c:prandom_bytes_state
```
```
In lib/lzo/lzo1x_compress.c (ffffffff814f092c)
Location: include/linux/unaligned/access_ok.h:43
Inline: True
Inline callers:
  - lib/lzo/lzo1x_compress.c:lzo1x_1_do_compress
```
```
In lib/lzo/lzo1x_decompress_safe.c (ffffffff814f0fdb)
Location: include/linux/unaligned/access_ok.h:43
Inline: True
Inline callers:
  - lib/lzo/lzo1x_decompress_safe.c:lzo1x_decompress_safe
  - lib/lzo/lzo1x_decompress_safe.c:lzo1x_decompress_safe
```
```
In lib/lz4/lz4_decompress.c (ffffffff814f2af8)
Location: include/linux/unaligned/access_ok.h:43
Inline: True
Inline callers:
  - lib/lz4/lz4_decompress.c:LZ4_decompress_fast_continue
  - lib/lz4/lz4_decompress.c:LZ4_decompress_safe_continue
  - lib/lz4/lz4_decompress.c:LZ4_decompress_fast_extDict
  - lib/lz4/lz4_decompress.c:LZ4_decompress_safe_forceExtDict
  - lib/lz4/lz4_decompress.c:LZ4_decompress_safe_withSmallPrefix
  - lib/lz4/lz4_decompress.c:LZ4_decompress_safe_withPrefix64k
  - lib/lz4/lz4_decompress.c:LZ4_decompress_fast
  - lib/lz4/lz4_decompress.c:LZ4_decompress_safe
```
```
In lib/xz/xz_dec_bcj.c (ffffffff81502fcc)
Location: include/linux/unaligned/access_ok.h:43
Inline: True
Inline callers:
  - lib/xz/xz_dec_bcj.c:bcj_apply
```
```
In drivers/usb/host/ehci-hcd.c (ffffffff817b0576)
Location: include/linux/unaligned/access_ok.h:43
Inline: True
Inline callers:
  - drivers/usb/host/ehci-hcd.c:ehci_hub_control
```
```
In drivers/usb/host/ohci-hcd.c (ffffffff817b5150)
Location: include/linux/unaligned/access_ok.h:43
Inline: True
Inline callers:
  - drivers/usb/host/ohci-hcd.c:ohci_hub_control
  - drivers/usb/host/ohci-hcd.c:ohci_hub_control
```
```
In drivers/usb/host/xhci-hub.c (ffffffff817d4bcf)
Location: include/linux/unaligned/access_ok.h:43
Inline: True
Inline callers:
  - drivers/usb/host/xhci-hub.c:xhci_hub_control
  - drivers/usb/host/xhci-hub.c:xhci_hub_control
  - drivers/usb/host/xhci-hub.c:xhci_hub_control
  - drivers/usb/host/xhci-hub.c:xhci_hub_control
  - drivers/usb/host/xhci-hub.c:xhci_hub_control
```
```
In net/core/netpoll.c (ffffffff818e88e3)
Location: include/linux/unaligned/access_ok.h:43
Inline: True
Inline callers:
  - net/core/netpoll.c:netpoll_send_udp
  - net/core/netpoll.c:netpoll_send_udp
```
```
In lib/chacha.c (ffffffff81a06f1c)
Location: include/linux/unaligned/access_ok.h:43
Inline: True
Inline callers:
  - lib/chacha.c:chacha_block
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
In crypto/aes_generic.c (ffffffff814b9de7)
Location: include/linux/unaligned/access_ok.h:43
Inline: True
Inline callers:
  - crypto/aes_generic.c:aes_decrypt
  - crypto/aes_generic.c:aes_decrypt
  - crypto/aes_generic.c:aes_decrypt
  - crypto/aes_generic.c:aes_decrypt
  - crypto/aes_generic.c:aes_encrypt
  - crypto/aes_generic.c:aes_encrypt
  - crypto/aes_generic.c:aes_encrypt
  - crypto/aes_generic.c:aes_encrypt
```
```
In crypto/crc32c_generic.c (ffffffff814ba40a)
Location: include/linux/unaligned/access_ok.h:43
Inline: True
Inline callers:
  - crypto/crc32c_generic.c:chksum_digest
  - crypto/crc32c_generic.c:chksum_finup
  - crypto/crc32c_generic.c:chksum_final
```
```
In lib/random32.c (ffffffff81502be3)
Location: include/linux/unaligned/access_ok.h:43
Inline: True
Inline callers:
  - lib/random32.c:prandom_bytes_state
```
```
In lib/lzo/lzo1x_compress.c (ffffffff8151d612)
Location: include/linux/unaligned/access_ok.h:43
Inline: True
Inline callers:
  - lib/lzo/lzo1x_compress.c:lzo1x_1_do_compress
  - lib/lzo/lzo1x_compress.c:lzo1x_1_do_compress
```
```
In lib/lzo/lzo1x_decompress_safe.c (ffffffff8151df0b)
Location: include/linux/unaligned/access_ok.h:43
Inline: True
Inline callers:
  - lib/lzo/lzo1x_decompress_safe.c:lzo1x_decompress_safe
  - lib/lzo/lzo1x_decompress_safe.c:lzo1x_decompress_safe
```
```
In lib/lz4/lz4_decompress.c (ffffffff8151fb3d)
Location: include/linux/unaligned/access_ok.h:43
Inline: True
Inline callers:
  - lib/lz4/lz4_decompress.c:LZ4_decompress_fast_continue
  - lib/lz4/lz4_decompress.c:LZ4_decompress_safe_continue
  - lib/lz4/lz4_decompress.c:LZ4_decompress_fast_extDict
  - lib/lz4/lz4_decompress.c:LZ4_decompress_safe_forceExtDict
  - lib/lz4/lz4_decompress.c:LZ4_decompress_safe_withSmallPrefix
  - lib/lz4/lz4_decompress.c:LZ4_decompress_safe_withPrefix64k
  - lib/lz4/lz4_decompress.c:LZ4_decompress_fast
  - lib/lz4/lz4_decompress.c:LZ4_decompress_safe
```
```
In lib/xz/xz_dec_bcj.c (ffffffff8153126f)
Location: include/linux/unaligned/access_ok.h:43
Inline: True
Inline callers:
  - lib/xz/xz_dec_bcj.c:bcj_apply
```
```
In drivers/usb/host/ehci-hcd.c (ffffffff817f0de1)
Location: include/linux/unaligned/access_ok.h:43
Inline: True
Inline callers:
  - drivers/usb/host/ehci-hcd.c:ehci_hub_control
```
```
In drivers/usb/host/ohci-hcd.c (ffffffff817f4656)
Location: include/linux/unaligned/access_ok.h:43
Inline: True
Inline callers:
  - drivers/usb/host/ohci-hcd.c:ohci_hub_control
  - drivers/usb/host/ohci-hcd.c:ohci_hub_control
```
```
In drivers/usb/host/xhci-hub.c (ffffffff81814c02)
Location: include/linux/unaligned/access_ok.h:43
Inline: True
Inline callers:
  - drivers/usb/host/xhci-hub.c:xhci_hub_control
  - drivers/usb/host/xhci-hub.c:xhci_hub_control
  - drivers/usb/host/xhci-hub.c:xhci_hub_control
  - drivers/usb/host/xhci-hub.c:xhci_hub_control
  - drivers/usb/host/xhci-hub.c:xhci_hub_control
```
```
In net/core/netpoll.c (ffffffff819380f5)
Location: include/linux/unaligned/access_ok.h:43
Inline: True
Inline callers:
  - net/core/netpoll.c:netpoll_send_udp
  - net/core/netpoll.c:netpoll_send_udp
```
```
In lib/chacha.c (ffffffff81a7688c)
Location: include/linux/unaligned/access_ok.h:43
Inline: True
Inline callers:
  - lib/chacha.c:chacha_block
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
In crypto/aes_generic.c (ffffffff814d2b87)
Location: include/linux/unaligned/access_ok.h:43
Inline: True
Inline callers:
  - crypto/aes_generic.c:crypto_aes_decrypt
  - crypto/aes_generic.c:crypto_aes_decrypt
  - crypto/aes_generic.c:crypto_aes_decrypt
  - crypto/aes_generic.c:crypto_aes_decrypt
  - crypto/aes_generic.c:crypto_aes_encrypt
  - crypto/aes_generic.c:crypto_aes_encrypt
  - crypto/aes_generic.c:crypto_aes_encrypt
  - crypto/aes_generic.c:crypto_aes_encrypt
```
```
In crypto/crc32c_generic.c (ffffffff814d31da)
Location: include/linux/unaligned/access_ok.h:43
Inline: True
Inline callers:
  - crypto/crc32c_generic.c:chksum_digest
  - crypto/crc32c_generic.c:chksum_finup
  - crypto/crc32c_generic.c:chksum_final
```
```
In lib/random32.c (ffffffff81520b83)
Location: include/linux/unaligned/access_ok.h:43
Inline: True
Inline callers:
  - lib/random32.c:prandom_bytes_state
```
```
In lib/crypto/aes.c (ffffffff8152f62b)
Location: include/linux/unaligned/access_ok.h:43
Inline: True
Inline callers:
  - lib/crypto/aes.c:aes_decrypt
  - lib/crypto/aes.c:aes_decrypt
  - lib/crypto/aes.c:aes_decrypt
  - lib/crypto/aes.c:aes_decrypt
  - lib/crypto/aes.c:aes_encrypt
  - lib/crypto/aes.c:aes_encrypt
  - lib/crypto/aes.c:aes_encrypt
  - lib/crypto/aes.c:aes_encrypt
```
```
In lib/lzo/lzo1x_compress.c (ffffffff8153e4a2)
Location: include/linux/unaligned/access_ok.h:43
Inline: True
Inline callers:
  - lib/lzo/lzo1x_compress.c:lzo1x_1_do_compress
  - lib/lzo/lzo1x_compress.c:lzo1x_1_do_compress
```
```
In lib/lzo/lzo1x_decompress_safe.c (ffffffff8153ed9b)
Location: include/linux/unaligned/access_ok.h:43
Inline: True
Inline callers:
  - lib/lzo/lzo1x_decompress_safe.c:lzo1x_decompress_safe
  - lib/lzo/lzo1x_decompress_safe.c:lzo1x_decompress_safe
```
```
In lib/lz4/lz4_decompress.c (ffffffff815409cd)
Location: include/linux/unaligned/access_ok.h:43
Inline: True
Inline callers:
  - lib/lz4/lz4_decompress.c:LZ4_decompress_fast_continue
  - lib/lz4/lz4_decompress.c:LZ4_decompress_safe_continue
  - lib/lz4/lz4_decompress.c:LZ4_decompress_fast_extDict
  - lib/lz4/lz4_decompress.c:LZ4_decompress_safe_forceExtDict
  - lib/lz4/lz4_decompress.c:LZ4_decompress_safe_withSmallPrefix
  - lib/lz4/lz4_decompress.c:LZ4_decompress_safe_withPrefix64k
  - lib/lz4/lz4_decompress.c:LZ4_decompress_fast
  - lib/lz4/lz4_decompress.c:LZ4_decompress_safe
```
```
In lib/xz/xz_dec_bcj.c (ffffffff815520ff)
Location: include/linux/unaligned/access_ok.h:43
Inline: True
Inline callers:
  - lib/xz/xz_dec_bcj.c:bcj_apply
```
```
In drivers/usb/host/ehci-hcd.c (ffffffff81821cd1)
Location: include/linux/unaligned/access_ok.h:43
Inline: True
Inline callers:
  - drivers/usb/host/ehci-hcd.c:ehci_hub_control
```
```
In drivers/usb/host/ohci-hcd.c (ffffffff818254b6)
Location: include/linux/unaligned/access_ok.h:43
Inline: True
Inline callers:
  - drivers/usb/host/ohci-hcd.c:ohci_hub_control
  - drivers/usb/host/ohci-hcd.c:ohci_hub_control
```
```
In drivers/usb/host/xhci-hub.c (ffffffff81845e2d)
Location: include/linux/unaligned/access_ok.h:43
Inline: True
Inline callers:
  - drivers/usb/host/xhci-hub.c:xhci_hub_control
  - drivers/usb/host/xhci-hub.c:xhci_hub_control
  - drivers/usb/host/xhci-hub.c:xhci_hub_control
  - drivers/usb/host/xhci-hub.c:xhci_hub_control
  - drivers/usb/host/xhci-hub.c:xhci_hub_control
```
```
In net/core/netpoll.c (ffffffff8196afb5)
Location: include/linux/unaligned/access_ok.h:43
Inline: True
Inline callers:
  - net/core/netpoll.c:netpoll_send_udp
  - net/core/netpoll.c:netpoll_send_udp
```
```
In lib/chacha.c (ffffffff81aadc9c)
Location: include/linux/unaligned/access_ok.h:43
Inline: True
Inline callers:
  - lib/chacha.c:chacha_block
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
In crypto/aes_generic.c (ffffffff81531cea)
Location: include/linux/unaligned/access_ok.h:43
Inline: True
Inline callers:
  - crypto/aes_generic.c:crypto_aes_decrypt
  - crypto/aes_generic.c:crypto_aes_decrypt
  - crypto/aes_generic.c:crypto_aes_decrypt
  - crypto/aes_generic.c:crypto_aes_decrypt
  - crypto/aes_generic.c:crypto_aes_encrypt
  - crypto/aes_generic.c:crypto_aes_encrypt
  - crypto/aes_generic.c:crypto_aes_encrypt
  - crypto/aes_generic.c:crypto_aes_encrypt
```
```
In crypto/crc32c_generic.c (ffffffff8153245a)
Location: include/linux/unaligned/access_ok.h:43
Inline: True
Inline callers:
  - crypto/crc32c_generic.c:chksum_digest
  - crypto/crc32c_generic.c:chksum_finup
  - crypto/crc32c_generic.c:chksum_final
```
```
In lib/random32.c (ffffffff81583f9f)
Location: include/linux/unaligned/access_ok.h:43
Inline: True
Inline callers:
  - lib/random32.c:prandom_bytes_state
```
```
In lib/crypto/chacha.c (ffffffff81592aca)
Location: include/linux/unaligned/access_ok.h:43
Inline: True
Inline callers:
  - lib/crypto/chacha.c:chacha_block_generic
```
```
In lib/crypto/aes.c (ffffffff815932e1)
Location: include/linux/unaligned/access_ok.h:43
Inline: True
Inline callers:
  - lib/crypto/aes.c:aes_decrypt
  - lib/crypto/aes.c:aes_decrypt
  - lib/crypto/aes.c:aes_decrypt
  - lib/crypto/aes.c:aes_decrypt
  - lib/crypto/aes.c:aes_encrypt
  - lib/crypto/aes.c:aes_encrypt
  - lib/crypto/aes.c:aes_encrypt
  - lib/crypto/aes.c:aes_encrypt
```
```
In lib/lzo/lzo1x_compress.c (ffffffff815a2ab1)
Location: include/linux/unaligned/access_ok.h:43
Inline: True
Inline callers:
  - lib/lzo/lzo1x_compress.c:lzo1x_1_do_compress
  - lib/lzo/lzo1x_compress.c:lzo1x_1_do_compress
```
```
In lib/lzo/lzo1x_decompress_safe.c (ffffffff815a33ec)
Location: include/linux/unaligned/access_ok.h:43
Inline: True
Inline callers:
  - lib/lzo/lzo1x_decompress_safe.c:lzo1x_decompress_safe
  - lib/lzo/lzo1x_decompress_safe.c:lzo1x_decompress_safe
```
```
In lib/lz4/lz4_compress.c (ffffffff815a5748)
Location: include/linux/unaligned/access_ok.h:43
Inline: True
Inline callers:
  - lib/lz4/lz4_compress.c:LZ4_compress_fast_continue
  - lib/lz4/lz4_compress.c:LZ4_compress_fast_continue
  - lib/lz4/lz4_compress.c:LZ4_compress_fast_continue
  - lib/lz4/lz4_compress.c:LZ4_compress_fast_continue
  - lib/lz4/lz4_compress.c:LZ4_compress_fast_continue
  - lib/lz4/lz4_compress.c:LZ4_compress_fast_continue
  - lib/lz4/lz4_compress.c:LZ4_compress_fast_continue
  - lib/lz4/lz4_compress.c:LZ4_compress_fast_continue
  - lib/lz4/lz4_compress.c:LZ4_compress_fast_extState
  - lib/lz4/lz4_compress.c:LZ4_compress_fast_extState
  - lib/lz4/lz4_compress.c:LZ4_compress_fast_extState
  - lib/lz4/lz4_compress.c:LZ4_compress_fast_extState
  - lib/lz4/lz4_compress.c:LZ4_compress_fast_extState
  - lib/lz4/lz4_compress.c:LZ4_compress_fast_extState
  - lib/lz4/lz4_compress.c:LZ4_compress_fast_extState
  - lib/lz4/lz4_compress.c:LZ4_compress_fast_extState
```
```
In lib/lz4/lz4_decompress.c (ffffffff815aa02f)
Location: include/linux/unaligned/access_ok.h:43
Inline: True
Inline callers:
  - lib/lz4/lz4_decompress.c:LZ4_decompress_fast_continue
  - lib/lz4/lz4_decompress.c:LZ4_decompress_safe_continue
  - lib/lz4/lz4_decompress.c:LZ4_decompress_fast_extDict
  - lib/lz4/lz4_decompress.c:LZ4_decompress_safe_forceExtDict
  - lib/lz4/lz4_decompress.c:LZ4_decompress_safe_withSmallPrefix
  - lib/lz4/lz4_decompress.c:LZ4_decompress_safe_withPrefix64k
  - lib/lz4/lz4_decompress.c:LZ4_decompress_fast
  - lib/lz4/lz4_decompress.c:LZ4_decompress_safe
```
```
In lib/zstd/fse_compress.c (0)
Location: include/linux/unaligned/access_ok.h:43
Inline: True
```
```
In lib/zstd/huf_compress.c (0)
Location: include/linux/unaligned/access_ok.h:43
Inline: True
```
```
In lib/zstd/compress.c (ffffffff815c9bbc)
Location: include/linux/unaligned/access_ok.h:43
Inline: True
Inline callers:
  - lib/zstd/compress.c:ZSTD_compressSequences_internal
  - lib/zstd/compress.c:ZSTD_compressSequences_internal
  - lib/zstd/compress.c:ZSTD_compressSequences_internal
  - lib/zstd/compress.c:ZSTD_noCompressLiterals
```
```
In lib/xz/xz_dec_bcj.c (ffffffff815db5df)
Location: include/linux/unaligned/access_ok.h:43
Inline: True
Inline callers:
  - lib/xz/xz_dec_bcj.c:bcj_apply
```
```
In drivers/base/regmap/regmap.c (ffffffff817d9865)
Location: include/linux/unaligned/access_ok.h:43
Inline: True
Inline callers:
  - drivers/base/regmap/regmap.c:regmap_format_32_le
```
```
In drivers/usb/host/ehci-hcd.c (ffffffff818f4359)
Location: include/linux/unaligned/access_ok.h:43
Inline: True
Inline callers:
  - drivers/usb/host/ehci-hcd.c:ehci_hub_control
```
```
In drivers/usb/host/ohci-hcd.c (ffffffff818f9196)
Location: include/linux/unaligned/access_ok.h:43
Inline: True
Inline callers:
  - drivers/usb/host/ohci-hcd.c:ohci_hub_control
  - drivers/usb/host/ohci-hcd.c:ohci_hub_control
```
```
In drivers/usb/host/xhci-hub.c (ffffffff81918d25)
Location: include/linux/unaligned/access_ok.h:43
Inline: True
Inline callers:
  - drivers/usb/host/xhci-hub.c:xhci_hub_control
  - drivers/usb/host/xhci-hub.c:xhci_hub_control
  - drivers/usb/host/xhci-hub.c:xhci_create_usb3_bos_desc
  - drivers/usb/host/xhci-hub.c:xhci_create_usb3_bos_desc
  - drivers/usb/host/xhci-hub.c:xhci_create_usb3_bos_desc
```
```
In net/core/netpoll.c (ffffffff81a3ed1e)
Location: include/linux/unaligned/access_ok.h:43
Inline: True
Inline callers:
  - net/core/netpoll.c:netpoll_send_udp
  - net/core/netpoll.c:netpoll_send_udp
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
In crypto/aes_generic.c (ffffffff8154ec3a)
Location: include/linux/unaligned/access_ok.h:43
Inline: True
Inline callers:
  - crypto/aes_generic.c:crypto_aes_decrypt
  - crypto/aes_generic.c:crypto_aes_decrypt
  - crypto/aes_generic.c:crypto_aes_decrypt
  - crypto/aes_generic.c:crypto_aes_decrypt
  - crypto/aes_generic.c:crypto_aes_encrypt
  - crypto/aes_generic.c:crypto_aes_encrypt
  - crypto/aes_generic.c:crypto_aes_encrypt
  - crypto/aes_generic.c:crypto_aes_encrypt
```
```
In crypto/crc32c_generic.c (ffffffff8154f3aa)
Location: include/linux/unaligned/access_ok.h:43
Inline: True
Inline callers:
  - crypto/crc32c_generic.c:chksum_digest
  - crypto/crc32c_generic.c:chksum_finup
  - crypto/crc32c_generic.c:chksum_final
```
```
In lib/random32.c (ffffffff815a0e09)
Location: include/linux/unaligned/access_ok.h:43
Inline: True
Inline callers:
  - lib/random32.c:prandom_bytes
  - lib/random32.c:prandom_bytes_state
```
```
In lib/crypto/chacha.c (ffffffff815af65f)
Location: include/linux/unaligned/access_ok.h:43
Inline: True
Inline callers:
  - lib/crypto/chacha.c:chacha_block_generic
```
```
In lib/crypto/aes.c (ffffffff815afeef)
Location: include/linux/unaligned/access_ok.h:43
Inline: True
Inline callers:
  - lib/crypto/aes.c:aes_decrypt
  - lib/crypto/aes.c:aes_decrypt
  - lib/crypto/aes.c:aes_decrypt
  - lib/crypto/aes.c:aes_decrypt
  - lib/crypto/aes.c:aes_encrypt
  - lib/crypto/aes.c:aes_encrypt
  - lib/crypto/aes.c:aes_encrypt
  - lib/crypto/aes.c:aes_encrypt
```
```
In lib/lzo/lzo1x_compress.c (ffffffff815be5b6)
Location: include/linux/unaligned/access_ok.h:43
Inline: True
Inline callers:
  - lib/lzo/lzo1x_compress.c:lzo1x_1_do_compress
  - lib/lzo/lzo1x_compress.c:lzo1x_1_do_compress
```
```
In lib/lzo/lzo1x_decompress_safe.c (ffffffff815bef27)
Location: include/linux/unaligned/access_ok.h:43
Inline: True
Inline callers:
  - lib/lzo/lzo1x_decompress_safe.c:lzo1x_decompress_safe
  - lib/lzo/lzo1x_decompress_safe.c:lzo1x_decompress_safe
```
```
In lib/lz4/lz4_compress.c (ffffffff815c12c8)
Location: include/linux/unaligned/access_ok.h:43
Inline: True
Inline callers:
  - lib/lz4/lz4_compress.c:LZ4_compress_fast_continue
  - lib/lz4/lz4_compress.c:LZ4_compress_fast_continue
  - lib/lz4/lz4_compress.c:LZ4_compress_fast_continue
  - lib/lz4/lz4_compress.c:LZ4_compress_fast_continue
  - lib/lz4/lz4_compress.c:LZ4_compress_fast_continue
  - lib/lz4/lz4_compress.c:LZ4_compress_fast_continue
  - lib/lz4/lz4_compress.c:LZ4_compress_fast_continue
  - lib/lz4/lz4_compress.c:LZ4_compress_fast_continue
  - lib/lz4/lz4_compress.c:LZ4_compress_fast_extState
  - lib/lz4/lz4_compress.c:LZ4_compress_fast_extState
  - lib/lz4/lz4_compress.c:LZ4_compress_fast_extState
  - lib/lz4/lz4_compress.c:LZ4_compress_fast_extState
  - lib/lz4/lz4_compress.c:LZ4_compress_fast_extState
  - lib/lz4/lz4_compress.c:LZ4_compress_fast_extState
  - lib/lz4/lz4_compress.c:LZ4_compress_fast_extState
  - lib/lz4/lz4_compress.c:LZ4_compress_fast_extState
```
```
In lib/lz4/lz4_decompress.c (ffffffff815c5b16)
Location: include/linux/unaligned/access_ok.h:43
Inline: True
Inline callers:
  - lib/lz4/lz4_decompress.c:LZ4_decompress_fast_continue
  - lib/lz4/lz4_decompress.c:LZ4_decompress_safe_continue
  - lib/lz4/lz4_decompress.c:LZ4_decompress_fast_extDict
  - lib/lz4/lz4_decompress.c:LZ4_decompress_safe_forceExtDict
  - lib/lz4/lz4_decompress.c:LZ4_decompress_safe_withSmallPrefix
  - lib/lz4/lz4_decompress.c:LZ4_decompress_safe_withPrefix64k
  - lib/lz4/lz4_decompress.c:LZ4_decompress_fast
  - lib/lz4/lz4_decompress.c:LZ4_decompress_safe
```
```
In lib/zstd/fse_compress.c (0)
Location: include/linux/unaligned/access_ok.h:43
Inline: True
```
```
In lib/zstd/huf_compress.c (0)
Location: include/linux/unaligned/access_ok.h:43
Inline: True
```
```
In lib/zstd/compress.c (ffffffff815e778c)
Location: include/linux/unaligned/access_ok.h:43
Inline: True
Inline callers:
  - lib/zstd/compress.c:ZSTD_compressSequences_internal
  - lib/zstd/compress.c:ZSTD_compressSequences_internal
  - lib/zstd/compress.c:ZSTD_compressSequences_internal
  - lib/zstd/compress.c:ZSTD_noCompressLiterals
```
```
In lib/xz/xz_dec_bcj.c (ffffffff815f9231)
Location: include/linux/unaligned/access_ok.h:43
Inline: True
Inline callers:
  - lib/xz/xz_dec_bcj.c:bcj_apply
```
```
In drivers/base/regmap/regmap.c (ffffffff817ee6b5)
Location: include/linux/unaligned/access_ok.h:43
Inline: True
Inline callers:
  - drivers/base/regmap/regmap.c:regmap_format_32_le
```
```
In drivers/usb/host/ehci-hcd.c (ffffffff818fd299)
Location: include/linux/unaligned/access_ok.h:43
Inline: True
Inline callers:
  - drivers/usb/host/ehci-hcd.c:ehci_hub_control
```
```
In drivers/usb/host/ohci-hcd.c (ffffffff81901cd6)
Location: include/linux/unaligned/access_ok.h:43
Inline: True
Inline callers:
  - drivers/usb/host/ohci-hcd.c:ohci_hub_control
  - drivers/usb/host/ohci-hcd.c:ohci_hub_control
```
```
In drivers/usb/host/xhci-hub.c (ffffffff8191f66d)
Location: include/linux/unaligned/access_ok.h:43
Inline: True
Inline callers:
  - drivers/usb/host/xhci-hub.c:xhci_hub_control
  - drivers/usb/host/xhci-hub.c:xhci_hub_control
  - drivers/usb/host/xhci-hub.c:xhci_create_usb3_bos_desc
  - drivers/usb/host/xhci-hub.c:xhci_create_usb3_bos_desc
  - drivers/usb/host/xhci-hub.c:xhci_create_usb3_bos_desc
```
```
In net/core/netpoll.c (ffffffff81a41abe)
Location: include/linux/unaligned/access_ok.h:43
Inline: True
Inline callers:
  - net/core/netpoll.c:netpoll_send_udp
  - net/core/netpoll.c:netpoll_send_udp
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
In crypto/aes_generic.c (ffffffff815574a6)
Location: include/linux/unaligned/access_ok.h:43
Inline: True
Inline callers:
  - crypto/aes_generic.c:crypto_aes_decrypt
  - crypto/aes_generic.c:crypto_aes_decrypt
  - crypto/aes_generic.c:crypto_aes_decrypt
  - crypto/aes_generic.c:crypto_aes_decrypt
  - crypto/aes_generic.c:crypto_aes_encrypt
  - crypto/aes_generic.c:crypto_aes_encrypt
  - crypto/aes_generic.c:crypto_aes_encrypt
  - crypto/aes_generic.c:crypto_aes_encrypt
```
```
In crypto/crc32c_generic.c (ffffffff81557c1a)
Location: include/linux/unaligned/access_ok.h:43
Inline: True
Inline callers:
  - crypto/crc32c_generic.c:chksum_digest
  - crypto/crc32c_generic.c:chksum_finup
  - crypto/crc32c_generic.c:chksum_final
```
```
In lib/random32.c (ffffffff815a7cbf)
Location: include/linux/unaligned/access_ok.h:43
Inline: True
Inline callers:
  - lib/random32.c:prandom_bytes
  - lib/random32.c:prandom_bytes_state
```
```
In lib/crypto/chacha.c (ffffffff815ba47f)
Location: include/linux/unaligned/access_ok.h:43
Inline: True
Inline callers:
  - lib/crypto/chacha.c:chacha_block_generic
```
```
In lib/crypto/aes.c (ffffffff815bacf8)
Location: include/linux/unaligned/access_ok.h:43
Inline: True
Inline callers:
  - lib/crypto/aes.c:aes_decrypt
  - lib/crypto/aes.c:aes_decrypt
  - lib/crypto/aes.c:aes_decrypt
  - lib/crypto/aes.c:aes_decrypt
  - lib/crypto/aes.c:aes_encrypt
  - lib/crypto/aes.c:aes_encrypt
  - lib/crypto/aes.c:aes_encrypt
  - lib/crypto/aes.c:aes_encrypt
```
```
In lib/lzo/lzo1x_compress.c (ffffffff815c9236)
Location: include/linux/unaligned/access_ok.h:43
Inline: True
Inline callers:
  - lib/lzo/lzo1x_compress.c:lzo1x_1_do_compress
  - lib/lzo/lzo1x_compress.c:lzo1x_1_do_compress
```
```
In lib/lzo/lzo1x_decompress_safe.c (ffffffff815c9b97)
Location: include/linux/unaligned/access_ok.h:43
Inline: True
Inline callers:
  - lib/lzo/lzo1x_decompress_safe.c:lzo1x_decompress_safe
  - lib/lzo/lzo1x_decompress_safe.c:lzo1x_decompress_safe
```
```
In lib/lz4/lz4_decompress.c (ffffffff815cb7dd)
Location: include/linux/unaligned/access_ok.h:43
Inline: True
Inline callers:
  - lib/lz4/lz4_decompress.c:LZ4_decompress_fast_continue
  - lib/lz4/lz4_decompress.c:LZ4_decompress_safe_continue
  - lib/lz4/lz4_decompress.c:LZ4_decompress_fast_extDict
  - lib/lz4/lz4_decompress.c:LZ4_decompress_safe_forceExtDict
  - lib/lz4/lz4_decompress.c:LZ4_decompress_safe_withSmallPrefix
  - lib/lz4/lz4_decompress.c:LZ4_decompress_safe_withPrefix64k
  - lib/lz4/lz4_decompress.c:LZ4_decompress_fast
  - lib/lz4/lz4_decompress.c:LZ4_decompress_safe
```
```
In lib/xz/xz_dec_bcj.c (ffffffff815dbce5)
Location: include/linux/unaligned/access_ok.h:43
Inline: True
Inline callers:
  - lib/xz/xz_dec_bcj.c:bcj_apply
```
```
In drivers/base/regmap/regmap.c (ffffffff817d2f65)
Location: include/linux/unaligned/access_ok.h:43
Inline: True
Inline callers:
  - drivers/base/regmap/regmap.c:regmap_format_32_le
```
```
In drivers/usb/host/ehci-hcd.c (ffffffff818dfc5c)
Location: include/linux/unaligned/access_ok.h:43
Inline: True
Inline callers:
  - drivers/usb/host/ehci-hcd.c:ehci_hub_control
```
```
In drivers/usb/host/ohci-hcd.c (ffffffff818e6146)
Location: include/linux/unaligned/access_ok.h:43
Inline: True
Inline callers:
  - drivers/usb/host/ohci-hcd.c:ohci_hub_control
  - drivers/usb/host/ohci-hcd.c:ohci_hub_control
```
```
In drivers/usb/host/xhci-hub.c (ffffffff81902d7c)
Location: include/linux/unaligned/access_ok.h:43
Inline: True
Inline callers:
  - drivers/usb/host/xhci-hub.c:xhci_hub_control
  - drivers/usb/host/xhci-hub.c:xhci_hub_control
```
```
In net/core/netpoll.c (ffffffff81a26581)
Location: include/linux/unaligned/access_ok.h:43
Inline: True
Inline callers:
  - net/core/netpoll.c:netpoll_send_udp
  - net/core/netpoll.c:netpoll_send_udp
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
In crypto/aes_generic.c (ffffffff815b8789)
Location: include/asm-generic/unaligned.h:45
Inline: True
Inline callers:
  - crypto/aes_generic.c:crypto_aes_decrypt
  - crypto/aes_generic.c:crypto_aes_decrypt
  - crypto/aes_generic.c:crypto_aes_decrypt
  - crypto/aes_generic.c:crypto_aes_decrypt
  - crypto/aes_generic.c:crypto_aes_encrypt
  - crypto/aes_generic.c:crypto_aes_encrypt
  - crypto/aes_generic.c:crypto_aes_encrypt
  - crypto/aes_generic.c:crypto_aes_encrypt
```
```
In crypto/crc32c_generic.c (ffffffff815b8eca)
Location: include/asm-generic/unaligned.h:45
Inline: True
Inline callers:
  - crypto/crc32c_generic.c:chksum_digest
  - crypto/crc32c_generic.c:chksum_finup
  - crypto/crc32c_generic.c:chksum_final
```
```
In lib/crypto/chacha.c (ffffffff81620e1a)
Location: include/asm-generic/unaligned.h:45
Inline: True
Inline callers:
  - lib/crypto/chacha.c:chacha_block_generic
```
```
In lib/crypto/aes.c (ffffffff816213f8)
Location: include/asm-generic/unaligned.h:45
Inline: True
Inline callers:
  - lib/crypto/aes.c:aes_decrypt
  - lib/crypto/aes.c:aes_decrypt
  - lib/crypto/aes.c:aes_decrypt
  - lib/crypto/aes.c:aes_decrypt
  - lib/crypto/aes.c:aes_encrypt
  - lib/crypto/aes.c:aes_encrypt
  - lib/crypto/aes.c:aes_encrypt
  - lib/crypto/aes.c:aes_encrypt
```
```
In lib/lzo/lzo1x_compress.c (ffffffff8163382a)
Location: include/asm-generic/unaligned.h:45
Inline: True
Inline callers:
  - lib/lzo/lzo1x_compress.c:lzo1x_1_do_compress
```
```
In lib/xz/xz_dec_bcj.c (ffffffff8164742c)
Location: include/asm-generic/unaligned.h:45
Inline: True
Inline callers:
  - lib/xz/xz_dec_bcj.c:bcj_x86
```
```
In drivers/base/regmap/regmap.c (ffffffff8185ecb0)
Location: include/asm-generic/unaligned.h:45
Inline: True
Inline callers:
  - drivers/base/regmap/regmap.c:regmap_format_32_le
```
```
In drivers/usb/host/ehci-hcd.c (ffffffff8197b67b)
Location: include/asm-generic/unaligned.h:45
Inline: True
Inline callers:
  - drivers/usb/host/ehci-hcd.c:ehci_hub_control
```
```
In drivers/usb/host/ohci-hcd.c (ffffffff81982506)
Location: include/asm-generic/unaligned.h:45
Inline: True
Inline callers:
  - drivers/usb/host/ohci-hcd.c:ohci_hub_control
  - drivers/usb/host/ohci-hcd.c:ohci_hub_control
```
```
In drivers/usb/host/xhci-hub.c (ffffffff819a3297)
Location: include/asm-generic/unaligned.h:45
Inline: True
Inline callers:
  - drivers/usb/host/xhci-hub.c:xhci_hub_control
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
In crypto/aes_generic.c (ffffffff81661ab9)
Location: include/asm-generic/unaligned.h:45
Inline: True
Inline callers:
  - crypto/aes_generic.c:crypto_aes_decrypt
  - crypto/aes_generic.c:crypto_aes_decrypt
  - crypto/aes_generic.c:crypto_aes_decrypt
  - crypto/aes_generic.c:crypto_aes_decrypt
  - crypto/aes_generic.c:crypto_aes_encrypt
  - crypto/aes_generic.c:crypto_aes_encrypt
  - crypto/aes_generic.c:crypto_aes_encrypt
  - crypto/aes_generic.c:crypto_aes_encrypt
```
```
In crypto/crc32c_generic.c (ffffffff8166227a)
Location: include/asm-generic/unaligned.h:45
Inline: True
Inline callers:
  - crypto/crc32c_generic.c:chksum_digest
  - crypto/crc32c_generic.c:chksum_finup
  - crypto/crc32c_generic.c:chksum_final
```
```
In lib/crypto/chacha.c (ffffffff816ef04a)
Location: include/asm-generic/unaligned.h:45
Inline: True
Inline callers:
  - lib/crypto/chacha.c:chacha_block_generic
```
```
In lib/crypto/aes.c (ffffffff816ef638)
Location: include/asm-generic/unaligned.h:45
Inline: True
Inline callers:
  - lib/crypto/aes.c:aes_decrypt
  - lib/crypto/aes.c:aes_decrypt
  - lib/crypto/aes.c:aes_decrypt
  - lib/crypto/aes.c:aes_decrypt
  - lib/crypto/aes.c:aes_encrypt
  - lib/crypto/aes.c:aes_encrypt
  - lib/crypto/aes.c:aes_encrypt
  - lib/crypto/aes.c:aes_encrypt
```
```
In lib/lzo/lzo1x_compress.c (ffffffff8170538c)
Location: include/asm-generic/unaligned.h:45
Inline: True
Inline callers:
  - lib/lzo/lzo1x_compress.c:lzo1x_1_do_compress
```
```
In lib/zstd/compress/fse_compress.c (0)
Location: include/asm-generic/unaligned.h:45
Inline: True
```
```
In lib/zstd/compress/huf_compress.c (0)
Location: include/asm-generic/unaligned.h:45
Inline: True
```
```
In lib/zstd/compress/zstd_compress.c (ffffffff8171c63b)
Location: include/asm-generic/unaligned.h:45
Inline: True
Inline callers:
  - lib/zstd/compress/zstd_compress.c:ZSTD_compressSequences
  - lib/zstd/compress/zstd_compress.c:ZSTD_compressSequences_internal
  - lib/zstd/compress/zstd_compress.c:ZSTD_compressEnd
  - lib/zstd/compress/zstd_compress.c:ZSTD_compressEnd
  - lib/zstd/compress/zstd_compress.c:ZSTD_writeSkippableFrame
  - lib/zstd/compress/zstd_compress.c:ZSTD_writeSkippableFrame
  - lib/zstd/compress/zstd_compress.c:ZSTD_writeFrameHeader
  - lib/zstd/compress/zstd_compress.c:ZSTD_writeFrameHeader
  - lib/zstd/compress/zstd_compress.c:ZSTD_writeFrameHeader
```
```
In lib/zstd/compress/zstd_compress_literals.c (ffffffff8171cd0e)
Location: include/asm-generic/unaligned.h:45
Inline: True
Inline callers:
  - lib/zstd/compress/zstd_compress_literals.c:ZSTD_compressLiterals
  - lib/zstd/compress/zstd_compress_literals.c:ZSTD_compressLiterals
  - lib/zstd/compress/zstd_compress_literals.c:ZSTD_compressRleLiteralsBlock
  - lib/zstd/compress/zstd_compress_literals.c:ZSTD_noCompressLiterals
```
```
In lib/zstd/compress/zstd_compress_sequences.c (0)
Location: include/asm-generic/unaligned.h:45
Inline: True
```
```
In lib/zstd/compress/zstd_compress_superblock.c (ffffffff8171faa2)
Location: include/asm-generic/unaligned.h:45
Inline: True
```
```
In lib/xz/xz_dec_bcj.c (ffffffff8175d68d)
Location: include/asm-generic/unaligned.h:45
Inline: True
Inline callers:
  - lib/xz/xz_dec_bcj.c:bcj_x86
```
```
In drivers/base/regmap/regmap.c (ffffffff819a6660)
Location: include/asm-generic/unaligned.h:45
Inline: True
Inline callers:
  - drivers/base/regmap/regmap.c:regmap_format_32_le
```
```
In drivers/usb/host/ehci-hcd.c (ffffffff81ad3a12)
Location: include/asm-generic/unaligned.h:45
Inline: True
Inline callers:
  - drivers/usb/host/ehci-hcd.c:ehci_hub_control
```
```
In drivers/usb/host/ohci-hcd.c (ffffffff81ae0521)
Location: include/asm-generic/unaligned.h:45
Inline: True
Inline callers:
  - drivers/usb/host/ohci-hcd.c:ohci_hub_control
  - drivers/usb/host/ohci-hcd.c:ohci_hub_control
```
```
In drivers/usb/host/xhci-hub.c (ffffffff81b00d21)
Location: include/asm-generic/unaligned.h:45
Inline: True
Inline callers:
  - drivers/usb/host/xhci-hub.c:xhci_hub_control
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
In crypto/aes_generic.c (ffffffff8171b959)
Location: include/asm-generic/unaligned.h:45
Inline: True
Inline callers:
  - crypto/aes_generic.c:crypto_aes_decrypt
  - crypto/aes_generic.c:crypto_aes_decrypt
  - crypto/aes_generic.c:crypto_aes_decrypt
  - crypto/aes_generic.c:crypto_aes_decrypt
  - crypto/aes_generic.c:crypto_aes_encrypt
  - crypto/aes_generic.c:crypto_aes_encrypt
  - crypto/aes_generic.c:crypto_aes_encrypt
  - crypto/aes_generic.c:crypto_aes_encrypt
```
```
In crypto/crc32c_generic.c (ffffffff8171c23a)
Location: include/asm-generic/unaligned.h:45
Inline: True
Inline callers:
  - crypto/crc32c_generic.c:chksum_digest
  - crypto/crc32c_generic.c:chksum_finup
  - crypto/crc32c_generic.c:chksum_final
```
```
In lib/crypto/chacha.c (ffffffff817dfe1a)
Location: include/asm-generic/unaligned.h:45
Inline: True
Inline callers:
  - lib/crypto/chacha.c:chacha_block_generic
```
```
In lib/crypto/aes.c (ffffffff817e0448)
Location: include/asm-generic/unaligned.h:45
Inline: True
Inline callers:
  - lib/crypto/aes.c:aes_decrypt
  - lib/crypto/aes.c:aes_decrypt
  - lib/crypto/aes.c:aes_decrypt
  - lib/crypto/aes.c:aes_decrypt
  - lib/crypto/aes.c:aes_encrypt
  - lib/crypto/aes.c:aes_encrypt
  - lib/crypto/aes.c:aes_encrypt
  - lib/crypto/aes.c:aes_encrypt
```
```
In lib/lzo/lzo1x_compress.c (ffffffff817f7fcc)
Location: include/asm-generic/unaligned.h:45
Inline: True
Inline callers:
  - lib/lzo/lzo1x_compress.c:lzo1x_1_do_compress
```
```
In lib/zstd/compress/fse_compress.c (0)
Location: include/asm-generic/unaligned.h:45
Inline: True
```
```
In lib/zstd/compress/huf_compress.c (0)
Location: include/asm-generic/unaligned.h:45
Inline: True
```
```
In lib/zstd/compress/zstd_compress.c (ffffffff81811eab)
Location: include/asm-generic/unaligned.h:45
Inline: True
Inline callers:
  - lib/zstd/compress/zstd_compress.c:ZSTD_compressSequences
  - lib/zstd/compress/zstd_compress.c:ZSTD_compressSequences_internal
  - lib/zstd/compress/zstd_compress.c:ZSTD_compressEnd
  - lib/zstd/compress/zstd_compress.c:ZSTD_compressEnd
  - lib/zstd/compress/zstd_compress.c:ZSTD_writeSkippableFrame
  - lib/zstd/compress/zstd_compress.c:ZSTD_writeSkippableFrame
  - lib/zstd/compress/zstd_compress.c:ZSTD_writeFrameHeader
  - lib/zstd/compress/zstd_compress.c:ZSTD_writeFrameHeader
  - lib/zstd/compress/zstd_compress.c:ZSTD_writeFrameHeader
```
```
In lib/zstd/compress/zstd_compress_literals.c (ffffffff8181261a)
Location: include/asm-generic/unaligned.h:45
Inline: True
Inline callers:
  - lib/zstd/compress/zstd_compress_literals.c:ZSTD_compressLiterals
  - lib/zstd/compress/zstd_compress_literals.c:ZSTD_compressLiterals
  - lib/zstd/compress/zstd_compress_literals.c:ZSTD_compressRleLiteralsBlock
  - lib/zstd/compress/zstd_compress_literals.c:ZSTD_noCompressLiterals
```
```
In lib/zstd/compress/zstd_compress_sequences.c (0)
Location: include/asm-generic/unaligned.h:45
Inline: True
```
```
In lib/zstd/compress/zstd_compress_superblock.c (ffffffff81815402)
Location: include/asm-generic/unaligned.h:45
Inline: True
```
```
In lib/xz/xz_dec_bcj.c (ffffffff8188abad)
Location: include/asm-generic/unaligned.h:45
Inline: True
Inline callers:
  - lib/xz/xz_dec_bcj.c:bcj_x86
```
```
In drivers/base/regmap/regmap.c (ffffffff81b18da0)
Location: include/asm-generic/unaligned.h:45
Inline: True
Inline callers:
  - drivers/base/regmap/regmap.c:regmap_format_32_le
```
```
In drivers/usb/host/ehci-hcd.c (ffffffff81c5e679)
Location: include/asm-generic/unaligned.h:45
Inline: True
Inline callers:
  - drivers/usb/host/ehci-hcd.c:ehci_hub_control
```
```
In drivers/usb/host/ohci-hcd.c (ffffffff81c6bc31)
Location: include/asm-generic/unaligned.h:45
Inline: True
Inline callers:
  - drivers/usb/host/ohci-hcd.c:ohci_hub_control
  - drivers/usb/host/ohci-hcd.c:ohci_hub_control
```
```
In drivers/usb/host/xhci-hub.c (ffffffff81c90134)
Location: include/asm-generic/unaligned.h:45
Inline: True
Inline callers:
  - drivers/usb/host/xhci-hub.c:xhci_hub_control
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
In crypto/sha3_generic.c (ffffffff81750426)
Location: include/asm-generic/unaligned.h:45
Inline: True
Inline callers:
  - crypto/sha3_generic.c:crypto_sha3_final
```
```
In crypto/aes_generic.c (ffffffff817570ec)
Location: include/asm-generic/unaligned.h:45
Inline: True
Inline callers:
  - crypto/aes_generic.c:crypto_aes_decrypt
  - crypto/aes_generic.c:crypto_aes_decrypt
  - crypto/aes_generic.c:crypto_aes_decrypt
  - crypto/aes_generic.c:crypto_aes_decrypt
  - crypto/aes_generic.c:crypto_aes_encrypt
  - crypto/aes_generic.c:crypto_aes_encrypt
  - crypto/aes_generic.c:crypto_aes_encrypt
  - crypto/aes_generic.c:crypto_aes_encrypt
```
```
In crypto/crc32c_generic.c (ffffffff817579da)
Location: include/asm-generic/unaligned.h:45
Inline: True
Inline callers:
  - crypto/crc32c_generic.c:chksum_digest
  - crypto/crc32c_generic.c:chksum_finup
  - crypto/crc32c_generic.c:chksum_final
```
```
In lib/crypto/chacha.c (ffffffff8181f59a)
Location: include/asm-generic/unaligned.h:45
Inline: True
Inline callers:
  - lib/crypto/chacha.c:chacha_block_generic
```
```
In lib/crypto/aes.c (ffffffff8181fbc0)
Location: include/asm-generic/unaligned.h:45
Inline: True
Inline callers:
  - lib/crypto/aes.c:aes_decrypt
  - lib/crypto/aes.c:aes_decrypt
  - lib/crypto/aes.c:aes_decrypt
  - lib/crypto/aes.c:aes_decrypt
  - lib/crypto/aes.c:aes_encrypt
  - lib/crypto/aes.c:aes_encrypt
  - lib/crypto/aes.c:aes_encrypt
  - lib/crypto/aes.c:aes_encrypt
```
```
In lib/lzo/lzo1x_compress.c (ffffffff818383bc)
Location: include/asm-generic/unaligned.h:45
Inline: True
Inline callers:
  - lib/lzo/lzo1x_compress.c:lzo1x_1_do_compress
```
```
In lib/zstd/compress/fse_compress.c (0)
Location: include/asm-generic/unaligned.h:45
Inline: True
```
```
In lib/zstd/compress/huf_compress.c (0)
Location: include/asm-generic/unaligned.h:45
Inline: True
```
```
In lib/zstd/compress/zstd_compress.c (ffffffff818529ab)
Location: include/asm-generic/unaligned.h:45
Inline: True
Inline callers:
  - lib/zstd/compress/zstd_compress.c:ZSTD_compressSequences
  - lib/zstd/compress/zstd_compress.c:ZSTD_compressSequences_internal
  - lib/zstd/compress/zstd_compress.c:ZSTD_compressEnd
  - lib/zstd/compress/zstd_compress.c:ZSTD_compressEnd
  - lib/zstd/compress/zstd_compress.c:ZSTD_writeSkippableFrame
  - lib/zstd/compress/zstd_compress.c:ZSTD_writeSkippableFrame
  - lib/zstd/compress/zstd_compress.c:ZSTD_writeFrameHeader
  - lib/zstd/compress/zstd_compress.c:ZSTD_writeFrameHeader
  - lib/zstd/compress/zstd_compress.c:ZSTD_writeFrameHeader
```
```
In lib/zstd/compress/zstd_compress_literals.c (ffffffff8185311a)
Location: include/asm-generic/unaligned.h:45
Inline: True
Inline callers:
  - lib/zstd/compress/zstd_compress_literals.c:ZSTD_compressLiterals
  - lib/zstd/compress/zstd_compress_literals.c:ZSTD_compressLiterals
  - lib/zstd/compress/zstd_compress_literals.c:ZSTD_compressRleLiteralsBlock
  - lib/zstd/compress/zstd_compress_literals.c:ZSTD_noCompressLiterals
```
```
In lib/zstd/compress/zstd_compress_sequences.c (0)
Location: include/asm-generic/unaligned.h:45
Inline: True
```
```
In lib/zstd/compress/zstd_compress_superblock.c (ffffffff818559fb)
Location: include/asm-generic/unaligned.h:45
Inline: True
```
```
In lib/xz/xz_dec_bcj.c (ffffffff818cd07e)
Location: include/asm-generic/unaligned.h:45
Inline: True
Inline callers:
  - lib/xz/xz_dec_bcj.c:bcj_x86
```
```
In drivers/base/regmap/regmap.c (ffffffff81b67b90)
Location: include/asm-generic/unaligned.h:45
Inline: True
Inline callers:
  - drivers/base/regmap/regmap.c:regmap_format_32_le
```
```
In drivers/usb/host/ehci-hcd.c (ffffffff81cc5ba7)
Location: include/asm-generic/unaligned.h:45
Inline: True
Inline callers:
  - drivers/usb/host/ehci-hcd.c:ehci_hub_control
```
```
In drivers/usb/host/ohci-hcd.c (ffffffff81cd3094)
Location: include/asm-generic/unaligned.h:45
Inline: True
Inline callers:
  - drivers/usb/host/ohci-hcd.c:ohci_hub_control
  - drivers/usb/host/ohci-hcd.c:ohci_hub_control
```
```
In drivers/usb/host/xhci-hub.c (ffffffff81cf6932)
Location: include/asm-generic/unaligned.h:45
Inline: True
Inline callers:
  - drivers/usb/host/xhci-hub.c:xhci_hub_control
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
In crypto/sha3_generic.c (ffffffff81792076)
Location: include/asm-generic/unaligned.h:45
Inline: True
Inline callers:
  - crypto/sha3_generic.c:crypto_sha3_final
```
```
In crypto/aes_generic.c (ffffffff817990ac)
Location: include/asm-generic/unaligned.h:45
Inline: True
Inline callers:
  - crypto/aes_generic.c:crypto_aes_decrypt
  - crypto/aes_generic.c:crypto_aes_decrypt
  - crypto/aes_generic.c:crypto_aes_decrypt
  - crypto/aes_generic.c:crypto_aes_decrypt
  - crypto/aes_generic.c:crypto_aes_encrypt
  - crypto/aes_generic.c:crypto_aes_encrypt
  - crypto/aes_generic.c:crypto_aes_encrypt
  - crypto/aes_generic.c:crypto_aes_encrypt
```
```
In crypto/crc32c_generic.c (ffffffff817998da)
Location: include/asm-generic/unaligned.h:45
Inline: True
Inline callers:
  - crypto/crc32c_generic.c:chksum_digest
  - crypto/crc32c_generic.c:chksum_finup
  - crypto/crc32c_generic.c:chksum_final
```
```
In lib/crypto/chacha.c (ffffffff8186551a)
Location: include/asm-generic/unaligned.h:45
Inline: True
Inline callers:
  - lib/crypto/chacha.c:chacha_block_generic
```
```
In lib/crypto/aes.c (ffffffff81865b40)
Location: include/asm-generic/unaligned.h:45
Inline: True
Inline callers:
  - lib/crypto/aes.c:aes_decrypt
  - lib/crypto/aes.c:aes_decrypt
  - lib/crypto/aes.c:aes_decrypt
  - lib/crypto/aes.c:aes_decrypt
  - lib/crypto/aes.c:aes_encrypt
  - lib/crypto/aes.c:aes_encrypt
  - lib/crypto/aes.c:aes_encrypt
  - lib/crypto/aes.c:aes_encrypt
```
```
In lib/lzo/lzo1x_compress.c (ffffffff81889f7c)
Location: include/asm-generic/unaligned.h:45
Inline: True
Inline callers:
  - lib/lzo/lzo1x_compress.c:lzo1x_1_do_compress
```
```
In lib/zstd/compress/fse_compress.c (0)
Location: include/asm-generic/unaligned.h:45
Inline: True
```
```
In lib/zstd/compress/huf_compress.c (0)
Location: include/asm-generic/unaligned.h:45
Inline: True
```
```
In lib/zstd/compress/zstd_compress.c (ffffffff818a456b)
Location: include/asm-generic/unaligned.h:45
Inline: True
Inline callers:
  - lib/zstd/compress/zstd_compress.c:ZSTD_compressSequences
  - lib/zstd/compress/zstd_compress.c:ZSTD_compressSequences_internal
  - lib/zstd/compress/zstd_compress.c:ZSTD_compressEnd
  - lib/zstd/compress/zstd_compress.c:ZSTD_compressEnd
  - lib/zstd/compress/zstd_compress.c:ZSTD_writeSkippableFrame
  - lib/zstd/compress/zstd_compress.c:ZSTD_writeSkippableFrame
  - lib/zstd/compress/zstd_compress.c:ZSTD_writeFrameHeader
  - lib/zstd/compress/zstd_compress.c:ZSTD_writeFrameHeader
  - lib/zstd/compress/zstd_compress.c:ZSTD_writeFrameHeader
```
```
In lib/zstd/compress/zstd_compress_literals.c (ffffffff818a4cda)
Location: include/asm-generic/unaligned.h:45
Inline: True
Inline callers:
  - lib/zstd/compress/zstd_compress_literals.c:ZSTD_compressLiterals
  - lib/zstd/compress/zstd_compress_literals.c:ZSTD_compressLiterals
  - lib/zstd/compress/zstd_compress_literals.c:ZSTD_compressRleLiteralsBlock
  - lib/zstd/compress/zstd_compress_literals.c:ZSTD_noCompressLiterals
```
```
In lib/zstd/compress/zstd_compress_sequences.c (0)
Location: include/asm-generic/unaligned.h:45
Inline: True
```
```
In lib/zstd/compress/zstd_compress_superblock.c (ffffffff818a75bb)
Location: include/asm-generic/unaligned.h:45
Inline: True
```
```
In lib/xz/xz_dec_bcj.c (ffffffff8191ec6e)
Location: include/asm-generic/unaligned.h:45
Inline: True
Inline callers:
  - lib/xz/xz_dec_bcj.c:bcj_x86
```
```
In drivers/base/regmap/regmap.c (ffffffff81bbb960)
Location: include/asm-generic/unaligned.h:45
Inline: True
Inline callers:
  - drivers/base/regmap/regmap.c:regmap_format_32_le
```
```
In drivers/usb/host/ehci-hcd.c (ffffffff81d7aaa4)
Location: include/asm-generic/unaligned.h:45
Inline: True
Inline callers:
  - drivers/usb/host/ehci-hcd.c:ehci_hub_control
```
```
In drivers/usb/host/ohci-hcd.c (ffffffff81d88054)
Location: include/asm-generic/unaligned.h:45
Inline: True
Inline callers:
  - drivers/usb/host/ohci-hcd.c:ohci_hub_control
  - drivers/usb/host/ohci-hcd.c:ohci_hub_control
```
```
In drivers/usb/host/xhci-hub.c (ffffffff81dac257)
Location: include/asm-generic/unaligned.h:45
Inline: True
Inline callers:
  - drivers/usb/host/xhci-hub.c:xhci_hub_control
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
In crypto/aes_generic.c (ffff8000105cf058)
Location: include/linux/unaligned/access_ok.h:43
Inline: True
Inline callers:
  - crypto/aes_generic.c:crypto_aes_decrypt
  - crypto/aes_generic.c:crypto_aes_decrypt
  - crypto/aes_generic.c:crypto_aes_decrypt
  - crypto/aes_generic.c:crypto_aes_decrypt
  - crypto/aes_generic.c:crypto_aes_encrypt
  - crypto/aes_generic.c:crypto_aes_encrypt
  - crypto/aes_generic.c:crypto_aes_encrypt
  - crypto/aes_generic.c:crypto_aes_encrypt
```
```
In crypto/crc32c_generic.c (ffff8000105cf82c)
Location: include/linux/unaligned/access_ok.h:43
Inline: True
Inline callers:
  - crypto/crc32c_generic.c:chksum_digest
  - crypto/crc32c_generic.c:chksum_finup
  - crypto/crc32c_generic.c:chksum_final
```
```
In lib/random32.c (ffff80001062a0b0)
Location: include/linux/unaligned/access_ok.h:43
Inline: True
Inline callers:
  - lib/random32.c:prandom_bytes_state
```
```
In lib/crypto/aes.c (ffff80001063b9e4)
Location: include/linux/unaligned/access_ok.h:43
Inline: True
Inline callers:
  - lib/crypto/aes.c:aes_decrypt
  - lib/crypto/aes.c:aes_decrypt
  - lib/crypto/aes.c:aes_decrypt
  - lib/crypto/aes.c:aes_decrypt
  - lib/crypto/aes.c:aes_encrypt
  - lib/crypto/aes.c:aes_encrypt
  - lib/crypto/aes.c:aes_encrypt
  - lib/crypto/aes.c:aes_encrypt
```
```
In lib/lzo/lzo1x_compress.c (ffff80001064abb0)
Location: include/linux/unaligned/access_ok.h:43
Inline: True
Inline callers:
  - lib/lzo/lzo1x_compress.c:lzo1x_1_do_compress
  - lib/lzo/lzo1x_compress.c:lzo1x_1_do_compress
```
```
In lib/lzo/lzo1x_decompress_safe.c (ffff80001064b448)
Location: include/linux/unaligned/access_ok.h:43
Inline: True
Inline callers:
  - lib/lzo/lzo1x_decompress_safe.c:lzo1x_decompress_safe
  - lib/lzo/lzo1x_decompress_safe.c:lzo1x_decompress_safe
```
```
In lib/lz4/lz4_decompress.c (ffff80001064d60c)
Location: include/linux/unaligned/access_ok.h:43
Inline: True
Inline callers:
  - lib/lz4/lz4_decompress.c:LZ4_decompress_fast_continue
  - lib/lz4/lz4_decompress.c:LZ4_decompress_safe_continue
  - lib/lz4/lz4_decompress.c:LZ4_decompress_fast_extDict
  - lib/lz4/lz4_decompress.c:LZ4_decompress_safe_forceExtDict
  - lib/lz4/lz4_decompress.c:LZ4_decompress_safe_withSmallPrefix
  - lib/lz4/lz4_decompress.c:LZ4_decompress_safe_withPrefix64k
  - lib/lz4/lz4_decompress.c:LZ4_decompress_fast
  - lib/lz4/lz4_decompress.c:LZ4_decompress_safe
```
```
In lib/xz/xz_dec_bcj.c (ffff80001065de44)
Location: include/linux/unaligned/access_ok.h:43
Inline: True
Inline callers:
  - lib/xz/xz_dec_bcj.c:bcj_apply
```
```
In drivers/usb/host/ehci-hcd.c (ffff800010a58718)
Location: include/linux/unaligned/access_ok.h:43
Inline: True
Inline callers:
  - drivers/usb/host/ehci-hcd.c:ehci_hub_control
```
```
In drivers/usb/host/ohci-hcd.c (ffff800010a6423c)
Location: include/linux/unaligned/access_ok.h:43
Inline: True
Inline callers:
  - drivers/usb/host/ohci-hcd.c:ohci_hub_control
  - drivers/usb/host/ohci-hcd.c:ohci_hub_control
```
```
In drivers/usb/host/xhci-hub.c (ffff800010a84a58)
Location: include/linux/unaligned/access_ok.h:43
Inline: True
Inline callers:
  - drivers/usb/host/xhci-hub.c:xhci_hub_control
  - drivers/usb/host/xhci-hub.c:xhci_hub_control
  - drivers/usb/host/xhci-hub.c:xhci_hub_control
  - drivers/usb/host/xhci-hub.c:xhci_hub_control
  - drivers/usb/host/xhci-hub.c:xhci_hub_control
```
```
In drivers/firmware/arm_scmi/base.c (ffff800010b57554)
Location: include/linux/unaligned/access_ok.h:43
Inline: True
Inline callers:
  - drivers/firmware/arm_scmi/base.c:scmi_base_protocol_init
```
```
In drivers/firmware/arm_scmi/clock.c (ffff800010b57a00)
Location: include/linux/unaligned/access_ok.h:43
Inline: True
Inline callers:
  - drivers/firmware/arm_scmi/clock.c:scmi_clock_protocol_init
  - drivers/firmware/arm_scmi/clock.c:scmi_clock_rate_get
```
```
In drivers/firmware/arm_scmi/perf.c (ffff800010b5872c)
Location: include/linux/unaligned/access_ok.h:43
Inline: True
Inline callers:
  - drivers/firmware/arm_scmi/perf.c:scmi_perf_protocol_init
  - drivers/firmware/arm_scmi/perf.c:scmi_perf_level_get
  - drivers/firmware/arm_scmi/perf.c:scmi_perf_limits_get
```
```
In drivers/firmware/arm_scmi/power.c (ffff800010b59058)
Location: include/linux/unaligned/access_ok.h:43
Inline: True
Inline callers:
  - drivers/firmware/arm_scmi/power.c:scmi_power_protocol_init
  - drivers/firmware/arm_scmi/power.c:scmi_power_state_get
```
```
In drivers/firmware/arm_scmi/reset.c (ffff800010b59328)
Location: include/linux/unaligned/access_ok.h:43
Inline: True
Inline callers:
  - drivers/firmware/arm_scmi/reset.c:scmi_reset_protocol_init
```
```
In drivers/firmware/arm_scmi/sensors.c (ffff800010b599d0)
Location: include/linux/unaligned/access_ok.h:43
Inline: True
Inline callers:
  - drivers/firmware/arm_scmi/sensors.c:scmi_sensors_protocol_init
```
```
In net/core/netpoll.c (ffff800010c11768)
Location: include/linux/unaligned/access_ok.h:43
Inline: True
Inline callers:
  - net/core/netpoll.c:netpoll_send_udp
  - net/core/netpoll.c:netpoll_send_udp
```
```
In lib/chacha.c (ffff800010d83f08)
Location: include/linux/unaligned/access_ok.h:43
Inline: True
Inline callers:
  - lib/chacha.c:chacha_block
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
In crypto/aes_generic.c (c077ced0)
Location: include/linux/unaligned/le_struct.h:27
Inline: True
Inline callers:
  - crypto/aes_generic.c:crypto_aes_decrypt
  - crypto/aes_generic.c:crypto_aes_decrypt
  - crypto/aes_generic.c:crypto_aes_decrypt
  - crypto/aes_generic.c:crypto_aes_decrypt
  - crypto/aes_generic.c:crypto_aes_encrypt
  - crypto/aes_generic.c:crypto_aes_encrypt
  - crypto/aes_generic.c:crypto_aes_encrypt
  - crypto/aes_generic.c:crypto_aes_encrypt
```
```
In crypto/crc32c_generic.c (c077d520)
Location: include/linux/unaligned/le_struct.h:27
Inline: True
Inline callers:
  - crypto/crc32c_generic.c:chksum_digest
  - crypto/crc32c_generic.c:chksum_finup
  - crypto/crc32c_generic.c:chksum_final
```
```
In lib/random32.c (c07d13d4)
Location: include/linux/unaligned/le_struct.h:27
Inline: True
Inline callers:
  - lib/random32.c:prandom_bytes_state
```
```
In lib/crypto/aes.c (c07e1db0)
Location: include/linux/unaligned/le_struct.h:27
Inline: True
Inline callers:
  - lib/crypto/aes.c:aes_decrypt
  - lib/crypto/aes.c:aes_decrypt
  - lib/crypto/aes.c:aes_decrypt
  - lib/crypto/aes.c:aes_decrypt
  - lib/crypto/aes.c:aes_encrypt
  - lib/crypto/aes.c:aes_encrypt
  - lib/crypto/aes.c:aes_encrypt
  - lib/crypto/aes.c:aes_encrypt
```
```
In lib/lzo/lzo1x_compress.c (c07f6868)
Location: include/linux/unaligned/le_struct.h:27
Inline: True
Inline callers:
  - lib/lzo/lzo1x_compress.c:lzogeneric1x_1_compress
  - lib/lzo/lzo1x_compress.c:lzogeneric1x_1_compress
  - lib/lzo/lzo1x_compress.c:lzogeneric1x_1_compress
  - lib/lzo/lzo1x_compress.c:lzogeneric1x_1_compress
  - lib/lzo/lzo1x_compress.c:lzo1x_1_do_compress
  - lib/lzo/lzo1x_compress.c:lzo1x_1_do_compress
  - lib/lzo/lzo1x_compress.c:lzo1x_1_do_compress
  - lib/lzo/lzo1x_compress.c:lzo1x_1_do_compress
  - lib/lzo/lzo1x_compress.c:lzo1x_1_do_compress
  - lib/lzo/lzo1x_compress.c:lzo1x_1_do_compress
  - lib/lzo/lzo1x_compress.c:lzo1x_1_do_compress
  - lib/lzo/lzo1x_compress.c:lzo1x_1_do_compress
  - lib/lzo/lzo1x_compress.c:lzo1x_1_do_compress
  - lib/lzo/lzo1x_compress.c:lzo1x_1_do_compress
```
```
In lib/lzo/lzo1x_decompress_safe.c (c07f69fc)
Location: include/linux/unaligned/le_struct.h:27
Inline: True
Inline callers:
  - lib/lzo/lzo1x_decompress_safe.c:lzo1x_decompress_safe
  - lib/lzo/lzo1x_decompress_safe.c:lzo1x_decompress_safe
  - lib/lzo/lzo1x_decompress_safe.c:lzo1x_decompress_safe
  - lib/lzo/lzo1x_decompress_safe.c:lzo1x_decompress_safe
  - lib/lzo/lzo1x_decompress_safe.c:lzo1x_decompress_safe
  - lib/lzo/lzo1x_decompress_safe.c:lzo1x_decompress_safe
  - lib/lzo/lzo1x_decompress_safe.c:lzo1x_decompress_safe
  - lib/lzo/lzo1x_decompress_safe.c:lzo1x_decompress_safe
  - lib/lzo/lzo1x_decompress_safe.c:lzo1x_decompress_safe
  - lib/lzo/lzo1x_decompress_safe.c:lzo1x_decompress_safe
```
```
In lib/lz4/lz4_decompress.c (c07f915c)
Location: include/linux/unaligned/le_struct.h:27
Inline: True
Inline callers:
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
  - lib/lz4/lz4_decompress.c:LZ4_decompress_fast_extDict
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
  - lib/lz4/lz4_decompress.c:LZ4_decompress_safe_forceExtDict
  - lib/lz4/lz4_decompress.c:LZ4_decompress_safe_withSmallPrefix
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
  - lib/lz4/lz4_decompress.c:LZ4_decompress_safe_withPrefix64k
  - lib/lz4/lz4_decompress.c:LZ4_decompress_fast
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
  - lib/lz4/lz4_decompress.c:LZ4_decompress_safe
```
```
In lib/xz/xz_dec_bcj.c (c0807580)
Location: include/linux/unaligned/le_struct.h:27
Inline: True
Inline callers:
  - lib/xz/xz_dec_bcj.c:bcj_apply
```
```
In drivers/usb/core/hcd.c (c0af3a0c)
Location: include/linux/unaligned/le_struct.h:27
Inline: True
```
```
In drivers/usb/host/ehci-hcd.c (c0b2c6a8)
Location: include/linux/unaligned/le_struct.h:27
Inline: True
Inline callers:
  - drivers/usb/host/ehci-hcd.c:ehci_hub_control
```
```
In drivers/usb/host/ohci-hcd.c (c0b31af4)
Location: include/linux/unaligned/le_struct.h:27
Inline: True
Inline callers:
  - drivers/usb/host/ohci-hcd.c:ohci_hub_control
  - drivers/usb/host/ohci-hcd.c:ohci_hub_control
```
```
In drivers/usb/host/xhci-hub.c (c0b57de0)
Location: include/linux/unaligned/le_struct.h:27
Inline: True
Inline callers:
  - drivers/usb/host/xhci-hub.c:xhci_hub_control
  - drivers/usb/host/xhci-hub.c:xhci_hub_control
  - drivers/usb/host/xhci-hub.c:xhci_hub_control
  - drivers/usb/host/xhci-hub.c:xhci_hub_control
  - drivers/usb/host/xhci-hub.c:xhci_hub_control
```
```
In drivers/usb/musb/musb_virthub.c (c0b69ad4)
Location: include/linux/unaligned/le_struct.h:27
Inline: True
Inline callers:
  - drivers/usb/musb/musb_virthub.c:musb_hub_control
```
```
In drivers/firmware/arm_scmi/base.c (c0c388a4)
Location: include/linux/unaligned/le_struct.h:27
Inline: True
Inline callers:
  - drivers/firmware/arm_scmi/base.c:scmi_base_protocol_init
```
```
In drivers/firmware/arm_scmi/clock.c (c0c38e98)
Location: include/linux/unaligned/le_struct.h:27
Inline: True
Inline callers:
  - drivers/firmware/arm_scmi/clock.c:scmi_clock_protocol_init
  - drivers/firmware/arm_scmi/clock.c:scmi_clock_rate_get
```
```
In drivers/firmware/arm_scmi/perf.c (c0c39cbc)
Location: include/linux/unaligned/le_struct.h:27
Inline: True
Inline callers:
  - drivers/firmware/arm_scmi/perf.c:scmi_perf_protocol_init
  - drivers/firmware/arm_scmi/perf.c:scmi_perf_level_get
  - drivers/firmware/arm_scmi/perf.c:scmi_perf_limits_get
```
```
In drivers/firmware/arm_scmi/power.c (c0c3a31c)
Location: include/linux/unaligned/le_struct.h:27
Inline: True
Inline callers:
  - drivers/firmware/arm_scmi/power.c:scmi_power_protocol_init
  - drivers/firmware/arm_scmi/power.c:scmi_power_state_get
```
```
In drivers/firmware/arm_scmi/reset.c (c0c3a5f8)
Location: include/linux/unaligned/le_struct.h:27
Inline: True
Inline callers:
  - drivers/firmware/arm_scmi/reset.c:scmi_reset_protocol_init
```
```
In drivers/firmware/arm_scmi/sensors.c (c0c3ac0c)
Location: include/linux/unaligned/le_struct.h:27
Inline: True
Inline callers:
  - drivers/firmware/arm_scmi/sensors.c:scmi_sensors_protocol_init
```
```
In net/core/netpoll.c (c0d294cc)
Location: include/linux/unaligned/le_struct.h:27
Inline: True
Inline callers:
  - net/core/netpoll.c:netpoll_send_udp
  - net/core/netpoll.c:netpoll_send_udp
```
```
In lib/chacha.c (c0e7f3b8)
Location: include/linux/unaligned/le_struct.h:27
Inline: True
Inline callers:
  - lib/chacha.c:chacha_block
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
In crypto/aes_generic.c (c00000000075aeb8)
Location: include/linux/unaligned/access_ok.h:43
Inline: True
Inline callers:
  - crypto/aes_generic.c:crypto_aes_decrypt
  - crypto/aes_generic.c:crypto_aes_decrypt
  - crypto/aes_generic.c:crypto_aes_decrypt
  - crypto/aes_generic.c:crypto_aes_decrypt
  - crypto/aes_generic.c:crypto_aes_encrypt
  - crypto/aes_generic.c:crypto_aes_encrypt
  - crypto/aes_generic.c:crypto_aes_encrypt
  - crypto/aes_generic.c:crypto_aes_encrypt
```
```
In crypto/crc32c_generic.c (c00000000075b844)
Location: include/linux/unaligned/access_ok.h:43
Inline: True
Inline callers:
  - crypto/crc32c_generic.c:chksum_digest
  - crypto/crc32c_generic.c:chksum_finup
  - crypto/crc32c_generic.c:chksum_final
```
```
In lib/random32.c (c0000000007cbf68)
Location: include/linux/unaligned/access_ok.h:43
Inline: True
Inline callers:
  - lib/random32.c:prandom_bytes_state
```
```
In lib/crypto/aes.c (c0000000007e2f34)
Location: include/linux/unaligned/access_ok.h:43
Inline: True
Inline callers:
  - lib/crypto/aes.c:aes_decrypt
  - lib/crypto/aes.c:aes_decrypt
  - lib/crypto/aes.c:aes_decrypt
  - lib/crypto/aes.c:aes_decrypt
  - lib/crypto/aes.c:aes_encrypt
  - lib/crypto/aes.c:aes_encrypt
  - lib/crypto/aes.c:aes_encrypt
  - lib/crypto/aes.c:aes_encrypt
```
```
In lib/lzo/lzo1x_compress.c (c0000000007f9134)
Location: include/linux/unaligned/access_ok.h:43
Inline: True
Inline callers:
  - lib/lzo/lzo1x_compress.c:lzogeneric1x_1_compress
  - lib/lzo/lzo1x_compress.c:lzogeneric1x_1_compress
  - lib/lzo/lzo1x_compress.c:lzogeneric1x_1_compress
  - lib/lzo/lzo1x_compress.c:lzogeneric1x_1_compress
  - lib/lzo/lzo1x_compress.c:lzo1x_1_do_compress
  - lib/lzo/lzo1x_compress.c:lzo1x_1_do_compress
  - lib/lzo/lzo1x_compress.c:lzo1x_1_do_compress
  - lib/lzo/lzo1x_compress.c:lzo1x_1_do_compress
  - lib/lzo/lzo1x_compress.c:lzo1x_1_do_compress
  - lib/lzo/lzo1x_compress.c:lzo1x_1_do_compress
  - lib/lzo/lzo1x_compress.c:lzo1x_1_do_compress
  - lib/lzo/lzo1x_compress.c:lzo1x_1_do_compress
  - lib/lzo/lzo1x_compress.c:lzo1x_1_do_compress
  - lib/lzo/lzo1x_compress.c:lzo1x_1_do_compress
```
```
In lib/lzo/lzo1x_decompress_safe.c (c0000000007f9344)
Location: include/linux/unaligned/access_ok.h:43
Inline: True
Inline callers:
  - lib/lzo/lzo1x_decompress_safe.c:lzo1x_decompress_safe
  - lib/lzo/lzo1x_decompress_safe.c:lzo1x_decompress_safe
  - lib/lzo/lzo1x_decompress_safe.c:lzo1x_decompress_safe
  - lib/lzo/lzo1x_decompress_safe.c:lzo1x_decompress_safe
  - lib/lzo/lzo1x_decompress_safe.c:lzo1x_decompress_safe
  - lib/lzo/lzo1x_decompress_safe.c:lzo1x_decompress_safe
  - lib/lzo/lzo1x_decompress_safe.c:lzo1x_decompress_safe
  - lib/lzo/lzo1x_decompress_safe.c:lzo1x_decompress_safe
  - lib/lzo/lzo1x_decompress_safe.c:lzo1x_decompress_safe
  - lib/lzo/lzo1x_decompress_safe.c:lzo1x_decompress_safe
```
```
In lib/lz4/lz4_decompress.c (c0000000007fb93c)
Location: include/linux/unaligned/access_ok.h:43
Inline: True
Inline callers:
  - lib/lz4/lz4_decompress.c:LZ4_decompress_fast_continue
  - lib/lz4/lz4_decompress.c:LZ4_decompress_safe_continue
  - lib/lz4/lz4_decompress.c:LZ4_decompress_fast_extDict
  - lib/lz4/lz4_decompress.c:LZ4_decompress_safe_forceExtDict
  - lib/lz4/lz4_decompress.c:LZ4_decompress_safe_withSmallPrefix
  - lib/lz4/lz4_decompress.c:LZ4_decompress_safe_withPrefix64k
  - lib/lz4/lz4_decompress.c:LZ4_decompress_fast
  - lib/lz4/lz4_decompress.c:LZ4_decompress_safe
```
```
In lib/xz/xz_dec_bcj.c (c00000000081008c)
Location: include/linux/unaligned/access_ok.h:43
Inline: True
Inline callers:
  - lib/xz/xz_dec_bcj.c:bcj_apply
```
```
In drivers/usb/host/ehci-hcd.c (c000000000b2a63c)
Location: include/linux/unaligned/access_ok.h:43
Inline: True
Inline callers:
  - drivers/usb/host/ehci-hcd.c:ehci_hub_control
```
```
In drivers/usb/host/ohci-hcd.c (c000000000b3304c)
Location: include/linux/unaligned/access_ok.h:43
Inline: True
Inline callers:
  - drivers/usb/host/ohci-hcd.c:ohci_hub_control
  - drivers/usb/host/ohci-hcd.c:ohci_hub_control
```
```
In drivers/usb/host/xhci-hub.c (c000000000b5e738)
Location: include/linux/unaligned/access_ok.h:43
Inline: True
Inline callers:
  - drivers/usb/host/xhci-hub.c:xhci_hub_control
  - drivers/usb/host/xhci-hub.c:xhci_hub_control
  - drivers/usb/host/xhci-hub.c:xhci_hub_control
  - drivers/usb/host/xhci-hub.c:xhci_hub_control
  - drivers/usb/host/xhci-hub.c:xhci_hub_control
```
```
In net/core/netpoll.c (c000000000cfe4d4)
Location: include/linux/unaligned/access_ok.h:43
Inline: True
Inline callers:
  - net/core/netpoll.c:netpoll_send_udp
  - net/core/netpoll.c:netpoll_send_udp
```
```
In lib/chacha.c (c000000000ec2e60)
Location: include/linux/unaligned/access_ok.h:43
Inline: True
Inline callers:
  - lib/chacha.c:chacha_block
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
In crypto/aes_generic.c (ffffffe000413fa8)
Location: include/linux/unaligned/le_struct.h:27
Inline: True
Inline callers:
  - crypto/aes_generic.c:crypto_aes_decrypt
  - crypto/aes_generic.c:crypto_aes_decrypt
  - crypto/aes_generic.c:crypto_aes_decrypt
  - crypto/aes_generic.c:crypto_aes_decrypt
  - crypto/aes_generic.c:crypto_aes_encrypt
  - crypto/aes_generic.c:crypto_aes_encrypt
  - crypto/aes_generic.c:crypto_aes_encrypt
  - crypto/aes_generic.c:crypto_aes_encrypt
```
```
In crypto/crc32c_generic.c (ffffffe00041475e)
Location: include/linux/unaligned/le_struct.h:27
Inline: True
Inline callers:
  - crypto/crc32c_generic.c:chksum_digest
  - crypto/crc32c_generic.c:chksum_finup
  - crypto/crc32c_generic.c:chksum_final
```
```
In lib/random32.c (ffffffe00045aba0)
Location: include/linux/unaligned/le_struct.h:27
Inline: True
Inline callers:
  - lib/random32.c:prandom_bytes_state
```
```
In lib/crypto/aes.c (ffffffe000468742)
Location: include/linux/unaligned/le_struct.h:27
Inline: True
Inline callers:
  - lib/crypto/aes.c:aes_decrypt
  - lib/crypto/aes.c:aes_decrypt
  - lib/crypto/aes.c:aes_decrypt
  - lib/crypto/aes.c:aes_decrypt
  - lib/crypto/aes.c:aes_encrypt
  - lib/crypto/aes.c:aes_encrypt
  - lib/crypto/aes.c:aes_encrypt
  - lib/crypto/aes.c:aes_encrypt
```
```
In lib/lzo/lzo1x_compress.c (ffffffe0004771f6)
Location: include/linux/unaligned/le_struct.h:27
Inline: True
Inline callers:
  - lib/lzo/lzo1x_compress.c:lzogeneric1x_1_compress
  - lib/lzo/lzo1x_compress.c:lzogeneric1x_1_compress
  - lib/lzo/lzo1x_compress.c:lzogeneric1x_1_compress
  - lib/lzo/lzo1x_compress.c:lzogeneric1x_1_compress
  - lib/lzo/lzo1x_compress.c:lzo1x_1_do_compress
  - lib/lzo/lzo1x_compress.c:lzo1x_1_do_compress
  - lib/lzo/lzo1x_compress.c:lzo1x_1_do_compress
  - lib/lzo/lzo1x_compress.c:lzo1x_1_do_compress
  - lib/lzo/lzo1x_compress.c:lzo1x_1_do_compress
  - lib/lzo/lzo1x_compress.c:lzo1x_1_do_compress
  - lib/lzo/lzo1x_compress.c:lzo1x_1_do_compress
  - lib/lzo/lzo1x_compress.c:lzo1x_1_do_compress
  - lib/lzo/lzo1x_compress.c:lzo1x_1_do_compress
  - lib/lzo/lzo1x_compress.c:lzo1x_1_do_compress
```
```
In lib/lz4/lz4_decompress.c (ffffffe000479b84)
Location: include/linux/unaligned/le_struct.h:27
Inline: True
Inline callers:
  - lib/lz4/lz4_decompress.c:LZ4_decompress_fast_continue
  - lib/lz4/lz4_decompress.c:LZ4_decompress_safe_continue
  - lib/lz4/lz4_decompress.c:LZ4_decompress_fast_extDict
  - lib/lz4/lz4_decompress.c:LZ4_decompress_safe_forceExtDict
  - lib/lz4/lz4_decompress.c:LZ4_decompress_safe_withSmallPrefix
  - lib/lz4/lz4_decompress.c:LZ4_decompress_safe_withPrefix64k
  - lib/lz4/lz4_decompress.c:LZ4_decompress_fast
  - lib/lz4/lz4_decompress.c:LZ4_decompress_safe
```
```
In lib/xz/xz_dec_bcj.c (ffffffe00048b868)
Location: include/linux/unaligned/le_struct.h:27
Inline: True
Inline callers:
  - lib/xz/xz_dec_bcj.c:bcj_apply
```
```
In drivers/usb/host/ehci-hcd.c (ffffffe000677dfe)
Location: include/linux/unaligned/le_struct.h:27
Inline: True
Inline callers:
  - drivers/usb/host/ehci-hcd.c:ehci_hub_control
```
```
In drivers/usb/host/ohci-hcd.c (ffffffe00067a6ee)
Location: include/linux/unaligned/le_struct.h:27
Inline: True
Inline callers:
  - drivers/usb/host/ohci-hcd.c:ohci_hub_control
  - drivers/usb/host/ohci-hcd.c:ohci_hub_control
```
```
In drivers/usb/host/xhci-hub.c (ffffffe00069a8a8)
Location: include/linux/unaligned/le_struct.h:27
Inline: True
Inline callers:
  - drivers/usb/host/xhci-hub.c:xhci_hub_control
  - drivers/usb/host/xhci-hub.c:xhci_hub_control
  - drivers/usb/host/xhci-hub.c:xhci_hub_control
  - drivers/usb/host/xhci-hub.c:xhci_hub_control
  - drivers/usb/host/xhci-hub.c:xhci_hub_control
```
```
In net/core/netpoll.c (ffffffe00078d970)
Location: include/linux/unaligned/le_struct.h:27
Inline: True
Inline callers:
  - net/core/netpoll.c:netpoll_send_udp
  - net/core/netpoll.c:netpoll_send_udp
```
```
In lib/chacha.c (ffffffe0008ae616)
Location: include/linux/unaligned/le_struct.h:27
Inline: True
Inline callers:
  - lib/chacha.c:chacha_block
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
In crypto/aes_generic.c (ffffffff814cb167)
Location: include/linux/unaligned/access_ok.h:43
Inline: True
Inline callers:
  - crypto/aes_generic.c:crypto_aes_decrypt
  - crypto/aes_generic.c:crypto_aes_decrypt
  - crypto/aes_generic.c:crypto_aes_decrypt
  - crypto/aes_generic.c:crypto_aes_decrypt
  - crypto/aes_generic.c:crypto_aes_encrypt
  - crypto/aes_generic.c:crypto_aes_encrypt
  - crypto/aes_generic.c:crypto_aes_encrypt
  - crypto/aes_generic.c:crypto_aes_encrypt
```
```
In crypto/crc32c_generic.c (ffffffff814cb7ba)
Location: include/linux/unaligned/access_ok.h:43
Inline: True
Inline callers:
  - crypto/crc32c_generic.c:chksum_digest
  - crypto/crc32c_generic.c:chksum_finup
  - crypto/crc32c_generic.c:chksum_final
```
```
In lib/random32.c (ffffffff81519163)
Location: include/linux/unaligned/access_ok.h:43
Inline: True
Inline callers:
  - lib/random32.c:prandom_bytes_state
```
```
In lib/crypto/aes.c (ffffffff81527c0b)
Location: include/linux/unaligned/access_ok.h:43
Inline: True
Inline callers:
  - lib/crypto/aes.c:aes_decrypt
  - lib/crypto/aes.c:aes_decrypt
  - lib/crypto/aes.c:aes_decrypt
  - lib/crypto/aes.c:aes_decrypt
  - lib/crypto/aes.c:aes_encrypt
  - lib/crypto/aes.c:aes_encrypt
  - lib/crypto/aes.c:aes_encrypt
  - lib/crypto/aes.c:aes_encrypt
```
```
In lib/lzo/lzo1x_compress.c (ffffffff81536a82)
Location: include/linux/unaligned/access_ok.h:43
Inline: True
Inline callers:
  - lib/lzo/lzo1x_compress.c:lzo1x_1_do_compress
  - lib/lzo/lzo1x_compress.c:lzo1x_1_do_compress
```
```
In lib/lzo/lzo1x_decompress_safe.c (ffffffff8153737b)
Location: include/linux/unaligned/access_ok.h:43
Inline: True
Inline callers:
  - lib/lzo/lzo1x_decompress_safe.c:lzo1x_decompress_safe
  - lib/lzo/lzo1x_decompress_safe.c:lzo1x_decompress_safe
```
```
In lib/lz4/lz4_decompress.c (ffffffff81538fad)
Location: include/linux/unaligned/access_ok.h:43
Inline: True
Inline callers:
  - lib/lz4/lz4_decompress.c:LZ4_decompress_fast_continue
  - lib/lz4/lz4_decompress.c:LZ4_decompress_safe_continue
  - lib/lz4/lz4_decompress.c:LZ4_decompress_fast_extDict
  - lib/lz4/lz4_decompress.c:LZ4_decompress_safe_forceExtDict
  - lib/lz4/lz4_decompress.c:LZ4_decompress_safe_withSmallPrefix
  - lib/lz4/lz4_decompress.c:LZ4_decompress_safe_withPrefix64k
  - lib/lz4/lz4_decompress.c:LZ4_decompress_fast
  - lib/lz4/lz4_decompress.c:LZ4_decompress_safe
```
```
In lib/xz/xz_dec_bcj.c (ffffffff8154a6df)
Location: include/linux/unaligned/access_ok.h:43
Inline: True
Inline callers:
  - lib/xz/xz_dec_bcj.c:bcj_apply
```
```
In drivers/usb/host/ehci-hcd.c (ffffffff817da0b1)
Location: include/linux/unaligned/access_ok.h:43
Inline: True
Inline callers:
  - drivers/usb/host/ehci-hcd.c:ehci_hub_control
```
```
In drivers/usb/host/ohci-hcd.c (ffffffff817dd896)
Location: include/linux/unaligned/access_ok.h:43
Inline: True
Inline callers:
  - drivers/usb/host/ohci-hcd.c:ohci_hub_control
  - drivers/usb/host/ohci-hcd.c:ohci_hub_control
```
```
In drivers/usb/host/xhci-hub.c (ffffffff817fe1dd)
Location: include/linux/unaligned/access_ok.h:43
Inline: True
Inline callers:
  - drivers/usb/host/xhci-hub.c:xhci_hub_control
  - drivers/usb/host/xhci-hub.c:xhci_hub_control
  - drivers/usb/host/xhci-hub.c:xhci_hub_control
  - drivers/usb/host/xhci-hub.c:xhci_hub_control
  - drivers/usb/host/xhci-hub.c:xhci_hub_control
```
```
In net/core/netpoll.c (ffffffff8190af85)
Location: include/linux/unaligned/access_ok.h:43
Inline: True
Inline callers:
  - net/core/netpoll.c:netpoll_send_udp
  - net/core/netpoll.c:netpoll_send_udp
```
```
In lib/chacha.c (ffffffff81a4caec)
Location: include/linux/unaligned/access_ok.h:43
Inline: True
Inline callers:
  - lib/chacha.c:chacha_block
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
In crypto/aes_generic.c (ffffffff814bbb87)
Location: include/linux/unaligned/access_ok.h:43
Inline: True
Inline callers:
  - crypto/aes_generic.c:crypto_aes_decrypt
  - crypto/aes_generic.c:crypto_aes_decrypt
  - crypto/aes_generic.c:crypto_aes_decrypt
  - crypto/aes_generic.c:crypto_aes_decrypt
  - crypto/aes_generic.c:crypto_aes_encrypt
  - crypto/aes_generic.c:crypto_aes_encrypt
  - crypto/aes_generic.c:crypto_aes_encrypt
  - crypto/aes_generic.c:crypto_aes_encrypt
```
```
In crypto/crc32c_generic.c (ffffffff814bc1da)
Location: include/linux/unaligned/access_ok.h:43
Inline: True
Inline callers:
  - crypto/crc32c_generic.c:chksum_digest
  - crypto/crc32c_generic.c:chksum_finup
  - crypto/crc32c_generic.c:chksum_final
```
```
In lib/random32.c (ffffffff81509463)
Location: include/linux/unaligned/access_ok.h:43
Inline: True
Inline callers:
  - lib/random32.c:prandom_bytes_state
```
```
In lib/crypto/aes.c (ffffffff81517eeb)
Location: include/linux/unaligned/access_ok.h:43
Inline: True
Inline callers:
  - lib/crypto/aes.c:aes_decrypt
  - lib/crypto/aes.c:aes_decrypt
  - lib/crypto/aes.c:aes_decrypt
  - lib/crypto/aes.c:aes_decrypt
  - lib/crypto/aes.c:aes_encrypt
  - lib/crypto/aes.c:aes_encrypt
  - lib/crypto/aes.c:aes_encrypt
  - lib/crypto/aes.c:aes_encrypt
```
```
In lib/lzo/lzo1x_compress.c (ffffffff81526d62)
Location: include/linux/unaligned/access_ok.h:43
Inline: True
Inline callers:
  - lib/lzo/lzo1x_compress.c:lzo1x_1_do_compress
  - lib/lzo/lzo1x_compress.c:lzo1x_1_do_compress
```
```
In lib/lzo/lzo1x_decompress_safe.c (ffffffff8152765b)
Location: include/linux/unaligned/access_ok.h:43
Inline: True
Inline callers:
  - lib/lzo/lzo1x_decompress_safe.c:lzo1x_decompress_safe
  - lib/lzo/lzo1x_decompress_safe.c:lzo1x_decompress_safe
```
```
In lib/lz4/lz4_decompress.c (ffffffff8152928d)
Location: include/linux/unaligned/access_ok.h:43
Inline: True
Inline callers:
  - lib/lz4/lz4_decompress.c:LZ4_decompress_fast_continue
  - lib/lz4/lz4_decompress.c:LZ4_decompress_safe_continue
  - lib/lz4/lz4_decompress.c:LZ4_decompress_fast_extDict
  - lib/lz4/lz4_decompress.c:LZ4_decompress_safe_forceExtDict
  - lib/lz4/lz4_decompress.c:LZ4_decompress_safe_withSmallPrefix
  - lib/lz4/lz4_decompress.c:LZ4_decompress_safe_withPrefix64k
  - lib/lz4/lz4_decompress.c:LZ4_decompress_fast
  - lib/lz4/lz4_decompress.c:LZ4_decompress_safe
```
```
In lib/xz/xz_dec_bcj.c (ffffffff8153a9bf)
Location: include/linux/unaligned/access_ok.h:43
Inline: True
Inline callers:
  - lib/xz/xz_dec_bcj.c:bcj_apply
```
```
In drivers/usb/host/xhci-hub.c (ffffffff817c337d)
Location: include/linux/unaligned/access_ok.h:43
Inline: True
Inline callers:
  - drivers/usb/host/xhci-hub.c:xhci_hub_control
  - drivers/usb/host/xhci-hub.c:xhci_hub_control
  - drivers/usb/host/xhci-hub.c:xhci_hub_control
  - drivers/usb/host/xhci-hub.c:xhci_hub_control
  - drivers/usb/host/xhci-hub.c:xhci_hub_control
```
```
In net/core/netpoll.c (ffffffff818c4d20)
Location: include/linux/unaligned/access_ok.h:43
Inline: True
Inline callers:
  - net/core/netpoll.c:netpoll_send_udp
  - net/core/netpoll.c:netpoll_send_udp
```
```
In lib/chacha.c (ffffffff81a09c1c)
Location: include/linux/unaligned/access_ok.h:43
Inline: True
Inline callers:
  - lib/chacha.c:chacha_block
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
In crypto/aes_generic.c (ffffffff814c71f7)
Location: include/linux/unaligned/access_ok.h:43
Inline: True
Inline callers:
  - crypto/aes_generic.c:crypto_aes_decrypt
  - crypto/aes_generic.c:crypto_aes_decrypt
  - crypto/aes_generic.c:crypto_aes_decrypt
  - crypto/aes_generic.c:crypto_aes_decrypt
  - crypto/aes_generic.c:crypto_aes_encrypt
  - crypto/aes_generic.c:crypto_aes_encrypt
  - crypto/aes_generic.c:crypto_aes_encrypt
  - crypto/aes_generic.c:crypto_aes_encrypt
```
```
In crypto/crc32c_generic.c (ffffffff814c784a)
Location: include/linux/unaligned/access_ok.h:43
Inline: True
Inline callers:
  - crypto/crc32c_generic.c:chksum_digest
  - crypto/crc32c_generic.c:chksum_finup
  - crypto/crc32c_generic.c:chksum_final
```
```
In lib/random32.c (ffffffff815151f3)
Location: include/linux/unaligned/access_ok.h:43
Inline: True
Inline callers:
  - lib/random32.c:prandom_bytes_state
```
```
In lib/crypto/aes.c (ffffffff81523c9b)
Location: include/linux/unaligned/access_ok.h:43
Inline: True
Inline callers:
  - lib/crypto/aes.c:aes_decrypt
  - lib/crypto/aes.c:aes_decrypt
  - lib/crypto/aes.c:aes_decrypt
  - lib/crypto/aes.c:aes_decrypt
  - lib/crypto/aes.c:aes_encrypt
  - lib/crypto/aes.c:aes_encrypt
  - lib/crypto/aes.c:aes_encrypt
  - lib/crypto/aes.c:aes_encrypt
```
```
In lib/lzo/lzo1x_compress.c (ffffffff815327c2)
Location: include/linux/unaligned/access_ok.h:43
Inline: True
Inline callers:
  - lib/lzo/lzo1x_compress.c:lzo1x_1_do_compress
  - lib/lzo/lzo1x_compress.c:lzo1x_1_do_compress
```
```
In lib/lzo/lzo1x_decompress_safe.c (ffffffff815330bb)
Location: include/linux/unaligned/access_ok.h:43
Inline: True
Inline callers:
  - lib/lzo/lzo1x_decompress_safe.c:lzo1x_decompress_safe
  - lib/lzo/lzo1x_decompress_safe.c:lzo1x_decompress_safe
```
```
In lib/lz4/lz4_decompress.c (ffffffff81534ced)
Location: include/linux/unaligned/access_ok.h:43
Inline: True
Inline callers:
  - lib/lz4/lz4_decompress.c:LZ4_decompress_fast_continue
  - lib/lz4/lz4_decompress.c:LZ4_decompress_safe_continue
  - lib/lz4/lz4_decompress.c:LZ4_decompress_fast_extDict
  - lib/lz4/lz4_decompress.c:LZ4_decompress_safe_forceExtDict
  - lib/lz4/lz4_decompress.c:LZ4_decompress_safe_withSmallPrefix
  - lib/lz4/lz4_decompress.c:LZ4_decompress_safe_withPrefix64k
  - lib/lz4/lz4_decompress.c:LZ4_decompress_fast
  - lib/lz4/lz4_decompress.c:LZ4_decompress_safe
```
```
In lib/xz/xz_dec_bcj.c (ffffffff8154641f)
Location: include/linux/unaligned/access_ok.h:43
Inline: True
Inline callers:
  - lib/xz/xz_dec_bcj.c:bcj_apply
```
```
In drivers/usb/host/ehci-hcd.c (ffffffff81816b51)
Location: include/linux/unaligned/access_ok.h:43
Inline: True
Inline callers:
  - drivers/usb/host/ehci-hcd.c:ehci_hub_control
```
```
In drivers/usb/host/ohci-hcd.c (ffffffff8181a336)
Location: include/linux/unaligned/access_ok.h:43
Inline: True
Inline callers:
  - drivers/usb/host/ohci-hcd.c:ohci_hub_control
  - drivers/usb/host/ohci-hcd.c:ohci_hub_control
```
```
In drivers/usb/host/xhci-hub.c (ffffffff8183acad)
Location: include/linux/unaligned/access_ok.h:43
Inline: True
Inline callers:
  - drivers/usb/host/xhci-hub.c:xhci_hub_control
  - drivers/usb/host/xhci-hub.c:xhci_hub_control
  - drivers/usb/host/xhci-hub.c:xhci_hub_control
  - drivers/usb/host/xhci-hub.c:xhci_hub_control
  - drivers/usb/host/xhci-hub.c:xhci_hub_control
```
```
In net/core/netpoll.c (ffffffff8195bfb5)
Location: include/linux/unaligned/access_ok.h:43
Inline: True
Inline callers:
  - net/core/netpoll.c:netpoll_send_udp
  - net/core/netpoll.c:netpoll_send_udp
```
```
In lib/chacha.c (ffffffff81ab8edc)
Location: include/linux/unaligned/access_ok.h:43
Inline: True
Inline callers:
  - lib/chacha.c:chacha_block
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
In crypto/aes_generic.c (ffffffff814dfcc7)
Location: include/linux/unaligned/access_ok.h:43
Inline: True
Inline callers:
  - crypto/aes_generic.c:crypto_aes_decrypt
  - crypto/aes_generic.c:crypto_aes_decrypt
  - crypto/aes_generic.c:crypto_aes_decrypt
  - crypto/aes_generic.c:crypto_aes_decrypt
  - crypto/aes_generic.c:crypto_aes_encrypt
  - crypto/aes_generic.c:crypto_aes_encrypt
  - crypto/aes_generic.c:crypto_aes_encrypt
  - crypto/aes_generic.c:crypto_aes_encrypt
```
```
In crypto/crc32c_generic.c (ffffffff814e031a)
Location: include/linux/unaligned/access_ok.h:43
Inline: True
Inline callers:
  - crypto/crc32c_generic.c:chksum_digest
  - crypto/crc32c_generic.c:chksum_finup
  - crypto/crc32c_generic.c:chksum_final
```
```
In lib/random32.c (ffffffff8152e943)
Location: include/linux/unaligned/access_ok.h:43
Inline: True
Inline callers:
  - lib/random32.c:prandom_bytes_state
```
```
In lib/crypto/aes.c (ffffffff8153d61b)
Location: include/linux/unaligned/access_ok.h:43
Inline: True
Inline callers:
  - lib/crypto/aes.c:aes_decrypt
  - lib/crypto/aes.c:aes_decrypt
  - lib/crypto/aes.c:aes_decrypt
  - lib/crypto/aes.c:aes_decrypt
  - lib/crypto/aes.c:aes_encrypt
  - lib/crypto/aes.c:aes_encrypt
  - lib/crypto/aes.c:aes_encrypt
  - lib/crypto/aes.c:aes_encrypt
```
```
In lib/lzo/lzo1x_compress.c (ffffffff8154c5f2)
Location: include/linux/unaligned/access_ok.h:43
Inline: True
Inline callers:
  - lib/lzo/lzo1x_compress.c:lzo1x_1_do_compress
  - lib/lzo/lzo1x_compress.c:lzo1x_1_do_compress
```
```
In lib/lzo/lzo1x_decompress_safe.c (ffffffff8154ceeb)
Location: include/linux/unaligned/access_ok.h:43
Inline: True
Inline callers:
  - lib/lzo/lzo1x_decompress_safe.c:lzo1x_decompress_safe
  - lib/lzo/lzo1x_decompress_safe.c:lzo1x_decompress_safe
```
```
In lib/lz4/lz4_decompress.c (ffffffff8154eb1d)
Location: include/linux/unaligned/access_ok.h:43
Inline: True
Inline callers:
  - lib/lz4/lz4_decompress.c:LZ4_decompress_fast_continue
  - lib/lz4/lz4_decompress.c:LZ4_decompress_safe_continue
  - lib/lz4/lz4_decompress.c:LZ4_decompress_fast_extDict
  - lib/lz4/lz4_decompress.c:LZ4_decompress_safe_forceExtDict
  - lib/lz4/lz4_decompress.c:LZ4_decompress_safe_withSmallPrefix
  - lib/lz4/lz4_decompress.c:LZ4_decompress_safe_withPrefix64k
  - lib/lz4/lz4_decompress.c:LZ4_decompress_fast
  - lib/lz4/lz4_decompress.c:LZ4_decompress_safe
```
```
In lib/xz/xz_dec_bcj.c (ffffffff8156024f)
Location: include/linux/unaligned/access_ok.h:43
Inline: True
Inline callers:
  - lib/xz/xz_dec_bcj.c:bcj_apply
```
```
In drivers/usb/host/ehci-hcd.c (ffffffff81830ba1)
Location: include/linux/unaligned/access_ok.h:43
Inline: True
Inline callers:
  - drivers/usb/host/ehci-hcd.c:ehci_hub_control
```
```
In drivers/usb/host/ohci-hcd.c (ffffffff81834486)
Location: include/linux/unaligned/access_ok.h:43
Inline: True
Inline callers:
  - drivers/usb/host/ohci-hcd.c:ohci_hub_control
  - drivers/usb/host/ohci-hcd.c:ohci_hub_control
```
```
In drivers/usb/host/xhci-hub.c (ffffffff8185513d)
Location: include/linux/unaligned/access_ok.h:43
Inline: True
Inline callers:
  - drivers/usb/host/xhci-hub.c:xhci_hub_control
  - drivers/usb/host/xhci-hub.c:xhci_hub_control
  - drivers/usb/host/xhci-hub.c:xhci_hub_control
  - drivers/usb/host/xhci-hub.c:xhci_hub_control
  - drivers/usb/host/xhci-hub.c:xhci_hub_control
```
```
In net/core/netpoll.c (ffffffff8197e395)
Location: include/linux/unaligned/access_ok.h:43
Inline: True
Inline callers:
  - net/core/netpoll.c:netpoll_send_udp
  - net/core/netpoll.c:netpoll_send_udp
```
```
In lib/chacha.c (ffffffff81ac532c)
Location: include/linux/unaligned/access_ok.h:43
Inline: True
Inline callers:
  - lib/chacha.c:chacha_block
```
</details>
</li>
</ul>

## Differences
