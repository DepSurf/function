# Function: <code>debugfs_initialized</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
bool debugfs_initialized();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/debugfs/inode.c (ffffffff8131d100)
Location: fs/debugfs/inode.c:714
Inline: False
Direct callers:
  - mm/zswap.c:init_zswap
```
**Symbols:**

```
ffffffff8131d100-ffffffff8131d112: debugfs_initialized (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
bool debugfs_initialized();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/debugfs/inode.c (ffffffff81351c00)
Location: fs/debugfs/inode.c:775
Inline: False
Direct callers:
  - mm/zswap.c:init_zswap
```
**Symbols:**

```
ffffffff81351c00-ffffffff81351c12: debugfs_initialized (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
bool debugfs_initialized();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/debugfs/inode.c (ffffffff81367ec0)
Location: fs/debugfs/inode.c:775
Inline: False
Direct callers:
  - mm/zswap.c:init_zswap
```
**Symbols:**

```
ffffffff81367ec0-ffffffff81367ed2: debugfs_initialized (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
bool debugfs_initialized();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/debugfs/inode.c (ffffffff8137c4a0)
Location: fs/debugfs/inode.c:809
Inline: False
Direct callers:
  - mm/zswap.c:init_zswap
```
**Symbols:**

```
ffffffff8137c4a0-ffffffff8137c4b2: debugfs_initialized (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
bool debugfs_initialized();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/debugfs/inode.c (ffffffff813a1350)
Location: fs/debugfs/inode.c:833
Inline: False
Direct callers:
  - mm/zswap.c:init_zswap
```
**Symbols:**

```
ffffffff813a1350-ffffffff813a1362: debugfs_initialized (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
bool debugfs_initialized();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/debugfs/inode.c (ffffffff813d0730)
Location: fs/debugfs/inode.c:856
Inline: False
Direct callers:
  - mm/zswap.c:init_zswap
  - drivers/i2c/busses/i2c-amd-pci-mp2.c:amd_mp2_pci_driver_init
```
**Symbols:**

```
ffffffff813d0730-ffffffff813d0742: debugfs_initialized (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
bool debugfs_initialized();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/debugfs/inode.c (ffffffff813eadc0)
Location: fs/debugfs/inode.c:868
Inline: False
Direct callers:
  - mm/zswap.c:init_zswap
```
**Symbols:**

```
ffffffff813eadc0-ffffffff813eadd2: debugfs_initialized (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
bool debugfs_initialized();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/debugfs/inode.c (ffffffff81416ec0)
Location: fs/debugfs/inode.c:888
Inline: False
Direct callers:
  - mm/zswap.c:init_zswap
```
**Symbols:**

```
ffffffff81416ec0-ffffffff81416ed2: debugfs_initialized (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
bool debugfs_initialized();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/debugfs/inode.c (ffffffff81430da0)
Location: fs/debugfs/inode.c:890
Inline: False
Direct callers:
  - kernel/trace/trace.c:tracing_init_dentry
  - mm/zswap.c:init_zswap
  - drivers/remoteproc/remoteproc_debugfs.c:rproc_init_debugfs
```
**Symbols:**

```
ffffffff81430da0-ffffffff81430db2: debugfs_initialized (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
bool debugfs_initialized();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/debugfs/inode.c (ffffffff81480bb0)
Location: fs/debugfs/inode.c:783
Inline: False
Direct callers:
  - mm/zswap.c:zswap_debugfs_init
  - lib/dynamic_debug.c:dynamic_debug_init_control
  - drivers/remoteproc/remoteproc_debugfs.c:rproc_init_debugfs
```
**Symbols:**

```
ffffffff81480bb0-ffffffff81480bc2: debugfs_initialized (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
bool debugfs_initialized();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/debugfs/inode.c (ffffffff8149ec8b)
Location: fs/debugfs/inode.c:808
Inline: True
Inline callers:
  - fs/debugfs/inode.c:debugfs_create_symlink
  - fs/debugfs/inode.c:debugfs_create_automount
  - fs/debugfs/inode.c:debugfs_create_dir
  - fs/debugfs/inode.c:__debugfs_create_file
Direct callers:
  - mm/zswap.c:zswap_debugfs_init
  - lib/dynamic_debug.c:dynamic_debug_init_control
  - drivers/remoteproc/remoteproc_debugfs.c:rproc_init_debugfs
```
**Symbols:**

```
ffffffff8149e260-ffffffff8149e272: debugfs_initialized (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
bool debugfs_initialized();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/debugfs/inode.c (ffffffff814a4c6b)
Location: fs/debugfs/inode.c:812
Inline: True
Inline callers:
  - fs/debugfs/inode.c:debugfs_create_symlink
  - fs/debugfs/inode.c:debugfs_create_automount
  - fs/debugfs/inode.c:debugfs_create_dir
  - fs/debugfs/inode.c:__debugfs_create_file
Direct callers:
  - mm/zswap.c:init_zswap
  - lib/dynamic_debug.c:dynamic_debug_init_control
  - drivers/remoteproc/remoteproc_debugfs.c:rproc_init_debugfs
```
**Symbols:**

```
ffffffff814a4220-ffffffff814a4232: debugfs_initialized (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline, Transformation ⚠️</summary>

```c
bool debugfs_initialized();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/debugfs/inode.c (ffffffff814fcd55)
Location: fs/debugfs/inode.c:812
Inline: True
Inline callers:
  - fs/debugfs/inode.c:debugfs_create_symlink
  - fs/debugfs/inode.c:debugfs_create_automount
  - fs/debugfs/inode.c:debugfs_create_dir
  - fs/debugfs/inode.c:__debugfs_create_file
Direct callers:
  - mm/zswap.c:init_zswap
  - lib/dynamic_debug.c:dynamic_debug_init_control
  - drivers/remoteproc/remoteproc_debugfs.c:rproc_init_debugfs
```
**Symbols:**

```
ffffffff81cd2435-ffffffff81cd2455: debugfs_initialized.cold (STB_LOCAL)
ffffffff814fc5f0-ffffffff814fc608: debugfs_initialized (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline, Transformation ⚠️</summary>

```c
bool debugfs_initialized();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/debugfs/inode.c (ffffffff8158d58d)
Location: fs/debugfs/inode.c:822
Inline: True
Inline callers:
  - fs/debugfs/inode.c:debugfs_create_symlink
  - fs/debugfs/inode.c:debugfs_create_automount
  - fs/debugfs/inode.c:debugfs_create_dir
  - fs/debugfs/inode.c:__debugfs_create_file
  - fs/debugfs/inode.c:debugfs_lookup
Direct callers:
  - mm/zswap.c:init_zswap
  - lib/dynamic_debug.c:dynamic_debug_init_control
  - drivers/remoteproc/remoteproc_debugfs.c:rproc_init_debugfs
```
**Symbols:**

```
ffffffff81e85571-ffffffff81e8559b: debugfs_initialized.cold (STB_LOCAL)
ffffffff8158cd40-ffffffff8158cd62: debugfs_initialized (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline, Transformation ⚠️</summary>

```c
bool debugfs_initialized();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/debugfs/inode.c (ffffffff816343ed)
Location: fs/debugfs/inode.c:867
Inline: True
Inline callers:
  - fs/debugfs/inode.c:debugfs_create_symlink
  - fs/debugfs/inode.c:debugfs_create_automount
  - fs/debugfs/inode.c:debugfs_create_dir
  - fs/debugfs/inode.c:__debugfs_create_file
  - fs/debugfs/inode.c:debugfs_lookup
Direct callers:
  - mm/zswap.c:init_zswap
  - lib/dynamic_debug.c:dynamic_debug_init_control
  - drivers/remoteproc/remoteproc_debugfs.c:rproc_init_debugfs
```
**Symbols:**

```
ffffffff820729df-ffffffff82072a09: debugfs_initialized.cold (STB_LOCAL)
ffffffff816336b0-ffffffff816336d2: debugfs_initialized (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline, Transformation ⚠️</summary>

```c
bool debugfs_initialized();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/debugfs/inode.c (ffffffff8166c6fd)
Location: fs/debugfs/inode.c:867
Inline: True
Inline callers:
  - fs/debugfs/inode.c:debugfs_create_symlink
  - fs/debugfs/inode.c:debugfs_create_automount
  - fs/debugfs/inode.c:debugfs_create_dir
  - fs/debugfs/inode.c:__debugfs_create_file
  - fs/debugfs/inode.c:debugfs_lookup
Direct callers:
  - mm/zswap.c:zswap_setup
  - lib/dynamic_debug.c:dynamic_debug_init_control
  - drivers/remoteproc/remoteproc_debugfs.c:rproc_init_debugfs
```
**Symbols:**

```
ffffffff820f2643-ffffffff820f266d: debugfs_initialized.cold (STB_LOCAL)
ffffffff8166b9b0-ffffffff8166b9d2: debugfs_initialized (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline, Transformation ⚠️</summary>

```c
bool debugfs_initialized();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/debugfs/inode.c (ffffffff816a687d)
Location: fs/debugfs/inode.c:914
Inline: True
Inline callers:
  - fs/debugfs/inode.c:debugfs_create_symlink
  - fs/debugfs/inode.c:debugfs_create_automount
  - fs/debugfs/inode.c:debugfs_create_dir
  - fs/debugfs/inode.c:__debugfs_create_file
  - fs/debugfs/inode.c:debugfs_lookup
Direct callers:
  - mm/zswap.c:zswap_debugfs_init
  - lib/dynamic_debug.c:dynamic_debug_init_control
  - drivers/remoteproc/remoteproc_debugfs.c:rproc_init_debugfs
```
**Symbols:**

```
ffffffff821cf8de-ffffffff821cf908: debugfs_initialized.cold (STB_LOCAL)
ffffffff816a5d60-ffffffff816a5d82: debugfs_initialized (STB_GLOBAL)
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
bool debugfs_initialized();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/debugfs/inode.c (ffff800010515948)
Location: fs/debugfs/inode.c:890
Inline: False
Direct callers:
  - mm/zswap.c:init_zswap
  - drivers/remoteproc/remoteproc_debugfs.c:rproc_init_debugfs
```
**Symbols:**

```
ffff800010515948-ffff800010515968: debugfs_initialized (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
bool debugfs_initialized();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/debugfs/inode.c (c06d072c)
Location: fs/debugfs/inode.c:890
Inline: False
Direct callers:
  - kernel/trace/trace.c:tracing_init_dentry
  - mm/zswap.c:init_zswap
  - drivers/remoteproc/remoteproc_debugfs.c:rproc_init_debugfs
```
**Symbols:**

```
c06d072c-c06d0750: debugfs_initialized (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
bool debugfs_initialized();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/debugfs/inode.c (c00000000065e280)
Location: fs/debugfs/inode.c:890
Inline: False
Direct callers:
  - mm/zswap.c:init_zswap
  - drivers/remoteproc/remoteproc_debugfs.c:rproc_init_debugfs
```
**Symbols:**

```
c00000000065e280-c00000000065e29c: debugfs_initialized (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
bool debugfs_initialized();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/debugfs/inode.c (ffffffe00037f160)
Location: fs/debugfs/inode.c:890
Inline: False
Direct callers:
  - mm/zswap.c:init_zswap
```
**Symbols:**

```
ffffffe00037f160-ffffffe00037f182: debugfs_initialized (STB_GLOBAL)
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
bool debugfs_initialized();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/debugfs/inode.c (ffffffff81429380)
Location: fs/debugfs/inode.c:890
Inline: False
Direct callers:
  - kernel/trace/trace.c:tracing_init_dentry
  - mm/zswap.c:init_zswap
  - drivers/remoteproc/remoteproc_debugfs.c:rproc_init_debugfs
```
**Symbols:**

```
ffffffff81429380-ffffffff81429392: debugfs_initialized (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
bool debugfs_initialized();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/debugfs/inode.c (ffffffff81419e00)
Location: fs/debugfs/inode.c:890
Inline: False
Direct callers:
  - kernel/trace/trace.c:tracing_init_dentry
  - mm/zswap.c:init_zswap
```
**Symbols:**

```
ffffffff81419e00-ffffffff81419e12: debugfs_initialized (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
bool debugfs_initialized();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/debugfs/inode.c (ffffffff81425520)
Location: fs/debugfs/inode.c:890
Inline: False
Direct callers:
  - kernel/trace/trace.c:tracing_init_dentry
  - mm/zswap.c:init_zswap
```
**Symbols:**

```
ffffffff81425520-ffffffff81425532: debugfs_initialized (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
bool debugfs_initialized();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/debugfs/inode.c (ffffffff8143c3e0)
Location: fs/debugfs/inode.c:890
Inline: False
Direct callers:
  - kernel/trace/trace.c:tracing_init_dentry
  - mm/zswap.c:init_zswap
  - drivers/remoteproc/remoteproc_debugfs.c:rproc_init_debugfs
```
**Symbols:**

```
ffffffff8143c3e0-ffffffff8143c3f2: debugfs_initialized (STB_GLOBAL)
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
