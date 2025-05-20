# Function: <code>__devlink_snapshot_id_decrement</code>

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
void __devlink_snapshot_id_decrement(struct devlink *devlink, u32 id);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/devlink.c (ffffffff81a51320)
Location: net/core/devlink.c:3849
Inline: False
Direct callers:
  - net/core/devlink.c:devlink_region_snapshot_id_put
  - net/core/devlink.c:devlink_nl_cmd_region_new
  - net/core/devlink.c:devlink_region_snapshot_del
```
**Symbols:**

```
ffffffff81a51320-ffffffff81a51393: __devlink_snapshot_id_decrement (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void __devlink_snapshot_id_decrement(struct devlink *devlink, u32 id);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/devlink.c (ffffffff81a57430)
Location: net/core/devlink.c:4408
Inline: False
Direct callers:
  - net/core/devlink.c:devlink_region_snapshot_id_put
  - net/core/devlink.c:devlink_nl_cmd_region_new
  - net/core/devlink.c:devlink_region_snapshot_del
```
**Symbols:**

```
ffffffff81a57430-ffffffff81a574a3: __devlink_snapshot_id_decrement (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void __devlink_snapshot_id_decrement(struct devlink *devlink, u32 id);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/devlink.c (ffffffff81a3a290)
Location: net/core/devlink.c:4611
Inline: False
Direct callers:
  - net/core/devlink.c:devlink_region_snapshot_id_put
  - net/core/devlink.c:devlink_nl_cmd_region_new
  - net/core/devlink.c:devlink_region_snapshot_del
```
**Symbols:**

```
ffffffff81a3a290-ffffffff81a3a303: __devlink_snapshot_id_decrement (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void __devlink_snapshot_id_decrement(struct devlink *devlink, u32 id);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/devlink.c (ffffffff81aeff50)
Location: net/core/devlink.c:5212
Inline: False
Direct callers:
  - net/core/devlink.c:devlink_region_snapshot_id_put
  - net/core/devlink.c:devlink_nl_cmd_region_new
  - net/core/devlink.c:devlink_region_snapshot_del
```
**Symbols:**

```
ffffffff81aeff50-ffffffff81aeffc3: __devlink_snapshot_id_decrement (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void __devlink_snapshot_id_decrement(struct devlink *devlink, u32 id);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/devlink.c (ffffffff81c73500)
Location: net/core/devlink.c:5707
Inline: False
Direct callers:
  - net/core/devlink.c:devlink_region_snapshot_id_put
  - net/core/devlink.c:devlink_nl_cmd_region_new
  - net/core/devlink.c:devlink_region_snapshot_del
```
**Symbols:**

```
ffffffff81c73500-ffffffff81c73599: __devlink_snapshot_id_decrement (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void __devlink_snapshot_id_decrement(struct devlink *devlink, u32 id);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/devlink.c (ffffffff81e2c280)
Location: net/core/devlink.c:6151
Inline: False
Direct callers:
  - net/core/devlink.c:devlink_region_snapshot_id_put
  - net/core/devlink.c:devlink_nl_cmd_region_new
  - net/core/devlink.c:devlink_region_snapshot_del
```
**Symbols:**

```
ffffffff81e2c280-ffffffff81e2c33d: __devlink_snapshot_id_decrement (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void __devlink_snapshot_id_decrement(struct devlink *devlink, u32 id);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/devlink/leftover.c (ffffffff8202ffd0)
Location: net/devlink/leftover.c:4623
Inline: False
Direct callers:
  - net/devlink/leftover.c:devlink_region_snapshot_id_put
  - net/devlink/leftover.c:devlink_nl_cmd_region_new
  - net/devlink/leftover.c:devlink_region_snapshot_del
```
**Symbols:**

```
ffffffff8202ffd0-ffffffff8203008d: __devlink_snapshot_id_decrement (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void __devlink_snapshot_id_decrement(struct devlink *devlink, u32 id);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/devlink/region.c (ffffffff8210f410)
Location: net/devlink/region.c:322
Inline: False
Direct callers:
  - net/devlink/region.c:devlink_region_snapshot_id_put
  - net/devlink/region.c:devlink_nl_region_new_doit
  - net/devlink/region.c:devlink_region_snapshot_del
```
**Symbols:**

```
ffffffff8210f410-ffffffff8210f4cd: __devlink_snapshot_id_decrement (STB_LOCAL)
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
