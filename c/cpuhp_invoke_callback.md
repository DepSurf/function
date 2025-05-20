# Function: <code>cpuhp_invoke_callback</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int cpuhp_invoke_callback(unsigned int cpu, enum cpuhp_state step, int (*cb)(unsigned int));
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cpu.c (ffffffff81083a80)
Location: kernel/cpu.c:90
Inline: False
Direct callers:
  - kernel/cpu.c:notify_cpu_starting
  - kernel/cpu.c:take_cpu_down
  - kernel/cpu.c:cpuhp_thread_fun
  - kernel/cpu.c:cpuhp_thread_fun
  - kernel/cpu.c:cpuhp_up_callbacks
  - kernel/cpu.c:cpuhp_up_callbacks
  - kernel/cpu.c:cpuhp_down_callbacks
```
**Symbols:**

```
ffffffff81083a80-ffffffff81083b77: cpuhp_invoke_callback (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int cpuhp_invoke_callback(unsigned int cpu, enum cpuhp_state state, bool bringup, struct hlist_node *node);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cpu.c (ffffffff81088810)
Location: kernel/cpu.c:122
Inline: False
Direct callers:
  - kernel/cpu.c:notify_cpu_starting
  - kernel/cpu.c:take_cpu_down
  - kernel/cpu.c:cpuhp_thread_fun
  - kernel/cpu.c:cpuhp_thread_fun
  - kernel/cpu.c:cpuhp_up_callbacks
  - kernel/cpu.c:cpuhp_up_callbacks
  - kernel/cpu.c:cpuhp_down_callbacks
```
**Symbols:**

```
ffffffff81088810-ffffffff81088bbd: cpuhp_invoke_callback (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int cpuhp_invoke_callback(unsigned int cpu, enum cpuhp_state state, bool bringup, struct hlist_node *node);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cpu.c (ffffffff81085680)
Location: kernel/cpu.c:131
Inline: False
Direct callers:
  - kernel/cpu.c:notify_cpu_starting
  - kernel/cpu.c:take_cpu_down
  - kernel/cpu.c:cpuhp_thread_fun
  - kernel/cpu.c:cpuhp_thread_fun
  - kernel/cpu.c:cpuhp_up_callbacks
  - kernel/cpu.c:cpuhp_up_callbacks
  - kernel/cpu.c:cpuhp_down_callbacks
```
**Symbols:**

```
ffffffff81085680-ffffffff81085a23: cpuhp_invoke_callback (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int cpuhp_invoke_callback(unsigned int cpu, enum cpuhp_state state, bool bringup, struct hlist_node *node, struct hlist_node **lastp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cpu.c (ffffffff8108c300)
Location: kernel/cpu.c:157
Inline: False
Direct callers:
  - kernel/cpu.c:cpuhp_issue_call
  - kernel/cpu.c:_cpu_up
  - kernel/cpu.c:_cpu_up
  - kernel/cpu.c:notify_cpu_starting
  - kernel/cpu.c:_cpu_down
  - kernel/cpu.c:_cpu_down
  - kernel/cpu.c:take_cpu_down
  - kernel/cpu.c:cpuhp_thread_fun
  - kernel/cpu.c:cpuhp_thread_fun
```
**Symbols:**

```
ffffffff8108c300-ffffffff8108c863: cpuhp_invoke_callback (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int cpuhp_invoke_callback(unsigned int cpu, enum cpuhp_state state, bool bringup, struct hlist_node *node, struct hlist_node **lastp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cpu.c (ffffffff8108fcd0)
Location: kernel/cpu.c:145
Inline: False
Direct callers:
  - kernel/cpu.c:_cpu_up
  - kernel/cpu.c:_cpu_up
  - kernel/cpu.c:notify_cpu_starting
  - kernel/cpu.c:_cpu_down
  - kernel/cpu.c:_cpu_down
  - kernel/cpu.c:take_cpu_down
  - kernel/cpu.c:cpuhp_thread_fun
  - kernel/cpu.c:cpuhp_thread_fun
```
**Symbols:**

```
ffffffff8108fcd0-ffffffff81090206: cpuhp_invoke_callback (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int cpuhp_invoke_callback(unsigned int cpu, enum cpuhp_state state, bool bringup, struct hlist_node *node, struct hlist_node **lastp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cpu.c (ffffffff81097ff0)
Location: kernel/cpu.c:143
Inline: False
Direct callers:
  - kernel/cpu.c:_cpu_up
  - kernel/cpu.c:_cpu_up
  - kernel/cpu.c:notify_cpu_starting
  - kernel/cpu.c:_cpu_down
  - kernel/cpu.c:_cpu_down
  - kernel/cpu.c:take_cpu_down
  - kernel/cpu.c:cpuhp_thread_fun
  - kernel/cpu.c:cpuhp_thread_fun
```
**Symbols:**

```
ffffffff81097ff0-ffffffff81098526: cpuhp_invoke_callback (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int cpuhp_invoke_callback(unsigned int cpu, enum cpuhp_state state, bool bringup, struct hlist_node *node, struct hlist_node **lastp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cpu.c (ffffffff8109c580)
Location: kernel/cpu.c:144
Inline: False
Direct callers:
  - kernel/cpu.c:_cpu_up
  - kernel/cpu.c:_cpu_up
  - kernel/cpu.c:notify_cpu_starting
  - kernel/cpu.c:_cpu_down
  - kernel/cpu.c:_cpu_down
  - kernel/cpu.c:take_cpu_down
  - kernel/cpu.c:cpuhp_thread_fun
  - kernel/cpu.c:cpuhp_thread_fun
```
**Symbols:**

```
ffffffff8109c580-ffffffff8109caf1: cpuhp_invoke_callback (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int cpuhp_invoke_callback(unsigned int cpu, enum cpuhp_state state, bool bringup, struct hlist_node *node, struct hlist_node **lastp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cpu.c (ffffffff810a2ad0)
Location: kernel/cpu.c:147
Inline: False
Direct callers:
  - kernel/cpu.c:_cpu_up
  - kernel/cpu.c:_cpu_up
  - kernel/cpu.c:notify_cpu_starting
  - kernel/cpu.c:_cpu_down
  - kernel/cpu.c:_cpu_down
  - kernel/cpu.c:take_cpu_down
  - kernel/cpu.c:cpuhp_thread_fun
  - kernel/cpu.c:cpuhp_thread_fun
```
**Symbols:**

```
ffffffff810a2ad0-ffffffff810a3041: cpuhp_invoke_callback (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int cpuhp_invoke_callback(unsigned int cpu, enum cpuhp_state state, bool bringup, struct hlist_node *node, struct hlist_node **lastp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cpu.c (ffffffff810a9a80)
Location: kernel/cpu.c:148
Inline: False
Direct callers:
  - kernel/cpu.c:cpuhp_issue_call
  - kernel/cpu.c:_cpu_up
  - kernel/cpu.c:_cpu_up
  - kernel/cpu.c:notify_cpu_starting
  - kernel/cpu.c:_cpu_down
  - kernel/cpu.c:_cpu_down
  - kernel/cpu.c:take_cpu_down
  - kernel/cpu.c:cpuhp_invoke_ap_callback
  - kernel/cpu.c:cpuhp_thread_fun
  - kernel/cpu.c:cpuhp_thread_fun
```
**Symbols:**

```
ffffffff810a9a80-ffffffff810a9ff1: cpuhp_invoke_callback (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int cpuhp_invoke_callback(unsigned int cpu, enum cpuhp_state state, bool bringup, struct hlist_node *node, struct hlist_node **lastp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cpu.c (ffffffff810a5480)
Location: kernel/cpu.c:148
Inline: False
Direct callers:
  - kernel/cpu.c:cpuhp_issue_call
  - kernel/cpu.c:_cpu_up
  - kernel/cpu.c:_cpu_up
  - kernel/cpu.c:notify_cpu_starting
  - kernel/cpu.c:_cpu_down
  - kernel/cpu.c:_cpu_down
  - kernel/cpu.c:take_cpu_down
  - kernel/cpu.c:cpuhp_invoke_ap_callback
  - kernel/cpu.c:cpuhp_thread_fun
  - kernel/cpu.c:cpuhp_thread_fun
```
**Symbols:**

```
ffffffff810a5480-ffffffff810a588f: cpuhp_invoke_callback (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int cpuhp_invoke_callback(unsigned int cpu, enum cpuhp_state state, bool bringup, struct hlist_node *node, struct hlist_node **lastp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cpu.c (ffffffff810a6130)
Location: kernel/cpu.c:155
Inline: False
Direct callers:
  - kernel/cpu.c:cpuhp_issue_call
  - kernel/cpu.c:cpuhp_issue_call
  - kernel/cpu.c:_cpu_up
  - kernel/cpu.c:_cpu_up
  - kernel/cpu.c:notify_cpu_starting
  - kernel/cpu.c:_cpu_down
  - kernel/cpu.c:_cpu_down
  - kernel/cpu.c:take_cpu_down
  - kernel/cpu.c:cpuhp_thread_fun
  - kernel/cpu.c:cpuhp_thread_fun
```
**Symbols:**

```
ffffffff810a6130-ffffffff810a654a: cpuhp_invoke_callback (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int cpuhp_invoke_callback(unsigned int cpu, enum cpuhp_state state, bool bringup, struct hlist_node *node, struct hlist_node **lastp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/cpu.c (0)
Location: kernel/cpu.c:166
Inline: False
Direct callers:
  - kernel/cpu.c:cpuhp_issue_call
  - kernel/cpu.c:cpuhp_issue_call
  - kernel/cpu.c:_cpu_up
  - kernel/cpu.c:_cpu_up
  - kernel/cpu.c:notify_cpu_starting
  - kernel/cpu.c:_cpu_down
  - kernel/cpu.c:_cpu_down
  - kernel/cpu.c:take_cpu_down
  - kernel/cpu.c:cpuhp_thread_fun
  - kernel/cpu.c:cpuhp_thread_fun
```
**Symbols:**

```
ffffffff810b7c70-ffffffff810b8080: cpuhp_invoke_callback (STB_LOCAL)
ffffffff81ca3e2f-ffffffff81ca3e4a: cpuhp_invoke_callback.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int cpuhp_invoke_callback(unsigned int cpu, enum cpuhp_state state, bool bringup, struct hlist_node *node, struct hlist_node **lastp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/cpu.c (0)
Location: kernel/cpu.c:167
Inline: False
Direct callers:
  - kernel/cpu.c:cpuhp_issue_call
  - kernel/cpu.c:_cpu_up
  - kernel/cpu.c:_cpu_up
  - kernel/cpu.c:notify_cpu_starting
  - kernel/cpu.c:_cpu_down
  - kernel/cpu.c:_cpu_down
  - kernel/cpu.c:take_cpu_down
  - kernel/cpu.c:cpuhp_thread_fun
  - kernel/cpu.c:cpuhp_thread_fun
```
**Symbols:**

```
ffffffff810ce3a0-ffffffff810ce8a4: cpuhp_invoke_callback (STB_LOCAL)
ffffffff81e53672-ffffffff81e536b9: cpuhp_invoke_callback.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
int cpuhp_invoke_callback(unsigned int cpu, enum cpuhp_state state, bool bringup, struct hlist_node *node, struct hlist_node **lastp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/cpu.c (0)
Location: kernel/cpu.c:167
Inline: False
Direct callers:
  - kernel/cpu.c:cpuhp_issue_call
  - kernel/cpu.c:cpuhp_thread_fun
  - kernel/cpu.c:cpuhp_thread_fun
  - kernel/cpu.c:__cpuhp_invoke_callback_range
```
**Symbols:**

```
ffffffff810ec560-ffffffff810eca82: cpuhp_invoke_callback (STB_LOCAL)
ffffffff82055b7d-ffffffff82055bc4: cpuhp_invoke_callback.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
int cpuhp_invoke_callback(unsigned int cpu, enum cpuhp_state state, bool bringup, struct hlist_node *node, struct hlist_node **lastp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/cpu.c (0)
Location: kernel/cpu.c:170
Inline: False
Direct callers:
  - kernel/cpu.c:cpuhp_thread_fun
  - kernel/cpu.c:cpuhp_thread_fun
  - kernel/cpu.c:__cpuhp_invoke_callback_range
```
**Symbols:**

```
ffffffff810f8090-ffffffff810f85b2: cpuhp_invoke_callback (STB_LOCAL)
ffffffff820d4163-ffffffff820d41aa: cpuhp_invoke_callback.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
int cpuhp_invoke_callback(unsigned int cpu, enum cpuhp_state state, bool bringup, struct hlist_node *node, struct hlist_node **lastp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/cpu.c (0)
Location: kernel/cpu.c:170
Inline: False
Direct callers:
  - kernel/cpu.c:cpuhp_thread_fun
  - kernel/cpu.c:cpuhp_thread_fun
  - kernel/cpu.c:__cpuhp_invoke_callback_range
```
**Symbols:**

```
ffffffff811014a0-ffffffff811019c2: cpuhp_invoke_callback (STB_LOCAL)
ffffffff821af037-ffffffff821af07e: cpuhp_invoke_callback.cold (STB_LOCAL)
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
int cpuhp_invoke_callback(unsigned int cpu, enum cpuhp_state state, bool bringup, struct hlist_node *node, struct hlist_node **lastp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cpu.c (ffff8000100f8028)
Location: kernel/cpu.c:147
Inline: False
Direct callers:
  - kernel/cpu.c:_cpu_up
  - kernel/cpu.c:_cpu_up
  - kernel/cpu.c:notify_cpu_starting
  - kernel/cpu.c:_cpu_down
  - kernel/cpu.c:_cpu_down
  - kernel/cpu.c:take_cpu_down
  - kernel/cpu.c:cpuhp_thread_fun
  - kernel/cpu.c:cpuhp_thread_fun
```
**Symbols:**

```
ffff8000100f8028-ffff8000100f8650: cpuhp_invoke_callback (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int cpuhp_invoke_callback(unsigned int cpu, enum cpuhp_state state, bool bringup, struct hlist_node *node, struct hlist_node **lastp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cpu.c (c0356098)
Location: kernel/cpu.c:147
Inline: False
Direct callers:
  - kernel/cpu.c:_cpu_up
  - kernel/cpu.c:_cpu_up
  - kernel/cpu.c:notify_cpu_starting
  - kernel/cpu.c:_cpu_down
  - kernel/cpu.c:_cpu_down
  - kernel/cpu.c:take_cpu_down
  - kernel/cpu.c:cpuhp_thread_fun
  - kernel/cpu.c:cpuhp_thread_fun
```
**Symbols:**

```
c0356098-c03568fc: cpuhp_invoke_callback (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int cpuhp_invoke_callback(unsigned int cpu, enum cpuhp_state state, bool bringup, struct hlist_node *node, struct hlist_node **lastp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cpu.c (c00000000013e790)
Location: kernel/cpu.c:147
Inline: False
Direct callers:
  - kernel/cpu.c:cpuhp_issue_call
  - kernel/cpu.c:_cpu_up
  - kernel/cpu.c:_cpu_up
  - kernel/cpu.c:notify_cpu_starting
  - kernel/cpu.c:_cpu_down
  - kernel/cpu.c:_cpu_down
  - kernel/cpu.c:take_cpu_down
  - kernel/cpu.c:cpuhp_thread_fun
  - kernel/cpu.c:cpuhp_thread_fun
```
**Symbols:**

```
c00000000013e790-c00000000013ef84: cpuhp_invoke_callback (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int cpuhp_invoke_callback(unsigned int cpu, enum cpuhp_state state, bool bringup, struct hlist_node *node, struct hlist_node **lastp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cpu.c (ffffffe0000c3144)
Location: kernel/cpu.c:147
Inline: False
Direct callers:
  - kernel/cpu.c:cpuhp_issue_call
  - kernel/cpu.c:cpu_up
  - kernel/cpu.c:cpu_up
  - kernel/cpu.c:notify_cpu_starting
  - kernel/cpu.c:cpuhp_thread_fun
  - kernel/cpu.c:cpuhp_thread_fun
```
**Symbols:**

```
ffffffe0000c3144-ffffffe0000c35b8: cpuhp_invoke_callback (STB_LOCAL)
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
int cpuhp_invoke_callback(unsigned int cpu, enum cpuhp_state state, bool bringup, struct hlist_node *node, struct hlist_node **lastp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cpu.c (ffffffff8109c3f0)
Location: kernel/cpu.c:147
Inline: False
Direct callers:
  - kernel/cpu.c:_cpu_up
  - kernel/cpu.c:_cpu_up
  - kernel/cpu.c:notify_cpu_starting
  - kernel/cpu.c:_cpu_down
  - kernel/cpu.c:_cpu_down
  - kernel/cpu.c:take_cpu_down
  - kernel/cpu.c:cpuhp_thread_fun
  - kernel/cpu.c:cpuhp_thread_fun
```
**Symbols:**

```
ffffffff8109c3f0-ffffffff8109c961: cpuhp_invoke_callback (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int cpuhp_invoke_callback(unsigned int cpu, enum cpuhp_state state, bool bringup, struct hlist_node *node, struct hlist_node **lastp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cpu.c (ffffffff8108ae20)
Location: kernel/cpu.c:147
Inline: False
Direct callers:
  - kernel/cpu.c:_cpu_up
  - kernel/cpu.c:_cpu_up
  - kernel/cpu.c:notify_cpu_starting
  - kernel/cpu.c:_cpu_down
  - kernel/cpu.c:_cpu_down
  - kernel/cpu.c:take_cpu_down
  - kernel/cpu.c:cpuhp_thread_fun
  - kernel/cpu.c:cpuhp_thread_fun
```
**Symbols:**

```
ffffffff8108ae20-ffffffff8108b391: cpuhp_invoke_callback (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int cpuhp_invoke_callback(unsigned int cpu, enum cpuhp_state state, bool bringup, struct hlist_node *node, struct hlist_node **lastp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cpu.c (ffffffff8109c3a0)
Location: kernel/cpu.c:147
Inline: False
Direct callers:
  - kernel/cpu.c:_cpu_up
  - kernel/cpu.c:_cpu_up
  - kernel/cpu.c:notify_cpu_starting
  - kernel/cpu.c:_cpu_down
  - kernel/cpu.c:_cpu_down
  - kernel/cpu.c:take_cpu_down
  - kernel/cpu.c:cpuhp_thread_fun
  - kernel/cpu.c:cpuhp_thread_fun
```
**Symbols:**

```
ffffffff8109c3a0-ffffffff8109c911: cpuhp_invoke_callback (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int cpuhp_invoke_callback(unsigned int cpu, enum cpuhp_state state, bool bringup, struct hlist_node *node, struct hlist_node **lastp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cpu.c (ffffffff810a4080)
Location: kernel/cpu.c:147
Inline: False
Direct callers:
  - kernel/cpu.c:_cpu_up
  - kernel/cpu.c:_cpu_up
  - kernel/cpu.c:notify_cpu_starting
  - kernel/cpu.c:_cpu_down
  - kernel/cpu.c:_cpu_down
  - kernel/cpu.c:take_cpu_down
  - kernel/cpu.c:cpuhp_thread_fun
  - kernel/cpu.c:cpuhp_thread_fun
```
**Symbols:**

```
ffffffff810a4080-ffffffff810a46a6: cpuhp_invoke_callback (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
<details>
<summary>Changed between <code>4.8</code> and <code>4.10</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>enum cpuhp_state state</code>
</li>
<li>
<b>Param added. </b>
<code>bool bringup</code>
</li>
<li>
<b>Param added. </b>
<code>struct hlist_node *node</code>
</li>
<li>
<b>Param removed. </b>
<code>enum cpuhp_state step</code>
</li>
<li>
<b>Param removed. </b>
<code>int (*cb)(unsigned int)</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>4.10</code> and <code>4.13</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>4.13</code> and <code>4.15</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>struct hlist_node **lastp</code>
</li>
</ul>
</details>
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
