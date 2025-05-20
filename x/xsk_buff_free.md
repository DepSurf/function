# Function: <code>xsk_buff_free</code>

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
<details>
<summary>In <code>5.8</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/core/xdp.c (ffffffff81a3579a)
Location: include/net/xdp_sock_drv.h:81
Inline: True
Inline callers:
  - net/core/xdp.c:xdp_convert_zc_to_xdp_frame
```
```
In net/xdp/xsk.c (ffffffff81ba7549)
Location: include/net/xdp_sock_drv.h:81
Inline: True
Inline callers:
  - net/xdp/xsk.c:__xsk_rcv
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
In net/core/xdp.c (ffffffff81a37b3a)
Location: include/net/xdp_sock_drv.h:85
Inline: True
Inline callers:
  - net/core/xdp.c:xdp_convert_zc_to_xdp_frame
  - net/core/xdp.c:__xdp_return
```
```
In net/xdp/xsk.c (ffffffff81bb6caa)
Location: include/net/xdp_sock_drv.h:85
Inline: True
Inline callers:
  - net/xdp/xsk.c:__xsk_rcv
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
In net/core/xdp.c (ffffffff81a1ecca)
Location: include/net/xdp_sock_drv.h:85
Inline: True
Inline callers:
  - net/core/xdp.c:xdp_convert_zc_to_xdp_frame
  - net/core/xdp.c:__xdp_return
```
```
In net/xdp/xsk.c (ffffffff81ba5c46)
Location: include/net/xdp_sock_drv.h:85
Inline: True
Inline callers:
  - net/xdp/xsk.c:__xsk_rcv
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
In net/core/xdp.c (ffffffff81ad2d6a)
Location: include/net/xdp_sock_drv.h:85
Inline: True
Inline callers:
  - net/core/xdp.c:xdp_convert_zc_to_xdp_frame
  - net/core/xdp.c:__xdp_return
```
```
In net/xdp/xsk.c (ffffffff81c736c6)
Location: include/net/xdp_sock_drv.h:85
Inline: True
Inline callers:
  - net/xdp/xsk.c:__xsk_rcv
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
In net/core/xdp.c (ffffffff81c50888)
Location: include/net/xdp_sock_drv.h:91
Inline: True
Inline callers:
  - net/core/xdp.c:xdp_convert_zc_to_xdp_frame
  - net/core/xdp.c:__xdp_return
```
```
In net/xdp/xsk.c (ffffffff81e172d8)
Location: include/net/xdp_sock_drv.h:91
Inline: True
Inline callers:
  - net/xdp/xsk.c:__xsk_rcv
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
In net/core/xdp.c (ffffffff81e05d07)
Location: include/net/xdp_sock_drv.h:103
Inline: True
Inline callers:
  - net/core/xdp.c:xdp_convert_zc_to_xdp_frame
  - net/core/xdp.c:__xdp_return
```
```
In net/xdp/xsk.c (ffffffff81fee120)
Location: include/net/xdp_sock_drv.h:103
Inline: True
Inline callers:
  - net/xdp/xsk.c:__xsk_rcv
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
In net/core/xdp.c (ffffffff81e78637)
Location: include/net/xdp_sock_drv.h:103
Inline: True
Inline callers:
  - net/core/xdp.c:xdp_convert_zc_to_xdp_frame
  - net/core/xdp.c:__xdp_return
```
```
In net/xdp/xsk.c (ffffffff8206a280)
Location: include/net/xdp_sock_drv.h:103
Inline: True
Inline callers:
  - net/xdp/xsk.c:__xsk_rcv
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
In net/core/xdp.c (ffffffff81f39238)
Location: include/net/xdp_sock_drv.h:120
Inline: True
Inline callers:
  - net/core/xdp.c:xdp_convert_zc_to_xdp_frame
  - net/core/xdp.c:__xdp_return
```
```
In net/xdp/xsk.c (ffffffff8213ff25)
Location: include/net/xdp_sock_drv.h:120
Inline: True
Inline callers:
  - net/xdp/xsk.c:__xsk_map_redirect
  - net/xdp/xsk.c:__xsk_rcv
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
In <code>arm64</code>: Absent ⚠️
</li>
<li>
In <code>armhf</code>: Absent ⚠️
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
