# Function: <code>path_is_under</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int path_is_under(struct path *path1, struct path *path2);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namespace.c (ffffffff8122fe00)
Location: fs/namespace.c:2947
Inline: False
Direct callers:
  - kernel/audit_tree.c:audit_tag_tree
```
**Symbols:**

```
ffffffff8122fe00-ffffffff8122fe49: path_is_under (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
bool path_is_under(struct path *path1, struct path *path2);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namespace.c (ffffffff81258490)
Location: fs/namespace.c:2934
Inline: False
Direct callers:
  - kernel/audit_tree.c:audit_tag_tree
```
**Symbols:**

```
ffffffff81258490-ffffffff812584d8: path_is_under (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
bool path_is_under(const struct path *path1, const struct path *path2);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namespace.c (ffffffff8126b920)
Location: fs/namespace.c:3078
Inline: False
Direct callers:
  - kernel/audit_tree.c:audit_tag_tree
```
**Symbols:**

```
ffffffff8126b920-ffffffff8126b968: path_is_under (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
bool path_is_under(const struct path *path1, const struct path *path2);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namespace.c (ffffffff812790f0)
Location: fs/namespace.c:3020
Inline: False
Direct callers:
  - kernel/audit_tree.c:audit_tag_tree
```
**Symbols:**

```
ffffffff812790f0-ffffffff81279138: path_is_under (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
bool path_is_under(const struct path *path1, const struct path *path2);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namespace.c (ffffffff8129bb30)
Location: fs/namespace.c:3093
Inline: False
Direct callers:
  - kernel/audit_tree.c:audit_tag_tree
```
**Symbols:**

```
ffffffff8129bb30-ffffffff8129bb78: path_is_under (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
bool path_is_under(const struct path *path1, const struct path *path2);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namespace.c (ffffffff812c1c70)
Location: fs/namespace.c:3130
Inline: False
Direct callers:
  - kernel/audit_tree.c:audit_tag_tree
```
**Symbols:**

```
ffffffff812c1c70-ffffffff812c1cb8: path_is_under (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
bool path_is_under(const struct path *path1, const struct path *path2);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namespace.c (ffffffff812d6f10)
Location: fs/namespace.c:3102
Inline: False
Direct callers:
  - kernel/audit_tree.c:audit_tag_tree
```
**Symbols:**

```
ffffffff812d6f10-ffffffff812d6f58: path_is_under (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
bool path_is_under(const struct path *path1, const struct path *path2);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namespace.c (ffffffff812f5370)
Location: fs/namespace.c:3559
Inline: False
Direct callers:
  - kernel/audit_tree.c:audit_tag_tree
```
**Symbols:**

```
ffffffff812f5370-ffffffff812f53ba: path_is_under (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
bool path_is_under(const struct path *path1, const struct path *path2);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namespace.c (ffffffff81306ef0)
Location: fs/namespace.c:3590
Inline: False
Direct callers:
  - kernel/audit_tree.c:audit_tag_tree
```
**Symbols:**

```
ffffffff81306ef0-ffffffff81306f3a: path_is_under (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
bool path_is_under(const struct path *path1, const struct path *path2);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namespace.c (ffffffff8133b0e0)
Location: fs/namespace.c:3643
Inline: False
Direct callers:
  - kernel/audit_tree.c:audit_tag_tree
  - fs/namei.c:complete_walk
```
**Symbols:**

```
ffffffff8133b0e0-ffffffff8133b155: path_is_under (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
bool path_is_under(const struct path *path1, const struct path *path2);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namespace.c (ffffffff81346e90)
Location: fs/namespace.c:3665
Inline: False
Direct callers:
  - kernel/audit_tree.c:audit_tag_tree
  - fs/namei.c:complete_walk
```
**Symbols:**

```
ffffffff81346e90-ffffffff81346f05: path_is_under (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
bool path_is_under(const struct path *path1, const struct path *path2);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namespace.c (ffffffff8134d6b0)
Location: fs/namespace.c:3711
Inline: False
Direct callers:
  - kernel/audit_tree.c:audit_tag_tree
  - fs/namei.c:complete_walk
```
**Symbols:**

```
ffffffff8134d6b0-ffffffff8134d728: path_is_under (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
bool path_is_under(const struct path *path1, const struct path *path2);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namespace.c (ffffffff8139b610)
Location: fs/namespace.c:3790
Inline: False
Direct callers:
  - kernel/audit_tree.c:audit_tag_tree
  - fs/namei.c:complete_walk
```
**Symbols:**

```
ffffffff8139b610-ffffffff8139b688: path_is_under (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
bool path_is_under(const struct path *path1, const struct path *path2);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namespace.c (ffffffff8141e5b0)
Location: fs/namespace.c:3833
Inline: False
Direct callers:
  - kernel/audit_tree.c:audit_tag_tree
  - fs/namei.c:complete_walk
```
**Symbols:**

```
ffffffff8141e5b0-ffffffff8141e637: path_is_under (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
bool path_is_under(const struct path *path1, const struct path *path2);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namespace.c (ffffffff814aad50)
Location: fs/namespace.c:3939
Inline: False
Direct callers:
  - kernel/audit_tree.c:audit_tag_tree
  - fs/namei.c:complete_walk
```
**Symbols:**

```
ffffffff814aad50-ffffffff814aadd7: path_is_under (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
bool path_is_under(const struct path *path1, const struct path *path2);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namespace.c (ffffffff814dfb50)
Location: fs/namespace.c:4131
Inline: False
Direct callers:
  - kernel/audit_tree.c:audit_tag_tree
  - fs/namei.c:complete_walk
```
**Symbols:**

```
ffffffff814dfb50-ffffffff814dfbd7: path_is_under (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
bool path_is_under(const struct path *path1, const struct path *path2);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namespace.c (ffffffff81512fe0)
Location: fs/namespace.c:4144
Inline: False
Direct callers:
  - kernel/audit_tree.c:audit_tag_tree
  - fs/namei.c:complete_walk
```
**Symbols:**

```
ffffffff81512fe0-ffffffff81513067: path_is_under (STB_GLOBAL)
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
bool path_is_under(const struct path *path1, const struct path *path2);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namespace.c (ffff8000103ba660)
Location: fs/namespace.c:3590
Inline: False
Direct callers:
  - kernel/audit_tree.c:audit_tag_tree
```
**Symbols:**

```
ffff8000103ba660-ffff8000103ba704: path_is_under (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
bool path_is_under(const struct path *path1, const struct path *path2);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namespace.c (c0598468)
Location: fs/namespace.c:3590
Inline: False
Direct callers:
  - kernel/audit_tree.c:audit_tag_tree
```
**Symbols:**

```
c0598468-c05984c4: path_is_under (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
bool path_is_under(const struct path *path1, const struct path *path2);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namespace.c (c0000000004b7e60)
Location: fs/namespace.c:3590
Inline: False
Direct callers:
  - kernel/audit_tree.c:audit_tag_tree
```
**Symbols:**

```
c0000000004b7e60-c0000000004b7f2c: path_is_under (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
bool path_is_under(const struct path *path1, const struct path *path2);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namespace.c (ffffffe00027cb68)
Location: fs/namespace.c:3590
Inline: False
Direct callers:
  - kernel/audit_tree.c:audit_tag_tree
```
**Symbols:**

```
ffffffe00027cb68-ffffffe00027cbf2: path_is_under (STB_GLOBAL)
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
bool path_is_under(const struct path *path1, const struct path *path2);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namespace.c (ffffffff812ff4d0)
Location: fs/namespace.c:3590
Inline: False
Direct callers:
  - kernel/audit_tree.c:audit_tag_tree
```
**Symbols:**

```
ffffffff812ff4d0-ffffffff812ff51a: path_is_under (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
bool path_is_under(const struct path *path1, const struct path *path2);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namespace.c (ffffffff812f00f0)
Location: fs/namespace.c:3590
Inline: False
Direct callers:
  - kernel/audit_tree.c:audit_tag_tree
```
**Symbols:**

```
ffffffff812f00f0-ffffffff812f013a: path_is_under (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
bool path_is_under(const struct path *path1, const struct path *path2);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namespace.c (ffffffff812fd2c0)
Location: fs/namespace.c:3590
Inline: False
Direct callers:
  - kernel/audit_tree.c:audit_tag_tree
```
**Symbols:**

```
ffffffff812fd2c0-ffffffff812fd30a: path_is_under (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
bool path_is_under(const struct path *path1, const struct path *path2);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namespace.c (ffffffff8130e620)
Location: fs/namespace.c:3590
Inline: False
Direct callers:
  - kernel/audit_tree.c:audit_tag_tree
```
**Symbols:**

```
ffffffff8130e620-ffffffff8130e668: path_is_under (STB_GLOBAL)
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
<b>Return type changed. </b>
<code>int</code> ➡️ <code>bool</code>
</li>
</ul>
</details>
</li>
<li>
<details>
<summary>Changed between <code>4.8</code> and <code>4.10</code> ⚠️</summary>
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
