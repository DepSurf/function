# Function: <code>__nh_notifier_single_info_init</code>

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
<summary>In <code>5.11</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/ipv4/nexthop.c (ffffffff81b09210)
Location: net/ipv4/nexthop.c:45
Inline: True
Direct callers:
  - net/ipv4/nexthop.c:nexthops_dump
  - net/ipv4/nexthop.c:call_nexthop_notifiers
```
**Symbols:**

```
ffffffff81b09210-ffffffff81b09282: __nh_notifier_single_info_init.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv4/nexthop.c (ffffffff81af613b)
Location: net/ipv4/nexthop.c:84
Inline: True
Inline callers:
  - net/ipv4/nexthop.c:register_nexthop_notifier
  - net/ipv4/nexthop.c:__call_nexthop_res_bucket_notifiers
  - net/ipv4/nexthop.c:__call_nexthop_res_bucket_notifiers
  - net/ipv4/nexthop.c:call_nexthop_notifiers
  - net/ipv4/nexthop.c:nh_notifier_res_table_info_init
  - net/ipv4/nexthop.c:nh_notifier_mpath_info_init
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline, Transformation ⚠️</summary>

```c
void __nh_notifier_single_info_init(struct nh_notifier_single_info *nh_info, const struct nh_info *nhi);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/ipv4/nexthop.c (ffffffff81bb8252)
Location: net/ipv4/nexthop.c:84
Inline: True
Inline callers:
  - net/ipv4/nexthop.c:nh_notifier_info_init
  - net/ipv4/nexthop.c:nh_notifier_mpath_info_init
Direct callers:
  - net/ipv4/nexthop.c:__call_nexthop_res_bucket_notifiers
  - net/ipv4/nexthop.c:__call_nexthop_res_bucket_notifiers
  - net/ipv4/nexthop.c:nh_notifier_info_init
```
**Symbols:**

```
ffffffff81bb42b0-ffffffff81bb4354: __nh_notifier_single_info_init (STB_LOCAL)
ffffffff81d3dc2e-ffffffff81d3dc58: __nh_notifier_single_info_init.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline, Transformation ⚠️</summary>

```c
void __nh_notifier_single_info_init(struct nh_notifier_single_info *nh_info, const struct nh_info *nhi);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/ipv4/nexthop.c (ffffffff81d4c068)
Location: net/ipv4/nexthop.c:85
Inline: True
Inline callers:
  - net/ipv4/nexthop.c:nh_notifier_info_init
  - net/ipv4/nexthop.c:nh_notifier_mpath_info_init
Direct callers:
  - net/ipv4/nexthop.c:__call_nexthop_res_bucket_notifiers
  - net/ipv4/nexthop.c:__call_nexthop_res_bucket_notifiers
  - net/ipv4/nexthop.c:nh_notifier_info_init
```
**Symbols:**

```
ffffffff81d47c10-ffffffff81d47cc7: __nh_notifier_single_info_init (STB_LOCAL)
ffffffff81f0a4e9-ffffffff81f0a513: __nh_notifier_single_info_init.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline, Transformation ⚠️</summary>

```c
void __nh_notifier_single_info_init(struct nh_notifier_single_info *nh_info, const struct nh_info *nhi);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/ipv4/nexthop.c (ffffffff81f15828)
Location: net/ipv4/nexthop.c:85
Inline: True
Inline callers:
  - net/ipv4/nexthop.c:nh_notifier_info_init
  - net/ipv4/nexthop.c:nh_notifier_mpath_info_init
Direct callers:
  - net/ipv4/nexthop.c:__call_nexthop_res_bucket_notifiers
  - net/ipv4/nexthop.c:__call_nexthop_res_bucket_notifiers
  - net/ipv4/nexthop.c:nh_notifier_info_init
```
**Symbols:**

```
ffffffff81f11120-ffffffff81f111d7: __nh_notifier_single_info_init (STB_LOCAL)
ffffffff820b1d9e-ffffffff820b1dc8: __nh_notifier_single_info_init.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline, Transformation ⚠️</summary>

```c
void __nh_notifier_single_info_init(struct nh_notifier_single_info *nh_info, const struct nh_info *nhi);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/ipv4/nexthop.c (ffffffff81f754b8)
Location: net/ipv4/nexthop.c:85
Inline: True
Inline callers:
  - net/ipv4/nexthop.c:nh_notifier_info_init
  - net/ipv4/nexthop.c:nh_notifier_mpath_info_init
Direct callers:
  - net/ipv4/nexthop.c:__call_nexthop_res_bucket_notifiers
  - net/ipv4/nexthop.c:__call_nexthop_res_bucket_notifiers
  - net/ipv4/nexthop.c:nh_notifier_info_init
```
**Symbols:**

```
ffffffff81f70e10-ffffffff81f70ec7: __nh_notifier_single_info_init (STB_LOCAL)
ffffffff82132fab-ffffffff82132fd5: __nh_notifier_single_info_init.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline, Transformation ⚠️</summary>

```c
void __nh_notifier_single_info_init(struct nh_notifier_single_info *nh_info, const struct nh_info *nhi);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/ipv4/nexthop.c (ffffffff8203bc5c)
Location: net/ipv4/nexthop.c:85
Inline: True
Inline callers:
  - net/ipv4/nexthop.c:nh_notifier_info_init
  - net/ipv4/nexthop.c:nh_notifier_mpath_info_init
Direct callers:
  - net/ipv4/nexthop.c:__call_nexthop_res_bucket_notifiers
  - net/ipv4/nexthop.c:__call_nexthop_res_bucket_notifiers
  - net/ipv4/nexthop.c:nh_notifier_info_init
```
**Symbols:**

```
ffffffff82037570-ffffffff82037627: __nh_notifier_single_info_init (STB_LOCAL)
ffffffff8221495a-ffffffff82214984: __nh_notifier_single_info_init.cold (STB_LOCAL)
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
