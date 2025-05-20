# Function: <code>xdp_data_meta_unsupported</code>

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
In net/core/filter.c (0)
Location: include/linux/filter.h:743
Inline: True
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
In net/core/filter.c (0)
Location: include/net/xdp.h:142
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
In net/core/filter.c (0)
Location: include/net/xdp.h:151
Inline: True
```
```
In net/core/xdp.c (ffffffff818e1b85)
Location: include/net/xdp.h:151
Inline: True
Inline callers:
  - net/core/xdp.c:xdp_convert_zc_to_xdp_frame
```
```
In net/xdp/xsk.c (ffffffff81a0571f)
Location: include/net/xdp.h:151
Inline: True
Inline callers:
  - net/xdp/xsk.c:xsk_rcv
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
In net/core/filter.c (0)
Location: include/net/xdp.h:166
Inline: True
```
```
In net/core/xdp.c (ffffffff81930605)
Location: include/net/xdp.h:166
Inline: True
Inline callers:
  - net/core/xdp.c:xdp_convert_zc_to_xdp_frame
```
```
In net/xdp/xsk.c (ffffffff81a75035)
Location: include/net/xdp.h:166
Inline: True
Inline callers:
  - net/xdp/xsk.c:xsk_rcv
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
In net/core/filter.c (0)
Location: include/net/xdp.h:166
Inline: True
```
```
In net/core/xdp.c (ffffffff81962765)
Location: include/net/xdp.h:166
Inline: True
Inline callers:
  - net/core/xdp.c:xdp_convert_zc_to_xdp_frame
```
```
In net/xdp/xsk.c (ffffffff81aabdb2)
Location: include/net/xdp.h:166
Inline: True
Inline callers:
  - net/xdp/xsk.c:xsk_rcv
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
In net/core/filter.c (ffffffff81a2986f)
Location: include/net/xdp.h:201
Inline: True
Inline callers:
  - net/core/filter.c:bpf_xdp_adjust_head
```
```
In net/core/xdp.c (ffffffff81a356b5)
Location: include/net/xdp.h:201
Inline: True
Inline callers:
  - net/core/xdp.c:xdp_convert_zc_to_xdp_frame
```
```
In net/xdp/xsk.c (0)
Location: include/net/xdp.h:201
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
In net/core/filter.c (ffffffff81a2a1cf)
Location: include/net/xdp.h:248
Inline: True
Inline callers:
  - net/core/filter.c:bpf_xdp_adjust_head
```
```
In net/core/xdp.c (ffffffff81a37a55)
Location: include/net/xdp.h:248
Inline: True
Inline callers:
  - net/core/xdp.c:xdp_convert_zc_to_xdp_frame
```
```
In net/xdp/xsk.c (0)
Location: include/net/xdp.h:248
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
In net/core/filter.c (ffffffff81a1142f)
Location: include/net/xdp.h:273
Inline: True
Inline callers:
  - net/core/filter.c:bpf_xdp_adjust_head
```
```
In net/core/xdp.c (ffffffff81a1ebe5)
Location: include/net/xdp.h:273
Inline: True
Inline callers:
  - net/core/xdp.c:xdp_convert_zc_to_xdp_frame
```
```
In net/xdp/xsk.c (0)
Location: include/net/xdp.h:273
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
In net/core/filter.c (ffffffff81ac288f)
Location: include/net/xdp.h:274
Inline: True
Inline callers:
  - net/core/filter.c:bpf_xdp_adjust_head
```
```
In net/core/xdp.c (ffffffff81ad2c85)
Location: include/net/xdp.h:274
Inline: True
Inline callers:
  - net/core/xdp.c:xdp_convert_zc_to_xdp_frame
```
```
In net/xdp/xsk.c (0)
Location: include/net/xdp.h:274
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
In net/core/filter.c (ffffffff81c3d45f)
Location: include/net/xdp.h:391
Inline: True
Inline callers:
  - net/core/filter.c:bpf_xdp_adjust_head
```
```
In net/core/xdp.c (ffffffff81c507a5)
Location: include/net/xdp.h:391
Inline: True
Inline callers:
  - net/core/xdp.c:xdp_convert_zc_to_xdp_frame
```
```
In net/xdp/xsk.c (0)
Location: include/net/xdp.h:391
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
In net/core/filter.c (ffffffff81df39af)
Location: include/net/xdp.h:391
Inline: True
Inline callers:
  - net/core/filter.c:bpf_xdp_adjust_head
```
```
In net/core/xdp.c (ffffffff81e05c25)
Location: include/net/xdp.h:391
Inline: True
Inline callers:
  - net/core/xdp.c:xdp_convert_zc_to_xdp_frame
```
```
In net/xdp/xsk.c (0)
Location: include/net/xdp.h:391
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
In net/core/filter.c (ffffffff81e657df)
Location: include/net/xdp.h:366
Inline: True
Inline callers:
  - net/core/filter.c:bpf_xdp_adjust_head
```
```
In net/core/xdp.c (ffffffff81e78555)
Location: include/net/xdp.h:366
Inline: True
Inline callers:
  - net/core/xdp.c:xdp_convert_zc_to_xdp_frame
```
```
In net/xdp/xsk.c (0)
Location: include/net/xdp.h:366
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
In net/core/filter.c (ffffffff81f2498f)
Location: include/net/xdp.h:365
Inline: True
Inline callers:
  - net/core/filter.c:bpf_xdp_adjust_head
```
```
In net/core/xdp.c (ffffffff81f39155)
Location: include/net/xdp.h:365
Inline: True
Inline callers:
  - net/core/xdp.c:xdp_convert_zc_to_xdp_frame
```
```
In net/xdp/xsk.c (ffffffff8213d726)
Location: include/net/xdp.h:365
Inline: True
Inline callers:
  - net/xdp/xsk.c:__xsk_rcv
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
In net/core/filter.c (0)
Location: include/net/xdp.h:166
Inline: True
```
```
In net/core/xdp.c (ffff800010c07090)
Location: include/net/xdp.h:166
Inline: True
Inline callers:
  - net/core/xdp.c:xdp_convert_zc_to_xdp_frame
```
```
In net/xdp/xsk.c (ffff800010d804cc)
Location: include/net/xdp.h:166
Inline: True
Inline callers:
  - net/xdp/xsk.c:xsk_rcv
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
In net/core/filter.c (c0d11338)
Location: include/net/xdp.h:166
Inline: True
Inline callers:
  - net/core/filter.c:bpf_xdp_adjust_head
```
```
In net/core/xdp.c (c0d2027c)
Location: include/net/xdp.h:166
Inline: True
Inline callers:
  - net/core/xdp.c:xdp_convert_zc_to_xdp_frame
```
```
In net/xdp/xsk.c (c0e7a848)
Location: include/net/xdp.h:166
Inline: True
Inline callers:
  - net/xdp/xsk.c:xsk_rcv
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
In net/core/filter.c (0)
Location: include/net/xdp.h:166
Inline: True
```
```
In net/core/xdp.c (c000000000cf1928)
Location: include/net/xdp.h:166
Inline: True
Inline callers:
  - net/core/xdp.c:xdp_convert_zc_to_xdp_frame
```
```
In net/xdp/xsk.c (c000000000ebffe4)
Location: include/net/xdp.h:166
Inline: True
Inline callers:
  - net/xdp/xsk.c:xsk_rcv
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
In net/core/filter.c (0)
Location: include/net/xdp.h:166
Inline: True
```
```
In net/core/xdp.c (ffffffe000785476)
Location: include/net/xdp.h:166
Inline: True
Inline callers:
  - net/core/xdp.c:xdp_convert_zc_to_xdp_frame
```
```
In net/xdp/xsk.c (ffffffe0008accb6)
Location: include/net/xdp.h:166
Inline: True
Inline callers:
  - net/xdp/xsk.c:xsk_rcv
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
In net/core/filter.c (0)
Location: include/net/xdp.h:166
Inline: True
```
```
In net/core/xdp.c (ffffffff81902735)
Location: include/net/xdp.h:166
Inline: True
Inline callers:
  - net/core/xdp.c:xdp_convert_zc_to_xdp_frame
```
```
In net/xdp/xsk.c (ffffffff81a4b142)
Location: include/net/xdp.h:166
Inline: True
Inline callers:
  - net/xdp/xsk.c:xsk_rcv
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
In net/core/filter.c (0)
Location: include/net/xdp.h:166
Inline: True
```
```
In net/core/xdp.c (ffffffff818bc565)
Location: include/net/xdp.h:166
Inline: True
Inline callers:
  - net/core/xdp.c:xdp_convert_zc_to_xdp_frame
```
```
In net/xdp/xsk.c (ffffffff81a07d32)
Location: include/net/xdp.h:166
Inline: True
Inline callers:
  - net/xdp/xsk.c:xsk_rcv
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
In net/core/filter.c (0)
Location: include/net/xdp.h:166
Inline: True
```
```
In net/core/xdp.c (ffffffff81953765)
Location: include/net/xdp.h:166
Inline: True
Inline callers:
  - net/core/xdp.c:xdp_convert_zc_to_xdp_frame
```
```
In net/xdp/xsk.c (ffffffff81ab6ff2)
Location: include/net/xdp.h:166
Inline: True
Inline callers:
  - net/xdp/xsk.c:xsk_rcv
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
In net/core/filter.c (0)
Location: include/net/xdp.h:166
Inline: True
```
```
In net/core/xdp.c (ffffffff81975285)
Location: include/net/xdp.h:166
Inline: True
Inline callers:
  - net/core/xdp.c:xdp_convert_zc_to_xdp_frame
```
```
In net/xdp/xsk.c (ffffffff81ac3412)
Location: include/net/xdp.h:166
Inline: True
Inline callers:
  - net/xdp/xsk.c:xsk_rcv
```
</details>
</li>
</ul>

## Differences
