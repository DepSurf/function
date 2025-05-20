# Function: <code>l3mdev_ifindex_lookup_by_table_id</code>

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
int l3mdev_ifindex_lookup_by_table_id(enum l3mdev_type l3type, struct net *net, u32 table_id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/l3mdev/l3mdev.c (ffffffff81badc50)
Location: net/l3mdev/l3mdev.c:76
Inline: False
Direct callers:
  - net/ipv6/seg6_local.c:seg6_end_dt4_build
```
**Symbols:**

```
ffffffff81badc50-ffffffff81badcb7: l3mdev_ifindex_lookup_by_table_id (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int l3mdev_ifindex_lookup_by_table_id(enum l3mdev_type l3type, struct net *net, u32 table_id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/l3mdev/l3mdev.c (ffffffff81b9cdb0)
Location: net/l3mdev/l3mdev.c:76
Inline: False
Direct callers:
  - net/ipv6/seg6_local.c:__seg6_end_dt_vrf_build
```
**Symbols:**

```
ffffffff81b9cdb0-ffffffff81b9ce13: l3mdev_ifindex_lookup_by_table_id (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int l3mdev_ifindex_lookup_by_table_id(enum l3mdev_type l3type, struct net *net, u32 table_id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/l3mdev/l3mdev.c (ffffffff81c6a2d0)
Location: net/l3mdev/l3mdev.c:76
Inline: False
Direct callers:
  - net/ipv6/seg6_local.c:__seg6_end_dt_vrf_build
```
**Symbols:**

```
ffffffff81c6a2d0-ffffffff81c6a333: l3mdev_ifindex_lookup_by_table_id (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int l3mdev_ifindex_lookup_by_table_id(enum l3mdev_type l3type, struct net *net, u32 table_id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/l3mdev/l3mdev.c (ffffffff81e0d7d0)
Location: net/l3mdev/l3mdev.c:76
Inline: False
Direct callers:
  - net/ipv6/seg6_local.c:__seg6_end_dt_vrf_build
```
**Symbols:**

```
ffffffff81e0d7d0-ffffffff81e0d837: l3mdev_ifindex_lookup_by_table_id (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int l3mdev_ifindex_lookup_by_table_id(enum l3mdev_type l3type, struct net *net, u32 table_id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/l3mdev/l3mdev.c (ffffffff81fe3aa0)
Location: net/l3mdev/l3mdev.c:76
Inline: False
Direct callers:
  - net/ipv6/seg6_local.c:__seg6_end_dt_vrf_build
```
**Symbols:**

```
ffffffff81fe3aa0-ffffffff81fe3b07: l3mdev_ifindex_lookup_by_table_id (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int l3mdev_ifindex_lookup_by_table_id(enum l3mdev_type l3type, struct net *net, u32 table_id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/l3mdev/l3mdev.c (ffffffff8205fdc0)
Location: net/l3mdev/l3mdev.c:76
Inline: False
Direct callers:
  - net/ipv6/seg6_local.c:seg6_end_dt46_build
  - net/ipv6/seg6_local.c:seg6_end_dt4_build
```
**Symbols:**

```
ffffffff8205fdc0-ffffffff8205fe27: l3mdev_ifindex_lookup_by_table_id (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int l3mdev_ifindex_lookup_by_table_id(enum l3mdev_type l3type, struct net *net, u32 table_id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/l3mdev/l3mdev.c (ffffffff82132d00)
Location: net/l3mdev/l3mdev.c:76
Inline: False
Direct callers:
  - net/ipv6/seg6_local.c:seg6_end_dt46_build
  - net/ipv6/seg6_local.c:seg6_end_dt4_build
```
**Symbols:**

```
ffffffff82132d00-ffffffff82132d67: l3mdev_ifindex_lookup_by_table_id (STB_GLOBAL)
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
