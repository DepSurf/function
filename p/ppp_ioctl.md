# Function: <code>ppp_ioctl</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
long int ppp_ioctl(struct file *file, unsigned int cmd, long unsigned int arg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/net/ppp/ppp_generic.c (ffffffff815f8190)
Location: drivers/net/ppp/ppp_generic.c:568
Inline: False
```
**Symbols:**

```
ffffffff815f8190-ffffffff815f8f2d: ppp_ioctl (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
long int ppp_ioctl(struct file *file, unsigned int cmd, long unsigned int arg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/net/ppp/ppp_generic.c (ffffffff81658380)
Location: drivers/net/ppp/ppp_generic.c:583
Inline: False
```
**Symbols:**

```
ffffffff81658380-ffffffff81658e7f: ppp_ioctl (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
long int ppp_ioctl(struct file *file, unsigned int cmd, long unsigned int arg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/net/ppp/ppp_generic.c (ffffffff81686110)
Location: drivers/net/ppp/ppp_generic.c:583
Inline: False
```
**Symbols:**

```
ffffffff81686110-ffffffff81686c01: ppp_ioctl (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
long int ppp_ioctl(struct file *file, unsigned int cmd, long unsigned int arg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/net/ppp/ppp_generic.c (ffffffff8169b540)
Location: drivers/net/ppp/ppp_generic.c:585
Inline: False
```
**Symbols:**

```
ffffffff8169b540-ffffffff8169bfad: ppp_ioctl (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
long int ppp_ioctl(struct file *file, unsigned int cmd, long unsigned int arg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/net/ppp/ppp_generic.c (ffffffff81706520)
Location: drivers/net/ppp/ppp_generic.c:585
Inline: False
```
**Symbols:**

```
ffffffff81706520-ffffffff81706ff5: ppp_ioctl (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Transformation ⚠️</summary>

```c
long int ppp_ioctl(struct file *file, unsigned int cmd, long unsigned int arg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/net/ppp/ppp_generic.c (0)
Location: drivers/net/ppp/ppp_generic.c:585
Inline: False
```
**Symbols:**

```
ffffffff817451d0-ffffffff81745c97: ppp_ioctl (STB_LOCAL)
ffffffff81745cab-ffffffff81745cf8: ppp_ioctl.cold.35 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Transformation ⚠️</summary>

```c
long int ppp_ioctl(struct file *file, unsigned int cmd, long unsigned int arg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/net/ppp/ppp_generic.c (0)
Location: drivers/net/ppp/ppp_generic.c:585
Inline: False
```
**Symbols:**

```
ffffffff817692c0-ffffffff81769d87: ppp_ioctl (STB_LOCAL)
ffffffff81769d9b-ffffffff81769de8: ppp_ioctl.cold.36 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
long int ppp_ioctl(struct file *file, unsigned int cmd, long unsigned int arg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/net/ppp/ppp_generic.c (0)
Location: drivers/net/ppp/ppp_generic.c:581
Inline: False
```
**Symbols:**

```
ffffffff817a6d80-ffffffff817a7839: ppp_ioctl (STB_LOCAL)
ffffffff817a7b43-ffffffff817a7b90: ppp_ioctl.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
long int ppp_ioctl(struct file *file, unsigned int cmd, long unsigned int arg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/net/ppp/ppp_generic.c (0)
Location: drivers/net/ppp/ppp_generic.c:581
Inline: False
```
**Symbols:**

```
ffffffff817ca7f0-ffffffff817cb2a9: ppp_ioctl (STB_LOCAL)
ffffffff817cb5b3-ffffffff817cb600: ppp_ioctl.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
long int ppp_ioctl(struct file *file, unsigned int cmd, long unsigned int arg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/net/ppp/ppp_generic.c (0)
Location: drivers/net/ppp/ppp_generic.c:609
Inline: False
Direct callers:
  - drivers/net/ppp/ppp_generic.c:ppp_compat_ioctl
```
**Symbols:**

```
ffffffff81893fa0-ffffffff818946ab: ppp_ioctl (STB_LOCAL)
ffffffff81895ac1-ffffffff81895b0e: ppp_ioctl.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
long int ppp_ioctl(struct file *file, unsigned int cmd, long unsigned int arg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/net/ppp/ppp_generic.c (0)
Location: drivers/net/ppp/ppp_generic.c:693
Inline: False
Direct callers:
  - drivers/net/ppp/ppp_generic.c:ppp_compat_ioctl
```
**Symbols:**

```
ffffffff818a2590-ffffffff818a2dd9: ppp_ioctl (STB_LOCAL)
ffffffff81c19b96-ffffffff81c19be3: ppp_ioctl.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
long int ppp_ioctl(struct file *file, unsigned int cmd, long unsigned int arg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/net/ppp/ppp_generic.c (0)
Location: drivers/net/ppp/ppp_generic.c:693
Inline: False
Direct callers:
  - drivers/net/ppp/ppp_generic.c:ppp_compat_ioctl
```
**Symbols:**

```
ffffffff81885c80-ffffffff818867f8: ppp_ioctl (STB_LOCAL)
ffffffff81c0ba6f-ffffffff81c0babc: ppp_ioctl.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
long int ppp_ioctl(struct file *file, unsigned int cmd, long unsigned int arg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/net/ppp/ppp_generic.c (0)
Location: drivers/net/ppp/ppp_generic.c:698
Inline: False
Direct callers:
  - drivers/net/ppp/ppp_generic.c:ppp_compat_ioctl
```
**Symbols:**

```
ffffffff81917670-ffffffff819181ed: ppp_ioctl (STB_LOCAL)
ffffffff81d110d0-ffffffff81d11132: ppp_ioctl.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
long int ppp_ioctl(struct file *file, unsigned int cmd, long unsigned int arg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/net/ppp/ppp_generic.c (0)
Location: drivers/net/ppp/ppp_generic.c:699
Inline: False
Direct callers:
  - drivers/net/ppp/ppp_generic.c:ppp_compat_ioctl
```
**Symbols:**

```
ffffffff81a6c500-ffffffff81a6d08e: ppp_ioctl (STB_LOCAL)
ffffffff81edbdf7-ffffffff81edbe1c: ppp_ioctl.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
long int ppp_ioctl(struct file *file, unsigned int cmd, long unsigned int arg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/net/ppp/ppp_generic.c (0)
Location: drivers/net/ppp/ppp_generic.c:699
Inline: False
Direct callers:
  - drivers/net/ppp/ppp_generic.c:ppp_compat_ioctl
```
**Symbols:**

```
ffffffff81bff470-ffffffff81bffffb: ppp_ioctl (STB_LOCAL)
ffffffff8209dac3-ffffffff8209dad7: ppp_ioctl.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
long int ppp_ioctl(struct file *file, unsigned int cmd, long unsigned int arg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/net/ppp/ppp_generic.c (0)
Location: drivers/net/ppp/ppp_generic.c:699
Inline: False
Direct callers:
  - drivers/net/ppp/ppp_generic.c:ppp_compat_ioctl
```
**Symbols:**

```
ffffffff81c64ac0-ffffffff81c65650: ppp_ioctl (STB_LOCAL)
ffffffff8211f04b-ffffffff8211f05f: ppp_ioctl.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
long int ppp_ioctl(struct file *file, unsigned int cmd, long unsigned int arg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/net/ppp/ppp_generic.c (0)
Location: drivers/net/ppp/ppp_generic.c:699
Inline: False
Direct callers:
  - drivers/net/ppp/ppp_generic.c:ppp_compat_ioctl
```
**Symbols:**

```
ffffffff81d1b4e0-ffffffff81d1c071: ppp_ioctl (STB_LOCAL)
ffffffff82200821-ffffffff82200835: ppp_ioctl.cold (STB_LOCAL)
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
long int ppp_ioctl(struct file *file, unsigned int cmd, long unsigned int arg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/net/ppp/ppp_generic.c (ffff800010a03d00)
Location: drivers/net/ppp/ppp_generic.c:581
Inline: False
```
**Symbols:**

```
ffff800010a03d00-ffff800010a04cb0: ppp_ioctl (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
long int ppp_ioctl(struct file *file, unsigned int cmd, long unsigned int arg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/net/ppp/ppp_generic.c (c0adf9a4)
Location: drivers/net/ppp/ppp_generic.c:581
Inline: False
```
**Symbols:**

```
c0adf9a4-c0ae068c: ppp_ioctl (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
long int ppp_ioctl(struct file *file, unsigned int cmd, long unsigned int arg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/net/ppp/ppp_generic.c (c000000000aab540)
Location: drivers/net/ppp/ppp_generic.c:581
Inline: False
```
**Symbols:**

```
c000000000aab540-c000000000aac350: ppp_ioctl (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
long int ppp_ioctl(struct file *file, unsigned int cmd, long unsigned int arg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/net/ppp/ppp_generic.c (ffffffe00062f160)
Location: drivers/net/ppp/ppp_generic.c:581
Inline: False
```
**Symbols:**

```
ffffffe00062f160-ffffffe00062f90c: ppp_ioctl (STB_LOCAL)
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
long int ppp_ioctl(struct file *file, unsigned int cmd, long unsigned int arg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/net/ppp/ppp_generic.c (0)
Location: drivers/net/ppp/ppp_generic.c:581
Inline: False
```
**Symbols:**

```
ffffffff8178f2d0-ffffffff8178fd89: ppp_ioctl (STB_LOCAL)
ffffffff81790093-ffffffff817900e0: ppp_ioctl.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Transformation ⚠️</summary>

```c
long int ppp_ioctl(struct file *file, unsigned int cmd, long unsigned int arg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/net/ppp/ppp_generic.c (0)
Location: drivers/net/ppp/ppp_generic.c:581
Inline: False
```
**Symbols:**

```
ffffffff817780a0-ffffffff81778b59: ppp_ioctl (STB_LOCAL)
ffffffff81778e63-ffffffff81778eb0: ppp_ioctl.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Transformation ⚠️</summary>

```c
long int ppp_ioctl(struct file *file, unsigned int cmd, long unsigned int arg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/net/ppp/ppp_generic.c (0)
Location: drivers/net/ppp/ppp_generic.c:581
Inline: False
```
**Symbols:**

```
ffffffff817bf670-ffffffff817c0129: ppp_ioctl (STB_LOCAL)
ffffffff817c0433-ffffffff817c0480: ppp_ioctl.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
long int ppp_ioctl(struct file *file, unsigned int cmd, long unsigned int arg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/net/ppp/ppp_generic.c (0)
Location: drivers/net/ppp/ppp_generic.c:581
Inline: False
```
**Symbols:**

```
ffffffff817d9900-ffffffff817da3dc: ppp_ioctl (STB_LOCAL)
ffffffff817da6e6-ffffffff817da733: ppp_ioctl.cold (STB_LOCAL)
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
