# Function: <code>netif_tx_napi_add</code>

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
<details>
<summary>In <code>5.4</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/net/tun.c (ffffffff817c3a8a)
Location: include/linux/netdevice.h:2236
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_attach
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
In drivers/net/tun.c (ffffffff8188f47c)
Location: include/linux/netdevice.h:2321
Inline: True
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
In drivers/net/tun.c (ffffffff8189d7fe)
Location: include/linux/netdevice.h:2408
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
In drivers/net/tun.c (ffffffff81880051)
Location: include/linux/netdevice.h:2472
Inline: True
```
```
In net/mptcp/protocol.c (ffffffff8322aad3)
Location: include/linux/netdevice.h:2472
Inline: True
Inline callers:
  - net/mptcp/protocol.c:mptcp_proto_init
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
In drivers/net/tun.c (ffffffff81911900)
Location: include/linux/netdevice.h:2492
Inline: True
```
```
In net/mptcp/protocol.c (ffffffff83315215)
Location: include/linux/netdevice.h:2492
Inline: True
Inline callers:
  - net/mptcp/protocol.c:mptcp_proto_init
```
</details>
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
<summary>In <code>arm64</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/net/tun.c (ffff8000109de624)
Location: include/linux/netdevice.h:2236
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
In drivers/net/tun.c (c0ac357c)
Location: include/linux/netdevice.h:2236
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_attach
```
```
In drivers/net/ethernet/ti/cpsw.c (c0ad5778)
Location: include/linux/netdevice.h:2236
Inline: True
Inline callers:
  - drivers/net/ethernet/ti/cpsw.c:cpsw_probe
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
In drivers/net/tun.c (c000000000a9f794)
Location: include/linux/netdevice.h:2236
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_attach
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
In drivers/net/tun.c (ffffffe000628ea2)
Location: include/linux/netdevice.h:2236
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_attach
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
In drivers/net/tun.c (ffffffff8178856a)
Location: include/linux/netdevice.h:2236
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_attach
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
In drivers/net/tun.c (ffffffff81767eba)
Location: include/linux/netdevice.h:2236
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_attach
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
In drivers/net/tun.c (ffffffff817b890a)
Location: include/linux/netdevice.h:2236
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_attach
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
In drivers/net/tun.c (ffffffff817d184a)
Location: include/linux/netdevice.h:2236
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_attach
```
</details>
</li>
</ul>

## Differences
