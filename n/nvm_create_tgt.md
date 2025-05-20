# Function: <code>nvm_create_tgt</code>

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
<details>
<summary>In <code>4.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/lightnvm/core.c (ffffffff815d8630)
Location: drivers/lightnvm/core.c:229
Inline: True
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
In drivers/lightnvm/core.c (ffffffff8163f350)
Location: drivers/lightnvm/core.c:247
Inline: True
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
In drivers/lightnvm/core.c (ffffffff8167a95a)
Location: drivers/lightnvm/core.c:319
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/lightnvm/core.c (ffffffff8169a28a)
Location: drivers/lightnvm/core.c:319
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
int nvm_create_tgt(struct nvm_dev *dev, struct nvm_ioctl_create *create);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/lightnvm/core.c (0)
Location: drivers/lightnvm/core.c:307
Inline: False
```
**Symbols:**

```
ffffffff816d2ca0-ffffffff816d3584: nvm_create_tgt (STB_LOCAL)
ffffffff816d3cf8-ffffffff816d3e0a: nvm_create_tgt.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
int nvm_create_tgt(struct nvm_dev *dev, struct nvm_ioctl_create *create);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/lightnvm/core.c (0)
Location: drivers/lightnvm/core.c:309
Inline: False
```
**Symbols:**

```
ffffffff816f6b80-ffffffff816f7465: nvm_create_tgt (STB_LOCAL)
ffffffff816f7bc7-ffffffff816f7cc6: nvm_create_tgt.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
int nvm_create_tgt(struct nvm_dev *dev, struct nvm_ioctl_create *create);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/lightnvm/core.c (0)
Location: drivers/lightnvm/core.c:309
Inline: False
```
**Symbols:**

```
ffffffff817afda0-ffffffff817b02f6: nvm_create_tgt (STB_LOCAL)
ffffffff817b0700-ffffffff817b0819: nvm_create_tgt.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
int nvm_create_tgt(struct nvm_dev *dev, struct nvm_ioctl_create *create);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/lightnvm/core.c (0)
Location: drivers/lightnvm/core.c:305
Inline: False
```
**Symbols:**

```
ffffffff817c4920-ffffffff817c4eb1: nvm_create_tgt (STB_LOCAL)
ffffffff81c0d9b4-ffffffff81c0dae8: nvm_create_tgt.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
int nvm_create_tgt(struct nvm_dev *dev, struct nvm_ioctl_create *create);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/lightnvm/core.c (0)
Location: drivers/lightnvm/core.c:305
Inline: False
```
**Symbols:**

```
ffffffff817a7780-ffffffff817a7d0c: nvm_create_tgt (STB_LOCAL)
ffffffff81bffc91-ffffffff81bffdc5: nvm_create_tgt.cold (STB_LOCAL)
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
int nvm_create_tgt(struct nvm_dev *dev, struct nvm_ioctl_create *create);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/lightnvm/core.c (ffff8000108e09d8)
Location: drivers/lightnvm/core.c:309
Inline: False
```
**Symbols:**

```
ffff8000108e09d8-ffff8000108e13e8: nvm_create_tgt (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int nvm_create_tgt(struct nvm_dev *dev, struct nvm_ioctl_create *create);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/lightnvm/core.c (c09cf59c)
Location: drivers/lightnvm/core.c:309
Inline: False
```
**Symbols:**

```
c09cf59c-c09cfeb4: nvm_create_tgt (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int nvm_create_tgt(struct nvm_dev *dev, struct nvm_ioctl_create *create);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/lightnvm/core.c (c000000000974550)
Location: drivers/lightnvm/core.c:309
Inline: False
```
**Symbols:**

```
c000000000974550-c00000000097527c: nvm_create_tgt (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int nvm_create_tgt(struct nvm_dev *dev, struct nvm_ioctl_create *create);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/lightnvm/core.c (ffffffe00057631c)
Location: drivers/lightnvm/core.c:309
Inline: False
```
**Symbols:**

```
ffffffe00057631c-ffffffe000576b2a: nvm_create_tgt (STB_LOCAL)
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
int nvm_create_tgt(struct nvm_dev *dev, struct nvm_ioctl_create *create);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/lightnvm/core.c (0)
Location: drivers/lightnvm/core.c:309
Inline: False
```
**Symbols:**

```
ffffffff816bc370-ffffffff816bcc55: nvm_create_tgt (STB_LOCAL)
ffffffff816bd3b7-ffffffff816bd4b6: nvm_create_tgt.cold (STB_LOCAL)
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
int nvm_create_tgt(struct nvm_dev *dev, struct nvm_ioctl_create *create);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/lightnvm/core.c (0)
Location: drivers/lightnvm/core.c:309
Inline: False
```
**Symbols:**

```
ffffffff816ea840-ffffffff816eb125: nvm_create_tgt (STB_LOCAL)
ffffffff816eb887-ffffffff816eb986: nvm_create_tgt.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
int nvm_create_tgt(struct nvm_dev *dev, struct nvm_ioctl_create *create);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/lightnvm/core.c (0)
Location: drivers/lightnvm/core.c:309
Inline: False
```
**Symbols:**

```
ffffffff81705080-ffffffff81705965: nvm_create_tgt (STB_LOCAL)
ffffffff817060c7-ffffffff817061c6: nvm_create_tgt.cold (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
