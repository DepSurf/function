# Function: <code>vfs_ustat</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int vfs_ustat(dev_t dev, struct kstatfs *sbuf);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/statfs.c (ffffffff81241de0)
Location: fs/statfs.c:216
Inline: False
Direct callers:
  - fs/statfs.c:SYSC_ustat
  - fs/compat.c:C_SYSC_ustat
```
**Symbols:**

```
ffffffff81241de0-ffffffff81241e22: vfs_ustat (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int vfs_ustat(dev_t dev, struct kstatfs *sbuf);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/statfs.c (ffffffff8126a130)
Location: fs/statfs.c:216
Inline: False
Direct callers:
  - fs/statfs.c:SYSC_ustat
  - fs/compat.c:C_SYSC_ustat
```
**Symbols:**

```
ffffffff8126a130-ffffffff8126a173: vfs_ustat (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int vfs_ustat(dev_t dev, struct kstatfs *sbuf);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/statfs.c (ffffffff8127d0e0)
Location: fs/statfs.c:216
Inline: False
Direct callers:
  - fs/statfs.c:SYSC_ustat
  - fs/compat.c:C_SYSC_ustat
```
**Symbols:**

```
ffffffff8127d0e0-ffffffff8127d123: vfs_ustat (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int vfs_ustat(dev_t dev, struct kstatfs *sbuf);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/statfs.c (ffffffff8128ab60)
Location: fs/statfs.c:219
Inline: False
Direct callers:
  - fs/statfs.c:C_SYSC_ustat
  - fs/statfs.c:SYSC_ustat
```
**Symbols:**

```
ffffffff8128ab60-ffffffff8128aba3: vfs_ustat (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int vfs_ustat(dev_t dev, struct kstatfs *sbuf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/statfs.c (ffffffff812ad160)
Location: fs/statfs.c:220
Inline: False
Direct callers:
  - fs/statfs.c:C_SYSC_ustat
  - fs/statfs.c:SYSC_ustat
```
**Symbols:**

```
ffffffff812ad160-ffffffff812ad1a3: vfs_ustat (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int vfs_ustat(dev_t dev, struct kstatfs *sbuf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/statfs.c (ffffffff812d4d20)
Location: fs/statfs.c:220
Inline: False
Direct callers:
  - fs/statfs.c:__do_compat_sys_ustat
  - fs/statfs.c:__do_sys_ustat
```
**Symbols:**

```
ffffffff812d4d20-ffffffff812d4d63: vfs_ustat (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int vfs_ustat(dev_t dev, struct kstatfs *sbuf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/statfs.c (ffffffff812ea0f0)
Location: fs/statfs.c:220
Inline: False
Direct callers:
  - fs/statfs.c:__do_compat_sys_ustat
  - fs/statfs.c:__do_sys_ustat
```
**Symbols:**

```
ffffffff812ea0f0-ffffffff812ea133: vfs_ustat (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int vfs_ustat(dev_t dev, struct kstatfs *sbuf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/statfs.c (ffffffff81308b50)
Location: fs/statfs.c:234
Inline: False
Direct callers:
  - fs/statfs.c:__do_compat_sys_ustat
  - fs/statfs.c:__do_sys_ustat
```
**Symbols:**

```
ffffffff81308b50-ffffffff81308b95: vfs_ustat (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int vfs_ustat(dev_t dev, struct kstatfs *sbuf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/statfs.c (ffffffff8131bbc0)
Location: fs/statfs.c:234
Inline: False
Direct callers:
  - fs/statfs.c:__do_compat_sys_ustat
  - fs/statfs.c:__do_sys_ustat
```
**Symbols:**

```
ffffffff8131bbc0-ffffffff8131bc05: vfs_ustat (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/statfs.c (ffffffff813558dc)
Location: fs/statfs.c:234
Inline: True
Inline callers:
  - fs/statfs.c:__do_compat_sys_ustat
  - fs/statfs.c:__do_sys_ustat
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/statfs.c (ffffffff813621fe)
Location: fs/statfs.c:236
Inline: True
Inline callers:
  - fs/statfs.c:__do_compat_sys_ustat
  - fs/statfs.c:__do_sys_ustat
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
In fs/statfs.c (ffffffff81368ccf)
Location: fs/statfs.c:236
Inline: True
Inline callers:
  - fs/statfs.c:__do_compat_sys_ustat
  - fs/statfs.c:__do_sys_ustat
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
In fs/statfs.c (ffffffff813b79cf)
Location: fs/statfs.c:236
Inline: True
Inline callers:
  - fs/statfs.c:__do_compat_sys_ustat
  - fs/statfs.c:__do_sys_ustat
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
In fs/statfs.c (ffffffff8143d138)
Location: fs/statfs.c:236
Inline: True
Inline callers:
  - fs/statfs.c:__do_compat_sys_ustat
  - fs/statfs.c:__do_sys_ustat
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/statfs.c (ffffffff814cb908)
Location: fs/statfs.c:236
Inline: True
Inline callers:
  - fs/statfs.c:__do_compat_sys_ustat
  - fs/statfs.c:__do_sys_ustat
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/statfs.c (ffffffff81501b48)
Location: fs/statfs.c:236
Inline: True
Inline callers:
  - fs/statfs.c:__do_compat_sys_ustat
  - fs/statfs.c:__do_sys_ustat
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/statfs.c (ffffffff81536798)
Location: fs/statfs.c:236
Inline: True
Inline callers:
  - fs/statfs.c:__do_compat_sys_ustat
  - fs/statfs.c:__do_sys_ustat
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
int vfs_ustat(dev_t dev, struct kstatfs *sbuf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/statfs.c (ffff8000103d2fd0)
Location: fs/statfs.c:234
Inline: False
Direct callers:
  - fs/statfs.c:__do_compat_sys_ustat
  - fs/statfs.c:__do_sys_ustat
```
**Symbols:**

```
ffff8000103d2fd0-ffff8000103d302c: vfs_ustat (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/statfs.c (c05ad984)
Location: fs/statfs.c:234
Inline: True
Inline callers:
  - fs/statfs.c:__do_sys_ustat
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int vfs_ustat(dev_t dev, struct kstatfs *sbuf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/statfs.c (c0000000004d5ec0)
Location: fs/statfs.c:234
Inline: False
Direct callers:
  - fs/statfs.c:__do_compat_sys_ustat
  - fs/statfs.c:__do_sys_ustat
```
**Symbols:**

```
c0000000004d5ec0-c0000000004d5f3c: vfs_ustat (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/statfs.c (ffffffe00028e11a)
Location: fs/statfs.c:234
Inline: True
Inline callers:
  - fs/statfs.c:__do_sys_ustat
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
int vfs_ustat(dev_t dev, struct kstatfs *sbuf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/statfs.c (ffffffff813141a0)
Location: fs/statfs.c:234
Inline: False
Direct callers:
  - fs/statfs.c:__do_compat_sys_ustat
  - fs/statfs.c:__do_sys_ustat
```
**Symbols:**

```
ffffffff813141a0-ffffffff813141e5: vfs_ustat (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int vfs_ustat(dev_t dev, struct kstatfs *sbuf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/statfs.c (ffffffff81304db0)
Location: fs/statfs.c:234
Inline: False
Direct callers:
  - fs/statfs.c:__do_compat_sys_ustat
  - fs/statfs.c:__do_sys_ustat
```
**Symbols:**

```
ffffffff81304db0-ffffffff81304df5: vfs_ustat (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int vfs_ustat(dev_t dev, struct kstatfs *sbuf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/statfs.c (ffffffff81311f90)
Location: fs/statfs.c:234
Inline: False
Direct callers:
  - fs/statfs.c:__do_compat_sys_ustat
  - fs/statfs.c:__do_sys_ustat
```
**Symbols:**

```
ffffffff81311f90-ffffffff81311fd5: vfs_ustat (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int vfs_ustat(dev_t dev, struct kstatfs *sbuf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/statfs.c (ffffffff813237d0)
Location: fs/statfs.c:234
Inline: False
Direct callers:
  - fs/statfs.c:__do_compat_sys_ustat
  - fs/statfs.c:__do_sys_ustat
```
**Symbols:**

```
ffffffff813237d0-ffffffff81323815: vfs_ustat (STB_LOCAL)
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
</ul>
<b>Arch</b>
<ul>
<li>
No changes between <code>amd64</code> and <code>arm64</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>ppc64el</code> ✅
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
