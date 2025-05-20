# Function: <code>sg_set_page</code>

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
In fs/ext4/crypto.c (ffffffff812e4ed1)
Location: include/linux/scatterlist.h:112
Inline: True
Inline callers:
  - fs/ext4/crypto.c:ext4_page_crypto
  - fs/ext4/crypto.c:ext4_page_crypto
```
```
In fs/ecryptfs/crypto.c (ffffffff813057b1)
Location: include/linux/scatterlist.h:112
Inline: True
Inline callers:
  - fs/ecryptfs/crypto.c:crypt_extent
  - fs/ecryptfs/crypto.c:crypt_extent
  - fs/ecryptfs/crypto.c:virt_to_scatterlist
```
```
In security/keys/encrypted-keys/encrypted.c (ffffffff81338fc5)
Location: include/linux/scatterlist.h:112
Inline: True
```
```
In crypto/scatterwalk.c (ffffffff8139eb19)
Location: include/linux/scatterlist.h:112
Inline: True
Inline callers:
  - crypto/scatterwalk.c:scatterwalk_ffwd
```
```
In crypto/eseqiv.c (ffffffff813a2619)
Location: include/linux/scatterlist.h:112
Inline: True
Inline callers:
  - crypto/eseqiv.c:eseqiv_givencrypt
  - crypto/eseqiv.c:eseqiv_givencrypt
```
```
In block/blk-merge.c (ffffffff813bff7f)
Location: include/linux/scatterlist.h:112
Inline: True
Inline callers:
  - block/blk-merge.c:blk_rq_map_sg
  - block/blk-merge.c:blk_rq_map_sg
  - block/blk-merge.c:blk_rq_map_sg
```
```
In block/blk-integrity.c (ffffffff813e7ce7)
Location: include/linux/scatterlist.h:112
Inline: True
Inline callers:
  - block/blk-integrity.c:blk_rq_map_integrity_sg
```
```
In lib/scatterlist.c (ffffffff813f9f0f)
Location: include/linux/scatterlist.h:112
Inline: True
Inline callers:
  - lib/scatterlist.c:sg_init_one
  - lib/scatterlist.c:sg_alloc_table_from_pages
```
```
In lib/kfifo.c (ffffffff813febd9)
Location: include/linux/scatterlist.h:112
Inline: True
```
```
In drivers/char/virtio_console.c (ffffffff8151755f)
Location: include/linux/scatterlist.h:112
Inline: True
Inline callers:
  - drivers/char/virtio_console.c:pipe_to_sg
  - drivers/char/virtio_console.c:pipe_to_sg
```
```
In drivers/char/agp/intel-gtt.c (ffffffff8152223a)
Location: include/linux/scatterlist.h:112
Inline: True
Inline callers:
  - drivers/char/agp/intel-gtt.c:intel_fake_agp_insert_entries
```
```
In drivers/base/dma-mapping.c (ffffffff8155d940)
Location: include/linux/scatterlist.h:112
Inline: True
Inline callers:
  - drivers/base/dma-mapping.c:dma_common_get_sgtable
```
```
In drivers/spi/spi.c (ffffffff815e7801)
Location: include/linux/scatterlist.h:112
Inline: True
```
```
In drivers/net/virtio_net.c (ffffffff815f2202)
Location: include/linux/scatterlist.h:112
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
Location: include/linux/scatterlist.h:112
Inline: True
Inline callers:
  - drivers/usb/core/devio.c:proc_do_submiturb
```
```
In drivers/mmc/core/sdio_ops.c (ffffffff816ca4a0)
Location: include/linux/scatterlist.h:112
Inline: True
Inline callers:
  - drivers/mmc/core/sdio_ops.c:mmc_io_rw_extended
```
```
In net/core/skbuff.c (ffffffff81705750)
Location: include/linux/scatterlist.h:112
Inline: True
Inline callers:
  - net/core/skbuff.c:__skb_to_sgvec
  - net/core/skbuff.c:__skb_to_sgvec
```
```
In net/ipv4/tcp.c (ffffffff81766cc6)
Location: include/linux/scatterlist.h:112
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_md5_hash_skb_data
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
In fs/crypto/crypto.c (ffffffff812889f0)
Location: include/linux/scatterlist.h:112
Inline: True
```
```
In fs/ecryptfs/crypto.c (ffffffff81339a52)
Location: include/linux/scatterlist.h:112
Inline: True
Inline callers:
  - fs/ecryptfs/crypto.c:crypt_extent
  - fs/ecryptfs/crypto.c:crypt_extent
  - fs/ecryptfs/crypto.c:virt_to_scatterlist
```
```
In security/keys/encrypted-keys/encrypted.c (ffffffff8136e599)
Location: include/linux/scatterlist.h:112
Inline: True
```
```
In crypto/scatterwalk.c (ffffffff813db8dc)
Location: include/linux/scatterlist.h:112
Inline: True
```
```
In crypto/rsa-pkcs1pad.c (ffffffff813e0f11)
Location: include/linux/scatterlist.h:112
Inline: True
Inline callers:
  - crypto/rsa-pkcs1pad.c:pkcs1pad_sg_set_buf
```
```
In block/blk-merge.c (ffffffff81404018)
Location: include/linux/scatterlist.h:112
Inline: True
Inline callers:
  - block/blk-merge.c:blk_rq_map_sg
  - block/blk-merge.c:blk_rq_map_sg
  - block/blk-merge.c:blk_rq_map_sg
```
```
In block/blk-integrity.c (ffffffff8142df79)
Location: include/linux/scatterlist.h:112
Inline: True
Inline callers:
  - block/blk-integrity.c:blk_rq_map_integrity_sg
```
```
In lib/scatterlist.c (ffffffff8144188a)
Location: include/linux/scatterlist.h:112
Inline: True
Inline callers:
  - lib/scatterlist.c:sg_alloc_table_from_pages
  - lib/scatterlist.c:sg_init_one
```
```
In lib/kfifo.c (ffffffff81445e32)
Location: include/linux/scatterlist.h:112
Inline: True
```
```
In drivers/char/virtio_console.c (ffffffff8156a325)
Location: include/linux/scatterlist.h:112
Inline: True
Inline callers:
  - drivers/char/virtio_console.c:pipe_to_sg
  - drivers/char/virtio_console.c:pipe_to_sg
```
```
In drivers/char/agp/intel-gtt.c (ffffffff815750a0)
Location: include/linux/scatterlist.h:112
Inline: True
Inline callers:
  - drivers/char/agp/intel-gtt.c:intel_fake_agp_insert_entries
```
```
In drivers/base/dma-mapping.c (ffffffff815b1b8a)
Location: include/linux/scatterlist.h:112
Inline: True
Inline callers:
  - drivers/base/dma-mapping.c:dma_common_get_sgtable
```
```
In drivers/spi/spi.c (ffffffff816458d5)
Location: include/linux/scatterlist.h:112
Inline: True
```
```
In drivers/net/virtio_net.c (ffffffff81651b45)
Location: include/linux/scatterlist.h:112
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
In drivers/usb/core/devio.c (ffffffff8167c1cc)
Location: include/linux/scatterlist.h:112
Inline: True
Inline callers:
  - drivers/usb/core/devio.c:proc_do_submiturb
```
```
In drivers/mmc/core/sdio_ops.c (ffffffff8172d456)
Location: include/linux/scatterlist.h:112
Inline: True
Inline callers:
  - drivers/mmc/core/sdio_ops.c:mmc_io_rw_extended
```
```
In net/core/skbuff.c (ffffffff8176c4c7)
Location: include/linux/scatterlist.h:112
Inline: True
Inline callers:
  - net/core/skbuff.c:__skb_to_sgvec
  - net/core/skbuff.c:__skb_to_sgvec
```
```
In net/ipv4/tcp.c (ffffffff817d3220)
Location: include/linux/scatterlist.h:112
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_md5_hash_skb_data
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
In fs/crypto/crypto.c (ffffffff8129d629)
Location: include/linux/scatterlist.h:112
Inline: True
```
```
In fs/ecryptfs/crypto.c (ffffffff8134f7f2)
Location: include/linux/scatterlist.h:112
Inline: True
Inline callers:
  - fs/ecryptfs/crypto.c:crypt_extent
  - fs/ecryptfs/crypto.c:crypt_extent
  - fs/ecryptfs/crypto.c:virt_to_scatterlist
```
```
In security/keys/encrypted-keys/encrypted.c (ffffffff813851b2)
Location: include/linux/scatterlist.h:112
Inline: True
```
```
In crypto/scatterwalk.c (ffffffff813f321c)
Location: include/linux/scatterlist.h:112
Inline: True
```
```
In crypto/rsa-pkcs1pad.c (ffffffff813fa1ad)
Location: include/linux/scatterlist.h:112
Inline: True
Inline callers:
  - crypto/rsa-pkcs1pad.c:pkcs1pad_verify
  - crypto/rsa-pkcs1pad.c:pkcs1pad_decrypt
  - crypto/rsa-pkcs1pad.c:pkcs1pad_encrypt
```
```
In crypto/scompress.c (ffffffff813fabc3)
Location: include/linux/scatterlist.h:112
Inline: True
Inline callers:
  - crypto/scompress.c:scomp_acomp_comp_decomp
```
```
In block/blk-merge.c (ffffffff8141e46f)
Location: include/linux/scatterlist.h:112
Inline: True
Inline callers:
  - block/blk-merge.c:blk_rq_map_sg
  - block/blk-merge.c:blk_rq_map_sg
  - block/blk-merge.c:blk_rq_map_sg
  - block/blk-merge.c:blk_rq_map_sg
```
```
In block/blk-integrity.c (ffffffff81447d31)
Location: include/linux/scatterlist.h:112
Inline: True
Inline callers:
  - block/blk-integrity.c:blk_rq_map_integrity_sg
```
```
In lib/scatterlist.c (ffffffff8145ea94)
Location: include/linux/scatterlist.h:112
Inline: True
Inline callers:
  - lib/scatterlist.c:sg_alloc_table_from_pages
  - lib/scatterlist.c:sg_init_one
```
```
In lib/kfifo.c (ffffffff814645b2)
Location: include/linux/scatterlist.h:112
Inline: True
```
```
In drivers/char/virtio_console.c (ffffffff81596a64)
Location: include/linux/scatterlist.h:112
Inline: True
Inline callers:
  - drivers/char/virtio_console.c:pipe_to_sg
  - drivers/char/virtio_console.c:pipe_to_sg
```
```
In drivers/char/agp/intel-gtt.c (ffffffff815a16b2)
Location: include/linux/scatterlist.h:112
Inline: True
Inline callers:
  - drivers/char/agp/intel-gtt.c:intel_fake_agp_insert_entries
```
```
In drivers/base/dma-mapping.c (ffffffff815e1156)
Location: include/linux/scatterlist.h:112
Inline: True
```
```
In drivers/spi/spi.c (ffffffff816770b6)
Location: include/linux/scatterlist.h:112
Inline: True
```
```
In drivers/usb/core/devio.c (ffffffff816aa149)
Location: include/linux/scatterlist.h:112
Inline: True
Inline callers:
  - drivers/usb/core/devio.c:proc_do_submiturb
```
```
In drivers/mmc/core/sdio_ops.c (ffffffff817603dc)
Location: include/linux/scatterlist.h:112
Inline: True
Inline callers:
  - drivers/mmc/core/sdio_ops.c:mmc_io_rw_extended
```
```
In net/core/skbuff.c (ffffffff81799f09)
Location: include/linux/scatterlist.h:112
Inline: True
Inline callers:
  - net/core/skbuff.c:__skb_to_sgvec
  - net/core/skbuff.c:__skb_to_sgvec
```
```
In net/ipv4/tcp.c (ffffffff81804b02)
Location: include/linux/scatterlist.h:112
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_md5_hash_skb_data
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
In fs/crypto/crypto.c (ffffffff812ac393)
Location: include/linux/scatterlist.h:112
Inline: True
Inline callers:
  - fs/crypto/crypto.c:fscrypt_do_page_crypto
  - fs/crypto/crypto.c:fscrypt_do_page_crypto
```
```
In fs/ecryptfs/crypto.c (ffffffff813642a2)
Location: include/linux/scatterlist.h:112
Inline: True
Inline callers:
  - fs/ecryptfs/crypto.c:crypt_extent
  - fs/ecryptfs/crypto.c:crypt_extent
  - fs/ecryptfs/crypto.c:virt_to_scatterlist
```
```
In security/keys/encrypted-keys/encrypted.c (ffffffff813998af)
Location: include/linux/scatterlist.h:112
Inline: True
```
```
In crypto/scatterwalk.c (ffffffff813ff53c)
Location: include/linux/scatterlist.h:112
Inline: True
```
```
In crypto/rsa-pkcs1pad.c (ffffffff814069bd)
Location: include/linux/scatterlist.h:112
Inline: True
Inline callers:
  - crypto/rsa-pkcs1pad.c:pkcs1pad_verify
  - crypto/rsa-pkcs1pad.c:pkcs1pad_decrypt
  - crypto/rsa-pkcs1pad.c:pkcs1pad_encrypt
```
```
In crypto/scompress.c (ffffffff814075de)
Location: include/linux/scatterlist.h:112
Inline: True
Inline callers:
  - crypto/scompress.c:scomp_acomp_comp_decomp
```
```
In block/blk-merge.c (ffffffff8142bc6f)
Location: include/linux/scatterlist.h:112
Inline: True
Inline callers:
  - block/blk-merge.c:blk_rq_map_sg
  - block/blk-merge.c:blk_rq_map_sg
  - block/blk-merge.c:blk_rq_map_sg
  - block/blk-merge.c:blk_rq_map_sg
```
```
In block/blk-integrity.c (ffffffff81456671)
Location: include/linux/scatterlist.h:112
Inline: True
Inline callers:
  - block/blk-integrity.c:blk_rq_map_integrity_sg
```
```
In lib/scatterlist.c (ffffffff81463d71)
Location: include/linux/scatterlist.h:112
Inline: True
Inline callers:
  - lib/scatterlist.c:sg_alloc_table_from_pages
  - lib/scatterlist.c:sg_init_one
```
```
In lib/kfifo.c (ffffffff8146969c)
Location: include/linux/scatterlist.h:112
Inline: True
```
```
In drivers/char/virtio_console.c (ffffffff815aa840)
Location: include/linux/scatterlist.h:112
Inline: True
Inline callers:
  - drivers/char/virtio_console.c:pipe_to_sg
  - drivers/char/virtio_console.c:pipe_to_sg
```
```
In drivers/char/agp/intel-gtt.c (ffffffff815b5e3d)
Location: include/linux/scatterlist.h:112
Inline: True
Inline callers:
  - drivers/char/agp/intel-gtt.c:intel_fake_agp_insert_entries
```
```
In drivers/base/dma-mapping.c (ffffffff815f5fa6)
Location: include/linux/scatterlist.h:112
Inline: True
```
```
In drivers/spi/spi.c (ffffffff8168b7b1)
Location: include/linux/scatterlist.h:112
Inline: True
```
```
In drivers/usb/core/devio.c (ffffffff816bf10e)
Location: include/linux/scatterlist.h:112
Inline: True
Inline callers:
  - drivers/usb/core/devio.c:proc_do_submiturb
```
```
In drivers/mmc/core/sdio_ops.c (ffffffff8177ecb9)
Location: include/linux/scatterlist.h:112
Inline: True
Inline callers:
  - drivers/mmc/core/sdio_ops.c:mmc_io_rw_extended
```
```
In net/core/skbuff.c (ffffffff817b957f)
Location: include/linux/scatterlist.h:112
Inline: True
Inline callers:
  - net/core/skbuff.c:__skb_to_sgvec
  - net/core/skbuff.c:__skb_to_sgvec
```
```
In net/ipv4/tcp.c (ffffffff81824e47)
Location: include/linux/scatterlist.h:112
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_md5_hash_skb_data
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
In fs/crypto/crypto.c (ffffffff812cfbab)
Location: include/linux/scatterlist.h:119
Inline: True
Inline callers:
  - fs/crypto/crypto.c:fscrypt_do_page_crypto
  - fs/crypto/crypto.c:fscrypt_do_page_crypto
```
```
In fs/ecryptfs/crypto.c (ffffffff81388fc2)
Location: include/linux/scatterlist.h:119
Inline: True
Inline callers:
  - fs/ecryptfs/crypto.c:crypt_extent
  - fs/ecryptfs/crypto.c:crypt_extent
  - fs/ecryptfs/crypto.c:virt_to_scatterlist
```
```
In security/keys/encrypted-keys/encrypted.c (ffffffff813bf07f)
Location: include/linux/scatterlist.h:119
Inline: True
```
```
In crypto/scatterwalk.c (ffffffff81427afc)
Location: include/linux/scatterlist.h:119
Inline: True
```
```
In crypto/rsa-pkcs1pad.c (ffffffff8142f2fd)
Location: include/linux/scatterlist.h:119
Inline: True
Inline callers:
  - crypto/rsa-pkcs1pad.c:pkcs1pad_verify
  - crypto/rsa-pkcs1pad.c:pkcs1pad_decrypt
  - crypto/rsa-pkcs1pad.c:pkcs1pad_encrypt
```
```
In crypto/scompress.c (ffffffff8142ff34)
Location: include/linux/scatterlist.h:119
Inline: True
Inline callers:
  - crypto/scompress.c:scomp_acomp_comp_decomp
```
```
In crypto/gcm.c (ffffffff81439d9b)
Location: include/linux/scatterlist.h:119
Inline: True
Inline callers:
  - crypto/gcm.c:crypto_rfc4106_crypt
  - crypto/gcm.c:crypto_rfc4106_crypt
  - crypto/gcm.c:crypto_gcm_init_common
  - crypto/gcm.c:crypto_gcm_init_common
```
```
In block/blk-merge.c (ffffffff81456f89)
Location: include/linux/scatterlist.h:119
Inline: True
Inline callers:
  - block/blk-merge.c:blk_rq_map_sg
  - block/blk-merge.c:blk_rq_map_sg
  - block/blk-merge.c:blk_rq_map_sg
  - block/blk-merge.c:blk_rq_map_sg
```
```
In block/blk-integrity.c (ffffffff814822c0)
Location: include/linux/scatterlist.h:119
Inline: True
Inline callers:
  - block/blk-integrity.c:blk_rq_map_integrity_sg
```
```
In lib/scatterlist.c (ffffffff8148f83f)
Location: include/linux/scatterlist.h:119
Inline: True
Inline callers:
  - lib/scatterlist.c:sg_init_one
```
```
In lib/kfifo.c (ffffffff8149596f)
Location: include/linux/scatterlist.h:119
Inline: True
```
```
In drivers/char/virtio_console.c (ffffffff816111c6)
Location: include/linux/scatterlist.h:119
Inline: True
Inline callers:
  - drivers/char/virtio_console.c:pipe_to_sg
  - drivers/char/virtio_console.c:pipe_to_sg
```
```
In drivers/char/agp/intel-gtt.c (ffffffff8161c039)
Location: include/linux/scatterlist.h:119
Inline: True
Inline callers:
  - drivers/char/agp/intel-gtt.c:intel_fake_agp_insert_entries
```
```
In drivers/base/dma-mapping.c (ffffffff8165dcd6)
Location: include/linux/scatterlist.h:119
Inline: True
Inline callers:
  - drivers/base/dma-mapping.c:dma_common_get_sgtable
```
```
In drivers/spi/spi.c (ffffffff816f513d)
Location: include/linux/scatterlist.h:119
Inline: True
```
```
In drivers/usb/core/devio.c (ffffffff8172aafe)
Location: include/linux/scatterlist.h:119
Inline: True
Inline callers:
  - drivers/usb/core/devio.c:proc_do_submiturb
```
```
In drivers/mmc/core/sdio_ops.c (ffffffff817f5259)
Location: include/linux/scatterlist.h:119
Inline: True
Inline callers:
  - drivers/mmc/core/sdio_ops.c:mmc_io_rw_extended
```
```
In net/core/skbuff.c (ffffffff81831dbf)
Location: include/linux/scatterlist.h:119
Inline: True
Inline callers:
  - net/core/skbuff.c:__skb_to_sgvec
  - net/core/skbuff.c:__skb_to_sgvec
```
```
In net/ipv4/tcp.c (ffffffff818a37ba)
Location: include/linux/scatterlist.h:119
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_md5_hash_skb_data
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
In kernel/dma/mapping.c (ffffffff8110c708)
Location: include/linux/scatterlist.h:116
Inline: True
Inline callers:
  - kernel/dma/mapping.c:dma_common_get_sgtable
```
```
In kernel/bpf/sockmap.c (ffffffff811cf867)
Location: include/linux/scatterlist.h:116
Inline: True
Inline callers:
  - kernel/bpf/sockmap.c:bpf_tcp_sendpage
```
```
In fs/crypto/crypto.c (ffffffff812fa48d)
Location: include/linux/scatterlist.h:116
Inline: True
Inline callers:
  - fs/crypto/crypto.c:fscrypt_do_page_crypto
  - fs/crypto/crypto.c:fscrypt_do_page_crypto
```
```
In fs/ecryptfs/crypto.c (ffffffff813b7e39)
Location: include/linux/scatterlist.h:116
Inline: True
Inline callers:
  - fs/ecryptfs/crypto.c:crypt_extent
  - fs/ecryptfs/crypto.c:crypt_extent
  - fs/ecryptfs/crypto.c:virt_to_scatterlist
```
```
In security/keys/big_key.c (ffffffff813ecf3b)
Location: include/linux/scatterlist.h:116
Inline: True
Inline callers:
  - security/keys/big_key.c:big_key_alloc_buffer
```
```
In security/keys/encrypted-keys/encrypted.c (ffffffff813efe27)
Location: include/linux/scatterlist.h:116
Inline: True
```
```
In crypto/scatterwalk.c (ffffffff8145a974)
Location: include/linux/scatterlist.h:116
Inline: True
```
```
In crypto/rsa-pkcs1pad.c (ffffffff81461fa3)
Location: include/linux/scatterlist.h:116
Inline: True
Inline callers:
  - crypto/rsa-pkcs1pad.c:pkcs1pad_verify
  - crypto/rsa-pkcs1pad.c:pkcs1pad_decrypt
  - crypto/rsa-pkcs1pad.c:pkcs1pad_encrypt
```
```
In crypto/gcm.c (ffffffff8146ca9e)
Location: include/linux/scatterlist.h:116
Inline: True
Inline callers:
  - crypto/gcm.c:crypto_rfc4106_crypt
  - crypto/gcm.c:crypto_rfc4106_crypt
  - crypto/gcm.c:crypto_gcm_init_common
  - crypto/gcm.c:crypto_gcm_init_common
```
```
In block/blk-merge.c (ffffffff8148aa7a)
Location: include/linux/scatterlist.h:116
Inline: True
Inline callers:
  - block/blk-merge.c:blk_rq_map_sg
  - block/blk-merge.c:blk_rq_map_sg
  - block/blk-merge.c:blk_rq_map_sg
  - block/blk-merge.c:blk_rq_map_sg
```
```
In block/blk-integrity.c (ffffffff814b6fd5)
Location: include/linux/scatterlist.h:116
Inline: True
Inline callers:
  - block/blk-integrity.c:blk_rq_map_integrity_sg
```
```
In lib/scatterlist.c (ffffffff814c4b03)
Location: include/linux/scatterlist.h:116
Inline: True
Inline callers:
  - lib/scatterlist.c:sgl_alloc_order
  - lib/scatterlist.c:sg_init_one
```
```
In lib/kfifo.c (ffffffff814cad12)
Location: include/linux/scatterlist.h:116
Inline: True
```
```
In drivers/char/virtio_console.c (ffffffff8164ac53)
Location: include/linux/scatterlist.h:116
Inline: True
Inline callers:
  - drivers/char/virtio_console.c:pipe_to_sg
  - drivers/char/virtio_console.c:pipe_to_sg
```
```
In drivers/char/agp/intel-gtt.c (ffffffff81655cd5)
Location: include/linux/scatterlist.h:116
Inline: True
Inline callers:
  - drivers/char/agp/intel-gtt.c:intel_fake_agp_insert_entries
```
```
In drivers/spi/spi.c (ffffffff8173281c)
Location: include/linux/scatterlist.h:116
Inline: True
Inline callers:
  - drivers/spi/spi.c:spi_map_buf
  - drivers/spi/spi.c:spi_map_buf
```
```
In drivers/usb/core/devio.c (ffffffff8176949a)
Location: include/linux/scatterlist.h:116
Inline: True
Inline callers:
  - drivers/usb/core/devio.c:proc_do_submiturb
```
```
In drivers/mmc/core/sdio_ops.c (ffffffff8183e784)
Location: include/linux/scatterlist.h:116
Inline: True
Inline callers:
  - drivers/mmc/core/sdio_ops.c:mmc_io_rw_extended
```
```
In net/core/sock.c (ffffffff81877404)
Location: include/linux/scatterlist.h:116
Inline: True
Inline callers:
  - net/core/sock.c:sk_alloc_sg
```
```
In net/core/skbuff.c (ffffffff8187c4b7)
Location: include/linux/scatterlist.h:116
Inline: True
Inline callers:
  - net/core/skbuff.c:__skb_to_sgvec
  - net/core/skbuff.c:__skb_to_sgvec
```
```
In net/core/filter.c (ffffffff818b3b5b)
Location: include/linux/scatterlist.h:116
Inline: True
Inline callers:
  - net/core/filter.c:bpf_msg_pull_data
```
```
In net/ipv4/tcp.c (ffffffff818f8b2a)
Location: include/linux/scatterlist.h:116
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_md5_hash_skb_data
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
In kernel/dma/mapping.c (ffffffff81118362)
Location: include/linux/scatterlist.h:116
Inline: True
Inline callers:
  - kernel/dma/mapping.c:dma_common_get_sgtable
```
```
In fs/crypto/crypto.c (ffffffff8130f7c1)
Location: include/linux/scatterlist.h:116
Inline: True
Inline callers:
  - fs/crypto/crypto.c:fscrypt_do_page_crypto
  - fs/crypto/crypto.c:fscrypt_do_page_crypto
```
```
In fs/ecryptfs/crypto.c (ffffffff813d13b9)
Location: include/linux/scatterlist.h:116
Inline: True
Inline callers:
  - fs/ecryptfs/crypto.c:crypt_extent
  - fs/ecryptfs/crypto.c:crypt_extent
  - fs/ecryptfs/crypto.c:virt_to_scatterlist
```
```
In security/keys/big_key.c (ffffffff8140811b)
Location: include/linux/scatterlist.h:116
Inline: True
Inline callers:
  - security/keys/big_key.c:big_key_alloc_buffer
```
```
In security/keys/encrypted-keys/encrypted.c (ffffffff8140b108)
Location: include/linux/scatterlist.h:116
Inline: True
```
```
In crypto/scatterwalk.c (ffffffff814784e4)
Location: include/linux/scatterlist.h:116
Inline: True
```
```
In crypto/rsa-pkcs1pad.c (ffffffff8147fd73)
Location: include/linux/scatterlist.h:116
Inline: True
Inline callers:
  - crypto/rsa-pkcs1pad.c:pkcs1pad_verify
  - crypto/rsa-pkcs1pad.c:pkcs1pad_decrypt
```
```
In crypto/gcm.c (ffffffff8148a20e)
Location: include/linux/scatterlist.h:116
Inline: True
Inline callers:
  - crypto/gcm.c:crypto_rfc4106_crypt
  - crypto/gcm.c:crypto_rfc4106_crypt
  - crypto/gcm.c:crypto_gcm_init_common
  - crypto/gcm.c:crypto_gcm_init_common
```
```
In crypto/drbg.c (ffffffff8149004e)
Location: include/linux/scatterlist.h:116
Inline: True
Inline callers:
  - crypto/drbg.c:drbg_kcapi_sym_ctr
  - crypto/drbg.c:drbg_kcapi_sym_ctr
```
```
In block/blk-merge.c (ffffffff814a473c)
Location: include/linux/scatterlist.h:116
Inline: True
Inline callers:
  - block/blk-merge.c:blk_rq_map_sg
  - block/blk-merge.c:blk_rq_map_sg
  - block/blk-merge.c:blk_rq_map_sg
  - block/blk-merge.c:blk_rq_map_sg
```
```
In block/blk-integrity.c (ffffffff814ca675)
Location: include/linux/scatterlist.h:116
Inline: True
Inline callers:
  - block/blk-integrity.c:blk_rq_map_integrity_sg
```
```
In lib/scatterlist.c (ffffffff814d91f3)
Location: include/linux/scatterlist.h:116
Inline: True
Inline callers:
  - lib/scatterlist.c:sgl_alloc_order
  - lib/scatterlist.c:sg_init_one
```
```
In lib/kfifo.c (ffffffff814dfa42)
Location: include/linux/scatterlist.h:116
Inline: True
```
```
In drivers/char/virtio_console.c (ffffffff81668f13)
Location: include/linux/scatterlist.h:116
Inline: True
Inline callers:
  - drivers/char/virtio_console.c:pipe_to_sg
  - drivers/char/virtio_console.c:pipe_to_sg
```
```
In drivers/char/agp/intel-gtt.c (ffffffff816748d5)
Location: include/linux/scatterlist.h:116
Inline: True
Inline callers:
  - drivers/char/agp/intel-gtt.c:intel_fake_agp_insert_entries
```
```
In drivers/spi/spi.c (ffffffff8175520c)
Location: include/linux/scatterlist.h:116
Inline: True
Inline callers:
  - drivers/spi/spi.c:spi_map_buf
  - drivers/spi/spi.c:spi_map_buf
```
```
In drivers/usb/core/devio.c (ffffffff8178db1d)
Location: include/linux/scatterlist.h:116
Inline: True
Inline callers:
  - drivers/usb/core/devio.c:proc_do_submiturb
```
```
In drivers/mmc/core/sdio_ops.c (ffffffff8186a734)
Location: include/linux/scatterlist.h:116
Inline: True
Inline callers:
  - drivers/mmc/core/sdio_ops.c:mmc_io_rw_extended
```
```
In net/core/skbuff.c (ffffffff8189ce41)
Location: include/linux/scatterlist.h:116
Inline: True
Inline callers:
  - net/core/skbuff.c:__skb_to_sgvec
  - net/core/skbuff.c:__skb_to_sgvec
```
```
In net/core/filter.c (ffffffff818d9646)
Location: include/linux/scatterlist.h:116
Inline: True
Inline callers:
  - net/core/filter.c:bpf_msg_pop_data
  - net/core/filter.c:bpf_msg_pop_data
  - net/core/filter.c:bpf_msg_push_data
  - net/core/filter.c:bpf_msg_pull_data
```
```
In net/core/skmsg.c (ffffffff818e66f3)
Location: include/linux/scatterlist.h:116
Inline: True
Inline callers:
  - net/core/skmsg.c:sk_msg_zerocopy_from_iter
  - net/core/skmsg.c:sk_msg_clone
  - net/core/skmsg.c:sk_msg_alloc
```
```
In net/ipv4/tcp.c (ffffffff8192686f)
Location: include/linux/scatterlist.h:116
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_md5_hash_skb_data
  - net/ipv4/tcp.c:tcp_md5_hash_skb_data
```
```
In net/ipv4/tcp_bpf.c (ffffffff8197777d)
Location: include/linux/scatterlist.h:116
Inline: True
Inline callers:
  - net/ipv4/tcp_bpf.c:tcp_bpf_sendpage
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
In kernel/dma/mapping.c (ffffffff811226cf)
Location: include/linux/scatterlist.h:116
Inline: True
Inline callers:
  - kernel/dma/mapping.c:dma_common_get_sgtable
```
```
In fs/crypto/crypto.c (ffffffff81336ca2)
Location: include/linux/scatterlist.h:116
Inline: True
Inline callers:
  - fs/crypto/crypto.c:fscrypt_crypt_block
  - fs/crypto/crypto.c:fscrypt_crypt_block
```
```
In fs/ecryptfs/crypto.c (ffffffff813fbef2)
Location: include/linux/scatterlist.h:116
Inline: True
Inline callers:
  - fs/ecryptfs/crypto.c:crypt_extent
  - fs/ecryptfs/crypto.c:crypt_extent
  - fs/ecryptfs/crypto.c:virt_to_scatterlist
```
```
In security/keys/big_key.c (ffffffff8143515b)
Location: include/linux/scatterlist.h:116
Inline: True
Inline callers:
  - security/keys/big_key.c:big_key_alloc_buffer
```
```
In security/keys/encrypted-keys/encrypted.c (ffffffff81437edf)
Location: include/linux/scatterlist.h:116
Inline: True
```
```
In crypto/scatterwalk.c (ffffffff814a6307)
Location: include/linux/scatterlist.h:116
Inline: True
```
```
In crypto/rsa-pkcs1pad.c (ffffffff814adf6f)
Location: include/linux/scatterlist.h:116
Inline: True
Inline callers:
  - crypto/rsa-pkcs1pad.c:pkcs1pad_verify
  - crypto/rsa-pkcs1pad.c:pkcs1pad_decrypt
```
```
In crypto/gcm.c (ffffffff814b79f4)
Location: include/linux/scatterlist.h:116
Inline: True
Inline callers:
  - crypto/gcm.c:crypto_rfc4106_crypt
  - crypto/gcm.c:crypto_rfc4106_crypt
  - crypto/gcm.c:crypto_gcm_init_common
  - crypto/gcm.c:crypto_gcm_init_common
```
```
In crypto/drbg.c (ffffffff814bd23b)
Location: include/linux/scatterlist.h:116
Inline: True
Inline callers:
  - crypto/drbg.c:drbg_kcapi_sym_ctr
  - crypto/drbg.c:drbg_kcapi_sym_ctr
```
```
In crypto/asymmetric_keys/public_key.c (ffffffff814c0e60)
Location: include/linux/scatterlist.h:116
Inline: True
Inline callers:
  - crypto/asymmetric_keys/public_key.c:public_key_verify_signature
  - crypto/asymmetric_keys/public_key.c:public_key_verify_signature
```
```
In block/blk-merge.c (ffffffff814d242c)
Location: include/linux/scatterlist.h:116
Inline: True
Inline callers:
  - block/blk-merge.c:blk_rq_map_sg
  - block/blk-merge.c:blk_rq_map_sg
  - block/blk-merge.c:blk_rq_map_sg
  - block/blk-merge.c:__blk_bios_map_sg
  - block/blk-merge.c:__blk_bios_map_sg
```
```
In block/blk-integrity.c (ffffffff814f8f44)
Location: include/linux/scatterlist.h:116
Inline: True
Inline callers:
  - block/blk-integrity.c:blk_rq_map_integrity_sg
```
```
In lib/scatterlist.c (ffffffff81505096)
Location: include/linux/scatterlist.h:116
Inline: True
Inline callers:
  - lib/scatterlist.c:sgl_alloc_order
  - lib/scatterlist.c:sg_init_one
```
```
In lib/kfifo.c (ffffffff8150b8dc)
Location: include/linux/scatterlist.h:116
Inline: True
```
```
In drivers/char/virtio_console.c (ffffffff8169e87e)
Location: include/linux/scatterlist.h:116
Inline: True
Inline callers:
  - drivers/char/virtio_console.c:pipe_to_sg
  - drivers/char/virtio_console.c:pipe_to_sg
```
```
In drivers/char/agp/intel-gtt.c (ffffffff816a9896)
Location: include/linux/scatterlist.h:116
Inline: True
Inline callers:
  - drivers/char/agp/intel-gtt.c:intel_fake_agp_insert_entries
```
```
In drivers/spi/spi.c (ffffffff8179130f)
Location: include/linux/scatterlist.h:116
Inline: True
Inline callers:
  - drivers/spi/spi.c:spi_map_buf
  - drivers/spi/spi.c:spi_map_buf
```
```
In drivers/usb/core/devio.c (ffffffff817cc61d)
Location: include/linux/scatterlist.h:116
Inline: True
Inline callers:
  - drivers/usb/core/devio.c:proc_do_submiturb
```
```
In drivers/mmc/core/sdio_ops.c (ffffffff818ae623)
Location: include/linux/scatterlist.h:116
Inline: True
Inline callers:
  - drivers/mmc/core/sdio_ops.c:mmc_io_rw_extended
```
```
In net/core/skbuff.c (ffffffff818e7569)
Location: include/linux/scatterlist.h:116
Inline: True
Inline callers:
  - net/core/skbuff.c:__skb_to_sgvec
  - net/core/skbuff.c:__skb_to_sgvec
```
```
In net/core/filter.c (ffffffff8192b72e)
Location: include/linux/scatterlist.h:116
Inline: True
Inline callers:
  - net/core/filter.c:bpf_msg_pop_data
  - net/core/filter.c:bpf_msg_pop_data
  - net/core/filter.c:bpf_msg_push_data
  - net/core/filter.c:bpf_msg_pull_data
```
```
In net/core/skmsg.c (ffffffff81936097)
Location: include/linux/scatterlist.h:116
Inline: True
Inline callers:
  - net/core/skmsg.c:sk_msg_zerocopy_from_iter
  - net/core/skmsg.c:sk_msg_clone
  - net/core/skmsg.c:sk_msg_alloc
```
```
In net/ipv4/tcp.c (ffffffff819877bc)
Location: include/linux/scatterlist.h:116
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_md5_hash_skb_data
  - net/ipv4/tcp.c:tcp_md5_hash_skb_data
```
```
In net/ipv4/tcp_bpf.c (ffffffff819e12a4)
Location: include/linux/scatterlist.h:116
Inline: True
Inline callers:
  - net/ipv4/tcp_bpf.c:tcp_bpf_sendpage
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
In kernel/dma/mapping.c (ffffffff8112ec00)
Location: include/linux/scatterlist.h:116
Inline: True
```
```
In fs/crypto/crypto.c (ffffffff8134a872)
Location: include/linux/scatterlist.h:116
Inline: True
Inline callers:
  - fs/crypto/crypto.c:fscrypt_crypt_block
  - fs/crypto/crypto.c:fscrypt_crypt_block
  - fs/crypto/crypto.c:fscrypt_crypt_block
  - fs/crypto/crypto.c:fscrypt_crypt_block
```
```
In fs/verity/hash_algs.c (ffffffff81350394)
Location: include/linux/scatterlist.h:116
Inline: True
Inline callers:
  - fs/verity/hash_algs.c:fsverity_hash_page
```
```
In fs/ecryptfs/crypto.c (ffffffff81415dd2)
Location: include/linux/scatterlist.h:116
Inline: True
Inline callers:
  - fs/ecryptfs/crypto.c:crypt_extent
  - fs/ecryptfs/crypto.c:crypt_extent
  - fs/ecryptfs/crypto.c:crypt_extent
  - fs/ecryptfs/crypto.c:crypt_extent
  - fs/ecryptfs/crypto.c:virt_to_scatterlist
  - fs/ecryptfs/crypto.c:virt_to_scatterlist
```
```
In security/keys/big_key.c (ffffffff8144eedb)
Location: include/linux/scatterlist.h:116
Inline: True
Inline callers:
  - security/keys/big_key.c:big_key_alloc_buffer
```
```
In security/keys/encrypted-keys/encrypted.c (ffffffff81451c9f)
Location: include/linux/scatterlist.h:116
Inline: True
```
```
In crypto/scatterwalk.c (ffffffff814c0f97)
Location: include/linux/scatterlist.h:116
Inline: True
```
```
In crypto/rsa-pkcs1pad.c (ffffffff814c8c1c)
Location: include/linux/scatterlist.h:116
Inline: True
Inline callers:
  - crypto/rsa-pkcs1pad.c:pkcs1pad_verify
  - crypto/rsa-pkcs1pad.c:pkcs1pad_decrypt
```
```
In crypto/gcm.c (ffffffff814d0c14)
Location: include/linux/scatterlist.h:116
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
In crypto/drbg.c (ffffffff814d5ede)
Location: include/linux/scatterlist.h:116
Inline: True
Inline callers:
  - crypto/drbg.c:drbg_kcapi_sym_ctr
  - crypto/drbg.c:drbg_kcapi_sym_ctr
  - crypto/drbg.c:drbg_kcapi_sym_ctr
  - crypto/drbg.c:drbg_kcapi_sym_ctr
```
```
In crypto/asymmetric_keys/public_key.c (ffffffff814d9c90)
Location: include/linux/scatterlist.h:116
Inline: True
Inline callers:
  - crypto/asymmetric_keys/public_key.c:public_key_verify_signature
  - crypto/asymmetric_keys/public_key.c:public_key_verify_signature
  - crypto/asymmetric_keys/public_key.c:public_key_verify_signature
  - crypto/asymmetric_keys/public_key.c:public_key_verify_signature
```
```
In block/blk-merge.c (ffffffff814eb7ac)
Location: include/linux/scatterlist.h:116
Inline: True
Inline callers:
  - block/blk-merge.c:blk_rq_map_sg
  - block/blk-merge.c:blk_rq_map_sg
  - block/blk-merge.c:blk_rq_map_sg
  - block/blk-merge.c:blk_rq_map_sg
  - block/blk-merge.c:blk_rq_map_sg
  - block/blk-merge.c:blk_rq_map_sg
  - block/blk-merge.c:__blk_bios_map_sg
  - block/blk-merge.c:__blk_bios_map_sg
  - block/blk-merge.c:__blk_bios_map_sg
  - block/blk-merge.c:__blk_bios_map_sg
```
```
In block/blk-integrity.c (ffffffff81516dfd)
Location: include/linux/scatterlist.h:116
Inline: True
Inline callers:
  - block/blk-integrity.c:blk_rq_map_integrity_sg
```
```
In lib/scatterlist.c (ffffffff81522aa6)
Location: include/linux/scatterlist.h:116
Inline: True
Inline callers:
  - lib/scatterlist.c:sgl_alloc_order
  - lib/scatterlist.c:sgl_alloc_order
  - lib/scatterlist.c:sg_init_one
  - lib/scatterlist.c:sg_init_one
```
```
In lib/kfifo.c (ffffffff81529673)
Location: include/linux/scatterlist.h:116
Inline: True
```
```
In drivers/char/virtio_console.c (ffffffff816c192e)
Location: include/linux/scatterlist.h:116
Inline: True
Inline callers:
  - drivers/char/virtio_console.c:pipe_to_sg
  - drivers/char/virtio_console.c:pipe_to_sg
  - drivers/char/virtio_console.c:pipe_to_sg
  - drivers/char/virtio_console.c:pipe_to_sg
```
```
In drivers/char/agp/intel-gtt.c (ffffffff816cc5d6)
Location: include/linux/scatterlist.h:116
Inline: True
Inline callers:
  - drivers/char/agp/intel-gtt.c:intel_fake_agp_insert_entries
```
```
In drivers/spi/spi.c (ffffffff817b4f08)
Location: include/linux/scatterlist.h:116
Inline: True
Inline callers:
  - drivers/spi/spi.c:spi_map_buf
  - drivers/spi/spi.c:spi_map_buf
  - drivers/spi/spi.c:spi_map_buf
  - drivers/spi/spi.c:spi_map_buf
```
```
In drivers/usb/core/devio.c (ffffffff817fd2ac)
Location: include/linux/scatterlist.h:116
Inline: True
Inline callers:
  - drivers/usb/core/devio.c:proc_do_submiturb
```
```
In drivers/mmc/core/sdio_ops.c (ffffffff818e0ac1)
Location: include/linux/scatterlist.h:116
Inline: True
Inline callers:
  - drivers/mmc/core/sdio_ops.c:mmc_io_rw_extended
```
```
In net/core/skbuff.c (ffffffff819198b6)
Location: include/linux/scatterlist.h:116
Inline: True
Inline callers:
  - net/core/skbuff.c:__skb_to_sgvec
  - net/core/skbuff.c:__skb_to_sgvec
  - net/core/skbuff.c:__skb_to_sgvec
  - net/core/skbuff.c:__skb_to_sgvec
```
```
In net/core/filter.c (ffffffff8195da61)
Location: include/linux/scatterlist.h:116
Inline: True
Inline callers:
  - net/core/filter.c:bpf_msg_pop_data
  - net/core/filter.c:bpf_msg_pop_data
  - net/core/filter.c:bpf_msg_pop_data
  - net/core/filter.c:bpf_msg_push_data
  - net/core/filter.c:bpf_msg_push_data
  - net/core/filter.c:bpf_msg_pull_data
  - net/core/filter.c:bpf_msg_pull_data
```
```
In net/core/skmsg.c (ffffffff819690e7)
Location: include/linux/scatterlist.h:116
Inline: True
Inline callers:
  - net/core/skmsg.c:sk_msg_zerocopy_from_iter
  - net/core/skmsg.c:sk_msg_zerocopy_from_iter
  - net/core/skmsg.c:sk_msg_clone
  - net/core/skmsg.c:sk_msg_alloc
  - net/core/skmsg.c:sk_msg_alloc
```
```
In net/ipv4/tcp.c (ffffffff819bdf82)
Location: include/linux/scatterlist.h:116
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_md5_hash_skb_data
  - net/ipv4/tcp.c:tcp_md5_hash_skb_data
  - net/ipv4/tcp.c:tcp_md5_hash_skb_data
  - net/ipv4/tcp.c:tcp_md5_hash_skb_data
```
```
In net/ipv4/tcp_bpf.c (ffffffff81a18670)
Location: include/linux/scatterlist.h:116
Inline: True
Inline callers:
  - net/ipv4/tcp_bpf.c:tcp_bpf_sendpage
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
In kernel/dma/mapping.c (ffffffff8113d65f)
Location: include/linux/scatterlist.h:116
Inline: True
Inline callers:
  - kernel/dma/mapping.c:dma_common_get_sgtable
```
```
In kernel/dma/direct.c (ffffffff8113e351)
Location: include/linux/scatterlist.h:116
Inline: True
Inline callers:
  - kernel/dma/direct.c:dma_direct_get_sgtable
```
```
In mm/page_reporting.c (ffffffff8130d2e8)
Location: include/linux/scatterlist.h:116
Inline: True
Inline callers:
  - mm/page_reporting.c:page_reporting_cycle
```
```
In fs/crypto/crypto.c (ffffffff8138ffd2)
Location: include/linux/scatterlist.h:116
Inline: True
Inline callers:
  - fs/crypto/crypto.c:fscrypt_crypt_block
  - fs/crypto/crypto.c:fscrypt_crypt_block
```
```
In fs/verity/hash_algs.c (ffffffff81396d34)
Location: include/linux/scatterlist.h:116
Inline: True
Inline callers:
  - fs/verity/hash_algs.c:fsverity_hash_page
```
```
In fs/ecryptfs/crypto.c (ffffffff81464371)
Location: include/linux/scatterlist.h:116
Inline: True
Inline callers:
  - fs/ecryptfs/crypto.c:crypt_extent
  - fs/ecryptfs/crypto.c:crypt_extent
  - fs/ecryptfs/crypto.c:virt_to_scatterlist
```
```
In security/keys/encrypted-keys/encrypted.c (ffffffff814a4a05)
Location: include/linux/scatterlist.h:116
Inline: True
```
```
In crypto/scatterwalk.c (ffffffff81521847)
Location: include/linux/scatterlist.h:116
Inline: True
Inline callers:
  - crypto/scatterwalk.c:scatterwalk_ffwd
```
```
In crypto/rsa-pkcs1pad.c (ffffffff815272ec)
Location: include/linux/scatterlist.h:116
Inline: True
Inline callers:
  - crypto/rsa-pkcs1pad.c:pkcs1pad_verify
  - crypto/rsa-pkcs1pad.c:pkcs1pad_decrypt
```
```
In crypto/gcm.c (ffffffff8152f8f1)
Location: include/linux/scatterlist.h:116
Inline: True
Inline callers:
  - crypto/gcm.c:crypto_rfc4106_crypt
  - crypto/gcm.c:crypto_rfc4106_crypt
  - crypto/gcm.c:crypto_gcm_init_common
  - crypto/gcm.c:crypto_gcm_init_common
```
```
In crypto/drbg.c (ffffffff81535ac1)
Location: include/linux/scatterlist.h:116
Inline: True
Inline callers:
  - crypto/drbg.c:drbg_kcapi_sym_ctr
  - crypto/drbg.c:drbg_kcapi_sym_ctr
```
```
In crypto/asymmetric_keys/public_key.c (ffffffff8153921e)
Location: include/linux/scatterlist.h:116
Inline: True
Inline callers:
  - crypto/asymmetric_keys/public_key.c:public_key_verify_signature
  - crypto/asymmetric_keys/public_key.c:public_key_verify_signature
```
```
In block/blk-merge.c (ffffffff8154b599)
Location: include/linux/scatterlist.h:116
Inline: True
Inline callers:
  - block/blk-merge.c:__blk_rq_map_sg
  - block/blk-merge.c:__blk_rq_map_sg
  - block/blk-merge.c:__blk_bios_map_sg
  - block/blk-merge.c:blk_bvec_map_sg
```
```
In block/blk-integrity.c (ffffffff8157759a)
Location: include/linux/scatterlist.h:116
Inline: True
Inline callers:
  - block/blk-integrity.c:blk_rq_map_integrity_sg
```
```
In block/blk-crypto-fallback.c (ffffffff8158251c)
Location: include/linux/scatterlist.h:116
Inline: True
Inline callers:
  - block/blk-crypto-fallback.c:blk_crypto_fallback_decrypt_bio
  - block/blk-crypto-fallback.c:blk_crypto_fallback_encrypt_bio
  - block/blk-crypto-fallback.c:blk_crypto_fallback_encrypt_bio
```
```
In lib/scatterlist.c (ffffffff815865fb)
Location: include/linux/scatterlist.h:116
Inline: True
Inline callers:
  - lib/scatterlist.c:sgl_alloc_order
  - lib/scatterlist.c:__sg_alloc_table_from_pages
  - lib/scatterlist.c:sg_init_one
```
```
In lib/kfifo.c (ffffffff8158cd6b)
Location: include/linux/scatterlist.h:116
Inline: True
```
```
In drivers/char/virtio_console.c (ffffffff81774ead)
Location: include/linux/scatterlist.h:116
Inline: True
Inline callers:
  - drivers/char/virtio_console.c:pipe_to_sg
  - drivers/char/virtio_console.c:pipe_to_sg
```
```
In drivers/char/agp/intel-gtt.c (ffffffff81780f98)
Location: include/linux/scatterlist.h:116
Inline: True
Inline callers:
  - drivers/char/agp/intel-gtt.c:intel_gtt_map_memory
```
```
In drivers/iommu/dma-iommu.c (ffffffff81791dff)
Location: include/linux/scatterlist.h:116
Inline: True
Inline callers:
  - drivers/iommu/dma-iommu.c:iommu_dma_get_sgtable
```
```
In drivers/scsi/scsi_lib.c (ffffffff81836f89)
Location: include/linux/scatterlist.h:116
Inline: True
Inline callers:
  - drivers/scsi/scsi_lib.c:scsi_init_io
```
```
In drivers/spi/spi.c (ffffffff8187babf)
Location: include/linux/scatterlist.h:116
Inline: True
Inline callers:
  - drivers/spi/spi.c:spi_map_buf
  - drivers/spi/spi.c:spi_map_buf
```
```
In drivers/usb/core/devio.c (ffffffff818cc8c9)
Location: include/linux/scatterlist.h:116
Inline: True
Inline callers:
  - drivers/usb/core/devio.c:proc_do_submiturb
```
```
In drivers/mmc/core/sdio_ops.c (ffffffff819b3aed)
Location: include/linux/scatterlist.h:116
Inline: True
Inline callers:
  - drivers/mmc/core/sdio_ops.c:mmc_io_rw_extended
```
```
In net/core/skbuff.c (ffffffff819ea76f)
Location: include/linux/scatterlist.h:116
Inline: True
Inline callers:
  - net/core/skbuff.c:__skb_to_sgvec
  - net/core/skbuff.c:__skb_to_sgvec
```
```
In net/core/filter.c (ffffffff81a2ca00)
Location: include/linux/scatterlist.h:116
Inline: True
Inline callers:
  - net/core/filter.c:bpf_msg_pop_data
  - net/core/filter.c:bpf_msg_pop_data
  - net/core/filter.c:bpf_msg_push_data
  - net/core/filter.c:bpf_msg_pull_data
```
```
In net/core/skmsg.c (ffffffff81a3c40f)
Location: include/linux/scatterlist.h:116
Inline: True
Inline callers:
  - net/core/skmsg.c:sk_msg_zerocopy_from_iter
  - net/core/skmsg.c:sk_msg_clone
  - net/core/skmsg.c:sk_msg_alloc
```
```
In net/ipv4/tcp.c (ffffffff81aa915a)
Location: include/linux/scatterlist.h:116
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_md5_hash_skb_data
  - net/ipv4/tcp.c:tcp_md5_hash_skb_data
```
```
In net/ipv4/tcp_bpf.c (ffffffff81b09395)
Location: include/linux/scatterlist.h:116
Inline: True
Inline callers:
  - net/ipv4/tcp_bpf.c:tcp_bpf_sendpage
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
In kernel/dma/direct.c (ffffffff811396cb)
Location: include/linux/scatterlist.h:110
Inline: True
Inline callers:
  - kernel/dma/direct.c:dma_direct_get_sgtable
```
```
In kernel/dma/ops_helpers.c (ffffffff81139a9f)
Location: include/linux/scatterlist.h:110
Inline: True
Inline callers:
  - kernel/dma/ops_helpers.c:dma_common_get_sgtable
```
```
In mm/zswap.c (ffffffff812cd51c)
Location: include/linux/scatterlist.h:110
Inline: True
Inline callers:
  - mm/zswap.c:zswap_frontswap_load
  - mm/zswap.c:zswap_frontswap_store
  - mm/zswap.c:zswap_writeback_entry
```
```
In mm/page_reporting.c (ffffffff81319238)
Location: include/linux/scatterlist.h:110
Inline: True
Inline callers:
  - mm/page_reporting.c:page_reporting_cycle
```
```
In fs/crypto/crypto.c (ffffffff813a1612)
Location: include/linux/scatterlist.h:110
Inline: True
Inline callers:
  - fs/crypto/crypto.c:fscrypt_crypt_block
  - fs/crypto/crypto.c:fscrypt_crypt_block
```
```
In fs/verity/hash_algs.c (ffffffff813a8964)
Location: include/linux/scatterlist.h:110
Inline: True
Inline callers:
  - fs/verity/hash_algs.c:fsverity_hash_page
```
```
In fs/ecryptfs/crypto.c (ffffffff8147fb31)
Location: include/linux/scatterlist.h:110
Inline: True
Inline callers:
  - fs/ecryptfs/crypto.c:crypt_extent
  - fs/ecryptfs/crypto.c:crypt_extent
  - fs/ecryptfs/crypto.c:virt_to_scatterlist
```
```
In security/keys/encrypted-keys/encrypted.c (ffffffff814c2205)
Location: include/linux/scatterlist.h:110
Inline: True
```
```
In crypto/scatterwalk.c (ffffffff8153e6b7)
Location: include/linux/scatterlist.h:110
Inline: True
Inline callers:
  - crypto/scatterwalk.c:scatterwalk_ffwd
```
```
In crypto/rsa-pkcs1pad.c (ffffffff8154426c)
Location: include/linux/scatterlist.h:110
Inline: True
Inline callers:
  - crypto/rsa-pkcs1pad.c:pkcs1pad_verify
  - crypto/rsa-pkcs1pad.c:pkcs1pad_decrypt
```
```
In crypto/gcm.c (ffffffff8154c4b1)
Location: include/linux/scatterlist.h:110
Inline: True
Inline callers:
  - crypto/gcm.c:crypto_rfc4106_crypt
  - crypto/gcm.c:crypto_rfc4106_crypt
  - crypto/gcm.c:crypto_gcm_init_common
  - crypto/gcm.c:crypto_gcm_init_common
```
```
In crypto/drbg.c (ffffffff81552a31)
Location: include/linux/scatterlist.h:110
Inline: True
Inline callers:
  - crypto/drbg.c:drbg_kcapi_sym_ctr
  - crypto/drbg.c:drbg_kcapi_sym_ctr
```
```
In crypto/asymmetric_keys/public_key.c (ffffffff81556017)
Location: include/linux/scatterlist.h:110
Inline: True
Inline callers:
  - crypto/asymmetric_keys/public_key.c:public_key_verify_signature
  - crypto/asymmetric_keys/public_key.c:public_key_verify_signature
```
```
In block/blk-merge.c (ffffffff81567649)
Location: include/linux/scatterlist.h:110
Inline: True
Inline callers:
  - block/blk-merge.c:__blk_rq_map_sg
  - block/blk-merge.c:__blk_rq_map_sg
  - block/blk-merge.c:__blk_bios_map_sg
  - block/blk-merge.c:blk_bvec_map_sg
```
```
In block/blk-integrity.c (ffffffff81594166)
Location: include/linux/scatterlist.h:110
Inline: True
Inline callers:
  - block/blk-integrity.c:blk_rq_map_integrity_sg
```
```
In block/blk-crypto-fallback.c (ffffffff8159f4c8)
Location: include/linux/scatterlist.h:110
Inline: True
Inline callers:
  - block/blk-crypto-fallback.c:blk_crypto_fallback_decrypt_bio
  - block/blk-crypto-fallback.c:blk_crypto_fallback_encrypt_bio
  - block/blk-crypto-fallback.c:blk_crypto_fallback_encrypt_bio
```
```
In lib/scatterlist.c (ffffffff815a38e2)
Location: include/linux/scatterlist.h:110
Inline: True
Inline callers:
  - lib/scatterlist.c:sgl_alloc_order
  - lib/scatterlist.c:__sg_alloc_table_from_pages
  - lib/scatterlist.c:sg_init_one
```
```
In lib/kfifo.c (ffffffff815a979e)
Location: include/linux/scatterlist.h:110
Inline: True
```
```
In drivers/char/virtio_console.c (ffffffff8178fbfd)
Location: include/linux/scatterlist.h:110
Inline: True
Inline callers:
  - drivers/char/virtio_console.c:pipe_to_sg
  - drivers/char/virtio_console.c:pipe_to_sg
```
```
In drivers/char/agp/intel-gtt.c (ffffffff817988a8)
Location: include/linux/scatterlist.h:110
Inline: True
Inline callers:
  - drivers/char/agp/intel-gtt.c:intel_gtt_map_memory
```
```
In drivers/iommu/dma-iommu.c (ffffffff817be02f)
Location: include/linux/scatterlist.h:110
Inline: True
Inline callers:
  - drivers/iommu/dma-iommu.c:iommu_dma_get_sgtable
```
```
In drivers/dma-buf/heaps/system_heap.c (ffffffff8183b467)
Location: include/linux/scatterlist.h:110
Inline: True
Inline callers:
  - drivers/dma-buf/heaps/system_heap.c:system_heap_allocate
  - drivers/dma-buf/heaps/system_heap.c:dup_sg_table
```
```
In drivers/scsi/scsi_lib.c (ffffffff818479f9)
Location: include/linux/scatterlist.h:110
Inline: True
Inline callers:
  - drivers/scsi/scsi_lib.c:scsi_alloc_sgtables
```
```
In drivers/spi/spi.c (ffffffff8188ac9f)
Location: include/linux/scatterlist.h:110
Inline: True
Inline callers:
  - drivers/spi/spi.c:spi_map_buf
  - drivers/spi/spi.c:spi_map_buf
```
```
In drivers/usb/core/devio.c (ffffffff818d7aab)
Location: include/linux/scatterlist.h:110
Inline: True
Inline callers:
  - drivers/usb/core/devio.c:proc_do_submiturb
```
```
In drivers/mmc/core/sdio_ops.c (ffffffff819b5f6d)
Location: include/linux/scatterlist.h:110
Inline: True
Inline callers:
  - drivers/mmc/core/sdio_ops.c:mmc_io_rw_extended
```
```
In net/core/skbuff.c (ffffffff819ea4af)
Location: include/linux/scatterlist.h:110
Inline: True
Inline callers:
  - net/core/skbuff.c:__skb_to_sgvec
  - net/core/skbuff.c:__skb_to_sgvec
```
```
In net/core/filter.c (ffffffff81a2dfb0)
Location: include/linux/scatterlist.h:110
Inline: True
Inline callers:
  - net/core/filter.c:bpf_msg_pop_data
  - net/core/filter.c:bpf_msg_pop_data
  - net/core/filter.c:bpf_msg_push_data
  - net/core/filter.c:bpf_msg_pull_data
```
```
In net/core/skmsg.c (ffffffff81a3eacf)
Location: include/linux/scatterlist.h:110
Inline: True
Inline callers:
  - net/core/skmsg.c:sk_msg_zerocopy_from_iter
  - net/core/skmsg.c:sk_msg_clone
  - net/core/skmsg.c:sk_msg_alloc
```
```
In net/ipv4/tcp.c (ffffffff81ab364a)
Location: include/linux/scatterlist.h:110
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_md5_hash_skb_data
  - net/ipv4/tcp.c:tcp_md5_hash_skb_data
```
```
In net/ipv4/tcp_bpf.c (ffffffff81b17bb0)
Location: include/linux/scatterlist.h:110
Inline: True
Inline callers:
  - net/ipv4/tcp_bpf.c:tcp_bpf_sendpage
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
In kernel/dma/mapping.c (ffffffff81138ad3)
Location: include/linux/scatterlist.h:110
Inline: True
Inline callers:
  - kernel/dma/mapping.c:dma_alloc_noncontiguous
```
```
In kernel/dma/direct.c (ffffffff8113a79b)
Location: include/linux/scatterlist.h:110
Inline: True
Inline callers:
  - kernel/dma/direct.c:dma_direct_get_sgtable
```
```
In kernel/dma/ops_helpers.c (ffffffff8113abbc)
Location: include/linux/scatterlist.h:110
Inline: True
Inline callers:
  - kernel/dma/ops_helpers.c:dma_common_get_sgtable
```
```
In mm/zswap.c (ffffffff812d3f6a)
Location: include/linux/scatterlist.h:110
Inline: True
Inline callers:
  - mm/zswap.c:zswap_frontswap_load
  - mm/zswap.c:zswap_frontswap_store
  - mm/zswap.c:zswap_writeback_entry
```
```
In mm/page_reporting.c (ffffffff8131f425)
Location: include/linux/scatterlist.h:110
Inline: True
Inline callers:
  - mm/page_reporting.c:page_reporting_cycle
```
```
In fs/crypto/crypto.c (ffffffff813a87a0)
Location: include/linux/scatterlist.h:110
Inline: True
Inline callers:
  - fs/crypto/crypto.c:fscrypt_crypt_block
  - fs/crypto/crypto.c:fscrypt_crypt_block
```
```
In fs/verity/hash_algs.c (ffffffff813af9d4)
Location: include/linux/scatterlist.h:110
Inline: True
Inline callers:
  - fs/verity/hash_algs.c:fsverity_hash_page
```
```
In fs/ecryptfs/crypto.c (ffffffff81485381)
Location: include/linux/scatterlist.h:110
Inline: True
Inline callers:
  - fs/ecryptfs/crypto.c:crypt_extent
  - fs/ecryptfs/crypto.c:crypt_extent
  - fs/ecryptfs/crypto.c:virt_to_scatterlist
```
```
In security/keys/encrypted-keys/encrypted.c (ffffffff814c8825)
Location: include/linux/scatterlist.h:110
Inline: True
```
```
In crypto/scatterwalk.c (ffffffff81546d67)
Location: include/linux/scatterlist.h:110
Inline: True
Inline callers:
  - crypto/scatterwalk.c:scatterwalk_ffwd
```
```
In crypto/rsa-pkcs1pad.c (ffffffff8154c8dc)
Location: include/linux/scatterlist.h:110
Inline: True
Inline callers:
  - crypto/rsa-pkcs1pad.c:pkcs1pad_verify
  - crypto/rsa-pkcs1pad.c:pkcs1pad_decrypt
```
```
In crypto/gcm.c (ffffffff81555311)
Location: include/linux/scatterlist.h:110
Inline: True
Inline callers:
  - crypto/gcm.c:crypto_rfc4106_crypt
  - crypto/gcm.c:crypto_rfc4106_crypt
  - crypto/gcm.c:crypto_gcm_init_common
  - crypto/gcm.c:crypto_gcm_init_common
```
```
In crypto/drbg.c (ffffffff8155b2f4)
Location: include/linux/scatterlist.h:110
Inline: True
Inline callers:
  - crypto/drbg.c:drbg_kcapi_sym_ctr
  - crypto/drbg.c:drbg_kcapi_sym_ctr
```
```
In crypto/asymmetric_keys/public_key.c (ffffffff8155e779)
Location: include/linux/scatterlist.h:110
Inline: True
Inline callers:
  - crypto/asymmetric_keys/public_key.c:public_key_verify_signature
  - crypto/asymmetric_keys/public_key.c:public_key_verify_signature
```
```
In block/blk-merge.c (ffffffff8156fa31)
Location: include/linux/scatterlist.h:110
Inline: True
Inline callers:
  - block/blk-merge.c:__blk_rq_map_sg
  - block/blk-merge.c:__blk_rq_map_sg
  - block/blk-merge.c:__blk_bios_map_sg
  - block/blk-merge.c:__blk_bios_map_sg
```
```
In block/blk-integrity.c (ffffffff8159af45)
Location: include/linux/scatterlist.h:110
Inline: True
Inline callers:
  - block/blk-integrity.c:blk_rq_map_integrity_sg
```
```
In block/blk-crypto-fallback.c (ffffffff815a61d3)
Location: include/linux/scatterlist.h:110
Inline: True
Inline callers:
  - block/blk-crypto-fallback.c:blk_crypto_fallback_decrypt_bio
  - block/blk-crypto-fallback.c:blk_crypto_fallback_encrypt_bio
  - block/blk-crypto-fallback.c:blk_crypto_fallback_encrypt_bio
```
```
In lib/scatterlist.c (ffffffff815aa804)
Location: include/linux/scatterlist.h:110
Inline: True
Inline callers:
  - lib/scatterlist.c:sgl_alloc_order
  - lib/scatterlist.c:__sg_alloc_table_from_pages
  - lib/scatterlist.c:sg_init_one
```
```
In lib/kfifo.c (ffffffff815b4399)
Location: include/linux/scatterlist.h:110
Inline: True
```
```
In drivers/char/virtio_console.c (ffffffff8177276d)
Location: include/linux/scatterlist.h:110
Inline: True
Inline callers:
  - drivers/char/virtio_console.c:pipe_to_sg
  - drivers/char/virtio_console.c:pipe_to_sg
```
```
In drivers/char/agp/intel-gtt.c (ffffffff8177c331)
Location: include/linux/scatterlist.h:110
Inline: True
Inline callers:
  - drivers/char/agp/intel-gtt.c:intel_fake_agp_insert_entries
```
```
In drivers/iommu/dma-iommu.c (ffffffff817a1222)
Location: include/linux/scatterlist.h:110
Inline: True
Inline callers:
  - drivers/iommu/dma-iommu.c:iommu_dma_get_sgtable
```
```
In drivers/dma-buf/heaps/system_heap.c (ffffffff8181e68e)
Location: include/linux/scatterlist.h:110
Inline: True
Inline callers:
  - drivers/dma-buf/heaps/system_heap.c:system_heap_allocate
  - drivers/dma-buf/heaps/system_heap.c:system_heap_attach
```
```
In drivers/scsi/scsi_lib.c (ffffffff8182aa75)
Location: include/linux/scatterlist.h:110
Inline: True
Inline callers:
  - drivers/scsi/scsi_lib.c:scsi_alloc_sgtables
```
```
In drivers/spi/spi.c (ffffffff8186d637)
Location: include/linux/scatterlist.h:110
Inline: True
Inline callers:
  - drivers/spi/spi.c:spi_map_buf
  - drivers/spi/spi.c:spi_map_buf
```
```
In drivers/usb/core/devio.c (ffffffff818ba9b6)
Location: include/linux/scatterlist.h:110
Inline: True
Inline callers:
  - drivers/usb/core/devio.c:proc_do_submiturb
```
```
In drivers/mmc/core/sdio_ops.c (ffffffff8199a72b)
Location: include/linux/scatterlist.h:110
Inline: True
Inline callers:
  - drivers/mmc/core/sdio_ops.c:mmc_io_rw_extended
```
```
In net/core/skbuff.c (ffffffff819d0a6f)
Location: include/linux/scatterlist.h:110
Inline: True
Inline callers:
  - net/core/skbuff.c:__skb_to_sgvec
  - net/core/skbuff.c:__skb_to_sgvec
```
```
In net/core/filter.c (ffffffff81a14c83)
Location: include/linux/scatterlist.h:110
Inline: True
Inline callers:
  - net/core/filter.c:bpf_msg_pop_data
  - net/core/filter.c:bpf_msg_pop_data
  - net/core/filter.c:bpf_msg_push_data
  - net/core/filter.c:bpf_msg_pull_data
```
```
In net/core/skmsg.c (ffffffff81a4cf2f)
Location: include/linux/scatterlist.h:110
Inline: True
Inline callers:
  - net/core/skmsg.c:sk_msg_zerocopy_from_iter
  - net/core/skmsg.c:sk_msg_clone
  - net/core/skmsg.c:sk_msg_alloc
```
```
In net/ipv4/tcp.c (ffffffff81a9e7c8)
Location: include/linux/scatterlist.h:110
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_md5_hash_skb_data
  - net/ipv4/tcp.c:tcp_md5_hash_skb_data
```
```
In net/ipv4/tcp_bpf.c (ffffffff81b0577f)
Location: include/linux/scatterlist.h:110
Inline: True
Inline callers:
  - net/ipv4/tcp_bpf.c:tcp_bpf_sendpage
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
In kernel/dma/mapping.c (ffffffff8115b9b9)
Location: include/linux/scatterlist.h:116
Inline: True
Inline callers:
  - kernel/dma/mapping.c:dma_alloc_noncontiguous
```
```
In kernel/dma/direct.c (ffffffff8115d6c0)
Location: include/linux/scatterlist.h:116
Inline: True
Inline callers:
  - kernel/dma/direct.c:dma_direct_get_sgtable
```
```
In kernel/dma/ops_helpers.c (ffffffff8115daf5)
Location: include/linux/scatterlist.h:116
Inline: True
Inline callers:
  - kernel/dma/ops_helpers.c:dma_common_get_sgtable
```
```
In mm/zswap.c (ffffffff81319c14)
Location: include/linux/scatterlist.h:116
Inline: True
Inline callers:
  - mm/zswap.c:zswap_frontswap_load
  - mm/zswap.c:zswap_frontswap_store
  - mm/zswap.c:zswap_writeback_entry
```
```
In mm/page_reporting.c (ffffffff8136c7a8)
Location: include/linux/scatterlist.h:116
Inline: True
Inline callers:
  - mm/page_reporting.c:page_reporting_cycle
```
```
In fs/crypto/crypto.c (ffffffff813f7ee0)
Location: include/linux/scatterlist.h:116
Inline: True
Inline callers:
  - fs/crypto/crypto.c:fscrypt_crypt_block
  - fs/crypto/crypto.c:fscrypt_crypt_block
```
```
In fs/verity/hash_algs.c (ffffffff813ff5c4)
Location: include/linux/scatterlist.h:116
Inline: True
Inline callers:
  - fs/verity/hash_algs.c:fsverity_hash_page
```
```
In fs/ecryptfs/crypto.c (ffffffff814dcaa1)
Location: include/linux/scatterlist.h:116
Inline: True
Inline callers:
  - fs/ecryptfs/crypto.c:crypt_extent
  - fs/ecryptfs/crypto.c:crypt_extent
  - fs/ecryptfs/crypto.c:virt_to_scatterlist
```
```
In security/keys/encrypted-keys/encrypted.c (ffffffff815212ce)
Location: include/linux/scatterlist.h:116
Inline: True
```
```
In crypto/scatterwalk.c (ffffffff815a7547)
Location: include/linux/scatterlist.h:116
Inline: True
Inline callers:
  - crypto/scatterwalk.c:scatterwalk_ffwd
```
```
In crypto/rsa-pkcs1pad.c (ffffffff815ad0bc)
Location: include/linux/scatterlist.h:116
Inline: True
Inline callers:
  - crypto/rsa-pkcs1pad.c:pkcs1pad_verify
  - crypto/rsa-pkcs1pad.c:pkcs1pad_decrypt
```
```
In crypto/gcm.c (ffffffff815b6341)
Location: include/linux/scatterlist.h:116
Inline: True
Inline callers:
  - crypto/gcm.c:crypto_rfc4106_crypt
  - crypto/gcm.c:crypto_rfc4106_crypt
  - crypto/gcm.c:crypto_gcm_init_common
  - crypto/gcm.c:crypto_gcm_init_common
```
```
In crypto/drbg.c (ffffffff815bbc94)
Location: include/linux/scatterlist.h:116
Inline: True
Inline callers:
  - crypto/drbg.c:drbg_kcapi_sym_ctr
  - crypto/drbg.c:drbg_kcapi_sym_ctr
```
```
In crypto/asymmetric_keys/public_key.c (ffffffff815bfad3)
Location: include/linux/scatterlist.h:116
Inline: True
Inline callers:
  - crypto/asymmetric_keys/public_key.c:public_key_verify_signature
  - crypto/asymmetric_keys/public_key.c:public_key_verify_signature
```
```
In block/blk-merge.c (ffffffff815d40d1)
Location: include/linux/scatterlist.h:116
Inline: True
Inline callers:
  - block/blk-merge.c:__blk_rq_map_sg
  - block/blk-merge.c:__blk_rq_map_sg
  - block/blk-merge.c:__blk_bios_map_sg
  - block/blk-merge.c:__blk_bios_map_sg
```
```
In block/blk-integrity.c (ffffffff816031a6)
Location: include/linux/scatterlist.h:116
Inline: True
Inline callers:
  - block/blk-integrity.c:blk_rq_map_integrity_sg
```
```
In block/blk-crypto-fallback.c (ffffffff8160ecf3)
Location: include/linux/scatterlist.h:116
Inline: True
Inline callers:
  - block/blk-crypto-fallback.c:blk_crypto_fallback_decrypt_bio
  - block/blk-crypto-fallback.c:blk_crypto_fallback_encrypt_bio
  - block/blk-crypto-fallback.c:blk_crypto_fallback_encrypt_bio
```
```
In lib/scatterlist.c (ffffffff81613ac1)
Location: include/linux/scatterlist.h:116
Inline: True
Inline callers:
  - lib/scatterlist.c:sgl_alloc_order
  - lib/scatterlist.c:sg_alloc_append_table_from_pages
  - lib/scatterlist.c:sg_init_one
```
```
In lib/kfifo.c (ffffffff8161a57f)
Location: include/linux/scatterlist.h:116
Inline: True
```
```
In drivers/char/virtio_console.c (ffffffff817f7f9d)
Location: include/linux/scatterlist.h:116
Inline: True
Inline callers:
  - drivers/char/virtio_console.c:pipe_to_sg
  - drivers/char/virtio_console.c:pipe_to_sg
```
```
In drivers/char/agp/intel-gtt.c (ffffffff818024ef)
Location: include/linux/scatterlist.h:116
Inline: True
Inline callers:
  - drivers/char/agp/intel-gtt.c:intel_fake_agp_insert_entries
```
```
In drivers/iommu/dma-iommu.c (ffffffff81829e53)
Location: include/linux/scatterlist.h:116
Inline: True
Inline callers:
  - drivers/iommu/dma-iommu.c:iommu_dma_get_sgtable
```
```
In drivers/dma-buf/heaps/system_heap.c (ffffffff818a8b77)
Location: include/linux/scatterlist.h:116
Inline: True
Inline callers:
  - drivers/dma-buf/heaps/system_heap.c:system_heap_allocate
  - drivers/dma-buf/heaps/system_heap.c:system_heap_attach
```
```
In drivers/scsi/scsi_lib.c (ffffffff818b64fe)
Location: include/linux/scatterlist.h:116
Inline: True
Inline callers:
  - drivers/scsi/scsi_lib.c:scsi_alloc_sgtables
```
```
In drivers/spi/spi.c (ffffffff818fd61d)
Location: include/linux/scatterlist.h:116
Inline: True
Inline callers:
  - drivers/spi/spi.c:spi_map_buf
  - drivers/spi/spi.c:spi_map_buf
```
```
In drivers/usb/core/devio.c (ffffffff81951136)
Location: include/linux/scatterlist.h:116
Inline: True
Inline callers:
  - drivers/usb/core/devio.c:proc_do_submiturb
```
```
In drivers/mmc/core/sdio_ops.c (ffffffff81a4706b)
Location: include/linux/scatterlist.h:116
Inline: True
Inline callers:
  - drivers/mmc/core/sdio_ops.c:mmc_io_rw_extended
```
```
In net/core/skbuff.c (ffffffff81a7fc20)
Location: include/linux/scatterlist.h:116
Inline: True
Inline callers:
  - net/core/skbuff.c:__skb_to_sgvec
  - net/core/skbuff.c:__skb_to_sgvec
```
```
In net/core/filter.c (ffffffff81ac8621)
Location: include/linux/scatterlist.h:116
Inline: True
Inline callers:
  - net/core/filter.c:bpf_msg_pop_data
  - net/core/filter.c:bpf_msg_pop_data
  - net/core/filter.c:bpf_msg_push_data
  - net/core/filter.c:bpf_msg_pull_data
```
```
In net/core/skmsg.c (ffffffff81b04e1d)
Location: include/linux/scatterlist.h:116
Inline: True
Inline callers:
  - net/core/skmsg.c:sk_msg_zerocopy_from_iter
  - net/core/skmsg.c:sk_msg_clone
  - net/core/skmsg.c:sk_msg_alloc
```
```
In net/ipv4/tcp.c (ffffffff81b5a586)
Location: include/linux/scatterlist.h:116
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_md5_hash_skb_data
  - net/ipv4/tcp.c:tcp_md5_hash_skb_data
```
```
In net/ipv4/tcp_bpf.c (ffffffff81bc82dc)
Location: include/linux/scatterlist.h:116
Inline: True
Inline callers:
  - net/ipv4/tcp_bpf.c:tcp_bpf_sendpage
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
In kernel/dma/mapping.c (ffffffff811854e0)
Location: include/linux/scatterlist.h:133
Inline: True
Inline callers:
  - kernel/dma/mapping.c:dma_alloc_noncontiguous
```
```
In kernel/dma/direct.c (ffffffff811875d0)
Location: include/linux/scatterlist.h:133
Inline: True
Inline callers:
  - kernel/dma/direct.c:dma_direct_get_sgtable
```
```
In kernel/dma/ops_helpers.c (ffffffff81187a95)
Location: include/linux/scatterlist.h:133
Inline: True
Inline callers:
  - kernel/dma/ops_helpers.c:dma_common_get_sgtable
```
```
In mm/zswap.c (ffffffff81385504)
Location: include/linux/scatterlist.h:133
Inline: True
Inline callers:
  - mm/zswap.c:zswap_frontswap_load
  - mm/zswap.c:zswap_frontswap_store
  - mm/zswap.c:zswap_writeback_entry
```
```
In mm/page_reporting.c (ffffffff813ea99b)
Location: include/linux/scatterlist.h:133
Inline: True
Inline callers:
  - mm/page_reporting.c:page_reporting_cycle
```
```
In fs/crypto/crypto.c (ffffffff8146ac88)
Location: include/linux/scatterlist.h:133
Inline: True
Inline callers:
  - fs/crypto/crypto.c:fscrypt_crypt_block
  - fs/crypto/crypto.c:fscrypt_crypt_block
```
```
In fs/verity/hash_algs.c (ffffffff814731d4)
Location: include/linux/scatterlist.h:133
Inline: True
Inline callers:
  - fs/verity/hash_algs.c:fsverity_hash_page
```
```
In fs/ecryptfs/crypto.c (ffffffff8156aa35)
Location: include/linux/scatterlist.h:133
Inline: True
Inline callers:
  - fs/ecryptfs/crypto.c:crypt_extent
  - fs/ecryptfs/crypto.c:crypt_extent
  - fs/ecryptfs/crypto.c:virt_to_scatterlist
```
```
In security/keys/encrypted-keys/encrypted.c (ffffffff815b4b91)
Location: include/linux/scatterlist.h:133
Inline: True
```
```
In crypto/scatterwalk.c (ffffffff8164e646)
Location: include/linux/scatterlist.h:133
Inline: True
Inline callers:
  - crypto/scatterwalk.c:scatterwalk_ffwd
```
```
In crypto/rsa-pkcs1pad.c (ffffffff816554f1)
Location: include/linux/scatterlist.h:133
Inline: True
Inline callers:
  - crypto/rsa-pkcs1pad.c:pkcs1pad_verify
  - crypto/rsa-pkcs1pad.c:pkcs1pad_decrypt
```
```
In crypto/gcm.c (ffffffff8165f5ee)
Location: include/linux/scatterlist.h:133
Inline: True
Inline callers:
  - crypto/gcm.c:crypto_rfc4106_crypt
  - crypto/gcm.c:crypto_rfc4106_crypt
  - crypto/gcm.c:crypto_gcm_init_common
  - crypto/gcm.c:crypto_gcm_init_common
```
```
In crypto/drbg.c (ffffffff81665504)
Location: include/linux/scatterlist.h:133
Inline: True
Inline callers:
  - crypto/drbg.c:drbg_kcapi_sym_ctr
  - crypto/drbg.c:drbg_kcapi_sym_ctr
```
```
In crypto/asymmetric_keys/public_key.c (ffffffff8166a031)
Location: include/linux/scatterlist.h:133
Inline: True
Inline callers:
  - crypto/asymmetric_keys/public_key.c:public_key_verify_signature
  - crypto/asymmetric_keys/public_key.c:public_key_verify_signature
```
```
In block/blk-merge.c (ffffffff8167ff3f)
Location: include/linux/scatterlist.h:133
Inline: True
Inline callers:
  - block/blk-merge.c:__blk_rq_map_sg
  - block/blk-merge.c:__blk_bios_map_sg
  - block/blk-merge.c:__blk_bios_map_sg
```
```
In block/blk-integrity.c (ffffffff816b5a26)
Location: include/linux/scatterlist.h:133
Inline: True
Inline callers:
  - block/blk-integrity.c:blk_rq_map_integrity_sg
```
```
In block/blk-crypto-fallback.c (ffffffff816c356c)
Location: include/linux/scatterlist.h:133
Inline: True
Inline callers:
  - block/blk-crypto-fallback.c:blk_crypto_fallback_decrypt_bio
  - block/blk-crypto-fallback.c:blk_crypto_fallback_encrypt_bio
  - block/blk-crypto-fallback.c:blk_crypto_fallback_encrypt_bio
```
```
In lib/scatterlist.c (ffffffff816e0339)
Location: include/linux/scatterlist.h:133
Inline: True
Inline callers:
  - lib/scatterlist.c:sgl_alloc_order
  - lib/scatterlist.c:sg_alloc_append_table_from_pages
  - lib/scatterlist.c:sg_init_one
```
```
In lib/kfifo.c (ffffffff816e7bcf)
Location: include/linux/scatterlist.h:133
Inline: True
```
```
In drivers/char/virtio_console.c (ffffffff8193659f)
Location: include/linux/scatterlist.h:133
Inline: True
Inline callers:
  - drivers/char/virtio_console.c:pipe_to_sg
  - drivers/char/virtio_console.c:pipe_to_sg
```
```
In drivers/char/agp/intel-gtt.c (ffffffff81941cae)
Location: include/linux/scatterlist.h:133
Inline: True
Inline callers:
  - drivers/char/agp/intel-gtt.c:intel_fake_agp_insert_entries
```
```
In drivers/iommu/dma-iommu.c (ffffffff8196a2bd)
Location: include/linux/scatterlist.h:133
Inline: True
Inline callers:
  - drivers/iommu/dma-iommu.c:iommu_dma_get_sgtable
```
```
In drivers/dma-buf/heaps/system_heap.c (ffffffff819f2857)
Location: include/linux/scatterlist.h:133
Inline: True
Inline callers:
  - drivers/dma-buf/heaps/system_heap.c:system_heap_allocate
  - drivers/dma-buf/heaps/system_heap.c:system_heap_attach
```
```
In drivers/scsi/scsi_lib.c (ffffffff81a019f7)
Location: include/linux/scatterlist.h:133
Inline: True
Inline callers:
  - drivers/scsi/scsi_lib.c:scsi_alloc_sgtables
```
```
In drivers/spi/spi.c (ffffffff81a4ec67)
Location: include/linux/scatterlist.h:133
Inline: True
Inline callers:
  - drivers/spi/spi.c:spi_map_buf
  - drivers/spi/spi.c:spi_map_buf
```
```
In drivers/usb/core/devio.c (ffffffff81aaa876)
Location: include/linux/scatterlist.h:133
Inline: True
Inline callers:
  - drivers/usb/core/devio.c:proc_do_submiturb
```
```
In drivers/mmc/core/sdio_ops.c (ffffffff81bb4ed1)
Location: include/linux/scatterlist.h:133
Inline: True
Inline callers:
  - drivers/mmc/core/sdio_ops.c:mmc_io_rw_extended
```
```
In net/core/skbuff.c (ffffffff81bf4120)
Location: include/linux/scatterlist.h:133
Inline: True
Inline callers:
  - net/core/skbuff.c:__skb_to_sgvec
  - net/core/skbuff.c:__skb_to_sgvec
```
```
In net/core/filter.c (ffffffff81c44b70)
Location: include/linux/scatterlist.h:133
Inline: True
Inline callers:
  - net/core/filter.c:bpf_msg_pop_data
  - net/core/filter.c:bpf_msg_pop_data
  - net/core/filter.c:bpf_msg_push_data
  - net/core/filter.c:bpf_msg_pull_data
```
```
In net/core/skmsg.c (ffffffff81c8a68e)
Location: include/linux/scatterlist.h:133
Inline: True
Inline callers:
  - net/core/skmsg.c:sk_msg_zerocopy_from_iter
  - net/core/skmsg.c:sk_msg_clone
  - net/core/skmsg.c:sk_msg_alloc
```
```
In net/ipv4/tcp.c (ffffffff81ce90a0)
Location: include/linux/scatterlist.h:133
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_md5_hash_skb_data
  - net/ipv4/tcp.c:tcp_md5_hash_skb_data
```
```
In net/ipv4/tcp_bpf.c (ffffffff81d5db7c)
Location: include/linux/scatterlist.h:133
Inline: True
Inline callers:
  - net/ipv4/tcp_bpf.c:tcp_bpf_sendpage
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
In kernel/dma/mapping.c (ffffffff811c0d26)
Location: include/linux/scatterlist.h:136
Inline: True
Inline callers:
  - kernel/dma/mapping.c:dma_alloc_noncontiguous
```
```
In kernel/dma/direct.c (ffffffff811c31a0)
Location: include/linux/scatterlist.h:136
Inline: True
Inline callers:
  - kernel/dma/direct.c:dma_direct_get_sgtable
```
```
In kernel/dma/ops_helpers.c (ffffffff811c36e5)
Location: include/linux/scatterlist.h:136
Inline: True
Inline callers:
  - kernel/dma/ops_helpers.c:dma_common_get_sgtable
```
```
In mm/zswap.c (ffffffff81403274)
Location: include/linux/scatterlist.h:136
Inline: True
Inline callers:
  - mm/zswap.c:zswap_frontswap_load
  - mm/zswap.c:zswap_frontswap_store
  - mm/zswap.c:zswap_writeback_entry
```
```
In mm/page_reporting.c (ffffffff81472b3b)
Location: include/linux/scatterlist.h:136
Inline: True
Inline callers:
  - mm/page_reporting.c:page_reporting_cycle
```
```
In fs/crypto/crypto.c (ffffffff814fbda5)
Location: include/linux/scatterlist.h:136
Inline: True
Inline callers:
  - fs/crypto/crypto.c:fscrypt_crypt_block
  - fs/crypto/crypto.c:fscrypt_crypt_block
```
```
In fs/verity/hash_algs.c (ffffffff81505025)
Location: include/linux/scatterlist.h:136
Inline: True
Inline callers:
  - fs/verity/hash_algs.c:fsverity_hash_page
```
```
In fs/ecryptfs/crypto.c (ffffffff8160e855)
Location: include/linux/scatterlist.h:136
Inline: True
Inline callers:
  - fs/ecryptfs/crypto.c:crypt_extent
  - fs/ecryptfs/crypto.c:crypt_extent
  - fs/ecryptfs/crypto.c:virt_to_scatterlist
```
```
In security/keys/encrypted-keys/encrypted.c (ffffffff8165fb71)
Location: include/linux/scatterlist.h:136
Inline: True
```
```
In crypto/scatterwalk.c (ffffffff81707a96)
Location: include/linux/scatterlist.h:136
Inline: True
Inline callers:
  - crypto/scatterwalk.c:scatterwalk_ffwd
```
```
In crypto/rsa-pkcs1pad.c (ffffffff8170f721)
Location: include/linux/scatterlist.h:136
Inline: True
Inline callers:
  - crypto/rsa-pkcs1pad.c:pkcs1pad_verify
  - crypto/rsa-pkcs1pad.c:pkcs1pad_decrypt
```
```
In crypto/gcm.c (ffffffff8171941e)
Location: include/linux/scatterlist.h:136
Inline: True
Inline callers:
  - crypto/gcm.c:crypto_rfc4106_crypt
  - crypto/gcm.c:crypto_rfc4106_crypt
  - crypto/gcm.c:crypto_gcm_init_common
  - crypto/gcm.c:crypto_gcm_init_common
```
```
In crypto/drbg.c (ffffffff81720314)
Location: include/linux/scatterlist.h:136
Inline: True
Inline callers:
  - crypto/drbg.c:drbg_kcapi_sym_ctr
  - crypto/drbg.c:drbg_kcapi_sym_ctr
```
```
In crypto/asymmetric_keys/public_key.c (ffffffff817245fc)
Location: include/linux/scatterlist.h:136
Inline: True
Inline callers:
  - crypto/asymmetric_keys/public_key.c:public_key_verify_signature
  - crypto/asymmetric_keys/public_key.c:public_key_verify_signature
```
```
In block/blk-merge.c (ffffffff8173d2df)
Location: include/linux/scatterlist.h:136
Inline: True
Inline callers:
  - block/blk-merge.c:__blk_rq_map_sg
  - block/blk-merge.c:__blk_bios_map_sg
  - block/blk-merge.c:__blk_bios_map_sg
```
```
In block/blk-integrity.c (ffffffff81775cd6)
Location: include/linux/scatterlist.h:136
Inline: True
Inline callers:
  - block/blk-integrity.c:blk_rq_map_integrity_sg
```
```
In block/blk-crypto-fallback.c (ffffffff81784a01)
Location: include/linux/scatterlist.h:136
Inline: True
Inline callers:
  - block/blk-crypto-fallback.c:blk_crypto_fallback_decrypt_bio
  - block/blk-crypto-fallback.c:blk_crypto_fallback_encrypt_bio
  - block/blk-crypto-fallback.c:blk_crypto_fallback_encrypt_bio
```
```
In lib/scatterlist.c (ffffffff817d0639)
Location: include/linux/scatterlist.h:136
Inline: True
Inline callers:
  - lib/scatterlist.c:sgl_alloc_order
  - lib/scatterlist.c:sg_alloc_append_table_from_pages
  - lib/scatterlist.c:sg_init_one
```
```
In lib/kfifo.c (ffffffff817d7a9f)
Location: include/linux/scatterlist.h:136
Inline: True
```
```
In drivers/pci/p2pdma.c (ffffffff8191c7bc)
Location: include/linux/scatterlist.h:136
Inline: True
Inline callers:
  - drivers/pci/p2pdma.c:pci_p2pmem_alloc_sgl
```
```
In drivers/char/virtio_console.c (ffffffff81a963df)
Location: include/linux/scatterlist.h:136
Inline: True
Inline callers:
  - drivers/char/virtio_console.c:pipe_to_sg
  - drivers/char/virtio_console.c:pipe_to_sg
```
```
In drivers/char/agp/intel-gtt.c (ffffffff81aa381e)
Location: include/linux/scatterlist.h:136
Inline: True
Inline callers:
  - drivers/char/agp/intel-gtt.c:intel_fake_agp_insert_entries
```
```
In drivers/iommu/dma-iommu.c (ffffffff81ad42dd)
Location: include/linux/scatterlist.h:136
Inline: True
Inline callers:
  - drivers/iommu/dma-iommu.c:iommu_dma_get_sgtable
```
```
In drivers/dma-buf/heaps/system_heap.c (ffffffff81b7080c)
Location: include/linux/scatterlist.h:136
Inline: True
Inline callers:
  - drivers/dma-buf/heaps/system_heap.c:system_heap_allocate
  - drivers/dma-buf/heaps/system_heap.c:system_heap_attach
```
```
In drivers/scsi/scsi_lib.c (ffffffff81b80057)
Location: include/linux/scatterlist.h:136
Inline: True
Inline callers:
  - drivers/scsi/scsi_lib.c:scsi_alloc_sgtables
```
```
In drivers/spi/spi.c (ffffffff81bd04c6)
Location: include/linux/scatterlist.h:136
Inline: True
Inline callers:
  - drivers/spi/spi.c:spi_map_buf_attrs
  - drivers/spi/spi.c:spi_map_buf_attrs
```
```
In drivers/usb/core/devio.c (ffffffff81c31c7e)
Location: include/linux/scatterlist.h:136
Inline: True
Inline callers:
  - drivers/usb/core/devio.c:proc_do_submiturb
```
```
In drivers/mmc/core/sdio_ops.c (ffffffff81d595d1)
Location: include/linux/scatterlist.h:136
Inline: True
Inline callers:
  - drivers/mmc/core/sdio_ops.c:mmc_io_rw_extended
```
```
In net/core/skbuff.c (ffffffff81da1f30)
Location: include/linux/scatterlist.h:136
Inline: True
Inline callers:
  - net/core/skbuff.c:__skb_to_sgvec
  - net/core/skbuff.c:__skb_to_sgvec
```
```
In net/core/filter.c (ffffffff81dff12d)
Location: include/linux/scatterlist.h:136
Inline: True
Inline callers:
  - net/core/filter.c:bpf_msg_pop_data
  - net/core/filter.c:bpf_msg_pop_data
  - net/core/filter.c:bpf_msg_push_data
  - net/core/filter.c:bpf_msg_pull_data
```
```
In net/core/skmsg.c (ffffffff81e4528d)
Location: include/linux/scatterlist.h:136
Inline: True
Inline callers:
  - net/core/skmsg.c:sk_msg_zerocopy_from_iter
  - net/core/skmsg.c:sk_msg_clone
  - net/core/skmsg.c:sk_msg_alloc
```
```
In net/ipv4/tcp.c (ffffffff81eac620)
Location: include/linux/scatterlist.h:136
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_md5_hash_skb_data
  - net/ipv4/tcp.c:tcp_md5_hash_skb_data
```
```
In net/ipv4/tcp_bpf.c (ffffffff81f2782c)
Location: include/linux/scatterlist.h:136
Inline: True
Inline callers:
  - net/ipv4/tcp_bpf.c:tcp_bpf_sendpage
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
In kernel/dma/mapping.c (ffffffff811d3816)
Location: include/linux/scatterlist.h:136
Inline: True
Inline callers:
  - kernel/dma/mapping.c:dma_alloc_noncontiguous
```
```
In kernel/dma/direct.c (ffffffff811d5ce0)
Location: include/linux/scatterlist.h:136
Inline: True
Inline callers:
  - kernel/dma/direct.c:dma_direct_get_sgtable
```
```
In kernel/dma/ops_helpers.c (ffffffff811d6235)
Location: include/linux/scatterlist.h:136
Inline: True
Inline callers:
  - kernel/dma/ops_helpers.c:dma_common_get_sgtable
```
```
In mm/zswap.c (ffffffff814367b9)
Location: include/linux/scatterlist.h:136
Inline: True
Inline callers:
  - mm/zswap.c:zswap_frontswap_load
  - mm/zswap.c:zswap_frontswap_store
  - mm/zswap.c:zswap_writeback_entry
```
```
In mm/page_reporting.c (ffffffff814a72aa)
Location: include/linux/scatterlist.h:136
Inline: True
Inline callers:
  - mm/page_reporting.c:page_reporting_cycle
```
```
In fs/crypto/crypto.c (ffffffff815330d5)
Location: include/linux/scatterlist.h:136
Inline: True
Inline callers:
  - fs/crypto/crypto.c:fscrypt_crypt_block
  - fs/crypto/crypto.c:fscrypt_crypt_block
```
```
In fs/ecryptfs/crypto.c (ffffffff816466e5)
Location: include/linux/scatterlist.h:136
Inline: True
Inline callers:
  - fs/ecryptfs/crypto.c:crypt_extent
  - fs/ecryptfs/crypto.c:crypt_extent
  - fs/ecryptfs/crypto.c:virt_to_scatterlist
```
```
In security/keys/encrypted-keys/encrypted.c (ffffffff816984e1)
Location: include/linux/scatterlist.h:136
Inline: True
```
```
In crypto/scatterwalk.c (ffffffff81741206)
Location: include/linux/scatterlist.h:136
Inline: True
Inline callers:
  - crypto/scatterwalk.c:scatterwalk_ffwd
```
```
In crypto/rsa-pkcs1pad.c (ffffffff8174a791)
Location: include/linux/scatterlist.h:136
Inline: True
Inline callers:
  - crypto/rsa-pkcs1pad.c:pkcs1pad_verify
  - crypto/rsa-pkcs1pad.c:pkcs1pad_decrypt
```
```
In crypto/gcm.c (ffffffff81754dae)
Location: include/linux/scatterlist.h:136
Inline: True
Inline callers:
  - crypto/gcm.c:crypto_rfc4106_crypt
  - crypto/gcm.c:crypto_rfc4106_crypt
  - crypto/gcm.c:crypto_gcm_init_common
  - crypto/gcm.c:crypto_gcm_init_common
```
```
In crypto/drbg.c (ffffffff8175bc14)
Location: include/linux/scatterlist.h:136
Inline: True
Inline callers:
  - crypto/drbg.c:drbg_kcapi_sym_ctr
  - crypto/drbg.c:drbg_kcapi_sym_ctr
```
```
In block/blk-merge.c (ffffffff8177987f)
Location: include/linux/scatterlist.h:136
Inline: True
Inline callers:
  - block/blk-merge.c:__blk_rq_map_sg
  - block/blk-merge.c:__blk_bios_map_sg
  - block/blk-merge.c:__blk_bios_map_sg
```
```
In block/blk-integrity.c (ffffffff817b5986)
Location: include/linux/scatterlist.h:136
Inline: True
Inline callers:
  - block/blk-integrity.c:blk_rq_map_integrity_sg
```
```
In block/blk-crypto-fallback.c (ffffffff817c4d61)
Location: include/linux/scatterlist.h:136
Inline: True
Inline callers:
  - block/blk-crypto-fallback.c:blk_crypto_fallback_decrypt_bio
  - block/blk-crypto-fallback.c:blk_crypto_fallback_encrypt_bio
  - block/blk-crypto-fallback.c:blk_crypto_fallback_encrypt_bio
```
```
In lib/scatterlist.c (ffffffff8180f28c)
Location: include/linux/scatterlist.h:136
Inline: True
Inline callers:
  - lib/scatterlist.c:sgl_alloc_order
  - lib/scatterlist.c:sg_alloc_append_table_from_pages
  - lib/scatterlist.c:sg_init_one
```
```
In lib/kfifo.c (ffffffff81816caf)
Location: include/linux/scatterlist.h:136
Inline: True
```
```
In drivers/pci/p2pdma.c (ffffffff8195fd7c)
Location: include/linux/scatterlist.h:136
Inline: True
Inline callers:
  - drivers/pci/p2pdma.c:pci_p2pmem_alloc_sgl
```
```
In drivers/char/virtio_console.c (ffffffff81ae1bef)
Location: include/linux/scatterlist.h:136
Inline: True
Inline callers:
  - drivers/char/virtio_console.c:pipe_to_sg
  - drivers/char/virtio_console.c:pipe_to_sg
```
```
In drivers/char/agp/intel-gtt.c (ffffffff81aef0fe)
Location: include/linux/scatterlist.h:136
Inline: True
Inline callers:
  - drivers/char/agp/intel-gtt.c:intel_fake_agp_insert_entries
```
```
In drivers/iommu/dma-iommu.c (ffffffff81b22aad)
Location: include/linux/scatterlist.h:136
Inline: True
Inline callers:
  - drivers/iommu/dma-iommu.c:iommu_dma_get_sgtable
```
```
In drivers/dma-buf/heaps/system_heap.c (ffffffff81bc407a)
Location: include/linux/scatterlist.h:136
Inline: True
Inline callers:
  - drivers/dma-buf/heaps/system_heap.c:system_heap_allocate
  - drivers/dma-buf/heaps/system_heap.c:system_heap_attach
```
```
In drivers/scsi/scsi_lib.c (ffffffff81bd40b9)
Location: include/linux/scatterlist.h:136
Inline: True
Inline callers:
  - drivers/scsi/scsi_lib.c:scsi_alloc_sgtables
```
```
In drivers/spi/spi.c (ffffffff81c28146)
Location: include/linux/scatterlist.h:136
Inline: True
Inline callers:
  - drivers/spi/spi.c:spi_map_buf_attrs
  - drivers/spi/spi.c:spi_map_buf_attrs
```
```
In drivers/net/virtio_net.c (ffffffff81c4e522)
Location: include/linux/scatterlist.h:136
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
  - drivers/net/virtio_net.c:__virtnet_xdp_xmit_one
```
```
In drivers/usb/core/devio.c (ffffffff81c98efe)
Location: include/linux/scatterlist.h:136
Inline: True
Inline callers:
  - drivers/usb/core/devio.c:proc_do_submiturb
```
```
In drivers/mmc/core/sdio_ops.c (ffffffff81dc3f7e)
Location: include/linux/scatterlist.h:136
Inline: True
Inline callers:
  - drivers/mmc/core/sdio_ops.c:mmc_io_rw_extended
```
```
In net/core/skbuff.c (ffffffff81e10793)
Location: include/linux/scatterlist.h:136
Inline: True
Inline callers:
  - net/core/skbuff.c:__skb_to_sgvec
  - net/core/skbuff.c:__skb_to_sgvec
```
```
In net/core/filter.c (ffffffff81e70bfd)
Location: include/linux/scatterlist.h:136
Inline: True
Inline callers:
  - net/core/filter.c:bpf_msg_pop_data
  - net/core/filter.c:bpf_msg_pop_data
  - net/core/filter.c:bpf_msg_push_data
  - net/core/filter.c:bpf_msg_pull_data
```
```
In net/core/skmsg.c (ffffffff81ea087d)
Location: include/linux/scatterlist.h:136
Inline: True
Inline callers:
  - net/core/skmsg.c:sk_msg_zerocopy_from_iter
  - net/core/skmsg.c:sk_msg_clone
  - net/core/skmsg.c:sk_msg_alloc
```
```
In net/ipv4/tcp.c (ffffffff81f0ad01)
Location: include/linux/scatterlist.h:136
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_md5_hash_skb_data
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
In kernel/dma/mapping.c (ffffffff811e84b2)
Location: include/linux/scatterlist.h:136
Inline: True
Inline callers:
  - kernel/dma/mapping.c:dma_alloc_noncontiguous
```
```
In kernel/dma/direct.c (ffffffff811eac60)
Location: include/linux/scatterlist.h:136
Inline: True
Inline callers:
  - kernel/dma/direct.c:dma_direct_get_sgtable
```
```
In kernel/dma/ops_helpers.c (ffffffff811eb265)
Location: include/linux/scatterlist.h:136
Inline: True
Inline callers:
  - kernel/dma/ops_helpers.c:dma_common_get_sgtable
```
```
In mm/zswap.c (ffffffff81470abd)
Location: include/linux/scatterlist.h:136
Inline: True
Inline callers:
  - mm/zswap.c:zswap_store
  - mm/zswap.c:__zswap_load
```
```
In mm/page_reporting.c (ffffffff814d82aa)
Location: include/linux/scatterlist.h:136
Inline: True
Inline callers:
  - mm/page_reporting.c:page_reporting_cycle
```
```
In fs/crypto/crypto.c (ffffffff81567fd2)
Location: include/linux/scatterlist.h:136
Inline: True
Inline callers:
  - fs/crypto/crypto.c:fscrypt_crypt_data_unit
  - fs/crypto/crypto.c:fscrypt_crypt_data_unit
```
```
In fs/ecryptfs/crypto.c (ffffffff8167fba5)
Location: include/linux/scatterlist.h:136
Inline: True
Inline callers:
  - fs/ecryptfs/crypto.c:crypt_extent
  - fs/ecryptfs/crypto.c:crypt_extent
  - fs/ecryptfs/crypto.c:virt_to_scatterlist
```
```
In security/keys/encrypted-keys/encrypted.c (ffffffff816d4b61)
Location: include/linux/scatterlist.h:136
Inline: True
```
```
In crypto/scatterwalk.c (ffffffff817820a6)
Location: include/linux/scatterlist.h:136
Inline: True
Inline callers:
  - crypto/scatterwalk.c:scatterwalk_ffwd
```
```
In crypto/rsa-pkcs1pad.c (ffffffff8178c351)
Location: include/linux/scatterlist.h:136
Inline: True
Inline callers:
  - crypto/rsa-pkcs1pad.c:pkcs1pad_verify
  - crypto/rsa-pkcs1pad.c:pkcs1pad_decrypt
```
```
In crypto/gcm.c (ffffffff81796d6e)
Location: include/linux/scatterlist.h:136
Inline: True
Inline callers:
  - crypto/gcm.c:crypto_rfc4106_crypt
  - crypto/gcm.c:crypto_rfc4106_crypt
  - crypto/gcm.c:crypto_gcm_init_common
  - crypto/gcm.c:crypto_gcm_init_common
```
```
In crypto/drbg.c (ffffffff8179db14)
Location: include/linux/scatterlist.h:136
Inline: True
Inline callers:
  - crypto/drbg.c:drbg_kcapi_sym_ctr
  - crypto/drbg.c:drbg_kcapi_sym_ctr
```
```
In block/blk-merge.c (ffffffff817bbc4f)
Location: include/linux/scatterlist.h:136
Inline: True
Inline callers:
  - block/blk-merge.c:__blk_rq_map_sg
  - block/blk-merge.c:__blk_bios_map_sg
  - block/blk-merge.c:__blk_bios_map_sg
```
```
In block/blk-integrity.c (ffffffff817fa396)
Location: include/linux/scatterlist.h:136
Inline: True
Inline callers:
  - block/blk-integrity.c:blk_rq_map_integrity_sg
```
```
In block/blk-crypto-fallback.c (ffffffff81809a51)
Location: include/linux/scatterlist.h:136
Inline: True
Inline callers:
  - block/blk-crypto-fallback.c:blk_crypto_fallback_decrypt_bio
  - block/blk-crypto-fallback.c:blk_crypto_fallback_encrypt_bio
  - block/blk-crypto-fallback.c:blk_crypto_fallback_encrypt_bio
```
```
In lib/scatterlist.c (ffffffff81854f0c)
Location: include/linux/scatterlist.h:136
Inline: True
Inline callers:
  - lib/scatterlist.c:sgl_alloc_order
  - lib/scatterlist.c:sg_alloc_append_table_from_pages
  - lib/scatterlist.c:sg_init_one
```
```
In lib/kfifo.c (ffffffff8185bf8f)
Location: include/linux/scatterlist.h:136
Inline: True
```
```
In drivers/pci/p2pdma.c (ffffffff819a946b)
Location: include/linux/scatterlist.h:136
Inline: True
Inline callers:
  - drivers/pci/p2pdma.c:pci_p2pmem_alloc_sgl
```
```
In drivers/char/virtio_console.c (ffffffff81b34fdf)
Location: include/linux/scatterlist.h:136
Inline: True
Inline callers:
  - drivers/char/virtio_console.c:pipe_to_sg
  - drivers/char/virtio_console.c:pipe_to_sg
```
```
In drivers/char/agp/intel-gtt.c (ffffffff81b4263e)
Location: include/linux/scatterlist.h:136
Inline: True
Inline callers:
  - drivers/char/agp/intel-gtt.c:intel_fake_agp_insert_entries
```
```
In drivers/iommu/dma-iommu.c (ffffffff81b796ed)
Location: include/linux/scatterlist.h:136
Inline: True
Inline callers:
  - drivers/iommu/dma-iommu.c:iommu_dma_get_sgtable
```
```
In drivers/dma-buf/heaps/system_heap.c (ffffffff81c1887f)
Location: include/linux/scatterlist.h:136
Inline: True
Inline callers:
  - drivers/dma-buf/heaps/system_heap.c:system_heap_allocate
  - drivers/dma-buf/heaps/system_heap.c:system_heap_attach
```
```
In drivers/scsi/scsi_lib.c (ffffffff81c28d29)
Location: include/linux/scatterlist.h:136
Inline: True
Inline callers:
  - drivers/scsi/scsi_lib.c:scsi_alloc_sgtables
```
```
In drivers/spi/spi.c (ffffffff81cda896)
Location: include/linux/scatterlist.h:136
Inline: True
Inline callers:
  - drivers/spi/spi.c:spi_map_buf_attrs
  - drivers/spi/spi.c:spi_map_buf_attrs
```
```
In drivers/net/virtio_net.c (ffffffff81d04602)
Location: include/linux/scatterlist.h:136
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
  - drivers/net/virtio_net.c:__virtnet_xdp_xmit_one
```
```
In drivers/usb/core/devio.c (ffffffff81d4da6e)
Location: include/linux/scatterlist.h:136
Inline: True
Inline callers:
  - drivers/usb/core/devio.c:proc_do_submiturb
```
```
In drivers/mmc/core/sdio_ops.c (ffffffff81e7c85e)
Location: include/linux/scatterlist.h:136
Inline: True
Inline callers:
  - drivers/mmc/core/sdio_ops.c:mmc_io_rw_extended
```
```
In net/core/skbuff.c (ffffffff81ecd2b3)
Location: include/linux/scatterlist.h:136
Inline: True
Inline callers:
  - net/core/skbuff.c:__skb_to_sgvec
  - net/core/skbuff.c:__skb_to_sgvec
```
```
In net/core/filter.c (ffffffff81f302d4)
Location: include/linux/scatterlist.h:136
Inline: True
Inline callers:
  - net/core/filter.c:bpf_msg_pop_data
  - net/core/filter.c:bpf_msg_pop_data
  - net/core/filter.c:bpf_msg_push_data
  - net/core/filter.c:bpf_msg_pull_data
```
```
In net/core/skmsg.c (ffffffff81f63027)
Location: include/linux/scatterlist.h:136
Inline: True
Inline callers:
  - net/core/skmsg.c:sk_msg_zerocopy_from_iter
  - net/core/skmsg.c:sk_msg_clone
  - net/core/skmsg.c:sk_msg_alloc
```
```
In net/ipv4/tcp_sigpool.c (ffffffff8204c872)
Location: include/linux/scatterlist.h:136
Inline: True
Inline callers:
  - net/ipv4/tcp_sigpool.c:tcp_sigpool_hash_skb_data
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
In kernel/dma/mapping.c (ffff800010194150)
Location: include/linux/scatterlist.h:116
Inline: True
Inline callers:
  - kernel/dma/mapping.c:dma_common_get_sgtable
```
```
In fs/crypto/crypto.c (ffff80001040b060)
Location: include/linux/scatterlist.h:116
Inline: True
Inline callers:
  - fs/crypto/crypto.c:fscrypt_crypt_block
  - fs/crypto/crypto.c:fscrypt_crypt_block
```
```
In fs/verity/hash_algs.c (ffff800010412004)
Location: include/linux/scatterlist.h:116
Inline: True
Inline callers:
  - fs/verity/hash_algs.c:fsverity_hash_page
```
```
In fs/ecryptfs/crypto.c (ffff8000104f7374)
Location: include/linux/scatterlist.h:116
Inline: True
Inline callers:
  - fs/ecryptfs/crypto.c:crypt_extent
  - fs/ecryptfs/crypto.c:crypt_extent
  - fs/ecryptfs/crypto.c:virt_to_scatterlist
```
```
In security/keys/big_key.c (ffff800010539b04)
Location: include/linux/scatterlist.h:116
Inline: True
Inline callers:
  - security/keys/big_key.c:big_key_alloc_buffer
```
```
In security/keys/encrypted-keys/encrypted.c (ffff80001053d510)
Location: include/linux/scatterlist.h:116
Inline: True
```
```
In crypto/scatterwalk.c (ffff8000105baf84)
Location: include/linux/scatterlist.h:116
Inline: True
```
```
In crypto/rsa-pkcs1pad.c (ffff8000105c3ea0)
Location: include/linux/scatterlist.h:116
Inline: True
Inline callers:
  - crypto/rsa-pkcs1pad.c:pkcs1pad_sg_set_buf
```
```
In crypto/gcm.c (ffff8000105ccfb0)
Location: include/linux/scatterlist.h:116
Inline: True
Inline callers:
  - crypto/gcm.c:crypto_rfc4106_crypt
  - crypto/gcm.c:crypto_rfc4106_crypt
  - crypto/gcm.c:crypto_gcm_init_common
  - crypto/gcm.c:crypto_gcm_init_common
```
```
In crypto/drbg.c (ffff8000105d1d74)
Location: include/linux/scatterlist.h:116
Inline: True
Inline callers:
  - crypto/drbg.c:drbg_kcapi_sym_ctr
  - crypto/drbg.c:drbg_kcapi_sym_ctr
```
```
In crypto/asymmetric_keys/public_key.c (ffff8000105d5b10)
Location: include/linux/scatterlist.h:116
Inline: True
Inline callers:
  - crypto/asymmetric_keys/public_key.c:public_key_verify_signature
  - crypto/asymmetric_keys/public_key.c:public_key_verify_signature
```
```
In block/blk-merge.c (ffff8000105ea1a4)
Location: include/linux/scatterlist.h:116
Inline: True
Inline callers:
  - block/blk-merge.c:blk_rq_map_sg
  - block/blk-merge.c:blk_rq_map_sg
  - block/blk-merge.c:blk_rq_map_sg
  - block/blk-merge.c:__blk_bios_map_sg
  - block/blk-merge.c:__blk_bios_map_sg
```
```
In block/blk-integrity.c (ffff80001061e258)
Location: include/linux/scatterlist.h:116
Inline: True
Inline callers:
  - block/blk-integrity.c:blk_rq_map_integrity_sg
```
```
In lib/scatterlist.c (ffff80001062cdc8)
Location: include/linux/scatterlist.h:116
Inline: True
Inline callers:
  - lib/scatterlist.c:sgl_alloc_order
  - lib/scatterlist.c:sg_init_one
```
```
In lib/kfifo.c (ffff800010634160)
Location: include/linux/scatterlist.h:116
Inline: True
```
```
In drivers/video/fbdev/mx3fb.c (ffff80001075f4b8)
Location: include/linux/scatterlist.h:116
Inline: True
Inline callers:
  - drivers/video/fbdev/mx3fb.c:mx3fb_pan_display
  - drivers/video/fbdev/mx3fb.c:__set_par
```
```
In drivers/tty/serial/amba-pl011.c (ffff800010894adc)
Location: include/linux/scatterlist.h:116
Inline: True
```
```
In drivers/tty/serial/imx.c (ffff80001089abf4)
Location: include/linux/scatterlist.h:116
Inline: True
Inline callers:
  - drivers/tty/serial/imx.c:imx_uart_dma_tx
  - drivers/tty/serial/imx.c:imx_uart_dma_tx
```
```
In drivers/char/virtio_console.c (ffff8000108b2bf4)
Location: include/linux/scatterlist.h:116
Inline: True
Inline callers:
  - drivers/char/virtio_console.c:pipe_to_sg
  - drivers/char/virtio_console.c:pipe_to_sg
```
```
In drivers/iommu/dma-iommu.c (ffff8000108c92c0)
Location: include/linux/scatterlist.h:116
Inline: True
Inline callers:
  - drivers/iommu/dma-iommu.c:iommu_dma_get_sgtable
```
```
In drivers/spi/spi.c (ffff8000109c85a0)
Location: include/linux/scatterlist.h:116
Inline: True
Inline callers:
  - drivers/spi/spi.c:spi_map_buf
  - drivers/spi/spi.c:spi_map_buf
```
```
In drivers/usb/core/devio.c (ffff800010a2ed70)
Location: include/linux/scatterlist.h:116
Inline: True
Inline callers:
  - drivers/usb/core/devio.c:proc_do_submiturb
```
```
In drivers/mmc/core/sdio_ops.c (ffff800010b3ac44)
Location: include/linux/scatterlist.h:116
Inline: True
Inline callers:
  - drivers/mmc/core/sdio_ops.c:mmc_io_rw_extended
```
```
In net/core/skbuff.c (ffff800010bb2984)
Location: include/linux/scatterlist.h:116
Inline: True
Inline callers:
  - net/core/skbuff.c:__skb_to_sgvec
  - net/core/skbuff.c:__skb_to_sgvec
```
```
In net/core/filter.c (ffff800010bfdb40)
Location: include/linux/scatterlist.h:116
Inline: True
Inline callers:
  - net/core/filter.c:bpf_msg_pop_data
  - net/core/filter.c:bpf_msg_pop_data
  - net/core/filter.c:bpf_msg_push_data
  - net/core/filter.c:bpf_msg_pull_data
```
```
In net/core/skmsg.c (ffff800010c0e508)
Location: include/linux/scatterlist.h:116
Inline: True
Inline callers:
  - net/core/skmsg.c:sk_msg_zerocopy_from_iter
  - net/core/skmsg.c:sk_msg_clone
  - net/core/skmsg.c:sk_msg_alloc
```
```
In net/ipv4/tcp.c (ffff800010c6fb90)
Location: include/linux/scatterlist.h:116
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_md5_hash_skb_data
  - net/ipv4/tcp.c:tcp_md5_hash_skb_data
```
```
In net/ipv4/tcp_bpf.c (ffff800010cd3e74)
Location: include/linux/scatterlist.h:116
Inline: True
Inline callers:
  - net/ipv4/tcp_bpf.c:tcp_bpf_sendpage
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
In arch/arm/mm/dma-mapping.c (c031bd1c)
Location: include/linux/scatterlist.h:116
Inline: True
```
```
In kernel/dma/mapping.c (c03e145c)
Location: include/linux/scatterlist.h:116
Inline: True
```
```
In fs/crypto/crypto.c (c05d81f8)
Location: include/linux/scatterlist.h:116
Inline: True
Inline callers:
  - fs/crypto/crypto.c:fscrypt_crypt_block
  - fs/crypto/crypto.c:fscrypt_crypt_block
  - fs/crypto/crypto.c:fscrypt_crypt_block
```
```
In fs/verity/hash_algs.c (c05de65c)
Location: include/linux/scatterlist.h:116
Inline: True
Inline callers:
  - fs/verity/hash_algs.c:fsverity_hash_page
```
```
In fs/ecryptfs/crypto.c (c06b4b1c)
Location: include/linux/scatterlist.h:116
Inline: True
Inline callers:
  - fs/ecryptfs/crypto.c:crypt_extent
  - fs/ecryptfs/crypto.c:crypt_extent
  - fs/ecryptfs/crypto.c:crypt_extent
  - fs/ecryptfs/crypto.c:virt_to_scatterlist
  - fs/ecryptfs/crypto.c:virt_to_scatterlist
```
```
In security/keys/big_key.c (c06f0090)
Location: include/linux/scatterlist.h:116
Inline: True
Inline callers:
  - security/keys/big_key.c:big_key_alloc_buffer
```
```
In security/keys/encrypted-keys/encrypted.c (c06f2edc)
Location: include/linux/scatterlist.h:116
Inline: True
```
```
In crypto/scatterwalk.c (c07692b4)
Location: include/linux/scatterlist.h:116
Inline: True
```
```
In crypto/rsa-pkcs1pad.c (c0771780)
Location: include/linux/scatterlist.h:116
Inline: True
Inline callers:
  - crypto/rsa-pkcs1pad.c:pkcs1pad_verify
  - crypto/rsa-pkcs1pad.c:pkcs1pad_decrypt
```
```
In crypto/gcm.c (c077a81c)
Location: include/linux/scatterlist.h:116
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
In crypto/drbg.c (c077f614)
Location: include/linux/scatterlist.h:116
Inline: True
Inline callers:
  - crypto/drbg.c:drbg_kcapi_sym_ctr
  - crypto/drbg.c:drbg_kcapi_sym_ctr
  - crypto/drbg.c:drbg_kcapi_sym_ctr
```
```
In crypto/asymmetric_keys/public_key.c (c07835e4)
Location: include/linux/scatterlist.h:116
Inline: True
Inline callers:
  - crypto/asymmetric_keys/public_key.c:public_key_verify_signature
  - crypto/asymmetric_keys/public_key.c:public_key_verify_signature
  - crypto/asymmetric_keys/public_key.c:public_key_verify_signature
```
```
In block/blk-merge.c (c0796794)
Location: include/linux/scatterlist.h:116
Inline: True
Inline callers:
  - block/blk-merge.c:blk_rq_map_sg
  - block/blk-merge.c:blk_rq_map_sg
  - block/blk-merge.c:blk_rq_map_sg
  - block/blk-merge.c:blk_rq_map_sg
  - block/blk-merge.c:__blk_bios_map_sg
  - block/blk-merge.c:__blk_bios_map_sg
  - block/blk-merge.c:__blk_bios_map_sg
```
```
In block/blk-integrity.c (c07c5e50)
Location: include/linux/scatterlist.h:116
Inline: True
Inline callers:
  - block/blk-integrity.c:blk_rq_map_integrity_sg
```
```
In lib/scatterlist.c (c07d36c0)
Location: include/linux/scatterlist.h:116
Inline: True
Inline callers:
  - lib/scatterlist.c:sgl_alloc_order
  - lib/scatterlist.c:sgl_alloc_order
  - lib/scatterlist.c:sg_init_one
  - lib/scatterlist.c:sg_init_one
```
```
In lib/kfifo.c (c07da430)
Location: include/linux/scatterlist.h:116
Inline: True
```
```
In drivers/video/fbdev/mx3fb.c (c08e255c)
Location: include/linux/scatterlist.h:116
Inline: True
Inline callers:
  - drivers/video/fbdev/mx3fb.c:mx3fb_pan_display
  - drivers/video/fbdev/mx3fb.c:mx3fb_pan_display
  - drivers/video/fbdev/mx3fb.c:__set_par
  - drivers/video/fbdev/mx3fb.c:__set_par
```
```
In drivers/tty/serial/amba-pl011.c (c0990a98)
Location: include/linux/scatterlist.h:116
Inline: True
```
```
In drivers/tty/serial/imx.c (c0997b1c)
Location: include/linux/scatterlist.h:116
Inline: True
Inline callers:
  - drivers/tty/serial/imx.c:imx_uart_dma_tx
  - drivers/tty/serial/imx.c:imx_uart_dma_tx
  - drivers/tty/serial/imx.c:imx_uart_dma_tx
```
```
In drivers/char/virtio_console.c (c09af104)
Location: include/linux/scatterlist.h:116
Inline: True
Inline callers:
  - drivers/char/virtio_console.c:pipe_to_sg
  - drivers/char/virtio_console.c:pipe_to_sg
  - drivers/char/virtio_console.c:pipe_to_sg
```
```
In drivers/spi/spi.c (c0ab2248)
Location: include/linux/scatterlist.h:116
Inline: True
Inline callers:
  - drivers/spi/spi.c:spi_map_buf
  - drivers/spi/spi.c:spi_map_buf
  - drivers/spi/spi.c:spi_map_buf
```
```
In drivers/usb/core/devio.c (c0b04bbc)
Location: include/linux/scatterlist.h:116
Inline: True
Inline callers:
  - drivers/usb/core/devio.c:proc_do_submiturb
```
```
In drivers/mmc/core/sdio_ops.c (c0c155f8)
Location: include/linux/scatterlist.h:116
Inline: True
Inline callers:
  - drivers/mmc/core/sdio_ops.c:mmc_io_rw_extended
```
```
In net/core/skbuff.c (c0cd0e94)
Location: include/linux/scatterlist.h:116
Inline: True
Inline callers:
  - net/core/skbuff.c:__skb_to_sgvec
  - net/core/skbuff.c:__skb_to_sgvec
  - net/core/skbuff.c:__skb_to_sgvec
```
```
In net/core/filter.c (c0d19df8)
Location: include/linux/scatterlist.h:116
Inline: True
Inline callers:
  - net/core/filter.c:bpf_msg_pop_data
  - net/core/filter.c:bpf_msg_pop_data
  - net/core/filter.c:bpf_msg_pop_data
  - net/core/filter.c:bpf_msg_push_data
  - net/core/filter.c:bpf_msg_push_data
  - net/core/filter.c:bpf_msg_pull_data
  - net/core/filter.c:bpf_msg_pull_data
```
```
In net/core/skmsg.c (c0d270a0)
Location: include/linux/scatterlist.h:116
Inline: True
Inline callers:
  - net/core/skmsg.c:sk_msg_zerocopy_from_iter
  - net/core/skmsg.c:sk_msg_zerocopy_from_iter
  - net/core/skmsg.c:sk_msg_clone
  - net/core/skmsg.c:sk_msg_alloc
  - net/core/skmsg.c:sk_msg_alloc
```
```
In net/ipv4/tcp.c (c0d7eff4)
Location: include/linux/scatterlist.h:116
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_md5_hash_skb_data
  - net/ipv4/tcp.c:tcp_md5_hash_skb_data
  - net/ipv4/tcp.c:tcp_md5_hash_skb_data
```
```
In net/ipv4/tcp_bpf.c (c0dddd58)
Location: include/linux/scatterlist.h:116
Inline: True
Inline callers:
  - net/ipv4/tcp_bpf.c:tcp_bpf_sendpage
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
In kernel/dma/mapping.c (c0000000001f4454)
Location: include/linux/scatterlist.h:116
Inline: True
Inline callers:
  - kernel/dma/mapping.c:dma_common_get_sgtable
```
```
In fs/crypto/crypto.c (c000000000517b20)
Location: include/linux/scatterlist.h:116
Inline: True
Inline callers:
  - fs/crypto/crypto.c:fscrypt_crypt_block
  - fs/crypto/crypto.c:fscrypt_crypt_block
```
```
In fs/verity/hash_algs.c (c00000000051fcec)
Location: include/linux/scatterlist.h:116
Inline: True
Inline callers:
  - fs/verity/hash_algs.c:fsverity_hash_page
```
```
In fs/ecryptfs/crypto.c (c0000000006388cc)
Location: include/linux/scatterlist.h:116
Inline: True
Inline callers:
  - fs/ecryptfs/crypto.c:crypt_extent
  - fs/ecryptfs/crypto.c:crypt_extent
  - fs/ecryptfs/crypto.c:virt_to_scatterlist
```
```
In security/keys/big_key.c (c0000000006887b0)
Location: include/linux/scatterlist.h:116
Inline: True
Inline callers:
  - security/keys/big_key.c:big_key_alloc_buffer
```
```
In security/keys/encrypted-keys/encrypted.c (c00000000068ca10)
Location: include/linux/scatterlist.h:116
Inline: True
```
```
In crypto/scatterwalk.c (c00000000074160c)
Location: include/linux/scatterlist.h:116
Inline: True
```
```
In crypto/rsa-pkcs1pad.c (c00000000074c9dc)
Location: include/linux/scatterlist.h:116
Inline: True
Inline callers:
  - crypto/rsa-pkcs1pad.c:pkcs1pad_sg_set_buf
```
```
In crypto/gcm.c (c000000000757e10)
Location: include/linux/scatterlist.h:116
Inline: True
Inline callers:
  - crypto/gcm.c:crypto_rfc4106_crypt
  - crypto/gcm.c:crypto_rfc4106_crypt
  - crypto/gcm.c:crypto_gcm_init_common
  - crypto/gcm.c:crypto_gcm_init_common
```
```
In crypto/drbg.c (c00000000075ecf0)
Location: include/linux/scatterlist.h:116
Inline: True
Inline callers:
  - crypto/drbg.c:drbg_kcapi_sym_ctr
  - crypto/drbg.c:drbg_kcapi_sym_ctr
```
```
In crypto/asymmetric_keys/public_key.c (c0000000007642d8)
Location: include/linux/scatterlist.h:116
Inline: True
Inline callers:
  - crypto/asymmetric_keys/public_key.c:public_key_verify_signature
  - crypto/asymmetric_keys/public_key.c:public_key_verify_signature
```
```
In block/blk-merge.c (c00000000077f168)
Location: include/linux/scatterlist.h:116
Inline: True
Inline callers:
  - block/blk-merge.c:blk_rq_map_sg
  - block/blk-merge.c:blk_rq_map_sg
  - block/blk-merge.c:blk_rq_map_sg
  - block/blk-merge.c:__blk_bios_map_sg
  - block/blk-merge.c:__blk_bios_map_sg
```
```
In block/blk-integrity.c (c0000000007bd408)
Location: include/linux/scatterlist.h:116
Inline: True
Inline callers:
  - block/blk-integrity.c:blk_rq_map_integrity_sg
```
```
In lib/scatterlist.c (c0000000007cfb78)
Location: include/linux/scatterlist.h:116
Inline: True
Inline callers:
  - lib/scatterlist.c:sgl_alloc_order
  - lib/scatterlist.c:sg_init_one
```
```
In lib/kfifo.c (c0000000007d9834)
Location: include/linux/scatterlist.h:116
Inline: True
```
```
In drivers/char/virtio_console.c (c00000000094cee0)
Location: include/linux/scatterlist.h:116
Inline: True
Inline callers:
  - drivers/char/virtio_console.c:pipe_to_sg
  - drivers/char/virtio_console.c:pipe_to_sg
```
```
In drivers/spi/spi.c (c000000000a8a050)
Location: include/linux/scatterlist.h:116
Inline: True
Inline callers:
  - drivers/spi/spi.c:spi_map_buf
  - drivers/spi/spi.c:spi_map_buf
```
```
In drivers/usb/core/devio.c (c000000000aee204)
Location: include/linux/scatterlist.h:116
Inline: True
Inline callers:
  - drivers/usb/core/devio.c:proc_do_submiturb
```
```
In drivers/mmc/core/sdio_ops.c (c000000000c37678)
Location: include/linux/scatterlist.h:116
Inline: True
Inline callers:
  - drivers/mmc/core/sdio_ops.c:mmc_io_rw_extended
```
```
In net/core/skbuff.c (c000000000c8a9c4)
Location: include/linux/scatterlist.h:116
Inline: True
Inline callers:
  - net/core/skbuff.c:__skb_to_sgvec
  - net/core/skbuff.c:__skb_to_sgvec
```
```
In net/core/filter.c (c000000000ce9500)
Location: include/linux/scatterlist.h:116
Inline: True
Inline callers:
  - net/core/filter.c:bpf_msg_pop_data
  - net/core/filter.c:bpf_msg_pop_data
  - net/core/filter.c:bpf_msg_push_data
  - net/core/filter.c:bpf_msg_pull_data
```
```
In net/core/skmsg.c (c000000000cfacb8)
Location: include/linux/scatterlist.h:116
Inline: True
Inline callers:
  - net/core/skmsg.c:sk_msg_zerocopy_from_iter
  - net/core/skmsg.c:sk_msg_clone
  - net/core/skmsg.c:sk_msg_alloc
```
```
In net/ipv4/tcp.c (c000000000d766e0)
Location: include/linux/scatterlist.h:116
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_md5_hash_skb_data
  - net/ipv4/tcp.c:tcp_md5_hash_skb_data
```
```
In net/ipv4/tcp_bpf.c (c000000000df320c)
Location: include/linux/scatterlist.h:116
Inline: True
Inline callers:
  - net/ipv4/tcp_bpf.c:tcp_bpf_sendpage
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
In kernel/dma/mapping.c (ffffffe0001263ae)
Location: include/linux/scatterlist.h:116
Inline: True
Inline callers:
  - kernel/dma/mapping.c:dma_common_get_sgtable
```
```
In fs/crypto/crypto.c (ffffffe0002b4d80)
Location: include/linux/scatterlist.h:116
Inline: True
Inline callers:
  - fs/crypto/crypto.c:fscrypt_crypt_block
  - fs/crypto/crypto.c:fscrypt_crypt_block
  - fs/crypto/crypto.c:fscrypt_crypt_block
```
```
In fs/verity/hash_algs.c (ffffffe0002ba0c2)
Location: include/linux/scatterlist.h:116
Inline: True
Inline callers:
  - fs/verity/hash_algs.c:fsverity_hash_page
```
```
In fs/ecryptfs/crypto.c (ffffffe000365e3e)
Location: include/linux/scatterlist.h:116
Inline: True
Inline callers:
  - fs/ecryptfs/crypto.c:crypt_extent
  - fs/ecryptfs/crypto.c:crypt_extent
  - fs/ecryptfs/crypto.c:crypt_extent
  - fs/ecryptfs/crypto.c:virt_to_scatterlist
```
```
In security/keys/big_key.c (ffffffe000398156)
Location: include/linux/scatterlist.h:116
Inline: True
Inline callers:
  - security/keys/big_key.c:big_key_alloc_buffer
```
```
In security/keys/encrypted-keys/encrypted.c (ffffffe00039a96c)
Location: include/linux/scatterlist.h:116
Inline: True
```
```
In crypto/scatterwalk.c (ffffffe000400cba)
Location: include/linux/scatterlist.h:116
Inline: True
```
```
In crypto/rsa-pkcs1pad.c (ffffffe000407e60)
Location: include/linux/scatterlist.h:116
Inline: True
Inline callers:
  - crypto/rsa-pkcs1pad.c:pkcs1pad_sg_set_buf
```
```
In crypto/gcm.c (ffffffe00040ffa4)
Location: include/linux/scatterlist.h:116
Inline: True
Inline callers:
  - crypto/gcm.c:crypto_rfc4106_crypt
  - crypto/gcm.c:crypto_rfc4106_crypt
  - crypto/gcm.c:crypto_gcm_init_common
  - crypto/gcm.c:crypto_gcm_init_common
```
```
In crypto/drbg.c (ffffffe000415502)
Location: include/linux/scatterlist.h:116
Inline: True
Inline callers:
  - crypto/drbg.c:drbg_kcapi_sym_ctr
  - crypto/drbg.c:drbg_kcapi_sym_ctr
```
```
In crypto/asymmetric_keys/public_key.c (ffffffe000419c96)
Location: include/linux/scatterlist.h:116
Inline: True
Inline callers:
  - crypto/asymmetric_keys/public_key.c:public_key_verify_signature
  - crypto/asymmetric_keys/public_key.c:public_key_verify_signature
```
```
In block/blk-merge.c (ffffffe00042a5cc)
Location: include/linux/scatterlist.h:116
Inline: True
Inline callers:
  - block/blk-merge.c:blk_rq_map_sg
  - block/blk-merge.c:blk_rq_map_sg
  - block/blk-merge.c:blk_rq_map_sg
  - block/blk-merge.c:blk_rq_map_sg
  - block/blk-merge.c:__blk_bios_map_sg
  - block/blk-merge.c:__blk_bios_map_sg
  - block/blk-merge.c:__blk_bios_map_sg
```
```
In block/blk-integrity.c (ffffffe000450fe8)
Location: include/linux/scatterlist.h:116
Inline: True
Inline callers:
  - block/blk-integrity.c:blk_rq_map_integrity_sg
```
```
In lib/scatterlist.c (ffffffe00045cc3c)
Location: include/linux/scatterlist.h:116
Inline: True
Inline callers:
  - lib/scatterlist.c:sgl_alloc_order
  - lib/scatterlist.c:sgl_alloc_order
  - lib/scatterlist.c:sg_init_one
```
```
In lib/kfifo.c (ffffffe00046205a)
Location: include/linux/scatterlist.h:116
Inline: True
```
```
In drivers/char/virtio_console.c (ffffffe000565892)
Location: include/linux/scatterlist.h:116
Inline: True
Inline callers:
  - drivers/char/virtio_console.c:pipe_to_sg
  - drivers/char/virtio_console.c:pipe_to_sg
  - drivers/char/virtio_console.c:pipe_to_sg
```
```
In drivers/spi/spi.c (ffffffe000618a2e)
Location: include/linux/scatterlist.h:116
Inline: True
Inline callers:
  - drivers/spi/spi.c:spi_map_buf
  - drivers/spi/spi.c:spi_map_buf
  - drivers/spi/spi.c:spi_map_buf
```
```
In drivers/usb/core/devio.c (ffffffe00064f0ca)
Location: include/linux/scatterlist.h:116
Inline: True
Inline callers:
  - drivers/usb/core/devio.c:proc_do_submiturb
```
```
In drivers/mmc/core/sdio_ops.c (ffffffe0007125a0)
Location: include/linux/scatterlist.h:116
Inline: True
Inline callers:
  - drivers/mmc/core/sdio_ops.c:mmc_io_rw_extended
```
```
In net/core/skbuff.c (ffffffe000743eba)
Location: include/linux/scatterlist.h:116
Inline: True
Inline callers:
  - net/core/skbuff.c:__skb_to_sgvec
  - net/core/skbuff.c:__skb_to_sgvec
  - net/core/skbuff.c:__skb_to_sgvec
```
```
In net/core/filter.c (ffffffe00077d24a)
Location: include/linux/scatterlist.h:116
Inline: True
Inline callers:
  - net/core/filter.c:bpf_msg_pop_data
  - net/core/filter.c:bpf_msg_pop_data
  - net/core/filter.c:bpf_msg_pop_data
  - net/core/filter.c:bpf_msg_push_data
  - net/core/filter.c:bpf_msg_push_data
  - net/core/filter.c:bpf_msg_pull_data
  - net/core/filter.c:bpf_msg_pull_data
```
```
In net/core/skmsg.c (ffffffe00078b768)
Location: include/linux/scatterlist.h:116
Inline: True
Inline callers:
  - net/core/skmsg.c:sk_msg_zerocopy_from_iter
  - net/core/skmsg.c:sk_msg_zerocopy_from_iter
  - net/core/skmsg.c:sk_msg_clone
  - net/core/skmsg.c:sk_msg_alloc
  - net/core/skmsg.c:sk_msg_alloc
```
```
In net/ipv4/tcp.c (ffffffe0007d4e30)
Location: include/linux/scatterlist.h:116
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_md5_hash_skb_data
  - net/ipv4/tcp.c:tcp_md5_hash_skb_data
  - net/ipv4/tcp.c:tcp_md5_hash_skb_data
```
```
In net/ipv4/tcp_bpf.c (ffffffe000824c92)
Location: include/linux/scatterlist.h:116
Inline: True
Inline callers:
  - net/ipv4/tcp_bpf.c:tcp_bpf_sendpage
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
In kernel/dma/mapping.c (ffffffff811271e0)
Location: include/linux/scatterlist.h:116
Inline: True
```
```
In fs/crypto/crypto.c (ffffffff81342e52)
Location: include/linux/scatterlist.h:116
Inline: True
Inline callers:
  - fs/crypto/crypto.c:fscrypt_crypt_block
  - fs/crypto/crypto.c:fscrypt_crypt_block
  - fs/crypto/crypto.c:fscrypt_crypt_block
  - fs/crypto/crypto.c:fscrypt_crypt_block
```
```
In fs/verity/hash_algs.c (ffffffff81348974)
Location: include/linux/scatterlist.h:116
Inline: True
Inline callers:
  - fs/verity/hash_algs.c:fsverity_hash_page
```
```
In fs/ecryptfs/crypto.c (ffffffff8140e3b2)
Location: include/linux/scatterlist.h:116
Inline: True
Inline callers:
  - fs/ecryptfs/crypto.c:crypt_extent
  - fs/ecryptfs/crypto.c:crypt_extent
  - fs/ecryptfs/crypto.c:crypt_extent
  - fs/ecryptfs/crypto.c:crypt_extent
  - fs/ecryptfs/crypto.c:virt_to_scatterlist
  - fs/ecryptfs/crypto.c:virt_to_scatterlist
```
```
In security/keys/big_key.c (ffffffff814474bb)
Location: include/linux/scatterlist.h:116
Inline: True
Inline callers:
  - security/keys/big_key.c:big_key_alloc_buffer
```
```
In security/keys/encrypted-keys/encrypted.c (ffffffff8144a27f)
Location: include/linux/scatterlist.h:116
Inline: True
```
```
In crypto/scatterwalk.c (ffffffff814b9577)
Location: include/linux/scatterlist.h:116
Inline: True
```
```
In crypto/rsa-pkcs1pad.c (ffffffff814c11fc)
Location: include/linux/scatterlist.h:116
Inline: True
Inline callers:
  - crypto/rsa-pkcs1pad.c:pkcs1pad_verify
  - crypto/rsa-pkcs1pad.c:pkcs1pad_decrypt
```
```
In crypto/gcm.c (ffffffff814c91f4)
Location: include/linux/scatterlist.h:116
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
In crypto/drbg.c (ffffffff814ce4be)
Location: include/linux/scatterlist.h:116
Inline: True
Inline callers:
  - crypto/drbg.c:drbg_kcapi_sym_ctr
  - crypto/drbg.c:drbg_kcapi_sym_ctr
  - crypto/drbg.c:drbg_kcapi_sym_ctr
  - crypto/drbg.c:drbg_kcapi_sym_ctr
```
```
In crypto/asymmetric_keys/public_key.c (ffffffff814d2270)
Location: include/linux/scatterlist.h:116
Inline: True
Inline callers:
  - crypto/asymmetric_keys/public_key.c:public_key_verify_signature
  - crypto/asymmetric_keys/public_key.c:public_key_verify_signature
  - crypto/asymmetric_keys/public_key.c:public_key_verify_signature
  - crypto/asymmetric_keys/public_key.c:public_key_verify_signature
```
```
In block/blk-merge.c (ffffffff814e3d8c)
Location: include/linux/scatterlist.h:116
Inline: True
Inline callers:
  - block/blk-merge.c:blk_rq_map_sg
  - block/blk-merge.c:blk_rq_map_sg
  - block/blk-merge.c:blk_rq_map_sg
  - block/blk-merge.c:blk_rq_map_sg
  - block/blk-merge.c:blk_rq_map_sg
  - block/blk-merge.c:blk_rq_map_sg
  - block/blk-merge.c:__blk_bios_map_sg
  - block/blk-merge.c:__blk_bios_map_sg
  - block/blk-merge.c:__blk_bios_map_sg
  - block/blk-merge.c:__blk_bios_map_sg
```
```
In block/blk-integrity.c (ffffffff8150f3dd)
Location: include/linux/scatterlist.h:116
Inline: True
Inline callers:
  - block/blk-integrity.c:blk_rq_map_integrity_sg
```
```
In lib/scatterlist.c (ffffffff8151b086)
Location: include/linux/scatterlist.h:116
Inline: True
Inline callers:
  - lib/scatterlist.c:sgl_alloc_order
  - lib/scatterlist.c:sgl_alloc_order
  - lib/scatterlist.c:sg_init_one
  - lib/scatterlist.c:sg_init_one
```
```
In lib/kfifo.c (ffffffff81521c53)
Location: include/linux/scatterlist.h:116
Inline: True
```
```
In drivers/char/virtio_console.c (ffffffff8168737e)
Location: include/linux/scatterlist.h:116
Inline: True
Inline callers:
  - drivers/char/virtio_console.c:pipe_to_sg
  - drivers/char/virtio_console.c:pipe_to_sg
  - drivers/char/virtio_console.c:pipe_to_sg
  - drivers/char/virtio_console.c:pipe_to_sg
```
```
In drivers/char/agp/intel-gtt.c (ffffffff81692026)
Location: include/linux/scatterlist.h:116
Inline: True
Inline callers:
  - drivers/char/agp/intel-gtt.c:intel_fake_agp_insert_entries
```
```
In drivers/spi/spi.c (ffffffff817799e8)
Location: include/linux/scatterlist.h:116
Inline: True
Inline callers:
  - drivers/spi/spi.c:spi_map_buf
  - drivers/spi/spi.c:spi_map_buf
  - drivers/spi/spi.c:spi_map_buf
  - drivers/spi/spi.c:spi_map_buf
```
```
In drivers/usb/core/devio.c (ffffffff817b568c)
Location: include/linux/scatterlist.h:116
Inline: True
Inline callers:
  - drivers/usb/core/devio.c:proc_do_submiturb
```
```
In drivers/mmc/core/sdio_ops.c (ffffffff81884481)
Location: include/linux/scatterlist.h:116
Inline: True
Inline callers:
  - drivers/mmc/core/sdio_ops.c:mmc_io_rw_extended
```
```
In net/core/skbuff.c (ffffffff818b98b6)
Location: include/linux/scatterlist.h:116
Inline: True
Inline callers:
  - net/core/skbuff.c:__skb_to_sgvec
  - net/core/skbuff.c:__skb_to_sgvec
  - net/core/skbuff.c:__skb_to_sgvec
  - net/core/skbuff.c:__skb_to_sgvec
```
```
In net/core/filter.c (ffffffff818fda31)
Location: include/linux/scatterlist.h:116
Inline: True
Inline callers:
  - net/core/filter.c:bpf_msg_pop_data
  - net/core/filter.c:bpf_msg_pop_data
  - net/core/filter.c:bpf_msg_pop_data
  - net/core/filter.c:bpf_msg_push_data
  - net/core/filter.c:bpf_msg_push_data
  - net/core/filter.c:bpf_msg_pull_data
  - net/core/filter.c:bpf_msg_pull_data
```
```
In net/core/skmsg.c (ffffffff819090b7)
Location: include/linux/scatterlist.h:116
Inline: True
Inline callers:
  - net/core/skmsg.c:sk_msg_zerocopy_from_iter
  - net/core/skmsg.c:sk_msg_zerocopy_from_iter
  - net/core/skmsg.c:sk_msg_clone
  - net/core/skmsg.c:sk_msg_alloc
  - net/core/skmsg.c:sk_msg_alloc
```
```
In net/ipv4/tcp.c (ffffffff8195ddf2)
Location: include/linux/scatterlist.h:116
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_md5_hash_skb_data
  - net/ipv4/tcp.c:tcp_md5_hash_skb_data
  - net/ipv4/tcp.c:tcp_md5_hash_skb_data
  - net/ipv4/tcp.c:tcp_md5_hash_skb_data
```
```
In net/ipv4/tcp_bpf.c (ffffffff819b7d00)
Location: include/linux/scatterlist.h:116
Inline: True
Inline callers:
  - net/ipv4/tcp_bpf.c:tcp_bpf_sendpage
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
In kernel/dma/mapping.c (ffffffff81119c40)
Location: include/linux/scatterlist.h:116
Inline: True
```
```
In fs/crypto/crypto.c (ffffffff81333b32)
Location: include/linux/scatterlist.h:116
Inline: True
Inline callers:
  - fs/crypto/crypto.c:fscrypt_crypt_block
  - fs/crypto/crypto.c:fscrypt_crypt_block
  - fs/crypto/crypto.c:fscrypt_crypt_block
  - fs/crypto/crypto.c:fscrypt_crypt_block
```
```
In fs/verity/hash_algs.c (ffffffff81339654)
Location: include/linux/scatterlist.h:116
Inline: True
Inline callers:
  - fs/verity/hash_algs.c:fsverity_hash_page
```
```
In fs/ecryptfs/crypto.c (ffffffff813fee32)
Location: include/linux/scatterlist.h:116
Inline: True
Inline callers:
  - fs/ecryptfs/crypto.c:crypt_extent
  - fs/ecryptfs/crypto.c:crypt_extent
  - fs/ecryptfs/crypto.c:crypt_extent
  - fs/ecryptfs/crypto.c:crypt_extent
  - fs/ecryptfs/crypto.c:virt_to_scatterlist
  - fs/ecryptfs/crypto.c:virt_to_scatterlist
```
```
In security/keys/big_key.c (ffffffff81437f0b)
Location: include/linux/scatterlist.h:116
Inline: True
Inline callers:
  - security/keys/big_key.c:big_key_alloc_buffer
```
```
In security/keys/encrypted-keys/encrypted.c (ffffffff8143accf)
Location: include/linux/scatterlist.h:116
Inline: True
```
```
In crypto/scatterwalk.c (ffffffff814a9f97)
Location: include/linux/scatterlist.h:116
Inline: True
```
```
In crypto/rsa-pkcs1pad.c (ffffffff814b1c1c)
Location: include/linux/scatterlist.h:116
Inline: True
Inline callers:
  - crypto/rsa-pkcs1pad.c:pkcs1pad_verify
  - crypto/rsa-pkcs1pad.c:pkcs1pad_decrypt
```
```
In crypto/gcm.c (ffffffff814b9c14)
Location: include/linux/scatterlist.h:116
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
In crypto/drbg.c (ffffffff814beede)
Location: include/linux/scatterlist.h:116
Inline: True
Inline callers:
  - crypto/drbg.c:drbg_kcapi_sym_ctr
  - crypto/drbg.c:drbg_kcapi_sym_ctr
  - crypto/drbg.c:drbg_kcapi_sym_ctr
  - crypto/drbg.c:drbg_kcapi_sym_ctr
```
```
In crypto/asymmetric_keys/public_key.c (ffffffff814c2c90)
Location: include/linux/scatterlist.h:116
Inline: True
Inline callers:
  - crypto/asymmetric_keys/public_key.c:public_key_verify_signature
  - crypto/asymmetric_keys/public_key.c:public_key_verify_signature
  - crypto/asymmetric_keys/public_key.c:public_key_verify_signature
  - crypto/asymmetric_keys/public_key.c:public_key_verify_signature
```
```
In block/blk-merge.c (ffffffff814d466c)
Location: include/linux/scatterlist.h:116
Inline: True
Inline callers:
  - block/blk-merge.c:blk_rq_map_sg
  - block/blk-merge.c:blk_rq_map_sg
  - block/blk-merge.c:blk_rq_map_sg
  - block/blk-merge.c:blk_rq_map_sg
  - block/blk-merge.c:blk_rq_map_sg
  - block/blk-merge.c:blk_rq_map_sg
  - block/blk-merge.c:__blk_bios_map_sg
  - block/blk-merge.c:__blk_bios_map_sg
  - block/blk-merge.c:__blk_bios_map_sg
  - block/blk-merge.c:__blk_bios_map_sg
```
```
In block/blk-integrity.c (ffffffff814ff7f8)
Location: include/linux/scatterlist.h:116
Inline: True
Inline callers:
  - block/blk-integrity.c:blk_rq_map_integrity_sg
```
```
In lib/scatterlist.c (ffffffff8150b376)
Location: include/linux/scatterlist.h:116
Inline: True
Inline callers:
  - lib/scatterlist.c:sgl_alloc_order
  - lib/scatterlist.c:sgl_alloc_order
  - lib/scatterlist.c:sg_init_one
  - lib/scatterlist.c:sg_init_one
```
```
In lib/kfifo.c (ffffffff81511f43)
Location: include/linux/scatterlist.h:116
Inline: True
```
```
In drivers/char/virtio_console.c (ffffffff81664f6e)
Location: include/linux/scatterlist.h:116
Inline: True
Inline callers:
  - drivers/char/virtio_console.c:pipe_to_sg
  - drivers/char/virtio_console.c:pipe_to_sg
  - drivers/char/virtio_console.c:pipe_to_sg
  - drivers/char/virtio_console.c:pipe_to_sg
```
```
In drivers/char/agp/intel-gtt.c (ffffffff8166fa16)
Location: include/linux/scatterlist.h:116
Inline: True
Inline callers:
  - drivers/char/agp/intel-gtt.c:intel_fake_agp_insert_entries
```
```
In drivers/spi/spi.c (ffffffff81759798)
Location: include/linux/scatterlist.h:116
Inline: True
Inline callers:
  - drivers/spi/spi.c:spi_map_buf
  - drivers/spi/spi.c:spi_map_buf
  - drivers/spi/spi.c:spi_map_buf
  - drivers/spi/spi.c:spi_map_buf
```
```
In drivers/usb/core/devio.c (ffffffff817a70bc)
Location: include/linux/scatterlist.h:116
Inline: True
Inline callers:
  - drivers/usb/core/devio.c:proc_do_submiturb
```
```
In net/core/skbuff.c (ffffffff81873806)
Location: include/linux/scatterlist.h:116
Inline: True
Inline callers:
  - net/core/skbuff.c:__skb_to_sgvec
  - net/core/skbuff.c:__skb_to_sgvec
  - net/core/skbuff.c:__skb_to_sgvec
  - net/core/skbuff.c:__skb_to_sgvec
```
```
In net/core/filter.c (ffffffff818b7861)
Location: include/linux/scatterlist.h:116
Inline: True
Inline callers:
  - net/core/filter.c:bpf_msg_pop_data
  - net/core/filter.c:bpf_msg_pop_data
  - net/core/filter.c:bpf_msg_pop_data
  - net/core/filter.c:bpf_msg_push_data
  - net/core/filter.c:bpf_msg_push_data
  - net/core/filter.c:bpf_msg_pull_data
  - net/core/filter.c:bpf_msg_pull_data
```
```
In net/core/skmsg.c (ffffffff818c2ec7)
Location: include/linux/scatterlist.h:116
Inline: True
Inline callers:
  - net/core/skmsg.c:sk_msg_zerocopy_from_iter
  - net/core/skmsg.c:sk_msg_zerocopy_from_iter
  - net/core/skmsg.c:sk_msg_clone
  - net/core/skmsg.c:sk_msg_alloc
  - net/core/skmsg.c:sk_msg_alloc
```
```
In net/ipv4/tcp.c (ffffffff819178e2)
Location: include/linux/scatterlist.h:116
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_md5_hash_skb_data
  - net/ipv4/tcp.c:tcp_md5_hash_skb_data
  - net/ipv4/tcp.c:tcp_md5_hash_skb_data
  - net/ipv4/tcp.c:tcp_md5_hash_skb_data
```
```
In net/ipv4/tcp_bpf.c (ffffffff81974af0)
Location: include/linux/scatterlist.h:116
Inline: True
Inline callers:
  - net/ipv4/tcp_bpf.c:tcp_bpf_sendpage
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
In kernel/dma/mapping.c (ffffffff811250d0)
Location: include/linux/scatterlist.h:116
Inline: True
```
```
In fs/crypto/crypto.c (ffffffff81340922)
Location: include/linux/scatterlist.h:116
Inline: True
Inline callers:
  - fs/crypto/crypto.c:fscrypt_crypt_block
  - fs/crypto/crypto.c:fscrypt_crypt_block
  - fs/crypto/crypto.c:fscrypt_crypt_block
  - fs/crypto/crypto.c:fscrypt_crypt_block
```
```
In fs/verity/hash_algs.c (ffffffff81346444)
Location: include/linux/scatterlist.h:116
Inline: True
Inline callers:
  - fs/verity/hash_algs.c:fsverity_hash_page
```
```
In fs/ecryptfs/crypto.c (ffffffff8140b732)
Location: include/linux/scatterlist.h:116
Inline: True
Inline callers:
  - fs/ecryptfs/crypto.c:crypt_extent
  - fs/ecryptfs/crypto.c:crypt_extent
  - fs/ecryptfs/crypto.c:crypt_extent
  - fs/ecryptfs/crypto.c:crypt_extent
  - fs/ecryptfs/crypto.c:virt_to_scatterlist
  - fs/ecryptfs/crypto.c:virt_to_scatterlist
```
```
In security/keys/big_key.c (ffffffff8144355b)
Location: include/linux/scatterlist.h:116
Inline: True
Inline callers:
  - security/keys/big_key.c:big_key_alloc_buffer
```
```
In security/keys/encrypted-keys/encrypted.c (ffffffff8144631f)
Location: include/linux/scatterlist.h:116
Inline: True
```
```
In crypto/scatterwalk.c (ffffffff814b5607)
Location: include/linux/scatterlist.h:116
Inline: True
```
```
In crypto/rsa-pkcs1pad.c (ffffffff814bd28c)
Location: include/linux/scatterlist.h:116
Inline: True
Inline callers:
  - crypto/rsa-pkcs1pad.c:pkcs1pad_verify
  - crypto/rsa-pkcs1pad.c:pkcs1pad_decrypt
```
```
In crypto/gcm.c (ffffffff814c5284)
Location: include/linux/scatterlist.h:116
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
In crypto/drbg.c (ffffffff814ca54e)
Location: include/linux/scatterlist.h:116
Inline: True
Inline callers:
  - crypto/drbg.c:drbg_kcapi_sym_ctr
  - crypto/drbg.c:drbg_kcapi_sym_ctr
  - crypto/drbg.c:drbg_kcapi_sym_ctr
  - crypto/drbg.c:drbg_kcapi_sym_ctr
```
```
In crypto/asymmetric_keys/public_key.c (ffffffff814ce300)
Location: include/linux/scatterlist.h:116
Inline: True
Inline callers:
  - crypto/asymmetric_keys/public_key.c:public_key_verify_signature
  - crypto/asymmetric_keys/public_key.c:public_key_verify_signature
  - crypto/asymmetric_keys/public_key.c:public_key_verify_signature
  - crypto/asymmetric_keys/public_key.c:public_key_verify_signature
```
```
In block/blk-merge.c (ffffffff814dfe1c)
Location: include/linux/scatterlist.h:116
Inline: True
Inline callers:
  - block/blk-merge.c:blk_rq_map_sg
  - block/blk-merge.c:blk_rq_map_sg
  - block/blk-merge.c:blk_rq_map_sg
  - block/blk-merge.c:blk_rq_map_sg
  - block/blk-merge.c:blk_rq_map_sg
  - block/blk-merge.c:blk_rq_map_sg
  - block/blk-merge.c:__blk_bios_map_sg
  - block/blk-merge.c:__blk_bios_map_sg
  - block/blk-merge.c:__blk_bios_map_sg
  - block/blk-merge.c:__blk_bios_map_sg
```
```
In block/blk-integrity.c (ffffffff8150b46d)
Location: include/linux/scatterlist.h:116
Inline: True
Inline callers:
  - block/blk-integrity.c:blk_rq_map_integrity_sg
```
```
In lib/scatterlist.c (ffffffff81517116)
Location: include/linux/scatterlist.h:116
Inline: True
Inline callers:
  - lib/scatterlist.c:sgl_alloc_order
  - lib/scatterlist.c:sgl_alloc_order
  - lib/scatterlist.c:sg_init_one
  - lib/scatterlist.c:sg_init_one
```
```
In lib/kfifo.c (ffffffff8151dce3)
Location: include/linux/scatterlist.h:116
Inline: True
```
```
In drivers/char/virtio_console.c (ffffffff816b56be)
Location: include/linux/scatterlist.h:116
Inline: True
Inline callers:
  - drivers/char/virtio_console.c:pipe_to_sg
  - drivers/char/virtio_console.c:pipe_to_sg
  - drivers/char/virtio_console.c:pipe_to_sg
  - drivers/char/virtio_console.c:pipe_to_sg
```
```
In drivers/char/agp/intel-gtt.c (ffffffff816c0296)
Location: include/linux/scatterlist.h:116
Inline: True
Inline callers:
  - drivers/char/agp/intel-gtt.c:intel_fake_agp_insert_entries
```
```
In drivers/spi/spi.c (ffffffff817a9d88)
Location: include/linux/scatterlist.h:116
Inline: True
Inline callers:
  - drivers/spi/spi.c:spi_map_buf
  - drivers/spi/spi.c:spi_map_buf
  - drivers/spi/spi.c:spi_map_buf
  - drivers/spi/spi.c:spi_map_buf
```
```
In drivers/usb/core/devio.c (ffffffff817f212c)
Location: include/linux/scatterlist.h:116
Inline: True
Inline callers:
  - drivers/usb/core/devio.c:proc_do_submiturb
```
```
In drivers/mmc/core/sdio_ops.c (ffffffff818d5921)
Location: include/linux/scatterlist.h:116
Inline: True
Inline callers:
  - drivers/mmc/core/sdio_ops.c:mmc_io_rw_extended
```
```
In net/core/skbuff.c (ffffffff8190a8b6)
Location: include/linux/scatterlist.h:116
Inline: True
Inline callers:
  - net/core/skbuff.c:__skb_to_sgvec
  - net/core/skbuff.c:__skb_to_sgvec
  - net/core/skbuff.c:__skb_to_sgvec
  - net/core/skbuff.c:__skb_to_sgvec
```
```
In net/core/filter.c (ffffffff8194ea61)
Location: include/linux/scatterlist.h:116
Inline: True
Inline callers:
  - net/core/filter.c:bpf_msg_pop_data
  - net/core/filter.c:bpf_msg_pop_data
  - net/core/filter.c:bpf_msg_pop_data
  - net/core/filter.c:bpf_msg_push_data
  - net/core/filter.c:bpf_msg_push_data
  - net/core/filter.c:bpf_msg_pull_data
  - net/core/filter.c:bpf_msg_pull_data
```
```
In net/core/skmsg.c (ffffffff8195a0e7)
Location: include/linux/scatterlist.h:116
Inline: True
Inline callers:
  - net/core/skmsg.c:sk_msg_zerocopy_from_iter
  - net/core/skmsg.c:sk_msg_zerocopy_from_iter
  - net/core/skmsg.c:sk_msg_clone
  - net/core/skmsg.c:sk_msg_alloc
  - net/core/skmsg.c:sk_msg_alloc
```
```
In net/ipv4/tcp.c (ffffffff819c85c2)
Location: include/linux/scatterlist.h:116
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_md5_hash_skb_data
  - net/ipv4/tcp.c:tcp_md5_hash_skb_data
  - net/ipv4/tcp.c:tcp_md5_hash_skb_data
  - net/ipv4/tcp.c:tcp_md5_hash_skb_data
```
```
In net/ipv4/tcp_bpf.c (ffffffff81a22780)
Location: include/linux/scatterlist.h:116
Inline: True
Inline callers:
  - net/ipv4/tcp_bpf.c:tcp_bpf_sendpage
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
In kernel/dma/mapping.c (ffffffff81131710)
Location: include/linux/scatterlist.h:116
Inline: True
```
```
In fs/crypto/crypto.c (ffffffff81353c22)
Location: include/linux/scatterlist.h:116
Inline: True
Inline callers:
  - fs/crypto/crypto.c:fscrypt_crypt_block
  - fs/crypto/crypto.c:fscrypt_crypt_block
  - fs/crypto/crypto.c:fscrypt_crypt_block
  - fs/crypto/crypto.c:fscrypt_crypt_block
```
```
In fs/verity/hash_algs.c (ffffffff81359724)
Location: include/linux/scatterlist.h:116
Inline: True
Inline callers:
  - fs/verity/hash_algs.c:fsverity_hash_page
```
```
In fs/ecryptfs/crypto.c (ffffffff814213d2)
Location: include/linux/scatterlist.h:116
Inline: True
Inline callers:
  - fs/ecryptfs/crypto.c:crypt_extent
  - fs/ecryptfs/crypto.c:crypt_extent
  - fs/ecryptfs/crypto.c:crypt_extent
  - fs/ecryptfs/crypto.c:crypt_extent
  - fs/ecryptfs/crypto.c:virt_to_scatterlist
  - fs/ecryptfs/crypto.c:virt_to_scatterlist
```
```
In security/keys/big_key.c (ffffffff8145a88b)
Location: include/linux/scatterlist.h:116
Inline: True
Inline callers:
  - security/keys/big_key.c:big_key_alloc_buffer
```
```
In security/keys/encrypted-keys/encrypted.c (ffffffff8145d64f)
Location: include/linux/scatterlist.h:116
Inline: True
```
```
In crypto/scatterwalk.c (ffffffff814ce0a7)
Location: include/linux/scatterlist.h:116
Inline: True
```
```
In crypto/rsa-pkcs1pad.c (ffffffff814d5d5c)
Location: include/linux/scatterlist.h:116
Inline: True
Inline callers:
  - crypto/rsa-pkcs1pad.c:pkcs1pad_verify
  - crypto/rsa-pkcs1pad.c:pkcs1pad_decrypt
```
```
In crypto/gcm.c (ffffffff814ddd54)
Location: include/linux/scatterlist.h:116
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
In crypto/drbg.c (ffffffff814e301e)
Location: include/linux/scatterlist.h:116
Inline: True
Inline callers:
  - crypto/drbg.c:drbg_kcapi_sym_ctr
  - crypto/drbg.c:drbg_kcapi_sym_ctr
  - crypto/drbg.c:drbg_kcapi_sym_ctr
  - crypto/drbg.c:drbg_kcapi_sym_ctr
```
```
In crypto/asymmetric_keys/public_key.c (ffffffff814e6dd0)
Location: include/linux/scatterlist.h:116
Inline: True
Inline callers:
  - crypto/asymmetric_keys/public_key.c:public_key_verify_signature
  - crypto/asymmetric_keys/public_key.c:public_key_verify_signature
  - crypto/asymmetric_keys/public_key.c:public_key_verify_signature
  - crypto/asymmetric_keys/public_key.c:public_key_verify_signature
```
```
In block/blk-merge.c (ffffffff814f8c7c)
Location: include/linux/scatterlist.h:116
Inline: True
Inline callers:
  - block/blk-merge.c:blk_rq_map_sg
  - block/blk-merge.c:blk_rq_map_sg
  - block/blk-merge.c:blk_rq_map_sg
  - block/blk-merge.c:blk_rq_map_sg
  - block/blk-merge.c:blk_rq_map_sg
  - block/blk-merge.c:blk_rq_map_sg
  - block/blk-merge.c:__blk_bios_map_sg
  - block/blk-merge.c:__blk_bios_map_sg
  - block/blk-merge.c:__blk_bios_map_sg
  - block/blk-merge.c:__blk_bios_map_sg
```
```
In block/blk-integrity.c (ffffffff81524b0d)
Location: include/linux/scatterlist.h:116
Inline: True
Inline callers:
  - block/blk-integrity.c:blk_rq_map_integrity_sg
```
```
In lib/scatterlist.c (ffffffff815308a6)
Location: include/linux/scatterlist.h:116
Inline: True
Inline callers:
  - lib/scatterlist.c:sgl_alloc_order
  - lib/scatterlist.c:sgl_alloc_order
  - lib/scatterlist.c:sg_init_one
  - lib/scatterlist.c:sg_init_one
```
```
In lib/kfifo.c (ffffffff81537553)
Location: include/linux/scatterlist.h:116
Inline: True
```
```
In drivers/char/virtio_console.c (ffffffff816d015e)
Location: include/linux/scatterlist.h:116
Inline: True
Inline callers:
  - drivers/char/virtio_console.c:pipe_to_sg
  - drivers/char/virtio_console.c:pipe_to_sg
  - drivers/char/virtio_console.c:pipe_to_sg
  - drivers/char/virtio_console.c:pipe_to_sg
```
```
In drivers/char/agp/intel-gtt.c (ffffffff816da866)
Location: include/linux/scatterlist.h:116
Inline: True
Inline callers:
  - drivers/char/agp/intel-gtt.c:intel_fake_agp_insert_entries
```
```
In drivers/spi/spi.c (ffffffff817c3c18)
Location: include/linux/scatterlist.h:116
Inline: True
Inline callers:
  - drivers/spi/spi.c:spi_map_buf
  - drivers/spi/spi.c:spi_map_buf
  - drivers/spi/spi.c:spi_map_buf
  - drivers/spi/spi.c:spi_map_buf
```
```
In drivers/usb/core/devio.c (ffffffff8180c36c)
Location: include/linux/scatterlist.h:116
Inline: True
Inline callers:
  - drivers/usb/core/devio.c:proc_do_submiturb
```
```
In drivers/mmc/core/sdio_ops.c (ffffffff818f2441)
Location: include/linux/scatterlist.h:116
Inline: True
Inline callers:
  - drivers/mmc/core/sdio_ops.c:mmc_io_rw_extended
```
```
In net/core/skbuff.c (ffffffff8192b9b6)
Location: include/linux/scatterlist.h:116
Inline: True
Inline callers:
  - net/core/skbuff.c:__skb_to_sgvec
  - net/core/skbuff.c:__skb_to_sgvec
  - net/core/skbuff.c:__skb_to_sgvec
  - net/core/skbuff.c:__skb_to_sgvec
```
```
In net/core/filter.c (ffffffff81970431)
Location: include/linux/scatterlist.h:116
Inline: True
Inline callers:
  - net/core/filter.c:bpf_msg_pop_data
  - net/core/filter.c:bpf_msg_pop_data
  - net/core/filter.c:bpf_msg_pop_data
  - net/core/filter.c:bpf_msg_push_data
  - net/core/filter.c:bpf_msg_push_data
  - net/core/filter.c:bpf_msg_pull_data
  - net/core/filter.c:bpf_msg_pull_data
```
```
In net/core/skmsg.c (ffffffff8197c307)
Location: include/linux/scatterlist.h:116
Inline: True
Inline callers:
  - net/core/skmsg.c:sk_msg_zerocopy_from_iter
  - net/core/skmsg.c:sk_msg_zerocopy_from_iter
  - net/core/skmsg.c:sk_msg_clone
  - net/core/skmsg.c:sk_msg_alloc
  - net/core/skmsg.c:sk_msg_alloc
```
```
In net/ipv4/tcp.c (ffffffff819d2112)
Location: include/linux/scatterlist.h:116
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_md5_hash_skb_data
  - net/ipv4/tcp.c:tcp_md5_hash_skb_data
  - net/ipv4/tcp.c:tcp_md5_hash_skb_data
  - net/ipv4/tcp.c:tcp_md5_hash_skb_data
```
```
In net/ipv4/tcp_bpf.c (ffffffff81a2db5c)
Location: include/linux/scatterlist.h:116
Inline: True
Inline callers:
  - net/ipv4/tcp_bpf.c:tcp_bpf_sendpage
```
</details>
</li>
</ul>

## Differences
