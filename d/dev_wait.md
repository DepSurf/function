# Function: <code>dev_wait</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int dev_wait(struct dm_ioctl *param, size_t param_size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/dm-ioctl.c (ffffffff816aa510)
Location: drivers/md/dm-ioctl.c:1173
Inline: False
```
**Symbols:**

```
ffffffff816aa510-ffffffff816aa5cd: dev_wait (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int dev_wait(struct dm_ioctl *param, size_t param_size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/dm-ioctl.c (ffffffff8170a980)
Location: drivers/md/dm-ioctl.c:1173
Inline: False
```
**Symbols:**

```
ffffffff8170a980-ffffffff8170aa44: dev_wait (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int dev_wait(struct dm_ioctl *param, size_t param_size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/dm-ioctl.c (ffffffff8173c850)
Location: drivers/md/dm-ioctl.c:1173
Inline: False
```
**Symbols:**

```
ffffffff8173c850-ffffffff8173c914: dev_wait (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int dev_wait(struct file *filp, struct dm_ioctl *param, size_t param_size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/dm-ioctl.c (ffffffff81756230)
Location: drivers/md/dm-ioctl.c:1178
Inline: False
```
**Symbols:**

```
ffffffff81756230-ffffffff817562f7: dev_wait (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int dev_wait(struct file *filp, struct dm_ioctl *param, size_t param_size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/dm-ioctl.c (ffffffff817c8440)
Location: drivers/md/dm-ioctl.c:1185
Inline: False
```
**Symbols:**

```
ffffffff817c8440-ffffffff817c8507: dev_wait (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int dev_wait(struct file *filp, struct dm_ioctl *param, size_t param_size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/dm-ioctl.c (ffffffff81810ee0)
Location: drivers/md/dm-ioctl.c:1185
Inline: False
```
**Symbols:**

```
ffffffff81810ee0-ffffffff81810fa7: dev_wait (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int dev_wait(struct file *filp, struct dm_ioctl *param, size_t param_size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/dm-ioctl.c (ffffffff8183cee0)
Location: drivers/md/dm-ioctl.c:1185
Inline: False
```
**Symbols:**

```
ffffffff8183cee0-ffffffff8183cfa7: dev_wait (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int dev_wait(struct file *filp, struct dm_ioctl *param, size_t param_size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/dm-ioctl.c (ffffffff8187fde0)
Location: drivers/md/dm-ioctl.c:1185
Inline: False
```
**Symbols:**

```
ffffffff8187fde0-ffffffff8187fea3: dev_wait (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int dev_wait(struct file *filp, struct dm_ioctl *param, size_t param_size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/dm-ioctl.c (ffffffff818b1ca0)
Location: drivers/md/dm-ioctl.c:1210
Inline: False
```
**Symbols:**

```
ffffffff818b1ca0-ffffffff818b1d63: dev_wait (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
int dev_wait(struct file *filp, struct dm_ioctl *param, size_t param_size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/md/dm-ioctl.c (0)
Location: drivers/md/dm-ioctl.c:1210
Inline: False
```
**Symbols:**

```
ffffffff819820f0-ffffffff81982242: dev_wait (STB_LOCAL)
ffffffff81982c3d-ffffffff81982c5a: dev_wait.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
int dev_wait(struct file *filp, struct dm_ioctl *param, size_t param_size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/md/dm-ioctl.c (0)
Location: drivers/md/dm-ioctl.c:1210
Inline: False
```
**Symbols:**

```
ffffffff81986710-ffffffff81986862: dev_wait (STB_LOCAL)
ffffffff81c2857b-ffffffff81c28598: dev_wait.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
int dev_wait(struct file *filp, struct dm_ioctl *param, size_t param_size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/md/dm-ioctl.c (0)
Location: drivers/md/dm-ioctl.c:1287
Inline: False
```
**Symbols:**

```
ffffffff8196abe0-ffffffff8196ad32: dev_wait (STB_LOCAL)
ffffffff81c1a73d-ffffffff81c1a75a: dev_wait.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int dev_wait(struct file *filp, struct dm_ioctl *param, size_t param_size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/md/dm-ioctl.c (0)
Location: drivers/md/dm-ioctl.c:1300
Inline: False
```
**Symbols:**

```
ffffffff81a130a0-ffffffff81a131f2: dev_wait (STB_LOCAL)
ffffffff81d2a5a4-ffffffff81d2a5c1: dev_wait.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int dev_wait(struct file *filp, struct dm_ioctl *param, size_t param_size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/md/dm-ioctl.c (0)
Location: drivers/md/dm-ioctl.c:1307
Inline: False
```
**Symbols:**

```
ffffffff81b7b900-ffffffff81b7ba54: dev_wait (STB_LOCAL)
ffffffff81ef67e8-ffffffff81ef6805: dev_wait.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int dev_wait(struct file *filp, struct dm_ioctl *param, size_t param_size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/dm-ioctl.c (ffffffff81d18dc0)
Location: drivers/md/dm-ioctl.c:1314
Inline: False
```
**Symbols:**

```
ffffffff81d18dc0-ffffffff81d18f26: dev_wait (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int dev_wait(struct file *filp, struct dm_ioctl *param, size_t param_size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/dm-ioctl.c (ffffffff81d81fd0)
Location: drivers/md/dm-ioctl.c:1338
Inline: False
```
**Symbols:**

```
ffffffff81d81fd0-ffffffff81d820d2: dev_wait (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int dev_wait(struct file *filp, struct dm_ioctl *param, size_t param_size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/dm-ioctl.c (ffffffff81e39640)
Location: drivers/md/dm-ioctl.c:1338
Inline: False
```
**Symbols:**

```
ffffffff81e39640-ffffffff81e39742: dev_wait (STB_LOCAL)
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
int dev_wait(struct file *filp, struct dm_ioctl *param, size_t param_size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/dm-ioctl.c (ffff800010b08ac8)
Location: drivers/md/dm-ioctl.c:1210
Inline: False
```
**Symbols:**

```
ffff800010b08ac8-ffff800010b08b9c: dev_wait (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int dev_wait(struct file *filp, struct dm_ioctl *param, size_t param_size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/dm-ioctl.c (c0be6b60)
Location: drivers/md/dm-ioctl.c:1210
Inline: False
```
**Symbols:**

```
c0be6b60-c0be6c34: dev_wait (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int dev_wait(struct file *filp, struct dm_ioctl *param, size_t param_size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/dm-ioctl.c (c000000000bfa5c0)
Location: drivers/md/dm-ioctl.c:1210
Inline: False
```
**Symbols:**

```
c000000000bfa5c0-c000000000bfa6c4: dev_wait (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int dev_wait(struct file *filp, struct dm_ioctl *param, size_t param_size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/dm-ioctl.c (ffffffe0006f73f6)
Location: drivers/md/dm-ioctl.c:1210
Inline: False
```
**Symbols:**

```
ffffffe0006f73f6-ffffffe0006f7492: dev_wait (STB_LOCAL)
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
int dev_wait(struct file *filp, struct dm_ioctl *param, size_t param_size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/dm-ioctl.c (ffffffff81857b20)
Location: drivers/md/dm-ioctl.c:1210
Inline: False
```
**Symbols:**

```
ffffffff81857b20-ffffffff81857be3: dev_wait (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int dev_wait(struct file *filp, struct dm_ioctl *param, size_t param_size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/dm-ioctl.c (ffffffff8181f130)
Location: drivers/md/dm-ioctl.c:1210
Inline: False
```
**Symbols:**

```
ffffffff8181f130-ffffffff8181f1f3: dev_wait (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int dev_wait(struct file *filp, struct dm_ioctl *param, size_t param_size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/dm-ioctl.c (ffffffff818a7150)
Location: drivers/md/dm-ioctl.c:1210
Inline: False
```
**Symbols:**

```
ffffffff818a7150-ffffffff818a7213: dev_wait (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int dev_wait(struct file *filp, struct dm_ioctl *param, size_t param_size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/dm-ioctl.c (ffffffff818c3390)
Location: drivers/md/dm-ioctl.c:1210
Inline: False
```
**Symbols:**

```
ffffffff818c3390-ffffffff818c3453: dev_wait (STB_LOCAL)
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
<details>
<summary>Changed between <code>4.10</code> and <code>4.13</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>struct file *filp</code>
</li>
<li>
<b>Param reordered. </b>
<code>param, param_size</code> ➡️ <code>filp, param, param_size</code>
</li>
</ul>
</details>
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
