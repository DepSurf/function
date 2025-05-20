# Function: <code>proc_ns_fget</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
struct file *proc_ns_fget(int fd);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/nsfs.c (ffffffff81242500)
Location: fs/nsfs.c:122
Inline: False
Direct callers:
  - kernel/nsproxy.c:SyS_setns
  - net/core/net_namespace.c:get_net_ns_by_fd
```
**Symbols:**

```
ffffffff81242500-ffffffff81242538: proc_ns_fget (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
struct file *proc_ns_fget(int fd);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/nsfs.c (ffffffff8126a860)
Location: fs/nsfs.c:122
Inline: False
Direct callers:
  - kernel/nsproxy.c:SyS_setns
  - net/core/net_namespace.c:get_net_ns_by_fd
```
**Symbols:**

```
ffffffff8126a860-ffffffff8126a897: proc_ns_fget (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
struct file *proc_ns_fget(int fd);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/nsfs.c (ffffffff8127d970)
Location: fs/nsfs.c:193
Inline: False
Direct callers:
  - kernel/nsproxy.c:SyS_setns
  - net/core/net_namespace.c:get_net_ns_by_fd
```
**Symbols:**

```
ffffffff8127d970-ffffffff8127d9a7: proc_ns_fget (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
struct file *proc_ns_fget(int fd);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/nsfs.c (ffffffff8128b590)
Location: fs/nsfs.c:208
Inline: False
Direct callers:
  - kernel/nsproxy.c:SyS_setns
  - net/core/net_namespace.c:get_net_ns_by_fd
```
**Symbols:**

```
ffffffff8128b590-ffffffff8128b5c7: proc_ns_fget (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
struct file *proc_ns_fget(int fd);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/nsfs.c (ffffffff812ae110)
Location: fs/nsfs.c:209
Inline: False
Direct callers:
  - kernel/nsproxy.c:SyS_setns
  - net/core/net_namespace.c:get_net_ns_by_fd
```
**Symbols:**

```
ffffffff812ae110-ffffffff812ae147: proc_ns_fget (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
struct file *proc_ns_fget(int fd);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/nsfs.c (ffffffff812d5f30)
Location: fs/nsfs.c:233
Inline: False
Direct callers:
  - kernel/nsproxy.c:__ia32_sys_setns
  - kernel/nsproxy.c:__x64_sys_setns
  - net/core/net_namespace.c:get_net_ns_by_fd
```
**Symbols:**

```
ffffffff812d5f30-ffffffff812d5f69: proc_ns_fget (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
struct file *proc_ns_fget(int fd);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/nsfs.c (ffffffff812eb300)
Location: fs/nsfs.c:233
Inline: False
Direct callers:
  - kernel/nsproxy.c:__ia32_sys_setns
  - kernel/nsproxy.c:__x64_sys_setns
  - net/core/net_namespace.c:get_net_ns_by_fd
```
**Symbols:**

```
ffffffff812eb300-ffffffff812eb339: proc_ns_fget (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
struct file *proc_ns_fget(int fd);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/nsfs.c (ffffffff81309d60)
Location: fs/nsfs.c:230
Inline: False
Direct callers:
  - kernel/nsproxy.c:__ia32_sys_setns
  - kernel/nsproxy.c:__x64_sys_setns
  - net/core/net_namespace.c:get_net_ns_by_fd
```
**Symbols:**

```
ffffffff81309d60-ffffffff81309d99: proc_ns_fget (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
struct file *proc_ns_fget(int fd);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/nsfs.c (ffffffff8131cdd0)
Location: fs/nsfs.c:230
Inline: False
Direct callers:
  - kernel/nsproxy.c:__ia32_sys_setns
  - kernel/nsproxy.c:__x64_sys_setns
  - net/core/net_namespace.c:get_net_ns_by_fd
```
**Symbols:**

```
ffffffff8131cdd0-ffffffff8131ce09: proc_ns_fget (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
struct file *proc_ns_fget(int fd);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/nsfs.c (ffffffff81356af0)
Location: fs/nsfs.c:237
Inline: False
Direct callers:
  - net/core/net_namespace.c:get_net_ns_by_fd
```
**Symbols:**

```
ffffffff81356af0-ffffffff81356b29: proc_ns_fget (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
struct file *proc_ns_fget(int fd);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/nsfs.c (ffffffff813634a0)
Location: fs/nsfs.c:237
Inline: False
Direct callers:
  - net/core/net_namespace.c:get_net_ns_by_fd
```
**Symbols:**

```
ffffffff813634a0-ffffffff813634d9: proc_ns_fget (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
struct file *proc_ns_fget(int fd);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/nsfs.c (ffffffff81369f30)
Location: fs/nsfs.c:237
Inline: False
Direct callers:
  - net/core/net_namespace.c:get_net_ns_by_fd
```
**Symbols:**

```
ffffffff81369f30-ffffffff81369f69: proc_ns_fget (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
struct file *proc_ns_fget(int fd);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/nsfs.c (ffffffff813b8c20)
Location: fs/nsfs.c:237
Inline: False
Direct callers:
  - net/core/net_namespace.c:get_net_ns_by_fd
```
**Symbols:**

```
ffffffff813b8c20-ffffffff813b8c59: proc_ns_fget (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
struct file *proc_ns_fget(int fd);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/nsfs.c (ffffffff8143e590)
Location: fs/nsfs.c:237
Inline: False
Direct callers:
  - net/core/net_namespace.c:get_net_ns_by_fd
```
**Symbols:**

```
ffffffff8143e590-ffffffff8143e5db: proc_ns_fget (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
struct file *proc_ns_fget(int fd);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/nsfs.c (ffffffff814cd040)
Location: fs/nsfs.c:237
Inline: False
Direct callers:
  - net/core/net_namespace.c:get_net_ns_by_fd
```
**Symbols:**

```
ffffffff814cd040-ffffffff814cd08b: proc_ns_fget (STB_GLOBAL)
```
</details>
</li>
<li>
In <code>6.5</code>: Absent ⚠️
</li>
<li>
In <code>6.8</code>: Absent ⚠️
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: ✅</summary>

```c
struct file *proc_ns_fget(int fd);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/nsfs.c (ffff8000103d4be8)
Location: fs/nsfs.c:230
Inline: False
Direct callers:
  - kernel/nsproxy.c:__arm64_sys_setns
  - net/core/net_namespace.c:get_net_ns_by_fd
```
**Symbols:**

```
ffff8000103d4be8-ffff8000103d4c54: proc_ns_fget (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
struct file *proc_ns_fget(int fd);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/nsfs.c (c05aeaa8)
Location: fs/nsfs.c:230
Inline: False
Direct callers:
  - kernel/nsproxy.c:__se_sys_setns
  - net/core/net_namespace.c:get_net_ns_by_fd
```
**Symbols:**

```
c05aeaa8-c05aeaf0: proc_ns_fget (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
struct file *proc_ns_fget(int fd);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/nsfs.c (c0000000004d79b0)
Location: fs/nsfs.c:230
Inline: False
Direct callers:
  - kernel/nsproxy.c:__se_sys_setns
  - net/core/net_namespace.c:get_net_ns_by_fd
```
**Symbols:**

```
c0000000004d79b0-c0000000004d7a38: proc_ns_fget (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
struct file *proc_ns_fget(int fd);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/nsfs.c (ffffffe00028eea0)
Location: fs/nsfs.c:230
Inline: False
Direct callers:
  - kernel/nsproxy.c:__se_sys_setns
  - net/core/net_namespace.c:get_net_ns_by_fd
```
**Symbols:**

```
ffffffe00028eea0-ffffffe00028eef6: proc_ns_fget (STB_GLOBAL)
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
struct file *proc_ns_fget(int fd);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/nsfs.c (ffffffff813153b0)
Location: fs/nsfs.c:230
Inline: False
Direct callers:
  - kernel/nsproxy.c:__ia32_sys_setns
  - kernel/nsproxy.c:__x64_sys_setns
  - net/core/net_namespace.c:get_net_ns_by_fd
```
**Symbols:**

```
ffffffff813153b0-ffffffff813153e9: proc_ns_fget (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
struct file *proc_ns_fget(int fd);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/nsfs.c (ffffffff81305fa0)
Location: fs/nsfs.c:230
Inline: False
Direct callers:
  - kernel/nsproxy.c:__ia32_sys_setns
  - kernel/nsproxy.c:__x64_sys_setns
  - net/core/net_namespace.c:get_net_ns_by_fd
```
**Symbols:**

```
ffffffff81305fa0-ffffffff81305fd9: proc_ns_fget (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
struct file *proc_ns_fget(int fd);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/nsfs.c (ffffffff813131a0)
Location: fs/nsfs.c:230
Inline: False
Direct callers:
  - kernel/nsproxy.c:__ia32_sys_setns
  - kernel/nsproxy.c:__x64_sys_setns
  - net/core/net_namespace.c:get_net_ns_by_fd
```
**Symbols:**

```
ffffffff813131a0-ffffffff813131d9: proc_ns_fget (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
struct file *proc_ns_fget(int fd);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/nsfs.c (ffffffff813249f0)
Location: fs/nsfs.c:230
Inline: False
Direct callers:
  - kernel/nsproxy.c:__ia32_sys_setns
  - kernel/nsproxy.c:__x64_sys_setns
  - net/core/net_namespace.c:get_net_ns_by_fd
```
**Symbols:**

```
ffffffff813249f0-ffffffff81324a29: proc_ns_fget (STB_GLOBAL)
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
