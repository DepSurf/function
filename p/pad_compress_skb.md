# Function: <code>pad_compress_skb</code>

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
In drivers/net/ppp/ppp_generic.c (ffffffff815f799e)
Location: drivers/net/ppp/ppp_generic.c:1183
Inline: True
Inline callers:
  - drivers/net/ppp/ppp_generic.c:ppp_xmit_process
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
In drivers/net/ppp/ppp_generic.c (ffffffff81657b4c)
Location: drivers/net/ppp/ppp_generic.c:1396
Inline: True
Inline callers:
  - drivers/net/ppp/ppp_generic.c:ppp_xmit_process
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
In drivers/net/ppp/ppp_generic.c (ffffffff8168582c)
Location: drivers/net/ppp/ppp_generic.c:1427
Inline: True
Inline callers:
  - drivers/net/ppp/ppp_generic.c:__ppp_xmit_process
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
In drivers/net/ppp/ppp_generic.c (ffffffff8169ac3c)
Location: drivers/net/ppp/ppp_generic.c:1441
Inline: True
Inline callers:
  - drivers/net/ppp/ppp_generic.c:__ppp_xmit_process
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
In drivers/net/ppp/ppp_generic.c (ffffffff817053f9)
Location: drivers/net/ppp/ppp_generic.c:1468
Inline: True
Inline callers:
  - drivers/net/ppp/ppp_generic.c:__ppp_xmit_process
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
In drivers/net/ppp/ppp_generic.c (ffffffff8174487b)
Location: drivers/net/ppp/ppp_generic.c:1451
Inline: True
Inline callers:
  - drivers/net/ppp/ppp_generic.c:__ppp_xmit_process
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
In drivers/net/ppp/ppp_generic.c (ffffffff81768978)
Location: drivers/net/ppp/ppp_generic.c:1451
Inline: True
Inline callers:
  - drivers/net/ppp/ppp_generic.c:__ppp_xmit_process
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
In drivers/net/ppp/ppp_generic.c (ffffffff817a630a)
Location: drivers/net/ppp/ppp_generic.c:1447
Inline: True
Inline callers:
  - drivers/net/ppp/ppp_generic.c:ppp_send_frame
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
In drivers/net/ppp/ppp_generic.c (ffffffff817c9d5a)
Location: drivers/net/ppp/ppp_generic.c:1447
Inline: True
Inline callers:
  - drivers/net/ppp/ppp_generic.c:ppp_send_frame
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
struct sk_buff *pad_compress_skb(struct ppp *ppp, struct sk_buff *skb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/net/ppp/ppp_generic.c (0)
Location: drivers/net/ppp/ppp_generic.c:1535
Inline: False
Direct callers:
  - drivers/net/ppp/ppp_generic.c:ppp_send_frame
```
**Symbols:**

```
ffffffff81890fe0-ffffffff8189112b: pad_compress_skb (STB_LOCAL)
ffffffff81895857-ffffffff81895887: pad_compress_skb.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
struct sk_buff *pad_compress_skb(struct ppp *ppp, struct sk_buff *skb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/net/ppp/ppp_generic.c (0)
Location: drivers/net/ppp/ppp_generic.c:1645
Inline: False
Direct callers:
  - drivers/net/ppp/ppp_generic.c:ppp_send_frame
```
**Symbols:**

```
ffffffff8189f1c0-ffffffff8189f30b: pad_compress_skb (STB_LOCAL)
ffffffff81c1992f-ffffffff81c1995f: pad_compress_skb.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
struct sk_buff *pad_compress_skb(struct ppp *ppp, struct sk_buff *skb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/net/ppp/ppp_generic.c (0)
Location: drivers/net/ppp/ppp_generic.c:1678
Inline: False
Direct callers:
  - drivers/net/ppp/ppp_generic.c:ppp_send_frame
```
**Symbols:**

```
ffffffff81881c50-ffffffff81881d9b: pad_compress_skb (STB_LOCAL)
ffffffff81c0b786-ffffffff81c0b7b6: pad_compress_skb.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
struct sk_buff *pad_compress_skb(struct ppp *ppp, struct sk_buff *skb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/net/ppp/ppp_generic.c (0)
Location: drivers/net/ppp/ppp_generic.c:1683
Inline: False
Direct callers:
  - drivers/net/ppp/ppp_generic.c:ppp_send_frame
```
**Symbols:**

```
ffffffff819135f0-ffffffff8191373b: pad_compress_skb (STB_LOCAL)
ffffffff81d10db0-ffffffff81d10de0: pad_compress_skb.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
struct sk_buff *pad_compress_skb(struct ppp *ppp, struct sk_buff *skb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/net/ppp/ppp_generic.c (0)
Location: drivers/net/ppp/ppp_generic.c:1684
Inline: False
Direct callers:
  - drivers/net/ppp/ppp_generic.c:ppp_send_frame
```
**Symbols:**

```
ffffffff81a68080-ffffffff81a68205: pad_compress_skb (STB_LOCAL)
ffffffff81edbac3-ffffffff81edbaf5: pad_compress_skb.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
struct sk_buff *pad_compress_skb(struct ppp *ppp, struct sk_buff *skb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/net/ppp/ppp_generic.c (ffffffff81bfa980)
Location: drivers/net/ppp/ppp_generic.c:1684
Inline: False
Direct callers:
  - drivers/net/ppp/ppp_generic.c:ppp_send_frame
```
**Symbols:**

```
ffffffff81bfa980-ffffffff81bfab32: pad_compress_skb (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
struct sk_buff *pad_compress_skb(struct ppp *ppp, struct sk_buff *skb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/net/ppp/ppp_generic.c (ffffffff81c5ffc0)
Location: drivers/net/ppp/ppp_generic.c:1684
Inline: False
Direct callers:
  - drivers/net/ppp/ppp_generic.c:ppp_send_frame
```
**Symbols:**

```
ffffffff81c5ffc0-ffffffff81c60172: pad_compress_skb (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
struct sk_buff *pad_compress_skb(struct ppp *ppp, struct sk_buff *skb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/net/ppp/ppp_generic.c (ffffffff81d169a0)
Location: drivers/net/ppp/ppp_generic.c:1684
Inline: False
Direct callers:
  - drivers/net/ppp/ppp_generic.c:ppp_send_frame
```
**Symbols:**

```
ffffffff81d169a0-ffffffff81d16b4f: pad_compress_skb (STB_LOCAL)
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
In drivers/net/ppp/ppp_generic.c (ffff800010a0186c)
Location: drivers/net/ppp/ppp_generic.c:1447
Inline: True
Inline callers:
  - drivers/net/ppp/ppp_generic.c:ppp_send_frame
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
In drivers/net/ppp/ppp_generic.c (c0adea7c)
Location: drivers/net/ppp/ppp_generic.c:1447
Inline: True
Inline callers:
  - drivers/net/ppp/ppp_generic.c:ppp_send_frame
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
In drivers/net/ppp/ppp_generic.c (c000000000aaa068)
Location: drivers/net/ppp/ppp_generic.c:1447
Inline: True
Inline callers:
  - drivers/net/ppp/ppp_generic.c:ppp_send_frame
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
In drivers/net/ppp/ppp_generic.c (ffffffe00062e49c)
Location: drivers/net/ppp/ppp_generic.c:1447
Inline: True
Inline callers:
  - drivers/net/ppp/ppp_generic.c:ppp_send_frame
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
In drivers/net/ppp/ppp_generic.c (ffffffff8178e83a)
Location: drivers/net/ppp/ppp_generic.c:1447
Inline: True
Inline callers:
  - drivers/net/ppp/ppp_generic.c:ppp_send_frame
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
In drivers/net/ppp/ppp_generic.c (ffffffff8177760a)
Location: drivers/net/ppp/ppp_generic.c:1447
Inline: True
Inline callers:
  - drivers/net/ppp/ppp_generic.c:ppp_send_frame
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
In drivers/net/ppp/ppp_generic.c (ffffffff817bebda)
Location: drivers/net/ppp/ppp_generic.c:1447
Inline: True
Inline callers:
  - drivers/net/ppp/ppp_generic.c:ppp_send_frame
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
In drivers/net/ppp/ppp_generic.c (ffffffff817d8e6a)
Location: drivers/net/ppp/ppp_generic.c:1447
Inline: True
Inline callers:
  - drivers/net/ppp/ppp_generic.c:ppp_send_frame
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
