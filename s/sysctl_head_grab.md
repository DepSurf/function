# Function: <code>sysctl_head_grab</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline ⚠️</summary>

```c
struct ctl_table_header *sysctl_head_grab(struct ctl_table_header *head);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/proc/proc_sysctl.c (ffffffff812849b0)
Location: fs/proc/proc_sysctl.c:302
Inline: True
Direct callers:
  - fs/proc/proc_sysctl.c:proc_sys_open
  - fs/proc/proc_sysctl.c:proc_sys_poll
  - fs/proc/proc_sysctl.c:proc_sys_permission
  - fs/proc/proc_sysctl.c:proc_sys_getattr
  - fs/proc/proc_sysctl.c:proc_sys_lookup
  - fs/proc/proc_sysctl.c:proc_sys_readdir
  - fs/proc/proc_sysctl.c:proc_sys_readdir
  - fs/proc/proc_sysctl.c:proc_sys_call_handler
```
**Symbols:**

```
ffffffff812849b0-ffffffff812849f8: sysctl_head_grab (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
struct ctl_table_header *sysctl_head_grab(struct ctl_table_header *head);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/proc/proc_sysctl.c (ffffffff812b1a80)
Location: fs/proc/proc_sysctl.c:302
Inline: True
Direct callers:
  - fs/proc/proc_sysctl.c:proc_sys_getattr
  - fs/proc/proc_sysctl.c:proc_sys_permission
  - fs/proc/proc_sysctl.c:proc_sys_readdir
  - fs/proc/proc_sysctl.c:proc_sys_readdir
  - fs/proc/proc_sysctl.c:proc_sys_poll
  - fs/proc/proc_sysctl.c:proc_sys_open
  - fs/proc/proc_sysctl.c:proc_sys_call_handler
  - fs/proc/proc_sysctl.c:proc_sys_lookup
```
**Symbols:**

```
ffffffff812b1a80-ffffffff812b1ac9: sysctl_head_grab (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
struct ctl_table_header *sysctl_head_grab(struct ctl_table_header *head);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/proc/proc_sysctl.c (ffffffff812c7320)
Location: fs/proc/proc_sysctl.c:302
Inline: True
Direct callers:
  - fs/proc/proc_sysctl.c:proc_sys_getattr
  - fs/proc/proc_sysctl.c:proc_sys_permission
  - fs/proc/proc_sysctl.c:proc_sys_readdir
  - fs/proc/proc_sysctl.c:proc_sys_readdir
  - fs/proc/proc_sysctl.c:proc_sys_poll
  - fs/proc/proc_sysctl.c:proc_sys_open
  - fs/proc/proc_sysctl.c:proc_sys_call_handler
  - fs/proc/proc_sysctl.c:proc_sys_lookup
```
**Symbols:**

```
ffffffff812c7320-ffffffff812c7369: sysctl_head_grab (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
struct ctl_table_header *sysctl_head_grab(struct ctl_table_header *head);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/proc/proc_sysctl.c (ffffffff812d42f0)
Location: fs/proc/proc_sysctl.c:333
Inline: True
Direct callers:
  - fs/proc/proc_sysctl.c:proc_sys_getattr
  - fs/proc/proc_sysctl.c:proc_sys_permission
  - fs/proc/proc_sysctl.c:proc_sys_readdir
  - fs/proc/proc_sysctl.c:proc_sys_readdir
  - fs/proc/proc_sysctl.c:proc_sys_poll
  - fs/proc/proc_sysctl.c:proc_sys_open
  - fs/proc/proc_sysctl.c:proc_sys_call_handler
  - fs/proc/proc_sysctl.c:proc_sys_lookup
```
**Symbols:**

```
ffffffff812d42f0-ffffffff812d4339: sysctl_head_grab (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
struct ctl_table_header *sysctl_head_grab(struct ctl_table_header *head);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/proc/proc_sysctl.c (ffffffff812f8b20)
Location: fs/proc/proc_sysctl.c:334
Inline: True
Direct callers:
  - fs/proc/proc_sysctl.c:proc_sys_getattr
  - fs/proc/proc_sysctl.c:proc_sys_permission
  - fs/proc/proc_sysctl.c:proc_sys_readdir
  - fs/proc/proc_sysctl.c:proc_sys_readdir
  - fs/proc/proc_sysctl.c:proc_sys_poll
  - fs/proc/proc_sysctl.c:proc_sys_open
  - fs/proc/proc_sysctl.c:proc_sys_call_handler
  - fs/proc/proc_sysctl.c:proc_sys_lookup
```
**Symbols:**

```
ffffffff812f8b20-ffffffff812f8b69: sysctl_head_grab (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
struct ctl_table_header *sysctl_head_grab(struct ctl_table_header *head);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/proc/proc_sysctl.c (ffffffff81325ba0)
Location: fs/proc/proc_sysctl.c:334
Inline: True
Direct callers:
  - fs/proc/proc_sysctl.c:proc_sys_getattr
  - fs/proc/proc_sysctl.c:proc_sys_permission
  - fs/proc/proc_sysctl.c:proc_sys_readdir
  - fs/proc/proc_sysctl.c:proc_sys_readdir
  - fs/proc/proc_sysctl.c:proc_sys_poll
  - fs/proc/proc_sysctl.c:proc_sys_open
  - fs/proc/proc_sysctl.c:proc_sys_call_handler
  - fs/proc/proc_sysctl.c:proc_sys_lookup
```
**Symbols:**

```
ffffffff81325ba0-ffffffff81325be9: sysctl_head_grab (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
struct ctl_table_header *sysctl_head_grab(struct ctl_table_header *head);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/proc/proc_sysctl.c (ffffffff8133cd90)
Location: fs/proc/proc_sysctl.c:334
Inline: True
Direct callers:
  - fs/proc/proc_sysctl.c:proc_sys_getattr
  - fs/proc/proc_sysctl.c:proc_sys_permission
  - fs/proc/proc_sysctl.c:proc_sys_readdir
  - fs/proc/proc_sysctl.c:proc_sys_readdir
  - fs/proc/proc_sysctl.c:proc_sys_poll
  - fs/proc/proc_sysctl.c:proc_sys_open
  - fs/proc/proc_sysctl.c:proc_sys_call_handler
  - fs/proc/proc_sysctl.c:proc_sys_lookup
```
**Symbols:**

```
ffffffff8133cd90-ffffffff8133cdd9: sysctl_head_grab (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
struct ctl_table_header *sysctl_head_grab(struct ctl_table_header *head);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/proc/proc_sysctl.c (ffffffff81364fd0)
Location: fs/proc/proc_sysctl.c:339
Inline: True
Direct callers:
  - fs/proc/proc_sysctl.c:proc_sys_getattr
  - fs/proc/proc_sysctl.c:proc_sys_permission
  - fs/proc/proc_sysctl.c:proc_sys_readdir
  - fs/proc/proc_sysctl.c:proc_sys_readdir
  - fs/proc/proc_sysctl.c:proc_sys_poll
  - fs/proc/proc_sysctl.c:proc_sys_open
  - fs/proc/proc_sysctl.c:proc_sys_call_handler
  - fs/proc/proc_sysctl.c:proc_sys_lookup
```
**Symbols:**

```
ffffffff81364fd0-ffffffff8136501b: sysctl_head_grab (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
struct ctl_table_header *sysctl_head_grab(struct ctl_table_header *head);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/proc/proc_sysctl.c (ffffffff8137d260)
Location: fs/proc/proc_sysctl.c:339
Inline: True
Direct callers:
  - fs/proc/proc_sysctl.c:proc_sys_getattr
  - fs/proc/proc_sysctl.c:proc_sys_permission
  - fs/proc/proc_sysctl.c:proc_sys_readdir
  - fs/proc/proc_sysctl.c:proc_sys_readdir
  - fs/proc/proc_sysctl.c:proc_sys_poll
  - fs/proc/proc_sysctl.c:proc_sys_open
  - fs/proc/proc_sysctl.c:proc_sys_call_handler
  - fs/proc/proc_sysctl.c:proc_sys_lookup
```
**Symbols:**

```
ffffffff8137d260-ffffffff8137d2ab: sysctl_head_grab (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
struct ctl_table_header *sysctl_head_grab(struct ctl_table_header *head);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/proc/proc_sysctl.c (ffffffff813c7160)
Location: fs/proc/proc_sysctl.c:307
Inline: True
Direct callers:
  - fs/proc/proc_sysctl.c:proc_sys_getattr
  - fs/proc/proc_sysctl.c:proc_sys_permission
  - fs/proc/proc_sysctl.c:proc_sys_readdir
  - fs/proc/proc_sysctl.c:proc_sys_readdir
  - fs/proc/proc_sysctl.c:proc_sys_poll
  - fs/proc/proc_sysctl.c:proc_sys_open
  - fs/proc/proc_sysctl.c:proc_sys_lookup
```
**Symbols:**

```
ffffffff813c7160-ffffffff813c71ae: sysctl_head_grab (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
struct ctl_table_header *sysctl_head_grab(struct ctl_table_header *head);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/proc/proc_sysctl.c (ffffffff813d9130)
Location: fs/proc/proc_sysctl.c:308
Inline: True
Direct callers:
  - fs/proc/proc_sysctl.c:proc_sys_getattr
  - fs/proc/proc_sysctl.c:proc_sys_permission
  - fs/proc/proc_sysctl.c:proc_sys_readdir
  - fs/proc/proc_sysctl.c:proc_sys_readdir
  - fs/proc/proc_sysctl.c:proc_sys_poll
  - fs/proc/proc_sysctl.c:proc_sys_open
  - fs/proc/proc_sysctl.c:proc_sys_call_handler
  - fs/proc/proc_sysctl.c:proc_sys_lookup
```
**Symbols:**

```
ffffffff813d9130-ffffffff813d917e: sysctl_head_grab (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
struct ctl_table_header *sysctl_head_grab(struct ctl_table_header *head);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/proc/proc_sysctl.c (ffffffff813e01a0)
Location: fs/proc/proc_sysctl.c:303
Inline: True
Direct callers:
  - fs/proc/proc_sysctl.c:proc_sys_getattr
  - fs/proc/proc_sysctl.c:proc_sys_permission
  - fs/proc/proc_sysctl.c:proc_sys_readdir
  - fs/proc/proc_sysctl.c:proc_sys_readdir
  - fs/proc/proc_sysctl.c:proc_sys_poll
  - fs/proc/proc_sysctl.c:proc_sys_open
  - fs/proc/proc_sysctl.c:proc_sys_call_handler
  - fs/proc/proc_sysctl.c:proc_sys_lookup
```
**Symbols:**

```
ffffffff813e01a0-ffffffff813e01ee: sysctl_head_grab (STB_LOCAL)
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
In fs/proc/proc_sysctl.c (ffffffff81431d36)
Location: fs/proc/proc_sysctl.c:303
Inline: True
Inline callers:
  - fs/proc/proc_sysctl.c:proc_sys_getattr
  - fs/proc/proc_sysctl.c:proc_sys_permission
  - fs/proc/proc_sysctl.c:proc_sys_readdir
  - fs/proc/proc_sysctl.c:proc_sys_readdir
  - fs/proc/proc_sysctl.c:proc_sys_poll
  - fs/proc/proc_sysctl.c:proc_sys_open
  - fs/proc/proc_sysctl.c:proc_sys_call_handler
  - fs/proc/proc_sysctl.c:proc_sys_lookup
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
In fs/proc/proc_sysctl.c (ffffffff814ad0a4)
Location: fs/proc/proc_sysctl.c:328
Inline: True
Inline callers:
  - fs/proc/proc_sysctl.c:proc_sys_getattr
  - fs/proc/proc_sysctl.c:proc_sys_permission
  - fs/proc/proc_sysctl.c:proc_sys_readdir
  - fs/proc/proc_sysctl.c:proc_sys_readdir
  - fs/proc/proc_sysctl.c:proc_sys_poll
  - fs/proc/proc_sysctl.c:proc_sys_open
  - fs/proc/proc_sysctl.c:proc_sys_call_handler
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
In fs/proc/proc_sysctl.c (ffffffff815434f4)
Location: fs/proc/proc_sysctl.c:321
Inline: True
Inline callers:
  - fs/proc/proc_sysctl.c:proc_sys_getattr
  - fs/proc/proc_sysctl.c:proc_sys_permission
  - fs/proc/proc_sysctl.c:proc_sys_readdir
  - fs/proc/proc_sysctl.c:proc_sys_readdir
  - fs/proc/proc_sysctl.c:proc_sys_poll
  - fs/proc/proc_sysctl.c:proc_sys_open
  - fs/proc/proc_sysctl.c:proc_sys_call_handler
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
In fs/proc/proc_sysctl.c (ffffffff8157b950)
Location: fs/proc/proc_sysctl.c:315
Inline: True
Inline callers:
  - fs/proc/proc_sysctl.c:proc_sys_getattr
  - fs/proc/proc_sysctl.c:proc_sys_permission
  - fs/proc/proc_sysctl.c:proc_sys_readdir
  - fs/proc/proc_sysctl.c:proc_sys_readdir
  - fs/proc/proc_sysctl.c:proc_sys_poll
  - fs/proc/proc_sysctl.c:proc_sys_open
  - fs/proc/proc_sysctl.c:proc_sys_call_handler
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
In fs/proc/proc_sysctl.c (ffffffff815b4200)
Location: fs/proc/proc_sysctl.c:317
Inline: True
Inline callers:
  - fs/proc/proc_sysctl.c:proc_sys_getattr
  - fs/proc/proc_sysctl.c:proc_sys_permission
  - fs/proc/proc_sysctl.c:proc_sys_readdir
  - fs/proc/proc_sysctl.c:proc_sys_readdir
  - fs/proc/proc_sysctl.c:proc_sys_poll
  - fs/proc/proc_sysctl.c:proc_sys_open
  - fs/proc/proc_sysctl.c:proc_sys_call_handler
  - fs/proc/proc_sysctl.c:proc_sys_lookup
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
struct ctl_table_header *sysctl_head_grab(struct ctl_table_header *head);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/proc/proc_sysctl.c (ffff800010449e08)
Location: fs/proc/proc_sysctl.c:339
Inline: True
Direct callers:
  - fs/proc/proc_sysctl.c:proc_sys_getattr
  - fs/proc/proc_sysctl.c:proc_sys_permission
  - fs/proc/proc_sysctl.c:proc_sys_readdir
  - fs/proc/proc_sysctl.c:proc_sys_readdir
  - fs/proc/proc_sysctl.c:proc_sys_poll
  - fs/proc/proc_sysctl.c:proc_sys_open
  - fs/proc/proc_sysctl.c:proc_sys_call_handler
  - fs/proc/proc_sysctl.c:proc_sys_lookup
```
**Symbols:**

```
ffff800010449e08-ffff800010449eb0: sysctl_head_grab (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
struct ctl_table_header *sysctl_head_grab(struct ctl_table_header *head);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/proc/proc_sysctl.c (c060efb8)
Location: fs/proc/proc_sysctl.c:339
Inline: True
Direct callers:
  - fs/proc/proc_sysctl.c:proc_sys_getattr
  - fs/proc/proc_sysctl.c:proc_sys_permission
  - fs/proc/proc_sysctl.c:proc_sys_readdir
  - fs/proc/proc_sysctl.c:proc_sys_readdir
  - fs/proc/proc_sysctl.c:proc_sys_poll
  - fs/proc/proc_sysctl.c:proc_sys_open
  - fs/proc/proc_sysctl.c:proc_sys_call_handler
  - fs/proc/proc_sysctl.c:proc_sys_lookup
```
**Symbols:**

```
c060efb8-c060f024: sysctl_head_grab (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
struct ctl_table_header *sysctl_head_grab(struct ctl_table_header *head);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/proc/proc_sysctl.c (c000000000560250)
Location: fs/proc/proc_sysctl.c:339
Inline: False
Direct callers:
  - fs/proc/proc_sysctl.c:proc_sys_getattr
  - fs/proc/proc_sysctl.c:proc_sys_getattr
  - fs/proc/proc_sysctl.c:proc_sys_permission
  - fs/proc/proc_sysctl.c:proc_sys_readdir
  - fs/proc/proc_sysctl.c:proc_sys_readdir
  - fs/proc/proc_sysctl.c:proc_sys_poll
  - fs/proc/proc_sysctl.c:proc_sys_poll
  - fs/proc/proc_sysctl.c:proc_sys_open
  - fs/proc/proc_sysctl.c:proc_sys_call_handler
  - fs/proc/proc_sysctl.c:proc_sys_lookup
  - fs/proc/proc_sysctl.c:proc_sys_lookup
```
**Symbols:**

```
c000000000560250-c000000000560310: sysctl_head_grab (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
struct ctl_table_header *sysctl_head_grab(struct ctl_table_header *head);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/proc/proc_sysctl.c (ffffffe0002df63e)
Location: fs/proc/proc_sysctl.c:339
Inline: True
Direct callers:
  - fs/proc/proc_sysctl.c:proc_sys_getattr
  - fs/proc/proc_sysctl.c:proc_sys_getattr
  - fs/proc/proc_sysctl.c:proc_sys_permission
  - fs/proc/proc_sysctl.c:proc_sys_readdir
  - fs/proc/proc_sysctl.c:proc_sys_readdir
  - fs/proc/proc_sysctl.c:proc_sys_readdir
  - fs/proc/proc_sysctl.c:proc_sys_poll
  - fs/proc/proc_sysctl.c:proc_sys_poll
  - fs/proc/proc_sysctl.c:proc_sys_open
  - fs/proc/proc_sysctl.c:proc_sys_call_handler
  - fs/proc/proc_sysctl.c:proc_sys_lookup
  - fs/proc/proc_sysctl.c:proc_sys_lookup
```
**Symbols:**

```
ffffffe0002df63e-ffffffe0002df6c6: sysctl_head_grab (STB_LOCAL)
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
struct ctl_table_header *sysctl_head_grab(struct ctl_table_header *head);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/proc/proc_sysctl.c (ffffffff81375840)
Location: fs/proc/proc_sysctl.c:339
Inline: True
Direct callers:
  - fs/proc/proc_sysctl.c:proc_sys_getattr
  - fs/proc/proc_sysctl.c:proc_sys_permission
  - fs/proc/proc_sysctl.c:proc_sys_readdir
  - fs/proc/proc_sysctl.c:proc_sys_readdir
  - fs/proc/proc_sysctl.c:proc_sys_poll
  - fs/proc/proc_sysctl.c:proc_sys_open
  - fs/proc/proc_sysctl.c:proc_sys_call_handler
  - fs/proc/proc_sysctl.c:proc_sys_lookup
```
**Symbols:**

```
ffffffff81375840-ffffffff8137588b: sysctl_head_grab (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
struct ctl_table_header *sysctl_head_grab(struct ctl_table_header *head);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/proc/proc_sysctl.c (ffffffff81366310)
Location: fs/proc/proc_sysctl.c:339
Inline: True
Direct callers:
  - fs/proc/proc_sysctl.c:proc_sys_getattr
  - fs/proc/proc_sysctl.c:proc_sys_permission
  - fs/proc/proc_sysctl.c:proc_sys_readdir
  - fs/proc/proc_sysctl.c:proc_sys_readdir
  - fs/proc/proc_sysctl.c:proc_sys_poll
  - fs/proc/proc_sysctl.c:proc_sys_open
  - fs/proc/proc_sysctl.c:proc_sys_call_handler
  - fs/proc/proc_sysctl.c:proc_sys_lookup
```
**Symbols:**

```
ffffffff81366310-ffffffff8136635b: sysctl_head_grab (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
struct ctl_table_header *sysctl_head_grab(struct ctl_table_header *head);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/proc/proc_sysctl.c (ffffffff81373310)
Location: fs/proc/proc_sysctl.c:339
Inline: True
Direct callers:
  - fs/proc/proc_sysctl.c:proc_sys_getattr
  - fs/proc/proc_sysctl.c:proc_sys_permission
  - fs/proc/proc_sysctl.c:proc_sys_readdir
  - fs/proc/proc_sysctl.c:proc_sys_readdir
  - fs/proc/proc_sysctl.c:proc_sys_poll
  - fs/proc/proc_sysctl.c:proc_sys_open
  - fs/proc/proc_sysctl.c:proc_sys_call_handler
  - fs/proc/proc_sysctl.c:proc_sys_lookup
```
**Symbols:**

```
ffffffff81373310-ffffffff8137335b: sysctl_head_grab (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
struct ctl_table_header *sysctl_head_grab(struct ctl_table_header *head);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/proc/proc_sysctl.c (ffffffff81386ea0)
Location: fs/proc/proc_sysctl.c:339
Inline: True
Direct callers:
  - fs/proc/proc_sysctl.c:proc_sys_getattr
  - fs/proc/proc_sysctl.c:proc_sys_permission
  - fs/proc/proc_sysctl.c:proc_sys_readdir
  - fs/proc/proc_sysctl.c:proc_sys_readdir
  - fs/proc/proc_sysctl.c:proc_sys_poll
  - fs/proc/proc_sysctl.c:proc_sys_open
  - fs/proc/proc_sysctl.c:proc_sys_call_handler
  - fs/proc/proc_sysctl.c:proc_sys_lookup
```
**Symbols:**

```
ffffffff81386ea0-ffffffff81386eeb: sysctl_head_grab (STB_LOCAL)
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
