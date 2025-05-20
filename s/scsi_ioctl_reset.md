# Function: <code>scsi_ioctl_reset</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int scsi_ioctl_reset(struct scsi_device *dev, int *arg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi_error.c (ffffffff815a9d80)
Location: drivers/scsi/scsi_error.c:2327
Inline: False
Direct callers:
  - drivers/scsi/scsi_ioctl.c:scsi_ioctl
```
**Symbols:**

```
ffffffff815a9d80-ffffffff815aa030: scsi_ioctl_reset (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int scsi_ioctl_reset(struct scsi_device *dev, int *arg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi_error.c (ffffffff81601cd0)
Location: drivers/scsi/scsi_error.c:2330
Inline: False
Direct callers:
  - drivers/scsi/scsi_ioctl.c:scsi_ioctl
```
**Symbols:**

```
ffffffff81601cd0-ffffffff81601f92: scsi_ioctl_reset (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int scsi_ioctl_reset(struct scsi_device *dev, int *arg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi_error.c (ffffffff816313c0)
Location: drivers/scsi/scsi_error.c:2330
Inline: False
Direct callers:
  - drivers/scsi/scsi_ioctl.c:scsi_ioctl
```
**Symbols:**

```
ffffffff816313c0-ffffffff81631682: scsi_ioctl_reset (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int scsi_ioctl_reset(struct scsi_device *dev, int *arg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi_error.c (ffffffff81647b10)
Location: drivers/scsi/scsi_error.c:2259
Inline: False
Direct callers:
  - drivers/scsi/scsi_ioctl.c:scsi_ioctl
```
**Symbols:**

```
ffffffff81647b10-ffffffff81647dba: scsi_ioctl_reset (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int scsi_ioctl_reset(struct scsi_device *dev, int *arg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi_error.c (ffffffff816b0b80)
Location: drivers/scsi/scsi_error.c:2284
Inline: False
Direct callers:
  - drivers/scsi/scsi_ioctl.c:scsi_ioctl
```
**Symbols:**

```
ffffffff816b0b80-ffffffff816b0e33: scsi_ioctl_reset (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int scsi_ioctl_reset(struct scsi_device *dev, int *arg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi_error.c (ffffffff816ecec0)
Location: drivers/scsi/scsi_error.c:2308
Inline: False
Direct callers:
  - drivers/scsi/scsi_ioctl.c:scsi_ioctl
```
**Symbols:**

```
ffffffff816ecec0-ffffffff816ed168: scsi_ioctl_reset (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int scsi_ioctl_reset(struct scsi_device *dev, int *arg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi_error.c (ffffffff81710a00)
Location: drivers/scsi/scsi_error.c:2305
Inline: False
Direct callers:
  - drivers/scsi/scsi_ioctl.c:scsi_ioctl
```
**Symbols:**

```
ffffffff81710a00-ffffffff81710cc9: scsi_ioctl_reset (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
int scsi_ioctl_reset(struct scsi_device *dev, int *arg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/scsi/scsi_error.c (0)
Location: drivers/scsi/scsi_error.c:2325
Inline: False
Direct callers:
  - drivers/scsi/scsi_ioctl.c:scsi_ioctl
```
**Symbols:**

```
ffffffff8174d97b-ffffffff8174d99a: scsi_ioctl_reset.cold (STB_LOCAL)
ffffffff8174d420-ffffffff8174d6cd: scsi_ioctl_reset (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
int scsi_ioctl_reset(struct scsi_device *dev, int *arg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/scsi/scsi_error.c (0)
Location: drivers/scsi/scsi_error.c:2328
Inline: False
Direct callers:
  - drivers/scsi/scsi_ioctl.c:scsi_ioctl
```
**Symbols:**

```
ffffffff81771ae8-ffffffff81771b07: scsi_ioctl_reset.cold (STB_LOCAL)
ffffffff817715a0-ffffffff8177184d: scsi_ioctl_reset (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
int scsi_ioctl_reset(struct scsi_device *dev, int *arg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/scsi/scsi_error.c (0)
Location: drivers/scsi/scsi_error.c:2330
Inline: False
Direct callers:
  - drivers/scsi/scsi_ioctl.c:scsi_ioctl_common
```
**Symbols:**

```
ffffffff81834206-ffffffff81834225: scsi_ioctl_reset.cold (STB_LOCAL)
ffffffff81833cc0-ffffffff81833f8b: scsi_ioctl_reset (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
int scsi_ioctl_reset(struct scsi_device *dev, int *arg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/scsi/scsi_error.c (0)
Location: drivers/scsi/scsi_error.c:2343
Inline: False
Direct callers:
  - drivers/scsi/scsi_ioctl.c:scsi_ioctl_common
```
**Symbols:**

```
ffffffff81c168ce-ffffffff81c168ed: scsi_ioctl_reset.cold (STB_LOCAL)
ffffffff818448f0-ffffffff81844bbb: scsi_ioctl_reset (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
int scsi_ioctl_reset(struct scsi_device *dev, int *arg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/scsi/scsi_error.c (0)
Location: drivers/scsi/scsi_error.c:2365
Inline: False
Direct callers:
  - drivers/scsi/scsi_ioctl.c:scsi_ioctl_common
```
**Symbols:**

```
ffffffff81c085a9-ffffffff81c085c8: scsi_ioctl_reset.cold (STB_LOCAL)
ffffffff81827ae0-ffffffff81827da7: scsi_ioctl_reset (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int scsi_ioctl_reset(struct scsi_device *dev, int *arg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/scsi/scsi_error.c (0)
Location: drivers/scsi/scsi_error.c:2377
Inline: False
Direct callers:
  - drivers/scsi/scsi_ioctl.c:scsi_ioctl
```
**Symbols:**

```
ffffffff81d0c463-ffffffff81d0c482: scsi_ioctl_reset.cold (STB_LOCAL)
ffffffff818b3490-ffffffff818b3750: scsi_ioctl_reset (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int scsi_ioctl_reset(struct scsi_device *dev, int *arg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/scsi/scsi_error.c (0)
Location: drivers/scsi/scsi_error.c:2377
Inline: False
Direct callers:
  - drivers/scsi/scsi_ioctl.c:scsi_ioctl
```
**Symbols:**

```
ffffffff81ed53a6-ffffffff81ed53c5: scsi_ioctl_reset.cold (STB_LOCAL)
ffffffff819fe660-ffffffff819fe8f9: scsi_ioctl_reset (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int scsi_ioctl_reset(struct scsi_device *dev, int *arg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi_error.c (ffffffff81b7cbc0)
Location: drivers/scsi/scsi_error.c:2386
Inline: False
Direct callers:
  - drivers/scsi/scsi_ioctl.c:scsi_ioctl
```
**Symbols:**

```
ffffffff81b7cbc0-ffffffff81b7ce7c: scsi_ioctl_reset (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int scsi_ioctl_reset(struct scsi_device *dev, int *arg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi_error.c (ffffffff81bd0940)
Location: drivers/scsi/scsi_error.c:2432
Inline: False
Direct callers:
  - drivers/scsi/scsi_ioctl.c:scsi_ioctl
```
**Symbols:**

```
ffffffff81bd0940-ffffffff81bd0bfc: scsi_ioctl_reset (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int scsi_ioctl_reset(struct scsi_device *dev, int *arg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi_error.c (ffffffff81c255a0)
Location: drivers/scsi/scsi_error.c:2438
Inline: False
Direct callers:
  - drivers/scsi/scsi_ioctl.c:scsi_ioctl
```
**Symbols:**

```
ffffffff81c255a0-ffffffff81c2586e: scsi_ioctl_reset (STB_GLOBAL)
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
int scsi_ioctl_reset(struct scsi_device *dev, int *arg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi_error.c (ffff800010974c60)
Location: drivers/scsi/scsi_error.c:2328
Inline: False
Direct callers:
  - drivers/scsi/scsi_ioctl.c:scsi_ioctl
```
**Symbols:**

```
ffff800010974c60-ffff8000109750fc: scsi_ioctl_reset (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int scsi_ioctl_reset(struct scsi_device *dev, int *arg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi_error.c (c0a4957c)
Location: drivers/scsi/scsi_error.c:2328
Inline: False
Direct callers:
  - drivers/scsi/scsi_ioctl.c:scsi_ioctl
```
**Symbols:**

```
c0a4957c-c0a49820: scsi_ioctl_reset (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int scsi_ioctl_reset(struct scsi_device *dev, int *arg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi_error.c (c000000000a2ec20)
Location: drivers/scsi/scsi_error.c:2328
Inline: False
Direct callers:
  - drivers/scsi/scsi_ioctl.c:scsi_ioctl
```
**Symbols:**

```
c000000000a2ec20-c000000000a2efe0: scsi_ioctl_reset (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int scsi_ioctl_reset(struct scsi_device *dev, int *arg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi_error.c (ffffffe0005dd644)
Location: drivers/scsi/scsi_error.c:2328
Inline: False
Direct callers:
  - drivers/scsi/scsi_ioctl.c:scsi_ioctl
```
**Symbols:**

```
ffffffe0005dd644-ffffffe0005dd8a4: scsi_ioctl_reset (STB_GLOBAL)
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
int scsi_ioctl_reset(struct scsi_device *dev, int *arg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/scsi/scsi_error.c (0)
Location: drivers/scsi/scsi_error.c:2328
Inline: False
Direct callers:
  - drivers/scsi/scsi_ioctl.c:scsi_ioctl
```
**Symbols:**

```
ffffffff817261d8-ffffffff817261f7: scsi_ioctl_reset.cold (STB_LOCAL)
ffffffff81725c90-ffffffff81725f3d: scsi_ioctl_reset (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Transformation ⚠️</summary>

```c
int scsi_ioctl_reset(struct scsi_device *dev, int *arg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/scsi/scsi_error.c (0)
Location: drivers/scsi/scsi_error.c:2328
Inline: False
Direct callers:
  - drivers/scsi/scsi_ioctl.c:scsi_ioctl
```
**Symbols:**

```
ffffffff816ff608-ffffffff816ff627: scsi_ioctl_reset.cold (STB_LOCAL)
ffffffff816ff0c0-ffffffff816ff36d: scsi_ioctl_reset (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Transformation ⚠️</summary>

```c
int scsi_ioctl_reset(struct scsi_device *dev, int *arg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/scsi/scsi_error.c (0)
Location: drivers/scsi/scsi_error.c:2328
Inline: False
Direct callers:
  - drivers/scsi/scsi_ioctl.c:scsi_ioctl
```
**Symbols:**

```
ffffffff81764fa8-ffffffff81764fc7: scsi_ioctl_reset.cold (STB_LOCAL)
ffffffff81764a60-ffffffff81764d0d: scsi_ioctl_reset (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
int scsi_ioctl_reset(struct scsi_device *dev, int *arg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/scsi/scsi_error.c (0)
Location: drivers/scsi/scsi_error.c:2328
Inline: False
Direct callers:
  - drivers/scsi/scsi_ioctl.c:scsi_ioctl
```
**Symbols:**

```
ffffffff81780628-ffffffff81780647: scsi_ioctl_reset.cold (STB_LOCAL)
ffffffff817800e0-ffffffff8178038d: scsi_ioctl_reset (STB_GLOBAL)
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
