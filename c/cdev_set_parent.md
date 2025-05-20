# Function: <code>cdev_set_parent</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4</code>: Absent ⚠️
</li>
<li>
In <code>4.8</code>: Absent ⚠️
</li>
<li>
In <code>4.10</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
void cdev_set_parent(struct cdev *p, struct kobject *kobj);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/char_dev.c (ffffffff81255a40)
Location: fs/char_dev.c:483
Inline: True
```
**Symbols:**

```
ffffffff81255a40-ffffffff81255a5d: cdev_set_parent (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
void cdev_set_parent(struct cdev *p, struct kobject *kobj);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/char_dev.c (ffffffff81277bd0)
Location: fs/char_dev.c:508
Inline: True
```
**Symbols:**

```
ffffffff81277bd0-ffffffff81277bec: cdev_set_parent (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void cdev_set_parent(struct cdev *p, struct kobject *kobj);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/char_dev.c (ffffffff8129e430)
Location: fs/char_dev.c:508
Inline: False
Direct callers:
  - fs/char_dev.c:cdev_device_add
```
**Symbols:**

```
ffffffff8129e430-ffffffff8129e44c: cdev_set_parent (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void cdev_set_parent(struct cdev *p, struct kobject *kobj);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/char_dev.c (ffffffff812b3410)
Location: fs/char_dev.c:508
Inline: False
Direct callers:
  - fs/char_dev.c:cdev_device_add
```
**Symbols:**

```
ffffffff812b3410-ffffffff812b342c: cdev_set_parent (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
void cdev_set_parent(struct cdev *p, struct kobject *kobj);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/char_dev.c (0)
Location: fs/char_dev.c:505
Inline: False
Direct callers:
  - fs/char_dev.c:cdev_device_add
```
**Symbols:**

```
ffffffff812d0cca-ffffffff812d0ce5: cdev_set_parent.cold (STB_LOCAL)
ffffffff812d01d0-ffffffff812d01f6: cdev_set_parent (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
void cdev_set_parent(struct cdev *p, struct kobject *kobj);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/char_dev.c (ffffffff812e2291)
Location: fs/char_dev.c:505
Inline: True
Inline callers:
  - fs/char_dev.c:cdev_device_add
```
**Symbols:**

```
ffffffff812e1d80-ffffffff812e1d9d: cdev_set_parent (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
void cdev_set_parent(struct cdev *p, struct kobject *kobj);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/char_dev.c (ffffffff81319841)
Location: fs/char_dev.c:508
Inline: True
Inline callers:
  - fs/char_dev.c:cdev_device_add
```
**Symbols:**

```
ffffffff81319050-ffffffff8131906d: cdev_set_parent (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
void cdev_set_parent(struct cdev *p, struct kobject *kobj);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/char_dev.c (ffffffff81324f21)
Location: fs/char_dev.c:508
Inline: True
Inline callers:
  - fs/char_dev.c:cdev_device_add
Direct callers:
  - drivers/remoteproc/remoteproc_cdev.c:rproc_char_device_add
```
**Symbols:**

```
ffffffff81324500-ffffffff8132451d: cdev_set_parent (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
void cdev_set_parent(struct cdev *p, struct kobject *kobj);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/char_dev.c (ffffffff8132aef1)
Location: fs/char_dev.c:508
Inline: True
Inline callers:
  - fs/char_dev.c:cdev_device_add
Direct callers:
  - drivers/remoteproc/remoteproc_cdev.c:rproc_char_device_add
```
**Symbols:**

```
ffffffff8132a5d0-ffffffff8132a5ed: cdev_set_parent (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
void cdev_set_parent(struct cdev *p, struct kobject *kobj);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/char_dev.c (ffffffff81378601)
Location: fs/char_dev.c:508
Inline: True
Inline callers:
  - fs/char_dev.c:cdev_device_add
Direct callers:
  - drivers/remoteproc/remoteproc_cdev.c:rproc_char_device_add
```
**Symbols:**

```
ffffffff81377c80-ffffffff81377c9d: cdev_set_parent (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
void cdev_set_parent(struct cdev *p, struct kobject *kobj);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/char_dev.c (ffffffff813f7a20)
Location: fs/char_dev.c:508
Inline: True
Inline callers:
  - fs/char_dev.c:cdev_device_add
Direct callers:
  - drivers/remoteproc/remoteproc_cdev.c:rproc_char_device_add
```
**Symbols:**

```
ffffffff813f6f90-ffffffff813f6fbd: cdev_set_parent (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
void cdev_set_parent(struct cdev *p, struct kobject *kobj);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/char_dev.c (ffffffff81481030)
Location: fs/char_dev.c:515
Inline: True
Inline callers:
  - fs/char_dev.c:cdev_device_add
Direct callers:
  - drivers/remoteproc/remoteproc_cdev.c:rproc_char_device_add
```
**Symbols:**

```
ffffffff81480230-ffffffff8148025d: cdev_set_parent (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
void cdev_set_parent(struct cdev *p, struct kobject *kobj);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/char_dev.c (ffffffff814b5c60)
Location: fs/char_dev.c:515
Inline: True
Inline callers:
  - fs/char_dev.c:cdev_device_add
Direct callers:
  - drivers/remoteproc/remoteproc_cdev.c:rproc_char_device_add
```
**Symbols:**

```
ffffffff814b4f90-ffffffff814b4fbd: cdev_set_parent (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
void cdev_set_parent(struct cdev *p, struct kobject *kobj);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/char_dev.c (ffffffff814e7f70)
Location: fs/char_dev.c:515
Inline: True
Inline callers:
  - fs/char_dev.c:cdev_device_add
Direct callers:
  - drivers/remoteproc/remoteproc_cdev.c:rproc_char_device_add
```
**Symbols:**

```
ffffffff814e7250-ffffffff814e727d: cdev_set_parent (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Selective Inline ⚠️</summary>

```c
void cdev_set_parent(struct cdev *p, struct kobject *kobj);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/char_dev.c (ffff800010389a18)
Location: fs/char_dev.c:505
Inline: True
Inline callers:
  - fs/char_dev.c:cdev_device_add
```
**Symbols:**

```
ffff8000103897d8-ffff800010389820: cdev_set_parent (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
void cdev_set_parent(struct cdev *p, struct kobject *kobj);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/char_dev.c (c0571d90)
Location: fs/char_dev.c:505
Inline: True
Inline callers:
  - fs/char_dev.c:cdev_device_add
```
**Symbols:**

```
c0571ca0-c0571cf0: cdev_set_parent (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void cdev_set_parent(struct cdev *p, struct kobject *kobj);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/char_dev.c (c0000000004801f0)
Location: fs/char_dev.c:505
Inline: False
Direct callers:
  - fs/char_dev.c:cdev_device_add
```
**Symbols:**

```
c0000000004801f0-c000000000480210: cdev_set_parent (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
void cdev_set_parent(struct cdev *p, struct kobject *kobj);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/char_dev.c (ffffffe00025bbc6)
Location: fs/char_dev.c:505
Inline: True
Inline callers:
  - fs/char_dev.c:cdev_device_add
```
**Symbols:**

```
ffffffe00025b9ba-ffffffe00025b9fe: cdev_set_parent (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Selective Inline ⚠️</summary>

```c
void cdev_set_parent(struct cdev *p, struct kobject *kobj);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/char_dev.c (ffffffff812da871)
Location: fs/char_dev.c:505
Inline: True
Inline callers:
  - fs/char_dev.c:cdev_device_add
```
**Symbols:**

```
ffffffff812da360-ffffffff812da37d: cdev_set_parent (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
void cdev_set_parent(struct cdev *p, struct kobject *kobj);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/char_dev.c (ffffffff812cb4f1)
Location: fs/char_dev.c:505
Inline: True
Inline callers:
  - fs/char_dev.c:cdev_device_add
Direct callers:
  - drivers/dax/device.c:dev_dax_probe
```
**Symbols:**

```
ffffffff812cafe0-ffffffff812caffd: cdev_set_parent (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
void cdev_set_parent(struct cdev *p, struct kobject *kobj);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/char_dev.c (ffffffff812d8681)
Location: fs/char_dev.c:505
Inline: True
Inline callers:
  - fs/char_dev.c:cdev_device_add
```
**Symbols:**

```
ffffffff812d8170-ffffffff812d818d: cdev_set_parent (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
void cdev_set_parent(struct cdev *p, struct kobject *kobj);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/char_dev.c (ffffffff812e9571)
Location: fs/char_dev.c:505
Inline: True
Inline callers:
  - fs/char_dev.c:cdev_device_add
```
**Symbols:**

```
ffffffff812e9010-ffffffff812e902d: cdev_set_parent (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
