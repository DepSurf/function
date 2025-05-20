# Function: <code>loop_get_status64</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int loop_get_status64(struct loop_device *lo, struct loop_info64 *arg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/block/loop.c (ffffffff8156ef00)
Location: drivers/block/loop.c:1347
Inline: False
Direct callers:
  - drivers/block/loop.c:lo_ioctl
```
**Symbols:**

```
ffffffff8156ef00-ffffffff8156ef82: loop_get_status64 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int loop_get_status64(struct loop_device *lo, struct loop_info64 *arg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/block/loop.c (ffffffff815c4800)
Location: drivers/block/loop.c:1342
Inline: False
Direct callers:
  - drivers/block/loop.c:lo_ioctl
```
**Symbols:**

```
ffffffff815c4800-ffffffff815c4882: loop_get_status64 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int loop_get_status64(struct loop_device *lo, struct loop_info64 *arg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/block/loop.c (ffffffff815f2f50)
Location: drivers/block/loop.c:1313
Inline: False
Direct callers:
  - drivers/block/loop.c:lo_ioctl
```
**Symbols:**

```
ffffffff815f2f50-ffffffff815f2fd2: loop_get_status64 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int loop_get_status64(struct loop_device *lo, struct loop_info64 *arg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/block/loop.c (ffffffff816071c0)
Location: drivers/block/loop.c:1358
Inline: False
Direct callers:
  - drivers/block/loop.c:lo_ioctl
```
**Symbols:**

```
ffffffff816071c0-ffffffff81607242: loop_get_status64 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int loop_get_status64(struct loop_device *lo, struct loop_info64 *arg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/block/loop.c (ffffffff8166f5e0)
Location: drivers/block/loop.c:1346
Inline: False
Direct callers:
  - drivers/block/loop.c:lo_ioctl
```
**Symbols:**

```
ffffffff8166f5e0-ffffffff8166f662: loop_get_status64 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int loop_get_status64(struct loop_device *lo, struct loop_info64 *arg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/block/loop.c (ffffffff816ab0f0)
Location: drivers/block/loop.c:1395
Inline: False
Direct callers:
  - drivers/block/loop.c:lo_ioctl
```
**Symbols:**

```
ffffffff816ab0f0-ffffffff816ab182: loop_get_status64 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int loop_get_status64(struct loop_device *lo, struct loop_info64 *arg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/block/loop.c (ffffffff816cc5b0)
Location: drivers/block/loop.c:1476
Inline: False
Direct callers:
  - drivers/block/loop.c:lo_ioctl
```
**Symbols:**

```
ffffffff816cc5b0-ffffffff816cc636: loop_get_status64 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int loop_get_status64(struct loop_device *lo, struct loop_info64 *arg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/block/loop.c (ffffffff81707bd0)
Location: drivers/block/loop.c:1527
Inline: False
Direct callers:
  - drivers/block/loop.c:lo_ioctl
```
**Symbols:**

```
ffffffff81707bd0-ffffffff81707c5c: loop_get_status64 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int loop_get_status64(struct loop_device *lo, struct loop_info64 *arg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/block/loop.c (ffffffff8172be20)
Location: drivers/block/loop.c:1547
Inline: False
Direct callers:
  - drivers/block/loop.c:lo_ioctl
```
**Symbols:**

```
ffffffff8172be20-ffffffff8172beac: loop_get_status64 (STB_LOCAL)
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
In drivers/block/loop.c (ffffffff817eaac9)
Location: drivers/block/loop.c:1619
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
In drivers/block/loop.c (ffffffff817ff536)
Location: drivers/block/loop.c:1610
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
In drivers/block/loop.c (ffffffff817e4287)
Location: drivers/block/loop.c:1627
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
In drivers/block/loop.c (ffffffff81870a07)
Location: drivers/block/loop.c:1764
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
In drivers/block/loop.c (ffffffff819b8a63)
Location: drivers/block/loop.c:1439
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
In drivers/block/loop.c (ffffffff81b2de03)
Location: drivers/block/loop.c:1439
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
In drivers/block/loop.c (ffffffff81b7df7b)
Location: drivers/block/loop.c:1439
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
In drivers/block/loop.c (ffffffff81bd1eeb)
Location: drivers/block/loop.c:1433
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
int loop_get_status64(struct loop_device *lo, struct loop_info64 *arg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/block/loop.c (ffff800010923f40)
Location: drivers/block/loop.c:1547
Inline: False
Direct callers:
  - drivers/block/loop.c:lo_ioctl
```
**Symbols:**

```
ffff800010923f40-ffff800010924100: loop_get_status64 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int loop_get_status64(struct loop_device *lo, struct loop_info64 *arg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/block/loop.c (c0a07d74)
Location: drivers/block/loop.c:1547
Inline: False
Direct callers:
  - drivers/block/loop.c:lo_ioctl
```
**Symbols:**

```
c0a07d74-c0a07e4c: loop_get_status64 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int loop_get_status64(struct loop_device *lo, struct loop_info64 *arg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/block/loop.c (c0000000009c70d0)
Location: drivers/block/loop.c:1547
Inline: False
Direct callers:
  - drivers/block/loop.c:lo_ioctl
```
**Symbols:**

```
c0000000009c70d0-c0000000009c7194: loop_get_status64 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int loop_get_status64(struct loop_device *lo, struct loop_info64 *arg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/block/loop.c (ffffffe0005a0b7c)
Location: drivers/block/loop.c:1547
Inline: False
Direct callers:
  - drivers/block/loop.c:lo_ioctl
```
**Symbols:**

```
ffffffe0005a0b7c-ffffffe0005a0bd6: loop_get_status64 (STB_LOCAL)
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
int loop_get_status64(struct loop_device *lo, struct loop_info64 *arg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/block/loop.c (ffffffff816f1c00)
Location: drivers/block/loop.c:1547
Inline: False
Direct callers:
  - drivers/block/loop.c:lo_ioctl
```
**Symbols:**

```
ffffffff816f1c00-ffffffff816f1c8c: loop_get_status64 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int loop_get_status64(struct loop_device *lo, struct loop_info64 *arg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/block/loop.c (ffffffff816cbd00)
Location: drivers/block/loop.c:1547
Inline: False
Direct callers:
  - drivers/block/loop.c:lo_ioctl
```
**Symbols:**

```
ffffffff816cbd00-ffffffff816cbd8c: loop_get_status64 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int loop_get_status64(struct loop_device *lo, struct loop_info64 *arg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/block/loop.c (ffffffff8171f2e0)
Location: drivers/block/loop.c:1547
Inline: False
Direct callers:
  - drivers/block/loop.c:lo_ioctl
```
**Symbols:**

```
ffffffff8171f2e0-ffffffff8171f36c: loop_get_status64 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int loop_get_status64(struct loop_device *lo, struct loop_info64 *arg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/block/loop.c (ffffffff8173a710)
Location: drivers/block/loop.c:1547
Inline: False
Direct callers:
  - drivers/block/loop.c:lo_ioctl
```
**Symbols:**

```
ffffffff8173a710-ffffffff8173a79c: loop_get_status64 (STB_LOCAL)
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
