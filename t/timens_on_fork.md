# Function: <code>timens_on_fork</code>

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
int timens_on_fork(struct nsproxy *nsproxy, struct task_struct *tsk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/namespace.c (ffffffff8115a240)
Location: kernel/time/namespace.c:312
Inline: False
Direct callers:
  - kernel/nsproxy.c:copy_namespaces
```
**Symbols:**

```
ffffffff8115a240-ffffffff8115a320: timens_on_fork (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void timens_on_fork(struct nsproxy *nsproxy, struct task_struct *tsk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/namespace.c (ffffffff811562c0)
Location: kernel/time/namespace.c:308
Inline: False
Direct callers:
  - kernel/nsproxy.c:copy_namespaces
```
**Symbols:**

```
ffffffff811562c0-ffffffff81156359: timens_on_fork (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void timens_on_fork(struct nsproxy *nsproxy, struct task_struct *tsk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/namespace.c (ffffffff811576c0)
Location: kernel/time/namespace.c:308
Inline: False
Direct callers:
  - kernel/nsproxy.c:copy_namespaces
```
**Symbols:**

```
ffffffff811576c0-ffffffff81157759: timens_on_fork (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void timens_on_fork(struct nsproxy *nsproxy, struct task_struct *tsk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/namespace.c (ffffffff8117c530)
Location: kernel/time/namespace.c:308
Inline: False
Direct callers:
  - kernel/nsproxy.c:copy_namespaces
```
**Symbols:**

```
ffffffff8117c530-ffffffff8117c5c9: timens_on_fork (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void timens_on_fork(struct nsproxy *nsproxy, struct task_struct *tsk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/namespace.c (ffffffff811b1cf0)
Location: kernel/time/namespace.c:308
Inline: False
Direct callers:
  - kernel/nsproxy.c:copy_namespaces
```
**Symbols:**

```
ffffffff811b1cf0-ffffffff811b1d95: timens_on_fork (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void timens_on_fork(struct nsproxy *nsproxy, struct task_struct *tsk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/namespace.c (ffffffff811f2b00)
Location: kernel/time/namespace.c:326
Inline: False
Direct callers:
  - kernel/nsproxy.c:exec_task_namespaces
  - kernel/nsproxy.c:copy_namespaces
```
**Symbols:**

```
ffffffff811f2b00-ffffffff811f2ba5: timens_on_fork (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void timens_on_fork(struct nsproxy *nsproxy, struct task_struct *tsk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/namespace.c (ffffffff81207280)
Location: kernel/time/namespace.c:326
Inline: False
Direct callers:
  - kernel/nsproxy.c:exec_task_namespaces
  - kernel/nsproxy.c:copy_namespaces
```
**Symbols:**

```
ffffffff81207280-ffffffff81207325: timens_on_fork (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void timens_on_fork(struct nsproxy *nsproxy, struct task_struct *tsk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/namespace.c (ffffffff8121e490)
Location: kernel/time/namespace.c:326
Inline: False
Direct callers:
  - kernel/nsproxy.c:exec_task_namespaces
  - kernel/nsproxy.c:copy_namespaces
```
**Symbols:**

```
ffffffff8121e490-ffffffff8121e535: timens_on_fork (STB_GLOBAL)
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
<details>
<summary>Changed between <code>5.8</code> and <code>5.11</code> ⚠️</summary>
<ul>
<li>
<b>Return type changed. </b>
<code>int</code> ➡️ <code>void</code>
</li>
</ul>
</details>
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
