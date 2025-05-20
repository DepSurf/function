# Function: <code>devlink_fmsg_nest_end</code>

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
<summary>In <code>5.3</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/core/devlink.c (ffffffff8194ef54)
Location: net/core/devlink.c:4117
Inline: True
Inline callers:
  - net/core/devlink.c:devlink_nl_cmd_health_reporter_diagnose_doit
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/core/devlink.c (ffffffff81985cc4)
Location: net/core/devlink.c:4171
Inline: True
Inline callers:
  - net/core/devlink.c:devlink_nl_cmd_health_reporter_diagnose_doit
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/core/devlink.c (ffffffff81a5c075)
Location: net/core/devlink.c:4612
Inline: True
Inline callers:
  - net/core/devlink.c:devlink_nl_cmd_health_reporter_diagnose_doit
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/core/devlink.c (ffffffff81a5ed2a)
Location: net/core/devlink.c:5301
Inline: True
Inline callers:
  - net/core/devlink.c:devlink_nl_cmd_health_reporter_diagnose_doit
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
int devlink_fmsg_nest_end(struct devlink_fmsg *fmsg);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/devlink.c (ffffffff81a3ca00)
Location: net/core/devlink.c:5504
Inline: True
Direct callers:
  - net/core/devlink.c:devlink_nl_cmd_health_reporter_diagnose_doit
```
**Symbols:**

```
ffffffff81a3ca00-ffffffff81a3ca5c: devlink_fmsg_nest_end (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline, Transformation ⚠️</summary>

```c
int devlink_fmsg_nest_end(struct devlink_fmsg *fmsg);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/core/devlink.c (ffffffff81d384d7)
Location: net/core/devlink.c:6117
Inline: True
Inline callers:
  - net/core/devlink.c:devlink_fmsg_obj_nest_end
```
**Symbols:**

```
ffffffff81af36d0-ffffffff81af373d: devlink_fmsg_nest_end (STB_LOCAL)
ffffffff81d38426-ffffffff81d3843b: devlink_fmsg_nest_end.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline, Transformation ⚠️</summary>

```c
int devlink_fmsg_nest_end(struct devlink_fmsg *fmsg);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/core/devlink.c (ffffffff81f04e77)
Location: net/core/devlink.c:6612
Inline: True
Inline callers:
  - net/core/devlink.c:devlink_fmsg_pair_nest_end
  - net/core/devlink.c:devlink_fmsg_obj_nest_end
```
**Symbols:**

```
ffffffff81c77550-ffffffff81c775c7: devlink_fmsg_nest_end (STB_LOCAL)
ffffffff81f04df8-ffffffff81f04e0d: devlink_fmsg_nest_end.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline, Transformation ⚠️</summary>

```c
int devlink_fmsg_nest_end(struct devlink_fmsg *fmsg);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/core/devlink.c (ffffffff820ace60)
Location: net/core/devlink.c:7167
Inline: True
Inline callers:
  - net/core/devlink.c:devlink_fmsg_pair_nest_end
  - net/core/devlink.c:devlink_fmsg_obj_nest_end
```
**Symbols:**

```
ffffffff81e30060-ffffffff81e300d7: devlink_fmsg_nest_end (STB_LOCAL)
ffffffff820acde1-ffffffff820acdf6: devlink_fmsg_nest_end.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline, Transformation ⚠️</summary>

```c
int devlink_fmsg_nest_end(struct devlink_fmsg *fmsg);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/devlink/health.c (ffffffff821367e1)
Location: net/devlink/health.c:684
Inline: True
Inline callers:
  - net/devlink/health.c:devlink_fmsg_pair_nest_end
  - net/devlink/health.c:devlink_fmsg_obj_nest_end
```
**Symbols:**

```
ffffffff82045ec0-ffffffff82045f37: devlink_fmsg_nest_end (STB_LOCAL)
ffffffff821366f9-ffffffff8213670e: devlink_fmsg_nest_end.cold (STB_LOCAL)
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
In net/devlink/health.c (ffffffff82114320)
Location: net/devlink/health.c:707
Inline: True
Inline callers:
  - net/devlink/health.c:devlink_nl_health_reporter_diagnose_doit
  - net/devlink/health.c:devlink_nl_health_reporter_diagnose_doit
  - net/devlink/health.c:devlink_fmsg_binary_pair_put
  - net/devlink/health.c:devlink_fmsg_binary_pair_put
  - net/devlink/health.c:devlink_fmsg_binary_pair_put
  - net/devlink/health.c:devlink_fmsg_binary_pair_put
  - net/devlink/health.c:devlink_fmsg_string_pair_put
  - net/devlink/health.c:devlink_fmsg_string_pair_put
  - net/devlink/health.c:devlink_fmsg_u64_pair_put
  - net/devlink/health.c:devlink_fmsg_u64_pair_put
  - net/devlink/health.c:devlink_fmsg_u32_pair_put
  - net/devlink/health.c:devlink_fmsg_u32_pair_put
  - net/devlink/health.c:devlink_fmsg_u8_pair_put
  - net/devlink/health.c:devlink_fmsg_u8_pair_put
  - net/devlink/health.c:devlink_fmsg_bool_pair_put
  - net/devlink/health.c:devlink_fmsg_bool_pair_put
  - net/devlink/health.c:devlink_health_do_dump
  - net/devlink/health.c:devlink_health_do_dump
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/core/devlink.c (ffff800010c2e5b0)
Location: net/core/devlink.c:4171
Inline: True
Inline callers:
  - net/core/devlink.c:devlink_nl_cmd_health_reporter_diagnose_doit
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/core/devlink.c (c0d452f8)
Location: net/core/devlink.c:4171
Inline: True
Inline callers:
  - net/core/devlink.c:devlink_nl_cmd_health_reporter_diagnose_doit
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int devlink_fmsg_nest_end(struct devlink_fmsg *fmsg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/devlink.c (c000000000d1a5b0)
Location: net/core/devlink.c:4171
Inline: False
Direct callers:
  - net/core/devlink.c:devlink_nl_cmd_health_reporter_diagnose_doit
```
**Symbols:**

```
c000000000d1a5b0-c000000000d1a634: devlink_fmsg_nest_end (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/core/devlink.c (ffffffe00079ff7a)
Location: net/core/devlink.c:4171
Inline: True
Inline callers:
  - net/core/devlink.c:devlink_nl_cmd_health_reporter_diagnose_doit
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/core/devlink.c (ffffffff81925b34)
Location: net/core/devlink.c:4171
Inline: True
Inline callers:
  - net/core/devlink.c:devlink_nl_cmd_health_reporter_diagnose_doit
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/core/devlink.c (ffffffff818df8e4)
Location: net/core/devlink.c:4171
Inline: True
Inline callers:
  - net/core/devlink.c:devlink_nl_cmd_health_reporter_diagnose_doit
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/core/devlink.c (ffffffff81976cc4)
Location: net/core/devlink.c:4171
Inline: True
Inline callers:
  - net/core/devlink.c:devlink_nl_cmd_health_reporter_diagnose_doit
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/core/devlink.c (ffffffff819991b4)
Location: net/core/devlink.c:4171
Inline: True
Inline callers:
  - net/core/devlink.c:devlink_nl_cmd_health_reporter_diagnose_doit
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
</ul>
<b>Arch</b>
<ul>
</ul>
