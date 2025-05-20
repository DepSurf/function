# Function: <code>d_lru_add</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/dcache.c (ffffffff81223964)
Location: fs/dcache.c:390
Inline: True
Inline callers:
  - fs/dcache.c:dput
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/dcache.c (ffffffff8124c017)
Location: fs/dcache.c:361
Inline: True
Inline callers:
  - fs/dcache.c:dput
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/dcache.c (ffffffff8125eff7)
Location: fs/dcache.c:361
Inline: True
Inline callers:
  - fs/dcache.c:dput
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/dcache.c (ffffffff8126c96a)
Location: fs/dcache.c:393
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/dcache.c (ffffffff8128ecc0)
Location: fs/dcache.c:393
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void d_lru_add(struct dentry *dentry);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/dcache.c (ffffffff812b4480)
Location: fs/dcache.c:392
Inline: False
Direct callers:
  - fs/dcache.c:dentry_kill
```
**Symbols:**

```
ffffffff812b4480-ffffffff812b44c6: d_lru_add (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void d_lru_add(struct dentry *dentry);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/dcache.c (ffffffff812c96d0)
Location: fs/dcache.c:397
Inline: False
Direct callers:
  - fs/dcache.c:dentry_kill
```
**Symbols:**

```
ffffffff812c96d0-ffffffff812c9726: d_lru_add (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void d_lru_add(struct dentry *dentry);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/dcache.c (ffffffff812e6000)
Location: fs/dcache.c:397
Inline: False
Direct callers:
  - fs/dcache.c:dput_to_list
  - fs/dcache.c:dput
  - fs/dcache.c:dput
```
**Symbols:**

```
ffffffff812e6000-ffffffff812e6056: d_lru_add (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void d_lru_add(struct dentry *dentry);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/dcache.c (ffffffff812f7ab0)
Location: fs/dcache.c:397
Inline: False
Direct callers:
  - fs/dcache.c:dput_to_list
  - fs/dcache.c:dput
  - fs/dcache.c:dput
```
**Symbols:**

```
ffffffff812f7ab0-ffffffff812f7b06: d_lru_add (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void d_lru_add(struct dentry *dentry);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/dcache.c (ffffffff81330700)
Location: fs/dcache.c:397
Inline: False
Direct callers:
  - fs/dcache.c:dput_to_list
  - fs/dcache.c:dput
  - fs/dcache.c:dentry_kill
```
**Symbols:**

```
ffffffff81330700-ffffffff81330756: d_lru_add (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void d_lru_add(struct dentry *dentry);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/dcache.c (ffffffff8133c070)
Location: fs/dcache.c:397
Inline: False
Direct callers:
  - fs/dcache.c:dput_to_list
  - fs/dcache.c:dput
  - fs/dcache.c:dentry_kill
```
**Symbols:**

```
ffffffff8133c070-ffffffff8133c0c6: d_lru_add (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void d_lru_add(struct dentry *dentry);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/dcache.c (ffffffff81342500)
Location: fs/dcache.c:399
Inline: False
Direct callers:
  - fs/dcache.c:dput_to_list
  - fs/dcache.c:dput
  - fs/dcache.c:dentry_kill
```
**Symbols:**

```
ffffffff81342500-ffffffff81342556: d_lru_add (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void d_lru_add(struct dentry *dentry);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/dcache.c (ffffffff8138fe60)
Location: fs/dcache.c:399
Inline: False
Direct callers:
  - fs/dcache.c:dput_to_list
  - fs/dcache.c:dput
  - fs/dcache.c:dentry_kill
```
**Symbols:**

```
ffffffff8138fe60-ffffffff8138feb6: d_lru_add (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void d_lru_add(struct dentry *dentry);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/dcache.c (ffffffff814116a0)
Location: fs/dcache.c:424
Inline: False
Direct callers:
  - fs/dcache.c:dput_to_list
  - fs/dcache.c:dput
  - fs/dcache.c:dput
```
**Symbols:**

```
ffffffff814116a0-ffffffff8141170a: d_lru_add (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void d_lru_add(struct dentry *dentry);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/dcache.c (ffffffff8149c140)
Location: fs/dcache.c:424
Inline: False
Direct callers:
  - fs/dcache.c:dput_to_list
  - fs/dcache.c:dput
  - fs/dcache.c:dput
```
**Symbols:**

```
ffffffff8149c140-ffffffff8149c1aa: d_lru_add (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void d_lru_add(struct dentry *dentry);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/dcache.c (ffffffff814d1380)
Location: fs/dcache.c:424
Inline: False
Direct callers:
  - fs/dcache.c:dput_to_list
  - fs/dcache.c:dput
  - fs/dcache.c:dput
```
**Symbols:**

```
ffffffff814d1380-ffffffff814d13ea: d_lru_add (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void d_lru_add(struct dentry *dentry);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/dcache.c (ffffffff81503ea0)
Location: fs/dcache.c:423
Inline: False
Direct callers:
  - fs/dcache.c:dput_to_list
```
**Symbols:**

```
ffffffff81503ea0-ffffffff81503f0a: d_lru_add (STB_LOCAL)
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
void d_lru_add(struct dentry *dentry);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/dcache.c (ffff8000103a6210)
Location: fs/dcache.c:397
Inline: False
Direct callers:
  - fs/dcache.c:dput_to_list
  - fs/dcache.c:dput
  - fs/dcache.c:dput
```
**Symbols:**

```
ffff8000103a6210-ffff8000103a62e8: d_lru_add (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void d_lru_add(struct dentry *dentry);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/dcache.c (c058723c)
Location: fs/dcache.c:397
Inline: False
Direct callers:
  - fs/dcache.c:dput_to_list
  - fs/dcache.c:dput
  - fs/dcache.c:dput
```
**Symbols:**

```
c058723c-c0587348: d_lru_add (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void d_lru_add(struct dentry *dentry);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/dcache.c (c00000000049ee90)
Location: fs/dcache.c:397
Inline: False
Direct callers:
  - fs/dcache.c:dput_to_list
  - fs/dcache.c:dput
  - fs/dcache.c:dput
```
**Symbols:**

```
c00000000049ee90-c00000000049efb8: d_lru_add (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void d_lru_add(struct dentry *dentry);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/dcache.c (ffffffe00026bf30)
Location: fs/dcache.c:397
Inline: False
Direct callers:
  - fs/dcache.c:dput_to_list
  - fs/dcache.c:dput
  - fs/dcache.c:dput
```
**Symbols:**

```
ffffffe00026bf30-ffffffe00026bfe4: d_lru_add (STB_LOCAL)
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
void d_lru_add(struct dentry *dentry);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/dcache.c (ffffffff812f0090)
Location: fs/dcache.c:397
Inline: False
Direct callers:
  - fs/dcache.c:dput_to_list
  - fs/dcache.c:dput
  - fs/dcache.c:dput
```
**Symbols:**

```
ffffffff812f0090-ffffffff812f00e6: d_lru_add (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void d_lru_add(struct dentry *dentry);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/dcache.c (ffffffff812e0cc0)
Location: fs/dcache.c:397
Inline: False
Direct callers:
  - fs/dcache.c:dput_to_list
  - fs/dcache.c:dput
  - fs/dcache.c:dput
```
**Symbols:**

```
ffffffff812e0cc0-ffffffff812e0d16: d_lru_add (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void d_lru_add(struct dentry *dentry);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/dcache.c (ffffffff812edea0)
Location: fs/dcache.c:397
Inline: False
Direct callers:
  - fs/dcache.c:dput_to_list
  - fs/dcache.c:dput
  - fs/dcache.c:dput
```
**Symbols:**

```
ffffffff812edea0-ffffffff812edef6: d_lru_add (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void d_lru_add(struct dentry *dentry);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/dcache.c (ffffffff812fefc0)
Location: fs/dcache.c:397
Inline: False
Direct callers:
  - fs/dcache.c:dput_to_list
  - fs/dcache.c:dput
  - fs/dcache.c:dput
```
**Symbols:**

```
ffffffff812fefc0-ffffffff812ff016: d_lru_add (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
