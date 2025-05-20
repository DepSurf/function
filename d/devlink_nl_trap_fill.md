# Function: <code>devlink_nl_trap_fill</code>

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
In <code>5.3</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int devlink_nl_trap_fill(struct sk_buff *msg, struct devlink *devlink, const struct devlink_trap_item *trap_item, enum devlink_command cmd, u32 portid, u32 seq, int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/devlink.c (ffffffff81983980)
Location: net/core/devlink.c:5380
Inline: False
Direct callers:
  - net/core/devlink.c:devlink_trap_notify
  - net/core/devlink.c:devlink_nl_cmd_trap_get_dumpit
  - net/core/devlink.c:devlink_nl_cmd_trap_get_doit
```
**Symbols:**

```
ffffffff81983980-ffffffff81983bc7: devlink_nl_trap_fill (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int devlink_nl_trap_fill(struct sk_buff *msg, struct devlink *devlink, const struct devlink_trap_item *trap_item, enum devlink_command cmd, u32 portid, u32 seq, int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/devlink.c (ffffffff81a5e670)
Location: net/core/devlink.c:5972
Inline: False
Direct callers:
  - net/core/devlink.c:devlink_trap_notify
  - net/core/devlink.c:devlink_nl_cmd_trap_get_dumpit
  - net/core/devlink.c:devlink_nl_cmd_trap_get_doit
```
**Symbols:**

```
ffffffff81a5e670-ffffffff81a5e824: devlink_nl_trap_fill (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int devlink_nl_trap_fill(struct sk_buff *msg, struct devlink *devlink, const struct devlink_trap_item *trap_item, enum devlink_command cmd, u32 portid, u32 seq, int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/devlink.c (ffffffff81a654d0)
Location: net/core/devlink.c:6823
Inline: False
Direct callers:
  - net/core/devlink.c:devlink_trap_notify
  - net/core/devlink.c:devlink_nl_cmd_trap_get_dumpit
  - net/core/devlink.c:devlink_nl_cmd_trap_get_doit
```
**Symbols:**

```
ffffffff81a654d0-ffffffff81a65688: devlink_nl_trap_fill (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int devlink_nl_trap_fill(struct sk_buff *msg, struct devlink *devlink, const struct devlink_trap_item *trap_item, enum devlink_command cmd, u32 portid, u32 seq, int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/devlink.c (ffffffff81a4ad90)
Location: net/core/devlink.c:7026
Inline: False
Direct callers:
  - net/core/devlink.c:devlink_trap_notify
  - net/core/devlink.c:devlink_nl_cmd_trap_get_dumpit
  - net/core/devlink.c:devlink_nl_cmd_trap_get_doit
```
**Symbols:**

```
ffffffff81a4ad90-ffffffff81a4aff1: devlink_nl_trap_fill (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int devlink_nl_trap_fill(struct sk_buff *msg, struct devlink *devlink, const struct devlink_trap_item *trap_item, enum devlink_command cmd, u32 portid, u32 seq, int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/core/devlink.c (0)
Location: net/core/devlink.c:7697
Inline: False
Direct callers:
  - net/core/devlink.c:devlink_trap_notify
  - net/core/devlink.c:devlink_nl_cmd_trap_get_dumpit
  - net/core/devlink.c:devlink_nl_cmd_trap_get_doit
```
**Symbols:**

```
ffffffff81b03410-ffffffff81b037d4: devlink_nl_trap_fill (STB_LOCAL)
ffffffff81d38ab5-ffffffff81d38aca: devlink_nl_trap_fill.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int devlink_nl_trap_fill(struct sk_buff *msg, struct devlink *devlink, const struct devlink_trap_item *trap_item, enum devlink_command cmd, u32 portid, u32 seq, int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/core/devlink.c (0)
Location: net/core/devlink.c:8190
Inline: False
Direct callers:
  - net/core/devlink.c:devlink_nl_cmd_trap_get_dumpit
  - net/core/devlink.c:devlink_nl_cmd_trap_get_doit
```
**Symbols:**

```
ffffffff81c84a80-ffffffff81c84e62: devlink_nl_trap_fill (STB_LOCAL)
ffffffff81f052e4-ffffffff81f052f9: devlink_nl_trap_fill.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
int devlink_nl_trap_fill(struct sk_buff *msg, struct devlink *devlink, const struct devlink_trap_item *trap_item, enum devlink_command cmd, u32 portid, u32 seq, int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/core/devlink.c (0)
Location: net/core/devlink.c:8729
Inline: False
Direct callers:
  - net/core/devlink.c:devlink_nl_cmd_trap_get_dumpit
  - net/core/devlink.c:devlink_nl_cmd_trap_get_doit
```
**Symbols:**

```
ffffffff81e3ebe0-ffffffff81e3efc2: devlink_nl_trap_fill (STB_LOCAL)
ffffffff820ad2ee-ffffffff820ad303: devlink_nl_trap_fill.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
int devlink_nl_trap_fill(struct sk_buff *msg, struct devlink *devlink, const struct devlink_trap_item *trap_item, enum devlink_command cmd, u32 portid, u32 seq, int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/devlink/leftover.c (0)
Location: net/devlink/leftover.c:5585
Inline: False
Direct callers:
  - net/devlink/leftover.c:devlink_nl_cmd_trap_get_dump_one
  - net/devlink/leftover.c:devlink_nl_cmd_trap_get_doit
```
**Symbols:**

```
ffffffff8203f2c0-ffffffff8203f6a2: devlink_nl_trap_fill (STB_LOCAL)
ffffffff821365f0-ffffffff82136605: devlink_nl_trap_fill.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
int devlink_nl_trap_fill(struct sk_buff *msg, struct devlink *devlink, const struct devlink_trap_item *trap_item, enum devlink_command cmd, u32 portid, u32 seq, int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/devlink/trap.c (0)
Location: net/devlink/trap.c:257
Inline: False
Direct callers:
  - net/devlink/trap.c:devlink_nl_trap_get_dump_one
  - net/devlink/trap.c:devlink_nl_trap_get_doit
```
**Symbols:**

```
ffffffff82115e10-ffffffff82116250: devlink_nl_trap_fill (STB_LOCAL)
ffffffff82218760-ffffffff82218775: devlink_nl_trap_fill.cold (STB_LOCAL)
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
int devlink_nl_trap_fill(struct sk_buff *msg, struct devlink *devlink, const struct devlink_trap_item *trap_item, enum devlink_command cmd, u32 portid, u32 seq, int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/devlink.c (ffff800010c2bfb0)
Location: net/core/devlink.c:5380
Inline: False
Direct callers:
  - net/core/devlink.c:devlink_trap_notify
  - net/core/devlink.c:devlink_nl_cmd_trap_get_dumpit
  - net/core/devlink.c:devlink_nl_cmd_trap_get_doit
```
**Symbols:**

```
ffff800010c2bfb0-ffff800010c2c21c: devlink_nl_trap_fill (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int devlink_nl_trap_fill(struct sk_buff *msg, struct devlink *devlink, const struct devlink_trap_item *trap_item, enum devlink_command cmd, u32 portid, u32 seq, int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/devlink.c (c0d42b3c)
Location: net/core/devlink.c:5380
Inline: False
Direct callers:
  - net/core/devlink.c:devlink_trap_notify
  - net/core/devlink.c:devlink_nl_cmd_trap_get_dumpit
  - net/core/devlink.c:devlink_nl_cmd_trap_get_doit
```
**Symbols:**

```
c0d42b3c-c0d42db0: devlink_nl_trap_fill (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int devlink_nl_trap_fill(struct sk_buff *msg, struct devlink *devlink, const struct devlink_trap_item *trap_item, enum devlink_command cmd, u32 portid, u32 seq, int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/devlink.c (c000000000d22a70)
Location: net/core/devlink.c:5380
Inline: False
Direct callers:
  - net/core/devlink.c:devlink_trap_notify
  - net/core/devlink.c:devlink_nl_cmd_trap_get_dumpit
  - net/core/devlink.c:devlink_nl_cmd_trap_get_doit
```
**Symbols:**

```
c000000000d22a70-c000000000d22da0: devlink_nl_trap_fill (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int devlink_nl_trap_fill(struct sk_buff *msg, struct devlink *devlink, const struct devlink_trap_item *trap_item, enum devlink_command cmd, u32 portid, u32 seq, int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/devlink.c (ffffffe0007a35ec)
Location: net/core/devlink.c:5380
Inline: False
Direct callers:
  - net/core/devlink.c:devlink_trap_notify
  - net/core/devlink.c:devlink_nl_cmd_trap_get_dumpit
  - net/core/devlink.c:devlink_nl_cmd_trap_get_doit
```
**Symbols:**

```
ffffffe0007a35ec-ffffffe0007a37c8: devlink_nl_trap_fill (STB_LOCAL)
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
int devlink_nl_trap_fill(struct sk_buff *msg, struct devlink *devlink, const struct devlink_trap_item *trap_item, enum devlink_command cmd, u32 portid, u32 seq, int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/devlink.c (ffffffff819237f0)
Location: net/core/devlink.c:5380
Inline: False
Direct callers:
  - net/core/devlink.c:devlink_trap_notify
  - net/core/devlink.c:devlink_nl_cmd_trap_get_dumpit
  - net/core/devlink.c:devlink_nl_cmd_trap_get_doit
```
**Symbols:**

```
ffffffff819237f0-ffffffff81923a37: devlink_nl_trap_fill (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int devlink_nl_trap_fill(struct sk_buff *msg, struct devlink *devlink, const struct devlink_trap_item *trap_item, enum devlink_command cmd, u32 portid, u32 seq, int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/devlink.c (ffffffff818dd5a0)
Location: net/core/devlink.c:5380
Inline: False
Direct callers:
  - net/core/devlink.c:devlink_trap_notify
  - net/core/devlink.c:devlink_nl_cmd_trap_get_dumpit
  - net/core/devlink.c:devlink_nl_cmd_trap_get_doit
```
**Symbols:**

```
ffffffff818dd5a0-ffffffff818dd7e7: devlink_nl_trap_fill (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int devlink_nl_trap_fill(struct sk_buff *msg, struct devlink *devlink, const struct devlink_trap_item *trap_item, enum devlink_command cmd, u32 portid, u32 seq, int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/devlink.c (ffffffff81974980)
Location: net/core/devlink.c:5380
Inline: False
Direct callers:
  - net/core/devlink.c:devlink_trap_notify
  - net/core/devlink.c:devlink_nl_cmd_trap_get_dumpit
  - net/core/devlink.c:devlink_nl_cmd_trap_get_doit
```
**Symbols:**

```
ffffffff81974980-ffffffff81974bc7: devlink_nl_trap_fill (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int devlink_nl_trap_fill(struct sk_buff *msg, struct devlink *devlink, const struct devlink_trap_item *trap_item, enum devlink_command cmd, u32 portid, u32 seq, int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/devlink.c (ffffffff81996e70)
Location: net/core/devlink.c:5380
Inline: False
Direct callers:
  - net/core/devlink.c:devlink_trap_notify
  - net/core/devlink.c:devlink_nl_cmd_trap_get_dumpit
  - net/core/devlink.c:devlink_nl_cmd_trap_get_doit
```
**Symbols:**

```
ffffffff81996e70-ffffffff819970b7: devlink_nl_trap_fill (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
