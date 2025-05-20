# Function: <code>kernfs_path_from_node_locked</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int kernfs_path_from_node_locked(struct kernfs_node *kn_to, struct kernfs_node *kn_from, char *buf, size_t buflen);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/kernfs/dir.c (ffffffff812892b0)
Location: fs/kernfs/dir.c:117
Inline: False
Direct callers:
  - fs/kernfs/dir.c:kernfs_path_from_node
  - fs/kernfs/dir.c:pr_cont_kernfs_path
```
**Symbols:**

```
ffffffff812892b0-ffffffff812895eb: kernfs_path_from_node_locked (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int kernfs_path_from_node_locked(struct kernfs_node *kn_to, struct kernfs_node *kn_from, char *buf, size_t buflen);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/kernfs/dir.c (ffffffff812b6780)
Location: fs/kernfs/dir.c:116
Inline: False
Direct callers:
  - fs/kernfs/dir.c:pr_cont_kernfs_path
  - fs/kernfs/dir.c:kernfs_path_from_node
```
**Symbols:**

```
ffffffff812b6780-ffffffff812b6ab0: kernfs_path_from_node_locked (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int kernfs_path_from_node_locked(struct kernfs_node *kn_to, struct kernfs_node *kn_from, char *buf, size_t buflen);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/kernfs/dir.c (ffffffff812cbef0)
Location: fs/kernfs/dir.c:117
Inline: False
Direct callers:
  - fs/kernfs/dir.c:pr_cont_kernfs_path
  - fs/kernfs/dir.c:kernfs_path_from_node
```
**Symbols:**

```
ffffffff812cbef0-ffffffff812cc23b: kernfs_path_from_node_locked (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int kernfs_path_from_node_locked(struct kernfs_node *kn_to, struct kernfs_node *kn_from, char *buf, size_t buflen);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/kernfs/dir.c (ffffffff812d9470)
Location: fs/kernfs/dir.c:122
Inline: False
Direct callers:
  - fs/kernfs/dir.c:pr_cont_kernfs_path
  - fs/kernfs/dir.c:kernfs_path_from_node
```
**Symbols:**

```
ffffffff812d9470-ffffffff812d9960: kernfs_path_from_node_locked (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int kernfs_path_from_node_locked(struct kernfs_node *kn_to, struct kernfs_node *kn_from, char *buf, size_t buflen);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/kernfs/dir.c (ffffffff812fdcb0)
Location: fs/kernfs/dir.c:123
Inline: False
Direct callers:
  - fs/kernfs/dir.c:pr_cont_kernfs_path
  - fs/kernfs/dir.c:kernfs_path_from_node
```
**Symbols:**

```
ffffffff812fdcb0-ffffffff812fe12c: kernfs_path_from_node_locked (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Transformation ⚠️</summary>

```c
int kernfs_path_from_node_locked(struct kernfs_node *kn_to, struct kernfs_node *kn_from, char *buf, size_t buflen);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/kernfs/dir.c (0)
Location: fs/kernfs/dir.c:123
Inline: False
Direct callers:
  - fs/kernfs/dir.c:pr_cont_kernfs_path
  - fs/kernfs/dir.c:kernfs_path_from_node
```
**Symbols:**

```
ffffffff8132b920-ffffffff8132bd67: kernfs_path_from_node_locked (STB_LOCAL)
ffffffff8132d8e1-ffffffff8132d8f9: kernfs_path_from_node_locked.cold.19 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Transformation ⚠️</summary>

```c
int kernfs_path_from_node_locked(struct kernfs_node *kn_to, struct kernfs_node *kn_from, char *buf, size_t buflen);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/kernfs/dir.c (0)
Location: fs/kernfs/dir.c:123
Inline: False
Direct callers:
  - fs/kernfs/dir.c:pr_cont_kernfs_path
  - fs/kernfs/dir.c:kernfs_path_from_node
```
**Symbols:**

```
ffffffff81342c80-ffffffff813430c7: kernfs_path_from_node_locked (STB_LOCAL)
ffffffff81344c96-ffffffff81344cae: kernfs_path_from_node_locked.cold.17 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
int kernfs_path_from_node_locked(struct kernfs_node *kn_to, struct kernfs_node *kn_from, char *buf, size_t buflen);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/kernfs/dir.c (0)
Location: fs/kernfs/dir.c:122
Inline: False
Direct callers:
  - fs/kernfs/dir.c:pr_cont_kernfs_path
  - fs/kernfs/dir.c:kernfs_path_from_node
```
**Symbols:**

```
ffffffff8136af10-ffffffff8136b31b: kernfs_path_from_node_locked (STB_LOCAL)
ffffffff8136cec6-ffffffff8136cef6: kernfs_path_from_node_locked.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
int kernfs_path_from_node_locked(struct kernfs_node *kn_to, struct kernfs_node *kn_from, char *buf, size_t buflen);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/kernfs/dir.c (0)
Location: fs/kernfs/dir.c:122
Inline: False
Direct callers:
  - fs/kernfs/dir.c:pr_cont_kernfs_path
  - fs/kernfs/dir.c:kernfs_path_from_node
```
**Symbols:**

```
ffffffff813830d0-ffffffff813834fe: kernfs_path_from_node_locked (STB_LOCAL)
ffffffff81385076-ffffffff8138508e: kernfs_path_from_node_locked.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
int kernfs_path_from_node_locked(struct kernfs_node *kn_to, struct kernfs_node *kn_from, char *buf, size_t buflen);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/kernfs/dir.c (0)
Location: fs/kernfs/dir.c:122
Inline: False
Direct callers:
  - fs/kernfs/dir.c:pr_cont_kernfs_path
  - fs/kernfs/dir.c:kernfs_path_from_node
```
**Symbols:**

```
ffffffff813cda20-ffffffff813cde3b: kernfs_path_from_node_locked (STB_LOCAL)
ffffffff813cfc27-ffffffff813cfc3f: kernfs_path_from_node_locked.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
int kernfs_path_from_node_locked(struct kernfs_node *kn_to, struct kernfs_node *kn_from, char *buf, size_t buflen);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/kernfs/dir.c (0)
Location: fs/kernfs/dir.c:122
Inline: False
Direct callers:
  - fs/kernfs/dir.c:pr_cont_kernfs_path
  - fs/kernfs/dir.c:kernfs_path_from_node
```
**Symbols:**

```
ffffffff813df650-ffffffff813dfa6b: kernfs_path_from_node_locked (STB_LOCAL)
ffffffff81bec0d1-ffffffff81bec0e9: kernfs_path_from_node_locked.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
int kernfs_path_from_node_locked(struct kernfs_node *kn_to, struct kernfs_node *kn_from, char *buf, size_t buflen);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/kernfs/dir.c (0)
Location: fs/kernfs/dir.c:122
Inline: False
Direct callers:
  - fs/kernfs/dir.c:pr_cont_kernfs_path
  - fs/kernfs/dir.c:kernfs_path_from_node
```
**Symbols:**

```
ffffffff813e62f0-ffffffff813e66fa: kernfs_path_from_node_locked (STB_LOCAL)
ffffffff81bde12f-ffffffff81bde147: kernfs_path_from_node_locked.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int kernfs_path_from_node_locked(struct kernfs_node *kn_to, struct kernfs_node *kn_from, char *buf, size_t buflen);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/kernfs/dir.c (0)
Location: fs/kernfs/dir.c:122
Inline: False
Direct callers:
  - fs/kernfs/dir.c:pr_cont_kernfs_path
  - fs/kernfs/dir.c:kernfs_path_from_node
```
**Symbols:**

```
ffffffff81437ef0-ffffffff814382fa: kernfs_path_from_node_locked (STB_LOCAL)
ffffffff81cc85bd-ffffffff81cc85d5: kernfs_path_from_node_locked.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int kernfs_path_from_node_locked(struct kernfs_node *kn_to, struct kernfs_node *kn_from, char *buf, size_t buflen);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/kernfs/dir.c (0)
Location: fs/kernfs/dir.c:129
Inline: False
Direct callers:
  - fs/kernfs/dir.c:pr_cont_kernfs_path
```
**Symbols:**

```
ffffffff814b2c90-ffffffff814b3101: kernfs_path_from_node_locked (STB_LOCAL)
ffffffff81e7b2f8-ffffffff81e7b310: kernfs_path_from_node_locked.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int kernfs_path_from_node_locked(struct kernfs_node *kn_to, struct kernfs_node *kn_from, char *buf, size_t buflen);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/kernfs/dir.c (ffffffff815498d0)
Location: fs/kernfs/dir.c:134
Inline: False
Direct callers:
  - fs/kernfs/dir.c:pr_cont_kernfs_path
```
**Symbols:**

```
ffffffff815498d0-ffffffff81549d4f: kernfs_path_from_node_locked (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int kernfs_path_from_node_locked(struct kernfs_node *kn_to, struct kernfs_node *kn_from, char *buf, size_t buflen);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/kernfs/dir.c (ffffffff815814b0)
Location: fs/kernfs/dir.c:134
Inline: False
Direct callers:
  - fs/kernfs/dir.c:pr_cont_kernfs_path
```
**Symbols:**

```
ffffffff815814b0-ffffffff8158196e: kernfs_path_from_node_locked (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int kernfs_path_from_node_locked(struct kernfs_node *kn_to, struct kernfs_node *kn_from, char *buf, size_t buflen);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/kernfs/dir.c (ffffffff815b9fb0)
Location: fs/kernfs/dir.c:134
Inline: False
Direct callers:
  - fs/kernfs/dir.c:pr_cont_kernfs_path
```
**Symbols:**

```
ffffffff815b9fb0-ffffffff815ba449: kernfs_path_from_node_locked (STB_LOCAL)
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
int kernfs_path_from_node_locked(struct kernfs_node *kn_to, struct kernfs_node *kn_from, char *buf, size_t buflen);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/kernfs/dir.c (ffff8000104516c0)
Location: fs/kernfs/dir.c:122
Inline: False
Direct callers:
  - fs/kernfs/dir.c:pr_cont_kernfs_path
  - fs/kernfs/dir.c:kernfs_path_from_node
```
**Symbols:**

```
ffff8000104516c0-ffff800010451aac: kernfs_path_from_node_locked (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int kernfs_path_from_node_locked(struct kernfs_node *kn_to, struct kernfs_node *kn_from, char *buf, size_t buflen);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/kernfs/dir.c (c06145c0)
Location: fs/kernfs/dir.c:122
Inline: False
Direct callers:
  - fs/kernfs/dir.c:pr_cont_kernfs_path
  - fs/kernfs/dir.c:kernfs_path_from_node
```
**Symbols:**

```
c06145c0-c0614a10: kernfs_path_from_node_locked (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int kernfs_path_from_node_locked(struct kernfs_node *kn_to, struct kernfs_node *kn_from, char *buf, size_t buflen);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/kernfs/dir.c (c000000000569e70)
Location: fs/kernfs/dir.c:122
Inline: False
Direct callers:
  - fs/kernfs/dir.c:pr_cont_kernfs_path
  - fs/kernfs/dir.c:kernfs_path_from_node
```
**Symbols:**

```
c000000000569e70-c00000000056a404: kernfs_path_from_node_locked (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int kernfs_path_from_node_locked(struct kernfs_node *kn_to, struct kernfs_node *kn_from, char *buf, size_t buflen);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/kernfs/dir.c (ffffffe0002e43c0)
Location: fs/kernfs/dir.c:122
Inline: False
Direct callers:
  - fs/kernfs/dir.c:pr_cont_kernfs_path
  - fs/kernfs/dir.c:kernfs_path_from_node
```
**Symbols:**

```
ffffffe0002e43c0-ffffffe0002e45e6: kernfs_path_from_node_locked (STB_LOCAL)
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
int kernfs_path_from_node_locked(struct kernfs_node *kn_to, struct kernfs_node *kn_from, char *buf, size_t buflen);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/kernfs/dir.c (0)
Location: fs/kernfs/dir.c:122
Inline: False
Direct callers:
  - fs/kernfs/dir.c:pr_cont_kernfs_path
  - fs/kernfs/dir.c:kernfs_path_from_node
```
**Symbols:**

```
ffffffff8137b6b0-ffffffff8137bade: kernfs_path_from_node_locked (STB_LOCAL)
ffffffff8137d656-ffffffff8137d66e: kernfs_path_from_node_locked.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Transformation ⚠️</summary>

```c
int kernfs_path_from_node_locked(struct kernfs_node *kn_to, struct kernfs_node *kn_from, char *buf, size_t buflen);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/kernfs/dir.c (0)
Location: fs/kernfs/dir.c:122
Inline: False
Direct callers:
  - fs/kernfs/dir.c:pr_cont_kernfs_path
  - fs/kernfs/dir.c:kernfs_path_from_node
```
**Symbols:**

```
ffffffff8136c180-ffffffff8136c5ae: kernfs_path_from_node_locked (STB_LOCAL)
ffffffff8136e10c-ffffffff8136e124: kernfs_path_from_node_locked.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Transformation ⚠️</summary>

```c
int kernfs_path_from_node_locked(struct kernfs_node *kn_to, struct kernfs_node *kn_from, char *buf, size_t buflen);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/kernfs/dir.c (0)
Location: fs/kernfs/dir.c:122
Inline: False
Direct callers:
  - fs/kernfs/dir.c:pr_cont_kernfs_path
  - fs/kernfs/dir.c:kernfs_path_from_node
```
**Symbols:**

```
ffffffff81379180-ffffffff813795ae: kernfs_path_from_node_locked (STB_LOCAL)
ffffffff8137b126-ffffffff8137b13e: kernfs_path_from_node_locked.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
int kernfs_path_from_node_locked(struct kernfs_node *kn_to, struct kernfs_node *kn_from, char *buf, size_t buflen);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/kernfs/dir.c (0)
Location: fs/kernfs/dir.c:122
Inline: False
Direct callers:
  - fs/kernfs/dir.c:pr_cont_kernfs_path
  - fs/kernfs/dir.c:kernfs_path_from_node
```
**Symbols:**

```
ffffffff8138cc30-ffffffff8138d05e: kernfs_path_from_node_locked (STB_LOCAL)
ffffffff8138ec19-ffffffff8138ec31: kernfs_path_from_node_locked.cold (STB_LOCAL)
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
