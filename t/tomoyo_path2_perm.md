# Function: <code>tomoyo_path2_perm</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int tomoyo_path2_perm(const u8 operation, struct path *path1, struct path *path2);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/tomoyo/file.c (ffffffff8136f9c0)
Location: security/tomoyo/file.c:885
Inline: False
Direct callers:
  - security/tomoyo/tomoyo.c:tomoyo_sb_pivotroot
  - security/tomoyo/tomoyo.c:tomoyo_path_rename
  - security/tomoyo/tomoyo.c:tomoyo_path_link
```
**Symbols:**

```
ffffffff8136f9c0-ffffffff8136fbe1: tomoyo_path2_perm (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int tomoyo_path2_perm(const u8 operation, const struct path *path1, const struct path *path2);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/tomoyo/file.c (ffffffff813a5d20)
Location: security/tomoyo/file.c:885
Inline: False
Direct callers:
  - security/tomoyo/tomoyo.c:tomoyo_sb_pivotroot
  - security/tomoyo/tomoyo.c:tomoyo_path_rename
  - security/tomoyo/tomoyo.c:tomoyo_path_link
```
**Symbols:**

```
ffffffff813a5d20-ffffffff813a5f61: tomoyo_path2_perm (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int tomoyo_path2_perm(const u8 operation, const struct path *path1, const struct path *path2);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/tomoyo/file.c (ffffffff813bc8a0)
Location: security/tomoyo/file.c:885
Inline: False
Direct callers:
  - security/tomoyo/tomoyo.c:tomoyo_sb_pivotroot
  - security/tomoyo/tomoyo.c:tomoyo_path_rename
  - security/tomoyo/tomoyo.c:tomoyo_path_link
```
**Symbols:**

```
ffffffff813bc8a0-ffffffff813bcae1: tomoyo_path2_perm (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int tomoyo_path2_perm(const u8 operation, const struct path *path1, const struct path *path2);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/tomoyo/file.c (ffffffff813d3200)
Location: security/tomoyo/file.c:885
Inline: False
Direct callers:
  - security/tomoyo/tomoyo.c:tomoyo_sb_pivotroot
  - security/tomoyo/tomoyo.c:tomoyo_path_rename
  - security/tomoyo/tomoyo.c:tomoyo_path_link
```
**Symbols:**

```
ffffffff813d3200-ffffffff813d3458: tomoyo_path2_perm (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int tomoyo_path2_perm(const u8 operation, const struct path *path1, const struct path *path2);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/tomoyo/file.c (ffffffff813f9710)
Location: security/tomoyo/file.c:886
Inline: False
Direct callers:
  - security/tomoyo/tomoyo.c:tomoyo_sb_pivotroot
  - security/tomoyo/tomoyo.c:tomoyo_path_rename
  - security/tomoyo/tomoyo.c:tomoyo_path_link
```
**Symbols:**

```
ffffffff813f9710-ffffffff813f9968: tomoyo_path2_perm (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int tomoyo_path2_perm(const u8 operation, const struct path *path1, const struct path *path2);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/tomoyo/file.c (ffffffff8142a6f0)
Location: security/tomoyo/file.c:886
Inline: False
Direct callers:
  - security/tomoyo/tomoyo.c:tomoyo_sb_pivotroot
  - security/tomoyo/tomoyo.c:tomoyo_path_rename
  - security/tomoyo/tomoyo.c:tomoyo_path_link
```
**Symbols:**

```
ffffffff8142a6f0-ffffffff8142a93d: tomoyo_path2_perm (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int tomoyo_path2_perm(const u8 operation, const struct path *path1, const struct path *path2);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/tomoyo/file.c (ffffffff81446fc0)
Location: security/tomoyo/file.c:886
Inline: False
Direct callers:
  - security/tomoyo/tomoyo.c:tomoyo_sb_pivotroot
  - security/tomoyo/tomoyo.c:tomoyo_path_rename
  - security/tomoyo/tomoyo.c:tomoyo_path_link
```
**Symbols:**

```
ffffffff81446fc0-ffffffff8144720d: tomoyo_path2_perm (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int tomoyo_path2_perm(const u8 operation, const struct path *path1, const struct path *path2);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/tomoyo/file.c (ffffffff81474bd0)
Location: security/tomoyo/file.c:903
Inline: False
Direct callers:
  - security/tomoyo/tomoyo.c:tomoyo_sb_pivotroot
  - security/tomoyo/tomoyo.c:tomoyo_path_rename
  - security/tomoyo/tomoyo.c:tomoyo_path_link
```
**Symbols:**

```
ffffffff81474bd0-ffffffff81474e2b: tomoyo_path2_perm (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int tomoyo_path2_perm(const u8 operation, const struct path *path1, const struct path *path2);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/tomoyo/file.c (ffffffff8148e970)
Location: security/tomoyo/file.c:903
Inline: False
Direct callers:
  - security/tomoyo/tomoyo.c:tomoyo_sb_pivotroot
  - security/tomoyo/tomoyo.c:tomoyo_path_rename
  - security/tomoyo/tomoyo.c:tomoyo_path_link
```
**Symbols:**

```
ffffffff8148e970-ffffffff8148ebcb: tomoyo_path2_perm (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int tomoyo_path2_perm(const u8 operation, const struct path *path1, const struct path *path2);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/tomoyo/file.c (ffffffff814e5c00)
Location: security/tomoyo/file.c:903
Inline: False
Direct callers:
  - security/tomoyo/tomoyo.c:tomoyo_sb_pivotroot
  - security/tomoyo/tomoyo.c:tomoyo_path_rename
  - security/tomoyo/tomoyo.c:tomoyo_path_link
```
**Symbols:**

```
ffffffff814e5c00-ffffffff814e5e62: tomoyo_path2_perm (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int tomoyo_path2_perm(const u8 operation, const struct path *path1, const struct path *path2);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/tomoyo/file.c (ffffffff81503000)
Location: security/tomoyo/file.c:903
Inline: False
Direct callers:
  - security/tomoyo/tomoyo.c:tomoyo_sb_pivotroot
  - security/tomoyo/tomoyo.c:tomoyo_path_rename
  - security/tomoyo/tomoyo.c:tomoyo_path_link
```
**Symbols:**

```
ffffffff81503000-ffffffff81503262: tomoyo_path2_perm (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int tomoyo_path2_perm(const u8 operation, const struct path *path1, const struct path *path2);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/tomoyo/file.c (ffffffff81509bd0)
Location: security/tomoyo/file.c:903
Inline: False
Direct callers:
  - security/tomoyo/tomoyo.c:tomoyo_sb_pivotroot
  - security/tomoyo/tomoyo.c:tomoyo_path_rename
  - security/tomoyo/tomoyo.c:tomoyo_path_link
```
**Symbols:**

```
ffffffff81509bd0-ffffffff81509e32: tomoyo_path2_perm (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int tomoyo_path2_perm(const u8 operation, const struct path *path1, const struct path *path2);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/tomoyo/file.c (ffffffff815670b0)
Location: security/tomoyo/file.c:903
Inline: False
Direct callers:
  - security/tomoyo/tomoyo.c:tomoyo_sb_pivotroot
  - security/tomoyo/tomoyo.c:tomoyo_path_rename
  - security/tomoyo/tomoyo.c:tomoyo_path_link
```
**Symbols:**

```
ffffffff815670b0-ffffffff815673c6: tomoyo_path2_perm (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int tomoyo_path2_perm(const u8 operation, const struct path *path1, const struct path *path2);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/tomoyo/file.c (ffffffff81602c20)
Location: security/tomoyo/file.c:903
Inline: False
Direct callers:
  - security/tomoyo/tomoyo.c:tomoyo_sb_pivotroot
  - security/tomoyo/tomoyo.c:tomoyo_path_rename
  - security/tomoyo/tomoyo.c:tomoyo_path_rename
  - security/tomoyo/tomoyo.c:tomoyo_path_link
```
**Symbols:**

```
ffffffff81602c20-ffffffff81602f70: tomoyo_path2_perm (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int tomoyo_path2_perm(const u8 operation, const struct path *path1, const struct path *path2);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/tomoyo/file.c (ffffffff816b3da0)
Location: security/tomoyo/file.c:903
Inline: False
Direct callers:
  - security/tomoyo/tomoyo.c:tomoyo_sb_pivotroot
  - security/tomoyo/tomoyo.c:tomoyo_path_rename
  - security/tomoyo/tomoyo.c:tomoyo_path_rename
  - security/tomoyo/tomoyo.c:tomoyo_path_link
```
**Symbols:**

```
ffffffff816b3da0-ffffffff816b40f0: tomoyo_path2_perm (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int tomoyo_path2_perm(const u8 operation, const struct path *path1, const struct path *path2);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/tomoyo/file.c (ffffffff816ec760)
Location: security/tomoyo/file.c:903
Inline: False
Direct callers:
  - security/tomoyo/tomoyo.c:tomoyo_sb_pivotroot
  - security/tomoyo/tomoyo.c:tomoyo_path_rename
  - security/tomoyo/tomoyo.c:tomoyo_path_rename
  - security/tomoyo/tomoyo.c:tomoyo_path_link
```
**Symbols:**

```
ffffffff816ec760-ffffffff816ecab0: tomoyo_path2_perm (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int tomoyo_path2_perm(const u8 operation, const struct path *path1, const struct path *path2);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/tomoyo/file.c (ffffffff81729530)
Location: security/tomoyo/file.c:903
Inline: False
Direct callers:
  - security/tomoyo/tomoyo.c:tomoyo_sb_pivotroot
  - security/tomoyo/tomoyo.c:tomoyo_path_rename
  - security/tomoyo/tomoyo.c:tomoyo_path_rename
  - security/tomoyo/tomoyo.c:tomoyo_path_link
```
**Symbols:**

```
ffffffff81729530-ffffffff81729880: tomoyo_path2_perm (STB_GLOBAL)
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
int tomoyo_path2_perm(const u8 operation, const struct path *path1, const struct path *path2);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/tomoyo/file.c (ffff8000105822d0)
Location: security/tomoyo/file.c:903
Inline: False
Direct callers:
  - security/tomoyo/tomoyo.c:tomoyo_sb_pivotroot
  - security/tomoyo/tomoyo.c:tomoyo_path_rename
  - security/tomoyo/tomoyo.c:tomoyo_path_link
```
**Symbols:**

```
ffff8000105822d0-ffff800010582518: tomoyo_path2_perm (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int tomoyo_path2_perm(const u8 operation, const struct path *path1, const struct path *path2);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/tomoyo/file.c (c0734228)
Location: security/tomoyo/file.c:903
Inline: False
Direct callers:
  - security/tomoyo/tomoyo.c:tomoyo_sb_pivotroot
  - security/tomoyo/tomoyo.c:tomoyo_path_rename
  - security/tomoyo/tomoyo.c:tomoyo_path_link
```
**Symbols:**

```
c0734228-c0734480: tomoyo_path2_perm (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int tomoyo_path2_perm(const u8 operation, const struct path *path1, const struct path *path2);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/tomoyo/file.c (c0000000006f0b80)
Location: security/tomoyo/file.c:903
Inline: False
Direct callers:
  - security/tomoyo/tomoyo.c:tomoyo_sb_pivotroot
  - security/tomoyo/tomoyo.c:tomoyo_path_rename
  - security/tomoyo/tomoyo.c:tomoyo_path_link
```
**Symbols:**

```
c0000000006f0b80-c0000000006f0e5c: tomoyo_path2_perm (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int tomoyo_path2_perm(const u8 operation, const struct path *path1, const struct path *path2);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/tomoyo/file.c (ffffffe0003d2852)
Location: security/tomoyo/file.c:903
Inline: False
Direct callers:
  - security/tomoyo/tomoyo.c:tomoyo_sb_pivotroot
  - security/tomoyo/tomoyo.c:tomoyo_path_rename
  - security/tomoyo/tomoyo.c:tomoyo_path_link
```
**Symbols:**

```
ffffffe0003d2852-ffffffe0003d2a3c: tomoyo_path2_perm (STB_GLOBAL)
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
int tomoyo_path2_perm(const u8 operation, const struct path *path1, const struct path *path2);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/tomoyo/file.c (ffffffff81486f50)
Location: security/tomoyo/file.c:903
Inline: False
Direct callers:
  - security/tomoyo/tomoyo.c:tomoyo_sb_pivotroot
  - security/tomoyo/tomoyo.c:tomoyo_path_rename
  - security/tomoyo/tomoyo.c:tomoyo_path_link
```
**Symbols:**

```
ffffffff81486f50-ffffffff814871ab: tomoyo_path2_perm (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int tomoyo_path2_perm(const u8 operation, const struct path *path1, const struct path *path2);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/tomoyo/file.c (ffffffff81477970)
Location: security/tomoyo/file.c:903
Inline: False
Direct callers:
  - security/tomoyo/tomoyo.c:tomoyo_sb_pivotroot
  - security/tomoyo/tomoyo.c:tomoyo_path_rename
  - security/tomoyo/tomoyo.c:tomoyo_path_link
```
**Symbols:**

```
ffffffff81477970-ffffffff81477bcb: tomoyo_path2_perm (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int tomoyo_path2_perm(const u8 operation, const struct path *path1, const struct path *path2);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/tomoyo/file.c (ffffffff81482ff0)
Location: security/tomoyo/file.c:903
Inline: False
Direct callers:
  - security/tomoyo/tomoyo.c:tomoyo_sb_pivotroot
  - security/tomoyo/tomoyo.c:tomoyo_path_rename
  - security/tomoyo/tomoyo.c:tomoyo_path_link
```
**Symbols:**

```
ffffffff81482ff0-ffffffff8148324b: tomoyo_path2_perm (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int tomoyo_path2_perm(const u8 operation, const struct path *path1, const struct path *path2);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/tomoyo/file.c (ffffffff8149ab80)
Location: security/tomoyo/file.c:903
Inline: False
Direct callers:
  - security/tomoyo/tomoyo.c:tomoyo_sb_pivotroot
  - security/tomoyo/tomoyo.c:tomoyo_path_rename
  - security/tomoyo/tomoyo.c:tomoyo_path_link
```
**Symbols:**

```
ffffffff8149ab80-ffffffff8149addb: tomoyo_path2_perm (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
<details>
<summary>Changed between <code>4.4</code> and <code>4.8</code> ⚠️</summary>
<ul>
<li>
<b>Param type changed. </b>
<code>struct path *path1</code> ➡️ <code>const struct path *path1</code>
</li>
<li>
<b>Param type changed. </b>
<code>struct path *path2</code> ➡️ <code>const struct path *path2</code>
</li>
</ul>
</details>
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
