# Function: <code>tcp_tso_segs</code>

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
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
u32 tcp_tso_segs(struct sock *sk, unsigned int mss_now);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_output.c (ffffffff81812430)
Location: net/ipv4/tcp_output.c:1605
Inline: True
Direct callers:
  - net/ipv4/tcp_output.c:tcp_write_xmit
```
**Symbols:**

```
ffffffff81812430-ffffffff81812498: tcp_tso_segs (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
u32 tcp_tso_segs(struct sock *sk, unsigned int mss_now);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_output.c (ffffffff818326a0)
Location: net/ipv4/tcp_output.c:1686
Inline: True
Direct callers:
  - net/ipv4/tcp_output.c:tcp_write_xmit
```
**Symbols:**

```
ffffffff818326a0-ffffffff81832703: tcp_tso_segs (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
u32 tcp_tso_segs(struct sock *sk, unsigned int mss_now);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_output.c (ffffffff818b0c20)
Location: net/ipv4/tcp_output.c:1740
Inline: False
Direct callers:
  - net/ipv4/tcp_output.c:tcp_write_xmit
```
**Symbols:**

```
ffffffff818b0c20-ffffffff818b0c90: tcp_tso_segs (STB_LOCAL)
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
In net/ipv4/tcp_output.c (ffffffff81908996)
Location: net/ipv4/tcp_output.c:1730
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_write_xmit
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
In net/ipv4/tcp_output.c (ffffffff81936bdf)
Location: net/ipv4/tcp_output.c:1719
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_write_xmit
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
In net/ipv4/tcp_output.c (ffffffff8199c1d1)
Location: net/ipv4/tcp_output.c:1732
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_write_xmit
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
In net/ipv4/tcp_output.c (ffffffff819d2c71)
Location: net/ipv4/tcp_output.c:1751
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_write_xmit
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_output.c (ffffffff81abf85c)
Location: net/ipv4/tcp_output.c:1814
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_write_xmit
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_output.c (ffffffff81acb2c8)
Location: net/ipv4/tcp_output.c:1982
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_write_xmit
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
In net/ipv4/tcp_output.c (ffffffff81ab62f8)
Location: net/ipv4/tcp_output.c:1983
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_write_xmit
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
u32 tcp_tso_segs(struct sock *sk, unsigned int mss_now);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ipv4/tcp_output.c (0)
Location: net/ipv4/tcp_output.c:1983
Inline: False
Direct callers:
  - net/ipv4/tcp_output.c:tcp_write_xmit
```
**Symbols:**

```
ffffffff81b6e320-ffffffff81b6e3ae: tcp_tso_segs (STB_LOCAL)
ffffffff81d3adaf-ffffffff81d3add1: tcp_tso_segs.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
u32 tcp_tso_segs(struct sock *sk, unsigned int mss_now);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ipv4/tcp_output.c (0)
Location: net/ipv4/tcp_output.c:1988
Inline: False
Direct callers:
  - net/ipv4/tcp_output.c:tcp_write_xmit
```
**Symbols:**

```
ffffffff81cfd7b0-ffffffff81cfd886: tcp_tso_segs (STB_LOCAL)
ffffffff81f0765f-ffffffff81f076a2: tcp_tso_segs.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
u32 tcp_tso_segs(struct sock *sk, unsigned int mss_now);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ipv4/tcp_output.c (0)
Location: net/ipv4/tcp_output.c:1990
Inline: False
Direct callers:
  - net/ipv4/tcp_output.c:tcp_write_xmit
```
**Symbols:**

```
ffffffff81ec23d0-ffffffff81ec24a6: tcp_tso_segs (STB_LOCAL)
ffffffff820af0d7-ffffffff820af11a: tcp_tso_segs.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
u32 tcp_tso_segs(struct sock *sk, unsigned int mss_now);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ipv4/tcp_output.c (0)
Location: net/ipv4/tcp_output.c:1982
Inline: False
Direct callers:
  - net/ipv4/tcp_output.c:tcp_write_xmit
```
**Symbols:**

```
ffffffff81f209e0-ffffffff81f20aae: tcp_tso_segs (STB_LOCAL)
ffffffff821304c6-ffffffff82130506: tcp_tso_segs.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
u32 tcp_tso_segs(struct sock *sk, unsigned int mss_now);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ipv4/tcp_output.c (0)
Location: net/ipv4/tcp_output.c:2025
Inline: False
Direct callers:
  - net/ipv4/tcp_output.c:tcp_write_xmit
```
**Symbols:**

```
ffffffff81fe50e0-ffffffff81fe51ae: tcp_tso_segs (STB_LOCAL)
ffffffff82211eac-ffffffff82211ee8: tcp_tso_segs.cold (STB_LOCAL)
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
In net/ipv4/tcp_output.c (ffff800010c85844)
Location: net/ipv4/tcp_output.c:1751
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_write_xmit
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
In net/ipv4/tcp_output.c (c0d94a44)
Location: net/ipv4/tcp_output.c:1751
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_write_xmit
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
In net/ipv4/tcp_output.c (c000000000d91a10)
Location: net/ipv4/tcp_output.c:1751
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_write_xmit
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
In net/ipv4/tcp_output.c (ffffffe0007e705e)
Location: net/ipv4/tcp_output.c:1751
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_write_xmit
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
In net/ipv4/tcp_output.c (ffffffff81972ae1)
Location: net/ipv4/tcp_output.c:1751
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_write_xmit
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
In net/ipv4/tcp_output.c (ffffffff8192c5b1)
Location: net/ipv4/tcp_output.c:1751
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_write_xmit
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
In net/ipv4/tcp_output.c (ffffffff819dd2b1)
Location: net/ipv4/tcp_output.c:1751
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_write_xmit
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
In net/ipv4/tcp_output.c (ffffffff819e6f31)
Location: net/ipv4/tcp_output.c:1751
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_write_xmit
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>4.10</code> and <code>4.13</code> ✅
</li>
<li>
No changes between <code>4.13</code> and <code>4.15</code> ✅
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
