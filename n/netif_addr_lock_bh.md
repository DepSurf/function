# Function: <code>netif_addr_lock_bh</code>

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
In net/core/dev.c (ffffffff8171d9ec)
Location: include/linux/netdevice.h:3423
Inline: True
Inline callers:
  - net/core/dev.c:dev_set_rx_mode
```
```
In net/core/dev_addr_lists.c (ffffffff8172283b)
Location: include/linux/netdevice.h:3423
Inline: True
Inline callers:
  - net/core/dev_addr_lists.c:dev_uc_flush
  - net/core/dev_addr_lists.c:dev_mc_flush
  - net/core/dev_addr_lists.c:dev_uc_add_excl
  - net/core/dev_addr_lists.c:dev_uc_add
  - net/core/dev_addr_lists.c:dev_mc_add_excl
  - net/core/dev_addr_lists.c:__dev_mc_add
  - net/core/dev_addr_lists.c:dev_uc_del
  - net/core/dev_addr_lists.c:__dev_mc_del
```
```
In net/core/rtnetlink.c (ffffffff8172d8bf)
Location: include/linux/netdevice.h:3423
Inline: True
Inline callers:
  - net/core/rtnetlink.c:ndo_dflt_fdb_dump
```
```
In net/core/net-procfs.c (ffffffff81737970)
Location: include/linux/netdevice.h:3423
Inline: True
Inline callers:
  - net/core/net-procfs.c:dev_mc_seq_show
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
In net/core/dev.c (ffffffff817862bc)
Location: include/linux/netdevice.h:3659
Inline: True
Inline callers:
  - net/core/dev.c:dev_set_rx_mode
```
```
In net/core/dev_addr_lists.c (ffffffff8178c2cb)
Location: include/linux/netdevice.h:3659
Inline: True
Inline callers:
  - net/core/dev_addr_lists.c:dev_mc_flush
  - net/core/dev_addr_lists.c:__dev_mc_del
  - net/core/dev_addr_lists.c:__dev_mc_add
  - net/core/dev_addr_lists.c:dev_mc_add_excl
  - net/core/dev_addr_lists.c:dev_uc_flush
  - net/core/dev_addr_lists.c:dev_uc_del
  - net/core/dev_addr_lists.c:dev_uc_add
  - net/core/dev_addr_lists.c:dev_uc_add_excl
```
```
In net/core/rtnetlink.c (ffffffff8179713d)
Location: include/linux/netdevice.h:3659
Inline: True
Inline callers:
  - net/core/rtnetlink.c:ndo_dflt_fdb_dump
```
```
In net/core/net-procfs.c (ffffffff817a3c20)
Location: include/linux/netdevice.h:3659
Inline: True
Inline callers:
  - net/core/net-procfs.c:dev_mc_seq_show
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
In net/core/dev.c (ffffffff817b387c)
Location: include/linux/netdevice.h:3628
Inline: True
Inline callers:
  - net/core/dev.c:dev_set_rx_mode
```
```
In net/core/dev_addr_lists.c (ffffffff817b9b9b)
Location: include/linux/netdevice.h:3628
Inline: True
Inline callers:
  - net/core/dev_addr_lists.c:dev_mc_flush
  - net/core/dev_addr_lists.c:__dev_mc_del
  - net/core/dev_addr_lists.c:__dev_mc_add
  - net/core/dev_addr_lists.c:dev_mc_add_excl
  - net/core/dev_addr_lists.c:dev_uc_flush
  - net/core/dev_addr_lists.c:dev_uc_del
  - net/core/dev_addr_lists.c:dev_uc_add
  - net/core/dev_addr_lists.c:dev_uc_add_excl
```
```
In net/core/rtnetlink.c (ffffffff817c4321)
Location: include/linux/netdevice.h:3628
Inline: True
Inline callers:
  - net/core/rtnetlink.c:ndo_dflt_fdb_dump
```
```
In net/core/net-procfs.c (ffffffff817d26b0)
Location: include/linux/netdevice.h:3628
Inline: True
Inline callers:
  - net/core/net-procfs.c:dev_mc_seq_show
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
In net/core/dev.c (ffffffff817d21fc)
Location: include/linux/netdevice.h:3674
Inline: True
Inline callers:
  - net/core/dev.c:dev_set_rx_mode
```
```
In net/core/dev_addr_lists.c (ffffffff817d86eb)
Location: include/linux/netdevice.h:3674
Inline: True
Inline callers:
  - net/core/dev_addr_lists.c:dev_mc_flush
  - net/core/dev_addr_lists.c:__dev_mc_del
  - net/core/dev_addr_lists.c:__dev_mc_add
  - net/core/dev_addr_lists.c:dev_mc_add_excl
  - net/core/dev_addr_lists.c:dev_uc_flush
  - net/core/dev_addr_lists.c:dev_uc_del
  - net/core/dev_addr_lists.c:dev_uc_add
  - net/core/dev_addr_lists.c:dev_uc_add_excl
```
```
In net/core/rtnetlink.c (ffffffff817e2691)
Location: include/linux/netdevice.h:3674
Inline: True
Inline callers:
  - net/core/rtnetlink.c:ndo_dflt_fdb_dump
```
```
In net/core/net-procfs.c (ffffffff817f1d10)
Location: include/linux/netdevice.h:3674
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
In net/core/dev.c (ffffffff8184c48c)
Location: include/linux/netdevice.h:3703
Inline: True
Inline callers:
  - net/core/dev.c:dev_set_rx_mode
```
```
In net/core/dev_addr_lists.c (ffffffff81852deb)
Location: include/linux/netdevice.h:3703
Inline: True
Inline callers:
  - net/core/dev_addr_lists.c:dev_mc_flush
  - net/core/dev_addr_lists.c:__dev_mc_del
  - net/core/dev_addr_lists.c:__dev_mc_add
  - net/core/dev_addr_lists.c:dev_mc_add_excl
  - net/core/dev_addr_lists.c:dev_uc_flush
  - net/core/dev_addr_lists.c:dev_uc_del
  - net/core/dev_addr_lists.c:dev_uc_add
  - net/core/dev_addr_lists.c:dev_uc_add_excl
```
```
In net/core/rtnetlink.c (ffffffff8185d551)
Location: include/linux/netdevice.h:3703
Inline: True
Inline callers:
  - net/core/rtnetlink.c:ndo_dflt_fdb_dump
```
```
In net/core/net-procfs.c (ffffffff8186d2d0)
Location: include/linux/netdevice.h:3703
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
In net/core/dev.c (ffffffff818966d5)
Location: include/linux/netdevice.h:3809
Inline: True
Inline callers:
  - net/core/dev.c:dev_set_rx_mode
```
```
In net/core/dev_addr_lists.c (ffffffff8189e4f5)
Location: include/linux/netdevice.h:3809
Inline: True
Inline callers:
  - net/core/dev_addr_lists.c:dev_mc_flush
  - net/core/dev_addr_lists.c:__dev_mc_del
  - net/core/dev_addr_lists.c:__dev_mc_add
  - net/core/dev_addr_lists.c:dev_mc_add_excl
  - net/core/dev_addr_lists.c:dev_uc_flush
  - net/core/dev_addr_lists.c:dev_uc_del
  - net/core/dev_addr_lists.c:dev_uc_add
  - net/core/dev_addr_lists.c:dev_uc_add_excl
```
```
In net/core/rtnetlink.c (ffffffff818a90c5)
Location: include/linux/netdevice.h:3809
Inline: True
Inline callers:
  - net/core/rtnetlink.c:ndo_dflt_fdb_dump
```
```
In net/core/net-procfs.c (ffffffff818be526)
Location: include/linux/netdevice.h:3809
Inline: True
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
In net/core/dev.c (ffffffff818b8945)
Location: include/linux/netdevice.h:4035
Inline: True
Inline callers:
  - net/core/dev.c:dev_set_rx_mode
```
```
In net/core/dev_addr_lists.c (ffffffff818c0d15)
Location: include/linux/netdevice.h:4035
Inline: True
Inline callers:
  - net/core/dev_addr_lists.c:dev_mc_flush
  - net/core/dev_addr_lists.c:__dev_mc_del
  - net/core/dev_addr_lists.c:__dev_mc_add
  - net/core/dev_addr_lists.c:dev_mc_add_excl
  - net/core/dev_addr_lists.c:dev_uc_flush
  - net/core/dev_addr_lists.c:dev_uc_del
  - net/core/dev_addr_lists.c:dev_uc_add
  - net/core/dev_addr_lists.c:dev_uc_add_excl
```
```
In net/core/rtnetlink.c (ffffffff818cd74b)
Location: include/linux/netdevice.h:4035
Inline: True
Inline callers:
  - net/core/rtnetlink.c:ndo_dflt_fdb_dump
```
```
In net/core/net-procfs.c (ffffffff818e59a6)
Location: include/linux/netdevice.h:4035
Inline: True
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
In net/core/dev.c (ffffffff81904b05)
Location: include/linux/netdevice.h:4056
Inline: True
Inline callers:
  - net/core/dev.c:dev_set_rx_mode
```
```
In net/core/dev_addr_lists.c (ffffffff8190d425)
Location: include/linux/netdevice.h:4056
Inline: True
Inline callers:
  - net/core/dev_addr_lists.c:dev_mc_flush
  - net/core/dev_addr_lists.c:__dev_mc_del
  - net/core/dev_addr_lists.c:__dev_mc_add
  - net/core/dev_addr_lists.c:dev_mc_add_excl
  - net/core/dev_addr_lists.c:dev_uc_flush
  - net/core/dev_addr_lists.c:dev_uc_del
  - net/core/dev_addr_lists.c:dev_uc_add
  - net/core/dev_addr_lists.c:dev_uc_add_excl
```
```
In net/core/rtnetlink.c (ffffffff8191a42d)
Location: include/linux/netdevice.h:4056
Inline: True
Inline callers:
  - net/core/rtnetlink.c:ndo_dflt_fdb_dump
```
```
In net/core/net-procfs.c (ffffffff8193520b)
Location: include/linux/netdevice.h:4056
Inline: True
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
In net/core/dev.c (ffffffff81937175)
Location: include/linux/netdevice.h:4062
Inline: True
Inline callers:
  - net/core/dev.c:dev_set_rx_mode
```
```
In net/core/dev_addr_lists.c (ffffffff8193fb25)
Location: include/linux/netdevice.h:4062
Inline: True
Inline callers:
  - net/core/dev_addr_lists.c:dev_mc_flush
  - net/core/dev_addr_lists.c:__dev_mc_del
  - net/core/dev_addr_lists.c:__dev_mc_add
  - net/core/dev_addr_lists.c:dev_mc_add_excl
  - net/core/dev_addr_lists.c:dev_uc_flush
  - net/core/dev_addr_lists.c:dev_uc_del
  - net/core/dev_addr_lists.c:dev_uc_add
  - net/core/dev_addr_lists.c:dev_uc_add_excl
```
```
In net/core/rtnetlink.c (ffffffff8194ca4d)
Location: include/linux/netdevice.h:4062
Inline: True
Inline callers:
  - net/core/rtnetlink.c:ndo_dflt_fdb_dump
```
```
In net/core/net-procfs.c (ffffffff81967fcb)
Location: include/linux/netdevice.h:4062
Inline: True
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
In net/core/dev.c (ffffffff81a0c21f)
Location: include/linux/netdevice.h:4246
Inline: True
Inline callers:
  - net/core/dev.c:__dev_change_flags
  - net/core/dev.c:__dev_change_flags
  - net/core/dev.c:__dev_set_allmulti
  - net/core/dev.c:dev_set_promiscuity
  - net/core/dev.c:__dev_open
```
```
In net/core/dev_addr_lists.c (ffffffff81a10225)
Location: include/linux/netdevice.h:4246
Inline: True
Inline callers:
  - net/core/dev_addr_lists.c:dev_mc_flush
  - net/core/dev_addr_lists.c:dev_mc_del_global
  - net/core/dev_addr_lists.c:dev_mc_del
  - net/core/dev_addr_lists.c:dev_mc_add_global
  - net/core/dev_addr_lists.c:dev_mc_add
  - net/core/dev_addr_lists.c:dev_mc_add_excl
  - net/core/dev_addr_lists.c:dev_uc_flush
  - net/core/dev_addr_lists.c:dev_uc_del
  - net/core/dev_addr_lists.c:dev_uc_add
  - net/core/dev_addr_lists.c:dev_uc_add_excl
```
```
In net/core/rtnetlink.c (ffffffff81a1e67d)
Location: include/linux/netdevice.h:4246
Inline: True
Inline callers:
  - net/core/rtnetlink.c:ndo_dflt_fdb_dump
```
```
In net/core/net-procfs.c (ffffffff81a3b7ab)
Location: include/linux/netdevice.h:4246
Inline: True
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
In net/core/dev.c (ffffffff81a0d8ee)
Location: include/linux/netdevice.h:4416
Inline: True
Inline callers:
  - net/core/dev.c:__dev_change_flags
  - net/core/dev.c:__dev_change_flags
  - net/core/dev.c:__dev_set_allmulti
  - net/core/dev.c:dev_set_promiscuity
  - net/core/dev.c:__dev_open
```
```
In net/core/dev_addr_lists.c (ffffffff81a105e5)
Location: include/linux/netdevice.h:4416
Inline: True
Inline callers:
  - net/core/dev_addr_lists.c:dev_mc_flush
  - net/core/dev_addr_lists.c:dev_mc_del_global
  - net/core/dev_addr_lists.c:dev_mc_del
  - net/core/dev_addr_lists.c:__dev_mc_add
  - net/core/dev_addr_lists.c:dev_mc_add_excl
  - net/core/dev_addr_lists.c:dev_uc_flush
  - net/core/dev_addr_lists.c:dev_uc_del
  - net/core/dev_addr_lists.c:dev_uc_add
  - net/core/dev_addr_lists.c:dev_uc_add_excl
```
```
In net/core/rtnetlink.c (ffffffff81a1e9b0)
Location: include/linux/netdevice.h:4416
Inline: True
Inline callers:
  - net/core/rtnetlink.c:ndo_dflt_fdb_dump
```
```
In net/core/net-procfs.c (ffffffff81a3de97)
Location: include/linux/netdevice.h:4416
Inline: True
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
In net/core/dev.c (ffffffff819f458b)
Location: include/linux/netdevice.h:4546
Inline: True
Inline callers:
  - net/core/dev.c:__dev_change_flags
  - net/core/dev.c:__dev_change_flags
  - net/core/dev.c:__dev_set_allmulti
  - net/core/dev.c:dev_set_promiscuity
  - net/core/dev.c:__dev_open
```
```
In net/core/dev_addr_lists.c (ffffffff819f7455)
Location: include/linux/netdevice.h:4546
Inline: True
Inline callers:
  - net/core/dev_addr_lists.c:dev_mc_flush
  - net/core/dev_addr_lists.c:dev_mc_del_global
  - net/core/dev_addr_lists.c:dev_mc_del
  - net/core/dev_addr_lists.c:__dev_mc_add
  - net/core/dev_addr_lists.c:dev_mc_add_excl
  - net/core/dev_addr_lists.c:dev_uc_flush
  - net/core/dev_addr_lists.c:dev_uc_del
  - net/core/dev_addr_lists.c:dev_uc_add
  - net/core/dev_addr_lists.c:dev_uc_add_excl
```
```
In net/core/rtnetlink.c (ffffffff81a057b0)
Location: include/linux/netdevice.h:4546
Inline: True
Inline callers:
  - net/core/rtnetlink.c:ndo_dflt_fdb_dump
```
```
In net/core/net-procfs.c (ffffffff81a24f67)
Location: include/linux/netdevice.h:4546
Inline: True
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
In net/core/dev.c (ffffffff81aa5eab)
Location: include/linux/netdevice.h:4576
Inline: True
Inline callers:
  - net/core/dev.c:__dev_change_flags
  - net/core/dev.c:__dev_change_flags
  - net/core/dev.c:__dev_set_allmulti
  - net/core/dev.c:dev_set_promiscuity
  - net/core/dev.c:__dev_open
```
```
In net/core/dev_addr_lists.c (ffffffff81aa90c5)
Location: include/linux/netdevice.h:4576
Inline: True
Inline callers:
  - net/core/dev_addr_lists.c:dev_mc_flush
  - net/core/dev_addr_lists.c:dev_mc_del_global
  - net/core/dev_addr_lists.c:dev_mc_del
  - net/core/dev_addr_lists.c:__dev_mc_add
  - net/core/dev_addr_lists.c:dev_mc_add_excl
  - net/core/dev_addr_lists.c:dev_uc_flush
  - net/core/dev_addr_lists.c:dev_uc_del
  - net/core/dev_addr_lists.c:dev_uc_add
  - net/core/dev_addr_lists.c:dev_uc_add_excl
```
```
In net/core/rtnetlink.c (ffffffff81ab7bf0)
Location: include/linux/netdevice.h:4576
Inline: True
Inline callers:
  - net/core/rtnetlink.c:ndo_dflt_fdb_dump
```
```
In net/core/net-procfs.c (ffffffff81ad9a9c)
Location: include/linux/netdevice.h:4576
Inline: True
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
In net/core/dev.c (ffffffff81c1d95d)
Location: include/linux/netdevice.h:4415
Inline: True
Inline callers:
  - net/core/dev.c:__dev_change_flags
  - net/core/dev.c:__dev_change_flags
  - net/core/dev.c:__dev_set_allmulti
  - net/core/dev.c:dev_set_promiscuity
  - net/core/dev.c:__dev_open
```
```
In net/core/dev_addr_lists.c (ffffffff81c21275)
Location: include/linux/netdevice.h:4415
Inline: True
Inline callers:
  - net/core/dev_addr_lists.c:dev_mc_flush
  - net/core/dev_addr_lists.c:dev_mc_del_global
  - net/core/dev_addr_lists.c:dev_mc_del
  - net/core/dev_addr_lists.c:__dev_mc_add
  - net/core/dev_addr_lists.c:dev_mc_add_excl
  - net/core/dev_addr_lists.c:dev_uc_flush
  - net/core/dev_addr_lists.c:dev_uc_del
  - net/core/dev_addr_lists.c:dev_uc_add
  - net/core/dev_addr_lists.c:dev_uc_add_excl
```
```
In net/core/rtnetlink.c (ffffffff81c317fe)
Location: include/linux/netdevice.h:4415
Inline: True
Inline callers:
  - net/core/rtnetlink.c:ndo_dflt_fdb_dump
```
```
In net/core/net-procfs.c (ffffffff81c5aecc)
Location: include/linux/netdevice.h:4415
Inline: True
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
In net/core/dev.c (ffffffff81dcec4d)
Location: include/linux/netdevice.h:4459
Inline: True
Inline callers:
  - net/core/dev.c:__dev_change_flags
  - net/core/dev.c:__dev_change_flags
  - net/core/dev.c:__dev_set_allmulti
  - net/core/dev.c:dev_set_promiscuity
  - net/core/dev.c:__dev_open
```
```
In net/core/dev_addr_lists.c (ffffffff81dd3345)
Location: include/linux/netdevice.h:4459
Inline: True
Inline callers:
  - net/core/dev_addr_lists.c:dev_mc_flush
  - net/core/dev_addr_lists.c:dev_mc_del_global
  - net/core/dev_addr_lists.c:dev_mc_del
  - net/core/dev_addr_lists.c:__dev_mc_add
  - net/core/dev_addr_lists.c:dev_mc_add_excl
  - net/core/dev_addr_lists.c:dev_uc_flush
  - net/core/dev_addr_lists.c:dev_uc_del
  - net/core/dev_addr_lists.c:dev_uc_add
  - net/core/dev_addr_lists.c:dev_uc_add_excl
```
```
In net/core/rtnetlink.c (ffffffff81de4b9e)
Location: include/linux/netdevice.h:4459
Inline: True
Inline callers:
  - net/core/rtnetlink.c:ndo_dflt_fdb_dump
```
```
In net/core/net-procfs.c (ffffffff81e1111c)
Location: include/linux/netdevice.h:4459
Inline: True
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
In drivers/net/net_failover.c (ffffffff81c6fb3e)
Location: include/linux/netdevice.h:4518
Inline: True
Inline callers:
  - drivers/net/net_failover.c:net_failover_slave_register
```
```
In net/core/dev.c (ffffffff81e3f87d)
Location: include/linux/netdevice.h:4518
Inline: True
Inline callers:
  - net/core/dev.c:__dev_change_flags
  - net/core/dev.c:__dev_change_flags
  - net/core/dev.c:__dev_set_allmulti
  - net/core/dev.c:dev_set_promiscuity
  - net/core/dev.c:__dev_open
```
```
In net/core/dev_addr_lists.c (ffffffff81e43f15)
Location: include/linux/netdevice.h:4518
Inline: True
Inline callers:
  - net/core/dev_addr_lists.c:dev_mc_flush
  - net/core/dev_addr_lists.c:dev_mc_del_global
  - net/core/dev_addr_lists.c:dev_mc_del
  - net/core/dev_addr_lists.c:__dev_mc_add
  - net/core/dev_addr_lists.c:dev_mc_add_excl
  - net/core/dev_addr_lists.c:dev_uc_flush
  - net/core/dev_addr_lists.c:dev_uc_del
  - net/core/dev_addr_lists.c:dev_uc_add
  - net/core/dev_addr_lists.c:dev_uc_add_excl
```
```
In net/core/rtnetlink.c (ffffffff81e565ae)
Location: include/linux/netdevice.h:4518
Inline: True
Inline callers:
  - net/core/rtnetlink.c:ndo_dflt_fdb_dump
```
```
In net/core/net-procfs.c (ffffffff81e84a2c)
Location: include/linux/netdevice.h:4518
Inline: True
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
In drivers/net/net_failover.c (ffffffff81d243eb)
Location: include/linux/netdevice.h:4594
Inline: True
Inline callers:
  - drivers/net/net_failover.c:net_failover_slave_register
```
```
In net/core/dev.c (ffffffff81efe1d3)
Location: include/linux/netdevice.h:4594
Inline: True
Inline callers:
  - net/core/dev.c:__dev_change_flags
  - net/core/dev.c:__dev_change_flags
  - net/core/dev.c:__dev_set_allmulti
  - net/core/dev.c:dev_set_promiscuity
  - net/core/dev.c:__dev_open
```
```
In net/core/dev_addr_lists.c (ffffffff81f02b65)
Location: include/linux/netdevice.h:4594
Inline: True
Inline callers:
  - net/core/dev_addr_lists.c:dev_mc_flush
  - net/core/dev_addr_lists.c:dev_mc_del_global
  - net/core/dev_addr_lists.c:dev_mc_del
  - net/core/dev_addr_lists.c:__dev_mc_add
  - net/core/dev_addr_lists.c:dev_mc_add_excl
  - net/core/dev_addr_lists.c:dev_uc_flush
  - net/core/dev_addr_lists.c:dev_uc_del
  - net/core/dev_addr_lists.c:dev_uc_add
  - net/core/dev_addr_lists.c:dev_uc_add_excl
```
```
In net/core/rtnetlink.c (ffffffff81f1590e)
Location: include/linux/netdevice.h:4594
Inline: True
Inline callers:
  - net/core/rtnetlink.c:ndo_dflt_fdb_dump
```
```
In net/core/net-procfs.c (ffffffff81f469f1)
Location: include/linux/netdevice.h:4594
Inline: True
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
In net/core/dev.c (ffff800010bd5ab4)
Location: include/linux/netdevice.h:4062
Inline: True
Inline callers:
  - net/core/dev.c:dev_set_rx_mode
```
```
In net/core/dev_addr_lists.c (ffff800010bdf6b4)
Location: include/linux/netdevice.h:4062
Inline: True
Inline callers:
  - net/core/dev_addr_lists.c:dev_mc_flush
  - net/core/dev_addr_lists.c:__dev_mc_del
  - net/core/dev_addr_lists.c:__dev_mc_add
  - net/core/dev_addr_lists.c:dev_mc_add_excl
  - net/core/dev_addr_lists.c:dev_uc_flush
  - net/core/dev_addr_lists.c:dev_uc_del
  - net/core/dev_addr_lists.c:dev_uc_add
  - net/core/dev_addr_lists.c:dev_uc_add_excl
```
```
In net/core/rtnetlink.c (ffff800010beebec)
Location: include/linux/netdevice.h:4062
Inline: True
Inline callers:
  - net/core/rtnetlink.c:ndo_dflt_fdb_dump
```
```
In net/core/net-procfs.c (ffff800010c0dfe0)
Location: include/linux/netdevice.h:4062
Inline: True
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
In net/core/dev.c (c0cf0714)
Location: include/linux/netdevice.h:4062
Inline: True
Inline callers:
  - net/core/dev.c:dev_set_rx_mode
```
```
In net/core/dev_addr_lists.c (c0cf9814)
Location: include/linux/netdevice.h:4062
Inline: True
Inline callers:
  - net/core/dev_addr_lists.c:dev_mc_flush
  - net/core/dev_addr_lists.c:__dev_mc_del
  - net/core/dev_addr_lists.c:__dev_mc_add
  - net/core/dev_addr_lists.c:dev_mc_add_excl
  - net/core/dev_addr_lists.c:dev_uc_flush
  - net/core/dev_addr_lists.c:dev_uc_del
  - net/core/dev_addr_lists.c:dev_uc_add
  - net/core/dev_addr_lists.c:dev_uc_add_excl
```
```
In net/core/rtnetlink.c (c0d07094)
Location: include/linux/netdevice.h:4062
Inline: True
Inline callers:
  - net/core/rtnetlink.c:ndo_dflt_fdb_dump
```
```
In net/core/net-procfs.c (c0d25eb8)
Location: include/linux/netdevice.h:4062
Inline: True
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
In net/core/dev.c (c000000000cb51a4)
Location: include/linux/netdevice.h:4062
Inline: True
Inline callers:
  - net/core/dev.c:dev_set_rx_mode
```
```
In net/core/dev_addr_lists.c (c000000000cbf5f4)
Location: include/linux/netdevice.h:4062
Inline: True
Inline callers:
  - net/core/dev_addr_lists.c:dev_mc_flush
  - net/core/dev_addr_lists.c:__dev_mc_del
  - net/core/dev_addr_lists.c:__dev_mc_add
  - net/core/dev_addr_lists.c:dev_mc_add_excl
  - net/core/dev_addr_lists.c:dev_uc_flush
  - net/core/dev_addr_lists.c:dev_uc_del
  - net/core/dev_addr_lists.c:dev_uc_add
  - net/core/dev_addr_lists.c:dev_uc_add_excl
```
```
In net/core/rtnetlink.c (c000000000cd2944)
Location: include/linux/netdevice.h:4062
Inline: True
Inline callers:
  - net/core/rtnetlink.c:ndo_dflt_fdb_dump
```
```
In net/core/net-procfs.c (c000000000cf9628)
Location: include/linux/netdevice.h:4062
Inline: True
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
In net/core/dev.c (ffffffe00075f3f8)
Location: include/linux/netdevice.h:4062
Inline: True
Inline callers:
  - net/core/dev.c:dev_set_rx_mode
```
```
In net/core/dev_addr_lists.c (ffffffe000765a98)
Location: include/linux/netdevice.h:4062
Inline: True
Inline callers:
  - net/core/dev_addr_lists.c:dev_mc_flush
  - net/core/dev_addr_lists.c:__dev_mc_del
  - net/core/dev_addr_lists.c:__dev_mc_add
  - net/core/dev_addr_lists.c:dev_mc_add_excl
  - net/core/dev_addr_lists.c:dev_uc_flush
  - net/core/dev_addr_lists.c:dev_uc_del
  - net/core/dev_addr_lists.c:dev_uc_add
  - net/core/dev_addr_lists.c:dev_uc_add_excl
```
```
In net/core/rtnetlink.c (ffffffe00077128c)
Location: include/linux/netdevice.h:4062
Inline: True
Inline callers:
  - net/core/rtnetlink.c:ndo_dflt_fdb_dump
```
```
In net/core/net-procfs.c (ffffffe00078a97a)
Location: include/linux/netdevice.h:4062
Inline: True
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
In net/core/dev.c (ffffffff818d7145)
Location: include/linux/netdevice.h:4062
Inline: True
Inline callers:
  - net/core/dev.c:dev_set_rx_mode
```
```
In net/core/dev_addr_lists.c (ffffffff818dfaf5)
Location: include/linux/netdevice.h:4062
Inline: True
Inline callers:
  - net/core/dev_addr_lists.c:dev_mc_flush
  - net/core/dev_addr_lists.c:__dev_mc_del
  - net/core/dev_addr_lists.c:__dev_mc_add
  - net/core/dev_addr_lists.c:dev_mc_add_excl
  - net/core/dev_addr_lists.c:dev_uc_flush
  - net/core/dev_addr_lists.c:dev_uc_del
  - net/core/dev_addr_lists.c:dev_uc_add
  - net/core/dev_addr_lists.c:dev_uc_add_excl
```
```
In net/core/rtnetlink.c (ffffffff818eca1d)
Location: include/linux/netdevice.h:4062
Inline: True
Inline callers:
  - net/core/rtnetlink.c:ndo_dflt_fdb_dump
```
```
In net/core/net-procfs.c (ffffffff81907f9b)
Location: include/linux/netdevice.h:4062
Inline: True
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
In net/core/dev.c (ffffffff81890f85)
Location: include/linux/netdevice.h:4062
Inline: True
Inline callers:
  - net/core/dev.c:dev_set_rx_mode
```
```
In net/core/dev_addr_lists.c (ffffffff81899935)
Location: include/linux/netdevice.h:4062
Inline: True
Inline callers:
  - net/core/dev_addr_lists.c:dev_mc_flush
  - net/core/dev_addr_lists.c:__dev_mc_del
  - net/core/dev_addr_lists.c:__dev_mc_add
  - net/core/dev_addr_lists.c:dev_mc_add_excl
  - net/core/dev_addr_lists.c:dev_uc_flush
  - net/core/dev_addr_lists.c:dev_uc_del
  - net/core/dev_addr_lists.c:dev_uc_add
  - net/core/dev_addr_lists.c:dev_uc_add_excl
```
```
In net/core/rtnetlink.c (ffffffff818a685d)
Location: include/linux/netdevice.h:4062
Inline: True
Inline callers:
  - net/core/rtnetlink.c:ndo_dflt_fdb_dump
```
```
In net/core/net-procfs.c (ffffffff818c1dab)
Location: include/linux/netdevice.h:4062
Inline: True
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
In net/core/dev.c (ffffffff81928175)
Location: include/linux/netdevice.h:4062
Inline: True
Inline callers:
  - net/core/dev.c:dev_set_rx_mode
```
```
In net/core/dev_addr_lists.c (ffffffff81930b25)
Location: include/linux/netdevice.h:4062
Inline: True
Inline callers:
  - net/core/dev_addr_lists.c:dev_mc_flush
  - net/core/dev_addr_lists.c:__dev_mc_del
  - net/core/dev_addr_lists.c:__dev_mc_add
  - net/core/dev_addr_lists.c:dev_mc_add_excl
  - net/core/dev_addr_lists.c:dev_uc_flush
  - net/core/dev_addr_lists.c:dev_uc_del
  - net/core/dev_addr_lists.c:dev_uc_add
  - net/core/dev_addr_lists.c:dev_uc_add_excl
```
```
In net/core/rtnetlink.c (ffffffff8193da4d)
Location: include/linux/netdevice.h:4062
Inline: True
Inline callers:
  - net/core/rtnetlink.c:ndo_dflt_fdb_dump
```
```
In net/core/net-procfs.c (ffffffff81958fcb)
Location: include/linux/netdevice.h:4062
Inline: True
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
In net/core/dev.c (ffffffff81949845)
Location: include/linux/netdevice.h:4062
Inline: True
Inline callers:
  - net/core/dev.c:dev_set_rx_mode
```
```
In net/core/dev_addr_lists.c (ffffffff819521f5)
Location: include/linux/netdevice.h:4062
Inline: True
Inline callers:
  - net/core/dev_addr_lists.c:dev_mc_flush
  - net/core/dev_addr_lists.c:__dev_mc_del
  - net/core/dev_addr_lists.c:__dev_mc_add
  - net/core/dev_addr_lists.c:dev_mc_add_excl
  - net/core/dev_addr_lists.c:dev_uc_flush
  - net/core/dev_addr_lists.c:dev_uc_del
  - net/core/dev_addr_lists.c:dev_uc_add
  - net/core/dev_addr_lists.c:dev_uc_add_excl
```
```
In net/core/rtnetlink.c (ffffffff8195f2dd)
Location: include/linux/netdevice.h:4062
Inline: True
Inline callers:
  - net/core/rtnetlink.c:ndo_dflt_fdb_dump
```
```
In net/core/net-procfs.c (ffffffff8197b13b)
Location: include/linux/netdevice.h:4062
Inline: True
```
</details>
</li>
</ul>

## Differences
