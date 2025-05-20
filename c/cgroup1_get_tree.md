# Function: <code>cgroup1_get_tree</code>

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
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
int cgroup1_get_tree(struct fs_context *fc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/cgroup/cgroup-v1.c (0)
Location: kernel/cgroup/cgroup-v1.c:1220
Inline: False
```
**Symbols:**

```
ffffffff8115dc79-ffffffff8115dc92: cgroup1_get_tree.cold (STB_LOCAL)
ffffffff8115d880-ffffffff8115dc37: cgroup1_get_tree (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
int cgroup1_get_tree(struct fs_context *fc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/cgroup/cgroup-v1.c (0)
Location: kernel/cgroup/cgroup-v1.c:1202
Inline: False
```
**Symbols:**

```
ffffffff81169876-ffffffff8116988f: cgroup1_get_tree.cold (STB_LOCAL)
ffffffff81169490-ffffffff81169847: cgroup1_get_tree (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int cgroup1_get_tree(struct fs_context *fc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cgroup-v1.c (ffffffff8117b2a0)
Location: kernel/cgroup/cgroup-v1.c:1196
Inline: False
```
**Symbols:**

```
ffffffff8117b2a0-ffffffff8117b3b4: cgroup1_get_tree (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int cgroup1_get_tree(struct fs_context *fc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cgroup-v1.c (ffffffff81178170)
Location: kernel/cgroup/cgroup-v1.c:1201
Inline: False
```
**Symbols:**

```
ffffffff81178170-ffffffff81178296: cgroup1_get_tree (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int cgroup1_get_tree(struct fs_context *fc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cgroup-v1.c (ffffffff81178cf0)
Location: kernel/cgroup/cgroup-v1.c:1207
Inline: False
```
**Symbols:**

```
ffffffff81178cf0-ffffffff81178e09: cgroup1_get_tree (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int cgroup1_get_tree(struct fs_context *fc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cgroup-v1.c (ffffffff811a0620)
Location: kernel/cgroup/cgroup-v1.c:1228
Inline: False
```
**Symbols:**

```
ffffffff811a0620-ffffffff811a0739: cgroup1_get_tree (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int cgroup1_get_tree(struct fs_context *fc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cgroup-v1.c (ffffffff811d0d70)
Location: kernel/cgroup/cgroup-v1.c:1219
Inline: False
```
**Symbols:**

```
ffffffff811d0d70-ffffffff811d0e83: cgroup1_get_tree (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int cgroup1_get_tree(struct fs_context *fc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cgroup-v1.c (ffffffff812148d0)
Location: kernel/cgroup/cgroup-v1.c:1234
Inline: False
```
**Symbols:**

```
ffffffff812148d0-ffffffff812149e3: cgroup1_get_tree (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int cgroup1_get_tree(struct fs_context *fc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cgroup-v1.c (ffffffff8122a1f0)
Location: kernel/cgroup/cgroup-v1.c:1234
Inline: False
```
**Symbols:**

```
ffffffff8122a1f0-ffffffff8122a303: cgroup1_get_tree (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int cgroup1_get_tree(struct fs_context *fc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cgroup-v1.c (ffffffff81242090)
Location: kernel/cgroup/cgroup-v1.c:1233
Inline: False
```
**Symbols:**

```
ffffffff81242090-ffffffff812421a3: cgroup1_get_tree (STB_GLOBAL)
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
int cgroup1_get_tree(struct fs_context *fc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cgroup-v1.c (ffff8000101dc6d0)
Location: kernel/cgroup/cgroup-v1.c:1202
Inline: False
```
**Symbols:**

```
ffff8000101dc6d0-ffff8000101dcb74: cgroup1_get_tree (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int cgroup1_get_tree(struct fs_context *fc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cgroup-v1.c (c041e980)
Location: kernel/cgroup/cgroup-v1.c:1202
Inline: False
```
**Symbols:**

```
c041e980-c041ee00: cgroup1_get_tree (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int cgroup1_get_tree(struct fs_context *fc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cgroup-v1.c (c00000000024a3a0)
Location: kernel/cgroup/cgroup-v1.c:1202
Inline: False
```
**Symbols:**

```
c00000000024a3a0-c00000000024aad4: cgroup1_get_tree (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int cgroup1_get_tree(struct fs_context *fc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cgroup-v1.c (ffffffe000154650)
Location: kernel/cgroup/cgroup-v1.c:1202
Inline: False
```
**Symbols:**

```
ffffffe000154650-ffffffe000154a2e: cgroup1_get_tree (STB_GLOBAL)
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
int cgroup1_get_tree(struct fs_context *fc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/cgroup/cgroup-v1.c (0)
Location: kernel/cgroup/cgroup-v1.c:1202
Inline: False
```
**Symbols:**

```
ffffffff81161e96-ffffffff81161eaf: cgroup1_get_tree.cold (STB_LOCAL)
ffffffff81161ab0-ffffffff81161e67: cgroup1_get_tree (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Transformation ⚠️</summary>

```c
int cgroup1_get_tree(struct fs_context *fc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/cgroup/cgroup-v1.c (0)
Location: kernel/cgroup/cgroup-v1.c:1202
Inline: False
```
**Symbols:**

```
ffffffff811550f6-ffffffff8115510f: cgroup1_get_tree.cold (STB_LOCAL)
ffffffff81154d10-ffffffff811550c7: cgroup1_get_tree (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Transformation ⚠️</summary>

```c
int cgroup1_get_tree(struct fs_context *fc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/cgroup/cgroup-v1.c (0)
Location: kernel/cgroup/cgroup-v1.c:1202
Inline: False
```
**Symbols:**

```
ffffffff8115fc66-ffffffff8115fc7f: cgroup1_get_tree.cold (STB_LOCAL)
ffffffff8115f880-ffffffff8115fc37: cgroup1_get_tree (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
int cgroup1_get_tree(struct fs_context *fc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/cgroup/cgroup-v1.c (0)
Location: kernel/cgroup/cgroup-v1.c:1202
Inline: False
```
**Symbols:**

```
ffffffff8116cf8a-ffffffff8116cfa3: cgroup1_get_tree.cold (STB_LOCAL)
ffffffff8116cb20-ffffffff8116cf5b: cgroup1_get_tree (STB_GLOBAL)
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
