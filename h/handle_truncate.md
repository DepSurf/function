# Function: <code>handle_truncate</code>

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
In fs/namei.c (ffffffff8121ab68)
Location: fs/namei.c:2723
Inline: True
Inline callers:
  - fs/namei.c:path_openat
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
In fs/namei.c (ffffffff812423aa)
Location: fs/namei.c:2946
Inline: True
Inline callers:
  - fs/namei.c:path_openat
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
In fs/namei.c (ffffffff8125527f)
Location: fs/namei.c:2910
Inline: True
Inline callers:
  - fs/namei.c:path_openat
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
In fs/namei.c (ffffffff812612c3)
Location: fs/namei.c:2955
Inline: True
Inline callers:
  - fs/namei.c:path_openat
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
In fs/namei.c (ffffffff812839f6)
Location: fs/namei.c:2953
Inline: True
Inline callers:
  - fs/namei.c:path_openat
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
In fs/namei.c (ffffffff812aab87)
Location: fs/namei.c:2975
Inline: True
Inline callers:
  - fs/namei.c:path_openat
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
In fs/namei.c (ffffffff812bf94f)
Location: fs/namei.c:2994
Inline: True
Inline callers:
  - fs/namei.c:path_openat
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
In fs/namei.c (ffffffff812dcadd)
Location: fs/namei.c:2992
Inline: True
Inline callers:
  - fs/namei.c:do_last
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
In fs/namei.c (ffffffff812ee62c)
Location: fs/namei.c:2985
Inline: True
Inline callers:
  - fs/namei.c:do_last
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int handle_truncate(struct file *filp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namei.c (ffffffff813213d0)
Location: fs/namei.c:2887
Inline: False
Direct callers:
  - fs/namei.c:do_open
```
**Symbols:**

```
ffffffff813213d0-ffffffff81321465: handle_truncate (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int handle_truncate(struct file *filp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namei.c (ffffffff8132c970)
Location: fs/namei.c:2893
Inline: False
Direct callers:
  - fs/namei.c:do_open
```
**Symbols:**

```
ffffffff8132c970-ffffffff8132ca05: handle_truncate (STB_LOCAL)
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
In fs/namei.c (ffffffff8133679a)
Location: fs/namei.c:3003
Inline: True
Inline callers:
  - fs/namei.c:do_open
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
In fs/namei.c (ffffffff8138417a)
Location: fs/namei.c:3072
Inline: True
Inline callers:
  - fs/namei.c:do_open
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
In fs/namei.c (ffffffff814052c9)
Location: fs/namei.c:3168
Inline: True
Inline callers:
  - fs/namei.c:do_open
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
In fs/namei.c (ffffffff8148f71a)
Location: fs/namei.c:3206
Inline: True
Inline callers:
  - fs/namei.c:do_open
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
In fs/namei.c (ffffffff814c1f03)
Location: fs/namei.c:3285
Inline: True
Inline callers:
  - fs/namei.c:do_open
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
In fs/namei.c (ffffffff814f43c3)
Location: fs/namei.c:3293
Inline: True
Inline callers:
  - fs/namei.c:do_open
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
In fs/namei.c (ffff8000103982a4)
Location: fs/namei.c:2985
Inline: True
Inline callers:
  - fs/namei.c:do_last
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
In fs/namei.c (c057e898)
Location: fs/namei.c:2985
Inline: True
Inline callers:
  - fs/namei.c:do_last
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
In fs/namei.c (c0000000004921b0)
Location: fs/namei.c:2985
Inline: True
Inline callers:
  - fs/namei.c:do_last
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
In fs/namei.c (ffffffe000265ed4)
Location: fs/namei.c:2985
Inline: True
Inline callers:
  - fs/namei.c:do_last
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
In fs/namei.c (ffffffff812e6c0c)
Location: fs/namei.c:2985
Inline: True
Inline callers:
  - fs/namei.c:do_last
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
In fs/namei.c (ffffffff812d784c)
Location: fs/namei.c:2985
Inline: True
Inline callers:
  - fs/namei.c:do_last
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
In fs/namei.c (ffffffff812e4a1c)
Location: fs/namei.c:2985
Inline: True
Inline callers:
  - fs/namei.c:do_last
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
In fs/namei.c (ffffffff812f599c)
Location: fs/namei.c:2985
Inline: True
Inline callers:
  - fs/namei.c:do_last
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
</ul>
