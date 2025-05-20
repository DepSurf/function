# Function: <code>__set_oom_adj</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int __set_oom_adj(struct file *file, int oom_adj, bool legacy);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/proc/base.c (ffffffff812a9960)
Location: fs/proc/base.c:1044
Inline: False
Direct callers:
  - fs/proc/base.c:oom_score_adj_write
  - fs/proc/base.c:oom_adj_write
```
**Symbols:**

```
ffffffff812a9960-ffffffff812a9d15: __set_oom_adj (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int __set_oom_adj(struct file *file, int oom_adj, bool legacy);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/proc/base.c (ffffffff812bf280)
Location: fs/proc/base.c:1062
Inline: False
Direct callers:
  - fs/proc/base.c:oom_score_adj_write
  - fs/proc/base.c:oom_adj_write
```
**Symbols:**

```
ffffffff812bf280-ffffffff812bf635: __set_oom_adj (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int __set_oom_adj(struct file *file, int oom_adj, bool legacy);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/proc/base.c (ffffffff812cbeb0)
Location: fs/proc/base.c:1036
Inline: False
Direct callers:
  - fs/proc/base.c:oom_score_adj_write
  - fs/proc/base.c:oom_adj_write
```
**Symbols:**

```
ffffffff812cbeb0-ffffffff812cc238: __set_oom_adj (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int __set_oom_adj(struct file *file, int oom_adj, bool legacy);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/proc/base.c (ffffffff812f0650)
Location: fs/proc/base.c:1036
Inline: False
Direct callers:
  - fs/proc/base.c:oom_score_adj_write
  - fs/proc/base.c:oom_adj_write
```
**Symbols:**

```
ffffffff812f0650-ffffffff812f09d9: __set_oom_adj (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Transformation ⚠️</summary>

```c
int __set_oom_adj(struct file *file, int oom_adj, bool legacy);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/proc/base.c (0)
Location: fs/proc/base.c:1004
Inline: False
Direct callers:
  - fs/proc/base.c:oom_score_adj_write
  - fs/proc/base.c:oom_adj_write
```
**Symbols:**

```
ffffffff8131dd50-ffffffff8131e046: __set_oom_adj (STB_LOCAL)
ffffffff8131fe40-ffffffff8131fefc: __set_oom_adj.cold.25 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Transformation ⚠️</summary>

```c
int __set_oom_adj(struct file *file, int oom_adj, bool legacy);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/proc/base.c (0)
Location: fs/proc/base.c:1024
Inline: False
Direct callers:
  - fs/proc/base.c:oom_score_adj_write
  - fs/proc/base.c:oom_adj_write
```
**Symbols:**

```
ffffffff81335150-ffffffff81335473: __set_oom_adj (STB_LOCAL)
ffffffff81336fa0-ffffffff81336fd8: __set_oom_adj.cold.25 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
int __set_oom_adj(struct file *file, int oom_adj, bool legacy);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/proc/base.c (0)
Location: fs/proc/base.c:1037
Inline: False
Direct callers:
  - fs/proc/base.c:oom_score_adj_write
  - fs/proc/base.c:oom_adj_write
```
**Symbols:**

```
ffffffff8135cca0-ffffffff8135cfe4: __set_oom_adj (STB_LOCAL)
ffffffff8135f0d6-ffffffff8135f10e: __set_oom_adj.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
int __set_oom_adj(struct file *file, int oom_adj, bool legacy);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/proc/base.c (0)
Location: fs/proc/base.c:1037
Inline: False
Direct callers:
  - fs/proc/base.c:oom_score_adj_write
  - fs/proc/base.c:oom_adj_write
```
**Symbols:**

```
ffffffff81375410-ffffffff81375754: __set_oom_adj (STB_LOCAL)
ffffffff81377336-ffffffff8137736e: __set_oom_adj.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/proc/base.c (0)
Location: fs/proc/base.c:1047
Inline: True
Direct callers:
  - fs/proc/base.c:oom_score_adj_write
  - fs/proc/base.c:oom_adj_write
```
**Symbols:**

```
ffffffff813bde90-ffffffff813be1f7: __set_oom_adj.isra.0 (STB_LOCAL)
ffffffff813c0091-ffffffff813c00c9: __set_oom_adj.isra.0.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/proc/base.c (0)
Location: fs/proc/base.c:1058
Inline: True
Direct callers:
  - fs/proc/base.c:oom_score_adj_write
  - fs/proc/base.c:oom_adj_write
```
**Symbols:**

```
ffffffff813cfbe0-ffffffff813cff43: __set_oom_adj.isra.0 (STB_LOCAL)
ffffffff81bebcc9-ffffffff81bebd01: __set_oom_adj.isra.0.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/proc/base.c (0)
Location: fs/proc/base.c:1057
Inline: True
Direct callers:
  - fs/proc/base.c:oom_score_adj_write
  - fs/proc/base.c:oom_adj_write
```
**Symbols:**

```
ffffffff813d6ac0-ffffffff813d6e23: __set_oom_adj.isra.0 (STB_LOCAL)
ffffffff81bddcd8-ffffffff81bddd10: __set_oom_adj.isra.0.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/proc/base.c (0)
Location: fs/proc/base.c:1061
Inline: True
Direct callers:
  - fs/proc/base.c:oom_score_adj_write
  - fs/proc/base.c:oom_adj_write
```
**Symbols:**

```
ffffffff814281f0-ffffffff81428562: __set_oom_adj.isra.0 (STB_LOCAL)
ffffffff81cc80da-ffffffff81cc8127: __set_oom_adj.isra.0.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/proc/base.c (0)
Location: fs/proc/base.c:1060
Inline: True
Direct callers:
  - fs/proc/base.c:oom_score_adj_write
  - fs/proc/base.c:oom_adj_write
```
**Symbols:**

```
ffffffff814a1430-ffffffff814a1814: __set_oom_adj.isra.0 (STB_LOCAL)
ffffffff81e7ac82-ffffffff81e7acec: __set_oom_adj.isra.0.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/proc/base.c (0)
Location: fs/proc/base.c:1061
Inline: True
Direct callers:
  - fs/proc/base.c:oom_score_adj_write
  - fs/proc/base.c:oom_adj_write
```
**Symbols:**

```
ffffffff81536450-ffffffff8153684c: __set_oom_adj.isra.0 (STB_LOCAL)
ffffffff8206bb32-ffffffff8206bb47: __set_oom_adj.isra.0.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/proc/base.c (0)
Location: fs/proc/base.c:1061
Inline: True
Direct callers:
  - fs/proc/base.c:oom_score_adj_write
  - fs/proc/base.c:oom_adj_write
```
**Symbols:**

```
ffffffff8156e610-ffffffff8156ea0a: __set_oom_adj.isra.0 (STB_LOCAL)
ffffffff820eb9b4-ffffffff820eb9c9: __set_oom_adj.isra.0.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/proc/base.c (0)
Location: fs/proc/base.c:1061
Inline: True
Direct callers:
  - fs/proc/base.c:oom_score_adj_write
  - fs/proc/base.c:oom_adj_write
```
**Symbols:**

```
ffffffff815a6fd0-ffffffff815a73ca: __set_oom_adj.isra.0 (STB_LOCAL)
ffffffff821c8c2d-ffffffff821c8c42: __set_oom_adj.isra.0.cold (STB_LOCAL)
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
int __set_oom_adj(struct file *file, int oom_adj, bool legacy);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/proc/base.c (ffff80001043f598)
Location: fs/proc/base.c:1037
Inline: False
Direct callers:
  - fs/proc/base.c:oom_score_adj_write
  - fs/proc/base.c:oom_adj_write
```
**Symbols:**

```
ffff80001043f598-ffff80001043f954: __set_oom_adj (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int __set_oom_adj(struct file *file, int oom_adj, bool legacy);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/proc/base.c (c0605fc8)
Location: fs/proc/base.c:1037
Inline: False
Direct callers:
  - fs/proc/base.c:oom_score_adj_write
  - fs/proc/base.c:oom_adj_write
  - fs/proc/base.c:oom_adj_write
```
**Symbols:**

```
c0605fc8-c06063ac: __set_oom_adj (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int __set_oom_adj(struct file *file, int oom_adj, bool legacy);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/proc/base.c (c000000000554a90)
Location: fs/proc/base.c:1037
Inline: False
Direct callers:
  - fs/proc/base.c:oom_score_adj_write
  - fs/proc/base.c:oom_adj_write
```
**Symbols:**

```
c000000000554a90-c000000000554f68: __set_oom_adj (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int __set_oom_adj(struct file *file, int oom_adj, bool legacy);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/proc/base.c (ffffffe0002d7246)
Location: fs/proc/base.c:1037
Inline: False
Direct callers:
  - fs/proc/base.c:oom_score_adj_write
  - fs/proc/base.c:oom_adj_write
```
**Symbols:**

```
ffffffe0002d7246-ffffffe0002d757a: __set_oom_adj (STB_LOCAL)
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
int __set_oom_adj(struct file *file, int oom_adj, bool legacy);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/proc/base.c (0)
Location: fs/proc/base.c:1037
Inline: False
Direct callers:
  - fs/proc/base.c:oom_score_adj_write
  - fs/proc/base.c:oom_adj_write
```
**Symbols:**

```
ffffffff8136d9f0-ffffffff8136dd34: __set_oom_adj (STB_LOCAL)
ffffffff8136f916-ffffffff8136f94e: __set_oom_adj.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Transformation ⚠️</summary>

```c
int __set_oom_adj(struct file *file, int oom_adj, bool legacy);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/proc/base.c (0)
Location: fs/proc/base.c:1037
Inline: False
Direct callers:
  - fs/proc/base.c:oom_score_adj_write
  - fs/proc/base.c:oom_adj_write
```
**Symbols:**

```
ffffffff8135e480-ffffffff8135e7c4: __set_oom_adj (STB_LOCAL)
ffffffff813603a6-ffffffff813603de: __set_oom_adj.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Transformation ⚠️</summary>

```c
int __set_oom_adj(struct file *file, int oom_adj, bool legacy);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/proc/base.c (0)
Location: fs/proc/base.c:1037
Inline: False
Direct callers:
  - fs/proc/base.c:oom_score_adj_write
  - fs/proc/base.c:oom_adj_write
```
**Symbols:**

```
ffffffff8136b4c0-ffffffff8136b804: __set_oom_adj (STB_LOCAL)
ffffffff8136d3e6-ffffffff8136d41e: __set_oom_adj.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
int __set_oom_adj(struct file *file, int oom_adj, bool legacy);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/proc/base.c (0)
Location: fs/proc/base.c:1037
Inline: False
Direct callers:
  - fs/proc/base.c:oom_score_adj_write
  - fs/proc/base.c:oom_adj_write
```
**Symbols:**

```
ffffffff8137ec10-ffffffff8137efac: __set_oom_adj (STB_LOCAL)
ffffffff81380d0c-ffffffff81380d45: __set_oom_adj.cold (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
