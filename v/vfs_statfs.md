# Function: <code>vfs_statfs</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline ⚠️</summary>

```c
int vfs_statfs(struct path *path, struct kstatfs *buf);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/statfs.c (ffffffff81241a60)
Location: fs/statfs.c:66
Inline: True
Direct callers:
  - kernel/acct.c:check_free_space
  - fs/statfs.c:user_statfs
  - fs/statfs.c:fd_statfs
```
**Symbols:**

```
ffffffff81241a60-ffffffff81241afe: vfs_statfs (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
int vfs_statfs(struct path *path, struct kstatfs *buf);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/statfs.c (ffffffff81269da0)
Location: fs/statfs.c:66
Inline: True
Direct callers:
  - kernel/acct.c:check_free_space
  - fs/statfs.c:fd_statfs
  - fs/statfs.c:user_statfs
```
**Symbols:**

```
ffffffff81269da0-ffffffff81269e50: vfs_statfs (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
int vfs_statfs(const struct path *path, struct kstatfs *buf);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/statfs.c (ffffffff8127cd50)
Location: fs/statfs.c:66
Inline: True
Direct callers:
  - kernel/acct.c:check_free_space
  - fs/statfs.c:fd_statfs
  - fs/statfs.c:user_statfs
```
**Symbols:**

```
ffffffff8127cd50-ffffffff8127ce00: vfs_statfs (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
int vfs_statfs(const struct path *path, struct kstatfs *buf);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/statfs.c (ffffffff8128a620)
Location: fs/statfs.c:69
Inline: True
Direct callers:
  - kernel/acct.c:check_free_space
  - fs/statfs.c:fd_statfs
  - fs/statfs.c:user_statfs
```
**Symbols:**

```
ffffffff8128a620-ffffffff8128a6dc: vfs_statfs (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
int vfs_statfs(const struct path *path, struct kstatfs *buf);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/statfs.c (ffffffff812ad340)
Location: fs/statfs.c:70
Inline: True
Direct callers:
  - kernel/acct.c:check_free_space
  - fs/statfs.c:fd_statfs
  - fs/statfs.c:user_statfs
```
**Symbols:**

```
ffffffff812ad340-ffffffff812ad3fc: vfs_statfs (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
int vfs_statfs(const struct path *path, struct kstatfs *buf);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/statfs.c (ffffffff812d4f80)
Location: fs/statfs.c:70
Inline: True
Direct callers:
  - kernel/acct.c:check_free_space
  - fs/statfs.c:fd_statfs
  - fs/statfs.c:user_statfs
```
**Symbols:**

```
ffffffff812d4f80-ffffffff812d503a: vfs_statfs (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
int vfs_statfs(const struct path *path, struct kstatfs *buf);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/statfs.c (ffffffff812ea350)
Location: fs/statfs.c:70
Inline: True
Direct callers:
  - kernel/acct.c:check_free_space
  - fs/statfs.c:fd_statfs
  - fs/statfs.c:user_statfs
```
**Symbols:**

```
ffffffff812ea350-ffffffff812ea40a: vfs_statfs (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
int vfs_statfs(const struct path *path, struct kstatfs *buf);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/statfs.c (ffffffff81308db0)
Location: fs/statfs.c:84
Inline: True
Direct callers:
  - kernel/acct.c:check_free_space
  - fs/statfs.c:fd_statfs
  - fs/statfs.c:user_statfs
```
**Symbols:**

```
ffffffff81308db0-ffffffff81308e6b: vfs_statfs (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
int vfs_statfs(const struct path *path, struct kstatfs *buf);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/statfs.c (ffffffff8131be20)
Location: fs/statfs.c:84
Inline: True
Direct callers:
  - kernel/acct.c:check_free_space
  - fs/statfs.c:fd_statfs
  - fs/statfs.c:user_statfs
```
**Symbols:**

```
ffffffff8131be20-ffffffff8131bedb: vfs_statfs (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline, Transformation ⚠️</summary>

```c
int vfs_statfs(const struct path *path, struct kstatfs *buf);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/statfs.c (ffffffff81355ebb)
Location: fs/statfs.c:84
Inline: True
Inline callers:
  - fs/statfs.c:fd_statfs
  - fs/statfs.c:user_statfs
Direct callers:
  - kernel/acct.c:check_free_space
  - fs/statfs.c:fd_statfs
  - fs/statfs.c:user_statfs
```
**Symbols:**

```
ffffffff813559d0-ffffffff81355a5f: vfs_statfs.part.0.isra.0 (STB_LOCAL)
ffffffff81355a60-ffffffff81355a99: vfs_statfs (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline, Transformation ⚠️</summary>

```c
int vfs_statfs(const struct path *path, struct kstatfs *buf);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/statfs.c (ffffffff813627fb)
Location: fs/statfs.c:86
Inline: True
Inline callers:
  - fs/statfs.c:fd_statfs
  - fs/statfs.c:user_statfs
Direct callers:
  - kernel/acct.c:check_free_space
  - fs/statfs.c:fd_statfs
  - fs/statfs.c:user_statfs
```
**Symbols:**

```
ffffffff813622f0-ffffffff81362399: vfs_statfs.part.0.isra.0 (STB_LOCAL)
ffffffff813623a0-ffffffff813623d9: vfs_statfs (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline, Transformation ⚠️</summary>

```c
int vfs_statfs(const struct path *path, struct kstatfs *buf);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/statfs.c (ffffffff8136929b)
Location: fs/statfs.c:86
Inline: True
Inline callers:
  - fs/statfs.c:fd_statfs
  - fs/statfs.c:user_statfs
Direct callers:
  - kernel/acct.c:check_free_space
  - fs/statfs.c:fd_statfs
  - fs/statfs.c:user_statfs
```
**Symbols:**

```
ffffffff81368dd0-ffffffff81368e4c: vfs_statfs.part.0.isra.0 (STB_LOCAL)
ffffffff81368e50-ffffffff81368e89: vfs_statfs (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline, Transformation ⚠️</summary>

```c
int vfs_statfs(const struct path *path, struct kstatfs *buf);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/statfs.c (ffffffff813b7f9b)
Location: fs/statfs.c:86
Inline: True
Inline callers:
  - fs/statfs.c:fd_statfs
  - fs/statfs.c:user_statfs
Direct callers:
  - kernel/acct.c:check_free_space
  - fs/statfs.c:fd_statfs
  - fs/statfs.c:user_statfs
  - drivers/block/loop.c:loop_config_discard
```
**Symbols:**

```
ffffffff813b7ad0-ffffffff813b7b4c: vfs_statfs.part.0.isra.0 (STB_LOCAL)
ffffffff813b7b50-ffffffff813b7b89: vfs_statfs (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline, Transformation ⚠️</summary>

```c
int vfs_statfs(const struct path *path, struct kstatfs *buf);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/statfs.c (ffffffff8143d7df)
Location: fs/statfs.c:86
Inline: True
Inline callers:
  - fs/statfs.c:fd_statfs
  - fs/statfs.c:user_statfs
Direct callers:
  - kernel/acct.c:check_free_space
  - fs/statfs.c:fd_statfs
  - fs/statfs.c:user_statfs
```
**Symbols:**

```
ffffffff8143d220-ffffffff8143d2ad: vfs_statfs.part.0.isra.0 (STB_LOCAL)
ffffffff8143d2b0-ffffffff8143d2f0: vfs_statfs (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline, Transformation ⚠️</summary>

```c
int vfs_statfs(const struct path *path, struct kstatfs *buf);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/statfs.c (ffffffff814cc0af)
Location: fs/statfs.c:86
Inline: True
Inline callers:
  - fs/statfs.c:fd_statfs
  - fs/statfs.c:user_statfs
Direct callers:
  - kernel/acct.c:check_free_space
  - fs/statfs.c:fd_statfs
  - fs/statfs.c:user_statfs
```
**Symbols:**

```
ffffffff814cba10-ffffffff814cba9d: vfs_statfs.part.0.isra.0 (STB_LOCAL)
ffffffff814cbab0-ffffffff814cbaf0: vfs_statfs (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline, Transformation ⚠️</summary>

```c
int vfs_statfs(const struct path *path, struct kstatfs *buf);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/statfs.c (ffffffff815022f2)
Location: fs/statfs.c:86
Inline: True
Inline callers:
  - fs/statfs.c:fd_statfs
  - fs/statfs.c:user_statfs
Direct callers:
  - kernel/acct.c:check_free_space
  - fs/statfs.c:fd_statfs
  - fs/statfs.c:user_statfs
```
**Symbols:**

```
ffffffff81501c50-ffffffff81501cdb: vfs_statfs.part.0.isra.0 (STB_LOCAL)
ffffffff81501cf0-ffffffff81501d30: vfs_statfs (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline, Transformation ⚠️</summary>

```c
int vfs_statfs(const struct path *path, struct kstatfs *buf);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/statfs.c (ffffffff81536f42)
Location: fs/statfs.c:86
Inline: True
Inline callers:
  - fs/statfs.c:fd_statfs
  - fs/statfs.c:user_statfs
Direct callers:
  - kernel/acct.c:check_free_space
  - fs/statfs.c:fd_statfs
  - fs/statfs.c:user_statfs
```
**Symbols:**

```
ffffffff815368a0-ffffffff8153692b: vfs_statfs.part.0.isra.0 (STB_LOCAL)
ffffffff81536940-ffffffff81536980: vfs_statfs (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Selective Inline ⚠️</summary>

```c
int vfs_statfs(const struct path *path, struct kstatfs *buf);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/statfs.c (ffff8000103d3030)
Location: fs/statfs.c:84
Inline: True
Direct callers:
  - kernel/acct.c:check_free_space
  - fs/statfs.c:fd_statfs
  - fs/statfs.c:user_statfs
```
**Symbols:**

```
ffff8000103d3030-ffff8000103d30f8: vfs_statfs (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
int vfs_statfs(const struct path *path, struct kstatfs *buf);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/statfs.c (c05ada5c)
Location: fs/statfs.c:84
Inline: True
Direct callers:
  - kernel/acct.c:check_free_space
  - fs/statfs.c:fd_statfs
  - fs/statfs.c:user_statfs
```
**Symbols:**

```
c05ada5c-c05adaf0: vfs_statfs (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
int vfs_statfs(const struct path *path, struct kstatfs *buf);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/statfs.c (c0000000004d6140)
Location: fs/statfs.c:84
Inline: True
Direct callers:
  - kernel/acct.c:check_free_space
  - fs/statfs.c:fd_statfs
  - fs/statfs.c:user_statfs
```
**Symbols:**

```
c0000000004d6140-c0000000004d6270: vfs_statfs (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
int vfs_statfs(const struct path *path, struct kstatfs *buf);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/statfs.c (ffffffe00028e1ba)
Location: fs/statfs.c:84
Inline: True
Direct callers:
  - kernel/acct.c:check_free_space
  - fs/statfs.c:fd_statfs
  - fs/statfs.c:user_statfs
```
**Symbols:**

```
ffffffe00028e1ba-ffffffe00028e26a: vfs_statfs (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Selective Inline ⚠️</summary>

```c
int vfs_statfs(const struct path *path, struct kstatfs *buf);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/statfs.c (ffffffff81314400)
Location: fs/statfs.c:84
Inline: True
Direct callers:
  - kernel/acct.c:check_free_space
  - fs/statfs.c:fd_statfs
  - fs/statfs.c:user_statfs
```
**Symbols:**

```
ffffffff81314400-ffffffff813144bb: vfs_statfs (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
int vfs_statfs(const struct path *path, struct kstatfs *buf);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/statfs.c (ffffffff81305010)
Location: fs/statfs.c:84
Inline: True
Direct callers:
  - kernel/acct.c:check_free_space
  - fs/statfs.c:fd_statfs
  - fs/statfs.c:user_statfs
```
**Symbols:**

```
ffffffff81305010-ffffffff813050cb: vfs_statfs (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
int vfs_statfs(const struct path *path, struct kstatfs *buf);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/statfs.c (ffffffff813121f0)
Location: fs/statfs.c:84
Inline: True
Direct callers:
  - kernel/acct.c:check_free_space
  - fs/statfs.c:fd_statfs
  - fs/statfs.c:user_statfs
```
**Symbols:**

```
ffffffff813121f0-ffffffff813122ab: vfs_statfs (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
int vfs_statfs(const struct path *path, struct kstatfs *buf);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/statfs.c (ffffffff81323a30)
Location: fs/statfs.c:84
Inline: True
Direct callers:
  - kernel/acct.c:check_free_space
  - fs/statfs.c:fd_statfs
  - fs/statfs.c:user_statfs
```
**Symbols:**

```
ffffffff81323a30-ffffffff81323aeb: vfs_statfs (STB_GLOBAL)
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
<details>
<summary>Changed between <code>4.8</code> and <code>4.10</code> ⚠️</summary>
<ul>
<li>
<b>Param type changed. </b>
<code>struct path *path</code> ➡️ <code>const struct path *path</code>
</li>
</ul>
</details>
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
