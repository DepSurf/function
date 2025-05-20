# Function: <code>regulator_get_suspend_state_check</code>

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
<summary>In <code>5.11</code>: Selective Inline, Transformation ⚠️</summary>

```c
const struct regulator_state *regulator_get_suspend_state_check(struct regulator_dev *rdev, suspend_state_t state);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/regulator/core.c (ffffffff817490bc)
Location: drivers/regulator/core.c:570
Inline: True
Direct callers:
  - drivers/regulator/core.c:regulator_suspend
  - drivers/regulator/core.c:set_machine_constraints
```
**Symbols:**

```
ffffffff81749080-ffffffff817490ed: regulator_get_suspend_state_check (STB_LOCAL)
ffffffff81c06801-ffffffff81c0681c: regulator_get_suspend_state_check.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline, Transformation ⚠️</summary>

```c
const struct regulator_state *regulator_get_suspend_state_check(struct regulator_dev *rdev, suspend_state_t state);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/regulator/core.c (ffffffff8172c96c)
Location: drivers/regulator/core.c:571
Inline: True
Direct callers:
  - drivers/regulator/core.c:regulator_suspend
  - drivers/regulator/core.c:set_machine_constraints
```
**Symbols:**

```
ffffffff8172c930-ffffffff8172c998: regulator_get_suspend_state_check (STB_LOCAL)
ffffffff81bf84a1-ffffffff81bf84bd: regulator_get_suspend_state_check.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline, Transformation ⚠️</summary>

```c
const struct regulator_state *regulator_get_suspend_state_check(struct regulator_dev *rdev, suspend_state_t state);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/regulator/core.c (ffffffff817a7f6c)
Location: drivers/regulator/core.c:561
Inline: True
Direct callers:
  - drivers/regulator/core.c:regulator_suspend
  - drivers/regulator/core.c:set_machine_constraints
```
**Symbols:**

```
ffffffff817a7f30-ffffffff817a7f98: regulator_get_suspend_state_check (STB_LOCAL)
ffffffff81cf751b-ffffffff81cf7537: regulator_get_suspend_state_check.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
const struct regulator_state *regulator_get_suspend_state_check(struct regulator_dev *rdev, suspend_state_t state);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/regulator/core.c (0)
Location: drivers/regulator/core.c:562
Inline: False
Direct callers:
  - drivers/regulator/core.c:regulator_suspend
  - drivers/regulator/core.c:set_machine_constraints
```
**Symbols:**

```
ffffffff818e2800-ffffffff818e287f: regulator_get_suspend_state_check (STB_LOCAL)
ffffffff81ebf6eb-ffffffff81ebf713: regulator_get_suspend_state_check.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
const struct regulator_state *regulator_get_suspend_state_check(struct regulator_dev *rdev, suspend_state_t state);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/regulator/core.c (ffffffff81a39bd0)
Location: drivers/regulator/core.c:562
Inline: False
Direct callers:
  - drivers/regulator/core.c:regulator_suspend
  - drivers/regulator/core.c:set_machine_constraints
```
**Symbols:**

```
ffffffff81a39bd0-ffffffff81a39c7a: regulator_get_suspend_state_check (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
const struct regulator_state *regulator_get_suspend_state_check(struct regulator_dev *rdev, suspend_state_t state);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/regulator/core.c (ffffffff81a837b0)
Location: drivers/regulator/core.c:628
Inline: False
Direct callers:
  - drivers/regulator/core.c:regulator_suspend
  - drivers/regulator/core.c:set_machine_constraints
```
**Symbols:**

```
ffffffff81a837b0-ffffffff81a83860: regulator_get_suspend_state_check (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
const struct regulator_state *regulator_get_suspend_state_check(struct regulator_dev *rdev, suspend_state_t state);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/regulator/core.c (ffffffff81ad5f60)
Location: drivers/regulator/core.c:630
Inline: False
Direct callers:
  - drivers/regulator/core.c:regulator_suspend
  - drivers/regulator/core.c:set_machine_constraints
```
**Symbols:**

```
ffffffff81ad5f60-ffffffff81ad6010: regulator_get_suspend_state_check (STB_LOCAL)
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
