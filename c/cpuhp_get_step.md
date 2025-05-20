# Function: <code>cpuhp_get_step</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>4.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/cpu.c (ffffffff81083a04)
Location: kernel/cpu.c:1368
Inline: True
Inline callers:
  - kernel/cpu.c:show_cpuhp_states
  - kernel/cpu.c:write_cpuhp_target
  - kernel/cpu.c:__cpuhp_remove_state
  - kernel/cpu.c:cpuhp_store_callbacks
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/cpu.c (ffffffff810883f4)
Location: kernel/cpu.c:106
Inline: True
Inline callers:
  - kernel/cpu.c:show_cpuhp_states
  - kernel/cpu.c:write_cpuhp_target
  - kernel/cpu.c:__cpuhp_remove_state
  - kernel/cpu.c:__cpuhp_state_remove_instance
  - kernel/cpu.c:__cpuhp_state_add_instance
  - kernel/cpu.c:cpuhp_store_callbacks
  - kernel/cpu.c:cpuhp_up_callbacks
  - kernel/cpu.c:cpuhp_invoke_callback
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/cpu.c (ffffffff81085304)
Location: kernel/cpu.c:115
Inline: True
Inline callers:
  - kernel/cpu.c:show_cpuhp_states
  - kernel/cpu.c:write_cpuhp_target
  - kernel/cpu.c:__cpuhp_remove_state_cpuslocked
  - kernel/cpu.c:__cpuhp_state_remove_instance
  - kernel/cpu.c:__cpuhp_setup_state_cpuslocked
  - kernel/cpu.c:__cpuhp_setup_state_cpuslocked
  - kernel/cpu.c:__cpuhp_state_add_instance_cpuslocked
  - kernel/cpu.c:cpuhp_up_callbacks
  - kernel/cpu.c:cpuhp_invoke_callback
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/cpu.c (ffffffff8108bfa4)
Location: kernel/cpu.c:139
Inline: True
Inline callers:
  - kernel/cpu.c:show_cpuhp_states
  - kernel/cpu.c:write_cpuhp_fail
  - kernel/cpu.c:write_cpuhp_target
  - kernel/cpu.c:__cpuhp_remove_state_cpuslocked
  - kernel/cpu.c:__cpuhp_state_remove_instance
  - kernel/cpu.c:__cpuhp_setup_state_cpuslocked
  - kernel/cpu.c:__cpuhp_setup_state_cpuslocked
  - kernel/cpu.c:__cpuhp_state_add_instance_cpuslocked
  - kernel/cpu.c:cpuhp_issue_call
  - kernel/cpu.c:_cpu_up
  - kernel/cpu.c:_cpu_down
  - kernel/cpu.c:cpuhp_thread_fun
  - kernel/cpu.c:cpuhp_invoke_callback
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/cpu.c (ffffffff8108f658)
Location: kernel/cpu.c:130
Inline: True
Inline callers:
  - kernel/cpu.c:write_cpuhp_fail
  - kernel/cpu.c:write_cpuhp_target
  - kernel/cpu.c:__cpuhp_remove_state_cpuslocked
  - kernel/cpu.c:__cpuhp_state_remove_instance
  - kernel/cpu.c:__cpuhp_setup_state_cpuslocked
  - kernel/cpu.c:__cpuhp_setup_state_cpuslocked
  - kernel/cpu.c:__cpuhp_state_add_instance_cpuslocked
  - kernel/cpu.c:_cpu_up
  - kernel/cpu.c:_cpu_down
  - kernel/cpu.c:cpuhp_thread_fun
  - kernel/cpu.c:cpuhp_invoke_callback
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/cpu.c (ffffffff81097958)
Location: kernel/cpu.c:128
Inline: True
Inline callers:
  - kernel/cpu.c:write_cpuhp_fail
  - kernel/cpu.c:write_cpuhp_target
  - kernel/cpu.c:__cpuhp_remove_state_cpuslocked
  - kernel/cpu.c:__cpuhp_state_remove_instance
  - kernel/cpu.c:__cpuhp_setup_state_cpuslocked
  - kernel/cpu.c:__cpuhp_setup_state_cpuslocked
  - kernel/cpu.c:__cpuhp_state_add_instance_cpuslocked
  - kernel/cpu.c:cpuhp_invoke_callback
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/cpu.c (ffffffff8109bf20)
Location: kernel/cpu.c:129
Inline: True
Inline callers:
  - kernel/cpu.c:write_cpuhp_fail
  - kernel/cpu.c:write_cpuhp_target
  - kernel/cpu.c:__cpuhp_remove_state_cpuslocked
  - kernel/cpu.c:__cpuhp_state_remove_instance
  - kernel/cpu.c:__cpuhp_setup_state_cpuslocked
  - kernel/cpu.c:__cpuhp_setup_state_cpuslocked
  - kernel/cpu.c:__cpuhp_state_add_instance_cpuslocked
  - kernel/cpu.c:cpuhp_invoke_callback
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
In kernel/cpu.c (ffffffff810a24a0)
Location: kernel/cpu.c:132
Inline: True
Inline callers:
  - kernel/cpu.c:write_cpuhp_fail
  - kernel/cpu.c:write_cpuhp_target
  - kernel/cpu.c:__cpuhp_remove_state_cpuslocked
  - kernel/cpu.c:__cpuhp_state_remove_instance
  - kernel/cpu.c:__cpuhp_setup_state_cpuslocked
  - kernel/cpu.c:__cpuhp_setup_state_cpuslocked
  - kernel/cpu.c:__cpuhp_state_add_instance_cpuslocked
  - kernel/cpu.c:cpuhp_invoke_callback
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
In kernel/cpu.c (ffffffff810a9170)
Location: kernel/cpu.c:133
Inline: True
Inline callers:
  - kernel/cpu.c:write_cpuhp_fail
  - kernel/cpu.c:write_cpuhp_target
  - kernel/cpu.c:__cpuhp_remove_state_cpuslocked
  - kernel/cpu.c:__cpuhp_state_remove_instance
  - kernel/cpu.c:__cpuhp_setup_state_cpuslocked
  - kernel/cpu.c:__cpuhp_setup_state_cpuslocked
  - kernel/cpu.c:__cpuhp_state_add_instance_cpuslocked
  - kernel/cpu.c:cpuhp_issue_call
  - kernel/cpu.c:cpuhp_invoke_callback
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
In kernel/cpu.c (ffffffff810a4bc0)
Location: kernel/cpu.c:133
Inline: True
Inline callers:
  - kernel/cpu.c:write_cpuhp_fail
  - kernel/cpu.c:write_cpuhp_target
  - kernel/cpu.c:__cpuhp_remove_state_cpuslocked
  - kernel/cpu.c:__cpuhp_state_remove_instance
  - kernel/cpu.c:__cpuhp_setup_state_cpuslocked
  - kernel/cpu.c:__cpuhp_setup_state_cpuslocked
  - kernel/cpu.c:__cpuhp_state_add_instance_cpuslocked
  - kernel/cpu.c:cpuhp_issue_call
  - kernel/cpu.c:cpuhp_invoke_callback
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
In kernel/cpu.c (ffffffff810a58b4)
Location: kernel/cpu.c:135
Inline: True
Inline callers:
  - kernel/cpu.c:write_cpuhp_fail
  - kernel/cpu.c:write_cpuhp_target
  - kernel/cpu.c:__cpuhp_remove_state_cpuslocked
  - kernel/cpu.c:__cpuhp_state_remove_instance
  - kernel/cpu.c:__cpuhp_setup_state_cpuslocked
  - kernel/cpu.c:__cpuhp_setup_state_cpuslocked
  - kernel/cpu.c:__cpuhp_state_add_instance_cpuslocked
  - kernel/cpu.c:cpuhp_issue_call
  - kernel/cpu.c:cpuhp_next_state
  - kernel/cpu.c:cpuhp_invoke_callback
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/cpu.c (ffffffff810b7092)
Location: kernel/cpu.c:144
Inline: True
Inline callers:
  - kernel/cpu.c:fail_store
  - kernel/cpu.c:target_store
  - kernel/cpu.c:__cpuhp_remove_state_cpuslocked
  - kernel/cpu.c:__cpuhp_state_remove_instance
  - kernel/cpu.c:__cpuhp_setup_state_cpuslocked
  - kernel/cpu.c:__cpuhp_setup_state_cpuslocked
  - kernel/cpu.c:__cpuhp_state_add_instance_cpuslocked
  - kernel/cpu.c:cpuhp_issue_call
  - kernel/cpu.c:_cpu_up
  - kernel/cpu.c:_cpu_down
  - kernel/cpu.c:cpuhp_next_state
  - kernel/cpu.c:cpuhp_invoke_callback
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
In kernel/cpu.c (ffffffff810cd805)
Location: kernel/cpu.c:145
Inline: True
Inline callers:
  - kernel/cpu.c:fail_store
  - kernel/cpu.c:target_store
  - kernel/cpu.c:__cpuhp_remove_state_cpuslocked
  - kernel/cpu.c:__cpuhp_state_remove_instance
  - kernel/cpu.c:__cpuhp_setup_state_cpuslocked
  - kernel/cpu.c:__cpuhp_setup_state_cpuslocked
  - kernel/cpu.c:__cpuhp_state_add_instance_cpuslocked
  - kernel/cpu.c:cpuhp_issue_call
  - kernel/cpu.c:_cpu_up
  - kernel/cpu.c:_cpu_down
  - kernel/cpu.c:cpuhp_next_state
  - kernel/cpu.c:cpuhp_invoke_callback
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
In kernel/cpu.c (ffffffff810eb8e5)
Location: kernel/cpu.c:145
Inline: True
Inline callers:
  - kernel/cpu.c:fail_store
  - kernel/cpu.c:target_store
  - kernel/cpu.c:__cpuhp_remove_state_cpuslocked
  - kernel/cpu.c:__cpuhp_state_remove_instance
  - kernel/cpu.c:__cpuhp_setup_state_cpuslocked
  - kernel/cpu.c:__cpuhp_setup_state_cpuslocked
  - kernel/cpu.c:__cpuhp_state_add_instance_cpuslocked
  - kernel/cpu.c:cpuhp_issue_call
  - kernel/cpu.c:_cpu_up
  - kernel/cpu.c:_cpu_down
  - kernel/cpu.c:__cpuhp_invoke_callback_range
  - kernel/cpu.c:cpuhp_next_state
  - kernel/cpu.c:cpuhp_invoke_callback
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
In kernel/cpu.c (ffffffff810f75c5)
Location: kernel/cpu.c:148
Inline: True
Inline callers:
  - kernel/cpu.c:fail_store
  - kernel/cpu.c:target_store
  - kernel/cpu.c:__cpuhp_remove_state_cpuslocked
  - kernel/cpu.c:__cpuhp_state_remove_instance
  - kernel/cpu.c:__cpuhp_setup_state_cpuslocked
  - kernel/cpu.c:__cpuhp_setup_state_cpuslocked
  - kernel/cpu.c:__cpuhp_state_add_instance_cpuslocked
  - kernel/cpu.c:_cpu_up
  - kernel/cpu.c:_cpu_down
  - kernel/cpu.c:__cpuhp_invoke_callback_range
  - kernel/cpu.c:cpuhp_next_state
  - kernel/cpu.c:cpuhp_invoke_callback
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
In kernel/cpu.c (ffffffff81100975)
Location: kernel/cpu.c:148
Inline: True
Inline callers:
  - kernel/cpu.c:fail_store
  - kernel/cpu.c:target_store
  - kernel/cpu.c:__cpuhp_remove_state_cpuslocked
  - kernel/cpu.c:__cpuhp_state_remove_instance
  - kernel/cpu.c:__cpuhp_setup_state_cpuslocked
  - kernel/cpu.c:__cpuhp_setup_state_cpuslocked
  - kernel/cpu.c:__cpuhp_state_add_instance_cpuslocked
  - kernel/cpu.c:_cpu_up
  - kernel/cpu.c:_cpu_down
  - kernel/cpu.c:__cpuhp_invoke_callback_range
  - kernel/cpu.c:cpuhp_next_state
  - kernel/cpu.c:cpuhp_invoke_callback
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
In kernel/cpu.c (ffff8000100f7580)
Location: kernel/cpu.c:132
Inline: True
Inline callers:
  - kernel/cpu.c:write_cpuhp_fail
  - kernel/cpu.c:write_cpuhp_target
  - kernel/cpu.c:__cpuhp_remove_state_cpuslocked
  - kernel/cpu.c:__cpuhp_state_remove_instance
  - kernel/cpu.c:__cpuhp_setup_state_cpuslocked
  - kernel/cpu.c:__cpuhp_setup_state_cpuslocked
  - kernel/cpu.c:__cpuhp_state_add_instance_cpuslocked
  - kernel/cpu.c:cpuhp_invoke_callback
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
In kernel/cpu.c (c0355964)
Location: kernel/cpu.c:132
Inline: True
Inline callers:
  - kernel/cpu.c:write_cpuhp_fail
  - kernel/cpu.c:write_cpuhp_target
  - kernel/cpu.c:__cpuhp_remove_state_cpuslocked
  - kernel/cpu.c:__cpuhp_state_remove_instance
  - kernel/cpu.c:__cpuhp_setup_state_cpuslocked
  - kernel/cpu.c:__cpuhp_setup_state_cpuslocked
  - kernel/cpu.c:__cpuhp_state_add_instance_cpuslocked
  - kernel/cpu.c:cpuhp_invoke_callback
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
In kernel/cpu.c (c00000000013dc80)
Location: kernel/cpu.c:132
Inline: True
Inline callers:
  - kernel/cpu.c:write_cpuhp_fail
  - kernel/cpu.c:write_cpuhp_target
  - kernel/cpu.c:__cpuhp_remove_state_cpuslocked
  - kernel/cpu.c:__cpuhp_state_remove_instance
  - kernel/cpu.c:__cpuhp_setup_state_cpuslocked
  - kernel/cpu.c:__cpuhp_setup_state_cpuslocked
  - kernel/cpu.c:__cpuhp_state_add_instance_cpuslocked
  - kernel/cpu.c:cpuhp_issue_call
  - kernel/cpu.c:cpuhp_invoke_callback
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
In kernel/cpu.c (ffffffe0000c3b0e)
Location: kernel/cpu.c:132
Inline: True
Inline callers:
  - kernel/cpu.c:__cpuhp_remove_state_cpuslocked
  - kernel/cpu.c:__cpuhp_state_remove_instance
  - kernel/cpu.c:__cpuhp_setup_state_cpuslocked
  - kernel/cpu.c:__cpuhp_setup_state_cpuslocked
  - kernel/cpu.c:__cpuhp_state_add_instance_cpuslocked
  - kernel/cpu.c:cpuhp_issue_call
  - kernel/cpu.c:cpuhp_invoke_callback
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
In kernel/cpu.c (ffffffff8109bdc0)
Location: kernel/cpu.c:132
Inline: True
Inline callers:
  - kernel/cpu.c:write_cpuhp_fail
  - kernel/cpu.c:write_cpuhp_target
  - kernel/cpu.c:__cpuhp_remove_state_cpuslocked
  - kernel/cpu.c:__cpuhp_state_remove_instance
  - kernel/cpu.c:__cpuhp_setup_state_cpuslocked
  - kernel/cpu.c:__cpuhp_setup_state_cpuslocked
  - kernel/cpu.c:__cpuhp_state_add_instance_cpuslocked
  - kernel/cpu.c:cpuhp_invoke_callback
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
In kernel/cpu.c (ffffffff8108a7f0)
Location: kernel/cpu.c:132
Inline: True
Inline callers:
  - kernel/cpu.c:write_cpuhp_fail
  - kernel/cpu.c:write_cpuhp_target
  - kernel/cpu.c:__cpuhp_remove_state_cpuslocked
  - kernel/cpu.c:__cpuhp_state_remove_instance
  - kernel/cpu.c:__cpuhp_setup_state_cpuslocked
  - kernel/cpu.c:__cpuhp_setup_state_cpuslocked
  - kernel/cpu.c:__cpuhp_state_add_instance_cpuslocked
  - kernel/cpu.c:cpuhp_invoke_callback
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
In kernel/cpu.c (ffffffff8109bd70)
Location: kernel/cpu.c:132
Inline: True
Inline callers:
  - kernel/cpu.c:write_cpuhp_fail
  - kernel/cpu.c:write_cpuhp_target
  - kernel/cpu.c:__cpuhp_remove_state_cpuslocked
  - kernel/cpu.c:__cpuhp_state_remove_instance
  - kernel/cpu.c:__cpuhp_setup_state_cpuslocked
  - kernel/cpu.c:__cpuhp_setup_state_cpuslocked
  - kernel/cpu.c:__cpuhp_state_add_instance_cpuslocked
  - kernel/cpu.c:cpuhp_invoke_callback
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
In kernel/cpu.c (ffffffff810a3970)
Location: kernel/cpu.c:132
Inline: True
Inline callers:
  - kernel/cpu.c:write_cpuhp_fail
  - kernel/cpu.c:write_cpuhp_target
  - kernel/cpu.c:__cpuhp_remove_state_cpuslocked
  - kernel/cpu.c:__cpuhp_state_remove_instance
  - kernel/cpu.c:__cpuhp_setup_state_cpuslocked
  - kernel/cpu.c:__cpuhp_setup_state_cpuslocked
  - kernel/cpu.c:__cpuhp_state_add_instance_cpuslocked
  - kernel/cpu.c:cpuhp_invoke_callback
```
</details>
</li>
</ul>

## Differences
