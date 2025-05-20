# Function: <code>class_for_each_device</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline ⚠️</summary>

```c
int class_for_each_device(struct class *class, struct device *start, void *data, int (*fn)(struct device *, void *));
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/class.c (ffffffff8154d0d0)
Location: drivers/base/class.c:365
Inline: True
Direct callers:
  - drivers/regulator/core.c:regulator_suspend_prepare
  - drivers/regulator/core.c:regulator_suspend_finish
  - drivers/regulator/core.c:regulator_init_complete
  - drivers/regulator/core.c:regulator_summary_show
  - drivers/regulator/core.c:regulator_summary_show_subtree
  - drivers/base/devcoredump.c:disabled_store
  - drivers/base/devcoredump.c:devcoredump_exit
  - drivers/power/power_supply_core.c:power_supply_am_i_supplied
  - drivers/power/power_supply_core.c:power_supply_is_system_supplied
  - drivers/power/power_supply_core.c:power_supply_changed_work
```
**Symbols:**

```
ffffffff8154d0d0-ffffffff8154d1bb: class_for_each_device (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
int class_for_each_device(struct class *class, struct device *start, void *data, int (*fn)(struct device *, void *));
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/class.c (ffffffff8159eec0)
Location: drivers/base/class.c:365
Inline: True
Direct callers:
  - drivers/regulator/core.c:regulator_init_complete
  - drivers/regulator/core.c:regulator_summary_show
  - drivers/regulator/core.c:regulator_summary_show_subtree
  - drivers/regulator/core.c:regulator_suspend_finish
  - drivers/regulator/core.c:regulator_suspend_prepare
  - drivers/base/devcoredump.c:devcoredump_exit
  - drivers/base/devcoredump.c:disabled_store
  - drivers/power/power_supply_core.c:power_supply_is_system_supplied
  - drivers/power/power_supply_core.c:power_supply_am_i_supplied
  - drivers/power/power_supply_core.c:power_supply_changed_work
```
**Symbols:**

```
ffffffff8159eec0-ffffffff8159efab: class_for_each_device (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
int class_for_each_device(struct class *class, struct device *start, void *data, int (*fn)(struct device *, void *));
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/class.c (ffffffff815cd480)
Location: drivers/base/class.c:380
Inline: True
Direct callers:
  - drivers/regulator/core.c:regulator_init_complete
  - drivers/regulator/core.c:regulator_summary_show
  - drivers/regulator/core.c:regulator_summary_show_subtree
  - drivers/regulator/core.c:regulator_suspend_finish
  - drivers/regulator/core.c:regulator_suspend_prepare
  - drivers/base/devcoredump.c:devcoredump_exit
  - drivers/base/devcoredump.c:disabled_store
  - drivers/power/supply/power_supply_core.c:power_supply_is_system_supplied
  - drivers/power/supply/power_supply_core.c:power_supply_am_i_supplied
  - drivers/power/supply/power_supply_core.c:power_supply_changed_work
```
**Symbols:**

```
ffffffff815cd480-ffffffff815cd56b: class_for_each_device (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
int class_for_each_device(struct class *class, struct device *start, void *data, int (*fn)(struct device *, void *));
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/class.c (ffffffff815e1f80)
Location: drivers/base/class.c:347
Inline: True
Direct callers:
  - drivers/regulator/core.c:regulator_init_complete
  - drivers/regulator/core.c:regulator_init_complete
  - drivers/regulator/core.c:regulator_summary_show
  - drivers/regulator/core.c:regulator_summary_show_subtree
  - drivers/regulator/core.c:regulator_suspend_finish
  - drivers/regulator/core.c:regulator_suspend_prepare
  - drivers/base/devcoredump.c:devcoredump_exit
  - drivers/base/devcoredump.c:disabled_store
  - drivers/power/supply/power_supply_core.c:power_supply_is_system_supplied
  - drivers/power/supply/power_supply_core.c:power_supply_am_i_supplied
  - drivers/power/supply/power_supply_core.c:power_supply_changed_work
```
**Symbols:**

```
ffffffff815e1f80-ffffffff815e206a: class_for_each_device (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
int class_for_each_device(struct class *class, struct device *start, void *data, int (*fn)(struct device *, void *));
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/class.c (ffffffff816490f0)
Location: drivers/base/class.c:347
Inline: True
Direct callers:
  - drivers/regulator/core.c:regulator_init_complete
  - drivers/regulator/core.c:regulator_init_complete
  - drivers/regulator/core.c:regulator_summary_show
  - drivers/regulator/core.c:regulator_summary_show_subtree
  - drivers/regulator/core.c:regulator_suspend_finish
  - drivers/regulator/core.c:regulator_suspend_prepare
  - drivers/base/devcoredump.c:devcoredump_exit
  - drivers/base/devcoredump.c:disabled_store
  - drivers/power/supply/power_supply_core.c:power_supply_set_input_current_limit_from_supplier
  - drivers/power/supply/power_supply_core.c:power_supply_is_system_supplied
  - drivers/power/supply/power_supply_core.c:power_supply_am_i_supplied
  - drivers/power/supply/power_supply_core.c:power_supply_changed_work
```
**Symbols:**

```
ffffffff816490f0-ffffffff816491dc: class_for_each_device (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
int class_for_each_device(struct class *class, struct device *start, void *data, int (*fn)(struct device *, void *));
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/class.c (ffffffff816846b0)
Location: drivers/base/class.c:345
Inline: True
Direct callers:
  - drivers/regulator/core.c:regulator_init_complete
  - drivers/regulator/core.c:regulator_init_complete
  - drivers/regulator/core.c:regulator_init_complete
  - drivers/regulator/core.c:regulator_summary_show
  - drivers/regulator/core.c:regulator_summary_show_subtree
  - drivers/regulator/core.c:regulator_resume_early
  - drivers/regulator/core.c:regulator_suspend_late
  - drivers/base/devcoredump.c:devcoredump_exit
  - drivers/base/devcoredump.c:disabled_store
  - drivers/power/supply/power_supply_core.c:power_supply_set_input_current_limit_from_supplier
  - drivers/power/supply/power_supply_core.c:power_supply_is_system_supplied
  - drivers/power/supply/power_supply_core.c:power_supply_am_i_supplied
  - drivers/power/supply/power_supply_core.c:power_supply_changed_work
```
**Symbols:**

```
ffffffff816846b0-ffffffff81684793: class_for_each_device (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
int class_for_each_device(struct class *class, struct device *start, void *data, int (*fn)(struct device *, void *));
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/class.c (ffffffff816a4370)
Location: drivers/base/class.c:345
Inline: True
Direct callers:
  - drivers/regulator/core.c:regulator_init_complete
  - drivers/regulator/core.c:regulator_init_complete
  - drivers/regulator/core.c:regulator_summary_show
  - drivers/regulator/core.c:regulator_summary_show
  - drivers/regulator/core.c:regulator_summary_show
  - drivers/regulator/core.c:regulator_summary_show
  - drivers/regulator/core.c:regulator_summary_show_subtree
  - drivers/regulator/core.c:regulator_register
  - drivers/base/devcoredump.c:devcoredump_exit
  - drivers/base/devcoredump.c:disabled_store
  - drivers/power/supply/power_supply_core.c:power_supply_set_input_current_limit_from_supplier
  - drivers/power/supply/power_supply_core.c:power_supply_is_system_supplied
  - drivers/power/supply/power_supply_core.c:power_supply_am_i_supplied
  - drivers/power/supply/power_supply_core.c:power_supply_changed_work
```
**Symbols:**

```
ffffffff816a4370-ffffffff816a4451: class_for_each_device (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
int class_for_each_device(struct class *class, struct device *start, void *data, int (*fn)(struct device *, void *));
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/class.c (ffffffff816dd280)
Location: drivers/base/class.c:351
Inline: True
Direct callers:
  - drivers/regulator/core.c:regulator_init_complete
  - drivers/regulator/core.c:regulator_init_complete
  - drivers/regulator/core.c:regulator_summary_show
  - drivers/regulator/core.c:regulator_summary_show
  - drivers/regulator/core.c:regulator_summary_show
  - drivers/regulator/core.c:regulator_summary_show
  - drivers/regulator/core.c:regulator_summary_show_subtree
  - drivers/regulator/core.c:regulator_register
  - drivers/base/devcoredump.c:devcoredump_exit
  - drivers/base/devcoredump.c:disabled_store
  - drivers/power/supply/power_supply_core.c:power_supply_set_input_current_limit_from_supplier
  - drivers/power/supply/power_supply_core.c:power_supply_is_system_supplied
  - drivers/power/supply/power_supply_core.c:power_supply_am_i_supplied
  - drivers/power/supply/power_supply_core.c:power_supply_changed_work
```
**Symbols:**

```
ffffffff816dd280-ffffffff816dd368: class_for_each_device (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
int class_for_each_device(struct class *class, struct device *start, void *data, int (*fn)(struct device *, void *));
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/class.c (ffffffff81701330)
Location: drivers/base/class.c:351
Inline: True
Direct callers:
  - drivers/regulator/core.c:regulator_init_complete_work_function
  - drivers/regulator/core.c:regulator_init_complete_work_function
  - drivers/regulator/core.c:regulator_summary_show
  - drivers/regulator/core.c:regulator_summary_show
  - drivers/regulator/core.c:regulator_summary_show
  - drivers/regulator/core.c:regulator_summary_show
  - drivers/regulator/core.c:regulator_summary_show_subtree
  - drivers/regulator/core.c:regulator_register
  - drivers/base/devcoredump.c:devcoredump_exit
  - drivers/base/devcoredump.c:disabled_store
  - drivers/power/supply/power_supply_core.c:power_supply_set_input_current_limit_from_supplier
  - drivers/power/supply/power_supply_core.c:power_supply_is_system_supplied
  - drivers/power/supply/power_supply_core.c:power_supply_am_i_supplied
  - drivers/power/supply/power_supply_core.c:power_supply_changed_work
```
**Symbols:**

```
ffffffff81701330-ffffffff81701418: class_for_each_device (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int class_for_each_device(struct class *class, struct device *start, void *data, int (*fn)(struct device *, void *));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/class.c (ffffffff817bb2e0)
Location: drivers/base/class.c:352
Inline: False
Direct callers:
  - drivers/regulator/core.c:regulator_init_complete_work_function
  - drivers/regulator/core.c:regulator_init_complete_work_function
  - drivers/regulator/core.c:regulator_summary_show
  - drivers/regulator/core.c:regulator_summary_show
  - drivers/regulator/core.c:regulator_summary_lock
  - drivers/regulator/core.c:regulator_summary_lock
  - drivers/regulator/core.c:regulator_register
  - drivers/base/devcoredump.c:devcoredump_exit
  - drivers/base/devcoredump.c:disabled_store
  - drivers/power/supply/power_supply_core.c:power_supply_set_input_current_limit_from_supplier
  - drivers/power/supply/power_supply_core.c:power_supply_is_system_supplied
  - drivers/power/supply/power_supply_core.c:power_supply_am_i_supplied
  - drivers/power/supply/power_supply_core.c:power_supply_changed_work
```
**Symbols:**

```
ffffffff817bb2e0-ffffffff817bb3d3: class_for_each_device (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int class_for_each_device(struct class *class, struct device *start, void *data, int (*fn)(struct device *, void *));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/class.c (ffffffff817cfed0)
Location: drivers/base/class.c:352
Inline: False
Direct callers:
  - drivers/regulator/core.c:regulator_init_complete_work_function
  - drivers/regulator/core.c:regulator_init_complete_work_function
  - drivers/regulator/core.c:regulator_summary_show
  - drivers/regulator/core.c:regulator_summary_show
  - drivers/regulator/core.c:regulator_summary_lock
  - drivers/regulator/core.c:regulator_summary_lock
  - drivers/regulator/core.c:regulator_register
  - drivers/base/devcoredump.c:devcoredump_exit
  - drivers/base/devcoredump.c:disabled_store
  - drivers/power/supply/power_supply_core.c:power_supply_set_input_current_limit_from_supplier
  - drivers/power/supply/power_supply_core.c:power_supply_is_system_supplied
  - drivers/power/supply/power_supply_core.c:power_supply_am_i_supplied
  - drivers/power/supply/power_supply_core.c:power_supply_changed_work
```
**Symbols:**

```
ffffffff817cfed0-ffffffff817cffc3: class_for_each_device (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int class_for_each_device(struct class *class, struct device *start, void *data, int (*fn)(struct device *, void *));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/class.c (ffffffff817b38e0)
Location: drivers/base/class.c:352
Inline: False
Direct callers:
  - drivers/regulator/core.c:regulator_init_complete_work_function
  - drivers/regulator/core.c:regulator_init_complete_work_function
  - drivers/regulator/core.c:regulator_summary_show
  - drivers/regulator/core.c:regulator_summary_show
  - drivers/regulator/core.c:regulator_summary_show
  - drivers/regulator/core.c:regulator_summary_show
  - drivers/regulator/core.c:regulator_register
  - drivers/base/core.c:fw_devlink_drivers_done
  - drivers/base/devcoredump.c:devcoredump_exit
  - drivers/base/devcoredump.c:disabled_store
  - drivers/power/supply/power_supply_core.c:power_supply_set_input_current_limit_from_supplier
  - drivers/power/supply/power_supply_core.c:power_supply_is_system_supplied
  - drivers/power/supply/power_supply_core.c:power_supply_am_i_supplied
  - drivers/power/supply/power_supply_core.c:power_supply_changed_work
```
**Symbols:**

```
ffffffff817b38e0-ffffffff817b39e0: class_for_each_device (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int class_for_each_device(struct class *class, struct device *start, void *data, int (*fn)(struct device *, void *));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/class.c (ffffffff8183cdc0)
Location: drivers/base/class.c:352
Inline: False
Direct callers:
  - drivers/regulator/core.c:regulator_init_complete_work_function
  - drivers/regulator/core.c:regulator_init_complete_work_function
  - drivers/regulator/core.c:regulator_summary_show
  - drivers/regulator/core.c:regulator_summary_show
  - drivers/regulator/core.c:regulator_summary_show
  - drivers/regulator/core.c:regulator_summary_show
  - drivers/regulator/core.c:regulator_register
  - drivers/base/core.c:fw_devlink_drivers_done
  - drivers/base/devcoredump.c:devcoredump_exit
  - drivers/base/devcoredump.c:disabled_store
  - drivers/power/supply/power_supply_core.c:power_supply_set_input_current_limit_from_supplier
  - drivers/power/supply/power_supply_core.c:power_supply_is_system_supplied
  - drivers/power/supply/power_supply_core.c:power_supply_am_i_supplied
  - drivers/power/supply/power_supply_core.c:power_supply_changed_work
```
**Symbols:**

```
ffffffff8183cdc0-ffffffff8183cec0: class_for_each_device (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int class_for_each_device(struct class *class, struct device *start, void *data, int (*fn)(struct device *, void *));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/class.c (ffffffff8197f950)
Location: drivers/base/class.c:352
Inline: False
Direct callers:
  - drivers/regulator/core.c:regulator_init_complete_work_function
  - drivers/regulator/core.c:regulator_init_complete_work_function
  - drivers/regulator/core.c:regulator_summary_show
  - drivers/regulator/core.c:regulator_summary_show
  - drivers/regulator/core.c:regulator_summary_show
  - drivers/regulator/core.c:regulator_summary_show
  - drivers/regulator/core.c:regulator_summary_show_subtree
  - drivers/regulator/core.c:regulator_register
  - drivers/base/core.c:fw_devlink_drivers_done
  - drivers/base/devcoredump.c:devcoredump_exit
  - drivers/base/devcoredump.c:disabled_store
  - drivers/power/supply/power_supply_core.c:power_supply_get_property_from_supplier
  - drivers/power/supply/power_supply_core.c:power_supply_is_system_supplied
  - drivers/power/supply/power_supply_core.c:power_supply_am_i_supplied
  - drivers/power/supply/power_supply_core.c:power_supply_changed_work
```
**Symbols:**

```
ffffffff8197f950-ffffffff8197fa6e: class_for_each_device (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int class_for_each_device(struct class *class, struct device *start, void *data, int (*fn)(struct device *, void *));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/class.c (ffffffff81aed250)
Location: drivers/base/class.c:357
Inline: False
Direct callers:
  - drivers/regulator/core.c:regulator_init_complete_work_function
  - drivers/regulator/core.c:regulator_init_complete_work_function
  - drivers/regulator/core.c:regulator_summary_show
  - drivers/regulator/core.c:regulator_summary_show
  - drivers/regulator/core.c:regulator_summary_show
  - drivers/regulator/core.c:regulator_summary_show
  - drivers/regulator/core.c:regulator_summary_show_subtree
  - drivers/regulator/core.c:regulator_register
  - drivers/base/core.c:fw_devlink_drivers_done
  - drivers/base/devcoredump.c:devcoredump_exit
  - drivers/base/devcoredump.c:disabled_store
  - drivers/power/supply/power_supply_core.c:power_supply_get_property_from_supplier
  - drivers/power/supply/power_supply_core.c:power_supply_is_system_supplied
  - drivers/power/supply/power_supply_core.c:power_supply_am_i_supplied
  - drivers/power/supply/power_supply_core.c:power_supply_changed_work
```
**Symbols:**

```
ffffffff81aed250-ffffffff81aed36e: class_for_each_device (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int class_for_each_device(const struct class *class, const struct device *start, void *data, int (*fn)(struct device *, void *));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/class.c (ffffffff81b3b4a0)
Location: drivers/base/class.c:387
Inline: False
Direct callers:
  - drivers/regulator/core.c:regulator_init_complete_work_function
  - drivers/regulator/core.c:regulator_init_complete_work_function
  - drivers/regulator/core.c:regulator_summary_show
  - drivers/regulator/core.c:regulator_summary_show
  - drivers/regulator/core.c:regulator_summary_show
  - drivers/regulator/core.c:regulator_summary_show
  - drivers/regulator/core.c:regulator_summary_show_subtree
  - drivers/regulator/core.c:regulator_register
  - drivers/base/core.c:fw_devlink_probing_done
  - drivers/base/core.c:fw_devlink_drivers_done
  - drivers/base/devcoredump.c:devcoredump_exit
  - drivers/base/devcoredump.c:disabled_store
  - drivers/power/supply/power_supply_core.c:power_supply_get_property_from_supplier
  - drivers/power/supply/power_supply_core.c:power_supply_is_system_supplied
  - drivers/power/supply/power_supply_core.c:power_supply_am_i_supplied
  - drivers/power/supply/power_supply_core.c:power_supply_changed_work
```
**Symbols:**

```
ffffffff81b3b4a0-ffffffff81b3b619: class_for_each_device (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int class_for_each_device(const struct class *class, const struct device *start, void *data, int (*fn)(struct device *, void *));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/class.c (ffffffff81b92ff0)
Location: drivers/base/class.c:386
Inline: False
Direct callers:
  - drivers/regulator/core.c:regulator_summary_show
  - drivers/regulator/core.c:regulator_summary_show
  - drivers/regulator/core.c:regulator_summary_show
  - drivers/regulator/core.c:regulator_summary_show
  - drivers/regulator/core.c:regulator_summary_show_subtree
  - drivers/regulator/core.c:regulator_register
  - drivers/base/core.c:fw_devlink_probing_done
  - drivers/base/core.c:fw_devlink_drivers_done
  - drivers/base/devcoredump.c:devcoredump_exit
  - drivers/base/devcoredump.c:disabled_store
  - drivers/power/supply/power_supply_core.c:power_supply_get_property_from_supplier
  - drivers/power/supply/power_supply_core.c:power_supply_is_system_supplied
  - drivers/power/supply/power_supply_core.c:power_supply_am_i_supplied
  - drivers/power/supply/power_supply_core.c:power_supply_changed_work
```
**Symbols:**

```
ffffffff81b92ff0-ffffffff81b93169: class_for_each_device (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Selective Inline ⚠️</summary>

```c
int class_for_each_device(struct class *class, struct device *start, void *data, int (*fn)(struct device *, void *));
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/class.c (ffff8000108ecbc0)
Location: drivers/base/class.c:351
Inline: True
Direct callers:
  - drivers/regulator/core.c:regulator_init_complete_work_function
  - drivers/regulator/core.c:regulator_init_complete_work_function
  - drivers/regulator/core.c:regulator_summary_show
  - drivers/regulator/core.c:regulator_summary_show
  - drivers/regulator/core.c:regulator_summary_show
  - drivers/regulator/core.c:regulator_summary_show
  - drivers/regulator/core.c:regulator_summary_show_subtree
  - drivers/regulator/core.c:regulator_register
  - drivers/base/devcoredump.c:devcoredump_exit
  - drivers/base/devcoredump.c:disabled_store
  - drivers/power/supply/power_supply_core.c:power_supply_set_input_current_limit_from_supplier
  - drivers/power/supply/power_supply_core.c:power_supply_is_system_supplied
  - drivers/power/supply/power_supply_core.c:power_supply_am_i_supplied
  - drivers/power/supply/power_supply_core.c:power_supply_changed_work
```
**Symbols:**

```
ffff8000108ecbc0-ffff8000108eccb4: class_for_each_device (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
int class_for_each_device(struct class *class, struct device *start, void *data, int (*fn)(struct device *, void *));
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/class.c (c09daa34)
Location: drivers/base/class.c:351
Inline: True
Direct callers:
  - drivers/regulator/core.c:regulator_init_complete_work_function
  - drivers/regulator/core.c:regulator_init_complete_work_function
  - drivers/regulator/core.c:regulator_summary_show
  - drivers/regulator/core.c:regulator_summary_show
  - drivers/regulator/core.c:regulator_summary_show
  - drivers/regulator/core.c:regulator_summary_show
  - drivers/regulator/core.c:regulator_summary_show_subtree
  - drivers/regulator/core.c:regulator_register
  - drivers/base/devcoredump.c:devcoredump_exit
  - drivers/base/devcoredump.c:disabled_store
  - drivers/power/supply/power_supply_core.c:power_supply_set_input_current_limit_from_supplier
  - drivers/power/supply/power_supply_core.c:power_supply_is_system_supplied
  - drivers/power/supply/power_supply_core.c:power_supply_am_i_supplied
  - drivers/power/supply/power_supply_core.c:power_supply_changed_work
```
**Symbols:**

```
c09daa34-c09dab34: class_for_each_device (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
int class_for_each_device(struct class *class, struct device *start, void *data, int (*fn)(struct device *, void *));
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/class.c (c0000000009846a0)
Location: drivers/base/class.c:351
Inline: True
Direct callers:
  - drivers/regulator/core.c:regulator_init_complete_work_function
  - drivers/regulator/core.c:regulator_init_complete_work_function
  - drivers/regulator/core.c:regulator_summary_show
  - drivers/regulator/core.c:regulator_summary_show
  - drivers/regulator/core.c:regulator_summary_show
  - drivers/regulator/core.c:regulator_summary_show
  - drivers/regulator/core.c:regulator_summary_show_subtree
  - drivers/regulator/core.c:regulator_register
  - drivers/base/devcoredump.c:devcoredump_exit
  - drivers/base/devcoredump.c:disabled_store
  - drivers/power/supply/power_supply_core.c:power_supply_set_input_current_limit_from_supplier
  - drivers/power/supply/power_supply_core.c:power_supply_is_system_supplied
  - drivers/power/supply/power_supply_core.c:power_supply_am_i_supplied
  - drivers/power/supply/power_supply_core.c:power_supply_changed_work
```
**Symbols:**

```
c0000000009846a0-c0000000009847f0: class_for_each_device (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
int class_for_each_device(struct class *class, struct device *start, void *data, int (*fn)(struct device *, void *));
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/class.c (ffffffe00057fe30)
Location: drivers/base/class.c:351
Inline: True
Direct callers:
  - drivers/regulator/core.c:regulator_init_complete_work_function
  - drivers/regulator/core.c:regulator_init_complete_work_function
  - drivers/regulator/core.c:regulator_summary_show
  - drivers/regulator/core.c:regulator_summary_show
  - drivers/regulator/core.c:regulator_summary_show
  - drivers/regulator/core.c:regulator_summary_show
  - drivers/regulator/core.c:regulator_summary_show_subtree
  - drivers/regulator/core.c:regulator_register
  - drivers/base/devcoredump.c:devcoredump_exit
  - drivers/base/devcoredump.c:disabled_store
  - drivers/power/supply/power_supply_core.c:power_supply_set_input_current_limit_from_supplier
  - drivers/power/supply/power_supply_core.c:power_supply_is_system_supplied
  - drivers/power/supply/power_supply_core.c:power_supply_am_i_supplied
  - drivers/power/supply/power_supply_core.c:power_supply_changed_work
```
**Symbols:**

```
ffffffe00057fe30-ffffffe00057fed8: class_for_each_device (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Selective Inline ⚠️</summary>

```c
int class_for_each_device(struct class *class, struct device *start, void *data, int (*fn)(struct device *, void *));
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/class.c (ffffffff816c6b20)
Location: drivers/base/class.c:351
Inline: True
Direct callers:
  - drivers/regulator/core.c:regulator_init_complete_work_function
  - drivers/regulator/core.c:regulator_init_complete_work_function
  - drivers/regulator/core.c:regulator_summary_show
  - drivers/regulator/core.c:regulator_summary_show
  - drivers/regulator/core.c:regulator_summary_show
  - drivers/regulator/core.c:regulator_summary_show
  - drivers/regulator/core.c:regulator_summary_show_subtree
  - drivers/regulator/core.c:regulator_register
  - drivers/base/devcoredump.c:devcoredump_exit
  - drivers/base/devcoredump.c:disabled_store
  - drivers/power/supply/power_supply_core.c:power_supply_set_input_current_limit_from_supplier
  - drivers/power/supply/power_supply_core.c:power_supply_is_system_supplied
  - drivers/power/supply/power_supply_core.c:power_supply_am_i_supplied
  - drivers/power/supply/power_supply_core.c:power_supply_changed_work
```
**Symbols:**

```
ffffffff816c6b20-ffffffff816c6c08: class_for_each_device (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
int class_for_each_device(struct class *class, struct device *start, void *data, int (*fn)(struct device *, void *));
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/class.c (ffffffff816a1d80)
Location: drivers/base/class.c:351
Inline: True
Direct callers:
  - drivers/regulator/core.c:regulator_init_complete_work_function
  - drivers/regulator/core.c:regulator_init_complete_work_function
  - drivers/regulator/core.c:regulator_summary_show
  - drivers/regulator/core.c:regulator_summary_show
  - drivers/regulator/core.c:regulator_summary_show
  - drivers/regulator/core.c:regulator_summary_show
  - drivers/regulator/core.c:regulator_summary_show_subtree
  - drivers/regulator/core.c:regulator_register
  - drivers/power/supply/power_supply_core.c:power_supply_set_input_current_limit_from_supplier
  - drivers/power/supply/power_supply_core.c:power_supply_is_system_supplied
  - drivers/power/supply/power_supply_core.c:power_supply_am_i_supplied
  - drivers/power/supply/power_supply_core.c:power_supply_changed_work
```
**Symbols:**

```
ffffffff816a1d80-ffffffff816a1e68: class_for_each_device (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
int class_for_each_device(struct class *class, struct device *start, void *data, int (*fn)(struct device *, void *));
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/class.c (ffffffff816f4ff0)
Location: drivers/base/class.c:351
Inline: True
Direct callers:
  - drivers/regulator/core.c:regulator_init_complete_work_function
  - drivers/regulator/core.c:regulator_init_complete_work_function
  - drivers/regulator/core.c:regulator_summary_show
  - drivers/regulator/core.c:regulator_summary_show
  - drivers/regulator/core.c:regulator_summary_show
  - drivers/regulator/core.c:regulator_summary_show
  - drivers/regulator/core.c:regulator_summary_show_subtree
  - drivers/regulator/core.c:regulator_register
  - drivers/base/devcoredump.c:devcoredump_exit
  - drivers/base/devcoredump.c:disabled_store
  - drivers/power/supply/power_supply_core.c:power_supply_set_input_current_limit_from_supplier
  - drivers/power/supply/power_supply_core.c:power_supply_is_system_supplied
  - drivers/power/supply/power_supply_core.c:power_supply_am_i_supplied
  - drivers/power/supply/power_supply_core.c:power_supply_changed_work
```
**Symbols:**

```
ffffffff816f4ff0-ffffffff816f50d8: class_for_each_device (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
int class_for_each_device(struct class *class, struct device *start, void *data, int (*fn)(struct device *, void *));
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/class.c (ffffffff8170f880)
Location: drivers/base/class.c:351
Inline: True
Direct callers:
  - drivers/regulator/core.c:regulator_init_complete_work_function
  - drivers/regulator/core.c:regulator_init_complete_work_function
  - drivers/regulator/core.c:regulator_summary_show
  - drivers/regulator/core.c:regulator_summary_show
  - drivers/regulator/core.c:regulator_summary_show
  - drivers/regulator/core.c:regulator_summary_show
  - drivers/regulator/core.c:regulator_summary_show_subtree
  - drivers/regulator/core.c:regulator_register
  - drivers/base/devcoredump.c:devcoredump_exit
  - drivers/base/devcoredump.c:disabled_store
  - drivers/power/supply/power_supply_core.c:power_supply_set_input_current_limit_from_supplier
  - drivers/power/supply/power_supply_core.c:power_supply_is_system_supplied
  - drivers/power/supply/power_supply_core.c:power_supply_am_i_supplied
  - drivers/power/supply/power_supply_core.c:power_supply_changed_work
```
**Symbols:**

```
ffffffff8170f880-ffffffff8170f968: class_for_each_device (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>4.4</code> and <code>4.8</code> ✅
</li>
<li>
No changes between <code>4.8</code> and <code>4.10</code> ✅
</li>
<li>
No changes between <code>4.10</code> and <code>4.13</code> ✅
</li>
<li>
No changes between <code>4.13</code> and <code>4.15</code> ✅
</li>
<li>
No changes between <code>4.15</code> and <code>4.18</code> ✅
</li>
<li>
No changes between <code>4.18</code> and <code>5.0</code> ✅
</li>
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
<details>
<summary>Changed between <code>6.2</code> and <code>6.5</code> ⚠️</summary>
<ul>
<li>
<b>Param type changed. </b>
<code>struct class *class</code> ➡️ <code>const struct class *class</code>
</li>
<li>
<b>Param type changed. </b>
<code>struct device *start</code> ➡️ <code>const struct device *start</code>
</li>
</ul>
</details>
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
