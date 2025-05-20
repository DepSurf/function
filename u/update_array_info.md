# Function: <code>update_array_info</code>

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
In drivers/md/md.c (ffffffff8169a44f)
Location: drivers/md/md.c:6512
Inline: True
Inline callers:
  - drivers/md/md.c:md_ioctl
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
In drivers/md/md.c (ffffffff816fb596)
Location: drivers/md/md.c:6539
Inline: True
Inline callers:
  - drivers/md/md.c:md_ioctl
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
In drivers/md/md.c (ffffffff8172d345)
Location: drivers/md/md.c:6595
Inline: True
Inline callers:
  - drivers/md/md.c:md_ioctl
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
In drivers/md/md.c (ffffffff81745b78)
Location: drivers/md/md.c:6811
Inline: True
Inline callers:
  - drivers/md/md.c:md_ioctl
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
In drivers/md/md.c (ffffffff817b7d6b)
Location: drivers/md/md.c:6866
Inline: True
Inline callers:
  - drivers/md/md.c:md_ioctl
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
In drivers/md/md.c (ffffffff817fee32)
Location: drivers/md/md.c:6935
Inline: True
Inline callers:
  - drivers/md/md.c:md_ioctl
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
In drivers/md/md.c (ffffffff8182afd2)
Location: drivers/md/md.c:6922
Inline: True
Inline callers:
  - drivers/md/md.c:md_ioctl
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
In drivers/md/md.c (ffffffff8186d58c)
Location: drivers/md/md.c:6984
Inline: True
Inline callers:
  - drivers/md/md.c:md_ioctl
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
In drivers/md/md.c (ffffffff8189f37c)
Location: drivers/md/md.c:7088
Inline: True
Inline callers:
  - drivers/md/md.c:md_ioctl
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
int update_array_info(struct mddev *mddev, mdu_array_info_t *info);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/md/md.c (0)
Location: drivers/md/md.c:7286
Inline: False
Direct callers:
  - drivers/md/md.c:md_ioctl
```
**Symbols:**

```
ffffffff8196b0f0-ffffffff8196b478: update_array_info (STB_LOCAL)
ffffffff81970e0c-ffffffff81970e37: update_array_info.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
int update_array_info(struct mddev *mddev, mdu_array_info_t *info);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/md/md.c (0)
Location: drivers/md/md.c:7320
Inline: False
Direct callers:
  - drivers/md/md.c:md_ioctl
```
**Symbols:**

```
ffffffff81971c70-ffffffff81972010: update_array_info (STB_LOCAL)
ffffffff81c26ef5-ffffffff81c26f20: update_array_info.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
int update_array_info(struct mddev *mddev, mdu_array_info_t *info);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/md/md.c (0)
Location: drivers/md/md.c:7275
Inline: False
Direct callers:
  - drivers/md/md.c:md_ioctl
```
**Symbols:**

```
ffffffff81955d60-ffffffff81956100: update_array_info (STB_LOCAL)
ffffffff81c190a6-ffffffff81c190d1: update_array_info.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int update_array_info(struct mddev *mddev, mdu_array_info_t *info);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/md/md.c (0)
Location: drivers/md/md.c:7288
Inline: False
Direct callers:
  - drivers/md/md.c:md_ioctl
```
**Symbols:**

```
ffffffff819fb390-ffffffff819fb730: update_array_info (STB_LOCAL)
ffffffff81d286c2-ffffffff81d286ed: update_array_info.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int update_array_info(struct mddev *mddev, mdu_array_info_t *info);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/md/md.c (0)
Location: drivers/md/md.c:7285
Inline: False
Direct callers:
  - drivers/md/md.c:md_ioctl
```
**Symbols:**

```
ffffffff81b629a0-ffffffff81b62dc0: update_array_info (STB_LOCAL)
ffffffff81ef472f-ffffffff81ef475a: update_array_info.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int update_array_info(struct mddev *mddev, mdu_array_info_t *info);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/md.c (ffffffff81cfcc80)
Location: drivers/md/md.c:7271
Inline: False
Direct callers:
  - drivers/md/md.c:__md_set_array_info
```
**Symbols:**

```
ffffffff81cfcc80-ffffffff81cfd0cb: update_array_info (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int update_array_info(struct mddev *mddev, mdu_array_info_t *info);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/md.c (ffffffff81d64120)
Location: drivers/md/md.c:7274
Inline: False
Direct callers:
  - drivers/md/md.c:__md_set_array_info
```
**Symbols:**

```
ffffffff81d64120-ffffffff81d64575: update_array_info (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int update_array_info(struct mddev *mddev, mdu_array_info_t *info);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/md.c (ffffffff81e1af50)
Location: drivers/md/md.c:7389
Inline: False
Direct callers:
  - drivers/md/md.c:__md_set_array_info
```
**Symbols:**

```
ffffffff81e1af50-ffffffff81e1b313: update_array_info (STB_LOCAL)
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
In drivers/md/md.c (ffff800010af3f1c)
Location: drivers/md/md.c:7088
Inline: True
Inline callers:
  - drivers/md/md.c:md_ioctl
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
In drivers/md/md.c (c0bd5524)
Location: drivers/md/md.c:7088
Inline: True
Inline callers:
  - drivers/md/md.c:md_ioctl
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
In drivers/md/md.c (c000000000be1020)
Location: drivers/md/md.c:7088
Inline: True
Inline callers:
  - drivers/md/md.c:md_ioctl
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
In drivers/md/md.c (ffffffe0006e75e8)
Location: drivers/md/md.c:7088
Inline: True
Inline callers:
  - drivers/md/md.c:md_ioctl
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
In drivers/md/md.c (ffffffff818451fc)
Location: drivers/md/md.c:7088
Inline: True
Inline callers:
  - drivers/md/md.c:md_ioctl
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
In drivers/md/md.c (ffffffff8180c85c)
Location: drivers/md/md.c:7088
Inline: True
Inline callers:
  - drivers/md/md.c:md_ioctl
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
In drivers/md/md.c (ffffffff8189482c)
Location: drivers/md/md.c:7088
Inline: True
Inline callers:
  - drivers/md/md.c:md_ioctl
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
In drivers/md/md.c (ffffffff818b0bf3)
Location: drivers/md/md.c:7088
Inline: True
Inline callers:
  - drivers/md/md.c:md_ioctl
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
