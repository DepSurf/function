# Function: <code>nvm_submit_io_wait</code>

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
<summary>In <code>5.4</code>: ✅</summary>

```c
int nvm_submit_io_wait(struct nvm_dev *dev, struct nvm_rq *rqd, void *buf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/lightnvm/core.c (ffffffff816f54e0)
Location: drivers/lightnvm/core.c:767
Inline: False
Direct callers:
  - drivers/lightnvm/core.c:nvm_bb_chunk_sense
  - drivers/lightnvm/core.c:nvm_submit_io_sync
```
**Symbols:**

```
ffffffff816f54e0-ffffffff816f5566: nvm_submit_io_wait (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/lightnvm/core.c (ffffffff817ae026)
Location: drivers/lightnvm/core.c:766
Inline: True
Inline callers:
  - drivers/lightnvm/core.c:nvm_bb_chunk_sense
  - drivers/lightnvm/core.c:nvm_submit_io_sync
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/lightnvm/core.c (ffffffff817c2ba6)
Location: drivers/lightnvm/core.c:762
Inline: True
Inline callers:
  - drivers/lightnvm/core.c:nvm_bb_chunk_sense
  - drivers/lightnvm/core.c:nvm_submit_io_sync
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/lightnvm/core.c (ffffffff817a6066)
Location: drivers/lightnvm/core.c:762
Inline: True
Inline callers:
  - drivers/lightnvm/core.c:nvm_bb_chunk_sense
  - drivers/lightnvm/core.c:nvm_submit_io_sync
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
int nvm_submit_io_wait(struct nvm_dev *dev, struct nvm_rq *rqd, void *buf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/lightnvm/core.c (ffff8000108deb80)
Location: drivers/lightnvm/core.c:767
Inline: False
Direct callers:
  - drivers/lightnvm/core.c:nvm_bb_chunk_sense
  - drivers/lightnvm/core.c:nvm_submit_io_sync
```
**Symbols:**

```
ffff8000108deb80-ffff8000108dec34: nvm_submit_io_wait (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int nvm_submit_io_wait(struct nvm_dev *dev, struct nvm_rq *rqd, void *buf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/lightnvm/core.c (c09cdbe0)
Location: drivers/lightnvm/core.c:767
Inline: False
Direct callers:
  - drivers/lightnvm/core.c:nvm_bb_chunk_sense
  - drivers/lightnvm/core.c:nvm_submit_io_sync
```
**Symbols:**

```
c09cdbe0-c09cdc7c: nvm_submit_io_wait (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int nvm_submit_io_wait(struct nvm_dev *dev, struct nvm_rq *rqd, void *buf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/lightnvm/core.c (c000000000972700)
Location: drivers/lightnvm/core.c:767
Inline: False
Direct callers:
  - drivers/lightnvm/core.c:nvm_bb_chunk_sense
  - drivers/lightnvm/core.c:nvm_submit_io_sync
  - drivers/lightnvm/core.c:nvm_submit_io_sync
```
**Symbols:**

```
c000000000972700-c0000000009727c0: nvm_submit_io_wait (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int nvm_submit_io_wait(struct nvm_dev *dev, struct nvm_rq *rqd, void *buf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/lightnvm/core.c (ffffffe000574dbc)
Location: drivers/lightnvm/core.c:767
Inline: False
Direct callers:
  - drivers/lightnvm/core.c:nvm_bb_chunk_sense
  - drivers/lightnvm/core.c:nvm_submit_io_sync
```
**Symbols:**

```
ffffffe000574dbc-ffffffe000574e30: nvm_submit_io_wait (STB_LOCAL)
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
int nvm_submit_io_wait(struct nvm_dev *dev, struct nvm_rq *rqd, void *buf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/lightnvm/core.c (ffffffff816bacd0)
Location: drivers/lightnvm/core.c:767
Inline: False
Direct callers:
  - drivers/lightnvm/core.c:nvm_bb_chunk_sense
  - drivers/lightnvm/core.c:nvm_submit_io_sync
```
**Symbols:**

```
ffffffff816bacd0-ffffffff816bad56: nvm_submit_io_wait (STB_LOCAL)
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
int nvm_submit_io_wait(struct nvm_dev *dev, struct nvm_rq *rqd, void *buf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/lightnvm/core.c (ffffffff816e91a0)
Location: drivers/lightnvm/core.c:767
Inline: False
Direct callers:
  - drivers/lightnvm/core.c:nvm_bb_chunk_sense
  - drivers/lightnvm/core.c:nvm_submit_io_sync
```
**Symbols:**

```
ffffffff816e91a0-ffffffff816e9226: nvm_submit_io_wait (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int nvm_submit_io_wait(struct nvm_dev *dev, struct nvm_rq *rqd, void *buf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/lightnvm/core.c (ffffffff817039e0)
Location: drivers/lightnvm/core.c:767
Inline: False
Direct callers:
  - drivers/lightnvm/core.c:nvm_bb_chunk_sense
  - drivers/lightnvm/core.c:nvm_submit_io_sync
```
**Symbols:**

```
ffffffff817039e0-ffffffff81703a66: nvm_submit_io_wait (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
