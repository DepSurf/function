# Function: <code>__lookup_slow</code>

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
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
struct dentry *__lookup_slow(const struct qstr *name, struct dentry *dir, unsigned int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namei.c (ffffffff812a7020)
Location: fs/namei.c:1601
Inline: False
Direct callers:
  - fs/namei.c:lookup_one_len
  - fs/namei.c:lookup_slow
```
**Symbols:**

```
ffffffff812a7020-ffffffff812a716d: __lookup_slow (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
struct dentry *__lookup_slow(const struct qstr *name, struct dentry *dir, unsigned int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namei.c (ffffffff812bc240)
Location: fs/namei.c:1642
Inline: False
Direct callers:
  - fs/namei.c:lookup_one_len
  - fs/namei.c:lookup_slow
```
**Symbols:**

```
ffffffff812bc240-ffffffff812bc38d: __lookup_slow (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
struct dentry *__lookup_slow(const struct qstr *name, struct dentry *dir, unsigned int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namei.c (ffffffff812d8cd0)
Location: fs/namei.c:1640
Inline: False
Direct callers:
  - fs/namei.c:lookup_one_len
  - fs/namei.c:lookup_slow
```
**Symbols:**

```
ffffffff812d8cd0-ffffffff812d8e2c: __lookup_slow (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
struct dentry *__lookup_slow(const struct qstr *name, struct dentry *dir, unsigned int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namei.c (ffffffff812ea7e0)
Location: fs/namei.c:1635
Inline: False
Direct callers:
  - fs/namei.c:lookup_one_len
  - fs/namei.c:lookup_slow
```
**Symbols:**

```
ffffffff812ea7e0-ffffffff812ea93c: __lookup_slow (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
struct dentry *__lookup_slow(const struct qstr *name, struct dentry *dir, unsigned int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namei.c (ffffffff81322870)
Location: fs/namei.c:1517
Inline: False
Direct callers:
  - fs/namei.c:lookup_one_len_unlocked
  - fs/namei.c:lookup_one_len
  - fs/namei.c:walk_component
```
**Symbols:**

```
ffffffff81322870-ffffffff813229b7: __lookup_slow (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
struct dentry *__lookup_slow(const struct qstr *name, struct dentry *dir, unsigned int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namei.c (ffffffff8132de10)
Location: fs/namei.c:1517
Inline: False
Direct callers:
  - fs/namei.c:lookup_one_len_unlocked
  - fs/namei.c:lookup_one_len
  - fs/namei.c:walk_component
```
**Symbols:**

```
ffffffff8132de10-ffffffff8132df57: __lookup_slow (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
struct dentry *__lookup_slow(const struct qstr *name, struct dentry *dir, unsigned int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namei.c (ffffffff81333f20)
Location: fs/namei.c:1602
Inline: False
Direct callers:
  - fs/namei.c:lookup_one_len_unlocked
  - fs/namei.c:lookup_one_len
  - fs/namei.c:walk_component
```
**Symbols:**

```
ffffffff81333f20-ffffffff81334067: __lookup_slow (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
struct dentry *__lookup_slow(const struct qstr *name, struct dentry *dir, unsigned int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namei.c (ffffffff81381870)
Location: fs/namei.c:1630
Inline: False
Direct callers:
  - fs/namei.c:lookup_one_len_unlocked
  - fs/namei.c:lookup_one
  - fs/namei.c:lookup_one_len
  - fs/namei.c:walk_component
```
**Symbols:**

```
ffffffff81381870-ffffffff813819b7: __lookup_slow (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
struct dentry *__lookup_slow(const struct qstr *name, struct dentry *dir, unsigned int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namei.c (ffffffff814008b0)
Location: fs/namei.c:1676
Inline: False
Direct callers:
  - fs/namei.c:lookup_one_len_unlocked
  - fs/namei.c:lookup_one
  - fs/namei.c:lookup_one_len
  - fs/namei.c:walk_component
```
**Symbols:**

```
ffffffff814008b0-ffffffff81400a00: __lookup_slow (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
struct dentry *__lookup_slow(const struct qstr *name, struct dentry *dir, unsigned int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namei.c (ffffffff8148a720)
Location: fs/namei.c:1658
Inline: False
Direct callers:
  - fs/namei.c:lookup_one_len_unlocked
  - fs/namei.c:lookup_one
  - fs/namei.c:lookup_one_len
  - fs/namei.c:walk_component
```
**Symbols:**

```
ffffffff8148a720-ffffffff8148a84a: __lookup_slow (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
struct dentry *__lookup_slow(const struct qstr *name, struct dentry *dir, unsigned int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namei.c (ffffffff814c05d0)
Location: fs/namei.c:1663
Inline: False
Direct callers:
  - fs/namei.c:lookup_one_len_unlocked
  - fs/namei.c:lookup_one
  - fs/namei.c:lookup_one_len
  - fs/namei.c:walk_component
```
**Symbols:**

```
ffffffff814c05d0-ffffffff814c06fa: __lookup_slow (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
struct dentry *__lookup_slow(const struct qstr *name, struct dentry *dir, unsigned int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namei.c (ffffffff814f2ab0)
Location: fs/namei.c:1666
Inline: False
Direct callers:
  - fs/namei.c:lookup_one_len_unlocked
  - fs/namei.c:lookup_one
  - fs/namei.c:lookup_one_len
  - fs/namei.c:walk_component
```
**Symbols:**

```
ffffffff814f2ab0-ffffffff814f2bda: __lookup_slow (STB_LOCAL)
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
struct dentry *__lookup_slow(const struct qstr *name, struct dentry *dir, unsigned int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namei.c (ffff800010393e30)
Location: fs/namei.c:1635
Inline: False
Direct callers:
  - fs/namei.c:lookup_one_len
  - fs/namei.c:lookup_slow
```
**Symbols:**

```
ffff800010393e30-ffff800010393fd4: __lookup_slow (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
struct dentry *__lookup_slow(const struct qstr *name, struct dentry *dir, unsigned int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namei.c (c057a7dc)
Location: fs/namei.c:1635
Inline: False
Direct callers:
  - fs/namei.c:lookup_one_len
  - fs/namei.c:lookup_slow
```
**Symbols:**

```
c057a7dc-c057a94c: __lookup_slow (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
struct dentry *__lookup_slow(const struct qstr *name, struct dentry *dir, unsigned int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namei.c (c00000000048d610)
Location: fs/namei.c:1635
Inline: False
Direct callers:
  - fs/namei.c:lookup_one_len
  - fs/namei.c:lookup_slow
```
**Symbols:**

```
c00000000048d610-c00000000048d864: __lookup_slow (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
struct dentry *__lookup_slow(const struct qstr *name, struct dentry *dir, unsigned int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namei.c (ffffffe000262ae4)
Location: fs/namei.c:1635
Inline: False
Direct callers:
  - fs/namei.c:lookup_one_len
  - fs/namei.c:lookup_slow
```
**Symbols:**

```
ffffffe000262ae4-ffffffe000262c38: __lookup_slow (STB_LOCAL)
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
struct dentry *__lookup_slow(const struct qstr *name, struct dentry *dir, unsigned int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namei.c (ffffffff812e2dc0)
Location: fs/namei.c:1635
Inline: False
Direct callers:
  - fs/namei.c:lookup_one_len
  - fs/namei.c:lookup_slow
```
**Symbols:**

```
ffffffff812e2dc0-ffffffff812e2f1c: __lookup_slow (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
struct dentry *__lookup_slow(const struct qstr *name, struct dentry *dir, unsigned int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namei.c (ffffffff812d3a00)
Location: fs/namei.c:1635
Inline: False
Direct callers:
  - fs/namei.c:lookup_one_len
  - fs/namei.c:lookup_slow
```
**Symbols:**

```
ffffffff812d3a00-ffffffff812d3b5c: __lookup_slow (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
struct dentry *__lookup_slow(const struct qstr *name, struct dentry *dir, unsigned int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namei.c (ffffffff812e0bd0)
Location: fs/namei.c:1635
Inline: False
Direct callers:
  - fs/namei.c:lookup_one_len
  - fs/namei.c:lookup_slow
```
**Symbols:**

```
ffffffff812e0bd0-ffffffff812e0d2c: __lookup_slow (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
struct dentry *__lookup_slow(const struct qstr *name, struct dentry *dir, unsigned int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namei.c (ffffffff812f2420)
Location: fs/namei.c:1635
Inline: False
Direct callers:
  - fs/namei.c:lookup_one_len
  - fs/namei.c:lookup_slow
```
**Symbols:**

```
ffffffff812f2420-ffffffff812f257a: __lookup_slow (STB_LOCAL)
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
