# Function: <code>mctp_neigh_lookup</code>

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
int mctp_neigh_lookup(struct mctp_dev *mdev, mctp_eid_t eid, void *ret_hwaddr);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/mctp/neigh.c (ffffffff81e3b876)
Location: net/mctp/neigh.c:279
Inline: True
Inline callers:
  - net/mctp/neigh.c:mctp_rtm_newneigh
Direct callers:
  - net/mctp/route.c:mctp_route_output
```
**Symbols:**

```
ffffffff81e3bbf0-ffffffff81e3bc9a: mctp_neigh_lookup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
int mctp_neigh_lookup(struct mctp_dev *mdev, mctp_eid_t eid, void *ret_hwaddr);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/mctp/neigh.c (ffffffff82014e63)
Location: net/mctp/neigh.c:279
Inline: True
Direct callers:
  - net/mctp/route.c:mctp_route_output
```
**Symbols:**

```
ffffffff82015300-ffffffff820153aa: mctp_neigh_lookup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
int mctp_neigh_lookup(struct mctp_dev *mdev, mctp_eid_t eid, void *ret_hwaddr);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/mctp/neigh.c (ffffffff82091c83)
Location: net/mctp/neigh.c:279
Inline: True
Direct callers:
  - net/mctp/route.c:mctp_route_output
```
**Symbols:**

```
ffffffff82092120-ffffffff820921ca: mctp_neigh_lookup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
int mctp_neigh_lookup(struct mctp_dev *mdev, mctp_eid_t eid, void *ret_hwaddr);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/mctp/neigh.c (ffffffff82168223)
Location: net/mctp/neigh.c:279
Inline: True
Direct callers:
  - net/mctp/route.c:mctp_route_output
```
**Symbols:**

```
ffffffff82168700-ffffffff821687aa: mctp_neigh_lookup (STB_GLOBAL)
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
