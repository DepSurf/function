# Function: <code>audit_filter_syscall</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
enum audit_state audit_filter_syscall(struct task_struct *tsk, struct audit_context *ctx, struct list_head *list);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/auditsc.c (ffffffff81127b00)
Location: kernel/auditsc.c:748
Inline: False
Direct callers:
  - kernel/auditsc.c:__audit_free
  - kernel/auditsc.c:__audit_syscall_entry
  - kernel/auditsc.c:__audit_syscall_exit
```
**Symbols:**

```
ffffffff81127b00-ffffffff81127bde: audit_filter_syscall (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
enum audit_state audit_filter_syscall(struct task_struct *tsk, struct audit_context *ctx, struct list_head *list);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/auditsc.c (ffffffff8112fce0)
Location: kernel/auditsc.c:753
Inline: False
Direct callers:
  - kernel/auditsc.c:__audit_syscall_exit
  - kernel/auditsc.c:__audit_syscall_entry
  - kernel/auditsc.c:__audit_free
```
**Symbols:**

```
ffffffff8112fce0-ffffffff8112fdbe: audit_filter_syscall (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
enum audit_state audit_filter_syscall(struct task_struct *tsk, struct audit_context *ctx, struct list_head *list);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/auditsc.c (ffffffff81139a50)
Location: kernel/auditsc.c:758
Inline: False
Direct callers:
  - kernel/auditsc.c:__audit_syscall_exit
  - kernel/auditsc.c:__audit_syscall_entry
  - kernel/auditsc.c:__audit_free
```
**Symbols:**

```
ffffffff81139a50-ffffffff81139b2e: audit_filter_syscall (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
enum audit_state audit_filter_syscall(struct task_struct *tsk, struct audit_context *ctx, struct list_head *list);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/auditsc.c (ffffffff8113b0f0)
Location: kernel/auditsc.c:759
Inline: True
Direct callers:
  - kernel/auditsc.c:__audit_syscall_exit
  - kernel/auditsc.c:__audit_syscall_entry
  - kernel/auditsc.c:__audit_free
```
**Symbols:**

```
ffffffff8113b0f0-ffffffff8113b1c4: audit_filter_syscall (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
enum audit_state audit_filter_syscall(struct task_struct *tsk, struct audit_context *ctx, struct list_head *list);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/auditsc.c (ffffffff81147dd0)
Location: kernel/auditsc.c:759
Inline: True
Direct callers:
  - kernel/auditsc.c:__audit_syscall_exit
  - kernel/auditsc.c:__audit_syscall_entry
  - kernel/auditsc.c:__audit_free
```
**Symbols:**

```
ffffffff81147dd0-ffffffff81147ea4: audit_filter_syscall (STB_LOCAL)
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
In kernel/auditsc.c (ffffffff81156750)
Location: kernel/auditsc.c:766
Inline: True
Direct callers:
  - kernel/auditsc.c:__audit_syscall_exit
  - kernel/auditsc.c:__audit_free
```
**Symbols:**

```
ffffffff81156750-ffffffff81156839: audit_filter_syscall.constprop.15 (STB_LOCAL)
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
In kernel/auditsc.c (ffffffff81163ca0)
Location: kernel/auditsc.c:760
Inline: True
Direct callers:
  - kernel/auditsc.c:__audit_syscall_exit
  - kernel/auditsc.c:__audit_free
```
**Symbols:**

```
ffffffff81163ca0-ffffffff81163d8e: audit_filter_syscall.constprop.16 (STB_LOCAL)
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
In kernel/auditsc.c (ffffffff811708d0)
Location: kernel/auditsc.c:780
Inline: True
Direct callers:
  - kernel/auditsc.c:__audit_syscall_exit
  - kernel/auditsc.c:__audit_free
```
**Symbols:**

```
ffffffff811708d0-ffffffff811709a4: audit_filter_syscall.constprop.0 (STB_LOCAL)
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
In kernel/auditsc.c (ffffffff8117c750)
Location: kernel/auditsc.c:780
Inline: True
Direct callers:
  - kernel/auditsc.c:__audit_syscall_exit
  - kernel/auditsc.c:__audit_free
```
**Symbols:**

```
ffffffff8117c750-ffffffff8117c824: audit_filter_syscall.constprop.0 (STB_LOCAL)
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
In kernel/auditsc.c (ffffffff8118edd0)
Location: kernel/auditsc.c:792
Inline: True
Direct callers:
  - kernel/auditsc.c:__audit_syscall_exit
  - kernel/auditsc.c:__audit_free
```
**Symbols:**

```
ffffffff8118edd0-ffffffff8118ee99: audit_filter_syscall.constprop.0.isra.0 (STB_LOCAL)
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
In kernel/auditsc.c (ffffffff8118bdf0)
Location: kernel/auditsc.c:808
Inline: True
Direct callers:
  - kernel/auditsc.c:__audit_syscall_exit
  - kernel/auditsc.c:__audit_free
```
**Symbols:**

```
ffffffff8118bdf0-ffffffff8118bec3: audit_filter_syscall.constprop.0.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
void audit_filter_syscall(struct task_struct *tsk, struct audit_context *ctx);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/auditsc.c (ffffffff8118cca0)
Location: kernel/auditsc.c:808
Inline: True
Direct callers:
  - kernel/auditsc.c:__audit_syscall_exit
  - kernel/auditsc.c:__audit_free
```
**Symbols:**

```
ffffffff8118cca0-ffffffff8118cd73: audit_filter_syscall (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline, Transformation ⚠️</summary>

```c
void audit_filter_syscall(struct task_struct *tsk, struct audit_context *ctx);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/auditsc.c (ffffffff811b5938)
Location: kernel/auditsc.c:814
Inline: True
Direct callers:
  - kernel/auditsc.c:__audit_syscall_exit
  - kernel/auditsc.c:__audit_free
```
**Symbols:**

```
ffffffff811b5900-ffffffff811b5a03: audit_filter_syscall (STB_LOCAL)
ffffffff81cb35ab-ffffffff81cb35cc: audit_filter_syscall.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
void audit_filter_syscall(struct task_struct *tsk, struct audit_context *ctx);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/auditsc.c (0)
Location: kernel/auditsc.c:848
Inline: False
Direct callers:
  - kernel/auditsc.c:__audit_syscall_exit
  - kernel/auditsc.c:__audit_uring_exit
  - kernel/auditsc.c:__audit_free
```
**Symbols:**

```
ffffffff811e9340-ffffffff811e9468: audit_filter_syscall (STB_LOCAL)
ffffffff81e64413-ffffffff81e64434: audit_filter_syscall.cold (STB_LOCAL)
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
In kernel/auditsc.c (ffffffff812300f4)
Location: kernel/auditsc.c:871
Inline: True
Inline callers:
  - kernel/auditsc.c:__audit_syscall_exit
  - kernel/auditsc.c:__audit_syscall_exit
  - kernel/auditsc.c:__audit_uring_exit
  - kernel/auditsc.c:__audit_uring_exit
  - kernel/auditsc.c:__audit_free
  - kernel/auditsc.c:__audit_free
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
In kernel/auditsc.c (ffffffff81246be4)
Location: kernel/auditsc.c:872
Inline: True
Inline callers:
  - kernel/auditsc.c:__audit_syscall_exit
  - kernel/auditsc.c:__audit_syscall_exit
  - kernel/auditsc.c:__audit_uring_exit
  - kernel/auditsc.c:__audit_uring_exit
  - kernel/auditsc.c:__audit_free
  - kernel/auditsc.c:__audit_free
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
In kernel/auditsc.c (ffffffff81260a94)
Location: kernel/auditsc.c:869
Inline: True
Inline callers:
  - kernel/auditsc.c:__audit_syscall_exit
  - kernel/auditsc.c:__audit_syscall_exit
  - kernel/auditsc.c:__audit_uring_exit
  - kernel/auditsc.c:__audit_uring_exit
  - kernel/auditsc.c:__audit_free
  - kernel/auditsc.c:__audit_free
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
In kernel/auditsc.c (ffff8000101f15a0)
Location: kernel/auditsc.c:780
Inline: True
Direct callers:
  - kernel/auditsc.c:__audit_syscall_exit
  - kernel/auditsc.c:__audit_free
```
**Symbols:**

```
ffff8000101f15a0-ffff8000101f16ac: audit_filter_syscall.constprop.0 (STB_LOCAL)
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
In kernel/auditsc.c (c0431aa4)
Location: kernel/auditsc.c:780
Inline: True
Direct callers:
  - kernel/auditsc.c:__audit_syscall_exit
  - kernel/auditsc.c:__audit_free
```
**Symbols:**

```
c0431aa4-c0431b8c: audit_filter_syscall.constprop.0 (STB_LOCAL)
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
In kernel/auditsc.c (c000000000264eb0)
Location: kernel/auditsc.c:780
Inline: True
Direct callers:
  - kernel/auditsc.c:__audit_syscall_exit
  - kernel/auditsc.c:__audit_free
```
**Symbols:**

```
c000000000264eb0-c000000000265034: audit_filter_syscall.constprop.0 (STB_LOCAL)
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
In kernel/auditsc.c (ffffffe000164fbc)
Location: kernel/auditsc.c:780
Inline: True
Direct callers:
  - kernel/auditsc.c:__audit_syscall_exit
  - kernel/auditsc.c:__audit_free
```
**Symbols:**

```
ffffffe000164fbc-ffffffe000165082: audit_filter_syscall.constprop.0 (STB_LOCAL)
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
In kernel/auditsc.c (ffffffff81174d70)
Location: kernel/auditsc.c:780
Inline: True
Direct callers:
  - kernel/auditsc.c:__audit_syscall_exit
  - kernel/auditsc.c:__audit_free
```
**Symbols:**

```
ffffffff81174d70-ffffffff81174e44: audit_filter_syscall.constprop.0 (STB_LOCAL)
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
In kernel/auditsc.c (ffffffff81167f10)
Location: kernel/auditsc.c:780
Inline: True
Direct callers:
  - kernel/auditsc.c:__audit_syscall_exit
  - kernel/auditsc.c:__audit_free
```
**Symbols:**

```
ffffffff81167f10-ffffffff81167fe4: audit_filter_syscall.constprop.0 (STB_LOCAL)
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
In kernel/auditsc.c (ffffffff81172b40)
Location: kernel/auditsc.c:780
Inline: True
Direct callers:
  - kernel/auditsc.c:__audit_syscall_exit
  - kernel/auditsc.c:__audit_free
```
**Symbols:**

```
ffffffff81172b40-ffffffff81172c14: audit_filter_syscall.constprop.0 (STB_LOCAL)
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
In kernel/auditsc.c (ffffffff81180370)
Location: kernel/auditsc.c:780
Inline: True
Direct callers:
  - kernel/auditsc.c:__audit_syscall_exit
  - kernel/auditsc.c:__audit_free
```
**Symbols:**

```
ffffffff81180370-ffffffff8118045f: audit_filter_syscall.constprop.0 (STB_LOCAL)
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
No changes between <code>5.13</code> and <code>5.15</code> ✅
</li>
<li>
No changes between <code>5.15</code> and <code>5.19</code> ✅
</li>
</ul>
