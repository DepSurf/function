# Function: <code>nvm_get_bb_meta</code>

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
int nvm_get_bb_meta(struct nvm_dev *dev, sector_t slba, int nchks, struct nvm_chk_meta *meta);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/lightnvm/core.c (ffffffff816997f0)
Location: drivers/lightnvm/core.c:970
Inline: False
Direct callers:
  - drivers/lightnvm/core.c:nvm_get_chunk_meta
```
**Symbols:**

```
ffffffff816997f0-ffffffff81699e28: nvm_get_bb_meta (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int nvm_get_bb_meta(struct nvm_dev *dev, sector_t slba, int nchks, struct nvm_chk_meta *meta);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/lightnvm/core.c (ffffffff816d2390)
Location: drivers/lightnvm/core.c:972
Inline: False
Direct callers:
  - drivers/lightnvm/core.c:nvm_get_chunk_meta
```
**Symbols:**

```
ffffffff816d2390-ffffffff816d29be: nvm_get_bb_meta (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int nvm_get_bb_meta(struct nvm_dev *dev, sector_t slba, int nchks, struct nvm_chk_meta *meta);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/lightnvm/core.c (ffffffff816f6270)
Location: drivers/lightnvm/core.c:1002
Inline: False
Direct callers:
  - drivers/lightnvm/core.c:nvm_get_chunk_meta
```
**Symbols:**

```
ffffffff816f6270-ffffffff816f689e: nvm_get_bb_meta (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int nvm_get_bb_meta(struct nvm_dev *dev, sector_t slba, int nchks, struct nvm_chk_meta *meta);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/lightnvm/core.c (ffffffff817af110)
Location: drivers/lightnvm/core.c:1001
Inline: False
Direct callers:
  - drivers/lightnvm/core.c:nvm_get_chunk_meta
```
**Symbols:**

```
ffffffff817af110-ffffffff817af2a3: nvm_get_bb_meta (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int nvm_get_bb_meta(struct nvm_dev *dev, sector_t slba, int nchks, struct nvm_chk_meta *meta);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/lightnvm/core.c (ffffffff817c3c90)
Location: drivers/lightnvm/core.c:996
Inline: False
Direct callers:
  - drivers/lightnvm/core.c:nvm_get_chunk_meta
```
**Symbols:**

```
ffffffff817c3c90-ffffffff817c3e21: nvm_get_bb_meta (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int nvm_get_bb_meta(struct nvm_dev *dev, sector_t slba, int nchks, struct nvm_chk_meta *meta);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/lightnvm/core.c (ffffffff817a6e60)
Location: drivers/lightnvm/core.c:996
Inline: False
Direct callers:
  - drivers/lightnvm/core.c:nvm_get_chunk_meta
```
**Symbols:**

```
ffffffff817a6e60-ffffffff817a7134: nvm_get_bb_meta (STB_LOCAL)
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
int nvm_get_bb_meta(struct nvm_dev *dev, sector_t slba, int nchks, struct nvm_chk_meta *meta);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/lightnvm/core.c (ffff8000108df9c8)
Location: drivers/lightnvm/core.c:1002
Inline: False
Direct callers:
  - drivers/lightnvm/core.c:nvm_get_chunk_meta
```
**Symbols:**

```
ffff8000108df9c8-ffff8000108dff38: nvm_get_bb_meta (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int nvm_get_bb_meta(struct nvm_dev *dev, sector_t slba, int nchks, struct nvm_chk_meta *meta);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/lightnvm/core.c (c09cebec)
Location: drivers/lightnvm/core.c:1002
Inline: False
Direct callers:
  - drivers/lightnvm/core.c:nvm_get_chunk_meta
```
**Symbols:**

```
c09cebec-c09cf1b4: nvm_get_bb_meta (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int nvm_get_bb_meta(struct nvm_dev *dev, sector_t slba, int nchks, struct nvm_chk_meta *meta);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/lightnvm/core.c (c000000000973970)
Location: drivers/lightnvm/core.c:1002
Inline: False
Direct callers:
  - drivers/lightnvm/core.c:nvm_get_chunk_meta
```
**Symbols:**

```
c000000000973970-c000000000973fd4: nvm_get_bb_meta (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int nvm_get_bb_meta(struct nvm_dev *dev, sector_t slba, int nchks, struct nvm_chk_meta *meta);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/lightnvm/core.c (ffffffe000575a82)
Location: drivers/lightnvm/core.c:1002
Inline: False
Direct callers:
  - drivers/lightnvm/core.c:nvm_get_chunk_meta
```
**Symbols:**

```
ffffffe000575a82-ffffffe000575f9a: nvm_get_bb_meta (STB_LOCAL)
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
int nvm_get_bb_meta(struct nvm_dev *dev, sector_t slba, int nchks, struct nvm_chk_meta *meta);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/lightnvm/core.c (ffffffff816bba60)
Location: drivers/lightnvm/core.c:1002
Inline: False
Direct callers:
  - drivers/lightnvm/core.c:nvm_get_chunk_meta
```
**Symbols:**

```
ffffffff816bba60-ffffffff816bc08e: nvm_get_bb_meta (STB_LOCAL)
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
int nvm_get_bb_meta(struct nvm_dev *dev, sector_t slba, int nchks, struct nvm_chk_meta *meta);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/lightnvm/core.c (ffffffff816e9f30)
Location: drivers/lightnvm/core.c:1002
Inline: False
Direct callers:
  - drivers/lightnvm/core.c:nvm_get_chunk_meta
```
**Symbols:**

```
ffffffff816e9f30-ffffffff816ea55e: nvm_get_bb_meta (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int nvm_get_bb_meta(struct nvm_dev *dev, sector_t slba, int nchks, struct nvm_chk_meta *meta);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/lightnvm/core.c (ffffffff81704770)
Location: drivers/lightnvm/core.c:1002
Inline: False
Direct callers:
  - drivers/lightnvm/core.c:nvm_get_chunk_meta
```
**Symbols:**

```
ffffffff81704770-ffffffff81704d9e: nvm_get_bb_meta (STB_LOCAL)
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
