# Function: <code>pps_cdev_ioctl</code>

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
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
long int pps_cdev_ioctl(struct file *file, unsigned int cmd, long unsigned int arg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pps/pps.c (ffffffff817dde10)
Location: drivers/pps/pps.c:104
Inline: False
Direct callers:
  - drivers/pps/pps.c:pps_cdev_compat_ioctl
```
**Symbols:**

```
ffffffff817dde10-ffffffff817de267: pps_cdev_ioctl (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
long int pps_cdev_ioctl(struct file *file, unsigned int cmd, long unsigned int arg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pps/pps.c (ffffffff81809230)
Location: drivers/pps/pps.c:104
Inline: False
Direct callers:
  - drivers/pps/pps.c:pps_cdev_compat_ioctl
```
**Symbols:**

```
ffffffff81809230-ffffffff81809687: pps_cdev_ioctl (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
long int pps_cdev_ioctl(struct file *file, unsigned int cmd, long unsigned int arg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pps/pps.c (0)
Location: drivers/pps/pps.c:90
Inline: False
Direct callers:
  - drivers/pps/pps.c:pps_cdev_compat_ioctl
```
**Symbols:**

```
ffffffff8184aed0-ffffffff8184b30d: pps_cdev_ioctl (STB_LOCAL)
ffffffff8184b664-ffffffff8184b6a2: pps_cdev_ioctl.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
long int pps_cdev_ioctl(struct file *file, unsigned int cmd, long unsigned int arg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pps/pps.c (0)
Location: drivers/pps/pps.c:90
Inline: False
Direct callers:
  - drivers/pps/pps.c:pps_cdev_compat_ioctl
```
**Symbols:**

```
ffffffff8187c6e0-ffffffff8187cb1d: pps_cdev_ioctl (STB_LOCAL)
ffffffff8187ce74-ffffffff8187ceb2: pps_cdev_ioctl.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
long int pps_cdev_ioctl(struct file *file, unsigned int cmd, long unsigned int arg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pps/pps.c (0)
Location: drivers/pps/pps.c:90
Inline: False
Direct callers:
  - drivers/pps/pps.c:pps_cdev_compat_ioctl
```
**Symbols:**

```
ffffffff8194aaa0-ffffffff8194aedd: pps_cdev_ioctl (STB_LOCAL)
ffffffff8194b237-ffffffff8194b275: pps_cdev_ioctl.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
long int pps_cdev_ioctl(struct file *file, unsigned int cmd, long unsigned int arg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pps/pps.c (0)
Location: drivers/pps/pps.c:90
Inline: False
Direct callers:
  - drivers/pps/pps.c:pps_cdev_compat_ioctl
```
**Symbols:**

```
ffffffff81950600-ffffffff81950a3d: pps_cdev_ioctl (STB_LOCAL)
ffffffff81c2516d-ffffffff81c251ab: pps_cdev_ioctl.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
long int pps_cdev_ioctl(struct file *file, unsigned int cmd, long unsigned int arg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pps/pps.c (0)
Location: drivers/pps/pps.c:90
Inline: False
Direct callers:
  - drivers/pps/pps.c:pps_cdev_compat_ioctl
```
**Symbols:**

```
ffffffff81934480-ffffffff819348bd: pps_cdev_ioctl (STB_LOCAL)
ffffffff81c1720f-ffffffff81c1724d: pps_cdev_ioctl.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
long int pps_cdev_ioctl(struct file *file, unsigned int cmd, long unsigned int arg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pps/pps.c (0)
Location: drivers/pps/pps.c:90
Inline: False
Direct callers:
  - drivers/pps/pps.c:pps_cdev_compat_ioctl
```
**Symbols:**

```
ffffffff819d78a0-ffffffff819d7cd4: pps_cdev_ioctl (STB_LOCAL)
ffffffff81d25f21-ffffffff81d25f5f: pps_cdev_ioctl.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
long int pps_cdev_ioctl(struct file *file, unsigned int cmd, long unsigned int arg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pps/pps.c (0)
Location: drivers/pps/pps.c:90
Inline: False
Direct callers:
  - drivers/pps/pps.c:pps_cdev_compat_ioctl
```
**Symbols:**

```
ffffffff81b3ab30-ffffffff81b3afae: pps_cdev_ioctl (STB_LOCAL)
ffffffff81ef1d4c-ffffffff81ef1d80: pps_cdev_ioctl.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
long int pps_cdev_ioctl(struct file *file, unsigned int cmd, long unsigned int arg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pps/pps.c (ffffffff81cd0780)
Location: drivers/pps/pps.c:90
Inline: False
Direct callers:
  - drivers/pps/pps.c:pps_cdev_compat_ioctl
```
**Symbols:**

```
ffffffff81cd0780-ffffffff81cd0c3a: pps_cdev_ioctl (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
long int pps_cdev_ioctl(struct file *file, unsigned int cmd, long unsigned int arg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pps/pps.c (ffffffff81d381c0)
Location: drivers/pps/pps.c:90
Inline: False
Direct callers:
  - drivers/pps/pps.c:pps_cdev_compat_ioctl
```
**Symbols:**

```
ffffffff81d381c0-ffffffff81d3866f: pps_cdev_ioctl (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
long int pps_cdev_ioctl(struct file *file, unsigned int cmd, long unsigned int arg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pps/pps.c (ffffffff81dee440)
Location: drivers/pps/pps.c:90
Inline: False
Direct callers:
  - drivers/pps/pps.c:pps_cdev_compat_ioctl
```
**Symbols:**

```
ffffffff81dee440-ffffffff81dee8ef: pps_cdev_ioctl (STB_LOCAL)
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
long int pps_cdev_ioctl(struct file *file, unsigned int cmd, long unsigned int arg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pps/pps.c (ffff800010ac5ba0)
Location: drivers/pps/pps.c:90
Inline: False
Direct callers:
  - drivers/pps/pps.c:pps_cdev_compat_ioctl
```
**Symbols:**

```
ffff800010ac5ba0-ffff800010ac61e0: pps_cdev_ioctl (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
long int pps_cdev_ioctl(struct file *file, unsigned int cmd, long unsigned int arg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pps/pps.c (c0ba57dc)
Location: drivers/pps/pps.c:90
Inline: False
```
**Symbols:**

```
c0ba57dc-c0ba5fd0: pps_cdev_ioctl (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
long int pps_cdev_ioctl(struct file *file, unsigned int cmd, long unsigned int arg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pps/pps.c (c000000000ba6f90)
Location: drivers/pps/pps.c:90
Inline: False
Direct callers:
  - drivers/pps/pps.c:pps_cdev_compat_ioctl
```
**Symbols:**

```
c000000000ba6f90-c000000000ba7640: pps_cdev_ioctl (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
long int pps_cdev_ioctl(struct file *file, unsigned int cmd, long unsigned int arg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pps/pps.c (ffffffe0006c4aba)
Location: drivers/pps/pps.c:90
Inline: False
```
**Symbols:**

```
ffffffe0006c4aba-ffffffe0006c4fa0: pps_cdev_ioctl (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Transformation ⚠️</summary>

```c
long int pps_cdev_ioctl(struct file *file, unsigned int cmd, long unsigned int arg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pps/pps.c (0)
Location: drivers/pps/pps.c:90
Inline: False
Direct callers:
  - drivers/pps/pps.c:pps_cdev_compat_ioctl
```
**Symbols:**

```
ffffffff81824c50-ffffffff8182508d: pps_cdev_ioctl (STB_LOCAL)
ffffffff818253e4-ffffffff81825422: pps_cdev_ioctl.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Transformation ⚠️</summary>

```c
long int pps_cdev_ioctl(struct file *file, unsigned int cmd, long unsigned int arg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pps/pps.c (0)
Location: drivers/pps/pps.c:90
Inline: False
Direct callers:
  - drivers/pps/pps.c:pps_cdev_compat_ioctl
```
**Symbols:**

```
ffffffff817ec2f0-ffffffff817ec71b: pps_cdev_ioctl (STB_LOCAL)
ffffffff817eca74-ffffffff817ecab2: pps_cdev_ioctl.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Transformation ⚠️</summary>

```c
long int pps_cdev_ioctl(struct file *file, unsigned int cmd, long unsigned int arg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pps/pps.c (0)
Location: drivers/pps/pps.c:90
Inline: False
Direct callers:
  - drivers/pps/pps.c:pps_cdev_compat_ioctl
```
**Symbols:**

```
ffffffff81871b90-ffffffff81871fcd: pps_cdev_ioctl (STB_LOCAL)
ffffffff81872324-ffffffff81872362: pps_cdev_ioctl.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
long int pps_cdev_ioctl(struct file *file, unsigned int cmd, long unsigned int arg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pps/pps.c (0)
Location: drivers/pps/pps.c:90
Inline: False
Direct callers:
  - drivers/pps/pps.c:pps_cdev_compat_ioctl
```
**Symbols:**

```
ffffffff8188d4d0-ffffffff8188d8f2: pps_cdev_ioctl (STB_LOCAL)
ffffffff8188dcd4-ffffffff8188dd12: pps_cdev_ioctl.cold (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
