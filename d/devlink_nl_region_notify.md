# Function: <code>devlink_nl_region_notify</code>

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
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
void devlink_nl_region_notify(struct devlink_region *region, struct devlink_snapshot *snapshot, enum devlink_command cmd);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/core/devlink.c (0)
Location: net/core/devlink.c:3547
Inline: False
Direct callers:
  - net/core/devlink.c:devlink_region_snapshot_create
  - net/core/devlink.c:devlink_region_destroy
  - net/core/devlink.c:devlink_region_create
  - net/core/devlink.c:devlink_nl_cmd_region_del
```
**Symbols:**

```
ffffffff8194a460-ffffffff8194a61c: devlink_nl_region_notify (STB_LOCAL)
ffffffff81952182-ffffffff819521b8: devlink_nl_region_notify.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void devlink_nl_region_notify(struct devlink_region *region, struct devlink_snapshot *snapshot, enum devlink_command cmd);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/devlink.c (ffffffff819806e0)
Location: net/core/devlink.c:3586
Inline: False
Direct callers:
  - net/core/devlink.c:devlink_region_snapshot_create
  - net/core/devlink.c:devlink_region_destroy
  - net/core/devlink.c:devlink_region_create
  - net/core/devlink.c:devlink_region_snapshot_del
```
**Symbols:**

```
ffffffff819806e0-ffffffff819808a3: devlink_nl_region_notify (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void devlink_nl_region_notify(struct devlink_region *region, struct devlink_snapshot *snapshot, enum devlink_command cmd);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/devlink.c (ffffffff81a581a0)
Location: net/core/devlink.c:3781
Inline: False
Direct callers:
  - net/core/devlink.c:devlink_region_destroy
  - net/core/devlink.c:devlink_region_create
  - net/core/devlink.c:devlink_region_snapshot_del
  - net/core/devlink.c:__devlink_region_snapshot_create
```
**Symbols:**

```
ffffffff81a581a0-ffffffff81a581fa: devlink_nl_region_notify (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void devlink_nl_region_notify(struct devlink_region *region, struct devlink_snapshot *snapshot, enum devlink_command cmd);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/devlink.c (ffffffff81a5ff70)
Location: net/core/devlink.c:4340
Inline: False
Direct callers:
  - net/core/devlink.c:devlink_region_destroy
  - net/core/devlink.c:devlink_port_region_create
  - net/core/devlink.c:devlink_region_create
  - net/core/devlink.c:devlink_region_snapshot_del
  - net/core/devlink.c:__devlink_region_snapshot_create
```
**Symbols:**

```
ffffffff81a5ff70-ffffffff81a5ffc9: devlink_nl_region_notify (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void devlink_nl_region_notify(struct devlink_region *region, struct devlink_snapshot *snapshot, enum devlink_command cmd);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/devlink.c (ffffffff81a41f60)
Location: net/core/devlink.c:4543
Inline: False
Direct callers:
  - net/core/devlink.c:devlink_region_destroy
  - net/core/devlink.c:devlink_port_region_create
  - net/core/devlink.c:devlink_region_create
  - net/core/devlink.c:devlink_region_snapshot_del
  - net/core/devlink.c:__devlink_region_snapshot_create
```
**Symbols:**

```
ffffffff81a41f60-ffffffff81a41fb9: devlink_nl_region_notify (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void devlink_nl_region_notify(struct devlink_region *region, struct devlink_snapshot *snapshot, enum devlink_command cmd);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/devlink.c (ffffffff81afa620)
Location: net/core/devlink.c:5144
Inline: False
Direct callers:
  - net/core/devlink.c:devlink_region_destroy
  - net/core/devlink.c:devlink_port_region_create
  - net/core/devlink.c:devlink_region_create
  - net/core/devlink.c:devlink_region_snapshot_del
  - net/core/devlink.c:__devlink_region_snapshot_create
```
**Symbols:**

```
ffffffff81afa620-ffffffff81afa67c: devlink_nl_region_notify (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void devlink_nl_region_notify(struct devlink_region *region, struct devlink_snapshot *snapshot, enum devlink_command cmd);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/devlink.c (ffffffff81c7f0c0)
Location: net/core/devlink.c:5637
Inline: False
Direct callers:
  - net/core/devlink.c:devlink_region_destroy
  - net/core/devlink.c:devlink_port_region_create
  - net/core/devlink.c:devlink_region_create
  - net/core/devlink.c:devlink_unregister
  - net/core/devlink.c:devlink_register
  - net/core/devlink.c:devlink_region_snapshot_del
  - net/core/devlink.c:__devlink_region_snapshot_create
```
**Symbols:**

```
ffffffff81c7f0c0-ffffffff81c7f17a: devlink_nl_region_notify (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void devlink_nl_region_notify(struct devlink_region *region, struct devlink_snapshot *snapshot, enum devlink_command cmd);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/devlink.c (ffffffff81e37f20)
Location: net/core/devlink.c:6074
Inline: False
Direct callers:
  - net/core/devlink.c:devl_region_destroy
  - net/core/devlink.c:devlink_port_region_create
  - net/core/devlink.c:devl_region_create
  - net/core/devlink.c:devlink_notify_unregister
  - net/core/devlink.c:devlink_notify_register
  - net/core/devlink.c:devlink_region_snapshot_del
  - net/core/devlink.c:__devlink_region_snapshot_create
```
**Symbols:**

```
ffffffff81e37f20-ffffffff81e37fda: devlink_nl_region_notify (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void devlink_nl_region_notify(struct devlink_region *region, struct devlink_snapshot *snapshot, enum devlink_command cmd);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/devlink/leftover.c (ffffffff82039080)
Location: net/devlink/leftover.c:4546
Inline: False
Direct callers:
  - net/devlink/leftover.c:devl_region_destroy
  - net/devlink/leftover.c:devlink_port_region_create
  - net/devlink/leftover.c:devl_region_create
  - net/devlink/leftover.c:devlink_notify_unregister
  - net/devlink/leftover.c:devlink_notify_register
  - net/devlink/leftover.c:devlink_region_snapshot_del
  - net/devlink/leftover.c:__devlink_region_snapshot_create
```
**Symbols:**

```
ffffffff82039080-ffffffff8203913e: devlink_nl_region_notify (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void devlink_nl_region_notify(struct devlink_region *region, struct devlink_snapshot *snapshot, enum devlink_command cmd);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/devlink/region.c (ffffffff8210fd20)
Location: net/devlink/region.c:229
Inline: False
Direct callers:
  - net/devlink/region.c:devl_region_destroy
  - net/devlink/region.c:devlink_port_region_create
  - net/devlink/region.c:devl_region_create
  - net/devlink/region.c:devlink_region_snapshot_del
  - net/devlink/region.c:__devlink_region_snapshot_create
  - net/devlink/region.c:devlink_regions_notify_unregister
  - net/devlink/region.c:devlink_regions_notify_register
```
**Symbols:**

```
ffffffff8210fd20-ffffffff8210fea2: devlink_nl_region_notify (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: ✅</summary>

```c
void devlink_nl_region_notify(struct devlink_region *region, struct devlink_snapshot *snapshot, enum devlink_command cmd);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/devlink.c (ffff800010c28790)
Location: net/core/devlink.c:3586
Inline: False
Direct callers:
  - net/core/devlink.c:devlink_region_snapshot_create
  - net/core/devlink.c:devlink_region_destroy
  - net/core/devlink.c:devlink_region_create
  - net/core/devlink.c:devlink_region_snapshot_del
```
**Symbols:**

```
ffff800010c28790-ffff800010c28940: devlink_nl_region_notify (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void devlink_nl_region_notify(struct devlink_region *region, struct devlink_snapshot *snapshot, enum devlink_command cmd);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/devlink.c (c0d3f9d0)
Location: net/core/devlink.c:3586
Inline: False
Direct callers:
  - net/core/devlink.c:devlink_region_snapshot_create
  - net/core/devlink.c:devlink_region_destroy
  - net/core/devlink.c:devlink_region_create
  - net/core/devlink.c:devlink_region_snapshot_del
```
**Symbols:**

```
c0d3f9d0-c0d3fbcc: devlink_nl_region_notify (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void devlink_nl_region_notify(struct devlink_region *region, struct devlink_snapshot *snapshot, enum devlink_command cmd);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/devlink.c (c000000000d1c960)
Location: net/core/devlink.c:3586
Inline: False
Direct callers:
  - net/core/devlink.c:devlink_region_snapshot_create
  - net/core/devlink.c:devlink_region_destroy
  - net/core/devlink.c:devlink_region_create
  - net/core/devlink.c:devlink_region_snapshot_del
```
**Symbols:**

```
c000000000d1c960-c000000000d1cb90: devlink_nl_region_notify (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void devlink_nl_region_notify(struct devlink_region *region, struct devlink_snapshot *snapshot, enum devlink_command cmd);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/devlink.c (ffffffe0007a0118)
Location: net/core/devlink.c:3586
Inline: False
Direct callers:
  - net/core/devlink.c:devlink_region_snapshot_create
  - net/core/devlink.c:devlink_region_destroy
  - net/core/devlink.c:devlink_region_create
  - net/core/devlink.c:devlink_region_snapshot_del
```
**Symbols:**

```
ffffffe0007a0118-ffffffe0007a026c: devlink_nl_region_notify (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: ✅</summary>

```c
void devlink_nl_region_notify(struct devlink_region *region, struct devlink_snapshot *snapshot, enum devlink_command cmd);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/devlink.c (ffffffff81920550)
Location: net/core/devlink.c:3586
Inline: False
Direct callers:
  - net/core/devlink.c:devlink_region_snapshot_create
  - net/core/devlink.c:devlink_region_destroy
  - net/core/devlink.c:devlink_region_create
  - net/core/devlink.c:devlink_region_snapshot_del
```
**Symbols:**

```
ffffffff81920550-ffffffff81920713: devlink_nl_region_notify (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void devlink_nl_region_notify(struct devlink_region *region, struct devlink_snapshot *snapshot, enum devlink_command cmd);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/devlink.c (ffffffff818da300)
Location: net/core/devlink.c:3586
Inline: False
Direct callers:
  - net/core/devlink.c:devlink_region_snapshot_create
  - net/core/devlink.c:devlink_region_destroy
  - net/core/devlink.c:devlink_region_create
  - net/core/devlink.c:devlink_region_snapshot_del
```
**Symbols:**

```
ffffffff818da300-ffffffff818da4c3: devlink_nl_region_notify (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void devlink_nl_region_notify(struct devlink_region *region, struct devlink_snapshot *snapshot, enum devlink_command cmd);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/devlink.c (ffffffff819716e0)
Location: net/core/devlink.c:3586
Inline: False
Direct callers:
  - net/core/devlink.c:devlink_region_snapshot_create
  - net/core/devlink.c:devlink_region_destroy
  - net/core/devlink.c:devlink_region_create
  - net/core/devlink.c:devlink_region_snapshot_del
```
**Symbols:**

```
ffffffff819716e0-ffffffff819718a3: devlink_nl_region_notify (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void devlink_nl_region_notify(struct devlink_region *region, struct devlink_snapshot *snapshot, enum devlink_command cmd);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/devlink.c (ffffffff81993bd0)
Location: net/core/devlink.c:3586
Inline: False
Direct callers:
  - net/core/devlink.c:devlink_region_snapshot_create
  - net/core/devlink.c:devlink_region_destroy
  - net/core/devlink.c:devlink_region_create
  - net/core/devlink.c:devlink_region_snapshot_del
```
**Symbols:**

```
ffffffff81993bd0-ffffffff81993d93: devlink_nl_region_notify (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>5.3</code> and <code>5.4</code> ✅
</li>
<li>
No changes between <code>5.4</code> and <code>5.8</code> ✅
</li>
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
<b>Arch</b>
<ul>
<li>
No changes between <code>amd64</code> and <code>arm64</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>armhf</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>ppc64el</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>riscv64</code> ✅
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
No changes between <code>generic</code> and <code>aws</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>azure</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>gcp</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>lowlatency</code> ✅
</li>
</ul>
