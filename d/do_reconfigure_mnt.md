# Function: <code>do_reconfigure_mnt</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4</code>: Absent ⚠️
</li>
<li>
In <code>4.8</code>: Absent ⚠️
</li>
<li>
In <code>4.10</code>: Absent ⚠️
</li>
<li>
In <code>4.13</code>: Absent ⚠️
</li>
<li>
In <code>4.15</code>: Absent ⚠️
</li>
<li>
In <code>4.18</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>5.0</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/namespace.c (ffffffff812d617d)
Location: fs/namespace.c:2289
Inline: True
Inline callers:
  - fs/namespace.c:do_mount
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
In fs/namespace.c (ffffffff812f4900)
Location: fs/namespace.c:2480
Inline: True
Inline callers:
  - fs/namespace.c:do_mount
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
In fs/namespace.c (ffffffff8130649e)
Location: fs/namespace.c:2505
Inline: True
Inline callers:
  - fs/namespace.c:do_mount
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int do_reconfigure_mnt(struct path *path, unsigned int mnt_flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namespace.c (ffffffff8133c000)
Location: fs/namespace.c:2563
Inline: False
Direct callers:
  - fs/namespace.c:do_mount
```
**Symbols:**

```
ffffffff8133c000-ffffffff8133c1f8: do_reconfigure_mnt (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int do_reconfigure_mnt(struct path *path, unsigned int mnt_flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namespace.c (ffffffff81347ea0)
Location: fs/namespace.c:2569
Inline: False
Direct callers:
  - fs/namespace.c:path_mount
```
**Symbols:**

```
ffffffff81347ea0-ffffffff81348098: do_reconfigure_mnt (STB_LOCAL)
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
In fs/namespace.c (ffffffff8135288b)
Location: fs/namespace.c:2593
Inline: True
Inline callers:
  - fs/namespace.c:path_mount
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
In fs/namespace.c (ffffffff813a0c9c)
Location: fs/namespace.c:2595
Inline: True
Inline callers:
  - fs/namespace.c:path_mount
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
In fs/namespace.c (ffffffff8142466b)
Location: fs/namespace.c:2638
Inline: True
Inline callers:
  - fs/namespace.c:path_mount
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
In fs/namespace.c (ffffffff814b0dce)
Location: fs/namespace.c:2743
Inline: True
Inline callers:
  - fs/namespace.c:path_mount
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
In fs/namespace.c (ffffffff814e5e0e)
Location: fs/namespace.c:2818
Inline: True
Inline callers:
  - fs/namespace.c:path_mount
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
In fs/namespace.c (ffffffff81519c3e)
Location: fs/namespace.c:2823
Inline: True
Inline callers:
  - fs/namespace.c:path_mount
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
In fs/namespace.c (ffff8000103b9a40)
Location: fs/namespace.c:2505
Inline: True
Inline callers:
  - fs/namespace.c:do_mount
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
In fs/namespace.c (c0597574)
Location: fs/namespace.c:2505
Inline: True
Inline callers:
  - fs/namespace.c:do_mount
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
In fs/namespace.c (c0000000004b7060)
Location: fs/namespace.c:2505
Inline: True
Inline callers:
  - fs/namespace.c:do_mount
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
In fs/namespace.c (ffffffe00027bd28)
Location: fs/namespace.c:2505
Inline: True
Inline callers:
  - fs/namespace.c:do_mount
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
In fs/namespace.c (ffffffff812fea7e)
Location: fs/namespace.c:2505
Inline: True
Inline callers:
  - fs/namespace.c:do_mount
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
In fs/namespace.c (ffffffff812ef69e)
Location: fs/namespace.c:2505
Inline: True
Inline callers:
  - fs/namespace.c:do_mount
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
In fs/namespace.c (ffffffff812fc86e)
Location: fs/namespace.c:2505
Inline: True
Inline callers:
  - fs/namespace.c:do_mount
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
In fs/namespace.c (ffffffff8130dbce)
Location: fs/namespace.c:2505
Inline: True
Inline callers:
  - fs/namespace.c:do_mount
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
