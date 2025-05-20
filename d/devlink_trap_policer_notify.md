# Function: <code>devlink_trap_policer_notify</code>

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
void devlink_trap_policer_notify(struct devlink *devlink, const struct devlink_trap_policer_item *policer_item, enum devlink_command cmd);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/devlink.c (ffffffff81a5fa20)
Location: net/core/devlink.c:9093
Inline: False
Direct callers:
  - net/core/devlink.c:devlink_trap_policer_unregister
  - net/core/devlink.c:devlink_trap_policer_register
```
**Symbols:**

```
ffffffff81a5fa20-ffffffff81a5face: devlink_trap_policer_notify (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void devlink_trap_policer_notify(struct devlink *devlink, const struct devlink_trap_policer_item *policer_item, enum devlink_command cmd);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/devlink.c (ffffffff81a68210)
Location: net/core/devlink.c:10047
Inline: False
Direct callers:
  - net/core/devlink.c:devlink_trap_policer_unregister
  - net/core/devlink.c:devlink_trap_policer_register
```
**Symbols:**

```
ffffffff81a68210-ffffffff81a682bd: devlink_trap_policer_notify (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void devlink_trap_policer_notify(struct devlink *devlink, const struct devlink_trap_policer_item *policer_item, enum devlink_command cmd);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/devlink.c (ffffffff81a43310)
Location: net/core/devlink.c:10311
Inline: False
Direct callers:
  - net/core/devlink.c:devlink_trap_policers_register
  - net/core/devlink.c:devlink_trap_policer_unregister
```
**Symbols:**

```
ffffffff81a43310-ffffffff81a433bd: devlink_trap_policer_notify (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void devlink_trap_policer_notify(struct devlink *devlink, const struct devlink_trap_policer_item *policer_item, enum devlink_command cmd);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/devlink.c (ffffffff81af97f0)
Location: net/core/devlink.c:11253
Inline: False
Direct callers:
  - net/core/devlink.c:devlink_trap_policers_register
  - net/core/devlink.c:devlink_trap_policer_unregister
```
**Symbols:**

```
ffffffff81af97f0-ffffffff81af989d: devlink_trap_policer_notify (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
void devlink_trap_policer_notify(struct devlink *devlink, const struct devlink_trap_policer_item *policer_item, enum devlink_command cmd);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/devlink.c (ffffffff81c7c550)
Location: net/core/devlink.c:11849
Inline: True
Direct callers:
  - net/core/devlink.c:devlink_trap_policers_register
  - net/core/devlink.c:devlink_trap_policer_unregister
  - net/core/devlink.c:devlink_unregister
  - net/core/devlink.c:devlink_register
```
**Symbols:**

```
ffffffff81c7c550-ffffffff81c7c664: devlink_trap_policer_notify (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
void devlink_trap_policer_notify(struct devlink *devlink, const struct devlink_trap_policer_item *policer_item, enum devlink_command cmd);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/devlink.c (ffffffff81e40e40)
Location: net/core/devlink.c:12742
Inline: True
Direct callers:
  - net/core/devlink.c:devl_trap_policers_register
  - net/core/devlink.c:devlink_trap_policer_unregister
  - net/core/devlink.c:devlink_notify_unregister
  - net/core/devlink.c:devlink_notify_register
```
**Symbols:**

```
ffffffff81e40e40-ffffffff81e40f54: devlink_trap_policer_notify (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
void devlink_trap_policer_notify(struct devlink *devlink, const struct devlink_trap_policer_item *policer_item, enum devlink_command cmd);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/devlink/leftover.c (ffffffff82037af0)
Location: net/devlink/leftover.c:9337
Inline: True
Direct callers:
  - net/devlink/leftover.c:devl_trap_policers_register
  - net/devlink/leftover.c:devlink_trap_policer_unregister
  - net/devlink/leftover.c:devlink_notify_unregister
  - net/devlink/leftover.c:devlink_notify_register
```
**Symbols:**

```
ffffffff82037af0-ffffffff82037c05: devlink_trap_policer_notify (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
void devlink_trap_policer_notify(struct devlink *devlink, const struct devlink_trap_policer_item *policer_item, enum devlink_command cmd);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/devlink/trap.c (ffffffff82114da0)
Location: net/devlink/trap.c:1704
Inline: True
Direct callers:
  - net/devlink/trap.c:devl_trap_policers_register
  - net/devlink/trap.c:devlink_trap_policer_unregister
  - net/devlink/trap.c:devlink_trap_policers_notify_unregister
  - net/devlink/trap.c:devlink_trap_policers_notify_register
```
**Symbols:**

```
ffffffff82114da0-ffffffff82114f56: devlink_trap_policer_notify (STB_LOCAL)
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
