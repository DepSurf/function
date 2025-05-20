# Function: <code>__devlink_snapshot_id_increment</code>

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
int __devlink_snapshot_id_increment(struct devlink *devlink, u32 id);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/devlink.c (ffffffff81a52d80)
Location: net/core/devlink.c:3813
Inline: False
Direct callers:
  - net/core/devlink.c:__devlink_region_snapshot_create
```
**Symbols:**

```
ffffffff81a52d80-ffffffff81a52e09: __devlink_snapshot_id_increment (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int __devlink_snapshot_id_increment(struct devlink *devlink, u32 id);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/devlink.c (ffffffff81a59700)
Location: net/core/devlink.c:4372
Inline: False
Direct callers:
  - net/core/devlink.c:__devlink_region_snapshot_create
```
**Symbols:**

```
ffffffff81a59700-ffffffff81a59789: __devlink_snapshot_id_increment (STB_LOCAL)
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
In net/core/devlink.c (ffffffff81a421f5)
Location: net/core/devlink.c:4575
Inline: True
Inline callers:
  - net/core/devlink.c:__devlink_region_snapshot_create
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
In net/core/devlink.c (ffffffff81afa8b5)
Location: net/core/devlink.c:5176
Inline: True
Inline callers:
  - net/core/devlink.c:__devlink_region_snapshot_create
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
In net/core/devlink.c (ffffffff81c7f3e5)
Location: net/core/devlink.c:5671
Inline: True
Inline callers:
  - net/core/devlink.c:__devlink_region_snapshot_create
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/core/devlink.c (ffffffff81e382a5)
Location: net/core/devlink.c:6108
Inline: True
Inline callers:
  - net/core/devlink.c:__devlink_region_snapshot_create
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/devlink/leftover.c (ffffffff820391c5)
Location: net/devlink/leftover.c:4580
Inline: True
Inline callers:
  - net/devlink/leftover.c:__devlink_region_snapshot_create
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/devlink/region.c (ffffffff8210ff64)
Location: net/devlink/region.c:279
Inline: True
Inline callers:
  - net/devlink/region.c:__devlink_region_snapshot_create
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
</ul>
