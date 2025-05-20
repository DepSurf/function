# Function: <code>sysfs_link_change_owner</code>

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
int sysfs_link_change_owner(struct kobject *kobj, struct kobject *targ, const char *name, kuid_t kuid, kgid_t kgid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/sysfs/file.c (ffffffff81387200)
Location: fs/sysfs/file.c:587
Inline: False
Direct callers:
  - drivers/base/core.c:device_change_owner
```
**Symbols:**

```
ffffffff81387200-ffffffff813872a8: sysfs_link_change_owner (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int sysfs_link_change_owner(struct kobject *kobj, struct kobject *targ, const char *name, kuid_t kuid, kgid_t kgid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/sysfs/file.c (ffffffff813d1e90)
Location: fs/sysfs/file.c:588
Inline: False
Direct callers:
  - drivers/base/core.c:device_change_owner
```
**Symbols:**

```
ffffffff813d1e90-ffffffff813d1f81: sysfs_link_change_owner (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int sysfs_link_change_owner(struct kobject *kobj, struct kobject *targ, const char *name, kuid_t kuid, kgid_t kgid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/sysfs/file.c (ffffffff813e3bf0)
Location: fs/sysfs/file.c:589
Inline: False
Direct callers:
  - drivers/base/core.c:device_change_owner
```
**Symbols:**

```
ffffffff813e3bf0-ffffffff813e3ce1: sysfs_link_change_owner (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int sysfs_link_change_owner(struct kobject *kobj, struct kobject *targ, const char *name, kuid_t kuid, kgid_t kgid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/sysfs/file.c (ffffffff813ea800)
Location: fs/sysfs/file.c:600
Inline: False
Direct callers:
  - drivers/base/core.c:device_change_owner
```
**Symbols:**

```
ffffffff813ea800-ffffffff813ea8f0: sysfs_link_change_owner (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int sysfs_link_change_owner(struct kobject *kobj, struct kobject *targ, const char *name, kuid_t kuid, kgid_t kgid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/sysfs/file.c (ffffffff8143c580)
Location: fs/sysfs/file.c:600
Inline: False
Direct callers:
  - drivers/base/core.c:device_change_owner
```
**Symbols:**

```
ffffffff8143c580-ffffffff8143c670: sysfs_link_change_owner (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int sysfs_link_change_owner(struct kobject *kobj, struct kobject *targ, const char *name, kuid_t kuid, kgid_t kgid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/sysfs/file.c (ffffffff814b7bb0)
Location: fs/sysfs/file.c:610
Inline: False
Direct callers:
  - drivers/base/core.c:device_change_owner
```
**Symbols:**

```
ffffffff814b7bb0-ffffffff814b7cd4: sysfs_link_change_owner (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int sysfs_link_change_owner(struct kobject *kobj, struct kobject *targ, const char *name, kuid_t kuid, kgid_t kgid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/sysfs/file.c (ffffffff8154f070)
Location: fs/sysfs/file.c:610
Inline: False
Direct callers:
  - drivers/base/core.c:device_change_owner
```
**Symbols:**

```
ffffffff8154f070-ffffffff8154f194: sysfs_link_change_owner (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int sysfs_link_change_owner(struct kobject *kobj, struct kobject *targ, const char *name, kuid_t kuid, kgid_t kgid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/sysfs/file.c (ffffffff81586d40)
Location: fs/sysfs/file.c:610
Inline: False
Direct callers:
  - drivers/base/core.c:device_change_owner
```
**Symbols:**

```
ffffffff81586d40-ffffffff81586e64: sysfs_link_change_owner (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int sysfs_link_change_owner(struct kobject *kobj, struct kobject *targ, const char *name, kuid_t kuid, kgid_t kgid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/sysfs/file.c (ffffffff815bf8a0)
Location: fs/sysfs/file.c:623
Inline: False
Direct callers:
  - drivers/base/core.c:device_change_owner
```
**Symbols:**

```
ffffffff815bf8a0-ffffffff815bf9c4: sysfs_link_change_owner (STB_GLOBAL)
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
int sysfs_link_change_owner(struct kobject *kobj, struct kobject *targ, const char *name, kuid_t kuid, kgid_t kgid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/sysfs/file.c (ffff800010456fc8)
Location: fs/sysfs/file.c:587
Inline: False
Direct callers:
  - drivers/base/core.c:device_change_owner
```
**Symbols:**

```
ffff800010456fc8-ffff800010457090: sysfs_link_change_owner (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int sysfs_link_change_owner(struct kobject *kobj, struct kobject *targ, const char *name, kuid_t kuid, kgid_t kgid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/sysfs/file.c (c0618fec)
Location: fs/sysfs/file.c:587
Inline: False
Direct callers:
  - drivers/base/core.c:device_change_owner
```
**Symbols:**

```
c0618fec-c0619098: sysfs_link_change_owner (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int sysfs_link_change_owner(struct kobject *kobj, struct kobject *targ, const char *name, kuid_t kuid, kgid_t kgid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/sysfs/file.c (c0000000005712a0)
Location: fs/sysfs/file.c:587
Inline: False
Direct callers:
  - drivers/base/core.c:device_change_owner
```
**Symbols:**

```
c0000000005712a0-c0000000005713c8: sysfs_link_change_owner (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int sysfs_link_change_owner(struct kobject *kobj, struct kobject *targ, const char *name, kuid_t kuid, kgid_t kgid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/sysfs/file.c (ffffffe0002e8576)
Location: fs/sysfs/file.c:587
Inline: False
Direct callers:
  - drivers/base/core.c:device_change_owner
```
**Symbols:**

```
ffffffe0002e8576-ffffffe0002e8612: sysfs_link_change_owner (STB_GLOBAL)
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
int sysfs_link_change_owner(struct kobject *kobj, struct kobject *targ, const char *name, kuid_t kuid, kgid_t kgid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/sysfs/file.c (ffffffff8137f7e0)
Location: fs/sysfs/file.c:587
Inline: False
Direct callers:
  - drivers/base/core.c:device_change_owner
```
**Symbols:**

```
ffffffff8137f7e0-ffffffff8137f888: sysfs_link_change_owner (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int sysfs_link_change_owner(struct kobject *kobj, struct kobject *targ, const char *name, kuid_t kuid, kgid_t kgid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/sysfs/file.c (ffffffff81370270)
Location: fs/sysfs/file.c:587
Inline: False
Direct callers:
  - drivers/base/core.c:device_change_owner
```
**Symbols:**

```
ffffffff81370270-ffffffff81370318: sysfs_link_change_owner (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int sysfs_link_change_owner(struct kobject *kobj, struct kobject *targ, const char *name, kuid_t kuid, kgid_t kgid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/sysfs/file.c (ffffffff8137d2b0)
Location: fs/sysfs/file.c:587
Inline: False
Direct callers:
  - drivers/base/core.c:device_change_owner
```
**Symbols:**

```
ffffffff8137d2b0-ffffffff8137d358: sysfs_link_change_owner (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int sysfs_link_change_owner(struct kobject *kobj, struct kobject *targ, const char *name, kuid_t kuid, kgid_t kgid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/sysfs/file.c (ffffffff81390d90)
Location: fs/sysfs/file.c:587
Inline: False
Direct callers:
  - drivers/base/core.c:device_change_owner
```
**Symbols:**

```
ffffffff81390d90-ffffffff81390e38: sysfs_link_change_owner (STB_GLOBAL)
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
