# Function: <code>arp_req_get</code>

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
In net/ipv4/arp.c (ffffffff8178d9d4)
Location: net/ipv4/arp.c:1043
Inline: True
Inline callers:
  - net/ipv4/arp.c:arp_ioctl
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
In net/ipv4/arp.c (ffffffff817faf9d)
Location: net/ipv4/arp.c:1056
Inline: True
Inline callers:
  - net/ipv4/arp.c:arp_ioctl
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
In net/ipv4/arp.c (ffffffff8182be4d)
Location: net/ipv4/arp.c:1056
Inline: True
Inline callers:
  - net/ipv4/arp.c:arp_ioctl
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
In net/ipv4/arp.c (ffffffff8184d1a9)
Location: net/ipv4/arp.c:1090
Inline: True
Inline callers:
  - net/ipv4/arp.c:arp_ioctl
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
In net/ipv4/arp.c (ffffffff818cced9)
Location: net/ipv4/arp.c:1095
Inline: True
Inline callers:
  - net/ipv4/arp.c:arp_ioctl
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
In net/ipv4/arp.c (ffffffff819233cf)
Location: net/ipv4/arp.c:1095
Inline: True
Inline callers:
  - net/ipv4/arp.c:arp_ioctl
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
In net/ipv4/arp.c (ffffffff819521bf)
Location: net/ipv4/arp.c:1095
Inline: True
Inline callers:
  - net/ipv4/arp.c:arp_ioctl
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
In net/ipv4/arp.c (ffffffff819b6a4c)
Location: net/ipv4/arp.c:1091
Inline: True
Inline callers:
  - net/ipv4/arp.c:arp_ioctl
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
In net/ipv4/arp.c (ffffffff819ed76c)
Location: net/ipv4/arp.c:1091
Inline: True
Inline callers:
  - net/ipv4/arp.c:arp_ioctl
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int arp_req_get(struct arpreq *r, struct net_device *dev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/arp.c (ffffffff81ada060)
Location: net/ipv4/arp.c:1091
Inline: False
Direct callers:
  - net/ipv4/arp.c:arp_ioctl
```
**Symbols:**

```
ffffffff81ada060-ffffffff81ada226: arp_req_get (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
int arp_req_get(struct arpreq *r, struct net_device *dev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ipv4/arp.c (0)
Location: net/ipv4/arp.c:1097
Inline: False
Direct callers:
  - net/ipv4/arp.c:arp_ioctl
```
**Symbols:**

```
ffffffff81ae6ad0-ffffffff81ae6cca: arp_req_get (STB_LOCAL)
ffffffff81c3280c-ffffffff81c32824: arp_req_get.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
int arp_req_get(struct arpreq *r, struct net_device *dev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ipv4/arp.c (0)
Location: net/ipv4/arp.c:1097
Inline: False
Direct callers:
  - net/ipv4/arp.c:arp_ioctl
```
**Symbols:**

```
ffffffff81ad1da0-ffffffff81ad1f9b: arp_req_get (STB_LOCAL)
ffffffff81c24ade-ffffffff81c24af6: arp_req_get.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int arp_req_get(struct arpreq *r, struct net_device *dev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ipv4/arp.c (0)
Location: net/ipv4/arp.c:1097
Inline: False
Direct callers:
  - net/ipv4/arp.c:arp_ioctl
```
**Symbols:**

```
ffffffff81b909f0-ffffffff81b90beb: arp_req_get (STB_LOCAL)
ffffffff81d3c0cc-ffffffff81d3c0e4: arp_req_get.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int arp_req_get(struct arpreq *r, struct net_device *dev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ipv4/arp.c (0)
Location: net/ipv4/arp.c:1097
Inline: False
Direct callers:
  - net/ipv4/arp.c:arp_ioctl
```
**Symbols:**

```
ffffffff81d21ef0-ffffffff81d220f3: arp_req_get (STB_LOCAL)
ffffffff81f088e5-ffffffff81f088fd: arp_req_get.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int arp_req_get(struct arpreq *r, struct net_device *dev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/arp.c (ffffffff81ee9360)
Location: net/ipv4/arp.c:1118
Inline: False
Direct callers:
  - net/ipv4/arp.c:arp_ioctl
```
**Symbols:**

```
ffffffff81ee9360-ffffffff81ee9564: arp_req_get (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int arp_req_get(struct arpreq *r, struct net_device *dev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/arp.c (ffffffff81f48c90)
Location: net/ipv4/arp.c:1118
Inline: False
Direct callers:
  - net/ipv4/arp.c:arp_ioctl
```
**Symbols:**

```
ffffffff81f48c90-ffffffff81f48e96: arp_req_get (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int arp_req_get(struct arpreq *r, struct net_device *dev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/arp.c (ffffffff8200edf0)
Location: net/ipv4/arp.c:1118
Inline: False
Direct callers:
  - net/ipv4/arp.c:arp_ioctl
```
**Symbols:**

```
ffffffff8200edf0-ffffffff8200f027: arp_req_get (STB_LOCAL)
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
In net/ipv4/arp.c (ffff800010ca31d8)
Location: net/ipv4/arp.c:1091
Inline: True
Inline callers:
  - net/ipv4/arp.c:arp_ioctl
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
In net/ipv4/arp.c (c0daff44)
Location: net/ipv4/arp.c:1091
Inline: True
Inline callers:
  - net/ipv4/arp.c:arp_ioctl
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
In net/ipv4/arp.c (c000000000db69c8)
Location: net/ipv4/arp.c:1091
Inline: True
Inline callers:
  - net/ipv4/arp.c:arp_ioctl
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
In net/ipv4/arp.c (ffffffe0007ff244)
Location: net/ipv4/arp.c:1091
Inline: True
Inline callers:
  - net/ipv4/arp.c:arp_ioctl
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
In net/ipv4/arp.c (ffffffff8198d50c)
Location: net/ipv4/arp.c:1091
Inline: True
Inline callers:
  - net/ipv4/arp.c:arp_ioctl
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
In net/ipv4/arp.c (ffffffff81946fcc)
Location: net/ipv4/arp.c:1091
Inline: True
Inline callers:
  - net/ipv4/arp.c:arp_ioctl
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
In net/ipv4/arp.c (ffffffff819f7dac)
Location: net/ipv4/arp.c:1091
Inline: True
Inline callers:
  - net/ipv4/arp.c:arp_ioctl
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
In net/ipv4/arp.c (ffffffff81a01fec)
Location: net/ipv4/arp.c:1091
Inline: True
Inline callers:
  - net/ipv4/arp.c:arp_ioctl
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
