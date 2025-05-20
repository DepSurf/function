# Function: <code>mctp_route_remove</code>

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
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int mctp_route_remove(struct mctp_dev *mdev, mctp_eid_t daddr_start, unsigned int daddr_extent, unsigned char type);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/mctp/route.c (0)
Location: net/mctp/route.c:1012
Inline: False
Direct callers:
  - net/mctp/route.c:mctp_delroute
  - net/mctp/route.c:mctp_route_remove_local
```
**Symbols:**

```
ffffffff81e394f0-ffffffff81e39648: mctp_route_remove (STB_LOCAL)
ffffffff81f10d57-ffffffff81f10d6b: mctp_route_remove.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
int mctp_route_remove(struct mctp_dev *mdev, mctp_eid_t daddr_start, unsigned int daddr_extent, unsigned char type);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/mctp/route.c (0)
Location: net/mctp/route.c:1020
Inline: False
Direct callers:
  - net/mctp/route.c:mctp_delroute
  - net/mctp/route.c:mctp_route_remove_local
```
**Symbols:**

```
ffffffff82012e10-ffffffff82012f68: mctp_route_remove (STB_LOCAL)
ffffffff820b7030-ffffffff820b7044: mctp_route_remove.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
int mctp_route_remove(struct mctp_dev *mdev, mctp_eid_t daddr_start, unsigned int daddr_extent, unsigned char type);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/mctp/route.c (0)
Location: net/mctp/route.c:1020
Inline: False
Direct callers:
  - net/mctp/route.c:mctp_delroute
  - net/mctp/route.c:mctp_route_remove_local
```
**Symbols:**

```
ffffffff8208fc30-ffffffff8208fd88: mctp_route_remove (STB_LOCAL)
ffffffff821383df-ffffffff821383f3: mctp_route_remove.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
int mctp_route_remove(struct mctp_dev *mdev, mctp_eid_t daddr_start, unsigned int daddr_extent, unsigned char type);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/mctp/route.c (0)
Location: net/mctp/route.c:1036
Inline: False
Direct callers:
  - net/mctp/route.c:mctp_delroute
  - net/mctp/route.c:mctp_route_remove_local
```
**Symbols:**

```
ffffffff82166140-ffffffff82166298: mctp_route_remove (STB_LOCAL)
ffffffff8221a27c-ffffffff8221a290: mctp_route_remove.cold (STB_LOCAL)
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
