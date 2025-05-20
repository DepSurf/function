# Function: <code>cant_mount</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/namespace.c (0)
Location: include/linux/dcache.h:383
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/namespace.c (0)
Location: include/linux/dcache.h:341
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/namespace.c (0)
Location: include/linux/dcache.h:341
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/namespace.c (0)
Location: include/linux/dcache.h:347
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/namespace.c (0)
Location: include/linux/dcache.h:348
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/namespace.c (ffffffff812bf6c0)
Location: include/linux/dcache.h:349
Inline: True
Inline callers:
  - fs/namespace.c:lock_mount
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/namespace.c (ffffffff812d48c0)
Location: include/linux/dcache.h:346
Inline: True
Inline callers:
  - fs/namespace.c:lock_mount
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/namespace.c (ffffffff812f1dc8)
Location: include/linux/dcache.h:344
Inline: True
Inline callers:
  - fs/namespace.c:lock_mount
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/namespace.c (ffffffff81303988)
Location: include/linux/dcache.h:344
Inline: True
Inline callers:
  - fs/namespace.c:lock_mount
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/namespace.c (ffffffff8133fa78)
Location: include/linux/dcache.h:346
Inline: True
Inline callers:
  - fs/namespace.c:finish_automount
  - fs/namespace.c:lock_mount
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/namespace.c (ffffffff8134bad8)
Location: include/linux/dcache.h:347
Inline: True
Inline callers:
  - fs/namespace.c:finish_automount
  - fs/namespace.c:lock_mount
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/namespace.c (ffffffff8135236b)
Location: include/linux/dcache.h:350
Inline: True
Inline callers:
  - fs/namespace.c:finish_automount
  - fs/namespace.c:lock_mount
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
In mm/swapfile.c (ffffffff81316f42)
Location: include/linux/dcache.h:350
Inline: True
Inline callers:
  - mm/swapfile.c:__do_sys_swapon
```
```
In fs/namespace.c (ffffffff813a0731)
Location: include/linux/dcache.h:350
Inline: True
Inline callers:
  - fs/namespace.c:finish_automount
  - fs/namespace.c:lock_mount
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
In mm/swapfile.c (ffffffff81382565)
Location: include/linux/dcache.h:340
Inline: True
Inline callers:
  - mm/swapfile.c:__do_sys_swapon
```
```
In fs/namespace.c (ffffffff8142404c)
Location: include/linux/dcache.h:340
Inline: True
Inline callers:
  - fs/namespace.c:finish_automount
  - fs/namespace.c:lock_mount
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
In mm/swapfile.c (ffffffff813fc4c6)
Location: include/linux/dcache.h:343
Inline: True
Inline callers:
  - mm/swapfile.c:__do_sys_swapon
```
```
In fs/namespace.c (ffffffff814b0798)
Location: include/linux/dcache.h:343
Inline: True
Inline callers:
  - fs/namespace.c:finish_automount
  - fs/namespace.c:lock_mount
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
In mm/swapfile.c (ffffffff8142f7d9)
Location: include/linux/dcache.h:343
Inline: True
Inline callers:
  - mm/swapfile.c:__do_sys_swapon
```
```
In fs/namespace.c (ffffffff814e57c5)
Location: include/linux/dcache.h:343
Inline: True
Inline callers:
  - fs/namespace.c:finish_automount
  - fs/namespace.c:do_lock_mount
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
In mm/swapfile.c (ffffffff814693ae)
Location: include/linux/dcache.h:350
Inline: True
Inline callers:
  - mm/swapfile.c:__do_sys_swapon
```
```
In fs/namespace.c (ffffffff815195f5)
Location: include/linux/dcache.h:350
Inline: True
Inline callers:
  - fs/namespace.c:finish_automount
  - fs/namespace.c:do_lock_mount
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/namespace.c (ffff8000103b6fd0)
Location: include/linux/dcache.h:344
Inline: True
Inline callers:
  - fs/namespace.c:lock_mount
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/namespace.c (c05956a4)
Location: include/linux/dcache.h:344
Inline: True
Inline callers:
  - fs/namespace.c:lock_mount
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/namespace.c (c0000000004b3988)
Location: include/linux/dcache.h:344
Inline: True
Inline callers:
  - fs/namespace.c:lock_mount
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/namespace.c (ffffffe000279c00)
Location: include/linux/dcache.h:344
Inline: True
Inline callers:
  - fs/namespace.c:lock_mount
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/namespace.c (ffffffff812fbf68)
Location: include/linux/dcache.h:344
Inline: True
Inline callers:
  - fs/namespace.c:lock_mount
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/namespace.c (ffffffff812ecb88)
Location: include/linux/dcache.h:344
Inline: True
Inline callers:
  - fs/namespace.c:lock_mount
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/namespace.c (ffffffff812f9d58)
Location: include/linux/dcache.h:344
Inline: True
Inline callers:
  - fs/namespace.c:lock_mount
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/namespace.c (ffffffff8130b0a8)
Location: include/linux/dcache.h:344
Inline: True
Inline callers:
  - fs/namespace.c:lock_mount
```
</details>
</li>
</ul>

## Differences
