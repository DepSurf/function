# Function: <code>regulator_unlock_recursive</code>

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
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void regulator_unlock_recursive(struct regulator_dev *rdev, unsigned int n_coupled);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/regulator/core.c (ffffffff816211c0)
Location: drivers/regulator/core.c:253
Inline: False
Direct callers:
  - drivers/regulator/core.c:regulator_get_voltage
  - drivers/regulator/core.c:regulator_set_suspend_voltage
  - drivers/regulator/core.c:regulator_set_voltage
  - drivers/regulator/core.c:regulator_disable_work
  - drivers/regulator/core.c:regulator_force_disable
  - drivers/regulator/core.c:regulator_disable
  - drivers/regulator/core.c:regulator_enable
  - drivers/regulator/core.c:regulator_lock_recursive
  - drivers/regulator/core.c:regulator_unlock_recursive
```
**Symbols:**

```
ffffffff816211c0-ffffffff8162123f: regulator_unlock_recursive (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/regulator/core.c (ffffffff81655390)
Location: drivers/regulator/core.c:235
Inline: True
Direct callers:
  - drivers/regulator/core.c:regulator_get_voltage
  - drivers/regulator/core.c:regulator_set_suspend_voltage
  - drivers/regulator/core.c:regulator_set_voltage
  - drivers/regulator/core.c:regulator_disable_work
  - drivers/regulator/core.c:regulator_force_disable
  - drivers/regulator/core.c:regulator_disable
  - drivers/regulator/core.c:regulator_enable
  - drivers/regulator/core.c:regulator_lock_recursive
```
**Symbols:**

```
ffffffff81655390-ffffffff81655430: regulator_unlock_recursive.isra.0 (STB_LOCAL)
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
In drivers/regulator/core.c (ffffffff816778c0)
Location: drivers/regulator/core.c:235
Inline: True
Direct callers:
  - drivers/regulator/core.c:regulator_get_voltage
  - drivers/regulator/core.c:regulator_set_suspend_voltage
  - drivers/regulator/core.c:regulator_set_voltage
  - drivers/regulator/core.c:regulator_disable_work
  - drivers/regulator/core.c:regulator_force_disable
  - drivers/regulator/core.c:regulator_disable
  - drivers/regulator/core.c:regulator_enable
  - drivers/regulator/core.c:regulator_lock_recursive
```
**Symbols:**

```
ffffffff816778c0-ffffffff81677960: regulator_unlock_recursive.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void regulator_unlock_recursive(struct regulator_dev *rdev, unsigned int n_coupled);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/regulator/core.c (ffffffff81727700)
Location: drivers/regulator/core.c:235
Inline: False
Direct callers:
  - drivers/regulator/core.c:regulator_unregister
  - drivers/regulator/core.c:regulator_bulk_disable
  - drivers/regulator/core.c:regulator_bulk_enable
  - drivers/regulator/core.c:regulator_bulk_enable_async
  - drivers/regulator/core.c:regulator_set_suspend_voltage
  - drivers/regulator/core.c:regulator_set_voltage
  - drivers/regulator/core.c:regulator_is_supported_voltage
  - drivers/regulator/core.c:regulator_disable_deferred
  - drivers/regulator/core.c:regulator_disable_work
  - drivers/regulator/core.c:regulator_force_disable
  - drivers/regulator/core.c:set_machine_constraints
  - drivers/regulator/core.c:drms_uA_update
  - drivers/regulator/core.c:regulator_lock_recursive
  - drivers/regulator/core.c:regulator_unlock_recursive
```
**Symbols:**

```
ffffffff81727700-ffffffff817277a5: regulator_unlock_recursive (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void regulator_unlock_recursive(struct regulator_dev *rdev, unsigned int n_coupled);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/regulator/core.c (ffffffff81744540)
Location: drivers/regulator/core.c:234
Inline: False
Direct callers:
  - drivers/regulator/core.c:regulator_unregister
  - drivers/regulator/core.c:regulator_bulk_disable
  - drivers/regulator/core.c:regulator_bulk_enable
  - drivers/regulator/core.c:regulator_bulk_enable_async
  - drivers/regulator/core.c:regulator_set_suspend_voltage
  - drivers/regulator/core.c:regulator_set_voltage
  - drivers/regulator/core.c:regulator_is_supported_voltage
  - drivers/regulator/core.c:regulator_disable_deferred
  - drivers/regulator/core.c:regulator_disable_work
  - drivers/regulator/core.c:regulator_force_disable
  - drivers/regulator/core.c:set_machine_constraints
  - drivers/regulator/core.c:drms_uA_update
  - drivers/regulator/core.c:regulator_lock_recursive
  - drivers/regulator/core.c:regulator_unlock_recursive
```
**Symbols:**

```
ffffffff81744540-ffffffff817445e5: regulator_unlock_recursive (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void regulator_unlock_recursive(struct regulator_dev *rdev, unsigned int n_coupled);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/regulator/core.c (ffffffff81727ee0)
Location: drivers/regulator/core.c:234
Inline: False
Direct callers:
  - drivers/regulator/core.c:regulator_unregister
  - drivers/regulator/core.c:regulator_bulk_disable
  - drivers/regulator/core.c:regulator_bulk_enable
  - drivers/regulator/core.c:regulator_bulk_enable_async
  - drivers/regulator/core.c:regulator_set_suspend_voltage
  - drivers/regulator/core.c:regulator_set_voltage
  - drivers/regulator/core.c:regulator_is_supported_voltage
  - drivers/regulator/core.c:regulator_disable_deferred
  - drivers/regulator/core.c:regulator_disable_work
  - drivers/regulator/core.c:regulator_force_disable
  - drivers/regulator/core.c:set_machine_constraints
  - drivers/regulator/core.c:drms_uA_update
  - drivers/regulator/core.c:regulator_lock_recursive
  - drivers/regulator/core.c:regulator_unlock_recursive
```
**Symbols:**

```
ffffffff81727ee0-ffffffff81727f85: regulator_unlock_recursive (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void regulator_unlock_recursive(struct regulator_dev *rdev, unsigned int n_coupled);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/regulator/core.c (ffffffff817a8d20)
Location: drivers/regulator/core.c:224
Inline: False
Direct callers:
  - drivers/regulator/core.c:regulator_unregister
  - drivers/regulator/core.c:regulator_bulk_disable
  - drivers/regulator/core.c:regulator_bulk_enable
  - drivers/regulator/core.c:regulator_bulk_enable_async
  - drivers/regulator/core.c:regulator_set_suspend_voltage
  - drivers/regulator/core.c:regulator_set_voltage
  - drivers/regulator/core.c:regulator_is_supported_voltage
  - drivers/regulator/core.c:regulator_disable_deferred
  - drivers/regulator/core.c:regulator_disable_work
  - drivers/regulator/core.c:regulator_force_disable
  - drivers/regulator/core.c:set_machine_constraints
  - drivers/regulator/core.c:drms_uA_update
  - drivers/regulator/core.c:regulator_lock_recursive
  - drivers/regulator/core.c:regulator_unlock_recursive
```
**Symbols:**

```
ffffffff817a8d20-ffffffff817a8e13: regulator_unlock_recursive (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void regulator_unlock_recursive(struct regulator_dev *rdev, unsigned int n_coupled);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/regulator/core.c (ffffffff818e3440)
Location: drivers/regulator/core.c:225
Inline: False
Direct callers:
  - drivers/regulator/core.c:regulator_unregister
  - drivers/regulator/core.c:regulator_bulk_disable
  - drivers/regulator/core.c:regulator_bulk_enable
  - drivers/regulator/core.c:regulator_bulk_enable_async
  - drivers/regulator/core.c:regulator_set_suspend_voltage
  - drivers/regulator/core.c:regulator_set_voltage
  - drivers/regulator/core.c:regulator_is_supported_voltage
  - drivers/regulator/core.c:regulator_disable_deferred
  - drivers/regulator/core.c:regulator_disable_work
  - drivers/regulator/core.c:regulator_force_disable
  - drivers/regulator/core.c:regulator_resolve_supply
  - drivers/regulator/core.c:set_machine_constraints
  - drivers/regulator/core.c:drms_uA_update
  - drivers/regulator/core.c:regulator_lock_recursive
  - drivers/regulator/core.c:regulator_unlock_recursive
```
**Symbols:**

```
ffffffff818e3440-ffffffff818e3556: regulator_unlock_recursive (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void regulator_unlock_recursive(struct regulator_dev *rdev, unsigned int n_coupled);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/regulator/core.c (ffffffff81a38570)
Location: drivers/regulator/core.c:225
Inline: False
Direct callers:
  - drivers/regulator/core.c:regulator_unregister
  - drivers/regulator/core.c:regulator_bulk_disable
  - drivers/regulator/core.c:regulator_bulk_disable
  - drivers/regulator/core.c:regulator_bulk_enable
  - drivers/regulator/core.c:regulator_bulk_enable_async
  - drivers/regulator/core.c:regulator_set_suspend_voltage
  - drivers/regulator/core.c:regulator_set_voltage
  - drivers/regulator/core.c:regulator_is_supported_voltage
  - drivers/regulator/core.c:regulator_disable_deferred
  - drivers/regulator/core.c:regulator_disable_work
  - drivers/regulator/core.c:regulator_force_disable
  - drivers/regulator/core.c:regulator_resolve_supply
  - drivers/regulator/core.c:set_machine_constraints
  - drivers/regulator/core.c:regulator_lock_recursive
  - drivers/regulator/core.c:regulator_unlock_recursive
```
**Symbols:**

```
ffffffff81a38570-ffffffff81a38686: regulator_unlock_recursive (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void regulator_unlock_recursive(struct regulator_dev *rdev, unsigned int n_coupled);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/regulator/core.c (ffffffff81a82140)
Location: drivers/regulator/core.c:290
Inline: False
Direct callers:
  - drivers/regulator/core.c:regulator_unregister
  - drivers/regulator/core.c:regulator_bulk_disable
  - drivers/regulator/core.c:regulator_bulk_disable
  - drivers/regulator/core.c:regulator_bulk_enable
  - drivers/regulator/core.c:regulator_bulk_enable_async
  - drivers/regulator/core.c:regulator_set_suspend_voltage
  - drivers/regulator/core.c:regulator_set_voltage
  - drivers/regulator/core.c:regulator_is_supported_voltage
  - drivers/regulator/core.c:regulator_disable_deferred
  - drivers/regulator/core.c:regulator_disable_work
  - drivers/regulator/core.c:regulator_force_disable
  - drivers/regulator/core.c:regulator_resolve_supply
  - drivers/regulator/core.c:set_machine_constraints
  - drivers/regulator/core.c:regulator_lock_recursive
  - drivers/regulator/core.c:regulator_unlock_recursive
```
**Symbols:**

```
ffffffff81a82140-ffffffff81a82256: regulator_unlock_recursive (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void regulator_unlock_recursive(struct regulator_dev *rdev, unsigned int n_coupled);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/regulator/core.c (ffffffff81ad4720)
Location: drivers/regulator/core.c:292
Inline: False
Direct callers:
  - drivers/regulator/core.c:regulator_unregister
  - drivers/regulator/core.c:regulator_bulk_disable
  - drivers/regulator/core.c:regulator_bulk_disable
  - drivers/regulator/core.c:regulator_bulk_enable
  - drivers/regulator/core.c:regulator_bulk_enable_async
  - drivers/regulator/core.c:regulator_set_suspend_voltage
  - drivers/regulator/core.c:regulator_set_voltage
  - drivers/regulator/core.c:regulator_is_supported_voltage
  - drivers/regulator/core.c:regulator_disable_deferred
  - drivers/regulator/core.c:regulator_disable_work
  - drivers/regulator/core.c:regulator_force_disable
  - drivers/regulator/core.c:regulator_resolve_supply
  - drivers/regulator/core.c:set_machine_constraints
  - drivers/regulator/core.c:regulator_lock_recursive
  - drivers/regulator/core.c:regulator_unlock_recursive
```
**Symbols:**

```
ffffffff81ad4720-ffffffff81ad4836: regulator_unlock_recursive (STB_LOCAL)
```
</details>
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
In drivers/regulator/core.c (ffff800010840a78)
Location: drivers/regulator/core.c:235
Inline: True
Direct callers:
  - drivers/regulator/core.c:regulator_get_voltage
  - drivers/regulator/core.c:regulator_set_suspend_voltage
  - drivers/regulator/core.c:regulator_set_voltage
  - drivers/regulator/core.c:regulator_disable_work
  - drivers/regulator/core.c:regulator_force_disable
  - drivers/regulator/core.c:regulator_disable
  - drivers/regulator/core.c:regulator_enable
  - drivers/regulator/core.c:regulator_lock_recursive
```
**Symbols:**

```
ffff800010840a78-ffff800010840b34: regulator_unlock_recursive.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void regulator_unlock_recursive(struct regulator_dev *rdev, unsigned int n_coupled);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/regulator/core.c (c09492d0)
Location: drivers/regulator/core.c:235
Inline: False
Direct callers:
  - drivers/regulator/core.c:regulator_get_voltage
  - drivers/regulator/core.c:regulator_set_suspend_voltage
  - drivers/regulator/core.c:regulator_set_voltage
  - drivers/regulator/core.c:regulator_disable_work
  - drivers/regulator/core.c:regulator_force_disable
  - drivers/regulator/core.c:regulator_disable
  - drivers/regulator/core.c:regulator_enable
  - drivers/regulator/core.c:regulator_lock_recursive
  - drivers/regulator/core.c:regulator_unlock_recursive
```
**Symbols:**

```
c09492d0-c094935c: regulator_unlock_recursive (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void regulator_unlock_recursive(struct regulator_dev *rdev, unsigned int n_coupled);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/regulator/core.c (c0000000008d8e60)
Location: drivers/regulator/core.c:235
Inline: False
Direct callers:
  - drivers/regulator/core.c:regulator_get_voltage
  - drivers/regulator/core.c:regulator_set_voltage
  - drivers/regulator/core.c:regulator_disable_work
  - drivers/regulator/core.c:regulator_force_disable
  - drivers/regulator/core.c:regulator_disable
  - drivers/regulator/core.c:regulator_enable
  - drivers/regulator/core.c:regulator_lock_recursive
  - drivers/regulator/core.c:regulator_unlock_recursive
```
**Symbols:**

```
c0000000008d8e60-c0000000008d8f60: regulator_unlock_recursive (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void regulator_unlock_recursive(struct regulator_dev *rdev, unsigned int n_coupled);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/regulator/core.c (ffffffe000521a62)
Location: drivers/regulator/core.c:235
Inline: False
Direct callers:
  - drivers/regulator/core.c:regulator_get_voltage
  - drivers/regulator/core.c:regulator_set_voltage
  - drivers/regulator/core.c:regulator_disable_work
  - drivers/regulator/core.c:regulator_force_disable
  - drivers/regulator/core.c:regulator_disable
  - drivers/regulator/core.c:regulator_enable
  - drivers/regulator/core.c:regulator_lock_recursive
  - drivers/regulator/core.c:regulator_unlock_recursive
```
**Symbols:**

```
ffffffe000521a62-ffffffe000521b0a: regulator_unlock_recursive (STB_LOCAL)
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
In drivers/regulator/core.c (ffffffff8163d5b0)
Location: drivers/regulator/core.c:235
Inline: True
Direct callers:
  - drivers/regulator/core.c:regulator_get_voltage
  - drivers/regulator/core.c:regulator_set_suspend_voltage
  - drivers/regulator/core.c:regulator_set_voltage
  - drivers/regulator/core.c:regulator_disable_work
  - drivers/regulator/core.c:regulator_force_disable
  - drivers/regulator/core.c:regulator_disable
  - drivers/regulator/core.c:regulator_enable
  - drivers/regulator/core.c:regulator_lock_recursive
```
**Symbols:**

```
ffffffff8163d5b0-ffffffff8163d650: regulator_unlock_recursive.isra.0 (STB_LOCAL)
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
In drivers/regulator/core.c (ffffffff8161d7a0)
Location: drivers/regulator/core.c:235
Inline: True
Direct callers:
  - drivers/regulator/core.c:regulator_get_voltage
  - drivers/regulator/core.c:regulator_set_suspend_voltage
  - drivers/regulator/core.c:regulator_set_voltage
  - drivers/regulator/core.c:regulator_disable_work
  - drivers/regulator/core.c:regulator_force_disable
  - drivers/regulator/core.c:regulator_disable
  - drivers/regulator/core.c:regulator_enable
  - drivers/regulator/core.c:regulator_lock_recursive
```
**Symbols:**

```
ffffffff8161d7a0-ffffffff8161d840: regulator_unlock_recursive.isra.0 (STB_LOCAL)
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
In drivers/regulator/core.c (ffffffff8166b700)
Location: drivers/regulator/core.c:235
Inline: True
Direct callers:
  - drivers/regulator/core.c:regulator_get_voltage
  - drivers/regulator/core.c:regulator_set_suspend_voltage
  - drivers/regulator/core.c:regulator_set_voltage
  - drivers/regulator/core.c:regulator_disable_work
  - drivers/regulator/core.c:regulator_force_disable
  - drivers/regulator/core.c:regulator_disable
  - drivers/regulator/core.c:regulator_enable
  - drivers/regulator/core.c:regulator_lock_recursive
```
**Symbols:**

```
ffffffff8166b700-ffffffff8166b7a0: regulator_unlock_recursive.isra.0 (STB_LOCAL)
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
In drivers/regulator/core.c (ffffffff81685cc0)
Location: drivers/regulator/core.c:235
Inline: True
Direct callers:
  - drivers/regulator/core.c:regulator_get_voltage
  - drivers/regulator/core.c:regulator_set_suspend_voltage
  - drivers/regulator/core.c:regulator_set_voltage
  - drivers/regulator/core.c:regulator_disable_work
  - drivers/regulator/core.c:regulator_force_disable
  - drivers/regulator/core.c:regulator_disable
  - drivers/regulator/core.c:regulator_enable
  - drivers/regulator/core.c:regulator_lock_recursive
```
**Symbols:**

```
ffffffff81685cc0-ffffffff81685d60: regulator_unlock_recursive.isra.0 (STB_LOCAL)
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
<b>Arch</b>
<ul>
</ul>
