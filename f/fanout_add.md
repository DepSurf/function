# Function: <code>fanout_add</code>

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
In net/packet/af_packet.c (ffffffff818063f1)
Location: net/packet/af_packet.c:1625
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_setsockopt
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
In net/packet/af_packet.c (ffffffff81876eb0)
Location: net/packet/af_packet.c:1621
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_setsockopt
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
In net/packet/af_packet.c (ffffffff818ab7a9)
Location: net/packet/af_packet.c:1624
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_setsockopt
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
In net/packet/af_packet.c (ffffffff818d1cf6)
Location: net/packet/af_packet.c:1662
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_setsockopt
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
In net/packet/af_packet.c (ffffffff81956be4)
Location: net/packet/af_packet.c:1650
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_setsockopt
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
In net/packet/af_packet.c (ffffffff819b35e3)
Location: net/packet/af_packet.c:1626
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_setsockopt
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
In net/packet/af_packet.c (ffffffff819ea6c4)
Location: net/packet/af_packet.c:1627
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_setsockopt
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
In net/packet/af_packet.c (ffffffff81a593e0)
Location: net/packet/af_packet.c:1626
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_setsockopt
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
In net/packet/af_packet.c (ffffffff81a8f4f0)
Location: net/packet/af_packet.c:1633
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_setsockopt
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int fanout_add(struct sock *sk, u16 id, u16 type_flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/packet/af_packet.c (ffffffff81b8a1f0)
Location: net/packet/af_packet.c:1636
Inline: False
Direct callers:
  - net/packet/af_packet.c:packet_setsockopt
```
**Symbols:**

```
ffffffff81b8a1f0-ffffffff81b8a62e: fanout_add (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int fanout_add(struct sock *sk, struct fanout_args *args);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/packet/af_packet.c (ffffffff81b9a740)
Location: net/packet/af_packet.c:1640
Inline: False
Direct callers:
  - net/packet/af_packet.c:packet_setsockopt
```
**Symbols:**

```
ffffffff81b9a740-ffffffff81b9abb6: fanout_add (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int fanout_add(struct sock *sk, struct fanout_args *args);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/packet/af_packet.c (ffffffff81b896b0)
Location: net/packet/af_packet.c:1644
Inline: False
Direct callers:
  - net/packet/af_packet.c:packet_setsockopt
```
**Symbols:**

```
ffffffff81b896b0-ffffffff81b89ad7: fanout_add (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int fanout_add(struct sock *sk, struct fanout_args *args);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/packet/af_packet.c (ffffffff81c557c0)
Location: net/packet/af_packet.c:1645
Inline: False
Direct callers:
  - net/packet/af_packet.c:packet_setsockopt
```
**Symbols:**

```
ffffffff81c557c0-ffffffff81c55bf0: fanout_add (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int fanout_add(struct sock *sk, struct fanout_args *args);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/packet/af_packet.c (ffffffff81df1860)
Location: net/packet/af_packet.c:1681
Inline: False
Direct callers:
  - net/packet/af_packet.c:packet_setsockopt
```
**Symbols:**

```
ffffffff81df1860-ffffffff81df1cc4: fanout_add (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int fanout_add(struct sock *sk, struct fanout_args *args);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/packet/af_packet.c (ffffffff81fc5830)
Location: net/packet/af_packet.c:1681
Inline: False
Direct callers:
  - net/packet/af_packet.c:packet_setsockopt
```
**Symbols:**

```
ffffffff81fc5830-ffffffff81fc5ca3: fanout_add (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int fanout_add(struct sock *sk, struct fanout_args *args);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/packet/af_packet.c (ffffffff82029d80)
Location: net/packet/af_packet.c:1683
Inline: False
Direct callers:
  - net/packet/af_packet.c:packet_setsockopt
```
**Symbols:**

```
ffffffff82029d80-ffffffff8202a1ed: fanout_add (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int fanout_add(struct sock *sk, struct fanout_args *args);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/packet/af_packet.c (ffffffff820f9850)
Location: net/packet/af_packet.c:1683
Inline: False
Direct callers:
  - net/packet/af_packet.c:packet_setsockopt
```
**Symbols:**

```
ffffffff820f9850-ffffffff820f9ceb: fanout_add (STB_LOCAL)
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
In net/packet/af_packet.c (ffff800010d5c70c)
Location: net/packet/af_packet.c:1633
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_setsockopt
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
In net/packet/af_packet.c (c0e5dd6c)
Location: net/packet/af_packet.c:1633
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_setsockopt
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
In net/packet/af_packet.c (c000000000e986e4)
Location: net/packet/af_packet.c:1633
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_setsockopt
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
In net/packet/af_packet.c (ffffffe0008931b6)
Location: net/packet/af_packet.c:1633
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_setsockopt
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
In net/packet/af_packet.c (ffffffff81a2eb80)
Location: net/packet/af_packet.c:1633
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_setsockopt
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
In net/packet/af_packet.c (ffffffff819ebd70)
Location: net/packet/af_packet.c:1633
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_setsockopt
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
In net/packet/af_packet.c (ffffffff81a9a730)
Location: net/packet/af_packet.c:1633
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_setsockopt
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
In net/packet/af_packet.c (ffffffff81aa7482)
Location: net/packet/af_packet.c:1633
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_setsockopt
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
<details>
<summary>Changed between <code>5.8</code> and <code>5.11</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>struct fanout_args *args</code>
</li>
<li>
<b>Param removed. </b>
<code>u16 id</code>
</li>
<li>
<b>Param removed. </b>
<code>u16 type_flags</code>
</li>
</ul>
</details>
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
