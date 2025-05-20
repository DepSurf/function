# Function: <code>devlink_nl_trap_policer_fill</code>

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
In <code>5.4</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int devlink_nl_trap_policer_fill(struct sk_buff *msg, struct devlink *devlink, const struct devlink_trap_policer_item *policer_item, enum devlink_command cmd, u32 portid, u32 seq, int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/devlink.c (ffffffff81a5f610)
Location: net/core/devlink.c:6490
Inline: False
Direct callers:
  - net/core/devlink.c:devlink_trap_policer_notify
  - net/core/devlink.c:devlink_nl_cmd_trap_policer_get_dumpit
  - net/core/devlink.c:devlink_nl_cmd_trap_policer_get_doit
```
**Symbols:**

```
ffffffff81a5f610-ffffffff81a5f76e: devlink_nl_trap_policer_fill (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int devlink_nl_trap_policer_fill(struct sk_buff *msg, struct devlink *devlink, const struct devlink_trap_policer_item *policer_item, enum devlink_command cmd, u32 portid, u32 seq, int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/devlink.c (ffffffff81a67e00)
Location: net/core/devlink.c:7355
Inline: False
Direct callers:
  - net/core/devlink.c:devlink_trap_policer_notify
  - net/core/devlink.c:devlink_nl_cmd_trap_policer_get_dumpit
  - net/core/devlink.c:devlink_nl_cmd_trap_policer_get_doit
```
**Symbols:**

```
ffffffff81a67e00-ffffffff81a67f5e: devlink_nl_trap_policer_fill (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int devlink_nl_trap_policer_fill(struct sk_buff *msg, struct devlink *devlink, const struct devlink_trap_policer_item *policer_item, enum devlink_command cmd, u32 portid, u32 seq, int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/devlink.c (ffffffff81a42e50)
Location: net/core/devlink.c:7558
Inline: False
Direct callers:
  - net/core/devlink.c:devlink_trap_policer_notify
  - net/core/devlink.c:devlink_nl_cmd_trap_policer_get_dumpit
  - net/core/devlink.c:devlink_nl_cmd_trap_policer_get_doit
```
**Symbols:**

```
ffffffff81a42e50-ffffffff81a43056: devlink_nl_trap_policer_fill (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int devlink_nl_trap_policer_fill(struct sk_buff *msg, struct devlink *devlink, const struct devlink_trap_policer_item *policer_item, enum devlink_command cmd, u32 portid, u32 seq, int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/devlink.c (ffffffff81af92c0)
Location: net/core/devlink.c:8245
Inline: False
Direct callers:
  - net/core/devlink.c:devlink_trap_policer_notify
  - net/core/devlink.c:devlink_nl_cmd_trap_policer_get_dumpit
  - net/core/devlink.c:devlink_nl_cmd_trap_policer_get_doit
```
**Symbols:**

```
ffffffff81af92c0-ffffffff81af94c6: devlink_nl_trap_policer_fill (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int devlink_nl_trap_policer_fill(struct sk_buff *msg, struct devlink *devlink, const struct devlink_trap_policer_item *policer_item, enum devlink_command cmd, u32 portid, u32 seq, int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/devlink.c (ffffffff81c7c1c0)
Location: net/core/devlink.c:8738
Inline: False
Direct callers:
  - net/core/devlink.c:devlink_nl_cmd_trap_policer_get_dumpit
  - net/core/devlink.c:devlink_nl_cmd_trap_policer_get_doit
```
**Symbols:**

```
ffffffff81c7c1c0-ffffffff81c7c3de: devlink_nl_trap_policer_fill (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int devlink_nl_trap_policer_fill(struct sk_buff *msg, struct devlink *devlink, const struct devlink_trap_policer_item *policer_item, enum devlink_command cmd, u32 portid, u32 seq, int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/devlink.c (ffffffff81e40a90)
Location: net/core/devlink.c:9257
Inline: False
Direct callers:
  - net/core/devlink.c:devlink_nl_cmd_trap_policer_get_dumpit
  - net/core/devlink.c:devlink_nl_cmd_trap_policer_get_doit
```
**Symbols:**

```
ffffffff81e40a90-ffffffff81e40cae: devlink_nl_trap_policer_fill (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int devlink_nl_trap_policer_fill(struct sk_buff *msg, struct devlink *devlink, const struct devlink_trap_policer_item *policer_item, enum devlink_command cmd, u32 portid, u32 seq, int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/devlink/leftover.c (ffffffff82037600)
Location: net/devlink/leftover.c:6099
Inline: False
Direct callers:
  - net/devlink/leftover.c:devlink_nl_cmd_trap_policer_get_dump_one
  - net/devlink/leftover.c:devlink_nl_cmd_trap_policer_get_doit
```
**Symbols:**

```
ffffffff82037600-ffffffff82037872: devlink_nl_trap_policer_fill (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int devlink_nl_trap_policer_fill(struct sk_buff *msg, struct devlink *devlink, const struct devlink_trap_policer_item *policer_item, enum devlink_command cmd, u32 portid, u32 seq, int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/devlink/trap.c (ffffffff82114a30)
Location: net/devlink/trap.c:767
Inline: False
Direct callers:
  - net/devlink/trap.c:devlink_nl_trap_policer_get_dump_one
  - net/devlink/trap.c:devlink_nl_trap_policer_get_doit
```
**Symbols:**

```
ffffffff82114a30-ffffffff82114ca2: devlink_nl_trap_policer_fill (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
In <code>arm64</code>: Absent ⚠️
</li>
<li>
In <code>armhf</code>: Absent ⚠️
</li>
<li>
In <code>ppc64el</code>: Absent ⚠️
</li>
<li>
In <code>riscv64</code>: Absent ⚠️
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
In <code>aws</code>: Absent ⚠️
</li>
<li>
In <code>azure</code>: Absent ⚠️
</li>
<li>
In <code>gcp</code>: Absent ⚠️
</li>
<li>
In <code>lowlatency</code>: Absent ⚠️
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
