# Function: <code>swsusp_free</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void swsusp_free();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/power/snapshot.c (ffffffff810d1420)
Location: kernel/power/snapshot.c:1324
Inline: False
Direct callers:
  - kernel/power/hibernate.c:hibernation_snapshot
  - kernel/power/hibernate.c:hibernation_snapshot
  - kernel/power/hibernate.c:hibernation_snapshot
  - kernel/power/hibernate.c:hibernate
  - kernel/power/snapshot.c:hibernate_preallocate_memory
  - kernel/power/snapshot.c:swsusp_save
  - kernel/power/snapshot.c:snapshot_write_next
  - kernel/power/user.c:snapshot_release
```
**Symbols:**

```
ffffffff810d1420-ffffffff810d15a4: swsusp_free (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void swsusp_free();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/power/snapshot.c (ffffffff810d6170)
Location: kernel/power/snapshot.c:1424
Inline: False
Direct callers:
  - kernel/power/hibernate.c:hibernate
  - kernel/power/hibernate.c:load_image_and_restore
  - kernel/power/hibernate.c:hibernation_snapshot
  - kernel/power/hibernate.c:hibernation_snapshot
  - kernel/power/hibernate.c:hibernation_snapshot
  - kernel/power/snapshot.c:snapshot_write_next
  - kernel/power/snapshot.c:swsusp_save
  - kernel/power/snapshot.c:hibernate_preallocate_memory
  - kernel/power/user.c:snapshot_release
```
**Symbols:**

```
ffffffff810d6170-ffffffff810d6321: swsusp_free (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void swsusp_free();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/power/snapshot.c (ffffffff810dccd0)
Location: kernel/power/snapshot.c:1446
Inline: False
Direct callers:
  - kernel/power/hibernate.c:hibernate
  - kernel/power/hibernate.c:load_image_and_restore
  - kernel/power/hibernate.c:hibernation_snapshot
  - kernel/power/hibernate.c:hibernation_snapshot
  - kernel/power/hibernate.c:hibernation_snapshot
  - kernel/power/snapshot.c:snapshot_write_next
  - kernel/power/snapshot.c:swsusp_save
  - kernel/power/snapshot.c:hibernate_preallocate_memory
  - kernel/power/user.c:snapshot_release
```
**Symbols:**

```
ffffffff810dccd0-ffffffff810dce81: swsusp_free (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void swsusp_free();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/power/snapshot.c (ffffffff810dbde0)
Location: kernel/power/snapshot.c:1448
Inline: False
Direct callers:
  - kernel/power/hibernate.c:hibernate
  - kernel/power/hibernate.c:load_image_and_restore
  - kernel/power/hibernate.c:hibernation_snapshot
  - kernel/power/hibernate.c:hibernation_snapshot
  - kernel/power/hibernate.c:hibernation_snapshot
  - kernel/power/hibernate.c:hibernation_snapshot
  - kernel/power/snapshot.c:snapshot_write_next
  - kernel/power/snapshot.c:swsusp_save
  - kernel/power/snapshot.c:hibernate_preallocate_memory
  - kernel/power/user.c:snapshot_ioctl
  - kernel/power/user.c:snapshot_release
```
**Symbols:**

```
ffffffff810dbde0-ffffffff810dbf9d: swsusp_free (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void swsusp_free();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/power/snapshot.c (ffffffff810e4000)
Location: kernel/power/snapshot.c:1450
Inline: False
Direct callers:
  - kernel/power/hibernate.c:hibernate
  - kernel/power/hibernate.c:load_image_and_restore
  - kernel/power/hibernate.c:hibernation_snapshot
  - kernel/power/hibernate.c:hibernation_snapshot
  - kernel/power/hibernate.c:hibernation_snapshot
  - kernel/power/hibernate.c:hibernation_snapshot
  - kernel/power/snapshot.c:snapshot_write_next
  - kernel/power/snapshot.c:swsusp_save
  - kernel/power/snapshot.c:hibernate_preallocate_memory
  - kernel/power/user.c:snapshot_ioctl
  - kernel/power/user.c:snapshot_release
```
**Symbols:**

```
ffffffff810e4000-ffffffff810e41b9: swsusp_free (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void swsusp_free();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/power/snapshot.c (ffffffff810ec370)
Location: kernel/power/snapshot.c:1450
Inline: False
Direct callers:
  - kernel/power/hibernate.c:hibernate
  - kernel/power/hibernate.c:load_image_and_restore
  - kernel/power/hibernate.c:hibernation_snapshot
  - kernel/power/hibernate.c:hibernation_snapshot
  - kernel/power/hibernate.c:hibernation_snapshot
  - kernel/power/hibernate.c:hibernation_snapshot
  - kernel/power/snapshot.c:snapshot_write_next
  - kernel/power/snapshot.c:swsusp_save
  - kernel/power/snapshot.c:hibernate_preallocate_memory
  - kernel/power/user.c:snapshot_ioctl
  - kernel/power/user.c:snapshot_release
```
**Symbols:**

```
ffffffff810ec370-ffffffff810ec530: swsusp_free (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void swsusp_free();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/power/snapshot.c (ffffffff810f7a10)
Location: kernel/power/snapshot.c:1451
Inline: False
Direct callers:
  - kernel/power/hibernate.c:hibernate
  - kernel/power/hibernate.c:load_image_and_restore
  - kernel/power/hibernate.c:hibernation_snapshot
  - kernel/power/hibernate.c:hibernation_snapshot
  - kernel/power/hibernate.c:hibernation_snapshot
  - kernel/power/hibernate.c:hibernation_snapshot
  - kernel/power/snapshot.c:snapshot_write_next
  - kernel/power/snapshot.c:swsusp_save
  - kernel/power/snapshot.c:hibernate_preallocate_memory
  - kernel/power/user.c:snapshot_ioctl
  - kernel/power/user.c:snapshot_release
```
**Symbols:**

```
ffffffff810f7a10-ffffffff810f7bd0: swsusp_free (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void swsusp_free();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/power/snapshot.c (ffffffff810fffb0)
Location: kernel/power/snapshot.c:1458
Inline: False
Direct callers:
  - kernel/power/hibernate.c:hibernate
  - kernel/power/hibernate.c:load_image_and_restore
  - kernel/power/hibernate.c:hibernation_snapshot
  - kernel/power/hibernate.c:hibernation_snapshot
  - kernel/power/hibernate.c:hibernation_snapshot
  - kernel/power/snapshot.c:snapshot_write_next
  - kernel/power/snapshot.c:swsusp_save
  - kernel/power/snapshot.c:hibernate_preallocate_memory
  - kernel/power/user.c:snapshot_ioctl
  - kernel/power/user.c:snapshot_release
```
**Symbols:**

```
ffffffff810fffb0-ffffffff811001c6: swsusp_free (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void swsusp_free();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/power/snapshot.c (ffffffff8110c410)
Location: kernel/power/snapshot.c:1465
Inline: False
Direct callers:
  - kernel/power/hibernate.c:hibernate
  - kernel/power/hibernate.c:load_image_and_restore
  - kernel/power/hibernate.c:hibernation_snapshot
  - kernel/power/hibernate.c:hibernation_snapshot
  - kernel/power/hibernate.c:hibernation_snapshot
  - kernel/power/snapshot.c:snapshot_write_next
  - kernel/power/snapshot.c:swsusp_save
  - kernel/power/snapshot.c:hibernate_preallocate_memory
  - kernel/power/user.c:snapshot_ioctl
  - kernel/power/user.c:snapshot_release
```
**Symbols:**

```
ffffffff8110c410-ffffffff8110c626: swsusp_free (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void swsusp_free();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/power/snapshot.c (ffffffff81117260)
Location: kernel/power/snapshot.c:1464
Inline: False
Direct callers:
  - kernel/power/hibernate.c:hibernate
  - kernel/power/hibernate.c:load_image_and_restore
  - kernel/power/hibernate.c:resume_target_kernel
  - kernel/power/hibernate.c:hibernation_snapshot
  - kernel/power/hibernate.c:hibernation_snapshot
  - kernel/power/hibernate.c:hibernation_snapshot
  - kernel/power/snapshot.c:swsusp_save
  - kernel/power/snapshot.c:hibernate_preallocate_memory
  - kernel/power/user.c:snapshot_ioctl
  - kernel/power/user.c:snapshot_release
```
**Symbols:**

```
ffffffff81117260-ffffffff81117494: swsusp_free (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void swsusp_free();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/power/snapshot.c (ffffffff811136a0)
Location: kernel/power/snapshot.c:1506
Inline: False
Direct callers:
  - kernel/power/hibernate.c:hibernate
  - kernel/power/hibernate.c:load_image_and_restore
  - kernel/power/hibernate.c:resume_target_kernel
  - kernel/power/hibernate.c:hibernation_snapshot
  - kernel/power/hibernate.c:hibernation_snapshot
  - kernel/power/hibernate.c:hibernation_snapshot
  - kernel/power/snapshot.c:swsusp_save
  - kernel/power/snapshot.c:hibernate_preallocate_memory
  - kernel/power/user.c:snapshot_ioctl
  - kernel/power/user.c:snapshot_release
```
**Symbols:**

```
ffffffff811136a0-ffffffff811138d4: swsusp_free (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void swsusp_free();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/power/snapshot.c (ffffffff81114070)
Location: kernel/power/snapshot.c:1506
Inline: False
Direct callers:
  - kernel/power/hibernate.c:hibernate
  - kernel/power/hibernate.c:load_image_and_restore
  - kernel/power/hibernate.c:hibernation_restore
  - kernel/power/hibernate.c:hibernation_snapshot
  - kernel/power/hibernate.c:hibernation_snapshot
  - kernel/power/hibernate.c:hibernation_snapshot
  - kernel/power/snapshot.c:swsusp_save
  - kernel/power/snapshot.c:hibernate_preallocate_memory
  - kernel/power/user.c:snapshot_ioctl
  - kernel/power/user.c:snapshot_release
```
**Symbols:**

```
ffffffff81114070-ffffffff81114200: swsusp_free (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
void swsusp_free();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/power/snapshot.c (0)
Location: kernel/power/snapshot.c:1499
Inline: False
Direct callers:
  - kernel/power/hibernate.c:hibernate
  - kernel/power/hibernate.c:load_image_and_restore
  - kernel/power/hibernate.c:hibernation_restore
  - kernel/power/hibernate.c:hibernation_snapshot
  - kernel/power/hibernate.c:hibernation_snapshot
  - kernel/power/hibernate.c:hibernation_snapshot
  - kernel/power/snapshot.c:swsusp_save
  - kernel/power/snapshot.c:hibernate_preallocate_memory
  - kernel/power/user.c:snapshot_ioctl
  - kernel/power/user.c:snapshot_release
```
**Symbols:**

```
ffffffff81caa775-ffffffff81caa789: swsusp_free.cold (STB_LOCAL)
ffffffff81134170-ffffffff81134336: swsusp_free (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
void swsusp_free();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/power/snapshot.c (0)
Location: kernel/power/snapshot.c:1503
Inline: False
Direct callers:
  - kernel/power/hibernate.c:hibernate
  - kernel/power/hibernate.c:load_image_and_restore
  - kernel/power/hibernate.c:resume_target_kernel
  - kernel/power/hibernate.c:hibernation_snapshot
  - kernel/power/hibernate.c:hibernation_snapshot
  - kernel/power/hibernate.c:hibernation_snapshot
  - kernel/power/hibernate.c:hibernation_snapshot
  - kernel/power/hibernate.c:hibernation_snapshot
  - kernel/power/snapshot.c:swsusp_save
  - kernel/power/snapshot.c:hibernate_preallocate_memory
  - kernel/power/user.c:snapshot_ioctl
  - kernel/power/user.c:snapshot_release
```
**Symbols:**

```
ffffffff81e5aba2-ffffffff81e5abb7: swsusp_free.cold (STB_LOCAL)
ffffffff81156260-ffffffff811564de: swsusp_free (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
void swsusp_free();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/power/snapshot.c (0)
Location: kernel/power/snapshot.c:1503
Inline: False
Direct callers:
  - kernel/power/hibernate.c:hibernate
  - kernel/power/hibernate.c:load_image_and_restore
  - kernel/power/hibernate.c:resume_target_kernel
  - kernel/power/hibernate.c:hibernation_snapshot
  - kernel/power/hibernate.c:hibernation_snapshot
  - kernel/power/hibernate.c:hibernation_snapshot
  - kernel/power/hibernate.c:hibernation_snapshot
  - kernel/power/hibernate.c:hibernation_snapshot
  - kernel/power/snapshot.c:swsusp_save
  - kernel/power/snapshot.c:hibernate_preallocate_memory
  - kernel/power/user.c:snapshot_ioctl
  - kernel/power/user.c:snapshot_release
```
**Symbols:**

```
ffffffff8205867f-ffffffff82058694: swsusp_free.cold (STB_LOCAL)
ffffffff81186860-ffffffff81186ade: swsusp_free (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
void swsusp_free();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/power/snapshot.c (0)
Location: kernel/power/snapshot.c:1555
Inline: False
Direct callers:
  - kernel/power/hibernate.c:hibernate
  - kernel/power/hibernate.c:load_image_and_restore
  - kernel/power/hibernate.c:resume_target_kernel
  - kernel/power/hibernate.c:hibernation_snapshot
  - kernel/power/hibernate.c:hibernation_snapshot
  - kernel/power/hibernate.c:hibernation_snapshot
  - kernel/power/hibernate.c:hibernation_snapshot
  - kernel/power/hibernate.c:hibernation_snapshot
  - kernel/power/snapshot.c:swsusp_save
  - kernel/power/snapshot.c:hibernate_preallocate_memory
  - kernel/power/user.c:snapshot_ioctl
  - kernel/power/user.c:snapshot_release
```
**Symbols:**

```
ffffffff820d6e12-ffffffff820d6e27: swsusp_free.cold (STB_LOCAL)
ffffffff811979d0-ffffffff81197c4e: swsusp_free (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
void swsusp_free();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/power/snapshot.c (0)
Location: kernel/power/snapshot.c:1598
Inline: False
Direct callers:
  - kernel/power/hibernate.c:hibernate
  - kernel/power/hibernate.c:load_image_and_restore
  - kernel/power/hibernate.c:resume_target_kernel
  - kernel/power/hibernate.c:hibernation_snapshot
  - kernel/power/hibernate.c:hibernation_snapshot
  - kernel/power/hibernate.c:hibernation_snapshot
  - kernel/power/hibernate.c:hibernation_snapshot
  - kernel/power/hibernate.c:hibernation_snapshot
  - kernel/power/snapshot.c:swsusp_save
  - kernel/power/snapshot.c:hibernate_preallocate_memory
  - kernel/power/user.c:snapshot_ioctl
  - kernel/power/user.c:snapshot_release
```
**Symbols:**

```
ffffffff821b20a9-ffffffff821b20be: swsusp_free.cold (STB_LOCAL)
ffffffff811a6650-ffffffff811a6910: swsusp_free (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
In <code>arm64</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void swsusp_free();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/power/snapshot.c (c03bebe8)
Location: kernel/power/snapshot.c:1465
Inline: False
Direct callers:
  - kernel/power/hibernate.c:hibernate
  - kernel/power/hibernate.c:load_image_and_restore
  - kernel/power/hibernate.c:hibernation_snapshot
  - kernel/power/hibernate.c:hibernation_snapshot
  - kernel/power/hibernate.c:hibernation_snapshot
  - kernel/power/snapshot.c:swsusp_save
  - kernel/power/snapshot.c:hibernate_preallocate_memory
  - kernel/power/user.c:snapshot_ioctl
  - kernel/power/user.c:snapshot_release
```
**Symbols:**

```
c03bebe8-c03bed74: swsusp_free (STB_GLOBAL)
```
</details>
</li>
<li>
In <code>ppc64el</code>: Absent ⚠️
</li>
<li>
In <code>riscv64</code>: Absent ⚠️
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: ✅</summary>

```c
void swsusp_free();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/power/snapshot.c (ffffffff81104630)
Location: kernel/power/snapshot.c:1464
Inline: False
Direct callers:
  - kernel/power/hibernate.c:hibernate
  - kernel/power/hibernate.c:load_image_and_restore
  - kernel/power/hibernate.c:hibernation_snapshot
  - kernel/power/hibernate.c:hibernation_snapshot
  - kernel/power/hibernate.c:hibernation_snapshot
  - kernel/power/snapshot.c:snapshot_write_next
  - kernel/power/snapshot.c:swsusp_save
  - kernel/power/snapshot.c:hibernate_preallocate_memory
  - kernel/power/user.c:snapshot_ioctl
  - kernel/power/user.c:snapshot_release
```
**Symbols:**

```
ffffffff81104630-ffffffff81104846: swsusp_free (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void swsusp_free();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/power/snapshot.c (ffffffff810f58d0)
Location: kernel/power/snapshot.c:1465
Inline: False
Direct callers:
  - kernel/power/hibernate.c:hibernate
  - kernel/power/hibernate.c:load_image_and_restore
  - kernel/power/hibernate.c:hibernation_snapshot
  - kernel/power/hibernate.c:hibernation_snapshot
  - kernel/power/hibernate.c:hibernation_snapshot
  - kernel/power/snapshot.c:snapshot_write_next
  - kernel/power/snapshot.c:swsusp_save
  - kernel/power/snapshot.c:hibernate_preallocate_memory
  - kernel/power/user.c:snapshot_ioctl
  - kernel/power/user.c:snapshot_release
```
**Symbols:**

```
ffffffff810f58d0-ffffffff810f5ae6: swsusp_free (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void swsusp_free();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/power/snapshot.c (ffffffff811028e0)
Location: kernel/power/snapshot.c:1465
Inline: False
Direct callers:
  - kernel/power/hibernate.c:hibernate
  - kernel/power/hibernate.c:load_image_and_restore
  - kernel/power/hibernate.c:hibernation_snapshot
  - kernel/power/hibernate.c:hibernation_snapshot
  - kernel/power/hibernate.c:hibernation_snapshot
  - kernel/power/snapshot.c:snapshot_write_next
  - kernel/power/snapshot.c:swsusp_save
  - kernel/power/snapshot.c:hibernate_preallocate_memory
  - kernel/power/user.c:snapshot_ioctl
  - kernel/power/user.c:snapshot_release
```
**Symbols:**

```
ffffffff811028e0-ffffffff81102af6: swsusp_free (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void swsusp_free();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/power/snapshot.c (ffffffff8110dcd0)
Location: kernel/power/snapshot.c:1465
Inline: False
Direct callers:
  - kernel/power/hibernate.c:hibernate
  - kernel/power/hibernate.c:load_image_and_restore
  - kernel/power/hibernate.c:hibernation_snapshot
  - kernel/power/hibernate.c:hibernation_snapshot
  - kernel/power/hibernate.c:hibernation_snapshot
  - kernel/power/snapshot.c:snapshot_write_next
  - kernel/power/snapshot.c:swsusp_save
  - kernel/power/snapshot.c:hibernate_preallocate_memory
  - kernel/power/user.c:snapshot_ioctl
  - kernel/power/user.c:snapshot_release
```
**Symbols:**

```
ffffffff8110dcd0-ffffffff8110dee6: swsusp_free (STB_GLOBAL)
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
No changes between <code>amd64</code> and <code>armhf</code> ✅
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
