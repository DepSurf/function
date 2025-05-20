# Function: <code>sync_file_fdget</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>4.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/dma-buf/sync_file.c (ffffffff815fd65b)
Location: drivers/dma-buf/sync_file.c:107
Inline: True
Inline callers:
  - drivers/dma-buf/sync_file.c:sync_file_ioctl
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
struct sync_file *sync_file_fdget(int fd);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/dma-buf/sync_file.c (ffffffff8162b380)
Location: drivers/dma-buf/sync_file.c:100
Inline: False
Direct callers:
  - drivers/dma-buf/sync_file.c:sync_file_ioctl
  - drivers/dma-buf/sync_file.c:sync_file_get_fence
```
**Symbols:**

```
ffffffff8162b380-ffffffff8162b3b6: sync_file_fdget (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
struct sync_file *sync_file_fdget(int fd);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/dma-buf/sync_file.c (ffffffff81640b60)
Location: drivers/dma-buf/sync_file.c:87
Inline: False
Direct callers:
  - drivers/dma-buf/sync_file.c:sync_file_ioctl
  - drivers/dma-buf/sync_file.c:sync_file_get_fence
```
**Symbols:**

```
ffffffff81640b60-ffffffff81640b96: sync_file_fdget (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
struct sync_file *sync_file_fdget(int fd);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/dma-buf/sync_file.c (ffffffff816a98e0)
Location: drivers/dma-buf/sync_file.c:87
Inline: False
Direct callers:
  - drivers/dma-buf/sync_file.c:sync_file_ioctl
  - drivers/dma-buf/sync_file.c:sync_file_get_fence
```
**Symbols:**

```
ffffffff816a98e0-ffffffff816a9916: sync_file_fdget (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
struct sync_file *sync_file_fdget(int fd);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/dma-buf/sync_file.c (ffffffff816e5df0)
Location: drivers/dma-buf/sync_file.c:87
Inline: False
Direct callers:
  - drivers/dma-buf/sync_file.c:sync_file_ioctl
  - drivers/dma-buf/sync_file.c:sync_file_get_fence
```
**Symbols:**

```
ffffffff816e5df0-ffffffff816e5e26: sync_file_fdget (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
struct sync_file *sync_file_fdget(int fd);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/dma-buf/sync_file.c (ffffffff81709180)
Location: drivers/dma-buf/sync_file.c:87
Inline: False
Direct callers:
  - drivers/dma-buf/sync_file.c:sync_file_ioctl
  - drivers/dma-buf/sync_file.c:sync_file_get_fence
```
**Symbols:**

```
ffffffff81709180-ffffffff817091b2: sync_file_fdget (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
struct sync_file *sync_file_fdget(int fd);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/dma-buf/sync_file.c (ffffffff81744930)
Location: drivers/dma-buf/sync_file.c:78
Inline: False
Direct callers:
  - drivers/dma-buf/sync_file.c:sync_file_ioctl
  - drivers/dma-buf/sync_file.c:sync_file_get_fence
```
**Symbols:**

```
ffffffff81744930-ffffffff81744962: sync_file_fdget (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
struct sync_file *sync_file_fdget(int fd);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/dma-buf/sync_file.c (ffffffff81768ae0)
Location: drivers/dma-buf/sync_file.c:78
Inline: False
Direct callers:
  - drivers/dma-buf/sync_file.c:sync_file_ioctl
  - drivers/dma-buf/sync_file.c:sync_file_get_fence
```
**Symbols:**

```
ffffffff81768ae0-ffffffff81768b12: sync_file_fdget (STB_LOCAL)
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
In drivers/dma-buf/sync_file.c (ffffffff8182b282)
Location: drivers/dma-buf/sync_file.c:78
Inline: True
Inline callers:
  - drivers/dma-buf/sync_file.c:sync_file_ioctl_merge
  - drivers/dma-buf/sync_file.c:sync_file_get_fence
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
In drivers/dma-buf/sync_file.c (ffffffff8183c002)
Location: drivers/dma-buf/sync_file.c:78
Inline: True
Inline callers:
  - drivers/dma-buf/sync_file.c:sync_file_ioctl_merge
  - drivers/dma-buf/sync_file.c:sync_file_get_fence
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
In drivers/dma-buf/sync_file.c (ffffffff8181f5c0)
Location: drivers/dma-buf/sync_file.c:78
Inline: True
Inline callers:
  - drivers/dma-buf/sync_file.c:sync_file_ioctl
  - drivers/dma-buf/sync_file.c:sync_file_get_fence
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
In drivers/dma-buf/sync_file.c (ffffffff818a9c60)
Location: drivers/dma-buf/sync_file.c:78
Inline: True
Inline callers:
  - drivers/dma-buf/sync_file.c:sync_file_ioctl
  - drivers/dma-buf/sync_file.c:sync_file_get_fence
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
In drivers/dma-buf/sync_file.c (ffffffff819f41bd)
Location: drivers/dma-buf/sync_file.c:79
Inline: True
Inline callers:
  - drivers/dma-buf/sync_file.c:sync_file_ioctl
  - drivers/dma-buf/sync_file.c:sync_file_get_fence
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
In drivers/dma-buf/sync_file.c (ffffffff81b7152d)
Location: drivers/dma-buf/sync_file.c:79
Inline: True
Inline callers:
  - drivers/dma-buf/sync_file.c:sync_file_ioctl
  - drivers/dma-buf/sync_file.c:sync_file_get_fence
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/dma-buf/sync_file.c (ffffffff81bc4d6f)
Location: drivers/dma-buf/sync_file.c:79
Inline: True
Inline callers:
  - drivers/dma-buf/sync_file.c:sync_file_ioctl
  - drivers/dma-buf/sync_file.c:sync_file_get_fence
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/dma-buf/sync_file.c (ffffffff81c19669)
Location: drivers/dma-buf/sync_file.c:79
Inline: True
Inline callers:
  - drivers/dma-buf/sync_file.c:sync_file_ioctl
  - drivers/dma-buf/sync_file.c:sync_file_get_fence
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
struct sync_file *sync_file_fdget(int fd);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/dma-buf/sync_file.c (ffff800010969da8)
Location: drivers/dma-buf/sync_file.c:78
Inline: False
Direct callers:
  - drivers/dma-buf/sync_file.c:sync_file_ioctl
  - drivers/dma-buf/sync_file.c:sync_file_get_fence
```
**Symbols:**

```
ffff800010969da8-ffff800010969e10: sync_file_fdget (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
struct sync_file *sync_file_fdget(int fd);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/dma-buf/sync_file.c (c0a3fea0)
Location: drivers/dma-buf/sync_file.c:78
Inline: False
Direct callers:
  - drivers/dma-buf/sync_file.c:sync_file_ioctl
  - drivers/dma-buf/sync_file.c:sync_file_get_fence
```
**Symbols:**

```
c0a3fea0-c0a3fef0: sync_file_fdget (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
struct sync_file *sync_file_fdget(int fd);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/dma-buf/sync_file.c (c000000000a22580)
Location: drivers/dma-buf/sync_file.c:78
Inline: False
Direct callers:
  - drivers/dma-buf/sync_file.c:sync_file_ioctl
  - drivers/dma-buf/sync_file.c:sync_file_get_fence
```
**Symbols:**

```
c000000000a22580-c000000000a22600: sync_file_fdget (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
struct sync_file *sync_file_fdget(int fd);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/dma-buf/sync_file.c (ffffffe0005d57a6)
Location: drivers/dma-buf/sync_file.c:78
Inline: False
Direct callers:
  - drivers/dma-buf/sync_file.c:sync_file_ioctl
  - drivers/dma-buf/sync_file.c:sync_file_get_fence
```
**Symbols:**

```
ffffffe0005d57a6-ffffffe0005d57fc: sync_file_fdget (STB_LOCAL)
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
struct sync_file *sync_file_fdget(int fd);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/dma-buf/sync_file.c (ffffffff8171d1d0)
Location: drivers/dma-buf/sync_file.c:78
Inline: False
Direct callers:
  - drivers/dma-buf/sync_file.c:sync_file_ioctl
  - drivers/dma-buf/sync_file.c:sync_file_get_fence
```
**Symbols:**

```
ffffffff8171d1d0-ffffffff8171d202: sync_file_fdget (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
struct sync_file *sync_file_fdget(int fd);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/dma-buf/sync_file.c (ffffffff816f6630)
Location: drivers/dma-buf/sync_file.c:78
Inline: False
Direct callers:
  - drivers/dma-buf/sync_file.c:sync_file_ioctl
  - drivers/dma-buf/sync_file.c:sync_file_get_fence
```
**Symbols:**

```
ffffffff816f6630-ffffffff816f6662: sync_file_fdget (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
struct sync_file *sync_file_fdget(int fd);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/dma-buf/sync_file.c (ffffffff8175bfa0)
Location: drivers/dma-buf/sync_file.c:78
Inline: False
Direct callers:
  - drivers/dma-buf/sync_file.c:sync_file_ioctl
  - drivers/dma-buf/sync_file.c:sync_file_get_fence
```
**Symbols:**

```
ffffffff8175bfa0-ffffffff8175bfd2: sync_file_fdget (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
struct sync_file *sync_file_fdget(int fd);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/dma-buf/sync_file.c (ffffffff81777640)
Location: drivers/dma-buf/sync_file.c:78
Inline: False
Direct callers:
  - drivers/dma-buf/sync_file.c:sync_file_ioctl
  - drivers/dma-buf/sync_file.c:sync_file_get_fence
```
**Symbols:**

```
ffffffff81777640-ffffffff81777672: sync_file_fdget (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
