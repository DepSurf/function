# Function: <code>sg_init_table</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void sg_init_table(struct scatterlist *sgl, unsigned int nents);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/scatterlist.c (ffffffff813f9e90)
Location: lib/scatterlist.c:132
Inline: False
Direct callers:
  - fs/ext4/crypto.c:ext4_page_crypto
  - fs/ext4/crypto.c:ext4_page_crypto
  - fs/ecryptfs/crypto.c:crypt_extent
  - fs/ecryptfs/crypto.c:crypt_extent
  - fs/ecryptfs/crypto.c:virt_to_scatterlist
  - crypto/scatterwalk.c:scatterwalk_ffwd
  - crypto/eseqiv.c:eseqiv_givencrypt
  - crypto/eseqiv.c:eseqiv_givencrypt
  - lib/scatterlist.c:sg_init_one
  - lib/scatterlist.c:__sg_alloc_table
  - drivers/tty/serial/8250/8250_dma.c:serial8250_tx_dma
  - drivers/tty/serial/8250/8250_dma.c:serial8250_rx_dma
  - drivers/char/virtio_console.c:port_fops_splice_write
  - drivers/block/virtio_blk.c:virtblk_init_request
  - drivers/block/xen-blkfront.c:blkfront_setup_indirect
  - drivers/net/virtio_net.c:virtnet_set_rx_mode
  - drivers/net/virtio_net.c:start_xmit
  - drivers/net/virtio_net.c:start_xmit
  - drivers/net/virtio_net.c:try_fill_recv
  - drivers/net/virtio_net.c:try_fill_recv
  - drivers/usb/core/devio.c:proc_do_submiturb
  - net/ipv4/tcp.c:tcp_md5_hash_skb_data
```
**Symbols:**

```
ffffffff813f9e90-ffffffff813f9ec9: sg_init_table (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
void sg_init_table(struct scatterlist *sgl, unsigned int nents);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/scatterlist.c (ffffffff81441091)
Location: lib/scatterlist.c:132
Inline: True
Inline callers:
  - lib/scatterlist.c:sg_init_one
Direct callers:
  - fs/ecryptfs/crypto.c:crypt_extent
  - fs/ecryptfs/crypto.c:crypt_extent
  - fs/ecryptfs/crypto.c:virt_to_scatterlist
  - crypto/rsa-pkcs1pad.c:pkcs1pad_sg_set_buf
  - lib/scatterlist.c:__sg_alloc_table
  - drivers/tty/serial/8250/8250_dma.c:serial8250_rx_dma
  - drivers/tty/serial/8250/8250_dma.c:serial8250_tx_dma
  - drivers/char/virtio_console.c:port_fops_splice_write
  - drivers/block/virtio_blk.c:virtblk_init_request
  - drivers/block/xen-blkfront.c:blkfront_setup_indirect
  - drivers/net/virtio_net.c:virtnet_set_rx_mode
  - drivers/net/virtio_net.c:start_xmit
  - drivers/net/virtio_net.c:start_xmit
  - drivers/net/virtio_net.c:try_fill_recv
  - drivers/net/virtio_net.c:try_fill_recv
  - drivers/usb/core/devio.c:proc_do_submiturb
  - net/ipv4/tcp.c:tcp_md5_hash_skb_data
```
**Symbols:**

```
ffffffff81440ee0-ffffffff81440f19: sg_init_table (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
void sg_init_table(struct scatterlist *sgl, unsigned int nents);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/scatterlist.c (ffffffff8145e661)
Location: lib/scatterlist.c:132
Inline: True
Inline callers:
  - lib/scatterlist.c:sg_init_one
Direct callers:
  - fs/ecryptfs/crypto.c:crypt_extent
  - fs/ecryptfs/crypto.c:crypt_extent
  - fs/ecryptfs/crypto.c:virt_to_scatterlist
  - crypto/rsa-pkcs1pad.c:pkcs1pad_verify
  - crypto/rsa-pkcs1pad.c:pkcs1pad_decrypt
  - crypto/rsa-pkcs1pad.c:pkcs1pad_encrypt
  - crypto/scompress.c:scomp_acomp_comp_decomp
  - lib/scatterlist.c:__sg_alloc_table
  - drivers/tty/serial/8250/8250_dma.c:serial8250_rx_dma
  - drivers/tty/serial/8250/8250_dma.c:serial8250_tx_dma
  - drivers/char/virtio_console.c:port_fops_splice_write
  - drivers/block/xen-blkfront.c:blkfront_setup_indirect
  - drivers/usb/core/devio.c:proc_do_submiturb
  - net/ipv4/tcp.c:tcp_md5_hash_skb_data
```
**Symbols:**

```
ffffffff8145e100-ffffffff8145e139: sg_init_table (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void sg_init_table(struct scatterlist *sgl, unsigned int nents);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/scatterlist.c (ffffffff81463470)
Location: lib/scatterlist.c:132
Inline: False
Direct callers:
  - fs/crypto/crypto.c:fscrypt_do_page_crypto
  - fs/crypto/crypto.c:fscrypt_do_page_crypto
  - fs/ecryptfs/crypto.c:crypt_extent
  - fs/ecryptfs/crypto.c:crypt_extent
  - fs/ecryptfs/crypto.c:virt_to_scatterlist
  - crypto/rsa-pkcs1pad.c:pkcs1pad_verify
  - crypto/rsa-pkcs1pad.c:pkcs1pad_decrypt
  - crypto/rsa-pkcs1pad.c:pkcs1pad_encrypt
  - crypto/scompress.c:scomp_acomp_comp_decomp
  - lib/scatterlist.c:sg_init_one
  - drivers/tty/serial/8250/8250_dma.c:serial8250_rx_dma
  - drivers/tty/serial/8250/8250_dma.c:serial8250_tx_dma
  - drivers/char/virtio_console.c:port_fops_splice_write
  - drivers/block/xen-blkfront.c:blkfront_setup_indirect
  - drivers/usb/core/devio.c:proc_do_submiturb
  - net/ipv4/tcp.c:tcp_md5_hash_skb_data
```
**Symbols:**

```
ffffffff81463470-ffffffff814634a3: sg_init_table (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void sg_init_table(struct scatterlist *sgl, unsigned int nents);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/scatterlist.c (ffffffff8148f380)
Location: lib/scatterlist.c:132
Inline: False
Direct callers:
  - fs/crypto/crypto.c:fscrypt_do_page_crypto
  - fs/crypto/crypto.c:fscrypt_do_page_crypto
  - fs/ecryptfs/crypto.c:crypt_extent
  - fs/ecryptfs/crypto.c:crypt_extent
  - fs/ecryptfs/crypto.c:virt_to_scatterlist
  - crypto/rsa-pkcs1pad.c:pkcs1pad_verify
  - crypto/rsa-pkcs1pad.c:pkcs1pad_decrypt
  - crypto/rsa-pkcs1pad.c:pkcs1pad_encrypt
  - crypto/scompress.c:scomp_acomp_comp_decomp
  - crypto/gcm.c:crypto_rfc4106_crypt
  - crypto/gcm.c:crypto_rfc4106_crypt
  - crypto/gcm.c:crypto_gcm_init_common
  - crypto/gcm.c:crypto_gcm_init_common
  - lib/scatterlist.c:sg_init_one
  - drivers/tty/serial/8250/8250_dma.c:serial8250_rx_dma
  - drivers/tty/serial/8250/8250_dma.c:serial8250_tx_dma
  - drivers/char/virtio_console.c:port_fops_splice_write
  - drivers/block/xen-blkfront.c:blkfront_setup_indirect
  - drivers/usb/core/devio.c:proc_do_submiturb
  - net/ipv4/tcp.c:tcp_md5_hash_skb_data
```
**Symbols:**

```
ffffffff8148f380-ffffffff8148f3b3: sg_init_table (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void sg_init_table(struct scatterlist *sgl, unsigned int nents);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/scatterlist.c (ffffffff814c3f90)
Location: lib/scatterlist.c:126
Inline: False
Direct callers:
  - kernel/bpf/sockmap.c:smap_tx_work
  - kernel/bpf/sockmap.c:bpf_tcp_push
  - fs/crypto/crypto.c:fscrypt_do_page_crypto
  - fs/crypto/crypto.c:fscrypt_do_page_crypto
  - fs/ecryptfs/crypto.c:crypt_extent
  - fs/ecryptfs/crypto.c:crypt_extent
  - fs/ecryptfs/crypto.c:virt_to_scatterlist
  - security/keys/big_key.c:big_key_alloc_buffer
  - crypto/rsa-pkcs1pad.c:pkcs1pad_verify
  - crypto/rsa-pkcs1pad.c:pkcs1pad_decrypt
  - crypto/rsa-pkcs1pad.c:pkcs1pad_encrypt
  - crypto/gcm.c:crypto_rfc4106_crypt
  - crypto/gcm.c:crypto_rfc4106_crypt
  - crypto/gcm.c:crypto_gcm_init_common
  - crypto/gcm.c:crypto_gcm_init_common
  - lib/scatterlist.c:sgl_alloc_order
  - lib/scatterlist.c:sg_init_one
  - drivers/tty/serial/8250/8250_dma.c:serial8250_rx_dma
  - drivers/tty/serial/8250/8250_dma.c:serial8250_tx_dma
  - drivers/char/virtio_console.c:port_fops_splice_write
  - drivers/block/xen-blkfront.c:blkfront_setup_indirect
  - drivers/usb/core/devio.c:proc_do_submiturb
  - net/ipv4/tcp.c:tcp_md5_hash_skb_data
```
**Symbols:**

```
ffffffff814c3f90-ffffffff814c3fc3: sg_init_table (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void sg_init_table(struct scatterlist *sgl, unsigned int nents);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/scatterlist.c (ffffffff814d8690)
Location: lib/scatterlist.c:126
Inline: False
Direct callers:
  - fs/crypto/crypto.c:fscrypt_do_page_crypto
  - fs/crypto/crypto.c:fscrypt_do_page_crypto
  - fs/ecryptfs/crypto.c:crypt_extent
  - fs/ecryptfs/crypto.c:crypt_extent
  - fs/ecryptfs/crypto.c:virt_to_scatterlist
  - security/keys/big_key.c:big_key_alloc_buffer
  - crypto/rsa-pkcs1pad.c:pkcs1pad_verify
  - crypto/rsa-pkcs1pad.c:pkcs1pad_decrypt
  - crypto/gcm.c:crypto_rfc4106_crypt
  - crypto/gcm.c:crypto_rfc4106_crypt
  - crypto/gcm.c:crypto_gcm_init_common
  - crypto/gcm.c:crypto_gcm_init_common
  - crypto/drbg.c:drbg_init_sym_kernel
  - lib/scatterlist.c:sgl_alloc_order
  - lib/scatterlist.c:sg_init_one
  - drivers/tty/serial/8250/8250_dma.c:serial8250_rx_dma
  - drivers/tty/serial/8250/8250_dma.c:serial8250_tx_dma
  - drivers/char/virtio_console.c:port_fops_splice_write
  - drivers/block/xen-blkfront.c:blkfront_setup_indirect
  - drivers/usb/core/devio.c:proc_do_submiturb
  - net/ipv4/tcp.c:tcp_md5_hash_skb_data
  - net/ipv4/tcp_bpf.c:tcp_bpf_push
```
**Symbols:**

```
ffffffff814d8690-ffffffff814d86c3: sg_init_table (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void sg_init_table(struct scatterlist *sgl, unsigned int nents);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/scatterlist.c (ffffffff81504400)
Location: lib/scatterlist.c:124
Inline: False
Direct callers:
  - fs/crypto/crypto.c:fscrypt_crypt_block
  - fs/crypto/crypto.c:fscrypt_crypt_block
  - fs/ecryptfs/crypto.c:crypt_extent
  - fs/ecryptfs/crypto.c:crypt_extent
  - fs/ecryptfs/crypto.c:virt_to_scatterlist
  - security/keys/big_key.c:big_key_alloc_buffer
  - crypto/rsa-pkcs1pad.c:pkcs1pad_verify
  - crypto/rsa-pkcs1pad.c:pkcs1pad_decrypt
  - crypto/gcm.c:crypto_rfc4106_crypt
  - crypto/gcm.c:crypto_rfc4106_crypt
  - crypto/gcm.c:crypto_gcm_init_common
  - crypto/gcm.c:crypto_gcm_init_common
  - crypto/drbg.c:drbg_init_sym_kernel
  - crypto/asymmetric_keys/public_key.c:public_key_verify_signature
  - lib/scatterlist.c:sgl_alloc_order
  - lib/scatterlist.c:__sg_alloc_table
  - lib/scatterlist.c:sg_init_one
  - drivers/tty/serial/8250/8250_dma.c:serial8250_rx_dma
  - drivers/tty/serial/8250/8250_dma.c:serial8250_tx_dma
  - drivers/char/virtio_console.c:port_fops_splice_write
  - drivers/block/xen-blkfront.c:blkfront_setup_indirect
  - drivers/usb/core/devio.c:proc_do_submiturb
  - net/ipv4/tcp.c:tcp_md5_hash_skb_data
  - net/ipv4/tcp_bpf.c:tcp_bpf_push
```
**Symbols:**

```
ffffffff81504400-ffffffff81504433: sg_init_table (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void sg_init_table(struct scatterlist *sgl, unsigned int nents);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/scatterlist.c (ffffffff81522410)
Location: lib/scatterlist.c:124
Inline: False
Direct callers:
  - fs/crypto/crypto.c:fscrypt_crypt_block
  - fs/crypto/crypto.c:fscrypt_crypt_block
  - fs/verity/hash_algs.c:fsverity_hash_page
  - fs/ecryptfs/crypto.c:crypt_extent
  - fs/ecryptfs/crypto.c:crypt_extent
  - fs/ecryptfs/crypto.c:virt_to_scatterlist
  - security/keys/big_key.c:big_key_alloc_buffer
  - crypto/rsa-pkcs1pad.c:pkcs1pad_verify
  - crypto/rsa-pkcs1pad.c:pkcs1pad_decrypt
  - crypto/gcm.c:crypto_rfc4106_crypt
  - crypto/gcm.c:crypto_rfc4106_crypt
  - crypto/gcm.c:crypto_gcm_init_common
  - crypto/gcm.c:crypto_gcm_init_common
  - crypto/drbg.c:drbg_init_sym_kernel
  - crypto/asymmetric_keys/public_key.c:public_key_verify_signature
  - lib/scatterlist.c:sgl_alloc_order
  - lib/scatterlist.c:__sg_alloc_table
  - lib/scatterlist.c:sg_init_one
  - drivers/tty/serial/8250/8250_dma.c:serial8250_rx_dma
  - drivers/tty/serial/8250/8250_dma.c:serial8250_tx_dma
  - drivers/char/virtio_console.c:port_fops_splice_write
  - drivers/block/xen-blkfront.c:blkfront_setup_indirect
  - drivers/usb/core/devio.c:proc_do_submiturb
  - net/ipv4/tcp.c:tcp_md5_hash_skb_data
  - net/ipv4/tcp_bpf.c:tcp_bpf_push
```
**Symbols:**

```
ffffffff81522410-ffffffff81522443: sg_init_table (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
void sg_init_table(struct scatterlist *sgl, unsigned int nents);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/scatterlist.c (ffffffff81586230)
Location: lib/scatterlist.c:124
Inline: True
Inline callers:
  - lib/scatterlist.c:sg_init_one
Direct callers:
  - mm/page_reporting.c:page_reporting_process
  - fs/crypto/crypto.c:fscrypt_crypt_block
  - fs/crypto/crypto.c:fscrypt_crypt_block
  - fs/verity/hash_algs.c:fsverity_hash_page
  - fs/ecryptfs/crypto.c:crypt_extent
  - fs/ecryptfs/crypto.c:crypt_extent
  - fs/ecryptfs/crypto.c:virt_to_scatterlist
  - crypto/scatterwalk.c:scatterwalk_ffwd
  - crypto/rsa-pkcs1pad.c:pkcs1pad_verify
  - crypto/rsa-pkcs1pad.c:pkcs1pad_decrypt
  - crypto/gcm.c:crypto_rfc4106_crypt
  - crypto/gcm.c:crypto_rfc4106_crypt
  - crypto/gcm.c:crypto_gcm_init_common
  - crypto/gcm.c:crypto_gcm_init_common
  - crypto/drbg.c:drbg_init_sym_kernel
  - crypto/asymmetric_keys/public_key.c:public_key_verify_signature
  - block/bsg-lib.c:bsg_map_buffer
  - block/blk-crypto-fallback.c:blk_crypto_fallback_decrypt_bio
  - block/blk-crypto-fallback.c:blk_crypto_fallback_encrypt_bio
  - block/blk-crypto-fallback.c:blk_crypto_fallback_encrypt_bio
  - lib/scatterlist.c:sgl_alloc_order
  - lib/scatterlist.c:__sg_alloc_table
  - lib/sg_pool.c:sg_alloc_table_chained
  - drivers/tty/serial/8250/8250_dma.c:serial8250_rx_dma
  - drivers/tty/serial/8250/8250_dma.c:serial8250_tx_dma
  - drivers/char/virtio_console.c:port_fops_splice_write
  - drivers/block/xen-blkfront.c:blkfront_setup_indirect
  - drivers/usb/core/devio.c:proc_do_submiturb
  - net/ipv4/tcp.c:tcp_md5_hash_skb_data
  - net/ipv4/tcp_bpf.c:tcp_bpf_push
```
**Symbols:**

```
ffffffff81585770-ffffffff815857a6: sg_init_table (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
void sg_init_table(struct scatterlist *sgl, unsigned int nents);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/scatterlist.c (ffffffff815a3310)
Location: lib/scatterlist.c:124
Inline: True
Inline callers:
  - lib/scatterlist.c:sg_init_one
Direct callers:
  - mm/zswap.c:zswap_frontswap_load
  - mm/zswap.c:zswap_frontswap_store
  - mm/zswap.c:zswap_writeback_entry
  - mm/page_reporting.c:page_reporting_process
  - fs/crypto/crypto.c:fscrypt_crypt_block
  - fs/crypto/crypto.c:fscrypt_crypt_block
  - fs/verity/hash_algs.c:fsverity_hash_page
  - fs/ecryptfs/crypto.c:crypt_extent
  - fs/ecryptfs/crypto.c:crypt_extent
  - fs/ecryptfs/crypto.c:virt_to_scatterlist
  - crypto/scatterwalk.c:scatterwalk_ffwd
  - crypto/rsa-pkcs1pad.c:pkcs1pad_verify
  - crypto/rsa-pkcs1pad.c:pkcs1pad_decrypt
  - crypto/gcm.c:crypto_rfc4106_crypt
  - crypto/gcm.c:crypto_rfc4106_crypt
  - crypto/gcm.c:crypto_gcm_init_common
  - crypto/gcm.c:crypto_gcm_init_common
  - crypto/drbg.c:drbg_init_sym_kernel
  - crypto/asymmetric_keys/public_key.c:public_key_verify_signature
  - block/bsg-lib.c:bsg_map_buffer
  - block/blk-crypto-fallback.c:blk_crypto_fallback_decrypt_bio
  - block/blk-crypto-fallback.c:blk_crypto_fallback_encrypt_bio
  - block/blk-crypto-fallback.c:blk_crypto_fallback_encrypt_bio
  - lib/scatterlist.c:sgl_alloc_order
  - lib/scatterlist.c:__sg_alloc_table_from_pages
  - lib/scatterlist.c:__sg_alloc_table
  - lib/sg_pool.c:sg_alloc_table_chained
  - drivers/tty/serial/8250/8250_dma.c:serial8250_rx_dma
  - drivers/tty/serial/8250/8250_dma.c:serial8250_tx_dma
  - drivers/char/virtio_console.c:port_fops_splice_write
  - drivers/block/xen-blkfront.c:blkfront_setup_indirect
  - drivers/usb/core/devio.c:proc_do_submiturb
  - net/ipv4/tcp.c:tcp_md5_hash_skb_data
  - net/ipv4/tcp_bpf.c:tcp_bpf_push
```
**Symbols:**

```
ffffffff815a2850-ffffffff815a2886: sg_init_table (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
void sg_init_table(struct scatterlist *sgl, unsigned int nents);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/scatterlist.c (ffffffff815aa6d0)
Location: lib/scatterlist.c:124
Inline: True
Inline callers:
  - lib/scatterlist.c:sg_init_one
Direct callers:
  - mm/zswap.c:zswap_frontswap_load
  - mm/zswap.c:zswap_frontswap_store
  - mm/zswap.c:zswap_writeback_entry
  - mm/page_reporting.c:page_reporting_process
  - fs/crypto/crypto.c:fscrypt_crypt_block
  - fs/crypto/crypto.c:fscrypt_crypt_block
  - fs/verity/hash_algs.c:fsverity_hash_page
  - fs/ecryptfs/crypto.c:crypt_extent
  - fs/ecryptfs/crypto.c:crypt_extent
  - fs/ecryptfs/crypto.c:virt_to_scatterlist
  - crypto/scatterwalk.c:scatterwalk_ffwd
  - crypto/rsa-pkcs1pad.c:pkcs1pad_verify
  - crypto/rsa-pkcs1pad.c:pkcs1pad_decrypt
  - crypto/gcm.c:crypto_rfc4106_crypt
  - crypto/gcm.c:crypto_rfc4106_crypt
  - crypto/gcm.c:crypto_gcm_init_common
  - crypto/gcm.c:crypto_gcm_init_common
  - crypto/drbg.c:drbg_init_sym_kernel
  - crypto/asymmetric_keys/public_key.c:public_key_verify_signature
  - block/bsg-lib.c:bsg_map_buffer
  - block/blk-crypto-fallback.c:blk_crypto_fallback_decrypt_bio
  - block/blk-crypto-fallback.c:blk_crypto_fallback_encrypt_bio
  - block/blk-crypto-fallback.c:blk_crypto_fallback_encrypt_bio
  - lib/scatterlist.c:sgl_alloc_order
  - lib/scatterlist.c:__sg_alloc_table_from_pages
  - lib/scatterlist.c:__sg_alloc_table
  - lib/sg_pool.c:sg_alloc_table_chained
  - drivers/tty/serial/8250/8250_dma.c:serial8250_rx_dma
  - drivers/tty/serial/8250/8250_dma.c:serial8250_tx_dma
  - drivers/char/virtio_console.c:port_fops_splice_write
  - drivers/block/xen-blkfront.c:blkfront_setup_indirect
  - drivers/usb/core/devio.c:proc_do_submiturb
  - net/ipv4/tcp.c:tcp_md5_hash_skb_data
  - net/ipv4/tcp_bpf.c:tcp_bpf_push
```
**Symbols:**

```
ffffffff815a9780-ffffffff815a97b6: sg_init_table (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
void sg_init_table(struct scatterlist *sgl, unsigned int nents);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/scatterlist.c (ffffffff81613960)
Location: lib/scatterlist.c:124
Inline: True
Inline callers:
  - lib/scatterlist.c:sg_init_one
Direct callers:
  - mm/zswap.c:zswap_frontswap_load
  - mm/zswap.c:zswap_frontswap_store
  - mm/zswap.c:zswap_writeback_entry
  - mm/page_reporting.c:page_reporting_process
  - fs/crypto/crypto.c:fscrypt_crypt_block
  - fs/crypto/crypto.c:fscrypt_crypt_block
  - fs/verity/hash_algs.c:fsverity_hash_page
  - fs/ecryptfs/crypto.c:crypt_extent
  - fs/ecryptfs/crypto.c:crypt_extent
  - fs/ecryptfs/crypto.c:virt_to_scatterlist
  - crypto/scatterwalk.c:scatterwalk_ffwd
  - crypto/rsa-pkcs1pad.c:pkcs1pad_verify
  - crypto/rsa-pkcs1pad.c:pkcs1pad_decrypt
  - crypto/gcm.c:crypto_rfc4106_crypt
  - crypto/gcm.c:crypto_rfc4106_crypt
  - crypto/gcm.c:crypto_gcm_init_common
  - crypto/gcm.c:crypto_gcm_init_common
  - crypto/drbg.c:drbg_init_sym_kernel
  - crypto/asymmetric_keys/public_key.c:public_key_verify_signature
  - block/bsg-lib.c:bsg_map_buffer
  - block/blk-crypto-fallback.c:blk_crypto_fallback_decrypt_bio
  - block/blk-crypto-fallback.c:blk_crypto_fallback_encrypt_bio
  - block/blk-crypto-fallback.c:blk_crypto_fallback_encrypt_bio
  - lib/scatterlist.c:sgl_alloc_order
  - lib/scatterlist.c:sg_alloc_append_table_from_pages
  - lib/scatterlist.c:__sg_alloc_table
  - lib/sg_pool.c:sg_alloc_table_chained
  - drivers/tty/serial/8250/8250_dma.c:serial8250_rx_dma
  - drivers/tty/serial/8250/8250_dma.c:serial8250_tx_dma
  - drivers/char/virtio_console.c:port_fops_splice_write
  - drivers/block/xen-blkfront.c:blkfront_setup_indirect
  - drivers/usb/core/devio.c:proc_do_submiturb
  - net/ipv4/tcp.c:tcp_md5_hash_skb_data
  - net/ipv4/tcp_bpf.c:tcp_bpf_push
```
**Symbols:**

```
ffffffff816129c0-ffffffff816129f6: sg_init_table (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void sg_init_table(struct scatterlist *sgl, unsigned int nents);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/scatterlist.c (ffffffff816df000)
Location: lib/scatterlist.c:124
Inline: False
Direct callers:
  - mm/zswap.c:zswap_frontswap_load
  - mm/zswap.c:zswap_frontswap_store
  - mm/zswap.c:zswap_writeback_entry
  - mm/page_reporting.c:page_reporting_process
  - fs/crypto/crypto.c:fscrypt_crypt_block
  - fs/crypto/crypto.c:fscrypt_crypt_block
  - fs/verity/hash_algs.c:fsverity_hash_page
  - fs/ecryptfs/crypto.c:crypt_extent
  - fs/ecryptfs/crypto.c:crypt_extent
  - fs/ecryptfs/crypto.c:virt_to_scatterlist
  - crypto/scatterwalk.c:scatterwalk_ffwd
  - crypto/rsa-pkcs1pad.c:pkcs1pad_verify
  - crypto/rsa-pkcs1pad.c:pkcs1pad_decrypt
  - crypto/gcm.c:crypto_rfc4106_crypt
  - crypto/gcm.c:crypto_rfc4106_crypt
  - crypto/gcm.c:crypto_gcm_init_common
  - crypto/gcm.c:crypto_gcm_init_common
  - crypto/drbg.c:drbg_init_sym_kernel
  - crypto/asymmetric_keys/public_key.c:public_key_verify_signature
  - block/bsg-lib.c:bsg_map_buffer
  - block/blk-crypto-fallback.c:blk_crypto_fallback_decrypt_bio
  - block/blk-crypto-fallback.c:blk_crypto_fallback_encrypt_bio
  - block/blk-crypto-fallback.c:blk_crypto_fallback_encrypt_bio
  - lib/scatterlist.c:sgl_alloc_order
  - lib/scatterlist.c:sg_alloc_append_table_from_pages
  - lib/scatterlist.c:__sg_alloc_table
  - lib/scatterlist.c:sg_init_one
  - lib/sg_pool.c:sg_alloc_table_chained
  - drivers/tty/serial/8250/8250_dma.c:serial8250_rx_dma
  - drivers/tty/serial/8250/8250_dma.c:serial8250_tx_dma
  - drivers/char/virtio_console.c:port_fops_splice_write
  - drivers/block/xen-blkfront.c:blkfront_setup_indirect
  - drivers/usb/core/devio.c:proc_do_submiturb
  - net/ipv4/tcp.c:tcp_md5_hash_skb_data
  - net/ipv4/tcp_bpf.c:tcp_bpf_push
```
**Symbols:**

```
ffffffff816df000-ffffffff816df042: sg_init_table (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void sg_init_table(struct scatterlist *sgl, unsigned int nents);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/scatterlist.c (ffffffff817cf1f0)
Location: lib/scatterlist.c:124
Inline: False
Direct callers:
  - mm/zswap.c:zswap_frontswap_load
  - mm/zswap.c:zswap_frontswap_store
  - mm/zswap.c:zswap_writeback_entry
  - mm/page_reporting.c:page_reporting_process
  - fs/crypto/crypto.c:fscrypt_crypt_block
  - fs/crypto/crypto.c:fscrypt_crypt_block
  - fs/verity/hash_algs.c:fsverity_hash_page
  - fs/ecryptfs/crypto.c:crypt_extent
  - fs/ecryptfs/crypto.c:crypt_extent
  - fs/ecryptfs/crypto.c:virt_to_scatterlist
  - crypto/scatterwalk.c:scatterwalk_ffwd
  - crypto/rsa-pkcs1pad.c:pkcs1pad_verify
  - crypto/rsa-pkcs1pad.c:pkcs1pad_decrypt
  - crypto/gcm.c:crypto_rfc4106_crypt
  - crypto/gcm.c:crypto_rfc4106_crypt
  - crypto/gcm.c:crypto_gcm_init_common
  - crypto/gcm.c:crypto_gcm_init_common
  - crypto/drbg.c:drbg_init_sym_kernel
  - crypto/asymmetric_keys/public_key.c:public_key_verify_signature
  - block/bsg-lib.c:bsg_map_buffer
  - block/blk-crypto-fallback.c:blk_crypto_fallback_decrypt_bio
  - block/blk-crypto-fallback.c:blk_crypto_fallback_encrypt_bio
  - block/blk-crypto-fallback.c:blk_crypto_fallback_encrypt_bio
  - lib/scatterlist.c:sgl_alloc_order
  - lib/scatterlist.c:sg_alloc_append_table_from_pages
  - lib/scatterlist.c:__sg_alloc_table
  - lib/scatterlist.c:sg_init_one
  - lib/sg_pool.c:sg_alloc_table_chained
  - drivers/pci/p2pdma.c:pci_p2pmem_alloc_sgl
  - drivers/tty/serial/8250/8250_dma.c:serial8250_rx_dma
  - drivers/tty/serial/8250/8250_dma.c:serial8250_tx_dma
  - drivers/char/virtio_console.c:port_fops_splice_write
  - drivers/block/xen-blkfront.c:blkfront_setup_indirect
  - drivers/usb/core/devio.c:proc_do_submiturb
  - net/ipv4/tcp.c:tcp_md5_hash_skb_data
  - net/ipv4/tcp_bpf.c:tcp_bpf_push
```
**Symbols:**

```
ffffffff817cf1f0-ffffffff817cf232: sg_init_table (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void sg_init_table(struct scatterlist *sgl, unsigned int nents);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/scatterlist.c (ffffffff8180d6a0)
Location: lib/scatterlist.c:126
Inline: False
Direct callers:
  - mm/zswap.c:zswap_frontswap_load
  - mm/zswap.c:zswap_frontswap_store
  - mm/zswap.c:zswap_writeback_entry
  - mm/page_reporting.c:page_reporting_process
  - fs/crypto/crypto.c:fscrypt_crypt_block
  - fs/crypto/crypto.c:fscrypt_crypt_block
  - fs/ecryptfs/crypto.c:crypt_extent
  - fs/ecryptfs/crypto.c:crypt_extent
  - fs/ecryptfs/crypto.c:virt_to_scatterlist
  - crypto/scatterwalk.c:scatterwalk_ffwd
  - crypto/rsa-pkcs1pad.c:pkcs1pad_verify
  - crypto/rsa-pkcs1pad.c:pkcs1pad_decrypt
  - crypto/gcm.c:crypto_rfc4106_crypt
  - crypto/gcm.c:crypto_rfc4106_crypt
  - crypto/gcm.c:crypto_gcm_init_common
  - crypto/gcm.c:crypto_gcm_init_common
  - crypto/drbg.c:drbg_init_sym_kernel
  - block/bsg-lib.c:bsg_map_buffer
  - block/blk-crypto-fallback.c:blk_crypto_fallback_decrypt_bio
  - block/blk-crypto-fallback.c:blk_crypto_fallback_encrypt_bio
  - block/blk-crypto-fallback.c:blk_crypto_fallback_encrypt_bio
  - lib/scatterlist.c:sgl_alloc_order
  - lib/scatterlist.c:sg_alloc_append_table_from_pages
  - lib/scatterlist.c:__sg_alloc_table
  - lib/scatterlist.c:sg_init_one
  - lib/sg_pool.c:sg_alloc_table_chained
  - drivers/pci/p2pdma.c:pci_p2pmem_alloc_sgl
  - drivers/tty/serial/8250/8250_dma.c:serial8250_rx_dma
  - drivers/tty/serial/8250/8250_dma.c:serial8250_tx_dma
  - drivers/char/virtio_console.c:port_fops_splice_write
  - drivers/block/xen-blkfront.c:blkfront_setup_indirect
  - drivers/net/virtio_net.c:virtnet_alloc_queues
  - drivers/net/virtio_net.c:virtnet_alloc_queues
  - drivers/net/virtio_net.c:virtnet_commit_rss_command
  - drivers/net/virtio_net.c:virtnet_set_rx_mode
  - drivers/net/virtio_net.c:xmit_skb
  - drivers/net/virtio_net.c:xmit_skb
  - drivers/net/virtio_net.c:add_recvbuf_big
  - drivers/net/virtio_net.c:__virtnet_xdp_xmit_one
  - drivers/usb/core/devio.c:proc_do_submiturb
  - net/ipv4/tcp.c:tcp_md5_hash_skb_data
  - net/ipv4/tcp_bpf.c:tcp_bpf_push
```
**Symbols:**

```
ffffffff8180d6a0-ffffffff8180d6e2: sg_init_table (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void sg_init_table(struct scatterlist *sgl, unsigned int nents);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/scatterlist.c (ffffffff81853350)
Location: lib/scatterlist.c:126
Inline: False
Direct callers:
  - mm/zswap.c:zswap_store
  - mm/zswap.c:__zswap_load
  - mm/page_reporting.c:page_reporting_process
  - fs/crypto/crypto.c:fscrypt_crypt_data_unit
  - fs/crypto/crypto.c:fscrypt_crypt_data_unit
  - fs/ecryptfs/crypto.c:crypt_extent
  - fs/ecryptfs/crypto.c:crypt_extent
  - fs/ecryptfs/crypto.c:virt_to_scatterlist
  - crypto/scatterwalk.c:scatterwalk_ffwd
  - crypto/rsa-pkcs1pad.c:pkcs1pad_verify
  - crypto/rsa-pkcs1pad.c:pkcs1pad_decrypt
  - crypto/gcm.c:crypto_rfc4106_crypt
  - crypto/gcm.c:crypto_rfc4106_crypt
  - crypto/gcm.c:crypto_gcm_init_common
  - crypto/gcm.c:crypto_gcm_init_common
  - crypto/drbg.c:drbg_init_sym_kernel
  - block/bsg-lib.c:bsg_map_buffer
  - block/blk-crypto-fallback.c:blk_crypto_fallback_decrypt_bio
  - block/blk-crypto-fallback.c:blk_crypto_fallback_encrypt_bio
  - block/blk-crypto-fallback.c:blk_crypto_fallback_encrypt_bio
  - lib/scatterlist.c:sgl_alloc_order
  - lib/scatterlist.c:sg_alloc_append_table_from_pages
  - lib/scatterlist.c:__sg_alloc_table
  - lib/scatterlist.c:sg_init_one
  - lib/sg_pool.c:sg_alloc_table_chained
  - drivers/pci/p2pdma.c:pci_p2pmem_alloc_sgl
  - drivers/tty/serial/8250/8250_dma.c:serial8250_rx_dma
  - drivers/tty/serial/8250/8250_dma.c:serial8250_tx_dma
  - drivers/char/virtio_console.c:port_fops_splice_write
  - drivers/block/xen-blkfront.c:blkfront_setup_indirect
  - drivers/net/virtio_net.c:virtnet_alloc_queues
  - drivers/net/virtio_net.c:virtnet_alloc_queues
  - drivers/net/virtio_net.c:virtnet_commit_rss_command
  - drivers/net/virtio_net.c:virtnet_set_rx_mode
  - drivers/net/virtio_net.c:xmit_skb
  - drivers/net/virtio_net.c:xmit_skb
  - drivers/net/virtio_net.c:add_recvbuf_big
  - drivers/net/virtio_net.c:__virtnet_xdp_xmit_one
  - drivers/usb/core/devio.c:proc_do_submiturb
  - net/ipv4/tcp_sigpool.c:tcp_sigpool_hash_skb_data
  - net/ipv4/tcp_bpf.c:tcp_bpf_push
```
**Symbols:**

```
ffffffff81853350-ffffffff81853392: sg_init_table (STB_GLOBAL)
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
void sg_init_table(struct scatterlist *sgl, unsigned int nents);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/scatterlist.c (ffff80001062c090)
Location: lib/scatterlist.c:124
Inline: False
Direct callers:
  - fs/crypto/crypto.c:fscrypt_crypt_block
  - fs/crypto/crypto.c:fscrypt_crypt_block
  - fs/verity/hash_algs.c:fsverity_hash_page
  - fs/ecryptfs/crypto.c:crypt_extent
  - fs/ecryptfs/crypto.c:crypt_extent
  - fs/ecryptfs/crypto.c:virt_to_scatterlist
  - security/keys/big_key.c:big_key_alloc_buffer
  - crypto/rsa-pkcs1pad.c:pkcs1pad_sg_set_buf
  - crypto/gcm.c:crypto_rfc4106_crypt
  - crypto/gcm.c:crypto_rfc4106_crypt
  - crypto/gcm.c:crypto_gcm_init_common
  - crypto/gcm.c:crypto_gcm_init_common
  - crypto/drbg.c:drbg_init_sym_kernel
  - crypto/asymmetric_keys/public_key.c:public_key_verify_signature
  - lib/scatterlist.c:sgl_alloc_order
  - lib/scatterlist.c:__sg_alloc_table
  - lib/scatterlist.c:sg_init_one
  - drivers/video/fbdev/mx3fb.c:__set_par
  - drivers/video/fbdev/mx3fb.c:__set_par
  - drivers/tty/serial/8250/8250_dma.c:serial8250_rx_dma
  - drivers/tty/serial/8250/8250_dma.c:serial8250_tx_dma
  - drivers/tty/serial/8250/8250_mtk.c:mtk8250_rx_dma
  - drivers/tty/serial/imx.c:imx_uart_dma_tx
  - drivers/tty/serial/msm_serial.c:msm_handle_tx
  - drivers/char/virtio_console.c:port_fops_splice_write
  - drivers/block/xen-blkfront.c:blkfront_setup_indirect
  - drivers/usb/core/devio.c:proc_do_submiturb
  - drivers/mmc/core/queue.c:mmc_mq_init_request
  - net/ipv4/tcp.c:tcp_md5_hash_skb_data
  - net/ipv4/tcp_bpf.c:tcp_bpf_push
```
**Symbols:**

```
ffff80001062c090-ffff80001062c0d4: sg_init_table (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void sg_init_table(struct scatterlist *sgl, unsigned int nents);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/scatterlist.c (c07d2a80)
Location: lib/scatterlist.c:124
Inline: False
Direct callers:
  - fs/crypto/crypto.c:fscrypt_crypt_block
  - fs/crypto/crypto.c:fscrypt_crypt_block
  - fs/verity/hash_algs.c:fsverity_hash_page
  - fs/ecryptfs/crypto.c:crypt_extent
  - fs/ecryptfs/crypto.c:crypt_extent
  - fs/ecryptfs/crypto.c:virt_to_scatterlist
  - security/keys/big_key.c:big_key_alloc_buffer
  - crypto/rsa-pkcs1pad.c:pkcs1pad_verify
  - crypto/rsa-pkcs1pad.c:pkcs1pad_decrypt
  - crypto/gcm.c:crypto_rfc4106_crypt
  - crypto/gcm.c:crypto_rfc4106_crypt
  - crypto/gcm.c:crypto_gcm_init_common
  - crypto/gcm.c:crypto_gcm_init_common
  - crypto/drbg.c:drbg_init_sym_kernel
  - crypto/asymmetric_keys/public_key.c:public_key_verify_signature
  - lib/scatterlist.c:sgl_alloc_order
  - lib/scatterlist.c:__sg_alloc_table
  - lib/scatterlist.c:sg_init_one
  - drivers/video/fbdev/mx3fb.c:__set_par
  - drivers/video/fbdev/mx3fb.c:__set_par
  - drivers/soc/tegra/fuse/fuse-tegra20.c:tegra20_fuse_read
  - drivers/tty/serial/8250/8250_dma.c:serial8250_rx_dma
  - drivers/tty/serial/8250/8250_dma.c:serial8250_tx_dma
  - drivers/tty/serial/8250/8250_mtk.c:mtk8250_rx_dma
  - drivers/tty/serial/imx.c:imx_uart_dma_tx
  - drivers/tty/serial/msm_serial.c:msm_handle_tx
  - drivers/char/virtio_console.c:port_fops_splice_write
  - drivers/usb/core/devio.c:proc_do_submiturb
  - drivers/i2c/busses/i2c-imx.c:i2c_imx_dma_xfer
  - drivers/mmc/core/queue.c:mmc_mq_init_request
  - net/ipv4/tcp.c:tcp_md5_hash_skb_data
  - net/ipv4/tcp_bpf.c:tcp_bpf_push
```
**Symbols:**

```
c07d2a80-c07d2abc: sg_init_table (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void sg_init_table(struct scatterlist *sgl, unsigned int nents);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/scatterlist.c (c0000000007ce980)
Location: lib/scatterlist.c:124
Inline: False
Direct callers:
  - fs/crypto/crypto.c:fscrypt_crypt_block
  - fs/crypto/crypto.c:fscrypt_crypt_block
  - fs/verity/hash_algs.c:fsverity_hash_page
  - fs/ecryptfs/crypto.c:crypt_extent
  - fs/ecryptfs/crypto.c:crypt_extent
  - fs/ecryptfs/crypto.c:virt_to_scatterlist
  - security/keys/big_key.c:big_key_alloc_buffer
  - crypto/rsa-pkcs1pad.c:pkcs1pad_sg_set_buf
  - crypto/gcm.c:crypto_rfc4106_crypt
  - crypto/gcm.c:crypto_rfc4106_crypt
  - crypto/gcm.c:crypto_gcm_init_common
  - crypto/gcm.c:crypto_gcm_init_common
  - crypto/drbg.c:drbg_init_sym_kernel
  - crypto/asymmetric_keys/public_key.c:public_key_verify_signature
  - block/bsg-lib.c:bsg_map_buffer
  - lib/scatterlist.c:sgl_alloc_order
  - lib/scatterlist.c:__sg_alloc_table
  - lib/scatterlist.c:sg_init_one
  - lib/sg_pool.c:sg_alloc_table_chained
  - drivers/tty/serial/8250/8250_dma.c:serial8250_rx_dma
  - drivers/tty/serial/8250/8250_dma.c:serial8250_tx_dma
  - drivers/tty/serial/8250/8250_dma.c:serial8250_tx_dma
  - drivers/char/virtio_console.c:port_fops_splice_write
  - drivers/usb/core/devio.c:proc_do_submiturb
  - net/ipv4/tcp.c:tcp_md5_hash_skb_data
  - net/ipv4/tcp_bpf.c:tcp_bpf_push
```
**Symbols:**

```
c0000000007ce980-c0000000007ce9e4: sg_init_table (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
void sg_init_table(struct scatterlist *sgl, unsigned int nents);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/scatterlist.c (ffffffe00045c2d0)
Location: lib/scatterlist.c:124
Inline: True
Inline callers:
  - lib/scatterlist.c:sg_init_one
Direct callers:
  - fs/crypto/crypto.c:fscrypt_crypt_block
  - fs/crypto/crypto.c:fscrypt_crypt_block
  - fs/verity/hash_algs.c:fsverity_hash_page
  - fs/ecryptfs/crypto.c:crypt_extent
  - fs/ecryptfs/crypto.c:crypt_extent
  - fs/ecryptfs/crypto.c:virt_to_scatterlist
  - security/keys/big_key.c:big_key_alloc_buffer
  - crypto/rsa-pkcs1pad.c:pkcs1pad_sg_set_buf
  - crypto/gcm.c:crypto_rfc4106_crypt
  - crypto/gcm.c:crypto_rfc4106_crypt
  - crypto/gcm.c:crypto_gcm_init_common
  - crypto/gcm.c:crypto_gcm_init_common
  - crypto/drbg.c:drbg_init_sym_kernel
  - crypto/asymmetric_keys/public_key.c:public_key_verify_signature
  - lib/scatterlist.c:sgl_alloc_order
  - lib/scatterlist.c:__sg_alloc_table
  - drivers/tty/serial/8250/8250_dma.c:serial8250_rx_dma
  - drivers/tty/serial/8250/8250_dma.c:serial8250_tx_dma
  - drivers/char/virtio_console.c:port_fops_splice_write
  - drivers/usb/core/devio.c:proc_do_submiturb
  - drivers/mmc/core/queue.c:mmc_mq_init_request
  - net/ipv4/tcp.c:tcp_md5_hash_skb_data
  - net/ipv4/tcp_bpf.c:tcp_bpf_push
```
**Symbols:**

```
ffffffe00045c282-ffffffe00045c2d0: sg_init_table (STB_GLOBAL)
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
void sg_init_table(struct scatterlist *sgl, unsigned int nents);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/scatterlist.c (ffffffff8151a9f0)
Location: lib/scatterlist.c:124
Inline: False
Direct callers:
  - fs/crypto/crypto.c:fscrypt_crypt_block
  - fs/crypto/crypto.c:fscrypt_crypt_block
  - fs/verity/hash_algs.c:fsverity_hash_page
  - fs/ecryptfs/crypto.c:crypt_extent
  - fs/ecryptfs/crypto.c:crypt_extent
  - fs/ecryptfs/crypto.c:virt_to_scatterlist
  - security/keys/big_key.c:big_key_alloc_buffer
  - crypto/rsa-pkcs1pad.c:pkcs1pad_verify
  - crypto/rsa-pkcs1pad.c:pkcs1pad_decrypt
  - crypto/gcm.c:crypto_rfc4106_crypt
  - crypto/gcm.c:crypto_rfc4106_crypt
  - crypto/gcm.c:crypto_gcm_init_common
  - crypto/gcm.c:crypto_gcm_init_common
  - crypto/drbg.c:drbg_init_sym_kernel
  - crypto/asymmetric_keys/public_key.c:public_key_verify_signature
  - lib/scatterlist.c:sgl_alloc_order
  - lib/scatterlist.c:__sg_alloc_table
  - lib/scatterlist.c:sg_init_one
  - drivers/tty/serial/8250/8250_dma.c:serial8250_rx_dma
  - drivers/tty/serial/8250/8250_dma.c:serial8250_tx_dma
  - drivers/char/virtio_console.c:port_fops_splice_write
  - drivers/block/xen-blkfront.c:blkfront_setup_indirect
  - drivers/nvme/host/pci.c:nvme_map_data
  - drivers/usb/core/devio.c:proc_do_submiturb
  - net/ipv4/tcp.c:tcp_md5_hash_skb_data
  - net/ipv4/tcp_bpf.c:tcp_bpf_push
```
**Symbols:**

```
ffffffff8151a9f0-ffffffff8151aa23: sg_init_table (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void sg_init_table(struct scatterlist *sgl, unsigned int nents);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/scatterlist.c (ffffffff8150ace0)
Location: lib/scatterlist.c:124
Inline: False
Direct callers:
  - fs/crypto/crypto.c:fscrypt_crypt_block
  - fs/crypto/crypto.c:fscrypt_crypt_block
  - fs/verity/hash_algs.c:fsverity_hash_page
  - fs/ecryptfs/crypto.c:crypt_extent
  - fs/ecryptfs/crypto.c:crypt_extent
  - fs/ecryptfs/crypto.c:virt_to_scatterlist
  - security/keys/big_key.c:big_key_alloc_buffer
  - crypto/rsa-pkcs1pad.c:pkcs1pad_verify
  - crypto/rsa-pkcs1pad.c:pkcs1pad_decrypt
  - crypto/gcm.c:crypto_rfc4106_crypt
  - crypto/gcm.c:crypto_rfc4106_crypt
  - crypto/gcm.c:crypto_gcm_init_common
  - crypto/gcm.c:crypto_gcm_init_common
  - crypto/drbg.c:drbg_init_sym_kernel
  - crypto/asymmetric_keys/public_key.c:public_key_verify_signature
  - lib/scatterlist.c:sgl_alloc_order
  - lib/scatterlist.c:__sg_alloc_table
  - lib/scatterlist.c:sg_init_one
  - drivers/tty/serial/8250/8250_dma.c:serial8250_rx_dma
  - drivers/tty/serial/8250/8250_dma.c:serial8250_tx_dma
  - drivers/char/virtio_console.c:port_fops_splice_write
  - drivers/nvme/host/pci.c:nvme_map_data
  - drivers/usb/core/devio.c:proc_do_submiturb
  - net/ipv4/tcp.c:tcp_md5_hash_skb_data
  - net/ipv4/tcp_bpf.c:tcp_bpf_push
```
**Symbols:**

```
ffffffff8150ace0-ffffffff8150ad13: sg_init_table (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void sg_init_table(struct scatterlist *sgl, unsigned int nents);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/scatterlist.c (ffffffff81516a80)
Location: lib/scatterlist.c:124
Inline: False
Direct callers:
  - fs/crypto/crypto.c:fscrypt_crypt_block
  - fs/crypto/crypto.c:fscrypt_crypt_block
  - fs/verity/hash_algs.c:fsverity_hash_page
  - fs/ecryptfs/crypto.c:crypt_extent
  - fs/ecryptfs/crypto.c:crypt_extent
  - fs/ecryptfs/crypto.c:virt_to_scatterlist
  - security/keys/big_key.c:big_key_alloc_buffer
  - crypto/rsa-pkcs1pad.c:pkcs1pad_verify
  - crypto/rsa-pkcs1pad.c:pkcs1pad_decrypt
  - crypto/gcm.c:crypto_rfc4106_crypt
  - crypto/gcm.c:crypto_rfc4106_crypt
  - crypto/gcm.c:crypto_gcm_init_common
  - crypto/gcm.c:crypto_gcm_init_common
  - crypto/drbg.c:drbg_init_sym_kernel
  - crypto/asymmetric_keys/public_key.c:public_key_verify_signature
  - lib/scatterlist.c:sgl_alloc_order
  - lib/scatterlist.c:__sg_alloc_table
  - lib/scatterlist.c:sg_init_one
  - drivers/tty/serial/8250/8250_dma.c:serial8250_rx_dma
  - drivers/tty/serial/8250/8250_dma.c:serial8250_tx_dma
  - drivers/char/virtio_console.c:port_fops_splice_write
  - drivers/block/xen-blkfront.c:blkfront_setup_indirect
  - drivers/usb/core/devio.c:proc_do_submiturb
  - net/ipv4/tcp.c:tcp_md5_hash_skb_data
  - net/ipv4/tcp_bpf.c:tcp_bpf_push
```
**Symbols:**

```
ffffffff81516a80-ffffffff81516ab3: sg_init_table (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void sg_init_table(struct scatterlist *sgl, unsigned int nents);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/scatterlist.c (ffffffff81530210)
Location: lib/scatterlist.c:124
Inline: False
Direct callers:
  - fs/crypto/crypto.c:fscrypt_crypt_block
  - fs/crypto/crypto.c:fscrypt_crypt_block
  - fs/verity/hash_algs.c:fsverity_hash_page
  - fs/ecryptfs/crypto.c:crypt_extent
  - fs/ecryptfs/crypto.c:crypt_extent
  - fs/ecryptfs/crypto.c:virt_to_scatterlist
  - security/keys/big_key.c:big_key_alloc_buffer
  - crypto/rsa-pkcs1pad.c:pkcs1pad_verify
  - crypto/rsa-pkcs1pad.c:pkcs1pad_decrypt
  - crypto/gcm.c:crypto_rfc4106_crypt
  - crypto/gcm.c:crypto_rfc4106_crypt
  - crypto/gcm.c:crypto_gcm_init_common
  - crypto/gcm.c:crypto_gcm_init_common
  - crypto/drbg.c:drbg_init_sym_kernel
  - crypto/asymmetric_keys/public_key.c:public_key_verify_signature
  - lib/scatterlist.c:sgl_alloc_order
  - lib/scatterlist.c:__sg_alloc_table
  - lib/scatterlist.c:sg_init_one
  - drivers/tty/serial/8250/8250_dma.c:serial8250_rx_dma
  - drivers/tty/serial/8250/8250_dma.c:serial8250_tx_dma
  - drivers/char/virtio_console.c:port_fops_splice_write
  - drivers/block/xen-blkfront.c:blkfront_setup_indirect
  - drivers/usb/core/devio.c:proc_do_submiturb
  - net/ipv4/tcp.c:tcp_md5_hash_skb_data
  - net/ipv4/tcp_bpf.c:tcp_bpf_push
```
**Symbols:**

```
ffffffff81530210-ffffffff81530243: sg_init_table (STB_GLOBAL)
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
