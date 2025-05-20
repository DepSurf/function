# Function: <code>mctp_route_release</code>

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
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
void mctp_route_release(struct mctp_route *rt);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/mctp/route.c (ffffffff81e39420)
Location: net/mctp/route.c:535
Inline: True
Direct callers:
  - net/mctp/route.c:mctp_routes_net_exit
  - net/mctp/route.c:mctp_pkttype_receive
  - net/mctp/route.c:mctp_route_remove_dev
  - net/mctp/route.c:mctp_route_remove
  - net/mctp/route.c:mctp_route_add
  - net/mctp/route.c:mctp_local_output
```
**Symbols:**

```
ffffffff81e39420-ffffffff81e3949a: mctp_route_release (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
void mctp_route_release(struct mctp_route *rt);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/mctp/route.c (ffffffff82012930)
Location: net/mctp/route.c:543
Inline: True
Direct callers:
  - net/mctp/route.c:mctp_routes_net_exit
  - net/mctp/route.c:mctp_pkttype_receive
  - net/mctp/route.c:mctp_route_remove_dev
  - net/mctp/route.c:mctp_route_remove
  - net/mctp/route.c:mctp_route_add
  - net/mctp/route.c:mctp_local_output
```
**Symbols:**

```
ffffffff82012930-ffffffff820129aa: mctp_route_release (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
void mctp_route_release(struct mctp_route *rt);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/mctp/route.c (ffffffff8208f720)
Location: net/mctp/route.c:543
Inline: True
Direct callers:
  - net/mctp/route.c:mctp_routes_net_exit
  - net/mctp/route.c:mctp_pkttype_receive
  - net/mctp/route.c:mctp_route_remove_dev
  - net/mctp/route.c:mctp_route_remove
  - net/mctp/route.c:mctp_route_add
  - net/mctp/route.c:mctp_local_output
```
**Symbols:**

```
ffffffff8208f720-ffffffff8208f798: mctp_route_release (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
void mctp_route_release(struct mctp_route *rt);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/mctp/route.c (ffffffff82165c00)
Location: net/mctp/route.c:543
Inline: True
Direct callers:
  - net/mctp/route.c:mctp_routes_net_exit
  - net/mctp/route.c:mctp_pkttype_receive
  - net/mctp/route.c:mctp_route_remove_dev
  - net/mctp/route.c:mctp_route_remove
  - net/mctp/route.c:mctp_route_add
  - net/mctp/route.c:mctp_local_output
```
**Symbols:**

```
ffffffff82165c00-ffffffff82165c78: mctp_route_release (STB_LOCAL)
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
