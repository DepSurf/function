# Function: <code>nvm_submit_io</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int nvm_submit_io(struct nvm_dev *dev, struct nvm_rq *rqd);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/lightnvm/core.c (ffffffff81542960)
Location: drivers/lightnvm/core.c:201
Inline: False
```
**Symbols:**

```
ffffffff81542960-ffffffff81542972: nvm_submit_io (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int nvm_submit_io(struct nvm_dev *dev, struct nvm_rq *rqd);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/lightnvm/core.c (ffffffff815942a0)
Location: drivers/lightnvm/core.c:199
Inline: False
```
**Symbols:**

```
ffffffff815942a0-ffffffff815942b2: nvm_submit_io (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int nvm_submit_io(struct nvm_tgt_dev *tgt_dev, struct nvm_rq *rqd);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/lightnvm/core.c (ffffffff815c1b20)
Location: drivers/lightnvm/core.c:261
Inline: False
```
**Symbols:**

```
ffffffff815c1b20-ffffffff815c1b39: nvm_submit_io (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int nvm_submit_io(struct nvm_tgt_dev *tgt_dev, struct nvm_rq *rqd);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/lightnvm/core.c (ffffffff815d7940)
Location: drivers/lightnvm/core.c:641
Inline: False
Direct callers:
  - drivers/lightnvm/core.c:nvm_erase_sync
```
**Symbols:**

```
ffffffff815d7940-ffffffff815d79a7: nvm_submit_io (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int nvm_submit_io(struct nvm_tgt_dev *tgt_dev, struct nvm_rq *rqd);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/lightnvm/core.c (ffffffff8163e750)
Location: drivers/lightnvm/core.c:689
Inline: False
```
**Symbols:**

```
ffffffff8163e750-ffffffff8163e7bd: nvm_submit_io (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int nvm_submit_io(struct nvm_tgt_dev *tgt_dev, struct nvm_rq *rqd);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/lightnvm/core.c (ffffffff81679d70)
Location: drivers/lightnvm/core.c:755
Inline: False
```
**Symbols:**

```
ffffffff81679d70-ffffffff81679de8: nvm_submit_io (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int nvm_submit_io(struct nvm_tgt_dev *tgt_dev, struct nvm_rq *rqd);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/lightnvm/core.c (ffffffff81699460)
Location: drivers/lightnvm/core.c:732
Inline: False
```
**Symbols:**

```
ffffffff81699460-ffffffff81699537: nvm_submit_io (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int nvm_submit_io(struct nvm_tgt_dev *tgt_dev, struct nvm_rq *rqd);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/lightnvm/core.c (ffffffff816d1f00)
Location: drivers/lightnvm/core.c:734
Inline: False
```
**Symbols:**

```
ffffffff816d1f00-ffffffff816d1fd3: nvm_submit_io (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int nvm_submit_io(struct nvm_tgt_dev *tgt_dev, struct nvm_rq *rqd, void *buf);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/lightnvm/core.c (ffffffff816f5df0)
Location: drivers/lightnvm/core.c:739
Inline: False
```
**Symbols:**

```
ffffffff816f5df0-ffffffff816f5ecb: nvm_submit_io (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int nvm_submit_io(struct nvm_tgt_dev *tgt_dev, struct nvm_rq *rqd, void *buf);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/lightnvm/core.c (ffffffff817aeee0)
Location: drivers/lightnvm/core.c:738
Inline: False
```
**Symbols:**

```
ffffffff817aeee0-ffffffff817aefcf: nvm_submit_io (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int nvm_submit_io(struct nvm_tgt_dev *tgt_dev, struct nvm_rq *rqd, void *buf);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/lightnvm/core.c (ffffffff817c3a60)
Location: drivers/lightnvm/core.c:734
Inline: False
```
**Symbols:**

```
ffffffff817c3a60-ffffffff817c3b4f: nvm_submit_io (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int nvm_submit_io(struct nvm_tgt_dev *tgt_dev, struct nvm_rq *rqd, void *buf);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/lightnvm/core.c (ffffffff817a6c30)
Location: drivers/lightnvm/core.c:734
Inline: False
```
**Symbols:**

```
ffffffff817a6c30-ffffffff817a6d1f: nvm_submit_io (STB_GLOBAL)
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
int nvm_submit_io(struct nvm_tgt_dev *tgt_dev, struct nvm_rq *rqd, void *buf);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/lightnvm/core.c (ffff8000108df2b0)
Location: drivers/lightnvm/core.c:739
Inline: False
```
**Symbols:**

```
ffff8000108df2b0-ffff8000108df3bc: nvm_submit_io (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int nvm_submit_io(struct nvm_tgt_dev *tgt_dev, struct nvm_rq *rqd, void *buf);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/lightnvm/core.c (c09ce858)
Location: drivers/lightnvm/core.c:739
Inline: False
```
**Symbols:**

```
c09ce858-c09ce934: nvm_submit_io (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int nvm_submit_io(struct nvm_tgt_dev *tgt_dev, struct nvm_rq *rqd, void *buf);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/lightnvm/core.c (c000000000973400)
Location: drivers/lightnvm/core.c:739
Inline: False
```
**Symbols:**

```
c000000000973400-c000000000973570: nvm_submit_io (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int nvm_submit_io(struct nvm_tgt_dev *tgt_dev, struct nvm_rq *rqd, void *buf);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/lightnvm/core.c (ffffffe000575746)
Location: drivers/lightnvm/core.c:739
Inline: False
```
**Symbols:**

```
ffffffe000575746-ffffffe000575820: nvm_submit_io (STB_GLOBAL)
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
int nvm_submit_io(struct nvm_tgt_dev *tgt_dev, struct nvm_rq *rqd, void *buf);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/lightnvm/core.c (ffffffff816bb5e0)
Location: drivers/lightnvm/core.c:739
Inline: False
```
**Symbols:**

```
ffffffff816bb5e0-ffffffff816bb6bb: nvm_submit_io (STB_GLOBAL)
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
int nvm_submit_io(struct nvm_tgt_dev *tgt_dev, struct nvm_rq *rqd, void *buf);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/lightnvm/core.c (ffffffff816e9ab0)
Location: drivers/lightnvm/core.c:739
Inline: False
```
**Symbols:**

```
ffffffff816e9ab0-ffffffff816e9b8b: nvm_submit_io (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int nvm_submit_io(struct nvm_tgt_dev *tgt_dev, struct nvm_rq *rqd, void *buf);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/lightnvm/core.c (ffffffff817042f0)
Location: drivers/lightnvm/core.c:739
Inline: False
```
**Symbols:**

```
ffffffff817042f0-ffffffff817043cb: nvm_submit_io (STB_GLOBAL)
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
<code>struct nvm_tgt_dev *tgt_dev</code>
</li>
<li>
<b>Param removed. </b>
<code>struct nvm_dev *dev</code>
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
<details>
<summary>Changed between <code>5.3</code> and <code>5.4</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>void *buf</code>
</li>
</ul>
</details>
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
