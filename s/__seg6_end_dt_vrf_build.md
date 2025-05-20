# Function: <code>__seg6_end_dt_vrf_build</code>

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
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
int __seg6_end_dt_vrf_build(struct seg6_local_lwt *slwt, const void *cfg, u16 family, struct netlink_ext_ack *extack);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv6/seg6_local.c (ffffffff81b8ece0)
Location: net/ipv6/seg6_local.c:465
Inline: True
Inline callers:
  - net/ipv6/seg6_local.c:seg6_end_dt4_build
```
**Symbols:**

```
ffffffff81b8e7d0-ffffffff81b8e8ab: __seg6_end_dt_vrf_build (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int __seg6_end_dt_vrf_build(struct seg6_local_lwt *slwt, const void *cfg, u16 family, struct netlink_ext_ack *extack);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/seg6_local.c (ffffffff81b7d7b0)
Location: net/ipv6/seg6_local.c:494
Inline: False
Direct callers:
  - net/ipv6/seg6_local.c:seg6_end_dt4_build
```
**Symbols:**

```
ffffffff81b7d7b0-ffffffff81b7d8ad: __seg6_end_dt_vrf_build (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int __seg6_end_dt_vrf_build(struct seg6_local_lwt *slwt, const void *cfg, u16 family, struct netlink_ext_ack *extack);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/seg6_local.c (ffffffff81c48920)
Location: net/ipv6/seg6_local.c:497
Inline: False
Direct callers:
  - net/ipv6/seg6_local.c:seg6_end_dt46_build
  - net/ipv6/seg6_local.c:seg6_end_dt4_build
```
**Symbols:**

```
ffffffff81c48920-ffffffff81c489e7: __seg6_end_dt_vrf_build (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int __seg6_end_dt_vrf_build(struct seg6_local_lwt *slwt, const void *cfg, u16 family, struct netlink_ext_ack *extack);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/seg6_local.c (ffffffff81de7ff0)
Location: net/ipv6/seg6_local.c:499
Inline: False
Direct callers:
  - net/ipv6/seg6_local.c:seg6_end_dt46_build
  - net/ipv6/seg6_local.c:seg6_end_dt4_build
```
**Symbols:**

```
ffffffff81de7ff0-ffffffff81de80c6: __seg6_end_dt_vrf_build (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int __seg6_end_dt_vrf_build(struct seg6_local_lwt *slwt, const void *cfg, u16 family, struct netlink_ext_ack *extack);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/seg6_local.c (ffffffff81fbad40)
Location: net/ipv6/seg6_local.c:624
Inline: False
Direct callers:
  - net/ipv6/seg6_local.c:seg6_end_dt46_build
  - net/ipv6/seg6_local.c:seg6_end_dt4_build
```
**Symbols:**

```
ffffffff81fbad40-ffffffff81fbae16: __seg6_end_dt_vrf_build (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
int __seg6_end_dt_vrf_build(struct seg6_local_lwt *slwt, const void *cfg, u16 family, struct netlink_ext_ack *extack);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv6/seg6_local.c (ffffffff8201d4f0)
Location: net/ipv6/seg6_local.c:951
Inline: True
Inline callers:
  - net/ipv6/seg6_local.c:seg6_end_dt46_build
  - net/ipv6/seg6_local.c:seg6_end_dt4_build
```
**Symbols:**

```
ffffffff8201b480-ffffffff8201b556: __seg6_end_dt_vrf_build (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
int __seg6_end_dt_vrf_build(struct seg6_local_lwt *slwt, const void *cfg, u16 family, struct netlink_ext_ack *extack);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv6/seg6_local.c (ffffffff820ec4d0)
Location: net/ipv6/seg6_local.c:1011
Inline: True
Inline callers:
  - net/ipv6/seg6_local.c:seg6_end_dt46_build
  - net/ipv6/seg6_local.c:seg6_end_dt4_build
```
**Symbols:**

```
ffffffff820ea440-ffffffff820ea516: __seg6_end_dt_vrf_build (STB_LOCAL)
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
