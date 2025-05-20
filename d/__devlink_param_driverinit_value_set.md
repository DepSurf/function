# Function: <code>__devlink_param_driverinit_value_set</code>

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
int __devlink_param_driverinit_value_set(struct devlink *devlink, unsigned int port_index, struct list_head *param_list, u32 param_id, union devlink_param_value init_val, enum devlink_command cmd);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/core/devlink.c (0)
Location: net/core/devlink.c:6501
Inline: False
Direct callers:
  - net/core/devlink.c:devlink_port_param_driverinit_value_set
  - net/core/devlink.c:devlink_param_driverinit_value_set
```
**Symbols:**

```
ffffffff81950e90-ffffffff81950fff: __devlink_param_driverinit_value_set (STB_LOCAL)
ffffffff81952607-ffffffff8195261f: __devlink_param_driverinit_value_set.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
int __devlink_param_driverinit_value_set(struct devlink *devlink, unsigned int port_index, struct list_head *param_list, u32 param_id, union devlink_param_value init_val, enum devlink_command cmd);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/core/devlink.c (0)
Location: net/core/devlink.c:7198
Inline: False
Direct callers:
  - net/core/devlink.c:devlink_port_param_driverinit_value_set
  - net/core/devlink.c:devlink_param_driverinit_value_set
```
**Symbols:**

```
ffffffff81987560-ffffffff819876cf: __devlink_param_driverinit_value_set (STB_LOCAL)
ffffffff819889d9-ffffffff819889f1: __devlink_param_driverinit_value_set.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
int __devlink_param_driverinit_value_set(struct devlink *devlink, unsigned int port_index, struct list_head *param_list, u32 param_id, union devlink_param_value init_val, enum devlink_command cmd);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/core/devlink.c (0)
Location: net/core/devlink.c:8143
Inline: False
Direct callers:
  - net/core/devlink.c:devlink_port_param_driverinit_value_set
  - net/core/devlink.c:devlink_param_driverinit_value_set
```
**Symbols:**

```
ffffffff81a5d700-ffffffff81a5d86f: __devlink_param_driverinit_value_set (STB_LOCAL)
ffffffff81a6063f-ffffffff81a60657: __devlink_param_driverinit_value_set.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
int __devlink_param_driverinit_value_set(struct devlink *devlink, unsigned int port_index, struct list_head *param_list, u32 param_id, union devlink_param_value init_val, enum devlink_command cmd);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/core/devlink.c (0)
Location: net/core/devlink.c:9031
Inline: False
Direct callers:
  - net/core/devlink.c:devlink_port_param_driverinit_value_set
  - net/core/devlink.c:devlink_param_driverinit_value_set
```
**Symbols:**

```
ffffffff81a64af0-ffffffff81a64c5f: __devlink_param_driverinit_value_set (STB_LOCAL)
ffffffff81c31f83-ffffffff81c31f9b: __devlink_param_driverinit_value_set.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
int __devlink_param_driverinit_value_set(struct devlink *devlink, unsigned int port_index, struct list_head *param_list, u32 param_id, union devlink_param_value init_val, enum devlink_command cmd);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/core/devlink.c (0)
Location: net/core/devlink.c:9294
Inline: False
Direct callers:
  - net/core/devlink.c:devlink_port_param_driverinit_value_set
  - net/core/devlink.c:devlink_param_driverinit_value_set
```
**Symbols:**

```
ffffffff81a48b10-ffffffff81a48c7f: __devlink_param_driverinit_value_set (STB_LOCAL)
ffffffff81c2429d-ffffffff81c242b5: __devlink_param_driverinit_value_set.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int __devlink_param_driverinit_value_set(struct devlink *devlink, unsigned int port_index, struct list_head *param_list, u32 param_id, union devlink_param_value init_val, enum devlink_command cmd);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/core/devlink.c (0)
Location: net/core/devlink.c:10236
Inline: False
Direct callers:
  - net/core/devlink.c:devlink_port_param_driverinit_value_set
  - net/core/devlink.c:devlink_param_driverinit_value_set
```
**Symbols:**

```
ffffffff81affd50-ffffffff81affebf: __devlink_param_driverinit_value_set (STB_LOCAL)
ffffffff81d389ae-ffffffff81d389c6: __devlink_param_driverinit_value_set.cold (STB_LOCAL)
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
int __devlink_param_driverinit_value_set(struct devlink *devlink, unsigned int port_index, struct list_head *param_list, u32 param_id, union devlink_param_value init_val, enum devlink_command cmd);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/devlink.c (ffff800010c2fa48)
Location: net/core/devlink.c:7198
Inline: False
Direct callers:
  - net/core/devlink.c:devlink_port_param_driverinit_value_set
  - net/core/devlink.c:devlink_param_driverinit_value_set
```
**Symbols:**

```
ffff800010c2fa48-ffff800010c2fb84: __devlink_param_driverinit_value_set (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int __devlink_param_driverinit_value_set(struct devlink *devlink, unsigned int port_index, struct list_head *param_list, u32 param_id, union devlink_param_value init_val, enum devlink_command cmd);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/devlink.c (c0d46a34)
Location: net/core/devlink.c:7198
Inline: False
Direct callers:
  - net/core/devlink.c:devlink_port_param_driverinit_value_set
  - net/core/devlink.c:devlink_param_driverinit_value_set
```
**Symbols:**

```
c0d46a34-c0d46b30: __devlink_param_driverinit_value_set (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int __devlink_param_driverinit_value_set(struct devlink *devlink, unsigned int port_index, struct list_head *param_list, u32 param_id, union devlink_param_value init_val, enum devlink_command cmd);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/devlink.c (c000000000d27f80)
Location: net/core/devlink.c:7198
Inline: False
Direct callers:
  - net/core/devlink.c:devlink_port_param_driverinit_value_set
  - net/core/devlink.c:devlink_param_driverinit_value_set
```
**Symbols:**

```
c000000000d27f80-c000000000d2813c: __devlink_param_driverinit_value_set (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int __devlink_param_driverinit_value_set(struct devlink *devlink, unsigned int port_index, struct list_head *param_list, u32 param_id, union devlink_param_value init_val, enum devlink_command cmd);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/devlink.c (ffffffe0007a5e46)
Location: net/core/devlink.c:7198
Inline: False
Direct callers:
  - net/core/devlink.c:devlink_port_param_driverinit_value_set
  - net/core/devlink.c:devlink_param_driverinit_value_set
```
**Symbols:**

```
ffffffe0007a5e46-ffffffe0007a5f22: __devlink_param_driverinit_value_set (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Transformation ⚠️</summary>

```c
int __devlink_param_driverinit_value_set(struct devlink *devlink, unsigned int port_index, struct list_head *param_list, u32 param_id, union devlink_param_value init_val, enum devlink_command cmd);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/core/devlink.c (0)
Location: net/core/devlink.c:7198
Inline: False
Direct callers:
  - net/core/devlink.c:devlink_port_param_driverinit_value_set
  - net/core/devlink.c:devlink_param_driverinit_value_set
```
**Symbols:**

```
ffffffff819273d0-ffffffff8192753f: __devlink_param_driverinit_value_set (STB_LOCAL)
ffffffff81928849-ffffffff81928861: __devlink_param_driverinit_value_set.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Transformation ⚠️</summary>

```c
int __devlink_param_driverinit_value_set(struct devlink *devlink, unsigned int port_index, struct list_head *param_list, u32 param_id, union devlink_param_value init_val, enum devlink_command cmd);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/core/devlink.c (0)
Location: net/core/devlink.c:7198
Inline: False
Direct callers:
  - net/core/devlink.c:devlink_port_param_driverinit_value_set
  - net/core/devlink.c:devlink_param_driverinit_value_set
```
**Symbols:**

```
ffffffff818e1180-ffffffff818e12ef: __devlink_param_driverinit_value_set (STB_LOCAL)
ffffffff818e25f9-ffffffff818e2611: __devlink_param_driverinit_value_set.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Transformation ⚠️</summary>

```c
int __devlink_param_driverinit_value_set(struct devlink *devlink, unsigned int port_index, struct list_head *param_list, u32 param_id, union devlink_param_value init_val, enum devlink_command cmd);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/core/devlink.c (0)
Location: net/core/devlink.c:7198
Inline: False
Direct callers:
  - net/core/devlink.c:devlink_port_param_driverinit_value_set
  - net/core/devlink.c:devlink_param_driverinit_value_set
```
**Symbols:**

```
ffffffff81978560-ffffffff819786cf: __devlink_param_driverinit_value_set (STB_LOCAL)
ffffffff819799d9-ffffffff819799f1: __devlink_param_driverinit_value_set.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
int __devlink_param_driverinit_value_set(struct devlink *devlink, unsigned int port_index, struct list_head *param_list, u32 param_id, union devlink_param_value init_val, enum devlink_command cmd);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/core/devlink.c (0)
Location: net/core/devlink.c:7198
Inline: False
Direct callers:
  - net/core/devlink.c:devlink_port_param_driverinit_value_set
  - net/core/devlink.c:devlink_param_driverinit_value_set
```
**Symbols:**

```
ffffffff8199aa50-ffffffff8199abbf: __devlink_param_driverinit_value_set (STB_LOCAL)
ffffffff8199bec9-ffffffff8199bee1: __devlink_param_driverinit_value_set.cold (STB_LOCAL)
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
