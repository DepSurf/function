# Function: <code>devlink_param_verify</code>

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
In net/core/devlink.c (ffffffff81950a79)
Location: net/core/devlink.c:6292
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
In net/core/devlink.c (ffffffff81987139)
Location: net/core/devlink.c:6989
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
In net/core/devlink.c (ffffffff81a5de1a)
Location: net/core/devlink.c:7934
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
In net/core/devlink.c (ffffffff81a64eda)
Location: net/core/devlink.c:8822
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
In net/core/devlink.c (ffffffff81a48efa)
Location: net/core/devlink.c:9085
Inline: True
Inline callers:
  - net/core/devlink.c:__devlink_params_register
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int devlink_param_verify(const struct devlink_param *param);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/core/devlink.c (0)
Location: net/core/devlink.c:9930
Inline: False
Direct callers:
  - net/core/devlink.c:devlink_param_register
  - net/core/devlink.c:__devlink_params_register
```
**Symbols:**

```
ffffffff81af07d0-ffffffff81af091c: devlink_param_verify (STB_LOCAL)
ffffffff81d38394-ffffffff81d383a8: devlink_param_verify.cold (STB_LOCAL)
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
In net/core/devlink.c (ffffffff81c776d7)
Location: net/core/devlink.c:10798
Inline: True
Inline callers:
  - net/core/devlink.c:devlink_param_register
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
In net/core/devlink.c (ffffffff81e30217)
Location: net/core/devlink.c:11581
Inline: True
Inline callers:
  - net/core/devlink.c:devlink_param_register
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/devlink/leftover.c (ffffffff8203b871)
Location: net/devlink/leftover.c:8138
Inline: True
Inline callers:
  - net/devlink/leftover.c:devl_params_register
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/devlink/param.c (ffffffff8210ebc0)
Location: net/devlink/param.c:612
Inline: True
Inline callers:
  - net/devlink/param.c:devl_params_register
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
In net/core/devlink.c (ffff800010c2f578)
Location: net/core/devlink.c:6989
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
In net/core/devlink.c (c0d46598)
Location: net/core/devlink.c:6989
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
In net/core/devlink.c (c000000000d27688)
Location: net/core/devlink.c:6989
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
In net/core/devlink.c (ffffffe0007a5a44)
Location: net/core/devlink.c:6989
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
In net/core/devlink.c (ffffffff81926fa9)
Location: net/core/devlink.c:6989
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
In net/core/devlink.c (ffffffff818e0d59)
Location: net/core/devlink.c:6989
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
In net/core/devlink.c (ffffffff81978139)
Location: net/core/devlink.c:6989
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
In net/core/devlink.c (ffffffff8199a629)
Location: net/core/devlink.c:6989
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
