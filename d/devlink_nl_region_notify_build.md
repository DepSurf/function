# Function: <code>devlink_nl_region_notify_build</code>

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
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
struct sk_buff *devlink_nl_region_notify_build(struct devlink_region *region, struct devlink_snapshot *snapshot, enum devlink_command cmd, u32 portid, u32 seq);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/devlink.c (ffffffff81a58000)
Location: net/core/devlink.c:3730
Inline: False
Direct callers:
  - net/core/devlink.c:devlink_nl_cmd_region_new
  - net/core/devlink.c:devlink_nl_region_notify
```
**Symbols:**

```
ffffffff81a58000-ffffffff81a5819e: devlink_nl_region_notify_build (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
struct sk_buff *devlink_nl_region_notify_build(struct devlink_region *region, struct devlink_snapshot *snapshot, enum devlink_command cmd, u32 portid, u32 seq);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/devlink.c (ffffffff81a5fdb0)
Location: net/core/devlink.c:4282
Inline: False
Direct callers:
  - net/core/devlink.c:devlink_nl_cmd_region_new
  - net/core/devlink.c:devlink_nl_region_notify
```
**Symbols:**

```
ffffffff81a5fdb0-ffffffff81a5ff6f: devlink_nl_region_notify_build (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
struct sk_buff *devlink_nl_region_notify_build(struct devlink_region *region, struct devlink_snapshot *snapshot, enum devlink_command cmd, u32 portid, u32 seq);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/devlink.c (ffffffff81a41da0)
Location: net/core/devlink.c:4485
Inline: False
Direct callers:
  - net/core/devlink.c:devlink_nl_cmd_region_new
  - net/core/devlink.c:devlink_nl_region_notify
```
**Symbols:**

```
ffffffff81a41da0-ffffffff81a41f5e: devlink_nl_region_notify_build (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
struct sk_buff *devlink_nl_region_notify_build(struct devlink_region *region, struct devlink_snapshot *snapshot, enum devlink_command cmd, u32 portid, u32 seq);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/devlink.c (ffffffff81afa460)
Location: net/core/devlink.c:5086
Inline: False
Direct callers:
  - net/core/devlink.c:devlink_nl_cmd_region_new
  - net/core/devlink.c:devlink_nl_region_notify
```
**Symbols:**

```
ffffffff81afa460-ffffffff81afa61e: devlink_nl_region_notify_build (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
struct sk_buff *devlink_nl_region_notify_build(struct devlink_region *region, struct devlink_snapshot *snapshot, enum devlink_command cmd, u32 portid, u32 seq);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/devlink.c (ffffffff81c7eec0)
Location: net/core/devlink.c:5579
Inline: False
Direct callers:
  - net/core/devlink.c:devlink_nl_cmd_region_new
  - net/core/devlink.c:devlink_nl_region_notify
```
**Symbols:**

```
ffffffff81c7eec0-ffffffff81c7f0be: devlink_nl_region_notify_build (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
struct sk_buff *devlink_nl_region_notify_build(struct devlink_region *region, struct devlink_snapshot *snapshot, enum devlink_command cmd, u32 portid, u32 seq);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/devlink.c (ffffffff81e37d10)
Location: net/core/devlink.c:6016
Inline: False
Direct callers:
  - net/core/devlink.c:devlink_nl_cmd_region_new
  - net/core/devlink.c:devlink_nl_region_notify
```
**Symbols:**

```
ffffffff81e37d10-ffffffff81e37f0e: devlink_nl_region_notify_build (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
struct sk_buff *devlink_nl_region_notify_build(struct devlink_region *region, struct devlink_snapshot *snapshot, enum devlink_command cmd, u32 portid, u32 seq);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/devlink/leftover.c (ffffffff82038e70)
Location: net/devlink/leftover.c:4488
Inline: False
Direct callers:
  - net/devlink/leftover.c:devlink_nl_cmd_region_new
  - net/devlink/leftover.c:devlink_nl_region_notify
```
**Symbols:**

```
ffffffff82038e70-ffffffff82039066: devlink_nl_region_notify_build (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
struct sk_buff *devlink_nl_region_notify_build(struct devlink_region *region, struct devlink_snapshot *snapshot, enum devlink_command cmd, u32 portid, u32 seq);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/devlink/region.c (ffffffff8210fac0)
Location: net/devlink/region.c:172
Inline: False
Direct callers:
  - net/devlink/region.c:devlink_nl_region_new_doit
  - net/devlink/region.c:devlink_nl_region_notify
```
**Symbols:**

```
ffffffff8210fac0-ffffffff8210fd10: devlink_nl_region_notify_build (STB_LOCAL)
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
No changes between <code>5.8</code> and <code>5.11</code> ✅
</li>
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
