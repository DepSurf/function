# Function: <code>pwm_unexport_child</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/pwm/sysfs.c (ffffffff8142d437)
Location: drivers/pwm/sysfs.c:228
Inline: True
Inline callers:
  - drivers/pwm/sysfs.c:unexport_store
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/pwm/sysfs.c (ffffffff81478613)
Location: drivers/pwm/sysfs.c:287
Inline: True
Inline callers:
  - drivers/pwm/sysfs.c:unexport_store
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int pwm_unexport_child(struct device *parent, struct pwm_device *pwm);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pwm/sysfs.c (ffffffff81499920)
Location: drivers/pwm/sysfs.c:287
Inline: False
Direct callers:
  - drivers/pwm/sysfs.c:pwmchip_sysfs_unexport_children
  - drivers/pwm/sysfs.c:unexport_store
```
**Symbols:**

```
ffffffff81499920-ffffffff81499977: pwm_unexport_child (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int pwm_unexport_child(struct device *parent, struct pwm_device *pwm);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pwm/sysfs.c (ffffffff814a3560)
Location: drivers/pwm/sysfs.c:287
Inline: False
Direct callers:
  - drivers/pwm/sysfs.c:pwmchip_sysfs_unexport_children
  - drivers/pwm/sysfs.c:unexport_store
```
**Symbols:**

```
ffffffff814a3560-ffffffff814a35b7: pwm_unexport_child (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int pwm_unexport_child(struct device *parent, struct pwm_device *pwm);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pwm/sysfs.c (ffffffff814e22d0)
Location: drivers/pwm/sysfs.c:287
Inline: False
Direct callers:
  - drivers/pwm/sysfs.c:pwmchip_sysfs_unexport_children
  - drivers/pwm/sysfs.c:unexport_store
```
**Symbols:**

```
ffffffff814e22d0-ffffffff814e2321: pwm_unexport_child (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int pwm_unexport_child(struct device *parent, struct pwm_device *pwm);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pwm/sysfs.c (ffffffff81511af0)
Location: drivers/pwm/sysfs.c:289
Inline: False
Direct callers:
  - drivers/pwm/sysfs.c:pwmchip_sysfs_unexport_children
  - drivers/pwm/sysfs.c:unexport_store
```
**Symbols:**

```
ffffffff81511af0-ffffffff81511b42: pwm_unexport_child (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int pwm_unexport_child(struct device *parent, struct pwm_device *pwm);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pwm/sysfs.c (ffffffff815271b0)
Location: drivers/pwm/sysfs.c:293
Inline: False
Direct callers:
  - drivers/pwm/sysfs.c:pwmchip_sysfs_unexport_children
  - drivers/pwm/sysfs.c:unexport_store
```
**Symbols:**

```
ffffffff815271b0-ffffffff81527274: pwm_unexport_child (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int pwm_unexport_child(struct device *parent, struct pwm_device *pwm);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pwm/sysfs.c (ffffffff815565f0)
Location: drivers/pwm/sysfs.c:285
Inline: False
Direct callers:
  - drivers/pwm/sysfs.c:pwmchip_sysfs_unexport
  - drivers/pwm/sysfs.c:unexport_store
```
**Symbols:**

```
ffffffff815565f0-ffffffff815566b6: pwm_unexport_child (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int pwm_unexport_child(struct device *parent, struct pwm_device *pwm);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pwm/sysfs.c (ffffffff81577c10)
Location: drivers/pwm/sysfs.c:285
Inline: False
Direct callers:
  - drivers/pwm/sysfs.c:pwmchip_sysfs_unexport
  - drivers/pwm/sysfs.c:unexport_store
```
**Symbols:**

```
ffffffff81577c10-ffffffff81577cd6: pwm_unexport_child (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int pwm_unexport_child(struct device *parent, struct pwm_device *pwm);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pwm/sysfs.c (ffffffff8161c8f0)
Location: drivers/pwm/sysfs.c:285
Inline: False
Direct callers:
  - drivers/pwm/sysfs.c:pwmchip_sysfs_unexport
  - drivers/pwm/sysfs.c:unexport_store
```
**Symbols:**

```
ffffffff8161c8f0-ffffffff8161c9b6: pwm_unexport_child (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int pwm_unexport_child(struct device *parent, struct pwm_device *pwm);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pwm/sysfs.c (ffffffff81642ec0)
Location: drivers/pwm/sysfs.c:285
Inline: False
Direct callers:
  - drivers/pwm/sysfs.c:pwmchip_sysfs_unexport
  - drivers/pwm/sysfs.c:unexport_store
```
**Symbols:**

```
ffffffff81642ec0-ffffffff81642f86: pwm_unexport_child (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int pwm_unexport_child(struct device *parent, struct pwm_device *pwm);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pwm/sysfs.c (ffffffff81625ce0)
Location: drivers/pwm/sysfs.c:285
Inline: False
Direct callers:
  - drivers/pwm/sysfs.c:pwmchip_sysfs_unexport
  - drivers/pwm/sysfs.c:unexport_store
```
**Symbols:**

```
ffffffff81625ce0-ffffffff81625da6: pwm_unexport_child (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int pwm_unexport_child(struct device *parent, struct pwm_device *pwm);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pwm/sysfs.c (ffffffff816954d0)
Location: drivers/pwm/sysfs.c:285
Inline: False
Direct callers:
  - drivers/pwm/sysfs.c:pwmchip_sysfs_unexport
  - drivers/pwm/sysfs.c:unexport_store
```
**Symbols:**

```
ffffffff816954d0-ffffffff81695596: pwm_unexport_child (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int pwm_unexport_child(struct device *parent, struct pwm_device *pwm);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pwm/sysfs.c (ffffffff817b6190)
Location: drivers/pwm/sysfs.c:285
Inline: False
Direct callers:
  - drivers/pwm/sysfs.c:pwmchip_sysfs_unexport
  - drivers/pwm/sysfs.c:unexport_store
```
**Symbols:**

```
ffffffff817b6190-ffffffff817b626c: pwm_unexport_child (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int pwm_unexport_child(struct device *parent, struct pwm_device *pwm);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pwm/sysfs.c (ffffffff818d06f0)
Location: drivers/pwm/sysfs.c:285
Inline: False
Direct callers:
  - drivers/pwm/sysfs.c:pwmchip_sysfs_unexport
  - drivers/pwm/sysfs.c:unexport_store
```
**Symbols:**

```
ffffffff818d06f0-ffffffff818d07cc: pwm_unexport_child (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int pwm_unexport_child(struct device *parent, struct pwm_device *pwm);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pwm/sysfs.c (ffffffff81913680)
Location: drivers/pwm/sysfs.c:285
Inline: False
Direct callers:
  - drivers/pwm/sysfs.c:pwmchip_sysfs_unexport
  - drivers/pwm/sysfs.c:unexport_store
```
**Symbols:**

```
ffffffff81913680-ffffffff8191375c: pwm_unexport_child (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int pwm_unexport_child(struct device *parent, struct pwm_device *pwm);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pwm/sysfs.c (ffffffff8195b5c0)
Location: drivers/pwm/sysfs.c:285
Inline: False
Direct callers:
  - drivers/pwm/sysfs.c:pwmchip_sysfs_unexport
  - drivers/pwm/sysfs.c:unexport_store
```
**Symbols:**

```
ffffffff8195b5c0-ffffffff8195b69c: pwm_unexport_child (STB_LOCAL)
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
int pwm_unexport_child(struct device *parent, struct pwm_device *pwm);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pwm/sysfs.c (ffff8000106d9a00)
Location: drivers/pwm/sysfs.c:285
Inline: False
Direct callers:
  - drivers/pwm/sysfs.c:pwmchip_sysfs_unexport
  - drivers/pwm/sysfs.c:unexport_store
```
**Symbols:**

```
ffff8000106d9a00-ffff8000106d9afc: pwm_unexport_child (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int pwm_unexport_child(struct device *parent, struct pwm_device *pwm);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pwm/sysfs.c (c08760e0)
Location: drivers/pwm/sysfs.c:285
Inline: False
Direct callers:
  - drivers/pwm/sysfs.c:pwmchip_sysfs_unexport
  - drivers/pwm/sysfs.c:unexport_store
```
**Symbols:**

```
c08760e0-c08761c8: pwm_unexport_child (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int pwm_unexport_child(struct device *parent, struct pwm_device *pwm);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pwm/sysfs.c (c000000000851100)
Location: drivers/pwm/sysfs.c:285
Inline: False
Direct callers:
  - drivers/pwm/sysfs.c:pwmchip_sysfs_unexport
  - drivers/pwm/sysfs.c:unexport_store
```
**Symbols:**

```
c000000000851100-c000000000851254: pwm_unexport_child (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int pwm_unexport_child(struct device *parent, struct pwm_device *pwm);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pwm/sysfs.c (ffffffe0004b24ba)
Location: drivers/pwm/sysfs.c:285
Inline: False
Direct callers:
  - drivers/pwm/sysfs.c:pwmchip_sysfs_unexport
  - drivers/pwm/sysfs.c:unexport_store
```
**Symbols:**

```
ffffffe0004b24ba-ffffffe0004b256c: pwm_unexport_child (STB_LOCAL)
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
int pwm_unexport_child(struct device *parent, struct pwm_device *pwm);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pwm/sysfs.c (ffffffff8156ca20)
Location: drivers/pwm/sysfs.c:285
Inline: False
Direct callers:
  - drivers/pwm/sysfs.c:pwmchip_sysfs_unexport
  - drivers/pwm/sysfs.c:unexport_store
```
**Symbols:**

```
ffffffff8156ca20-ffffffff8156cae6: pwm_unexport_child (STB_LOCAL)
```
</details>
</li>
<li>
In <code>azure</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int pwm_unexport_child(struct device *parent, struct pwm_device *pwm);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pwm/sysfs.c (ffffffff8156b960)
Location: drivers/pwm/sysfs.c:285
Inline: False
Direct callers:
  - drivers/pwm/sysfs.c:pwmchip_sysfs_unexport
  - drivers/pwm/sysfs.c:unexport_store
```
**Symbols:**

```
ffffffff8156b960-ffffffff8156ba26: pwm_unexport_child (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int pwm_unexport_child(struct device *parent, struct pwm_device *pwm);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pwm/sysfs.c (ffffffff81585e60)
Location: drivers/pwm/sysfs.c:285
Inline: False
Direct callers:
  - drivers/pwm/sysfs.c:pwmchip_sysfs_unexport
  - drivers/pwm/sysfs.c:unexport_store
```
**Symbols:**

```
ffffffff81585e60-ffffffff81585f26: pwm_unexport_child (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
No changes between <code>generic</code> and <code>gcp</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>lowlatency</code> ✅
</li>
</ul>
