# Function: <code>mctp_route_lookup</code>

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
In <code>5.11</code>: Absent ⚠️
</li>
<li>
In <code>5.13</code>: Absent ⚠️
</li>
<li>
In <code>5.15</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
struct mctp_route *mctp_route_lookup(struct net *net, unsigned int dnet, mctp_eid_t daddr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/mctp/route.c (ffffffff81e3a980)
Location: net/mctp/route.c:727
Inline: False
Direct callers:
  - net/mctp/af_mctp.c:mctp_sendmsg
  - net/mctp/route.c:mctp_pkttype_receive
```
**Symbols:**

```
ffffffff81e3a980-ffffffff81e3aa48: mctp_route_lookup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
struct mctp_route *mctp_route_lookup(struct net *net, unsigned int dnet, mctp_eid_t daddr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/mctp/route.c (ffffffff82013f40)
Location: net/mctp/route.c:735
Inline: False
Direct callers:
  - net/mctp/af_mctp.c:mctp_sendmsg
  - net/mctp/route.c:mctp_pkttype_receive
```
**Symbols:**

```
ffffffff82013f40-ffffffff82014008: mctp_route_lookup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
struct mctp_route *mctp_route_lookup(struct net *net, unsigned int dnet, mctp_eid_t daddr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/mctp/route.c (ffffffff82090dc0)
Location: net/mctp/route.c:735
Inline: False
Direct callers:
  - net/mctp/af_mctp.c:mctp_sendmsg
  - net/mctp/route.c:mctp_pkttype_receive
```
**Symbols:**

```
ffffffff82090dc0-ffffffff82090e83: mctp_route_lookup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
struct mctp_route *mctp_route_lookup(struct net *net, unsigned int dnet, mctp_eid_t daddr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/mctp/route.c (ffffffff82167300)
Location: net/mctp/route.c:735
Inline: False
Direct callers:
  - net/mctp/af_mctp.c:mctp_sendmsg
  - net/mctp/route.c:mctp_pkttype_receive
```
**Symbols:**

```
ffffffff82167300-ffffffff821673a6: mctp_route_lookup (STB_GLOBAL)
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
No changes between <code>5.19</code> and <code>6.2</code> ✅
</li>
<li>
No changes between <code>6.2</code> and <code>6.5</code> ✅
</li>
<li>
No changes between <code>6.5</code> and <code>6.8</code> ✅
</li>
</ul>
