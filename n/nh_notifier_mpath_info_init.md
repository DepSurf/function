# Function: <code>nh_notifier_mpath_info_init</code>

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
int nh_notifier_mpath_info_init(struct nh_notifier_info *info, struct nh_group *nhg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/nexthop.c (ffffffff81af5c10)
Location: net/ipv4/nexthop.c:119
Inline: False
Direct callers:
  - net/ipv4/nexthop.c:register_nexthop_notifier
  - net/ipv4/nexthop.c:replace_nexthop_grp
  - net/ipv4/nexthop.c:call_nexthop_notifiers
```
**Symbols:**

```
ffffffff81af5c10-ffffffff81af5d46: nh_notifier_mpath_info_init (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int nh_notifier_mpath_info_init(struct nh_notifier_info *info, struct nh_group *nhg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ipv4/nexthop.c (0)
Location: net/ipv4/nexthop.c:119
Inline: False
Direct callers:
  - net/ipv4/nexthop.c:replace_nexthop_grp
  - net/ipv4/nexthop.c:nh_notifier_info_init
```
**Symbols:**

```
ffffffff81bb7b30-ffffffff81bb7ca9: nh_notifier_mpath_info_init (STB_LOCAL)
ffffffff81d3e312-ffffffff81d3e38f: nh_notifier_mpath_info_init.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int nh_notifier_mpath_info_init(struct nh_notifier_info *info, struct nh_group *nhg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ipv4/nexthop.c (0)
Location: net/ipv4/nexthop.c:120
Inline: False
Direct callers:
  - net/ipv4/nexthop.c:replace_nexthop_grp
  - net/ipv4/nexthop.c:nh_notifier_info_init
```
**Symbols:**

```
ffffffff81d4b8d0-ffffffff81d4ba5a: nh_notifier_mpath_info_init (STB_LOCAL)
ffffffff81f0abf0-ffffffff81f0ac6d: nh_notifier_mpath_info_init.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
int nh_notifier_mpath_info_init(struct nh_notifier_info *info, struct nh_group *nhg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ipv4/nexthop.c (0)
Location: net/ipv4/nexthop.c:120
Inline: False
Direct callers:
  - net/ipv4/nexthop.c:replace_nexthop_grp
  - net/ipv4/nexthop.c:nh_notifier_info_init
```
**Symbols:**

```
ffffffff81f15520-ffffffff81f156aa: nh_notifier_mpath_info_init (STB_LOCAL)
ffffffff820b24b5-ffffffff820b2532: nh_notifier_mpath_info_init.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
int nh_notifier_mpath_info_init(struct nh_notifier_info *info, struct nh_group *nhg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ipv4/nexthop.c (0)
Location: net/ipv4/nexthop.c:120
Inline: False
Direct callers:
  - net/ipv4/nexthop.c:replace_nexthop_grp
  - net/ipv4/nexthop.c:nh_notifier_info_init
```
**Symbols:**

```
ffffffff81f751b0-ffffffff81f7533a: nh_notifier_mpath_info_init (STB_LOCAL)
ffffffff8213366d-ffffffff821336ea: nh_notifier_mpath_info_init.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
int nh_notifier_mpath_info_init(struct nh_notifier_info *info, struct nh_group *nhg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ipv4/nexthop.c (0)
Location: net/ipv4/nexthop.c:120
Inline: False
Direct callers:
  - net/ipv4/nexthop.c:replace_nexthop_grp
  - net/ipv4/nexthop.c:nh_notifier_info_init
```
**Symbols:**

```
ffffffff8203b4d0-ffffffff8203b65a: nh_notifier_mpath_info_init (STB_LOCAL)
ffffffff8221503d-ffffffff822150ba: nh_notifier_mpath_info_init.cold (STB_LOCAL)
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
