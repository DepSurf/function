# Function: <code>unbind_rdev_from_array</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void unbind_rdev_from_array(struct md_rdev *rdev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/md.c (ffffffff8168d9e0)
Location: drivers/md/md.c:2132
Inline: False
Direct callers:
  - drivers/md/md.c:md_run
  - drivers/md/md.c:md_run
  - drivers/md/md.c:do_md_stop
  - drivers/md/md.c:add_bound_rdev
  - drivers/md/md.c:state_store
  - drivers/md/md.c:md_ioctl
  - drivers/md/md.c:md_exit
```
**Symbols:**

```
ffffffff8168d9e0-ffffffff8168dafa: unbind_rdev_from_array (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void unbind_rdev_from_array(struct md_rdev *rdev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/md.c (ffffffff816ef050)
Location: drivers/md/md.c:2131
Inline: False
Direct callers:
  - drivers/md/md.c:md_exit
  - drivers/md/md.c:md_ioctl
  - drivers/md/md.c:do_md_stop
  - drivers/md/md.c:md_run
  - drivers/md/md.c:md_run
  - drivers/md/md.c:state_store
  - drivers/md/md.c:add_bound_rdev
```
**Symbols:**

```
ffffffff816ef050-ffffffff816ef16a: unbind_rdev_from_array (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void unbind_rdev_from_array(struct md_rdev *rdev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/md.c (ffffffff817211b0)
Location: drivers/md/md.c:2167
Inline: False
Direct callers:
  - drivers/md/md.c:md_exit
  - drivers/md/md.c:md_ioctl
  - drivers/md/md.c:add_new_disk
  - drivers/md/md.c:do_md_stop
  - drivers/md/md.c:md_run
  - drivers/md/md.c:md_run
  - drivers/md/md.c:state_store
  - drivers/md/md.c:add_bound_rdev
```
**Symbols:**

```
ffffffff817211b0-ffffffff817212db: unbind_rdev_from_array (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void unbind_rdev_from_array(struct md_rdev *rdev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/md.c (ffffffff81738260)
Location: drivers/md/md.c:2202
Inline: False
Direct callers:
  - drivers/md/md.c:md_exit
  - drivers/md/md.c:md_ioctl
  - drivers/md/md.c:add_new_disk
  - drivers/md/md.c:do_md_stop
  - drivers/md/md.c:md_run
  - drivers/md/md.c:md_run
  - drivers/md/md.c:state_store
  - drivers/md/md.c:add_bound_rdev
```
**Symbols:**

```
ffffffff81738260-ffffffff8173838b: unbind_rdev_from_array (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void unbind_rdev_from_array(struct md_rdev *rdev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/md.c (ffffffff817aaa90)
Location: drivers/md/md.c:2249
Inline: False
Direct callers:
  - drivers/md/md.c:md_exit
  - drivers/md/md.c:md_ioctl
  - drivers/md/md.c:add_new_disk
  - drivers/md/md.c:do_md_stop
  - drivers/md/md.c:md_run
  - drivers/md/md.c:md_run
  - drivers/md/md.c:state_store
  - drivers/md/md.c:add_bound_rdev
```
**Symbols:**

```
ffffffff817aaa90-ffffffff817aabbb: unbind_rdev_from_array (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void unbind_rdev_from_array(struct md_rdev *rdev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/md.c (ffffffff817f2a80)
Location: drivers/md/md.c:2264
Inline: False
Direct callers:
  - drivers/md/md.c:md_exit
  - drivers/md/md.c:md_ioctl
  - drivers/md/md.c:add_new_disk
  - drivers/md/md.c:do_md_stop
  - drivers/md/md.c:md_run
  - drivers/md/md.c:md_run
  - drivers/md/md.c:md_run
  - drivers/md/md.c:state_store
  - drivers/md/md.c:add_bound_rdev
```
**Symbols:**

```
ffffffff817f2a80-ffffffff817f2bab: unbind_rdev_from_array (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void unbind_rdev_from_array(struct md_rdev *rdev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/md.c (ffffffff8181e980)
Location: drivers/md/md.c:2255
Inline: False
Direct callers:
  - drivers/md/md.c:md_exit
  - drivers/md/md.c:md_check_recovery
  - drivers/md/md.c:md_ioctl
  - drivers/md/md.c:add_new_disk
  - drivers/md/md.c:do_md_stop
  - drivers/md/md.c:md_run
  - drivers/md/md.c:md_run
  - drivers/md/md.c:md_run
  - drivers/md/md.c:state_store
  - drivers/md/md.c:add_bound_rdev
```
**Symbols:**

```
ffffffff8181e980-ffffffff8181eaab: unbind_rdev_from_array (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void unbind_rdev_from_array(struct md_rdev *rdev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/md.c (ffffffff81861c00)
Location: drivers/md/md.c:2317
Inline: False
Direct callers:
  - drivers/md/md.c:md_exit
  - drivers/md/md.c:md_check_recovery
  - drivers/md/md.c:md_ioctl
  - drivers/md/md.c:add_new_disk
  - drivers/md/md.c:do_md_stop
  - drivers/md/md.c:md_run
  - drivers/md/md.c:md_run
  - drivers/md/md.c:md_run
  - drivers/md/md.c:state_store
  - drivers/md/md.c:add_bound_rdev
```
**Symbols:**

```
ffffffff81861c00-ffffffff81861d37: unbind_rdev_from_array (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void unbind_rdev_from_array(struct md_rdev *rdev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/md.c (ffffffff81893830)
Location: drivers/md/md.c:2371
Inline: False
Direct callers:
  - drivers/md/md.c:md_exit
  - drivers/md/md.c:md_check_recovery
  - drivers/md/md.c:md_ioctl
  - drivers/md/md.c:add_new_disk
  - drivers/md/md.c:do_md_stop
  - drivers/md/md.c:md_run
  - drivers/md/md.c:md_run
  - drivers/md/md.c:md_run
  - drivers/md/md.c:state_store
  - drivers/md/md.c:add_bound_rdev
```
**Symbols:**

```
ffffffff81893830-ffffffff81893967: unbind_rdev_from_array (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void unbind_rdev_from_array(struct md_rdev *rdev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/md.c (ffffffff819634a0)
Location: drivers/md/md.c:2497
Inline: False
Direct callers:
  - drivers/md/md.c:md_check_recovery
  - drivers/md/md.c:hot_remove_disk
  - drivers/md/md.c:add_new_disk
  - drivers/md/md.c:analyze_sbs
  - drivers/md/md.c:analyze_sbs
  - drivers/md/md.c:analyze_sbs
  - drivers/md/md.c:state_store
  - drivers/md/md.c:add_bound_rdev
  - drivers/md/md.c:export_array
```
**Symbols:**

```
ffffffff819634a0-ffffffff819635f4: unbind_rdev_from_array (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void unbind_rdev_from_array(struct md_rdev *rdev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/md.c (ffffffff81969d50)
Location: drivers/md/md.c:2514
Inline: False
Direct callers:
  - drivers/md/md.c:md_check_recovery
  - drivers/md/md.c:hot_remove_disk
  - drivers/md/md.c:md_add_new_disk
  - drivers/md/md.c:analyze_sbs
  - drivers/md/md.c:analyze_sbs
  - drivers/md/md.c:analyze_sbs
  - drivers/md/md.c:state_store
  - drivers/md/md.c:add_bound_rdev
  - drivers/md/md.c:export_array
```
**Symbols:**

```
ffffffff81969d50-ffffffff81969ed2: unbind_rdev_from_array (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void unbind_rdev_from_array(struct md_rdev *rdev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/md.c (ffffffff8194e040)
Location: drivers/md/md.c:2478
Inline: False
Direct callers:
  - drivers/md/md.c:md_check_recovery
  - drivers/md/md.c:hot_remove_disk
  - drivers/md/md.c:md_add_new_disk
  - drivers/md/md.c:analyze_sbs
  - drivers/md/md.c:analyze_sbs
  - drivers/md/md.c:analyze_sbs
  - drivers/md/md.c:state_store
  - drivers/md/md.c:add_bound_rdev
  - drivers/md/md.c:export_array
```
**Symbols:**

```
ffffffff8194e040-ffffffff8194e1c2: unbind_rdev_from_array (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void unbind_rdev_from_array(struct md_rdev *rdev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/md.c (ffffffff819f3440)
Location: drivers/md/md.c:2488
Inline: False
Direct callers:
  - drivers/md/md.c:md_check_recovery
  - drivers/md/md.c:hot_remove_disk
  - drivers/md/md.c:md_add_new_disk
  - drivers/md/md.c:analyze_sbs
  - drivers/md/md.c:analyze_sbs
  - drivers/md/md.c:analyze_sbs
  - drivers/md/md.c:state_store
  - drivers/md/md.c:add_bound_rdev
  - drivers/md/md.c:export_array
```
**Symbols:**

```
ffffffff819f3440-ffffffff819f35c2: unbind_rdev_from_array (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void unbind_rdev_from_array(struct md_rdev *rdev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/md.c (ffffffff81b5f420)
Location: drivers/md/md.c:2482
Inline: False
Direct callers:
  - drivers/md/md.c:md_check_recovery
  - drivers/md/md.c:hot_remove_disk
  - drivers/md/md.c:md_add_new_disk
  - drivers/md/md.c:analyze_sbs
  - drivers/md/md.c:analyze_sbs
  - drivers/md/md.c:analyze_sbs
  - drivers/md/md.c:state_store
  - drivers/md/md.c:add_bound_rdev
  - drivers/md/md.c:export_array
```
**Symbols:**

```
ffffffff81b5f420-ffffffff81b5f579: unbind_rdev_from_array (STB_LOCAL)
```
</details>
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
<summary>In <code>arm64</code>: ✅</summary>

```c
void unbind_rdev_from_array(struct md_rdev *rdev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/md.c (ffff800010aea4d8)
Location: drivers/md/md.c:2371
Inline: False
Direct callers:
  - drivers/md/md.c:md_exit
  - drivers/md/md.c:md_ioctl
  - drivers/md/md.c:add_new_disk
  - drivers/md/md.c:do_md_stop
  - drivers/md/md.c:md_run
  - drivers/md/md.c:md_run
  - drivers/md/md.c:md_run
  - drivers/md/md.c:state_store
  - drivers/md/md.c:add_bound_rdev
```
**Symbols:**

```
ffff800010aea4d8-ffff800010aea5f4: unbind_rdev_from_array (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void unbind_rdev_from_array(struct md_rdev *rdev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/md.c (c0bc9200)
Location: drivers/md/md.c:2371
Inline: False
Direct callers:
  - drivers/md/md.c:md_exit
  - drivers/md/md.c:md_check_recovery
  - drivers/md/md.c:md_ioctl
  - drivers/md/md.c:add_new_disk
  - drivers/md/md.c:do_md_stop
  - drivers/md/md.c:md_run
  - drivers/md/md.c:md_run
  - drivers/md/md.c:md_run
  - drivers/md/md.c:state_store
  - drivers/md/md.c:add_bound_rdev
```
**Symbols:**

```
c0bc9200-c0bc932c: unbind_rdev_from_array (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void unbind_rdev_from_array(struct md_rdev *rdev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/md.c (c000000000bd1420)
Location: drivers/md/md.c:2371
Inline: False
Direct callers:
  - drivers/md/md.c:md_exit
  - drivers/md/md.c:md_check_recovery
  - drivers/md/md.c:md_ioctl
  - drivers/md/md.c:add_new_disk
  - drivers/md/md.c:do_md_stop
  - drivers/md/md.c:md_run
  - drivers/md/md.c:md_run
  - drivers/md/md.c:md_run
  - drivers/md/md.c:state_store
  - drivers/md/md.c:add_bound_rdev
```
**Symbols:**

```
c000000000bd1420-c000000000bd1598: unbind_rdev_from_array (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void unbind_rdev_from_array(struct md_rdev *rdev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/md.c (ffffffe0006dc0f0)
Location: drivers/md/md.c:2371
Inline: False
Direct callers:
  - drivers/md/md.c:md_exit
  - drivers/md/md.c:md_ioctl
  - drivers/md/md.c:add_new_disk
  - drivers/md/md.c:do_md_stop
  - drivers/md/md.c:md_run
  - drivers/md/md.c:md_run
  - drivers/md/md.c:md_run
  - drivers/md/md.c:state_store
  - drivers/md/md.c:add_bound_rdev
```
**Symbols:**

```
ffffffe0006dc0f0-ffffffe0006dc1ee: unbind_rdev_from_array (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: ✅</summary>

```c
void unbind_rdev_from_array(struct md_rdev *rdev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/md.c (ffffffff818396b0)
Location: drivers/md/md.c:2371
Inline: False
Direct callers:
  - drivers/md/md.c:md_exit
  - drivers/md/md.c:md_check_recovery
  - drivers/md/md.c:md_ioctl
  - drivers/md/md.c:add_new_disk
  - drivers/md/md.c:do_md_stop
  - drivers/md/md.c:md_run
  - drivers/md/md.c:md_run
  - drivers/md/md.c:md_run
  - drivers/md/md.c:state_store
  - drivers/md/md.c:add_bound_rdev
```
**Symbols:**

```
ffffffff818396b0-ffffffff818397e7: unbind_rdev_from_array (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void unbind_rdev_from_array(struct md_rdev *rdev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/md.c (ffffffff81800d20)
Location: drivers/md/md.c:2371
Inline: False
Direct callers:
  - drivers/md/md.c:md_exit
  - drivers/md/md.c:md_check_recovery
  - drivers/md/md.c:md_ioctl
  - drivers/md/md.c:add_new_disk
  - drivers/md/md.c:do_md_stop
  - drivers/md/md.c:md_run
  - drivers/md/md.c:md_run
  - drivers/md/md.c:md_run
  - drivers/md/md.c:state_store
  - drivers/md/md.c:add_bound_rdev
```
**Symbols:**

```
ffffffff81800d20-ffffffff81800e57: unbind_rdev_from_array (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void unbind_rdev_from_array(struct md_rdev *rdev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/md.c (ffffffff81888ce0)
Location: drivers/md/md.c:2371
Inline: False
Direct callers:
  - drivers/md/md.c:md_exit
  - drivers/md/md.c:md_check_recovery
  - drivers/md/md.c:md_ioctl
  - drivers/md/md.c:add_new_disk
  - drivers/md/md.c:do_md_stop
  - drivers/md/md.c:md_run
  - drivers/md/md.c:md_run
  - drivers/md/md.c:md_run
  - drivers/md/md.c:state_store
  - drivers/md/md.c:add_bound_rdev
```
**Symbols:**

```
ffffffff81888ce0-ffffffff81888e17: unbind_rdev_from_array (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void unbind_rdev_from_array(struct md_rdev *rdev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/md.c (ffffffff818a6410)
Location: drivers/md/md.c:2371
Inline: False
Direct callers:
  - drivers/md/md.c:md_exit
  - drivers/md/md.c:md_check_recovery
  - drivers/md/md.c:md_ioctl
  - drivers/md/md.c:add_new_disk
  - drivers/md/md.c:do_md_stop
  - drivers/md/md.c:md_run
  - drivers/md/md.c:md_run
  - drivers/md/md.c:md_run
  - drivers/md/md.c:state_store
  - drivers/md/md.c:add_bound_rdev
```
**Symbols:**

```
ffffffff818a6410-ffffffff818a6547: unbind_rdev_from_array (STB_LOCAL)
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
</ul>
<b>Arch</b>
<ul>
<li>
No changes between <code>amd64</code> and <code>arm64</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>armhf</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>ppc64el</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>riscv64</code> ✅
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
