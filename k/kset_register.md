# Function: <code>kset_register</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int kset_register(struct kset *k);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/kobject.c (ffffffff813ec4e0)
Location: lib/kobject.c:809
Inline: False
Direct callers:
  - fs/ext4/sysfs.c:ext4_init_sysfs
  - lib/kobject.c:kset_create_and_add
  - drivers/base/bus.c:bus_register
  - drivers/base/class.c:__class_register
```
**Symbols:**

```
ffffffff813ec4e0-ffffffff813ec544: kset_register (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int kset_register(struct kset *k);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/kobject.c (ffffffff814327b0)
Location: lib/kobject.c:809
Inline: False
Direct callers:
  - fs/ext4/sysfs.c:ext4_init_sysfs
  - lib/kobject.c:kset_create_and_add
  - drivers/base/bus.c:bus_register
  - drivers/base/class.c:__class_register
```
**Symbols:**

```
ffffffff814327b0-ffffffff81432814: kset_register (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int kset_register(struct kset *k);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/kobject.c (ffffffff8144ea20)
Location: lib/kobject.c:809
Inline: False
Direct callers:
  - fs/ext4/sysfs.c:ext4_init_sysfs
  - lib/kobject.c:kset_create_and_add
  - drivers/base/bus.c:bus_register
  - drivers/base/class.c:__class_register
```
**Symbols:**

```
ffffffff8144ea20-ffffffff8144ea84: kset_register (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int kset_register(struct kset *k);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/kobject.c (ffffffff818eec40)
Location: lib/kobject.c:812
Inline: False
Direct callers:
  - fs/ext4/sysfs.c:ext4_init_sysfs
  - drivers/base/bus.c:bus_register
  - drivers/base/class.c:__class_register
  - lib/kobject.c:kset_create_and_add
```
**Symbols:**

```
ffffffff818eec40-ffffffff818eeca4: kset_register (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int kset_register(struct kset *k);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/kobject.c (ffffffff81974f00)
Location: lib/kobject.c:812
Inline: False
Direct callers:
  - fs/ext4/sysfs.c:ext4_init_sysfs
  - drivers/base/bus.c:bus_register
  - drivers/base/class.c:__class_register
  - lib/kobject.c:kset_create_and_add
```
**Symbols:**

```
ffffffff81974f00-ffffffff81974f64: kset_register (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int kset_register(struct kset *k);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/kobject.c (ffffffff819d1430)
Location: lib/kobject.c:825
Inline: False
Direct callers:
  - drivers/base/bus.c:bus_register
  - drivers/base/class.c:__class_register
  - lib/kobject.c:kset_create_and_add
```
**Symbols:**

```
ffffffff819d1430-ffffffff819d1494: kset_register (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int kset_register(struct kset *k);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/kobject.c (ffffffff81a0a9f0)
Location: lib/kobject.c:825
Inline: False
Direct callers:
  - drivers/base/bus.c:bus_register
  - drivers/base/class.c:__class_register
  - lib/kobject.c:kset_create_and_add
```
**Symbols:**

```
ffffffff81a0a9f0-ffffffff81a0aa54: kset_register (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int kset_register(struct kset *k);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/kobject.c (ffffffff81a7a3a0)
Location: lib/kobject.c:856
Inline: False
Direct callers:
  - drivers/base/bus.c:bus_register
  - drivers/base/class.c:__class_register
  - lib/kobject.c:kset_create_and_add
```
**Symbols:**

```
ffffffff81a7a3a0-ffffffff81a7a40e: kset_register (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int kset_register(struct kset *k);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/kobject.c (ffffffff81ab1700)
Location: lib/kobject.c:856
Inline: False
Direct callers:
  - drivers/base/bus.c:bus_register
  - drivers/base/class.c:__class_register
  - lib/kobject.c:kset_create_and_add
```
**Symbols:**

```
ffffffff81ab1700-ffffffff81ab176e: kset_register (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
int kset_register(struct kset *k);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/kobject.c (ffffffff815eb7de)
Location: lib/kobject.c:873
Inline: True
Inline callers:
  - lib/kobject.c:kset_create_and_add
Direct callers:
  - drivers/base/bus.c:bus_register
  - drivers/base/class.c:__class_register
```
**Symbols:**

```
ffffffff815eb300-ffffffff815eb36e: kset_register (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
int kset_register(struct kset *k);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/kobject.c (ffffffff816100fe)
Location: lib/kobject.c:870
Inline: True
Inline callers:
  - lib/kobject.c:kset_create_and_add
Direct callers:
  - drivers/base/bus.c:bus_register
  - drivers/base/class.c:__class_register
```
**Symbols:**

```
ffffffff8160fc20-ffffffff8160fc8e: kset_register (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
int kset_register(struct kset *k);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/kobject.c (ffffffff815f383e)
Location: lib/kobject.c:870
Inline: True
Inline callers:
  - lib/kobject.c:kset_create_and_add
Direct callers:
  - drivers/base/bus.c:bus_register
  - drivers/base/class.c:__class_register
```
**Symbols:**

```
ffffffff815f3360-ffffffff815f33ce: kset_register (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
int kset_register(struct kset *k);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/kobject.c (ffffffff81660a0e)
Location: lib/kobject.c:870
Inline: True
Inline callers:
  - lib/kobject.c:kset_create_and_add
Direct callers:
  - drivers/base/bus.c:bus_register
  - drivers/base/class.c:__class_register
```
**Symbols:**

```
ffffffff81660530-ffffffff8166059e: kset_register (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
int kset_register(struct kset *k);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/kobject.c (ffffffff8177a546)
Location: lib/kobject.c:838
Inline: True
Inline callers:
  - lib/kobject.c:kset_create_and_add
Direct callers:
  - drivers/base/bus.c:bus_register
  - drivers/base/class.c:__class_register
```
**Symbols:**

```
ffffffff81779ff0-ffffffff8177a061: kset_register (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int kset_register(struct kset *k);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/kobject.c (ffffffff82023090)
Location: lib/kobject.c:849
Inline: False
Direct callers:
  - drivers/base/bus.c:bus_register
  - drivers/base/class.c:__class_register
  - lib/kobject.c:kset_create_and_add
```
**Symbols:**

```
ffffffff82023090-ffffffff82023132: kset_register (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int kset_register(struct kset *k);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/kobject.c (ffffffff820a3100)
Location: lib/kobject.c:850
Inline: False
Direct callers:
  - drivers/base/bus.c:bus_register
  - drivers/base/class.c:class_register
  - lib/kobject.c:kset_create_and_add
```
**Symbols:**

```
ffffffff820a3100-ffffffff820a31a2: kset_register (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int kset_register(struct kset *k);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/kobject.c (ffffffff8217b170)
Location: lib/kobject.c:857
Inline: False
Direct callers:
  - drivers/base/bus.c:bus_register
  - drivers/base/class.c:class_register
  - lib/kobject.c:kset_create_and_add
```
**Symbols:**

```
ffffffff8217b170-ffffffff8217b229: kset_register (STB_GLOBAL)
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
int kset_register(struct kset *k);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/kobject.c (ffff800010d8b158)
Location: lib/kobject.c:856
Inline: False
Direct callers:
  - drivers/base/bus.c:bus_register
  - drivers/base/class.c:__class_register
  - lib/kobject.c:kset_create_and_add
```
**Symbols:**

```
ffff800010d8b158-ffff800010d8b1d8: kset_register (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int kset_register(struct kset *k);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/kobject.c (c0e85ecc)
Location: lib/kobject.c:856
Inline: False
Direct callers:
  - drivers/base/bus.c:bus_register
  - drivers/base/class.c:__class_register
  - lib/kobject.c:kset_create_and_add
```
**Symbols:**

```
c0e85ecc-c0e85f48: kset_register (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int kset_register(struct kset *k);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/kobject.c (c000000000ecd170)
Location: lib/kobject.c:856
Inline: False
Direct callers:
  - drivers/base/bus.c:bus_register
  - drivers/base/class.c:__class_register
  - lib/kobject.c:kset_create_and_add
```
**Symbols:**

```
c000000000ecd170-c000000000ecd234: kset_register (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int kset_register(struct kset *k);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/kobject.c (ffffffe0008b4b44)
Location: lib/kobject.c:856
Inline: False
Direct callers:
  - drivers/base/bus.c:bus_register
  - drivers/base/class.c:__class_register
  - lib/kobject.c:kset_create_and_add
```
**Symbols:**

```
ffffffe0008b4b44-ffffffe0008b4ba8: kset_register (STB_GLOBAL)
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
int kset_register(struct kset *k);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/kobject.c (ffffffff81a50550)
Location: lib/kobject.c:856
Inline: False
Direct callers:
  - drivers/base/bus.c:bus_register
  - drivers/base/class.c:__class_register
  - lib/kobject.c:kset_create_and_add
```
**Symbols:**

```
ffffffff81a50550-ffffffff81a505be: kset_register (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int kset_register(struct kset *k);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/kobject.c (ffffffff81a0d650)
Location: lib/kobject.c:856
Inline: False
Direct callers:
  - drivers/base/bus.c:bus_register
  - drivers/base/class.c:__class_register
  - lib/kobject.c:kset_create_and_add
```
**Symbols:**

```
ffffffff81a0d650-ffffffff81a0d6be: kset_register (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int kset_register(struct kset *k);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/kobject.c (ffffffff81abc940)
Location: lib/kobject.c:856
Inline: False
Direct callers:
  - drivers/base/bus.c:bus_register
  - drivers/base/class.c:__class_register
  - lib/kobject.c:kset_create_and_add
```
**Symbols:**

```
ffffffff81abc940-ffffffff81abc9ae: kset_register (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int kset_register(struct kset *k);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/kobject.c (ffffffff81ac8dc0)
Location: lib/kobject.c:856
Inline: False
Direct callers:
  - drivers/base/bus.c:bus_register
  - drivers/base/class.c:__class_register
  - lib/kobject.c:kset_create_and_add
```
**Symbols:**

```
ffffffff81ac8dc0-ffffffff81ac8e2e: kset_register (STB_GLOBAL)
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
