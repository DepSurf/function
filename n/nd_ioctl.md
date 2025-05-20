# Function: <code>nd_ioctl</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
long int nd_ioctl(struct file *file, unsigned int cmd, long unsigned int arg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/bus.c (ffffffff815983d0)
Location: drivers/nvdimm/bus.c:602
Inline: False
```
**Symbols:**

```
ffffffff815983d0-ffffffff81598481: nd_ioctl (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
long int nd_ioctl(struct file *file, unsigned int cmd, long unsigned int arg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/bus.c (ffffffff815ede80)
Location: drivers/nvdimm/bus.c:929
Inline: False
```
**Symbols:**

```
ffffffff815ede80-ffffffff815edf2e: nd_ioctl (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
long int nd_ioctl(struct file *file, unsigned int cmd, long unsigned int arg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/bus.c (ffffffff8161ac90)
Location: drivers/nvdimm/bus.c:946
Inline: False
```
**Symbols:**

```
ffffffff8161ac90-ffffffff8161ad3e: nd_ioctl (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
long int nd_ioctl(struct file *file, unsigned int cmd, long unsigned int arg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/bus.c (ffffffff8162eea0)
Location: drivers/nvdimm/bus.c:1064
Inline: False
```
**Symbols:**

```
ffffffff8162eea0-ffffffff8162ef4e: nd_ioctl (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
long int nd_ioctl(struct file *file, unsigned int cmd, long unsigned int arg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/bus.c (ffffffff81697610)
Location: drivers/nvdimm/bus.c:1060
Inline: False
```
**Symbols:**

```
ffffffff81697610-ffffffff816976be: nd_ioctl (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
long int nd_ioctl(struct file *file, unsigned int cmd, long unsigned int arg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/bus.c (ffffffff816d3760)
Location: drivers/nvdimm/bus.c:1067
Inline: False
```
**Symbols:**

```
ffffffff816d3760-ffffffff816d380e: nd_ioctl (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
long int nd_ioctl(struct file *file, unsigned int cmd, long unsigned int arg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/bus.c (ffffffff816f4e60)
Location: drivers/nvdimm/bus.c:1096
Inline: False
```
**Symbols:**

```
ffffffff816f4e60-ffffffff816f4f0e: nd_ioctl (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/nvdimm/bus.c (ffffffff8172e520)
Location: drivers/nvdimm/bus.c:1164
Inline: True
Direct callers:
  - drivers/nvdimm/bus.c:dimm_ioctl
  - drivers/nvdimm/bus.c:bus_ioctl
```
**Symbols:**

```
ffffffff8172e520-ffffffff8172e66f: nd_ioctl.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/nvdimm/bus.c (ffffffff817527c0)
Location: drivers/nvdimm/bus.c:1162
Inline: True
Direct callers:
  - drivers/nvdimm/bus.c:dimm_ioctl
  - drivers/nvdimm/bus.c:bus_ioctl
```
**Symbols:**

```
ffffffff817527c0-ffffffff8175290f: nd_ioctl.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
long int nd_ioctl(struct file *file, unsigned int cmd, long unsigned int arg, enum nd_ioctl_mode mode);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/bus.c (ffffffff81811200)
Location: drivers/nvdimm/bus.c:1212
Inline: False
Direct callers:
  - drivers/nvdimm/bus.c:dimm_ioctl
  - drivers/nvdimm/bus.c:bus_ioctl
```
**Symbols:**

```
ffffffff81811200-ffffffff81811357: nd_ioctl (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
long int nd_ioctl(struct file *file, unsigned int cmd, long unsigned int arg, enum nd_ioctl_mode mode);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/bus.c (ffffffff81820140)
Location: drivers/nvdimm/bus.c:1209
Inline: False
Direct callers:
  - drivers/nvdimm/bus.c:dimm_ioctl
  - drivers/nvdimm/bus.c:bus_ioctl
```
**Symbols:**

```
ffffffff81820140-ffffffff81820297: nd_ioctl (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
long int nd_ioctl(struct file *file, unsigned int cmd, long unsigned int arg, enum nd_ioctl_mode mode);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/bus.c (ffffffff81803420)
Location: drivers/nvdimm/bus.c:1204
Inline: False
Direct callers:
  - drivers/nvdimm/bus.c:dimm_ioctl
  - drivers/nvdimm/bus.c:bus_ioctl
```
**Symbols:**

```
ffffffff81803420-ffffffff81803577: nd_ioctl (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
long int nd_ioctl(struct file *file, unsigned int cmd, long unsigned int arg, enum nd_ioctl_mode mode);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/bus.c (ffffffff8188d9a0)
Location: drivers/nvdimm/bus.c:1221
Inline: False
Direct callers:
  - drivers/nvdimm/bus.c:dimm_ioctl
  - drivers/nvdimm/bus.c:bus_ioctl
```
**Symbols:**

```
ffffffff8188d9a0-ffffffff8188daf7: nd_ioctl (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
long int nd_ioctl(struct file *file, unsigned int cmd, long unsigned int arg, enum nd_ioctl_mode mode);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/bus.c (ffffffff819d6ec0)
Location: drivers/nvdimm/bus.c:1212
Inline: False
Direct callers:
  - drivers/nvdimm/bus.c:dimm_ioctl
  - drivers/nvdimm/bus.c:bus_ioctl
```
**Symbols:**

```
ffffffff819d6ec0-ffffffff819d703a: nd_ioctl (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
long int nd_ioctl(struct file *file, unsigned int cmd, long unsigned int arg, enum nd_ioctl_mode mode);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/bus.c (ffffffff81b51ba0)
Location: drivers/nvdimm/bus.c:1225
Inline: False
Direct callers:
  - drivers/nvdimm/bus.c:dimm_ioctl
  - drivers/nvdimm/bus.c:bus_ioctl
```
**Symbols:**

```
ffffffff81b51ba0-ffffffff81b51d1a: nd_ioctl (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
long int nd_ioctl(struct file *file, unsigned int cmd, long unsigned int arg, enum nd_ioctl_mode mode);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/bus.c (ffffffff81ba5080)
Location: drivers/nvdimm/bus.c:1225
Inline: False
Direct callers:
  - drivers/nvdimm/bus.c:dimm_ioctl
  - drivers/nvdimm/bus.c:bus_ioctl
```
**Symbols:**

```
ffffffff81ba5080-ffffffff81ba51fd: nd_ioctl (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
long int nd_ioctl(struct file *file, unsigned int cmd, long unsigned int arg, enum nd_ioctl_mode mode);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/bus.c (ffffffff81bf9300)
Location: drivers/nvdimm/bus.c:1225
Inline: False
Direct callers:
  - drivers/nvdimm/bus.c:dimm_ioctl
  - drivers/nvdimm/bus.c:bus_ioctl
```
**Symbols:**

```
ffffffff81bf9300-ffffffff81bf947d: nd_ioctl (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/nvdimm/bus.c (ffff800010952d68)
Location: drivers/nvdimm/bus.c:1162
Inline: True
Direct callers:
  - drivers/nvdimm/bus.c:dimm_ioctl
  - drivers/nvdimm/bus.c:bus_ioctl
```
**Symbols:**

```
ffff800010952d68-ffff800010952f0c: nd_ioctl.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
In <code>armhf</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
long int nd_ioctl(struct file *file, unsigned int cmd, long unsigned int arg, enum nd_ioctl_mode mode);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/bus.c (c0000000009ffe90)
Location: drivers/nvdimm/bus.c:1162
Inline: False
Direct callers:
  - drivers/nvdimm/bus.c:dimm_ioctl
  - drivers/nvdimm/bus.c:bus_ioctl
```
**Symbols:**

```
c0000000009ffe90-c000000000a000cc: nd_ioctl (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
long int nd_ioctl(struct file *file, unsigned int cmd, long unsigned int arg, enum nd_ioctl_mode mode);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/bus.c (ffffffe0005c2898)
Location: drivers/nvdimm/bus.c:1162
Inline: False
Direct callers:
  - drivers/nvdimm/bus.c:dimm_ioctl
  - drivers/nvdimm/bus.c:bus_ioctl
```
**Symbols:**

```
ffffffe0005c2898-ffffffe0005c29d4: nd_ioctl (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/nvdimm/bus.c (ffffffff81706eb0)
Location: drivers/nvdimm/bus.c:1162
Inline: True
Direct callers:
  - drivers/nvdimm/bus.c:dimm_ioctl
  - drivers/nvdimm/bus.c:bus_ioctl
```
**Symbols:**

```
ffffffff81706eb0-ffffffff81706fff: nd_ioctl.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/nvdimm/bus.c (ffffffff816da930)
Location: drivers/nvdimm/bus.c:1162
Inline: True
Direct callers:
  - drivers/nvdimm/bus.c:dimm_ioctl
  - drivers/nvdimm/bus.c:bus_ioctl
```
**Symbols:**

```
ffffffff816da930-ffffffff816daa7f: nd_ioctl.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/nvdimm/bus.c (ffffffff81745c80)
Location: drivers/nvdimm/bus.c:1162
Inline: True
Direct callers:
  - drivers/nvdimm/bus.c:dimm_ioctl
  - drivers/nvdimm/bus.c:bus_ioctl
```
**Symbols:**

```
ffffffff81745c80-ffffffff81745dcf: nd_ioctl.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/nvdimm/bus.c (ffffffff817610c0)
Location: drivers/nvdimm/bus.c:1162
Inline: True
Direct callers:
  - drivers/nvdimm/bus.c:dimm_ioctl
  - drivers/nvdimm/bus.c:bus_ioctl
```
**Symbols:**

```
ffffffff817610c0-ffffffff8176120f: nd_ioctl.isra.0 (STB_LOCAL)
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
</ul>
