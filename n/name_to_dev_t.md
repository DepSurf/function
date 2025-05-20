# Function: <code>name_to_dev_t</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
dev_t name_to_dev_t(const char *name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In init/do_mounts.c (ffffffff810022b0)
Location: init/do_mounts.c:210
Inline: False
Direct callers:
  - init/do_mounts.c:prepare_namespace
  - init/do_mounts.c:prepare_namespace
  - init/do_mounts_md.c:md_setup_drive
  - kernel/power/hibernate.c:resume_store
  - drivers/md/dm-table.c:dm_get_device
```
**Symbols:**

```
ffffffff810022b0-ffffffff81002705: name_to_dev_t (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
dev_t name_to_dev_t(const char *name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In init/do_mounts.c (ffffffff81002310)
Location: init/do_mounts.c:210
Inline: False
Direct callers:
  - init/do_mounts.c:prepare_namespace
  - init/do_mounts.c:prepare_namespace
  - init/do_mounts_md.c:md_setup_drive
  - kernel/power/hibernate.c:resume_store
  - kernel/power/hibernate.c:software_resume
  - kernel/power/hibernate.c:software_resume
  - kernel/power/hibernate.c:software_resume
  - drivers/md/dm-table.c:dm_get_dev_t
```
**Symbols:**

```
ffffffff81002310-ffffffff8100276a: name_to_dev_t (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
dev_t name_to_dev_t(const char *name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In init/do_mounts.c (ffffffff81002330)
Location: init/do_mounts.c:210
Inline: False
Direct callers:
  - init/do_mounts.c:prepare_namespace
  - init/do_mounts.c:prepare_namespace
  - init/do_mounts_md.c:md_setup_drive
  - kernel/power/hibernate.c:resume_store
  - kernel/power/hibernate.c:software_resume
  - kernel/power/hibernate.c:software_resume
  - kernel/power/hibernate.c:software_resume
  - drivers/md/dm-table.c:dm_get_dev_t
```
**Symbols:**

```
ffffffff81002330-ffffffff81002787: name_to_dev_t (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
dev_t name_to_dev_t(const char *name);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In init/do_mounts.c (ffffffff81002360)
Location: init/do_mounts.c:210
Inline: True
Direct callers:
  - init/do_mounts.c:prepare_namespace
  - init/do_mounts.c:prepare_namespace
  - init/do_mounts_md.c:md_setup_drive
  - kernel/power/hibernate.c:resume_store
  - kernel/power/hibernate.c:software_resume
  - kernel/power/hibernate.c:software_resume
  - kernel/power/hibernate.c:software_resume
  - drivers/md/dm-table.c:dm_get_dev_t
```
**Symbols:**

```
ffffffff81002360-ffffffff810027a0: name_to_dev_t (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
dev_t name_to_dev_t(const char *name);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In init/do_mounts.c (ffffffff81002390)
Location: init/do_mounts.c:210
Inline: True
Direct callers:
  - init/do_mounts.c:prepare_namespace
  - init/do_mounts.c:prepare_namespace
  - init/do_mounts_md.c:md_setup_drive
  - kernel/power/hibernate.c:resume_store
  - kernel/power/hibernate.c:software_resume
  - kernel/power/hibernate.c:software_resume
  - kernel/power/hibernate.c:software_resume
  - drivers/md/dm-table.c:dm_get_dev_t
```
**Symbols:**

```
ffffffff81002390-ffffffff810027d0: name_to_dev_t (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline, Transformation ⚠️</summary>

```c
dev_t name_to_dev_t(const char *name);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In init/do_mounts.c (0)
Location: init/do_mounts.c:210
Inline: True
Direct callers:
  - init/do_mounts.c:prepare_namespace
  - init/do_mounts.c:prepare_namespace
  - init/do_mounts_md.c:md_setup_drive
  - kernel/power/hibernate.c:resume_store
  - kernel/power/hibernate.c:software_resume
  - kernel/power/hibernate.c:software_resume
  - kernel/power/hibernate.c:software_resume
  - drivers/md/dm-table.c:dm_get_dev_t
```
**Symbols:**

```
ffffffff81002ec7-ffffffff81002efa: name_to_dev_t.cold.9 (STB_LOCAL)
ffffffff81002aa0-ffffffff81002ec7: name_to_dev_t (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline, Transformation ⚠️</summary>

```c
dev_t name_to_dev_t(const char *name);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In init/do_mounts.c (ffffffff81002b52)
Location: init/do_mounts.c:221
Inline: True
Direct callers:
  - init/do_mounts.c:prepare_namespace
  - init/do_mounts.c:prepare_namespace
  - init/do_mounts_md.c:md_setup_drive
  - kernel/power/hibernate.c:resume_store
  - kernel/power/hibernate.c:software_resume
  - kernel/power/hibernate.c:software_resume
  - kernel/power/hibernate.c:software_resume
  - drivers/md/dm-table.c:dm_get_dev_t
```
**Symbols:**

```
ffffffff81002f54-ffffffff81002f87: name_to_dev_t.cold.9 (STB_LOCAL)
ffffffff81002af0-ffffffff81002f54: name_to_dev_t (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline, Transformation ⚠️</summary>

```c
dev_t name_to_dev_t(const char *name);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In init/do_mounts.c (ffffffff81002c73)
Location: init/do_mounts.c:222
Inline: True
Direct callers:
  - init/do_mounts.c:prepare_namespace
  - init/do_mounts.c:prepare_namespace
  - init/do_mounts_md.c:md_setup_drive
  - kernel/power/hibernate.c:resume_store
  - kernel/power/hibernate.c:software_resume
  - kernel/power/hibernate.c:software_resume
  - kernel/power/hibernate.c:software_resume
  - drivers/md/dm-table.c:dm_get_dev_t
```
**Symbols:**

```
ffffffff81003081-ffffffff810030b4: name_to_dev_t.cold (STB_LOCAL)
ffffffff81002c10-ffffffff81003081: name_to_dev_t (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline, Transformation ⚠️</summary>

```c
dev_t name_to_dev_t(const char *name);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In init/do_mounts.c (ffffffff81002c63)
Location: init/do_mounts.c:222
Inline: True
Direct callers:
  - init/do_mounts.c:prepare_namespace
  - init/do_mounts.c:prepare_namespace
  - init/do_mounts_md.c:md_setup_drive
  - kernel/power/hibernate.c:resume_store
  - kernel/power/hibernate.c:software_resume
  - kernel/power/hibernate.c:software_resume
  - kernel/power/hibernate.c:software_resume
  - drivers/md/dm-table.c:dm_get_dev_t
```
**Symbols:**

```
ffffffff81003071-ffffffff810030a4: name_to_dev_t.cold (STB_LOCAL)
ffffffff81002c00-ffffffff81003071: name_to_dev_t (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline, Transformation ⚠️</summary>

```c
dev_t name_to_dev_t(const char *name);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In init/do_mounts.c (ffffffff81003e60)
Location: init/do_mounts.c:223
Inline: True
Direct callers:
  - init/do_mounts.c:prepare_namespace
  - init/do_mounts.c:prepare_namespace
  - init/do_mounts_md.c:md_setup_drive
  - kernel/power/hibernate.c:resume_store
  - kernel/power/hibernate.c:software_resume
  - kernel/power/hibernate.c:software_resume
  - kernel/power/hibernate.c:software_resume
  - drivers/md/dm-table.c:dm_get_device
```
**Symbols:**

```
ffffffff81003e60-ffffffff810041b6: name_to_dev_t.part.0 (STB_LOCAL)
ffffffff810041c0-ffffffff810041fb: name_to_dev_t (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline, Transformation ⚠️</summary>

```c
dev_t name_to_dev_t(const char *name);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In init/do_mounts.c (ffffffff81003f20)
Location: init/do_mounts.c:284
Inline: True
Direct callers:
  - init/do_mounts.c:prepare_namespace
  - init/do_mounts.c:prepare_namespace
  - kernel/power/hibernate.c:resume_store
  - drivers/md/md-autodetect.c:md_setup_drive
  - drivers/md/dm-table.c:dm_get_device
```
**Symbols:**

```
ffffffff81003f20-ffffffff81003fd4: name_to_dev_t.part.0 (STB_LOCAL)
ffffffff81003fe0-ffffffff81004057: name_to_dev_t (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
dev_t name_to_dev_t(const char *name);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In init/do_mounts.c (ffffffff81003e20)
Location: init/do_mounts.c:284
Inline: True
Direct callers:
  - init/do_mounts.c:prepare_namespace
  - init/do_mounts.c:prepare_namespace
  - kernel/power/hibernate.c:resume_store
  - drivers/md/md-autodetect.c:md_setup_drive
  - drivers/md/dm-table.c:dm_get_device
```
**Symbols:**

```
ffffffff81003e20-ffffffff81004012: name_to_dev_t (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
dev_t name_to_dev_t(const char *name);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In init/do_mounts.c (ffffffff81003e70)
Location: init/do_mounts.c:278
Inline: True
Direct callers:
  - init/do_mounts.c:prepare_namespace
  - init/do_mounts.c:prepare_namespace
  - kernel/power/hibernate.c:resume_store
  - drivers/md/md-autodetect.c:md_setup_drive
  - drivers/md/dm-table.c:dm_get_device
```
**Symbols:**

```
ffffffff81003e70-ffffffff81004062: name_to_dev_t (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
dev_t name_to_dev_t(const char *name);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In init/do_mounts.c (ffffffff81001b50)
Location: init/do_mounts.c:277
Inline: True
Direct callers:
  - init/do_mounts.c:prepare_namespace
  - init/do_mounts.c:prepare_namespace
  - kernel/power/hibernate.c:resume_store
  - drivers/md/md-autodetect.c:md_setup_drive
  - drivers/md/dm-table.c:dm_get_device
```
**Symbols:**

```
ffffffff81001b50-ffffffff81001d75: name_to_dev_t (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
dev_t name_to_dev_t(const char *name);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In init/do_mounts.c (ffffffff81002230)
Location: init/do_mounts.c:277
Inline: True
Direct callers:
  - init/do_mounts.c:prepare_namespace
  - init/do_mounts.c:prepare_namespace
  - kernel/power/hibernate.c:resume_store
  - drivers/md/md-autodetect.c:md_setup_drive
  - drivers/md/dm-table.c:dm_get_device
```
**Symbols:**

```
ffffffff81002230-ffffffff81002455: name_to_dev_t (STB_GLOBAL)
```
</details>
</li>
<li>
In <code>6.5</code>: Absent ⚠️
</li>
<li>
In <code>6.8</code>: Absent ⚠️
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Selective Inline ⚠️</summary>

```c
dev_t name_to_dev_t(const char *name);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In init/do_mounts.c (ffff800010085300)
Location: init/do_mounts.c:222
Inline: True
Direct callers:
  - init/do_mounts.c:prepare_namespace
  - init/do_mounts.c:prepare_namespace
  - init/do_mounts_md.c:md_setup_drive
  - drivers/md/dm-table.c:dm_get_dev_t
```
**Symbols:**

```
ffff800010085300-ffff8000100856f8: name_to_dev_t (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
dev_t name_to_dev_t(const char *name);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In init/do_mounts.c (c0303a84)
Location: init/do_mounts.c:222
Inline: True
Direct callers:
  - init/do_mounts.c:prepare_namespace
  - init/do_mounts.c:prepare_namespace
  - init/do_mounts_md.c:md_setup_drive
  - kernel/power/hibernate.c:resume_store
  - kernel/power/hibernate.c:software_resume
  - kernel/power/hibernate.c:software_resume
  - kernel/power/hibernate.c:software_resume
  - drivers/md/dm-table.c:dm_get_dev_t
```
**Symbols:**

```
c0303a84-c0303eac: name_to_dev_t (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
dev_t name_to_dev_t(const char *name);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In init/do_mounts.c (c000000000010aa0)
Location: init/do_mounts.c:222
Inline: True
Direct callers:
  - init/do_mounts.c:prepare_namespace
  - init/do_mounts.c:prepare_namespace
  - init/do_mounts_md.c:md_setup_drive
  - drivers/md/dm-table.c:dm_get_dev_t
```
**Symbols:**

```
c000000000010aa0-c000000000011344: name_to_dev_t (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
dev_t name_to_dev_t(const char *name);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In init/do_mounts.c (ffffffe0000b46d0)
Location: init/do_mounts.c:222
Inline: True
Direct callers:
  - init/do_mounts.c:prepare_namespace
  - init/do_mounts.c:prepare_namespace
  - init/do_mounts_md.c:md_setup_drive
  - drivers/md/dm-table.c:dm_get_dev_t
```
**Symbols:**

```
ffffffe0000b46d0-ffffffe0000b4aa2: name_to_dev_t (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Selective Inline, Transformation ⚠️</summary>

```c
dev_t name_to_dev_t(const char *name);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In init/do_mounts.c (ffffffff81002c63)
Location: init/do_mounts.c:222
Inline: True
Direct callers:
  - init/do_mounts.c:prepare_namespace
  - init/do_mounts.c:prepare_namespace
  - init/do_mounts_md.c:md_setup_drive
  - kernel/power/hibernate.c:resume_store
  - kernel/power/hibernate.c:software_resume
  - kernel/power/hibernate.c:software_resume
  - kernel/power/hibernate.c:software_resume
  - drivers/md/dm-table.c:dm_get_dev_t
```
**Symbols:**

```
ffffffff81003071-ffffffff810030a4: name_to_dev_t.cold (STB_LOCAL)
ffffffff81002c00-ffffffff81003071: name_to_dev_t (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline, Transformation ⚠️</summary>

```c
dev_t name_to_dev_t(const char *name);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In init/do_mounts.c (ffffffff81001143)
Location: init/do_mounts.c:222
Inline: True
Direct callers:
  - init/do_mounts.c:prepare_namespace
  - init/do_mounts.c:prepare_namespace
  - init/do_mounts_md.c:md_setup_drive
  - kernel/power/hibernate.c:resume_store
  - kernel/power/hibernate.c:software_resume
  - kernel/power/hibernate.c:software_resume
  - kernel/power/hibernate.c:software_resume
  - drivers/md/dm-table.c:dm_get_dev_t
```
**Symbols:**

```
ffffffff81001551-ffffffff81001584: name_to_dev_t.cold (STB_LOCAL)
ffffffff810010e0-ffffffff81001551: name_to_dev_t (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline, Transformation ⚠️</summary>

```c
dev_t name_to_dev_t(const char *name);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In init/do_mounts.c (ffffffff81002c63)
Location: init/do_mounts.c:222
Inline: True
Direct callers:
  - init/do_mounts.c:prepare_namespace
  - init/do_mounts.c:prepare_namespace
  - init/do_mounts_md.c:md_setup_drive
  - kernel/power/hibernate.c:resume_store
  - kernel/power/hibernate.c:software_resume
  - kernel/power/hibernate.c:software_resume
  - kernel/power/hibernate.c:software_resume
  - drivers/md/dm-table.c:dm_get_dev_t
```
**Symbols:**

```
ffffffff81003071-ffffffff810030a4: name_to_dev_t.cold (STB_LOCAL)
ffffffff81002c00-ffffffff81003071: name_to_dev_t (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline, Transformation ⚠️</summary>

```c
dev_t name_to_dev_t(const char *name);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In init/do_mounts.c (ffffffff81002cb3)
Location: init/do_mounts.c:222
Inline: True
Direct callers:
  - init/do_mounts.c:prepare_namespace
  - init/do_mounts.c:prepare_namespace
  - init/do_mounts_md.c:md_setup_drive
  - kernel/power/hibernate.c:resume_store
  - kernel/power/hibernate.c:software_resume
  - kernel/power/hibernate.c:software_resume
  - kernel/power/hibernate.c:software_resume
  - drivers/md/dm-table.c:dm_get_dev_t
```
**Symbols:**

```
ffffffff810030c1-ffffffff810030f4: name_to_dev_t.cold (STB_LOCAL)
ffffffff81002c50-ffffffff810030c1: name_to_dev_t (STB_GLOBAL)
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
