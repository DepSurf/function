# Function: <code>devlink_nl_param_value_fill_one</code>

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
In net/core/devlink.c (ffffffff8194fe7f)
Location: net/core/devlink.c:2952
Inline: True
Inline callers:
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
In net/core/devlink.c (ffffffff819864ef)
Location: net/core/devlink.c:2984
Inline: True
Inline callers:
  - net/core/devlink.c:devlink_nl_param_fill
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
int devlink_nl_param_value_fill_one(struct sk_buff *msg, enum devlink_param_type type, enum devlink_param_cmode cmode, union devlink_param_value val);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/core/devlink.c (0)
Location: net/core/devlink.c:3117
Inline: False
Direct callers:
  - net/core/devlink.c:devlink_nl_param_fill
```
**Symbols:**

```
ffffffff81a5c940-ffffffff81a5cace: devlink_nl_param_value_fill_one (STB_LOCAL)
ffffffff81a6060f-ffffffff81a60627: devlink_nl_param_value_fill_one.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
int devlink_nl_param_value_fill_one(struct sk_buff *msg, enum devlink_param_type type, enum devlink_param_cmode cmode, union devlink_param_value val);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/core/devlink.c (0)
Location: net/core/devlink.c:3662
Inline: False
Direct callers:
  - net/core/devlink.c:devlink_nl_param_fill
```
**Symbols:**

```
ffffffff81a63d30-ffffffff81a63ebe: devlink_nl_param_value_fill_one (STB_LOCAL)
ffffffff81c31f53-ffffffff81c31f6b: devlink_nl_param_value_fill_one.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
int devlink_nl_param_value_fill_one(struct sk_buff *msg, enum devlink_param_type type, enum devlink_param_cmode cmode, union devlink_param_value val);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/core/devlink.c (0)
Location: net/core/devlink.c:3865
Inline: False
Direct callers:
  - net/core/devlink.c:devlink_nl_param_fill
```
**Symbols:**

```
ffffffff81a47d60-ffffffff81a47eed: devlink_nl_param_value_fill_one (STB_LOCAL)
ffffffff81c2426d-ffffffff81c24285: devlink_nl_param_value_fill_one.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int devlink_nl_param_value_fill_one(struct sk_buff *msg, enum devlink_param_type type, enum devlink_param_cmode cmode, union devlink_param_value val);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/core/devlink.c (0)
Location: net/core/devlink.c:4450
Inline: False
Direct callers:
  - net/core/devlink.c:devlink_nl_param_fill
```
**Symbols:**

```
ffffffff81afec50-ffffffff81afede9: devlink_nl_param_value_fill_one (STB_LOCAL)
ffffffff81d3885e-ffffffff81d3888a: devlink_nl_param_value_fill_one.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int devlink_nl_param_value_fill_one(struct sk_buff *msg, enum devlink_param_type type, enum devlink_param_cmode cmode, union devlink_param_value val);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/core/devlink.c (0)
Location: net/core/devlink.c:4980
Inline: False
Direct callers:
  - net/core/devlink.c:devlink_nl_param_fill
```
**Symbols:**

```
ffffffff81c82560-ffffffff81c82708: devlink_nl_param_value_fill_one (STB_LOCAL)
ffffffff81f051d9-ffffffff81f05206: devlink_nl_param_value_fill_one.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
int devlink_nl_param_value_fill_one(struct sk_buff *msg, enum devlink_param_type type, enum devlink_param_cmode cmode, union devlink_param_value val);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/core/devlink.c (0)
Location: net/core/devlink.c:5504
Inline: False
```
**Symbols:**

```
ffffffff81e3ab30-ffffffff81e3ace8: devlink_nl_param_value_fill_one (STB_LOCAL)
ffffffff820ad1ba-ffffffff820ad1cf: devlink_nl_param_value_fill_one.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
int devlink_nl_param_value_fill_one(struct sk_buff *msg, enum devlink_param_type type, enum devlink_param_cmode cmode, union devlink_param_value val);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/devlink/leftover.c (0)
Location: net/devlink/leftover.c:3983
Inline: False
```
**Symbols:**

```
ffffffff8203a9d0-ffffffff8203ab88: devlink_nl_param_value_fill_one (STB_LOCAL)
ffffffff821364c0-ffffffff821364d5: devlink_nl_param_value_fill_one.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
int devlink_nl_param_value_fill_one(struct sk_buff *msg, enum devlink_param_type type, enum devlink_param_cmode cmode, union devlink_param_value val);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/devlink/param.c (0)
Location: net/devlink/param.c:188
Inline: False
```
**Symbols:**

```
ffffffff8210daa0-ffffffff8210dc58: devlink_nl_param_value_fill_one (STB_LOCAL)
ffffffff822181db-ffffffff822181f0: devlink_nl_param_value_fill_one.cold (STB_LOCAL)
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
In net/core/devlink.c (ffff800010c2ea08)
Location: net/core/devlink.c:2984
Inline: True
Inline callers:
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
In net/core/devlink.c (c0d45a18)
Location: net/core/devlink.c:2984
Inline: True
Inline callers:
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
In net/core/devlink.c (c000000000d26698)
Location: net/core/devlink.c:2984
Inline: True
Inline callers:
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
In net/core/devlink.c (ffffffe0007a5144)
Location: net/core/devlink.c:2984
Inline: True
Inline callers:
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
In net/core/devlink.c (ffffffff8192635f)
Location: net/core/devlink.c:2984
Inline: True
Inline callers:
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
In net/core/devlink.c (ffffffff818e010f)
Location: net/core/devlink.c:2984
Inline: True
Inline callers:
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
In net/core/devlink.c (ffffffff819774ef)
Location: net/core/devlink.c:2984
Inline: True
Inline callers:
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
In net/core/devlink.c (ffffffff819999df)
Location: net/core/devlink.c:2984
Inline: True
Inline callers:
  - net/core/devlink.c:devlink_nl_param_fill
```
</details>
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
