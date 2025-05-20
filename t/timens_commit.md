# Function: <code>timens_commit</code>

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
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void timens_commit(struct task_struct *tsk, struct time_namespace *ns);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/namespace.c (ffffffff81156180)
Location: kernel/time/namespace.c:280
Inline: False
Direct callers:
  - kernel/nsproxy.c:__do_sys_setns
  - kernel/time/namespace.c:timens_on_fork
```
**Symbols:**

```
ffffffff81156180-ffffffff811562bf: timens_commit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void timens_commit(struct task_struct *tsk, struct time_namespace *ns);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/namespace.c (ffffffff81157580)
Location: kernel/time/namespace.c:280
Inline: False
Direct callers:
  - kernel/nsproxy.c:__do_sys_setns
  - kernel/time/namespace.c:timens_on_fork
```
**Symbols:**

```
ffffffff81157580-ffffffff811576bf: timens_commit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
void timens_commit(struct task_struct *tsk, struct time_namespace *ns);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/time/namespace.c (0)
Location: kernel/time/namespace.c:280
Inline: False
Direct callers:
  - kernel/nsproxy.c:__do_sys_setns
  - kernel/time/namespace.c:timens_on_fork
```
**Symbols:**

```
ffffffff81cb22d1-ffffffff81cb22f9: timens_commit.cold (STB_LOCAL)
ffffffff8117c3d0-ffffffff8117c526: timens_commit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
void timens_commit(struct task_struct *tsk, struct time_namespace *ns);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/time/namespace.c (0)
Location: kernel/time/namespace.c:280
Inline: False
Direct callers:
  - kernel/nsproxy.c:__do_sys_setns
  - kernel/time/namespace.c:timens_on_fork
```
**Symbols:**

```
ffffffff81e63852-ffffffff81e6387c: timens_commit.cold (STB_LOCAL)
ffffffff811b1b90-ffffffff811b1cf0: timens_commit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
void timens_commit(struct task_struct *tsk, struct time_namespace *ns);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/time/namespace.c (0)
Location: kernel/time/namespace.c:298
Inline: False
Direct callers:
  - kernel/nsproxy.c:__do_sys_setns
  - kernel/time/namespace.c:timens_on_fork
```
**Symbols:**

```
ffffffff8205bf12-ffffffff8205bf3c: timens_commit.cold (STB_LOCAL)
ffffffff811f2990-ffffffff811f2af0: timens_commit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
void timens_commit(struct task_struct *tsk, struct time_namespace *ns);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/time/namespace.c (0)
Location: kernel/time/namespace.c:298
Inline: False
Direct callers:
  - kernel/nsproxy.c:__do_sys_setns
  - kernel/time/namespace.c:timens_on_fork
```
**Symbols:**

```
ffffffff820da704-ffffffff820da72e: timens_commit.cold (STB_LOCAL)
ffffffff81207110-ffffffff81207270: timens_commit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
void timens_commit(struct task_struct *tsk, struct time_namespace *ns);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/time/namespace.c (0)
Location: kernel/time/namespace.c:298
Inline: False
Direct callers:
  - kernel/nsproxy.c:__do_sys_setns
  - kernel/time/namespace.c:timens_on_fork
```
**Symbols:**

```
ffffffff821b6274-ffffffff821b629e: timens_commit.cold (STB_LOCAL)
ffffffff8121e320-ffffffff8121e480: timens_commit (STB_GLOBAL)
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
