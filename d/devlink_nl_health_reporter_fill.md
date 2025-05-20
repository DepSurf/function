# Function: <code>devlink_nl_health_reporter_fill</code>

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
<summary>In <code>5.3</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/core/devlink.c (0)
Location: net/core/devlink.c:4868
Inline: True
Direct callers:
  - net/core/devlink.c:devlink_nl_cmd_health_reporter_get_dumpit
  - net/core/devlink.c:devlink_nl_cmd_health_reporter_get_doit
```
**Symbols:**

```
ffffffff8194aed0-ffffffff8194b150: devlink_nl_health_reporter_fill.constprop.0 (STB_LOCAL)
ffffffff819521ec-ffffffff8195220f: devlink_nl_health_reporter_fill.constprop.0.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/core/devlink.c (ffffffff8197fbd0)
Location: net/core/devlink.c:4924
Inline: True
Direct callers:
  - net/core/devlink.c:devlink_nl_cmd_health_reporter_get_dumpit
  - net/core/devlink.c:devlink_nl_cmd_health_reporter_get_doit
```
**Symbols:**

```
ffffffff8197fbd0-ffffffff8197fe83: devlink_nl_health_reporter_fill.constprop.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int devlink_nl_health_reporter_fill(struct sk_buff *msg, struct devlink *devlink, struct devlink_health_reporter *reporter, enum devlink_command cmd, u32 portid, u32 seq, int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/devlink.c (ffffffff81a58d70)
Location: net/core/devlink.c:5246
Inline: False
Direct callers:
  - net/core/devlink.c:devlink_nl_cmd_health_reporter_get_dumpit
  - net/core/devlink.c:devlink_nl_cmd_health_reporter_get_doit
```
**Symbols:**

```
ffffffff81a58d70-ffffffff81a5904a: devlink_nl_health_reporter_fill (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int devlink_nl_health_reporter_fill(struct sk_buff *msg, struct devlink *devlink, struct devlink_health_reporter *reporter, enum devlink_command cmd, u32 portid, u32 seq, int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/devlink.c (ffffffff81a613f0)
Location: net/core/devlink.c:6037
Inline: False
Direct callers:
  - net/core/devlink.c:devlink_nl_cmd_health_reporter_get_dumpit
  - net/core/devlink.c:devlink_nl_cmd_health_reporter_get_dumpit
  - net/core/devlink.c:devlink_nl_cmd_health_reporter_get_doit
```
**Symbols:**

```
ffffffff81a613f0-ffffffff81a616fa: devlink_nl_health_reporter_fill (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int devlink_nl_health_reporter_fill(struct sk_buff *msg, struct devlink *devlink, struct devlink_health_reporter *reporter, enum devlink_command cmd, u32 portid, u32 seq, int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/devlink.c (ffffffff81a43bd0)
Location: net/core/devlink.c:6240
Inline: False
Direct callers:
  - net/core/devlink.c:devlink_nl_cmd_health_reporter_get_dumpit
  - net/core/devlink.c:devlink_nl_cmd_health_reporter_get_dumpit
  - net/core/devlink.c:devlink_nl_cmd_health_reporter_get_doit
```
**Symbols:**

```
ffffffff81a43bd0-ffffffff81a43ed9: devlink_nl_health_reporter_fill (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int devlink_nl_health_reporter_fill(struct sk_buff *msg, struct devlink_health_reporter *reporter, enum devlink_command cmd, u32 portid, u32 seq, int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/core/devlink.c (0)
Location: net/core/devlink.c:6853
Inline: False
Direct callers:
  - net/core/devlink.c:devlink_nl_cmd_health_reporter_get_dumpit
  - net/core/devlink.c:devlink_nl_cmd_health_reporter_get_dumpit
  - net/core/devlink.c:devlink_nl_cmd_health_reporter_get_doit
```
**Symbols:**

```
ffffffff81afb1d0-ffffffff81afb4f6: devlink_nl_health_reporter_fill (STB_LOCAL)
ffffffff81d387a6-ffffffff81d387d5: devlink_nl_health_reporter_fill.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int devlink_nl_health_reporter_fill(struct sk_buff *msg, struct devlink_health_reporter *reporter, enum devlink_command cmd, u32 portid, u32 seq, int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/core/devlink.c (0)
Location: net/core/devlink.c:7345
Inline: False
Direct callers:
  - net/core/devlink.c:devlink_nl_cmd_health_reporter_get_dumpit
  - net/core/devlink.c:devlink_nl_cmd_health_reporter_get_dumpit
  - net/core/devlink.c:devlink_nl_cmd_health_reporter_get_doit
```
**Symbols:**

```
ffffffff81c7d4d0-ffffffff81c7d811: devlink_nl_health_reporter_fill (STB_LOCAL)
ffffffff81f050e7-ffffffff81f05117: devlink_nl_health_reporter_fill.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
int devlink_nl_health_reporter_fill(struct sk_buff *msg, struct devlink_health_reporter *reporter, enum devlink_command cmd, u32 portid, u32 seq, int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/core/devlink.c (0)
Location: net/core/devlink.c:7900
Inline: False
Direct callers:
  - net/core/devlink.c:devlink_nl_cmd_health_reporter_get_dumpit
  - net/core/devlink.c:devlink_nl_cmd_health_reporter_get_dumpit
  - net/core/devlink.c:devlink_nl_cmd_health_reporter_get_doit
```
**Symbols:**

```
ffffffff81e35d50-ffffffff81e36091: devlink_nl_health_reporter_fill (STB_LOCAL)
ffffffff820ad0eb-ffffffff820ad11b: devlink_nl_health_reporter_fill.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
int devlink_nl_health_reporter_fill(struct sk_buff *msg, struct devlink_health_reporter *reporter, enum devlink_command cmd, u32 portid, u32 seq, int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/devlink/health.c (0)
Location: net/devlink/health.c:262
Inline: False
Direct callers:
  - net/devlink/health.c:devlink_nl_cmd_health_reporter_get_dump_one
  - net/devlink/health.c:devlink_nl_cmd_health_reporter_get_dump_one
  - net/devlink/health.c:devlink_nl_cmd_health_reporter_get_doit
```
**Symbols:**

```
ffffffff820474f0-ffffffff8204788e: devlink_nl_health_reporter_fill (STB_LOCAL)
ffffffff8213691f-ffffffff8213694f: devlink_nl_health_reporter_fill.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
int devlink_nl_health_reporter_fill(struct sk_buff *msg, struct devlink_health_reporter *reporter, enum devlink_command cmd, u32 portid, u32 seq, int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/devlink/health.c (0)
Location: net/devlink/health.c:260
Inline: False
Direct callers:
  - net/devlink/health.c:devlink_nl_health_reporter_get_dump_one
  - net/devlink/health.c:devlink_nl_health_reporter_get_dump_one
  - net/devlink/health.c:devlink_nl_health_reporter_get_doit
```
**Symbols:**

```
ffffffff82113420-ffffffff821137bb: devlink_nl_health_reporter_fill (STB_LOCAL)
ffffffff82218669-ffffffff82218699: devlink_nl_health_reporter_fill.cold (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/core/devlink.c (ffff800010c282d8)
Location: net/core/devlink.c:4924
Inline: True
Direct callers:
  - net/core/devlink.c:devlink_nl_cmd_health_reporter_get_dumpit
  - net/core/devlink.c:devlink_nl_cmd_health_reporter_get_doit
```
**Symbols:**

```
ffff800010c282d8-ffff800010c28584: devlink_nl_health_reporter_fill.constprop.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/core/devlink.c (c0d3e734)
Location: net/core/devlink.c:4924
Inline: True
Direct callers:
  - net/core/devlink.c:devlink_nl_cmd_health_reporter_get_dumpit
  - net/core/devlink.c:devlink_nl_cmd_health_reporter_get_doit
```
**Symbols:**

```
c0d3e734-c0d3e9f8: devlink_nl_health_reporter_fill.constprop.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/core/devlink.c (c000000000d1d860)
Location: net/core/devlink.c:4924
Inline: True
Direct callers:
  - net/core/devlink.c:devlink_nl_cmd_health_reporter_get_dumpit
  - net/core/devlink.c:devlink_nl_cmd_health_reporter_get_doit
```
**Symbols:**

```
c000000000d1d860-c000000000d1dbd0: devlink_nl_health_reporter_fill.constprop.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/core/devlink.c (ffffffe0007a09e8)
Location: net/core/devlink.c:4924
Inline: True
Direct callers:
  - net/core/devlink.c:devlink_nl_cmd_health_reporter_get_dumpit
  - net/core/devlink.c:devlink_nl_cmd_health_reporter_get_doit
```
**Symbols:**

```
ffffffe0007a09e8-ffffffe0007a0c14: devlink_nl_health_reporter_fill.constprop.0 (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/core/devlink.c (ffffffff8191fa40)
Location: net/core/devlink.c:4924
Inline: True
Direct callers:
  - net/core/devlink.c:devlink_nl_cmd_health_reporter_get_dumpit
  - net/core/devlink.c:devlink_nl_cmd_health_reporter_get_doit
```
**Symbols:**

```
ffffffff8191fa40-ffffffff8191fcf3: devlink_nl_health_reporter_fill.constprop.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/core/devlink.c (ffffffff818d97f0)
Location: net/core/devlink.c:4924
Inline: True
Direct callers:
  - net/core/devlink.c:devlink_nl_cmd_health_reporter_get_dumpit
  - net/core/devlink.c:devlink_nl_cmd_health_reporter_get_doit
```
**Symbols:**

```
ffffffff818d97f0-ffffffff818d9aa3: devlink_nl_health_reporter_fill.constprop.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/core/devlink.c (ffffffff81970bd0)
Location: net/core/devlink.c:4924
Inline: True
Direct callers:
  - net/core/devlink.c:devlink_nl_cmd_health_reporter_get_dumpit
  - net/core/devlink.c:devlink_nl_cmd_health_reporter_get_doit
```
**Symbols:**

```
ffffffff81970bd0-ffffffff81970e83: devlink_nl_health_reporter_fill.constprop.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/core/devlink.c (ffffffff819930c0)
Location: net/core/devlink.c:4924
Inline: True
Direct callers:
  - net/core/devlink.c:devlink_nl_cmd_health_reporter_get_dumpit
  - net/core/devlink.c:devlink_nl_cmd_health_reporter_get_doit
```
**Symbols:**

```
ffffffff819930c0-ffffffff81993373: devlink_nl_health_reporter_fill.constprop.0 (STB_LOCAL)
```
</details>
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
<details>
<summary>Changed between <code>5.13</code> and <code>5.15</code> ⚠️</summary>
<ul>
<li>
<b>Param removed. </b>
<code>struct devlink *devlink</code>
</li>
<li>
<b>Param reordered. </b>
<code>msg, devlink, reporter, cmd, portid, seq, flags</code> ➡️ <code>msg, reporter, cmd, portid, seq, flags</code>
</li>
</ul>
</details>
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
