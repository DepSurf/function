# Function: <code>device_get_devnode</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline ⚠️</summary>

```c
const char *device_get_devnode(struct device *dev, umode_t *mode, kuid_t *uid, kgid_t *gid, const char **tmp);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/core.c (ffffffff81548d60)
Location: drivers/base/core.c:1343
Inline: True
Direct callers:
  - drivers/base/core.c:dev_uevent
  - drivers/base/devtmpfs.c:devtmpfs_create_node
  - drivers/base/devtmpfs.c:devtmpfs_delete_node
```
**Symbols:**

```
ffffffff81548d60-ffffffff81548e26: device_get_devnode (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
const char *device_get_devnode(struct device *dev, umode_t *mode, kuid_t *uid, kgid_t *gid, const char **tmp);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/core.c (ffffffff8159a990)
Location: drivers/base/core.c:1343
Inline: True
Direct callers:
  - drivers/base/core.c:dev_uevent
  - drivers/base/devtmpfs.c:devtmpfs_delete_node
  - drivers/base/devtmpfs.c:devtmpfs_create_node
```
**Symbols:**

```
ffffffff8159a990-ffffffff8159aa56: device_get_devnode (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
const char *device_get_devnode(struct device *dev, umode_t *mode, kuid_t *uid, kgid_t *gid, const char **tmp);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/core.c (ffffffff815c8ef0)
Location: drivers/base/core.c:1934
Inline: True
Direct callers:
  - drivers/base/core.c:dev_uevent
  - drivers/base/devtmpfs.c:devtmpfs_delete_node
  - drivers/base/devtmpfs.c:devtmpfs_create_node
```
**Symbols:**

```
ffffffff815c8ef0-ffffffff815c8fb6: device_get_devnode (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
const char *device_get_devnode(struct device *dev, umode_t *mode, kuid_t *uid, kgid_t *gid, const char **tmp);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/core.c (ffffffff815ddc00)
Location: drivers/base/core.c:1932
Inline: True
Direct callers:
  - drivers/base/core.c:dev_uevent
  - drivers/base/devtmpfs.c:devtmpfs_delete_node
  - drivers/base/devtmpfs.c:devtmpfs_create_node
```
**Symbols:**

```
ffffffff815ddc00-ffffffff815ddcc6: device_get_devnode (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
const char *device_get_devnode(struct device *dev, umode_t *mode, kuid_t *uid, kgid_t *gid, const char **tmp);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/core.c (ffffffff81644c00)
Location: drivers/base/core.c:2067
Inline: True
Direct callers:
  - drivers/base/core.c:dev_uevent
  - drivers/base/devtmpfs.c:devtmpfs_delete_node
  - drivers/base/devtmpfs.c:devtmpfs_create_node
```
**Symbols:**

```
ffffffff81644c00-ffffffff81644ccf: device_get_devnode (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
const char *device_get_devnode(struct device *dev, umode_t *mode, kuid_t *uid, kgid_t *gid, const char **tmp);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/core.c (ffffffff81680020)
Location: drivers/base/core.c:2114
Inline: True
Direct callers:
  - drivers/base/core.c:dev_uevent
  - drivers/base/devtmpfs.c:devtmpfs_delete_node
  - drivers/base/devtmpfs.c:devtmpfs_create_node
```
**Symbols:**

```
ffffffff81680020-ffffffff816800f6: device_get_devnode (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
const char *device_get_devnode(struct device *dev, umode_t *mode, kuid_t *uid, kgid_t *gid, const char **tmp);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/core.c (ffffffff8169fab0)
Location: drivers/base/core.c:2189
Inline: True
Direct callers:
  - drivers/base/core.c:dev_uevent
  - drivers/base/devtmpfs.c:devtmpfs_delete_node
  - drivers/base/devtmpfs.c:devtmpfs_create_node
```
**Symbols:**

```
ffffffff8169fab0-ffffffff8169fb86: device_get_devnode (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
const char *device_get_devnode(struct device *dev, umode_t *mode, kuid_t *uid, kgid_t *gid, const char **tmp);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/core.c (ffffffff816d8220)
Location: drivers/base/core.c:2415
Inline: True
Direct callers:
  - drivers/base/core.c:dev_uevent
  - drivers/base/devtmpfs.c:devtmpfs_delete_node
  - drivers/base/devtmpfs.c:devtmpfs_create_node
```
**Symbols:**

```
ffffffff816d8220-ffffffff816d82f2: device_get_devnode (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
const char *device_get_devnode(struct device *dev, umode_t *mode, kuid_t *uid, kgid_t *gid, const char **tmp);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/core.c (ffffffff816fc320)
Location: drivers/base/core.c:2452
Inline: True
Direct callers:
  - drivers/base/core.c:dev_uevent
  - drivers/base/devtmpfs.c:devtmpfs_delete_node
  - drivers/base/devtmpfs.c:devtmpfs_create_node
```
**Symbols:**

```
ffffffff816fc320-ffffffff816fc3f2: device_get_devnode (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
const char *device_get_devnode(struct device *dev, umode_t *mode, kuid_t *uid, kgid_t *gid, const char **tmp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/core.c (ffffffff817b5c40)
Location: drivers/base/core.c:2953
Inline: False
Direct callers:
  - drivers/base/core.c:dev_uevent
  - drivers/base/devtmpfs.c:devtmpfs_delete_node
  - drivers/base/devtmpfs.c:devtmpfs_create_node
```
**Symbols:**

```
ffffffff817b5c40-ffffffff817b5d12: device_get_devnode (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
const char *device_get_devnode(struct device *dev, umode_t *mode, kuid_t *uid, kgid_t *gid, const char **tmp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/core.c (ffffffff817cb0b0)
Location: drivers/base/core.c:3365
Inline: False
Direct callers:
  - drivers/base/core.c:dev_uevent
  - drivers/base/devtmpfs.c:devtmpfs_delete_node
  - drivers/base/devtmpfs.c:devtmpfs_create_node
```
**Symbols:**

```
ffffffff817cb0b0-ffffffff817cb182: device_get_devnode (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
const char *device_get_devnode(struct device *dev, umode_t *mode, kuid_t *uid, kgid_t *gid, const char **tmp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/core.c (ffffffff817aea20)
Location: drivers/base/core.c:3592
Inline: False
Direct callers:
  - drivers/base/core.c:dev_uevent
  - drivers/base/devtmpfs.c:devtmpfs_delete_node
  - drivers/base/devtmpfs.c:devtmpfs_create_node
```
**Symbols:**

```
ffffffff817aea20-ffffffff817aeaf2: device_get_devnode (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
const char *device_get_devnode(struct device *dev, umode_t *mode, kuid_t *uid, kgid_t *gid, const char **tmp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/core.c (ffffffff81837c30)
Location: drivers/base/core.c:3657
Inline: False
Direct callers:
  - drivers/base/core.c:dev_uevent
  - drivers/base/devtmpfs.c:devtmpfs_delete_node
  - drivers/base/devtmpfs.c:devtmpfs_create_node
```
**Symbols:**

```
ffffffff81837c30-ffffffff81837d02: device_get_devnode (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
const char *device_get_devnode(struct device *dev, umode_t *mode, kuid_t *uid, kgid_t *gid, const char **tmp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/core.c (ffffffff81979f40)
Location: drivers/base/core.c:3691
Inline: False
Direct callers:
  - drivers/base/core.c:dev_uevent
  - drivers/base/devtmpfs.c:devtmpfs_delete_node
  - drivers/base/devtmpfs.c:devtmpfs_create_node
```
**Symbols:**

```
ffffffff81979f40-ffffffff8197a033: device_get_devnode (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
const char *device_get_devnode(struct device *dev, umode_t *mode, kuid_t *uid, kgid_t *gid, const char **tmp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/core.c (ffffffff81ae6d60)
Location: drivers/base/core.c:3890
Inline: False
Direct callers:
  - drivers/base/core.c:dev_uevent
  - drivers/base/devtmpfs.c:devtmpfs_delete_node
  - drivers/base/devtmpfs.c:devtmpfs_create_node
```
**Symbols:**

```
ffffffff81ae6d60-ffffffff81ae6e53: device_get_devnode (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
const char *device_get_devnode(const struct device *dev, umode_t *mode, kuid_t *uid, kgid_t *gid, const char **tmp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/core.c (ffffffff81b351b0)
Location: drivers/base/core.c:3899
Inline: False
Direct callers:
  - drivers/base/core.c:dev_uevent
  - drivers/base/devtmpfs.c:devtmpfs_delete_node
  - drivers/base/devtmpfs.c:devtmpfs_create_node
```
**Symbols:**

```
ffffffff81b351b0-ffffffff81b352a3: device_get_devnode (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
const char *device_get_devnode(const struct device *dev, umode_t *mode, kuid_t *uid, kgid_t *gid, const char **tmp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/core.c (ffffffff81b8cbe0)
Location: drivers/base/core.c:3913
Inline: False
Direct callers:
  - drivers/base/core.c:dev_uevent
  - drivers/base/devtmpfs.c:devtmpfs_delete_node
  - drivers/base/devtmpfs.c:devtmpfs_create_node
```
**Symbols:**

```
ffffffff81b8cbe0-ffffffff81b8cccf: device_get_devnode (STB_GLOBAL)
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
const char *device_get_devnode(struct device *dev, umode_t *mode, kuid_t *uid, kgid_t *gid, const char **tmp);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/core.c (ffff8000108e6c90)
Location: drivers/base/core.c:2452
Inline: True
Direct callers:
  - drivers/base/core.c:dev_uevent
  - drivers/base/devtmpfs.c:devtmpfs_delete_node
  - drivers/base/devtmpfs.c:devtmpfs_create_node
```
**Symbols:**

```
ffff8000108e6c90-ffff8000108e6d94: device_get_devnode (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
const char *device_get_devnode(struct device *dev, umode_t *mode, kuid_t *uid, kgid_t *gid, const char **tmp);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/core.c (c09d5264)
Location: drivers/base/core.c:2452
Inline: True
Direct callers:
  - drivers/base/core.c:dev_uevent
  - drivers/base/devtmpfs.c:devtmpfs_delete_node
  - drivers/base/devtmpfs.c:devtmpfs_create_node
```
**Symbols:**

```
c09d5264-c09d5348: device_get_devnode (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
const char *device_get_devnode(struct device *dev, umode_t *mode, kuid_t *uid, kgid_t *gid, const char **tmp);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/core.c (c00000000097cc80)
Location: drivers/base/core.c:2452
Inline: True
Direct callers:
  - drivers/base/core.c:dev_uevent
  - drivers/base/devtmpfs.c:devtmpfs_delete_node
  - drivers/base/devtmpfs.c:devtmpfs_create_node
```
**Symbols:**

```
c00000000097cc80-c00000000097cde8: device_get_devnode (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
const char *device_get_devnode(struct device *dev, umode_t *mode, kuid_t *uid, kgid_t *gid, const char **tmp);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/core.c (ffffffe00057b59e)
Location: drivers/base/core.c:2452
Inline: True
Direct callers:
  - drivers/base/core.c:dev_uevent
  - drivers/base/devtmpfs.c:devtmpfs_delete_node
  - drivers/base/devtmpfs.c:devtmpfs_create_node
```
**Symbols:**

```
ffffffe00057b59e-ffffffe00057b656: device_get_devnode (STB_GLOBAL)
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
const char *device_get_devnode(struct device *dev, umode_t *mode, kuid_t *uid, kgid_t *gid, const char **tmp);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/core.c (ffffffff816c1b10)
Location: drivers/base/core.c:2452
Inline: True
Direct callers:
  - drivers/base/core.c:dev_uevent
  - drivers/base/devtmpfs.c:devtmpfs_delete_node
  - drivers/base/devtmpfs.c:devtmpfs_create_node
```
**Symbols:**

```
ffffffff816c1b10-ffffffff816c1be2: device_get_devnode (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
const char *device_get_devnode(struct device *dev, umode_t *mode, kuid_t *uid, kgid_t *gid, const char **tmp);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/core.c (ffffffff8169cdc0)
Location: drivers/base/core.c:2452
Inline: True
Direct callers:
  - drivers/base/core.c:dev_uevent
  - drivers/base/devtmpfs.c:devtmpfs_delete_node
  - drivers/base/devtmpfs.c:devtmpfs_create_node
```
**Symbols:**

```
ffffffff8169cdc0-ffffffff8169ce92: device_get_devnode (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
const char *device_get_devnode(struct device *dev, umode_t *mode, kuid_t *uid, kgid_t *gid, const char **tmp);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/core.c (ffffffff816effe0)
Location: drivers/base/core.c:2452
Inline: True
Direct callers:
  - drivers/base/core.c:dev_uevent
  - drivers/base/devtmpfs.c:devtmpfs_delete_node
  - drivers/base/devtmpfs.c:devtmpfs_create_node
```
**Symbols:**

```
ffffffff816effe0-ffffffff816f00b2: device_get_devnode (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
const char *device_get_devnode(struct device *dev, umode_t *mode, kuid_t *uid, kgid_t *gid, const char **tmp);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/core.c (ffffffff8170a820)
Location: drivers/base/core.c:2452
Inline: True
Direct callers:
  - drivers/base/core.c:dev_uevent
  - drivers/base/devtmpfs.c:devtmpfs_delete_node
  - drivers/base/devtmpfs.c:devtmpfs_create_node
```
**Symbols:**

```
ffffffff8170a820-ffffffff8170a8f2: device_get_devnode (STB_GLOBAL)
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
<details>
<summary>Changed between <code>6.2</code> and <code>6.5</code> ⚠️</summary>
<ul>
<li>
<b>Param type changed. </b>
<code>struct device *dev</code> ➡️ <code>const struct device *dev</code>
</li>
</ul>
</details>
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
