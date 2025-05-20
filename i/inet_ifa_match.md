# Function: <code>inet_ifa_match</code>

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
In net/ipv4/devinet.c (0)
Location: include/linux/inetdevice.h:174
Inline: True
```
```
In net/ipv4/fib_frontend.c (0)
Location: include/linux/inetdevice.h:174
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
In net/ipv4/devinet.c (ffffffff817fcdcc)
Location: include/linux/inetdevice.h:174
Inline: True
Inline callers:
  - net/ipv4/devinet.c:inet_select_addr
  - net/ipv4/devinet.c:inet_rtm_newaddr
  - net/ipv4/devinet.c:inet_rtm_deladdr
  - net/ipv4/devinet.c:inet_ifa_byprefix
  - net/ipv4/devinet.c:__inet_insert_ifa
  - net/ipv4/devinet.c:__inet_del_ifa
  - net/ipv4/devinet.c:__inet_del_ifa
  - net/ipv4/devinet.c:__inet_del_ifa
  - net/ipv4/devinet.c:inet_addr_onlink
  - net/ipv4/devinet.c:inet_addr_onlink
```
```
In net/ipv4/fib_frontend.c (ffffffff81809800)
Location: include/linux/inetdevice.h:174
Inline: True
Inline callers:
  - net/ipv4/fib_frontend.c:fib_del_ifaddr
  - net/ipv4/fib_frontend.c:fib_del_ifaddr
  - net/ipv4/fib_frontend.c:fib_del_ifaddr
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
In net/ipv4/devinet.c (ffffffff8182dd2c)
Location: include/linux/inetdevice.h:174
Inline: True
Inline callers:
  - net/ipv4/devinet.c:inet_select_addr
  - net/ipv4/devinet.c:inet_rtm_newaddr
  - net/ipv4/devinet.c:inet_rtm_deladdr
  - net/ipv4/devinet.c:inet_ifa_byprefix
  - net/ipv4/devinet.c:__inet_insert_ifa
  - net/ipv4/devinet.c:__inet_del_ifa
  - net/ipv4/devinet.c:__inet_del_ifa
  - net/ipv4/devinet.c:__inet_del_ifa
  - net/ipv4/devinet.c:inet_addr_onlink
  - net/ipv4/devinet.c:inet_addr_onlink
```
```
In net/ipv4/fib_frontend.c (ffffffff8183a910)
Location: include/linux/inetdevice.h:174
Inline: True
Inline callers:
  - net/ipv4/fib_frontend.c:fib_del_ifaddr
  - net/ipv4/fib_frontend.c:fib_del_ifaddr
  - net/ipv4/fib_frontend.c:fib_del_ifaddr
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
In net/ipv4/devinet.c (ffffffff8184f7cc)
Location: include/linux/inetdevice.h:182
Inline: True
Inline callers:
  - net/ipv4/devinet.c:inet_select_addr
  - net/ipv4/devinet.c:inet_rtm_newaddr
  - net/ipv4/devinet.c:inet_rtm_deladdr
  - net/ipv4/devinet.c:inet_ifa_byprefix
  - net/ipv4/devinet.c:__inet_insert_ifa
  - net/ipv4/devinet.c:__inet_del_ifa
  - net/ipv4/devinet.c:__inet_del_ifa
  - net/ipv4/devinet.c:__inet_del_ifa
  - net/ipv4/devinet.c:inet_addr_onlink
  - net/ipv4/devinet.c:inet_addr_onlink
```
```
In net/ipv4/fib_frontend.c (ffffffff8185be37)
Location: include/linux/inetdevice.h:182
Inline: True
Inline callers:
  - net/ipv4/fib_frontend.c:fib_del_ifaddr
  - net/ipv4/fib_frontend.c:fib_del_ifaddr
  - net/ipv4/fib_frontend.c:fib_del_ifaddr
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
In net/ipv4/devinet.c (ffffffff818cf3fc)
Location: include/linux/inetdevice.h:185
Inline: True
Inline callers:
  - net/ipv4/devinet.c:inet_select_addr
  - net/ipv4/devinet.c:inet_rtm_newaddr
  - net/ipv4/devinet.c:inet_rtm_deladdr
  - net/ipv4/devinet.c:inet_ifa_byprefix
  - net/ipv4/devinet.c:__inet_insert_ifa
  - net/ipv4/devinet.c:__inet_del_ifa
  - net/ipv4/devinet.c:__inet_del_ifa
  - net/ipv4/devinet.c:__inet_del_ifa
  - net/ipv4/devinet.c:inet_addr_onlink
  - net/ipv4/devinet.c:inet_addr_onlink
```
```
In net/ipv4/fib_frontend.c (ffffffff818dbd27)
Location: include/linux/inetdevice.h:185
Inline: True
Inline callers:
  - net/ipv4/fib_frontend.c:fib_del_ifaddr
  - net/ipv4/fib_frontend.c:fib_del_ifaddr
  - net/ipv4/fib_frontend.c:fib_del_ifaddr
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
In net/ipv4/devinet.c (ffffffff8192527c)
Location: include/linux/inetdevice.h:186
Inline: True
Inline callers:
  - net/ipv4/devinet.c:inet_select_addr
  - net/ipv4/devinet.c:inet_rtm_newaddr
  - net/ipv4/devinet.c:inet_rtm_deladdr
  - net/ipv4/devinet.c:inet_ifa_byprefix
  - net/ipv4/devinet.c:__inet_insert_ifa
  - net/ipv4/devinet.c:__inet_del_ifa
  - net/ipv4/devinet.c:__inet_del_ifa
  - net/ipv4/devinet.c:__inet_del_ifa
  - net/ipv4/devinet.c:inet_addr_onlink
  - net/ipv4/devinet.c:inet_addr_onlink
```
```
In net/ipv4/fib_frontend.c (ffffffff8193293a)
Location: include/linux/inetdevice.h:186
Inline: True
Inline callers:
  - net/ipv4/fib_frontend.c:fib_del_ifaddr
  - net/ipv4/fib_frontend.c:fib_del_ifaddr
  - net/ipv4/fib_frontend.c:fib_del_ifaddr
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
In net/ipv4/devinet.c (ffffffff8195408c)
Location: include/linux/inetdevice.h:189
Inline: True
Inline callers:
  - net/ipv4/devinet.c:inet_select_addr
  - net/ipv4/devinet.c:inet_rtm_newaddr
  - net/ipv4/devinet.c:inet_rtm_deladdr
  - net/ipv4/devinet.c:inet_ifa_byprefix
  - net/ipv4/devinet.c:__inet_insert_ifa
  - net/ipv4/devinet.c:__inet_del_ifa
  - net/ipv4/devinet.c:__inet_del_ifa
  - net/ipv4/devinet.c:__inet_del_ifa
  - net/ipv4/devinet.c:inet_addr_onlink
  - net/ipv4/devinet.c:inet_addr_onlink
```
```
In net/ipv4/fib_frontend.c (ffffffff819621ca)
Location: include/linux/inetdevice.h:189
Inline: True
Inline callers:
  - net/ipv4/fib_frontend.c:fib_del_ifaddr
  - net/ipv4/fib_frontend.c:fib_del_ifaddr
  - net/ipv4/fib_frontend.c:fib_del_ifaddr
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
In net/ipv4/devinet.c (ffffffff819b8903)
Location: include/linux/inetdevice.h:189
Inline: True
Inline callers:
  - net/ipv4/devinet.c:confirm_addr_indev
  - net/ipv4/devinet.c:confirm_addr_indev
  - net/ipv4/devinet.c:confirm_addr_indev
  - net/ipv4/devinet.c:inet_select_addr
  - net/ipv4/devinet.c:inet_rtm_newaddr
  - net/ipv4/devinet.c:inet_rtm_deladdr
  - net/ipv4/devinet.c:inet_ifa_byprefix
  - net/ipv4/devinet.c:__inet_insert_ifa
  - net/ipv4/devinet.c:__inet_del_ifa
  - net/ipv4/devinet.c:__inet_del_ifa
  - net/ipv4/devinet.c:__inet_del_ifa
  - net/ipv4/devinet.c:inet_addr_onlink
  - net/ipv4/devinet.c:inet_addr_onlink
```
```
In net/ipv4/fib_frontend.c (ffffffff819c6f15)
Location: include/linux/inetdevice.h:189
Inline: True
Inline callers:
  - net/ipv4/fib_frontend.c:fib_del_ifaddr
  - net/ipv4/fib_frontend.c:fib_del_ifaddr
  - net/ipv4/fib_frontend.c:fib_del_ifaddr
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
In net/ipv4/devinet.c (ffffffff819ef603)
Location: include/linux/inetdevice.h:189
Inline: True
Inline callers:
  - net/ipv4/devinet.c:confirm_addr_indev
  - net/ipv4/devinet.c:confirm_addr_indev
  - net/ipv4/devinet.c:confirm_addr_indev
  - net/ipv4/devinet.c:inet_select_addr
  - net/ipv4/devinet.c:inet_rtm_newaddr
  - net/ipv4/devinet.c:inet_rtm_deladdr
  - net/ipv4/devinet.c:inet_ifa_byprefix
  - net/ipv4/devinet.c:__inet_insert_ifa
  - net/ipv4/devinet.c:__inet_del_ifa
  - net/ipv4/devinet.c:__inet_del_ifa
  - net/ipv4/devinet.c:__inet_del_ifa
  - net/ipv4/devinet.c:inet_addr_onlink
  - net/ipv4/devinet.c:inet_addr_onlink
```
```
In net/ipv4/fib_frontend.c (ffffffff819fdac5)
Location: include/linux/inetdevice.h:189
Inline: True
Inline callers:
  - net/ipv4/fib_frontend.c:fib_del_ifaddr
  - net/ipv4/fib_frontend.c:fib_del_ifaddr
  - net/ipv4/fib_frontend.c:fib_del_ifaddr
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
In net/ipv4/devinet.c (ffffffff81add559)
Location: include/linux/inetdevice.h:189
Inline: True
Inline callers:
  - net/ipv4/devinet.c:confirm_addr_indev
  - net/ipv4/devinet.c:confirm_addr_indev
  - net/ipv4/devinet.c:confirm_addr_indev
  - net/ipv4/devinet.c:inet_select_addr
  - net/ipv4/devinet.c:inet_rtm_newaddr
  - net/ipv4/devinet.c:inet_rtm_deladdr
  - net/ipv4/devinet.c:inet_ifa_byprefix
  - net/ipv4/devinet.c:__inet_insert_ifa
  - net/ipv4/devinet.c:__inet_del_ifa
  - net/ipv4/devinet.c:__inet_del_ifa
  - net/ipv4/devinet.c:__inet_del_ifa
  - net/ipv4/devinet.c:inet_addr_onlink
  - net/ipv4/devinet.c:inet_addr_onlink
```
```
In net/ipv4/fib_frontend.c (ffffffff81aec4cf)
Location: include/linux/inetdevice.h:189
Inline: True
Inline callers:
  - net/ipv4/fib_frontend.c:fib_del_ifaddr
  - net/ipv4/fib_frontend.c:fib_del_ifaddr
  - net/ipv4/fib_frontend.c:fib_del_ifaddr
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
In net/ipv4/devinet.c (ffffffff81aea279)
Location: include/linux/inetdevice.h:189
Inline: True
Inline callers:
  - net/ipv4/devinet.c:confirm_addr_indev
  - net/ipv4/devinet.c:confirm_addr_indev
  - net/ipv4/devinet.c:confirm_addr_indev
  - net/ipv4/devinet.c:inet_select_addr
  - net/ipv4/devinet.c:inet_rtm_newaddr
  - net/ipv4/devinet.c:inet_rtm_deladdr
  - net/ipv4/devinet.c:inet_ifa_byprefix
  - net/ipv4/devinet.c:__inet_insert_ifa
  - net/ipv4/devinet.c:__inet_del_ifa
  - net/ipv4/devinet.c:__inet_del_ifa
  - net/ipv4/devinet.c:__inet_del_ifa
  - net/ipv4/devinet.c:inet_addr_onlink
  - net/ipv4/devinet.c:inet_addr_onlink
```
```
In net/ipv4/fib_frontend.c (ffffffff81af93d6)
Location: include/linux/inetdevice.h:189
Inline: True
Inline callers:
  - net/ipv4/fib_frontend.c:fib_del_ifaddr
  - net/ipv4/fib_frontend.c:fib_del_ifaddr
  - net/ipv4/fib_frontend.c:fib_del_ifaddr
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
In net/ipv4/devinet.c (ffffffff81ad59cc)
Location: include/linux/inetdevice.h:189
Inline: True
Inline callers:
  - net/ipv4/devinet.c:confirm_addr_indev
  - net/ipv4/devinet.c:confirm_addr_indev
  - net/ipv4/devinet.c:confirm_addr_indev
  - net/ipv4/devinet.c:inet_select_addr
  - net/ipv4/devinet.c:inet_rtm_newaddr
  - net/ipv4/devinet.c:inet_rtm_deladdr
  - net/ipv4/devinet.c:inet_ifa_byprefix
  - net/ipv4/devinet.c:__inet_insert_ifa
  - net/ipv4/devinet.c:__inet_del_ifa
  - net/ipv4/devinet.c:__inet_del_ifa
  - net/ipv4/devinet.c:__inet_del_ifa
  - net/ipv4/devinet.c:inet_addr_onlink
  - net/ipv4/devinet.c:inet_addr_onlink
```
```
In net/ipv4/fib_frontend.c (ffffffff81ae4b96)
Location: include/linux/inetdevice.h:189
Inline: True
Inline callers:
  - net/ipv4/fib_frontend.c:fib_del_ifaddr
  - net/ipv4/fib_frontend.c:fib_del_ifaddr
  - net/ipv4/fib_frontend.c:fib_del_ifaddr
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
In net/ipv4/devinet.c (ffffffff81b9488c)
Location: include/linux/inetdevice.h:198
Inline: True
Inline callers:
  - net/ipv4/devinet.c:confirm_addr_indev
  - net/ipv4/devinet.c:confirm_addr_indev
  - net/ipv4/devinet.c:confirm_addr_indev
  - net/ipv4/devinet.c:inet_select_addr
  - net/ipv4/devinet.c:inet_rtm_newaddr
  - net/ipv4/devinet.c:inet_rtm_deladdr
  - net/ipv4/devinet.c:inet_ifa_byprefix
  - net/ipv4/devinet.c:__inet_insert_ifa
  - net/ipv4/devinet.c:__inet_del_ifa
  - net/ipv4/devinet.c:__inet_del_ifa
  - net/ipv4/devinet.c:__inet_del_ifa
  - net/ipv4/devinet.c:inet_addr_onlink
  - net/ipv4/devinet.c:inet_addr_onlink
```
```
In net/ipv4/fib_frontend.c (ffffffff81ba44c6)
Location: include/linux/inetdevice.h:198
Inline: True
Inline callers:
  - net/ipv4/fib_frontend.c:fib_del_ifaddr
  - net/ipv4/fib_frontend.c:fib_del_ifaddr
  - net/ipv4/fib_frontend.c:fib_del_ifaddr
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
In net/ipv4/devinet.c (ffffffff81d26207)
Location: include/linux/inetdevice.h:203
Inline: True
Inline callers:
  - net/ipv4/devinet.c:confirm_addr_indev
  - net/ipv4/devinet.c:confirm_addr_indev
  - net/ipv4/devinet.c:confirm_addr_indev
  - net/ipv4/devinet.c:inet_select_addr
  - net/ipv4/devinet.c:inet_rtm_newaddr
  - net/ipv4/devinet.c:inet_rtm_deladdr
  - net/ipv4/devinet.c:inet_ifa_byprefix
  - net/ipv4/devinet.c:__inet_insert_ifa
  - net/ipv4/devinet.c:__inet_del_ifa
  - net/ipv4/devinet.c:__inet_del_ifa
  - net/ipv4/devinet.c:__inet_del_ifa
  - net/ipv4/devinet.c:inet_addr_onlink
  - net/ipv4/devinet.c:inet_addr_onlink
```
```
In net/ipv4/fib_frontend.c (ffffffff81d36e56)
Location: include/linux/inetdevice.h:203
Inline: True
Inline callers:
  - net/ipv4/fib_frontend.c:fib_del_ifaddr
  - net/ipv4/fib_frontend.c:fib_del_ifaddr
  - net/ipv4/fib_frontend.c:fib_del_ifaddr
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
In net/ipv4/devinet.c (ffffffff81eeda67)
Location: include/linux/inetdevice.h:203
Inline: True
Inline callers:
  - net/ipv4/devinet.c:confirm_addr_indev
  - net/ipv4/devinet.c:confirm_addr_indev
  - net/ipv4/devinet.c:confirm_addr_indev
  - net/ipv4/devinet.c:inet_select_addr
  - net/ipv4/devinet.c:inet_rtm_newaddr
  - net/ipv4/devinet.c:inet_rtm_deladdr
  - net/ipv4/devinet.c:inet_ifa_byprefix
  - net/ipv4/devinet.c:__inet_insert_ifa
  - net/ipv4/devinet.c:__inet_del_ifa
  - net/ipv4/devinet.c:__inet_del_ifa
  - net/ipv4/devinet.c:__inet_del_ifa
  - net/ipv4/devinet.c:inet_addr_onlink
  - net/ipv4/devinet.c:inet_addr_onlink
```
```
In net/ipv4/fib_frontend.c (ffffffff81eff506)
Location: include/linux/inetdevice.h:203
Inline: True
Inline callers:
  - net/ipv4/fib_frontend.c:fib_del_ifaddr
  - net/ipv4/fib_frontend.c:fib_del_ifaddr
  - net/ipv4/fib_frontend.c:fib_del_ifaddr
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
In net/ipv4/devinet.c (ffffffff81f4d427)
Location: include/linux/inetdevice.h:203
Inline: True
Inline callers:
  - net/ipv4/devinet.c:confirm_addr_indev
  - net/ipv4/devinet.c:confirm_addr_indev
  - net/ipv4/devinet.c:confirm_addr_indev
  - net/ipv4/devinet.c:inet_select_addr
  - net/ipv4/devinet.c:inet_rtm_newaddr
  - net/ipv4/devinet.c:inet_rtm_deladdr
  - net/ipv4/devinet.c:inet_ifa_byprefix
  - net/ipv4/devinet.c:__inet_insert_ifa
  - net/ipv4/devinet.c:__inet_del_ifa
  - net/ipv4/devinet.c:__inet_del_ifa
  - net/ipv4/devinet.c:__inet_del_ifa
  - net/ipv4/devinet.c:inet_addr_onlink
  - net/ipv4/devinet.c:inet_addr_onlink
```
```
In net/ipv4/fib_frontend.c (ffffffff81f5ef8f)
Location: include/linux/inetdevice.h:203
Inline: True
Inline callers:
  - net/ipv4/fib_frontend.c:fib_del_ifaddr
  - net/ipv4/fib_frontend.c:fib_del_ifaddr
  - net/ipv4/fib_frontend.c:fib_del_ifaddr
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
In net/ipv4/devinet.c (ffffffff82013537)
Location: include/linux/inetdevice.h:203
Inline: True
Inline callers:
  - net/ipv4/devinet.c:confirm_addr_indev
  - net/ipv4/devinet.c:confirm_addr_indev
  - net/ipv4/devinet.c:confirm_addr_indev
  - net/ipv4/devinet.c:inet_select_addr
  - net/ipv4/devinet.c:inet_rtm_newaddr
  - net/ipv4/devinet.c:inet_rtm_deladdr
  - net/ipv4/devinet.c:inet_ifa_byprefix
  - net/ipv4/devinet.c:__inet_insert_ifa
  - net/ipv4/devinet.c:__inet_del_ifa
  - net/ipv4/devinet.c:__inet_del_ifa
  - net/ipv4/devinet.c:__inet_del_ifa
  - net/ipv4/devinet.c:inet_addr_onlink
  - net/ipv4/devinet.c:inet_addr_onlink
```
```
In net/ipv4/fib_frontend.c (ffffffff8202555f)
Location: include/linux/inetdevice.h:203
Inline: True
Inline callers:
  - net/ipv4/fib_frontend.c:fib_del_ifaddr
  - net/ipv4/fib_frontend.c:fib_del_ifaddr
  - net/ipv4/fib_frontend.c:fib_del_ifaddr
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
In net/ipv4/devinet.c (ffff800010ca5498)
Location: include/linux/inetdevice.h:189
Inline: True
Inline callers:
  - net/ipv4/devinet.c:confirm_addr_indev
  - net/ipv4/devinet.c:confirm_addr_indev
  - net/ipv4/devinet.c:confirm_addr_indev
  - net/ipv4/devinet.c:inet_select_addr
  - net/ipv4/devinet.c:inet_rtm_newaddr
  - net/ipv4/devinet.c:inet_rtm_deladdr
  - net/ipv4/devinet.c:inet_ifa_byprefix
  - net/ipv4/devinet.c:__inet_insert_ifa
  - net/ipv4/devinet.c:__inet_del_ifa
  - net/ipv4/devinet.c:__inet_del_ifa
  - net/ipv4/devinet.c:__inet_del_ifa
  - net/ipv4/devinet.c:inet_addr_onlink
  - net/ipv4/devinet.c:inet_addr_onlink
```
```
In net/ipv4/fib_frontend.c (ffff800010cb5c58)
Location: include/linux/inetdevice.h:189
Inline: True
Inline callers:
  - net/ipv4/fib_frontend.c:fib_del_ifaddr
  - net/ipv4/fib_frontend.c:fib_del_ifaddr
  - net/ipv4/fib_frontend.c:fib_del_ifaddr
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
In net/ipv4/devinet.c (c0db1cd8)
Location: include/linux/inetdevice.h:189
Inline: True
Inline callers:
  - net/ipv4/devinet.c:confirm_addr_indev
  - net/ipv4/devinet.c:confirm_addr_indev
  - net/ipv4/devinet.c:confirm_addr_indev
  - net/ipv4/devinet.c:inet_select_addr
  - net/ipv4/devinet.c:inet_rtm_newaddr
  - net/ipv4/devinet.c:inet_rtm_deladdr
  - net/ipv4/devinet.c:inet_ifa_byprefix
  - net/ipv4/devinet.c:__inet_insert_ifa
  - net/ipv4/devinet.c:__inet_del_ifa
  - net/ipv4/devinet.c:__inet_del_ifa
  - net/ipv4/devinet.c:__inet_del_ifa
  - net/ipv4/devinet.c:inet_addr_onlink
  - net/ipv4/devinet.c:inet_addr_onlink
```
```
In net/ipv4/fib_frontend.c (c0dc167c)
Location: include/linux/inetdevice.h:189
Inline: True
Inline callers:
  - net/ipv4/fib_frontend.c:fib_del_ifaddr
  - net/ipv4/fib_frontend.c:fib_del_ifaddr
  - net/ipv4/fib_frontend.c:fib_del_ifaddr
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
In net/ipv4/devinet.c (c000000000db9230)
Location: include/linux/inetdevice.h:189
Inline: True
Inline callers:
  - net/ipv4/devinet.c:confirm_addr_indev
  - net/ipv4/devinet.c:confirm_addr_indev
  - net/ipv4/devinet.c:confirm_addr_indev
  - net/ipv4/devinet.c:inet_select_addr
  - net/ipv4/devinet.c:inet_rtm_newaddr
  - net/ipv4/devinet.c:inet_rtm_deladdr
  - net/ipv4/devinet.c:inet_ifa_byprefix
  - net/ipv4/devinet.c:__inet_insert_ifa
  - net/ipv4/devinet.c:__inet_del_ifa
  - net/ipv4/devinet.c:__inet_del_ifa
  - net/ipv4/devinet.c:__inet_del_ifa
  - net/ipv4/devinet.c:inet_addr_onlink
  - net/ipv4/devinet.c:inet_addr_onlink
```
```
In net/ipv4/fib_frontend.c (c000000000dcda60)
Location: include/linux/inetdevice.h:189
Inline: True
Inline callers:
  - net/ipv4/fib_frontend.c:fib_del_ifaddr
  - net/ipv4/fib_frontend.c:fib_del_ifaddr
  - net/ipv4/fib_frontend.c:fib_del_ifaddr
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
In net/ipv4/devinet.c (ffffffe000800cc2)
Location: include/linux/inetdevice.h:189
Inline: True
Inline callers:
  - net/ipv4/devinet.c:confirm_addr_indev
  - net/ipv4/devinet.c:confirm_addr_indev
  - net/ipv4/devinet.c:confirm_addr_indev
  - net/ipv4/devinet.c:inet_select_addr
  - net/ipv4/devinet.c:inet_rtm_newaddr
  - net/ipv4/devinet.c:inet_rtm_deladdr
  - net/ipv4/devinet.c:inet_ifa_byprefix
  - net/ipv4/devinet.c:__inet_insert_ifa
  - net/ipv4/devinet.c:__inet_del_ifa
  - net/ipv4/devinet.c:__inet_del_ifa
  - net/ipv4/devinet.c:__inet_del_ifa
  - net/ipv4/devinet.c:inet_addr_onlink
  - net/ipv4/devinet.c:inet_addr_onlink
```
```
In net/ipv4/fib_frontend.c (ffffffe00080d43c)
Location: include/linux/inetdevice.h:189
Inline: True
Inline callers:
  - net/ipv4/fib_frontend.c:fib_del_ifaddr
  - net/ipv4/fib_frontend.c:fib_del_ifaddr
  - net/ipv4/fib_frontend.c:fib_del_ifaddr
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
In net/ipv4/devinet.c (ffffffff8198f3a3)
Location: include/linux/inetdevice.h:189
Inline: True
Inline callers:
  - net/ipv4/devinet.c:confirm_addr_indev
  - net/ipv4/devinet.c:confirm_addr_indev
  - net/ipv4/devinet.c:confirm_addr_indev
  - net/ipv4/devinet.c:inet_select_addr
  - net/ipv4/devinet.c:inet_rtm_newaddr
  - net/ipv4/devinet.c:inet_rtm_deladdr
  - net/ipv4/devinet.c:inet_ifa_byprefix
  - net/ipv4/devinet.c:__inet_insert_ifa
  - net/ipv4/devinet.c:__inet_del_ifa
  - net/ipv4/devinet.c:__inet_del_ifa
  - net/ipv4/devinet.c:__inet_del_ifa
  - net/ipv4/devinet.c:inet_addr_onlink
  - net/ipv4/devinet.c:inet_addr_onlink
```
```
In net/ipv4/fib_frontend.c (ffffffff8199d865)
Location: include/linux/inetdevice.h:189
Inline: True
Inline callers:
  - net/ipv4/fib_frontend.c:fib_del_ifaddr
  - net/ipv4/fib_frontend.c:fib_del_ifaddr
  - net/ipv4/fib_frontend.c:fib_del_ifaddr
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
In net/ipv4/devinet.c (ffffffff81948e63)
Location: include/linux/inetdevice.h:189
Inline: True
Inline callers:
  - net/ipv4/devinet.c:confirm_addr_indev
  - net/ipv4/devinet.c:confirm_addr_indev
  - net/ipv4/devinet.c:confirm_addr_indev
  - net/ipv4/devinet.c:inet_select_addr
  - net/ipv4/devinet.c:inet_rtm_newaddr
  - net/ipv4/devinet.c:inet_rtm_deladdr
  - net/ipv4/devinet.c:inet_ifa_byprefix
  - net/ipv4/devinet.c:__inet_insert_ifa
  - net/ipv4/devinet.c:__inet_del_ifa
  - net/ipv4/devinet.c:__inet_del_ifa
  - net/ipv4/devinet.c:__inet_del_ifa
  - net/ipv4/devinet.c:inet_addr_onlink
  - net/ipv4/devinet.c:inet_addr_onlink
```
```
In net/ipv4/fib_frontend.c (ffffffff81957325)
Location: include/linux/inetdevice.h:189
Inline: True
Inline callers:
  - net/ipv4/fib_frontend.c:fib_del_ifaddr
  - net/ipv4/fib_frontend.c:fib_del_ifaddr
  - net/ipv4/fib_frontend.c:fib_del_ifaddr
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
In net/ipv4/devinet.c (ffffffff819f9c43)
Location: include/linux/inetdevice.h:189
Inline: True
Inline callers:
  - net/ipv4/devinet.c:confirm_addr_indev
  - net/ipv4/devinet.c:confirm_addr_indev
  - net/ipv4/devinet.c:confirm_addr_indev
  - net/ipv4/devinet.c:inet_select_addr
  - net/ipv4/devinet.c:inet_rtm_newaddr
  - net/ipv4/devinet.c:inet_rtm_deladdr
  - net/ipv4/devinet.c:inet_ifa_byprefix
  - net/ipv4/devinet.c:__inet_insert_ifa
  - net/ipv4/devinet.c:__inet_del_ifa
  - net/ipv4/devinet.c:__inet_del_ifa
  - net/ipv4/devinet.c:__inet_del_ifa
  - net/ipv4/devinet.c:inet_addr_onlink
  - net/ipv4/devinet.c:inet_addr_onlink
```
```
In net/ipv4/fib_frontend.c (ffffffff81a08105)
Location: include/linux/inetdevice.h:189
Inline: True
Inline callers:
  - net/ipv4/fib_frontend.c:fib_del_ifaddr
  - net/ipv4/fib_frontend.c:fib_del_ifaddr
  - net/ipv4/fib_frontend.c:fib_del_ifaddr
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
In net/ipv4/devinet.c (ffffffff81a03f33)
Location: include/linux/inetdevice.h:189
Inline: True
Inline callers:
  - net/ipv4/devinet.c:confirm_addr_indev
  - net/ipv4/devinet.c:confirm_addr_indev
  - net/ipv4/devinet.c:confirm_addr_indev
  - net/ipv4/devinet.c:inet_select_addr
  - net/ipv4/devinet.c:inet_rtm_newaddr
  - net/ipv4/devinet.c:inet_rtm_deladdr
  - net/ipv4/devinet.c:inet_ifa_byprefix
  - net/ipv4/devinet.c:__inet_insert_ifa
  - net/ipv4/devinet.c:__inet_del_ifa
  - net/ipv4/devinet.c:__inet_del_ifa
  - net/ipv4/devinet.c:__inet_del_ifa
  - net/ipv4/devinet.c:inet_addr_onlink
  - net/ipv4/devinet.c:inet_addr_onlink
```
```
In net/ipv4/fib_frontend.c (ffffffff81a12852)
Location: include/linux/inetdevice.h:189
Inline: True
Inline callers:
  - net/ipv4/fib_frontend.c:fib_del_ifaddr
  - net/ipv4/fib_frontend.c:fib_del_ifaddr
  - net/ipv4/fib_frontend.c:fib_del_ifaddr
```
</details>
</li>
</ul>

## Differences
