# Function: <code>devlink_linecard_notify</code>

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
In <code>5.8</code>: Absent ⚠️
</li>
<li>
In <code>5.11</code>: Absent ⚠️
</li>
<li>
In <code>5.13</code>: Absent ⚠️
</li>
<li>
In <code>5.15</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void devlink_linecard_notify(struct devlink_linecard *linecard, enum devlink_command cmd);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/devlink.c (ffffffff81c7e0c0)
Location: net/core/devlink.c:2111
Inline: False
Direct callers:
  - net/core/devlink.c:devlink_linecard_deactivate
  - net/core/devlink.c:devlink_linecard_activate
  - net/core/devlink.c:devlink_linecard_provision_fail
  - net/core/devlink.c:devlink_linecard_provision_clear
  - net/core/devlink.c:devlink_linecard_provision_set
  - net/core/devlink.c:devlink_linecard_destroy
  - net/core/devlink.c:devlink_linecard_create
  - net/core/devlink.c:devlink_register
  - net/core/devlink.c:devlink_nl_cmd_linecard_set_doit
  - net/core/devlink.c:devlink_nl_cmd_linecard_set_doit
  - net/core/devlink.c:devlink_nl_cmd_linecard_set_doit
  - net/core/devlink.c:devlink_linecard_type_set
  - net/core/devlink.c:devlink_linecard_type_set
```
**Symbols:**

```
ffffffff81c7e0c0-ffffffff81c7e1d6: devlink_linecard_notify (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void devlink_linecard_notify(struct devlink_linecard *linecard, enum devlink_command cmd);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/devlink.c (ffffffff81e36cd0)
Location: net/core/devlink.c:2414
Inline: False
Direct callers:
  - net/core/devlink.c:devlink_linecard_nested_dl_set
  - net/core/devlink.c:devlink_linecard_deactivate
  - net/core/devlink.c:devlink_linecard_activate
  - net/core/devlink.c:devlink_linecard_provision_fail
  - net/core/devlink.c:devlink_linecard_provision_clear
  - net/core/devlink.c:devlink_linecard_provision_set
  - net/core/devlink.c:devlink_linecard_destroy
  - net/core/devlink.c:devlink_linecard_create
  - net/core/devlink.c:devlink_notify_register
  - net/core/devlink.c:devlink_nl_cmd_linecard_set_doit
  - net/core/devlink.c:devlink_nl_cmd_linecard_set_doit
  - net/core/devlink.c:devlink_nl_cmd_linecard_set_doit
  - net/core/devlink.c:devlink_linecard_type_set
  - net/core/devlink.c:devlink_linecard_type_set
```
**Symbols:**

```
ffffffff81e36cd0-ffffffff81e36de6: devlink_linecard_notify (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void devlink_linecard_notify(struct devlink_linecard *linecard, enum devlink_command cmd);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/devlink/leftover.c (ffffffff820404e0)
Location: net/devlink/leftover.c:1786
Inline: False
Direct callers:
  - net/devlink/leftover.c:devlink_linecard_nested_dl_set
  - net/devlink/leftover.c:devlink_linecard_deactivate
  - net/devlink/leftover.c:devlink_linecard_activate
  - net/devlink/leftover.c:devlink_linecard_provision_fail
  - net/devlink/leftover.c:devlink_linecard_provision_clear
  - net/devlink/leftover.c:devlink_linecard_provision_set
  - net/devlink/leftover.c:devl_linecard_destroy
  - net/devlink/leftover.c:devl_linecard_create
  - net/devlink/leftover.c:devlink_notify_unregister
  - net/devlink/leftover.c:devlink_notify_register
  - net/devlink/leftover.c:devlink_nl_cmd_linecard_set_doit
  - net/devlink/leftover.c:devlink_nl_cmd_linecard_set_doit
  - net/devlink/leftover.c:devlink_nl_cmd_linecard_set_doit
  - net/devlink/leftover.c:devlink_linecard_type_set
  - net/devlink/leftover.c:devlink_linecard_type_set
```
**Symbols:**

```
ffffffff820404e0-ffffffff820405f7: devlink_linecard_notify (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void devlink_linecard_notify(struct devlink_linecard *linecard, enum devlink_command cmd);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/devlink/linecard.c (ffffffff82119c20)
Location: net/devlink/linecard.c:129
Inline: False
Direct callers:
  - net/devlink/linecard.c:devlink_linecard_rel_notify_cb
  - net/devlink/linecard.c:devlink_linecard_deactivate
  - net/devlink/linecard.c:devlink_linecard_activate
  - net/devlink/linecard.c:devlink_linecard_provision_fail
  - net/devlink/linecard.c:devlink_linecard_provision_clear
  - net/devlink/linecard.c:devlink_linecard_provision_set
  - net/devlink/linecard.c:devl_linecard_destroy
  - net/devlink/linecard.c:devl_linecard_create
  - net/devlink/linecard.c:devlink_nl_linecard_set_doit
  - net/devlink/linecard.c:devlink_nl_linecard_set_doit
  - net/devlink/linecard.c:devlink_nl_linecard_set_doit
  - net/devlink/linecard.c:devlink_linecard_type_set
  - net/devlink/linecard.c:devlink_linecard_type_set
  - net/devlink/linecard.c:devlink_linecards_notify_unregister
  - net/devlink/linecard.c:devlink_linecards_notify_register
```
**Symbols:**

```
ffffffff82119c20-ffffffff82119dd5: devlink_linecard_notify (STB_LOCAL)
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
No changes between <code>5.19</code> and <code>6.2</code> ✅
</li>
<li>
No changes between <code>6.2</code> and <code>6.5</code> ✅
</li>
<li>
No changes between <code>6.5</code> and <code>6.8</code> ✅
</li>
</ul>
