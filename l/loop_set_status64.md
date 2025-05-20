# Function: <code>loop_set_status64</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int loop_set_status64(struct loop_device *lo, const struct loop_info64 *arg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/block/loop.c (ffffffff8156e7e0)
Location: drivers/block/loop.c:1319
Inline: False
Direct callers:
  - drivers/block/loop.c:lo_ioctl
```
**Symbols:**

```
ffffffff8156e7e0-ffffffff8156e84e: loop_set_status64 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int loop_set_status64(struct loop_device *lo, const struct loop_info64 *arg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/block/loop.c (ffffffff815c40d0)
Location: drivers/block/loop.c:1314
Inline: False
Direct callers:
  - drivers/block/loop.c:lo_ioctl
```
**Symbols:**

```
ffffffff815c40d0-ffffffff815c413e: loop_set_status64 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int loop_set_status64(struct loop_device *lo, const struct loop_info64 *arg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/block/loop.c (ffffffff815f2820)
Location: drivers/block/loop.c:1285
Inline: False
Direct callers:
  - drivers/block/loop.c:lo_ioctl
```
**Symbols:**

```
ffffffff815f2820-ffffffff815f288e: loop_set_status64 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int loop_set_status64(struct loop_device *lo, const struct loop_info64 *arg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/block/loop.c (ffffffff81606a50)
Location: drivers/block/loop.c:1330
Inline: False
Direct callers:
  - drivers/block/loop.c:lo_ioctl
```
**Symbols:**

```
ffffffff81606a50-ffffffff81606abd: loop_set_status64 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int loop_set_status64(struct loop_device *lo, const struct loop_info64 *arg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/block/loop.c (ffffffff8166ee70)
Location: drivers/block/loop.c:1318
Inline: False
Direct callers:
  - drivers/block/loop.c:lo_ioctl
```
**Symbols:**

```
ffffffff8166ee70-ffffffff8166eedd: loop_set_status64 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int loop_set_status64(struct loop_device *lo, const struct loop_info64 *arg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/block/loop.c (ffffffff816aa960)
Location: drivers/block/loop.c:1366
Inline: False
Direct callers:
  - drivers/block/loop.c:lo_ioctl
```
**Symbols:**

```
ffffffff816aa960-ffffffff816aa9cd: loop_set_status64 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int loop_set_status64(struct loop_device *lo, const struct loop_info64 *arg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/block/loop.c (ffffffff816cb5f0)
Location: drivers/block/loop.c:1449
Inline: False
Direct callers:
  - drivers/block/loop.c:lo_ioctl
```
**Symbols:**

```
ffffffff816cb5f0-ffffffff816cb65d: loop_set_status64 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int loop_set_status64(struct loop_device *lo, const struct loop_info64 *arg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/block/loop.c (ffffffff81706bf0)
Location: drivers/block/loop.c:1500
Inline: False
Direct callers:
  - drivers/block/loop.c:lo_ioctl
```
**Symbols:**

```
ffffffff81706bf0-ffffffff81706c5f: loop_set_status64 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int loop_set_status64(struct loop_device *lo, const struct loop_info64 *arg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/block/loop.c (ffffffff8172ae40)
Location: drivers/block/loop.c:1520
Inline: False
Direct callers:
  - drivers/block/loop.c:lo_ioctl
```
**Symbols:**

```
ffffffff8172ae40-ffffffff8172aeaf: loop_set_status64 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/block/loop.c (ffffffff817eaa95)
Location: drivers/block/loop.c:1592
Inline: True
Inline callers:
  - drivers/block/loop.c:lo_ioctl
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/block/loop.c (ffffffff817ff502)
Location: drivers/block/loop.c:1583
Inline: True
Inline callers:
  - drivers/block/loop.c:lo_ioctl
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/block/loop.c (ffffffff817e4253)
Location: drivers/block/loop.c:1600
Inline: True
Inline callers:
  - drivers/block/loop.c:lo_ioctl
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/block/loop.c (ffffffff818709d3)
Location: drivers/block/loop.c:1737
Inline: True
Inline callers:
  - drivers/block/loop.c:lo_ioctl
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/block/loop.c (ffffffff819b8a24)
Location: drivers/block/loop.c:1412
Inline: True
Inline callers:
  - drivers/block/loop.c:lo_ioctl
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/block/loop.c (ffffffff81b2ddc4)
Location: drivers/block/loop.c:1412
Inline: True
Inline callers:
  - drivers/block/loop.c:lo_ioctl
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/block/loop.c (ffffffff81b7e04a)
Location: drivers/block/loop.c:1412
Inline: True
Inline callers:
  - drivers/block/loop.c:lo_ioctl
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/block/loop.c (ffffffff81bd1fba)
Location: drivers/block/loop.c:1406
Inline: True
Inline callers:
  - drivers/block/loop.c:lo_ioctl
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
int loop_set_status64(struct loop_device *lo, const struct loop_info64 *arg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/block/loop.c (ffff800010923ec0)
Location: drivers/block/loop.c:1520
Inline: False
Direct callers:
  - drivers/block/loop.c:lo_ioctl
```
**Symbols:**

```
ffff800010923ec0-ffff800010923f40: loop_set_status64 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int loop_set_status64(struct loop_device *lo, const struct loop_info64 *arg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/block/loop.c (c0a07e4c)
Location: drivers/block/loop.c:1520
Inline: False
Direct callers:
  - drivers/block/loop.c:lo_ioctl
```
**Symbols:**

```
c0a07e4c-c0a07f08: loop_set_status64 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int loop_set_status64(struct loop_device *lo, const struct loop_info64 *arg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/block/loop.c (c0000000009c5db0)
Location: drivers/block/loop.c:1520
Inline: False
Direct callers:
  - drivers/block/loop.c:lo_ioctl
```
**Symbols:**

```
c0000000009c5db0-c0000000009c5e40: loop_set_status64 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int loop_set_status64(struct loop_device *lo, const struct loop_info64 *arg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/block/loop.c (ffffffe0005a0486)
Location: drivers/block/loop.c:1520
Inline: False
Direct callers:
  - drivers/block/loop.c:lo_ioctl
```
**Symbols:**

```
ffffffe0005a0486-ffffffe0005a04d2: loop_set_status64 (STB_LOCAL)
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
int loop_set_status64(struct loop_device *lo, const struct loop_info64 *arg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/block/loop.c (ffffffff816f0c20)
Location: drivers/block/loop.c:1520
Inline: False
Direct callers:
  - drivers/block/loop.c:lo_ioctl
```
**Symbols:**

```
ffffffff816f0c20-ffffffff816f0c8f: loop_set_status64 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int loop_set_status64(struct loop_device *lo, const struct loop_info64 *arg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/block/loop.c (ffffffff816cad30)
Location: drivers/block/loop.c:1520
Inline: False
Direct callers:
  - drivers/block/loop.c:lo_ioctl
```
**Symbols:**

```
ffffffff816cad30-ffffffff816cad9f: loop_set_status64 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int loop_set_status64(struct loop_device *lo, const struct loop_info64 *arg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/block/loop.c (ffffffff8171e300)
Location: drivers/block/loop.c:1520
Inline: False
Direct callers:
  - drivers/block/loop.c:lo_ioctl
```
**Symbols:**

```
ffffffff8171e300-ffffffff8171e36f: loop_set_status64 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int loop_set_status64(struct loop_device *lo, const struct loop_info64 *arg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/block/loop.c (ffffffff81739690)
Location: drivers/block/loop.c:1520
Inline: False
Direct callers:
  - drivers/block/loop.c:lo_ioctl
```
**Symbols:**

```
ffffffff81739690-ffffffff817396ff: loop_set_status64 (STB_LOCAL)
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
