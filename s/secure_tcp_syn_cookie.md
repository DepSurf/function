# Function: <code>secure_tcp_syn_cookie</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Collision, Full Inline ⚠️</summary>

**Collision:** Static-Static Collision

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv4/syncookies.c (ffffffff817aaf5f)
Location: net/ipv4/syncookies.c:108
Inline: True
Inline callers:
  - net/ipv4/syncookies.c:__cookie_v4_init_sequence
```
```
In net/ipv6/syncookies.c (ffffffff817ff09f)
Location: net/ipv6/syncookies.c:71
Inline: True
Inline callers:
  - net/ipv6/syncookies.c:__cookie_v6_init_sequence
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Collision, Full Inline ⚠️</summary>

**Collision:** Static-Static Collision

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv4/syncookies.c (ffffffff81818a57)
Location: net/ipv4/syncookies.c:105
Inline: True
Inline callers:
  - net/ipv4/syncookies.c:__cookie_v4_init_sequence
```
```
In net/ipv6/syncookies.c (ffffffff8186ea27)
Location: net/ipv6/syncookies.c:70
Inline: True
Inline callers:
  - net/ipv6/syncookies.c:__cookie_v6_init_sequence
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Collision, Full Inline ⚠️</summary>

**Collision:** Static-Static Collision

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv4/syncookies.c (ffffffff8184a2b7)
Location: net/ipv4/syncookies.c:105
Inline: True
Inline callers:
  - net/ipv4/syncookies.c:__cookie_v4_init_sequence
```
```
In net/ipv6/syncookies.c (ffffffff818a1977)
Location: net/ipv6/syncookies.c:70
Inline: True
Inline callers:
  - net/ipv6/syncookies.c:__cookie_v6_init_sequence
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Collision, Full Inline ⚠️</summary>

**Collision:** Static-Static Collision

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv4/syncookies.c (ffffffff8186dc65)
Location: net/ipv4/syncookies.c:95
Inline: True
Inline callers:
  - net/ipv4/syncookies.c:__cookie_v4_init_sequence
```
```
In net/ipv6/syncookies.c (ffffffff818c7f35)
Location: net/ipv6/syncookies.c:68
Inline: True
Inline callers:
  - net/ipv6/syncookies.c:__cookie_v6_init_sequence
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Collision, Full Inline ⚠️</summary>

**Collision:** Static-Static Collision

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv4/syncookies.c (ffffffff818ee5b5)
Location: net/ipv4/syncookies.c:95
Inline: True
Inline callers:
  - net/ipv4/syncookies.c:__cookie_v4_init_sequence
```
```
In net/ipv6/syncookies.c (ffffffff8194b4e5)
Location: net/ipv6/syncookies.c:68
Inline: True
Inline callers:
  - net/ipv6/syncookies.c:__cookie_v6_init_sequence
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Collision, Full Inline ⚠️</summary>

**Collision:** Static-Static Collision

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv4/syncookies.c (ffffffff81944f61)
Location: net/ipv4/syncookies.c:95
Inline: True
Inline callers:
  - net/ipv4/syncookies.c:__cookie_v4_init_sequence
```
```
In net/ipv6/syncookies.c (ffffffff819a479e)
Location: net/ipv6/syncookies.c:68
Inline: True
Inline callers:
  - net/ipv6/syncookies.c:__cookie_v6_init_sequence
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Collision, Full Inline ⚠️</summary>

**Collision:** Static-Static Collision

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv4/syncookies.c (ffffffff81975251)
Location: net/ipv4/syncookies.c:95
Inline: True
Inline callers:
  - net/ipv4/syncookies.c:__cookie_v4_init_sequence
```
```
In net/ipv6/syncookies.c (ffffffff819db2ae)
Location: net/ipv6/syncookies.c:68
Inline: True
Inline callers:
  - net/ipv6/syncookies.c:__cookie_v6_init_sequence
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Collision, Full Inline ⚠️</summary>

**Collision:** Static-Static Collision

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv4/syncookies.c (ffffffff819dee02)
Location: net/ipv4/syncookies.c:91
Inline: True
Inline callers:
  - net/ipv4/syncookies.c:__cookie_v4_init_sequence
```
```
In net/ipv6/syncookies.c (ffffffff81a49f38)
Location: net/ipv6/syncookies.c:63
Inline: True
Inline callers:
  - net/ipv6/syncookies.c:__cookie_v6_init_sequence
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Collision, Full Inline ⚠️</summary>

**Collision:** Static-Static Collision

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv4/syncookies.c (ffffffff81a15ea2)
Location: net/ipv4/syncookies.c:91
Inline: True
Inline callers:
  - net/ipv4/syncookies.c:__cookie_v4_init_sequence
```
```
In net/ipv6/syncookies.c (ffffffff81a80af8)
Location: net/ipv6/syncookies.c:63
Inline: True
Inline callers:
  - net/ipv6/syncookies.c:__cookie_v6_init_sequence
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Collision, Full Inline ⚠️</summary>

**Collision:** Static-Static Collision

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv4/syncookies.c (ffffffff81b06f12)
Location: net/ipv4/syncookies.c:91
Inline: True
Inline callers:
  - net/ipv4/syncookies.c:__cookie_v4_init_sequence
```
```
In net/ipv6/syncookies.c (ffffffff81b7b857)
Location: net/ipv6/syncookies.c:63
Inline: True
Inline callers:
  - net/ipv6/syncookies.c:__cookie_v6_init_sequence
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Collision, Full Inline ⚠️</summary>

**Collision:** Static-Static Collision

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv4/syncookies.c (ffffffff81b1511c)
Location: net/ipv4/syncookies.c:91
Inline: True
Inline callers:
  - net/ipv4/syncookies.c:__cookie_v4_init_sequence
```
```
In net/ipv6/syncookies.c (ffffffff81b8a8a1)
Location: net/ipv6/syncookies.c:63
Inline: True
Inline callers:
  - net/ipv6/syncookies.c:__cookie_v6_init_sequence
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Collision, Full Inline ⚠️</summary>

**Collision:** Static-Static Collision

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv4/syncookies.c (ffffffff81b02f24)
Location: net/ipv4/syncookies.c:91
Inline: True
Inline callers:
  - net/ipv4/syncookies.c:__cookie_v4_init_sequence
```
```
In net/ipv6/syncookies.c (ffffffff81b796fe)
Location: net/ipv6/syncookies.c:63
Inline: True
Inline callers:
  - net/ipv6/syncookies.c:__cookie_v6_init_sequence
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Collision, Full Inline ⚠️</summary>

**Collision:** Static-Static Collision

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv4/syncookies.c (ffffffff81bc515c)
Location: net/ipv4/syncookies.c:91
Inline: True
Inline callers:
  - net/ipv4/syncookies.c:__cookie_v4_init_sequence
```
```
In net/ipv6/syncookies.c (ffffffff81c4439b)
Location: net/ipv6/syncookies.c:63
Inline: True
Inline callers:
  - net/ipv6/syncookies.c:__cookie_v6_init_sequence
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Collision, Full Inline ⚠️</summary>

**Collision:** Static-Static Collision

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv4/syncookies.c (ffffffff81d5a2c9)
Location: net/ipv4/syncookies.c:89
Inline: True
Inline callers:
  - net/ipv4/syncookies.c:__cookie_v4_init_sequence
```
```
In net/ipv6/syncookies.c (ffffffff81de331f)
Location: net/ipv6/syncookies.c:63
Inline: True
Inline callers:
  - net/ipv6/syncookies.c:__cookie_v6_init_sequence
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Collision, Full Inline ⚠️</summary>

**Collision:** Static-Static Collision

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv4/syncookies.c (ffffffff81f246c9)
Location: net/ipv4/syncookies.c:89
Inline: True
Inline callers:
  - net/ipv4/syncookies.c:__cookie_v4_init_sequence
```
```
In net/ipv6/syncookies.c (ffffffff81fb597f)
Location: net/ipv6/syncookies.c:63
Inline: True
Inline callers:
  - net/ipv6/syncookies.c:__cookie_v6_init_sequence
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Collision, Full Inline ⚠️</summary>

**Collision:** Static-Static Collision

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv4/syncookies.c (ffffffff81f84258)
Location: net/ipv4/syncookies.c:89
Inline: True
Inline callers:
  - net/ipv4/syncookies.c:__cookie_v4_init_sequence
```
```
In net/ipv6/syncookies.c (ffffffff820160c5)
Location: net/ipv6/syncookies.c:63
Inline: True
Inline callers:
  - net/ipv6/syncookies.c:__cookie_v6_init_sequence
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Collision, Full Inline ⚠️</summary>

**Collision:** Static-Static Collision

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv4/syncookies.c (ffffffff8204a908)
Location: net/ipv4/syncookies.c:93
Inline: True
Inline callers:
  - net/ipv4/syncookies.c:__cookie_v4_init_sequence
```
```
In net/ipv6/syncookies.c (ffffffff820e5205)
Location: net/ipv6/syncookies.c:63
Inline: True
Inline callers:
  - net/ipv6/syncookies.c:__cookie_v6_init_sequence
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Collision, Full Inline ⚠️</summary>

**Collision:** Static-Static Collision

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv4/syncookies.c (ffff800010cd1b00)
Location: net/ipv4/syncookies.c:91
Inline: True
Inline callers:
  - net/ipv4/syncookies.c:__cookie_v4_init_sequence
```
```
In net/ipv6/syncookies.c (ffff800010d4c388)
Location: net/ipv6/syncookies.c:63
Inline: True
Inline callers:
  - net/ipv6/syncookies.c:__cookie_v6_init_sequence
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Collision, Full Inline ⚠️</summary>

**Collision:** Static-Static Collision

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv4/syncookies.c (c0ddb9c8)
Location: net/ipv4/syncookies.c:91
Inline: True
Inline callers:
  - net/ipv4/syncookies.c:__cookie_v4_init_sequence
```
```
In net/ipv6/syncookies.c (c0e4d55c)
Location: net/ipv6/syncookies.c:63
Inline: True
Inline callers:
  - net/ipv6/syncookies.c:__cookie_v6_init_sequence
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Collision, Full Inline ⚠️</summary>

**Collision:** Static-Static Collision

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv4/syncookies.c (c000000000defd74)
Location: net/ipv4/syncookies.c:91
Inline: True
Inline callers:
  - net/ipv4/syncookies.c:__cookie_v4_init_sequence
```
```
In net/ipv6/syncookies.c (c000000000e82984)
Location: net/ipv6/syncookies.c:63
Inline: True
Inline callers:
  - net/ipv6/syncookies.c:__cookie_v6_init_sequence
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Collision, Full Inline ⚠️</summary>

**Collision:** Static-Static Collision

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv4/syncookies.c (ffffffe000822f18)
Location: net/ipv4/syncookies.c:91
Inline: True
Inline callers:
  - net/ipv4/syncookies.c:__cookie_v4_init_sequence
```
```
In net/ipv6/syncookies.c (ffffffe0008850ba)
Location: net/ipv6/syncookies.c:63
Inline: True
Inline callers:
  - net/ipv6/syncookies.c:__cookie_v6_init_sequence
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Collision, Full Inline ⚠️</summary>

**Collision:** Static-Static Collision

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv4/syncookies.c (ffffffff819b5532)
Location: net/ipv4/syncookies.c:91
Inline: True
Inline callers:
  - net/ipv4/syncookies.c:__cookie_v4_init_sequence
```
```
In net/ipv6/syncookies.c (ffffffff81a20188)
Location: net/ipv6/syncookies.c:63
Inline: True
Inline callers:
  - net/ipv6/syncookies.c:__cookie_v6_init_sequence
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Collision, Full Inline ⚠️</summary>

**Collision:** Static-Static Collision

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv4/syncookies.c (ffffffff81972322)
Location: net/ipv4/syncookies.c:91
Inline: True
Inline callers:
  - net/ipv4/syncookies.c:__cookie_v4_init_sequence
```
```
In net/ipv6/syncookies.c (ffffffff819dcf48)
Location: net/ipv6/syncookies.c:63
Inline: True
Inline callers:
  - net/ipv6/syncookies.c:__cookie_v6_init_sequence
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Collision, Full Inline ⚠️</summary>

**Collision:** Static-Static Collision

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv4/syncookies.c (ffffffff81a1fdd2)
Location: net/ipv4/syncookies.c:91
Inline: True
Inline callers:
  - net/ipv4/syncookies.c:__cookie_v4_init_sequence
```
```
In net/ipv6/syncookies.c (ffffffff81a8ac08)
Location: net/ipv6/syncookies.c:63
Inline: True
Inline callers:
  - net/ipv6/syncookies.c:__cookie_v6_init_sequence
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Collision, Full Inline ⚠️</summary>

**Collision:** Static-Static Collision

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv4/syncookies.c (ffffffff81a2b2d2)
Location: net/ipv4/syncookies.c:91
Inline: True
Inline callers:
  - net/ipv4/syncookies.c:__cookie_v4_init_sequence
```
```
In net/ipv6/syncookies.c (ffffffff81a97868)
Location: net/ipv6/syncookies.c:63
Inline: True
Inline callers:
  - net/ipv6/syncookies.c:__cookie_v6_init_sequence
```
</details>
</li>
</ul>

## Differences
