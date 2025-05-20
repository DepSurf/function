# Function: <code>ns_get_name</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int ns_get_name(char *buf, size_t size, struct task_struct *task, const struct proc_ns_operations *ns_ops);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/nsfs.c (ffffffff812424a0)
Location: fs/nsfs.c:109
Inline: False
Direct callers:
  - fs/proc/namespaces.c:proc_ns_readlink
```
**Symbols:**

```
ffffffff812424a0-ffffffff812424fd: ns_get_name (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int ns_get_name(char *buf, size_t size, struct task_struct *task, const struct proc_ns_operations *ns_ops);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/nsfs.c (ffffffff8126a800)
Location: fs/nsfs.c:109
Inline: False
Direct callers:
  - fs/proc/namespaces.c:proc_ns_readlink
```
**Symbols:**

```
ffffffff8126a800-ffffffff8126a85d: ns_get_name (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int ns_get_name(char *buf, size_t size, struct task_struct *task, const struct proc_ns_operations *ns_ops);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/nsfs.c (ffffffff8127d910)
Location: fs/nsfs.c:180
Inline: False
Direct callers:
  - fs/proc/namespaces.c:proc_ns_readlink
```
**Symbols:**

```
ffffffff8127d910-ffffffff8127d96d: ns_get_name (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Collision, Selective Inline ⚠️</summary>

```c
int ns_get_name(char *buf, size_t size, struct task_struct *task, const struct proc_ns_operations *ns_ops);
```

**Collision:** Static-Global Collision

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/nsfs.c (ffffffff8128b520)
Location: fs/nsfs.c:193
Inline: False
Direct callers:
  - fs/proc/namespaces.c:proc_ns_readlink
```
```
In security/apparmor/apparmorfs.c (ffffffff813d9eeb)
Location: security/apparmor/apparmorfs.c:2404
Inline: True
Inline callers:
  - security/apparmor/apparmorfs.c:policy_readlink
```
**Symbols:**

```
ffffffff8128b520-ffffffff8128b589: ns_get_name (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Collision, Selective Inline ⚠️</summary>

```c
int ns_get_name(char *buf, size_t size, struct task_struct *task, const struct proc_ns_operations *ns_ops);
```

**Collision:** Static-Global Collision

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/nsfs.c (ffffffff812ae090)
Location: fs/nsfs.c:194
Inline: False
Direct callers:
  - fs/proc/namespaces.c:proc_ns_readlink
```
```
In security/apparmor/apparmorfs.c (ffffffff81400dbe)
Location: security/apparmor/apparmorfs.c:2468
Inline: True
Inline callers:
  - security/apparmor/apparmorfs.c:policy_readlink
```
**Symbols:**

```
ffffffff812ae090-ffffffff812ae105: ns_get_name (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int ns_get_name(char *buf, size_t size, struct task_struct *task, const struct proc_ns_operations *ns_ops);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/nsfs.c (ffffffff812d5eb0)
Location: fs/nsfs.c:218
Inline: False
Direct callers:
  - fs/proc/namespaces.c:proc_ns_readlink
```
**Symbols:**

```
ffffffff812d5eb0-ffffffff812d5f25: ns_get_name (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int ns_get_name(char *buf, size_t size, struct task_struct *task, const struct proc_ns_operations *ns_ops);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/nsfs.c (ffffffff812eb280)
Location: fs/nsfs.c:218
Inline: False
Direct callers:
  - fs/proc/namespaces.c:proc_ns_readlink
```
**Symbols:**

```
ffffffff812eb280-ffffffff812eb2f5: ns_get_name (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int ns_get_name(char *buf, size_t size, struct task_struct *task, const struct proc_ns_operations *ns_ops);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/nsfs.c (ffffffff81309ce0)
Location: fs/nsfs.c:215
Inline: False
Direct callers:
  - fs/proc/namespaces.c:proc_ns_readlink
```
**Symbols:**

```
ffffffff81309ce0-ffffffff81309d55: ns_get_name (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int ns_get_name(char *buf, size_t size, struct task_struct *task, const struct proc_ns_operations *ns_ops);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/nsfs.c (ffffffff8131cd50)
Location: fs/nsfs.c:215
Inline: False
Direct callers:
  - fs/proc/namespaces.c:proc_ns_readlink
```
**Symbols:**

```
ffffffff8131cd50-ffffffff8131cdc5: ns_get_name (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int ns_get_name(char *buf, size_t size, struct task_struct *task, const struct proc_ns_operations *ns_ops);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/nsfs.c (ffffffff81356a50)
Location: fs/nsfs.c:217
Inline: False
Direct callers:
  - fs/proc/namespaces.c:proc_ns_readlink
```
**Symbols:**

```
ffffffff81356a50-ffffffff81356ac5: ns_get_name (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int ns_get_name(char *buf, size_t size, struct task_struct *task, const struct proc_ns_operations *ns_ops);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/nsfs.c (ffffffff81363400)
Location: fs/nsfs.c:217
Inline: False
Direct callers:
  - fs/proc/namespaces.c:proc_ns_readlink
```
**Symbols:**

```
ffffffff81363400-ffffffff81363475: ns_get_name (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int ns_get_name(char *buf, size_t size, struct task_struct *task, const struct proc_ns_operations *ns_ops);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/nsfs.c (ffffffff81369e90)
Location: fs/nsfs.c:217
Inline: False
Direct callers:
  - fs/proc/namespaces.c:proc_ns_readlink
```
**Symbols:**

```
ffffffff81369e90-ffffffff81369f05: ns_get_name (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int ns_get_name(char *buf, size_t size, struct task_struct *task, const struct proc_ns_operations *ns_ops);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/nsfs.c (ffffffff813b8b80)
Location: fs/nsfs.c:217
Inline: False
Direct callers:
  - fs/proc/namespaces.c:proc_ns_readlink
```
**Symbols:**

```
ffffffff813b8b80-ffffffff813b8bf5: ns_get_name (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int ns_get_name(char *buf, size_t size, struct task_struct *task, const struct proc_ns_operations *ns_ops);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/nsfs.c (ffffffff8143e4e0)
Location: fs/nsfs.c:217
Inline: False
Direct callers:
  - fs/proc/namespaces.c:proc_ns_readlink
```
**Symbols:**

```
ffffffff8143e4e0-ffffffff8143e564: ns_get_name (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int ns_get_name(char *buf, size_t size, struct task_struct *task, const struct proc_ns_operations *ns_ops);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/nsfs.c (ffffffff814ccf70)
Location: fs/nsfs.c:217
Inline: False
Direct callers:
  - fs/proc/namespaces.c:proc_ns_readlink
```
**Symbols:**

```
ffffffff814ccf70-ffffffff814ccff4: ns_get_name (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int ns_get_name(char *buf, size_t size, struct task_struct *task, const struct proc_ns_operations *ns_ops);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/nsfs.c (ffffffff815031b0)
Location: fs/nsfs.c:218
Inline: False
Direct callers:
  - fs/proc/namespaces.c:proc_ns_readlink
```
**Symbols:**

```
ffffffff815031b0-ffffffff81503234: ns_get_name (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int ns_get_name(char *buf, size_t size, struct task_struct *task, const struct proc_ns_operations *ns_ops);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/nsfs.c (ffffffff81537dd0)
Location: fs/nsfs.c:215
Inline: False
Direct callers:
  - fs/proc/namespaces.c:proc_ns_readlink
```
**Symbols:**

```
ffffffff81537dd0-ffffffff81537e54: ns_get_name (STB_GLOBAL)
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
int ns_get_name(char *buf, size_t size, struct task_struct *task, const struct proc_ns_operations *ns_ops);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/nsfs.c (ffff8000103d4b58)
Location: fs/nsfs.c:215
Inline: False
Direct callers:
  - fs/proc/namespaces.c:proc_ns_readlink
```
**Symbols:**

```
ffff8000103d4b58-ffff8000103d4be8: ns_get_name (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int ns_get_name(char *buf, size_t size, struct task_struct *task, const struct proc_ns_operations *ns_ops);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/nsfs.c (c05aea20)
Location: fs/nsfs.c:215
Inline: False
Direct callers:
  - fs/proc/namespaces.c:proc_ns_readlink
```
**Symbols:**

```
c05aea20-c05aeaa8: ns_get_name (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int ns_get_name(char *buf, size_t size, struct task_struct *task, const struct proc_ns_operations *ns_ops);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/nsfs.c (c0000000004d78e0)
Location: fs/nsfs.c:215
Inline: False
Direct callers:
  - fs/proc/namespaces.c:proc_ns_readlink
```
**Symbols:**

```
c0000000004d78e0-c0000000004d79b0: ns_get_name (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int ns_get_name(char *buf, size_t size, struct task_struct *task, const struct proc_ns_operations *ns_ops);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/nsfs.c (ffffffe00028ee34)
Location: fs/nsfs.c:215
Inline: False
Direct callers:
  - fs/proc/namespaces.c:proc_ns_readlink
```
**Symbols:**

```
ffffffe00028ee34-ffffffe00028eea0: ns_get_name (STB_GLOBAL)
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
int ns_get_name(char *buf, size_t size, struct task_struct *task, const struct proc_ns_operations *ns_ops);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/nsfs.c (ffffffff81315330)
Location: fs/nsfs.c:215
Inline: False
Direct callers:
  - fs/proc/namespaces.c:proc_ns_readlink
```
**Symbols:**

```
ffffffff81315330-ffffffff813153a5: ns_get_name (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int ns_get_name(char *buf, size_t size, struct task_struct *task, const struct proc_ns_operations *ns_ops);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/nsfs.c (ffffffff81305f20)
Location: fs/nsfs.c:215
Inline: False
Direct callers:
  - fs/proc/namespaces.c:proc_ns_readlink
```
**Symbols:**

```
ffffffff81305f20-ffffffff81305f95: ns_get_name (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int ns_get_name(char *buf, size_t size, struct task_struct *task, const struct proc_ns_operations *ns_ops);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/nsfs.c (ffffffff81313120)
Location: fs/nsfs.c:215
Inline: False
Direct callers:
  - fs/proc/namespaces.c:proc_ns_readlink
```
**Symbols:**

```
ffffffff81313120-ffffffff81313195: ns_get_name (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int ns_get_name(char *buf, size_t size, struct task_struct *task, const struct proc_ns_operations *ns_ops);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/nsfs.c (ffffffff81324970)
Location: fs/nsfs.c:215
Inline: False
Direct callers:
  - fs/proc/namespaces.c:proc_ns_readlink
```
**Symbols:**

```
ffffffff81324970-ffffffff813249e5: ns_get_name (STB_GLOBAL)
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
