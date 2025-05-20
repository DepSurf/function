# Function: <code>nexthop_select_path_hthr</code>

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
struct nexthop *nexthop_select_path_hthr(struct nh_group *nhg, int hash);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/nexthop.c (ffffffff81af4860)
Location: net/ipv4/nexthop.c:1154
Inline: False
```
**Symbols:**

```
ffffffff81af4860-ffffffff81af4ac2: nexthop_select_path_hthr (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
struct nexthop *nexthop_select_path_hthr(struct nh_group *nhg, int hash);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ipv4/nexthop.c (0)
Location: net/ipv4/nexthop.c:1154
Inline: False
```
**Symbols:**

```
ffffffff81bb50e0-ffffffff81bb5347: nexthop_select_path_hthr (STB_LOCAL)
ffffffff81d3dfe0-ffffffff81d3e08d: nexthop_select_path_hthr.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
struct nexthop *nexthop_select_path_hthr(struct nh_group *nhg, int hash);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ipv4/nexthop.c (0)
Location: net/ipv4/nexthop.c:1155
Inline: False
```
**Symbols:**

```
ffffffff81d48be0-ffffffff81d48e77: nexthop_select_path_hthr (STB_LOCAL)
ffffffff81f0a8bc-ffffffff81f0a969: nexthop_select_path_hthr.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
struct nexthop *nexthop_select_path_hthr(struct nh_group *nhg, int hash);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ipv4/nexthop.c (0)
Location: net/ipv4/nexthop.c:1155
Inline: False
```
**Symbols:**

```
ffffffff81f121d0-ffffffff81f12467: nexthop_select_path_hthr (STB_LOCAL)
ffffffff820b2171-ffffffff820b221e: nexthop_select_path_hthr.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
struct nexthop *nexthop_select_path_hthr(struct nh_group *nhg, int hash);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ipv4/nexthop.c (0)
Location: net/ipv4/nexthop.c:1155
Inline: False
```
**Symbols:**

```
ffffffff81f71ec0-ffffffff81f72126: nexthop_select_path_hthr (STB_LOCAL)
ffffffff82133351-ffffffff821333ce: nexthop_select_path_hthr.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
struct nexthop *nexthop_select_path_hthr(struct nh_group *nhg, int hash);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ipv4/nexthop.c (0)
Location: net/ipv4/nexthop.c:1186
Inline: False
```
**Symbols:**

```
ffffffff820395b0-ffffffff82039827: nexthop_select_path_hthr (STB_LOCAL)
ffffffff82214d79-ffffffff82214def: nexthop_select_path_hthr.cold (STB_LOCAL)
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
