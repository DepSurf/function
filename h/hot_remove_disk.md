# Function: <code>hot_remove_disk</code>

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
In drivers/md/md.c (ffffffff8169a777)
Location: drivers/md/md.c:6137
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
In drivers/md/md.c (ffffffff816fb806)
Location: drivers/md/md.c:6167
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
In drivers/md/md.c (ffffffff8172d878)
Location: drivers/md/md.c:6220
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
In drivers/md/md.c (ffffffff8174651a)
Location: drivers/md/md.c:6434
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
In drivers/md/md.c (ffffffff817b84c4)
Location: drivers/md/md.c:6485
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
In drivers/md/md.c (ffffffff817ff392)
Location: drivers/md/md.c:6551
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
In drivers/md/md.c (ffffffff8182b532)
Location: drivers/md/md.c:6538
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
In drivers/md/md.c (ffffffff8186d36d)
Location: drivers/md/md.c:6600
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
In drivers/md/md.c (ffffffff8189f15d)
Location: drivers/md/md.c:6701
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
int hot_remove_disk(struct mddev *mddev, dev_t dev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/md.c (ffffffff8196e3b0)
Location: drivers/md/md.c:6899
Inline: False
Direct callers:
  - drivers/md/md.c:md_ioctl
```
**Symbols:**

```
ffffffff8196e3b0-ffffffff8196e55a: hot_remove_disk (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int hot_remove_disk(struct mddev *mddev, dev_t dev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/md.c (ffffffff81974d80)
Location: drivers/md/md.c:6931
Inline: False
Direct callers:
  - drivers/md/md.c:md_ioctl
```
**Symbols:**

```
ffffffff81974d80-ffffffff81974f2f: hot_remove_disk (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int hot_remove_disk(struct mddev *mddev, dev_t dev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/md.c (ffffffff81958db0)
Location: drivers/md/md.c:6886
Inline: False
Direct callers:
  - drivers/md/md.c:md_ioctl
```
**Symbols:**

```
ffffffff81958db0-ffffffff81958f5f: hot_remove_disk (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int hot_remove_disk(struct mddev *mddev, dev_t dev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/md.c (ffffffff819fe550)
Location: drivers/md/md.c:6899
Inline: False
Direct callers:
  - drivers/md/md.c:md_ioctl
```
**Symbols:**

```
ffffffff819fe550-ffffffff819fe6fc: hot_remove_disk (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int hot_remove_disk(struct mddev *mddev, dev_t dev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/md.c (ffffffff81b65b40)
Location: drivers/md/md.c:6889
Inline: False
Direct callers:
  - drivers/md/md.c:md_ioctl
```
**Symbols:**

```
ffffffff81b65b40-ffffffff81b65cc6: hot_remove_disk (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int hot_remove_disk(struct mddev *mddev, dev_t dev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/md.c (ffffffff81d00d30)
Location: drivers/md/md.c:6875
Inline: False
Direct callers:
  - drivers/md/md.c:md_ioctl
```
**Symbols:**

```
ffffffff81d00d30-ffffffff81d00eae: hot_remove_disk (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int hot_remove_disk(struct mddev *mddev, dev_t dev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/md.c (ffffffff81d63e00)
Location: drivers/md/md.c:6878
Inline: False
Direct callers:
  - drivers/md/md.c:md_ioctl
```
**Symbols:**

```
ffffffff81d63e00-ffffffff81d63f7e: hot_remove_disk (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int hot_remove_disk(struct mddev *mddev, dev_t dev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/md.c (ffffffff81e1adc0)
Location: drivers/md/md.c:6988
Inline: False
Direct callers:
  - drivers/md/md.c:md_ioctl
```
**Symbols:**

```
ffffffff81e1adc0-ffffffff81e1af3e: hot_remove_disk (STB_LOCAL)
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
In drivers/md/md.c (ffff800010af3d14)
Location: drivers/md/md.c:6701
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
In drivers/md/md.c (c0bd5284)
Location: drivers/md/md.c:6701
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
In drivers/md/md.c (c000000000be0e3c)
Location: drivers/md/md.c:6701
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
In drivers/md/md.c (ffffffe0006e7488)
Location: drivers/md/md.c:6701
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
In drivers/md/md.c (ffffffff81844fdd)
Location: drivers/md/md.c:6701
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
In drivers/md/md.c (ffffffff8180c63d)
Location: drivers/md/md.c:6701
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
In drivers/md/md.c (ffffffff8189460d)
Location: drivers/md/md.c:6701
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
In drivers/md/md.c (ffffffff818b02d3)
Location: drivers/md/md.c:6701
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
