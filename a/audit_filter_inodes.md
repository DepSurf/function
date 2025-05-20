# Function: <code>audit_filter_inodes</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void audit_filter_inodes(struct task_struct *tsk, struct audit_context *ctx);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/auditsc.c (ffffffff811280a0)
Location: kernel/auditsc.c:805
Inline: False
Direct callers:
  - kernel/auditsc.c:__audit_free
  - kernel/auditsc.c:__audit_syscall_exit
  - kernel/audit_watch.c:audit_update_watch
```
**Symbols:**

```
ffffffff811280a0-ffffffff811281b2: audit_filter_inodes (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void audit_filter_inodes(struct task_struct *tsk, struct audit_context *ctx);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/auditsc.c (ffffffff81130250)
Location: kernel/auditsc.c:810
Inline: False
Direct callers:
  - kernel/auditsc.c:__audit_syscall_exit
  - kernel/auditsc.c:__audit_free
  - kernel/audit_watch.c:audit_update_watch
```
**Symbols:**

```
ffffffff81130250-ffffffff8113036d: audit_filter_inodes (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void audit_filter_inodes(struct task_struct *tsk, struct audit_context *ctx);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/auditsc.c (ffffffff81139fc0)
Location: kernel/auditsc.c:815
Inline: False
Direct callers:
  - kernel/auditsc.c:__audit_syscall_exit
  - kernel/auditsc.c:__audit_free
  - kernel/audit_watch.c:audit_update_watch
```
**Symbols:**

```
ffffffff81139fc0-ffffffff8113a0dd: audit_filter_inodes (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
void audit_filter_inodes(struct task_struct *tsk, struct audit_context *ctx);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/auditsc.c (ffffffff8113b610)
Location: kernel/auditsc.c:816
Inline: True
Direct callers:
  - kernel/auditsc.c:__audit_syscall_exit
  - kernel/auditsc.c:__audit_free
  - kernel/audit_watch.c:audit_update_watch
```
**Symbols:**

```
ffffffff8113b610-ffffffff8113b71d: audit_filter_inodes (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
void audit_filter_inodes(struct task_struct *tsk, struct audit_context *ctx);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/auditsc.c (ffffffff81148370)
Location: kernel/auditsc.c:816
Inline: True
Direct callers:
  - kernel/auditsc.c:__audit_syscall_exit
  - kernel/auditsc.c:__audit_free
  - kernel/audit_watch.c:audit_update_watch
```
**Symbols:**

```
ffffffff81148370-ffffffff8114847d: audit_filter_inodes (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
void audit_filter_inodes(struct task_struct *tsk, struct audit_context *ctx);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/auditsc.c (ffffffff81156d40)
Location: kernel/auditsc.c:823
Inline: True
Direct callers:
  - kernel/auditsc.c:__audit_syscall_exit
  - kernel/auditsc.c:__audit_free
  - kernel/audit_watch.c:audit_update_watch
```
**Symbols:**

```
ffffffff81156d40-ffffffff81156e49: audit_filter_inodes (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
void audit_filter_inodes(struct task_struct *tsk, struct audit_context *ctx);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/auditsc.c (ffffffff81163d90)
Location: kernel/auditsc.c:817
Inline: True
Direct callers:
  - kernel/auditsc.c:__audit_syscall_exit
  - kernel/auditsc.c:__audit_free
  - kernel/audit_watch.c:audit_update_watch
```
**Symbols:**

```
ffffffff81163d90-ffffffff81163e99: audit_filter_inodes (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
void audit_filter_inodes(struct task_struct *tsk, struct audit_context *ctx);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/auditsc.c (ffffffff811709b0)
Location: kernel/auditsc.c:831
Inline: True
Direct callers:
  - kernel/auditsc.c:__audit_syscall_exit
  - kernel/auditsc.c:__audit_free
  - kernel/audit_watch.c:audit_update_watch
```
**Symbols:**

```
ffffffff811709b0-ffffffff81170aaf: audit_filter_inodes (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
void audit_filter_inodes(struct task_struct *tsk, struct audit_context *ctx);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/auditsc.c (ffffffff8117c830)
Location: kernel/auditsc.c:831
Inline: True
Direct callers:
  - kernel/auditsc.c:__audit_syscall_exit
  - kernel/auditsc.c:__audit_free
  - kernel/audit_watch.c:audit_update_watch
```
**Symbols:**

```
ffffffff8117c830-ffffffff8117c92f: audit_filter_inodes (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline, Transformation ⚠️</summary>

```c
void audit_filter_inodes(struct task_struct *tsk, struct audit_context *ctx);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/auditsc.c (ffffffff81190361)
Location: kernel/auditsc.c:843
Inline: True
Inline callers:
  - kernel/auditsc.c:__audit_syscall_exit
  - kernel/auditsc.c:__audit_free
Direct callers:
  - kernel/auditsc.c:__audit_syscall_exit
  - kernel/auditsc.c:__audit_free
  - kernel/audit_watch.c:audit_update_watch
```
**Symbols:**

```
ffffffff8118ec00-ffffffff8118ecf7: audit_filter_inodes.part.0 (STB_LOCAL)
ffffffff8118f500-ffffffff8118f52d: audit_filter_inodes (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline, Transformation ⚠️</summary>

```c
void audit_filter_inodes(struct task_struct *tsk, struct audit_context *ctx);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/auditsc.c (ffffffff8118d5e2)
Location: kernel/auditsc.c:859
Inline: True
Inline callers:
  - kernel/auditsc.c:__audit_syscall_exit
  - kernel/auditsc.c:__audit_free
Direct callers:
  - kernel/auditsc.c:__audit_syscall_exit
  - kernel/auditsc.c:__audit_free
  - kernel/audit_watch.c:audit_update_watch
```
**Symbols:**

```
ffffffff8118bfa0-ffffffff8118c09c: audit_filter_inodes.part.0 (STB_LOCAL)
ffffffff8118c770-ffffffff8118c79d: audit_filter_inodes (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
void audit_filter_inodes(struct task_struct *tsk, struct audit_context *ctx);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/auditsc.c (ffffffff8118d3c0)
Location: kernel/auditsc.c:858
Inline: True
Direct callers:
  - kernel/auditsc.c:__audit_syscall_exit
  - kernel/auditsc.c:__audit_free
  - kernel/audit_watch.c:audit_update_watch
```
**Symbols:**

```
ffffffff8118d3c0-ffffffff8118d4c9: audit_filter_inodes (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline, Transformation ⚠️</summary>

```c
void audit_filter_inodes(struct task_struct *tsk, struct audit_context *ctx);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/auditsc.c (ffffffff811b60a9)
Location: kernel/auditsc.c:864
Inline: True
Direct callers:
  - kernel/auditsc.c:__audit_syscall_exit
  - kernel/auditsc.c:__audit_free
  - kernel/audit_watch.c:audit_update_watch
```
**Symbols:**

```
ffffffff81cb360b-ffffffff81cb3634: audit_filter_inodes.cold (STB_LOCAL)
ffffffff811b6070-ffffffff811b61b0: audit_filter_inodes (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline, Transformation ⚠️</summary>

```c
void audit_filter_inodes(struct task_struct *tsk, struct audit_context *ctx);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/auditsc.c (ffffffff811e9f97)
Location: kernel/auditsc.c:898
Inline: True
Inline callers:
  - kernel/auditsc.c:__audit_syscall_exit
  - kernel/auditsc.c:__audit_uring_exit
  - kernel/auditsc.c:__audit_uring_exit
  - kernel/auditsc.c:__audit_free
  - kernel/auditsc.c:__audit_free
Direct callers:
  - kernel/auditsc.c:__audit_syscall_exit
  - kernel/auditsc.c:__audit_uring_exit
  - kernel/auditsc.c:__audit_uring_exit
  - kernel/auditsc.c:__audit_free
  - kernel/auditsc.c:__audit_free
  - kernel/audit_watch.c:audit_update_watch
```
**Symbols:**

```
ffffffff811e89c0-ffffffff811e8b1a: audit_filter_inodes.part.0 (STB_LOCAL)
ffffffff81e643cf-ffffffff81e643f8: audit_filter_inodes.part.0.cold (STB_LOCAL)
ffffffff811e9850-ffffffff811e9885: audit_filter_inodes (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
void audit_filter_inodes(struct task_struct *tsk, struct audit_context *ctx);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/auditsc.c (ffffffff8122f820)
Location: kernel/auditsc.c:901
Inline: True
Direct callers:
  - kernel/auditsc.c:__audit_syscall_exit
  - kernel/auditsc.c:__audit_uring_exit
  - kernel/auditsc.c:__audit_uring_exit
  - kernel/auditsc.c:__audit_free
  - kernel/auditsc.c:__audit_free
  - kernel/audit_watch.c:audit_update_watch
```
**Symbols:**

```
ffffffff8122f820-ffffffff8122f8c2: audit_filter_inodes (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
void audit_filter_inodes(struct task_struct *tsk, struct audit_context *ctx);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/auditsc.c (ffffffff81246310)
Location: kernel/auditsc.c:902
Inline: True
Direct callers:
  - kernel/auditsc.c:__audit_syscall_exit
  - kernel/auditsc.c:__audit_uring_exit
  - kernel/auditsc.c:__audit_uring_exit
  - kernel/auditsc.c:__audit_free
  - kernel/auditsc.c:__audit_free
  - kernel/audit_watch.c:audit_update_watch
```
**Symbols:**

```
ffffffff81246310-ffffffff812463b2: audit_filter_inodes (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
void audit_filter_inodes(struct task_struct *tsk, struct audit_context *ctx);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/auditsc.c (ffffffff812601a0)
Location: kernel/auditsc.c:900
Inline: True
Direct callers:
  - kernel/auditsc.c:__audit_syscall_exit
  - kernel/auditsc.c:__audit_uring_exit
  - kernel/auditsc.c:__audit_uring_exit
  - kernel/auditsc.c:__audit_free
  - kernel/auditsc.c:__audit_free
  - kernel/audit_watch.c:audit_update_watch
```
**Symbols:**

```
ffffffff812601a0-ffffffff81260242: audit_filter_inodes (STB_GLOBAL)
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
void audit_filter_inodes(struct task_struct *tsk, struct audit_context *ctx);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/auditsc.c (ffff8000101f16b0)
Location: kernel/auditsc.c:831
Inline: True
Direct callers:
  - kernel/auditsc.c:__audit_syscall_exit
  - kernel/auditsc.c:__audit_free
  - kernel/audit_watch.c:audit_update_watch
```
**Symbols:**

```
ffff8000101f16b0-ffff8000101f17d8: audit_filter_inodes (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
void audit_filter_inodes(struct task_struct *tsk, struct audit_context *ctx);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/auditsc.c (c0431b8c)
Location: kernel/auditsc.c:831
Inline: True
Direct callers:
  - kernel/auditsc.c:__audit_syscall_exit
  - kernel/auditsc.c:__audit_free
  - kernel/audit_watch.c:audit_update_watch
```
**Symbols:**

```
c0431b8c-c0431c94: audit_filter_inodes (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
void audit_filter_inodes(struct task_struct *tsk, struct audit_context *ctx);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/auditsc.c (c0000000002658a0)
Location: kernel/auditsc.c:831
Inline: True
Direct callers:
  - kernel/auditsc.c:__audit_syscall_exit
  - kernel/auditsc.c:__audit_free
  - kernel/audit_watch.c:audit_update_watch
```
**Symbols:**

```
c0000000002658a0-c000000000265a50: audit_filter_inodes (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
void audit_filter_inodes(struct task_struct *tsk, struct audit_context *ctx);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/auditsc.c (ffffffe000165082)
Location: kernel/auditsc.c:831
Inline: True
Direct callers:
  - kernel/auditsc.c:__audit_syscall_exit
  - kernel/auditsc.c:__audit_free
  - kernel/audit_watch.c:audit_update_watch
```
**Symbols:**

```
ffffffe000165082-ffffffe00016516c: audit_filter_inodes (STB_GLOBAL)
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
void audit_filter_inodes(struct task_struct *tsk, struct audit_context *ctx);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/auditsc.c (ffffffff81174e50)
Location: kernel/auditsc.c:831
Inline: True
Direct callers:
  - kernel/auditsc.c:__audit_syscall_exit
  - kernel/auditsc.c:__audit_free
  - kernel/audit_watch.c:audit_update_watch
```
**Symbols:**

```
ffffffff81174e50-ffffffff81174f4f: audit_filter_inodes (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
void audit_filter_inodes(struct task_struct *tsk, struct audit_context *ctx);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/auditsc.c (ffffffff81167ff0)
Location: kernel/auditsc.c:831
Inline: True
Direct callers:
  - kernel/auditsc.c:__audit_syscall_exit
  - kernel/auditsc.c:__audit_free
  - kernel/audit_watch.c:audit_update_watch
```
**Symbols:**

```
ffffffff81167ff0-ffffffff811680ef: audit_filter_inodes (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
void audit_filter_inodes(struct task_struct *tsk, struct audit_context *ctx);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/auditsc.c (ffffffff81172c20)
Location: kernel/auditsc.c:831
Inline: True
Direct callers:
  - kernel/auditsc.c:__audit_syscall_exit
  - kernel/auditsc.c:__audit_free
  - kernel/audit_watch.c:audit_update_watch
```
**Symbols:**

```
ffffffff81172c20-ffffffff81172d1f: audit_filter_inodes (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
void audit_filter_inodes(struct task_struct *tsk, struct audit_context *ctx);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/auditsc.c (ffffffff81180460)
Location: kernel/auditsc.c:831
Inline: True
Direct callers:
  - kernel/auditsc.c:__audit_syscall_exit
  - kernel/auditsc.c:__audit_free
  - kernel/audit_watch.c:audit_update_watch
```
**Symbols:**

```
ffffffff81180460-ffffffff81180576: audit_filter_inodes (STB_GLOBAL)
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
