# Function: <code>cdev_purge</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void cdev_purge(struct cdev *cdev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/char_dev.c (ffffffff81210850)
Location: fs/char_dev.c:408
Inline: False
Direct callers:
  - fs/char_dev.c:cdev_dynamic_release
  - fs/char_dev.c:cdev_default_release
```
**Symbols:**

```
ffffffff81210850-ffffffff812108ad: cdev_purge (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void cdev_purge(struct cdev *cdev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/char_dev.c (ffffffff812372d0)
Location: fs/char_dev.c:412
Inline: False
Direct callers:
  - fs/char_dev.c:cdev_dynamic_release
  - fs/char_dev.c:cdev_default_release
```
**Symbols:**

```
ffffffff812372d0-ffffffff81237331: cdev_purge (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void cdev_purge(struct cdev *cdev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/char_dev.c (ffffffff81249f80)
Location: fs/char_dev.c:413
Inline: False
Direct callers:
  - fs/char_dev.c:cdev_dynamic_release
  - fs/char_dev.c:cdev_default_release
```
**Symbols:**

```
ffffffff81249f80-ffffffff81249fe1: cdev_purge (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void cdev_purge(struct cdev *cdev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/char_dev.c (ffffffff81255880)
Location: fs/char_dev.c:413
Inline: False
Direct callers:
  - fs/char_dev.c:cdev_dynamic_release
  - fs/char_dev.c:cdev_default_release
```
**Symbols:**

```
ffffffff81255880-ffffffff812558e1: cdev_purge (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void cdev_purge(struct cdev *cdev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/char_dev.c (ffffffff81277a10)
Location: fs/char_dev.c:438
Inline: False
Direct callers:
  - fs/char_dev.c:cdev_dynamic_release
  - fs/char_dev.c:cdev_default_release
```
**Symbols:**

```
ffffffff81277a10-ffffffff81277a71: cdev_purge (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void cdev_purge(struct cdev *cdev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/char_dev.c (ffffffff8129ec40)
Location: fs/char_dev.c:438
Inline: False
Direct callers:
  - fs/char_dev.c:cdev_dynamic_release
  - fs/char_dev.c:cdev_default_release
```
**Symbols:**

```
ffffffff8129ec40-ffffffff8129eca1: cdev_purge (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void cdev_purge(struct cdev *cdev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/char_dev.c (ffffffff812b3c20)
Location: fs/char_dev.c:438
Inline: False
Direct callers:
  - fs/char_dev.c:cdev_dynamic_release
  - fs/char_dev.c:cdev_default_release
```
**Symbols:**

```
ffffffff812b3c20-ffffffff812b3c81: cdev_purge (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void cdev_purge(struct cdev *cdev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/char_dev.c (ffffffff812d0930)
Location: fs/char_dev.c:435
Inline: False
Direct callers:
  - fs/char_dev.c:cdev_dynamic_release
  - fs/char_dev.c:cdev_default_release
```
**Symbols:**

```
ffffffff812d0930-ffffffff812d0991: cdev_purge (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void cdev_purge(struct cdev *cdev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/char_dev.c (ffffffff812e24e0)
Location: fs/char_dev.c:435
Inline: False
Direct callers:
  - fs/char_dev.c:cdev_dynamic_release
  - fs/char_dev.c:cdev_default_release
```
**Symbols:**

```
ffffffff812e24e0-ffffffff812e2541: cdev_purge (STB_LOCAL)
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
In fs/char_dev.c (ffffffff81319764)
Location: fs/char_dev.c:435
Inline: True
Inline callers:
  - fs/char_dev.c:cdev_dynamic_release
  - fs/char_dev.c:cdev_default_release
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
In fs/char_dev.c (ffffffff81324e44)
Location: fs/char_dev.c:435
Inline: True
Inline callers:
  - fs/char_dev.c:cdev_dynamic_release
  - fs/char_dev.c:cdev_default_release
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
In fs/char_dev.c (ffffffff8132aff4)
Location: fs/char_dev.c:435
Inline: True
Inline callers:
  - fs/char_dev.c:cdev_dynamic_release
  - fs/char_dev.c:cdev_default_release
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
In fs/char_dev.c (ffffffff81378704)
Location: fs/char_dev.c:435
Inline: True
Inline callers:
  - fs/char_dev.c:cdev_dynamic_release
  - fs/char_dev.c:cdev_default_release
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
In fs/char_dev.c (ffffffff813f6fd3)
Location: fs/char_dev.c:435
Inline: True
Inline callers:
  - fs/char_dev.c:cdev_dynamic_release
  - fs/char_dev.c:cdev_default_release
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
In fs/char_dev.c (ffffffff81480283)
Location: fs/char_dev.c:435
Inline: True
Inline callers:
  - fs/char_dev.c:cdev_dynamic_release
  - fs/char_dev.c:cdev_default_release
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
In fs/char_dev.c (ffffffff814b4fe3)
Location: fs/char_dev.c:435
Inline: True
Inline callers:
  - fs/char_dev.c:cdev_dynamic_release
  - fs/char_dev.c:cdev_default_release
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
In fs/char_dev.c (ffffffff814e72a3)
Location: fs/char_dev.c:435
Inline: True
Inline callers:
  - fs/char_dev.c:cdev_dynamic_release
  - fs/char_dev.c:cdev_default_release
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
void cdev_purge(struct cdev *cdev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/char_dev.c (ffff800010389cf0)
Location: fs/char_dev.c:435
Inline: False
Direct callers:
  - fs/char_dev.c:cdev_dynamic_release
  - fs/char_dev.c:cdev_default_release
```
**Symbols:**

```
ffff800010389cf0-ffff800010389db0: cdev_purge (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void cdev_purge(struct cdev *cdev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/char_dev.c (c0571588)
Location: fs/char_dev.c:435
Inline: False
Direct callers:
  - fs/char_dev.c:cdev_dynamic_release
  - fs/char_dev.c:cdev_default_release
```
**Symbols:**

```
c0571588-c0571608: cdev_purge (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void cdev_purge(struct cdev *cdev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/char_dev.c (c000000000480930)
Location: fs/char_dev.c:435
Inline: False
Direct callers:
  - fs/char_dev.c:cdev_dynamic_release
  - fs/char_dev.c:cdev_default_release
```
**Symbols:**

```
c000000000480930-c000000000480a2c: cdev_purge (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void cdev_purge(struct cdev *cdev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/char_dev.c (ffffffe00025be36)
Location: fs/char_dev.c:435
Inline: False
Direct callers:
  - fs/char_dev.c:cdev_dynamic_release
  - fs/char_dev.c:cdev_default_release
```
**Symbols:**

```
ffffffe00025be36-ffffffe00025becc: cdev_purge (STB_LOCAL)
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
void cdev_purge(struct cdev *cdev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/char_dev.c (ffffffff812daac0)
Location: fs/char_dev.c:435
Inline: False
Direct callers:
  - fs/char_dev.c:cdev_dynamic_release
  - fs/char_dev.c:cdev_default_release
```
**Symbols:**

```
ffffffff812daac0-ffffffff812dab21: cdev_purge (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void cdev_purge(struct cdev *cdev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/char_dev.c (ffffffff812cb740)
Location: fs/char_dev.c:435
Inline: False
Direct callers:
  - fs/char_dev.c:cdev_dynamic_release
  - fs/char_dev.c:cdev_default_release
```
**Symbols:**

```
ffffffff812cb740-ffffffff812cb7a1: cdev_purge (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void cdev_purge(struct cdev *cdev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/char_dev.c (ffffffff812d88d0)
Location: fs/char_dev.c:435
Inline: False
Direct callers:
  - fs/char_dev.c:cdev_dynamic_release
  - fs/char_dev.c:cdev_default_release
```
**Symbols:**

```
ffffffff812d88d0-ffffffff812d8931: cdev_purge (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void cdev_purge(struct cdev *cdev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/char_dev.c (ffffffff812e8e50)
Location: fs/char_dev.c:435
Inline: False
Direct callers:
  - fs/char_dev.c:cdev_dynamic_release
  - fs/char_dev.c:cdev_default_release
```
**Symbols:**

```
ffffffff812e8e50-ffffffff812e8eaf: cdev_purge (STB_LOCAL)
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
