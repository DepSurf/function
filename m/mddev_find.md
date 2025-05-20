# Function: <code>mddev_find</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
struct mddev *mddev_find(dev_t unit);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/md.c (ffffffff81694760)
Location: drivers/md/md.c:516
Inline: False
Direct callers:
  - drivers/md/md.c:md_alloc
  - drivers/md/md.c:md_open
  - drivers/md/md.c:md_ioctl
```
**Symbols:**

```
ffffffff81694760-ffffffff816949d7: mddev_find (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
struct mddev *mddev_find(dev_t unit);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/md.c (ffffffff816f51c0)
Location: drivers/md/md.c:511
Inline: False
Direct callers:
  - drivers/md/md.c:md_open
  - drivers/md/md.c:md_ioctl
  - drivers/md/md.c:md_alloc
```
**Symbols:**

```
ffffffff816f51c0-ffffffff816f542b: mddev_find (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
struct mddev *mddev_find(dev_t unit);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/md.c (ffffffff817268d0)
Location: drivers/md/md.c:524
Inline: False
Direct callers:
  - drivers/md/md.c:md_open
  - drivers/md/md.c:md_ioctl
  - drivers/md/md.c:md_alloc
```
**Symbols:**

```
ffffffff817268d0-ffffffff81726b3b: mddev_find (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
struct mddev *mddev_find(dev_t unit);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/md.c (ffffffff8173ef60)
Location: drivers/md/md.c:536
Inline: False
Direct callers:
  - drivers/md/md.c:md_open
  - drivers/md/md.c:md_ioctl
  - drivers/md/md.c:md_alloc
```
**Symbols:**

```
ffffffff8173ef60-ffffffff8173f1d4: mddev_find (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
struct mddev *mddev_find(dev_t unit);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/md.c (ffffffff817b0f70)
Location: drivers/md/md.c:570
Inline: False
Direct callers:
  - drivers/md/md.c:md_open
  - drivers/md/md.c:md_ioctl
  - drivers/md/md.c:md_alloc
```
**Symbols:**

```
ffffffff817b0f70-ffffffff817b11e4: mddev_find (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
struct mddev *mddev_find(dev_t unit);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/md.c (ffffffff817f9120)
Location: drivers/md/md.c:581
Inline: False
Direct callers:
  - drivers/md/md.c:md_open
  - drivers/md/md.c:md_ioctl
  - drivers/md/md.c:md_alloc
```
**Symbols:**

```
ffffffff817f9120-ffffffff817f9376: mddev_find (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
struct mddev *mddev_find(dev_t unit);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/md.c (ffffffff818250f0)
Location: drivers/md/md.c:574
Inline: False
Direct callers:
  - drivers/md/md.c:md_open
  - drivers/md/md.c:md_ioctl
  - drivers/md/md.c:md_alloc
```
**Symbols:**

```
ffffffff818250f0-ffffffff81825356: mddev_find (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
struct mddev *mddev_find(dev_t unit);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/md.c (ffffffff81867580)
Location: drivers/md/md.c:635
Inline: False
Direct callers:
  - drivers/md/md.c:md_open
  - drivers/md/md.c:autorun_devices
  - drivers/md/md.c:md_alloc
```
**Symbols:**

```
ffffffff81867580-ffffffff818677c0: mddev_find (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
struct mddev *mddev_find(dev_t unit);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/md.c (ffffffff81899310)
Location: drivers/md/md.c:647
Inline: False
Direct callers:
  - drivers/md/md.c:md_open
  - drivers/md/md.c:autorun_devices
  - drivers/md/md.c:md_alloc
```
**Symbols:**

```
ffffffff81899310-ffffffff81899550: mddev_find (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
struct mddev *mddev_find(dev_t unit);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/md.c (ffffffff81968880)
Location: drivers/md/md.c:773
Inline: False
Direct callers:
  - drivers/md/md.c:md_open
  - drivers/md/md.c:autorun_devices
  - drivers/md/md.c:md_alloc
```
**Symbols:**

```
ffffffff81968880-ffffffff81968ac0: mddev_find (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
struct mddev *mddev_find(dev_t unit);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/md.c (ffffffff8196f350)
Location: drivers/md/md.c:755
Inline: False
Direct callers:
  - drivers/md/md.c:md_open
  - drivers/md/md.c:autorun_devices
  - drivers/md/md.c:md_alloc
```
**Symbols:**

```
ffffffff8196f350-ffffffff8196f590: mddev_find (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
struct mddev *mddev_find(dev_t unit);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/md.c (ffffffff8194f180)
Location: drivers/md/md.c:730
Inline: False
Direct callers:
  - drivers/md/md.c:md_open
  - drivers/md/md.c:autorun_devices
```
**Symbols:**

```
ffffffff8194f180-ffffffff8194f205: mddev_find (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
struct mddev *mddev_find(dev_t unit);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/md.c (ffffffff819f4590)
Location: drivers/md/md.c:731
Inline: False
Direct callers:
  - drivers/md/md.c:md_open
  - drivers/md/md.c:autorun_devices
```
**Symbols:**

```
ffffffff819f4590-ffffffff819f4615: mddev_find (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
struct mddev *mddev_find(dev_t unit);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/md.c (ffffffff81b54fa0)
Location: drivers/md/md.c:736
Inline: False
Direct callers:
  - drivers/md/md.c:md_open
  - drivers/md/md.c:autorun_devices
```
**Symbols:**

```
ffffffff81b54fa0-ffffffff81b5502c: mddev_find (STB_LOCAL)
```
</details>
</li>
<li>
In <code>6.2</code>: Absent ⚠️
</li>
<li>
In <code>6.5</code>: Absent ⚠️
</li>
<li>
In <code>6.8</code>: Absent ⚠️
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: ✅</summary>

```c
struct mddev *mddev_find(dev_t unit);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/md.c (ffff800010aeb1d0)
Location: drivers/md/md.c:647
Inline: False
Direct callers:
  - drivers/md/md.c:md_open
  - drivers/md/md.c:autorun_devices
  - drivers/md/md.c:md_alloc
```
**Symbols:**

```
ffff800010aeb1d0-ffff800010aeb458: mddev_find (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
struct mddev *mddev_find(dev_t unit);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/md.c (c0bc6528)
Location: drivers/md/md.c:647
Inline: False
Direct callers:
  - drivers/md/md.c:md_open
  - drivers/md/md.c:md_ioctl
  - drivers/md/md.c:md_alloc
```
**Symbols:**

```
c0bc6528-c0bc6798: mddev_find (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
struct mddev *mddev_find(dev_t unit);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/md.c (c000000000bd81d0)
Location: drivers/md/md.c:647
Inline: False
Direct callers:
  - drivers/md/md.c:md_open
  - drivers/md/md.c:md_ioctl
  - drivers/md/md.c:md_alloc
```
**Symbols:**

```
c000000000bd81d0-c000000000bd8604: mddev_find (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
struct mddev *mddev_find(dev_t unit);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/md.c (ffffffe0006e1c06)
Location: drivers/md/md.c:647
Inline: False
Direct callers:
  - drivers/md/md.c:md_open
  - drivers/md/md.c:md_ioctl
  - drivers/md/md.c:md_alloc
```
**Symbols:**

```
ffffffe0006e1c06-ffffffe0006e1f0c: mddev_find (STB_LOCAL)
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
struct mddev *mddev_find(dev_t unit);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/md.c (ffffffff8183f190)
Location: drivers/md/md.c:647
Inline: False
Direct callers:
  - drivers/md/md.c:md_open
  - drivers/md/md.c:autorun_devices
  - drivers/md/md.c:md_alloc
```
**Symbols:**

```
ffffffff8183f190-ffffffff8183f3d0: mddev_find (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
struct mddev *mddev_find(dev_t unit);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/md.c (ffffffff818067f0)
Location: drivers/md/md.c:647
Inline: False
Direct callers:
  - drivers/md/md.c:md_open
  - drivers/md/md.c:autorun_devices
  - drivers/md/md.c:md_alloc
```
**Symbols:**

```
ffffffff818067f0-ffffffff81806a30: mddev_find (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
struct mddev *mddev_find(dev_t unit);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/md.c (ffffffff8188e7c0)
Location: drivers/md/md.c:647
Inline: False
Direct callers:
  - drivers/md/md.c:md_open
  - drivers/md/md.c:autorun_devices
  - drivers/md/md.c:md_alloc
```
**Symbols:**

```
ffffffff8188e7c0-ffffffff8188ea00: mddev_find (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
struct mddev *mddev_find(dev_t unit);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/md.c (ffffffff818a8df0)
Location: drivers/md/md.c:647
Inline: False
Direct callers:
  - drivers/md/md.c:md_open
  - drivers/md/md.c:autorun_devices
  - drivers/md/md.c:md_alloc
```
**Symbols:**

```
ffffffff818a8df0-ffffffff818a907d: mddev_find (STB_LOCAL)
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
