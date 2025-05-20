# Function: <code>lookup_one_len_common</code>

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
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
int lookup_one_len_common(const char *name, struct dentry *base, int len, struct qstr *this);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/namei.c (ffffffff812a7b10)
Location: fs/namei.c:2434
Inline: True
Direct callers:
  - fs/namei.c:lookup_one_len_unlocked
  - fs/namei.c:lookup_one_len
  - fs/namei.c:try_lookup_one_len
```
**Symbols:**

```
ffffffff812a7b10-ffffffff812a7bc7: lookup_one_len_common (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
int lookup_one_len_common(const char *name, struct dentry *base, int len, struct qstr *this);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/namei.c (ffffffff812bcbb0)
Location: fs/namei.c:2458
Inline: True
Direct callers:
  - fs/namei.c:lookup_one_len_unlocked
  - fs/namei.c:lookup_one_len
  - fs/namei.c:try_lookup_one_len
```
**Symbols:**

```
ffffffff812bcbb0-ffffffff812bcc67: lookup_one_len_common (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
int lookup_one_len_common(const char *name, struct dentry *base, int len, struct qstr *this);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/namei.c (ffffffff812d96c0)
Location: fs/namei.c:2456
Inline: True
Direct callers:
  - fs/namei.c:lookup_one_len_unlocked
  - fs/namei.c:lookup_one_len
  - fs/namei.c:try_lookup_one_len
```
**Symbols:**

```
ffffffff812d96c0-ffffffff812d9776: lookup_one_len_common (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
int lookup_one_len_common(const char *name, struct dentry *base, int len, struct qstr *this);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/namei.c (ffffffff812eb1d0)
Location: fs/namei.c:2449
Inline: True
Direct callers:
  - fs/namei.c:lookup_one_len_unlocked
  - fs/namei.c:lookup_one_len
  - fs/namei.c:try_lookup_one_len
```
**Symbols:**

```
ffffffff812eb1d0-ffffffff812eb286: lookup_one_len_common (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int lookup_one_len_common(const char *name, struct dentry *base, int len, struct qstr *this);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namei.c (ffffffff81323e50)
Location: fs/namei.c:2477
Inline: False
Direct callers:
  - fs/namei.c:lookup_one_len_unlocked
  - fs/namei.c:lookup_one_len
  - fs/namei.c:try_lookup_one_len
```
**Symbols:**

```
ffffffff81323e50-ffffffff81323f09: lookup_one_len_common (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int lookup_one_len_common(const char *name, struct dentry *base, int len, struct qstr *this);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namei.c (ffffffff8132f450)
Location: fs/namei.c:2475
Inline: False
Direct callers:
  - fs/namei.c:lookup_one_len_unlocked
  - fs/namei.c:lookup_one_len
  - fs/namei.c:try_lookup_one_len
```
**Symbols:**

```
ffffffff8132f450-ffffffff8132f509: lookup_one_len_common (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int lookup_one_len_common(const char *name, struct dentry *base, int len, struct qstr *this);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namei.c (ffffffff81334b10)
Location: fs/namei.c:2565
Inline: False
Direct callers:
  - fs/namei.c:lookup_one_len_unlocked
  - fs/namei.c:lookup_one_len
  - fs/namei.c:try_lookup_one_len
```
**Symbols:**

```
ffffffff81334b10-ffffffff81334bd0: lookup_one_len_common (STB_LOCAL)
```
</details>
</li>
<li>
In <code>5.15</code>: Absent ⚠️
</li>
<li>
In <code>5.19</code>: Absent ⚠️
</li>
<li>
In <code>6.2</code>: Absent ⚠️
</li>
<li>
In <code>6.5</code>: Absent ⚠️
</li>
<li>
In <code>6.8</code>: Absent ⚠️
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Selective Inline ⚠️</summary>

```c
int lookup_one_len_common(const char *name, struct dentry *base, int len, struct qstr *this);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/namei.c (ffff8000103948f0)
Location: fs/namei.c:2449
Inline: True
Direct callers:
  - fs/namei.c:lookup_one_len_unlocked
  - fs/namei.c:lookup_one_len
  - fs/namei.c:try_lookup_one_len
```
**Symbols:**

```
ffff8000103948f0-ffff8000103949e4: lookup_one_len_common (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
int lookup_one_len_common(const char *name, struct dentry *base, int len, struct qstr *this);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/namei.c (c0579fbc)
Location: fs/namei.c:2449
Inline: True
Direct callers:
  - fs/namei.c:lookup_one_len_unlocked
  - fs/namei.c:lookup_one_len
  - fs/namei.c:try_lookup_one_len
```
**Symbols:**

```
c0579fbc-c057a098: lookup_one_len_common (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
int lookup_one_len_common(const char *name, struct dentry *base, int len, struct qstr *this);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/namei.c (c00000000048b500)
Location: fs/namei.c:2449
Inline: True
Direct callers:
  - fs/namei.c:lookup_one_len_unlocked
  - fs/namei.c:lookup_one_len
  - fs/namei.c:try_lookup_one_len
```
**Symbols:**

```
c00000000048b500-c00000000048b664: lookup_one_len_common (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int lookup_one_len_common(const char *name, struct dentry *base, int len, struct qstr *this);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namei.c (ffffffe00026338c)
Location: fs/namei.c:2449
Inline: False
Direct callers:
  - fs/namei.c:lookup_one_len_unlocked
  - fs/namei.c:lookup_one_len
  - fs/namei.c:try_lookup_one_len
```
**Symbols:**

```
ffffffe00026338c-ffffffe0002634a8: lookup_one_len_common (STB_LOCAL)
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
int lookup_one_len_common(const char *name, struct dentry *base, int len, struct qstr *this);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/namei.c (ffffffff812e37b0)
Location: fs/namei.c:2449
Inline: True
Direct callers:
  - fs/namei.c:lookup_one_len_unlocked
  - fs/namei.c:lookup_one_len
  - fs/namei.c:try_lookup_one_len
```
**Symbols:**

```
ffffffff812e37b0-ffffffff812e3866: lookup_one_len_common (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
int lookup_one_len_common(const char *name, struct dentry *base, int len, struct qstr *this);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/namei.c (ffffffff812d43f0)
Location: fs/namei.c:2449
Inline: True
Direct callers:
  - fs/namei.c:lookup_one_len_unlocked
  - fs/namei.c:lookup_one_len
  - fs/namei.c:try_lookup_one_len
```
**Symbols:**

```
ffffffff812d43f0-ffffffff812d44a6: lookup_one_len_common (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
int lookup_one_len_common(const char *name, struct dentry *base, int len, struct qstr *this);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/namei.c (ffffffff812e15c0)
Location: fs/namei.c:2449
Inline: True
Direct callers:
  - fs/namei.c:lookup_one_len_unlocked
  - fs/namei.c:lookup_one_len
  - fs/namei.c:try_lookup_one_len
```
**Symbols:**

```
ffffffff812e15c0-ffffffff812e1676: lookup_one_len_common (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
int lookup_one_len_common(const char *name, struct dentry *base, int len, struct qstr *this);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/namei.c (ffffffff812f17a0)
Location: fs/namei.c:2449
Inline: True
Direct callers:
  - fs/namei.c:lookup_one_len_unlocked
  - fs/namei.c:lookup_one_len
  - fs/namei.c:try_lookup_one_len
```
**Symbols:**

```
ffffffff812f17a0-ffffffff812f1856: lookup_one_len_common (STB_LOCAL)
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
