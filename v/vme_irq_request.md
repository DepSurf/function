# Function: <code>vme_irq_request</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int vme_irq_request(struct vme_dev *vdev, int level, int statid, void (*callback)(int, int, void *), void *priv_data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/vme/vme.c (ffffffff816efba0)
Location: drivers/vme/vme.c:1099
Inline: False
```
**Symbols:**

```
ffffffff816efba0-ffffffff816efcc3: vme_irq_request (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int vme_irq_request(struct vme_dev *vdev, int level, int statid, void (*callback)(int, int, void *), void *priv_data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/vme/vme.c (ffffffff81754b50)
Location: drivers/vme/vme.c:1099
Inline: False
```
**Symbols:**

```
ffffffff81754b50-ffffffff81754c71: vme_irq_request (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int vme_irq_request(struct vme_dev *vdev, int level, int statid, void (*callback)(int, int, void *), void *priv_data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/vme/vme.c (ffffffff81781110)
Location: drivers/vme/vme.c:1102
Inline: False
```
**Symbols:**

```
ffffffff81781110-ffffffff81781231: vme_irq_request (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int vme_irq_request(struct vme_dev *vdev, int level, int statid, void (*callback)(int, int, void *), void *priv_data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/vme/vme.c (ffffffff8179feb0)
Location: drivers/vme/vme.c:1370
Inline: False
```
**Symbols:**

```
ffffffff8179feb0-ffffffff8179ffd1: vme_irq_request (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int vme_irq_request(struct vme_dev *vdev, int level, int statid, void (*callback)(int, int, void *), void *priv_data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/vme/vme.c (ffffffff81816fe0)
Location: drivers/vme/vme.c:1346
Inline: False
```
**Symbols:**

```
ffffffff81816fe0-ffffffff81817106: vme_irq_request (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Transformation ⚠️</summary>

```c
int vme_irq_request(struct vme_dev *vdev, int level, int statid, void (*callback)(int, int, void *), void *priv_data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/vme/vme.c (0)
Location: drivers/vme/vme.c:1346
Inline: False
```
**Symbols:**

```
ffffffff818628a0-ffffffff818628e2: vme_irq_request.cold.15 (STB_LOCAL)
ffffffff81860ed0-ffffffff81860fbd: vme_irq_request (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Transformation ⚠️</summary>

```c
int vme_irq_request(struct vme_dev *vdev, int level, int statid, void (*callback)(int, int, void *), void *priv_data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/vme/vme.c (0)
Location: drivers/vme/vme.c:1346
Inline: False
```
**Symbols:**

```
ffffffff81882030-ffffffff81882072: vme_irq_request.cold.15 (STB_LOCAL)
ffffffff81880680-ffffffff8188076d: vme_irq_request (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
int vme_irq_request(struct vme_dev *vdev, int level, int statid, void (*callback)(int, int, void *), void *priv_data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/vme/vme.c (0)
Location: drivers/vme/vme.c:1342
Inline: False
```
**Symbols:**

```
ffffffff818cc655-ffffffff818cc697: vme_irq_request.cold (STB_LOCAL)
ffffffff818cac60-ffffffff818cad48: vme_irq_request (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
int vme_irq_request(struct vme_dev *vdev, int level, int statid, void (*callback)(int, int, void *), void *priv_data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/vme/vme.c (0)
Location: drivers/vme/vme.c:1342
Inline: False
```
**Symbols:**

```
ffffffff818fea45-ffffffff818fea87: vme_irq_request.cold (STB_LOCAL)
ffffffff818fd050-ffffffff818fd138: vme_irq_request (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
int vme_irq_request(struct vme_dev *vdev, int level, int statid, void (*callback)(int, int, void *), void *priv_data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/vme/vme.c (0)
Location: drivers/vme/vme.c:1342
Inline: False
```
**Symbols:**

```
ffffffff819d5a15-ffffffff819d5a57: vme_irq_request.cold (STB_LOCAL)
ffffffff819d4450-ffffffff819d4538: vme_irq_request (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
int vme_irq_request(struct vme_dev *vdev, int level, int statid, void (*callback)(int, int, void *), void *priv_data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/vme/vme.c (0)
Location: drivers/vme/vme.c:1333
Inline: False
```
**Symbols:**

```
ffffffff81c2f9ff-ffffffff81c2fa41: vme_irq_request.cold (STB_LOCAL)
ffffffff819d3fd0-ffffffff819d40b8: vme_irq_request (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
int vme_irq_request(struct vme_dev *vdev, int level, int statid, void (*callback)(int, int, void *), void *priv_data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/vme/vme.c (0)
Location: drivers/vme/vme.c:1333
Inline: False
```
**Symbols:**

```
ffffffff81c21cc7-ffffffff81c21d09: vme_irq_request.cold (STB_LOCAL)
ffffffff819b9290-ffffffff819b9378: vme_irq_request (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int vme_irq_request(struct vme_dev *vdev, int level, int statid, void (*callback)(int, int, void *), void *priv_data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/vme/vme.c (0)
Location: drivers/vme/vme.c:1333
Inline: False
```
**Symbols:**

```
ffffffff81d33a2c-ffffffff81d33a6e: vme_irq_request.cold (STB_LOCAL)
ffffffff81a68230-ffffffff81a683c8: vme_irq_request (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int vme_irq_request(struct vme_dev *vdev, int level, int statid, void (*callback)(int, int, void *), void *priv_data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/vme/vme.c (0)
Location: drivers/vme/vme.c:1333
Inline: False
```
**Symbols:**

```
ffffffff81effe28-ffffffff81effe5a: vme_irq_request.cold (STB_LOCAL)
ffffffff81bd9970-ffffffff81bd9b1a: vme_irq_request (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int vme_irq_request(struct vme_dev *vdev, int level, int statid, void (*callback)(int, int, void *), void *priv_data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/staging/vme_user/vme.c (ffffffff81d6b230)
Location: drivers/staging/vme_user/vme.c:1333
Inline: False
```
**Symbols:**

```
ffffffff81d6b230-ffffffff81d6b40a: vme_irq_request (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int vme_irq_request(struct vme_dev *vdev, int level, int statid, void (*callback)(int, int, void *), void *priv_data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/staging/vme_user/vme.c (ffffffff81dd8510)
Location: drivers/staging/vme_user/vme.c:1333
Inline: False
```
**Symbols:**

```
ffffffff81dd8510-ffffffff81dd874d: vme_irq_request (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int vme_irq_request(struct vme_dev *vdev, int level, int statid, void (*callback)(int, int, void *), void *priv_data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/staging/vme_user/vme.c (ffffffff81e90ad0)
Location: drivers/staging/vme_user/vme.c:1298
Inline: False
```
**Symbols:**

```
ffffffff81e90ad0-ffffffff81e90d1d: vme_irq_request (STB_GLOBAL)
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
int vme_irq_request(struct vme_dev *vdev, int level, int statid, void (*callback)(int, int, void *), void *priv_data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/vme/vme.c (ffff800010b8c6d8)
Location: drivers/vme/vme.c:1342
Inline: False
```
**Symbols:**

```
ffff800010b8c6d8-ffff800010b8c800: vme_irq_request (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int vme_irq_request(struct vme_dev *vdev, int level, int statid, void (*callback)(int, int, void *), void *priv_data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/vme/vme.c (c0c771c0)
Location: drivers/vme/vme.c:1342
Inline: False
```
**Symbols:**

```
c0c771c0-c0c772d0: vme_irq_request (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int vme_irq_request(struct vme_dev *vdev, int level, int statid, void (*callback)(int, int, void *), void *priv_data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/vme/vme.c (c000000000c6a2f0)
Location: drivers/vme/vme.c:1342
Inline: False
```
**Symbols:**

```
c000000000c6a2f0-c000000000c6a480: vme_irq_request (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int vme_irq_request(struct vme_dev *vdev, int level, int statid, void (*callback)(int, int, void *), void *priv_data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/vme/vme.c (ffffffe000732a92)
Location: drivers/vme/vme.c:1342
Inline: False
```
**Symbols:**

```
ffffffe000732a92-ffffffe000732ba2: vme_irq_request (STB_GLOBAL)
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
int vme_irq_request(struct vme_dev *vdev, int level, int statid, void (*callback)(int, int, void *), void *priv_data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/vme/vme.c (0)
Location: drivers/vme/vme.c:1342
Inline: False
```
**Symbols:**

```
ffffffff8189fd75-ffffffff8189fdb7: vme_irq_request.cold (STB_LOCAL)
ffffffff8189e380-ffffffff8189e468: vme_irq_request (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Transformation ⚠️</summary>

```c
int vme_irq_request(struct vme_dev *vdev, int level, int statid, void (*callback)(int, int, void *), void *priv_data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/vme/vme.c (0)
Location: drivers/vme/vme.c:1342
Inline: False
```
**Symbols:**

```
ffffffff8185b4e5-ffffffff8185b527: vme_irq_request.cold (STB_LOCAL)
ffffffff81859af0-ffffffff81859bd8: vme_irq_request (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Transformation ⚠️</summary>

```c
int vme_irq_request(struct vme_dev *vdev, int level, int statid, void (*callback)(int, int, void *), void *priv_data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/vme/vme.c (0)
Location: drivers/vme/vme.c:1342
Inline: False
```
**Symbols:**

```
ffffffff818ef465-ffffffff818ef4a7: vme_irq_request.cold (STB_LOCAL)
ffffffff818eda70-ffffffff818edb58: vme_irq_request (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
int vme_irq_request(struct vme_dev *vdev, int level, int statid, void (*callback)(int, int, void *), void *priv_data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/vme/vme.c (0)
Location: drivers/vme/vme.c:1342
Inline: False
```
**Symbols:**

```
ffffffff819104e8-ffffffff8191052a: vme_irq_request.cold (STB_LOCAL)
ffffffff8190eaf0-ffffffff8190ebd8: vme_irq_request (STB_GLOBAL)
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
