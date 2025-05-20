# Function: <code>loop_set_status</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int loop_set_status(struct loop_device *lo, const struct loop_info64 *info);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/block/loop.c (ffffffff8156e1d0)
Location: drivers/block/loop.c:1145
Inline: False
Direct callers:
  - drivers/block/loop.c:loop_set_status_compat
  - drivers/block/loop.c:loop_set_status_old
  - drivers/block/loop.c:loop_set_status64
```
**Symbols:**

```
ffffffff8156e1d0-ffffffff8156e56d: loop_set_status (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int loop_set_status(struct loop_device *lo, const struct loop_info64 *info);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/block/loop.c (ffffffff815c3ac0)
Location: drivers/block/loop.c:1140
Inline: False
Direct callers:
  - drivers/block/loop.c:loop_set_status_compat
  - drivers/block/loop.c:loop_set_status64
  - drivers/block/loop.c:loop_set_status_old
```
**Symbols:**

```
ffffffff815c3ac0-ffffffff815c3e5f: loop_set_status (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int loop_set_status(struct loop_device *lo, const struct loop_info64 *info);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/block/loop.c (ffffffff815f21f0)
Location: drivers/block/loop.c:1103
Inline: False
Direct callers:
  - drivers/block/loop.c:loop_set_status_compat
  - drivers/block/loop.c:loop_set_status64
  - drivers/block/loop.c:loop_set_status_old
```
**Symbols:**

```
ffffffff815f21f0-ffffffff815f25a2: loop_set_status (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int loop_set_status(struct loop_device *lo, const struct loop_info64 *info);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/block/loop.c (ffffffff81606400)
Location: drivers/block/loop.c:1146
Inline: False
Direct callers:
  - drivers/block/loop.c:loop_set_status_compat
  - drivers/block/loop.c:loop_set_status64
  - drivers/block/loop.c:loop_set_status_old
```
**Symbols:**

```
ffffffff81606400-ffffffff816067d4: loop_set_status (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int loop_set_status(struct loop_device *lo, const struct loop_info64 *info);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/block/loop.c (ffffffff8166e820)
Location: drivers/block/loop.c:1134
Inline: False
Direct callers:
  - drivers/block/loop.c:loop_set_status_compat
  - drivers/block/loop.c:loop_set_status64
  - drivers/block/loop.c:loop_set_status_old
```
**Symbols:**

```
ffffffff8166e820-ffffffff8166ebf7: loop_set_status (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int loop_set_status(struct loop_device *lo, const struct loop_info64 *info);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/block/loop.c (ffffffff816aa2e0)
Location: drivers/block/loop.c:1170
Inline: False
Direct callers:
  - drivers/block/loop.c:loop_set_status_compat
  - drivers/block/loop.c:loop_set_status64
  - drivers/block/loop.c:loop_set_status_old
```
**Symbols:**

```
ffffffff816aa2e0-ffffffff816aa6e1: loop_set_status (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Transformation ⚠️</summary>

```c
int loop_set_status(struct loop_device *lo, const struct loop_info64 *info);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/block/loop.c (0)
Location: drivers/block/loop.c:1220
Inline: False
Direct callers:
  - drivers/block/loop.c:loop_set_status_compat
  - drivers/block/loop.c:loop_set_status64
  - drivers/block/loop.c:loop_set_status_old
```
**Symbols:**

```
ffffffff816caec0-ffffffff816cb373: loop_set_status (STB_LOCAL)
ffffffff816ce618-ffffffff816ce647: loop_set_status.cold.41 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
int loop_set_status(struct loop_device *lo, const struct loop_info64 *info);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/block/loop.c (0)
Location: drivers/block/loop.c:1271
Inline: False
Direct callers:
  - drivers/block/loop.c:loop_set_status_compat
  - drivers/block/loop.c:loop_set_status64
  - drivers/block/loop.c:loop_set_status_old
```
**Symbols:**

```
ffffffff81706490-ffffffff81706963: loop_set_status (STB_LOCAL)
ffffffff81709d39-ffffffff81709d6d: loop_set_status.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
int loop_set_status(struct loop_device *lo, const struct loop_info64 *info);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/block/loop.c (0)
Location: drivers/block/loop.c:1291
Inline: False
Direct callers:
  - drivers/block/loop.c:loop_set_status_compat
  - drivers/block/loop.c:loop_set_status64
  - drivers/block/loop.c:loop_set_status_old
```
**Symbols:**

```
ffffffff8172a6e0-ffffffff8172abb3: loop_set_status (STB_LOCAL)
ffffffff8172e036-ffffffff8172e06a: loop_set_status.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
int loop_set_status(struct loop_device *lo, const struct loop_info64 *info);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/block/loop.c (0)
Location: drivers/block/loop.c:1400
Inline: False
Direct callers:
  - drivers/block/loop.c:loop_set_status_compat
  - drivers/block/loop.c:lo_ioctl
  - drivers/block/loop.c:loop_set_status_old
```
**Symbols:**

```
ffffffff817ea0a0-ffffffff817ea453: loop_set_status (STB_LOCAL)
ffffffff817eacf7-ffffffff817ead4e: loop_set_status.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
int loop_set_status(struct loop_device *lo, const struct loop_info64 *info);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/block/loop.c (0)
Location: drivers/block/loop.c:1391
Inline: False
Direct callers:
  - drivers/block/loop.c:loop_set_status_compat
  - drivers/block/loop.c:lo_ioctl
  - drivers/block/loop.c:loop_set_status_old
```
**Symbols:**

```
ffffffff817feb00-ffffffff817feeae: loop_set_status (STB_LOCAL)
ffffffff81c0fac0-ffffffff81c0fb17: loop_set_status.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
int loop_set_status(struct loop_device *lo, const struct loop_info64 *info);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/block/loop.c (0)
Location: drivers/block/loop.c:1408
Inline: False
Direct callers:
  - drivers/block/loop.c:loop_set_status_compat
  - drivers/block/loop.c:lo_ioctl
  - drivers/block/loop.c:loop_set_status_old
```
**Symbols:**

```
ffffffff817e3820-ffffffff817e3ac0: loop_set_status (STB_LOCAL)
ffffffff81c01c57-ffffffff81c01cae: loop_set_status.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int loop_set_status(struct loop_device *lo, const struct loop_info64 *info);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/block/loop.c (0)
Location: drivers/block/loop.c:1547
Inline: False
Direct callers:
  - drivers/block/loop.c:loop_set_status_compat
  - drivers/block/loop.c:lo_ioctl
  - drivers/block/loop.c:loop_set_status_old
```
**Symbols:**

```
ffffffff8186f510-ffffffff8186f7b2: loop_set_status (STB_LOCAL)
ffffffff81d05995-ffffffff81d059e1: loop_set_status.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int loop_set_status(struct loop_device *lo, const struct loop_info64 *info);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/block/loop.c (0)
Location: drivers/block/loop.c:1262
Inline: False
Direct callers:
  - drivers/block/loop.c:loop_set_status_compat
  - drivers/block/loop.c:lo_ioctl
  - drivers/block/loop.c:loop_set_status_old
```
**Symbols:**

```
ffffffff819b8430-ffffffff819b8609: loop_set_status (STB_LOCAL)
ffffffff81ece367-ffffffff81ece37c: loop_set_status.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
int loop_set_status(struct loop_device *lo, const struct loop_info64 *info);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/block/loop.c (0)
Location: drivers/block/loop.c:1262
Inline: False
Direct callers:
  - drivers/block/loop.c:loop_set_status_compat
  - drivers/block/loop.c:lo_ioctl
  - drivers/block/loop.c:loop_set_status_old
```
**Symbols:**

```
ffffffff81b2d7a0-ffffffff81b2d97b: loop_set_status (STB_LOCAL)
ffffffff82099ba4-ffffffff82099bb9: loop_set_status.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
int loop_set_status(struct loop_device *lo, const struct loop_info64 *info);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/block/loop.c (0)
Location: drivers/block/loop.c:1262
Inline: False
Direct callers:
  - drivers/block/loop.c:loop_set_status_compat
  - drivers/block/loop.c:lo_ioctl
  - drivers/block/loop.c:loop_set_status_old
```
**Symbols:**

```
ffffffff81b7dab0-ffffffff81b7dc8e: loop_set_status (STB_LOCAL)
ffffffff8211ac42-ffffffff8211ac57: loop_set_status.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
int loop_set_status(struct loop_device *lo, const struct loop_info64 *info);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/block/loop.c (0)
Location: drivers/block/loop.c:1258
Inline: False
Direct callers:
  - drivers/block/loop.c:loop_set_status_compat
  - drivers/block/loop.c:lo_ioctl
  - drivers/block/loop.c:loop_set_status_old
```
**Symbols:**

```
ffffffff81bd1a30-ffffffff81bd1bfe: loop_set_status (STB_LOCAL)
ffffffff821f8ac8-ffffffff821f8add: loop_set_status.cold (STB_LOCAL)
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
int loop_set_status(struct loop_device *lo, const struct loop_info64 *info);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/block/loop.c (ffff800010921300)
Location: drivers/block/loop.c:1291
Inline: False
Direct callers:
  - drivers/block/loop.c:loop_set_status_compat
  - drivers/block/loop.c:loop_set_status64
  - drivers/block/loop.c:loop_set_status_old
```
**Symbols:**

```
ffff800010921300-ffff800010921718: loop_set_status (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int loop_set_status(struct loop_device *lo, const struct loop_info64 *info);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/block/loop.c (c0a06950)
Location: drivers/block/loop.c:1291
Inline: False
Direct callers:
  - drivers/block/loop.c:loop_set_status64
  - drivers/block/loop.c:loop_set_status_old
```
**Symbols:**

```
c0a06950-c0a06db0: loop_set_status (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int loop_set_status(struct loop_device *lo, const struct loop_info64 *info);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/block/loop.c (c0000000009c55e0)
Location: drivers/block/loop.c:1291
Inline: False
Direct callers:
  - drivers/block/loop.c:loop_set_status_compat
  - drivers/block/loop.c:loop_set_status64
  - drivers/block/loop.c:loop_set_status_old
```
**Symbols:**

```
c0000000009c55e0-c0000000009c5b98: loop_set_status (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int loop_set_status(struct loop_device *lo, const struct loop_info64 *info);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/block/loop.c (ffffffe00059ffdc)
Location: drivers/block/loop.c:1291
Inline: False
Direct callers:
  - drivers/block/loop.c:loop_set_status64
  - drivers/block/loop.c:loop_set_status_old
```
**Symbols:**

```
ffffffe00059ffdc-ffffffe0005a036c: loop_set_status (STB_LOCAL)
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
int loop_set_status(struct loop_device *lo, const struct loop_info64 *info);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/block/loop.c (0)
Location: drivers/block/loop.c:1291
Inline: False
Direct callers:
  - drivers/block/loop.c:loop_set_status_compat
  - drivers/block/loop.c:loop_set_status64
  - drivers/block/loop.c:loop_set_status_old
```
**Symbols:**

```
ffffffff816f04c0-ffffffff816f0993: loop_set_status (STB_LOCAL)
ffffffff816f3e16-ffffffff816f3e4a: loop_set_status.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Transformation ⚠️</summary>

```c
int loop_set_status(struct loop_device *lo, const struct loop_info64 *info);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/block/loop.c (0)
Location: drivers/block/loop.c:1291
Inline: False
Direct callers:
  - drivers/block/loop.c:loop_set_status_compat
  - drivers/block/loop.c:loop_set_status64
  - drivers/block/loop.c:loop_set_status_old
```
**Symbols:**

```
ffffffff816ca5d0-ffffffff816caaa3: loop_set_status (STB_LOCAL)
ffffffff816cdf16-ffffffff816cdf4a: loop_set_status.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Transformation ⚠️</summary>

```c
int loop_set_status(struct loop_device *lo, const struct loop_info64 *info);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/block/loop.c (0)
Location: drivers/block/loop.c:1291
Inline: False
Direct callers:
  - drivers/block/loop.c:loop_set_status_compat
  - drivers/block/loop.c:loop_set_status64
  - drivers/block/loop.c:loop_set_status_old
```
**Symbols:**

```
ffffffff8171dba0-ffffffff8171e073: loop_set_status (STB_LOCAL)
ffffffff817214f6-ffffffff8172152a: loop_set_status.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
int loop_set_status(struct loop_device *lo, const struct loop_info64 *info);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/block/loop.c (0)
Location: drivers/block/loop.c:1291
Inline: False
Direct callers:
  - drivers/block/loop.c:loop_set_status_compat
  - drivers/block/loop.c:loop_set_status64
  - drivers/block/loop.c:loop_set_status_old
```
**Symbols:**

```
ffffffff81738f30-ffffffff81739403: loop_set_status (STB_LOCAL)
ffffffff8173c8c3-ffffffff8173c8f7: loop_set_status.cold (STB_LOCAL)
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
