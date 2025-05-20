# Function: <code>pstore_get_backend_records</code>

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
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void pstore_get_backend_records(struct pstore_info *psi, struct dentry *root, int quiet);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/pstore/platform.c (ffffffff81380a20)
Location: fs/pstore/platform.c:831
Inline: False
Direct callers:
  - fs/pstore/inode.c:pstore_get_records
```
**Symbols:**

```
ffffffff81380a20-ffffffff81380c83: pstore_get_backend_records (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void pstore_get_backend_records(struct pstore_info *psi, struct dentry *root, int quiet);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/pstore/platform.c (ffffffff813a5a30)
Location: fs/pstore/platform.c:828
Inline: False
Direct callers:
  - fs/pstore/inode.c:pstore_get_records
```
**Symbols:**

```
ffffffff813a5a30-ffffffff813a5c9e: pstore_get_backend_records (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Transformation ⚠️</summary>

```c
void pstore_get_backend_records(struct pstore_info *psi, struct dentry *root, int quiet);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/pstore/platform.c (0)
Location: fs/pstore/platform.c:674
Inline: False
Direct callers:
  - fs/pstore/inode.c:pstore_get_records
```
**Symbols:**

```
ffffffff813d4ec8-ffffffff813d4f5f: pstore_get_backend_records.cold.5 (STB_LOCAL)
ffffffff813d4bb0-ffffffff813d4de2: pstore_get_backend_records (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Transformation ⚠️</summary>

```c
void pstore_get_backend_records(struct pstore_info *psi, struct dentry *root, int quiet);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/pstore/platform.c (0)
Location: fs/pstore/platform.c:725
Inline: False
Direct callers:
  - fs/pstore/inode.c:pstore_get_records
```
**Symbols:**

```
ffffffff813ef520-ffffffff813ef59b: pstore_get_backend_records.cold.5 (STB_LOCAL)
ffffffff813ef1c0-ffffffff813ef3fe: pstore_get_backend_records (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
void pstore_get_backend_records(struct pstore_info *psi, struct dentry *root, int quiet);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/pstore/platform.c (0)
Location: fs/pstore/platform.c:719
Inline: False
Direct callers:
  - fs/pstore/inode.c:pstore_get_records
```
**Symbols:**

```
ffffffff8141b800-ffffffff8141b87b: pstore_get_backend_records.cold (STB_LOCAL)
ffffffff8141b440-ffffffff8141b680: pstore_get_backend_records (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
void pstore_get_backend_records(struct pstore_info *psi, struct dentry *root, int quiet);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/pstore/platform.c (0)
Location: fs/pstore/platform.c:719
Inline: False
Direct callers:
  - fs/pstore/inode.c:pstore_get_records
```
**Symbols:**

```
ffffffff81435650-ffffffff814356cb: pstore_get_backend_records.cold (STB_LOCAL)
ffffffff81435290-ffffffff814354d0: pstore_get_backend_records (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
void pstore_get_backend_records(struct pstore_info *psi, struct dentry *root, int quiet);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/pstore/platform.c (0)
Location: fs/pstore/platform.c:729
Inline: False
Direct callers:
  - fs/pstore/inode.c:pstore_get_records
```
**Symbols:**

```
ffffffff81485398-ffffffff814853d6: pstore_get_backend_records.cold (STB_LOCAL)
ffffffff81485110-ffffffff8148525c: pstore_get_backend_records (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
void pstore_get_backend_records(struct pstore_info *psi, struct dentry *root, int quiet);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/pstore/platform.c (0)
Location: fs/pstore/platform.c:729
Inline: False
Direct callers:
  - fs/pstore/inode.c:pstore_get_records
```
**Symbols:**

```
ffffffff81befa63-ffffffff81befaa1: pstore_get_backend_records.cold (STB_LOCAL)
ffffffff814a28b0-ffffffff814a2a05: pstore_get_backend_records (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
void pstore_get_backend_records(struct pstore_info *psi, struct dentry *root, int quiet);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/pstore/platform.c (0)
Location: fs/pstore/platform.c:732
Inline: False
Direct callers:
  - fs/pstore/inode.c:pstore_get_records
```
**Symbols:**

```
ffffffff81be1b0a-ffffffff81be1b48: pstore_get_backend_records.cold (STB_LOCAL)
ffffffff814a8a00-ffffffff814a8b55: pstore_get_backend_records (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
void pstore_get_backend_records(struct pstore_info *psi, struct dentry *root, int quiet);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/pstore/platform.c (0)
Location: fs/pstore/platform.c:732
Inline: False
Direct callers:
  - fs/pstore/inode.c:pstore_get_records
```
**Symbols:**

```
ffffffff81cd27ba-ffffffff81cd27f8: pstore_get_backend_records.cold (STB_LOCAL)
ffffffff81500d30-ffffffff81500e85: pstore_get_backend_records (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
void pstore_get_backend_records(struct pstore_info *psi, struct dentry *root, int quiet);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/pstore/platform.c (0)
Location: fs/pstore/platform.c:730
Inline: False
Direct callers:
  - fs/pstore/inode.c:pstore_get_records
```
**Symbols:**

```
ffffffff81e858f3-ffffffff81e85933: pstore_get_backend_records.cold (STB_LOCAL)
ffffffff81592030-ffffffff815921ac: pstore_get_backend_records (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void pstore_get_backend_records(struct pstore_info *psi, struct dentry *root, int quiet);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/pstore/platform.c (ffffffff816398e0)
Location: fs/pstore/platform.c:745
Inline: False
Direct callers:
  - fs/pstore/inode.c:pstore_get_records
```
**Symbols:**

```
ffffffff816398e0-ffffffff81639a9f: pstore_get_backend_records (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void pstore_get_backend_records(struct pstore_info *psi, struct dentry *root, int quiet);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/pstore/platform.c (ffffffff81671d40)
Location: fs/pstore/platform.c:745
Inline: False
Direct callers:
  - fs/pstore/inode.c:pstore_get_records
```
**Symbols:**

```
ffffffff81671d40-ffffffff81671eff: pstore_get_backend_records (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void pstore_get_backend_records(struct pstore_info *psi, struct dentry *root, int quiet);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/pstore/platform.c (ffffffff816adc00)
Location: fs/pstore/platform.c:656
Inline: False
Direct callers:
  - fs/pstore/inode.c:pstore_get_records
```
**Symbols:**

```
ffffffff816adc00-ffffffff816aded6: pstore_get_backend_records (STB_GLOBAL)
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
void pstore_get_backend_records(struct pstore_info *psi, struct dentry *root, int quiet);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/pstore/platform.c (ffff80001051b2f8)
Location: fs/pstore/platform.c:719
Inline: False
Direct callers:
  - fs/pstore/inode.c:pstore_get_records
```
**Symbols:**

```
ffff80001051b2f8-ffff80001051b5a4: pstore_get_backend_records (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void pstore_get_backend_records(struct pstore_info *psi, struct dentry *root, int quiet);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/pstore/platform.c (c06d57bc)
Location: fs/pstore/platform.c:719
Inline: False
Direct callers:
  - fs/pstore/inode.c:pstore_get_records
```
**Symbols:**

```
c06d57bc-c06d5ab4: pstore_get_backend_records (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void pstore_get_backend_records(struct pstore_info *psi, struct dentry *root, int quiet);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/pstore/platform.c (c000000000665340)
Location: fs/pstore/platform.c:719
Inline: False
Direct callers:
  - fs/pstore/inode.c:pstore_get_records
```
**Symbols:**

```
c000000000665340-c00000000066575c: pstore_get_backend_records (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void pstore_get_backend_records(struct pstore_info *psi, struct dentry *root, int quiet);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/pstore/platform.c (ffffffe0003842b4)
Location: fs/pstore/platform.c:719
Inline: False
Direct callers:
  - fs/pstore/inode.c:pstore_get_records
```
**Symbols:**

```
ffffffe0003842b4-ffffffe000384534: pstore_get_backend_records (STB_GLOBAL)
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
void pstore_get_backend_records(struct pstore_info *psi, struct dentry *root, int quiet);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/pstore/platform.c (0)
Location: fs/pstore/platform.c:719
Inline: False
Direct callers:
  - fs/pstore/inode.c:pstore_get_records
```
**Symbols:**

```
ffffffff8142dc30-ffffffff8142dcab: pstore_get_backend_records.cold (STB_LOCAL)
ffffffff8142d870-ffffffff8142dab0: pstore_get_backend_records (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Transformation ⚠️</summary>

```c
void pstore_get_backend_records(struct pstore_info *psi, struct dentry *root, int quiet);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/pstore/platform.c (0)
Location: fs/pstore/platform.c:719
Inline: False
Direct callers:
  - fs/pstore/inode.c:pstore_get_records
```
**Symbols:**

```
ffffffff8141e6b0-ffffffff8141e72b: pstore_get_backend_records.cold (STB_LOCAL)
ffffffff8141e2f0-ffffffff8141e530: pstore_get_backend_records (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Transformation ⚠️</summary>

```c
void pstore_get_backend_records(struct pstore_info *psi, struct dentry *root, int quiet);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/pstore/platform.c (0)
Location: fs/pstore/platform.c:719
Inline: False
Direct callers:
  - fs/pstore/inode.c:pstore_get_records
```
**Symbols:**

```
ffffffff81429dd0-ffffffff81429e4b: pstore_get_backend_records.cold (STB_LOCAL)
ffffffff81429a10-ffffffff81429c50: pstore_get_backend_records (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
void pstore_get_backend_records(struct pstore_info *psi, struct dentry *root, int quiet);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/pstore/platform.c (0)
Location: fs/pstore/platform.c:719
Inline: False
Direct callers:
  - fs/pstore/inode.c:pstore_get_records
```
**Symbols:**

```
ffffffff81440c92-ffffffff81440d0d: pstore_get_backend_records.cold (STB_LOCAL)
ffffffff814408d0-ffffffff81440b10: pstore_get_backend_records (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
