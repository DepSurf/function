# Function: <code>rcu_is_watching</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline ⚠️</summary>

```c
bool rcu_is_watching();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/rcu/tree.c (ffffffff810e4260)
Location: kernel/rcu/tree.c:996
Inline: True
Direct callers:
  - kernel/trace/ftrace.c:ftrace_ops_control_func
```
**Symbols:**

```
ffffffff810e4260-ffffffff810e427a: rcu_is_watching (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
bool rcu_is_watching();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/rcu/tree.c (ffffffff810ea590)
Location: kernel/rcu/tree.c:1051
Inline: True
Direct callers:
  - kernel/trace/ftrace.c:ftrace_ops_assist_func
  - kernel/trace/ftrace.c:ftrace_ops_list_func
```
**Symbols:**

```
ffffffff810ea590-ffffffff810ea5aa: rcu_is_watching (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
bool rcu_is_watching();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/rcu/tree.c (ffffffff810f1470)
Location: kernel/rcu/tree.c:1052
Inline: True
Direct callers:
  - kernel/trace/ftrace.c:ftrace_ops_assist_func
  - kernel/trace/ftrace.c:ftrace_ops_list_func
```
**Symbols:**

```
ffffffff810f1470-ffffffff810f148a: rcu_is_watching (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
bool rcu_is_watching();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/rcu/tree.c (ffffffff810f2470)
Location: kernel/rcu/tree.c:1120
Inline: True
Direct callers:
  - kernel/trace/ftrace.c:ftrace_ops_assist_func
  - kernel/trace/ftrace.c:ftrace_ops_list_func
  - kernel/trace/trace.c:__trace_stack
```
**Symbols:**

```
ffffffff810f2470-ffffffff810f248d: rcu_is_watching (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
bool rcu_is_watching();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/rcu/tree.c (ffffffff810fc1f0)
Location: kernel/rcu/tree.c:1155
Inline: True
Direct callers:
  - kernel/trace/ftrace.c:ftrace_ops_assist_func
  - kernel/trace/ftrace.c:ftrace_ops_list_func
  - kernel/trace/trace.c:__trace_stack
  - kernel/trace/trace_stack.c:stack_trace_call
```
**Symbols:**

```
ffffffff810fc1f0-ffffffff810fc20d: rcu_is_watching (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
bool rcu_is_watching();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/rcu/tree.c (ffffffff81104800)
Location: kernel/rcu/tree.c:1030
Inline: True
Direct callers:
  - kernel/extable.c:kernel_text_address
  - kernel/trace/ftrace.c:ftrace_ops_assist_func
  - kernel/trace/ftrace.c:ftrace_ops_list_func
  - kernel/trace/trace.c:__trace_stack
  - kernel/trace/trace_stack.c:stack_trace_call
```
**Symbols:**

```
ffffffff81104800-ffffffff8110481d: rcu_is_watching (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
bool rcu_is_watching();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/rcu/tree.c (ffffffff811101e0)
Location: kernel/rcu/tree.c:927
Inline: True
Direct callers:
  - kernel/extable.c:kernel_text_address
  - kernel/trace/ftrace.c:ftrace_ops_assist_func
  - kernel/trace/ftrace.c:ftrace_ops_list_func
  - kernel/trace/trace.c:__trace_stack
  - kernel/trace/trace_stack.c:stack_trace_call
```
**Symbols:**

```
ffffffff811101e0-ffffffff81110200: rcu_is_watching (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
bool rcu_is_watching();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/rcu/tree.c (ffffffff81119950)
Location: kernel/rcu/tree.c:889
Inline: True
Direct callers:
  - kernel/extable.c:kernel_text_address
  - kernel/extable.c:kernel_text_address
  - kernel/trace/ftrace.c:ftrace_ops_assist_func
  - kernel/trace/ftrace.c:ftrace_ops_list_func
  - kernel/trace/trace.c:__trace_stack
  - kernel/trace/trace_stack.c:stack_trace_call
```
**Symbols:**

```
ffffffff81119950-ffffffff8111996b: rcu_is_watching (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
bool rcu_is_watching();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/rcu/tree.c (ffffffff811282cc)
Location: kernel/rcu/tree.c:897
Inline: True
Inline callers:
  - kernel/rcu/tree.c:__call_rcu
  - kernel/rcu/tree.c:__call_rcu
Direct callers:
  - kernel/extable.c:kernel_text_address
  - kernel/extable.c:kernel_text_address
  - kernel/trace/ftrace.c:ftrace_ops_assist_func
  - kernel/trace/ftrace.c:ftrace_ops_list_func
  - kernel/trace/trace.c:__trace_stack
  - kernel/trace/trace_stack.c:stack_trace_call
```
**Symbols:**

```
ffffffff81125ce0-ffffffff81125cfb: rcu_is_watching (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
bool rcu_is_watching();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/rcu/tree.c (ffffffff81136ba0)
Location: kernel/rcu/tree.c:1092
Inline: True
Inline callers:
  - kernel/rcu/tree.c:__call_rcu
  - kernel/rcu/tree.c:__call_rcu
Direct callers:
  - kernel/trace/ftrace.c:ftrace_ops_assist_func
  - kernel/trace/ftrace.c:ftrace_ops_list_func
  - kernel/trace/trace.c:__trace_stack
  - kernel/trace/trace_stack.c:stack_trace_call
```
**Symbols:**

```
ffffffff811335b0-ffffffff811335d5: rcu_is_watching (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
bool rcu_is_watching();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/rcu/tree.c (ffffffff81132200)
Location: kernel/rcu/tree.c:1159
Inline: True
Inline callers:
  - kernel/rcu/tree.c:__call_rcu
  - kernel/rcu/tree.c:__call_rcu
Direct callers:
  - kernel/trace/ftrace.c:ftrace_ops_assist_func
  - kernel/trace/ftrace.c:ftrace_ops_list_func
  - kernel/trace/trace.c:__trace_stack
  - kernel/trace/trace_stack.c:stack_trace_call
  - kernel/trace/trace_event_perf.c:perf_ftrace_function_call
```
**Symbols:**

```
ffffffff8112ec50-ffffffff8112ec6b: rcu_is_watching (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
bool rcu_is_watching();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/rcu/tree.c (ffffffff811329e8)
Location: kernel/rcu/tree.c:1163
Inline: True
Inline callers:
  - kernel/rcu/tree.c:__call_rcu
  - kernel/rcu/tree.c:__call_rcu
Direct callers:
  - kernel/trace/ftrace.c:ftrace_ops_assist_func
  - kernel/trace/ftrace.c:ftrace_ops_list_func
  - kernel/trace/trace.c:__trace_stack
  - kernel/trace/trace_stack.c:stack_trace_call
  - kernel/trace/trace_event_perf.c:perf_ftrace_function_call
```
**Symbols:**

```
ffffffff8112f280-ffffffff8112f29b: rcu_is_watching (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
bool rcu_is_watching();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/rcu/tree.c (ffffffff81154c1c)
Location: kernel/rcu/tree.c:1116
Inline: True
Inline callers:
  - kernel/rcu/tree.c:__call_rcu
  - kernel/rcu/tree.c:__call_rcu
Direct callers:
  - kernel/trace/ftrace.c:ftrace_ops_assist_func
  - kernel/trace/ftrace.c:ftrace_ops_list_func
  - kernel/trace/trace.c:__trace_stack
  - kernel/trace/trace_stack.c:stack_trace_call
  - kernel/trace/trace_event_perf.c:perf_ftrace_function_call
```
**Symbols:**

```
ffffffff81150810-ffffffff81150825: rcu_is_watching (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
bool rcu_is_watching();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/rcu/tree.c (ffffffff8117df5c)
Location: kernel/rcu/tree.c:1133
Inline: True
Inline callers:
  - kernel/rcu/tree.c:call_rcu
  - kernel/rcu/tree.c:call_rcu
Direct callers:
  - kernel/trace/ftrace.c:ftrace_ops_assist_func
  - kernel/trace/ftrace.c:arch_ftrace_ops_list_func
  - kernel/trace/trace.c:__trace_stack
  - kernel/trace/trace_stack.c:stack_trace_call
  - kernel/trace/trace_event_perf.c:perf_ftrace_function_call
  - kernel/trace/rethook.c:rethook_try_get
```
**Symbols:**

```
ffffffff811781c0-ffffffff811781f8: rcu_is_watching (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
bool rcu_is_watching();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/rcu/tree.c (ffffffff811afa10)
Location: kernel/rcu/tree.c:708
Inline: True
Direct callers:
  - kernel/trace/ftrace.c:ftrace_ops_assist_func
  - kernel/trace/ftrace.c:arch_ftrace_ops_list_func
  - kernel/trace/trace.c:__trace_stack
  - kernel/trace/trace_stack.c:stack_trace_call
  - kernel/trace/trace_event_perf.c:perf_ftrace_function_call
  - kernel/trace/rethook.c:rethook_try_get
```
**Symbols:**

```
ffffffff811afa10-ffffffff811afa4b: rcu_is_watching (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
bool rcu_is_watching();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/rcu/tree.c (ffffffff811c1a80)
Location: kernel/rcu/tree.c:690
Inline: True
Direct callers:
  - arch/x86/kernel/ftrace.c:prepare_ftrace_return
  - arch/x86/kernel/kprobes/ftrace.c:kprobe_ftrace_handler
  - kernel/livepatch/patch.c:klp_ftrace_handler
  - kernel/trace/ftrace.c:ftrace_ops_assist_func
  - kernel/trace/ftrace.c:ftrace_ops_assist_func
  - kernel/trace/ftrace.c:arch_ftrace_ops_list_func
  - kernel/trace/ftrace.c:arch_ftrace_ops_list_func
  - kernel/trace/trace.c:__trace_stack
  - kernel/trace/trace_functions.c:function_no_repeats_trace_call
  - kernel/trace/trace_functions.c:function_trace_call
  - kernel/trace/trace_stack.c:stack_trace_call
  - kernel/trace/trace_event_perf.c:perf_ftrace_function_call
  - kernel/trace/trace_event_perf.c:perf_ftrace_function_call
  - kernel/trace/rethook.c:rethook_try_get
```
**Symbols:**

```
ffffffff811c1a80-ffffffff811c1abb: rcu_is_watching (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
bool rcu_is_watching();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/rcu/tree.c (ffffffff811e0a76)
Location: kernel/rcu/tree.c:695
Inline: True
Inline callers:
  - kernel/rcu/tree.c:__call_rcu_common
  - kernel/rcu/tree.c:__call_rcu_common
Direct callers:
  - arch/x86/kernel/ftrace.c:prepare_ftrace_return
  - arch/x86/kernel/kprobes/ftrace.c:kprobe_ftrace_handler
  - kernel/livepatch/patch.c:klp_ftrace_handler
  - kernel/trace/ftrace.c:ftrace_ops_assist_func
  - kernel/trace/ftrace.c:ftrace_ops_assist_func
  - kernel/trace/ftrace.c:arch_ftrace_ops_list_func
  - kernel/trace/ftrace.c:arch_ftrace_ops_list_func
  - kernel/trace/trace.c:__trace_stack
  - kernel/trace/trace_functions.c:function_no_repeats_trace_call
  - kernel/trace/trace_functions.c:function_trace_call
  - kernel/trace/trace_stack.c:stack_trace_call
  - kernel/trace/trace_event_perf.c:perf_ftrace_function_call
  - kernel/trace/trace_event_perf.c:perf_ftrace_function_call
  - kernel/trace/rethook.c:rethook_try_get
```
**Symbols:**

```
ffffffff811d1fe0-ffffffff811d201b: rcu_is_watching (STB_GLOBAL)
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
bool rcu_is_watching();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/rcu/tree.c (ffff80001018f08c)
Location: kernel/rcu/tree.c:897
Inline: True
Inline callers:
  - kernel/rcu/tree.c:__call_rcu
  - kernel/rcu/tree.c:__call_rcu
Direct callers:
  - kernel/extable.c:kernel_text_address
  - kernel/extable.c:kernel_text_address
  - kernel/trace/ftrace.c:ftrace_ops_assist_func
  - kernel/trace/ftrace.c:ftrace_ops_no_ops
  - kernel/trace/trace.c:__trace_stack
  - kernel/trace/trace_stack.c:stack_trace_call
```
**Symbols:**

```
ffff80001018c640-ffff80001018c65c: rcu_is_watching (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
bool rcu_is_watching();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/rcu/tree.c (c03dc4c0)
Location: kernel/rcu/tree.c:897
Inline: True
Inline callers:
  - kernel/rcu/tree.c:__call_rcu
  - kernel/rcu/tree.c:__call_rcu
Direct callers:
  - kernel/extable.c:kernel_text_address
  - kernel/extable.c:kernel_text_address
  - kernel/trace/ftrace.c:ftrace_ops_assist_func
  - kernel/trace/ftrace.c:ftrace_ops_list_func
  - kernel/trace/trace.c:__trace_stack
  - kernel/trace/trace_stack.c:stack_trace_call
```
**Symbols:**

```
c03d9e40-c03d9e68: rcu_is_watching (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
bool rcu_is_watching();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/rcu/tree.c (c0000000001e99c0)
Location: kernel/rcu/tree.c:897
Inline: True
Inline callers:
  - kernel/rcu/tree.c:__call_rcu
  - kernel/rcu/tree.c:__call_rcu
Direct callers:
  - kernel/extable.c:kernel_text_address
  - kernel/extable.c:kernel_text_address
  - kernel/trace/ftrace.c:ftrace_ops_assist_func
  - kernel/trace/ftrace.c:ftrace_ops_list_func
  - kernel/trace/trace.c:__trace_stack
  - kernel/trace/trace_stack.c:stack_trace_call
```
**Symbols:**

```
c0000000001e6490-c0000000001e64b4: rcu_is_watching (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
bool rcu_is_watching();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/rcu/tree.c (ffffffe0001232a0)
Location: kernel/rcu/tree.c:897
Inline: True
Inline callers:
  - kernel/rcu/tree.c:__call_rcu
  - kernel/rcu/tree.c:__call_rcu
Direct callers:
  - kernel/extable.c:kernel_text_address
  - kernel/extable.c:kernel_text_address
  - kernel/trace/ftrace.c:ftrace_ops_assist_func
  - kernel/trace/ftrace.c:ftrace_ops_list_func
  - kernel/trace/trace.c:__trace_stack
  - kernel/trace/trace_stack.c:stack_trace_call
```
**Symbols:**

```
ffffffe0001203e0-ffffffe000120416: rcu_is_watching (STB_GLOBAL)
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
bool rcu_is_watching();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/rcu/tree.c (ffffffff811208ac)
Location: kernel/rcu/tree.c:897
Inline: True
Inline callers:
  - kernel/rcu/tree.c:__call_rcu
  - kernel/rcu/tree.c:__call_rcu
Direct callers:
  - kernel/extable.c:kernel_text_address
  - kernel/extable.c:kernel_text_address
  - kernel/trace/ftrace.c:ftrace_ops_assist_func
  - kernel/trace/ftrace.c:ftrace_ops_list_func
  - kernel/trace/trace.c:__trace_stack
  - kernel/trace/trace_stack.c:stack_trace_call
```
**Symbols:**

```
ffffffff8111e2c0-ffffffff8111e2db: rcu_is_watching (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
bool rcu_is_watching();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/rcu/tree.c (ffffffff81113d47)
Location: kernel/rcu/tree.c:897
Inline: True
Inline callers:
  - kernel/rcu/tree.c:__call_rcu
  - kernel/rcu/tree.c:__call_rcu
Direct callers:
  - kernel/extable.c:kernel_text_address
  - kernel/extable.c:kernel_text_address
  - kernel/trace/ftrace.c:ftrace_ops_assist_func
  - kernel/trace/ftrace.c:ftrace_ops_list_func
  - kernel/trace/trace.c:__trace_stack
  - kernel/trace/trace_stack.c:stack_trace_call
```
**Symbols:**

```
ffffffff8110f320-ffffffff8110f33b: rcu_is_watching (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
bool rcu_is_watching();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/rcu/tree.c (ffffffff8111e79c)
Location: kernel/rcu/tree.c:897
Inline: True
Inline callers:
  - kernel/rcu/tree.c:__call_rcu
  - kernel/rcu/tree.c:__call_rcu
Direct callers:
  - kernel/extable.c:kernel_text_address
  - kernel/extable.c:kernel_text_address
  - kernel/trace/ftrace.c:ftrace_ops_assist_func
  - kernel/trace/ftrace.c:ftrace_ops_list_func
  - kernel/trace/trace.c:__trace_stack
  - kernel/trace/trace_stack.c:stack_trace_call
```
**Symbols:**

```
ffffffff8111c1b0-ffffffff8111c1cb: rcu_is_watching (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
bool rcu_is_watching();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/rcu/tree.c (ffffffff8112aab1)
Location: kernel/rcu/tree.c:897
Inline: True
Inline callers:
  - kernel/rcu/tree.c:__call_rcu
  - kernel/rcu/tree.c:__call_rcu
Direct callers:
  - kernel/extable.c:kernel_text_address
  - kernel/extable.c:kernel_text_address
  - kernel/trace/ftrace.c:ftrace_ops_assist_func
  - kernel/trace/ftrace.c:ftrace_ops_list_func
  - kernel/trace/trace.c:__trace_stack
  - kernel/trace/trace_stack.c:stack_trace_call
```
**Symbols:**

```
ffffffff81127ab0-ffffffff81127ae6: rcu_is_watching (STB_GLOBAL)
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
