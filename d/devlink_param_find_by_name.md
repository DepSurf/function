# Function: <code>devlink_param_find_by_name</code>

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
<summary>In <code>5.3</code>: ✅</summary>

```c
struct devlink_param_item *devlink_param_find_by_name(struct list_head *param_list, const char *param_name);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/devlink.c (ffffffff81946c70)
Location: net/core/devlink.c:2885
Inline: False
Direct callers:
  - net/core/devlink.c:__devlink_params_register
  - net/core/devlink.c:devlink_nl_cmd_port_param_get_doit
  - net/core/devlink.c:__devlink_nl_cmd_param_set_doit
  - net/core/devlink.c:devlink_nl_cmd_param_get_doit
```
**Symbols:**

```
ffffffff81946c70-ffffffff81946cc3: devlink_param_find_by_name (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
struct devlink_param_item *devlink_param_find_by_name(struct list_head *param_list, const char *param_name);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/devlink.c (ffffffff8197b890)
Location: net/core/devlink.c:2917
Inline: False
Direct callers:
  - net/core/devlink.c:__devlink_params_register
  - net/core/devlink.c:devlink_nl_cmd_port_param_get_doit
  - net/core/devlink.c:__devlink_nl_cmd_param_set_doit
  - net/core/devlink.c:devlink_nl_cmd_param_get_doit
```
**Symbols:**

```
ffffffff8197b890-ffffffff8197b8e3: devlink_param_find_by_name (STB_LOCAL)
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
In net/core/devlink.c (ffffffff81a5de8c)
Location: net/core/devlink.c:3050
Inline: True
Inline callers:
  - net/core/devlink.c:__devlink_params_register
  - net/core/devlink.c:devlink_nl_cmd_port_param_get_doit
  - net/core/devlink.c:__devlink_nl_cmd_param_set_doit
  - net/core/devlink.c:devlink_nl_cmd_param_get_doit
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
In net/core/devlink.c (ffffffff81a64f4c)
Location: net/core/devlink.c:3595
Inline: True
Inline callers:
  - net/core/devlink.c:__devlink_params_register
  - net/core/devlink.c:devlink_nl_cmd_port_param_get_doit
  - net/core/devlink.c:__devlink_nl_cmd_param_set_doit
  - net/core/devlink.c:devlink_nl_cmd_param_get_doit
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
In net/core/devlink.c (ffffffff81a48f6c)
Location: net/core/devlink.c:3798
Inline: True
Inline callers:
  - net/core/devlink.c:__devlink_params_register
  - net/core/devlink.c:devlink_nl_cmd_port_param_get_doit
  - net/core/devlink.c:__devlink_nl_cmd_param_set_doit
  - net/core/devlink.c:devlink_nl_cmd_param_get_doit
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
In net/core/devlink.c (ffffffff81b0051d)
Location: net/core/devlink.c:4383
Inline: True
Inline callers:
  - net/core/devlink.c:devlink_nl_cmd_port_param_get_doit
  - net/core/devlink.c:devlink_param_register_one
  - net/core/devlink.c:__devlink_nl_cmd_param_set_doit
  - net/core/devlink.c:devlink_nl_cmd_param_get_doit
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
In net/core/devlink.c (ffffffff81c770d4)
Location: net/core/devlink.c:4913
Inline: True
Inline callers:
  - net/core/devlink.c:devlink_param_unregister
  - net/core/devlink.c:devlink_param_register
  - net/core/devlink.c:devlink_nl_cmd_port_param_get_doit
  - net/core/devlink.c:__devlink_nl_cmd_param_set_doit
  - net/core/devlink.c:devlink_nl_cmd_param_get_doit
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
In net/core/devlink.c (ffffffff81e2f964)
Location: net/core/devlink.c:5437
Inline: True
Inline callers:
  - net/core/devlink.c:devlink_param_unregister
  - net/core/devlink.c:devlink_param_register
  - net/core/devlink.c:devlink_nl_cmd_param_get_doit
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
struct devlink_param_item *devlink_param_find_by_name(struct xarray *params, const char *param_name);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/devlink/leftover.c (ffffffff8202f800)
Location: net/devlink/leftover.c:3920
Inline: False
Direct callers:
  - net/devlink/leftover.c:devl_params_register
  - net/devlink/leftover.c:devl_params_register
  - net/devlink/leftover.c:devlink_nl_cmd_param_get_doit
```
**Symbols:**

```
ffffffff8202f800-ffffffff8202f8b4: devlink_param_find_by_name (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
struct devlink_param_item *devlink_param_find_by_name(struct xarray *params, const char *param_name);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/devlink/param.c (ffffffff8210d8c0)
Location: net/devlink/param.c:125
Inline: False
Direct callers:
  - net/devlink/param.c:devl_params_register
  - net/devlink/param.c:devl_params_register
  - net/devlink/param.c:devlink_nl_param_get_doit
```
**Symbols:**

```
ffffffff8210d8c0-ffffffff8210d974: devlink_param_find_by_name (STB_LOCAL)
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
struct devlink_param_item *devlink_param_find_by_name(struct list_head *param_list, const char *param_name);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/devlink.c (ffff800010c23200)
Location: net/core/devlink.c:2917
Inline: False
Direct callers:
  - net/core/devlink.c:__devlink_params_register
  - net/core/devlink.c:__devlink_params_register
  - net/core/devlink.c:devlink_nl_cmd_port_param_get_doit
  - net/core/devlink.c:__devlink_nl_cmd_param_set_doit
  - net/core/devlink.c:devlink_nl_cmd_param_get_doit
```
**Symbols:**

```
ffff800010c23200-ffff800010c2327c: devlink_param_find_by_name (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
struct devlink_param_item *devlink_param_find_by_name(struct list_head *param_list, const char *param_name);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/devlink.c (c0d3a80c)
Location: net/core/devlink.c:2917
Inline: False
Direct callers:
  - net/core/devlink.c:__devlink_params_register
  - net/core/devlink.c:devlink_nl_cmd_port_param_get_doit
  - net/core/devlink.c:devlink_param_unregister_one
  - net/core/devlink.c:__devlink_nl_cmd_param_set_doit
  - net/core/devlink.c:devlink_nl_cmd_param_get_doit
```
**Symbols:**

```
c0d3a80c-c0d3a870: devlink_param_find_by_name (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
struct devlink_param_item *devlink_param_find_by_name(struct list_head *param_list, const char *param_name);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/devlink.c (c000000000d16630)
Location: net/core/devlink.c:2917
Inline: False
Direct callers:
  - net/core/devlink.c:__devlink_params_register
  - net/core/devlink.c:devlink_nl_cmd_port_param_get_doit
  - net/core/devlink.c:__devlink_nl_cmd_param_set_doit
  - net/core/devlink.c:devlink_nl_cmd_param_get_doit
```
**Symbols:**

```
c000000000d16630-c000000000d16870: devlink_param_find_by_name (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
struct devlink_param_item *devlink_param_find_by_name(struct list_head *param_list, const char *param_name);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/devlink.c (ffffffe00079ba9a)
Location: net/core/devlink.c:2917
Inline: False
Direct callers:
  - net/core/devlink.c:__devlink_params_register
  - net/core/devlink.c:__devlink_params_register
  - net/core/devlink.c:devlink_nl_cmd_port_param_get_doit
  - net/core/devlink.c:__devlink_nl_cmd_param_set_doit
  - net/core/devlink.c:devlink_nl_cmd_param_get_doit
```
**Symbols:**

```
ffffffe00079ba9a-ffffffe00079baf8: devlink_param_find_by_name (STB_LOCAL)
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
struct devlink_param_item *devlink_param_find_by_name(struct list_head *param_list, const char *param_name);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/devlink.c (ffffffff8191b700)
Location: net/core/devlink.c:2917
Inline: False
Direct callers:
  - net/core/devlink.c:__devlink_params_register
  - net/core/devlink.c:devlink_nl_cmd_port_param_get_doit
  - net/core/devlink.c:__devlink_nl_cmd_param_set_doit
  - net/core/devlink.c:devlink_nl_cmd_param_get_doit
```
**Symbols:**

```
ffffffff8191b700-ffffffff8191b753: devlink_param_find_by_name (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
struct devlink_param_item *devlink_param_find_by_name(struct list_head *param_list, const char *param_name);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/devlink.c (ffffffff818d54b0)
Location: net/core/devlink.c:2917
Inline: False
Direct callers:
  - net/core/devlink.c:__devlink_params_register
  - net/core/devlink.c:devlink_nl_cmd_port_param_get_doit
  - net/core/devlink.c:__devlink_nl_cmd_param_set_doit
  - net/core/devlink.c:devlink_nl_cmd_param_get_doit
```
**Symbols:**

```
ffffffff818d54b0-ffffffff818d5503: devlink_param_find_by_name (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
struct devlink_param_item *devlink_param_find_by_name(struct list_head *param_list, const char *param_name);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/devlink.c (ffffffff8196c890)
Location: net/core/devlink.c:2917
Inline: False
Direct callers:
  - net/core/devlink.c:__devlink_params_register
  - net/core/devlink.c:devlink_nl_cmd_port_param_get_doit
  - net/core/devlink.c:__devlink_nl_cmd_param_set_doit
  - net/core/devlink.c:devlink_nl_cmd_param_get_doit
```
**Symbols:**

```
ffffffff8196c890-ffffffff8196c8e3: devlink_param_find_by_name (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
struct devlink_param_item *devlink_param_find_by_name(struct list_head *param_list, const char *param_name);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/devlink.c (ffffffff8198ed10)
Location: net/core/devlink.c:2917
Inline: False
Direct callers:
  - net/core/devlink.c:__devlink_params_register
  - net/core/devlink.c:devlink_nl_cmd_port_param_get_doit
  - net/core/devlink.c:__devlink_nl_cmd_param_set_doit
  - net/core/devlink.c:devlink_nl_cmd_param_get_doit
```
**Symbols:**

```
ffffffff8198ed10-ffffffff8198ed63: devlink_param_find_by_name (STB_LOCAL)
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
