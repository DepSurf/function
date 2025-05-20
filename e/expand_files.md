# Function: <code>expand_files</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int expand_files(struct files_struct *files, int nr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/file.c (ffffffff8122a020)
Location: fs/file.c:210
Inline: False
Direct callers:
  - fs/file.c:__alloc_fd
  - fs/file.c:replace_fd
  - fs/file.c:SyS_dup2
```
**Symbols:**

```
ffffffff8122a020-ffffffff8122a238: expand_files (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int expand_files(struct files_struct *files, int nr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/file.c (ffffffff81252770)
Location: fs/file.c:211
Inline: False
Direct callers:
  - fs/file.c:SyS_dup2
  - fs/file.c:replace_fd
  - fs/file.c:__alloc_fd
```
**Symbols:**

```
ffffffff81252770-ffffffff81252988: expand_files (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int expand_files(struct files_struct *files, unsigned int nr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/file.c (ffffffff812659e0)
Location: fs/file.c:211
Inline: False
Direct callers:
  - fs/file.c:SyS_dup2
  - fs/file.c:replace_fd
  - fs/file.c:__alloc_fd
```
**Symbols:**

```
ffffffff812659e0-ffffffff81265beb: expand_files (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int expand_files(struct files_struct *files, unsigned int nr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/file.c (ffffffff81273120)
Location: fs/file.c:197
Inline: False
Direct callers:
  - fs/file.c:SyS_dup2
  - fs/file.c:replace_fd
  - fs/file.c:__alloc_fd
```
**Symbols:**

```
ffffffff81273120-ffffffff8127333e: expand_files (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int expand_files(struct files_struct *files, unsigned int nr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/file.c (ffffffff81295a50)
Location: fs/file.c:198
Inline: False
Direct callers:
  - fs/file.c:SyS_dup2
  - fs/file.c:replace_fd
  - fs/file.c:__alloc_fd
```
**Symbols:**

```
ffffffff81295a50-ffffffff81295c6e: expand_files (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/file.c (ffffffff812bbffc)
Location: fs/file.c:193
Inline: True
Inline callers:
  - fs/file.c:ksys_dup3
  - fs/file.c:replace_fd
  - fs/file.c:__alloc_fd
Direct callers:
  - fs/file.c:ksys_dup3
  - fs/file.c:replace_fd
  - fs/file.c:__alloc_fd
```
**Symbols:**

```
ffffffff812bbd70-ffffffff812bbf85: expand_files.part.11 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/file.c (ffffffff812d11ec)
Location: fs/file.c:193
Inline: True
Inline callers:
  - fs/file.c:ksys_dup3
  - fs/file.c:replace_fd
  - fs/file.c:__alloc_fd
Direct callers:
  - fs/file.c:ksys_dup3
  - fs/file.c:replace_fd
  - fs/file.c:__alloc_fd
```
**Symbols:**

```
ffffffff812d0f60-ffffffff812d1175: expand_files.part.12 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int expand_files(struct files_struct *files, unsigned int nr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/file.c (ffffffff812edf90)
Location: fs/file.c:193
Inline: False
Direct callers:
  - fs/file.c:ksys_dup3
  - fs/file.c:replace_fd
  - fs/file.c:__alloc_fd
```
**Symbols:**

```
ffffffff812edf90-ffffffff812ee182: expand_files (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int expand_files(struct files_struct *files, unsigned int nr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/file.c (ffffffff812ffa50)
Location: fs/file.c:193
Inline: False
Direct callers:
  - fs/file.c:ksys_dup3
  - fs/file.c:replace_fd
  - fs/file.c:__alloc_fd
```
**Symbols:**

```
ffffffff812ffa50-ffffffff812ffc42: expand_files (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int expand_files(struct files_struct *files, unsigned int nr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/file.c (ffffffff81338c80)
Location: fs/file.c:193
Inline: False
Direct callers:
  - fs/file.c:ksys_dup3
  - fs/file.c:replace_fd
  - fs/file.c:__alloc_fd
```
**Symbols:**

```
ffffffff81338c80-ffffffff81338d8f: expand_files (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int expand_files(struct files_struct *files, unsigned int nr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/file.c (ffffffff81344700)
Location: fs/file.c:198
Inline: False
Direct callers:
  - fs/file.c:ksys_dup3
  - fs/file.c:replace_fd
  - fs/file.c:alloc_fd
```
**Symbols:**

```
ffffffff81344700-ffffffff8134480f: expand_files (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int expand_files(struct files_struct *files, unsigned int nr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/file.c (ffffffff8134aa20)
Location: fs/file.c:198
Inline: False
Direct callers:
  - fs/file.c:ksys_dup3
  - fs/file.c:replace_fd
  - fs/file.c:alloc_fd
```
**Symbols:**

```
ffffffff8134aa20-ffffffff8134ac2c: expand_files (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int expand_files(struct files_struct *files, unsigned int nr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/file.c (0)
Location: fs/file.c:198
Inline: False
Direct callers:
  - fs/file.c:ksys_dup3
  - fs/file.c:replace_fd
  - fs/file.c:alloc_fd
```
**Symbols:**

```
ffffffff813987d0-ffffffff81398a0a: expand_files (STB_LOCAL)
ffffffff81cc3de0-ffffffff81cc3e1f: expand_files.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int expand_files(struct files_struct *files, unsigned int nr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/file.c (0)
Location: fs/file.c:214
Inline: False
Direct callers:
  - fs/file.c:ksys_dup3
  - fs/file.c:replace_fd
  - fs/file.c:alloc_fd
```
**Symbols:**

```
ffffffff8141b020-ffffffff8141b241: expand_files (STB_LOCAL)
ffffffff81e766e3-ffffffff81e76722: expand_files.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
int expand_files(struct files_struct *files, unsigned int nr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/file.c (0)
Location: fs/file.c:214
Inline: False
Direct callers:
  - fs/file.c:ksys_dup3
  - fs/file.c:replace_fd
  - fs/file.c:alloc_fd
```
**Symbols:**

```
ffffffff814a70b0-ffffffff814a72d1: expand_files (STB_LOCAL)
ffffffff82068b81-ffffffff82068bc0: expand_files.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
int expand_files(struct files_struct *files, unsigned int nr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/file.c (0)
Location: fs/file.c:214
Inline: False
Direct callers:
  - fs/file.c:ksys_dup3
  - fs/file.c:replace_fd
  - fs/file.c:alloc_fd
```
**Symbols:**

```
ffffffff814dc090-ffffffff814dc2b8: expand_files (STB_LOCAL)
ffffffff820e84bf-ffffffff820e84fe: expand_files.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
int expand_files(struct files_struct *files, unsigned int nr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/file.c (0)
Location: fs/file.c:214
Inline: False
Direct callers:
  - fs/file.c:ksys_dup3
  - fs/file.c:replace_fd
  - fs/file.c:alloc_fd
```
**Symbols:**

```
ffffffff8150e3b0-ffffffff8150e5d8: expand_files (STB_LOCAL)
ffffffff821c5219-ffffffff821c5258: expand_files.cold (STB_LOCAL)
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
int expand_files(struct files_struct *files, unsigned int nr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/file.c (ffff8000103b1510)
Location: fs/file.c:193
Inline: False
Direct callers:
  - fs/file.c:ksys_dup3
  - fs/file.c:replace_fd
  - fs/file.c:__alloc_fd
```
**Symbols:**

```
ffff8000103b1510-ffff8000103b1798: expand_files (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int expand_files(struct files_struct *files, unsigned int nr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/file.c (c05905b8)
Location: fs/file.c:193
Inline: False
Direct callers:
  - fs/file.c:ksys_dup3
  - fs/file.c:replace_fd
  - fs/file.c:__alloc_fd
```
**Symbols:**

```
c05905b8-c05907f4: expand_files (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int expand_files(struct files_struct *files, unsigned int nr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/file.c (c0000000004ac7b0)
Location: fs/file.c:193
Inline: False
Direct callers:
  - fs/file.c:ksys_dup3
  - fs/file.c:replace_fd
  - fs/file.c:__alloc_fd
```
**Symbols:**

```
c0000000004ac7b0-c0000000004acae8: expand_files (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int expand_files(struct files_struct *files, unsigned int nr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/file.c (ffffffe00027561a)
Location: fs/file.c:193
Inline: False
Direct callers:
  - fs/file.c:ksys_dup3
  - fs/file.c:replace_fd
  - fs/file.c:__alloc_fd
```
**Symbols:**

```
ffffffe00027561a-ffffffe000275850: expand_files (STB_LOCAL)
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
int expand_files(struct files_struct *files, unsigned int nr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/file.c (ffffffff812f8030)
Location: fs/file.c:193
Inline: False
Direct callers:
  - fs/file.c:ksys_dup3
  - fs/file.c:replace_fd
  - fs/file.c:__alloc_fd
```
**Symbols:**

```
ffffffff812f8030-ffffffff812f8222: expand_files (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int expand_files(struct files_struct *files, unsigned int nr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/file.c (ffffffff812e8c50)
Location: fs/file.c:193
Inline: False
Direct callers:
  - fs/file.c:ksys_dup3
  - fs/file.c:replace_fd
  - fs/file.c:__alloc_fd
```
**Symbols:**

```
ffffffff812e8c50-ffffffff812e8e42: expand_files (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int expand_files(struct files_struct *files, unsigned int nr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/file.c (ffffffff812f5e40)
Location: fs/file.c:193
Inline: False
Direct callers:
  - fs/file.c:ksys_dup3
  - fs/file.c:replace_fd
  - fs/file.c:__alloc_fd
```
**Symbols:**

```
ffffffff812f5e40-ffffffff812f6032: expand_files (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int expand_files(struct files_struct *files, unsigned int nr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/file.c (ffffffff81306f60)
Location: fs/file.c:193
Inline: False
Direct callers:
  - fs/file.c:ksys_dup3
  - fs/file.c:replace_fd
  - fs/file.c:__alloc_fd
```
**Symbols:**

```
ffffffff81306f60-ffffffff81307149: expand_files (STB_LOCAL)
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
<b>Param type changed. </b>
<code>int nr</code> ➡️ <code>unsigned int nr</code>
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
