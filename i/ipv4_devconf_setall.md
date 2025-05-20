# Function: <code>ipv4_devconf_setall</code>

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
In net/ipv4/devinet.c (ffffffff81791abe)
Location: include/linux/inetdevice.h:67
Inline: True
Inline callers:
  - net/ipv4/devinet.c:inet_rtm_newaddr
  - net/ipv4/devinet.c:inetdev_event
  - net/ipv4/devinet.c:devinet_ioctl
```
```
In net/ipv4/ipmr.c (ffffffff817a7dd4)
Location: include/linux/inetdevice.h:67
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:vif_add
  - net/ipv4/ipmr.c:vif_add
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
In net/ipv4/devinet.c (ffffffff817ffffa)
Location: include/linux/inetdevice.h:67
Inline: True
Inline callers:
  - net/ipv4/devinet.c:inetdev_event
  - net/ipv4/devinet.c:devinet_ioctl
  - net/ipv4/devinet.c:inet_rtm_newaddr
```
```
In net/ipv4/ipmr.c (ffffffff818905aa)
Location: include/linux/inetdevice.h:67
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_init_vif_indev
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
In net/ipv4/devinet.c (ffffffff81830f5a)
Location: include/linux/inetdevice.h:67
Inline: True
Inline callers:
  - net/ipv4/devinet.c:inetdev_event
  - net/ipv4/devinet.c:devinet_ioctl
  - net/ipv4/devinet.c:inet_rtm_newaddr
```
```
In net/ipv4/ipmr.c (ffffffff818c4bc4)
Location: include/linux/inetdevice.h:67
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_init_vif_indev
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
In net/ipv4/devinet.c (ffffffff81852205)
Location: include/linux/inetdevice.h:68
Inline: True
Inline callers:
  - net/ipv4/devinet.c:inetdev_event
  - net/ipv4/devinet.c:devinet_ioctl
  - net/ipv4/devinet.c:inet_rtm_newaddr
```
```
In net/ipv4/ipmr.c (ffffffff81868d8b)
Location: include/linux/inetdevice.h:68
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_init_vif_indev
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
In net/ipv4/devinet.c (ffffffff818d2011)
Location: include/linux/inetdevice.h:69
Inline: True
Inline callers:
  - net/ipv4/devinet.c:inetdev_event
  - net/ipv4/devinet.c:devinet_ioctl
  - net/ipv4/devinet.c:inet_rtm_newaddr
```
```
In net/ipv4/ipmr.c (ffffffff818e92cb)
Location: include/linux/inetdevice.h:69
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_init_vif_indev
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
In net/ipv4/devinet.c (ffffffff8192852e)
Location: include/linux/inetdevice.h:69
Inline: True
Inline callers:
  - net/ipv4/devinet.c:inetdev_event
  - net/ipv4/devinet.c:devinet_ioctl
  - net/ipv4/devinet.c:inet_rtm_newaddr
```
```
In net/ipv4/ipmr.c (ffffffff8193ed92)
Location: include/linux/inetdevice.h:69
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_init_vif_indev
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
In net/ipv4/devinet.c (ffffffff81957981)
Location: include/linux/inetdevice.h:71
Inline: True
Inline callers:
  - net/ipv4/devinet.c:inetdev_event
  - net/ipv4/devinet.c:devinet_ioctl
  - net/ipv4/devinet.c:inet_rtm_newaddr
```
```
In net/ipv4/ipmr.c (ffffffff8196f654)
Location: include/linux/inetdevice.h:71
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_init_vif_indev
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
In net/ipv4/devinet.c (ffffffff819bc308)
Location: include/linux/inetdevice.h:71
Inline: True
Inline callers:
  - net/ipv4/devinet.c:inetdev_event
  - net/ipv4/devinet.c:devinet_ioctl
  - net/ipv4/devinet.c:inet_rtm_newaddr
```
```
In net/ipv4/ipmr.c (ffffffff819d8da5)
Location: include/linux/inetdevice.h:71
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_init_vif_indev
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
In net/ipv4/devinet.c (ffffffff819f3007)
Location: include/linux/inetdevice.h:71
Inline: True
Inline callers:
  - net/ipv4/devinet.c:inetdev_event
  - net/ipv4/devinet.c:devinet_ioctl
  - net/ipv4/devinet.c:inet_rtm_newaddr
```
```
In net/ipv4/ipmr.c (ffffffff81a0fb15)
Location: include/linux/inetdevice.h:71
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_init_vif_indev
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
In net/ipv4/devinet.c (ffffffff81ae19f5)
Location: include/linux/inetdevice.h:71
Inline: True
Inline callers:
  - net/ipv4/devinet.c:inetdev_event
  - net/ipv4/devinet.c:rtm_to_ifaddr
```
```
In net/ipv4/ipmr.c (ffffffff81b00c55)
Location: include/linux/inetdevice.h:71
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_init_vif_indev
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
In net/ipv4/devinet.c (ffffffff81aee895)
Location: include/linux/inetdevice.h:71
Inline: True
Inline callers:
  - net/ipv4/devinet.c:inetdev_event
  - net/ipv4/devinet.c:rtm_to_ifaddr
```
```
In net/ipv4/ipmr.c (ffffffff81b0ed35)
Location: include/linux/inetdevice.h:71
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_init_vif_indev
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
In net/ipv4/devinet.c (ffffffff81ad9f8d)
Location: include/linux/inetdevice.h:71
Inline: True
Inline callers:
  - net/ipv4/devinet.c:inetdev_event
  - net/ipv4/devinet.c:rtm_to_ifaddr
```
```
In net/ipv4/ipmr.c (ffffffff81afca35)
Location: include/linux/inetdevice.h:71
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_init_vif_indev
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
In net/ipv4/devinet.c (ffffffff81b990cd)
Location: include/linux/inetdevice.h:71
Inline: True
Inline callers:
  - net/ipv4/devinet.c:inetdev_event
  - net/ipv4/devinet.c:rtm_to_ifaddr
```
```
In net/ipv4/ipmr.c (ffffffff81bbe1b7)
Location: include/linux/inetdevice.h:71
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_init_vif_indev
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
In net/ipv4/devinet.c (ffffffff81d2afe9)
Location: include/linux/inetdevice.h:73
Inline: True
Inline callers:
  - net/ipv4/devinet.c:inetdev_event
```
```
In net/ipv4/ipmr.c (ffffffff81d530d6)
Location: include/linux/inetdevice.h:73
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_init_vif_indev
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
In net/ipv4/devinet.c (ffffffff81ef2c04)
Location: include/linux/inetdevice.h:73
Inline: True
Inline callers:
  - net/ipv4/devinet.c:inetdev_event
  - net/ipv4/devinet.c:devinet_ioctl
```
```
In net/ipv4/ipmr.c (ffffffff81f1c3f4)
Location: include/linux/inetdevice.h:73
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_init_vif_indev
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
In net/ipv4/devinet.c (ffffffff81f527b2)
Location: include/linux/inetdevice.h:73
Inline: True
Inline callers:
  - net/ipv4/devinet.c:inetdev_event
  - net/ipv4/devinet.c:devinet_ioctl
```
```
In net/ipv4/ipmr.c (ffffffff81f7bed4)
Location: include/linux/inetdevice.h:73
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_init_vif_indev
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
In net/ipv4/devinet.c (ffffffff82018a94)
Location: include/linux/inetdevice.h:73
Inline: True
Inline callers:
  - net/ipv4/devinet.c:inetdev_event
  - net/ipv4/devinet.c:devinet_ioctl
```
```
In net/ipv4/ipmr.c (ffffffff820425c4)
Location: include/linux/inetdevice.h:73
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_init_vif_indev
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
In net/ipv4/devinet.c (ffff800010ca93ac)
Location: include/linux/inetdevice.h:71
Inline: True
Inline callers:
  - net/ipv4/devinet.c:inetdev_event
  - net/ipv4/devinet.c:devinet_ioctl
  - net/ipv4/devinet.c:inet_rtm_newaddr
```
```
In net/ipv4/ipmr.c (ffff800010cc97e4)
Location: include/linux/inetdevice.h:71
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_init_vif_indev
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
In net/ipv4/devinet.c (c0db59b8)
Location: include/linux/inetdevice.h:71
Inline: True
Inline callers:
  - net/ipv4/devinet.c:inetdev_event
  - net/ipv4/devinet.c:devinet_ioctl
  - net/ipv4/devinet.c:inet_rtm_newaddr
```
```
In net/ipv4/ipmr.c (c0dd4f0c)
Location: include/linux/inetdevice.h:71
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_init_vif_indev
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
In net/ipv4/devinet.c (c000000000dbe510)
Location: include/linux/inetdevice.h:71
Inline: True
Inline callers:
  - net/ipv4/devinet.c:inetdev_event
  - net/ipv4/devinet.c:devinet_ioctl
  - net/ipv4/devinet.c:inet_rtm_newaddr
```
```
In net/ipv4/ipmr.c (c000000000de7794)
Location: include/linux/inetdevice.h:71
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_init_vif_indev
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
In net/ipv4/devinet.c (ffffffe000803e78)
Location: include/linux/inetdevice.h:71
Inline: True
Inline callers:
  - net/ipv4/devinet.c:inetdev_event
  - net/ipv4/devinet.c:devinet_ioctl
  - net/ipv4/devinet.c:inet_rtm_newaddr
```
```
In net/ipv4/ipmr.c (ffffffe00081d2a2)
Location: include/linux/inetdevice.h:71
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_init_vif_indev
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
In net/ipv4/devinet.c (ffffffff81992da7)
Location: include/linux/inetdevice.h:71
Inline: True
Inline callers:
  - net/ipv4/devinet.c:inetdev_event
  - net/ipv4/devinet.c:devinet_ioctl
  - net/ipv4/devinet.c:inet_rtm_newaddr
```
```
In net/ipv4/ipmr.c (ffffffff819af535)
Location: include/linux/inetdevice.h:71
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_init_vif_indev
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
In net/ipv4/devinet.c (ffffffff8194c867)
Location: include/linux/inetdevice.h:71
Inline: True
Inline callers:
  - net/ipv4/devinet.c:inetdev_event
  - net/ipv4/devinet.c:devinet_ioctl
  - net/ipv4/devinet.c:inet_rtm_newaddr
```
```
In net/ipv4/ipmr.c (ffffffff8196bb65)
Location: include/linux/inetdevice.h:71
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_init_vif_indev
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
In net/ipv4/devinet.c (ffffffff819fd647)
Location: include/linux/inetdevice.h:71
Inline: True
Inline callers:
  - net/ipv4/devinet.c:inetdev_event
  - net/ipv4/devinet.c:devinet_ioctl
  - net/ipv4/devinet.c:inet_rtm_newaddr
```
```
In net/ipv4/ipmr.c (ffffffff81a19dd5)
Location: include/linux/inetdevice.h:71
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_init_vif_indev
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
In net/ipv4/devinet.c (ffffffff81a079d7)
Location: include/linux/inetdevice.h:71
Inline: True
Inline callers:
  - net/ipv4/devinet.c:inetdev_event
  - net/ipv4/devinet.c:devinet_ioctl
  - net/ipv4/devinet.c:inet_rtm_newaddr
```
```
In net/ipv4/ipmr.c (ffffffff81a24c05)
Location: include/linux/inetdevice.h:71
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_init_vif_indev
```
</details>
</li>
</ul>

## Differences
