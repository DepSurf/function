# Function: <code>kobject_set_name_vargs</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int kobject_set_name_vargs(struct kobject *kobj, const char *fmt, struct __va_list_tag *vargs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/kobject.c (ffffffff813ebd90)
Location: lib/kobject.c:257
Inline: False
Direct callers:
  - lib/kobject.c:kobject_set_name
  - lib/kobject.c:kobject_add
  - lib/kobject.c:kobject_init_and_add
  - drivers/iommu/iommu-sysfs.c:iommu_device_create
  - drivers/base/core.c:dev_set_name
  - drivers/base/core.c:device_create_groups_vargs
  - drivers/base/cpu.c:cpu_device_create
```
**Symbols:**

```
ffffffff813ebd90-ffffffff813ebe25: kobject_set_name_vargs (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int kobject_set_name_vargs(struct kobject *kobj, const char *fmt, struct __va_list_tag *vargs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/kobject.c (ffffffff81432140)
Location: lib/kobject.c:257
Inline: False
Direct callers:
  - lib/kobject.c:kobject_init_and_add
  - lib/kobject.c:kobject_add
  - lib/kobject.c:kobject_set_name
  - drivers/iommu/iommu-sysfs.c:iommu_device_create
  - drivers/base/core.c:device_create_groups_vargs
  - drivers/base/core.c:dev_set_name
  - drivers/base/cpu.c:cpu_device_create
```
**Symbols:**

```
ffffffff81432140-ffffffff814321cd: kobject_set_name_vargs (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int kobject_set_name_vargs(struct kobject *kobj, const char *fmt, struct __va_list_tag *vargs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/kobject.c (ffffffff8144e3b0)
Location: lib/kobject.c:257
Inline: False
Direct callers:
  - lib/kobject.c:kobject_init_and_add
  - lib/kobject.c:kobject_add
  - lib/kobject.c:kobject_set_name
  - drivers/iommu/iommu-sysfs.c:iommu_device_create
  - drivers/base/core.c:device_create_groups_vargs
  - drivers/base/core.c:dev_set_name
  - drivers/base/cpu.c:cpu_device_create
```
**Symbols:**

```
ffffffff8144e3b0-ffffffff8144e43d: kobject_set_name_vargs (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int kobject_set_name_vargs(struct kobject *kobj, const char *fmt, struct __va_list_tag *vargs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/kobject.c (ffffffff818ee650)
Location: lib/kobject.c:257
Inline: False
Direct callers:
  - drivers/iommu/iommu-sysfs.c:iommu_device_sysfs_add
  - drivers/base/core.c:device_create_groups_vargs
  - drivers/base/core.c:dev_set_name
  - drivers/base/cpu.c:cpu_device_create
  - lib/kobject.c:kobject_init_and_add
  - lib/kobject.c:kobject_add
  - lib/kobject.c:kobject_set_name
```
**Symbols:**

```
ffffffff818ee650-ffffffff818ee6e0: kobject_set_name_vargs (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int kobject_set_name_vargs(struct kobject *kobj, const char *fmt, struct __va_list_tag *vargs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/kobject.c (ffffffff81974910)
Location: lib/kobject.c:257
Inline: False
Direct callers:
  - drivers/iommu/iommu-sysfs.c:iommu_device_sysfs_add
  - drivers/base/core.c:device_create_groups_vargs
  - drivers/base/core.c:dev_set_name
  - drivers/base/cpu.c:cpu_device_create
  - lib/kobject.c:kobject_init_and_add
  - lib/kobject.c:kobject_add
  - lib/kobject.c:kobject_set_name
```
**Symbols:**

```
ffffffff81974910-ffffffff819749a0: kobject_set_name_vargs (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int kobject_set_name_vargs(struct kobject *kobj, const char *fmt, struct __va_list_tag *vargs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/kobject.c (ffffffff819d0f10)
Location: lib/kobject.c:273
Inline: False
Direct callers:
  - drivers/iommu/iommu-sysfs.c:iommu_device_sysfs_add
  - drivers/base/core.c:device_create_groups_vargs
  - drivers/base/core.c:dev_set_name
  - drivers/base/cpu.c:cpu_device_create
  - lib/kobject.c:kobject_init_and_add
  - lib/kobject.c:kobject_add
  - lib/kobject.c:kobject_set_name
```
**Symbols:**

```
ffffffff819d0f10-ffffffff819d0f9f: kobject_set_name_vargs (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int kobject_set_name_vargs(struct kobject *kobj, const char *fmt, struct __va_list_tag *vargs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/kobject.c (ffffffff81a0a470)
Location: lib/kobject.c:273
Inline: False
Direct callers:
  - drivers/iommu/iommu-sysfs.c:iommu_device_sysfs_add
  - drivers/base/core.c:device_create_groups_vargs
  - drivers/base/core.c:dev_set_name
  - drivers/base/cpu.c:cpu_device_create
  - lib/kobject.c:kobject_init_and_add
  - lib/kobject.c:kobject_add
  - lib/kobject.c:kobject_set_name
```
**Symbols:**

```
ffffffff81a0a470-ffffffff81a0a4ff: kobject_set_name_vargs (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int kobject_set_name_vargs(struct kobject *kobj, const char *fmt, struct __va_list_tag *vargs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/kobject.c (ffffffff81a79dd0)
Location: lib/kobject.c:281
Inline: False
Direct callers:
  - drivers/iommu/iommu-sysfs.c:iommu_device_sysfs_add
  - drivers/base/core.c:device_create_groups_vargs
  - drivers/base/core.c:dev_set_name
  - drivers/base/cpu.c:cpu_device_create
  - lib/kobject.c:kobject_init_and_add
  - lib/kobject.c:kobject_add
  - lib/kobject.c:kobject_set_name
```
**Symbols:**

```
ffffffff81a79dd0-ffffffff81a79e5c: kobject_set_name_vargs (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int kobject_set_name_vargs(struct kobject *kobj, const char *fmt, struct __va_list_tag *vargs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/kobject.c (ffffffff81ab1130)
Location: lib/kobject.c:281
Inline: False
Direct callers:
  - drivers/iommu/iommu-sysfs.c:iommu_device_sysfs_add
  - drivers/base/core.c:device_create_groups_vargs
  - drivers/base/core.c:dev_set_name
  - drivers/base/cpu.c:cpu_device_create
  - lib/kobject.c:kobject_init_and_add
  - lib/kobject.c:kobject_add
  - lib/kobject.c:kobject_set_name
```
**Symbols:**

```
ffffffff81ab1130-ffffffff81ab11bc: kobject_set_name_vargs (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int kobject_set_name_vargs(struct kobject *kobj, const char *fmt, struct __va_list_tag *vargs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/kobject.c (ffffffff815eb670)
Location: lib/kobject.c:281
Inline: False
Direct callers:
  - lib/kobject.c:kobject_init_and_add
  - lib/kobject.c:kobject_add
  - lib/kobject.c:kobject_set_name
  - drivers/iommu/iommu-sysfs.c:iommu_device_sysfs_add
  - drivers/base/core.c:device_create_groups_vargs
  - drivers/base/core.c:dev_set_name
  - drivers/base/cpu.c:__cpu_device_create
```
**Symbols:**

```
ffffffff815eb670-ffffffff815eb6fc: kobject_set_name_vargs (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int kobject_set_name_vargs(struct kobject *kobj, const char *fmt, struct __va_list_tag *vargs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/kobject.c (ffffffff8160ff90)
Location: lib/kobject.c:281
Inline: False
Direct callers:
  - lib/kobject.c:kobject_init_and_add
  - lib/kobject.c:kobject_add
  - lib/kobject.c:kobject_set_name
  - drivers/iommu/iommu-sysfs.c:iommu_device_sysfs_add
  - drivers/base/core.c:device_create_groups_vargs
  - drivers/base/core.c:dev_set_name
  - drivers/base/cpu.c:__cpu_device_create
```
**Symbols:**

```
ffffffff8160ff90-ffffffff8161001c: kobject_set_name_vargs (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int kobject_set_name_vargs(struct kobject *kobj, const char *fmt, struct __va_list_tag *vargs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/kobject.c (ffffffff815f36d0)
Location: lib/kobject.c:281
Inline: False
Direct callers:
  - lib/kobject.c:kobject_init_and_add
  - lib/kobject.c:kobject_add
  - lib/kobject.c:kobject_set_name
  - drivers/iommu/iommu-sysfs.c:iommu_device_sysfs_add
  - drivers/base/core.c:device_create_groups_vargs
  - drivers/base/core.c:dev_set_name
  - drivers/base/cpu.c:cpu_device_create
```
**Symbols:**

```
ffffffff815f36d0-ffffffff815f375c: kobject_set_name_vargs (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int kobject_set_name_vargs(struct kobject *kobj, const char *fmt, struct __va_list_tag *vargs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/kobject.c (ffffffff816608a0)
Location: lib/kobject.c:281
Inline: False
Direct callers:
  - lib/kobject.c:kobject_init_and_add
  - lib/kobject.c:kobject_add
  - lib/kobject.c:kobject_set_name
  - drivers/iommu/iommu-sysfs.c:iommu_device_sysfs_add
  - drivers/base/core.c:device_create_groups_vargs
  - drivers/base/core.c:dev_set_name
  - drivers/base/cpu.c:cpu_device_create
```
**Symbols:**

```
ffffffff816608a0-ffffffff8166092c: kobject_set_name_vargs (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int kobject_set_name_vargs(struct kobject *kobj, const char *fmt, struct __va_list_tag *vargs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/kobject.c (ffffffff8177a3c0)
Location: lib/kobject.c:249
Inline: False
Direct callers:
  - lib/kobject.c:kobject_init_and_add
  - lib/kobject.c:kobject_add
  - lib/kobject.c:kobject_set_name
  - drivers/iommu/iommu-sysfs.c:iommu_device_sysfs_add
  - drivers/base/core.c:device_create_groups_vargs
  - drivers/base/core.c:dev_set_name
  - drivers/base/cpu.c:cpu_device_create
```
**Symbols:**

```
ffffffff8177a3c0-ffffffff8177a454: kobject_set_name_vargs (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int kobject_set_name_vargs(struct kobject *kobj, const char *fmt, struct __va_list_tag *vargs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/kobject.c (ffffffff820234d0)
Location: lib/kobject.c:257
Inline: False
Direct callers:
  - drivers/iommu/iommu-sysfs.c:iommu_device_sysfs_add
  - drivers/base/core.c:device_create_groups_vargs
  - drivers/base/core.c:dev_set_name
  - drivers/base/cpu.c:cpu_device_create
  - lib/kobject.c:kobject_init_and_add
  - lib/kobject.c:kobject_add
  - lib/kobject.c:kobject_set_name
```
**Symbols:**

```
ffffffff820234d0-ffffffff82023564: kobject_set_name_vargs (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int kobject_set_name_vargs(struct kobject *kobj, const char *fmt, struct __va_list_tag *vargs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/kobject.c (ffffffff820a3540)
Location: lib/kobject.c:259
Inline: False
Direct callers:
  - drivers/iommu/iommu-sysfs.c:iommu_device_sysfs_add
  - drivers/base/core.c:device_create_groups_vargs
  - drivers/base/core.c:dev_set_name
  - drivers/base/cpu.c:cpu_device_create
  - lib/kobject.c:kobject_init_and_add
  - lib/kobject.c:kobject_add
  - lib/kobject.c:kobject_set_name
```
**Symbols:**

```
ffffffff820a3540-ffffffff820a35d4: kobject_set_name_vargs (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int kobject_set_name_vargs(struct kobject *kobj, const char *fmt, struct __va_list_tag *vargs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/kobject.c (ffffffff8217b5c0)
Location: lib/kobject.c:266
Inline: False
Direct callers:
  - drivers/iommu/iommu-sysfs.c:iommu_device_sysfs_add
  - drivers/base/core.c:device_create_groups_vargs
  - drivers/base/core.c:dev_set_name
  - drivers/base/cpu.c:cpu_device_create
  - lib/kobject.c:kobject_init_and_add
  - lib/kobject.c:kobject_add
  - lib/kobject.c:kobject_set_name
```
**Symbols:**

```
ffffffff8217b5c0-ffffffff8217b654: kobject_set_name_vargs (STB_GLOBAL)
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
int kobject_set_name_vargs(struct kobject *kobj, const char *fmt, va_list vargs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/kobject.c (ffff800010d8b4c8)
Location: lib/kobject.c:281
Inline: False
Direct callers:
  - drivers/iommu/iommu-sysfs.c:iommu_device_sysfs_add
  - drivers/base/core.c:device_create_groups_vargs
  - drivers/base/core.c:dev_set_name
  - drivers/base/cpu.c:cpu_device_create
  - lib/kobject.c:kobject_init_and_add
  - lib/kobject.c:kobject_add
  - lib/kobject.c:kobject_set_name
```
**Symbols:**

```
ffff800010d8b4c8-ffff800010d8b590: kobject_set_name_vargs (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int kobject_set_name_vargs(struct kobject *kobj, const char *fmt, va_list vargs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/kobject.c (c0e857e8)
Location: lib/kobject.c:281
Inline: False
Direct callers:
  - drivers/iommu/iommu-sysfs.c:iommu_device_sysfs_add
  - drivers/base/core.c:device_create_groups_vargs
  - drivers/base/core.c:dev_set_name
  - drivers/base/cpu.c:cpu_device_create
  - lib/kobject.c:kobject_init_and_add
  - lib/kobject.c:kobject_add
  - lib/kobject.c:kobject_set_name
```
**Symbols:**

```
c0e857e8-c0e8588c: kobject_set_name_vargs (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int kobject_set_name_vargs(struct kobject *kobj, const char *fmt, va_list vargs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/kobject.c (c000000000ecc7f0)
Location: lib/kobject.c:281
Inline: False
Direct callers:
  - drivers/iommu/iommu-sysfs.c:iommu_device_sysfs_add
  - drivers/base/core.c:device_create_groups_vargs
  - drivers/base/core.c:dev_set_name
  - drivers/base/cpu.c:cpu_device_create
  - lib/kobject.c:kobject_init_and_add
  - lib/kobject.c:kobject_add
  - lib/kobject.c:kobject_set_name
```
**Symbols:**

```
c000000000ecc7f0-c000000000ecc8e4: kobject_set_name_vargs (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int kobject_set_name_vargs(struct kobject *kobj, const char *fmt, va_list vargs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/kobject.c (ffffffe0008b4560)
Location: lib/kobject.c:281
Inline: False
Direct callers:
  - drivers/base/core.c:device_create_groups_vargs
  - drivers/base/core.c:dev_set_name
  - drivers/base/cpu.c:cpu_device_create
  - lib/kobject.c:kobject_init_and_add
  - lib/kobject.c:kobject_add
  - lib/kobject.c:kobject_set_name
```
**Symbols:**

```
ffffffe0008b4560-ffffffe0008b45fc: kobject_set_name_vargs (STB_GLOBAL)
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
int kobject_set_name_vargs(struct kobject *kobj, const char *fmt, struct __va_list_tag *vargs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/kobject.c (ffffffff81a4ff80)
Location: lib/kobject.c:281
Inline: False
Direct callers:
  - drivers/iommu/iommu-sysfs.c:iommu_device_sysfs_add
  - drivers/base/core.c:device_create_groups_vargs
  - drivers/base/core.c:dev_set_name
  - drivers/base/cpu.c:cpu_device_create
  - lib/kobject.c:kobject_init_and_add
  - lib/kobject.c:kobject_add
  - lib/kobject.c:kobject_set_name
```
**Symbols:**

```
ffffffff81a4ff80-ffffffff81a5000c: kobject_set_name_vargs (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int kobject_set_name_vargs(struct kobject *kobj, const char *fmt, struct __va_list_tag *vargs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/kobject.c (ffffffff81a0d080)
Location: lib/kobject.c:281
Inline: False
Direct callers:
  - drivers/iommu/iommu-sysfs.c:iommu_device_sysfs_add
  - drivers/base/core.c:device_create_groups_vargs
  - drivers/base/core.c:dev_set_name
  - drivers/base/cpu.c:cpu_device_create
  - lib/kobject.c:kobject_init_and_add
  - lib/kobject.c:kobject_add
  - lib/kobject.c:kobject_set_name
```
**Symbols:**

```
ffffffff81a0d080-ffffffff81a0d10c: kobject_set_name_vargs (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int kobject_set_name_vargs(struct kobject *kobj, const char *fmt, struct __va_list_tag *vargs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/kobject.c (ffffffff81abc370)
Location: lib/kobject.c:281
Inline: False
Direct callers:
  - drivers/iommu/iommu-sysfs.c:iommu_device_sysfs_add
  - drivers/base/core.c:device_create_groups_vargs
  - drivers/base/core.c:dev_set_name
  - drivers/base/cpu.c:cpu_device_create
  - lib/kobject.c:kobject_init_and_add
  - lib/kobject.c:kobject_add
  - lib/kobject.c:kobject_set_name
```
**Symbols:**

```
ffffffff81abc370-ffffffff81abc3fc: kobject_set_name_vargs (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int kobject_set_name_vargs(struct kobject *kobj, const char *fmt, struct __va_list_tag *vargs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/kobject.c (ffffffff81ac87f0)
Location: lib/kobject.c:281
Inline: False
Direct callers:
  - drivers/iommu/iommu-sysfs.c:iommu_device_sysfs_add
  - drivers/base/core.c:device_create_groups_vargs
  - drivers/base/core.c:dev_set_name
  - drivers/base/cpu.c:cpu_device_create
  - lib/kobject.c:kobject_init_and_add
  - lib/kobject.c:kobject_add
  - lib/kobject.c:kobject_set_name
```
**Symbols:**

```
ffffffff81ac87f0-ffffffff81ac887c: kobject_set_name_vargs (STB_GLOBAL)
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
<details>
<summary>Changed between <code>amd64</code> and <code>arm64</code> ⚠️</summary>
<ul>
<li>
<b>Param type changed. </b>
<code>struct __va_list_tag *vargs</code> ➡️ <code>va_list vargs</code>
</li>
</ul>
</details>
</li>
<li>
<details>
<summary>Changed between <code>amd64</code> and <code>armhf</code> ⚠️</summary>
<ul>
<li>
<b>Param type changed. </b>
<code>struct __va_list_tag *vargs</code> ➡️ <code>va_list vargs</code>
</li>
</ul>
</details>
</li>
<li>
<details>
<summary>Changed between <code>amd64</code> and <code>ppc64el</code> ⚠️</summary>
<ul>
<li>
<b>Param type changed. </b>
<code>struct __va_list_tag *vargs</code> ➡️ <code>va_list vargs</code>
</li>
</ul>
</details>
</li>
<li>
<details>
<summary>Changed between <code>amd64</code> and <code>riscv64</code> ⚠️</summary>
<ul>
<li>
<b>Param type changed. </b>
<code>struct __va_list_tag *vargs</code> ➡️ <code>va_list vargs</code>
</li>
</ul>
</details>
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
