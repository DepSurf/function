# Function: <code>proc_ns_file</code>

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
bool proc_ns_file(const struct file *file);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/nsfs.c (ffffffff81356ad0)
Location: fs/nsfs.c:232
Inline: False
Direct callers:
  - kernel/nsproxy.c:__do_sys_setns
  - kernel/nsproxy.c:__do_sys_setns
```
**Symbols:**

```
ffffffff81356ad0-ffffffff81356ae6: proc_ns_file (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
bool proc_ns_file(const struct file *file);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/nsfs.c (ffffffff81363480)
Location: fs/nsfs.c:232
Inline: False
Direct callers:
  - kernel/nsproxy.c:__do_sys_setns
  - kernel/nsproxy.c:__do_sys_setns
```
**Symbols:**

```
ffffffff81363480-ffffffff81363496: proc_ns_file (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
bool proc_ns_file(const struct file *file);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/nsfs.c (ffffffff81369f10)
Location: fs/nsfs.c:232
Inline: False
Direct callers:
  - kernel/nsproxy.c:__do_sys_setns
  - kernel/nsproxy.c:__do_sys_setns
```
**Symbols:**

```
ffffffff81369f10-ffffffff81369f26: proc_ns_file (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
bool proc_ns_file(const struct file *file);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/nsfs.c (ffffffff813b8c00)
Location: fs/nsfs.c:232
Inline: False
Direct callers:
  - kernel/nsproxy.c:__do_sys_setns
  - kernel/nsproxy.c:__do_sys_setns
```
**Symbols:**

```
ffffffff813b8c00-ffffffff813b8c16: proc_ns_file (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
bool proc_ns_file(const struct file *file);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/nsfs.c (ffffffff8143e570)
Location: fs/nsfs.c:232
Inline: False
Direct callers:
  - kernel/nsproxy.c:__do_sys_setns
  - kernel/nsproxy.c:__do_sys_setns
```
**Symbols:**

```
ffffffff8143e570-ffffffff8143e58c: proc_ns_file (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
bool proc_ns_file(const struct file *file);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/nsfs.c (ffffffff814cd010)
Location: fs/nsfs.c:232
Inline: False
Direct callers:
  - kernel/nsproxy.c:__do_sys_setns
  - kernel/nsproxy.c:__do_sys_setns
```
**Symbols:**

```
ffffffff814cd010-ffffffff814cd02c: proc_ns_file (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
bool proc_ns_file(const struct file *file);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/nsfs.c (ffffffff81503250)
Location: fs/nsfs.c:233
Inline: False
Direct callers:
  - kernel/nsproxy.c:__do_sys_setns
  - kernel/nsproxy.c:__do_sys_setns
  - net/core/net_namespace.c:get_net_ns_by_fd
```
**Symbols:**

```
ffffffff81503250-ffffffff8150326f: proc_ns_file (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
bool proc_ns_file(const struct file *file);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/nsfs.c (ffffffff81537e70)
Location: fs/nsfs.c:230
Inline: False
Direct callers:
  - kernel/nsproxy.c:__do_sys_setns
  - kernel/nsproxy.c:__do_sys_setns
  - net/core/net_namespace.c:get_net_ns_by_fd
```
**Symbols:**

```
ffffffff81537e70-ffffffff81537e8f: proc_ns_file (STB_GLOBAL)
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
