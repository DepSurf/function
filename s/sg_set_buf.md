# Function: <code>sg_set_buf</code>

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
In security/keys/encrypted-keys/encrypted.c (ffffffff81338fbb)
Location: include/linux/scatterlist.h:136
Inline: True
```
```
In crypto/eseqiv.c (ffffffff813a2611)
Location: include/linux/scatterlist.h:136
Inline: True
Inline callers:
  - crypto/eseqiv.c:eseqiv_givencrypt
  - crypto/eseqiv.c:eseqiv_givencrypt
```
```
In lib/scatterlist.c (ffffffff813f9eec)
Location: include/linux/scatterlist.h:136
Inline: True
Inline callers:
  - lib/scatterlist.c:sg_init_one
```
```
In drivers/spi/spi.c (ffffffff815e7801)
Location: include/linux/scatterlist.h:136
Inline: True
```
```
In drivers/net/virtio_net.c (ffffffff815f21df)
Location: include/linux/scatterlist.h:136
Inline: True
Inline callers:
  - drivers/net/virtio_net.c:virtnet_set_rx_mode
  - drivers/net/virtio_net.c:virtnet_set_rx_mode
  - drivers/net/virtio_net.c:start_xmit
  - drivers/net/virtio_net.c:try_fill_recv
  - drivers/net/virtio_net.c:try_fill_recv
  - drivers/net/virtio_net.c:try_fill_recv
  - drivers/net/virtio_net.c:try_fill_recv
```
```
In drivers/usb/core/devio.c (ffffffff8161c260)
Location: include/linux/scatterlist.h:136
Inline: True
Inline callers:
  - drivers/usb/core/devio.c:proc_do_submiturb
```
```
In net/core/skbuff.c (ffffffff81705741)
Location: include/linux/scatterlist.h:136
Inline: True
Inline callers:
  - net/core/skbuff.c:__skb_to_sgvec
```
```
In net/ipv4/tcp.c (ffffffff81766cb7)
Location: include/linux/scatterlist.h:136
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_md5_hash_skb_data
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
In security/keys/encrypted-keys/encrypted.c (ffffffff8136e56d)
Location: include/linux/scatterlist.h:136
Inline: True
```
```
In crypto/rsa-pkcs1pad.c (ffffffff813e0ee4)
Location: include/linux/scatterlist.h:136
Inline: True
Inline callers:
  - crypto/rsa-pkcs1pad.c:pkcs1pad_sg_set_buf
```
```
In lib/scatterlist.c (ffffffff81441080)
Location: include/linux/scatterlist.h:136
Inline: True
Inline callers:
  - lib/scatterlist.c:sg_init_one
```
```
In drivers/spi/spi.c (ffffffff81645867)
Location: include/linux/scatterlist.h:136
Inline: True
```
```
In drivers/net/virtio_net.c (ffffffff81651b0f)
Location: include/linux/scatterlist.h:136
Inline: True
Inline callers:
  - drivers/net/virtio_net.c:virtnet_set_rx_mode
  - drivers/net/virtio_net.c:virtnet_set_rx_mode
  - drivers/net/virtio_net.c:start_xmit
  - drivers/net/virtio_net.c:try_fill_recv
  - drivers/net/virtio_net.c:try_fill_recv
  - drivers/net/virtio_net.c:try_fill_recv
  - drivers/net/virtio_net.c:try_fill_recv
```
```
In drivers/usb/core/devio.c (ffffffff8167c175)
Location: include/linux/scatterlist.h:136
Inline: True
Inline callers:
  - drivers/usb/core/devio.c:proc_do_submiturb
```
```
In net/core/skbuff.c (ffffffff8176c413)
Location: include/linux/scatterlist.h:136
Inline: True
Inline callers:
  - net/core/skbuff.c:__skb_to_sgvec
```
```
In net/ipv4/tcp.c (ffffffff817d3199)
Location: include/linux/scatterlist.h:136
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_md5_hash_skb_data
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
In security/keys/encrypted-keys/encrypted.c (ffffffff81385189)
Location: include/linux/scatterlist.h:136
Inline: True
```
```
In crypto/rsa-pkcs1pad.c (ffffffff813fa185)
Location: include/linux/scatterlist.h:136
Inline: True
Inline callers:
  - crypto/rsa-pkcs1pad.c:pkcs1pad_verify
  - crypto/rsa-pkcs1pad.c:pkcs1pad_decrypt
  - crypto/rsa-pkcs1pad.c:pkcs1pad_encrypt
```
```
In lib/scatterlist.c (ffffffff8145e650)
Location: include/linux/scatterlist.h:136
Inline: True
Inline callers:
  - lib/scatterlist.c:sg_init_one
```
```
In drivers/spi/spi.c (ffffffff81676ffd)
Location: include/linux/scatterlist.h:136
Inline: True
```
```
In drivers/usb/core/devio.c (ffffffff816aa123)
Location: include/linux/scatterlist.h:136
Inline: True
Inline callers:
  - drivers/usb/core/devio.c:proc_do_submiturb
```
```
In net/core/skbuff.c (ffffffff81799e53)
Location: include/linux/scatterlist.h:136
Inline: True
Inline callers:
  - net/core/skbuff.c:__skb_to_sgvec
```
```
In net/ipv4/tcp.c (ffffffff81804a79)
Location: include/linux/scatterlist.h:136
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_md5_hash_skb_data
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
In security/keys/encrypted-keys/encrypted.c (ffffffff81399886)
Location: include/linux/scatterlist.h:136
Inline: True
```
```
In crypto/rsa-pkcs1pad.c (ffffffff81406995)
Location: include/linux/scatterlist.h:136
Inline: True
Inline callers:
  - crypto/rsa-pkcs1pad.c:pkcs1pad_verify
  - crypto/rsa-pkcs1pad.c:pkcs1pad_decrypt
  - crypto/rsa-pkcs1pad.c:pkcs1pad_encrypt
```
```
In lib/scatterlist.c (ffffffff81463e2c)
Location: include/linux/scatterlist.h:136
Inline: True
Inline callers:
  - lib/scatterlist.c:sg_init_one
```
```
In drivers/spi/spi.c (ffffffff8168b6f8)
Location: include/linux/scatterlist.h:136
Inline: True
```
```
In drivers/usb/core/devio.c (ffffffff816bf093)
Location: include/linux/scatterlist.h:136
Inline: True
Inline callers:
  - drivers/usb/core/devio.c:proc_do_submiturb
```
```
In drivers/mmc/core/sdio_ops.c (ffffffff8177ec64)
Location: include/linux/scatterlist.h:136
Inline: True
Inline callers:
  - drivers/mmc/core/sdio_ops.c:mmc_io_rw_extended
```
```
In net/core/skbuff.c (ffffffff817b94c6)
Location: include/linux/scatterlist.h:136
Inline: True
Inline callers:
  - net/core/skbuff.c:__skb_to_sgvec
```
```
In net/ipv4/tcp.c (ffffffff81824db6)
Location: include/linux/scatterlist.h:136
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_md5_hash_skb_data
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
In security/keys/encrypted-keys/encrypted.c (ffffffff813bf056)
Location: include/linux/scatterlist.h:143
Inline: True
```
```
In crypto/rsa-pkcs1pad.c (ffffffff8142f2d5)
Location: include/linux/scatterlist.h:143
Inline: True
Inline callers:
  - crypto/rsa-pkcs1pad.c:pkcs1pad_verify
  - crypto/rsa-pkcs1pad.c:pkcs1pad_decrypt
  - crypto/rsa-pkcs1pad.c:pkcs1pad_encrypt
```
```
In crypto/gcm.c (ffffffff81439d4e)
Location: include/linux/scatterlist.h:143
Inline: True
Inline callers:
  - crypto/gcm.c:crypto_rfc4106_crypt
  - crypto/gcm.c:crypto_rfc4106_crypt
  - crypto/gcm.c:crypto_gcm_init_common
  - crypto/gcm.c:crypto_gcm_init_common
```
```
In lib/scatterlist.c (ffffffff8148f81c)
Location: include/linux/scatterlist.h:143
Inline: True
Inline callers:
  - lib/scatterlist.c:sg_init_one
```
```
In drivers/spi/spi.c (ffffffff816f5083)
Location: include/linux/scatterlist.h:143
Inline: True
```
```
In drivers/usb/core/devio.c (ffffffff8172aa8a)
Location: include/linux/scatterlist.h:143
Inline: True
Inline callers:
  - drivers/usb/core/devio.c:proc_do_submiturb
```
```
In drivers/mmc/core/sdio_ops.c (ffffffff817f5204)
Location: include/linux/scatterlist.h:143
Inline: True
Inline callers:
  - drivers/mmc/core/sdio_ops.c:mmc_io_rw_extended
```
```
In net/core/skbuff.c (ffffffff81831d06)
Location: include/linux/scatterlist.h:143
Inline: True
Inline callers:
  - net/core/skbuff.c:__skb_to_sgvec
```
```
In net/ipv4/tcp.c (ffffffff818a3726)
Location: include/linux/scatterlist.h:143
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_md5_hash_skb_data
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
In security/keys/encrypted-keys/encrypted.c (ffffffff813efde1)
Location: include/linux/scatterlist.h:139
Inline: True
```
```
In crypto/rsa-pkcs1pad.c (ffffffff81461f65)
Location: include/linux/scatterlist.h:139
Inline: True
Inline callers:
  - crypto/rsa-pkcs1pad.c:pkcs1pad_verify
  - crypto/rsa-pkcs1pad.c:pkcs1pad_decrypt
  - crypto/rsa-pkcs1pad.c:pkcs1pad_encrypt
```
```
In crypto/gcm.c (ffffffff8146ca71)
Location: include/linux/scatterlist.h:139
Inline: True
Inline callers:
  - crypto/gcm.c:crypto_rfc4106_crypt
  - crypto/gcm.c:crypto_rfc4106_crypt
  - crypto/gcm.c:crypto_gcm_init_common
  - crypto/gcm.c:crypto_gcm_init_common
```
```
In lib/scatterlist.c (ffffffff814c44fc)
Location: include/linux/scatterlist.h:139
Inline: True
Inline callers:
  - lib/scatterlist.c:sg_init_one
```
```
In drivers/spi/spi.c (ffffffff81732872)
Location: include/linux/scatterlist.h:139
Inline: True
Inline callers:
  - drivers/spi/spi.c:spi_map_buf
```
```
In drivers/usb/core/devio.c (ffffffff81769469)
Location: include/linux/scatterlist.h:139
Inline: True
Inline callers:
  - drivers/usb/core/devio.c:proc_do_submiturb
```
```
In drivers/mmc/core/sdio_ops.c (ffffffff8183e750)
Location: include/linux/scatterlist.h:139
Inline: True
Inline callers:
  - drivers/mmc/core/sdio_ops.c:mmc_io_rw_extended
```
```
In net/core/skbuff.c (ffffffff8187c3d8)
Location: include/linux/scatterlist.h:139
Inline: True
Inline callers:
  - net/core/skbuff.c:__skb_to_sgvec
```
```
In net/ipv4/tcp.c (ffffffff818f8a86)
Location: include/linux/scatterlist.h:139
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_md5_hash_skb_data
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
In security/keys/encrypted-keys/encrypted.c (ffffffff8140b0c6)
Location: include/linux/scatterlist.h:139
Inline: True
```
```
In crypto/rsa-pkcs1pad.c (ffffffff8147fd35)
Location: include/linux/scatterlist.h:139
Inline: True
Inline callers:
  - crypto/rsa-pkcs1pad.c:pkcs1pad_verify
  - crypto/rsa-pkcs1pad.c:pkcs1pad_decrypt
```
```
In crypto/gcm.c (ffffffff8148a1e1)
Location: include/linux/scatterlist.h:139
Inline: True
Inline callers:
  - crypto/gcm.c:crypto_rfc4106_crypt
  - crypto/gcm.c:crypto_rfc4106_crypt
  - crypto/gcm.c:crypto_gcm_init_common
  - crypto/gcm.c:crypto_gcm_init_common
```
```
In crypto/drbg.c (ffffffff81490011)
Location: include/linux/scatterlist.h:139
Inline: True
Inline callers:
  - crypto/drbg.c:drbg_kcapi_sym_ctr
  - crypto/drbg.c:drbg_kcapi_sym_ctr
```
```
In lib/scatterlist.c (ffffffff814d8bec)
Location: include/linux/scatterlist.h:139
Inline: True
Inline callers:
  - lib/scatterlist.c:sg_init_one
```
```
In drivers/spi/spi.c (ffffffff81755262)
Location: include/linux/scatterlist.h:139
Inline: True
Inline callers:
  - drivers/spi/spi.c:spi_map_buf
```
```
In drivers/usb/core/devio.c (ffffffff8178daec)
Location: include/linux/scatterlist.h:139
Inline: True
Inline callers:
  - drivers/usb/core/devio.c:proc_do_submiturb
```
```
In drivers/mmc/core/sdio_ops.c (ffffffff8186a700)
Location: include/linux/scatterlist.h:139
Inline: True
Inline callers:
  - drivers/mmc/core/sdio_ops.c:mmc_io_rw_extended
```
```
In net/core/skbuff.c (ffffffff8189cd62)
Location: include/linux/scatterlist.h:139
Inline: True
Inline callers:
  - net/core/skbuff.c:__skb_to_sgvec
```
```
In net/ipv4/tcp.c (ffffffff819267ad)
Location: include/linux/scatterlist.h:139
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_md5_hash_skb_data
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
In security/keys/encrypted-keys/encrypted.c (ffffffff81437ea0)
Location: include/linux/scatterlist.h:139
Inline: True
```
```
In crypto/rsa-pkcs1pad.c (ffffffff814adf31)
Location: include/linux/scatterlist.h:139
Inline: True
Inline callers:
  - crypto/rsa-pkcs1pad.c:pkcs1pad_verify
  - crypto/rsa-pkcs1pad.c:pkcs1pad_decrypt
```
```
In crypto/gcm.c (ffffffff814b79bb)
Location: include/linux/scatterlist.h:139
Inline: True
Inline callers:
  - crypto/gcm.c:crypto_rfc4106_crypt
  - crypto/gcm.c:crypto_rfc4106_crypt
  - crypto/gcm.c:crypto_gcm_init_common
  - crypto/gcm.c:crypto_gcm_init_common
```
```
In crypto/drbg.c (ffffffff814bd1fe)
Location: include/linux/scatterlist.h:139
Inline: True
Inline callers:
  - crypto/drbg.c:drbg_kcapi_sym_ctr
  - crypto/drbg.c:drbg_kcapi_sym_ctr
```
```
In crypto/asymmetric_keys/public_key.c (ffffffff814c0e22)
Location: include/linux/scatterlist.h:139
Inline: True
Inline callers:
  - crypto/asymmetric_keys/public_key.c:public_key_verify_signature
  - crypto/asymmetric_keys/public_key.c:public_key_verify_signature
```
```
In lib/scatterlist.c (ffffffff81504a9c)
Location: include/linux/scatterlist.h:139
Inline: True
Inline callers:
  - lib/scatterlist.c:sg_init_one
```
```
In drivers/spi/spi.c (ffffffff81791368)
Location: include/linux/scatterlist.h:139
Inline: True
Inline callers:
  - drivers/spi/spi.c:spi_map_buf
```
```
In drivers/usb/core/devio.c (ffffffff817cc5f1)
Location: include/linux/scatterlist.h:139
Inline: True
Inline callers:
  - drivers/usb/core/devio.c:proc_do_submiturb
```
```
In drivers/mmc/core/sdio_ops.c (ffffffff818ae5ef)
Location: include/linux/scatterlist.h:139
Inline: True
Inline callers:
  - drivers/mmc/core/sdio_ops.c:mmc_io_rw_extended
```
```
In net/core/skbuff.c (ffffffff818e762a)
Location: include/linux/scatterlist.h:139
Inline: True
Inline callers:
  - net/core/skbuff.c:__skb_to_sgvec
```
```
In net/ipv4/tcp.c (ffffffff81987670)
Location: include/linux/scatterlist.h:139
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_md5_hash_skb_data
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
In security/keys/encrypted-keys/encrypted.c (ffffffff81451c60)
Location: include/linux/scatterlist.h:139
Inline: True
```
```
In crypto/rsa-pkcs1pad.c (ffffffff814c8bde)
Location: include/linux/scatterlist.h:139
Inline: True
Inline callers:
  - crypto/rsa-pkcs1pad.c:pkcs1pad_verify
  - crypto/rsa-pkcs1pad.c:pkcs1pad_decrypt
```
```
In crypto/gcm.c (ffffffff814d0bdb)
Location: include/linux/scatterlist.h:139
Inline: True
Inline callers:
  - crypto/gcm.c:crypto_rfc4106_crypt
  - crypto/gcm.c:crypto_rfc4106_crypt
  - crypto/gcm.c:crypto_rfc4106_crypt
  - crypto/gcm.c:crypto_rfc4106_crypt
  - crypto/gcm.c:crypto_gcm_init_common
  - crypto/gcm.c:crypto_gcm_init_common
  - crypto/gcm.c:crypto_gcm_init_common
  - crypto/gcm.c:crypto_gcm_init_common
```
```
In crypto/drbg.c (ffffffff814d5ea1)
Location: include/linux/scatterlist.h:139
Inline: True
Inline callers:
  - crypto/drbg.c:drbg_kcapi_sym_ctr
  - crypto/drbg.c:drbg_kcapi_sym_ctr
  - crypto/drbg.c:drbg_kcapi_sym_ctr
  - crypto/drbg.c:drbg_kcapi_sym_ctr
```
```
In crypto/asymmetric_keys/public_key.c (ffffffff814d9c52)
Location: include/linux/scatterlist.h:139
Inline: True
Inline callers:
  - crypto/asymmetric_keys/public_key.c:public_key_verify_signature
  - crypto/asymmetric_keys/public_key.c:public_key_verify_signature
  - crypto/asymmetric_keys/public_key.c:public_key_verify_signature
  - crypto/asymmetric_keys/public_key.c:public_key_verify_signature
```
```
In lib/scatterlist.c (ffffffff8152311c)
Location: include/linux/scatterlist.h:139
Inline: True
Inline callers:
  - lib/scatterlist.c:sg_init_one
```
```
In drivers/spi/spi.c (ffffffff817b4f65)
Location: include/linux/scatterlist.h:139
Inline: True
Inline callers:
  - drivers/spi/spi.c:spi_map_buf
```
```
In drivers/usb/core/devio.c (ffffffff817fd280)
Location: include/linux/scatterlist.h:139
Inline: True
Inline callers:
  - drivers/usb/core/devio.c:proc_do_submiturb
```
```
In drivers/mmc/core/sdio_ops.c (ffffffff818e0a8d)
Location: include/linux/scatterlist.h:139
Inline: True
Inline callers:
  - drivers/mmc/core/sdio_ops.c:mmc_io_rw_extended
```
```
In net/core/skbuff.c (ffffffff8191994f)
Location: include/linux/scatterlist.h:139
Inline: True
Inline callers:
  - net/core/skbuff.c:__skb_to_sgvec
```
```
In net/ipv4/tcp.c (ffffffff819bde30)
Location: include/linux/scatterlist.h:139
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_md5_hash_skb_data
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
In security/keys/encrypted-keys/encrypted.c (ffffffff814a49be)
Location: include/linux/scatterlist.h:139
Inline: True
```
```
In crypto/rsa-pkcs1pad.c (ffffffff815272ae)
Location: include/linux/scatterlist.h:139
Inline: True
Inline callers:
  - crypto/rsa-pkcs1pad.c:pkcs1pad_verify
  - crypto/rsa-pkcs1pad.c:pkcs1pad_decrypt
```
```
In crypto/gcm.c (ffffffff8152f8c4)
Location: include/linux/scatterlist.h:139
Inline: True
Inline callers:
  - crypto/gcm.c:crypto_rfc4106_crypt
  - crypto/gcm.c:crypto_rfc4106_crypt
  - crypto/gcm.c:crypto_gcm_init_common
  - crypto/gcm.c:crypto_gcm_init_common
```
```
In crypto/drbg.c (ffffffff81535a84)
Location: include/linux/scatterlist.h:139
Inline: True
Inline callers:
  - crypto/drbg.c:drbg_kcapi_sym_ctr
  - crypto/drbg.c:drbg_kcapi_sym_ctr
```
```
In crypto/asymmetric_keys/public_key.c (ffffffff815391d0)
Location: include/linux/scatterlist.h:139
Inline: True
Inline callers:
  - crypto/asymmetric_keys/public_key.c:public_key_verify_signature
  - crypto/asymmetric_keys/public_key.c:public_key_verify_signature
```
```
In lib/scatterlist.c (ffffffff81586254)
Location: include/linux/scatterlist.h:139
Inline: True
Inline callers:
  - lib/scatterlist.c:sg_init_one
```
```
In drivers/scsi/scsi_lib.c (ffffffff81836f44)
Location: include/linux/scatterlist.h:139
Inline: True
Inline callers:
  - drivers/scsi/scsi_lib.c:scsi_init_io
```
```
In drivers/spi/spi.c (ffffffff8187bb1d)
Location: include/linux/scatterlist.h:139
Inline: True
Inline callers:
  - drivers/spi/spi.c:spi_map_buf
```
```
In drivers/usb/core/devio.c (ffffffff818cc89d)
Location: include/linux/scatterlist.h:139
Inline: True
Inline callers:
  - drivers/usb/core/devio.c:proc_do_submiturb
```
```
In drivers/mmc/core/sdio_ops.c (ffffffff819b3ab9)
Location: include/linux/scatterlist.h:139
Inline: True
Inline callers:
  - drivers/mmc/core/sdio_ops.c:mmc_io_rw_extended
```
```
In net/core/skbuff.c (ffffffff819ea80d)
Location: include/linux/scatterlist.h:139
Inline: True
Inline callers:
  - net/core/skbuff.c:__skb_to_sgvec
```
```
In net/ipv4/tcp.c (ffffffff81aa9001)
Location: include/linux/scatterlist.h:139
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_md5_hash_skb_data
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
In security/keys/encrypted-keys/encrypted.c (ffffffff814c21be)
Location: include/linux/scatterlist.h:133
Inline: True
```
```
In crypto/rsa-pkcs1pad.c (ffffffff8154422e)
Location: include/linux/scatterlist.h:133
Inline: True
Inline callers:
  - crypto/rsa-pkcs1pad.c:pkcs1pad_verify
  - crypto/rsa-pkcs1pad.c:pkcs1pad_decrypt
```
```
In crypto/gcm.c (ffffffff8154c484)
Location: include/linux/scatterlist.h:133
Inline: True
Inline callers:
  - crypto/gcm.c:crypto_rfc4106_crypt
  - crypto/gcm.c:crypto_rfc4106_crypt
  - crypto/gcm.c:crypto_gcm_init_common
  - crypto/gcm.c:crypto_gcm_init_common
```
```
In crypto/drbg.c (ffffffff815529f4)
Location: include/linux/scatterlist.h:133
Inline: True
Inline callers:
  - crypto/drbg.c:drbg_kcapi_sym_ctr
  - crypto/drbg.c:drbg_kcapi_sym_ctr
```
```
In crypto/asymmetric_keys/public_key.c (ffffffff81555fdf)
Location: include/linux/scatterlist.h:133
Inline: True
Inline callers:
  - crypto/asymmetric_keys/public_key.c:public_key_verify_signature
  - crypto/asymmetric_keys/public_key.c:public_key_verify_signature
```
```
In lib/scatterlist.c (ffffffff815a3334)
Location: include/linux/scatterlist.h:133
Inline: True
Inline callers:
  - lib/scatterlist.c:sg_init_one
```
```
In drivers/scsi/scsi_lib.c (ffffffff818479b7)
Location: include/linux/scatterlist.h:133
Inline: True
Inline callers:
  - drivers/scsi/scsi_lib.c:scsi_alloc_sgtables
```
```
In drivers/spi/spi.c (ffffffff8188acf9)
Location: include/linux/scatterlist.h:133
Inline: True
Inline callers:
  - drivers/spi/spi.c:spi_map_buf
```
```
In drivers/usb/core/devio.c (ffffffff818d7a7f)
Location: include/linux/scatterlist.h:133
Inline: True
Inline callers:
  - drivers/usb/core/devio.c:proc_do_submiturb
```
```
In drivers/mmc/core/sdio_ops.c (ffffffff819b5f39)
Location: include/linux/scatterlist.h:133
Inline: True
Inline callers:
  - drivers/mmc/core/sdio_ops.c:mmc_io_rw_extended
```
```
In net/core/skbuff.c (ffffffff819ea54d)
Location: include/linux/scatterlist.h:133
Inline: True
Inline callers:
  - net/core/skbuff.c:__skb_to_sgvec
```
```
In net/ipv4/tcp.c (ffffffff81ab34f1)
Location: include/linux/scatterlist.h:133
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_md5_hash_skb_data
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
In security/keys/encrypted-keys/encrypted.c (ffffffff814c87de)
Location: include/linux/scatterlist.h:133
Inline: True
```
```
In crypto/rsa-pkcs1pad.c (ffffffff8154c89e)
Location: include/linux/scatterlist.h:133
Inline: True
Inline callers:
  - crypto/rsa-pkcs1pad.c:pkcs1pad_verify
  - crypto/rsa-pkcs1pad.c:pkcs1pad_decrypt
```
```
In crypto/gcm.c (ffffffff815552e4)
Location: include/linux/scatterlist.h:133
Inline: True
Inline callers:
  - crypto/gcm.c:crypto_rfc4106_crypt
  - crypto/gcm.c:crypto_rfc4106_crypt
  - crypto/gcm.c:crypto_gcm_init_common
  - crypto/gcm.c:crypto_gcm_init_common
```
```
In crypto/drbg.c (ffffffff8155b2b4)
Location: include/linux/scatterlist.h:133
Inline: True
Inline callers:
  - crypto/drbg.c:drbg_kcapi_sym_ctr
  - crypto/drbg.c:drbg_kcapi_sym_ctr
```
```
In crypto/asymmetric_keys/public_key.c (ffffffff8155e73f)
Location: include/linux/scatterlist.h:133
Inline: True
Inline callers:
  - crypto/asymmetric_keys/public_key.c:public_key_verify_signature
  - crypto/asymmetric_keys/public_key.c:public_key_verify_signature
```
```
In lib/scatterlist.c (ffffffff815aa6ef)
Location: include/linux/scatterlist.h:133
Inline: True
Inline callers:
  - lib/scatterlist.c:sg_init_one
```
```
In drivers/scsi/scsi_lib.c (ffffffff8182aa37)
Location: include/linux/scatterlist.h:133
Inline: True
Inline callers:
  - drivers/scsi/scsi_lib.c:scsi_alloc_sgtables
```
```
In drivers/spi/spi.c (ffffffff8186d68c)
Location: include/linux/scatterlist.h:133
Inline: True
Inline callers:
  - drivers/spi/spi.c:spi_map_buf
```
```
In drivers/usb/core/devio.c (ffffffff818ba985)
Location: include/linux/scatterlist.h:133
Inline: True
Inline callers:
  - drivers/usb/core/devio.c:proc_do_submiturb
```
```
In drivers/mmc/core/sdio_ops.c (ffffffff8199a6f7)
Location: include/linux/scatterlist.h:133
Inline: True
Inline callers:
  - drivers/mmc/core/sdio_ops.c:mmc_io_rw_extended
```
```
In net/core/skbuff.c (ffffffff819d0b0d)
Location: include/linux/scatterlist.h:133
Inline: True
Inline callers:
  - net/core/skbuff.c:__skb_to_sgvec
```
```
In net/ipv4/tcp.c (ffffffff81a9e679)
Location: include/linux/scatterlist.h:133
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_md5_hash_skb_data
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
In security/keys/encrypted-keys/encrypted.c (ffffffff81521295)
Location: include/linux/scatterlist.h:139
Inline: True
```
```
In crypto/rsa-pkcs1pad.c (ffffffff815ad07e)
Location: include/linux/scatterlist.h:139
Inline: True
Inline callers:
  - crypto/rsa-pkcs1pad.c:pkcs1pad_verify
  - crypto/rsa-pkcs1pad.c:pkcs1pad_decrypt
```
```
In crypto/gcm.c (ffffffff815b6314)
Location: include/linux/scatterlist.h:139
Inline: True
Inline callers:
  - crypto/gcm.c:crypto_rfc4106_crypt
  - crypto/gcm.c:crypto_rfc4106_crypt
  - crypto/gcm.c:crypto_gcm_init_common
  - crypto/gcm.c:crypto_gcm_init_common
```
```
In crypto/drbg.c (ffffffff815bbc54)
Location: include/linux/scatterlist.h:139
Inline: True
Inline callers:
  - crypto/drbg.c:drbg_kcapi_sym_ctr
  - crypto/drbg.c:drbg_kcapi_sym_ctr
```
```
In crypto/asymmetric_keys/public_key.c (ffffffff815bfa99)
Location: include/linux/scatterlist.h:139
Inline: True
Inline callers:
  - crypto/asymmetric_keys/public_key.c:public_key_verify_signature
  - crypto/asymmetric_keys/public_key.c:public_key_verify_signature
```
```
In lib/scatterlist.c (ffffffff8161397f)
Location: include/linux/scatterlist.h:139
Inline: True
Inline callers:
  - lib/scatterlist.c:sg_init_one
```
```
In drivers/scsi/scsi_lib.c (ffffffff818b64c3)
Location: include/linux/scatterlist.h:139
Inline: True
Inline callers:
  - drivers/scsi/scsi_lib.c:scsi_alloc_sgtables
```
```
In drivers/spi/spi.c (ffffffff818fd671)
Location: include/linux/scatterlist.h:139
Inline: True
Inline callers:
  - drivers/spi/spi.c:spi_map_buf
```
```
In drivers/usb/core/devio.c (ffffffff81951105)
Location: include/linux/scatterlist.h:139
Inline: True
Inline callers:
  - drivers/usb/core/devio.c:proc_do_submiturb
```
```
In drivers/mmc/core/sdio_ops.c (ffffffff81a47037)
Location: include/linux/scatterlist.h:139
Inline: True
Inline callers:
  - drivers/mmc/core/sdio_ops.c:mmc_io_rw_extended
```
```
In net/core/skbuff.c (ffffffff81a7fcbb)
Location: include/linux/scatterlist.h:139
Inline: True
Inline callers:
  - net/core/skbuff.c:__skb_to_sgvec
```
```
In net/ipv4/tcp.c (ffffffff81b5a439)
Location: include/linux/scatterlist.h:139
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_md5_hash_skb_data
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
In security/keys/encrypted-keys/encrypted.c (ffffffff815b4b5c)
Location: include/linux/scatterlist.h:156
Inline: True
```
```
In crypto/rsa-pkcs1pad.c (ffffffff816554a8)
Location: include/linux/scatterlist.h:156
Inline: True
Inline callers:
  - crypto/rsa-pkcs1pad.c:pkcs1pad_verify
  - crypto/rsa-pkcs1pad.c:pkcs1pad_decrypt
```
```
In crypto/gcm.c (ffffffff8165f5c1)
Location: include/linux/scatterlist.h:156
Inline: True
Inline callers:
  - crypto/gcm.c:crypto_rfc4106_crypt
  - crypto/gcm.c:crypto_rfc4106_crypt
  - crypto/gcm.c:crypto_gcm_init_common
  - crypto/gcm.c:crypto_gcm_init_common
```
```
In crypto/drbg.c (ffffffff816654c4)
Location: include/linux/scatterlist.h:156
Inline: True
Inline callers:
  - crypto/drbg.c:drbg_kcapi_sym_ctr
  - crypto/drbg.c:drbg_kcapi_sym_ctr
```
```
In crypto/asymmetric_keys/public_key.c (ffffffff81669fe7)
Location: include/linux/scatterlist.h:156
Inline: True
Inline callers:
  - crypto/asymmetric_keys/public_key.c:public_key_verify_signature
  - crypto/asymmetric_keys/public_key.c:public_key_verify_signature
```
```
In lib/scatterlist.c (ffffffff816df06c)
Location: include/linux/scatterlist.h:156
Inline: True
Inline callers:
  - lib/scatterlist.c:sg_init_one
```
```
In drivers/scsi/scsi_lib.c (ffffffff81a019c3)
Location: include/linux/scatterlist.h:156
Inline: True
Inline callers:
  - drivers/scsi/scsi_lib.c:scsi_alloc_sgtables
```
```
In drivers/spi/spi.c (ffffffff81a4ecbe)
Location: include/linux/scatterlist.h:156
Inline: True
Inline callers:
  - drivers/spi/spi.c:spi_map_buf
```
```
In drivers/usb/core/devio.c (ffffffff81aaa845)
Location: include/linux/scatterlist.h:156
Inline: True
Inline callers:
  - drivers/usb/core/devio.c:proc_do_submiturb
```
```
In drivers/mmc/core/sdio_ops.c (ffffffff81bb4e9d)
Location: include/linux/scatterlist.h:156
Inline: True
Inline callers:
  - drivers/mmc/core/sdio_ops.c:mmc_io_rw_extended
```
```
In net/core/skbuff.c (ffffffff81bf41d7)
Location: include/linux/scatterlist.h:156
Inline: True
Inline callers:
  - net/core/skbuff.c:__skb_to_sgvec
```
```
In net/ipv4/tcp.c (ffffffff81ce8f4d)
Location: include/linux/scatterlist.h:156
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_md5_hash_skb_data
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
In security/keys/encrypted-keys/encrypted.c (ffffffff8165fb3c)
Location: include/linux/scatterlist.h:159
Inline: True
```
```
In crypto/rsa-pkcs1pad.c (ffffffff8170f6d8)
Location: include/linux/scatterlist.h:159
Inline: True
Inline callers:
  - crypto/rsa-pkcs1pad.c:pkcs1pad_verify
  - crypto/rsa-pkcs1pad.c:pkcs1pad_decrypt
```
```
In crypto/gcm.c (ffffffff817193f1)
Location: include/linux/scatterlist.h:159
Inline: True
Inline callers:
  - crypto/gcm.c:crypto_rfc4106_crypt
  - crypto/gcm.c:crypto_rfc4106_crypt
  - crypto/gcm.c:crypto_gcm_init_common
  - crypto/gcm.c:crypto_gcm_init_common
```
```
In crypto/drbg.c (ffffffff817202d4)
Location: include/linux/scatterlist.h:159
Inline: True
Inline callers:
  - crypto/drbg.c:drbg_kcapi_sym_ctr
  - crypto/drbg.c:drbg_kcapi_sym_ctr
```
```
In crypto/asymmetric_keys/public_key.c (ffffffff817245b2)
Location: include/linux/scatterlist.h:159
Inline: True
Inline callers:
  - crypto/asymmetric_keys/public_key.c:public_key_verify_signature
  - crypto/asymmetric_keys/public_key.c:public_key_verify_signature
```
```
In lib/scatterlist.c (ffffffff817cf26c)
Location: include/linux/scatterlist.h:159
Inline: True
Inline callers:
  - lib/scatterlist.c:sg_init_one
```
```
In drivers/pci/p2pdma.c (ffffffff8191c786)
Location: include/linux/scatterlist.h:159
Inline: True
Inline callers:
  - drivers/pci/p2pdma.c:pci_p2pmem_alloc_sgl
```
```
In drivers/scsi/scsi_lib.c (ffffffff81b80023)
Location: include/linux/scatterlist.h:159
Inline: True
Inline callers:
  - drivers/scsi/scsi_lib.c:scsi_alloc_sgtables
```
```
In drivers/spi/spi.c (ffffffff81bd051d)
Location: include/linux/scatterlist.h:159
Inline: True
Inline callers:
  - drivers/spi/spi.c:spi_map_buf_attrs
```
```
In drivers/usb/core/devio.c (ffffffff81c31c4d)
Location: include/linux/scatterlist.h:159
Inline: True
Inline callers:
  - drivers/usb/core/devio.c:proc_do_submiturb
```
```
In drivers/mmc/core/sdio_ops.c (ffffffff81d5959d)
Location: include/linux/scatterlist.h:159
Inline: True
Inline callers:
  - drivers/mmc/core/sdio_ops.c:mmc_io_rw_extended
```
```
In net/core/skbuff.c (ffffffff81da1fe7)
Location: include/linux/scatterlist.h:159
Inline: True
Inline callers:
  - net/core/skbuff.c:__skb_to_sgvec
```
```
In net/ipv4/tcp.c (ffffffff81eac4cd)
Location: include/linux/scatterlist.h:159
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_md5_hash_skb_data
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
In security/keys/encrypted-keys/encrypted.c (ffffffff816984ac)
Location: include/linux/scatterlist.h:183
Inline: True
```
```
In crypto/rsa-pkcs1pad.c (ffffffff8174a748)
Location: include/linux/scatterlist.h:183
Inline: True
Inline callers:
  - crypto/rsa-pkcs1pad.c:pkcs1pad_verify
  - crypto/rsa-pkcs1pad.c:pkcs1pad_decrypt
```
```
In crypto/gcm.c (ffffffff81754d81)
Location: include/linux/scatterlist.h:183
Inline: True
Inline callers:
  - crypto/gcm.c:crypto_rfc4106_crypt
  - crypto/gcm.c:crypto_rfc4106_crypt
  - crypto/gcm.c:crypto_gcm_init_common
  - crypto/gcm.c:crypto_gcm_init_common
```
```
In crypto/drbg.c (ffffffff8175bbd4)
Location: include/linux/scatterlist.h:183
Inline: True
Inline callers:
  - crypto/drbg.c:drbg_kcapi_sym_ctr
  - crypto/drbg.c:drbg_kcapi_sym_ctr
```
```
In lib/scatterlist.c (ffffffff8180d71c)
Location: include/linux/scatterlist.h:183
Inline: True
Inline callers:
  - lib/scatterlist.c:sg_init_one
```
```
In drivers/pci/p2pdma.c (ffffffff8195fd46)
Location: include/linux/scatterlist.h:183
Inline: True
Inline callers:
  - drivers/pci/p2pdma.c:pci_p2pmem_alloc_sgl
```
```
In drivers/scsi/scsi_lib.c (ffffffff81bd4085)
Location: include/linux/scatterlist.h:183
Inline: True
Inline callers:
  - drivers/scsi/scsi_lib.c:scsi_alloc_sgtables
```
```
In drivers/spi/spi.c (ffffffff81c2819d)
Location: include/linux/scatterlist.h:183
Inline: True
Inline callers:
  - drivers/spi/spi.c:spi_map_buf_attrs
```
```
In drivers/net/virtio_net.c (ffffffff81c4e4ed)
Location: include/linux/scatterlist.h:183
Inline: True
Inline callers:
  - drivers/net/virtio_net.c:virtnet_commit_rss_command
  - drivers/net/virtio_net.c:virtnet_commit_rss_command
  - drivers/net/virtio_net.c:virtnet_commit_rss_command
  - drivers/net/virtio_net.c:virtnet_commit_rss_command
  - drivers/net/virtio_net.c:virtnet_set_rx_mode
  - drivers/net/virtio_net.c:virtnet_set_rx_mode
  - drivers/net/virtio_net.c:xmit_skb
  - drivers/net/virtio_net.c:add_recvbuf_big
  - drivers/net/virtio_net.c:add_recvbuf_big
  - drivers/net/virtio_net.c:add_recvbuf_big
  - drivers/net/virtio_net.c:__virtnet_xdp_xmit_one
```
```
In drivers/usb/core/devio.c (ffffffff81c98ecd)
Location: include/linux/scatterlist.h:183
Inline: True
Inline callers:
  - drivers/usb/core/devio.c:proc_do_submiturb
```
```
In drivers/mmc/core/sdio_ops.c (ffffffff81dc3f4a)
Location: include/linux/scatterlist.h:183
Inline: True
Inline callers:
  - drivers/mmc/core/sdio_ops.c:mmc_io_rw_extended
```
```
In net/core/skbuff.c (ffffffff81e10846)
Location: include/linux/scatterlist.h:183
Inline: True
Inline callers:
  - net/core/skbuff.c:__skb_to_sgvec
```
```
In net/ipv4/tcp.c (ffffffff81f0abd6)
Location: include/linux/scatterlist.h:183
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_md5_hash_skb_data
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
In security/keys/encrypted-keys/encrypted.c (ffffffff816d4b2c)
Location: include/linux/scatterlist.h:183
Inline: True
```
```
In crypto/rsa-pkcs1pad.c (ffffffff8178c308)
Location: include/linux/scatterlist.h:183
Inline: True
Inline callers:
  - crypto/rsa-pkcs1pad.c:pkcs1pad_verify
  - crypto/rsa-pkcs1pad.c:pkcs1pad_decrypt
```
```
In crypto/gcm.c (ffffffff81796d41)
Location: include/linux/scatterlist.h:183
Inline: True
Inline callers:
  - crypto/gcm.c:crypto_rfc4106_crypt
  - crypto/gcm.c:crypto_rfc4106_crypt
  - crypto/gcm.c:crypto_gcm_init_common
  - crypto/gcm.c:crypto_gcm_init_common
```
```
In crypto/drbg.c (ffffffff8179dad4)
Location: include/linux/scatterlist.h:183
Inline: True
Inline callers:
  - crypto/drbg.c:drbg_kcapi_sym_ctr
  - crypto/drbg.c:drbg_kcapi_sym_ctr
```
```
In lib/scatterlist.c (ffffffff818533cc)
Location: include/linux/scatterlist.h:183
Inline: True
Inline callers:
  - lib/scatterlist.c:sg_init_one
```
```
In drivers/pci/p2pdma.c (ffffffff819a9435)
Location: include/linux/scatterlist.h:183
Inline: True
Inline callers:
  - drivers/pci/p2pdma.c:pci_p2pmem_alloc_sgl
```
```
In drivers/scsi/scsi_lib.c (ffffffff81c28cf5)
Location: include/linux/scatterlist.h:183
Inline: True
Inline callers:
  - drivers/scsi/scsi_lib.c:scsi_alloc_sgtables
```
```
In drivers/spi/spi.c (ffffffff81cda8ed)
Location: include/linux/scatterlist.h:183
Inline: True
Inline callers:
  - drivers/spi/spi.c:spi_map_buf_attrs
```
```
In drivers/net/virtio_net.c (ffffffff81d045cd)
Location: include/linux/scatterlist.h:183
Inline: True
Inline callers:
  - drivers/net/virtio_net.c:virtnet_commit_rss_command
  - drivers/net/virtio_net.c:virtnet_commit_rss_command
  - drivers/net/virtio_net.c:virtnet_commit_rss_command
  - drivers/net/virtio_net.c:virtnet_commit_rss_command
  - drivers/net/virtio_net.c:virtnet_set_rx_mode
  - drivers/net/virtio_net.c:virtnet_set_rx_mode
  - drivers/net/virtio_net.c:xmit_skb
  - drivers/net/virtio_net.c:add_recvbuf_big
  - drivers/net/virtio_net.c:add_recvbuf_big
  - drivers/net/virtio_net.c:add_recvbuf_big
  - drivers/net/virtio_net.c:__virtnet_xdp_xmit_one
```
```
In drivers/usb/core/devio.c (ffffffff81d4da3d)
Location: include/linux/scatterlist.h:183
Inline: True
Inline callers:
  - drivers/usb/core/devio.c:proc_do_submiturb
```
```
In drivers/mmc/core/sdio_ops.c (ffffffff81e7c82a)
Location: include/linux/scatterlist.h:183
Inline: True
Inline callers:
  - drivers/mmc/core/sdio_ops.c:mmc_io_rw_extended
```
```
In net/core/skbuff.c (ffffffff81ecd366)
Location: include/linux/scatterlist.h:183
Inline: True
Inline callers:
  - net/core/skbuff.c:__skb_to_sgvec
```
```
In net/ipv4/tcp_sigpool.c (ffffffff8204c778)
Location: include/linux/scatterlist.h:183
Inline: True
Inline callers:
  - net/ipv4/tcp_sigpool.c:tcp_sigpool_hash_skb_data
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
In security/keys/encrypted-keys/encrypted.c (ffff80001053d510)
Location: include/linux/scatterlist.h:139
Inline: True
```
```
In crypto/rsa-pkcs1pad.c (ffff8000105c3ea0)
Location: include/linux/scatterlist.h:139
Inline: True
Inline callers:
  - crypto/rsa-pkcs1pad.c:pkcs1pad_sg_set_buf
```
```
In crypto/gcm.c (ffff8000105ccfb0)
Location: include/linux/scatterlist.h:139
Inline: True
Inline callers:
  - crypto/gcm.c:crypto_rfc4106_crypt
  - crypto/gcm.c:crypto_rfc4106_crypt
  - crypto/gcm.c:crypto_gcm_init_common
  - crypto/gcm.c:crypto_gcm_init_common
```
```
In crypto/drbg.c (ffff8000105d1d74)
Location: include/linux/scatterlist.h:139
Inline: True
Inline callers:
  - crypto/drbg.c:drbg_kcapi_sym_ctr
  - crypto/drbg.c:drbg_kcapi_sym_ctr
```
```
In crypto/asymmetric_keys/public_key.c (ffff8000105d5b10)
Location: include/linux/scatterlist.h:139
Inline: True
Inline callers:
  - crypto/asymmetric_keys/public_key.c:public_key_verify_signature
  - crypto/asymmetric_keys/public_key.c:public_key_verify_signature
```
```
In lib/scatterlist.c (ffff80001062c78c)
Location: include/linux/scatterlist.h:139
Inline: True
Inline callers:
  - lib/scatterlist.c:sg_init_one
```
```
In drivers/tty/serial/imx.c (ffff80001089abf4)
Location: include/linux/scatterlist.h:139
Inline: True
Inline callers:
  - drivers/tty/serial/imx.c:imx_uart_dma_tx
  - drivers/tty/serial/imx.c:imx_uart_dma_tx
```
```
In drivers/spi/spi.c (ffff8000109c85ec)
Location: include/linux/scatterlist.h:139
Inline: True
Inline callers:
  - drivers/spi/spi.c:spi_map_buf
```
```
In drivers/usb/core/devio.c (ffff800010a2ed70)
Location: include/linux/scatterlist.h:139
Inline: True
Inline callers:
  - drivers/usb/core/devio.c:proc_do_submiturb
```
```
In drivers/mmc/core/sdio_ops.c (ffff800010b3ac44)
Location: include/linux/scatterlist.h:139
Inline: True
Inline callers:
  - drivers/mmc/core/sdio_ops.c:mmc_io_rw_extended
```
```
In net/core/skbuff.c (ffff800010bb2a28)
Location: include/linux/scatterlist.h:139
Inline: True
Inline callers:
  - net/core/skbuff.c:__skb_to_sgvec
```
```
In net/ipv4/tcp.c (ffff800010c6faa0)
Location: include/linux/scatterlist.h:139
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_md5_hash_skb_data
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
In security/keys/encrypted-keys/encrypted.c (c06f2edc)
Location: include/linux/scatterlist.h:139
Inline: True
```
```
In crypto/rsa-pkcs1pad.c (c077176c)
Location: include/linux/scatterlist.h:139
Inline: True
Inline callers:
  - crypto/rsa-pkcs1pad.c:pkcs1pad_verify
  - crypto/rsa-pkcs1pad.c:pkcs1pad_decrypt
```
```
In crypto/gcm.c (c077a81c)
Location: include/linux/scatterlist.h:139
Inline: True
Inline callers:
  - crypto/gcm.c:crypto_rfc4106_crypt
  - crypto/gcm.c:crypto_rfc4106_crypt
  - crypto/gcm.c:crypto_rfc4106_crypt
  - crypto/gcm.c:crypto_gcm_init_common
  - crypto/gcm.c:crypto_gcm_init_common
  - crypto/gcm.c:crypto_gcm_init_common
```
```
In crypto/drbg.c (c077f5fc)
Location: include/linux/scatterlist.h:139
Inline: True
Inline callers:
  - crypto/drbg.c:drbg_kcapi_sym_ctr
  - crypto/drbg.c:drbg_kcapi_sym_ctr
  - crypto/drbg.c:drbg_kcapi_sym_ctr
```
```
In crypto/asymmetric_keys/public_key.c (c07835e4)
Location: include/linux/scatterlist.h:139
Inline: True
Inline callers:
  - crypto/asymmetric_keys/public_key.c:public_key_verify_signature
  - crypto/asymmetric_keys/public_key.c:public_key_verify_signature
  - crypto/asymmetric_keys/public_key.c:public_key_verify_signature
```
```
In lib/scatterlist.c (c07d3a24)
Location: include/linux/scatterlist.h:139
Inline: True
Inline callers:
  - lib/scatterlist.c:sg_init_one
```
```
In drivers/tty/serial/imx.c (c0997b18)
Location: include/linux/scatterlist.h:139
Inline: True
Inline callers:
  - drivers/tty/serial/imx.c:imx_uart_dma_tx
  - drivers/tty/serial/imx.c:imx_uart_dma_tx
  - drivers/tty/serial/imx.c:imx_uart_dma_tx
```
```
In drivers/spi/spi.c (c0ab2248)
Location: include/linux/scatterlist.h:139
Inline: True
Inline callers:
  - drivers/spi/spi.c:spi_map_buf
```
```
In drivers/usb/core/devio.c (c0b04bbc)
Location: include/linux/scatterlist.h:139
Inline: True
Inline callers:
  - drivers/usb/core/devio.c:proc_do_submiturb
```
```
In drivers/mmc/core/sdio_ops.c (c0c155e4)
Location: include/linux/scatterlist.h:139
Inline: True
Inline callers:
  - drivers/mmc/core/sdio_ops.c:mmc_io_rw_extended
```
```
In net/core/skbuff.c (c0cd0f4c)
Location: include/linux/scatterlist.h:139
Inline: True
Inline callers:
  - net/core/skbuff.c:__skb_to_sgvec
```
```
In net/ipv4/tcp.c (c0d7eeb8)
Location: include/linux/scatterlist.h:139
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_md5_hash_skb_data
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
In security/keys/encrypted-keys/encrypted.c (c00000000068c9f8)
Location: include/linux/scatterlist.h:139
Inline: True
```
```
In crypto/rsa-pkcs1pad.c (c00000000074c9c4)
Location: include/linux/scatterlist.h:139
Inline: True
Inline callers:
  - crypto/rsa-pkcs1pad.c:pkcs1pad_sg_set_buf
```
```
In crypto/gcm.c (c000000000757e10)
Location: include/linux/scatterlist.h:139
Inline: True
Inline callers:
  - crypto/gcm.c:crypto_rfc4106_crypt
  - crypto/gcm.c:crypto_rfc4106_crypt
  - crypto/gcm.c:crypto_gcm_init_common
  - crypto/gcm.c:crypto_gcm_init_common
```
```
In crypto/drbg.c (c00000000075ecd4)
Location: include/linux/scatterlist.h:139
Inline: True
Inline callers:
  - crypto/drbg.c:drbg_kcapi_sym_ctr
  - crypto/drbg.c:drbg_kcapi_sym_ctr
```
```
In crypto/asymmetric_keys/public_key.c (c0000000007642c0)
Location: include/linux/scatterlist.h:139
Inline: True
Inline callers:
  - crypto/asymmetric_keys/public_key.c:public_key_verify_signature
  - crypto/asymmetric_keys/public_key.c:public_key_verify_signature
```
```
In lib/scatterlist.c (c0000000007cf314)
Location: include/linux/scatterlist.h:139
Inline: True
Inline callers:
  - lib/scatterlist.c:sg_init_one
```
```
In drivers/spi/spi.c (c000000000a89d90)
Location: include/linux/scatterlist.h:139
Inline: True
Inline callers:
  - drivers/spi/spi.c:spi_map_buf
```
```
In drivers/usb/core/devio.c (c000000000aee200)
Location: include/linux/scatterlist.h:139
Inline: True
Inline callers:
  - drivers/usb/core/devio.c:proc_do_submiturb
```
```
In drivers/mmc/core/sdio_ops.c (c000000000c37664)
Location: include/linux/scatterlist.h:139
Inline: True
Inline callers:
  - drivers/mmc/core/sdio_ops.c:mmc_io_rw_extended
```
```
In net/core/skbuff.c (c000000000c8ab88)
Location: include/linux/scatterlist.h:139
Inline: True
Inline callers:
  - net/core/skbuff.c:__skb_to_sgvec
```
```
In net/ipv4/tcp.c (c000000000d765e8)
Location: include/linux/scatterlist.h:139
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_md5_hash_skb_data
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
In security/keys/encrypted-keys/encrypted.c (ffffffe00039a942)
Location: include/linux/scatterlist.h:139
Inline: True
```
```
In crypto/rsa-pkcs1pad.c (ffffffe000407e60)
Location: include/linux/scatterlist.h:139
Inline: True
Inline callers:
  - crypto/rsa-pkcs1pad.c:pkcs1pad_sg_set_buf
```
```
In crypto/gcm.c (ffffffe00040ff98)
Location: include/linux/scatterlist.h:139
Inline: True
Inline callers:
  - crypto/gcm.c:crypto_rfc4106_crypt
  - crypto/gcm.c:crypto_rfc4106_crypt
  - crypto/gcm.c:crypto_gcm_init_common
  - crypto/gcm.c:crypto_gcm_init_common
```
```
In crypto/drbg.c (ffffffe000415502)
Location: include/linux/scatterlist.h:139
Inline: True
Inline callers:
  - crypto/drbg.c:drbg_kcapi_sym_ctr
  - crypto/drbg.c:drbg_kcapi_sym_ctr
```
```
In crypto/asymmetric_keys/public_key.c (ffffffe000419c82)
Location: include/linux/scatterlist.h:139
Inline: True
Inline callers:
  - crypto/asymmetric_keys/public_key.c:public_key_verify_signature
  - crypto/asymmetric_keys/public_key.c:public_key_verify_signature
```
```
In lib/scatterlist.c (ffffffe00045c2da)
Location: include/linux/scatterlist.h:139
Inline: True
Inline callers:
  - lib/scatterlist.c:sg_init_one
```
```
In drivers/spi/spi.c (ffffffe0006189fe)
Location: include/linux/scatterlist.h:139
Inline: True
Inline callers:
  - drivers/spi/spi.c:spi_map_buf
```
```
In drivers/usb/core/devio.c (ffffffe00064f050)
Location: include/linux/scatterlist.h:139
Inline: True
Inline callers:
  - drivers/usb/core/devio.c:proc_do_submiturb
```
```
In drivers/mmc/core/sdio_ops.c (ffffffe00071257c)
Location: include/linux/scatterlist.h:139
Inline: True
Inline callers:
  - drivers/mmc/core/sdio_ops.c:mmc_io_rw_extended
```
```
In net/core/skbuff.c (ffffffe000743e36)
Location: include/linux/scatterlist.h:139
Inline: True
Inline callers:
  - net/core/skbuff.c:__skb_to_sgvec
```
```
In net/ipv4/tcp.c (ffffffe0007d4db0)
Location: include/linux/scatterlist.h:139
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_md5_hash_skb_data
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
In security/keys/encrypted-keys/encrypted.c (ffffffff8144a240)
Location: include/linux/scatterlist.h:139
Inline: True
```
```
In crypto/rsa-pkcs1pad.c (ffffffff814c11be)
Location: include/linux/scatterlist.h:139
Inline: True
Inline callers:
  - crypto/rsa-pkcs1pad.c:pkcs1pad_verify
  - crypto/rsa-pkcs1pad.c:pkcs1pad_decrypt
```
```
In crypto/gcm.c (ffffffff814c91bb)
Location: include/linux/scatterlist.h:139
Inline: True
Inline callers:
  - crypto/gcm.c:crypto_rfc4106_crypt
  - crypto/gcm.c:crypto_rfc4106_crypt
  - crypto/gcm.c:crypto_rfc4106_crypt
  - crypto/gcm.c:crypto_rfc4106_crypt
  - crypto/gcm.c:crypto_gcm_init_common
  - crypto/gcm.c:crypto_gcm_init_common
  - crypto/gcm.c:crypto_gcm_init_common
  - crypto/gcm.c:crypto_gcm_init_common
```
```
In crypto/drbg.c (ffffffff814ce481)
Location: include/linux/scatterlist.h:139
Inline: True
Inline callers:
  - crypto/drbg.c:drbg_kcapi_sym_ctr
  - crypto/drbg.c:drbg_kcapi_sym_ctr
  - crypto/drbg.c:drbg_kcapi_sym_ctr
  - crypto/drbg.c:drbg_kcapi_sym_ctr
```
```
In crypto/asymmetric_keys/public_key.c (ffffffff814d2232)
Location: include/linux/scatterlist.h:139
Inline: True
Inline callers:
  - crypto/asymmetric_keys/public_key.c:public_key_verify_signature
  - crypto/asymmetric_keys/public_key.c:public_key_verify_signature
  - crypto/asymmetric_keys/public_key.c:public_key_verify_signature
  - crypto/asymmetric_keys/public_key.c:public_key_verify_signature
```
```
In lib/scatterlist.c (ffffffff8151b6fc)
Location: include/linux/scatterlist.h:139
Inline: True
Inline callers:
  - lib/scatterlist.c:sg_init_one
```
```
In drivers/spi/spi.c (ffffffff81779a45)
Location: include/linux/scatterlist.h:139
Inline: True
Inline callers:
  - drivers/spi/spi.c:spi_map_buf
```
```
In drivers/usb/core/devio.c (ffffffff817b5660)
Location: include/linux/scatterlist.h:139
Inline: True
Inline callers:
  - drivers/usb/core/devio.c:proc_do_submiturb
```
```
In drivers/mmc/core/sdio_ops.c (ffffffff8188444d)
Location: include/linux/scatterlist.h:139
Inline: True
Inline callers:
  - drivers/mmc/core/sdio_ops.c:mmc_io_rw_extended
```
```
In net/core/skbuff.c (ffffffff818b994f)
Location: include/linux/scatterlist.h:139
Inline: True
Inline callers:
  - net/core/skbuff.c:__skb_to_sgvec
```
```
In net/ipv4/tcp.c (ffffffff8195dca0)
Location: include/linux/scatterlist.h:139
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_md5_hash_skb_data
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
In security/keys/encrypted-keys/encrypted.c (ffffffff8143ac90)
Location: include/linux/scatterlist.h:139
Inline: True
```
```
In crypto/rsa-pkcs1pad.c (ffffffff814b1bde)
Location: include/linux/scatterlist.h:139
Inline: True
Inline callers:
  - crypto/rsa-pkcs1pad.c:pkcs1pad_verify
  - crypto/rsa-pkcs1pad.c:pkcs1pad_decrypt
```
```
In crypto/gcm.c (ffffffff814b9bdb)
Location: include/linux/scatterlist.h:139
Inline: True
Inline callers:
  - crypto/gcm.c:crypto_rfc4106_crypt
  - crypto/gcm.c:crypto_rfc4106_crypt
  - crypto/gcm.c:crypto_rfc4106_crypt
  - crypto/gcm.c:crypto_rfc4106_crypt
  - crypto/gcm.c:crypto_gcm_init_common
  - crypto/gcm.c:crypto_gcm_init_common
  - crypto/gcm.c:crypto_gcm_init_common
  - crypto/gcm.c:crypto_gcm_init_common
```
```
In crypto/drbg.c (ffffffff814beea1)
Location: include/linux/scatterlist.h:139
Inline: True
Inline callers:
  - crypto/drbg.c:drbg_kcapi_sym_ctr
  - crypto/drbg.c:drbg_kcapi_sym_ctr
  - crypto/drbg.c:drbg_kcapi_sym_ctr
  - crypto/drbg.c:drbg_kcapi_sym_ctr
```
```
In crypto/asymmetric_keys/public_key.c (ffffffff814c2c52)
Location: include/linux/scatterlist.h:139
Inline: True
Inline callers:
  - crypto/asymmetric_keys/public_key.c:public_key_verify_signature
  - crypto/asymmetric_keys/public_key.c:public_key_verify_signature
  - crypto/asymmetric_keys/public_key.c:public_key_verify_signature
  - crypto/asymmetric_keys/public_key.c:public_key_verify_signature
```
```
In lib/scatterlist.c (ffffffff8150b9ec)
Location: include/linux/scatterlist.h:139
Inline: True
Inline callers:
  - lib/scatterlist.c:sg_init_one
```
```
In drivers/spi/spi.c (ffffffff817597f5)
Location: include/linux/scatterlist.h:139
Inline: True
Inline callers:
  - drivers/spi/spi.c:spi_map_buf
```
```
In drivers/usb/core/devio.c (ffffffff817a7090)
Location: include/linux/scatterlist.h:139
Inline: True
Inline callers:
  - drivers/usb/core/devio.c:proc_do_submiturb
```
```
In net/core/skbuff.c (ffffffff8187389f)
Location: include/linux/scatterlist.h:139
Inline: True
Inline callers:
  - net/core/skbuff.c:__skb_to_sgvec
```
```
In net/ipv4/tcp.c (ffffffff81917790)
Location: include/linux/scatterlist.h:139
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_md5_hash_skb_data
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
In security/keys/encrypted-keys/encrypted.c (ffffffff814462e0)
Location: include/linux/scatterlist.h:139
Inline: True
```
```
In crypto/rsa-pkcs1pad.c (ffffffff814bd24e)
Location: include/linux/scatterlist.h:139
Inline: True
Inline callers:
  - crypto/rsa-pkcs1pad.c:pkcs1pad_verify
  - crypto/rsa-pkcs1pad.c:pkcs1pad_decrypt
```
```
In crypto/gcm.c (ffffffff814c524b)
Location: include/linux/scatterlist.h:139
Inline: True
Inline callers:
  - crypto/gcm.c:crypto_rfc4106_crypt
  - crypto/gcm.c:crypto_rfc4106_crypt
  - crypto/gcm.c:crypto_rfc4106_crypt
  - crypto/gcm.c:crypto_rfc4106_crypt
  - crypto/gcm.c:crypto_gcm_init_common
  - crypto/gcm.c:crypto_gcm_init_common
  - crypto/gcm.c:crypto_gcm_init_common
  - crypto/gcm.c:crypto_gcm_init_common
```
```
In crypto/drbg.c (ffffffff814ca511)
Location: include/linux/scatterlist.h:139
Inline: True
Inline callers:
  - crypto/drbg.c:drbg_kcapi_sym_ctr
  - crypto/drbg.c:drbg_kcapi_sym_ctr
  - crypto/drbg.c:drbg_kcapi_sym_ctr
  - crypto/drbg.c:drbg_kcapi_sym_ctr
```
```
In crypto/asymmetric_keys/public_key.c (ffffffff814ce2c2)
Location: include/linux/scatterlist.h:139
Inline: True
Inline callers:
  - crypto/asymmetric_keys/public_key.c:public_key_verify_signature
  - crypto/asymmetric_keys/public_key.c:public_key_verify_signature
  - crypto/asymmetric_keys/public_key.c:public_key_verify_signature
  - crypto/asymmetric_keys/public_key.c:public_key_verify_signature
```
```
In lib/scatterlist.c (ffffffff8151778c)
Location: include/linux/scatterlist.h:139
Inline: True
Inline callers:
  - lib/scatterlist.c:sg_init_one
```
```
In drivers/spi/spi.c (ffffffff817a9de5)
Location: include/linux/scatterlist.h:139
Inline: True
Inline callers:
  - drivers/spi/spi.c:spi_map_buf
```
```
In drivers/usb/core/devio.c (ffffffff817f2100)
Location: include/linux/scatterlist.h:139
Inline: True
Inline callers:
  - drivers/usb/core/devio.c:proc_do_submiturb
```
```
In drivers/mmc/core/sdio_ops.c (ffffffff818d58ed)
Location: include/linux/scatterlist.h:139
Inline: True
Inline callers:
  - drivers/mmc/core/sdio_ops.c:mmc_io_rw_extended
```
```
In net/core/skbuff.c (ffffffff8190a94f)
Location: include/linux/scatterlist.h:139
Inline: True
Inline callers:
  - net/core/skbuff.c:__skb_to_sgvec
```
```
In net/ipv4/tcp.c (ffffffff819c8470)
Location: include/linux/scatterlist.h:139
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_md5_hash_skb_data
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
In security/keys/encrypted-keys/encrypted.c (ffffffff8145d610)
Location: include/linux/scatterlist.h:139
Inline: True
```
```
In crypto/rsa-pkcs1pad.c (ffffffff814d5d1e)
Location: include/linux/scatterlist.h:139
Inline: True
Inline callers:
  - crypto/rsa-pkcs1pad.c:pkcs1pad_verify
  - crypto/rsa-pkcs1pad.c:pkcs1pad_decrypt
```
```
In crypto/gcm.c (ffffffff814ddd1b)
Location: include/linux/scatterlist.h:139
Inline: True
Inline callers:
  - crypto/gcm.c:crypto_rfc4106_crypt
  - crypto/gcm.c:crypto_rfc4106_crypt
  - crypto/gcm.c:crypto_rfc4106_crypt
  - crypto/gcm.c:crypto_rfc4106_crypt
  - crypto/gcm.c:crypto_gcm_init_common
  - crypto/gcm.c:crypto_gcm_init_common
  - crypto/gcm.c:crypto_gcm_init_common
  - crypto/gcm.c:crypto_gcm_init_common
```
```
In crypto/drbg.c (ffffffff814e2fe1)
Location: include/linux/scatterlist.h:139
Inline: True
Inline callers:
  - crypto/drbg.c:drbg_kcapi_sym_ctr
  - crypto/drbg.c:drbg_kcapi_sym_ctr
  - crypto/drbg.c:drbg_kcapi_sym_ctr
  - crypto/drbg.c:drbg_kcapi_sym_ctr
```
```
In crypto/asymmetric_keys/public_key.c (ffffffff814e6d92)
Location: include/linux/scatterlist.h:139
Inline: True
Inline callers:
  - crypto/asymmetric_keys/public_key.c:public_key_verify_signature
  - crypto/asymmetric_keys/public_key.c:public_key_verify_signature
  - crypto/asymmetric_keys/public_key.c:public_key_verify_signature
  - crypto/asymmetric_keys/public_key.c:public_key_verify_signature
```
```
In lib/scatterlist.c (ffffffff81530f2c)
Location: include/linux/scatterlist.h:139
Inline: True
Inline callers:
  - lib/scatterlist.c:sg_init_one
```
```
In drivers/spi/spi.c (ffffffff817c3c75)
Location: include/linux/scatterlist.h:139
Inline: True
Inline callers:
  - drivers/spi/spi.c:spi_map_buf
```
```
In drivers/usb/core/devio.c (ffffffff8180c340)
Location: include/linux/scatterlist.h:139
Inline: True
Inline callers:
  - drivers/usb/core/devio.c:proc_do_submiturb
```
```
In drivers/mmc/core/sdio_ops.c (ffffffff818f240d)
Location: include/linux/scatterlist.h:139
Inline: True
Inline callers:
  - drivers/mmc/core/sdio_ops.c:mmc_io_rw_extended
```
```
In net/core/skbuff.c (ffffffff8192ba4f)
Location: include/linux/scatterlist.h:139
Inline: True
Inline callers:
  - net/core/skbuff.c:__skb_to_sgvec
```
```
In net/ipv4/tcp.c (ffffffff819d1fc0)
Location: include/linux/scatterlist.h:139
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_md5_hash_skb_data
```
</details>
</li>
</ul>

## Differences
