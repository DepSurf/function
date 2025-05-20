# Function: <code>devlink_fmsg_prepare_skb</code>

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
<summary>In <code>5.3</code>: ✅</summary>

```c
int devlink_fmsg_prepare_skb(struct devlink_fmsg *fmsg, struct sk_buff *skb, int *start);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/devlink.c (ffffffff8194ec20)
Location: net/core/devlink.c:4437
Inline: False
Direct callers:
  - net/core/devlink.c:devlink_nl_cmd_health_reporter_dump_get_dumpit
  - net/core/devlink.c:devlink_nl_cmd_health_reporter_diagnose_doit
```
**Symbols:**

```
ffffffff8194ec20-ffffffff8194ee82: devlink_fmsg_prepare_skb (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int devlink_fmsg_prepare_skb(struct devlink_fmsg *fmsg, struct sk_buff *skb, int *start);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/devlink.c (ffffffff81985990)
Location: net/core/devlink.c:4491
Inline: False
Direct callers:
  - net/core/devlink.c:devlink_nl_cmd_health_reporter_dump_get_dumpit
  - net/core/devlink.c:devlink_nl_cmd_health_reporter_diagnose_doit
```
**Symbols:**

```
ffffffff81985990-ffffffff81985bf2: devlink_fmsg_prepare_skb (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int devlink_fmsg_prepare_skb(struct devlink_fmsg *fmsg, struct sk_buff *skb, int *start);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/devlink.c (ffffffff81a56e00)
Location: net/core/devlink.c:5007
Inline: False
```
**Symbols:**

```
ffffffff81a56e00-ffffffff81a57043: devlink_fmsg_prepare_skb (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int devlink_fmsg_prepare_skb(struct devlink_fmsg *fmsg, struct sk_buff *skb, int *start);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/devlink.c (ffffffff81a5e590)
Location: net/core/devlink.c:5696
Inline: False
```
**Symbols:**

```
ffffffff81a5e590-ffffffff81a5e7d3: devlink_fmsg_prepare_skb (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int devlink_fmsg_prepare_skb(struct devlink_fmsg *fmsg, struct sk_buff *skb, int *start);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/devlink.c (ffffffff81a49460)
Location: net/core/devlink.c:5899
Inline: False
Direct callers:
  - net/core/devlink.c:devlink_nl_cmd_health_reporter_dump_get_dumpit
  - net/core/devlink.c:devlink_nl_cmd_health_reporter_diagnose_doit
```
**Symbols:**

```
ffffffff81a49460-ffffffff81a4969e: devlink_fmsg_prepare_skb (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int devlink_fmsg_prepare_skb(struct devlink_fmsg *fmsg, struct sk_buff *skb, int *start);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/core/devlink.c (0)
Location: net/core/devlink.c:6512
Inline: False
Direct callers:
  - net/core/devlink.c:devlink_nl_cmd_health_reporter_dump_get_dumpit
  - net/core/devlink.c:devlink_nl_cmd_health_reporter_diagnose_doit
```
**Symbols:**

```
ffffffff81af8290-ffffffff81af84df: devlink_fmsg_prepare_skb (STB_LOCAL)
ffffffff81d3873a-ffffffff81d38755: devlink_fmsg_prepare_skb.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int devlink_fmsg_prepare_skb(struct devlink_fmsg *fmsg, struct sk_buff *skb, int *start);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/core/devlink.c (0)
Location: net/core/devlink.c:7004
Inline: False
Direct callers:
  - net/core/devlink.c:devlink_nl_cmd_health_reporter_dump_get_dumpit
  - net/core/devlink.c:devlink_nl_cmd_health_reporter_diagnose_doit
```
**Symbols:**

```
ffffffff81c83f80-ffffffff81c841f4: devlink_fmsg_prepare_skb (STB_LOCAL)
ffffffff81f0529f-ffffffff81f052ba: devlink_fmsg_prepare_skb.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
int devlink_fmsg_prepare_skb(struct devlink_fmsg *fmsg, struct sk_buff *skb, int *start);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/core/devlink.c (0)
Location: net/core/devlink.c:7559
Inline: False
Direct callers:
  - net/core/devlink.c:devlink_nl_cmd_health_reporter_dump_get_dumpit
  - net/core/devlink.c:devlink_nl_cmd_health_reporter_diagnose_doit
```
**Symbols:**

```
ffffffff81e3c500-ffffffff81e3c774: devlink_fmsg_prepare_skb (STB_LOCAL)
ffffffff820ad250-ffffffff820ad26b: devlink_fmsg_prepare_skb.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
int devlink_fmsg_prepare_skb(struct devlink_fmsg *fmsg, struct sk_buff *skb, int *start);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/devlink/health.c (0)
Location: net/devlink/health.c:1076
Inline: False
Direct callers:
  - net/devlink/health.c:devlink_nl_cmd_health_reporter_dump_get_dumpit
```
**Symbols:**

```
ffffffff82047080-ffffffff820472df: devlink_fmsg_prepare_skb (STB_LOCAL)
ffffffff82136904-ffffffff8213691f: devlink_fmsg_prepare_skb.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
int devlink_fmsg_prepare_skb(struct devlink_fmsg *fmsg, struct sk_buff *skb, int *start);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/devlink/health.c (0)
Location: net/devlink/health.c:978
Inline: False
Direct callers:
  - net/devlink/health.c:devlink_nl_health_reporter_dump_get_dumpit
```
**Symbols:**

```
ffffffff82112fb0-ffffffff8211320f: devlink_fmsg_prepare_skb (STB_LOCAL)
ffffffff8221864e-ffffffff82218669: devlink_fmsg_prepare_skb.cold (STB_LOCAL)
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
int devlink_fmsg_prepare_skb(struct devlink_fmsg *fmsg, struct sk_buff *skb, int *start);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/devlink.c (ffff800010c2df78)
Location: net/core/devlink.c:4491
Inline: False
Direct callers:
  - net/core/devlink.c:devlink_nl_cmd_health_reporter_dump_get_dumpit
  - net/core/devlink.c:devlink_nl_cmd_health_reporter_diagnose_doit
```
**Symbols:**

```
ffff800010c2df78-ffff800010c2e214: devlink_fmsg_prepare_skb (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int devlink_fmsg_prepare_skb(struct devlink_fmsg *fmsg, struct sk_buff *skb, int *start);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/devlink.c (c0d44fb8)
Location: net/core/devlink.c:4491
Inline: False
Direct callers:
  - net/core/devlink.c:devlink_nl_cmd_health_reporter_dump_get_dumpit
  - net/core/devlink.c:devlink_nl_cmd_health_reporter_diagnose_doit
```
**Symbols:**

```
c0d44fb8-c0d45234: devlink_fmsg_prepare_skb (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int devlink_fmsg_prepare_skb(struct devlink_fmsg *fmsg, struct sk_buff *skb, int *start);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/devlink.c (c000000000d24220)
Location: net/core/devlink.c:4491
Inline: False
Direct callers:
  - net/core/devlink.c:devlink_nl_cmd_health_reporter_dump_get_dumpit
  - net/core/devlink.c:devlink_nl_cmd_health_reporter_diagnose_doit
```
**Symbols:**

```
c000000000d24220-c000000000d2457c: devlink_fmsg_prepare_skb (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int devlink_fmsg_prepare_skb(struct devlink_fmsg *fmsg, struct sk_buff *skb, int *start);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/devlink.c (ffffffe00079fcd2)
Location: net/core/devlink.c:4491
Inline: False
Direct callers:
  - net/core/devlink.c:devlink_nl_cmd_health_reporter_dump_get_dumpit
  - net/core/devlink.c:devlink_nl_cmd_health_reporter_diagnose_doit
```
**Symbols:**

```
ffffffe00079fcd2-ffffffe00079fed4: devlink_fmsg_prepare_skb (STB_LOCAL)
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
int devlink_fmsg_prepare_skb(struct devlink_fmsg *fmsg, struct sk_buff *skb, int *start);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/devlink.c (ffffffff81925800)
Location: net/core/devlink.c:4491
Inline: False
Direct callers:
  - net/core/devlink.c:devlink_nl_cmd_health_reporter_dump_get_dumpit
  - net/core/devlink.c:devlink_nl_cmd_health_reporter_diagnose_doit
```
**Symbols:**

```
ffffffff81925800-ffffffff81925a62: devlink_fmsg_prepare_skb (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int devlink_fmsg_prepare_skb(struct devlink_fmsg *fmsg, struct sk_buff *skb, int *start);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/devlink.c (ffffffff818df5b0)
Location: net/core/devlink.c:4491
Inline: False
Direct callers:
  - net/core/devlink.c:devlink_nl_cmd_health_reporter_dump_get_dumpit
  - net/core/devlink.c:devlink_nl_cmd_health_reporter_diagnose_doit
```
**Symbols:**

```
ffffffff818df5b0-ffffffff818df812: devlink_fmsg_prepare_skb (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int devlink_fmsg_prepare_skb(struct devlink_fmsg *fmsg, struct sk_buff *skb, int *start);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/devlink.c (ffffffff81976990)
Location: net/core/devlink.c:4491
Inline: False
Direct callers:
  - net/core/devlink.c:devlink_nl_cmd_health_reporter_dump_get_dumpit
  - net/core/devlink.c:devlink_nl_cmd_health_reporter_diagnose_doit
```
**Symbols:**

```
ffffffff81976990-ffffffff81976bf2: devlink_fmsg_prepare_skb (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int devlink_fmsg_prepare_skb(struct devlink_fmsg *fmsg, struct sk_buff *skb, int *start);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/devlink.c (ffffffff81998e80)
Location: net/core/devlink.c:4491
Inline: False
Direct callers:
  - net/core/devlink.c:devlink_nl_cmd_health_reporter_dump_get_dumpit
  - net/core/devlink.c:devlink_nl_cmd_health_reporter_diagnose_doit
```
**Symbols:**

```
ffffffff81998e80-ffffffff819990e2: devlink_fmsg_prepare_skb (STB_LOCAL)
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
