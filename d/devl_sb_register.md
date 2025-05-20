# Function: <code>devl_sb_register</code>

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
In <code>5.13</code>: Absent ⚠️
</li>
<li>
In <code>5.15</code>: Absent ⚠️
</li>
<li>
In <code>5.19</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int devl_sb_register(struct devlink *devlink, unsigned int sb_index, u32 size, u16 ingress_pools_count, u16 egress_pools_count, u16 ingress_tc_count, u16 egress_tc_count);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/devlink.c (ffffffff81e2fc10)
Location: net/core/devlink.c:11106
Inline: False
Direct callers:
  - net/core/devlink.c:devlink_sb_register
```
**Symbols:**

```
ffffffff81e2fc10-ffffffff81e2fcd7: devl_sb_register (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int devl_sb_register(struct devlink *devlink, unsigned int sb_index, u32 size, u16 ingress_pools_count, u16 egress_pools_count, u16 ingress_tc_count, u16 egress_tc_count);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/devlink/leftover.c (ffffffff82032fd0)
Location: net/devlink/leftover.c:7663
Inline: False
Direct callers:
  - net/devlink/leftover.c:devlink_sb_register
```
**Symbols:**

```
ffffffff82032fd0-ffffffff82033097: devl_sb_register (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int devl_sb_register(struct devlink *devlink, unsigned int sb_index, u32 size, u16 ingress_pools_count, u16 egress_pools_count, u16 ingress_tc_count, u16 egress_tc_count);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/devlink/sb.c (ffffffff821084c0)
Location: net/devlink/sb.c:934
Inline: False
Direct callers:
  - net/devlink/sb.c:devlink_sb_register
```
**Symbols:**

```
ffffffff821084c0-ffffffff821085ba: devl_sb_register (STB_GLOBAL)
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
