# Function: <code>cgroup_css_set_put_fork</code>

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
In <code>5.0</code>: Absent ⚠️
</li>
<li>
In <code>5.3</code>: Absent ⚠️
</li>
<li>
In <code>5.4</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
void cgroup_css_set_put_fork(struct kernel_clone_args *kargs);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cgroup.c (ffffffff81172e20)
Location: kernel/cgroup/cgroup.c:6019
Inline: True
Direct callers:
  - kernel/cgroup/cgroup.c:cgroup_post_fork
  - kernel/cgroup/cgroup.c:cgroup_cancel_fork
  - kernel/cgroup/cgroup.c:cgroup_can_fork
```
**Symbols:**

```
ffffffff81172e20-ffffffff81172f12: cgroup_css_set_put_fork (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
void cgroup_css_set_put_fork(struct kernel_clone_args *kargs);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cgroup.c (ffffffff8116fae0)
Location: kernel/cgroup/cgroup.c:6011
Inline: True
Direct callers:
  - kernel/cgroup/cgroup.c:cgroup_post_fork
  - kernel/cgroup/cgroup.c:cgroup_cancel_fork
  - kernel/cgroup/cgroup.c:cgroup_can_fork
```
**Symbols:**

```
ffffffff8116fae0-ffffffff8116fbde: cgroup_css_set_put_fork (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
void cgroup_css_set_put_fork(struct kernel_clone_args *kargs);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cgroup.c (ffffffff81170710)
Location: kernel/cgroup/cgroup.c:5986
Inline: True
Direct callers:
  - kernel/cgroup/cgroup.c:cgroup_post_fork
  - kernel/cgroup/cgroup.c:cgroup_cancel_fork
  - kernel/cgroup/cgroup.c:cgroup_can_fork
```
**Symbols:**

```
ffffffff81170710-ffffffff8117080e: cgroup_css_set_put_fork (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
void cgroup_css_set_put_fork(struct kernel_clone_args *kargs);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cgroup.c (ffffffff81196c40)
Location: kernel/cgroup/cgroup.c:6202
Inline: True
Direct callers:
  - kernel/cgroup/cgroup.c:cgroup_post_fork
  - kernel/cgroup/cgroup.c:cgroup_cancel_fork
  - kernel/cgroup/cgroup.c:cgroup_can_fork
```
**Symbols:**

```
ffffffff81196c40-ffffffff81196d3e: cgroup_css_set_put_fork (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
void cgroup_css_set_put_fork(struct kernel_clone_args *kargs);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cgroup.c (ffffffff811c6bb0)
Location: kernel/cgroup/cgroup.c:6230
Inline: True
Direct callers:
  - kernel/cgroup/cgroup.c:cgroup_post_fork
  - kernel/cgroup/cgroup.c:cgroup_cancel_fork
  - kernel/cgroup/cgroup.c:cgroup_can_fork
```
**Symbols:**

```
ffffffff811c6bb0-ffffffff811c6ce5: cgroup_css_set_put_fork (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
void cgroup_css_set_put_fork(struct kernel_clone_args *kargs);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cgroup.c (ffffffff812096b0)
Location: kernel/cgroup/cgroup.c:6476
Inline: True
Direct callers:
  - kernel/cgroup/cgroup.c:cgroup_post_fork
  - kernel/cgroup/cgroup.c:cgroup_cancel_fork
  - kernel/cgroup/cgroup.c:cgroup_can_fork
```
**Symbols:**

```
ffffffff812096b0-ffffffff812097e5: cgroup_css_set_put_fork (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void cgroup_css_set_put_fork(struct kernel_clone_args *kargs);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cgroup.c (ffffffff8121ee00)
Location: kernel/cgroup/cgroup.c:6457
Inline: False
Direct callers:
  - kernel/cgroup/cgroup.c:cgroup_post_fork
  - kernel/cgroup/cgroup.c:cgroup_cancel_fork
  - kernel/cgroup/cgroup.c:cgroup_can_fork
```
**Symbols:**

```
ffffffff8121ee00-ffffffff8121ef37: cgroup_css_set_put_fork (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void cgroup_css_set_put_fork(struct kernel_clone_args *kargs);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cgroup.c (ffffffff81236a90)
Location: kernel/cgroup/cgroup.c:6492
Inline: False
Direct callers:
  - kernel/cgroup/cgroup.c:cgroup_post_fork
  - kernel/cgroup/cgroup.c:cgroup_cancel_fork
  - kernel/cgroup/cgroup.c:cgroup_can_fork
```
**Symbols:**

```
ffffffff81236a90-ffffffff81236bc7: cgroup_css_set_put_fork (STB_LOCAL)
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
In <code>armhf</code>: Absent ⚠️
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
In <code>aws</code>: Absent ⚠️
</li>
<li>
In <code>azure</code>: Absent ⚠️
</li>
<li>
In <code>gcp</code>: Absent ⚠️
</li>
<li>
In <code>lowlatency</code>: Absent ⚠️
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
