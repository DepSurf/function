# Function: <code>devlink_nl_flash_update_fill</code>

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
In net/core/devlink.c (ffffffff8194ea17)
Location: net/core/devlink.c:2691
Inline: True
Inline callers:
  - net/core/devlink.c:__devlink_flash_update_notify
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
In net/core/devlink.c (ffffffff81984c97)
Location: net/core/devlink.c:2718
Inline: True
Inline callers:
  - net/core/devlink.c:__devlink_flash_update_notify
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
In net/core/devlink.c (ffffffff81a5e3af)
Location: net/core/devlink.c:2846
Inline: True
Inline callers:
  - net/core/devlink.c:__devlink_flash_update_notify
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int devlink_nl_flash_update_fill(struct sk_buff *msg, struct devlink *devlink, enum devlink_command cmd, struct devlink_flash_notify *params);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/devlink.c (ffffffff81a62fc0)
Location: net/core/devlink.c:3326
Inline: False
Direct callers:
  - net/core/devlink.c:__devlink_flash_update_notify
```
**Symbols:**

```
ffffffff81a62fc0-ffffffff81a63172: devlink_nl_flash_update_fill (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int devlink_nl_flash_update_fill(struct sk_buff *msg, struct devlink *devlink, enum devlink_command cmd, struct devlink_flash_notify *params);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/devlink.c (ffffffff81a46ea0)
Location: net/core/devlink.c:3529
Inline: False
Direct callers:
  - net/core/devlink.c:__devlink_flash_update_notify
```
**Symbols:**

```
ffffffff81a46ea0-ffffffff81a47051: devlink_nl_flash_update_fill (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int devlink_nl_flash_update_fill(struct sk_buff *msg, struct devlink *devlink, enum devlink_command cmd, struct devlink_flash_notify *params);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/devlink.c (ffffffff81afcdb0)
Location: net/core/devlink.c:4099
Inline: False
Direct callers:
  - net/core/devlink.c:__devlink_flash_update_notify
```
**Symbols:**

```
ffffffff81afcdb0-ffffffff81afcf61: devlink_nl_flash_update_fill (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int devlink_nl_flash_update_fill(struct sk_buff *msg, struct devlink *devlink, enum devlink_command cmd, struct devlink_flash_notify *params);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/devlink.c (ffffffff81c7fd20)
Location: net/core/devlink.c:4611
Inline: False
```
**Symbols:**

```
ffffffff81c7fd20-ffffffff81c7fee3: devlink_nl_flash_update_fill (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int devlink_nl_flash_update_fill(struct sk_buff *msg, struct devlink *devlink, enum devlink_command cmd, struct devlink_flash_notify *params);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/devlink.c (ffffffff81e38db0)
Location: net/core/devlink.c:4877
Inline: False
```
**Symbols:**

```
ffffffff81e38db0-ffffffff81e38f73: devlink_nl_flash_update_fill (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int devlink_nl_flash_update_fill(struct sk_buff *msg, struct devlink *devlink, enum devlink_command cmd, struct devlink_flash_notify *params);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/devlink/dev.c (ffffffff82043f50)
Location: net/devlink/dev.c:847
Inline: False
```
**Symbols:**

```
ffffffff82043f50-ffffffff8204416c: devlink_nl_flash_update_fill (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int devlink_nl_flash_update_fill(struct sk_buff *msg, struct devlink *devlink, enum devlink_command cmd, struct devlink_flash_notify *params);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/devlink/dev.c (ffffffff82103720)
Location: net/devlink/dev.c:949
Inline: False
```
**Symbols:**

```
ffffffff82103720-ffffffff8210393c: devlink_nl_flash_update_fill (STB_LOCAL)
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
In net/core/devlink.c (ffff800010c2d2b8)
Location: net/core/devlink.c:2718
Inline: True
Inline callers:
  - net/core/devlink.c:__devlink_flash_update_notify
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
In net/core/devlink.c (c0d43888)
Location: net/core/devlink.c:2718
Inline: True
Inline callers:
  - net/core/devlink.c:__devlink_flash_update_notify
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/core/devlink.c (c000000000d25750)
Location: net/core/devlink.c:2718
Inline: True
Inline callers:
  - net/core/devlink.c:__devlink_flash_update_notify
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
In net/core/devlink.c (ffffffe0007a452c)
Location: net/core/devlink.c:2718
Inline: True
Inline callers:
  - net/core/devlink.c:__devlink_flash_update_notify
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
In net/core/devlink.c (ffffffff81924b07)
Location: net/core/devlink.c:2718
Inline: True
Inline callers:
  - net/core/devlink.c:__devlink_flash_update_notify
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
In net/core/devlink.c (ffffffff818de8b7)
Location: net/core/devlink.c:2718
Inline: True
Inline callers:
  - net/core/devlink.c:__devlink_flash_update_notify
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
In net/core/devlink.c (ffffffff81975c97)
Location: net/core/devlink.c:2718
Inline: True
Inline callers:
  - net/core/devlink.c:__devlink_flash_update_notify
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
In net/core/devlink.c (ffffffff81998187)
Location: net/core/devlink.c:2718
Inline: True
Inline callers:
  - net/core/devlink.c:__devlink_flash_update_notify
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
