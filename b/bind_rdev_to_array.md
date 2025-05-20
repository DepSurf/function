# Function: <code>bind_rdev_to_array</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int bind_rdev_to_array(struct md_rdev *rdev, struct mddev *mddev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/md.c (ffffffff8168ffb0)
Location: drivers/md/md.c:2049
Inline: False
Direct callers:
  - drivers/md/md.c:new_dev_store
  - drivers/md/md.c:add_new_disk
  - drivers/md/md.c:add_new_disk
  - drivers/md/md.c:md_ioctl
  - drivers/md/md.c:md_ioctl
```
**Symbols:**

```
ffffffff8168ffb0-ffffffff8169025e: bind_rdev_to_array (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int bind_rdev_to_array(struct md_rdev *rdev, struct mddev *mddev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/md.c (ffffffff816f0c60)
Location: drivers/md/md.c:2046
Inline: False
Direct callers:
  - drivers/md/md.c:md_ioctl
  - drivers/md/md.c:md_ioctl
  - drivers/md/md.c:add_new_disk
  - drivers/md/md.c:add_new_disk
  - drivers/md/md.c:new_dev_store
```
**Symbols:**

```
ffffffff816f0c60-ffffffff816f0f45: bind_rdev_to_array (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int bind_rdev_to_array(struct md_rdev *rdev, struct mddev *mddev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/md.c (ffffffff817224f0)
Location: drivers/md/md.c:2082
Inline: False
Direct callers:
  - drivers/md/md.c:md_ioctl
  - drivers/md/md.c:md_ioctl
  - drivers/md/md.c:add_new_disk
  - drivers/md/md.c:add_new_disk
  - drivers/md/md.c:new_dev_store
```
**Symbols:**

```
ffffffff817224f0-ffffffff817227fe: bind_rdev_to_array (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int bind_rdev_to_array(struct md_rdev *rdev, struct mddev *mddev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/md.c (ffffffff8173ec20)
Location: drivers/md/md.c:2113
Inline: False
Direct callers:
  - drivers/md/md.c:md_ioctl
  - drivers/md/md.c:md_ioctl
  - drivers/md/md.c:add_new_disk
  - drivers/md/md.c:add_new_disk
  - drivers/md/md.c:new_dev_store
```
**Symbols:**

```
ffffffff8173ec20-ffffffff8173ef53: bind_rdev_to_array (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int bind_rdev_to_array(struct md_rdev *rdev, struct mddev *mddev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/md.c (ffffffff817b0bf0)
Location: drivers/md/md.c:2160
Inline: False
Direct callers:
  - drivers/md/md.c:md_ioctl
  - drivers/md/md.c:md_ioctl
  - drivers/md/md.c:add_new_disk
  - drivers/md/md.c:add_new_disk
  - drivers/md/md.c:new_dev_store
```
**Symbols:**

```
ffffffff817b0bf0-ffffffff817b0f23: bind_rdev_to_array (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Transformation ⚠️</summary>

```c
int bind_rdev_to_array(struct md_rdev *rdev, struct mddev *mddev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/md/md.c (0)
Location: drivers/md/md.c:2175
Inline: False
Direct callers:
  - drivers/md/md.c:md_ioctl
  - drivers/md/md.c:md_ioctl
  - drivers/md/md.c:add_new_disk
  - drivers/md/md.c:add_new_disk
  - drivers/md/md.c:add_new_disk
  - drivers/md/md.c:new_dev_store
```
**Symbols:**

```
ffffffff817f4e90-ffffffff817f5173: bind_rdev_to_array (STB_LOCAL)
ffffffff8180003c-ffffffff81800094: bind_rdev_to_array.cold.81 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Transformation ⚠️</summary>

```c
int bind_rdev_to_array(struct md_rdev *rdev, struct mddev *mddev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/md/md.c (0)
Location: drivers/md/md.c:2166
Inline: False
Direct callers:
  - drivers/md/md.c:md_ioctl
  - drivers/md/md.c:md_ioctl
  - drivers/md/md.c:add_new_disk
  - drivers/md/md.c:add_new_disk
  - drivers/md/md.c:add_new_disk
  - drivers/md/md.c:new_dev_store
```
**Symbols:**

```
ffffffff818210a0-ffffffff81821383: bind_rdev_to_array (STB_LOCAL)
ffffffff8182c262-ffffffff8182c2ba: bind_rdev_to_array.cold.81 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
int bind_rdev_to_array(struct md_rdev *rdev, struct mddev *mddev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/md/md.c (0)
Location: drivers/md/md.c:2225
Inline: False
Direct callers:
  - drivers/md/md.c:md_ioctl
  - drivers/md/md.c:add_new_disk
  - drivers/md/md.c:add_new_disk
  - drivers/md/md.c:add_new_disk
  - drivers/md/md.c:autorun_devices
  - drivers/md/md.c:new_dev_store
```
**Symbols:**

```
ffffffff818634c0-ffffffff818637a1: bind_rdev_to_array (STB_LOCAL)
ffffffff8186e786-ffffffff8186e7e0: bind_rdev_to_array.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
int bind_rdev_to_array(struct md_rdev *rdev, struct mddev *mddev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/md/md.c (0)
Location: drivers/md/md.c:2279
Inline: False
Direct callers:
  - drivers/md/md.c:md_ioctl
  - drivers/md/md.c:add_new_disk
  - drivers/md/md.c:add_new_disk
  - drivers/md/md.c:add_new_disk
  - drivers/md/md.c:autorun_devices
  - drivers/md/md.c:new_dev_store
```
**Symbols:**

```
ffffffff81895210-ffffffff818954f1: bind_rdev_to_array (STB_LOCAL)
ffffffff818a0589-ffffffff818a05e3: bind_rdev_to_array.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
int bind_rdev_to_array(struct md_rdev *rdev, struct mddev *mddev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/md/md.c (0)
Location: drivers/md/md.c:2405
Inline: False
Direct callers:
  - drivers/md/md.c:hot_add_disk
  - drivers/md/md.c:add_new_disk
  - drivers/md/md.c:add_new_disk
  - drivers/md/md.c:add_new_disk
  - drivers/md/md.c:autorun_devices
  - drivers/md/md.c:new_dev_store
```
**Symbols:**

```
ffffffff81969500-ffffffff819697e1: bind_rdev_to_array (STB_LOCAL)
ffffffff81970d28-ffffffff81970d82: bind_rdev_to_array.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
int bind_rdev_to_array(struct md_rdev *rdev, struct mddev *mddev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/md/md.c (0)
Location: drivers/md/md.c:2420
Inline: False
Direct callers:
  - drivers/md/md.c:hot_add_disk
  - drivers/md/md.c:md_add_new_disk
  - drivers/md/md.c:md_add_new_disk
  - drivers/md/md.c:md_add_new_disk
  - drivers/md/md.c:autorun_devices
  - drivers/md/md.c:new_dev_store
```
**Symbols:**

```
ffffffff81970010-ffffffff81970367: bind_rdev_to_array (STB_LOCAL)
ffffffff81c26e13-ffffffff81c26e6b: bind_rdev_to_array.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
int bind_rdev_to_array(struct md_rdev *rdev, struct mddev *mddev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/md/md.c (0)
Location: drivers/md/md.c:2385
Inline: False
Direct callers:
  - drivers/md/md.c:hot_add_disk
  - drivers/md/md.c:md_add_new_disk
  - drivers/md/md.c:md_add_new_disk
  - drivers/md/md.c:md_add_new_disk
  - drivers/md/md.c:autorun_devices
  - drivers/md/md.c:new_dev_store
```
**Symbols:**

```
ffffffff81953f50-ffffffff819542ba: bind_rdev_to_array (STB_LOCAL)
ffffffff81c18fc4-ffffffff81c1901c: bind_rdev_to_array.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int bind_rdev_to_array(struct md_rdev *rdev, struct mddev *mddev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/md/md.c (0)
Location: drivers/md/md.c:2395
Inline: False
Direct callers:
  - drivers/md/md.c:hot_add_disk
  - drivers/md/md.c:md_add_new_disk
  - drivers/md/md.c:md_add_new_disk
  - drivers/md/md.c:md_add_new_disk
  - drivers/md/md.c:autorun_devices
  - drivers/md/md.c:new_dev_store
```
**Symbols:**

```
ffffffff819f9520-ffffffff819f988a: bind_rdev_to_array (STB_LOCAL)
ffffffff81d285a1-ffffffff81d285f9: bind_rdev_to_array.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int bind_rdev_to_array(struct md_rdev *rdev, struct mddev *mddev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/md/md.c (0)
Location: drivers/md/md.c:2389
Inline: False
Direct callers:
  - drivers/md/md.c:hot_add_disk
  - drivers/md/md.c:md_add_new_disk
  - drivers/md/md.c:md_add_new_disk
  - drivers/md/md.c:md_add_new_disk
  - drivers/md/md.c:autorun_devices
  - drivers/md/md.c:new_dev_store
```
**Symbols:**

```
ffffffff81b60a10-ffffffff81b60d7d: bind_rdev_to_array (STB_LOCAL)
ffffffff81ef4630-ffffffff81ef4682: bind_rdev_to_array.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int bind_rdev_to_array(struct md_rdev *rdev, struct mddev *mddev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/md.c (ffffffff81cfac50)
Location: drivers/md/md.c:2380
Inline: False
Direct callers:
  - drivers/md/md.c:hot_add_disk
  - drivers/md/md.c:md_add_new_disk
  - drivers/md/md.c:md_add_new_disk
  - drivers/md/md.c:md_add_new_disk
  - drivers/md/md.c:autorun_devices
  - drivers/md/md.c:new_dev_store
```
**Symbols:**

```
ffffffff81cfac50-ffffffff81cfb02a: bind_rdev_to_array (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int bind_rdev_to_array(struct md_rdev *rdev, struct mddev *mddev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/md.c (ffffffff81d615f0)
Location: drivers/md/md.c:2356
Inline: False
Direct callers:
  - drivers/md/md.c:hot_add_disk
  - drivers/md/md.c:md_add_new_disk
  - drivers/md/md.c:md_add_new_disk
  - drivers/md/md.c:md_add_new_disk
  - drivers/md/md.c:autorun_devices
  - drivers/md/md.c:new_dev_store
```
**Symbols:**

```
ffffffff81d615f0-ffffffff81d619cd: bind_rdev_to_array (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int bind_rdev_to_array(struct md_rdev *rdev, struct mddev *mddev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/md.c (ffffffff81e187f0)
Location: drivers/md/md.c:2486
Inline: False
Direct callers:
  - drivers/md/md.c:hot_add_disk
  - drivers/md/md.c:md_add_new_disk
  - drivers/md/md.c:md_add_new_disk
  - drivers/md/md.c:md_add_new_disk
  - drivers/md/md.c:autorun_devices
  - drivers/md/md.c:new_dev_store
```
**Symbols:**

```
ffffffff81e187f0-ffffffff81e18bd1: bind_rdev_to_array (STB_LOCAL)
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
int bind_rdev_to_array(struct md_rdev *rdev, struct mddev *mddev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/md.c (ffff800010aea0d0)
Location: drivers/md/md.c:2279
Inline: False
Direct callers:
  - drivers/md/md.c:md_ioctl
  - drivers/md/md.c:add_new_disk
  - drivers/md/md.c:add_new_disk
  - drivers/md/md.c:add_new_disk
  - drivers/md/md.c:autorun_devices
  - drivers/md/md.c:new_dev_store
```
**Symbols:**

```
ffff800010aea0d0-ffff800010aea3dc: bind_rdev_to_array (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int bind_rdev_to_array(struct md_rdev *rdev, struct mddev *mddev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/md.c (c0bcc0dc)
Location: drivers/md/md.c:2279
Inline: False
Direct callers:
  - drivers/md/md.c:md_ioctl
  - drivers/md/md.c:md_ioctl
  - drivers/md/md.c:add_new_disk
  - drivers/md/md.c:add_new_disk
  - drivers/md/md.c:add_new_disk
  - drivers/md/md.c:new_dev_store
```
**Symbols:**

```
c0bcc0dc-c0bcc424: bind_rdev_to_array (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int bind_rdev_to_array(struct md_rdev *rdev, struct mddev *mddev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/md.c (c000000000bd5e50)
Location: drivers/md/md.c:2279
Inline: False
Direct callers:
  - drivers/md/md.c:md_ioctl
  - drivers/md/md.c:md_ioctl
  - drivers/md/md.c:add_new_disk
  - drivers/md/md.c:add_new_disk
  - drivers/md/md.c:add_new_disk
  - drivers/md/md.c:new_dev_store
```
**Symbols:**

```
c000000000bd5e50-c000000000bd625c: bind_rdev_to_array (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int bind_rdev_to_array(struct md_rdev *rdev, struct mddev *mddev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/md.c (ffffffe0006dd9e8)
Location: drivers/md/md.c:2279
Inline: False
Direct callers:
  - drivers/md/md.c:md_ioctl
  - drivers/md/md.c:md_ioctl
  - drivers/md/md.c:add_new_disk
  - drivers/md/md.c:add_new_disk
  - drivers/md/md.c:new_dev_store
```
**Symbols:**

```
ffffffe0006dd9e8-ffffffe0006ddc6c: bind_rdev_to_array (STB_LOCAL)
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
int bind_rdev_to_array(struct md_rdev *rdev, struct mddev *mddev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/md/md.c (0)
Location: drivers/md/md.c:2279
Inline: False
Direct callers:
  - drivers/md/md.c:md_ioctl
  - drivers/md/md.c:add_new_disk
  - drivers/md/md.c:add_new_disk
  - drivers/md/md.c:add_new_disk
  - drivers/md/md.c:autorun_devices
  - drivers/md/md.c:new_dev_store
```
**Symbols:**

```
ffffffff8183b090-ffffffff8183b371: bind_rdev_to_array (STB_LOCAL)
ffffffff81846409-ffffffff81846463: bind_rdev_to_array.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Transformation ⚠️</summary>

```c
int bind_rdev_to_array(struct md_rdev *rdev, struct mddev *mddev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/md/md.c (0)
Location: drivers/md/md.c:2279
Inline: False
Direct callers:
  - drivers/md/md.c:md_ioctl
  - drivers/md/md.c:add_new_disk
  - drivers/md/md.c:add_new_disk
  - drivers/md/md.c:add_new_disk
  - drivers/md/md.c:autorun_devices
  - drivers/md/md.c:new_dev_store
```
**Symbols:**

```
ffffffff81802700-ffffffff818029e1: bind_rdev_to_array (STB_LOCAL)
ffffffff8180da69-ffffffff8180dac3: bind_rdev_to_array.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Transformation ⚠️</summary>

```c
int bind_rdev_to_array(struct md_rdev *rdev, struct mddev *mddev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/md/md.c (0)
Location: drivers/md/md.c:2279
Inline: False
Direct callers:
  - drivers/md/md.c:md_ioctl
  - drivers/md/md.c:add_new_disk
  - drivers/md/md.c:add_new_disk
  - drivers/md/md.c:add_new_disk
  - drivers/md/md.c:autorun_devices
  - drivers/md/md.c:new_dev_store
```
**Symbols:**

```
ffffffff8188a6c0-ffffffff8188a9a1: bind_rdev_to_array (STB_LOCAL)
ffffffff81895a39-ffffffff81895a93: bind_rdev_to_array.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
int bind_rdev_to_array(struct md_rdev *rdev, struct mddev *mddev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/md/md.c (0)
Location: drivers/md/md.c:2279
Inline: False
Direct callers:
  - drivers/md/md.c:md_ioctl
  - drivers/md/md.c:add_new_disk
  - drivers/md/md.c:add_new_disk
  - drivers/md/md.c:add_new_disk
  - drivers/md/md.c:autorun_devices
  - drivers/md/md.c:new_dev_store
```
**Symbols:**

```
ffffffff818a9540-ffffffff818a982b: bind_rdev_to_array (STB_LOCAL)
ffffffff818b23ab-ffffffff818b2405: bind_rdev_to_array.cold (STB_LOCAL)
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
