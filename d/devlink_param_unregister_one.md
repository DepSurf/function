# Function: <code>devlink_param_unregister_one</code>

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
<summary>In <code>5.3</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/core/devlink.c (0)
Location: net/core/devlink.c:3359
Inline: True
Direct callers:
  - net/core/devlink.c:devlink_port_params_unregister
  - net/core/devlink.c:devlink_params_unregister
  - net/core/devlink.c:__devlink_params_register
```
**Symbols:**

```
ffffffff819509b0-ffffffff81950a2b: devlink_param_unregister_one.isra.0 (STB_LOCAL)
ffffffff819525b7-ffffffff819525ca: devlink_param_unregister_one.isra.0.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/core/devlink.c (ffffffff81987070)
Location: net/core/devlink.c:3398
Inline: True
Direct callers:
  - net/core/devlink.c:devlink_port_params_unregister
  - net/core/devlink.c:devlink_params_unregister
  - net/core/devlink.c:__devlink_params_register
```
**Symbols:**

```
ffffffff81987070-ffffffff819870eb: devlink_param_unregister_one.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/core/devlink.c (ffffffff81a5dca0)
Location: net/core/devlink.c:3536
Inline: True
Direct callers:
  - net/core/devlink.c:devlink_port_params_unregister
  - net/core/devlink.c:devlink_params_unregister
  - net/core/devlink.c:__devlink_params_register
```
**Symbols:**

```
ffffffff81a5dca0-ffffffff81a5dd47: devlink_param_unregister_one.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/core/devlink.c (ffffffff81a64d60)
Location: net/core/devlink.c:4081
Inline: True
Direct callers:
  - net/core/devlink.c:devlink_port_params_unregister
  - net/core/devlink.c:devlink_params_unregister
  - net/core/devlink.c:__devlink_params_register
```
**Symbols:**

```
ffffffff81a64d60-ffffffff81a64e07: devlink_param_unregister_one.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/core/devlink.c (ffffffff81a48d80)
Location: net/core/devlink.c:4284
Inline: True
Direct callers:
  - net/core/devlink.c:devlink_port_params_unregister
  - net/core/devlink.c:devlink_params_unregister
  - net/core/devlink.c:__devlink_params_register
```
**Symbols:**

```
ffffffff81a48d80-ffffffff81a48e27: devlink_param_unregister_one.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/core/devlink.c (ffffffff81b00180)
Location: net/core/devlink.c:4877
Inline: True
Direct callers:
  - net/core/devlink.c:devlink_port_params_unregister
  - net/core/devlink.c:devlink_param_unregister
  - net/core/devlink.c:devlink_params_unregister
  - net/core/devlink.c:__devlink_params_register
```
**Symbols:**

```
ffffffff81b00180-ffffffff81b00227: devlink_param_unregister_one.isra.0 (STB_LOCAL)
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
<summary>In <code>arm64</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/core/devlink.c (ffff800010c2f480)
Location: net/core/devlink.c:3398
Inline: True
Direct callers:
  - net/core/devlink.c:devlink_port_params_unregister
  - net/core/devlink.c:devlink_params_unregister
  - net/core/devlink.c:__devlink_params_register
```
**Symbols:**

```
ffff800010c2f480-ffff800010c2f51c: devlink_param_unregister_one.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void devlink_param_unregister_one(struct devlink *devlink, unsigned int port_index, struct list_head *param_list, const struct devlink_param *param, enum devlink_command cmd);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/devlink.c (c0d464d0)
Location: net/core/devlink.c:3398
Inline: False
Direct callers:
  - net/core/devlink.c:devlink_port_params_unregister
  - net/core/devlink.c:devlink_params_unregister
  - net/core/devlink.c:__devlink_params_register
```
**Symbols:**

```
c0d464d0-c0d46558: devlink_param_unregister_one (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/core/devlink.c (c000000000d27540)
Location: net/core/devlink.c:3398
Inline: True
Direct callers:
  - net/core/devlink.c:devlink_port_params_unregister
  - net/core/devlink.c:devlink_params_unregister
  - net/core/devlink.c:__devlink_params_register
```
**Symbols:**

```
c000000000d27540-c000000000d2760c: devlink_param_unregister_one.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/core/devlink.c (ffffffe0007a597a)
Location: net/core/devlink.c:3398
Inline: True
Direct callers:
  - net/core/devlink.c:devlink_port_params_unregister
  - net/core/devlink.c:devlink_params_unregister
  - net/core/devlink.c:__devlink_params_register
```
**Symbols:**

```
ffffffe0007a597a-ffffffe0007a59f4: devlink_param_unregister_one.isra.0 (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/core/devlink.c (ffffffff81926ee0)
Location: net/core/devlink.c:3398
Inline: True
Direct callers:
  - net/core/devlink.c:devlink_port_params_unregister
  - net/core/devlink.c:devlink_params_unregister
  - net/core/devlink.c:__devlink_params_register
```
**Symbols:**

```
ffffffff81926ee0-ffffffff81926f5b: devlink_param_unregister_one.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/core/devlink.c (ffffffff818e0c90)
Location: net/core/devlink.c:3398
Inline: True
Direct callers:
  - net/core/devlink.c:devlink_port_params_unregister
  - net/core/devlink.c:devlink_params_unregister
  - net/core/devlink.c:__devlink_params_register
```
**Symbols:**

```
ffffffff818e0c90-ffffffff818e0d0b: devlink_param_unregister_one.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/core/devlink.c (ffffffff81978070)
Location: net/core/devlink.c:3398
Inline: True
Direct callers:
  - net/core/devlink.c:devlink_port_params_unregister
  - net/core/devlink.c:devlink_params_unregister
  - net/core/devlink.c:__devlink_params_register
```
**Symbols:**

```
ffffffff81978070-ffffffff819780eb: devlink_param_unregister_one.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/core/devlink.c (ffffffff8199a560)
Location: net/core/devlink.c:3398
Inline: True
Direct callers:
  - net/core/devlink.c:devlink_port_params_unregister
  - net/core/devlink.c:devlink_params_unregister
  - net/core/devlink.c:__devlink_params_register
```
**Symbols:**

```
ffffffff8199a560-ffffffff8199a5db: devlink_param_unregister_one.isra.0 (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Arch</b>
<ul>
</ul>
