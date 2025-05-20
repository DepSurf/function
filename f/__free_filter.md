# Function: <code>__free_filter</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void __free_filter(struct event_filter *filter);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_events_filter.c (ffffffff81163330)
Location: kernel/trace/trace_events_filter.c:837
Inline: False
Direct callers:
  - kernel/trace/trace_events_filter.c:free_event_filter
  - kernel/trace/trace_events_filter.c:apply_event_filter
  - kernel/trace/trace_events_filter.c:apply_event_filter
  - kernel/trace/trace_events_filter.c:apply_subsystem_event_filter
  - kernel/trace/trace_events_filter.c:apply_subsystem_event_filter
  - kernel/trace/trace_events_filter.c:apply_subsystem_event_filter
  - kernel/trace/trace_events_filter.c:apply_subsystem_event_filter
  - kernel/trace/trace_events_filter.c:apply_subsystem_event_filter
  - kernel/trace/trace_events_filter.c:apply_subsystem_event_filter
  - kernel/trace/trace_events_filter.c:ftrace_profile_free_filter
  - kernel/trace/trace_events_filter.c:ftrace_profile_set_filter
```
**Symbols:**

```
ffffffff81163330-ffffffff81163357: __free_filter (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void __free_filter(struct event_filter *filter);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_events_filter.c (ffffffff8116dae0)
Location: kernel/trace/trace_events_filter.c:834
Inline: False
Direct callers:
  - kernel/trace/trace_events_filter.c:ftrace_profile_set_filter
  - kernel/trace/trace_events_filter.c:ftrace_profile_free_filter
  - kernel/trace/trace_events_filter.c:apply_subsystem_event_filter
  - kernel/trace/trace_events_filter.c:apply_subsystem_event_filter
  - kernel/trace/trace_events_filter.c:apply_subsystem_event_filter
  - kernel/trace/trace_events_filter.c:apply_subsystem_event_filter
  - kernel/trace/trace_events_filter.c:apply_subsystem_event_filter
  - kernel/trace/trace_events_filter.c:apply_event_filter
  - kernel/trace/trace_events_filter.c:apply_event_filter
  - kernel/trace/trace_events_filter.c:free_event_filter
```
**Symbols:**

```
ffffffff8116dae0-ffffffff8116db07: __free_filter (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void __free_filter(struct event_filter *filter);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_events_filter.c (ffffffff811791b0)
Location: kernel/trace/trace_events_filter.c:865
Inline: False
Direct callers:
  - kernel/trace/trace_events_filter.c:ftrace_profile_set_filter
  - kernel/trace/trace_events_filter.c:ftrace_profile_free_filter
  - kernel/trace/trace_events_filter.c:apply_subsystem_event_filter
  - kernel/trace/trace_events_filter.c:apply_subsystem_event_filter
  - kernel/trace/trace_events_filter.c:apply_subsystem_event_filter
  - kernel/trace/trace_events_filter.c:apply_subsystem_event_filter
  - kernel/trace/trace_events_filter.c:apply_subsystem_event_filter
  - kernel/trace/trace_events_filter.c:apply_event_filter
  - kernel/trace/trace_events_filter.c:apply_event_filter
  - kernel/trace/trace_events_filter.c:free_event_filter
```
**Symbols:**

```
ffffffff811791b0-ffffffff811791d7: __free_filter (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/trace/trace_events_filter.c (ffffffff8117e29c)
Location: kernel/trace/trace_events_filter.c:865
Inline: True
Inline callers:
  - kernel/trace/trace_events_filter.c:ftrace_profile_set_filter
  - kernel/trace/trace_events_filter.c:ftrace_profile_free_filter
  - kernel/trace/trace_events_filter.c:apply_subsystem_event_filter
  - kernel/trace/trace_events_filter.c:apply_subsystem_event_filter
  - kernel/trace/trace_events_filter.c:apply_subsystem_event_filter
  - kernel/trace/trace_events_filter.c:apply_subsystem_event_filter
  - kernel/trace/trace_events_filter.c:apply_subsystem_event_filter
  - kernel/trace/trace_events_filter.c:apply_event_filter
  - kernel/trace/trace_events_filter.c:apply_event_filter
  - kernel/trace/trace_events_filter.c:create_filter
Direct callers:
  - kernel/trace/trace_events_filter.c:ftrace_profile_set_filter
  - kernel/trace/trace_events_filter.c:ftrace_profile_free_filter
  - kernel/trace/trace_events_filter.c:apply_subsystem_event_filter
  - kernel/trace/trace_events_filter.c:apply_subsystem_event_filter
  - kernel/trace/trace_events_filter.c:apply_subsystem_event_filter
  - kernel/trace/trace_events_filter.c:apply_subsystem_event_filter
  - kernel/trace/trace_events_filter.c:apply_subsystem_event_filter
  - kernel/trace/trace_events_filter.c:apply_event_filter
  - kernel/trace/trace_events_filter.c:create_filter
```
**Symbols:**

```
ffffffff8117c480-ffffffff8117c4a1: __free_filter.part.21 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/trace/trace_events_filter.c (ffffffff8118bb2c)
Location: kernel/trace/trace_events_filter.c:864
Inline: True
Inline callers:
  - kernel/trace/trace_events_filter.c:ftrace_profile_set_filter
  - kernel/trace/trace_events_filter.c:ftrace_profile_free_filter
  - kernel/trace/trace_events_filter.c:apply_subsystem_event_filter
  - kernel/trace/trace_events_filter.c:apply_subsystem_event_filter
  - kernel/trace/trace_events_filter.c:apply_subsystem_event_filter
  - kernel/trace/trace_events_filter.c:apply_subsystem_event_filter
  - kernel/trace/trace_events_filter.c:apply_subsystem_event_filter
  - kernel/trace/trace_events_filter.c:apply_event_filter
  - kernel/trace/trace_events_filter.c:apply_event_filter
  - kernel/trace/trace_events_filter.c:create_filter
Direct callers:
  - kernel/trace/trace_events_filter.c:ftrace_profile_set_filter
  - kernel/trace/trace_events_filter.c:ftrace_profile_free_filter
  - kernel/trace/trace_events_filter.c:apply_subsystem_event_filter
  - kernel/trace/trace_events_filter.c:apply_subsystem_event_filter
  - kernel/trace/trace_events_filter.c:apply_subsystem_event_filter
  - kernel/trace/trace_events_filter.c:apply_subsystem_event_filter
  - kernel/trace/trace_events_filter.c:apply_subsystem_event_filter
  - kernel/trace/trace_events_filter.c:apply_event_filter
  - kernel/trace/trace_events_filter.c:create_filter
```
**Symbols:**

```
ffffffff81189d10-ffffffff81189d31: __free_filter.part.21 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/trace/trace_events_filter.c (ffffffff8119a3d6)
Location: kernel/trace/trace_events_filter.c:1019
Inline: True
Inline callers:
  - kernel/trace/trace_events_filter.c:ftrace_profile_set_filter
  - kernel/trace/trace_events_filter.c:ftrace_profile_free_filter
  - kernel/trace/trace_events_filter.c:apply_subsystem_event_filter
  - kernel/trace/trace_events_filter.c:apply_subsystem_event_filter
  - kernel/trace/trace_events_filter.c:apply_subsystem_event_filter
  - kernel/trace/trace_events_filter.c:apply_subsystem_event_filter
  - kernel/trace/trace_events_filter.c:apply_subsystem_event_filter
  - kernel/trace/trace_events_filter.c:apply_event_filter
  - kernel/trace/trace_events_filter.c:apply_event_filter
  - kernel/trace/trace_events_filter.c:create_filter_start
  - kernel/trace/trace_events_filter.c:free_event_filter
Direct callers:
  - kernel/trace/trace_events_filter.c:ftrace_profile_set_filter
  - kernel/trace/trace_events_filter.c:ftrace_profile_free_filter
  - kernel/trace/trace_events_filter.c:apply_subsystem_event_filter
  - kernel/trace/trace_events_filter.c:apply_subsystem_event_filter
  - kernel/trace/trace_events_filter.c:apply_subsystem_event_filter
  - kernel/trace/trace_events_filter.c:apply_subsystem_event_filter
  - kernel/trace/trace_events_filter.c:apply_subsystem_event_filter
  - kernel/trace/trace_events_filter.c:apply_event_filter
  - kernel/trace/trace_events_filter.c:create_filter_start
  - kernel/trace/trace_events_filter.c:free_event_filter
```
**Symbols:**

```
ffffffff81198740-ffffffff8119879b: __free_filter.part.7 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/trace/trace_events_filter.c (ffffffff811a85c6)
Location: kernel/trace/trace_events_filter.c:1009
Inline: True
Inline callers:
  - kernel/trace/trace_events_filter.c:ftrace_profile_set_filter
  - kernel/trace/trace_events_filter.c:ftrace_profile_free_filter
  - kernel/trace/trace_events_filter.c:apply_subsystem_event_filter
  - kernel/trace/trace_events_filter.c:apply_subsystem_event_filter
  - kernel/trace/trace_events_filter.c:apply_subsystem_event_filter
  - kernel/trace/trace_events_filter.c:apply_subsystem_event_filter
  - kernel/trace/trace_events_filter.c:apply_subsystem_event_filter
  - kernel/trace/trace_events_filter.c:apply_event_filter
  - kernel/trace/trace_events_filter.c:apply_event_filter
  - kernel/trace/trace_events_filter.c:create_filter_start
  - kernel/trace/trace_events_filter.c:free_event_filter
Direct callers:
  - kernel/trace/trace_events_filter.c:ftrace_profile_set_filter
  - kernel/trace/trace_events_filter.c:ftrace_profile_free_filter
  - kernel/trace/trace_events_filter.c:apply_subsystem_event_filter
  - kernel/trace/trace_events_filter.c:apply_subsystem_event_filter
  - kernel/trace/trace_events_filter.c:apply_subsystem_event_filter
  - kernel/trace/trace_events_filter.c:apply_subsystem_event_filter
  - kernel/trace/trace_events_filter.c:apply_subsystem_event_filter
  - kernel/trace/trace_events_filter.c:apply_event_filter
  - kernel/trace/trace_events_filter.c:create_filter_start
  - kernel/trace/trace_events_filter.c:free_event_filter
```
**Symbols:**

```
ffffffff811a6880-ffffffff811a68db: __free_filter.part.7 (STB_LOCAL)
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
In kernel/trace/trace_events_filter.c (ffffffff811b64f6)
Location: kernel/trace/trace_events_filter.c:1028
Inline: True
Inline callers:
  - kernel/trace/trace_events_filter.c:ftrace_profile_set_filter
  - kernel/trace/trace_events_filter.c:ftrace_profile_free_filter
  - kernel/trace/trace_events_filter.c:apply_subsystem_event_filter
  - kernel/trace/trace_events_filter.c:apply_subsystem_event_filter
  - kernel/trace/trace_events_filter.c:apply_subsystem_event_filter
  - kernel/trace/trace_events_filter.c:apply_subsystem_event_filter
  - kernel/trace/trace_events_filter.c:apply_subsystem_event_filter
  - kernel/trace/trace_events_filter.c:apply_event_filter
  - kernel/trace/trace_events_filter.c:apply_event_filter
  - kernel/trace/trace_events_filter.c:create_filter_start
  - kernel/trace/trace_events_filter.c:free_event_filter
Direct callers:
  - kernel/trace/trace_events_filter.c:ftrace_profile_set_filter
  - kernel/trace/trace_events_filter.c:ftrace_profile_free_filter
  - kernel/trace/trace_events_filter.c:apply_subsystem_event_filter
  - kernel/trace/trace_events_filter.c:apply_subsystem_event_filter
  - kernel/trace/trace_events_filter.c:apply_subsystem_event_filter
  - kernel/trace/trace_events_filter.c:apply_subsystem_event_filter
  - kernel/trace/trace_events_filter.c:apply_subsystem_event_filter
  - kernel/trace/trace_events_filter.c:apply_event_filter
  - kernel/trace/trace_events_filter.c:apply_event_filter
  - kernel/trace/trace_events_filter.c:create_filter_start
  - kernel/trace/trace_events_filter.c:free_event_filter
```
**Symbols:**

```
ffffffff811b47c0-ffffffff811b4819: __free_filter.part.0 (STB_LOCAL)
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
In kernel/trace/trace_events_filter.c (ffffffff811c1b86)
Location: kernel/trace/trace_events_filter.c:1030
Inline: True
Inline callers:
  - kernel/trace/trace_events_filter.c:ftrace_profile_set_filter
  - kernel/trace/trace_events_filter.c:ftrace_profile_free_filter
  - kernel/trace/trace_events_filter.c:apply_subsystem_event_filter
  - kernel/trace/trace_events_filter.c:apply_subsystem_event_filter
  - kernel/trace/trace_events_filter.c:apply_subsystem_event_filter
  - kernel/trace/trace_events_filter.c:apply_subsystem_event_filter
  - kernel/trace/trace_events_filter.c:apply_subsystem_event_filter
  - kernel/trace/trace_events_filter.c:apply_subsystem_event_filter
  - kernel/trace/trace_events_filter.c:apply_event_filter
  - kernel/trace/trace_events_filter.c:apply_event_filter
  - kernel/trace/trace_events_filter.c:create_filter_start
  - kernel/trace/trace_events_filter.c:free_event_filter
Direct callers:
  - kernel/trace/trace_events_filter.c:ftrace_profile_set_filter
  - kernel/trace/trace_events_filter.c:ftrace_profile_free_filter
  - kernel/trace/trace_events_filter.c:apply_subsystem_event_filter
  - kernel/trace/trace_events_filter.c:apply_subsystem_event_filter
  - kernel/trace/trace_events_filter.c:apply_subsystem_event_filter
  - kernel/trace/trace_events_filter.c:apply_subsystem_event_filter
  - kernel/trace/trace_events_filter.c:apply_subsystem_event_filter
  - kernel/trace/trace_events_filter.c:apply_subsystem_event_filter
  - kernel/trace/trace_events_filter.c:apply_event_filter
  - kernel/trace/trace_events_filter.c:apply_event_filter
  - kernel/trace/trace_events_filter.c:create_filter_start
  - kernel/trace/trace_events_filter.c:free_event_filter
```
**Symbols:**

```
ffffffff811bfdf0-ffffffff811bfe49: __free_filter.part.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/trace/trace_events_filter.c (ffffffff811db7f5)
Location: kernel/trace/trace_events_filter.c:1030
Inline: True
Inline callers:
  - kernel/trace/trace_events_filter.c:ftrace_profile_set_filter
  - kernel/trace/trace_events_filter.c:ftrace_profile_free_filter
  - kernel/trace/trace_events_filter.c:apply_subsystem_event_filter
  - kernel/trace/trace_events_filter.c:apply_subsystem_event_filter
  - kernel/trace/trace_events_filter.c:apply_subsystem_event_filter
  - kernel/trace/trace_events_filter.c:apply_event_filter
  - kernel/trace/trace_events_filter.c:apply_event_filter
  - kernel/trace/trace_events_filter.c:process_system_preds
  - kernel/trace/trace_events_filter.c:process_system_preds
  - kernel/trace/trace_events_filter.c:process_system_preds
  - kernel/trace/trace_events_filter.c:free_event_filter
Direct callers:
  - kernel/trace/trace_events_filter.c:ftrace_profile_set_filter
  - kernel/trace/trace_events_filter.c:ftrace_profile_free_filter
  - kernel/trace/trace_events_filter.c:apply_subsystem_event_filter
  - kernel/trace/trace_events_filter.c:apply_subsystem_event_filter
  - kernel/trace/trace_events_filter.c:apply_subsystem_event_filter
  - kernel/trace/trace_events_filter.c:apply_event_filter
  - kernel/trace/trace_events_filter.c:apply_event_filter
  - kernel/trace/trace_events_filter.c:process_system_preds
  - kernel/trace/trace_events_filter.c:process_system_preds
  - kernel/trace/trace_events_filter.c:process_system_preds
  - kernel/trace/trace_events_filter.c:free_event_filter
```
**Symbols:**

```
ffffffff811d9d90-ffffffff811d9de9: __free_filter.part.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/trace/trace_events_filter.c (ffffffff811d8925)
Location: kernel/trace/trace_events_filter.c:1030
Inline: True
Inline callers:
  - kernel/trace/trace_events_filter.c:ftrace_profile_set_filter
  - kernel/trace/trace_events_filter.c:ftrace_profile_free_filter
  - kernel/trace/trace_events_filter.c:apply_subsystem_event_filter
  - kernel/trace/trace_events_filter.c:apply_subsystem_event_filter
  - kernel/trace/trace_events_filter.c:apply_subsystem_event_filter
  - kernel/trace/trace_events_filter.c:apply_event_filter
  - kernel/trace/trace_events_filter.c:apply_event_filter
  - kernel/trace/trace_events_filter.c:process_system_preds
  - kernel/trace/trace_events_filter.c:process_system_preds
  - kernel/trace/trace_events_filter.c:process_system_preds
  - kernel/trace/trace_events_filter.c:free_event_filter
Direct callers:
  - kernel/trace/trace_events_filter.c:ftrace_profile_set_filter
  - kernel/trace/trace_events_filter.c:ftrace_profile_free_filter
  - kernel/trace/trace_events_filter.c:apply_subsystem_event_filter
  - kernel/trace/trace_events_filter.c:apply_subsystem_event_filter
  - kernel/trace/trace_events_filter.c:apply_subsystem_event_filter
  - kernel/trace/trace_events_filter.c:apply_event_filter
  - kernel/trace/trace_events_filter.c:apply_event_filter
  - kernel/trace/trace_events_filter.c:process_system_preds
  - kernel/trace/trace_events_filter.c:process_system_preds
  - kernel/trace/trace_events_filter.c:process_system_preds
  - kernel/trace/trace_events_filter.c:free_event_filter
```
**Symbols:**

```
ffffffff811d6e90-ffffffff811d6ee9: __free_filter.part.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/trace/trace_events_filter.c (ffffffff811d9dd6)
Location: kernel/trace/trace_events_filter.c:1030
Inline: True
Inline callers:
  - kernel/trace/trace_events_filter.c:ftrace_profile_set_filter
  - kernel/trace/trace_events_filter.c:ftrace_profile_free_filter
  - kernel/trace/trace_events_filter.c:apply_subsystem_event_filter
  - kernel/trace/trace_events_filter.c:apply_subsystem_event_filter
  - kernel/trace/trace_events_filter.c:apply_subsystem_event_filter
  - kernel/trace/trace_events_filter.c:apply_event_filter
  - kernel/trace/trace_events_filter.c:apply_event_filter
  - kernel/trace/trace_events_filter.c:process_system_preds
  - kernel/trace/trace_events_filter.c:process_system_preds
  - kernel/trace/trace_events_filter.c:process_system_preds
  - kernel/trace/trace_events_filter.c:free_event_filter
Direct callers:
  - kernel/trace/trace_events_filter.c:ftrace_profile_set_filter
  - kernel/trace/trace_events_filter.c:ftrace_profile_free_filter
  - kernel/trace/trace_events_filter.c:apply_subsystem_event_filter
  - kernel/trace/trace_events_filter.c:apply_subsystem_event_filter
  - kernel/trace/trace_events_filter.c:apply_subsystem_event_filter
  - kernel/trace/trace_events_filter.c:apply_event_filter
  - kernel/trace/trace_events_filter.c:apply_event_filter
  - kernel/trace/trace_events_filter.c:process_system_preds
  - kernel/trace/trace_events_filter.c:process_system_preds
  - kernel/trace/trace_events_filter.c:process_system_preds
  - kernel/trace/trace_events_filter.c:free_event_filter
```
**Symbols:**

```
ffffffff811d8180-ffffffff811d81d9: __free_filter.part.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/trace/trace_events_filter.c (ffffffff812071a6)
Location: kernel/trace/trace_events_filter.c:1101
Inline: True
Inline callers:
  - kernel/trace/trace_events_filter.c:ftrace_profile_set_filter
  - kernel/trace/trace_events_filter.c:ftrace_profile_free_filter
  - kernel/trace/trace_events_filter.c:apply_subsystem_event_filter
  - kernel/trace/trace_events_filter.c:apply_subsystem_event_filter
  - kernel/trace/trace_events_filter.c:apply_subsystem_event_filter
  - kernel/trace/trace_events_filter.c:apply_event_filter
  - kernel/trace/trace_events_filter.c:apply_event_filter
  - kernel/trace/trace_events_filter.c:process_system_preds
  - kernel/trace/trace_events_filter.c:process_system_preds
  - kernel/trace/trace_events_filter.c:process_system_preds
  - kernel/trace/trace_events_filter.c:free_event_filter
Direct callers:
  - kernel/trace/trace_events_filter.c:ftrace_profile_set_filter
  - kernel/trace/trace_events_filter.c:ftrace_profile_free_filter
  - kernel/trace/trace_events_filter.c:apply_subsystem_event_filter
  - kernel/trace/trace_events_filter.c:apply_subsystem_event_filter
  - kernel/trace/trace_events_filter.c:apply_subsystem_event_filter
  - kernel/trace/trace_events_filter.c:apply_event_filter
  - kernel/trace/trace_events_filter.c:apply_event_filter
  - kernel/trace/trace_events_filter.c:process_system_preds
  - kernel/trace/trace_events_filter.c:process_system_preds
  - kernel/trace/trace_events_filter.c:process_system_preds
  - kernel/trace/trace_events_filter.c:free_event_filter
```
**Symbols:**

```
ffffffff812051a0-ffffffff812051f9: __free_filter.part.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/trace/trace_events_filter.c (ffffffff81242af5)
Location: kernel/trace/trace_events_filter.c:1124
Inline: True
Inline callers:
  - kernel/trace/trace_events_filter.c:ftrace_profile_set_filter
  - kernel/trace/trace_events_filter.c:ftrace_profile_free_filter
  - kernel/trace/trace_events_filter.c:apply_subsystem_event_filter
  - kernel/trace/trace_events_filter.c:apply_subsystem_event_filter
  - kernel/trace/trace_events_filter.c:apply_subsystem_event_filter
  - kernel/trace/trace_events_filter.c:apply_event_filter
  - kernel/trace/trace_events_filter.c:apply_event_filter
  - kernel/trace/trace_events_filter.c:process_system_preds
  - kernel/trace/trace_events_filter.c:process_system_preds
  - kernel/trace/trace_events_filter.c:process_system_preds
  - kernel/trace/trace_events_filter.c:free_event_filter
Direct callers:
  - kernel/trace/trace_events_filter.c:ftrace_profile_set_filter
  - kernel/trace/trace_events_filter.c:ftrace_profile_free_filter
  - kernel/trace/trace_events_filter.c:apply_subsystem_event_filter
  - kernel/trace/trace_events_filter.c:apply_subsystem_event_filter
  - kernel/trace/trace_events_filter.c:apply_subsystem_event_filter
  - kernel/trace/trace_events_filter.c:apply_event_filter
  - kernel/trace/trace_events_filter.c:apply_event_filter
  - kernel/trace/trace_events_filter.c:process_system_preds
  - kernel/trace/trace_events_filter.c:process_system_preds
  - kernel/trace/trace_events_filter.c:process_system_preds
  - kernel/trace/trace_events_filter.c:free_event_filter
```
**Symbols:**

```
ffffffff81240840-ffffffff812408a3: __free_filter.part.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/trace/trace_events_filter.c (ffffffff81290544)
Location: kernel/trace/trace_events_filter.c:1172
Inline: True
Inline callers:
  - kernel/trace/trace_events_filter.c:ftrace_profile_set_filter
  - kernel/trace/trace_events_filter.c:ftrace_profile_free_filter
  - kernel/trace/trace_events_filter.c:apply_subsystem_event_filter
  - kernel/trace/trace_events_filter.c:apply_subsystem_event_filter
  - kernel/trace/trace_events_filter.c:apply_subsystem_event_filter
  - kernel/trace/trace_events_filter.c:apply_event_filter
  - kernel/trace/trace_events_filter.c:apply_event_filter
  - kernel/trace/trace_events_filter.c:process_system_preds
  - kernel/trace/trace_events_filter.c:process_system_preds
  - kernel/trace/trace_events_filter.c:process_system_preds
  - kernel/trace/trace_events_filter.c:free_event_filter
Direct callers:
  - kernel/trace/trace_events_filter.c:ftrace_profile_set_filter
  - kernel/trace/trace_events_filter.c:ftrace_profile_free_filter
  - kernel/trace/trace_events_filter.c:apply_subsystem_event_filter
  - kernel/trace/trace_events_filter.c:apply_subsystem_event_filter
  - kernel/trace/trace_events_filter.c:apply_subsystem_event_filter
  - kernel/trace/trace_events_filter.c:apply_event_filter
  - kernel/trace/trace_events_filter.c:apply_event_filter
  - kernel/trace/trace_events_filter.c:process_system_preds
  - kernel/trace/trace_events_filter.c:process_system_preds
  - kernel/trace/trace_events_filter.c:process_system_preds
  - kernel/trace/trace_events_filter.c:free_event_filter
```
**Symbols:**

```
ffffffff8128d8d0-ffffffff8128d933: __free_filter.part.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/trace/trace_events_filter.c (ffffffff812ad705)
Location: kernel/trace/trace_events_filter.c:1186
Inline: True
Inline callers:
  - kernel/trace/trace_events_filter.c:ftrace_profile_set_filter
  - kernel/trace/trace_events_filter.c:ftrace_profile_free_filter
  - kernel/trace/trace_events_filter.c:apply_subsystem_event_filter
  - kernel/trace/trace_events_filter.c:apply_subsystem_event_filter
  - kernel/trace/trace_events_filter.c:apply_subsystem_event_filter
  - kernel/trace/trace_events_filter.c:apply_event_filter
  - kernel/trace/trace_events_filter.c:apply_event_filter
  - kernel/trace/trace_events_filter.c:process_system_preds
  - kernel/trace/trace_events_filter.c:process_system_preds
  - kernel/trace/trace_events_filter.c:process_system_preds
  - kernel/trace/trace_events_filter.c:free_event_filter
Direct callers:
  - kernel/trace/trace_events_filter.c:ftrace_profile_set_filter
  - kernel/trace/trace_events_filter.c:ftrace_profile_free_filter
  - kernel/trace/trace_events_filter.c:apply_subsystem_event_filter
  - kernel/trace/trace_events_filter.c:apply_subsystem_event_filter
  - kernel/trace/trace_events_filter.c:apply_subsystem_event_filter
  - kernel/trace/trace_events_filter.c:apply_event_filter
  - kernel/trace/trace_events_filter.c:apply_event_filter
  - kernel/trace/trace_events_filter.c:process_system_preds
  - kernel/trace/trace_events_filter.c:process_system_preds
  - kernel/trace/trace_events_filter.c:process_system_preds
  - kernel/trace/trace_events_filter.c:free_event_filter
```
**Symbols:**

```
ffffffff812aa9a0-ffffffff812aaa03: __free_filter.part.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/trace/trace_events_filter.c (ffffffff812c9c35)
Location: kernel/trace/trace_events_filter.c:1305
Inline: True
Inline callers:
  - kernel/trace/trace_events_filter.c:ftrace_profile_set_filter
  - kernel/trace/trace_events_filter.c:ftrace_profile_free_filter
  - kernel/trace/trace_events_filter.c:apply_subsystem_event_filter
  - kernel/trace/trace_events_filter.c:apply_subsystem_event_filter
  - kernel/trace/trace_events_filter.c:apply_subsystem_event_filter
  - kernel/trace/trace_events_filter.c:apply_event_filter
  - kernel/trace/trace_events_filter.c:apply_event_filter
  - kernel/trace/trace_events_filter.c:process_system_preds
  - kernel/trace/trace_events_filter.c:process_system_preds
  - kernel/trace/trace_events_filter.c:process_system_preds
  - kernel/trace/trace_events_filter.c:free_event_filter
Direct callers:
  - kernel/trace/trace_events_filter.c:ftrace_profile_set_filter
  - kernel/trace/trace_events_filter.c:ftrace_profile_free_filter
  - kernel/trace/trace_events_filter.c:apply_subsystem_event_filter
  - kernel/trace/trace_events_filter.c:apply_subsystem_event_filter
  - kernel/trace/trace_events_filter.c:apply_subsystem_event_filter
  - kernel/trace/trace_events_filter.c:apply_event_filter
  - kernel/trace/trace_events_filter.c:apply_event_filter
  - kernel/trace/trace_events_filter.c:process_system_preds
  - kernel/trace/trace_events_filter.c:process_system_preds
  - kernel/trace/trace_events_filter.c:process_system_preds
  - kernel/trace/trace_events_filter.c:free_event_filter
```
**Symbols:**

```
ffffffff812c68c0-ffffffff812c693b: __free_filter.part.0 (STB_LOCAL)
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
In kernel/trace/trace_events_filter.c (ffff800010241220)
Location: kernel/trace/trace_events_filter.c:1030
Inline: True
Inline callers:
  - kernel/trace/trace_events_filter.c:ftrace_profile_set_filter
  - kernel/trace/trace_events_filter.c:ftrace_profile_free_filter
  - kernel/trace/trace_events_filter.c:apply_subsystem_event_filter
  - kernel/trace/trace_events_filter.c:apply_subsystem_event_filter
  - kernel/trace/trace_events_filter.c:apply_subsystem_event_filter
  - kernel/trace/trace_events_filter.c:apply_subsystem_event_filter
  - kernel/trace/trace_events_filter.c:apply_subsystem_event_filter
  - kernel/trace/trace_events_filter.c:apply_subsystem_event_filter
  - kernel/trace/trace_events_filter.c:apply_event_filter
  - kernel/trace/trace_events_filter.c:apply_event_filter
  - kernel/trace/trace_events_filter.c:create_filter_start
  - kernel/trace/trace_events_filter.c:free_event_filter
Direct callers:
  - kernel/trace/trace_events_filter.c:ftrace_profile_set_filter
  - kernel/trace/trace_events_filter.c:ftrace_profile_free_filter
  - kernel/trace/trace_events_filter.c:apply_subsystem_event_filter
  - kernel/trace/trace_events_filter.c:apply_subsystem_event_filter
  - kernel/trace/trace_events_filter.c:apply_subsystem_event_filter
  - kernel/trace/trace_events_filter.c:apply_subsystem_event_filter
  - kernel/trace/trace_events_filter.c:apply_subsystem_event_filter
  - kernel/trace/trace_events_filter.c:apply_subsystem_event_filter
  - kernel/trace/trace_events_filter.c:apply_event_filter
  - kernel/trace/trace_events_filter.c:apply_event_filter
  - kernel/trace/trace_events_filter.c:create_filter_start
  - kernel/trace/trace_events_filter.c:free_event_filter
```
**Symbols:**

```
ffff80001023f3b0-ffff80001023f414: __free_filter.part.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/trace/trace_events_filter.c (c047ccd0)
Location: kernel/trace/trace_events_filter.c:1030
Inline: True
Inline callers:
  - kernel/trace/trace_events_filter.c:ftrace_profile_set_filter
  - kernel/trace/trace_events_filter.c:ftrace_profile_free_filter
  - kernel/trace/trace_events_filter.c:apply_subsystem_event_filter
  - kernel/trace/trace_events_filter.c:apply_subsystem_event_filter
  - kernel/trace/trace_events_filter.c:apply_subsystem_event_filter
  - kernel/trace/trace_events_filter.c:apply_subsystem_event_filter
  - kernel/trace/trace_events_filter.c:apply_subsystem_event_filter
  - kernel/trace/trace_events_filter.c:apply_subsystem_event_filter
  - kernel/trace/trace_events_filter.c:apply_event_filter
  - kernel/trace/trace_events_filter.c:apply_event_filter
  - kernel/trace/trace_events_filter.c:create_filter_start
  - kernel/trace/trace_events_filter.c:free_event_filter
Direct callers:
  - kernel/trace/trace_events_filter.c:ftrace_profile_set_filter
  - kernel/trace/trace_events_filter.c:ftrace_profile_free_filter
  - kernel/trace/trace_events_filter.c:apply_subsystem_event_filter
  - kernel/trace/trace_events_filter.c:apply_subsystem_event_filter
  - kernel/trace/trace_events_filter.c:apply_subsystem_event_filter
  - kernel/trace/trace_events_filter.c:apply_subsystem_event_filter
  - kernel/trace/trace_events_filter.c:apply_subsystem_event_filter
  - kernel/trace/trace_events_filter.c:apply_subsystem_event_filter
  - kernel/trace/trace_events_filter.c:apply_event_filter
  - kernel/trace/trace_events_filter.c:apply_event_filter
  - kernel/trace/trace_events_filter.c:create_filter_start
  - kernel/trace/trace_events_filter.c:free_event_filter
```
**Symbols:**

```
c047ae64-c047aec0: __free_filter.part.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/trace/trace_events_filter.c (c0000000002d249c)
Location: kernel/trace/trace_events_filter.c:1030
Inline: True
Inline callers:
  - kernel/trace/trace_events_filter.c:ftrace_profile_set_filter
  - kernel/trace/trace_events_filter.c:ftrace_profile_free_filter
  - kernel/trace/trace_events_filter.c:apply_subsystem_event_filter
  - kernel/trace/trace_events_filter.c:apply_subsystem_event_filter
  - kernel/trace/trace_events_filter.c:apply_subsystem_event_filter
  - kernel/trace/trace_events_filter.c:apply_subsystem_event_filter
  - kernel/trace/trace_events_filter.c:apply_subsystem_event_filter
  - kernel/trace/trace_events_filter.c:apply_subsystem_event_filter
  - kernel/trace/trace_events_filter.c:apply_event_filter
  - kernel/trace/trace_events_filter.c:apply_event_filter
  - kernel/trace/trace_events_filter.c:create_filter_start
  - kernel/trace/trace_events_filter.c:free_event_filter
Direct callers:
  - kernel/trace/trace_events_filter.c:ftrace_profile_set_filter
  - kernel/trace/trace_events_filter.c:ftrace_profile_free_filter
  - kernel/trace/trace_events_filter.c:apply_subsystem_event_filter
  - kernel/trace/trace_events_filter.c:apply_subsystem_event_filter
  - kernel/trace/trace_events_filter.c:apply_subsystem_event_filter
  - kernel/trace/trace_events_filter.c:apply_subsystem_event_filter
  - kernel/trace/trace_events_filter.c:apply_subsystem_event_filter
  - kernel/trace/trace_events_filter.c:apply_subsystem_event_filter
  - kernel/trace/trace_events_filter.c:apply_event_filter
  - kernel/trace/trace_events_filter.c:apply_event_filter
  - kernel/trace/trace_events_filter.c:create_filter_start
  - kernel/trace/trace_events_filter.c:free_event_filter
```
**Symbols:**

```
c0000000002cf790-c0000000002cf834: __free_filter.part.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/trace/trace_events_filter.c (ffffffe0001962ce)
Location: kernel/trace/trace_events_filter.c:1030
Inline: True
Inline callers:
  - kernel/trace/trace_events_filter.c:ftrace_profile_set_filter
  - kernel/trace/trace_events_filter.c:ftrace_profile_free_filter
  - kernel/trace/trace_events_filter.c:apply_subsystem_event_filter
  - kernel/trace/trace_events_filter.c:apply_subsystem_event_filter
  - kernel/trace/trace_events_filter.c:apply_subsystem_event_filter
  - kernel/trace/trace_events_filter.c:apply_subsystem_event_filter
  - kernel/trace/trace_events_filter.c:apply_subsystem_event_filter
  - kernel/trace/trace_events_filter.c:apply_subsystem_event_filter
  - kernel/trace/trace_events_filter.c:apply_event_filter
  - kernel/trace/trace_events_filter.c:apply_event_filter
  - kernel/trace/trace_events_filter.c:create_filter_start
  - kernel/trace/trace_events_filter.c:free_event_filter
Direct callers:
  - kernel/trace/trace_events_filter.c:ftrace_profile_set_filter
  - kernel/trace/trace_events_filter.c:ftrace_profile_free_filter
  - kernel/trace/trace_events_filter.c:apply_subsystem_event_filter
  - kernel/trace/trace_events_filter.c:apply_subsystem_event_filter
  - kernel/trace/trace_events_filter.c:apply_subsystem_event_filter
  - kernel/trace/trace_events_filter.c:apply_subsystem_event_filter
  - kernel/trace/trace_events_filter.c:apply_subsystem_event_filter
  - kernel/trace/trace_events_filter.c:apply_subsystem_event_filter
  - kernel/trace/trace_events_filter.c:apply_event_filter
  - kernel/trace/trace_events_filter.c:create_filter_start
  - kernel/trace/trace_events_filter.c:free_event_filter
```
**Symbols:**

```
ffffffe0001949a6-ffffffe000194a06: __free_filter.part.0 (STB_LOCAL)
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
In kernel/trace/trace_events_filter.c (ffffffff811ba1a6)
Location: kernel/trace/trace_events_filter.c:1030
Inline: True
Inline callers:
  - kernel/trace/trace_events_filter.c:ftrace_profile_set_filter
  - kernel/trace/trace_events_filter.c:ftrace_profile_free_filter
  - kernel/trace/trace_events_filter.c:apply_subsystem_event_filter
  - kernel/trace/trace_events_filter.c:apply_subsystem_event_filter
  - kernel/trace/trace_events_filter.c:apply_subsystem_event_filter
  - kernel/trace/trace_events_filter.c:apply_subsystem_event_filter
  - kernel/trace/trace_events_filter.c:apply_subsystem_event_filter
  - kernel/trace/trace_events_filter.c:apply_subsystem_event_filter
  - kernel/trace/trace_events_filter.c:apply_event_filter
  - kernel/trace/trace_events_filter.c:apply_event_filter
  - kernel/trace/trace_events_filter.c:create_filter_start
  - kernel/trace/trace_events_filter.c:free_event_filter
Direct callers:
  - kernel/trace/trace_events_filter.c:ftrace_profile_set_filter
  - kernel/trace/trace_events_filter.c:ftrace_profile_free_filter
  - kernel/trace/trace_events_filter.c:apply_subsystem_event_filter
  - kernel/trace/trace_events_filter.c:apply_subsystem_event_filter
  - kernel/trace/trace_events_filter.c:apply_subsystem_event_filter
  - kernel/trace/trace_events_filter.c:apply_subsystem_event_filter
  - kernel/trace/trace_events_filter.c:apply_subsystem_event_filter
  - kernel/trace/trace_events_filter.c:apply_subsystem_event_filter
  - kernel/trace/trace_events_filter.c:apply_event_filter
  - kernel/trace/trace_events_filter.c:apply_event_filter
  - kernel/trace/trace_events_filter.c:create_filter_start
  - kernel/trace/trace_events_filter.c:free_event_filter
```
**Symbols:**

```
ffffffff811b8410-ffffffff811b8469: __free_filter.part.0 (STB_LOCAL)
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
In kernel/trace/trace_events_filter.c (ffffffff811acf86)
Location: kernel/trace/trace_events_filter.c:1030
Inline: True
Inline callers:
  - kernel/trace/trace_events_filter.c:ftrace_profile_set_filter
  - kernel/trace/trace_events_filter.c:ftrace_profile_free_filter
  - kernel/trace/trace_events_filter.c:apply_subsystem_event_filter
  - kernel/trace/trace_events_filter.c:apply_subsystem_event_filter
  - kernel/trace/trace_events_filter.c:apply_subsystem_event_filter
  - kernel/trace/trace_events_filter.c:apply_subsystem_event_filter
  - kernel/trace/trace_events_filter.c:apply_subsystem_event_filter
  - kernel/trace/trace_events_filter.c:apply_subsystem_event_filter
  - kernel/trace/trace_events_filter.c:apply_event_filter
  - kernel/trace/trace_events_filter.c:apply_event_filter
  - kernel/trace/trace_events_filter.c:create_filter_start
  - kernel/trace/trace_events_filter.c:free_event_filter
Direct callers:
  - kernel/trace/trace_events_filter.c:ftrace_profile_set_filter
  - kernel/trace/trace_events_filter.c:ftrace_profile_free_filter
  - kernel/trace/trace_events_filter.c:apply_subsystem_event_filter
  - kernel/trace/trace_events_filter.c:apply_subsystem_event_filter
  - kernel/trace/trace_events_filter.c:apply_subsystem_event_filter
  - kernel/trace/trace_events_filter.c:apply_subsystem_event_filter
  - kernel/trace/trace_events_filter.c:apply_subsystem_event_filter
  - kernel/trace/trace_events_filter.c:apply_subsystem_event_filter
  - kernel/trace/trace_events_filter.c:apply_event_filter
  - kernel/trace/trace_events_filter.c:apply_event_filter
  - kernel/trace/trace_events_filter.c:create_filter_start
  - kernel/trace/trace_events_filter.c:free_event_filter
```
**Symbols:**

```
ffffffff811ab1f0-ffffffff811ab249: __free_filter.part.0 (STB_LOCAL)
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
In kernel/trace/trace_events_filter.c (ffffffff811b7f76)
Location: kernel/trace/trace_events_filter.c:1030
Inline: True
Inline callers:
  - kernel/trace/trace_events_filter.c:ftrace_profile_set_filter
  - kernel/trace/trace_events_filter.c:ftrace_profile_free_filter
  - kernel/trace/trace_events_filter.c:apply_subsystem_event_filter
  - kernel/trace/trace_events_filter.c:apply_subsystem_event_filter
  - kernel/trace/trace_events_filter.c:apply_subsystem_event_filter
  - kernel/trace/trace_events_filter.c:apply_subsystem_event_filter
  - kernel/trace/trace_events_filter.c:apply_subsystem_event_filter
  - kernel/trace/trace_events_filter.c:apply_subsystem_event_filter
  - kernel/trace/trace_events_filter.c:apply_event_filter
  - kernel/trace/trace_events_filter.c:apply_event_filter
  - kernel/trace/trace_events_filter.c:create_filter_start
  - kernel/trace/trace_events_filter.c:free_event_filter
Direct callers:
  - kernel/trace/trace_events_filter.c:ftrace_profile_set_filter
  - kernel/trace/trace_events_filter.c:ftrace_profile_free_filter
  - kernel/trace/trace_events_filter.c:apply_subsystem_event_filter
  - kernel/trace/trace_events_filter.c:apply_subsystem_event_filter
  - kernel/trace/trace_events_filter.c:apply_subsystem_event_filter
  - kernel/trace/trace_events_filter.c:apply_subsystem_event_filter
  - kernel/trace/trace_events_filter.c:apply_subsystem_event_filter
  - kernel/trace/trace_events_filter.c:apply_subsystem_event_filter
  - kernel/trace/trace_events_filter.c:apply_event_filter
  - kernel/trace/trace_events_filter.c:apply_event_filter
  - kernel/trace/trace_events_filter.c:create_filter_start
  - kernel/trace/trace_events_filter.c:free_event_filter
```
**Symbols:**

```
ffffffff811b61e0-ffffffff811b6239: __free_filter.part.0 (STB_LOCAL)
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
In kernel/trace/trace_events_filter.c (ffffffff811c6016)
Location: kernel/trace/trace_events_filter.c:1030
Inline: True
Inline callers:
  - kernel/trace/trace_events_filter.c:ftrace_profile_set_filter
  - kernel/trace/trace_events_filter.c:ftrace_profile_free_filter
  - kernel/trace/trace_events_filter.c:apply_subsystem_event_filter
  - kernel/trace/trace_events_filter.c:apply_subsystem_event_filter
  - kernel/trace/trace_events_filter.c:apply_subsystem_event_filter
  - kernel/trace/trace_events_filter.c:apply_subsystem_event_filter
  - kernel/trace/trace_events_filter.c:apply_subsystem_event_filter
  - kernel/trace/trace_events_filter.c:apply_subsystem_event_filter
  - kernel/trace/trace_events_filter.c:apply_event_filter
  - kernel/trace/trace_events_filter.c:apply_event_filter
  - kernel/trace/trace_events_filter.c:create_filter_start
  - kernel/trace/trace_events_filter.c:free_event_filter
Direct callers:
  - kernel/trace/trace_events_filter.c:ftrace_profile_set_filter
  - kernel/trace/trace_events_filter.c:ftrace_profile_free_filter
  - kernel/trace/trace_events_filter.c:apply_subsystem_event_filter
  - kernel/trace/trace_events_filter.c:apply_subsystem_event_filter
  - kernel/trace/trace_events_filter.c:apply_subsystem_event_filter
  - kernel/trace/trace_events_filter.c:apply_subsystem_event_filter
  - kernel/trace/trace_events_filter.c:apply_subsystem_event_filter
  - kernel/trace/trace_events_filter.c:apply_subsystem_event_filter
  - kernel/trace/trace_events_filter.c:apply_event_filter
  - kernel/trace/trace_events_filter.c:apply_event_filter
  - kernel/trace/trace_events_filter.c:create_filter_start
  - kernel/trace/trace_events_filter.c:free_event_filter
```
**Symbols:**

```
ffffffff811c4280-ffffffff811c42d9: __free_filter.part.0 (STB_LOCAL)
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
</ul>
