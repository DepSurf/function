# Function: <code>netif_tx_lock_bh</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/sched/sch_generic.c (ffffffff81741c3e)
Location: include/linux/netdevice.h:3345
Inline: True
Inline callers:
  - net/sched/sch_generic.c:dev_deactivate_many
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/sched/sch_generic.c (ffffffff817aeaee)
Location: include/linux/netdevice.h:3581
Inline: True
Inline callers:
  - net/sched/sch_generic.c:dev_deactivate_many
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/sched/sch_generic.c (ffffffff817de16e)
Location: include/linux/netdevice.h:3546
Inline: True
Inline callers:
  - net/sched/sch_generic.c:dev_deactivate_many
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/sched/sch_generic.c (ffffffff817fd7be)
Location: include/linux/netdevice.h:3592
Inline: True
Inline callers:
  - net/sched/sch_generic.c:dev_deactivate_many
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/sched/sch_generic.c (ffffffff8187b3aa)
Location: include/linux/netdevice.h:3621
Inline: True
Inline callers:
  - net/sched/sch_generic.c:dev_deactivate_many
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/sched/sch_generic.c (ffffffff818cd85a)
Location: include/linux/netdevice.h:3727
Inline: True
Inline callers:
  - net/sched/sch_generic.c:dev_deactivate_many
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/sched/sch_generic.c (ffffffff818f8a9a)
Location: include/linux/netdevice.h:3953
Inline: True
Inline callers:
  - net/sched/sch_generic.c:dev_deactivate_many
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/sched/sch_generic.c (ffffffff8195826a)
Location: include/linux/netdevice.h:3974
Inline: True
Inline callers:
  - net/sched/sch_generic.c:dev_deactivate_many
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/sched/sch_generic.c (ffffffff8198e71a)
Location: include/linux/netdevice.h:3990
Inline: True
Inline callers:
  - net/sched/sch_generic.c:dev_deactivate_many
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/sched/sch_generic.c (ffffffff81a664ce)
Location: include/linux/netdevice.h:4169
Inline: True
Inline callers:
  - net/sched/sch_generic.c:dev_deactivate_many
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/sched/sch_generic.c (ffffffff81a6e5ae)
Location: include/linux/netdevice.h:4337
Inline: True
Inline callers:
  - net/sched/sch_generic.c:dev_deactivate_many
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/sched/sch_generic.c (ffffffff81a56e3e)
Location: include/linux/netdevice.h:4467
Inline: True
Inline callers:
  - net/sched/sch_generic.c:dev_deactivate_many
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
In drivers/net/xen-netfront.c (ffffffff8191f33b)
Location: include/linux/netdevice.h:4497
Inline: True
Inline callers:
  - drivers/net/xen-netfront.c:xennet_connect
  - drivers/net/xen-netfront.c:netfront_resume
```
```
In net/sched/sch_generic.c (ffffffff81b0fc6e)
Location: include/linux/netdevice.h:4497
Inline: True
Inline callers:
  - net/sched/sch_generic.c:dev_deactivate_many
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
In drivers/net/xen-netfront.c (ffffffff81a736bd)
Location: include/linux/netdevice.h:4351
Inline: True
Inline callers:
  - drivers/net/xen-netfront.c:xennet_connect
  - drivers/net/xen-netfront.c:netfront_resume
```
```
In net/sched/sch_generic.c (ffffffff81c96e5d)
Location: include/linux/netdevice.h:4351
Inline: True
Inline callers:
  - net/sched/sch_generic.c:dev_deactivate_many
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
In drivers/net/xen-netfront.c (ffffffff81c0794d)
Location: include/linux/netdevice.h:4395
Inline: True
Inline callers:
  - drivers/net/xen-netfront.c:xennet_connect
  - drivers/net/xen-netfront.c:netfront_resume
```
```
In net/sched/sch_generic.c (ffffffff81e52c3d)
Location: include/linux/netdevice.h:4395
Inline: True
Inline callers:
  - net/sched/sch_generic.c:dev_deactivate_many
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
In drivers/net/virtio_net.c (ffffffff81c54551)
Location: include/linux/netdevice.h:4454
Inline: True
Inline callers:
  - drivers/net/virtio_net.c:virtnet_restore
```
```
In drivers/net/xen-netfront.c (ffffffff81c6d06d)
Location: include/linux/netdevice.h:4454
Inline: True
Inline callers:
  - drivers/net/xen-netfront.c:xennet_connect
  - drivers/net/xen-netfront.c:netfront_resume
```
```
In net/sched/sch_generic.c (ffffffff81eae4db)
Location: include/linux/netdevice.h:4454
Inline: True
Inline callers:
  - net/sched/sch_generic.c:dev_deactivate_many
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
In drivers/net/virtio_net.c (ffffffff81d0abcb)
Location: include/linux/netdevice.h:4530
Inline: True
Inline callers:
  - drivers/net/virtio_net.c:virtnet_restore
```
```
In drivers/net/xen-netfront.c (ffffffff81d219aa)
Location: include/linux/netdevice.h:4530
Inline: True
Inline callers:
  - drivers/net/xen-netfront.c:xennet_connect
  - drivers/net/xen-netfront.c:netfront_resume
```
```
In net/sched/sch_generic.c (ffffffff81f70f52)
Location: include/linux/netdevice.h:4530
Inline: True
Inline callers:
  - net/sched/sch_generic.c:dev_deactivate_many
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
In drivers/net/ethernet/freescale/fec_main.c (ffff8000109ea6ec)
Location: include/linux/netdevice.h:3990
Inline: True
Inline callers:
  - drivers/net/ethernet/freescale/fec_main.c:fec_resume
  - drivers/net/ethernet/freescale/fec_main.c:fec_suspend
  - drivers/net/ethernet/freescale/fec_main.c:fec_enet_set_pauseparam
  - drivers/net/ethernet/freescale/fec_main.c:fec_enet_adjust_link
  - drivers/net/ethernet/freescale/fec_main.c:fec_enet_adjust_link
  - drivers/net/ethernet/freescale/fec_main.c:fec_enet_timeout_work
```
```
In net/sched/sch_generic.c (ffff800010c3a010)
Location: include/linux/netdevice.h:3990
Inline: True
Inline callers:
  - net/sched/sch_generic.c:dev_deactivate_many
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
In drivers/net/ethernet/freescale/fec_main.c (c0accb64)
Location: include/linux/netdevice.h:3990
Inline: True
Inline callers:
  - drivers/net/ethernet/freescale/fec_main.c:fec_resume
  - drivers/net/ethernet/freescale/fec_main.c:fec_suspend
  - drivers/net/ethernet/freescale/fec_main.c:fec_enet_set_pauseparam
  - drivers/net/ethernet/freescale/fec_main.c:fec_enet_adjust_link
  - drivers/net/ethernet/freescale/fec_main.c:fec_enet_adjust_link
  - drivers/net/ethernet/freescale/fec_main.c:fec_enet_timeout_work
```
```
In net/sched/sch_generic.c (c0d4c2ac)
Location: include/linux/netdevice.h:3990
Inline: True
Inline callers:
  - net/sched/sch_generic.c:dev_deactivate_many
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/sched/sch_generic.c (c000000000d33084)
Location: include/linux/netdevice.h:3990
Inline: True
Inline callers:
  - net/sched/sch_generic.c:dev_deactivate_many
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/sched/sch_generic.c (ffffffe0007ab1fe)
Location: include/linux/netdevice.h:3990
Inline: True
Inline callers:
  - net/sched/sch_generic.c:dev_deactivate_many
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/sched/sch_generic.c (ffffffff8192e58a)
Location: include/linux/netdevice.h:3990
Inline: True
Inline callers:
  - net/sched/sch_generic.c:dev_deactivate_many
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/sched/sch_generic.c (ffffffff818e808a)
Location: include/linux/netdevice.h:3990
Inline: True
Inline callers:
  - net/sched/sch_generic.c:dev_deactivate_many
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/sched/sch_generic.c (ffffffff8197f71a)
Location: include/linux/netdevice.h:3990
Inline: True
Inline callers:
  - net/sched/sch_generic.c:dev_deactivate_many
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/sched/sch_generic.c (ffffffff819a1c7a)
Location: include/linux/netdevice.h:3990
Inline: True
Inline callers:
  - net/sched/sch_generic.c:dev_deactivate_many
```
</details>
</li>
</ul>

## Differences
