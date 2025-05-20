# Function: <code>__unregister_chrdev_region</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
struct char_device_struct *__unregister_chrdev_region(unsigned int major, unsigned int baseminor, int minorct);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/char_dev.c (ffffffff81210910)
Location: fs/char_dev.c:146
Inline: False
Direct callers:
  - fs/char_dev.c:unregister_chrdev_region
  - fs/char_dev.c:__unregister_chrdev
  - fs/char_dev.c:register_chrdev_region
  - fs/char_dev.c:__register_chrdev
```
**Symbols:**

```
ffffffff81210910-ffffffff812109a5: __unregister_chrdev_region (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
struct char_device_struct *__unregister_chrdev_region(unsigned int major, unsigned int baseminor, int minorct);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/char_dev.c (ffffffff812373a0)
Location: fs/char_dev.c:150
Inline: False
Direct callers:
  - fs/char_dev.c:__unregister_chrdev
  - fs/char_dev.c:unregister_chrdev_region
  - fs/char_dev.c:__register_chrdev
  - fs/char_dev.c:register_chrdev_region
```
**Symbols:**

```
ffffffff812373a0-ffffffff81237437: __unregister_chrdev_region (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
struct char_device_struct *__unregister_chrdev_region(unsigned int major, unsigned int baseminor, int minorct);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/char_dev.c (ffffffff8124a050)
Location: fs/char_dev.c:150
Inline: False
Direct callers:
  - fs/char_dev.c:__unregister_chrdev
  - fs/char_dev.c:unregister_chrdev_region
  - fs/char_dev.c:__register_chrdev
  - fs/char_dev.c:register_chrdev_region
```
**Symbols:**

```
ffffffff8124a050-ffffffff8124a0e7: __unregister_chrdev_region (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
struct char_device_struct *__unregister_chrdev_region(unsigned int major, unsigned int baseminor, int minorct);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/char_dev.c (ffffffff81255950)
Location: fs/char_dev.c:150
Inline: False
Direct callers:
  - fs/char_dev.c:__unregister_chrdev
  - fs/char_dev.c:unregister_chrdev_region
  - fs/char_dev.c:__register_chrdev
  - fs/char_dev.c:register_chrdev_region
```
**Symbols:**

```
ffffffff81255950-ffffffff812559e7: __unregister_chrdev_region (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
struct char_device_struct *__unregister_chrdev_region(unsigned int major, unsigned int baseminor, int minorct);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/char_dev.c (ffffffff81277ae0)
Location: fs/char_dev.c:175
Inline: False
Direct callers:
  - fs/char_dev.c:__unregister_chrdev
  - fs/char_dev.c:unregister_chrdev_region
  - fs/char_dev.c:__register_chrdev
  - fs/char_dev.c:register_chrdev_region
```
**Symbols:**

```
ffffffff81277ae0-ffffffff81277b77: __unregister_chrdev_region (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
struct char_device_struct *__unregister_chrdev_region(unsigned int major, unsigned int baseminor, int minorct);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/char_dev.c (ffffffff8129e4a0)
Location: fs/char_dev.c:175
Inline: False
Direct callers:
  - fs/char_dev.c:__unregister_chrdev
  - fs/char_dev.c:unregister_chrdev_region
  - fs/char_dev.c:__register_chrdev
  - fs/char_dev.c:register_chrdev_region
```
**Symbols:**

```
ffffffff8129e4a0-ffffffff8129e537: __unregister_chrdev_region (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
struct char_device_struct *__unregister_chrdev_region(unsigned int major, unsigned int baseminor, int minorct);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/char_dev.c (ffffffff812b3480)
Location: fs/char_dev.c:175
Inline: False
Direct callers:
  - fs/char_dev.c:__unregister_chrdev
  - fs/char_dev.c:unregister_chrdev_region
  - fs/char_dev.c:__register_chrdev
  - fs/char_dev.c:register_chrdev_region
```
**Symbols:**

```
ffffffff812b3480-ffffffff812b3517: __unregister_chrdev_region (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
struct char_device_struct *__unregister_chrdev_region(unsigned int major, unsigned int baseminor, int minorct);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/char_dev.c (ffffffff812d00d0)
Location: fs/char_dev.c:172
Inline: False
Direct callers:
  - fs/char_dev.c:__unregister_chrdev
  - fs/char_dev.c:unregister_chrdev_region
  - fs/char_dev.c:__register_chrdev
  - fs/char_dev.c:register_chrdev_region
```
**Symbols:**

```
ffffffff812d00d0-ffffffff812d0171: __unregister_chrdev_region (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
struct char_device_struct *__unregister_chrdev_region(unsigned int major, unsigned int baseminor, int minorct);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/char_dev.c (ffffffff812e1c80)
Location: fs/char_dev.c:172
Inline: False
Direct callers:
  - fs/char_dev.c:__unregister_chrdev
  - fs/char_dev.c:unregister_chrdev_region
  - fs/char_dev.c:__register_chrdev
  - fs/char_dev.c:register_chrdev_region
```
**Symbols:**

```
ffffffff812e1c80-ffffffff812e1d21: __unregister_chrdev_region (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
struct char_device_struct *__unregister_chrdev_region(unsigned int major, unsigned int baseminor, int minorct);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/char_dev.c (ffffffff81318f50)
Location: fs/char_dev.c:172
Inline: False
Direct callers:
  - fs/char_dev.c:__unregister_chrdev
  - fs/char_dev.c:unregister_chrdev_region
  - fs/char_dev.c:__register_chrdev
  - fs/char_dev.c:register_chrdev_region
```
**Symbols:**

```
ffffffff81318f50-ffffffff81318ff1: __unregister_chrdev_region (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
struct char_device_struct *__unregister_chrdev_region(unsigned int major, unsigned int baseminor, int minorct);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/char_dev.c (ffffffff81324400)
Location: fs/char_dev.c:172
Inline: False
Direct callers:
  - fs/char_dev.c:__unregister_chrdev
  - fs/char_dev.c:unregister_chrdev_region
  - fs/char_dev.c:__register_chrdev
  - fs/char_dev.c:register_chrdev_region
```
**Symbols:**

```
ffffffff81324400-ffffffff813244a1: __unregister_chrdev_region (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
struct char_device_struct *__unregister_chrdev_region(unsigned int major, unsigned int baseminor, int minorct);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/char_dev.c (ffffffff8132a4d0)
Location: fs/char_dev.c:172
Inline: False
Direct callers:
  - fs/char_dev.c:__unregister_chrdev
  - fs/char_dev.c:unregister_chrdev_region
  - fs/char_dev.c:__register_chrdev
  - fs/char_dev.c:register_chrdev_region
```
**Symbols:**

```
ffffffff8132a4d0-ffffffff8132a571: __unregister_chrdev_region (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
struct char_device_struct *__unregister_chrdev_region(unsigned int major, unsigned int baseminor, int minorct);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/char_dev.c (ffffffff81377b70)
Location: fs/char_dev.c:172
Inline: False
Direct callers:
  - fs/char_dev.c:__unregister_chrdev
  - fs/char_dev.c:unregister_chrdev_region
  - fs/char_dev.c:__register_chrdev
  - fs/char_dev.c:register_chrdev_region
```
**Symbols:**

```
ffffffff81377b70-ffffffff81377c2f: __unregister_chrdev_region (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
struct char_device_struct *__unregister_chrdev_region(unsigned int major, unsigned int baseminor, int minorct);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/char_dev.c (ffffffff813f6e70)
Location: fs/char_dev.c:172
Inline: False
Direct callers:
  - fs/char_dev.c:__unregister_chrdev
  - fs/char_dev.c:unregister_chrdev_region
  - fs/char_dev.c:__register_chrdev
  - fs/char_dev.c:register_chrdev_region
```
**Symbols:**

```
ffffffff813f6e70-ffffffff813f6f2f: __unregister_chrdev_region (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
struct char_device_struct *__unregister_chrdev_region(unsigned int major, unsigned int baseminor, int minorct);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/char_dev.c (ffffffff814800f0)
Location: fs/char_dev.c:172
Inline: False
Direct callers:
  - fs/char_dev.c:__unregister_chrdev
  - fs/char_dev.c:unregister_chrdev_region
  - fs/char_dev.c:__register_chrdev
  - fs/char_dev.c:register_chrdev_region
```
**Symbols:**

```
ffffffff814800f0-ffffffff814801af: __unregister_chrdev_region (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
struct char_device_struct *__unregister_chrdev_region(unsigned int major, unsigned int baseminor, int minorct);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/char_dev.c (ffffffff814b4e50)
Location: fs/char_dev.c:172
Inline: False
Direct callers:
  - fs/char_dev.c:__unregister_chrdev
  - fs/char_dev.c:unregister_chrdev_region
  - fs/char_dev.c:__register_chrdev
  - fs/char_dev.c:register_chrdev_region
```
**Symbols:**

```
ffffffff814b4e50-ffffffff814b4f0f: __unregister_chrdev_region (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
struct char_device_struct *__unregister_chrdev_region(unsigned int major, unsigned int baseminor, int minorct);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/char_dev.c (ffffffff814e7110)
Location: fs/char_dev.c:172
Inline: False
Direct callers:
  - fs/char_dev.c:__unregister_chrdev
  - fs/char_dev.c:unregister_chrdev_region
  - fs/char_dev.c:__register_chrdev
  - fs/char_dev.c:register_chrdev_region
```
**Symbols:**

```
ffffffff814e7110-ffffffff814e71cf: __unregister_chrdev_region (STB_LOCAL)
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
struct char_device_struct *__unregister_chrdev_region(unsigned int major, unsigned int baseminor, int minorct);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/char_dev.c (ffff8000103892c0)
Location: fs/char_dev.c:172
Inline: False
Direct callers:
  - fs/char_dev.c:__unregister_chrdev
  - fs/char_dev.c:unregister_chrdev_region
  - fs/char_dev.c:__register_chrdev
  - fs/char_dev.c:register_chrdev_region
```
**Symbols:**

```
ffff8000103892c0-ffff800010389384: __unregister_chrdev_region (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
struct char_device_struct *__unregister_chrdev_region(unsigned int major, unsigned int baseminor, int minorct);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/char_dev.c (c0571678)
Location: fs/char_dev.c:172
Inline: False
Direct callers:
  - fs/char_dev.c:__unregister_chrdev
  - fs/char_dev.c:unregister_chrdev_region
  - fs/char_dev.c:__register_chrdev
  - fs/char_dev.c:register_chrdev_region
```
**Symbols:**

```
c0571678-c0571734: __unregister_chrdev_region (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
struct char_device_struct *__unregister_chrdev_region(unsigned int major, unsigned int baseminor, int minorct);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/char_dev.c (c000000000480030)
Location: fs/char_dev.c:172
Inline: False
Direct callers:
  - fs/char_dev.c:__unregister_chrdev
  - fs/char_dev.c:unregister_chrdev_region
  - fs/char_dev.c:__register_chrdev
  - fs/char_dev.c:register_chrdev_region
```
**Symbols:**

```
c000000000480030-c000000000480128: __unregister_chrdev_region (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
struct char_device_struct *__unregister_chrdev_region(unsigned int major, unsigned int baseminor, int minorct);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/char_dev.c (ffffffe00025b522)
Location: fs/char_dev.c:172
Inline: False
Direct callers:
  - fs/char_dev.c:__unregister_chrdev
  - fs/char_dev.c:unregister_chrdev_region
  - fs/char_dev.c:__register_chrdev
  - fs/char_dev.c:register_chrdev_region
```
**Symbols:**

```
ffffffe00025b522-ffffffe00025b5ba: __unregister_chrdev_region (STB_LOCAL)
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
struct char_device_struct *__unregister_chrdev_region(unsigned int major, unsigned int baseminor, int minorct);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/char_dev.c (ffffffff812da260)
Location: fs/char_dev.c:172
Inline: False
Direct callers:
  - fs/char_dev.c:__unregister_chrdev
  - fs/char_dev.c:unregister_chrdev_region
  - fs/char_dev.c:__register_chrdev
  - fs/char_dev.c:register_chrdev_region
```
**Symbols:**

```
ffffffff812da260-ffffffff812da301: __unregister_chrdev_region (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
struct char_device_struct *__unregister_chrdev_region(unsigned int major, unsigned int baseminor, int minorct);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/char_dev.c (ffffffff812caee0)
Location: fs/char_dev.c:172
Inline: False
Direct callers:
  - fs/char_dev.c:__unregister_chrdev
  - fs/char_dev.c:unregister_chrdev_region
  - fs/char_dev.c:__register_chrdev
  - fs/char_dev.c:register_chrdev_region
```
**Symbols:**

```
ffffffff812caee0-ffffffff812caf81: __unregister_chrdev_region (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
struct char_device_struct *__unregister_chrdev_region(unsigned int major, unsigned int baseminor, int minorct);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/char_dev.c (ffffffff812d8070)
Location: fs/char_dev.c:172
Inline: False
Direct callers:
  - fs/char_dev.c:__unregister_chrdev
  - fs/char_dev.c:unregister_chrdev_region
  - fs/char_dev.c:__register_chrdev
  - fs/char_dev.c:register_chrdev_region
```
**Symbols:**

```
ffffffff812d8070-ffffffff812d8111: __unregister_chrdev_region (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
struct char_device_struct *__unregister_chrdev_region(unsigned int major, unsigned int baseminor, int minorct);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/char_dev.c (ffffffff812e8f10)
Location: fs/char_dev.c:172
Inline: False
Direct callers:
  - fs/char_dev.c:__unregister_chrdev
  - fs/char_dev.c:unregister_chrdev_region
  - fs/char_dev.c:__register_chrdev
  - fs/char_dev.c:register_chrdev_region
```
**Symbols:**

```
ffffffff812e8f10-ffffffff812e8fb1: __unregister_chrdev_region (STB_LOCAL)
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
