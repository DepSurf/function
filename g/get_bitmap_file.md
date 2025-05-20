# Function: <code>get_bitmap_file</code>

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
In drivers/md/md.c (ffffffff81699c89)
Location: drivers/md/md.c:5880
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
In drivers/md/md.c (ffffffff816fad48)
Location: drivers/md/md.c:5895
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
In drivers/md/md.c (ffffffff8172c6de)
Location: drivers/md/md.c:5941
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
In drivers/md/md.c (ffffffff81745022)
Location: drivers/md/md.c:6155
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
In drivers/md/md.c (ffffffff817b71f2)
Location: drivers/md/md.c:6206
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
In drivers/md/md.c (ffffffff817fe659)
Location: drivers/md/md.c:6272
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
In drivers/md/md.c (ffffffff8182a7f9)
Location: drivers/md/md.c:6259
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
In drivers/md/md.c (ffffffff8186ce43)
Location: drivers/md/md.c:6321
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
In drivers/md/md.c (ffffffff8189ec33)
Location: drivers/md/md.c:6422
Inline: True
Inline callers:
  - drivers/md/md.c:md_ioctl
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int get_bitmap_file(struct mddev *mddev, void *arg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/md.c (ffffffff81965390)
Location: drivers/md/md.c:6620
Inline: False
Direct callers:
  - drivers/md/md.c:md_ioctl
```
**Symbols:**

```
ffffffff81965390-ffffffff81965463: get_bitmap_file (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int get_bitmap_file(struct mddev *mddev, void *arg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/md.c (ffffffff8196bde0)
Location: drivers/md/md.c:6652
Inline: False
Direct callers:
  - drivers/md/md.c:md_ioctl
```
**Symbols:**

```
ffffffff8196bde0-ffffffff8196beb3: get_bitmap_file (STB_LOCAL)
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
In drivers/md/md.c (ffffffff81959fcf)
Location: drivers/md/md.c:6607
Inline: True
Inline callers:
  - drivers/md/md.c:md_ioctl
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
In drivers/md/md.c (ffffffff819ff79f)
Location: drivers/md/md.c:6620
Inline: True
Inline callers:
  - drivers/md/md.c:md_ioctl
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int get_bitmap_file(struct mddev *mddev, void *arg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/md.c (ffffffff81b59e10)
Location: drivers/md/md.c:6611
Inline: False
Direct callers:
  - drivers/md/md.c:md_ioctl
```
**Symbols:**

```
ffffffff81b59e10-ffffffff81b59f07: get_bitmap_file (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int get_bitmap_file(struct mddev *mddev, void *arg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/md.c (ffffffff81cf44b0)
Location: drivers/md/md.c:6597
Inline: False
Direct callers:
  - drivers/md/md.c:md_ioctl
```
**Symbols:**

```
ffffffff81cf44b0-ffffffff81cf45a7: get_bitmap_file (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int get_bitmap_file(struct mddev *mddev, void *arg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/md.c (ffffffff81d5c300)
Location: drivers/md/md.c:6601
Inline: False
Direct callers:
  - drivers/md/md.c:md_ioctl
```
**Symbols:**

```
ffffffff81d5c300-ffffffff81d5c3eb: get_bitmap_file (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int get_bitmap_file(struct mddev *mddev, void *arg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/md.c (ffffffff81e13460)
Location: drivers/md/md.c:6711
Inline: False
Direct callers:
  - drivers/md/md.c:md_ioctl
```
**Symbols:**

```
ffffffff81e13460-ffffffff81e13575: get_bitmap_file (STB_LOCAL)
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
In drivers/md/md.c (ffff800010af3728)
Location: drivers/md/md.c:6422
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
In drivers/md/md.c (c0bd4d28)
Location: drivers/md/md.c:6422
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
In drivers/md/md.c (c000000000be079c)
Location: drivers/md/md.c:6422
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
In drivers/md/md.c (ffffffe0006e6fd2)
Location: drivers/md/md.c:6422
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
In drivers/md/md.c (ffffffff81844ab3)
Location: drivers/md/md.c:6422
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
In drivers/md/md.c (ffffffff8180c113)
Location: drivers/md/md.c:6422
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
In drivers/md/md.c (ffffffff818940e3)
Location: drivers/md/md.c:6422
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
In drivers/md/md.c (ffffffff818afd0c)
Location: drivers/md/md.c:6422
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
No changes between <code>5.19</code> and <code>6.2</code> ✅
</li>
<li>
No changes between <code>6.2</code> and <code>6.5</code> ✅
</li>
<li>
No changes between <code>6.5</code> and <code>6.8</code> ✅
</li>
</ul>
