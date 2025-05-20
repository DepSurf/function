# Function: <code>nh_res_bucket_migrate</code>

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
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
bool nh_res_bucket_migrate(struct nh_res_table *res_table, u16 bucket_index, bool notify, bool notify_nl, bool force);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ipv4/nexthop.c (0)
Location: net/ipv4/nexthop.c:1500
Inline: False
Direct callers:
  - net/ipv4/nexthop.c:nh_res_table_upkeep
```
**Symbols:**

```
ffffffff81af7720-ffffffff81af798f: nh_res_bucket_migrate (STB_LOCAL)
ffffffff81c24cd7-ffffffff81c24cfc: nh_res_bucket_migrate.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv4/nexthop.c (ffffffff81bb768c)
Location: net/ipv4/nexthop.c:1500
Inline: True
Inline callers:
  - net/ipv4/nexthop.c:nh_res_table_upkeep
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv4/nexthop.c (ffffffff81d4b3be)
Location: net/ipv4/nexthop.c:1501
Inline: True
Inline callers:
  - net/ipv4/nexthop.c:nh_res_table_upkeep
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
bool nh_res_bucket_migrate(struct nh_res_table *res_table, u16 bucket_index, bool notify, bool notify_nl, bool force);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ipv4/nexthop.c (0)
Location: net/ipv4/nexthop.c:1501
Inline: False
Direct callers:
  - net/ipv4/nexthop.c:nh_res_table_upkeep
```
**Symbols:**

```
ffffffff81f149a0-ffffffff81f14c93: nh_res_bucket_migrate (STB_LOCAL)
ffffffff820b23d3-ffffffff820b2403: nh_res_bucket_migrate.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
bool nh_res_bucket_migrate(struct nh_res_table *res_table, u16 bucket_index, bool notify, bool notify_nl, bool force);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ipv4/nexthop.c (0)
Location: net/ipv4/nexthop.c:1501
Inline: False
Direct callers:
  - net/ipv4/nexthop.c:nh_res_table_upkeep
```
**Symbols:**

```
ffffffff81f74670-ffffffff81f74963: nh_res_bucket_migrate (STB_LOCAL)
ffffffff82133583-ffffffff821335b3: nh_res_bucket_migrate.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
bool nh_res_bucket_migrate(struct nh_res_table *res_table, u16 bucket_index, bool notify, bool notify_nl, bool force);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ipv4/nexthop.c (0)
Location: net/ipv4/nexthop.c:1524
Inline: False
Direct callers:
  - net/ipv4/nexthop.c:nh_res_table_upkeep
```
**Symbols:**

```
ffffffff8203ae10-ffffffff8203b103: nh_res_bucket_migrate (STB_LOCAL)
ffffffff82214f8f-ffffffff82214fbf: nh_res_bucket_migrate.cold (STB_LOCAL)
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
No changes between <code>6.2</code> and <code>6.5</code> ✅
</li>
<li>
No changes between <code>6.5</code> and <code>6.8</code> ✅
</li>
</ul>
