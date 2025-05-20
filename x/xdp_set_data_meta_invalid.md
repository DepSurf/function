# Function: <code>xdp_set_data_meta_invalid</code>

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
<details>
<summary>In <code>4.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/net/tun.c (ffffffff816ff91a)
Location: include/linux/filter.h:737
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_get_user
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
In drivers/net/tun.c (ffffffff8173d088)
Location: include/net/xdp.h:136
Inline: True
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
In drivers/net/tun.c (ffffffff81763600)
Location: include/net/xdp.h:145
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_sendmsg
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
In drivers/net/tun.c (ffffffff817a133b)
Location: include/net/xdp.h:160
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_sendmsg
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
In drivers/net/tun.c (ffffffff817c62fb)
Location: include/net/xdp.h:160
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_sendmsg
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
In kernel/bpf/devmap.c (ffffffff81226ef5)
Location: include/net/xdp.h:195
Inline: True
Inline callers:
  - kernel/bpf/devmap.c:dev_map_run_prog
```
```
In drivers/net/tun.c (ffffffff8188ce1d)
Location: include/net/xdp.h:195
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_build_skb
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
In kernel/bpf/devmap.c (ffffffff8122da55)
Location: include/net/xdp.h:242
Inline: True
Inline callers:
  - kernel/bpf/devmap.c:dev_map_run_prog
```
```
In drivers/net/tun.c (ffffffff8189b085)
Location: include/net/xdp.h:242
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_build_skb
```
```
In drivers/net/xen-netfront.c (ffffffff818a894d)
Location: include/net/xdp.h:242
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
In kernel/bpf/devmap.c (ffffffff81232b25)
Location: include/net/xdp.h:267
Inline: True
Inline callers:
  - kernel/bpf/devmap.c:dev_map_run_prog
```
```
In drivers/net/tun.c (ffffffff8187db74)
Location: include/net/xdp.h:267
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/net/tun.c (ffffffff8190f244)
Location: include/net/xdp.h:268
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/net/tun.c (ffffffff81a639b2)
Location: include/net/xdp.h:385
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_xdp_one
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/net/tun.c (ffffffff81bf2b92)
Location: include/net/xdp.h:385
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_xdp_one
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/net/tun.c (ffffffff81c49dc6)
Location: include/net/xdp.h:360
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_xdp_one
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/net/tun.c (ffffffff81cff756)
Location: include/net/xdp.h:359
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_xdp_one
```
</details>
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
In drivers/net/tun.c (ffff8000109e141c)
Location: include/net/xdp.h:160
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_sendmsg
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
In drivers/net/tun.c (c0ac659c)
Location: include/net/xdp.h:160
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_xdp_one
  - drivers/net/tun.c:tun_get_user
```
```
In drivers/net/ethernet/ti/cpsw.c (c0ad2ca8)
Location: include/net/xdp.h:160
Inline: True
Inline callers:
  - drivers/net/ethernet/ti/cpsw.c:cpsw_rx_handler
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
In drivers/net/tun.c (c000000000aa3110)
Location: include/net/xdp.h:160
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_sendmsg
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
In drivers/net/tun.c (ffffffe00062af84)
Location: include/net/xdp.h:160
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_sendmsg
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
In drivers/net/tun.c (ffffffff8178addb)
Location: include/net/xdp.h:160
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_sendmsg
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
In drivers/net/tun.c (ffffffff8176a72b)
Location: include/net/xdp.h:160
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_sendmsg
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
In drivers/net/tun.c (ffffffff817bb17b)
Location: include/net/xdp.h:160
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_sendmsg
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
In drivers/net/tun.c (ffffffff817d41b1)
Location: include/net/xdp.h:160
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_sendmsg
```
</details>
</li>
</ul>

## Differences
