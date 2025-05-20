# Function: <code>seg6_update_csum</code>

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
<summary>In <code>4.10</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv6/exthdrs.c (ffffffff81894c61)
Location: net/ipv6/exthdrs.c:294
Inline: True
Inline callers:
  - net/ipv6/exthdrs.c:ipv6_rthdr_rcv
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
In net/ipv6/exthdrs.c (ffffffff818baf16)
Location: net/ipv6/exthdrs.c:294
Inline: True
Inline callers:
  - net/ipv6/exthdrs.c:ipv6_rthdr_rcv
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv6/exthdrs.c (ffffffff8193df26)
Location: net/ipv6/exthdrs.c:327
Inline: True
Inline callers:
  - net/ipv6/exthdrs.c:ipv6_rthdr_rcv
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
In net/ipv6/exthdrs.c (ffffffff81996e52)
Location: net/ipv6/exthdrs.c:327
Inline: True
Inline callers:
  - net/ipv6/exthdrs.c:ipv6_rthdr_rcv
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
In net/ipv6/exthdrs.c (ffffffff819cd746)
Location: net/ipv6/exthdrs.c:327
Inline: True
Inline callers:
  - net/ipv6/exthdrs.c:ipv6_rthdr_rcv
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
In net/ipv6/exthdrs.c (ffffffff81a3be9d)
Location: net/ipv6/exthdrs.c:323
Inline: True
Inline callers:
  - net/ipv6/exthdrs.c:ipv6_srh_rcv
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
In net/ipv6/exthdrs.c (ffffffff81a72b1d)
Location: net/ipv6/exthdrs.c:323
Inline: True
Inline callers:
  - net/ipv6/exthdrs.c:ipv6_srh_rcv
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void seg6_update_csum(struct sk_buff *skb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/exthdrs.c (ffffffff81b6b990)
Location: net/ipv6/exthdrs.c:324
Inline: False
Direct callers:
  - net/ipv6/exthdrs.c:ipv6_srh_rcv
```
**Symbols:**

```
ffffffff81b6b990-ffffffff81b6ba7d: seg6_update_csum (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void seg6_update_csum(struct sk_buff *skb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/exthdrs.c (ffffffff81b7a420)
Location: net/ipv6/exthdrs.c:324
Inline: False
Direct callers:
  - net/ipv6/exthdrs.c:ipv6_srh_rcv
```
**Symbols:**

```
ffffffff81b7a420-ffffffff81b7a50d: seg6_update_csum (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv6/exthdrs.c (ffffffff81b69b69)
Location: net/ipv6/exthdrs.c:323
Inline: True
Inline callers:
  - net/ipv6/exthdrs.c:ipv6_srh_rcv
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
In net/ipv6/exthdrs.c (ffffffff81c319c9)
Location: net/ipv6/exthdrs.c:334
Inline: True
Inline callers:
  - net/ipv6/exthdrs.c:ipv6_srh_rcv
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
In net/ipv6/exthdrs.c (ffffffff81dcf210)
Location: net/ipv6/exthdrs.c:340
Inline: True
Inline callers:
  - net/ipv6/exthdrs.c:ipv6_srh_rcv
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
In net/ipv6/exthdrs.c (ffffffff81fa0580)
Location: net/ipv6/exthdrs.c:340
Inline: True
Inline callers:
  - net/ipv6/exthdrs.c:ipv6_srh_rcv
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
In net/ipv6/exthdrs.c (ffffffff8200101b)
Location: net/ipv6/exthdrs.c:337
Inline: True
Inline callers:
  - net/ipv6/exthdrs.c:ipv6_srh_rcv
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
In net/ipv6/exthdrs.c (ffffffff820cfe5b)
Location: net/ipv6/exthdrs.c:339
Inline: True
Inline callers:
  - net/ipv6/exthdrs.c:ipv6_srh_rcv
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
In net/ipv6/exthdrs.c (ffff800010d3b670)
Location: net/ipv6/exthdrs.c:323
Inline: True
Inline callers:
  - net/ipv6/exthdrs.c:ipv6_srh_rcv
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv6/exthdrs.c (c0e3db9c)
Location: net/ipv6/exthdrs.c:323
Inline: True
Inline callers:
  - net/ipv6/exthdrs.c:ipv6_srh_rcv
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
In net/ipv6/exthdrs.c (c000000000e6edb4)
Location: net/ipv6/exthdrs.c:323
Inline: True
Inline callers:
  - net/ipv6/exthdrs.c:ipv6_srh_rcv
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
In net/ipv6/exthdrs.c (ffffffe000877f9a)
Location: net/ipv6/exthdrs.c:323
Inline: True
Inline callers:
  - net/ipv6/exthdrs.c:ipv6_srh_rcv
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
In net/ipv6/exthdrs.c (ffffffff81a121ad)
Location: net/ipv6/exthdrs.c:323
Inline: True
Inline callers:
  - net/ipv6/exthdrs.c:ipv6_srh_rcv
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
In net/ipv6/exthdrs.c (ffffffff819cef6d)
Location: net/ipv6/exthdrs.c:323
Inline: True
Inline callers:
  - net/ipv6/exthdrs.c:ipv6_srh_rcv
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
In net/ipv6/exthdrs.c (ffffffff81a7cc2d)
Location: net/ipv6/exthdrs.c:323
Inline: True
Inline callers:
  - net/ipv6/exthdrs.c:ipv6_srh_rcv
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
In net/ipv6/exthdrs.c (ffffffff81a8947d)
Location: net/ipv6/exthdrs.c:323
Inline: True
Inline callers:
  - net/ipv6/exthdrs.c:ipv6_srh_rcv
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>5.8</code> and <code>5.11</code> ✅
</li>
</ul>
