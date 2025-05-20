# Function: <code>nvm_unregister</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline ⚠️</summary>

```c
void nvm_unregister(char *disk_name);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/lightnvm/core.c (ffffffff81543080)
Location: drivers/lightnvm/core.c:595
Inline: True
```
**Symbols:**

```
ffffffff81543080-ffffffff81543149: nvm_unregister (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
void nvm_unregister(char *disk_name);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/lightnvm/core.c (ffffffff81594dd0)
Location: drivers/lightnvm/core.c:720
Inline: True
```
**Symbols:**

```
ffffffff81594dd0-ffffffff81594ead: nvm_unregister (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void nvm_unregister(struct nvm_dev *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/lightnvm/core.c (ffffffff815c39a0)
Location: drivers/lightnvm/core.c:823
Inline: False
```
**Symbols:**

```
ffffffff815c39a0-ffffffff815c39fb: nvm_unregister (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void nvm_unregister(struct nvm_dev *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/lightnvm/core.c (ffffffff815d83c0)
Location: drivers/lightnvm/core.c:1109
Inline: False
```
**Symbols:**

```
ffffffff815d83c0-ffffffff815d84ee: nvm_unregister (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void nvm_unregister(struct nvm_dev *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/lightnvm/core.c (ffffffff8163f030)
Location: drivers/lightnvm/core.c:1115
Inline: False
```
**Symbols:**

```
ffffffff8163f030-ffffffff8163f164: nvm_unregister (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void nvm_unregister(struct nvm_dev *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/lightnvm/core.c (ffffffff8167a3f0)
Location: drivers/lightnvm/core.c:958
Inline: False
```
**Symbols:**

```
ffffffff8167a3f0-ffffffff8167a526: nvm_unregister (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void nvm_unregister(struct nvm_dev *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/lightnvm/core.c (ffffffff81699040)
Location: drivers/lightnvm/core.c:1173
Inline: False
```
**Symbols:**

```
ffffffff81699040-ffffffff81699108: nvm_unregister (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void nvm_unregister(struct nvm_dev *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/lightnvm/core.c (ffffffff816d2290)
Location: drivers/lightnvm/core.c:1186
Inline: False
```
**Symbols:**

```
ffffffff816d2290-ffffffff816d2385: nvm_unregister (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void nvm_unregister(struct nvm_dev *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/lightnvm/core.c (ffffffff816f6170)
Location: drivers/lightnvm/core.c:1215
Inline: False
```
**Symbols:**

```
ffffffff816f6170-ffffffff816f6265: nvm_unregister (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void nvm_unregister(struct nvm_dev *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/lightnvm/core.c (ffffffff817af500)
Location: drivers/lightnvm/core.c:1214
Inline: False
```
**Symbols:**

```
ffffffff817af500-ffffffff817af634: nvm_unregister (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void nvm_unregister(struct nvm_dev *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/lightnvm/core.c (ffffffff817c4080)
Location: drivers/lightnvm/core.c:1209
Inline: False
```
**Symbols:**

```
ffffffff817c4080-ffffffff817c41b4: nvm_unregister (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void nvm_unregister(struct nvm_dev *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/lightnvm/core.c (ffffffff817a7240)
Location: drivers/lightnvm/core.c:1211
Inline: False
```
**Symbols:**

```
ffffffff817a7240-ffffffff817a7374: nvm_unregister (STB_GLOBAL)
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
void nvm_unregister(struct nvm_dev *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/lightnvm/core.c (ffff8000108df8c0)
Location: drivers/lightnvm/core.c:1215
Inline: False
```
**Symbols:**

```
ffff8000108df8c0-ffff8000108df9c8: nvm_unregister (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void nvm_unregister(struct nvm_dev *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/lightnvm/core.c (c09ce288)
Location: drivers/lightnvm/core.c:1215
Inline: False
```
**Symbols:**

```
c09ce288-c09ce370: nvm_unregister (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void nvm_unregister(struct nvm_dev *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/lightnvm/core.c (c000000000972e20)
Location: drivers/lightnvm/core.c:1215
Inline: False
```
**Symbols:**

```
c000000000972e20-c000000000972fd8: nvm_unregister (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void nvm_unregister(struct nvm_dev *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/lightnvm/core.c (ffffffe000575260)
Location: drivers/lightnvm/core.c:1215
Inline: False
```
**Symbols:**

```
ffffffe000575260-ffffffe00057535a: nvm_unregister (STB_GLOBAL)
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
void nvm_unregister(struct nvm_dev *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/lightnvm/core.c (ffffffff816bb960)
Location: drivers/lightnvm/core.c:1215
Inline: False
Direct callers:
  - drivers/nvme/host/lightnvm.c:nvme_nvm_unregister
```
**Symbols:**

```
ffffffff816bb960-ffffffff816bba55: nvm_unregister (STB_GLOBAL)
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
void nvm_unregister(struct nvm_dev *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/lightnvm/core.c (ffffffff816e9e30)
Location: drivers/lightnvm/core.c:1215
Inline: False
```
**Symbols:**

```
ffffffff816e9e30-ffffffff816e9f25: nvm_unregister (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void nvm_unregister(struct nvm_dev *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/lightnvm/core.c (ffffffff81704670)
Location: drivers/lightnvm/core.c:1215
Inline: False
```
**Symbols:**

```
ffffffff81704670-ffffffff81704765: nvm_unregister (STB_GLOBAL)
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
<details>
<summary>Changed between <code>4.8</code> and <code>4.10</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>struct nvm_dev *dev</code>
</li>
<li>
<b>Param removed. </b>
<code>char *disk_name</code>
</li>
</ul>
</details>
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
