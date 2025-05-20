# Function: <code>replace_nexthop_grp_res</code>

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
void replace_nexthop_grp_res(struct nh_group *oldg, struct nh_group *newg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/nexthop.c (ffffffff81af7b40)
Location: net/ipv4/nexthop.c:1692
Inline: False
Direct callers:
  - net/ipv4/nexthop.c:replace_nexthop_grp
  - net/ipv4/nexthop.c:remove_nh_grp_entry
```
**Symbols:**

```
ffffffff81af7b40-ffffffff81af7c8a: replace_nexthop_grp_res (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
void replace_nexthop_grp_res(struct nh_group *oldg, struct nh_group *newg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ipv4/nexthop.c (0)
Location: net/ipv4/nexthop.c:1692
Inline: False
Direct callers:
  - net/ipv4/nexthop.c:replace_nexthop_grp
  - net/ipv4/nexthop.c:remove_nh_grp_entry
```
**Symbols:**

```
ffffffff81bb79a0-ffffffff81bb7b10: replace_nexthop_grp_res (STB_LOCAL)
ffffffff81d3e2bf-ffffffff81d3e312: replace_nexthop_grp_res.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
void replace_nexthop_grp_res(struct nh_group *oldg, struct nh_group *newg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ipv4/nexthop.c (0)
Location: net/ipv4/nexthop.c:1693
Inline: False
Direct callers:
  - net/ipv4/nexthop.c:replace_nexthop_grp
  - net/ipv4/nexthop.c:remove_nh_grp_entry
```
**Symbols:**

```
ffffffff81d4b710-ffffffff81d4b895: replace_nexthop_grp_res (STB_LOCAL)
ffffffff81f0ab9d-ffffffff81f0abf0: replace_nexthop_grp_res.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
void replace_nexthop_grp_res(struct nh_group *oldg, struct nh_group *newg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ipv4/nexthop.c (0)
Location: net/ipv4/nexthop.c:1693
Inline: False
Direct callers:
  - net/ipv4/nexthop.c:replace_nexthop_grp
  - net/ipv4/nexthop.c:remove_nh_grp_entry
```
**Symbols:**

```
ffffffff81f14e90-ffffffff81f15015: replace_nexthop_grp_res (STB_LOCAL)
ffffffff820b2426-ffffffff820b2479: replace_nexthop_grp_res.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
void replace_nexthop_grp_res(struct nh_group *oldg, struct nh_group *newg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ipv4/nexthop.c (0)
Location: net/ipv4/nexthop.c:1693
Inline: False
Direct callers:
  - net/ipv4/nexthop.c:replace_nexthop_grp
  - net/ipv4/nexthop.c:remove_nh_grp_entry
```
**Symbols:**

```
ffffffff81f74b60-ffffffff81f74ce0: replace_nexthop_grp_res (STB_LOCAL)
ffffffff821335d6-ffffffff82133631: replace_nexthop_grp_res.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
void replace_nexthop_grp_res(struct nh_group *oldg, struct nh_group *newg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ipv4/nexthop.c (0)
Location: net/ipv4/nexthop.c:1716
Inline: False
Direct callers:
  - net/ipv4/nexthop.c:replace_nexthop_grp
  - net/ipv4/nexthop.c:remove_nh_grp_entry
```
**Symbols:**

```
ffffffff8203b300-ffffffff8203b480: replace_nexthop_grp_res (STB_LOCAL)
ffffffff82214fe2-ffffffff8221503d: replace_nexthop_grp_res.cold (STB_LOCAL)
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
