# Function: <code>devlink_nl_param_fill</code>

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
int devlink_nl_param_fill(struct sk_buff *msg, struct devlink *devlink, unsigned int port_index, struct devlink_param_item *param_item, enum devlink_command cmd, u32 portid, u32 seq, int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/core/devlink.c (0)
Location: net/core/devlink.c:3001
Inline: False
Direct callers:
  - net/core/devlink.c:devlink_nl_cmd_port_param_get_doit
  - net/core/devlink.c:devlink_nl_cmd_port_param_get_dumpit
  - net/core/devlink.c:devlink_nl_cmd_param_get_doit
  - net/core/devlink.c:devlink_nl_cmd_param_get_dumpit
  - net/core/devlink.c:devlink_param_notify
```
**Symbols:**

```
ffffffff8194fb90-ffffffff819501d6: devlink_nl_param_fill (STB_LOCAL)
ffffffff8195250c-ffffffff81952580: devlink_nl_param_fill.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
int devlink_nl_param_fill(struct sk_buff *msg, struct devlink *devlink, unsigned int port_index, struct devlink_param_item *param_item, enum devlink_command cmd, u32 portid, u32 seq, int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/core/devlink.c (0)
Location: net/core/devlink.c:3033
Inline: False
Direct callers:
  - net/core/devlink.c:devlink_nl_cmd_port_param_get_doit
  - net/core/devlink.c:devlink_nl_cmd_port_param_get_dumpit
  - net/core/devlink.c:devlink_nl_cmd_param_get_doit
  - net/core/devlink.c:devlink_nl_cmd_param_get_dumpit
  - net/core/devlink.c:devlink_param_notify
```
**Symbols:**

```
ffffffff81986200-ffffffff8198685b: devlink_nl_param_fill (STB_LOCAL)
ffffffff8198899d-ffffffff819889b5: devlink_nl_param_fill.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int devlink_nl_param_fill(struct sk_buff *msg, struct devlink *devlink, unsigned int port_index, struct devlink_param_item *param_item, enum devlink_command cmd, u32 portid, u32 seq, int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/devlink.c (ffffffff81a5cad0)
Location: net/core/devlink.c:3166
Inline: False
Direct callers:
  - net/core/devlink.c:devlink_nl_cmd_port_param_get_doit
  - net/core/devlink.c:devlink_nl_cmd_port_param_get_dumpit
  - net/core/devlink.c:devlink_nl_cmd_param_get_doit
  - net/core/devlink.c:devlink_nl_cmd_param_get_dumpit
  - net/core/devlink.c:devlink_param_notify
```
**Symbols:**

```
ffffffff81a5cad0-ffffffff81a5cef4: devlink_nl_param_fill (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int devlink_nl_param_fill(struct sk_buff *msg, struct devlink *devlink, unsigned int port_index, struct devlink_param_item *param_item, enum devlink_command cmd, u32 portid, u32 seq, int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/devlink.c (ffffffff81a63ec0)
Location: net/core/devlink.c:3711
Inline: False
Direct callers:
  - net/core/devlink.c:devlink_nl_cmd_port_param_get_doit
  - net/core/devlink.c:devlink_nl_cmd_port_param_get_dumpit
  - net/core/devlink.c:devlink_nl_cmd_param_get_doit
  - net/core/devlink.c:devlink_nl_cmd_param_get_dumpit
  - net/core/devlink.c:devlink_param_notify
```
**Symbols:**

```
ffffffff81a63ec0-ffffffff81a642e4: devlink_nl_param_fill (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int devlink_nl_param_fill(struct sk_buff *msg, struct devlink *devlink, unsigned int port_index, struct devlink_param_item *param_item, enum devlink_command cmd, u32 portid, u32 seq, int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/devlink.c (ffffffff81a47ef0)
Location: net/core/devlink.c:3914
Inline: False
Direct callers:
  - net/core/devlink.c:devlink_nl_cmd_port_param_get_doit
  - net/core/devlink.c:devlink_nl_cmd_port_param_get_dumpit
  - net/core/devlink.c:devlink_nl_cmd_param_get_doit
  - net/core/devlink.c:devlink_nl_cmd_param_get_dumpit
  - net/core/devlink.c:devlink_param_notify
```
**Symbols:**

```
ffffffff81a47ef0-ffffffff81a48302: devlink_nl_param_fill (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int devlink_nl_param_fill(struct sk_buff *msg, struct devlink *devlink, unsigned int port_index, struct devlink_param_item *param_item, enum devlink_command cmd, u32 portid, u32 seq, int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/core/devlink.c (0)
Location: net/core/devlink.c:4499
Inline: False
Direct callers:
  - net/core/devlink.c:devlink_nl_cmd_port_param_get_doit
  - net/core/devlink.c:devlink_nl_cmd_port_param_get_dumpit
  - net/core/devlink.c:devlink_nl_cmd_param_get_doit
  - net/core/devlink.c:devlink_nl_cmd_param_get_dumpit
  - net/core/devlink.c:devlink_param_notify
```
**Symbols:**

```
ffffffff81afedf0-ffffffff81aff374: devlink_nl_param_fill (STB_LOCAL)
ffffffff81d3888a-ffffffff81d38996: devlink_nl_param_fill.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int devlink_nl_param_fill(struct sk_buff *msg, struct devlink *devlink, unsigned int port_index, struct devlink_param_item *param_item, enum devlink_command cmd, u32 portid, u32 seq, int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/core/devlink.c (0)
Location: net/core/devlink.c:5029
Inline: False
Direct callers:
  - net/core/devlink.c:devlink_nl_cmd_port_param_get_doit
  - net/core/devlink.c:devlink_nl_cmd_port_param_get_dumpit
  - net/core/devlink.c:devlink_nl_cmd_param_get_doit
  - net/core/devlink.c:devlink_nl_cmd_param_get_dumpit
  - net/core/devlink.c:devlink_param_notify
```
**Symbols:**

```
ffffffff81c82710-ffffffff81c82d2c: devlink_nl_param_fill (STB_LOCAL)
ffffffff81f05206-ffffffff81f05287: devlink_nl_param_fill.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/core/devlink.c (0)
Location: net/core/devlink.c:5553
Inline: True
Direct callers:
  - net/core/devlink.c:devlink_nl_cmd_param_get_doit
  - net/core/devlink.c:devlink_nl_cmd_param_get_dumpit
```
**Symbols:**

```
ffffffff81e3ad00-ffffffff81e3b257: devlink_nl_param_fill.constprop.0 (STB_LOCAL)
ffffffff820ad1cf-ffffffff820ad250: devlink_nl_param_fill.constprop.0.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/devlink/leftover.c (0)
Location: net/devlink/leftover.c:4032
Inline: True
Direct callers:
  - net/devlink/leftover.c:devlink_nl_cmd_param_get_doit
  - net/devlink/leftover.c:devlink_nl_cmd_param_get_dump_one
```
**Symbols:**

```
ffffffff8203aba0-ffffffff8203b125: devlink_nl_param_fill.constprop.0 (STB_LOCAL)
ffffffff821364d5-ffffffff8213655e: devlink_nl_param_fill.constprop.0.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/devlink/param.c (0)
Location: net/devlink/param.c:237
Inline: True
Direct callers:
  - net/devlink/param.c:devlink_nl_param_get_doit
  - net/devlink/param.c:devlink_nl_param_get_dump_one
```
**Symbols:**

```
ffffffff8210dd30-ffffffff8210e2fb: devlink_nl_param_fill.constprop.0 (STB_LOCAL)
ffffffff8221820d-ffffffff82218296: devlink_nl_param_fill.constprop.0.cold (STB_LOCAL)
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
int devlink_nl_param_fill(struct sk_buff *msg, struct devlink *devlink, unsigned int port_index, struct devlink_param_item *param_item, enum devlink_command cmd, u32 portid, u32 seq, int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/devlink.c (ffff800010c2e7a0)
Location: net/core/devlink.c:3033
Inline: False
Direct callers:
  - net/core/devlink.c:devlink_nl_cmd_port_param_get_doit
  - net/core/devlink.c:devlink_nl_cmd_port_param_get_dumpit
  - net/core/devlink.c:devlink_nl_cmd_param_get_doit
  - net/core/devlink.c:devlink_nl_cmd_param_get_dumpit
  - net/core/devlink.c:devlink_param_notify
```
**Symbols:**

```
ffff800010c2e7a0-ffff800010c2ecc8: devlink_nl_param_fill (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int devlink_nl_param_fill(struct sk_buff *msg, struct devlink *devlink, unsigned int port_index, struct devlink_param_item *param_item, enum devlink_command cmd, u32 portid, u32 seq, int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/devlink.c (c0d457a8)
Location: net/core/devlink.c:3033
Inline: False
Direct callers:
  - net/core/devlink.c:devlink_nl_cmd_port_param_get_doit
  - net/core/devlink.c:devlink_nl_cmd_port_param_get_dumpit
  - net/core/devlink.c:devlink_nl_cmd_param_get_doit
  - net/core/devlink.c:devlink_nl_cmd_param_get_dumpit
  - net/core/devlink.c:devlink_param_notify
```
**Symbols:**

```
c0d457a8-c0d45cfc: devlink_nl_param_fill (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int devlink_nl_param_fill(struct sk_buff *msg, struct devlink *devlink, unsigned int port_index, struct devlink_param_item *param_item, enum devlink_command cmd, u32 portid, u32 seq, int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/devlink.c (c000000000d263b0)
Location: net/core/devlink.c:3033
Inline: False
Direct callers:
  - net/core/devlink.c:devlink_nl_cmd_port_param_get_doit
  - net/core/devlink.c:devlink_nl_cmd_port_param_get_dumpit
  - net/core/devlink.c:devlink_nl_cmd_param_get_doit
  - net/core/devlink.c:devlink_nl_cmd_param_get_dumpit
  - net/core/devlink.c:devlink_param_notify
```
**Symbols:**

```
c000000000d263b0-c000000000d26a4c: devlink_nl_param_fill (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int devlink_nl_param_fill(struct sk_buff *msg, struct devlink *devlink, unsigned int port_index, struct devlink_param_item *param_item, enum devlink_command cmd, u32 portid, u32 seq, int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/devlink.c (ffffffe0007a4f44)
Location: net/core/devlink.c:3033
Inline: False
Direct callers:
  - net/core/devlink.c:devlink_nl_cmd_port_param_get_doit
  - net/core/devlink.c:devlink_nl_cmd_port_param_get_dumpit
  - net/core/devlink.c:devlink_nl_cmd_param_get_doit
  - net/core/devlink.c:devlink_nl_cmd_param_get_dumpit
  - net/core/devlink.c:devlink_param_notify
```
**Symbols:**

```
ffffffe0007a4f44-ffffffe0007a538c: devlink_nl_param_fill (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Transformation ⚠️</summary>

```c
int devlink_nl_param_fill(struct sk_buff *msg, struct devlink *devlink, unsigned int port_index, struct devlink_param_item *param_item, enum devlink_command cmd, u32 portid, u32 seq, int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/core/devlink.c (0)
Location: net/core/devlink.c:3033
Inline: False
Direct callers:
  - net/core/devlink.c:devlink_nl_cmd_port_param_get_doit
  - net/core/devlink.c:devlink_nl_cmd_port_param_get_dumpit
  - net/core/devlink.c:devlink_nl_cmd_param_get_doit
  - net/core/devlink.c:devlink_nl_cmd_param_get_dumpit
  - net/core/devlink.c:devlink_param_notify
```
**Symbols:**

```
ffffffff81926070-ffffffff819266cb: devlink_nl_param_fill (STB_LOCAL)
ffffffff8192880d-ffffffff81928825: devlink_nl_param_fill.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Transformation ⚠️</summary>

```c
int devlink_nl_param_fill(struct sk_buff *msg, struct devlink *devlink, unsigned int port_index, struct devlink_param_item *param_item, enum devlink_command cmd, u32 portid, u32 seq, int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/core/devlink.c (0)
Location: net/core/devlink.c:3033
Inline: False
Direct callers:
  - net/core/devlink.c:devlink_nl_cmd_port_param_get_doit
  - net/core/devlink.c:devlink_nl_cmd_port_param_get_dumpit
  - net/core/devlink.c:devlink_nl_cmd_param_get_doit
  - net/core/devlink.c:devlink_nl_cmd_param_get_dumpit
  - net/core/devlink.c:devlink_param_notify
```
**Symbols:**

```
ffffffff818dfe20-ffffffff818e047b: devlink_nl_param_fill (STB_LOCAL)
ffffffff818e25bd-ffffffff818e25d5: devlink_nl_param_fill.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Transformation ⚠️</summary>

```c
int devlink_nl_param_fill(struct sk_buff *msg, struct devlink *devlink, unsigned int port_index, struct devlink_param_item *param_item, enum devlink_command cmd, u32 portid, u32 seq, int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/core/devlink.c (0)
Location: net/core/devlink.c:3033
Inline: False
Direct callers:
  - net/core/devlink.c:devlink_nl_cmd_port_param_get_doit
  - net/core/devlink.c:devlink_nl_cmd_port_param_get_dumpit
  - net/core/devlink.c:devlink_nl_cmd_param_get_doit
  - net/core/devlink.c:devlink_nl_cmd_param_get_dumpit
  - net/core/devlink.c:devlink_param_notify
```
**Symbols:**

```
ffffffff81977200-ffffffff8197785b: devlink_nl_param_fill (STB_LOCAL)
ffffffff8197999d-ffffffff819799b5: devlink_nl_param_fill.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
int devlink_nl_param_fill(struct sk_buff *msg, struct devlink *devlink, unsigned int port_index, struct devlink_param_item *param_item, enum devlink_command cmd, u32 portid, u32 seq, int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/core/devlink.c (0)
Location: net/core/devlink.c:3033
Inline: False
Direct callers:
  - net/core/devlink.c:devlink_nl_cmd_port_param_get_doit
  - net/core/devlink.c:devlink_nl_cmd_port_param_get_dumpit
  - net/core/devlink.c:devlink_nl_cmd_param_get_doit
  - net/core/devlink.c:devlink_nl_cmd_param_get_dumpit
  - net/core/devlink.c:devlink_param_notify
```
**Symbols:**

```
ffffffff819996f0-ffffffff81999d4b: devlink_nl_param_fill (STB_LOCAL)
ffffffff8199be8d-ffffffff8199bea5: devlink_nl_param_fill.cold (STB_LOCAL)
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
