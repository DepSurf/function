# Function: <code>cdev_put</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void cdev_put(struct cdev *p);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/char_dev.c (ffffffff81210ff0)
Location: fs/char_dev.c:335
Inline: False
Direct callers:
  - fs/file_table.c:__fput
  - fs/char_dev.c:chrdev_open
  - fs/char_dev.c:chrdev_open
```
**Symbols:**

```
ffffffff81210ff0-ffffffff81211014: cdev_put (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void cdev_put(struct cdev *p);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/char_dev.c (ffffffff81237ab0)
Location: fs/char_dev.c:339
Inline: False
Direct callers:
  - fs/file_table.c:__fput
  - fs/char_dev.c:chrdev_open
  - fs/char_dev.c:chrdev_open
```
**Symbols:**

```
ffffffff81237ab0-ffffffff81237ad4: cdev_put (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void cdev_put(struct cdev *p);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/char_dev.c (ffffffff8124a760)
Location: fs/char_dev.c:339
Inline: False
Direct callers:
  - fs/file_table.c:__fput
  - fs/char_dev.c:chrdev_open
  - fs/char_dev.c:chrdev_open
```
**Symbols:**

```
ffffffff8124a760-ffffffff8124a784: cdev_put (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline, Transformation ⚠️</summary>

```c
void cdev_put(struct cdev *p);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/char_dev.c (ffffffff81255d9b)
Location: fs/char_dev.c:339
Inline: True
Inline callers:
  - fs/char_dev.c:chrdev_open
  - fs/char_dev.c:chrdev_open
Direct callers:
  - fs/file_table.c:__fput
  - fs/char_dev.c:chrdev_open
  - fs/char_dev.c:chrdev_open
```
**Symbols:**

```
ffffffff81255d10-ffffffff81255d2e: cdev_put.part.3 (STB_LOCAL)
ffffffff81256310-ffffffff81256327: cdev_put (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline, Transformation ⚠️</summary>

```c
void cdev_put(struct cdev *p);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/char_dev.c (ffffffff81277f2b)
Location: fs/char_dev.c:364
Inline: True
Inline callers:
  - fs/char_dev.c:chrdev_open
  - fs/char_dev.c:chrdev_open
Direct callers:
  - fs/file_table.c:__fput
  - fs/char_dev.c:chrdev_open
  - fs/char_dev.c:chrdev_open
```
**Symbols:**

```
ffffffff81277ea0-ffffffff81277ebe: cdev_put.part.3 (STB_LOCAL)
ffffffff81278550-ffffffff81278567: cdev_put (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline, Transformation ⚠️</summary>

```c
void cdev_put(struct cdev *p);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/char_dev.c (ffffffff8129ed6b)
Location: fs/char_dev.c:364
Inline: True
Inline callers:
  - fs/char_dev.c:chrdev_open
  - fs/char_dev.c:chrdev_open
Direct callers:
  - fs/file_table.c:__fput
  - fs/char_dev.c:chrdev_open
  - fs/char_dev.c:chrdev_open
```
**Symbols:**

```
ffffffff8129e7f0-ffffffff8129e80e: cdev_put.part.3 (STB_LOCAL)
ffffffff8129ef50-ffffffff8129ef66: cdev_put (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline, Transformation ⚠️</summary>

```c
void cdev_put(struct cdev *p);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/char_dev.c (ffffffff812b3d55)
Location: fs/char_dev.c:364
Inline: True
Inline callers:
  - fs/char_dev.c:chrdev_open
  - fs/char_dev.c:chrdev_open
Direct callers:
  - fs/file_table.c:__fput
  - fs/char_dev.c:chrdev_open
  - fs/char_dev.c:chrdev_open
```
**Symbols:**

```
ffffffff812b3c00-ffffffff812b3c1e: cdev_put.part.3 (STB_LOCAL)
ffffffff812b3f30-ffffffff812b3f46: cdev_put (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline, Transformation ⚠️</summary>

```c
void cdev_put(struct cdev *p);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/char_dev.c (ffffffff812d0a65)
Location: fs/char_dev.c:361
Inline: True
Inline callers:
  - fs/char_dev.c:chrdev_open
  - fs/char_dev.c:chrdev_open
Direct callers:
  - fs/file_table.c:__fput
  - fs/char_dev.c:chrdev_open
  - fs/char_dev.c:chrdev_open
```
**Symbols:**

```
ffffffff812d0910-ffffffff812d0930: cdev_put.part.0 (STB_LOCAL)
ffffffff812d0c40-ffffffff812d0c56: cdev_put (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline, Transformation ⚠️</summary>

```c
void cdev_put(struct cdev *p);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/char_dev.c (ffffffff812e2615)
Location: fs/char_dev.c:361
Inline: True
Inline callers:
  - fs/char_dev.c:chrdev_open
  - fs/char_dev.c:chrdev_open
Direct callers:
  - fs/file_table.c:__fput
  - fs/char_dev.c:chrdev_open
  - fs/char_dev.c:chrdev_open
```
**Symbols:**

```
ffffffff812e24c0-ffffffff812e24e0: cdev_put.part.0 (STB_LOCAL)
ffffffff812e27f0-ffffffff812e2806: cdev_put (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
void cdev_put(struct cdev *p);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/char_dev.c (ffffffff8131993c)
Location: fs/char_dev.c:361
Inline: True
Inline callers:
  - fs/char_dev.c:chrdev_open
  - fs/char_dev.c:chrdev_open
  - fs/char_dev.c:chrdev_open
  - fs/char_dev.c:chrdev_open
Direct callers:
  - fs/file_table.c:__fput
```
**Symbols:**

```
ffffffff81319b60-ffffffff81319b88: cdev_put (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
void cdev_put(struct cdev *p);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/char_dev.c (ffffffff8132501c)
Location: fs/char_dev.c:361
Inline: True
Inline callers:
  - fs/char_dev.c:chrdev_open
  - fs/char_dev.c:chrdev_open
  - fs/char_dev.c:chrdev_open
  - fs/char_dev.c:chrdev_open
Direct callers:
  - fs/file_table.c:__fput
```
**Symbols:**

```
ffffffff81325240-ffffffff81325268: cdev_put (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
void cdev_put(struct cdev *p);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/char_dev.c (ffffffff8132b0ec)
Location: fs/char_dev.c:361
Inline: True
Inline callers:
  - fs/char_dev.c:chrdev_open
  - fs/char_dev.c:chrdev_open
  - fs/char_dev.c:chrdev_open
  - fs/char_dev.c:chrdev_open
Direct callers:
  - fs/file_table.c:__fput
```
**Symbols:**

```
ffffffff8132b340-ffffffff8132b368: cdev_put (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
void cdev_put(struct cdev *p);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/char_dev.c (ffffffff813787fc)
Location: fs/char_dev.c:361
Inline: True
Inline callers:
  - fs/char_dev.c:chrdev_open
  - fs/char_dev.c:chrdev_open
  - fs/char_dev.c:chrdev_open
  - fs/char_dev.c:chrdev_open
Direct callers:
  - fs/file_table.c:__fput
```
**Symbols:**

```
ffffffff81378a80-ffffffff81378aa8: cdev_put (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
void cdev_put(struct cdev *p);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/char_dev.c (ffffffff813f7b1e)
Location: fs/char_dev.c:361
Inline: True
Inline callers:
  - fs/char_dev.c:chrdev_open
  - fs/char_dev.c:chrdev_open
  - fs/char_dev.c:chrdev_open
  - fs/char_dev.c:chrdev_open
Direct callers:
  - fs/file_table.c:__fput
```
**Symbols:**

```
ffffffff813f7db0-ffffffff813f7de3: cdev_put (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
void cdev_put(struct cdev *p);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/char_dev.c (ffffffff81480e3e)
Location: fs/char_dev.c:361
Inline: True
Inline callers:
  - fs/char_dev.c:chrdev_open
  - fs/char_dev.c:chrdev_open
  - fs/char_dev.c:chrdev_open
  - fs/char_dev.c:chrdev_open
Direct callers:
  - fs/file_table.c:__fput
```
**Symbols:**

```
ffffffff814811c0-ffffffff814811f3: cdev_put (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
void cdev_put(struct cdev *p);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/char_dev.c (ffffffff814b5a5e)
Location: fs/char_dev.c:361
Inline: True
Inline callers:
  - fs/char_dev.c:chrdev_open
  - fs/char_dev.c:chrdev_open
  - fs/char_dev.c:chrdev_open
  - fs/char_dev.c:chrdev_open
Direct callers:
  - fs/file_table.c:__fput
```
**Symbols:**

```
ffffffff814b5df0-ffffffff814b5e23: cdev_put (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
void cdev_put(struct cdev *p);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/char_dev.c (ffffffff814e7d69)
Location: fs/char_dev.c:361
Inline: True
Inline callers:
  - fs/char_dev.c:chrdev_open
  - fs/char_dev.c:chrdev_open
  - fs/char_dev.c:chrdev_open
  - fs/char_dev.c:chrdev_open
Direct callers:
  - fs/file_table.c:__fput
```
**Symbols:**

```
ffffffff814e8100-ffffffff814e8133: cdev_put (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Selective Inline, Transformation ⚠️</summary>

```c
void cdev_put(struct cdev *p);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/char_dev.c (ffff800010389ea8)
Location: fs/char_dev.c:361
Inline: True
Inline callers:
  - fs/char_dev.c:chrdev_open
  - fs/char_dev.c:chrdev_open
Direct callers:
  - fs/file_table.c:__fput
  - fs/char_dev.c:chrdev_open
  - fs/char_dev.c:chrdev_open
  - fs/char_dev.c:chrdev_open
```
**Symbols:**

```
ffff800010389cb8-ffff800010389cf0: cdev_put.part.0 (STB_LOCAL)
ffff80001038a120-ffff80001038a150: cdev_put (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline, Transformation ⚠️</summary>

```c
void cdev_put(struct cdev *p);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/char_dev.c (c0572040)
Location: fs/char_dev.c:361
Inline: True
Inline callers:
  - fs/char_dev.c:chrdev_open
  - fs/char_dev.c:chrdev_open
Direct callers:
  - fs/file_table.c:__fput
  - fs/char_dev.c:chrdev_open
  - fs/char_dev.c:chrdev_open
```
**Symbols:**

```
c0571f98-c0571fc0: cdev_put.part.0 (STB_LOCAL)
c0572230-c0572254: cdev_put (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline, Transformation ⚠️</summary>

```c
void cdev_put(struct cdev *p);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/char_dev.c (c000000000480740)
Location: fs/char_dev.c:361
Inline: True
Inline callers:
  - fs/char_dev.c:chrdev_open
  - fs/char_dev.c:chrdev_open
Direct callers:
  - fs/file_table.c:__fput
  - fs/char_dev.c:chrdev_open
  - fs/char_dev.c:chrdev_open
```
**Symbols:**

```
c000000000480630-c00000000048067c: cdev_put.part.0 (STB_LOCAL)
c0000000004813f0-c00000000048140c: cdev_put (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline, Transformation ⚠️</summary>

```c
void cdev_put(struct cdev *p);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/char_dev.c (ffffffe00025bfda)
Location: fs/char_dev.c:361
Inline: True
Inline callers:
  - fs/char_dev.c:chrdev_open
  - fs/char_dev.c:chrdev_open
Direct callers:
  - fs/file_table.c:__fput
  - fs/char_dev.c:chrdev_open
  - fs/char_dev.c:chrdev_open
```
**Symbols:**

```
ffffffe00025bdfa-ffffffe00025be36: cdev_put.part.0 (STB_LOCAL)
ffffffe00025c1b2-ffffffe00025c1de: cdev_put (STB_GLOBAL)
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
void cdev_put(struct cdev *p);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/char_dev.c (ffffffff812dabf5)
Location: fs/char_dev.c:361
Inline: True
Inline callers:
  - fs/char_dev.c:chrdev_open
  - fs/char_dev.c:chrdev_open
Direct callers:
  - fs/file_table.c:__fput
  - fs/char_dev.c:chrdev_open
  - fs/char_dev.c:chrdev_open
```
**Symbols:**

```
ffffffff812daaa0-ffffffff812daac0: cdev_put.part.0 (STB_LOCAL)
ffffffff812dadd0-ffffffff812dade6: cdev_put (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline, Transformation ⚠️</summary>

```c
void cdev_put(struct cdev *p);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/char_dev.c (ffffffff812cb875)
Location: fs/char_dev.c:361
Inline: True
Inline callers:
  - fs/char_dev.c:chrdev_open
  - fs/char_dev.c:chrdev_open
Direct callers:
  - fs/file_table.c:__fput
  - fs/char_dev.c:chrdev_open
  - fs/char_dev.c:chrdev_open
```
**Symbols:**

```
ffffffff812cb720-ffffffff812cb740: cdev_put.part.0 (STB_LOCAL)
ffffffff812cba50-ffffffff812cba66: cdev_put (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline, Transformation ⚠️</summary>

```c
void cdev_put(struct cdev *p);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/char_dev.c (ffffffff812d8a05)
Location: fs/char_dev.c:361
Inline: True
Inline callers:
  - fs/char_dev.c:chrdev_open
  - fs/char_dev.c:chrdev_open
Direct callers:
  - fs/file_table.c:__fput
  - fs/char_dev.c:chrdev_open
  - fs/char_dev.c:chrdev_open
```
**Symbols:**

```
ffffffff812d88b0-ffffffff812d88d0: cdev_put.part.0 (STB_LOCAL)
ffffffff812d8be0-ffffffff812d8bf6: cdev_put (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline, Transformation ⚠️</summary>

```c
void cdev_put(struct cdev *p);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/char_dev.c (ffffffff812e981e)
Location: fs/char_dev.c:361
Inline: True
Inline callers:
  - fs/char_dev.c:chrdev_open
  - fs/char_dev.c:chrdev_open
Direct callers:
  - fs/file_table.c:__fput
  - fs/char_dev.c:chrdev_open
  - fs/char_dev.c:chrdev_open
  - fs/char_dev.c:chrdev_open
```
**Symbols:**

```
ffffffff812e97a0-ffffffff812e97c0: cdev_put.part.0 (STB_LOCAL)
ffffffff812e9a10-ffffffff812e9a26: cdev_put (STB_GLOBAL)
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
