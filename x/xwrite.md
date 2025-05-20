# Function: <code>xwrite</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
ssize_t xwrite(int fd, const char *p, size_t count);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In init/initramfs.c (ffffffff81f5bf12)
Location: init/initramfs.c:22
Inline: False
Direct callers:
  - init/initramfs.c:do_copy
  - init/initramfs.c:do_copy
```
**Symbols:**

```
ffffffff81f5bf12-ffffffff81f5bf6e: xwrite (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
ssize_t xwrite(int fd, const char *p, size_t count);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In init/initramfs.c (ffffffff81f83eb9)
Location: init/initramfs.c:22
Inline: False
Direct callers:
  - init/initramfs.c:do_copy
  - init/initramfs.c:do_copy
```
**Symbols:**

```
ffffffff81f83eb9-ffffffff81f83f15: xwrite (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
ssize_t xwrite(int fd, const char *p, size_t count);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In init/initramfs.c (ffffffff81fbf35b)
Location: init/initramfs.c:22
Inline: False
Direct callers:
  - init/initramfs.c:do_copy
  - init/initramfs.c:do_copy
```
**Symbols:**

```
ffffffff81fbf35b-ffffffff81fbf3b7: xwrite (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
ssize_t xwrite(int fd, const char *p, size_t count);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In init/initramfs.c (ffffffff8209f4c4)
Location: init/initramfs.c:23
Inline: False
```
**Symbols:**

```
ffffffff8209f4c4-ffffffff8209f525: xwrite (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
ssize_t xwrite(int fd, const char *p, size_t count);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In init/initramfs.c (ffffffff826a54c4)
Location: init/initramfs.c:24
Inline: False
```
**Symbols:**

```
ffffffff826a54c4-ffffffff826a5525: xwrite (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
ssize_t xwrite(int fd, const char *p, size_t count);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In init/initramfs.c (ffffffff826cea1c)
Location: init/initramfs.c:24
Inline: False
Direct callers:
  - init/initramfs.c:do_copy
  - init/initramfs.c:do_copy
```
**Symbols:**

```
ffffffff826cea1c-ffffffff826cea7d: xwrite (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
ssize_t xwrite(int fd, const char *p, size_t count);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In init/initramfs.c (ffffffff82884a5f)
Location: init/initramfs.c:14
Inline: False
Direct callers:
  - init/initramfs.c:do_copy
  - init/initramfs.c:do_copy
```
**Symbols:**

```
ffffffff82884a5f-ffffffff82884ac0: xwrite (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
ssize_t xwrite(int fd, const char *p, size_t count);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In init/initramfs.c (ffffffff8289baad)
Location: init/initramfs.c:14
Inline: False
Direct callers:
  - init/initramfs.c:do_copy
  - init/initramfs.c:do_copy
```
**Symbols:**

```
ffffffff8289baad-ffffffff8289bb0f: xwrite (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
ssize_t xwrite(int fd, const char *p, size_t count);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In init/initramfs.c (ffffffff8289ea92)
Location: init/initramfs.c:14
Inline: False
Direct callers:
  - init/initramfs.c:do_copy
  - init/initramfs.c:do_copy
```
**Symbols:**

```
ffffffff8289ea92-ffffffff8289eaf4: xwrite (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
ssize_t xwrite(int fd, const char *p, size_t count);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In init/initramfs.c (ffffffff82cc4b2d)
Location: init/initramfs.c:15
Inline: False
Direct callers:
  - init/initramfs.c:do_copy
  - init/initramfs.c:do_copy
```
**Symbols:**

```
ffffffff82cc4b2d-ffffffff82cc4b8f: xwrite (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In init/initramfs.c (ffffffff82fb08fa)
Location: init/initramfs.c:17
Inline: True
Direct callers:
  - init/initramfs.c:do_copy
  - init/initramfs.c:do_copy
```
**Symbols:**

```
ffffffff82fb08fa-ffffffff82fb0963: xwrite.constprop.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In init/initramfs.c (ffffffff831ba9a5)
Location: init/initramfs.c:19
Inline: True
Direct callers:
  - init/initramfs.c:do_copy
  - init/initramfs.c:do_copy
```
**Symbols:**

```
ffffffff831ba9a5-ffffffff831baa0e: xwrite.constprop.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In init/initramfs.c (ffffffff8329aeb0)
Location: init/initramfs.c:20
Inline: True
Direct callers:
  - init/initramfs.c:do_copy
  - init/initramfs.c:do_copy
```
**Symbols:**

```
ffffffff8329aeb0-ffffffff8329af19: xwrite.constprop.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In init/initramfs.c (ffffffff8344997c)
Location: init/initramfs.c:24
Inline: True
Direct callers:
  - init/initramfs.c:do_copy
  - init/initramfs.c:do_copy
```
**Symbols:**

```
ffffffff8344997c-ffffffff83449a4e: xwrite.constprop.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In init/initramfs.c (ffffffff83e634f0)
Location: init/initramfs.c:24
Inline: True
Direct callers:
  - init/initramfs.c:do_copy
  - init/initramfs.c:do_copy
```
**Symbols:**

```
ffffffff83e634f0-ffffffff83e635cd: xwrite.constprop.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In init/initramfs.c (ffffffff83683b10)
Location: init/initramfs.c:25
Inline: True
Direct callers:
  - init/initramfs.c:do_copy
  - init/initramfs.c:do_copy
```
**Symbols:**

```
ffffffff83683b10-ffffffff83683bed: xwrite.constprop.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In init/initramfs.c (ffffffff838b2c20)
Location: init/initramfs.c:25
Inline: True
Direct callers:
  - init/initramfs.c:do_copy
  - init/initramfs.c:do_copy
```
**Symbols:**

```
ffffffff838b2c20-ffffffff838b2cfd: xwrite.constprop.0 (STB_LOCAL)
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
ssize_t xwrite(int fd, const char *p, size_t count);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In init/initramfs.c (ffff800011432d18)
Location: init/initramfs.c:14
Inline: False
Direct callers:
  - init/initramfs.c:do_copy
  - init/initramfs.c:do_copy
```
**Symbols:**

```
ffff800011432d18-ffff800011432d9c: xwrite (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
ssize_t xwrite(int fd, const char *p, size_t count);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In init/initramfs.c (c1502e30)
Location: init/initramfs.c:14
Inline: False
Direct callers:
  - init/initramfs.c:do_copy
  - init/initramfs.c:do_copy
```
**Symbols:**

```
c1502e30-c1502ea4: xwrite (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
ssize_t xwrite(int fd, const char *p, size_t count);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In init/initramfs.c (c000000001346778)
Location: init/initramfs.c:14
Inline: False
Direct callers:
  - init/initramfs.c:do_copy
  - init/initramfs.c:do_copy
```
**Symbols:**

```
c000000001346778-c000000001346830: xwrite (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
ssize_t xwrite(int fd, const char *p, size_t count);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In init/initramfs.c (ffffffe00000281a)
Location: init/initramfs.c:14
Inline: False
Direct callers:
  - init/initramfs.c:do_copy
  - init/initramfs.c:do_copy
```
**Symbols:**

```
ffffffe00000281a-ffffffe00000288a: xwrite (STB_LOCAL)
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
ssize_t xwrite(int fd, const char *p, size_t count);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In init/initramfs.c (ffffffff8288ca92)
Location: init/initramfs.c:14
Inline: False
Direct callers:
  - init/initramfs.c:do_copy
  - init/initramfs.c:do_copy
```
**Symbols:**

```
ffffffff8288ca92-ffffffff8288caf4: xwrite (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
ssize_t xwrite(int fd, const char *p, size_t count);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In init/initramfs.c (ffffffff8288aa0f)
Location: init/initramfs.c:14
Inline: False
Direct callers:
  - init/initramfs.c:do_copy
  - init/initramfs.c:do_copy
```
**Symbols:**

```
ffffffff8288aa0f-ffffffff8288aa71: xwrite (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
ssize_t xwrite(int fd, const char *p, size_t count);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In init/initramfs.c (ffffffff8289fa92)
Location: init/initramfs.c:14
Inline: False
Direct callers:
  - init/initramfs.c:do_copy
  - init/initramfs.c:do_copy
```
**Symbols:**

```
ffffffff8289fa92-ffffffff8289faf4: xwrite (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
ssize_t xwrite(int fd, const char *p, size_t count);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In init/initramfs.c (ffffffff8289fa97)
Location: init/initramfs.c:14
Inline: False
Direct callers:
  - init/initramfs.c:do_copy
  - init/initramfs.c:do_copy
```
**Symbols:**

```
ffffffff8289fa97-ffffffff8289faf9: xwrite (STB_LOCAL)
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
