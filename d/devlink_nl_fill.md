# Function: <code>devlink_nl_fill</code>

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
int devlink_nl_fill(struct sk_buff *msg, struct devlink *devlink, enum devlink_command cmd, u32 portid, u32 seq, int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/core/devlink.c (0)
Location: net/core/devlink.c:467
Inline: False
Direct callers:
  - net/core/devlink.c:devlink_nl_cmd_get_dumpit
  - net/core/devlink.c:devlink_nl_cmd_get_doit
  - net/core/devlink.c:devlink_notify
```
**Symbols:**

```
ffffffff8194f360-ffffffff8194f3f6: devlink_nl_fill (STB_LOCAL)
ffffffff819524c8-ffffffff819524e3: devlink_nl_fill.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int devlink_nl_fill(struct sk_buff *msg, struct devlink *devlink, enum devlink_command cmd, u32 portid, u32 seq, int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/devlink.c (ffffffff81981fc0)
Location: net/core/devlink.c:462
Inline: False
Direct callers:
  - net/core/devlink.c:devlink_nl_cmd_get_dumpit
  - net/core/devlink.c:devlink_nl_cmd_get_doit
  - net/core/devlink.c:devlink_notify
```
**Symbols:**

```
ffffffff81981fc0-ffffffff819820b1: devlink_nl_fill (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int devlink_nl_fill(struct sk_buff *msg, struct devlink *devlink, enum devlink_command cmd, u32 portid, u32 seq, int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/devlink.c (ffffffff81a596d0)
Location: net/core/devlink.c:478
Inline: False
Direct callers:
  - net/core/devlink.c:devlink_nl_cmd_get_dumpit
  - net/core/devlink.c:devlink_nl_cmd_get_doit
  - net/core/devlink.c:devlink_notify
```
**Symbols:**

```
ffffffff81a596d0-ffffffff81a597c3: devlink_nl_fill (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int devlink_nl_fill(struct sk_buff *msg, struct devlink *devlink, enum devlink_command cmd, u32 portid, u32 seq, int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/devlink.c (ffffffff81a66de0)
Location: net/core/devlink.c:603
Inline: False
Direct callers:
  - net/core/devlink.c:devlink_nl_cmd_get_dumpit
  - net/core/devlink.c:devlink_nl_cmd_get_doit
  - net/core/devlink.c:devlink_notify
```
**Symbols:**

```
ffffffff81a66de0-ffffffff81a66f6c: devlink_nl_fill (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int devlink_nl_fill(struct sk_buff *msg, struct devlink *devlink, enum devlink_command cmd, u32 portid, u32 seq, int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/devlink.c (ffffffff81a4a000)
Location: net/core/devlink.c:606
Inline: False
Direct callers:
  - net/core/devlink.c:devlink_nl_cmd_get_dumpit
  - net/core/devlink.c:devlink_nl_cmd_get_doit
  - net/core/devlink.c:devlink_notify
```
**Symbols:**

```
ffffffff81a4a000-ffffffff81a4a183: devlink_nl_fill (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int devlink_nl_fill(struct sk_buff *msg, struct devlink *devlink, enum devlink_command cmd, u32 portid, u32 seq, int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/devlink.c (ffffffff81b01fb0)
Location: net/core/devlink.c:703
Inline: False
Direct callers:
  - net/core/devlink.c:devlink_nl_cmd_get_dumpit
  - net/core/devlink.c:devlink_nl_cmd_get_doit
  - net/core/devlink.c:devlink_notify
```
**Symbols:**

```
ffffffff81b01fb0-ffffffff81b02133: devlink_nl_fill (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int devlink_nl_fill(struct sk_buff *msg, struct devlink *devlink, enum devlink_command cmd, u32 portid, u32 seq, int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/devlink.c (ffffffff81c85b30)
Location: net/core/devlink.c:920
Inline: False
Direct callers:
  - net/core/devlink.c:devlink_nl_cmd_get_dumpit
  - net/core/devlink.c:devlink_nl_cmd_get_doit
  - net/core/devlink.c:devlink_notify
```
**Symbols:**

```
ffffffff81c85b30-ffffffff81c85cbc: devlink_nl_fill (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int devlink_nl_fill(struct sk_buff *msg, struct devlink *devlink, enum devlink_command cmd, u32 portid, u32 seq, int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/devlink.c (ffffffff81e3fe30)
Location: net/core/devlink.c:1096
Inline: False
Direct callers:
  - net/core/devlink.c:devlink_nl_cmd_get_dumpit
  - net/core/devlink.c:devlink_nl_cmd_get_doit
  - net/core/devlink.c:devlink_notify
```
**Symbols:**

```
ffffffff81e3fe30-ffffffff81e3ffbc: devlink_nl_fill (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int devlink_nl_fill(struct sk_buff *msg, struct devlink *devlink, enum devlink_command cmd, u32 portid, u32 seq, int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/devlink/dev.c (ffffffff82043810)
Location: net/devlink/dev.c:141
Inline: False
Direct callers:
  - net/devlink/dev.c:devlink_nl_cmd_get_dump_one
  - net/devlink/dev.c:devlink_nl_cmd_get_doit
  - net/devlink/dev.c:devlink_notify
```
**Symbols:**

```
ffffffff82043810-ffffffff820439f9: devlink_nl_fill (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int devlink_nl_fill(struct sk_buff *msg, struct devlink *devlink, enum devlink_command cmd, u32 portid, u32 seq, int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/devlink/dev.c (ffffffff82102ea0)
Location: net/devlink/dev.c:159
Inline: False
Direct callers:
  - net/devlink/dev.c:devlink_nl_get_dump_one
  - net/devlink/dev.c:devlink_nl_get_doit
```
**Symbols:**

```
ffffffff82102ea0-ffffffff82103101: devlink_nl_fill (STB_LOCAL)
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
int devlink_nl_fill(struct sk_buff *msg, struct devlink *devlink, enum devlink_command cmd, u32 portid, u32 seq, int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/devlink.c (ffff800010c2a008)
Location: net/core/devlink.c:462
Inline: False
Direct callers:
  - net/core/devlink.c:devlink_nl_cmd_get_dumpit
  - net/core/devlink.c:devlink_nl_cmd_get_doit
  - net/core/devlink.c:devlink_notify
```
**Symbols:**

```
ffff800010c2a008-ffff800010c2a124: devlink_nl_fill (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int devlink_nl_fill(struct sk_buff *msg, struct devlink *devlink, enum devlink_command cmd, u32 portid, u32 seq, int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/devlink.c (c0d40c30)
Location: net/core/devlink.c:462
Inline: False
Direct callers:
  - net/core/devlink.c:devlink_nl_cmd_get_dumpit
  - net/core/devlink.c:devlink_nl_cmd_get_doit
  - net/core/devlink.c:devlink_notify
```
**Symbols:**

```
c0d40c30-c0d40d48: devlink_nl_fill (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int devlink_nl_fill(struct sk_buff *msg, struct devlink *devlink, enum devlink_command cmd, u32 portid, u32 seq, int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/devlink.c (c000000000d20c80)
Location: net/core/devlink.c:462
Inline: False
Direct callers:
  - net/core/devlink.c:devlink_nl_cmd_get_dumpit
  - net/core/devlink.c:devlink_nl_cmd_get_doit
  - net/core/devlink.c:devlink_notify
```
**Symbols:**

```
c000000000d20c80-c000000000d20dd0: devlink_nl_fill (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int devlink_nl_fill(struct sk_buff *msg, struct devlink *devlink, enum devlink_command cmd, u32 portid, u32 seq, int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/devlink.c (ffffffe0007a25d6)
Location: net/core/devlink.c:462
Inline: False
Direct callers:
  - net/core/devlink.c:devlink_nl_cmd_get_dumpit
  - net/core/devlink.c:devlink_nl_cmd_get_doit
  - net/core/devlink.c:devlink_notify
```
**Symbols:**

```
ffffffe0007a25d6-ffffffe0007a2698: devlink_nl_fill (STB_LOCAL)
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
int devlink_nl_fill(struct sk_buff *msg, struct devlink *devlink, enum devlink_command cmd, u32 portid, u32 seq, int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/devlink.c (ffffffff81921e30)
Location: net/core/devlink.c:462
Inline: False
Direct callers:
  - net/core/devlink.c:devlink_nl_cmd_get_dumpit
  - net/core/devlink.c:devlink_nl_cmd_get_doit
  - net/core/devlink.c:devlink_notify
```
**Symbols:**

```
ffffffff81921e30-ffffffff81921f21: devlink_nl_fill (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int devlink_nl_fill(struct sk_buff *msg, struct devlink *devlink, enum devlink_command cmd, u32 portid, u32 seq, int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/devlink.c (ffffffff818dbbe0)
Location: net/core/devlink.c:462
Inline: False
Direct callers:
  - net/core/devlink.c:devlink_nl_cmd_get_dumpit
  - net/core/devlink.c:devlink_nl_cmd_get_doit
  - net/core/devlink.c:devlink_notify
```
**Symbols:**

```
ffffffff818dbbe0-ffffffff818dbcd1: devlink_nl_fill (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int devlink_nl_fill(struct sk_buff *msg, struct devlink *devlink, enum devlink_command cmd, u32 portid, u32 seq, int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/devlink.c (ffffffff81972fc0)
Location: net/core/devlink.c:462
Inline: False
Direct callers:
  - net/core/devlink.c:devlink_nl_cmd_get_dumpit
  - net/core/devlink.c:devlink_nl_cmd_get_doit
  - net/core/devlink.c:devlink_notify
```
**Symbols:**

```
ffffffff81972fc0-ffffffff819730b1: devlink_nl_fill (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int devlink_nl_fill(struct sk_buff *msg, struct devlink *devlink, enum devlink_command cmd, u32 portid, u32 seq, int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/devlink.c (ffffffff819954b0)
Location: net/core/devlink.c:462
Inline: False
Direct callers:
  - net/core/devlink.c:devlink_nl_cmd_get_dumpit
  - net/core/devlink.c:devlink_nl_cmd_get_doit
  - net/core/devlink.c:devlink_notify
```
**Symbols:**

```
ffffffff819954b0-ffffffff819955a1: devlink_nl_fill (STB_LOCAL)
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
