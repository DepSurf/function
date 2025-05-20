# Function: <code>devfreq_set_target</code>

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
<summary>In <code>5.0</code>: ✅</summary>

```c
int devfreq_set_target(struct devfreq *devfreq, long unsigned int new_freq, u32 flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/devfreq/devfreq.c (ffffffff8187b520)
Location: drivers/devfreq/devfreq.c:288
Inline: False
```
**Symbols:**

```
ffffffff8187b520-ffffffff8187b6a9: devfreq_set_target (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
int devfreq_set_target(struct devfreq *devfreq, long unsigned int new_freq, u32 flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/devfreq/devfreq.c (0)
Location: drivers/devfreq/devfreq.c:288
Inline: False
```
**Symbols:**

```
ffffffff818c5680-ffffffff818c57ef: devfreq_set_target (STB_LOCAL)
ffffffff818c79a1-ffffffff818c79b6: devfreq_set_target.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
int devfreq_set_target(struct devfreq *devfreq, long unsigned int new_freq, u32 flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/devfreq/devfreq.c (0)
Location: drivers/devfreq/devfreq.c:289
Inline: False
Direct callers:
  - drivers/devfreq/devfreq.c:update_devfreq
```
**Symbols:**

```
ffffffff818f7b60-ffffffff818f7ccf: devfreq_set_target (STB_LOCAL)
ffffffff818f9e81-ffffffff818f9e96: devfreq_set_target.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
int devfreq_set_target(struct devfreq *devfreq, long unsigned int new_freq, u32 flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/devfreq/devfreq.c (0)
Location: drivers/devfreq/devfreq.c:342
Inline: False
Direct callers:
  - drivers/devfreq/devfreq.c:update_devfreq
```
**Symbols:**

```
ffffffff819cf740-ffffffff819cf8ad: devfreq_set_target (STB_LOCAL)
ffffffff819d0b4a-ffffffff819d0b5f: devfreq_set_target.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
int devfreq_set_target(struct devfreq *devfreq, long unsigned int new_freq, u32 flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/devfreq/devfreq.c (0)
Location: drivers/devfreq/devfreq.c:349
Inline: False
Direct callers:
  - drivers/devfreq/devfreq.c:devfreq_update_target
```
**Symbols:**

```
ffffffff819cf3d0-ffffffff819cf5a2: devfreq_set_target (STB_LOCAL)
ffffffff81c2f469-ffffffff81c2f47e: devfreq_set_target.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
int devfreq_set_target(struct devfreq *devfreq, long unsigned int new_freq, u32 flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/devfreq/devfreq.c (0)
Location: drivers/devfreq/devfreq.c:350
Inline: False
Direct callers:
  - drivers/devfreq/devfreq.c:devfreq_update_target
```
**Symbols:**

```
ffffffff819b4510-ffffffff819b46da: devfreq_set_target (STB_LOCAL)
ffffffff81c2172e-ffffffff81c21743: devfreq_set_target.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int devfreq_set_target(struct devfreq *devfreq, long unsigned int new_freq, u32 flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/devfreq/devfreq.c (0)
Location: drivers/devfreq/devfreq.c:350
Inline: False
Direct callers:
  - drivers/devfreq/devfreq.c:devfreq_update_target
```
**Symbols:**

```
ffffffff81a63060-ffffffff81a63217: devfreq_set_target (STB_LOCAL)
ffffffff81d33297-ffffffff81d332ac: devfreq_set_target.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int devfreq_set_target(struct devfreq *devfreq, long unsigned int new_freq, u32 flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/devfreq/devfreq.c (0)
Location: drivers/devfreq/devfreq.c:347
Inline: False
Direct callers:
  - drivers/devfreq/devfreq.c:devfreq_resume_device
  - drivers/devfreq/devfreq.c:devfreq_suspend_device
  - drivers/devfreq/devfreq.c:devfreq_update_target
```
**Symbols:**

```
ffffffff81bd1f20-ffffffff81bd210e: devfreq_set_target (STB_LOCAL)
ffffffff81eff35f-ffffffff81eff374: devfreq_set_target.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int devfreq_set_target(struct devfreq *devfreq, long unsigned int new_freq, u32 flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/devfreq/devfreq.c (ffffffff81d7db20)
Location: drivers/devfreq/devfreq.c:347
Inline: False
Direct callers:
  - drivers/devfreq/devfreq.c:devfreq_resume_device
  - drivers/devfreq/devfreq.c:devfreq_suspend_device
  - drivers/devfreq/devfreq.c:devfreq_update_target
```
**Symbols:**

```
ffffffff81d7db20-ffffffff81d7dd3f: devfreq_set_target (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int devfreq_set_target(struct devfreq *devfreq, long unsigned int new_freq, u32 flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/devfreq/devfreq.c (ffffffff81debea0)
Location: drivers/devfreq/devfreq.c:347
Inline: False
Direct callers:
  - drivers/devfreq/devfreq.c:devfreq_resume_device
  - drivers/devfreq/devfreq.c:devfreq_suspend_device
  - drivers/devfreq/devfreq.c:devfreq_update_target
```
**Symbols:**

```
ffffffff81debea0-ffffffff81dec0bf: devfreq_set_target (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int devfreq_set_target(struct devfreq *devfreq, long unsigned int new_freq, u32 flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/devfreq/devfreq.c (ffffffff81ea2290)
Location: drivers/devfreq/devfreq.c:347
Inline: False
Direct callers:
  - drivers/devfreq/devfreq.c:devfreq_resume_device
  - drivers/devfreq/devfreq.c:devfreq_suspend_device
  - drivers/devfreq/devfreq.c:devfreq_update_target
```
**Symbols:**

```
ffffffff81ea2290-ffffffff81ea24af: devfreq_set_target (STB_LOCAL)
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
int devfreq_set_target(struct devfreq *devfreq, long unsigned int new_freq, u32 flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/devfreq/devfreq.c (ffff800010b83ef8)
Location: drivers/devfreq/devfreq.c:289
Inline: False
Direct callers:
  - drivers/devfreq/devfreq.c:update_devfreq
```
**Symbols:**

```
ffff800010b83ef8-ffff800010b84064: devfreq_set_target (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int devfreq_set_target(struct devfreq *devfreq, long unsigned int new_freq, u32 flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/devfreq/devfreq.c (c0c67284)
Location: drivers/devfreq/devfreq.c:289
Inline: False
Direct callers:
  - drivers/devfreq/devfreq.c:update_devfreq
```
**Symbols:**

```
c0c67284-c0c67400: devfreq_set_target (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int devfreq_set_target(struct devfreq *devfreq, long unsigned int new_freq, u32 flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/devfreq/devfreq.c (c000000000c61800)
Location: drivers/devfreq/devfreq.c:289
Inline: False
Direct callers:
  - drivers/devfreq/devfreq.c:update_devfreq
```
**Symbols:**

```
c000000000c61800-c000000000c619e4: devfreq_set_target (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int devfreq_set_target(struct devfreq *devfreq, long unsigned int new_freq, u32 flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/devfreq/devfreq.c (ffffffe00072d64a)
Location: drivers/devfreq/devfreq.c:289
Inline: False
Direct callers:
  - drivers/devfreq/devfreq.c:update_devfreq
```
**Symbols:**

```
ffffffe00072d64a-ffffffe00072d766: devfreq_set_target (STB_LOCAL)
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
int devfreq_set_target(struct devfreq *devfreq, long unsigned int new_freq, u32 flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/devfreq/devfreq.c (0)
Location: drivers/devfreq/devfreq.c:289
Inline: False
Direct callers:
  - drivers/devfreq/devfreq.c:update_devfreq
```
**Symbols:**

```
ffffffff81898e90-ffffffff81898fff: devfreq_set_target (STB_LOCAL)
ffffffff8189b1b1-ffffffff8189b1c6: devfreq_set_target.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Transformation ⚠️</summary>

```c
int devfreq_set_target(struct devfreq *devfreq, long unsigned int new_freq, u32 flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/devfreq/devfreq.c (0)
Location: drivers/devfreq/devfreq.c:289
Inline: False
Direct callers:
  - drivers/devfreq/devfreq.c:update_devfreq
```
**Symbols:**

```
ffffffff81856360-ffffffff818564cf: devfreq_set_target (STB_LOCAL)
ffffffff81858681-ffffffff81858696: devfreq_set_target.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Transformation ⚠️</summary>

```c
int devfreq_set_target(struct devfreq *devfreq, long unsigned int new_freq, u32 flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/devfreq/devfreq.c (0)
Location: drivers/devfreq/devfreq.c:289
Inline: False
Direct callers:
  - drivers/devfreq/devfreq.c:update_devfreq
```
**Symbols:**

```
ffffffff818e8580-ffffffff818e86ef: devfreq_set_target (STB_LOCAL)
ffffffff818ea8a1-ffffffff818ea8b6: devfreq_set_target.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
int devfreq_set_target(struct devfreq *devfreq, long unsigned int new_freq, u32 flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/devfreq/devfreq.c (0)
Location: drivers/devfreq/devfreq.c:289
Inline: False
Direct callers:
  - drivers/devfreq/devfreq.c:update_devfreq
```
**Symbols:**

```
ffffffff819095f0-ffffffff8190975f: devfreq_set_target (STB_LOCAL)
ffffffff8190b921-ffffffff8190b936: devfreq_set_target.cold (STB_LOCAL)
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
