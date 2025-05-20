# Function: <code>__devlink_param_driverinit_value_get</code>

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
int __devlink_param_driverinit_value_get(struct list_head *param_list, u32 param_id, union devlink_param_value *init_val);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/devlink.c (ffffffff819462b0)
Location: net/core/devlink.c:6478
Inline: False
Direct callers:
  - net/core/devlink.c:devlink_port_param_driverinit_value_get
  - net/core/devlink.c:devlink_param_driverinit_value_get
```
**Symbols:**

```
ffffffff819462b0-ffffffff8194632e: __devlink_param_driverinit_value_get (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int __devlink_param_driverinit_value_get(struct list_head *param_list, u32 param_id, union devlink_param_value *init_val);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/devlink.c (ffffffff8197b250)
Location: net/core/devlink.c:7175
Inline: False
Direct callers:
  - net/core/devlink.c:devlink_port_param_driverinit_value_get
  - net/core/devlink.c:devlink_param_driverinit_value_get
```
**Symbols:**

```
ffffffff8197b250-ffffffff8197b2ce: __devlink_param_driverinit_value_get (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int __devlink_param_driverinit_value_get(struct list_head *param_list, u32 param_id, union devlink_param_value *init_val);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/devlink.c (ffffffff81a52c90)
Location: net/core/devlink.c:8120
Inline: False
Direct callers:
  - net/core/devlink.c:devlink_port_param_driverinit_value_get
  - net/core/devlink.c:devlink_param_driverinit_value_get
```
**Symbols:**

```
ffffffff81a52c90-ffffffff81a52d10: __devlink_param_driverinit_value_get (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
int __devlink_param_driverinit_value_get(struct list_head *param_list, u32 param_id, union devlink_param_value *init_val);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/core/devlink.c (0)
Location: net/core/devlink.c:9008
Inline: False
Direct callers:
  - net/core/devlink.c:devlink_port_param_driverinit_value_get
  - net/core/devlink.c:devlink_param_driverinit_value_get
```
**Symbols:**

```
ffffffff81a592b0-ffffffff81a593f9: __devlink_param_driverinit_value_get (STB_LOCAL)
ffffffff81c31f3b-ffffffff81c31f53: __devlink_param_driverinit_value_get.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
int __devlink_param_driverinit_value_get(struct list_head *param_list, u32 param_id, union devlink_param_value *init_val);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/core/devlink.c (0)
Location: net/core/devlink.c:9271
Inline: False
Direct callers:
  - net/core/devlink.c:devlink_port_param_driverinit_value_get
  - net/core/devlink.c:devlink_param_driverinit_value_get
```
**Symbols:**

```
ffffffff81a3c220-ffffffff81a3c365: __devlink_param_driverinit_value_get (STB_LOCAL)
ffffffff81c2421e-ffffffff81c24236: __devlink_param_driverinit_value_get.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int __devlink_param_driverinit_value_get(struct list_head *param_list, u32 param_id, union devlink_param_value *init_val);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/core/devlink.c (0)
Location: net/core/devlink.c:10213
Inline: False
Direct callers:
  - net/core/devlink.c:devlink_port_param_driverinit_value_get
  - net/core/devlink.c:devlink_param_driverinit_value_get
```
**Symbols:**

```
ffffffff81af2c40-ffffffff81af2d91: __devlink_param_driverinit_value_get (STB_LOCAL)
ffffffff81d383f9-ffffffff81d38426: __devlink_param_driverinit_value_get.cold (STB_LOCAL)
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
int __devlink_param_driverinit_value_get(struct list_head *param_list, u32 param_id, union devlink_param_value *init_val);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/devlink.c (ffff800010c22a40)
Location: net/core/devlink.c:7175
Inline: False
Direct callers:
  - net/core/devlink.c:devlink_port_param_driverinit_value_get
  - net/core/devlink.c:devlink_param_driverinit_value_get
```
**Symbols:**

```
ffff800010c22a40-ffff800010c22b14: __devlink_param_driverinit_value_get (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int __devlink_param_driverinit_value_get(struct list_head *param_list, u32 param_id, union devlink_param_value *init_val);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/devlink.c (c0d39da8)
Location: net/core/devlink.c:7175
Inline: False
Direct callers:
  - net/core/devlink.c:devlink_port_param_driverinit_value_get
  - net/core/devlink.c:devlink_param_driverinit_value_get
```
**Symbols:**

```
c0d39da8-c0d39e68: __devlink_param_driverinit_value_get (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int __devlink_param_driverinit_value_get(struct list_head *param_list, u32 param_id, union devlink_param_value *init_val);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/devlink.c (c000000000d15270)
Location: net/core/devlink.c:7175
Inline: False
Direct callers:
  - net/core/devlink.c:devlink_port_param_driverinit_value_get
  - net/core/devlink.c:devlink_param_driverinit_value_get
```
**Symbols:**

```
c000000000d15270-c000000000d15348: __devlink_param_driverinit_value_get (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int __devlink_param_driverinit_value_get(struct list_head *param_list, u32 param_id, union devlink_param_value *init_val);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/devlink.c (ffffffe00079b3b2)
Location: net/core/devlink.c:7175
Inline: False
Direct callers:
  - net/core/devlink.c:devlink_port_param_driverinit_value_get
  - net/core/devlink.c:devlink_param_driverinit_value_get
```
**Symbols:**

```
ffffffe00079b3b2-ffffffe00079b478: __devlink_param_driverinit_value_get (STB_LOCAL)
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
int __devlink_param_driverinit_value_get(struct list_head *param_list, u32 param_id, union devlink_param_value *init_val);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/devlink.c (ffffffff8191b0c0)
Location: net/core/devlink.c:7175
Inline: False
Direct callers:
  - net/core/devlink.c:devlink_port_param_driverinit_value_get
  - net/core/devlink.c:devlink_param_driverinit_value_get
```
**Symbols:**

```
ffffffff8191b0c0-ffffffff8191b13e: __devlink_param_driverinit_value_get (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int __devlink_param_driverinit_value_get(struct list_head *param_list, u32 param_id, union devlink_param_value *init_val);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/devlink.c (ffffffff818d4e70)
Location: net/core/devlink.c:7175
Inline: False
Direct callers:
  - net/core/devlink.c:devlink_port_param_driverinit_value_get
  - net/core/devlink.c:devlink_param_driverinit_value_get
```
**Symbols:**

```
ffffffff818d4e70-ffffffff818d4eee: __devlink_param_driverinit_value_get (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int __devlink_param_driverinit_value_get(struct list_head *param_list, u32 param_id, union devlink_param_value *init_val);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/devlink.c (ffffffff8196c250)
Location: net/core/devlink.c:7175
Inline: False
Direct callers:
  - net/core/devlink.c:devlink_port_param_driverinit_value_get
  - net/core/devlink.c:devlink_param_driverinit_value_get
```
**Symbols:**

```
ffffffff8196c250-ffffffff8196c2ce: __devlink_param_driverinit_value_get (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int __devlink_param_driverinit_value_get(struct list_head *param_list, u32 param_id, union devlink_param_value *init_val);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/devlink.c (ffffffff8198e6d0)
Location: net/core/devlink.c:7175
Inline: False
Direct callers:
  - net/core/devlink.c:devlink_port_param_driverinit_value_get
  - net/core/devlink.c:devlink_param_driverinit_value_get
```
**Symbols:**

```
ffffffff8198e6d0-ffffffff8198e74e: __devlink_param_driverinit_value_get (STB_LOCAL)
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
