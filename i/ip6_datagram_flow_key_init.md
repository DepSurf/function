# Function: <code>ip6_datagram_flow_key_init</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>4.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv6/datagram.c (ffffffff818634ac)
Location: net/ipv6/datagram.c:43
Inline: True
Inline callers:
  - net/ipv6/datagram.c:ip6_datagram_dst_update
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
In net/ipv6/datagram.c (ffffffff81895abc)
Location: net/ipv6/datagram.c:43
Inline: True
Inline callers:
  - net/ipv6/datagram.c:ip6_datagram_dst_update
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
In net/ipv6/datagram.c (ffffffff818bc036)
Location: net/ipv6/datagram.c:43
Inline: True
Inline callers:
  - net/ipv6/datagram.c:ip6_datagram_dst_update
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
In net/ipv6/datagram.c (ffffffff8193f106)
Location: net/ipv6/datagram.c:43
Inline: True
Inline callers:
  - net/ipv6/datagram.c:ip6_datagram_dst_update
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
In net/ipv6/datagram.c (ffffffff81997fea)
Location: net/ipv6/datagram.c:43
Inline: True
Inline callers:
  - net/ipv6/datagram.c:ip6_datagram_dst_update
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
In net/ipv6/datagram.c (ffffffff819ce97a)
Location: net/ipv6/datagram.c:43
Inline: True
Inline callers:
  - net/ipv6/datagram.c:ip6_datagram_dst_update
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
In net/ipv6/datagram.c (ffffffff81a3d629)
Location: net/ipv6/datagram.c:40
Inline: True
Inline callers:
  - net/ipv6/datagram.c:ip6_datagram_dst_update
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
In net/ipv6/datagram.c (ffffffff81a74289)
Location: net/ipv6/datagram.c:40
Inline: True
Inline callers:
  - net/ipv6/datagram.c:ip6_datagram_dst_update
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void ip6_datagram_flow_key_init(struct flowi6 *fl6, struct sock *sk);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/datagram.c (ffffffff81b6de60)
Location: net/ipv6/datagram.c:40
Inline: False
Direct callers:
  - net/ipv6/datagram.c:ip6_datagram_dst_update
  - net/ipv6/datagram.c:ip6_datagram_dst_update
```
**Symbols:**

```
ffffffff81b6de60-ffffffff81b6df37: ip6_datagram_flow_key_init (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void ip6_datagram_flow_key_init(struct flowi6 *fl6, struct sock *sk);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/datagram.c (ffffffff81b7c8e0)
Location: net/ipv6/datagram.c:41
Inline: False
Direct callers:
  - net/ipv6/datagram.c:ip6_datagram_dst_update
  - net/ipv6/datagram.c:ip6_datagram_dst_update
```
**Symbols:**

```
ffffffff81b7c8e0-ffffffff81b7c9b7: ip6_datagram_flow_key_init (STB_LOCAL)
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
In net/ipv6/datagram.c (ffffffff81b6bb1a)
Location: net/ipv6/datagram.c:41
Inline: True
Inline callers:
  - net/ipv6/datagram.c:ip6_datagram_dst_update
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
In net/ipv6/datagram.c (ffffffff81c33984)
Location: net/ipv6/datagram.c:41
Inline: True
Inline callers:
  - net/ipv6/datagram.c:ip6_datagram_dst_update
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
In net/ipv6/datagram.c (ffffffff81dd120d)
Location: net/ipv6/datagram.c:41
Inline: True
Inline callers:
  - net/ipv6/datagram.c:ip6_datagram_dst_update
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
In net/ipv6/datagram.c (ffffffff81fa27fd)
Location: net/ipv6/datagram.c:41
Inline: True
Inline callers:
  - net/ipv6/datagram.c:ip6_datagram_dst_update
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
In net/ipv6/datagram.c (ffffffff8200309e)
Location: net/ipv6/datagram.c:41
Inline: True
Inline callers:
  - net/ipv6/datagram.c:ip6_datagram_dst_update
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
In net/ipv6/datagram.c (ffffffff820d1e6f)
Location: net/ipv6/datagram.c:41
Inline: True
Inline callers:
  - net/ipv6/datagram.c:ip6_datagram_dst_update
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
In net/ipv6/datagram.c (ffff800010d3ccd0)
Location: net/ipv6/datagram.c:40
Inline: True
Inline callers:
  - net/ipv6/datagram.c:ip6_datagram_dst_update
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
In net/ipv6/datagram.c (c0e3ff40)
Location: net/ipv6/datagram.c:40
Inline: True
Inline callers:
  - net/ipv6/datagram.c:ip6_datagram_dst_update
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
In net/ipv6/datagram.c (c000000000e70c8c)
Location: net/ipv6/datagram.c:40
Inline: True
Inline callers:
  - net/ipv6/datagram.c:ip6_datagram_dst_update
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
In net/ipv6/datagram.c (ffffffe00087954a)
Location: net/ipv6/datagram.c:40
Inline: True
Inline callers:
  - net/ipv6/datagram.c:ip6_datagram_dst_update
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
In net/ipv6/datagram.c (ffffffff81a13919)
Location: net/ipv6/datagram.c:40
Inline: True
Inline callers:
  - net/ipv6/datagram.c:ip6_datagram_dst_update
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
In net/ipv6/datagram.c (ffffffff819d06d9)
Location: net/ipv6/datagram.c:40
Inline: True
Inline callers:
  - net/ipv6/datagram.c:ip6_datagram_dst_update
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
In net/ipv6/datagram.c (ffffffff81a7e399)
Location: net/ipv6/datagram.c:40
Inline: True
Inline callers:
  - net/ipv6/datagram.c:ip6_datagram_dst_update
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
In net/ipv6/datagram.c (ffffffff81a8ac29)
Location: net/ipv6/datagram.c:40
Inline: True
Inline callers:
  - net/ipv6/datagram.c:ip6_datagram_dst_update
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
