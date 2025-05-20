# Function: <code>debugfs_file_put</code>

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
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void debugfs_file_put(struct dentry *dentry);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/debugfs/file.c (ffffffff813a25f0)
Location: fs/debugfs/file.c:130
Inline: False
Direct callers:
  - fs/debugfs/file.c:read_file_blob
  - fs/debugfs/file.c:debugfs_write_file_bool
  - fs/debugfs/file.c:debugfs_read_file_bool
  - fs/debugfs/file.c:debugfs_attr_write
  - fs/debugfs/file.c:debugfs_attr_read
  - fs/debugfs/file.c:full_proxy_open
  - fs/debugfs/file.c:full_proxy_poll
  - fs/debugfs/file.c:full_proxy_unlocked_ioctl
  - fs/debugfs/file.c:full_proxy_write
  - fs/debugfs/file.c:full_proxy_read
  - fs/debugfs/file.c:full_proxy_llseek
  - fs/debugfs/file.c:open_proxy_open
```
**Symbols:**

```
ffffffff813a25f0-ffffffff813a2616: debugfs_file_put (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void debugfs_file_put(struct dentry *dentry);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/debugfs/file.c (ffffffff813d19d0)
Location: fs/debugfs/file.c:130
Inline: False
Direct callers:
  - fs/debugfs/file.c:read_file_blob
  - fs/debugfs/file.c:debugfs_write_file_bool
  - fs/debugfs/file.c:debugfs_read_file_bool
  - fs/debugfs/file.c:debugfs_attr_write
  - fs/debugfs/file.c:debugfs_attr_read
  - fs/debugfs/file.c:full_proxy_open
  - fs/debugfs/file.c:full_proxy_poll
  - fs/debugfs/file.c:full_proxy_unlocked_ioctl
  - fs/debugfs/file.c:full_proxy_write
  - fs/debugfs/file.c:full_proxy_read
  - fs/debugfs/file.c:full_proxy_llseek
  - fs/debugfs/file.c:open_proxy_open
```
**Symbols:**

```
ffffffff813d19d0-ffffffff813d19f6: debugfs_file_put (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void debugfs_file_put(struct dentry *dentry);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/debugfs/file.c (ffffffff813ec0d0)
Location: fs/debugfs/file.c:130
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:pseudo_lock_measure_trigger
  - fs/debugfs/file.c:read_file_blob
  - fs/debugfs/file.c:debugfs_write_file_bool
  - fs/debugfs/file.c:debugfs_read_file_bool
  - fs/debugfs/file.c:debugfs_attr_write
  - fs/debugfs/file.c:debugfs_attr_read
  - fs/debugfs/file.c:full_proxy_open
  - fs/debugfs/file.c:full_proxy_poll
  - fs/debugfs/file.c:full_proxy_unlocked_ioctl
  - fs/debugfs/file.c:full_proxy_write
  - fs/debugfs/file.c:full_proxy_read
  - fs/debugfs/file.c:full_proxy_llseek
  - fs/debugfs/file.c:open_proxy_open
```
**Symbols:**

```
ffffffff813ec0d0-ffffffff813ec0f6: debugfs_file_put (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void debugfs_file_put(struct dentry *dentry);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/debugfs/file.c (ffffffff81418300)
Location: fs/debugfs/file.c:130
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:pseudo_lock_measure_trigger
  - fs/debugfs/file.c:read_file_blob
  - fs/debugfs/file.c:debugfs_write_file_bool
  - fs/debugfs/file.c:debugfs_read_file_bool
  - fs/debugfs/file.c:debugfs_attr_write
  - fs/debugfs/file.c:debugfs_attr_read
  - fs/debugfs/file.c:full_proxy_open
  - fs/debugfs/file.c:full_proxy_poll
  - fs/debugfs/file.c:full_proxy_unlocked_ioctl
  - fs/debugfs/file.c:full_proxy_write
  - fs/debugfs/file.c:full_proxy_read
  - fs/debugfs/file.c:full_proxy_llseek
  - fs/debugfs/file.c:open_proxy_open
```
**Symbols:**

```
ffffffff81418300-ffffffff81418325: debugfs_file_put (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void debugfs_file_put(struct dentry *dentry);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/debugfs/file.c (ffffffff814321c0)
Location: fs/debugfs/file.c:131
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:pseudo_lock_measure_trigger
  - fs/debugfs/file.c:read_file_blob
  - fs/debugfs/file.c:debugfs_write_file_bool
  - fs/debugfs/file.c:debugfs_read_file_bool
  - fs/debugfs/file.c:debugfs_attr_write
  - fs/debugfs/file.c:debugfs_attr_read
  - fs/debugfs/file.c:full_proxy_open
  - fs/debugfs/file.c:full_proxy_poll
  - fs/debugfs/file.c:full_proxy_unlocked_ioctl
  - fs/debugfs/file.c:full_proxy_write
  - fs/debugfs/file.c:full_proxy_read
  - fs/debugfs/file.c:full_proxy_llseek
  - fs/debugfs/file.c:open_proxy_open
```
**Symbols:**

```
ffffffff814321c0-ffffffff814321e5: debugfs_file_put (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void debugfs_file_put(struct dentry *dentry);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/debugfs/file.c (ffffffff81482490)
Location: fs/debugfs/file.c:132
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:pseudo_lock_measure_trigger
  - fs/debugfs/file.c:read_file_blob
  - fs/debugfs/file.c:debugfs_write_file_bool
  - fs/debugfs/file.c:debugfs_read_file_bool
  - fs/debugfs/file.c:debugfs_attr_write
  - fs/debugfs/file.c:debugfs_attr_read
  - fs/debugfs/file.c:full_proxy_open
  - fs/debugfs/file.c:full_proxy_poll
  - fs/debugfs/file.c:full_proxy_unlocked_ioctl
  - fs/debugfs/file.c:full_proxy_write
  - fs/debugfs/file.c:full_proxy_read
  - fs/debugfs/file.c:full_proxy_llseek
  - fs/debugfs/file.c:open_proxy_open
  - drivers/base/regmap/regmap-debugfs.c:regmap_cache_bypass_write_file
  - drivers/base/regmap/regmap-debugfs.c:regmap_cache_only_write_file
  - drivers/base/regmap/regmap-debugfs.c:regmap_cache_only_write_file
```
**Symbols:**

```
ffffffff81482490-ffffffff814824d0: debugfs_file_put (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void debugfs_file_put(struct dentry *dentry);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/debugfs/file.c (ffffffff8149fb20)
Location: fs/debugfs/file.c:132
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:pseudo_lock_measure_trigger
  - fs/debugfs/file.c:read_file_blob
  - fs/debugfs/file.c:debugfs_write_file_bool
  - fs/debugfs/file.c:debugfs_read_file_bool
  - fs/debugfs/file.c:debugfs_attr_write
  - fs/debugfs/file.c:debugfs_attr_read
  - fs/debugfs/file.c:full_proxy_open
  - fs/debugfs/file.c:full_proxy_poll
  - fs/debugfs/file.c:full_proxy_unlocked_ioctl
  - fs/debugfs/file.c:full_proxy_write
  - fs/debugfs/file.c:full_proxy_read
  - fs/debugfs/file.c:full_proxy_llseek
  - fs/debugfs/file.c:open_proxy_open
  - drivers/base/regmap/regmap-debugfs.c:regmap_cache_bypass_write_file
  - drivers/base/regmap/regmap-debugfs.c:regmap_cache_only_write_file
  - drivers/base/regmap/regmap-debugfs.c:regmap_cache_only_write_file
```
**Symbols:**

```
ffffffff8149fb20-ffffffff8149fb60: debugfs_file_put (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void debugfs_file_put(struct dentry *dentry);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/debugfs/file.c (ffffffff814a5b20)
Location: fs/debugfs/file.c:132
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:pseudo_lock_measure_trigger
  - fs/debugfs/file.c:read_file_blob
  - fs/debugfs/file.c:debugfs_read_file_str
  - fs/debugfs/file.c:debugfs_read_file_str
  - fs/debugfs/file.c:debugfs_write_file_bool
  - fs/debugfs/file.c:debugfs_read_file_bool
  - fs/debugfs/file.c:debugfs_attr_write
  - fs/debugfs/file.c:debugfs_attr_read
  - fs/debugfs/file.c:full_proxy_open
  - fs/debugfs/file.c:full_proxy_poll
  - fs/debugfs/file.c:full_proxy_unlocked_ioctl
  - fs/debugfs/file.c:full_proxy_write
  - fs/debugfs/file.c:full_proxy_read
  - fs/debugfs/file.c:full_proxy_llseek
  - fs/debugfs/file.c:open_proxy_open
  - drivers/base/regmap/regmap-debugfs.c:regmap_cache_bypass_write_file
  - drivers/base/regmap/regmap-debugfs.c:regmap_cache_only_write_file
  - drivers/base/regmap/regmap-debugfs.c:regmap_cache_only_write_file
```
**Symbols:**

```
ffffffff814a5b20-ffffffff814a5b60: debugfs_file_put (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void debugfs_file_put(struct dentry *dentry);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/debugfs/file.c (ffffffff814fdcc0)
Location: fs/debugfs/file.c:132
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:pseudo_lock_measure_trigger
  - fs/debugfs/file.c:read_file_blob
  - fs/debugfs/file.c:debugfs_read_file_str
  - fs/debugfs/file.c:debugfs_read_file_str
  - fs/debugfs/file.c:debugfs_write_file_bool
  - fs/debugfs/file.c:debugfs_read_file_bool
  - fs/debugfs/file.c:debugfs_attr_write
  - fs/debugfs/file.c:debugfs_attr_read
  - fs/debugfs/file.c:full_proxy_open
  - fs/debugfs/file.c:full_proxy_poll
  - fs/debugfs/file.c:full_proxy_unlocked_ioctl
  - fs/debugfs/file.c:full_proxy_write
  - fs/debugfs/file.c:full_proxy_read
  - fs/debugfs/file.c:full_proxy_llseek
  - fs/debugfs/file.c:open_proxy_open
  - drivers/base/regmap/regmap-debugfs.c:regmap_cache_bypass_write_file
  - drivers/base/regmap/regmap-debugfs.c:regmap_cache_only_write_file
  - drivers/base/regmap/regmap-debugfs.c:regmap_cache_only_write_file
  - drivers/base/regmap/regmap-debugfs.c:regmap_cache_only_write_file
```
**Symbols:**

```
ffffffff814fdcc0-ffffffff814fdd00: debugfs_file_put (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void debugfs_file_put(struct dentry *dentry);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/debugfs/file.c (ffffffff8158e880)
Location: fs/debugfs/file.c:132
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:pseudo_lock_measure_trigger
  - fs/debugfs/file.c:read_file_blob
  - fs/debugfs/file.c:debugfs_read_file_str
  - fs/debugfs/file.c:debugfs_read_file_str
  - fs/debugfs/file.c:debugfs_write_file_bool
  - fs/debugfs/file.c:debugfs_read_file_bool
  - fs/debugfs/file.c:debugfs_attr_write
  - fs/debugfs/file.c:debugfs_attr_read
  - fs/debugfs/file.c:full_proxy_open
  - fs/debugfs/file.c:full_proxy_poll
  - fs/debugfs/file.c:full_proxy_unlocked_ioctl
  - fs/debugfs/file.c:full_proxy_write
  - fs/debugfs/file.c:full_proxy_read
  - fs/debugfs/file.c:full_proxy_llseek
  - fs/debugfs/file.c:open_proxy_open
  - drivers/base/regmap/regmap-debugfs.c:regmap_cache_bypass_write_file
  - drivers/base/regmap/regmap-debugfs.c:regmap_cache_only_write_file
  - drivers/base/regmap/regmap-debugfs.c:regmap_cache_only_write_file
  - drivers/base/regmap/regmap-debugfs.c:regmap_cache_only_write_file
```
**Symbols:**

```
ffffffff8158e880-ffffffff8158e8e4: debugfs_file_put (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void debugfs_file_put(struct dentry *dentry);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/debugfs/file.c (ffffffff81635900)
Location: fs/debugfs/file.c:132
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:pseudo_lock_measure_trigger
  - fs/debugfs/file.c:read_file_blob
  - fs/debugfs/file.c:debugfs_read_file_str
  - fs/debugfs/file.c:debugfs_read_file_str
  - fs/debugfs/file.c:debugfs_write_file_bool
  - fs/debugfs/file.c:debugfs_read_file_bool
  - fs/debugfs/file.c:debugfs_attr_write_signed
  - fs/debugfs/file.c:debugfs_attr_write
  - fs/debugfs/file.c:debugfs_attr_read
  - fs/debugfs/file.c:full_proxy_open
  - fs/debugfs/file.c:full_proxy_poll
  - fs/debugfs/file.c:full_proxy_unlocked_ioctl
  - fs/debugfs/file.c:full_proxy_write
  - fs/debugfs/file.c:full_proxy_read
  - fs/debugfs/file.c:full_proxy_llseek
  - fs/debugfs/file.c:open_proxy_open
  - drivers/base/regmap/regmap-debugfs.c:regmap_cache_bypass_write_file
  - drivers/base/regmap/regmap-debugfs.c:regmap_cache_only_write_file
  - drivers/base/regmap/regmap-debugfs.c:regmap_cache_only_write_file
  - drivers/base/regmap/regmap-debugfs.c:regmap_cache_only_write_file
  - drivers/base/regmap/regmap-debugfs.c:regmap_cache_only_write_file
```
**Symbols:**

```
ffffffff81635900-ffffffff81635964: debugfs_file_put (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void debugfs_file_put(struct dentry *dentry);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/debugfs/file.c (ffffffff8166dc10)
Location: fs/debugfs/file.c:132
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:pseudo_lock_measure_trigger
  - fs/debugfs/file.c:read_file_blob
  - fs/debugfs/file.c:debugfs_read_file_str
  - fs/debugfs/file.c:debugfs_read_file_str
  - fs/debugfs/file.c:debugfs_write_file_bool
  - fs/debugfs/file.c:debugfs_read_file_bool
  - fs/debugfs/file.c:debugfs_attr_write_signed
  - fs/debugfs/file.c:debugfs_attr_write
  - fs/debugfs/file.c:debugfs_attr_read
  - fs/debugfs/file.c:full_proxy_open
  - fs/debugfs/file.c:full_proxy_poll
  - fs/debugfs/file.c:full_proxy_unlocked_ioctl
  - fs/debugfs/file.c:full_proxy_write
  - fs/debugfs/file.c:full_proxy_read
  - fs/debugfs/file.c:full_proxy_llseek
  - fs/debugfs/file.c:open_proxy_open
  - drivers/base/regmap/regmap-debugfs.c:regmap_cache_bypass_write_file
  - drivers/base/regmap/regmap-debugfs.c:regmap_cache_only_write_file
  - drivers/base/regmap/regmap-debugfs.c:regmap_cache_only_write_file
  - drivers/base/regmap/regmap-debugfs.c:regmap_cache_only_write_file
  - drivers/base/regmap/regmap-debugfs.c:regmap_cache_only_write_file
```
**Symbols:**

```
ffffffff8166dc10-ffffffff8166dc74: debugfs_file_put (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void debugfs_file_put(struct dentry *dentry);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/debugfs/file.c (ffffffff816a8360)
Location: fs/debugfs/file.c:144
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:pseudo_lock_measure_trigger
  - fs/debugfs/file.c:write_file_blob
  - fs/debugfs/file.c:read_file_blob
  - fs/debugfs/file.c:debugfs_write_file_str
  - fs/debugfs/file.c:debugfs_write_file_str
  - fs/debugfs/file.c:debugfs_read_file_str
  - fs/debugfs/file.c:debugfs_read_file_str
  - fs/debugfs/file.c:debugfs_write_file_bool
  - fs/debugfs/file.c:debugfs_read_file_bool
  - fs/debugfs/file.c:debugfs_attr_write_signed
  - fs/debugfs/file.c:debugfs_attr_write
  - fs/debugfs/file.c:debugfs_attr_read
  - fs/debugfs/file.c:full_proxy_open
  - fs/debugfs/file.c:full_proxy_poll
  - fs/debugfs/file.c:full_proxy_unlocked_ioctl
  - fs/debugfs/file.c:full_proxy_write
  - fs/debugfs/file.c:full_proxy_read
  - fs/debugfs/file.c:full_proxy_llseek
  - fs/debugfs/file.c:open_proxy_open
  - drivers/base/regmap/regmap-debugfs.c:regmap_cache_bypass_write_file
  - drivers/base/regmap/regmap-debugfs.c:regmap_cache_only_write_file
  - drivers/base/regmap/regmap-debugfs.c:regmap_cache_only_write_file
  - drivers/base/regmap/regmap-debugfs.c:regmap_cache_only_write_file
  - drivers/base/regmap/regmap-debugfs.c:regmap_cache_only_write_file
```
**Symbols:**

```
ffffffff816a8360-ffffffff816a83c7: debugfs_file_put (STB_GLOBAL)
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
void debugfs_file_put(struct dentry *dentry);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/debugfs/file.c (ffff8000105170c0)
Location: fs/debugfs/file.c:131
Inline: False
Direct callers:
  - fs/debugfs/file.c:read_file_blob
  - fs/debugfs/file.c:debugfs_write_file_bool
  - fs/debugfs/file.c:debugfs_read_file_bool
  - fs/debugfs/file.c:debugfs_attr_write
  - fs/debugfs/file.c:debugfs_attr_read
  - fs/debugfs/file.c:full_proxy_open
  - fs/debugfs/file.c:full_proxy_poll
  - fs/debugfs/file.c:full_proxy_unlocked_ioctl
  - fs/debugfs/file.c:full_proxy_write
  - fs/debugfs/file.c:full_proxy_read
  - fs/debugfs/file.c:full_proxy_llseek
  - fs/debugfs/file.c:open_proxy_open
```
**Symbols:**

```
ffff8000105170c0-ffff80001051710c: debugfs_file_put (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void debugfs_file_put(struct dentry *dentry);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/debugfs/file.c (c06d1c0c)
Location: fs/debugfs/file.c:131
Inline: False
Direct callers:
  - fs/debugfs/file.c:read_file_blob
  - fs/debugfs/file.c:debugfs_write_file_bool
  - fs/debugfs/file.c:debugfs_read_file_bool
  - fs/debugfs/file.c:debugfs_attr_write
  - fs/debugfs/file.c:debugfs_attr_read
  - fs/debugfs/file.c:full_proxy_open
  - fs/debugfs/file.c:full_proxy_poll
  - fs/debugfs/file.c:full_proxy_unlocked_ioctl
  - fs/debugfs/file.c:full_proxy_write
  - fs/debugfs/file.c:full_proxy_read
  - fs/debugfs/file.c:full_proxy_llseek
  - fs/debugfs/file.c:open_proxy_open
```
**Symbols:**

```
c06d1c0c-c06d1c40: debugfs_file_put (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void debugfs_file_put(struct dentry *dentry);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/debugfs/file.c (c000000000660090)
Location: fs/debugfs/file.c:131
Inline: False
Direct callers:
  - fs/debugfs/file.c:read_file_blob
  - fs/debugfs/file.c:debugfs_write_file_bool
  - fs/debugfs/file.c:debugfs_read_file_bool
  - fs/debugfs/file.c:debugfs_attr_write
  - fs/debugfs/file.c:debugfs_attr_read
  - fs/debugfs/file.c:full_proxy_open
  - fs/debugfs/file.c:full_proxy_poll
  - fs/debugfs/file.c:full_proxy_unlocked_ioctl
  - fs/debugfs/file.c:full_proxy_write
  - fs/debugfs/file.c:full_proxy_read
  - fs/debugfs/file.c:full_proxy_llseek
  - fs/debugfs/file.c:open_proxy_open
```
**Symbols:**

```
c000000000660090-c0000000006600f4: debugfs_file_put (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
void debugfs_file_put(struct dentry *dentry);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/debugfs/file.c (ffffffe0003817b0)
Location: fs/debugfs/file.c:131
Inline: True
Inline callers:
  - fs/debugfs/file.c:read_file_blob
  - fs/debugfs/file.c:debugfs_write_file_bool
  - fs/debugfs/file.c:debugfs_read_file_bool
  - fs/debugfs/file.c:debugfs_attr_write
  - fs/debugfs/file.c:debugfs_attr_read
  - fs/debugfs/file.c:full_proxy_open
  - fs/debugfs/file.c:full_proxy_poll
  - fs/debugfs/file.c:full_proxy_unlocked_ioctl
  - fs/debugfs/file.c:full_proxy_write
  - fs/debugfs/file.c:full_proxy_read
  - fs/debugfs/file.c:full_proxy_llseek
  - fs/debugfs/file.c:open_proxy_open
```
**Symbols:**

```
ffffffe0003806a2-ffffffe0003806ea: debugfs_file_put (STB_GLOBAL)
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
void debugfs_file_put(struct dentry *dentry);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/debugfs/file.c (ffffffff8142a7a0)
Location: fs/debugfs/file.c:131
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:pseudo_lock_measure_trigger
  - fs/debugfs/file.c:read_file_blob
  - fs/debugfs/file.c:debugfs_write_file_bool
  - fs/debugfs/file.c:debugfs_read_file_bool
  - fs/debugfs/file.c:debugfs_attr_write
  - fs/debugfs/file.c:debugfs_attr_read
  - fs/debugfs/file.c:full_proxy_open
  - fs/debugfs/file.c:full_proxy_poll
  - fs/debugfs/file.c:full_proxy_unlocked_ioctl
  - fs/debugfs/file.c:full_proxy_write
  - fs/debugfs/file.c:full_proxy_read
  - fs/debugfs/file.c:full_proxy_llseek
  - fs/debugfs/file.c:open_proxy_open
```
**Symbols:**

```
ffffffff8142a7a0-ffffffff8142a7c5: debugfs_file_put (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void debugfs_file_put(struct dentry *dentry);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/debugfs/file.c (ffffffff8141b220)
Location: fs/debugfs/file.c:131
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:pseudo_lock_measure_trigger
  - fs/debugfs/file.c:read_file_blob
  - fs/debugfs/file.c:debugfs_write_file_bool
  - fs/debugfs/file.c:debugfs_read_file_bool
  - fs/debugfs/file.c:debugfs_attr_write
  - fs/debugfs/file.c:debugfs_attr_read
  - fs/debugfs/file.c:full_proxy_open
  - fs/debugfs/file.c:full_proxy_poll
  - fs/debugfs/file.c:full_proxy_unlocked_ioctl
  - fs/debugfs/file.c:full_proxy_write
  - fs/debugfs/file.c:full_proxy_read
  - fs/debugfs/file.c:full_proxy_llseek
  - fs/debugfs/file.c:open_proxy_open
```
**Symbols:**

```
ffffffff8141b220-ffffffff8141b245: debugfs_file_put (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void debugfs_file_put(struct dentry *dentry);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/debugfs/file.c (ffffffff81426940)
Location: fs/debugfs/file.c:131
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:pseudo_lock_measure_trigger
  - fs/debugfs/file.c:read_file_blob
  - fs/debugfs/file.c:debugfs_write_file_bool
  - fs/debugfs/file.c:debugfs_read_file_bool
  - fs/debugfs/file.c:debugfs_attr_write
  - fs/debugfs/file.c:debugfs_attr_read
  - fs/debugfs/file.c:full_proxy_open
  - fs/debugfs/file.c:full_proxy_poll
  - fs/debugfs/file.c:full_proxy_unlocked_ioctl
  - fs/debugfs/file.c:full_proxy_write
  - fs/debugfs/file.c:full_proxy_read
  - fs/debugfs/file.c:full_proxy_llseek
  - fs/debugfs/file.c:open_proxy_open
```
**Symbols:**

```
ffffffff81426940-ffffffff81426965: debugfs_file_put (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void debugfs_file_put(struct dentry *dentry);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/debugfs/file.c (ffffffff8143d800)
Location: fs/debugfs/file.c:131
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:pseudo_lock_measure_trigger
  - fs/debugfs/file.c:read_file_blob
  - fs/debugfs/file.c:debugfs_write_file_bool
  - fs/debugfs/file.c:debugfs_read_file_bool
  - fs/debugfs/file.c:debugfs_attr_write
  - fs/debugfs/file.c:debugfs_attr_read
  - fs/debugfs/file.c:full_proxy_open
  - fs/debugfs/file.c:full_proxy_poll
  - fs/debugfs/file.c:full_proxy_unlocked_ioctl
  - fs/debugfs/file.c:full_proxy_write
  - fs/debugfs/file.c:full_proxy_read
  - fs/debugfs/file.c:full_proxy_llseek
  - fs/debugfs/file.c:open_proxy_open
```
**Symbols:**

```
ffffffff8143d800-ffffffff8143d825: debugfs_file_put (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
