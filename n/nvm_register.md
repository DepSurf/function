# Function: <code>nvm_register</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int nvm_register(struct request_queue *q, char *disk_name, struct nvm_dev_ops *ops);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/lightnvm/core.c (ffffffff81543890)
Location: drivers/lightnvm/core.c:539
Inline: False
```
**Symbols:**

```
ffffffff81543890-ffffffff81543dec: nvm_register (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int nvm_register(struct request_queue *q, char *disk_name, struct nvm_dev_ops *ops);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/lightnvm/core.c (ffffffff81595840)
Location: drivers/lightnvm/core.c:661
Inline: False
```
**Symbols:**

```
ffffffff81595840-ffffffff81595de9: nvm_register (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int nvm_register(struct nvm_dev *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/lightnvm/core.c (ffffffff815c33f0)
Location: drivers/lightnvm/core.c:778
Inline: False
```
**Symbols:**

```
ffffffff815c33f0-ffffffff815c3936: nvm_register (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int nvm_register(struct nvm_dev *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/lightnvm/core.c (ffffffff815d9530)
Location: drivers/lightnvm/core.c:1073
Inline: False
```
**Symbols:**

```
ffffffff815d9530-ffffffff815d9b71: nvm_register (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int nvm_register(struct nvm_dev *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/lightnvm/core.c (ffffffff81640290)
Location: drivers/lightnvm/core.c:1079
Inline: False
```
**Symbols:**

```
ffffffff81640290-ffffffff816408e3: nvm_register (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline, Transformation ⚠️</summary>

```c
int nvm_register(struct nvm_dev *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/lightnvm/core.c (0)
Location: drivers/lightnvm/core.c:929
Inline: True
```
**Symbols:**

```
ffffffff8167b8e0-ffffffff8167b941: nvm_register.cold.26 (STB_LOCAL)
ffffffff8167a560-ffffffff8167a873: nvm_register (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline, Transformation ⚠️</summary>

```c
int nvm_register(struct nvm_dev *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/lightnvm/core.c (ffffffff8169b270)
Location: drivers/lightnvm/core.c:1141
Inline: True
```
**Symbols:**

```
ffffffff8169b21a-ffffffff8169b2af: nvm_register.cold.29 (STB_LOCAL)
ffffffff81699eb0-ffffffff8169a1ad: nvm_register (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
int nvm_register(struct nvm_dev *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/lightnvm/core.c (0)
Location: drivers/lightnvm/core.c:1150
Inline: False
```
**Symbols:**

```
ffffffff816d3ba3-ffffffff816d3cf8: nvm_register.cold (STB_LOCAL)
ffffffff816d2a40-ffffffff816d2c95: nvm_register (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
int nvm_register(struct nvm_dev *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/lightnvm/core.c (0)
Location: drivers/lightnvm/core.c:1179
Inline: False
```
**Symbols:**

```
ffffffff816f7a72-ffffffff816f7bc7: nvm_register.cold (STB_LOCAL)
ffffffff816f6920-ffffffff816f6b75: nvm_register (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
int nvm_register(struct nvm_dev *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/lightnvm/core.c (0)
Location: drivers/lightnvm/core.c:1178
Inline: False
```
**Symbols:**

```
ffffffff817b06dd-ffffffff817b0700: nvm_register.cold (STB_LOCAL)
ffffffff817af890-ffffffff817af9b6: nvm_register (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
int nvm_register(struct nvm_dev *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/lightnvm/core.c (0)
Location: drivers/lightnvm/core.c:1173
Inline: False
```
**Symbols:**

```
ffffffff81c0d991-ffffffff81c0d9b4: nvm_register.cold (STB_LOCAL)
ffffffff817c4410-ffffffff817c4536: nvm_register (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
int nvm_register(struct nvm_dev *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/lightnvm/core.c (0)
Location: drivers/lightnvm/core.c:1173
Inline: False
```
**Symbols:**

```
ffffffff81bffea5-ffffffff81bffee0: nvm_register.cold (STB_LOCAL)
ffffffff817a8430-ffffffff817a8562: nvm_register (STB_GLOBAL)
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
int nvm_register(struct nvm_dev *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/lightnvm/core.c (ffff8000108e0698)
Location: drivers/lightnvm/core.c:1179
Inline: False
```
**Symbols:**

```
ffff8000108e0698-ffff8000108e09d8: nvm_register (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int nvm_register(struct nvm_dev *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/lightnvm/core.c (c09cf23c)
Location: drivers/lightnvm/core.c:1179
Inline: False
```
**Symbols:**

```
c09cf23c-c09cf59c: nvm_register (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
int nvm_register(struct nvm_dev *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/lightnvm/core.c (c0000000009740b0)
Location: drivers/lightnvm/core.c:1179
Inline: True
```
**Symbols:**

```
c0000000009740b0-c000000000974550: nvm_register (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
int nvm_register(struct nvm_dev *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/lightnvm/core.c (ffffffe000576020)
Location: drivers/lightnvm/core.c:1179
Inline: True
```
**Symbols:**

```
ffffffe000576020-ffffffe00057631c: nvm_register (STB_GLOBAL)
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
int nvm_register(struct nvm_dev *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/lightnvm/core.c (0)
Location: drivers/lightnvm/core.c:1179
Inline: False
Direct callers:
  - drivers/nvme/host/lightnvm.c:nvme_nvm_register
```
**Symbols:**

```
ffffffff816bd262-ffffffff816bd3b7: nvm_register.cold (STB_LOCAL)
ffffffff816bc110-ffffffff816bc365: nvm_register (STB_GLOBAL)
```
</details>
</li>
<li>
In <code>azure</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>gcp</code>: Transformation ⚠️</summary>

```c
int nvm_register(struct nvm_dev *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/lightnvm/core.c (0)
Location: drivers/lightnvm/core.c:1179
Inline: False
```
**Symbols:**

```
ffffffff816eb732-ffffffff816eb887: nvm_register.cold (STB_LOCAL)
ffffffff816ea5e0-ffffffff816ea835: nvm_register (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
int nvm_register(struct nvm_dev *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/lightnvm/core.c (0)
Location: drivers/lightnvm/core.c:1179
Inline: False
```
**Symbols:**

```
ffffffff81705f72-ffffffff817060c7: nvm_register.cold (STB_LOCAL)
ffffffff81704e20-ffffffff81705075: nvm_register (STB_GLOBAL)
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
<code>struct request_queue *q</code>
</li>
<li>
<b>Param removed. </b>
<code>char *disk_name</code>
</li>
<li>
<b>Param removed. </b>
<code>struct nvm_dev_ops *ops</code>
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
