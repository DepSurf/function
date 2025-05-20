# Function: <code>devlink_region_snapshot_del</code>

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
<summary>In <code>5.3</code>: ✅</summary>

```c
void devlink_region_snapshot_del(struct devlink_snapshot *snapshot);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/devlink.c (ffffffff81946f60)
Location: net/core/devlink.c:374
Inline: False
Direct callers:
  - net/core/devlink.c:devlink_region_destroy
  - net/core/devlink.c:devlink_nl_cmd_region_del
```
**Symbols:**

```
ffffffff81946f60-ffffffff81946fb3: devlink_region_snapshot_del (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void devlink_region_snapshot_del(struct devlink_region *region, struct devlink_snapshot *snapshot);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/devlink.c (ffffffff819808b0)
Location: net/core/devlink.c:3638
Inline: False
Direct callers:
  - net/core/devlink.c:devlink_region_destroy
  - net/core/devlink.c:devlink_nl_cmd_region_del
```
**Symbols:**

```
ffffffff819808b0-ffffffff81980913: devlink_region_snapshot_del (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void devlink_region_snapshot_del(struct devlink_region *region, struct devlink_snapshot *snapshot);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/devlink.c (ffffffff81a58200)
Location: net/core/devlink.c:3981
Inline: False
Direct callers:
  - net/core/devlink.c:devlink_region_destroy
  - net/core/devlink.c:devlink_nl_cmd_region_new
  - net/core/devlink.c:devlink_nl_cmd_region_del
```
**Symbols:**

```
ffffffff81a58200-ffffffff81a5827a: devlink_region_snapshot_del (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void devlink_region_snapshot_del(struct devlink_region *region, struct devlink_snapshot *snapshot);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/devlink.c (ffffffff81a5ffd0)
Location: net/core/devlink.c:4540
Inline: False
Direct callers:
  - net/core/devlink.c:devlink_region_destroy
  - net/core/devlink.c:devlink_nl_cmd_region_new
  - net/core/devlink.c:devlink_nl_cmd_region_del
```
**Symbols:**

```
ffffffff81a5ffd0-ffffffff81a6004a: devlink_region_snapshot_del (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void devlink_region_snapshot_del(struct devlink_region *region, struct devlink_snapshot *snapshot);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/devlink.c (ffffffff81a41fc0)
Location: net/core/devlink.c:4743
Inline: False
Direct callers:
  - net/core/devlink.c:devlink_region_destroy
  - net/core/devlink.c:devlink_nl_cmd_region_new
  - net/core/devlink.c:devlink_nl_cmd_region_del
```
**Symbols:**

```
ffffffff81a41fc0-ffffffff81a4203a: devlink_region_snapshot_del (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void devlink_region_snapshot_del(struct devlink_region *region, struct devlink_snapshot *snapshot);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/devlink.c (ffffffff81afa680)
Location: net/core/devlink.c:5344
Inline: False
Direct callers:
  - net/core/devlink.c:devlink_region_destroy
  - net/core/devlink.c:devlink_nl_cmd_region_new
  - net/core/devlink.c:devlink_nl_cmd_region_del
```
**Symbols:**

```
ffffffff81afa680-ffffffff81afa6fa: devlink_region_snapshot_del (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void devlink_region_snapshot_del(struct devlink_region *region, struct devlink_snapshot *snapshot);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/devlink.c (ffffffff81c7f180)
Location: net/core/devlink.c:5839
Inline: False
Direct callers:
  - net/core/devlink.c:devlink_region_destroy
  - net/core/devlink.c:devlink_nl_cmd_region_new
  - net/core/devlink.c:devlink_nl_cmd_region_del
```
**Symbols:**

```
ffffffff81c7f180-ffffffff81c7f202: devlink_region_snapshot_del (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void devlink_region_snapshot_del(struct devlink_region *region, struct devlink_snapshot *snapshot);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/devlink.c (ffffffff81e37ff0)
Location: net/core/devlink.c:6286
Inline: False
Direct callers:
  - net/core/devlink.c:devl_region_destroy
  - net/core/devlink.c:devlink_nl_cmd_region_new
  - net/core/devlink.c:devlink_nl_cmd_region_del
```
**Symbols:**

```
ffffffff81e37ff0-ffffffff81e38072: devlink_region_snapshot_del (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void devlink_region_snapshot_del(struct devlink_region *region, struct devlink_snapshot *snapshot);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/devlink/leftover.c (ffffffff82039370)
Location: net/devlink/leftover.c:4758
Inline: False
Direct callers:
  - net/devlink/leftover.c:devl_region_destroy
  - net/devlink/leftover.c:devlink_nl_cmd_region_new
  - net/devlink/leftover.c:devlink_nl_cmd_region_del
```
**Symbols:**

```
ffffffff82039370-ffffffff820393f2: devlink_region_snapshot_del (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void devlink_region_snapshot_del(struct devlink_region *region, struct devlink_snapshot *snapshot);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/devlink/region.c (ffffffff82110110)
Location: net/devlink/region.c:457
Inline: False
Direct callers:
  - net/devlink/region.c:devl_region_destroy
  - net/devlink/region.c:devlink_nl_region_new_doit
  - net/devlink/region.c:devlink_nl_region_del_doit
```
**Symbols:**

```
ffffffff82110110-ffffffff82110192: devlink_region_snapshot_del (STB_LOCAL)
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
void devlink_region_snapshot_del(struct devlink_region *region, struct devlink_snapshot *snapshot);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/devlink.c (ffff800010c28940)
Location: net/core/devlink.c:3638
Inline: False
Direct callers:
  - net/core/devlink.c:devlink_region_destroy
  - net/core/devlink.c:devlink_nl_cmd_region_del
```
**Symbols:**

```
ffff800010c28940-ffff800010c289b4: devlink_region_snapshot_del (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void devlink_region_snapshot_del(struct devlink_region *region, struct devlink_snapshot *snapshot);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/devlink.c (c0d3fbcc)
Location: net/core/devlink.c:3638
Inline: False
Direct callers:
  - net/core/devlink.c:devlink_region_destroy
  - net/core/devlink.c:devlink_nl_cmd_region_del
```
**Symbols:**

```
c0d3fbcc-c0d3fc2c: devlink_region_snapshot_del (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void devlink_region_snapshot_del(struct devlink_region *region, struct devlink_snapshot *snapshot);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/devlink.c (c000000000d1cb90)
Location: net/core/devlink.c:3638
Inline: False
Direct callers:
  - net/core/devlink.c:devlink_region_destroy
  - net/core/devlink.c:devlink_nl_cmd_region_del
```
**Symbols:**

```
c000000000d1cb90-c000000000d1cc4c: devlink_region_snapshot_del (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void devlink_region_snapshot_del(struct devlink_region *region, struct devlink_snapshot *snapshot);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/devlink.c (ffffffe0007a026c)
Location: net/core/devlink.c:3638
Inline: False
Direct callers:
  - net/core/devlink.c:devlink_region_destroy
  - net/core/devlink.c:devlink_nl_cmd_region_del
```
**Symbols:**

```
ffffffe0007a026c-ffffffe0007a02d0: devlink_region_snapshot_del (STB_LOCAL)
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
void devlink_region_snapshot_del(struct devlink_region *region, struct devlink_snapshot *snapshot);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/devlink.c (ffffffff81920720)
Location: net/core/devlink.c:3638
Inline: False
Direct callers:
  - net/core/devlink.c:devlink_region_destroy
  - net/core/devlink.c:devlink_nl_cmd_region_del
```
**Symbols:**

```
ffffffff81920720-ffffffff81920783: devlink_region_snapshot_del (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void devlink_region_snapshot_del(struct devlink_region *region, struct devlink_snapshot *snapshot);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/devlink.c (ffffffff818da4d0)
Location: net/core/devlink.c:3638
Inline: False
Direct callers:
  - net/core/devlink.c:devlink_region_destroy
  - net/core/devlink.c:devlink_nl_cmd_region_del
```
**Symbols:**

```
ffffffff818da4d0-ffffffff818da533: devlink_region_snapshot_del (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void devlink_region_snapshot_del(struct devlink_region *region, struct devlink_snapshot *snapshot);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/devlink.c (ffffffff819718b0)
Location: net/core/devlink.c:3638
Inline: False
Direct callers:
  - net/core/devlink.c:devlink_region_destroy
  - net/core/devlink.c:devlink_nl_cmd_region_del
```
**Symbols:**

```
ffffffff819718b0-ffffffff81971913: devlink_region_snapshot_del (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void devlink_region_snapshot_del(struct devlink_region *region, struct devlink_snapshot *snapshot);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/devlink.c (ffffffff81993da0)
Location: net/core/devlink.c:3638
Inline: False
Direct callers:
  - net/core/devlink.c:devlink_region_destroy
  - net/core/devlink.c:devlink_nl_cmd_region_del
```
**Symbols:**

```
ffffffff81993da0-ffffffff81993e03: devlink_region_snapshot_del (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
<details>
<summary>Changed between <code>5.3</code> and <code>5.4</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>struct devlink_region *region</code>
</li>
<li>
<b>Param reordered. </b>
<code>snapshot</code> ➡️ <code>region, snapshot</code>
</li>
</ul>
</details>
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
