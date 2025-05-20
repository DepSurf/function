# Function: <code>regulator_lock_dependent</code>

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
void regulator_lock_dependent(struct regulator_dev *rdev, struct ww_acquire_ctx *ww_ctx);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/regulator/core.c (ffffffff81624000)
Location: drivers/regulator/core.c:346
Inline: False
Direct callers:
  - drivers/regulator/core.c:regulator_get_voltage
  - drivers/regulator/core.c:regulator_set_suspend_voltage
  - drivers/regulator/core.c:regulator_set_voltage
  - drivers/regulator/core.c:regulator_disable_work
  - drivers/regulator/core.c:regulator_force_disable
  - drivers/regulator/core.c:regulator_disable
  - drivers/regulator/core.c:regulator_enable
```
**Symbols:**

```
ffffffff81624000-ffffffff816240f5: regulator_lock_dependent (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void regulator_lock_dependent(struct regulator_dev *rdev, struct ww_acquire_ctx *ww_ctx);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/regulator/core.c (ffffffff81656d80)
Location: drivers/regulator/core.c:328
Inline: False
Direct callers:
  - drivers/regulator/core.c:regulator_get_voltage
  - drivers/regulator/core.c:regulator_set_suspend_voltage
  - drivers/regulator/core.c:regulator_set_voltage
  - drivers/regulator/core.c:regulator_disable_work
  - drivers/regulator/core.c:regulator_force_disable
  - drivers/regulator/core.c:regulator_disable
  - drivers/regulator/core.c:regulator_enable
```
**Symbols:**

```
ffffffff81656d80-ffffffff81656e7b: regulator_lock_dependent (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void regulator_lock_dependent(struct regulator_dev *rdev, struct ww_acquire_ctx *ww_ctx);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/regulator/core.c (ffffffff8167a2c0)
Location: drivers/regulator/core.c:328
Inline: False
Direct callers:
  - drivers/regulator/core.c:regulator_get_voltage
  - drivers/regulator/core.c:regulator_set_suspend_voltage
  - drivers/regulator/core.c:regulator_set_voltage
  - drivers/regulator/core.c:regulator_disable_work
  - drivers/regulator/core.c:regulator_force_disable
  - drivers/regulator/core.c:regulator_disable
  - drivers/regulator/core.c:regulator_enable
```
**Symbols:**

```
ffffffff8167a2c0-ffffffff8167a3bb: regulator_lock_dependent (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void regulator_lock_dependent(struct regulator_dev *rdev, struct ww_acquire_ctx *ww_ctx);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/regulator/core.c (ffffffff817294b0)
Location: drivers/regulator/core.c:331
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
```
**Symbols:**

```
ffffffff817294b0-ffffffff817295ab: regulator_lock_dependent (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void regulator_lock_dependent(struct regulator_dev *rdev, struct ww_acquire_ctx *ww_ctx);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/regulator/core.c (ffffffff81746060)
Location: drivers/regulator/core.c:330
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
```
**Symbols:**

```
ffffffff81746060-ffffffff8174615b: regulator_lock_dependent (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void regulator_lock_dependent(struct regulator_dev *rdev, struct ww_acquire_ctx *ww_ctx);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/regulator/core.c (ffffffff81729a70)
Location: drivers/regulator/core.c:330
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
```
**Symbols:**

```
ffffffff81729a70-ffffffff81729b6b: regulator_lock_dependent (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void regulator_lock_dependent(struct regulator_dev *rdev, struct ww_acquire_ctx *ww_ctx);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/regulator/core.c (ffffffff817abc30)
Location: drivers/regulator/core.c:320
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
```
**Symbols:**

```
ffffffff817abc30-ffffffff817abd90: regulator_lock_dependent (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void regulator_lock_dependent(struct regulator_dev *rdev, struct ww_acquire_ctx *ww_ctx);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/regulator/core.c (ffffffff818e6990)
Location: drivers/regulator/core.c:321
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
```
**Symbols:**

```
ffffffff818e6990-ffffffff818e6afe: regulator_lock_dependent (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void regulator_lock_dependent(struct regulator_dev *rdev, struct ww_acquire_ctx *ww_ctx);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/regulator/core.c (ffffffff81a3acd0)
Location: drivers/regulator/core.c:321
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
```
**Symbols:**

```
ffffffff81a3acd0-ffffffff81a3ae3e: regulator_lock_dependent (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void regulator_lock_dependent(struct regulator_dev *rdev, struct ww_acquire_ctx *ww_ctx);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/regulator/core.c (ffffffff81a84b40)
Location: drivers/regulator/core.c:386
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
```
**Symbols:**

```
ffffffff81a84b40-ffffffff81a84cbd: regulator_lock_dependent (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void regulator_lock_dependent(struct regulator_dev *rdev, struct ww_acquire_ctx *ww_ctx);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/regulator/core.c (ffffffff81ad7320)
Location: drivers/regulator/core.c:388
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
```
**Symbols:**

```
ffffffff81ad7320-ffffffff81ad749d: regulator_lock_dependent (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: ✅</summary>

```c
void regulator_lock_dependent(struct regulator_dev *rdev, struct ww_acquire_ctx *ww_ctx);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/regulator/core.c (ffff8000108425c8)
Location: drivers/regulator/core.c:328
Inline: False
Direct callers:
  - drivers/regulator/core.c:regulator_get_voltage
  - drivers/regulator/core.c:regulator_set_suspend_voltage
  - drivers/regulator/core.c:regulator_set_voltage
  - drivers/regulator/core.c:regulator_disable_work
  - drivers/regulator/core.c:regulator_force_disable
  - drivers/regulator/core.c:regulator_disable
  - drivers/regulator/core.c:regulator_enable
```
**Symbols:**

```
ffff8000108425c8-ffff8000108426dc: regulator_lock_dependent (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void regulator_lock_dependent(struct regulator_dev *rdev, struct ww_acquire_ctx *ww_ctx);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/regulator/core.c (c094d138)
Location: drivers/regulator/core.c:328
Inline: False
Direct callers:
  - drivers/regulator/core.c:regulator_get_voltage
  - drivers/regulator/core.c:regulator_set_suspend_voltage
  - drivers/regulator/core.c:regulator_set_voltage
  - drivers/regulator/core.c:regulator_disable_work
  - drivers/regulator/core.c:regulator_force_disable
  - drivers/regulator/core.c:regulator_disable
  - drivers/regulator/core.c:regulator_enable
```
**Symbols:**

```
c094d138-c094d258: regulator_lock_dependent (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void regulator_lock_dependent(struct regulator_dev *rdev, struct ww_acquire_ctx *ww_ctx);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/regulator/core.c (c0000000008de580)
Location: drivers/regulator/core.c:328
Inline: False
Direct callers:
  - drivers/regulator/core.c:regulator_get_voltage
  - drivers/regulator/core.c:regulator_set_voltage
  - drivers/regulator/core.c:regulator_disable_work
  - drivers/regulator/core.c:regulator_force_disable
  - drivers/regulator/core.c:regulator_disable
  - drivers/regulator/core.c:regulator_enable
```
**Symbols:**

```
c0000000008de580-c0000000008de6e0: regulator_lock_dependent (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void regulator_lock_dependent(struct regulator_dev *rdev, struct ww_acquire_ctx *ww_ctx);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/regulator/core.c (ffffffe0005248fa)
Location: drivers/regulator/core.c:328
Inline: False
Direct callers:
  - drivers/regulator/core.c:regulator_get_voltage
  - drivers/regulator/core.c:regulator_set_voltage
  - drivers/regulator/core.c:regulator_disable_work
  - drivers/regulator/core.c:regulator_force_disable
  - drivers/regulator/core.c:regulator_disable
  - drivers/regulator/core.c:regulator_enable
```
**Symbols:**

```
ffffffe0005248fa-ffffffe0005249d0: regulator_lock_dependent (STB_LOCAL)
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
void regulator_lock_dependent(struct regulator_dev *rdev, struct ww_acquire_ctx *ww_ctx);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/regulator/core.c (ffffffff8163fdc0)
Location: drivers/regulator/core.c:328
Inline: False
Direct callers:
  - drivers/regulator/core.c:regulator_get_voltage
  - drivers/regulator/core.c:regulator_set_suspend_voltage
  - drivers/regulator/core.c:regulator_set_voltage
  - drivers/regulator/core.c:regulator_disable_work
  - drivers/regulator/core.c:regulator_force_disable
  - drivers/regulator/core.c:regulator_disable
  - drivers/regulator/core.c:regulator_enable
```
**Symbols:**

```
ffffffff8163fdc0-ffffffff8163febb: regulator_lock_dependent (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void regulator_lock_dependent(struct regulator_dev *rdev, struct ww_acquire_ctx *ww_ctx);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/regulator/core.c (ffffffff816201a0)
Location: drivers/regulator/core.c:328
Inline: False
Direct callers:
  - drivers/regulator/core.c:regulator_get_voltage
  - drivers/regulator/core.c:regulator_set_suspend_voltage
  - drivers/regulator/core.c:regulator_set_voltage
  - drivers/regulator/core.c:regulator_disable_work
  - drivers/regulator/core.c:regulator_force_disable
  - drivers/regulator/core.c:regulator_disable
  - drivers/regulator/core.c:regulator_enable
```
**Symbols:**

```
ffffffff816201a0-ffffffff8162029b: regulator_lock_dependent (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void regulator_lock_dependent(struct regulator_dev *rdev, struct ww_acquire_ctx *ww_ctx);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/regulator/core.c (ffffffff8166e100)
Location: drivers/regulator/core.c:328
Inline: False
Direct callers:
  - drivers/regulator/core.c:regulator_get_voltage
  - drivers/regulator/core.c:regulator_set_suspend_voltage
  - drivers/regulator/core.c:regulator_set_voltage
  - drivers/regulator/core.c:regulator_disable_work
  - drivers/regulator/core.c:regulator_force_disable
  - drivers/regulator/core.c:regulator_disable
  - drivers/regulator/core.c:regulator_enable
```
**Symbols:**

```
ffffffff8166e100-ffffffff8166e1fb: regulator_lock_dependent (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void regulator_lock_dependent(struct regulator_dev *rdev, struct ww_acquire_ctx *ww_ctx);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/regulator/core.c (ffffffff81688760)
Location: drivers/regulator/core.c:328
Inline: False
Direct callers:
  - drivers/regulator/core.c:regulator_get_voltage
  - drivers/regulator/core.c:regulator_set_suspend_voltage
  - drivers/regulator/core.c:regulator_set_voltage
  - drivers/regulator/core.c:regulator_disable_work
  - drivers/regulator/core.c:regulator_force_disable
  - drivers/regulator/core.c:regulator_disable
  - drivers/regulator/core.c:regulator_enable
```
**Symbols:**

```
ffffffff81688760-ffffffff8168885b: regulator_lock_dependent (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>5.0</code> and <code>5.3</code> ✅
</li>
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
