# Function: <code>devlink_notify</code>

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
void devlink_notify(struct devlink *devlink, enum devlink_command cmd);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/core/devlink.c (0)
Location: net/core/devlink.c:488
Inline: False
Direct callers:
  - net/core/devlink.c:devlink_unregister
  - net/core/devlink.c:devlink_register
```
**Symbols:**

```
ffffffff8194f570-ffffffff8194f615: devlink_notify (STB_LOCAL)
ffffffff819524e3-ffffffff819524f6: devlink_notify.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void devlink_notify(struct devlink *devlink, enum devlink_command cmd);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/devlink.c (ffffffff81982190)
Location: net/core/devlink.c:485
Inline: False
Direct callers:
  - net/core/devlink.c:devlink_unregister
  - net/core/devlink.c:devlink_register
  - net/core/devlink.c:devlink_nl_cmd_reload
```
**Symbols:**

```
ffffffff81982190-ffffffff8198223c: devlink_notify (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void devlink_notify(struct devlink *devlink, enum devlink_command cmd);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/devlink.c (ffffffff81a598a0)
Location: net/core/devlink.c:501
Inline: False
Direct callers:
  - net/core/devlink.c:devlink_unregister
  - net/core/devlink.c:devlink_register
```
**Symbols:**

```
ffffffff81a598a0-ffffffff81a59939: devlink_notify (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void devlink_notify(struct devlink *devlink, enum devlink_command cmd);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/devlink.c (ffffffff81a67040)
Location: net/core/devlink.c:639
Inline: False
Direct callers:
  - net/core/devlink.c:devlink_unregister
  - net/core/devlink.c:devlink_register
  - net/core/devlink.c:devlink_reload
  - net/core/devlink.c:devlink_reload
  - net/core/devlink.c:devlink_reload
  - net/core/devlink.c:__devlink_reload_stats_update
```
**Symbols:**

```
ffffffff81a67040-ffffffff81a670d8: devlink_notify (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void devlink_notify(struct devlink *devlink, enum devlink_command cmd);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/devlink.c (ffffffff81a4a260)
Location: net/core/devlink.c:642
Inline: False
Direct callers:
  - net/core/devlink.c:devlink_unregister
  - net/core/devlink.c:devlink_register
  - net/core/devlink.c:devlink_reload
  - net/core/devlink.c:devlink_reload
  - net/core/devlink.c:devlink_reload
  - net/core/devlink.c:__devlink_reload_stats_update
```
**Symbols:**

```
ffffffff81a4a260-ffffffff81a4a2f8: devlink_notify (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void devlink_notify(struct devlink *devlink, enum devlink_command cmd);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/devlink.c (ffffffff81b022c0)
Location: net/core/devlink.c:739
Inline: False
Direct callers:
  - net/core/devlink.c:devlink_unregister
  - net/core/devlink.c:devlink_register
  - net/core/devlink.c:devlink_reload
  - net/core/devlink.c:devlink_reload
  - net/core/devlink.c:devlink_reload
  - net/core/devlink.c:__devlink_reload_stats_update
```
**Symbols:**

```
ffffffff81b022c0-ffffffff81b02358: devlink_notify (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void devlink_notify(struct devlink *devlink, enum devlink_command cmd);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/devlink.c (ffffffff81c85cc0)
Location: net/core/devlink.c:956
Inline: False
Direct callers:
  - net/core/devlink.c:devlink_unregister
  - net/core/devlink.c:devlink_register
  - net/core/devlink.c:devlink_reload
  - net/core/devlink.c:devlink_reload
  - net/core/devlink.c:devlink_reload
  - net/core/devlink.c:__devlink_reload_stats_update
```
**Symbols:**

```
ffffffff81c85cc0-ffffffff81c85da6: devlink_notify (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void devlink_notify(struct devlink *devlink, enum devlink_command cmd);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/devlink.c (ffffffff81e3ffd0)
Location: net/core/devlink.c:1132
Inline: False
Direct callers:
  - net/core/devlink.c:devlink_notify_unregister
  - net/core/devlink.c:devlink_notify_register
  - net/core/devlink.c:devlink_reload
  - net/core/devlink.c:devlink_reload
  - net/core/devlink.c:devlink_reload
  - net/core/devlink.c:__devlink_reload_stats_update
```
**Symbols:**

```
ffffffff81e3ffd0-ffffffff81e400b6: devlink_notify (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void devlink_notify(struct devlink *devlink, enum devlink_command cmd);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/devlink/dev.c (ffffffff82044390)
Location: net/devlink/dev.c:177
Inline: False
Direct callers:
  - net/devlink/leftover.c:devlink_notify_unregister
  - net/devlink/leftover.c:devlink_notify_register
  - net/devlink/dev.c:devlink_reload
  - net/devlink/dev.c:__devlink_reload_stats_update
```
**Symbols:**

```
ffffffff82044390-ffffffff8204448b: devlink_notify (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline, Transformation ⚠️</summary>

```c
void devlink_notify(struct devlink *devlink, enum devlink_command cmd);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/devlink/dev.c (ffffffff82103170)
Location: net/devlink/dev.c:199
Inline: True
Direct callers:
  - net/devlink/dev.c:devlink_reload
  - net/devlink/dev.c:__devlink_reload_stats_update
  - net/devlink/dev.c:devlink_notify_unregister
  - net/devlink/dev.c:devlink_notify_register
  - net/devlink/dev.c:devlink_rel_notify_cb
```
**Symbols:**

```
ffffffff82103170-ffffffff821032bd: devlink_notify.part.0 (STB_LOCAL)
ffffffff821032d0-ffffffff82103358: devlink_notify (STB_LOCAL)
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
void devlink_notify(struct devlink *devlink, enum devlink_command cmd);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/devlink.c (ffff800010c2a200)
Location: net/core/devlink.c:485
Inline: False
Direct callers:
  - net/core/devlink.c:devlink_unregister
  - net/core/devlink.c:devlink_register
  - net/core/devlink.c:devlink_nl_cmd_reload
```
**Symbols:**

```
ffff800010c2a200-ffff800010c2a2b8: devlink_notify (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void devlink_notify(struct devlink *devlink, enum devlink_command cmd);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/devlink.c (c0d40e14)
Location: net/core/devlink.c:485
Inline: False
Direct callers:
  - net/core/devlink.c:devlink_unregister
  - net/core/devlink.c:devlink_register
  - net/core/devlink.c:devlink_nl_cmd_reload
```
**Symbols:**

```
c0d40e14-c0d40ef0: devlink_notify (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void devlink_notify(struct devlink *devlink, enum devlink_command cmd);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/devlink.c (c000000000d20f10)
Location: net/core/devlink.c:485
Inline: False
Direct callers:
  - net/core/devlink.c:devlink_unregister
  - net/core/devlink.c:devlink_register
  - net/core/devlink.c:devlink_nl_cmd_reload
```
**Symbols:**

```
c000000000d20f10-c000000000d21028: devlink_notify (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void devlink_notify(struct devlink *devlink, enum devlink_command cmd);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/devlink.c (ffffffe0007a274a)
Location: net/core/devlink.c:485
Inline: False
Direct callers:
  - net/core/devlink.c:devlink_unregister
  - net/core/devlink.c:devlink_register
  - net/core/devlink.c:devlink_nl_cmd_reload
```
**Symbols:**

```
ffffffe0007a274a-ffffffe0007a27ec: devlink_notify (STB_LOCAL)
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
void devlink_notify(struct devlink *devlink, enum devlink_command cmd);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/devlink.c (ffffffff81922000)
Location: net/core/devlink.c:485
Inline: False
Direct callers:
  - net/core/devlink.c:devlink_unregister
  - net/core/devlink.c:devlink_register
  - net/core/devlink.c:devlink_nl_cmd_reload
```
**Symbols:**

```
ffffffff81922000-ffffffff819220ac: devlink_notify (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void devlink_notify(struct devlink *devlink, enum devlink_command cmd);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/devlink.c (ffffffff818dbdb0)
Location: net/core/devlink.c:485
Inline: False
Direct callers:
  - net/core/devlink.c:devlink_unregister
  - net/core/devlink.c:devlink_register
  - net/core/devlink.c:devlink_nl_cmd_reload
```
**Symbols:**

```
ffffffff818dbdb0-ffffffff818dbe5c: devlink_notify (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void devlink_notify(struct devlink *devlink, enum devlink_command cmd);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/devlink.c (ffffffff81973190)
Location: net/core/devlink.c:485
Inline: False
Direct callers:
  - net/core/devlink.c:devlink_unregister
  - net/core/devlink.c:devlink_register
  - net/core/devlink.c:devlink_nl_cmd_reload
```
**Symbols:**

```
ffffffff81973190-ffffffff8197323c: devlink_notify (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void devlink_notify(struct devlink *devlink, enum devlink_command cmd);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/devlink.c (ffffffff81995680)
Location: net/core/devlink.c:485
Inline: False
Direct callers:
  - net/core/devlink.c:devlink_unregister
  - net/core/devlink.c:devlink_register
  - net/core/devlink.c:devlink_nl_cmd_reload
```
**Symbols:**

```
ffffffff81995680-ffffffff8199572c: devlink_notify (STB_LOCAL)
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
