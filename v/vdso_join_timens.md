# Function: <code>vdso_join_timens</code>

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
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int vdso_join_timens(struct task_struct *task, struct time_namespace *ns);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/entry/vdso/vma.c (ffffffff81005bf0)
Location: arch/x86/entry/vdso/vma.c:142
Inline: False
Direct callers:
  - kernel/time/namespace.c:timens_on_fork
  - kernel/time/namespace.c:timens_install
```
**Symbols:**

```
ffffffff81005bf0-ffffffff81005c81: vdso_join_timens (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int vdso_join_timens(struct task_struct *task, struct time_namespace *ns);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/entry/vdso/vma.c (ffffffff81004ba0)
Location: arch/x86/entry/vdso/vma.c:126
Inline: False
Direct callers:
  - kernel/time/namespace.c:timens_commit
```
**Symbols:**

```
ffffffff81004ba0-ffffffff81004c6a: vdso_join_timens (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int vdso_join_timens(struct task_struct *task, struct time_namespace *ns);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/entry/vdso/vma.c (ffffffff81004b90)
Location: arch/x86/entry/vdso/vma.c:126
Inline: False
Direct callers:
  - kernel/time/namespace.c:timens_commit
```
**Symbols:**

```
ffffffff81004b90-ffffffff81004c57: vdso_join_timens (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int vdso_join_timens(struct task_struct *task, struct time_namespace *ns);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/entry/vdso/vma.c (ffffffff810051c0)
Location: arch/x86/entry/vdso/vma.c:126
Inline: False
Direct callers:
  - kernel/time/namespace.c:timens_commit
```
**Symbols:**

```
ffffffff810051c0-ffffffff81005273: vdso_join_timens (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int vdso_join_timens(struct task_struct *task, struct time_namespace *ns);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/entry/vdso/vma.c (ffffffff81004220)
Location: arch/x86/entry/vdso/vma.c:126
Inline: False
Direct callers:
  - kernel/time/namespace.c:timens_commit
```
**Symbols:**

```
ffffffff81004220-ffffffff810042e0: vdso_join_timens (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int vdso_join_timens(struct task_struct *task, struct time_namespace *ns);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/entry/vdso/vma.c (ffffffff81004ad0)
Location: arch/x86/entry/vdso/vma.c:108
Inline: False
Direct callers:
  - kernel/time/namespace.c:timens_commit
```
**Symbols:**

```
ffffffff81004ad0-ffffffff81004bdb: vdso_join_timens (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int vdso_join_timens(struct task_struct *task, struct time_namespace *ns);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/entry/vdso/vma.c (ffffffff810042b0)
Location: arch/x86/entry/vdso/vma.c:111
Inline: False
Direct callers:
  - kernel/time/namespace.c:timens_commit
```
**Symbols:**

```
ffffffff810042b0-ffffffff810043b8: vdso_join_timens (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int vdso_join_timens(struct task_struct *task, struct time_namespace *ns);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/entry/vdso/vma.c (ffffffff81006bc0)
Location: arch/x86/entry/vdso/vma.c:111
Inline: False
Direct callers:
  - kernel/time/namespace.c:timens_commit
```
**Symbols:**

```
ffffffff81006bc0-ffffffff81006cc7: vdso_join_timens (STB_GLOBAL)
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
