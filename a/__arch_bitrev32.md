# Function: <code>__arch_bitrev32</code>

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
<details>
<summary>In <code>arm64</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In lib/zlib_deflate/deftree.c (ffff8000106494e4)
Location: arch/arm64/include/asm/bitrev.h:4
Inline: True
Inline callers:
  - lib/zlib_deflate/deftree.c:gen_codes
  - lib/zlib_deflate/deftree.c:zlib_tr_init
```
```
In drivers/net/tun.c (ffff8000109e0244)
Location: arch/arm64/include/asm/bitrev.h:4
Inline: True
Inline callers:
  - drivers/net/tun.c:__tun_chr_ioctl
  - drivers/net/tun.c:tun_net_xmit
```
```
In drivers/net/ethernet/freescale/fman/fman_dtsec.c (ffff8000109f582c)
Location: arch/arm64/include/asm/bitrev.h:4
Inline: True
Inline callers:
  - drivers/net/ethernet/freescale/fman/fman_dtsec.c:dtsec_del_hash_mac_address
  - drivers/net/ethernet/freescale/fman/fman_dtsec.c:dtsec_add_hash_mac_address
```
```
In drivers/net/ethernet/freescale/fman/fman_tgec.c (ffff8000109f83e8)
Location: arch/arm64/include/asm/bitrev.h:4
Inline: True
Inline callers:
  - drivers/net/ethernet/freescale/fman/fman_tgec.c:tgec_del_hash_mac_address
  - drivers/net/ethernet/freescale/fman/fman_tgec.c:tgec_add_hash_mac_address
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
In lib/zlib_deflate/deftree.c (c07eff5c)
Location: arch/arm/include/asm/bitrev.h:5
Inline: True
Inline callers:
  - lib/zlib_deflate/deftree.c:gen_codes
  - lib/zlib_deflate/deftree.c:zlib_tr_init
```
```
In drivers/net/tun.c (c0ac2cfc)
Location: arch/arm/include/asm/bitrev.h:5
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_net_xmit
```
</details>
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
