# Function: <code>locks_lock_file_wait</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/locks.c (ffffffff812629d8)
Location: include/linux/fs.h:1185
Inline: True
Inline callers:
  - fs/locks.c:SyS_flock
```
```
In fs/fuse/file.c (ffffffff813179bb)
Location: include/linux/fs.h:1185
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/locks.c (ffffffff8128ebfb)
Location: include/linux/fs.h:1252
Inline: True
Inline callers:
  - fs/locks.c:SyS_flock
```
```
In fs/fuse/file.c (ffffffff8134c2cb)
Location: include/linux/fs.h:1252
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/locks.c (ffffffff812a3ba0)
Location: include/linux/fs.h:1217
Inline: True
Inline callers:
  - fs/locks.c:SyS_flock
```
```
In fs/fuse/file.c (ffffffff81361bdb)
Location: include/linux/fs.h:1217
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/locks.c (ffffffff812b2822)
Location: include/linux/fs.h:1239
Inline: True
Inline callers:
  - fs/locks.c:SyS_flock
```
```
In fs/fuse/file.c (ffffffff813765ab)
Location: include/linux/fs.h:1239
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/locks.c (ffffffff812d6386)
Location: include/linux/fs.h:1242
Inline: True
Inline callers:
  - fs/locks.c:SyS_flock
```
```
In fs/fuse/file.c (ffffffff8139b34b)
Location: include/linux/fs.h:1242
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/locks.c (ffffffff81300bf6)
Location: include/linux/fs.h:1250
Inline: True
Inline callers:
  - fs/locks.c:__ia32_sys_flock
  - fs/locks.c:__x64_sys_flock
```
```
In fs/fuse/file.c (ffffffff813ca274)
Location: include/linux/fs.h:1250
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/locks.c (ffffffff81316583)
Location: include/linux/fs.h:1293
Inline: True
Inline callers:
  - fs/locks.c:__ia32_sys_flock
  - fs/locks.c:__x64_sys_flock
```
```
In fs/fuse/file.c (ffffffff813e38c4)
Location: include/linux/fs.h:1293
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/locks.c (ffffffff8133ddb0)
Location: include/linux/fs.h:1308
Inline: True
Inline callers:
  - fs/locks.c:__ia32_sys_flock
  - fs/locks.c:__x64_sys_flock
```
```
In fs/fuse/file.c (ffffffff8140f8a4)
Location: include/linux/fs.h:1308
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/locks.c (ffffffff813563a0)
Location: include/linux/fs.h:1327
Inline: True
Inline callers:
  - fs/locks.c:__ia32_sys_flock
  - fs/locks.c:__x64_sys_flock
```
```
In fs/fuse/file.c (ffffffff81429374)
Location: include/linux/fs.h:1327
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/locks.c (ffffffff8139d1c0)
Location: include/linux/fs.h:1347
Inline: True
Inline callers:
  - fs/locks.c:__ia32_sys_flock
  - fs/locks.c:__x64_sys_flock
```
```
In fs/fuse/file.c (ffffffff81479d44)
Location: include/linux/fs.h:1347
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/locks.c (ffffffff813aeb90)
Location: include/linux/fs.h:1307
Inline: True
Inline callers:
  - fs/locks.c:__ia32_sys_flock
  - fs/locks.c:__x64_sys_flock
```
```
In fs/fuse/file.c (ffffffff81494bd7)
Location: include/linux/fs.h:1307
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/locks.c (ffffffff813b5eef)
Location: include/linux/fs.h:1312
Inline: True
Inline callers:
  - fs/locks.c:__ia32_sys_flock
  - fs/locks.c:__x64_sys_flock
```
```
In fs/fuse/file.c (ffffffff81499c37)
Location: include/linux/fs.h:1312
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/locks.c (ffffffff81405bef)
Location: include/linux/fs.h:1358
Inline: True
Inline callers:
  - fs/locks.c:__ia32_sys_flock
  - fs/locks.c:__x64_sys_flock
```
```
In fs/fuse/file.c (ffffffff814f1657)
Location: include/linux/fs.h:1358
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/locks.c (ffffffff8147a9a6)
Location: include/linux/fs.h:1325
Inline: True
Inline callers:
  - fs/locks.c:__do_sys_flock
```
```
In fs/fuse/file.c (ffffffff81580e17)
Location: include/linux/fs.h:1325
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/locks.c (ffffffff8150d370)
Location: include/linux/fs.h:1363
Inline: True
Inline callers:
  - fs/locks.c:__do_sys_flock
```
```
In fs/fuse/file.c (ffffffff81626c07)
Location: include/linux/fs.h:1363
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/locks.c (ffffffff81544b54)
Location: include/linux/filelock.h:344
Inline: True
Inline callers:
  - fs/locks.c:__do_sys_flock
```
```
In fs/fuse/file.c (ffffffff8165f1ca)
Location: include/linux/filelock.h:344
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/locks.c (ffffffff8157a044)
Location: include/linux/filelock.h:344
Inline: True
Inline callers:
  - fs/locks.c:__do_sys_flock
```
```
In fs/fuse/file.c (ffffffff8169900a)
Location: include/linux/filelock.h:344
Inline: True
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/locks.c (ffff800010418ee4)
Location: include/linux/fs.h:1327
Inline: True
Inline callers:
  - fs/locks.c:__arm64_sys_flock
```
```
In fs/fuse/file.c (ffff80001050d388)
Location: include/linux/fs.h:1327
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/locks.c (c05e5468)
Location: include/linux/fs.h:1327
Inline: True
Inline callers:
  - fs/locks.c:__se_sys_flock
```
```
In fs/fuse/file.c (c06c8a24)
Location: include/linux/fs.h:1327
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/locks.c (c0000000005280b0)
Location: include/linux/fs.h:1327
Inline: True
Inline callers:
  - fs/locks.c:__se_sys_flock
```
```
In fs/fuse/file.c (c000000000653f68)
Location: include/linux/fs.h:1327
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/locks.c (ffffffe0002bfc06)
Location: include/linux/fs.h:1327
Inline: True
Inline callers:
  - fs/locks.c:__se_sys_flock
```
```
In fs/fuse/file.c (ffffffe00037820e)
Location: include/linux/fs.h:1327
Inline: True
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/locks.c (ffffffff8134e980)
Location: include/linux/fs.h:1327
Inline: True
Inline callers:
  - fs/locks.c:__ia32_sys_flock
  - fs/locks.c:__x64_sys_flock
```
```
In fs/fuse/file.c (ffffffff81421954)
Location: include/linux/fs.h:1327
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/locks.c (ffffffff8133f660)
Location: include/linux/fs.h:1327
Inline: True
Inline callers:
  - fs/locks.c:__ia32_sys_flock
  - fs/locks.c:__x64_sys_flock
```
```
In fs/fuse/file.c (ffffffff814123d4)
Location: include/linux/fs.h:1327
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/locks.c (ffffffff8134c450)
Location: include/linux/fs.h:1327
Inline: True
Inline callers:
  - fs/locks.c:__ia32_sys_flock
  - fs/locks.c:__x64_sys_flock
```
```
In fs/fuse/file.c (ffffffff8141daf4)
Location: include/linux/fs.h:1327
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/locks.c (ffffffff8135ec40)
Location: include/linux/fs.h:1327
Inline: True
Inline callers:
  - fs/locks.c:__ia32_sys_flock
  - fs/locks.c:__x64_sys_flock
```
```
In fs/fuse/file.c (ffffffff81434854)
Location: include/linux/fs.h:1327
Inline: True
```
</details>
</li>
</ul>

## Differences
