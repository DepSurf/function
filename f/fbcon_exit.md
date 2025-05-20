# Function: <code>fbcon_exit</code>

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
In drivers/video/console/fbcon.c (ffffffff81460ab8)
Location: drivers/video/console/fbcon.c:3548
Inline: True
Inline callers:
  - drivers/video/console/fbcon.c:fbcon_deinit
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
In drivers/video/console/fbcon.c (ffffffff814ae9b8)
Location: drivers/video/console/fbcon.c:3545
Inline: True
Inline callers:
  - drivers/video/console/fbcon.c:fbcon_deinit
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
In drivers/video/console/fbcon.c (ffffffff814d0ac1)
Location: drivers/video/console/fbcon.c:3556
Inline: True
Inline callers:
  - drivers/video/console/fbcon.c:fbcon_deinit
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
In drivers/video/console/fbcon.c (ffffffff814dc25b)
Location: drivers/video/console/fbcon.c:3554
Inline: True
Inline callers:
  - drivers/video/console/fbcon.c:fbcon_deinit
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
In drivers/video/fbdev/core/fbcon.c (ffffffff8152533b)
Location: drivers/video/fbdev/core/fbcon.c:3570
Inline: True
Inline callers:
  - drivers/video/fbdev/core/fbcon.c:fbcon_deinit
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
In drivers/video/fbdev/core/fbcon.c (ffffffff8155b0b0)
Location: drivers/video/fbdev/core/fbcon.c:3578
Inline: True
Inline callers:
  - drivers/video/fbdev/core/fbcon.c:fbcon_deinit
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
In drivers/video/fbdev/core/fbcon.c (ffffffff81572e19)
Location: drivers/video/fbdev/core/fbcon.c:3660
Inline: True
Inline callers:
  - drivers/video/fbdev/core/fbcon.c:fbcon_deinit
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
In drivers/video/fbdev/core/fbcon.c (ffffffff815a3624)
Location: drivers/video/fbdev/core/fbcon.c:3627
Inline: True
Inline callers:
  - drivers/video/fbdev/core/fbcon.c:fbcon_deinit
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
In drivers/video/fbdev/core/fbcon.c (ffffffff815c44a4)
Location: drivers/video/fbdev/core/fbcon.c:3627
Inline: True
Inline callers:
  - drivers/video/fbdev/core/fbcon.c:fbcon_deinit
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void fbcon_exit();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/video/fbdev/core/fbcon.c (ffffffff81671900)
Location: drivers/video/fbdev/core/fbcon.c:3335
Inline: False
Direct callers:
  - drivers/video/fbdev/core/fbcon.c:fbcon_deinit
```
**Symbols:**

```
ffffffff81671900-ffffffff81671a6e: fbcon_exit (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void fbcon_exit();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/video/fbdev/core/fbcon.c (ffffffff81691ce0)
Location: drivers/video/fbdev/core/fbcon.c:3285
Inline: False
Direct callers:
  - drivers/video/fbdev/core/fbcon.c:fbcon_deinit
```
**Symbols:**

```
ffffffff81691ce0-ffffffff81691e4e: fbcon_exit (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void fbcon_exit();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/video/fbdev/core/fbcon.c (ffffffff81674a60)
Location: drivers/video/fbdev/core/fbcon.c:3277
Inline: False
Direct callers:
  - drivers/video/fbdev/core/fbcon.c:fbcon_deinit
```
**Symbols:**

```
ffffffff81674a60-ffffffff81674c15: fbcon_exit (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
void fbcon_exit();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/video/fbdev/core/fbcon.c (0)
Location: drivers/video/fbdev/core/fbcon.c:3322
Inline: False
Direct callers:
  - drivers/video/fbdev/core/fbcon.c:fbcon_deinit
```
**Symbols:**

```
ffffffff816e8c60-ffffffff816e8eb4: fbcon_exit (STB_LOCAL)
ffffffff81cec776-ffffffff81cec78a: fbcon_exit.cold (STB_LOCAL)
```
</details>
</li>
<li>
In <code>5.19</code>: Absent ⚠️
</li>
<li>
In <code>6.2</code>: Absent ⚠️
</li>
<li>
In <code>6.5</code>: Absent ⚠️
</li>
<li>
In <code>6.8</code>: Absent ⚠️
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
In drivers/video/fbdev/core/fbcon.c (ffff80001074ea60)
Location: drivers/video/fbdev/core/fbcon.c:3627
Inline: True
Inline callers:
  - drivers/video/fbdev/core/fbcon.c:fbcon_deinit
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
In drivers/video/fbdev/core/fbcon.c (c08d0bd4)
Location: drivers/video/fbdev/core/fbcon.c:3627
Inline: True
Inline callers:
  - drivers/video/fbdev/core/fbcon.c:fbcon_deinit
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
In drivers/video/fbdev/core/fbcon.c (c0000000008b2b90)
Location: drivers/video/fbdev/core/fbcon.c:3627
Inline: True
Inline callers:
  - drivers/video/fbdev/core/fbcon.c:fbcon_deinit
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
In drivers/video/fbdev/core/fbcon.c (ffffffe0004fce54)
Location: drivers/video/fbdev/core/fbcon.c:3627
Inline: True
Inline callers:
  - drivers/video/fbdev/core/fbcon.c:fbcon_deinit
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
In drivers/video/fbdev/core/fbcon.c (ffffffff815b85f4)
Location: drivers/video/fbdev/core/fbcon.c:3627
Inline: True
Inline callers:
  - drivers/video/fbdev/core/fbcon.c:fbcon_deinit
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
In drivers/video/fbdev/core/fbcon.c (ffffffff815a73d4)
Location: drivers/video/fbdev/core/fbcon.c:3627
Inline: True
Inline callers:
  - drivers/video/fbdev/core/fbcon.c:fbcon_deinit
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
In drivers/video/fbdev/core/fbcon.c (ffffffff815b8b84)
Location: drivers/video/fbdev/core/fbcon.c:3627
Inline: True
Inline callers:
  - drivers/video/fbdev/core/fbcon.c:fbcon_deinit
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
In drivers/video/fbdev/core/fbcon.c (ffffffff815d25e4)
Location: drivers/video/fbdev/core/fbcon.c:3627
Inline: True
Inline callers:
  - drivers/video/fbdev/core/fbcon.c:fbcon_deinit
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
</ul>
