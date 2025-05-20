# Function: <code>rethook_find_ret_addr</code>

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
In <code>5.15</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
long unsigned int rethook_find_ret_addr(struct task_struct *tsk, long unsigned int frame, struct llist_node **cur);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/rethook.c (ffffffff81268ea0)
Location: kernel/trace/rethook.c:234
Inline: False
Direct callers:
  - arch/x86/kernel/unwind_frame.c:update_stack_state
```
**Symbols:**

```
ffffffff81268ea0-ffffffff81268f26: rethook_find_ret_addr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
long unsigned int rethook_find_ret_addr(struct task_struct *tsk, long unsigned int frame, struct llist_node **cur);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/rethook.c (ffffffff812bb1a0)
Location: kernel/trace/rethook.c:236
Inline: False
Direct callers:
  - arch/x86/kernel/unwind_frame.c:update_stack_state
```
**Symbols:**

```
ffffffff812bb1a0-ffffffff812bb226: rethook_find_ret_addr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
long unsigned int rethook_find_ret_addr(struct task_struct *tsk, long unsigned int frame, struct llist_node **cur);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/rethook.c (ffffffff812deda0)
Location: kernel/trace/rethook.c:249
Inline: False
Direct callers:
  - arch/x86/kernel/unwind_frame.c:update_stack_state
```
**Symbols:**

```
ffffffff812deda0-ffffffff812dee26: rethook_find_ret_addr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
long unsigned int rethook_find_ret_addr(struct task_struct *tsk, long unsigned int frame, struct llist_node **cur);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/rethook.c (ffffffff812fcda0)
Location: kernel/trace/rethook.c:242
Inline: False
Direct callers:
  - arch/x86/kernel/unwind_frame.c:update_stack_state
```
**Symbols:**

```
ffffffff812fcda0-ffffffff812fce26: rethook_find_ret_addr (STB_GLOBAL)
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
No changes between <code>5.19</code> and <code>6.2</code> ✅
</li>
<li>
No changes between <code>6.2</code> and <code>6.5</code> ✅
</li>
<li>
No changes between <code>6.5</code> and <code>6.8</code> ✅
</li>
</ul>
