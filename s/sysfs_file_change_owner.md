# Function: <code>sysfs_file_change_owner</code>

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
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int sysfs_file_change_owner(struct kobject *kobj, const char *name, kuid_t kuid, kgid_t kgid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/sysfs/file.c (ffffffff81386a50)
Location: fs/sysfs/file.c:626
Inline: False
Direct callers:
  - fs/sysfs/file.c:sysfs_change_owner
  - drivers/base/core.c:device_change_owner
  - drivers/base/core.c:device_change_owner
```
**Symbols:**

```
ffffffff81386a50-ffffffff81386ab7: sysfs_file_change_owner (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int sysfs_file_change_owner(struct kobject *kobj, const char *name, kuid_t kuid, kgid_t kgid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/sysfs/file.c (ffffffff813d1910)
Location: fs/sysfs/file.c:627
Inline: False
Direct callers:
  - fs/sysfs/file.c:sysfs_change_owner
  - drivers/base/core.c:device_change_owner
  - drivers/base/core.c:device_change_owner
```
**Symbols:**

```
ffffffff813d1910-ffffffff813d19b9: sysfs_file_change_owner (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int sysfs_file_change_owner(struct kobject *kobj, const char *name, kuid_t kuid, kgid_t kgid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/sysfs/file.c (ffffffff813e3670)
Location: fs/sysfs/file.c:628
Inline: False
Direct callers:
  - fs/sysfs/file.c:sysfs_change_owner
  - drivers/base/core.c:device_change_owner
  - drivers/base/core.c:device_change_owner
```
**Symbols:**

```
ffffffff813e3670-ffffffff813e3719: sysfs_file_change_owner (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int sysfs_file_change_owner(struct kobject *kobj, const char *name, kuid_t kuid, kgid_t kgid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/sysfs/file.c (ffffffff813ea290)
Location: fs/sysfs/file.c:639
Inline: False
Direct callers:
  - fs/sysfs/file.c:sysfs_change_owner
  - drivers/base/core.c:device_change_owner
  - drivers/base/core.c:device_change_owner
```
**Symbols:**

```
ffffffff813ea290-ffffffff813ea339: sysfs_file_change_owner (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int sysfs_file_change_owner(struct kobject *kobj, const char *name, kuid_t kuid, kgid_t kgid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/sysfs/file.c (ffffffff8143c010)
Location: fs/sysfs/file.c:639
Inline: False
Direct callers:
  - fs/sysfs/file.c:sysfs_change_owner
  - drivers/base/core.c:device_change_owner
  - drivers/base/core.c:device_change_owner
```
**Symbols:**

```
ffffffff8143c010-ffffffff8143c0b9: sysfs_file_change_owner (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int sysfs_file_change_owner(struct kobject *kobj, const char *name, kuid_t kuid, kgid_t kgid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/sysfs/file.c (ffffffff814b74e0)
Location: fs/sysfs/file.c:649
Inline: False
Direct callers:
  - drivers/base/core.c:device_change_owner
  - drivers/base/core.c:device_change_owner
```
**Symbols:**

```
ffffffff814b74e0-ffffffff814b75b0: sysfs_file_change_owner (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int sysfs_file_change_owner(struct kobject *kobj, const char *name, kuid_t kuid, kgid_t kgid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/sysfs/file.c (ffffffff8154e920)
Location: fs/sysfs/file.c:649
Inline: False
Direct callers:
  - drivers/base/core.c:device_change_owner
  - drivers/base/core.c:device_change_owner
```
**Symbols:**

```
ffffffff8154e920-ffffffff8154e9f0: sysfs_file_change_owner (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int sysfs_file_change_owner(struct kobject *kobj, const char *name, kuid_t kuid, kgid_t kgid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/sysfs/file.c (ffffffff815865f0)
Location: fs/sysfs/file.c:649
Inline: False
Direct callers:
  - drivers/base/core.c:device_change_owner
  - drivers/base/core.c:device_change_owner
```
**Symbols:**

```
ffffffff815865f0-ffffffff815866c0: sysfs_file_change_owner (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int sysfs_file_change_owner(struct kobject *kobj, const char *name, kuid_t kuid, kgid_t kgid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/sysfs/file.c (ffffffff815bf150)
Location: fs/sysfs/file.c:662
Inline: False
Direct callers:
  - drivers/base/core.c:device_change_owner
  - drivers/base/core.c:device_change_owner
```
**Symbols:**

```
ffffffff815bf150-ffffffff815bf220: sysfs_file_change_owner (STB_GLOBAL)
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
int sysfs_file_change_owner(struct kobject *kobj, const char *name, kuid_t kuid, kgid_t kgid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/sysfs/file.c (ffff800010456650)
Location: fs/sysfs/file.c:626
Inline: False
Direct callers:
  - fs/sysfs/file.c:sysfs_change_owner
  - drivers/base/core.c:device_change_owner
  - drivers/base/core.c:device_change_owner
```
**Symbols:**

```
ffff800010456650-ffff8000104566d8: sysfs_file_change_owner (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int sysfs_file_change_owner(struct kobject *kobj, const char *name, kuid_t kuid, kgid_t kgid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/sysfs/file.c (c0618700)
Location: fs/sysfs/file.c:626
Inline: False
Direct callers:
  - fs/sysfs/file.c:sysfs_change_owner
  - drivers/base/core.c:device_change_owner
  - drivers/base/core.c:device_change_owner
```
**Symbols:**

```
c0618700-c0618778: sysfs_file_change_owner (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int sysfs_file_change_owner(struct kobject *kobj, const char *name, kuid_t kuid, kgid_t kgid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/sysfs/file.c (c0000000005704f0)
Location: fs/sysfs/file.c:626
Inline: False
Direct callers:
  - fs/sysfs/file.c:sysfs_change_owner
  - drivers/base/core.c:device_change_owner
  - drivers/base/core.c:device_change_owner
```
**Symbols:**

```
c0000000005704f0-c0000000005705b0: sysfs_file_change_owner (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int sysfs_file_change_owner(struct kobject *kobj, const char *name, kuid_t kuid, kgid_t kgid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/sysfs/file.c (ffffffe0002e7e18)
Location: fs/sysfs/file.c:626
Inline: False
Direct callers:
  - fs/sysfs/file.c:sysfs_change_owner
  - drivers/base/core.c:device_change_owner
  - drivers/base/core.c:device_change_owner
```
**Symbols:**

```
ffffffe0002e7e18-ffffffe0002e7e8c: sysfs_file_change_owner (STB_GLOBAL)
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
int sysfs_file_change_owner(struct kobject *kobj, const char *name, kuid_t kuid, kgid_t kgid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/sysfs/file.c (ffffffff8137f030)
Location: fs/sysfs/file.c:626
Inline: False
Direct callers:
  - fs/sysfs/file.c:sysfs_change_owner
  - drivers/base/core.c:device_change_owner
  - drivers/base/core.c:device_change_owner
```
**Symbols:**

```
ffffffff8137f030-ffffffff8137f097: sysfs_file_change_owner (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int sysfs_file_change_owner(struct kobject *kobj, const char *name, kuid_t kuid, kgid_t kgid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/sysfs/file.c (ffffffff8136fac0)
Location: fs/sysfs/file.c:626
Inline: False
Direct callers:
  - fs/sysfs/file.c:sysfs_change_owner
  - drivers/base/core.c:device_change_owner
  - drivers/base/core.c:device_change_owner
```
**Symbols:**

```
ffffffff8136fac0-ffffffff8136fb27: sysfs_file_change_owner (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int sysfs_file_change_owner(struct kobject *kobj, const char *name, kuid_t kuid, kgid_t kgid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/sysfs/file.c (ffffffff8137cb00)
Location: fs/sysfs/file.c:626
Inline: False
Direct callers:
  - fs/sysfs/file.c:sysfs_change_owner
  - drivers/base/core.c:device_change_owner
  - drivers/base/core.c:device_change_owner
```
**Symbols:**

```
ffffffff8137cb00-ffffffff8137cb67: sysfs_file_change_owner (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int sysfs_file_change_owner(struct kobject *kobj, const char *name, kuid_t kuid, kgid_t kgid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/sysfs/file.c (ffffffff813905e0)
Location: fs/sysfs/file.c:626
Inline: False
Direct callers:
  - fs/sysfs/file.c:sysfs_change_owner
  - drivers/base/core.c:device_change_owner
  - drivers/base/core.c:device_change_owner
```
**Symbols:**

```
ffffffff813905e0-ffffffff81390647: sysfs_file_change_owner (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
