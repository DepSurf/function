# Function: <code>clk_prepare_unlock</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline ⚠️</summary>

```c
void clk_prepare_unlock();
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/clk/clk.c (ffffffff816e5700)
Location: drivers/clk/clk.c:106
Inline: True
Direct callers:
  - drivers/clk/clk.c:clk_prepare
  - drivers/clk/clk.c:clk_round_rate
  - drivers/clk/clk.c:clk_core_get_accuracy
  - drivers/clk/clk.c:clk_core_get_accuracy
  - drivers/clk/clk.c:clk_get_parent
  - drivers/clk/clk.c:clk_get_parent
  - drivers/clk/clk.c:clk_set_phase
  - drivers/clk/clk.c:clk_get_phase
  - drivers/clk/clk.c:clk_core_get_rate
  - drivers/clk/clk.c:clk_core_get_rate
  - drivers/clk/clk.c:clk_summary_show_subtree
  - drivers/clk/clk.c:clk_summary_show
  - drivers/clk/clk.c:clk_notifier_unregister
  - drivers/clk/clk.c:clk_dump_subtree
  - drivers/clk/clk.c:clk_dump
  - drivers/clk/clk.c:clk_notifier_register
  - drivers/clk/clk.c:clk_core_set_parent
  - drivers/clk/clk.c:clk_unregister
  - drivers/clk/clk.c:clk_disable_unused
  - drivers/clk/clk.c:clk_set_rate
  - drivers/clk/clk.c:__clk_create_clk
  - drivers/clk/clk.c:__clk_free_clk
  - drivers/clk/clk.c:clk_register
  - drivers/clk/clk.c:clk_register
  - drivers/clk/clk.c:__clk_put
```
**Symbols:**

```
ffffffff816e5700-ffffffff816e57a5: clk_prepare_unlock (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
void clk_prepare_unlock();
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/clk/clk.c (ffffffff8174a5c0)
Location: drivers/clk/clk.c:106
Inline: True
Direct callers:
  - drivers/clk/clk.c:clk_notifier_unregister
  - drivers/clk/clk.c:clk_notifier_register
  - drivers/clk/clk.c:__clk_put
  - drivers/clk/clk.c:clk_unregister
  - drivers/clk/clk.c:clk_register
  - drivers/clk/clk.c:clk_register
  - drivers/clk/clk.c:clk_register
  - drivers/clk/clk.c:__clk_free_clk
  - drivers/clk/clk.c:clk_dump
  - drivers/clk/clk.c:clk_dump_subtree
  - drivers/clk/clk.c:clk_summary_show
  - drivers/clk/clk.c:clk_summary_show_subtree
  - drivers/clk/clk.c:clk_get_phase
  - drivers/clk/clk.c:clk_set_phase
  - drivers/clk/clk.c:clk_core_set_parent
  - drivers/clk/clk.c:clk_core_set_parent
  - drivers/clk/clk.c:clk_get_parent
  - drivers/clk/clk.c:clk_set_rate
  - drivers/clk/clk.c:clk_core_get_rate
  - drivers/clk/clk.c:clk_core_get_rate
  - drivers/clk/clk.c:clk_core_get_accuracy
  - drivers/clk/clk.c:clk_core_get_accuracy
  - drivers/clk/clk.c:clk_round_rate
  - drivers/clk/clk.c:clk_disable_unused
  - drivers/clk/clk.c:clk_core_disable_unprepare
  - drivers/clk/clk.c:clk_prepare
```
**Symbols:**

```
ffffffff8174a5c0-ffffffff8174a665: clk_prepare_unlock (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
void clk_prepare_unlock();
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/clk/clk.c (ffffffff81532e40)
Location: drivers/clk/clk.c:106
Inline: True
Direct callers:
  - drivers/clk/clk.c:clk_notifier_unregister
  - drivers/clk/clk.c:clk_notifier_register
  - drivers/clk/clk.c:__clk_put
  - drivers/clk/clk.c:clk_unregister
  - drivers/clk/clk.c:clk_register
  - drivers/clk/clk.c:clk_register
  - drivers/clk/clk.c:clk_register
  - drivers/clk/clk.c:__clk_free_clk
  - drivers/clk/clk.c:clk_dump
  - drivers/clk/clk.c:clk_dump_subtree
  - drivers/clk/clk.c:clk_summary_show
  - drivers/clk/clk.c:clk_summary_show_subtree
  - drivers/clk/clk.c:clk_get_phase
  - drivers/clk/clk.c:clk_set_phase
  - drivers/clk/clk.c:clk_core_set_parent
  - drivers/clk/clk.c:clk_core_set_parent
  - drivers/clk/clk.c:clk_get_parent
  - drivers/clk/clk.c:clk_set_rate
  - drivers/clk/clk.c:clk_core_get_rate
  - drivers/clk/clk.c:clk_core_get_rate
  - drivers/clk/clk.c:clk_core_get_accuracy
  - drivers/clk/clk.c:clk_core_get_accuracy
  - drivers/clk/clk.c:clk_round_rate
  - drivers/clk/clk.c:clk_disable_unused
  - drivers/clk/clk.c:clk_core_disable_unprepare
  - drivers/clk/clk.c:clk_prepare
```
**Symbols:**

```
ffffffff81532e40-ffffffff81532ee5: clk_prepare_unlock (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
void clk_prepare_unlock();
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/clk/clk.c (ffffffff81545d30)
Location: drivers/clk/clk.c:106
Inline: True
Direct callers:
  - drivers/clk/clk.c:clk_notifier_unregister
  - drivers/clk/clk.c:clk_notifier_register
  - drivers/clk/clk.c:__clk_put
  - drivers/clk/clk.c:clk_register
  - drivers/clk/clk.c:clk_register
  - drivers/clk/clk.c:clk_register
  - drivers/clk/clk.c:clk_register
  - drivers/clk/clk.c:clk_register
  - drivers/clk/clk.c:clk_register
  - drivers/clk/clk.c:__clk_free_clk
  - drivers/clk/clk.c:clk_dump
  - drivers/clk/clk.c:clk_dump_subtree
  - drivers/clk/clk.c:clk_summary_show
  - drivers/clk/clk.c:clk_summary_show_subtree
  - drivers/clk/clk.c:clk_set_phase
  - drivers/clk/clk.c:clk_get_parent
  - drivers/clk/clk.c:clk_core_get_rate
  - drivers/clk/clk.c:clk_core_get_rate
  - drivers/clk/clk.c:clk_core_get_accuracy
  - drivers/clk/clk.c:clk_disable_unused
  - drivers/clk/clk.c:clk_core_disable_unprepare
```
**Symbols:**

```
ffffffff81545d30-ffffffff81545d8e: clk_prepare_unlock (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void clk_prepare_unlock();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/clk/clk.c (ffffffff815a7d00)
Location: drivers/clk/clk.c:128
Inline: False
Direct callers:
  - drivers/clk/clk.c:clk_notifier_unregister
  - drivers/clk/clk.c:clk_notifier_register
  - drivers/clk/clk.c:__clk_put
  - drivers/clk/clk.c:clk_register
  - drivers/clk/clk.c:clk_register
  - drivers/clk/clk.c:clk_register
  - drivers/clk/clk.c:__clk_free_clk
  - drivers/clk/clk.c:clk_dump
  - drivers/clk/clk.c:clk_dump_subtree
  - drivers/clk/clk.c:clk_summary_show
  - drivers/clk/clk.c:clk_summary_show_subtree
  - drivers/clk/clk.c:clk_set_phase
  - drivers/clk/clk.c:clk_get_parent
  - drivers/clk/clk.c:clk_core_get_rate
  - drivers/clk/clk.c:clk_core_get_rate
  - drivers/clk/clk.c:clk_core_get_accuracy
  - drivers/clk/clk.c:clk_disable_unused
  - drivers/clk/clk.c:clk_core_disable_unprepare
```
**Symbols:**

```
ffffffff815a7d00-ffffffff815a7d5f: clk_prepare_unlock (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void clk_prepare_unlock();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/clk/clk.c (ffffffff815df890)
Location: drivers/clk/clk.c:130
Inline: False
Direct callers:
  - drivers/clk/clk.c:clk_notifier_unregister
  - drivers/clk/clk.c:clk_notifier_register
  - drivers/clk/clk.c:__clk_put
  - drivers/clk/clk.c:clk_unregister
  - drivers/clk/clk.c:clk_register
  - drivers/clk/clk.c:clk_register
  - drivers/clk/clk.c:clk_register
  - drivers/clk/clk.c:clk_register
  - drivers/clk/clk.c:clk_register
  - drivers/clk/clk.c:clk_register
  - drivers/clk/clk.c:clk_register
  - drivers/clk/clk.c:clk_register
  - drivers/clk/clk.c:clk_register
  - drivers/clk/clk.c:__clk_free_clk
  - drivers/clk/clk.c:clk_dump_show
  - drivers/clk/clk.c:clk_summary_show
  - drivers/clk/clk.c:clk_core_get_phase
  - drivers/clk/clk.c:clk_core_get_phase
  - drivers/clk/clk.c:clk_set_phase
  - drivers/clk/clk.c:clk_get_parent
  - drivers/clk/clk.c:clk_set_rate_range
  - drivers/clk/clk.c:clk_core_get_rate
  - drivers/clk/clk.c:clk_core_get_rate
  - drivers/clk/clk.c:clk_core_get_accuracy
  - drivers/clk/clk.c:clk_disable_unused
  - drivers/clk/clk.c:clk_core_disable_unprepare
```
**Symbols:**

```
ffffffff815df890-ffffffff815df8ed: clk_prepare_unlock (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void clk_prepare_unlock();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/clk/clk.c (ffffffff815f95b0)
Location: drivers/clk/clk.c:128
Inline: False
Direct callers:
  - drivers/clk/clk.c:clk_notifier_unregister
  - drivers/clk/clk.c:clk_notifier_register
  - drivers/clk/clk.c:__clk_put
  - drivers/clk/clk.c:clk_unregister
  - drivers/clk/clk.c:clk_register
  - drivers/clk/clk.c:clk_register
  - drivers/clk/clk.c:clk_register
  - drivers/clk/clk.c:clk_register
  - drivers/clk/clk.c:clk_register
  - drivers/clk/clk.c:clk_register
  - drivers/clk/clk.c:clk_register
  - drivers/clk/clk.c:clk_register
  - drivers/clk/clk.c:clk_register
  - drivers/clk/clk.c:__clk_free_clk
  - drivers/clk/clk.c:clk_dump_show
  - drivers/clk/clk.c:clk_summary_show
  - drivers/clk/clk.c:clk_core_get_scaled_duty_cycle
  - drivers/clk/clk.c:clk_set_duty_cycle
  - drivers/clk/clk.c:clk_core_get_phase
  - drivers/clk/clk.c:clk_core_get_phase
  - drivers/clk/clk.c:clk_set_phase
  - drivers/clk/clk.c:clk_get_parent
  - drivers/clk/clk.c:clk_set_rate_range
  - drivers/clk/clk.c:clk_core_get_rate
  - drivers/clk/clk.c:clk_core_get_rate
  - drivers/clk/clk.c:clk_core_get_accuracy
  - drivers/clk/clk.c:clk_disable_unused
  - drivers/clk/clk.c:clk_core_disable_unprepare
```
**Symbols:**

```
ffffffff815f95b0-ffffffff815f960d: clk_prepare_unlock (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void clk_prepare_unlock();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/clk/clk.c (ffffffff8162b950)
Location: drivers/clk/clk.c:138
Inline: False
Direct callers:
  - drivers/clk/clk.c:clk_notifier_unregister
  - drivers/clk/clk.c:clk_notifier_register
  - drivers/clk/clk.c:__clk_put
  - drivers/clk/clk.c:clk_unregister
  - drivers/clk/clk.c:__clk_register
  - drivers/clk/clk.c:__clk_register
  - drivers/clk/clk.c:clk_hw_create_clk
  - drivers/clk/clk.c:__clk_core_init
  - drivers/clk/clk.c:__clk_core_init
  - drivers/clk/clk.c:__clk_core_init
  - drivers/clk/clk.c:__clk_core_init
  - drivers/clk/clk.c:clk_dump_show
  - drivers/clk/clk.c:clk_summary_show
  - drivers/clk/clk.c:clk_core_get_scaled_duty_cycle
  - drivers/clk/clk.c:clk_set_duty_cycle
  - drivers/clk/clk.c:clk_core_get_phase
  - drivers/clk/clk.c:clk_core_get_phase
  - drivers/clk/clk.c:clk_set_phase
  - drivers/clk/clk.c:clk_get_parent
  - drivers/clk/clk.c:clk_set_rate_range
  - drivers/clk/clk.c:clk_core_get_rate
  - drivers/clk/clk.c:clk_core_get_rate
  - drivers/clk/clk.c:clk_core_get_accuracy
  - drivers/clk/clk.c:clk_disable_unused
  - drivers/clk/clk.c:clk_core_disable_unprepare
```
**Symbols:**

```
ffffffff8162b950-ffffffff8162b9ad: clk_prepare_unlock (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
void clk_prepare_unlock();
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/clk/clk.c (ffffffff8164ec20)
Location: drivers/clk/clk.c:144
Inline: True
Direct callers:
  - drivers/clk/clk.c:clk_notifier_unregister
  - drivers/clk/clk.c:clk_notifier_register
  - drivers/clk/clk.c:__clk_put
  - drivers/clk/clk.c:clk_unregister
  - drivers/clk/clk.c:__clk_register
  - drivers/clk/clk.c:__clk_register
  - drivers/clk/clk.c:clk_hw_create_clk
  - drivers/clk/clk.c:__clk_core_init
  - drivers/clk/clk.c:__clk_core_init
  - drivers/clk/clk.c:clk_max_rate_show
  - drivers/clk/clk.c:clk_min_rate_show
  - drivers/clk/clk.c:clk_dump_show
  - drivers/clk/clk.c:clk_summary_show
  - drivers/clk/clk.c:clk_core_get_scaled_duty_cycle
  - drivers/clk/clk.c:clk_set_duty_cycle
  - drivers/clk/clk.c:clk_core_get_phase
  - drivers/clk/clk.c:clk_core_get_phase
  - drivers/clk/clk.c:clk_set_phase
  - drivers/clk/clk.c:clk_get_parent
  - drivers/clk/clk.c:clk_set_rate_range
  - drivers/clk/clk.c:clk_core_get_rate
  - drivers/clk/clk.c:clk_core_get_rate
  - drivers/clk/clk.c:clk_core_get_accuracy
  - drivers/clk/clk.c:clk_disable_unused
  - drivers/clk/clk.c:clk_core_disable_unprepare
```
**Symbols:**

```
ffffffff8164ec20-ffffffff8164ec7d: clk_prepare_unlock (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void clk_prepare_unlock();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/clk/clk.c (ffffffff816fc240)
Location: drivers/clk/clk.c:148
Inline: False
Direct callers:
  - drivers/clk/clk.c:clk_notifier_unregister
  - drivers/clk/clk.c:clk_notifier_register
  - drivers/clk/clk.c:__clk_put
  - drivers/clk/clk.c:clk_unregister
  - drivers/clk/clk.c:__clk_register
  - drivers/clk/clk.c:__clk_register
  - drivers/clk/clk.c:clk_hw_create_clk
  - drivers/clk/clk.c:__clk_core_init
  - drivers/clk/clk.c:__clk_core_init
  - drivers/clk/clk.c:clk_max_rate_show
  - drivers/clk/clk.c:clk_min_rate_show
  - drivers/clk/clk.c:clk_dump_show
  - drivers/clk/clk.c:clk_summary_show
  - drivers/clk/clk.c:clk_summary_show_one
  - drivers/clk/clk.c:clk_set_duty_cycle
  - drivers/clk/clk.c:clk_set_phase
  - drivers/clk/clk.c:clk_get_parent
  - drivers/clk/clk.c:clk_set_rate_range
  - drivers/clk/clk.c:clk_change_rate
  - drivers/clk/clk.c:clk_disable_unused
  - drivers/clk/clk.c:clk_unprepare
```
**Symbols:**

```
ffffffff816fc240-ffffffff816fc29d: clk_prepare_unlock (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void clk_prepare_unlock();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/clk/clk.c (ffffffff81719140)
Location: drivers/clk/clk.c:148
Inline: False
Direct callers:
  - drivers/clk/clk.c:clk_notifier_unregister
  - drivers/clk/clk.c:clk_notifier_register
  - drivers/clk/clk.c:__clk_put
  - drivers/clk/clk.c:clk_unregister
  - drivers/clk/clk.c:__clk_register
  - drivers/clk/clk.c:__clk_register
  - drivers/clk/clk.c:__clk_core_init
  - drivers/clk/clk.c:__clk_core_init
  - drivers/clk/clk.c:clk_max_rate_show
  - drivers/clk/clk.c:clk_min_rate_show
  - drivers/clk/clk.c:clk_dump_show
  - drivers/clk/clk.c:clk_summary_show
  - drivers/clk/clk.c:clk_summary_show_one
  - drivers/clk/clk.c:clk_set_duty_cycle
  - drivers/clk/clk.c:clk_set_phase
  - drivers/clk/clk.c:clk_get_parent
  - drivers/clk/clk.c:clk_change_rate
  - drivers/clk/clk.c:clk_disable_unused
  - drivers/clk/clk.c:clk_unprepare
```
**Symbols:**

```
ffffffff81719140-ffffffff8171919d: clk_prepare_unlock (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void clk_prepare_unlock();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/clk/clk.c (ffffffff816fa450)
Location: drivers/clk/clk.c:148
Inline: False
Direct callers:
  - drivers/clk/clk.c:clk_notifier_unregister
  - drivers/clk/clk.c:clk_notifier_register
  - drivers/clk/clk.c:__clk_put
  - drivers/clk/clk.c:clk_unregister
  - drivers/clk/clk.c:__clk_register
  - drivers/clk/clk.c:__clk_register
  - drivers/clk/clk.c:__clk_core_init
  - drivers/clk/clk.c:__clk_core_init
  - drivers/clk/clk.c:clk_max_rate_show
  - drivers/clk/clk.c:clk_min_rate_show
  - drivers/clk/clk.c:clk_dump_show
  - drivers/clk/clk.c:clk_summary_show
  - drivers/clk/clk.c:clk_summary_show_subtree
  - drivers/clk/clk.c:clk_set_duty_cycle
  - drivers/clk/clk.c:clk_set_phase
  - drivers/clk/clk.c:clk_get_parent
  - drivers/clk/clk.c:clk_change_rate
  - drivers/clk/clk.c:clk_disable_unused
  - drivers/clk/clk.c:clk_unprepare
```
**Symbols:**

```
ffffffff816fa450-ffffffff816fa4ad: clk_prepare_unlock (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
void clk_prepare_unlock();
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/clk/clk.c (ffffffff81775210)
Location: drivers/clk/clk.c:148
Inline: True
Direct callers:
  - drivers/clk/clk.c:clk_notifier_unregister
  - drivers/clk/clk.c:clk_notifier_register
  - drivers/clk/clk.c:__clk_put
  - drivers/clk/clk.c:clk_unregister
  - drivers/clk/clk.c:__clk_register
  - drivers/clk/clk.c:__clk_register
  - drivers/clk/clk.c:__clk_core_init
  - drivers/clk/clk.c:__clk_core_init
  - drivers/clk/clk.c:clk_max_rate_show
  - drivers/clk/clk.c:clk_min_rate_show
  - drivers/clk/clk.c:clk_dump_show
  - drivers/clk/clk.c:clk_summary_show
  - drivers/clk/clk.c:clk_summary_show_subtree
  - drivers/clk/clk.c:clk_set_duty_cycle
  - drivers/clk/clk.c:clk_set_phase
  - drivers/clk/clk.c:clk_get_parent
  - drivers/clk/clk.c:clk_change_rate
  - drivers/clk/clk.c:clk_disable_unused
  - drivers/clk/clk.c:clk_unprepare
```
**Symbols:**

```
ffffffff81775210-ffffffff8177526d: clk_prepare_unlock (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
void clk_prepare_unlock();
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/clk/clk.c (ffffffff818aaf20)
Location: drivers/clk/clk.c:141
Inline: True
Direct callers:
  - drivers/clk/clk.c:clk_notifier_unregister
  - drivers/clk/clk.c:clk_notifier_register
  - drivers/clk/clk.c:__clk_put
  - drivers/clk/clk.c:clk_unregister
  - drivers/clk/clk.c:__clk_register
  - drivers/clk/clk.c:__clk_register
  - drivers/clk/clk.c:clk_hw_create_clk
  - drivers/clk/clk.c:__clk_core_init
  - drivers/clk/clk.c:__clk_core_init
  - drivers/clk/clk.c:clk_max_rate_show
  - drivers/clk/clk.c:clk_min_rate_show
  - drivers/clk/clk.c:clk_rate_get
  - drivers/clk/clk.c:clk_rate_get
  - drivers/clk/clk.c:clk_dump_show
  - drivers/clk/clk.c:clk_summary_show
  - drivers/clk/clk.c:clk_summary_show_subtree
  - drivers/clk/clk.c:clk_set_duty_cycle
  - drivers/clk/clk.c:clk_set_phase
  - drivers/clk/clk.c:clk_get_parent
  - drivers/clk/clk.c:clk_change_rate
  - drivers/clk/clk.c:clk_round_rate
  - drivers/clk/clk.c:clk_disable_unused
  - drivers/clk/clk.c:clk_unprepare
```
**Symbols:**

```
ffffffff818aaf20-ffffffff818aaf93: clk_prepare_unlock (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
void clk_prepare_unlock();
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/clk/clk.c (ffffffff819f6560)
Location: drivers/clk/clk.c:141
Inline: True
Direct callers:
  - drivers/clk/clk.c:clk_notifier_unregister
  - drivers/clk/clk.c:clk_notifier_register
  - drivers/clk/clk.c:__clk_put
  - drivers/clk/clk.c:clk_unregister
  - drivers/clk/clk.c:__clk_register
  - drivers/clk/clk.c:__clk_register
  - drivers/clk/clk.c:clk_hw_create_clk
  - drivers/clk/clk.c:__clk_core_init
  - drivers/clk/clk.c:__clk_core_init
  - drivers/clk/clk.c:clk_max_rate_show
  - drivers/clk/clk.c:clk_min_rate_show
  - drivers/clk/clk.c:clk_rate_get
  - drivers/clk/clk.c:clk_rate_get
  - drivers/clk/clk.c:clk_dump_show
  - drivers/clk/clk.c:clk_summary_show
  - drivers/clk/clk.c:clk_summary_show_subtree
  - drivers/clk/clk.c:clk_set_duty_cycle
  - drivers/clk/clk.c:clk_set_phase
  - drivers/clk/clk.c:clk_get_parent
  - drivers/clk/clk.c:clk_change_rate
  - drivers/clk/clk.c:clk_round_rate
  - drivers/clk/clk.c:clk_disable_unused
  - drivers/clk/clk.c:clk_disable_unused_subtree
  - drivers/clk/clk.c:clk_unprepare
```
**Symbols:**

```
ffffffff819f6560-ffffffff819f65d3: clk_prepare_unlock (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
void clk_prepare_unlock();
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/clk/clk.c (ffffffff81a3ecf0)
Location: drivers/clk/clk.c:141
Inline: True
Direct callers:
  - drivers/clk/clk.c:clk_notifier_unregister
  - drivers/clk/clk.c:clk_notifier_register
  - drivers/clk/clk.c:__clk_put
  - drivers/clk/clk.c:clk_unregister
  - drivers/clk/clk.c:__clk_register
  - drivers/clk/clk.c:__clk_register
  - drivers/clk/clk.c:clk_hw_create_clk
  - drivers/clk/clk.c:__clk_core_init
  - drivers/clk/clk.c:__clk_core_init
  - drivers/clk/clk.c:clk_max_rate_show
  - drivers/clk/clk.c:clk_min_rate_show
  - drivers/clk/clk.c:clk_rate_get
  - drivers/clk/clk.c:clk_rate_get
  - drivers/clk/clk.c:clk_dump_show
  - drivers/clk/clk.c:clk_summary_show
  - drivers/clk/clk.c:clk_summary_show_subtree
  - drivers/clk/clk.c:clk_set_duty_cycle
  - drivers/clk/clk.c:clk_set_phase
  - drivers/clk/clk.c:clk_get_parent
  - drivers/clk/clk.c:clk_change_rate
  - drivers/clk/clk.c:clk_round_rate
  - drivers/clk/clk.c:clk_disable_unused
  - drivers/clk/clk.c:clk_disable_unused_subtree
  - drivers/clk/clk.c:clk_unprepare
```
**Symbols:**

```
ffffffff81a3ecf0-ffffffff81a3ed63: clk_prepare_unlock (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
void clk_prepare_unlock();
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/clk/clk.c (ffffffff81a8a620)
Location: drivers/clk/clk.c:141
Inline: True
Direct callers:
  - drivers/clk/clk.c:clk_notifier_unregister
  - drivers/clk/clk.c:clk_notifier_register
  - drivers/clk/clk.c:__clk_put
  - drivers/clk/clk.c:clk_unregister
  - drivers/clk/clk.c:__clk_register
  - drivers/clk/clk.c:__clk_register
  - drivers/clk/clk.c:clk_hw_create_clk
  - drivers/clk/clk.c:__clk_core_init
  - drivers/clk/clk.c:__clk_core_init
  - drivers/clk/clk.c:clk_max_rate_show
  - drivers/clk/clk.c:clk_min_rate_show
  - drivers/clk/clk.c:clk_rate_get
  - drivers/clk/clk.c:clk_rate_get
  - drivers/clk/clk.c:clk_dump_show
  - drivers/clk/clk.c:clk_summary_show
  - drivers/clk/clk.c:clk_summary_show_one
  - drivers/clk/clk.c:clk_set_duty_cycle
  - drivers/clk/clk.c:clk_set_phase
  - drivers/clk/clk.c:clk_get_parent
  - drivers/clk/clk.c:clk_change_rate
  - drivers/clk/clk.c:clk_round_rate
  - drivers/clk/clk.c:clk_disable_unused
  - drivers/clk/clk.c:clk_disable_unused_subtree
  - drivers/clk/clk.c:clk_unprepare
```
**Symbols:**

```
ffffffff81a8a620-ffffffff81a8a693: clk_prepare_unlock (STB_LOCAL)
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
void clk_prepare_unlock();
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/clk/clk.c (ffff8000107bd3c0)
Location: drivers/clk/clk.c:144
Inline: True
Direct callers:
  - drivers/clk/clk.c:of_clk_add_hw_provider
  - drivers/clk/clk.c:of_clk_add_hw_provider
  - drivers/clk/clk.c:of_clk_add_provider
  - drivers/clk/clk.c:of_clk_add_provider
  - drivers/clk/clk.c:clk_notifier_unregister
  - drivers/clk/clk.c:clk_notifier_register
  - drivers/clk/clk.c:__clk_put
  - drivers/clk/clk.c:clk_unregister
  - drivers/clk/clk.c:__clk_register
  - drivers/clk/clk.c:__clk_register
  - drivers/clk/clk.c:__clk_core_init
  - drivers/clk/clk.c:__clk_core_init
  - drivers/clk/clk.c:clk_max_rate_show
  - drivers/clk/clk.c:clk_min_rate_show
  - drivers/clk/clk.c:clk_dump_show
  - drivers/clk/clk.c:clk_summary_show
  - drivers/clk/clk.c:clk_core_get_scaled_duty_cycle
  - drivers/clk/clk.c:clk_set_duty_cycle
  - drivers/clk/clk.c:clk_core_get_phase
  - drivers/clk/clk.c:clk_core_get_phase
  - drivers/clk/clk.c:clk_set_phase
  - drivers/clk/clk.c:clk_get_parent
  - drivers/clk/clk.c:clk_set_rate_range
  - drivers/clk/clk.c:clk_core_get_rate
  - drivers/clk/clk.c:clk_core_get_rate
  - drivers/clk/clk.c:clk_core_get_accuracy
  - drivers/clk/clk.c:clk_disable_unused
  - drivers/clk/clk.c:clk_core_disable_unprepare
```
**Symbols:**

```
ffff8000107bd3c0-ffff8000107bd428: clk_prepare_unlock (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
void clk_prepare_unlock();
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/clk/clk.c (c08e9ad0)
Location: drivers/clk/clk.c:144
Inline: True
Direct callers:
  - drivers/clk/clk.c:of_clk_add_hw_provider
  - drivers/clk/clk.c:of_clk_add_provider
  - drivers/clk/clk.c:clk_notifier_unregister
  - drivers/clk/clk.c:clk_notifier_register
  - drivers/clk/clk.c:__clk_put
  - drivers/clk/clk.c:clk_unregister
  - drivers/clk/clk.c:__clk_register
  - drivers/clk/clk.c:__clk_register
  - drivers/clk/clk.c:__clk_core_init
  - drivers/clk/clk.c:__clk_core_init
  - drivers/clk/clk.c:__clk_core_init
  - drivers/clk/clk.c:__clk_core_init
  - drivers/clk/clk.c:clk_max_rate_show
  - drivers/clk/clk.c:clk_min_rate_show
  - drivers/clk/clk.c:clk_dump_show
  - drivers/clk/clk.c:clk_summary_show
  - drivers/clk/clk.c:clk_core_get_scaled_duty_cycle
  - drivers/clk/clk.c:clk_set_duty_cycle
  - drivers/clk/clk.c:clk_core_get_phase
  - drivers/clk/clk.c:clk_set_phase
  - drivers/clk/clk.c:clk_get_parent
  - drivers/clk/clk.c:clk_set_rate_range
  - drivers/clk/clk.c:clk_core_get_rate
  - drivers/clk/clk.c:clk_core_get_accuracy
  - drivers/clk/clk.c:clk_disable_unused
  - drivers/clk/clk.c:clk_core_disable_unprepare
```
**Symbols:**

```
c08e9ad0-c08e9bb0: clk_prepare_unlock (STB_LOCAL)
```
</details>
</li>
<li>
In <code>ppc64el</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
void clk_prepare_unlock();
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/clk/clk.c (ffffffe00050c75c)
Location: drivers/clk/clk.c:144
Inline: True
Direct callers:
  - drivers/clk/clk.c:of_clk_add_hw_provider
  - drivers/clk/clk.c:of_clk_add_provider
  - drivers/clk/clk.c:clk_notifier_unregister
  - drivers/clk/clk.c:clk_notifier_register
  - drivers/clk/clk.c:__clk_put
  - drivers/clk/clk.c:clk_unregister
  - drivers/clk/clk.c:__clk_register
  - drivers/clk/clk.c:__clk_register
  - drivers/clk/clk.c:__clk_core_init
  - drivers/clk/clk.c:__clk_core_init
  - drivers/clk/clk.c:clk_max_rate_show
  - drivers/clk/clk.c:clk_min_rate_show
  - drivers/clk/clk.c:clk_dump_show
  - drivers/clk/clk.c:clk_summary_show
  - drivers/clk/clk.c:clk_core_get_scaled_duty_cycle
  - drivers/clk/clk.c:clk_set_duty_cycle
  - drivers/clk/clk.c:clk_core_get_phase
  - drivers/clk/clk.c:clk_set_phase
  - drivers/clk/clk.c:clk_get_parent
  - drivers/clk/clk.c:clk_set_rate_range
  - drivers/clk/clk.c:clk_core_get_rate
  - drivers/clk/clk.c:clk_core_get_rate
  - drivers/clk/clk.c:clk_core_get_accuracy
  - drivers/clk/clk.c:clk_disable_unused
  - drivers/clk/clk.c:clk_core_disable_unprepare
```
**Symbols:**

```
ffffffe00050c75c-ffffffe00050c7c0: clk_prepare_unlock (STB_LOCAL)
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
void clk_prepare_unlock();
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/clk/clk.c (ffffffff81614c80)
Location: drivers/clk/clk.c:144
Inline: True
Direct callers:
  - drivers/clk/clk.c:clk_notifier_unregister
  - drivers/clk/clk.c:clk_notifier_register
  - drivers/clk/clk.c:__clk_put
  - drivers/clk/clk.c:clk_unregister
  - drivers/clk/clk.c:__clk_register
  - drivers/clk/clk.c:__clk_register
  - drivers/clk/clk.c:clk_hw_create_clk
  - drivers/clk/clk.c:__clk_core_init
  - drivers/clk/clk.c:__clk_core_init
  - drivers/clk/clk.c:clk_max_rate_show
  - drivers/clk/clk.c:clk_min_rate_show
  - drivers/clk/clk.c:clk_dump_show
  - drivers/clk/clk.c:clk_summary_show
  - drivers/clk/clk.c:clk_core_get_scaled_duty_cycle
  - drivers/clk/clk.c:clk_set_duty_cycle
  - drivers/clk/clk.c:clk_core_get_phase
  - drivers/clk/clk.c:clk_core_get_phase
  - drivers/clk/clk.c:clk_set_phase
  - drivers/clk/clk.c:clk_get_parent
  - drivers/clk/clk.c:clk_set_rate_range
  - drivers/clk/clk.c:clk_core_get_rate
  - drivers/clk/clk.c:clk_core_get_rate
  - drivers/clk/clk.c:clk_core_get_accuracy
  - drivers/clk/clk.c:clk_disable_unused
  - drivers/clk/clk.c:clk_core_disable_unprepare
```
**Symbols:**

```
ffffffff81614c80-ffffffff81614cdd: clk_prepare_unlock (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
void clk_prepare_unlock();
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/clk/clk.c (ffffffff816091b0)
Location: drivers/clk/clk.c:144
Inline: True
Direct callers:
  - drivers/clk/clk.c:clk_notifier_unregister
  - drivers/clk/clk.c:clk_notifier_register
  - drivers/clk/clk.c:__clk_put
  - drivers/clk/clk.c:clk_unregister
  - drivers/clk/clk.c:__clk_register
  - drivers/clk/clk.c:__clk_register
  - drivers/clk/clk.c:clk_hw_create_clk
  - drivers/clk/clk.c:__clk_core_init
  - drivers/clk/clk.c:__clk_core_init
  - drivers/clk/clk.c:clk_max_rate_show
  - drivers/clk/clk.c:clk_min_rate_show
  - drivers/clk/clk.c:clk_dump_show
  - drivers/clk/clk.c:clk_summary_show
  - drivers/clk/clk.c:clk_core_get_scaled_duty_cycle
  - drivers/clk/clk.c:clk_set_duty_cycle
  - drivers/clk/clk.c:clk_core_get_phase
  - drivers/clk/clk.c:clk_core_get_phase
  - drivers/clk/clk.c:clk_set_phase
  - drivers/clk/clk.c:clk_get_parent
  - drivers/clk/clk.c:clk_set_rate_range
  - drivers/clk/clk.c:clk_core_get_rate
  - drivers/clk/clk.c:clk_core_get_rate
  - drivers/clk/clk.c:clk_core_get_accuracy
  - drivers/clk/clk.c:clk_disable_unused
  - drivers/clk/clk.c:clk_core_disable_unprepare
```
**Symbols:**

```
ffffffff816091b0-ffffffff8160920d: clk_prepare_unlock (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
void clk_prepare_unlock();
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/clk/clk.c (ffffffff81642a60)
Location: drivers/clk/clk.c:144
Inline: True
Direct callers:
  - drivers/clk/clk.c:clk_notifier_unregister
  - drivers/clk/clk.c:clk_notifier_register
  - drivers/clk/clk.c:__clk_put
  - drivers/clk/clk.c:clk_unregister
  - drivers/clk/clk.c:__clk_register
  - drivers/clk/clk.c:__clk_register
  - drivers/clk/clk.c:clk_hw_create_clk
  - drivers/clk/clk.c:__clk_core_init
  - drivers/clk/clk.c:__clk_core_init
  - drivers/clk/clk.c:clk_max_rate_show
  - drivers/clk/clk.c:clk_min_rate_show
  - drivers/clk/clk.c:clk_dump_show
  - drivers/clk/clk.c:clk_summary_show
  - drivers/clk/clk.c:clk_core_get_scaled_duty_cycle
  - drivers/clk/clk.c:clk_set_duty_cycle
  - drivers/clk/clk.c:clk_core_get_phase
  - drivers/clk/clk.c:clk_core_get_phase
  - drivers/clk/clk.c:clk_set_phase
  - drivers/clk/clk.c:clk_get_parent
  - drivers/clk/clk.c:clk_set_rate_range
  - drivers/clk/clk.c:clk_core_get_rate
  - drivers/clk/clk.c:clk_core_get_rate
  - drivers/clk/clk.c:clk_core_get_accuracy
  - drivers/clk/clk.c:clk_disable_unused
  - drivers/clk/clk.c:clk_core_disable_unprepare
```
**Symbols:**

```
ffffffff81642a60-ffffffff81642abd: clk_prepare_unlock (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
void clk_prepare_unlock();
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/clk/clk.c (ffffffff8165ce70)
Location: drivers/clk/clk.c:144
Inline: True
Direct callers:
  - drivers/clk/clk.c:clk_notifier_unregister
  - drivers/clk/clk.c:clk_notifier_register
  - drivers/clk/clk.c:__clk_put
  - drivers/clk/clk.c:clk_unregister
  - drivers/clk/clk.c:__clk_register
  - drivers/clk/clk.c:__clk_register
  - drivers/clk/clk.c:clk_hw_create_clk
  - drivers/clk/clk.c:__clk_core_init
  - drivers/clk/clk.c:__clk_core_init
  - drivers/clk/clk.c:clk_max_rate_show
  - drivers/clk/clk.c:clk_min_rate_show
  - drivers/clk/clk.c:clk_dump_show
  - drivers/clk/clk.c:clk_summary_show
  - drivers/clk/clk.c:clk_core_get_scaled_duty_cycle
  - drivers/clk/clk.c:clk_set_duty_cycle
  - drivers/clk/clk.c:clk_core_get_phase
  - drivers/clk/clk.c:clk_core_get_phase
  - drivers/clk/clk.c:clk_set_phase
  - drivers/clk/clk.c:clk_get_parent
  - drivers/clk/clk.c:clk_set_rate_range
  - drivers/clk/clk.c:clk_core_get_rate
  - drivers/clk/clk.c:clk_core_get_rate
  - drivers/clk/clk.c:clk_core_get_accuracy
  - drivers/clk/clk.c:clk_disable_unused
  - drivers/clk/clk.c:clk_core_disable_unprepare
```
**Symbols:**

```
ffffffff8165ce70-ffffffff8165cecd: clk_prepare_unlock (STB_LOCAL)
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
