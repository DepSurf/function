# Function: <code>__register_chrdev_region</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
struct char_device_struct *__register_chrdev_region(unsigned int major, unsigned int baseminor, int minorct, const char *name);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/char_dev.c (ffffffff81210be0)
Location: fs/char_dev.c:74
Inline: False
Direct callers:
  - fs/char_dev.c:register_chrdev_region
  - fs/char_dev.c:alloc_chrdev_region
  - fs/char_dev.c:__register_chrdev
```
**Symbols:**

```
ffffffff81210be0-ffffffff81210d47: __register_chrdev_region (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
struct char_device_struct *__register_chrdev_region(unsigned int major, unsigned int baseminor, int minorct, const char *name);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/char_dev.c (ffffffff812376d0)
Location: fs/char_dev.c:74
Inline: False
Direct callers:
  - fs/char_dev.c:__register_chrdev
  - fs/char_dev.c:alloc_chrdev_region
  - fs/char_dev.c:register_chrdev_region
```
**Symbols:**

```
ffffffff812376d0-ffffffff8123786b: __register_chrdev_region (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
struct char_device_struct *__register_chrdev_region(unsigned int major, unsigned int baseminor, int minorct, const char *name);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/char_dev.c (ffffffff8124a380)
Location: fs/char_dev.c:74
Inline: False
Direct callers:
  - fs/char_dev.c:__register_chrdev
  - fs/char_dev.c:alloc_chrdev_region
  - fs/char_dev.c:register_chrdev_region
```
**Symbols:**

```
ffffffff8124a380-ffffffff8124a51b: __register_chrdev_region (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
struct char_device_struct *__register_chrdev_region(unsigned int major, unsigned int baseminor, int minorct, const char *name);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/char_dev.c (ffffffff81255f20)
Location: fs/char_dev.c:74
Inline: False
Direct callers:
  - fs/char_dev.c:__register_chrdev
  - fs/char_dev.c:alloc_chrdev_region
  - fs/char_dev.c:register_chrdev_region
```
**Symbols:**

```
ffffffff81255f20-ffffffff812560d0: __register_chrdev_region (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
struct char_device_struct *__register_chrdev_region(unsigned int major, unsigned int baseminor, int minorct, const char *name);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/char_dev.c (ffffffff812780c0)
Location: fs/char_dev.c:100
Inline: False
Direct callers:
  - fs/char_dev.c:__register_chrdev
  - fs/char_dev.c:alloc_chrdev_region
  - fs/char_dev.c:register_chrdev_region
```
**Symbols:**

```
ffffffff812780c0-ffffffff812782d3: __register_chrdev_region (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Transformation ⚠️</summary>

```c
struct char_device_struct *__register_chrdev_region(unsigned int major, unsigned int baseminor, int minorct, const char *name);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/char_dev.c (0)
Location: fs/char_dev.c:100
Inline: False
Direct callers:
  - fs/char_dev.c:__register_chrdev
  - fs/char_dev.c:alloc_chrdev_region
  - fs/char_dev.c:register_chrdev_region
```
**Symbols:**

```
ffffffff8129e860-ffffffff8129ea5d: __register_chrdev_region (STB_LOCAL)
ffffffff8129efda-ffffffff8129effc: __register_chrdev_region.cold.6 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Transformation ⚠️</summary>

```c
struct char_device_struct *__register_chrdev_region(unsigned int major, unsigned int baseminor, int minorct, const char *name);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/char_dev.c (0)
Location: fs/char_dev.c:100
Inline: False
Direct callers:
  - fs/char_dev.c:__register_chrdev
  - fs/char_dev.c:alloc_chrdev_region
  - fs/char_dev.c:register_chrdev_region
```
**Symbols:**

```
ffffffff812b3570-ffffffff812b376d: __register_chrdev_region (STB_LOCAL)
ffffffff812b3fba-ffffffff812b3fdc: __register_chrdev_region.cold.5 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
struct char_device_struct *__register_chrdev_region(unsigned int major, unsigned int baseminor, int minorct, const char *name);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/char_dev.c (0)
Location: fs/char_dev.c:97
Inline: False
Direct callers:
  - fs/char_dev.c:__register_chrdev
  - fs/char_dev.c:alloc_chrdev_region
  - fs/char_dev.c:register_chrdev_region
```
**Symbols:**

```
ffffffff812d0200-ffffffff812d0478: __register_chrdev_region (STB_LOCAL)
ffffffff812d0ce5-ffffffff812d0d36: __register_chrdev_region.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
struct char_device_struct *__register_chrdev_region(unsigned int major, unsigned int baseminor, int minorct, const char *name);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/char_dev.c (0)
Location: fs/char_dev.c:97
Inline: False
Direct callers:
  - fs/char_dev.c:__register_chrdev
  - fs/char_dev.c:alloc_chrdev_region
  - fs/char_dev.c:register_chrdev_region
```
**Symbols:**

```
ffffffff812e1da0-ffffffff812e2018: __register_chrdev_region (STB_LOCAL)
ffffffff812e287a-ffffffff812e28cb: __register_chrdev_region.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
struct char_device_struct *__register_chrdev_region(unsigned int major, unsigned int baseminor, int minorct, const char *name);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/char_dev.c (0)
Location: fs/char_dev.c:97
Inline: False
Direct callers:
  - fs/char_dev.c:__register_chrdev
  - fs/char_dev.c:alloc_chrdev_region
  - fs/char_dev.c:register_chrdev_region
```
**Symbols:**

```
ffffffff81319180-ffffffff81319402: __register_chrdev_region (STB_LOCAL)
ffffffff81319bfd-ffffffff81319c4e: __register_chrdev_region.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
struct char_device_struct *__register_chrdev_region(unsigned int major, unsigned int baseminor, int minorct, const char *name);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/char_dev.c (0)
Location: fs/char_dev.c:97
Inline: False
Direct callers:
  - fs/char_dev.c:__register_chrdev
  - fs/char_dev.c:alloc_chrdev_region
  - fs/char_dev.c:register_chrdev_region
```
**Symbols:**

```
ffffffff81324630-ffffffff81324aef: __register_chrdev_region (STB_LOCAL)
ffffffff81bea5b9-ffffffff81bea608: __register_chrdev_region.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
struct char_device_struct *__register_chrdev_region(unsigned int major, unsigned int baseminor, int minorct, const char *name);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/char_dev.c (0)
Location: fs/char_dev.c:97
Inline: False
Direct callers:
  - fs/char_dev.c:__register_chrdev
  - fs/char_dev.c:alloc_chrdev_region
  - fs/char_dev.c:register_chrdev_region
```
**Symbols:**

```
ffffffff8132a750-ffffffff8132ac07: __register_chrdev_region (STB_LOCAL)
ffffffff81bdc5f5-ffffffff81bdc644: __register_chrdev_region.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
struct char_device_struct *__register_chrdev_region(unsigned int major, unsigned int baseminor, int minorct, const char *name);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/char_dev.c (0)
Location: fs/char_dev.c:97
Inline: False
Direct callers:
  - fs/char_dev.c:__register_chrdev
  - fs/char_dev.c:alloc_chrdev_region
  - fs/char_dev.c:register_chrdev_region
```
**Symbols:**

```
ffffffff81377e00-ffffffff81378320: __register_chrdev_region (STB_LOCAL)
ffffffff81cc3932-ffffffff81cc397e: __register_chrdev_region.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
struct char_device_struct *__register_chrdev_region(unsigned int major, unsigned int baseminor, int minorct, const char *name);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/char_dev.c (0)
Location: fs/char_dev.c:97
Inline: False
Direct callers:
  - fs/char_dev.c:__register_chrdev
  - fs/char_dev.c:alloc_chrdev_region
  - fs/char_dev.c:register_chrdev_region
```
**Symbols:**

```
ffffffff813f7210-ffffffff813f7642: __register_chrdev_region (STB_LOCAL)
ffffffff81e760b0-ffffffff81e760f5: __register_chrdev_region.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
struct char_device_struct *__register_chrdev_region(unsigned int major, unsigned int baseminor, int minorct, const char *name);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/char_dev.c (ffffffff81480500)
Location: fs/char_dev.c:97
Inline: False
Direct callers:
  - fs/char_dev.c:__register_chrdev
  - fs/char_dev.c:alloc_chrdev_region
  - fs/char_dev.c:register_chrdev_region
```
**Symbols:**

```
ffffffff81480500-ffffffff8148098d: __register_chrdev_region (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
struct char_device_struct *__register_chrdev_region(unsigned int major, unsigned int baseminor, int minorct, const char *name);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/char_dev.c (ffffffff814b5260)
Location: fs/char_dev.c:97
Inline: False
Direct callers:
  - fs/char_dev.c:__register_chrdev
  - fs/char_dev.c:alloc_chrdev_region
  - fs/char_dev.c:register_chrdev_region
```
**Symbols:**

```
ffffffff814b5260-ffffffff814b55a1: __register_chrdev_region (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
struct char_device_struct *__register_chrdev_region(unsigned int major, unsigned int baseminor, int minorct, const char *name);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/char_dev.c (ffffffff814e7550)
Location: fs/char_dev.c:97
Inline: False
Direct callers:
  - fs/char_dev.c:__register_chrdev
  - fs/char_dev.c:alloc_chrdev_region
  - fs/char_dev.c:register_chrdev_region
```
**Symbols:**

```
ffffffff814e7550-ffffffff814e78be: __register_chrdev_region (STB_LOCAL)
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
struct char_device_struct *__register_chrdev_region(unsigned int major, unsigned int baseminor, int minorct, const char *name);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/char_dev.c (ffff8000103893f0)
Location: fs/char_dev.c:97
Inline: False
Direct callers:
  - fs/char_dev.c:__register_chrdev
  - fs/char_dev.c:alloc_chrdev_region
  - fs/char_dev.c:register_chrdev_region
```
**Symbols:**

```
ffff8000103893f0-ffff80001038969c: __register_chrdev_region (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
struct char_device_struct *__register_chrdev_region(unsigned int major, unsigned int baseminor, int minorct, const char *name);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/char_dev.c (c057178c)
Location: fs/char_dev.c:97
Inline: False
Direct callers:
  - fs/char_dev.c:__register_chrdev
  - fs/char_dev.c:alloc_chrdev_region
  - fs/char_dev.c:register_chrdev_region
```
**Symbols:**

```
c057178c-c0571a64: __register_chrdev_region (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
struct char_device_struct *__register_chrdev_region(unsigned int major, unsigned int baseminor, int minorct, const char *name);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/char_dev.c (c000000000480b60)
Location: fs/char_dev.c:97
Inline: False
Direct callers:
  - fs/char_dev.c:__register_chrdev
  - fs/char_dev.c:alloc_chrdev_region
  - fs/char_dev.c:register_chrdev_region
```
**Symbols:**

```
c000000000480b60-c000000000480f10: __register_chrdev_region (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
struct char_device_struct *__register_chrdev_region(unsigned int major, unsigned int baseminor, int minorct, const char *name);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/char_dev.c (ffffffe00025b630)
Location: fs/char_dev.c:97
Inline: False
Direct callers:
  - fs/char_dev.c:__register_chrdev
  - fs/char_dev.c:alloc_chrdev_region
  - fs/char_dev.c:register_chrdev_region
```
**Symbols:**

```
ffffffe00025b630-ffffffe00025b882: __register_chrdev_region (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Transformation ⚠️</summary>

```c
struct char_device_struct *__register_chrdev_region(unsigned int major, unsigned int baseminor, int minorct, const char *name);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/char_dev.c (0)
Location: fs/char_dev.c:97
Inline: False
Direct callers:
  - fs/char_dev.c:__register_chrdev
  - fs/char_dev.c:alloc_chrdev_region
  - fs/char_dev.c:register_chrdev_region
```
**Symbols:**

```
ffffffff812da380-ffffffff812da5f8: __register_chrdev_region (STB_LOCAL)
ffffffff812dae5a-ffffffff812daeab: __register_chrdev_region.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Transformation ⚠️</summary>

```c
struct char_device_struct *__register_chrdev_region(unsigned int major, unsigned int baseminor, int minorct, const char *name);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/char_dev.c (0)
Location: fs/char_dev.c:97
Inline: False
Direct callers:
  - fs/char_dev.c:__register_chrdev
  - fs/char_dev.c:alloc_chrdev_region
  - fs/char_dev.c:register_chrdev_region
```
**Symbols:**

```
ffffffff812cb000-ffffffff812cb278: __register_chrdev_region (STB_LOCAL)
ffffffff812cbada-ffffffff812cbb2b: __register_chrdev_region.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Transformation ⚠️</summary>

```c
struct char_device_struct *__register_chrdev_region(unsigned int major, unsigned int baseminor, int minorct, const char *name);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/char_dev.c (0)
Location: fs/char_dev.c:97
Inline: False
Direct callers:
  - fs/char_dev.c:__register_chrdev
  - fs/char_dev.c:alloc_chrdev_region
  - fs/char_dev.c:register_chrdev_region
```
**Symbols:**

```
ffffffff812d8190-ffffffff812d8408: __register_chrdev_region (STB_LOCAL)
ffffffff812d8c6a-ffffffff812d8cbb: __register_chrdev_region.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
struct char_device_struct *__register_chrdev_region(unsigned int major, unsigned int baseminor, int minorct, const char *name);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/char_dev.c (0)
Location: fs/char_dev.c:97
Inline: False
Direct callers:
  - fs/char_dev.c:__register_chrdev
  - fs/char_dev.c:alloc_chrdev_region
  - fs/char_dev.c:register_chrdev_region
```
**Symbols:**

```
ffffffff812e9030-ffffffff812e92a8: __register_chrdev_region (STB_LOCAL)
ffffffff812e9a98-ffffffff812e9ae9: __register_chrdev_region.cold (STB_LOCAL)
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
