# Function: <code>__devlink_params_register</code>

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
int __devlink_params_register(struct devlink *devlink, unsigned int port_index, struct list_head *param_list, const struct devlink_param *params, size_t params_count, enum devlink_command reg_cmd, enum devlink_command unreg_cmd);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/core/devlink.c (0)
Location: net/core/devlink.c:6302
Inline: False
Direct callers:
  - net/core/devlink.c:devlink_port_params_register
  - net/core/devlink.c:devlink_params_register
```
**Symbols:**

```
ffffffff81950a30-ffffffff81950c8c: __devlink_params_register (STB_LOCAL)
ffffffff819525ca-ffffffff81952607: __devlink_params_register.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int __devlink_params_register(struct devlink *devlink, unsigned int port_index, struct list_head *param_list, const struct devlink_param *params, size_t params_count, enum devlink_command reg_cmd, enum devlink_command unreg_cmd);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/devlink.c (ffffffff819870f0)
Location: net/core/devlink.c:6999
Inline: False
Direct callers:
  - net/core/devlink.c:devlink_port_params_register
  - net/core/devlink.c:devlink_params_register
```
**Symbols:**

```
ffffffff819870f0-ffffffff81987359: __devlink_params_register (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int __devlink_params_register(struct devlink *devlink, unsigned int port_index, struct list_head *param_list, const struct devlink_param *params, size_t params_count, enum devlink_command reg_cmd, enum devlink_command unreg_cmd);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/devlink.c (ffffffff81a5ddd0)
Location: net/core/devlink.c:7944
Inline: False
Direct callers:
  - net/core/devlink.c:devlink_port_params_register
  - net/core/devlink.c:devlink_params_register
```
**Symbols:**

```
ffffffff81a5ddd0-ffffffff81a5e042: __devlink_params_register (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int __devlink_params_register(struct devlink *devlink, unsigned int port_index, struct list_head *param_list, const struct devlink_param *params, size_t params_count, enum devlink_command reg_cmd, enum devlink_command unreg_cmd);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/devlink.c (ffffffff81a64e90)
Location: net/core/devlink.c:8832
Inline: False
Direct callers:
  - net/core/devlink.c:devlink_port_params_register
  - net/core/devlink.c:devlink_params_register
```
**Symbols:**

```
ffffffff81a64e90-ffffffff81a65102: __devlink_params_register (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int __devlink_params_register(struct devlink *devlink, unsigned int port_index, struct list_head *param_list, const struct devlink_param *params, size_t params_count, enum devlink_command reg_cmd, enum devlink_command unreg_cmd);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/devlink.c (ffffffff81a48eb0)
Location: net/core/devlink.c:9095
Inline: False
Direct callers:
  - net/core/devlink.c:devlink_port_params_register
  - net/core/devlink.c:devlink_params_register
```
**Symbols:**

```
ffffffff81a48eb0-ffffffff81a49122: __devlink_params_register (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int __devlink_params_register(struct devlink *devlink, unsigned int port_index, struct list_head *param_list, const struct devlink_param *params, size_t params_count, enum devlink_command reg_cmd, enum devlink_command unreg_cmd);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/devlink.c (ffffffff81b002b0)
Location: net/core/devlink.c:9956
Inline: False
Direct callers:
  - net/core/devlink.c:devlink_port_params_register
  - net/core/devlink.c:devlink_params_register
```
**Symbols:**

```
ffffffff81b002b0-ffffffff81b003ac: __devlink_params_register (STB_LOCAL)
```
</details>
</li>
<li>
In <code>5.19</code>: Absent ⚠️
</li>
<li>
In <code>6.2</code>: Absent ⚠️
</li>
<li>
In <code>6.5</code>: Absent ⚠️
</li>
<li>
In <code>6.8</code>: Absent ⚠️
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: ✅</summary>

```c
int __devlink_params_register(struct devlink *devlink, unsigned int port_index, struct list_head *param_list, const struct devlink_param *params, size_t params_count, enum devlink_command reg_cmd, enum devlink_command unreg_cmd);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/devlink.c (ffff800010c2f520)
Location: net/core/devlink.c:6999
Inline: False
Direct callers:
  - net/core/devlink.c:devlink_port_params_register
  - net/core/devlink.c:devlink_params_register
```
**Symbols:**

```
ffff800010c2f520-ffff800010c2f79c: __devlink_params_register (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int __devlink_params_register(struct devlink *devlink, unsigned int port_index, struct list_head *param_list, const struct devlink_param *params, size_t params_count, enum devlink_command reg_cmd, enum devlink_command unreg_cmd);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/devlink.c (c0d46558)
Location: net/core/devlink.c:6999
Inline: False
Direct callers:
  - net/core/devlink.c:devlink_port_params_register
  - net/core/devlink.c:devlink_params_register
```
**Symbols:**

```
c0d46558-c0d467f8: __devlink_params_register (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int __devlink_params_register(struct devlink *devlink, unsigned int port_index, struct list_head *param_list, const struct devlink_param *params, size_t params_count, enum devlink_command reg_cmd, enum devlink_command unreg_cmd);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/devlink.c (c000000000d27610)
Location: net/core/devlink.c:6999
Inline: False
Direct callers:
  - net/core/devlink.c:devlink_port_params_register
  - net/core/devlink.c:devlink_params_register
```
**Symbols:**

```
c000000000d27610-c000000000d27c4c: __devlink_params_register (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int __devlink_params_register(struct devlink *devlink, unsigned int port_index, struct list_head *param_list, const struct devlink_param *params, size_t params_count, enum devlink_command reg_cmd, enum devlink_command unreg_cmd);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/devlink.c (ffffffe0007a59f4)
Location: net/core/devlink.c:6999
Inline: False
Direct callers:
  - net/core/devlink.c:devlink_port_params_register
  - net/core/devlink.c:devlink_params_register
```
**Symbols:**

```
ffffffe0007a59f4-ffffffe0007a5c0e: __devlink_params_register (STB_LOCAL)
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
int __devlink_params_register(struct devlink *devlink, unsigned int port_index, struct list_head *param_list, const struct devlink_param *params, size_t params_count, enum devlink_command reg_cmd, enum devlink_command unreg_cmd);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/devlink.c (ffffffff81926f60)
Location: net/core/devlink.c:6999
Inline: False
Direct callers:
  - net/core/devlink.c:devlink_port_params_register
  - net/core/devlink.c:devlink_params_register
```
**Symbols:**

```
ffffffff81926f60-ffffffff819271c9: __devlink_params_register (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int __devlink_params_register(struct devlink *devlink, unsigned int port_index, struct list_head *param_list, const struct devlink_param *params, size_t params_count, enum devlink_command reg_cmd, enum devlink_command unreg_cmd);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/devlink.c (ffffffff818e0d10)
Location: net/core/devlink.c:6999
Inline: False
Direct callers:
  - net/core/devlink.c:devlink_port_params_register
  - net/core/devlink.c:devlink_params_register
```
**Symbols:**

```
ffffffff818e0d10-ffffffff818e0f79: __devlink_params_register (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int __devlink_params_register(struct devlink *devlink, unsigned int port_index, struct list_head *param_list, const struct devlink_param *params, size_t params_count, enum devlink_command reg_cmd, enum devlink_command unreg_cmd);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/devlink.c (ffffffff819780f0)
Location: net/core/devlink.c:6999
Inline: False
Direct callers:
  - net/core/devlink.c:devlink_port_params_register
  - net/core/devlink.c:devlink_params_register
```
**Symbols:**

```
ffffffff819780f0-ffffffff81978359: __devlink_params_register (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int __devlink_params_register(struct devlink *devlink, unsigned int port_index, struct list_head *param_list, const struct devlink_param *params, size_t params_count, enum devlink_command reg_cmd, enum devlink_command unreg_cmd);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/devlink.c (ffffffff8199a5e0)
Location: net/core/devlink.c:6999
Inline: False
Direct callers:
  - net/core/devlink.c:devlink_port_params_register
  - net/core/devlink.c:devlink_params_register
```
**Symbols:**

```
ffffffff8199a5e0-ffffffff8199a849: __devlink_params_register (STB_LOCAL)
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
