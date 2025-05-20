# Function: <code>loop_change_fd</code>

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
In drivers/block/loop.c (ffffffff8156fb5e)
Location: drivers/block/loop.c:665
Inline: True
Inline callers:
  - drivers/block/loop.c:lo_ioctl
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
In drivers/block/loop.c (ffffffff815c547e)
Location: drivers/block/loop.c:660
Inline: True
Inline callers:
  - drivers/block/loop.c:lo_ioctl
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
In drivers/block/loop.c (ffffffff815f3b0e)
Location: drivers/block/loop.c:648
Inline: True
Inline callers:
  - drivers/block/loop.c:lo_ioctl
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
In drivers/block/loop.c (ffffffff81607e9e)
Location: drivers/block/loop.c:659
Inline: True
Inline callers:
  - drivers/block/loop.c:lo_ioctl
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
In drivers/block/loop.c (ffffffff816708f3)
Location: drivers/block/loop.c:642
Inline: True
Inline callers:
  - drivers/block/loop.c:lo_ioctl
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
In drivers/block/loop.c (ffffffff816ac176)
Location: drivers/block/loop.c:698
Inline: True
Inline callers:
  - drivers/block/loop.c:lo_ioctl
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
In drivers/block/loop.c (ffffffff816cdd9f)
Location: drivers/block/loop.c:686
Inline: True
Inline callers:
  - drivers/block/loop.c:lo_ioctl
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
In drivers/block/loop.c (ffffffff81708d04)
Location: drivers/block/loop.c:686
Inline: True
Inline callers:
  - drivers/block/loop.c:lo_ioctl
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
In drivers/block/loop.c (ffffffff8172cfe4)
Location: drivers/block/loop.c:696
Inline: True
Inline callers:
  - drivers/block/loop.c:lo_ioctl
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
int loop_change_fd(struct loop_device *lo, struct block_device *bdev, unsigned int arg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/block/loop.c (0)
Location: drivers/block/loop.c:711
Inline: False
Direct callers:
  - drivers/block/loop.c:lo_ioctl
```
**Symbols:**

```
ffffffff817ea540-ffffffff817ea88b: loop_change_fd (STB_LOCAL)
ffffffff817ead4e-ffffffff817ead6f: loop_change_fd.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
int loop_change_fd(struct loop_device *lo, struct block_device *bdev, unsigned int arg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/block/loop.c (0)
Location: drivers/block/loop.c:709
Inline: False
Direct callers:
  - drivers/block/loop.c:lo_ioctl
```
**Symbols:**

```
ffffffff817fef90-ffffffff817ff2f3: loop_change_fd (STB_LOCAL)
ffffffff81c0fb17-ffffffff81c0fb38: loop_change_fd.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
int loop_change_fd(struct loop_device *lo, struct block_device *bdev, unsigned int arg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/block/loop.c (0)
Location: drivers/block/loop.c:744
Inline: False
Direct callers:
  - drivers/block/loop.c:lo_ioctl
```
**Symbols:**

```
ffffffff817e3d20-ffffffff817e404a: loop_change_fd (STB_LOCAL)
ffffffff81c01cae-ffffffff81c01ccf: loop_change_fd.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int loop_change_fd(struct loop_device *lo, struct block_device *bdev, unsigned int arg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/block/loop.c (0)
Location: drivers/block/loop.c:737
Inline: False
Direct callers:
  - drivers/block/loop.c:lo_ioctl
```
**Symbols:**

```
ffffffff8186f0f0-ffffffff8186f507: loop_change_fd (STB_LOCAL)
ffffffff81d05972-ffffffff81d05995: loop_change_fd.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int loop_change_fd(struct loop_device *lo, struct block_device *bdev, unsigned int arg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/block/loop.c (0)
Location: drivers/block/loop.c:565
Inline: False
Direct callers:
  - drivers/block/loop.c:lo_ioctl
```
**Symbols:**

```
ffffffff819b80d0-ffffffff819b8430: loop_change_fd (STB_LOCAL)
ffffffff81ece346-ffffffff81ece367: loop_change_fd.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
int loop_change_fd(struct loop_device *lo, struct block_device *bdev, unsigned int arg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/block/loop.c (0)
Location: drivers/block/loop.c:565
Inline: False
Direct callers:
  - drivers/block/loop.c:lo_ioctl
```
**Symbols:**

```
ffffffff81b2d430-ffffffff81b2d790: loop_change_fd (STB_LOCAL)
ffffffff82099b83-ffffffff82099ba4: loop_change_fd.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
int loop_change_fd(struct loop_device *lo, struct block_device *bdev, unsigned int arg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/block/loop.c (0)
Location: drivers/block/loop.c:565
Inline: False
Direct callers:
  - drivers/block/loop.c:lo_ioctl
```
**Symbols:**

```
ffffffff81b7d740-ffffffff81b7daa0: loop_change_fd (STB_LOCAL)
ffffffff8211ac21-ffffffff8211ac42: loop_change_fd.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
int loop_change_fd(struct loop_device *lo, struct block_device *bdev, unsigned int arg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/block/loop.c (0)
Location: drivers/block/loop.c:561
Inline: False
Direct callers:
  - drivers/block/loop.c:lo_ioctl
```
**Symbols:**

```
ffffffff81bd16c0-ffffffff81bd1a1b: loop_change_fd (STB_LOCAL)
ffffffff821f8aa7-ffffffff821f8ac8: loop_change_fd.cold (STB_LOCAL)
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
In drivers/block/loop.c (ffff800010924944)
Location: drivers/block/loop.c:696
Inline: True
Inline callers:
  - drivers/block/loop.c:lo_ioctl
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
In drivers/block/loop.c (c0a080e4)
Location: drivers/block/loop.c:696
Inline: True
Inline callers:
  - drivers/block/loop.c:lo_ioctl
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
In drivers/block/loop.c (c0000000009c8840)
Location: drivers/block/loop.c:696
Inline: True
Inline callers:
  - drivers/block/loop.c:lo_ioctl
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
In drivers/block/loop.c (ffffffe0005a1a7c)
Location: drivers/block/loop.c:696
Inline: True
Inline callers:
  - drivers/block/loop.c:lo_ioctl
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
In drivers/block/loop.c (ffffffff816f2dc4)
Location: drivers/block/loop.c:696
Inline: True
Inline callers:
  - drivers/block/loop.c:lo_ioctl
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
In drivers/block/loop.c (ffffffff816ccec4)
Location: drivers/block/loop.c:696
Inline: True
Inline callers:
  - drivers/block/loop.c:lo_ioctl
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
In drivers/block/loop.c (ffffffff817204a4)
Location: drivers/block/loop.c:696
Inline: True
Inline callers:
  - drivers/block/loop.c:lo_ioctl
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
In drivers/block/loop.c (ffffffff8173b864)
Location: drivers/block/loop.c:696
Inline: True
Inline callers:
  - drivers/block/loop.c:lo_ioctl
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
