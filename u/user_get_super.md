# Function: <code>user_get_super</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
struct super_block *user_get_super(dev_t dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/super.c (ffffffff812101a0)
Location: fs/super.c:711
Inline: False
Direct callers:
  - fs/statfs.c:vfs_ustat
```
**Symbols:**

```
ffffffff812101a0-ffffffff8121026e: user_get_super (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
struct super_block *user_get_super(dev_t dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/super.c (ffffffff81236c60)
Location: fs/super.c:725
Inline: False
Direct callers:
  - fs/statfs.c:vfs_ustat
```
**Symbols:**

```
ffffffff81236c60-ffffffff81236d39: user_get_super (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
struct super_block *user_get_super(dev_t dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/super.c (ffffffff81249910)
Location: fs/super.c:771
Inline: False
Direct callers:
  - fs/statfs.c:vfs_ustat
```
**Symbols:**

```
ffffffff81249910-ffffffff812499e9: user_get_super (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
struct super_block *user_get_super(dev_t dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/super.c (ffffffff81255240)
Location: fs/super.c:774
Inline: False
Direct callers:
  - fs/statfs.c:vfs_ustat
```
**Symbols:**

```
ffffffff81255240-ffffffff81255318: user_get_super (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
struct super_block *user_get_super(dev_t dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/super.c (ffffffff812773d0)
Location: fs/super.c:774
Inline: False
Direct callers:
  - fs/statfs.c:vfs_ustat
```
**Symbols:**

```
ffffffff812773d0-ffffffff812774a8: user_get_super (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
struct super_block *user_get_super(dev_t dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/super.c (ffffffff8129dda0)
Location: fs/super.c:806
Inline: False
Direct callers:
  - fs/statfs.c:vfs_ustat
```
**Symbols:**

```
ffffffff8129dda0-ffffffff8129de6b: user_get_super (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
struct super_block *user_get_super(dev_t dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/super.c (ffffffff812b2d60)
Location: fs/super.c:810
Inline: False
Direct callers:
  - fs/statfs.c:vfs_ustat
```
**Symbols:**

```
ffffffff812b2d60-ffffffff812b2e2b: user_get_super (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
struct super_block *user_get_super(dev_t dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/super.c (ffffffff812cfa00)
Location: fs/super.c:864
Inline: False
Direct callers:
  - fs/statfs.c:vfs_ustat
```
**Symbols:**

```
ffffffff812cfa00-ffffffff812cfacd: user_get_super (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
struct super_block *user_get_super(dev_t dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/super.c (ffffffff812e14a0)
Location: fs/super.c:870
Inline: False
Direct callers:
  - fs/statfs.c:vfs_ustat
```
**Symbols:**

```
ffffffff812e14a0-ffffffff812e155e: user_get_super (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
struct super_block *user_get_super(dev_t dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/super.c (ffffffff81318810)
Location: fs/super.c:870
Inline: False
Direct callers:
  - fs/statfs.c:__do_compat_sys_ustat
  - fs/statfs.c:__do_sys_ustat
```
**Symbols:**

```
ffffffff81318810-ffffffff813188dd: user_get_super (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
struct super_block *user_get_super(dev_t dev, bool excl);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/super.c (ffffffff81323d20)
Location: fs/super.c:811
Inline: False
Direct callers:
  - fs/statfs.c:__do_compat_sys_ustat
  - fs/statfs.c:__do_sys_ustat
  - fs/quota/quota.c:quotactl_block
```
**Symbols:**

```
ffffffff81323d20-ffffffff81323e1c: user_get_super (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
struct super_block *user_get_super(dev_t dev, bool excl);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/super.c (ffffffff81329de0)
Location: fs/super.c:812
Inline: False
Direct callers:
  - fs/statfs.c:__do_compat_sys_ustat
  - fs/statfs.c:__do_sys_ustat
  - fs/quota/quota.c:quotactl_block
```
**Symbols:**

```
ffffffff81329de0-ffffffff81329edc: user_get_super (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
struct super_block *user_get_super(dev_t dev, bool excl);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/super.c (ffffffff81377410)
Location: fs/super.c:812
Inline: False
Direct callers:
  - fs/statfs.c:__do_compat_sys_ustat
  - fs/statfs.c:__do_sys_ustat
  - fs/quota/quota.c:quotactl_block
```
**Symbols:**

```
ffffffff81377410-ffffffff8137750c: user_get_super (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
struct super_block *user_get_super(dev_t dev, bool excl);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/super.c (ffffffff813f6670)
Location: fs/super.c:811
Inline: False
Direct callers:
  - fs/statfs.c:__do_compat_sys_ustat
  - fs/statfs.c:__do_sys_ustat
  - fs/quota/quota.c:quotactl_block
```
**Symbols:**

```
ffffffff813f6670-ffffffff813f675f: user_get_super (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
struct super_block *user_get_super(dev_t dev, bool excl);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/super.c (ffffffff8147f780)
Location: fs/super.c:854
Inline: False
Direct callers:
  - fs/statfs.c:__do_compat_sys_ustat
  - fs/statfs.c:__do_sys_ustat
  - fs/quota/quota.c:quotactl_block
```
**Symbols:**

```
ffffffff8147f780-ffffffff8147f86f: user_get_super (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
struct super_block *user_get_super(dev_t dev, bool excl);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/super.c (ffffffff814b4460)
Location: fs/super.c:861
Inline: False
Direct callers:
  - fs/statfs.c:__do_compat_sys_ustat
  - fs/statfs.c:__do_sys_ustat
  - fs/quota/quota.c:quotactl_block
  - fs/quota/quota.c:quotactl_block
```
**Symbols:**

```
ffffffff814b4460-ffffffff814b454f: user_get_super (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
struct super_block *user_get_super(dev_t dev, bool excl);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/super.c (ffffffff814e6980)
Location: fs/super.c:976
Inline: False
Direct callers:
  - fs/statfs.c:__do_compat_sys_ustat
  - fs/statfs.c:__do_sys_ustat
  - fs/quota/quota.c:quotactl_block
  - fs/quota/quota.c:quotactl_block
```
**Symbols:**

```
ffffffff814e6980-ffffffff814e6a37: user_get_super (STB_GLOBAL)
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
struct super_block *user_get_super(dev_t dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/super.c (ffff8000103887b0)
Location: fs/super.c:870
Inline: False
Direct callers:
  - fs/statfs.c:vfs_ustat
```
**Symbols:**

```
ffff8000103887b0-ffff80001038894c: user_get_super (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
struct super_block *user_get_super(dev_t dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/super.c (c0570e78)
Location: fs/super.c:870
Inline: False
Direct callers:
  - fs/statfs.c:__do_sys_ustat
```
**Symbols:**

```
c0570e78-c0570f6c: user_get_super (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
struct super_block *user_get_super(dev_t dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/super.c (c00000000047f520)
Location: fs/super.c:870
Inline: False
Direct callers:
  - fs/statfs.c:vfs_ustat
```
**Symbols:**

```
c00000000047f520-c00000000047f6c8: user_get_super (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
struct super_block *user_get_super(dev_t dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/super.c (ffffffe00025ada2)
Location: fs/super.c:870
Inline: False
Direct callers:
  - fs/statfs.c:__do_sys_ustat
```
**Symbols:**

```
ffffffe00025ada2-ffffffe00025aef6: user_get_super (STB_GLOBAL)
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
struct super_block *user_get_super(dev_t dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/super.c (ffffffff812d9a80)
Location: fs/super.c:870
Inline: False
Direct callers:
  - fs/statfs.c:vfs_ustat
```
**Symbols:**

```
ffffffff812d9a80-ffffffff812d9b3e: user_get_super (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
struct super_block *user_get_super(dev_t dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/super.c (ffffffff812ca700)
Location: fs/super.c:870
Inline: False
Direct callers:
  - fs/statfs.c:vfs_ustat
```
**Symbols:**

```
ffffffff812ca700-ffffffff812ca7be: user_get_super (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
struct super_block *user_get_super(dev_t dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/super.c (ffffffff812d7890)
Location: fs/super.c:870
Inline: False
Direct callers:
  - fs/statfs.c:vfs_ustat
```
**Symbols:**

```
ffffffff812d7890-ffffffff812d794e: user_get_super (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
struct super_block *user_get_super(dev_t dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/super.c (ffffffff812e86d0)
Location: fs/super.c:870
Inline: False
Direct callers:
  - fs/statfs.c:vfs_ustat
```
**Symbols:**

```
ffffffff812e86d0-ffffffff812e8787: user_get_super (STB_GLOBAL)
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
<details>
<summary>Changed between <code>5.8</code> and <code>5.11</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>bool excl</code>
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
