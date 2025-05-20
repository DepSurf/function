# Function: <code>devlink_rate_notify</code>

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
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void devlink_rate_notify(struct devlink_rate *devlink_rate, enum devlink_command cmd);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/devlink.c (ffffffff81afd5c0)
Location: net/core/devlink.c:1063
Inline: False
Direct callers:
  - net/core/devlink.c:devlink_rate_leaf_destroy
  - net/core/devlink.c:devlink_rate_leaf_create
  - net/core/devlink.c:devlink_nl_cmd_rate_del_doit
  - net/core/devlink.c:devlink_nl_cmd_rate_new_doit
  - net/core/devlink.c:devlink_nl_cmd_rate_set_doit
```
**Symbols:**

```
ffffffff81afd5c0-ffffffff81afd65c: devlink_rate_notify (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void devlink_rate_notify(struct devlink_rate *devlink_rate, enum devlink_command cmd);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/devlink.c (ffffffff81c83880)
Location: net/core/devlink.c:1288
Inline: False
Direct callers:
  - net/core/devlink.c:devl_rate_leaf_destroy
  - net/core/devlink.c:devl_rate_leaf_create
  - net/core/devlink.c:devlink_unregister
  - net/core/devlink.c:devlink_register
  - net/core/devlink.c:devlink_nl_cmd_rate_del_doit
  - net/core/devlink.c:devlink_nl_cmd_rate_new_doit
  - net/core/devlink.c:devlink_nl_cmd_rate_set_doit
```
**Symbols:**

```
ffffffff81c83880-ffffffff81c83986: devlink_rate_notify (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void devlink_rate_notify(struct devlink_rate *devlink_rate, enum devlink_command cmd);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/devlink.c (ffffffff81e3bd20)
Location: net/core/devlink.c:1514
Inline: False
Direct callers:
  - net/core/devlink.c:devl_rate_leaf_destroy
  - net/core/devlink.c:devl_rate_leaf_create
  - net/core/devlink.c:devlink_notify_unregister
  - net/core/devlink.c:devlink_notify_register
  - net/core/devlink.c:devlink_nl_cmd_rate_del_doit
  - net/core/devlink.c:devlink_nl_cmd_rate_new_doit
  - net/core/devlink.c:devlink_nl_cmd_rate_set_doit
```
**Symbols:**

```
ffffffff81e3bd20-ffffffff81e3be26: devlink_rate_notify (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void devlink_rate_notify(struct devlink_rate *devlink_rate, enum devlink_command cmd);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/devlink/leftover.c (ffffffff8203e310)
Location: net/devlink/leftover.c:981
Inline: False
Direct callers:
  - net/devlink/leftover.c:devl_rate_leaf_destroy
  - net/devlink/leftover.c:devl_rate_leaf_create
  - net/devlink/leftover.c:devlink_notify_unregister
  - net/devlink/leftover.c:devlink_notify_register
  - net/devlink/leftover.c:devlink_nl_cmd_rate_del_doit
  - net/devlink/leftover.c:devlink_nl_cmd_rate_new_doit
  - net/devlink/leftover.c:devlink_nl_cmd_rate_set_doit
```
**Symbols:**

```
ffffffff8203e310-ffffffff8203e417: devlink_rate_notify (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void devlink_rate_notify(struct devlink_rate *devlink_rate, enum devlink_command cmd);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/devlink/rate.c (ffffffff82118a80)
Location: net/devlink/rate.c:140
Inline: False
Direct callers:
  - net/devlink/rate.c:devl_rate_leaf_destroy
  - net/devlink/rate.c:devl_rate_leaf_create
  - net/devlink/rate.c:devlink_nl_rate_del_doit
  - net/devlink/rate.c:devlink_nl_rate_new_doit
  - net/devlink/rate.c:devlink_nl_rate_set_doit
  - net/devlink/rate.c:devlink_rates_notify_unregister
  - net/devlink/rate.c:devlink_rates_notify_register
```
**Symbols:**

```
ffffffff82118a80-ffffffff82118c39: devlink_rate_notify (STB_LOCAL)
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
