# Function: <code>devlink_param_cmode_is_supported</code>

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
In net/core/devlink.c (ffffffff81950ecc)
Location: net/core/devlink.c:2908
Inline: True
Inline callers:
  - net/core/devlink.c:__devlink_param_driverinit_value_set
  - net/core/devlink.c:__devlink_param_driverinit_value_get
  - net/core/devlink.c:__devlink_nl_cmd_param_set_doit
  - net/core/devlink.c:devlink_nl_param_fill
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
In net/core/devlink.c (ffffffff8198759c)
Location: net/core/devlink.c:2940
Inline: True
Inline callers:
  - net/core/devlink.c:__devlink_param_driverinit_value_set
  - net/core/devlink.c:__devlink_param_driverinit_value_get
  - net/core/devlink.c:__devlink_nl_cmd_param_set_doit
  - net/core/devlink.c:devlink_nl_param_fill
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
In net/core/devlink.c (ffffffff81a5d73c)
Location: net/core/devlink.c:3073
Inline: True
Inline callers:
  - net/core/devlink.c:__devlink_param_driverinit_value_set
  - net/core/devlink.c:__devlink_param_driverinit_value_get
  - net/core/devlink.c:__devlink_nl_cmd_param_set_doit
  - net/core/devlink.c:devlink_nl_param_fill
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
In net/core/devlink.c (ffffffff81a64b2c)
Location: net/core/devlink.c:3618
Inline: True
Inline callers:
  - net/core/devlink.c:__devlink_param_driverinit_value_set
  - net/core/devlink.c:__devlink_param_driverinit_value_get
  - net/core/devlink.c:__devlink_nl_cmd_param_set_doit
  - net/core/devlink.c:devlink_nl_param_fill
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
In net/core/devlink.c (ffffffff81a48b4c)
Location: net/core/devlink.c:3821
Inline: True
Inline callers:
  - net/core/devlink.c:__devlink_param_driverinit_value_set
  - net/core/devlink.c:__devlink_param_driverinit_value_get
  - net/core/devlink.c:__devlink_nl_cmd_param_set_doit
  - net/core/devlink.c:devlink_nl_param_fill
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
In net/core/devlink.c (ffffffff81affd8c)
Location: net/core/devlink.c:4406
Inline: True
Inline callers:
  - net/core/devlink.c:__devlink_param_driverinit_value_set
  - net/core/devlink.c:__devlink_param_driverinit_value_get
  - net/core/devlink.c:__devlink_nl_cmd_param_set_doit
  - net/core/devlink.c:devlink_nl_param_fill
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
In net/core/devlink.c (ffffffff81c73292)
Location: net/core/devlink.c:4936
Inline: True
Inline callers:
  - net/core/devlink.c:devlink_param_driverinit_value_set
  - net/core/devlink.c:devlink_param_driverinit_value_get
  - net/core/devlink.c:__devlink_nl_cmd_param_set_doit
  - net/core/devlink.c:devlink_nl_param_fill
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
bool devlink_param_cmode_is_supported(const struct devlink_param *param, enum devlink_param_cmode cmode);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/devlink.c (ffffffff81e31122)
Location: net/core/devlink.c:5460
Inline: True
Inline callers:
  - net/core/devlink.c:devlink_param_driverinit_value_set
  - net/core/devlink.c:devlink_param_driverinit_value_get
```
**Symbols:**

```
ffffffff81e2a970-ffffffff81e2a98d: devlink_param_cmode_is_supported (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
bool devlink_param_cmode_is_supported(const struct devlink_param *param, enum devlink_param_cmode cmode);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/devlink/leftover.c (ffffffff82041acc)
Location: net/devlink/leftover.c:3939
Inline: True
Inline callers:
  - net/devlink/leftover.c:devlink_params_driverinit_load_new
  - net/devlink/leftover.c:devl_param_driverinit_value_set
  - net/devlink/leftover.c:devl_param_driverinit_value_get
```
**Symbols:**

```
ffffffff8202e5b0-ffffffff8202e5cd: devlink_param_cmode_is_supported (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
bool devlink_param_cmode_is_supported(const struct devlink_param *param, enum devlink_param_cmode cmode);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/devlink/param.c (ffffffff8210f2cc)
Location: net/devlink/param.c:144
Inline: True
Inline callers:
  - net/devlink/param.c:devlink_params_driverinit_load_new
  - net/devlink/param.c:devl_param_driverinit_value_set
  - net/devlink/param.c:devl_param_driverinit_value_get
```
**Symbols:**

```
ffffffff8210d890-ffffffff8210d8ad: devlink_param_cmode_is_supported (STB_LOCAL)
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
In net/core/devlink.c (ffff800010c2fab0)
Location: net/core/devlink.c:2940
Inline: True
Inline callers:
  - net/core/devlink.c:__devlink_param_driverinit_value_set
  - net/core/devlink.c:__devlink_param_driverinit_value_get
  - net/core/devlink.c:__devlink_nl_cmd_param_set_doit
  - net/core/devlink.c:devlink_nl_param_fill
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
In net/core/devlink.c (c0d46a84)
Location: net/core/devlink.c:2940
Inline: True
Inline callers:
  - net/core/devlink.c:__devlink_param_driverinit_value_set
  - net/core/devlink.c:__devlink_param_driverinit_value_get
  - net/core/devlink.c:__devlink_nl_cmd_param_set_doit
  - net/core/devlink.c:devlink_nl_param_fill
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
In net/core/devlink.c (c000000000d28004)
Location: net/core/devlink.c:2940
Inline: True
Inline callers:
  - net/core/devlink.c:__devlink_param_driverinit_value_set
  - net/core/devlink.c:__devlink_param_driverinit_value_get
  - net/core/devlink.c:__devlink_nl_cmd_param_set_doit
  - net/core/devlink.c:devlink_nl_param_fill
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
In net/core/devlink.c (ffffffe0007a5e8c)
Location: net/core/devlink.c:2940
Inline: True
Inline callers:
  - net/core/devlink.c:__devlink_param_driverinit_value_set
  - net/core/devlink.c:__devlink_param_driverinit_value_get
  - net/core/devlink.c:__devlink_nl_cmd_param_set_doit
  - net/core/devlink.c:devlink_nl_param_fill
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
In net/core/devlink.c (ffffffff8192740c)
Location: net/core/devlink.c:2940
Inline: True
Inline callers:
  - net/core/devlink.c:__devlink_param_driverinit_value_set
  - net/core/devlink.c:__devlink_param_driverinit_value_get
  - net/core/devlink.c:__devlink_nl_cmd_param_set_doit
  - net/core/devlink.c:devlink_nl_param_fill
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
In net/core/devlink.c (ffffffff818e11bc)
Location: net/core/devlink.c:2940
Inline: True
Inline callers:
  - net/core/devlink.c:__devlink_param_driverinit_value_set
  - net/core/devlink.c:__devlink_param_driverinit_value_get
  - net/core/devlink.c:__devlink_nl_cmd_param_set_doit
  - net/core/devlink.c:devlink_nl_param_fill
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
In net/core/devlink.c (ffffffff8197859c)
Location: net/core/devlink.c:2940
Inline: True
Inline callers:
  - net/core/devlink.c:__devlink_param_driverinit_value_set
  - net/core/devlink.c:__devlink_param_driverinit_value_get
  - net/core/devlink.c:__devlink_nl_cmd_param_set_doit
  - net/core/devlink.c:devlink_nl_param_fill
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
In net/core/devlink.c (ffffffff8199aa8c)
Location: net/core/devlink.c:2940
Inline: True
Inline callers:
  - net/core/devlink.c:__devlink_param_driverinit_value_set
  - net/core/devlink.c:__devlink_param_driverinit_value_get
  - net/core/devlink.c:__devlink_nl_cmd_param_set_doit
  - net/core/devlink.c:devlink_nl_param_fill
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>6.2</code> and <code>6.5</code> ✅
</li>
<li>
No changes between <code>6.5</code> and <code>6.8</code> ✅
</li>
</ul>
