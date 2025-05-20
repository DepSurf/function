# Function: <code>ns_get_path</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void *ns_get_path(struct path *path, struct task_struct *task, const struct proc_ns_operations *ns_ops);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/nsfs.c (ffffffff812422e0)
Location: fs/nsfs.c:47
Inline: False
Direct callers:
  - fs/proc/namespaces.c:proc_ns_follow_link
```
**Symbols:**

```
ffffffff812422e0-ffffffff81242493: ns_get_path (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void *ns_get_path(struct path *path, struct task_struct *task, const struct proc_ns_operations *ns_ops);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/nsfs.c (ffffffff8126a640)
Location: fs/nsfs.c:47
Inline: False
Direct callers:
  - fs/proc/namespaces.c:proc_ns_get_link
```
**Symbols:**

```
ffffffff8126a640-ffffffff8126a7f3: ns_get_path (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void *ns_get_path(struct path *path, struct task_struct *task, const struct proc_ns_operations *ns_ops);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/nsfs.c (ffffffff8127d770)
Location: fs/nsfs.c:104
Inline: False
Direct callers:
  - fs/proc/namespaces.c:proc_ns_get_link
```
**Symbols:**

```
ffffffff8127d770-ffffffff8127d7bd: ns_get_path (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void *ns_get_path(struct path *path, struct task_struct *task, const struct proc_ns_operations *ns_ops);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/nsfs.c (ffffffff8128b2e0)
Location: fs/nsfs.c:105
Inline: False
Direct callers:
  - kernel/events/core.c:perf_fill_ns_link_info
  - fs/proc/namespaces.c:proc_ns_get_link
```
**Symbols:**

```
ffffffff8128b2e0-ffffffff8128b32b: ns_get_path (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void *ns_get_path(struct path *path, struct task_struct *task, const struct proc_ns_operations *ns_ops);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/nsfs.c (ffffffff812ade30)
Location: fs/nsfs.c:106
Inline: False
Direct callers:
  - kernel/events/core.c:perf_fill_ns_link_info
  - fs/proc/namespaces.c:proc_ns_get_link
```
**Symbols:**

```
ffffffff812ade30-ffffffff812ade81: ns_get_path (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void *ns_get_path(struct path *path, struct task_struct *task, const struct proc_ns_operations *ns_ops);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/nsfs.c (ffffffff812d5e60)
Location: fs/nsfs.c:135
Inline: False
Direct callers:
  - fs/proc/namespaces.c:proc_ns_get_link
```
**Symbols:**

```
ffffffff812d5e60-ffffffff812d5eaa: ns_get_path (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void *ns_get_path(struct path *path, struct task_struct *task, const struct proc_ns_operations *ns_ops);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/nsfs.c (ffffffff812eb230)
Location: fs/nsfs.c:135
Inline: False
Direct callers:
  - fs/proc/namespaces.c:proc_ns_get_link
```
**Symbols:**

```
ffffffff812eb230-ffffffff812eb27a: ns_get_path (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void *ns_get_path(struct path *path, struct task_struct *task, const struct proc_ns_operations *ns_ops);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/nsfs.c (ffffffff81309c90)
Location: fs/nsfs.c:134
Inline: False
Direct callers:
  - fs/proc/namespaces.c:proc_ns_get_link
```
**Symbols:**

```
ffffffff81309c90-ffffffff81309cda: ns_get_path (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void *ns_get_path(struct path *path, struct task_struct *task, const struct proc_ns_operations *ns_ops);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/nsfs.c (ffffffff8131cd00)
Location: fs/nsfs.c:134
Inline: False
Direct callers:
  - fs/proc/namespaces.c:proc_ns_get_link
```
**Symbols:**

```
ffffffff8131cd00-ffffffff8131cd4a: ns_get_path (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int ns_get_path(struct path *path, struct task_struct *task, const struct proc_ns_operations *ns_ops);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/nsfs.c (ffffffff81356a00)
Location: fs/nsfs.c:136
Inline: False
Direct callers:
  - kernel/events/core.c:perf_fill_ns_link_info
  - fs/proc/namespaces.c:proc_ns_get_link
```
**Symbols:**

```
ffffffff81356a00-ffffffff81356a46: ns_get_path (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int ns_get_path(struct path *path, struct task_struct *task, const struct proc_ns_operations *ns_ops);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/nsfs.c (ffffffff813633b0)
Location: fs/nsfs.c:136
Inline: False
Direct callers:
  - kernel/events/core.c:perf_fill_ns_link_info
  - fs/proc/namespaces.c:proc_ns_get_link
```
**Symbols:**

```
ffffffff813633b0-ffffffff813633f6: ns_get_path (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int ns_get_path(struct path *path, struct task_struct *task, const struct proc_ns_operations *ns_ops);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/nsfs.c (ffffffff81369e40)
Location: fs/nsfs.c:136
Inline: False
Direct callers:
  - kernel/events/core.c:perf_fill_ns_link_info
  - fs/proc/namespaces.c:proc_ns_get_link
```
**Symbols:**

```
ffffffff81369e40-ffffffff81369e86: ns_get_path (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int ns_get_path(struct path *path, struct task_struct *task, const struct proc_ns_operations *ns_ops);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/nsfs.c (ffffffff813b8b30)
Location: fs/nsfs.c:136
Inline: False
Direct callers:
  - kernel/events/core.c:perf_fill_ns_link_info
  - fs/proc/namespaces.c:proc_ns_get_link
```
**Symbols:**

```
ffffffff813b8b30-ffffffff813b8b76: ns_get_path (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int ns_get_path(struct path *path, struct task_struct *task, const struct proc_ns_operations *ns_ops);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/nsfs.c (ffffffff8143e490)
Location: fs/nsfs.c:136
Inline: False
Direct callers:
  - kernel/events/core.c:perf_fill_ns_link_info
  - fs/proc/namespaces.c:proc_ns_get_link
```
**Symbols:**

```
ffffffff8143e490-ffffffff8143e4e0: ns_get_path (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int ns_get_path(struct path *path, struct task_struct *task, const struct proc_ns_operations *ns_ops);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/nsfs.c (ffffffff814ccf10)
Location: fs/nsfs.c:136
Inline: False
Direct callers:
  - kernel/events/core.c:perf_fill_ns_link_info
  - fs/proc/namespaces.c:proc_ns_get_link
```
**Symbols:**

```
ffffffff814ccf10-ffffffff814ccf60: ns_get_path (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int ns_get_path(struct path *path, struct task_struct *task, const struct proc_ns_operations *ns_ops);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/nsfs.c (ffffffff81503150)
Location: fs/nsfs.c:137
Inline: False
Direct callers:
  - kernel/events/core.c:perf_fill_ns_link_info
  - fs/proc/namespaces.c:proc_ns_get_link
```
**Symbols:**

```
ffffffff81503150-ffffffff815031a0: ns_get_path (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int ns_get_path(struct path *path, struct task_struct *task, const struct proc_ns_operations *ns_ops);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/nsfs.c (ffffffff81537d70)
Location: fs/nsfs.c:134
Inline: False
Direct callers:
  - kernel/events/core.c:perf_fill_ns_link_info
  - fs/proc/namespaces.c:proc_ns_get_link
```
**Symbols:**

```
ffffffff81537d70-ffffffff81537dc0: ns_get_path (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: ✅</summary>

```c
void *ns_get_path(struct path *path, struct task_struct *task, const struct proc_ns_operations *ns_ops);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/nsfs.c (ffff8000103d4ae8)
Location: fs/nsfs.c:134
Inline: False
Direct callers:
  - fs/proc/namespaces.c:proc_ns_get_link
```
**Symbols:**

```
ffff8000103d4ae8-ffff8000103d4b58: ns_get_path (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void *ns_get_path(struct path *path, struct task_struct *task, const struct proc_ns_operations *ns_ops);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/nsfs.c (c05ae9b0)
Location: fs/nsfs.c:134
Inline: False
Direct callers:
  - kernel/events/core.c:perf_fill_ns_link_info
  - fs/proc/namespaces.c:proc_ns_get_link
```
**Symbols:**

```
c05ae9b0-c05aea20: ns_get_path (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void *ns_get_path(struct path *path, struct task_struct *task, const struct proc_ns_operations *ns_ops);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/nsfs.c (c0000000004d7860)
Location: fs/nsfs.c:134
Inline: False
Direct callers:
  - fs/proc/namespaces.c:proc_ns_get_link
```
**Symbols:**

```
c0000000004d7860-c0000000004d78d4: ns_get_path (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void *ns_get_path(struct path *path, struct task_struct *task, const struct proc_ns_operations *ns_ops);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/nsfs.c (ffffffe00028edea)
Location: fs/nsfs.c:134
Inline: False
Direct callers:
  - fs/proc/namespaces.c:proc_ns_get_link
```
**Symbols:**

```
ffffffe00028edea-ffffffe00028ee34: ns_get_path (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: ✅</summary>

```c
void *ns_get_path(struct path *path, struct task_struct *task, const struct proc_ns_operations *ns_ops);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/nsfs.c (ffffffff813152e0)
Location: fs/nsfs.c:134
Inline: False
Direct callers:
  - fs/proc/namespaces.c:proc_ns_get_link
```
**Symbols:**

```
ffffffff813152e0-ffffffff8131532a: ns_get_path (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void *ns_get_path(struct path *path, struct task_struct *task, const struct proc_ns_operations *ns_ops);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/nsfs.c (ffffffff81305ed0)
Location: fs/nsfs.c:134
Inline: False
Direct callers:
  - fs/proc/namespaces.c:proc_ns_get_link
```
**Symbols:**

```
ffffffff81305ed0-ffffffff81305f1a: ns_get_path (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void *ns_get_path(struct path *path, struct task_struct *task, const struct proc_ns_operations *ns_ops);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/nsfs.c (ffffffff813130d0)
Location: fs/nsfs.c:134
Inline: False
Direct callers:
  - fs/proc/namespaces.c:proc_ns_get_link
```
**Symbols:**

```
ffffffff813130d0-ffffffff8131311a: ns_get_path (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void *ns_get_path(struct path *path, struct task_struct *task, const struct proc_ns_operations *ns_ops);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/nsfs.c (ffffffff81324920)
Location: fs/nsfs.c:134
Inline: False
Direct callers:
  - fs/proc/namespaces.c:proc_ns_get_link
```
**Symbols:**

```
ffffffff81324920-ffffffff8132496a: ns_get_path (STB_GLOBAL)
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
<details>
<summary>Changed between <code>5.4</code> and <code>5.8</code> ⚠️</summary>
<ul>
<li>
<b>Return type changed. </b>
<code>void *</code> ➡️ <code>int</code>
</li>
</ul>
</details>
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
