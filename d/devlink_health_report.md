# Function: <code>devlink_health_report</code>

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
int devlink_health_report(struct devlink_health_reporter *reporter, const char *msg, void *priv_ctx);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/core/devlink.c (0)
Location: net/core/devlink.c:4760
Inline: False
```
**Symbols:**

```
ffffffff81952118-ffffffff8195212b: devlink_health_report.cold (STB_LOCAL)
ffffffff81948350-ffffffff81948510: devlink_health_report (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int devlink_health_report(struct devlink_health_reporter *reporter, const char *msg, void *priv_ctx);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/devlink.c (ffffffff8197d7f0)
Location: net/core/devlink.c:4816
Inline: False
```
**Symbols:**

```
ffffffff8197d7f0-ffffffff8197d9bd: devlink_health_report (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int devlink_health_report(struct devlink_health_reporter *reporter, const char *msg, void *priv_ctx);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/devlink.c (ffffffff81a594c0)
Location: net/core/devlink.c:5417
Inline: False
```
**Symbols:**

```
ffffffff81a594c0-ffffffff81a596ca: devlink_health_report (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int devlink_health_report(struct devlink_health_reporter *reporter, const char *msg, void *priv_ctx);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/devlink.c (ffffffff81a61c80)
Location: net/core/devlink.c:6212
Inline: False
```
**Symbols:**

```
ffffffff81a61c80-ffffffff81a61e57: devlink_health_report (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int devlink_health_report(struct devlink_health_reporter *reporter, const char *msg, void *priv_ctx);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/devlink.c (ffffffff81a44460)
Location: net/core/devlink.c:6415
Inline: False
```
**Symbols:**

```
ffffffff81a44460-ffffffff81a44637: devlink_health_report (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int devlink_health_report(struct devlink_health_reporter *reporter, const char *msg, void *priv_ctx);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/core/devlink.c (0)
Location: net/core/devlink.c:7027
Inline: False
```
**Symbols:**

```
ffffffff81d387d5-ffffffff81d38820: devlink_health_report.cold (STB_LOCAL)
ffffffff81afbb20-ffffffff81afbd0c: devlink_health_report (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int devlink_health_report(struct devlink_health_reporter *reporter, const char *msg, void *priv_ctx);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/core/devlink.c (0)
Location: net/core/devlink.c:7520
Inline: False
```
**Symbols:**

```
ffffffff81f05117-ffffffff81f05164: devlink_health_report.cold (STB_LOCAL)
ffffffff81c7db90-ffffffff81c7dda6: devlink_health_report (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
int devlink_health_report(struct devlink_health_reporter *reporter, const char *msg, void *priv_ctx);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/core/devlink.c (0)
Location: net/core/devlink.c:8075
Inline: False
```
**Symbols:**

```
ffffffff820ad11b-ffffffff820ad168: devlink_health_report.cold (STB_LOCAL)
ffffffff81e36470-ffffffff81e3667f: devlink_health_report (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
int devlink_health_report(struct devlink_health_reporter *reporter, const char *msg, void *priv_ctx);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/devlink/health.c (0)
Location: net/devlink/health.c:580
Inline: False
```
**Symbols:**

```
ffffffff8213694f-ffffffff8213699c: devlink_health_report.cold (STB_LOCAL)
ffffffff82047c90-ffffffff82047e98: devlink_health_report (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
int devlink_health_report(struct devlink_health_reporter *reporter, const char *msg, void *priv_ctx);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/devlink/health.c (0)
Location: net/devlink/health.c:597
Inline: False
```
**Symbols:**

```
ffffffff82218699-ffffffff822186e6: devlink_health_report.cold (STB_LOCAL)
ffffffff82113cf0-ffffffff82113eeb: devlink_health_report (STB_GLOBAL)
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
int devlink_health_report(struct devlink_health_reporter *reporter, const char *msg, void *priv_ctx);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/devlink.c (ffff800010c26f10)
Location: net/core/devlink.c:4816
Inline: False
```
**Symbols:**

```
ffff800010c26f10-ffff800010c27140: devlink_health_report (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int devlink_health_report(struct devlink_health_reporter *reporter, const char *msg, void *priv_ctx);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/devlink.c (c0d3c4a8)
Location: net/core/devlink.c:4816
Inline: False
```
**Symbols:**

```
c0d3c4a8-c0d3c718: devlink_health_report (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int devlink_health_report(struct devlink_health_reporter *reporter, const char *msg, void *priv_ctx);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/devlink.c (c000000000d1ab80)
Location: net/core/devlink.c:4816
Inline: False
```
**Symbols:**

```
c000000000d1ab80-c000000000d1ae2c: devlink_health_report (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int devlink_health_report(struct devlink_health_reporter *reporter, const char *msg, void *priv_ctx);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/devlink.c (ffffffe00079d804)
Location: net/core/devlink.c:4816
Inline: False
```
**Symbols:**

```
ffffffe00079d804-ffffffe00079d9cc: devlink_health_report (STB_GLOBAL)
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
int devlink_health_report(struct devlink_health_reporter *reporter, const char *msg, void *priv_ctx);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/devlink.c (ffffffff8191d660)
Location: net/core/devlink.c:4816
Inline: False
```
**Symbols:**

```
ffffffff8191d660-ffffffff8191d82d: devlink_health_report (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int devlink_health_report(struct devlink_health_reporter *reporter, const char *msg, void *priv_ctx);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/devlink.c (ffffffff818d7410)
Location: net/core/devlink.c:4816
Inline: False
```
**Symbols:**

```
ffffffff818d7410-ffffffff818d75dd: devlink_health_report (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int devlink_health_report(struct devlink_health_reporter *reporter, const char *msg, void *priv_ctx);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/devlink.c (ffffffff8196e7f0)
Location: net/core/devlink.c:4816
Inline: False
```
**Symbols:**

```
ffffffff8196e7f0-ffffffff8196e9bd: devlink_health_report (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int devlink_health_report(struct devlink_health_reporter *reporter, const char *msg, void *priv_ctx);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/devlink.c (ffffffff81990ca0)
Location: net/core/devlink.c:4816
Inline: False
```
**Symbols:**

```
ffffffff81990ca0-ffffffff81990ea9: devlink_health_report (STB_GLOBAL)
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
