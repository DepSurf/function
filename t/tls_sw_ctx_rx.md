# Function: <code>tls_sw_ctx_rx</code>

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
<summary>In <code>5.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/core/skmsg.c (ffffffff81a3bbd8)
Location: include/net/tls.h:559
Inline: True
Inline callers:
  - net/core/skmsg.c:sk_psock_strp_data_ready
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
In net/core/filter.c (ffffffff81a2d464)
Location: include/net/tls.h:580
Inline: True
Inline callers:
  - net/core/filter.c:sk_skb_adjust_room
```
```
In net/core/skmsg.c (ffffffff81a3e568)
Location: include/net/tls.h:580
Inline: True
Inline callers:
  - net/core/skmsg.c:sk_psock_strp_data_ready
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
In net/core/filter.c (ffffffff81a15476)
Location: include/net/tls.h:588
Inline: True
Inline callers:
  - net/core/filter.c:sk_skb_adjust_room
```
```
In net/core/skmsg.c (ffffffff81a4c768)
Location: include/net/tls.h:588
Inline: True
Inline callers:
  - net/core/skmsg.c:sk_psock_strp_data_ready
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
In net/core/filter.c (ffffffff81ac6496)
Location: include/net/tls.h:581
Inline: True
Inline callers:
  - net/core/filter.c:sk_skb_adjust_room
```
```
In net/core/skmsg.c (ffffffff81b05088)
Location: include/net/tls.h:581
Inline: True
Inline callers:
  - net/core/skmsg.c:sk_psock_strp_data_ready
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
In net/core/filter.c (ffffffff81c42405)
Location: include/net/tls.h:580
Inline: True
Inline callers:
  - net/core/filter.c:sk_skb_adjust_room
```
```
In net/core/skmsg.c (ffffffff81c8a938)
Location: include/net/tls.h:580
Inline: True
Inline callers:
  - net/core/skmsg.c:sk_psock_strp_data_ready
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
In net/core/filter.c (ffffffff81df8595)
Location: include/net/tls.h:391
Inline: True
Inline callers:
  - net/core/filter.c:sk_skb_adjust_room
```
```
In net/core/skmsg.c (ffffffff81e45558)
Location: include/net/tls.h:391
Inline: True
Inline callers:
  - net/core/skmsg.c:sk_psock_strp_data_ready
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
In net/core/filter.c (ffffffff81e6a505)
Location: include/net/tls.h:396
Inline: True
Inline callers:
  - net/core/filter.c:sk_skb_adjust_room
```
```
In net/core/skmsg.c (ffffffff81ea1a7e)
Location: include/net/tls.h:396
Inline: True
Inline callers:
  - net/core/skmsg.c:sk_psock_strp_data_ready
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
In net/core/filter.c (ffffffff81f29495)
Location: include/net/tls.h:372
Inline: True
Inline callers:
  - net/core/filter.c:sk_skb_adjust_room
```
```
In net/core/skmsg.c (ffffffff81f6428e)
Location: include/net/tls.h:372
Inline: True
Inline callers:
  - net/core/skmsg.c:sk_psock_strp_data_ready
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
