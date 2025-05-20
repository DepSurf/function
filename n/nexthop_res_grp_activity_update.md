# Function: <code>nexthop_res_grp_activity_update</code>

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
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void nexthop_res_grp_activity_update(struct net *net, u32 id, u16 num_buckets, long unsigned int *activity);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/nexthop.c (ffffffff81af3e60)
Location: net/ipv4/nexthop.c:3664
Inline: False
```
**Symbols:**

```
ffffffff81af3e60-ffffffff81af3ef4: nexthop_res_grp_activity_update (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
void nexthop_res_grp_activity_update(struct net *net, u32 id, u16 num_buckets, long unsigned int *activity);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ipv4/nexthop.c (0)
Location: net/ipv4/nexthop.c:3702
Inline: False
```
**Symbols:**

```
ffffffff81d3dce4-ffffffff81d3dd1d: nexthop_res_grp_activity_update.cold (STB_LOCAL)
ffffffff81bb4520-ffffffff81bb45e7: nexthop_res_grp_activity_update (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
void nexthop_res_grp_activity_update(struct net *net, u32 id, u16 num_buckets, long unsigned int *activity);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ipv4/nexthop.c (0)
Location: net/ipv4/nexthop.c:3702
Inline: False
```
**Symbols:**

```
ffffffff81f0a58c-ffffffff81f0a5b5: nexthop_res_grp_activity_update.cold (STB_LOCAL)
ffffffff81d47fb0-ffffffff81d480ac: nexthop_res_grp_activity_update (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
void nexthop_res_grp_activity_update(struct net *net, u32 id, u16 num_buckets, long unsigned int *activity);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ipv4/nexthop.c (0)
Location: net/ipv4/nexthop.c:3702
Inline: False
```
**Symbols:**

```
ffffffff820b1e41-ffffffff820b1e6a: nexthop_res_grp_activity_update.cold (STB_LOCAL)
ffffffff81f11500-ffffffff81f115fc: nexthop_res_grp_activity_update (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
void nexthop_res_grp_activity_update(struct net *net, u32 id, u16 num_buckets, long unsigned int *activity);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ipv4/nexthop.c (0)
Location: net/ipv4/nexthop.c:3688
Inline: False
```
**Symbols:**

```
ffffffff8213304e-ffffffff82133077: nexthop_res_grp_activity_update.cold (STB_LOCAL)
ffffffff81f711f0-ffffffff81f712ed: nexthop_res_grp_activity_update (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
void nexthop_res_grp_activity_update(struct net *net, u32 id, u16 num_buckets, long unsigned int *activity);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ipv4/nexthop.c (0)
Location: net/ipv4/nexthop.c:3705
Inline: False
```
**Symbols:**

```
ffffffff822149fd-ffffffff82214a26: nexthop_res_grp_activity_update.cold (STB_LOCAL)
ffffffff82037950-ffffffff82037a4d: nexthop_res_grp_activity_update (STB_GLOBAL)
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
