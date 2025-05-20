# Function: <code>set_task_ioprio</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int set_task_ioprio(struct task_struct *task, int ioprio);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/ioprio.c (ffffffff813cdb90)
Location: block/ioprio.c:32
Inline: False
Direct callers:
  - fs/ext4/super.c:ext4_remount
  - fs/ext4/super.c:ext4_fill_super
  - block/ioprio.c:SyS_ioprio_set
  - block/ioprio.c:SyS_ioprio_set
  - block/ioprio.c:SyS_ioprio_set
```
**Symbols:**

```
ffffffff813cdb90-ffffffff813cdc26: set_task_ioprio (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int set_task_ioprio(struct task_struct *task, int ioprio);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/ioprio.c (ffffffff81411fc0)
Location: block/ioprio.c:32
Inline: False
Direct callers:
  - fs/ext4/super.c:ext4_remount
  - fs/ext4/super.c:ext4_fill_super
  - block/ioprio.c:SyS_ioprio_set
  - block/ioprio.c:SyS_ioprio_set
  - block/ioprio.c:SyS_ioprio_set
```
**Symbols:**

```
ffffffff81411fc0-ffffffff81412056: set_task_ioprio (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int set_task_ioprio(struct task_struct *task, int ioprio);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/ioprio.c (ffffffff8142d420)
Location: block/ioprio.c:32
Inline: False
Direct callers:
  - fs/ext4/super.c:ext4_remount
  - fs/ext4/super.c:ext4_fill_super
  - block/ioprio.c:SyS_ioprio_set
  - block/ioprio.c:SyS_ioprio_set
  - block/ioprio.c:SyS_ioprio_set
```
**Symbols:**

```
ffffffff8142d420-ffffffff8142d4b6: set_task_ioprio (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
int set_task_ioprio(struct task_struct *task, int ioprio);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/ioprio.c (ffffffff8143a700)
Location: block/ioprio.c:35
Inline: True
Direct callers:
  - fs/ext4/super.c:ext4_remount
  - fs/ext4/super.c:ext4_fill_super
  - block/ioprio.c:SyS_ioprio_set
  - block/ioprio.c:SyS_ioprio_set
  - block/ioprio.c:SyS_ioprio_set
```
**Symbols:**

```
ffffffff8143a700-ffffffff8143a798: set_task_ioprio (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
int set_task_ioprio(struct task_struct *task, int ioprio);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/ioprio.c (ffffffff81466720)
Location: block/ioprio.c:35
Inline: True
Direct callers:
  - fs/ext4/super.c:ext4_remount
  - fs/ext4/super.c:ext4_fill_super
  - block/ioprio.c:SyS_ioprio_set
  - block/ioprio.c:SyS_ioprio_set
  - block/ioprio.c:SyS_ioprio_set
```
**Symbols:**

```
ffffffff81466720-ffffffff814667b8: set_task_ioprio (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
int set_task_ioprio(struct task_struct *task, int ioprio);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/ioprio.c (ffffffff8149a070)
Location: block/ioprio.c:35
Inline: True
Direct callers:
  - fs/ext4/super.c:ext4_remount
  - fs/ext4/super.c:ext4_fill_super
  - block/ioprio.c:__ia32_sys_ioprio_set
  - block/ioprio.c:__ia32_sys_ioprio_set
  - block/ioprio.c:__ia32_sys_ioprio_set
  - block/ioprio.c:__x64_sys_ioprio_set
  - block/ioprio.c:__x64_sys_ioprio_set
  - block/ioprio.c:__x64_sys_ioprio_set
```
**Symbols:**

```
ffffffff8149a070-ffffffff8149a108: set_task_ioprio (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
int set_task_ioprio(struct task_struct *task, int ioprio);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/ioprio.c (ffffffff814b4380)
Location: block/ioprio.c:35
Inline: True
Direct callers:
  - fs/ext4/super.c:ext4_remount
  - fs/ext4/super.c:ext4_fill_super
  - block/ioprio.c:__ia32_sys_ioprio_set
  - block/ioprio.c:__ia32_sys_ioprio_set
  - block/ioprio.c:__ia32_sys_ioprio_set
  - block/ioprio.c:__x64_sys_ioprio_set
  - block/ioprio.c:__x64_sys_ioprio_set
  - block/ioprio.c:__x64_sys_ioprio_set
```
**Symbols:**

```
ffffffff814b4380-ffffffff814b4418: set_task_ioprio (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
int set_task_ioprio(struct task_struct *task, int ioprio);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/ioprio.c (ffffffff814e28a0)
Location: block/ioprio.c:36
Inline: True
Direct callers:
  - fs/ext4/super.c:ext4_remount
  - fs/ext4/super.c:ext4_fill_super
  - block/ioprio.c:__ia32_sys_ioprio_set
  - block/ioprio.c:__ia32_sys_ioprio_set
  - block/ioprio.c:__ia32_sys_ioprio_set
  - block/ioprio.c:__x64_sys_ioprio_set
  - block/ioprio.c:__x64_sys_ioprio_set
  - block/ioprio.c:__x64_sys_ioprio_set
```
**Symbols:**

```
ffffffff814e28a0-ffffffff814e2935: set_task_ioprio (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
int set_task_ioprio(struct task_struct *task, int ioprio);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/ioprio.c (ffffffff814fbc60)
Location: block/ioprio.c:36
Inline: True
Direct callers:
  - fs/ext4/super.c:ext4_remount
  - fs/ext4/super.c:ext4_fill_super
  - block/ioprio.c:__ia32_sys_ioprio_set
  - block/ioprio.c:__ia32_sys_ioprio_set
  - block/ioprio.c:__ia32_sys_ioprio_set
  - block/ioprio.c:__x64_sys_ioprio_set
  - block/ioprio.c:__x64_sys_ioprio_set
  - block/ioprio.c:__x64_sys_ioprio_set
```
**Symbols:**

```
ffffffff814fbc60-ffffffff814fbcf5: set_task_ioprio (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int set_task_ioprio(struct task_struct *task, int ioprio);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/ioprio.c (ffffffff8155b900)
Location: block/ioprio.c:36
Inline: False
Direct callers:
  - fs/ext4/super.c:ext4_remount
  - fs/ext4/super.c:ext4_fill_super
  - block/ioprio.c:__do_sys_ioprio_set
  - block/ioprio.c:__do_sys_ioprio_set
  - block/ioprio.c:__do_sys_ioprio_set
```
**Symbols:**

```
ffffffff8155b900-ffffffff8155b995: set_task_ioprio (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int set_task_ioprio(struct task_struct *task, int ioprio);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/ioprio.c (ffffffff81577a60)
Location: block/ioprio.c:36
Inline: False
Direct callers:
  - fs/ext4/super.c:ext4_remount
  - fs/ext4/super.c:ext4_fill_super
  - block/ioprio.c:__do_sys_ioprio_set
  - block/ioprio.c:__do_sys_ioprio_set
  - block/ioprio.c:__do_sys_ioprio_set
```
**Symbols:**

```
ffffffff81577a60-ffffffff81577aff: set_task_ioprio (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int set_task_ioprio(struct task_struct *task, int ioprio);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/ioprio.c (ffffffff8157f7a0)
Location: block/ioprio.c:36
Inline: False
Direct callers:
  - fs/ext4/super.c:ext4_remount
  - fs/ext4/super.c:ext4_fill_super
  - block/ioprio.c:__do_sys_ioprio_set
  - block/ioprio.c:__do_sys_ioprio_set
  - block/ioprio.c:__do_sys_ioprio_set
```
**Symbols:**

```
ffffffff8157f7a0-ffffffff8157f83f: set_task_ioprio (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int set_task_ioprio(struct task_struct *task, int ioprio);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/ioprio.c (ffffffff815e4a40)
Location: block/ioprio.c:36
Inline: False
Direct callers:
  - fs/ext4/super.c:ext4_remount
  - fs/ext4/super.c:ext4_fill_super
  - block/ioprio.c:__do_sys_ioprio_set
  - block/ioprio.c:__do_sys_ioprio_set
  - block/ioprio.c:__do_sys_ioprio_set
```
**Symbols:**

```
ffffffff815e4a40-ffffffff815e4adf: set_task_ioprio (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int set_task_ioprio(struct task_struct *task, int ioprio);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-ioc.c (ffffffff8167d750)
Location: block/blk-ioc.c:255
Inline: False
Direct callers:
  - fs/ext4/super.c:__ext4_remount
  - fs/ext4/super.c:__ext4_fill_super
  - block/ioprio.c:__do_sys_ioprio_set
  - block/ioprio.c:__do_sys_ioprio_set
  - block/ioprio.c:__do_sys_ioprio_set
```
**Symbols:**

```
ffffffff8167d750-ffffffff8167d892: set_task_ioprio (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int set_task_ioprio(struct task_struct *task, int ioprio);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-ioc.c (ffffffff8173a340)
Location: block/blk-ioc.c:255
Inline: False
Direct callers:
  - fs/ext4/super.c:__ext4_remount
  - fs/ext4/super.c:ext4_load_and_init_journal
  - block/ioprio.c:__do_sys_ioprio_set
  - block/ioprio.c:__do_sys_ioprio_set
  - block/ioprio.c:__do_sys_ioprio_set
```
**Symbols:**

```
ffffffff8173a340-ffffffff8173a482: set_task_ioprio (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int set_task_ioprio(struct task_struct *task, int ioprio);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-ioc.c (ffffffff81776a40)
Location: block/blk-ioc.c:251
Inline: False
Direct callers:
  - fs/ext4/super.c:__ext4_remount
  - fs/ext4/super.c:ext4_load_and_init_journal
  - block/ioprio.c:__do_sys_ioprio_set
  - block/ioprio.c:__do_sys_ioprio_set
  - block/ioprio.c:__do_sys_ioprio_set
```
**Symbols:**

```
ffffffff81776a40-ffffffff81776b82: set_task_ioprio (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int set_task_ioprio(struct task_struct *task, int ioprio);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-ioc.c (ffffffff817b8c70)
Location: block/blk-ioc.c:251
Inline: False
Direct callers:
  - fs/ext4/super.c:__ext4_remount
  - fs/ext4/super.c:ext4_load_and_init_journal
  - block/ioprio.c:__do_sys_ioprio_set
  - block/ioprio.c:__do_sys_ioprio_set
  - block/ioprio.c:__do_sys_ioprio_set
```
**Symbols:**

```
ffffffff817b8c70-ffffffff817b8db2: set_task_ioprio (STB_GLOBAL)
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
int set_task_ioprio(struct task_struct *task, int ioprio);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/ioprio.c (ffff8000105fdc70)
Location: block/ioprio.c:36
Inline: True
Direct callers:
  - fs/ext4/super.c:ext4_remount
  - fs/ext4/super.c:ext4_fill_super
  - block/ioprio.c:__arm64_sys_ioprio_set
  - block/ioprio.c:__arm64_sys_ioprio_set
  - block/ioprio.c:__arm64_sys_ioprio_set
```
**Symbols:**

```
ffff8000105fdc70-ffff8000105fdd28: set_task_ioprio (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
int set_task_ioprio(struct task_struct *task, int ioprio);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/ioprio.c (c07a8ba0)
Location: block/ioprio.c:36
Inline: True
Direct callers:
  - fs/ext4/super.c:ext4_remount
  - fs/ext4/super.c:ext4_fill_super
  - block/ioprio.c:__se_sys_ioprio_set
  - block/ioprio.c:__se_sys_ioprio_set
  - block/ioprio.c:__se_sys_ioprio_set
```
**Symbols:**

```
c07a8ba0-c07a8c4c: set_task_ioprio (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
int set_task_ioprio(struct task_struct *task, int ioprio);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/ioprio.c (c0000000007976f0)
Location: block/ioprio.c:36
Inline: True
Direct callers:
  - fs/ext4/super.c:ext4_remount
  - fs/ext4/super.c:ext4_fill_super
  - block/ioprio.c:__se_sys_ioprio_set
  - block/ioprio.c:__se_sys_ioprio_set
  - block/ioprio.c:__se_sys_ioprio_set
```
**Symbols:**

```
c0000000007976f0-c0000000007977e8: set_task_ioprio (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
int set_task_ioprio(struct task_struct *task, int ioprio);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/ioprio.c (ffffffe0004396b0)
Location: block/ioprio.c:36
Inline: True
Direct callers:
  - fs/ext4/super.c:ext4_remount
  - fs/ext4/super.c:ext4_fill_super
  - block/ioprio.c:__se_sys_ioprio_set
  - block/ioprio.c:__se_sys_ioprio_set
  - block/ioprio.c:__se_sys_ioprio_set
```
**Symbols:**

```
ffffffe0004396b0-ffffffe000439742: set_task_ioprio (STB_GLOBAL)
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
int set_task_ioprio(struct task_struct *task, int ioprio);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/ioprio.c (ffffffff814f4240)
Location: block/ioprio.c:36
Inline: True
Direct callers:
  - fs/ext4/super.c:ext4_remount
  - fs/ext4/super.c:ext4_fill_super
  - block/ioprio.c:__ia32_sys_ioprio_set
  - block/ioprio.c:__ia32_sys_ioprio_set
  - block/ioprio.c:__ia32_sys_ioprio_set
  - block/ioprio.c:__x64_sys_ioprio_set
  - block/ioprio.c:__x64_sys_ioprio_set
  - block/ioprio.c:__x64_sys_ioprio_set
```
**Symbols:**

```
ffffffff814f4240-ffffffff814f42d5: set_task_ioprio (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
int set_task_ioprio(struct task_struct *task, int ioprio);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/ioprio.c (ffffffff814e4750)
Location: block/ioprio.c:36
Inline: True
Direct callers:
  - fs/ext4/super.c:ext4_remount
  - fs/ext4/super.c:ext4_fill_super
  - block/ioprio.c:__ia32_sys_ioprio_set
  - block/ioprio.c:__ia32_sys_ioprio_set
  - block/ioprio.c:__ia32_sys_ioprio_set
  - block/ioprio.c:__x64_sys_ioprio_set
  - block/ioprio.c:__x64_sys_ioprio_set
  - block/ioprio.c:__x64_sys_ioprio_set
```
**Symbols:**

```
ffffffff814e4750-ffffffff814e47e5: set_task_ioprio (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
int set_task_ioprio(struct task_struct *task, int ioprio);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/ioprio.c (ffffffff814f02d0)
Location: block/ioprio.c:36
Inline: True
Direct callers:
  - fs/ext4/super.c:ext4_remount
  - fs/ext4/super.c:ext4_fill_super
  - block/ioprio.c:__ia32_sys_ioprio_set
  - block/ioprio.c:__ia32_sys_ioprio_set
  - block/ioprio.c:__ia32_sys_ioprio_set
  - block/ioprio.c:__x64_sys_ioprio_set
  - block/ioprio.c:__x64_sys_ioprio_set
  - block/ioprio.c:__x64_sys_ioprio_set
```
**Symbols:**

```
ffffffff814f02d0-ffffffff814f0365: set_task_ioprio (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
int set_task_ioprio(struct task_struct *task, int ioprio);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/ioprio.c (ffffffff81509360)
Location: block/ioprio.c:36
Inline: True
Direct callers:
  - fs/ext4/super.c:ext4_remount
  - fs/ext4/super.c:ext4_fill_super
  - block/ioprio.c:__ia32_sys_ioprio_set
  - block/ioprio.c:__ia32_sys_ioprio_set
  - block/ioprio.c:__ia32_sys_ioprio_set
  - block/ioprio.c:__x64_sys_ioprio_set
  - block/ioprio.c:__x64_sys_ioprio_set
  - block/ioprio.c:__x64_sys_ioprio_set
```
**Symbols:**

```
ffffffff81509360-ffffffff81509407: set_task_ioprio (STB_GLOBAL)
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
