# Function: <code>copy_fs_struct</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
struct fs_struct *copy_fs_struct(struct fs_struct *old);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fs_struct.c (ffffffff812416d0)
Location: fs/fs_struct.c:110
Inline: False
Direct callers:
  - kernel/fork.c:copy_process
  - kernel/fork.c:SyS_unshare
  - fs/fs_struct.c:unshare_fs_struct
```
**Symbols:**

```
ffffffff812416d0-ffffffff81241774: copy_fs_struct (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
struct fs_struct *copy_fs_struct(struct fs_struct *old);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fs_struct.c (ffffffff81269a10)
Location: fs/fs_struct.c:110
Inline: False
Direct callers:
  - kernel/fork.c:SyS_unshare
  - fs/fs_struct.c:unshare_fs_struct
```
**Symbols:**

```
ffffffff81269a10-ffffffff81269ab4: copy_fs_struct (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
struct fs_struct *copy_fs_struct(struct fs_struct *old);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fs_struct.c (ffffffff8127c9c0)
Location: fs/fs_struct.c:110
Inline: False
Direct callers:
  - kernel/fork.c:SyS_unshare
  - fs/fs_struct.c:unshare_fs_struct
```
**Symbols:**

```
ffffffff8127c9c0-ffffffff8127ca64: copy_fs_struct (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
struct fs_struct *copy_fs_struct(struct fs_struct *old);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fs_struct.c (ffffffff8128a070)
Location: fs/fs_struct.c:111
Inline: False
Direct callers:
  - kernel/fork.c:SyS_unshare
  - fs/fs_struct.c:unshare_fs_struct
```
**Symbols:**

```
ffffffff8128a070-ffffffff8128a112: copy_fs_struct (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
struct fs_struct *copy_fs_struct(struct fs_struct *old);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fs_struct.c (ffffffff812acbb0)
Location: fs/fs_struct.c:111
Inline: False
Direct callers:
  - kernel/fork.c:SyS_unshare
  - fs/fs_struct.c:unshare_fs_struct
```
**Symbols:**

```
ffffffff812acbb0-ffffffff812acc52: copy_fs_struct (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
struct fs_struct *copy_fs_struct(struct fs_struct *old);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fs_struct.c (ffffffff812d4790)
Location: fs/fs_struct.c:111
Inline: False
Direct callers:
  - kernel/fork.c:ksys_unshare
  - fs/fs_struct.c:unshare_fs_struct
```
**Symbols:**

```
ffffffff812d4790-ffffffff812d482e: copy_fs_struct (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
struct fs_struct *copy_fs_struct(struct fs_struct *old);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fs_struct.c (ffffffff812e9b60)
Location: fs/fs_struct.c:111
Inline: False
Direct callers:
  - kernel/fork.c:ksys_unshare
  - fs/fs_struct.c:unshare_fs_struct
```
**Symbols:**

```
ffffffff812e9b60-ffffffff812e9bfe: copy_fs_struct (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
struct fs_struct *copy_fs_struct(struct fs_struct *old);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fs_struct.c (ffffffff81308560)
Location: fs/fs_struct.c:112
Inline: False
Direct callers:
  - kernel/fork.c:ksys_unshare
  - kernel/fork.c:copy_process
  - fs/fs_struct.c:unshare_fs_struct
```
**Symbols:**

```
ffffffff81308560-ffffffff813085ff: copy_fs_struct (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
struct fs_struct *copy_fs_struct(struct fs_struct *old);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fs_struct.c (ffffffff8131b600)
Location: fs/fs_struct.c:112
Inline: False
Direct callers:
  - kernel/fork.c:ksys_unshare
  - kernel/fork.c:copy_process
  - fs/fs_struct.c:unshare_fs_struct
```
**Symbols:**

```
ffffffff8131b600-ffffffff8131b69f: copy_fs_struct (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
struct fs_struct *copy_fs_struct(struct fs_struct *old);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fs_struct.c (ffffffff813552c0)
Location: fs/fs_struct.c:112
Inline: False
Direct callers:
  - kernel/fork.c:ksys_unshare
  - kernel/fork.c:copy_process
  - kernel/nsproxy.c:__do_sys_setns
  - fs/fs_struct.c:unshare_fs_struct
```
**Symbols:**

```
ffffffff813552c0-ffffffff8135535f: copy_fs_struct (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
struct fs_struct *copy_fs_struct(struct fs_struct *old);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fs_struct.c (ffffffff81361be0)
Location: fs/fs_struct.c:112
Inline: False
Direct callers:
  - kernel/fork.c:ksys_unshare
  - kernel/fork.c:copy_process
  - kernel/nsproxy.c:__do_sys_setns
  - fs/fs_struct.c:unshare_fs_struct
```
**Symbols:**

```
ffffffff81361be0-ffffffff81361c7f: copy_fs_struct (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
struct fs_struct *copy_fs_struct(struct fs_struct *old);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fs_struct.c (ffffffff813686c0)
Location: fs/fs_struct.c:112
Inline: False
Direct callers:
  - kernel/fork.c:ksys_unshare
  - kernel/fork.c:copy_process
  - kernel/nsproxy.c:__do_sys_setns
  - fs/fs_struct.c:unshare_fs_struct
```
**Symbols:**

```
ffffffff813686c0-ffffffff8136875f: copy_fs_struct (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
struct fs_struct *copy_fs_struct(struct fs_struct *old);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fs_struct.c (ffffffff813b73c0)
Location: fs/fs_struct.c:112
Inline: False
Direct callers:
  - kernel/fork.c:ksys_unshare
  - kernel/fork.c:copy_process
  - kernel/nsproxy.c:__do_sys_setns
  - fs/fs_struct.c:unshare_fs_struct
```
**Symbols:**

```
ffffffff813b73c0-ffffffff813b745f: copy_fs_struct (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
struct fs_struct *copy_fs_struct(struct fs_struct *old);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fs_struct.c (ffffffff8143ca70)
Location: fs/fs_struct.c:112
Inline: False
Direct callers:
  - kernel/fork.c:ksys_unshare
  - kernel/fork.c:copy_process
  - kernel/nsproxy.c:__do_sys_setns
  - fs/fs_struct.c:unshare_fs_struct
```
**Symbols:**

```
ffffffff8143ca70-ffffffff8143cb16: copy_fs_struct (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
struct fs_struct *copy_fs_struct(struct fs_struct *old);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fs_struct.c (ffffffff814cb1c0)
Location: fs/fs_struct.c:112
Inline: False
Direct callers:
  - kernel/fork.c:ksys_unshare
  - kernel/fork.c:copy_process
  - kernel/nsproxy.c:__do_sys_setns
  - fs/fs_struct.c:unshare_fs_struct
```
**Symbols:**

```
ffffffff814cb1c0-ffffffff814cb266: copy_fs_struct (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
struct fs_struct *copy_fs_struct(struct fs_struct *old);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fs_struct.c (ffffffff81501400)
Location: fs/fs_struct.c:112
Inline: False
Direct callers:
  - kernel/fork.c:ksys_unshare
  - kernel/fork.c:copy_process
  - kernel/nsproxy.c:__do_sys_setns
  - fs/fs_struct.c:unshare_fs_struct
```
**Symbols:**

```
ffffffff81501400-ffffffff815014a6: copy_fs_struct (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
struct fs_struct *copy_fs_struct(struct fs_struct *old);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fs_struct.c (ffffffff81536050)
Location: fs/fs_struct.c:112
Inline: False
Direct callers:
  - kernel/fork.c:ksys_unshare
  - kernel/fork.c:copy_process
  - kernel/nsproxy.c:__do_sys_setns
  - fs/fs_struct.c:unshare_fs_struct
```
**Symbols:**

```
ffffffff81536050-ffffffff815360f6: copy_fs_struct (STB_GLOBAL)
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
struct fs_struct *copy_fs_struct(struct fs_struct *old);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fs_struct.c (ffff8000103d2b98)
Location: fs/fs_struct.c:112
Inline: False
Direct callers:
  - kernel/fork.c:ksys_unshare
  - kernel/fork.c:copy_process
  - fs/fs_struct.c:unshare_fs_struct
```
**Symbols:**

```
ffff8000103d2b98-ffff8000103d2c64: copy_fs_struct (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
struct fs_struct *copy_fs_struct(struct fs_struct *old);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fs_struct.c (c05ad6cc)
Location: fs/fs_struct.c:112
Inline: False
Direct callers:
  - kernel/fork.c:ksys_unshare
  - kernel/fork.c:copy_process
  - fs/fs_struct.c:unshare_fs_struct
```
**Symbols:**

```
c05ad6cc-c05ad770: copy_fs_struct (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
struct fs_struct *copy_fs_struct(struct fs_struct *old);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fs_struct.c (c0000000004d5770)
Location: fs/fs_struct.c:112
Inline: False
Direct callers:
  - kernel/fork.c:ksys_unshare
  - kernel/fork.c:copy_process
  - fs/fs_struct.c:unshare_fs_struct
```
**Symbols:**

```
c0000000004d5770-c0000000004d587c: copy_fs_struct (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
struct fs_struct *copy_fs_struct(struct fs_struct *old);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fs_struct.c (ffffffe00028ddc0)
Location: fs/fs_struct.c:112
Inline: False
Direct callers:
  - kernel/fork.c:ksys_unshare
  - kernel/fork.c:copy_process
  - fs/fs_struct.c:unshare_fs_struct
```
**Symbols:**

```
ffffffe00028ddc0-ffffffe00028de92: copy_fs_struct (STB_GLOBAL)
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
struct fs_struct *copy_fs_struct(struct fs_struct *old);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fs_struct.c (ffffffff81313be0)
Location: fs/fs_struct.c:112
Inline: False
Direct callers:
  - kernel/fork.c:ksys_unshare
  - kernel/fork.c:copy_process
  - fs/fs_struct.c:unshare_fs_struct
```
**Symbols:**

```
ffffffff81313be0-ffffffff81313c7f: copy_fs_struct (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
struct fs_struct *copy_fs_struct(struct fs_struct *old);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fs_struct.c (ffffffff813047f0)
Location: fs/fs_struct.c:112
Inline: False
Direct callers:
  - kernel/fork.c:ksys_unshare
  - kernel/fork.c:copy_process
  - fs/fs_struct.c:unshare_fs_struct
```
**Symbols:**

```
ffffffff813047f0-ffffffff8130488f: copy_fs_struct (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
struct fs_struct *copy_fs_struct(struct fs_struct *old);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fs_struct.c (ffffffff813119d0)
Location: fs/fs_struct.c:112
Inline: False
Direct callers:
  - kernel/fork.c:ksys_unshare
  - kernel/fork.c:copy_process
  - fs/fs_struct.c:unshare_fs_struct
```
**Symbols:**

```
ffffffff813119d0-ffffffff81311a6f: copy_fs_struct (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
struct fs_struct *copy_fs_struct(struct fs_struct *old);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fs_struct.c (ffffffff81323210)
Location: fs/fs_struct.c:112
Inline: False
Direct callers:
  - kernel/fork.c:ksys_unshare
  - kernel/fork.c:copy_process
  - fs/fs_struct.c:unshare_fs_struct
```
**Symbols:**

```
ffffffff81323210-ffffffff813232ad: copy_fs_struct (STB_GLOBAL)
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
