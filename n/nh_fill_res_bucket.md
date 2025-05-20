# Function: <code>nh_fill_res_bucket</code>

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
<summary>In <code>5.13</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/ipv4/nexthop.c (ffffffff81af7510)
Location: net/ipv4/nexthop.c:913
Inline: True
Direct callers:
  - net/ipv4/nexthop.c:rtm_get_nexthop_bucket
  - net/ipv4/nexthop.c:rtm_dump_nexthop_bucket_nh
  - net/ipv4/nexthop.c:nh_res_bucket_migrate
```
**Symbols:**

```
ffffffff81af7510-ffffffff81af7716: nh_fill_res_bucket.constprop.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/ipv4/nexthop.c (ffffffff81bb6ec0)
Location: net/ipv4/nexthop.c:913
Inline: True
Direct callers:
  - net/ipv4/nexthop.c:rtm_get_nexthop_bucket
  - net/ipv4/nexthop.c:rtm_dump_nexthop_bucket_nh
  - net/ipv4/nexthop.c:nh_res_table_upkeep
```
**Symbols:**

```
ffffffff81bb6ec0-ffffffff81bb70c6: nh_fill_res_bucket.constprop.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/ipv4/nexthop.c (ffffffff81d4ab70)
Location: net/ipv4/nexthop.c:914
Inline: True
Direct callers:
  - net/ipv4/nexthop.c:rtm_get_nexthop_bucket
  - net/ipv4/nexthop.c:rtm_dump_nexthop_bucket_nh
  - net/ipv4/nexthop.c:nh_res_table_upkeep
```
**Symbols:**

```
ffffffff81d4ab70-ffffffff81d4ad8a: nh_fill_res_bucket.constprop.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/ipv4/nexthop.c (ffffffff81f14250)
Location: net/ipv4/nexthop.c:914
Inline: True
Direct callers:
  - net/ipv4/nexthop.c:rtm_get_nexthop_bucket
  - net/ipv4/nexthop.c:rtm_dump_nexthop_bucket_nh
  - net/ipv4/nexthop.c:nh_res_bucket_migrate
```
**Symbols:**

```
ffffffff81f14250-ffffffff81f1446a: nh_fill_res_bucket.constprop.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/ipv4/nexthop.c (ffffffff81f73f20)
Location: net/ipv4/nexthop.c:914
Inline: True
Direct callers:
  - net/ipv4/nexthop.c:rtm_get_nexthop_bucket
  - net/ipv4/nexthop.c:rtm_dump_nexthop_bucket_nh
  - net/ipv4/nexthop.c:nh_res_bucket_migrate
```
**Symbols:**

```
ffffffff81f73f20-ffffffff81f7413a: nh_fill_res_bucket.constprop.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/ipv4/nexthop.c (ffffffff8203a700)
Location: net/ipv4/nexthop.c:914
Inline: True
Direct callers:
  - net/ipv4/nexthop.c:rtm_get_nexthop_bucket
  - net/ipv4/nexthop.c:rtm_dump_nexthop_bucket_nh
  - net/ipv4/nexthop.c:nh_res_bucket_migrate
```
**Symbols:**

```
ffffffff8203a700-ffffffff8203a91a: nh_fill_res_bucket.constprop.0 (STB_LOCAL)
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
