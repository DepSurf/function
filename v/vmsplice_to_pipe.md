# Function: <code>vmsplice_to_pipe</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
long int vmsplice_to_pipe(struct file *file, const struct iovec *iov, long unsigned int nr_segs, unsigned int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/splice.c (ffffffff8123f320)
Location: fs/splice.c:1591
Inline: False
Direct callers:
  - fs/splice.c:compat_SyS_vmsplice
```
**Symbols:**

```
ffffffff8123f320-ffffffff8123f5b0: vmsplice_to_pipe (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
long int vmsplice_to_pipe(struct file *file, const struct iovec *iov, long unsigned int nr_segs, unsigned int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/splice.c (ffffffff81267640)
Location: fs/splice.c:1595
Inline: False
Direct callers:
  - fs/splice.c:compat_SyS_vmsplice
```
**Symbols:**

```
ffffffff81267640-ffffffff812678ef: vmsplice_to_pipe (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
long int vmsplice_to_pipe(struct file *file, const struct iovec *uiov, long unsigned int nr_segs, unsigned int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/splice.c (ffffffff8127a110)
Location: fs/splice.c:1307
Inline: False
Direct callers:
  - fs/splice.c:compat_SyS_vmsplice
```
**Symbols:**

```
ffffffff8127a110-ffffffff8127a226: vmsplice_to_pipe (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
long int vmsplice_to_pipe(struct file *file, const struct iovec *uiov, long unsigned int nr_segs, unsigned int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/splice.c (ffffffff81287610)
Location: fs/splice.c:1303
Inline: False
Direct callers:
  - fs/splice.c:compat_SyS_vmsplice
```
**Symbols:**

```
ffffffff81287610-ffffffff81287735: vmsplice_to_pipe (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
long int vmsplice_to_pipe(struct file *file, const struct iovec *uiov, long unsigned int nr_segs, unsigned int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/splice.c (ffffffff812a9f50)
Location: fs/splice.c:1287
Inline: False
Direct callers:
  - fs/splice.c:compat_SyS_vmsplice
```
**Symbols:**

```
ffffffff812a9f50-ffffffff812aa075: vmsplice_to_pipe (STB_LOCAL)
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
In fs/splice.c (ffffffff812d12bd)
Location: fs/splice.c:1276
Inline: True
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
In fs/splice.c (ffffffff812e676d)
Location: fs/splice.c:1280
Inline: True
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
In fs/splice.c (ffffffff813053ef)
Location: fs/splice.c:1286
Inline: True
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
In fs/splice.c (ffffffff8131847f)
Location: fs/splice.c:1294
Inline: True
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
In fs/splice.c (ffffffff81351346)
Location: fs/splice.c:1282
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
long int vmsplice_to_pipe(struct file *file, struct iov_iter *iter, unsigned int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/splice.c (ffffffff8135dbb0)
Location: fs/splice.c:1236
Inline: False
Direct callers:
  - fs/splice.c:__do_sys_vmsplice
```
**Symbols:**

```
ffffffff8135dbb0-ffffffff8135dc86: vmsplice_to_pipe (STB_LOCAL)
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
In fs/splice.c (ffffffff81364cf9)
Location: fs/splice.c:1241
Inline: True
Inline callers:
  - fs/splice.c:__do_sys_vmsplice
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
In fs/splice.c (ffffffff813b3255)
Location: fs/splice.c:1243
Inline: True
Inline callers:
  - fs/splice.c:__do_sys_vmsplice
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
In fs/splice.c (ffffffff81438378)
Location: fs/splice.c:1239
Inline: True
Inline callers:
  - fs/splice.c:__do_sys_vmsplice
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/splice.c (ffffffff814c681f)
Location: fs/splice.c:1239
Inline: True
Inline callers:
  - fs/splice.c:__do_sys_vmsplice
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
long int vmsplice_to_pipe(struct file *file, struct iov_iter *iter, unsigned int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/splice.c (ffffffff814fbcb0)
Location: fs/splice.c:1476
Inline: False
Direct callers:
  - fs/splice.c:__do_sys_vmsplice
```
**Symbols:**

```
ffffffff814fbcb0-ffffffff814fbe43: vmsplice_to_pipe (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
ssize_t vmsplice_to_pipe(struct file *file, struct iov_iter *iter, unsigned int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/splice.c (ffffffff81530ab0)
Location: fs/splice.c:1539
Inline: False
Direct callers:
  - fs/splice.c:__do_sys_vmsplice
```
**Symbols:**

```
ffffffff81530ab0-ffffffff81530c25: vmsplice_to_pipe (STB_LOCAL)
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
In fs/splice.c (ffff8000103ce55c)
Location: fs/splice.c:1294
Inline: True
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
In fs/splice.c (c05a9d44)
Location: fs/splice.c:1294
Inline: True
Inline callers:
  - fs/splice.c:__do_sys_vmsplice
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
In fs/splice.c (c0000000004d1944)
Location: fs/splice.c:1294
Inline: True
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
In fs/splice.c (ffffffe00028b5d2)
Location: fs/splice.c:1294
Inline: True
Inline callers:
  - fs/splice.c:__do_sys_vmsplice
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
In fs/splice.c (ffffffff81310a5f)
Location: fs/splice.c:1294
Inline: True
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
In fs/splice.c (ffffffff8130166f)
Location: fs/splice.c:1294
Inline: True
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
In fs/splice.c (ffffffff8130e84f)
Location: fs/splice.c:1294
Inline: True
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
In fs/splice.c (ffffffff8132004f)
Location: fs/splice.c:1294
Inline: True
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
<details>
<summary>Changed between <code>4.8</code> and <code>4.10</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>const struct iovec *uiov</code>
</li>
<li>
<b>Param removed. </b>
<code>const struct iovec *iov</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>4.10</code> and <code>4.13</code> ✅
</li>
<li>
No changes between <code>4.13</code> and <code>4.15</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>6.5</code> and <code>6.8</code> ⚠️</summary>
<ul>
<li>
<b>Return type changed. </b>
<code>long int</code> ➡️ <code>ssize_t</code>
</li>
</ul>
</details>
</li>
</ul>
