# Function: <code>hot_add_disk</code>

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
In drivers/md/md.c (ffffffff8169ac72)
Location: drivers/md/md.c:6177
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
In drivers/md/md.c (ffffffff816fbebc)
Location: drivers/md/md.c:6200
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
In drivers/md/md.c (ffffffff8172ddc8)
Location: drivers/md/md.c:6257
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
In drivers/md/md.c (ffffffff81745a5f)
Location: drivers/md/md.c:6471
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
In drivers/md/md.c (ffffffff817b7bc8)
Location: drivers/md/md.c:6522
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
In drivers/md/md.c (ffffffff817ff83e)
Location: drivers/md/md.c:6591
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
In drivers/md/md.c (ffffffff8182b9de)
Location: drivers/md/md.c:6578
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
In drivers/md/md.c (ffffffff8186db7a)
Location: drivers/md/md.c:6640
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
In drivers/md/md.c (ffffffff8189f96a)
Location: drivers/md/md.c:6741
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
int hot_add_disk(struct mddev *mddev, dev_t dev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/md/md.c (0)
Location: drivers/md/md.c:6939
Inline: False
Direct callers:
  - drivers/md/md.c:md_ioctl
```
**Symbols:**

```
ffffffff8196eb50-ffffffff8196ed1a: hot_add_disk (STB_LOCAL)
ffffffff819719ab-ffffffff81971a1f: hot_add_disk.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
int hot_add_disk(struct mddev *mddev, dev_t dev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/md/md.c (0)
Location: drivers/md/md.c:6973
Inline: False
Direct callers:
  - drivers/md/md.c:md_ioctl
```
**Symbols:**

```
ffffffff81975b00-ffffffff81975cca: hot_add_disk (STB_LOCAL)
ffffffff81c2759e-ffffffff81c27612: hot_add_disk.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
int hot_add_disk(struct mddev *mddev, dev_t dev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/md/md.c (0)
Location: drivers/md/md.c:6928
Inline: False
Direct callers:
  - drivers/md/md.c:md_ioctl
```
**Symbols:**

```
ffffffff81959b40-ffffffff81959d0a: hot_add_disk (STB_LOCAL)
ffffffff81c19751-ffffffff81c197c5: hot_add_disk.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int hot_add_disk(struct mddev *mddev, dev_t dev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/md/md.c (0)
Location: drivers/md/md.c:6941
Inline: False
Direct callers:
  - drivers/md/md.c:md_ioctl
```
**Symbols:**

```
ffffffff819ff310-ffffffff819ff4da: hot_add_disk (STB_LOCAL)
ffffffff81d28d91-ffffffff81d28e05: hot_add_disk.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int hot_add_disk(struct mddev *mddev, dev_t dev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/md/md.c (0)
Location: drivers/md/md.c:6930
Inline: False
Direct callers:
  - drivers/md/md.c:md_ioctl
```
**Symbols:**

```
ffffffff81b66820-ffffffff81b669b5: hot_add_disk (STB_LOCAL)
ffffffff81ef4df5-ffffffff81ef4ec6: hot_add_disk.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int hot_add_disk(struct mddev *mddev, dev_t dev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/md.c (ffffffff81d020f0)
Location: drivers/md/md.c:6916
Inline: False
Direct callers:
  - drivers/md/md.c:md_ioctl
```
**Symbols:**

```
ffffffff81d020f0-ffffffff81d02329: hot_add_disk (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int hot_add_disk(struct mddev *mddev, dev_t dev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/md.c (ffffffff81d6b220)
Location: drivers/md/md.c:6919
Inline: False
Direct callers:
  - drivers/md/md.c:md_ioctl
```
**Symbols:**

```
ffffffff81d6b220-ffffffff81d6b45c: hot_add_disk (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int hot_add_disk(struct mddev *mddev, dev_t dev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/md.c (ffffffff81e1cc10)
Location: drivers/md/md.c:7029
Inline: False
Direct callers:
  - drivers/md/md.c:md_ioctl
```
**Symbols:**

```
ffffffff81e1cc10-ffffffff81e1ce46: hot_add_disk (STB_LOCAL)
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
In drivers/md/md.c (ffff800010af4484)
Location: drivers/md/md.c:6741
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
In drivers/md/md.c (c0bd5a24)
Location: drivers/md/md.c:6741
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
In drivers/md/md.c (c000000000be142c)
Location: drivers/md/md.c:6741
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
In drivers/md/md.c (ffffffe0006e71c0)
Location: drivers/md/md.c:6741
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
In drivers/md/md.c (ffffffff818457ea)
Location: drivers/md/md.c:6741
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
In drivers/md/md.c (ffffffff8180ce4a)
Location: drivers/md/md.c:6741
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
In drivers/md/md.c (ffffffff81894e1a)
Location: drivers/md/md.c:6741
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
In drivers/md/md.c (ffffffff818b098e)
Location: drivers/md/md.c:6741
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
