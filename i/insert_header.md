# Function: <code>insert_header</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int insert_header(struct ctl_dir *dir, struct ctl_table_header *header);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/proc/proc_sysctl.c (ffffffff812854c0)
Location: fs/proc/proc_sysctl.c:207
Inline: False
Direct callers:
  - fs/proc/proc_sysctl.c:insert_header
  - fs/proc/proc_sysctl.c:__register_sysctl_table
  - fs/proc/proc_sysctl.c:__register_sysctl_table
```
**Symbols:**

```
ffffffff812854c0-ffffffff8128591c: insert_header (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int insert_header(struct ctl_dir *dir, struct ctl_table_header *header);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/proc/proc_sysctl.c (ffffffff812b2600)
Location: fs/proc/proc_sysctl.c:207
Inline: False
Direct callers:
  - fs/proc/proc_sysctl.c:__register_sysctl_table
  - fs/proc/proc_sysctl.c:__register_sysctl_table
  - fs/proc/proc_sysctl.c:insert_header
```
**Symbols:**

```
ffffffff812b2600-ffffffff812b2a52: insert_header (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int insert_header(struct ctl_dir *dir, struct ctl_table_header *header);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/proc/proc_sysctl.c (ffffffff812c7e50)
Location: fs/proc/proc_sysctl.c:207
Inline: False
Direct callers:
  - fs/proc/proc_sysctl.c:__register_sysctl_table
  - fs/proc/proc_sysctl.c:__register_sysctl_table
  - fs/proc/proc_sysctl.c:insert_header
```
**Symbols:**

```
ffffffff812c7e50-ffffffff812c82a2: insert_header (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int insert_header(struct ctl_dir *dir, struct ctl_table_header *header);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/proc/proc_sysctl.c (ffffffff812d51d0)
Location: fs/proc/proc_sysctl.c:209
Inline: False
Direct callers:
  - fs/proc/proc_sysctl.c:__register_sysctl_table
  - fs/proc/proc_sysctl.c:__register_sysctl_table
  - fs/proc/proc_sysctl.c:insert_header
```
**Symbols:**

```
ffffffff812d51d0-ffffffff812d5614: insert_header (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int insert_header(struct ctl_dir *dir, struct ctl_table_header *header);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/proc/proc_sysctl.c (ffffffff812f9a10)
Location: fs/proc/proc_sysctl.c:210
Inline: False
Direct callers:
  - fs/proc/proc_sysctl.c:__register_sysctl_table
  - fs/proc/proc_sysctl.c:__register_sysctl_table
  - fs/proc/proc_sysctl.c:insert_header
```
**Symbols:**

```
ffffffff812f9a10-ffffffff812f9e54: insert_header (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Transformation ⚠️</summary>

```c
int insert_header(struct ctl_dir *dir, struct ctl_table_header *header);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/proc/proc_sysctl.c (0)
Location: fs/proc/proc_sysctl.c:210
Inline: False
Direct callers:
  - fs/proc/proc_sysctl.c:__register_sysctl_table
  - fs/proc/proc_sysctl.c:__register_sysctl_table
  - fs/proc/proc_sysctl.c:insert_header
```
**Symbols:**

```
ffffffff813267d0-ffffffff81326bd5: insert_header (STB_LOCAL)
ffffffff81327bc2-ffffffff81327c05: insert_header.cold.33 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Transformation ⚠️</summary>

```c
int insert_header(struct ctl_dir *dir, struct ctl_table_header *header);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/proc/proc_sysctl.c (0)
Location: fs/proc/proc_sysctl.c:210
Inline: False
Direct callers:
  - fs/proc/proc_sysctl.c:__register_sysctl_table
  - fs/proc/proc_sysctl.c:__register_sysctl_table
  - fs/proc/proc_sysctl.c:insert_header
```
**Symbols:**

```
ffffffff8133d620-ffffffff8133da28: insert_header (STB_LOCAL)
ffffffff8133ed52-ffffffff8133ed95: insert_header.cold.33 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
int insert_header(struct ctl_dir *dir, struct ctl_table_header *header);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/proc/proc_sysctl.c (0)
Location: fs/proc/proc_sysctl.c:215
Inline: False
Direct callers:
  - fs/proc/proc_sysctl.c:__register_sysctl_table
  - fs/proc/proc_sysctl.c:__register_sysctl_table
  - fs/proc/proc_sysctl.c:insert_header
```
**Symbols:**

```
ffffffff81366140-ffffffff81366570: insert_header (STB_LOCAL)
ffffffff813670af-ffffffff813670f3: insert_header.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
int insert_header(struct ctl_dir *dir, struct ctl_table_header *header);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/proc/proc_sysctl.c (0)
Location: fs/proc/proc_sysctl.c:215
Inline: False
Direct callers:
  - fs/proc/proc_sysctl.c:__register_sysctl_table
  - fs/proc/proc_sysctl.c:__register_sysctl_table
  - fs/proc/proc_sysctl.c:insert_header
```
**Symbols:**

```
ffffffff8137e3d0-ffffffff8137e800: insert_header (STB_LOCAL)
ffffffff8137f33f-ffffffff8137f383: insert_header.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int insert_header(struct ctl_dir *dir, struct ctl_table_header *header);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/proc/proc_sysctl.c (ffffffff813c8130)
Location: fs/proc/proc_sysctl.c:216
Inline: False
Direct callers:
  - fs/proc/proc_sysctl.c:__register_sysctl_table
  - fs/proc/proc_sysctl.c:get_subdir
  - fs/proc/proc_sysctl.c:insert_header
```
**Symbols:**

```
ffffffff813c8130-ffffffff813c8338: insert_header (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int insert_header(struct ctl_dir *dir, struct ctl_table_header *header);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/proc/proc_sysctl.c (ffffffff813da120)
Location: fs/proc/proc_sysctl.c:217
Inline: False
Direct callers:
  - fs/proc/proc_sysctl.c:__register_sysctl_table
  - fs/proc/proc_sysctl.c:get_subdir
  - fs/proc/proc_sysctl.c:insert_header
```
**Symbols:**

```
ffffffff813da120-ffffffff813da328: insert_header (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int insert_header(struct ctl_dir *dir, struct ctl_table_header *header);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/proc/proc_sysctl.c (ffffffff813e0f70)
Location: fs/proc/proc_sysctl.c:212
Inline: False
Direct callers:
  - fs/proc/proc_sysctl.c:__register_sysctl_table
  - fs/proc/proc_sysctl.c:__register_sysctl_table
  - fs/proc/proc_sysctl.c:insert_header
```
**Symbols:**

```
ffffffff813e0f70-ffffffff813e1178: insert_header (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int insert_header(struct ctl_dir *dir, struct ctl_table_header *header);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/proc/proc_sysctl.c (ffffffff81432a20)
Location: fs/proc/proc_sysctl.c:212
Inline: False
Direct callers:
  - fs/proc/proc_sysctl.c:__register_sysctl_table
  - fs/proc/proc_sysctl.c:__register_sysctl_table
  - fs/proc/proc_sysctl.c:insert_header
```
**Symbols:**

```
ffffffff81432a20-ffffffff81432c28: insert_header (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int insert_header(struct ctl_dir *dir, struct ctl_table_header *header);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/proc/proc_sysctl.c (ffffffff814ac3f0)
Location: fs/proc/proc_sysctl.c:237
Inline: False
Direct callers:
  - fs/proc/proc_sysctl.c:__register_sysctl_table
  - fs/proc/proc_sysctl.c:__register_sysctl_table
  - fs/proc/proc_sysctl.c:insert_header
```
**Symbols:**

```
ffffffff814ac3f0-ffffffff814ac60f: insert_header (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int insert_header(struct ctl_dir *dir, struct ctl_table_header *header);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/proc/proc_sysctl.c (ffffffff81542a20)
Location: fs/proc/proc_sysctl.c:230
Inline: False
Direct callers:
  - fs/proc/proc_sysctl.c:__register_sysctl_table
  - fs/proc/proc_sysctl.c:__register_sysctl_table
  - fs/proc/proc_sysctl.c:insert_header
```
**Symbols:**

```
ffffffff81542a20-ffffffff81542c3f: insert_header (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int insert_header(struct ctl_dir *dir, struct ctl_table_header *header);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/proc/proc_sysctl.c (ffffffff8157aaf0)
Location: fs/proc/proc_sysctl.c:222
Inline: False
Direct callers:
  - fs/proc/proc_sysctl.c:__register_sysctl_table
  - fs/proc/proc_sysctl.c:sysctl_mkdir_p
  - fs/proc/proc_sysctl.c:insert_header
```
**Symbols:**

```
ffffffff8157aaf0-ffffffff8157ad00: insert_header (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int insert_header(struct ctl_dir *dir, struct ctl_table_header *header);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/proc/proc_sysctl.c (ffffffff815b33d0)
Location: fs/proc/proc_sysctl.c:223
Inline: False
Direct callers:
  - fs/proc/proc_sysctl.c:__register_sysctl_table
  - fs/proc/proc_sysctl.c:sysctl_mkdir_p
  - fs/proc/proc_sysctl.c:insert_header
```
**Symbols:**

```
ffffffff815b33d0-ffffffff815b35d6: insert_header (STB_LOCAL)
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
int insert_header(struct ctl_dir *dir, struct ctl_table_header *header);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/proc/proc_sysctl.c (ffff80001044ae18)
Location: fs/proc/proc_sysctl.c:215
Inline: False
Direct callers:
  - fs/proc/proc_sysctl.c:__register_sysctl_table
  - fs/proc/proc_sysctl.c:__register_sysctl_table
  - fs/proc/proc_sysctl.c:insert_header
```
**Symbols:**

```
ffff80001044ae18-ffff80001044b274: insert_header (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int insert_header(struct ctl_dir *dir, struct ctl_table_header *header);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/proc/proc_sysctl.c (c06101a0)
Location: fs/proc/proc_sysctl.c:215
Inline: False
Direct callers:
  - fs/proc/proc_sysctl.c:__register_sysctl_table
  - fs/proc/proc_sysctl.c:__register_sysctl_table
  - fs/proc/proc_sysctl.c:insert_header
```
**Symbols:**

```
c06101a0-c0610608: insert_header (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int insert_header(struct ctl_dir *dir, struct ctl_table_header *header);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/proc/proc_sysctl.c (c000000000562ac0)
Location: fs/proc/proc_sysctl.c:215
Inline: False
Direct callers:
  - fs/proc/proc_sysctl.c:__register_sysctl_table
  - fs/proc/proc_sysctl.c:__register_sysctl_table
  - fs/proc/proc_sysctl.c:insert_header
```
**Symbols:**

```
c000000000562ac0-c0000000005630f0: insert_header (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int insert_header(struct ctl_dir *dir, struct ctl_table_header *header);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/proc/proc_sysctl.c (ffffffe0002e0006)
Location: fs/proc/proc_sysctl.c:215
Inline: False
Direct callers:
  - fs/proc/proc_sysctl.c:__register_sysctl_table
  - fs/proc/proc_sysctl.c:__register_sysctl_table
  - fs/proc/proc_sysctl.c:insert_header
```
**Symbols:**

```
ffffffe0002e0006-ffffffe0002e040e: insert_header (STB_LOCAL)
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
int insert_header(struct ctl_dir *dir, struct ctl_table_header *header);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/proc/proc_sysctl.c (0)
Location: fs/proc/proc_sysctl.c:215
Inline: False
Direct callers:
  - fs/proc/proc_sysctl.c:__register_sysctl_table
  - fs/proc/proc_sysctl.c:__register_sysctl_table
  - fs/proc/proc_sysctl.c:insert_header
```
**Symbols:**

```
ffffffff813769b0-ffffffff81376de0: insert_header (STB_LOCAL)
ffffffff8137791f-ffffffff81377963: insert_header.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Transformation ⚠️</summary>

```c
int insert_header(struct ctl_dir *dir, struct ctl_table_header *header);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/proc/proc_sysctl.c (0)
Location: fs/proc/proc_sysctl.c:215
Inline: False
Direct callers:
  - fs/proc/proc_sysctl.c:__register_sysctl_table
  - fs/proc/proc_sysctl.c:__register_sysctl_table
  - fs/proc/proc_sysctl.c:insert_header
```
**Symbols:**

```
ffffffff81367480-ffffffff813678b0: insert_header (STB_LOCAL)
ffffffff813683ef-ffffffff81368433: insert_header.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Transformation ⚠️</summary>

```c
int insert_header(struct ctl_dir *dir, struct ctl_table_header *header);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/proc/proc_sysctl.c (0)
Location: fs/proc/proc_sysctl.c:215
Inline: False
Direct callers:
  - fs/proc/proc_sysctl.c:__register_sysctl_table
  - fs/proc/proc_sysctl.c:__register_sysctl_table
  - fs/proc/proc_sysctl.c:insert_header
```
**Symbols:**

```
ffffffff81374480-ffffffff813748b0: insert_header (STB_LOCAL)
ffffffff813753ef-ffffffff81375433: insert_header.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
int insert_header(struct ctl_dir *dir, struct ctl_table_header *header);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/proc/proc_sysctl.c (0)
Location: fs/proc/proc_sysctl.c:215
Inline: False
Direct callers:
  - fs/proc/proc_sysctl.c:__register_sysctl_table
  - fs/proc/proc_sysctl.c:__register_sysctl_table
  - fs/proc/proc_sysctl.c:insert_header
```
**Symbols:**

```
ffffffff81387e90-ffffffff813882be: insert_header (STB_LOCAL)
ffffffff81388dbf-ffffffff81388e03: insert_header.cold (STB_LOCAL)
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
