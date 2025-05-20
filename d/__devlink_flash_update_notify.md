# Function: <code>__devlink_flash_update_notify</code>

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
void __devlink_flash_update_notify(struct devlink *devlink, enum devlink_command cmd, const char *status_msg, const char *component, long unsigned int done, long unsigned int total);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/core/devlink.c (0)
Location: net/core/devlink.c:2734
Inline: False
Direct callers:
  - net/core/devlink.c:devlink_flash_update_status_notify
  - net/core/devlink.c:devlink_flash_update_end_notify
  - net/core/devlink.c:devlink_flash_update_begin_notify
```
**Symbols:**

```
ffffffff8194e9b0-ffffffff8194ebab: __devlink_flash_update_notify (STB_LOCAL)
ffffffff8195249b-ffffffff819524c8: __devlink_flash_update_notify.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void __devlink_flash_update_notify(struct devlink *devlink, enum devlink_command cmd, const char *status_msg, const char *component, long unsigned int done, long unsigned int total);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/devlink.c (ffffffff81984c30)
Location: net/core/devlink.c:2761
Inline: False
Direct callers:
  - net/core/devlink.c:devlink_flash_update_status_notify
  - net/core/devlink.c:devlink_flash_update_end_notify
  - net/core/devlink.c:devlink_flash_update_begin_notify
```
**Symbols:**

```
ffffffff81984c30-ffffffff81984e32: __devlink_flash_update_notify (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void __devlink_flash_update_notify(struct devlink *devlink, enum devlink_command cmd, const char *status_msg, const char *component, long unsigned int done, long unsigned int total);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/devlink.c (ffffffff81a5e340)
Location: net/core/devlink.c:2889
Inline: False
Direct callers:
  - net/core/devlink.c:devlink_flash_update_status_notify
  - net/core/devlink.c:devlink_flash_update_end_notify
  - net/core/devlink.c:devlink_flash_update_begin_notify
```
**Symbols:**

```
ffffffff81a5e340-ffffffff81a5e52a: __devlink_flash_update_notify (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void __devlink_flash_update_notify(struct devlink *devlink, enum devlink_command cmd, struct devlink_flash_notify *params);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/devlink.c (ffffffff81a63180)
Location: net/core/devlink.c:3370
Inline: False
Direct callers:
  - net/core/devlink.c:devlink_compat_flash_update
  - net/core/devlink.c:devlink_compat_flash_update
  - net/core/devlink.c:devlink_nl_cmd_flash_update
  - net/core/devlink.c:devlink_nl_cmd_flash_update
  - net/core/devlink.c:devlink_flash_update_timeout_notify
  - net/core/devlink.c:devlink_flash_update_status_notify
```
**Symbols:**

```
ffffffff81a63180-ffffffff81a6321c: __devlink_flash_update_notify (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void __devlink_flash_update_notify(struct devlink *devlink, enum devlink_command cmd, struct devlink_flash_notify *params);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/devlink.c (ffffffff81a47060)
Location: net/core/devlink.c:3573
Inline: False
Direct callers:
  - net/core/devlink.c:devlink_compat_flash_update
  - net/core/devlink.c:devlink_compat_flash_update
  - net/core/devlink.c:devlink_nl_cmd_flash_update
  - net/core/devlink.c:devlink_nl_cmd_flash_update
  - net/core/devlink.c:devlink_flash_update_timeout_notify
  - net/core/devlink.c:devlink_flash_update_status_notify
```
**Symbols:**

```
ffffffff81a47060-ffffffff81a470fc: __devlink_flash_update_notify (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void __devlink_flash_update_notify(struct devlink *devlink, enum devlink_command cmd, struct devlink_flash_notify *params);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/devlink.c (ffffffff81afcf70)
Location: net/core/devlink.c:4143
Inline: False
Direct callers:
  - net/core/devlink.c:devlink_compat_flash_update
  - net/core/devlink.c:devlink_compat_flash_update
  - net/core/devlink.c:devlink_nl_cmd_flash_update
  - net/core/devlink.c:devlink_nl_cmd_flash_update
  - net/core/devlink.c:devlink_flash_update_timeout_notify
  - net/core/devlink.c:devlink_flash_update_status_notify
```
**Symbols:**

```
ffffffff81afcf70-ffffffff81afd00c: __devlink_flash_update_notify (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
void __devlink_flash_update_notify(struct devlink *devlink, enum devlink_command cmd, struct devlink_flash_notify *params);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/devlink.c (ffffffff81c7fef0)
Location: net/core/devlink.c:4655
Inline: True
Direct callers:
  - net/core/devlink.c:devlink_compat_flash_update
  - net/core/devlink.c:devlink_compat_flash_update
  - net/core/devlink.c:devlink_nl_cmd_flash_update
  - net/core/devlink.c:devlink_nl_cmd_flash_update
  - net/core/devlink.c:devlink_flash_update_timeout_notify
  - net/core/devlink.c:devlink_flash_update_status_notify
```
**Symbols:**

```
ffffffff81c7fef0-ffffffff81c7ffe6: __devlink_flash_update_notify (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
void __devlink_flash_update_notify(struct devlink *devlink, enum devlink_command cmd, struct devlink_flash_notify *params);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/devlink.c (ffffffff81e38f90)
Location: net/core/devlink.c:4921
Inline: True
Direct callers:
  - net/core/devlink.c:devlink_compat_flash_update
  - net/core/devlink.c:devlink_compat_flash_update
  - net/core/devlink.c:devlink_nl_cmd_flash_update
  - net/core/devlink.c:devlink_nl_cmd_flash_update
  - net/core/devlink.c:devlink_flash_update_timeout_notify
  - net/core/devlink.c:devlink_flash_update_status_notify
```
**Symbols:**

```
ffffffff81e38f90-ffffffff81e39086: __devlink_flash_update_notify (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
void __devlink_flash_update_notify(struct devlink *devlink, enum devlink_command cmd, struct devlink_flash_notify *params);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/devlink/dev.c (ffffffff82044180)
Location: net/devlink/dev.c:891
Inline: True
Direct callers:
  - net/devlink/dev.c:devlink_compat_flash_update
  - net/devlink/dev.c:devlink_compat_flash_update
  - net/devlink/dev.c:devlink_nl_cmd_flash_update
  - net/devlink/dev.c:devlink_nl_cmd_flash_update
  - net/devlink/dev.c:devlink_flash_update_timeout_notify
  - net/devlink/dev.c:devlink_flash_update_status_notify
```
**Symbols:**

```
ffffffff82044180-ffffffff82044277: __devlink_flash_update_notify (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline, Transformation ⚠️</summary>

```c
void __devlink_flash_update_notify(struct devlink *devlink, enum devlink_command cmd, struct devlink_flash_notify *params);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/devlink/dev.c (ffffffff82103950)
Location: net/devlink/dev.c:993
Inline: True
Direct callers:
  - net/devlink/dev.c:devlink_compat_flash_update
  - net/devlink/dev.c:devlink_compat_flash_update
  - net/devlink/dev.c:devlink_nl_flash_update_doit
  - net/devlink/dev.c:devlink_nl_flash_update_doit
  - net/devlink/dev.c:devlink_flash_update_timeout_notify
  - net/devlink/dev.c:devlink_flash_update_status_notify
```
**Symbols:**

```
ffffffff82103950-ffffffff82103aa0: __devlink_flash_update_notify.part.0 (STB_LOCAL)
ffffffff82103ab0-ffffffff82103b42: __devlink_flash_update_notify (STB_LOCAL)
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
void __devlink_flash_update_notify(struct devlink *devlink, enum devlink_command cmd, const char *status_msg, const char *component, long unsigned int done, long unsigned int total);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/devlink.c (ffff800010c2d250)
Location: net/core/devlink.c:2761
Inline: False
Direct callers:
  - net/core/devlink.c:devlink_flash_update_status_notify
  - net/core/devlink.c:devlink_flash_update_end_notify
  - net/core/devlink.c:devlink_flash_update_begin_notify
```
**Symbols:**

```
ffff800010c2d250-ffff800010c2d434: __devlink_flash_update_notify (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void __devlink_flash_update_notify(struct devlink *devlink, enum devlink_command cmd, const char *status_msg, const char *component, long unsigned int done, long unsigned int total);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/devlink.c (c0d43830)
Location: net/core/devlink.c:2761
Inline: False
Direct callers:
  - net/core/devlink.c:devlink_flash_update_status_notify
  - net/core/devlink.c:devlink_flash_update_end_notify
  - net/core/devlink.c:devlink_flash_update_begin_notify
```
**Symbols:**

```
c0d43830-c0d43a70: __devlink_flash_update_notify (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void __devlink_flash_update_notify(struct devlink *devlink, enum devlink_command cmd, const char *status_msg, const char *component, long unsigned int done, long unsigned int total);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/devlink.c (c000000000d256c0)
Location: net/core/devlink.c:2761
Inline: False
Direct callers:
  - net/core/devlink.c:devlink_flash_update_status_notify
  - net/core/devlink.c:devlink_flash_update_end_notify
  - net/core/devlink.c:devlink_flash_update_begin_notify
```
**Symbols:**

```
c000000000d256c0-c000000000d25958: __devlink_flash_update_notify (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void __devlink_flash_update_notify(struct devlink *devlink, enum devlink_command cmd, const char *status_msg, const char *component, long unsigned int done, long unsigned int total);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/devlink.c (ffffffe0007a44e4)
Location: net/core/devlink.c:2761
Inline: False
Direct callers:
  - net/core/devlink.c:devlink_flash_update_status_notify
  - net/core/devlink.c:devlink_flash_update_end_notify
  - net/core/devlink.c:devlink_flash_update_begin_notify
```
**Symbols:**

```
ffffffe0007a44e4-ffffffe0007a4668: __devlink_flash_update_notify (STB_LOCAL)
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
void __devlink_flash_update_notify(struct devlink *devlink, enum devlink_command cmd, const char *status_msg, const char *component, long unsigned int done, long unsigned int total);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/devlink.c (ffffffff81924aa0)
Location: net/core/devlink.c:2761
Inline: False
Direct callers:
  - net/core/devlink.c:devlink_flash_update_status_notify
  - net/core/devlink.c:devlink_flash_update_end_notify
  - net/core/devlink.c:devlink_flash_update_begin_notify
```
**Symbols:**

```
ffffffff81924aa0-ffffffff81924ca2: __devlink_flash_update_notify (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void __devlink_flash_update_notify(struct devlink *devlink, enum devlink_command cmd, const char *status_msg, const char *component, long unsigned int done, long unsigned int total);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/devlink.c (ffffffff818de850)
Location: net/core/devlink.c:2761
Inline: False
Direct callers:
  - net/core/devlink.c:devlink_flash_update_status_notify
  - net/core/devlink.c:devlink_flash_update_end_notify
  - net/core/devlink.c:devlink_flash_update_begin_notify
```
**Symbols:**

```
ffffffff818de850-ffffffff818dea52: __devlink_flash_update_notify (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void __devlink_flash_update_notify(struct devlink *devlink, enum devlink_command cmd, const char *status_msg, const char *component, long unsigned int done, long unsigned int total);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/devlink.c (ffffffff81975c30)
Location: net/core/devlink.c:2761
Inline: False
Direct callers:
  - net/core/devlink.c:devlink_flash_update_status_notify
  - net/core/devlink.c:devlink_flash_update_end_notify
  - net/core/devlink.c:devlink_flash_update_begin_notify
```
**Symbols:**

```
ffffffff81975c30-ffffffff81975e32: __devlink_flash_update_notify (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void __devlink_flash_update_notify(struct devlink *devlink, enum devlink_command cmd, const char *status_msg, const char *component, long unsigned int done, long unsigned int total);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/devlink.c (ffffffff81998120)
Location: net/core/devlink.c:2761
Inline: False
Direct callers:
  - net/core/devlink.c:devlink_flash_update_status_notify
  - net/core/devlink.c:devlink_flash_update_end_notify
  - net/core/devlink.c:devlink_flash_update_begin_notify
```
**Symbols:**

```
ffffffff81998120-ffffffff81998322: __devlink_flash_update_notify (STB_LOCAL)
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
<details>
<summary>Changed between <code>5.8</code> and <code>5.11</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>struct devlink_flash_notify *params</code>
</li>
<li>
<b>Param removed. </b>
<code>const char *status_msg</code>
</li>
<li>
<b>Param removed. </b>
<code>const char *component</code>
</li>
<li>
<b>Param removed. </b>
<code>long unsigned int done</code>
</li>
<li>
<b>Param removed. </b>
<code>long unsigned int total</code>
</li>
</ul>
</details>
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
