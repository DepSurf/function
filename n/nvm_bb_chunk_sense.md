# Function: <code>nvm_bb_chunk_sense</code>

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
int nvm_bb_chunk_sense(struct nvm_dev *dev, struct ppa_addr ppa);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/lightnvm/core.c (ffffffff81698c70)
Location: drivers/lightnvm/core.c:797
Inline: False
Direct callers:
  - drivers/lightnvm/core.c:nvm_get_bb_meta
  - drivers/lightnvm/core.c:nvm_get_bb_meta
  - drivers/lightnvm/core.c:nvm_get_bb_meta
```
**Symbols:**

```
ffffffff81698c70-ffffffff81698e88: nvm_bb_chunk_sense (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int nvm_bb_chunk_sense(struct nvm_dev *dev, struct ppa_addr ppa);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/lightnvm/core.c (ffffffff816d16c0)
Location: drivers/lightnvm/core.c:799
Inline: False
Direct callers:
  - drivers/lightnvm/core.c:nvm_get_bb_meta
  - drivers/lightnvm/core.c:nvm_get_bb_meta
  - drivers/lightnvm/core.c:nvm_get_bb_meta
```
**Symbols:**

```
ffffffff816d16c0-ffffffff816d18ee: nvm_bb_chunk_sense (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int nvm_bb_chunk_sense(struct nvm_dev *dev, struct ppa_addr ppa);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/lightnvm/core.c (ffffffff816f5670)
Location: drivers/lightnvm/core.c:829
Inline: False
Direct callers:
  - drivers/lightnvm/core.c:nvm_get_bb_meta
  - drivers/lightnvm/core.c:nvm_get_bb_meta
  - drivers/lightnvm/core.c:nvm_get_bb_meta
```
**Symbols:**

```
ffffffff816f5670-ffffffff816f58b3: nvm_bb_chunk_sense (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int nvm_bb_chunk_sense(struct nvm_dev *dev, struct ppa_addr ppa);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/lightnvm/core.c (ffffffff817aded0)
Location: drivers/lightnvm/core.c:828
Inline: False
Direct callers:
  - drivers/lightnvm/core.c:nvm_bb_chunk_scan
  - drivers/lightnvm/core.c:nvm_bb_chunk_scan
  - drivers/lightnvm/core.c:nvm_bb_chunk_scan
```
**Symbols:**

```
ffffffff817aded0-ffffffff817ae161: nvm_bb_chunk_sense (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int nvm_bb_chunk_sense(struct nvm_dev *dev, struct ppa_addr ppa);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/lightnvm/core.c (ffffffff817c2a50)
Location: drivers/lightnvm/core.c:824
Inline: False
Direct callers:
  - drivers/lightnvm/core.c:nvm_bb_chunk_scan
  - drivers/lightnvm/core.c:nvm_bb_chunk_scan
  - drivers/lightnvm/core.c:nvm_bb_chunk_scan
```
**Symbols:**

```
ffffffff817c2a50-ffffffff817c2d00: nvm_bb_chunk_sense (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int nvm_bb_chunk_sense(struct nvm_dev *dev, struct ppa_addr ppa);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/lightnvm/core.c (ffffffff817a5f10)
Location: drivers/lightnvm/core.c:824
Inline: False
```
**Symbols:**

```
ffffffff817a5f10-ffffffff817a619c: nvm_bb_chunk_sense (STB_LOCAL)
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
int nvm_bb_chunk_sense(struct nvm_dev *dev, struct ppa_addr ppa);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/lightnvm/core.c (ffff8000108dec68)
Location: drivers/lightnvm/core.c:829
Inline: False
Direct callers:
  - drivers/lightnvm/core.c:nvm_get_bb_meta
  - drivers/lightnvm/core.c:nvm_get_bb_meta
  - drivers/lightnvm/core.c:nvm_get_bb_meta
```
**Symbols:**

```
ffff8000108dec68-ffff8000108dee5c: nvm_bb_chunk_sense (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int nvm_bb_chunk_sense(struct nvm_dev *dev, struct ppa_addr ppa);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/lightnvm/core.c (c09cdd70)
Location: drivers/lightnvm/core.c:829
Inline: False
Direct callers:
  - drivers/lightnvm/core.c:nvm_get_bb_meta
  - drivers/lightnvm/core.c:nvm_get_bb_meta
  - drivers/lightnvm/core.c:nvm_get_bb_meta
```
**Symbols:**

```
c09cdd70-c09ce0cc: nvm_bb_chunk_sense (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int nvm_bb_chunk_sense(struct nvm_dev *dev, struct ppa_addr ppa);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/lightnvm/core.c (c000000000972aa0)
Location: drivers/lightnvm/core.c:829
Inline: False
Direct callers:
  - drivers/lightnvm/core.c:nvm_get_bb_meta
  - drivers/lightnvm/core.c:nvm_get_bb_meta
  - drivers/lightnvm/core.c:nvm_get_bb_meta
```
**Symbols:**

```
c000000000972aa0-c000000000972ce0: nvm_bb_chunk_sense (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int nvm_bb_chunk_sense(struct nvm_dev *dev, struct ppa_addr ppa);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/lightnvm/core.c (ffffffe000574ef4)
Location: drivers/lightnvm/core.c:829
Inline: False
Direct callers:
  - drivers/lightnvm/core.c:nvm_get_bb_meta
  - drivers/lightnvm/core.c:nvm_get_bb_meta
  - drivers/lightnvm/core.c:nvm_get_bb_meta
```
**Symbols:**

```
ffffffe000574ef4-ffffffe0005750a6: nvm_bb_chunk_sense (STB_LOCAL)
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
int nvm_bb_chunk_sense(struct nvm_dev *dev, struct ppa_addr ppa);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/lightnvm/core.c (ffffffff816bae60)
Location: drivers/lightnvm/core.c:829
Inline: False
Direct callers:
  - drivers/lightnvm/core.c:nvm_get_bb_meta
  - drivers/lightnvm/core.c:nvm_get_bb_meta
  - drivers/lightnvm/core.c:nvm_get_bb_meta
```
**Symbols:**

```
ffffffff816bae60-ffffffff816bb0a3: nvm_bb_chunk_sense (STB_LOCAL)
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
int nvm_bb_chunk_sense(struct nvm_dev *dev, struct ppa_addr ppa);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/lightnvm/core.c (ffffffff816e9330)
Location: drivers/lightnvm/core.c:829
Inline: False
Direct callers:
  - drivers/lightnvm/core.c:nvm_get_bb_meta
  - drivers/lightnvm/core.c:nvm_get_bb_meta
  - drivers/lightnvm/core.c:nvm_get_bb_meta
```
**Symbols:**

```
ffffffff816e9330-ffffffff816e9573: nvm_bb_chunk_sense (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int nvm_bb_chunk_sense(struct nvm_dev *dev, struct ppa_addr ppa);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/lightnvm/core.c (ffffffff81703b70)
Location: drivers/lightnvm/core.c:829
Inline: False
Direct callers:
  - drivers/lightnvm/core.c:nvm_get_bb_meta
  - drivers/lightnvm/core.c:nvm_get_bb_meta
  - drivers/lightnvm/core.c:nvm_get_bb_meta
```
**Symbols:**

```
ffffffff81703b70-ffffffff81703db3: nvm_bb_chunk_sense (STB_LOCAL)
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
