# Function: <code>devlink_health_reporter_recover</code>

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
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
int devlink_health_reporter_recover(struct devlink_health_reporter *reporter, void *priv_ctx);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/devlink.c (ffffffff81947f20)
Location: net/core/devlink.c:4693
Inline: True
Direct callers:
  - net/core/devlink.c:devlink_nl_cmd_health_reporter_recover_doit
  - net/core/devlink.c:devlink_health_report
```
**Symbols:**

```
ffffffff81947f20-ffffffff81947f60: devlink_health_reporter_recover (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
int devlink_health_reporter_recover(struct devlink_health_reporter *reporter, void *priv_ctx);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/devlink.c (ffffffff8197d030)
Location: net/core/devlink.c:4748
Inline: True
Direct callers:
  - net/core/devlink.c:devlink_nl_cmd_health_reporter_recover_doit
  - net/core/devlink.c:devlink_health_report
```
**Symbols:**

```
ffffffff8197d030-ffffffff8197d073: devlink_health_reporter_recover (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
int devlink_health_reporter_recover(struct devlink_health_reporter *reporter, void *priv_ctx, struct netlink_ext_ack *extack);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/devlink.c (ffffffff81a593e0)
Location: net/core/devlink.c:5345
Inline: True
Direct callers:
  - net/core/devlink.c:devlink_nl_cmd_health_reporter_recover_doit
  - net/core/devlink.c:devlink_health_report
```
**Symbols:**

```
ffffffff81a593e0-ffffffff81a5944f: devlink_health_reporter_recover (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
int devlink_health_reporter_recover(struct devlink_health_reporter *reporter, void *priv_ctx, struct netlink_ext_ack *extack);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/devlink.c (ffffffff81a61ba0)
Location: net/core/devlink.c:6140
Inline: True
Direct callers:
  - net/core/devlink.c:devlink_nl_cmd_health_reporter_recover_doit
  - net/core/devlink.c:devlink_health_report
```
**Symbols:**

```
ffffffff81a61ba0-ffffffff81a61c12: devlink_health_reporter_recover (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
int devlink_health_reporter_recover(struct devlink_health_reporter *reporter, void *priv_ctx, struct netlink_ext_ack *extack);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/devlink.c (ffffffff81a44380)
Location: net/core/devlink.c:6343
Inline: True
Direct callers:
  - net/core/devlink.c:devlink_nl_cmd_health_reporter_recover_doit
  - net/core/devlink.c:devlink_health_report
```
**Symbols:**

```
ffffffff81a44380-ffffffff81a443f2: devlink_health_reporter_recover (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
int devlink_health_reporter_recover(struct devlink_health_reporter *reporter, void *priv_ctx, struct netlink_ext_ack *extack);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/devlink.c (ffffffff81afba40)
Location: net/core/devlink.c:6955
Inline: True
Direct callers:
  - net/core/devlink.c:devlink_nl_cmd_health_reporter_recover_doit
  - net/core/devlink.c:devlink_health_report
```
**Symbols:**

```
ffffffff81afba40-ffffffff81afbab2: devlink_health_reporter_recover (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int devlink_health_reporter_recover(struct devlink_health_reporter *reporter, void *priv_ctx, struct netlink_ext_ack *extack);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/devlink.c (ffffffff81c7daa0)
Location: net/core/devlink.c:7448
Inline: False
Direct callers:
  - net/core/devlink.c:devlink_nl_cmd_health_reporter_recover_doit
  - net/core/devlink.c:devlink_health_report
```
**Symbols:**

```
ffffffff81c7daa0-ffffffff81c7db21: devlink_health_reporter_recover (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int devlink_health_reporter_recover(struct devlink_health_reporter *reporter, void *priv_ctx, struct netlink_ext_ack *extack);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/devlink.c (ffffffff81e36360)
Location: net/core/devlink.c:8003
Inline: False
Direct callers:
  - net/core/devlink.c:devlink_nl_cmd_health_reporter_recover_doit
  - net/core/devlink.c:devlink_health_report
```
**Symbols:**

```
ffffffff81e36360-ffffffff81e363e1: devlink_health_reporter_recover (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int devlink_health_reporter_recover(struct devlink_health_reporter *reporter, void *priv_ctx, struct netlink_ext_ack *extack);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/devlink/health.c (ffffffff82047c00)
Location: net/devlink/health.c:508
Inline: False
Direct callers:
  - net/devlink/health.c:devlink_nl_cmd_health_reporter_recover_doit
  - net/devlink/health.c:devlink_health_report
```
**Symbols:**

```
ffffffff82047c00-ffffffff82047c7f: devlink_health_reporter_recover (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int devlink_health_reporter_recover(struct devlink_health_reporter *reporter, void *priv_ctx, struct netlink_ext_ack *extack);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/devlink/health.c (ffffffff82113c60)
Location: net/devlink/health.c:528
Inline: False
Direct callers:
  - net/devlink/health.c:devlink_nl_health_reporter_recover_doit
  - net/devlink/health.c:devlink_health_report
```
**Symbols:**

```
ffffffff82113c60-ffffffff82113cd9: devlink_health_reporter_recover (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Selective Inline ⚠️</summary>

```c
int devlink_health_reporter_recover(struct devlink_health_reporter *reporter, void *priv_ctx);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/devlink.c (ffff800010c24c58)
Location: net/core/devlink.c:4748
Inline: True
Direct callers:
  - net/core/devlink.c:devlink_nl_cmd_health_reporter_recover_doit
  - net/core/devlink.c:devlink_health_report
```
**Symbols:**

```
ffff800010c24c58-ffff800010c24cbc: devlink_health_reporter_recover (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
int devlink_health_reporter_recover(struct devlink_health_reporter *reporter, void *priv_ctx);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/devlink.c (c0d3bfdc)
Location: net/core/devlink.c:4748
Inline: True
Direct callers:
  - net/core/devlink.c:devlink_nl_cmd_health_reporter_recover_doit
  - net/core/devlink.c:devlink_health_report
```
**Symbols:**

```
c0d3bfdc-c0d3c04c: devlink_health_reporter_recover (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
int devlink_health_reporter_recover(struct devlink_health_reporter *reporter, void *priv_ctx);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/devlink.c (c000000000d18550)
Location: net/core/devlink.c:4748
Inline: True
Direct callers:
  - net/core/devlink.c:devlink_nl_cmd_health_reporter_recover_doit
  - net/core/devlink.c:devlink_health_report
```
**Symbols:**

```
c000000000d18550-c000000000d185d8: devlink_health_reporter_recover (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
int devlink_health_reporter_recover(struct devlink_health_reporter *reporter, void *priv_ctx);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/devlink.c (ffffffe00079ce00)
Location: net/core/devlink.c:4748
Inline: True
Direct callers:
  - net/core/devlink.c:devlink_nl_cmd_health_reporter_recover_doit
  - net/core/devlink.c:devlink_health_report
```
**Symbols:**

```
ffffffe00079ce00-ffffffe00079ce4e: devlink_health_reporter_recover (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Selective Inline ⚠️</summary>

```c
int devlink_health_reporter_recover(struct devlink_health_reporter *reporter, void *priv_ctx);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/devlink.c (ffffffff8191cea0)
Location: net/core/devlink.c:4748
Inline: True
Direct callers:
  - net/core/devlink.c:devlink_nl_cmd_health_reporter_recover_doit
  - net/core/devlink.c:devlink_health_report
```
**Symbols:**

```
ffffffff8191cea0-ffffffff8191cee3: devlink_health_reporter_recover (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
int devlink_health_reporter_recover(struct devlink_health_reporter *reporter, void *priv_ctx);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/devlink.c (ffffffff818d6c50)
Location: net/core/devlink.c:4748
Inline: True
Direct callers:
  - net/core/devlink.c:devlink_nl_cmd_health_reporter_recover_doit
  - net/core/devlink.c:devlink_health_report
```
**Symbols:**

```
ffffffff818d6c50-ffffffff818d6c93: devlink_health_reporter_recover (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
int devlink_health_reporter_recover(struct devlink_health_reporter *reporter, void *priv_ctx);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/devlink.c (ffffffff8196e030)
Location: net/core/devlink.c:4748
Inline: True
Direct callers:
  - net/core/devlink.c:devlink_nl_cmd_health_reporter_recover_doit
  - net/core/devlink.c:devlink_health_report
```
**Symbols:**

```
ffffffff8196e030-ffffffff8196e073: devlink_health_reporter_recover (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
int devlink_health_reporter_recover(struct devlink_health_reporter *reporter, void *priv_ctx);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/devlink.c (ffffffff819904c0)
Location: net/core/devlink.c:4748
Inline: True
Direct callers:
  - net/core/devlink.c:devlink_nl_cmd_health_reporter_recover_doit
  - net/core/devlink.c:devlink_health_report
```
**Symbols:**

```
ffffffff819904c0-ffffffff81990503: devlink_health_reporter_recover (STB_LOCAL)
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
<details>
<summary>Changed between <code>5.4</code> and <code>5.8</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>struct netlink_ext_ack *extack</code>
</li>
</ul>
</details>
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
