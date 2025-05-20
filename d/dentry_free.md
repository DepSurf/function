# Function: <code>dentry_free</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline ⚠️</summary>

```c
void dentry_free(struct dentry *dentry);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/dcache.c (ffffffff81223360)
Location: fs/dcache.c:294
Inline: True
Direct callers:
  - fs/dcache.c:__dentry_kill
  - fs/dcache.c:shrink_dentry_list
```
**Symbols:**

```
ffffffff81223360-ffffffff812233e1: dentry_free (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
void dentry_free(struct dentry *dentry);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/dcache.c (ffffffff8124b180)
Location: fs/dcache.c:302
Inline: True
Direct callers:
  - fs/dcache.c:shrink_dentry_list
  - fs/dcache.c:__dentry_kill
```
**Symbols:**

```
ffffffff8124b180-ffffffff8124b1ff: dentry_free (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
void dentry_free(struct dentry *dentry);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/dcache.c (ffffffff8125e160)
Location: fs/dcache.c:302
Inline: True
Direct callers:
  - fs/dcache.c:shrink_dentry_list
  - fs/dcache.c:__dentry_kill
```
**Symbols:**

```
ffffffff8125e160-ffffffff8125e1df: dentry_free (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void dentry_free(struct dentry *dentry);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/dcache.c (ffffffff8126b1b0)
Location: fs/dcache.c:334
Inline: False
Direct callers:
  - fs/dcache.c:shrink_dentry_list
  - fs/dcache.c:__dentry_kill
```
**Symbols:**

```
ffffffff8126b1b0-ffffffff8126b21a: dentry_free (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void dentry_free(struct dentry *dentry);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/dcache.c (ffffffff8128da30)
Location: fs/dcache.c:334
Inline: False
Direct callers:
  - fs/dcache.c:shrink_dentry_list
  - fs/dcache.c:__dentry_kill
```
**Symbols:**

```
ffffffff8128da30-ffffffff8128da9a: dentry_free (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void dentry_free(struct dentry *dentry);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/dcache.c (ffffffff812b4530)
Location: fs/dcache.c:336
Inline: False
Direct callers:
  - fs/dcache.c:shrink_dentry_list
  - fs/dcache.c:__dentry_kill
```
**Symbols:**

```
ffffffff812b4530-ffffffff812b459a: dentry_free (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void dentry_free(struct dentry *dentry);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/dcache.c (ffffffff812c9790)
Location: fs/dcache.c:336
Inline: False
Direct callers:
  - fs/dcache.c:shrink_dentry_list
  - fs/dcache.c:__dentry_kill
```
**Symbols:**

```
ffffffff812c9790-ffffffff812c97fa: dentry_free (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
void dentry_free(struct dentry *dentry);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/dcache.c (0)
Location: fs/dcache.c:336
Inline: False
Direct callers:
  - fs/dcache.c:shrink_dentry_list
  - fs/dcache.c:__dentry_kill
```
**Symbols:**

```
ffffffff812e60c0-ffffffff812e6131: dentry_free (STB_LOCAL)
ffffffff812e9cf0-ffffffff812e9d0b: dentry_free.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
void dentry_free(struct dentry *dentry);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/dcache.c (ffffffff812f7ed0)
Location: fs/dcache.c:336
Inline: True
Direct callers:
  - fs/dcache.c:shrink_dentry_list
  - fs/dcache.c:__dentry_kill
```
**Symbols:**

```
ffffffff812f7ed0-ffffffff812f7f3d: dentry_free (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void dentry_free(struct dentry *dentry);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/dcache.c (ffffffff81330820)
Location: fs/dcache.c:336
Inline: False
Direct callers:
  - fs/dcache.c:shrink_dentry_list
  - fs/dcache.c:__dentry_kill
```
**Symbols:**

```
ffffffff81330820-ffffffff8133088d: dentry_free (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void dentry_free(struct dentry *dentry);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/dcache.c (ffffffff8133c190)
Location: fs/dcache.c:336
Inline: False
Direct callers:
  - fs/dcache.c:shrink_dentry_list
  - fs/dcache.c:__dentry_kill
```
**Symbols:**

```
ffffffff8133c190-ffffffff8133c1fd: dentry_free (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void dentry_free(struct dentry *dentry);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/dcache.c (ffffffff81342620)
Location: fs/dcache.c:338
Inline: False
Direct callers:
  - fs/dcache.c:shrink_dentry_list
  - fs/dcache.c:__dentry_kill
```
**Symbols:**

```
ffffffff81342620-ffffffff8134268d: dentry_free (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void dentry_free(struct dentry *dentry);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/dcache.c (ffffffff8138ff80)
Location: fs/dcache.c:338
Inline: False
Direct callers:
  - fs/dcache.c:shrink_dentry_list
  - fs/dcache.c:__dentry_kill
```
**Symbols:**

```
ffffffff8138ff80-ffffffff8138ffed: dentry_free (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void dentry_free(struct dentry *dentry);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/dcache.c (ffffffff814118f0)
Location: fs/dcache.c:363
Inline: False
Direct callers:
  - fs/dcache.c:shrink_dentry_list
  - fs/dcache.c:__dentry_kill
```
**Symbols:**

```
ffffffff814118f0-ffffffff81411981: dentry_free (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void dentry_free(struct dentry *dentry);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/dcache.c (ffffffff8149c2e0)
Location: fs/dcache.c:363
Inline: False
Direct callers:
  - fs/dcache.c:shrink_dentry_list
  - fs/dcache.c:__dentry_kill
```
**Symbols:**

```
ffffffff8149c2e0-ffffffff8149c371: dentry_free (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void dentry_free(struct dentry *dentry);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/dcache.c (ffffffff814d1630)
Location: fs/dcache.c:363
Inline: False
Direct callers:
  - fs/dcache.c:shrink_dentry_list
  - fs/dcache.c:__dentry_kill
```
**Symbols:**

```
ffffffff814d1630-ffffffff814d16c1: dentry_free (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void dentry_free(struct dentry *dentry);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/dcache.c (ffffffff81503df0)
Location: fs/dcache.c:362
Inline: False
Direct callers:
  - fs/dcache.c:shrink_dentry_list
  - fs/dcache.c:__dentry_kill
```
**Symbols:**

```
ffffffff81503df0-ffffffff81503e81: dentry_free (STB_LOCAL)
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
void dentry_free(struct dentry *dentry);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/dcache.c (ffff8000103a5778)
Location: fs/dcache.c:336
Inline: False
Direct callers:
  - fs/dcache.c:shrink_dentry_list
  - fs/dcache.c:__dentry_kill
```
**Symbols:**

```
ffff8000103a5778-ffff8000103a5834: dentry_free (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void dentry_free(struct dentry *dentry);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/dcache.c (c0587620)
Location: fs/dcache.c:336
Inline: False
Direct callers:
  - fs/dcache.c:shrink_dentry_list
  - fs/dcache.c:__dentry_kill
```
**Symbols:**

```
c0587620-c05876e8: dentry_free (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void dentry_free(struct dentry *dentry);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/dcache.c (c00000000049f3b0)
Location: fs/dcache.c:336
Inline: False
Direct callers:
  - fs/dcache.c:shrink_dentry_list
  - fs/dcache.c:__dentry_kill
```
**Symbols:**

```
c00000000049f3b0-c00000000049f480: dentry_free (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
void dentry_free(struct dentry *dentry);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/dcache.c (ffffffe00026c580)
Location: fs/dcache.c:336
Inline: True
Direct callers:
  - fs/dcache.c:shrink_dentry_list
  - fs/dcache.c:__dentry_kill
```
**Symbols:**

```
ffffffe00026c580-ffffffe00026c612: dentry_free (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Selective Inline ⚠️</summary>

```c
void dentry_free(struct dentry *dentry);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/dcache.c (ffffffff812f04b0)
Location: fs/dcache.c:336
Inline: True
Direct callers:
  - fs/dcache.c:shrink_dentry_list
  - fs/dcache.c:__dentry_kill
```
**Symbols:**

```
ffffffff812f04b0-ffffffff812f051d: dentry_free (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
void dentry_free(struct dentry *dentry);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/dcache.c (ffffffff812e10e0)
Location: fs/dcache.c:336
Inline: True
Direct callers:
  - fs/dcache.c:shrink_dentry_list
  - fs/dcache.c:__dentry_kill
```
**Symbols:**

```
ffffffff812e10e0-ffffffff812e114d: dentry_free (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
void dentry_free(struct dentry *dentry);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/dcache.c (ffffffff812ee2c0)
Location: fs/dcache.c:336
Inline: True
Direct callers:
  - fs/dcache.c:shrink_dentry_list
  - fs/dcache.c:__dentry_kill
```
**Symbols:**

```
ffffffff812ee2c0-ffffffff812ee32d: dentry_free (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
void dentry_free(struct dentry *dentry);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/dcache.c (ffffffff812ff780)
Location: fs/dcache.c:336
Inline: True
Direct callers:
  - fs/dcache.c:shrink_dentry_list
  - fs/dcache.c:__dentry_kill
```
**Symbols:**

```
ffffffff812ff780-ffffffff812ff7ed: dentry_free (STB_LOCAL)
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
