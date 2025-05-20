# Function: <code>fat12_ent_set_ptr</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline ⚠️</summary>

```c
void fat12_ent_set_ptr(struct fat_entry *fatent, int offset);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/fat/fatent.c (ffffffff812f9510)
Location: fs/fat/fatent.c:41
Inline: True
Direct callers:
  - fs/fat/fatent.c:fat12_ent_bread
```
**Symbols:**

```
ffffffff812f9510-ffffffff812f95b5: fat12_ent_set_ptr (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
void fat12_ent_set_ptr(struct fat_entry *fatent, int offset);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/fat/fatent.c (ffffffff8132d140)
Location: fs/fat/fatent.c:41
Inline: True
Direct callers:
  - fs/fat/fatent.c:fat12_ent_bread
```
**Symbols:**

```
ffffffff8132d140-ffffffff8132d1e5: fat12_ent_set_ptr (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
void fat12_ent_set_ptr(struct fat_entry *fatent, int offset);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/fat/fatent.c (ffffffff81342e80)
Location: fs/fat/fatent.c:41
Inline: True
Direct callers:
  - fs/fat/fatent.c:fat12_ent_bread
```
**Symbols:**

```
ffffffff81342e80-ffffffff81342f25: fat12_ent_set_ptr (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
void fat12_ent_set_ptr(struct fat_entry *fatent, int offset);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/fat/fatent.c (ffffffff81357960)
Location: fs/fat/fatent.c:41
Inline: True
Direct callers:
  - fs/fat/fatent.c:fat12_ent_bread
```
**Symbols:**

```
ffffffff81357960-ffffffff813579c0: fat12_ent_set_ptr (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
void fat12_ent_set_ptr(struct fat_entry *fatent, int offset);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/fat/fatent.c (ffffffff8137c6c0)
Location: fs/fat/fatent.c:41
Inline: True
Direct callers:
  - fs/fat/fatent.c:fat12_ent_bread
```
**Symbols:**

```
ffffffff8137c6c0-ffffffff8137c720: fat12_ent_set_ptr (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
void fat12_ent_set_ptr(struct fat_entry *fatent, int offset);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/fat/fatent.c (ffffffff813ab020)
Location: fs/fat/fatent.c:41
Inline: True
Direct callers:
  - fs/fat/fatent.c:fat12_ent_bread
```
**Symbols:**

```
ffffffff813ab020-ffffffff813ab080: fat12_ent_set_ptr (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
void fat12_ent_set_ptr(struct fat_entry *fatent, int offset);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/fat/fatent.c (ffffffff813c3df0)
Location: fs/fat/fatent.c:42
Inline: True
Direct callers:
  - fs/fat/fatent.c:fat12_ent_bread
```
**Symbols:**

```
ffffffff813c3df0-ffffffff813c3e50: fat12_ent_set_ptr (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline, Transformation ⚠️</summary>

```c
void fat12_ent_set_ptr(struct fat_entry *fatent, int offset);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/fat/fatent.c (ffffffff813ee5ca)
Location: fs/fat/fatent.c:42
Inline: True
Direct callers:
  - fs/fat/fatent.c:fat12_ent_bread
```
**Symbols:**

```
ffffffff813ee580-ffffffff813ee5f2: fat12_ent_set_ptr (STB_LOCAL)
ffffffff813efed1-ffffffff813eff0f: fat12_ent_set_ptr.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
void fat12_ent_set_ptr(struct fat_entry *fatent, int offset);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/fat/fatent.c (ffffffff81408550)
Location: fs/fat/fatent.c:42
Inline: True
Direct callers:
  - fs/fat/fatent.c:fat12_ent_bread
```
**Symbols:**

```
ffffffff81408550-ffffffff814085b0: fat12_ent_set_ptr (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void fat12_ent_set_ptr(struct fat_entry *fatent, int offset);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fat/fatent.c (ffffffff81455cc0)
Location: fs/fat/fatent.c:42
Inline: False
Direct callers:
  - fs/fat/fatent.c:fat12_ent_bread
```
**Symbols:**

```
ffffffff81455cc0-ffffffff81455d1e: fat12_ent_set_ptr (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void fat12_ent_set_ptr(struct fat_entry *fatent, int offset);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fat/fatent.c (ffffffff81472080)
Location: fs/fat/fatent.c:42
Inline: False
Direct callers:
  - fs/fat/fatent.c:fat12_ent_bread
```
**Symbols:**

```
ffffffff81472080-ffffffff814720de: fat12_ent_set_ptr (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void fat12_ent_set_ptr(struct fat_entry *fatent, int offset);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fat/fatent.c (ffffffff81477aa0)
Location: fs/fat/fatent.c:42
Inline: False
Direct callers:
  - fs/fat/fatent.c:fat12_ent_bread
```
**Symbols:**

```
ffffffff81477aa0-ffffffff81477afe: fat12_ent_set_ptr (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
void fat12_ent_set_ptr(struct fat_entry *fatent, int offset);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/fat/fatent.c (ffffffff814cf3b0)
Location: fs/fat/fatent.c:43
Inline: True
Direct callers:
  - fs/fat/fatent.c:fat12_ent_bread
```
**Symbols:**

```
ffffffff814cf3b0-ffffffff814cf40e: fat12_ent_set_ptr (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
void fat12_ent_set_ptr(struct fat_entry *fatent, int offset);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/fat/fatent.c (ffffffff8155bef0)
Location: fs/fat/fatent.c:43
Inline: True
Direct callers:
  - fs/fat/fatent.c:fat12_ent_bread
```
**Symbols:**

```
ffffffff8155bef0-ffffffff8155bf6a: fat12_ent_set_ptr (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
void fat12_ent_set_ptr(struct fat_entry *fatent, int offset);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/fat/fatent.c (ffffffff815fddc0)
Location: fs/fat/fatent.c:43
Inline: True
Direct callers:
  - fs/fat/fatent.c:fat12_ent_bread
```
**Symbols:**

```
ffffffff815fddc0-ffffffff815fde3a: fat12_ent_set_ptr (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
void fat12_ent_set_ptr(struct fat_entry *fatent, int offset);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/fat/fatent.c (ffffffff81635d90)
Location: fs/fat/fatent.c:43
Inline: True
Direct callers:
  - fs/fat/fatent.c:fat12_ent_bread
```
**Symbols:**

```
ffffffff81635d90-ffffffff81635e0a: fat12_ent_set_ptr (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
void fat12_ent_set_ptr(struct fat_entry *fatent, int offset);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/fat/fatent.c (ffffffff8166f280)
Location: fs/fat/fatent.c:43
Inline: True
Direct callers:
  - fs/fat/fatent.c:fat12_ent_bread
```
**Symbols:**

```
ffffffff8166f280-ffffffff8166f2fa: fat12_ent_set_ptr (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Selective Inline ⚠️</summary>

```c
void fat12_ent_set_ptr(struct fat_entry *fatent, int offset);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/fat/fatent.c (ffff8000104e8a68)
Location: fs/fat/fatent.c:42
Inline: True
Direct callers:
  - fs/fat/fatent.c:fat12_ent_bread
```
**Symbols:**

```
ffff8000104e8a68-ffff8000104e8b14: fat12_ent_set_ptr (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
void fat12_ent_set_ptr(struct fat_entry *fatent, int offset);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/fat/fatent.c (c06a69cc)
Location: fs/fat/fatent.c:42
Inline: True
Direct callers:
  - fs/fat/fatent.c:fat12_ent_bread
```
**Symbols:**

```
c06a69cc-c06a6a8c: fat12_ent_set_ptr (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
void fat12_ent_set_ptr(struct fat_entry *fatent, int offset);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/fat/fatent.c (c000000000626700)
Location: fs/fat/fatent.c:42
Inline: True
Direct callers:
  - fs/fat/fatent.c:fat12_ent_bread
```
**Symbols:**

```
c000000000626700-c000000000626778: fat12_ent_set_ptr (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
void fat12_ent_set_ptr(struct fat_entry *fatent, int offset);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/fat/fatent.c (ffffffe000359fae)
Location: fs/fat/fatent.c:42
Inline: True
Direct callers:
  - fs/fat/fatent.c:fat12_ent_bread
```
**Symbols:**

```
ffffffe000359fae-ffffffe00035a01e: fat12_ent_set_ptr (STB_LOCAL)
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
void fat12_ent_set_ptr(struct fat_entry *fatent, int offset);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/fat/fatent.c (ffffffff81400b30)
Location: fs/fat/fatent.c:42
Inline: True
Direct callers:
  - fs/fat/fatent.c:fat12_ent_bread
```
**Symbols:**

```
ffffffff81400b30-ffffffff81400b90: fat12_ent_set_ptr (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
void fat12_ent_set_ptr(struct fat_entry *fatent, int offset);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/fat/fatent.c (ffffffff813f15b0)
Location: fs/fat/fatent.c:42
Inline: True
Direct callers:
  - fs/fat/fatent.c:fat12_ent_bread
```
**Symbols:**

```
ffffffff813f15b0-ffffffff813f1610: fat12_ent_set_ptr (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
void fat12_ent_set_ptr(struct fat_entry *fatent, int offset);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/fat/fatent.c (ffffffff813fdeb0)
Location: fs/fat/fatent.c:42
Inline: True
Direct callers:
  - fs/fat/fatent.c:fat12_ent_bread
```
**Symbols:**

```
ffffffff813fdeb0-ffffffff813fdf10: fat12_ent_set_ptr (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
void fat12_ent_set_ptr(struct fat_entry *fatent, int offset);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/fat/fatent.c (ffffffff81413b60)
Location: fs/fat/fatent.c:42
Inline: True
Direct callers:
  - fs/fat/fatent.c:fat12_ent_bread
```
**Symbols:**

```
ffffffff81413b60-ffffffff81413bc0: fat12_ent_set_ptr (STB_LOCAL)
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
