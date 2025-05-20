# Function: <code>proc_flush_pid</code>

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
void proc_flush_pid(struct pid *pid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/proc/base.c (ffffffff813bfd50)
Location: fs/proc/base.c:3309
Inline: False
Direct callers:
  - kernel/exit.c:release_task
```
**Symbols:**

```
ffffffff813bfd50-ffffffff813bfd68: proc_flush_pid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void proc_flush_pid(struct pid *pid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/proc/base.c (ffffffff813d1be0)
Location: fs/proc/base.c:3326
Inline: False
Direct callers:
  - kernel/exit.c:release_task
```
**Symbols:**

```
ffffffff813d1be0-ffffffff813d1bf8: proc_flush_pid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void proc_flush_pid(struct pid *pid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/proc/base.c (ffffffff813d8ad0)
Location: fs/proc/base.c:3338
Inline: False
Direct callers:
  - kernel/exit.c:release_task
```
**Symbols:**

```
ffffffff813d8ad0-ffffffff813d8ae8: proc_flush_pid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void proc_flush_pid(struct pid *pid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/proc/base.c (ffffffff8142a200)
Location: fs/proc/base.c:3344
Inline: False
Direct callers:
  - kernel/exit.c:release_task
```
**Symbols:**

```
ffffffff8142a200-ffffffff8142a218: proc_flush_pid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void proc_flush_pid(struct pid *pid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/proc/base.c (ffffffff814a3710)
Location: fs/proc/base.c:3392
Inline: False
Direct callers:
  - kernel/exit.c:release_task
  - kernel/exit.c:release_task
```
**Symbols:**

```
ffffffff814a3710-ffffffff814a3730: proc_flush_pid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void proc_flush_pid(struct pid *pid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/proc/base.c (ffffffff81538a10)
Location: fs/proc/base.c:3408
Inline: False
Direct callers:
  - kernel/exit.c:release_task
  - kernel/exit.c:release_task
```
**Symbols:**

```
ffffffff81538a10-ffffffff81538a30: proc_flush_pid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void proc_flush_pid(struct pid *pid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/proc/base.c (ffffffff81570c50)
Location: fs/proc/base.c:3410
Inline: False
Direct callers:
  - kernel/exit.c:release_task
  - kernel/exit.c:release_task
```
**Symbols:**

```
ffffffff81570c50-ffffffff81570c70: proc_flush_pid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void proc_flush_pid(struct pid *pid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/proc/base.c (ffffffff815a95f0)
Location: fs/proc/base.c:3417
Inline: False
Direct callers:
  - kernel/exit.c:release_task
  - kernel/exit.c:release_task
```
**Symbols:**

```
ffffffff815a95f0-ffffffff815a9610: proc_flush_pid (STB_GLOBAL)
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
