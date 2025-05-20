# Function: <code>acpi_ut_delete_generic_state</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void acpi_ut_delete_generic_state(union acpi_generic_state *state);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/utstate.c (ffffffff814a9f66)
Location: drivers/acpi/acpica/utstate.c:298
Inline: False
Direct callers:
  - drivers/acpi/acpica/dscontrol.c:acpi_ds_exec_end_control_op
  - drivers/acpi/acpica/dscontrol.c:acpi_ds_exec_end_control_op
  - drivers/acpi/acpica/dswscope.c:acpi_ds_scope_stack_clear
  - drivers/acpi/acpica/dswscope.c:acpi_ds_scope_stack_pop
  - drivers/acpi/acpica/dswstate.c:acpi_ds_result_pop
  - drivers/acpi/acpica/dswstate.c:acpi_ds_delete_walk_state
  - drivers/acpi/acpica/dswstate.c:acpi_ds_delete_walk_state
  - drivers/acpi/acpica/dswstate.c:acpi_ds_delete_walk_state
  - drivers/acpi/acpica/evmisc.c:acpi_ev_notify_dispatch
  - drivers/acpi/acpica/evmisc.c:acpi_ev_queue_notify_request
  - drivers/acpi/acpica/psparse.c:acpi_ps_parse_aml
  - drivers/acpi/acpica/psscope.c:acpi_ps_pop_scope
  - drivers/acpi/acpica/psscope.c:acpi_ps_cleanup_scope
  - drivers/acpi/acpica/utdelete.c:acpi_ut_update_object_reference
  - drivers/acpi/acpica/utdelete.c:acpi_ut_update_object_reference
  - drivers/acpi/acpica/utmisc.c:acpi_ut_walk_package_tree
  - drivers/acpi/acpica/utmisc.c:acpi_ut_walk_package_tree
```
**Symbols:**

```
ffffffff814a9f66-ffffffff814a9f85: acpi_ut_delete_generic_state (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void acpi_ut_delete_generic_state(union acpi_generic_state *state);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/utstate.c (ffffffff814f9210)
Location: drivers/acpi/acpica/utstate.c:300
Inline: False
Direct callers:
  - drivers/acpi/acpica/dscontrol.c:acpi_ds_exec_end_control_op
  - drivers/acpi/acpica/dscontrol.c:acpi_ds_exec_end_control_op
  - drivers/acpi/acpica/dswscope.c:acpi_ds_scope_stack_pop
  - drivers/acpi/acpica/dswscope.c:acpi_ds_scope_stack_clear
  - drivers/acpi/acpica/dswstate.c:acpi_ds_delete_walk_state
  - drivers/acpi/acpica/dswstate.c:acpi_ds_delete_walk_state
  - drivers/acpi/acpica/dswstate.c:acpi_ds_delete_walk_state
  - drivers/acpi/acpica/dswstate.c:acpi_ds_result_pop
  - drivers/acpi/acpica/evmisc.c:acpi_ev_notify_dispatch
  - drivers/acpi/acpica/evmisc.c:acpi_ev_queue_notify_request
  - drivers/acpi/acpica/psparse.c:acpi_ps_parse_aml
  - drivers/acpi/acpica/psscope.c:acpi_ps_cleanup_scope
  - drivers/acpi/acpica/psscope.c:acpi_ps_pop_scope
  - drivers/acpi/acpica/utdelete.c:acpi_ut_update_object_reference
  - drivers/acpi/acpica/utdelete.c:acpi_ut_update_object_reference
  - drivers/acpi/acpica/utmisc.c:acpi_ut_walk_package_tree
  - drivers/acpi/acpica/utmisc.c:acpi_ut_walk_package_tree
```
**Symbols:**

```
ffffffff814f9210-ffffffff814f922f: acpi_ut_delete_generic_state (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void acpi_ut_delete_generic_state(union acpi_generic_state *state);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/utstate.c (ffffffff8151bc27)
Location: drivers/acpi/acpica/utstate.c:300
Inline: False
Direct callers:
  - drivers/acpi/acpica/dscontrol.c:acpi_ds_exec_end_control_op
  - drivers/acpi/acpica/dscontrol.c:acpi_ds_exec_end_control_op
  - drivers/acpi/acpica/dswscope.c:acpi_ds_scope_stack_pop
  - drivers/acpi/acpica/dswscope.c:acpi_ds_scope_stack_clear
  - drivers/acpi/acpica/dswstate.c:acpi_ds_delete_walk_state
  - drivers/acpi/acpica/dswstate.c:acpi_ds_delete_walk_state
  - drivers/acpi/acpica/dswstate.c:acpi_ds_delete_walk_state
  - drivers/acpi/acpica/dswstate.c:acpi_ds_result_pop
  - drivers/acpi/acpica/evmisc.c:acpi_ev_notify_dispatch
  - drivers/acpi/acpica/evmisc.c:acpi_ev_queue_notify_request
  - drivers/acpi/acpica/psparse.c:acpi_ps_parse_aml
  - drivers/acpi/acpica/psscope.c:acpi_ps_cleanup_scope
  - drivers/acpi/acpica/psscope.c:acpi_ps_pop_scope
  - drivers/acpi/acpica/utdelete.c:acpi_ut_update_object_reference
  - drivers/acpi/acpica/utdelete.c:acpi_ut_update_object_reference
  - drivers/acpi/acpica/utmisc.c:acpi_ut_walk_package_tree
  - drivers/acpi/acpica/utmisc.c:acpi_ut_walk_package_tree
```
**Symbols:**

```
ffffffff8151bc27-ffffffff8151bc46: acpi_ut_delete_generic_state (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void acpi_ut_delete_generic_state(union acpi_generic_state *state);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/utstate.c (ffffffff8152c43a)
Location: drivers/acpi/acpica/utstate.c:300
Inline: False
Direct callers:
  - drivers/acpi/acpica/dscontrol.c:acpi_ds_exec_end_control_op
  - drivers/acpi/acpica/dscontrol.c:acpi_ds_exec_end_control_op
  - drivers/acpi/acpica/dswscope.c:acpi_ds_scope_stack_pop
  - drivers/acpi/acpica/dswscope.c:acpi_ds_scope_stack_clear
  - drivers/acpi/acpica/dswstate.c:acpi_ds_delete_walk_state
  - drivers/acpi/acpica/dswstate.c:acpi_ds_delete_walk_state
  - drivers/acpi/acpica/dswstate.c:acpi_ds_delete_walk_state
  - drivers/acpi/acpica/dswstate.c:acpi_ds_result_pop
  - drivers/acpi/acpica/evmisc.c:acpi_ev_notify_dispatch
  - drivers/acpi/acpica/evmisc.c:acpi_ev_queue_notify_request
  - drivers/acpi/acpica/psparse.c:acpi_ps_parse_aml
  - drivers/acpi/acpica/psscope.c:acpi_ps_cleanup_scope
  - drivers/acpi/acpica/psscope.c:acpi_ps_pop_scope
  - drivers/acpi/acpica/utdelete.c:acpi_ut_update_object_reference
  - drivers/acpi/acpica/utdelete.c:acpi_ut_update_object_reference
  - drivers/acpi/acpica/utmisc.c:acpi_ut_walk_package_tree
  - drivers/acpi/acpica/utmisc.c:acpi_ut_walk_package_tree
```
**Symbols:**

```
ffffffff8152c43a-ffffffff8152c45a: acpi_ut_delete_generic_state (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void acpi_ut_delete_generic_state(union acpi_generic_state *state);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/utstate.c (ffffffff81586c2d)
Location: drivers/acpi/acpica/utstate.c:300
Inline: False
Direct callers:
  - drivers/acpi/acpica/dscontrol.c:acpi_ds_exec_end_control_op
  - drivers/acpi/acpica/dscontrol.c:acpi_ds_exec_end_control_op
  - drivers/acpi/acpica/dswscope.c:acpi_ds_scope_stack_pop
  - drivers/acpi/acpica/dswscope.c:acpi_ds_scope_stack_clear
  - drivers/acpi/acpica/dswstate.c:acpi_ds_delete_walk_state
  - drivers/acpi/acpica/dswstate.c:acpi_ds_delete_walk_state
  - drivers/acpi/acpica/dswstate.c:acpi_ds_delete_walk_state
  - drivers/acpi/acpica/dswstate.c:acpi_ds_result_pop
  - drivers/acpi/acpica/evmisc.c:acpi_ev_notify_dispatch
  - drivers/acpi/acpica/evmisc.c:acpi_ev_queue_notify_request
  - drivers/acpi/acpica/psobject.c:acpi_ps_complete_op
  - drivers/acpi/acpica/psparse.c:acpi_ps_parse_aml
  - drivers/acpi/acpica/psscope.c:acpi_ps_cleanup_scope
  - drivers/acpi/acpica/psscope.c:acpi_ps_pop_scope
  - drivers/acpi/acpica/utdelete.c:acpi_ut_update_object_reference
  - drivers/acpi/acpica/utdelete.c:acpi_ut_update_object_reference
  - drivers/acpi/acpica/utmisc.c:acpi_ut_walk_package_tree
  - drivers/acpi/acpica/utmisc.c:acpi_ut_walk_package_tree
```
**Symbols:**

```
ffffffff81586c2d-ffffffff81586c56: acpi_ut_delete_generic_state (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void acpi_ut_delete_generic_state(union acpi_generic_state *state);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/utstate.c (ffffffff815bddd6)
Location: drivers/acpi/acpica/utstate.c:264
Inline: False
Direct callers:
  - drivers/acpi/acpica/dscontrol.c:acpi_ds_exec_end_control_op
  - drivers/acpi/acpica/dscontrol.c:acpi_ds_exec_end_control_op
  - drivers/acpi/acpica/dswscope.c:acpi_ds_scope_stack_pop
  - drivers/acpi/acpica/dswscope.c:acpi_ds_scope_stack_clear
  - drivers/acpi/acpica/dswstate.c:acpi_ds_delete_walk_state
  - drivers/acpi/acpica/dswstate.c:acpi_ds_delete_walk_state
  - drivers/acpi/acpica/dswstate.c:acpi_ds_delete_walk_state
  - drivers/acpi/acpica/dswstate.c:acpi_ds_result_pop
  - drivers/acpi/acpica/evmisc.c:acpi_ev_notify_dispatch
  - drivers/acpi/acpica/evmisc.c:acpi_ev_queue_notify_request
  - drivers/acpi/acpica/psobject.c:acpi_ps_complete_op
  - drivers/acpi/acpica/psparse.c:acpi_ps_parse_aml
  - drivers/acpi/acpica/psscope.c:acpi_ps_cleanup_scope
  - drivers/acpi/acpica/psscope.c:acpi_ps_pop_scope
  - drivers/acpi/acpica/utdelete.c:acpi_ut_update_object_reference
  - drivers/acpi/acpica/utdelete.c:acpi_ut_update_object_reference
  - drivers/acpi/acpica/utmisc.c:acpi_ut_walk_package_tree
  - drivers/acpi/acpica/utmisc.c:acpi_ut_walk_package_tree
```
**Symbols:**

```
ffffffff815bddd6-ffffffff815bddff: acpi_ut_delete_generic_state (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void acpi_ut_delete_generic_state(union acpi_generic_state *state);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/utstate.c (ffffffff815d7221)
Location: drivers/acpi/acpica/utstate.c:264
Inline: False
Direct callers:
  - drivers/acpi/acpica/dscontrol.c:acpi_ds_exec_end_control_op
  - drivers/acpi/acpica/dscontrol.c:acpi_ds_exec_end_control_op
  - drivers/acpi/acpica/dswscope.c:acpi_ds_scope_stack_pop
  - drivers/acpi/acpica/dswscope.c:acpi_ds_scope_stack_clear
  - drivers/acpi/acpica/dswstate.c:acpi_ds_delete_walk_state
  - drivers/acpi/acpica/dswstate.c:acpi_ds_delete_walk_state
  - drivers/acpi/acpica/dswstate.c:acpi_ds_delete_walk_state
  - drivers/acpi/acpica/dswstate.c:acpi_ds_result_pop
  - drivers/acpi/acpica/evmisc.c:acpi_ev_notify_dispatch
  - drivers/acpi/acpica/evmisc.c:acpi_ev_queue_notify_request
  - drivers/acpi/acpica/psobject.c:acpi_ps_complete_op
  - drivers/acpi/acpica/psparse.c:acpi_ps_parse_aml
  - drivers/acpi/acpica/psscope.c:acpi_ps_cleanup_scope
  - drivers/acpi/acpica/psscope.c:acpi_ps_pop_scope
  - drivers/acpi/acpica/utdelete.c:acpi_ut_update_object_reference
  - drivers/acpi/acpica/utdelete.c:acpi_ut_update_object_reference
  - drivers/acpi/acpica/utmisc.c:acpi_ut_walk_package_tree
  - drivers/acpi/acpica/utmisc.c:acpi_ut_walk_package_tree
```
**Symbols:**

```
ffffffff815d7221-ffffffff815d724a: acpi_ut_delete_generic_state (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void acpi_ut_delete_generic_state(union acpi_generic_state *state);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/utstate.c (ffffffff81608c08)
Location: drivers/acpi/acpica/utstate.c:264
Inline: False
Direct callers:
  - drivers/acpi/acpica/dscontrol.c:acpi_ds_exec_end_control_op
  - drivers/acpi/acpica/dscontrol.c:acpi_ds_exec_end_control_op
  - drivers/acpi/acpica/dswscope.c:acpi_ds_scope_stack_pop
  - drivers/acpi/acpica/dswscope.c:acpi_ds_scope_stack_clear
  - drivers/acpi/acpica/dswstate.c:acpi_ds_delete_walk_state
  - drivers/acpi/acpica/dswstate.c:acpi_ds_delete_walk_state
  - drivers/acpi/acpica/dswstate.c:acpi_ds_delete_walk_state
  - drivers/acpi/acpica/dswstate.c:acpi_ds_result_pop
  - drivers/acpi/acpica/evmisc.c:acpi_ev_notify_dispatch
  - drivers/acpi/acpica/evmisc.c:acpi_ev_queue_notify_request
  - drivers/acpi/acpica/psobject.c:acpi_ps_complete_op
  - drivers/acpi/acpica/psparse.c:acpi_ps_parse_aml
  - drivers/acpi/acpica/psscope.c:acpi_ps_cleanup_scope
  - drivers/acpi/acpica/psscope.c:acpi_ps_pop_scope
  - drivers/acpi/acpica/utdelete.c:acpi_ut_update_object_reference
  - drivers/acpi/acpica/utdelete.c:acpi_ut_update_object_reference
  - drivers/acpi/acpica/utmisc.c:acpi_ut_walk_package_tree
  - drivers/acpi/acpica/utmisc.c:acpi_ut_walk_package_tree
```
**Symbols:**

```
ffffffff81608c08-ffffffff81608c33: acpi_ut_delete_generic_state (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void acpi_ut_delete_generic_state(union acpi_generic_state *state);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/utstate.c (ffffffff8162a0ad)
Location: drivers/acpi/acpica/utstate.c:264
Inline: False
Direct callers:
  - drivers/acpi/acpica/dscontrol.c:acpi_ds_exec_end_control_op
  - drivers/acpi/acpica/dscontrol.c:acpi_ds_exec_end_control_op
  - drivers/acpi/acpica/dswscope.c:acpi_ds_scope_stack_pop
  - drivers/acpi/acpica/dswscope.c:acpi_ds_scope_stack_clear
  - drivers/acpi/acpica/dswstate.c:acpi_ds_delete_walk_state
  - drivers/acpi/acpica/dswstate.c:acpi_ds_delete_walk_state
  - drivers/acpi/acpica/dswstate.c:acpi_ds_delete_walk_state
  - drivers/acpi/acpica/dswstate.c:acpi_ds_result_pop
  - drivers/acpi/acpica/evmisc.c:acpi_ev_notify_dispatch
  - drivers/acpi/acpica/evmisc.c:acpi_ev_queue_notify_request
  - drivers/acpi/acpica/psobject.c:acpi_ps_complete_op
  - drivers/acpi/acpica/psparse.c:acpi_ps_parse_aml
  - drivers/acpi/acpica/psscope.c:acpi_ps_cleanup_scope
  - drivers/acpi/acpica/psscope.c:acpi_ps_pop_scope
  - drivers/acpi/acpica/utdelete.c:acpi_ut_update_object_reference
  - drivers/acpi/acpica/utdelete.c:acpi_ut_update_object_reference
  - drivers/acpi/acpica/utmisc.c:acpi_ut_walk_package_tree
  - drivers/acpi/acpica/utmisc.c:acpi_ut_walk_package_tree
```
**Symbols:**

```
ffffffff8162a0ad-ffffffff8162a0d8: acpi_ut_delete_generic_state (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void acpi_ut_delete_generic_state(union acpi_generic_state *state);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/utstate.c (ffffffff816d688c)
Location: drivers/acpi/acpica/utstate.c:264
Inline: False
Direct callers:
  - drivers/acpi/acpica/dscontrol.c:acpi_ds_exec_end_control_op
  - drivers/acpi/acpica/dscontrol.c:acpi_ds_exec_end_control_op
  - drivers/acpi/acpica/dswscope.c:acpi_ds_scope_stack_pop
  - drivers/acpi/acpica/dswscope.c:acpi_ds_scope_stack_clear
  - drivers/acpi/acpica/dswstate.c:acpi_ds_delete_walk_state
  - drivers/acpi/acpica/dswstate.c:acpi_ds_delete_walk_state
  - drivers/acpi/acpica/dswstate.c:acpi_ds_delete_walk_state
  - drivers/acpi/acpica/dswstate.c:acpi_ds_result_pop
  - drivers/acpi/acpica/evmisc.c:acpi_ev_notify_dispatch
  - drivers/acpi/acpica/evmisc.c:acpi_ev_queue_notify_request
  - drivers/acpi/acpica/psobject.c:acpi_ps_complete_op
  - drivers/acpi/acpica/psparse.c:acpi_ps_parse_aml
  - drivers/acpi/acpica/psscope.c:acpi_ps_cleanup_scope
  - drivers/acpi/acpica/psscope.c:acpi_ps_pop_scope
  - drivers/acpi/acpica/utdelete.c:acpi_ut_update_object_reference
  - drivers/acpi/acpica/utdelete.c:acpi_ut_update_object_reference
  - drivers/acpi/acpica/utmisc.c:acpi_ut_walk_package_tree
  - drivers/acpi/acpica/utmisc.c:acpi_ut_walk_package_tree
```
**Symbols:**

```
ffffffff816d688c-ffffffff816d68b7: acpi_ut_delete_generic_state (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void acpi_ut_delete_generic_state(union acpi_generic_state *state);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/utstate.c (ffffffff816f4837)
Location: drivers/acpi/acpica/utstate.c:264
Inline: False
Direct callers:
  - drivers/acpi/acpica/dscontrol.c:acpi_ds_exec_end_control_op
  - drivers/acpi/acpica/dscontrol.c:acpi_ds_exec_end_control_op
  - drivers/acpi/acpica/dswscope.c:acpi_ds_scope_stack_pop
  - drivers/acpi/acpica/dswscope.c:acpi_ds_scope_stack_clear
  - drivers/acpi/acpica/dswstate.c:acpi_ds_delete_walk_state
  - drivers/acpi/acpica/dswstate.c:acpi_ds_delete_walk_state
  - drivers/acpi/acpica/dswstate.c:acpi_ds_delete_walk_state
  - drivers/acpi/acpica/dswstate.c:acpi_ds_result_pop
  - drivers/acpi/acpica/evmisc.c:acpi_ev_notify_dispatch
  - drivers/acpi/acpica/evmisc.c:acpi_ev_queue_notify_request
  - drivers/acpi/acpica/psobject.c:acpi_ps_complete_op
  - drivers/acpi/acpica/psparse.c:acpi_ps_parse_aml
  - drivers/acpi/acpica/psscope.c:acpi_ps_cleanup_scope
  - drivers/acpi/acpica/psscope.c:acpi_ps_pop_scope
  - drivers/acpi/acpica/utdelete.c:acpi_ut_update_object_reference
  - drivers/acpi/acpica/utdelete.c:acpi_ut_update_object_reference
  - drivers/acpi/acpica/utmisc.c:acpi_ut_walk_package_tree
  - drivers/acpi/acpica/utmisc.c:acpi_ut_walk_package_tree
```
**Symbols:**

```
ffffffff816f4837-ffffffff816f4862: acpi_ut_delete_generic_state (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void acpi_ut_delete_generic_state(union acpi_generic_state *state);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/utstate.c (ffffffff816d66d5)
Location: drivers/acpi/acpica/utstate.c:264
Inline: False
Direct callers:
  - drivers/acpi/acpica/dscontrol.c:acpi_ds_exec_end_control_op
  - drivers/acpi/acpica/dscontrol.c:acpi_ds_exec_end_control_op
  - drivers/acpi/acpica/dswscope.c:acpi_ds_scope_stack_pop
  - drivers/acpi/acpica/dswscope.c:acpi_ds_scope_stack_clear
  - drivers/acpi/acpica/dswstate.c:acpi_ds_delete_walk_state
  - drivers/acpi/acpica/dswstate.c:acpi_ds_delete_walk_state
  - drivers/acpi/acpica/dswstate.c:acpi_ds_delete_walk_state
  - drivers/acpi/acpica/dswstate.c:acpi_ds_result_pop
  - drivers/acpi/acpica/evmisc.c:acpi_ev_notify_dispatch
  - drivers/acpi/acpica/evmisc.c:acpi_ev_queue_notify_request
  - drivers/acpi/acpica/psobject.c:acpi_ps_complete_op
  - drivers/acpi/acpica/psparse.c:acpi_ps_parse_aml
  - drivers/acpi/acpica/psscope.c:acpi_ps_cleanup_scope
  - drivers/acpi/acpica/psscope.c:acpi_ps_pop_scope
  - drivers/acpi/acpica/utdelete.c:acpi_ut_update_object_reference
  - drivers/acpi/acpica/utdelete.c:acpi_ut_update_object_reference
  - drivers/acpi/acpica/utmisc.c:acpi_ut_walk_package_tree
  - drivers/acpi/acpica/utmisc.c:acpi_ut_walk_package_tree
```
**Symbols:**

```
ffffffff816d66d5-ffffffff816d6700: acpi_ut_delete_generic_state (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void acpi_ut_delete_generic_state(union acpi_generic_state *state);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/utstate.c (ffffffff8174e241)
Location: drivers/acpi/acpica/utstate.c:264
Inline: False
Direct callers:
  - drivers/acpi/acpica/dscontrol.c:acpi_ds_exec_end_control_op
  - drivers/acpi/acpica/dscontrol.c:acpi_ds_exec_end_control_op
  - drivers/acpi/acpica/dswscope.c:acpi_ds_scope_stack_pop
  - drivers/acpi/acpica/dswscope.c:acpi_ds_scope_stack_clear
  - drivers/acpi/acpica/dswstate.c:acpi_ds_delete_walk_state
  - drivers/acpi/acpica/dswstate.c:acpi_ds_delete_walk_state
  - drivers/acpi/acpica/dswstate.c:acpi_ds_delete_walk_state
  - drivers/acpi/acpica/dswstate.c:acpi_ds_result_pop
  - drivers/acpi/acpica/evmisc.c:acpi_ev_notify_dispatch
  - drivers/acpi/acpica/evmisc.c:acpi_ev_queue_notify_request
  - drivers/acpi/acpica/psobject.c:acpi_ps_complete_op
  - drivers/acpi/acpica/psparse.c:acpi_ps_parse_aml
  - drivers/acpi/acpica/psscope.c:acpi_ps_cleanup_scope
  - drivers/acpi/acpica/psscope.c:acpi_ps_pop_scope
  - drivers/acpi/acpica/utdelete.c:acpi_ut_update_object_reference
  - drivers/acpi/acpica/utdelete.c:acpi_ut_update_object_reference
  - drivers/acpi/acpica/utmisc.c:acpi_ut_walk_package_tree
  - drivers/acpi/acpica/utmisc.c:acpi_ut_walk_package_tree
```
**Symbols:**

```
ffffffff8174e241-ffffffff8174e26c: acpi_ut_delete_generic_state (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void acpi_ut_delete_generic_state(union acpi_generic_state *state);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/utstate.c (ffffffff81880ad8)
Location: drivers/acpi/acpica/utstate.c:264
Inline: False
Direct callers:
  - drivers/acpi/acpica/dscontrol.c:acpi_ds_exec_end_control_op
  - drivers/acpi/acpica/dscontrol.c:acpi_ds_exec_end_control_op
  - drivers/acpi/acpica/dswscope.c:acpi_ds_scope_stack_pop
  - drivers/acpi/acpica/dswscope.c:acpi_ds_scope_stack_clear
  - drivers/acpi/acpica/dswstate.c:acpi_ds_delete_walk_state
  - drivers/acpi/acpica/dswstate.c:acpi_ds_delete_walk_state
  - drivers/acpi/acpica/dswstate.c:acpi_ds_delete_walk_state
  - drivers/acpi/acpica/dswstate.c:acpi_ds_result_pop
  - drivers/acpi/acpica/evmisc.c:acpi_ev_notify_dispatch
  - drivers/acpi/acpica/evmisc.c:acpi_ev_queue_notify_request
  - drivers/acpi/acpica/psobject.c:acpi_ps_complete_op
  - drivers/acpi/acpica/psparse.c:acpi_ps_parse_aml
  - drivers/acpi/acpica/psscope.c:acpi_ps_cleanup_scope
  - drivers/acpi/acpica/psscope.c:acpi_ps_pop_scope
  - drivers/acpi/acpica/utdelete.c:acpi_ut_update_object_reference
  - drivers/acpi/acpica/utdelete.c:acpi_ut_update_object_reference
  - drivers/acpi/acpica/utmisc.c:acpi_ut_walk_package_tree
  - drivers/acpi/acpica/utmisc.c:acpi_ut_walk_package_tree
```
**Symbols:**

```
ffffffff81880ad8-ffffffff81880b0b: acpi_ut_delete_generic_state (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void acpi_ut_delete_generic_state(union acpi_generic_state *state);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/utstate.c (ffffffff819c5060)
Location: drivers/acpi/acpica/utstate.c:264
Inline: False
Direct callers:
  - drivers/acpi/acpica/dscontrol.c:acpi_ds_exec_end_control_op
  - drivers/acpi/acpica/dscontrol.c:acpi_ds_exec_end_control_op
  - drivers/acpi/acpica/dswscope.c:acpi_ds_scope_stack_pop
  - drivers/acpi/acpica/dswscope.c:acpi_ds_scope_stack_clear
  - drivers/acpi/acpica/dswstate.c:acpi_ds_delete_walk_state
  - drivers/acpi/acpica/dswstate.c:acpi_ds_delete_walk_state
  - drivers/acpi/acpica/dswstate.c:acpi_ds_delete_walk_state
  - drivers/acpi/acpica/dswstate.c:acpi_ds_result_pop
  - drivers/acpi/acpica/evmisc.c:acpi_ev_notify_dispatch
  - drivers/acpi/acpica/evmisc.c:acpi_ev_queue_notify_request
  - drivers/acpi/acpica/psobject.c:acpi_ps_complete_op
  - drivers/acpi/acpica/psparse.c:acpi_ps_parse_aml
  - drivers/acpi/acpica/psscope.c:acpi_ps_cleanup_scope
  - drivers/acpi/acpica/psscope.c:acpi_ps_pop_scope
  - drivers/acpi/acpica/utdelete.c:acpi_ut_update_object_reference
  - drivers/acpi/acpica/utdelete.c:acpi_ut_update_object_reference
  - drivers/acpi/acpica/utmisc.c:acpi_ut_walk_package_tree
  - drivers/acpi/acpica/utmisc.c:acpi_ut_walk_package_tree
```
**Symbols:**

```
ffffffff819c5060-ffffffff819c5096: acpi_ut_delete_generic_state (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void acpi_ut_delete_generic_state(union acpi_generic_state *state);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/utstate.c (ffffffff81a0c460)
Location: drivers/acpi/acpica/utstate.c:264
Inline: False
Direct callers:
  - drivers/acpi/acpica/dscontrol.c:acpi_ds_exec_end_control_op
  - drivers/acpi/acpica/dscontrol.c:acpi_ds_exec_end_control_op
  - drivers/acpi/acpica/dswscope.c:acpi_ds_scope_stack_pop
  - drivers/acpi/acpica/dswscope.c:acpi_ds_scope_stack_clear
  - drivers/acpi/acpica/dswstate.c:acpi_ds_delete_walk_state
  - drivers/acpi/acpica/dswstate.c:acpi_ds_delete_walk_state
  - drivers/acpi/acpica/dswstate.c:acpi_ds_delete_walk_state
  - drivers/acpi/acpica/dswstate.c:acpi_ds_result_pop
  - drivers/acpi/acpica/evmisc.c:acpi_ev_notify_dispatch
  - drivers/acpi/acpica/evmisc.c:acpi_ev_queue_notify_request
  - drivers/acpi/acpica/psobject.c:acpi_ps_complete_op
  - drivers/acpi/acpica/psparse.c:acpi_ps_parse_aml
  - drivers/acpi/acpica/psscope.c:acpi_ps_cleanup_scope
  - drivers/acpi/acpica/psscope.c:acpi_ps_pop_scope
  - drivers/acpi/acpica/utdelete.c:acpi_ut_update_object_reference
  - drivers/acpi/acpica/utdelete.c:acpi_ut_update_object_reference
  - drivers/acpi/acpica/utmisc.c:acpi_ut_walk_package_tree
  - drivers/acpi/acpica/utmisc.c:acpi_ut_walk_package_tree
```
**Symbols:**

```
ffffffff81a0c460-ffffffff81a0c496: acpi_ut_delete_generic_state (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void acpi_ut_delete_generic_state(union acpi_generic_state *state);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/utstate.c (ffffffff81a57430)
Location: drivers/acpi/acpica/utstate.c:264
Inline: False
Direct callers:
  - drivers/acpi/acpica/dscontrol.c:acpi_ds_exec_end_control_op
  - drivers/acpi/acpica/dscontrol.c:acpi_ds_exec_end_control_op
  - drivers/acpi/acpica/dswscope.c:acpi_ds_scope_stack_pop
  - drivers/acpi/acpica/dswscope.c:acpi_ds_scope_stack_clear
  - drivers/acpi/acpica/dswstate.c:acpi_ds_delete_walk_state
  - drivers/acpi/acpica/dswstate.c:acpi_ds_delete_walk_state
  - drivers/acpi/acpica/dswstate.c:acpi_ds_delete_walk_state
  - drivers/acpi/acpica/dswstate.c:acpi_ds_result_pop
  - drivers/acpi/acpica/evmisc.c:acpi_ev_notify_dispatch
  - drivers/acpi/acpica/evmisc.c:acpi_ev_queue_notify_request
  - drivers/acpi/acpica/psobject.c:acpi_ps_complete_op
  - drivers/acpi/acpica/psparse.c:acpi_ps_parse_aml
  - drivers/acpi/acpica/psscope.c:acpi_ps_cleanup_scope
  - drivers/acpi/acpica/psscope.c:acpi_ps_pop_scope
  - drivers/acpi/acpica/utdelete.c:acpi_ut_update_object_reference
  - drivers/acpi/acpica/utdelete.c:acpi_ut_update_object_reference
  - drivers/acpi/acpica/utmisc.c:acpi_ut_walk_package_tree
  - drivers/acpi/acpica/utmisc.c:acpi_ut_walk_package_tree
```
**Symbols:**

```
ffffffff81a57430-ffffffff81a57466: acpi_ut_delete_generic_state (STB_GLOBAL)
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
void acpi_ut_delete_generic_state(union acpi_generic_state *state);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/utstate.c (ffff80001079e6f8)
Location: drivers/acpi/acpica/utstate.c:264
Inline: False
Direct callers:
  - drivers/acpi/acpica/dscontrol.c:acpi_ds_exec_end_control_op
  - drivers/acpi/acpica/dscontrol.c:acpi_ds_exec_end_control_op
  - drivers/acpi/acpica/dswscope.c:acpi_ds_scope_stack_pop
  - drivers/acpi/acpica/dswscope.c:acpi_ds_scope_stack_clear
  - drivers/acpi/acpica/dswstate.c:acpi_ds_delete_walk_state
  - drivers/acpi/acpica/dswstate.c:acpi_ds_delete_walk_state
  - drivers/acpi/acpica/dswstate.c:acpi_ds_delete_walk_state
  - drivers/acpi/acpica/dswstate.c:acpi_ds_result_pop
  - drivers/acpi/acpica/evmisc.c:acpi_ev_notify_dispatch
  - drivers/acpi/acpica/evmisc.c:acpi_ev_queue_notify_request
  - drivers/acpi/acpica/psparse.c:acpi_ps_parse_aml
  - drivers/acpi/acpica/psscope.c:acpi_ps_cleanup_scope
  - drivers/acpi/acpica/psscope.c:acpi_ps_pop_scope
  - drivers/acpi/acpica/utdelete.c:acpi_ut_update_object_reference
  - drivers/acpi/acpica/utdelete.c:acpi_ut_update_object_reference
  - drivers/acpi/acpica/utmisc.c:acpi_ut_walk_package_tree
  - drivers/acpi/acpica/utmisc.c:acpi_ut_walk_package_tree
```
**Symbols:**

```
ffff80001079e6f8-ffff80001079e730: acpi_ut_delete_generic_state (STB_GLOBAL)
```
</details>
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
<details>
<summary>In <code>aws</code>: ✅</summary>

```c
void acpi_ut_delete_generic_state(union acpi_generic_state *state);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/utstate.c (ffffffff816011ed)
Location: drivers/acpi/acpica/utstate.c:264
Inline: False
Direct callers:
  - drivers/acpi/acpica/dscontrol.c:acpi_ds_exec_end_control_op
  - drivers/acpi/acpica/dscontrol.c:acpi_ds_exec_end_control_op
  - drivers/acpi/acpica/dswscope.c:acpi_ds_scope_stack_pop
  - drivers/acpi/acpica/dswscope.c:acpi_ds_scope_stack_clear
  - drivers/acpi/acpica/dswstate.c:acpi_ds_delete_walk_state
  - drivers/acpi/acpica/dswstate.c:acpi_ds_delete_walk_state
  - drivers/acpi/acpica/dswstate.c:acpi_ds_delete_walk_state
  - drivers/acpi/acpica/dswstate.c:acpi_ds_result_pop
  - drivers/acpi/acpica/evmisc.c:acpi_ev_notify_dispatch
  - drivers/acpi/acpica/evmisc.c:acpi_ev_queue_notify_request
  - drivers/acpi/acpica/psparse.c:acpi_ps_parse_aml
  - drivers/acpi/acpica/psscope.c:acpi_ps_cleanup_scope
  - drivers/acpi/acpica/psscope.c:acpi_ps_pop_scope
  - drivers/acpi/acpica/utdelete.c:acpi_ut_update_object_reference
  - drivers/acpi/acpica/utdelete.c:acpi_ut_update_object_reference
  - drivers/acpi/acpica/utmisc.c:acpi_ut_walk_package_tree
  - drivers/acpi/acpica/utmisc.c:acpi_ut_walk_package_tree
```
**Symbols:**

```
ffffffff816011ed-ffffffff8160120d: acpi_ut_delete_generic_state (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void acpi_ut_delete_generic_state(union acpi_generic_state *state);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/utstate.c (ffffffff815ec6a8)
Location: drivers/acpi/acpica/utstate.c:264
Inline: False
Direct callers:
  - drivers/acpi/acpica/dscontrol.c:acpi_ds_exec_end_control_op
  - drivers/acpi/acpica/dscontrol.c:acpi_ds_exec_end_control_op
  - drivers/acpi/acpica/dswscope.c:acpi_ds_scope_stack_pop
  - drivers/acpi/acpica/dswscope.c:acpi_ds_scope_stack_clear
  - drivers/acpi/acpica/dswstate.c:acpi_ds_delete_walk_state
  - drivers/acpi/acpica/dswstate.c:acpi_ds_delete_walk_state
  - drivers/acpi/acpica/dswstate.c:acpi_ds_delete_walk_state
  - drivers/acpi/acpica/dswstate.c:acpi_ds_result_pop
  - drivers/acpi/acpica/evmisc.c:acpi_ev_notify_dispatch
  - drivers/acpi/acpica/evmisc.c:acpi_ev_queue_notify_request
  - drivers/acpi/acpica/psparse.c:acpi_ps_parse_aml
  - drivers/acpi/acpica/psscope.c:acpi_ps_cleanup_scope
  - drivers/acpi/acpica/psscope.c:acpi_ps_pop_scope
  - drivers/acpi/acpica/utdelete.c:acpi_ut_update_object_reference
  - drivers/acpi/acpica/utdelete.c:acpi_ut_update_object_reference
  - drivers/acpi/acpica/utmisc.c:acpi_ut_walk_package_tree
  - drivers/acpi/acpica/utmisc.c:acpi_ut_walk_package_tree
```
**Symbols:**

```
ffffffff815ec6a8-ffffffff815ec6c8: acpi_ut_delete_generic_state (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void acpi_ut_delete_generic_state(union acpi_generic_state *state);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/utstate.c (ffffffff8161e38d)
Location: drivers/acpi/acpica/utstate.c:264
Inline: False
Direct callers:
  - drivers/acpi/acpica/dscontrol.c:acpi_ds_exec_end_control_op
  - drivers/acpi/acpica/dscontrol.c:acpi_ds_exec_end_control_op
  - drivers/acpi/acpica/dswscope.c:acpi_ds_scope_stack_pop
  - drivers/acpi/acpica/dswscope.c:acpi_ds_scope_stack_clear
  - drivers/acpi/acpica/dswstate.c:acpi_ds_delete_walk_state
  - drivers/acpi/acpica/dswstate.c:acpi_ds_delete_walk_state
  - drivers/acpi/acpica/dswstate.c:acpi_ds_delete_walk_state
  - drivers/acpi/acpica/dswstate.c:acpi_ds_result_pop
  - drivers/acpi/acpica/evmisc.c:acpi_ev_notify_dispatch
  - drivers/acpi/acpica/evmisc.c:acpi_ev_queue_notify_request
  - drivers/acpi/acpica/psobject.c:acpi_ps_complete_op
  - drivers/acpi/acpica/psparse.c:acpi_ps_parse_aml
  - drivers/acpi/acpica/psscope.c:acpi_ps_cleanup_scope
  - drivers/acpi/acpica/psscope.c:acpi_ps_pop_scope
  - drivers/acpi/acpica/utdelete.c:acpi_ut_update_object_reference
  - drivers/acpi/acpica/utdelete.c:acpi_ut_update_object_reference
  - drivers/acpi/acpica/utmisc.c:acpi_ut_walk_package_tree
  - drivers/acpi/acpica/utmisc.c:acpi_ut_walk_package_tree
```
**Symbols:**

```
ffffffff8161e38d-ffffffff8161e3b8: acpi_ut_delete_generic_state (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void acpi_ut_delete_generic_state(union acpi_generic_state *state);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/utstate.c (ffffffff8163823d)
Location: drivers/acpi/acpica/utstate.c:264
Inline: False
Direct callers:
  - drivers/acpi/acpica/dscontrol.c:acpi_ds_exec_end_control_op
  - drivers/acpi/acpica/dscontrol.c:acpi_ds_exec_end_control_op
  - drivers/acpi/acpica/dswscope.c:acpi_ds_scope_stack_pop
  - drivers/acpi/acpica/dswscope.c:acpi_ds_scope_stack_clear
  - drivers/acpi/acpica/dswstate.c:acpi_ds_delete_walk_state
  - drivers/acpi/acpica/dswstate.c:acpi_ds_delete_walk_state
  - drivers/acpi/acpica/dswstate.c:acpi_ds_delete_walk_state
  - drivers/acpi/acpica/dswstate.c:acpi_ds_result_pop
  - drivers/acpi/acpica/evmisc.c:acpi_ev_notify_dispatch
  - drivers/acpi/acpica/evmisc.c:acpi_ev_queue_notify_request
  - drivers/acpi/acpica/psobject.c:acpi_ps_complete_op
  - drivers/acpi/acpica/psparse.c:acpi_ps_parse_aml
  - drivers/acpi/acpica/psscope.c:acpi_ps_cleanup_scope
  - drivers/acpi/acpica/psscope.c:acpi_ps_pop_scope
  - drivers/acpi/acpica/utdelete.c:acpi_ut_update_object_reference
  - drivers/acpi/acpica/utdelete.c:acpi_ut_update_object_reference
  - drivers/acpi/acpica/utmisc.c:acpi_ut_walk_package_tree
  - drivers/acpi/acpica/utmisc.c:acpi_ut_walk_package_tree
```
**Symbols:**

```
ffffffff8163823d-ffffffff81638268: acpi_ut_delete_generic_state (STB_GLOBAL)
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
