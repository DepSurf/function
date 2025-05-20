# Function: <code>ftrace_profile_tracefs</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/trace/ftrace.c (ffffffff81f83595)
Location: kernel/trace/ftrace.c:1051
Inline: True
Inline callers:
  - kernel/trace/ftrace.c:ftrace_init_tracefs
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/trace/ftrace.c (ffffffff81facc42)
Location: kernel/trace/ftrace.c:1023
Inline: True
Inline callers:
  - kernel/trace/ftrace.c:ftrace_init_tracefs_toplevel
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
In kernel/trace/ftrace.c (ffffffff81fe8f60)
Location: kernel/trace/ftrace.c:1029
Inline: True
Inline callers:
  - kernel/trace/ftrace.c:ftrace_init_tracefs_toplevel
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
In kernel/trace/ftrace.c (ffffffff820c98eb)
Location: kernel/trace/ftrace.c:1046
Inline: True
Inline callers:
  - kernel/trace/ftrace.c:ftrace_init_tracefs_toplevel
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
In kernel/trace/ftrace.c (ffffffff826d1fe1)
Location: kernel/trace/ftrace.c:1017
Inline: True
Inline callers:
  - kernel/trace/ftrace.c:ftrace_init_tracefs_toplevel
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
In kernel/trace/ftrace.c (ffffffff826fc7fe)
Location: kernel/trace/ftrace.c:1006
Inline: True
Inline callers:
  - kernel/trace/ftrace.c:ftrace_init_tracefs_toplevel
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
In kernel/trace/ftrace.c (ffffffff828b3718)
Location: kernel/trace/ftrace.c:963
Inline: True
Inline callers:
  - kernel/trace/ftrace.c:ftrace_init_tracefs_toplevel
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
In kernel/trace/ftrace.c (ffffffff828cc499)
Location: kernel/trace/ftrace.c:960
Inline: True
Inline callers:
  - kernel/trace/ftrace.c:ftrace_init_tracefs_toplevel
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
In kernel/trace/ftrace.c (ffffffff828d4963)
Location: kernel/trace/ftrace.c:961
Inline: True
Inline callers:
  - kernel/trace/ftrace.c:ftrace_init_tracefs_toplevel
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void ftrace_profile_tracefs(struct dentry *d_tracer);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/ftrace.c (ffffffff82cf4e56)
Location: kernel/trace/ftrace.c:957
Inline: False
Direct callers:
  - kernel/trace/ftrace.c:ftrace_init_tracefs_toplevel
```
**Symbols:**

```
ffffffff82cf4e56-ffffffff82cf4f3f: ftrace_profile_tracefs (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void ftrace_profile_tracefs(struct dentry *d_tracer);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/ftrace.c (ffffffff82fe1935)
Location: kernel/trace/ftrace.c:957
Inline: False
Direct callers:
  - kernel/trace/ftrace.c:ftrace_init_tracefs_toplevel
```
**Symbols:**

```
ffffffff82fe1935-ffffffff82fe1a1e: ftrace_profile_tracefs (STB_LOCAL)
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
In kernel/trace/ftrace.c (ffffffff831ec325)
Location: kernel/trace/ftrace.c:957
Inline: True
Inline callers:
  - kernel/trace/ftrace.c:ftrace_init_tracefs_toplevel
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
In kernel/trace/ftrace.c (ffffffff832d0dad)
Location: kernel/trace/ftrace.c:957
Inline: True
Inline callers:
  - kernel/trace/ftrace.c:ftrace_init_tracefs_toplevel
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
In kernel/trace/ftrace.c (ffffffff83484e85)
Location: kernel/trace/ftrace.c:954
Inline: True
Inline callers:
  - kernel/trace/ftrace.c:ftrace_init_tracefs_toplevel
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
In kernel/trace/ftrace.c (0)
Location: kernel/trace/ftrace.c:954
Inline: True
Inline callers:
  - kernel/trace/ftrace.c:ftrace_init_tracefs_toplevel
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void ftrace_profile_tracefs(struct dentry *d_tracer);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/ftrace.c (ffffffff836d81b0)
Location: kernel/trace/ftrace.c:985
Inline: False
Direct callers:
  - kernel/trace/ftrace.c:ftrace_init_tracefs_toplevel
```
**Symbols:**

```
ffffffff836d81b0-ffffffff836d8334: ftrace_profile_tracefs (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void ftrace_profile_tracefs(struct dentry *d_tracer);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/ftrace.c (ffffffff8390a740)
Location: kernel/trace/ftrace.c:985
Inline: False
Direct callers:
  - kernel/trace/ftrace.c:ftrace_init_tracefs_toplevel
```
**Symbols:**

```
ffffffff8390a740-ffffffff8390a8c4: ftrace_profile_tracefs (STB_LOCAL)
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
In kernel/trace/ftrace.c (ffff80001144d150)
Location: kernel/trace/ftrace.c:961
Inline: True
Inline callers:
  - kernel/trace/ftrace.c:ftrace_init_tracefs_toplevel
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
In kernel/trace/ftrace.c (c15276b0)
Location: kernel/trace/ftrace.c:961
Inline: True
Inline callers:
  - kernel/trace/ftrace.c:ftrace_init_tracefs_toplevel
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
In kernel/trace/ftrace.c (c000000001373490)
Location: kernel/trace/ftrace.c:961
Inline: True
Inline callers:
  - kernel/trace/ftrace.c:ftrace_init_tracefs_toplevel
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
In kernel/trace/ftrace.c (ffffffe00000d870)
Location: kernel/trace/ftrace.c:961
Inline: True
Inline callers:
  - kernel/trace/ftrace.c:ftrace_init_tracefs_toplevel
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
In kernel/trace/ftrace.c (ffffffff828bd814)
Location: kernel/trace/ftrace.c:961
Inline: True
Inline callers:
  - kernel/trace/ftrace.c:ftrace_init_tracefs_toplevel
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
In kernel/trace/ftrace.c (ffffffff828b5eb4)
Location: kernel/trace/ftrace.c:961
Inline: True
Inline callers:
  - kernel/trace/ftrace.c:ftrace_init_tracefs_toplevel
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
In kernel/trace/ftrace.c (ffffffff828d0597)
Location: kernel/trace/ftrace.c:961
Inline: True
Inline callers:
  - kernel/trace/ftrace.c:ftrace_init_tracefs_toplevel
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
In kernel/trace/ftrace.c (ffffffff828d59b8)
Location: kernel/trace/ftrace.c:961
Inline: True
Inline callers:
  - kernel/trace/ftrace.c:ftrace_init_tracefs_toplevel
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>5.8</code> and <code>5.11</code> ✅
</li>
<li>
No changes between <code>6.5</code> and <code>6.8</code> ✅
</li>
</ul>
