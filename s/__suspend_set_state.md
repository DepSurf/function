# Function: <code>__suspend_set_state</code>

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
In <code>5.4</code>: Absent ⚠️
</li>
<li>
In <code>5.8</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
int __suspend_set_state(struct regulator_dev *rdev, const struct regulator_state *rstate);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/regulator/core.c (0)
Location: drivers/regulator/core.c:1012
Inline: False
Direct callers:
  - drivers/regulator/core.c:regulator_suspend
  - drivers/regulator/core.c:set_machine_constraints
```
**Symbols:**

```
ffffffff817490f0-ffffffff817491bc: __suspend_set_state (STB_LOCAL)
ffffffff81c0681c-ffffffff81c06879: __suspend_set_state.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
int __suspend_set_state(struct regulator_dev *rdev, const struct regulator_state *rstate);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/regulator/core.c (0)
Location: drivers/regulator/core.c:1014
Inline: False
Direct callers:
  - drivers/regulator/core.c:regulator_suspend
  - drivers/regulator/core.c:set_machine_constraints
```
**Symbols:**

```
ffffffff8172c9a0-ffffffff8172ca6c: __suspend_set_state (STB_LOCAL)
ffffffff81bf84bd-ffffffff81bf851a: __suspend_set_state.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int __suspend_set_state(struct regulator_dev *rdev, const struct regulator_state *rstate);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/regulator/core.c (0)
Location: drivers/regulator/core.c:994
Inline: False
Direct callers:
  - drivers/regulator/core.c:regulator_suspend
  - drivers/regulator/core.c:set_machine_constraints
```
**Symbols:**

```
ffffffff817a78a0-ffffffff817a796c: __suspend_set_state (STB_LOCAL)
ffffffff81cf73d0-ffffffff81cf742d: __suspend_set_state.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int __suspend_set_state(struct regulator_dev *rdev, const struct regulator_state *rstate);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/regulator/core.c (0)
Location: drivers/regulator/core.c:1019
Inline: False
Direct callers:
  - drivers/regulator/core.c:regulator_suspend
  - drivers/regulator/core.c:set_machine_constraints
```
**Symbols:**

```
ffffffff818e20d0-ffffffff818e21a3: __suspend_set_state (STB_LOCAL)
ffffffff81ebf5a4-ffffffff81ebf601: __suspend_set_state.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int __suspend_set_state(struct regulator_dev *rdev, const struct regulator_state *rstate);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/regulator/core.c (ffffffff81a3ae50)
Location: drivers/regulator/core.c:1037
Inline: False
Direct callers:
  - drivers/regulator/core.c:regulator_suspend
  - drivers/regulator/core.c:set_machine_constraints
```
**Symbols:**

```
ffffffff81a3ae50-ffffffff81a3afdc: __suspend_set_state (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int __suspend_set_state(struct regulator_dev *rdev, const struct regulator_state *rstate);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/regulator/core.c (ffffffff81a84cd0)
Location: drivers/regulator/core.c:1103
Inline: False
Direct callers:
  - drivers/regulator/core.c:regulator_suspend
  - drivers/regulator/core.c:set_machine_constraints
```
**Symbols:**

```
ffffffff81a84cd0-ffffffff81a84e5c: __suspend_set_state (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int __suspend_set_state(struct regulator_dev *rdev, const struct regulator_state *rstate);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/regulator/core.c (ffffffff81ad74b0)
Location: drivers/regulator/core.c:1105
Inline: False
Direct callers:
  - drivers/regulator/core.c:regulator_suspend
  - drivers/regulator/core.c:set_machine_constraints
```
**Symbols:**

```
ffffffff81ad74b0-ffffffff81ad763c: __suspend_set_state (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
In <code>arm64</code>: Absent ⚠️
</li>
<li>
In <code>armhf</code>: Absent ⚠️
</li>
<li>
In <code>ppc64el</code>: Absent ⚠️
</li>
<li>
In <code>riscv64</code>: Absent ⚠️
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
In <code>aws</code>: Absent ⚠️
</li>
<li>
In <code>azure</code>: Absent ⚠️
</li>
<li>
In <code>gcp</code>: Absent ⚠️
</li>
<li>
In <code>lowlatency</code>: Absent ⚠️
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
