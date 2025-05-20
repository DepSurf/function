# Function: <code>copy_params</code>

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
In drivers/md/dm-ioctl.c (ffffffff816a9e9a)
Location: drivers/md/dm-ioctl.c:1687
Inline: True
Inline callers:
  - drivers/md/dm-ioctl.c:ctl_ioctl
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
In drivers/md/dm-ioctl.c (ffffffff8170a2eb)
Location: drivers/md/dm-ioctl.c:1694
Inline: True
Inline callers:
  - drivers/md/dm-ioctl.c:ctl_ioctl
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
In drivers/md/dm-ioctl.c (ffffffff8173c1bb)
Location: drivers/md/dm-ioctl.c:1694
Inline: True
Inline callers:
  - drivers/md/dm-ioctl.c:ctl_ioctl
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
In drivers/md/dm-ioctl.c (ffffffff81755a7e)
Location: drivers/md/dm-ioctl.c:1713
Inline: True
Inline callers:
  - drivers/md/dm-ioctl.c:ctl_ioctl
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
In drivers/md/dm-ioctl.c (ffffffff817c7d1e)
Location: drivers/md/dm-ioctl.c:1721
Inline: True
Inline callers:
  - drivers/md/dm-ioctl.c:ctl_ioctl
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
In drivers/md/dm-ioctl.c (ffffffff8180f8cc)
Location: drivers/md/dm-ioctl.c:1722
Inline: True
Inline callers:
  - drivers/md/dm-ioctl.c:ctl_ioctl
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
In drivers/md/dm-ioctl.c (ffffffff8183b8b4)
Location: drivers/md/dm-ioctl.c:1722
Inline: True
Inline callers:
  - drivers/md/dm-ioctl.c:ctl_ioctl
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
In drivers/md/dm-ioctl.c (ffffffff8187f472)
Location: drivers/md/dm-ioctl.c:1722
Inline: True
Inline callers:
  - drivers/md/dm-ioctl.c:ctl_ioctl
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
In drivers/md/dm-ioctl.c (ffffffff818b12f2)
Location: drivers/md/dm-ioctl.c:1748
Inline: True
Inline callers:
  - drivers/md/dm-ioctl.c:ctl_ioctl
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int copy_params(struct dm_ioctl *user, struct dm_ioctl *param_kernel, int ioctl_flags, struct dm_ioctl **param, int *param_flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/dm-ioctl.c (ffffffff819810f0)
Location: drivers/md/dm-ioctl.c:1748
Inline: False
Direct callers:
  - drivers/md/dm-ioctl.c:ctl_ioctl
```
**Symbols:**

```
ffffffff819810f0-ffffffff819812de: copy_params (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int copy_params(struct dm_ioctl *user, struct dm_ioctl *param_kernel, int ioctl_flags, struct dm_ioctl **param, int *param_flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/dm-ioctl.c (ffffffff81985710)
Location: drivers/md/dm-ioctl.c:1749
Inline: False
Direct callers:
  - drivers/md/dm-ioctl.c:ctl_ioctl
```
**Symbols:**

```
ffffffff81985710-ffffffff819858fe: copy_params (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int copy_params(struct dm_ioctl *user, struct dm_ioctl *param_kernel, int ioctl_flags, struct dm_ioctl **param, int *param_flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/dm-ioctl.c (ffffffff81969050)
Location: drivers/md/dm-ioctl.c:1826
Inline: False
Direct callers:
  - drivers/md/dm-ioctl.c:ctl_ioctl
```
**Symbols:**

```
ffffffff81969050-ffffffff81969233: copy_params (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int copy_params(struct dm_ioctl *user, struct dm_ioctl *param_kernel, int ioctl_flags, struct dm_ioctl **param, int *param_flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/dm-ioctl.c (ffffffff81a11270)
Location: drivers/md/dm-ioctl.c:1841
Inline: False
Direct callers:
  - drivers/md/dm-ioctl.c:ctl_ioctl
```
**Symbols:**

```
ffffffff81a11270-ffffffff81a11453: copy_params (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int copy_params(struct dm_ioctl *user, struct dm_ioctl *param_kernel, int ioctl_flags, struct dm_ioctl **param, int *param_flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/md/dm-ioctl.c (0)
Location: drivers/md/dm-ioctl.c:1849
Inline: False
Direct callers:
  - drivers/md/dm-ioctl.c:ctl_ioctl
```
**Symbols:**

```
ffffffff81b79960-ffffffff81b79b5b: copy_params (STB_LOCAL)
ffffffff81ef6439-ffffffff81ef644f: copy_params.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int copy_params(struct dm_ioctl *user, struct dm_ioctl *param_kernel, int ioctl_flags, struct dm_ioctl **param, int *param_flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/dm-ioctl.c (ffffffff81d17d70)
Location: drivers/md/dm-ioctl.c:1856
Inline: False
Direct callers:
  - drivers/md/dm-ioctl.c:ctl_ioctl
```
**Symbols:**

```
ffffffff81d17d70-ffffffff81d17fd7: copy_params (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int copy_params(struct dm_ioctl *user, struct dm_ioctl *param_kernel, int ioctl_flags, struct dm_ioctl **param, int *param_flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/dm-ioctl.c (ffffffff81d80ff0)
Location: drivers/md/dm-ioctl.c:1926
Inline: False
Direct callers:
  - drivers/md/dm-ioctl.c:ctl_ioctl
```
**Symbols:**

```
ffffffff81d80ff0-ffffffff81d812b1: copy_params (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int copy_params(struct dm_ioctl *user, struct dm_ioctl *param_kernel, int ioctl_flags, struct dm_ioctl **param, int *param_flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/dm-ioctl.c (ffffffff81e38650)
Location: drivers/md/dm-ioctl.c:1931
Inline: False
Direct callers:
  - drivers/md/dm-ioctl.c:ctl_ioctl
```
**Symbols:**

```
ffffffff81e38650-ffffffff81e38926: copy_params (STB_LOCAL)
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
In drivers/md/dm-ioctl.c (ffff800010b09320)
Location: drivers/md/dm-ioctl.c:1748
Inline: True
Inline callers:
  - drivers/md/dm-ioctl.c:ctl_ioctl
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
In drivers/md/dm-ioctl.c (c0be7aec)
Location: drivers/md/dm-ioctl.c:1748
Inline: True
Inline callers:
  - drivers/md/dm-ioctl.c:ctl_ioctl
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
In drivers/md/dm-ioctl.c (c000000000bfad80)
Location: drivers/md/dm-ioctl.c:1748
Inline: True
Inline callers:
  - drivers/md/dm-ioctl.c:ctl_ioctl
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
In drivers/md/dm-ioctl.c (ffffffe0006f78d2)
Location: drivers/md/dm-ioctl.c:1748
Inline: True
Inline callers:
  - drivers/md/dm-ioctl.c:ctl_ioctl
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
In drivers/md/dm-ioctl.c (ffffffff81857172)
Location: drivers/md/dm-ioctl.c:1748
Inline: True
Inline callers:
  - drivers/md/dm-ioctl.c:ctl_ioctl
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
In drivers/md/dm-ioctl.c (ffffffff8181e782)
Location: drivers/md/dm-ioctl.c:1748
Inline: True
Inline callers:
  - drivers/md/dm-ioctl.c:ctl_ioctl
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
In drivers/md/dm-ioctl.c (ffffffff818a67a2)
Location: drivers/md/dm-ioctl.c:1748
Inline: True
Inline callers:
  - drivers/md/dm-ioctl.c:ctl_ioctl
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
In drivers/md/dm-ioctl.c (ffffffff818c29e2)
Location: drivers/md/dm-ioctl.c:1748
Inline: True
Inline callers:
  - drivers/md/dm-ioctl.c:ctl_ioctl
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
