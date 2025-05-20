# Function: <code>__dev_direct_xmit</code>

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
In <code>5.8</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int __dev_direct_xmit(struct sk_buff *skb, u16 queue_id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff81a09530)
Location: net/core/dev.c:4206
Inline: False
Direct callers:
  - net/packet/af_packet.c:packet_direct_xmit
  - net/xdp/xsk.c:xsk_generic_xmit
```
**Symbols:**

```
ffffffff81a09530-ffffffff81a09748: __dev_direct_xmit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int __dev_direct_xmit(struct sk_buff *skb, u16 queue_id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff819efea0)
Location: net/core/dev.c:4289
Inline: False
Direct callers:
  - net/core/selftests.c:__net_test_loopback
  - net/packet/af_packet.c:packet_direct_xmit
  - net/packet/af_packet.c:packet_direct_xmit
  - net/xdp/xsk.c:xsk_generic_xmit
```
**Symbols:**

```
ffffffff819efea0-ffffffff819f00b8: __dev_direct_xmit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int __dev_direct_xmit(struct sk_buff *skb, u16 queue_id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff81aa12d0)
Location: net/core/dev.c:4257
Inline: False
Direct callers:
  - net/core/selftests.c:__net_test_loopback
  - net/packet/af_packet.c:packet_direct_xmit
  - net/packet/af_packet.c:packet_direct_xmit
  - net/xdp/xsk.c:xsk_generic_xmit
```
**Symbols:**

```
ffffffff81aa12d0-ffffffff81aa14e8: __dev_direct_xmit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int __dev_direct_xmit(struct sk_buff *skb, u16 queue_id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff81c191b0)
Location: net/core/dev.c:4288
Inline: False
Direct callers:
  - net/core/selftests.c:__net_test_loopback
  - net/packet/af_packet.c:packet_direct_xmit
  - net/xdp/xsk.c:xsk_generic_xmit
```
**Symbols:**

```
ffffffff81c191b0-ffffffff81c193ca: __dev_direct_xmit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int __dev_direct_xmit(struct sk_buff *skb, u16 queue_id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff81dca1b0)
Location: net/core/dev.c:4275
Inline: False
Direct callers:
  - net/core/selftests.c:__net_test_loopback
  - net/packet/af_packet.c:packet_direct_xmit
  - net/xdp/xsk.c:__xsk_generic_xmit
```
**Symbols:**

```
ffffffff81dca1b0-ffffffff81dca3ca: __dev_direct_xmit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int __dev_direct_xmit(struct sk_buff *skb, u16 queue_id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff81e3ad30)
Location: net/core/dev.c:4235
Inline: False
Direct callers:
  - net/core/selftests.c:__net_test_loopback
  - net/packet/af_packet.c:packet_xmit
  - net/xdp/xsk.c:__xsk_generic_xmit
```
**Symbols:**

```
ffffffff81e3ad30-ffffffff81e3af4a: __dev_direct_xmit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int __dev_direct_xmit(struct sk_buff *skb, u16 queue_id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff81ef90c0)
Location: net/core/dev.c:4383
Inline: False
Direct callers:
  - net/core/selftests.c:__net_test_loopback
  - net/packet/af_packet.c:packet_xmit
  - net/xdp/xsk.c:__xsk_generic_xmit
```
**Symbols:**

```
ffffffff81ef90c0-ffffffff81ef92bc: __dev_direct_xmit (STB_GLOBAL)
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
<b>Regular</b>
<ul>
<li>
No changes between <code>5.11</code> and <code>5.13</code> ✅
</li>
<li>
No changes between <code>5.13</code> and <code>5.15</code> ✅
</li>
<li>
No changes between <code>5.15</code> and <code>5.19</code> ✅
</li>
<li>
No changes between <code>5.19</code> and <code>6.2</code> ✅
</li>
<li>
No changes between <code>6.2</code> and <code>6.5</code> ✅
</li>
<li>
No changes between <code>6.5</code> and <code>6.8</code> ✅
</li>
</ul>
