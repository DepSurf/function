# Function: <code>devlink_reload_supported</code>

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
<summary>In <code>5.4</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/core/devlink.c (ffffffff8197b310)
Location: net/core/devlink.c:2677
Inline: True
Inline callers:
  - net/core/devlink.c:devlink_port_param_driverinit_value_get
  - net/core/devlink.c:devlink_param_driverinit_value_get
  - net/core/devlink.c:devlink_unregister
  - net/core/devlink.c:devlink_nl_cmd_reload
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
In net/core/devlink.c (ffffffff81a5dc52)
Location: net/core/devlink.c:2775
Inline: True
Inline callers:
  - net/core/devlink.c:devlink_pernet_pre_exit
  - net/core/devlink.c:devlink_port_param_driverinit_value_get
  - net/core/devlink.c:devlink_param_driverinit_value_get
  - net/core/devlink.c:devlink_unregister
  - net/core/devlink.c:devlink_nl_cmd_reload
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/core/devlink.c (ffffffff81a676fc)
Location: net/core/devlink.c:3107
Inline: True
Inline callers:
  - net/core/devlink.c:devlink_pernet_pre_exit
  - net/core/devlink.c:devlink_port_param_driverinit_value_get
  - net/core/devlink.c:devlink_param_driverinit_value_get
  - net/core/devlink.c:devlink_unregister
  - net/core/devlink.c:devlink_nl_cmd_reload
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/core/devlink.c (ffffffff81a4a5fc)
Location: net/core/devlink.c:3310
Inline: True
Inline callers:
  - net/core/devlink.c:devlink_pernet_pre_exit
  - net/core/devlink.c:devlink_port_param_driverinit_value_get
  - net/core/devlink.c:devlink_param_driverinit_value_get
  - net/core/devlink.c:devlink_unregister
  - net/core/devlink.c:devlink_nl_cmd_reload
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/core/devlink.c (ffffffff81b02818)
Location: net/core/devlink.c:3875
Inline: True
Inline callers:
  - net/core/devlink.c:devlink_pernet_pre_exit
  - net/core/devlink.c:devlink_port_param_driverinit_value_get
  - net/core/devlink.c:devlink_param_driverinit_value_get
  - net/core/devlink.c:devlink_unregister
  - net/core/devlink.c:devlink_alloc_ns
  - net/core/devlink.c:devlink_nl_cmd_reload
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/core/devlink.c (ffffffff81c73c3c)
Location: net/core/devlink.c:4390
Inline: True
Inline callers:
  - net/core/devlink.c:devlink_param_driverinit_value_get
  - net/core/devlink.c:devlink_alloc_ns
  - net/core/devlink.c:devlink_set_features
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/core/devlink.c (ffffffff81e3129c)
Location: net/core/devlink.c:4656
Inline: True
Inline callers:
  - net/core/devlink.c:devlink_param_driverinit_value_get
  - net/core/devlink.c:devlink_alloc_ns
  - net/core/devlink.c:devlink_set_features
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/devlink/leftover.c (ffffffff82033d0c)
Location: net/devlink/devl_internal.h:188
Inline: True
Inline callers:
  - net/devlink/leftover.c:devl_param_driverinit_value_get
```
```
In net/devlink/dev.c (ffffffff82044e35)
Location: net/devlink/devl_internal.h:188
Inline: True
Inline callers:
  - net/devlink/dev.c:devlink_reload_actions_valid
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/devlink/dev.c (ffffffff821046f5)
Location: net/devlink/devl_internal.h:280
Inline: True
Inline callers:
  - net/devlink/dev.c:devlink_reload_actions_valid
```
```
In net/devlink/param.c (ffffffff8210dc7c)
Location: net/devlink/devl_internal.h:280
Inline: True
Inline callers:
  - net/devlink/param.c:devl_param_driverinit_value_get
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
In net/core/devlink.c (ffff800010c22bb4)
Location: net/core/devlink.c:2677
Inline: True
Inline callers:
  - net/core/devlink.c:devlink_port_param_driverinit_value_get
  - net/core/devlink.c:devlink_param_driverinit_value_get
  - net/core/devlink.c:devlink_unregister
  - net/core/devlink.c:devlink_nl_cmd_reload
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
In net/core/devlink.c (c0d39ec0)
Location: net/core/devlink.c:2677
Inline: True
Inline callers:
  - net/core/devlink.c:devlink_port_param_driverinit_value_get
  - net/core/devlink.c:devlink_param_driverinit_value_get
  - net/core/devlink.c:devlink_unregister
  - net/core/devlink.c:devlink_nl_cmd_reload
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
In net/core/devlink.c (c000000000d153b0)
Location: net/core/devlink.c:2677
Inline: True
Inline callers:
  - net/core/devlink.c:devlink_port_param_driverinit_value_get
  - net/core/devlink.c:devlink_param_driverinit_value_get
  - net/core/devlink.c:devlink_unregister
  - net/core/devlink.c:devlink_nl_cmd_reload
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
In net/core/devlink.c (ffffffe00079b4ee)
Location: net/core/devlink.c:2677
Inline: True
Inline callers:
  - net/core/devlink.c:devlink_port_param_driverinit_value_get
  - net/core/devlink.c:devlink_param_driverinit_value_get
  - net/core/devlink.c:devlink_unregister
  - net/core/devlink.c:devlink_nl_cmd_reload
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
In net/core/devlink.c (ffffffff8191b180)
Location: net/core/devlink.c:2677
Inline: True
Inline callers:
  - net/core/devlink.c:devlink_port_param_driverinit_value_get
  - net/core/devlink.c:devlink_param_driverinit_value_get
  - net/core/devlink.c:devlink_unregister
  - net/core/devlink.c:devlink_nl_cmd_reload
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
In net/core/devlink.c (ffffffff818d4f30)
Location: net/core/devlink.c:2677
Inline: True
Inline callers:
  - net/core/devlink.c:devlink_port_param_driverinit_value_get
  - net/core/devlink.c:devlink_param_driverinit_value_get
  - net/core/devlink.c:devlink_unregister
  - net/core/devlink.c:devlink_nl_cmd_reload
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
In net/core/devlink.c (ffffffff8196c310)
Location: net/core/devlink.c:2677
Inline: True
Inline callers:
  - net/core/devlink.c:devlink_port_param_driverinit_value_get
  - net/core/devlink.c:devlink_param_driverinit_value_get
  - net/core/devlink.c:devlink_unregister
  - net/core/devlink.c:devlink_nl_cmd_reload
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
In net/core/devlink.c (ffffffff8198e790)
Location: net/core/devlink.c:2677
Inline: True
Inline callers:
  - net/core/devlink.c:devlink_port_param_driverinit_value_get
  - net/core/devlink.c:devlink_param_driverinit_value_get
  - net/core/devlink.c:devlink_unregister
  - net/core/devlink.c:devlink_nl_cmd_reload
```
</details>
</li>
</ul>

## Differences
