# Function: <code>devlink_reload_limit_is_supported</code>

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
<summary>In <code>5.11</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/core/devlink.c (ffffffff81a6752d)
Location: net/core/devlink.c:515
Inline: True
Inline callers:
  - net/core/devlink.c:devlink_nl_cmd_reload
  - net/core/devlink.c:devlink_reload_stats_put
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
In net/core/devlink.c (ffffffff81a4aa42)
Location: net/core/devlink.c:518
Inline: True
Inline callers:
  - net/core/devlink.c:devlink_nl_cmd_reload
  - net/core/devlink.c:devlink_reload_stats_put
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
In net/core/devlink.c (ffffffff81b02c3a)
Location: net/core/devlink.c:615
Inline: True
Inline callers:
  - net/core/devlink.c:devlink_nl_cmd_reload
  - net/core/devlink.c:devlink_reload_stats_put
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
In net/core/devlink.c (ffffffff81c86406)
Location: net/core/devlink.c:832
Inline: True
Inline callers:
  - net/core/devlink.c:devlink_nl_cmd_reload
  - net/core/devlink.c:devlink_reload_stats_put
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
bool devlink_reload_limit_is_supported(struct devlink *devlink, enum devlink_reload_limit limit);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/devlink.c (ffffffff81e3fc42)
Location: net/core/devlink.c:1008
Inline: True
Inline callers:
  - net/core/devlink.c:devlink_reload_stats_put
Direct callers:
  - net/core/devlink.c:devlink_nl_cmd_reload
```
**Symbols:**

```
ffffffff81e2a9e0-ffffffff81e2aa04: devlink_reload_limit_is_supported (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
bool devlink_reload_limit_is_supported(struct devlink *devlink, enum devlink_reload_limit limit);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/devlink/dev.c (ffffffff8204319f)
Location: net/devlink/dev.c:52
Inline: True
Inline callers:
  - net/devlink/dev.c:devlink_reload_stats_put
Direct callers:
  - net/devlink/dev.c:devlink_nl_cmd_reload
```
**Symbols:**

```
ffffffff82042b10-ffffffff82042b34: devlink_reload_limit_is_supported (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
bool devlink_reload_limit_is_supported(struct devlink *devlink, enum devlink_reload_limit limit);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/devlink/dev.c (ffffffff821025ef)
Location: net/devlink/dev.c:53
Inline: True
Inline callers:
  - net/devlink/dev.c:devlink_reload_stats_put
Direct callers:
  - net/devlink/dev.c:devlink_nl_reload_doit
```
**Symbols:**

```
ffffffff82101e50-ffffffff82101e74: devlink_reload_limit_is_supported (STB_LOCAL)
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
