# Function: <code>snapshot_write_next</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int snapshot_write_next(struct snapshot_handle *handle);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/power/snapshot.c (ffffffff810d2020)
Location: kernel/power/snapshot.c:2469
Inline: False
Direct callers:
  - kernel/power/swap.c:load_image
  - kernel/power/swap.c:load_image_lzo
  - kernel/power/swap.c:load_image_lzo
  - kernel/power/swap.c:swsusp_read
  - kernel/power/user.c:snapshot_write
```
**Symbols:**

```
ffffffff810d2020-ffffffff810d27e1: snapshot_write_next (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int snapshot_write_next(struct snapshot_handle *handle);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/power/snapshot.c (ffffffff810d6da0)
Location: kernel/power/snapshot.c:2554
Inline: False
Direct callers:
  - kernel/power/swap.c:swsusp_read
  - kernel/power/swap.c:load_image_lzo
  - kernel/power/swap.c:load_image_lzo
  - kernel/power/swap.c:load_image
  - kernel/power/user.c:snapshot_write
```
**Symbols:**

```
ffffffff810d6da0-ffffffff810d7453: snapshot_write_next (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int snapshot_write_next(struct snapshot_handle *handle);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/power/snapshot.c (ffffffff810dd920)
Location: kernel/power/snapshot.c:2576
Inline: False
Direct callers:
  - kernel/power/swap.c:swsusp_read
  - kernel/power/swap.c:load_image_lzo
  - kernel/power/swap.c:load_image_lzo
  - kernel/power/swap.c:load_image
  - kernel/power/user.c:snapshot_write
```
**Symbols:**

```
ffffffff810dd920-ffffffff810ddfd4: snapshot_write_next (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int snapshot_write_next(struct snapshot_handle *handle);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/power/snapshot.c (ffffffff810dca10)
Location: kernel/power/snapshot.c:2577
Inline: False
Direct callers:
  - kernel/power/swap.c:swsusp_read
  - kernel/power/swap.c:load_image_lzo
  - kernel/power/swap.c:load_image_lzo
  - kernel/power/swap.c:load_image
  - kernel/power/user.c:snapshot_write
```
**Symbols:**

```
ffffffff810dca10-ffffffff810dd0d5: snapshot_write_next (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int snapshot_write_next(struct snapshot_handle *handle);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/power/snapshot.c (ffffffff810e4c30)
Location: kernel/power/snapshot.c:2578
Inline: False
Direct callers:
  - kernel/power/swap.c:swsusp_read
  - kernel/power/swap.c:load_image_lzo
  - kernel/power/swap.c:load_image_lzo
  - kernel/power/swap.c:load_image
  - kernel/power/user.c:snapshot_write
```
**Symbols:**

```
ffffffff810e4c30-ffffffff810e5300: snapshot_write_next (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int snapshot_write_next(struct snapshot_handle *handle);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/power/snapshot.c (ffffffff810ec8b0)
Location: kernel/power/snapshot.c:2576
Inline: False
Direct callers:
  - kernel/power/swap.c:swsusp_read
  - kernel/power/swap.c:load_image_lzo
  - kernel/power/swap.c:load_image_lzo
  - kernel/power/swap.c:load_image
  - kernel/power/user.c:snapshot_write
```
**Symbols:**

```
ffffffff810ec8b0-ffffffff810ecf77: snapshot_write_next (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int snapshot_write_next(struct snapshot_handle *handle);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/power/snapshot.c (ffffffff810f7f50)
Location: kernel/power/snapshot.c:2577
Inline: False
Direct callers:
  - kernel/power/swap.c:swsusp_read
  - kernel/power/swap.c:load_image_lzo
  - kernel/power/swap.c:load_image_lzo
  - kernel/power/swap.c:load_image
  - kernel/power/user.c:snapshot_write
```
**Symbols:**

```
ffffffff810f7f50-ffffffff810f8617: snapshot_write_next (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
int snapshot_write_next(struct snapshot_handle *handle);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/power/snapshot.c (0)
Location: kernel/power/snapshot.c:2584
Inline: False
Direct callers:
  - kernel/power/swap.c:swsusp_read
  - kernel/power/swap.c:load_image_lzo
  - kernel/power/swap.c:load_image_lzo
  - kernel/power/swap.c:load_image
  - kernel/power/user.c:snapshot_write
```
**Symbols:**

```
ffffffff811016b4-ffffffff811016c8: snapshot_write_next.cold (STB_LOCAL)
ffffffff81100540-ffffffff81100bf4: snapshot_write_next (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
int snapshot_write_next(struct snapshot_handle *handle);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/power/snapshot.c (0)
Location: kernel/power/snapshot.c:2591
Inline: False
Direct callers:
  - kernel/power/swap.c:swsusp_read
  - kernel/power/swap.c:load_image_lzo
  - kernel/power/swap.c:load_image_lzo
  - kernel/power/swap.c:load_image
  - kernel/power/user.c:snapshot_write
```
**Symbols:**

```
ffffffff8110dae7-ffffffff8110dafb: snapshot_write_next.cold (STB_LOCAL)
ffffffff8110c9a0-ffffffff8110d054: snapshot_write_next (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
int snapshot_write_next(struct snapshot_handle *handle);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/power/snapshot.c (0)
Location: kernel/power/snapshot.c:2586
Inline: False
Direct callers:
  - kernel/power/swap.c:swsusp_read
  - kernel/power/swap.c:load_image_lzo
  - kernel/power/swap.c:load_image_lzo
  - kernel/power/swap.c:load_image
  - kernel/power/user.c:snapshot_write
```
**Symbols:**

```
ffffffff81118b02-ffffffff81118b17: snapshot_write_next.cold (STB_LOCAL)
ffffffff81117c20-ffffffff81117ff0: snapshot_write_next (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
int snapshot_write_next(struct snapshot_handle *handle);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/power/snapshot.c (0)
Location: kernel/power/snapshot.c:2628
Inline: False
Direct callers:
  - kernel/power/swap.c:swsusp_read
  - kernel/power/swap.c:load_image_lzo
  - kernel/power/swap.c:load_image_lzo
  - kernel/power/swap.c:load_image
  - kernel/power/user.c:snapshot_write
```
**Symbols:**

```
ffffffff81bdff99-ffffffff81bdffae: snapshot_write_next.cold (STB_LOCAL)
ffffffff81114060-ffffffff81114430: snapshot_write_next (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
int snapshot_write_next(struct snapshot_handle *handle);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/power/snapshot.c (0)
Location: kernel/power/snapshot.c:2628
Inline: False
Direct callers:
  - kernel/power/swap.c:swsusp_read
  - kernel/power/swap.c:load_image_lzo
  - kernel/power/swap.c:load_image_lzo
  - kernel/power/swap.c:load_image
  - kernel/power/user.c:snapshot_write
```
**Symbols:**

```
ffffffff81bd1fa0-ffffffff81bd1fb4: snapshot_write_next.cold (STB_LOCAL)
ffffffff81114950-ffffffff81114c74: snapshot_write_next (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int snapshot_write_next(struct snapshot_handle *handle);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/power/snapshot.c (0)
Location: kernel/power/snapshot.c:2621
Inline: False
Direct callers:
  - kernel/power/swap.c:swsusp_read
  - kernel/power/swap.c:load_image_lzo
  - kernel/power/swap.c:load_image_lzo
  - kernel/power/swap.c:load_image
  - kernel/power/user.c:snapshot_write
```
**Symbols:**

```
ffffffff81caac57-ffffffff81caac95: snapshot_write_next.cold (STB_LOCAL)
ffffffff81134a90-ffffffff81134de6: snapshot_write_next (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int snapshot_write_next(struct snapshot_handle *handle);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/power/snapshot.c (0)
Location: kernel/power/snapshot.c:2625
Inline: False
Direct callers:
  - kernel/power/swap.c:swsusp_read
  - kernel/power/swap.c:load_image_lzo
  - kernel/power/swap.c:load_image_lzo
  - kernel/power/swap.c:load_image
  - kernel/power/user.c:snapshot_write
```
**Symbols:**

```
ffffffff81e5b086-ffffffff81e5b0cb: snapshot_write_next.cold (STB_LOCAL)
ffffffff81156c80-ffffffff8115707d: snapshot_write_next (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
int snapshot_write_next(struct snapshot_handle *handle);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/power/snapshot.c (0)
Location: kernel/power/snapshot.c:2629
Inline: False
Direct callers:
  - kernel/power/swap.c:swsusp_read
  - kernel/power/swap.c:load_image_lzo
  - kernel/power/swap.c:load_image_lzo
  - kernel/power/swap.c:load_image
  - kernel/power/user.c:snapshot_write
```
**Symbols:**

```
ffffffff82058694-ffffffff820586be: snapshot_write_next.cold (STB_LOCAL)
ffffffff811878c0-ffffffff81187d8e: snapshot_write_next (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
int snapshot_write_next(struct snapshot_handle *handle);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/power/snapshot.c (0)
Location: kernel/power/snapshot.c:2681
Inline: False
Direct callers:
  - kernel/power/swap.c:swsusp_read
  - kernel/power/swap.c:load_image_lzo
  - kernel/power/swap.c:load_image_lzo
  - kernel/power/swap.c:load_image
  - kernel/power/user.c:snapshot_write
```
**Symbols:**

```
ffffffff820d6e27-ffffffff820d6e51: snapshot_write_next.cold (STB_LOCAL)
ffffffff81198a50-ffffffff81198f1e: snapshot_write_next (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
int snapshot_write_next(struct snapshot_handle *handle);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/power/snapshot.c (0)
Location: kernel/power/snapshot.c:2778
Inline: False
Direct callers:
  - kernel/power/swap.c:swsusp_read
  - kernel/power/swap.c:load_image_lzo
  - kernel/power/swap.c:load_image_lzo
  - kernel/power/swap.c:load_image
  - kernel/power/user.c:snapshot_write
```
**Symbols:**

```
ffffffff821b20be-ffffffff821b20e8: snapshot_write_next.cold (STB_LOCAL)
ffffffff811a7910-ffffffff811a7f6b: snapshot_write_next (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
In <code>arm64</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int snapshot_write_next(struct snapshot_handle *handle);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/power/snapshot.c (c03bf4c4)
Location: kernel/power/snapshot.c:2591
Inline: False
Direct callers:
  - kernel/power/swap.c:swsusp_read
  - kernel/power/swap.c:swsusp_read
  - kernel/power/swap.c:load_image_lzo
  - kernel/power/swap.c:load_image_lzo
  - kernel/power/user.c:snapshot_write
```
**Symbols:**

```
c03bf4c4-c03bf818: snapshot_write_next (STB_GLOBAL)
```
</details>
</li>
<li>
In <code>ppc64el</code>: Absent ⚠️
</li>
<li>
In <code>riscv64</code>: Absent ⚠️
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Transformation ⚠️</summary>

```c
int snapshot_write_next(struct snapshot_handle *handle);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/power/snapshot.c (0)
Location: kernel/power/snapshot.c:2590
Inline: False
Direct callers:
  - kernel/power/swap.c:swsusp_read
  - kernel/power/swap.c:load_image_lzo
  - kernel/power/swap.c:load_image_lzo
  - kernel/power/swap.c:load_image
  - kernel/power/user.c:snapshot_write
```
**Symbols:**

```
ffffffff81105d07-ffffffff81105d1b: snapshot_write_next.cold (STB_LOCAL)
ffffffff81104bc0-ffffffff81105274: snapshot_write_next (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Transformation ⚠️</summary>

```c
int snapshot_write_next(struct snapshot_handle *handle);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/power/snapshot.c (0)
Location: kernel/power/snapshot.c:2591
Inline: False
Direct callers:
  - kernel/power/swap.c:swsusp_read
  - kernel/power/swap.c:load_image_lzo
  - kernel/power/swap.c:load_image_lzo
  - kernel/power/swap.c:load_image
  - kernel/power/user.c:snapshot_write
```
**Symbols:**

```
ffffffff810f6fa7-ffffffff810f6fbb: snapshot_write_next.cold (STB_LOCAL)
ffffffff810f5e60-ffffffff810f6514: snapshot_write_next (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Transformation ⚠️</summary>

```c
int snapshot_write_next(struct snapshot_handle *handle);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/power/snapshot.c (0)
Location: kernel/power/snapshot.c:2591
Inline: False
Direct callers:
  - kernel/power/swap.c:swsusp_read
  - kernel/power/swap.c:load_image_lzo
  - kernel/power/swap.c:load_image_lzo
  - kernel/power/swap.c:load_image
  - kernel/power/user.c:snapshot_write
```
**Symbols:**

```
ffffffff81103fb7-ffffffff81103fcb: snapshot_write_next.cold (STB_LOCAL)
ffffffff81102e70-ffffffff81103524: snapshot_write_next (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
int snapshot_write_next(struct snapshot_handle *handle);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/power/snapshot.c (0)
Location: kernel/power/snapshot.c:2591
Inline: False
Direct callers:
  - kernel/power/swap.c:swsusp_read
  - kernel/power/swap.c:load_image_lzo
  - kernel/power/swap.c:load_image_lzo
  - kernel/power/swap.c:load_image
  - kernel/power/user.c:snapshot_write
```
**Symbols:**

```
ffffffff8110f3a7-ffffffff8110f3bb: snapshot_write_next.cold (STB_LOCAL)
ffffffff8110e260-ffffffff8110e914: snapshot_write_next (STB_GLOBAL)
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
No changes between <code>amd64</code> and <code>armhf</code> ✅
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
