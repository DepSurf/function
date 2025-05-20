# Function: <code>devlink_param_register_one</code>

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
In net/core/devlink.c (ffffffff81950acf)
Location: net/core/devlink.c:3333
Inline: True
Inline callers:
  - net/core/devlink.c:__devlink_params_register
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
In net/core/devlink.c (ffffffff8198718f)
Location: net/core/devlink.c:3372
Inline: True
Inline callers:
  - net/core/devlink.c:__devlink_params_register
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
Location: net/core/devlink.c:3510
Inline: True
Inline callers:
  - net/core/devlink.c:__devlink_params_register
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
Location: net/core/devlink.c:4055
Inline: True
Inline callers:
  - net/core/devlink.c:__devlink_params_register
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
Location: net/core/devlink.c:4258
Inline: True
Inline callers:
  - net/core/devlink.c:__devlink_params_register
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int devlink_param_register_one(struct devlink *devlink, unsigned int port_index, struct list_head *param_list, const struct devlink_param *param, enum devlink_command cmd);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/devlink.c (ffffffff81affbf0)
Location: net/core/devlink.c:4851
Inline: False
Direct callers:
  - net/core/devlink.c:devlink_param_register
  - net/core/devlink.c:__devlink_params_register
```
**Symbols:**

```
ffffffff81affbf0-ffffffff81affcd8: devlink_param_register_one (STB_LOCAL)
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
<summary>In <code>arm64</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/core/devlink.c (ffff800010c2f5ec)
Location: net/core/devlink.c:3372
Inline: True
Inline callers:
  - net/core/devlink.c:__devlink_params_register
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
In net/core/devlink.c (c0d46634)
Location: net/core/devlink.c:3372
Inline: True
Inline callers:
  - net/core/devlink.c:__devlink_params_register
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
In net/core/devlink.c (c000000000d2787c)
Location: net/core/devlink.c:3372
Inline: True
Inline callers:
  - net/core/devlink.c:__devlink_params_register
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
In net/core/devlink.c (ffffffe0007a5a48)
Location: net/core/devlink.c:3372
Inline: True
Inline callers:
  - net/core/devlink.c:__devlink_params_register
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
In net/core/devlink.c (ffffffff81926fff)
Location: net/core/devlink.c:3372
Inline: True
Inline callers:
  - net/core/devlink.c:__devlink_params_register
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
In net/core/devlink.c (ffffffff818e0daf)
Location: net/core/devlink.c:3372
Inline: True
Inline callers:
  - net/core/devlink.c:__devlink_params_register
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
In net/core/devlink.c (ffffffff8197818f)
Location: net/core/devlink.c:3372
Inline: True
Inline callers:
  - net/core/devlink.c:__devlink_params_register
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
In net/core/devlink.c (ffffffff8199a67f)
Location: net/core/devlink.c:3372
Inline: True
Inline callers:
  - net/core/devlink.c:__devlink_params_register
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
</ul>
