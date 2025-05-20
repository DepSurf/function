# Function: <code>__d_move</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void __d_move(struct dentry *dentry, struct dentry *target, bool exchange);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/dcache.c (ffffffff81224780)
Location: fs/dcache.c:2591
Inline: False
Direct callers:
  - fs/dcache.c:d_move
  - fs/dcache.c:d_splice_alias
  - fs/dcache.c:d_splice_alias
  - fs/dcache.c:d_splice_alias
  - fs/dcache.c:d_exchange
```
**Symbols:**

```
ffffffff81224780-ffffffff81224c78: __d_move (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void __d_move(struct dentry *dentry, struct dentry *target, bool exchange);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/dcache.c (ffffffff8124c960)
Location: fs/dcache.c:2761
Inline: False
Direct callers:
  - fs/dcache.c:d_splice_alias
  - fs/dcache.c:d_splice_alias
  - fs/dcache.c:d_splice_alias
  - fs/dcache.c:d_exchange
  - fs/dcache.c:d_move
```
**Symbols:**

```
ffffffff8124c960-ffffffff8124ce7d: __d_move (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void __d_move(struct dentry *dentry, struct dentry *target, bool exchange);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/dcache.c (ffffffff8125f950)
Location: fs/dcache.c:2770
Inline: False
Direct callers:
  - fs/dcache.c:d_splice_alias
  - fs/dcache.c:d_splice_alias
  - fs/dcache.c:d_splice_alias
  - fs/dcache.c:d_exchange
  - fs/dcache.c:d_move
```
**Symbols:**

```
ffffffff8125f950-ffffffff8125fe6d: __d_move (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void __d_move(struct dentry *dentry, struct dentry *target, bool exchange);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/dcache.c (ffffffff8126d2a0)
Location: fs/dcache.c:2800
Inline: False
Direct callers:
  - fs/dcache.c:d_splice_alias
  - fs/dcache.c:d_splice_alias
  - fs/dcache.c:d_splice_alias
  - fs/dcache.c:d_exchange
  - fs/dcache.c:d_move
```
**Symbols:**

```
ffffffff8126d2a0-ffffffff8126d7d2: __d_move (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void __d_move(struct dentry *dentry, struct dentry *target, bool exchange);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/dcache.c (ffffffff8128fbc0)
Location: fs/dcache.c:2810
Inline: False
Direct callers:
  - fs/dcache.c:d_splice_alias
  - fs/dcache.c:d_splice_alias
  - fs/dcache.c:d_splice_alias
  - fs/dcache.c:d_exchange
  - fs/dcache.c:d_move
```
**Symbols:**

```
ffffffff8128fbc0-ffffffff812900fb: __d_move (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void __d_move(struct dentry *dentry, struct dentry *target, bool exchange);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/dcache.c (ffffffff812b5610)
Location: fs/dcache.c:2779
Inline: False
Direct callers:
  - fs/dcache.c:d_exchange
  - fs/dcache.c:d_move
```
**Symbols:**

```
ffffffff812b5610-ffffffff812b5aa2: __d_move (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void __d_move(struct dentry *dentry, struct dentry *target, bool exchange);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/dcache.c (ffffffff812ca930)
Location: fs/dcache.c:2733
Inline: False
Direct callers:
  - fs/dcache.c:d_exchange
  - fs/dcache.c:d_move
```
**Symbols:**

```
ffffffff812ca930-ffffffff812cadb8: __d_move (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
void __d_move(struct dentry *dentry, struct dentry *target, bool exchange);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/dcache.c (0)
Location: fs/dcache.c:2803
Inline: False
Direct callers:
  - fs/dcache.c:d_splice_alias
  - fs/dcache.c:d_splice_alias
  - fs/dcache.c:d_splice_alias
  - fs/dcache.c:d_exchange
  - fs/dcache.c:d_move
```
**Symbols:**

```
ffffffff812e7350-ffffffff812e77a4: __d_move (STB_LOCAL)
ffffffff812e9d81-ffffffff812e9dba: __d_move.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void __d_move(struct dentry *dentry, struct dentry *target, bool exchange);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/dcache.c (ffffffff812f8ec0)
Location: fs/dcache.c:2803
Inline: False
Direct callers:
  - fs/dcache.c:d_splice_alias
  - fs/dcache.c:d_splice_alias
  - fs/dcache.c:d_splice_alias
  - fs/dcache.c:d_exchange
  - fs/dcache.c:d_move
```
**Symbols:**

```
ffffffff812f8ec0-ffffffff812f933b: __d_move (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void __d_move(struct dentry *dentry, struct dentry *target, bool exchange);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/dcache.c (ffffffff81331e80)
Location: fs/dcache.c:2824
Inline: False
Direct callers:
  - fs/dcache.c:d_splice_alias
  - fs/dcache.c:d_splice_alias
  - fs/dcache.c:d_splice_alias
  - fs/dcache.c:d_exchange
  - fs/dcache.c:d_move
```
**Symbols:**

```
ffffffff81331e80-ffffffff813322ec: __d_move (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void __d_move(struct dentry *dentry, struct dentry *target, bool exchange);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/dcache.c (ffffffff8133d8a0)
Location: fs/dcache.c:2831
Inline: False
Direct callers:
  - fs/dcache.c:d_splice_alias
  - fs/dcache.c:d_splice_alias
  - fs/dcache.c:d_splice_alias
  - fs/dcache.c:d_exchange
  - fs/dcache.c:d_move
```
**Symbols:**

```
ffffffff8133d8a0-ffffffff8133dd0f: __d_move (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void __d_move(struct dentry *dentry, struct dentry *target, bool exchange);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/dcache.c (ffffffff81343ba0)
Location: fs/dcache.c:2858
Inline: False
Direct callers:
  - fs/dcache.c:d_splice_alias
  - fs/dcache.c:d_splice_alias
  - fs/dcache.c:d_splice_alias
  - fs/dcache.c:d_exchange
  - fs/dcache.c:d_move
```
**Symbols:**

```
ffffffff81343ba0-ffffffff81344005: __d_move (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void __d_move(struct dentry *dentry, struct dentry *target, bool exchange);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/dcache.c (ffffffff813914d0)
Location: fs/dcache.c:2859
Inline: False
Direct callers:
  - fs/dcache.c:d_splice_alias
  - fs/dcache.c:d_splice_alias
  - fs/dcache.c:d_splice_alias
  - fs/dcache.c:d_exchange
  - fs/dcache.c:d_move
```
**Symbols:**

```
ffffffff813914d0-ffffffff81391935: __d_move (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void __d_move(struct dentry *dentry, struct dentry *target, bool exchange);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/dcache.c (ffffffff81413470)
Location: fs/dcache.c:2884
Inline: False
Direct callers:
  - fs/dcache.c:d_splice_alias
  - fs/dcache.c:d_splice_alias
  - fs/dcache.c:d_splice_alias
  - fs/dcache.c:d_exchange
  - fs/dcache.c:d_move
```
**Symbols:**

```
ffffffff81413470-ffffffff8141386c: __d_move (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void __d_move(struct dentry *dentry, struct dentry *target, bool exchange);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/dcache.c (ffffffff8149e8a0)
Location: fs/dcache.c:2939
Inline: False
Direct callers:
  - fs/dcache.c:d_splice_alias
  - fs/dcache.c:d_splice_alias
  - fs/dcache.c:d_splice_alias
  - fs/dcache.c:d_exchange
  - fs/dcache.c:d_move
```
**Symbols:**

```
ffffffff8149e8a0-ffffffff8149ec4a: __d_move (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void __d_move(struct dentry *dentry, struct dentry *target, bool exchange);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/dcache.c (ffffffff814d3bc0)
Location: fs/dcache.c:2939
Inline: False
Direct callers:
  - fs/dcache.c:d_splice_alias
  - fs/dcache.c:d_splice_alias
  - fs/dcache.c:d_splice_alias
  - fs/dcache.c:d_exchange
  - fs/dcache.c:d_move
```
**Symbols:**

```
ffffffff814d3bc0-ffffffff814d3f6a: __d_move (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void __d_move(struct dentry *dentry, struct dentry *target, bool exchange);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/dcache.c (ffffffff81506270)
Location: fs/dcache.c:2763
Inline: False
Direct callers:
  - fs/dcache.c:d_splice_alias
  - fs/dcache.c:d_splice_alias
  - fs/dcache.c:d_splice_alias
  - fs/dcache.c:d_exchange
  - fs/dcache.c:d_move
```
**Symbols:**

```
ffffffff81506270-ffffffff81506641: __d_move (STB_LOCAL)
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
void __d_move(struct dentry *dentry, struct dentry *target, bool exchange);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/dcache.c (ffff8000103a8188)
Location: fs/dcache.c:2803
Inline: False
Direct callers:
  - fs/dcache.c:d_splice_alias
  - fs/dcache.c:d_splice_alias
  - fs/dcache.c:d_splice_alias
  - fs/dcache.c:d_exchange
  - fs/dcache.c:d_move
```
**Symbols:**

```
ffff8000103a8188-ffff8000103a87d0: __d_move (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void __d_move(struct dentry *dentry, struct dentry *target, bool exchange);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/dcache.c (c0588fb4)
Location: fs/dcache.c:2803
Inline: False
Direct callers:
  - fs/dcache.c:d_splice_alias
  - fs/dcache.c:d_splice_alias
  - fs/dcache.c:d_splice_alias
  - fs/dcache.c:d_exchange
  - fs/dcache.c:d_move
```
**Symbols:**

```
c0588fb4-c0589538: __d_move (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void __d_move(struct dentry *dentry, struct dentry *target, bool exchange);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/dcache.c (c0000000004a1a10)
Location: fs/dcache.c:2803
Inline: False
Direct callers:
  - fs/dcache.c:d_splice_alias
  - fs/dcache.c:d_splice_alias
  - fs/dcache.c:d_splice_alias
  - fs/dcache.c:d_exchange
  - fs/dcache.c:d_move
```
**Symbols:**

```
c0000000004a1a10-c0000000004a2084: __d_move (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void __d_move(struct dentry *dentry, struct dentry *target, bool exchange);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/dcache.c (ffffffe00026d9da)
Location: fs/dcache.c:2803
Inline: False
Direct callers:
  - fs/dcache.c:d_splice_alias
  - fs/dcache.c:d_splice_alias
  - fs/dcache.c:d_splice_alias
  - fs/dcache.c:d_exchange
  - fs/dcache.c:d_move
```
**Symbols:**

```
ffffffe00026d9da-ffffffe00026de6a: __d_move (STB_LOCAL)
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
void __d_move(struct dentry *dentry, struct dentry *target, bool exchange);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/dcache.c (ffffffff812f14a0)
Location: fs/dcache.c:2803
Inline: False
Direct callers:
  - fs/dcache.c:d_splice_alias
  - fs/dcache.c:d_splice_alias
  - fs/dcache.c:d_splice_alias
  - fs/dcache.c:d_exchange
  - fs/dcache.c:d_move
```
**Symbols:**

```
ffffffff812f14a0-ffffffff812f191b: __d_move (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void __d_move(struct dentry *dentry, struct dentry *target, bool exchange);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/dcache.c (ffffffff812e20d0)
Location: fs/dcache.c:2803
Inline: False
Direct callers:
  - fs/dcache.c:d_splice_alias
  - fs/dcache.c:d_splice_alias
  - fs/dcache.c:d_splice_alias
  - fs/dcache.c:d_exchange
  - fs/dcache.c:d_move
```
**Symbols:**

```
ffffffff812e20d0-ffffffff812e254b: __d_move (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void __d_move(struct dentry *dentry, struct dentry *target, bool exchange);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/dcache.c (ffffffff812ef2b0)
Location: fs/dcache.c:2803
Inline: False
Direct callers:
  - fs/dcache.c:d_splice_alias
  - fs/dcache.c:d_splice_alias
  - fs/dcache.c:d_splice_alias
  - fs/dcache.c:d_exchange
  - fs/dcache.c:d_move
```
**Symbols:**

```
ffffffff812ef2b0-ffffffff812ef72b: __d_move (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void __d_move(struct dentry *dentry, struct dentry *target, bool exchange);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/dcache.c (ffffffff813005c0)
Location: fs/dcache.c:2803
Inline: False
Direct callers:
  - fs/dcache.c:d_splice_alias
  - fs/dcache.c:d_splice_alias
  - fs/dcache.c:d_splice_alias
  - fs/dcache.c:d_exchange
  - fs/dcache.c:d_move
```
**Symbols:**

```
ffffffff813005c0-ffffffff81300a38: __d_move (STB_LOCAL)
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
