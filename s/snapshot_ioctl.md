# Function: <code>snapshot_ioctl</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline ⚠️</summary>

```c
long int snapshot_ioctl(struct file *filp, unsigned int cmd, long unsigned int arg);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/power/user.c (ffffffff810d5960)
Location: kernel/power/user.c:197
Inline: True
Direct callers:
  - kernel/power/user.c:snapshot_compat_ioctl
  - kernel/power/user.c:snapshot_compat_ioctl
  - kernel/power/user.c:snapshot_compat_ioctl
  - kernel/power/user.c:snapshot_compat_ioctl
```
**Symbols:**

```
ffffffff810d5960-ffffffff810d5dc8: snapshot_ioctl (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
long int snapshot_ioctl(struct file *filp, unsigned int cmd, long unsigned int arg);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/power/user.c (ffffffff810da7e0)
Location: kernel/power/user.c:199
Inline: True
Direct callers:
  - kernel/power/user.c:snapshot_compat_ioctl
  - kernel/power/user.c:snapshot_compat_ioctl
  - kernel/power/user.c:snapshot_compat_ioctl
  - kernel/power/user.c:snapshot_compat_ioctl
```
**Symbols:**

```
ffffffff810da7e0-ffffffff810dac48: snapshot_ioctl (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
long int snapshot_ioctl(struct file *filp, unsigned int cmd, long unsigned int arg);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/power/user.c (ffffffff810e12b0)
Location: kernel/power/user.c:199
Inline: True
Direct callers:
  - kernel/power/user.c:snapshot_compat_ioctl
  - kernel/power/user.c:snapshot_compat_ioctl
  - kernel/power/user.c:snapshot_compat_ioctl
  - kernel/power/user.c:snapshot_compat_ioctl
```
**Symbols:**

```
ffffffff810e12b0-ffffffff810e1718: snapshot_ioctl (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
long int snapshot_ioctl(struct file *filp, unsigned int cmd, long unsigned int arg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/power/user.c (ffffffff810e01f0)
Location: kernel/power/user.c:202
Inline: False
Direct callers:
  - kernel/power/user.c:snapshot_compat_ioctl
  - kernel/power/user.c:snapshot_compat_ioctl
  - kernel/power/user.c:snapshot_compat_ioctl
  - kernel/power/user.c:snapshot_compat_ioctl
```
**Symbols:**

```
ffffffff810e01f0-ffffffff810e0652: snapshot_ioctl (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
long int snapshot_ioctl(struct file *filp, unsigned int cmd, long unsigned int arg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/power/user.c (ffffffff810e84a0)
Location: kernel/power/user.c:202
Inline: False
Direct callers:
  - kernel/power/user.c:snapshot_compat_ioctl
  - kernel/power/user.c:snapshot_compat_ioctl
  - kernel/power/user.c:snapshot_compat_ioctl
  - kernel/power/user.c:snapshot_compat_ioctl
```
**Symbols:**

```
ffffffff810e84a0-ffffffff810e8902: snapshot_ioctl (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Transformation ⚠️</summary>

```c
long int snapshot_ioctl(struct file *filp, unsigned int cmd, long unsigned int arg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/power/user.c (0)
Location: kernel/power/user.c:207
Inline: False
Direct callers:
  - kernel/power/user.c:snapshot_compat_ioctl
  - kernel/power/user.c:snapshot_compat_ioctl
  - kernel/power/user.c:snapshot_compat_ioctl
  - kernel/power/user.c:snapshot_compat_ioctl
```
**Symbols:**

```
ffffffff810f0810-ffffffff810f0c29: snapshot_ioctl (STB_LOCAL)
ffffffff810f0f2a-ffffffff810f0f7a: snapshot_ioctl.cold.1 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Transformation ⚠️</summary>

```c
long int snapshot_ioctl(struct file *filp, unsigned int cmd, long unsigned int arg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/power/user.c (0)
Location: kernel/power/user.c:207
Inline: False
Direct callers:
  - kernel/power/user.c:snapshot_compat_ioctl
  - kernel/power/user.c:snapshot_compat_ioctl
  - kernel/power/user.c:snapshot_compat_ioctl
  - kernel/power/user.c:snapshot_compat_ioctl
```
**Symbols:**

```
ffffffff810fbea0-ffffffff810fc2b9: snapshot_ioctl (STB_LOCAL)
ffffffff810fc5ba-ffffffff810fc60a: snapshot_ioctl.cold.2 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
long int snapshot_ioctl(struct file *filp, unsigned int cmd, long unsigned int arg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/power/user.c (ffffffff81104570)
Location: kernel/power/user.c:204
Inline: False
Direct callers:
  - kernel/power/user.c:snapshot_compat_ioctl
  - kernel/power/user.c:snapshot_compat_ioctl
  - kernel/power/user.c:snapshot_compat_ioctl
  - kernel/power/user.c:snapshot_compat_ioctl
```
**Symbols:**

```
ffffffff81104570-ffffffff811049c6: snapshot_ioctl (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
long int snapshot_ioctl(struct file *filp, unsigned int cmd, long unsigned int arg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/power/user.c (ffffffff81110920)
Location: kernel/power/user.c:201
Inline: False
Direct callers:
  - kernel/power/user.c:snapshot_compat_ioctl
  - kernel/power/user.c:snapshot_compat_ioctl
  - kernel/power/user.c:snapshot_compat_ioctl
  - kernel/power/user.c:snapshot_compat_ioctl
```
**Symbols:**

```
ffffffff81110920-ffffffff81110d76: snapshot_ioctl (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
long int snapshot_ioctl(struct file *filp, unsigned int cmd, long unsigned int arg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/power/user.c (ffffffff8111bb70)
Location: kernel/power/user.c:253
Inline: False
```
**Symbols:**

```
ffffffff8111bb70-ffffffff8111bf36: snapshot_ioctl (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
long int snapshot_ioctl(struct file *filp, unsigned int cmd, long unsigned int arg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/power/user.c (ffffffff811164d0)
Location: kernel/power/user.c:239
Inline: False
```
**Symbols:**

```
ffffffff811164d0-ffffffff81116896: snapshot_ioctl (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
long int snapshot_ioctl(struct file *filp, unsigned int cmd, long unsigned int arg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/power/user.c (ffffffff81116b60)
Location: kernel/power/user.c:239
Inline: False
```
**Symbols:**

```
ffffffff81116b60-ffffffff81116fc7: snapshot_ioctl (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
long int snapshot_ioctl(struct file *filp, unsigned int cmd, long unsigned int arg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/power/user.c (0)
Location: kernel/power/user.c:239
Inline: False
```
**Symbols:**

```
ffffffff81136f20-ffffffff81137416: snapshot_ioctl (STB_LOCAL)
ffffffff81cabe2d-ffffffff81cabf1d: snapshot_ioctl.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
long int snapshot_ioctl(struct file *filp, unsigned int cmd, long unsigned int arg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/power/user.c (0)
Location: kernel/power/user.c:245
Inline: False
```
**Symbols:**

```
ffffffff811593b0-ffffffff81159908: snapshot_ioctl (STB_LOCAL)
ffffffff81e5c267-ffffffff81e5c36d: snapshot_ioctl.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
long int snapshot_ioctl(struct file *filp, unsigned int cmd, long unsigned int arg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/power/user.c (0)
Location: kernel/power/user.c:249
Inline: False
```
**Symbols:**

```
ffffffff8118b5e0-ffffffff8118bb38: snapshot_ioctl (STB_LOCAL)
ffffffff82058725-ffffffff8205882b: snapshot_ioctl.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
long int snapshot_ioctl(struct file *filp, unsigned int cmd, long unsigned int arg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/power/user.c (0)
Location: kernel/power/user.c:249
Inline: False
```
**Symbols:**

```
ffffffff8119ccf0-ffffffff8119d253: snapshot_ioctl (STB_LOCAL)
ffffffff820d6f6a-ffffffff820d7070: snapshot_ioctl.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
long int snapshot_ioctl(struct file *filp, unsigned int cmd, long unsigned int arg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/power/user.c (0)
Location: kernel/power/user.c:249
Inline: False
```
**Symbols:**

```
ffffffff811abe40-ffffffff811ac3a3: snapshot_ioctl (STB_LOCAL)
ffffffff821b2201-ffffffff821b2307: snapshot_ioctl.cold (STB_LOCAL)
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
long int snapshot_ioctl(struct file *filp, unsigned int cmd, long unsigned int arg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/power/user.c (c03c36dc)
Location: kernel/power/user.c:201
Inline: False
```
**Symbols:**

```
c03c36dc-c03c3c3c: snapshot_ioctl (STB_LOCAL)
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
<summary>In <code>aws</code>: ✅</summary>

```c
long int snapshot_ioctl(struct file *filp, unsigned int cmd, long unsigned int arg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/power/user.c (ffffffff81108ef0)
Location: kernel/power/user.c:201
Inline: False
Direct callers:
  - kernel/power/user.c:snapshot_compat_ioctl
  - kernel/power/user.c:snapshot_compat_ioctl
  - kernel/power/user.c:snapshot_compat_ioctl
  - kernel/power/user.c:snapshot_compat_ioctl
```
**Symbols:**

```
ffffffff81108ef0-ffffffff81109356: snapshot_ioctl (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
long int snapshot_ioctl(struct file *filp, unsigned int cmd, long unsigned int arg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/power/user.c (ffffffff810f9de0)
Location: kernel/power/user.c:201
Inline: False
Direct callers:
  - kernel/power/user.c:snapshot_compat_ioctl
  - kernel/power/user.c:snapshot_compat_ioctl
  - kernel/power/user.c:snapshot_compat_ioctl
  - kernel/power/user.c:snapshot_compat_ioctl
```
**Symbols:**

```
ffffffff810f9de0-ffffffff810fa236: snapshot_ioctl (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
long int snapshot_ioctl(struct file *filp, unsigned int cmd, long unsigned int arg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/power/user.c (ffffffff81106df0)
Location: kernel/power/user.c:201
Inline: False
Direct callers:
  - kernel/power/user.c:snapshot_compat_ioctl
  - kernel/power/user.c:snapshot_compat_ioctl
  - kernel/power/user.c:snapshot_compat_ioctl
  - kernel/power/user.c:snapshot_compat_ioctl
```
**Symbols:**

```
ffffffff81106df0-ffffffff81107246: snapshot_ioctl (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
long int snapshot_ioctl(struct file *filp, unsigned int cmd, long unsigned int arg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/power/user.c (ffffffff811121b0)
Location: kernel/power/user.c:201
Inline: False
Direct callers:
  - kernel/power/user.c:snapshot_compat_ioctl
  - kernel/power/user.c:snapshot_compat_ioctl
  - kernel/power/user.c:snapshot_compat_ioctl
  - kernel/power/user.c:snapshot_compat_ioctl
```
**Symbols:**

```
ffffffff811121b0-ffffffff81112606: snapshot_ioctl (STB_LOCAL)
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
