# Function: <code>nh_res_table_upkeep</code>

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
void nh_res_table_upkeep(struct nh_res_table *res_table, bool notify, bool notify_nl);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/nexthop.c (ffffffff81af7990)
Location: net/ipv4/nexthop.c:1555
Inline: False
Direct callers:
  - net/ipv4/nexthop.c:insert_nexthop
  - net/ipv4/nexthop.c:replace_nexthop_grp_res
  - net/ipv4/nexthop.c:nh_res_table_upkeep_dw
```
**Symbols:**

```
ffffffff81af7990-ffffffff81af7b3d: nh_res_table_upkeep (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
void nh_res_table_upkeep(struct nh_res_table *res_table, bool notify, bool notify_nl);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ipv4/nexthop.c (0)
Location: net/ipv4/nexthop.c:1555
Inline: False
Direct callers:
  - net/ipv4/nexthop.c:insert_nexthop
  - net/ipv4/nexthop.c:replace_nexthop_grp_res
  - net/ipv4/nexthop.c:nh_res_table_upkeep_dw
```
**Symbols:**

```
ffffffff81bb7540-ffffffff81bb799a: nh_res_table_upkeep (STB_LOCAL)
ffffffff81d3e240-ffffffff81d3e2bf: nh_res_table_upkeep.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
void nh_res_table_upkeep(struct nh_res_table *res_table, bool notify, bool notify_nl);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ipv4/nexthop.c (0)
Location: net/ipv4/nexthop.c:1556
Inline: False
Direct callers:
  - net/ipv4/nexthop.c:insert_nexthop
  - net/ipv4/nexthop.c:replace_nexthop_grp_res
  - net/ipv4/nexthop.c:nh_res_table_upkeep_dw
```
**Symbols:**

```
ffffffff81d4b270-ffffffff81d4b701: nh_res_table_upkeep (STB_LOCAL)
ffffffff81f0ab1e-ffffffff81f0ab9d: nh_res_table_upkeep.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
void nh_res_table_upkeep(struct nh_res_table *res_table, bool notify, bool notify_nl);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ipv4/nexthop.c (0)
Location: net/ipv4/nexthop.c:1556
Inline: False
Direct callers:
  - net/ipv4/nexthop.c:insert_nexthop
  - net/ipv4/nexthop.c:replace_nexthop_grp_res
  - net/ipv4/nexthop.c:nh_res_table_upkeep_dw
```
**Symbols:**

```
ffffffff81f14cb0-ffffffff81f14e80: nh_res_table_upkeep (STB_LOCAL)
ffffffff820b2403-ffffffff820b2426: nh_res_table_upkeep.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
void nh_res_table_upkeep(struct nh_res_table *res_table, bool notify, bool notify_nl);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ipv4/nexthop.c (0)
Location: net/ipv4/nexthop.c:1556
Inline: False
Direct callers:
  - net/ipv4/nexthop.c:insert_nexthop
  - net/ipv4/nexthop.c:replace_nexthop_grp_res
  - net/ipv4/nexthop.c:nh_res_table_upkeep_dw
```
**Symbols:**

```
ffffffff81f74980-ffffffff81f74b42: nh_res_table_upkeep (STB_LOCAL)
ffffffff821335b3-ffffffff821335d6: nh_res_table_upkeep.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
void nh_res_table_upkeep(struct nh_res_table *res_table, bool notify, bool notify_nl);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ipv4/nexthop.c (0)
Location: net/ipv4/nexthop.c:1579
Inline: False
Direct callers:
  - net/ipv4/nexthop.c:insert_nexthop
  - net/ipv4/nexthop.c:replace_nexthop_grp_res
  - net/ipv4/nexthop.c:nh_res_table_upkeep_dw
```
**Symbols:**

```
ffffffff8203b120-ffffffff8203b2e4: nh_res_table_upkeep (STB_LOCAL)
ffffffff82214fbf-ffffffff82214fe2: nh_res_table_upkeep.cold (STB_LOCAL)
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
