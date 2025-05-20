# Function: <code>fuse_copy_ioctl_iovec_old</code>

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
In fs/fuse/file.c (ffffffff81315e26)
Location: fs/fuse/file.c:2320
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_do_ioctl
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
In fs/fuse/file.c (ffffffff8134a79a)
Location: fs/fuse/file.c:2390
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_do_ioctl
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
In fs/fuse/file.c (ffffffff8135ffea)
Location: fs/fuse/file.c:2354
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_do_ioctl
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
In fs/fuse/file.c (ffffffff81374de2)
Location: fs/fuse/file.c:2347
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_do_ioctl
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
In fs/fuse/file.c (ffffffff81399a96)
Location: fs/fuse/file.c:2355
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_do_ioctl
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
In fs/fuse/file.c (ffffffff813c86e7)
Location: fs/fuse/file.c:2356
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_do_ioctl
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
In fs/fuse/file.c (ffffffff813e18cd)
Location: fs/fuse/file.c:2369
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_do_ioctl
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
In fs/fuse/file.c (ffffffff8140d5ea)
Location: fs/fuse/file.c:2435
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_do_ioctl
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
In fs/fuse/file.c (ffffffff8142898f)
Location: fs/fuse/file.c:2581
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_do_ioctl
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
In fs/fuse/file.c (ffffffff8147666f)
Location: fs/fuse/file.c:2598
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_do_ioctl
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
In fs/fuse/file.c (ffffffff814910c7)
Location: fs/fuse/file.c:2645
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_do_ioctl
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
In fs/fuse/ioctl.c (ffffffff814a1d38)
Location: fs/fuse/ioctl.c:18
Inline: True
Inline callers:
  - fs/fuse/ioctl.c:fuse_do_ioctl
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/fuse/ioctl.c (ffffffff814f9ddd)
Location: fs/fuse/ioctl.c:18
Inline: True
Inline callers:
  - fs/fuse/ioctl.c:fuse_do_ioctl
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/fuse/ioctl.c (ffffffff815899ef)
Location: fs/fuse/ioctl.c:29
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int fuse_copy_ioctl_iovec_old(struct iovec *dst, void *src, size_t transferred, unsigned int count, bool is_compat);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fuse/ioctl.c (ffffffff81630030)
Location: fs/fuse/ioctl.c:29
Inline: False
Direct callers:
  - fs/fuse/ioctl.c:fuse_do_ioctl
```
**Symbols:**

```
ffffffff81630030-ffffffff816300d8: fuse_copy_ioctl_iovec_old (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int fuse_copy_ioctl_iovec_old(struct iovec *dst, void *src, size_t transferred, unsigned int count, bool is_compat);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fuse/ioctl.c (ffffffff816680b0)
Location: fs/fuse/ioctl.c:38
Inline: False
Direct callers:
  - fs/fuse/ioctl.c:fuse_do_ioctl
```
**Symbols:**

```
ffffffff816680b0-ffffffff81668158: fuse_copy_ioctl_iovec_old (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int fuse_copy_ioctl_iovec_old(struct iovec *dst, void *src, size_t transferred, unsigned int count, bool is_compat);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fuse/ioctl.c (ffffffff816a23b0)
Location: fs/fuse/ioctl.c:38
Inline: False
Direct callers:
  - fs/fuse/ioctl.c:fuse_do_ioctl
```
**Symbols:**

```
ffffffff816a23b0-ffffffff816a2458: fuse_copy_ioctl_iovec_old (STB_LOCAL)
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
In fs/fuse/file.c (ffff80001050ad38)
Location: fs/fuse/file.c:2581
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_do_ioctl
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
In fs/fuse/file.c (c06c801c)
Location: fs/fuse/file.c:2581
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_do_ioctl
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
In fs/fuse/file.c (c000000000653188)
Location: fs/fuse/file.c:2581
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_do_ioctl
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
In fs/fuse/file.c (ffffffe000377366)
Location: fs/fuse/file.c:2581
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_do_ioctl
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
In fs/fuse/file.c (ffffffff81420f6f)
Location: fs/fuse/file.c:2581
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_do_ioctl
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
In fs/fuse/file.c (ffffffff814119ef)
Location: fs/fuse/file.c:2581
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_do_ioctl
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
In fs/fuse/file.c (ffffffff8141d10f)
Location: fs/fuse/file.c:2581
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_do_ioctl
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
In fs/fuse/file.c (ffffffff81433e99)
Location: fs/fuse/file.c:2581
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_do_ioctl
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>6.2</code> and <code>6.5</code> ✅
</li>
<li>
No changes between <code>6.5</code> and <code>6.8</code> ✅
</li>
</ul>
