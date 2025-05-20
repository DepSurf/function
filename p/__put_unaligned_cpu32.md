# Function: <code>__put_unaligned_cpu32</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4</code>: Absent ⚠️
</li>
<li>
In <code>4.8</code>: Absent ⚠️
</li>
<li>
In <code>4.10</code>: Absent ⚠️
</li>
<li>
In <code>4.13</code>: Absent ⚠️
</li>
<li>
In <code>4.15</code>: Absent ⚠️
</li>
<li>
In <code>4.18</code>: Absent ⚠️
</li>
<li>
In <code>5.0</code>: Absent ⚠️
</li>
<li>
In <code>5.3</code>: Absent ⚠️
</li>
<li>
In <code>5.4</code>: Absent ⚠️
</li>
<li>
In <code>5.8</code>: Absent ⚠️
</li>
<li>
In <code>5.11</code>: Absent ⚠️
</li>
<li>
In <code>5.13</code>: Absent ⚠️
</li>
<li>
In <code>5.15</code>: Absent ⚠️
</li>
<li>
In <code>5.19</code>: Absent ⚠️
</li>
<li>
In <code>6.2</code>: Absent ⚠️
</li>
<li>
In <code>6.5</code>: Absent ⚠️
</li>
<li>
In <code>6.8</code>: Absent ⚠️
</li>
</ul>
<b>Arch</b>
<ul>
<li>
In <code>arm64</code>: Absent ⚠️
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
Location: include/linux/unaligned/packed_struct.h:34
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
Location: include/linux/unaligned/packed_struct.h:34
Inline: True
Inline callers:
  - crypto/crc32c_generic.c:chksum_digest
  - crypto/crc32c_generic.c:chksum_finup
  - crypto/crc32c_generic.c:chksum_final
```
```
In lib/random32.c (c07d13d4)
Location: include/linux/unaligned/packed_struct.h:34
Inline: True
Inline callers:
  - lib/random32.c:prandom_bytes_state
```
```
In lib/crypto/aes.c (c07e1db0)
Location: include/linux/unaligned/packed_struct.h:34
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
Location: include/linux/unaligned/packed_struct.h:34
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
Location: include/linux/unaligned/packed_struct.h:34
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
Location: include/linux/unaligned/packed_struct.h:34
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
Location: include/linux/unaligned/packed_struct.h:34
Inline: True
Inline callers:
  - lib/xz/xz_dec_bcj.c:bcj_apply
```
```
In drivers/usb/core/hcd.c (c0af3a0c)
Location: include/linux/unaligned/packed_struct.h:34
Inline: True
```
```
In drivers/usb/host/ehci-hcd.c (c0b2c6a8)
Location: include/linux/unaligned/packed_struct.h:34
Inline: True
Inline callers:
  - drivers/usb/host/ehci-hcd.c:ehci_hub_control
```
```
In drivers/usb/host/ohci-hcd.c (c0b31af4)
Location: include/linux/unaligned/packed_struct.h:34
Inline: True
Inline callers:
  - drivers/usb/host/ohci-hcd.c:ohci_hub_control
  - drivers/usb/host/ohci-hcd.c:ohci_hub_control
```
```
In drivers/usb/host/xhci-hub.c (c0b57de0)
Location: include/linux/unaligned/packed_struct.h:34
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
Location: include/linux/unaligned/packed_struct.h:34
Inline: True
Inline callers:
  - drivers/usb/musb/musb_virthub.c:musb_hub_control
```
```
In drivers/firmware/arm_scmi/base.c (c0c388a4)
Location: include/linux/unaligned/packed_struct.h:34
Inline: True
Inline callers:
  - drivers/firmware/arm_scmi/base.c:scmi_base_protocol_init
```
```
In drivers/firmware/arm_scmi/clock.c (c0c38e98)
Location: include/linux/unaligned/packed_struct.h:34
Inline: True
Inline callers:
  - drivers/firmware/arm_scmi/clock.c:scmi_clock_protocol_init
  - drivers/firmware/arm_scmi/clock.c:scmi_clock_rate_get
```
```
In drivers/firmware/arm_scmi/perf.c (c0c39cbc)
Location: include/linux/unaligned/packed_struct.h:34
Inline: True
Inline callers:
  - drivers/firmware/arm_scmi/perf.c:scmi_perf_protocol_init
  - drivers/firmware/arm_scmi/perf.c:scmi_perf_level_get
  - drivers/firmware/arm_scmi/perf.c:scmi_perf_limits_get
```
```
In drivers/firmware/arm_scmi/power.c (c0c3a31c)
Location: include/linux/unaligned/packed_struct.h:34
Inline: True
Inline callers:
  - drivers/firmware/arm_scmi/power.c:scmi_power_protocol_init
  - drivers/firmware/arm_scmi/power.c:scmi_power_state_get
```
```
In drivers/firmware/arm_scmi/reset.c (c0c3a5f8)
Location: include/linux/unaligned/packed_struct.h:34
Inline: True
Inline callers:
  - drivers/firmware/arm_scmi/reset.c:scmi_reset_protocol_init
```
```
In drivers/firmware/arm_scmi/sensors.c (c0c3ac0c)
Location: include/linux/unaligned/packed_struct.h:34
Inline: True
Inline callers:
  - drivers/firmware/arm_scmi/sensors.c:scmi_sensors_protocol_init
```
```
In net/core/netpoll.c (c0d294cc)
Location: include/linux/unaligned/packed_struct.h:34
Inline: True
Inline callers:
  - net/core/netpoll.c:netpoll_send_udp
  - net/core/netpoll.c:netpoll_send_udp
```
```
In lib/chacha.c (c0e7f3b8)
Location: include/linux/unaligned/packed_struct.h:34
Inline: True
Inline callers:
  - lib/chacha.c:chacha_block
```
</details>
</li>
<li>
In <code>ppc64el</code>: Absent ⚠️
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
Location: include/linux/unaligned/packed_struct.h:34
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
Location: include/linux/unaligned/packed_struct.h:34
Inline: True
Inline callers:
  - crypto/crc32c_generic.c:chksum_digest
  - crypto/crc32c_generic.c:chksum_finup
  - crypto/crc32c_generic.c:chksum_final
```
```
In lib/random32.c (ffffffe00045aba0)
Location: include/linux/unaligned/packed_struct.h:34
Inline: True
Inline callers:
  - lib/random32.c:prandom_bytes_state
```
```
In lib/crypto/aes.c (ffffffe000468742)
Location: include/linux/unaligned/packed_struct.h:34
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
Location: include/linux/unaligned/packed_struct.h:34
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
Location: include/linux/unaligned/packed_struct.h:34
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
Location: include/linux/unaligned/packed_struct.h:34
Inline: True
Inline callers:
  - lib/xz/xz_dec_bcj.c:bcj_apply
```
```
In drivers/usb/host/ehci-hcd.c (ffffffe000677dfe)
Location: include/linux/unaligned/packed_struct.h:34
Inline: True
Inline callers:
  - drivers/usb/host/ehci-hcd.c:ehci_hub_control
```
```
In drivers/usb/host/ohci-hcd.c (ffffffe00067a6ee)
Location: include/linux/unaligned/packed_struct.h:34
Inline: True
Inline callers:
  - drivers/usb/host/ohci-hcd.c:ohci_hub_control
  - drivers/usb/host/ohci-hcd.c:ohci_hub_control
```
```
In drivers/usb/host/xhci-hub.c (ffffffe00069a8a8)
Location: include/linux/unaligned/packed_struct.h:34
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
Location: include/linux/unaligned/packed_struct.h:34
Inline: True
Inline callers:
  - net/core/netpoll.c:netpoll_send_udp
  - net/core/netpoll.c:netpoll_send_udp
```
```
In lib/chacha.c (ffffffe0008ae616)
Location: include/linux/unaligned/packed_struct.h:34
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
In <code>aws</code>: Absent ⚠️
</li>
<li>
In <code>azure</code>: Absent ⚠️
</li>
<li>
In <code>gcp</code>: Absent ⚠️
</li>
<li>
In <code>lowlatency</code>: Absent ⚠️
</li>
</ul>

## Differences
