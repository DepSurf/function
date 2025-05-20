# Function: <code>__sync_filesystem</code>

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
In fs/sync.c (ffffffff8124071f)
Location: fs/sync.c:30
Inline: True
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
In fs/sync.c (ffffffff81268a61)
Location: fs/sync.c:30
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int __sync_filesystem(struct super_block *sb, int wait);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/sync.c (ffffffff8127b7a0)
Location: fs/sync.c:30
Inline: False
```
**Symbols:**

```
ffffffff8127b7a0-ffffffff8127b7f0: __sync_filesystem (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int __sync_filesystem(struct super_block *sb, int wait);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/sync.c (ffffffff81288b30)
Location: fs/sync.c:30
Inline: False
```
**Symbols:**

```
ffffffff81288b30-ffffffff81288b80: __sync_filesystem (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int __sync_filesystem(struct super_block *sb, int wait);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/sync.c (ffffffff812ab660)
Location: fs/sync.c:31
Inline: False
```
**Symbols:**

```
ffffffff812ab660-ffffffff812ab6b3: __sync_filesystem (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int __sync_filesystem(struct super_block *sb, int wait);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/sync.c (ffffffff812d22d0)
Location: fs/sync.c:31
Inline: False
```
**Symbols:**

```
ffffffff812d22d0-ffffffff812d2323: __sync_filesystem (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int __sync_filesystem(struct super_block *sb, int wait);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/sync.c (ffffffff812e76b0)
Location: fs/sync.c:31
Inline: False
```
**Symbols:**

```
ffffffff812e76b0-ffffffff812e7703: __sync_filesystem (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int __sync_filesystem(struct super_block *sb, int wait);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/sync.c (ffffffff81305f60)
Location: fs/sync.c:31
Inline: False
```
**Symbols:**

```
ffffffff81305f60-ffffffff81305fb3: __sync_filesystem (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int __sync_filesystem(struct super_block *sb, int wait);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/sync.c (ffffffff81318fe0)
Location: fs/sync.c:31
Inline: False
```
**Symbols:**

```
ffffffff81318fe0-ffffffff81319033: __sync_filesystem (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
int __sync_filesystem(struct super_block *sb, int wait);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/sync.c (ffffffff81352c50)
Location: fs/sync.c:31
Inline: True
```
**Symbols:**

```
ffffffff81352c50-ffffffff81352ca3: __sync_filesystem (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
int __sync_filesystem(struct super_block *sb, int wait);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/sync.c (ffffffff8135f530)
Location: fs/sync.c:31
Inline: True
```
**Symbols:**

```
ffffffff8135f530-ffffffff8135f583: __sync_filesystem (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/sync.c (ffffffff813661f4)
Location: fs/sync.c:31
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
int __sync_filesystem(struct super_block *sb, int wait);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/sync.c (ffffffff813b505e)
Location: fs/sync.c:31
Inline: True
Inline callers:
  - fs/sync.c:__ia32_sys_syncfs
  - fs/sync.c:__ia32_sys_syncfs
  - fs/sync.c:__x64_sys_syncfs
  - fs/sync.c:__x64_sys_syncfs
```
**Symbols:**

```
ffffffff813b4910-ffffffff813b4963: __sync_filesystem (STB_GLOBAL)
```
</details>
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
<summary>In <code>arm64</code>: ✅</summary>

```c
int __sync_filesystem(struct super_block *sb, int wait);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/sync.c (ffff8000103cff80)
Location: fs/sync.c:31
Inline: False
```
**Symbols:**

```
ffff8000103cff80-ffff8000103cffe8: __sync_filesystem (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int __sync_filesystem(struct super_block *sb, int wait);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/sync.c (c05ab320)
Location: fs/sync.c:31
Inline: False
```
**Symbols:**

```
c05ab320-c05ab37c: __sync_filesystem (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int __sync_filesystem(struct super_block *sb, int wait);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/sync.c (c0000000004d24b0)
Location: fs/sync.c:31
Inline: False
```
**Symbols:**

```
c0000000004d24b0-c0000000004d2550: __sync_filesystem (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int __sync_filesystem(struct super_block *sb, int wait);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/sync.c (ffffffe00028c2ce)
Location: fs/sync.c:31
Inline: False
```
**Symbols:**

```
ffffffe00028c2ce-ffffffe00028c328: __sync_filesystem (STB_GLOBAL)
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
int __sync_filesystem(struct super_block *sb, int wait);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/sync.c (ffffffff813115c0)
Location: fs/sync.c:31
Inline: False
```
**Symbols:**

```
ffffffff813115c0-ffffffff81311613: __sync_filesystem (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int __sync_filesystem(struct super_block *sb, int wait);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/sync.c (ffffffff813021d0)
Location: fs/sync.c:31
Inline: False
```
**Symbols:**

```
ffffffff813021d0-ffffffff81302223: __sync_filesystem (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int __sync_filesystem(struct super_block *sb, int wait);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/sync.c (ffffffff8130f3b0)
Location: fs/sync.c:31
Inline: False
```
**Symbols:**

```
ffffffff8130f3b0-ffffffff8130f403: __sync_filesystem (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int __sync_filesystem(struct super_block *sb, int wait);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/sync.c (ffffffff81320bb0)
Location: fs/sync.c:31
Inline: False
```
**Symbols:**

```
ffffffff81320bb0-ffffffff81320c03: __sync_filesystem (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
