# Function: <code>cec_ioctl</code>

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
<summary>In <code>5.0</code>: Transformation ⚠️</summary>

```c
long int cec_ioctl(struct file *filp, unsigned int cmd, long unsigned int arg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/media/cec/cec-api.c (0)
Location: drivers/media/cec/cec-api.c:491
Inline: False
```
**Symbols:**

```
ffffffff81807ae0-ffffffff81808820: cec_ioctl (STB_LOCAL)
ffffffff81808a5d-ffffffff81808b59: cec_ioctl.cold.9 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
long int cec_ioctl(struct file *filp, unsigned int cmd, long unsigned int arg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/media/cec/cec-api.c (0)
Location: drivers/media/cec/cec-api.c:483
Inline: False
```
**Symbols:**

```
ffffffff81849420-ffffffff8184a127: cec_ioctl (STB_LOCAL)
ffffffff8184a389-ffffffff8184a485: cec_ioctl.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
long int cec_ioctl(struct file *filp, unsigned int cmd, long unsigned int arg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/media/cec/cec-api.c (0)
Location: drivers/media/cec/cec-api.c:483
Inline: False
```
**Symbols:**

```
ffffffff8187ac20-ffffffff8187b927: cec_ioctl (STB_LOCAL)
ffffffff8187bb76-ffffffff8187bc72: cec_ioctl.cold (STB_LOCAL)
```
</details>
</li>
<li>
In <code>5.8</code>: Absent ⚠️
</li>
<li>
In <code>5.11</code>: Absent ⚠️
</li>
<li>
In <code>5.13</code>: Absent ⚠️
</li>
<li>
In <code>5.15</code>: Absent ⚠️
</li>
<li>
In <code>5.19</code>: Absent ⚠️
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
long int cec_ioctl(struct file *filp, unsigned int cmd, long unsigned int arg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/media/cec/cec-api.c (ffff800010ac2870)
Location: drivers/media/cec/cec-api.c:483
Inline: False
```
**Symbols:**

```
ffff800010ac2870-ffff800010ac3540: cec_ioctl (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
long int cec_ioctl(struct file *filp, unsigned int cmd, long unsigned int arg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/media/cec/cec-api.c (c0ba4058)
Location: drivers/media/cec/cec-api.c:483
Inline: False
```
**Symbols:**

```
c0ba4058-c0ba5070: cec_ioctl (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
long int cec_ioctl(struct file *filp, unsigned int cmd, long unsigned int arg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/media/cec/cec-api.c (c000000000ba4d90)
Location: drivers/media/cec/cec-api.c:483
Inline: False
```
**Symbols:**

```
c000000000ba4d90-c000000000ba5bd0: cec_ioctl (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
long int cec_ioctl(struct file *filp, unsigned int cmd, long unsigned int arg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/media/cec/cec-api.c (ffffffe0006c35a2)
Location: drivers/media/cec/cec-api.c:483
Inline: False
```
**Symbols:**

```
ffffffe0006c35a2-ffffffe0006c3f7a: cec_ioctl (STB_LOCAL)
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
long int cec_ioctl(struct file *filp, unsigned int cmd, long unsigned int arg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/media/cec/cec-api.c (0)
Location: drivers/media/cec/cec-api.c:483
Inline: False
```
**Symbols:**

```
ffffffff81823190-ffffffff81823e97: cec_ioctl (STB_LOCAL)
ffffffff818240e6-ffffffff818241e2: cec_ioctl.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Transformation ⚠️</summary>

```c
long int cec_ioctl(struct file *filp, unsigned int cmd, long unsigned int arg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/media/cec/cec-api.c (0)
Location: drivers/media/cec/cec-api.c:483
Inline: False
```
**Symbols:**

```
ffffffff817ea830-ffffffff817eb537: cec_ioctl (STB_LOCAL)
ffffffff817eb786-ffffffff817eb882: cec_ioctl.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Transformation ⚠️</summary>

```c
long int cec_ioctl(struct file *filp, unsigned int cmd, long unsigned int arg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/media/cec/cec-api.c (0)
Location: drivers/media/cec/cec-api.c:483
Inline: False
```
**Symbols:**

```
ffffffff818700d0-ffffffff81870dd7: cec_ioctl (STB_LOCAL)
ffffffff81871026-ffffffff81871122: cec_ioctl.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
long int cec_ioctl(struct file *filp, unsigned int cmd, long unsigned int arg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/media/cec/cec-api.c (0)
Location: drivers/media/cec/cec-api.c:483
Inline: False
```
**Symbols:**

```
ffffffff8188a040-ffffffff8188ad3f: cec_ioctl (STB_LOCAL)
ffffffff8188aff0-ffffffff8188b0ec: cec_ioctl.cold (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>5.0</code> and <code>5.3</code> ✅
</li>
<li>
No changes between <code>5.3</code> and <code>5.4</code> ✅
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
