# Function: <code>drop_links</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/namei.c (ffffffff81216b90)
Location: fs/namei.c:590
Inline: True
Direct callers:
  - fs/namei.c:terminate_walk
  - fs/namei.c:unlazy_walk
  - fs/namei.c:pick_link
```
**Symbols:**

```
ffffffff81216b90-ffffffff81216beb: drop_links.isra.10 (STB_LOCAL)
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
In fs/namei.c (ffffffff8123f7df)
Location: fs/namei.c:598
Inline: True
Inline callers:
  - fs/namei.c:pick_link
  - fs/namei.c:unlazy_walk
  - fs/namei.c:terminate_walk
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
In fs/namei.c (ffffffff812525af)
Location: fs/namei.c:598
Inline: True
Inline callers:
  - fs/namei.c:pick_link
  - fs/namei.c:unlazy_walk
  - fs/namei.c:terminate_walk
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
In fs/namei.c (ffffffff8125e8f0)
Location: fs/namei.c:598
Inline: True
Inline callers:
  - fs/namei.c:pick_link
  - fs/namei.c:legitimize_links
  - fs/namei.c:terminate_walk
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
In fs/namei.c (ffffffff81280b14)
Location: fs/namei.c:599
Inline: True
Inline callers:
  - fs/namei.c:pick_link
  - fs/namei.c:legitimize_links
  - fs/namei.c:terminate_walk
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
In fs/namei.c (ffffffff812a6a7a)
Location: fs/namei.c:583
Inline: True
Inline callers:
  - fs/namei.c:pick_link
  - fs/namei.c:legitimize_links
  - fs/namei.c:terminate_walk
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
In fs/namei.c (ffffffff812bbcaa)
Location: fs/namei.c:583
Inline: True
Inline callers:
  - fs/namei.c:pick_link
  - fs/namei.c:legitimize_links
  - fs/namei.c:terminate_walk
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
In fs/namei.c (ffffffff812d885e)
Location: fs/namei.c:581
Inline: True
Inline callers:
  - fs/namei.c:pick_link
  - fs/namei.c:legitimize_links
  - fs/namei.c:terminate_walk
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
In fs/namei.c (ffffffff812ea36a)
Location: fs/namei.c:581
Inline: True
Inline callers:
  - fs/namei.c:pick_link
  - fs/namei.c:legitimize_links
  - fs/namei.c:terminate_walk
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
In fs/namei.c (ffffffff81320f50)
Location: fs/namei.c:578
Inline: True
Inline callers:
  - fs/namei.c:legitimize_links
  - fs/namei.c:terminate_walk
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
In fs/namei.c (ffffffff8132c4e0)
Location: fs/namei.c:578
Inline: True
Inline callers:
  - fs/namei.c:legitimize_links
  - fs/namei.c:terminate_walk
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
In fs/namei.c (ffffffff81333435)
Location: fs/namei.c:630
Inline: True
Inline callers:
  - fs/namei.c:terminate_walk
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
In fs/namei.c (ffffffff81380d65)
Location: fs/namei.c:657
Inline: True
Inline callers:
  - fs/namei.c:terminate_walk
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
In fs/namei.c (ffffffff81400cd3)
Location: fs/namei.c:658
Inline: True
Inline callers:
  - fs/namei.c:legitimize_links
  - fs/namei.c:legitimize_links
  - fs/namei.c:terminate_walk
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
In fs/namei.c (ffffffff8148ac13)
Location: fs/namei.c:658
Inline: True
Inline callers:
  - fs/namei.c:legitimize_links
  - fs/namei.c:legitimize_links
  - fs/namei.c:terminate_walk
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
In fs/namei.c (ffffffff814c1323)
Location: fs/namei.c:661
Inline: True
Inline callers:
  - fs/namei.c:legitimize_links
  - fs/namei.c:legitimize_links
  - fs/namei.c:terminate_walk
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
In fs/namei.c (ffffffff814f37e3)
Location: fs/namei.c:664
Inline: True
Inline callers:
  - fs/namei.c:legitimize_links
  - fs/namei.c:legitimize_links
  - fs/namei.c:terminate_walk
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
In fs/namei.c (ffff800010393824)
Location: fs/namei.c:581
Inline: True
Inline callers:
  - fs/namei.c:pick_link
  - fs/namei.c:legitimize_links
  - fs/namei.c:terminate_walk
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
In fs/namei.c (c057b224)
Location: fs/namei.c:581
Inline: True
Inline callers:
  - fs/namei.c:pick_link
  - fs/namei.c:legitimize_links
  - fs/namei.c:terminate_walk
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
In fs/namei.c (c00000000048dd00)
Location: fs/namei.c:581
Inline: True
Inline callers:
  - fs/namei.c:pick_link
  - fs/namei.c:legitimize_links
  - fs/namei.c:terminate_walk
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
In fs/namei.c (ffffffe0002626bc)
Location: fs/namei.c:581
Inline: True
Inline callers:
  - fs/namei.c:pick_link
  - fs/namei.c:legitimize_links
  - fs/namei.c:terminate_walk
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
In fs/namei.c (ffffffff812e294a)
Location: fs/namei.c:581
Inline: True
Inline callers:
  - fs/namei.c:pick_link
  - fs/namei.c:legitimize_links
  - fs/namei.c:terminate_walk
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
In fs/namei.c (ffffffff812d358a)
Location: fs/namei.c:581
Inline: True
Inline callers:
  - fs/namei.c:pick_link
  - fs/namei.c:legitimize_links
  - fs/namei.c:terminate_walk
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
In fs/namei.c (ffffffff812e075a)
Location: fs/namei.c:581
Inline: True
Inline callers:
  - fs/namei.c:pick_link
  - fs/namei.c:legitimize_links
  - fs/namei.c:terminate_walk
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
In fs/namei.c (ffffffff812f284e)
Location: fs/namei.c:581
Inline: True
Inline callers:
  - fs/namei.c:pick_link
  - fs/namei.c:legitimize_links
  - fs/namei.c:terminate_walk
```
</details>
</li>
</ul>

## Differences
