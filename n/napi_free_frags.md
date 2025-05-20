# Function: <code>napi_free_frags</code>

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
In net/core/dev.c (ffffffff81715cb7)
Location: include/linux/netdevice.h:3063
Inline: True
Inline callers:
  - net/core/dev.c:netif_napi_del
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
In net/core/dev.c (ffffffff8177e4af)
Location: include/linux/netdevice.h:3286
Inline: True
Inline callers:
  - net/core/dev.c:netif_napi_del
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
In net/core/dev.c (ffffffff817abcaf)
Location: include/linux/netdevice.h:3225
Inline: True
Inline callers:
  - net/core/dev.c:netif_napi_del
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
In net/core/dev.c (ffffffff817ca23f)
Location: include/linux/netdevice.h:3264
Inline: True
Inline callers:
  - net/core/dev.c:netif_napi_del
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
In drivers/net/tun.c (ffffffff816ff882)
Location: include/linux/netdevice.h:3292
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_get_user
  - drivers/net/tun.c:tun_get_user
```
```
In net/core/dev.c (ffffffff81843d3f)
Location: include/linux/netdevice.h:3292
Inline: True
Inline callers:
  - net/core/dev.c:netif_napi_del
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
In drivers/net/tun.c (ffffffff8173f4e5)
Location: include/linux/netdevice.h:3394
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_get_user
  - drivers/net/tun.c:tun_get_user
```
```
In net/core/dev.c (ffffffff81890f4c)
Location: include/linux/netdevice.h:3394
Inline: True
Inline callers:
  - net/core/dev.c:netif_napi_del
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
In drivers/net/tun.c (ffffffff81763430)
Location: include/linux/netdevice.h:3611
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_get_user
  - drivers/net/tun.c:tun_get_user
```
```
In net/core/dev.c (ffffffff818b1544)
Location: include/linux/netdevice.h:3611
Inline: True
Inline callers:
  - net/core/dev.c:netif_napi_del
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
In drivers/net/tun.c (ffffffff817a113c)
Location: include/linux/netdevice.h:3628
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_get_user
  - drivers/net/tun.c:tun_get_user
```
```
In net/core/dev.c (ffffffff818fe2f4)
Location: include/linux/netdevice.h:3628
Inline: True
Inline callers:
  - net/core/dev.c:netif_napi_del
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
In drivers/net/tun.c (ffffffff817c610e)
Location: include/linux/netdevice.h:3642
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_get_user
  - drivers/net/tun.c:tun_get_user
```
```
In net/core/dev.c (ffffffff81930624)
Location: include/linux/netdevice.h:3642
Inline: True
Inline callers:
  - net/core/dev.c:netif_napi_del
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
In drivers/net/tun.c (ffffffff8188e248)
Location: include/linux/netdevice.h:3755
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_get_user
  - drivers/net/tun.c:tun_napi_alloc_frags
```
```
In net/core/dev.c (ffffffff81a04214)
Location: include/linux/netdevice.h:3755
Inline: True
Inline callers:
  - net/core/dev.c:netif_napi_del
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
In drivers/net/tun.c (ffffffff8189c7b0)
Location: include/linux/netdevice.h:3917
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_get_user
  - drivers/net/tun.c:tun_napi_alloc_frags
```
```
In net/core/dev.c (ffffffff81a06249)
Location: include/linux/netdevice.h:3917
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
In drivers/net/tun.c (ffffffff8187ed15)
Location: include/linux/netdevice.h:4002
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_get_user
  - drivers/net/tun.c:tun_napi_alloc_frags
```
```
In net/core/dev.c (ffffffff819ecd79)
Location: include/linux/netdevice.h:4002
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
In drivers/net/tun.c (ffffffff81910509)
Location: include/linux/netdevice.h:4018
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_get_user
  - drivers/net/tun.c:tun_napi_alloc_frags
```
```
In net/core/dev.c (ffffffff81a9df05)
Location: include/linux/netdevice.h:4018
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
In drivers/net/tun.c (ffffffff81a674ee)
Location: include/linux/netdevice.h:3809
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_get_user
  - drivers/net/tun.c:tun_napi_alloc_frags
```
```
In net/core/dev.c (ffffffff81c0f086)
Location: include/linux/netdevice.h:3809
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
In drivers/net/tun.c (ffffffff81bf2962)
Location: include/linux/netdevice.h:3855
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_get_user
  - drivers/net/tun.c:tun_napi_alloc_frags
```
```
In net/core/skbuff.c (ffffffff81da70cd)
Location: include/linux/netdevice.h:3855
Inline: True
Inline callers:
  - net/core/skbuff.c:napi_get_frags_check
```
```
In net/core/dev.c (ffffffff81dbedc6)
Location: include/linux/netdevice.h:3855
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
In drivers/net/tun.c (ffffffff81c4b669)
Location: include/linux/netdevice.h:3914
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_get_user
  - drivers/net/tun.c:tun_napi_alloc_frags
```
```
In net/core/skbuff.c (ffffffff81e1917d)
Location: include/linux/netdevice.h:3914
Inline: True
Inline callers:
  - net/core/skbuff.c:napi_get_frags_check
```
```
In net/core/dev.c (ffffffff81e2e996)
Location: include/linux/netdevice.h:3914
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
In drivers/net/tun.c (ffffffff81d00d25)
Location: include/linux/netdevice.h:3985
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_get_user
  - drivers/net/tun.c:tun_napi_alloc_frags
```
```
In net/core/skbuff.c (ffffffff81ed660d)
Location: include/linux/netdevice.h:3985
Inline: True
Inline callers:
  - net/core/skbuff.c:napi_get_frags_check
```
```
In net/core/dev.c (ffffffff81eed316)
Location: include/linux/netdevice.h:3985
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
In drivers/net/tun.c (ffff8000109e1214)
Location: include/linux/netdevice.h:3642
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_get_user
  - drivers/net/tun.c:tun_get_user
```
```
In net/core/dev.c (ffff800010bcc56c)
Location: include/linux/netdevice.h:3642
Inline: True
Inline callers:
  - net/core/dev.c:netif_napi_del
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
In drivers/net/tun.c (c0ac5654)
Location: include/linux/netdevice.h:3642
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_get_user
  - drivers/net/tun.c:tun_get_user
```
```
In net/core/dev.c (c0ce5370)
Location: include/linux/netdevice.h:3642
Inline: True
Inline callers:
  - net/core/dev.c:netif_napi_del
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
In drivers/net/tun.c (c000000000aa25ec)
Location: include/linux/netdevice.h:3642
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_get_user
  - drivers/net/tun.c:tun_get_user
```
```
In net/core/dev.c (c000000000cab7c4)
Location: include/linux/netdevice.h:3642
Inline: True
Inline callers:
  - net/core/dev.c:netif_napi_del
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
In drivers/net/tun.c (ffffffe00062ada6)
Location: include/linux/netdevice.h:3642
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_get_user
  - drivers/net/tun.c:tun_get_user
```
```
In net/core/dev.c (ffffffe000757ff8)
Location: include/linux/netdevice.h:3642
Inline: True
Inline callers:
  - net/core/dev.c:netif_napi_del
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
In drivers/net/tun.c (ffffffff8178abee)
Location: include/linux/netdevice.h:3642
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_get_user
  - drivers/net/tun.c:tun_get_user
```
```
In net/core/dev.c (ffffffff818d0624)
Location: include/linux/netdevice.h:3642
Inline: True
Inline callers:
  - net/core/dev.c:netif_napi_del
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
In drivers/net/tun.c (ffffffff8176a53e)
Location: include/linux/netdevice.h:3642
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_get_user
  - drivers/net/tun.c:tun_get_user
```
```
In net/core/dev.c (ffffffff8188a504)
Location: include/linux/netdevice.h:3642
Inline: True
Inline callers:
  - net/core/dev.c:netif_napi_del
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
In drivers/net/tun.c (ffffffff817baf8e)
Location: include/linux/netdevice.h:3642
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_get_user
  - drivers/net/tun.c:tun_get_user
```
```
In net/core/dev.c (ffffffff81921624)
Location: include/linux/netdevice.h:3642
Inline: True
Inline callers:
  - net/core/dev.c:netif_napi_del
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
In drivers/net/tun.c (ffffffff817d34e5)
Location: include/linux/netdevice.h:3642
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_get_user
  - drivers/net/tun.c:tun_get_user
```
```
In net/core/dev.c (ffffffff8193f00c)
Location: include/linux/netdevice.h:3642
Inline: True
Inline callers:
  - net/core/dev.c:netif_napi_del
```
</details>
</li>
</ul>

## Differences
