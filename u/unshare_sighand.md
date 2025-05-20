# Function: <code>unshare_sighand</code>

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
int unshare_sighand(struct task_struct *me);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/exec.c (ffffffff8131db50)
Location: fs/exec.c:1277
Inline: False
Direct callers:
  - fs/exec.c:begin_new_exec
```
**Symbols:**

```
ffffffff8131db50-ffffffff8131dc04: unshare_sighand (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int unshare_sighand(struct task_struct *me);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/exec.c (ffffffff813289b0)
Location: fs/exec.c:1189
Inline: False
Direct callers:
  - fs/exec.c:begin_new_exec
```
**Symbols:**

```
ffffffff813289b0-ffffffff81328a64: unshare_sighand (STB_LOCAL)
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
In fs/exec.c (ffffffff8132fa5d)
Location: fs/exec.c:1181
Inline: True
Inline callers:
  - fs/exec.c:begin_new_exec
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
In fs/exec.c (ffffffff8137d21a)
Location: fs/exec.c:1181
Inline: True
Inline callers:
  - fs/exec.c:begin_new_exec
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
In fs/exec.c (ffffffff813fce0e)
Location: fs/exec.c:1188
Inline: True
Inline callers:
  - fs/exec.c:begin_new_exec
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int unshare_sighand(struct task_struct *me);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/exec.c (ffffffff81483de0)
Location: fs/exec.c:1183
Inline: False
Direct callers:
  - fs/exec.c:begin_new_exec
```
**Symbols:**

```
ffffffff81483de0-ffffffff81483e8f: unshare_sighand (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int unshare_sighand(struct task_struct *me);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/exec.c (ffffffff814b8620)
Location: fs/exec.c:1186
Inline: False
Direct callers:
  - fs/exec.c:begin_new_exec
```
**Symbols:**

```
ffffffff814b8620-ffffffff814b86cf: unshare_sighand (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int unshare_sighand(struct task_struct *me);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/exec.c (ffffffff814eab30)
Location: fs/exec.c:1201
Inline: False
Direct callers:
  - fs/exec.c:begin_new_exec
```
**Symbols:**

```
ffffffff814eab30-ffffffff814eabdf: unshare_sighand (STB_LOCAL)
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
No changes between <code>6.2</code> and <code>6.5</code> ✅
</li>
<li>
No changes between <code>6.5</code> and <code>6.8</code> ✅
</li>
</ul>
