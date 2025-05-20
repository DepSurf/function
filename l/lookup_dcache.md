# Function: <code>lookup_dcache</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline ⚠️</summary>

```c
struct dentry *lookup_dcache(struct qstr *name, struct dentry *dir, unsigned int flags, bool *need_lookup);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/namei.c (ffffffff81217c70)
Location: fs/namei.c:1451
Inline: True
Direct callers:
  - fs/namei.c:__lookup_hash
  - fs/namei.c:path_openat
```
**Symbols:**

```
ffffffff81217c70-ffffffff81217d16: lookup_dcache (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
struct dentry *lookup_dcache(const struct qstr *name, struct dentry *dir, unsigned int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namei.c (ffffffff8123d800)
Location: fs/namei.c:1472
Inline: False
Direct callers:
  - fs/namei.c:lookup_one_len_unlocked
```
**Symbols:**

```
ffffffff8123d800-ffffffff8123d86e: lookup_dcache (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
struct dentry *lookup_dcache(const struct qstr *name, struct dentry *dir, unsigned int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namei.c (ffffffff812505a0)
Location: fs/namei.c:1468
Inline: False
Direct callers:
  - fs/namei.c:lookup_one_len_unlocked
```
**Symbols:**

```
ffffffff812505a0-ffffffff8125060e: lookup_dcache (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
struct dentry *lookup_dcache(const struct qstr *name, struct dentry *dir, unsigned int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namei.c (ffffffff8125db80)
Location: fs/namei.c:1480
Inline: False
Direct callers:
  - fs/namei.c:lookup_one_len_unlocked
```
**Symbols:**

```
ffffffff8125db80-ffffffff8125dbdf: lookup_dcache (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
struct dentry *lookup_dcache(const struct qstr *name, struct dentry *dir, unsigned int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namei.c (ffffffff8127fed0)
Location: fs/namei.c:1478
Inline: False
Direct callers:
  - fs/namei.c:lookup_one_len_unlocked
```
**Symbols:**

```
ffffffff8127fed0-ffffffff8127ff35: lookup_dcache (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
struct dentry *lookup_dcache(const struct qstr *name, struct dentry *dir, unsigned int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namei.c (ffffffff812a6470)
Location: fs/namei.c:1463
Inline: False
Direct callers:
  - fs/namei.c:lookup_one_len_unlocked
  - fs/namei.c:lookup_one_len
  - fs/namei.c:try_lookup_one_len
  - fs/namei.c:__lookup_hash
```
**Symbols:**

```
ffffffff812a6470-ffffffff812a64d4: lookup_dcache (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
struct dentry *lookup_dcache(const struct qstr *name, struct dentry *dir, unsigned int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namei.c (ffffffff812bb540)
Location: fs/namei.c:1504
Inline: False
Direct callers:
  - fs/namei.c:lookup_one_len_unlocked
  - fs/namei.c:lookup_one_len
  - fs/namei.c:try_lookup_one_len
  - fs/namei.c:__lookup_hash
```
**Symbols:**

```
ffffffff812bb540-ffffffff812bb5a4: lookup_dcache (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
struct dentry *lookup_dcache(const struct qstr *name, struct dentry *dir, unsigned int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namei.c (ffffffff812d8140)
Location: fs/namei.c:1502
Inline: False
Direct callers:
  - fs/namei.c:lookup_one_len_unlocked
  - fs/namei.c:lookup_one_len
  - fs/namei.c:try_lookup_one_len
  - fs/namei.c:__lookup_hash
```
**Symbols:**

```
ffffffff812d8140-ffffffff812d81a6: lookup_dcache (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
struct dentry *lookup_dcache(const struct qstr *name, struct dentry *dir, unsigned int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namei.c (ffffffff812e9cb0)
Location: fs/namei.c:1497
Inline: False
Direct callers:
  - fs/namei.c:lookup_one_len_unlocked
  - fs/namei.c:lookup_one_len
  - fs/namei.c:try_lookup_one_len
  - fs/namei.c:__lookup_hash
```
**Symbols:**

```
ffffffff812e9cb0-ffffffff812e9d16: lookup_dcache (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
struct dentry *lookup_dcache(const struct qstr *name, struct dentry *dir, unsigned int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namei.c (ffffffff81321ca0)
Location: fs/namei.c:1403
Inline: False
Direct callers:
  - fs/namei.c:lookup_one_len_unlocked
  - fs/namei.c:lookup_one_len
  - fs/namei.c:try_lookup_one_len
  - fs/namei.c:__lookup_hash
```
**Symbols:**

```
ffffffff81321ca0-ffffffff81321d06: lookup_dcache (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
struct dentry *lookup_dcache(const struct qstr *name, struct dentry *dir, unsigned int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namei.c (ffffffff8132d260)
Location: fs/namei.c:1403
Inline: False
Direct callers:
  - fs/namei.c:lookup_one_len_unlocked
  - fs/namei.c:lookup_one_len
  - fs/namei.c:try_lookup_one_len
  - fs/namei.c:__lookup_hash
```
**Symbols:**

```
ffffffff8132d260-ffffffff8132d2c6: lookup_dcache (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
struct dentry *lookup_dcache(const struct qstr *name, struct dentry *dir, unsigned int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namei.c (ffffffff81332d50)
Location: fs/namei.c:1488
Inline: False
Direct callers:
  - fs/namei.c:lookup_one_len_unlocked
  - fs/namei.c:lookup_one_len
  - fs/namei.c:try_lookup_one_len
  - fs/namei.c:__lookup_hash
```
**Symbols:**

```
ffffffff81332d50-ffffffff81332db6: lookup_dcache (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
struct dentry *lookup_dcache(const struct qstr *name, struct dentry *dir, unsigned int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namei.c (ffffffff813804e0)
Location: fs/namei.c:1516
Inline: False
Direct callers:
  - fs/namei.c:lookup_one_len_unlocked
  - fs/namei.c:lookup_one
  - fs/namei.c:lookup_one_len
  - fs/namei.c:try_lookup_one_len
  - fs/namei.c:__lookup_hash
```
**Symbols:**

```
ffffffff813804e0-ffffffff81380546: lookup_dcache (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
struct dentry *lookup_dcache(const struct qstr *name, struct dentry *dir, unsigned int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namei.c (ffffffff81400570)
Location: fs/namei.c:1562
Inline: False
Direct callers:
  - fs/namei.c:lookup_one_len_unlocked
  - fs/namei.c:lookup_one
  - fs/namei.c:lookup_one_len
  - fs/namei.c:try_lookup_one_len
  - fs/namei.c:__lookup_hash
```
**Symbols:**

```
ffffffff81400570-ffffffff814005de: lookup_dcache (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
struct dentry *lookup_dcache(const struct qstr *name, struct dentry *dir, unsigned int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namei.c (ffffffff8148a5e0)
Location: fs/namei.c:1559
Inline: False
Direct callers:
  - fs/namei.c:lookup_one_len_unlocked
  - fs/namei.c:lookup_one
  - fs/namei.c:lookup_one_len
  - fs/namei.c:try_lookup_one_len
  - fs/namei.c:__lookup_hash
```
**Symbols:**

```
ffffffff8148a5e0-ffffffff8148a64e: lookup_dcache (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
struct dentry *lookup_dcache(const struct qstr *name, struct dentry *dir, unsigned int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namei.c (ffffffff814bfe20)
Location: fs/namei.c:1562
Inline: False
Direct callers:
  - fs/namei.c:lookup_one_len_unlocked
  - fs/namei.c:lookup_one
  - fs/namei.c:lookup_one_len
  - fs/namei.c:try_lookup_one_len
  - fs/namei.c:lookup_one_qstr_excl
```
**Symbols:**

```
ffffffff814bfe20-ffffffff814bfe8e: lookup_dcache (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
struct dentry *lookup_dcache(const struct qstr *name, struct dentry *dir, unsigned int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namei.c (ffffffff814f2340)
Location: fs/namei.c:1565
Inline: False
Direct callers:
  - fs/namei.c:lookup_one_len_unlocked
  - fs/namei.c:lookup_one
  - fs/namei.c:lookup_one_len
  - fs/namei.c:try_lookup_one_len
  - fs/namei.c:lookup_one_qstr_excl
```
**Symbols:**

```
ffffffff814f2340-ffffffff814f23ae: lookup_dcache (STB_LOCAL)
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
struct dentry *lookup_dcache(const struct qstr *name, struct dentry *dir, unsigned int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namei.c (ffff8000103931c0)
Location: fs/namei.c:1497
Inline: False
Direct callers:
  - fs/namei.c:lookup_one_len_unlocked
  - fs/namei.c:lookup_one_len
  - fs/namei.c:try_lookup_one_len
  - fs/namei.c:__lookup_hash
```
**Symbols:**

```
ffff8000103931c0-ffff800010393250: lookup_dcache (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
struct dentry *lookup_dcache(const struct qstr *name, struct dentry *dir, unsigned int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namei.c (c057a2a0)
Location: fs/namei.c:1497
Inline: False
Direct callers:
  - fs/namei.c:lookup_one_len_unlocked
  - fs/namei.c:lookup_one_len
  - fs/namei.c:try_lookup_one_len
  - fs/namei.c:__lookup_hash
```
**Symbols:**

```
c057a2a0-c057a31c: lookup_dcache (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
struct dentry *lookup_dcache(const struct qstr *name, struct dentry *dir, unsigned int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namei.c (c00000000048c8e0)
Location: fs/namei.c:1497
Inline: False
Direct callers:
  - fs/namei.c:lookup_one_len_unlocked
  - fs/namei.c:lookup_one_len
  - fs/namei.c:try_lookup_one_len
  - fs/namei.c:__lookup_hash
```
**Symbols:**

```
c00000000048c8e0-c00000000048c9b0: lookup_dcache (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
struct dentry *lookup_dcache(const struct qstr *name, struct dentry *dir, unsigned int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namei.c (ffffffe000262252)
Location: fs/namei.c:1497
Inline: False
Direct callers:
  - fs/namei.c:lookup_one_len_unlocked
  - fs/namei.c:lookup_one_len
  - fs/namei.c:try_lookup_one_len
  - fs/namei.c:__lookup_hash
```
**Symbols:**

```
ffffffe000262252-ffffffe0002622c0: lookup_dcache (STB_LOCAL)
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
struct dentry *lookup_dcache(const struct qstr *name, struct dentry *dir, unsigned int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namei.c (ffffffff812e2290)
Location: fs/namei.c:1497
Inline: False
Direct callers:
  - fs/namei.c:lookup_one_len_unlocked
  - fs/namei.c:lookup_one_len
  - fs/namei.c:try_lookup_one_len
  - fs/namei.c:__lookup_hash
```
**Symbols:**

```
ffffffff812e2290-ffffffff812e22f6: lookup_dcache (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
struct dentry *lookup_dcache(const struct qstr *name, struct dentry *dir, unsigned int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namei.c (ffffffff812d2ed0)
Location: fs/namei.c:1497
Inline: False
Direct callers:
  - fs/namei.c:lookup_one_len_unlocked
  - fs/namei.c:lookup_one_len
  - fs/namei.c:try_lookup_one_len
  - fs/namei.c:__lookup_hash
```
**Symbols:**

```
ffffffff812d2ed0-ffffffff812d2f36: lookup_dcache (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
struct dentry *lookup_dcache(const struct qstr *name, struct dentry *dir, unsigned int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namei.c (ffffffff812e00a0)
Location: fs/namei.c:1497
Inline: False
Direct callers:
  - fs/namei.c:lookup_one_len_unlocked
  - fs/namei.c:lookup_one_len
  - fs/namei.c:try_lookup_one_len
  - fs/namei.c:__lookup_hash
```
**Symbols:**

```
ffffffff812e00a0-ffffffff812e0106: lookup_dcache (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
struct dentry *lookup_dcache(const struct qstr *name, struct dentry *dir, unsigned int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namei.c (ffffffff812f1900)
Location: fs/namei.c:1497
Inline: False
Direct callers:
  - fs/namei.c:lookup_one_len_unlocked
  - fs/namei.c:lookup_one_len
  - fs/namei.c:try_lookup_one_len
  - fs/namei.c:__lookup_hash
```
**Symbols:**

```
ffffffff812f1900-ffffffff812f1966: lookup_dcache (STB_LOCAL)
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
<b>Param removed. </b>
<code>bool *need_lookup</code>
</li>
<li>
<b>Param type changed. </b>
<code>struct qstr *name</code> ➡️ <code>const struct qstr *name</code>
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
