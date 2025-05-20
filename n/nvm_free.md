# Function: <code>nvm_free</code>

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
In drivers/lightnvm/core.c (ffffffff815430f8)
Location: drivers/lightnvm/core.c:477
Inline: True
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
In drivers/lightnvm/core.c (ffffffff81594e48)
Location: drivers/lightnvm/core.c:599
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void nvm_free(struct nvm_dev *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/lightnvm/core.c (ffffffff815c3940)
Location: drivers/lightnvm/core.c:714
Inline: False
Direct callers:
  - drivers/lightnvm/core.c:nvm_unregister
```
**Symbols:**

```
ffffffff815c3940-ffffffff815c399c: nvm_free (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/lightnvm/core.c (ffffffff815d8471)
Location: drivers/lightnvm/core.c:1019
Inline: True
Inline callers:
  - drivers/lightnvm/core.c:nvm_unregister
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/lightnvm/core.c (ffffffff8163f0e1)
Location: drivers/lightnvm/core.c:1025
Inline: True
Inline callers:
  - drivers/lightnvm/core.c:nvm_unregister
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/lightnvm/core.c (ffffffff8167a4a7)
Location: drivers/lightnvm/core.c:880
Inline: True
Inline callers:
  - drivers/lightnvm/core.c:nvm_unregister
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void nvm_free(struct nvm_dev *dev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/lightnvm/core.c (ffffffff81698fb0)
Location: drivers/lightnvm/core.c:1092
Inline: False
Direct callers:
  - drivers/lightnvm/core.c:nvm_unregister
```
**Symbols:**

```
ffffffff81698fb0-ffffffff8169903a: nvm_free (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void nvm_free(struct kref *ref);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/lightnvm/core.c (ffffffff816d1af0)
Location: drivers/lightnvm/core.c:1094
Inline: False
Direct callers:
  - drivers/lightnvm/core.c:nvm_ctl_ioctl
  - drivers/lightnvm/core.c:nvm_unregister
  - drivers/lightnvm/core.c:nvm_unregister
  - drivers/lightnvm/core.c:nvm_register
  - drivers/lightnvm/core.c:nvm_register
  - drivers/lightnvm/core.c:nvm_register
```
**Symbols:**

```
ffffffff816d1af0-ffffffff816d1b83: nvm_free (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void nvm_free(struct kref *ref);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/lightnvm/core.c (ffffffff816f59e0)
Location: drivers/lightnvm/core.c:1124
Inline: False
Direct callers:
  - drivers/lightnvm/core.c:nvm_ctl_ioctl
  - drivers/lightnvm/core.c:nvm_unregister
  - drivers/lightnvm/core.c:nvm_unregister
  - drivers/lightnvm/core.c:nvm_register
  - drivers/lightnvm/core.c:nvm_register
  - drivers/lightnvm/core.c:nvm_register
```
**Symbols:**

```
ffffffff816f59e0-ffffffff816f5a73: nvm_free (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void nvm_free(struct kref *ref);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/lightnvm/core.c (ffffffff817add30)
Location: drivers/lightnvm/core.c:1123
Inline: False
Direct callers:
  - drivers/lightnvm/core.c:nvm_unregister
  - drivers/lightnvm/core.c:nvm_unregister
  - drivers/lightnvm/core.c:nvm_register
  - drivers/lightnvm/core.c:nvm_register
```
**Symbols:**

```
ffffffff817add30-ffffffff817addc4: nvm_free (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void nvm_free(struct kref *ref);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/lightnvm/core.c (ffffffff817c28d0)
Location: drivers/lightnvm/core.c:1118
Inline: False
Direct callers:
  - drivers/lightnvm/core.c:nvm_unregister
  - drivers/lightnvm/core.c:nvm_unregister
  - drivers/lightnvm/core.c:nvm_register
  - drivers/lightnvm/core.c:nvm_register
```
**Symbols:**

```
ffffffff817c28d0-ffffffff817c2964: nvm_free (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void nvm_free(struct kref *ref);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/lightnvm/core.c (ffffffff817a5d90)
Location: drivers/lightnvm/core.c:1118
Inline: False
Direct callers:
  - drivers/lightnvm/core.c:nvm_ctl_ioctl
  - drivers/lightnvm/core.c:nvm_unregister
  - drivers/lightnvm/core.c:nvm_unregister
  - drivers/lightnvm/core.c:nvm_register
  - drivers/lightnvm/core.c:nvm_register
```
**Symbols:**

```
ffffffff817a5d90-ffffffff817a5e24: nvm_free (STB_LOCAL)
```
</details>
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
void nvm_free(struct kref *ref);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/lightnvm/core.c (ffff8000108def10)
Location: drivers/lightnvm/core.c:1124
Inline: False
Direct callers:
  - drivers/lightnvm/core.c:nvm_ctl_ioctl
  - drivers/lightnvm/core.c:nvm_unregister
  - drivers/lightnvm/core.c:nvm_unregister
  - drivers/lightnvm/core.c:nvm_register
  - drivers/lightnvm/core.c:nvm_register
```
**Symbols:**

```
ffff8000108def10-ffff8000108defbc: nvm_free (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void nvm_free(struct kref *ref);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/lightnvm/core.c (c09cdc9c)
Location: drivers/lightnvm/core.c:1124
Inline: False
Direct callers:
  - drivers/lightnvm/core.c:nvm_ctl_ioctl
  - drivers/lightnvm/core.c:nvm_unregister
  - drivers/lightnvm/core.c:nvm_unregister
  - drivers/lightnvm/core.c:nvm_register
  - drivers/lightnvm/core.c:nvm_register
  - drivers/lightnvm/core.c:nvm_register
```
**Symbols:**

```
c09cdc9c-c09cdd34: nvm_free (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void nvm_free(struct kref *ref);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/lightnvm/core.c (c000000000972800)
Location: drivers/lightnvm/core.c:1124
Inline: False
Direct callers:
  - drivers/lightnvm/core.c:nvm_ctl_ioctl
  - drivers/lightnvm/core.c:nvm_unregister
  - drivers/lightnvm/core.c:nvm_unregister
```
**Symbols:**

```
c000000000972800-c0000000009728fc: nvm_free (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void nvm_free(struct kref *ref);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/lightnvm/core.c (ffffffe000574e5a)
Location: drivers/lightnvm/core.c:1124
Inline: False
Direct callers:
  - drivers/lightnvm/core.c:nvm_ctl_ioctl
  - drivers/lightnvm/core.c:nvm_unregister
  - drivers/lightnvm/core.c:nvm_unregister
```
**Symbols:**

```
ffffffe000574e5a-ffffffe000574ef4: nvm_free (STB_LOCAL)
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
void nvm_free(struct kref *ref);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/lightnvm/core.c (ffffffff816bb1d0)
Location: drivers/lightnvm/core.c:1124
Inline: False
Direct callers:
  - drivers/lightnvm/core.c:nvm_ctl_ioctl
  - drivers/lightnvm/core.c:nvm_unregister
  - drivers/lightnvm/core.c:nvm_unregister
  - drivers/lightnvm/core.c:nvm_register
  - drivers/lightnvm/core.c:nvm_register
  - drivers/lightnvm/core.c:nvm_register
```
**Symbols:**

```
ffffffff816bb1d0-ffffffff816bb263: nvm_free (STB_LOCAL)
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
void nvm_free(struct kref *ref);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/lightnvm/core.c (ffffffff816e96a0)
Location: drivers/lightnvm/core.c:1124
Inline: False
Direct callers:
  - drivers/lightnvm/core.c:nvm_ctl_ioctl
  - drivers/lightnvm/core.c:nvm_unregister
  - drivers/lightnvm/core.c:nvm_unregister
  - drivers/lightnvm/core.c:nvm_register
  - drivers/lightnvm/core.c:nvm_register
  - drivers/lightnvm/core.c:nvm_register
```
**Symbols:**

```
ffffffff816e96a0-ffffffff816e9733: nvm_free (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void nvm_free(struct kref *ref);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/lightnvm/core.c (ffffffff81703ee0)
Location: drivers/lightnvm/core.c:1124
Inline: False
Direct callers:
  - drivers/lightnvm/core.c:nvm_ctl_ioctl
  - drivers/lightnvm/core.c:nvm_unregister
  - drivers/lightnvm/core.c:nvm_unregister
  - drivers/lightnvm/core.c:nvm_register
  - drivers/lightnvm/core.c:nvm_register
  - drivers/lightnvm/core.c:nvm_register
```
**Symbols:**

```
ffffffff81703ee0-ffffffff81703f73: nvm_free (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
<details>
<summary>Changed between <code>5.0</code> and <code>5.3</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>struct kref *ref</code>
</li>
<li>
<b>Param removed. </b>
<code>struct nvm_dev *dev</code>
</li>
</ul>
</details>
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
