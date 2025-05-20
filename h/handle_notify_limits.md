# Function: <code>handle_notify_limits</code>

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
In <code>5.11</code>: Absent ⚠️
</li>
<li>
In <code>5.13</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int handle_notify_limits(struct regulator_dev *rdev, int (*set)(struct regulator_dev *, int, int, bool), struct notification_limit *limits);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/regulator/core.c (ffffffff817a6760)
Location: drivers/regulator/core.c:1317
Inline: False
Direct callers:
  - drivers/regulator/core.c:set_machine_constraints
  - drivers/regulator/core.c:set_machine_constraints
  - drivers/regulator/core.c:set_machine_constraints
  - drivers/regulator/core.c:set_machine_constraints
```
**Symbols:**

```
ffffffff817a6760-ffffffff817a6822: handle_notify_limits (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int handle_notify_limits(struct regulator_dev *rdev, int (*set)(struct regulator_dev *, int, int, bool), struct notification_limit *limits);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/regulator/core.c (ffffffff818e0a00)
Location: drivers/regulator/core.c:1343
Inline: False
Direct callers:
  - drivers/regulator/core.c:set_machine_constraints
  - drivers/regulator/core.c:set_machine_constraints
  - drivers/regulator/core.c:set_machine_constraints
  - drivers/regulator/core.c:set_machine_constraints
```
**Symbols:**

```
ffffffff818e0a00-ffffffff818e0aec: handle_notify_limits (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int handle_notify_limits(struct regulator_dev *rdev, int (*set)(struct regulator_dev *, int, int, bool), struct notification_limit *limits);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/regulator/core.c (ffffffff81a35a40)
Location: drivers/regulator/core.c:1361
Inline: False
Direct callers:
  - drivers/regulator/core.c:set_machine_constraints
  - drivers/regulator/core.c:set_machine_constraints
  - drivers/regulator/core.c:set_machine_constraints
  - drivers/regulator/core.c:set_machine_constraints
```
**Symbols:**

```
ffffffff81a35a40-ffffffff81a35b2c: handle_notify_limits (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int handle_notify_limits(struct regulator_dev *rdev, int (*set)(struct regulator_dev *, int, int, bool), struct notification_limit *limits);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/regulator/core.c (ffffffff81a7f4c0)
Location: drivers/regulator/core.c:1427
Inline: False
Direct callers:
  - drivers/regulator/core.c:set_machine_constraints
  - drivers/regulator/core.c:set_machine_constraints
  - drivers/regulator/core.c:set_machine_constraints
  - drivers/regulator/core.c:set_machine_constraints
```
**Symbols:**

```
ffffffff81a7f4c0-ffffffff81a7f5d5: handle_notify_limits (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int handle_notify_limits(struct regulator_dev *rdev, int (*set)(struct regulator_dev *, int, int, bool), struct notification_limit *limits);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/regulator/core.c (ffffffff81ad1a30)
Location: drivers/regulator/core.c:1429
Inline: False
Direct callers:
  - drivers/regulator/core.c:set_machine_constraints
  - drivers/regulator/core.c:set_machine_constraints
  - drivers/regulator/core.c:set_machine_constraints
  - drivers/regulator/core.c:set_machine_constraints
```
**Symbols:**

```
ffffffff81ad1a30-ffffffff81ad1b45: handle_notify_limits (STB_LOCAL)
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
