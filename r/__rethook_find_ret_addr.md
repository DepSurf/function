# Function: <code>__rethook_find_ret_addr</code>

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
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
long unsigned int __rethook_find_ret_addr(struct task_struct *tsk, struct llist_node **cur);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/trace/rethook.c (ffffffff812691da)
Location: kernel/trace/rethook.c:195
Inline: True
Inline callers:
  - kernel/trace/rethook.c:rethook_trampoline_handler
  - kernel/trace/rethook.c:rethook_find_ret_addr
```
**Symbols:**

```
ffffffff81268be0-ffffffff81268c31: __rethook_find_ret_addr (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
long unsigned int __rethook_find_ret_addr(struct task_struct *tsk, struct llist_node **cur);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/trace/rethook.c (ffffffff812bb53a)
Location: kernel/trace/rethook.c:197
Inline: True
Inline callers:
  - kernel/trace/rethook.c:rethook_trampoline_handler
  - kernel/trace/rethook.c:rethook_find_ret_addr
```
**Symbols:**

```
ffffffff812bae90-ffffffff812baee1: __rethook_find_ret_addr (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
long unsigned int __rethook_find_ret_addr(struct task_struct *tsk, struct llist_node **cur);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/trace/rethook.c (ffffffff812df15a)
Location: kernel/trace/rethook.c:210
Inline: True
Inline callers:
  - kernel/trace/rethook.c:rethook_trampoline_handler
  - kernel/trace/rethook.c:rethook_find_ret_addr
```
**Symbols:**

```
ffffffff812dea90-ffffffff812deae1: __rethook_find_ret_addr (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
long unsigned int __rethook_find_ret_addr(struct task_struct *tsk, struct llist_node **cur);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/trace/rethook.c (ffffffff812fd09a)
Location: kernel/trace/rethook.c:203
Inline: True
Inline callers:
  - kernel/trace/rethook.c:rethook_trampoline_handler
  - kernel/trace/rethook.c:rethook_find_ret_addr
```
**Symbols:**

```
ffffffff812fcba0-ffffffff812fcbf1: __rethook_find_ret_addr (STB_LOCAL)
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
