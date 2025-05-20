# Function: <code>devlink_param_notify</code>

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
void devlink_param_notify(struct devlink *devlink, unsigned int port_index, struct devlink_param_item *param_item, enum devlink_command cmd);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/core/devlink.c (0)
Location: net/core/devlink.c:3093
Inline: False
Direct callers:
  - net/core/devlink.c:devlink_port_param_value_changed
  - net/core/devlink.c:devlink_param_value_changed
  - net/core/devlink.c:__devlink_param_driverinit_value_set
  - net/core/devlink.c:devlink_params_unpublish
  - net/core/devlink.c:devlink_params_publish
  - net/core/devlink.c:__devlink_params_register
  - net/core/devlink.c:__devlink_nl_cmd_param_set_doit
```
**Symbols:**

```
ffffffff819504b0-ffffffff8195057d: devlink_param_notify (STB_LOCAL)
ffffffff81952580-ffffffff81952593: devlink_param_notify.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void devlink_param_notify(struct devlink *devlink, unsigned int port_index, struct devlink_param_item *param_item, enum devlink_command cmd);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/devlink.c (ffffffff81986b40)
Location: net/core/devlink.c:3125
Inline: False
Direct callers:
  - net/core/devlink.c:devlink_port_param_value_changed
  - net/core/devlink.c:devlink_param_value_changed
  - net/core/devlink.c:devlink_param_value_changed
  - net/core/devlink.c:__devlink_param_driverinit_value_set
  - net/core/devlink.c:devlink_params_unpublish
  - net/core/devlink.c:devlink_params_publish
  - net/core/devlink.c:__devlink_params_register
  - net/core/devlink.c:__devlink_nl_cmd_param_set_doit
```
**Symbols:**

```
ffffffff81986b40-ffffffff81986c14: devlink_param_notify (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void devlink_param_notify(struct devlink *devlink, unsigned int port_index, struct devlink_param_item *param_item, enum devlink_command cmd);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/devlink.c (ffffffff81a5d200)
Location: net/core/devlink.c:3258
Inline: False
Direct callers:
  - net/core/devlink.c:devlink_port_param_value_changed
  - net/core/devlink.c:devlink_param_value_changed
  - net/core/devlink.c:devlink_param_value_changed
  - net/core/devlink.c:__devlink_param_driverinit_value_set
  - net/core/devlink.c:devlink_params_unpublish
  - net/core/devlink.c:devlink_params_publish
  - net/core/devlink.c:__devlink_params_register
  - net/core/devlink.c:__devlink_nl_cmd_param_set_doit
```
**Symbols:**

```
ffffffff81a5d200-ffffffff81a5d2d4: devlink_param_notify (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void devlink_param_notify(struct devlink *devlink, unsigned int port_index, struct devlink_param_item *param_item, enum devlink_command cmd);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/devlink.c (ffffffff81a645f0)
Location: net/core/devlink.c:3803
Inline: False
Direct callers:
  - net/core/devlink.c:devlink_port_param_value_changed
  - net/core/devlink.c:devlink_param_value_changed
  - net/core/devlink.c:devlink_param_value_changed
  - net/core/devlink.c:__devlink_param_driverinit_value_set
  - net/core/devlink.c:devlink_params_unpublish
  - net/core/devlink.c:devlink_params_publish
  - net/core/devlink.c:__devlink_params_register
  - net/core/devlink.c:__devlink_nl_cmd_param_set_doit
  - net/core/devlink.c:devlink_reload
  - net/core/devlink.c:devlink_reload
```
**Symbols:**

```
ffffffff81a645f0-ffffffff81a646c3: devlink_param_notify (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void devlink_param_notify(struct devlink *devlink, unsigned int port_index, struct devlink_param_item *param_item, enum devlink_command cmd);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/devlink.c (ffffffff81a48610)
Location: net/core/devlink.c:4006
Inline: False
Direct callers:
  - net/core/devlink.c:devlink_port_param_value_changed
  - net/core/devlink.c:devlink_param_value_changed
  - net/core/devlink.c:devlink_param_value_changed
  - net/core/devlink.c:__devlink_param_driverinit_value_set
  - net/core/devlink.c:devlink_params_unpublish
  - net/core/devlink.c:devlink_params_publish
  - net/core/devlink.c:__devlink_params_register
  - net/core/devlink.c:__devlink_nl_cmd_param_set_doit
  - net/core/devlink.c:devlink_reload
  - net/core/devlink.c:devlink_reload
```
**Symbols:**

```
ffffffff81a48610-ffffffff81a486e3: devlink_param_notify (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void devlink_param_notify(struct devlink *devlink, unsigned int port_index, struct devlink_param_item *param_item, enum devlink_command cmd);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/devlink.c (ffffffff81aff790)
Location: net/core/devlink.c:4591
Inline: False
Direct callers:
  - net/core/devlink.c:devlink_port_param_value_changed
  - net/core/devlink.c:devlink_param_value_changed
  - net/core/devlink.c:devlink_param_value_changed
  - net/core/devlink.c:__devlink_param_driverinit_value_set
  - net/core/devlink.c:devlink_param_unpublish
  - net/core/devlink.c:devlink_param_publish
  - net/core/devlink.c:devlink_params_unpublish
  - net/core/devlink.c:devlink_params_publish
  - net/core/devlink.c:devlink_param_register_one
  - net/core/devlink.c:__devlink_nl_cmd_param_set_doit
  - net/core/devlink.c:devlink_reload
  - net/core/devlink.c:devlink_reload
```
**Symbols:**

```
ffffffff81aff790-ffffffff81aff863: devlink_param_notify (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void devlink_param_notify(struct devlink *devlink, unsigned int port_index, struct devlink_param_item *param_item, enum devlink_command cmd);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/devlink.c (ffffffff81c82d30)
Location: net/core/devlink.c:5119
Inline: False
Direct callers:
  - net/core/devlink.c:devlink_param_value_changed
  - net/core/devlink.c:devlink_param_value_changed
  - net/core/devlink.c:devlink_unregister
  - net/core/devlink.c:devlink_register
  - net/core/devlink.c:__devlink_nl_cmd_param_set_doit
  - net/core/devlink.c:devlink_reload
  - net/core/devlink.c:devlink_reload
```
**Symbols:**

```
ffffffff81c82d30-ffffffff81c82e4b: devlink_param_notify (STB_LOCAL)
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
In net/core/devlink.c (ffffffff81e3b270)
Location: net/core/devlink.c:5643
Inline: True
Direct callers:
  - net/core/devlink.c:devlink_param_value_changed
  - net/core/devlink.c:devlink_param_value_changed
  - net/core/devlink.c:devlink_notify_unregister
  - net/core/devlink.c:devlink_notify_register
  - net/core/devlink.c:devlink_reload
  - net/core/devlink.c:devlink_reload
```
**Symbols:**

```
ffffffff81e3b270-ffffffff81e3b36b: devlink_param_notify.constprop.0 (STB_LOCAL)
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
In net/devlink/leftover.c (ffffffff8203b140)
Location: net/devlink/leftover.c:4125
Inline: True
Direct callers:
  - net/devlink/leftover.c:devl_param_value_changed
  - net/devlink/leftover.c:devl_param_driverinit_value_set
  - net/devlink/leftover.c:devl_params_register
  - net/devlink/leftover.c:devlink_param_unregister
  - net/devlink/leftover.c:devlink_notify_unregister
  - net/devlink/leftover.c:devlink_notify_register
```
**Symbols:**

```
ffffffff8203b140-ffffffff8203b25a: devlink_param_notify.constprop.0 (STB_LOCAL)
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
In net/devlink/param.c (ffffffff8210e310)
Location: net/devlink/param.c:330
Inline: True
Direct callers:
  - net/devlink/param.c:devl_param_value_changed
  - net/devlink/param.c:devl_param_driverinit_value_set
  - net/devlink/param.c:devl_params_register
  - net/devlink/param.c:devlink_param_unregister
  - net/devlink/param.c:devlink_params_notify
```
**Symbols:**

```
ffffffff8210e310-ffffffff8210e4c6: devlink_param_notify.constprop.0 (STB_LOCAL)
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
void devlink_param_notify(struct devlink *devlink, unsigned int port_index, struct devlink_param_item *param_item, enum devlink_command cmd);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/devlink.c (ffff800010c2efb8)
Location: net/core/devlink.c:3125
Inline: False
Direct callers:
  - net/core/devlink.c:devlink_port_param_value_changed
  - net/core/devlink.c:devlink_port_param_value_changed
  - net/core/devlink.c:devlink_param_value_changed
  - net/core/devlink.c:devlink_param_value_changed
  - net/core/devlink.c:__devlink_param_driverinit_value_set
  - net/core/devlink.c:devlink_params_unpublish
  - net/core/devlink.c:devlink_params_publish
  - net/core/devlink.c:__devlink_params_register
  - net/core/devlink.c:__devlink_nl_cmd_param_set_doit
```
**Symbols:**

```
ffff800010c2efb8-ffff800010c2f0a8: devlink_param_notify (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void devlink_param_notify(struct devlink *devlink, unsigned int port_index, struct devlink_param_item *param_item, enum devlink_command cmd);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/devlink.c (c0d45fb4)
Location: net/core/devlink.c:3125
Inline: False
Direct callers:
  - net/core/devlink.c:devlink_port_param_value_changed
  - net/core/devlink.c:devlink_param_value_changed
  - net/core/devlink.c:__devlink_param_driverinit_value_set
  - net/core/devlink.c:devlink_params_unpublish
  - net/core/devlink.c:devlink_params_publish
  - net/core/devlink.c:__devlink_params_register
  - net/core/devlink.c:devlink_param_unregister_one
  - net/core/devlink.c:__devlink_nl_cmd_param_set_doit
```
**Symbols:**

```
c0d45fb4-c0d460d4: devlink_param_notify (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void devlink_param_notify(struct devlink *devlink, unsigned int port_index, struct devlink_param_item *param_item, enum devlink_command cmd);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/devlink.c (c000000000d26e80)
Location: net/core/devlink.c:3125
Inline: False
Direct callers:
  - net/core/devlink.c:devlink_port_param_value_changed
  - net/core/devlink.c:devlink_port_param_value_changed
  - net/core/devlink.c:devlink_param_value_changed
  - net/core/devlink.c:devlink_param_value_changed
  - net/core/devlink.c:__devlink_param_driverinit_value_set
  - net/core/devlink.c:devlink_params_unpublish
  - net/core/devlink.c:devlink_params_publish
  - net/core/devlink.c:__devlink_params_register
  - net/core/devlink.c:__devlink_nl_cmd_param_set_doit
```
**Symbols:**

```
c000000000d26e80-c000000000d26fb8: devlink_param_notify (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void devlink_param_notify(struct devlink *devlink, unsigned int port_index, struct devlink_param_item *param_item, enum devlink_command cmd);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/devlink.c (ffffffe0007a5608)
Location: net/core/devlink.c:3125
Inline: False
Direct callers:
  - net/core/devlink.c:devlink_port_param_value_changed
  - net/core/devlink.c:devlink_param_value_changed
  - net/core/devlink.c:__devlink_param_driverinit_value_set
  - net/core/devlink.c:devlink_params_unpublish
  - net/core/devlink.c:devlink_params_publish
  - net/core/devlink.c:__devlink_params_register
  - net/core/devlink.c:__devlink_nl_cmd_param_set_doit
```
**Symbols:**

```
ffffffe0007a5608-ffffffe0007a56c2: devlink_param_notify (STB_LOCAL)
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
void devlink_param_notify(struct devlink *devlink, unsigned int port_index, struct devlink_param_item *param_item, enum devlink_command cmd);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/devlink.c (ffffffff819269b0)
Location: net/core/devlink.c:3125
Inline: False
Direct callers:
  - net/core/devlink.c:devlink_port_param_value_changed
  - net/core/devlink.c:devlink_param_value_changed
  - net/core/devlink.c:devlink_param_value_changed
  - net/core/devlink.c:__devlink_param_driverinit_value_set
  - net/core/devlink.c:devlink_params_unpublish
  - net/core/devlink.c:devlink_params_publish
  - net/core/devlink.c:__devlink_params_register
  - net/core/devlink.c:__devlink_nl_cmd_param_set_doit
```
**Symbols:**

```
ffffffff819269b0-ffffffff81926a84: devlink_param_notify (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void devlink_param_notify(struct devlink *devlink, unsigned int port_index, struct devlink_param_item *param_item, enum devlink_command cmd);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/devlink.c (ffffffff818e0760)
Location: net/core/devlink.c:3125
Inline: False
Direct callers:
  - net/core/devlink.c:devlink_port_param_value_changed
  - net/core/devlink.c:devlink_param_value_changed
  - net/core/devlink.c:devlink_param_value_changed
  - net/core/devlink.c:__devlink_param_driverinit_value_set
  - net/core/devlink.c:devlink_params_unpublish
  - net/core/devlink.c:devlink_params_publish
  - net/core/devlink.c:__devlink_params_register
  - net/core/devlink.c:__devlink_nl_cmd_param_set_doit
```
**Symbols:**

```
ffffffff818e0760-ffffffff818e0834: devlink_param_notify (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void devlink_param_notify(struct devlink *devlink, unsigned int port_index, struct devlink_param_item *param_item, enum devlink_command cmd);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/devlink.c (ffffffff81977b40)
Location: net/core/devlink.c:3125
Inline: False
Direct callers:
  - net/core/devlink.c:devlink_port_param_value_changed
  - net/core/devlink.c:devlink_param_value_changed
  - net/core/devlink.c:devlink_param_value_changed
  - net/core/devlink.c:__devlink_param_driverinit_value_set
  - net/core/devlink.c:devlink_params_unpublish
  - net/core/devlink.c:devlink_params_publish
  - net/core/devlink.c:__devlink_params_register
  - net/core/devlink.c:__devlink_nl_cmd_param_set_doit
```
**Symbols:**

```
ffffffff81977b40-ffffffff81977c14: devlink_param_notify (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void devlink_param_notify(struct devlink *devlink, unsigned int port_index, struct devlink_param_item *param_item, enum devlink_command cmd);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/devlink.c (ffffffff8199a030)
Location: net/core/devlink.c:3125
Inline: False
Direct callers:
  - net/core/devlink.c:devlink_port_param_value_changed
  - net/core/devlink.c:devlink_param_value_changed
  - net/core/devlink.c:devlink_param_value_changed
  - net/core/devlink.c:__devlink_param_driverinit_value_set
  - net/core/devlink.c:devlink_params_unpublish
  - net/core/devlink.c:devlink_params_publish
  - net/core/devlink.c:__devlink_params_register
  - net/core/devlink.c:__devlink_nl_cmd_param_set_doit
```
**Symbols:**

```
ffffffff8199a030-ffffffff8199a104: devlink_param_notify (STB_LOCAL)
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
