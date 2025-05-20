# Function: <code>ops_references_ip</code>

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
In <code>5.19</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
bool ops_references_ip(struct ftrace_ops *ops, long unsigned int ip);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/trace/ftrace.c (0)
Location: kernel/trace/ftrace.c:6829
Inline: False
Direct callers:
  - kernel/trace/ftrace.c:unregister_ftrace_function
  - kernel/trace/ftrace.c:register_ftrace_function
  - kernel/trace/ftrace.c:ftrace_module_enable
```
**Symbols:**

```
ffffffff81254aa0-ffffffff81254b9d: ops_references_ip (STB_LOCAL)
ffffffff8205cda2-ffffffff8205cdc6: ops_references_ip.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
bool ops_references_ip(struct ftrace_ops *ops, long unsigned int ip);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/trace/ftrace.c (0)
Location: kernel/trace/ftrace.c:6644
Inline: False
Direct callers:
  - kernel/trace/ftrace.c:unregister_ftrace_function
  - kernel/trace/ftrace.c:register_ftrace_function
  - kernel/trace/ftrace.c:ftrace_module_enable
```
**Symbols:**

```
ffffffff8126bdc0-ffffffff8126bebd: ops_references_ip (STB_LOCAL)
ffffffff820db6d0-ffffffff820db6f4: ops_references_ip.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
bool ops_references_ip(struct ftrace_ops *ops, long unsigned int ip);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/trace/ftrace.c (0)
Location: kernel/trace/ftrace.c:6648
Inline: False
Direct callers:
  - kernel/trace/ftrace.c:unregister_ftrace_function
  - kernel/trace/ftrace.c:register_ftrace_function
  - kernel/trace/ftrace.c:ftrace_module_enable
```
**Symbols:**

```
ffffffff812863b0-ffffffff812864ad: ops_references_ip (STB_LOCAL)
ffffffff821b7441-ffffffff821b7465: ops_references_ip.cold (STB_LOCAL)
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
No changes between <code>6.2</code> and <code>6.5</code> ✅
</li>
<li>
No changes between <code>6.5</code> and <code>6.8</code> ✅
</li>
</ul>
