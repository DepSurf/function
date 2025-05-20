# Function: <code>class_remove_file_ns</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline ⚠️</summary>

```c
void class_remove_file_ns(struct class *cls, const struct class_attribute *attr, const void *ns);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/class.c (ffffffff8154cae0)
Location: drivers/base/class.c:102
Inline: True
Inline callers:
  - drivers/base/class.c:class_unregister
  - drivers/base/class.c:__class_register
Direct callers:
  - net/core/net-sysfs.c:netdev_class_remove_file_ns
```
**Symbols:**

```
ffffffff8154cae0-ffffffff8154cafe: class_remove_file_ns (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
void class_remove_file_ns(struct class *cls, const struct class_attribute *attr, const void *ns);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/class.c (ffffffff8159ea59)
Location: drivers/base/class.c:102
Inline: True
Inline callers:
  - drivers/base/class.c:class_unregister
  - drivers/base/class.c:__class_register
Direct callers:
  - net/core/net-sysfs.c:netdev_class_remove_file_ns
```
**Symbols:**

```
ffffffff8159e8d0-ffffffff8159e8ee: class_remove_file_ns (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
void class_remove_file_ns(struct class *cls, const struct class_attribute *attr, const void *ns);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/class.c (ffffffff815cd009)
Location: drivers/base/class.c:102
Inline: True
Inline callers:
  - drivers/base/class.c:class_unregister
  - drivers/base/class.c:__class_register
Direct callers:
  - net/core/net-sysfs.c:netdev_class_remove_file_ns
```
**Symbols:**

```
ffffffff815cce80-ffffffff815cce9e: class_remove_file_ns (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void class_remove_file_ns(struct class *cls, const struct class_attribute *attr, const void *ns);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/class.c (ffffffff815e19c0)
Location: drivers/base/class.c:102
Inline: False
Direct callers:
  - net/core/net-sysfs.c:netdev_class_remove_file_ns
```
**Symbols:**

```
ffffffff815e19c0-ffffffff815e19df: class_remove_file_ns (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void class_remove_file_ns(struct class *cls, const struct class_attribute *attr, const void *ns);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/class.c (ffffffff81648b20)
Location: drivers/base/class.c:102
Inline: False
Direct callers:
  - net/core/net-sysfs.c:netdev_class_remove_file_ns
```
**Symbols:**

```
ffffffff81648b20-ffffffff81648b3f: class_remove_file_ns (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void class_remove_file_ns(struct class *cls, const struct class_attribute *attr, const void *ns);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/class.c (ffffffff816840f0)
Location: drivers/base/class.c:100
Inline: False
Direct callers:
  - net/core/net-sysfs.c:netdev_class_remove_file_ns
```
**Symbols:**

```
ffffffff816840f0-ffffffff8168410e: class_remove_file_ns (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void class_remove_file_ns(struct class *cls, const struct class_attribute *attr, const void *ns);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/class.c (ffffffff816a3dc0)
Location: drivers/base/class.c:100
Inline: False
Direct callers:
  - net/core/net-sysfs.c:netdev_class_remove_file_ns
```
**Symbols:**

```
ffffffff816a3dc0-ffffffff816a3dde: class_remove_file_ns (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void class_remove_file_ns(struct class *cls, const struct class_attribute *attr, const void *ns);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/class.c (ffffffff816dccd0)
Location: drivers/base/class.c:100
Inline: False
Direct callers:
  - net/core/net-sysfs.c:netdev_class_remove_file_ns
```
**Symbols:**

```
ffffffff816dccd0-ffffffff816dccee: class_remove_file_ns (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void class_remove_file_ns(struct class *cls, const struct class_attribute *attr, const void *ns);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/class.c (ffffffff81700d80)
Location: drivers/base/class.c:100
Inline: False
Direct callers:
  - net/core/net-sysfs.c:netdev_class_remove_file_ns
```
**Symbols:**

```
ffffffff81700d80-ffffffff81700d9e: class_remove_file_ns (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void class_remove_file_ns(struct class *cls, const struct class_attribute *attr, const void *ns);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/class.c (ffffffff817bacf0)
Location: drivers/base/class.c:101
Inline: False
Direct callers:
  - net/core/net-sysfs.c:netdev_class_remove_file_ns
```
**Symbols:**

```
ffffffff817bacf0-ffffffff817bad0e: class_remove_file_ns (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void class_remove_file_ns(struct class *cls, const struct class_attribute *attr, const void *ns);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/class.c (ffffffff817cf8f0)
Location: drivers/base/class.c:101
Inline: False
Direct callers:
  - net/core/net-sysfs.c:netdev_class_remove_file_ns
```
**Symbols:**

```
ffffffff817cf8f0-ffffffff817cf90e: class_remove_file_ns (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void class_remove_file_ns(struct class *cls, const struct class_attribute *attr, const void *ns);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/class.c (ffffffff817b3300)
Location: drivers/base/class.c:101
Inline: False
Direct callers:
  - net/core/net-sysfs.c:netdev_class_remove_file_ns
```
**Symbols:**

```
ffffffff817b3300-ffffffff817b331e: class_remove_file_ns (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void class_remove_file_ns(struct class *cls, const struct class_attribute *attr, const void *ns);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/class.c (ffffffff8183c7f0)
Location: drivers/base/class.c:101
Inline: False
Direct callers:
  - net/core/net-sysfs.c:netdev_class_remove_file_ns
```
**Symbols:**

```
ffffffff8183c7f0-ffffffff8183c80e: class_remove_file_ns (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
void class_remove_file_ns(struct class *cls, const struct class_attribute *attr, const void *ns);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/class.c (ffffffff8197f6c0)
Location: drivers/base/class.c:101
Inline: True
Direct callers:
  - net/core/net-sysfs.c:netdev_class_remove_file_ns
```
**Symbols:**

```
ffffffff8197f6c0-ffffffff8197f6f2: class_remove_file_ns (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
void class_remove_file_ns(struct class *cls, const struct class_attribute *attr, const void *ns);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/class.c (ffffffff81aecfa0)
Location: drivers/base/class.c:101
Inline: True
Direct callers:
  - net/core/net-sysfs.c:netdev_class_remove_file_ns
```
**Symbols:**

```
ffffffff81aecfa0-ffffffff81aecfd2: class_remove_file_ns (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void class_remove_file_ns(const struct class *cls, const struct class_attribute *attr, const void *ns);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/class.c (ffffffff81b3b2c0)
Location: drivers/base/class.c:145
Inline: False
Direct callers:
  - net/core/net-sysfs.c:netdev_class_remove_file_ns
```
**Symbols:**

```
ffffffff81b3b2c0-ffffffff81b3b30b: class_remove_file_ns (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void class_remove_file_ns(const struct class *cls, const struct class_attribute *attr, const void *ns);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/class.c (ffffffff81b92e10)
Location: drivers/base/class.c:145
Inline: False
Direct callers:
  - drivers/gpu/drm/drm_sysfs.c:drm_sysfs_destroy
  - net/core/net-sysfs.c:netdev_class_remove_file_ns
```
**Symbols:**

```
ffffffff81b92e10-ffffffff81b92e5b: class_remove_file_ns (STB_GLOBAL)
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
void class_remove_file_ns(struct class *cls, const struct class_attribute *attr, const void *ns);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/class.c (ffff8000108ec2a8)
Location: drivers/base/class.c:100
Inline: False
Direct callers:
  - net/core/net-sysfs.c:netdev_class_remove_file_ns
```
**Symbols:**

```
ffff8000108ec2a8-ffff8000108ec2f4: class_remove_file_ns (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void class_remove_file_ns(struct class *cls, const struct class_attribute *attr, const void *ns);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/class.c (c09da218)
Location: drivers/base/class.c:100
Inline: False
Direct callers:
  - net/core/net-sysfs.c:netdev_class_remove_file_ns
```
**Symbols:**

```
c09da218-c09da244: class_remove_file_ns (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void class_remove_file_ns(struct class *cls, const struct class_attribute *attr, const void *ns);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/class.c (c000000000983ce0)
Location: drivers/base/class.c:100
Inline: False
Direct callers:
  - net/core/net-sysfs.c:netdev_class_remove_file_ns
```
**Symbols:**

```
c000000000983ce0-c000000000983d24: class_remove_file_ns (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void class_remove_file_ns(struct class *cls, const struct class_attribute *attr, const void *ns);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/class.c (ffffffe00057f846)
Location: drivers/base/class.c:100
Inline: False
Direct callers:
  - net/core/net-sysfs.c:netdev_class_remove_file_ns
```
**Symbols:**

```
ffffffe00057f846-ffffffe00057f884: class_remove_file_ns (STB_GLOBAL)
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
void class_remove_file_ns(struct class *cls, const struct class_attribute *attr, const void *ns);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/class.c (ffffffff816c6570)
Location: drivers/base/class.c:100
Inline: False
Direct callers:
  - net/core/net-sysfs.c:netdev_class_remove_file_ns
```
**Symbols:**

```
ffffffff816c6570-ffffffff816c658e: class_remove_file_ns (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void class_remove_file_ns(struct class *cls, const struct class_attribute *attr, const void *ns);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/class.c (ffffffff816a17d0)
Location: drivers/base/class.c:100
Inline: False
Direct callers:
  - net/core/net-sysfs.c:netdev_class_remove_file_ns
```
**Symbols:**

```
ffffffff816a17d0-ffffffff816a17ee: class_remove_file_ns (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void class_remove_file_ns(struct class *cls, const struct class_attribute *attr, const void *ns);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/class.c (ffffffff816f4a40)
Location: drivers/base/class.c:100
Inline: False
Direct callers:
  - net/core/net-sysfs.c:netdev_class_remove_file_ns
```
**Symbols:**

```
ffffffff816f4a40-ffffffff816f4a5e: class_remove_file_ns (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void class_remove_file_ns(struct class *cls, const struct class_attribute *attr, const void *ns);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/class.c (ffffffff8170f2d0)
Location: drivers/base/class.c:100
Inline: False
Direct callers:
  - net/core/net-sysfs.c:netdev_class_remove_file_ns
```
**Symbols:**

```
ffffffff8170f2d0-ffffffff8170f2ee: class_remove_file_ns (STB_GLOBAL)
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
<details>
<summary>Changed between <code>6.2</code> and <code>6.5</code> ⚠️</summary>
<ul>
<li>
<b>Param type changed. </b>
<code>struct class *cls</code> ➡️ <code>const struct class *cls</code>
</li>
</ul>
</details>
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
