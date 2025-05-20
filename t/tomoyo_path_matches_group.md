# Function: <code>tomoyo_path_matches_group</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
const struct tomoyo_path_info *tomoyo_path_matches_group(const struct tomoyo_path_info *pathname, const struct tomoyo_group *group);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/tomoyo/group.c (ffffffff81370c60)
Location: security/tomoyo/group.c:125
Inline: False
```
**Symbols:**

```
ffffffff81370c60-ffffffff81370cb2: tomoyo_path_matches_group (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
const struct tomoyo_path_info *tomoyo_path_matches_group(const struct tomoyo_path_info *pathname, const struct tomoyo_group *group);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/tomoyo/group.c (ffffffff813a7050)
Location: security/tomoyo/group.c:125
Inline: False
```
**Symbols:**

```
ffffffff813a7050-ffffffff813a70a2: tomoyo_path_matches_group (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
const struct tomoyo_path_info *tomoyo_path_matches_group(const struct tomoyo_path_info *pathname, const struct tomoyo_group *group);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/tomoyo/group.c (ffffffff813bdbd0)
Location: security/tomoyo/group.c:125
Inline: False
```
**Symbols:**

```
ffffffff813bdbd0-ffffffff813bdc22: tomoyo_path_matches_group (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
const struct tomoyo_path_info *tomoyo_path_matches_group(const struct tomoyo_path_info *pathname, const struct tomoyo_group *group);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/tomoyo/group.c (ffffffff813d44b0)
Location: security/tomoyo/group.c:127
Inline: False
```
**Symbols:**

```
ffffffff813d44b0-ffffffff813d4500: tomoyo_path_matches_group (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
const struct tomoyo_path_info *tomoyo_path_matches_group(const struct tomoyo_path_info *pathname, const struct tomoyo_group *group);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/tomoyo/group.c (ffffffff813fa9c0)
Location: security/tomoyo/group.c:128
Inline: False
```
**Symbols:**

```
ffffffff813fa9c0-ffffffff813faa10: tomoyo_path_matches_group (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
const struct tomoyo_path_info *tomoyo_path_matches_group(const struct tomoyo_path_info *pathname, const struct tomoyo_group *group);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/tomoyo/group.c (ffffffff8142b960)
Location: security/tomoyo/group.c:128
Inline: False
```
**Symbols:**

```
ffffffff8142b960-ffffffff8142b9b0: tomoyo_path_matches_group (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
const struct tomoyo_path_info *tomoyo_path_matches_group(const struct tomoyo_path_info *pathname, const struct tomoyo_group *group);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/tomoyo/group.c (ffffffff81448280)
Location: security/tomoyo/group.c:128
Inline: False
```
**Symbols:**

```
ffffffff81448280-ffffffff814482d0: tomoyo_path_matches_group (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
const struct tomoyo_path_info *tomoyo_path_matches_group(const struct tomoyo_path_info *pathname, const struct tomoyo_group *group);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/tomoyo/group.c (ffffffff81475ec0)
Location: security/tomoyo/group.c:131
Inline: False
```
**Symbols:**

```
ffffffff81475ec0-ffffffff81475f10: tomoyo_path_matches_group (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
const struct tomoyo_path_info *tomoyo_path_matches_group(const struct tomoyo_path_info *pathname, const struct tomoyo_group *group);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/tomoyo/group.c (ffffffff8148fc60)
Location: security/tomoyo/group.c:131
Inline: False
```
**Symbols:**

```
ffffffff8148fc60-ffffffff8148fcb0: tomoyo_path_matches_group (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
const struct tomoyo_path_info *tomoyo_path_matches_group(const struct tomoyo_path_info *pathname, const struct tomoyo_group *group);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/tomoyo/group.c (ffffffff814e6f80)
Location: security/tomoyo/group.c:131
Inline: False
Direct callers:
  - security/tomoyo/file.c:tomoyo_check_mkdev_acl
  - security/tomoyo/file.c:tomoyo_check_path2_acl
  - security/tomoyo/file.c:tomoyo_check_path2_acl
  - security/tomoyo/file.c:tomoyo_check_path_number_acl
```
**Symbols:**

```
ffffffff814e6f80-ffffffff814e6fd0: tomoyo_path_matches_group (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
const struct tomoyo_path_info *tomoyo_path_matches_group(const struct tomoyo_path_info *pathname, const struct tomoyo_group *group);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/tomoyo/group.c (ffffffff81504390)
Location: security/tomoyo/group.c:131
Inline: False
Direct callers:
  - security/tomoyo/file.c:tomoyo_check_mkdev_acl
  - security/tomoyo/file.c:tomoyo_check_path2_acl
  - security/tomoyo/file.c:tomoyo_check_path2_acl
  - security/tomoyo/file.c:tomoyo_check_path_number_acl
```
**Symbols:**

```
ffffffff81504390-ffffffff815043e0: tomoyo_path_matches_group (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
const struct tomoyo_path_info *tomoyo_path_matches_group(const struct tomoyo_path_info *pathname, const struct tomoyo_group *group);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/tomoyo/group.c (ffffffff8150af10)
Location: security/tomoyo/group.c:131
Inline: False
Direct callers:
  - security/tomoyo/file.c:tomoyo_check_mkdev_acl
  - security/tomoyo/file.c:tomoyo_check_path2_acl
  - security/tomoyo/file.c:tomoyo_check_path2_acl
  - security/tomoyo/file.c:tomoyo_check_path_number_acl
```
**Symbols:**

```
ffffffff8150af10-ffffffff8150af60: tomoyo_path_matches_group (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
const struct tomoyo_path_info *tomoyo_path_matches_group(const struct tomoyo_path_info *pathname, const struct tomoyo_group *group);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/tomoyo/group.c (ffffffff815686b0)
Location: security/tomoyo/group.c:131
Inline: False
Direct callers:
  - security/tomoyo/file.c:tomoyo_check_mkdev_acl
  - security/tomoyo/file.c:tomoyo_check_path2_acl
  - security/tomoyo/file.c:tomoyo_check_path2_acl
  - security/tomoyo/file.c:tomoyo_check_path_number_acl
```
**Symbols:**

```
ffffffff815686b0-ffffffff81568700: tomoyo_path_matches_group (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
const struct tomoyo_path_info *tomoyo_path_matches_group(const struct tomoyo_path_info *pathname, const struct tomoyo_group *group);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/tomoyo/group.c (ffffffff81604330)
Location: security/tomoyo/group.c:131
Inline: False
Direct callers:
  - security/tomoyo/file.c:tomoyo_check_mkdev_acl
  - security/tomoyo/file.c:tomoyo_check_path2_acl
  - security/tomoyo/file.c:tomoyo_check_path2_acl
  - security/tomoyo/file.c:tomoyo_check_path_number_acl
```
**Symbols:**

```
ffffffff81604330-ffffffff81604390: tomoyo_path_matches_group (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
const struct tomoyo_path_info *tomoyo_path_matches_group(const struct tomoyo_path_info *pathname, const struct tomoyo_group *group);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/tomoyo/group.c (ffffffff816b5570)
Location: security/tomoyo/group.c:131
Inline: False
Direct callers:
  - security/tomoyo/file.c:tomoyo_check_mkdev_acl
  - security/tomoyo/file.c:tomoyo_check_path2_acl
  - security/tomoyo/file.c:tomoyo_check_path2_acl
  - security/tomoyo/file.c:tomoyo_check_path_number_acl
```
**Symbols:**

```
ffffffff816b5570-ffffffff816b55d0: tomoyo_path_matches_group (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
const struct tomoyo_path_info *tomoyo_path_matches_group(const struct tomoyo_path_info *pathname, const struct tomoyo_group *group);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/tomoyo/group.c (ffffffff816edf50)
Location: security/tomoyo/group.c:131
Inline: False
Direct callers:
  - security/tomoyo/file.c:tomoyo_check_mkdev_acl
  - security/tomoyo/file.c:tomoyo_check_path2_acl
  - security/tomoyo/file.c:tomoyo_check_path2_acl
  - security/tomoyo/file.c:tomoyo_check_path_number_acl
```
**Symbols:**

```
ffffffff816edf50-ffffffff816edfb0: tomoyo_path_matches_group (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
const struct tomoyo_path_info *tomoyo_path_matches_group(const struct tomoyo_path_info *pathname, const struct tomoyo_group *group);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/tomoyo/group.c (ffffffff8172ad20)
Location: security/tomoyo/group.c:131
Inline: False
Direct callers:
  - security/tomoyo/file.c:tomoyo_check_mkdev_acl
  - security/tomoyo/file.c:tomoyo_check_path2_acl
  - security/tomoyo/file.c:tomoyo_check_path2_acl
  - security/tomoyo/file.c:tomoyo_check_path_number_acl
```
**Symbols:**

```
ffffffff8172ad20-ffffffff8172ad80: tomoyo_path_matches_group (STB_GLOBAL)
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
const struct tomoyo_path_info *tomoyo_path_matches_group(const struct tomoyo_path_info *pathname, const struct tomoyo_group *group);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/tomoyo/group.c (ffff800010583c88)
Location: security/tomoyo/group.c:131
Inline: False
```
**Symbols:**

```
ffff800010583c88-ffff800010583d04: tomoyo_path_matches_group (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
const struct tomoyo_path_info *tomoyo_path_matches_group(const struct tomoyo_path_info *pathname, const struct tomoyo_group *group);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/tomoyo/group.c (c0735858)
Location: security/tomoyo/group.c:131
Inline: False
```
**Symbols:**

```
c0735858-c07358bc: tomoyo_path_matches_group (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
const struct tomoyo_path_info *tomoyo_path_matches_group(const struct tomoyo_path_info *pathname, const struct tomoyo_group *group);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/tomoyo/group.c (c0000000006f2970)
Location: security/tomoyo/group.c:131
Inline: False
```
**Symbols:**

```
c0000000006f2970-c0000000006f2a2c: tomoyo_path_matches_group (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
const struct tomoyo_path_info *tomoyo_path_matches_group(const struct tomoyo_path_info *pathname, const struct tomoyo_group *group);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/tomoyo/group.c (ffffffe0003d3e2c)
Location: security/tomoyo/group.c:131
Inline: False
```
**Symbols:**

```
ffffffe0003d3e2c-ffffffe0003d3e8e: tomoyo_path_matches_group (STB_GLOBAL)
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
const struct tomoyo_path_info *tomoyo_path_matches_group(const struct tomoyo_path_info *pathname, const struct tomoyo_group *group);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/tomoyo/group.c (ffffffff81488240)
Location: security/tomoyo/group.c:131
Inline: False
```
**Symbols:**

```
ffffffff81488240-ffffffff81488290: tomoyo_path_matches_group (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
const struct tomoyo_path_info *tomoyo_path_matches_group(const struct tomoyo_path_info *pathname, const struct tomoyo_group *group);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/tomoyo/group.c (ffffffff81478c60)
Location: security/tomoyo/group.c:131
Inline: False
```
**Symbols:**

```
ffffffff81478c60-ffffffff81478cb0: tomoyo_path_matches_group (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
const struct tomoyo_path_info *tomoyo_path_matches_group(const struct tomoyo_path_info *pathname, const struct tomoyo_group *group);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/tomoyo/group.c (ffffffff814842e0)
Location: security/tomoyo/group.c:131
Inline: False
```
**Symbols:**

```
ffffffff814842e0-ffffffff81484330: tomoyo_path_matches_group (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
const struct tomoyo_path_info *tomoyo_path_matches_group(const struct tomoyo_path_info *pathname, const struct tomoyo_group *group);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/tomoyo/group.c (ffffffff8149be20)
Location: security/tomoyo/group.c:131
Inline: False
```
**Symbols:**

```
ffffffff8149be20-ffffffff8149be70: tomoyo_path_matches_group (STB_GLOBAL)
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
