# Function: <code>cdev_get</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
struct kobject *cdev_get(struct cdev *p);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/char_dev.c (ffffffff81210a50)
Location: fs/char_dev.c:322
Inline: False
Direct callers:
  - fs/char_dev.c:exact_lock
  - fs/char_dev.c:chrdev_open
  - fs/char_dev.c:chrdev_open
```
**Symbols:**

```
ffffffff81210a50-ffffffff81210a95: cdev_get (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
struct kobject *cdev_get(struct cdev *p);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/char_dev.c (ffffffff812374e0)
Location: fs/char_dev.c:326
Inline: False
Direct callers:
  - fs/char_dev.c:exact_lock
  - fs/char_dev.c:chrdev_open
  - fs/char_dev.c:chrdev_open
```
**Symbols:**

```
ffffffff812374e0-ffffffff81237534: cdev_get (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
struct kobject *cdev_get(struct cdev *p);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/char_dev.c (ffffffff8124a190)
Location: fs/char_dev.c:326
Inline: False
Direct callers:
  - fs/char_dev.c:exact_lock
  - fs/char_dev.c:chrdev_open
  - fs/char_dev.c:chrdev_open
```
**Symbols:**

```
ffffffff8124a190-ffffffff8124a1e4: cdev_get (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
struct kobject *cdev_get(struct cdev *p);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/char_dev.c (ffffffff81255ab0)
Location: fs/char_dev.c:326
Inline: False
Direct callers:
  - fs/char_dev.c:exact_lock
  - fs/char_dev.c:chrdev_open
  - fs/char_dev.c:chrdev_open
```
**Symbols:**

```
ffffffff81255ab0-ffffffff81255b0b: cdev_get (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
struct kobject *cdev_get(struct cdev *p);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/char_dev.c (ffffffff81277c40)
Location: fs/char_dev.c:351
Inline: False
Direct callers:
  - fs/char_dev.c:exact_lock
  - fs/char_dev.c:chrdev_open
  - fs/char_dev.c:chrdev_open
```
**Symbols:**

```
ffffffff81277c40-ffffffff81277c9b: cdev_get (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
struct kobject *cdev_get(struct cdev *p);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/char_dev.c (ffffffff8129e590)
Location: fs/char_dev.c:351
Inline: False
Direct callers:
  - fs/char_dev.c:exact_lock
  - fs/char_dev.c:chrdev_open
  - fs/char_dev.c:chrdev_open
```
**Symbols:**

```
ffffffff8129e590-ffffffff8129e5f2: cdev_get (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
struct kobject *cdev_get(struct cdev *p);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/char_dev.c (ffffffff812b3870)
Location: fs/char_dev.c:351
Inline: False
Direct callers:
  - fs/char_dev.c:exact_lock
  - fs/char_dev.c:chrdev_open
  - fs/char_dev.c:chrdev_open
```
**Symbols:**

```
ffffffff812b3870-ffffffff812b38d2: cdev_get (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
struct kobject *cdev_get(struct cdev *p);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/char_dev.c (ffffffff812d0570)
Location: fs/char_dev.c:348
Inline: False
Direct callers:
  - fs/char_dev.c:exact_lock
  - fs/char_dev.c:chrdev_open
  - fs/char_dev.c:chrdev_open
```
**Symbols:**

```
ffffffff812d0570-ffffffff812d05d6: cdev_get (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
struct kobject *cdev_get(struct cdev *p);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/char_dev.c (ffffffff812e2110)
Location: fs/char_dev.c:348
Inline: False
Direct callers:
  - fs/char_dev.c:exact_lock
  - fs/char_dev.c:chrdev_open
  - fs/char_dev.c:chrdev_open
```
**Symbols:**

```
ffffffff812e2110-ffffffff812e2176: cdev_get (STB_LOCAL)
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
In fs/char_dev.c (ffffffff81319635)
Location: fs/char_dev.c:348
Inline: True
Inline callers:
  - fs/char_dev.c:exact_lock
  - fs/char_dev.c:chrdev_open
  - fs/char_dev.c:chrdev_open
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
In fs/char_dev.c (ffffffff81324d15)
Location: fs/char_dev.c:348
Inline: True
Inline callers:
  - fs/char_dev.c:exact_lock
  - fs/char_dev.c:chrdev_open
  - fs/char_dev.c:chrdev_open
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
In fs/char_dev.c (ffffffff8132ade5)
Location: fs/char_dev.c:348
Inline: True
Inline callers:
  - fs/char_dev.c:exact_lock
  - fs/char_dev.c:chrdev_open
  - fs/char_dev.c:chrdev_open
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
In fs/char_dev.c (ffffffff813784f5)
Location: fs/char_dev.c:348
Inline: True
Inline callers:
  - fs/char_dev.c:exact_lock
  - fs/char_dev.c:chrdev_open
  - fs/char_dev.c:chrdev_open
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
In fs/char_dev.c (ffffffff813f78d5)
Location: fs/char_dev.c:348
Inline: True
Inline callers:
  - fs/char_dev.c:exact_lock
  - fs/char_dev.c:chrdev_open
  - fs/char_dev.c:chrdev_open
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
In fs/char_dev.c (ffffffff81480c65)
Location: fs/char_dev.c:348
Inline: True
Inline callers:
  - fs/char_dev.c:exact_lock
  - fs/char_dev.c:chrdev_open
  - fs/char_dev.c:chrdev_open
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
In fs/char_dev.c (ffffffff814b5885)
Location: fs/char_dev.c:348
Inline: True
Inline callers:
  - fs/char_dev.c:exact_lock
  - fs/char_dev.c:chrdev_open
  - fs/char_dev.c:chrdev_open
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
In fs/char_dev.c (ffffffff814e7b95)
Location: fs/char_dev.c:348
Inline: True
Inline callers:
  - fs/char_dev.c:exact_lock
  - fs/char_dev.c:chrdev_open
  - fs/char_dev.c:chrdev_open
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
struct kobject *cdev_get(struct cdev *p);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/char_dev.c (ffff800010389820)
Location: fs/char_dev.c:348
Inline: False
Direct callers:
  - fs/char_dev.c:exact_lock
  - fs/char_dev.c:chrdev_open
  - fs/char_dev.c:chrdev_open
```
**Symbols:**

```
ffff800010389820-ffff80001038989c: cdev_get (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
struct kobject *cdev_get(struct cdev *p);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/char_dev.c (c0571ba8)
Location: fs/char_dev.c:348
Inline: False
Direct callers:
  - fs/char_dev.c:exact_lock
  - fs/char_dev.c:chrdev_open
  - fs/char_dev.c:chrdev_open
```
**Symbols:**

```
c0571ba8-c0571c04: cdev_get (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
struct kobject *cdev_get(struct cdev *p);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/char_dev.c (c000000000480210)
Location: fs/char_dev.c:348
Inline: False
Direct callers:
  - fs/char_dev.c:exact_lock
  - fs/char_dev.c:chrdev_open
  - fs/char_dev.c:chrdev_open
```
**Symbols:**

```
c000000000480210-c0000000004802e0: cdev_get (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
struct kobject *cdev_get(struct cdev *p);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/char_dev.c (ffffffe00025b9fe)
Location: fs/char_dev.c:348
Inline: False
Direct callers:
  - fs/char_dev.c:exact_lock
  - fs/char_dev.c:chrdev_open
  - fs/char_dev.c:chrdev_open
```
**Symbols:**

```
ffffffe00025b9fe-ffffffe00025ba6e: cdev_get (STB_LOCAL)
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
struct kobject *cdev_get(struct cdev *p);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/char_dev.c (ffffffff812da6f0)
Location: fs/char_dev.c:348
Inline: False
Direct callers:
  - fs/char_dev.c:exact_lock
  - fs/char_dev.c:chrdev_open
  - fs/char_dev.c:chrdev_open
```
**Symbols:**

```
ffffffff812da6f0-ffffffff812da756: cdev_get (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
struct kobject *cdev_get(struct cdev *p);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/char_dev.c (ffffffff812cb370)
Location: fs/char_dev.c:348
Inline: False
Direct callers:
  - fs/char_dev.c:exact_lock
  - fs/char_dev.c:chrdev_open
  - fs/char_dev.c:chrdev_open
```
**Symbols:**

```
ffffffff812cb370-ffffffff812cb3d6: cdev_get (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
struct kobject *cdev_get(struct cdev *p);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/char_dev.c (ffffffff812d8500)
Location: fs/char_dev.c:348
Inline: False
Direct callers:
  - fs/char_dev.c:exact_lock
  - fs/char_dev.c:chrdev_open
  - fs/char_dev.c:chrdev_open
```
**Symbols:**

```
ffffffff812d8500-ffffffff812d8566: cdev_get (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
struct kobject *cdev_get(struct cdev *p);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/char_dev.c (ffffffff812e93f0)
Location: fs/char_dev.c:348
Inline: False
Direct callers:
  - fs/char_dev.c:exact_lock
  - fs/char_dev.c:chrdev_open
  - fs/char_dev.c:chrdev_open
```
**Symbols:**

```
ffffffff812e93f0-ffffffff812e9456: cdev_get (STB_LOCAL)
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
