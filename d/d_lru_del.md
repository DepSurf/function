# Function: <code>d_lru_del</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline ⚠️</summary>

```c
void d_lru_del(struct dentry *dentry);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/dcache.c (ffffffff812231f0)
Location: fs/dcache.c:398
Inline: True
Direct callers:
  - fs/dcache.c:select_collect
  - fs/dcache.c:__dentry_kill
```
**Symbols:**

```
ffffffff812231f0-ffffffff81223284: d_lru_del (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
void d_lru_del(struct dentry *dentry);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/dcache.c (ffffffff8124b010)
Location: fs/dcache.c:369
Inline: True
Direct callers:
  - fs/dcache.c:select_collect
  - fs/dcache.c:__dentry_kill
```
**Symbols:**

```
ffffffff8124b010-ffffffff8124b0a4: d_lru_del (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
void d_lru_del(struct dentry *dentry);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/dcache.c (ffffffff8125e000)
Location: fs/dcache.c:369
Inline: True
Direct callers:
  - fs/dcache.c:select_collect
  - fs/dcache.c:__dentry_kill
```
**Symbols:**

```
ffffffff8125e000-ffffffff8125e094: d_lru_del (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
void d_lru_del(struct dentry *dentry);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/dcache.c (ffffffff8126b820)
Location: fs/dcache.c:401
Inline: True
Direct callers:
  - fs/dcache.c:__dentry_kill
```
**Symbols:**

```
ffffffff8126b820-ffffffff8126b86f: d_lru_del (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
void d_lru_del(struct dentry *dentry);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/dcache.c (ffffffff8128e0b0)
Location: fs/dcache.c:401
Inline: True
Direct callers:
  - fs/dcache.c:__dentry_kill
```
**Symbols:**

```
ffffffff8128e0b0-ffffffff8128e0ff: d_lru_del (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
void d_lru_del(struct dentry *dentry);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/dcache.c (ffffffff812b4650)
Location: fs/dcache.c:400
Inline: True
Direct callers:
  - fs/dcache.c:__dentry_kill
```
**Symbols:**

```
ffffffff812b4650-ffffffff812b469f: d_lru_del (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
void d_lru_del(struct dentry *dentry);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/dcache.c (ffffffff812c98c0)
Location: fs/dcache.c:407
Inline: True
Direct callers:
  - fs/dcache.c:__dentry_kill
```
**Symbols:**

```
ffffffff812c98c0-ffffffff812c991f: d_lru_del (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
void d_lru_del(struct dentry *dentry);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/dcache.c (ffffffff812e6240)
Location: fs/dcache.c:407
Inline: True
Direct callers:
  - fs/dcache.c:__dentry_kill
```
**Symbols:**

```
ffffffff812e6240-ffffffff812e629f: d_lru_del (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
void d_lru_del(struct dentry *dentry);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/dcache.c (ffffffff812f7c30)
Location: fs/dcache.c:407
Inline: True
Direct callers:
  - fs/dcache.c:select_collect2
  - fs/dcache.c:select_collect
  - fs/dcache.c:__dentry_kill
```
**Symbols:**

```
ffffffff812f7c30-ffffffff812f7c8f: d_lru_del (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void d_lru_del(struct dentry *dentry);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/dcache.c (ffffffff81330760)
Location: fs/dcache.c:407
Inline: False
Direct callers:
  - fs/dcache.c:select_collect2
  - fs/dcache.c:select_collect
  - fs/dcache.c:__dentry_kill
```
**Symbols:**

```
ffffffff81330760-ffffffff813307bf: d_lru_del (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void d_lru_del(struct dentry *dentry);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/dcache.c (ffffffff8133c0d0)
Location: fs/dcache.c:407
Inline: False
Direct callers:
  - fs/dcache.c:select_collect2
  - fs/dcache.c:select_collect
  - fs/dcache.c:__dentry_kill
```
**Symbols:**

```
ffffffff8133c0d0-ffffffff8133c12f: d_lru_del (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void d_lru_del(struct dentry *dentry);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/dcache.c (ffffffff81342560)
Location: fs/dcache.c:409
Inline: False
Direct callers:
  - fs/dcache.c:select_collect2
  - fs/dcache.c:select_collect
  - fs/dcache.c:__dentry_kill
```
**Symbols:**

```
ffffffff81342560-ffffffff813425bf: d_lru_del (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void d_lru_del(struct dentry *dentry);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/dcache.c (ffffffff8138fec0)
Location: fs/dcache.c:409
Inline: False
Direct callers:
  - fs/dcache.c:select_collect2
  - fs/dcache.c:select_collect
  - fs/dcache.c:__dentry_kill
```
**Symbols:**

```
ffffffff8138fec0-ffffffff8138ff1f: d_lru_del (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void d_lru_del(struct dentry *dentry);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/dcache.c (ffffffff81411710)
Location: fs/dcache.c:434
Inline: False
Direct callers:
  - fs/dcache.c:select_collect2
  - fs/dcache.c:select_collect
  - fs/dcache.c:__dentry_kill
```
**Symbols:**

```
ffffffff81411710-ffffffff81411787: d_lru_del (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void d_lru_del(struct dentry *dentry);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/dcache.c (ffffffff8149c1c0)
Location: fs/dcache.c:434
Inline: False
Direct callers:
  - fs/dcache.c:select_collect2
  - fs/dcache.c:select_collect
  - fs/dcache.c:__dentry_kill
```
**Symbols:**

```
ffffffff8149c1c0-ffffffff8149c237: d_lru_del (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void d_lru_del(struct dentry *dentry);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/dcache.c (ffffffff814d1400)
Location: fs/dcache.c:434
Inline: False
Direct callers:
  - fs/dcache.c:select_collect2
  - fs/dcache.c:select_collect
  - fs/dcache.c:__dentry_kill
```
**Symbols:**

```
ffffffff814d1400-ffffffff814d1477: d_lru_del (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void d_lru_del(struct dentry *dentry);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/dcache.c (ffffffff81503b80)
Location: fs/dcache.c:434
Inline: False
Direct callers:
  - fs/dcache.c:to_shrink_list
  - fs/dcache.c:__dentry_kill
```
**Symbols:**

```
ffffffff81503b80-ffffffff81503bf7: d_lru_del (STB_LOCAL)
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
void d_lru_del(struct dentry *dentry);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/dcache.c (ffff8000103a62e8)
Location: fs/dcache.c:407
Inline: False
Direct callers:
  - fs/dcache.c:__dentry_kill
```
**Symbols:**

```
ffff8000103a62e8-ffff8000103a63c4: d_lru_del (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void d_lru_del(struct dentry *dentry);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/dcache.c (c0587348)
Location: fs/dcache.c:407
Inline: False
Direct callers:
  - fs/dcache.c:__dentry_kill
```
**Symbols:**

```
c0587348-c0587458: d_lru_del (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void d_lru_del(struct dentry *dentry);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/dcache.c (c00000000049efc0)
Location: fs/dcache.c:407
Inline: False
Direct callers:
  - fs/dcache.c:__dentry_kill
```
**Symbols:**

```
c00000000049efc0-c00000000049f0e8: d_lru_del (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void d_lru_del(struct dentry *dentry);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/dcache.c (ffffffe00026bfe4)
Location: fs/dcache.c:407
Inline: False
Direct callers:
  - fs/dcache.c:__dentry_kill
```
**Symbols:**

```
ffffffe00026bfe4-ffffffe00026c09c: d_lru_del (STB_LOCAL)
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
void d_lru_del(struct dentry *dentry);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/dcache.c (ffffffff812f0210)
Location: fs/dcache.c:407
Inline: True
Direct callers:
  - fs/dcache.c:select_collect2
  - fs/dcache.c:select_collect
  - fs/dcache.c:__dentry_kill
```
**Symbols:**

```
ffffffff812f0210-ffffffff812f026f: d_lru_del (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
void d_lru_del(struct dentry *dentry);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/dcache.c (ffffffff812e0e40)
Location: fs/dcache.c:407
Inline: True
Direct callers:
  - fs/dcache.c:select_collect2
  - fs/dcache.c:select_collect
  - fs/dcache.c:__dentry_kill
```
**Symbols:**

```
ffffffff812e0e40-ffffffff812e0e9f: d_lru_del (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
void d_lru_del(struct dentry *dentry);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/dcache.c (ffffffff812ee020)
Location: fs/dcache.c:407
Inline: True
Direct callers:
  - fs/dcache.c:select_collect2
  - fs/dcache.c:select_collect
  - fs/dcache.c:__dentry_kill
```
**Symbols:**

```
ffffffff812ee020-ffffffff812ee07f: d_lru_del (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
void d_lru_del(struct dentry *dentry);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/dcache.c (ffffffff812ff4f0)
Location: fs/dcache.c:407
Inline: True
Direct callers:
  - fs/dcache.c:select_collect2
  - fs/dcache.c:select_collect
  - fs/dcache.c:__dentry_kill
```
**Symbols:**

```
ffffffff812ff4f0-ffffffff812ff54f: d_lru_del (STB_LOCAL)
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
