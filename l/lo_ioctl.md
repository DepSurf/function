# Function: <code>lo_ioctl</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int lo_ioctl(struct block_device *bdev, fmode_t mode, unsigned int cmd, long unsigned int arg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/block/loop.c (ffffffff8156fab0)
Location: drivers/block/loop.c:1383
Inline: False
Direct callers:
  - drivers/block/loop.c:lo_compat_ioctl
```
**Symbols:**

```
ffffffff8156fab0-ffffffff81570351: lo_ioctl (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int lo_ioctl(struct block_device *bdev, fmode_t mode, unsigned int cmd, long unsigned int arg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/block/loop.c (ffffffff815c53d0)
Location: drivers/block/loop.c:1378
Inline: False
Direct callers:
  - drivers/block/loop.c:lo_compat_ioctl
```
**Symbols:**

```
ffffffff815c53d0-ffffffff815c5c6f: lo_ioctl (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int lo_ioctl(struct block_device *bdev, fmode_t mode, unsigned int cmd, long unsigned int arg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/block/loop.c (ffffffff815f3a60)
Location: drivers/block/loop.c:1349
Inline: False
Direct callers:
  - drivers/block/loop.c:lo_compat_ioctl
```
**Symbols:**

```
ffffffff815f3a60-ffffffff815f423d: lo_ioctl (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int lo_ioctl(struct block_device *bdev, fmode_t mode, unsigned int cmd, long unsigned int arg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/block/loop.c (ffffffff81607df0)
Location: drivers/block/loop.c:1394
Inline: False
Direct callers:
  - drivers/block/loop.c:lo_compat_ioctl
```
**Symbols:**

```
ffffffff81607df0-ffffffff81608607: lo_ioctl (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int lo_ioctl(struct block_device *bdev, fmode_t mode, unsigned int cmd, long unsigned int arg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/block/loop.c (ffffffff81670880)
Location: drivers/block/loop.c:1402
Inline: False
Direct callers:
  - drivers/block/loop.c:lo_compat_ioctl
```
**Symbols:**

```
ffffffff81670880-ffffffff816711bf: lo_ioctl (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int lo_ioctl(struct block_device *bdev, fmode_t mode, unsigned int cmd, long unsigned int arg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/block/loop.c (ffffffff816abf10)
Location: drivers/block/loop.c:1452
Inline: False
Direct callers:
  - drivers/block/loop.c:lo_compat_ioctl
```
**Symbols:**

```
ffffffff816abf10-ffffffff816ac84c: lo_ioctl (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Transformation ⚠️</summary>

```c
int lo_ioctl(struct block_device *bdev, fmode_t mode, unsigned int cmd, long unsigned int arg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/block/loop.c (0)
Location: drivers/block/loop.c:1573
Inline: False
Direct callers:
  - drivers/block/loop.c:lo_compat_ioctl
```
**Symbols:**

```
ffffffff816cdad0-ffffffff816ce561: lo_ioctl (STB_LOCAL)
ffffffff816ce6aa-ffffffff816ce6ce: lo_ioctl.cold.44 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
int lo_ioctl(struct block_device *bdev, fmode_t mode, unsigned int cmd, long unsigned int arg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/block/loop.c (0)
Location: drivers/block/loop.c:1624
Inline: False
Direct callers:
  - drivers/block/loop.c:lo_compat_ioctl
  - drivers/block/loop.c:lo_compat_ioctl
```
**Symbols:**

```
ffffffff81708b10-ffffffff817091d0: lo_ioctl (STB_LOCAL)
ffffffff81709da1-ffffffff81709dc5: lo_ioctl.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
int lo_ioctl(struct block_device *bdev, fmode_t mode, unsigned int cmd, long unsigned int arg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/block/loop.c (0)
Location: drivers/block/loop.c:1644
Inline: False
Direct callers:
  - drivers/block/loop.c:lo_compat_ioctl
  - drivers/block/loop.c:lo_compat_ioctl
```
**Symbols:**

```
ffffffff8172cdf0-ffffffff8172d4ae: lo_ioctl (STB_LOCAL)
ffffffff8172e09e-ffffffff8172e0c2: lo_ioctl.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int lo_ioctl(struct block_device *bdev, fmode_t mode, unsigned int cmd, long unsigned int arg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/block/loop.c (ffffffff817ea890)
Location: drivers/block/loop.c:1722
Inline: False
Direct callers:
  - drivers/block/loop.c:lo_compat_ioctl
```
**Symbols:**

```
ffffffff817ea890-ffffffff817eaba7: lo_ioctl (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int lo_ioctl(struct block_device *bdev, fmode_t mode, unsigned int cmd, long unsigned int arg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/block/loop.c (ffffffff817ff300)
Location: drivers/block/loop.c:1713
Inline: False
Direct callers:
  - drivers/block/loop.c:lo_compat_ioctl
```
**Symbols:**

```
ffffffff817ff300-ffffffff817ff614: lo_ioctl (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int lo_ioctl(struct block_device *bdev, fmode_t mode, unsigned int cmd, long unsigned int arg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/block/loop.c (ffffffff817e4050)
Location: drivers/block/loop.c:1730
Inline: False
Direct callers:
  - drivers/block/loop.c:lo_compat_ioctl
```
**Symbols:**

```
ffffffff817e4050-ffffffff817e4337: lo_ioctl (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int lo_ioctl(struct block_device *bdev, fmode_t mode, unsigned int cmd, long unsigned int arg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/block/loop.c (ffffffff818707d0)
Location: drivers/block/loop.c:1867
Inline: False
Direct callers:
  - drivers/block/loop.c:lo_compat_ioctl
```
**Symbols:**

```
ffffffff818707d0-ffffffff81870ab7: lo_ioctl (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int lo_ioctl(struct block_device *bdev, fmode_t mode, unsigned int cmd, long unsigned int arg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/block/loop.c (ffffffff819b8810)
Location: drivers/block/loop.c:1531
Inline: False
Direct callers:
  - drivers/block/loop.c:lo_compat_ioctl
```
**Symbols:**

```
ffffffff819b8810-ffffffff819b8b65: lo_ioctl (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int lo_ioctl(struct block_device *bdev, fmode_t mode, unsigned int cmd, long unsigned int arg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/block/loop.c (ffffffff81b2dbb0)
Location: drivers/block/loop.c:1531
Inline: False
Direct callers:
  - drivers/block/loop.c:lo_compat_ioctl
```
**Symbols:**

```
ffffffff81b2dbb0-ffffffff81b2df05: lo_ioctl (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int lo_ioctl(struct block_device *bdev, blk_mode_t mode, unsigned int cmd, long unsigned int arg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/block/loop.c (ffffffff81b7ddf0)
Location: drivers/block/loop.c:1531
Inline: False
Direct callers:
  - drivers/block/loop.c:lo_compat_ioctl
```
**Symbols:**

```
ffffffff81b7ddf0-ffffffff81b7e13e: lo_ioctl (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int lo_ioctl(struct block_device *bdev, blk_mode_t mode, unsigned int cmd, long unsigned int arg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/block/loop.c (ffffffff81bd1d60)
Location: drivers/block/loop.c:1525
Inline: False
Direct callers:
  - drivers/block/loop.c:lo_compat_ioctl
```
**Symbols:**

```
ffffffff81bd1d60-ffffffff81bd20ae: lo_ioctl (STB_LOCAL)
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
int lo_ioctl(struct block_device *bdev, fmode_t mode, unsigned int cmd, long unsigned int arg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/block/loop.c (ffff8000109246e0)
Location: drivers/block/loop.c:1644
Inline: False
Direct callers:
  - drivers/block/loop.c:lo_compat_ioctl
```
**Symbols:**

```
ffff8000109246e0-ffff800010924d80: lo_ioctl (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int lo_ioctl(struct block_device *bdev, fmode_t mode, unsigned int cmd, long unsigned int arg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/block/loop.c (c0a07f08)
Location: drivers/block/loop.c:1644
Inline: False
```
**Symbols:**

```
c0a07f08-c0a084b4: lo_ioctl (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int lo_ioctl(struct block_device *bdev, fmode_t mode, unsigned int cmd, long unsigned int arg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/block/loop.c (c0000000009c8640)
Location: drivers/block/loop.c:1644
Inline: False
Direct callers:
  - drivers/block/loop.c:lo_compat_ioctl
```
**Symbols:**

```
c0000000009c8640-c0000000009c8ef0: lo_ioctl (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int lo_ioctl(struct block_device *bdev, fmode_t mode, unsigned int cmd, long unsigned int arg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/block/loop.c (ffffffe0005a18e0)
Location: drivers/block/loop.c:1644
Inline: False
```
**Symbols:**

```
ffffffe0005a18e0-ffffffe0005a1e36: lo_ioctl (STB_LOCAL)
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
int lo_ioctl(struct block_device *bdev, fmode_t mode, unsigned int cmd, long unsigned int arg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/block/loop.c (0)
Location: drivers/block/loop.c:1644
Inline: False
Direct callers:
  - drivers/block/loop.c:lo_compat_ioctl
  - drivers/block/loop.c:lo_compat_ioctl
```
**Symbols:**

```
ffffffff816f2bd0-ffffffff816f328e: lo_ioctl (STB_LOCAL)
ffffffff816f3e7e-ffffffff816f3ea2: lo_ioctl.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Transformation ⚠️</summary>

```c
int lo_ioctl(struct block_device *bdev, fmode_t mode, unsigned int cmd, long unsigned int arg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/block/loop.c (0)
Location: drivers/block/loop.c:1644
Inline: False
Direct callers:
  - drivers/block/loop.c:lo_compat_ioctl
  - drivers/block/loop.c:lo_compat_ioctl
```
**Symbols:**

```
ffffffff816cccd0-ffffffff816cd38e: lo_ioctl (STB_LOCAL)
ffffffff816cdf7e-ffffffff816cdfa2: lo_ioctl.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Transformation ⚠️</summary>

```c
int lo_ioctl(struct block_device *bdev, fmode_t mode, unsigned int cmd, long unsigned int arg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/block/loop.c (0)
Location: drivers/block/loop.c:1644
Inline: False
Direct callers:
  - drivers/block/loop.c:lo_compat_ioctl
  - drivers/block/loop.c:lo_compat_ioctl
```
**Symbols:**

```
ffffffff817202b0-ffffffff8172096e: lo_ioctl (STB_LOCAL)
ffffffff8172155e-ffffffff81721582: lo_ioctl.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
int lo_ioctl(struct block_device *bdev, fmode_t mode, unsigned int cmd, long unsigned int arg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/block/loop.c (0)
Location: drivers/block/loop.c:1644
Inline: False
Direct callers:
  - drivers/block/loop.c:lo_compat_ioctl
  - drivers/block/loop.c:lo_compat_ioctl
```
**Symbols:**

```
ffffffff8173b670-ffffffff8173bd2e: lo_ioctl (STB_LOCAL)
ffffffff8173c92b-ffffffff8173c94f: lo_ioctl.cold (STB_LOCAL)
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
<code>fmode_t mode</code> ➡️ <code>blk_mode_t mode</code>
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
