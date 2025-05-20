# Function: <code>devlink_reload_action_is_supported</code>

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
In net/core/devlink.c (ffffffff81a6745f)
Location: net/core/devlink.c:509
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
In net/core/devlink.c (ffffffff81a4a936)
Location: net/core/devlink.c:512
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
In net/core/devlink.c (ffffffff81b029cd)
Location: net/core/devlink.c:609
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
In net/core/devlink.c (ffffffff81c86388)
Location: net/core/devlink.c:826
Inline: True
Inline callers:
  - net/core/devlink.c:devlink_nl_cmd_reload
  - net/core/devlink.c:devlink_reload_stats_put
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
bool devlink_reload_action_is_supported(struct devlink *devlink, enum devlink_reload_action action);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/devlink.c (ffffffff81e2a9a0)
Location: net/core/devlink.c:1002
Inline: False
Direct callers:
  - net/core/devlink.c:devlink_nl_cmd_reload
  - net/core/devlink.c:devlink_reload_stats_put
  - net/core/devlink.c:devlink_reload_stats_put
```
**Symbols:**

```
ffffffff81e2a9a0-ffffffff81e2a9c4: devlink_reload_action_is_supported (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
bool devlink_reload_action_is_supported(struct devlink *devlink, enum devlink_reload_action action);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/devlink/dev.c (ffffffff82042ad0)
Location: net/devlink/dev.c:46
Inline: False
Direct callers:
  - net/devlink/dev.c:devlink_nl_cmd_reload
  - net/devlink/dev.c:devlink_reload_stats_put
  - net/devlink/dev.c:devlink_reload_stats_put
```
**Symbols:**

```
ffffffff82042ad0-ffffffff82042af4: devlink_reload_action_is_supported (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
bool devlink_reload_action_is_supported(struct devlink *devlink, enum devlink_reload_action action);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/devlink/dev.c (ffffffff82101e10)
Location: net/devlink/dev.c:47
Inline: False
Direct callers:
  - net/devlink/dev.c:devlink_nl_reload_doit
  - net/devlink/dev.c:devlink_reload_stats_put
  - net/devlink/dev.c:devlink_reload_stats_put
```
**Symbols:**

```
ffffffff82101e10-ffffffff82101e34: devlink_reload_action_is_supported (STB_LOCAL)
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
