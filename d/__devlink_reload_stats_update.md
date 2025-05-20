# Function: <code>__devlink_reload_stats_update</code>

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
<summary>In <code>5.11</code>: ✅</summary>

```c
void __devlink_reload_stats_update(struct devlink *devlink, u32 *reload_stats, enum devlink_reload_limit limit, u32 actions_performed);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/devlink.c (ffffffff81a670e0)
Location: net/core/devlink.c:3128
Inline: False
Direct callers:
  - net/core/devlink.c:devlink_reload
  - net/core/devlink.c:devlink_remote_reload_actions_performed
```
**Symbols:**

```
ffffffff81a670e0-ffffffff81a6717a: __devlink_reload_stats_update (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void __devlink_reload_stats_update(struct devlink *devlink, u32 *reload_stats, enum devlink_reload_limit limit, u32 actions_performed);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/devlink.c (ffffffff81a4a300)
Location: net/core/devlink.c:3331
Inline: False
Direct callers:
  - net/core/devlink.c:devlink_reload
  - net/core/devlink.c:devlink_remote_reload_actions_performed
```
**Symbols:**

```
ffffffff81a4a300-ffffffff81a4a368: __devlink_reload_stats_update (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void __devlink_reload_stats_update(struct devlink *devlink, u32 *reload_stats, enum devlink_reload_limit limit, u32 actions_performed);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/devlink.c (ffffffff81b02360)
Location: net/core/devlink.c:3896
Inline: False
Direct callers:
  - net/core/devlink.c:devlink_reload
  - net/core/devlink.c:devlink_remote_reload_actions_performed
```
**Symbols:**

```
ffffffff81b02360-ffffffff81b023c8: __devlink_reload_stats_update (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void __devlink_reload_stats_update(struct devlink *devlink, u32 *reload_stats, enum devlink_reload_limit limit, u32 actions_performed);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/devlink.c (ffffffff81c85db0)
Location: net/core/devlink.c:4411
Inline: False
Direct callers:
  - net/core/devlink.c:devlink_reload
  - net/core/devlink.c:devlink_remote_reload_actions_performed
```
**Symbols:**

```
ffffffff81c85db0-ffffffff81c85e31: __devlink_reload_stats_update (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void __devlink_reload_stats_update(struct devlink *devlink, u32 *reload_stats, enum devlink_reload_limit limit, u32 actions_performed);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/devlink.c (ffffffff81e400d0)
Location: net/core/devlink.c:4677
Inline: False
Direct callers:
  - net/core/devlink.c:devlink_reload
  - net/core/devlink.c:devlink_remote_reload_actions_performed
```
**Symbols:**

```
ffffffff81e400d0-ffffffff81e4014c: __devlink_reload_stats_update (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void __devlink_reload_stats_update(struct devlink *devlink, u32 *reload_stats, enum devlink_reload_limit limit, u32 actions_performed);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/devlink/dev.c (ffffffff820444a0)
Location: net/devlink/dev.c:248
Inline: False
Direct callers:
  - net/devlink/dev.c:devlink_reload
  - net/devlink/dev.c:devlink_remote_reload_actions_performed
```
**Symbols:**

```
ffffffff820444a0-ffffffff8204451c: __devlink_reload_stats_update (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void __devlink_reload_stats_update(struct devlink *devlink, u32 *reload_stats, enum devlink_reload_limit limit, u32 actions_performed);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/devlink/dev.c (ffffffff821033a0)
Location: net/devlink/dev.c:327
Inline: False
Direct callers:
  - net/devlink/dev.c:devlink_reload
  - net/devlink/dev.c:devlink_remote_reload_actions_performed
```
**Symbols:**

```
ffffffff821033a0-ffffffff8210341c: __devlink_reload_stats_update (STB_LOCAL)
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
