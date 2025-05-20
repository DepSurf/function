# Function: <code>sysctl_head_finish</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void sysctl_head_finish(struct ctl_table_header *head);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/proc/proc_sysctl.c (ffffffff81284b40)
Location: fs/proc/proc_sysctl.c:312
Inline: False
Direct callers:
  - fs/proc/proc_sysctl.c:proc_sys_open
  - fs/proc/proc_sysctl.c:proc_sys_poll
  - fs/proc/proc_sysctl.c:proc_sys_permission
  - fs/proc/proc_sysctl.c:proc_sys_getattr
  - fs/proc/proc_sysctl.c:proc_sys_lookup
  - fs/proc/proc_sysctl.c:proc_sys_lookup
  - fs/proc/proc_sysctl.c:proc_sys_readdir
  - fs/proc/proc_sysctl.c:proc_sys_readdir
  - fs/proc/proc_sysctl.c:proc_sys_readdir
  - fs/proc/proc_sysctl.c:proc_sys_call_handler
```
**Symbols:**

```
ffffffff81284b40-ffffffff81284b81: sysctl_head_finish (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void sysctl_head_finish(struct ctl_table_header *head);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/proc/proc_sysctl.c (ffffffff812b1c10)
Location: fs/proc/proc_sysctl.c:312
Inline: False
Direct callers:
  - fs/proc/proc_sysctl.c:proc_sys_getattr
  - fs/proc/proc_sysctl.c:proc_sys_permission
  - fs/proc/proc_sysctl.c:proc_sys_readdir
  - fs/proc/proc_sysctl.c:proc_sys_readdir
  - fs/proc/proc_sysctl.c:proc_sys_readdir
  - fs/proc/proc_sysctl.c:proc_sys_readdir
  - fs/proc/proc_sysctl.c:proc_sys_poll
  - fs/proc/proc_sysctl.c:proc_sys_open
  - fs/proc/proc_sysctl.c:proc_sys_call_handler
  - fs/proc/proc_sysctl.c:proc_sys_lookup
  - fs/proc/proc_sysctl.c:proc_sys_lookup
```
**Symbols:**

```
ffffffff812b1c10-ffffffff812b1c51: sysctl_head_finish (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void sysctl_head_finish(struct ctl_table_header *head);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/proc/proc_sysctl.c (ffffffff812c74a0)
Location: fs/proc/proc_sysctl.c:312
Inline: False
Direct callers:
  - fs/proc/proc_sysctl.c:proc_sys_getattr
  - fs/proc/proc_sysctl.c:proc_sys_permission
  - fs/proc/proc_sysctl.c:proc_sys_readdir
  - fs/proc/proc_sysctl.c:proc_sys_readdir
  - fs/proc/proc_sysctl.c:proc_sys_readdir
  - fs/proc/proc_sysctl.c:proc_sys_readdir
  - fs/proc/proc_sysctl.c:proc_sys_poll
  - fs/proc/proc_sysctl.c:proc_sys_open
  - fs/proc/proc_sysctl.c:proc_sys_call_handler
  - fs/proc/proc_sysctl.c:proc_sys_lookup
  - fs/proc/proc_sysctl.c:proc_sys_lookup
```
**Symbols:**

```
ffffffff812c74a0-ffffffff812c74e1: sysctl_head_finish (STB_LOCAL)
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
In fs/proc/proc_sysctl.c (ffffffff812d4bc9)
Location: fs/proc/proc_sysctl.c:343
Inline: True
Inline callers:
  - fs/proc/proc_sysctl.c:proc_sys_getattr
  - fs/proc/proc_sysctl.c:proc_sys_permission
  - fs/proc/proc_sysctl.c:proc_sys_readdir
  - fs/proc/proc_sysctl.c:proc_sys_readdir
  - fs/proc/proc_sysctl.c:proc_sys_readdir
  - fs/proc/proc_sysctl.c:proc_sys_poll
  - fs/proc/proc_sysctl.c:proc_sys_open
  - fs/proc/proc_sysctl.c:proc_sys_call_handler
  - fs/proc/proc_sysctl.c:proc_sys_lookup
  - fs/proc/proc_sysctl.c:proc_sys_lookup
Direct callers:
  - fs/proc/proc_sysctl.c:proc_sys_getattr
  - fs/proc/proc_sysctl.c:proc_sys_permission
  - fs/proc/proc_sysctl.c:proc_sys_readdir
  - fs/proc/proc_sysctl.c:proc_sys_readdir
  - fs/proc/proc_sysctl.c:proc_sys_readdir
  - fs/proc/proc_sysctl.c:proc_sys_readdir
  - fs/proc/proc_sysctl.c:proc_sys_poll
  - fs/proc/proc_sysctl.c:proc_sys_open
  - fs/proc/proc_sysctl.c:proc_sys_call_handler
  - fs/proc/proc_sysctl.c:proc_sys_lookup
  - fs/proc/proc_sysctl.c:proc_sys_lookup
```
**Symbols:**

```
ffffffff812d4800-ffffffff812d483b: sysctl_head_finish.part.22 (STB_LOCAL)
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
In fs/proc/proc_sysctl.c (ffffffff812f93f9)
Location: fs/proc/proc_sysctl.c:344
Inline: True
Inline callers:
  - fs/proc/proc_sysctl.c:proc_sys_getattr
  - fs/proc/proc_sysctl.c:proc_sys_permission
  - fs/proc/proc_sysctl.c:proc_sys_readdir
  - fs/proc/proc_sysctl.c:proc_sys_readdir
  - fs/proc/proc_sysctl.c:proc_sys_readdir
  - fs/proc/proc_sysctl.c:proc_sys_poll
  - fs/proc/proc_sysctl.c:proc_sys_open
  - fs/proc/proc_sysctl.c:proc_sys_call_handler
  - fs/proc/proc_sysctl.c:proc_sys_lookup
  - fs/proc/proc_sysctl.c:proc_sys_lookup
Direct callers:
  - fs/proc/proc_sysctl.c:proc_sys_getattr
  - fs/proc/proc_sysctl.c:proc_sys_permission
  - fs/proc/proc_sysctl.c:proc_sys_readdir
  - fs/proc/proc_sysctl.c:proc_sys_readdir
  - fs/proc/proc_sysctl.c:proc_sys_readdir
  - fs/proc/proc_sysctl.c:proc_sys_readdir
  - fs/proc/proc_sysctl.c:proc_sys_poll
  - fs/proc/proc_sysctl.c:proc_sys_open
  - fs/proc/proc_sysctl.c:proc_sys_call_handler
  - fs/proc/proc_sysctl.c:proc_sys_lookup
  - fs/proc/proc_sysctl.c:proc_sys_lookup
```
**Symbols:**

```
ffffffff812f9030-ffffffff812f906b: sysctl_head_finish.part.22 (STB_LOCAL)
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
In fs/proc/proc_sysctl.c (ffffffff81325fb5)
Location: fs/proc/proc_sysctl.c:344
Inline: True
Inline callers:
  - fs/proc/proc_sysctl.c:proc_sys_getattr
  - fs/proc/proc_sysctl.c:proc_sys_permission
  - fs/proc/proc_sysctl.c:proc_sys_readdir
  - fs/proc/proc_sysctl.c:proc_sys_readdir
  - fs/proc/proc_sysctl.c:proc_sys_readdir
  - fs/proc/proc_sysctl.c:proc_sys_poll
  - fs/proc/proc_sysctl.c:proc_sys_open
  - fs/proc/proc_sysctl.c:proc_sys_call_handler
  - fs/proc/proc_sysctl.c:proc_sys_lookup
  - fs/proc/proc_sysctl.c:proc_sys_lookup
Direct callers:
  - fs/proc/proc_sysctl.c:proc_sys_getattr
  - fs/proc/proc_sysctl.c:proc_sys_permission
  - fs/proc/proc_sysctl.c:proc_sys_readdir
  - fs/proc/proc_sysctl.c:proc_sys_readdir
  - fs/proc/proc_sysctl.c:proc_sys_readdir
  - fs/proc/proc_sysctl.c:proc_sys_readdir
  - fs/proc/proc_sysctl.c:proc_sys_poll
  - fs/proc/proc_sysctl.c:proc_sys_open
  - fs/proc/proc_sysctl.c:proc_sys_call_handler
  - fs/proc/proc_sysctl.c:proc_sys_lookup
  - fs/proc/proc_sysctl.c:proc_sys_lookup
```
**Symbols:**

```
ffffffff81325bf0-ffffffff81325c29: sysctl_head_finish.part.27 (STB_LOCAL)
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
In fs/proc/proc_sysctl.c (ffffffff8133d165)
Location: fs/proc/proc_sysctl.c:344
Inline: True
Inline callers:
  - fs/proc/proc_sysctl.c:proc_sys_getattr
  - fs/proc/proc_sysctl.c:proc_sys_permission
  - fs/proc/proc_sysctl.c:proc_sys_readdir
  - fs/proc/proc_sysctl.c:proc_sys_readdir
  - fs/proc/proc_sysctl.c:proc_sys_readdir
  - fs/proc/proc_sysctl.c:proc_sys_poll
  - fs/proc/proc_sysctl.c:proc_sys_open
  - fs/proc/proc_sysctl.c:proc_sys_call_handler
  - fs/proc/proc_sysctl.c:proc_sys_lookup
  - fs/proc/proc_sysctl.c:proc_sys_lookup
Direct callers:
  - fs/proc/proc_sysctl.c:proc_sys_getattr
  - fs/proc/proc_sysctl.c:proc_sys_permission
  - fs/proc/proc_sysctl.c:proc_sys_readdir
  - fs/proc/proc_sysctl.c:proc_sys_readdir
  - fs/proc/proc_sysctl.c:proc_sys_readdir
  - fs/proc/proc_sysctl.c:proc_sys_readdir
  - fs/proc/proc_sysctl.c:proc_sys_poll
  - fs/proc/proc_sysctl.c:proc_sys_open
  - fs/proc/proc_sysctl.c:proc_sys_call_handler
  - fs/proc/proc_sysctl.c:proc_sys_lookup
  - fs/proc/proc_sysctl.c:proc_sys_lookup
```
**Symbols:**

```
ffffffff8133cd50-ffffffff8133cd89: sysctl_head_finish.part.27 (STB_LOCAL)
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
In fs/proc/proc_sysctl.c (ffffffff81365462)
Location: fs/proc/proc_sysctl.c:349
Inline: True
Inline callers:
  - fs/proc/proc_sysctl.c:proc_sys_getattr
  - fs/proc/proc_sysctl.c:proc_sys_permission
  - fs/proc/proc_sysctl.c:proc_sys_readdir
  - fs/proc/proc_sysctl.c:proc_sys_readdir
  - fs/proc/proc_sysctl.c:proc_sys_readdir
  - fs/proc/proc_sysctl.c:proc_sys_poll
  - fs/proc/proc_sysctl.c:proc_sys_open
  - fs/proc/proc_sysctl.c:proc_sys_call_handler
  - fs/proc/proc_sysctl.c:proc_sys_lookup
  - fs/proc/proc_sysctl.c:proc_sys_lookup
Direct callers:
  - fs/proc/proc_sysctl.c:proc_sys_getattr
  - fs/proc/proc_sysctl.c:proc_sys_permission
  - fs/proc/proc_sysctl.c:proc_sys_readdir
  - fs/proc/proc_sysctl.c:proc_sys_readdir
  - fs/proc/proc_sysctl.c:proc_sys_readdir
  - fs/proc/proc_sysctl.c:proc_sys_readdir
  - fs/proc/proc_sysctl.c:proc_sys_poll
  - fs/proc/proc_sysctl.c:proc_sys_open
  - fs/proc/proc_sysctl.c:proc_sys_call_handler
  - fs/proc/proc_sysctl.c:proc_sys_lookup
  - fs/proc/proc_sysctl.c:proc_sys_lookup
```
**Symbols:**

```
ffffffff81364f90-ffffffff81364fc9: sysctl_head_finish.part.0 (STB_LOCAL)
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
In fs/proc/proc_sysctl.c (ffffffff8137d6f2)
Location: fs/proc/proc_sysctl.c:349
Inline: True
Inline callers:
  - fs/proc/proc_sysctl.c:proc_sys_getattr
  - fs/proc/proc_sysctl.c:proc_sys_permission
  - fs/proc/proc_sysctl.c:proc_sys_readdir
  - fs/proc/proc_sysctl.c:proc_sys_readdir
  - fs/proc/proc_sysctl.c:proc_sys_readdir
  - fs/proc/proc_sysctl.c:proc_sys_poll
  - fs/proc/proc_sysctl.c:proc_sys_open
  - fs/proc/proc_sysctl.c:proc_sys_call_handler
  - fs/proc/proc_sysctl.c:proc_sys_lookup
  - fs/proc/proc_sysctl.c:proc_sys_lookup
Direct callers:
  - fs/proc/proc_sysctl.c:proc_sys_getattr
  - fs/proc/proc_sysctl.c:proc_sys_permission
  - fs/proc/proc_sysctl.c:proc_sys_readdir
  - fs/proc/proc_sysctl.c:proc_sys_readdir
  - fs/proc/proc_sysctl.c:proc_sys_readdir
  - fs/proc/proc_sysctl.c:proc_sys_readdir
  - fs/proc/proc_sysctl.c:proc_sys_poll
  - fs/proc/proc_sysctl.c:proc_sys_open
  - fs/proc/proc_sysctl.c:proc_sys_call_handler
  - fs/proc/proc_sysctl.c:proc_sys_lookup
  - fs/proc/proc_sysctl.c:proc_sys_lookup
```
**Symbols:**

```
ffffffff8137d220-ffffffff8137d259: sysctl_head_finish.part.0 (STB_LOCAL)
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
In fs/proc/proc_sysctl.c (ffffffff813c7506)
Location: fs/proc/proc_sysctl.c:317
Inline: True
Inline callers:
  - fs/proc/proc_sysctl.c:proc_sys_getattr
  - fs/proc/proc_sysctl.c:proc_sys_getattr
  - fs/proc/proc_sysctl.c:proc_sys_permission
  - fs/proc/proc_sysctl.c:proc_sys_permission
  - fs/proc/proc_sysctl.c:proc_sys_readdir
  - fs/proc/proc_sysctl.c:proc_sys_readdir
  - fs/proc/proc_sysctl.c:proc_sys_readdir
  - fs/proc/proc_sysctl.c:proc_sys_poll
  - fs/proc/proc_sysctl.c:proc_sys_poll
  - fs/proc/proc_sysctl.c:proc_sys_open
  - fs/proc/proc_sysctl.c:proc_sys_open
  - fs/proc/proc_sysctl.c:proc_sys_lookup
  - fs/proc/proc_sysctl.c:proc_sys_lookup
  - fs/proc/proc_sysctl.c:proc_sys_lookup
Direct callers:
  - fs/proc/proc_sysctl.c:proc_sys_readdir
  - fs/proc/proc_sysctl.c:proc_sys_readdir
  - fs/proc/proc_sysctl.c:proc_sys_readdir
  - fs/proc/proc_sysctl.c:proc_sys_readdir
  - fs/proc/proc_sysctl.c:proc_sys_lookup
```
**Symbols:**

```
ffffffff813c7110-ffffffff813c7153: sysctl_head_finish.part.0 (STB_LOCAL)
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
In fs/proc/proc_sysctl.c (ffffffff813d94f6)
Location: fs/proc/proc_sysctl.c:318
Inline: True
Inline callers:
  - fs/proc/proc_sysctl.c:proc_sys_getattr
  - fs/proc/proc_sysctl.c:proc_sys_getattr
  - fs/proc/proc_sysctl.c:proc_sys_permission
  - fs/proc/proc_sysctl.c:proc_sys_permission
  - fs/proc/proc_sysctl.c:proc_sys_readdir
  - fs/proc/proc_sysctl.c:proc_sys_readdir
  - fs/proc/proc_sysctl.c:proc_sys_readdir
  - fs/proc/proc_sysctl.c:proc_sys_poll
  - fs/proc/proc_sysctl.c:proc_sys_poll
  - fs/proc/proc_sysctl.c:proc_sys_open
  - fs/proc/proc_sysctl.c:proc_sys_open
  - fs/proc/proc_sysctl.c:proc_sys_call_handler
  - fs/proc/proc_sysctl.c:proc_sys_lookup
  - fs/proc/proc_sysctl.c:proc_sys_lookup
  - fs/proc/proc_sysctl.c:proc_sys_lookup
Direct callers:
  - fs/proc/proc_sysctl.c:proc_sys_readdir
  - fs/proc/proc_sysctl.c:proc_sys_readdir
  - fs/proc/proc_sysctl.c:proc_sys_readdir
  - fs/proc/proc_sysctl.c:proc_sys_readdir
  - fs/proc/proc_sysctl.c:proc_sys_call_handler
  - fs/proc/proc_sysctl.c:proc_sys_lookup
```
**Symbols:**

```
ffffffff813d90e0-ffffffff813d9123: sysctl_head_finish.part.0 (STB_LOCAL)
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
In fs/proc/proc_sysctl.c (ffffffff813e040d)
Location: fs/proc/proc_sysctl.c:313
Inline: True
Inline callers:
  - fs/proc/proc_sysctl.c:proc_sys_getattr
  - fs/proc/proc_sysctl.c:proc_sys_getattr
  - fs/proc/proc_sysctl.c:proc_sys_permission
  - fs/proc/proc_sysctl.c:proc_sys_permission
  - fs/proc/proc_sysctl.c:proc_sys_readdir
  - fs/proc/proc_sysctl.c:proc_sys_readdir
  - fs/proc/proc_sysctl.c:proc_sys_readdir
  - fs/proc/proc_sysctl.c:proc_sys_readdir
  - fs/proc/proc_sysctl.c:proc_sys_poll
  - fs/proc/proc_sysctl.c:proc_sys_poll
  - fs/proc/proc_sysctl.c:proc_sys_open
  - fs/proc/proc_sysctl.c:proc_sys_open
  - fs/proc/proc_sysctl.c:proc_sys_call_handler
  - fs/proc/proc_sysctl.c:proc_sys_call_handler
  - fs/proc/proc_sysctl.c:proc_sys_lookup
  - fs/proc/proc_sysctl.c:proc_sys_lookup
  - fs/proc/proc_sysctl.c:proc_sys_lookup
  - fs/proc/proc_sysctl.c:proc_sys_lookup
Direct callers:
  - fs/proc/proc_sysctl.c:proc_sys_readdir
  - fs/proc/proc_sysctl.c:proc_sys_readdir
  - fs/proc/proc_sysctl.c:proc_sys_readdir
```
**Symbols:**

```
ffffffff813e0150-ffffffff813e0193: sysctl_head_finish.part.0 (STB_LOCAL)
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
In fs/proc/proc_sysctl.c (ffffffff81431d99)
Location: fs/proc/proc_sysctl.c:313
Inline: True
Inline callers:
  - fs/proc/proc_sysctl.c:proc_sys_getattr
  - fs/proc/proc_sysctl.c:proc_sys_getattr
  - fs/proc/proc_sysctl.c:proc_sys_permission
  - fs/proc/proc_sysctl.c:proc_sys_permission
  - fs/proc/proc_sysctl.c:proc_sys_readdir
  - fs/proc/proc_sysctl.c:proc_sys_readdir
  - fs/proc/proc_sysctl.c:proc_sys_readdir
  - fs/proc/proc_sysctl.c:proc_sys_readdir
  - fs/proc/proc_sysctl.c:proc_sys_poll
  - fs/proc/proc_sysctl.c:proc_sys_poll
  - fs/proc/proc_sysctl.c:proc_sys_open
  - fs/proc/proc_sysctl.c:proc_sys_open
  - fs/proc/proc_sysctl.c:proc_sys_call_handler
  - fs/proc/proc_sysctl.c:proc_sys_call_handler
  - fs/proc/proc_sysctl.c:proc_sys_lookup
  - fs/proc/proc_sysctl.c:proc_sys_lookup
  - fs/proc/proc_sysctl.c:proc_sys_lookup
  - fs/proc/proc_sysctl.c:proc_sys_lookup
Direct callers:
  - fs/proc/proc_sysctl.c:proc_sys_readdir
  - fs/proc/proc_sysctl.c:proc_sys_readdir
  - fs/proc/proc_sysctl.c:proc_sys_readdir
```
**Symbols:**

```
ffffffff81431ae0-ffffffff81431b23: sysctl_head_finish.part.0 (STB_LOCAL)
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
In fs/proc/proc_sysctl.c (ffffffff814ac1df)
Location: fs/proc/proc_sysctl.c:338
Inline: True
Inline callers:
  - fs/proc/proc_sysctl.c:proc_sys_getattr
  - fs/proc/proc_sysctl.c:proc_sys_getattr
  - fs/proc/proc_sysctl.c:proc_sys_permission
  - fs/proc/proc_sysctl.c:proc_sys_permission
  - fs/proc/proc_sysctl.c:proc_sys_readdir
  - fs/proc/proc_sysctl.c:proc_sys_readdir
  - fs/proc/proc_sysctl.c:proc_sys_readdir
  - fs/proc/proc_sysctl.c:proc_sys_readdir
  - fs/proc/proc_sysctl.c:proc_sys_readdir
  - fs/proc/proc_sysctl.c:proc_sys_readdir
  - fs/proc/proc_sysctl.c:proc_sys_poll
  - fs/proc/proc_sysctl.c:proc_sys_poll
  - fs/proc/proc_sysctl.c:proc_sys_open
  - fs/proc/proc_sysctl.c:proc_sys_open
  - fs/proc/proc_sysctl.c:proc_sys_call_handler
  - fs/proc/proc_sysctl.c:proc_sys_call_handler
  - fs/proc/proc_sysctl.c:proc_sys_lookup
  - fs/proc/proc_sysctl.c:proc_sys_lookup
  - fs/proc/proc_sysctl.c:proc_sys_lookup
  - fs/proc/proc_sysctl.c:proc_sys_lookup
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
In fs/proc/proc_sysctl.c (ffffffff8154200f)
Location: fs/proc/proc_sysctl.c:331
Inline: True
Inline callers:
  - fs/proc/proc_sysctl.c:proc_sys_getattr
  - fs/proc/proc_sysctl.c:proc_sys_getattr
  - fs/proc/proc_sysctl.c:proc_sys_permission
  - fs/proc/proc_sysctl.c:proc_sys_permission
  - fs/proc/proc_sysctl.c:proc_sys_readdir
  - fs/proc/proc_sysctl.c:proc_sys_readdir
  - fs/proc/proc_sysctl.c:proc_sys_readdir
  - fs/proc/proc_sysctl.c:proc_sys_readdir
  - fs/proc/proc_sysctl.c:proc_sys_readdir
  - fs/proc/proc_sysctl.c:proc_sys_readdir
  - fs/proc/proc_sysctl.c:proc_sys_poll
  - fs/proc/proc_sysctl.c:proc_sys_poll
  - fs/proc/proc_sysctl.c:proc_sys_open
  - fs/proc/proc_sysctl.c:proc_sys_open
  - fs/proc/proc_sysctl.c:proc_sys_call_handler
  - fs/proc/proc_sysctl.c:proc_sys_call_handler
  - fs/proc/proc_sysctl.c:proc_sys_lookup
  - fs/proc/proc_sysctl.c:proc_sys_lookup
  - fs/proc/proc_sysctl.c:proc_sys_lookup
  - fs/proc/proc_sysctl.c:proc_sys_lookup
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
In fs/proc/proc_sysctl.c (ffffffff8157a16f)
Location: fs/proc/proc_sysctl.c:325
Inline: True
Inline callers:
  - fs/proc/proc_sysctl.c:proc_sys_getattr
  - fs/proc/proc_sysctl.c:proc_sys_getattr
  - fs/proc/proc_sysctl.c:proc_sys_permission
  - fs/proc/proc_sysctl.c:proc_sys_permission
  - fs/proc/proc_sysctl.c:proc_sys_readdir
  - fs/proc/proc_sysctl.c:proc_sys_readdir
  - fs/proc/proc_sysctl.c:proc_sys_readdir
  - fs/proc/proc_sysctl.c:proc_sys_readdir
  - fs/proc/proc_sysctl.c:proc_sys_readdir
  - fs/proc/proc_sysctl.c:proc_sys_readdir
  - fs/proc/proc_sysctl.c:proc_sys_poll
  - fs/proc/proc_sysctl.c:proc_sys_poll
  - fs/proc/proc_sysctl.c:proc_sys_open
  - fs/proc/proc_sysctl.c:proc_sys_open
  - fs/proc/proc_sysctl.c:proc_sys_call_handler
  - fs/proc/proc_sysctl.c:proc_sys_call_handler
  - fs/proc/proc_sysctl.c:proc_sys_lookup
  - fs/proc/proc_sysctl.c:proc_sys_lookup
  - fs/proc/proc_sysctl.c:proc_sys_lookup
  - fs/proc/proc_sysctl.c:proc_sys_lookup
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
In fs/proc/proc_sysctl.c (ffffffff815b2a77)
Location: fs/proc/proc_sysctl.c:327
Inline: True
Inline callers:
  - fs/proc/proc_sysctl.c:proc_sys_getattr
  - fs/proc/proc_sysctl.c:proc_sys_getattr
  - fs/proc/proc_sysctl.c:proc_sys_permission
  - fs/proc/proc_sysctl.c:proc_sys_permission
  - fs/proc/proc_sysctl.c:proc_sys_readdir
  - fs/proc/proc_sysctl.c:proc_sys_readdir
  - fs/proc/proc_sysctl.c:proc_sys_readdir
  - fs/proc/proc_sysctl.c:proc_sys_readdir
  - fs/proc/proc_sysctl.c:proc_sys_readdir
  - fs/proc/proc_sysctl.c:proc_sys_readdir
  - fs/proc/proc_sysctl.c:proc_sys_poll
  - fs/proc/proc_sysctl.c:proc_sys_poll
  - fs/proc/proc_sysctl.c:proc_sys_open
  - fs/proc/proc_sysctl.c:proc_sys_open
  - fs/proc/proc_sysctl.c:proc_sys_call_handler
  - fs/proc/proc_sysctl.c:proc_sys_call_handler
  - fs/proc/proc_sysctl.c:proc_sys_lookup
  - fs/proc/proc_sysctl.c:proc_sys_lookup
  - fs/proc/proc_sysctl.c:proc_sys_lookup
  - fs/proc/proc_sysctl.c:proc_sys_lookup
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
In fs/proc/proc_sysctl.c (ffff80001044a3f8)
Location: fs/proc/proc_sysctl.c:349
Inline: True
Inline callers:
  - fs/proc/proc_sysctl.c:proc_sys_getattr
  - fs/proc/proc_sysctl.c:proc_sys_permission
  - fs/proc/proc_sysctl.c:proc_sys_readdir
  - fs/proc/proc_sysctl.c:proc_sys_readdir
  - fs/proc/proc_sysctl.c:proc_sys_readdir
  - fs/proc/proc_sysctl.c:proc_sys_poll
  - fs/proc/proc_sysctl.c:proc_sys_open
  - fs/proc/proc_sysctl.c:proc_sys_call_handler
  - fs/proc/proc_sysctl.c:proc_sys_lookup
  - fs/proc/proc_sysctl.c:proc_sys_lookup
Direct callers:
  - fs/proc/proc_sysctl.c:proc_sys_getattr
  - fs/proc/proc_sysctl.c:proc_sys_permission
  - fs/proc/proc_sysctl.c:proc_sys_readdir
  - fs/proc/proc_sysctl.c:proc_sys_readdir
  - fs/proc/proc_sysctl.c:proc_sys_readdir
  - fs/proc/proc_sysctl.c:proc_sys_readdir
  - fs/proc/proc_sysctl.c:proc_sys_poll
  - fs/proc/proc_sysctl.c:proc_sys_open
  - fs/proc/proc_sysctl.c:proc_sys_call_handler
  - fs/proc/proc_sysctl.c:proc_sys_lookup
  - fs/proc/proc_sysctl.c:proc_sys_lookup
```
**Symbols:**

```
ffff800010449d70-ffff800010449e08: sysctl_head_finish.part.0 (STB_LOCAL)
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
In fs/proc/proc_sysctl.c (c060f7fc)
Location: fs/proc/proc_sysctl.c:349
Inline: True
Inline callers:
  - fs/proc/proc_sysctl.c:proc_sys_getattr
  - fs/proc/proc_sysctl.c:proc_sys_permission
  - fs/proc/proc_sysctl.c:proc_sys_readdir
  - fs/proc/proc_sysctl.c:proc_sys_readdir
  - fs/proc/proc_sysctl.c:proc_sys_readdir
  - fs/proc/proc_sysctl.c:proc_sys_poll
  - fs/proc/proc_sysctl.c:proc_sys_open
  - fs/proc/proc_sysctl.c:proc_sys_call_handler
  - fs/proc/proc_sysctl.c:proc_sys_lookup
  - fs/proc/proc_sysctl.c:proc_sys_lookup
Direct callers:
  - fs/proc/proc_sysctl.c:proc_sys_getattr
  - fs/proc/proc_sysctl.c:proc_sys_permission
  - fs/proc/proc_sysctl.c:proc_sys_readdir
  - fs/proc/proc_sysctl.c:proc_sys_readdir
  - fs/proc/proc_sysctl.c:proc_sys_readdir
  - fs/proc/proc_sysctl.c:proc_sys_readdir
  - fs/proc/proc_sysctl.c:proc_sys_poll
  - fs/proc/proc_sysctl.c:proc_sys_open
  - fs/proc/proc_sysctl.c:proc_sys_call_handler
  - fs/proc/proc_sysctl.c:proc_sys_lookup
  - fs/proc/proc_sysctl.c:proc_sys_lookup
```
**Symbols:**

```
c060f188-c060f1ec: sysctl_head_finish.part.0 (STB_LOCAL)
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
In fs/proc/proc_sysctl.c (c0000000005622c8)
Location: fs/proc/proc_sysctl.c:349
Inline: True
Inline callers:
  - fs/proc/proc_sysctl.c:proc_sys_getattr
  - fs/proc/proc_sysctl.c:proc_sys_permission
  - fs/proc/proc_sysctl.c:proc_sys_readdir
  - fs/proc/proc_sysctl.c:proc_sys_readdir
  - fs/proc/proc_sysctl.c:proc_sys_readdir
  - fs/proc/proc_sysctl.c:proc_sys_poll
  - fs/proc/proc_sysctl.c:proc_sys_open
  - fs/proc/proc_sysctl.c:proc_sys_call_handler
  - fs/proc/proc_sysctl.c:proc_sys_lookup
  - fs/proc/proc_sysctl.c:proc_sys_lookup
Direct callers:
  - fs/proc/proc_sysctl.c:proc_sys_getattr
  - fs/proc/proc_sysctl.c:proc_sys_permission
  - fs/proc/proc_sysctl.c:proc_sys_readdir
  - fs/proc/proc_sysctl.c:proc_sys_readdir
  - fs/proc/proc_sysctl.c:proc_sys_readdir
  - fs/proc/proc_sysctl.c:proc_sys_readdir
  - fs/proc/proc_sysctl.c:proc_sys_poll
  - fs/proc/proc_sysctl.c:proc_sys_open
  - fs/proc/proc_sysctl.c:proc_sys_call_handler
  - fs/proc/proc_sysctl.c:proc_sys_lookup
  - fs/proc/proc_sysctl.c:proc_sys_lookup
```
**Symbols:**

```
c000000000561920-c0000000005619ec: sysctl_head_finish.part.0 (STB_LOCAL)
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
In fs/proc/proc_sysctl.c (ffffffe0002dfa92)
Location: fs/proc/proc_sysctl.c:349
Inline: True
Inline callers:
  - fs/proc/proc_sysctl.c:proc_sys_getattr
  - fs/proc/proc_sysctl.c:proc_sys_permission
  - fs/proc/proc_sysctl.c:proc_sys_readdir
  - fs/proc/proc_sysctl.c:proc_sys_readdir
  - fs/proc/proc_sysctl.c:proc_sys_readdir
  - fs/proc/proc_sysctl.c:proc_sys_poll
  - fs/proc/proc_sysctl.c:proc_sys_open
  - fs/proc/proc_sysctl.c:proc_sys_call_handler
  - fs/proc/proc_sysctl.c:proc_sys_lookup
  - fs/proc/proc_sysctl.c:proc_sys_lookup
Direct callers:
  - fs/proc/proc_sysctl.c:proc_sys_getattr
  - fs/proc/proc_sysctl.c:proc_sys_permission
  - fs/proc/proc_sysctl.c:proc_sys_readdir
  - fs/proc/proc_sysctl.c:proc_sys_readdir
  - fs/proc/proc_sysctl.c:proc_sys_readdir
  - fs/proc/proc_sysctl.c:proc_sys_readdir
  - fs/proc/proc_sysctl.c:proc_sys_poll
  - fs/proc/proc_sysctl.c:proc_sys_open
  - fs/proc/proc_sysctl.c:proc_sys_call_handler
  - fs/proc/proc_sysctl.c:proc_sys_lookup
  - fs/proc/proc_sysctl.c:proc_sys_lookup
```
**Symbols:**

```
ffffffe0002df5b4-ffffffe0002df63e: sysctl_head_finish.part.0 (STB_LOCAL)
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
In fs/proc/proc_sysctl.c (ffffffff81375cd2)
Location: fs/proc/proc_sysctl.c:349
Inline: True
Inline callers:
  - fs/proc/proc_sysctl.c:proc_sys_getattr
  - fs/proc/proc_sysctl.c:proc_sys_permission
  - fs/proc/proc_sysctl.c:proc_sys_readdir
  - fs/proc/proc_sysctl.c:proc_sys_readdir
  - fs/proc/proc_sysctl.c:proc_sys_readdir
  - fs/proc/proc_sysctl.c:proc_sys_poll
  - fs/proc/proc_sysctl.c:proc_sys_open
  - fs/proc/proc_sysctl.c:proc_sys_call_handler
  - fs/proc/proc_sysctl.c:proc_sys_lookup
  - fs/proc/proc_sysctl.c:proc_sys_lookup
Direct callers:
  - fs/proc/proc_sysctl.c:proc_sys_getattr
  - fs/proc/proc_sysctl.c:proc_sys_permission
  - fs/proc/proc_sysctl.c:proc_sys_readdir
  - fs/proc/proc_sysctl.c:proc_sys_readdir
  - fs/proc/proc_sysctl.c:proc_sys_readdir
  - fs/proc/proc_sysctl.c:proc_sys_readdir
  - fs/proc/proc_sysctl.c:proc_sys_poll
  - fs/proc/proc_sysctl.c:proc_sys_open
  - fs/proc/proc_sysctl.c:proc_sys_call_handler
  - fs/proc/proc_sysctl.c:proc_sys_lookup
  - fs/proc/proc_sysctl.c:proc_sys_lookup
```
**Symbols:**

```
ffffffff81375800-ffffffff81375839: sysctl_head_finish.part.0 (STB_LOCAL)
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
In fs/proc/proc_sysctl.c (ffffffff813667a2)
Location: fs/proc/proc_sysctl.c:349
Inline: True
Inline callers:
  - fs/proc/proc_sysctl.c:proc_sys_getattr
  - fs/proc/proc_sysctl.c:proc_sys_permission
  - fs/proc/proc_sysctl.c:proc_sys_readdir
  - fs/proc/proc_sysctl.c:proc_sys_readdir
  - fs/proc/proc_sysctl.c:proc_sys_readdir
  - fs/proc/proc_sysctl.c:proc_sys_poll
  - fs/proc/proc_sysctl.c:proc_sys_open
  - fs/proc/proc_sysctl.c:proc_sys_call_handler
  - fs/proc/proc_sysctl.c:proc_sys_lookup
  - fs/proc/proc_sysctl.c:proc_sys_lookup
Direct callers:
  - fs/proc/proc_sysctl.c:proc_sys_getattr
  - fs/proc/proc_sysctl.c:proc_sys_permission
  - fs/proc/proc_sysctl.c:proc_sys_readdir
  - fs/proc/proc_sysctl.c:proc_sys_readdir
  - fs/proc/proc_sysctl.c:proc_sys_readdir
  - fs/proc/proc_sysctl.c:proc_sys_readdir
  - fs/proc/proc_sysctl.c:proc_sys_poll
  - fs/proc/proc_sysctl.c:proc_sys_open
  - fs/proc/proc_sysctl.c:proc_sys_call_handler
  - fs/proc/proc_sysctl.c:proc_sys_lookup
  - fs/proc/proc_sysctl.c:proc_sys_lookup
```
**Symbols:**

```
ffffffff813662d0-ffffffff81366309: sysctl_head_finish.part.0 (STB_LOCAL)
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
In fs/proc/proc_sysctl.c (ffffffff813737a2)
Location: fs/proc/proc_sysctl.c:349
Inline: True
Inline callers:
  - fs/proc/proc_sysctl.c:proc_sys_getattr
  - fs/proc/proc_sysctl.c:proc_sys_permission
  - fs/proc/proc_sysctl.c:proc_sys_readdir
  - fs/proc/proc_sysctl.c:proc_sys_readdir
  - fs/proc/proc_sysctl.c:proc_sys_readdir
  - fs/proc/proc_sysctl.c:proc_sys_poll
  - fs/proc/proc_sysctl.c:proc_sys_open
  - fs/proc/proc_sysctl.c:proc_sys_call_handler
  - fs/proc/proc_sysctl.c:proc_sys_lookup
  - fs/proc/proc_sysctl.c:proc_sys_lookup
Direct callers:
  - fs/proc/proc_sysctl.c:proc_sys_getattr
  - fs/proc/proc_sysctl.c:proc_sys_permission
  - fs/proc/proc_sysctl.c:proc_sys_readdir
  - fs/proc/proc_sysctl.c:proc_sys_readdir
  - fs/proc/proc_sysctl.c:proc_sys_readdir
  - fs/proc/proc_sysctl.c:proc_sys_readdir
  - fs/proc/proc_sysctl.c:proc_sys_poll
  - fs/proc/proc_sysctl.c:proc_sys_open
  - fs/proc/proc_sysctl.c:proc_sys_call_handler
  - fs/proc/proc_sysctl.c:proc_sys_lookup
  - fs/proc/proc_sysctl.c:proc_sys_lookup
```
**Symbols:**

```
ffffffff813732d0-ffffffff81373309: sysctl_head_finish.part.0 (STB_LOCAL)
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
In fs/proc/proc_sysctl.c (ffffffff813877c2)
Location: fs/proc/proc_sysctl.c:349
Inline: True
Inline callers:
  - fs/proc/proc_sysctl.c:proc_sys_getattr
  - fs/proc/proc_sysctl.c:proc_sys_permission
  - fs/proc/proc_sysctl.c:proc_sys_readdir
  - fs/proc/proc_sysctl.c:proc_sys_readdir
  - fs/proc/proc_sysctl.c:proc_sys_readdir
  - fs/proc/proc_sysctl.c:proc_sys_poll
  - fs/proc/proc_sysctl.c:proc_sys_open
  - fs/proc/proc_sysctl.c:proc_sys_call_handler
  - fs/proc/proc_sysctl.c:proc_sys_lookup
  - fs/proc/proc_sysctl.c:proc_sys_lookup
Direct callers:
  - fs/proc/proc_sysctl.c:proc_sys_getattr
  - fs/proc/proc_sysctl.c:proc_sys_permission
  - fs/proc/proc_sysctl.c:proc_sys_readdir
  - fs/proc/proc_sysctl.c:proc_sys_readdir
  - fs/proc/proc_sysctl.c:proc_sys_readdir
  - fs/proc/proc_sysctl.c:proc_sys_readdir
  - fs/proc/proc_sysctl.c:proc_sys_poll
  - fs/proc/proc_sysctl.c:proc_sys_open
  - fs/proc/proc_sysctl.c:proc_sys_call_handler
  - fs/proc/proc_sysctl.c:proc_sys_lookup
  - fs/proc/proc_sysctl.c:proc_sys_lookup
```
**Symbols:**

```
ffffffff813873b0-ffffffff813873e7: sysctl_head_finish.part.0 (STB_LOCAL)
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
