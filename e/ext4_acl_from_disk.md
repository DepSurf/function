# Function: <code>ext4_acl_from_disk</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/ext4/acl.c (ffffffff812e41ed)
Location: fs/ext4/acl.c:16
Inline: True
Inline callers:
  - fs/ext4/acl.c:ext4_get_acl
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/ext4/acl.c (ffffffff81314150)
Location: fs/ext4/acl.c:16
Inline: True
Inline callers:
  - fs/ext4/acl.c:ext4_get_acl
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/ext4/acl.c (ffffffff8132a130)
Location: fs/ext4/acl.c:16
Inline: True
Inline callers:
  - fs/ext4/acl.c:ext4_get_acl
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/ext4/acl.c (ffffffff8133f2e8)
Location: fs/ext4/acl.c:17
Inline: True
Inline callers:
  - fs/ext4/acl.c:ext4_get_acl
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/ext4/acl.c (ffffffff813638f8)
Location: fs/ext4/acl.c:18
Inline: True
Inline callers:
  - fs/ext4/acl.c:ext4_get_acl
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/ext4/acl.c (ffffffff81392049)
Location: fs/ext4/acl.c:18
Inline: True
Inline callers:
  - fs/ext4/acl.c:ext4_get_acl
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/ext4/acl.c (ffffffff813aac89)
Location: fs/ext4/acl.c:18
Inline: True
Inline callers:
  - fs/ext4/acl.c:ext4_get_acl
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/ext4/acl.c (ffffffff813d4e9d)
Location: fs/ext4/acl.c:18
Inline: True
Inline callers:
  - fs/ext4/acl.c:ext4_get_acl
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/ext4/acl.c (ffffffff813ee56d)
Location: fs/ext4/acl.c:18
Inline: True
Inline callers:
  - fs/ext4/acl.c:ext4_get_acl
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
struct posix_acl *ext4_acl_from_disk(const void *value, size_t size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/acl.c (ffffffff8143b500)
Location: fs/ext4/acl.c:18
Inline: False
Direct callers:
  - fs/ext4/acl.c:ext4_get_acl
```
**Symbols:**

```
ffffffff8143b500-ffffffff8143b6ec: ext4_acl_from_disk (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
struct posix_acl *ext4_acl_from_disk(const void *value, size_t size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/acl.c (ffffffff81457830)
Location: fs/ext4/acl.c:18
Inline: False
Direct callers:
  - fs/ext4/acl.c:ext4_get_acl
```
**Symbols:**

```
ffffffff81457830-ffffffff81457a1c: ext4_acl_from_disk (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
struct posix_acl *ext4_acl_from_disk(const void *value, size_t size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/acl.c (ffffffff8145d1e0)
Location: fs/ext4/acl.c:18
Inline: False
Direct callers:
  - fs/ext4/acl.c:ext4_get_acl
```
**Symbols:**

```
ffffffff8145d1e0-ffffffff8145d3b6: ext4_acl_from_disk (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
struct posix_acl *ext4_acl_from_disk(const void *value, size_t size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/acl.c (ffffffff814b2680)
Location: fs/ext4/acl.c:18
Inline: False
Direct callers:
  - fs/ext4/acl.c:ext4_get_acl
```
**Symbols:**

```
ffffffff814b2680-ffffffff814b2856: ext4_acl_from_disk (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
struct posix_acl *ext4_acl_from_disk(const void *value, size_t size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/acl.c (ffffffff8153b2d0)
Location: fs/ext4/acl.c:18
Inline: False
Direct callers:
  - fs/ext4/acl.c:ext4_get_acl
```
**Symbols:**

```
ffffffff8153b2d0-ffffffff8153b4ad: ext4_acl_from_disk (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
struct posix_acl *ext4_acl_from_disk(const void *value, size_t size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/acl.c (ffffffff815d98d0)
Location: fs/ext4/acl.c:18
Inline: False
Direct callers:
  - fs/ext4/acl.c:ext4_get_acl
```
**Symbols:**

```
ffffffff815d98d0-ffffffff815d9abe: ext4_acl_from_disk (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
struct posix_acl *ext4_acl_from_disk(const void *value, size_t size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/acl.c (ffffffff81611490)
Location: fs/ext4/acl.c:18
Inline: False
Direct callers:
  - fs/ext4/acl.c:ext4_get_acl
```
**Symbols:**

```
ffffffff81611490-ffffffff81611690: ext4_acl_from_disk (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
struct posix_acl *ext4_acl_from_disk(const void *value, size_t size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/acl.c (ffffffff8164a250)
Location: fs/ext4/acl.c:18
Inline: False
Direct callers:
  - fs/ext4/acl.c:ext4_get_acl
```
**Symbols:**

```
ffffffff8164a250-ffffffff8164a450: ext4_acl_from_disk (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/ext4/acl.c (ffff8000104c79b4)
Location: fs/ext4/acl.c:18
Inline: True
Inline callers:
  - fs/ext4/acl.c:ext4_get_acl
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/ext4/acl.c (c068b60c)
Location: fs/ext4/acl.c:18
Inline: True
Inline callers:
  - fs/ext4/acl.c:ext4_get_acl
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/ext4/acl.c (c0000000005ffe60)
Location: fs/ext4/acl.c:18
Inline: True
Inline callers:
  - fs/ext4/acl.c:ext4_get_acl
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/ext4/acl.c (ffffffe00034184e)
Location: fs/ext4/acl.c:18
Inline: True
Inline callers:
  - fs/ext4/acl.c:ext4_get_acl
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/ext4/acl.c (ffffffff813e6b4d)
Location: fs/ext4/acl.c:18
Inline: True
Inline callers:
  - fs/ext4/acl.c:ext4_get_acl
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/ext4/acl.c (ffffffff813d75cd)
Location: fs/ext4/acl.c:18
Inline: True
Inline callers:
  - fs/ext4/acl.c:ext4_get_acl
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/ext4/acl.c (ffffffff813e3ecd)
Location: fs/ext4/acl.c:18
Inline: True
Inline callers:
  - fs/ext4/acl.c:ext4_get_acl
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/ext4/acl.c (ffffffff813f92dd)
Location: fs/ext4/acl.c:18
Inline: True
Inline callers:
  - fs/ext4/acl.c:ext4_get_acl
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
