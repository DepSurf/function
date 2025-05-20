# Function: <code>l3mdev_l3_out</code>

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
<details>
<summary>In <code>4.10</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv4/ip_output.c (ffffffff817f9fcc)
Location: include/net/l3mdev.h:167
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:__ip_local_out
```
```
In net/ipv6/ip6_output.c (ffffffff81863960)
Location: include/net/l3mdev.h:167
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_xmit
```
```
In net/ipv6/raw.c (ffffffff8188678e)
Location: include/net/l3mdev.h:167
Inline: True
Inline callers:
  - net/ipv6/raw.c:rawv6_sendmsg
```
```
In net/ipv6/output_core.c (ffffffff818a62b9)
Location: include/net/l3mdev.h:167
Inline: True
Inline callers:
  - net/ipv6/output_core.c:__ip6_local_out
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
In net/ipv4/ip_output.c (ffffffff8181a3cc)
Location: include/net/l3mdev.h:167
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:__ip_local_out
```
```
In net/ipv6/ip6_output.c (ffffffff81888f17)
Location: include/net/l3mdev.h:167
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_xmit
```
```
In net/ipv6/raw.c (ffffffff818acae9)
Location: include/net/l3mdev.h:167
Inline: True
Inline callers:
  - net/ipv6/raw.c:rawv6_sendmsg
```
```
In net/ipv6/output_core.c (ffffffff818ccd09)
Location: include/net/l3mdev.h:167
Inline: True
Inline callers:
  - net/ipv6/output_core.c:__ip6_local_out
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
In net/ipv4/ip_output.c (ffffffff8189938c)
Location: include/net/l3mdev.h:167
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:__ip_local_out
```
```
In net/ipv6/ip6_output.c (ffffffff8190932b)
Location: include/net/l3mdev.h:167
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_xmit
```
```
In net/ipv6/raw.c (ffffffff8192f346)
Location: include/net/l3mdev.h:167
Inline: True
Inline callers:
  - net/ipv6/raw.c:rawv6_sendmsg
```
```
In net/ipv6/output_core.c (ffffffff81951ae9)
Location: include/net/l3mdev.h:167
Inline: True
Inline callers:
  - net/ipv6/output_core.c:__ip6_local_out
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
In net/ipv4/ip_output.c (ffffffff818ed7dc)
Location: include/net/l3mdev.h:167
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:__ip_local_out
```
```
In net/ipv6/ip6_output.c (ffffffff8196066b)
Location: include/net/l3mdev.h:167
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_xmit
```
```
In net/ipv6/raw.c (ffffffff81987d28)
Location: include/net/l3mdev.h:167
Inline: True
Inline callers:
  - net/ipv6/raw.c:rawv6_sendmsg
```
```
In net/ipv6/output_core.c (ffffffff819ab086)
Location: include/net/l3mdev.h:167
Inline: True
Inline callers:
  - net/ipv6/output_core.c:__ip6_local_out
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
In net/ipv4/ip_output.c (ffffffff8191af99)
Location: include/net/l3mdev.h:179
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:__ip_local_out
```
```
In net/ipv6/ip6_output.c (ffffffff8199543f)
Location: include/net/l3mdev.h:179
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_xmit
```
```
In net/ipv6/raw.c (ffffffff819be686)
Location: include/net/l3mdev.h:179
Inline: True
Inline callers:
  - net/ipv6/raw.c:rawv6_sendmsg
```
```
In net/ipv6/output_core.c (ffffffff819e1ba3)
Location: include/net/l3mdev.h:179
Inline: True
Inline callers:
  - net/ipv6/output_core.c:__ip6_local_out
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
In net/ipv4/ip_output.c (ffffffff8197d239)
Location: include/net/l3mdev.h:175
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:__ip_local_out
```
```
In net/ipv6/ip6_output.c (ffffffff81a01d2e)
Location: include/net/l3mdev.h:175
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_xmit
```
```
In net/ipv6/raw.c (ffffffff81a2d0d4)
Location: include/net/l3mdev.h:175
Inline: True
```
```
In net/ipv6/output_core.c (ffffffff81a50969)
Location: include/net/l3mdev.h:175
Inline: True
Inline callers:
  - net/ipv6/output_core.c:__ip6_local_out
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
In net/ipv4/ip_output.c (ffffffff819b3be9)
Location: include/net/l3mdev.h:175
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:__ip_local_out
```
```
In net/ipv6/ip6_output.c (ffffffff81a38a8e)
Location: include/net/l3mdev.h:175
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_xmit
```
```
In net/ipv6/raw.c (ffffffff81a63c27)
Location: include/net/l3mdev.h:175
Inline: True
Inline callers:
  - net/ipv6/raw.c:rawv6_send_hdrinc
```
```
In net/ipv6/output_core.c (ffffffff81a87589)
Location: include/net/l3mdev.h:175
Inline: True
Inline callers:
  - net/ipv6/output_core.c:__ip6_local_out
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
In net/ipv4/ip_output.c (ffffffff81a9dce9)
Location: include/net/l3mdev.h:175
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:__ip_local_out
```
```
In net/ipv6/ip6_output.c (ffffffff81b2d8c3)
Location: include/net/l3mdev.h:175
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_xmit
```
```
In net/ipv6/raw.c (ffffffff81b5c6a6)
Location: include/net/l3mdev.h:175
Inline: True
Inline callers:
  - net/ipv6/raw.c:rawv6_send_hdrinc
```
```
In net/ipv6/output_core.c (ffffffff81b82997)
Location: include/net/l3mdev.h:175
Inline: True
Inline callers:
  - net/ipv6/output_core.c:__ip6_local_out
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
In net/ipv4/ip_output.c (ffffffff81aa7bbb)
Location: include/net/l3mdev.h:194
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:__ip_local_out
```
```
In net/ipv6/ip6_output.c (ffffffff81b3c2f3)
Location: include/net/l3mdev.h:194
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_xmit
```
```
In net/ipv6/raw.c (ffffffff81b6aee6)
Location: include/net/l3mdev.h:194
Inline: True
Inline callers:
  - net/ipv6/raw.c:rawv6_send_hdrinc
```
```
In net/ipv6/output_core.c (ffffffff81b91ff9)
Location: include/net/l3mdev.h:194
Inline: True
Inline callers:
  - net/ipv6/output_core.c:__ip6_local_out
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
In net/ipv4/ip_output.c (ffffffff81a92dab)
Location: include/net/l3mdev.h:194
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:__ip_local_out
```
```
In net/ipv6/ip6_output.c (ffffffff81b2c48b)
Location: include/net/l3mdev.h:194
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_xmit
```
```
In net/ipv6/raw.c (ffffffff81b591f8)
Location: include/net/l3mdev.h:194
Inline: True
Inline callers:
  - net/ipv6/raw.c:rawv6_send_hdrinc
```
```
In net/ipv6/output_core.c (ffffffff81b81289)
Location: include/net/l3mdev.h:194
Inline: True
Inline callers:
  - net/ipv6/output_core.c:__ip6_local_out
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
In net/ipv4/ip_output.c (ffffffff81b4e1ab)
Location: include/net/l3mdev.h:194
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:__ip_local_out
```
```
In net/ipv6/ip6_output.c (ffffffff81bf262a)
Location: include/net/l3mdev.h:194
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_xmit
```
```
In net/ipv6/raw.c (ffffffff81c20802)
Location: include/net/l3mdev.h:194
Inline: True
Inline callers:
  - net/ipv6/raw.c:rawv6_send_hdrinc
```
```
In net/ipv6/output_core.c (ffffffff81c4d2a9)
Location: include/net/l3mdev.h:194
Inline: True
Inline callers:
  - net/ipv6/output_core.c:__ip6_local_out
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
In net/ipv4/ip_output.c (ffffffff81cdba5d)
Location: include/net/l3mdev.h:194
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:__ip_local_out
```
```
In net/ipv6/ip6_output.c (ffffffff81d8b0df)
Location: include/net/l3mdev.h:194
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_xmit
```
```
In net/ipv6/raw.c (ffffffff81dbd580)
Location: include/net/l3mdev.h:194
Inline: True
Inline callers:
  - net/ipv6/raw.c:rawv6_send_hdrinc
```
```
In net/ipv6/output_core.c (ffffffff81ded7c5)
Location: include/net/l3mdev.h:194
Inline: True
Inline callers:
  - net/ipv6/output_core.c:__ip6_local_out
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
In net/ipv4/ip_output.c (ffffffff81e9c43d)
Location: include/net/l3mdev.h:194
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:__ip_local_out
```
```
In net/ipv6/ip6_output.c (ffffffff81f590df)
Location: include/net/l3mdev.h:194
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_xmit
```
```
In net/ipv6/raw.c (ffffffff81f8dabf)
Location: include/net/l3mdev.h:194
Inline: True
Inline callers:
  - net/ipv6/raw.c:rawv6_send_hdrinc
```
```
In net/ipv6/output_core.c (ffffffff81fc15f5)
Location: include/net/l3mdev.h:194
Inline: True
Inline callers:
  - net/ipv6/output_core.c:__ip6_local_out
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
In net/ipv4/ip_output.c (ffffffff81efb02c)
Location: include/net/l3mdev.h:194
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:__ip_local_out
```
```
In net/ipv6/ip6_output.c (ffffffff81fb8dad)
Location: include/net/l3mdev.h:194
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_xmit
```
```
In net/ipv6/raw.c (ffffffff81fee298)
Location: include/net/l3mdev.h:194
Inline: True
Inline callers:
  - net/ipv6/raw.c:rawv6_send_hdrinc
```
```
In net/ipv6/output_core.c (ffffffff82022575)
Location: include/net/l3mdev.h:194
Inline: True
Inline callers:
  - net/ipv6/output_core.c:__ip6_local_out
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
In net/ipv4/ip_output.c (ffffffff81fbef39)
Location: include/net/l3mdev.h:194
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:__ip_local_out
```
```
In net/ipv6/ip6_output.c (ffffffff82086339)
Location: include/net/l3mdev.h:194
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_xmit
```
```
In net/ipv6/raw.c (ffffffff820bbe6c)
Location: include/net/l3mdev.h:194
Inline: True
Inline callers:
  - net/ipv6/raw.c:rawv6_send_hdrinc
```
```
In net/ipv6/output_core.c (ffffffff820f1695)
Location: include/net/l3mdev.h:194
Inline: True
Inline callers:
  - net/ipv6/output_core.c:__ip6_local_out
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
In net/ipv4/ip_output.c (ffff800010c643e4)
Location: include/net/l3mdev.h:175
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:__ip_local_out
```
```
In net/ipv6/ip6_output.c (ffff800010cfaab0)
Location: include/net/l3mdev.h:175
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_xmit
```
```
In net/ipv6/raw.c (ffff800010d29c8c)
Location: include/net/l3mdev.h:175
Inline: True
Inline callers:
  - net/ipv6/raw.c:rawv6_send_hdrinc
```
```
In net/ipv6/output_core.c (ffff800010d53e68)
Location: include/net/l3mdev.h:175
Inline: True
Inline callers:
  - net/ipv6/output_core.c:__ip6_local_out
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
In net/ipv4/ip_output.c (c0d73f44)
Location: include/net/l3mdev.h:175
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:__ip_local_out
```
```
In net/ipv6/ip6_output.c (c0dfef40)
Location: include/net/l3mdev.h:175
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_xmit
```
```
In net/ipv6/raw.c (c0e2da5c)
Location: include/net/l3mdev.h:175
Inline: True
Inline callers:
  - net/ipv6/raw.c:rawv6_send_hdrinc
```
```
In net/ipv6/output_core.c (c0e54620)
Location: include/net/l3mdev.h:175
Inline: True
Inline callers:
  - net/ipv6/output_core.c:__ip6_local_out
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
In net/ipv4/ip_output.c (c000000000d683b8)
Location: include/net/l3mdev.h:175
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:__ip_local_out
```
```
In net/ipv6/ip6_output.c (c000000000e1fcf0)
Location: include/net/l3mdev.h:175
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_xmit
```
```
In net/ipv6/raw.c (c000000000e5aacc)
Location: include/net/l3mdev.h:175
Inline: True
Inline callers:
  - net/ipv6/raw.c:rawv6_send_hdrinc
```
```
In net/ipv6/output_core.c (c000000000e8c7c0)
Location: include/net/l3mdev.h:175
Inline: True
Inline callers:
  - net/ipv6/output_core.c:__ip6_local_out
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
In net/ipv4/ip_output.c (ffffffe0007cbdba)
Location: include/net/l3mdev.h:175
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:__ip_local_out
```
```
In net/ipv6/ip6_output.c (ffffffe000843994)
Location: include/net/l3mdev.h:175
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_xmit
```
```
In net/ipv6/raw.c (ffffffe00086a4ac)
Location: include/net/l3mdev.h:175
Inline: True
Inline callers:
  - net/ipv6/raw.c:rawv6_send_hdrinc
```
```
In net/ipv6/output_core.c (ffffffe00088b9ae)
Location: include/net/l3mdev.h:175
Inline: True
Inline callers:
  - net/ipv6/output_core.c:__ip6_local_out
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
In net/ipv4/ip_output.c (ffffffff81953a59)
Location: include/net/l3mdev.h:175
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:__ip_local_out
```
```
In net/ipv6/ip6_output.c (ffffffff819d811e)
Location: include/net/l3mdev.h:175
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_xmit
```
```
In net/ipv6/raw.c (ffffffff81a032b7)
Location: include/net/l3mdev.h:175
Inline: True
Inline callers:
  - net/ipv6/raw.c:rawv6_send_hdrinc
```
```
In net/ipv6/output_core.c (ffffffff81a26c19)
Location: include/net/l3mdev.h:175
Inline: True
Inline callers:
  - net/ipv6/output_core.c:__ip6_local_out
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
In net/ipv4/ip_output.c (ffffffff8190d549)
Location: include/net/l3mdev.h:175
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:__ip_local_out
```
```
In net/ipv6/ip6_output.c (ffffffff81994ede)
Location: include/net/l3mdev.h:175
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_xmit
```
```
In net/ipv6/raw.c (ffffffff819c0077)
Location: include/net/l3mdev.h:175
Inline: True
Inline callers:
  - net/ipv6/raw.c:rawv6_send_hdrinc
```
```
In net/ipv6/output_core.c (ffffffff819e39d9)
Location: include/net/l3mdev.h:175
Inline: True
Inline callers:
  - net/ipv6/output_core.c:__ip6_local_out
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
In net/ipv4/ip_output.c (ffffffff819be229)
Location: include/net/l3mdev.h:175
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:__ip_local_out
```
```
In net/ipv6/ip6_output.c (ffffffff81a42b9e)
Location: include/net/l3mdev.h:175
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_xmit
```
```
In net/ipv6/raw.c (ffffffff81a6dd37)
Location: include/net/l3mdev.h:175
Inline: True
Inline callers:
  - net/ipv6/raw.c:rawv6_send_hdrinc
```
```
In net/ipv6/output_core.c (ffffffff81a927c9)
Location: include/net/l3mdev.h:175
Inline: True
Inline callers:
  - net/ipv6/output_core.c:__ip6_local_out
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
In net/ipv4/ip_output.c (ffffffff819c7b3d)
Location: include/net/l3mdev.h:175
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:__ip_local_out
```
```
In net/ipv6/ip6_output.c (ffffffff81a4e82e)
Location: include/net/l3mdev.h:175
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_xmit
```
```
In net/ipv6/raw.c (ffffffff81a7a357)
Location: include/net/l3mdev.h:175
Inline: True
Inline callers:
  - net/ipv6/raw.c:rawv6_send_hdrinc
```
```
In net/ipv6/output_core.c (ffffffff81a9e8ad)
Location: include/net/l3mdev.h:175
Inline: True
Inline callers:
  - net/ipv6/output_core.c:__ip6_local_out
```
</details>
</li>
</ul>

## Differences
