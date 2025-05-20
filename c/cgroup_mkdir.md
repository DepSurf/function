# Function: <code>cgroup_mkdir</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline ⚠️</summary>

```c
int cgroup_mkdir(struct kernfs_node *parent_kn, const char *name, umode_t mode);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/cgroup.c (ffffffff81118680)
Location: kernel/cgroup.c:5021
Inline: True
```
**Symbols:**

```
ffffffff81118680-ffffffff81118921: cgroup_mkdir (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
int cgroup_mkdir(struct kernfs_node *parent_kn, const char *name, umode_t mode);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/cgroup.c (ffffffff81120170)
Location: kernel/cgroup.c:5288
Inline: True
```
**Symbols:**

```
ffffffff81120170-ffffffff8112045b: cgroup_mkdir (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
int cgroup_mkdir(struct kernfs_node *parent_kn, const char *name, umode_t mode);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/cgroup.c (ffffffff81128630)
Location: kernel/cgroup.c:5305
Inline: True
```
**Symbols:**

```
ffffffff81128630-ffffffff81128943: cgroup_mkdir (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int cgroup_mkdir(struct kernfs_node *parent_kn, const char *name, umode_t mode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cgroup.c (ffffffff81127b10)
Location: kernel/cgroup/cgroup.c:4258
Inline: False
```
**Symbols:**

```
ffffffff81127b10-ffffffff81127e38: cgroup_mkdir (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int cgroup_mkdir(struct kernfs_node *parent_kn, const char *name, umode_t mode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cgroup.c (ffffffff81133f70)
Location: kernel/cgroup/cgroup.c:4891
Inline: False
```
**Symbols:**

```
ffffffff81133f70-ffffffff8113435f: cgroup_mkdir (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int cgroup_mkdir(struct kernfs_node *parent_kn, const char *name, umode_t mode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cgroup.c (ffffffff81142670)
Location: kernel/cgroup/cgroup.c:4931
Inline: False
```
**Symbols:**

```
ffffffff81142670-ffffffff81142a8d: cgroup_mkdir (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int cgroup_mkdir(struct kernfs_node *parent_kn, const char *name, umode_t mode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cgroup.c (ffffffff8114e0f0)
Location: kernel/cgroup/cgroup.c:5025
Inline: False
```
**Symbols:**

```
ffffffff8114e0f0-ffffffff8114e56c: cgroup_mkdir (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int cgroup_mkdir(struct kernfs_node *parent_kn, const char *name, umode_t mode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cgroup.c (ffffffff81159ed0)
Location: kernel/cgroup/cgroup.c:5354
Inline: False
```
**Symbols:**

```
ffffffff81159ed0-ffffffff8115a09f: cgroup_mkdir (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int cgroup_mkdir(struct kernfs_node *parent_kn, const char *name, umode_t mode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cgroup.c (ffffffff81165b60)
Location: kernel/cgroup/cgroup.c:5369
Inline: False
```
**Symbols:**

```
ffffffff81165b60-ffffffff81165d33: cgroup_mkdir (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int cgroup_mkdir(struct kernfs_node *parent_kn, const char *name, umode_t mode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cgroup.c (ffffffff81176ce0)
Location: kernel/cgroup/cgroup.c:5320
Inline: False
```
**Symbols:**

```
ffffffff81176ce0-ffffffff81176e79: cgroup_mkdir (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int cgroup_mkdir(struct kernfs_node *parent_kn, const char *name, umode_t mode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cgroup.c (ffffffff811739e0)
Location: kernel/cgroup/cgroup.c:5312
Inline: False
```
**Symbols:**

```
ffffffff811739e0-ffffffff81173b68: cgroup_mkdir (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int cgroup_mkdir(struct kernfs_node *parent_kn, const char *name, umode_t mode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cgroup.c (ffffffff811745b0)
Location: kernel/cgroup/cgroup.c:5293
Inline: False
```
**Symbols:**

```
ffffffff811745b0-ffffffff8117473b: cgroup_mkdir (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int cgroup_mkdir(struct kernfs_node *parent_kn, const char *name, umode_t mode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cgroup.c (ffffffff8119b660)
Location: kernel/cgroup/cgroup.c:5483
Inline: False
```
**Symbols:**

```
ffffffff8119b660-ffffffff8119b7e5: cgroup_mkdir (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int cgroup_mkdir(struct kernfs_node *parent_kn, const char *name, umode_t mode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cgroup.c (ffffffff811cb870)
Location: kernel/cgroup/cgroup.c:5494
Inline: False
```
**Symbols:**

```
ffffffff811cb870-ffffffff811cba1e: cgroup_mkdir (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int cgroup_mkdir(struct kernfs_node *parent_kn, const char *name, umode_t mode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cgroup.c (ffffffff8120ed00)
Location: kernel/cgroup/cgroup.c:5710
Inline: False
```
**Symbols:**

```
ffffffff8120ed00-ffffffff8120eeae: cgroup_mkdir (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int cgroup_mkdir(struct kernfs_node *parent_kn, const char *name, umode_t mode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cgroup.c (ffffffff81224710)
Location: kernel/cgroup/cgroup.c:5691
Inline: False
```
**Symbols:**

```
ffffffff81224710-ffffffff812248be: cgroup_mkdir (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int cgroup_mkdir(struct kernfs_node *parent_kn, const char *name, umode_t mode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cgroup.c (ffffffff8123c400)
Location: kernel/cgroup/cgroup.c:5728
Inline: False
```
**Symbols:**

```
ffffffff8123c400-ffffffff8123c59f: cgroup_mkdir (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: ✅</summary>

```c
int cgroup_mkdir(struct kernfs_node *parent_kn, const char *name, umode_t mode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cgroup.c (ffff8000101d7618)
Location: kernel/cgroup/cgroup.c:5369
Inline: False
```
**Symbols:**

```
ffff8000101d7618-ffff8000101d782c: cgroup_mkdir (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int cgroup_mkdir(struct kernfs_node *parent_kn, const char *name, umode_t mode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cgroup.c (c041a384)
Location: kernel/cgroup/cgroup.c:5369
Inline: False
```
**Symbols:**

```
c041a384-c041a58c: cgroup_mkdir (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int cgroup_mkdir(struct kernfs_node *parent_kn, const char *name, umode_t mode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cgroup.c (c000000000243f30)
Location: kernel/cgroup/cgroup.c:5369
Inline: False
```
**Symbols:**

```
c000000000243f30-c00000000024456c: cgroup_mkdir (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int cgroup_mkdir(struct kernfs_node *parent_kn, const char *name, umode_t mode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cgroup.c (ffffffe0001507a4)
Location: kernel/cgroup/cgroup.c:5369
Inline: False
```
**Symbols:**

```
ffffffe0001507a4-ffffffe000150964: cgroup_mkdir (STB_GLOBAL)
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
int cgroup_mkdir(struct kernfs_node *parent_kn, const char *name, umode_t mode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cgroup.c (ffffffff8115e180)
Location: kernel/cgroup/cgroup.c:5369
Inline: False
```
**Symbols:**

```
ffffffff8115e180-ffffffff8115e353: cgroup_mkdir (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int cgroup_mkdir(struct kernfs_node *parent_kn, const char *name, umode_t mode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cgroup.c (ffffffff81151450)
Location: kernel/cgroup/cgroup.c:5369
Inline: False
```
**Symbols:**

```
ffffffff81151450-ffffffff81151623: cgroup_mkdir (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int cgroup_mkdir(struct kernfs_node *parent_kn, const char *name, umode_t mode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cgroup.c (ffffffff8115bf50)
Location: kernel/cgroup/cgroup.c:5369
Inline: False
```
**Symbols:**

```
ffffffff8115bf50-ffffffff8115c123: cgroup_mkdir (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int cgroup_mkdir(struct kernfs_node *parent_kn, const char *name, umode_t mode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cgroup.c (ffffffff81169070)
Location: kernel/cgroup/cgroup.c:5369
Inline: False
```
**Symbols:**

```
ffffffff81169070-ffffffff81169258: cgroup_mkdir (STB_GLOBAL)
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
