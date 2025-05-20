# Function: <code>enable_verity</code>

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
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
int enable_verity(struct file *filp, const struct fsverity_enable_arg *arg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/verity/enable.c (0)
Location: fs/verity/enable.c:157
Inline: False
Direct callers:
  - fs/verity/enable.c:fsverity_ioctl_enable
```
**Symbols:**

```
ffffffff8134f990-ffffffff8134fd5d: enable_verity (STB_LOCAL)
ffffffff8134ffab-ffffffff81350007: enable_verity.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
int enable_verity(struct file *filp, const struct fsverity_enable_arg *arg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/verity/enable.c (0)
Location: fs/verity/enable.c:198
Inline: False
Direct callers:
  - fs/verity/enable.c:fsverity_ioctl_enable
```
**Symbols:**

```
ffffffff813961f0-ffffffff813965c2: enable_verity (STB_LOCAL)
ffffffff81396809-ffffffff81396865: enable_verity.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
int enable_verity(struct file *filp, const struct fsverity_enable_arg *arg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/verity/enable.c (0)
Location: fs/verity/enable.c:198
Inline: False
Direct callers:
  - fs/verity/enable.c:fsverity_ioctl_enable
```
**Symbols:**

```
ffffffff813a7f10-ffffffff813a82e2: enable_verity (STB_LOCAL)
ffffffff81beb3a0-ffffffff81beb3fc: enable_verity.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
int enable_verity(struct file *filp, const struct fsverity_enable_arg *arg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/verity/enable.c (0)
Location: fs/verity/enable.c:198
Inline: False
Direct callers:
  - fs/verity/enable.c:fsverity_ioctl_enable
```
**Symbols:**

```
ffffffff813aef70-ffffffff813af336: enable_verity (STB_LOCAL)
ffffffff81bdd3f7-ffffffff81bdd450: enable_verity.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int enable_verity(struct file *filp, const struct fsverity_enable_arg *arg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/verity/enable.c (0)
Location: fs/verity/enable.c:198
Inline: False
Direct callers:
  - fs/verity/enable.c:fsverity_ioctl_enable
```
**Symbols:**

```
ffffffff813feb20-ffffffff813feee6: enable_verity (STB_LOCAL)
ffffffff81cc6cfe-ffffffff81cc6d57: enable_verity.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int enable_verity(struct file *filp, const struct fsverity_enable_arg *arg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/verity/enable.c (0)
Location: fs/verity/enable.c:197
Inline: False
Direct callers:
  - fs/verity/enable.c:fsverity_ioctl_enable
```
**Symbols:**

```
ffffffff814726b0-ffffffff81472a70: enable_verity (STB_LOCAL)
ffffffff81e79245-ffffffff81e79293: enable_verity.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int enable_verity(struct file *filp, const struct fsverity_enable_arg *arg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/verity/enable.c (ffffffff815043a0)
Location: fs/verity/enable.c:197
Inline: False
Direct callers:
  - fs/verity/enable.c:fsverity_ioctl_enable
```
**Symbols:**

```
ffffffff815043a0-ffffffff815047a9: enable_verity (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int enable_verity(struct file *filp, const struct fsverity_enable_arg *arg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/verity/enable.c (ffffffff8153bb30)
Location: fs/verity/enable.c:183
Inline: False
Direct callers:
  - fs/verity/enable.c:fsverity_ioctl_enable
```
**Symbols:**

```
ffffffff8153bb30-ffffffff8153bec3: enable_verity (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int enable_verity(struct file *filp, const struct fsverity_enable_arg *arg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/verity/enable.c (ffffffff81570e10)
Location: fs/verity/enable.c:183
Inline: False
Direct callers:
  - fs/verity/enable.c:fsverity_ioctl_enable
```
**Symbols:**

```
ffffffff81570e10-ffffffff815711a3: enable_verity (STB_LOCAL)
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
int enable_verity(struct file *filp, const struct fsverity_enable_arg *arg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/verity/enable.c (ffff800010411588)
Location: fs/verity/enable.c:157
Inline: False
Direct callers:
  - fs/verity/enable.c:fsverity_ioctl_enable
```
**Symbols:**

```
ffff800010411588-ffff800010411924: enable_verity (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int enable_verity(struct file *filp, const struct fsverity_enable_arg *arg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/verity/enable.c (c05ddad8)
Location: fs/verity/enable.c:157
Inline: False
Direct callers:
  - fs/verity/enable.c:fsverity_ioctl_enable
```
**Symbols:**

```
c05ddad8-c05ddfb8: enable_verity (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int enable_verity(struct file *filp, const struct fsverity_enable_arg *arg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/verity/enable.c (c00000000051eff0)
Location: fs/verity/enable.c:157
Inline: False
Direct callers:
  - fs/verity/enable.c:fsverity_ioctl_enable
```
**Symbols:**

```
c00000000051eff0-c00000000051f498: enable_verity (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int enable_verity(struct file *filp, const struct fsverity_enable_arg *arg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/verity/enable.c (ffffffe0002b9796)
Location: fs/verity/enable.c:157
Inline: False
Direct callers:
  - fs/verity/enable.c:fsverity_ioctl_enable
```
**Symbols:**

```
ffffffe0002b9796-ffffffe0002b9b56: enable_verity (STB_LOCAL)
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
int enable_verity(struct file *filp, const struct fsverity_enable_arg *arg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/verity/enable.c (0)
Location: fs/verity/enable.c:157
Inline: False
Direct callers:
  - fs/verity/enable.c:fsverity_ioctl_enable
```
**Symbols:**

```
ffffffff81347f70-ffffffff8134833d: enable_verity (STB_LOCAL)
ffffffff8134858b-ffffffff813485e7: enable_verity.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Transformation ⚠️</summary>

```c
int enable_verity(struct file *filp, const struct fsverity_enable_arg *arg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/verity/enable.c (0)
Location: fs/verity/enable.c:157
Inline: False
Direct callers:
  - fs/verity/enable.c:fsverity_ioctl_enable
```
**Symbols:**

```
ffffffff81338c50-ffffffff8133901d: enable_verity (STB_LOCAL)
ffffffff8133926b-ffffffff813392c7: enable_verity.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Transformation ⚠️</summary>

```c
int enable_verity(struct file *filp, const struct fsverity_enable_arg *arg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/verity/enable.c (0)
Location: fs/verity/enable.c:157
Inline: False
Direct callers:
  - fs/verity/enable.c:fsverity_ioctl_enable
```
**Symbols:**

```
ffffffff81345a40-ffffffff81345e0d: enable_verity (STB_LOCAL)
ffffffff8134605b-ffffffff813460b7: enable_verity.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
int enable_verity(struct file *filp, const struct fsverity_enable_arg *arg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/verity/enable.c (0)
Location: fs/verity/enable.c:157
Inline: False
Direct callers:
  - fs/verity/enable.c:fsverity_ioctl_enable
```
**Symbols:**

```
ffffffff81358d20-ffffffff813590ed: enable_verity (STB_LOCAL)
ffffffff8135933b-ffffffff81359397: enable_verity.cold (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
