# Function: <code>bits_to_user</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline ⚠️</summary>

```c
int bits_to_user(long unsigned int *bits, unsigned int maxbit, unsigned int maxlen, void *p, int compat);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/input/evdev.c (ffffffff8166d250)
Location: drivers/input/evdev.c:730
Inline: True
Inline callers:
  - drivers/input/evdev.c:evdev_do_ioctl
Direct callers:
  - drivers/input/evdev.c:evdev_handle_get_val
  - drivers/input/evdev.c:evdev_do_ioctl
  - drivers/input/evdev.c:evdev_do_ioctl
```
**Symbols:**

```
ffffffff8166d250-ffffffff8166d2a0: bits_to_user (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int bits_to_user(long unsigned int *bits, unsigned int maxbit, unsigned int maxlen, void *p, int compat);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/input/evdev.c (ffffffff816cdbd0)
Location: drivers/input/evdev.c:730
Inline: False
Direct callers:
  - drivers/input/evdev.c:evdev_do_ioctl
  - drivers/input/evdev.c:evdev_do_ioctl
  - drivers/input/evdev.c:evdev_do_ioctl
  - drivers/input/evdev.c:evdev_handle_get_val
```
**Symbols:**

```
ffffffff816cdbd0-ffffffff816cdc47: bits_to_user (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int bits_to_user(long unsigned int *bits, unsigned int maxbit, unsigned int maxlen, void *p, int compat);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/input/evdev.c (ffffffff816fbb70)
Location: drivers/input/evdev.c:730
Inline: False
Direct callers:
  - drivers/input/evdev.c:evdev_do_ioctl
  - drivers/input/evdev.c:evdev_do_ioctl
  - drivers/input/evdev.c:evdev_do_ioctl
  - drivers/input/evdev.c:evdev_handle_get_val
```
**Symbols:**

```
ffffffff816fbb70-ffffffff816fbbe7: bits_to_user (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int bits_to_user(long unsigned int *bits, unsigned int maxbit, unsigned int maxlen, void *p, int compat);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/input/evdev.c (ffffffff81711cb0)
Location: drivers/input/evdev.c:730
Inline: False
Direct callers:
  - drivers/input/evdev.c:evdev_do_ioctl
  - drivers/input/evdev.c:evdev_do_ioctl
  - drivers/input/evdev.c:evdev_do_ioctl
  - drivers/input/evdev.c:evdev_handle_get_val
```
**Symbols:**

```
ffffffff81711cb0-ffffffff81711d23: bits_to_user (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int bits_to_user(long unsigned int *bits, unsigned int maxbit, unsigned int maxlen, void *p, int compat);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/input/evdev.c (ffffffff81782ee0)
Location: drivers/input/evdev.c:730
Inline: False
Direct callers:
  - drivers/input/evdev.c:evdev_do_ioctl
  - drivers/input/evdev.c:evdev_do_ioctl
  - drivers/input/evdev.c:evdev_do_ioctl
  - drivers/input/evdev.c:evdev_handle_get_val
```
**Symbols:**

```
ffffffff81782ee0-ffffffff81782f53: bits_to_user (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int bits_to_user(long unsigned int *bits, unsigned int maxbit, unsigned int maxlen, void *p, int compat);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/input/evdev.c (ffffffff817c4020)
Location: drivers/input/evdev.c:736
Inline: False
Direct callers:
  - drivers/input/evdev.c:evdev_do_ioctl
  - drivers/input/evdev.c:evdev_do_ioctl
  - drivers/input/evdev.c:evdev_do_ioctl
  - drivers/input/evdev.c:evdev_handle_get_val
```
**Symbols:**

```
ffffffff817c4020-ffffffff817c4093: bits_to_user (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int bits_to_user(long unsigned int *bits, unsigned int maxbit, unsigned int maxlen, void *p, int compat);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/input/evdev.c (ffffffff817eb5a0)
Location: drivers/input/evdev.c:737
Inline: False
Direct callers:
  - drivers/input/evdev.c:evdev_do_ioctl
  - drivers/input/evdev.c:evdev_do_ioctl
  - drivers/input/evdev.c:evdev_do_ioctl
  - drivers/input/evdev.c:evdev_handle_get_val
```
**Symbols:**

```
ffffffff817eb5a0-ffffffff817eb613: bits_to_user (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int bits_to_user(long unsigned int *bits, unsigned int maxbit, unsigned int maxlen, void *p, int compat);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/input/evdev.c (ffffffff8182c110)
Location: drivers/input/evdev.c:733
Inline: False
Direct callers:
  - drivers/input/evdev.c:evdev_do_ioctl
  - drivers/input/evdev.c:evdev_do_ioctl
  - drivers/input/evdev.c:evdev_do_ioctl
  - drivers/input/evdev.c:evdev_handle_get_val
```
**Symbols:**

```
ffffffff8182c110-ffffffff8182c18c: bits_to_user (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int bits_to_user(long unsigned int *bits, unsigned int maxbit, unsigned int maxlen, void *p, int compat);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/input/evdev.c (ffffffff8185d530)
Location: drivers/input/evdev.c:711
Inline: False
Direct callers:
  - drivers/input/evdev.c:evdev_do_ioctl
  - drivers/input/evdev.c:evdev_do_ioctl
  - drivers/input/evdev.c:evdev_do_ioctl
  - drivers/input/evdev.c:evdev_handle_get_val
```
**Symbols:**

```
ffffffff8185d530-ffffffff8185d5ac: bits_to_user (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int bits_to_user(long unsigned int *bits, unsigned int maxbit, unsigned int maxlen, void *p, int compat);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/input/evdev.c (ffffffff8192fef0)
Location: drivers/input/evdev.c:702
Inline: False
Direct callers:
  - drivers/input/evdev.c:evdev_do_ioctl
  - drivers/input/evdev.c:evdev_do_ioctl
  - drivers/input/evdev.c:evdev_do_ioctl
  - drivers/input/evdev.c:evdev_handle_get_val
```
**Symbols:**

```
ffffffff8192fef0-ffffffff8192ff6c: bits_to_user (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int bits_to_user(long unsigned int *bits, unsigned int maxbit, unsigned int maxlen, void *p, int compat);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/input/evdev.c (ffffffff819371b0)
Location: drivers/input/evdev.c:702
Inline: False
Direct callers:
  - drivers/input/evdev.c:evdev_do_ioctl
  - drivers/input/evdev.c:evdev_do_ioctl
  - drivers/input/evdev.c:evdev_do_ioctl
  - drivers/input/evdev.c:evdev_handle_get_val
```
**Symbols:**

```
ffffffff819371b0-ffffffff8193722c: bits_to_user (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int bits_to_user(long unsigned int *bits, unsigned int maxbit, unsigned int maxlen, void *p, int compat);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/input/evdev.c (ffffffff8191a6b0)
Location: drivers/input/evdev.c:702
Inline: False
Direct callers:
  - drivers/input/evdev.c:evdev_do_ioctl
  - drivers/input/evdev.c:evdev_do_ioctl
  - drivers/input/evdev.c:evdev_do_ioctl
  - drivers/input/evdev.c:evdev_handle_get_val
```
**Symbols:**

```
ffffffff8191a6b0-ffffffff8191a72c: bits_to_user (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
int bits_to_user(long unsigned int *bits, unsigned int maxbit, unsigned int maxlen, void *p, int compat);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/input/evdev.c (ffffffff819be3a8)
Location: drivers/input/evdev.c:702
Inline: True
Inline callers:
  - drivers/input/evdev.c:evdev_do_ioctl
Direct callers:
  - drivers/input/evdev.c:evdev_do_ioctl
  - drivers/input/evdev.c:evdev_do_ioctl
  - drivers/input/evdev.c:evdev_handle_get_val
```
**Symbols:**

```
ffffffff819bc950-ffffffff819bc9cc: bits_to_user (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
int bits_to_user(long unsigned int *bits, unsigned int maxbit, unsigned int maxlen, void *p, int compat);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/input/evdev.c (ffffffff81b1e6ac)
Location: drivers/input/evdev.c:702
Inline: True
Inline callers:
  - drivers/input/evdev.c:evdev_do_ioctl
Direct callers:
  - drivers/input/evdev.c:evdev_do_ioctl
  - drivers/input/evdev.c:evdev_do_ioctl
  - drivers/input/evdev.c:evdev_handle_get_val
```
**Symbols:**

```
ffffffff81b1d7c0-ffffffff81b1d842: bits_to_user (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
int bits_to_user(long unsigned int *bits, unsigned int maxbit, unsigned int maxlen, void *p, int compat);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/input/evdev.c (ffffffff81cb07b1)
Location: drivers/input/evdev.c:702
Inline: True
Inline callers:
  - drivers/input/evdev.c:evdev_do_ioctl
Direct callers:
  - drivers/input/evdev.c:evdev_do_ioctl
  - drivers/input/evdev.c:evdev_get_mask
  - drivers/input/evdev.c:evdev_handle_get_val
```
**Symbols:**

```
ffffffff81caf7c0-ffffffff81caf842: bits_to_user (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
int bits_to_user(long unsigned int *bits, unsigned int maxbit, unsigned int maxlen, void *p, int compat);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/input/evdev.c (ffffffff81d17d8a)
Location: drivers/input/evdev.c:702
Inline: True
Inline callers:
  - drivers/input/evdev.c:evdev_do_ioctl
Direct callers:
  - drivers/input/evdev.c:evdev_do_ioctl
  - drivers/input/evdev.c:evdev_get_mask
  - drivers/input/evdev.c:evdev_handle_get_val
```
**Symbols:**

```
ffffffff81d16dc0-ffffffff81d16e42: bits_to_user (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
int bits_to_user(long unsigned int *bits, unsigned int maxbit, unsigned int maxlen, void *p, int compat);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/input/evdev.c (ffffffff81dcda3a)
Location: drivers/input/evdev.c:702
Inline: True
Inline callers:
  - drivers/input/evdev.c:evdev_do_ioctl
Direct callers:
  - drivers/input/evdev.c:evdev_do_ioctl
  - drivers/input/evdev.c:evdev_get_mask
  - drivers/input/evdev.c:evdev_handle_get_val
```
**Symbols:**

```
ffffffff81dcca70-ffffffff81dccaf2: bits_to_user (STB_LOCAL)
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
int bits_to_user(long unsigned int *bits, unsigned int maxbit, unsigned int maxlen, void *p, int compat);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/input/evdev.c (ffff800010a9efa8)
Location: drivers/input/evdev.c:711
Inline: False
Direct callers:
  - drivers/input/evdev.c:evdev_do_ioctl
  - drivers/input/evdev.c:evdev_do_ioctl
  - drivers/input/evdev.c:evdev_do_ioctl
  - drivers/input/evdev.c:evdev_handle_get_val
```
**Symbols:**

```
ffff800010a9efa8-ffff800010a9f1b8: bits_to_user (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/input/evdev.c (c0b7f390)
Location: drivers/input/evdev.c:745
Inline: True
```
**Symbols:**

```
c0b7f390-c0b7f43c: bits_to_user.constprop.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int bits_to_user(long unsigned int *bits, unsigned int maxbit, unsigned int maxlen, void *p, int compat);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/input/evdev.c (c000000000b7f630)
Location: drivers/input/evdev.c:711
Inline: False
Direct callers:
  - drivers/input/evdev.c:evdev_do_ioctl
  - drivers/input/evdev.c:evdev_do_ioctl
  - drivers/input/evdev.c:evdev_do_ioctl
  - drivers/input/evdev.c:evdev_handle_get_val
```
**Symbols:**

```
c000000000b7f630-c000000000b7f6e8: bits_to_user (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/input/evdev.c (ffffffe0006ae0c4)
Location: drivers/input/evdev.c:745
Inline: True
```
**Symbols:**

```
ffffffe0006ae0c4-ffffffe0006ae12e: bits_to_user.isra.0 (STB_LOCAL)
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
int bits_to_user(long unsigned int *bits, unsigned int maxbit, unsigned int maxlen, void *p, int compat);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/input/evdev.c (ffffffff81812540)
Location: drivers/input/evdev.c:711
Inline: False
Direct callers:
  - drivers/input/evdev.c:evdev_do_ioctl
  - drivers/input/evdev.c:evdev_do_ioctl
  - drivers/input/evdev.c:evdev_do_ioctl
  - drivers/input/evdev.c:evdev_handle_get_val
```
**Symbols:**

```
ffffffff81812540-ffffffff818125bc: bits_to_user (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int bits_to_user(long unsigned int *bits, unsigned int maxbit, unsigned int maxlen, void *p, int compat);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/input/evdev.c (ffffffff817d9c80)
Location: drivers/input/evdev.c:711
Inline: False
Direct callers:
  - drivers/input/evdev.c:evdev_do_ioctl
  - drivers/input/evdev.c:evdev_do_ioctl
  - drivers/input/evdev.c:evdev_do_ioctl
  - drivers/input/evdev.c:evdev_handle_get_val
```
**Symbols:**

```
ffffffff817d9c80-ffffffff817d9cfc: bits_to_user (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int bits_to_user(long unsigned int *bits, unsigned int maxbit, unsigned int maxlen, void *p, int compat);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/input/evdev.c (ffffffff818516c0)
Location: drivers/input/evdev.c:711
Inline: False
Direct callers:
  - drivers/input/evdev.c:evdev_do_ioctl
  - drivers/input/evdev.c:evdev_do_ioctl
  - drivers/input/evdev.c:evdev_do_ioctl
  - drivers/input/evdev.c:evdev_handle_get_val
```
**Symbols:**

```
ffffffff818516c0-ffffffff8185173c: bits_to_user (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int bits_to_user(long unsigned int *bits, unsigned int maxbit, unsigned int maxlen, void *p, int compat);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/input/evdev.c (ffffffff8186cb40)
Location: drivers/input/evdev.c:711
Inline: False
Direct callers:
  - drivers/input/evdev.c:evdev_do_ioctl
  - drivers/input/evdev.c:evdev_do_ioctl
  - drivers/input/evdev.c:evdev_do_ioctl
  - drivers/input/evdev.c:evdev_handle_get_val
```
**Symbols:**

```
ffffffff8186cb40-ffffffff8186cbbc: bits_to_user (STB_LOCAL)
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
No changes between <code>amd64</code> and <code>ppc64el</code> ✅
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
