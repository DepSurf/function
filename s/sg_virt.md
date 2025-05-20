# Function: <code>sg_virt</code>

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
In arch/x86/kernel/pci-calgary_64.c (0)
Location: include/linux/scatterlist.h:239
Inline: True
```
```
In lib/mpi/mpicoder.c (ffffffff81416f52)
Location: include/linux/scatterlist.h:239
Inline: True
Inline callers:
  - lib/mpi/mpicoder.c:mpi_write_to_sgl
  - lib/mpi/mpicoder.c:mpi_write_to_sgl
  - lib/mpi/mpicoder.c:mpi_read_raw_from_sgl
```
```
In drivers/char/agp/intel-gtt.c (0)
Location: include/linux/scatterlist.h:239
Inline: True
```
```
In drivers/scsi/scsi_lib_dma.c (0)
Location: include/linux/scatterlist.h:239
Inline: True
```
```
In drivers/ata/libata-core.c (0)
Location: include/linux/scatterlist.h:239
Inline: True
```
```
In drivers/spi/spi.c (0)
Location: include/linux/scatterlist.h:239
Inline: True
```
```
In drivers/usb/core/hcd.c (0)
Location: include/linux/scatterlist.h:239
Inline: True
```
```
In drivers/usb/core/message.c (0)
Location: include/linux/scatterlist.h:239
Inline: True
```
```
In drivers/usb/core/devio.c (0)
Location: include/linux/scatterlist.h:239
Inline: True
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
In arch/x86/kernel/pci-calgary_64.c (ffffffff81067bc9)
Location: include/linux/scatterlist.h:239
Inline: True
Inline callers:
  - arch/x86/kernel/pci-calgary_64.c:calgary_map_sg
```
```
In drivers/char/agp/intel-gtt.c (0)
Location: include/linux/scatterlist.h:239
Inline: True
```
```
In drivers/scsi/scsi_lib_dma.c (0)
Location: include/linux/scatterlist.h:239
Inline: True
```
```
In drivers/ata/libata-core.c (0)
Location: include/linux/scatterlist.h:239
Inline: True
```
```
In drivers/spi/spi.c (0)
Location: include/linux/scatterlist.h:239
Inline: True
```
```
In drivers/usb/core/hcd.c (0)
Location: include/linux/scatterlist.h:239
Inline: True
```
```
In drivers/usb/core/message.c (ffffffff8167121f)
Location: include/linux/scatterlist.h:239
Inline: True
Inline callers:
  - drivers/usb/core/message.c:usb_sg_init
```
```
In drivers/usb/core/devio.c (ffffffff8167ccf2)
Location: include/linux/scatterlist.h:239
Inline: True
Inline callers:
  - drivers/usb/core/devio.c:copy_urb_data_to_user
  - drivers/usb/core/devio.c:snoop_urb_data
  - drivers/usb/core/devio.c:free_async
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
In arch/x86/kernel/pci-calgary_64.c (ffffffff8106b81f)
Location: include/linux/scatterlist.h:239
Inline: True
Inline callers:
  - arch/x86/kernel/pci-calgary_64.c:calgary_map_sg
```
```
In drivers/char/agp/intel-gtt.c (0)
Location: include/linux/scatterlist.h:239
Inline: True
```
```
In drivers/scsi/scsi_lib_dma.c (0)
Location: include/linux/scatterlist.h:239
Inline: True
```
```
In drivers/ata/libata-core.c (0)
Location: include/linux/scatterlist.h:239
Inline: True
```
```
In drivers/spi/spi.c (0)
Location: include/linux/scatterlist.h:239
Inline: True
```
```
In drivers/usb/core/hcd.c (0)
Location: include/linux/scatterlist.h:239
Inline: True
```
```
In drivers/usb/core/message.c (ffffffff8169eecf)
Location: include/linux/scatterlist.h:239
Inline: True
Inline callers:
  - drivers/usb/core/message.c:usb_sg_init
```
```
In drivers/usb/core/devio.c (ffffffff816aaa84)
Location: include/linux/scatterlist.h:239
Inline: True
Inline callers:
  - drivers/usb/core/devio.c:copy_urb_data_to_user
  - drivers/usb/core/devio.c:snoop_urb_data
  - drivers/usb/core/devio.c:free_async
```
```
In lib/dma-noop.c (ffffffff818c55dd)
Location: include/linux/scatterlist.h:239
Inline: True
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
In arch/x86/kernel/pci-calgary_64.c (ffffffff8106ab99)
Location: include/linux/scatterlist.h:239
Inline: True
Inline callers:
  - arch/x86/kernel/pci-calgary_64.c:calgary_map_sg
```
```
In drivers/char/agp/intel-gtt.c (0)
Location: include/linux/scatterlist.h:239
Inline: True
```
```
In drivers/scsi/scsi_lib_dma.c (0)
Location: include/linux/scatterlist.h:239
Inline: True
```
```
In drivers/ata/libata-core.c (0)
Location: include/linux/scatterlist.h:239
Inline: True
```
```
In drivers/spi/spi.c (0)
Location: include/linux/scatterlist.h:239
Inline: True
```
```
In drivers/usb/core/hcd.c (0)
Location: include/linux/scatterlist.h:239
Inline: True
```
```
In drivers/usb/core/message.c (ffffffff816b400b)
Location: include/linux/scatterlist.h:239
Inline: True
Inline callers:
  - drivers/usb/core/message.c:usb_sg_init
```
```
In drivers/usb/core/devio.c (ffffffff816bfa84)
Location: include/linux/scatterlist.h:239
Inline: True
Inline callers:
  - drivers/usb/core/devio.c:copy_urb_data_to_user
  - drivers/usb/core/devio.c:snoop_urb_data
  - drivers/usb/core/devio.c:free_async
```
```
In lib/dma-virt.c (ffffffff818ebefc)
Location: include/linux/scatterlist.h:239
Inline: True
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
In arch/x86/kernel/pci-calgary_64.c (ffffffff8106f499)
Location: include/linux/scatterlist.h:246
Inline: True
Inline callers:
  - arch/x86/kernel/pci-calgary_64.c:calgary_map_sg
```
```
In drivers/usb/core/message.c (ffffffff8171f83b)
Location: include/linux/scatterlist.h:246
Inline: True
Inline callers:
  - drivers/usb/core/message.c:usb_sg_init
```
```
In drivers/usb/core/devio.c (ffffffff8172b434)
Location: include/linux/scatterlist.h:246
Inline: True
Inline callers:
  - drivers/usb/core/devio.c:copy_urb_data_to_user
  - drivers/usb/core/devio.c:snoop_urb_data
  - drivers/usb/core/devio.c:free_async
```
```
In lib/dma-virt.c (ffffffff81971eec)
Location: include/linux/scatterlist.h:246
Inline: True
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
In arch/x86/kernel/pci-calgary_64.c (ffffffff810720d9)
Location: include/linux/scatterlist.h:237
Inline: True
Inline callers:
  - arch/x86/kernel/pci-calgary_64.c:calgary_map_sg
```
```
In kernel/dma/virt.c (ffffffff8110d251)
Location: include/linux/scatterlist.h:237
Inline: True
```
```
In kernel/bpf/sockmap.c (ffffffff811cfbac)
Location: include/linux/scatterlist.h:237
Inline: True
Inline callers:
  - kernel/bpf/sockmap.c:bpf_tcp_sendmsg
  - kernel/bpf/sockmap.c:bpf_exec_tx_verdict
```
```
In drivers/usb/core/message.c (ffffffff8175f4bb)
Location: include/linux/scatterlist.h:237
Inline: True
Inline callers:
  - drivers/usb/core/message.c:usb_sg_init
```
```
In drivers/usb/core/devio.c (ffffffff8176a4ef)
Location: include/linux/scatterlist.h:237
Inline: True
Inline callers:
  - drivers/usb/core/devio.c:copy_urb_data_to_user
  - drivers/usb/core/devio.c:snoop_urb_data
  - drivers/usb/core/devio.c:free_async
```
```
In net/core/filter.c (ffffffff818b3a94)
Location: include/linux/scatterlist.h:237
Inline: True
Inline callers:
  - net/core/filter.c:bpf_msg_pull_data
  - net/core/filter.c:bpf_msg_pull_data
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
In arch/x86/kernel/pci-calgary_64.c (ffffffff8107809a)
Location: include/linux/scatterlist.h:237
Inline: True
Inline callers:
  - arch/x86/kernel/pci-calgary_64.c:calgary_map_sg
```
```
In kernel/dma/virt.c (ffffffff81118f21)
Location: include/linux/scatterlist.h:237
Inline: True
```
```
In drivers/usb/core/message.c (ffffffff81783a9b)
Location: include/linux/scatterlist.h:237
Inline: True
Inline callers:
  - drivers/usb/core/message.c:usb_sg_init
```
```
In drivers/usb/core/devio.c (ffffffff8178ea7f)
Location: include/linux/scatterlist.h:237
Inline: True
Inline callers:
  - drivers/usb/core/devio.c:copy_urb_data_to_user
  - drivers/usb/core/devio.c:snoop_urb_data
  - drivers/usb/core/devio.c:free_async
```
```
In net/core/filter.c (ffffffff818d95f8)
Location: include/linux/scatterlist.h:237
Inline: True
Inline callers:
  - net/core/filter.c:bpf_msg_pop_data
  - net/core/filter.c:bpf_msg_pop_data
  - net/core/filter.c:bpf_msg_push_data
  - net/core/filter.c:bpf_msg_push_data
  - net/core/filter.c:bpf_msg_pull_data
  - net/core/filter.c:bpf_msg_pull_data
```
```
In net/core/skmsg.c (ffffffff818e5ccb)
Location: include/linux/scatterlist.h:237
Inline: True
Inline callers:
  - net/core/skmsg.c:sk_psock_msg_verdict
  - net/core/skmsg.c:sk_msg_memcopy_from_iter
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
In arch/x86/kernel/pci-calgary_64.c (ffffffff8107bc1d)
Location: include/linux/scatterlist.h:237
Inline: True
Inline callers:
  - arch/x86/kernel/pci-calgary_64.c:calgary_map_sg
```
```
In kernel/dma/virt.c (ffffffff811238da)
Location: include/linux/scatterlist.h:237
Inline: True
```
```
In drivers/usb/core/message.c (ffffffff817c1dae)
Location: include/linux/scatterlist.h:237
Inline: True
Inline callers:
  - drivers/usb/core/message.c:usb_sg_init
```
```
In drivers/usb/core/devio.c (ffffffff817cb74e)
Location: include/linux/scatterlist.h:237
Inline: True
Inline callers:
  - drivers/usb/core/devio.c:copy_urb_data_to_user
  - drivers/usb/core/devio.c:snoop_urb_data
  - drivers/usb/core/devio.c:free_async
```
```
In net/core/filter.c (ffffffff8192b7c3)
Location: include/linux/scatterlist.h:237
Inline: True
Inline callers:
  - net/core/filter.c:bpf_msg_pop_data
  - net/core/filter.c:bpf_msg_pop_data
  - net/core/filter.c:bpf_msg_push_data
  - net/core/filter.c:bpf_msg_push_data
  - net/core/filter.c:bpf_msg_pull_data
  - net/core/filter.c:bpf_msg_pull_data
```
```
In net/core/skmsg.c (ffffffff819355e5)
Location: include/linux/scatterlist.h:237
Inline: True
Inline callers:
  - net/core/skmsg.c:sk_psock_msg_verdict
  - net/core/skmsg.c:sk_msg_memcopy_from_iter
  - net/core/skmsg.c:sk_msg_clone
  - net/core/skmsg.c:sk_msg_clone
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
In arch/x86/kernel/pci-calgary_64.c (ffffffff8107cd0d)
Location: include/linux/scatterlist.h:237
Inline: True
Inline callers:
  - arch/x86/kernel/pci-calgary_64.c:calgary_map_sg
```
```
In kernel/dma/virt.c (ffffffff8112f86a)
Location: include/linux/scatterlist.h:237
Inline: True
```
```
In drivers/usb/core/message.c (ffffffff817f272e)
Location: include/linux/scatterlist.h:237
Inline: True
Inline callers:
  - drivers/usb/core/message.c:usb_sg_init
```
```
In drivers/usb/core/devio.c (ffffffff817fc3ae)
Location: include/linux/scatterlist.h:237
Inline: True
Inline callers:
  - drivers/usb/core/devio.c:copy_urb_data_to_user
  - drivers/usb/core/devio.c:snoop_urb_data
  - drivers/usb/core/devio.c:free_async
```
```
In net/core/filter.c (ffffffff8195daf3)
Location: include/linux/scatterlist.h:237
Inline: True
Inline callers:
  - net/core/filter.c:bpf_msg_pop_data
  - net/core/filter.c:bpf_msg_pop_data
  - net/core/filter.c:bpf_msg_push_data
  - net/core/filter.c:bpf_msg_push_data
  - net/core/filter.c:bpf_msg_pull_data
  - net/core/filter.c:bpf_msg_pull_data
```
```
In net/core/skmsg.c (ffffffff819683a5)
Location: include/linux/scatterlist.h:237
Inline: True
Inline callers:
  - net/core/skmsg.c:sk_psock_msg_verdict
  - net/core/skmsg.c:sk_msg_memcopy_from_iter
  - net/core/skmsg.c:sk_msg_clone
  - net/core/skmsg.c:sk_msg_clone
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
In kernel/dma/virt.c (ffffffff8113e62a)
Location: include/linux/scatterlist.h:251
Inline: True
Inline callers:
  - kernel/dma/virt.c:dma_virt_map_sg
```
```
In drivers/usb/core/message.c (ffffffff818c20ab)
Location: include/linux/scatterlist.h:251
Inline: True
Inline callers:
  - drivers/usb/core/message.c:usb_sg_init
```
```
In drivers/usb/core/devio.c (ffffffff818cde1e)
Location: include/linux/scatterlist.h:251
Inline: True
Inline callers:
  - drivers/usb/core/devio.c:copy_urb_data_to_user
  - drivers/usb/core/devio.c:snoop_urb_data
  - drivers/usb/core/devio.c:free_async
```
```
In net/core/filter.c (ffffffff81a2cc30)
Location: include/linux/scatterlist.h:251
Inline: True
Inline callers:
  - net/core/filter.c:bpf_msg_pop_data
  - net/core/filter.c:bpf_msg_pop_data
  - net/core/filter.c:bpf_msg_push_data
  - net/core/filter.c:bpf_msg_push_data
  - net/core/filter.c:bpf_msg_pull_data
  - net/core/filter.c:bpf_msg_pull_data
```
```
In net/core/skmsg.c (ffffffff81a3bde1)
Location: include/linux/scatterlist.h:251
Inline: True
Inline callers:
  - net/core/skmsg.c:sk_psock_msg_verdict
  - net/core/skmsg.c:sk_msg_memcopy_from_iter
  - net/core/skmsg.c:sk_msg_clone
  - net/core/skmsg.c:sk_msg_clone
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
In drivers/usb/core/message.c (ffffffff818ce39b)
Location: include/linux/scatterlist.h:250
Inline: True
Inline callers:
  - drivers/usb/core/message.c:usb_sg_init
```
```
In drivers/usb/core/devio.c (ffffffff818d8e16)
Location: include/linux/scatterlist.h:250
Inline: True
Inline callers:
  - drivers/usb/core/devio.c:copy_urb_data_to_user
  - drivers/usb/core/devio.c:snoop_urb_data
  - drivers/usb/core/devio.c:free_async
```
```
In net/core/filter.c (ffffffff81a2e1e9)
Location: include/linux/scatterlist.h:250
Inline: True
Inline callers:
  - net/core/filter.c:bpf_msg_pop_data
  - net/core/filter.c:bpf_msg_pop_data
  - net/core/filter.c:bpf_msg_push_data
  - net/core/filter.c:bpf_msg_push_data
  - net/core/filter.c:bpf_msg_pull_data
  - net/core/filter.c:bpf_msg_pull_data
```
```
In net/core/skmsg.c (ffffffff81a3fec5)
Location: include/linux/scatterlist.h:250
Inline: True
Inline callers:
  - net/core/skmsg.c:sk_psock_msg_verdict
  - net/core/skmsg.c:sk_msg_memcopy_from_iter
  - net/core/skmsg.c:sk_msg_clone
  - net/core/skmsg.c:sk_msg_clone
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
In drivers/usb/core/message.c (ffffffff818b166e)
Location: include/linux/scatterlist.h:250
Inline: True
Inline callers:
  - drivers/usb/core/message.c:usb_sg_init
```
```
In drivers/usb/core/devio.c (ffffffff818bbfa5)
Location: include/linux/scatterlist.h:250
Inline: True
Inline callers:
  - drivers/usb/core/devio.c:copy_urb_data_to_user
  - drivers/usb/core/devio.c:snoop_urb_data
  - drivers/usb/core/devio.c:free_async
```
```
In net/core/filter.c (ffffffff81a14e89)
Location: include/linux/scatterlist.h:250
Inline: True
Inline callers:
  - net/core/filter.c:bpf_msg_pop_data
  - net/core/filter.c:bpf_msg_pop_data
  - net/core/filter.c:bpf_msg_push_data
  - net/core/filter.c:bpf_msg_push_data
  - net/core/filter.c:bpf_msg_pull_data
  - net/core/filter.c:bpf_msg_pull_data
```
```
In net/core/skmsg.c (ffffffff81a4e768)
Location: include/linux/scatterlist.h:250
Inline: True
Inline callers:
  - net/core/skmsg.c:sk_psock_msg_verdict
  - net/core/skmsg.c:sk_msg_memcopy_from_iter
  - net/core/skmsg.c:sk_msg_clone
  - net/core/skmsg.c:sk_msg_clone
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
In drivers/usb/core/message.c (ffffffff819468be)
Location: include/linux/scatterlist.h:256
Inline: True
Inline callers:
  - drivers/usb/core/message.c:usb_sg_init
```
```
In drivers/usb/core/devio.c (ffffffff81950775)
Location: include/linux/scatterlist.h:256
Inline: True
Inline callers:
  - drivers/usb/core/devio.c:copy_urb_data_to_user
  - drivers/usb/core/devio.c:snoop_urb_data
  - drivers/usb/core/devio.c:free_async
```
```
In net/core/filter.c (ffffffff81ac86db)
Location: include/linux/scatterlist.h:256
Inline: True
Inline callers:
  - net/core/filter.c:bpf_msg_pop_data
  - net/core/filter.c:bpf_msg_pop_data
  - net/core/filter.c:bpf_msg_push_data
  - net/core/filter.c:bpf_msg_push_data
  - net/core/filter.c:bpf_msg_pull_data
  - net/core/filter.c:bpf_msg_pull_data
```
```
In net/core/skmsg.c (ffffffff81b05119)
Location: include/linux/scatterlist.h:256
Inline: True
Inline callers:
  - net/core/skmsg.c:sk_psock_msg_verdict
  - net/core/skmsg.c:sk_msg_memcopy_from_iter
  - net/core/skmsg.c:sk_msg_clone
  - net/core/skmsg.c:sk_msg_clone
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
In drivers/usb/core/message.c (ffffffff81a9f38a)
Location: include/linux/scatterlist.h:273
Inline: True
Inline callers:
  - drivers/usb/core/message.c:usb_sg_init
```
```
In drivers/usb/core/devio.c (ffffffff81aa8f73)
Location: include/linux/scatterlist.h:273
Inline: True
Inline callers:
  - drivers/usb/core/devio.c:copy_urb_data_to_user
  - drivers/usb/core/devio.c:snoop_urb_data
  - drivers/usb/core/devio.c:free_async
```
```
In net/core/filter.c (ffffffff81c44c50)
Location: include/linux/scatterlist.h:273
Inline: True
Inline callers:
  - net/core/filter.c:bpf_msg_pop_data
  - net/core/filter.c:bpf_msg_pop_data
  - net/core/filter.c:bpf_msg_push_data
  - net/core/filter.c:bpf_msg_push_data
  - net/core/filter.c:bpf_msg_pull_data
  - net/core/filter.c:bpf_msg_pull_data
```
```
In net/core/skmsg.c (ffffffff81c8d3ff)
Location: include/linux/scatterlist.h:273
Inline: True
Inline callers:
  - net/core/skmsg.c:sk_psock_msg_verdict
  - net/core/skmsg.c:sk_msg_memcopy_from_iter
  - net/core/skmsg.c:sk_msg_clone
  - net/core/skmsg.c:sk_msg_clone
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
In drivers/pci/p2pdma.c (ffffffff8191ce36)
Location: include/linux/scatterlist.h:342
Inline: True
Inline callers:
  - drivers/pci/p2pdma.c:pci_p2pmem_free_sgl
```
```
In drivers/usb/core/message.c (ffffffff81c2480a)
Location: include/linux/scatterlist.h:342
Inline: True
Inline callers:
  - drivers/usb/core/message.c:usb_sg_init
```
```
In drivers/usb/core/devio.c (ffffffff81c30223)
Location: include/linux/scatterlist.h:342
Inline: True
Inline callers:
  - drivers/usb/core/devio.c:copy_urb_data_to_user
  - drivers/usb/core/devio.c:snoop_urb_data
  - drivers/usb/core/devio.c:free_async
```
```
In net/core/filter.c (ffffffff81dff20d)
Location: include/linux/scatterlist.h:342
Inline: True
Inline callers:
  - net/core/filter.c:bpf_msg_pop_data
  - net/core/filter.c:bpf_msg_pop_data
  - net/core/filter.c:bpf_msg_push_data
  - net/core/filter.c:bpf_msg_push_data
  - net/core/filter.c:bpf_msg_pull_data
  - net/core/filter.c:bpf_msg_pull_data
```
```
In net/core/skmsg.c (ffffffff81e45a3f)
Location: include/linux/scatterlist.h:342
Inline: True
Inline callers:
  - net/core/skmsg.c:sk_psock_msg_verdict
  - net/core/skmsg.c:sk_msg_memcopy_from_iter
  - net/core/skmsg.c:sk_msg_clone
  - net/core/skmsg.c:sk_msg_clone
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
In drivers/pci/p2pdma.c (ffffffff819603f6)
Location: include/linux/scatterlist.h:402
Inline: True
Inline callers:
  - drivers/pci/p2pdma.c:pci_p2pmem_free_sgl
```
```
In drivers/usb/core/message.c (ffffffff81c8b962)
Location: include/linux/scatterlist.h:402
Inline: True
Inline callers:
  - drivers/usb/core/message.c:usb_sg_init
```
```
In drivers/usb/core/devio.c (ffffffff81c9746e)
Location: include/linux/scatterlist.h:402
Inline: True
Inline callers:
  - drivers/usb/core/devio.c:copy_urb_data_to_user
  - drivers/usb/core/devio.c:snoop_urb_data
  - drivers/usb/core/devio.c:free_async
```
```
In net/core/filter.c (ffffffff81e70cdd)
Location: include/linux/scatterlist.h:402
Inline: True
Inline callers:
  - net/core/filter.c:bpf_msg_pop_data
  - net/core/filter.c:bpf_msg_pop_data
  - net/core/filter.c:bpf_msg_push_data
  - net/core/filter.c:bpf_msg_push_data
  - net/core/filter.c:bpf_msg_pull_data
  - net/core/filter.c:bpf_msg_pull_data
```
```
In net/core/skmsg.c (ffffffff81ea104f)
Location: include/linux/scatterlist.h:402
Inline: True
Inline callers:
  - net/core/skmsg.c:sk_psock_msg_verdict
  - net/core/skmsg.c:sk_msg_memcopy_from_iter
  - net/core/skmsg.c:sk_msg_clone
  - net/core/skmsg.c:sk_msg_clone
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
In drivers/pci/p2pdma.c (ffffffff819a9ae6)
Location: include/linux/scatterlist.h:402
Inline: True
Inline callers:
  - drivers/pci/p2pdma.c:pci_p2pmem_free_sgl
```
```
In drivers/usb/core/message.c (ffffffff81d40412)
Location: include/linux/scatterlist.h:402
Inline: True
Inline callers:
  - drivers/usb/core/message.c:usb_sg_init
```
```
In drivers/usb/core/devio.c (ffffffff81d4bf4e)
Location: include/linux/scatterlist.h:402
Inline: True
Inline callers:
  - drivers/usb/core/devio.c:copy_urb_data_to_user
  - drivers/usb/core/devio.c:snoop_urb_data
  - drivers/usb/core/devio.c:free_async
```
```
In net/core/filter.c (ffffffff81f303b4)
Location: include/linux/scatterlist.h:402
Inline: True
Inline callers:
  - net/core/filter.c:bpf_msg_pop_data
  - net/core/filter.c:bpf_msg_pop_data
  - net/core/filter.c:bpf_msg_push_data
  - net/core/filter.c:bpf_msg_push_data
  - net/core/filter.c:bpf_msg_pull_data
  - net/core/filter.c:bpf_msg_pull_data
```
```
In net/core/skmsg.c (ffffffff81f6372f)
Location: include/linux/scatterlist.h:402
Inline: True
Inline callers:
  - net/core/skmsg.c:sk_psock_msg_verdict
  - net/core/skmsg.c:sk_msg_memcopy_from_iter
  - net/core/skmsg.c:sk_msg_clone
  - net/core/skmsg.c:sk_msg_clone
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
In kernel/dma/virt.c (ffff800010195f98)
Location: include/linux/scatterlist.h:237
Inline: True
```
```
In drivers/usb/core/message.c (ffff800010a22978)
Location: include/linux/scatterlist.h:237
Inline: True
Inline callers:
  - drivers/usb/core/message.c:usb_sg_init
```
```
In drivers/usb/core/devio.c (ffff800010a2f860)
Location: include/linux/scatterlist.h:237
Inline: True
Inline callers:
  - drivers/usb/core/devio.c:copy_urb_data_to_user
  - drivers/usb/core/devio.c:snoop_urb_data
  - drivers/usb/core/devio.c:free_async
```
```
In net/core/filter.c (ffff800010bfdba8)
Location: include/linux/scatterlist.h:237
Inline: True
Inline callers:
  - net/core/filter.c:bpf_msg_pop_data
  - net/core/filter.c:bpf_msg_pop_data
  - net/core/filter.c:bpf_msg_push_data
  - net/core/filter.c:bpf_msg_push_data
  - net/core/filter.c:bpf_msg_pull_data
  - net/core/filter.c:bpf_msg_pull_data
```
```
In net/core/skmsg.c (ffff800010c0e2b4)
Location: include/linux/scatterlist.h:237
Inline: True
Inline callers:
  - net/core/skmsg.c:sk_psock_msg_verdict
  - net/core/skmsg.c:sk_msg_memcopy_from_iter
  - net/core/skmsg.c:sk_msg_clone
  - net/core/skmsg.c:sk_msg_clone
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
In kernel/dma/virt.c (c03e281c)
Location: include/linux/scatterlist.h:237
Inline: True
```
```
In drivers/usb/core/message.c (c0af97f8)
Location: include/linux/scatterlist.h:237
Inline: True
Inline callers:
  - drivers/usb/core/message.c:usb_sg_init
```
```
In drivers/usb/core/devio.c (c0b034d0)
Location: include/linux/scatterlist.h:237
Inline: True
Inline callers:
  - drivers/usb/core/devio.c:processcompl
  - drivers/usb/core/devio.c:snoop_urb_data
  - drivers/usb/core/devio.c:free_async
```
```
In net/core/filter.c (c0d19fd8)
Location: include/linux/scatterlist.h:237
Inline: True
Inline callers:
  - net/core/filter.c:bpf_msg_pop_data
  - net/core/filter.c:bpf_msg_pop_data
  - net/core/filter.c:bpf_msg_push_data
  - net/core/filter.c:bpf_msg_push_data
  - net/core/filter.c:bpf_msg_pull_data
  - net/core/filter.c:bpf_msg_pull_data
```
```
In net/core/skmsg.c (c0d266b0)
Location: include/linux/scatterlist.h:237
Inline: True
Inline callers:
  - net/core/skmsg.c:sk_psock_msg_verdict
  - net/core/skmsg.c:sk_msg_memcopy_from_iter
  - net/core/skmsg.c:sk_msg_clone
  - net/core/skmsg.c:sk_msg_clone
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
In arch/powerpc/kernel/iommu.c (c00000000005236c)
Location: include/linux/scatterlist.h:237
Inline: True
Inline callers:
  - arch/powerpc/kernel/iommu.c:ppc_iommu_map_sg
```
```
In kernel/dma/virt.c (c0000000001f6024)
Location: include/linux/scatterlist.h:237
Inline: True
Inline callers:
  - kernel/dma/virt.c:dma_virt_map_sg
```
```
In drivers/usb/core/message.c (c000000000add980)
Location: include/linux/scatterlist.h:237
Inline: True
Inline callers:
  - drivers/usb/core/message.c:usb_sg_init
```
```
In drivers/usb/core/devio.c (c000000000aebf7c)
Location: include/linux/scatterlist.h:237
Inline: True
Inline callers:
  - drivers/usb/core/devio.c:copy_urb_data_to_user
  - drivers/usb/core/devio.c:snoop_urb_data
  - drivers/usb/core/devio.c:free_async
```
```
In net/core/filter.c (c000000000ce9824)
Location: include/linux/scatterlist.h:237
Inline: True
Inline callers:
  - net/core/filter.c:bpf_msg_pop_data
  - net/core/filter.c:bpf_msg_pop_data
  - net/core/filter.c:bpf_msg_push_data
  - net/core/filter.c:bpf_msg_push_data
  - net/core/filter.c:bpf_msg_pull_data
  - net/core/filter.c:bpf_msg_pull_data
```
```
In net/core/skmsg.c (c000000000cf9b84)
Location: include/linux/scatterlist.h:237
Inline: True
Inline callers:
  - net/core/skmsg.c:sk_psock_msg_verdict
  - net/core/skmsg.c:sk_msg_memcopy_from_iter
  - net/core/skmsg.c:sk_msg_clone
  - net/core/skmsg.c:sk_msg_clone
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
In kernel/dma/virt.c (ffffffe0001279e2)
Location: include/linux/scatterlist.h:237
Inline: True
```
```
In drivers/usb/core/message.c (ffffffe000645866)
Location: include/linux/scatterlist.h:237
Inline: True
Inline callers:
  - drivers/usb/core/message.c:usb_sg_init
```
```
In drivers/usb/core/devio.c (ffffffe00064fc36)
Location: include/linux/scatterlist.h:237
Inline: True
Inline callers:
  - drivers/usb/core/devio.c:processcompl
  - drivers/usb/core/devio.c:snoop_urb_data
  - drivers/usb/core/devio.c:free_async
```
```
In net/core/filter.c (ffffffe00077d2aa)
Location: include/linux/scatterlist.h:237
Inline: True
Inline callers:
  - net/core/filter.c:bpf_msg_pop_data
  - net/core/filter.c:bpf_msg_pop_data
  - net/core/filter.c:bpf_msg_push_data
  - net/core/filter.c:bpf_msg_push_data
  - net/core/filter.c:bpf_msg_pull_data
  - net/core/filter.c:bpf_msg_pull_data
```
```
In net/core/skmsg.c (ffffffe00078ad20)
Location: include/linux/scatterlist.h:237
Inline: True
Inline callers:
  - net/core/skmsg.c:sk_psock_msg_verdict
  - net/core/skmsg.c:sk_msg_memcopy_from_iter
  - net/core/skmsg.c:sk_msg_clone
  - net/core/skmsg.c:sk_msg_clone
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
In arch/x86/kernel/pci-calgary_64.c (ffffffff8107bd0d)
Location: include/linux/scatterlist.h:237
Inline: True
Inline callers:
  - arch/x86/kernel/pci-calgary_64.c:calgary_map_sg
```
```
In kernel/dma/virt.c (ffffffff8112801a)
Location: include/linux/scatterlist.h:237
Inline: True
```
```
In drivers/usb/core/message.c (ffffffff817aab0e)
Location: include/linux/scatterlist.h:237
Inline: True
Inline callers:
  - drivers/usb/core/message.c:usb_sg_init
```
```
In drivers/usb/core/devio.c (ffffffff817b478e)
Location: include/linux/scatterlist.h:237
Inline: True
Inline callers:
  - drivers/usb/core/devio.c:copy_urb_data_to_user
  - drivers/usb/core/devio.c:snoop_urb_data
  - drivers/usb/core/devio.c:free_async
```
```
In net/core/filter.c (ffffffff818fdac3)
Location: include/linux/scatterlist.h:237
Inline: True
Inline callers:
  - net/core/filter.c:bpf_msg_pop_data
  - net/core/filter.c:bpf_msg_pop_data
  - net/core/filter.c:bpf_msg_push_data
  - net/core/filter.c:bpf_msg_push_data
  - net/core/filter.c:bpf_msg_pull_data
  - net/core/filter.c:bpf_msg_pull_data
```
```
In net/core/skmsg.c (ffffffff81908375)
Location: include/linux/scatterlist.h:237
Inline: True
Inline callers:
  - net/core/skmsg.c:sk_psock_msg_verdict
  - net/core/skmsg.c:sk_msg_memcopy_from_iter
  - net/core/skmsg.c:sk_msg_clone
  - net/core/skmsg.c:sk_msg_clone
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
In arch/x86/kernel/pci-calgary_64.c (ffffffff8106b43d)
Location: include/linux/scatterlist.h:237
Inline: True
Inline callers:
  - arch/x86/kernel/pci-calgary_64.c:calgary_map_sg
```
```
In kernel/dma/virt.c (ffffffff8111a8aa)
Location: include/linux/scatterlist.h:237
Inline: True
```
```
In drivers/usb/core/message.c (ffffffff8179c50e)
Location: include/linux/scatterlist.h:237
Inline: True
Inline callers:
  - drivers/usb/core/message.c:usb_sg_init
```
```
In drivers/usb/core/devio.c (ffffffff817a61be)
Location: include/linux/scatterlist.h:237
Inline: True
Inline callers:
  - drivers/usb/core/devio.c:copy_urb_data_to_user
  - drivers/usb/core/devio.c:snoop_urb_data
  - drivers/usb/core/devio.c:free_async
```
```
In net/core/filter.c (ffffffff818b78f3)
Location: include/linux/scatterlist.h:237
Inline: True
Inline callers:
  - net/core/filter.c:bpf_msg_pop_data
  - net/core/filter.c:bpf_msg_pop_data
  - net/core/filter.c:bpf_msg_push_data
  - net/core/filter.c:bpf_msg_push_data
  - net/core/filter.c:bpf_msg_pull_data
  - net/core/filter.c:bpf_msg_pull_data
```
```
In net/core/skmsg.c (ffffffff818c2185)
Location: include/linux/scatterlist.h:237
Inline: True
Inline callers:
  - net/core/skmsg.c:sk_psock_msg_verdict
  - net/core/skmsg.c:sk_msg_memcopy_from_iter
  - net/core/skmsg.c:sk_msg_clone
  - net/core/skmsg.c:sk_msg_clone
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
In arch/x86/kernel/pci-calgary_64.c (ffffffff8107bcbd)
Location: include/linux/scatterlist.h:237
Inline: True
Inline callers:
  - arch/x86/kernel/pci-calgary_64.c:calgary_map_sg
```
```
In kernel/dma/virt.c (ffffffff81125d3a)
Location: include/linux/scatterlist.h:237
Inline: True
```
```
In drivers/usb/core/message.c (ffffffff817e75ae)
Location: include/linux/scatterlist.h:237
Inline: True
Inline callers:
  - drivers/usb/core/message.c:usb_sg_init
```
```
In drivers/usb/core/devio.c (ffffffff817f122e)
Location: include/linux/scatterlist.h:237
Inline: True
Inline callers:
  - drivers/usb/core/devio.c:copy_urb_data_to_user
  - drivers/usb/core/devio.c:snoop_urb_data
  - drivers/usb/core/devio.c:free_async
```
```
In net/core/filter.c (ffffffff8194eaf3)
Location: include/linux/scatterlist.h:237
Inline: True
Inline callers:
  - net/core/filter.c:bpf_msg_pop_data
  - net/core/filter.c:bpf_msg_pop_data
  - net/core/filter.c:bpf_msg_push_data
  - net/core/filter.c:bpf_msg_push_data
  - net/core/filter.c:bpf_msg_pull_data
  - net/core/filter.c:bpf_msg_pull_data
```
```
In net/core/skmsg.c (ffffffff819593a5)
Location: include/linux/scatterlist.h:237
Inline: True
Inline callers:
  - net/core/skmsg.c:sk_psock_msg_verdict
  - net/core/skmsg.c:sk_msg_memcopy_from_iter
  - net/core/skmsg.c:sk_msg_clone
  - net/core/skmsg.c:sk_msg_clone
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
In arch/x86/kernel/pci-calgary_64.c (ffffffff8107ddbd)
Location: include/linux/scatterlist.h:237
Inline: True
Inline callers:
  - arch/x86/kernel/pci-calgary_64.c:calgary_map_sg
```
```
In kernel/dma/virt.c (ffffffff8113237a)
Location: include/linux/scatterlist.h:237
Inline: True
```
```
In drivers/usb/core/message.c (ffffffff818017fe)
Location: include/linux/scatterlist.h:237
Inline: True
Inline callers:
  - drivers/usb/core/message.c:usb_sg_init
```
```
In drivers/usb/core/devio.c (ffffffff8180b46e)
Location: include/linux/scatterlist.h:237
Inline: True
Inline callers:
  - drivers/usb/core/devio.c:copy_urb_data_to_user
  - drivers/usb/core/devio.c:snoop_urb_data
  - drivers/usb/core/devio.c:free_async
```
```
In net/core/filter.c (ffffffff819704c3)
Location: include/linux/scatterlist.h:237
Inline: True
Inline callers:
  - net/core/filter.c:bpf_msg_pop_data
  - net/core/filter.c:bpf_msg_pop_data
  - net/core/filter.c:bpf_msg_push_data
  - net/core/filter.c:bpf_msg_push_data
  - net/core/filter.c:bpf_msg_pull_data
  - net/core/filter.c:bpf_msg_pull_data
```
```
In net/core/skmsg.c (ffffffff8197b4c5)
Location: include/linux/scatterlist.h:237
Inline: True
Inline callers:
  - net/core/skmsg.c:sk_psock_msg_verdict
  - net/core/skmsg.c:sk_msg_memcopy_from_iter
  - net/core/skmsg.c:sk_msg_clone
  - net/core/skmsg.c:sk_msg_clone
```
</details>
</li>
</ul>

## Differences
